all: clean
	javac P3.java

clean:
	rm -rf *~ *.class base/*.class base/*~ visitor/*.class visitor/*~ syntaxtree/*.class syntaxtree/*~ *.out tests/*~ tests/*.out tests/*.class

test: all
	./test.sh
