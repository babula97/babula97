api = "Bearer " + input("lip_w2qDvtvDwEwT90KycJw9")
r =requests.post("https://lichess.org/api/bot/account/upgrade", headers = {"Authorization" : api})
print(r.status_code, r.text) 
