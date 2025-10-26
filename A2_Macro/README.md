# A2 - Macro Processor

## Pass 1

```bash
cd "A2_Macro/Pass_1"

javac MacroPass1.java

java MacroPass1
```

## Pass 2

```bash
cd "A2_Macro/Pass_2"

javac MacroPass2.java

java MacroPass2
```

## Run Both Passes

```bash
cd "A2_Macro/Pass_1"
javac MacroPass1.java
java MacroPass1

copy intermediate.txt ..\Pass_2\
copy mnt.txt ..\Pass_2\
copy mdt.txt ..\Pass_2\
copy kpdt.txt ..\Pass_2\

cd ..\Pass_2
javac MacroPass2.java
java MacroPass2

type pass2.txt
```

