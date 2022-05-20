# Array dan Looping

## Tools

Untuk coding C++ secara online dapat menggunakan
- [Programiz](https://www.programiz.com/cpp-programming/online-compiler/)
- [OnlineGDB](https://www.onlinegdb.com/online_c++_compiler)
- [W3Schools](https://www.w3schools.com/cpp/trycpp.asp?filename=demo_compiler)

## Referensi
- [W3 - While Loop](https://www.w3schools.com/CPP/cpp_while_loop.asp)
- [W3 - Do While Loop](https://www.w3schools.com/CPP/cpp_do_while_loop.asp)
- [W3 - For Loop](https://www.w3schools.com/CPP/cpp_for_loop.asp)
- [W3 - Break & Continue](https://www.w3schools.com/CPP/cpp_break.asp)

## Pengulangan While

### Dasar

```cpp
#include <iostream>
using namespace std;

int main() {
  int jumlahTugas = 0;
  
  while(jumlahTugas < 5) {
    cout << jumlahTugas << " tugas untuk dikerjakan\n";
    jumlahTugas++;
  }
  
  return 0;
}
```

### Deret Genap

```cpp
#include <iostream>
using namespace std;

int main() {
  int pengali = 0;
  
  while(pengali < 5) {
    cout << pengali * 2 << " merupakan bilangan genap ke " << pengali << "\n";
    pengali++;
  }
  
  return 0;
}
```
