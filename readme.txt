MineGame

Gitʹ�ü�Ҫ˵��

#�����ļ��е��Ҽ�
#ѡ�� git bash

#�ڱ��ؿ�¡Զ�ֿ̲�
#git  clone  https://github.com/�ʺ�/Զ�ֿ̲�.git
git  clone  https://github.com/cib2000/TestGit.git

#�쿴���زֿ�״̬
git status

#�л���Զ�ֿ̲�
#cd Զ�ֿ̲�
cd TestGit

git status

#���������ļ����浽���棬׼�������زֿ�
#git add  �����ļ���
#  . С�����ʾ��ǰ·����Ŀ¼��
git add  .
git status


#���������ļ��ύ�����زֿ�
git commit  -m  "�����ύ˵����ע�ͣ�"
git status

#ȡ�����һ���ύ
git  reset  HEAD^
git status

#ȡ����������ύ
#git  reset  HEAD^^^
#��������git  reset  HEAD~3

#�ӱ��زֿ�ָ���������
git  checkout  .
git  status

################################
#�����زֿ�ͬ���ύ��Զ�ֿ̲�
git config --global user.name "github����ע����ʻ�"
git config --global user.email "�ʻ���Ӧ�������ַ"

#�쿴Զ�ֿ̲�����
git remote -v

#���Զ�̷�֧������
#git remote  add  origin https://github.com/�ʺ�/Զ�ֿ̲�.git
git remote  add  origin https://github.com/cib2000/TestGit.git

#���͵�Զ�ֿ̲�
git push

#�г�ͻʱ��ǿ������
git push  -f


################################
#��Զ�ֿ̲���±��زֿ�
git pull


################################
#��Զ�ֿ̲����ص�����ȫ���ļ��� ��2
#��ʼ�����زֿ�
git init

#git pull https://github.com/�ʺ�/Զ�ֿ̲�.git
git pull https://github.com/cib2000/TestGit.git

/git/cib2000

/git/testgit



