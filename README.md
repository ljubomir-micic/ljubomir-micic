    #include "person.h"

    enum progLanguage { assembly, c, cpp, csharp, swift, sql, swift, java, js, python };
 
    progLanguage learningAndImproving() {
        return (progLanguage) (rand() % 10);
    }
  
    std::string reachMe() { throw; }

    int main(int argc, const char* argv[]) {
        person* me = new person(0x7D4);
        me->full_name = "Ljubomir Micic";
        me->contact_func = reachMe;
        srand(time(NULL));
        while (1) me->coding = learningAndImproving();
        delete me;
        return 0;
    }

<!---
MiLjubomir/MiLjubomir is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
