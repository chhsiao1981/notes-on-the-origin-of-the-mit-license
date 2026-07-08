# [The Origin of the MIT License](https://ieeexplore.ieee.org/abstract/document/9263265)

Department: Anecdotes \
Editor: [David Walden](https://www.walden-family.com/dave/), dave@walden-family.com

[Jerome H. Saltzer](https://www.mit.edu/~Saltzer/) \
Massachusetts Institute of Technology

[Digital Object Identifier: 10.1109/MAHC.2020.3020234](https://doi.org/10.1109/MAHC.2020.3020234) \
目前版本的日期: 2020-11-15

Publisher: IEEE \
Journal: IEEE Annals of the History Computing ( Volume: 42, Issue: 4, pp. 94-98 )

## 摘要
討論了「MIT 授權條款 (MIT License)」的起源與歷史。這種授權條款已成為「發佈受到版權保護的電腦程式以提供他人使用，並且不需(書面合同)簽署或支付授權費用」的一種流行方式。括號內的文字 (MIT 授權條款) 指的是一組具有共同來源 (ancestry) 和指導原則，但措辭不同的軟體授權條款。最近有些關於「MIT 授權條款」起源的討論，但由於缺乏或很難找到權威性的歷史文獻，該討論並未得出結論。這篇文章提供了部分歷史背景和相關文獻。由於這篇文章是在相關事件發生 35 年後所寫，主要依賴於我經常模糊的回憶，但也提供了一些在我的檔案們裡和網路上的檔案庫中找到的相關支持文獻。

## 本文
**「MIT 授權條款 (MIT License)」** 已成為「發佈受版權保護的電腦程式提供他人使用，並且不需(書面合同)簽署或支付授權費用」的一種流行方式。括號內的文字 (MIT 授權條款) 指的是一組具有共同來源 (ancestry) 和指導原則，但措辭不同的軟體授權條款。最近有些關於「MIT 授權條款」起源的討論[1]，但由於缺乏或很難找到權威性的歷史文獻，該討論並未得出結論。這篇文章提供了部分歷史背景和相關文獻。由於這篇文章是在相關事件發生 35 年後所寫的，主要依賴於我經常模糊的回憶，但也提供了一些在我的檔案們裡和網路上檔案庫中找到的相關支持文獻。

在1983年的秋天，麻省理工學院電腦科學實驗室（MIT Laboratory for Computer Science, MIT-LCS）的電腦系統研究小組（Computer Systems Research, CSR）開發了幾個引起外界興趣，並且請求希望可以得到相關資訊和程式碼的網路軟體。其中之一是 David Clark[3] 為 Xerox Alto 實作的 TsCP/IP 架構 (TCP/IP stack)，目的是展示實作 TCP/IP 可以小型、快速，並且能夠在工作站或個人電腦上使用。之後，Larry Allen[4] 將 BCPL 程式碼翻譯為 C 語言，用於迪吉多（Digital Equipment）的 PDP-11 系統，並且在 Wayne Gramlich[5] 的帶領下，John Romkey[7]、David Bridgham[8]、Karl Wright[9]、Don Gillies[10] 和 Louis Konopelski[11] 共同為 IBM 個人電腦 (IBM PC) 開發了一個帶有網路應用的 TCP/IP 實作（PC/IP）[6]。此外，Noel Chiappa[12] 為迪吉多 LSI-11 開發了一個多協議網路路由系統 (multiprotocol network routing system)，稱為 C-Gateway，其中由 Liza Martin[13] 實作了 External Gateway Protocol（EGP）[14]。

由於請求來自大學研究人員和商業機構，該小組內部進行了關於「應該附帶哪些條件來發佈這些成果」的討論。那時候的不久之前，美國國會 (Congress) 和美國版權局 (U.S. Copyright Office) 已經釐清了「將版權聲明附加於軟體及其文件」的選項。然而，這個選項引出了另一個問題：如果是受版權保護的，MIT 是否應該要求書面合同並收取授權費？該小組的主要目標是影響網路技術的發展方式，並且看起來授權收入不會太多。麻省理工學院電腦科學實驗室（MIT-LCS）其他軟體小組的經驗也表明，將會花費大量時間與律師準備並協商授權協議。基於這些考慮，我們得出結論，最好是將軟體免費提供，並附上版權聲明，指出其來源，且不需要任何(書面合同)簽名。

Larry Allen 和我開始與波士頓律師事務所的律師 Bob Sullivan[15] 和 Sib Reppert[16] 進行討論，當時該律師事務所正在處理麻省理工學院電腦科學實驗室（MIT-LCS）的著作權相關事務。在 1984 年 1 月，Larry 和我根據「將軟體進行版權註冊的構思，但是在版權聲明中包括了一個許可聲明，允許任何人可以免費使用該軟體」，來草擬了提議的措辭。該措辭借鑒了研究小組之前在限制發佈聲明 (restricted distribution notices) 中使用的理念和語句，並且也借用了電腦協會（Association for Computing Machinery）在當時的最近開始附加於其出版物中的文章的版權和許可聲明。圖1[17] 是一份給律師的備忘錄，呈現了草擬的措辭，圖2[18] 是該備忘錄附件的摘錄，是來自於當時的最近一期《Communications of the ACM》的頁面裡，呈現他們的版權和許可聲明措辭。律師很快給出了積極的回應，並且在 1984 年 1 月 25 日，我們向約 25 位收到 1983 年 6 月 1 日「請勿再散佈」的版本 ("please do not distribute any further" version) 的 PC/IP 收受者 (recipient)，發送了一封描述授權許可政策變更的公告。

這份版權和許可聲明有四個基本原則：

1. 允許出於任何目的使用，包括商業用途。
2. 不需要簽署協議或支付授權費。
3. 允許的使用有三個限制：
    * 任何的再散佈必須註明 MIT。
    * 任何的再散佈必須包含相同的版權和許可聲明。
    * 限制使用 MIT 的名稱進行促銷 (Promotional use)。
4. 軟體以「現狀」提供，並不提供任何保證 (warranty)。

接下來幾天的討論對措辭進行了完善，刪除了「銷售」一詞，因為它與「任何目的」一詞重複，並且稍微放寬了對 MIT 名稱促銷使用 (promotional use) 的限制。經過完善的措辭的授權，首次用於 1984 年 2 月 1 日的 PC/IP 發佈。圖3[19] 是用於 C 語言程式的 include.h 檔案，這些程式構成了在 C-Gateway 裡 PC/IP 和 EGP 實作。這個版本的授權聲明可能是第一個適合被認定為「MIT 授權條款」的版本。研究小組之前的軟體發佈曾使用過帶有一個或多個元素的版權聲明，這些元素基於相同的基本原則，但這似乎是第一次將所有四個原則結合在單一授權條款中。

在1985年秋季，出現了如何替「由 Jim Gettys[21] 和 Bob Scheifler[22] 為 MIT Project Athena[23] 開發的 X Window 系統[20] 」授權的問題。在與兩年前類似的討論中，他們注意到 X Window 系統早期版本的專有授權對他們自己以及潛在收受者 (prospective recipient) 來說，成為了一種麻煩，並且有可能影響廣泛採用。早期採用者 (adopter) 做出了重要貢獻，但這也使得「最小化授權衝突 (minimize the licensing friction)」變得更加重要。他們還指出，昇陽 (Sun Microsystems) 和卡內基梅隆大學（Carnegie Mellon University）也在跟 X Window 競爭類似的視窗系統，並且兩者都要求簽署授權。結論是，如果「採用 X Window 系統的過程」能更簡單，X Window 可能會更具影響力。

一群新的律師審查了 PC/IP 版權和許可聲明的措辭，並加入了幾個律師喜愛的措辭，同時保持了四個基本原則。為了向 X Window 系統的收受者保證關於潛在問題的解釋，他們還添加了一句話，說明該軟體不包含任何「授權成為在 Unix 系統的一部份的內容」。圖4[24] 中的重新措辭的授權條款第一次應用於 1986 年 2 月的 X Window 系統版本 10 釋出 3 (X Window System Version 10 Release 3)。這個措辭可以被視為第二版的「MIT 授權條款」。

自那時以來，包括所有由Project Athena 開發的軟體，麻省理工學院及其他地方的組織已經根據此授權條款進行了多次版本的措辭上的小幅變更。術語「MIT 授權條款」既具體指的是 X10R3 授權，也泛指任何具有此共同來源 (ancestry) 並基於相同四個原則的「寬容式自由軟體授權條款」(permissive free software license) 。

結果證明，這一授權策略達到了預期的效果：影響力的目標實現了。PC/IP 成為了 IBM 個人電腦 (IBM PC) 上十幾個「商業網路架構 (commercial networking stack)」的基礎。 X Window 系統成為了 Unix 和 Linux 的標準視窗系統，並且今天在數百萬台系統上運行。Project Athena 的 Kerberos 身份驗證系統[26] 被包括在許多電腦系統的發行版中，特別包括了 Microsoft Windows、Apple macOS、大多數版本的 Unix 和Linux，以及 IBM z/OS。

更進一步的，這些軟體的免費發佈所帶來的良好聲譽，促使資金和軟體應用的回流，這些回流支持了麻省理工學院的研究和教育。現金流量已經超過了可能來自收費授權的收入，甚至這筆金額也被可用的應用程式的價值所超越。這裡學到重要的一課是，我們要可以看到超越「收取授權費的好處 (可能會帶來一些收入)」，而是更要看到如果免費提供軟體所帶來的機會。潛在的回報可以大得非常多 (orders of magnitude larger)。

## 感謝

Larry Allen, Noel Chiappa, David Clark, Jim Gettys, 和 John Romkey 提供了有幫助的留言 (comments)，補充了我遺忘、錯誤或從未知道的歷史細節。任何剩餘的錯誤均由我負責。

## Reference

1. G. Haff, “The mysterious history of the MIT License,” Apr. 26, 2019, Opensource.com, [Online]. Available: https://opensource.com/article/19/4/history-mit-license. Accessed: May 4, 2020. A comment by Wayne Gramlich in a followup discussion on Slashdot provides a little more background: [Online]. Available: https://news.slashdot.org/story/19/04/28/0326207/the-mysterious-history-of-the-mit-license. Accessed: May 4, 2020
2. MIT–LCS is one of the antecedents of the MIT Computer Science and Artificial Intelligence
Laboratory (CSAIL) when CSAIL was formed in 2003.
3. Dr. David D. Clark, MIT–LCS Senior Research Scientist in 1983.
4. Larry W. Allen, MIT–LCS staff member in 1983.
5. Wayne C. Gramlich, MIT EECS graduate student in 1983.
6.  J. H. Saltzer, D. D. Clark, J. L. Romkey, and W. L. Gramlich, “The desktop computer as a
network participant,” IEEE J. Sel. Areas Commun., vol. SAC-3, no. 3, pp. 468–478, May 1985.
7. John L. Romkey, MIT EECS undergraduate student in 1983.
8. David A. Bridgham, MIT EECS undergraduate student in 1983.
9. Karl D. Wright, MIT EECS undergraduate student in 1982.
10. Donald W. Gillies, MIT EECS undergraduate student in 1983.
11. Louis J. Konopelski, MIT EECS undergraduate student in 1982.
12. J. Noel Chiappa, MIT–LCS staff member in 1982.
13. Elizabeth A. Martin, MIT–LCS staff member in 1983.
14. L. Zhang “How to build a gateway—C-gateway: An example,” in Proc. 2nd Int. Conf. Comput. Appl., IEEE Computer Society Press, Beijing, China, Jun. 1987.
15. Robert E. Sullivan, Herrick & Smith attorney in 1983.
16. Sibley P. Reppert, Herrick & Smith attorney in 1983.
17. Scan of paper file. Source: Prof. Saltzer’s files, crate #20, folder “PC/IP Licensing.”
18. Cropped scan of page 1051 from Commun. ACM, vol. 26, 12, Dec. 1983. Source: Prof. Saltzer’s files, crate #20, folder “PC/IP Licensing.”
19. Scan of printout from a dot matrix printer. Source: Prof. Saltzer’s files, crate #20, folder “PC/IP Licensing.” A digital version is also in file /usr/Martin/sysnet/export/utils/notice.h, file size 669 bytes, last modified date 27 January 1984. Source: J. N. Chiappa, 21 May 1985 backup tape of the MIT–LCS–CSR PDP-11/45, Accessed: 4 May 2020.
20. R. W. Scheifler and J. Gettys, “The X Window System,” ACM Trans. Graph., vol. 5, no. 2, pp. 79–109, Apr. 1986.
21. James Gettys, Digital Equipment Corporation staff member in 1983.
22. Robert W. Scheifler, MIT–LCS staff member in 1983.
23. G. A. Champine, MIT Project Athena: A Model for Distributed Campus Computing, Digital Press,
Hudson, MA, USA, 1991.
24. Contemporary printout of file include/X/mit-copyright.h, file size 814 bytes, last modified date, Feb. 2, 1986. [Online]. Available: https://www.x.org/archive/x10R3/X.V10R3.tar.gz, December 7, 1995, Accessed: May 4, 2020.
25. “MIT_License,” Wikipedia, the Wikimedia Foundation, [Online]. Available: https://en.wikipedia.org/wiki/MIT_License. Accessed: May 2020.
26. B. C. Neuman and T. Ts’o, "Kerberos: An authentication service for computer networks," IEEE
Commun. Mag., vol. 32, no. 9, pp. 33–38, Sep. 1994.

## 作者
Jerome H. Saltzer 是「 MIT EECS 的電腦科學類榮譽退休教授」(professor emeritus of computer science with the Department of Electrical Engineering and Computer Science, Massachusetts
Institute of Technology). 在本文所描述的事件發生時，他是 MIT-LCS 裡的 CSR 的負責人 (the head of the Computer Systems Research Group of the MIT Laboratory for Computer Science) 和 MIT Project Athena 的技術總監 (technical director of MIT Project Athena). 可以透過 Saltzer@mit.edu 與他聯絡.

## 翻譯者

[The Contributors of The Origin of the MIT License (zh-hant)](https://github.com/chhsiao1981/the-origin-of-the-mit-license-zh-hant/graphs/contributors) 和 [ChatGPT 4o-mini](https://chatgpt.com/).
