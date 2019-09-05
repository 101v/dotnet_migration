## Migrating .net 4.5 project to .net 4.6

1. Right click on project and select **properties** from the context menu.
2. On the property page select **Application** tab 
3. On the application tab change target framework from **.NET Framework 4.5** to **.NET Framework 4.6**
4. On changing framework, it will open a dialog box, click Ok.
5. Build Solution. It may result into follow warning/error.
   ![Warnings](Warnings.png)
6. To resolver above mentioned warnings/errors, fire following command in the **Visual Studio Package Manager Console**
```
   Update-Package -Reinstall
```
7.
