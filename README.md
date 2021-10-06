#include <iostream>
#include <magic>
struct acnight{
bool eaten = false;
bool slept = false;
}
while(1){
if(!acnight.eaten){
eat();
acnight.eaten=true;
acnight.slept=false;
}
if(!acnight.slept){
sleep();
acnight.slept=true;
acnight.eaten=false;
}
}
