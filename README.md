# ORACLE_DBMS_MAZE_GAME

You just need to execute all the statements

set serverout on;

call registerPlayer('username', 'password');
call login('username', 'passoword');
call showPlayer(1);
call goDown(1);
call goUp(1);
call goLeft(1);
call goRight(1);

call logout(1);

triggers:

updateScoreTrigger1
updateScoreTrigger2

You are p:player.
Eat a : apple / m:mango to increase score. Stage will automatically change when stamping g:goal.
