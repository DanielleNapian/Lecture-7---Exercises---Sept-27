# Lecture-7---Exercises---Sept-27
TASK 1:

    #include <iostream>
    using namespace std;

    int main()
    {
      char grade;
      cout << "\nEnter the letter for grade: ";
      cin >> grade;

      switch (grade)
      {
      case 'A':
        /*Marks between 90-100*/
        cout << "\nYour numeric grade was between 90 and 100" << endl;
        break;

      case 'B':
        /*Marks between 80-89*/
        cout << "\nYour numeric grade was between 80 and 89" << endl;
        break;

      case 'C':
        /*Marks between 70-79*/
        cout << "\nYour numeric grade was between 70 and 79" << endl;
        break;

      case 'D':
        /*Marks between 60-69*/
        cout << "\nYour numeric grade was between 60 and 69" << endl;
        break;

      case 'E':
        cout << "\nYour numeric grade was below 60" << endl;

      default:

        cout << "\nInvalid letter grade" << endl;
        break;
      }

      return 0;
    }
  
 TASK 2:
 
        #include <iostream>
    #include <ctype.h>
    using namespace std;
    int main() {
        bool musicfriend;
        bool musicinst;
        cout << "You want to start a band, but you need another person to play with. Do you have a friend that can play an instrument to start a band with?" << endl;
        cout << "Enter 1 if yes, 0 if no" << endl;
        cin >> musicfriend;
        if (musicfriend == true) {
            cout << "Can he play the guitar and/or drums?" << endl;
            cout << "Enter 1 if yes, 0 if no" << endl;
            cin >> musicinst;
            if (musicinst == true) {
                cout << "They qualify!" << endl;
            }
            else if (musicinst == false) {
                cout << "Find another friend that can play those instruments" << endl;
            }
            else {
                cout << "Invalid. Try again." << endl;
            }
        }
        else if(musicfriend == false){
            cout << "Make a friend that can play instruments then" << endl;
        }
        cin.get();
        return 0;
    }

  
  TASK 3: SCENARIO 
  
         #include <iostream>
    using namespace std;

    int main()
    {
        int mins, money;

        cout << "How many minutes before your friend goes with you? ";
        cin >> mins;

        if (mins >= 15) {
            cout << "\nSince your friend is going to arrive for another 15 minutes or more,\nhow much money do you have in change? ";
            cin >> money;

            if (money >= 5) {
                cout << "\nGo buy a coffee" << endl;
            } else {
                cout << "\nConsidering that you don't have enough change to buy a coffee,\ngo for a walk around the town" << endl;
            }
        }
        if (mins < 15) {
            cout << "\nYour friend is going to arrive soon, sit in the food zone and wait";
    return 0;
        }
    }
 
 TASK 4:
 
     #include <iostream>
    using namespace std;

    int main()
    {
        double magnitude;

        cout << "Enter the magnitude of the earthquake: ";
        cin >> magnitude;

        if (magnitude <= 2.0)
        {
            cout << "The earhquake is MICRO" << endl;
        }
        else if (magnitude >= 2.0 && magnitude <= 3.0)
        {
            cout << "The earthquake is VERY MINOR" << endl;
        }
        else if (magnitude >= 3.0 && magnitude <= 4.0)
        {
            cout << "The earthquake is MINOR" << endl;
        }
        else if (magnitude >= 4.0 && magnitude <= 5.0)
        {
            cout << "The earthquake is LIGHT" << endl;
        }
        else if (magnitude >= 5.0 && magnitude <= 6.0)
        {
            cout << "The earthquake is MODERATE" << endl;
        }
        else if (magnitude >= 6.0 && magnitude <= 7.0)
        {
            cout << "The earthquake is STRONG" << endl;
        }
        else if (magnitude >= 7.0 && magnitude <= 8.0)
        {
            cout << "The earthquake is MAJOR" << endl;
        }
        else if (magnitude >= 8.0 && magnitude <= 10.0)
        {
            cout << "The earthquake is GREAT" << endl;
        }
        else if (magnitude >= 10)
        {
            cout << "The earthquake is METEORIC" << endl;

            return 0;
        }
    }
