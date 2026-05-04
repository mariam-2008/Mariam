```cpp
#include <iostream>
#include <string>
using namespace std;
int main() {
string studentData[2][3][2] = {
{
{"Maryam", "95"},
{"Ahmed", "88"},
{"Zainab", "91"}
},
{
{"Ali", "82"},
{"Soso", "94"},
{"Nabaa", "89"}
}
};
for (int i = 0; i < 2; i++) {
for (int j = 0; j < 3; j++) {
cout << "Student: " << studentData[i][j][0] << " | Grade: " << studentData[i][j][1] << endl;
}
}
return 0;
}
