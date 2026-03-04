# plant-Species-Image-Classification



## Section A: Project Overview
What is this project? This project is an image classification model I built to help identify different types of plants just by looking at a photo. I trained the model to recognize the unique shapes, colors, and patterns of various species so it can tell them apart instantly.

Why did I build this? The goal was to create a tool that makes botany a bit easier for everyone. Whether you're a student or just someone who loves gardening, this model helps identify plants quickly without needing to flip through a textbook, making nature a little more accessible through technology.


## Section B: Plant Species Section
1. African Violet

Scientific Name: Saintpaulia ionantha

About this plant: Famous for its fuzzy, heart-shaped leaves and bright clusters of flowers. They are a favorite for indoor gardeners because they stay small and bloom beautifully.

Representative Image: <img width="626" height="626" alt="image" src="https://github.com/user-attachments/assets/905e04af-da8d-4142-9354-bc7122d6b3bb" />




2. Air Plant

Scientific Name: Tillandsia

About this plant: These unique plants don't need soil to grow! They absorb water and nutrients through their leaves, making them look like little green sea creatures living on air.

Representative Image: (Drag your image here)




3. Black Bat Flower

Scientific Name: Tacca chantrieri

About this plant: One of the most unusual flowers in the world, it features dark, almost black petals and long "whiskers" that give it the appearance of a bat in flight.

Representative Image: (Drag your image here)




4. Bleeding Heart

Scientific Name: Lamprocapnos spectabilis

About this plant: This plant is named for its stunning heart-shaped flowers that dangle from arching stems, looking exactly like tiny pink and white hearts.

Representative Image: (Drag your image here)




5. Caladium

Scientific Name: Caladium bicolor

About this plant: Known as "Angel Wings," these plants are loved for their large, paper-thin leaves that come in incredible combinations of pink, white, and green.

Representative Image: (Drag your image here)





6. Cockscomb

Scientific Name: Celosia cristata

About this plant: The flower heads on this plant are wavy and velvety, often looking like a bright red or orange brain or the comb of a rooster.

Representative Image: (Drag your image here)





7. Coleus

Scientific Name: Coleus scutellarioides

About this plant: These are all about the foliage! Their leaves feature vibrant, neon patterns of burgundy, lime green, and hot pink that look hand-painted.

Representative Image: (Drag your image here)






8. Copperleaf

Scientific Name: Acalypha wilkesiana

About this plant: This shrub stands out with its copper-colored, serrated leaves that turn brilliant shades of red and bronze in the sun.

Representative Image: (Drag your image here)





9. Fiddle Leaf Fig

Scientific Name: Ficus lyrata

About this plant: A very trendy indoor tree with large, waxy leaves shaped just like a violin or a fiddle. It's a bold statement plant for any room.

Representative Image: (Drag your image here)






10. Hydrangea

Scientific Name: Hydrangea macrophylla

About this plant: Famous for its massive, globe-shaped flower clusters that can actually change color from blue to pink depending on the soil's acidity.

Representative Image: (Drag your image here)






11. Jade Vine

Scientific Name: Strongylodon macrobotrys

About this plant: This rare tropical vine produces hanging clusters of claw-shaped flowers in a stunning, almost unnatural turquoise-green color.

Representative Image: (Drag your image here)





12. Japanese Blood Grass

Scientific Name: Imperata cylindrica 'Rubra'

About this plant: This ornamental grass starts out green at the bottom but turns a deep, fiery red toward the tips, making the garden look like it's glowing.

Representative Image: (Drag your image here)





13. Prayer Plant

Scientific Name: Maranta leuconeura

About this plant: This plant is "active"—its beautiful patterned leaves fold up together at night like hands in prayer, then open back up every morning.

Representative Image: (Drag your image here)





14. Purple Fountain Grass

Scientific Name: Cenchrus setaceus 'Rubrum'

About this plant: A graceful grass with burgundy foliage and soft, fuzzy flower spikes that sway in the wind like purple feathers.

Representative Image: (Drag your image here)





15. Silver Inch Plant

Scientific Name: Tradescantia zebrina

About this plant: This trailing plant has striking purple and green striped leaves that have a shimmering, silvery metallic finish in the light.

Representative Image: (Drag your image here)





16. Snake Plant

Scientific Name: Dracaena trifasciata

About this plant: Also called "Mother-in-law's tongue," these hardy plants have stiff, vertical leaves that are experts at cleaning the air in your home.

Representative Image: (Drag your image here)





17. Spathiphyllum (Peace Lily)

Scientific Name: Spathiphyllum

About this plant: A classic indoor plant with glossy green leaves and elegant white flowers that symbolize peace and purity.

Representative Image: (Drag your image here)





18. Strelitzia (Bird of Paradise)

Scientific Name: Strelitzia reginae

About this plant: This tropical beauty produces dramatic flowers that look exactly like the head of a brightly colored exotic bird.

Representative Image: (Drag your image here)






19. String of Pearls

Scientific Name: Curio rowleyanus

About this plant: A unique succulent with long, trailing stems covered in tiny green spheres that look just like a necklace of pearls.

Representative Image: (Drag your image here)





20. Swiss Cheese Plant

Scientific Name: Monstera deliciosa

About this plant: Famous for the natural holes and splits that develop in its large, heart-shaped leaves, making it look like a slice of Swiss cheese.

Representative Image: (Drag your image here)






## Step 4: Training the Model.


<img width="379" height="712" alt="image" src="https://github.com/user-attachments/assets/c79a7e4a-d58f-42a7-bc67-a30bdccc74b2" />


*I configured my model using 50 Epochs and a Batch Size of 16. Combined with a 0.001 Learning Rate, this setup ensured the training process stayed stable. It's a reliable middle ground that helps the model learn to distinguish between the different plant species accurately.

## Step 5: Model Evaluation.

<img width="409" height="800" alt="image" src="https://github.com/user-attachments/assets/ae1f6106-6f2e-4e9d-9e16-2e8299fd05f5" />
<img width="423" height="806" alt="image" src="https://github.com/user-attachments/assets/6a05fd5c-70a3-472f-a23e-e02b62ca7e56" />
<img width="421" height="812" alt="image" src="https://github.com/user-attachments/assets/92602d7c-8f7c-48c0-a949-575622a3dc60" />
<img width="430" height="821" alt="image" src="https://github.com/user-attachments/assets/fb4ad15c-be3c-4213-992b-ade3fd7f9f0a" />
<img width="415" height="701" alt="image" src="https://github.com/user-attachments/assets/67a6f369-817a-4d3d-ab90-3eaa7b8c9488" />

*My model performed great! The graphs show that it learned the plant features quickly and reached high accuracy levels. While Class 4 had a lower accuracy of 0.76, the rest of the species were mostly above 0.90. Overall, the evaluation proves the model is ready to identify different plants with high confidence.

## Step 6: Testing the Model

<img width="361" height="388" alt="image" src="https://github.com/user-attachments/assets/ea4c8357-0a4d-44be-a494-7f446cf8408d" />
<img width="362" height="493" alt="image" src="https://github.com/user-attachments/assets/0a536582-a3ba-4085-b615-8c2019888216" />
<img width="264" height="782" alt="image" src="https://github.com/user-attachments/assets/55a5fa47-23cc-4d75-a148-ed8b493c5db4" />
<img width="402" height="553" alt="image" src="https://github.com/user-attachments/assets/eea4c153-0156-4598-a47c-f150f20bc383" />
<img width="358" height="610" alt="image" src="https://github.com/user-attachments/assets/27fb0984-ed2c-4a89-b5d7-07c329b46995" />
<img width="382" height="638" alt="image" src="https://github.com/user-attachments/assets/73bf4d12-31ac-4f44-ba46-e298c614c18b" />
<img width="389" height="627" alt="image" src="https://github.com/user-attachments/assets/6547faba-9dd0-4201-8c71-c231e36d82f2" />
<img width="340" height="644" alt="image" src="https://github.com/user-attachments/assets/bfdc73e7-8ff6-4335-a3a6-be975bdecc6f" />
<img width="336" height="711" alt="image" src="https://github.com/user-attachments/assets/74919bc5-a21b-467f-be33-d834dea54232" />
<img width="443" height="756" alt="image" src="https://github.com/user-attachments/assets/70c82a69-f6bc-43ca-b9cf-079b583253cd" />

*I conducted 10 different tests using new images to verify the model's accuracy. The model performed exceptionally well, identifying classes like Class 1, Class 8, and Class 9 with 100% confidence. Most results were perfect, confirming that the training was successful and the model is ready for use.


## Step 7: Model Export and Storage

<img width="1280" height="622" alt="image" src="https://github.com/user-attachments/assets/fcd9e1d7-dc7b-4ab6-a48e-a3914c5b1605" />


"To conclude the project, I exported the final trained model and stored it in Google Drive as a zip file. This ensures the model is backed up and ready for future use or deployment".




