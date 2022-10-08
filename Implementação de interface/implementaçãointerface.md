# Implementação de interface

![interfaceuml](https://user-images.githubusercontent.com/104468335/194682330-c19fa348-05bf-4d00-8084-a6e1e55828c4.png)

```java
public class Animal {
  public String nome;
  public String especie;
  public String genero;
}

public interface naoVoador {
  void naoVoa()
}

public interface Andar {
  void estaAndando()
}
  
public class Galinha extends Animal implements naoVoador {
  public String raca;
  
  @Override
  public void naoVoa() {
    System.out.println("A "+ raca + " não voa!!");
  }
}
    
public class Penguim extends Animal implements Andar {
  public String raca;
  
  @Override
  public void estaAndando() {
    System.out.println("A "+ raca + " está andando!!");
  }
}
```
