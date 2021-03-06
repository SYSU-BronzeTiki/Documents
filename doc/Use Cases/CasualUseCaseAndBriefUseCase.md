### Casual Use Case

#### 用户注册

用户输入用户标识符，系统检查用户标识符是否唯一并返回检查结果，用户输入账号密码，系统检查用户密码是否过于简单并返回检查结果，用户再次确认密码，系统检查密码是否一致并返回检查结果，系统存储用户个人信息（加密）。

![sign_up](https://raw.githubusercontent.com/SYSU-BronzeTiki/Documents/master/image/sign_up.png)

#### 用户登陆

用户输入用户标识符与用户密码，系统检查用户名和密码的正确性，用户名和密码匹配则登陆成功，跳转到个人页面，如果用户名和密码不匹配则提示错误并停留在登陆界面。

![sign_in](https://raw.githubusercontent.com/SYSU-BronzeTiki/Documents/master/image/sign_in.png)

#### 用户信息修改

用户在登陆后，在个人界面中修改个人信息，如果修改的是用户密码信息，那么需要提供旧密码以及新的密码，如果修改的是用户昵称，用户头像，用户签名之类的信息，则只需要填入新的内容即可。

![modify](https://raw.githubusercontent.com/SYSU-BronzeTiki/Documents/master/image/modify.png)

### Brief Use Case

用户进入页面之后，无论登陆与否，都可以看到系统显示的当前正在上映的电影，点击可以查看电影的详情介绍，评分以及其他用户的讨论

用户进入页面之后，无论登陆与否，都可以使用页面内的搜索功能，可以通过各种信息来搜索一部影片，点击搜索结果同样可以看到电影的详情介绍，评分以及其他用户的讨论

用户登陆后，可以使用推荐功能，推荐功能根据用户的习惯以及用户的观影经历，评价，为用户推荐电影，推荐的电影是存在于影片库中的，无论是否正在上映，点击推荐结果同样可以看到电影的详情介绍，评分以及其他用户的讨论