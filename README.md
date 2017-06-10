# Desharp - .NET Debugging Tool - C#/VB Code Snippets
Visual Studio code snippets - automaticly generated code snippets from 3-4 letter shortcuts to work better with Desharp library.

## Shortcuts
#### Dumping:
```cs
/// ddd
Desharp.Debug.Dump(params object[] args);
Desharp.Debug.Dump(Exception exception = null, DumpOptions? options = null);

/// ddf
Desharp.Debug.Fire.Log(object obj, FireLog.);

/// dddd
Desharp.Debug.DumpAndDie(object obj = null, DumpOptions? options = null);

/// dddo
Desharp.Debug.Dump(object obj, DumpOptions? options = null);
```

#### Logging:
  - **dde** - `Desharp.Debug.Log(Exception exception = null);`
  - **ddl** - `Desharp.Debug.Log(object obj = null, Level level = Level.INFO, int maxDepth = 0, int maxLength = 0);`

#### Other:
  - **dds** - `Desharp.Debug.Stop();
  - **ddc** - `Desharp.Debug.Configure(DebugConfig cfg);`
  - **dda** - `Desharp.Debug.Assert(bool assertion, string description = "", Level logLevel = Level.DEBUG);`
  - **ddt** - `Desharp.Debug.Timer(string name = null, bool returnTimerSeconds = false, Level logLevel = Level.DEBUG);`


## Instalation - C#
- download and unzip package
- copy all files from repo directory `C#` with extension `.snippet` into directory:
  - for VS 2017: `C:\Program Files (x86)\Microsoft Visual Studio 15.0\VC#\Snippets\1033\Visual C#\`
  - for VS 2015: `C:\Program Files (x86)\Microsoft Visual Studio 14.0\VC#\Snippets\1033\Visual C#\`
  - for VS 2013: `C:\Program Files (x86)\Microsoft Visual Studio 12.0\VC#\Snippets\1033\Visual C#\`
  - for VS 2012: `C:\Program Files (x86)\Microsoft Visual Studio 11.0\VC#\Snippets\1033\Visual C#\`
  - ...
- you can use it imediatelly, no needs to restart Visual Studio (tested in 2015)

## Instalation - Visual Basic
- download and unzip package
- copy all content from repo directory `Visual Basic` into directory:
  - for VS 2017: `C:\Program Files (x86)\Microsoft Visual Studio 15.0\VB\Snippets\1033\other\`
  - for VS 2015: `C:\Program Files (x86)\Microsoft Visual Studio 14.0\VB\Snippets\1033\other\`
  - for VS 2013: `C:\Program Files (x86)\Microsoft Visual Studio 12.0\VB\Snippets\1033\other\`
  - for VS 2012: `C:\Program Files (x86)\Microsoft Visual Studio 11.0\VB\Snippets\1033\other\`
  - ...
- you can use it imediatelly, no needs to restart Visual Studio (tested in 2015)
