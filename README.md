# google-page-clone
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Google</title>
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="page">
        <!--nav header-->
        <nav>
            <div class="nav-left">
                <a  href="#">About</a>
                <a  href="#">Store</a>
            </div>

            <div class="nav-right">
                <a  href="#">Gmail</a>
                <a  href="#">Images</a>
                <i class="material-icons">apps</i>
                <img src="assets/Screenshot 2024-04-13 131916.png" style="width:40px;height:40px;">
            </div>
        </nav>

        <!--google image-->
        <img class="google-image"src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAYIAAACCCAMAAAB8Uz8PAAAA8FBMVEX///9ChfTqQzX7vAU0qFM6gfTm9OrL59IZokIlpUk+g/T7uQA1f/SLsPdnnPbqPzDpNybqPS7pOSnpMyGwyPovfPOsxPlyvoTu+PAtpk5woff//v5akvX+9/b5+//pLxvh6/3V4vxMjPXvenLH2fvx9v784+HrTkHtZFro8P7//vf9243znZfrSTvylY/85ePsV0v/+er4x8Tub2b1qqXP3/xWkfWcvPm60Pp+qPf61NH3vbnxhn/80277wy795KjvdGuFrvf+6bf0pqH+8dH8zl38yUT+7sn+9d/2tLD92Yf93p/81HX7wx78y1DuaF41My6zAAASdklEQVR4nO1deV/azBYWvbm3N4SshPu+7PuigojKrhWttrS1fv9vc0nY5sweILav5vn1L4TpTJ4558zZJkdHQZBvlUo3N6VSsRboZxEOgdZwkO5r7hYxPZG8yf/uaX0U1IazsqspagyFqiqaq+mDUkRD2KgldU2DTx8lQnHLidLvnuO7xs0opims57+C4urDDyQKf/0PxX9C/t+GOq5+GLKglVMfxkD/+9PfW3wKl4Jq1pV5/kto5WSok/lz8O9P/9riv2FSUEqzLQCdBP1j2IS3oiA/kNJAAIqS+Agm4Y0oKPWDM+Adj/rFsGb05+BtKBgE1EEICe/fIrwFBXld240AjwM3Ecqc/iC8AQXFMs8R8MVD5QiJpocxqT8I4VNww7QCqrL1ElS2x6z037eLEDoFVboSUhWlrA+qpVZtcejJ11qlampUjlEdN1UpHn5afxDCpqBK9cYUJUsLxxWT6RghDGqsePBZ/VEImQIqA1qMHYhrpfqQhHfPQMgUlCiGWIkNWrzf5IdZhIT3z0C4FLRihAwsPF4uAR7yKXVNnVouHnZKfyDCpCCfJRjQslJxn9bI/TAMhErBCFdDqjuQ/W3SU0YfgoEwKUjix1FVq8r/euHQfQA74CE8ClqkHRZaARS1rFo84HT+XIRHgY4ZArUc0MnNB2Lsn4vQKBi6ezLwYRAWBbUyzsAH2dPBERYFA8wWfxC9vgtCogB3yrThoUZ+fwiJggR0CbR3n3fZA+FQgAmBmv0IafhdEQ4FmCVQArhkHw+hUJCHxyFldJhh3ylCoaAKfAI1Og1xEQoFI2AJlNlhRn2vCIOCGrQEkRDwEQYFQ0CBmj7IoJLIjSfXnel02nmc9y52HOP068OP77e3tz/PPj9823GMYjU5mM1mg2RVGBUIQkG9t1hdZTo9n49zvO9BPRQkQr0fcpNpu+A4pm1Zlm2bTsG5uq4HHOP04edLHOD5x5eAY7SSadfVNMWDprnlxA3367IU1B+bhQKyukZnzPwudArKb+MTZHqVgmMdQ1hmoXvN3S4QX28Xz/wEQzz+chZAGIa6izWxKG45uXwIVT29gZ5a/UCKgty8WTANsDjDLrTP6YsrgvPQ2xjj3LxRwJ//aqKmOZUThdPPd+TzX7PwJCcK+WGfWrWjlf0ITdJVNtDWD0aCgty5jT3/9eJsKgkwW/YWeigzaTi0Ga5gmx0JSXi4Yzz/FQm3EpLAaWJx0y34aJR10EZMwbxtMhdntifkD0B8SFXDD1LXr3gE+CQcU+YJ8O2JR4BPwskPwRi1Ga+AXCmXdqPggr88o1AhNhism+jLPcY9MLfoKgiAMk8UDyciBjwSnrmCUOKWL3slUaXhDhT02qLl2Q1c0wI9FLopyEwdMQHUeSL4LkGALwhf2WMMhU0sahlN5kpS8Eg1AhDWMTwb5YE11kJu0ci9stUkhGH0WIMIldCWhM+sMVIu/sSpghCUgo7UBjMswAE8EIVsjXNdW5IB7xDH4OCXNAMLDhgGAc8SiiFFgRwD3v5CZfwGUiBRPTfS5ZEFRQCZroQZQDig+jJBGGDJAVEzdRgKrgvSa2sgtg42FCjiA1G+r6jScAGl91QZMBb+I1WBGseUmMVPpi/A+JxiD4bUo5Dqr2sPCsY0BizbNE2bWJ/1ik4H/Efi0hVK6SkbIAl9ToqpYTpm975y/2o4JikhVpc4F/2gPOmFi/zy/PTr+YTiKy9wiY/RoixA0bRsejTSY6z2ITEFOZIBy7Gvzufzeadp4stzOiwKxOGJQBQoqe0PewQDltmdr5VirlexCCExp9h//o1CwMsmKnT5cEueVuO/hAvwLnBYi2trqFPPSmIKrvA9ZNvTjSrN9K6ws5K5+VvIFGwLg3MNTBoN8x4q+9z5MU6Cg5nkZ/wJx5+hojn9QZCAmwPCFGtZeAgpjiimQkhBr4Avbwr16BieRazmWsRDpmDrZ3Sw46jdIE88FxXsSwZURbgaip+Q1vbylhAEoIqKmL5XVfIgXqV0WggoyGA7zGoQh4nMFKzOuV59Hq4tUDd56AtMBky6/3uNWa7NPP2n+4KLANX//YyLwU/0r2ksLkq9MaCVxV1nEQVzuHnsV9rypqgcGO3VV7ATEW0+EMEo2CSAplDHOLiWX6OHadQ2spQzuL/jT6f0Mb7iYoAwdYNVi2Tpm66mYxwIKMCEwL7K0EbNNdFvmY/LT0tB/YLdKMCEgLCzW0wgV+ZWDDAhiP9iMEBwgIpBGpZM9Vmn8FofLlNAQQ8IgdWkMrCwB0AMVs5BC1IgrmTcTRGdY1PkROEewVeN7mY1n6EQvBCnzS2wr55syCpilrbIHKIED0YCCuBxyKAnYTO9CtiJziogDDM24tamncxxrgv+b4ublYHLKWzM2i+4tTkxuKMjaJO3hyJYuskNicGTE5+CC+qjhbi47mLOwdo/g49MnLwPRsFq4mPgE5jn3P+hDlSRvdZZ3+BTveWOcQmlYO0bwKo1lXtfBiz451MAjLHRpIw2nh6TQdTCcitiJwTuwpar8DLd2iahhwMMt5aqDk0HMoGZ7tWnmDEWZMXgt+MrTXQTJCgJIkl8Ciro9sadGS9P2DVpwRl76SIP4DMr8lfmzSyFIkkAFZKVpGfAScDmCwEuBmtNBGLU8SfBGFAM4g9H5GLVLH8IIAZcCoCeJXbYRYeeSl54bwX/q/BUun/CoIWOt9pnOahahBVD8Ow29z87DWAJPEDGvi8/1Cn7g40ZQhiXArBn7A4YpHdVoEfoLaexKhepwYrSva8TApSuIqXAFBivghEw1WotjQE0BXfMA+kaD+D7z/5nedQzVoUtpVXZxCUIf6F6KPfYppeKGLZ9v/0eOACL5yVCCpV1dxnwuEYfqVAPYbvK6PqfPQTSQ4RB9j8D+SmRHoJ9F1wKztH5mmshz4ynDl0DWWbjHFUF0BhoqaP9AN3K5WfAGpPWigSYsOl/BOwrOyO5xR1pj4dUA8tGVpKCKbLT16bAq+aiZ6hs+3UCzQU8JYj3hgBohGvtHIMDA98pWAIYg6XNAjl7sSnAjYEf0AYSKuGGpiUpuEcp8D3jeseg17IYTrtDPACsw2PP9PENuspVuiADnK22RP0uuq2OC/4PYLpMolqOwhkQeI1fO+oBceS4FLwiT9u6OspNrhy6Cbad5px2IoeaaE+DDAZzl6sEZ1KDTIWRAJpr6cDAugmJWjkQ2V6eSoFvrIjjYQNJCsD6mucNolp2+RfTmI7pwSMYqduz1QyIlLa0xsEpAPZt6Rg8AevKiQ+t8VlAgUQjRWprO3gUQLfHIDPFvnQ43Wu2/MP7J/ZquARH0nW4Y18pWFJwaClQxVKQkpMCSAEVtlPpMaKnPrALKPY5FIHz0HqgzCsqmKLwhAdoC3xFdBuUgrO3U0SvfAoWlvlcYADzMDa+R8MfMMYxd+1jgBMRrTQFx6voRCRhjm9F5liscGeSFNzz6qPsQnPCE4Alkpg12PlgCoRga9hB3M1hd5ts0EbXUPA/omxqPqBf4BsPGHgTC7u+g1+ACYBZkOuXwMRg5xsQsF6FzcEbeo/XvCF8XMDAqv8ZtK78ULUHLKbk70PQ3ivuqkPjdPLeMQLLaVDPoDQMsWSSu1O0rggHiW3SsiCGYt0LBwJpQKvif/aFEvPh4SuMKfmfwXiYsKerJBumI0ukfAGwKhICvwF+KZe7w8kUS+YgGbgLMEWxbwZsh73McsNdLfbNgCu3yh5DL1QR+WYp2TBdnVIJaDYeg/WQlvDqmuBOch4mf9CGHZi3dOaCkXIwDbiKKYG85Tr6zMQpyPWvY0qgu1TYTCHdX4DlZReugXXPPYNSQVwKFfROojxWgwaiYMBeGaz6gjVgAt9caVPY2MFL3nuACfz46hCLKVx+VBjGWuSzZgvXhwwDSYBICatuIPegRrx4Al0fVJYmv5Us10b31MoU4MYgfsYd4xSch1am4OioRU2rMgDqXfgUTGCdHD8WzNyARSIr787k3eRiHyt9gv5dDpwyBQ4ycI235QjYU+V7Z2cMvsBj5TtAVUgXv4IC2gF+Uuqc2VFK9j0ocvclLzDEizBVHdI3pVdF0NCDJzxjM1+oiYiKaRRfIFvxDV1DlzdLFPjhgl9HBDUR19r1HLPLOiklCA5UdSAjCDWiFFnFAzBjWHLpsH2DehuWBm4zsVhlOywVBbiEAoPk2PC7l9gO0Eyhf5NOAbY+k20L6sfGwlyzBAGvo/Q6T8piq5yMEb8jw0xY9T292mmBC6wZykFOdljNNNMcnGI18GiCJwV3i8YyB/jxRFTWC89ERpulay6WxadMQehTqrQ0Pgn5ZJmsxtfIi73GmPfCkIN6AzIAVBbe4MGQg29YYz5QWfiNrIxAwADvyBRRgHlnFiMYOT5eUWWYHapZzpdpL6fR1ESROt7CCidUWjsELcZUwTt9KpQpzPF0twXcG7zRLP5MOZo+YERhMT0sHhbTdLK2Oj8iemKFLR5NuD6ssXWFa2R9JtmB4KFGbUlXFTeWqOIzrVUTMZf6QiGq539B3LtCKKP6K96uhcnKJfF0CWX0jejIxGWFuJ2b0JpVUrOKKajjcy8Q+r7+CkTFIL/hP1eit2E9Bc0tjwbJYfXmplodphLpGH6JzJYBesn+NdH17bSRPFJmck9UHFivmKQ84M/3JH6CXH2TeXgiO/7wkiPy9K2hL4vJD7O0tnBxrxneRuTdZ1Lfzj/XI9dXoMpBPs3uyVW9ClLv+iRNUZjtoQrzwnGy59UwC93O9aQ3mZ/fm2TC1TgmDhZkF5N3AZF3IdfD57MnWusrWWxB6TpW3GwiNaxWkwPWO84lml7Jrmq70Jg+znve+q4o63MeGU+KPJsGAattxdsHDUpY3bBN07+ai/zTsUl6mfhhZ82CD8pfqP33M4r4qssCZebNFBIUXFDapw3LXiyPvj6zQk5tvUvIZjdpaCOOI1E3xHdkoJuEdmjC+80EoB+a0gxty4FM9/1Y9oINH/R2tBVK2R0FQWUes1dzpBcXMBigFz5SWo85DNBTO3mWxduPgqOJ5B0UPgO8TiP/jdPB94lnBkQR7rEhfQsFgwGPA/mbWFjJNaKbj76jglJwNJG4C2cJkycDPkrUYwF/wu5IXBJcb8jdxWIU2GGWS+6daCgDnGhqWrw+tSybL9iiJ7nHHP6dV0sMyfdXcuerCUXAR64ic12JfcxL+Z1SzkUUAvg5fsL/JXbUMCmbuERQ70oYBKMgri73kE/RPF8WAYpUQM/DnHLhBz5D0R6RuBlNcC/awgFTucpIS+52N12uUxApI5O7wQDyqRjzCsNdCTjyrjlgVH2v4LTF5e+Xt6zbb1YEUK5GwFGbuUwSFLW68w2N4y73gkCL7hQzUU27An2kKm4/6HtXxq9MEgzHEKWWl/j2i01CPH4m7MLxUNLpW0x10553syMFC6t8zCTBLlQC3wxdS+re676plyh5LwLvD4pBhzzyekAtij4yTLMpuh9zi2+31IugFt7yDykCPJTSioavTdH0ZbaDQcHfW3xiXZjca5rk4chYrHmnrLIfkMvGFDQqofp9r7H+bLhzX1RuUmnbjm0ZS1iWaR43A15affrwBO7j8jzku+/BLq1uJfXYZot5e6q8iQujHSHbPPNfKNjjXlw3j03T2qxvsdZGpRdIBWGolYaDmZ7tlz30s+nZYFja9+1zmfGkc9/sNhqNbvd1es2/3ZyFLw/ff93dvby83N09P5193eXu9lY1NfJX1tdnSSTdh5agSpQ/EsiN59OrbtdbXrPSmdQDl7XQkfdwmKFWyORyub0nd3p5Kq18GCDXhRZi7/6escwBlvdhgYaSXHFbVISDA9RQaNEbJ38DwOveoteuhoGi4O9o9eP+txJEIDDURV2vaA1w9J6rQ6M1KC98Af7OBnooevHqYbFwiRXxcwXFXNGrxg6IfLK8DQxxbGwLhGIiU3Aw5BMaGvjhPNkR6C4Q39kXQRYwc68xrSx8x0Skhw6IElbWy+ih+J2vPHz3GME0jabT3F6srvrtXnn4IYB35qqxJC4IJaxpa+87miJApPCMuJZNIpJQq6bxYtlICA4NooZI1WL6YFgqlW6Gg3SZSNRGr0E/OFpkwaaXgnW1xT9qCVsUJD04bgJVSLlRbCIEDAOUCrqRVxYK5DmgtM1FOAiqkhxEDISHIqWfjKKFdryYKYIMapyOrhWUWGSJw0WS/8ZjVUtHp9GwUUswtZGqanrkE78F/AQmTQDUUUTAWyFfnZVdv6bUf82r7ybH0slIBb0pasVkIp317qYol/V0Irl3rWyEnZDP1xY4cLlshAgRIvwz8H+2fPs9Fa5eTwAAAABJRU5ErkJggg==">
    
        <!--searchbox-->
        <div class="search-box">
            <i class="material-icons">search</i>
            <input type="text">
            <i class="material-icons">mic</i>
            <i class="material-icons">search</i>
        </div>

        <!--buttons-->
        <div class="btn-box">
            <button>Google Search</button>
            <button>I'm Feeling Lucky</button>
        </div>

        <!--footer-->
        <footer>
           <p>our third decade of climate action: join us</p>
           <div class="footer-links">
            <div class="links-left">
                <a  href="#">Advertising</a>
                <a  href="#">Business</a>
                <a  href="#">How Search Works</a>

            </div>
            <div class="links-right">
                <a  href="#">Privacy</a>
                <a  href="#">Terms</a>
                <a  href="#">Settings</a>
            </div>

           </div>
        </footer>
    </div>

</body>
</html>
