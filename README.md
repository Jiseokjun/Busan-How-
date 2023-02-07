# Busan-How-
부산어때
프로젝트 DB
CREATE TABLE "PROJECT"."ALLFS" 
   (	"A_NAME" VARCHAR2(80 BYTE), 
	"A_DATE" VARCHAR2(50 BYTE), 
	"A_ADDRESS" VARCHAR2(200 BYTE), 
	"A_FEE" VARCHAR2(100 BYTE), 
	"A_TEL" VARCHAR2(20 BYTE), 
	"A_HP" VARCHAR2(300 BYTE), 
	"A_LATITUDE" FLOAT(126), 
	"A_LONGITUDE" FLOAT(126), 
	"A_INTRO" VARCHAR2(4000 BYTE), 
	"A_CODE" NUMBER(7,0)
   ) SEGMENT CREATION IMMEDIATE 
  PCTFREE 10 PCTUSED 40 INITRANS 1 MAXTRANS 255 
 NOCOMPRESS LOGGING
  STORAGE(INITIAL 65536 NEXT 1048576 MINEXTENTS 1 MAXEXTENTS 2147483645
  PCTINCREASE 0 FREELISTS 1 FREELIST GROUPS 1
  BUFFER_POOL DEFAULT FLASH_CACHE DEFAULT CELL_FLASH_CACHE DEFAULT)
  TABLESPACE "USERS" ;
REM INSERTING into PROJECT.ALLFS
SET DEFINE OFF;
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('40계단','40계단 문화관 매주 월 휴무','부산시 중구 대청로135번길 13','무료','051-600-4046','http://www.bsjunggu.go.kr/tour/index.junggu?menuCd=DOM_000000208001001000&link=success&cpath=%2Ftour',35.1039739,129.0346464,'부산항 부두에서 고지대 판자촌으로 이어지는 길목. 피난민들의 애환이 스며든 생생한 삶의 현장',6001);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('apec나루공원',null,'부산시 해운대구 우동 1494(수영강변대로 93)','무료','051-749-4000','http://heundae.com/?site=apec-%EB%82%98%EB%A3%A8%EA%B3%B5%EC%9B%90',35.1706486,129.1254273,'수영강변에 따라 뻗어 있는 도심 속 강바람을 느낄 수 있는 평화로운 작은 공원',6002);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('감천문화마을','09:00 ~18:00','부산시 사하구 감내2로 203','무료','051-204-1444','https://www.gamcheon.or.kr/',35.0973904,129.0105924,'하늘에 닿을 것만 같은 형형색색의 지붕과 질서정연하게 늘어선 계단식 마을의 독특한 아름다움',6003);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('광안리해수욕장',null,'부산시 수영구 광안해변로 219','무료, 프로그램별 상이','051-622-4251','http://www.suyeong.go.kr/tour/index.suyeong',35.152813,129.118218,'광안대교와 함께 부산을 대표하는 해수욕장. 도심과 가장 가까운 해변이자 젊은이들의 성지',6004);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('국립일제강제동원역사관','매주 월 휴무','부산시 남구 홍곡로320번길 100','무료','051-629-8600','https://www.fomo.or.kr/museum',35.12499,129.092335,'식민지 조선의 아픈 역사와 일제의 강제동원 만행을 기록하기 위한 역사관',6005);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('국립해양박물관','매주 월요일 휴무','부산시 영도구 해양로301번길 45','무료','051-309-1900','https://www.mmk.or.kr/',35.0783256,129.0798565,'바다의 과거와 현재, 미래, 세상의 모든 바다 이야기가 시작되는 해양박물관',6006);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('금강공원과식물원',null,'부산시 동래구 우장춘로 155','대인 1000원 어린이 및 경로우대 500원','051-582-3284','https://www.bisco.or.kr/geumgangpark/',35.2201331,129.0738073,'울창한 숲과 기암괴석의 조화가 아름다운 금정산에 있는 도심 속 공원',6007);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('기장달음산자연휴향림','화요일 휴무','부산시 기장군 일광면 화용길 299-106','무료','051-722-3023','https://www.foresttrip.go.kr/indvz/main.do?hmpgId=0202',35.301617,129.185367,'잔디광장을 중심으로 둥글게 배치된 숙소가 저마다의 색깔을 뽐내며 방문객을 맞이하는 자연공간',6008);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('기장도예관광힐링촌',null,'부산시 기장군 장안읍 기룡리 산126','무료','051-728-3909','https://www.gijang.go.kr/tour/index.gijang?menuCd=DOM_000000301008000000',35.360046,129.239801,'공기 좋은 기장 기룡마을 산자락에 펼쳐진, 동심 속 동화마을이 펼쳐진 힐링촌 테마숲',6009);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('다대포',null,'부산시 사하구 몰운대1길 14','무료','051-220-5895','https://www.saha.go.kr/tour/contents.do?mId=0101030000',35.046999,128.966551,'낙동강과 남해안이 만나 희고 고운 모래사장을 거닐 수 있는 해수욕장',6010);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('대신공원',null,'부산시 서구 대신공원로 37-18','무료','051-860-7830','-',35.1211379,129.0167921,'수령 높은 노목들이 오색찬란하게 빛을 발하는 도심 속 휴식 공간. 자연 그대로의 힐링 쉼터',6011);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('동래읍성','매주 월 휴무','부산시 동래구 명륜동 산48-2','무료','051-550-6634','-',35.2101539,129.0894131,'과거 부산 그 자체였던 동래를 감싸고 있는 읍성. 조용히 여유와 자연을 즐길 수 있는 곳',6012);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('동아대학교석당박물관','매주 일,월 휴무','부산시 서구 구덕로 225','무료','051-200-8493','http://museum.donga.ac.kr/',35.1042116,129.0191299,'대한민국의 3대 대학박물관. 한 때 임시정부청사, 부산지방검찰청으로 쓰인 근대문화유산',6013);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('민락수변공원','00:00 ~ 02:00','부산시?수영구?민락수변로?129','무료','051-610-4216','https://www.suyeong.go.kr/board/view.suyeong?boardId=BBS_0000073&menuCd=DOM_000001101001000000&startPage=1&dataSid=296',35.1545716,129.1329907,'푸른 하늘과 끝없는 바다가 한눈에 펼쳐지는 풍경을 가진 광안리 바다의 낭만',6014);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('민주공원','매주 월 휴무','부산시 중구 민주공원길 19','무료','051-790-7400','http://www.demopark.or.kr/main/',35.1100718,129.0280727,'호국용사와 민주영령의 살아있는 정신이 고스란히 전해지는 중앙공원',6015);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('백산기념관','매주 월 휴무','부산시 중구 백산길 11 백산기념관','무료','051-600-025','https://www.bsjunggu.go.kr/tour/index.junggu?menuCd=DOM_000000208002001000&link=success&cpath=%2Ftour',35.1019518,129.0345919,'백산상회를 일으켜 독립운동에 자금을 지원한 백산 안희제 선생을 기념하기 위한 공간 ',6016);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('범어사',null,'부산시 금정구 범어사로 250','무료','051-508-3122','http://www.beomeo.kr/',35.2839899,129.0687639,'빼어난 산세를 자랑하는 금정산 자락에 위치한 신라 문무왕때 건축된 역사적인 사찰',6017);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('벡스코',null,'부산시 해운대구 APEC로 55','프로그램별 상이','051-740-7300','http://www.bexco.co.kr',35.1689766,129.1360411,'부산의 대형 행사와 박람회가 열리는 국제적 규모의 전시컨벤션센터',6018);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('보수동책방골목','도서구입 별도','부산시 중구 책방골목길 16','무료','051-253-8253','http://www.bosubook.com/',35.1031252,129.0274609,'입구 풍경에서부터 예스러움이 가득 묻어나는, 한 줄기 따뜻한 아날로그 감성을 지닌 책방들의 골목',6019);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('복천박물관,복천동고분군','매주 월 휴무','부산시 동래구 복천로 63 복천박물관','무료','051-554-4263','https://museum.busan.go.kr/bokcheon/index',35.2083599,129.0914505,'가야의 뛰어난 철기문화를 알려주는 유물과 다양한 형태의 무덤이 전시되어 있는 박물관',6020);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('부산치유의숲',null,'부산시 기장군 철마면 철마천로 101','무료','051-976-2831','https://cafe.naver.com/busangreenforest',35.272772,129.137896,'청정자연을 그대로 품은, 아홉산 자락에 넓게 자리한 부산 최초로 조성된 치유의 숲',6021);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('부산근대문화역사관','휴관(06/29-12/31)','부산시 중구 대청로 104','무료','051-253-3845','https://www.busan.go.kr/mmch',35.1026721,129.031176,'대한민국의 아픈 역사 일제강점기, 그리고 근대화 시기의 부산의 역사를 간직한 곳',6022);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('부산도서관','09:00 ~ 22:00','부산시 사상구 사상로310번길 33','무료','051-310-5400','https://library.busan.go.kr/busanlibrary/index.do',35.172711,128.9853636,'깔끔한 외관, 창문 너머로 한 가득 쏟아지는 햇살을 품은 부산의 대표 도서관',6023);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('부산박물관','매주 월 휴무','부산시 남구 유엔로 152','무료','051-610-7111','museum.busan.go.kr/busan',35.1295178,129.094151,'구석기 유물부터 근현대에 이르기까지 부산의 역사를 한 번에 아우르는 부산을 대표하는 박물관',6024);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('부산시민공원','05:00 ~ 24:00','부산시 부산진구 시민공원로 73','무료','051-850-6000','https://www.citizenpark.or.kr/',35.1681608,129.0573853,'하야리야 부대가 있던 곳에서 70년 만에 부산 시민의 따뜻한 쉼터로 돌아온 공원',6025);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('부산엑스더스카이전망대','1000  21:00','부산시 해운대구 달맞이길 30','대인 27,000원 소인 24,000원','051-731-0099','http://www.busanxthesky.com/',35.1599375,129.1698125,'국내에서 두 번째로 높은 건물에 있는 바다와 도시를 한 번에 조망할 수 있는 전망대',6026);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('부산임시수도기념관','매주 월 휴무','부산시 서구 임시수도기념로 45','무료','051-244-6345','http://museum.busan.go.kr/monument/index',35.1034532,129.0174521,'한국 전쟁이 일어난 직후 임시수도가 된 부산의 대통령 관저로 쓰인, 부산의 역사를 담은 기념물',6027);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('사직야구장',null,'부산시 동래구 사직로 45','좌석 별 상이','051-505-7422','http://www.giantsclub.com/html/',35.1940316,129.0615183,'야구를 사랑하는 야구의 도시 부산의 인기구단 롯데 자이언츠의 홈구장',6028);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('삼락생태공원',null,'부산시 사상구 낙동대로 1231','무료','051-303-0048',null,35.1687484,128.9735403,'유유히 흘러가는 낙동강 줄기 옆에 삼락동 둔치에 넓게 자리잡은 생태공원',6029);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('송도용궁구름다리','휴무(11/03-12/31)','부산시 서구 암남동 620-53','서구 구민 1천원, 일반관광객 2천원','051-240-4087','https://www.bsseogu.go.kr/tour/index.bsseogu',35.061884,129.022211,'바나 건너 작은 섬 동섬을 연결한 구름다리. 사랑을 이어주는 행운을 부르는 다리',6030);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('송도해수욕장','06:00 ~ 23:00','부산시 서구 암남동 송도해수욕장','무료','051-501-6054','http://www.bfo.or.kr/main/index.asp',35.076122,129.017298,'1913년에 개장한 우리나라 1호 해수욕장. 송도스카이워크, 해상케이블카를 이용할 수 있다',6031);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('송상현광장',null,'부산시 진구 중앙대로 818','무료','051-850-6081','http://www.songsanghyeon.com/song/Main.do',35.1641542,129.0648058,'도심 한가운데 아름다운 숲과 실개천을 간직한 광장. 시민을 위한 부산 최대 규모의 도심광장',6032);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('송정해수욕장',null,'부산시 해운대구 송정동 송정해수욕장','무료','051-501-6055','http://www.bfo.or.kr/main/index.asp',35.17827,129.199126,'달맞이 길을 돌아 내려오면 보이는 넓고 길게 펼쳐진 백사장. 서퍼들이 사랑하는 바다',6033);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('수영F1963','09:00 ~ 21:00','부산시 수영구 구락로123번길 20','무료','051-756-1963','http://www.f1963.org/ko/',35.1769907,129.1154605,'2008년까지 운영되었던 와이어공장 부지를 탈바꿈시킨 복합문화공간',6034);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('수영사적공원',null,'부산시 수영구 수영성로 43','무료','051-752-2947','http://www.suyeongminsok.or.kr',35.1710871,129.1139105,'조선시대 남해안 수군지휘부가 있던 자리에 만든 사적공원이자 유적공원',6035);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('아미산전망대','매주 월 휴무','부산시 사하구 다대낙조2길 77','무료','051-265-6863','busan.go.kr/wetland/amisanintro01',35.052544,128.960647,'낙동강의 끝자락이 남해안과 만나 바다가 되기 전, 거대한 삼각주의 강과 바다의 환상적인 분위기',6036);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('어린이대공원',null,'부산시 부산진구 새싹로 295','무료','051-860-7848','https://www.bisco.or.kr/bschildpark/',35.1846343,129.0434794,'아이와 함께 어린이회관부터 오르막을 지나 놀이터까지, 자연속에서 동심을 즐기는 곳',6037);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('영도대교',null,'부산시 영도구 대교동1가 190-1','무료','-','-',35.0930473,129.0374683,'부산  최초의 연륙교이자 도개교, 그리고 수많은 피란민들의 눈물로 약속한 공간 ',6038);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('영화의거리',null,'부산시 해운대구 마린시티1로 91','무료','-','-',35.1547966,129.144653,'부산에서 촬영한 천만관객을 이끈 영화들을 위한 영화의 거리',6039);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('영화의전당',null,'부산시 해운대구 수영강변대로 120','프로그램별 상이','051-780-6000','http://www.dureraum.org',35.1711778,129.1271956,'거대한 빅루프의 LED조명이 특징인 부산의 랜드마크. 영화의 도시 부산을 상징하는 곳',6040);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('오랑대공원',null,'부산시 기장군 기장읍 기장해안로 340','무료','-','-',35.2057006,129.2276931,'바다의 안녕을 기원하는, 갯바위에 부딪히는 파도소리가 마음의 평안을 가져다주는 공원',6041);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('오륙도',null,'부산시 남구 오륙도로 137','홍보관 무료 / 유람선 별도','051-607-6395',' https://www.bsnamgu.go.kr',35.097635,129.120893,'동해와 남해가 만나는 바다위의 부산에서 가장 아름다운 섬',6042);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('용두산공원',null,'부산시?중구?대청로116번길 13','무료','051-860-7820','https://www.bisco.or.kr/yongdusanpark/',35.1006536,129.0326226,'부산을 찾는 이들이 빼놓지 않고 찾는 부산의 대표 랜드마크',6043);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('우암동소막마을',null,'부산시 남구 우암동','무료','-','-',35.1249213,129.0743458,'화려한 부산의 가려진 역사. 피란민들의 움막과 판잣집으로 이루어진 부산의 옛 흔적',6044);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('유엔기념공원','하절기(09:00~18:00),동절기(09:00~17:00)','부산시 남구 유엔평화로 93','무료','051-625-0625','www.unmck.or.kr',35.1279039,129.0961877,'세계 유일의 유엔기념묘지. 세계평화와 자유를 위해 생명을 바친 유엔군 전몰 장병들이 잠든 곳',6045);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('초량1941','11:00 ~ 19:00','부산시 동구 망양로 533-5','이용요금 별도','051-462-7774','https://ntchmgsugung.modoo.at/',35.1198148,129.029509,'일제강점기에 지어진, 주변의 현대식 풍경과 대비되는 독특한 매력을 지닌 공간',6046);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('커피박물관','매주 토요일 휴무','부산시 부산진구 동천로 70 2층 207호','무료','010-9346-8000','https://www.kpeople24.com/home/info/2133',35.154865,129.062732,'부산 최초의 커피전문박물관. 긴 시간에 걸쳐 발전한 커피의 긴 여정이 있는 곳',6047);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('태종대','하절기(04:00~24:00),동절기(05:00~24:00)','부산시 영도구 전망로 24','무료(다누비 열차 요금 별도)','051-405-8745','https://www.bisco.or.kr/taejongdae/',35.046999,128.966551,'오랜 세월 파도에 깎여 각양각색의 신비를 가진 바위해안의 수려함을 볼 수 있는 곳',6048);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('해동용궁사','04:00 ~ 20:30','부산시 기장군 기장읍 용궁길 86','무료','051-722-7744','http://www.yongkungsa.or.kr',35.1883491,129.2233197,'시원하게 트인 기장 앞바다에서 감탄이 절로 나오는 해안절경과 망망대해를 눈 앞에 두는 곳',6049);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('해운대해수욕장','09:00 ~ 18:00','부산시 해운대구 해운대해변로 264','무료','051-749-7601','http://sunnfun.haeundae.go.kr/',35.158601,129.160001,'부산 바다의 정석. 다른 어떤 곳보다 다이내믹한 부산의 분위기를 느낄 수 있는 장소',6050);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('화명수목원','매주 월요일 휴무','부산시 북구 산성로 299','무료','051-362-0261','https://www.busan.go.kr/green/index',35.2510047,129.0427975,'금정산 자락에 사뿐히 내려앉은 수목원. 시원한 물줄기와 산내음이 기분 좋은 하루를 만들어 주는 곳',6051);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('흰여울문화마을',null,'부산시 영도구 흰여울길','무료','051-419-4067','http://www.ydculture.com/huinnyeoulculturetown/',35.078255,129.045316,'가파른 절벽 끝, 부산의 대표적 원도심 흰여울길에 있는 영도의 독창적 문화예술마을',6052);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('감천문화마을골목축제','매년 4월 말','부산시 사하구 감내2로 203','무료','051-220-5911','https://www.gamcheon.or.kr/',35.0961559,129.0089071,'흥이 넘쳐나는 감천골. 전쟁의 상흔을 딛고 보존과 재생의 마을에서 다니는 미로 골목길 투어',1001);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('광안리어방축제','10월 중순','부산시 수영구 광안해변로 219','무료','051-610-4062','http://www.suyeong.go.kr/eobang',35.1537821,129.1185399,'매년 4월, 어업협동체 어방의 전통을 이어가는 어방축제가 광연대교를 배경으로 화려한 막을 연다',1002);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('금정산성축제','매년 10월 말','부산시 금정구 장전온천천로 144','무료','051-512-3455','https://blog.naver.com/geumjeonggu/222904230446',35.2755,129.0575042,'금정산성과 녹음이 우거진 마을에서 호패 하나 손에 쥐고 떠나는 오감만족 역사문화여행',1003);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('기장멸치축제','매년 4월','부산시 기장군 기장읍 대변항 일원','무료','051-709-4502','http://www.gijang.go.kr/tour/index.gijang',35.2247703,129.2301119,'풍요로운 봄바람, 기장의 앞바다. 오동통통 살이 오른 신선한 기장멸치를 즐긴다',1004);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('기장미역다시마축제','매년 4월','부산시 기장군 일광면 이동길 43','무료','051-709-4000','http://www.gijang.go.kr/tour/index.gijang',35.2722418,129.245967,'기장 앞바다의 봄은 수확의 계절. 기장 이동항에서 열리는 미역과 다시마의 먹거리 천국',1005);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('낙동강구포나루축제','10월 중','부산시 북구 낙동대로1739번길 257 화명생태공원 선착장','무료','051-309-4980','http://guponarufes.co.kr/',35.220095,128.9994207,'싱그러운 봄. 솔솔 부는 강바람에 정겨운 북적거림이 실려오는 구포나루의 추억과 낭만',1006);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('낙동강유채꽃축제','매년 4월','부산시 강서구 대저생태공원','무료','051-501-6051','http://www.bfo.or.kr/',35.2048909,128.982775,'유채꽃 향기가 가득한 대저생태공원에서 펼쳐지는 샛노란 봄날의 유혹',1007);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('대저토마토축제','매년 4월','부산시 강서구 체육공원로 43(강서체육공원)','무료','051-970-4812','https://www.bsgangseo.go.kr/visit/contents.do?mId=0305000000',35.209882,128.972345,'4월이 시작되면 열리는 빨간 토마토의 향연. 몸에 좋고 맛도 좋은 토마토를 즐기는 대저토마토축제',1008);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('동래읍성역사축제','10월','부산시 동래구 문화로 80','무료(일부 체험 유료)','051-550-4000','https://www.dongnae.go.kr/festival/index.dongnae?contentsSid=169',35.2118622,129.0899982,'청명한 가을에 만나는 동래읍성 역사축제가 시작되면 부산은 1592년의 그 때로 돌아간다',1009);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('부산국제영화제','10월','부산시 해운대구 수영강변대로 120(영화의 전당)','일반상영작 8,000원, 행사 및 체험 일부 무료','1688-3010','https://www.biff.kr/kor/',35.1711778,129.1271956,'10월이 되면 아시아를 대표하는 영화제와 함께 부산은 영화의 바다에 빠져든다',1010);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('부산바다미술제','10월','부산시 사하구 몰운대1길 14','무료','051-503-6111','http://www.busanbiennale.org/intro.html',35.0457857,128.968704,'자연 그대로의 바다를 간직한 다대포 해수욕장에서 예술전시물들로 예술의 향기 속에 빠져 보자',1011);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('부산바다축제','7월말~8월초','부산시 해운대구 해운대 해수욕장','무료','051-501-6051','http://www.bfo.or.kr/main/index.asp',35.158367,129.159007,'타오르는 태양, 시원한 바다, 금빛 백사장, 화려한 네온사인, 신나는 음악을 한 번에 즐기는 여름축제',1012);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('부산바다축제','7월말~9월초','부산시 수영구 광안동 광안리해수욕장','무료','051-501-6052','http://www.bfo.or.kr/main/index.asp',35.152502,129.118065,'타오르는 태양, 시원한 바다, 금빛 백사장, 화려한 네온사인, 신나는 음악을 한 번에 즐기는 여름축제',1013);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('부산바다축제','7월말~10월초','부산시 사하구 다대동 다대포해수욕장','무료','051-501-6053','http://www.bfo.or.kr/main/index.asp',35.046338,128.967912,'타오르는 태양, 시원한 바다, 금빛 백사장, 화려한 네온사인, 신나는 음악을 한 번에 즐기는 여름축제',1014);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('부산바다축제','7월말~11월초','부산시 서구 암남동 송도해수욕장','무료','051-501-6054','http://www.bfo.or.kr/main/index.asp',35.076122,129.017298,'타오르는 태양, 시원한 바다, 금빛 백사장, 화려한 네온사인, 신나는 음악을 한 번에 즐기는 여름축제',1015);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('부산바다축제','7월말~12월초','부산시 해운대구 송정동 송정해수욕장','무료','051-501-6055','http://www.bfo.or.kr/main/index.asp',35.17827,129.199126,'타오르는 태양, 시원한 바다, 금빛 백사장, 화려한 네온사인, 신나는 음악을 한 번에 즐기는 여름축제',1016);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('부산불꽃축제','11월','부산시 수영구 광안해변로 219','무료 (유료좌석 구매별도)','051-501-6051','http://www.bfo.or.kr',35.1537821,129.1185399,'바다가 멀리 보이는 광안리 해변에서 화려한 불꽃이 꽃피면 사람들의 이목이 하늘의 불꽃에 쏠린다',1017);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('부산원아시아페스티벌','10월 말','부산시 연제구 월드컵대로 344','무료','051-780-4144','http://bof.or.kr',35.1899786,129.0582686,'부산과 세계의 젊은이들이 함께하는 아시아 대표 문화 콘텐츠, 세계 최고의 케이팝 콘서트',1018);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('부산자갈치축제','10월','부산시 중구 자갈치해안로 52','무료','051-245-2594','-',35.0966394,129.0305933,'매년 10월, 자갈치시장에서 싱싱한 해산물과 함께 바다의 정기를 느낄 수 있는 축제가 열린다',1019);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('부산차이나타운축제','10월 중순','부산시 동구 대영로243번길 43','무료','051-440-4062','http://www.bsdonggu.go.kr/tour/',35.1142633,129.0380202,' 차이나타운에서 중국 전통 의상을 입고 펼치는 무예, 무용을 만나는 화려한 거리퍼레이드가 열린다',1020);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('부산푸드필름페스타','7월 초','부산시 해운대구 수영강변대로 120 영화의전당','유료','051-780-6000','https://www.dureraum.org/bcc/main/main.do?rbsIdx=1',35.171074,129.126709,'영화와 함께 음식으로 다양한 푸드콘텐츠를 즐기는, 온 가족이 함께하는 맛있는 영화 축제',1021);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('사상강변축제','3월','부산시 사상구 삼락동','무료','051-316-9111','https://sasangfestival.or.kr/notice',35.1687484,128.9735403,'푸른 낙동강변, 천혜의 자연환경을 가진 삼락생태공원에서 펼쳐지는 문화의 향연',1023);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('삼광사연등축제','매년 4월 초','부산시 부산진구 초읍천로43번길 77','무료','051-808-7111','http://www.samkwangsa.or.kr/',35.1754288,129.0433882,'백양산 잘가을 수놓는 수 만개의 연등. 오색찬란 연등터널이 삼광사를 뒤덮으며 환하게 밝힌다',1024);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('삼락벚꽃축제','3월','부산시 사상구 삼락동','무료','051-310-3002','https://www.sasang.go.kr/index.sasang?menuCd=DOM_000000604002000000',35.1687484,128.9735403,'삼락벚꽃축제가 시작되면 만개한 벚꽃이 12킬로미터의 터널을 만들어주는 몽환의 순간이 열린다',1025);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('조선통신사축제','매년 5월 초','부산시 중구 용두산길 37-55 용두산 공원','무료','051-631-0858','http://www.tongsinsa.com/',35.1006536,129.0326226,'추위가 가신 완연한 부산의 봄날의 행렬, 용두산 공원에서 펼쳐지는 한일 양국에서 피어나는 봄꽃',1026);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('크리스마스트리문화축제','12월~1월','부산시 중구 광복로 58-2','무료','051-243-3927','-',35.0990683,129.031487,'다양한 크기와 모양을 가진 트리가 광복로를 화려하게 수놓으며 매일 밤 화려한 공연이 열린다',1027);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('태종대수국축제','6월','부산시 영도구 전망로 119','무료','051-405-4848','https://www.bisco.or.kr/taejongdae/facil/facil03/facil03_1/index.asp',35.056739,129.086336,'본격적인 휴가철이 시작되기 전 초여름, 태종대에서 만나는 오색찬란한 수국의 매력',1028);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('해운대달맞이온천축제','2월','부산시 해운대구 중동','무료','051-749-4062','-',35.1582327,129.1615639,'매년 정월대보름날에 경이로운 월출을 맞이하는 해운대달맞이온천축제가 열린다',1029);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('해운대모래축제','매년 5월','부산시 해운대구 우동 해운대해수욕장','무료','051-749-4062','http://www.haeundae.go.kr/tour/index.do',35.158697,129.1603842,'모래의 변신은 예술. 해운대 백사장 위에서 세계적인 작가의 모래조각 작품이 펼쳐진다',1030);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('해운대북극곰축제','1월','부산시 해운대구 중동','10000원','051-731-1509','http://bear.busan.com/',35.1582327,129.1615639,'영하의 날씨에도 두려움 없이 바다로 뛰어드는 용감한 사람들을 위한 이색 스포츠 체험',1031);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('해운대빛축제','2월','부산시 해운대구 중동','무료','051-749-4061','http://www.haeundae.go.kr',35.1582327,129.1615639,'해운대빛축제가 시작되면 해운대 밤바다는 아름다운 빛의 바다로 가득 매워진다',1032);
Insert into PROJECT.ALLFS (A_NAME,A_DATE,A_ADDRESS,A_FEE,A_TEL,A_HP,A_LATITUDE,A_LONGITUDE,A_INTRO,A_CODE) values ('부산항축제','7월 초','부산시 동구 초량3동 충장대로 206(부산항국제여객터미널)','무료','051-501-6051','http://www.bfo.or.kr',35.1173881,129.0487465,'해양과 항만에 관한 모든 이야기를 즐기고 배우는 체험형 항만축제',1022);
--------------------------------------------------------
--  DDL for Index ALLFS_PK
--------------------------------------------------------

  CREATE UNIQUE INDEX "PROJECT"."ALLFS_PK" ON "PROJECT"."ALLFS" ("A_CODE") 
  PCTFREE 10 INITRANS 2 MAXTRANS 255 COMPUTE STATISTICS 
  STORAGE(INITIAL 65536 NEXT 1048576 MINEXTENTS 1 MAXEXTENTS 2147483645
  PCTINCREASE 0 FREELISTS 1 FREELIST GROUPS 1
  BUFFER_POOL DEFAULT FLASH_CACHE DEFAULT CELL_FLASH_CACHE DEFAULT)
  TABLESPACE "USERS" ;
????????????????????????????
????????????????????????????  Constraints for Table ALLFS
????????????????????????????

  ALTER TABLE "PROJECT"."ALLFS" MODIFY ("A_ADDRESS" NOT NULL ENABLE);
  ALTER TABLE "PROJECT"."ALLFS" MODIFY ("A_LATITUDE" NOT NULL ENABLE);
  ALTER TABLE "PROJECT"."ALLFS" MODIFY ("A_LONGITUDE" NOT NULL ENABLE);
  ALTER TABLE "PROJECT"."ALLFS" MODIFY ("A_CODE" NOT NULL ENABLE);
  ALTER TABLE "PROJECT"."ALLFS" ADD CONSTRAINT "ALLFS_PK" PRIMARY KEY ("A_CODE")
  USING INDEX PCTFREE 10 INITRANS 2 MAXTRANS 255 COMPUTE STATISTICS 
  STORAGE(INITIAL 65536 NEXT 1048576 MINEXTENTS 1 MAXEXTENTS 2147483645
  PCTINCREASE 0 FREELISTS 1 FREELIST GROUPS 1
  BUFFER_POOL DEFAULT FLASH_CACHE DEFAULT CELL_FLASH_CACHE DEFAULT)
  TABLESPACE "USERS"  ENABLE;
  
  
  
  --------------------------------------------------------
--  파일이 생성됨 - 일요일-1월-29-2023   
--------------------------------------------------------
--------------------------------------------------------
--  DDL for Table BOARD
--------------------------------------------------------

  CREATE TABLE "PROJECT"."BOARD" 
   (	"IDX" NUMBER(5,0), 
	"MENU_ID" VARCHAR2(6 BYTE), 
	"TITLE" VARCHAR2(300 BYTE), 
	"CONT" VARCHAR2(4000 BYTE), 
	"WRITER" VARCHAR2(50 BYTE), 
	"REGDATE" DATE DEFAULT SYSDATE, 
	"READCOUNT" NUMBER(6,0) DEFAULT 0, 
	"BNUM" NUMBER(5,0) DEFAULT 0, 
	"LVL" NUMBER(5,0) DEFAULT 0, 
	"STEP" NUMBER(5,0) DEFAULT 0, 
	"NREF" NUMBER(5,0) DEFAULT 0
   ) SEGMENT CREATION IMMEDIATE 
  PCTFREE 10 PCTUSED 40 INITRANS 1 MAXTRANS 255 
 NOCOMPRESS LOGGING
  STORAGE(INITIAL 65536 NEXT 1048576 MINEXTENTS 1 MAXEXTENTS 2147483645
  PCTINCREASE 0 FREELISTS 1 FREELIST GROUPS 1
  BUFFER_POOL DEFAULT FLASH_CACHE DEFAULT CELL_FLASH_CACHE DEFAULT)
  TABLESPACE "USERS" ;
REM INSERTING into PROJECT.BOARD
SET DEFINE OFF;
Insert into PROJECT.BOARD (IDX,MENU_ID,TITLE,CONT,WRITER,REGDATE,READCOUNT,BNUM,LVL,STEP,NREF) values (1,'MENU01','후기입니다.','해운대 너무 좋아요','admin',to_date('22/11/21','RR/MM/DD'),0,1,0,0,1);
Insert into PROJECT.BOARD (IDX,MENU_ID,TITLE,CONT,WRITER,REGDATE,READCOUNT,BNUM,LVL,STEP,NREF) values (2,'MENU02','공지사항','공지사항입니다.','admin',to_date('22/11/27','RR/MM/DD'),3,2,0,0,2);
--------------------------------------------------------
--  DDL for Index SYS_C008431
--------------------------------------------------------

  CREATE UNIQUE INDEX "PROJECT"."SYS_C008431" ON "PROJECT"."BOARD" ("IDX") 
  PCTFREE 10 INITRANS 2 MAXTRANS 255 COMPUTE STATISTICS 
  STORAGE(INITIAL 65536 NEXT 1048576 MINEXTENTS 1 MAXEXTENTS 2147483645
  PCTINCREASE 0 FREELISTS 1 FREELIST GROUPS 1
  BUFFER_POOL DEFAULT FLASH_CACHE DEFAULT CELL_FLASH_CACHE DEFAULT)
  TABLESPACE "USERS" ;
????????????????????????????
????????????????????????????  Constraints for Table BOARD
????????????????????????????

  ALTER TABLE "PROJECT"."BOARD" MODIFY ("MENU_ID" NOT NULL ENABLE);
  ALTER TABLE "PROJECT"."BOARD" MODIFY ("TITLE" NOT NULL ENABLE);
  ALTER TABLE "PROJECT"."BOARD" ADD PRIMARY KEY ("IDX")
  USING INDEX PCTFREE 10 INITRANS 2 MAXTRANS 255 COMPUTE STATISTICS 
  STORAGE(INITIAL 65536 NEXT 1048576 MINEXTENTS 1 MAXEXTENTS 2147483645
  PCTINCREASE 0 FREELISTS 1 FREELIST GROUPS 1
  BUFFER_POOL DEFAULT FLASH_CACHE DEFAULT CELL_FLASH_CACHE DEFAULT)
  TABLESPACE "USERS"  ENABLE;
????????????????????????????
????????????????????????????  Ref Constraints for Table BOARD
????????????????????????????

  ALTER TABLE "PROJECT"."BOARD" ADD FOREIGN KEY ("MENU_ID")
	  REFERENCES "PROJECT"."MENUS" ("MENU_ID") ENABLE;
-------------------------------------------------------------------------------------------





--------------------------------------------------------
--  파일이 생성됨 - 일요일-1월-29-2023   
--------------------------------------------------------
--------------------------------------------------------
--  DDL for Table FESTIVAL
--------------------------------------------------------

  CREATE TABLE "PROJECT"."FESTIVAL" 
   (	"F_CODE" NUMBER(6,0), 
	"F_NAME" VARCHAR2(80 BYTE), 
	"F_DATE" VARCHAR2(50 BYTE), 
	"F_ADDRESS" VARCHAR2(200 BYTE), 
	"F_FEE" VARCHAR2(100 BYTE), 
	"F_TEL" VARCHAR2(20 BYTE), 
	"F_HP" VARCHAR2(300 BYTE), 
	"F_LATITUDE" FLOAT(126), 
	"F_LONGITUDE" FLOAT(126), 
	"F_THEME" VARCHAR2(50 BYTE), 
	"F_GOOD" NUMBER(38,0), 
	"F_INTRO" VARCHAR2(4000 BYTE)
   ) SEGMENT CREATION IMMEDIATE 
  PCTFREE 10 PCTUSED 40 INITRANS 1 MAXTRANS 255 
 NOCOMPRESS LOGGING
  STORAGE(INITIAL 65536 NEXT 1048576 MINEXTENTS 1 MAXEXTENTS 2147483645
  PCTINCREASE 0 FREELISTS 1 FREELIST GROUPS 1
  BUFFER_POOL DEFAULT FLASH_CACHE DEFAULT CELL_FLASH_CACHE DEFAULT)
  TABLESPACE "USERS" ;
REM INSERTING into PROJECT.FESTIVAL
SET DEFINE OFF;
Insert into PROJECT.FESTIVAL (F_CODE,F_NAME,F_DATE,F_ADDRESS,F_FEE,F_TEL,F_HP,F_LATITUDE,F_LONGITUDE,F_THEME,F_GOOD,F_INTRO) values (1013,'부산바다축제','7월말~9월초','부산시 수영구 광안동 광안리해수욕장','무료','051-501-6052','http://www.bfo.or.kr/main/index.asp',35.152502,129.118065,'축제',null,'타오르는 태양, 시원한 바다, 금빛 백사장, 화려한 네온사인, 신나는 음악을 한 번에 즐기는 여름축제');
Insert into PROJECT.FESTIVAL (F_CODE,F_NAME,F_DATE,F_ADDRESS,F_FEE,F_TEL,F_HP,F_LATITUDE,F_LONGITUDE,F_THEME,F_GOOD,F_INTRO) values (1014,'부산바다축제','7월말~10월초','부산시 사하구 다대동 다대포해수욕장','무료','051-501-6053','http://www.bfo.or.kr/main/index.asp',35.046338,128.967912,'축제',null,'타오르는 태양, 시원한 바다, 금빛 백사장, 화려한 네온사인, 신나는 음악을 한 번에 즐기는 여름축제');
Insert into PROJECT.FESTIVAL (F_CODE,F_NAME,F_DATE,F_ADDRESS,F_FEE,F_TEL,F_HP,F_LATITUDE,F_LONGITUDE,F_THEME,F_GOOD,F_INTRO) values (1015,'부산바다축제','7월말~11월초','부산시 서구 암남동 송도해수욕장','무료','051-501-6054','http://www.bfo.or.kr/main/index.asp',35.076122,129.017298,'축제',null,'타오르는 태양, 시원한 바다, 금빛 백사장, 화려한 네온사인, 신나는 음악을 한 번에 즐기는 여름축제');
Insert into PROJECT.FESTIVAL (F_CODE,F_NAME,F_DATE,F_ADDRESS,F_FEE,F_TEL,F_HP,F_LATITUDE,F_LONGITUDE,F_THEME,F_GOOD,F_INTRO) values (1016,'부산바다축제','7월말~12월초','부산시 해운대구 송정동 송정해수욕장','무료','051-501-6055','http://www.bfo.or.kr/main/index.asp',35.17827,129.199126,'축제',null,'타오르는 태양, 시원한 바다, 금빛 백사장, 화려한 네온사인, 신나는 음악을 한 번에 즐기는 여름축제');
Insert into PROJECT.FESTIVAL (F_CODE,F_NAME,F_DATE,F_ADDRESS,F_FEE,F_TEL,F_HP,F_LATITUDE,F_LONGITUDE,F_THEME,F_GOOD,F_INTRO) values (1017,'부산불꽃축제','11월','부산시 수영구 광안해변로 219','무료 (유료좌석 구매별도)','051-501-6051','http://www.bfo.or.kr',35.1537821,129.1185399,'축제',null,'바다가 멀리 보이는 광안리 해변에서 화려한 불꽃이 꽃피면 사람들의 이목이 하늘의 불꽃에 쏠린다');
Insert into PROJECT.FESTIVAL (F_CODE,F_NAME,F_DATE,F_ADDRESS,F_FEE,F_TEL,F_HP,F_LATITUDE,F_LONGITUDE,F_THEME,F_GOOD,F_INTRO) values (1018,'부산원아시아페스티벌','10월 말','부산시 연제구 월드컵대로 344','무료','051-780-4144','http://bof.or.kr',35.1899786,129.0582686,'축제',null,'부산과 세계의 젊은이들이 함께하는 아시아 대표 문화 콘텐츠, 세계 최고의 케이팝 콘서트');
Insert into PROJECT.FESTIVAL (F_CODE,F_NAME,F_DATE,F_ADDRESS,F_FEE,F_TEL,F_HP,F_LATITUDE,F_LONGITUDE,F_THEME,F_GOOD,F_INTRO) values (1019,'부산자갈치축제','10월','부산시 중구 자갈치해안로 52','무료','051-245-2594','-',35.0966394,129.0305933,'축제',null,'매년 10월, 자갈치시장에서 싱싱한 해산물과 함께 바다의 정기를 느낄 수 있는 축제가 열린다');
Insert into PROJECT.FESTIVAL (F_CODE,F_NAME,F_DATE,F_ADDRESS,F_FEE,F_TEL,F_HP,F_LATITUDE,F_LONGITUDE,F_THEME,F_GOOD,F_INTRO) values (1020,'부산차이나타운축제','10월 중순','부산시 동구 대영로243번길 43','무료','051-440-4062','http://www.bsdonggu.go.kr/tour/',35.1142633,129.0380202,'축제',null,' 차이나타운에서 중국 전통 의상을 입고 펼치는 무예, 무용을 만나는 화려한 거리퍼레이드가 열린다');
Insert into PROJECT.FESTIVAL (F_CODE,F_NAME,F_DATE,F_ADDRESS,F_FEE,F_TEL,F_HP,F_LATITUDE,F_LONGITUDE,F_THEME,F_GOOD,F_INTRO) values (1021,'부산푸드필름페스타','7월 초','부산시 해운대구 수영강변대로 120 영화의전당','유료','051-780-6000','https://www.dureraum.org/bcc/main/main.do?rbsIdx=1',35.171074,129.126709,'축제',null,'영화와 함께 음식으로 다양한 푸드콘텐츠를 즐기는, 온 가족이 함께하는 맛있는 영화 축제');
Insert into PROJECT.FESTIVAL (F_CODE,F_NAME,F_DATE,F_ADDRESS,F_FEE,F_TEL,F_HP,F_LATITUDE,F_LONGITUDE,F_THEME,F_GOOD,F_INTRO) values (1022,'부산항축제','7월 초','부산시 동구 초량3동 충장대로 206(부산항국제여객터미널)','무료','051-501-6051','http://www.bfo.or.kr',35.1173881,129.0487465,'축제',null,'해양과 항만에 관한 모든 이야기를 즐기고 배우는 체험형 항만축제');
Insert into PROJECT.FESTIVAL (F_CODE,F_NAME,F_DATE,F_ADDRESS,F_FEE,F_TEL,F_HP,F_LATITUDE,F_LONGITUDE,F_THEME,F_GOOD,F_INTRO) values (1023,'사상강변축제','3월','부산시 사상구 삼락동','무료','051-316-9111','https://sasangfestival.or.kr/notice',35.1687484,128.9735403,'축제',null,'푸른 낙동강변, 천혜의 자연환경을 가진 삼락생태공원에서 펼쳐지는 문화의 향연');
Insert into PROJECT.FESTIVAL (F_CODE,F_NAME,F_DATE,F_ADDRESS,F_FEE,F_TEL,F_HP,F_LATITUDE,F_LONGITUDE,F_THEME,F_GOOD,F_INTRO) values (1024,'삼광사연등축제','매년 4월 초','부산시 부산진구 초읍천로43번길 77','무료','051-808-7111','http://www.samkwangsa.or.kr/',35.1754288,129.0433882,'축제',null,'백양산 잘가을 수놓는 수 만개의 연등. 오색찬란 연등터널이 삼광사를 뒤덮으며 환하게 밝힌다');
Insert into PROJECT.FESTIVAL (F_CODE,F_NAME,F_DATE,F_ADDRESS,F_FEE,F_TEL,F_HP,F_LATITUDE,F_LONGITUDE,F_THEME,F_GOOD,F_INTRO) values (1025,'삼락벚꽃축제','3월','부산시 사상구 삼락동','무료','051-310-3002','https://www.sasang.go.kr/index.sasang?menuCd=DOM_000000604002000000',35.1687484,128.9735403,'축제',null,'삼락벚꽃축제가 시작되면 만개한 벚꽃이 12킬로미터의 터널을 만들어주는 몽환의 순간이 열린다');
Insert into PROJECT.FESTIVAL (F_CODE,F_NAME,F_DATE,F_ADDRESS,F_FEE,F_TEL,F_HP,F_LATITUDE,F_LONGITUDE,F_THEME,F_GOOD,F_INTRO) values (1026,'조선통신사축제','매년 5월 초','부산시 중구 용두산길 37-55 용두산 공원','무료','051-631-0858','http://www.tongsinsa.com/',35.1006536,129.0326226,'축제',null,'추위가 가신 완연한 부산의 봄날의 행렬, 용두산 공원에서 펼쳐지는 한일 양국에서 피어나는 봄꽃');
Insert into PROJECT.FESTIVAL (F_CODE,F_NAME,F_DATE,F_ADDRESS,F_FEE,F_TEL,F_HP,F_LATITUDE,F_LONGITUDE,F_THEME,F_GOOD,F_INTRO) values (1027,'크리스마스트리문화축제','12월~1월','부산시 중구 광복로 58-2','무료','051-243-3927','-',35.0990683,129.031487,'축제',null,'다양한 크기와 모양을 가진 트리가 광복로를 화려하게 수놓으며 매일 밤 화려한 공연이 열린다');
Insert into PROJECT.FESTIVAL (F_CODE,F_NAME,F_DATE,F_ADDRESS,F_FEE,F_TEL,F_HP,F_LATITUDE,F_LONGITUDE,F_THEME,F_GOOD,F_INTRO) values (1028,'태종대수국축제','6월','부산시 영도구 전망로 119','무료','051-405-4848','https://www.bisco.or.kr/taejongdae/facil/facil03/facil03_1/index.asp',35.056739,129.086336,'축제',null,'본격적인 휴가철이 시작되기 전 초여름, 태종대에서 만나는 오색찬란한 수국의 매력');
Insert into PROJECT.FESTIVAL (F_CODE,F_NAME,F_DATE,F_ADDRESS,F_FEE,F_TEL,F_HP,F_LATITUDE,F_LONGITUDE,F_THEME,F_GOOD,F_INTRO) values (1029,'해운대달맞이온천축제','2월','부산시 해운대구 중동','무료','051-749-4062','-',35.1582327,129.1615639,'축제',null,'매년 정월대보름날에 경이로운 월출을 맞이하는 해운대달맞이온천축제가 열린다');
Insert into PROJECT.FESTIVAL (F_CODE,F_NAME,F_DATE,F_ADDRESS,F_FEE,F_TEL,F_HP,F_LATITUDE,F_LONGITUDE,F_THEME,F_GOOD,F_INTRO) values (1030,'해운대모래축제','매년 5월','부산시 해운대구 우동 해운대해수욕장','무료','051-749-4062','http://www.haeundae.go.kr/tour/index.do',35.158697,129.1603842,'축제',null,'모래의 변신은 예술. 해운대 백사장 위에서 세계적인 작가의 모래조각 작품이 펼쳐진다');
Insert into PROJECT.FESTIVAL (F_CODE,F_NAME,F_DATE,F_ADDRESS,F_FEE,F_TEL,F_HP,F_LATITUDE,F_LONGITUDE,F_THEME,F_GOOD,F_INTRO) values (1031,'해운대북극곰축제','1월 ','부산시 해운대구 중동','10000원','051-731-1509','http://bear.busan.com/',35.1582327,129.1615639,'축제',null,'영하의 날씨에도 두려움 없이 바다로 뛰어드는 용감한 사람들을 위한 이색 스포츠 체험');
Insert into PROJECT.FESTIVAL (F_CODE,F_NAME,F_DATE,F_ADDRESS,F_FEE,F_TEL,F_HP,F_LATITUDE,F_LONGITUDE,F_THEME,F_GOOD,F_INTRO) values (1032,'해운대빛축제','2월','부산시 해운대구 중동','무료','051-749-4061','http://www.haeundae.go.kr',35.1582327,129.1615639,'축제',null,'해운대빛축제가 시작되면 해운대 밤바다는 아름다운 빛의 바다로 가득 매워진다');
Insert into PROJECT.FESTIVAL (F_CODE,F_NAME,F_DATE,F_ADDRESS,F_FEE,F_TEL,F_HP,F_LATITUDE,F_LONGITUDE,F_THEME,F_GOOD,F_INTRO) values (1006,'낙동강구포나루축제','10월 중','부산시 북구 낙동대로1739번길 257 화명생태공원 선착장','무료','051-309-4980','http://guponarufes.co.kr/',35.220095,128.9994207,'축제',null,'싱그러운 봄. 솔솔 부는 강바람에 정겨운 북적거림이 실려오는 구포나루의 추억과 낭만');
Insert into PROJECT.FESTIVAL (F_CODE,F_NAME,F_DATE,F_ADDRESS,F_FEE,F_TEL,F_HP,F_LATITUDE,F_LONGITUDE,F_THEME,F_GOOD,F_INTRO) values (1007,'낙동강유채꽃축제','매년 4월','부산시 강서구 대저생태공원','무료','051-501-6051','http://www.bfo.or.kr/',35.2048909,128.982775,'축제',null,'유채꽃 향기가 가득한 대저생태공원에서 펼쳐지는 샛노란 봄날의 유혹');
Insert into PROJECT.FESTIVAL (F_CODE,F_NAME,F_DATE,F_ADDRESS,F_FEE,F_TEL,F_HP,F_LATITUDE,F_LONGITUDE,F_THEME,F_GOOD,F_INTRO) values (1008,'대저토마토축제','매년 4월','부산시 강서구 체육공원로 43(강서체육공원)','무료','051-970-4812','https://www.bsgangseo.go.kr/visit/contents.do?mId=0305000000',35.209882,128.972345,'축제',null,'4월이 시작되면 열리는 빨간 토마토의 향연. 몸에 좋고 맛도 좋은 토마토를 즐기는 대저토마토축제');
Insert into PROJECT.FESTIVAL (F_CODE,F_NAME,F_DATE,F_ADDRESS,F_FEE,F_TEL,F_HP,F_LATITUDE,F_LONGITUDE,F_THEME,F_GOOD,F_INTRO) values (1009,'동래읍성역사축제','10월','부산시 동래구 문화로 80','무료(일부 체험 유료)','051-550-4000','https://www.dongnae.go.kr/festival/index.dongnae?contentsSid=169 ',35.2118622,129.0899982,'축제',null,'청명한 가을에 만나는 동래읍성 역사축제가 시작되면 부산은 1592년의 그 때로 돌아간다');
Insert into PROJECT.FESTIVAL (F_CODE,F_NAME,F_DATE,F_ADDRESS,F_FEE,F_TEL,F_HP,F_LATITUDE,F_LONGITUDE,F_THEME,F_GOOD,F_INTRO) values (1010,'부산국제영화제','10월','부산시 해운대구 수영강변대로 120(영화의 전당)','일반상영작 8,000원, 행사 및 체험 일부 무료','1688-3010','https://www.biff.kr/kor/',35.1711778,129.1271956,'축제',null,'10월이 되면 아시아를 대표하는 영화제와 함께 부산은 영화의 바다에 빠져든다');
Insert into PROJECT.FESTIVAL (F_CODE,F_NAME,F_DATE,F_ADDRESS,F_FEE,F_TEL,F_HP,F_LATITUDE,F_LONGITUDE,F_THEME,F_GOOD,F_INTRO) values (1011,'부산바다미술제','10월','부산시 사하구 몰운대1길 14','무료','051-503-6111','http://www.busanbiennale.org/intro.html',35.0457857,128.968704,'축제',null,'자연 그대로의 바다를 간직한 다대포 해수욕장에서 예술전시물들로 예술의 향기 속에 빠져 보자');
Insert into PROJECT.FESTIVAL (F_CODE,F_NAME,F_DATE,F_ADDRESS,F_FEE,F_TEL,F_HP,F_LATITUDE,F_LONGITUDE,F_THEME,F_GOOD,F_INTRO) values (1012,'부산바다축제','7월말~8월초','부산시 해운대구 해운대 해수욕장','무료','051-501-6051','http://www.bfo.or.kr/main/index.asp',35.158367,129.159007,'축제',null,'타오르는 태양, 시원한 바다, 금빛 백사장, 화려한 네온사인, 신나는 음악을 한 번에 즐기는 여름축제');
Insert into PROJECT.FESTIVAL (F_CODE,F_NAME,F_DATE,F_ADDRESS,F_FEE,F_TEL,F_HP,F_LATITUDE,F_LONGITUDE,F_THEME,F_GOOD,F_INTRO) values (1001,'감천문화마을골목축제','매년 4월 말','부산시 사하구 감내2로 203','무료','051-220-5911','https://www.gamcheon.or.kr/',35.0961559,129.0089071,'축제',null,'흥이 넘쳐나는 감천골. 전쟁의 상흔을 딛고 보존과 재생의 마을에서 다니는 미로 골목길 투어');
Insert into PROJECT.FESTIVAL (F_CODE,F_NAME,F_DATE,F_ADDRESS,F_FEE,F_TEL,F_HP,F_LATITUDE,F_LONGITUDE,F_THEME,F_GOOD,F_INTRO) values (1002,'광안리어방축제','10월 중순','부산시 수영구 광안해변로 219','무료','051-610-4062','http://www.suyeong.go.kr/eobang',35.1537821,129.1185399,'축제',null,'매년 4월, 어업협동체 어방의 전통을 이어가는 어방축제가 광연대교를 배경으로 화려한 막을 연다');
Insert into PROJECT.FESTIVAL (F_CODE,F_NAME,F_DATE,F_ADDRESS,F_FEE,F_TEL,F_HP,F_LATITUDE,F_LONGITUDE,F_THEME,F_GOOD,F_INTRO) values (1003,'금정산성축제','매년 10월 말','부산시 금정구 장전온천천로 144','무료','051-512-3455','https://blog.naver.com/geumjeonggu/222904230446',35.2755,129.0575042,'축제',null,'금정산성과 녹음이 우거진 마을에서 호패 하나 손에 쥐고 떠나는 오감만족 역사문화여행');
Insert into PROJECT.FESTIVAL (F_CODE,F_NAME,F_DATE,F_ADDRESS,F_FEE,F_TEL,F_HP,F_LATITUDE,F_LONGITUDE,F_THEME,F_GOOD,F_INTRO) values (1004,'기장멸치축제','매년 4월','부산시 기장군 기장읍 대변항 일원','무료','051-709-4502','http://www.gijang.go.kr/tour/index.gijang',35.2247703,129.2301119,'축제',null,'풍요로운 봄바람, 기장의 앞바다. 오동통통 살이 오른 신선한 기장멸치를 즐긴다');
Insert into PROJECT.FESTIVAL (F_CODE,F_NAME,F_DATE,F_ADDRESS,F_FEE,F_TEL,F_HP,F_LATITUDE,F_LONGITUDE,F_THEME,F_GOOD,F_INTRO) values (1005,'기장미역다시마축제','매년 4월','부산시 기장군 일광면 이동길 43','무료','051-709-4000','http://www.gijang.go.kr/tour/index.gijang',35.2722418,129.245967,'축제',null,'기장 앞바다의 봄은 수확의 계절. 기장 이동항에서 열리는 미역과 다시마의 먹거리 천국');
--------------------------------------------------------
--  DDL for Index SYS_C008403
--------------------------------------------------------

  CREATE UNIQUE INDEX "PROJECT"."SYS_C008403" ON "PROJECT"."FESTIVAL" ("F_CODE") 
  PCTFREE 10 INITRANS 2 MAXTRANS 255 COMPUTE STATISTICS 
  STORAGE(INITIAL 65536 NEXT 1048576 MINEXTENTS 1 MAXEXTENTS 2147483645
  PCTINCREASE 0 FREELISTS 1 FREELIST GROUPS 1
  BUFFER_POOL DEFAULT FLASH_CACHE DEFAULT CELL_FLASH_CACHE DEFAULT)
  TABLESPACE "USERS" ;
--------------------------------------------------------
--  Constraints for Table FESTIVAL
--------------------------------------------------------

  ALTER TABLE "PROJECT"."FESTIVAL" MODIFY ("F_NAME" NOT NULL ENABLE);
  ALTER TABLE "PROJECT"."FESTIVAL" MODIFY ("F_ADDRESS" NOT NULL ENABLE);
  ALTER TABLE "PROJECT"."FESTIVAL" MODIFY ("F_LATITUDE" NOT NULL ENABLE);
  ALTER TABLE "PROJECT"."FESTIVAL" MODIFY ("F_LONGITUDE" NOT NULL ENABLE);
  ALTER TABLE "PROJECT"."FESTIVAL" MODIFY ("F_THEME" NOT NULL ENABLE);
  ALTER TABLE "PROJECT"."FESTIVAL" ADD PRIMARY KEY ("F_CODE")
  USING INDEX PCTFREE 10 INITRANS 2 MAXTRANS 255 COMPUTE STATISTICS 
  STORAGE(INITIAL 65536 NEXT 1048576 MINEXTENTS 1 MAXEXTENTS 2147483645
  PCTINCREASE 0 FREELISTS 1 FREELIST GROUPS 1
  BUFFER_POOL DEFAULT FLASH_CACHE DEFAULT CELL_FLASH_CACHE DEFAULT)
  TABLESPACE "USERS"  ENABLE;
????????????????????????????
????????????????????????????  Ref Constraints for Table FESTIVAL
????????????????????????????

  ALTER TABLE "PROJECT"."FESTIVAL" ADD CONSTRAINT "FESTIVAL_FK1" FOREIGN KEY ("F_CODE")
	  REFERENCES "PROJECT"."ALLFS" ("A_CODE") ENABLE;
--------------------------------------------------------------------------------





--------------------------------------------------------
--  파일이 생성됨 - 일요일-1월-29-2023   
--------------------------------------------------------
--------------------------------------------------------
--  DDL for Table IMAGE
--------------------------------------------------------

  CREATE TABLE "PROJECT"."IMAGE" 
   (	"I_CODE" NUMBER(6,0), 
	"SIG_SCODE" NUMBER(6,0), 
	"FES_FCODE" NUMBER(6,0), 
	"I_ADDRESS" VARCHAR2(200 BYTE), 
	"I_ALT" VARCHAR2(200 BYTE), 
	"I_LATITUDE" FLOAT(126), 
	"I_LONGITUDE" FLOAT(126)
   ) SEGMENT CREATION IMMEDIATE 
  PCTFREE 10 PCTUSED 40 INITRANS 1 MAXTRANS 255 
 NOCOMPRESS LOGGING
  STORAGE(INITIAL 65536 NEXT 1048576 MINEXTENTS 1 MAXEXTENTS 2147483645
  PCTINCREASE 0 FREELISTS 1 FREELIST GROUPS 1
  BUFFER_POOL DEFAULT FLASH_CACHE DEFAULT CELL_FLASH_CACHE DEFAULT)
  TABLESPACE "USERS" ;
REM INSERTING into PROJECT.IMAGE
SET DEFINE OFF;
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (1001,null,1001,'festival\감천문화마을골목축제.jpg','감천문화마을골목축제',35.0961559,129.0089071);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (1002,null,1002,'festival\광안리어방축제.jpg','광안리어방축제',35.1537821,129.1185399);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (1003,null,1003,'festival\금정산성축제.jpg','금정산성축제',35.2755,129.0575042);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (1004,null,1004,'festival\기장멸치축제.jpg','기장멸치축제',35.2247703,129.2301119);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (1005,null,1005,'festival\기장미역다시마축제.jpg','기장미역다시마축제',35.2722418,129.245967);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (1006,null,1006,'festival\낙동강구포나루축제.jpg','낙동강구포나루축제',35.220095,128.9994207);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (1007,null,1007,'festival\낙동강유채꽃축제.jpg','낙동강유채꽃축제',35.2048909,128.982775);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (1008,null,1008,'festival\대저토마토축제.jpg','대저토마토축제',35.209882,128.972345);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (1009,null,1009,'festival\동래읍성역사축제.jpg','동래읍성역사축제',35.2118622,129.0899982);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (1010,null,1010,'festival\부산국제영화제.jpg','부산국제영화제',35.1711778,129.1271956);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (1011,null,1011,'festival\부산바다미술제.jpg','부산바다미술제',35.0457857,128.968704);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (1012,null,1012,'festival\부산바다축제.jpg','부산바다축제',35.158367,129.159007);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (1013,null,1013,'festival\부산바다축제.jpg','부산바다축제',35.152502,129.118065);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (1014,null,1014,'festival\부산바다축제.jpg','부산바다축제',35.046338,128.967912);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (1015,null,1015,'festival\부산바다축제.jpg','부산바다축제',35.076122,129.017298);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (1016,null,1016,'festival\부산바다축제.jpg','부산바다축제',35.17827,129.199126);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (1017,null,1017,'festival\부산불꽃축제.jpg','부산불꽃축제',35.1537821,129.1185399);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (1018,null,1018,'festival\부산원아시아페스티벌.jpg','부산원아시아페스티벌',35.1899786,129.0582686);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (1019,null,1019,'festival\부산자갈치축제.jpg','부산자갈치축제',35.0966394,129.0305933);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (1020,null,1020,'festival\부산푸드필름페스타.jpg','부산푸드필름페스타',35.1142633,129.0380202);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (1021,null,1021,'festival\부산항축제.jpg','부산항축제',35.171074,129.126709);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (1022,null,1022,'festival\사상강변축제.jpg','사상강변축제',35.1173881,129.0487465);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (1023,null,1023,'festival\삼광사연등축제.jpg','삼광사연등축제',35.1687484,128.9735403);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (1024,null,1024,'festival\삼락벚꽃축제.jpg','삼락벚꽃축제',35.1754288,129.0433882);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (1025,null,1025,'festival\조선통신사축제.jpg','조선통신사축제',35.1687484,128.9735403);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (1026,null,1026,'festival\차이나타운축제.jpg','차이나타운축제',35.1006536,129.0326226);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (1027,null,1027,'festival\크리스마스트리문화축제.jpg','크리스마스트리문화축제',35.0990683,129.031487);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (1028,null,1028,'festival\태종대수국축제.jpg','태종대수국축제',35.056739,129.086336);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (1029,null,1029,'festival\해운대달맞이온천축제.jpg','해운대달맞이온천축제',35.1582327,129.1615639);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (1030,null,1030,'festival\해운대모래축제.jpg','해운대모래축제',35.158697,129.1603842);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (1031,null,1031,'festival\해운대북극곰축제.jpg','해운대북극곰축제',35.1582327,129.1615639);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (1032,null,1032,'festival\해운대빛축제.jpg','해운대빛축제',35.1582327,129.1615639);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6001,6001,null,'sight\40계단.jpg','40계단',35.1039739,129.0346464);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6002,6002,null,'sight\APEC나루공원.jpg','apec나루공원',35.1706486,129.1254273);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6003,6003,null,'sight\감천문화마을.jpg','감천문화마을',35.0973904,129.0105924);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6004,6004,null,'sight\광안리해수욕장.jpg','광안리해수욕장',35.152813,129.118218);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6005,6005,null,'sight\국립일제강제동원역사관.jpg','국립일제강제동원역사관',35.12499,129.092335);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6006,6006,null,'sight\국립해양박물관.jpg','국립해양박물관',35.0783256,129.0798565);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6007,6007,null,'sight\금강공원과 식물원.jpg','금강공원과식물원',35.2201331,129.0738073);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6008,6008,null,'sight\기장달음산자연휴향림.jpg','기장 달음산 자연휴향림',35.301617,129.185367);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6009,6009,null,'sight\기장도예관광힐링촌.jpg','기장도예관광 힐링촌',35.360046,129.239801);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6010,6010,null,'sight\다대포.jpg','다대포',35.046999,128.966551);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6011,6011,null,'sight\대신공원.jpg','대신공원',35.1211379,129.0167921);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6012,6012,null,'sight\동래읍성.jpg','동래읍성',35.2101539,129.0894131);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6013,6013,null,'sight\동아대학교석당박물관.jpg','동아대학교석당박물관',35.1042116,129.0191299);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6014,6014,null,'sight\민락수변공원.jpg','민락수변공원',35.1545716,129.1329907);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6015,6015,null,'sight\민주공원.jpg','민주공원',35.1100718,129.0280727);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6016,6016,null,'sight\백산기념관.jpg','백산기념관',35.1019518,129.0345919);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6017,6017,null,'sight\범어사.jpg','범어사',35.2839899,129.0687639);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6018,6018,null,'sight\벡스코.jpg','벡스코',35.1689766,129.1360411);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6019,6019,null,'sight\보수동책방골목.jpg','보수동책방골목',35.1031252,129.0274609);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6020,6020,null,'sight\복천박물관/복천동고분군.jpg','복천박물관/복천동고분군',35.2083599,129.0914505);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6021,6021,null,'sight\부산치유의숲.jpg','부산 치유의 숲',35.272772,129.137896);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6022,6022,null,'sight\부산근대역사관.jpg','부산근대문화역사관',35.1026721,129.031176);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6023,6023,null,'sight\부산도서관.jpg','부산도서관',35.172711,128.9853636);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6024,6024,null,'sight\부산박물관.jpg','부산박물관',35.1295178,129.094151);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6025,6025,null,'sight\부산시민공원.jpg','부산시민공원',35.1599375,129.1698125);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6026,6026,null,'sight\부산엑스더스카이전망대.jpg','부산엑스더스카이전망대',35.1034532,129.0174521);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6027,6027,null,'sight\부산임시수도기념관.jpg','부산임시수도기념관',35.1940316,129.0615183);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6028,6028,null,'sight\사직야구장.jpg','사직야구장',35.1687484,128.9735403);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6029,6029,null,'sight\삼락생태공원.jpg','삼락생태공원',35.061884,129.022211);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6030,6030,null,'sight\송도용궁구름다리.jpg','송도 용궁구름다리',35.076122,129.017298);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6031,6031,null,'sight\송도해수욕장.jpg','송도해수욕장',35.1641542,129.0648058);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6032,6032,null,'sight\송상현광장.jpg','송상현광장',35.17827,129.199126);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6033,6033,null,'sight\송정해수요장.jpg','송정해수욕장',35.1769907,129.1154605);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6034,6034,null,'sight\수영F1963.jpg','수영F1963',35.1710871,129.1139105);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6035,6035,null,'sight\수영사적공원.jpg','수영사적공원',35.1681608,129.0573853);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6036,6036,null,'sight\아미산전망대.jpg','아미산전망대',35.052544,128.960647);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6037,6037,null,'sight\어린이 대공원.jpg','어린이대공원',35.1846343,129.0434794);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6038,6038,null,'sight\영도대교.jpg','영도대교',35.0930473,129.0374683);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6039,6039,null,'sight\영화의거리.jpg','영화의거리',35.1547966,129.144653);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6040,6040,null,'sight\영화의전당.jpg','영화의전당',35.1711778,129.1271956);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6041,6041,null,'sight\오랑대공원.jpg','오랑대공원',35.2057006,129.2276931);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6042,6042,null,'sight\오륙도.jpg','오륙도',35.097635,129.120893);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6043,6043,null,'sight\용두산공원.jpg','용두산공원',35.1006536,129.0326226);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6044,6044,null,'sight\우암동소막마을.jpg','우암동소막마을',35.1249213,129.0743458);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6045,6045,null,'sight\유엔기념공원.jpg','유엔기념공원',35.1279039,129.0961877);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6046,6046,null,'sight\초량1941.jpg','초량1941',35.1198148,129.029509);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6047,6047,null,'sight\커피박물관.jpg','커피박물관',35.154865,129.062732);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6048,6048,null,'sight\태종대.jpg','태종대',35.046999,128.966551);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6049,6049,null,'sight\해동용궁사.jpg','해동용궁사',35.1883491,129.2233197);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6050,6050,null,'sight\해운대해수욕장.jpg','해운대해수욕장',35.158601,129.160001);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6051,6051,null,'sight\화명수목원.jpg','화명수목원',35.2510047,129.0427975);
Insert into PROJECT.IMAGE (I_CODE,SIG_SCODE,FES_FCODE,I_ADDRESS,I_ALT,I_LATITUDE,I_LONGITUDE) values (6052,6052,null,'sight\흰여울문화마을.jpg','흰여울문화마을',35.078255,129.045316);
--------------------------------------------------------
--  DDL for Index SYS_C008407
--------------------------------------------------------

  CREATE UNIQUE INDEX "PROJECT"."SYS_C008407" ON "PROJECT"."IMAGE" ("I_CODE") 
  PCTFREE 10 INITRANS 2 MAXTRANS 255 COMPUTE STATISTICS 
  STORAGE(INITIAL 65536 NEXT 1048576 MINEXTENTS 1 MAXEXTENTS 2147483645
  PCTINCREASE 0 FREELISTS 1 FREELIST GROUPS 1
  BUFFER_POOL DEFAULT FLASH_CACHE DEFAULT CELL_FLASH_CACHE DEFAULT)
  TABLESPACE "USERS" ;
--------------------------------------------------------
--  Constraints for Table IMAGE
--------------------------------------------------------

  ALTER TABLE "PROJECT"."IMAGE" MODIFY ("I_ADDRESS" NOT NULL ENABLE);
  ALTER TABLE "PROJECT"."IMAGE" MODIFY ("I_LATITUDE" NOT NULL ENABLE);
  ALTER TABLE "PROJECT"."IMAGE" MODIFY ("I_LONGITUDE" NOT NULL ENABLE);
  ALTER TABLE "PROJECT"."IMAGE" ADD PRIMARY KEY ("I_CODE")
  USING INDEX PCTFREE 10 INITRANS 2 MAXTRANS 255 COMPUTE STATISTICS 
  STORAGE(INITIAL 65536 NEXT 1048576 MINEXTENTS 1 MAXEXTENTS 2147483645
  PCTINCREASE 0 FREELISTS 1 FREELIST GROUPS 1
  BUFFER_POOL DEFAULT FLASH_CACHE DEFAULT CELL_FLASH_CACHE DEFAULT)
  TABLESPACE "USERS"  ENABLE;
????????????????????????????
????????????????????????????  Ref Constraints for Table IMAGE
????????????????????????????

  ALTER TABLE "PROJECT"."IMAGE" ADD FOREIGN KEY ("SIG_SCODE")
	  REFERENCES "PROJECT"."SIGHT" ("S_CODE") ENABLE;
  ALTER TABLE "PROJECT"."IMAGE" ADD FOREIGN KEY ("FES_FCODE")
	  REFERENCES "PROJECT"."FESTIVAL" ("F_CODE") ENABLE;

-------------------------------------------------------------------------------



--------------------------------------------------------
--  파일이 생성됨 - 일요일-1월-29-2023   
--------------------------------------------------------
--------------------------------------------------------
--  DDL for Table MENUS
--------------------------------------------------------

  CREATE TABLE "PROJECT"."MENUS" 
   (	"MENU_ID" VARCHAR2(6 BYTE), 
	"MENU_NAME" VARCHAR2(120 BYTE), 
	"MENU_SEQ" NUMBER(5,0)
   ) SEGMENT CREATION IMMEDIATE 
  PCTFREE 10 PCTUSED 40 INITRANS 1 MAXTRANS 255 
 NOCOMPRESS LOGGING
  STORAGE(INITIAL 65536 NEXT 1048576 MINEXTENTS 1 MAXEXTENTS 2147483645
  PCTINCREASE 0 FREELISTS 1 FREELIST GROUPS 1
  BUFFER_POOL DEFAULT FLASH_CACHE DEFAULT CELL_FLASH_CACHE DEFAULT)
  TABLESPACE "USERS" ;
REM INSERTING into PROJECT.MENUS
SET DEFINE OFF;
Insert into PROJECT.MENUS (MENU_ID,MENU_NAME,MENU_SEQ) values ('MENU01','명소',1);
Insert into PROJECT.MENUS (MENU_ID,MENU_NAME,MENU_SEQ) values ('MENU02','축제',2);
--------------------------------------------------------
--  DDL for Index SYS_C008428
--------------------------------------------------------

  CREATE UNIQUE INDEX "PROJECT"."SYS_C008428" ON "PROJECT"."MENUS" ("MENU_ID") 
  PCTFREE 10 INITRANS 2 MAXTRANS 255 COMPUTE STATISTICS 
  STORAGE(INITIAL 65536 NEXT 1048576 MINEXTENTS 1 MAXEXTENTS 2147483645
  PCTINCREASE 0 FREELISTS 1 FREELIST GROUPS 1
  BUFFER_POOL DEFAULT FLASH_CACHE DEFAULT CELL_FLASH_CACHE DEFAULT)
  TABLESPACE "USERS" ;
--------------------------------------------------------
--  Constraints for Table MENUS
--------------------------------------------------------

  ALTER TABLE "PROJECT"."MENUS" MODIFY ("MENU_ID" NOT NULL ENABLE);
  ALTER TABLE "PROJECT"."MENUS" MODIFY ("MENU_NAME" NOT NULL ENABLE);
  ALTER TABLE "PROJECT"."MENUS" MODIFY ("MENU_SEQ" NOT NULL ENABLE);
  ALTER TABLE "PROJECT"."MENUS" ADD PRIMARY KEY ("MENU_ID")
  USING INDEX PCTFREE 10 INITRANS 2 MAXTRANS 255 COMPUTE STATISTICS 
  STORAGE(INITIAL 65536 NEXT 1048576 MINEXTENTS 1 MAXEXTENTS 2147483645
  PCTINCREASE 0 FREELISTS 1 FREELIST GROUPS 1
  BUFFER_POOL DEFAULT FLASH_CACHE DEFAULT CELL_FLASH_CACHE DEFAULT)
  TABLESPACE "USERS"  ENABLE;

---------------------------------------------------------------------
\


--------------------------------------------------------
--  파일이 생성됨 - 일요일-1월-29-2023   
--------------------------------------------------------
--------------------------------------------------------
--  DDL for Table SIGHT
--------------------------------------------------------

  CREATE TABLE "PROJECT"."SIGHT" 
   (	"S_CODE" NUMBER(6,0), 
	"S_NAME" VARCHAR2(80 BYTE), 
	"S_DATE" VARCHAR2(50 BYTE), 
	"S_ADDRESS" VARCHAR2(200 BYTE), 
	"S_FEE" VARCHAR2(100 BYTE), 
	"S_TEL" VARCHAR2(20 BYTE), 
	"S_HP" VARCHAR2(300 BYTE), 
	"S_LATITUDE" FLOAT(126), 
	"S_LONGITUDE" FLOAT(126), 
	"S_THEME" VARCHAR2(50 BYTE), 
	"S_INTRO" VARCHAR2(4000 BYTE), 
	"S_GOOD" NUMBER(38,0)
   ) SEGMENT CREATION IMMEDIATE 
  PCTFREE 10 PCTUSED 40 INITRANS 1 MAXTRANS 255 
 NOCOMPRESS LOGGING
  STORAGE(INITIAL 65536 NEXT 1048576 MINEXTENTS 1 MAXEXTENTS 2147483645
  PCTINCREASE 0 FREELISTS 1 FREELIST GROUPS 1
  BUFFER_POOL DEFAULT FLASH_CACHE DEFAULT CELL_FLASH_CACHE DEFAULT)
  TABLESPACE "USERS" ;
REM INSERTING into PROJECT.SIGHT
SET DEFINE OFF;
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6001,'40계단','40계단 문화관 매주 월 휴무','부산시 중구 대청로135번길 13?','무료','051-600-4046','http://www.bsjunggu.go.kr/tour/index.junggu?menuCd=DOM_000000208001001000&link=success&cpath=%2Ftour',35.1039739,129.0346464,'역사','부산항 부두에서 고지대 판자촌으로 이어지는 길목. 피난민들의 애환이 스며든 생생한 삶의 현장',16);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6002,'apec나루공원','상시운영','부산시 해운대구 우동 1494(수영강변대로 93)','무료','051-749-4000','http://heundae.com/?site=apec-%EB%82%98%EB%A3%A8%EA%B3%B5%EC%9B%90',35.1706486,129.1254273,'공원','수영강변에 따라 뻗어 있는 도심 속 강바람을 느낄 수 있는 평화로운 작은 공원',2);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6003,'감천문화마을','09:00 ~18:00','부산시 사하구 감내2로 203','무료','051-204-1444','https://www.gamcheon.or.kr/',35.0973904,129.0105924,'문화','하늘에 닿을 것만 같은 형형색색의 지붕과 질서정연하게 늘어선 계단식 마을의 독특한 아름다움',1);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6004,'광안리해수욕장','상시운영','부산시 수영구 광안해변로 219','무료, 프로그램별 상이','051-622-4251','http://www.suyeong.go.kr/tour/index.suyeong',35.152813,129.118218,'자연','광안대교와 함께 부산을 대표하는 해수욕장. 도심과 가장 가까운 해변이자 젊은이들의 성지',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6005,'국립일제강제동원역사관','매주 월 휴무','부산시 남구 홍곡로320번길 100','무료','051-629-8600','https://www.fomo.or.kr/museum',35.12499,129.092335,'역사','식민지 조선의 아픈 역사와 일제의 강제동원 만행을 기록하기 위한 역사관',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6006,'국립해양박물관','매주 월요일 휴무','부산시 영도구 해양로301번길 45','무료','051-309-1900','https://www.mmk.or.kr/',35.0783256,129.0798565,'문화','바다의 과거와 현재, 미래, 세상의 모든 바다 이야기가 시작되는 해양박물관',6011);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6007,'금강공원식물원','상시운영','부산시 동래구 우장춘로 155','대인 1000원 어린이 및 경로우대 500원','051-582-3284','https://www.bisco.or.kr/geumgangpark/',35.2201331,129.0738073,'공원','울창한 숲과 기암괴석의 조화가 아름다운 금정산에 있는 도심 속 공원',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6008,'기장달음산자연휴양림','화요일 휴무','부산시 기장군 일광면 화용길 299-106','무료','051-722-3023','https://www.foresttrip.go.kr/indvz/main.do?hmpgId=0202',35.301617,129.185367,'자연','잔디광장을 중심으로 둥글게 배치된 숙소가 저마다의 색깔을 뽐내며 방문객을 맞이하는 자연공간',4);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6009,'기장도예관광힐링촌','상시운영','부산시 기장군 장안읍 기룡리 산126','무료','051-728-3909','https://www.gijang.go.kr/tour/index.gijang?menuCd=DOM_000000301008000000',35.360046,129.239801,'자연','공기 좋은 기장 기룡마을 산자락에 펼쳐진, 동심 속 동화마을이 펼쳐진 힐링촌 테마숲',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6010,'다대포','상시운영','부산시 사하구 몰운대1길 14','무료','051-220-5895','https://www.saha.go.kr/tour/contents.do?mId=0101030000',35.046999,128.966551,'자연','낙동강과 남해안이 만나 희고 고운 모래사장을 거닐 수 있는 해수욕장',63);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6011,'대신공원','상시운영','부산시 서구 대신공원로 37-18','무료','051-860-7830','-',35.1211379,129.0167921,'공원','수령 높은 노목들이 오색찬란하게 빛을 발하는 도심 속 휴식 공간. 자연 그대로의 힐링 쉼터',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6012,'동래읍성','매주 월 휴무','부산시 동래구 명륜동 산48-2','무료','051-550-6634','-',35.2101539,129.0894131,'역사','과거 부산 그 자체였던 동래를 감싸고 있는 읍성. 조용히 여유와 자연을 즐길 수 있는 곳',91);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6013,'동아대학교석당박물관','매주 일,월 휴무','부산시 서구 구덕로 225','무료','051-200-8493','http://museum.donga.ac.kr/',35.1042116,129.0191299,'역사','대한민국의 3대 대학박물관. 한 때 임시정부청사, 부산지방검찰청으로 쓰인 근대문화유산',6017);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6014,'민락수변공원','00:00 ~ 02:00','부산시?수영구?민락수변로?129','무료','051-610-4216','https://www.suyeong.go.kr/board/view.suyeong?boardId=BBS_0000073&menuCd=DOM_000001101001000000&startPage=1&dataSid=296',35.1545716,129.1329907,'공원','푸른 하늘과 끝없는 바다가 한눈에 펼쳐지는 풍경을 가진 광안리 바다의 낭만',6027);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6015,'민주공원','매주 월 휴무','부산시 중구 민주공원길 19','무료','051-790-7400','http://www.demopark.or.kr/main/',35.1100718,129.0280727,'공원','호국용사와 민주영령의 살아있는 정신이 고스란히 전해지는 중앙공원',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6016,'백산기념관','매주 월 휴무','부산시 중구 백산길 11 백산기념관','무료','051-600-025','https://www.bsjunggu.go.kr/tour/index.junggu?menuCd=DOM_000000208002001000&link=success&cpath=%2Ftour',35.1019518,129.0345919,'역사','백산상회를 일으켜 독립운동에 자금을 지원한 백산 안희제 선생을 기념하기 위한 공간 ',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6017,'범어사','상시운영','부산시 금정구 범어사로 250','무료','051-508-3122','http://www.beomeo.kr/',35.2839899,129.0687639,'문화','빼어난 산세를 자랑하는 금정산 자락에 위치한 신라 문무왕때 건축된 역사적인 사찰',9);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6018,'벡스코','상시운영','부산시 해운대구 APEC로 55','프로그램별 상이','051-740-7300','http://www.bexco.co.kr',35.1689766,129.1360411,'문화','부산의 대형 행사와 박람회가 열리는 국제적 규모의 전시컨벤션센터',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6019,'보수동책방골목','도서구입 별도','부산시 중구 책방골목길 16','무료','051-253-8253','http://www.bosubook.com/',35.1031252,129.0274609,'문화','입구 풍경에서부터 예스러움이 가득 묻어나는, 한 줄기 따뜻한 아날로그 감성을 지닌 책방들의 골목',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6020,'복천박물관,복천동고분군','매주 월 휴무','부산시 동래구 복천로 63 복천박물관','무료','051-554-4263','https://museum.busan.go.kr/bokcheon/index',35.2083599,129.0914505,'역사','가야의 뛰어난 철기문화를 알려주는 유물과 다양한 형태의 무덤이 전시되어 있는 박물관',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6021,'부산치유의숲','상시운영','부산시 기장군 철마면 철마천로 101','무료','051-976-2831','https://cafe.naver.com/busangreenforest',35.272772,129.137896,'자연','청정자연을 그대로 품은, 아홉산 자락에 넓게 자리한 부산 최초로 조성된 치유의 숲',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6022,'부산근대문화역사관','휴관(06/29-12/31)','부산시 중구 대청로 104','무료','051-253-3845','https://www.busan.go.kr/mmch',35.1026721,129.031176,'역사','대한민국의 아픈 역사 일제강점기, 그리고 근대화 시기의 부산의 역사를 간직한 곳',6);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6023,'부산도서관','09:00 ~ 22:00','부산시 사상구 사상로310번길 33','무료','051-310-5400','https://library.busan.go.kr/busanlibrary/index.do',35.172711,128.9853636,'문화','깔끔한 외관, 창문 너머로 한 가득 쏟아지는 햇살을 품은 부산의 대표 도서관',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6024,'부산박물관','매주 월 휴무','부산시 남구 유엔로 152','무료','051-610-7111','museum.busan.go.kr/busan',35.1295178,129.094151,'역사','구석기 유물부터 근현대에 이르기까지 부산의 역사를 한 번에 아우르는 부산을 대표하는 박물관',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6025,'부산시민공원','05:00 ~ 24:00','부산시 부산진구 시민공원로 73','무료','?051-850-6000','https://www.citizenpark.or.kr/',35.1681608,129.0573853,'공원','하야리야 부대가 있던 곳에서 70년 만에 부산 시민의 따뜻한 쉼터로 돌아온 공원',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6026,'부산엑스더스카이전망대','1000  21:00','부산시 해운대구 달맞이길 30','대인 27,000원 소인 24,000원','051-731-0099','http://www.busanxthesky.com/',35.1599375,129.1698125,'문화','국내에서 두 번째로 높은 건물에 있는 바다와 도시를 한 번에 조망할 수 있는 전망대',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6027,'부산임시수도기념관','매주 월 휴무','부산시 서구 임시수도기념로 45','무료','051-244-6345','http://museum.busan.go.kr/monument/index',35.1034532,129.0174521,'역사','한국 전쟁이 일어난 직후 임시수도가 된 부산의 대통령 관저로 쓰인, 부산의 역사를 담은 기념물',5);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6028,'사직야구장','상시운영','부산시 동래구 사직로 45','좌석 별 상이','051-505-7422','http://www.giantsclub.com/html/',35.1940316,129.0615183,'문화','야구를 사랑하는 야구의 도시 부산의 인기구단 롯데 자이언츠의 홈구장',88);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6029,'삼락생태공원','상시운영','부산시 사상구 낙동대로 1231','무료','051-303-0048',null,35.1687484,128.9735403,'공원','유유히 흘러가는 낙동강 줄기 옆에 삼락동 둔치에 넓게 자리잡은 생태공원',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6030,'송도용궁구름다리','휴무(11/03-12/31)','부산시 서구 암남동 620-53','서구 구민 1천원, 일반관광객 2천원','051-240-4087','https://www.bsseogu.go.kr/tour/index.bsseogu',35.061884,129.022211,'자연','바나 건너 작은 섬 동섬을 연결한 구름다리. 사랑을 이어주는 행운을 부르는 다리',56);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6031,'송도해수욕장','06:00 ~ 23:00','부산시 서구 암남동 송도해수욕장','무료','051-501-6054','http://www.bfo.or.kr/main/index.asp',35.076122,129.017298,'자연','1913년에 개장한 우리나라 1호 해수욕장. 송도스카이워크, 해상케이블카를 이용할 수 있다',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6032,'송상현광장','상시운영','부산시 진구 중앙대로 818','무료','051-850-6081','http://www.songsanghyeon.com/song/Main.do',35.1641542,129.0648058,'공원','도심 한가운데 아름다운 숲과 실개천을 간직한 광장. 시민을 위한 부산 최대 규모의 도심광장',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6033,'송정해수욕장','상시운영','부산시 해운대구 송정동 송정해수욕장','무료','051-501-6055','http://www.bfo.or.kr/main/index.asp',35.17827,129.199126,'자연','달맞이 길을 돌아 내려오면 보이는 넓고 길게 펼쳐진 백사장. 서퍼들이 사랑하는 바다',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6034,'수영F1963','09:00 ~ 21:00','부산시 수영구 구락로123번길 20','무료','051-756-1963','http://www.f1963.org/ko/',35.1769907,129.1154605,'문화','2008년까지 운영되었던 와이어공장 부지를 탈바꿈시킨 복합문화공간',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6035,'수영사적공원','상시운영','부산시 수영구 수영성로 43','무료','051-752-2947','http://www.suyeongminsok.or.kr',35.1710871,129.1139105,'공원','조선시대 남해안 수군지휘부가 있던 자리에 만든 사적공원이자 유적공원',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6036,'아미산전망대','매주 월 휴무','부산시 사하구 다대낙조2길 77','무료','051-265-6863','busan.go.kr/wetland/amisanintro01',35.052544,128.960647,'자연','낙동강의 끝자락이 남해안과 만나 바다가 되기 전, 거대한 삼각주의 강과 바다의 환상적인 분위기',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6037,'어린이대공원','상시운영','부산시 부산진구 새싹로 295','무료','051-860-7848','https://www.bisco.or.kr/bschildpark/',35.1846343,129.0434794,'공원','아이와 함께 어린이회관부터 오르막을 지나 놀이터까지, 자연속에서 동심을 즐기는 곳',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6038,'영도대교','상시운영','부산시 영도구 대교동1가 190-1','무료','-','-',35.0930473,129.0374683,'역사','부산  최초의 연륙교이자 도개교, 그리고 수많은 피란민들의 눈물로 약속한 공간 ',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6039,'영화의거리','상시운영','부산시 해운대구 마린시티1로 91','무료','-','-',35.1547966,129.144653,'문화','부산에서 촬영한 천만관객을 이끈 영화들을 위한 영화의 거리',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6040,'영화의전당','상시운영','부산시 해운대구 수영강변대로 120','프로그램별 상이','051-780-6000','http://www.dureraum.org',35.1711778,129.1271956,'문화','거대한 빅루프의 LED조명이 특징인 부산의 랜드마크. 영화의 도시 부산을 상징하는 곳',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6041,'오랑대공원','상시운영','부산시 기장군 기장읍 기장해안로 340','무료','-','-',35.2057006,129.2276931,'공원','바다의 안녕을 기원하는, 갯바위에 부딪히는 파도소리가 마음의 평안을 가져다주는 공원',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6042,'오륙도','상시운영','부산시 남구 오륙도로 137','홍보관 무료 / 유람선 별도','051-607-6395',' https://www.bsnamgu.go.kr',35.097635,129.120893,'자연','동해와 남해가 만나는 바다위의 부산에서 가장 아름다운 섬',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6043,'용두산공원','상시운영','부산시?중구?대청로116번길 13','무료','051-860-7820','https://www.bisco.or.kr/yongdusanpark/',35.1006536,129.0326226,'공원','부산을 찾는 이들이 빼놓지 않고 찾는 부산의 대표 랜드마크',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6044,'우암동소막마을','상시운영','부산시 남구 우암동','무료','-','-',35.1249213,129.0743458,'역사','화려한 부산의 가려진 역사. 피란민들의 움막과 판잣집으로 이루어진 부산의 옛 흔적',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6045,'유엔기념공원','하절기(09:00~18:00),동절기(09:00~17:00)','부산시 남구 유엔평화로 93','무료','051-625-0625','www.unmck.or.kr',35.1279039,129.0961877,'역사','세계 유일의 유엔기념묘지. 세계평화와 자유를 위해 생명을 바친 유엔군 전몰 장병들이 잠든 곳',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6046,'초량1941','11:00 ~ 19:00','부산시 동구 망양로 533-5','이용요금 별도','051-462-7774','https://ntchmgsugung.modoo.at/',35.1198148,129.029509,'문화','일제강점기에 지어진, 주변의 현대식 풍경과 대비되는 독특한 매력을 지닌 공간',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6047,'커피박물관','매주 토요일 휴무','부산시 부산진구 동천로 70 2층 207호','무료','010-9346-8000','https://www.kpeople24.com/home/info/2133',35.154865,129.062732,'문화','부산 최초의 커피전문박물관. 긴 시간에 걸쳐 발전한 커피의 긴 여정이 있는 곳',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6048,'태종대','하절기(04:00~24:00),동절기(05:00~24:00)','부산시 영도구 전망로 24','무료(다누비 열차 요금 별도)','051-405-8745','https://www.bisco.or.kr/taejongdae/',35.046999,128.966551,'자연','오랜 세월 파도에 깎여 각양각색의 신비를 가진 바위해안의 수려함을 볼 수 있는 곳',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6049,'해동용궁사','04:00 ~ 20:30','부산시 기장군 기장읍 용궁길 86','무료','051-722-7744','http://www.yongkungsa.or.kr',35.1883491,129.2233197,'문화','시원하게 트인 기장 앞바다에서 감탄이 절로 나오는 해안절경과 망망대해를 눈 앞에 두는 곳',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6050,'해운대해수욕장','09:00 ~ 18:00','부산시 해운대구 해운대해변로 264','무료','051-749-7601','http://sunnfun.haeundae.go.kr/',35.158601,129.160001,'자연','부산 바다의 정석. 다른 어떤 곳보다 다이내믹한 부산의 분위기를 느낄 수 있는 장소',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6051,'화명수목원','매주 월요일 휴무','부산시 북구 산성로 299','무료','051-362-0261','https://www.busan.go.kr/green/index',35.2510047,129.0427975,'공원','금정산 자락에 사뿐히 내려앉은 수목원. 시원한 물줄기와 산내음이 기분 좋은 하루를 만들어 주는 곳',0);
Insert into PROJECT.SIGHT (S_CODE,S_NAME,S_DATE,S_ADDRESS,S_FEE,S_TEL,S_HP,S_LATITUDE,S_LONGITUDE,S_THEME,S_INTRO,S_GOOD) values (6052,'흰여울문화마을','상시운영','부산시 영도구 흰여울길','무료','051-419-4067','http://www.ydculture.com/huinnyeoulculturetown/',35.078255,129.045316,'자연','가파른 절벽 끝, 부산의 대표적 원도심 흰여울길에 있는 영도의 독창적 문화예술마을',0);
--------------------------------------------------------
--  DDL for Index SYS_C008397
--------------------------------------------------------

  CREATE UNIQUE INDEX "PROJECT"."SYS_C008397" ON "PROJECT"."SIGHT" ("S_CODE") 
  PCTFREE 10 INITRANS 2 MAXTRANS 255 COMPUTE STATISTICS 
  STORAGE(INITIAL 65536 NEXT 1048576 MINEXTENTS 1 MAXEXTENTS 2147483645
  PCTINCREASE 0 FREELISTS 1 FREELIST GROUPS 1
  BUFFER_POOL DEFAULT FLASH_CACHE DEFAULT CELL_FLASH_CACHE DEFAULT)
  TABLESPACE "USERS" ;
--------------------------------------------------------
--  Constraints for Table SIGHT
--------------------------------------------------------

  ALTER TABLE "PROJECT"."SIGHT" MODIFY ("S_NAME" NOT NULL ENABLE);
  ALTER TABLE "PROJECT"."SIGHT" MODIFY ("S_ADDRESS" NOT NULL ENABLE);
  ALTER TABLE "PROJECT"."SIGHT" MODIFY ("S_LATITUDE" NOT NULL ENABLE);
  ALTER TABLE "PROJECT"."SIGHT" MODIFY ("S_LONGITUDE" NOT NULL ENABLE);
  ALTER TABLE "PROJECT"."SIGHT" MODIFY ("S_THEME" NOT NULL ENABLE);
  ALTER TABLE "PROJECT"."SIGHT" ADD PRIMARY KEY ("S_CODE")
  USING INDEX PCTFREE 10 INITRANS 2 MAXTRANS 255 COMPUTE STATISTICS 
  STORAGE(INITIAL 65536 NEXT 1048576 MINEXTENTS 1 MAXEXTENTS 2147483645
  PCTINCREASE 0 FREELISTS 1 FREELIST GROUPS 1
  BUFFER_POOL DEFAULT FLASH_CACHE DEFAULT CELL_FLASH_CACHE DEFAULT)
  TABLESPACE "USERS"  ENABLE;
--------------------------------------------------------
--  Ref Constraints for Table SIGHT
--------------------------------------------------------

  ALTER TABLE "PROJECT"."SIGHT" ADD CONSTRAINT "SIGHT_FK1" FOREIGN KEY ("S_CODE")
	  REFERENCES "PROJECT"."ALLFS" ("A_CODE") ENABLE;


---------------------------------------------------------------------



--------------------------------------------------------
--  파일이 생성됨 - 일요일-1월-29-2023   
--------------------------------------------------------
--------------------------------------------------------
--  DDL for Table TUSER
--------------------------------------------------------

  CREATE TABLE "PROJECT"."TUSER" 
   (	"USER_ID" VARCHAR2(20 BYTE), 
	"USER_PW" VARCHAR2(60 BYTE), 
	"USER_NAME" VARCHAR2(60 BYTE)
   ) SEGMENT CREATION IMMEDIATE 
  PCTFREE 10 PCTUSED 40 INITRANS 1 MAXTRANS 255 
 NOCOMPRESS LOGGING
  STORAGE(INITIAL 65536 NEXT 1048576 MINEXTENTS 1 MAXEXTENTS 2147483645
  PCTINCREASE 0 FREELISTS 1 FREELIST GROUPS 1
  BUFFER_POOL DEFAULT FLASH_CACHE DEFAULT CELL_FLASH_CACHE DEFAULT)
  TABLESPACE "USERS" ;
REM INSERTING into PROJECT.TUSER
SET DEFINE OFF;
Insert into PROJECT.TUSER (USER_ID,USER_PW,USER_NAME) values ('sky','1234','하늘');
Insert into PROJECT.TUSER (USER_ID,USER_PW,USER_NAME) values ('admin','1234','관리자');
Insert into PROJECT.TUSER (USER_ID,USER_PW,USER_NAME) values ('sea','1234','바다');
Insert into PROJECT.TUSER (USER_ID,USER_PW,USER_NAME) values ('admin2','1234','관리자2');
Insert into PROJECT.TUSER (USER_ID,USER_PW,USER_NAME) values ('1234','1234','1234');
--------------------------------------------------------
--  DDL for Index SYS_C008328
--------------------------------------------------------

  CREATE UNIQUE INDEX "PROJECT"."SYS_C008328" ON "PROJECT"."TUSER" ("USER_ID") 
  PCTFREE 10 INITRANS 2 MAXTRANS 255 COMPUTE STATISTICS 
  STORAGE(INITIAL 65536 NEXT 1048576 MINEXTENTS 1 MAXEXTENTS 2147483645
  PCTINCREASE 0 FREELISTS 1 FREELIST GROUPS 1
  BUFFER_POOL DEFAULT FLASH_CACHE DEFAULT CELL_FLASH_CACHE DEFAULT)
  TABLESPACE "USERS" ;
????????????????????????????
????????????????????????????  Constraints for Table TUSER
????????????????????????????

  ALTER TABLE "PROJECT"."TUSER" MODIFY ("USER_PW" NOT NULL ENABLE);
  ALTER TABLE "PROJECT"."TUSER" MODIFY ("USER_NAME" NOT NULL ENABLE);
  ALTER TABLE "PROJECT"."TUSER" ADD PRIMARY KEY ("USER_ID")
  USING INDEX PCTFREE 10 INITRANS 2 MAXTRANS 255 COMPUTE STATISTICS 
  STORAGE(INITIAL 65536 NEXT 1048576 MINEXTENTS 1 MAXEXTENTS 2147483645
  PCTINCREASE 0 FREELISTS 1 FREELIST GROUPS 1
  BUFFER_POOL DEFAULT FLASH_CACHE DEFAULT CELL_FLASH_CACHE DEFAULT)
  TABLESPACE "USERS"  ENABLE;
