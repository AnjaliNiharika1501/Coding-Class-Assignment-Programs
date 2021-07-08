class Solution {
   public int[] plusOne(int[] digits) {

      int carry = 1;
      int sum = 0;

      for (int i = digits.length - 1; i >= 0; i--) {
         sum = carry + digits[i];

         if (sum > 9) {
            carry = 1;
            sum = sum % 10;
         } else {
            carry = 0;
         }

         digits[i] = sum;
      }

      if (carry == 1) {
         int[] temp = new int[digits.length + 1];
         temp[0] = carry;

         for (int i = 0; i < digits.length; i++) {
            temp[i + 1] = digits[i];
         }

         return temp;
      }

      return digits;

   }
}
