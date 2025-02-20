#include <iostream>
#include <cstdlib>

int main() {
  
  std::cout << "MAGIC 8-BALL SAYS:\n\n";

  srand(time(NULL));

  int answer = std::rand() % 10;

  if (answer == 0) {
    std::cout << "It is certain.\n";
  }

  else if (answer == 1){
    std::cout << "Very doubtful.\n";
  }

  else if (answer == 2) {
    std::cout << "mmmmm ask again.\n";
  }

  else if (answer == 3) {
    std::cout << "Heck yessss.\n";
  }

  else if (answer == 4) {
    std::cout << "Cannot predict now.\n";
  }

  else if (answer == 5) {
    std::cout << "Very doubtful.\n";
  }

  else if (answer == 6) {
    std::cout << "Without a doubt.\n";
  }
  
  else if (answer == 7) {
    std::cout << "My sources say no.\n";
  }

  else if (answer == 8) {
    std::cout << "Reply hazy, try again.\n";
  }

  else {
    std::cout << "Very doubtful.\n";
  }
}
