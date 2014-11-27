#JBossのOSSVERT環境を作成するDockerfile

* なにこれ  
一応JBossのOSSVERT環境が入っているDockerコンテナを簡単に作成するDockerfileです。

* 発想  
非常にシンプルな考えで、JBossのバージョンごとに一つのイメージを作成します。

* OSSVERT設定と違うところ  
 　* myserver.properties  
     管理コンソールを0.0.0.0にバインディングする
