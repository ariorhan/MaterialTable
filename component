import MaterialTable from 'material-table'
import React from 'react'
import { StyledContainer } from './index.styles'

const defaultOptions = {
  search: true,
  searchFieldAlignment: 'left',
  searchFieldStyle: {
    disableUnderline: true
  },
  headerStyle: {
    color: 'black',
    backgroundColor: '#E3E6F2',
    fontFamily: 'DM Sans',
    fontSize: '10px',
    fontWeight: 800,
  },
  rowStyle: {
    fontFamily: 'DM Sans',
    fontSize: '16px',
  },
  maxHeight: '500px',
}

function Material({ title, columns, data, options, actions, localization }) {
  return (
    <StyledContainer>
      <MaterialTable
        title={title}
        columns={columns}
        data={data}
        options= {{...defaultOptions, ...options}}
        actions={actions}
        localization={localization}
      />
    </StyledContainer>
  )
}

export default Material
