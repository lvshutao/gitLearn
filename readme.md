### Git ѧϰ�ʼ�

#### Git Gui ����Щ���õ������Ϊͨ������command line �²����ģ������Ͳ��þ����򿪽�����

<img src='./pic/1.start.png' />

<img src='./pic/2.sshkey.png' />

<img src='./pic/3.common.png' />

<img src='./pic/4.branch.png' />

<img src='./pic/5.commit.png' />

<img src='./pic/6.merge.png' />

##### merge��һ��ʾ��

<img src='./pic/6.mregeRemote1.jpg' />

���git merge remotes/origin/master

<img src='./pic/6.mregeRemote2.png' />

<img src='./pic/7.remote.png' />

<img src='./pic/8.repository.png' />


#### �������ù��ܣ�

##### �鿴�ļ��޸ļ�¼

* �鿴���ύ��¼ <br/>git log --pretty=oneline fileName
* �鿴��ϸ�ύ��¼ <br/>git log -p fileName
* �鿴ÿһ���ύ	<br/>git blame fileName

##### git diff

1. ��ͬ��֧�ϵĲ�ͬ�ļ�<br/>
git  diff  branchA:fileA  branchB:fileB
2. ��ͬ��֧�ϵ���ͬ�ļ�<br/>
git  diff  branchA  branchB  --  file

<img src='./pic/9.diff.png' />