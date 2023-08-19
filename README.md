# Single-Number-Leetcode

    class Solution {
    public:
        int singleNumber(vector<int>& nums) {
            int dp=0;
            for(int i=0;i<nums.size();i++){
                dp^=nums[i];
            }
            return dp;
            }
            
        
    };
