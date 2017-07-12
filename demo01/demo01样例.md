```java

public class Demo01 {
	public boolean checkDifferent(String iniString) {
        // write code here
        for(int i=1;i<iniString.length();i++){
        	for(int j=i+1;j<iniString.length();j++){
        		if(iniString.charAt(i)==iniString.charAt(j)){
        			return false;
        		}
        	}
        }
        return true;
    }
}

```