# Atividade-Avaliativa-T.E-

Valendo 2 pontos

# Atividade-Avaliativa

Valendo 2 pontos

Questão 1

Resposta: d;

###########################################

#Questão 2

##A

 void main() {

   int var1 = 2;

   int var2 = 5;

    String nome = 'Julia';

   print('O primeiro valor é $var1');

    print('O segundo valor é $var2');

   print('O texto é $nome');
 }



##B

escrever(){

  for (int i = 1; i<11; i++){

  print(i);

  }

}



void main() {

  escrever();

}



##C

escrever(int a ){

  for (int i = 1; i<=a; i++){

  print(i);

  }

}



void main() {

  int num = 50;

  escrever(num);

}



##D

void main() {

  int num = 10;

  soma(num);

}



int soma(int a ){

int cont = 0;

int somar = 0;

while (cont<=a){

somar = somar +cont;

cont++;

}

print(somar);

  return somar;

}


##E



class Pessoa {

  String nome;
  
  double peso;
  
  double altura;



  Pessoa(String nom, double pes, double alt) {
  
    this.nome = nom;
    
      this.peso = pes;
    
    this.altura = alt;
  
  }

  void MostrarTexto() {
  
  print(nome);
  
  }

  
  void MostrarDouble() {
  
    print(peso);
    
    print(altura);
  
  }

}


void main() {

  Pessoa p1 = new Pessoa("Julia", 47, 1.52);
  
  p1.MostrarTexto();
  
  p1.MostrarDouble();

}
