**1. Por que o Linux recebeu esse nome?**

O nome surgiu da união de Linus + Unix. Linus é o nome do criador do Linux, Linus Torvalds. E Unix, é o nome de um sistema operacional de grande porte.

**2. O que são daemons?**

É um programa de computador que executa como um processo em plano de fundo, em vez de estar sob o controle direto de um usuário interativo.

**3. O que é o shell?**

Shell é a interface de comandos. Permite a comunicação entre o usuário e o sistema operacional, através das linhas de comando.
É um arquivo executável, encarregado de interpretar comandos, transmiti-los ao sistema e devolver resultados.

**4. Por que é importante evitar executar o terminal como super-usuário?**

Denominado Root. Possui o UID igual a 0. Através dele é possível fazer qualquer coisa com o sistema operacional, por exemplo, remover ou adicionar privilégios de impressão para determinados usuários, remover todos os diretórios do sistemas e etc.

**5. Qual botão do teclado completa o que o usuário escreve no terminal, de acordo com o contexto?**
Tecla TAB.

**6. Quais botões do teclado apresentam instruções escritas anteriormente?**

ctrl s (???)

**7. Apresente os respectivos comandos no terminal para:** 

- (a) Obter mais informações sobre um comando. 

man <comando>

- (b) Apresentar uma lista com os arquivos dentro de uma pasta. 

ls <pasta>

- (c) Apresentar o caminho completo da pasta. 

pwd

- (d) Trocar de pasta. 
- (e) Criar uma pasta. 
- (f) Apagar arquivos definitivamente. 

rm <arquivo>

- (g) Apagar pastas definitivamente. 

rm <pasta/> 

- (h) Copiar arquivos. 

cp 

- (i) Copiar pastas. 

cp

- (j) Mover arquivos. 

mv <arquivo> <destino>  (se for pasta, final "/")
  

- (k) Mover pastas. 

mv <pasta/> <pasta/>

- (l) Renomear pastas. 

mv <nome atual> <novo nome>
  
- (m) Apresentar o conteúdo de um arquivo. 

cat <arquivo.formato>

- (n) Apresentar o tipo de um arquivo. 
- (o) Limpar a tela do terminal. 

clear

- (p) Encontrar ocorrências de palavras-chave em um arquivo-texto. 

grep <"palavra chave"> <arquivo>
  
- (q) Ordenar informações em um arquivo-texto. 
- (r) Substituir ocorrências de palavras-chave em um arquivo-texto. 
- (s) Conferir se dois arquivos são iguais. 
- (t) Escrever algo na tela.

echo 

**Notas:**

Permissões: ls -l
ex: chmod <numero>
    reasd
  
 > : apaga e coloca no arquivo
 >> : adiciona ao arquivo (concatena)
 
 | : saida vertical 

; : comandos sequenciais

ps : todos os comandos que estão sendo executados no terminal

kill : interrompe um processo
