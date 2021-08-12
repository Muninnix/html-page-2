# html-page-2
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style-P2.css">
    <title>Page d'annonce</title>
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css"
      integrity="sha512-1ycn6IcaQQ40/MKBW2W4Rhis/DbILU74C1vSrLJxCq57o941Ym01SwNsOMqvEBFlcgUa6xLiPY/NS5R+E6ztJQ=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />
    <link href="http://fonts.cdnfonts.com/css/days" rel="stylesheet">
</head>

<body>
    <header>
        <div class="btnMenuLeft">
            <h1 class="itemMenu textMenu">Freedom Family</h1>
            <div class="btnAnnonce itemMenu">
                <p class="annonceBtnMenu"><i class="far fa-plus-square"></i> Ajouter une annonce</p>
            </div>
            <div class="btnRecherche itemMenu">
                <p class="rechercheBtnMenu">Recherche</p>
            </div>
        </div>
        <div class="btnMenuCenter"></div>
        <div class="btnMenuRight">
            <div class="btnFavoris">
                <i class="fas fa-heart"></i>
            </div>
            <div class="btnCategories itemMenu">
                <i class="fas fa-clipboard-list"></i>
            </div>
            <div class="btnProfil itemMenu">
                <i class="fas fa-address-book"></i>
            </div>
        </div>
    </header>
    <div id="cadre_principale">
        <!-- div de mise à niveau pour photo et cadre-->
        <div id="mis_niv">
            <div id="photo">
                <img id="photo_int"
                    src="https://images.frandroid.com/wp-content/uploads/2020/04/model-s-performance-1200x750.jpg"
                    alt="photo_anonce" height="300" width="450">
            </div>
            <div id="cadre_contacte">
                <h1 id="contacte">Contacte</h1>
                <div id="bande"></div>
                <h2 class="info">Tel :</h2>
                <h2 class="info">Email :</h2>
            </div>
        </div>
        <div id="group_img">
            <img id="img_photo"
                src="https://cdn.discordapp.com/attachments/746874144783728813/874616737042157608/Capture_du_2021-08-10_15-33-26.png"
                alt="">
            <img id="img_partage"
                src="https://media.discordapp.net/attachments/746874144783728813/874616760534433823/Capture_du_2021-08-10_15-33-46.png"
                alt="">
            <img id="img_like"
                src="https://cdn.discordapp.com/attachments/746874144783728813/874616779861819512/Capture_du_2021-08-10_15-33-36.png"
                alt="">
        </div>
        <div id="text_1">
            <h1>Titre de l'annonce</h1>
            <h2>ville, code postal</h2>
            <h2>Rue</h2>
        </div>
        <div id="text_2">
            <h3>Prix</h3>
            <h4>Date de la mise en ligne de l'annonce</h4>
        </div>
        <div id="des">
            <h1>Description</h1>
            <div id="des_b">
                <p id="pp">Bla bla bla...</p>
            </div>
        </div>
    </div>
</body>

</html>
