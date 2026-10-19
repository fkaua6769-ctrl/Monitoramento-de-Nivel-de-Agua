from colorama import Fore, Style
Níveis = [
    "Nível 1: Muito baixo (crítico)",
    "Nível 2: Baixo",
    "Nível 3: Médio",
    "Nível 4: Alto",
    "Nível 5: Muito alto (alerta)"
]
def exibir_alerta(nivel):
    if nivel == 1:
        print(Fore.RED + Níveis[0])
    elif nivel == 2:
        print(Fore.YELLOW + Níveis[1])
    elif nivel == 3:
        print(Fore.GREEN + Níveis[2])
    elif nivel == 4:
        print(Fore.CYAN + Níveis[3])
    elif nivel == 5:
        print(Fore.BLUE + Níveis[4])
    print(Style.RESET_ALL)
print("Sistema de monitoramento")
exibir_alerta(1)
exibir_alerta(2)
exibir_alerta(3)
exibir_alerta(4)
exibir_alerta(5)