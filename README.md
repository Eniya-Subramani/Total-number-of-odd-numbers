# Total-number-of-odd-numbers
Public cass TotalOddNum {
Public static void main(String args[]) {
int count = 0;
for (int i = 1; i &lt;= 100; i++) {
if (i % 2 != 0) {
count++;
}
}
System.out.println(&quot;The count of odd numbers between 1 and 100 is: &quot; + count);
}
}
OUTPUT:
The count of odd numbers between 1 and 100 is: 50
