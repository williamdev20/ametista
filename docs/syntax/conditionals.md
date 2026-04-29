# Estrutura condicional

## Condição simples
```
if idade < 12 do
    out "Criança"
end
```

## Condição composta
```
if idade < 12 do
    out "Criança"
else
    out "Adolescente"
end
```

## Condição aninhada
```
if idade < 12 do
    out "Criança"
elif idade < 18 do
    out "Adolescente"
else
    out "Adulto"
end
```

## Condição múltipla
```
choose letra begin
    case "A" do
        out "Você escolheu A"
    end
    case "B" do
        out "Você escolheu B"
    end
    other
        out "Você escolheu outra coisa"
    end
end
```