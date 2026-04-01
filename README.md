/* RESET + FONT */
body {
    margin: 0;
    font-family: -apple-system, BlinkMacSystemFont, "SF Pro Text", "Segoe UI", Roboto, Arial, sans-serif;
    color: #1d1d1f;
    background: #ffffff;
    -webkit-font-smoothing: antialiased;
}

/* ===== THANH QUỐC GIA ===== */
#QuocGia {
    background: #f5f5f7;
    border-bottom: 1px solid #d2d2d7;
    font-size: 12px;

    display: flex;
    justify-content: center;
    align-items: center;
    gap: 14px;

    padding: 10px 20px;
}

#QuocGia p {
    margin: 0;
    color: #1d1d1f;
}

#QuocGia select {
    height: 28px;
    border-radius: 8px;
    border: 1px solid #d2d2d7;
    padding: 0 8px;
    background: #fff;
    font-size: 12px;
    outline: none;
}

#QuocGia button {
    height: 28px;
    padding: 0 16px;
    border-radius: 14px;
    border: none;
    background: #1d1d1f;
    color: #fff;
    font-weight: 600;
    cursor: pointer;
}

#QuocGia a {
    font-size: 18px;
    text-decoration: none;
    color: #6e6e73;
}

/* ===== NAVBAR ===== */
#navigation {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 32px;

    padding: 12px 0;
    background: #ffffff;

    font-size: 12px;
}

#navigation a {
    text-decoration: none;
    color: #6e6e73;
    transition: color 0.25s ease;
}

#navigation a:hover {
    color: #000;
}

/* Icon Apple + icon cuối */
#navigation a:first-child {
    font-size: 18px;
    color: #000;
}

#navigation a:last-child,
#navigation a:nth-last-child(2) {
    font-size: 14px;
}

/* ===== HERO ===== */
#NoiDung {
    background: #f5f5f7;
    text-align: center;

    padding-top: 90px;
    padding-bottom: 40px;
}

/* Title */
#NoiDung h1 {
    font-size: 56px;
    font-weight: 600;
    letter-spacing: -0.005em;
    margin: 0;
}

/* Subtitle */
#NoiDung h2 {
    font-size: 28px;
    font-weight: 400;
    color: #6e6e73;

    margin-top: 10px;
    margin-bottom: 28px;
}

/* ===== BUTTONS ===== */
#NoiDung button {
    font-size: 17px;
    padding: 12px 28px;
    border-radius: 980px;
    cursor: pointer;
    margin: 0 8px;
    transition: all 0.25s ease;
}

/* Learn more */
#NoiDung button:nth-of-type(1) {
    background: linear-gradient(90deg, #0071e3, #2997ff);
    border: none;
    color: #fff;
}

#NoiDung button:nth-of-type(1):hover {
    background: linear-gradient(90deg, #0077ed, #3aa0ff);
}

/* Buy */
#NoiDung button:nth-of-type(2) {
    background: transparent;
    border: 1px solid #0071e3;
    color: #0071e3;
}

#NoiDung button:nth-of-type(2):hover {
    background: #0071e3;
    color: #fff;
}

/* ===== IMAGE ===== */
#NoiDung img {
    display: block;
    margin: 50px auto 0 auto;

    max-width: 900px;
    width: 90%;
    height: auto;
}

/* ===== RESPONSIVE ===== */
@media (max-width: 768px) {

    #navigation {
        gap: 16px;
        overflow-x: auto;
        justify-content: flex-start;
        padding: 12px 16px;
    }

    #NoiDung {
        padding-top: 60px;
    }

    #NoiDung h1 {
        font-size: 40px;
    }

    #NoiDung h2 {
        font-size: 20px;
    }

    #NoiDung button {
        font-size: 15px;
        padding: 10px 20px;
    }
}
