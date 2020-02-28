---
layout: default
---

I am a research scientist at Google working with [Cordelia Schmid](https://thoth.inrialpes.fr/~schmid/){:target="_blank"} on research problems involving both vision and language. I completed Ph.D. in 2020 under the supervision of [Bohyung Han](https://cv.snu.ac.kr/index.php/~bhhan/){:target="_blank"} and [Minsu Cho](http://cvlab.postech.ac.kr/~mcho/){:target="_blank"} at [POSTECH](http://www.postech.ac.kr/eng/){:target="_blank"}. Before that I was advised by [Gary Geunbae Lee](http://nlp.postech.ac.kr/~gblee/){:target="_blank"} at the same school for M.S. During my Ph.D., I interned at Disney Research, Google and Facebook working with [Leonid Sigal](https://www.cs.ubc.ca/~lsigal/){:target="_blank"}, [Jack Sim](https://scholar.google.com/citations?hl=ko&user=UhnT9e4AAAAJ&view_op=list_works&sortby=pubdate){:target="_blank"}, [Radu Soricut](https://scholar.google.com/citations?hl=en&user=NAzD9mgAAAAJ&view_op=list_works&sortby=pubdate){:target="_blank"} and [Peter Vajda](https://sites.google.com/site/vajdap){:target="_blank"}. My research interests primarily lies in the areas of computer vision and natural language processing, especially in the intersections of these areas.

* * *
# Education
* **Ph.D.**  [Computer Science and Engineering](https://ecse.postech.ac.kr/){:target="_blank"}, [POSTECH](http://www.postech.ac.kr/eng/){:target="_blank"} (Sep. 2016 - Feb. 2020)
  * <i>Combinatorial Classification: Learning by Combination of Classifiers on Heterogeneous Output Spaces</i> <br />
  Advisors: Bohyung Han and Minsu Cho; Committee: Suha Kwak, Seungyong Lee and Jinwoo Shin
* **M.S.**  [Computer Science and Engineering](https://ecse.postech.ac.kr/){:target="_blank"}, [POSTECH](http://www.postech.ac.kr/eng/){:target="_blank"} (Mar. 2011 - Feb. 2013)
  * <i>Multiple User Intent Understanding for Spoken Dialog System</i> <br />
  Advisor: Gary Geunbae Lee; Committee: Jonghyeok Lee and Hwanjo Yu
* **B.S.**  [Computer Engineering](http://portal.changwon.ac.kr/home/ce){:target="_blank"}, [Changwon National University](http://eng.changwon.ac.kr/eng/main/index.php){:target="_blank"} (Mar. 2006 - Feb. 2011)

* * *
# Work Experiences
* **Research Scientist**, Google, France (Mar. 2020 - )
* **Research Intern**, Facebook, USA (Sep. 2019 - Jan. 2020)
* **Research Intern**, Google, USA (May. 2019 - Aug. 2019)
* **Tech Intern**, Google, USA (Jun. 2017 - Dec. 2017)
* **Lab Associate**, Disney Research Pittsburgh, USA (Feb. 2017 - May. 2017)
* **Lecturer**, Dept. of Information Technology, [Mongolia International University](http://www.miu.edu.mn/){:target="_blank"} (Aug. 2013 - Jan. 2015)

* * *
# Honors and Awards
* **Best Ph.D. Award (Engineering)**, POSTECH (2020)
* **CVPR 2019 Doctoral Consortium** (2019)
* **Naver Ph.D. Fellowship** (2017)
* **Best Team Project Award**, SUNY Korea Hot Topics in Computer Science Workshop (2015)
* **Academic Scholarship**, Kyobo Foundation for Education and Culture (2006 - 2011)
* **Academic Scholarship**, Bakyeop Foundation (2007 - 2008)
* **Grand Prize**, CNU Venture Item Contest (2007)
*	**First Runner Up**, CNU Programming Contest (2006)

* * *
# Academic Services
* **Regular Program Committee Member (Reviewer)** in CVPR, NeurIPS, ICLR, ICML, ICCV and ACL.
* **Technical Committee Member**, Conceptual Captions Challenge, CVPR 2019

* * *
# Publications
<ul>
{% for pub in site.publications %}
  <li>
    <a href="{{pub.url}}" target="_blank">{{pub.title}}</a> <br />
    {% if pub.authors contains "*Paul Hongsuck Seo" %}
    {{pub.authors | replace: "*Paul Hongsuck Seo", "<strong>*Paul Hongsuck Seo</strong>"}} <br />
    {% elsif pub.authors contains "Paul Hongsuck Seo" %}
    {{pub.authors | replace: "Paul Hongsuck Seo", "<strong>Paul Hongsuck Seo</strong>"}} <br />
    {% elsif pub.authors contains "Hongsuck Seo" %}
    {{pub.authors | replace: "Hongsuck Seo", "<strong>Hongsuck Seo</strong>"}} <br />
    {% endif %}
    In <i>{{pub.conf}}</i>
  </li>
{% endfor %}
</ul>

