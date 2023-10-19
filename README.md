# ETL_GDP_PIPLINE

<h2>Objectives</h2>
<p>complete the following tasks</p>
<ls>
<li>Write a data extraction function to retrieve the relevant information from the required URL.</li
<li>Transform the available GDP information into 'Billion USD' from 'Million USD'.</li>

<li>Load the transformed information to the required CSV file and as a database file.</li>

<li>Run the required query on the database.</li>

<li>Log the progress of the code with appropriate timestamps.</li>
</ls>

<h2>CALL FUNCTION</h2>

<img src="https://github.com/noraibraheem/ETL_GDP/assets/62545277/bda2ada2-9322-4f93-bce3-4d33da624670" alt="image">

<h2>NOTES</h2>
<ls>
<li> to covert data type of column from string into numeric</li>
<ls><ul>df['x']=pd.to_numeric(df['x']) </ul>
<ul> df['x']=df['x'].astype(float)</ul></ls>
  
<li>to remove commas </li>
<ls><ul>df['x']=df['x'.str.replace(',','')</ul></ls>
<li>to rename column</li>
<ul>df['gdb_usd_millions']=df['gdp_usd_millions'].rename(columns={ 'gdp_usd_millions' : 'gdp_usd_billions'}) </ul>
</ls>
