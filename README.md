# optimised-bubble-sort 



int n=nums.size();
for(int i=0;i<n-1;i++){
bool swapped=true; 
for(int j=0;j<n-i-1;j++){
if(nums[j]>nums[j+1]){
swap(nums[j],nums[j+1]);
swapped=true;}
}
if(!swapped) //we are trying to reduce no of times the loop should run
break;       // this is what optimisation meansb by introducing boolean function
}




