# Notes on "[_The Origin of the MIT License_](https://ieeexplore.ieee.org/abstract/document/9263265)"

[English](README.en.md) \
[Traditional Chinese](README.zh-hant.md)

## Introduction
[The MIT License](https://en.wikipedia.org/wiki/MIT_License) and [permissive licenses](https://en.wikipedia.org/wiki/Permissive_software_license) have substantially influenced the whole open source community since 1980s. Although many people treat the concept of permissive licenses as trivial, I feel the need to clarify the details of the permissive licenses for the non-English speakers.

In 2020, Professor Emeritus Jerome H. Saltzer published _[The Origin of the MIT License](https://ieeexplore.ieee.org/abstract/document/9263265)_. I believe it serves as a good starting point for introducing this topic to those who are not familiar with permissive licenses. After contacting Professor Emeritus Saltzer and IEEE, I was informed that IEEE had their own concerns and did not permit a direct translation of the article into Traditional Chinese. This repository has therefore been transitioned into Notes on "_The Origin of the MIT License_".

The goal of this repository is to clarify the permissive licenses in multiple languages as accurately as possible. Given that my own description may fall short of this goal, I warmly welcome discussions to improve the quality through GitHub Issues and Pull Requests. The copyright holder is listed as [The Contributors of Notes on "_The Origin of the MIT License_"](https://github.com/chhsiao1981/notes-on-the-origin-of-the-mit-license/graphs/contributors), under [CC BY-SA 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/deed.en) <img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" style="width:20px;height:20px;margin-left:10px;"><img src="https://mirrors.creativecommons.org/presskit/icons/by.svg" style="width:20px;height:20px;margin-left:10px;"><img src="https://mirrors.creativecommons.org/presskit/icons/sa.svg" alt="" style="width:20px;height:20px;margin-left:10px;">.

### Why Don't I Post Only on [Wikipedia](https://zh.wikipedia.org/wiki/MIT%E8%A8%B1%E5%8F%AF%E8%AD%89#%E8%B5%B7%E6%BA%90)?
Wikipedia [3] is an excellent platform for collecting knowledge from a wide range of fields. However, it is common that the descriptions of the same topic differ significantly across different languages. To ensure the multilingual descriptions convey as consistent a meaning as possible, I believe maintaining this repository is the most straightforward solution.

### Why Is This Repository Licensed Under CC BY-SA 4.0 International?
I contributed the Traditional Chinese version of the "Origins" section to [Wikipedia](https://zh.wikipedia.org/wiki/MIT%E8%A8%B1%E5%8F%AF%E8%AD%89#%E8%B5%B7%E6%BA%90) and then copied to this repository. Based on [the license of Wikipedia](https://foundation.wikimedia.org/wiki/Policy:Terms_of_Use#7._Licensing_of_Content), the license in this repository is also licensed under [CC BY-SA 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/deed.en) <img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" style="width:20px;height:20px;margin-left:10px;"><img src="https://mirrors.creativecommons.org/presskit/icons/by.svg" style="width:20px;height:20px;margin-left:10px;"><img src="https://mirrors.creativecommons.org/presskit/icons/sa.svg" alt="" style="width:20px;height:20px;margin-left:10px;">.

## Reference
1. J. H. Saltzer, “The Origin of the MIT License,” IEEE Annals of the History Computing, vol. 42, no. 4, pp. 94–98, Nov. 2020, doi: [10.1109/MAHC.2020.3020234](https://doi.org/10.1109/MAHC.2020.3020234).

2. “MIT License,” Wikipedia, \[Online\]. Available: https://en.wikipedia.org/wiki/MIT_License. \[Accessed: Jul. 17, 2025\].

3. Wikipedia. \[Online\]. Available: https://www.wikipedia.org. \[Accessed: Jul. 17, 2025\].

4. J. H. Saltzer, D. D. Clark, J. L. Romkey, and
W. L. Gramlich, “The Desktop Computer as a
Network Participant,” IEEE J. Sel. Areas Commun.,
vol. SAC-3, no. 3, pp. 468–478, May 1985, doi: [10.1109/JSAC.1985.1146219](https://doi.org/10.1109/JSAC.1985.1146219)

5. L. Zhang “How to Build a Gateway—C-Gateway: An
Example,” in Proc. 2nd Int. Conf. Comput. Appl., IEEE
Computer Society Press, Beijing, China, Jun. 1987.

6. R. W. Scheifler and J. Gettys, “The X Window System,” ACM Trans. Graph., vol. 5, no. 2, pp. 79–109, Apr. 1986, doi: [10.1145/22949.24053](https://doi.org/10.1145/22949.24053).

## How to Contribute
Similar to software development, the quality of this repository can always be significantly improved through the community. Issues and Pull Requests for any parts of this repo, including and not limited to this README and the following Notes, are always welcome.

## Notes

### Design Philosophy
In 1983, the originators of the MIT License recognized that charging license fees would result in time-consuming negotiations. Therefore, they developed a simple license for several pieces of network software—developed by the Computer Systems Research (CSR) group at the MIT Laboratory for Computer Science (MIT-LCS)—which had gained attention from both academia and industry [4,5,and others which could only be referenced by the developer names in the original article]. Their approach was based on the following four principles (quoted from the original article):

> 1. Permission is granted for any purpose, including commercial use.
> 2. Neither signed agreement nor license fee is required.
> 3. Permission is subject to three restrictions:
>    * Any redistribution must credit MIT.
>    * Any redistribution must include the same copyright and permission notice.
>    * Promotional use of MIT’s name is restricted.
> 4. The software is provided “as-is” without warranty.

### About the 3 Restrictions in the 3rd Principle
The four principles in the paper were within the context in the 1983 event mentioned in the paper. Based on my knowledge to many repositories adopting the MIT License, I would like to make the following notes:

1. "Any redistribution must credit MIT" is within the context of the software
    developed by CSR at MIT-LCS in 1983, as mentioned in the previous paragraphs
    in the paper. Software that uses the MIT License but is not copyrighted
    by MIT must not credit MIT.
2. "Any redistribution must include the same copyright and permission notice" can be extended to any parts of
   the "Software" that may be considered as violating copyright, as outlined in the
   actual content of [the MIT License](https://opensource.org/license/mit). For derived
   works, a common practice is to "include" the copyright and the license
   by placing the same copyright and permission notice somewhere noticeable
   in the derived work, as a citation/acknowledgment of the original work.
3. Furthermore, unless agreed upon by the copyright holder of the original work,
   it is not appropriate to include "the same copyright (of the copyright holder of the original work) and permission notice"
   directly inside the license of the derived work without clearly stating that
   it is for acknowledgement and not part of the license, especially if the license
   of the derived work is also using the MIT License. This could cause the confusion,
   leading to the misconception that the copyright holder of the original work
   is also involved in the derived work. An example of the confusing usage
   is provided in [confusing-statement](misc/confusing-statement).
