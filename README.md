# Summative-Code-1-

    #include <iostream>
    using namespace std;
    int main()
    {
      cout << "Please enter your age? (16-30 only) \n";
      int age;
      cin >> age;

      if (age >= 16 && age <= 21)
      {
        cout << "\nDo you want to go to the mall? (y/n) \n";
        char input;
        cin >> input;

        switch (input)
        {
        case 'y':
        case 'Y':
          cout << "\nEnjoy\n";
          break;

        case 'n':
        case 'N':
          cout << "\nCancelled\n";
          break;
        default:
          cout << "\nInvalid Input\n";
        }
      }

      else if (age >= 22 && age <= 30)
      {
        cout << "\nDo you want to go to Hawaii? (y/n) \n";
        char input;
        cin >> input;

        switch (input)
        {
        case 'y':
        case 'Y':
          cout << "\nEnjoy\n";
          break;

        case 'n':
        case 'N':
          cout << "\nCancelled\n";
          break;
        default:
          cout << "\nInvalid Input\n";
        }
      }
      else
      {
        cout << "\nInvalid Output\n";
      }
    }
