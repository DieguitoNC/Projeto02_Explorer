# Aprendizado no projeto
Nesse projeto eu aprendi algumas funcionalidades a mais tanto no HTML quanto CSS, deixarei embaixo cada aprendizado. 

# Estruturando HTML com tags semanticas
## nav - secao no html
- Vai criar uma secao no html
```
<nav></nav>
```
## listas -html
```
<ul>

          <li>Home</li>

          <li>Sobre</li>

          <li>Treinar</li>

 </ul>
```
### Listas ordenadas OL
- Para criar uma lista ordenada bastar usar a tag ol
### UL para listas sem ordem
- Para criar uma lista sem ordem obrigatoria bastar usar a tag UL
### criar elementos de listas com LI
- Para criar os elementos das listas


## main - parte principal do site
- Tag html para identificar
```
<main>
```
## Button - Serve para criar um botao na pagina
```
<button>

        <img src="./assets/whats.svg" alt="logo do whatsapp">

 </button>
```
# Box model
1. Margem seria a margem pensando na caixa pro lado de fora
2. Padding seria a margem interna do proprio bloco
3. border 'e a borda da caixa


# Flex box CSS
## Display flex
Elementos filhos vao ficar alinhados um do lado do outro
## Justify content
- Vai justifcar os elementos como vc quiser, geralmente usamos o display space-between para deixar extremo opostos
## Align-itens
vai servir para alinhar os itens que estao na mesma box
## gap
- Serve para conseguir colocar espacos entre elementos da lista
## list style 
- Serve para definir as bolinhas da lista, geralmente para tirar, colocamos none


# Configurando o botao
```
button {

  color: white;

  text-transform: uppercase;

  font-family: "Open Sans";

  
  

  background-color: #69B99D;

  border: 0px;

  padding: 14px 32px 15px;

  

  display: flex;

  align-items: center;

  justify-content: center;

  gap: 10px;

  

  border-radius: 4px;

  cursor: pointer;

}
```
## Arrumar padding
Ao inves de colocar altura e largura, mexer com padding, pq ele vem com padding padrao
## Border Radius 
Serve para a gente arrendondar a box do botao
## Cursor pointer
Serve para mudar o ponteiro do mouse quando passamos ele por cima.
# Background linear-gradient e ajustes finais
## Background: linear gradient
- Vai criar um degrade na pagina, podemos pesquisar sites que facam isso
```
  background: linear-gradient(180deg, rgba(227, 255, 248, 0.00) 82.08%, rgba(227, 255, 248, 0.38) 100%);
```



