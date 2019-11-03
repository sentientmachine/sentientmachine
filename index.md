
Front page for project work demo!

Literal code can be presented thustly with triple back ticks as delimiters or 4 spaces indentation:
```
    #include<iostream>
    #include<algorithm>
    using namespace std;
    class Foo{
        public:
            int num;
            int other;
    };
    int main(){
        Foo bar[10] = {{1,5},{9,2},{3,0},{5,7},{1,3},{6,4},{10,8},{0,9},{6,2},{3,5}};
        std::sort(bar, bar + 10, [](const Foo &x, const Foo &y) {
            return x.num < y.num;
        });
        cout << "done";
    }
```

href Links can be raw html or github's `.md` markdown:

<a href="https://github.com/sentientmachine/sentientmachine/blob/master/cpp_image.png">https://github.com/sentientmachine/sentientmachine/blob/master/cpp_image.png</a>

Present child's photograph of project, or screenshot or anything here.  

Look what I did!  I did a thing and you can see it!

![Alt text](./cpp_image.png?raw=true "user mouse-hover text ")


Code is here: <a href="https://github.com/sentientmachine/sentientmachine/blob/master/index.md">https://github.com/sentientmachine/sentientmachine/blob/master/index.md</a>


If the child writes illegal code, the error message is shown here:

https://github.com/sentientmachine/sentientmachine/settings

for example: 

     Your site is having problems building: The variable {{1,5} on line 15 in index.md 
     was not properly closed with }}. For more information, see 
     https://help.github.com/en/github/working-with-github-pages/troubleshooting-jekyll-build-errors-for-github-pages-sites#tag-not-properly-terminated.

Getting the child to make an edit, see an error, fix the error, commit, see the change, repeat, counts as programming.
