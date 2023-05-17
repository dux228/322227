# 322227
322
//интерфейс
public interface InterfaceCalc
{
    //а - первый аргумент, b - второй
    void Put_A(double a); //сохранить а
 
    void Clear_A();
 
    double Multiplication(double b);
 
    double Division(double b);
 
    double Sum(double b);
 
    double Subtraction(double b); //вычитание
 
    double SqrtX(double b);
 
    double DegreeY(double b);
 
    double Sqrt();
 
    double Square();
 
    double Factorial();
 
    double MemoryShow(); //показать содержимое регистра памяти
 
    void Memory_Clear(); //стереть содержимое регистра памяти
 
    //* / + - к регистру памяти
    void M_Multiplication(double b);
 
    void M_Division(double b);
 
    void M_Sum(double b);
 
    void M_Subtraction(double b); //вычитание
}
