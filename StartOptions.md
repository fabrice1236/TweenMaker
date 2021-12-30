# Changing the start option
Hello and welcome, if you are here you either saw the warning when changing the property or you just wanted to give a look, so lets get right into it ! \
To start the tween if you chose the on call property, you first need to require the tweening script by doing the following : \
``
local TweeningModule = require([path to the part].TweenModule) 
`` \
you need to replace [path to the part] by the actual path to your part, per exemple
``
workspace.Part
``
After that, to call the tween, you simply need to execute \
``
TweeningModule.Start()
`` \
and the tween should start ! Simple enough, right ? \

**NOTE : you can call the tween as many times as you wish as long as you let it the time to finish**
