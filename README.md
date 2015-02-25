#yiiDemo
This demo was created based on Yii framework.
##Directory structure
    /www 
        the project
    /yii  
        the yii framework
-----------------------------

Mon Feb 23 11:51:29 UTC 2015

	1. using yii v1.1.16
		
		cd yii
		git checkout 1.1.16
		cd ..

	2. create project with yiic
	
		yii/framework/yiic webapp www


Wed Feb 25 10:43:02 UTC 2015
	
	1. testing gii and it works well

		important line
			(
			add '*' to ipFilter being access gii from anywhere.
			keep in mind after debug delete your /index-test.php to deny access gii from public.
			)

		`
			'ipFilters'=>array('127.0.0.1','::1','*'),
		`



