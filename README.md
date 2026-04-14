# Desafio Nology - Cashback

Aplicacao em Flask com frontend estatico em JavaScript para calculo de cashback e historico por IP.

## Regras

1. O cashback e calculado sobre o valor final da compra, apos desconto.
2. O cashback base e de 5% sobre o valor final.
3. Clientes VIP recebem 10% adicional sobre o cashback base.
4. Compras com valor final acima de R$ 500 recebem o dobro de cashback.

## Estrutura

- `app.py`: API Python e persistencia.
- `static/index.html`: frontend estatico.
- `requirements.txt`: dependencias do projeto.

## Execucao local

```powershell
$env:ALLOW_SQLITE_FALLBACK="true"
python app.py
```

Para rodar com banco real, defina `DATABASE_URL` com Postgres ou MySQL.
