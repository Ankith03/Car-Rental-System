# Car-Rental-System
#ifndef _LOGIN_H
#define _LOGIN_H

class Login {
public: 
    String Username;
    String Password;
    
void Getdetails();
    
void Checkdetails();
};

#endif //_LOGIN_H
#ifndef _CUSTOMERDETAILS_H
#define _CUSTOMERDETAILS_H

class Customerdetails {
public: 
    string Name;
    int Contact_number;
    void Attribute1;
    void Display;
    
void Getdetails();
    
void Display();
};

#endif //_CUSTOMERDETAILS_H

#ifndef _CARSELECTION_H
#define _CARSELECTION_H

class Carselection {
public: 
    String Car;
    
void SelectCar();
};

#endif //_CARSELECTION_H
#ifndef _CARDETAILS_H
#define _CARDETAILS_H

class Cardetails {
public: 
    
void Display();
};

#endif //_CARDETAILS_H
#ifndef _RENTDETAILS_H
#define _RENTDETAILS_H

class Rentdetails {
public: 
    int NumberofDays;
    int NumberofCars;
    int Advancedamt;
    int Rent;
    
void Getdetails();
    
void Calculaterent();
    
void Displayrent();
};

#endif //_RENTDETAILS_H
#ifndef _TRANSACTION_H
#define _TRANSACTION_H

class Transaction {
public: 
    int Rent;
    int Advancedamt;
    int Payableamt;
    
void Calcpayable();
    
void Tansaction();
};

#endif //_TRANSACTION_H
#ifndef _INVOICE_H
#define _INVOICE_H

class Invoice {
public: 
    string Invoice_number;
    string Name;
    int Contact_number;
    string Car;
    int NumberofCars;
    int NumberofDays;
    int Rent;
    int Advancedamt;
    string Transactionstatus;
    
void Display();
};

#endif //_INVOICE_H

