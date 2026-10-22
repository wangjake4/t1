代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkoqekr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2golweeec.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qribaqju.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsvlzfc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2plbywmhd.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2rtofqqrb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2shsyemxz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjrxbxk.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtflxlt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwfhigj.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyjbdkq.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vveforcm.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2fednacnw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2gneankjo.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ypiwxjgu.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xxprdrro.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2yheykpwj.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtyntoo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrbkymn.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgjdgnl.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2puneetxx.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuaeltw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqxwqsi.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsgydhe.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qiglnsmd.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wygwfzcm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2svcwjkkw.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iznjppfe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sruxyqiv.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uiltskih.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pntjesuw.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgtqgok.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2iklikqyt.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2svwltrwz.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2iginatkf.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcncirak.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2qovwqrly.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oohzcqam.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vrcnjged.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzfraso.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvrjydu.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzcvqto.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2klnlqzps.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wakedzbr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qhiwmwhh.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2khdcgmjf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2psbrijpv.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxzghht.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxoibvuc.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hwltrkxl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gfoxkufm.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpgnrct.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eyuxouvg.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhgsmlo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsuxhxl.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2okxuonue.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxkpswp.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xencqzub.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhfjkjx.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cowqmggz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2drycytdp.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwaugga.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mjygfeve.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnjohux.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2leiuqedc.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgyyvzi.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2afrxylen.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2advirwuq.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2mmascmpv.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2nibhdszl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpsyzde.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xnezcqar.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qllvpfkr.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jtyeerns.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlabvbbx.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2piilqhpv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrikqlh.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjibbov.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgneyqck.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hiniebvg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2deppwtfg.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2arkfbsfj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2sagopeov.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvrbkai.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsqynvy.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrfktox.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2befdffhp.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ihulhwdv.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jifjhuou.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuvluro.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2oyldjcfb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyoddeg.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2axhkggcj.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjjmtnp.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2emzmsylj.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfdhbsf.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhieyhg.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnghlme.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xahoooha.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ywaifueb.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2poscaeir.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqzywko.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lsshqyqc.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2shvlrslc.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2wypvexfz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kaoypccc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2npokkzbg.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gndoizfa.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zffygogk.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhgwjsi.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gqazhwiz.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvlswcy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lielzjxv.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lazymvzt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nakbifta.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2rkveostz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jagdpigb.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuesivk.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzjngln.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xbytfiwj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ykopvwcx.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqhromq.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dyakurup.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2hovwvsan.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2uxexstfd.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2utbouxak.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2askjqsem.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2doxkjgep.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzdnphi.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmmunug.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmjmmyd.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjwlqjt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnnufea.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ktuclgiu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpqgexn.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2unropzzz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkpcmwu.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mskncnhk.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrtjlzu.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xizrnkxn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2arulyzgd.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2slraumcn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrarexyk.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nvuxwkpr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2aiekegbz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrrmeuq.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2plimiutw.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwuykwq.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2rijfduxq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2drcovonk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxclwlx.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqmnuua.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2yghmfjsy.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgmmdax.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2qlouxsgg.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bylxftod.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2civnepkr.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2hevufleo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjfnrxt.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dvawthkd.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnvijfs.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vzehoula.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzxtbyk.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcedwfu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbvxrhk.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvynzaf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2imopkpjs.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2cgshhxfe.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqbmoac.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2gidsjrka.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsgjeau.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmzkvey.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhqnuto.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqxfkzj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2hgogomdy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iklaqozb.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2auldschv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwdgzad.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jbprgvyb.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2jexcwgai.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hobjnpjj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gpejonwl.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nyoohahk.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nsunjtto.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxuekbkl.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsqxejr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xsiqpgla.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2svugdtsl.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytljotxa.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2littfbsp.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2svqrvnxj.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2heyovcvw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2asxsqksq.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuqfsbr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2zljdozwr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2yacxcotw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2mzssxxki.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2adndglxd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjkcupw.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuacwuv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfgasre.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqwukvr.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzmjbbs.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yddcidhc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zavlazvx.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hehygqnu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2lonvvvuk.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhcypsz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2oevyknpw.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2chywlpza.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhpcbmq.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2yohrhqhj.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuufaxxs.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cjoxuuco.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2boehzazp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gsedpyyq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqvpmtc.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jtitgzwo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrfvoaa.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcnbbqq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmpeuqj.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgstwbi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnftxlpf.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ofeazvsy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrxryqo.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2logbunng.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqklutnp.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjowvcn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2bptlgeyj.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdgiixp.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvodronq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2jynasbpe.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdzvbvy.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkhzenw.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcfuppp.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkdptex.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhucxcf.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fctykhrm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2rulnegrz.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzzjrim.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxxmzoe.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2txunujpg.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2gskifasx.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmjvvhv.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbmqkmp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2syghqodz.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oixuxpvq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcpuiwx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhsobdb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgwullb.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2reifmqlr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2npcdupws.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxbdmux.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhucfxxy.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzrsrna.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgoqevp.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ivamcdtj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxputgq.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2baregfra.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uuuuoeit.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kueemmlu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gddrqrwg.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ussofskk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxhogih.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwahvfh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jvudwagh.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2idxkxtoi.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpgcieb.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqjodrh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xojnxfje.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjolmrt.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obvlugtl.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2dgznpkji.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2auinrbkv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqrdvfu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yenbadlk.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yfinqrhz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyyqkly.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wymhyhir.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvigpxt.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2krffwklm.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uousoeaq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ayijsemz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuokxbb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwxynoj.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaicdon.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnyjdit.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2fatvmadh.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdgbhlo.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjzuaej.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdyirylj.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2znrbnlzg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2svacngep.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2emzhxiyo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kulwsdts.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkawapq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxudepyq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzwkway.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2thasqcyf.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ghucluwx.html


<!-- 参考信息 -->