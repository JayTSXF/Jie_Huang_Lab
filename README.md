# Hey guys, I am Jie (Jay) Huang, and my partner is Harry (Jiacheng) He. I am from section 007, Harry is from section 002. Our final project is a game called FlappyBirds and FlappyBirds’ Friends. In the beginning, we planned to make a game like Mario, but we encountered a lot of bugs such as Mario’s air resistance, jump inertia, game crash, and so on. Therefore, we changed our plan to make a game like the FlappyBirds game. We followed the tutorial video, and we changed a lot of stuff and added a lot of our own ideas. First of all, we studied imported how to use pygame and pycharm. Second, we create the structure of the FlappyBirds which are three themes of in-game theme, menu theme, and sprites died theme. Then, we started to build the game. We didn't let the bird's wings vibrate but we change the idea to add many different characters and different backgrounds. The first bug that we encountered is that the drop speed of the dying character is very slow, we changed the FPS to fix it. The second bug that we encountered is that the characters hitting the sky or ground will cause the game to crash. We fixed it by adding a variable. The third bug that we faced is that we met errors when we used pygame.sprite.Sprite() which tutorial video recommends. Thus, we did not use pygame.sprite.Sprite(), but we use some python’s own code which is harder than pygame.sprite.Sprite(). The water pipe only can turn 180 degrees but not mirror flip because we use pygame.transform.rotate() but not flip(), the reason is we faced multiple bugs when we used flip(). When the character died, the water pipes disappeared. However, we added a RIP tomb instead of water pipes. We tried to change the speed of moving, but there are some bugs that we cannot fix. Thus, we changed the idea to that let the difficulty of the game gradually increase with the game time until it is the most difficult. The biggest bug that we met is that the scores cannot display normally. At first, the character who passed a pipe will get 22 scores. After we fix, the character who passed a pipe will get 1 score but the character will not get any score when passing the first pipe. So, we give 1 score when the game starts. Overall, the game is kind of successful, and we studied lots of knowledge that how to use python and pygame.
# Our video link: https://youtu.be/Arw3q1M5bZ8
# Tutorial video vedio link: https://www.bilibili.com/video/BV1Kz4y1m7PZ?spm_id_from=333.999.0.0
