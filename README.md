# OOP_EX4
Pokemon Game in java with Directed Weighted Graphs

In this project we have implemented pokemon game wich was applied using directed and weighted grapghs , wich was implemented in the previous project , in Java . </br>

The game contains agents and pokemons , each agent starts on a specific position on the graph , the main purpose of the agents is to catch the pokemons with less moves as possible ,wich means more efficiency .

photo provided for our pokemon game (in case 5) : </br>

![Screenshot from 2022-01-13 23-11-52](https://user-images.githubusercontent.com/94143804/149411011-1a6d202f-50c8-447c-bb81-cdaeb890104a.png)

</br>

# Graph implementation 
## we have used our previous project in java (DirectedWeightedGraph) and the algorihms that we have implemented to do this project .</br> 

## In this project we have implemented several classes : </br>
 - Agent : This class is used to represent the agents on the graph </br>
   - change_vals : this function reads from json and converts to values to the object.</br>
   - set_next : this function sets the next node destination .</br>
   - get_pos : this function returns the position of the agent .</br>
 - Arena : This class includes the graph and represents the agents and the pokemons as objects (converted from JSON) : </br>
   - pok_from_json : This functions convert pokemons from json </br>
   - agents_from_json : This function converts agents from json </br>
   - pokemon_location : This function returns if the pokemon exist on the edge </br>
 - Pokemon : This class used to represent the pokemons on the graph wich will be hunted during the game : </br>
   - hunted : This function returns if the pokemon is beeing hunted </br>
 - StuddentCode : This is 
