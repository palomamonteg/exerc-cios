# exercícios
#Conversor de medidas

m = float (input("Digite o valor em metros: "))
cm = m*100
mm = m*1000
dm = m*10
dam = m*0.1
hm = m*0.01
km = m*0.001
print (f"A medida de {m}m em cm é: {cm}\nA medida de {m} em mm é: {mm}
\nA medida de {m}m em dm é: {dm}\nA medida de {m}m em dam é: {dam:.0}
\nA medida de {m}m em hm é: {hm:.0}\nA medida de {m}m em km é: {km:.0}.")
