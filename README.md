## usersテーブル

|Colum          | type     |
|-------------- | -------- |
|id             | int      |
|name           | varchar  |
|email_verlfied | timestamp|
|password       | varchar  |
|remember_token | varchar  |
|update_at      | timestamp|
|created_at     | timestamp|

### Association

- has-many :reviews


## reviewsテーブル

|Colum          | type     |
|-------------- | -------- |
|id             | int      |
|user_id        | int      |
|title          | varchar  |
|body           | varchar  |
|image          | varchar  |
|update_at      | timestamp|
|created_at     | timestamp|

### Association

- belongs_to :user


