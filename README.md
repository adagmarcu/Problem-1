# Problem-1

int sum_even_numbers_array(int v[], int n)
{
int sum = 0;
for (int i = 0; i < n; i++) {
if (v[i] % 2 == 0) {
sum += v[i];
}

}
return sum;
}
