Application:
  * @Sign in (function)
- require Users
- require Pictures
- require Network

Users (class)
* @users_id - username
* @password - users password
* @user_pic_id - user uploaded pictures
* @tagged_user_pics - pictures of user, tagged in.
  - tag_users

Pictures (class)
* @picture_id - individual picture identifier
  - add_pictures
* @tagged_users - tag users in network
  - tag_users
* @date_stamp - date photo uploaded
  - add_date
* @time_stamp - time photo uploaded
  - add_time
* @location - location photo taken
  - add_location
* @caption - description added by user
  - add_caption
* @comments - users in-network added comments
  - add_comment
* @album - segmented albums
  - add_album

Network (class)
* @category - category name
  - view_category_list 
  - add_category
* @user_network - group/list of friends
  - add_networks
  - add_users






