<template>

    <div class="section2">

        <div class="section2__container">
            <div class="section2__left">
                <div class="section2__explain">
                    <img src="@/assets/Vector1.png" alt="Explain Icon">
                    <h2>Explain Code</h2>
                </div>
                <p>Explain some code based on the syntax provided</p>
                <h3>Paste your code below</h3>
                <div class="section2__code-section">
                    <pre><span class="section2__code-keyword first">function</span> <span class="section2__code-name second">HelloWorld</span>(text){</pre>
                    <p>echo text || <span class="section2__code-string third">"Hello World"</span>;</p> }
                </div>
                <button class="section2__btn">
                    <img src="@/assets/Vector2.png" alt="Enhance Icon">
                    <a>Enhance with AI</a>
                </button>
            </div>

            <div class="section2__right">
                <h1><i class="fa fa-chevron-right" aria-hidden="true"></i> What does this code do?</h1>
                <p class="ptext">The following code does:</p>
                <div class="section2__info-section">
                    <div><i class="fa fa-chevron-right" aria-hidden="true"></i>The code above is a function definition.</div>
                    <div><i class="fa fa-chevron-right" aria-hidden="true"></i>It defines a new function called `HelloWorld` that takes a single argument called `text`</div>
                    <div><i class="fa fa-chevron-right" aria-hidden="true"></i>The body of the function is a single line of code that prints out the value of `text` if it is defined, or `Hello World` if it is not defined.</div>
                </div>
                <button class="section2__btn">
                    <img src="@/assets/Vector3.png">
                    <a>Copy Output</a>
                </button>
            </div>
        </div>

        <div class="buttons">
            <div class="button">
                <button class="btn"><img src="@/assets/btn-vector1.png" alt=""><a href="#">Explain Code</a></button>
            </div>

            <div class="button">
                <button class="btn"><img src="@/assets/btn-vector2.png" alt=""><a href="#">Regex</a></button>
            </div>

            <div class="button">
                <button class="btn"><img src="@/assets/btn-vector3.png" alt=""><a href="#">Convert Code</a></button>
            </div>

            <div class="button">
                <button class="btn"><img src="@/assets/btn-vector4.png" alt=""><a href="#">Fix Grammar</a></button>
            </div>

            <div class="button">
                <button class="btn"><img src="@/assets/btn-vector5.png" alt=""><a href="#">Todo</a></button>
            </div>

            <div class="button">
                <img src="@/assets/btn-vector6.png" alt="">
            </div>

        </div>

        <div class="signupbutton">
            <div class="button">
                <button class="btn"><img src="@/assets/signup-Vector.png" alt="">Free Signup</button>
            </div>
        </div>

    </div>

</template>

<script>
export default {
    name: 'Section2'
}
</script>
