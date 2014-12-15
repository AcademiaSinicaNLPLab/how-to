Feelit project
===

- ##tools and environment setup
	- 裝 `python`
	- 用 `sublime` + `ipython` 寫程式
	- 用 `pip install [package]` 管理 python 套件
	- 利用 `ssh` 登入 server
		- ssh __your-user-name__@doraemon.iis.sinica.edu.tw -p 2222
	- 善用 `git` 做版本控制
		- 申請 github 帳號，請企鵝幫忙加入 [實驗室 github 群組](https://github.com/AcademiaSinicaNLPLab)

- ##Corpus (語料)
	- LJ40K: LiveJournal
	- 資料庫
		- 資料庫為 `mongodb`
		- python 可用 `pymongo`	做連接
			
		```
		# 登入 server
		> ssh xxx
		
		# 登入後，查看 LJ40K.sents 的一筆資料
		> mongo
		> use  LJ40K
		> show collections
		> db.sents.findOne()
		```
		

	
- ##Data preprocessing
	- NLP: `NLTK`, `Stanford Parser`
	- Machine Learning: `scikit-learn`

- goal 
- 怎麼抽 features
- svm 概念跟用法
- 各種 feature 的 performance 比較
- fusion (late fusion & MKL)
- future work (feature representation)