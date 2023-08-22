# Calculadora
body {
    overflow: hidden;
}






.form-container {
    position: absolute;
    top: 37%;
    left: 0%;
    transform: translateY(-50%);
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.fieldset {
    max-width: 90%;
    max-height: 100%;
}
.container {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
}

.form-container {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    margin-top: 20px;
}

@media only screen and (min-width: 768px) {
    .container {
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
    }

    .form-container {
        margin-top: 0;
    }
} 
