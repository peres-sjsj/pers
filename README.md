import tkinter as tk

# Função para cadastrar um cliente
def cadastrar_cliente():
    # Implemente a lógica para cadastrar um cliente aqui
    pass

# Função para conceder um empréstimo
def conceder_emprestimo():
    # Implemente a lógica para conceder um empréstimo aqui
    pass

# Criar janela principal
root = tk.Tk()
root.title("Sistema de Empréstimo")

# Botões para cadastrar cliente e conceder empréstimo
btn_cadastrar_cliente = tk.Button(root, text="Cadastrar Cliente", command=cadastrar_cliente)
btn_cadastrar_cliente.pack()

btn_conceder_emprestimo = tk.Button(root, text="Conceder Empréstimo", command=conceder_emprestimo)
btn_conceder_emprestimo.pack()

# Executar o loop principal da janela
root.mainloop()

