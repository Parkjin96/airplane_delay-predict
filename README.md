# airplane_delay-predict
competition site : https://www.bigcontest.or.kr/community/faq.php

# Purpose 
predicting the delay rate and possivility of delay through aviation data

# Data description
테이블설명		2019.9.16 ~ 2019.9.30 까지 지연율 계산			
No.	컬럼ID	컬럼명	                    타입	        NULL	비고
1	  SDT_YY	연(year)	                  VARCHAR2(8)	  N	
2	  SDT_MM	월(month)	                VARCHAR2(8)	  N	
3	  SDT_DD	일(day)	                  VARCHAR2(8)	  N	
4	  SDT_DY	요일(day of week)	         VARCHAR2(8)	 N	
5	  ARP 	  공항(airport)	             VARCHAR2(4)	 N	
6	  ODP 	  상대공항(rerlative airport)VARCHAR2(4)	 N	
7	  FLO 	  항공사(airline)	          VARCHAR2(3)	  N	
8	  FLT 	  편명(flight name)	         VARCHAR2(10)	 N	
10	AOD	    출도착(arrive/departure)	  CHAR(1)	      N	   A:도착, D:출발
11	STT	    계획시각(planetime)        CHAR(8)	     N	
13	DLY	    지연여부(delay T/F)        CHAR(1)	     Y	  지연:1, 정상:0
14	DLY_RATE지연확률(delay possibility)NUMBER(8)	   Y	  소수점 셋째자리에서 반올림

