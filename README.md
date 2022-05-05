# Codechef-CMASKS
#include <iostream>
using namespace std;

int main() {
	// your code goes here
	int T,X,Y;
	cin >> T;
	for(int i=0;i<T;i++){
	    cin >> X >> Y;
	    if(100*X < 10*Y)
	        cout << "Disposable" << endl;
	    else if(100*X > 10*Y)
	        cout << "cloth" << endl;
	    else
	        cout << "cloth" << endl;
	}
	return 0;
}
