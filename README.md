## Oh! Hello there 👋 　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　
```cpp
#include <iostream>
#include <string>
#include <vector>

class SoftwareDeveloper {
private:
    std::string name;
    std::string status;
    std::vector<std::string> tongue_spoken;
    std::vector<std::string> adventure_prior;
    std::vector<std::string> venture_exploratory;
    std::string familiar;

public:
    SoftwareDeveloper() : 
        name("Yann Stephant"),
        status("ongoing professional Training"),
        tongue_spoken({"de_DE", "en_US", "fr_FR"}),
        adventure_prior({"BA in Communication Science", "Film Crew", "Military"}),
        venture_exploratory({"Forest Wandering", "Philosophy", "Science/Tech", "Survey of Celestial Influences", "Workout"}),
        familiar("Doggy") {}

    void say_something() const {
        std::cout << "I explore the great realm of programming to conjure up innovative projects." << '\n';
        std::cout << "Thanks for swinging by!" << std::endl;                            
    }
};

int main() {
    const SoftwareDeveloper me;
    me.say_something();
    return 0;
}
