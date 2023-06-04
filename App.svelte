<script>
    let welcomes = [
        "Welcome to APC del Noroeste", // English
        "Bienvenidos a APC del Noroeste", // Spanish
        "欢迎来到 APC del Noroeste", // Chinese
        "APC del Noroesteへようこそ", // Japanese
        ".... . .-.. .-.. --- / - --- / .- .--. -.-. / -.. . .-.. / -. --- .-. --- . ... - .", // Morse
        "nuqneH APC del Noroeste", // Klingon
        "Mae g'ovannen APC del Noroeste", // Elvish
        "Bem-vindo à APC del Noroeste", // Portuguese
        "Bienvenue à APC del Noroeste" // French
    ];
    let currentIndex = 0;

    setInterval(() => {
        currentIndex = (currentIndex + 1) % welcomes.length;
    }, 3000);
</script>

<style>
    main {
        text-align: center;
        padding: 1em;
        max-width: 240px;
        margin: 0 auto;
        font-size: 1em;
    }
</style>

<main>
    <h1>{welcomes[currentIndex]}</h1>
</main>
