# HACKERRANK-THE-PADS PROBLEM SOLUTION


select  name || '(' || substr(occupation,1,1) || ')' from occupations order by name;

select ' There are a total of ' || count(occupation) || ' ' || lower(occupation) || '.'  from occupations group by occupation ORDER BY count(OCCUPATION), occupation  ;

