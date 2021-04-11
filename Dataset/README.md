
## Files : 
[1] [behaviors.tsv](https://github.com/caped-crusader16/CSE523-Machine-Learning-Team-Gryffindor/blob/main/Dataset/behaviors.tsv) : is a TSV (tab separated values) file containing the data of the user's interaction and history with the Microsoft Bing. Dataset has following columns :
  * Impression ID. The ID of an impression.
  * User ID. The anonymous ID of a user.
  * Time. The impression time with format "MM/DD/YYYY HH:MM:SS AM/PM".
  * History. The news click history (ID list of clicked news) of this user before this impression. The clicked news articles are ordered by time.
  * Impressions. List of news displayed in this impression and user's click behaviors on them (1 for click and 0 for non-click). The orders of news in a impressions have been shuffled.
  
[2] [news.tsv](https://github.com/caped-crusader16/CSE523-Machine-Learning-Team-Gryffindor/blob/main/Dataset/news.tsv) : is a TSV (tab separated values) file containing the data of the news articles. Dataset has following columns :
  * News ID
  * Category
  * SubCategory
  * Title
  * Abstract
  * URL
  * Title Entities (entities contained in the title of this news)
  * Abstract Entities (entites contained in the abstract of this new
