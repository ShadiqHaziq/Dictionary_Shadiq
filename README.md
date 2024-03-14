meme_dict = {
            "SUS": "Sesuatu yang sangat aneh atau mencurigakan",
            "HELLO": "Tanggapan umum terhadap sesuatu yang bersapa",
            "BRO": "Tanggapan umum terhadap keluarga, abang",
            }

word = input("Ketik kata yang tidak Kamu mengerti (gunakan huruf kapital semua!):")

if word in meme_dict.keys():
    print("makna kata",word,"adalah",meme_dict[word])
else:
    print("makna kata tidak di temukan")
