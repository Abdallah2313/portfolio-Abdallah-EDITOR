const cylinder = document.querySelector('.cylinder');

cylinder.addEventListener('mouseover', () => {
    cylinder.style.animationPlayState = 'paused';
});

cylinder.addEventListener('mouseout', () => {
    cylinder.style.animationPlayState = 'running';
});
