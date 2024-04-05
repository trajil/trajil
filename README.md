# Hey, I'm Eugene! 👋

Welcome to my GitHub space where I tinker with C++ and Python and build bridges between problems and solutions. Feel free to connect with me!

![C++](https://img.shields.io/badge/-C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
<!-- TryHackMe Badge -->
[![TryHackMe Badge](https://tryhackme-badges.s3.amazonaws.com/Trajil.png?8)](https://tryhackme.com/p/Trajil)

```cpp
#include <friendlyness>
#include <passion>
#include <iostream>

class WhoAmI {
  std::string user = "Eugene Gugel";
  std::string current_edu = "GFN";
  std::vector<std::string> currently_learning = {"C++", "Software Development"};
  std::string fun_fact = "I have a penchant for the tranquility of Koblenz.";
  std::vector<std::string> hobbies = {
    "Power Lifting",
    "Tech",
    "Cycling",
    "Sci-Fi Movies"
  };

public:
  void getCity() {
    std::cout << "Koblenz, Germany - best place in Germany." << std::endl;
  }
  
  void Ambitions() {
    std::cout << "Striving to become a proficient Security Developer." << std::endl;
    std::cout << "Aiming to complete my personal projects and contribute to open source." << std::endl;
  }
};

int main() {
  WhoAmI eugene;
  eugene.getCity();
  eugene.Ambitions();
  return 0;
}
```


- 🔭 I’m currently working on:
      A C++ generator for password dictionaries to be used in pen testing enviroments (dictionary attacks)
