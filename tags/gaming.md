# Gaming Prompts

> Found 22 prompts in this category.

---

## Watch the fireworks show from the top of the mountain

![Watch the fireworks show from the top of the mountain](https://opennana.com/awesome-prompt-gallery/images/1000.jpeg)

- **Model:** Nano banana pro
- **Source:** [Unknown](#)
- **Tags:** 3d, animal, architecture, branding, cartoon, character, clay, data-viz, fantasy, fashion, felt, food, futuristic, gaming, illustration, infographic, interior, landscape, logo, minimalist, nature, neon, paper-craft, photography, pixel, portrait, poster, product, retro, sci-fi, sculpture, toy, typography, ui, vehicle

**Prompt:**

```
{
  "template_name": "New Year City Skyline Celebration",
  "description": "A cinematic shot of a child overlooking a city skyline with custom fireworks effects.",
  "prompt_template": "A stunning cinematic shot of a joyful child in silhouette, wearing a whimsical party hat, standing on a high mountain peak with arms outstretched in wonder. The background is a breathtaking aerial night view of the Shanghai skyline, featuring the Oriental Pearl Tower, The Bund, and the winding Huangpu River under a starry night sky. The sky erupts with {city_fireworks_effect}. A massive, glowing firework display clearly spells out '2026' in the center. 8k resolution, photorealistic, magical atmosphere, highly detailed urban nightscape.",
  "input_variables": {
    "city_fireworks_effect": {
      "type": "string",
      "description": "Description of the style, shape, and vibe of the fireworks.",
      "default_value": "a spectacular Disney-style fireworks show, featuring Mickey Mouse shaped bursts, fairy-tale pastel colors, glittering magic dust, and dreamlike cascading sparks"
    }
  },
  "full_prompt_example": "A stunning cinematic shot of a joyful child in silhouette, wearing a whimsical party hat, standing on a high mountain peak with arms outstretched in wonder. The background is a breathtaking aerial night view of the Shanghai skyline, featuring the Oriental Pearl Tower, The Bund, and the winding Huangpu River under a starry night sky. The sky erupts with a spectacular Disney-style fireworks show, featuring Mickey Mouse shaped bursts, fairy-tale pastel colors, glittering magic dust, and dreamlike cascading sparks. A massive, glowing firework display clearly spells out '2026' in the center. 8k resolution, photorealistic, magical atmosphere, highly detailed urban nightscape."
}
```

---

## First person shooter perspective

![First person shooter perspective](https://opennana.com/awesome-prompt-gallery/images/971.jpeg)

- **Model:** Nano banana pro
- **Source:** [@fofrAI](https://x.com/fofrAI/status/2003146989060710828)
- **Tags:** gaming, landscape, nature, neon, photography, sci-fi, ui, vehicle

**Prompt:**

```
{
  "subject": {
    "description": "First-person shooter (FPS) perspective of a cybernetic mercenary holding a dual-barreled smart pistol in a dystopian mega-city.",
    "mirror_rules": "HUD elements and text must be legible and non-mirrored. Charge meter reads '100%'.",
    "age": "N/A",
    "expression": {
      "eyes": null,
      "mouth": null,
      "overall": "Adrenaline-fueled, chaotic, fast-paced"
    },
    "face": {
      "preserve_original": "false",
      "texture": "Ocular implant interface, glitch effects",
      "makeup": null,
      "features": "Augmented reality (AR) overlay with scan lines"
    },
    "hair": null,
    "body": {
      "frame": "Robotic prosthetic arm visible in foreground",
      "waist": null,
      "chest": null,
      "legs": "Not visible",
      "skin": {
        "visible_areas": "None (cybernetics)",
        "tone": "Chrome and synthetic black",
        "texture": "Carbon fiber weave, exposed wiring, neon tubing",
        "lighting_effect": "Pink and cyan reflections from city lights"
      }
    },
    "pose": {
      "position": "First-person view, weapon canted slightly sideways, dynamic movement",
      "base": "Parkour/Wall-running stance",
      "overall": "High-velocity action camera angle"
    },
    "clothing": {
      "top": {
        "effect": "Tech-wear jacket sleeve, tactical wrist computer"
      },
      "bottom": null
    }
  },
  "accessories": {
    "jewelry": null,
    "device": "Experimental Smart Pistol. Matte black finish with glowing yellow heat vents. Holographic ammo projection displaying '12/12'.",
    "prop": "HUD Overlay: Red enemy outlines, Threat detection (center), Mini-map (top right), Health bar (bottom left). Text prompt: 'WARNING: SECTOR 4 LOCKDOWN'."
  },
  "photography": {
    "camera_style": "In-game screenshot, Ray-traced Render",
    "angle": "First-person POV, high FOV (Field of View)",
    "shot_type": "Landscape, POV",
    "aspect_ratio": "16:9",
    "texture": "Next-gen graphics, wet surface reflections, chromatic aberration, digital noise",
    "lighting": "Neon signage (pink, purple, cyan), dark shadows, volumetric fog, wet pavement glare",
    "depth_of_field": "Motion blur on edges, sharp focus on weapon and immediate target"
  },
  "background": {
    "setting": "Rain-slicked rooftop in a Cyberpunk metropolis",
    "wall_color": "Dark concrete and neon",
    "elements": [
      "Massive holographic billboards featuring anime girls",
      "Flying cars in traffic lanes below",
      "Dense skyscrapers blocking the sky",
      "Heavy rain falling"
    ],
    "atmosphere": "Dystopian, gritty, technological noir",
    "lighting": "Artificial city lights, gloom, lightning flashes"
  },
  "the_vibe": {
    "energy": "High-octane, rebellious",
    "mood": "Dark, electric, dangerous",
    "authenticity": "High-end PC game screenshot",
    "intimacy": "Visceral combat",
    "story": "escaping a corporate security raid",
    "caption_energy": "System Override"
  },
  "constraints": {
    "must_keep": [
      "FPS perspective",
      "Glitchy HUD elements",
      "Cybernetic hand details",
      "Neon lighting",
      "Text 'WARNING: SECTOR 4 LOCKDOWN'",
      "Rain effects"
    ],
    "avoid": [
      "Third-person view",
      "Daylight",
      "Nature/Trees",
      "Medieval weaponry",
      "Clean military aesthetic"
    ]
  },
  "negative_prompt": [
    "third person",
    "sunlight",
    "grass",
    "mountains",
    "clean",
    "low poly",
    "blurry",
    "peaceful"
  ]
}
```

---

## Create your own GTA character

![Create your own GTA character](https://opennana.com/awesome-prompt-gallery/images/5.png)

- **Model:** None
- **Source:** [@Anima_Labs](https://x.com/Anima_Labs/status/1924135446629728712)
- **Tags:** character, gaming, landscape, neon

**Prompt:**

```
Act as a creative director at Rockstar Games. Create a fictional GTA VI character sheet in the exact same style as the official GTA VI promotional images.

The layout must be:

A horizontal character sheet, with the character on the right, in a dynamic pose that reflects their personality.
On the left, include the following structured text:
A small "VI" logo at the top left (mention it visually).
The character’s name in big bold text.
A catchy slogan or tagline right below in a different bright color.
A short backstory (3–5 lines) written in an ironic, street-smart, or playful tone — just like Rockstar’s tone of voice.

Use the vibrant Vice City aesthetic with sunset lighting, neon accents, and cel-shaded comic style. The character’s clothing, action, and environment must reflect their archetype and background.

Let me customize the following variables:

Archetype: {your choice}

Gender: {your choice}

Skin tone: {your choice}

Hairstyle: {your choice}

Emotion : {your choice}

Outfit: {your choice}

Weapon or action: {your choice}

Background details: {your choice}

Generate a fictive name in tittle and a description in english

Format the final result like a finished in-game asset reveal. The vibe should be over-the-top, stylish, and full of personality — as if part of the real GTA VI world.

(if the "Your choice" sections are not filled with personalized information, it's up to you to generate it randomly by yourself) generate the visual directly from now on
```

---

## Brand Minecraft Style

![Brand Minecraft Style](https://opennana.com/awesome-prompt-gallery/images/18.png)

- **Model:** None
- **Source:** [@TheRelianceAI](https://x.com/TheRelianceAI/status/1923757741262164427)
- **Tags:** branding, gaming, nature, pixel

**Prompt:**

```
"A Minecraft-style voxel recreation of a [BRAND NAME] [OBJECT], built entirely from pixelated cubes — detailed voxel modeling, signature brand colors and logo, blocky textures, clean lighting, stylized yet recognizable, 3D render, high resolution, playful and creative interpretation
```

---

## Put the logo into my world

![Put the logo into my world](https://opennana.com/awesome-prompt-gallery/images/37.jpeg)

- **Model:** None
- **Source:** [@alex_prompter](https://x.com/alex_prompter/status/1924503062325989836)
- **Tags:** animal, branding, gaming, landscape, logo, pixel

**Prompt:**

```
Recreate the [BRAND NAME] logo following the JSON Aesthetic below: {
"style": "Minecraft-style voxel 3D rendering",
"logo_handling": {
"adapt_to_uploaded_logo": true,
"rebuild_logo_using_voxel_blocks": true,
"use_original_logo_as_strict_pixel-color map": true,
"preserve_text_in_logo": true,
"preserve_text_case": true,
"preserve_original_logo_colors": true,
"preserve_shape_and_layout": true
"aspect_ratio": [INSERT ASPECT RATIO]
},
"minecraft_conversion": {
"voxel_depth": "medium thickness to show 3D volume",
"block_style": "authentic Minecraft texture mapping",
"color_strategy": "each block in the logo must match a pixel from the uploaded logo exactly — no estimation or stylistic substitution",
"voxel_material_match": "map logo pixels to Minecraft block colors that visually match pixel color as closely as possible — no creative enhancements",
"disable_palette_expansion": true
},
"scene_environment": {
"base": "neutral terrain (gray concrete or light stone)",
"background": "simple sky (clouds, no sun flare)",
"optional_elements": [
"Minecraft animals at a distance",
"terrain vegetation in background only"
],
"environment_color_policy": "environment must not share colors used in the logo to prevent blending or confusion"
},
"lighting": {
"neutral directional light": true,
"do_not_adjust_logo_colors_for_lighting": true,
"prevent_ambient_light_color_bleed": true
},
"camera": {
"angle": "slightly top-down with 3D logo centered",
"focus": "sharp focus on voxel logo only, environment softly rendered"
},
"render_quality": {
"voxel_texture_resolution": "high",
"shadows": "natural voxel-style ambient shadows only",
"disable_artistic_effects": true
},
"post_processing": {
"no glow effects": true,
"no color correction": true,
"disable AI reinterpretation of tones or palette": true
},
"image_constraints": {
"transparent_background": false,
"include_text": true,
"preserve_text_case": true,
"preserve_original_logo_colors": true,
"obey_uploaded_logo_shape": true,
"match_uploaded_logo_layout": true,
"enforce_color_source_from_logo_only": true
},
"notes": "Rebuild the uploaded logo using Minecraft-style voxel blocks. Every block must represent one pixel from the logo's original image. No creative license is allowed in color, shape, or layout. The environment is decorative only and must not affect logo readability or color perception. The final image should appear as if the logo were physically constructed in a Minecraft world using blocks that match its exact colors and shapes."
}
```

---

## Nintendo style 3D cartoon illustration

![Nintendo style 3D cartoon illustration](https://opennana.com/awesome-prompt-gallery/images/116.png)

- **Model:** None
- **Source:** [@Artedeingenio](https://x.com/Artedeingenio/status/1931647658382258183)
- **Tags:** animal, cartoon, character, clay, fantasy, gaming, illustration, landscape, toy, vehicle

**Prompt:**

```
Transform this image into a Nintendo-inspired 3D cartoon style illustration.

Use soft, rounded 3D shapes and clean, toy-like geometry to give the characters and objects a charming, handcrafted look.

Characters should have exaggerated, childlike proportions (large heads, small limbs), with expressive, simplified faces and bright, colorful clothing — similar to designs seen in Zelda: Link’s Awakening, Animal Crossing, or Miitopia.

Apply smooth, matte textures with no realistic detail — everything should look cheerful and slightly plastic, as if sculpted from soft clay or digital vinyl.

The environment should be bright and whimsical, with stylized grass, puffy clouds, geometric trees, and soft lighting like a sunny afternoon.

The overall tone should be lighthearted, clean, and family-friendly, like a frame from a Nintendo fantasy adventure game.
```

---

## City Candy Crush Saga style

![City Candy Crush Saga style](https://opennana.com/awesome-prompt-gallery/images/261.jpeg)

- **Model:** None
- **Source:** [@miilesus](https://x.com/miilesus/status/1939690110418833592)
- **Tags:** architecture, cartoon, gaming, logo, vehicle

**Prompt:**

```
A colorful, playful 2D map of [city name], in the style of Candy Crush Saga, featuring the city’s iconic landmarks as candy-inspired buildings, cute gumdrop trees, licorice bridges, pastel roads, and glossy water elements, floating clouds, vibrant cartoon style, top-down view, kid-friendly game aesthetics, horizontal layout
```

---

## Cartoon style app icons

![Cartoon style app icons](https://opennana.com/awesome-prompt-gallery/images/303.jpeg)

- **Model:** None
- **Source:** [@CharaspowerAI](https://x.com/CharaspowerAI/status/1966539819158212759)
- **Tags:** cartoon, character, food, gaming, portrait, vehicle

**Prompt:**

```
Colorful, cartoon-style app icon design for a [type of app: game, movie, food, sport, etc.] logo with the text ["App Name"] and [character, symbol, or cute object + short description of its pose or action] on the front of a square button, set against a [background color / theme] with simple details. High-resolution game art and graphics for a mobile app, Pixar style, realistic.
```

---

## Full body realistic fashion portrait

![Full body realistic fashion portrait](https://opennana.com/awesome-prompt-gallery/images/393.jpeg)

- **Model:** None
- **Source:** [@IamEmily2050](https://x.com/IamEmily2050/status/1983742027058835543)
- **Tags:** architecture, cartoon, character, fantasy, fashion, futuristic, gaming, interior, landscape, nature, neon, photography, portrait, sci-fi, vehicle

**Prompt:**

```
{
  "instruction": "Generate a full-body, photorealistic fashion portrait of a modern East Asian idol in all-black styling. The result must look like a professional test shot, not anime, not cosplay, not fantasy.",

 "subject": {
    "identity": "East Asian female idol, early 20s look, pale smooth skin, symmetrical features, refined jawline, large natural eyes, soft neutral lips.",
    "hair": {
      "color": "jet-black",
      "style": "straight with blunt bangs framing the eyes",
      "length": "long, falling past the chest",
      "optional_variants": [
        "clean straight hair down",
        "twin high ponytails with bangs and loose face-framing strands"
      ]
    },
    "body": {
      "build": "slender, long-legged, elegant proportions, model-like lines",
      "posture": "calm, confident, controlled posture, standing tall",
      "pose": "full-body standing pose, relaxed arms at sides or slight hip angle, natural stance, no exaggerated arching"
    }
  },

  "wardrobe": {
    "palette": "all black, monochrome styling",
    "look_variants": [
      {
        "description": "long-sleeve fitted black top with structured waist (corset-like shaping), short pleated mini skirt with belt hardware, over-the-knee black lace-up boots with platform heel, subtle layered silver jewelry"
      },
      {
        "description": "black cropped top, exposed midriff, slim black jeans, fitted choker stack and pendant necklace, matte black boots"
      }
    ],
    "note": "Outfit must read as high-fashion / street idol aesthetic, not fantasy costume, not sci-fi armor, not latex fetishwear."
  },

  "camera": {
    "framing": "full-body portrait from head to shoes, vertical composition, subject centered and filling most of the frame",
    "angle": "slightly low to mid-torso camera height for subtle leg lengthening OR neutral eye-level framing against a doorway",
    "lens_behavior": "clean realistic perspective, no wide distortion, no fisheye",
    "focus": "sharp focus across the subject from face to boots, depth of field appropriate for fashion photography"
  },

  "environment": {
    "style_options": [
      "industrial interior with worn tile floor and large window frame / metal framing in the background, muted gray tones",
      "neutral architectural doorway outdoors, pale stone or painted door, soft natural light"
    ],
    "lighting": "soft, diffused, natural-feeling light with gentle directional falloff. Skin should look smooth and real, not plastic. No neon rim light, no colored gels."
  },

  "aesthetic": {
    "tone": "clean Korean idol / street editorial test shot",
    "color_grade": "subtle cool neutrals in the background, deep matte blacks in wardrobe, natural skin tones",
    "finish": "high-end fashion photography, not fantasy art, not anime render, not glossy VR avatar"
  },

  "technical_rendering": {
    "intent": "photorealistic human subject",
    "keywords": [
      "cinematic portrait photography",
      "studio-quality fashion still",
      "PBR material realism on fabric texture (matte black cloth, leather belt, lace-up boots)",
      "no exaggerated body morph",
      "no plastic skin",
      "no cel-shaded look"
    ]
  },

  "negative": {
    "forbidden_styles": [
      "anime style",
      "cartoon style",
      "3D game character",
      "virtual idol hologram look",
      "cyberpunk fantasy costume",
      "latex catsuit aesthetic",
      "sci-fi armor",
      "bright colored hair",
      "oversized eyes / doll face",
      "hyper-airbrushed Barbie texture",
      "warped body proportions",
      "fish-eye distortion",
      "text overlays or watermarks"
    ],
    "forbidden_words": [
      "NSFW pose",
      "explicit lingerie framing",
      "cutesy cosplay expression",
      "aggressive pin-up arching"
    ]
}
```

---

## Young woman by the window on the bus

![Young woman by the window on the bus](https://opennana.com/awesome-prompt-gallery/images/419.jpeg)

- **Model:** None
- **Source:** [@miilesus](https://x.com/miilesus/status/1986833636193189893)
- **Tags:** gaming, landscape, nature, photography, portrait, ui, vehicle

**Prompt:**

```
{
    "promptDetails": {
        "description": "A prompt to *create a new scene* by placing a subject (based on a reference photo) into a new atmospheric background, then overlaying a music UI.",
        "styleTags": [
            "Aesthetic Edit",
            "Cinematic",
            "Scene Compositing",
            "Glassmorphism"
        ]
    },
    "subjectReference": {
        "source": "[UPLOADED IMAGE]",
        "description": "Use this image *only* as a reference for the subject's face, hair, and appearance. Do *not* use its original background."
    },
    "scene": {
        "background": {
            "setting": "the window on the bus is sad, troubled, sorrowful",
            "details": "This is the *new* environment the subject must be placed into, completely replacing the original background."
        },
        "subject": {
            "description": "The young man whose appearance is defined by the `[UPLOADED IMAGE]`.",
            "pose": "his head resting gently against the bus window",
            "focus": "Subject is in sharp focus, fully integrated into the new background."
        }
    },
    "overlayObject": {
        "type": "Floating Glassmorphism Music Player UI",
        "relationshipToEnvironment": "the UI is **perfectly flush and physically attached** to the same plane as the bus window glass, **not floating**, not screen-space.",
        "transform": "the UI matches the *exact same rotation and perspective* as the window surface. If the window tilts, the UI tilts identically with correct foreshortening.",
        "surfaceInteraction": "subtle, realistic reflection and slight refraction through glass, extremely thin glassmorphism panel integrated *into* the window surface.",
        "components": {
            "songTitle": "Wrecked",
            "artistName": "Imagine Dragons",
            "position": "mounted on the bus window glass at the middle-left region of the frame (not floating)."
        }
    },
    "technicalStyle": {
        "aspectRatio": "1:1",
        "photographyStyle": "Cinematic Portrait, Realistic Compositing",
        "camera": {
            "shotType": "Medium Shot or Medium Close-Up",
            "angle": "Eye-level",
            "depthOfField": "Shallow, to blur the new background (bokeh)."
        },
        "lighting": {
            "type": "Soft, Ambient, Moody",
            "description": "Lighting on the subject *must match* the lighting of the new background setting (e.g., rainy light through bus window, soft shadow gradients)."
        },
        "color": {
            "palette": "Muted, cinematic color grading."
        }
    },
    "audioDevice": {
        "type": "subtle in-ear wireless earbuds",
        "fit": "naturally seated in both ears with correct realistic skin contact",
        "color": "matte black or dark neutral tone",
        "consistencyNote": "no cable, no bulky gaming headset"
    },
    "moodReinforcement": "earbuds imply the sad music 'Wrecked - Imagine Dragons' is what the subject is listening to."
}
```

---

## Super Smash Bros. game poster family portrait

![Super Smash Bros. game poster family portrait](https://opennana.com/awesome-prompt-gallery/images/474.jpeg)

- **Model:** Nano banana pro
- **Source:** [@berryxia_ai](https://x.com/berryxia_ai/status/1991541693708136662)
- **Tags:** gaming, poster

**Prompt:**

```
Draw a family portrait for the Super Smash Bros. game poster, keeping the style consistent with the game. aspect 9:16 2k
```

---

## Panoramic character depth concept exploded view

![Panoramic character depth concept exploded view](https://opennana.com/awesome-prompt-gallery/images/478.jpeg)

- **Model:** Nano banana pro
- **Source:** [@berryxia_ai](https://x.com/berryxia_ai/status/1992621791588835494)
- **Tags:** branding, character, fashion, gaming, illustration, interior, nature, paper-craft, pixel, portrait

**Prompt:**

```
Role
You are a top concept artist for games and animations, and are good at producing detailed character sheets. You have the ability to "pixel-level disassembly", which allows you to see through the layers of a character's clothing, capture changes in micro-expressions, and restore the objects related to them in a concrete way. You are particularly good at fleshing out the character and backstory of female characters through their private belongings, belongings and life details.
Task
Based on the main image uploaded or described by the user, a "panoramic character depth concept decomposition diagram" is generated. The picture must include a full-body portrait of the central character, surrounded by a display of the character's clothing layers, different expressions, core props, close-ups of materials, as well as displays of private and personal belongings with a sense of life.
Visual Guidelines
1. Layout:
• Center: Place the character's full-body silhouette or main dynamic pose as a visual anchor.
• Surroundings: Arrange the disassembled elements in an orderly manner in the blank space around the central figure.
• Visual guidance (Connectors): Use hand-drawn arrows or guide lines to connect the surrounding disassembled items with the corresponding parts or areas of the central figure (such as the hand where the bag is connected).
2. Deconstruction Details - core iteration area:
• Clothing Layers [Enhanced Version]:
• Split the character's clothing into individual items for display. If it is a multi-layered outfit, you need to show the state of the inner layer after taking off the jacket.
• Newly added: Intimate Apparel: Displays the character's inner clothing independently, focusing on the design and material. For example: a set of lace underwear (showing lace pattern details), thongs (showing tailoring), stockings (showing translucency and sock opening design), shapewear or safety pants, etc.
• Expression Sheet:
• Draw 3-4 different close-ups of heads in the corners, showing different emotions (e.g. aloofness, shyness, surprise, absence, or concentration while applying lipstick).
• Texture & Zoom [Enhanced Version]:
• Select 1-2 key parts for close-ups. For example: the folds of fabric, the texture of skin, the details of hands.
• New: Close-up of object texture: Added description of the material of small objects, such as: the moist feel of lipstick paste, the grainy texture of leather bags, and the delicate feel of cosmetic powder.
• Related Items [Deep Iteration]:
• This is no longer limited to large props, it is necessary to add "life slices" to display the characters.
• Bag & Contents: Draw the character's daily commute bag or clutch and "open" it to reveal the items scattered around.
• Beauty & Grooming: Showcase their commonly used cosmetic combinations (e.g. close-ups of specific shades of lipstick/lip gloss, powder cases with mirrors, perfume bottle designs, hand cream).
• Lifestyle & Intimate Items: Items that embody the hidden side of a character. Depending on the character's personality, it may include: private diary, commonly used medicine/supplement box, electronic cigarette, or more personal items (such as the airplane cup/sex toy mentioned by the user, which needs to be presented from an objective perspective of a design drawing, indicating the model or design features).
3. Style & Annotations:
• Drawing style: Maintain a high-quality 2D illustration style or concept design sketch style with clean and crisp lines.
• Background: Use a beige, parchment, or light gray textured background to create the atmosphere of a design manuscript.
• Text description: Simulate handwritten notes next to each teardown element, briefly describing the material (e.g., “soft lace,” “nubuck leather”) or brand/model hints (e.g., “common color number #520,” “customized version”).
Workflow (execution logic)
When the user provides an image or description:
1. Analyze the subject’s core characteristics, clothing style and potential personality.
2. Extract detachable first-level elements (coats, shoes, big expressions).
3. Brainstorm and design secondary in-depth elements (What style does she wear in underwear? What lipstick does she carry in her bag? What items does she use when she is alone?).
4. Produce a combined image of all these elements, ensuring accurate perspective, uniform light and shadow, and clear annotations.
5. Use Chinese: English mark, high-definition 4K HD output
```

---

## Brand co-branded poster

![Brand co-branded poster](https://opennana.com/awesome-prompt-gallery/images/504.jpeg)

- **Model:** Nano banana pro
- **Source:** [@imaxichuhai](https://x.com/imaxichuhai/status/1991761772454224349)
- **Tags:** branding, character, futuristic, gaming, landscape, logo, neon, poster, typography

**Prompt:**

```
Aspect ratio 16:9, official game linkage poster, masterpiece, vibrant "Zero" anime style.  Scene: Four stylish anime characters (a pink-haired girl in a black jacket is the visual center, a silver-haired girl, a white-haired boy, and a black-haired boy) pose in a futuristic city night, each holding a glass of Coke.  Environment: This is a nighttime street in a futuristic city, where the entire scene is dominated by huge, glowing neon signs.  A large, unmissable neon sign featuring a stylized "ZZZ" logo is the absolute focal point of the background, shining brightly behind the protagonists. Other neon signs reading "Coca-Cola" are equally eye-catching, bathing the entire scene in vivid purple and blue light.  Special effects: Fruits such as strawberries and lemons are encased in transparent bubbles and float, with glowing pink and blue energy swirling across the frame.  Text elements: Upper left corner: Displaying the logo of "Zero Zero" and "Coke", connected by "X".  Bottom center: A large block of eye-catching Chinese text "Zero Zero X Coke: Awakening of powers, double happiness!". The font is bold, stylized word art with white fill and thick purple-pink gradient strokes.  Below the Chinese: There is "LIMITED COLLAB" in white capital letters in a black rectangular frame.  Art style: Highly detailed, clean lines, cinematic light effects from giant neon signs, dynamic compositions.  Negative warning words: blurry, low quality, broken human structure, hand deformity, ugly, watermark, signature, garbled text, deformed letters
```

---

## career map picture

![career map picture](https://opennana.com/awesome-prompt-gallery/images/557.jpeg)

- **Model:** Nano banana pro
- **Source:** [@songguoxiansen](https://x.com/songguoxiansen/status/1992766727126704259)
- **Tags:** gaming

**Prompt:**

```
Please create an interesting career map picture for Xiaomi’s Lei Jun, using the theme of Honor of Kings
```

---

## Game character tries to crawl from TV screen to living room

![Game character tries to crawl from TV screen to living room](https://opennana.com/awesome-prompt-gallery/images/570.jpeg)

- **Model:** Nano banana pro
- **Source:** [@songguoxiansen](https://x.com/songguoxiansen/status/1991801077092733297)
- **Tags:** character, gaming, pixel

**Prompt:**

```
A pixelated video game character tries to crawl from the TV screen into the living room. A real human player is scrambling to push the character back onto the screen with a controller.
```

---

## Beautiful 3D renderings of the handheld game console

![Beautiful 3D renderings of the handheld game console](https://opennana.com/awesome-prompt-gallery/images/574.jpeg)

- **Model:** Nano banana pro
- **Source:** [@egeberkina](https://x.com/egeberkina/status/1993592049430650957)
- **Tags:** gaming, minimalist, photography, retro

**Prompt:**

```
A highly polished 3D render of a classic handheld game console split cleanly into two halves, standing upright on a glossy reflective surface. Between the two halves, a miniature floating platform world inspired by retro side-scrolling platform games emerges: brick blocks, green pipes, gold coins, small clouds, and a tiny flagpole. The level pieces are arranged in multiple layers suspended in mid-air. The console screens show a retro game title. Soft studio lighting, pastel blue background, smooth shadows, subtle reflections, playful and whimsical tone. Ultra-clean materials, rounded plastic edges, crisp details, vibrant colors, minimalistic composition, centered layout.
```

---

## Woman in suit poses for suspect photo

![Woman in suit poses for suspect photo](https://opennana.com/awesome-prompt-gallery/images/657.jpeg)

- **Model:** Nano banana pro
- **Source:** [@xmiiru_](https://x.com/xmiiru_/status/1995344587750072496)
- **Tags:** cartoon, fantasy, fashion, gaming, illustration, interior, nature, photography, pixel, portrait, retro, vehicle

**Prompt:**

```
{
  "title": "Hyper-Realistic Portrait: Suited Woman in Mugshot Pose",
  "description": "A high-resolution hyper-realistic 8K HD portrait photograph captured with a professional DSLR camera using a 50mm lens for natural depth of field and razor-sharp focus. Full-body composition mimicking an old-fashioned mugshot/police booking photo.",
  "subject": {
    "type": "woman",
    "features": {
      "likeness_reference": "attached image",
      "height": "tall",
      "build": "elegant",
      "facial_features": {
        "jawline": "sharp",
        "eyes": "intense",
        "expression": "confident, slightly smug smirk"
      },
      "pose": "leaning against wall, one knee bent"
    },
    "hair": {
      "style": "neat, straight, wavy or elegant updo",
      "appearance": "natural and well-groomed"
    },
    "clothing": {
      "jacket": "vintage-style tailored dark pinstripe suit jacket",
      "inner_garment": "none",
      "tie": "slightly loosened, dark shade matching jacket",
      "accessories": [
        {
          "type": "mugshot board",
          "text": {
            "name": "MIRA",
            "date": "17/5/62"
          }
        },
        {
          "type": "shoe",
          "description": "single shiny dark-colored high-heeled shoe in right hand",
          "material": "patent leather"
        }
      ]
    }
  },
  "background": {
    "style": "naturally blurred bokeh",
    "texture": "slightly gritty studio wall",
    "details": {
      "height_chart": "vertical lines with numerical markings 2'0\" to 6'6\"",
      "color_tone": "desaturated, slightly sepia-toned archival photograph aesthetic"
    }
  },
  "lighting": {
    "type": "clean, soft, balanced",
    "shadow": "accurate shadows and highlights",
    "direction": "strong overhead or frontal lighting emphasizing dramatic shadows and height chart lines"
  },
  "framing": {
    "resolution": "1080x1350px (4:5)",
    "focus": "sharp subject focus",
    "composition": "full figure and mugshot details",
    "color_accuracy": "professional, natural tones"
  },
  "style": "Hyper-realistic photography, 8K clarity, DSLR quality, accurate color grading, natural lens blur, vintage photo aesthetic, true-to-life detail",
  "watermark": "© xmiiru",
  "negative_prompt": [
    "No anime",
    "No cartoon",
    "No digital painting",
    "No illustration",
    "No 3D render",
    "No CGI",
    "No stylized features",
    "No plastic/doll-like skin",
    "No fantasy glow",
    "No cinematic effects",
    "No airbrushed smoothing",
    "No overexposure",
    "No unnatural blur",
    "No video-game/Unreal Engine style",
    "No sketch",
    "No artificial lighting effects",
    "No unrealistic proportions/textures",
    "No multiple shoes",
    "No modern background elements"
  ]
}
```

---

## Refrigerator magnet prompt word template

![Refrigerator magnet prompt word template](https://opennana.com/awesome-prompt-gallery/images/714.jpeg)

- **Model:** Nano banana pro
- **Source:** [@berryxia_ai](https://x.com/berryxia_ai/status/1996017856782499963)
- **Tags:** animal, architecture, character, food, gaming, nature, photography, toy, vehicle

**Prompt:**

```
# Role:
You are an expert Visual Anthropologist and Knolling Photographer. Your goal is to deconstruct a [City Name] into a high-density, encyclopedic "Kit of Parts" using realistic 3D miniature magnets.

# Critical Constraints (The "Anti-Duplication" Rule):
**STRICT NO REPETITION:** Every single item in the collection must be a completely distinct object category. You cannot have two different bowls of noodles, or two different types of teacups. If you have a cooked dish, the next food item must be a raw ingredient or a packaged snack. **Diversity is key.**

# Design Guidelines:

1.  **Layout & Density:**
    * **Strict Knolling Grid:** All items arranged in perfect parallel lines and 90-degree angles.
    * **High Count:** Aim for 15-20 distinct items filling the frame evenly.
    * **Centerpiece:** The main landmark sits in the middle, surrounded by the smaller cultural artifacts.

2.  **Content Categories (Must define specific, non-repeating items across these tiers):**

    * **Tier 1: Architecture & Space**
        * 1x Main Landmark Model (Centerpiece).
        * 1x Secondary Urban Element (e.g., A specific street sign, an ancient gate, a unique lamppost).

    * **Tier 2: Gastronomy (The full spectrum)**
        * 1x Signature Finished Dish (Cooked).
        * 1x Iconic Street Snack (Ready-to-eat).
        * **1x Raw Biodiversity/Ingredient Source** (Crucial: e.g., A bundle of raw spices, a specific local fruit in its natural state, a whole uncooked fish, raw tea leaves).

    * **Tier 3: People & Culture (Deep Dive)**
        * 1x Typical Character Figurine (e.g., A local profession).
        * **1x Ethnic/Historical Costume Figurine** (Specific to the region's minority groups or deep history, distinct from the typical character).
        * 1x Cultural Artifact/Tool (e.g., Musical instrument, game piece, traditional craft tool).

    * **Tier 4: Life & Nature**
        * 1x Distinctive Local Transport vehicle.
        * 1x Representative Flora or Fauna (Plant or Animal).

3.  **Weather & Identity Integration:**
    * **Identity Badge:** A ceramic/metal magnet with "[CITY NAME] & [Local Language Name]".
    * **Weather Note:** A sticky note with "[Temp]°C" and a sketch.
    * **Physical Weather Icon:** A separate, distinct magnet representing the weather condition (e.g., a cloud magnet, a sun magnet, a raindrop magnet).

4.  **Material & Aesthetic:**
    Realistic miniature textures: glazed ceramic, painted resin, die-cast metal. Studio lighting, clean neutral background.

# Output Format (Directly output the English Prompt):

/imagine prompt: An overhead, high-density knolling photography shot of a comprehensive miniature kit representing [City Name], composed of 18+ distinct 3D fridge magnets and artifacts arranged in a strict grid.
**The Centerpiece:** A detailed model of [Main Landmark].
**Gastronomy Spectrum:** Surrounding items include a bowl of [Cooked Dish], a [Street Snack Item], and a raw bundle of [Specific Raw Ingredient].
**Cultural Depth:** Figures include a [Typical Character Figurine] and a distinct [Ethnic/Historical Costume Figurine]. Cultural tools include a [Artifact/Tool].
**Urban Life & Nature:** A [Vehicle Type], a [secondary urban element], and a [Flora/Fauna item].
**Identity & Weather:** A top-center badge magnet reads "[CITY NAME] [Native Name]". Beside it, a yellow sticky note says "[Temp]°C" with a [Weather Icon]. A separate, small [Physical Weather Magnet, e.g., Cloud/Sun] is placed nearby.
**Style:** No object types are repeated. Materials are rich mix of glossy resin, ceramic glaze, and painted metal. Museum archive quality, studio lighting, 8k, octane render, macro photography --v 6.0 --style raw
```

---

## Young woman taking selfie in front of bathroom mirror

![Young woman taking selfie in front of bathroom mirror](https://opennana.com/awesome-prompt-gallery/images/724.jpeg)

- **Model:** Nano banana pro
- **Source:** [@gaucheai](https://x.com/gaucheai/status/1996184483343520186)
- **Tags:** animal, gaming, interior, logo, minimalist, nature, photography, vehicle

**Prompt:**

```
{
  "subject": {
    "description": "Young woman taking bathroom mirror selfie, innocent doe eyes but the outfit tells another story",
    "mirror_rules": "facing mirror, hips slightly angled, close to mirror filling frame",
    "age": "early 20s",
    
    "expression": {
      "eyes": "big innocent doe eyes looking up through lashes, 'who me?' energy",
      "mouth": "soft pout, lips slightly parted, maybe tiny tongue touching corner",
      "brows": "soft, slightly raised, faux innocent",
      "overall": "angel face but devil body, the contrast is the whole point"
    },
    
    "hair": {
      "color": "platinum blonde",
      "style": "messy bun or claw clip, loose strands framing face, effortless"
    },
    
    "body": {
      "waist": "tiny",
      "ass": "round, full, fabric of shorts riding up and clinging between cheeks, every curve visible through thin athletic material",
      "thighs": "thick, soft, shorts barely containing"
    },
    
    "clothing": {
      "top": {
        "type": "ULTRA mini crop tee",
        "color": "yellow",
        "graphic": "single BANANA logo/graphic",
        "fit": "barely containing chest, fabric stretched tight, ends just below, shows full stomach"
      },
      "bottom": {
        "type": "tight tennis skort or athletic booty shorts",
        "color": "white",
        "material": "thin stretchy athletic fabric",
        "fit": "vacuum tight, riding up, clinging between cheeks, fabric creases visible, leaving nothing to imagination"
      }
    },
    
    "face": {
      "features": "pretty - big eyes, small nose, full lips",
      "makeup": "minimal, natural, lip gloss, no-makeup makeup"
    }
  },

  "accessories": {
    "headwear": {
      "type": "Goorin Bros cap",
      "details": "black with animal patch, worn backwards or tilted"
    },
    "headphones": {
      "type": "over-ear white headphones",
      "position": "around neck"
    },
    "device": {
      "type": "iPhone",
      "details": "visible in mirror, held at chest level"
    }
  },

  "photography": {
    "camera_style": "casual iPhone mirror selfie, NOT professional",
    "quality": "iPhone camera - good but not studio, realistic social media quality",
    "angle": "eye-level, straight on mirror",
    "shot_type": "3/4 body, close to mirror",
    "aspect_ratio": "9:16 vertical",
    "texture": "natural, slightly grainy iPhone look, not over-processed"
  },

  "background": {
    "setting": "regular apartment bathroom",
    "style": "normal NYC apartment bathroom, not luxury",
    "elements": [
      "white subway tile walls",
      "basic bathroom mirror with good lighting above",
      "simple white sink vanity",
      "toiletries visible - skincare bottles, toothbrush holder",
      "towel hanging on hook",
      "maybe shower curtain edge visible",
      "small plant on counter"
    ],
    "atmosphere": "real bathroom, lived-in, normal home",
    "lighting": "good vanity lighting above mirror - bright, even, flattering but not studio"
  },

  "vibe": {
    "energy": "innocent face + sinful body = the whole game",
    "mood": "just got ready for tennis but making content first, 'what?' expression while wearing basically nothing",
    "contrast": "doe eyes + ass eating the shorts = lethal",
    "caption_energy": "'tennis anyone? 🍌' or 'running late oops'"
  }
}
```

---

## Each frame of the 6-panel comic has a different style

![Each frame of the 6-panel comic has a different style](https://opennana.com/awesome-prompt-gallery/images/775.jpeg)

- **Model:** Nano banana pro
- **Source:** [@songguoxiansen](https://x.com/songguoxiansen/status/1996758924528124001)
- **Tags:** gaming, logo, pixel, retro

**Prompt:**

```
Panel 1: Chinese ink animation style

Chinese ink animation style, Officer Judy is wearing a police uniform and watching a farmer sitting next to a big tree stump in a daze while wearing a police uniform. The light is bright and the fur texture is realistic. There is a speech bubble in the picture, which accurately writes Chinese characters: "Judy saw a farmer sitting next to a tree stump in a daze."

Panel 2: Ghibli hand-painted style

Hayao Miyazaki's Studio Ghibli hand-drawn animation style, fresh watercolor texture, green grass and blue sky, Judy is asking, the sheep farmer excitedly points to the tree stump to explain, the picture is healing, there is a speech bubble in the picture, with Chinese characters accurately written in it: "The farmer said: 'Yesterday a rabbit hit and died here, I am waiting for the next one.'"

Box 3: 1930s retro rubber hose style

The retro rubber tube animation style of the 1930s, with a black and white film texture, is similar to the style of "Cuphead". Judy was shocked, her body leaned back exaggeratedly, her ears were erect and elongated, her eyes were as big as saucers, and her expression was unbelievable. The retro speech bubble with jagged edges accurately wrote Chinese characters: "Judy was shocked: 'What? You expected this kind of chance?'"

Panel 4: Spider-Man Parallel Universe Beauty Style

"Spider-Man: Into the Spider-Verse" American comic pop art style, half-tone dot effect, chromatic aberration glitch art, Nick walked over slowly, wearing sunglasses, holding a claw popsicle in his hand, with a mischievous smile on his face, there were dynamic graffiti lines in the background, and Chinese characters were accurately written in the comic-style dialogue bubble: "Nick walked over slowly, with a mischievous smile on his face"

Panel 5: Aardman Clay Animation Style

Aardman Studio's clay animation style, stop-motion animation, similar to the texture of "Chicken Run", you can see the fingerprint details on the plasticine. Nick took off his sunglasses and pointed at the sheep farmer to explain to Judy. Nick has a signature wide mouth and big teeth, a funny expression, and precise Chinese characters written in the clay-textured speech bubbles: "Nick said: 'Carrot head, this is called waiting for rabbits, he is daydreaming.'"

Box 6: 16-bit pixel game style

16-bit retro pixel art style, Super Nintendo game screen, bright pixel color blocks, Judy reluctantly pulls the sheep farmer to work, Nick spreads his hands behind him and shrugs, like the clearance screen of an RPG game, the game dialog box accurately writes Chinese characters: "Judy drags the farmer to work, Nick helplessly spreads his hands"
```

---

## A 3D game level map poster

![A 3D game level map poster](https://opennana.com/awesome-prompt-gallery/images/809.jpeg)

- **Model:** Nano banana pro
- **Source:** [@op7418](https://x.com/op7418/status/1997722842042085409)
- **Tags:** clay, gaming, landscape, poster, typography, ui

**Prompt:**

```
Based on the theme [The path to advancement for front-end engineers], create a 3D game level map poster.

Picture structure: A winding 3D road extends from the bottom of the picture to the clouds at the top, divided into three main "level stages":

Bottom: Noob Village (Level 1: Noob)
Model: Simple grass scene. Place basic tools.
Road sign: A wooden sign is inserted with the title written on it, and a paragraph below to introduce the standards of the current level.

Central: Proving Grounds (Level 10: Pro)
Model: The terrain becomes complex (forest or rocky). Place advanced equipment.
Visual: The road becomes steeper, symbolizing increasing difficulty.
Road sign: A wooden sign is inserted with the title written on it, and a paragraph below to introduce the standards of the current level.

Top: Temple of God (Level 99: Master)
Model: A glorious temple or high-tech laboratory floating in the clouds. Place the ultimate artifact.
Vision: Glowing gold, rainbow or treasure chest.
Road sign: A wooden sign is inserted with the title written on it, and a paragraph below to introduce the standards of the current level.

Data and layout: Path lines: Dotted lines connect the stages, with small footprints on them.

Time Elapsed/Cost: Next to each stage, a game UI-style floating window displays "Estimated Time Elapsed" or "Estimated Gold Coin Consumption".

Style and Rendering: Nintendo-style clay. Colors are bright and saturated.
```

---

## Tokyo Tower is occupied by a super giant cat

![Tokyo Tower is occupied by a super giant cat](https://opennana.com/awesome-prompt-gallery/images/842.jpeg)

- **Model:** Nano banana pro
- **Source:** [@KanaWorks_AI](https://x.com/KanaWorks_AI/status/1999350454980067595)
- **Tags:** architecture, gaming, landscape, toy

**Prompt:**

```
A scene where 【Tokyo Tower】is occupied by a super gigantic, adorable 【cat】.The surrounding buildings appear as small as toy models, while the 【cat】 is enormously large.
The setting features a realistic city environment.
The overall mood is quiet, warm, soothing, and cute.
```

---

