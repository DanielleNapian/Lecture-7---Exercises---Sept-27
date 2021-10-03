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
 
      #include<iostream>
    #include<string>
    using namespace std;

    int main()
    {
        bool musicalFriend = true;
        string friendPlays = "guitar";
        string yesNo;

        cout << "What intrument do you play?" << endl;
        cin >> friendPlays;

        if (friendPlays == "guitar") {
            cout << "do you want to join the band?" << endl;
            cin >> yesNo;

            if (yesNo == "yes") {
                cout << " welcome to the band" << endl;
            }
            else
                cout << " okay thank you for participating" << endl;

        }
        else {
            cout << "okay bye" << endl;
        }


    }
  
  TASK 3: SCENARIO 1
  
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
