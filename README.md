# Guia-de-Java
![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![VSCode](https://img.shields.io/badge/Made%20for-VSCode-1f425f.svg)
![GitHub repo size](https://img.shields.io/github/repo-size/deniseflora/Guia-de-Java)
![GitHub](https://img.shields.io/github/license/deniseflora/Guia-de-Java)

## Um Tutorial para Iniciantes

## Introdução a Linguagem Java

📖: 1. [Definição](#id1)  

🏛️: 2. [História](#id2)

🍵: 3. [Instalando o Java Development Kit (JDK)](#id3)

💻: 4. [Configurando o Ambiente de Desenvolvimento](#id4)
  
🖋️: 5. [Editores Java](#id5)

📚:6.  [Fundamentos](#id6)

🔖: 7. [Sintaxe Básica em Java](#id7)

📇: 8. [Identificadores](#id8)

🔑: 9. [Palavras-chave](#id9)

⬅️: 10. [Comentários em Java](#id9) 

🚀:11. [Primeiro Programa](#id10) 


<div id='id1' />
  
 ## 1. Definição
 
Java é uma linguagem de programação orientada a objetos e um conjunto de bibliotecas de classes (frameworks). É uma linguagem de programação de alto nível, robusta, orientada a objetos e segura em que utiliza uma máquina virtual(JVM-Java Virtual Machine) para execução de programas.

  <div id='id2' />
    
## 2. História

**Início (Década de 1990):** A linguagem de programação Java foi criada pela **Sun Microsystems** por uma equipe liderada por **James Gosling**.Inicialmente como parte de um projeto para desenvolver software para aparelhos, como televisões.
 **Java 1.0 (1996):** A primeira versão oficial do Java foi lançada em 1996. Apresentava recursos como classes e objetos, exceções,  e a  **máquina virtual Java (JVM)**, que permitia que os programas Java fossem executados em várias plataformas.
**Java 2 Platform (1998):** O lançamento da Java 2 Platform trouxe várias melhorias, incluindo a adição de bibliotecas de classes como Swing para criar interfaces gráficas de usuário (GUI), bem como a plataforma Enterprise Edition (Java EE) para o desenvolvimento de aplicativos corporativos.
**Open Source (2006):** A Sun Microsystems começou a disponibilizar o código-fonte da implementação de referência da linguagem Java sob a Licença Pública Geral da GNU (GPL), tornando-a mais acessível para a comunidade de desenvolvedores.
**Aquisição pela Oracle (2010):** Em 2010, a **Oracle Corporation** adquiriu a Sun Microsystems, tornando-se a proprietária oficial da linguagem Java.
**Lançamento de versões (periódicas):** A Oracle continuou a desenvolver e lançar novas versões do Java regularmente, trazendo melhorias de desempenho, segurança e funcionalidade. As versões notáveis incluem o Java 5 (com recursos como generics), o Java 8 (com lambdas e a Stream API), o Java 11 (que marcou o início do suporte de longo prazo) e muitas outras versões subsequentes.

<div id='id3' />
  
##  3. Instalando o Java Development Kit (JDK)

Instalação do JDK (Java Development Kit): O JDK é composto de ferramentas de software para desenvolver aplicações em Java. A instalação do JDK, no ambiente de desenvolvimento, é feita através do download do sotware utilizando a plataforma da Oracle, seguindo as intruções para cada sistema operacional. 
Aparecerá na tela a caixa de diálogo para download do arquivo. Basta apartar o botão “Executar” e clicar em “Instalar” para aceitar os termos de licença e concluir a instalação.

<div id='id4' />
  
 ## 4. Configurando o Ambiente de Desenvolvimento
 
Configuração do ambiente: Após a instalação, é necessário configurar as variáveis de ambiente. No Windows, vá em "Painel de Controle" > "Sistema" > "Configurações Avançadas do Sistema" > "Variáveis de Ambiente" e adicione o caminho para o diretório bin do JDK na variável PATH. No Linux ou macOS, você pode configurar o PATH no arquivo ~/.bashrc ou ~/.bash_profile.

Verifique a instalação: Abra um terminal ou prompt de comando e digite java -version e javac -version para verificar se a instalação foi bem-sucedida.

<div id='id5' />
  
## 5. Editores Java

Os editores Java, IDE ou Ambiente de Desenvolvimento Integrado fornecem  ferramentas e facilidadespara como editor de código-fonte, ferramentas de compilação e depuradores. Os principais estão descritos abaixo:

- **Bloco de notas** -O Notepad (Bloco de notas) é um editor de texto simples incluído no  Microsoft Windows. 
- **Netbeans** − É um IDE Java de código aberto e gratuito que pode ser baixado do www.netbeans.org/index.html.
- **Eclipse** − É um IDE Java desenvolvido pela comunidade de código aberto Eclipse e pode ser baixado do www.eclipse.org.
- **VSCode** : utilizado para editar códigos de desenvolvimento para aplicações web, o download do site é no endereço https://code.visualstudio.com.

<div id='id6' />
  
 ## 6. Fundamentos    
  |                                                                      | 
| ----------------------------------------------------------------------------------------------------------------| 
| 1. **Plataforma Java**: Consiste em duas partes principais –  o kit de desenvolvimento Java (JDK) necessário para desenvolver aplicativos Java, e o o ambiente de tempo de execução Java (JRE). O JRE é responsável por executar aplicativos Java.   | 
|  2. **Pacote**: Os pacotes são o mecanismo usado para agrupar classes relacionadas em Java. Eles são usados para organizar melhor o código e evitar conflitos de nome.  | 
|  3. **Classe**: A classe é a unidade básica de programação em Java. Ela é usada como um modelo para criar objetos. Cada classe contém atributos (variáveis) e métodos (funções).   | 
|  4. **Objeto**: É uma instância de uma classe. A criação de um objeto envolve a alocação de memória para esse objeto.   | 


<div id='id7' />
  
 ## 7. Sintaxe Básica em Java
|                              |
| -----------------------------|
| **Diferenciação de maiúsculas e minúsculas** − Java diferencia maiúsculas de minúsculas.  |
| **Nomes de classe** − a primeira letra deve estar em maiúsculas. Se várias palavras forem usadas para formar um nome da classe, a primeira letra de cada palavra interna deve estar em maiúsculas.Exemplo: PrimeiroPrograma  |
| **Nomes de método** − Todos os nomes de método devem começar com uma letra minúscula. Se várias palavras forem usadas para formar o nome do método, a primeira letra de cada palavra interna deve estar em maiúsculas. Exemplo: public void myMethodName(). |
| **Nome do arquivo do programa** −  deve corresponder exatamente ao nome da classe.Exemplo: Suponha que 'PrimeiroPrograma' é o nome da classe. Em seguida, o arquivo deve ser salvo como 'PrimeiroPrograma.java'.|
| **public static void main(String args[])** − O processamento do programa Java começa a partir do método main() que é uma parte obrigatória de todo programa Java.|

<div id='id8' />
  
## 8. Identificadores 

Todos os componentes Java requerem nomes. Os nomes usados para classes, variáveis e métodos são chamados de identificadores.
Em Java, há vários pontos a serem lembrados sobre identificadores. 

|                                                                 |
|----------------------------------------------------------------------------|
| - Devem começar com uma letra (A a Z ou a a z), caractere de moeda ($) ou um sublinhado (_).  |
| - Após o primeiro caractere, os identificadores podem ter qualquer combinação de caracteres.  |
| - Uma palavra-chave não pode ser usada como um identificador.  |
| - Diferenciam maiúsculas de minúsculas. |

<div id='id9' />
  
 ## 9. Palavras-chave 
 
São os **identificadores** que têm significado especial para o compilador. Estes não podem ser usados para nomear variáveis, classes, funções ou métodos. São palavras reservadas.  São elas:
`` abstract, assert, boolean, break, byte, case, catch, char, class, const, continue, default, do,  
double, else, enum, extends, final, finally, float, for, goto, if, implements, import, int,interface, long, native, new, null, package, private, protected, public, return, short, static,	strictfp, super, switch, synchronized, this, throw, transient, try, void, volatile, while  .``

<div id='id10' />
  
## 10. Comentários em Java

**Comentários de linha única**: Marcados com duas barras invertidas(//) 

**Comentários de várias linhas**: Marcados por uma tag inicial(/*) e uma tag final(*/)

<div id='id11' />

## 11. Primeiro Programa em Java - 

Criamos um arquivo Java chamado **HelloWorld**, e usamos o seguinte código para imprimir **"Hello World"** na tela: 

```
public class Main {
  public static void main(String[] args) {
    System.out.println("Hello World");
  }
}
```
O nome da classe é o nome do  arquivo chamado **HelloWorld**. O ***public*** - acesso público, ***class*** -classe e ***Hello*** - nome do  arquivo. O ***static*** - acesso sem instanciar a classe, ***void*** -não retorna nada e ***main*** - ponto de entrada do programa. O ***System.out*** - objeto de saída padrão, o ***println*** -mostrar algo escrito na tela. ***System.out.println()***: Esta linha imprime o texto "Hello, World!" no console.

## Referências

1. [A Brief History of Java Programming Language](https://www.theknowledgeacademy.com/)

2. [Java Quick Guide](https://www.tutorialspoint.com/java/java_quick_guide.htm)https://www.tutorialspoint.com/java/java_quick_guide.htm)


