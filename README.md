# MyShelfie

Application developed as part of the Software Engineering course @ Politecnico di Milano.

## Goal
Implementing an online version of the board game "My Shelfie".

## Description
 Server once launched is able to simultaneously manage multiple games of 2-4 players (clients) each. 
 
 Each player can join a game through:
- Command line interface (CLI)
- Graphical user interface (GUI)
  
Clients can also decide whether to communicate with the server using socket or RMI as communication techonology during the game. Players in the same game are also allowed to chat with each other.
The application is based on the Model View Controller (MVC) design pattern. The communication protocol being used and the UML diagrams can be found in the deliverables/ folder.

## How to run the application
### Run the server
```bat
java -jar AM11.jar --server
```
### Run a client (command line interface)
```bat
java -jar AM11.jar --client --tui
```
### Run a client (graphical user interface)
```bat
java -jar AM11.jar --client --gui
```

### Run the server
```bat
java -jar AM11.jar --server
```

### Run a TUI client
```bat
java -jar AM11.jar --client --tui
```

### Run a GUI client
```bat
java -jar AM11.jar --client --gui
```

### Students
- [Simone Bevilacqua](https://github.com/simobevilacqua25)
- [Raffaele Chiaverini](https://github.com/ChiaveriniRaffaele)
- [Luca Barda](https://github.com/LucaBardaPoli)
- [Michael Alibeaj](https://github.com/MikeTech01)
