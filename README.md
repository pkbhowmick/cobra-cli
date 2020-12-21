# cobra-cli 
cobra cli provides a go program build using [cobra library](https://github.com/spf13/cobra) to add integers or floating numbers from cli

## Available commands
___
- cobra-cli add args
   - ```$ cobra-cli add 1 2 3 4```
    command adds the integers and prints the sum in cli
- cobra-cli add args --flag
   - ```$ cobra-cli add 2.4 5.6 9.3 --float``` or ```$ cobra-cli add 2.4 5.6 9.3 --f``` command adds the floating numbers and prints the sum in cli
    
- cobra-cli add even args
  - ```$ cobra-cli add even 1 2 3 4``` adds only even integers and prints sum in the cli
    
- cobra-cli add odd args
  - ```$ cobra-cli add odd 1 2 3 4``` adds only odd integers and prints sum in the cli