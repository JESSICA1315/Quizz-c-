#include <iostream>

using namespace std;

int main()
{
    int pontuacao=0,erros=0;
    char opcao;
    cout<<"<<           Bem vindo ao nosso quizz            >>"<<endl;
    cout<<"<<           Aqui a sua lógica será desafiada!!!         >>"<<endl<<endl;

    cout<<"1)Qual o numero minimo de jogadores em cada time?"<<endl;
    cout<<"a) 8"<<endl;
    cout<<"b) 10"<<endl;
    cout<<"c) 9"<<endl;
    cout<<"d) 5"<<endl;
    cout<<"e) 7"<<endl;
    cout<<"Resposta: ";
    cin>>opcao;
    if(opcao=='e'){
        cout<<"Você acertou! Vamos para proxima"<<endl<<endl;
        pontuacao=pontuacao+10;
    }
    else{
        cout<<"Você errou, a respota certa eh = e"<<endl<<endl;
        erros=erros-5;
    }

    cout<<"2)O que a palavra LEGEND significa em portugues?"<<endl;

    cout<<"a) Legenda"<<endl;
    cout<<"b) Conto"<<endl;
    cout<<"c) Historia"<<endl;
    cout<<"d) Lenda"<<endl;
    cout<<"e) Legendario"<<endl;
    cout<<"Resposta: ";
    cin>>opcao;
    if(opcao=='d'){
        cout<<"Você acertou! Vamos para proxima"<<endl<<endl;
        pontuacao=pontuacao+10;
    }
    else{
        cout<<"Você errou, a respota certa eh = d"<<endl<<endl;
        erros=erros-5;
    }

    cout<<"3)Complete o provérbio, A cavalo dado..."<<endl;

    cout<<"a) sai caro"<<endl;
    cout<<"b) tem medo de agua fria"<<endl;
    cout<<"c) nao se olha o rabo"<<endl;
    cout<<"d) bonito lhe parece"<<endl;
    cout<<"e) não se olha os dentes"<<endl;
    cout<<"Resposta: ";
    cin>>opcao;
    if(opcao=='e'){
        cout<<"Você acertou! Vamos para proxima"<<endl<<endl;
        pontuacao=pontuacao+10;
    }
    else{
        cout<<"Você errou, a respota certa eh = e"<<endl<<endl;
        erros=erros-5;
    }

    cout<<"4)Quantos litros de sangeu uma pessoa tem?"<<endl;

    cout<<"a) tem entre 2 a 4 litros"<<endl;
    cout<<"b) tem entre 4 a 6 litros"<<endl;
    cout<<"c) tem 10 litros"<<endl;
    cout<<"d) tem 7 litros"<<endl;
    cout<<"e) tem 0,5 litros"<<endl;
    cout<<"Resposta: ";
    cin>>opcao;
    if(opcao=='d'){
        cout<<"Você acertou! Vamos para proxima"<<endl<<endl;
        pontuacao=pontuacao+10;
    }
    else{
        cout<<"Você errou, a respota certa eh = d"<<endl<<endl;
        erros=erros-5;
    }

    cout<<"5)Qual o maior animal terrestre nos dias de hoje?"<<endl;

    cout<<"a) Baleia Azul"<<endl;
    cout<<"b) Dinossauro"<<endl;
    cout<<"c) Elefante africano"<<endl;
    cout<<"d) Tubarão Branco"<<endl;
    cout<<"e) Girafa"<<endl;
    cout<<"Resposta: ";
    cin>>opcao;
    if(opcao=='c'){
        cout<<"Você acertou! Vamos para proxima"<<endl<<endl;
        pontuacao=pontuacao+10;
    }
    else{
        cout<<"Você errou, a respota certa eh = c"<<endl<<endl;
        erros=erros-5;
    }


    cout<<"Resultado:"<<endl;
    cout<<"Pontuação: "<<pontuacao<<endl;
    cout<<"Erros: "<<erros<<endl;
    cout<<"         FIM DE JOGO, ATE A PROXIMA!"<<endl;
    return 0;
}
