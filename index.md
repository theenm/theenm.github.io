**Conference / Meetup**
1. RTC Conference Korea 2018 https://rtckorea.com/
2. WebRTC Meetup Seoul 2019  https://www.youtube.com/watch?v=Wf-2GJNm1e4&ab_channel=rtckorea
3. WebRTC Meetup Seoul 19.09.05 https://www.youtube.com/watch?v=8jXtSg5DFtk**
> * 화상회의에서 WebRTC 로컬 레코딩 - 신상준(유프리즘)
> * WebRTC와 새로운 코덱 AV1 - 한현섭(리모트몬스터)
> * Docker기반 Janus 설치 및 구성 - 손태희(리모트몬스터)
> * WebRTC on WebOS - 김범준(LG전자)
> * WebRTC 방송 송출이 가능한 OBS 프로젝트 개발기 - 정주호(리모트몬스터)
4. WebRTC Meetup Seoul 20.05.14 https://www.youtube.com/watch?v=75mDKX2ufcQ**
> * 언택트 서비스 사례 - 최진호(RemoteMonster)
> * 대용량 WebRTC 성능 향상 사례 - 차민수 (uPrism)
> * WebRTC 기반의 컨택센터 솔루션 - 정유철 (더화이트커뮤니케이션)
> * B2B 시장에서의 WebRTC 활용 - 홍정현    (오디오코즈)
> * SendBird Call SDK - 김성혁 (센드버드)

**미디어 서버 서베이**
1. mediasoup
> ![](https://theenmgw.daouoffice.com/resources/images/mail/inline/20210218/gs.ko@theenm.com_inline_img_CAD17796307C400C9D2DD3BA64FCA0B7.png)
> * https://mediasoup.org/documentation/v3/scalability/
> * 아프리카티비 합동 방송 : WebRTC 사용
> * HyperConnect 라이브 방송 : Janus Gateway 사용
2. Janus
> * https://github.com/meetecho/janus-gateway
> * https://janus.conf.meetecho.com/
> * https://github.com/hyperconnect/janus-gateway
> * https://dangen-effy.github.io/post/janus-%EC%86%8C%EA%B0%9C%EC%99%80-docker-%EA%B8%B0%EB%B0%98%EC%9C%BC%EB%A1%9C-%EC%89%BD%EA%B2%8C-%EC%82%AC%EC%9A%A9%ED%95%98%EA%B8%B0/
3. Audio Codec 스터디**
> ![](https://theenmgw.daouoffice.com/resources/images/mail/inline/20210218/gs.ko@theenm.com_inline_img_EE936B842EA0462C95400828A93BFE95.jpg)
> * 48KHz 샘플링만 지원, 극저, 극고 비트레이트에서는 불리, latency (기본 26.5ms, 최적화시 5ms)
> * https://en.wikipedia.org/wiki/Opus_(audio_format)

**코드 샘플 서베이**
1. 미디어 수집 API https://developer.mozilla.org/en-US/docs/Web/API/MediaTrackConstraints
1. 기본 샘플 https://webrtc.org/
1. 참여방송 샘플 https://www.webrtc-experiment.com/MultiStreamsMixer/, https://github.com/muaz-khan/MultiStreamsMixer
1. 구글 포럼 https://groups.google.com/g/discuss-webrtc?pli=1
1. 테스트 샘플 https://www.html5rocks.com/en/tutorials/webrtc/basics/
1. WebRTC 엔진 소스 https://webrtc.googlesource.com/src/, https://webrtc.googlesource.com/src/+/refs/heads/master/docs/native-code/index.md
1. WebRTC SFU Load Testing (Alex Gouaillard) https://choisee02.tistory.com/33, https://webrtchacks.com/sfu-load-testing/
1. 리모트몬스터 https://github.com/RemoteMonster/remon-show, https://github.com/calmglow/expedition
1. 테스트 도구 chrome://webrtc-internals

**코드 샘플 서베이2**
1. Build WebRTC MCU on Browser https://speakerdeck.com/mganeko/build-webrtc-mcu-on-browser
> * Canvas captureStream(), WebAudio API
> * 일부 소스 공개 됨 https://github.com/mganeko/browser_mcu_server, https://qiita.com/massie_g
> * 2017년 소스코드이긴 하지만, 샘플 테스트 예정
2. Sample source (TODO TEST)**
> * WebRTC Voice Demo https://www.tutorialspoint.com/webrtc/webrtc_voice_demo.htm
> * WebRTC security https://www.tutorialspoint.com/webrtc/webrtc_security.htm

**아키텍트**
1. mediasoup https://www.npmjs.com/package/mediasoup
2. mediasoup  스케일링 https://mediasoup.org/documentation/v3/scalability/
3. REST 보안가이드 https://bcho.tistory.com/955

**#확장성 리뷰**
1. mediasoup https://mediasoup.org/documentation/v3/scalability/
2. janus https://www.slideshare.net/LorenzoMiniero/scaling-webrtc-applications-with-janus
3. sfu vs mcu https://www.slideshare.net/LorenzoMiniero/can-sfus-and-mcus-be-friends-iitrtc-2020

**#Tutorial**
1. https://www.tutorialspoint.com/webrtc/webrtc_security.htm
