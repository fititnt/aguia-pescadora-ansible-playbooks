# aguia-pescadora

> _TODO: mover de README.md para este arquivo comentários e instruções
especificas demais sobre o playbook e/ou que não foram testadas o suficiente
(fititnt, 2019-07-12 23:22 BRT)_

## Metas

- Ter pelo menos três versões:
  - "Tudo Em Um" (limitação de hardware: máximo uma máquina; pode ter ajuda externa)
  - Intermediária & Flexível
  - "Alta Disponibilidade"
- Dentro de limitações de hardware máximo, procurar manter versões diferentes
  de configurações de implementações de Águia Pescadora relativamente
  compatíveis com as outras

### Estratégias de implementação

Os nomes código abaixo podem mudar com evolução do playbook. Aqui estão apenas
para evitar usar referência ao que é ou não instalado em cada ambiente e não

<!--

-->

## macarico-solitario

"Tudo Em Um"

<!--
https://www.wikiaves.com.br/wiki/macarico-solitario
-->

```bash
ansible-playbook -i inventory/macarico-solitario macarico-solitario.yml
```

<!--
ansible-lint macarico-solitario.yml
-->

## (Nome código não definido)

## guira-guira
"Alta Disponibilidade"
> https://www.jstor.org/stable/3676971?seq=1#page_scan_tab_contents
> http://conexaoplaneta.com.br/blog/aves-brasileiras-superpoderosas-e-supermaes-com-qual-sua-mae-ou-voce-se-identifica/

---

## Referências sobre a pilha de soluções da Águia Pescadora

### Ansible

#### Documentação Ansible-BR
- <http://ansible-br.org/>

#### Documentação oficial do Ansible
- <https://docs.ansible.com/> <sup>(Inglês)</sup>

### Kubernetes

#### Documentação oficial do Kubernetes

- <https://kubernetes.io/docs/> <sup>(Inglês)</sup>

<!--
@TODO ver projetos extras de interesse potencial do usuário (fititnt, 2019-06-28 09:31 BRT)
-->

## Referência de projetos semelhantes

### Kubespray

Kubespray é mantido pelos grupos de interesse especial do Kubernetes e documenta
como por um cluster de Kubernentes pronto para uso em produção

- Ansible Playbook: <https://github.com/kubernetes-sigs/kubespray> <sup>(Inglês)</sup>
- Documentação: <https://kubespray.io> <sup>(Inglês)</sup>
