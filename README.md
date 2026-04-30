


#include <iostream>
using namespace std;


class point {
public:
	int x;
	int y;

};

void main() {

	point p1, p2;
	p1.x = 10;
	p1.y = 20;
	p2.x = 900;
	p2.y = 700;

	point* p1 = new (point);
	p1->x = 100;
	p1->y = 100;
	point* p2 = new(point);


}
