```c
#define _CRT_SECURE_NO_WARNINGS
#include<stdio.h>
int main() {
	int n[8][9];
	
	for (int i = 0; i < 8; i++) {
		for (int j = 0; j < 9; j++) {
			n[i][j]=(i+2)*(j+1);
		}
	}
	for (int i = 0; i < 8; i++) {
		for (int j = 0; j < 9; j++) {
			printf("%d\t", n[i][j]);
		}
		printf("\n");
	}

	return 0;
}
```
