
# Javadoc Tutorial
Javadoc comments can only be used in Java source code.
Javadoc comments are similar to regular comments except they begin with the /**
symbol, and end with the */ symbol. They also use the following tags. 

## Uses for Javadoc:
Javadoc comments allow programmers to easily generate an API (application programmer interface). By writing java code with these comments you can then run the javadoc (ex: javadoc HelloWorld.java) command to generate documentation in HTML format for any public classes and public and protected methods and variables. Any standard HTML code can also be used inside a javadoc comment.

## Javadoc Tags which COMTOR Utilizes:
@param Indicates the name of a formal parameter followed by a short description. If there are multiple parameters, @param tags should be defined in the exact same order as the parameters are declared in the method declaration.
@return Indicates the return type of a method. Do not use for void methods. @throws Indicates the exceptions the method throws.

## Other Important Javadoc Tags:
@author @deprecated @see @version @since
You can also this:
Indicates the name of the author of the source code. Indicates that the item is a member of the depreciated API. Used to refer to related classes.
Indicates the version of your source code.
Also can be used to indicate the version of the source code.
use the <code> tag for all Java keywords, names and code samples, like <code>aMethod( ) </code>


Sample Code with Javadoc Tags:
/**
 * Sample.java – a class that demonstrates the use of javadoc
 * comments.
 * @author Ruth Dannenfelser
 * @version 2.0
 * @see Sample2
 */
 public class Sample extends Sample2 {
  public String words;
  /**
   * Retrieve the value of words.
   * @return String data type.
   */
   public String getWords()
   {
      return words;
   }
  /**
   * Set the value of words.
   * @param someWords A variable of type String.
   */
   public void setWords(String someWords)
   {
      words = newWords;
   }
}
For More Info on Javadoc visit:
Sun’s Website - http://java.sun.com/j2se/javadoc/writingdoccomments/
Source Forge Java Workshop -
http://javaworkshop.sourceforge.net/chapter4.html#Javadoc+Comments

