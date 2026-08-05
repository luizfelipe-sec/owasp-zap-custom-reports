# owasp-zap-custom-reports
Guia prático e templates para customização de relatórios em HTML no OWASP ZAP 2.17.0 utilizando tags chave-valor e engine Thymeleaf.
Este repositório contém um guia prático e templates prontos para a geração e customização de relatórios de varredura no **OWASP ZAP 2.17.0**. O objetivo é demonstrar como utilizar a engine de templates **Thymeleaf** e o sistema de **Tags Chave-Valor (Key-Value Tags)** do ZAP para criar relatórios executivos e técnicos adaptados às necessidades de AppSec e GRC facilitando acesso aos links de referência nos relatórios do Owaspzap

---

## 📌 Recursos e Recursos Customizados

- [x] **Filtragem por Tags Chave(CWE, OWASP, WSTG, POLICY e etc)-Valor(Link de referência a chave):** Mapeamento de vulnerabilidades por severidade, risco e tags personalizadas.

---

## 🛠️ Pré-requisitos

* **OWASP ZAP** instalado (versão 2.17.0 recomendada).
* Add-on **Report Generation** atualizado no OWASP ZAP Marketplace.

---

## 🚀 Como Utilizar os Templates

Copiar os três arquivos abaixo para a pasta custom-tags-report dentro de /home/usuario/.ZAP/reports/custom-tags-report
Messages.properties
report.html
template.yaml

No Owaspzap ao gerar o relatório vai pegar do arquivo Messages.properties o atributo report.template.name=Relatório Tradicional Completo com Seções

<img width="641" height="546" alt="relatório" src="https://github.com/user-attachments/assets/4519e4b3-35ac-4ff0-b9da-25386e92b81a" />

Seu relatório ficará assim:

<img width="1735" height="726" alt="image" src="https://github.com/user-attachments/assets/be4ab56d-1807-4847-b142-8ab3df6cae1f" />

