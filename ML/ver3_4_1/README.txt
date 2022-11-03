# 環境構築に関して

本講座では、Miniconda または Anaconda を使用して、仮想環境を構築していただきます。
以下の手順に従い、受講までに仮想環境を構築しておいてください。
ご不明な点がございましたら、ご連絡ください。


# 仮想環境構築の手順

別で配布しているpython_env_turorial_windows.pdfまたはpython_env_turorial_mac.pdf を参照しつつ、以下の手順で環境構築を進めてください。

1. Anaconda または Miniconda をインストール
2. python_env/env_mlver3.yml を使って、仮想環境を構築
3. 仮想環境を起動
4. JupyterNotebook を起動
5. DAY1/2_notebook/0_preparation.ipynb を開く
6. すべてエラーなく実行できれば、仮想環境構築完了


# 注意点

・社用のパソコンなどでアクセス制限のあるインターネット回線をご利用の方は、インストール作業を問題なく行えることを事前にご確認ください。
・手順2. の仮想環境起動時に長文のエラーが表示されることがあります。最後に(mlver3) C:... または (mlver3) suai@MacBook-Pro % のように表示されていれば、仮想環境は正常に起動していますので、エラーは無視して構いません。
・手順5. のNotebook実行時に、kerasやtensorflowをインポートするセルで、numpyに関する警告（Warning）が出る場合があります。演習には支障ないため、警告は無視して構いません。