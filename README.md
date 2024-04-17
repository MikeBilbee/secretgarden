<h1> Secret Garden </h1>

This is the final project of Atlas T3 Fullstack course
---

<h2> Authors </h2>

- [Stephaine Biggs](https://github.com/Sbiggs1985) - [stephaine.biggs@atlasschool.com](stephaine.biggs@atlasschool.com)
- [Mike Bilbee](https://github.com/MikeBilbee) - [colin.bilbee@atlasschool.com](colin.bilbee@atlasschool.com)
- [Chris Gillis](https://github.com/chris85gillis) - [chris.gillis@atlasschool.com](chris.gillis@atlasschool.com)
---

<h2> Custom Frontend From Scratch </h2>

Imagine you’ve been tasked with crafting a digital exhibit for the “Garden of Dreams,” a virtual space devoted to exploring the intricate relationship between nature and the human psyche. This project aims to weave together the realms of botanical beauty and deep-seated emotions, presenting an online sanctuary that delves into the heart of our connection with the natural world.

The “Garden of Dreams” has entrusted you with a compilation of dreamlike descriptions, each painting a vivid picture of a unique aspect of this intertwining. You’re invited to select any of these sentences as the foundation for a webpage that captures the essence of the described scene. Your artistic direction is key in deciding how these narratives will unfold visually and emotionally for the visitors.

Your mission is to create an engaging and profound online experience that represents the chosen artwork, capturing the delicate balance between the natural and the emotional landscapes, and igniting the visitors’ senses. Through innovative design techniques, such as parallax scrolling, interactive storytelling, dynamic visuals, ai-generated images, or sensory exploration interfaces, your goal is to envelop visitors in a world where nature speaks to the soul.
---

<h2> Contents </h2>

| File | Description | Assets |
| ----- | ----- | ----- |
| [login.html](https://github.com/MikeBilbee/secretgarden/blob/main/login.html) |  | []() []() |
| [jan.html]() |  | []() []() |
| [feb.html]() |  | []() []() |
| [mar.html]() |  | []() []() |
| [apr.html]() |  | []() []() |
| [may.html]() |  | []() []() |
| [jun.html]() |  | []() []() |
| [jul.html]() |  | []() []() |
| [aug.html]() |  | []() []() |
| [sep.html]() |  | []() []() |
| [oct.html]() |  | []() []() |
| [nov.html]() |  | []() []() |
| [dec.html]() |  | []() []() |
| [styles.css]() |  |  |
---

© 2024 Stephaine Biggs, Mike Bilbee, Chris Gillis

<br>

<svg fill="none" viewBox="0 0 600 300" width="600" height="300" xmlns="http://www.w3.org/2000/svg">
  <foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml">
      <style>
        @keyframes hi  {
            0% { transform: rotate( 0.0deg) }
           10% { transform: rotate(14.0deg) }
           20% { transform: rotate(-8.0deg) }
           30% { transform: rotate(14.0deg) }
           40% { transform: rotate(-4.0deg) }
           50% { transform: rotate(10.0deg) }
           60% { transform: rotate( 0.0deg) }
          100% { transform: rotate( 0.0deg) }
        }

        @keyframes gradient {
          0% {
            background-position: 0% 50%;
          }
          50% {
            background-position: 100% 50%;
          }
          100% {
            background-position: 0% 50%;
          }
        }

        .container {
          background: linear-gradient(-45deg, #ee7752, #e73c7e, #23a6d5, #23d5ab);
          background-size: 400% 400%;
          animation: gradient 15s ease infinite;

          width: 100%;
          height: 300px;

          display: flex;
          justify-content: center;
          align-items: center;
          color: white;

          font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
        }

        .hi {
          animation: hi 1.5s linear -0.5s infinite;
          display: inline-block;
          transform-origin: 70% 70%;
        }

        @media (prefers-reduced-motion) {
          .container {
            animation: none;
          }

          .hi {
            animation: none;
          }
        }
      </style>

      <div class="container">
        <h1>Hi there, my name is Nikola <div class="hi">👋</div></h1>
      </div>
    </div>
  </foreignObject>
</svg>
