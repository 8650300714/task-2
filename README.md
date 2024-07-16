# task-2
#include <iostream>
using namespace std;
int main ()
{
  int pocketmoney , date;
  cout << "date";
  cin>>date;

  for (int date = 1; date <= 30; date++)
	{
	  if (date % 2 !=0)
		{
		  continue;

		}
	  if (pocketmoney == 0)
		{
		  break;
		}
	  cout << "GO TODAY ON TRIP" << endl;
	  pocketmoney = pocketmoney - 300;
	}

  return 0;
}
