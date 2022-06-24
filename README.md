```cs
using Github;
using System;
using System.Threading;
using System.Collections.Generic;
class Marcel : Github.xxxMarcel.Profile {
  public string MyUsername;
  public List<string> MyAliases;
  public List<string> MyProgrammingLanguages;
  public Dictionary<string,string> MyContacts;
  public Dictionary<string,string> MyProjects;
  public ReuelPlayZ() {
    this.MyUsername = "Marcel";
    this.MyAiases = new List<string>("Alex","xBryon","xByron","Reuel");
    this.MyProgrammingLanguages = new List<string>(){"Rust","C#"};
    this.MyContacts = new Dictionary<string,string>(){{"discord","Marcel#6395"}};
    this.MyProjects = new Dictionary<string,List<string>>(){{"Rust","Learning it"}};
    Thread.Sleep(5000);
    Console.WriteLine("That's Pretty Much It.");
    Thread.Sleep(2500);
    Environment.Exit(0);
  }
}
```
