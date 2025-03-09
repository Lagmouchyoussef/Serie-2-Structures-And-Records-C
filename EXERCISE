#include <stdio.h>
#include <stdlib.h>
#include <string.h>

typedef struct {
    int x;
    int y;
} point;

typedef struct {
    char marque[50];
    char modele[50];
    int annee;
    float prix;
} voiture;

typedef struct {
    char nom[50];
    int age;
    char type[30];
} animal;

typedef struct {
    char marque[50];
    char modele[50];
    float prix;
    int etanche;
} montre;

int main() {
    point p1;
    p1.x = 10;
    p1.y = 20;
    printf("Point Pi: (%d, %d)\n", p1.x, p1.y);

    voiture v1;
    strcpy(v1.marque, "Toyota");
    strcpy(v1.modele, "Corolla");
    v1.annee = 2020;
    v1.prix = 20000.0;
    printf("Car: %s %s, Year: %d, Price: %.2f\n", v1.marque, v1.modele, v1.annee, v1.prix);

    animal ai;
    strcpy(ai.nom, "Rex");
    ai.age = 5;
    strcpy(ai.type, "Dog");
    printf("Animal: %s, Age: %d, Type: %s\n", ai.nom, ai.age, ai.type);

    montre m1;
    strcpy(m1.marque, "Rolex");
    strcpy(m1.modele, "Submariner");
    m1.prix = 8000.0;
    m1.etanche = 1;
    printf("Watch: %s %s, Price: %.2f, Waterproof: %s\n", m1.marque, m1.modele, m1.prix, m1.etanche ? "Yes" : "No");

    return 0;
}