<div id="skills"></div>
    <div class="skills">
        <h1 class="text">Skills:</h1>
        <div class="skills-item">
            <img src="data/images/html.png" alt="HTML">
            <p class="text">HTML</p>
        </div>
        <div class="skills-item">
            <img src="data/images/css.png" alt="CSS">
            <p class="text">CSS</p>
        </div>
        <div class="skills-item">
            <img src="data/images/js.png" alt="Javascript">
            <p class="text">Javascript</p>
        </div>
        <!--<div class="skills-item">
            <img src="data/images/lua.png" alt="Lua">
            <p class="text">Lua</p>
        </div>-->
        <div class="skills-item">
            <img src="data/images/py.png" alt="Python">
            <p class="text">Python</p>
        </div>
    </div>
    
   <style>
    .skillstext {
      justify-content: center;
    }
    .text {
      color:  #ffffff
    }
    .skills {
    margin: 0 5px;
    margin-top: 5rem;
    display: flex;
    flex-direction: row;
    justify-content: center;
    gap: 2.2rem;
    flex-wrap: wrap;
}

.skills-item {
    text-align: center;
    border-radius: 5px;
    border: 1px solid #1470e9;
    padding: 1rem 0;
    width: 7.5rem;
    transition: 400ms;
}

.skills-item:hover {
    transform: translateY(-5px);
    box-shadow: 2px 5px 10px #00000013;
}

.skills-item:hover > img {
    filter: grayscale(0);
}

.skills-item > img {
    height: 5rem;
    filter: grayscale(100%);
    transition: 400ms;
}

.skills-item > p {
    text-align: center;
    font-size: 1.1rem;
}

@media (max-width: 330px) {

    .skills {
        flex-direction: column;
        margin: 0 10px;
        gap: 1rem;
    }

    .skills-item {
        width: calc(100% - 3px);
    }

    .skills-item > img {
        float: left;
        margin-left: 1rem;
    }

    .skills-item > p {
        font-size: 1.5rem;
    }

}
   </style>
