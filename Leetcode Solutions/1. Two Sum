class Solution {
public:
    vector<int> twoSum(vector<int>& nums, int target) {
        int n = nums.size();
        vector<int>ans;
        unordered_map<int, int>myMap;

        for(int i=0; i<n; i++){
            int search = target - nums[i];

            if(myMap.find(search)==myMap.end()){ // search is not present in map then insert it
                    myMap[nums[i]] = i;
            }
            else{
                ans.push_back(myMap[search]);
                ans.push_back(i);
            }
        }
        return ans;
    }
};
