# Guards
<img src="https://raw.githubusercontent.com/thomasgalliker/Guards/master/Guards.NuGet/GuardsIcon.png" alt="Guards" align="right" height="200" width="200"> 
This Guards project is a light-weight toolbox which helps you to protect your public interfaces against invalid parameters being passed over. It is one of the fundamentals in object oriented programming that you clearly shield your internals from invalid external signals.


### Download and Install Guards 
This library is available on NuGet: https://www.nuget.org/packages/Guards/ 
Use the following command to install Guards using NuGet package manager console: 

    PM> Install-Package Guards 

You can use this library in any .Net project which is compatible to PCL (e.g. Xamarin Android, iOS, Windows Phone, Windows Store, Universal Apps, etc.) 

### API Usage 
Following guards are currently available:
<table>
   <tr>
    <td><b>Category</b></td>
    <td><b>Guards</b></td>
    <td><b>Type of exception
   </tr>
  <tr>
    <td>Boolean</td>
    <td>
        Guard.ArgumentIsTrue<br>
        Guard.ArgumentIsFalse
    </td>
    <td>ArgumentException</td>
    </tr>
    <tr>
    <td>Enumerable</td>
    <td>
        Guard.ArgumentNotNullOrEmpty
    </td>
    <td>ArgumentException</td>
   </tr>
    <tr>
    <td>Null</td>
    <td>
        Guard.ArgumentNull<br>
        Guard.ArgumentNotNull
    </td>
    <td>
        ArgumentException<br>
        ArgumentNullException
    </td>
   </tr>
     <tr>
    <td>Numeric</td>
    <td>
        Guard.ArgumentIsBetween<br>
        Guard.ArgumentIsGreaterOrEqual<br>
        Guard.ArgumentIsGreaterThan<br>
        Guard.ArgumentIsLowerOrEqual<br>
        Guard.ArgumentIsLowerThan<br>
        Guard.ArgumentIsNotNegative<br>
    </td>
    <td>ArgumentOutOfRangeException</td>
   </tr>
    <tr>
    <td>Reflective</td>
    <td>
        Guard.ArgumentMustBeInterface<br>
        Guard.ArgumentMustNotBeInterface
    </td>
    <td>ArgumentException</td>
      </tr>
    <tr>
    <td>String</td>
    <td>
        Guard.ArgumentHasLength<br>
        Guard.ArgumentHasMaxLength<br>
        Guard.ArgumentHasMinLength<br>
        Guard.ArgumentNotNullOrEmpty
    </td>
    <td>
        ArgumentException<br>
        ArgumentException<br>
        ArgumentException<br>
        ArgumentNullException or ArgumentException<br>
    </td>
   </tr>
</table>

### Contribution 
New guards are added when desired. Since this is an open source project, everyone is highly welcome to contribute and add new guards. However, the proposals should follow the existing pattern. A minimum of governance is required. Thank you for understanding.

### License 
Guards is Copyright &copy; 2015 [Thomas Galliker](https://ch.linkedin.com/in/thomasgalliker). Free for non-commercial use. For commercial use please contact the author. 
