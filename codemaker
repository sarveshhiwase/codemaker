#!/bin/bash
# A simple function to make a directory with input.txt and filename.cpp
# Adds my boiler plate by default

cplusplus='#include<bits/stdc++.h>
#define ll long long int
#define mod 1000000007
#define add insert
#define pb push_back 
#define rep(start,n) for(int i = start; i < n; i++)
#define dis(x) cout << x << " "; 
#define disnew(x) cout << x << "\\n"; 
#define negmod(a) (a%mod + mod) % mod 
using namespace std;

void solve();

int main()
{
ios_base::sync_with_stdio(false);
cin.tie(NULL);

#ifndef ONLINE_JUDGE
freopen("input.txt", "r", stdin);
freopen("error.txt", "w", stderr);
freopen("output.txt", "w", stdout);
#endif

int t=1;
/*cin>>t;*/

while(t--)
{
    solve();
}

cerr<<"time taken : "<<(float)clock()/CLOCKS_PER_SEC<<" secs"<<endl;

return 0;
}

void solve()
{

}'

javascript="var name = 'Buddy';

console.log('Hello There, + name');"

java='import java.util.*;
import java.lang.*;
import java.io.*;

class Main
{
    public static void main (String[] args) throws java.lang.Exception
    {

    }
}'

python='print("Hello World!")'

returnsnippet(){
    extension=$1
    if [ $extension == "js" ]
    then
        echo "$javascript"
    elif [ $extension == "py" ]
    then 
        echo "$python"
    elif [ $extension == "cpp" ]
    then 
        echo "$cplusplus"
    elif [ $extension == "java" ]
    then 
        echo "$java"
    fi
}

# Taking Command line arguments as an array named arr
arr=("$@")
# Temp variable i for identfying the first folder name
i=0
# iterate over all array 
for y in "${arr[@]}"
do
    if [ "$i" != 0 ]
    then
        # Entire file name
        val="$y"
        # Extension name
        ext="${val##*.}"
        touch "$val"
        echo "$(returnsnippet $ext)" > "$val"
    else
        # Make a directory 
        mkdir "$y"
        echo "Created "$y" directory..."
        cd "$y/"
        touch "input.txt"
    i+=1
    fi
done