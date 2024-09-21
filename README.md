# MonoGame Avalonia Example

## Usage
1. Install the library using the [NuGet package](https://www.nuget.org/packages/MonoGame.Avalonia/1.0.0):
```
dotnet add package MonoGame.Avalonia --version 1.0.0
```
2. Add `Game` Property to ViewModel with new instance of game to run
3. Add `MonoGameControl` to view

```xml
<monoGame:MonoGameControl 
	Game="{Binding Game}"
	BackBufferWidth="1920"
	BackBufferHeight="1080"
	IsPaused="False"/>
```

See Examples in `MonoGame.Avalonia.Example.Desktop` and `MonoGame.Avalonia.Example.Desktop.Desktop`  projects

## License
- Original work from [Aristurtle](https://github.com/AristurtleDev)
- NeonShooter is licensed under the Microsoft Public License (Ms-PL).  You can find the license text for this in the [/source/NeonShooter/LICENSE.TXT](/source/NeonShooter/LICENSE.TXT) file.
- MonoGame.Avalonia is licensed under the MIT license.  You can find the license text in the [LICENSE](LICENSE).


