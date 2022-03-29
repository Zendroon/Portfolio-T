# Portfólio-T
##### Portfólio do primeiro trimestre / Técnico (Contém trabalhos feitos durante o primeiro trimestre do ensino médio)
----------------------------------------------------------------------------------------------------------------
## Sobre mim
##### Sou Gabriel Barroso Zendron, tenho 16 anos e estudo atualmente no Sesi Senai-SJ. Aproveito o tempo livre para estudar e programar em Python e HTML5 visto no canal [Curso em vídeo](https://www.youtube.com/c/CursoemV%C3%ADdeo), além de aprender Inglês no colégio e Japonês em cursos pagos na busca de alcançar a fluência de ambos. Focando atualmente em aprender Power BI para a análise de dados de empresa, algo que nos dias de hoje está em falta, busco ingressar cedo nessa parte do mercado de trabalho para me adaptar nas novas linguagens e tipos de análises que podem surgir.
## Conquistas e Trabalhos:
* ###### *Alcançar o N4 em Japonês*
* ###### *Conseguir criar um site*
* ###### *Acabar curso de cores fornecido pela Bradesco*
* ###### *Finalizar cursos de Japonês*
* ###### *Certificado do Hellow (alocado no final do portfólio)*
------------------------------------------------------------------
## Descrição do Portfólio
##### *O portfólio terá conteúdos sobre:*  
###### **Fundamentos de TI + exemplos** → **Lógica computacional + exemplos** →  **Fundamentos de Design + exemplos**
-----------------------------------------------------------------------------
#### Toda matéria vista em Lógica computacional:
~~~javascript
Códigos de Java:

comandos:
!=  →  diferente
">"  →  maior que 
<  →  menor que
>=  →  maior igual 
<=  →  menor que
&&  →   e
||  →  ou
++  →  soma mais 1 na variavel
--  →  subtrai menos 1 na variavel
%  →  resto da divisão
==  →  comparação
=   →  recebe (torna igual, iguala etc)
!  →  negação

numéricos:
int → números inteiros
float → números com casas decimais
long → números inteiros extensos 
double → números com muitas casas decimais


caracteres:
char → 1 caracter
string → conjunto de caracteres

binário:
boolean → verdadeiro ou falso

Exemplos: 

1* 
import java.util.Scanner;
public class Main
{
	public static void main(String[] args) {//Início do método main
		Scanner bofao = new Scanner(System.in);//Criação do Scanner
		System.out.println("Digite um número");//Mensagem para digitar algo
		int n = bofao.nextInt();//Variável 'n' recebe o valor digitado no Scanner
		int i = 0;//Variável 'i' recebe o valor '0'
		while(i < n){//Enquanto 'i' for menor do que 'n', faça:
		    int j = i;//Variável 'j' recebe o valor da variável 'i'
		    int d = 0;//Variável 'd' recebe o valor '0'
		    while(j > 0){//Enquanto 'j' for maior do que '0', faça:
		        if(i % j == 0){//Se o RESTO da divisão de 'i' por 'j' for 0, faça:
		            d++;//Adicione +1 ao valor da variável 'd'
		        }//Fim do if
		        j--;//Subtrai -1 ao valor da variável 'j'
		    }//Fim do while
		    if(d == 2){//Se o valor da variável 'd' for igual a '2', faça:
		        System.out.println(i);//Mensagem informando o valor de 'i'
		    }//Fim do if
		    i ++;//Adiciona +1 ao valor da variável 'i'
		}//Fim do while
	}//Fim do método main
}


2*
import java.util.Scanner;
public class Main
{
	public static void main(String[] args) {
	    Scanner batata = new Scanner(System.in);
		System.out.println("Digite um número:");
		int passos = batata.nextInt();
		int i = 0;
		while(i < passos){
		    i = i + 1;
		     if(i % 2 ==0){
		    System.out.println(i);
		    }
		}
	}
}
~~~
----------------------------------------------------------------
#### Toda matéria vista em Fundamentos de TI:
~~~TI
Segurança da Informação:

Existem quatro princípios básicos

Disponibilidade
Integridade
Confidencialidade
Autenticidade


Disponibilidade → A informação estará disponível sempre que for preciso
ferramentas = Nobreak, Firewall e Backup.

firewall:
Necessário para proteção contra ataques e impede ataques de intrusão e de negação de serviço

backup: cópia de arquivos


Integridade → A informação só pode ser alterada por pessoas autorizadas
ferramentas = Assinatura digital e Backup

Assinatura digital:
- Senhas feitas através de algoritmos, é gerado um resumo do documento original (hash)
- impossível obter o documento original a partir do hash
- o hash deve parecer aleatório
- duas mensagens diferentes não possuem o mesmo hash

O hash é criptografado com o sistema de chave
Para verificar a autenticidade, é feito o caminho inverso


Confidencialidade → Garante sigilo da informação
ferramentas: Criptografia


Autenticidade → 
Garante a veracidade da autoria da informação 
Não garante a veracidade do conteúdo
Não repúdio: não tem como negar a autoria
Ferramentas: Biometria, Assinatura e certificados digitais.

Biometria: Identifica a pessoa através de caracteres físicos
Assinatura digital: Identifica a pessoa através da assinatura 
Certificados: garantem a autenticidade de autoria 

Sistemas Operacionais:

Responsável pelo gerenciamento de recursos e periféricos
interpretação de mensagens e execução de programas

→ Conjunto de ferramentas necessárias para que um computador possa ser utilizado de forma
adequada
→ Intermediário entre o aplicativo e a camada física do hardware
(usuário → Programa → Sistema Operacional → Hardware)
→ Abstração do hardware

Conveniência: Tornar o uso do pc mais fácil (conveniente)
Eficiência: Tornar eficiente (Seguro e justo) e o uso compartilhado dos recursos existentes
Evolução: Possibilitar o constante aprimoramento e desenvolvimento de novas funções

→ Permitir que os programas obtenha e armazenem informações
→ Controlar o fluxo de dados entre os componentes
→ Permitir que programas sejam Núcleo e Cerne
Para acessar o kernel, o usuário deve usar um interpretador de comandos
Aplicativos + shell → Kernel → (cpu - memória - dispositivos)

Exemplos:
 
 1 - 
   1  mkdir aluno
    2  cd aluno
    3  touch test01.txt test02.txt test03.txt
    4  cd ..
    5  touch test2.txt
    6  mkdir aulaso
    7  cd aluno
    8  cp test01.txt-/aulaso
    9  cp test.01.txt-/desktop/aulaso
   10  cp test.02.txt-/desktop/aulaso
   11  cp test.03.txt-/desktop/aulaso
   12  mv test2.txt-/desktop/aulaso
   13  rm test01.txt
   14  cd ..

2 - 
   15  find . -name 'test'
./aulaso/test01.txt
./aulaso/test02.txt 
./aulaso/test03.txt 
./test2.txt
   16  cd aulaso
   17  find . -name 't'
./teste1.txt
./teste2.txt
./teste3.txt
   
   3 - 
   
   44  mkdir /
   45  mkdir home
   46  cd home
   47  mkdir aluno
   48  cd aluno
   49  mkdir filmes
   50  cd filmes
   51  mkdir Comédia Aventura Suspense
   52  cd Comédia
   53   mkdir Nacional Estrangeiro
   54  history
~~~
