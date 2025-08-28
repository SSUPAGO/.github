<h2 align="center">SSUPAGO </h2>
<h3 align="center">혐오/차별 발언 필터링 서비스 🤬->😊</h3>

<p align="center">
<img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FSSUPAGO&count_bg=%23F23064&title_bg=%23254159&icon=&icon_color=%23E7E7E7&title=%E2%9D%A4%EF%B8%8F&edge_flat=false"/>
</p>


<p align="center">
  <img src="https://user-images.githubusercontent.com/50352139/190885285-ed29d912-1c9f-4ac9-8369-523aa1d6376f.jpg" />
</p>



<details>
    <summary>
    <h4>Development background and purpose</h4>
    </summary>

'혐오의 시대' 최근 우리 사회에 뿌리내려가고 있는 혐오의 심각성을 드러내는 말이다. '혐오'의 문제는 오래 전부터 논의됐지만, 포털 사이트의 인터넷 뉴스 댓글, SNS, 커뮤니티에서의 명예훼손 사건들부터 전국장애인차별철폐연대 시위 이슈를 필두로 일어난 장애인 혐오 발언, 혐오 범죄 등 문제는 더욱 심각해져 가고 있다. 그뿐만 아니라 '혐오 범죄'에 대한 책임의 명확성, 예방 대책도 매우 미흡한 현실이다. 이에 본 프로젝트에서는 이러한 문제를 직시하고 이를 'AI - 딥러닝' 기술로 풀어가고자 하였다. 

본 프로젝트 진행에 앞서, 우리 사회의 혐오 문제의 심각성에 관한 실제 사례들과 통계자료들을 분석한 결과, 해당 문제의 위험성과 이 위험성을 제대로 인지하지 못하는 사람들의 인식 편향 문제도 매우 심각함을 확인할 수 있었다. 
대표적으로 코로나 19 이후 발생한 아시안 혐오 범죄가 있다. 코로나로 인해서 아시안들이 해외에서 각종 혐오 범죄와 발언들에 노출되는 빈도가 높아졌는데 이러한 상황은 우리나라에서도 똑같이 재현되었다. 한겨레 기사에 따르면 국내 코로나 확진자 발생 이후 한국 내 온라인상에서 중국인에 대한 혐오 발언이 급증한 것을 확인할 수 있었다.

이러한 문제 해결을 위해 신고제와 같은 여러 법안이 제안되고 있지만, 사람들의 자발적 신고에만 의존하거나 제대로 된 시스템 구축이 어렵다는 한계에 부딪히고 있다. 
이에 슈파고 팀은 한국어를 기반으로 한 혐오 발언 필터링 서비스를 제공하고자 한다. 혐오 및 차별 발언을 분류해 낼 수 있는 딥러닝 모델을 구축하고 모델의 입력과 출력값을 HTTP 통신을 통해 전달할 수 있도록 하였다. API 방식으로 모델을 어디서나 사용할 수 있게 함으로써 사용자의 접근성과 활용성을 높인다. 또한, 한국어 기반 자연어 처리에 특화된 BERT 구조의 모델을 구축함으로써 더욱더 높은 정확도를 갖춘 서비스를 제공할 수 있도록 한다. 

The term “Era of Hate” reflects the growing seriousness of hatred that has taken root in our society today. While the issue of hate has long been discussed, it has become increasingly severe with defamation cases arising from online news comments on portal sites, social media, and communities; hate speech against people with disabilities sparked by protests led by the Solidarity Against Disability Discrimination (SADD); and hate crimes. Furthermore, accountability for hate crimes and preventive measures remain highly insufficient in reality. In response, this project aims to confront these problems and address them using AI and deep learning technologies.

Before proceeding with the project, we analyzed real-world cases and statistical data related to the seriousness of hate in our society. The findings revealed not only the dangers of such problems but also the severe issue of perception bias among people who fail to recognize these risks. A representative example is the surge in anti-Asian hate crimes following COVID-19. Asians abroad were increasingly subjected to hate crimes and hate speech, and this trend was mirrored in Korea. According to The Hankyoreh, after the first confirmed COVID-19 cases in Korea, online hate speech against Chinese people rose sharply.

Although various legislative measures such as reporting systems have been proposed to address these problems, they face limitations by relying solely on voluntary reports from individuals or the lack of proper system implementation. To tackle these challenges, Team Supago has developed a Korean-language-based hate speech filtering service. The system classifies hate and discriminatory expressions through a deep learning model and enables communication of input and output values via HTTP. By providing the model in an API format, the service enhances accessibility and usability for users anywhere. Moreover, by building the model on a BERT architecture specialized for Korean natural language processing, the system ensures higher accuracy and more reliable service delivery.
    
</details>


<h4> Development environment</h4></summary>

![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)
![Gunicorn](https://img.shields.io/badge/Gunicorn-%298729.svg?style=flat-square&logo=Gunicorn&logoColor=white)
![Nginx](https://img.shields.io/badge/NGINX-%23009639.svg?style=flat-square&logo=nginx&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)

![image](https://user-images.githubusercontent.com/50352139/190885529-80c8d535-a69e-4fe5-bede-90debc2f9236.png)
