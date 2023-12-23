
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color:  green;
        }

        header {
            background-color: green;
            color: white;
            text-align: center;
            padding: 1em;
        }

        section {
            max-width: blue;
            margin: 2em auto;
            padding: 1em;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        button {
            background-color: hex;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        button:hover {
            background-color: hex;
        }

        .info:hover::after {
            content: attr(data-info);
            background-color: darkcharcoal;
            color: white;
            padding: 5px;
            border-radius: 4px;
            position: absolute;
            z-index: 1;
            margin-top: 10px;
        }
    </style>
</head>
<body>

    <header>
        <h1> MAHNOOR</h1>
    </header>

    <section>
        <h2>About Me</h2>
        <p>CYS STUDENT AT AIR UNIVERSITY KAMRA HOPE TO GIVE YOU NICE RESPONSE ...</p>
        <button id="downloadBtn"><a href="https://images.search.yahoo.com/images/view;_ylt=Awrig6hZjHplOg4ODdKJzbkF;_ylu=c2VjA3NyBHNsawNpbWcEb2lkAzEwM2EwYWFjZGY2MGVlY2E5NDhmZjU1NzU3YTI3ZGQxBGdwb3MDMQRpdANiaW5n?back=https%3A%2F%2Fimages.search.yahoo.com%2Fsearch%2Fimages%3Fp%3Dcv%2Bpdf%26type%3DE210US91215G0%26fr%3Dmcafee%26fr2%3Dpiv-web%26tab%3Dorganic%26ri%3D1&w=600&h=818&imgurl=images.template.net%2Fwp-content%2Fuploads%2F2018%2F11%2FFree-Professional-Resume-Template.jpg&rurl=https%3A%2F%2Fwww.template.net%2Fbusiness%2Fresume%2Fcv-template%2F&size=65.0KB&p=cv+pdf&oid=103a0aacdf60eeca948ff55757a27dd1&fr2=piv-web&fr=mcafee&tt=52%2B+Sample+CV+Templates+-+PDF%2C+DOC&b=0&ni=21&no=1&ts=&tab=organic&sigr=hqmrLtvI1kP0&sigb=Emyu9UZj18FZ&sigi=nfdy0O_UM9G9&sigt=uwnkgO6KEFs8&.crumb=ATx6ypmPWGY&fr=mcafee&fr2=piv-web&type=E210US91215G0">Download Resume</a></button>
    </section>

    <section class="info" data-info="Details about your services">
        <h2>Services</h2>
        <ul>
            <li>Service 1</li>
            <li>web development</li>
            <li>software development</li>
            <li>Service 2</li>
            <li>DBMS</li>
            <li>C++</li>
           
        </ul>
    </section>

    <section class="info" data-info="Contact information">
        <h2>Contact</h2>
        <p>Email: manoshk78@email.com</p>
        <p>Phone: 03235061298</p>
    </section>

    <script>
        document.getElementById('downloadBtn').addEventListener('click', function() 
    </script>

</body></html>
