### UE4 Smarter Macro Indenting
This extension was designed to fix the unnecessary and annoying "smart" indenting that Visual Studio likes to do around various UE4 macros.  It attempts to fix these indents when your current line proceeds any of the following UE4 macros:
* UPROPERTY
* UFUNCTION
* GENERATED_BODY
* GENERATED_UCLASS_BODY
* GENERATED_USTRUCT_BODY
* GENERATED_UINTERFACE_BODY
* GENERATED_IINTERFACE_BODY

### Installation

1. Download and install the Visual Commander extension for Visual Studio from here: https://vlasovstudio.com/visual-commander/
2. Go to VCmd -> Import and import ue4_smarter_macro_indenting.vcmd
3. Go to VCmd -> Extensions to open the Extensions panel
4. Check the "Enabled" checkbox for the "UE4 Fix Indent" extension.
5. Make sure Indenting is set to "Smart" in Tools -> Options -> Text Editor -> C/C++ -> Tabs.

> If "VCmd" doesn't appear on your Visual Studio toolbar after installing Visual Commander, you may need to restart Visual Studio.

