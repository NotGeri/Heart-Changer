# Heart-Changer

Updated to 1.16.5. You may find a direct download in the releases tab.

### Default configuration file: 

```yaml
# > ---
# > HeartChanger Configuration
# > Visit Spigot page for more informations 
# > https://goo.gl/iT3ubv
# > List of Hearts Type
#     0 = Auto (Permissions)
#     1 = Normal
#     2 = Hardcore
#     3 = Dark (Not supported yet)
#     4 = Golden (Not supported yet)
#     5 = Poisoned (Not supported yet)
# > ---
# > The default heart type after joining the server.
Type: 2
# > Is the death screen supposed to be displayed?  
# > I recommend to leave it on "false" because after the death
# > screen is from hardcore mode.
DeathScreen: false
# > Will the message be displayed after the death of the player? 
# > It works only if the death screen is set to "false".  
DisplayMessage: true
# > Is the message supposed to be generated automatically?
AutoMessage: true
# > If AutoMessage is set to "false", the messages will be replaced by the ones below.
Messages:
    # > Header Title.
    YouDied: You Died
    # > Sub Title.
    # > Placeholder %score% which corresponds to the score obtained by the player
    Score: Score %score%
```