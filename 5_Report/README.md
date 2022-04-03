#c Sololearn
[C course certificate.pdf](https://github.com/Hariharan4501/M1_March_2022/files/8253658/C.course.certificate.pdf)
# NDG Linux Unhatched Certificate
[HariharanK-NDG Linux Unhatc-certificate.pdf](https://github.com/Hariharan4501/M1_March_2022/files/8253670/HariharanK-NDG.Linux.Unhatc-certificate.pdf)
#Github Certificate
[GIT Certificate.pdf](https://github.com/Hariharan4501/M1_March_2022/files/8253673/GIT.Certificate.pdf)
#First day on github
![Screenshot (101)](https://user-images.githubusercontent.com/101234573/158387639-ad404fc9-794a-48ce-b23c-cb2473fc8e31.png)
# Calculation of Tariff
# Introduction
The amount of money framed by the supplier for the supply of electrical energy to various types of consumers is known as "electrical tariff".The tariff covers the total cost of producing and supplying electrical energy and in addition to reasonable cost.
The actual tariff that the consumer pay depends on the consumption of the eletricity. The industrial consumers pay more tariff because they use more power for long times than the domestic consumers. The electricity tariff depends on the following factors : 1) Type of load, Time at which load is required, The amount of energy used.
The total bill of consumer has these parts namely fixed charge, rate of charge, costumer charge, Electrical duty and no of units consumed.
# Adavantages and Disadvantages of Tariff calculation
# Advantages 
* Less initial cost and we do not need to install metering equipment 
* Poor people will be benefited in flat tariff
* Easy to understand 
* Proper return
* Reasonable profit
# Disadvantages 
* Every consumer have to pay fixed charges irrespective of load variation.
SWOT Analysis :

# WHO : 
Consumers of different types will consume the electricity.

# When : 
It can be used everytime and world is nothing without electrical power.

# Where :
It is used all over the world.

# How : 
From conventional energy sources the energy is converted into useful form of electrical energy and it is generated, transmitted and distributed to consumers. And hence along with the units multiplied with rate of charge,the maintenance nothing but fixed and consumer charges are also added.  

# Low level requirements:

[No of units consumed by the consumer]

High level requirement--- 
Units will be recorded from the
 difference of prev reading and current reading.
|LLR01 |    |select Group |
             |HLR01|     Implemented----
| LLR02 |
The group will be selected like A or B or C 
             | HLR01 |  | Implemented |
| LLR03 | If it not belongs to first group it will be directly switch into other group
             | HLR01|    | Implemented |
| LLR04 | After the selected The rate of charge belongs to that particular group will be multiplied with no. of units to get energy charges.
              | HLR02 |    | Implemented |
| LLR05 | The bill amount will be calculated by adding energy charges to fixed charges, customer charges and electrical duty charges.
| LLR06 |   And hence the total amount will be noted
          |HLR01 HLR02 |  | Implemented |

## Defining Our System

<br>
<br>

![DOS](Defining_our_system.jpg)

---

<br>
## Here are the below steps to run the code 

 * For Running and Building the code
   * Type make run in terminal
 * For Running the Building tests
   * Type make run_test in terminal
 * For static analysis
   * Type make static_analysis in terminal
 * For dynamic analysis
   * Type make dynamic_analysis in terminal
 * For code coverage
   * Type make coverage in terminal
 * For cleaning
   * Type make clean in terminal


## USAGE OF PREPROCESSOR/POINTERS/FUNCTION POINTERS/STRUCT/TYPE DEF

## Preprocessor:
The C preprocessor is a macro processor that is used automatically by the C compiler to transform your program before actual compilation. It is called a macro processor because it allows you to define macros, which are brief abbreviations for longer constructs.

## The C preprocessor provides four separate facilities that you can use as you see fit:

Inclusion of header files. These are files of declarations that can be substituted into your program.
Macro expansion. You can define macros, which are abbreviations for arbitrary fragments of C code, and then the C preprocessor will replace the macros with their definitions throughout the program.
Conditional compilation. Using special preprocessing directives, you can include or exclude parts of the program according to various conditions.
Line control. If you use a program to combine or rearrange source files into an intermediate file which is then compiled, you can use line control to inform the compiler of where each source line originally came from.

## Pointers:
Pointers:
The Pointer in C, is a variable that stores address of another variable. A pointer can also be used to refer to another pointer function. A pointer can be incremented/decremented, i.e., to point to the next/ previous memory location. The purpose of pointer is to save memory space and achieve faster execution time.
Like variables, pointers in C programming have to be declared before they can be used in your program. Pointers can be named anything you want as long as they obey C’s naming rules. A pointer declaration has the following form.

 syntax:
data_type * pointer_variable_name;

Types of Pointers in C:
1.Null Pointer
2.Void Pointer
3.Wild pointer
4.Dangling pointer

## Funtion Pointer:
In the C function pointer is used to resolve the run time-binding. A function pointer is a pointer that stores the address of the function and invokes the function whenever required.
In C, we can use function pointers to avoid code redundancy.
1) Unlike normal pointers, a function pointer points to code, not data. Typically a function pointer stores the start of executable code.
2) Unlike normal pointers, we do not allocate de-allocate memory using function pointers.

## Struct:
A structure is a key word that create user defined data type in C. A structure creates a data type that can be used to group items of possibly different types into a single type.

‘struct’ keyword is used to create a structure. 

A structure variable can either be declared with structure declaration or as a separate declaration like basic types.Structure members cannot be initialized with declaration. 

Structure members can be initialized using curly braces ‘{}’. For example, following is a valid initialization. 
Structure members are accessed using dot (.) operator.

## Type def:
typedef, which you can use to give a type a new name. Following is an example to define a term BYTE for one-byte numbers.After this type definition, the identifier BYTE can be used as an abbreviation for the type unsigned char

By convention, uppercase letters are used for these definitions to remind the user that the type name is really a symbolic abbreviation, but you can use lowercase.

You can use typedef to give a name to your user defined data types as well. For example, you can use typedef with structure to define a new data type and then use that data type to define structure variables directly

Syntax: typedef data_type new_name
