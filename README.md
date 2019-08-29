Lights Out Game

Here’s a simple GUI application designed and developed on Dolphin’s MVP framework. It is a simple game called “Lights Out”. I have used Model-View-Presenter as GUI framework.



I have created LightsOutCell presenter and LightsOutCellView. Along with that, I have created the MVP triad for the LightsOutCell component, which is used to display each cell on the game board. Then I have created the LightsOutBoard model and the LightsOutGame presenter. Which serves as the model for the game board and the top-level presenter for the game itself. 

Because the game can have a variable size playing field I have created presenter components dynamically. 

I have also used Dolphin’s debugger to code the missing parts of the methods. I have loaded an icon image for the game class from a PNG file and then installed it into the Dolphin samples folder.

