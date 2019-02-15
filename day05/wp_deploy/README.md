



	   	        source
			  |
			  |
			roles
			  |
	   	          |
	   ----------------------------------------
	   |	    |	       |        |	  |
	   |        |          |        |         |
	  role     role	     role      role      role
	 common   mariadb   nginx   php-fpm   wordpress


0. summary

    - role summary
	|-- common 	---> selinux & firewall
	|-- mariadb	---> mariaDB
	|-- nginx	---> nginx 
	|-- php-fpm	---> php module for nginx
	|-- wordpress	---> wordpress
        
        -----------------------------------------------

    - directory
        |-- defaults    ---> 기본 지정 변수
        |-- handlers	---> 핸들러 구성
	|-- meta	---> 역할에 대한 기본 정보
	|-- tasks	---> 역할이 실행할 작업들
	|-- templates	---> jinja2 파일
	|-- tests	---> 테스트 플레이 제공
	|-- vars	---> 사용할 변수















