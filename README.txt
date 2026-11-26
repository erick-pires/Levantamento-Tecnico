# Levantamento Técnico (PWA)

Aplicativo web instalável no Android pelo Chrome.

## Recursos
- Pastas por disciplina: criar, renomear, excluir e abrir.
- Equipamentos ilimitados por disciplina.
- ID editável, descrição e até 3 fotos por equipamento.
- Botão de foto abre o seletor de câmera/galeria do Android (`capture="environment"`).
- Edição e exclusão de equipamentos.
- Relatório individual por disciplina: use **Gerar PDF** e escolha **Salvar como PDF** na janela de impressão.
- Dados guardados localmente no navegador via IndexedDB; funciona offline depois do primeiro carregamento.

## Como colocar no Android
O PWA precisa ser servido por HTTPS para o Chrome oferecer instalação e permitir o service worker.

1. Publique o conteúdo desta pasta em uma hospedagem estática HTTPS (por exemplo, GitHub Pages).
2. Abra o endereço HTTPS no Chrome do tablet.
3. Toque no menu ⋮ e escolha **Instalar app** ou **Adicionar à tela inicial**.
4. Abra pelo ícone criado.

## Observações importantes
- Os dados e fotos ficam no armazenamento do navegador/aparelho. Não limpe os dados do Chrome nem desinstale o app sem antes exportar/guardar os relatórios.
- Faça relatórios PDF periódicos como cópia de segurança.
- O comportamento da câmera depende do Android e do navegador; o Chrome pode mostrar a escolha entre câmera e galeria.
- Para gerar o PDF, escolha "Salvar como PDF" no diálogo de impressão/compartilhamento do Android.
