## <h1 align="center">🖐️👨‍🎓Привет, я Артём!</h1>
<p> <img src="https://img.shields.io/badge/ITMO-студент-blue?style=for-the-badge" alt="ITMO" /> <img src="https://img.shields.io/badge/C++-learning-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" /> <img src="https://img.shields.io/badge/Git-GitHub-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" /> </p>

## `Time to lock in. Без усилия нет прогресса.`

## 
1. 🎓 Студент первого курса ИТМО
2. 💻 Учусь программировать и пишу на C++
3. 🔧 Осваиваю Git и работу с репозиториями
4. 🌏 Хочу путешествовать и когда-нибудь переехать в Китай
5. 🎯 Строю большие планы и иду к ним шаг за шагом
6. 🛠 Технологии
7. Языки: C++
8. Инструменты: Git, GitHub
9. Сейчас изучаю: алгоритмы и структуры данных
## <p align="center">🎯 Цели по жизни/p>
-|----------------------------------|-------------------------
№|	Цель	                        |Статус
1|	Поступить в ИТМО	            |✅ Выполнена
2|	Отучиться 1 курс	            |⏳ Не выполнена
3|	Отучиться 2 курс	            |⏳ Не выполнена
4|	Отучиться 3 курс	            |⏳ Не выполнена
5|	Отучиться 4 курс	            |⏳ Не выполнена
6|	Магистратура, 1 курс	        |⏳ Не выполнена
7|	Магистратура, 2 курс	        |⏳ Не выполнена
8|	Переезд в Китай	                |⏳ Не выполнена
9|	Купить спорткар Xiaomi YU7 GT	|⏳ Не выполнена

## <p align="center">💡 Немного кода</p>
Быстрая сортировка на C++ (QuickSort):
```cpp
#include <iostream>
#include <vector>

int contin(std::vector<int> &mass_c, int dno, int verh) {
  int pivot = mass_c[(dno + verh) / 2];
  int i = dno - 1;
  for (int j = dno; j < verh; j++) {
    if (mass_c[j] <= pivot) {
      i++;
      std::swap(mass_c[i], mass_c[j]);
    }
  }
  std::swap(mass_c[i + 1], mass_c[verh]);
  return i + 1;
}

void quick_sort(std::vector<int> &mass_q, int dno, int verh) {
  if (dno < verh) {
    int pivot = contin(mass_q, dno, verh);
    quick_sort(mass_q, dno, pivot - 1);
    quick_sort(mass_q, pivot + 1, verh);
  }
}

int main() {
  int n = 0;
  std::cin >> n;
  std::vector<int> massive(n);
  for (int i = 0; i < n; i++) {
    std::cin >> massive[i];
  }
  quick_sort(massive, 0, n - 1);
  for (int i = 0; i < n; i++) {
    std::cout << massive[i] << " ";
  }
  std::cout << "\n";
  return 0;
}
```
📊 Статистика GitHub
<p align="center"> <img height="170" src="https://github-readme-stats.vercel.app/api?username=USERNAME&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub stats" /> <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=USERNAME&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" /> </p> <p align="center"> <img src="https://streak-stats.demolab.com/?user=USERNAME&theme=tokyonight&hide_border=true" alt="GitHub streak" /> </p>