
### Summary
Project Support Map method or properties with document [revitapidoc](https://www.revitapidocs.com/) online , we can use data guid to check with name method, properties to check.

let see this problem [Revitlookupwpf](https://github.com/weianweigan/RevitLookupWpf/issues/20#issuecomment-1040504071) or [revitapidoc](https://github.com/gtalarico/revitapidocs/issues/97) to see detail.

### How to use : 
Install some package: 
- pip install pandas
- pip install beautifulsoup4

### Step by step:
- Extract file htm from file chm RevitAPI
- Install all package request
- Run file JsonRevitAPI.ipynb
- See file json output

#### Demo Data

![](pic/data.png)

#### Demo Json

``` json
 {
        "Title":"DoorCost",
        "Keywords":"ParameterTypeId.DoorCost property",
        "APIName":"P:Autodesk.Revit.DB.ParameterTypeId.DoorCost.DoorCost",
        "Description":"\"Cost\"",
        "Namespace":"Autodesk.Revit.DB",
        "Guid":"efdf5191-47a5-2d99-db4f-b425edebbee6",
        "Type":"property"
    }

```
Result link to go to : [https://www.revitapidocs.com/2022/efdf5191-47a5-2d99-db4f-b425edebbee6.htm](https://www.revitapidocs.com/2022/efdf5191-47a5-2d99-db4f-b425edebbee6.htm)

![](pic/json.png)

### Warning 

Project can't get everything, some function or properties can't search or include in file `json` or export to `csv`.If you want improve for this, please create a pull request !