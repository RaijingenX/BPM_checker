print("\t\t\t✨ Welcome to BPM Checker ✨\n")

age = int(input("\t\tEnter your age ➡️   "))

# Age Category
if 0 <= age <= 6:
    print("\t\tYou are Infant")
    print("\t\tYour BPM code is [i]\n")

elif 7 <= age <= 17:
    print("\t\tYou are Teenager")
    print("\t\tYour BPM code is [t]\n")

elif age >= 18:
    print("\t\tYou are Adult")
    print("\t\tYour BPM code is [a]\n")

else:
    print("\t\t❌ Invalid age!")
    exit()

cd = input("\t\tEnter your BPM code ➡️   ").lower()

# Adult
if cd == "a":
    bpm = int(input("\t\tEnter your BPM rate ➡️ "))

    if 60 <= bpm <= 100:
        print("\n\t\t🟢 Status : Healthy")

    elif 50 <= bpm <= 59 or 101 <= bpm <= 120:
        print("\n\t\t🟡 Status : Not Healthy")

    else:
        print("\n\t\t🔴 Status : Risky")

# Teenager
elif cd == "t":
    bpm = int(input("\t\tEnter your BPM rate ➡️   "))

    if 70 <= bpm <= 100:
        print("\n\t\t🟢 Status : Healthy")

    elif 60 <= bpm <= 69 or 101 <= bpm <= 110:
        print("\n\t\t🟡 Status : Not Healthy")

    else:
        print("\n\t\t🔴 Status : Risky")

# Infant
elif cd == "i":
    bpm = int(input("\t\tEnter your BPM rate ➡️ "))

    if 100 <= bpm <= 180:
        print("\n\t\t🟢 Status : Healthy")

    elif 90 <= bpm <= 99 or 181 <= bpm <= 190:
        print("\n\t\t🟡 Status : Not Healthy")

    else:
        print("\n\t\t🔴 Status : Risky")

else:
    print("\n\t\t❌ Invalid BPM code!")
