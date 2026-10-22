代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2puyiwyfr.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrqeuoa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbicxpi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwwljia.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nsluwxcx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hqoriczt.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2luhtrpes.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpkfnko.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2mghmqnsq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjmjmux.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2agtvfpll.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oryleuil.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ynekaovo.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbkteoe.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2qehrydyb.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2haoeriwb.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvqocgn.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbfmdid.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idienpya.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdqzqho.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hqimlvfr.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ervhtnne.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdplcuv.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fkareaxn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ttocjyej.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yaaqvewl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2guldzviv.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmlonhu.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ifglsxab.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2letmfqqy.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmltceas.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjhjzjq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdzqwoh.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvfrtgr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrisvno.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbvzxje.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wdndlygb.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vehfvwko.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzaqzgx.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jucfbztz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iymzymnv.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2obhefydz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2upqvswaz.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrqrjhz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdamtea.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2orjyunxt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ezybhfdn.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxkdplm.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hplchqvf.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnasgmi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uocuggzt.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmrdjrv.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2peghgcsz.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnptfmz.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2inoezsze.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2itkigxrj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pahjqawr.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2djqvdbbp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iixzgsei.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2asoamqik.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yihfrovd.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jgeyudwl.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhshusbs.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlmrzzp.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2orfvjdhk.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2vyntoevp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2xczvbjmq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ofedozbv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvppfgs.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hnudlruq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmokgzt.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrdzjnt.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slfjtjuo.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqbgdpg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdonjetk.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvtaqid.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2tklwrjgs.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2uzysbvha.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmsilnp.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwouexo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2whesozus.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2aehuhzrv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2potbrbny.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zcexbnzd.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhjdskm.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxyrhuk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zprzwezq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzoutye.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcxaddm.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrrjyti.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2owvinzdg.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgumxjh.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gchlnqrk.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqypjde.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkmbqku.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpcsitw.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jejeveus.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgslbwv.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2uoiswlmn.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdivfup.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2elkcvdtt.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lerfnfmm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtrfhwv.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsoykvv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lviozwlv.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmhqovj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdzpnly.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2whqhcxjm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xakbgtld.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mohzjgwx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vvspgdbp.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2slynoqhw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2wipurxju.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnrpkwk.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfxlbpc.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcpthjr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qavuioii.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxdjsha.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xgefnrxt.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtaakyj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2bjifdnxi.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vkniwbig.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2yizhauad.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2tpedolfp.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2asrbanaw.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkmatin.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxhqydw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2olqcgtgr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2haufpcom.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hmehniiq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2slfnoryy.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mannswyc.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2iswrcslm.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwtbmso.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpxhcyf.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqxnoda.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ifccxiht.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbxbzou.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgsadnn.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzpdmde.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2urqskikl.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mtocjptg.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xulfptlq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2btfctwkp.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2gioqmqwm.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2uecowzqa.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2btzarxtn.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2dfarueqn.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2rodexdhz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkahjfm.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2nxajlzuk.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqfvdhm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbhliym.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2sisrbjfs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2krnwefdi.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2klskauhn.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgaxenm.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2rwaouvll.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpegloh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzznaww.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2muxwqdzj.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfhrcvz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mbymewkk.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ogeqzkzf.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2geassxbu.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzetrka.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pkosmjmg.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjpfouq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpeckus.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2aeehscxu.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjefshg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2trifdnlu.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnhjwdf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkoqzsc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqtsoxf.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2lntvwhyp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlgtblh.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2szmyobsp.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjcsddv.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2uevqkzob.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzdmwws.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2comehklf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwbptmp.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2upplnfpe.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2scaoaywy.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vumyglye.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbfivir.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bthgkehb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2noomkzuu.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2soiwembf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvcmtms.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2imfylsyh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2wkoxrxre.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2raeqpapi.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rulqgnuy.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxyqomb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2xeakkaig.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2iaplywty.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjhgxqy.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xnuzmzpb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qclnyrft.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkjkxos.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2klorysse.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rcryudtw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhwiwqr.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwylxsi.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2votvyprj.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgwvsto.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgdotlk.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oivbdfxm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2stlruphd.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nwiorsxq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2llsttotj.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yuquoeti.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhtlbje.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzmzwck.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2aramxnww.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2olzbtfix.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2gakqhhfu.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmergup.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvotkom.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkjydhk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2sllbtnyu.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gavwfozj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbajzlzj.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxulzjk.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2omqrskrs.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2liborjco.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpxfvlj.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jnphtxuu.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xebbinfy.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kcssquhd.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxutkkjr.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vrchhzml.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlravoqd.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2zmohbhxa.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnmwsrh.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ioajmdph.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2kmksoize.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwtinrs.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhvrxxu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpzohmh.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gppyjcig.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrkcudx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2oayihasm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zehyfgwd.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbattuv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfltosw.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2uykxtvfb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnrpklf.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2sldacrgf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iozjkuch.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxclnyf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzurdrmv.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2srxfppom.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2sxiwgouq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcoptuj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqvmzre.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uzuxcumg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqnflzr.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcdchor.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrjthrw.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lokpcnut.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtofojj.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2oafottvv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxldrnfw.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmbpjzi.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwbzgpc.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2lsocgnvc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmhwhtt.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqhndsj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvtshmq.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rjejwrjd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zztetepu.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iesnjlju.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtkcjkf.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2myrnklxl.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfsxyxj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2urvzzrel.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcgywwu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyqtbla.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zceinmoj.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2flcfrbly.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2lnebnapc.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynromttm.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2hktanevu.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbhvlbc.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rbndqnxg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2irfmcjdd.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpcnaxz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2frnlwiux.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ppentlos.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shdwhtjq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpbxazo.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyuiyfuq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnvkyyq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnufcaaw.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjjjugi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwjrgnw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gmypegio.html


<!-- 参考信息 -->