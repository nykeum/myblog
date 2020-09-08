**fastpage를 이용한 블로그 개설 방법**

안녕하세요 **Tequila\_Angela** 입니다.

저 이번에 아주 칭찬 받을 만한 짓을 하려고 합니다.

이번에 처음 들어가게 된 fast.ai 스터디에서 유용한 정보를 알게 되었고

그걸 여러분과 공유하려고 합니다.

그것은 바로바로

두둥!! (한껏 비장)

**매우 쉬운 방법으로 블로그를 개설할 수 있다는 것인데요**.

꺄아 &gt;\_&lt; 정말 너무너무 쉬워요.

평소에 github.io로 블로그를 꾸미려고 시도하시다가 포기한 적이 정말 많았는데

(저만 그런건… 아니죠?? 다들 힘들게 살고 계신거 안다구요!!)  
하지만 이제 그런 슬픈 과거는 잊어도 될 것 같습니다.

왜냐구요??

**바로 fastai에서 제공하는 fastpages 덕분이죠!!**

**이 툴의 장점은 “관리가 정말 정말 쉽다” 입니다.**

[**https://fastpages.fast.ai/**](https://fastpages.fast.ai/)

<img src="2020-09-09-My-first-blog-with-fastpages//media/image1.png" style="width:6.26806in;height:2.49861in" alt="스크린샷이(가) 표시된 사진 자동 생성된 설명" />

이는 홈페이지에 가시면 바로 대문에 걸려있는 그림입니다.

그림에서 보이는 .md 확장자 바로 markdown 언어죠.

github에서 제공하는 Github.io 블로그 기능은 너무나 생소한 markdown언어를 사용해서 많은 사용자들이 불편함을 겪었다고 해도 과언이 아닙니다.

fastpages의 놀라운 점은 기존의 markdown 받고 쥬피터에서 제공하는 .ipynb  
그리고 정말 어마무시하게도 word .docx까지!!  
Blog를 관리 하는 방법으로 쓸 수 있는다는 겁니다!

저 혼자만 알기엔 너무 아까워서

주변에 친구들 후배들 선배들에게 이러한 툴을 알려주기위해 배운 방법들을 기재해 보았습니다.

차근차근 따라하시면 어느새 개인 블로그 페이지가 뚝딱 완성 된답니다.

시작하겠습니다.

1.  **먼저 이 하단에 기재된 링크를 따라가주세요.  
    <https://github.com/fastai/fastpages>**

2.  **초록색 버튼인 Use this template을 눌러주세요**

<img src="2020-09-09-My-first-blog-with-fastpages//media/image2.png" style="width:6.26806in;height:1.45764in" alt="스크린샷이(가) 표시된 사진 자동 생성된 설명" />

1.  **Repository name을 설정하고  
    초록색 버튼인 Create repository from template을 눌러주세요.**

<img src="2020-09-09-My-first-blog-with-fastpages//media/image3.png" style="width:5.3622in;height:3.94472in" alt="스크린샷이(가) 표시된 사진 자동 생성된 설명" />

1.  **nykeum/myblog가 개설 된 것을 확인하셨다면  
    Actions탭을 클릭해 주세요.**

<img src="2020-09-09-My-first-blog-with-fastpages//media/image4.png" style="width:6.26806in;height:0.95208in" alt="스크린샷이(가) 표시된 사진 자동 생성된 설명" />

1.  **Actions 탭으로 가보시면 3개의 initial commit이 자동으로 진행 된걸 보실 수 있습니다.**

<img src="2020-09-09-My-first-blog-with-fastpages//media/image5.png" style="width:6.26806in;height:2.30833in" alt="스크린샷이(가) 표시된 사진 자동 생성된 설명" />

1.  **이제 Pull requests 탭으로 가시면  
    Initial Setup이 생성된 것을 볼 수 있습니다.  
    생성된 Initial Setup을 클릭해주세요**

<img src="2020-09-09-My-first-blog-with-fastpages//media/image6.png" style="width:6.26806in;height:2.01181in" alt="스크린샷이(가) 표시된 사진 자동 생성된 설명" />

1.  **Merge 작업을 하기 전에 1 2 3을 수행해 봅시다.**

<img src="2020-09-09-My-first-blog-with-fastpages//media/image7.png" style="width:5.66142in;height:3.74522in" alt="스크린샷이(가) 표시된 사진 자동 생성된 설명" />

**7-1 this utility를 클릭하면 SSH Keys를 만들어주는 페이지가 뜹니다.  
RSA -&gt; 4096 -&gt; Generate-SSH-Key를 클릭해주면  
private key와 public key가 생성됩니다.**

<img src="2020-09-09-My-first-blog-with-fastpages//media/image8.png" style="width:6.26806in;height:1.98425in" alt="스크린샷이(가) 표시된 사진 자동 생성된 설명" />

**7-2 7번의 Initial Setup 페이지로 돌아가 2번의 this link를 클릭합니다. Secrete page에서 우측의 New secret을 누릅니다.  
7-1에서 생성한 private key를 value에 복붙 (ctrl + c & ctrl +v)**

**Name에는 SSH\_DEPLOY\_KEY를 적어주고 Add Secret 버튼을 눌러줍니다.**

<img src="2020-09-09-My-first-blog-with-fastpages//media/image7.png" style="width:5.66142in;height:3.74522in" alt="스크린샷이(가) 표시된 사진 자동 생성된 설명" />

<img src="2020-09-09-My-first-blog-with-fastpages//media/image9.png" style="width:6.26806in;height:1.97569in" alt="스크린샷이(가) 표시된 사진 자동 생성된 설명" />

<img src="2020-09-09-My-first-blog-with-fastpages//media/image10.png" style="width:6.26806in;height:2.29861in" alt="스크린샷이(가) 표시된 사진 자동 생성된 설명" />

**7-3 다시 7번의 initial setup page로 돌아갑니다.**

**3번의 this link를 클릭하여 setting의 Deploy keys페이지로 이동 -&gt; Add Deploy 클릭7-1에서 생성한 public key를 value 복붙(ctrl + c & ctrl + v) 해줍니다.  
Name은 fastpages-key로 입력하고 Allow write access 꼭!! 클릭  
Add Key를 눌러주시면  
merge 준비 끝**

<img src="2020-09-09-My-first-blog-with-fastpages//media/image11.png" style="width:4.86614in;height:3.21912in" alt="스크린샷이(가) 표시된 사진 자동 생성된 설명" />

<img src="2020-09-09-My-first-blog-with-fastpages//media/image12.png" style="width:5.97638in;height:1.92878in" alt="스크린샷이(가) 표시된 사진 자동 생성된 설명" />

<img src="2020-09-09-My-first-blog-with-fastpages//media/image13.png" style="width:5.79528in;height:2.15156in" alt="스크린샷이(가) 표시된 사진 자동 생성된 설명" />

1.  **이제 merge만 하면 됩니다.  
    다시 상단 탭의 Pull requests -&gt; Initial Setup  
    스크롤을 내려주시면 그림과 같이  
    Merge pull request 버튼이 있습니다. 눌러주세요.  
    Confirm merge 눌러주세요**

> <img src="2020-09-09-My-first-blog-with-fastpages//media/image14.png" style="width:6.26806in;height:2.7125in" alt="스크린샷이(가) 표시된 사진 자동 생성된 설명" />

<img src="2020-09-09-My-first-blog-with-fastpages//media/image15.png" style="width:6.26806in;height:2.91181in" alt="스크린샷이(가) 표시된 사진 자동 생성된 설명" />

<img src="2020-09-09-My-first-blog-with-fastpages//media/image16.png" style="width:6.26806in;height:1.43403in" alt="스크린샷이(가) 표시된 사진 자동 생성된 설명" />

1.  **Actions 탭에 가시면  
    3개의 Merge pull이 자동으로 진행된 것을 보실 수 있습니다.**

<img src="2020-09-09-My-first-blog-with-fastpages//media/image17.png" style="width:6.26806in;height:2.74028in" alt="스크린샷이(가) 표시된 사진 자동 생성된 설명" />

1.  **&lt;&gt;Code 탭으로 가시면 README가  
    My Blog로 바뀐 것을 볼 수 있습니다.**

<img src="2020-09-09-My-first-blog-with-fastpages//media/image18.png" style="width:6.26806in;height:4.49861in" alt="스크린샷이(가) 표시된 사진 자동 생성된 설명" />

**끝!! 블로그 개설 성공입니다!!**

참고로 UX/UI를 custom하길 좋아하시는 사용자들은 추천하지 않는 툴이라고합니다.

이유는 즉 이 템플렛은 fastpage 제작자들의 그 시스템이 적용되고 업데이트 되기 때문이죠.

그저 간편하게 포트폴리오용으로 제작하기에는 매우 좋은 방법이라고 생각됩니다.

앞으로 자주 Blogging하도록 하겠습니다.
