# Factorial-validation
```csharp

        /// Functions:
        /// 
        /// Task 4:
        /// What's a void function?
        /// factorialVoid(int num);
        /// 
        /// Returnable:
        /// int result = factorialRseturnable(int num);

        static void factorialVoid(int num)
        {
            if (num <= 10 && num >= 0)
            {
                int y = 1;
                for (int i = 1; i <= num; i++)
                    y *= i;

                Console.WriteLine("Factorial (void): " + y);
            }
            else
            {
                Console.WriteLine("Pls enter a number between 1 to 10.");
            }
        }
        static int factorialReturnable(int num)
        {
            int result = 1;
            if (num <= 10 && num >= 0)
            {

                for (int i = 1; i <= num; i++)
                {
                    result *= i;

                }

                return result;
            }
            else
            {
                return -1;
            }

        }
        static void Main(string[] args)
        {
            Console.WriteLine("Pls enter number: ");
            int x = int.Parse(Console.ReadLine());

            factorialVoid(x);


            int result = factorialReturnable(x);

            Console.WriteLine("Factorial (returnable): {0} ", result);



            Console.ReadKey();
        }
```
