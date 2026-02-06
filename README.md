# Apresentação

Este projeto um se trata de um vault do software Obsidian para estudos na área de teologia. A proposta é criar funcionalidades que permitam um sistema mais fluído de referencias do texto bíblico e de outas fontes, criando um sistema de gestão de conhecimento eficaz que o Obsidian oferece.
# Notas do texto bíblico

A imagem abaixo é o grafo formado pelas notas de todos os capítulos da bíblia, ligadas às notas de seus livros, ligadas as notas de seus autores. Pontos vermelhos são notas do texto bíblico por capítulo e pontos amarelos são das notas dos livros e autores. Notas de livros e autores estão vazias para que o gestor da aplicação possa colocar suas próprias considerações e apontamentos. Elas foram previamente construídas para agrupar as notas dos textos, criando uma hierarquia.

![[Pasted image 20260205205223.png]]

Por causa de direitos autorais, a versão utilizada para criar o vault é a NVA - Nova Versão de Acesso Livre. Este projeto possui direitos autorais abertos e texto disponível na internet. 
![[Pasted image 20260205210124.png]]
# Sistema de notação

Neste Vault existem alguns modelos ou templates que auxiliam na inserção de referências bíblicas e e textos nas notas dos estudos. Para que eles funcionem, é imprescindível a instalação do Plugin Templater (Athor: SilentVoid). Eles Permitem criar os três tipo de referência abaixo:

- **Modelo 01-Referência Bíblica** é para criar a referência comum em estudos com livro+capítulo+versículo, bloco de versículo ou versículos esparsos. A referência já faz link com a nota do texto. Para usar, chame o modelo e entre com a abreviação, capítulo e versículo, separados por espaço e aperte o Enter.

Ex.: [[Gênesis 1#^v1|Gênesis 1.1]] ou [[Gênesis 1#^v5|Gênesis 1.5-10]] ou [[Gênesis 1#^v3|Gênesis 1.3,5,18]]

- **Modelo 02 - Bloco de Versículos** é para criar uma caixa de texto com o texto do versículo destacado.

> [!Bible] Gênesis 1:1
> ![[Gênesis 1#^v1]]

> [!Bible] Gênesis 1:1-3
> ![[Gênesis 1#^v1]]
> ![[Gênesis 1#^v2]]
> ![[Gênesis 1#^v3]]

- **Modelo 04 - Referência Cruzada** permite criar um sistema de marcação no texto bíblico igual ao sistema de referências cruzadas nas bíblias tradicionais. Observe no exemplo que ele cria uma marcação flutuante no texto, próximo à palavra referenciada e também cria automaticamente um rodapé que fica no fim da página (inclusive está neste exemplo)

Ex.: **1** No [^1]princípio, criou Deus os céus e a terra.

- **Modelo 03 - Abreviações**. Para qualquer um dos três  você deve chamar o modelo e entrar com a abreviação do livro seguido pelo capítulo e seguido do versículo. Caso não saiba qual a abreviação, você pode chamar o plugin 03 que lista todos os livros pelo nome para você escolher e depois abre uma caixa para colocar o capítulo e o versículo.

![[Pasted image 20260205213741.png]]



[^1]: [[Provérbios 8#^v23|Provérbios 8:23]]