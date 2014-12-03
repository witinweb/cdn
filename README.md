#CDN을 사용해야하는 7가지 이유

글쓴이 : [Craig Buckler](http://www.sitepoint.com/author/craig-buckler/)
번역 : [공잠](http://gongjam.co.kr/)

CDN(Content Delivery Networks)는 지난 몇 년 동안 웹 호스팅에 큰 변화를 일으켰습니다. 하나의 서버에서 여러분의 웹사이트를 호스팅하는 대신 파일들을 분산시키고 여러 시스템에 걸쳐 로드합니다.

##어떤 파일을 CDN에 호스팅할 수 있을까요?

대부분의 CDN들은 이미지, 비디오, 오디오 클립, CSS파일과 자바스크립트 파일과 같은 정적인 자원들을 호스팅합니다. 여러분은 공동 자바스크립트 라이브러리들, HTML5 shims들, CSS 초기화 파일들, 폰트 파일들 등 CDN 시스템에 사용할 수 있는 자원들을 찾을 수 있을 것입니다.

##CDN 서비스

구글, 마이크로소프트, 야후 등 큰 웹 서비스에 의해 제공되는 무료 CDN 들이 많습니다. 예컨대 어떤 이들은 자신의 비디오들을 [유뷰브](http://www.youtube.com/)과 [Vimeo](http://vimeo.com/)에 호스팅합니다. 마찬가지로 제이쿼리를 사용할 때 다음과 같이 페이지에 로드할 수 있습니다:

```javascript
    <div>
        <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.6.4/jquery.min.js.js"></script>
    </div>
    or
    <div>
    <script src="http://ajax.aspnetcdn.com/ajax/jQuery/jquery-1.6.4.min.js"></script>
    </div>
```

다른 방법으로는 [Amazon S3](http://aws.amazon.com/s3/), [Microsoft Windows Azure](http://www.microsoft.com/windowsazure/) 와 [MaxCDN](http://maxcdn.com/)처럼 상업적인 CDN 서비스들을 사용할 수도 있습니다.

##CDN 사용의 장점

CDN이 여러분의 웹사이트와 회사에 왜 이득이 되는지에대한 몇 가지 이유가 있습니다.

1. 다른 도메인

브라우저는 도메인당 동시 연결 수를 제한합니다. 대부분 동시연결을 4개로 제한하기 때문에 다섯 번째 파일의 다운로드는 이전 파일중 하나가 완전히 받아질 때까지 차단됩니다. 여러분은 같은 도메인으로부터 많은 파일들을 다운받을 대 이런 제한을 종종 겪을 수 있습니다.

CDN 파일들은 다른 도메인에 호스팅되어 있습니다. 사실상 단일 CDN은 브라우저로 하여금 동시에 4개이상의 파일 다운로드를 허용하게 되는 것입니다.

2. 파일들이 미리 캐쉬될 수 있습니다

제이쿼리는 웹상에서 어디에서든 흔히 볼 수 있습니다. 여러분의 페이지에 방문한 사람들은 이미 구글 CDN을 사용하는 사이트를 방문했었을 확률이 매우 높습니다. 그러므로 제이쿼리 파일은 이미 방문자의 브라우저에 캐쉬되어있을 것이므로 여러분의 페이지에서 다시 다운로드 받을 필요가 없습니다.

3. 대용량 인프라

여러분이 아무리 좋은 호스팅을 가지고 있다고 하더라도 나는 구글, 마이크로소프트나 야후가 제공하는 용량과 확장성 만큼은 되지 않는다고 확신합니다. 더 나은 CDN들은 더 높은 가용성을 제공하고 네트워크 대기시간과 패킷 손실이 작습니다.

4. 분산된 데이터 센터들

만약 여러분의 메인 웹 서버가 Dallas에 있다면 유럽과 아시아 사용자들이 파일에 접근할때 대륙을 횡단해야 합니다. 많은 CDN들은 사용자에게 더 가까운 지역 데이터 센터를 제공해서 더 빠르게 다운로드 됩니다.

5. 내장된 버전관리

보통 CSS파일이나 자바스트립트 라이브러리의 특정 버전에 연결 가능합니다. 종종 “마지막 버전”을 요청할 수도 있습니다.

6. 사용 분석

많은 상업 CDN들은 일반적으로 바이트 단위로 요금을 부과하기 때문에 파일의 사용 보고서를 제공합니다. 이 보고서는 여러분의 웹사이트 분석에 사용될 수 있고 어떤 때에는 동용상 조회사나 다운로드 수보다 더 나은 의견을 줄 수 있습니다.

7. 성능향상과 비용 절감

CDN은 부하를 분산시키고 대역폭을 절약하고 성능을 향상시키며 호스팅 비용(때로는 무료)을 절감할 수 있습니다.

_좋아하지 않을 이유가 무엇일까요?_

여러분이 기대하는 것처럼 이것이 전부가 아닙니다. 곧 [CDN을 사용하지 않는 7가지 이유](http://www.sitepoint.com/7-reasons-not-to-use-a-cdn/) 로 돌아오겠습니다...
