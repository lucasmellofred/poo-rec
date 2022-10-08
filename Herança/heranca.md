# Herança

![herancauml](https://user-images.githubusercontent.com/104468335/194680426-58d18d93-bc13-4048-aa7f-4a074cb8ef20.png)

```java
public class Pessoa {
  private String nome;
  private int idade;
  private int cpf;
}
  
public class Aluno extends Pessoa {
  private int matricula;
  private double media;
  private String turma;
}
    
public class Professor extends Pessoa {
  private double salario;
  private String turma;
}
```
