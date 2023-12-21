# Commandes pour installer
npm init -y  
npm install -D tailwindcss  
npx tailwindcss init  
Dans tailwind config, ajouter dans content : ["./src/**/*.{html,js"]  
npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch  

## Propriété

# Color
text-red-200

# Font size
text-xs (xs sm base lg xl 2xl 3xl...)  
text-base/7 (la taille modifie l'espcement interligne)

# Font weight
text-thin (thin extralignt light normal medium semibold bold extrabold black)

# Padding
pt = padding top  
pl padding left  
pr padding right  
pb padding bottom  
py padding top and bottom  
px padding right and left  

