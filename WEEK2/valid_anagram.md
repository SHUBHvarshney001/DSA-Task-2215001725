```java
class Solution {
    public boolean isAnagram(String s, String t) {
        char n1[]=s.toCharArray();
        char n2[]=t.toCharArray();

        Arrays.sort(n1);
        Arrays.sort(n2);

        s=Arrays.toString(n1);
        t=Arrays.toString(n2);

        if(s.equals(t))
        {
            return true;
        }
        return false;
    }
}
```