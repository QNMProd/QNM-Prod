<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Niko</title>
    <link rel="Icon" href="images/OIP.jfif">
    <link href='https://fonts.googleapis.com/css?family=Lato:300,400,700,400italic' rel='stylesheet' type='text/css' />

    <link href="//fastmobileporndelivery.hqporner.com/css/framework.css" rel="stylesheet" type="text/css" media="all" />
    <link href="//fastmobileporndelivery.hqporner.com/css/colorbox.css" rel="stylesheet" type="text/css" media="all" />
    <link href="//fastmobileporndelivery.hqporner.com/css/elements.css" rel="stylesheet" type="text/css" media="all" />
    <link href="//fastmobileporndelivery.hqporner.com/css/style.css" rel="stylesheet" type="text/css" media="all" />
    <link href="//fastmobileporndelivery.hqporner.com/css/responsive.css" rel="stylesheet" type="text/css"
        media="screen" />
    <link href="//fastmobileporndelivery.hqporner.com/css/hidpi.css" rel="stylesheet" type="text/css" media="screen" />

    <script type="text/javascript" src="//fastmobileporndelivery.hqporner.com/js/jquery.min.js"></script>
    <script type="text/javascript">
    //$(document).ready(function(){
    //	if ($('#loadcontrol').html().trim().length > 500) {
    //		document.getElementById("loadcontrol").style.display = 'block';
    //	}
    //});
    </script>
    <!--<script type="text/javascript" src="/js/change-m.js"></script>-->
    <script type="text/javascript" src="//fastmobileporndelivery.hqporner.com/js/effects.jquery-ui.min.js"></script>
    <script type="text/javascript" src="//fastmobileporndelivery.hqporner.com/js/jquery.colorbox.min.js"></script>
    <script type="text/javascript" src="//fastmobileporndelivery.hqporner.com/js/custom.js"></script>
    <script type="text/javascript" src="//fastmobileporndelivery.hqporner.com/js/cookies.js"></script>

    <link rel="stylesheet" href="//fastmobileporndelivery.hqporner.com/css/font-awesome/css/font-awesome.min.css">

    <style>
        .video-container {
            position: relative;
            padding-bottom: 56.25%;
            padding-top: 0px;
            height: 0;
            overflow: hidden;
            background: #000;
        }

        .video-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }

        i {
            margin-right: 6px;
            margin-top: 6px;
        }

        .meta_data {
            margin-right: 12px;
            margin-top: 6px;
        }

        .fol {
            padding: 6px 12px;
            background: #333;
            margin: 6px 6px 0 0;
            float: left;
        }

        .pornstars {
            padding: 24px 0 0 0;
        }

        .pornstars a {
            color: #666 !important;
            border-bottom: 1px dotted #666;
            text-decoration: none !important;
        }

        .pornstars a:hover {
            border-bottom: 0px dotted #666;
        }

        @keyframes blink {
            0% {
                opacity: .2;
            }

            20% {
                opacity: 1;
            }

            100% {
                opacity: .2;
            }
        }

        .loading_dots span {
            animation-name: blink;
            animation-duration: 1.4s;
            animation-iteration-count: infinite;
            animation-fill-mode: both;
        }

        .loading_dots span:nth-child(2) {
            animation-delay: .2s;
        }

        .loading_dots span:nth-child(3) {
            animation-delay: .4s;
        }

        .loading_dots {
            padding: 15px 20px;
            font-size: 14px;
            color: #666;
        }

        .altPlayerButton {
            padding: 6px 12px;
            background: #333;
            display: inline-block;
        }
    </style>

    <script type="text/javascript">
        function altPlayer() {
            $.ajax({
                url: '/blocks/altplayer.php?i=//mydaddy.cc/video/5aa99ed4dc2312e3ca/',
                cache: false,
                beforeSend: function () { $('#playerWrapper').html('<h3 class="loading_dots">One moment <span>.</span><span>.</span><span>.</span></h3>'); },
                success: function (html) {
                    $('#playerWrapper').innerHTML = '';
                    $('#playerWrapper').html(html);
                }
            });
            $('#linkAltPlayer').attr('onclick', 'nativePlayer();this.innerHTML = \'Go to alternative player\';return false;');
            return false;
        }

        function nativePlayer() {
            $.ajax({
                url: '/blocks/nativeplayer.php?i=//mydaddy.cc/video/5aa99ed4dc2312e3ca/',
                cache: false,
                beforeSend: function () { $('#playerWrapper').html('<h3 class="loading_dots">One moment <span>.</span><span>.</span><span>.</span></h3>'); },
                success: function (html) {
                    $('#playerWrapper').innerHTML = '';
                    $('#playerWrapper').html(html);
                }
            });
            $('#linkAltPlayer').attr('onclick', 'altPlayer();this.innerHTML = \'Back to native\';return false;');
            return false;
        }
    </script>

</head>

</head>

<body>
    <div class="video-container" id="playerWrapper">
        <h3 class="loading_dots">Loading may take some time <span>.</span><span>.</span><span>.</span></h3>
        <iframe src="//mydaddy.cc/video/5aa99ed4dc2312e3ca/" width="640" height="360" frameborder="0" scrolling="no"
            allowfullscreen=""></iframe>
    </div>
</body>

</html>
