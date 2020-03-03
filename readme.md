# Pet Store CLI
This is a simple example application which demonstrates the following:
* Ability to pull all a list of available Pets from the https://petstore.swagger.io api.
* Prints pets sorted by Category and then by name in reverse order.
* With example unit tests.

##prerequisites
* dotnet core 3.0(https://dotnet.microsoft.com/download/dotnet-core/3.0) or installed with Visual Studio 2019

## How to build
### Visual Studio 2019
* Open the project in Visual Studio
* Change the project configuration to Release
* Press f6 to build solution.

### Commandline or Continous Intergration server
Change directory into the directory containing the project then run the following commands:

```bash
dotnet restore
dotnet build --configuration release
```

Application binary files will be located in %SolutionFolder%\PetStoreCLI\bin\Release.

 ## License
Copyright (c) 2020 Wil Taylor

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.