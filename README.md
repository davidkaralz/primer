// primer
#include <iostream>
#include <string>

int main()
{
  std::string name, second, complet;
  std::cout << "What is your firstname? ";
  std::cin >> name;
  std::cout << "What is your secondname? ";
  std::cin>> second;
  complet=name += second;
  std::cout << "Hello, " << complet << "!\n";
}
