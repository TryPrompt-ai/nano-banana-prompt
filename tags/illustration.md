# Illustration Prompts

> Found 122 prompts in this category.

---

## Gorillaz style

![Gorillaz style](https://opennana.com/awesome-prompt-gallery/images/215.png)

- **Model:** None
- **Source:** [@azed_ai](https://x.com/azed_ai/status/1942586412920103180)
- **Tags:** illustration

**Prompt:**

```
Restyle this image into a gritty Gorillaz-style illustration, bold thick black outlines, sharp angular edges, flat expressive lighting, stylized high-contrast shadows, dirty distressed surface textures, muted color palette: washed-out teals, olive greens, rusty reds, mustard yellows, dusty browns, raw grungy urban atmosphere, comic book flatness mixed with painterly grit, hand-drawn finish with faded gradients, graphic novel aesthetic
with a rebellious, animated tone, dark stylish tone, full of attitude.
```

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

## One hand holds a slender vertical hollow bookmark

![One hand holds a slender vertical hollow bookmark](https://opennana.com/awesome-prompt-gallery/images/1022.jpeg)

- **Model:** Nano banana pro
- **Source:** [@firatbilal](https://x.com/firatbilal/status/2003553245499916501)
- **Tags:** 3d, architecture, illustration, landscape, logo, paper-craft, photography

**Prompt:**

```
Your city
{
  "image_request": {
    "subject": "A person's hand holding a long, narrow vertical die-cut bookmark",
    "bookmark_design": {
      "style": "Intricate layered paper-cut illustration, 3D depth, whimsical artistic style",
      "content": "Iconic landmarks and symbols of {{location}} depicted inside the bookmark frame, some elements slightly popping out of the edges (die-cut)",
      "artistic_elements": "Delicate textures, vibrant colors, miniature architectural details"
    },
    "background": {
      "setting": "A romantic, cinematic wide shot of the actual {{location}} skyline and scenery",
      "depth_of_field": "Soft bokeh, blurred background to emphasize the bookmark in focus",
      "time_of_day": "{{time_of_day}}",
      "lighting_effects": "Atmospheric lighting matching the {{time_of_day}}, golden hour glows, city lights, or soft daylight"
    },
    "composition": {
      "framing": "Close-up on the hand and bookmark, centered vertically",
      "vibe": "Nostalgic, aesthetic, travel-inspired, poetic",
      "color_palette": "Harmonized colors between the bookmark's art and the real-world background"
    },
    "technical_specs": {
      "quality": "8k resolution, highly detailed, photorealistic hand, sharp focus on bookmark",
      "aspect_ratio": "3:4"
    }
  },
  "variables": {
    "location": ["Istanbul", "Paris", "Tokyo", "London", "Rome"],
    "time_of_day": ["Sunrise", "Sunset", "Night with city lights", "Bright daylight"]
  }
}
```

---

## Hyper-realistic style real and cartoon separation effect

![Hyper-realistic style real and cartoon separation effect](https://opennana.com/awesome-prompt-gallery/images/667.jpeg)

- **Model:** Nano banana pro
- **Source:** [@ZaraIrahh](https://x.com/ZaraIrahh/status/1995304550610407807)
- **Tags:** cartoon, character, illustration, interior, landscape, minimalist, nature, paper-craft, pixel, portrait, retro, vehicle

**Prompt:**

```
{
  "image_generation": {
    "requirements": {
      "face_preservation": {
        "preserve_original": true,
        "accuracy_level": "100% identical to reference",
        "details": [
          "real facial proportions",
          "exact skin texture",
          "true eye shape and color",
          "natural soft makeup",
          "subtle upward eyeliner",
          "soft pink eyeshadow",
          "natural rosy lips"
        ]
      },
      "pose": {
        "match_reference_pose": true,
        "description": "Chest-up portrait, face facing forward but gently tilted to the right from the viewer’s perspective."
      },
      "lighting": {
        "match_reference_lighting": true,
        "type": "soft diffused indoor lighting",
        "direction": "from the front and slightly from the left",
        "shadows": "gentle soft shadows on the sides of the face and neck",
        "background_tone": "soft neutral with slight bluish tint"
      }
    },

    "subject": {
      "gender": "female",
      "hairstyle": {
        "match_reference": true,
        "description": "same exact hairstyle as in reference image"
      },
      "expression": "neutral, slightly thoughtful",
      "clothing": {
        "top": "simple black T-shirt",
        "necklace": "thin silver necklace with a small minimal pendant"
      }
    },

    "composition": {
      "frame": "chest-up portrait",
      "orientation": "frontal with slight rightward tilt",
      "style": "hyper-realistic with split real/cartoon effect"
    },

    "special_effects": {
      "split_effect": {
        "type": "irregular centered tear",
        "edges": "white angled torn-paper look",
        "description": "image appears ripped down the middle"
      },

      "realistic_side": {
        "background": "soft, neutral, slightly bluish environment",
        "filters": [
          "soft analog grain",
          "lightly aged texture",
          "reduced saturation",
          "subtle film imperfections"
        ],
        "overlays": [
          "blue stylized teardrop stickers below the left eye",
          "small 'Zzz' sleep symbols near forehead",
          "yellow crescent moon in upper-left corner",
          "light blue hand-drawn cloud"
        ]
      },

      "illustrated_side": {
        "art_style": "bold cartoon, digital illustration",
        "color_palette": "bright, vibrant, saturated",
        "hair": "same tone as realistic side but stylized",
        "eyes": "exaggerated eyeliner, dramatic expression",
        "background": "vibrant light pink pop-art style",
        "decorations": {
          "kawaii_elements": [
            "Hello Kitty holding a microphone",
            "pixel-art pink mascot character",
            "yellow stars",
            "pink hearts",
            "colorful planets",
            "bold pink Japanese characters"
          ]
        }
      }
    },

    "aesthetic": {
      "overall_tone": "soft, dreamy, lightly vintage",
      "lighting_consistency": "must match reference perfectly",
      "skin_texture_realism": "high",
      "blending_quality": "smooth, natural transition between real and illustrated halves with crisp tear edge"
    },

    "output": {
      "style": "hyper-realistic + digital cartoon fusion",
      "quality": "ultra-high-resolution",
      "filters": [
        "subtle analog vintage film filter",
        "soft grain"
      ]
    }
  }
}
```

---

## Childlike style illustration

![Childlike style illustration](https://opennana.com/awesome-prompt-gallery/images/981.jpeg)

- **Model:** Nano banana pro
- **Source:** [@VoxcatAI](https://x.com/VoxcatAI/status/2004021013798179014)
- **Tags:** illustration, paper-craft

**Prompt:**

```
Please generate an illustration of [theme/subject]. The overall style is whimsical and childlike in children's book illustrations: outlines are sketched with loose black ink lines, and the details are not overly realistic; superimposed with soft watercolor blooming and spotting, the colors are clean, warm, and slightly paper texture. The temperament of the picture is suitable for postcards/children's picture books/Christmas advertising campaigns/emotional editorial illustrations. The atmosphere is sincere, healing and a little nostalgic. The composition is simple, the white space is comfortable, and the protagonist is clear and prominent. No photo texture, no 3D rendering, no overly sharp details. No watermarks or logos.
```

---

## Display board for residential building created by architectural illustrator

![Display board for residential building created by architectural illustrator](https://opennana.com/awesome-prompt-gallery/images/966.jpeg)

- **Model:** Nano banana pro
- **Source:** [@AllaAisling](https://x.com/AllaAisling/status/2003122606527205436)
- **Tags:** 3d, architecture, illustration, paper-craft, photography

**Prompt:**

```
An expert architectural illustrator's presentation board for a [STYLE] residence featuring [KEY ARCHITECTURAL ELEMENTS].
The canvas flows left to right: black and white 2D drawings (Site Plan, Floor Plans) on the left, Elevations and Cross-Section in the center, and a photorealistic 3D render at [TIME OF DAY/LIGHTING] on the right.
Unified aesthetic blending [LINEWORK STYLE] with [TEXTURE/MATERIAL]. [TECHNICAL DRAWING TONES] transitioning to [RENDER COLOUR PALETTE]. Title block reads '[PROJECT NAME]'.
```

---

## triptych collage depicts three consecutive moments of women

![triptych collage depicts three consecutive moments of women](https://opennana.com/awesome-prompt-gallery/images/967.jpeg)

- **Model:** Nano banana pro
- **Source:** [@underwoodxie96](https://x.com/underwoodxie96/status/2003340602193379443)
- **Tags:** illustration, landscape, nature, photography, portrait, retro

**Prompt:**

```
A real-life woman is presented in a vertical triptych collage composition, depicting three consecutive moments (a calm stance, a direct confrontation, and a startled reaction). Each panel deliberately uses left–right offset positioning to create a coherent visual narrative flow.

The image is shot in a photorealistic, cinematic live-action style, high resolution with subtle natural grain, true contrast, hard natural daylight, a clear blue sky, and deep depth of field consistent with real lens behavior. The scene takes place in an open outdoor environment.

The subject wears a cowboy hat, a short-sleeve button-up shirt, and a brownish-red long skirt. Her makeup is retro-inspired, with distinct red lipstick and clearly defined eye makeup.

Top panel:
The subject is positioned toward the right, leaving open sky on the left. She stands with arms crossed, looking toward the lower-left with a surprised expression.
Middle panel:
The subject is positioned toward the left, aiming a firearm with the barrel angled toward the lower-right. Her expression is focused and sharp, and the shot is taken from a slightly top-down angle. In this panel, both the subject and the weapon intentionally break through the top and bottom panel borders, overlapping the frame lines to create a clear layered effect. The middle panel serves as the primary visual focal point.

Bottom panel:
The subject is positioned in the lower-right corner, leaving more negative space on the left. She raises both hands defensively, her eyes naturally widened in surprise, looking toward the upper-left. The subject intentionally breaks the panel frame and overlaps the border lines, forming a distinct layered composition.
The image maintains a 2:3 aspect ratio and a photorealistic live-action style, explicitly avoiding illustration or comic aesthetics.
```

---

## Woman extends index finger forward towards camera lens

![Woman extends index finger forward towards camera lens](https://opennana.com/awesome-prompt-gallery/images/969.jpeg)

- **Model:** Nano banana pro
- **Source:** [@Ankit_patel211](https://x.com/Ankit_patel211/status/2003366639170113824)
- **Tags:** branding, cartoon, food, illustration, landscape, neon, photography, pixel, portrait, sci-fi, ui, vehicle

**Prompt:**

```
{
  "request_id": "portrait_neon_urban_001",
  "configuration": {
    "model": "v6. 0_or_latest",
    "output_settings": {
      "dimensions": {
        "width": 1080,
        "height": 1920,
        "aspect_ratio": "9:16",
        "target_resolution": "64K DSLR"
      }
    }
  },
  "scene_composition": {
    "subject": {
      "entity": "Young woman",
      "pose": "Standing confidently",
      "action": "Extending index finger forward toward camera lens",
      "interaction": "Dynamic gesture / POV interaction",
      "wardrobe": {
        "outerwear": "dark crimson red striped baseball-style shirt",
        "undergarment": "Light inner shirt",
        "bottoms": "Cargo pants",
        "accessories": [
          "Necklace",
          "Crossbody bag"
        ]
      }
    },
    "environment": {
      "location": "Urban street",
      "time_of_day": "Night",
      "ambience": "Neon-lit",
      "background_elements": [
        "Colorful city lights",
        "Blurred passersby"
      ]
    },
    "cinematography": {
      "camera": {
        "perspective": "Wide-angle",
        "depth_of_field": "Soft bokeh",
        "motion": "Slight motion blur"
      },
      "lighting": {
        "style": "Cinematic",
        "primary_sources": [cyber punk street lights", "City glow"]
      },
      "ui_overlay": {
        "enabled": true,
        "aesthetic": "Smartphone video recording",
        "on_screen_elements": [
          "REC 00:00:00",
          "8K/60fps",
          "Frame brackets",
          "VIDEO indicator",
          "CINEMATIC indicator"
        ]
      }
    }
  },
  "technical_rendering": {
    "style": "Hyper-realistic",
    "engines": [
      "Octane Render",
      "Unreal Engine 5"
    ]
  },
  "negative_prompt": {
    "stylistic_exclusions": [
      "cartoon",
      "illustration",
      "anime"
    ],
    "quality_exclusions": [
      "low quality",
      "pixelated",
      "blurry"
    ],
    "anatomical_exclusions": [
      "bad anatomy",
      "deformed hands",
      "extra fingers",
      "missing limbs",
      "bad proportions"
    ],
    "branding_exclusions": [
      "watermark (except for requested UI overlays)"
    ]
  }
}
```

---

## museum specimen photography

![museum specimen photography](https://opennana.com/awesome-prompt-gallery/images/976.jpeg)

- **Model:** Nano banana pro
- **Source:** [@Gdgtify](https://x.com/Gdgtify/status/2003466876115177544?referrer=grok.com)
- **Tags:** 3d, food, illustration, landscape, paper-craft, photography, toy, vehicle

**Prompt:**

```
<instruction>
Input A: user uploads an image or shares name of dish

Logic  Identify the historical inventor (e.g., Raffaele Esposito or Henri Charpentier) and the exact year of origin.

Task: A hyper-realistic 4:5 macro photograph of an oversized, open antique culinary codex resting on a dark velvet museum plinth. 

 Left Page (The Living Diorama): 
The left side of the book is hollowed out like a secret compartment. Inside is a breathtaking 3D miniature scene. A highly detailed figurine of the dish’s inventor is captured mid-motion in a period-accurate kitchen. Around them are microscopic versions of the 10-15 key ingredients, each in its own tiny hand-blown glass vial or micro-wooden crate. Include miniature brass cooking tools specific to the era. The scene is lit from within the "pages" by a warm, magical amber glow.

 Right Page (The Technical Recipe): 
The right page is flat, aged parchment featuring elegant, faded Spencerian calligraphy and hand-painted watercolor illustrations. 
1. Top: The dish name in both English and its native language, with the bold "Origin Date."
2. Middle: A vertical "Ingredient Blueprint" with hyper-detailed sketches of each raw component.
3. Bottom: A small, detailed "Origin Map" showing the specific city of birth, styled like a 19th-century cartographic inset. 
4. Text: Visible, legible recipe steps written in ink that looks slightly raised on the paper.

Style: 
Museum specimen photography. 85mm macro lens. The lighting should be a mix of cool gallery spotlights and the warm "internal" glow of the book's diorama. Extreme texture on the weathered leather binding and the tooth of the paper.
Output: ONE image, 4:5 aspect ratio.
</instruction>
```

---

## Nine-square grid collage

![Nine-square grid collage](https://opennana.com/awesome-prompt-gallery/images/987.jpeg)

- **Model:** Nano banana pro
- **Source:** [@msjiaozhu](https://x.com/msjiaozhu/status/2003819615282229720)
- **Tags:** cartoon, character, illustration, photography, portrait, vehicle

**Prompt:**

```
{
  "project_settings": {
    "task_type": "Single_Image_Contact_Sheet (9-Grid)",
    "aspect_ratio": "3:4",
    "resolution_mode": "High / Upscale (Crucial for face details in grids)",
    "batch_size": 1
  },
  "reference_config": {
    "usage": "Upload Reference Image -> Set Strength to 0.5-0.7",
    "purpose": "Define the 3x3 grid structure and character identity"
  },
  "prompt_payload": {
    "structure_trigger": "A single contact sheet image containing a 3x3 photo grid matrix",
    "grid_logic": "9 distinct panels separated by thin white borders",
    "subject_consistency": "Same young asian woman in all 9 panels, identical outfit, identical hairstyle",
    "expression_variation": "9 different facial expressions (winking, tongue out, surprised, laughing, serious, etc.)",
    "camera_angles": "Varied angles in each panel (high angle, low angle, straight on)",
    "visual_style": "Photorealistic, Studio lighting, Light grey background, K-pop idol photocard style"
  },
  "negative_prompt": [
    "One single portrait",
    "merged bodies",
    "distorted grid lines",
    "missing panels",
    "cartoon",
    "illustration",
    "different clothes"
  ]
}
```

---

## Embroidery illustration style

![Embroidery illustration style](https://opennana.com/awesome-prompt-gallery/images/8.png)

- **Model:** None
- **Source:** [@Artedeingenio](https://x.com/Artedeingenio/status/1924032621220188340)
- **Tags:** illustration

**Prompt:**

```
A handcrafted illustration that simulates traditional embroidery using colorful threads on linen fabric. All elements are “stitched” with visible yarn textures, using techniques like satin stitch, backstitch, and French knots. Raised contours and directional thread flow create a tactile, cozy appearance. The background is made of woven linen, with gentle pastel or folk-inspired colors. The composition is friendly and magical, evoking a storybook charm. Include decorative details such as flowers, suns, clouds, trees or symbols to enhance the folk embroidery style.
```

---

## creative advertising

![creative advertising](https://opennana.com/awesome-prompt-gallery/images/14.png)

- **Model:** None
- **Source:** [@azed_ai](https://x.com/azed_ai/status/1924090458298609881)
- **Tags:** branding, illustration, neon, product

**Prompt:**

```
A high-impact advertisement set against a clean, dark or high-contrast background. A [product] is centered, sharply lit and highly detailed. Around it, surreal, stylized visual [elements] illustrations explode outward (e.g., musicians, runners, curls, sunbursts), vibrant color palette, neon. bold uppercase ad copy at the top that reads [TEXT] and the brand logo at the bottom, modern Ad
```

---

## Flat design equilateral style

![Flat design equilateral style](https://opennana.com/awesome-prompt-gallery/images/23.png)

- **Model:** None
- **Source:** [@Artedeingenio](https://x.com/Artedeingenio/status/1924388407939076377)
- **Tags:** illustration, infographic, minimalist, ui

**Prompt:**

```
A flat isometric digital illustration of [describe the subject: e.g., a modern workspace, a city block, a group of app icons, a sports shop], clean lines and geometric forms, bright pastel colors, simplified perspective with 3D depth, minimal shading, white background or light gradient. Style resembles modern vector infographics, ideal for UI, app design or web visuals.
```

---

## character drama exaggerated style

![character drama exaggerated style](https://opennana.com/awesome-prompt-gallery/images/35.png)

- **Model:** None
- **Source:** [@dotey](https://x.com/dotey/status/1924288320881750108)
- **Tags:** character, illustration, minimalist, portrait, typography

**Prompt:**

```
A high-resolution vertical Pixar-style 3D character illustration.

Main character:  
Salvador Dalí — depicted as a tall, slim, and slightly exaggerated Pixar-style 3D character.  
Wearing a classic blue shirt, yellow tie, high-waisted plaid trousers with suspenders, and leather shoes.  
His iconic long upturned mustache, slick black hair, sharply arched eyebrows, and slightly eccentric posture.  
Stands with chest out, one hand on hip, head tilted slightly back in his typical theatrical flair.

Background:  
Flat, clean yellow background with subtle surface texture.  
Strong sunlight from top-left casts a distinct and enlarged shadow on the wall behind him.

Key Concept – Shadow as spiritual projection:  
The shadow cast behind him does **not** mirror his body shape.  
Instead, it takes the form of one of his most iconic artworks —  
a surreal melted clock with long dripping arms, inspired by “The Persistence of Memory”.

The melted clock shadow is positioned diagonally, starting from his shoulder,  
stretching wide and low across the yellow wall, surreal and fluid, yet unmistakably symbolic.

This shadow is **Dalí’s legacy made visible** — a symbolic extension of his identity through time, dream, and visual distortion.

Lighting & Rendering:  
Pixar-like rendering with detailed but stylized textures.  
Use subtle filmic grain, soft shadows, and warm color grading.  
Subtle sparkles or light speckles inside the shadow to evoke dreamlike texture.

Typography (top-left corner):  
“Salvador Dalí” in minimalist black sans-serif font, “Dalí” bolded.
```

---

## Logo hyper-realistic miniature photography

![Logo hyper-realistic miniature photography](https://opennana.com/awesome-prompt-gallery/images/42.jpeg)

- **Model:** None
- **Source:** [@alex_prompter](https://x.com/alex_prompter/status/1923036265013801025)
- **Tags:** branding, illustration, landscape, logo, photography

**Prompt:**

```
Recreate this [BRAND NAME] logo follow the JSON aesthetic below: 
{
    "style": "hyperrealistic miniature photography",
    "scene": {
        "main_subject": "uploaded logo scaled to appear as a large physical object",
        "interaction": "tiny human figures interacting with the logo",
        "activities": [
            "cleaning the logo",
            "painting parts of the logo",
            "climbing ladders on the logo surface",
            "taking photographs of the logo"
        ],
        "environment": "studio-style white background to focus on details",
        "perspective": "frontal view with shallow depth of field for macro effect"
    },
    "logo_handling": {
        "preserve_original_logo_shape": true,
        "preserve_original_logo_colors": true,
        "preserve_text_in_logo": true,
        "use_logo_as_structural_object": true,
        "adapt_logo_to_3D_surface": true
    },
    "miniature_elements": {
        "figure_scale": "1:50 ratio to logo",
        "figure_details": "tiny realistic humans with props like brushes, ropes, and scaffolding",
        "interaction_type": "physical interaction, not illustration or overlay"
    },
    "lighting": {
        "key_light": "soft diffused white light from above",
        "fill_light": "mild side fill to reveal depth and volume",
        "shadows": "realistic and subtle around base and figures"
    },
    "camera": {
        "focus_mode": "macro with shallow depth of field",
        "angle": "slightly top-down to give sense of scale",
        "background": "clean white surface, no gradient, no transparency"
    },
    "post_processing": {
        "realism_enhancement": "preserve logo clarity, crisp text, no artistic blurring",
        "forbid_artistic_filters": true,
        "forbid_color_modifications": true
    },
    "image_constraints": {
        "transparent_background": false,
        "include_text": true,
        "adapt_to_uploaded_logo": true,
        "obey_logo_shape": true,
        "preserve_original_logo_colors": true
    },
    "notes": "The uploaded logo must be clearly recognizable, unmodified, and serve as the core structural element of the scene. Tiny people should interact with the logo realistically, as if it were a large 3D object in a physical miniature world."
}
```

---

## Colorful cartoon playful icons and logos

![Colorful cartoon playful icons and logos](https://opennana.com/awesome-prompt-gallery/images/55.jpeg)

- **Model:** None
- **Source:** [@gnrlyxyz](https://x.com/gnrlyxyz/status/1925553233881145499)
- **Tags:** cartoon, illustration, vehicle

**Prompt:**

```
Create a 2D digital illustration of the [FIREFOX] logo in a colorful cartoon style with bold black outlines. The icon design should feature playful, vibrant solid colors such as pink, teal, orange, yellow, and purple, applied in a flat, bold way. Give the shapes a slightly exaggerated, bubbly form with rounded edges and fun details like starbursts, stripes, or spark effects if relevant. Keep the illustration simple and stylized with a hand-drawn look. Use thick outlines to emphasize form. Vector friendly. White background. Square aspect ratio.
```

---

## Cute miniature scene

![Cute miniature scene](https://opennana.com/awesome-prompt-gallery/images/67.jpeg)

- **Model:** None
- **Source:** [@ZHO_ZHO_ZHO](https://x.com/ZHO_ZHO_ZHO/status/1925878276133708224)
- **Tags:** clay, illustration, landscape, nature, paper-craft, vehicle

**Prompt:**

```
{
    "style": "miniature handcrafted diorama",
    "material": "tree branches, cardboard, clay, moss, dried flowers, paper",
    "surface_texture": "organic, rough and varied (wood grain, soft moss, paper texture)",
    "lighting": {
        "type": "soft ambient natural light",
        "intensity": "low to moderate",
        "direction": "diffused overhead",
        "accent_colors": [
            "forest green",
            "earth brown",
            "soft beige",
            "muted pink"
        ],
        "reflections": false,
        "refractions": false,
        "dispersion_effects": false,
        "bloom": false
    },
    "color_scheme": {
        "primary": "natural greens and browns",
        "secondary": "soft neutral tones (cardboard, clay, paper)",
        "highlights": "light falling on the open book and cat’s glasses",
        "rim_light": "subtle natural edge light from the forest opening"
    },
    "background": {
        "color": "natural moss green",
        "vignette": false,
        "texture": "moss and dried floral structure"
    },
    "post_processing": {
        "chromatic_aberration": false,
        "glow": false,
        "high_contrast": false,
        "sharp_details": true,
        "film_grain": false
    },
    "form_composition": {
        "scene_elements": [
            "a small girl sitting on a balcony holding an open miniature book",
            "a cat with glasses observing the book's illustrations",
            "a treehouse made from twigs, cardboard, and clay",
            "balcony and surrounding forest made of moss and dried flowers"
        ],
        "scale": "miniature",
        "theme": "childlike wonder and storytelling in a handcrafted world",
        "visual_metaphor": [
            "curiosity",
            "quiet companionship",
            "imagination in nature"
        ]
    },
    "metadata": {
        "artist": "-Zho-",
        "series": "ZH4O"
    }
}
```

---

## Black and white comic style illustration

![Black and white comic style illustration](https://opennana.com/awesome-prompt-gallery/images/76.png)

- **Model:** None
- **Source:** [@CharaspowerAI](https://x.com/CharaspowerAI/status/1923778050845528388)
- **Tags:** character, illustration

**Prompt:**

```
Highly dramatic and epic black and white manga-style illustration of [Your character and description].  Powerful, dynamic pose, exaggerated features emphasizing the intensity of the scene. Background with explosive energy bursts, lightning effects, and a whirlwind of debris
```

---

## 3D snack cartoon world

![3D snack cartoon world](https://opennana.com/awesome-prompt-gallery/images/77.jpeg)

- **Model:** None
- **Source:** [@aziz4ai](https://x.com/aziz4ai/status/1925895453217898847)
- **Tags:** branding, cartoon, character, food, illustration, landscape, product, retro, vehicle

**Prompt:**

```
A 3D-rendered digital illustration featuring a retro-style food truck inspired by the brand [INSERT BRAND NAME], designed with smooth pastel colors and soft textures. A black-and-white cartoon character stands beside the truck, holding a product that visually represents the brand. The environment reflects the brand’s world—playful hills, trees, and skies stylized with its color palette and product shapes. The brand’s logo is clearly displayed on the truck, and a short slogan appears naturally within the scene. Format: 1:1, isometric view, cinematic lighting, clean and joyful composition.
```

---

## Neon floral harmony illustration

![Neon floral harmony illustration](https://opennana.com/awesome-prompt-gallery/images/82.png)

- **Model:** None
- **Source:** [@LudovicCreator](https://x.com/LudovicCreator/status/1926246931661042132)
- **Tags:** illustration, nature, neon

**Prompt:**

```
A Neon Floral Harmony illustration of [SUBJECT], with flowers and plants outlined in glowing neon hues. Use vibrant [COLOR1] and [COLOR2] to create a serene yet electrifying botanical scene
```

---

## Outline key lines

![Outline key lines](https://opennana.com/awesome-prompt-gallery/images/112.jpeg)

- **Model:** None
- **Source:** [@umesh_ai](https://x.com/umesh_ai/status/1931637370639520011)
- **Tags:** illustration

**Prompt:**

```
A digital illustration of a [SUBJECT], portrayed with a network of glowing clean pristine blue lines outlining its anatomy. The image is set against a dark background, highlighting the [SUBJECT] form and features. A specific area such as [PART] is emphasized with a red glow to indicate a point of interest or significance. The style is both educational and visually captivating, designed to resemble an advanced imaging technique
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

## Anime mecha stylized mechanical design drawing

![Anime mecha stylized mechanical design drawing](https://opennana.com/awesome-prompt-gallery/images/117.png)

- **Model:** None
- **Source:** [@Artedeingenio](https://x.com/Artedeingenio/status/1931711452160651654)
- **Tags:** character, futuristic, illustration, landscape, sci-fi

**Prompt:**

```
Transform this image into a stylized mechanical design sheet inspired by Japanese anime mecha blueprints.
Render the subject with precise, clean linework and semi-realistic cel-shading, as if it were a technical illustration from an anime artbook.
Break down the design into parts (e.g. head, hand, accessory, full body) and arrange them like a reference sheet, with different angles and views.
Include soft handwritten notes or Japanese characters scattered like concept annotations.
Use muted digital colors (red, gray, metallic tones) and draw the background in a loose watercolor anime landscape style — cliffs, cityscapes, or grassland ruins.
The final composition should feel like an official design page for an animated sci-fi series or manga.
Keep the format horizontal, like a blueprint or character sheet, with a balance between precision and artistic flair.
```

---

## Surreal advertising reimagined

![Surreal advertising reimagined](https://opennana.com/awesome-prompt-gallery/images/126.jpeg)

- **Model:** None
- **Source:** [@aziz4ai](https://x.com/aziz4ai/status/1934702903932957023)
- **Tags:** illustration, landscape, minimalist, photography, product

**Prompt:**

```
“[Product Name]” placed at the center in full photorealism, surrounded by surreal vector illustrations using exactly two bold, vibrant colors that match the product’s mood.
The scene is minimalistic yet energetic, with abstract vector shapes (symbols, lines, expressions, etc.) orbiting or interacting with the product.
Add the real logo clearly and integrate a short 3–4 word slogan at the bottom.
Style: surreal, high-resolution, minimal, cinematic lighting, 1:1 aspect ratio.
```

---

## Prismatic glass icon

![Prismatic glass icon](https://opennana.com/awesome-prompt-gallery/images/135.jpeg)

- **Model:** None
- **Source:** [@gnrlyxyz](https://x.com/gnrlyxyz/status/1934330176113938606)
- **Tags:** illustration, sculpture

**Prompt:**

```
Create a high-resolution illustration of a [skull] icon in the style of a glossy, translucent sculpture. The icon should appear as if made of curved, flowing glass with reflective surfaces. Infuse the form with vivid, refracted rainbow gradients that shift smoothly across its contours. The shape should be abstract yet recognizable, with a sleek, high-gloss finish and soft reflections that mimic light bending through clear material. Center the icon on a solid black background. No shadows, textures, or extra elements. Square aspect ratio.
```

---

## Gumroad style icon

![Gumroad style icon](https://opennana.com/awesome-prompt-gallery/images/138.jpeg)

- **Model:** None
- **Source:** [@gnrlyxyz](https://x.com/gnrlyxyz/status/1934745654888124753)
- **Tags:** cartoon, illustration, interior, paper-craft, vehicle

**Prompt:**

```
Create a high-resolution illustration of a [OBJECT] icon in the style of a flat, outlined sticker graphic. The icon should be made entirely from very thin, solid black outlines with no interior fill. Add a bold, soft-edged sticker-style contour around the icon using a flat, vibrant [YELLOW, BLUE, OR PINK] color. The result should look like a cartoon-style icon cut from black paper, outlined by a bright color. Do not use any white or filled shapes inside. No gradients, no shadows, no textures. Vector-friendly. Black background. Square aspect ratio.
```

---

## vinyl toys

![vinyl toys](https://opennana.com/awesome-prompt-gallery/images/150.png)

- **Model:** None
- **Source:** [@azed_ai](https://x.com/azed_ai/status/1937104120097407069)
- **Tags:** character, illustration, portrait, toy, vehicle

**Prompt:**

```
A comic-style caricature illustration of [subject], with an oversized head and expressive eyes, rendered in a hyper-realistic vinyl toy aesthetic. The character features exaggerated proportions, glossy textures, and playful details, blending caricature art with collectible figure charm.
```

---

## new anime style

![new anime style](https://opennana.com/awesome-prompt-gallery/images/152.png)

- **Model:** None
- **Source:** [@Artedeingenio](https://x.com/Artedeingenio/status/1936716854090760197)
- **Tags:** futuristic, illustration, retro

**Prompt:**

```
Transform this image into a 1960s Tezuka-style illustration. Use big, rounded expressive eyes with bright highlights. Simplify the anatomy with soft, rounded limbs and clean linework. Avoid detailed textures — focus on smooth color fills and strong silhouettes. The final image should resemble a vintage anime frame from Astro Boy, with an optimistic, futuristic feel.
```

---

## new anime style

![new anime style](https://opennana.com/awesome-prompt-gallery/images/160.png)

- **Model:** None
- **Source:** [@Artedeingenio](https://x.com/Artedeingenio/status/1937069198921924968)
- **Tags:** illustration

**Prompt:**

```
Transform this image into an over-the-top anime illustration in the style of Trigger / Gainax. Use exaggerated expressions, wild motion lines, and hyperdynamic poses. The anatomy should be fluid and distorted for emphasis — limbs stretching or snapping into action. Add speed lines, explosive backgrounds, and dramatic lighting effects. Integrate onomatopoeia or stylized text for extra chaos. Colors should be bold, saturated, and contrasting. The result should feel like a freeze frame from Kill la Kill or FLCL, mid-action, full of energy and visual impact.
```

---

## Geometry Zen

![Geometry Zen](https://opennana.com/awesome-prompt-gallery/images/166.png)

- **Model:** None
- **Source:** [@LudovicCreator](https://x.com/LudovicCreator/status/1938330188414132727)
- **Tags:** illustration

**Prompt:**

```
[SUBJECT] illustrated in a Geometric Zen Tranquility style, where simplicity and balance are key. Utilize clean lines, basic shapes, and a serene color palette of [COLOR1] and [COLOR2] to evoke a sense of peace and harmony.
```

---

## Retro style icon

![Retro style icon](https://opennana.com/awesome-prompt-gallery/images/173.jpeg)

- **Model:** None
- **Source:** [@gnrlyxyz](https://x.com/gnrlyxyz/status/1938613929413869705)
- **Tags:** cartoon, illustration, retro, vehicle

**Prompt:**

```
Create an illustration of a [OBJECT] in a retro cartoon style. Use only flat, solid colors with no gradients, smudging, airbrushing, or blur. All shading and highlights should be made from clean, separate color blocks. Outline all shapes with thick, bold black lines. Use a simplified color palette (such as teal, coral, mustard, and white) for a vintage feel. Add small sparkle accents or motion lines for charm, but keep the icon the clear focus. Set the illustration on a plain white background. The final result must be crisp, clean, and vector friendly with sharp edges and no texture or raster effects. Square aspect ratio.
```

---

## 3D geometric effect

![3D geometric effect](https://opennana.com/awesome-prompt-gallery/images/176.jpeg)

- **Model:** None
- **Source:** [@BeanieBlossom](https://x.com/BeanieBlossom/status/1938568084207665488)
- **Tags:** 3d, illustration, landscape

**Prompt:**

```
A bison in the center of an array of colorful geometric shapes, surrounded by symbols representing different aspects like family and home. The artwork features warm colors in an oil painting style, with an Art Nouveau illustration showcasing ornate details and colorful patterns. The scene also includes a night sky and desert landscapes. The artwork should have a rich texture and a three-dimensional effect with intricate detailing.
```

---

## 2D word poster design

![2D word poster design](https://opennana.com/awesome-prompt-gallery/images/177.jpeg)

- **Model:** None
- **Source:** [@aziz4ai](https://x.com/aziz4ai/status/1938818077451325444)
- **Tags:** illustration, minimalist, poster, typography

**Prompt:**

```
Create a surreal 2D poster design based on the word “[KEYWORD]” — the layout should be dominated by kinetic typography where the word is visually shaped or distorted to reflect its meaning — integrate a symbolic flat minimal illustration that reinforces the concept — the style must be inspired by risograph print: only 2 bold contrasting colors (no gradients) — include a poetic, short quote that resonates emotionally with the keyword — background must be clean and minimal — composition must be vertical, with strong visual impact and artistic balance — the overall tone should feel cinematic, surreal, and graphic — ultra-sharp, high-resolution, no clutter
```

---

## Create a variety of 3D style avatars

![Create a variety of 3D style avatars](https://opennana.com/awesome-prompt-gallery/images/179.png)

- **Model:** None
- **Source:** [@tranmautritam](https://x.com/tranmautritam/status/1938160355064353153)
- **Tags:** branding, cartoon, character, fashion, illustration, minimalist, nature, product, vehicle

**Prompt:**

```
Create a 3D-rendered digital illustration of a stylized cartoon boy character, standing in a neutral pose. The character should be rendered in a realistic-minimalist 3D style, with soft rounded proportions and plush matte textures — similar to high-end Cinema 4D + Redshift product renders.
```

---

## Comparison between real person and style

![Comparison between real person and style](https://opennana.com/awesome-prompt-gallery/images/200.jpeg)

- **Model:** None
- **Source:** [@ZHO_ZHO_ZHO](https://x.com/ZHO_ZHO_ZHO/status/1935620536090153216)
- **Tags:** branding, cartoon, character, fashion, illustration, minimalist, nature, photography, portrait, poster, product, vehicle

**Prompt:**

```
create image {
"title": "Live-action × animation comparison creative work",
"author": "ZH4O",
"description": "A creative work that uses vertical collage and white space to juxtapose photos and illustrations of the same person, highlighting the contrast in language, texture and emotion of the medium.",
"layout": {
"orientation": "vertical",
"photo": {
"position": "top-left",
"aspect_ratio": "3:4",
"style": "street photo",
"camera_angle": "eye-level, slightly tilted left",
"lens": "mild wide-angle",
"background_elements": ["road", "store signs", "urban perspective lines"]
},
"illustration": {
"position": "bottom-right",
"scale": "slightly larger",
"composition": "2/3 body, medium shot",
"pose": "similar to photo",
"motion_direction": "curve extending top-right",
"balance": "forms visual counterpoint to photo"
},
"background": {
"color": "pure white",
"purpose": "breathing space, minimalism, focus"
}
},
"color_and_lighting": {
"photo": {
"dominant_tones": "neutral warm gray",
"light_source": "natural light",
"highlight_effects": "soft overexposure, summer glare",
"key_elements": ["white dress with gauzy texture", "cement, scooter, wall as low-saturation backdrop"]
},
"illustration": {
"style": "cartoon, simplified color blocks",
"skin": "warm orange with soft pink blush",
"hair": "deep brown, almost flat color",
"dress": "white with minimal shading to indicate folds",
"contrast": "high, compressed tonal range",
"focus": "sharp character silhouette"
},
"background": {
"function": "isolates media contrast, emphasizes character and action"
}
},
"style_comparison_and_details": {
"photo": {
"gesture": "hand shading forehead",
"expression": "wide eyes, slightly pouting lips, playful with a hint of exasperation",
"context": "spontaneous, tight alley space, loose hair movement"
},
"illustration": {
"design_inspiration": "Disney/CalArts style",
"features": ["large eyes", "wide cheekbones", "pointy chin", "freckles", "blush"],
"motion_effects": "exaggerated hair and skirt movement",
"line_quality": "fluid and bouncy",
"reproduction": "pose, expression, dress bow, forehead hair accurately translated"
}
},
"visual_and_communication_value": {
"themes": ["reality to animation transformation", "character design", "personified self-portrait"],
"usability": ["IP development", "illustration demo", "fashion branding"],
"design_elements": ["space for text/logo", "poster/social media-ready"],
"narrative_strength": "uses white space as frame, pose as link, and medium contrast as core interest",
"tone": "light, stylish, socially shareable"
}
}
```

---

## Traveling through the maze of dreams

![Traveling through the maze of dreams](https://opennana.com/awesome-prompt-gallery/images/216.png)

- **Model:** None
- **Source:** [@B_4AI](https://x.com/B_4AI/status/1942850557548388499)
- **Tags:** character, fantasy, illustration

**Prompt:**

```
[Character] sprinting past dream elements, Storybook illustration, Maze of floating doors, clocks, and whispers, Lantern glow and ambient sparkle trails, [Color1] and [Color2], Whimsical and fast-paced, Follow-cam style with trailing POV
```

---

## Cartoon modern style illustration

![Cartoon modern style illustration](https://opennana.com/awesome-prompt-gallery/images/217.png)

- **Model:** None
- **Source:** [@Artedeingenio](https://x.com/Artedeingenio/status/1942867064378573293)
- **Tags:** cartoon, character, illustration, landscape, logo, minimalist, vehicle

**Prompt:**

```
Transform this image into a Cartoon Modern Style illustration, inspired by classic UPA animation like Mr. Magoo and The Jetsons.
Redesign the character using flat, geometric shapes: ovals, rectangles, simple curves and angles. Avoid realistic proportions — the design should be stylized and abstract.
Use a limited color palette, preferably soft pastels or bold contrasts (e.g. mint green, salmon, sky blue, mustard yellow), with flat tones and no gradients.
Simplify facial features and body structure to be iconic and minimalist — large heads, small limbs, expressive poses, but with minimal detail.
The background should be minimal or symbolic, using basic shapes or abstract scenery (floating stairs, blocky furniture, stylized trees or stars).
The final image should look like a frame from a 1950s or 1960s modernist cartoon — playful, graphic, and highly stylized.
```

---

## Japanese funny manga style illustration

![Japanese funny manga style illustration](https://opennana.com/awesome-prompt-gallery/images/228.jpeg)

- **Model:** None
- **Source:** [@fy360593](https://x.com/fy360593/status/1944708178266259689)
- **Tags:** cartoon, character, illustration, retro, vehicle

**Prompt:**

```
Transform this image into a Japanese gag manga style illustration. Use a high-contrast black-and-white color palette with bold linework and screentone (halftone) shading. Characters should have exaggerated facial expressions, cartoonish proportions (big head, small body), and comedic intensity. Include dynamic action lines or radiating background effects. The overall aesthetic should mimic retro manga from the 80s and 90s with humorous and intense emotion.
```

---

## 90s American cartoon stop motion animation style illustration

![90s American cartoon stop motion animation style illustration](https://opennana.com/awesome-prompt-gallery/images/247.jpeg)

- **Model:** None
- **Source:** [@cuchocapilla](https://x.com/cuchocapilla/status/1934280060292284492)
- **Tags:** cartoon, character, illustration, minimalist, vehicle

**Prompt:**

```
Transform this image into a 90s American cartoon cel-style illustration. Use thick black outlines, flat bold colors, and sharp cel shading with hard shadows. Emphasize exaggerated facial expressions and stylized, geometric character shapes. The background should be flat or minimal to keep the focus on the character. The whole image should feel like a frame from a Saturday morning cartoon.
```

---

## Weird and dreamy surreal illustrations

![Weird and dreamy surreal illustrations](https://opennana.com/awesome-prompt-gallery/images/252.png)

- **Model:** None
- **Source:** [@fy360593](https://x.com/fy360593/status/1955265393188286632)
- **Tags:** cartoon, character, fantasy, illustration, landscape, vehicle

**Prompt:**

```
Transform the uploaded image into a surreal illustration with a whimsical, dream‑like vibe.
• Color palette: muted tones (soft greens, browns, greys) with occasional gentle pops of green.
• Lighting: soft, diffused, almost ethereal light that blends gradients and subtle highlights.
• Texture & medium feel: oil‑painting‑like brushstrokes, faint watercolor washes, or loose hand‑drawn linework, with a slight grainy texture.
• Mood & composition: exaggerated, expressive features (e.g., elongated faces or emotive eyes) characteristic of cartoonish or Muppet‑style illustrations, but applied in a surreal, slightly fantastical context.
• Overall aesthetic: blend realistic attention to detail with a touch of surreal whimsy—think serene, slightly uncanny atmosphere.
```

---

## Fairy tale illustrations in the style of Arthur Rackham from the 1920s

![Fairy tale illustrations in the style of Arthur Rackham from the 1920s](https://opennana.com/awesome-prompt-gallery/images/260.png)

- **Model:** None
- **Source:** [@vkuoo](https://x.com/vkuoo/status/1929708611208728874)
- **Tags:** animal, fantasy, illustration, landscape

**Prompt:**

```
Transform this image into a 1920s fairy tale illustration in the style of Arthur Rackham. Use muted watercolor tones and intricate ink linework. Fill the scene with whimsical forest creatures, twisted tree branches, and hidden magical objects. The overall tone should be mysterious, enchanting, and slightly eerie. Add handwritten calligraphy-style captions and riddles.
```

---

## Gorillaz style illustration

![Gorillaz style illustration](https://opennana.com/awesome-prompt-gallery/images/262.png)

- **Model:** None
- **Source:** [@azed_ai](https://x.com/azed_ai/status/1942586412920103180)
- **Tags:** illustration

**Prompt:**

```
Restyle this image into a gritty Gorillaz-style illustration, bold thick black outlines, sharp angular edges, flat expressive lighting, stylized high-contrast shadows, dirty distressed surface textures, muted color palette: washed-out teals, olive greens, rusty reds, mustard yellows, dusty browns, raw grungy urban atmosphere, comic book flatness mixed with painterly grit, hand-drawn finish with faded gradients, graphic novel aesthetic
with a rebellious, animated tone, dark stylish tone, full of attitude.
```

---

## A vintage tea bag

![A vintage tea bag](https://opennana.com/awesome-prompt-gallery/images/267.png)

- **Model:** None
- **Source:** [@TheRelianceAI](https://x.com/TheRelianceAI/status/1955240654440894730)
- **Tags:** illustration, paper-craft, retro

**Prompt:**

```
A single vintage tea bag lying on a clean white background, hand-painted with an intricate illustration resembling a book cover. The tea bag has delicate aged paper texture, soft warm lighting, and realistic details. On the painted design, leave a clear blank space labeled [BOOK] for the book title. Cinematic, high-resolution, vertical format 9:16.
```

---

## Childlike illustrations

![Childlike illustrations](https://opennana.com/awesome-prompt-gallery/images/268.jpeg)

- **Model:** None
- **Source:** [@gnrlyxyz](https://x.com/gnrlyxyz/status/1953477354161848322)
- **Tags:** cartoon, character, fashion, illustration, vehicle

**Prompt:**

```
Create a full body, flat vector illustration of [CHARACTER] in a whimsical, wavy cartoon style. Use thin black outlines and smooth, rounded shapes. The character should have a tiny white-colored head with tiny dot eyes and a simple nose and mouth. The body should have exaggerated, playful proportions. Use bold, flat colors for the clothing. No gradients. No shading. No smudging. Place the character on a solid blue background. Vector friendly. Square aspect ratio.
```

---

## Digital illustration in surreal geometric art style

![Digital illustration in surreal geometric art style](https://opennana.com/awesome-prompt-gallery/images/271.png)

- **Model:** None
- **Source:** [@fy360593](https://x.com/fy360593/status/1945042543609008235)
- **Tags:** futuristic, illustration, landscape, photography, retro

**Prompt:**

```
Transform this image into a digital illustration with a surreal, geometric art style. Apply glitch textures, abstract shapes, and cinematic composition. Use the original photo’s lighting and color palette to guide the atmosphere, while reimagining the scene in a stylized, dreamy, retro-futuristic way.
```

---

## Create comic-style illustrations

![Create comic-style illustrations](https://opennana.com/awesome-prompt-gallery/images/274.png)

- **Model:** None
- **Source:** [@miilesus](https://x.com/miilesus/status/1921944436684038496)
- **Tags:** illustration, paper-craft

**Prompt:**

```
create comic style illustration:
{
"style": "comic book illustration",
"line_art": {
"type": "bold black outlines",
"thickness": "medium",
"detail": "emphasized contours and shading lines"
},
"coloring": {
"palette": "vibrant and saturated colors",
"shading": "halftone dots and cel shading",
"highlighting": "strong contrast with pop art effects"
},
"texture": {
"surface": "flat with visible ink strokes",
"effect": "printed comic paper texture"
},
"composition": {
"layout": "centered subject",
"background": "simple with radial burst or comic-style lines",
"framing": "comic panel border"
},
"lighting": {
"type": "dramatic",
"angle": "top-left with bold highlights and shadows"
},
"post_processing": {
"effect": ["halftone dots", "ink outline", "grain"],
"saturation": "high",
"contrast": "high"
},
"mood": "dynamic and action-oriented",
"format": "vertical or square depending on original image"
}
```

---

## minimalist style illustration

![minimalist style illustration](https://opennana.com/awesome-prompt-gallery/images/277.png)

- **Model:** None
- **Source:** [@miilesus](https://x.com/miilesus/status/1913139509740314972)
- **Tags:** illustration, landscape, minimalist, paper-craft

**Prompt:**

```
Create a minimalistic illustration of [object or scene] in a paper cut-out style. Use soft, pastel colors and simple shapes. Include layered paper textures and subtle shadows to create depth. Place the object on a plain background. Ensure a clean, modern, and aesthetically pleasing composition with a slightly isometric perspective.
```

---

## Cartoon illustration pill image

![Cartoon illustration pill image](https://opennana.com/awesome-prompt-gallery/images/285.jpeg)

- **Model:** None
- **Source:** [@gnrlyxyz](https://x.com/gnrlyxyz/status/1951976345514487951)
- **Tags:** cartoon, character, fashion, illustration, logo, minimalist, vehicle

**Prompt:**

```
Create a stylized cartoon illustration of [CHARACTER] with a smooth, vertical pill-shaped body (rounded on top and bottom, symmetrical left to right). The body should be a single, unified capsule shape with no limbs. Do not alter the character's core design or personality, but simplify them into this playful capsule form. Use bold black outlines, flat vector-style coloring, and simple geometric features. Give the character large, expressive eyes and a fun, exaggerated facial expression that reflects their original personality. If the character wears clothes, include a minimal, iconic version of their outfit. If they do not, keep the body clean and unclothed. Use a solid bright yellow background. Center the character in a square frame. Use only flat colors. No gradients. No shadows. No texture. No smudging. The final result should be clean, modern, vector-friendly, and clearly pill-shaped.
```

---

## Retro comic style cartoon illustration

![Retro comic style cartoon illustration](https://opennana.com/awesome-prompt-gallery/images/305.jpeg)

- **Model:** None
- **Source:** [@azed_ai](https://x.com/azed_ai/status/1967180553553330306)
- **Tags:** cartoon, illustration, landscape, retro, vehicle

**Prompt:**

```
2D cartoon illustration of a [subject] mid-motion in a [dynamic action pose], drawn in vintage comic book style with bold outlines and saturated primary colors. Featuring dramatic motion streaks, exaggerated perspective, punchy panel composition, and crisp halftone texture. Designed for high-energy visual storytelling with retro superhero flair.
```

---

## Layered paper cut illustration

![Layered paper cut illustration](https://opennana.com/awesome-prompt-gallery/images/306.jpeg)

- **Model:** None
- **Source:** [@azed_ai](https://x.com/azed_ai/status/1968631874663891175)
- **Tags:** illustration, paper-craft

**Prompt:**

```
Layered paper-cut illustration of [subject], built with overlapping shapes in soft [color1] and [color2], handcrafted textures, subtle shadows between layers, clean vector edges, centered on a matte cream background, whimsical and modern visual storytelling.
```

---

## brand font

![brand font](https://opennana.com/awesome-prompt-gallery/images/316.jpeg)

- **Model:** None
- **Source:** [@aziz4ai](https://x.com/aziz4ai/status/1940348752969322544)
- **Tags:** branding, illustration, poster, typography

**Prompt:**

```
Create a typographic illustration shaped like a {OBJECT}, where the text itself forms the shape — bold and playful lettering style that fills the entire silhouette — letters adapt fluidly to the curves and contours of the object — vibrant and contrasting color palette that fits the theme — background is solid and enhances the focus on the main shape — vector-style, clean, high resolution, poster format, 1:1 aspect ratio.
```

---

## Objects turn into bold cartoon drippings

![Objects turn into bold cartoon drippings](https://opennana.com/awesome-prompt-gallery/images/320.jpeg)

- **Model:** None
- **Source:** [@Arminn_Ai](https://x.com/Arminn_Ai/status/1969324325162324163)
- **Tags:** cartoon, illustration, landscape, nature, photography, vehicle

**Prompt:**

```
Transform the [OBJECT] from the uploaded photo into a bold, colorful cartoon illustration style, while keeping the rest of the photo realistic and unchanged. 

Cartoon style details: thick black outlines, vibrant flat colors (such as bright cyan, magenta, yellow, pink), dripping paint and splash effects, playful comic-book energy.  most drips flow downwards
The cartoon object should look like it is melting or bursting with colors, blending naturally into the real photo. 

Keep all other elements (background, other objects, environment) photorealistic with no alterations. 
High resolution, pop-art aesthetic, surreal contrast between realism and cartoon.
```

---

## beauty fashion photography

![beauty fashion photography](https://opennana.com/awesome-prompt-gallery/images/325.jpeg)

- **Model:** None
- **Source:** [@Prashant_1722](https://x.com/Prashant_1722/status/1977458454483874088)
- **Tags:** architecture, cartoon, fashion, illustration, landscape, nature, photography, vehicle

**Prompt:**

```
{
  "prompt_title": "Effortless Chic Pose",
  "concept": "A hyperrealistic fashion photograph replicating a specific street style moment: a woman in a black knit set posing elegantly against a lamppost in a European city.",
  "scene_composition": {
    "shot_type": "Medium full-body shot",
    "camera_lens": "85mm f/1.4 lens",
    "perspective": "Eye-level, capturing the subject from the side.",
    "aspect_ratio": "2:3",
    "focus": "Sharp focus on the woman and her outfit. The background is beautifully blurred with creamy bokeh to isolate the subject."
  },
  "environment": {
    "setting": "A European city square or wide pedestrian street during the day.",
    "background_details": "The background is softly blurred but shows classical architecture with light-colored stone buildings. A few indistinct figures are walking in the distance.",
    "ground": "Light-colored stone pavers or cobblestones.",
    "atmosphere": "Chic, relaxed, and sophisticated."
  },
  "subject": {
    "primary": "A stylish young woman with long, wavy dark hair.",
    "appearance": "Her hair falls naturally over her shoulder. She has a gentle, soft expression and is looking slightly away from the camera.",
    "pose": "She is leaning with her back against a dark, ornate metal lamppost on the left side of the frame. Her right leg is bent and lifted behind her. "
  },
  "outfit_and_details": {
    "top": "A form-fitting, sleeveless black top made of a visible ribbed knit fabric.",
    "bottom": "A matching black mini skirt, also made of the same ribbed knit material.",
   "shoes": "black slingback high heel"
  },
  "style_and_aesthetics": {
    "realism": "Hyperrealistic, photorealistic, cinematic, 8K resolution, ultra-detailed.",
    "lighting": "Soft, diffused daylight, as if on an overcast day or in the shade, to prevent harsh shadows and create a flattering, even light on the subject.",
    "color_palette": "A monochrome and muted palette. Dominant blacks from the outfit and lamppost, contrasted with the light tones of the buildings and ground.",
    "details": "Emphasis on realistic material properties: the fine texture of the ribbed knit, the rough texture of the stone pavers, and the metallic finish of the lamppost."
  },
  "quality_boosters": [
    "masterpiece",
    "best quality",
    "insanely detailed",
    "sharp focus",
    "professional fashion photography",
    "street style",
    "editorial",
    "trending on Vogue"
  ],
  "negative_prompt": [
    "cartoon, anime, 3D render, illustration, painting",
    "blurry, out of focus, low quality, jpeg artifacts",
    "harsh sunlight, strong shadows",
    "crowded street, distracting background",
    "deformed anatomy, bad hands, extra limbs",
    "text, watermark, signature"
  ]
}
```

---

## Photorealistic indoor lying portraits

![Photorealistic indoor lying portraits](https://opennana.com/awesome-prompt-gallery/images/330.jpeg)

- **Model:** None
- **Source:** [@IamEmily2050](https://x.com/IamEmily2050/status/1976068430798389550)
- **Tags:** 3d, cartoon, illustration, interior, landscape, logo, minimalist, nature, photography, pixel, portrait, vehicle

**Prompt:**

```
{
"photorealistic_indoor_reclining_portrait",
  "style": "Natural editorial portrait; lifelike texture; minimal, tasteful retouching.",
  "output": { "aspect_ratio": "9:16", "resolution_px": [1440, 2560], "color_profile": "sRGB" },

  "subject": {
    "category": "human",
    "gender_presentation": "female",
    "ethnicity": "East Asian",
    "age_bracket": "young_adult",
    "body": {
      "build": "slim with realistic proportions",
      "bust": "fuller bust (natural C–D cup), proportional to frame; gentle natural slope, supportive shaping—no extreme push-up",
      "skin_tone": "light neutral with natural variation"
    },
    "pose": {
      "orientation": "reclining on back, relaxed",
      "right_arm": "raised above head, fingers lightly touching hairline",
      "left_arm": "bent across torso, hand resting on midriff",
      "head": "slightly tilted toward camera left"
    },
    "face": {
      "shape": "oval with mild asymmetry and natural cheek volume",
      "expression": "soft and open",
      "gaze": "direct to camera"
    },
    "eyes": {
      "description": "natural-size, lively but realistic",
      "color": "neutral gray-blue (low saturation)",
      "size_ratio": { "iris_fraction_of_visible_eye": 0.29, "pupil_fraction_of_iris": 0.27 },
      "details": {
        "limbal_ring_strength": 0.08,
        "sclera_brightness_Lstar": 78,
        "sclera_texture": "fine veins and faint tear meniscus on lower lid",
        "catchlights": "two soft rectangular window reflections about 10% of iris width",
        "specular_quality": "satin (no glassy glare)",
        "iris_texture": "visible stromal fibers and subtle color noise"
      }
    },
    "makeup": "sheer base preserving pores; soft peach blush; brown mascara/liner; taupe eyeshadow; hydrated nude lips",
    "hair": { "length": "long", "style": "half-up with bun, slight wave; a few flyaways visible", "color": "natural black" },
    "wardrobe": {
      "outfit": "blue top with Gucci shorts",
      "top": "powder-blue cropped bustier with sweetheart neckline and structured cups; off-shoulder or slim straps; tasteful cleavage; opaque lined fabric; subtle corset seams; cropped length reveals a sliver of midriff",
      "bottom": "Gucci blue GG-monogram denim shorts (small-scale jacquard, navy/indigo on blue; correct 'GG' orientation; no extra text)",
      "accessories": {
        "jewelry": "thin black velvet choker with tiny pendant, small stud earrings, simple rings",
        "wrists": "white fabric scrunchie on right; delicate bracelets on left"
      }
    }
  },
     "environment": {
    "location": "bedroom",
    "set": "plush bed with slightly wrinkled off-white linens and pillows",
    "background_props": "upper right: dark round tray with small white ceramic tea set on textured brown surface"
  },

  "lighting": {
    "scheme": "window key + sheet bounce",
    "source": "large window through sheer curtains (or 120 cm softbox with double diffusion)",
    "quality": "very soft with defined direction",
    "direction": "45° from camera right and slightly top; white bedding as fill about 1.5 stops under key",
    "temperature": "5200K",
    "effect": "gentle modeling with soft nose/lip shadow; crisp but soft eye catchlights; no bloom"
  },

  "camera": {
    "sensor": "full-frame",
    "lens": { "focal_length_mm": 85 },
    "distance_m": 1.8,
    "exposure": {
      "aperture_f": 3.2,
      "iso": 200,
      "shutter_s": 0.005,
      "metering": "spot on cheekbone; ETTR then -0.3 EV to protect highlights on fabric"
    },
    "focus": {
      "target": "near eye",
      "depth_of_field": "moderate (eyes and bust plane in focus; bedding softly blurred)"
    },
    "framing": {
      "orientation": "vertical",
      "angle": "overhead with slight tilt toward face; avoid wide-angle distortion",
      "composition": "9:16 crop framed head to upper hips so bustier and Gucci shorts are visible without foreshortening"
    }
  },

  "color_grade": {
    "look": "true-to-life neutrals with blue accent",
    "contrast": "medium-low",
    "palette": "powder/indigo blues, ivory, soft brown",
    "notes": "retain skin undertones; avoid cyan cast; ensure Gucci blue reads clean without oversaturation"
  },

  "postprocess": {
    "skin": "retain pores and micro-shine; remove only transient blemishes; keep faint under-eye texture",
    "eyes": "no iris enlargement; subtle iris clarity and micro-contrast; limbal ring kept weak",
    "sharpen": "moderate on eyes/brows/hair strands and denim weave/monogram",
    "grain": "fine film grain at 1.5–2%",
    "effects": "disable beauty filters, frequency-separation blur, glow/bloom; no HDR skin"
  },

  "realism_cues": [
    "flyaway hairs around hairline",
    "subtle nasolabial and philtrum depth",
    "natural knuckle/tendon texture on left hand",
    "visible denim weave and aligned monogram on shorts",
    "fabric creases and bedding wrinkles"
  ],

  "negative_prompt": [
    "doll, BJD, porcelain skin, neotenous proportions, plastic/waxy texture",
    "oversized/anime/doe eyes, iris enlargement, glassy eyes",
    "bright cyan/ice-blue contacts, heavy limbal ring, unnaturally white sclera",
    "poreless skin, beauty filter, airbrushed, skin smoothing",
    "bloom/Orton glow, excessive skin luster",
    "CGI, 3D render, illustration, toon shading, LoRA: doll/BJD",
    "wide-angle facial distortion, extreme symmetry filter",
    "random text overlays, misspelled logos, watermarks",
    "see-through fabrics, wardrobe malfunction, underboob/sideboob, explicit NSFW",
    "distorted anatomy, extra fingers"
  ],

}
```

---

## Girls mirror selfie

![Girls mirror selfie](https://opennana.com/awesome-prompt-gallery/images/332.jpeg)

- **Model:** None
- **Source:** [@dotey](https://x.com/dotey/status/1976485558319722711)
- **Tags:** branding, illustration, landscape, nature, paper-craft, portrait, poster, ui

**Prompt:**

```
### **Scene**
Mirror selfie, otaku computer corner, blue tones

---

### **Subject**
* **Gender Expression**: Female
* **Age**: Around 25 years old
* **Ethnicity**: East Asian
* **Shadow**: Slim, with a clear waistline; natural body proportions
* **Tone**: Light Neutral
* **Hairstyle**:
    * **Length**: Waist length hair
    * **Style**: Straight hair with slightly curled ends
    * **Color**: Medium Brown
* **Posture**:
    * **Standing**: Standing, slight contrapposto
    * **Right hand**: Holding mobile phone to cover face (identity is blocked)
    * **Left arm**: hangs naturally next to the torso
    * **Torso**: Body slightly tilted back; waist and abdomen exposed
* **Dress **:
    * **Top**: Light blue short knitted cardigan, button the first two buttons; blue French bra is faintly visible
    * **Bottoms**: Denim shorts with a blue ribbon bow on each hip
    * **Socks**: Blue and white horizontal striped over-the-knee socks
    * **Accessories**: Blue cute mascot phone case

---

### **Environment**
* **Description**: The computer corner in the bedroom as seen from the wall mirror
* **Furnishings**:
    * White desk
    * Single monitor showing soft blue wallpaper (no readable text)
    * Mechanical keyboard, white keycaps, placed on blue desk mat
    * Mouse, placed on small blue mouse pad
    * The PC host is on the right side with blue chassis lighting effect
    * There are three anime figures on or near the PC host
    * There is a pagoda poster on the wall
    *Cat-shaped table lamp with blue accents
    * A clear glass water cup
    * There is a tall green leafy plant by the window (left of the camera)
* **Color Replacement**: Replace all original pink elements (clothes and rooms) with blue (baby blue -> sky blue/periwinkle blue).

---

### **Lighting**
* **Light Source**: Daylight from the large window to the left of the shot, through the gauze curtains
* **Light texture**: soft diffused light
* **White Balance (K)**: 5200

---

### **Camera**
* **Mode**: Smartphone rear camera shot through mirror (no portrait/blur mode)
* **Equivalent focal length (mm)**: 26
* **Distance (meters)**:
    * Subject to mirror: 0.6
    * Camera to mirror: 0.5
* **Exposure**:
    * Aperture (f): 1.8
    * Sensitivity (ISO): 100
    * Shutter speed (seconds): 0.01
    * Exposure compensation (EV): -0.3
* **Focus**: Focus on the torso and shorts of the image in the mirror
* **Depth of field**: Natural smartphone depth of field (deep depth of field); the background is clearly discernible and no artificial blur
* **Composition**:
    * **Aspect Ratio**: 1:1
    * **Crop**: From top of head to mid-thigh; includes desk, monitor, PC and plant
    * **Angle**: Slight overhead shot from the perspective of a mirror
    * **Composition Notes**: Keep the subject in the center; to avoid stretching the wide-angle edges, you can stand farther away and then perform square cropping

---

### **Negative prompt words**
* Anywhere pink/magenta appears
* Beauty filters/dermabrasion; poreless look
* Exaggerated or distorted human structure
* NSFW, see-through fabric, exposure
* Logo, brand name, readable user interface text
* Fake portrait mode blur, CGI/illustration look
```

---

## Woman 3D digital illustration

![Woman 3D digital illustration](https://opennana.com/awesome-prompt-gallery/images/352.jpeg)

- **Model:** None
- **Source:** [@SimplyAnnisa](https://x.com/SimplyAnnisa/status/1980553716131414281)
- **Tags:** illustration, nature

**Prompt:**

```
A hyper-realistic 3D digital illustration of a woman with her natural facial features, hairstyle, and skin tone unchanged, styled in a Pixar-inspired cinematic look. She is smiling warmly while leaning through a glowing orange rectangular frame, both hands gently holding the edge of the frame. She wears a denim jacket layered over a black top, subtle jewelry, and a smartwatch on her wrist. The lighting is soft yet vibrant, highlighting facial depth, realistic fabric texture, and warm glow reflections on her face and hands. The background is softly blurred, creating a cinematic atmosphere with a perfect blend of realism, warmth, and Pixar-style charm.
```

---

## Surreal gothic rabbit studio portrait

![Surreal gothic rabbit studio portrait](https://opennana.com/awesome-prompt-gallery/images/370.jpeg)

- **Model:** None
- **Source:** [@IqraSaifiii](https://x.com/IqraSaifiii/status/1982469385156489563)
- **Tags:** cartoon, fashion, illustration, interior, landscape, nature, photography, portrait, product, vehicle

**Prompt:**

```
{
"prompt_title": "Hyperrealistic Gothic Bunny Studio Portrait",
"image_description": "An ultra-photorealistic, high-resolution studio portrait of a female subject in a gothic-inspired bunny costume, featuring intricate lace ears, a structured corset, and delicate hosiery. The subject is posed on the floor, exuding an alluring and sophisticated aura under precise studio lighting.",
"subject": {
"gender": "female",
"appearance": "Young adult with a flawless, luminous complexion. **Extreme micro-detail rendering on skin, showing subtle pores, fine vellus hairs, accurate light interaction (sub-surface scattering), and realistic skin texture.**",
"facial_features": "Smooth, clear skin. Her eyes are large, dark, and captivating, looking directly into the camera with a **confident and slightly seductive expression**. Lips are full, with a matte red or deep berry lipstick that shows micro-creases. Defined eyebrows and subtle contouring.",
"hair_style": "Long, flowing, wavy black hair, cascading over her shoulders and back. **Hair must show individual strands, realistic volume, high-gloss reflections, and subtle flyaways.**",
"makeup": "Dramatic and precise. Sharp, winged black eyeliner, full, dark eyelashes (possibly individual lash extensions), subtle glitter or shimmer on eyelids. Contoured cheeks. Flawless foundation and blush.",
"attire": {
"headwear": "Intricate **black lace bunny ears headband**. The lace should have visible patterns, delicate wire structure, and possibly small faux floral or ribbon accents. Realistic light interaction with the lace.",
"neck_accessories": "A simple, fitted black velvet or leather choker necklace.",
"main_outfit": "A highly detailed **black strapless corset dress or top and skirt ensemble**. The corset should be structured, showing **visible boning and lacing details** (possibly satin or leather laces). Fabric should be a mix of matte black leather/faux leather and textured, ruffled black tulle or chiffon for the skirt. **Emphasis on realistic fabric folds, textures, and subtle sheen.**",
"hosiery": "Sheer black thigh-high stockings with a delicate lace top band, clearly visible on her upper thigh. **Stockings must show realistic transparency and fabric stretch over skin.**",
"footwear": "Black pointed-toe high heels with ankle straps. The material should be a realistic matte or patent leather, showing accurate reflections and shoe construction."
}
},
"pose": {
"description": "The subject is kneeling on a flat, light-colored studio floor, leaning slightly forward. Her left hand is placed on the floor beside her left knee, fingers slightly spread. Her right arm is gently resting on her right thigh. Her body is slightly twisted, creating an alluring silhouette. **Exact replication of the confident and poised pose.**",
"camera_angle": "Medium shot, eye-level angle, slightly looking down at the subject. The camera is positioned to capture her full body from the mid-thigh up, with enough space around her to establish the studio environment.",
"composition": "Centered composition, vertical orientation. The subject fills approximately 70-80% of the frame, with subtle negative space around her. **Sharp focus on the subject, with a very shallow depth of field creating a soft bokeh in the background.**"
},
"setting": {
"location": "Professional indoor photo studio.",
"background_elements": "Seamless, plain light gray or off-white backdrop, extending from the floor to the wall, creating a clean, infinite background. **Subtle, soft gradient in the background due to lighting falloff.**"
},
"lighting_and_atmosphere": {
"key_light_source": "Softbox or parabolic diffuser from the front-left, creating soft, even illumination with subtle directional shadows to define contours.",
"fill_light": "Subtle fill light from the front-right to reduce harsh shadows on the right side of her face and body.",
"back_light": "A subtle hair light or rim light from the rear-right to create separation from the background and add definition to her hair and shoulders.",
"highlights_shadows": "Soft, creamy highlights on skin, hair, and corset material. Deep but soft shadows defining facial structure and body contours. **Accurate light falloff and realistic specular reflections on materials.**",
"photographic_realism": "Extreme micro-detail, sub-surface scattering on skin, realistic fabric textures (lace, leather, tulle), **cinematic studio lighting**, crisp focus on eyes, perfect white balance, neutral color grading, **ultra-realistic material rendering (PBR - Physically Based Rendering).**"
},
"style_and_camera": {
"photographic_style": "High-fashion portraiture, hyperrealistic studio photography, fine art glamour.",
"camera_type": "High-end full-frame mirrorless camera (e.g., Sony A1, Canon R5) with a fast prime lens (e.g., 50mm f/1.2 or 85mm f/1.4).",
"camera_values": "ISO 100, f/1.8, 1/160 sec. **These values contribute to shallow depth of field, sharp detail, and clean image quality.**",
"resolution_quality": "8K resolution, ultra-photorealistic, extreme detail on all elements. **Masterpiece quality render, production quality image.**"
},
"negative_prompt_suggestions": [
"blurry", "low resolution", "deformed", "harsh lighting", "flat background", "bad anatomy",
"cartoon", "illustration", "painting", "text", "watermark", "oversaturated", "poor composition",
"unrealistic skin", "plastic texture", "missing details"
]
}
```

---

## cartoon illustration

![cartoon illustration](https://opennana.com/awesome-prompt-gallery/images/380.jpeg)

- **Model:** None
- **Source:** [@Arminn_Ai](https://x.com/Arminn_Ai/status/1978164256240501226)
- **Tags:** 3d, cartoon, character, illustration, minimalist, photography, portrait, product, vehicle

**Prompt:**

```
A cartoon illustration of [OBJECT],
photographed in a clean minimal studio setup. All objects remain realistic and three-dimensional, but have been transformed into expressive cartoon characters:
• [DESCRIPTION & EMOTION]  
  (describe facial features, expressions, and emotional tone for each object)
• [ACTION]  
• doodle lines are black, slightly uneven, and hand-drawn —  like quick expressive sketchbook strokes drawn directly on the objects.
Style: hybrid mix of real product photography and cartoon doodle overlay.  
Background: solid pastel [COLOR], clean and minimal.
Lighting: soft, even, studio-style — subtle highlights and gentle shadows; no harsh light.
Mood: [MOOD / THEME — e.g. playful, melancholic, poetic, humorous].  
Keywords: hybrid photo-doodle, product cartoon, expressive characters, minimal pastel background. Aspect ratio: 1:1
```

---

## 3D chibi style vinyl collectibles

![3D chibi style vinyl collectibles](https://opennana.com/awesome-prompt-gallery/images/382.jpeg)

- **Model:** None
- **Source:** [@Arminn_Ai](https://x.com/Arminn_Ai/status/1982860799879114903)
- **Tags:** cartoon, character, fashion, illustration, logo, minimalist, nature, photography, portrait, product, toy, typography, vehicle

**Prompt:**

```
A 3D chibi-style vinyl collectible figure of [CHARACTER NAME] Big head, small body, cartoon proportion, Standing inside a Youtooz-style
packaging box with: Transparent front window
"YOUTOOZ COLLECTIBLES" logo on the top
Number label ([#XXX]) on the top-left
Bottom front text: “[CHARACTER NAME]” and lower with smaller font “VINYL FIGURE”
Cartoon 2D illustration of [CHARACTER NAME] on the side of the box ([ILLUSTRATION DESCRIPTION])

Background/theme:
[BOX COLORS + TEXTURES + ICONIC MOTIFS RELATED TO CHARACTER] 
[Figure POSE OR GESTURE] 
[Outfit DESCRIPTION + SIGNATURE ITEMS]

Face details: The facial features (mouth/eyes/details) must be fully 3D sculpted, not flat or printed.
Lighting: clean product photography look, minimal soft shadows
Style: vinyl-toy aesthetic with a mix of matte + glossy accents depending on costume, Composition: 3/4 product shot view, full box visible. The entire packaging box must be fully visible inside the frame with a clean margin around all edges.
```

---

## Sleepy girl on white pillow

![Sleepy girl on white pillow](https://opennana.com/awesome-prompt-gallery/images/388.jpeg)

- **Model:** None
- **Source:** [@songguoxiansen](https://x.com/songguoxiansen/status/1981178369262964886)
- **Tags:** 3d, illustration, interior, landscape, nature, photography

**Prompt:**

```
{
  "scene": {
    "location": "Bedroom, in bed",
    "background": "White pillows and soft, rumpled bedsheets, soft morning light"
  },
  "subject": {
    "age": "adult",
    "description": "East Asian woman, beautiful 'just woke up' messy hair, sleepy eyes",
    "wardrobe": "Simple, thin-strap camisole (e.g., silk or cotton), strap slightly falling off one shoulder",
    "accessories": "None",
    "pose": "Lying on her stomach in bed, propped up on her elbows, looking at the camera",
    "expression": "Soft, sleepy smile, intimate, 'good morning' look",
    "gaze": "Direct to camera, soft and alluring",
    "body_notes": "Photorealistic, realistic adult proportions; natural skin texture, visible collarbones, 'sleepy' flush"
  },
  "camera": {
    "sensor": "full_frame",
    "focal_length_mm": 50,
    "aperture_f": 1.8,
    "shutter_s": 0.01,
    "iso": 400,
    "white_balance_k": 5500,
    "distance_m": 1.5,
    "camera_height_m": 0.8,
    "framing": "Close-up (chest-up), at eye level with her",
    "focus": "eye_detect_AF on nearest eye"
  },
  "lighting": {
    "key": "Large, diffused window light from the side, creating very soft shadows",
    "fill": "Bounced light from the white sheets",
    "hair": "Soft halo from the window",
    "catchlights": "Large, soft window catchlights",
    "notes": "Very soft, high-key, intimate"
  },
  "color_grade": {
    "style": "Intimate, soft, 'morning' aesthetic",
    "palette": "Whites, skin tones, pastels; soft, luminous skin",
    "contrast": "Very low, dreamy",
    "saturation": "Moderate, soft"
  },
  "makeup": {
    "eyes": "None, 'bare face' look",
    "cheeks": "Natural, sleepy flush",
    "lips": "Natural, hydrated"
  },
  "postprocess": {
    "retouch": "Professional retouching, maintain "real skin" look",
    "clarity": "Selective clarity on eyes and lashes",
    "dodge_burn": "Subtle dodge on eyes and collarbone",
    "vignette": "Subtle, bright vignette"
  },
  "art_direction": {
    "mood": "Flirty, intimate, ambiguous, soft, sleepy, alluring",
    "keywords": ["photorealistic", "flirty", "morning", "in bed", "ambiguous", "natural beauty", "sleepy"]
  },
  "negative_prompts": [
    "nsfw",
    "underage look",
    "text or logos",
    "plastic doll skin",
    "cg",
    "3d render",
    "anime",
    "heavy makeup",
    "warped hands"
  ]
}
```

---

## Young East Asian Female K-Pop Idol Style

![Young East Asian Female K-Pop Idol Style](https://opennana.com/awesome-prompt-gallery/images/399.jpeg)

- **Model:** None
- **Source:** [@IamEmily2050](https://x.com/IamEmily2050/status/1985682978182480251)
- **Tags:** illustration, interior, landscape, photography, portrait, retro

**Prompt:**

```
{
    "style_mode": "raw_photoreal_high_fidelity",
    "look": "K-Pop idol aesthetic, flawless complexion, high-resolution digital photography, trendy",
    "camera": {
      "vantage": "slightly high angle (selfie perspective), direct address",
      "framing": "extreme close-up (ECU), tight framing on the face and shoulders",
      "lens_behavior": "portrait lens (e.g., 85mm prime), extremely shallow depth of field (DoF), sharp focus on the eyes",
      "sensor_quality": "high fidelity, no digital noise"
    }
  },
  "scene": {
    "environment": {
      "setting": "indoor studio or simple interior",
      "lighting": "soft, even beauty lighting (e.g., large softbox or beauty dish), minimizing shadows, creating clear catchlights in the eyes, emphasizing glossy highlights"
    },
    "subject": {
      "description": "young East Asian female, K-Pop idol styling",
      "hair": "long, dark brown, wavy, glossy finish",
      "expression": {
        "mood": "playful, confident, slightly sultry",
        "action": "looking directly into the lens, mouth slightly open, tongue slightly sticking out over the lower lip"
      },
      "makeup": {
        "style": "contemporary K-beauty trends",
        "complexion": "flawless, 'glass skin' effect, dewy/glossy finish, realistic micro-texture",
        "cheeks": "rosy blush, high application",
        "lips": "glossy, pink tint"
      },
      "attire": {
        "top": "grey pinstriped halter top, structured design",
        "details": "white contrasting collar lapel with silver snap buttons and circular metal hardware"
      },
      "accessories": {
        "hair_clip": "decorative silver/rhinestone clip on her left side",
        "earrings": "dangling silver earrings (heart motif)"
      }
    },
    "background": {
      "description": "plain, neutral grey or white wall, blurred (bokeh)"
    }
  },
  "aesthetic_controls": {
    "render_intent": "high-quality digital photograph suitable for promotional material or social media",
    "material_fidelity": [
      "realistic skin micro-texture (pores, gloss, makeup interaction)",
      "individual hair strand detail",
      "fabric texture of the pinstripe material",
      "metallic shine of accessories"
    ],
    "color_grade": {
      "overall": "neutral, slightly warm, vibrant skin tones, high clarity",
      "contrast": "balanced"
    }
  },
  "negative_prompt": {
    "forbidden_elements": ["skin imperfections", "blemishes", "wrinkles", "harsh shadows", "textured/matte skin", "dry lips", "outdoor setting", "distorted features", "motion blur", "digital artifacts"],
    "forbidden_style": ["anime", "painting", "illustration", "CGI render", "low resolution", "gritty realism", "vintage photography", "uncanny valley", "overly airbrushed/plastic skin"]
  }
}
```

---

## Digital comics of a middle-aged man

![Digital comics of a middle-aged man](https://opennana.com/awesome-prompt-gallery/images/402.jpeg)

- **Model:** None
- **Source:** [@ShreyaYadav___](https://x.com/ShreyaYadav___/status/1985908915427758305)
- **Tags:** 3d, character, fashion, illustration, nature, photography, portrait, vehicle

**Prompt:**

```
Create a realistic digital caricature painting of a middle-aged man (attached photo) with a slightly oversized head, exuding charm and quiet confidence. He is dressed in a modern, stylish bomber jacket made of dark olive nylon with subtle reflective highlights that give it a sleek and fashionable look. Underneath, he wears a warm-toned flannel shirt slightly visible at the collar and cuffs, paired with khaki cargo pants and black sneakersthat ground the outfit with a casual yet confident energy. Completing his look, he wears a brown flat cap tilted slightly forward — a small detail that adds personality and flair.

The man is portrayed in a mid-shot, adjusting his glasses with one hand while gazing directly at the viewer with a self-assured and composed expression. His head is slightly larger than normal, emphasizing his thoughtful character and giving the image a light caricature charm without losing realism.The facial expression radiates intelligence, humor, and approachability.

The lighting is warm and soft, like that of a late afternoon sun filtering through a studio setup. Smooth gradual shadows enhance the contours of his face, while subtle highlights accentuate the texture of his bomber jacket and the reflection in his glasses. His skin tones glow naturally under the warm light, creating a pleasant sense of depth and realism.The background is a gradient of warm brown and beige hues, blending smoothly from light to dark. This background is simple yet elegant, allowing the subject to stand out while maintaining a professional, editorial quality.

The art style should combine semi-realistic digital painting with the texture of oil brushstrokes, delivering a balanced fusion of realism and stylized charm.Clean outlines, smooth blending, and controlled highlights give the impression of a modern portrait illustration—detailed, expressive, and visually captivating.
```

---

## Incorporate comic characters into your real-life photos

![Incorporate comic characters into your real-life photos](https://opennana.com/awesome-prompt-gallery/images/445.jpeg)

- **Model:** Nano banana pro
- **Source:** [@azed_ai](https://x.com/azed_ai/status/1992263611428082031)
- **Tags:** 3d, character, illustration, photography, portrait, vehicle

**Prompt:**

```
A photograph of a crowded subway train in Tokyo, hyper-realistic style. Sitting on one of the seats is a 2D black-and-white manga illustration of a tired samurai. The character is drawn with clean ink lines and cross-hatching shading. The lighting from the subway car hits the 2D drawing correctly, creating realistic highlights on the ink. The character holds a real photographic soda can, blending the 2D and 3D worlds. 4k, cinematic composition.
```

---

## Add sketched people to your real photos

![Add sketched people to your real photos](https://opennana.com/awesome-prompt-gallery/images/448.jpeg)

- **Model:** Nano banana pro
- **Source:** [@egeberkina](https://x.com/egeberkina/status/1992151432422986028)
- **Tags:** fantasy, illustration, landscape, minimalist, nature, photography, portrait

**Prompt:**

```
Add clean, minimal white line-drawing illustrations of people into this photo. Match the perspective, lighting, and scale of the scene. The illustrated figures should interact naturally and meaningfully with the environment, reflecting the mood, purpose, and activity of the space. Keep the drawings simple, fluid, and expressive, with no facial details. Maintain a modern, warm, and slightly whimsical tone that complements the overall aesthetic. Do not obscure any original elements. The illustrated figures should feel like friendly, imaginative additions that blend seamlessly with the context of the scene.
```

---

## Recipe - Tomato Scrambled Eggs

![Recipe - Tomato Scrambled Eggs](https://opennana.com/awesome-prompt-gallery/images/476.jpeg)

- **Model:** Nano banana pro
- **Source:** [@cnyzgkc](https://x.com/cnyzgkc/status/1992570337977082030?s=46)
- **Tags:** food, illustration, infographic, landscape, paper-craft, typography

**Prompt:**

```
Create a 9:16 vertical version of the "Tomato Scrambled Eggs" hand-drawn style teaching recipe infographic.

Overall style requirements:
	• Instructional recipes written by professional chefs for ordinary people
	• Use Z-shaped dynamic line layout (upper left → upper right → lower left) for smooth reading
	• Colorful watercolor pen sketch style with delicate ink outlines
	• Adopt 2025 mainstream illustration colors and brushstrokes
	• Beige paper texture background, warm, rustic and friendly
	• Illustrations must make people “want to see them”

⸻

Content structure (general)

1. Top title (eye-catching)

"{Dish name}"

⸻

2. Step block (Z moving line layout, steps 3–5)

Each step includes:
	• Hand-drawn step-by-step illustrations (color watercolor + ink line)
	• Short graphic description
	• Chef secrets
	• Tips or tips

⸻

Step template (general, can be automatically filled in by the model)

Step 1: Prepare ingredients
(Automatically generate related ingredients based on the dish name)
Illustration: Neatly arranged main ingredients and seasonings.
Directions: List and process the basic ingredients for this dish.
Tips: Tell users how to improve flavor or mouthfeel.
Experience: Provide simple experience or reminder.

⸻

Step 2: Seasoning/marinization/pre-processing
Illustrations: Small bowls or chopping boards for preparing sauces, marinating meats, and preparing main ingredients.
Description: Shows key foundational steps.
Secrets: Proportions, Tips, Key Points to Avoid Failure.
Thoughts: Tips for effortless style.

⸻

Step 3: Crucial Stir-frying/Cooking Steps
Illustration: Cooking scene of ingredients in a pot with soft watercolor smoke.
Description: big fire, small fire, sequence, important actions.
Secret technique: ways to maintain the heat, control the time, and enhance the aroma.
Thoughts: Emphasize the soul of cooking.

⸻

Step 4: Combination of flavors/steps before serving
Illustration: Scenes of adding sauce, seasoning, and mixing ingredients.
Instructions: The whole sauce is collected and the seasoning is in place.
Secrets: Tips for brightening oils and maintaining texture or fragrance.
Thoughts: This step determines success or failure.

⸻

Step 5: Embellishment/Finishing Steps
Illustrations: Spreading spices, adding nuts, plating, etc.
Instructions: Make final adjustments to taste or presentation.
Secrets: Maintaining crispness and avoiding overcooking.
Thoughts: Flavor description of finished product.

⸻

Bottom finished illustration
	• An exquisite, delicious and delicious "{Dish Name}"
	• Watercolor texture is strong, shiny, fresh and attractive
	• Make readers want to do something after reading it

⸻

Signed at bottom center

@ Trojan AI
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

## Illustrations of Chang'an in the Tang Dynasty

![Illustrations of Chang'an in the Tang Dynasty](https://opennana.com/awesome-prompt-gallery/images/501.jpeg)

- **Model:** Nano banana pro
- **Source:** [@imaxichuhai](https://x.com/imaxichuhai/status/1991684207513350329)
- **Tags:** cartoon, illustration, landscape, minimalist, portrait, typography

**Prompt:**

```
With a ratio of 16:9, this is a breathtaking masterpiece of illustrated cartography, depicting a map of Chang'an, the capital of the Tang Dynasty. The entire picture is presented in the exquisite style of paintings of ladies in the Tang Dynasty, which is reminiscent of the works of the master painting Zhou Fang. The medium is the use of meticulous brushwork and heavy colors on old, delicate silk.

**Composition and Perspective:**
The map is in the form of a long scroll with "scattered perspective". The city feels more like a living tapestry than a rigid blueprint. Zhuque Street serves as the central axis of the picture.

**Illustration and font details:**
- **Landmarks as miniature scenes:** Key locations are small, delicate narrative scenes:
- **Daming Palace:** Palace ladies playing musical instruments in the garden.
- **West Market:** Sogdian merchants traded silk with noble women.
- **Qujiang Pool:** The ladies are doing the "Qujiang Pool".
- **Elegant figures as map elements:** Elegant Tang Dynasty ladies are used as decorative elements, their postures and sleeves guiding the viewer's eye.

**One hundred and eight squares - advanced instructions:**
One hundred and eight squares are represented by elegant hand-drawn rectangular seals. The core goal is to populate these seals with plausible, historical text.
- **Instructions:** The AI ​​does not have to try to render all 108 unique names, but must learn from the provided "sample set" and fill each seal with similar, reasonable, and non-duplicate two-letter names.
- **Sample collection of famous shop names (for style reference):**
"Pingkangfang", "Chongrenfang", "Xingqingfang", "Daozhengfang", "Changxingfang", "Yongchongfang", "Qinrenfang", "Yongningfang", "Huaiyuanfang", "Yankangfang", "Jinchengfang", "Buzhengfang".
- **Style Mandatory Requirements:** All text in the seal must be in beautiful, slender and elegant "Xiaozhuan" font. The structure should be "[a][a]fang".

**Main title and tags:**
- **Main title:** "Datang Chang'an" is written vertically in the upper right corner in majestic official script.
- **Tag:** The names of the street ("Suzaku Street") and the river ("Weishui") are written directly on the silk background in graceful running script, flowing along the curve of the path.

**Aesthetics and Atmosphere:**
The color palette is rich and ornate (cinnabar, lime green, azurite, gold leaf). The lines are as thin and smooth as "gossamer drawing". The overall atmosphere is a prosperous, poetic and elegant feeling.

**Negative cue words:**
English, roman alphabet, 3D, modern map, grid layout, geometric shapes, computer font, western art style, cartoon, simple, minimalist, white space, watermark, bad calligraphy, gibberish.
```

---

## dragon ball cards

![dragon ball cards](https://opennana.com/awesome-prompt-gallery/images/520.jpeg)

- **Model:** Nano banana pro
- **Source:** [@servasyy](https://x.com/servasyy/status/1993337294477218061)
- **Tags:** futuristic, illustration, ui, vehicle

**Prompt:**

```
A 3x3 grid layout displaying 9 different premium Japanese TCG collectible card designs, each featuring Son Goku in Super Saiyan form with unique battle scenes.

Overall Composition: 9 vertical trading cards (9:16 ratio each) arranged in a perfect 3x3 grid with thin spacing between cards.

Each Card Contains:

Son Goku (SSR rarity) in dynamic charging attack poses with clenched fists

Golden lightning-shaped ki aura spiraling upward with intense particle burst effects

Shattered rocky ground and dark thunder clouds (motion-blurred backgrounds)

Radial golden speed lines in mid-ground

Flying debris rocks and energy sparks in foreground

Holographic foil texture with glow effects on energy areas

Top-left: "SSR" metallic badge with golden light rays

Border: Futuristic tech frame with lightning pattern decorations

Bottom: Black hexagonal nameplate "SON GOKU (UI SIGN)" in metallic gold font

9 Different Scenes (varied poses and angles):

Frontal charging punch

Side aerial kick with energy burst

Kamehameha charging stance

Spinning attack with motion trails

Upward rising power-up pose

Downward diving strike

Energy sphere preparation

Defensive counter stance

Final impact explosion moment

Consistent Color Palette Across All Cards:

Primary: Radiant gold (#FFD700) and electric blue (#00BFFF)

Contrast: Deep purple (#4B0082)

Highlights: Pure white (#FFFFFF) with bloom

Shadows: Deep blue-black (#001F3F)

Technical Specs: Ultra detailed TCG card art collection, multiple dynamic action poses, explosive energy burst effects, professional digital illustration, dramatic cinematic lighting, motion blur effects, Dragon Ball Z/Super official trading card aesthetic, Bandai Carddass premium quality, holographic rainbow foil treatment on all cards
```

---

## Wardrobe teardown and style analysis

![Wardrobe teardown and style analysis](https://opennana.com/awesome-prompt-gallery/images/522.jpeg)

- **Model:** Nano banana pro
- **Source:** [@IamEmily2050](https://x.com/IamEmily2050/status/1993194975169781882)
- **Tags:** character, fashion, illustration, landscape, minimalist, nature, photography, portrait, product, typography

**Prompt:**

```
**Task: Create a comprehensive "Wardrobe Deconstruction and Style Profile" collage based on an uploaded image.**

**Objective:**
Act as a professional fashion archivist and technical designer. Given an uploaded image of a person, generate a visually compelling, high-resolution "Style Profile" collage that meticulously deconstructs their entire ensemble, from the outermost layer to the foundational structure. The final output must be a single, cohesive, photorealistic image.

**Core Elements:**

1.  **Central Subject Image:**
    *   Place the subject from the uploaded image in a full-body pose as the central focus.
    *   Maintain the subject's likeness (face, hair, clothing) while enhancing the image to a professional, high-fashion photographic standard.

2.  **Complete Ensemble Deconstruction (Photorealistic Product Shots):**
    *   Generate a visual breakdown of the subject's attire, presenting each item as a separate, high-quality product photograph. This breakdown must include:
        *   **Outer and Mid-Layers:** All visible garments and accessories.
        *   **Foundational Elements:** A technical illustration of the essential structural garments that provide shape and support to the silhouette (e.g., a bra, slip, or specific underlayer). These elements must be rendered as **objective, flat-lay design schematics** with a focus on material and construction, not on the human form.
    *   Include detailed close-ups of key materials (e.g., fabric weave, leather texture, metal finish) to emphasize quality and design.

3.  **Lifestyle & Contextual Items:**
    *   Based on the subject's style, infer and generate a collection of 4-6 photorealistic items that suggest their likely environment, interests, or daily routine.

4.  **Expression & Detail Sheet:**
    *   Generate a series of 3-4 close-up portraits showing a range of natural, context-appropriate expressions.

**Aesthetic and Layout Guidelines:**

*   **Overall Style:** Strictly **Hyper-realistic, photographic style**. Absolutely no illustration, anime, or hand-drawn elements.
*   **Layout:** Arrange all elements in a **clean, balanced, and modular collage** on a neutral background (white or light gray). The layout must be visually logical and professional, resembling a high-end fashion technical document.
*   **Annotations:** Use a clean, minimalist font for all text.
    *   **Title:** Generate a professional, gender-neutral title (e.g., "Technical Deconstruction: The Urban Minimalist").
    *   **Labels:** Add brief, descriptive labels for all deconstructed items, including the "Foundational Elements," using technical terms (e.g., "Structural Support Garment," "Base Layer").

**Crucial Instruction:** The rendering of all "Foundational Elements" must be purely technical and objective, presented as a **design schematic or flat-lay product shot** to emphasize construction and material, completely detached from the central subject's body.
```

---

## Minecraft Mysterious Age Information Card

![Minecraft Mysterious Age Information Card](https://opennana.com/awesome-prompt-gallery/images/527.jpeg)

- **Model:** Nano banana pro
- **Source:** [@manateelazycat](https://x.com/manateelazycat/status/1993248526479114602)
- **Tags:** illustration, typography

**Prompt:**

```
Use Chinese to draw a complete information card output, and use PUNCH to display all content on one page as much as possible! This is a complete information card designed based on the article content you provided. It can include the image element display of banana. In order to achieve the "PUNCH" effect, I adopted a modular design, refined the core keywords, and combined it with visual symbols and compact layout to emphasize visual impact and information acquisition efficiency.

The content is the core gameplay of Minecraft Mysterious Age version 1.7.10

An illustration showing the core gameplay of Minecraft Mysterious Age 1.7.10,

Including magic nodes, research tables, magic wands, magic-infused altars, crucible alchemy, and puppet automation,

The picture is full of arcane runes, purple and blue magical energy, with a sense of mystery and classical magic technology style.

Featuring floating magic books, Vis flowing special effects, and details of the workings of magical devices.

High quality, fine texture, glowing effect, fantasy style.
```

---

## Literacy tabloid meta prompt words

![Literacy tabloid meta prompt words](https://opennana.com/awesome-prompt-gallery/images/529.jpeg)

- **Model:** Nano banana pro
- **Source:** [@lxfater](https://x.com/lxfater/status/1993238777033105634)
- **Tags:** cartoon, character, food, illustration, landscape, nature, paper-craft, portrait, toy, typography, vehicle

**Prompt:**

```
Please generate a children's literacy tabloid "Amusement Park", vertical format A4, learning tabloid format, suitable for children aged 5-9 years old to read words and recognize objects by looking at pictures. 1. Tabloid title area (top) Centered headline at the top: "Amusement Park Literacy Tabloid" Style: cross tabloid / children's learning report Text requirements: large characters, eye-catching, cartoon handwriting, colorful strokes Decoration: add sticker-style decorations related to amusement parks around, bright colors 2. Main body of the tabloid (middle main screen) The center of the screen is a cartoon illustration-style "amusement park" scene: Overall atmosphere: bright, warm, positive Composition: The boundaries of objects are clear, easy to correspond to text, and not too crowded. Scene partition and core content Core area A (main object): expresses the core activities of the amusement park (children playing on the rides). Core area B (supporting facilities): displays related tools or items (ticket sales, snacks, instruction facilities). Core area C (environmental background): reflects environmental features (entrance, street signs, colorful flags, green space, etc.). Theme characters: 1 cute cartoon character (identity: amusement park staff/tourists and children). Action: Natural interaction related to the scene (such as smiling and giving directions, waving to welcome, playing with children). 3. Required Drawing Objects and Literacy List (Generated Content) Please be sure to clearly draw the following objects in the picture and reserve space for labeling them: 1. Core roles and facilities: gōng zuò rén yuán staff shòu piào chù ticket office guò shān chē roller coaster mó tiān lún Ferris wheel xuán zhuǎn mǎ carousel 2. Common items/tools: piào ticket qì qiú balloon bīng jī líng ice cream bào mǐ huā popcorn táng hú lu candied haws miàn jù mask wán jù toy xiǎo qí zi small flag 3. Environment and decoration: rù kǒu entrance chū kǒu exit zhǐ shì pái signboard cǎi qí colorful flag guǎng chǎng square (Note: The number of objects in the picture is not limited to this, but the above list must be used as the key depiction object; a total of 18 typical nouns, suitable for children aged 5–9 to read.) 4. Literacy labeling rules Label the objects in the above list with Chinese literacy labels: Format: two-line system (the first line has pinyin with tones, the second line has simplified Chinese characters). Style: Colorful small sticker style, with black or dark text on a white background, clear and readable. Layout: The label is close to the corresponding object and does not block the main body. 5. Painting style parameters Style: children’s picture book style + literacy tabloid style Color: High Saturation, Warm Tone Quality: 8k resolution, high detail, vector illustration style, clean lines.
```

---

## Turn articles into blackboard newspapers

![Turn articles into blackboard newspapers](https://opennana.com/awesome-prompt-gallery/images/545.jpeg)

- **Model:** Nano banana pro
- **Source:** [@dotey](https://x.com/dotey/status/1993192263334183370)
- **Tags:** cartoon, illustration, infographic, minimalist, portrait, vehicle

**Prompt:**

```
Please create an infographic based on the input content, highlighting key themes and essential points:

- Simplify information, emphasizing keywords and core concepts, leaving ample whitespace for clarity.

- Include minimalistic cartoon elements, icons, or simple portraits of famous figures to enhance engagement and visual recall.

- All text and images should strictly use colored chalk style without realistic illustrations.

- Unless specifically requested, maintain the original language of the input content.

- Use a horizontal layout (16:9) with a black chalkboard background and colorful chalk drawing style.

Use "nano banana pro" for drawing based on the provided content.
```

---

## Turn articles into cartoon infographics

![Turn articles into cartoon infographics](https://opennana.com/awesome-prompt-gallery/images/546.jpeg)

- **Model:** Nano banana pro
- **Source:** [@dotey](https://x.com/dotey/status/1993567848564686926)
- **Tags:** cartoon, illustration, infographic, landscape, portrait, vehicle

**Prompt:**

```
Please create a cartoon-style infographic based on the provided content, following these guidelines:

- Hand-drawn illustration style, landscape orientation (16:9 aspect ratio).

- Include a small number of simple cartoon elements, icons, or famous personalities to enhance visual interest and memorability.

- If the content includes sensitive or copyrighted figures, replace them with visually similar alternatives; do not refuse to generate the illustration.

- All imagery and text must strictly adhere to a hand-drawn style; avoid realistic visual elements.

- Keep information concise, highlighting keywords and core concepts. Utilize ample whitespace to clearly emphasize key points.

- Unless otherwise specified, use the same language as the provided content.

Please use nano banana pro to create the illustration based on the input provided.
```

---

## Hand drawn calendar illustration

![Hand drawn calendar illustration](https://opennana.com/awesome-prompt-gallery/images/547.jpeg)

- **Model:** Nano banana pro
- **Source:** [@dotey](https://x.com/dotey/status/1993754650336428422)
- **Tags:** character, data-viz, fashion, illustration, logo, minimalist, portrait, typography, vehicle

**Prompt:**

```
Please create a cute, stylish calendar illustration in a vertical (9:16) layout featuring a fresh, bright, hand-drawn style:

Illustration Requirements:

- The main character is a young, fashionable female with a cute and lively watercolor or hand-drawn texture, vibrant yet soft colors.
- Character features include large eyes, rounded rosy cheeks, and bold, fashionable accessories (e.g., sunglasses, hoop earrings, headscarves, headbands, bows, knit hats, etc.). Clothing should be bright, with dynamic and playful poses. Proportions may be slightly exaggerated (e.g., larger head, slender waist).
- Outfit and accessories must reflect seasonal elements, holidays, recommended activities ("auspicious items"), or distinctive local characteristics based on the user's location and input. Outfit description: [{Character Outfit Description}]
- Character positioned centrally or slightly right-aligned to leave ample whitespace for textual content.
- Pure white, minimalist background without additional decorative elements, emphasizing the character and text.

Calendar Layout:

- Prominent position at the top center: Gregorian date number [{Gregorian Date Number}] (large and eye-catching).
- Below the date number, display the English month [{English Month}].
- Below the English month, display the year [{Year Number}].
- Symmetrical layout left and right of the date: weekday in both local language [{Weekday in Local Language}] and English [{Weekday in English}], along with the lunar date and local holiday [{Lunar or Local Calendar Date}] [{Local Holiday}], ensuring clear, elegant fonts.

"Recommended Activities" and Inspirational Quote:

- Vertically aligned on the left side in bold handwriting: [{Recommended Activities}], using brush calligraphy for Chinese users and complementary handwriting style for other languages, slightly larger and vertically arranged.
- To the right of "Recommended Activities," arrange vertically an inspirational and comforting quote [{Inspirational Quote}] in slightly smaller matching handwriting.

Localized Elements:

- Incorporate distinct local cultural elements or landmarks based on the user's current location or input into the character's outfit, accessories, or details (e.g., city landmarks, climate characteristics, local cultural motifs).

General Guidelines:

- All elements must be neatly arranged with balanced whitespace.
- Ensure text readability without overlapping or obscuring the illustration.
- Replace all placeholder content with information dynamically generated based on user input or system-provided user data.
```

---

## Fashion style concept exploded illustration in hand drawn style

![Fashion style concept exploded illustration in hand drawn style](https://opennana.com/awesome-prompt-gallery/images/550.jpeg)

- **Model:** Nano banana pro
- **Source:** [@cheerselflin](https://x.com/cheerselflin/status/1992877077570453712)
- **Tags:** character, fashion, illustration, nature, paper-craft

**Prompt:**

```
A fashion-style concept breakdown sheet in hand-drawn illustration style. 
Center: full-body view of a stylish, confident female character with a slightly sexy vibe (not explicit), in a dynamic yet natural pose. 
Surrounding: structured layout of her key components:
• Clothing layering – show outerwear, innerwear, tights (lace, sheer textures), shapewear with detailed pattern zoom-ins.  
• Expression sheet – 3-4 facial expressions (neutral, shy, surprised, focused).
• Close-up zooms – textures of fabric folds, skin details, hand gestures.
• Lifestyle & accessories – open handbag with daily items: lipstick, perfume, mirror compact, hand cream, diary, supplements.
• Material annotations – handwritten-style notes beside each item (e.g., “soft lace,” “matte leather,” “shade #520”).

Background: soft beige or parchment paper texture to evoke a design sketchbook.
Lighting: clean, soft shadows to unify the scene.
Output: high-quality 2D illustration in 4K, balanced between sensuality and fashion editorial.
Language: labels in Chinese + English.
```

---

## Yellowed old newspaper account

![Yellowed old newspaper account](https://opennana.com/awesome-prompt-gallery/images/569.jpeg)

- **Model:** Nano banana pro
- **Source:** [@songguoxiansen](https://x.com/songguoxiansen/status/1993959563251593223)
- **Tags:** fashion, illustration, nature, paper-craft, retro

**Prompt:**

```
Yellowed old newspaper account
9:16 fashion illustration in retro nostalgic style. The background mimics old, yellowed letter paper, with a hand-painted texture with a burnt effect and coffee stain marks around the edges. In the center are stickers of the user’s retro outfits, which are processed into film grain but retain the white sticker borders. Labubu doll sticker wearing retro sunglasses and floral shirt, sitting next to him. The clothing deconstruction section shows stickers on vintage leather jackets and oxford shoes. The hidden layer sticker is a vintage silk slip dress with a silky texture. Elegant cursive English date and vintage picture frame doodles drawn in pen and ink style around. The edges of the sticker are secured with a pattern of translucent washi tape. The picture is flat, without any writing tools or hands in the mirror, and it is a pure retro graphic design.
```

---

## Cream watercolor diary

![Cream watercolor diary](https://opennana.com/awesome-prompt-gallery/images/572.jpeg)

- **Model:** Nano banana pro
- **Source:** [@songguoxiansen](https://x.com/songguoxiansen/status/1993885921599693092)
- **Tags:** fashion, illustration, paper-craft

**Prompt:**

```
A 9:16 vertical screen high-end fashion illustration mood board, simulating the scanning effect of a tablet. The background is a pure hand-painted cream watercolor smudged paper with a subtle pink grid. The visual centerpiece is several sheets of glossy vinyl stickers with a distinct white die-cut wide edge and soft shadows. The center sticker is a photo of the user in a sweet date outfit, brightly lit. On the left is a deconstructed sticker of the outfit, with a neatly folded jacket and dainty heels. In the lower right corner is the key hidden layer sticker: a neatly folded set of high-end white lace underwear, showing off the delicate texture. A sticker of a Labubu art doll wearing a pink color that echoes the user's clothing is lying on a hand-drawn dialog box. The surroundings are decorated with crayon-textured hand-drawn hearts, glitter symbols and the scrawled Chinese calligraphy notation OOTD. There are absolutely no human hands, pens or physical desktop background in the picture, it is purely a graphic art illustration.
```

---

## Young woman sitting sideways on arcade stool

![Young woman sitting sideways on arcade stool](https://opennana.com/awesome-prompt-gallery/images/579.jpeg)

- **Model:** Nano banana pro
- **Source:** [@awesome_visuals](https://x.com/awesome_visuals/status/1994104753966686476)
- **Tags:** 3d, animal, illustration, interior, landscape, nature, neon, photography, portrait, retro

**Prompt:**

```
{ "subject": { "type": "young woman", "pose": "sitting sideways on an arcade stool, one knee up, hugging legs loosely, winking with exaggerated cuteness", "expression": "playful and lively" }, "clothing": { "top": "teal t-shirt with comic-outline shading", "bottom": "pink shorts", "socks": "purple crew socks", "shoes": "bright neon sneakers with translucent soles" }, "hair": { "color": "black", "style": "braided pigtails with neon hair ties" }, "environment": { "setting": "retro arcade interior", "details": "glowing cabinets, colorful reflections, cluttered neon lights" }, "lighting": { "type": "intense neon mixed lighting", "mood": "electric, colorful, kinetic" }, "camera": { "angle": "low-medium angle", "lens_effect": "wide lens, subtle distortion for dynamic feel", "framing": "tight arcade framing" }, "art_overlay": { "style": "overloaded sweets-monster pop-art", "description": "a hyper-busy explosion of candy-inspired monsters and neon shapes surrounding the subject while keeping skin photorealistic", "illustrated_elements": { "monsters": "goofy cute-ugly creatures made of donuts, chocolate chunks, banana ghosts, candy worms, gummy bears, soda bottles, strawberries, melting ice cream blobs", "graphic_shapes": "drips, splashes, stars, hearts, zigzags, spirals, speed lines, sparkles, comic bursts without text", "style": "flat graphic shapes with thick black outlines and bright neon hues" }, "placement_and_density": { "behavior": "extreme density filling almost all negative space", "behind_subject": "background jam-packed with overlapping layers of monsters", "around_subject": "creatures peeking behind shoulders, popping near head, sitting near feet", "over_clothing": "monsters overlapping shirt and shorts with subtle shading interaction", "avoid_skin": "no overlays touching the face, arms, or legs", "depth_layers": "front and back illustration layers creating chaotic dimensionality", "energy_effects": "white spark dots, glowing rims, dynamic speed lines around the figure" } }, "style": { "overall": "arcade portrait consumed by maximalist sweets-monster chaos", "aesthetic": "energetic, loud, neon-pop, surreal" } }
```

---

## Professional suit style diary

![Professional suit style diary](https://opennana.com/awesome-prompt-gallery/images/581.jpeg)

- **Model:** Nano banana pro
- **Source:** [@songguoxiansen](https://x.com/songguoxiansen/status/1994309283488444523)
- **Tags:** fashion, illustration, minimalist, paper-craft, typography

**Prompt:**

```
9:16 Minimalist fashion illustration. The background is a clean premium gray matte paper with only very thin engineering drawing lines. The layout of sticker elements is rigorous and the white edges are sharp. In the center is a sticker showing the user wearing a business suit or minimalist style. The Labubu doll sticker wears black-rimmed glasses and a tie, looking like an elite. Clothing deconstruction stickers include perfectly folded trousers and designer watches. The hidden layer sticker is a minimalist premium black silk slip that exudes understated luxury. All annotations are written in extremely fine black stylus pen. The picture is calm and restrained, without cluttered decorations, and displays a sense of high-end purely through layout and material contrast.
```

---

## Fresh blue wallet

![Fresh blue wallet](https://opennana.com/awesome-prompt-gallery/images/586.jpeg)

- **Model:** Nano banana pro
- **Source:** [@songguoxiansen](https://x.com/songguoxiansen/status/1994227033141100662)
- **Tags:** illustration, paper-craft

**Prompt:**

```
Vertical fashion illustration full of summer atmosphere. The background is a hand drawn blue ocean wave texture and beach color blocks using colored pencil textures. The main character sticker is wearing a long holiday dress or swimsuit and is sunny. Labubu figure sticker wearing a Hawaiian shirt and holding a surfboard or swim ring. Accessory stickers include straw bags and sunglasses. Hidden Layer Stickers are a set of delicate lace bikini or tulle cover-ups displayed flat. Cute doodles of palm trees, sun and cocktails are drawn around. A handwritten travel note with "Was here" in the corner of the sticker. The overall vibe is relaxed and cheerful, like scanned pages from a travel scrapbook.
```

---

## kawaii pop art

![kawaii pop art](https://opennana.com/awesome-prompt-gallery/images/589.jpeg)

- **Model:** Nano banana pro
- **Source:** [@songguoxiansen](https://x.com/songguoxiansen/status/1994239610713678137)
- **Tags:** cartoon, fashion, illustration, paper-craft, toy

**Prompt:**

```
Shot from a medium to low angle, a lovely young East Asian woman with fair, rosy skin, smooth and firm skin. She wore a pair of ponytails, too many colorful hairpins, and a Harajuku Decora-style outfit with an explosion of colors. She playfully made a "yeah" gesture on the busy streets of Tokyo. The style of the photo is overwhelmed by an overdose of kawaii pop art: countless illustrations of plastic toys, rainbows, unicorns, candies, smiley faces and giant bows fill the background and extend into the foreground, with some cartoon elements covering her clothes and accessories like stickers. The light is bright daylight, vibrant pastel colors.
```

---

## A vibrant mixed media masterpiece

![A vibrant mixed media masterpiece](https://opennana.com/awesome-prompt-gallery/images/611.jpeg)

- **Model:** Nano banana pro
- **Source:** [@ecommartinez](https://x.com/ecommartinez/status/1994126063656644727)
- **Tags:** animal, cartoon, fashion, food, illustration, landscape, nature, neon, photography, portrait, retro, vehicle

**Prompt:**

```
{
  "scene_description": "A vibrant, mixed-media masterpiece featuring a photorealistic version of the person from the reference photo eating at a diner, surrounded by a chaotic swarm of maximalist fast-food monsters.",

  "subject": {
    "type": "The person from the reference photo",
    "attire": "Same clothing style as in the reference, adapted naturally to the diner setting",
    "position": "Sitting in a red leather diner booth, holding a burger",
    "expression": "Shocked but amused, looking at a floating doodle pizza",
    "consistency_note": "Face, hairstyle and proportions must perfectly match the reference photo"
  },

  "action": {
    "primary": "Eating lunch",
    "effect": "Their food is coming to life in 2D form"
  },

  "illustration_layer": {
    "style": "Thick-line Pop Art cartoons",
    "creatures": [
      "Pizza slices surfing on cheese waves",
      "Burger beasts with lettuce tongues",
      "Angry French fry box",
      "Flying ketchup bottles."
    ],
    "graphics": "Mustard splashes, sesame seeds, heat lines, 'ÑAM' text bursts",
    "colors": "Ketchup Red, Mustard Yellow, Lettuce Green"
  },

  "environment": {
    "setting": "Retro American Diner",
    "background_elements": ["Checkerboard floor", "Neon sign in window"]
  },

  "lighting": {
    "style": "Warm Diner Glow",
    "key_light": {
      "type": "Window light",
      "color": "Warm afternoon sun"
    }
  },

  "style": {
    "medium": "Mixed Media Photography",
    "aesthetic": "Retro-pop, savory, chaotic",
    "quality": "Ultra-detailed textures vs flat cartoons"
  }
}
```

---

## A detailed technical illustration of a cyber warrior

![A detailed technical illustration of a cyber warrior](https://opennana.com/awesome-prompt-gallery/images/614.jpeg)

- **Model:** Nano banana pro
- **Source:** [@LudovicCreator](https://x.com/LudovicCreator/status/1994390935019360466)
- **Tags:** futuristic, illustration, sci-fi, typography

**Prompt:**

```
Create a detailed technical illustration of a Cybernetic Samurai, exploded into components: katana with energy core, cybernetic limbs, neural processor, armor plating, and internal power systems. Each part is labeled with clean futuristic font. Use a graphite and crimson color scheme on a dark blueprint background. Add subtle particle glow and depth shadows. Studio render style.
```

---

## Heartwarming moments between humans and robots

![Heartwarming moments between humans and robots](https://opennana.com/awesome-prompt-gallery/images/615.jpeg)

- **Model:** Nano banana pro
- **Source:** [@Samann_ai](https://x.com/Samann_ai/status/1994444395525832898)
- **Tags:** 3d, cartoon, character, fantasy, fashion, futuristic, illustration, interior, logo, minimalist, nature, photography, portrait, vehicle

**Prompt:**

```
{
  "prompt": "hyperrealistic ultra-detailed 8k photo of YOU (Upload Your Photo) standing in a bright cozy living room, same location as the reference: cream-colored sofa, large white curtains with soft daylight shining through, warm neutral walls, several green houseplants, minimal decor, natural sunlight and soft shadows. Use the uploaded photo as the main subject of the image, preserving the face, hairstyle, body type, clothing, and overall style exactly as in the uploaded photo. The subject is standing in front of the sofa, body slightly angled to the side, legs close together, one hip slightly popped, holding a smartphone in one hand at chest height, screen facing them, as if taking a mirror selfie, with a relaxed confident expression and slight smile, eyes toward the phone. Behind them, their partner is standing very close, a tall, attractive humanoid robot with a highly muscular, athletic build, entirely robotic with no human skin, detailed mechanical anatomy inspired by a futuristic cyborg: layered silver and gunmetal plates, visible bundles of flexible cables as muscles, complex joints, smooth armor around shoulders, chest, arms, and legs, elegant angular robotic face with a strong jawline, glowing blue eyes, subtle wear and micro-scratches on metal for realism. The robot’s torso is broad and V-shaped, narrow waist, perfect proportions, clearly fit and powerful but aesthetically beautiful. The robot stands just behind the subject with one sleek metallic arm wrapped gently and protectively around the front of their neck and shoulders, hand resting softly near the collarbone in an affectionate pose, the other arm relaxed at its side. Their bodies are close, giving a sense of intimacy and comfort. Extremely realistic skin texture on the subject, natural hair strands, detailed fabric texture and wrinkles on their clothing, realistic reflections and specular highlights on the robot’s metal surfaces, accurate global illumination and depth of field, sharp focus on both characters, slight background blur. Photoreal, cinematic lighting, no fantasy effects, looks like a real candid photo taken on a phone in this apartment.",
  "negative_prompt": "cartoon, anime, illustration, painting, 3d render, CGI, low resolution, blurry, grainy, oversaturated, unrealistic proportions, extra limbs, deformed hands, distorted face, visible mirror edges, text, watermark, logo, armor covering the subject, human skin on the robot, grotesque, horror, gore"
}
```

---

## Hand drawn beauty science chart

![Hand drawn beauty science chart](https://opennana.com/awesome-prompt-gallery/images/624.jpeg)

- **Model:** Nano banana pro
- **Source:** [@cnyzgkc](https://x.com/cnyzgkc/status/1994954677579125124)
- **Tags:** cartoon, character, illustration, infographic, nature, portrait, typography

**Prompt:**

```
Hand-drawn watercolor infographic, warm soft watercolor texture, pink tone, cute and clean design, 4:5 ratio, 1080x1350.

Character: An illustrator and doctor who specializes in medical care. He has a friendly smile and holds a watercolor pen. His style is cartoonish and cute.

Main title (above): What nutrients will make you look ugly if you lack it? The doctor’s vitamin beauty formula!

Chart structure (starting below):
Six cute characters, showing six "ugly symptoms", with corresponding cartoon nutrient icons.

Sample content (AI can be freely redrawn, do not be realistic):
1. Dull skin → Vitamin C (Vitamin C cartoon image)
2. Dry eyes → Vitamin A (Vitamin A cartoon image)
3. Hair loss → Vitamin B, vitamin D (B complex, D cartoon image)
4. (You can continue to automatically generate more symptoms and nutrients based on the copy)

Style requirements:
Hand-painted watercolor, pink main tone, soft and natural, relaxed and comfortable atmosphere.
The characters should be cute, rounded, and friendly.
Nutrient icons are in cartoon anthropomorphic style.
The text is in a clear and easy-to-read handwritten note-like font.
The overall layout is concise and in the form of information charts.

Lighting: soft, diffuse watercolor lighting.
Avoid: photo-like, real skin texture, excessive realism, oil painting style, metallic luster.

best quality, high-res, clean edges, masterpiece.
```

---

## Add candy monsters around characters

![Add candy monsters around characters](https://opennana.com/awesome-prompt-gallery/images/625.jpeg)

- **Model:** Nano banana pro
- **Source:** [@AI_GIRL_DESIGN](https://x.com/AI_GIRL_DESIGN/status/1993243344932413597)
- **Tags:** cartoon, fashion, food, illustration, landscape, neon, paper-craft, photography, portrait, vehicle

**Prompt:**

```
Use the uploaded photo. 
Do NOT alter the person’s real appearance — keep the person’s face, body, clothing, colors, and texture completely photorealistic. 
Do NOT change the background perspective. 
Do NOT turn the person into a drawing or illustration.

Add a dense, overloaded layer of pop-style illustrated “sweets monsters” and graphic decorations ONLY around the person (and on top of their clothing if needed), but never on their skin or face.

Illustrated elements:
- many colorful cartoon monsters with thick black outlines, flat colors, and cute-but-ugly expressions
- sweets-inspired monsters: bananas, cookies, strawberries, melting chocolate, lollipops, ice cream, oranges, cupcakes, donuts, candy pieces, soda bottles, etc.
- additional graphic shapes: stars, hearts, arrows, drips, splashes, zigzag lines, exclamation marks, motion lines, sparkles, bubbles, comic-style text shapes (but no real text)

Make the decoration very dense and “busy”:
- fill the space behind the person with overlapping sweets monsters and shapes
- add monsters peeking from behind the shoulders, around the bag, at the person’s feet, and near the head
- allow some monsters and shapes to overlap the clothing and accessories (shirt, shorts, bag, shoes), but keep the skin of the face, arms, and legs photorealistic and visible
- use multiple layers of illustrations in front of and behind the person to create depth
- add glowing outlines, small white dots, and speed lines around the person to emphasize energy

Color and style:
- use a vivid, neon-like color palette (hot pink, yellow, cyan, lime, orange, purple, turquoise)
- keep all illustrated elements flat and graphic with clean edges and bold outlines
- ensure shadows and overlap suggest interaction with the real person (e.g., slight shadows on clothing where monsters touch)

Overall goal:
Create a highly decorated, maximalist pop-art scene where the real person stands in the middle, surrounded and wrapped by a chaotic crowd of playful sweets monsters and graphic doodles, while the person remains clearly photorealistic.
```

---

## 3D three-dimensional book illustration

![3D three-dimensional book illustration](https://opennana.com/awesome-prompt-gallery/images/636.jpeg)

- **Model:** Nano banana pro
- **Source:** [@azed_ai](https://x.com/azed_ai/status/1995084424489422885)
- **Tags:** 3d, illustration, landscape, paper-craft

**Prompt:**

```
A 3D pop-up book illustration featuring a [subject], with layered paper elements unfolding into a miniature scene. Soft lighting, textured paper surfaces, playful handcrafted look, pastel [color1] and [color2] palette, viewed from a slight angle to show depth and detail.
```

---

## Blackboard Artwork-Pirate Empress

![Blackboard Artwork-Pirate Empress](https://opennana.com/awesome-prompt-gallery/images/642.jpeg)

- **Model:** Nano banana pro
- **Source:** [@IamEmily2050](https://x.com/IamEmily2050/status/1994624635300974734)
- **Tags:** character, felt, illustration, interior, landscape, logo, nature, paper-craft, photography, portrait

**Prompt:**

```
{
  "intent": "Photorealistic documentation of a specific chalkboard art piece featuring a single anime character, capturing the ephemeral nature of the medium within a classroom context.",
  "frame": {
    "aspect_ratio": "4:3",
    "composition": "A centered medium shot focusing on the chalkboard mural. The composition includes the teacher's desk in the immediate foreground to provide scale, with the artwork of the single character dominating the background space.",
    "style_mode": "documentary_realism, texture-focused, ambient naturalism"
  },
  "subject": {
    "primary_subject": "A large-scale, intricate chalk drawing of Boa Hancock from 'One Piece' on a standard green classroom blackboard.",
    "visual_details": "The illustration depicts Boa Hancock in a commanding pose, positioned centrally on the board. She is drawn with her signature long, straight black hair with a hime cut, rendered using dense application of black chalk with white accents for sheen. Her expression is haughty and imperious, with detailed dark blue eyes. She is depicted forming a heart shape with her hands, referencing her 'Mero Mero Mellow' technique. She wears a revealing red blouse with purple geometric and patterns gold snake-shaped earrings, drawn with vibrant colored chalks.",
    "medium_texture": "The image preserves the dusty, matte quality of the chalk. Visible hatching and cross-hatching strokes create shading on her clothing and hair. Smudged areas on the green slate indicate where colors have been blended by hand.",
    "surrounding_elements": "To the right of the character, vertical Japanese text reading 'Pirate Empress' (Pirate Empress) is written in crisp white chalk."
  },
  "environment": {
    "location": "A standard Japanese school classroom.",
    "foreground_elements": "A wooden teacher's desk occupies the lower foreground. Scattered across the surface are a yellow box of colored chalks, loose sticks of red, white, and blue pastel chalk, and a dust-covered black felt eraser.",
    "background_elements": "The green chalkboard spans the width of the frame, bordered by a metallic chalk tray containing accumulated chalk dust. The wall above is a plain, off-white plaster, featuring a small mounted speaker box.",
    "atmosphere": "Quiet and academic, with a sense of stillness suggesting the room is currently unoccupied."
  },
  "lighting": {
    "type": "Diffuse ambient classroom lighting.",
    "quality": "Soft, nondirectional illumination provided by overhead fluorescent fixtures mixed with daylight from windows on the left. The light is even, preventing glare on the chalkboard surface while highlighting the texture of the chalk.",
    "color_temperature": "Neutral white, approximately 5000K, ensuring accurate color rendition of the red and purple chalks against the dark green board.",
    "direction": "Overhead and slightly frontal."
  },
  "camera": {
    "sensor_format": "35mm full-frame digital sensor.",
    "lens": "35mm prime lens.",
    "aperture": "f/5.6",
    "depth_of_field": "Moderate depth of field, keeping the chalkboard drawing in sharp focus while allowing the foreground desk elements to soften slightly.",
    "shutter_speed": "1/60s",
    "iso": "400",
    "camera_position": "Eye-level standing position, set back enough to frame the entire drawing and the desk."
  },
  "negative": {
    "content": "Multiple characters, Midoriya, Shigaraki, male characters, digital art overlay, vector graphics, paper texture, oil painting, messy composition, extreme low angle, fisheye lens.",
    "style": "No hyper-saturation, no soft focus filters, no heavy vignetting."
  }
}
```

---

## A mini version of myself is standing in the cavity of the head

![A mini version of myself is standing in the cavity of the head](https://opennana.com/awesome-prompt-gallery/images/650.jpeg)

- **Model:** Nano banana pro
- **Source:** [@madpencil_](https://x.com/madpencil_/status/1994891011861221665)
- **Tags:** fantasy, illustration, nature, retro

**Prompt:**

```
"A surreal, whimsical digital illustration of a young woman with pale pink skin and voluminous, floating black hair. Her head is horizontally split open at the nose level. Inside the hollow of her head, a tiny, miniature version of herself (wearing the same attire) is standing and physically lifting the top half of the head (containing the closed eyes and forehead) up with her hands. The space inside the split head reveals a dark blue starry night sky or cosmic void.

Art style: Modern flat illustration with a lo-fi, grainy texture. Soft pastel colors including lavender, periwinkle, and peach. The shading is subtle and soft using gradients. There is a noise overlay/stipple effect giving it a retro print look. The background is a solid soft purple gradient with scattered white stardust. Emotional, dreamy, metaphorical."
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

## Extremely close selfie

![Extremely close selfie](https://opennana.com/awesome-prompt-gallery/images/666.jpeg)

- **Model:** Nano banana pro
- **Source:** [@IamEmily2050](https://x.com/IamEmily2050/status/1995065474749730989)
- **Tags:** character, illustration, landscape, minimalist, neon, photography, portrait, retro, vehicle

**Prompt:**

```
{
  "intent": "Generate a hyper-idealized, 'Douyin-aesthetic' portrait of a young woman at night, utilizing direct flash photography to create a high-contrast, ethereal look with clear weather conditions.",
  "frame": {
    "aspect_ratio": "9:16",
    "composition": "Extreme close-up selfie framing (tighter than standard portrait), cutting off the top of the forehead to focus intensely on the eyes and lips. The subject is centered with a direct, confronting gaze.",
    "style_mode": "Flash photography, digital influencer aesthetic, soft-focus realism."
  },
  "subject": {
    "identity": "A young Asian woman, approximately 20 years old, with hyper-symmetrical, doll-like features characterized by the 'bunny tongue' and 'puppy eye' aesthetic.",
    "skin": "Pale, cool-toned porcelain complexion with zero texture. The skin reflects the flash, creating a 'mochi' or 'glass skin' effect that appears soft and translucent. High-key brightness on the T-zone.",
    "eyes": "Large, round eyes with a slight downward tint at the outer corners (puppy dog eyes). Prominent 'aegyosal' (under-eye fat bands) are highlighted to enhance youthfulness. The irises are soft brown with a large diameter. Eyelashes are styled in the 'manhwa' or 'idol' style: distinct, vertical clumps of mascara-coated lashes separated by space, rather than a dense fan.",
    "nose": "Petite, low-bridge nose with a small, rounded tip. The lighting minimizes the nostril definition, making the nose appear delicate and unobtrusive.",
    "mouth": "Heart-shaped lips featuring a 'gradient lip' technique. The center of the lips is a saturated, glossy strawberry pink, fading outward to a blurred, pale nude at the vermilion border. The texture is soft and hydrated.",
    "hair": "Long, silky jet-black hair with a straight texture. Without the snow, the hair is dry, sleek, and tucked slightly behind the ears or framing the face smoothly, catching the flash with a white sheen.",
    "wardrobe": "Minimal visibility, suggesting a stylish but casual top appropriate for a pleasant evening."
  },
  "environment": {
    "location": "Urban night setting.",
    "weather": "Clear, calm, and beautiful night weather. The atmosphere is clean and free of precipitation or fog.",
    "background": "A backdrop of deep black shadows punctuated by creamy, circular bokeh from distant city lights (streetlamps, neon signs). The background is significantly darker than the subject, ensuring the face is the sole focus."
  },
  "lighting": {
    "type": "Direct, frontal camera flash or high-intensity screen light.",
    "quality": "Hard but flattering light that flattens facial topography, eliminating shadows under the eyes and nose. This creates a 2D, illustrative quality common in high-end social media selfies.",
    "contrast": "High contrast between the brightly illuminated face and the pitch-black environment.",
    "catchlight": "Sharp, tiny pinpoint reflection in the center of the pupils from the flash."
  },
  "camera": {
    "sensor_format": "Smartphone main sensor simulation.",
    "lens": "24mm wide-angle lens. This focal length slightly exaggerates the size of the eyes and diminishes the size of the nose and face width, contributing to the 'baby face' proportion.",
    "aperture_depth_of_field": "f/1.8 to f/2.2, keeping the eyes and lips razor sharp while instantly blurring the ears and background.",
    "focus": "Critical focus on the eyelashes and iris texture."
  },
  "negative": {
    "content": "No snow, no rain, no wet hair, no masculine jawline, no skin texture, no pores, no heavy contouring, no western makeup style, no sunglasses, no hand near face.",
    "style": "No cinematic dramatic shadows (must be flat lit), no warm vintage tones, no painting, no illustration."
  }
}
```

---

## Horoscope card

![Horoscope card](https://opennana.com/awesome-prompt-gallery/images/671.jpeg)

- **Model:** Nano banana pro
- **Source:** [@cnyzgkc](https://x.com/cnyzgkc/status/1995423285060976700)
- **Tags:** illustration, typography

**Prompt:**

```
Please help me search for today's latest fortune for "zodiac sign" first. The key points include: overall fortune, love fortune, career fortune, wealth fortune, as well as today's lucky color and lucky number. Next, please use Nano Banana Pro to draw a horoscope story card in the style of a literary hand-drawn graphic illustration based on today's fortune content. It requires exquisite layout and rich element design, simplified Chinese, 2K, and a 2:3 ratio.
```

---

## Wedding photos in the garden

![Wedding photos in the garden](https://opennana.com/awesome-prompt-gallery/images/683.jpeg)

- **Model:** Nano banana pro
- **Source:** [@miilesus](https://x.com/miilesus/status/1995536025859354724)
- **Tags:** cartoon, fashion, illustration, interior, logo, nature, photography, pixel, portrait, vehicle

**Prompt:**

```
{
 "Use [man_face] and [woman_fac]. Ultra-realistic high-end luxury wedding photography of a bride and groom standing closely together in an elegant outdoor ceremony setting. Golden hour sunlight casting warm soft highlights, natural rim light around their silhouettes, cinematic dynamic range. The bride wearing a premium handcrafted lace wedding gown with intricate embroidery details, soft flowing veil illuminated by backlight, subtle pearl accessories, refined natural bridal makeup with luminous skin texture, finely detailed eyelashes and catchlights in eyes. The groom wearing a tailored black tuxedo with satin lapels, crisp white shirt, luxury bow tie, polished boutonniere. Both posing in a candid yet editorial fashion – gentle eye contact, soft romantic smile, hands touching gracefully. Background featuring a softly blurred bokeh garden with roses, organic greenery, warm tones, shallow depth of field created by an 85mm f/1.4 full-frame lens. High-definition textures, ultra sharp facial details, realistic pores, true-to-life skin tones, natural hair strands, perfect color grading inspired by premium wedding photographers. Soft pastel color palette, creamy highlights, subtle film grain, magazine cover aesthetic. Cinematic global illumination, perfect exposure balance, no distortion, no artifacts. Award-winning photography style with fine-art wedding composition, dramatic yet soft lighting, museum-quality detail clarity.",
  
  "negative_prompt": "cartoon, illustration, painting, CGI, artificial look, uncanny valley, distorted facial features, extra limbs, deformed body parts, mismatched eyes, unnatural skin texture, plastic skin, blur, noise, pixelation, low resolution, oversaturated colors, washed out colors, hard flash, harsh shadows, blown highlights, low contrast, lens distortion, fisheye, bad anatomy, extra fingers, incorrect hand shapes, watermark, text, logo, border, frame, compression artifacts, glitch, unrealistic proportions, double face, duplicate subjects, warped background",

  "camera_settings": {
    "lens": "85mm f/1.4 prime",
    "iso": 100,
    "shutter_speed": "1/400",
    "aperture": "f/1.4",
    "white_balance": "5200K daylight"
  },

  "style": {
    "lighting": "soft natural golden hour, cinematic rim light, high dynamic range",
    "color_grade": "premium wedding film look, pastel tones, creamy highlights, warm undertones",
    "atmosphere": "romantic, elegant, fine-art editorial"
  },

  "composition": {
    "framing": "mid-shot portrait, slight angle, bride and groom centered",
    "focus": "sharp eyes, smooth bokeh background",
    "depth_of_field": "shallow, subject separation emphasized"
  },

  "width": 1024,
  "height": 1536,
  "num_inference_steps": 36,
  "guidance_scale": 8.0,
  "seed": 12345
}
```

---

## Label all items in English and Japanese

![Label all items in English and Japanese](https://opennana.com/awesome-prompt-gallery/images/691.jpeg)

- **Model:** Nano banana pro
- **Source:** [@ytiskw](https://x.com/ytiskw/status/1995730583373197440)
- **Tags:** illustration

**Prompt:**

```
Please draw an illustration of a bedroom. Label all items in English/Japanese. Please write in the following format: English (Japanese).
```

---

## Close-up of tender young woman

![Close-up of tender young woman](https://opennana.com/awesome-prompt-gallery/images/699.jpeg)

- **Model:** Nano banana pro
- **Source:** [@YaseenK7212](https://x.com/YaseenK7212/status/1995172379991883987)
- **Tags:** 3d, cartoon, character, illustration, nature, photography, vehicle

**Prompt:**

```
{
  "pipeline_configuration": {
    "job_type": "img2img_transformation",
    "meta_tags": ["macro", "beauty", "soft_focus", "realism"],
    
    "input_reference_handling": {
      "preservation_rules": {
        "facial_identity": {
          "strength": 1.0,
          "instruction": "Strict 100% preservation of facial geometry and features.",
          "technique": "FaceID / IP-Adapter Strong"
        },
        "color_palette": {
          "target": "Hair Color",
          "mode": "inherit_from_source",
          "instruction": "Do not hallucinate new hair color. Map source color to new hair texture."
        }
      }
    },

    "generative_parameters": {
      "subject_definition": {
        "hair_morphology": {
          "length": "Short",
          "texture_type": "Wavy",
          "styling_aesthetic": "Intentionally messy, artfully disheveled",
          "micro_details": "Fine strands falling across forehead and near eyes",
          "color_override": null
        },
        "facial_details": {
          "expression": "Serene, gentle",
          "makeup_style": "Natural, soft-beauty approach",
          "surface_texture": "Ultra-clean skin with visible macro pores"
        }
      },

      "scene_composition": {
        "camera_settings": {
          "proximity": "Extreme Close-Up (Macro)",
          "depth_of_field": "Ultra-shallow",
          "focus_target": "Eyes",
          "lens_character": "Soft beauty lens"
        },
        "foreground_layers": {
          "element": "Hand",
          "state": "Partially blurred",
          "purpose": "Framing effect, adding depth and intimacy"
        },
        "background_layers": {
          "state": "Fully out of focus",
          "visuals": "Pastel, soft tones",
          "bokeh_quality": "Strong, smooth, creamy"
        }
      },

      "lighting_and_atmosphere": {
        "style": "Soft-beauty photography",
        "dynamic_range": "High (HDR)",
        "quality": "Airy, bright, diffused",
        "reflections": {
          "eyes": "Crisp, sharp catchlights",
          "lips": "Soft, natural shine"
        }
      }
    },

    "text_prompts": {
      "weighted_positive": {
        "(Masterpiece, Best Quality, 8k, Macro Photo)": 1.5,
        "Extreme close-up of young woman with serene gentle expression": 1.3,
        "Short wavy messy hair with stray wisps over eyes": 1.2,
        "Hand in foreground partially blurred framing the face": 1.2,
        "Macro skin texture, pores visible, individual hair strands": 1.4,
        "Ultra-sharp eyes with crisp reflections": 1.3,
        "Soft pastel bokeh background": 1.1,
        "Soft diffused lighting, airy aesthetic": 1.0
      },
      "weighted_negative": {
        "alteration of face, new hair color, long hair": 1.5,
        "plastic skin, airbrushed, smooth": 1.4,
        "cartoon, 3d render, illustration": 1.3,
        "deep focus, sharp background, clutter": 1.2,
        "deformed hand, bad anatomy": 1.4
      }
    }
  }
}
```

---

## Generate 3×3 photo grid photos

![Generate 3×3 photo grid photos](https://opennana.com/awesome-prompt-gallery/images/702.jpeg)

- **Model:** Nano banana pro
- **Source:** [@iX00AI](https://x.com/iX00AI/status/1995130835218186540)
- **Tags:** cartoon, fashion, illustration, minimalist, photography, vehicle

**Prompt:**

```
Generate a 3×3 photo grid.
Fully preserve the face, hairstyle, and outfit from the uploaded image in all panels.

The person should make a cute, funny, and slightly weird expression and pose, and the same expression & pose must be consistent across all 9 panels.

Each panel should use a different camera angle.
Use the following angles, in varied composition and framing:
1. High angle (top-down)
2. Low angle (from below)
3. Eye-level straight-on
4. Dutch angle (slightly tilted)
5. Close-up low angle
6. Over-the-shoulder angle
7. Wide shot from the side
8. 45-degree angle from the front
9. Slight bird’s-eye angle

Style Requirements:
•Photorealistic, clean lighting
•Real camera lens rendering
•No illustration or cartoon look
•Same outfit, face, and hairstyle across all images
•The pose and expression stay identical across the grid
•Modern, minimal aesthetic
```

---

## Children's hand drawn travel diary style

![Children's hand drawn travel diary style](https://opennana.com/awesome-prompt-gallery/images/703.jpeg)

- **Model:** Nano banana pro
- **Source:** [@TechieBySA](https://x.com/TechieBySA/status/1995445643414847987)
- **Tags:** character, food, illustration, landscape, logo, nature, paper-craft, typography

**Prompt:**

```
“Create a vibrant, child-like crayon-style vertical (4:5) illustration titled “{City Name} Travel Journal.”  
The artwork should look as if it were drawn by a curious child using colorful crayons, featuring a soft, warm light-toned background (such as pale yellow), combined with bright reds, blues, greens, and other cheerful colors to create a cozy, playful travel atmosphere.

I. Main Scene: Travel-Journal Style Route Map

In the center of the illustration, draw a “winding, zigzagging travel route” with arrows and dotted lines connecting multiple locations.  
The route should automatically generate recommended attractions based on {Number of Days}:

Example structure (auto-filled with {City Name}-related content):

- “Stop 1: {Attraction 1 + short fun description}”
- “Stop 2: {Attraction 2 + short fun description}”
- “Stop 3: {Attraction 3 + short fun description}”
- …
- “Final Stop: {Local signature food or souvenir + warm closing remark}”

Rules:
- If no number of days is provided, default to a 1-day highlight itinerary.

II. Surrounding Playful Elements (Auto-adapt to the City)

Add many cute doodles and child-like decorative elements around the route, such as:

1. Adorable travel characters
   - A child holding a local snack  
   - A little adventurer with a backpack

2. Q-style hand-drawn iconic landmarks
   - “{City Landmark 1}”
   - “{City Landmark 2}”
   - “{City Landmark 3}”

3. Funny signboards
   - “Don’t get lost!”
   - “Crowds ahead!”
   - “Yummy food this way!”  
   (Auto-adjust contextually for the city)

4. Sticker-style short phrases
   - “{City Name} travel memories unlocked!”
   - “{City Name} food adventure!”
   - “Where to next?”

5. Cute icons of local foods
   - “{Local Food 1}”
   - “{Local Food 2}”
   - “{Local Food 3}”

6. Childlike exclamations
   - “I didn’t know {City Name} was so fun!”
   - “I want to come again!”

III. Overall Art Style Requirements

- Crayon / children’s hand-drawn travel diary style  
- Bright, warm, colorful palette  
- Cozy but full and lively composition  
- Emphasize the joy of exploring  
- All text should be in a cute handwritten font  
- Make the entire page feel like a young child’s fun travel-journal entry”
```

---

## Artistic digital scrapbooking style

![Artistic digital scrapbooking style](https://opennana.com/awesome-prompt-gallery/images/711.jpeg)

- **Model:** Nano banana pro
- **Source:** [@ZaraIrahh](https://x.com/ZaraIrahh/status/1996032358408224869)
- **Tags:** cartoon, character, illustration, interior, minimalist, nature, paper-craft, photography, portrait, vehicle

**Prompt:**

```
{
  "image_generation": {
    "face_preservation": {
      "preserve_original": true,
      "match_reference_face": true,
      "accuracy": "100% identical to the reference photo",
      "details": [
        "same facial proportions",
        "same realistic skin texture",
        "same eye shape and lashes",
        "natural soft lips",
        "same expression as reference"
      ]
    },

    "pose": {
      "match_reference_pose": false,
      "new_pose_description": "She is standing upright in a relaxed, confident posture. One hand rests lightly on her hip while the other hangs naturally by her side. Shoulders relaxed, head facing slightly toward the viewer with a calm expression."
    },

    "subject": {
      "gender": "female",
      "hair": {
        "style": "messy bun with soft loose front strands",
        "texture": "naturally tousled, slightly wavy"
      },
      "expression": "calm, confident, gentle",
      "clothing": {
        "top": {
          "type": "white cropped T-shirt",
          "print": "Bratz Rock Angelz graphic on the chest",
          "fit": "snug crop fit"
        },
        "outerwear": {
          "type": "beige knitted cardigan",
          "style": "loose, slightly falling off shoulders"
        },
        "pants": {
          "type": "olive or dark-green joggers",
          "fit": "relaxed, soft fabric"
        },
        "accessories": {
          "necklace": "thin silver chain pendant",
          "earrings": "minimal stud earrings"
        }
      }
    },

    "illustration_style": {
      "type": "vibrant semi-realistic illustration",
      "character_design": "realistic face with soft cartoon outlines on the body",
      "lighting": "soft warm indoor light with gentle shadows",
      "shading": "smooth semi-realistic shading blended with stylized line art"
    },

    "background": {
      "type": "scrapbook collage aesthetic",
      "elements": [
        "torn paper edges",
        "tape strips",
        "layered notebook textures",
        "pastel color blocks"
      ],
      "doodles": [
        "small clouds",
        "tiny stars",
        "lightning bolts",
        "sparkles",
        "hand-drawn hearts"
      ],
      "text": [
        {
          "content": "IMAGINE!",
          "style": "crayon-like scribble"
        },
        {
          "content": "NOW!",
          "style": "bold marker handwriting"
        }
      ]
    },

    "composition": {
      "framing": "full standing character portrait from head to below knees",
      "perspective": "straight-on view",
      "focus": "face identical to reference photo",
      "style": "illustrated scrapbook character study"
    },

    "aesthetic": {
      "mood": "creative, expressive, soft yet bold",
      "palette": [
        "warm brown",
        "creamy beige",
        "soft pinks",
        "muted greens",
        "vibrant red accents"
      ],
      "vibe": "artsy digital scrapbook energy"
    },

    "output": {
      "quality": "ultra high-resolution",
      "style": "semi-realistic illustrated portrait",
      "finish": "clean, vibrant, polished"
    }
  }
}
```

---

## Photos turned into beautiful acrylic artwork

![Photos turned into beautiful acrylic artwork](https://opennana.com/awesome-prompt-gallery/images/712.jpeg)

- **Model:** Nano banana pro
- **Source:** [@MatoToushi](https://x.com/MatoToushi/status/1995694265066991831)
- **Tags:** character, illustration, photography, product

**Prompt:**

```
Product photography, perfectly straight-on frontal view. CRITICAL: The original art style, linework, and character features of the input illustration MUST BE STRICTLY PRESERVED. Do not abstract or simplify the drawing itself.

The artwork is a physical multi-layered construction mounted on a white wall.
**COMPOSITION RULE:**
1. The aspect ratio and orientation of the final product photography should match the dimensions of the input source image.
2. A large clear base panel is secured with visible metallic standoffs.
3. Crucially, the entire die-cut illustration (all layers) MUST be contained entirely within the boundaries of this base panel.
4. There should be an appropriate clear margin between the edges of the illustration and the edges of the base panel.

**MATERIAL PHYSICS RULE (HIGH TRANSMISSION):**
On top of the base, the illustration is reconstructed using **ultra-clear, highly luminous tinted acrylic sheets** designed for maximal light transmission.
1. The colors are the color of the transparent material itself (glass-like), not painted.
2. **For Skin/White Areas:** MUST be **pure, colorless, ultra-clear glass-like acrylic**.
3. **For Colored Areas (Hair/Clothes):** Use **highly translucent colored acrylic**. The color is vibrant but extremely see-through, allowing significant light to pass.

**LIGHTING & SHADOWS:**
Strong cool diagonal lighting passes through the highly transparent artwork. **Instead of creating dark or heavy shadows, the light casts bright, glowing, highly translucent colorful caustics onto the wall, showing the wall's texture underneath.** The shadow area should feel light and airy, revealing the original colors as bright projections. 8k resolution, ultra-detailed.
```

---

## porcelain doll style photos

![porcelain doll style photos](https://opennana.com/awesome-prompt-gallery/images/715.jpeg)

- **Model:** Nano banana pro
- **Source:** [@SimplyAnnisa](https://x.com/SimplyAnnisa/status/1995860432423453003)
- **Tags:** fantasy, fashion, illustration, nature, photography, retro

**Prompt:**

```
Edit this photo without changing the face. The face must remain completely authentic and 100% recognizable. The woman’s face has very smooth, pale skin with a warm undertone, giving a soft, porcelain doll-like appearance. Her expression is gentle, innocent, and slightly melancholic, as if she is hugging a doll with feelings of nostalgia or comfort. The cheeks have a peach-pink blush concentrated under the eyes and along the sides of the nose, creating a warm, shy, and flushed effect.

Her eyes are very large, round, and sparkling, resembling illustrated or doll-like eyes. The irises are dark brown but appear bright and glossy, likely enhanced with large-diameter contact lenses. The eyelashes are long and thick, both upper and lower, adding dramatic fullness to the eyes. Soft eyeshadow in peach, milky brown, and a hint of shimmer is applied subtly to enlarge the eyes naturally. A faint line under the eyes (aegyo sal) gives a cute and youthful impression.

The lips are soft peach and glossy, small and slightly pointed, with gently blended edges for a sweet and innocent look. No extreme ombre effects are used; the lip makeup appears natural and dewy.

Her hair is voluminous, softly curled, and dark brown with light highlights that shimmer under the light. A thin center-parted fringe frames the face gently. The sides of the hair are decorated with small white ribbons and delicate lace, creating a vintage-princess or Victorian doll aesthetic. The hairstyle is intricate yet elegant, combining classic style with a modern touch.

She is hugging a light brown (beige) teddy bear with soft, plush fur. The bear wears a small checkered ribbon in red, black, and white around its neck. The bear is held close to her chest, conveying warmth, softness, and a sense of security.

Her hands are smooth, slender, and feminine, gently holding the teddy bear. Her body leans slightly forward, as if embracing the bear more closely. The fingers are long with natural, neatly kept nails.

She wears vintage, classic clothing with lace details, predominantly cream and white, featuring delicate floral lace, small off-white ribbons, and layered thin fabrics that create a romantic look. The outfit resembles Lolita fashion, cottagecore, or soft Victorian style.

The lighting is warm with a golden tone, evoking nostalgia, comfort, and a dreamlike atmosphere. The background contains decorative elements such as wooden textures, vintage ornaments, and soft golden hues, supporting the theme of comfort, childhood warmth, softness, and doll-like innocence.

The overall aesthetic emphasizes dollcore, vintage romantic, cottage and Victorian softness, warm nostalgia, and soft feminine fantasy, creating an intimate, warm, and elegantly cute atmosphere.
```

---

## a sketch of a certain character

![a sketch of a certain character](https://opennana.com/awesome-prompt-gallery/images/721.jpeg)

- **Model:** Nano banana pro
- **Source:** [@CharaspowerAI](https://x.com/CharaspowerAI/status/1996270726026784792)
- **Tags:** character, illustration, paper-craft

**Prompt:**

```
a drawing of [Character], crayon on white paper, in the style of a children's book illustration – simple, cute, and full-color, with [two glitter accent colors] glitter accents and high detail.
```

---

## Transform comic book characters into hyper-realistic humans

![Transform comic book characters into hyper-realistic humans](https://opennana.com/awesome-prompt-gallery/images/734.jpeg)

- **Model:** Nano banana pro
- **Source:** [@dotey](https://x.com/dotey/status/1996281855503372510)
- **Tags:** cartoon, character, fashion, illustration, landscape, photography, pixel, portrait, vehicle

**Prompt:**

```
Transform this comic character into an ultra-realistic human while preserving the original hairstyle, outfit, facial expression, and overall character identity.
The entire scene should use deep depth of field, keeping both the model and the environment extremely sharp, creating an immersive, cinematic smartphone photography look.

STYLE:
- Cinematic ultra-realistic fashion photography
- High-resolution smartphone camera aesthetic with crisp, sharp details
- Dramatic lighting contrast between warm work lights and cool twilight tones
- the model is the main subject while retaining rich environmental details

TECHNICAL SPECS:
- Camera: flagship smartphone camera
- Lens: standard built-in phone lens
- Aperture: f/8–f/11 for deep depth of field
- Resolution: 4K or higher

NEGATIVE PROMPT:
- blurry background, shallow depth of field, bokeh
- out of focus, distorted face
- cartoon, anime, CGI character, illustration, painting look
- low quality, pixelation, noise
- harsh direct sunlight or overexposed lighting
```

---

## Hand drawn portrait illustration in red and yellow colors

![Hand drawn portrait illustration in red and yellow colors](https://opennana.com/awesome-prompt-gallery/images/751.jpeg)

- **Model:** Nano banana pro
- **Source:** [@cnyzgkc](https://x.com/cnyzgkc/status/1997231229431857332)
- **Tags:** illustration, nature, paper-craft, portrait

**Prompt:**

```
Use my uploaded image. Generate a hand-drawn portrait illustration in red and yellow pen on notebook paper, inspired by doodle art and comic annotations.Keep full likeness of the subject, expressive lines, spontaneous
gestures, bold outline glow,
handwritten notes around, realistic pen stroke texture,4K resolution.
```

---

## The perfect blend of photos and sketches

![The perfect blend of photos and sketches](https://opennana.com/awesome-prompt-gallery/images/767.jpeg)

- **Model:** Nano banana pro
- **Source:** [@_MehdiSharifi_](https://x.com/_MehdiSharifi_/status/1996969905678143983)
- **Tags:** 3d, fantasy, illustration, interior, landscape, nature, photography, pixel, portrait

**Prompt:**

```
{
  "image_request": {
    "goal": "Create a whimsical mixed-media masterpiece blending realistic top-down photography with playful white line-art doodles, depicting a sleeping woman dreaming of a deep-sea scuba adventure",
    "meta": {
      "image_type": "Mixed Media Photography / Creative Conceptual Art / Surreal Dreamscape",
      "quality": "8K, Ultra-HD, Masterpiece, High Fidelity, Creative Composite",
      "color_mode": "Cool Nocturnal Blues / Monochromatic Teal Palette with Stark White Lines",
      "style_mode": "cinematic_mixed_media",
      "aspect_ratio": "1:1",
      "resolution": "1440x1440px"
    },
    "creative_style": "Playful and surreal integration of hand-drawn illustration over realistic photography, evoking a sense of childhood wonder and vivid dreaming, combining the cozy texture of bedding with the adventurous spirit of an underwater doodle world",
    "overall_theme": "dreaming of adventure / underwater fantasy / mixed media art / playful imagination",
    "mood_vibe": "serene, whimsical, imaginative, peaceful, creative, cool, nocturnal",
    "style_keywords": [
      "mixed media",
      "doodle art overlay",
      "white line art",
      "top-down perspective",
      "flat lay",
      "surrealism",
      "scuba diving",
      "dream concept",
      "night photography"
    ],
    "subject": {
      "count": "1",
      "type": "female human",
      "identity": "fit young woman, Finnish ethnicity, long blonde hair, relaxed sleeping expression",
      "identity_preservation": {
        "description": "Natural sleeping posture, relaxed facial muscles, closed eyes",
        "notes": "Subject should look peacefully asleep, unaware of the doodles"
      },
      "age_appearance": "young adult / early 20s",
      "skin": "fair, natural texture, cool-toned lighting interaction",
      "clothing": {
        "top": "pink bikini top",
        "bottom": "pink bikini bottom",
        "full_description": "wearing a pink bikini",
        "accessories": "none (real), drawn accessories (scuba mask, tank, fins)"
      },
      "props": {
        "other": "white line drawings of scuba gear: diving mask over eyes, air tank on back, breathing regulator, large swim fins on feet"
      }
    },
    "pose_action": {
      "description": "Subject is sleeping on her side in a fetal-like position, legs slightly bent, hands curled near chest/face, perfectly positioned to align with the superimposed doodles",
      "overall_pose": "sleeping on side / side-lying",
      "head_turn": "profile resting on pillow",
      "body_position": "lying on side, diagonal composition across the bed",
      "hands": "relaxed, tucked near chin"
    },
    "environment": {
      "setting": "cozy bedroom bed viewed from above",
      "location": "indoor bedroom/dream world",
      "weather": "indoor controlled / imaginary underwater",
      "time_of_day": "night/sleep time",
      "atmosphere": "dreamy, quiet, submerged feeling due to color palette"
    },
    "background": {
      "color": "teal/aquamarine / cool blue sheets",
      "effect": "wrinkled fabric texture serving as the canvas for the white doodles"
    },
    "lighting": {
      "type": "soft ambient moonlight / cool overhead fill",
      "position": "overhead diffused",
      "direction": "soft top-down",
      "intensity": "moderate, creating soft dimensional shadows on the bedsheets",
      "tone": "cool blue/cyanotic/nocturnal",
      "mood": "peaceful night",
      "subject_lighting": "soft cool highlighting on skin",
      "imperfections": ["fabric wrinkles", "natural shadows"]
    },
    "camera": {
      "sensor_format": "Digital Mirrorless / High-Res",
      "lens": "35mm or 50mm standard",
      "position_angle": "Directly Top-Down / 90-degree Bird's Eye View",
      "framing": "Wide enough to show the full bed or a significant portion of the mattress to allow space for the doodles",
      "composition": {
        "framing": "subject centered or slightly diagonal",
        "depth": "flat field focus (everything sharp, including bedsheets)",
        "emphasis": "interaction between the real sleeping figure and the drawn environment"
      }
    },
    "photobooth_collage_specific": {
      "layout": "N/A - Single Composite Image",
      "tonality_texture": "Smooth photographic texture for the background/subject, rough chalk/marker texture for the doodles"
    },
    "color_grading": {
      "palette": "Dominant hues of teal, cyan, and navy blue; pure white for the illustration elements; natural skin tones shifted cool",
      "mood": "Cinematic night / underwater simulation"
    },
    "post_processing": {
      "final_touch": "Superimpose distinct, scribbly white line art: 'hand-drawn' fish, bubbles, coral, seaweed surrounding the subject, and diving gear 'worn' by the subject."
    },
    "negative": {
      "style": "3D render of doodles, realistic props (the gear should be drawn, not real), warm lighting, sunlight, orange tones, complex bedding patterns",
      "content": "waking subject, standing, real scuba gear, messy room (other than bed)"
    },
    "additional_controls": {
      "focus_emphasis": "The contrast between the realistic sleeping human and the 2D white line art",
      "special_notes": "The doodles must look like they were drawn on the photo surface or the bedsheets, white outline style only. The doodles include: a school of fish, coral reefs at the bottom, bubbles rising, a starfish, and the scuba gear outfit.
      "vibe": "playful creativity",
      "final_output_goal": "A seamless blend of photo and sketch that tells a story of a diver's dream."
    }
  }
}
```

---

## Realistic photos with illustrated sticker overlays

![Realistic photos with illustrated sticker overlays](https://opennana.com/awesome-prompt-gallery/images/770.jpeg)

- **Model:** Nano banana pro
- **Source:** [@ShreyaYadav___](https://x.com/ShreyaYadav___/status/1996908146452025628)
- **Tags:** cartoon, character, fashion, illustration, interior, landscape, minimalist, nature, paper-craft, photography, vehicle

**Prompt:**

```
{
  "description": "Aesthetic cozy mirror selfie of a young woman sitting casually on a chair, wearing a dark oversized hoodie and blue jeans. She holds a professional camera in one hand while resting her face gently on the other with a soft, dreamy smile. The background is warm beige with soft studio lighting and a minimal modern interior. Cute cartoon-style doodles float around her, including a smiling sunflower character, a hand-drawn yellow sun, and playful white sketch lines around the camera. A handwritten romantic quote appears on the wall: 'Love feels a lot like… I saw this and thought of you!'. The overall style mixes photorealism with illustrated sticker overlays, creating a cozy, romantic Instagram aesthetic.",
  "style": {
    "tones": "soft warm tones, cozy romantic vibe",
    "lighting": "soft studio lighting, warm and diffused",
    "aesthetic": "Instagram aesthetic with cinematic depth of field",
    "texture": "natural skin texture, ultra-detailed"
  },
  "visual_elements": {
    "subject": {
      "gender": "female",
      "pose": "sitting casually on a chair, taking a mirror selfie",
      "clothing": "dark oversized hoodie and blue jeans",
      "expression": "soft dreamy smile"
    },
    "environment": {
      "background": "warm beige indoor setting, minimal modern interior",
      "lighting": "soft warm shadows"
    },
    "overlays": [
      "cute smiling sunflower doodle",
      "hand-drawn yellow sun",
      "white sketch lines around the camera",
      "handwritten romantic quote on the wall"
    ]
  },
  "quality": {
    "resolution": "4K ultra-detailed",
    "render": "photorealistic with illustrated sticker overlay"
  },
  "format": {
    "ratio": "3:4"
  }
}
```

---

## Young woman kneeling in field

![Young woman kneeling in field](https://opennana.com/awesome-prompt-gallery/images/779.jpeg)

- **Model:** Nano banana pro
- **Source:** [@IamEmily2050](https://x.com/IamEmily2050/status/1997809374136528952)
- **Tags:** cartoon, illustration, interior, landscape, nature, photography, portrait, vehicle

**Prompt:**

```
{
    "shot_type": "Medium Full Shot (kneeling)",
    "composition": "Central composition with low horizon line",
    "angle": "Eye-level to slightly low angle"
  },
  "subject": {
    "subject_type": "Human",
    "identity_summary": "A young woman with long, dark, windblown hair kneeling in a field.",
    "visual_signature": {
      "facial_signature": {
        "face_shape": "Defined jawline, prominent cheekbones, side profile view",
        "eye_details": "Closed, relaxed eyelids with dark lashes",
        "nose_details": "Straight, slightly upturned tip",
        "lip_details": "Natural shape, closed, relaxed mouth",
        "cheek_and_jaw": "Sculpted features highlighted by hard sunlight",
        "unique_features": "Serene expression, head tilted back slightly"
      },
      "body_signature": {
        "build": "Slender, fit physique",
        "proportions": "Natural",
        "skin_tone_and_texture": "Tanned, smooth skin, sun-kissed",
        "height_estimation_cm": 170
      }
    },
    "pose_and_action": {
      "description": "Kneeling on the ground, soaking up the sun and wind",
      "body_position": "Kneeling (seiza-style or similar), torso upright, back slightly arched, head tilted back and turned to the side towards the light source",
      "limb_positions": "Arms resting relaxed on thighs/lap, legs folded underneath",
      "hand_gestures": "Relaxed fingers resting on legs",
      "facial_expression": "Serene, peaceful, enjoying the moment, eyes closed"
    },
    "inventory": {
      "wardrobe": "Black mini dress with red polka dots, off-the-shoulder ruffled sleeves, sweetheart neckline",
      "accessories": "Thin gold chain necklace, rings on fingers",
      "held_objects": "None",
      "hair_style": "Long, dark brown/brunette, wavy texture, blowing dynamically in the wind towards the right"
    }
  },
  "environment": {
    "setting": "Wildflower field",
    "ground_elements": "Dense field of vibrant blue wildflowers (e.g., bluebells, cornflowers, nemophila), green grass visible near roots",
    "background_elements": "Rolling brown hills/mountains in the distance",
    "sky_condition": "Blue sky with wispy, streaky cirrus clouds",
    "weather": "Sunny, windy"
  },
  "lighting": {
    "type": "Natural hard sunlight",
    "direction": "Side lighting (from the left)",
    "quality": "High contrast, creating distinct shadows on the face and neck, illuminating the profile",
    "color_temperature": "Daylight balanced (approx 5500K)"
  },
  "camera": {
    "lens_focal_length": "50mm or 85mm (Portrait)",
    "aperture": "f/2.8 to f/4 (Subject sharp, background slightly softened)",
    "shutter_speed": "Fast (to freeze the hair motion)",
    "film_grain": "Fine grain, digital photography style"
  },
  "post_processing": {
    "color_grading": "Natural, cool tones in the shadows (blues) contrasted with warm highlights (skin), slight contrast boost",
    "contrast": "Medium-High",
    "saturation": "Natural to Vibrant"
  },
  "negative": {
    "artifact_suppression": "white dots, white polka dots, orange flowers, orange poppies, yellow flowers, open eyes, standing, straight hair, static hair, indoor, studio lighting, distorted hands, extra fingers, cartoon, illustration, sketch, low resolution, blurry face, different person",
    "conceptual_suppression": "sadness, rain, night, urban setting"
  }
}
```

---

## Selfie with 2D animation illustration

![Selfie with 2D animation illustration](https://opennana.com/awesome-prompt-gallery/images/783.jpeg)

- **Model:** Nano banana pro
- **Source:** [@_MehdiSharifi_](https://x.com/_MehdiSharifi_/status/1997824265215684761)
- **Tags:** 3d, character, fashion, illustration, interior, landscape, minimalist, nature, paper-craft, photography, portrait

**Prompt:**

```
{
  "image_request": {
    "goal": "Create a Gen Z anime-core streetwear mirror selfie blending [UPLOADED IMAGE] with 2D anime illustration elements",
    "meta": {
      "image_type": "Mixed Media Mirror Selfie / Anime-Core Fashion Editorial",
      "quality": "Best Quality, Ultra-Detailed, Mixed Reality, Smartphone Photography",
      "color_mode": "Full Color / Vibrant Accents",
      "style_mode": "raw_photoreal with 2D overlay",
      "aspect_ratio": "4:5",
      "resolution": "1080x1350"
    },
    "creative_style": "Playful Gen Z streetwear fashion mixed with 2D anime overlay, casual 'fit check' vibe, juxtaposition of cute styling with gothic anime horror elements, vibrant eclectic footwear, indoor mirror selfie aesthetic",
    "overall_theme": "anime culture/streetwear fashion / mixed reality / playful casual",
    "mood_vibe": "playful confident / otaku chic / quirky / casual cool",
    "style_keywords": [
      "mirror selfie",
      "streetwear",
      "anime overlay",
      "mixed media",
      "Gen Z fashion",
      "casual",
      "playful"
    ],
    "subject": {
      "count": "2 (1 human female [UPLOADED IMAGE] + 1 anime character overlay)",
      "type": "female / 2D character overlay",
      "identity": "[UPLOADED IMAGE]",
      "identity_preservation": {
        "description": "Strictly preserve facial features, hair, and body structure from [UPLOADED IMAGE]",
        "notes": "Use [UPLOADED IMAGE] as the reference for the main subject."
      },
      "age_appearance": "Derived from [UPLOADED IMAGE]",
      "skin": "Derived from [UPLOADED IMAGE]",
      "makeup": {
        "lips": "Derived from [UPLOADED IMAGE]",
        "eyes": "Derived from [UPLOADED IMAGE]",
        "general": "Derived from [UPLOADED IMAGE]."
      },
      "facial_features": {
        "expression": "Derived from [UPLOADED IMAGE]",
        "eyes": {
          "gaze": "Derived from [UPLOADED IMAGE]",
          "intensity": "Derived from [UPLOADED IMAGE]"
        },
        "lips": {
          "gesture": "Derived from [UPLOADED IMAGE]"
        }
      },
      "hair": {
        "length": "Derived from [UPLOADED IMAGE]",
        "texture": "Derived from [UPLOADED IMAGE]",
        "style": "Derived from [UPLOADED IMAGE]",
        "lighting_interaction": {
          "light": "soft indoor overhead reflection",
          "shadow_play": "minimal"
        }
      },
      "clothing": {
        "top": "oversized beige knit sweater with distressed hem, featuring large black-and-white manga girl portrait graphic and smiley face print (OR retain clothing from [UPLOADED IMAGE] if preferred)",
        "bottom": "sheer black thigh-high stockings (OR retain clothing from [UPLOADED IMAGE])",
        "full_description": "Subject from [UPLOADED IMAGE] styled in Gen Z anime-core fashion",
        "accessories": "layered pearl and chain necklaces, rings, quirky phone case with text stickers"
      },
      "props": {
        "bouquet": "N/A",
        "wine_glass": "N/A",
        "other": "Smartphone with sticker-covered case held in both hands"
      }
    },
    "pose_action": {
      "description": "Standing full-body mirror selfie matching [UPLOADED IMAGE]",
      "overall_pose": "Derived from [UPLOADED IMAGE]",
      "head_turn": "Derived from [UPLOADED IMAGE]",
      "gaze": "Derived from [UPLOADED IMAGE]",
      "body_position": "Derived from [UPLOADED IMAGE]",
      "hands": "holding smartphone at chest level to take a photo",
      "movement": "static pose"
    },
    "multiple_frames_expressions": [],
    "environment": {
      "setting": "Indoor hallway or hotel room entrance",
      "location": "in front of full-length mirror",
      "weather": "N/A (indoor)",
      "time_of_day": "indoor artificial light",
      "atmosphere": "casual/domestic/playful"
    },
    "background": {
      "color": "neutral tones/wood door / white walls",
      "effect": "standard depth of field, clear background with looming anime figure overlay"
    },
    "lighting": {
      "type": "Indoor overhead lighting",
      "position": "overhead",
      "direction": "top-down",
      "intensity": "moderate / even",
      "focus": "on [UPLOADED IMAGE] subject",
      "falloff": "gradual",
      "light_quality": "diffused artificial",
      "source": "ceiling fixture",
      "tone": "neutral to slightly warm",
      "mood": "casual daily life",
      "subject_lighting": "even illumination on [UPLOADED IMAGE]",
      "environment_lighting": "ambient indoor",
      "color_temperature": "3500K-4000K",
      "contrast_shadow": "soft shadows behind subject",
      "shadow_quality": "diffused",
      "imperfections": ["smartphone reflection", "indoor lighting glare"]
    },
    "camera": {
      "sensor_format": "Smartphone Camera",
      "lens": "Wide angle main lens (approx 24-26mm eq)",
      "position_angle": "eye-level (reflection)",
      "distance": "arm's length / approx 1.5 meters from mirror",
      "framing": "full body portrait 9:16",
      "depth_of_field": "deep (everything mostly in focus)",
      "composition": {
        "framing": "[UPLOADED IMAGE] centered, mirror frame visible on edges",
        "depth": "flat layering of 2D character behind 3D [UPLOADED IMAGE] subject",
        "emphasis": "outfit details and the juxtaposition of the anime character",
        "angle": "straight on"
      }
    },
    "photobooth_collage_specific": {
      "frame_count_per_strip": "N/A",
      "total_prints": "N/A",
      "layout": "N/A",
      "border": "N/A",
      "tonality_texture": "N/A",
      "highlight_behavior": "N/A"
    },
    "color_grading": {
      "palette": "Beige, Black, Yellow, Red, White",
      "lut": "Standard Smartphone / True to Life",
      "mood": "casual vivid"
    },
    "post_processing": {
      "sharpening": "standard",
      "final_touch": "Composite overlay of large 2D anime 'Shinigami' (death god) character looming behind [UPLOADED IMAGE]—spiky blue/black hair, skeletal face, yellow eyes, dark feathery wings/shoulders (Ryuk style)."
    },
    "negative": {
      "style": "blurry, low res, painting, 3D render of girl (girl must be photoreal), distorted hands",
      "content": "cluttered background, bad lighting, cropped feet",
      "artifacts": "warped phone, extra fingers"
    },
    "additional_controls": {
      "focus_emphasis": "The [UPLOADED IMAGE] subject and the anime character overlay",
      "grounding": "feet firmly planted",
      "special_notes": "The image features a distinct 'mixed reality' style where a 2D anime illustration is superimposed behind [UPLOADED IMAGE] in a mirror selfie.",
      "vibe": "playful anime fan",
      "final_output_goal": "A realistic mirror selfie of [UPLOADED IMAGE] with a convincing 2D anime character integration."
    }
  }
}
```

---

## Transform subjects into clay-style 3D characters

![Transform subjects into clay-style 3D characters](https://opennana.com/awesome-prompt-gallery/images/784.jpeg)

- **Model:** Nano banana pro
- **Source:** [@gizakdag](https://x.com/gizakdag/status/1997602898075615682)
- **Tags:** cartoon, character, clay, illustration, photography, sculpture, vehicle

**Prompt:**

```
Transform the subject into a stylized 3D character with soft clay-like materials, rounded sculptural forms, exaggerated facial features, pastel + vibrant color palette, smooth subsurface scattering skin, large cartoon eyes, simplified anatomy. Render against a bold blue studio background with soft frontal lighting and subtle shadows. Playful, surreal, polished character-design aesthetic similar to modern stylized 3D illustration. Keep the original photo’s composition and framing.
```

---

## Generate a nine-square grid of characters in different poses

![Generate a nine-square grid of characters in different poses](https://opennana.com/awesome-prompt-gallery/images/785.jpeg)

- **Model:** Nano banana pro
- **Source:** [@qisi_ai](https://x.com/qisi_ai/status/1997553039474143501)
- **Tags:** character, fashion, illustration, landscape, logo, nature, portrait

**Prompt:**

```
At the location of "Tokyo Tower", create pictures based on the local current time atmosphere and real-time weather. Let the designated character tour the location so that he or she becomes part of the scene.  

Generate screen:
Generate a picture with a vertical 3:4 ratio. The single picture has a fixed nine-square grid layout, three rows and three columns, and each grid is an independent lens.

Camera and perspective:
– Use a super wide-angle or fisheye lens (approximately equivalent to a full-frame 12–18mm look and feel)
– The camera angle must change significantly from the original image. Exaggerated camera positions that can be used include:
• Looking up from directly below
• A bird's-eye view looking down from directly above
• Ultra-low aircraft position close to the ground
• High camera position from top to bottom
• Oblique “Dutch angle” composition
– Always creates a strong foreshortening effect: the part of the body closest to the camera appears huge, and the rest of the body extends far away in perspective
– The final effect must be like a bold fashion or street photo, completely realistic, not illustrative or 2D style

Body parts close to camera (1–2, sometimes 3):
– In each edited image, choose one or two main body parts that are extremely close to the camera (in more complex poses, sometimes it can be three)
– Vary these areas from image to image, don’t always stay in the same place near the camera
– Parts of the body that can be brought close to the camera include:
• One or both hands/fingers extended toward the camera
• One or both feet/shoes/boots close to camera
• Knee or thigh
• Face very close to camera
• Shoulder or chest close to camera in forward lean pose
– The selected body part should be extremely close to the camera, almost touching it, so that skin texture, cloth texture and realistic wide-angle distortion can be clearly seen

Posture and overall body (complex and varied):
– Create strong, cool, dynamic poses that match extreme viewing angles
– Randomly use different types of gestures, including:
• Standing with one leg or hand extended toward the camera
• Squat or half-squat close to the floor
• Sitting on the ground or on an object
• Lie flat on the ground with your legs or feet facing the camera
• Lean your body sharply forward towards the camera
• Twist your torso, cross your legs, or arch your back to create a more dynamic body line
– Allows the use of complex gestures such as:
• Both hands are close to the camera, making gestures (biy, triangle, framing with fingers, pointing at the viewer, etc.)
• Both feet facing the camera
• A hand and a foot simultaneously serve as large elements in the foreground
• The face is close to the camera and the hands or feet appear in perspective
– Maintain a reasonable and believable human anatomy even under extreme foreshortening

Camera position and attitude (randomized):
– Randomly change the camera angle and direction (up, down, sideways, tilted composition) while maintaining a visually balanced and impactful composition.
– Keep your temperament cool, calm, and confident, preferring fashion blockbusters or street style, based on the original outfit temperament
– Facial expressions can vary (serious, playful, confident, mysterious, etc.) but must always look like the same person

Light and picture rendering:
– Maintain realistic shadows and contact with the ground/floor
– High resolution and clear details, skin texture, cloth texture and material highlights can be seen

Variation and randomness:
– Each thumbnail should be clearly different from other thumbnails, maintaining variety in the following aspects:
• Camera angle
• Posture type
• Which body parts are closest to the camera
• Composition direction (forward, tilted, looking down, looking up, etc.)
– Avoid repeating the same “one foot close to the camera” composition over and over again, and instead present a variety of dynamic postures and camera position changes

Strict rules:
– Don’t replace the character with someone else
– Do not change the type of clothing; only change the expression through posture, perspective and the natural movement of the clothing
– Do not move the scene to a location other than the specified latitude and longitude; always stay within a reasonable extension of the specified latitude and longitude location
– Do not add text, logos, watermarks or graphic design elements
– Do not change to an oil painting, illustration or anime style; must maintain photorealism
```

---

## A fascinating picture of time in four seasons

![A fascinating picture of time in four seasons](https://opennana.com/awesome-prompt-gallery/images/788.jpeg)

- **Model:** Nano banana pro
- **Source:** [@dotey](https://x.com/dotey/status/1997787952110239874)
- **Tags:** illustration, landscape, nature

**Prompt:**

```
Hyper-realistic digital illustration of {Scene}, presented as a single continuous composition showcasing the cycle of seasons. The scene flows seamlessly from left to right in a natural progression: Winter, Spring, Summer, and Autumn. 

The left side features cold snowy winter elements, gradually thawing into the fresh green buds and blooms of spring, then morphing into the lush vibrant vegetation and bright sunlight of summer, and finally transitioning into the golden, orange, and red hues of autumn on the far right. 

There are no visible dividing lines between seasons; the weather, lighting, and vegetation blend smoothly to create a unified and harmonious panorama. Rich in detail, symbolic of the passage of time, cinematic lighting, 8k resolution, highly detailed textures. --ar 4:3
```

---

## High fashion photos shot with ultra-wide angle

![High fashion photos shot with ultra-wide angle](https://opennana.com/awesome-prompt-gallery/images/807.jpeg)

- **Model:** Nano banana pro
- **Source:** [@IamEmily2050](https://x.com/IamEmily2050/status/1997986646655185245)
- **Tags:** 3d, cartoon, character, fashion, food, illustration, landscape, minimalist, nature, neon, photography, portrait, product, vehicle

**Prompt:**

```
{
  "meta_control": {
    "generation_mode": "multi_panel_consistent",
    "priority_stack": ["identity_lock", "perspective_physics", "material_fidelity", "environmental_coherence"],
    "quality_target": "editorial_print_ready"
  },
  "intent": {
    "primary": "High-fashion streetwear editorial with extreme wide-angle perspective study",
    "secondary": "Technical demonstration of foreshortening and forced perspective",
    "publication_context": "Double-page spread, fashion magazine collage layout"
  },
  "frame": {
    "aspect_ratio": "3:4",
    "layout": {
      "type": "2x2 grid collage",
      "gutter_width": "2px white or seamless",
      "panel_uniformity": "identical dimensions per panel"
    }
  },
  "subject": {
    "type": "Human female fashion model",
    "identity_lock": {
      "enforcement_level": "strict",
      "anchor_features": ["face_geometry", "skin_tone", "body_proportions", "hair_style"]
    },
    "biometrics": {
      "age_presentation": "22-26",
      "height_cm": 175,
      "build": "Slender athletic, model proportions",
      "ethnicity_presentation": "Northern European features"
    },
    "facial_signature": {
      "structure": "Angular diamond face, high cheekbones, defined jawline",
      "eyes": "Sharp almond, steel grey, graphic black winged liner extending 8mm",
      "nose": "Refined, straight, small silver hoop piercing on left nostril",
      "lips": "Natural shape, matte nude-pink",
      "skin": "Fair, visible pores and natural texture, subtle peach fuzz, tiny freckle cluster left cheekbone",
      "expression_default": "Cool confidence, intense direct eye contact, composed"
    },
    "hair": {
      "style": "Platinum blonde straight bob, blunt bangs ending at eyebrows",
      "texture": "Silky, light-catching, individual strand definition",
      "behavior": "Natural movement responding to pose changes"
    },
    "wardrobe": {
      "jacket": {
        "item": "Oversized bomber jacket",
        "material": "Ripstop nylon, high gloss",
        "color": "Neon orange (vivid, saturated)",
        "state": "Unzipped, hanging open",
        "light_behavior": "Sharp specular highlights, visible weave texture"
      },
      "top": {
        "item": "Crop top",
        "material": "Black synthetic mesh, diamond pattern",
        "fit": "Tight, stretched across torso",
        "transparency": "Semi-sheer, skin visible through weave"
      },
      "pants": {
        "item": "Tactical cargo pants",
        "material": "Heavy cotton twill, matte",
        "color": "Charcoal grey",
        "details": "Multiple pockets, silver buckles, black nylon straps, baggy fit"
      },
      "footwear": {
        "item": "Platform sneakers",
        "color": "White, chunky sole",
        "condition": "Clean but worn, realistic sole texture"
      }
    },
    "accessories": {
      "neck": "Layered heavy silver Cuban link chains, 3 chains varying thickness",
      "hands": "Silver rings on index and middle fingers both hands"
    }
  },
  "panels": [
    {
      "id": 1,
      "position": "top-left",
      "concept": "Extreme low-angle sneaker perspective",
      "camera": {
        "height_cm": 10,
        "distance_cm": 35,
        "angle": "Looking up at 75 degrees"
      },
      "composition": {
        "foreground_dominant": "Right sneaker sole filling 40% of frame, laces in sharp focus",
        "midground": "Legs receding upward",
        "background": "Torso and face small in upper frame, looking down at camera"
      },
      "subject_pose": "Standing, weight back, right foot extended toward lens",
      "expression": "Looking down, slight smirk"
    },
    {
      "id": 2,
      "position": "top-right",
      "concept": "Bird's-eye reaching hand",
      "camera": {
        "height_cm": 200,
        "distance_cm": 60,
        "angle": "Looking straight down"
      },
      "composition": {
        "foreground_dominant": "Hand reaching up, fingers spread, appearing oversized",
        "midground": "Face looking up",
        "background": "Body compressed, pavement visible around edges"
      },
      "subject_pose": "Deep squat, one arm reaching directly up to camera",
      "expression": "Intense upward eye contact, serious"
    },
    {
      "id": 3,
      "position": "bottom-left",
      "concept": "Fisheye face extreme close-up",
      "camera": {
        "height_cm": 150,
        "distance_cm": 20,
        "angle": "Dutch tilt 20 degrees"
      },
      "composition": {
        "foreground_dominant": "Face filling 70% of frame, nose and eyes enlarged by proximity",
        "background": "Environment warping and curving at edges, slight motion blur"
      },
      "subject_pose": "Leaning face toward camera, shoulders back",
      "expression": "Piercing eye contact, one eyebrow slightly raised, confident"
    },
    {
      "id": 4,
      "position": "bottom-right",
      "concept": "Seated knee-forward perspective",
      "camera": {
        "height_cm": 40,
        "distance_cm": 50,
        "angle": "Slight upward looking"
      },
      "composition": {
        "foreground_dominant": "Knees and shins large in frame, cargo pant texture detailed",
        "midground": "Torso leaning forward",
        "background": "Face in upper third, hands resting on knees"
      },
      "subject_pose": "Seated on pavement, knees up, leaning toward camera",
      "expression": "Relaxed confidence, soft direct gaze"
    }
  ],
  "environment": {
    "location_type": "Urban industrial alleyway",
    "surfaces": {
      "ground": "Weathered concrete pavement, cracks, texture, subtle debris",
      "walls": "Concrete and brick, metallic rolling security doors, faded graffiti tags"
    },
    "atmosphere": "Gritty urban, authentic street context",
    "consistency_rule": "Identical environment visible across all four panels"
  },
  "lighting": {
    "source": "Natural afternoon sunlight",
    "quality": "Hard directional light",
    "direction": "High side-light, approximately 45 degrees from left",
    "shadow_character": "Sharp-edged, deep shadows",
    "color_temperature_kelvin": 5500,
    "fill": "Minimal, ambient bounce from pavement only",
    "specular_behavior": "Strong highlights on nylon jacket, chain jewelry, sneaker rubber"
  },
  "camera_global": {
    "lens": "Ultra-wide rectilinear, 12-14mm equivalent",
    "aperture": "f/8",
    "depth_of_field": "Deep, foreground to background sharp",
    "distortion": "Barrel distortion, edge stretching, exaggerated foreshortening",
    "sensor": "Full-frame, high resolution"
  },
  "post_processing": {
    "color_grade": {
      "contrast": "High",
      "saturation_subject": "Vivid, especially neon orange jacket",
      "saturation_background": "Slightly desaturated, muted",
      "blacks": "Deep, crushed slightly",
      "highlights": "Preserved, not blown"
    },
    "texture": "8K resolution equivalent, visible skin texture, fabric weave, material detail",
    "film_treatment": "Subtle RAW photo grain, not excessive"
  },
  "negative_constraints": {
    "style_rejection": ["illustration", "anime", "cartoon", "painting", "drawing", "3d render", "CGI", "digital art", "AI art look", "smooth skin filter", "beauty filter"],
    "anatomical_rejection": ["extra fingers", "missing fingers", "fused fingers", "extra limbs", "anatomical errors", "broken joints", "impossible body positions"],
    "consistency_rejection": ["face change between panels", "different person", "clothing change", "hair color change", "inconsistent skin tone", "different lighting between panels"],
    "technical_rejection": ["blur", "low resolution", "jpeg artifacts", "noise", "watermark", "text", "logo", "signature"],
    "lens_rejection": ["telephoto compression", "portrait lens look", "85mm aesthetic", "no foreshortening", "flat perspective"]
  }
}
```

---

## Retro blueprint illustration

![Retro blueprint illustration](https://opennana.com/awesome-prompt-gallery/images/831.jpeg)

- **Model:** Nano banana pro
- **Source:** [@_MehdiSharifi_](https://x.com/_MehdiSharifi_/status/1999640304069279795)
- **Tags:** illustration, paper-craft, photography, retro

**Prompt:**

```
Create a highly detailed blueprint-style technical schematic based on the uploaded photo. Use clean, blue line art on a beige, aged engineering paper background.
```

---

## An exploded view of a dragon's anatomy

![An exploded view of a dragon's anatomy](https://opennana.com/awesome-prompt-gallery/images/833.jpeg)

- **Model:** Nano banana pro
- **Source:** [@LudovicCreator](https://x.com/LudovicCreator/status/1999464392258191511)
- **Tags:** fantasy, illustration, paper-craft, poster, typography

**Prompt:**

```
Create an exploded-view illustration of a dragon's anatomy, dissecting its wings, scales, fire-breathing glands, and skeletal structure into labeled components with connecting arrows. Each part is rendered in intricate detail, showing metallic iridescent scales, glowing ember veins, and crystalline bones. Set against a ancient parchment background with subtle smoke effects and warm torchlight shadows. Include educational annotations in elegant script font. Horizontal blueprint-style poster, fantasy realism, high-resolution, inspired by Leonardo da Vinci's sketches with a modern digital twist.
```

---

## Woman holding a big stuffed mouse

![Woman holding a big stuffed mouse](https://opennana.com/awesome-prompt-gallery/images/837.jpeg)

- **Model:** Nano banana pro
- **Source:** [@ZaraIrahh](https://x.com/ZaraIrahh/status/1999319777257619957)
- **Tags:** cartoon, illustration, interior, landscape, nature, photography, portrait, toy, vehicle

**Prompt:**

```
{
  "image_prompt": {
    "subject": {
      "face_preservation": true,
      "description": "A beautiful young woman kneeling inside a cartoon-style monochrome brown room. Her facial features must remain exactly the same as the reference image.",
      "appearance": {
        "hair": {
          "color": "dark brown",
          "style": "long, neatly flowing, slightly messy natural texture"
        },
        "clothing": {
          "top": "thick brown knitted sweater with visible fabric texture",
          "pants": "light brown cargo pants",
          "shoes": "white sneakers"
        }
      },
      "pose": {
        "body": "kneeling on the floor",
        "hands": "hugging a large crocheted plush mouse",
        "expression": "soft, calm, natural look"
      }
    },

    "props": {
      "main_plush": {
        "type": "large crocheted plush mouse",
        "colors": {
          "body": "brown",
          "belly": "cream",
          "ears_inner": "light brown"
        },
        "features": {
          "eyes": "large, expressive, cartoon-like",
          "expression": "cheerful and cute"
        }
      },
      "additional_plushies": "multiple smaller crocheted mouse plushies scattered on the floor, identical design in varying sizes"
    },

    "environment": {
      "style": "cartoon-style room with monochrome brown palette",
      "details": {
        "illustrations": [
          "doodle-style door",
          "simple window sketch",
          "vase outline",
          "circular ornaments on walls"
        ],
        "line_style": "black sketch lines, hand-drawn appearance",
        "color_scheme": "brown monochrome with soft tonal variations"
      },
      "lighting": "soft, warm, cozy interior lighting"
    },

    "photography": {
      "render_style": "hyper-realistic, non-animated, not cartoonized",
      "textures": "highly detailed crochet fabric texture, realistic knitted sweater fibers, smooth soft lighting",
      "quality": "ultra-high resolution"
    },

    "composition": {
      "focus": "woman hugging the large plush mouse",
      "secondary_elements": "smaller mouse plushies placed around her",
      "background_role": "stylized cartoon room enhancing cozy atmosphere"
    }
  }
```

---

## Take realistic selfies in front of the mirror in your bedroom

![Take realistic selfies in front of the mirror in your bedroom](https://opennana.com/awesome-prompt-gallery/images/838.jpeg)

- **Model:** Nano banana pro
- **Source:** [@YaseenK7212](https://x.com/YaseenK7212/status/1999348160926195949)
- **Tags:** 3d, cartoon, data-viz, fashion, illustration, interior, landscape, nature, photography, portrait, vehicle

**Prompt:**

```
{
  "generation_request": {
    "meta_data": {
      "task": "text_to_image_with_reference",
      "version": "2.0_structured"
    },
    "technical_constraints": {
      "output_format": {
        "aspect_ratio": "9:16",
        "orientation": "portrait"
      },
      "reference_image_compliance": {
        "enabled": true,
        "mode": "strict_visual_match",
        "instruction_text": "Picture should be same as reference uploaded."
      }
    },
    "creative_detailed_prompt": {
      "core_concept": "Realistic smartphone mirror selfie in a bedroom.",
      "subject_profile": {
        "demographics": {
          "gender": "female",
          "age_group": "young_adult"
        },
        "physical_appearance": {
          "hair_specs": {
            "color": "silver/grey ",
            "texture": "normal, voluminous",
            "style": "long beautiful looking hair falling over shoulders"
            "length": "long"
          },
          "skin_specs": {
            "tone": "pale",
            "distinctive_features": "visible natural freckles on face and chest"
          },
          "body_shape": "slender, fit physique",
          "face_specs": {
            "expression": "neutral",
            "gaze_direction": "soft gaze looking into mirror"
          }
        },
        "action": {
          "pose": "standing facing mirror",
          "activity": "holding smartphone to take photo"
        },
        "attire": {
          "vibe": "beachwear / lounge style",
          "garments": {
            "top": {
              "type": "triangle bikini top",
              "color": "cream-colored",
              "details": "ruffled edges"
            },
            "bottom": {
              "type": "sheer sarong/wrap skirt",
              "color": "cream-colored matching top",
              "details": "tied at hip with ruffles"
            }
          }
        }
      },
      "scene_environment": {
        "location_type": "bedroom interior",
        "atmosphere_mood": "soft domestic",
        "key_props": [
          "unmade bed (messy white sheets and pillows)",
          "wooden headboard",
          "mirror frame (visible on side)"
        ],
        "lighting_setup": {
          "primary_source": {
            "type": "natural daylight",
            "origin": "window behind subject with sheer curtains"
          },
          "accent_source": {
            "type": "LED ambient light strip",
            "color": "purple",
            "intensity": "subtle",
            "location": "on wall"
          }
        }
      },
      "photography_specs": {
        "camera_type": "smartphone",
        "shot_category": "mirror reflection selfie",
        "aesthetic_genre": ["amateur photography", "influencer aesthetic", "candid"],
        "technical_quality": {
          "resolution_target": "8K",
          "focus_priority": "sharp on subject",
          "rendering_style": "photorealistic",
          "texture_emphasis": "natural skin"
        }
      }
    },
    "negative_constraints_list": [
      "makeup",
      "heavy photoshop",
      "smooth skin",
      "cartoon",
      "illustration",
      "anime",
      "3d render",
      "distorted hands",
      "bad anatomy",
      "missing fingers",
      "extra limbs",
      "blurry",
      "low quality",
      "dark room"
    ]
  }
}
```

---

## Exaggerated perspective illustration style

![Exaggerated perspective illustration style](https://opennana.com/awesome-prompt-gallery/images/846.jpeg)

- **Model:** Nano banana pro
- **Source:** [@Cydiar404](https://x.com/Cydiar404/status/1999342146479096205)
- **Tags:** character, illustration, landscape, minimalist, typography

**Prompt:**

```
Professional flat vector illustration in modern commercial style, depicting [SCENE_DESCRIPTION].

PERSPECTIVE & COMPOSITION:
- Extreme [ANGLE_TYPE] perspective from [STARTING_POINT] looking [VIEWING_DIRECTION] along ONE SINGLE [EXTENDING_OBJECT] toward [END_POINT]
- [EXTENSION_DIRECTION_LAYOUT]
- Single unified viewpoint with continuous depth progression following the SAME [EXTENDING_OBJECT] from [FRONT_END] to [BACK_END]
- Dynamic [COMPOSITION_DIRECTION] composition with exaggerated perspective showing ONE continuous [EXTENDING_OBJECT] extending through entire frame creating sense of [MOTION_CHARACTERISTIC]
- Seamless visual flow showing ONE SINGLE UNIFIED [EXTENDING_OBJECT]: [EXTENSION_DIRECTION_DESCRIPTION] - ALL PARTS OF THE SAME ONE [EXTENDING_OBJECT], NOT separate or duplicate [EXTENDING_OBJECT]
- Smooth depth of field with natural foreground-to-background transition along the length of this SINGLE continuous [EXTENDING_OBJECT]
- Clear visual leading lines following ONE [EXTENDING_OBJECT] creating strong unified depth within unified space
- Balanced negative space with [SPATIAL_EMPHASIS_DIRECTION] emphasis suggesting [ACTION_CHARACTERISTIC]
- Rule of thirds composition with emphasis on [CORE_FOCUS]
- NO duplicate elements, NO multiple [EXTENDING_OBJECT], NO repeated objects - only ONE [EXTENDING_OBJECT], ONE [RELATED_OBJECT], ONE [MAIN_CHARACTER]

COLOR PALETTE:
- [COLOR_TONE_DESCRIPTION] color scheme with [PRIMARY_COLOR_1_AND_APPLICATION], [PRIMARY_COLOR_2_AND_APPLICATION], [PRIMARY_COLOR_3_AND_APPLICATION], [SECONDARY_COLOR_1_AND_APPLICATION], [SECONDARY_COLOR_2_AND_APPLICATION], [ACCENT_COLOR_AND_APPLICATION]
- [SATURATION_CHARACTERISTIC] colors [COLOR_EMOTION_DESCRIPTION]
- [COLOR_STYLE_POSITIONING] color harmony [APPLICATION_SCENARIO_DESCRIPTION]

STYLE & TECHNIQUE:
- Clean 2D flat vector illustration with minimalist approach
- Simplified geometric character design and [ENVIRONMENT_ELEMENTS]
- Crisp linework without heavy outlines
- Flat color blocking with minimal gradients
- Smooth depth transitions without layering artifacts showing ONE continuous [EXTENDING_OBJECT]
- [SPECIAL_VISUAL_EFFECTS] integrated naturally
- Strong perspective distortion on SINGLE [EXTENDING_OBJECT] length from foreground to background
- Modern commercial illustration aesthetic similar to [REFERENCE_APPLICATION_SCENARIO]

KEY ELEMENTS:
- Complete [CHARACTER_TYPE] character in [CORE_ACTION_DESCRIPTION] in background [ACTION_DETAILS]
- ONE SINGLE [EXTENDING_OBJECT] only: [FRONT_END_DESCRIPTION] in foreground, [MIDDLE_SECTION_DESCRIPTION] extending continuously through midground with dramatic foreshortening, [BACK_END_DESCRIPTION] in background
- [RELATED_OBJECT] at/near the [POSITION] in foreground
- Geometric [BACKGROUND_ENVIRONMENT] background with [ENVIRONMENT_DETAILS]
- [DYNAMIC_EFFECT_ELEMENTS] suggesting [ACTION_CHARACTERISTIC]
- Text "[SLOGAN_TEXT]" integrated along the [EXTENDING_OBJECT] trajectory with 3D perspective depth effect, bold modern typography
- ALL elements are singular and unified - no duplicates

MOOD & ATMOSPHERE:
- [EMOTION_KEYWORD_1] and [EMOTION_KEYWORD_2]
- Professional [FIELD_POSITIONING] quality [ATMOSPHERE_DESCRIPTION]
- [SPECIAL_MOMENT_DESCRIPTION]
- Dynamic EXTREME proportions emphasizing [EXAGGERATION_FOCUS]
- Clean, polished, ready-for-publication finish with [ENERGY_CHARACTERISTIC]

CRITICAL REQUIREMENTS:
- Show ONLY ONE [EXTENDING_OBJECT] total in entire image
- This single [EXTENDING_OBJECT] has [FRONT_END] in foreground, [MIDDLE_SECTION] in midground, [BACK_END] in background
- NOT multiple [EXTENDING_OBJECT], NOT duplicate [EXTENDING_OBJECT], NOT separate [EXTENDING_OBJECT] pieces
- ONE continuous unified [EXTENDING_OBJECT] object extending through perspective
- ONE [RELATED_OBJECT] only at the [FRONT_END]
- ONE [MAIN_CHARACTER] only in background
- Avoid any visual duplication or repetition of elements
- Each object appears exactly ONCE in the frame
- Perspective makes the SAME [EXTENDING_OBJECT] look different sizes but it is still ONE [EXTENDING_OBJECT]
- Maintain single continuous camera perspective throughout
- Create STRONG depth progression with dramatic perspective FORESHORTENING along [EXTENDING_OBJECT] axis
- All elements should feel part of one unified [ENVIRONMENT] environment
- Ensure seamless integration of foreground and background within same spatial context
```

---

## Beijing 7-day weather forecast-poster

![Beijing 7-day weather forecast-poster](https://opennana.com/awesome-prompt-gallery/images/875.jpeg)

- **Model:** Nano banana pro
- **Source:** [@songguoxiansen](https://x.com/songguoxiansen/status/1999287301600641188)
- **Tags:** futuristic, illustration, landscape, paper-craft, poster

**Prompt:**

```
Create a weather visualization poster for Beijing for the next 7 days (including today). Requirements: 1) Use unique visual symbols or scenes to represent daily weather (sunny/rainy/snowy/cloudy/haze); 2) Clearly display date, temperature, humidity, wind and other Chinese information; 3) The overall design style is [Ghibli animation/flat illustration/3D miniature/future technology]; 4) Use color and atmosphere to convey weather feelings; 5) The layout is clear and easy to read, suitable for mobile phone wallpapers; 6) Dressing suggestions or travel tips can be added. The combination of information design and art, vertical composition, suitable for social sharing.
```

---

## Convert photos into comics

![Convert photos into comics](https://opennana.com/awesome-prompt-gallery/images/915.jpeg)

- **Model:** Nano banana pro
- **Source:** [@ecommartinez](https://x.com/ecommartinez/status/2001689993778249952)
- **Tags:** character, illustration, nature

**Prompt:**

```
Crea una ilustración de cómic moderno usando mi imagen de referencia como personaje principal.
Estilo inspirado en los cómics de superhéroes contemporáneos y novelas gráficas cinematográficas.
El personaje mantiene los rasgos faciales exactos y su identidad de la foto de referencia, transformados en un estilo cómic estilizado con líneas limpias pero expresivas.
Añade contornos negros marcados, sombreado dinámico con tinta y colores de alto contraste.
Aplica efectos FX como energía brillante, chispas, estelas de movimiento, haces de luz y partículas sutiles para aumentar la acción y la intensidad.
Usa una pose de acción dinámica o una postura poderosa, con perspectiva exagerada y ángulos dramáticos.
El fondo debe ser gráfico y cinematográfico: formas urbanas abstractas, líneas de velocidad o explosiones de energía, sin distraer del personaje.
La iluminación es dramática, con luces y sombras fuertes para dar profundidad e impacto.
Estilo final: portada de cómic moderno de alta calidad, detalles nítidos, colores vibrantes, composición enérgica, ilustración profesional, impacto visual fuerte.
No cambies el rostro, solo estilízalo.
```

---

## High end studio portraits

![High end studio portraits](https://opennana.com/awesome-prompt-gallery/images/916.jpeg)

- **Model:** Nano banana pro
- **Source:** [@AIwithkhan](https://x.com/AIwithkhan/status/2001685648768680052)
- **Tags:** branding, illustration, minimalist, photography, portrait, poster

**Prompt:**

```
A high-end studio portrait using the uploaded photo as the main subject. The person stands confidently against a clean, minimal background in soft neutral tones, holding a large vertical poster in front of them. The poster features an artistic reinterpretation of the same uploaded photo — stylized as a digital illustration, sketch, or painterly artwork — clearly recognizable as the same face. Professional studio lighting with a soft key light and subtle rim light creates gentle shadows and depth. The subject’s expression is calm and confident, body posture relaxed yet strong, evoking a modern personal brand identity. Clean composition, balanced framing, premium editorial aesthetic, shallow depth of field, ultra-realistic skin texture, crisp details, contemporary creator branding vibe, cinematic realism, 1:1 aspect ratio, high resolution.
```

---

## Woman standing next to KAWS style art sculpture

![Woman standing next to KAWS style art sculpture](https://opennana.com/awesome-prompt-gallery/images/927.jpeg)

- **Model:** Grok
- **Source:** [@xmiiru_](https://x.com/xmiiru_/status/2002578056628601143)
- **Tags:** cartoon, fashion, illustration, interior, minimalist, photography, sculpture, vehicle

**Prompt:**

```
{
  "prompt": "Ultra realistic fashion editorial photography of a stylish young woman posing next to a gray KAWS-style art figure, One knee on the floor, one leg bent forward, body slightly angled, one arm resting casually on the statue’s head, the other hand on hip. Confident fierce expression, sharp gaze toward camera. Wearing a vibrant orange bucket hat with butterfly emblem, white fitted crop t-shirt with orange butterfly graphics, bright orange track pants with white piping, white sneakers Small orange shoulder bag, subtle tattoos visible, braided hair accents, minimal jewelry. Monochrome orange streetwear aesthetic. Minimalist indoor space with gray walls and clean floor. Soft diffused studio lighting, realistic skin texture, sharp focus, high fashion streetwear vibe, professional photography, ultra-detailed, 8K resolution. Don't change original face",
  "negative_prompt": "low quality, blur, bad anatomy, extra fingers, extra limbs, distorted pose, cartoon, anime, illustration",
  "parameters": {
    "aspect_ratio": "2:3",
    "version": "6",
    "style": "raw",
    "quality": 2
  }
}
```

---

## Woman holding a wooden picture frame of herself

![Woman holding a wooden picture frame of herself](https://opennana.com/awesome-prompt-gallery/images/928.jpeg)

- **Model:** Nano banana pro
- **Source:** [@AIwithSynthia](https://x.com/AIwithSynthia/status/2002578332496638452)
- **Tags:** fashion, illustration, minimalist, nature, paper-craft, photography, portrait

**Prompt:**

```
A stylish woman wearing a black fedora and white shirt stands against a soft neutral studio background, holding a wooden frame. Inside the frame is a photo watercolor portrait of herself, painted with loose brushstrokes, soft ink bleeds, and expressive splashes. The watercolor version tilts slightly, with vivid red lips and delicate facial details. Google Gemini Cinematic studio lighting, shallow depth of field, elegant editorial fashion aesthetic, fine art photography blended with watercolor illustration, ultra-high resolution, minimal composition, calm and sophisticated mood.
```

---

## Woman is stepping out of her mobile phone screen

![Woman is stepping out of her mobile phone screen](https://opennana.com/awesome-prompt-gallery/images/938.jpeg)

- **Model:** Nano banana pro
- **Source:** [@underwoodxie96](https://x.com/underwoodxie96/status/2002293540299420050)
- **Tags:** 3d, cartoon, fashion, illustration, landscape, nature, photography, pixel, ui, vehicle

**Prompt:**

```
{

"subject": {

"description": "A hyper-realistic optical illusion photograph. A young Caucasian woman appears to be stepping out of a smartphone screen held in a hand. The screen displays the camera interface, capturing her boots, while her real upper body extends out of the phone into reality.",

"mirror_rules": "Ensure the phone screen clearly shows the iOS Camera UI (shutter button, mode text). Handwritten annotations must be legible and not mirrored.",

"age": "20s",

"expression": {

"eyes": {

"look": "Alluring and playful",

"energy": "Confident, direct",

"direction": "Looking at the viewer"

},

"mouth": {

"position": "Blowing a kiss or pouting",

"energy": "Chic and charming"

},

"overall": "Lifelike, engaging interaction"

},

"face": {

"preserve_original": "false",

"makeup": "Natural glam, matte foundation, defined European features",

"features": "High nose bridge, double eyelids, defined jawline"

},

"hair": {

"color": "Dark brown",

"style": "Long, loose waves, voluminous",

"effect": "Realistic shine, wind-blown effect"

},

"body": {

"frame": "Petite but proportionally realistic",

"waist": "Defined",

"chest": "Covered by turtleneck",

"legs": "Visible INSIDE the phone screen interface wearing boots",

"skin": {

"visible_areas": "Face, hands",

"tone": "Fair Caucasian skin",

"texture": "Ultra-realistic skin texture, visible pores, natural imperfections",

"lighting_effect": "Soft daylight"

}

},

"pose": {

"position": "Torso and head emerging vertically from the phone, legs displayed on the screen",

"base": "Dynamic standing pose",

"overall": "Vibrant random poses make people feel full of vitality"

},

"clothing": {

"top": {

"effect": "Exquisite outfits, High-quality textile photography"

},

"bottom": {

"type": "Mini Skirt and Leather Boots",

"color": "Dark Gray (skirt), Brown (boots)",

"details": "Boots visible on the screen beneath the UI elements"

}

}

},

"accessories": {

"jewelry": "Gold rings on the photographer's hand (foreground)",

"device": "Smartphone with burgundy case. The screen is ACTIVE and DETAILED: it displays the IOS Camera App Interface (white circular shutter button at bottom, 'PHOTO' text).",

"prop": "On the phone screen: White handwritten-style text overlays with arrows pointing to the outfit elements (e.g., text 'suede jacket' with arrow, 'leather boots' with arrow)."

},

"photography": {

"camera_style": "DSLR photography, Macro lens for phone details",

"angle": "POV, High angle looking down at hand",

"shot_type": "Composite photography",

"aspect_ratio": "3:4",

"texture": "Sharp screen pixels, fingerprint smudges on screen, realistic fabric texture",

"lighting": "Overcast soft natural light",

"depth_of_field": "Background bench blurred (Bokeh), Phone screen UI and subject sharp"

},

"background": {

"setting": "Parisian Park in Autumn",

"wall_color": "Green bench, gray ground",

"elements": [

"Green park bench with text 'Le silence'",

"Autumn leaves"

],

"atmosphere": "Cinematic, realistic",

"lighting": "Natural ambient light"

},

"the_vibe": {

"energy": "Sophisticated, viral social media content",

"mood": "Fashion forward",

"aesthetic": "OOTD breakdown, creative edit",

"authenticity": "Photorealistic texture, not CGI",

"intimacy": "POV",

"story": "Fashion styling breakdown",

"caption_energy": "Styling brown suede & leather"

},

"constraints": {

"must_keep": [

"Caucasian ethnicity",

"Photorealistic skin",

"Camera UI elements on screen (shutter button)",

"Handwritten text annotations on screen",

"Pop-out effect"

],

"avoid": [

"Transparent phone screen",

"Blank screen",

"3D render style",

"Cartoon",

"Plastic skin"

]

},

"negative_prompt": [

"transparent screen",

"blank screen",

"glass phone",

"3d",

"render",

"cartoon",

"anime",

"plastic",

"drawing",

"illustration"

]

}
```

---

