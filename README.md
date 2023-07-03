while True:
    print("👋 Olá, sou @arthurmassimetti!")
    print("O que gostaria de saber sobre mim?")
    print("ㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ")
    print("1. 👀 Tenho interesse em ...")
    print("2. 🌱 Atualmente estou aprendendo ...")
    print("3. 💞️ Estou procurando colaborar em ...")
    print("4. 📫 Como me contatar ...")
    print("5. Sair")

    opcao = input("Escolha uma opção: ")

    if opcao == "1":
        print("Você escolheu a opção 1.")
        print("ㅤ")
        print("Meu desejo é aprimorar meu conhecimento em bancos de dados. Além disso, tenho o objetivo de concluir minha pós-graduação na Europa, buscando uma experiência internacional enriquecedora. Estou animado com essa jornada de aprendizado e determinado a adquirir as habilidades necessárias para construir uma carreira promissora nesse campo.")
        print("ㅤ") 
        
    elif opcao == "2":
        print("Você escolheu a opção 2.")
        print("ㅤ") 
        print("Estou aprendendo sobre a estrutura de hardwares, sistemas empresariais, HTML e CSS, Python e gestão empresarial. Estou explorando os componentes físicos de um computador, a gestão de operações empresariais, a construção de páginas web, a programação em Python e as habilidades de gerenciamento de uma organização.")
        print("ㅤ") 

    elif opcao == "3":
        print("Você escolheu a opção 3.")
        print("ㅤ")
        print("Estou em busca de oportunidades de colaboração. Busco aprimorar minhas habilidades tecnológicas e tenho interesse em desenvolvimento de software, administração de sistemas e segurança da informação. Estou aberto a aprender e me adaptar a novas tecnologias, e estou ansioso para contribuir com entusiasmo, resolução de problemas e habilidades de comunicação. Se você procura por alguém comprometido com o crescimento e inovação, estou pronto para enfrentar desafios e colaborar em projetos empolgantes.")
        print("ㅤ") 

    elif opcao == "4":
        print("Você escolheu a opção 4.")
        print("ㅤ")   
        print("- Email: arthursartori27@gmail.com")
        print("- LinkedIn: https://www.linkedin.com/in/arthur-massimetti-sartori-492184261/")
        print("- Instagram: arthurmassimetti")
        print("- Portfólio: https://arthurmassimetti.github.io/arthurmassimetti/folder.html")
        print("ㅤ") 

    elif opcao == "5":
        print("Saindo do programa...")
        print("ㅤ") 
        break
        
    else:
        print("Opção inválida! Por favor, escolha uma opção válida.")
        print("ㅤ") 

    resposta = input("Deseja repetir o programa? (Sim/Não): ")
    print("ㅤ") 
    
    # Verifica a resposta do usuário
    if resposta.lower() != "sim":
        print("Encerrando o programa...")
        break
