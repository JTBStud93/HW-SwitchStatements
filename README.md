# HW-SwitchStatements
Watch read and practice from the module: Switch Statements, While Loops  Write your understanding of the topic using comments and examples (at least 10 examples) to the instructor and describe them in your own words to the best of your knowledge. Put your work to GIT. Submit the GIT url to canvas. 

/* 1
Comment
The "structure" of the example is based on the book (page 56). The "cardNumber" subject has been replaced with "smoothieDrink" for this assignment.

Example
static void Start (int smoothieDrink)
{
    switch (smoothieDrink)
    {
        case 3:
            Console.Writeline ("Fruit");
            break;
        case 2:
            Console.Writeline ("Veggie");
            break;
        case 1:
            Console.Writeline ("Meat");
            break;
        default:    // Any other smoothieDrink
            Console.Writeline (smoothieDrink);
            break;
    }
}

*/

/* 2
Comment
The "structure" of the example is based on the Unity Tutorial. The "intelligence" subject has been replaced with "smoothieDrink" for this assignment.

Example
public class Smoothies : MonoBehaviour
{
    public int smoothieDrink = 3;


    void Start()
    {
        switch (smoothieDrink)
        {
            case 3:
                print ("A healthy smoothie that contains a lot of Vitamin C!");
                break;
            case 2:
                print ("A healthy smoothie that's really... leafy... it's still tastes good!");
                break;
            case 1:
                print ("A healthy smoothie tha-- wait, this is just chunks of meat in a glass of water! Where's the Manager?!");
                break;
            default:
                print ("No Smoothie today.");
                break;
        }
    }
}

*/

/* 3
Comment
In this example, cases 3 & 2 do NOT have any breaks. So this will show that it finds the Fruit Smoothie, then it'll find the Veggie Smoothie, then it will stop after it finds the Meat Smoothie.

Example
switch (int smoothieDrink)
{
    case 3 "smoothieDrink":
        print ("Fruit" + smoothieDrink);
    case 2 "smoothieDrink":
        print ("Veggie" + smoothieDrink);
    case 1 "smoothieDrink":
        print ("Meat" + smoothieDrink);
        break;
    default:
        print ("No Smoothie.")
        break;
}

*/

/* 4
Comment


Example
class main ()
{
    int key = Gold;

    switch (Gold = True)
    {
        case "Gold":
            print ("Gold Door is now unlocked.");
            break;
        case "Silver":
            print ("Can't use the Gold Key on the Silver Door.");
            break;
        default:
            print ("Can't use item here.");
            break;
    }
}

*/

/* 5
Comment


Example
public string jedi = "Luke"
{
    switch ("Luke")
    {
        case "Luke":
            print ("Old Ben?");
            break;
        case "ObiWan":
            print ("Now that's a name I've not heard in a long, long time.");
            break;
        case "HanSolo":
            print ("I know.");
            break;
        case "Yoda":
            print ("There is another.");
            break;
    }
}

*/

/* 6
Comment


Example


*/

/* 7
Comment


Example


*/

/* 8
Comment


Example


*/

/* 9
Comment


Example


*/

/* 10
Comment


Example


*/