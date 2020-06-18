JAR=btreelib.jar

#this is the name of the given project folder
ASSIGNMENT=btree_project_sum_20

#change the ASSIGN path to the path where you have downloaded on your computer
<<<<<<< HEAD
ASSIGN=/home/lubuntu-josh/Desktop/cse4331/project_1/dbms
=======
ASSIGN=~/Desktop/dbms
>>>>>>> 0a4dd988e94420d3a29b6e3727fb00fd41efd382

#change the JDKPATH if you are not using omega.uta.edu
JDKPATH = /usr
LIBPATH = $(ASSIGN)/$(ASSIGNMENT)/lib/$(JAR)
CLASSPATH = $(LIBPATH):$(ASSIGN)/$(ASSIGNMENT)/src
BINPATH = $(JDKPATH)/bin
JAVAC = $(JDKPATH)/bin/javac -classpath $(CLASSPATH)
JAVA  = $(JDKPATH)/bin/java  -classpath $(CLASSPATH)

PROGS = together

all: $(PROGS)

together:*.java
	$(JAVAC) *.java

clean:
	\rm -f *.class *~ \#* core
