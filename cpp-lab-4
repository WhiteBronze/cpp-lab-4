#include <iostream>
#include <math.h>

using namespace std;
int n;




bool YesNo(int n) {
	if ((n*n + n) % 4 != 0) {
		return true;
	}
	else {
		return false;
	}


}



int main() {
	cin >> n;

	bool l, f = false;
	l = YesNo(n);

	

	if (l) {

		cout << "no";

	}
	else {
		f = true;
		cout << "yes" << endl;

	}


	if (f) {
		if ((n + 1) % 4 == 0) {


			cout << (n / 2) + 1 << endl;



			for (int i = 1; 2*i <= (n - 1); i = i + 2) {

				cout << i << " " << n - i << " ";

			}
			cout << endl;
			cout << n / 2 << endl;



			for (int i = 2; 2* i <= (n - 1); i = i + 2) {
				cout << i << " " << n - i << " ";
			}
			cout << n;
		}
		else {
			cout << n / 2 << endl;

			for (int i = 1; 2*i <= n; i = i + 2) {

				cout << i << " " << n + 1 - i << " ";

			}


			cout << endl;
			cout << n / 2 << endl;


			for (int i = 2; 2*i <= n ; i = i + 2) {

				cout << i << " " << n + 1 - i << " ";

			}
		}
	}
}
