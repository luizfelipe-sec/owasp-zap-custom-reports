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

### 1. Importar o Template no OWASP ZAP na pasta /home/usuario/.ZAP/reports/ nesse diretório crie uma pasta exemplo: custom-tags-report e mantenha os 3 arquivos dentro dela: 
Messages.properties
report.html
template.yaml

