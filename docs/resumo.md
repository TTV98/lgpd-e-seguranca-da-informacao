# Resumo da apresentação

O conteúdo dos 24 slides em texto, para ler, buscar e copiar. A versão em PDF está na página de [Releases](https://github.com/TTV98/lgpd-e-seguranca-da-informacao/releases).

> Conteúdo educativo, sem caráter de parecer jurídico. Confira sempre a versão vigente da lei e das resoluções.

## 1. Por que importa

Quem trabalha com rotina administrativa lida com dados de pessoas todos os dias: nome, CPF, endereço, salário, atestado e foto de documento. Esses dados passam por planilhas, e-mails, impressoras e mensagens.

- **Para a pessoa:** um vazamento pode gerar fraude, golpe, constrangimento e prejuízo financeiro.
- **Para a organização:** sanções, ações de reparação e perda de confiança e de contratos.
- **Para quem manuseia o dado:** um descuido simples, como mandar um e-mail para o destinatário errado, pode virar um incidente.

## 2. Segurança da informação × LGPD

| Segurança da informação | LGPD |
|---|---|
| Protege **toda** informação: contratos, planilhas financeiras, código, senhas | Protege **dados pessoais**, com foco nos direitos do titular |

As duas se complementam. A LGPD exige medidas de segurança (art. 46), e a segurança da informação é o meio técnico e organizacional de cumprir essa parte da lei. A LGPD diz **o que** proteger e **por quê**. A segurança da informação ajuda a responder **como**.

### Os três pilares

| Pilar | O que significa | Exemplo de quebra |
|---|---|---|
| Confidencialidade | Só acessa quem tem autorização | Planilha enviada para a pessoa errada |
| Integridade | A informação está correta e não foi alterada indevidamente | Alguém muda um valor sem deixar rastro |
| Disponibilidade | A informação está acessível quando se precisa | Arquivo sequestrado por ransomware e sem backup |

## 3. Vocabulário

- **Dado pessoal:** informação relacionada a pessoa natural identificada ou identificável.
- **Titular:** a pessoa a quem os dados se referem.
- **Tratamento:** toda operação com dados, como coletar, usar, armazenar, compartilhar e eliminar.
- **Controlador:** quem decide sobre o tratamento.
- **Operador:** quem trata os dados em nome do controlador.
- **Encarregado (DPO):** o canal entre o controlador, os titulares e a ANPD.
- **ANPD:** o órgão que fiscaliza e orienta. Veja a observação sobre o nome no [README](../README.md).
- **Anonimização:** o dado que não permite identificar a pessoa por meios razoáveis deixa de ser dado pessoal.

## 4. Dado pessoal × dado pessoal sensível

- **Dado pessoal:** nome, CPF, RG, endereço, e-mail, telefone, matrícula, localização e identificadores online.
- **Dado sensível (art. 5º, II):** origem racial ou étnica, convicção religiosa, opinião política, filiação a sindicato ou a organização religiosa, filosófica ou política, dados de saúde ou de vida sexual, e dado genético ou biométrico.

O tratamento de dado sensível só pode ocorrer nas hipóteses do art. 11, que são mais restritas. No trabalho do dia a dia, são exemplos de dados sensíveis os **atestados, laudos, exames** e a biometria.

## 5. Os 10 princípios (art. 6º)

Além da **boa-fé**, todo tratamento deve seguir estes princípios:

1. **Finalidade:** propósito legítimo, específico e informado
2. **Adequação:** tratamento compatível com a finalidade
3. **Necessidade:** só o mínimo necessário
4. **Livre acesso:** consulta fácil e gratuita pelo titular
5. **Qualidade dos dados:** exatos, claros e atualizados
6. **Transparência:** informação clara sobre o tratamento
7. **Segurança:** medidas técnicas e administrativas
8. **Prevenção:** evitar danos antes que ocorram
9. **Não discriminação:** sem fins discriminatórios ou abusivos
10. **Responsabilização e prestação de contas:** demonstrar que as medidas funcionam

## 6. As 10 bases legais (art. 7º)

Para tratar dado pessoal é preciso ter uma base legal, e o consentimento é só uma delas.

1. Consentimento livre, informado e inequívoco
2. Cumprimento de obrigação legal ou regulatória
3. Execução de políticas públicas pela administração pública
4. Estudos por órgão de pesquisa
5. Execução de contrato ou de procedimentos preliminares
6. Exercício regular de direitos em processo judicial, administrativo ou arbitral
7. Proteção da vida ou da incolumidade física do titular ou de terceiro
8. Tutela da saúde, por profissionais e serviços de saúde
9. Legítimo interesse do controlador ou de terceiro, com limites
10. Proteção do crédito

## 7. Direitos do titular (art. 18)

1. Confirmação de que existe tratamento
2. Acesso aos dados
3. Correção de dados incompletos, inexatos ou desatualizados
4. Anonimização, bloqueio ou eliminação de dados desnecessários ou excessivos
5. Portabilidade para outro fornecedor
6. Eliminação dos dados tratados com consentimento
7. Informação sobre com quem os dados foram compartilhados
8. Informação sobre a possibilidade de não dar consentimento e as consequências disso
9. Revogação do consentimento

**Prazo (art. 19):** a resposta em formato simplificado é imediata. A declaração completa sai em até **15 dias**, contados do pedido.

## 8. Agentes de tratamento e encarregado

- **Controlador:** toma as decisões e é quem responde em primeiro lugar.
- **Operador:** trata os dados em nome do controlador e segue as instruções dele.
- **Encarregado (art. 41):** recebe pedidos dos titulares, conversa com a ANPD e orienta a equipe.
- **Responsabilidade (art. 42):** quem causa dano a alguém por tratamento irregular tem o dever de reparar.

## 9. Ciclo de vida do dado

| Etapa | Pergunta de segurança |
|---|---|
| 1. Coleta | Preciso mesmo desse dado? Para quê? |
| 2. Armazenamento | Onde fica? Quem acessa? Há cópia de segurança? |
| 3. Uso | Estou usando só para a finalidade informada? |
| 4. Compartilhamento | É o destinatário certo? O canal é seguro? Vai só o necessário? |
| 5. Eliminação | A finalidade acabou? O descarte é seguro? (arts. 15 e 16) |

## 10. Segurança na prática

**Pessoas:** o elo mais atacado é o humano.
- **Phishing e engenharia social:** mensagem com urgência, link estranho ou pedido de senha. Desconfie, confirme por outro canal e não clique.
- **Senhas:** use uma senha longa e diferente para cada serviço, um gerenciador de senhas e a verificação em duas etapas.
- **Contas:** cada pessoa com o seu acesso, para saber quem fez o quê.
- **Regra simples:** ninguém sério pede a sua senha por mensagem, e-mail ou telefone.

**Técnica:**
- **Mínimo privilégio:** cada pessoa acessa só o que precisa.
- **Backup 3-2-1:** 3 cópias, em 2 tipos de mídia, sendo 1 fora do local.
- **Atualizações:** sistemas e programas em dia.
- **Criptografia:** no disco, no pendrive e na transmissão.
- **Antivírus e firewall:** a primeira barreira contra programas maliciosos.
- **Registros (logs):** mostram quem acessou e quando.
- **Redes confiáveis:** evite Wi-Fi público.
- **Teste de restauração:** backup que nunca foi restaurado não é garantia.

**Rotina administrativa:** veja o [checklist](checklist.md).

## 11. Incidente de segurança

Conter, avisar, avaliar, comunicar e registrar (passo a passo no [checklist](checklist.md)). A comunicação à ANPD e aos titulares é feita quando há risco ou dano relevante (art. 48). Pela Resolução CD/ANPD nº 15/2024, o prazo é de **3 dias úteis**, contados de quando o controlador sabe que o incidente atingiu dados pessoais. Quem decide e comunica é o controlador. Quem percebe o problema precisa avisar rápido.

## 12. Sanções (art. 52)

As sanções são aplicadas pela ANPD de forma proporcional à gravidade:
- advertência, com prazo para corrigir;
- multa simples de até 2% do faturamento no Brasil no último exercício, limitada a **R$ 50 milhões por infração**;
- multa diária;
- publicização da infração;
- bloqueio ou eliminação dos dados;
- suspensão ou proibição, parcial ou total, de atividades de tratamento.

A adoção de boas práticas e de governança é um dos critérios na hora de aplicar a sanção (art. 52, § 1º).

## 13. Governança

- Registro das operações de tratamento (art. 37)
- Relatório de impacto, quando o risco é alto (art. 38)
- Programa de boas práticas e governança (art. 50)
- Política de privacidade clara
- Contratos com operadores que definem as responsabilidades
- Plano de resposta a incidentes
- Encarregado nomeado (art. 41)
- Treinamento contínuo

## 14. Como eu aplico nos meus projetos de automação

- **Offline por padrão:** as ferramentas rodam no próprio computador, sem enviar dados para a internet.
- **Minimização:** uso só os campos necessários.
- **Teste com dado fictício:** nunca uso base real para testar ou mostrar.
- **Prints sem dados:** o que mostro em público é sempre fictício.
- **Nada apagado sem confirmar:** o histórico é preservado.
- **Cópia de segurança diária.**
- **Gravação só em pastas permitidas:** o servidor local só grava nas pastas do projeto.
- **Base nunca compartilhada:** a ferramenta pode ser mostrada, os dados não.

**O que eu não faço:** publicar dado de pessoa, compartilhar senha ou acesso, enviar planilha com dados por aplicativo pessoal, usar base real em teste ou demonstração, guardar dados além do necessário e esconder um erro.

## 15. Mitos

| Mito | Na verdade |
|---|---|
| "LGPD é só para empresa grande" | Vale para qualquer porte, com regras diferenciadas para agentes de pequeno porte |
| "Só vale para dado digital" | Vale também para papel |
| "Sempre preciso de consentimento" | Existem 10 bases legais |
| "Dado público pode ser usado para tudo" | Finalidade, boa-fé e interesse público continuam valendo |
| "É assunto do TI e do jurídico" | Quem manuseia o dado faz parte da proteção |

---

Fontes: [fontes.md](fontes.md).
