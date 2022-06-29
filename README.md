# root

# mssql
## index 생성

```sql
CREATE INDEX IndexName

   ON [TABLE NAME] ([column name for key] [order type])
```
order type<br>
asc 오름차순<br>
desc 내림차순<br>

## index 확인
```sql
sp_helpindex [data_voucher]
```

## index 사용 예시
```sql
SELECT * FROM [TABLE NAME]  WITH (INDEX([indexName]))
where col_1 ='11'
```
