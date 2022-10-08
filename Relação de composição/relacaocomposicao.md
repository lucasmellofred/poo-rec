# Relação de composição

![composicaouml](https://user-images.githubusercontent.com/104468335/194683445-60ba197a-0156-4ff2-8a1c-6f55d4d75ec5.png)

```java
public class Pessoa {
  private int idade;
  private String nome;

public Pessoa(int idade, String nome) {
  this.idade = idade;
  this.nome = nome;
  }
}

public class Celular {
  private String modelo;
  private Pessoa dono;

public Celular(Pessoa dono, String modelo) {
  this.dono = dono;
  this.modelo = modelo;
  }
}

public class Main {
  public static void main(String[] args) {
    Pessoa pessoa = new Pessoa("Lucas", 19);
    Celular celular = new Carro("Motorola", pessoa);
    System.out.println(celular);
  }
}
```
