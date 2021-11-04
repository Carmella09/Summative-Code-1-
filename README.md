# Summative-Code-1-

        #include <iostream>
        using namespace std;
        int main()
        {
            int age;
            char input;
            cout << "Please enter your age? (16-30 only) \n";
            cin >> age;

            if (age >= 16 && age <= 21)
            {
                cout << "\nDo you want to go to the Abu Dhabi Mall? (y/n) \n" << "y for yes \n" << "n for no\n\n";
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
                cout << "\nDo you want to go to Hawaii? (y/n) \n" << "y for yes \n" << "n for no\n\n";
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


