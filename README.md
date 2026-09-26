# DriverPro — MVP

Protótipo funcional para motorista de aplicativo.

## O que já funciona
- Iniciar/encerrar turno.
- Captura de GPS pelo navegador.
- Cálculo de distância percorrida com as coordenadas do aparelho.
- Cronômetro do turno.
- Faturamento, gasolina e outras despesas.
- Lucro e lucro por km.
- Meta de faturamento e indicadores.
- Persistência local via localStorage.
- Interface responsiva/PWA básica.

## Como testar
Abra `index.html` em um ambiente HTTPS ou localhost e permita localização.
Em produção, o rastreamento em segundo plano exige aplicativo mobile e permissões específicas de localização.

## Próxima versão SaaS
1. Supabase Auth + PostgreSQL.
2. Tabelas users, vehicles, shifts, gps_points, earnings e expenses.
3. Mapbox/Google Maps para desenhar o trajeto.
4. Aplicativo Android/iOS para GPS em segundo plano.
5. Dashboard mensal, metas, manutenção e custo real por km.
6. Multi-tenant, assinatura e painel administrativo.
