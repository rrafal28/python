# pythonimport tkinter as tk

def oblicz_kosmogram():
    # Tutaj umieść kod do obliczania kosmogramu na podstawie wprowadzonych danych
    pass

# Tworzenie okna głównego
root = tk.Tk()
root.title("Kalkulator Kosmogramu")

# Tworzenie etykiet i pól wprowadzania danych
label_date = tk.Label(root, text="Data urodzenia:")
label_date.pack()
entry_date = tk.Entry(root)
entry_date.pack()

label_time = tk.Label(root, text="Czas urodzenia:")
label_time.pack()
entry_time = tk.Entry(root)
entry_time.pack()

label_location = tk.Label(root, text="Miejsce urodzenia:")
label_location.pack()
entry_location = tk.Entry(root)
entry_location.pack()

# Tworzenie przycisku obliczenia kosmogramu
button = tk.Button(root, text="Oblicz kosmogram", command=oblicz_kosmogram)
button.pack()

# Uruchamianie pętli głównej
root.mainloop()
