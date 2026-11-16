# 🛒 E-commerce com Microsserviços Orientados a Eventos (Java + Kafka)

## 🚀 Como Executar

### Pré-requisitos
- Java JDK 11+
- Docker e Docker Compose
- Git

### Passos de Inicialização
1. **Clonar o repositório:**
   ```bash
   git clone https://github.com
   cd e-commerce
   ```
2. **Subir a infraestrutura com Docker Compose:**
   ```bash
   cd docker
   docker-compose up -d
   cd ..
   ```
3. **Executar a Checkout API:**
   - Linux/macOS: `./gradlew bootRun`
   - Windows: `gradlew.bat bootRun`
4. **Executar a Payment API** (em outro terminal):
   ```bash
   cd ecommerce-payment-api
   ./gradlew bootRun
   ```

## 👨‍💻 Autor
Desenvolvido por **[marceloxm](https://github.com/marceloxm)**.

