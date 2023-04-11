#include <iostream>
#include <locale.h>
using namespace std;

int main()
{
int escolha;
setlocale (LC_ALL, "Portuguese");
cout << endl << "CHLOE" << endl << endl;
cout << endl << "Você se chama Chloe Barr Conway, nascida no Maine, tem fartos cabelos loiros na faixa dos ombros, olhos verde-fosco,pele caucasiana e mede um metro e setenta de altura. Trabalha no escritório de uma agência de investigação e reportagens em Bangor, onde os salários, para a sua posição e experiência de três anos na área, giram na casa das cinco mil a dez mil pratas anuais, e seu teste de gradivez, hoje jogado na lixeira do banheiro do seu apartamento, resultara positivo na manhã de um domingo da semana passada. Nem se Deus quisesse Horald deveria descobrir isso. Faltam-lhes verba para o aluguel, imagina para uma criança." << endl;
cout << endl << "— Chloe, você está bem? — perguntou Oliver, um companheiro seu de escritório sacana e braço direito carismático do direitor-chefe de vocês." << endl << "O que responder para ele? (Digite o número que melhor satisfazer sua vontade)" << endl;
cout << endl << "1. Estou bem, nada demais..." << endl;
cout << endl << "2. Os enjôos estão piorando. Que merda..." << endl;
cout << endl << "3. Está se importando comigo? Que gracinha..." << endl;
cin >> escolha;
if (escolha==1) {
cout << endl << "— Estou bem, nada demais — Sua cabeça explodia. Você ajeita uma mecha do seu cabelo e leva a mão à testa, como se aliviasse algo." << endl;
cout << endl << "Oliver levanta de sua cadeira apoiado nos joelhos, vai para a cafeteira que ficava numa estante do escritório e diz:" << endl << "— Pior atuação que vi nessa vida. Vai querer um café?" << endl;
}
if (escolha==2) {
cout << endl << "— Os enjôos estão piorando. Que merda... — Você leva sua mão à testa, e lamenta ter esquecido de ingerir as pílulas do dia seguinte." << endl;
cout << endl << "— Er, ainda bem que nasci com um belíssimo pinto bem-dotado entre as pernas — Oliver se levanta da cadeira dele apoiado nos joelhos e vai para a cafeteira, que ficava numa bancada do escritório — Vai querer um café?" << endl;
}
if (escolha==3) {
cout << endl << "— Está se importando comigo? Que gracinha. — Você encara Oliver, ele e a sua camisa social branco-marfim, suspensórios vermelhos e gravata e calças pretas." << endl;
cout << endl << "— Você é o futuro dessa instituição — declarou Oliver — Você, o Kean, a Stephania — Ele levanta da cadeira apoiado nos joelhos e vai para cafeteira do escritório, que ficava numa bancada — Vai querer um café?" << endl;
}
cout << endl << " 'Café ou não, eis a questão...', você pensa." << endl << "O que me diz, Chloe?" << endl << "1. Aceita..." << endl << "2. Ou recusa?" << endl;
cin >> escolha;

if (escolha==1) {
cout << endl << "— Uma dose não faz mal a ninguém, né? — Você diz." << endl << "— Essa é a velha e ousada Chole que conheço! — Pressionou o botão 'LIGAR' da cafeteira e encheu o segundo copo descartável de isopor — Você sabe do que quero falar agora, né?" << endl;
cout << endl << "1.Como assim?" << endl;
cout << "2. Sim, Oliver, e eu já disse que não!" << endl;
cin >> escolha;
}
if (escolha==2) {
cout << endl << "— Enlouqueceu de vez? Essas bebidas prejudicam o bebê. — Você protesta." << endl << "— Bom, se você diz... — Oliver abandonou o segundo copo descartável de isopor na bancada e caminhou paciente para as suas costas — Mas você sabe que temos de resolver umas pendências, certo? — Contornou-te à direita e sentou na cadeira." << endl;
cout << endl << "1.Como assim?" << endl;
cout << "2. Sim, Oliver, e eu já disse que não!" << endl;
cin >> escolha;
}
if (escolha==2) {
cout << endl << "— Sim, Oliver, e eu já disse que não! — Você cruza os braços e força sua tonalidade vocal. Oliver espreme os lábios e espia os seus flancos discreto. Ele parecia repensar os passos que teria de aplicar, contigo. As medidas necessárias para satisfazer os desejos dele, e quiçá, de alguém superior na cadeia alimentar do escritório." << endl;
cout << "— Escute, Chloe. Não é o tipo de oportunidade que aparece para todos. Entende isso, certo? — Ele torna a arriada cabeça para você — É como um cometa de milênios de intervalo para cortar o céu. O espaço — Suas mãos se conectavam num pêndulo rígido. As sobrancelhas, erguiam-se como de alguém que teme contar um desagrado." << endl;
cout << endl << "1. Por que querem tanto a minha presença. O que eu perderia?" << endl;
cout << "2. Eu disse que não, Oliver. Se não estiver disposto a aceitar, ao menos respeite que existem jornalistas dignos!" << endl;
cin >> escolha;
if (escolha==2) {
cout << "Oliver caminha para a sua direção, em silêncio, os olhos te predando tal qual o tigre fita seu banquete da grama alta. A mídia tem os seus tubarões, e Oliver estava acostumado a aprender com eles. Tornara-se um deles." << endl;
cout << "— Oras, por quê? — Suas sobrancelhas e lábios franziram." << endl;
cout << "— Está brincando? Lewiston é um campo minado pronto para explodir — Você se levanta da cadeira e o encara — A droga de um campo minado, Oliver! Você não vê? É loucura!" << endl;
cout << "Oliver inspira e expira pesado, como quem precisava de oxigênio amenizado para sobreviver. Deposita as duas mãos em seus ombros e os massageia." << endl;
cout << "— Entendo em absoluto, tudo o que disse. Sabe — Ele abre as pálpebras, disposto a ser, ou soar, compreensivo — Também tenho as minhas merdas em casa. A Lucy descobriu um câncer de colo de útero a três meses e...Tenho de arrecadar o dinheiro dessa reportagem, senão..." << endl;
cout << endl << "1. Ceder..." << endl;
cout << "2. Persistir em abandonar o escritório..." << endl;
cin >> escolha;
if (escolha==2) {
cout << endl << "— Eu não preciso disso. De você, dessa porra de notícia ou dessa empresa — Você se torna de costas para ele e se move depressa para a porta de entrada e saída do escritório. põe sua mão na maçaneta e inspira fundo — Eu me viro... — Conclui, e a gira." << endl;
cout << "Passos enlouquecedores soam detrás da sua retaguarda e as mãos de Oliver, avantajadas e quebradiças, predem-lhe a boca, os olhos e o nariz." << endl;
cout << "— Não, não, mocinha, você ficará comigo! Uma pena a associação ter de demitir mais um ousadinho..." << endl;
cout << "Seus gritos disparam em vão. Eram onze horas e trinta minutos da noite. Apenas você e ele estavam trabalhando, naquele escritório de lâmpadas falhas e conotação antiquada. Marrom, desenhos imperiais, e fedido a aposentos abandonados. Oliver aperta suas vias respiratórias e lhe esvai a consciência. Você o golpeia, inútil, com socos de petulância instável e pisões errôneos nos pés dele. O mundo se encolhe, e encolhe." << endl;
cout << "Um quique de rodas no quebra-molas te acorda. Você está na traseira obscura de uma vã azul-marinho. Amarrada, nos membros e na boca. Lágrimas escorrem dos seus olhos e poças de catarro implodiam das narinas para o lenço que alguém amarrara em sua boca." << endl;
cout << "— Você acredita que aquela puta quase me mordeu? — A voz de Oliver comenta para o seu parceiro, ou o motorista, ou para si mesmo — Porra, que caralho... Essa merda de usina está dando um trabalho desgraçado. Que merda." << endl;
cout << "Em cerca de uma hora ou duas. A vã estaciona, as portas dos bancos frontais dela abrem e você escuta solas de sapatos atritando no concreto molhado. Oliver destranca e puxa as portas-duplas de onde você deitava, fita-te, e torna os olhos para um homem que vestia um moletom preto com capuz acoplado no pescoço." << endl;
cout << "— Pegue ela, que eu cuido do resto — Ele saca um cigarro e um isqueiro prata límpido do bolso de peito da camisa social e se encaminha para fora do seu campo de visão das portas abertas." << endl;
cout << "O homem de casaco salta para a caçamba e ela balança hesitante convosco. Você tenta exprimir seus pensamentos, seus medos. 'Quem é você?'. 'O que está fazendo?'... e falha. Ele te carrega no ombro direito e te joga rente a uma parede de tijolos cinzentos e úmido." << endl;
cout << "— Permita que eu finalize essa garotinha mal-criada para você, Russus — Oliver contornou Russus, o seu amontoado de músculos coautor, o homem encapuzado...o segundo cúmplice direto do seu assassinato." << endl;
cout << "Oliver aponta o cano da revólver de pressão preto quatro ponto cinco dele para o seu estirado corpo, e dispara cinco rajadas. Duas no pescoço e no peito, e uma no rosto." << endl;
cout << endl << "...FIM DE JOGO..." << endl;
cout << "Reinicie a aplicação para usufruir dos seus outros destinos. " << endl;
}
if (escolha==1) {
cout << endl << "— Tudo bem, tudo bem! — Você o interrompe, incomodada. Sua consciência apita alertas vermelhos no breu de um palco teatral." << endl;
cout << "Oliver sorri nos cantos dos lábios e relembra:" << endl;
cout << "— Amanhã, às quatro. Tudo bem?" << endl;
cout << "Você meneia um 'sim' com a cabeça." << endl;
cout << "Sem problemas. Até lá..." << endl;
cout << "Ele te abraça e, cuidadoso, estapeia sua bochecha esquerda duas vezes." << endl;
cout << "— Esta é a minha jóia." << endl;
cout << "Oliver beija sua testa e sai do escritório" << endl;
cout << endl << "Em seu apartamento de trinta metros quadrados, às onze horas da noite, você está sozinha. Escuta os seus batimentos cardíacos acelerados e o sangue fluindo nas veias. O ventilador roía rodopiando no teto. As luzes, resumidas a uma luminária que se avizinhava à esquerda do sofá, onde suas costas e pernas se deitavam, tendiam a uma hora se apagarem para sempre. A vossa frequência estava inconstante. Um sincero sentimento seu clama uma última travessura de Chloe Conway. Uma fuga." << endl;
cout << endl << "1. Eu tenho de ir para a viagem..." << endl;
cout << "2. Nem fodendo..." << endl;
cin >> escolha;
if (escolha==2) {
cout << endl << "— Nem se me pagassem. Toda família tem uma mãe... — Você acaricia sua barriga, torna-se para a direita, encolhe-se, ignora a programação de horário do despertador, tenta adormecer, e ouve a maçaneta da porta destrancar..." << endl;
cout << "Tom Boyle, jornalista secundário do canal sete. Dia onze de Abril de dois mil e três. Maine:" << endl;
cout << " '— Os policiais de uma viatura da delegacia de Bangor relataram na madrugada desta sexta-feira assassinato à sangue frio no apartamento de Chloe Conway, jornalista mirim da NewsBang de vinte e três anos e grávida de um mês. Conforme as suspeitas dos médicos-legistas, o algoz de Chloe teria perfurado sua jugular com um caco de vidro. Este ao meu lado, é o delegado Bull, um dos descobridores desse terrível crime.'" << endl;
cout << " '— Nós... não tínhamos nada a fazer além de prestar condolências e orações para a alma dela... Quando chegamos ao apartamento, o sangue dela estava... grudento, e o rosto sem vida... que Deus proteja o nosso país.' " << endl;
cout << endl << "...FIM DE JOGO..." << endl;
cout << "Reinicie a aplicação para usufruir dos seus outros destinos. " << endl;
}
if (escolha==1) {
cout << endl << "Às quatro da madrugada do dia trinta e um de março de abril de dois mil e três, você desperta com o alarme penetrante do despertador em seus ouvidos. Anda para o banheiro para retocar a maquiagem e pentear o cabelo. Na fachada da NewsBang, Oliver, junto a dois homens e uma mulher de sobretudo, acena para você e grita, com as mãos em concha ao lado da boca:" << endl;
cout << "— Ei, garota, vamos dar uma voltinha?" << endl;
cout << "Você devolve o aceno e se aproxima dele e dos seus acompanhantes: Russus, Stephania e Josh." << endl;
cout << "— Há de irmos, senhoras e senhores! Não temos nada a perder! — Oliver abriga Stephania e Josh num abraço e aponta para a porta do motorista para Russus — Você dirige, grandão!" << endl;
cout << "A hora do nada, sua avó costumava se referir aos começos das manhãs. Você, Oliver, Stephania, Russus, Josh e a vã sprinter na qual haviam embarcado, atravessavam uma pista na hora do nada. As árvores e os tapetes de gramas que vos cercavam se camuflavam nas incertezas de um habitat de almas desorientadas. Segredos aparentavam viver nelas. Consumí-las dia-a-dia. Stephania, uma mulher gorducha de cintura larga e cabelo chanel, quebra sua hipnose com a Mão Natureza lhe cutucando o ombro direito do banco de trás." << endl;
cout << "— Você está legal, Chloe? — Ela te questiona." << endl;
cout << "— Sim, na medida do possível — Você reponde, presa às sombras que corriam pelas folhas, galhos e troncos." << endl;
cout << "— Ah bom — Respira ela, aliviada — Porque com os cortes salariais que terão mês que vem, não sei se explodo ou espero para ver. Quer dizer... Nunca se sbae, né?..." << endl;
cout << "As frases de Stephania se dispersam no ar como uma bolha de sabão que estoura. A...coisa... das florestas parecia estar se locomovendo para a pista com os braços felpudos e de três metros de comprimento, pernas similares as de um coelho e uma cabeça a qual os biólogos classificariam como a de um alce. Ela se anuncia esbarrando o tórax de uns quinhentos quilogramas na carcaça da vã." << endl;
cout << "— Mas que porra é essa? — Josh exclama dos bancos traseiros." << endl;
cout << "O volante foge dos dedos de Russus e, com as rodas e o peso da vã, capota. Você protege sua cabeça com os braços e ora para que tudo aquilo que está acontecendo não passasse de um pesadelo. A vã gira para fora da rua e se arrasta num morrinho de grama, de rodas e chassi para os ares." << endl;
cout << "— Caralho, caralho! — Soa a vagarosa voz fantasmagórica de Oliver, no banco do copiloto. Sua visão, embaçada, induz que ele estaria sacando um revólver do porta-luvas, ou tentando sacar." << endl;
cout << "A criatura, porém, raptura-o da vã e o som de ossos e músculos estralando repercutem de prontidão. A mesma infelicidade acontece com Russus, Stephania e Josh, em respectivo. Você, e os frangalhos de consciência que lhe restavam, fita os flancos e desconecta seu cinto de segurança. Cai no ex-tetp da vã e se arrasta para as portas-duplas da traseira dela. Sua respiração falha e o mundo borra feito um efeito psicodélico em espiral. Sobras de carne caem à sua esquerda. O sangue fresco delas pintam o gramado de um vermelho escarlate horrendo." << endl;
cout << "— Meu Deus! Meu Deus! — Você grita para Deus. O único salvador que poderia te oferecer uma mão para a terra do descanso eterno com ternura." << endl;
cout << "O braço da criatura invade a vã em sua porta-dupla traseira, agarra-te e joga você de costas para o solo. Seus músculos eletrificam de dor e a garganta implodia para gritar." << endl;
cout << "— Não, não! Merda, merda! Caralho! — Com os doloridos das suas pernas, você recua o corpo um centímetro — Por favor... — Fluídos vermelhos frescos escorriam da sua testa para se misturar às lágrimas e aos catarros." << endl;
cout << "A criatura se assemelha a um gárgula. Observando-te do cume do chassi. Os globos oculares brilhantes de um laranja-âmbar neon. Chifres enfeitados com sebo e lodo. Dentes ossudos manchados de sangue e encrustados de pedaços de pele dos seus colegas de escritório. Observando-te, como uma diversão, um hobbie. Ela desce da vã e vaga parcimoniosa para você, leve a cabeça dela à sua, e respira. Dois jatos de ar nublado das narinas." << endl;
cout << "— Deus,Deus, por favor... Cuide do Harold, cuide... A ti eu temo — Você sussurra nos pensamentos. Falha. Frágil." << endl;
cout << "O dedo indicador esquerdo da criatura, com uma pontiaguda e envergada unha preta embutida nele, move-se em direção a sua barriga e a cutuca. Como uma criança ansiosa deduzindo qual seria o seu presente de aniversário." << endl;
cout << "Você está ofegante, o coração descompassado. Órbitas oculares latejantes, e uma ânsia de vômito preocupante. Sujeita a quaisquer reviravoltas. Quaisquer alucinações." << endl;
cout << "A criatura abre a boca dela e de sua língua um eco se modula no ar:" << endl;
cout << "— Nunca mais...volte..." << endl;
cout << "Ela se tornou para a direita e voltou para o seu ambiente de breus e privacidade, paciente. Um camaleão adaptando a vossa pele para se camuflar no cenário. Preto, preto, e sumiço completo." << endl;
cout << "Você despenca sua cabeça na grama e aproveita a piedade dela para enfim respirar livre de ameaças. Você, a vã, e Savana, sua garotinha que viria a nascer em dois mil e quatro, pesando três quilos e aos prantos." << endl;
}
}

}
if (escolha==1) {
cout << endl << "— Por que querem tanto a minha presença. O que eu perderia, sério?" << endl;
cout << "— A porra de uma chance, sua vadia insistente! — Oliver rosna dentre os dentes. Dos seus lábios, gotículas de saliva disparam para as suas sapatilhas." << endl;
cout << "— Você enlouqueceu? Eu não preciso arriscar minha vida por uma notícia! — Você se levanta da cadeira e o encara. Seu coração bombeia descontrolado o sangue, e as veias das mãos pulsam para cerrá-las." << endl;
cout << "Oliver desdobra os joelhos e anda em sua direção, de postura e semblante rígidos." << endl;
cout << "— Vida? Que vida você tem?" << endl;
cout << "1. Abandonar o escritório..." << endl;
cout << "2. Permanecer..." << endl;
cin >> escolha;
if (escolha==1) {
cout << endl << "— Eu não preciso disso. De você, dessa porra de notícia ou dessa empresa — Você se torna de costas para ele e se move depressa para a porta de entrada e saída do escritório. põe sua mão na maçaneta e inspira fundo — Eu me viro... — Conclui, e a gira." << endl;
cout << "Passos enlouquecedores soam detrás da sua retaguarda e as mãos de Oliver, avantajadas e quebradiças, predem-lhe a boca, os olhos e o nariz." << endl;
cout << "— Não, não, mocinha, você ficará comigo! Uma pena a associação ter de demitir mais um ousadinho..." << endl;
cout << "Seus gritos disparam em vão. Eram onze horas e trinta minutos da noite. Apenas você e ele estavam trabalhando, naquele escritório de lâmpadas falhas e conotação antiquada. Marrom, desenhos imperiais, e fedido a aposentos abandonados. Oliver aperta suas vias respiratórias e lhe esvai a consciência. Você o golpeia, inútil, com socos de petulância instável e pisões errôneos nos pés dele. O mundo se encolhe, e encolhe." << endl;
cout << "Um quique de rodas no quebra-molas te acorda. Você está na traseira obscura de uma vã azul-marinho. Amarrada, nos membros e na boca. Lágrimas escorrem dos seus olhos e poças de catarro implodiam das narinas para o lenço que alguém amarrara em sua boca." << endl;
cout << "— Você acredita que aquela puta quase me mordeu? — A voz de Oliver comenta para o seu parceiro, ou o motorista, ou para si mesmo — Porra, que caralho... Essa merda de usina está dando um trabalho desgraçado. Que merda." << endl;
cout << "Em cerca de uma hora ou duas. A vã estaciona, as portas dos bancos frontais dela abrem e você escuta solas de sapatos atritando no concreto molhado. Oliver destranca e puxa as portas-duplas de onde você deitava, fita-te, e torna os olhos para um homem que vestia um moletom preto com capuz acoplado no pescoço." << endl;
cout << "— Pegue ela, que eu cuido do resto — Ele saca um cigarro e um isqueiro prata límpido do bolso de peito da camisa social e se encaminha para fora do seu campo de visão das portas abertas." << endl;
cout << "O homem de casaco salta para a caçamba e ela balança hesitante convosco. Você tenta exprimir seus pensamentos, seus medos. 'Quem é você?'. 'O que está fazendo?'... e falha. Ele te carrega no ombro direito e te joga rente a uma parede de tijolos cinzentos e úmido." << endl;
cout << "— Permita que eu finalize essa garotinha mal-criada para você, Russus — Oliver contornou Russus, o seu amontoado de músculos coautor, o homem encapuzado...o segundo cúmplice direto do seu assassinato." << endl;
cout << "Oliver aponta o cano da revólver de pressão preto quatro ponto cinco dele para o seu estirado corpo, e dispara cinco rajadas. Duas no pescoço e no peito, e uma no rosto." << endl;
cout << endl << "...FIM DE JOGO..." << endl;
cout << "Reinicie a aplicação para usufruir dos seus outros destinos. " << endl;
}
if (escolha==2) {
cout << endl << "— Uma família que está vindo. Meu namorado, pais... tudo, Oliver. Não entende? — Você se firma com um alavanque vocal polido, de olhos ficcionados nos dele." << endl;
cout << "Oliver inspira e expira pesado, como quem precisava de oxigênio amenizado para sobreviver. Deposita as duas mãos em seus ombros e os massageia." << endl;
cout << "— Entendo em absoluto, tudo o que disse. Sabe — Ele abre as pálpebras, disposto a ser, ou soar, compreensivo — Também tenho as minhas merdas em casa. A Lucy descobriu um câncer de colo de útero a três meses e...Tenho de arrecadar o dinheiro dessa reportagem, senão..." << endl;
cout << endl << "1. Ceder..." << endl;
cout << "2. Persistir em abandonar o escritório..." << endl;
cin >> escolha;
if (escolha==2) {
cout << endl << "— Eu não preciso disso. De você, dessa porra de notícia ou dessa empresa — Você se torna de costas para ele e se move depressa para a porta de entrada e saída do escritório. põe sua mão na maçaneta e inspira fundo — Eu me viro... — Conclui, e a gira." << endl;
cout << "Passos enlouquecedores soam detrás da sua retaguarda e as mãos de Oliver, avantajadas e quebradiças, predem-lhe a boca, os olhos e o nariz." << endl;
cout << "— Não, não, mocinha, você ficará comigo! Uma pena a associação ter de demitir mais um ousadinho..." << endl;
cout << "Seus gritos disparam em vão. Eram onze horas e trinta minutos da noite. Apenas você e ele estavam trabalhando, naquele escritório de lâmpadas falhas e conotação antiquada. Marrom, desenhos imperiais, e fedido a aposentos abandonados. Oliver aperta suas vias respiratórias e lhe esvai a consciência. Você o golpeia, inútil, com socos de petulância instável e pisões errôneos nos pés dele. O mundo se encolhe, e encolhe." << endl;
cout << "Um quique de rodas no quebra-molas te acorda. Você está na traseira obscura de uma vã azul-marinho. Amarrada, nos membros e na boca. Lágrimas escorrem dos seus olhos e poças de catarro implodiam das narinas para o lenço que alguém amarrara em sua boca." << endl;
cout << "— Você acredita que aquela puta quase me mordeu? — A voz de Oliver comenta para o seu parceiro, ou o motorista, ou para si mesmo — Porra, que caralho... Essa merda de usina está dando um trabalho desgraçado. Que merda." << endl;
cout << "Em cerca de uma hora ou duas. A vã estaciona, as portas dos bancos frontais dela abrem e você escuta solas de sapatos atritando no concreto molhado. Oliver destranca e puxa as portas-duplas de onde você deitava, fita-te, e torna os olhos para um homem que vestia um moletom preto com capuz acoplado no pescoço." << endl;
cout << "— Pegue ela, que eu cuido do resto — Ele saca um cigarro e um isqueiro prata límpido do bolso de peito da camisa social e se encaminha para fora do seu campo de visão das portas abertas." << endl;
cout << "O homem de casaco salta para a caçamba e ela balança hesitante convosco. Você tenta exprimir seus pensamentos, seus medos. 'Quem é você?'. 'O que está fazendo?'... e falha. Ele te carrega no ombro direito e te joga rente a uma parede de tijolos cinzentos e úmido." << endl;
cout << "— Permita que eu finalize essa garotinha mal-criada para você, Russus — Oliver contornou Russus, o seu amontoado de músculos coautor, o homem encapuzado...o segundo cúmplice direto do seu assassinato." << endl;
cout << "Oliver aponta o cano da revólver de pressão preto quatro ponto cinco dele para o seu estirado corpo, e dispara cinco rajadas. Duas no pescoço e no peito, e uma no rosto." << endl;
cout << endl << "...FIM DE JOGO..." << endl;
cout << "Reinicie a aplicação para usufruir dos seus outros destinos. " << endl;
}
if (escolha==1) {
cout << endl << "— Tudo bem, tudo bem! — Você o interrompe, incomodada. Sua consciência apita alertas vermelhos no breu de um palco teatral." << endl;
cout << "Oliver sorri nos cantos dos lábios e relembra:" << endl;
cout << "— Amanhã, às quatro. Tudo bem?" << endl;
cout << "Você meneia um 'sim' com a cabeça." << endl;
cout << "Sem problemas. Até lá..." << endl;
cout << "Ele te abraça e, cuidadoso, estapeia sua bochecha esquerda duas vezes." << endl;
cout << "— Esta é a minha jóia." << endl;
cout << "Oliver beija sua testa e sai do escritório" << endl;
cout << endl << "Em seu apartamento de trinta metros quadrados, às onze horas da noite, você está sozinha. Escuta os seus batimentos cardíacos acelerados e o sangue fluindo nas veias. O ventilador roía rodopiando no teto. As luzes, resumidas a uma luminária que se avizinhava à esquerda do sofá, onde suas costas e pernas se deitavam, tendiam a uma hora se apagarem para sempre. A vossa frequência estava inconstante. Um sincero sentimento seu clama uma última travessura de Chloe Conway. Uma fuga." << endl;
cout << endl << "1. Eu tenho de ir para a viagem..." << endl;
cout << "2. Nem fodendo..." << endl;
cin >> escolha;
if (escolha==2) {
cout << endl << "— Nem se me pagassem. Toda família tem uma mãe... — Você acaricia sua barriga, torna-se para a direita, encolhe-se, ignora a programação de horário do despertador, tenta adormecer, e ouve a maçaneta da porta destrancar..." << endl;
cout << "Tom Boyle, jornalista secundário do canal sete. Dia onze de Abril de dois mil e três. Maine:" << endl;
cout << " '— Os policiais de uma viatura da delegacia de Bangor relataram na madrugada desta sexta-feira assassinato à sangue frio no apartamento de Chloe Conway, jornalista mirim da NewsBang de vinte e três anos e grávida de um mês. Conforme as suspeitas dos médicos-legistas, o algoz de Chloe teria perfurado sua jugular com um caco de vidro. Este ao meu lado, é o delegado Bull, um dos descobridores desse terrível crime.'" << endl;
cout << " '— Nós... não tínhamos nada a fazer além de prestar condolências e orações para a alma dela... Quando chegamos ao apartamento, o sangue dela estava... grudento, e o rosto sem vida... que Deus proteja o nosso país.' " << endl;
cout << endl << "...FIM DE JOGO..." << endl;
cout << "Reinicie a aplicação para usufruir dos seus outros destinos. " << endl;
}
if (escolha==1) {
cout << endl << "Às quatro da madrugada do dia trinta e um de março de abril de dois mil e três, você desperta com o alarme penetrante do despertador em seus ouvidos. Anda para o banheiro para retocar a maquiagem e pentear o cabelo. Na fachada da NewsBang, Oliver, junto a dois homens e uma mulher de sobretudo, acena para você e grita, com as mãos em concha ao lado da boca:" << endl;
cout << "— Ei, garota, vamos dar uma voltinha?" << endl;
cout << "Você devolve o aceno e se aproxima dele e dos seus acompanhantes: Russus, Stephania e Josh." << endl;
cout << "— Há de irmos, senhoras e senhores! Não temos nada a perder! — Oliver abriga Stephania e Josh num abraço e aponta para a porta do motorista para Russus — Você dirige, grandão!" << endl;
cout << "A hora do nada, sua avó costumava se referir aos começos das manhãs. Você, Oliver, Stephania, Russus, Josh e a vã sprinter na qual haviam embarcado, atravessavam uma pista na hora do nada. As árvores e os tapetes de gramas que vos cercavam se camuflavam nas incertezas de um habitat de almas desorientadas. Segredos aparentavam viver nelas. Consumí-las dia-a-dia. Stephania, uma mulher gorducha de cintura larga e cabelo chanel, quebra sua hipnose com a Mão Natureza lhe cutucando o ombro direito do banco de trás." << endl;
cout << "— Você está legal, Chloe? — Ela te questiona." << endl;
cout << "— Sim, na medida do possível — Você reponde, presa às sombras que corriam pelas folhas, galhos e troncos." << endl;
cout << "— Ah bom — Respira ela, aliviada — Porque com os cortes salariais que terão mês que vem, não sei se explodo ou espero para ver. Quer dizer... Nunca se sbae, né?..." << endl;
cout << "As frases de Stephania se dispersam no ar como uma bolha de sabão que estoura. A...coisa... das florestas parecia estar se locomovendo para a pista com os braços felpudos e de três metros de comprimento, pernas similares as de um coelho e uma cabeça a qual os biólogos classificariam como a de um alce. Ela se anuncia esbarrando o tórax de uns quinhentos quilogramas na carcaça da vã." << endl;
cout << "— Mas que porra é essa? — Josh exclama dos bancos traseiros." << endl;
cout << "O volante foge dos dedos de Russus e, com as rodas e o peso da vã, capota. Você protege sua cabeça com os braços e ora para que tudo aquilo que está acontecendo não passasse de um pesadelo. A vã gira para fora da rua e se arrasta num morrinho de grama, de rodas e chassi para os ares." << endl;
cout << "— Caralho, caralho! — Soa a vagarosa voz fantasmagórica de Oliver, no banco do copiloto. Sua visão, embaçada, induz que ele estaria sacando um revólver do porta-luvas, ou tentando sacar." << endl;
cout << "A criatura, porém, raptura-o da vã e o som de ossos e músculos estralando repercutem de prontidão. A mesma infelicidade acontece com Russus, Stephania e Josh, em respectivo. Você, e os frangalhos de consciência que lhe restavam, fita os flancos e desconecta seu cinto de segurança. Cai no ex-tetp da vã e se arrasta para as portas-duplas da traseira dela. Sua respiração falha e o mundo borra feito um efeito psicodélico em espiral. Sobras de carne caem à sua esquerda. O sangue fresco delas pintam o gramado de um vermelho escarlate horrendo." << endl;
cout << "— Meu Deus! Meu Deus! — Você grita para Deus. O único salvador que poderia te oferecer uma mão para a terra do descanso eterno com ternura." << endl;
cout << "O braço da criatura invade a vã em sua porta-dupla traseira, agarra-te e joga você de costas para o solo. Seus músculos eletrificam de dor e a garganta implodia para gritar." << endl;
cout << "— Não, não! Merda, merda! Caralho! — Com os doloridos das suas pernas, você recua o corpo um centímetro — Por favor... — Fluídos vermelhos frescos escorriam da sua testa para se misturar às lágrimas e aos catarros." << endl;
cout << "A criatura se assemelha a um gárgula. Observando-te do cume do chassi. Os globos oculares brilhantes de um laranja-âmbar neon. Chifres enfeitados com sebo e lodo. Dentes ossudos manchados de sangue e encrustados de pedaços de pele dos seus colegas de escritório. Observando-te, como uma diversão, um hobbie. Ela desce da vã e vaga parcimoniosa para você, leve a cabeça dela à sua, e respira. Dois jatos de ar nublado das narinas." << endl;
cout << "— Deus,Deus, por favor... Cuide do Harold, cuide... A ti eu temo — Você sussurra nos pensamentos. Falha. Frágil." << endl;
cout << "O dedo indicador esquerdo da criatura, com uma pontiaguda e envergada unha preta embutida nele, move-se em direção a sua barriga e a cutuca. Como uma criança ansiosa deduzindo qual seria o seu presente de aniversário." << endl;
cout << "Você está ofegante, o coração descompassado. Órbitas oculares latejantes, e uma ânsia de vômito preocupante. Sujeita a quaisquer reviravoltas. Quaisquer alucinações." << endl;
cout << "A criatura abre a boca dela e de sua língua um eco se modula no ar:" << endl;
cout << "— Nunca mais...volte..." << endl;
cout << "Ela se tornou para a direita e voltou para o seu ambiente de breus e privacidade, paciente. Um camaleão adaptando a vossa pele para se camuflar no cenário. Preto, preto, e sumiço completo." << endl;
cout << "Você despenca sua cabeça na grama e aproveita a piedade dela para enfim respirar livre de ameaças. Você, a vã, e Savana, sua garotinha que viria a nascer em dois mil e quatro, pesando três quilos e aos prantos." << endl;
cout << endl << "...FIM DE JOGO..." << endl;
cout << "Reinicie a aplicação para usufruir dos seus outros destinos. " << endl;
}
}
}
}
}

if (escolha==1) {
cout << endl << "— Como assim? — Seus olhos se arregalam para Oliver." << endl;
cout << endl << "— A gravidez engorda, não te faz perder a memória — Ele se senta na cadeira e bebe um gole do café expresso de avelã com caramelo. O cheiro dele te enoja." << endl;
cout << endl << "1. Tanto faz. Desde que você tome essa coisa rápido..." << endl;
cout << "2. Não fode..." << endl;
cin >> escolha;
if (escolha==2) {
cout << endl << "— Não fode, Oliver — Você revira os olhos e sua voz fica rouca." << endl;
cout << "— Ei, ei, Chloe! Não precisamos disso! O que há? São os hormônios? — Ele arregalou os supercílios e estirou os braços." << endl;
cout << "1. Não sei, devem ser. Vai saber, né?..." << endl;
cout << "2. Ai, Oliver, deixa pra lá..." << endl;
cin >> escolha;
if (escolha==2) {
cout << endl << "— Ai, Oliver, deixa pra lá — Você menea a cabeça para baixo e reduz o volume da voz." << endl;
cout << "— Ótimo... — Disse ele, sombrio. Virou seu copo e o jogou na lixeira à esquerda de seus pés — Até, amanhã, querida, às quatro — Acariciou o seu ombro direito e saiu." << endl;
}
if (escolha==1) {
cout << endl << "— Não sei, devem ser. Vai saber, né, porra? — Ríspida, você gesticula sinais agressivos com as mãos. Seu semblante está ouriçando e empertigado para Oliver." << endl;
cout << "— Bom, se você diz, né — Ele vira o copo e jogo numa lata de lixo à esquerda de seus pés — Você está dentro ou não?" << endl;
cout << "1. Estou..." << endl;
cout << "2. Não estou... Pode esquecer..." << endl;
cin >> escolha;
if (escolha==1) {
cout << endl << "— Estou, sim... — Você menea a cabeça para baixo, da direita para a esquerda. Morde os lábios e as bochechas." << endl;
cout << "— Belíssima escolha, querida. Amanhã, às quatro — Oliver acaricia seu ombro direito e sai da sala." << endl;
cout << endl << "Em seu apartamento de trinta metros quadrados, às onze horas da noite, você está sozinha. Escuta os seus batimentos cardíacos acelerados e o sangue fluindo nas veias. O ventilador roía rodopiando no teto. As luzes, resumidas a uma luminária que se avizinhava à esquerda do sofá, onde suas costas e pernas se deitavam, tendiam a uma hora se apagarem para sempre. A vossa frequência estava inconstante. Um sincero sentimento seu clama uma última travessura de Chloe Conway. Uma fuga." << endl;
cout << endl << "1. Eu tenho de ir para a viagem..." << endl;
cout << "2. Nem fodendo..." << endl;
cin >> escolha;
if (escolha==2) {
cout << endl << "— Nem se me pagassem. Toda família tem uma mãe... — Você acaricia sua barriga, torna-se para a direita, encolhe-se, ignora a programação de horário do despertador, tenta adormecer, e ouve a maçaneta da porta destrancar..." << endl;
cout << "Tom Boyle, jornalista secundário do canal sete. Dia onze de Abril de dois mil e três. Maine:" << endl;
cout << " '— Os policiais de uma viatura da delegacia de Bangor relataram na madrugada desta sexta-feira assassinato à sangue frio no apartamento de Chloe Conway, jornalista mirim da NewsBang de vinte e três anos e grávida de um mês. Conforme as suspeitas dos médicos-legistas, o algoz de Chloe teria perfurado sua jugular com um caco de vidro. Este ao meu lado, é o delegado Bull, um dos descobridores desse terrível crime.'" << endl;
cout << " '— Nós... não tínhamos nada a fazer além de prestar condolências e orações para a alma dela... Quando chegamos ao apartamento, o sangue dela estava... grudento, e o rosto sem vida... que Deus proteja o nosso país.' " << endl;
cout << endl << "...FIM DE JOGO..." << endl;
cout << "Reinicie a aplicação para usufruir dos seus outros destinos. " << endl;
}
if (escolha==1) {
cout << endl << "Às quatro da madrugada do dia trinta e um de março de abril de dois mil e três, você desperta com o alarme penetrante do despertador em seus ouvidos. Anda para o banheiro para retocar a maquiagem e pentear o cabelo. Na fachada da NewsBang, Oliver, junto a dois homens e uma mulher de sobretudo, acena para você e grita, com as mãos em concha ao lado da boca:" << endl;
cout << "— Ei, garota, vamos dar uma voltinha?" << endl;
cout << "Você devolve o aceno e se aproxima dele e dos seus acompanhantes: Russus, Stephania e Josh." << endl;
cout << "— Há de irmos, senhoras e senhores! Não temos nada a perder! — Oliver abriga Stephania e Josh num abraço e aponta para a porta do motorista para Russus — Você dirige, grandão!" << endl;
cout << "A hora do nada, sua avó costumava se referir aos começos das manhãs. Você, Oliver, Stephania, Russus, Josh e a vã sprinter na qual haviam embarcado, atravessavam uma pista na hora do nada. As árvores e os tapetes de gramas que vos cercavam se camuflavam nas incertezas de um habitat de almas desorientadas. Segredos aparentavam viver nelas. Consumí-las dia-a-dia. Stephania, uma mulher gorducha de cintura larga e cabelo chanel, quebra sua hipnose com a Mão Natureza lhe cutucando o ombro direito do banco de trás." << endl;
cout << "— Você está legal, Chloe? — Ela te questiona." << endl;
cout << "— Sim, na medida do possível — Você reponde, presa às sombras que corriam pelas folhas, galhos e troncos." << endl;
cout << "— Ah bom — Respira ela, aliviada — Porque com os cortes salariais que terão mês que vem, não sei se explodo ou espero para ver. Quer dizer... Nunca se sbae, né?..." << endl;
cout << "As frases de Stephania se dispersam no ar como uma bolha de sabão que estoura. A...coisa... das florestas parecia estar se locomovendo para a pista com os braços felpudos e de três metros de comprimento, pernas similares as de um coelho e uma cabeça a qual os biólogos classificariam como a de um alce. Ela se anuncia esbarrando o tórax de uns quinhentos quilogramas na carcaça da vã." << endl;
cout << "— Mas que porra é essa? — Josh exclama dos bancos traseiros." << endl;
cout << "O volante foge dos dedos de Russus e, com as rodas e o peso da vã, capota. Você protege sua cabeça com os braços e ora para que tudo aquilo que está acontecendo não passasse de um pesadelo. A vã gira para fora da rua e se arrasta num morrinho de grama, de rodas e chassi para os ares." << endl;
cout << "— Caralho, caralho! — Soa a vagarosa voz fantasmagórica de Oliver, no banco do copiloto. Sua visão, embaçada, induz que ele estaria sacando um revólver do porta-luvas, ou tentando sacar." << endl;
cout << "A criatura, porém, raptura-o da vã e o som de ossos e músculos estralando repercutem de prontidão. A mesma infelicidade acontece com Russus, Stephania e Josh, em respectivo. Você, e os frangalhos de consciência que lhe restavam, fita os flancos e desconecta seu cinto de segurança. Cai no ex-tetp da vã e se arrasta para as portas-duplas da traseira dela. Sua respiração falha e o mundo borra feito um efeito psicodélico em espiral. Sobras de carne caem à sua esquerda. O sangue fresco delas pintam o gramado de um vermelho escarlate horrendo." << endl;
cout << "— Meu Deus! Meu Deus! — Você grita para Deus. O único salvador que poderia te oferecer uma mão para a terra do descanso eterno com ternura." << endl;
cout << "O braço da criatura invade a vã em sua porta-dupla traseira, agarra-te e joga você de costas para o solo. Seus músculos eletrificam de dor e a garganta implodia para gritar." << endl;
cout << "— Não, não! Merda, merda! Caralho! — Com os doloridos das suas pernas, você recua o corpo um centímetro — Por favor... — Fluídos vermelhos frescos escorriam da sua testa para se misturar às lágrimas e aos catarros." << endl;
cout << "A criatura se assemelha a um gárgula. Observando-te do cume do chassi. Os globos oculares brilhantes de um laranja-âmbar neon. Chifres enfeitados com sebo e lodo. Dentes ossudos manchados de sangue e encrustados de pedaços de pele dos seus colegas de escritório. Observando-te, como uma diversão, um hobbie. Ela desce da vã e vaga parcimoniosa para você, leve a cabeça dela à sua, e respira. Dois jatos de ar nublado das narinas." << endl;
cout << "— Deus,Deus, por favor... Cuide do Harold, cuide... A ti eu temo — Você sussurra nos pensamentos. Falha. Frágil." << endl;
cout << "O dedo indicador esquerdo da criatura, com uma pontiaguda e envergada unha preta embutida nele, move-se em direção a sua barriga e a cutuca. Como uma criança ansiosa deduzindo qual seria o seu presente de aniversário." << endl;
cout << "Você está ofegante, o coração descompassado. Órbitas oculares latejantes, e uma ânsia de vômito preocupante. Sujeita a quaisquer reviravoltas. Quaisquer alucinações." << endl;
cout << "A criatura abre a boca dela e de sua língua um eco se modula no ar:" << endl;
cout << "— Nunca mais...volte..." << endl;
cout << "Ela se tornou para a direita e voltou para o seu ambiente de breus e privacidade, paciente. Um camaleão adaptando a vossa pele para se camuflar no cenário. Preto, preto, e sumiço completo." << endl;
cout << "Você despenca sua cabeça na grama e aproveita a piedade dela para enfim respirar livre de ameaças. Você, a vã, e Savana, sua garotinha que viria a nascer em dois mil e quatro, pesando três quilos e aos prantos." << endl;
cout << endl << "...FIM DE JOGO..." << endl;
cout << "Reinicie a aplicação para usufruir dos seus outros destinos. " << endl;
}

}
if (escolha==2) {
cout << endl << "— Não, Oliver, não estou. Pode esquecer — Você menea um 'não' com a cabeça para ele." << endl;
cout << "Oliver caminha para a sua direção, em silêncio, os olhos te predando tal qual o tigre fita seu banquete da grama alta. A mídia tem os seus tubarões, e Oliver estava acostumado a aprender com eles. Tornara-se um deles." << endl;
cout << "— Oras, por quê? — Suas sobrancelhas e lábios franziram." << endl;
cout << "— Está brincando? Lewiston é um campo minado pronto para explodir — Você se levanta da cadeira e o encara — A droga de um campo minado, Oliver! Você não vê? É loucura!" << endl;
cout << "Oliver inspira e expira pesado, como quem precisava de oxigênio amenizado para sobreviver. Deposita as duas mãos em seus ombros e os massageia." << endl;
cout << "— Entendo em absoluto, tudo o que disse. Sabe — Ele abre as pálpebras, disposto a ser, ou soar, compreensivo — Também tenho as minhas merdas em casa. A Lucy descobriu um câncer de colo de útero a três meses e...Tenho de arrecadar o dinheiro dessa reportagem, senão..." << endl;
cout << endl << "1. Ceder..." << endl;
cout << "2. Persistir em abandonar o escritório..." << endl;
cin >> escolha;
if (escolha==2) {
cout << endl << "— Eu não preciso disso. De você, dessa porra de notícia ou dessa empresa — Você se torna de costas para ele e se move depressa para a porta de entrada e saída do escritório. põe sua mão na maçaneta e inspira fundo — Eu me viro... — Conclui, e a gira." << endl;
cout << "Passos enlouquecedores soam detrás da sua retaguarda e as mãos de Oliver, avantajadas e quebradiças, predem-lhe a boca, os olhos e o nariz." << endl;
cout << "— Não, não, mocinha, você ficará comigo! Uma pena a associação ter de demitir mais um ousadinho..." << endl;
cout << "Seus gritos disparam em vão. Eram onze horas e trinta minutos da noite. Apenas você e ele estavam trabalhando, naquele escritório de lâmpadas falhas e conotação antiquada. Marrom, desenhos imperiais, e fedido a aposentos abandonados. Oliver aperta suas vias respiratórias e lhe esvai a consciência. Você o golpeia, inútil, com socos de petulância instável e pisões errôneos nos pés dele. O mundo se encolhe, e encolhe." << endl;
cout << "Um quique de rodas no quebra-molas te acorda. Você está na traseira obscura de uma vã azul-marinho. Amarrada, nos membros e na boca. Lágrimas escorrem dos seus olhos e poças de catarro implodiam das narinas para o lenço que alguém amarrara em sua boca." << endl;
cout << "— Você acredita que aquela puta quase me mordeu? — A voz de Oliver comenta para o seu parceiro, ou o motorista, ou para si mesmo — Porra, que caralho... Essa merda de usina está dando um trabalho desgraçado. Que merda." << endl;
cout << "Em cerca de uma hora ou duas. A vã estaciona, as portas dos bancos frontais dela abrem e você escuta solas de sapatos atritando no concreto molhado. Oliver destranca e puxa as portas-duplas de onde você deitava, fita-te, e torna os olhos para um homem que vestia um moletom preto com capuz acoplado no pescoço." << endl;
cout << "— Pegue ela, que eu cuido do resto — Ele saca um cigarro e um isqueiro prata límpido do bolso de peito da camisa social e se encaminha para fora do seu campo de visão das portas abertas." << endl;
cout << "O homem de casaco salta para a caçamba e ela balança hesitante convosco. Você tenta exprimir seus pensamentos, seus medos. 'Quem é você?'. 'O que está fazendo?'... e falha. Ele te carrega no ombro direito e te joga rente a uma parede de tijolos cinzentos e úmido." << endl;
cout << "— Permita que eu finalize essa garotinha mal-criada para você, Russus — Oliver contornou Russus, o seu amontoado de músculos coautor, o homem encapuzado...o segundo cúmplice direto do seu assassinato." << endl;
cout << "Oliver aponta o cano da revólver de pressão preto quatro ponto cinco dele para o seu estirado corpo, e dispara cinco rajadas. Duas no pescoço e no peito, e uma no rosto." << endl;
cout << endl << "...FIM DE JOGO..." << endl;
cout << "Reinicie a aplicação para usufruir dos seus outros destinos. " << endl;
}
if (escolha==1) {
cout << endl << "— Tudo bem, tudo bem! — Você o interrompe, incomodada. Sua consciência apita alertas vermelhos no breu de um palco teatral." << endl;
cout << "Oliver sorri nos cantos dos lábios e relembra:" << endl;
cout << "— Amanhã, às quatro. Tudo bem?" << endl;
cout << "Você meneia um 'sim' com a cabeça." << endl;
cout << "Sem problemas. Até lá..." << endl;
cout << "Ele te abraça e, cuidadoso, estapeia sua bochecha esquerda duas vezes." << endl;
cout << "— Esta é a minha jóia." << endl;
cout << "Oliver beija sua testa e sai do escritório" << endl;
cout << endl << "Em seu apartamento de trinta metros quadrados, às onze horas da noite, você está sozinha. Escuta os seus batimentos cardíacos acelerados e o sangue fluindo nas veias. O ventilador roía rodopiando no teto. As luzes, resumidas a uma luminária que se avizinhava à esquerda do sofá, onde suas costas e pernas se deitavam, tendiam a uma hora se apagarem para sempre. A vossa frequência estava inconstante. Um sincero sentimento seu clama uma última travessura de Chloe Conway. Uma fuga." << endl;
cout << endl << "1. Eu tenho de ir para a viagem..." << endl;
cout << "2. Nem fodendo..." << endl;
cin >> escolha;
if (escolha==2) {
cout << endl << "— Nem se me pagassem. Toda família tem uma mãe... — Você acaricia sua barriga, torna-se para a direita, encolhe-se, ignora a programação de horário do despertador, tenta adormecer, e ouve a maçaneta da porta destrancar..." << endl;
cout << "Tom Boyle, jornalista secundário do canal sete. Dia onze de Abril de dois mil e três. Maine:" << endl;
cout << " '— Os policiais de uma viatura da delegacia de Bangor relataram na madrugada desta sexta-feira assassinato à sangue frio no apartamento de Chloe Conway, jornalista mirim da NewsBang de vinte e três anos e grávida de um mês. Conforme as suspeitas dos médicos-legistas, o algoz de Chloe teria perfurado sua jugular com um caco de vidro. Este ao meu lado, é o delegado Bull, um dos descobridores desse terrível crime.'" << endl;
cout << " '— Nós... não tínhamos nada a fazer além de prestar condolências e orações para a alma dela... Quando chegamos ao apartamento, o sangue dela estava... grudento, e o rosto sem vida... que Deus proteja o nosso país.' " << endl;
cout << endl << "...FIM DE JOGO..." << endl;
cout << "Reinicie a aplicação para usufruir dos seus outros destinos. " << endl;
}
if (escolha==1) {
cout << endl << "Às quatro da madrugada do dia trinta e um de março de abril de dois mil e três, você desperta com o alarme penetrante do despertador em seus ouvidos. Anda para o banheiro para retocar a maquiagem e pentear o cabelo. Na fachada da NewsBang, Oliver, junto a dois homens e uma mulher de sobretudo, acena para você e grita, com as mãos em concha ao lado da boca:" << endl;
cout << "— Ei, garota, vamos dar uma voltinha?" << endl;
cout << "Você devolve o aceno e se aproxima dele e dos seus acompanhantes: Russus, Stephania e Josh." << endl;
cout << "— Há de irmos, senhoras e senhores! Não temos nada a perder! — Oliver abriga Stephania e Josh num abraço e aponta para a porta do motorista para Russus — Você dirige, grandão!" << endl;
cout << "A hora do nada, sua avó costumava se referir aos começos das manhãs. Você, Oliver, Stephania, Russus, Josh e a vã sprinter na qual haviam embarcado, atravessavam uma pista na hora do nada. As árvores e os tapetes de gramas que vos cercavam se camuflavam nas incertezas de um habitat de almas desorientadas. Segredos aparentavam viver nelas. Consumí-las dia-a-dia. Stephania, uma mulher gorducha de cintura larga e cabelo chanel, quebra sua hipnose com a Mão Natureza lhe cutucando o ombro direito do banco de trás." << endl;
cout << "— Você está legal, Chloe? — Ela te questiona." << endl;
cout << "— Sim, na medida do possível — Você reponde, presa às sombras que corriam pelas folhas, galhos e troncos." << endl;
cout << "— Ah bom — Respira ela, aliviada — Porque com os cortes salariais que terão mês que vem, não sei se explodo ou espero para ver. Quer dizer... Nunca se sbae, né?..." << endl;
cout << "As frases de Stephania se dispersam no ar como uma bolha de sabão que estoura. A...coisa... das florestas parecia estar se locomovendo para a pista com os braços felpudos e de três metros de comprimento, pernas similares as de um coelho e uma cabeça a qual os biólogos classificariam como a de um alce. Ela se anuncia esbarrando o tórax de uns quinhentos quilogramas na carcaça da vã." << endl;
cout << "— Mas que porra é essa? — Josh exclama dos bancos traseiros." << endl;
cout << "O volante foge dos dedos de Russus e, com as rodas e o peso da vã, capota. Você protege sua cabeça com os braços e ora para que tudo aquilo que está acontecendo não passasse de um pesadelo. A vã gira para fora da rua e se arrasta num morrinho de grama, de rodas e chassi para os ares." << endl;
cout << "— Caralho, caralho! — Soa a vagarosa voz fantasmagórica de Oliver, no banco do copiloto. Sua visão, embaçada, induz que ele estaria sacando um revólver do porta-luvas, ou tentando sacar." << endl;
cout << "A criatura, porém, raptura-o da vã e o som de ossos e músculos estralando repercutem de prontidão. A mesma infelicidade acontece com Russus, Stephania e Josh, em respectivo. Você, e os frangalhos de consciência que lhe restavam, fita os flancos e desconecta seu cinto de segurança. Cai no ex-tetp da vã e se arrasta para as portas-duplas da traseira dela. Sua respiração falha e o mundo borra feito um efeito psicodélico em espiral. Sobras de carne caem à sua esquerda. O sangue fresco delas pintam o gramado de um vermelho escarlate horrendo." << endl;
cout << "— Meu Deus! Meu Deus! — Você grita para Deus. O único salvador que poderia te oferecer uma mão para a terra do descanso eterno com ternura." << endl;
cout << "O braço da criatura invade a vã em sua porta-dupla traseira, agarra-te e joga você de costas para o solo. Seus músculos eletrificam de dor e a garganta implodia para gritar." << endl;
cout << "— Não, não! Merda, merda! Caralho! — Com os doloridos das suas pernas, você recua o corpo um centímetro — Por favor... — Fluídos vermelhos frescos escorriam da sua testa para se misturar às lágrimas e aos catarros." << endl;
cout << "A criatura se assemelha a um gárgula. Observando-te do cume do chassi. Os globos oculares brilhantes de um laranja-âmbar neon. Chifres enfeitados com sebo e lodo. Dentes ossudos manchados de sangue e encrustados de pedaços de pele dos seus colegas de escritório. Observando-te, como uma diversão, um hobbie. Ela desce da vã e vaga parcimoniosa para você, leve a cabeça dela à sua, e respira. Dois jatos de ar nublado das narinas." << endl;
cout << "— Deus,Deus, por favor... Cuide do Harold, cuide... A ti eu temo — Você sussurra nos pensamentos. Falha. Frágil." << endl;
cout << "O dedo indicador esquerdo da criatura, com uma pontiaguda e envergada unha preta embutida nele, move-se em direção a sua barriga e a cutuca. Como uma criança ansiosa deduzindo qual seria o seu presente de aniversário." << endl;
cout << "Você está ofegante, o coração descompassado. Órbitas oculares latejantes, e uma ânsia de vômito preocupante. Sujeita a quaisquer reviravoltas. Quaisquer alucinações." << endl;
cout << "A criatura abre a boca dela e de sua língua um eco se modula no ar:" << endl;
cout << "— Nunca mais...volte..." << endl;
cout << "Ela se tornou para a direita e voltou para o seu ambiente de breus e privacidade, paciente. Um camaleão adaptando a vossa pele para se camuflar no cenário. Preto, preto, e sumiço completo." << endl;
cout << "Você despenca sua cabeça na grama e aproveita a piedade dela para enfim respirar livre de ameaças. Você, a vã, e Savana, sua garotinha que viria a nascer em dois mil e quatro, pesando três quilos e aos prantos." << endl;
cout << endl << "...FIM DE JOGO..." << endl;
cout << "Reinicie a aplicação para usufruir dos seus outros destinos. " << endl;
}
}

}
}
}
if (escolha==1) {
cout << endl << "— Tanto faz. Desde que você tome essa coisa rápido... — Um pressentimento de vômito ronda a sua garganta. Latejos tilintantes batucam em seu cérebro, repetitivos. Desincronizados." << endl;
cout << "Oliver sorri e ingere o café te fitando, como um palhaço que se mantém no personagem para satisfazer os seus pagantes" << endl;
cout << "— Devo interpretar isso como 'sim'?" << endl;
cout << endl << "1. Talvez..." << endl;
cout << "2. Er, né. Fazer o quê?" << endl;
cin >> escolha;
if (escolha==1) {
cout << endl << "— Talvez, quem sabe. Ainda tenho muitas dúvidas em relação a esse trabalho em Lewiston... — Você cruza os braços e o encara" << endl;
cout << "— Bom — De novo, Oliver se levanta da cadeira e apoia a cintura numa tábua de plástico que separava as cabines do escritório — A gente visita rapidinho a usina de lá, coleta umas informações e mete o pé. Simples — Dá de ombros." << endl;
cout << "— Ai, caramba... Quando que nós partiremos?" << endl;
cout << "— Amanhã, às quatro da manhã. Alvorada completa! Haha! — Ele balançou os braços em comemoração." << endl;
cout << endl << "Em seu apartamento de trinta metros quadrados, às onze horas da noite, você está sozinha. Escuta os seus batimentos cardíacos acelerados e o sangue fluindo nas veias. O ventilador roía rodopiando no teto. As luzes, resumidas a uma luminária que se avizinhava à esquerda do sofá, onde suas costas e pernas se deitavam, tendiam a uma hora se apagarem para sempre. A vossa frequência estava inconstante. Um sincero sentimento seu clama uma última travessura de Chloe Conway. Uma fuga." << endl;
cout << endl << "1. Eu tenho de ir para a viagem..." << endl;
cout << "2. Nem fodendo..." << endl;
cin >> escolha;
if (escolha==2) {
cout << endl << "— Nem se me pagassem. Toda família tem uma mãe... — Você acaricia sua barriga, torna-se para a direita, encolhe-se, ignora a programação de horário do despertador, tenta adormecer, e ouve a maçaneta da porta destrancar..." << endl;
cout << "Tom Boyle, jornalista secundário do canal sete. Dia onze de Abril de dois mil e três. Maine:" << endl;
cout << " '— Os policiais de uma viatura da delegacia de Bangor relataram na madrugada desta sexta-feira assassinato à sangue frio no apartamento de Chloe Conway, jornalista mirim da NewsBang de vinte e três anos e grávida de um mês. Conforme as suspeitas dos médicos-legistas, o algoz de Chloe teria perfurado sua jugular com um caco de vidro. Este ao meu lado, é o delegado Bull, um dos descobridores desse terrível crime.'" << endl;
cout << " '— Nós... não tínhamos nada a fazer além de prestar condolências e orações para a alma dela... Quando chegamos ao apartamento, o sangue dela estava... grudento, e o rosto sem vida... que Deus proteja o nosso país.' " << endl;
cout << endl << "...FIM DE JOGO..." << endl;
cout << "Reinicie a aplicação para usufruir dos seus outros destinos. " << endl;
}
if (escolha==1) {
cout << endl << "Às quatro da madrugada do dia trinta e um de março de abril de dois mil e três, você desperta com o alarme penetrante do despertador em seus ouvidos. Anda para o banheiro para retocar a maquiagem e pentear o cabelo. Na fachada da NewsBang, Oliver, junto a dois homens e uma mulher de sobretudo, acena para você e grita, com as mãos em concha ao lado da boca:" << endl;
cout << "— Ei, garota, vamos dar uma voltinha?" << endl;
cout << "Você devolve o aceno e se aproxima dele e dos seus acompanhantes: Russus, Stephania e Josh." << endl;
cout << "— Há de irmos, senhoras e senhores! Não temos nada a perder! — Oliver abriga Stephania e Josh num abraço e aponta para a porta do motorista para Russus — Você dirige, grandão!" << endl;
cout << "A hora do nada, sua avó costumava se referir aos começos das manhãs. Você, Oliver, Stephania, Russus, Josh e a vã sprinter na qual haviam embarcado, atravessavam uma pista na hora do nada. As árvores e os tapetes de gramas que vos cercavam se camuflavam nas incertezas de um habitat de almas desorientadas. Segredos aparentavam viver nelas. Consumí-las dia-a-dia. Stephania, uma mulher gorducha de cintura larga e cabelo chanel, quebra sua hipnose com a Mão Natureza lhe cutucando o ombro direito do banco de trás." << endl;
cout << "— Você está legal, Chloe? — Ela te questiona." << endl;
cout << "— Sim, na medida do possível — Você reponde, presa às sombras que corriam pelas folhas, galhos e troncos." << endl;
cout << "— Ah bom — Respira ela, aliviada — Porque com os cortes salariais que terão mês que vem, não sei se explodo ou espero para ver. Quer dizer... Nunca se sbae, né?..." << endl;
cout << "As frases de Stephania se dispersam no ar como uma bolha de sabão que estoura. A...coisa... das florestas parecia estar se locomovendo para a pista com os braços felpudos e de três metros de comprimento, pernas similares as de um coelho e uma cabeça a qual os biólogos classificariam como a de um alce. Ela se anuncia esbarrando o tórax de uns quinhentos quilogramas na carcaça da vã." << endl;
cout << "— Mas que porra é essa? — Josh exclama dos bancos traseiros." << endl;
cout << "O volante foge dos dedos de Russus e, com as rodas e o peso da vã, capota. Você protege sua cabeça com os braços e ora para que tudo aquilo que está acontecendo não passasse de um pesadelo. A vã gira para fora da rua e se arrasta num morrinho de grama, de rodas e chassi para os ares." << endl;
cout << "— Caralho, caralho! — Soa a vagarosa voz fantasmagórica de Oliver, no banco do copiloto. Sua visão, embaçada, induz que ele estaria sacando um revólver do porta-luvas, ou tentando sacar." << endl;
cout << "A criatura, porém, raptura-o da vã e o som de ossos e músculos estralando repercutem de prontidão. A mesma infelicidade acontece com Russus, Stephania e Josh, em respectivo. Você, e os frangalhos de consciência que lhe restavam, fita os flancos e desconecta seu cinto de segurança. Cai no ex-tetp da vã e se arrasta para as portas-duplas da traseira dela. Sua respiração falha e o mundo borra feito um efeito psicodélico em espiral. Sobras de carne caem à sua esquerda. O sangue fresco delas pintam o gramado de um vermelho escarlate horrendo." << endl;
cout << "— Meu Deus! Meu Deus! — Você grita para Deus. O único salvador que poderia te oferecer uma mão para a terra do descanso eterno com ternura." << endl;
cout << "O braço da criatura invade a vã em sua porta-dupla traseira, agarra-te e joga você de costas para o solo. Seus músculos eletrificam de dor e a garganta implodia para gritar." << endl;
cout << "— Não, não! Merda, merda! Caralho! — Com os doloridos das suas pernas, você recua o corpo um centímetro — Por favor... — Fluídos vermelhos frescos escorriam da sua testa para se misturar às lágrimas e aos catarros." << endl;
cout << "A criatura se assemelha a um gárgula. Observando-te do cume do chassi. Os globos oculares brilhantes de um laranja-âmbar neon. Chifres enfeitados com sebo e lodo. Dentes ossudos manchados de sangue e encrustados de pedaços de pele dos seus colegas de escritório. Observando-te, como uma diversão, um hobbie. Ela desce da vã e vaga parcimoniosa para você, leve a cabeça dela à sua, e respira. Dois jatos de ar nublado das narinas." << endl;
cout << "— Deus,Deus, por favor... Cuide do Harold, cuide... A ti eu temo — Você sussurra nos pensamentos. Falha. Frágil." << endl;
cout << "O dedo indicador esquerdo da criatura, com uma pontiaguda e envergada unha preta embutida nele, move-se em direção a sua barriga e a cutuca. Como uma criança ansiosa deduzindo qual seria o seu presente de aniversário." << endl;
cout << "Você está ofegante, o coração descompassado. Órbitas oculares latejantes, e uma ânsia de vômito preocupante. Sujeita a quaisquer reviravoltas. Quaisquer alucinações." << endl;
cout << "A criatura abre a boca dela e de sua língua um eco se modula no ar:" << endl;
cout << "— Nunca mais...volte..." << endl;
cout << "Ela se tornou para a direita e voltou para o seu ambiente de breus e privacidade, paciente. Um camaleão adaptando a vossa pele para se camuflar no cenário. Preto, preto, e sumiço completo." << endl;
cout << "Você despenca sua cabeça na grama e aproveita a piedade dela para enfim respirar livre de ameaças. Você, a vã, e Savana, sua garotinha que viria a nascer em dois mil e quatro, pesando três quilos e aos prantos." << endl;
cout << endl << "...FIM DE JOGO..." << endl;
cout << "Reinicie a aplicação para usufruir dos seus outros destinos. " << endl;
}
}
if (escolha==2) {
cout << endl << "— Er, né. Fazer o que, né? — Você dá de ombros e cede." << endl;
cout << "— Te vejo amanhã, às quatro. Okay? — Ele aponta para o seu peito, animado." << endl;
cout << endl << "1. Sim..." << endl;
cout << endl << "2. Não..." << endl;
cin >> escolha;
if (escolha==1) {
cout << "— Sim, sim... Amanhã, às quatro." << endl;
cout << "Oliver vira seu copo e o joga numa lata de lixo à esquerda dos pés dele." << endl;
cout << "— Belíssima escolha, querida. Tenha uma boa noite, e até amanhã — Ele acaricia o seu ombro direito e sai da sala." << endl;
cout << endl << "Em seu apartamento de trinta metros quadrados, às onze horas da noite, você está sozinha. Escuta os seus batimentos cardíacos acelerados e o sangue fluindo nas veias. O ventilador roía rodopiando no teto. As luzes, resumidas a uma luminária que se avizinhava à esquerda do sofá, onde suas costas e pernas se deitavam, tendiam a uma hora se apagarem para sempre. A vossa frequência estava inconstante. Um sincero sentimento seu clama uma última travessura de Chloe Conway. Uma fuga." << endl;
cout << endl << "1. Eu tenho de ir para a viagem..." << endl;
cout << "2. Nem fodendo..." << endl;
cin >> escolha;
if (escolha==2) {
cout << endl << "— Nem se me pagassem. Toda família tem uma mãe... — Você acaricia sua barriga, torna-se para a direita, encolhe-se, ignora a programação de horário do despertador, tenta adormecer, e ouve a maçaneta da porta destrancar..." << endl;
cout << "Tom Boyle, jornalista secundário do canal sete. Dia onze de Abril de dois mil e três. Maine:" << endl;
cout << " '— Os policiais de uma viatura da delegacia de Bangor relataram na madrugada desta sexta-feira assassinato à sangue frio no apartamento de Chloe Conway, jornalista mirim da NewsBang de vinte e três anos e grávida de um mês. Conforme as suspeitas dos médicos-legistas, o algoz de Chloe teria perfurado sua jugular com um caco de vidro. Este ao meu lado, é o delegado Bull, um dos descobridores desse terrível crime.'" << endl;
cout << " '— Nós... não tínhamos nada a fazer além de prestar condolências e orações para a alma dela... Quando chegamos ao apartamento, o sangue dela estava... grudento, e o rosto sem vida... que Deus proteja o nosso país.' " << endl;
cout << endl << "...FIM DE JOGO..." << endl;
cout << "Reinicie a aplicação para usufruir dos seus outros destinos. " << endl;
}
if (escolha==1) {
cout << endl << "Às quatro da madrugada do dia trinta e um de março de abril de dois mil e três, você desperta com o alarme penetrante do despertador em seus ouvidos. Anda para o banheiro para retocar a maquiagem e pentear o cabelo. Na fachada da NewsBang, Oliver, junto a dois homens e uma mulher de sobretudo, acena para você e grita, com as mãos em concha ao lado da boca:" << endl;
cout << "— Ei, garota, vamos dar uma voltinha?" << endl;
cout << "Você devolve o aceno e se aproxima dele e dos seus acompanhantes: Russus, Stephania e Josh." << endl;
cout << "— Há de irmos, senhoras e senhores! Não temos nada a perder! — Oliver abriga Stephania e Josh num abraço e aponta para a porta do motorista para Russus — Você dirige, grandão!" << endl;
cout << "A hora do nada, sua avó costumava se referir aos começos das manhãs. Você, Oliver, Stephania, Russus, Josh e a vã sprinter na qual haviam embarcado, atravessavam uma pista na hora do nada. As árvores e os tapetes de gramas que vos cercavam se camuflavam nas incertezas de um habitat de almas desorientadas. Segredos aparentavam viver nelas. Consumí-las dia-a-dia. Stephania, uma mulher gorducha de cintura larga e cabelo chanel, quebra sua hipnose com a Mão Natureza lhe cutucando o ombro direito do banco de trás." << endl;
cout << "— Você está legal, Chloe? — Ela te questiona." << endl;
cout << "— Sim, na medida do possível — Você reponde, presa às sombras que corriam pelas folhas, galhos e troncos." << endl;
cout << "— Ah bom — Respira ela, aliviada — Porque com os cortes salariais que terão mês que vem, não sei se explodo ou espero para ver. Quer dizer... Nunca se sbae, né?..." << endl;
cout << "As frases de Stephania se dispersam no ar como uma bolha de sabão que estoura. A...coisa... das florestas parecia estar se locomovendo para a pista com os braços felpudos e de três metros de comprimento, pernas similares as de um coelho e uma cabeça a qual os biólogos classificariam como a de um alce. Ela se anuncia esbarrando o tórax de uns quinhentos quilogramas na carcaça da vã." << endl;
cout << "— Mas que porra é essa? — Josh exclama dos bancos traseiros." << endl;
cout << "O volante foge dos dedos de Russus e, com as rodas e o peso da vã, capota. Você protege sua cabeça com os braços e ora para que tudo aquilo que está acontecendo não passasse de um pesadelo. A vã gira para fora da rua e se arrasta num morrinho de grama, de rodas e chassi para os ares." << endl;
cout << "— Caralho, caralho! — Soa a vagarosa voz fantasmagórica de Oliver, no banco do copiloto. Sua visão, embaçada, induz que ele estaria sacando um revólver do porta-luvas, ou tentando sacar." << endl;
cout << "A criatura, porém, raptura-o da vã e o som de ossos e músculos estralando repercutem de prontidão. A mesma infelicidade acontece com Russus, Stephania e Josh, em respectivo. Você, e os frangalhos de consciência que lhe restavam, fita os flancos e desconecta seu cinto de segurança. Cai no ex-tetp da vã e se arrasta para as portas-duplas da traseira dela. Sua respiração falha e o mundo borra feito um efeito psicodélico em espiral. Sobras de carne caem à sua esquerda. O sangue fresco delas pintam o gramado de um vermelho escarlate horrendo." << endl;
cout << "— Meu Deus! Meu Deus! — Você grita para Deus. O único salvador que poderia te oferecer uma mão para a terra do descanso eterno com ternura." << endl;
cout << "O braço da criatura invade a vã em sua porta-dupla traseira, agarra-te e joga você de costas para o solo. Seus músculos eletrificam de dor e a garganta implodia para gritar." << endl;
cout << "— Não, não! Merda, merda! Caralho! — Com os doloridos das suas pernas, você recua o corpo um centímetro — Por favor... — Fluídos vermelhos frescos escorriam da sua testa para se misturar às lágrimas e aos catarros." << endl;
cout << "A criatura se assemelha a um gárgula. Observando-te do cume do chassi. Os globos oculares brilhantes de um laranja-âmbar neon. Chifres enfeitados com sebo e lodo. Dentes ossudos manchados de sangue e encrustados de pedaços de pele dos seus colegas de escritório. Observando-te, como uma diversão, um hobbie. Ela desce da vã e vaga parcimoniosa para você, leve a cabeça dela à sua, e respira. Dois jatos de ar nublado das narinas." << endl;
cout << "— Deus,Deus, por favor... Cuide do Harold, cuide... A ti eu temo — Você sussurra nos pensamentos. Falha. Frágil." << endl;
cout << "O dedo indicador esquerdo da criatura, com uma pontiaguda e envergada unha preta embutida nele, move-se em direção a sua barriga e a cutuca. Como uma criança ansiosa deduzindo qual seria o seu presente de aniversário." << endl;
cout << "Você está ofegante, o coração descompassado. Órbitas oculares latejantes, e uma ânsia de vômito preocupante. Sujeita a quaisquer reviravoltas. Quaisquer alucinações." << endl;
cout << "A criatura abre a boca dela e de sua língua um eco se modula no ar:" << endl;
cout << "— Nunca mais...volte..." << endl;
cout << "Ela se tornou para a direita e voltou para o seu ambiente de breus e privacidade, paciente. Um camaleão adaptando a vossa pele para se camuflar no cenário. Preto, preto, e sumiço completo." << endl;
cout << "Você despenca sua cabeça na grama e aproveita a piedade dela para enfim respirar livre de ameaças. Você, a vã, e Savana, sua garotinha que viria a nascer em dois mil e quatro, pesando três quilos e aos prantos." << endl;
cout << endl << "...FIM DE JOGO..." << endl;
cout << "Reinicie a aplicação para usufruir dos seus outros destinos. " << endl;
}
}
if (escolha==2) {
cout << endl << "Você reflete. Considera os valores que te resultaram uma encruzilhada. Valia o risco se arriscar, arriscar sua vida para uma matéria perigosa? Lewiston transpirava maldições. Terras baldias cujos moradores impulsionavam seus visitantes para longe com ambientes hostis e sopros ácidos que lhe infectariam o âmago." << endl;
cout << "— Não, Oliver, não posso fazer isso. É loucura, nós dois sabemos disso. Sobretudo você, que vive ao lado do chefe." << endl;
cout << "Oliver deposita o copo de café na escrivaninha dele. Sua fumaça subia e desaparecia. Constante, e enjoativa." << endl;
cout << "— Caramba, Chloe. Você não fará isso comigo, né? Nunca faria conosco. Com essa empresa — Espande seus braços para os lados." << endl;
cout << "1. Persistir..." << endl;
cout << "2. Ceder..." << endl;
cin >> escolha;
if (escolha==1) {
cout << endl << "— Eu disse que não... — Você responde, firme. Convicta." << endl;
cout << "Oliver caminha para a sua direção, em silêncio, os olhos te predando tal qual o tigre fita seu banquete da grama alta. A mídia tem os seus tubarões, e Oliver estava acostumado a aprender com eles. Tornar-se um deles." << endl;
cout << "— Oras, por quê? — Suas sobrancelhas e lábios franziram." << endl;
cout << "— Está brincando? Lewiston é um campo minado pronto para explodir — Você se levanta da cadeira e o encara — A droga de um campo minado, Oliver! Você não vê? É loucura!" << endl;
cout << "Oliver inspira e expira pesado, como quem precisava de oxigênio amenizado para sobreviver. Deposita as duas mãos em seus ombros e os massageia." << endl;
cout << "— Entendo em absoluto, tudo o que disse. Sabe — Ele abre as pálpebras, disposto a ser, ou soar, compreensivo — Também tenho as minhas merdas em casa. A Lucy descobriu um câncer de colo de útero a três meses e...Tenho de arrecadar o dinheiro dessa reportagem, senão..." << endl;
cout << endl << "1. Ceder..." << endl;
cout << "2. Persistir em abandonar o escritório..." << endl;
cin >> escolha;
if (escolha==2) {
cout << endl << "— Eu não preciso disso. De você, dessa porra de notícia ou dessa empresa — Você se torna de costas para ele e se move depressa para a porta de entrada e saída do escritório. põe sua mão na maçaneta e inspira fundo — Eu me viro... — Conclui, e a gira." << endl;
cout << "Passos enlouquecedores soam detrás da sua retaguarda e as mãos de Oliver, avantajadas e quebradiças, predem-lhe a boca, os olhos e o nariz." << endl;
cout << "— Não, não, mocinha, você ficará comigo! Uma pena a associação ter de demitir mais um ousadinho..." << endl;
cout << "Seus gritos disparam em vão. Eram onze horas e trinta minutos da noite. Apenas você e ele estavam trabalhando, naquele escritório de lâmpadas falhas e conotação antiquada. Marrom, desenhos imperiais, e fedido a aposentos abandonados. Oliver aperta suas vias respiratórias e lhe esvai a consciência. Você o golpeia, inútil, com socos de petulância instável e pisões errôneos nos pés dele. O mundo se encolhe, e encolhe." << endl;
cout << "Um quique de rodas no quebra-molas te acorda. Você está na traseira obscura de uma vã azul-marinho. Amarrada, nos membros e na boca. Lágrimas escorrem dos seus olhos e poças de catarro implodiam das narinas para o lenço que alguém amarrara em sua boca." << endl;
cout << "— Você acredita que aquela puta quase me mordeu? — A voz de Oliver comenta para o seu parceiro, ou o motorista, ou para si mesmo — Porra, que caralho... Essa merda de usina está dando um trabalho desgraçado. Que merda." << endl;
cout << "Em cerca de uma hora ou duas. A vã estaciona, as portas dos bancos frontais dela abrem e você escuta solas de sapatos atritando no concreto molhado. Oliver destranca e puxa as portas-duplas de onde você deitava, fita-te, e torna os olhos para um homem que vestia um moletom preto com capuz acoplado no pescoço." << endl;
cout << "— Pegue ela, que eu cuido do resto — Ele saca um cigarro e um isqueiro prata límpido do bolso de peito da camisa social e se encaminha para fora do seu campo de visão das portas abertas." << endl;
cout << "O homem de casaco salta para a caçamba e ela balança hesitante convosco. Você tenta exprimir seus pensamentos, seus medos. 'Quem é você?'. 'O que está fazendo?'... e falha. Ele te carrega no ombro direito e te joga rente a uma parede de tijolos cinzentos e úmido." << endl;
cout << "— Permita que eu finalize essa garotinha mal-criada para você, Russus — Oliver contornou Russus, o seu amontoado de músculos coautor, o homem encapuzado...o segundo cúmplice direto do seu assassinato." << endl;
cout << "Oliver aponta o cano da revólver de pressão preto quatro ponto cinco dele para o seu estirado corpo, e dispara cinco rajadas. Duas no pescoço e no peito, e uma no rosto." << endl;
cout << endl << "...FIM DE JOGO..." << endl;
cout << "Reinicie a aplicação para usufruir dos seus outros destinos. " << endl;
}
if (escolha==1) {
cout << endl << "— Tudo bem, tudo bem! — Você o interrompe, incomodada. Sua consciência apita alertas vermelhos no breu de um palco teatral." << endl;
cout << "Oliver sorri nos cantos dos lábios e relembra:" << endl;
cout << "— Amanhã, às quatro. Tudo bem?" << endl;
cout << "Você meneia um 'sim' com a cabeça." << endl;
cout << "Sem problemas. Até lá..." << endl;
cout << "Ele te abraça e, cuidadoso, estapeia sua bochecha esquerda duas vezes." << endl;
cout << "— Esta é a minha jóia." << endl;
cout << "Oliver beija sua testa e sai do escritório" << endl;
cout << endl << "Em seu apartamento de trinta metros quadrados, às onze horas da noite, você está sozinha. Escuta os seus batimentos cardíacos acelerados e o sangue fluindo nas veias. O ventilador roía rodopiando no teto. As luzes, resumidas a uma luminária que se avizinhava à esquerda do sofá, onde suas costas e pernas se deitavam, tendiam a uma hora se apagarem para sempre. A vossa frequência estava inconstante. Um sincero sentimento seu clama uma última travessura de Chloe Conway. Uma fuga." << endl;
cout << endl << "1. Eu tenho de ir para a viagem..." << endl;
cout << "2. Nem fodendo..." << endl;
cin >> escolha;
if (escolha==2) {
cout << endl << "— Nem se me pagassem. Toda família tem uma mãe... — Você acaricia sua barriga, torna-se para a direita, encolhe-se, ignora a programação de horário do despertador, tenta adormecer, e ouve a maçaneta da porta destrancar..." << endl;
cout << "Tom Boyle, jornalista secundário do canal sete. Dia onze de Abril de dois mil e três. Maine:" << endl;
cout << " '— Os policiais de uma viatura da delegacia de Bangor relataram na madrugada desta sexta-feira assassinato à sangue frio no apartamento de Chloe Conway, jornalista mirim da NewsBang de vinte e três anos e grávida de um mês. Conforme as suspeitas dos médicos-legistas, o algoz de Chloe teria perfurado sua jugular com um caco de vidro. Este ao meu lado, é o delegado Bull, um dos descobridores desse terrível crime.'" << endl;
cout << " '— Nós... não tínhamos nada a fazer além de prestar condolências e orações para a alma dela... Quando chegamos ao apartamento, o sangue dela estava... grudento, e o rosto sem vida... que Deus proteja o nosso país.' " << endl;
cout << endl << "...FIM DE JOGO..." << endl;
cout << "Reinicie a aplicação para usufruir dos seus outros destinos. " << endl;
}
if (escolha==1) {
cout << endl << "Às quatro da madrugada do dia trinta e um de março de abril de dois mil e três, você desperta com o alarme penetrante do despertador em seus ouvidos. Anda para o banheiro para retocar a maquiagem e pentear o cabelo. Na fachada da NewsBang, Oliver, junto a dois homens e uma mulher de sobretudo, acena para você e grita, com as mãos em concha ao lado da boca:" << endl;
cout << "— Ei, garota, vamos dar uma voltinha?" << endl;
cout << "Você devolve o aceno e se aproxima dele e dos seus acompanhantes: Russus, Stephania e Josh." << endl;
cout << "— Há de irmos, senhoras e senhores! Não temos nada a perder! — Oliver abriga Stephania e Josh num abraço e aponta para a porta do motorista para Russus — Você dirige, grandão!" << endl;
cout << "A hora do nada, sua avó costumava se referir aos começos das manhãs. Você, Oliver, Stephania, Russus, Josh e a vã sprinter na qual haviam embarcado, atravessavam uma pista na hora do nada. As árvores e os tapetes de gramas que vos cercavam se camuflavam nas incertezas de um habitat de almas desorientadas. Segredos aparentavam viver nelas. Consumí-las dia-a-dia. Stephania, uma mulher gorducha de cintura larga e cabelo chanel, quebra sua hipnose com a Mão Natureza lhe cutucando o ombro direito do banco de trás." << endl;
cout << "— Você está legal, Chloe? — Ela te questiona." << endl;
cout << "— Sim, na medida do possível — Você reponde, presa às sombras que corriam pelas folhas, galhos e troncos." << endl;
cout << "— Ah bom — Respira ela, aliviada — Porque com os cortes salariais que terão mês que vem, não sei se explodo ou espero para ver. Quer dizer... Nunca se sbae, né?..." << endl;
cout << "As frases de Stephania se dispersam no ar como uma bolha de sabão que estoura. A...coisa... das florestas parecia estar se locomovendo para a pista com os braços felpudos e de três metros de comprimento, pernas similares as de um coelho e uma cabeça a qual os biólogos classificariam como a de um alce. Ela se anuncia esbarrando o tórax de uns quinhentos quilogramas na carcaça da vã." << endl;
cout << "— Mas que porra é essa? — Josh exclama dos bancos traseiros." << endl;
cout << "O volante foge dos dedos de Russus e, com as rodas e o peso da vã, capota. Você protege sua cabeça com os braços e ora para que tudo aquilo que está acontecendo não passasse de um pesadelo. A vã gira para fora da rua e se arrasta num morrinho de grama, de rodas e chassi para os ares." << endl;
cout << "— Caralho, caralho! — Soa a vagarosa voz fantasmagórica de Oliver, no banco do copiloto. Sua visão, embaçada, induz que ele estaria sacando um revólver do porta-luvas, ou tentando sacar." << endl;
cout << "A criatura, porém, raptura-o da vã e o som de ossos e músculos estralando repercutem de prontidão. A mesma infelicidade acontece com Russus, Stephania e Josh, em respectivo. Você, e os frangalhos de consciência que lhe restavam, fita os flancos e desconecta seu cinto de segurança. Cai no ex-tetp da vã e se arrasta para as portas-duplas da traseira dela. Sua respiração falha e o mundo borra feito um efeito psicodélico em espiral. Sobras de carne caem à sua esquerda. O sangue fresco delas pintam o gramado de um vermelho escarlate horrendo." << endl;
cout << "— Meu Deus! Meu Deus! — Você grita para Deus. O único salvador que poderia te oferecer uma mão para a terra do descanso eterno com ternura." << endl;
cout << "O braço da criatura invade a vã em sua porta-dupla traseira, agarra-te e joga você de costas para o solo. Seus músculos eletrificam de dor e a garganta implodia para gritar." << endl;
cout << "— Não, não! Merda, merda! Caralho! — Com os doloridos das suas pernas, você recua o corpo um centímetro — Por favor... — Fluídos vermelhos frescos escorriam da sua testa para se misturar às lágrimas e aos catarros." << endl;
cout << "A criatura se assemelha a um gárgula. Observando-te do cume do chassi. Os globos oculares brilhantes de um laranja-âmbar neon. Chifres enfeitados com sebo e lodo. Dentes ossudos manchados de sangue e encrustados de pedaços de pele dos seus colegas de escritório. Observando-te, como uma diversão, um hobbie. Ela desce da vã e vaga parcimoniosa para você, leve a cabeça dela à sua, e respira. Dois jatos de ar nublado das narinas." << endl;
cout << "— Deus,Deus, por favor... Cuide do Harold, cuide... A ti eu temo — Você sussurra nos pensamentos. Falha. Frágil." << endl;
cout << "O dedo indicador esquerdo da criatura, com uma pontiaguda e envergada unha preta embutida nele, move-se em direção a sua barriga e a cutuca. Como uma criança ansiosa deduzindo qual seria o seu presente de aniversário." << endl;
cout << "Você está ofegante, o coração descompassado. Órbitas oculares latejantes, e uma ânsia de vômito preocupante. Sujeita a quaisquer reviravoltas. Quaisquer alucinações." << endl;
cout << "A criatura abre a boca dela e de sua língua um eco se modula no ar:" << endl;
cout << "— Nunca mais...volte..." << endl;
cout << "Ela se tornou para a direita e voltou para o seu ambiente de breus e privacidade, paciente. Um camaleão adaptando a vossa pele para se camuflar no cenário. Preto, preto, e sumiço completo." << endl;
cout << "Você despenca sua cabeça na grama e aproveita a piedade dela para enfim respirar livre de ameaças. Você, a vã, e Savana, sua garotinha que viria a nascer em dois mil e quatro, pesando três quilos e aos prantos." << endl;
cout << endl << "...FIM DE JOGO..." << endl;
cout << "Reinicie a aplicação para usufruir dos seus outros destinos. " << endl;
}
}
}
if (escolha==2) {
cout << endl << "Você menea a cabeça, recua seus soldados, e torna a olhá-lo:" << endl;
cout << "— Er, complicado, mas eu posso ir... Que droga, Oliver." << endl;
cout << "Belíssima escolha, querida. Tenha uma boa noite, e até amanhã — Ele acaricia o seu ombro direito e sai da sala." << endl;
cout << endl << "Em seu apartamento de trinta metros quadrados, às onze horas da noite, você está sozinha. Escuta os seus batimentos cardíacos acelerados e o sangue fluindo nas veias. O ventilador roía rodopiando no teto. As luzes, resumidas a uma luminária que se avizinhava à esquerda do sofá, onde suas costas e pernas se deitavam, tendiam a uma hora se apagarem para sempre. A vossa frequência estava inconstante. Um sincero sentimento seu clama uma última travessura de Chloe Conway. Uma fuga." << endl;
cout << endl << "1. Eu tenho de ir para a viagem..." << endl;
cout << "2. Nem fodendo..." << endl;
cin >> escolha;
if (escolha==2) {
cout << endl << "— Nem se me pagassem. Toda família tem uma mãe... — Você acaricia sua barriga, torna-se para a direita, encolhe-se, ignora a programação de horário do despertador, tenta adormecer, e ouve a maçaneta da porta destrancar..." << endl;
cout << "Tom Boyle, jornalista secundário do canal sete. Dia onze de Abril de dois mil e três. Maine:" << endl;
cout << " '— Os policiais de uma viatura da delegacia de Bangor relataram na madrugada desta sexta-feira assassinato à sangue frio no apartamento de Chloe Conway, jornalista mirim da NewsBang de vinte e três anos e grávida de um mês. Conforme as suspeitas dos médicos-legistas, o algoz de Chloe teria perfurado sua jugular com um caco de vidro. Este ao meu lado, é o delegado Bull, um dos descobridores desse terrível crime.'" << endl;
cout << " '— Nós... não tínhamos nada a fazer além de prestar condolências e orações para a alma dela... Quando chegamos ao apartamento, o sangue dela estava... grudento, e o rosto sem vida... que Deus proteja o nosso país.' " << endl;
cout << endl << "...FIM DE JOGO..." << endl;
cout << "Reinicie a aplicação para usufruir dos seus outros destinos. " << endl;
}
if (escolha==1) {
cout << endl << "Às quatro da madrugada do dia trinta e um de março de abril de dois mil e três, você desperta com o alarme penetrante do despertador em seus ouvidos. Anda para o banheiro para retocar a maquiagem e pentear o cabelo. Na fachada da NewsBang, Oliver, junto a dois homens e uma mulher de sobretudo, acena para você e grita, com as mãos em concha ao lado da boca:" << endl;
cout << "— Ei, garota, vamos dar uma voltinha?" << endl;
cout << "Você devolve o aceno e se aproxima dele e dos seus acompanhantes: Russus, Stephania e Josh." << endl;
cout << "— Há de irmos, senhoras e senhores! Não temos nada a perder! — Oliver abriga Stephania e Josh num abraço e aponta para a porta do motorista para Russus — Você dirige, grandão!" << endl;
cout << "A hora do nada, sua avó costumava se referir aos começos das manhãs. Você, Oliver, Stephania, Russus, Josh e a vã sprinter na qual haviam embarcado, atravessavam uma pista na hora do nada. As árvores e os tapetes de gramas que vos cercavam se camuflavam nas incertezas de um habitat de almas desorientadas. Segredos aparentavam viver nelas. Consumí-las dia-a-dia. Stephania, uma mulher gorducha de cintura larga e cabelo chanel, quebra sua hipnose com a Mão Natureza lhe cutucando o ombro direito do banco de trás." << endl;
cout << "— Você está legal, Chloe? — Ela te questiona." << endl;
cout << "— Sim, na medida do possível — Você reponde, presa às sombras que corriam pelas folhas, galhos e troncos." << endl;
cout << "— Ah bom — Respira ela, aliviada — Porque com os cortes salariais que terão mês que vem, não sei se explodo ou espero para ver. Quer dizer... Nunca se sbae, né?..." << endl;
cout << "As frases de Stephania se dispersam no ar como uma bolha de sabão que estoura. A...coisa... das florestas parecia estar se locomovendo para a pista com os braços felpudos e de três metros de comprimento, pernas similares as de um coelho e uma cabeça a qual os biólogos classificariam como a de um alce. Ela se anuncia esbarrando o tórax de uns quinhentos quilogramas na carcaça da vã." << endl;
cout << "— Mas que porra é essa? — Josh exclama dos bancos traseiros." << endl;
cout << "O volante foge dos dedos de Russus e, com as rodas e o peso da vã, capota. Você protege sua cabeça com os braços e ora para que tudo aquilo que está acontecendo não passasse de um pesadelo. A vã gira para fora da rua e se arrasta num morrinho de grama, de rodas e chassi para os ares." << endl;
cout << "— Caralho, caralho! — Soa a vagarosa voz fantasmagórica de Oliver, no banco do copiloto. Sua visão, embaçada, induz que ele estaria sacando um revólver do porta-luvas, ou tentando sacar." << endl;
cout << "A criatura, porém, raptura-o da vã e o som de ossos e músculos estralando repercutem de prontidão. A mesma infelicidade acontece com Russus, Stephania e Josh, em respectivo. Você, e os frangalhos de consciência que lhe restavam, fita os flancos e desconecta seu cinto de segurança. Cai no ex-tetp da vã e se arrasta para as portas-duplas da traseira dela. Sua respiração falha e o mundo borra feito um efeito psicodélico em espiral. Sobras de carne caem à sua esquerda. O sangue fresco delas pintam o gramado de um vermelho escarlate horrendo." << endl;
cout << "— Meu Deus! Meu Deus! — Você grita para Deus. O único salvador que poderia te oferecer uma mão para a terra do descanso eterno com ternura." << endl;
cout << "O braço da criatura invade a vã em sua porta-dupla traseira, agarra-te e joga você de costas para o solo. Seus músculos eletrificam de dor e a garganta implodia para gritar." << endl;
cout << "— Não, não! Merda, merda! Caralho! — Com os doloridos das suas pernas, você recua o corpo um centímetro — Por favor... — Fluídos vermelhos frescos escorriam da sua testa para se misturar às lágrimas e aos catarros." << endl;
cout << "A criatura se assemelha a um gárgula. Observando-te do cume do chassi. Os globos oculares brilhantes de um laranja-âmbar neon. Chifres enfeitados com sebo e lodo. Dentes ossudos manchados de sangue e encrustados de pedaços de pele dos seus colegas de escritório. Observando-te, como uma diversão, um hobbie. Ela desce da vã e vaga parcimoniosa para você, leve a cabeça dela à sua, e respira. Dois jatos de ar nublado das narinas." << endl;
cout << "— Deus,Deus, por favor... Cuide do Harold, cuide... A ti eu temo — Você sussurra nos pensamentos. Falha. Frágil." << endl;
cout << "O dedo indicador esquerdo da criatura, com uma pontiaguda e envergada unha preta embutida nele, move-se em direção a sua barriga e a cutuca. Como uma criança ansiosa deduzindo qual seria o seu presente de aniversário." << endl;
cout << "Você está ofegante, o coração descompassado. Órbitas oculares latejantes, e uma ânsia de vômito preocupante. Sujeita a quaisquer reviravoltas. Quaisquer alucinações." << endl;
cout << "A criatura abre a boca dela e de sua língua um eco se modula no ar:" << endl;
cout << "— Nunca mais...volte..." << endl;
cout << "Ela se tornou para a direita e voltou para o seu ambiente de breus e privacidade, paciente. Um camaleão adaptando a vossa pele para se camuflar no cenário. Preto, preto, e sumiço completo." << endl;
cout << "Você despenca sua cabeça na grama e aproveita a piedade dela para enfim respirar livre de ameaças. Você, a vã, e Savana, sua garotinha que viria a nascer em dois mil e quatro, pesando três quilos e aos prantos." << endl;
cout << endl << "...FIM DE JOGO..." << endl;
cout << "Reinicie a aplicação para usufruir dos seus outros destinos. " << endl;
}
}
}
}
}
}
return 0;
}

