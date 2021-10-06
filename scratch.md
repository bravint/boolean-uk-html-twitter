nav {
    height: 100vh;
    width: 275px;
    padding: 12px;
    display: grid;
    grid-auto-rows: 50px 522px 1fr;
}

.navGridMid {
    display: grid;
    grid-template-columns: repeat(8, auto-fit);
    align-items: center;
}

.text,
.navIcon {
    display: inline-block;
    vertical-align: middle;
}

.text {
    margin-left: 20px;
    font-family: ChirpMedium;
    font-size: 22px;
    font-weight: 700;
}