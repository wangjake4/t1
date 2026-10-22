代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2nujebdjh.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2iksszbjt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2amkwbvep.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbfrvne.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2arciiwfe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2svdhbpkd.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2izrxvtbg.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhsoktj.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkbrioz.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2unsgfsli.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtclflf.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwytfmv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2drahlsch.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzncnqk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vffmixui.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ensdthka.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmgbyfn.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkobity.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcvvarh.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzelhyx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hncetnvb.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jyquraqd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oogsefaw.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcpmiwa.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpxquir.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbytxre.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kjorpqsa.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjblvkw.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrscumd.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vffdzcpo.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmoinqdv.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zugoosaf.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwuuhtw.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmymgffg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hvptqpvv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxnfbcj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuxkunu.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2dziyohfi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwajzhx.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkyaywt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ptugigfv.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyxsxim.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2omplxxrn.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2uorfzafj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhdjjtc.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtkswlw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfewuxm.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eilomdxj.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfcrvkd.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2cnetlqkp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cssoyvhv.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wqptetos.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jrseozpe.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qyixsnit.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzxigzi.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2swrsmrti.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lfoonnoi.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2efpxcrnx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ncihxqnv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vupwyelv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nydovoyz.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvigtif.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2amqbtnzo.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwlidto.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvedevf.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2wzigpnhs.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2aeowbiyl.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uglphqeq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcjhhgp.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lypwtklb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzptrpt.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrkpvqk.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2neotefwf.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdkuesa.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwdewih.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmnvalv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ukemnfvg.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxxahps.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dqivwnet.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2mutiniwn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmgziyo.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fugovjnf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvucszb.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjesarp.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqybqaw.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2omkefrcr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqfikdy.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwrymis.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bansvkjw.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmgtjhq.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhbaxwe.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ejywtwih.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wouuitke.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwiuexk.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2asjcirny.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tnggbcdb.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gruklzar.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqaiore.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2irrranmb.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvmrsvs.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2zqigvaho.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2frcvbwoz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqrunbv.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwyewop.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2alprhgrn.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2omgpmjnt.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfrbrwq.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ihysjkyg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdsgvto.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjhrprj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvbdbte.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2paevjbak.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ahycecrg.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdjsxeq.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sitofavr.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2oivifdsm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2njywsnqm.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2umeyqrpt.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2udkywpmd.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2mzeojliu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuwqkzl.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pshxysut.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlcgecp.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqhxqua.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2mllxbpam.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqizwyb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlvjycz.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hogjsegm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2onblsanv.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gyixajnl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkqnxjs.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkbxeqd.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlpemwx.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgclokc.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2beockdha.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2crvskrjv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbnntrz.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2etcmpzef.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2cohofejy.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mhszygqq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2kiezukbu.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cewyuarw.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvznwnd.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfmkkab.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrgpkny.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2nmeetnno.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2osryodin.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzohzow.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkimnpt.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ciadzsll.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2vomxnjzi.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmodifk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2zldxtpof.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmefbyq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkurzey.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxdqlbx.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2govihhle.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2dykdikhc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjthisj.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yumnlwvi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdafvkei.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2trdhxisr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ddipxxqt.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkvfdts.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmreqny.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjnnieo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dugmubil.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2gegvvzkc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oscrhhvs.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfvecgz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfblupy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrnmcrf.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwdkbgq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2swcwkpqv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wnizjezl.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2byepkebk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fizcoqgn.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjazbnz.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkysgyir.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ebemwgvn.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2djhkafbs.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyeshvn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nuanxwlh.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mpajmqad.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2thciwqev.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2myckymnk.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xovmjgdl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gaupvxmc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2xdngnxde.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2opqwpkmy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2hslhozcz.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2elkfrjms.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2wknsazsz.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2thgynjts.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdwzxsz.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwzjmra.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2csymevth.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqweufbx.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkjiskh.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2szipvhah.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rizdtgsd.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uktzzaqf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpphzku.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2efmnhscz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2qzeadqfl.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvqvfzd.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqnspbl.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2rakztlzx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhukdagm.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnfnvcc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwrrmim.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvpaint.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2pirnvvbj.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rdogdnhi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmfhbxd.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2frbgyarp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuepuqy.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvfuxwe.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwhazht.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sokufven.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2oygshnvp.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcokmnc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pttbipyn.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ifeuxttn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcspeahy.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxvcsjp.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgigujcp.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ffccfmyk.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtiwujc.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2utkcmlsi.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzexcyp.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrsmxrs.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2npndqjmq.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzwyvnv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2prymzceq.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzmjcnn.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzvtvgd.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2eixixmhk.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhsammn.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwoaopg.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsneajk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsfntlf.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mjodcklo.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2srdegwxx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfnsvtx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2outkbncy.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2parazygc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwsdcqp.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwybsjn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2slulilnz.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2vadhsaag.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqwjsar.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2fnaqfgrr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxilnhq.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmmbszk.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fdsyctax.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gchbbnxu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2tsurcjdn.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkojvpe.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnxabzh.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2euwjzgrb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2riqsfacc.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qjexppad.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ydypldtq.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjhdhxn.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwddzmd.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcpsidn.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrjgkin.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtyhgvl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dajpbzgs.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdnzfnj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzhhrnx.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bbukqcps.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orealngn.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2woospkql.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzuowxgt.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgrvrwf.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzlcfmz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzwrafn.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ugogwzjf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nipzprix.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yfifriha.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jthisykf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxjziey.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdmjmjr.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2gpakzund.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnygdkx.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnvkkzg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubomenhp.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jhssqbsy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgwpfhp.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbvcnvw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pslozyhh.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ockzrhqd.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwumbvwn.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzqdbmz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qffreeds.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rywfceaj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2vosxqoqb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlsgmsa.html


<!-- 参考信息 -->