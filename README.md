Firstly I tried to apply strategy pattern and interfaces to oblige use my strategies, than I understood that a) these interfaces are useless, b) the problem looks like multiply inheritance and strategy-approach is overcomplicated, especially as compared to MI.
But I'm coding with C# and C# doesn't allow MI. So, I decided to create my own MI! Ha!

Now my solution cosits of interface containing some properties without setter and extension method to this interface which realizes changing one property using another or method's arguments. Properties have only getter because I want to leave a case when the value of the property cann't be changed outside the class realizing the interface. But I stiil need to change it in the extension method, so I added changing method to my data class and DAMN, IT'S SENSELESS. WELL, I'LL TRY AGAIN.