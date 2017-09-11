docker exec -it superset superset-init

UPDATE Pagamento SET uf = concat('BR-', uf) WHERE 1 = 1