# REBASE.md

## Limpieza de historial con Git Rebase

### 1. Creación de commits desordenados

Se creó el archivo `notas.md` y se realizaron varios commits con mensajes poco descriptivos:

```bash
echo "Alicante" >> notas.md
git add notas.md
git commit -m "Mis creaciones.md"

echo "Torrevieja" >> notas.md
git add notas.md
git commit -m "Arreglo mis notas.md"

echo "España" >> notas.md
git add notas.md
git commit -m "pais"
