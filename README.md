```cs
using System;
using System.Threading;
using System.Collections.Generic;
class Marcel {
  public string MyUsername;
  public List<string> MyAliases;
  public List<string> MyProgrammingLanguages;
  public Dictionary<string,string> MyContacts;
  public Dictionary<string,string> MyOngoingProjects;
  Marcel() {
    this.MyUsername = "Marcel";
    this.MyAiases = new List<string>("Alex","xBryon","xByron","Reuel");
    this.MyProgrammingLanguages = new List<string>(){"Rust","Java","C#"};
    this.MyContacts = new Dictionary<string,string>(){{"discord","Marcel#6395"}};
    this.MyOngoingProjects = new Dictionary<string,List<string>>(){{"Rust","Learning it"}}; //Thats pretty much it.
  }
}
```
