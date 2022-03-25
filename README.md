# WORKING-ON-GOOGLE-SHEETS
This is a code for working directly on google sheets
import dataclasses
import gspread

sa = gspread.service_account()
sh = sa.open("APRIL PPMV ORDER 2022")

wks = sh.worksheet("FUNMILAYO")

# print('Rows: ', wks.row_count)
# print('Cols: ', wks.col_count)

# print(wks.get_all_cells())
# print(wks.get('A2:C19'))
# wks.update('B8','Sorochi')
# wks.delete_rows(12)
#  wks.update('b11','Amen')
# print(wks.get_all_records())
import pandas as pd
wks_df = pd.DataFrame({'Drug Name': ['col1']})
wks_df

