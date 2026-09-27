# Ejemplo 4: entorno con requests (consultar una API pública)

Consulta la cotización del euro frente al dólar en una API pública. Este entorno solo instala `requests`: no necesita pandas ni matplotlib, igual que los otros ejemplos no necesitan `requests`. Cada entorno instala únicamente lo que su proyecto usa. Requiere conexión a internet.

## Cómo ejecutarlo (Windows, PowerShell en VS Code)

```powershell
python -m venv venv
venv\Scripts\Activate.ps1
pip install -r requirements.txt
python main.py
```

En macOS/Linux: `python3 -m venv venv`, `source venv/bin/activate`.

En VS Code: `Ctrl+Shift+P` → **Python: Select Interpreter** → elegir `.\venv\Scripts\python.exe`.

## Resultado

```
1.14
```
(el valor exacto cambia cada día, según la cotización del euro frente al dólar)
