  SELECT DISTINCT A.listed_in, COUNT(B.type) AS Type_Count, COUNT(C.country) AS Country_Count
  FROM [dbo].[netflix_titles_category - netflix_titles_category] A
  INNER JOIN [dbo].[master_sheet_netflix] B ON A.show_id = B.show_id
  INNER JOIN [Netflix].[dbo].[netflix_titles_countries - netflix_titles_countries] C ON A.show_id = C.show_id
  GROUP BY A.listed_in
