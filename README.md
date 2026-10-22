<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:2563EB,100:38BDF8&height=200&section=header&text=MD.%20Rajin%20Al%20Ismam%20Albee&fontSize=38&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Generative%20AI%20%7C%20Data%20Analytics%20%7C%20CSE%20Student&descAlignY=52&descSize=16" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=38BDF8&center=true&vCenter=true&width=820&lines=Generative+AI+%26+Data+Analytics+%F0%9F%9A%80;Computer+Science+%26+Engineering+Student;Passionate+Problem+Solver;Building+real-world+solutions...;Always+learning.+Always+growing."/>

<br/>

<p>
  <a href="https://www.linkedin.com/in/md-rajin-al-ismam-albee"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://github.com/albeemohammad"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
  <a href="mailto:albeemohammad@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="tel:+8801761470226"><img src="https://img.shields.io/badge/Phone-008000?style=for-the-badge&logo=whatsapp&logoColor=white"/></a>
</p>
</div>

---

## 📌 Summary

MD. Rajin Al Ismam Albee is a passionate Computer Science and Engineering student at BGC Trust University Bangladesh. With a deep interest in technology and continuous self-improvement, key focus lies in **Generative AI**, **Data Analytics**, and **problem-solving**. Enjoys creating real-world solutions and exploring new tools, always prepared to turn every challenge into an opportunity.

---

## 🧑‍💻 $ whoami

```csharp
namespace BGCTUB.Student;

public sealed record Developer
{
    public string   Name     { get; init; }
    public string   Degree   { get; init; }
    public string   Location { get; init; }
    public string[] Focus    { get; init; }
    public string[] Stack    { get; init; }
    public string[] Tools    { get; init; }
    public string   Mission  { get; init; }
}

class Program
{
    static void Main()
    {
        var dev = new Developer
        {
            Name     = "MD. Rajin Al Ismam Albee",
            Degree   = "B.Sc in CSE @ BGC Trust University Bangladesh",
            Location = "Chawkbazar, Chattogram, Bangladesh",
            Focus    = ["Generative AI", "Data Analytics", "Problem Solving"],
            Stack    = ["C/C++", "Python", "PHP", "MySQL", "HTML", "CSS"],
            Tools    = ["Git", "GitHub", "VS Code", "Antigravity", "Arduino IDE", "XAMPP", "Canva"],
            Mission  = "Turning every challenge into an opportunity through tech and innovation."
        };
    }
}
