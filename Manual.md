Giti.me User Manual
===================

׼������
--------
- Windows�û������ز���װ���°汾��[Git for Windows](http://code.google.com/p/msysgit/downloads/list Git for Windows)��
- Linux��OSX�û�����װgit�������磺Ubuntu�û�����Terminal����`$ sudo apt-get install git`

����Giti.me����
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
	����`$ ssh -T git@github`�����������˻�ӭ��Ϣ�Ͱ汾����Ȩ��Ϣ����˵���������óɹ��ˡ�
	
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
	
Git���������ٲ�
---------------
![alt Git�����ٲ�](../git.png)