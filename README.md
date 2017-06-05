# HW-SwitchStatements
Watch read and practice from the module: Switch Statements, While Loops  Write your understanding of the topic using comments and examples (at least 10 examples) to the instructor and describe them in your own words to the best of your knowledge. Put your work to GIT. Submit the GIT url to canvas. 

/* 1
The purpose of Switch Statements is that it looks for variables, and it's a lot more faster than if-else statements. It's reccommended (by Preston Powel) that it should only be use if the script becomes complicated. The "structure" of the example is based on the book (page 56). The "cardNumber" subject has been replaced with "smoothieDrink" for this assignment.

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
In the next example below, we can see that the "int smoothieDrink" is assigned to the number 3, and it matches with case 3. Therefore case 3 is the result of this switch statement. The "structure" of the example is based on the Unity Tutorial. The "intelligence" subject has been replaced with "smoothieDrink" for this assignment. RESULT: "A healthy smoothie that contains a lot of Vitamin C!"

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
In this example, cases 3 & 2 do NOT have any breaks. So this will show that it finds the Fruit Smoothie, then it'll find the Veggie Smoothie, then it will stop after it finds the Meat Smoothie. RESULT: Fruit Smoothie, Veggie Smoothie, & Meat Smoothie.

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
Somewhat similar to the if-else statements, we see that "key" is assigned to "Gold". If the "Gold" case is selected, then this script is true. RESULT: "Gold Door is now unlocked."

class main ()
{
    int key = Gold;

    switch (Gold == True)
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
An example from Preston in today's class (6/5/2017)... from memory... RESULT: "Old Ben?"

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
Similar to #2, the int primaryWeapon is set to "1." So it won't pick case 3 or 2, but it will pick case 1. RESULT: "Staff - Basic magic based weapon... Awesome!"

public class Weapons : MonoBehaviour
{
    public int primaryWeapon = 1;


    void Start()
    {
        switch (primaryWeapon)
        {
            case 3:
                print ("Sword - Basic melee based weapon.");
                break;
            case 2:
                print ("Archer - Basic range based weapon.");
                break;
            case 1:
                print ("Staff - Basic magic based weapon... Awesome!");
                break;
            default:
                print ("Wimpy fist fights.");
                break;
        }
    }
}

*/

/* 7
Similar to #2, but the "int dialogueZelda" is assigned to "4", and "case 4" is not present. RESULT: "I AM ERROR."

public class Dialogue : MonoBehaviour
{
    public int dialogueZelda = 4;


    void Start()
    {
        switch (dialogueZelda)
        {
            case 3:
                print ("It's dangerous to go alone, take this!");
                break;
            case 2:
                print ("It's a secret to everybody.");
                break;
            case 1:
                print ("HEY! LISTEN! WATCH OUT! LOOK! HELLO?! HEY!");
                break;
            default:
                print ("I AM ERROR.");
                break;
        }
    }
}

*/

/* 8
Similar to #5. RESULT: "D'oh!"

public string Simpsons = "Homer"

{
    switch ("Homer")
    {
        case "Homer":
            print ("D'oh!");
            break;
        case "Bart":
            print ("Aye Carumba!");
            break;
        case "DrNick":
            print ("Hi Everybody!");
            break;
        case "MrBurns":
            print ("Excellent...");
            break;
    }
}

*/

/* 9
Similar to #2, but the "int youRather" is assigned to "2" RESULT: "Sit on the couch face-first."

public class WouldYouRather : MonoBehaviour
{
    public int youRather = 2;


    void Start()
    {
        switch (youRather)
        {
            case 3:
                print ("Sit on a lidless barrel with radioactive liquid.");
                break;
            case 2:
                print ("Sit on the couch face-first.");
                break;
            case 1:
                print ("Sit on a lidless barrel with radioactive liquid, face-first, who knows? Maybe you'll get superpowers and not cancer!");
                break;
            default:
                print ("Not sit anywhere for the rest of your life.");
                break;
        }
    }
}

*/

/* 10
Similar to #4. "Night In The Woods" is an indie slice-of-life game (Made with Unity! https://madewith.unity.com/en/games/night-in-the-woods). Highly reccommended! :) RESULT: "Crimes."

public class NightInTheWoods : MonoBehaviour
class main ()
{
    int nitwFriend = Gregg;

    switch (Gregg = True)
    {
        case "Gregg":
            print ("Crimes.");
            break;
        case "Bea":
            print ("Proximity.");
            break;
        case "Angus":
            print ("Constellations.")
        default:
            print ("Skip band practice.");
            break;
    }
}

*/