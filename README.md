# ProgramC_TLS21
Nama : Sefvia Lie, Kelompok A-Star

//Program Menginput Data Pasien
#include <iostream>

using namespace std;

int main(){
    string Name;
    int Age;
    string Gender;
    string Blood_Type;
    int HealthID;
    int Phone;
    int Emergency_contact;
    
    cout << "                             Welcome To DTETI Hospital\n";
    cout << "Please enter your data...\n";
    cout << "Enter Name               : ";
    getline(cin,Name);
    cout << "Enter Age                : ";
    cin >> Age;
    cout << "Enter Gender             : ";
    cin >> Gender;
    cout << "Enter Blood Type         : ";
    cin >> Blood_Type;
    cout << "Enter Health ID          : ";
    cin >> HealthID;
    cout << "Enter Phone Number       : ";
    cin >> Phone;
    cout << "Enter Emergency Contact  : ";
    cin >> Emergency_contact;
    
    cout << "\nPlease re-check your data : ";
    cout << "\n      ---Patient Data---\n";
    cout << "Name              : " << Name << endl;
    cout << "Age               : " << Age << endl;
    cout << "Gender            : " << Gender << endl;
    cout << "Blood Type        : " << Blood_Type << endl;
    cout << "Health ID         : " << HealthID << endl;
    cout << "Phone             : +62" << Phone << endl;
    cout << "Emergency Contact : +62" << Emergency_contact << endl;
    
    return 0;
}
