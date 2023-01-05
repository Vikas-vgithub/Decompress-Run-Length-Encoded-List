class Solution {
    public int[] decompressRLElist(int[] nums) {
        int size = 0;
        int k = 0;
        for(int i=0; i<nums.length; i+=2){
            size += nums[i];
        }
        int [] temp = new int[size];
        for(int i=0; i<nums.length; i+=2){
            for(int j=0; j<nums[i]; j++){
                temp[k++] = nums[i+1];
            }
        }
        return temp;
    }
}
