public class Solution {
    public int reverseBits(int n) {
int result = 0;
        for (int i = 0; i < 32; i ++) {
            int a = n & 1; 
            int reversea = a << (31 - i);  
            result = result | reversea;
            n = n >> 1;
        }
        return result;
    }
}
