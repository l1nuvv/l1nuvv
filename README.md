### Привет, я Данила

**C++ разработчик** с фокусом на **высокопроизводительные вычисления** и **компьютерное зрение**.

![CodeWars](https://www.codewars.com/users/l1nuvv/badges/small)

![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat&logo=cmake&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat&logo=windows&logoColor=white)

---

### 🛠️ Стек технологий

Технологии, с которыми я работаю ежедневно на основе практического опыта.

| Категория               | Технологии                                                         |
|:------------------------|:-------------------------------------------------------------------|
| **Язык**                | `C++ (11/17/20)`                                                   |
| **Основные библиотеки** | `OpenCV`, `GDAL`, `Eigen`, `spdlog`, `OpenGL`, `GLFW`, `GTest`    |
| **Инструменты**         | `CMake`, `Git`, `OpenMP`, `Windows/Linux`, `Wireshark`            |
| **Домены**              | `Computer Vision`, `ГИС`, `Обработка изображений`, `Геостатистика`|

---

### 🔭 Проекты

#### **[Field Analyzer](https://github.com/l1nuvv/field_analyzer-showcase)** (Приватный проект)

Движок для высокопроизводительного анализа спутниковых снимков Sentinel-2.

* **Что делает:** Обрабатывает гигабайты `.jp2` изображений для расчета вегетационных индексов (NDVI, EVI, PRI) и выполняет геостатистический анализ для моделирования пространственных зависимостей.
* **Мой вклад:**
    * Разработал и реализовал основной конвейер обработки данных.
    * **Оптимизировал цикл вычисления вариограмм, достигнув ускорения в 3-4 раза** за счет параллелизации алгоритма с **OpenMP**.
    * Спроектировал и реализовал **потокобезопасную систему логирования** с использованием `std::mutex` и `std::lock_guard` для предотвращения гонок данных в параллельных секциях.
    * Снизил алгоритмическую сложность с O(N²) до O(N log N) за счет интеграции библиотеки **FLANN KD-Tree** для эффективного поиска ближайших соседей.

#### **[PCAP Parser](https://github.com/l1nuvv/Pcap_parser)**

Консольный анализатор сетевого трафика для PCAP файлов.

* **Возможности:**
    * Парсинг Ethernet-фреймов (linktype 1).
    * Статистика пакетов по длинам и MAC-адресам.
    * Извлечение IPv4/IPv6 пакетов с экспортом в бинарные форматы `.pack2` и `.pack4`.
    * Бенчмарки производительности сортировки.
* **Стек:** `C++11`, `CMake`, `Google Test`

---

### 📫 Контакты

**Email:** uxo1612@gmail.com  
**Telegram:** @dannnnzzc
