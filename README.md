# Digital - Gerenciador de Finanças

Um aplicativo mobile de gerenciamento financeiro desenvolvido com React Native e Expo.

## 🎨 Telas Implementadas

### 1. **Splash Screen (Tela Inicial)**
- Logo e nome do app
- Botões para "Entrar" e "Criar Conta"
- Design limpo e moderno

### 2. **Login**
- Campos de e-mail e senha
- Link de "Esqueceu a senha?"
- Link para criar nova conta
- Navegação para Menu ao fazer login

### 3. **Cadastro (Sign Up)**
- Campos de nome, e-mail, senha e confirmação de senha
- Validação de senhas iguais
- Link para tela de login
- Navegação para Menu ao se registrar

### 4. **Menu (Dashboard)**
- Resumo das finanças com saldo total
- Gráficos rápidos de gastos e poupança
- Grid de ações rápidas:
  - Adicionar gasto (Laranja)
  - Transferir (Roxo)
  - Depositar (Verde/Teal)
  - Ver bancos (Azul)
- Bottom navigation com 4 abas:
  - Dashboard
  - Despesas
  - Poupança
  - Perfil

## 🎯 Paleta de Cores

- **Azul Escuro Primário**: `#004AAD`
- **Azul Secundário**: `#1E88E5`
- **Verde/Teal**: `#00BFA5` / `#14B8A6`
- **Laranja**: `#FF9100`
- **Roxo**: `#7C3AED`
- **Branco**: `#FFFFFF`
- **Fundo Cinza**: `#F5F5F5`

## 📦 Instalação

```bash
# Instalar dependências
npm install

# Iniciar o app
npm start

# Executar no Android
npm run android

# Executar no iOS
npm run ios

# Executar na Web
npm run web
```

## 📁 Estrutura do Projeto

```
src/
├── navigation/
│   └── RootNavigator.tsx    # Configuração de navegação
├── screens/
│   ├── SplashScreen.tsx     # Tela inicial
│   ├── LoginScreen.tsx      # Tela de login
│   ├── SignupScreen.tsx     # Tela de cadastro
│   └── MenuScreen.tsx       # Tela de menu (dashboard)
└── styles/
    ├── colors.ts           # Definição de cores
    └── globalStyles.ts     # Estilos globais
```

## 🛠️ Dependências

- **expo**: Framework para React Native
- **react**: Biblioteca React
- **react-native**: Framework mobile
- **@react-navigation/native**: Navegação entre telas
- **@react-navigation/native-stack**: Navigator de stack
- **react-native-screens**: Otimização de telas
- **react-native-safe-area-context**: Suporte para safe area

## 💡 Próximas Melhorias

- Integração com backend/API
- Persistência de dados (AsyncStorage)
- Validações mais robustas
- Telas de Despesas, Poupança e Perfil funcionais
- Animações avançadas
- Dark mode

---

Desenvolvido com ❤️ usando React Native e Expo
