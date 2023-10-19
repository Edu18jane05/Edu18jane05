#include <stdio.h>
#include <cs50.h> //inckude libraries

int main(void)
{
    string name = get_string("What's your name?\n"); //get user input
    printf("hello, %s\n", name); //print hello, user input
}
