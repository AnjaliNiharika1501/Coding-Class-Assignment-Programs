import java.io.*;
import java.math.*;
import java.security.*;
import java.text.*;
import java.util.*;
import java.util.concurrent.*;
import java.util.regex.*;

public class MegaPrime {
    
    static long next(long x) {
        if (x == 0) {
            return 0;
        }
        long y = x / 10;
        long y1 = next(y + (x % 10 > 7 ? 1 : 0));
        if (y != y1) {
            return 10 * y1 + 2;
        }
        return y1 * 10 + (x % 10 <= 2 ? 2 : x % 10 <= 3 ? 3 : x % 10 <= 5 ? 5 : 7);
    }

    public static void main(String[] args) {
        Scanner in = new Scanner(System.in);
        long first = in.nextLong();
        long last = in.nextLong();
        long ans = 0;
        first = next(first);
        while (first <= last) {
            if (BigInteger.valueOf(first).isProbablePrime(20)) {
                ans++;
            }
            first = next(first + 1);
        }
        System.out.println(ans);
    }
}
