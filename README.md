# codingchalleng





#include <iostream>

using namespace std;


int countBuildings(int arr[], int n)
{

    int count = 1;
 

    int curr_max = arr[0];

    for (int i=1; i<n; i++)

    {  

        if (arr[i] > curr_max)

        {

            count++;

            curr_max=arr[i];

        }

    }

 

    return count;
}
int cal_length(int a, int b);

int length;

 {
cout<<"eneter first value";

cin>>a;

cout<<"eneter second value";

cin>>b;

{
length=1/2(a*b*count);
}

return length;

}


int main()
{

    int arr[] = {7, 4, 8, 2, 9};

    int n = sizeof(arr) / sizeof(arr[0]);
    int length;

    cout << countBuildings(arr, n);

    cout<<cal_length(length);

    return 0;
}

