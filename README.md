# Anti-Cheat
A customizable anti-cheat according to the game's needs. 

To script work, active: Home > Game Settings > Security > Enable HTTP Requests → ON
It will work as a LocalScript if
The script is in one of these places:

Inside StarterPlayerScripts

Or StarterCharacterScripts

Or manually inserted into PlayerGui (as part of a UI anti-cheat system)

Or in ReplicatedFirst with loading logic

HttpService:PostAsync will only work in published games (local/test mode games do not make external requests, for security reasons).

In local Roblox Studio, the Webhook will not be called, but you will see suspicious warn() in the console.

In the real game (online/published), the Webhook will fire normally.
