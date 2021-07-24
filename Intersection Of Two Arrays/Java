class Solution {
    public int[] intersection(int[] nums1, int[] nums2) {
        HashSet<Integer> s=new HashSet<>();
        HashSet<Integer> h=new HashSet<>();
        for(int i:nums1){
            s.add(i);
        }
        int count=0;
        for(int i:nums2){
            if(s.contains(i)){
                if(!h.contains(i)){
                    h.add(i);
                    count++;
                }
            }
        }
        int arr[]=new int[count];
        int a=0;
        for(int i:h){
            arr[a]=i;
            a++;
        }
        return arr;
    }
}
