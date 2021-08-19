# so, usually IO would compile using this
# g++ -Wall main.cpp message.cpp -o newMEsage
# but since I'm kinda lazy and I will probably end up adding more files and libraries to new proyects, better add a makefile
output: main.o message.o
	g++ main.o message.o -o output

main.o: main.cpp
	g++ -c main.cpp

message.o: message.cpp message.h
	g++ -c message.cpp

clean:
	rm *.o output

# //https://www.youtube.com/watch?v=GExnnTaBELk