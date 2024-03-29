# Índice 

* [Índice](#índice)
* [Java Pacotes](#java-pacotes)
* [Sobre os pacotes](#sobre-os-pacotes)
* [Modificadores de Acesso](#modificadores-de-acesso)
* [Criar um javadoc](#criar-um-javadoc)
* [Criando uma biblioteca com JAR e criando um executavel JAR](#criando-uma-biblioteca-com-JAR-e-criando-um-executavel-JAR)
* [Pacote java.lang](#pacote-java)
* [Pacote java.lang.object](#pacote-java)
* [Pacote java.io](#pacote-java)
* [Certificações](#certificações)


# Java Pacotes
  
  Seguindo o cronograma de estudo do <a href="https://techguide.sh/pt-BR/path/java/">Tech Guide em Java<a>

 - Um pacote (package) em Java é usado para agrupar classes relacionadas, de forma semelhante a uma pasta em um diretório de arquivos. Os pacotes são usados para evitar conflitos de nomes e para escrever um código de melhor manutenção.
 - Use imports e organize o seu código através de packages
 - Conhecer a java.lang
 - Entender a imutabilidade e a classe String
 - Entender a classe java.lang.Object
 - Conhecer a java.io
  
  
  
  # Sobre os pacotes 
  
  trabalhar com o FQN (Full Qualified Name) que é o nome completo da classe, composto pelo nome do pacote e o nome da classe.
FQN = Nome Pacote . Nome Simples da Classe
  
  os packages:
  
  - Packages são diretórios com significado especial dentro do código fonte Java

  - A palavra chave package deve ser a primeira declaração no código fonte Java.
  
  - Packages servem para organização e agrupar as classes e interfaces.

  
# Modificadores de Acesso
  
| Modificadores de Acesso/Visibilidade |
|--------------------------------------|
| public                               |
| protected                            |
| <<package private>>                  |
| private                              |

  

public:visível em todos os espaços
protected: visível dentro do pacote e público para os filhos
package private: visível apenas dentro do pacote
private: visível apenas dentro da classe
  
  
# Criar um javadoc
  
  
  
 - É preciso ter instalado o JDK para poder gerar a documentação javadoc.
 - O javadoc é uma documentação escrita pelo desenvolvedor para desenvolvedores.
 - Existem tags especias para marcar o autor ou a versão da classe.
  
<img width="1432" alt="Captura de Tela 2023-05-16 às 14 00 32" src="https://github.com/ceerqueira/pacotes/assets/50030996/1826eeb8-41a5-418d-8ce0-32b17f18b737">
  
  
# Criando uma biblioteca com JAR e criando um executavel JAR
  
 - JAR significa  Java ARchive.
 - qualquer biblioteca ou projeto vai usar JAR(s) para distribuir o código.

  <img width="156" alt="Captura de Tela 2023-05-16 às 14 06 55" src="https://github.com/ceerqueira/pacotes/assets/50030996/a4545be2-11ec-4f06-bbb3-79ea124e3fd8">
  
  Exemplos de Jar excecutavel 
  
  ![3_3_26_interface+jar](https://github.com/ceerqueira/pacotes/assets/50030996/496f315c-7c5c-4cd2-acff-b7d1bce99ef1)
  
# Pacote java.lang
  - Não precisa do import, é automaticamente importado.
  - As classes String e System vem desse pacote.
  - classes como Exception, RuntimeException, NullPointerException ou ArithmeticException vem do pacote java.lang.
  
  sobre a classe String e a imutabilidade
   - um conceito fundamental da String: uma vez que foi criada, ela não poderá ser modificada posteriormente. Chamamos o conceito de um objeto não poder ser alterado de imutabilidade. Caso você queira alterar algo em uma String, você terá de criar uma String que refletirá uma nova ação, ou seja, teremos dois objetos.
   - StringBuilder para a contanenação

  
# Pacote java.lang.object
  - A classe Object é a classe raiz do Java
  - Não é preciso herda do Object explicitamente, o compilador automaticamente insere a declaração.
# Pacote java.io
  - A classe InputStream é abstrata, e FileInputStream, uma de suas filhas concretas. FileInputStream procurará o arquivo no diretório em que a JVM fora invocada 
# Certificações 
 <a href="https://cursos.alura.com.br/course/java-pacotes-e-java-lang">Java e java.lang: programe com a classe Object e String<a>
   
  <a href="https://cursos.alura.com.br/certificate/4acf8c94-45f4-4991-9ec3-56a450bb9200">Certificação Victor<a>
  
