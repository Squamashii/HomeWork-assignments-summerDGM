# HomeWork-assignments-summerDGM
Home work assignments 

//-------------------------------------------------------------------------------------------------------------------------------------
// 31 May 2017 --- If and Else Clauses
/* an if statement is a way to check data in your code, and give you an action depending on whether the data was true or false.
All if statements in C# must be inside of a function. In the class we are using void Start (), which I'm pretty sure means that the function is set to run when the program starts up. An ELSE clause is what happens when the if statement returns false. You can also have an ELSE IF clause which checks some extra things before determining that the statement is false. They are pretty straight forward.. at least for now. I put these all in the Bird script in my summer project:
*/

//Variables for the else clauses

public string charName = "Freddy";
public float charWeight = 150.5f;
public int charHeightcm = 95;
public bool charFit = true;
public bool charHappy = false;

void Start() //This is the Start function, and includes everything in the following curly bracket code box.
{
  if(charHeightcm <= 120)    //The computer will check if whatever is inside these parenthesis are true, and if it is, it will continue with the function in the curly brackets below it. 
  {
  print("You are a midget");
  }
  else
  {
  print (this.name + " is " + charHeightcm + " tall.");
  }
  
  if (charName == "Freddy")
  {
  print("Hi Freddy"); //if the character's name is Freddy, this will tell him Hi
  }
  else  //This is an else clause. If the if statment returned false, then this part of the function plays out.
  {
  print("Who the heck are you?"); //if his name isn't Freddy, the computer will ask his name
  }
  
  if(charWeight <= 140)
  {
  print("Somebody get that kid a sandwich");
  }
  else if(charWeight <= 180)   
  {
  charFit = true; //neat.. it worked. I can change other variables this way.. 
  }
  else
  {
  print("Do you even lift?");
  }

  if(2 + 2 == 5)
  {
  print("really?");
  }
  else
  {
  print("you were so close!");
  Debug.LogError("You are an idiot, everyone knows what 2 + 2 is... wait.. what what is again?");
  }
  
  if(charFit)
  {
  charHappy = true;
  }
  else
  {
  charHappy = false;
  }
}
//--------------------------------------------------------------------------------------------------------------------------------------

