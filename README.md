- 👋 Hi, I’m @RigobertoDavid
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
RigobertoDavid/RigobertoDavid is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
# Pedir al usuario que ingrese el número de ticket
numero_ticket = int(input("Ingrese el número de ticket: "))

# Validar si el ticket está dentro del rango válido (100-750)
if 100 <= numero_ticket <= 750:
    print("El ticket es válido.")

    # Determinar si el ticket es para cancha o galería
    if numero_ticket % 2 == 0:
        print("El ticket es para Cancha.")
    else:
        print("El ticket es para Galería.")

else:
    print("El ticket no es válido.")
