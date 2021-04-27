# O que é Markdown, e como ele pode melhorar o seu README no GitHub!


![mark](https://markdown-here.com/img/icon256.png) 

 O README no *GitHub* é uma parte essencial do seu repositório, onde você apresenta seu projeto ou organiza seu repositório!  

E para formatar o seu arquivo README utilizamos a linguagem de marcação chamada *Markdown*. As possibilidades dessa linguagem incluem formatações de texto de forma fácil e útil, apesar de ser uma formatação simples contém o que há de mais essencial para você deixar seu texto bem construído e organizado, por exemplo: listas, tabelas, titulação, inserção de links e imagens, bloco de código, destaque, negrito, sublinhado, itálico etc... 

# Onde Markdown costuma ser usado? 

 No próprio *GitHub* além do já citado arquivo README.md, pull requests, issues e na wiki. Mas também em outras plataformas para escrever mensagens em fóruns ou rich text. Este artigo mesmo foi escrito e formatado em *Markdown*. 

# Como escrever em Markdown 

A partir deste ponto eu vou te ensinar como executar essa linguagem na pratica passo a passo! 

Primero vamos abrir um preview de Markdown, para que você possa acompanhar o resultado do seu código enquanto o executa. 

1. Abra o editor de código VSCode. Usarei ele como base nesse tutorial. (*Clique [aqui](https://code.visualstudio.com) para baixar o VSCode caso você não o tenha instalado*.) 

2. Crie um novo arquivo com o nome README.md, repare que `.md` é a extensão de um arquivo Markdown. 

3. Pressione `CTRL/CMD + SHIFT + P` .

4. Isso fara com que uma janela se abra e nela você digitara `Markdown`, clique na extensão de nome ` *Markdown: Open Preview to the Side* `. 

Pronto! Agora sempre que quiser abrir sua preview é só dar o comando `CTRL/CMD + K` depois pressione `V` separadamente.

# Agora vamos a prática! 

A partir daqui vamos para as tags de formatação em Markdown, execute-os no seu arquivo ao mesmo tempo que os aprende para ver o resultado. 

## Titulação 

Para você destacar títulos (*como os títulos deste post por exemplo*), utiliza-se `#`. 

``` 

# Título 1  
 

## Título 2 
 

### Título 3 
 

#### Título 4 
 

##### Título 5 
 

###### Título 6 

``` 

# Título 1  
 

## Título 2 
 

### Título 3 
 

#### Título 4 
 

##### Título 5 
 

###### Título 6 

## Formatação

As vezes, existe mais de uma forma de se fazer a mesma coisa em Markdown. 

*Itálico* 

``` 

*Itálico* 

``` 

``` 

_Itálico_ 

``` 

**Negrito** 

``` 

**Negrito** 

``` 

``` 

__Negrito__ 

``` 

***Itálico e Negrito*** 

``` 

***Italico e Negrito*** 

``` 

``` 

___Italico e Negrito___ 

``` 

~~Riscado~~ 

``` 

~~Riscado~~ 

``` 

`Destaque` 

``` 

`Destaque` 

``` 

Repare que estou utilizando o ***acento invertido*** (`è`), e não o acento comum que utilizamos no dia a dia (`é`). 

## Links 

Existem duas formas de se inserir links: 

Com [texto](www.google.com) âncora. 

``` 

[Texto](www.google.com) 

``` 

Ou apenas o link direto 

``` 

<www.exemplo.com> 

``` 

## Imagens 

É parecido com inserir links. 

``` 

![texto](www.caminhodaimagem.com) 

``` 

Resultado: 

![icon](https://image.flaticon.com/icons/png/128/1077/1077114.png) 

## Listas

Para criar listas não ordenadas é só utilizar `-` ou `*`. 

- E 

- Fica 

- Assim 

E para listas ordenadas o bom e velho `1.` 

1. Item  

2. Outro item 

3. Mais um item 

Em ambos os casos se lembre de dar um espaço depois do ícone para o comando funcionar. 

## Blockquote 

Caso você precise fazer uma citação ou comentário é só utilizar `>`. 

> E fica assim. 

> Pra continuar outro “paragrafo” como este no blockquote você precisa utilizar outro `>` no começo. 

## Bloco de código 

Sabe os blocos de código legais que você estava vendo ao longo desse artigo? Se faz assim: 

<pre>
```js  

Console.log(3 > 2) 

```
</pre>

> Onde esta o `js` você pode substituir por qualquer outra linguagem que você quer exemplificar.

Você pode substituir o acento invertido por `~` que também funciona da mesma forma. 

 

## Tasklist 


Isso aqui, sabe?  

![boxpre](boxpreview.jpeg)

Se faz assim:

``` 

[ ] Fazer Rascunho do artigo
[ ] Revisar artigo
[ ] Publicar artigo 

``` 

Não esqueça do espaço entre os caracteres, quando completar sua tarefa é só colocar um `x` entre os colchetes. 

## Tabelas  

No Markdown você literalmente tem que desenhar as tabelas. 

`|` Para colunas. 

`-` Para Divisórias de título. 

``` 

Exemplo | Valor do exemplo 
--------- | ------ 
Exemplo 1 | R$ 10 
Exemplo 2 | R$ 8 
Exemplo 3 | R$ 7 
Exemplo 4 | R$ 8 

``` 

Fica assim: 

Exemplo | Valor do exemplo 
--------- | ------ 
Exemplo 1 | R$ 10 
Exemplo 2 | R$ 8 
Exemplo 3 | R$ 7 
Exemplo 4 | R$ 8 

<br>

Mas caso você goste de atalhos, recomendo [este site](https://www.tablesgenerator.com/markdown_tables) que desenha tabelas em Markdown para você e é só copiar e colar! 

# Conclusão

 Esses são os elementos mais basicos para quem esta conhecendo o Markdown e pretende utiliza-lo no dia a dia. Com isso você já consegue usar o melhor do Markdown nas suas plataformas preferidas, formatar seus textos, artigos e seus README’s. 
 Espero que tenha sido util para você! 

# Referencias
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/xdeu3coyhynrqcwv7kev.png)
- [Wikipedia](https://pt.wikipedia.org/wiki/Markdown#:~:text=Markdown%20é%20frequentemente%20usado%20para,um%20editor%20de%20texto%20simples%20.)

- [Pipz Academy - Guia básico de Markdown](https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open)

- [Lucas Santos - Escrita Eficiente de Artigos com VSCode](https://dev.to/azure/escrita-eficiente-de-artigos-com-vscode-1am4)

- [Afonso Pacifer - Pensando em URLs no Github](https://medium.com/@afonsopacifer/pensando-em-urls-no-github-3517d97249d0) 

TATAKAE!
