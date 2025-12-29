# 🚴 Bicicletaria Fragoso

Site institucional moderno e responsivo para a **Bicicletaria Fragoso**, uma oficina especializada em conserto e manutenção de bicicletas localizada em Fragoso, Rio de Janeiro.

## 📋 Sobre o Projeto

A Bicicletaria Fragoso é uma oficina de bicicletas que iniciou suas atividades em 1º de julho de 2025, oferecendo serviços especializados de manutenção, revisão e conserto de bikes com um visual urbano e moderno. Este site foi desenvolvido para apresentar os serviços, localização e facilitar o contato com os clientes.

## ✨ Características

- 🎨 **Design Moderno**: Interface com estilo urbano/graffiti, utilizando cores vibrantes (laranja e azul)
- 📱 **Totalmente Responsivo**: Adaptado para dispositivos móveis, tablets e desktops
- ⚡ **Performance Otimizada**: Uso de CDN para frameworks e bibliotecas
- 🎯 **Navegação Intuitiva**: Menu fixo com scroll suave entre seções
- 📞 **Integração WhatsApp**: Botões de contato direto via WhatsApp
- 🗺️ **Mapa Interativo**: Integração com Google Maps para localização
- 🎥 **Seção de Vídeo**: Área dedicada para exibir vídeos da oficina em ação

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **Tailwind CSS**: Framework CSS via CDN para estilização rápida
- **Font Awesome 6.0**: Ícones modernos
- **Google Fonts**: Tipografia (Bangers + Inter)
- **JavaScript Vanilla**: Interatividade e menu mobile
- **Google Maps API**: Mapa de localização

## 📁 Estrutura do Projeto

```
bicicletaria_Fragoso/
│
├── index.html              # Página principal
├── README.md              # Documentação do projeto
│
└── Assets/
    ├── BicicletariaFragosoOriginal.png  # Logo original
    └── video1.jpeg                      # Thumbnail do vídeo
```

## 🚀 Como Usar

### Visualização Local

1. Clone ou baixe este repositório
2. Abra o arquivo `index.html` diretamente no navegador
3. Ou use um servidor local:

```bash
# Com Python 3
python -m http.server 8000

# Com Node.js (http-server)
npx http-server

# Com PHP
php -S localhost:8000
```

4. Acesse `http://localhost:8000` no navegador

## 📄 Seções da Página

1. **Hero Section**: Apresentação principal com logo e call-to-action
2. **Serviços**: Cards destacando os principais serviços oferecidos
   - Revisão Geral
   - Ajuste de Marchas
   - Freios e Suspensão
3. **Na Prática**: Seção de vídeo mostrando a oficina em ação
4. **Localização**: Mapa interativo e informações de endereço
5. **Sobre**: História e valores da bicicletaria
6. **Contato**: Informações de contato e botões de ação
7. **Footer**: Links sociais e informações adicionais

## 📞 Informações de Contato

- **Endereço**: Av Marta Vidal 1101, Fragoso - Rio de Janeiro
- **WhatsApp**: (21) 98815-4676
- **Instagram**: [@bicicletariafragoso](https://www.instagram.com/bicicletariafragoso/)
- **Horário de Funcionamento**:
  - Segunda a Sexta: 08:00 - 18:00
  - Sábado: 08:00 - 14:00

## 🎨 Paleta de Cores

- **Laranja Primário**: `#f97316` - Cor principal da marca
- **Azul Secundário**: `#3b82f6` - Cor complementar
- **Verde WhatsApp**: `#25D366` - Botões de contato
- **Cinza**: Tons de cinza para backgrounds e textos

## 🔧 Personalização

### Alterar Cores

As cores principais estão definidas nas variáveis CSS no `<head>`:

```css
:root {
    --primary-color: #f97316;  /* Laranja */
    --secondary-color: #3b82f6; /* Azul */
}
```

### Atualizar Vídeo

Para adicionar um vídeo, substitua o `src` no elemento `<video>` na seção "Na Prática":

```html
<video controls class="w-full h-full object-cover" poster="video1.jpeg">
    <source src="caminho/para/seu/video.mp4" type="video/mp4">
</video>
```

### Modificar Mapa

Atualize o `src` do iframe do Google Maps com as coordenadas corretas:

```html
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3681.332344432124!2d-43.1783!3d-22.6789!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zMjLCsDQwJzQ0LjAiUyA0M8KwMTAnNDEuOSJX!5e0!3m2!1spt-BR!2sbr!4v1700000000000!5m2!1spt-BR!2sbr">
</iframe>
```

## 📱 Recursos Responsivos

- Menu hambúrguer para dispositivos móveis
- Grid adaptativo para cards de serviços
- Imagens e vídeos responsivos
- Botões e textos otimizados para touch

## 🔮 Melhorias Futuras

- [ ] Adicionar formulário de contato
- [ ] Implementar sistema de agendamento online
- [ ] Adicionar galeria de fotos
- [ ] Integrar sistema de avaliações/testemunhos
- [ ] Adicionar blog com dicas de manutenção
- [ ] Implementar modo escuro
- [ ] Adicionar animações mais elaboradas
- [ ] Otimizar imagens (WebP, lazy loading)

## 📝 Licença

Este projeto foi desenvolvido para a Bicicletaria Fragoso. Todos os direitos reservados.

## 👨‍💻 Desenvolvimento

Desenvolvido com foco em:
- Performance
- Acessibilidade
- Experiência do usuário
- Design moderno e atrativo

---

**Bicicletaria Fragoso** - A arte de cuidar da sua liberdade. 🚴‍♂️✨

