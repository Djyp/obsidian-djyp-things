|     | **L**  | **M**  | **M**  | **J**  | **V**  | S        | D      |     |
| --- | ------ | ------ | ------ | ------ | ------ | -------- | ------ | --- |
<%*
const year = await tp.system.prompt('What year ?');
const current = moment(year + '-01-01');
current.subtract(current.format('d'), 'days')

current.add(-7, 'days');
for (let i = 0; i < 54 ; i++) {
    let week = [];
    let showMonth = false;
    for (let day = 0 ; day < 7 ; day++) {
        let newValue = current.add(1, 'days').format('DD');
        if (newValue == '01') {
            newValue = '**01**'
            showMonth = true;
        }
        if (current.format('d') == 0 || current.format('d') == 6) {
            newValue = '*' + newValue + '*';
        }
        week.push(newValue);
    }
    if (showMonth) {
        tR += '| ' + current.format('MMM') + '  ';
    } else {
        tR += '|      ';
    }

    tR += '| '+ week[0] +'     | '+ week[1] +'     | '+ week[2] +'     | '+ week[3] +'     | '+ week[4] +'     | '+ week[5] +'     | '+ week[6] +'     |     |';
    %>
<%*
}
%>
