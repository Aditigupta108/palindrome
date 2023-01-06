# palindrome
class Solution {
public:
    bool isPalindrome(int x) {
        int m=x;
        long sum=0;
        int r;
        while(x!=0&&x>0){
            r=x%10;
            sum=sum*10+r;
            x=x/10;
        }
        if(sum==m){
            return true;
        }
        else{
            return false;
        }
    }
};
