PBL : GitHub Collaboration Scenarios
====================================

..
   テキトーにTheWorld.Javaを編集。なんか追加してください

   →保存
   →ExplorerでTheWorldを右クリック
   　→Team－Addを選択

   →もっかい右クリック
   　→Team－Commitを選択
   　　→Commitはなんかコメントいれてください

   →また右クリック
   　→Team－Push to Upstreamを選択
   　　→いろいろ出るからOKを押す

   ここからはGitHub
   →Your RepositoriesのTheWorldを選択

   →最新のUPDATEが表示されてるハズなので、PullRequestを押下

   　これで全員に更新が通知されるハズ…

Scenario Based Groupwork
------------------------

Introduction
~~~~~~~~~~~~
In this section, a group with tree members acts
following scenarios to learn how to use GitHub.

In this scenario, we assume that following members are in the group.

- **Nobita**
  starts a new project
- **Shizuka**
  helps **Nobita**
- **Dekisugi**
  imprements a new function

Scenario
--------

Nobita starts a new project
~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Nobita** acts following scenarios.

#. Start Eclipse
#. Create a new project named *Doraemon*
#. Create a new class named *Main*
#. Copy & paste following codes to *Main.java*

#. Commit your working tree
#. Share the project with git
#. Push the project to GitHub

::
      pubilc static ...

Fork and Clone the Project
~~~~~~~~~~~~~~~~~~~~~~~~~~
**Shizuka** and **Dekisugi** act following scenarios.

#. Open GitHub webpage
#. Follow **Nobita**
#. Fork **Nobita/Doraemon**
#. Start Eclipse
#. Clone **Shizuka/Doraemon**

Sizuka edits the code
~~~~~~~~~~~~~~~~~~~~~
**Shizuka** act following scenarios.

#. Edit *Main.java*
#. Commit your working tree
#. Push the project to **Shizuka/Doraemon**
#. Send a pull request to **Nobita**

Dekisugi adds a File
~~~~~~~~~~~~~~~~~~~~
**Dekisugi**

#. Add *README.txt* file
#. Push the project to **Dekisugi/Doraemon**
#. Send a pull request to **Nobita**

Nobita pulls and checks their requests
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
**Nobita**

#. Pull the commit by **Shizuka** and **Dekisugi**
#. Run and check
#. Push the project to **Nobita/Doraemon**

Branch,Conflict,Marge...
~~~~~~~~~~~~~~~~~~~~~~~~

References
----------

- http://d.hatena.ne.jp/zariganitosh/20080905/1220621182
- http://sourceforge.jp/magazine/09/03/16/0831212

