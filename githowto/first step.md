# 1.Git上で新しくリポジトリをつくる
Create repository をタップ
URL(http://github.com)をコピー
# 2. 新しい独立したフォルダを作成して移動する
mkdir プロジェクト名
cd プロジェクト名

# 3. Gitの管理を開始し、初期ファイルを作成する
git init
echo "# プロジェクト名" >> README.md

# 4. 変更を記録（コミット）する
git add .
git commit -m "first commit"

# 5. ブランチ名をmainにし、GitHubのURLと紐づけてアップロードする
git branch -M main
git remote add origin コピーしたURL
git push -u origin main

# 6.VS Codeで開いて作業をまとめる
code .

# ２回目以降
git add .
git commit -m "変更内容のメモ"
git push

