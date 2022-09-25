# latex-yearly-planner

PDF planner designed for e-ink devices.

See [discussions](https://github.com/kudrykv/latex-yearly-planner/discussions) for available planners and their variations.

### Documentation work in progress
I am planning to write more documentation on how to use it and build it on your own.
Spoiler alert: it won't be easy.
Anyhow, more info on this will come.

# Preview examples
<img src="https://github.com/kudrykv/latex-yearly-planner/blob/main/examples/pictures/sn_a5x.planner/01_annual.png" width="419"><img src="https://github.com/kudrykv/latex-yearly-planner/blob/main/examples/pictures/sn_a5x.planner/02_quarter.png" width="419"><img src="https://github.com/kudrykv/latex-yearly-planner/blob/main/examples/pictures/sn_a5x.planner/03_month.png" width="419"><img src="https://github.com/kudrykv/latex-yearly-planner/blob/main/examples/pictures/sn_a5x.planner/04_week.png" width="419"><img src="https://github.com/kudrykv/latex-yearly-planner/blob/main/examples/pictures/sn_a5x.planner/05_day.png" width="419"><img src="https://github.com/kudrykv/latex-yearly-planner/blob/main/examples/pictures/sn_a5x.planner/06_day_notes.png" width="419"><img src="https://github.com/kudrykv/latex-yearly-planner/blob/main/examples/pictures/sn_a5x.planner/07_day_reflect.png" width="419"><img src="https://github.com/kudrykv/latex-yearly-planner/blob/main/examples/pictures/sn_a5x.planner/08_todos_index.png" width="419"><img src="https://github.com/kudrykv/latex-yearly-planner/blob/main/examples/pictures/sn_a5x.planner/09_todos_page.png" width="419"><img src="https://github.com/kudrykv/latex-yearly-planner/blob/main/examples/pictures/sn_a5x.planner/10_notes_index.png" width="419"><img src="https://github.com/kudrykv/latex-yearly-planner/blob/main/examples/pictures/sn_a5x.planner/11_notes_page.png" width="419">


Build my own: 

install go (`brew install go`) 
install latex (e.g. mactex) and make sure on path with pdflatex available
modify cfg as needed

run in shell:
```
PLANNER_YEAR=2022 \
PASSES=2 \
CFG="cfg/base.yaml,cfg/rm2.base.yaml,cfg/template_months_on_side.yaml,cfg/boox_air2.mos.default.yaml" \
NAME="boox_air2.mos.default" \
./single.sh
```
