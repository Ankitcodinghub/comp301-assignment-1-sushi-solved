# comp301-assignment-1-sushi-solved
**TO GET THIS SOLUTION VISIT:** [Comp301 Assignment 1-sushi Solved](https://www.ankitcodinghub.com/product/comp301-a01-sushi-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;131786&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Comp301 Assignment 1-sushi Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
First, read the comments in the code for the following interfaces defined in package a1 to understand the abstractions for ingredients, ingredient portions, and sushi: * Ingredient * IngredientPortion * Sushi

Novice

Create eight classes which implement the Ingredient interface called Avocado, Crab, Eel, Rice, Yellowtail, Seaweed, Shrimp, and Tuna. The characteristics of these classes are given in the following table:

| Class Name | Name | Price/Oz. | Calories/Oz. | isVegetarian? | hasRice? | hasShellfish? | |————|——|———–|————–|————|——-|————| | Avocado | “avocado” | $0.24 | 42 | true | false | false | | Crab | “crab” | $0.72 | 37 | false | false | true | | Eel | “eel” | $2.15 |

82 | false | false | false | | Rice | “rice” | $0.13 | 34 | true | true | false | | Yellowtail | “yellowtail” | $0.74 | 57 | false | false | false | | Seaweed |

“seaweed” | $2.85 | 105 | true | false | false | | Shrimp | “shrimp” | $0.65 | 32 | false | false | true | | Tuna | “tuna” | $1.67 | 42 | false | false | false |

All of these classes should provide a constructor without any parameters. For example, for the Avocado class, the constructor should look like this:

public Avocado() { // Constructor code goes here }

You should employ inheritance to implement these classes. The easiest way to do this is to create a single parent class implementing the interface that encapsulates all of the information about an ingredient as private fields. You can then create individual subclasses for each specific ingredient. The constructor of each ingredient subclass should simply call the superclass constructor, passing the appropriate values from the table as arguments.

Next, create eight new classes that implement IngredientPortion, called AvocadoPortion, CrabPortion, EelPortion, RicePortion, YellowtailPortion, SeaweedPortion, ShrimpPortion, and TunaPortion. Each of these classes should provide a constructor that accepts a single parameter, indicating the amount of the portion in ounces. For example, for the AvocadoPortion class, the constructor should look like this:

public AvocadoPortion (double amount) { // Constructor code goes here }

The constructor should throw an IllegalArgumentException if the amount specified is less than 0.

Each of these classes should encapsulate an instance of Ingredient, representing the ingredient that it is a portion of. For example,

AvocadoPortion should use an instance of Avocado as its ingredient. The IngredientPortion classes should also implement the combine method to use the appropriate subclass according to which ingredient it is. For example, combining an instance of AvocadoPortion with another instance of AvocadoPortion should return a new instance of AvocadoPortion.

Again the easiest way to do this is to first create a parent class that implements an ingredient portion, and then create subclasses that simply provide the appropriate constructor and any subclass-specific method implementations that can not be provided generally (HINT: you’ll need a subclass specific version of combine).

As you implement the IngredientPortion classes, think about whether or not you can reuse the same ingredient instance for every ingredient portion of the same type. This is not necessary for full points but is just a challenge. (HINT: Think about immutability)

Adept

Create the following three classes which implement the Sushi interface.

Sashimi

A piece of sashimi is comprised of 0.75 ounces of some type of seafood. There are five types of sashimi: tuna, yellowtail, eel, crab, and shrimp. The Sashimi class should define a public enumeration called SashimiType with the following definition:

public enum SashimiType {TUNA, YELLOWTAIL, EEL, CRAB, SHRIMP};

The Sashimi class should have a constructor with the following signature:

public Sashimi(SashimiType type)

The value of type passed to the constructor indicates what type of sashimi is being made. The name associated with a Sashimi object should be the name of the underlying seafood ingredient followed by the word “sashimi”. For example, a tuna sashmi object should be produce the value “tuna sashimi” as the result of the getName method.

Nigiri

A piece of nigiri is comprised of 0.75 ounces of some type of seafood and 0.5 ounces of rice. There are five types of nigiri: tuna, yellowtail, eel, crab, and shrimp. The Nigiri class should define a public enumeration called NigiriType with the following definition:

public enum NigiriType {TUNA, YELLOWTAIL, EEL, CRAB, SHRIMP};

The Nigiri class should have a constructor with the following signature:

public Nigiri(NigiriType type)

The value of type passed to the constructor indicates what type of nigiri is being made. The name associated with a Nigiri object should be the name of the underlying seafood ingredient followed by the word “nigiri”. For example, a tuna nigiri object should be produce the value “tuna nigiri” as the result of the getName method.

Roll

public Roll(String name, IngredientPortion[] roll_ingredients)

Specifically do NOT use inheritance for these classes (i.e., Sashimi, Nigiri, and Roll). Implement each one as a separate class that implements the Sushi interface without using a common parent class.

Be careful about working with arrays as parameters to and from constructors and methods. in particular, your Roll constructor should not just blindly copy the array reference passed in to a private field encapsulated in your Roll class. Instead, you should use the clone method of the array to make a copy that you can store safely. Similarly, you should not simply return an encapsulated array reference in order to implement the getIngredients method. You should create a new array to return each time.

Jedi

Amend your Roll class to add the following functionality:

The constructor should detect if a particular ingredient type is repeated and combine the separate portions of a repeated ingredient type into a single portion.

The constructor should always include at least 0.1 ounces of SeaweedPortion as a component ingredient portion to represent the roll wrapper if the ingredient portion array passed to the constructor does not already include at least this much seaweed. If the ingredient portions passed to the constructor already have at least this much seaweed, you should not include any more.

Grading

Novice: 4 points

Adept: 4 points

Jedi: 2 points

Style guide: 2 points
