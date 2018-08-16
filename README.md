# Examen
#1
mnv<-c(11:30)
dim(mnv)<-c(4,5)
escuelas<-c("escuela1","escuela2","escuela3","escuela4","esuela5")
ciuda<-c("toluca","pachuca","gdl","mty")
tabla<-data.frame(ciudad=ciuda,mnv)
tabla[2,3]
tabla[3,5]
tabla[2,1]
#2
v1<-c(1:18)
mavas<-matrix(v1,ncol = 3)
mavas[3,3]
#3 completar el codigo
s<-matrix(1:9,nrow = 3)
s[,1]*s[,2]
#4
ac<-c("pequeño","largo","enorme")
b<-ac!="largo"
ac[b]
#5
facultad<-c("economia","ingenieria","arquitectura")
licenciatura<-c("actuaria","mecanica","diseño")
calificacion<-c(7.8,8.2,9.3)
typeof(facultad)
typeof(licenciatura)
typeof(calificacion)
fac<-facultad!="arquitectura"
licz<-licenciatura!="diseño"
calf<-calificacion!="9.3"
#6
nombres<-c("carlos","juan","raquel","paty")
edad<-c(32,35,43,25)
sit_conyugal<-c("casado","soltero","soltero","union libre")
segsocial<-c("imss","imss","issste","privado")
oficio<-c("contador","carpintero","profesor","diseñador")
tabla2<-data.frame(Nombre=nombres,Edad=edad,estado_civil=sit_conyugal,Ocupacion=oficio)
filter()
sum(tabla2[,2])
show(tabla2[])
