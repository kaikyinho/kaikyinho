Boas vindas ao meu perfil 💙💙
Meu nome é Kaiky Silva de Almeida

Estou estudando na Alura
Estou me desenvolvendo na linguagem JavaScript
Utilizo esse espaço para minha organização e compartilhamento dos meu projetos desenvolvidos

Você pode entrar em contato comigo 📫
kaikysilvadealmeida7@gmail.com

![]([link](https://media.giphy.com/media/cOKjNdJDbqNCm4n0Jm/giphy.gif?cid=790b7611hau6b7n234h3pnv5i8chfu5nsdmuj0oxvqj2m149&ep=v1_gifs_search&rid=giphy.gif&ct=g))

function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(220);
}function setup() {
  createCanvas(400, 400);
}

function draw() {
  background("white");
  fill("black");
  textSize(64);
  textAlign(CENTER, CENTER)
  
  let maximo = width;
  let minimo = 0;
  let palavra = "kaikyinho";
  let quantidade = map(mouseX, 0, width, 1, palavra.length);
  let parcial = palavra.substring(0,quantidade);
  text(parcial,200,200);
  
//  if(mouseX < 50){
//    let palavra = "C";
//    text(palavra, 200, 200);
//  } else {
//    let palavra = "Caminhante";
//    text(palavra, 200, 200);
//  }
}

