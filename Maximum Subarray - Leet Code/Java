class Solution {
    public int maxSubArray(int[] nums) {
    int max = nums[0];
        int res = nums[0];
        for(int i=1;i<nums.length;i++) {
            if(max+nums[i] > nums[i]) {
                max = max + nums[i];
            } else {
                max = nums[i];
            }
            
            if(max>res) {
                res = max;
            }
        }
        return res;
    }    
}
