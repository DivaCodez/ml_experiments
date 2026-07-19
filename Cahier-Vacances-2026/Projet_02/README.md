> df['date'].dt.year**: permet d'isoler uniquement l'année de chaque date.
> pd.to_datetime(df["date"])**: string to pandas object de type date

> On filtre avec `df[condition]`, et on combine deux conditions avec `&` en mettant chacune entre parenthèses : `df[(condition_1) & (condition_2)]`

**df.loc[Condition_sur_les_lignes, Choise_des_colonnes] = Nouvelle_Valeur**