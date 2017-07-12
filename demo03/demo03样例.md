```
public class Demo03 {
	public boolean checkSam(String stringA, String stringB) {
        // write code here
        if(stringA.length()!=stringB.length())
        	return false;
        if(stringA==null&&stringB==null)
        	return true;
      
        	int []arrayA = new int[256];
        	int []arrayB = new int[256];
        	for(int i = 0;i<stringA.length();i++){
        		arrayA[stringA.charAt(i)]++;
        		arrayB[stringB.charAt(i)]++;
        	}
        	
        	for(int i=0;i<arrayA.length;i++){
        		if(arrayA[i]!=arrayB[i])
        			return false;
        		
        	}
        	return true;
        }
}
```