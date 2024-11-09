.ring i:nth-child(1) {
    border-radius: 38% 62% 63% 37% / 41% 44% 56% 59%;
    animation: animate 6s linear infinite;
}

.ring:hover i:nth-child(1) {
    border: 6px solid lawngreen;
    filter: drop-shadow(0 0 20px lawngreen);
}

.ring i:nth-child(2) {
    border-radius: 41% 44% 56% 59% / 38% 62% 63% 37%;
    animation: animate 8s linear infinite;
}

.ring:hover i:nth-child(2) {
    border: 6px solid red;
    filter: drop-shadow(0 0 20px red);
}

.ring i:nth-child(3) {
    border-radius: 41% 44% 56% 59% / 38% 62% 63% 37%;
    animation: animate2 10s linear infinite;
}

.ring:hover i:nth-child(3) {
    border: 6px solid yellow;
    filter: drop-shadow(0 0 20px yellow);
}

@keyframes animate {
    /* Define keyframes for the animation */
}

@keyframes animate2 {
    /* Define keyframes for the second animation */
}
