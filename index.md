
Front page for project work demo!

Literal code can be presented thustly with triple back ticks as delimiters or 4 spaces indentation:

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


Links can be html or `.md` markdown

<a href="http://sentientmachine.github.io/sentientmachine/whatever.png">http://sentientmachine.github.io/sentientmachine/whatever.png</a>

prsent child photograph of project, or screenshot or whatever here:

Look what I did!

![Alt text](./cpp_image.png?raw=true "user mouse-hover text ")


Code is here: <a href="https://github.com/sentientmachine/sentientmachine/blob/master/index.md">https://github.com/sentientmachine/sentientmachine/blob/master/index.md</a>
