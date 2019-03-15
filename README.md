// Fibonacci_C
#include <stdio.h>
int main() {
	int i=3, penult=1, ult=1, m;
	while(i<=10){
		m=penult+ult;
		ult=penult;
		penult=m;
		if(i>=0)printf("%d " , m);
		i++;
			}
return 0;			
}

