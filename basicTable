import React from 'react'
import Material from '../../components/MaterialTable'

const header = [
  { title: 'COMPANY NAME', field: 'name' },
  { title: 'POSITION', field: 'surname' },
  { title: 'PUBLISHED DATE', field: 'pubDate' },
  { title: 'CLOSING DATE', field: 'closDate' },
  { title: 'EMPLOYMENT TYPE', field: 'type' },
  { title: 'SALARY', field: 'salary' },
  { title: 'VIEW', field: 'view' },
  { title: 'APPLY', field: 'apply' },
]

const data = [
  {
    name: 'Mohammad',
    surname: 'Faisal',
    pubDate: 'Mon Apr 15 2022',
    closDate: 'Apr 25 2022',
    type: 'Full-Time',
    salary: '£ 50.000',
    view: 'Eye',
    apply: '+',
  },
  {
    name: 'Hasan Can',
    surname: 'Ozlu',
    pubDate: 'Mon Apr 15 2022',
    closDate: 'Apr 25 2022',
    type: 'Full-Time',
    salary: '£ 50.000',
    view: 'Eye',
    apply: '+',
  },
]

export default function BasicTable() {
  return (
  <>
    <Material title='Browse your saved jobs with Talrise' columns={header} data={data} />
  </>
  )
}
