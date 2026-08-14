 
#include <iostream>

using namespace std;

class CPolygon{
protected:
    int width;
    int height;

public:
    CPolygon(): width(0),height(0){}

    void setValues(int a, int b){
    width=a;
    height=b;
    }
    virtual int area() const = 0;
    virtual ~CPolygon() = default;

};

class CRectangle:public CPolygon{
public:

int area() const override {
return width * height;
}
};
# Personal Portfolio

A personal portfolio website built with HTML and CSS to showcase my background, education, and contact information.

## Features
- Responsive design
- Navigation bar
- About Me section
- Alumni/projects section with external links
- Contact section with email, LinkedIn, and GitHub links

## Technologies Used
- HTML5
- CSS3

## Live Demo
[Coming soon]
