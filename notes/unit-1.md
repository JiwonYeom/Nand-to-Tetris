## Boolean Gates
- Physical implementation of Boolean function

#### Boolean Algebra
- Deals with Boolean(binary) values
- Binary input -> binary output
- *Truth table* representation

#### Boolean Expression
- And 
- Or 
- Not 

#### Canonical Representation
- Every Boolean function can be expressed by 
    1. Canonical Expression
    2. Can be expressed using And, Or, Not

#### Gate logic
- gate->physical device of Boolean function
- primitive gate

#### Primitive & Composite Gates
- gate logic ~ logic design ~ composite gates
- Any logic gate can be viewed from **external** or **internal** perspective

* * *
##### Basic Logic Gates
> custom code (my pseudocode for each chip)
1. Nand
```
if(a = 1 && b == 1){
    out = 0;
}else{
    out = 1;
}
```

2. Not
```
if(in == 0){
    out = 1;
}else{
    out = 0;
}
```

3. And
```
if(a == 1 && b == 1){
    out = 1;
}else{
    out = 0;
}
```

4. Or
```
if(a == 0 && b == 0){
    out = 0;
}else{
    out = 1;
}
```

5. Xor
```
if(a != b ){
    out = 1;
}else{
    out = 0;
}
```

6. Mux(Multiplexor)
- three-input gate that uses one of the inputs.
- this input is called *selection bit*
- output one of the other two inputs = *data bits*
```
if(sel == 0){
    out = a;
}else{
    out = b;
}
```

7. DMux(Demultiplexor)
- opposite function of multiplexor
- takes single input & channels it to one of the two possible outputs, according to a selector bit that specifies which output to choose
```
if(sel == 0){
    a = in;
    b = 0;
}else{
    a = 0;
    b = in;
}
```
