# wow validation
```csharp
  /// Functions:
  /// 
  /// Task 5:
  /// Learn how to write documentation for a function.
  /// 
  /// function name: stringRepeater(String str, int repeat);
  /// 
  /// Implement both void and returnable functions.
  static void wow_void(int num)
  {

      string x = 'w' + new string('o', num) + 'w';
      Console.WriteLine(x);

  }
  static string wow_returnable(int num)
  {


      return 'w' + new string('o', num) + 'w';

  }
  static void Main(string[] args)
  {
      int y;
      Console.WriteLine("pls enter number");
      y = int.Parse(Console.ReadLine());

      wow_void(y);

      string result = wow_returnable(y);
      Console.WriteLine("wow_returnable: {0}", result);

      Console.ReadKey();


  }
  ```