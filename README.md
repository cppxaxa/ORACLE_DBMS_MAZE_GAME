# ORACLE_DBMS_MAZE_GAME

You just need to execute all the statements<br/><br/>

set serverout on;<br/><br/>

call registerPlayer('username', 'password');<br/>
call login('username', 'passoword');<br/>
call showPlayer(1);<br/>
call goDown(1);<br/>
call goUp(1);<br/>
call goLeft(1);<br/>
call goRight(1);<br/><br/>

call logout(1);<br/><br/>

triggers:<br/><br/>

updateScoreTrigger1<br/>
updateScoreTrigger2

You are p:player.<br/>
Eat a : apple / m:mango to increase score. Stage will automatically change when stamping g:goal.<br/>
