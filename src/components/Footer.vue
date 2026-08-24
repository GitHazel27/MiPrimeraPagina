<template>
    <footer id="contacto" class="footer">
        <div class="redes">
            <a href="https://www.facebook.com/share/1EVEG6gpSL/" target="_blank">
                <svg width="50px" height="50px" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path fill-rule="evenodd" clip-rule="evenodd" d="M2 6C2 3.79086 3.79086 2 6 2H18C20.2091 2 22 3.79086 22 6V18C22 20.2091 20.2091 22 18 22H6C3.79086 22 2 20.2091 2 18V6ZM6 4C4.89543 4 4 4.89543 4 6V18C4 19.1046 4.89543 20 6 20H12V13H11C10.4477 13 10 12.5523 10 12C10 11.4477 10.4477 11 11 11H12V9.5C12 7.567 13.567 6 15.5 6H16.1C16.6523 6 17.1 6.44772 17.1 7C17.1 7.55228 16.6523 8 16.1 8H15.5C14.6716 8 14 8.67157 14 9.5V11H16.1C16.6523 11 17.1 11.4477 17.1 12C17.1 12.5523 16.6523 13 16.1 13H14V20H18C19.1046 20 20 19.1046 20 18V6C20 4.89543 19.1046 4 18 4H6Z" fill="#ff0586"/>
                </svg>
            </a>
            <a href="https://www.instagram.com/hazelsp27?igsi=MTU5Z3c1Mmo4czEycw==" target="_blank">
                <svg width="70px" height="70px" viewBox="0 -0.5 25 25" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path fill-rule="evenodd" clip-rule="evenodd" d="M15.5 5H9.5C7.29086 5 5.5 6.79086 5.5 9V15C5.5 17.2091 7.29086 19 9.5 19H15.5C17.7091 19 19.5 17.2091 19.5 15V9C19.5 6.79086 17.7091 5 15.5 5Z" stroke="#ff0586" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                <path fill-rule="evenodd" clip-rule="evenodd" d="M12.5 15C10.8431 15 9.5 13.6569 9.5 12C9.5 10.3431 10.8431 9 12.5 9C14.1569 9 15.5 10.3431 15.5 12C15.5 12.7956 15.1839 13.5587 14.6213 14.1213C14.0587 14.6839 13.2956 15 12.5 15Z" stroke="#ff0586" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                <rect x="15.5" y="9" width="2" height="2" rx="1" transform="rotate(-90 15.5 9)" fill="#ff0586"/>
                <rect x="16" y="8.5" width="1" height="1" rx="0.5" transform="rotate(-90 16 8.5)" stroke="#ff0586" stroke-linecap="round"/>
<               </svg>
            </a>
        </div>
    </footer>
</template>

<script lang="ts" setup>
</script>

<style scoped>

footer{
    font-family: sans-serif;
    font-weight: bold;
    bottom: 0;
    z-index: 1000;
    background-color: #030303;
    box-shadow: 0 -4px 15px rgba(0, 0, 0, 0.2);
}

.redes{
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 20px;
    padding: 20px 0;
}

a:hover{
    transform: scale(1.1);
    transition: transform 0.3s ease-in-out;
    background-color: #000;
}

</style>