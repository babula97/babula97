api = "Bearer " + input("Введите токен: ")
r = requests.post("https://lichess.org/api/bot/account/upgrade", headers = {"Authorization" : api})
print(r.status_code, r.text)
