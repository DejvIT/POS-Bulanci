all: pos

clean:
	rm -f pos

pos: main.cpp Game.h Game.cpp Server.h Server.cpp Map.h Map.cpp Player.h Player.cpp Client.h Client.cpp 
	g++ -lpthread -o -g pos main.cpp Game.cpp Server.cpp Map.cpp Player.cpp Client.cpp 
