# lab4
Lab4 
姓名:劉承叡
學號:F74031116

A:
  compile:  g++ -o lab4_a lab4_a.cpp
  執行:     nm lab4_a
  結果:     00000000004004b4 T _Z7averagePdRd  ==>double average(double * n1,double & n2)
            00000000004004e2 T _Z7averageif    ==>int average(int n1, float n2)
  
B.
  compile:  g++ -o lab4_b lab4_b.cpp
  執行:     ./lab4_b
  結果:   1 8
          4 8
          4 8
          8 8
          
  Reason:
          byte  位址
  char     1     8
  int      4     8
  float    4     8
  double   8     8
  
  byte:佔用的記憶體空間
  
  位址:指標的記憶體位址，這項必須要統一才去能定位全部的位址。
       8是因為作業系統本身是64bit(8bytes),如果在32bit的系統環境執行，位址就會變成4
 
  
