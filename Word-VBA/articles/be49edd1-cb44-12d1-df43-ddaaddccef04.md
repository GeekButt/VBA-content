
# Options.AutoFormatAsYouTypeAutoLetterWizard Property (Word)

 **True** for Microsoft Word to automatically start the Letter Wizard when the user enters a letter salutation or closing. Read/write.


## Syntax

 _expression_. **AutoFormatAsYouTypeAutoLetterWizard**

 _expression_Required. A variable that represents an  ** [Options](873b7b99-3fe1-fd89-9ece-a9355cb827dc.md)** collection.


## Example

This example sets Microsoft Word to automatically start the Letter Wizard when the user enters a letter salutation or closing.


```
Sub AutoLeterWizard() 
 Options.AutoFormatAsYouTypeAutoLetterWizard = True 
End Sub
```


## See also


#### Concepts


 [Options Object](873b7b99-3fe1-fd89-9ece-a9355cb827dc.md)
#### Other resources


 [Options Object Members](76cd9dfe-6bbb-4c3d-0bfc-79a62bedd15e.md)
