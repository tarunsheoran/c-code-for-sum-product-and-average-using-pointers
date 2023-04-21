# c-code-for-sum-product-and-average-using-pointers
// Online C compiler to run C program online #include &lt;stdio.h>  int main() {   int a = 3, b= 5;   int sum , pt ,ag;   dowork(a,b,&amp;sum,&amp;pt,&amp;ag);   printf("sum %d,pt %d, ag %d \n",sum , pt ,ag);          return 0; } void dowork(int a, int b , int *sum, int *pt, int *ag){     *sum = a+b;     *pt = a*b;     *ag = (a+b)/2; }
