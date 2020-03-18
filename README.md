# Proyecto-c-
proyecto de la universidad para marketful

#include <iostream>
#include <stdio.h>
#include <stdlib.h>
#include <conio.h>
using namespace std; 

int main(){
	int argc; 
	char argv;
    int num, num2, opc=0;; 
	int r1, r2, r3, i, mes, dia;
	int opc2, opc1, opc3, opc4;
	system( "color 30" );
	do{
	//gotoxy ("23,4");
	cout<<"\t\t\t*********************�Cual juego quieres jugar?********************* \n"<<"\t\t\t\t\t\t 1.-Adivinanzas \n"<<"\t\t\t\t\t\t 2.-Adivina el numero \n"<<"\t\t\t\t\t\t 3.-ecuaciones\n"<<"\t\t\t\t\t\t 4.-Signos del Zodiaco\n"<<"\t\t\t\t\t\t 5.- Recomendaciones de Peluclas\n"<<"\t\t\t\t\t\t 6.- Salir\n";
	cin>>opc;
	system("cls");
	switch (opc){
	case 1: //aqui se empieza las adivinanzas
	do{
		cout<<"\t\t\t\t\t A cual adivinanza quieres entrar\n"<<"\t\t\t\t\t\t 1.-libro de mate\n"<<"\t\t\t\t\t\t 2.-siempre cae...\n"<<"\t\t\t\t\t\t 3.-frio\n"<<"\t\t\t\t\t\t 4.-Salir\n";
		cin>>opc3;
		system("cls");
		switch(opc3){
			case 1:	
				cout<<"\t\t\t\t\t �Por que se suicido el libro de matematicas?\n";
				cout<<"\t\t\t\t\t\t 1)Porque reprobo el cuatrimestre \n";
				cout<<"\t\t\t\t\t\t 2)Porque nadie lo leia \n";
				cout<<"\t\t\t\t\t\t 3)Porque tenia muchos problemas\n";
				cout<<"\t\t\t\t\t\t 4)Porque lo dejo su novia \n";
				cin>>r1;
					if(r1==3)
					{
						cout<<"\t\t\t\t\t ����������Muy Bien!!!!!!!! tu si eres pro \n";
					}			
					else
					{
						cout<<"\t\t\t\t\t ******* Lo siento, perdiste :( ******* \n";
					}
			system("pause");
			system("cls");		
			break;
			case 2:
				cout<<"\t\t\t\t �Qu� es algo que siempre cae, y nunca se rompe?\n";
				cout<<"\t\t\t\t\t\t 1)el amor\n";
				cout<<"\t\t\t\t\t\t 2)la cascada\n";
				cout<<"\t\t\t\t\t\t 3)la determinacion\n";
				cout<<"\t\t\t\t\t\t 4)el agua \n";
				cin>>r2;
					if(r2==2)
						{
						cout<<"\t\t\t\t\t����������Muy Bien!!!!!!!! tu si eres pro \n";
						}			
							else
							{
							cout<<"\t\t\t\t\t******* Lo siento, perdiste :( ******* \n";
							}
			system("pause");
			system("cls");
			break;
			case 3:
				cout<<"Soy duro y bastante frio, cuando me tocas me sonrojo y si ahorita me ves, al rato, solo te mojo. �Quien soy?\n";
				cout<<"\t\t\t\t\t\t 1)El amor de ella\n";
				cout<<"\t\t\t\t\t\t 2)El hielo\n";
				cout<<"\t\t\t\t\t\t 3)Tu compa\n";
				cout<<"\t\t\t\t\t\t 4)El agua fria\n";
				cin>>r3;
					if(r3==2)
						{
						cout<<"\t\t\t\t\t����������Muy Bien!!!!!!!! tu si eres pro \n";
						}			
							else
							{
							cout<<"\t\t\t\t\t ******* Lo siento, perdiste :( ******* \n";
							}
			system("pause");
			system("cls");
			break;
	}
	cout<<"�Quieres volver al menu principal? \n";
	cout<<"1.-Si\n";
	cout<<"2.-No\n";
	cin>>opc1;
	}while(opc1 !=1);
	
			break;
	case 2: //*****aqui empieza la adivinanza del numero 
	cout<<"\t\t\t\t\t\t**JUEGO ADIVINA EL NUMERO**\n\n\n";
   	cout<<"\n \t\t\t\t\t\t�Te gustaria jugar? \n";
    cout<<"\t\t\t\t\t\t1.- Comenzar \n";
    cout<<"\t\t\t\t\t\t2.- Salir \n";
    cin>>opc;
   
    while (opc!=2)
    {  	
			cout<<"\t\t\t\t\t\t*Encuentra un numero entre el 0 y 100* \n";
			num = rand() % 100;
	        printf("\t\t\t\t\t\t\n Introduce numero: ");
	        cin>>num2;
        while(num !=num2)
			{
	            if (num>num2)
				{
	               cout<<"\t\t\t\t\t\tEs mayor\n";
	            }
	            else
				{
	                 cout<<"\t\t\t\t\t\tEs menor\n";
				}
	            cout<<"\n Introduce numero: ";
	            cin>>num2;
        	}
        cout<<"\n\t\t\t\t\t\t Has acertado! \n";
        cout<<"\n\t\t\t\t\t\t 1.- Jugar de nuevo";
        cout<<"\n\t\t\t\t\t\t 2.- Salir.";
        cin>>opc;
	system("pause");
	system("cls");
    }     
	break; 
		case 3://***********aqui empieza las ecuaciones************
		cout<<"\t\t\t\t\t\tHaz las operaciones en tu libreta\n"<<"\t\t\t\t\t\t    1.-Ecuacion 1\n"<<"\t\t\t\t\t\t    2.-Ecuacion 2\n"<<"\t\t\t\t\t\t    3.-Ecuacion 3\n";
		cin>>opc4; 
	switch(opc4){
			case 1:	
				cout<<"\t\t\t\t\t\t2-X=X-8\n";
				cout<<"\t\t\t\t\t\t1)X=10\n";
				cout<<"\t\t\t\t\t\t2)X=7.5\n";
				cout<<"\t\t\t\t\t\t3)X=5\n";
				cout<<"\t\t\t\t\t\t4)X=8.7\n";
				cin>>r1;
					if(r1==3)
					{
						cout<<"\t\t\t\t\t����������Muy Bien!!!!!!!! tu si eres pro \n";
					}			
					else
					{
						cout<<"\t\t\t\t\t******* Lo siento, perdiste :( ******* \n";
					}
			system("pause");
			system("cls");		
			break;
			case 2:
				cout<<"\t\t\t\t\t\t-2(1-X)=2X-3\n";
				cout<<"\t\t\t\t\t\t1)X=0\n";
				cout<<"\t\t\t\t\t\t2)0=-6\n";
				cout<<"\t\t\t\t\t\t3)0=6\n";
				cout<<"\t\t\t\t\t\t4)X=6\n";
				cin>>r2;
					if(r2==2)
						{
						cout<<"\t\t\t\t\t����������Muy Bien!!!!!!!! tu si eres pro \n";
						}			
							else
							{
								cout<<"\t\t\t\t\t******* Lo siento, perdiste :( ******* \n";
							}
			system("pause");
			system("cls");
			break;
			case 3:
				cout<<"\t\t\t\t\t\t1+1/2(4X-6)=-2\n";
				cout<<"\t\t\t\t\t\t1)X=1/2\n";
				cout<<"\t\t\t\t\t\t2)X=3/4\n";
				cout<<"\t\t\t\t\t\t3)0=0\n";
				cout<<"\t\t\t\t\t\t4)X=0\n";
				cin>>r3;
					if(r3==4)
						{
						cout<<"\t\t\t\t\t����������Muy Bien!!!!!!!! tu si eres pro \n";
						}			
							else
							{
								cout<<"\t\t\t\t\t******* Lo siento, perdiste :( ******* \n";
							}
			system("pause");
			system("cls");
			break;
				}
				case 4:
				cout<<"\t\t\t\t***************Signos del zodiaco***************\n";
				cout<<"\t\t\t\t\tCual es el mes en el que naciste(en numero del 1 al 12)\n";
				cin>>mes;
				cout<<"\t\t\t\t\t\tCual es el dia en el que naciste\n";
				cin>>dia;
				switch(mes){
					case 1:
						if(dia<21){
							cout<<"\t\t\t\t\t\tTu signo es : \nCapricornio\n";
						}
						else{
							cout<<"\t\t\t\t\t\tTu signo es : \nAcuario\n";
						}
						break;
					case 2:
						if(dia<19){
								cout<<"\t\t\t\t\t\tTu signo es : \nAcuario\n";
						}
						else{
							cout<<"\t\t\t\t\t\tTu signo es : \nPisis\n";
						}	
						break;
					case 3:
						if(dia<21){
						 	cout<<"\t\t\t\t\t\tTu signo es : \nPisis\n";	
						}	
						else{
							cout<<"\t\t\t\t\t\tTu signo es : \nAries\n";
						}
						break;
					case 4:
						if(dia<21){
							cout<<"\t\t\t\t\t\tTu signo es : \nAries\n";
						}
						else{
							cout<<"\t\t\t\t\t\tTu signo es : \nTauro\n";
						}
						break;
					case 5:
						if(dia<21){
							cout<<"\t\t\t\t\t\tTu signo es : \nTauro\n";
						}
						else{
							cout<<"\t\t\t\t\t\tTu signo es : \nGeminis\n";
						}
						break;
					case 6:
							if(dia<21){
								cout<<"\t\t\t\t\t\tTu signo es : \nGeminis\n";
							}
							else{
								cout<<"\t\t\t\t\t\tTu signo es : \nCancer\n";
							}
							break;
					case 7:
							if(dia<23){
								cout<<"\t\t\t\t\t\tTu signo es : \nCancer\n";
							}
							else{
								cout<<"\t\t\t\t\t\tTu signo es : \nAcuario\n";
							}
							break;
					case 8:
							if(dia<25){
								cout<<"\t\t\t\t\t\tTu signo es : \nLeo\n";
							}
							else{
								cout<<"\t\t\t\t\t\tTu signo es : \nVirgo\n";
							}
							break;
					case 9:
							if(dia<24){
								cout<<"\t\t\t\t\t\tTu signo es : \nVirgo\n";
							}
							else{
								cout<<"\t\t\t\t\t\tTu signo es : \nLibra\n";
							}
							break;
					case 10:
							if(dia<24){
								cout<<"\t\t\t\t\t\tTu signo es : \nLibra\n";
							}
							else{
								cout<<"\t\t\t\t\t\tTu signo es : \nEscorpio\n";
							}
							break;
					case 11:
							if(dia<23){
								cout<<"\t\t\t\t\t\tTu signo es : \nEscorpio\n";
							}
							else{
								cout<<"\t\t\t\t\t\tTu signo es : \nSagitario\n";
							}
							break;
					case 12:
							if(dia<22){
								cout<<"\t\t\t\t\t\tTu signo es : \nSagitario\n";
							}
							else{
								cout<<"\t\t\t\t\t\tTu signo es : \nCapricornio\n";
							}
							break;		
				}
				system("pause");
				system("cls");
					case 5:
							cout<<"\t\t\t\t\t\tRecomendaciones de Peliculas \n";
							cout<<"\n\t\t\t\t\t\t1.- Comedia\n"<<"\n\t\t\t\t\t\t2.- Terror\n"<<"\n\t\t\t\t\t\t3.- Romance\n"<<"\n\t\t\t\t\t\t4.- Accion\n"<<"\n\t\t\t\t\t\t5.- Ciencia Ficcion\n";
							cin>>opc;
							switch(opc){
							case 1:
								cout<<"\t\t\t\t\t\tTe recomendamos:\n"<< "\t\t\t\t\t-Los Cazafantasmas\n"<<"\t\t\t\t\t-Y donde estan las rubias?\n"<< "\t\t\t\t\t-La mascara\n";
								break;
							case 2: 
								cout<<"\t\t\t\t\t\tTe recomendamos: \n"<< "\t\t\t\t\t -El resplandor\n"<< "\t\t\t\t\t -Saga El conjuro\n"<< "\t\t\t\t\t -El Titere, SAW I y II\n";
								break;
							case 3:
								cout<<"\t\t\t\t\t\tTe recomendamos:\n"<< "\t\t\t\t\t -El diario de una pasion\n"<< "\t\t\t\t\t -500 dias con ella\n"<< "\t\t\t\t\t -El stand de los besos, Pretty Woman\n";
								break;
							case 4:
								cout<<"\t\t\t\t\t\tTe recomendamos:\n"<< "\t\t\t\t\t -Saga James Bond\n"<< "\t\t\t\t\t -Saga Imposiible Mision\n"<< "\t\t\t\t\t -Saga Fast and Furious\n";
								break;
							case 5:
								cout<<"\t\t\t\t\t\tTe recomendamos:\n"<< "\t\t\t\t\t -Trilogia Volver al Futuro\n"<< "\t\t\t\t\t -Saga Terminator\n"<< "\t\t\t\t\t -Matrix, Ghost in the sehll\n";
								break;
							}
							system("pause");
							system("cls");
						}
			}while (opc!=6);
			return 0;
	}




