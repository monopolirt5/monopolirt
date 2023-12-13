<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon Blog Reddit</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        h1 {
            color: #FF4500;
        }
        p {
            line-height: 1.6;
        }
        a {
            color: #4169E1;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .blog-section {
            display: none;
        }
        .active {
            display: block;
        }
    </style>
</head>
<body>

    <h1>Mon Blog Reddit</h1>

    <nav>
        <ul>
            <li><a href="#section1" onclick="showSection('section1')">Section 1</a></li>
            <li><a href="#section2" onclick="showSection('section2')">Section 2</a></li>
            <li><a href="#section3" onclick="showSection('section3')">Section 3</a></li>
        </ul>
    </nav>

    <!-- Section 1 -->
    <div id="section1" class="blog-section active">
        <h2>Reddit - Réseau Social</h2>
        <p>Reddit est un réseau social créé en 2005. Il permet aux utilisateurs de partager des contenus sous forme de textes, de liens, d'images et de vidéos, ainsi que de commenter et voter sur ces contenus.</p>
        <img src="https://www.google.com/imgres?imgurl=https%3A%2F%2Fwww.1min30.com%2Fwp-content%2Fuploads%2F2019%2F06%2Fshutterstock_1094702246-1.jpg" alt="Image 1">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSYjDBIvDWNCrPVAOx9wLDlxZbUApp1ii4jmQ&usqp=CAU" alt="Image 2">
    </div>

    <!-- Section 2 -->
    <div id="section2" class="blog-section">
        <h2>Les Utilisateurs de Reddit</h2>
        <p>a) Les utilisateurs de Reddit sont des personnes de + 13 ans minimum, des entreprises, des organisations, des associations, des groupes de discussion, des communautés virtuelles, etc. Les créateurs sont Steve Huffman, Alexis Ohanian et Aaron Swartz.</p>
        <p>b) Les utilisateurs peuvent établir des relations de toutes sortes sur Reddit, notamment des relations d'amitié, de collaboration, de coopération, de compétition, de conflit, d'échange, de partage, de soutien, etc.</p>
        <p>c) Sur Reddit, il est possible de partager toutes sortes de contenus, qu'ils soient publics ou privés, avec ou sans accès restreint, en direct ou de manière différée, de manière éphémère ou persistante. Les utilisateurs peuvent également réagir aux contenus en les commentant, en les votant, en les signalant, en les partageant, etc.</p>
        <img src="https://cdn.arstechnica.net/wp-content/uploads/2021/08/getty-reddit-icon-800x533.jpg" alt="Image 3">
        <img src="https://www.google.com/imgres?imgurl=https%3A%2F%2Fwww.1min30.com%2Fwp-content%2Fuploads%2F2019%2F06%2Fshutterstock_1094702246-1.jpg" alt="Image 4">
    </div>

    <!-- Section 3 -->
    <div id="section3" class="blog-section">
        <h2>Reddit en tant que plateforme</h2>
        <p>d) Reddit est une plateforme Web qui peut être utilisée à partir d'un navigateur Internet, mais il existe également des applications mobiles pour iOS et Android qui permettent d'accéder à Reddit depuis un smartphone ou une tablette.</p>
        <img src="http://cdn.statcdn.com/Infographic/images/normal/11860.jpeg" alt="Image
        <img src="http://cdn.statcdn.com/Infographic/images/normal/11860.jpeg" alt="Image 5">
        <img src="https://pbs.twimg.com/media/GAwxRv9XMAAqxmw.jpg" alt="Image 6">
    </div>

    <script>
        function showSection(sectionId) {
            // Masquer toutes les sections
            var sections = document.querySelectorAll('.blog-section');
            sections.forEach(function (section) {
                section.classList.remove('active');
            });

            // Afficher la section sélectionnée
            var selectedSection = document.getElementById(sectionId);
            if (selectedSection) {
                selectedSection.classList.add('active');
            }
        }
    </script>

</body>
</html>

