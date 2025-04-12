#compras 

usuario_1={'sofa', 'mesa', 'silla', 'cama', 'televisor'}

usuario_2={'mesa', 'silla', 'cama', 'televisor','video game'}

len(usuario_1.intersection(usuario_2)) # 4

print(len(usuario_1.intersection(usuario_2)))

#smilaridade

similaridade=len(usuario_1.intersection(usuario_2))/len(usuario_1.union(usuario_2))

print(similaridade) 
