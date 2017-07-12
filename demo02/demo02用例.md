```
public class Demo02 {
	public String reverseString(String iniString) {
        // write code her
		String str = "";
		for(int i=0;i<iniString.length();i++){
			str = iniString.charAt(i)+str;
		}
		return str;
		//简单方法
//		StringBuffer str = new StringBuffer(iniString);
//		return str.reverse().toString();
	}
}
```