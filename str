import streamlit as st
import pandas as pd
import plotly.graph_objects as go
df = pd.DataFrame(data={'Examen':['Examen 1','Examen 2','Examen 3'],
'Aziz':[77,76,87],'Maéva':[56,97,95],'Lamiri':[87,82,93]}
)
fig = go.Figure(data=[
go.Line(name='Aziz', x=df['Examen'], y=df['Aziz']),
go.Line(name='Maéva', x=df['Examen'], y=df['Maéva']),
go.Line(name='Lamiri', x=df['Examen'], y=df['Lamiri'])
])
fig.update_layout(xaxis_title='Examen', yaxis_title='Score',
legend_title='Nom')
st.plotly_chart(fig)
