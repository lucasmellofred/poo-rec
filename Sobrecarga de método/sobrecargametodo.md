# Sobrecarga de método

![sobrecargametodouml](https://user-images.githubusercontent.com/104468335/194682573-3fce1d02-3a02-454f-bc20-fc6d3f23aea6.png)

```java
public class calculadora {
  public String somar(String x, String y) {
      return x + y;
  }
  
  public double somar(double x, double y) {
      return x + y;
  }
    
  public int somar(int x, int y) {
      return x + y;
  }    
}
```
