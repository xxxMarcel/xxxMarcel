```cs
using Github;
using System;
using System.Threading;
using System.Collections.Generic;
class AcidCodeZ : Github.AcidCodeZ.Profile {
  public AcidCodeZ() {
    this.MyUsername = "Acid";
    this.MyAiases = new List<string>("Alex","Acid","xBryon","xByron");
    this.MyProgrammingLanguages = new List<string>(){"Python","C#"};
    this.MyContacts = new Dictionary<string,string>(){{"discord","Reuel#5201"},{"gmail","soon!"}};
    this.MyProjects = new Dictionary<string,List<string>>(){{"C#","Progressing With My C-Sharp Skills, Working On Calling APIs Using System.Net.Http."},{"Python","Nothing ATM, Just Working With C# For Now."}};
    Thread.Sleep(5000);
    Console.WriteLine("That's Pretty Much It.");
    Thread.Sleep(2500);
    Environment.Exit(0);
  }
}
```
