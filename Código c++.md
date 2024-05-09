///código c++
#include <iostream>

#include <string>

using namespace std;



int main() {

    string entero = "nuemeros";

    cout << entero << endl;

    cout << typeid(entero).name() << endl;



    int edad;

    cout << "Introduce tu edad: ";

    cin >> edad;

    cout << "Tu edad es: " << edad << endl;

    cout << typeid(edad).name() << endl;



    cout << "Introduce tu edad: ";

    cin >> edad;

    cout << "Tu edad es: " << edad << endl;

    cout << typeid(edad).name() << endl;



    string nombre = "Evert Limber Cuevas Espinoza";

    cout << nombre[0] << endl;

    cout << nombre.substr(0, 7) << endl;

    cout << nombre.substr(20) << endl;

    cout << nombre.substr(0, 20) << endl;

    cout << nombre.replace(0, 5, "Luis") << endl;

    cout << nombre.length() << endl;



    string nombres[] = {"nombre1", "nombre2", "nombre3"};

    cout << nombres[1] << endl;

    cout << nombres[0] << ", " << nombres[1] << endl;

    nombres[3] = "nombre4";

    nombres[1] = "nombre10";

    cout << nombres[3] << endl;



    return 0;

}

