Giti.me User Manual
===================

׼������
--------
- Windows�û������ز���װ���°汾��[Git for Windows](http://code.google.com/p/msysgit/downloads/list Git for Windows)��
- Linux�û�����װgit�������磺Ubuntu�û�����Terminal����`$ sudo apt-get install git`
- OSX�û���

����Giti��me����
----------------
Windows�û�����Git Bash����ɲ�����Linux��OSX�û�����Terminal����ɲ�����
1.  ����Ƿ��Ѿ�������SSH Key
	
	`$ cd ~/.ssh`
	�����ʾ"No such file or directory"����������2��������������3��
	
2.  �����µ�SSH Key

	ִ�����������������µ�SSH Key      
	`$ ssh-keygen -t rsa -C "yourname@youremail.com"`      
	��ȷ��д����Ŀ¼��passphrase�������鲻�޸�Ĭ��Ŀ¼������һ����д��ֱ�ӻس�����ΪĬ��ֵ��
	
3.	�ϴ�SSH Key��Giti.me
	
	��¼Giti.me��ѡ�����SSH Key���������ɺõ�SSH Key���Ƶ���ʶΪkey���ı����У���Ϊ����һ�����⡣�����Add Key�Ա���SSH Key��
	
4.	����һ��   
	
	����`$ ssh -T git@github`��������ʾ������ʾ��    
	`hello username, this is gitolite v2.2-ossxp-2-0-g40638fd running on git 1.7.5.4      
	the gitolite config gives you the following access:      
	..........`    
	�������Ĳ���Ϊ���İ汾����Ȩ��Ϣ��
	
5.	���ø�����Ϣ
 
	���������������޸��������ֺ�email     
	`git config --global user.name "Your Name"`   
	`git config --global user.name your_email@youremail.com`    

����һ���µİ汾��
------------------
1.	��ʼ��git�汾�⣬���README�ļ�
	
	��������ָ�����һ����git�汾�Ⲣ�½�һ��README�ļ���
	`$ mkdir repo`    
	`$ cd repo`    
	`$ git init`      
	`$ touch README`
	
2.	�ύ�޸�
	
	��������ָ��ύREADME�ļ���������
	`$ git add README`     
	`$ git commit -m "first commit"`   
    `$ git remote add origin git@giti.me:username/repo.git`	    
	`$ git push origin master`    
	
����Gitʹ�õĻ�����������ʣ�