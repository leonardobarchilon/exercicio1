# exercicio1
Repositório para exercício da aula de CI/CD


Configurações iniciais:
![image](https://github.com/user-attachments/assets/62bdc8ae-25c1-4bc2-a67b-d72f35c72fff)

Exercícios:
Letra A e B:
echo 01 > arquivo.txt                            # Criando arquivo de texto chamado "arquivo.txt", com o valor "01"
git add arquivo.txt                              # Adicionando o novo arquivo criado no staging
git status                                       # Conferindo o status
![image](https://github.com/user-attachments/assets/dfffe81c-5d4b-48eb-b809-7c1b566b45bc)

Letra C:
git commit -m "git add example - arquivo.txt"    # Commitando o arquivo que estava no staging com o comentário solicitado no exercício
![image](https://github.com/user-attachments/assets/0e85b76c-226c-43c7-90f4-8fdfd1981f80)

Letra D:
echo 02 > arquivo.txt                            # Sobrescrevendo o conteúdo do "arquivo.txt" com o valor "02"
![image](https://github.com/user-attachments/assets/fb48871f-591b-479d-a163-4e993979920e)

Letra E:
git diff                                        # Verificando a diferença entre o arquivo atual e o arquivo commitado pré-staging
![image](https://github.com/user-attachments/assets/96e8d4a4-cdc2-4bee-ac08-0ad210ac9b00)

Letra F:
git add arquivo.txt                            # Adicionando o arquivo "arquivo.txt" para staging novamente
git status                                     # Verificando o status
![image](https://github.com/user-attachments/assets/0addbf5d-fa4f-4a05-9c82-462e93a3ee38)
![image](https://github.com/user-attachments/assets/ba7f77d2-33d7-45ec-8376-de8ce2654b15)

Letra G:
git diff --staged                             # Verificando a diferença entre o arquivo commitado e o arquivo que está no staging
![image](https://github.com/user-attachments/assets/6736a54c-3df0-4466-99c7-00753cf64a75)

Letra H:
echo 03 > arquivo.txt                        # Sobrescrevendo o conteúdo do "arquivo.txt" com o valor "03"
![image](https://github.com/user-attachments/assets/101847e3-0e25-4a8d-855d-1036e468cd59)

Letra I:
git diff                                    # Verificando a diferença entre o arquivo comitado e o arquivo modificado pré-staging
![image](https://github.com/user-attachments/assets/e60a9fa2-702d-4faf-930c-f97c4be4d7ba)

Letra J:
git restore --staged arquivo.txt            # Restaurar o arquivo "arquivo.txt" da área de staging
git status                                  # Verificar o status
![image](https://github.com/user-attachments/assets/d4a45c08-bd57-4997-9b73-ab208f1166bf)

Letra K:
git add arquivo.txt                         # Adicionando o arquivo.txt novamente para staging
git commit -m "arquivo.txt restaurado"      # Commitando o arquivo "arquivo.txt"
git log                                     # Verificando os logs
![image](https://github.com/user-attachments/assets/65eb4bfa-6d2d-4981-a979-2dc5e1032eaf)

Letra L:
echo "*.txt" > .gitignore                  # Criando o arquivo .gitignore e adicionando o valor "*.txt" dentro dele
![image](https://github.com/user-attachments/assets/11164842-f823-4d64-90c4-098b1d67f4e6)

Letra M:
echo "novo arquivo" > novo.txt            # Criando arquivo "novo.txt"
git status                                # Verificando o status
![image](https://github.com/user-attachments/assets/8afea60e-f45b-4104-8b34-a701706db981)


### ADICIONAL ###
Utilizei o comando "git add ." para mover todos os arquivos para área de staging, e, quando, verifico o status, de fato, o arquivo "novo.txt" não é movido para staging:
![image](https://github.com/user-attachments/assets/5c1683fb-3813-4fa8-9859-21d23c18adc3)

Arquivo .gitginore commitado
![image](https://github.com/user-attachments/assets/c6bed458-7feb-4b46-8872-f5efe7548b22)
