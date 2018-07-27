<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Updated Game</title>
</head>
<body>

var startButton = document.getElementById("start");
var scoreButton = document.getElementById("scoreButton");
var settingButton = document.getElementById("setting");
var lightButton=document.getElementById("light");
var soundButton=document.getElementById("sound");
var hudButton=document.getElementById("hud");
var instructions=document.getElementById("instructions");
var bg=document.getElementById("gameWorld");
var gameTitle = document.getElementById("gameTitle");
var score = document.getElementById("score");
var dialog = document.getElementById("dialog");
var text = document.getElementById("text");
text.innerHTML = "Send these enemies to super-hell!! \n";
var beginAudio = new Audio();
var brick = new Audio();
var health = 3;
var timer = document.getElementById("timer");

var hitHurt = new Audio();
var shootingAudio = new Audio();
var explosionAudio =new Audio();
var openGateAudio = new Audio();
openGateAudio.src ="Audio/Start2.wav";
var upLevelAudio = new Audio();
upLevelAudio.src = "Audio/Back.wav";
brick.src = "Audio/brick.wav";
hitHurt.src = "Audio/Hit_Hurt20.wav";
explosionAudio.src = "Audio/explode.mp3";
var gameStart = false;
shootingAudio.src = "Audio/shooting.mp3";
beginAudio.src = "Audio/begin.mp3";
beginAudio.play();
startButton.addEventListener("click", startGame, false);
settingButton.addEventListener("click",setting,false);
lightButton.addEventListener("click",light,false);
soundButton.addEventListener("click",sound,false);
hudButton.addEventListener("click",hud,false);
lightButton.style.display = "none";
soundButton.style.display = "none";
hudButton.style.display = "none";
var backButton=document.getElementById("back");
backButton.addEventListener("click",back,false);
backButton.style.display="none";
function back()
{
gameTitle.innerHTML = "CRIMSON INVASION";
startButton.style.display = "block";
gameTitle.style.left = "33%";
scoreButton.style.display = "block";
settingButton.style.display = "block";
lightButton.style.display = "none";
soundButton.style.display = "none";
hudButton.style.display = "none";
backButton.style.display="none";
}

var  tick = 60;
function startGame()
{
startButton.style.display = "none";
scoreButton.style.display = "none";
settingButton.style.display = "none";
gameTitle.style.display = "none";
canvas.style.filter = "none";
document.getElementById("timer").style.display = "block";
dialog.style.display = "block";
gameStart = true;
health = 3;

beginAudio.pause();
shootingAudio.play();
var timeInterval = setInterval(function() {

if(gameStart)
{
tick--;
timer.innerText = "Time: " + tick;
}else clearInterval(timeInterval);

}, 1000);

}

function setting()
{
lightButton.style.display = "block";
soundButton.style.display = "block";
hudButton.style.display = "block";
backButton.style.display="block";
dialog.style.display = "none";
gameTitle.style.left = "45%";
canvas.style.filter = "opacity(50%) blur(10px)";
gameTitle.innerHTML = "Setting";
}

function hud() {
if(hudButton.innerHTML === "HUD : On")
{
instructions.style.display = "none";
hudButton.innerHTML = "HUD : Off";
}
else
{
instructions.style.display = "block";
hudButton.innerHTML = "HUD : On";
}

}

function light()
{
if(lightButton.innerHTML === "Lights : On")
{
bg.style.backgroundImage = "none";
lightButton.innerHTML="Lights : Off";
instructions.style.color="white";
}
else{
bg.style.backgroundImage = "url('Images/bg.jpg')";
lightButton.innerHTML = "Lights : On";
instructions.style.color="black";
}

}

function sound()
{
if(soundButton.innerHTML === "Sound : On")
{
upLevelAudio.muted = true;
beginAudio.muted = true;
brick.muted = true;
hitHurt.muted = true;
shootingAudio.muted = true;
explosionAudio.muted = true;
openGateAudio.muted = true;
soundButton.innerHTML = "Sound : Off";
}
else
{
upLevelAudio.muted = false;
beginAudio.muted = false;
brick.muted = false;
hitHurt.muted = false;
shootingAudio.muted = false;
explosionAudio.muted = false;
openGateAudio.muted = false;
soundButton.innerHTML="Sound : On";
}
}
/*var coin = function()
{
this.col = null;
this.row = null;
this.angle= 0;
};
var coins =[];
var coinImage = new Image();
coinImage.src = "Images/coin.png";*/


var canvas = document.getElementById("canvas");
canvas.width = 924;
canvas.height = 880;
canvas.style.backgroundImage = "url('Images/ground.png')";
var ctx = canvas.getContext("2d");
var mapImage = new Image();
mapImage.src = "Images/stylesheet.png";
var currentScore = 0;
var bulletImage = new Image();
bulletImage.src = "Images/bullet.png";
var playerImage = new Image();
playerImage.src = "Images/player.png";
var player =
{
col: Math.floor(Math.random() * 9 + 1),
row: 8,
positionX: 0,
positionY: 2,
img: playerImage
};

var MAP =
{
map: [
[3, 3, 3, 3, 3, 3, 3, 3, 3, 3, 3, 3, 3, 3, 3, 3, 3, 3, 3, 3, 3, 3],
[3, 0, 0, 0, 0, 0, 0, 4, 4, 4, 4, 4, 4, 4, 4, 0, 0, 0, 0, 0, 0, 3],
[3, 0, 0, 0, 0, 0, 0, 0, 4, 4, 4, 4, 4, 4, 0, 0, 0, 0, 0, 0, 0, 3],
[3, 0, 0, 0, 0, 0, 0, 0, 0, 0, 2, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 3],
[3, 0, 0, 0, 0, 0, 0, 2, 2, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 3],
[3, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 2, 0, 0, 2, 0, 0, 0, 0, 0, 3],
[3, 0, 0, 0, 0, 0, 0, 0, 2, 0, 2, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 3],
[3, 0, 0, 2, 0, 0, 2, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 3],
[3, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 3],
[3, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 3],
[3, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 2, 0, 0, 0, 0, 0, 3],
[3, 0, 0, 0, 0, 0, 0, 0, 2, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 3],
[3, 0, 2, 0, 0, 0, 0, 0, 0, 0, 2, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 3],
[3, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 2, 0, 0, 0, 0, 0, 0, 3],
[3, 0, 0, 0, 0, 2, 0, 2, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 3],
[3, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 3],
[3, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 2, 0, 0, 0, 0, 0, 0, 0, 0, 0, 3],
[3, 0, 0, 0, 2, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 3],
[3, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 2, 0, 0, 0, 0, 3],
[3, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 3],
[3, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 3],
[3, 3, 3, 3, 3, 3, 3, 3, 3, 3, 3, 3, 3, 3, 3, 3, 3, 3, 3, 3, 3, 3]
],
img: mapImage,
numOfBricks: 0,
numOfItems: Math.floor(Math.random() * 5),
item: 0,
randomMap: function ()
{
for (var i = 0; i < 22; i++)
{
for (var j = 0; j < 22; j++)
{

if (this.map[i][j] !== 3 && this.map[i][j] !== 4 && this.map[i][j] !== 2)
{

if (this.numOfBricks <= 60)
{
this.map[i][j] = Math.floor(Math.random() * 3);
this.numOfBricks++;
}
else this.map[i][j] = Math.floor(Math.random() * 2);
}
}
}
}

};

var mapIndex = 0;
var MAP1 = Object.create(MAP);
var MAP2 = Object.create(MAP);
var MAP3 = Object.create(MAP);
var MAP4 = Object.create(MAP);
var maps = [MAP1, MAP2, MAP3, MAP4];
maps[mapIndex].randomMap();


var spacePressed = false;
var upPressed = false;
var downPressed = false;
var leftPressed = false;
var rightPressed = false;
window.addEventListener("keydown", onKeyDown, false);
window.addEventListener("keyup", onKeyUp, false);

function animation()
{
if (player.positionX < 3) player.positionX++;
else player.positionX = 0
}


function fireAnimation()
{
if (player.positionX < 8) player.positionX++;
else player.positionX = 4;
}

function onKeyDown(e)
{
switch (e.keyCode)
{
case 37:
leftPressed = true;
animation();
player.positionY = 3;
break;
case 38:
upPressed = true;
player.positionY = 2;
animation();
break;
case 39:
rightPressed = true;
animation();
player.positionY = 1;
break;
case 40:
downPressed = true;
player.positionY = 0;
animation();
break;
case 32:
spacePressed = true;
shootingAudio.play();
fireAnimation();
break;
case 80:
if(gameStart === true)
{

gameStart = false;
gameTitle.style.display = "block";
startButton.style.display = "block";
settingButton.style.display = "block";
scoreButton.style.display = "block";
dialog.style.display = "none";
gameTitle.style.left = "44%";
canvas.style.filter = "opacity(50%) blur(10px)";
gameTitle.innerHTML = "Pause";
}
break;
//case 13:
//mapIndex++;
//break;

}
}

function onKeyUp(e)
{
switch (e.keyCode)
{
case 37:
leftPressed = false;
player.positionX = 0;
player.positionY = 3;
break;
case 38:
upPressed = false;
player.positionX = 0;
player.positionY = 2;
break;
case 39:
rightPressed = false;
player.positionX = 0;
player.positionY = 1;
break;
case 40:
downPressed = false;
player.positionX = 0;
player.positionY = 0;
break;
case 32:
spacePressed = false;
player.positionX = 0;
break;
}
}

function movePlayer()
{
if (leftPressed && player.positionY === 3 && maps[mapIndex].map[player.row][player.col - 1] !== 3 && maps[mapIndex].map[player.row][player.col - 1] !== 2)
{
player.col -= 1;
}

if (downPressed && player.positionY === 0 && maps[mapIndex].map[player.row + 1][player.col] !== 3 && maps[mapIndex].map[player.row + 1][player.col] !== 2)
{
player.row += 1;
}

if (rightPressed && player.positionY === 1 && maps[mapIndex].map[player.row][player.col + 1] !== 3 && maps[mapIndex].map[player.row][player.col + 1] !== 2)
{
player.col += 1;
}

if (upPressed && player.positionY === 2 && maps[mapIndex].map[player.row - 1][player.col] !== 3 && maps[mapIndex].map[player.row - 1][player.col] !== 2)
{

if(player.row === 1)
{
upLevelAudio.play();
mapIndex++;
for(var i = 8; i < 15; i++)
{
maps[mapIndex].map[0][i] = 3;
}
for (var i = 0; i < 22; i++)
{
for (var j = 0; j < 22; j++)
{
if(maps[mapIndex].map[i][j] === 2)
{
numOfBricks++;
}

if (maps[mapIndex].map[i][j] !== 3 && maps[mapIndex].map[i][j] !== 2 && maps[mapIndex].map[i][j] !== 4)
{

if (numOfBricks <= 40)
{
maps[mapIndex].map[i][j] = Math.floor(Math.random() * 3);
numOfBricks++;
}
else maps[mapIndex].map[i][j] = Math.floor(Math.random() * 2);
}
}
}
player.row = 21;
numberOfZombie = 10 + mapIndex * 2;
}
player.row -= 1;
}
}


var currentBullet = [];
var numOfBullets;
numOfBullets = 30;


function drawBullet() {
var bullet =
{
col: player.col,
row: player.row,
position: player.positionY,
//img: new Image()
};

if (spacePressed && currentBullet.length < numOfBullets)
{

currentBullet.push(bullet);
numOfBullets--;
var tick = 10;
if (numOfBullets === 0) {

var interval = setInterval(function () {
tick--;
text.innerHTML = tick + " seconds before filling up bullets";
if(tick === 0)
{
numOfBullets = 30;
text.innerHTML = "Try to kill all these enemies";
clearInterval(interval);
}
}, 1000);



}

}


for (var i = 0; currentBullet[i] !== undefined; i++)
{
switch (currentBullet[i].position)
{
case 0:
currentBullet[i].row++;
break;
case 1:
currentBullet[i].col++;
break;
case 2:
currentBullet[i].row--;
break;
case 3:
currentBullet[i].col--;
break;
}

if (currentBullet[i].row >= 0 && currentBullet[i].row < 21)
{

if (maps[mapIndex].map[currentBullet[i].row][currentBullet[i].col] === 2 || maps[0].map[currentBullet[i].row][currentBullet[i].col] === undefined)
{
if(maps[mapIndex].map[currentBullet[i].row][currentBullet[i].col] === 2)
{
brick.play();
var rate = Math.floor(Math.random()* 4);
/*if(rate === 0)
{
for(var j = 0; coins[j] !== undefined; j++)
{
for(var i = 0; i < 5; i++)
{
coins.push(new coin());
}
coins[j].col = currentBullet[i].col;
coins[j].row = currentBullet[i].row;
}
}*/
}

maps[mapIndex].map[currentBullet[i].row][currentBullet[i].col] = Math.floor(Math.random() * 2);
currentBullet.splice(i, 1);
}
} else
{
currentBullet.splice(i, 1);
}

}
}

var zombie = function ()
{

var spawningEnemy = Math.floor(Math.random()*4);
if(spawningEnemy === 0)
{
this.col = Math.floor(Math.random() * 3 + 8);
this.row = 1;
}else if(spawningEnemy === 1)
{
this.col = Math.floor(Math.random() * 3 + 8);
this.row = 20;
}else if(spawningEnemy === 2)
{
this.col = 2;
this.row = Math.floor(Math.random() * 3 + 8);
}else if(spawningEnemy === 3)
{
this.col = 20;
this.row = Math.floor(Math.random() * 3 + 8);
}

this.position = 0;
this.health = mapIndex + 1;
this.img = new Image();
this.img.src = "Images/newEnemies.png";
this.update_tick = 0 ;
this.move = function moveZombie() {


function followPlayer() {
while (player.col - this.col <= 5 && player.row - this.row <= 5) {
this.col++;
// this.position = 2;
}

while (player.row - this.row <= 5 && player.col - this.col <= 5) {
this.row++;

}

while (player.col - this.col >= 5 && player.row - this.row <= 5) {
this.col--;
//this.position = 3;
}


while (player.row - this.row >= 5 && player.col - this.col <= 5) {
this.row--;
//this.position = 1;
}

}
followPlayer();

switch (this.position) {
case 0:
if (this.row < 21 && maps[mapIndex].map[this.row + 1][this.col] !== 2 && maps[0].map[this.row + 1][this.col] !== 3) {


followPlayer();
this.row++;
setTimeout(function () {
this.position = Math.floor(Math.random() * 4);
}, 11);

}
else {
followPlayer();
this.position = Math.floor(Math.random() * 4);
}

break;

case 1:
if (this.row > 0 && maps[mapIndex].map[this.row - 1][this.col] !== 2 && maps[0].map[this.row - 1][this.col] !== 3)
{

followPlayer();
this.row--;

setTimeout(function () {
this.position = Math.floor(Math.random() * 4);
}, 11);

}
else {
followPlayer();
this.position = Math.floor(Math.random() * 4);
}


break;

case 3:
if (this.col > 0 && maps[mapIndex].map[this.row][this.col - 1] !== 2 && maps[0].map[this.row][this.col - 1] !== 3)
{

followPlayer();
this.col--;

setTimeout(function () {
this.position = Math.floor(Math.random() * 4);
}, 11);

}
else {
followPlayer();
this.position = Math.floor(Math.random() * 4);
}


break;
case 2:
if (this.col < 21 && maps[mapIndex].map[this.row][this.col + 1] !== 2 && maps[0].map[this.row][this.col + 1] !== 3)
{

followPlayer();
this.col++;
setTimeout(function () {
this.position = Math.floor(Math.random() * 4);
}, 11);
}
else {
followPlayer();
this.position = Math.floor(Math.random() * 4);
}

break;

}
}


};


var zombies = [];
var waitTime = 3;
var numberOfZombie = 7;

function moveZombies()
{
if (waitTime < 1 && numberOfZombie > 0 )
{
zombies.push(new zombie());
numberOfZombie--;
waitTime = Math.ceil(Math.random() * 60);
} else
waitTime--;

for (var i = 0; zombies[i] !== undefined; i++)
{
zombies[i].move();
}

}



function collision()
{
for (var j = 0; currentBullet[j] !== undefined; j++)
{
for (var i = 0; zombies[i] !== undefined; i++)
{


if ((zombies[i].col === currentBullet[j].col && zombies[i].row * 40 + 10 > currentBullet[j].row * 40  && zombies[i].row * 40 - 10 < currentBullet[j].row * 40 )
|| (zombies[i].row === currentBullet[j].row && zombies[i].col * 42 + 10 > currentBullet[j].col * 42 && zombies[i].col * 42 - 10 < currentBullet[j].col * 42)
|| (zombies[i].col === currentBullet[j].col && zombies[i].row === currentBullet[j].row)
)
{
zombies[i].health--;

explosionAudio.play();
currentBullet[j].col = 10000;
if (zombies[i].health === 0)
{
currentScore += 10;
text.innerHTML = "Kickass!!\n";
setTimeout(function () {
text.innerHTML = "Keep going!";
}, 5000);
zombies.splice(i,1);
}
}
}
}

for (var i = 0; zombies[i] !== undefined; i++)
{
if (zombies[i].col === player.col && zombies[i].row === player.row)
{
hitHurt.play();
health--;
if(currentScore > 0) currentScore -= 10;
text.innerHTML = "Ouch! \n";
setTimeout(function () {
text.innerHTML = "Don't lose focus!";
}, 5000);
}

resetLevel();
}

};

function resetLevel() {
if(health === 0 || tick === 0)
{

document.getElementById("timer").style.display = "none";
explosionAudio.play();
tick = 60;
gameStart = false;
mapIndex = 0;
numOfBullets = 30;
gameTitle.style.display = "block";
startButton.style.display = "block";
settingButton.style.display = "block";
scoreButton.style.display = "block";
dialog.style.display = "none";
gameTitle.style.left = "40%";
canvas.style.filter = "opacity(50%) blur(10px)";
if(health === 0) gameTitle.innerHTML = "GAME OVER, BABY! ";
else gameTitle.innerHTML = "TIME'S UP";
zombies = [];
numberOfZombie = 7;
currentScore = 0;
beginAudio.play();
numOfBricks = 0;
for(var i = 1; i < 3; i++)
{
for(var j = 8; j < 15; j++)
{
maps[mapIndex].map[0][j] = 3;
maps[mapIndex].map[i][j] = 4;
}
}
maps[mapIndex].map[13][9] = 2;
maps[mapIndex].map[15][15] = 2;
maps[mapIndex].map[17][6] = 2;
maps[mapIndex].map[3][7] = 4;
maps[mapIndex].map[3][9] = 4;
maps[mapIndex].map[3][13] = 4;
maps[mapIndex].map[4][9] = 4;
maps[mapIndex].map[4][6] = 4;
maps[mapIndex].map[4][10] = 4;

for (var i = 0; i < 22; i++)
{
for (var j = 0; j < 22; j++)
{
if(maps[mapIndex].map[i][j] === 2)
{
numOfBricks++;
}

if (maps[mapIndex].map[i][j] !== 3 && maps[mapIndex].map[i][j] !== 2 && maps[mapIndex].map[i][j] !== 4)
{

if (numOfBricks <= 40)
{
maps[mapIndex].map[i][j] = Math.floor(Math.random() * 3);
numOfBricks++;
}
else maps[mapIndex].map[i][j] = Math.floor(Math.random() * 2);
}
}
}
player.col = Math.floor(Math.random() * 19 + 1);
player.row = 18;
}
}

function updateLevel()
{


if (numberOfZombie === 0 && zombies.length === 0)
{
tick = 60 + 60 * (mapIndex+1);
numOfBricks = 0;
numOfBullets = 30;
openGateAudio.play();
for(var i = 8; i < 15; i++)
{
maps[0].map[0][i] = 4;
}

text.innerHTML = "Let go to level " + (mapIndex + 2);
health = 3;
}

}


update();

function update()
{
if(mapIndex === 3 && zombies.length === 0 & numberOfZombie === 0)
{
window.alert("CONGRATULATION YOU WIN !!!");
gameStart = false;
}
updateLevel();
ctx.clearRect(0, 0, canvas.height, canvas.width);
for (var i = 0; i < 22; i++)
{
for (var j = 0; j < 22; j++)
{

switch (maps[mapIndex].map[i][j])
{
case 0:
case 4:
ctx.drawImage(maps[mapIndex].img, 0, 46 * mapIndex, 48, 46, 42 * j, 40 * i, 42, 40);
break;
case 1:
ctx.drawImage(maps[mapIndex].img, 48, 46 * mapIndex, 48, 46, 42 * j, 40 * i, 42, 40);
break;
case 2:
ctx.drawImage(maps[mapIndex].img, 144, 46 * mapIndex, 48, 46, 42 * j, 40 * i, 42, 40);
break;
case 3:
ctx.drawImage(maps[mapIndex].img, 96, 46 * mapIndex, 48, 46, 42 * j, 40 * i, 42, 40);
break;

}

}
}

if (gameStart)
{

movePlayer();
ctx.drawImage(playerImage, 32 * player.positionX, 35 * player.positionY, 32, 35, 42 * player.col, 40 * player.row, 38, 39);

moveZombies();
for (i = 0; zombies[i] != undefined; i++)
{
ctx.drawImage(zombies[i].img, 46 * (zombies[i].health - 1) , 0, 46, 46, zombies[i].col * 42, zombies[i].row * 40, 41, 41);
}

drawBullet();
for (var i = 0; currentBullet[i] !== undefined; i++)
{
ctx.drawImage(bulletImage, 0, 0, 48, 48, currentBullet[i].col * 42, currentBullet[i].row * 40, 20, 20);
}

collision();
score.innerHTML = "Score: " + currentScore;
/*for(var i = 0; coins[i] !== undefined; i++)
{
setInterval(coins[i].angle++, 500);
if(coins[i].angle > 3) coins[i].angle = 0;
ctx.drawImage(coinImage, 30 * coins[i].angle, 0, 27, 33, coins[i].col * 42, coins[i].row * 40, 20, 20);
}*/

}
if(numOfBullets <= 0 || numOfBullets === null) document.getElementById("progress").value=0;
else document.getElementById("progress").value=numOfBullets;

document.getElementById("health").value=health;
setTimeout(function () {requestAnimationFrame(update);}, 1000 / 10);
}





</body>
<html/>
