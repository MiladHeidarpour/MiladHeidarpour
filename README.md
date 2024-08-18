## Code Biography 
```csharp
using Humanity;
using Planets.Earth;
using Country.Iran;

public class Milad : IDeveloper, IHuman
{
    public string Name
    {
        get => nameof(Milad);
    }

    public string LastName
    {
        get => "Heidarpour";
    }

    public string BirthDate = 1382/06/08 ;


    public List<string> ProgrammingLanguages = new(){ "C#" };

}
```
