# Redundant-Braces
1. a program to validate if the input string has redundant braces

int Solution::braces(string A) {
    
        int l=A.size(); stack<char> st;
    for(int i=0;i<l;i++)
    {
        if(A[i]==')')
        {
            char top=st.top();st.pop();
            int count = 0;
            while (top != '(')
            {
                count++;
                top = st.top();
                st.pop();
            }
            if(count <= 1) {
                return 1;
            }
        }
        else
        {
            st.push(A[i]);
        }
    }
    return 0;
    
}

