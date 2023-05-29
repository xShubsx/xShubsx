int[] a = new int[10];
for (int i = 0; i < a.Length; i++)
{
    Console.WriteLine("Digite o {0} valor: ", i + 1);
    a[i] = int.Parse(Console.ReadLine());
}
bool[] b = new bool[10];
for (int i = 0; i < a.Length; i++)
{
    if (a[i] <= 0)
    {
        b[i] = false;
    }
    else
    {
        b[i] = true;
    }
    Console.WriteLine(b[i]);
}
