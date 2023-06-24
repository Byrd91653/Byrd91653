- 👋 Hi, I’m @Byrd91653
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
unsigned char RD(int i,int j){
double a=0,b=0,c,d,n=0;
while((c=a*a)+(d=b*b)<4&&n++<880)
{b=2*a*b+j*8e-9-.645411;a=c-d+i*8e-9+.356888;}
return 255*pow((n-80)/800,3.);
}

unsigned char GR(int i,int j){
double a=0,b=0,c,d,n=0;
while((c=a*a)+(d=b*b)<4&&n++<880)
{b=2*a*b+j*8e-9-.645411;a=c-d+i*8e-9+.356888;}
return 255*pow((n-80)/800,.7);
}

unsigned char BL(int i,int j){
double a=0,b=0,c,d,n=0;
while((c=a*a)+(d=b*b)<4&&n++<880)
{b=2*a*b+j*8e-9-.645411;a=c-d+i*8e-9+.356888;}
return 255*pow((n-80)/800,.5);
}
<!---
Byrd91653/Byrd91653 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
