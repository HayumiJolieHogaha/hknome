# hknome
let xBolinha =300;
let yBolinha =200;
let diâmetro =15;
let raio =diâmetro/2;

//velocidade da Bolinha
let velocidadexBolinha =5;
let velocidadeyBolinha =5;

function setup() {
  createCanvas(600, 400);
}

function draw() {
  background(0);
  mostraBolinha();
 movimentaBolinha();
  
}
 
  circle(xBolinha, yBolinha, diâmetro);
  xBolinha += velocidadexBolinha; 
  //yBolinha += velocidadeyBolinha; 
  
function verificaColisãoBorda
  if(xBolinha + raio > width  || xBolinha - raio < 0) {
    velocidadexBolinha *=-1;
  
  }

  if(yBolinha + raio > heigth|| yBolinha - raio < 0)
    velocidadeyBolinha *= -1;
  
  }
