# projeto-simples
import random

def gerar_numero_aleatorio():
    return random.randint(1, 100)

if __name__ == "__main__":
    numero_aleatorio = gerar_numero_aleatorio()
    print("Número aleatório gerado:", numero_aleatorio)
