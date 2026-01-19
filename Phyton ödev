kahve_sube = [ ]
kahve_turleri = [ ]

kahve_turleri = [
    "Tea Latte",
    "Espresso",
    "Americano",
    "Filtre Kahve",
    "Türk Kahvesi",
    "Cappuccino"
]

subeler = [
    "Üsküdar",
    "Bebek",
    "Erenköy",
    "Etiler",
    "Bakırköy",
    "Kağıthane",
    "Mecidiyeköy"
]

stoklar = {}

for sube in subeler:
    print(f"\n{sube} şubesi stok girişleri")
    stoklar[sube] = []

    for kahve in kahve_turleri:
        adet = int(input(f"{kahve} stok miktarı: "))
        stoklar[sube].append(adet)

print("\n--- STOK LİSTESİ ---")

for sube, stok_listesi in stoklar.items():
    print(f"\n{sube} Şubesi")
    for kahve, stok in zip(kahve_turleri, stok_listesi):
        print(f"{kahve}: {stok}")

print("\n--- STOKLARA GÖRE SIRALI ---")

for sube, stok_listesi in stoklar.items():
    print(f"\n{sube} Şubesi")
    sirali = sorted(zip(kahve_turleri, stok_listesi), key=lambda x: x[1], reverse=True)
    for kahve, stok in sirali:
        print(f"{kahve}: {stok}")
