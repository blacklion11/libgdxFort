all: core

core: $(wildcard src/com/blacklion11/fort/*.java)  $(wildcard src/com/blacklion11/fort/states/*.java) $(wildcard src/com/blacklion11/fort/world/*.java) $(wildcard src/com/blacklion11/fort/world/gen/*.java) $(wildcard src/com/blacklion11/fort/input/*.java) $(wildcard src/com/blacklion11/fort/entity/*.java)
	javac -d bin -cp "libs/*"  $(wildcard src/com/blacklion11/fort/*.java) $(wildcard src/com/blacklion11/fort/states/*.java)  $(wildcard src/com/blacklion11/fort/world/*.java) $(wildcard src/com/blacklion11/fort/world/gen/*.java)  $(wildcard src/com/blacklion11/fort/input/*.java) $(wildcard src/com/blacklion11/fort/entity/*.java)

