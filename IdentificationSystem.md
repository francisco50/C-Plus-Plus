# Identification System for Equatorial Guinea
#include #include <stdbool.h> #include

void myinfo();

using namespace std;

void myinfo() { string name, country, surnames, female, mname, fname, onames, snames;

cout << " What's your first Name : ";
cin >> name; cout << endl;
cout << " What is your Middle name : ";
cin >> surnames; cout << endl;
cout << " Enter other names if any : ";
cin >> onames; cout << endl;
cout << "  What's your spouse name : ";
cin >> snames;

cout << endl;
}

int main() { string name, country, surnames, female, fname, mname, onames, snames; char islamic, christianity, traditionalist, other; int age = 0, gender, province, city, religion, nationality = 0, answer, employ, profession; int choice = 0, select = 0, num = 0; enum Logical { Yes = 0, No = 1 }; int day, month, year; char stroke; stroke = '/'; day = 0, month = 0, year = 0;

char alphabets;
alphabets = 'a', 'b', 'c', ' d', ' e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', ' n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z';

gender = 1, 2, 3;
islamic = 7, christianity = 8, traditionalist = 9, other = 10;




while (gender = 1, 2, 3)
{
	cout << "\n IDENTIFICATION CARD OF EQUATORIAL GUINEA \n\n" << endl;
	cout << endl;
	cout << " Enter Gender  m or M for male, f or F for female and NS or ns for not sure ." << endl;
	cout << " 1. Male = [M/m] " << endl;
	cout << " 2.Female = [F/f] " << endl;
	cout << " 3. Other = [NS/ns] " << endl;
	cout << " Select 1,2 or 3  = ";
	cin >> gender;

	if (gender == 1)
	{
		cout << " .....Male.\n" << endl;
	}
	else if (gender == 2)
	{
		cout << " .....Female." << endl;
	}
	else if (gender == 3)
	{
		cout << " .....Other.\n" << endl;
	}
	else
	{
		cout << " .....Please choose again.\n" << endl;
	}
	break;
}



myinfo();

while (age <= 100)
{
	cout << " What's your Age : ";
	cin >> age;

	if (age >= 100)
	{
		cout << " Please choose a right age. ";
		cin >> age;
	}
	break;
}


cout << " \n What religion do you belong to ?\n" << endl;
cout << " 7. Islamic = I." << endl;
cout << " 8. Christianity = C. " << endl;
cout << " 9. Traditionalist = T. " << endl;
cout << " 10. Other = O." << endl;
cout << " Enter your religion from 7-6 = ";
cin >> religion;

switch (religion)
{
case 'I':
	cout << " Islamic." << endl;
	break;
case 'C':
	cout << " Christianity." << endl;
	break;
case 'T':
	cout << " Traditionalist." << endl;
	break;
case 'O':
	cout << " Other." << endl;
	break;
default:
	cout << " The number is out of range." << endl;
	break;
}

while (select == 11 || 12)
{
	cout << " \n What is your Nationality ? \n  " << endl;
	cout << " 11. Equatorial Guinea." << endl;
	cout << " 12. Other." << endl;
	cout << " Select from the choices 11-12 =  ";
	cin >> select;

	if (select == 11)
	{
		cout << " Equatorial Guinea." << endl;
	}
	else if (select == 12)
	{
		cout << " Alien . " << endl;
	}
	else if (select < 11 || select > 12)
	{
		cout << " Please speak to the customer service about your choice. Thank you " << endl;
	}
	break;
}

cout << "\n What province where you born in? \n" << endl;
cout << "13.LITORAL - LT." << endl;
cout << "14.BIOKO NORTE - BN." << endl;
cout << "15.KIE'-NTEM - KN." << endl;
cout << "16.CENTRO SUR - CS." << endl;
cout << "17.WELE-NZAS - WN." << endl;
cout << "18.ANNOBON - AN." << endl;
cout << "19.BIOKO SUR - BS." << endl;
cout << " Enter a choice from 13-19  = ";
cin >> province;

switch (province)
{
case 13:
	cout << " LITORAL." << endl;
	break;
case 14:
	cout << " BIOKO NORTE." << endl;
	break;
case 15:
	cout << " KIE'-NTEM." << endl;
	break;
case 16:
	cout << " CENTRO SUR." << endl;
	break;
case 17:
	cout << " WELE-NZAS." << endl;
	break;
case 18:
	cout << " ANNOBON." << endl;
	break;
case 19:
	cout << " BIOKO SUR." << endl;
	break;
default:
	cout << " This number is out of range." << endl;
	break;
}

cout << "\n What city are you from ?\n" << endl;
cout << "20. BATA ." << endl;
cout << "21. MALABO ." << endl;
cout << "22. EBEBIYIN." << endl;
cout << "23. ACONIBE." << endl;
cout << "24. ANISOC." << endl;
cout << "25. LUBA." << endl;
cout << "26. EVINAYONG." << endl;
cout << "27. MONGOMO." << endl;
cout << "28. MENGOMEYEN." << endl;
cout << "29. MICOMESENG." << endl;
cout << "30. REBOLA." << endl;
cout << "31. BIDJABIDJAN." << endl;
cout << "32. NIEFANG." << endl;
cout << "33. COGO." << endl;
cout << "34. NSOK." << endl;
cout << "35. PALEA." << endl;
cout << "36. MBINI." << endl;
cout << "37. NSORK." << endl;
cout << "38. AYENE." << endl;
cout << "39. NKINI." << endl;
cout << "40. MACHINDA." << endl;
cout << "41. ACURENAM." << endl;
cout << "42. CORISCO." << endl;
cout << "43. BANEY." << endl;
cout << "44. BICURGA." << endl;
cout << "45. NSANG." << endl;
cout << "46. NCUE." << endl;
cout << "47. BITICA." << endl;
cout << "48. RIO CAMPO." << endl;
cout << "49. RIABA." << endl;
cout << " Enter a choice from 20-49 = ";
cin >> city;

switch (city)
{
case 20:
	cout << " BATA.\n" << endl;
	break;
case 21:
	cout << " MALABO.\n" << endl;
	break;
case 22:
	cout << " EBEBIYIN.\n" << endl;
	break;
case 23:
	cout << " ACONIBE.\n" << endl;
	break;
case 24:
	cout << " ANISOC.\n" << endl;
	break;
case 25:
	cout << " LUBA.\n" << endl;
	break;
case 26:
	cout << " EVINAYONG.\n" << endl;
	break;
case 27:
	cout << " MONGOMO.\n" << endl;
	break;
case 28:
	cout << " MENGOMEYEN.\n" << endl;
	break;
case 29:
	cout << " MICOMESENG.\n" << endl;
	break;
case 30:
	cout << " REBOLA.\n" << endl;
	break;
case 31:
	cout << " BIDJABIJAN.\n" << endl;
	break;
case 32:
	cout << " NIEFANG.\n" << endl;
	break;
case 33:
	cout << " COGO.\n" << endl;
	break;
case 34:
	cout << " NSOK.\n" << endl;
	break;
case 35:
	cout << " PALEA.\n" << endl;
	break;
case 36:
	cout << " MBINI.\n" << endl;
	break;
case 37:
	cout << " NSORK.\n" << endl;
	break;
case 38:
	cout << " AYENE.\n" << endl;
	break;
case 39:
	cout << " NKINI.\n" << endl;
	break;
case 40:
	cout << " MACHINDA.\n" << endl;
	break;
case 41:
	cout << " ACURENAM.\n" << endl;
	break;
case 42:
	cout << " CORISCO.\n" << endl;
	break;
case 43:
	cout << " BANEY.\n" << endl;
	break;
case 44:
	cout << " BICURGA.\n" << endl;
	break;
case 45:
	cout << " NSANG.\n" << endl;
	break;
case 46:
	cout << " NCUE.\n" << endl;
	break;
case 47:
	cout << " BITICA.\n" << endl;
	break;
case 48:
	cout << " RIO CAMPO.\n" << endl;
	break;
case 49:
	cout << " RIABA.\n" << endl;
	break;
default:
	cout << " This number is out of range." << endl;
	break;
}



while (nationality == 50 || 51)
{

	cout << "Enter your Mothers first name :";
	cin >> mname; cout << endl;
	cout << " Enter your mothers last name : ";
	cin >> surnames; cout << endl;
	cout << " \n What is your mother's Nationality ? \n  " << endl;
	cout << " 50. Equatorial Guinea." << endl;
	cout << " 51. Alien." << endl;
	cout << " Select from the choices 50-51 =  ";
	cin >> nationality;

	if (nationality == 50)
	{
		cout << " .....Equatorial Guinea.\n" << endl;
	}
	else if (select == 51)
	{
		cout << " .....Alien . \n" << endl;
	}
	else if (nationality < 50 || nationality > 51)
	{
		cout << " .....Please speak to the customer service about your choice. Thank you\n" << endl;
	}
	break;
}

while (nationality == 52 || 53)
{
	cout << "Enter your Fathers first name : ";
	cin >> fname; cout << endl;
	cout << " Enter your fathers last name : ";
	cin >> surnames;
	cout << " \n What is your father's Nationality ? \n  " << endl;
	cout << " 52. Equatorial Guinea." << endl;
	cout << " 53. Alien." << endl;
	cout << " Select from the choices 52-53 = ";
	cin >> nationality;

	if (nationality == 52)
	{
		cout << " .....Equatorial Guinea." << endl;
	}
	else if (nationality == 53)
	{
		cout << " .....Alien . " << endl;
	}
	else if (nationality < 52 || nationality > 53)
	{
		cout << " .....Please speak to the customer service about your choice. Thank you" << endl;
	}
	break;
}
while (answer = Yes || No)
{
	Yes == 1, No == 0;
	cout << " \n Marital status \n" << endl << " 54. Are you married ?" << " Select [ 1 = Yes /0 = No ] = ";
	cin >> answer;

	if (answer == 1)
	{
		cout << " Yes \n" << endl;
	}
	if (answer == 0)
	{
		cout << " No\n " << endl;
	}
	break;
}
while (answer = Yes || No)
{
	cout << " 55. Do you have children ? " << " Select [ 1 = Yes /0 = No ] = ";
	cin >> answer;

	if (answer == 0)
	{
		cout << " No\n " << endl;
	}
	if (answer == 1)
	{
		cout << " Yes \n" << endl;

		while (num >= 0 || num <= 20)
		{
			cout << " 56. How many children ?" << endl;
			cin >> num;

			if (num <= 0 || num >= 20)
			{
				cout << " Wrong answer.\n" << endl;
			}
			break;
		}

	}
	break;
}

while (nationality == 58 || 59)
{
	cout << " \n Whats the nationality of your spouse ?\n " << endl;
	cout << " 58. Equatorial Guinea." << endl;
	cout << " 59. Alien." << endl;
	cout << " Select from the choices 58-59 = ";
	cin >> nationality;

	if (nationality == 58)
	{
		cout << " .....Equatorial Guinea.\n" << endl;
	}
	else if (nationality == 59)
	{
		cout << " .....Alien .\n " << endl;
	}
	else if (nationality < 58 || nationality > 59)
	{
		cout << " .....Please speak to the customer service about your choice. Thank you\n" << endl;
	}
	break;
}
cout << " Do you own a car ? " << endl;
cout << " Select [ 1 = Yes /0 = No ] = ";
cin >> answer;

if (answer = 1)
{
	cout << " .....Yes.\n " << endl;
}
else if (answer = 0)
{
	cout << " .....Too bad.\n " << endl;
}


cout << " Enter your date of marriage being numbers in the form 01/01/0001. " << endl;


while (((day >= 1 || day <= 30)) || !(day == alphabets))
{

	cout << "...Day : ";
	cout << "1---30 : ";
	cin >> day;
	cout << endl;

	if ((day == alphabets) || !(day >= 1) || !(day <= 30))
	{
		cout << " .....Please enter the right number.\n " << endl;
		cin >> day;
	}

	break;
}
while ((month >= 1 || month <= 12) || !(month == alphabets))
{
	cout << "...Month :" << endl << "-01 January " << endl << "-02 February" << endl << "-03 March " << endl << "-04 April " << endl
		<< "-05 May " << endl
		<< "-06 June " << endl
		<< "- 07 July " << endl
		<< "-08 August " << endl
		<< "-09 Septemper " << endl
		<< "-10 October " << endl
		<< "-11 November " << endl
		<< "-12 December " << endl
		<< "...Month :";
	cin >> month;
	cout << endl;

	if (!(month >= 1) || !(month <= 12) || (month == alphabets))
	{
		cout << " .....Please enter the right number.\n " << endl;
		cin >> month;

	}

	break;
}
while ((year >= 1800) || (year <= 3000) || !(year == alphabets))
{
	cout << "...Year : "; cin >> year;
	cout << endl;

	if (!(year >= 1000) || !(year <= 3000) || (year == alphabets))
	{
		cout << " .....Please enter the right number.\n " << endl;
		cin >> year;

	}

	break;
}


cout << " Are you emoloyed or unemployed ? " << endl;
cout << " Select [ 1 = Yes /0 = No ] = ";
cin >> employ;

if (answer = 1)
{
	cout << " .....Employed.\n " << endl;
	cout << " Whats your profession ? :: ";
	cin >> profession;
}
else if (answer = 0)
{
	cout << " Unemployed.\n " << endl;
}















cout << "\n Information below is according to what provided by you.\n" << endl;
cout << "Gender : \n" << gender;
cout << "First Name :: \n" << name;
cout << "Middle Name :: \n" << surnames;
cout << "Other Names :: \n" << onames;
cout << "Spouse Name :: \n" << snames;
cout << "Age :: \n" << age;
cout << "Religion :: \n" << religion;
cout << "Nationality :: \n" << select;




cout << " Your date of Marriage is : " << day << stroke << month << stroke << year << "." << endl;





































system("pause");
return 0;
