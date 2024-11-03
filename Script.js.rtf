{\rtf1\ansi\ansicpg1252\cocoartf2818
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 let taskInterval;\
let elapsedTime = 0;\
let isRunning = false;\
\
const startButton = document.getElementById('startTask');\
const pauseButton = document.getElementById('pauseTask');\
const stopButton = document.getElementById('stopTask');\
const taskNameInput = document.getElementById('taskName');\
const currentTaskName = document.getElementById('currentTaskName');\
const currentTaskTime = document.getElementById('currentTaskTime');\
const taskList = document.getElementById('taskList');\
\
function formatTime(seconds) \{\
    const hrs = String(Math.floor(seconds / 3600)).padStart(2, '0');\
    const mins = String(Math.floor((seconds % 3600) / 60)).padStart(2, '0');\
    const secs = String(seconds % 60).padStart(2, '0');\
    return `$\{hrs\}:$\{mins\}:$\{secs\}`;\
\}\
\
function startTask() \{\
    if (isRunning) return; // prevent multiple intervals\
    if (!taskNameInput.value) \{\
        alert('Please enter a task name.');\
        return;\
    \}\
\
    isRunning = true;\
    currentTaskName.textContent = taskNameInput.value;\
    taskInterval = setInterval(() => \{\
        elapsedTime++;\
        currentTaskTime.textContent = formatTime(elapsedTime);\
    \}, 1000);\
\}\
\
function pauseTask() \{\
    clearInterval(taskInterval);\
    isRunning = false;\
\}\
\
function stopTask() \{\
    if (elapsedTime > 0) \{\
        const li = document.createElement('li');\
        li.textContent = `$\{taskNameInput.value\} - $\{formatTime(elapsedTime)\}`;\
        taskList.appendChild(li);\
    \}\
    clearInterval(taskInterval);\
    isRunning = false;\
    elapsedTime = 0;\
    currentTaskName.textContent = 'None';\
    currentTaskTime.textContent = '00:00:00';\
    taskNameInput.value = '';\
\}\
\
startButton.addEventListener('click', startTask);\
pauseButton.addEventListener('click', pauseTask);\
stopButton.addEventListener('click', stopTask);\
}