代发 wailian999

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2xiuzxdlp.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2popzvhwt.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ssppthxs.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrkmttp.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkzvqsr.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lkukzzbg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbfakes.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2znwywipw.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfcdsms.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhluzum.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcawead.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jugacngw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lqeiykds.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2khtizucr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tngiaymc.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2twdobxyl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uohgyfuu.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2trolgprv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vaezpqhh.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlnpanp.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmqgyxb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fylahdcx.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yaanryvs.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcaiuxzc.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2oifqxnyn.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fddmdoxk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqvisek.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hscmpadd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bljziuwk.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2zetvjzwy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2neaciexf.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pqupqqvy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tqksgtaj.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgxumof.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qptpjkqb.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2vwupjfjn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbepgio.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlovniu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnbipka.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2txsgxkjj.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhinflq.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkapcsn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnsgawq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vwucjdoq.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2khkyyzyg.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2irbxfcsa.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2natrfmev.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2azyltmjp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmczsmk.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tddbdbwg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpiehgz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwlsdud.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2clgogfyq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kfobetxs.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2atyuyqaz.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2sorvlriy.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmoieqq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2zgibigzl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfwhjjd.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rvspyehq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2knlphxrl.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwhxmcm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2hybdigli.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2urbfxmfj.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbzgcms.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhlotsb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxscqav.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2czubuoev.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2cgygboef.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhzfaru.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2clhsswcz.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyafoul.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtngtbv.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsdhkuz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2mazzhucu.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsftqnm.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2clivvvsr.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2wfelmdsw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2evhafooi.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2udjhjzhp.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bymdjcyt.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kovymyoy.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqibebc.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yjywwyes.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjvtptc.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdgckgd.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2chhdmprn.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2apxkmnag.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsqqucb.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2huexjkor.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmyuycn.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbocnwi.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwbuxmh.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jebiiomm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzhywdg.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2adeyufjd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pytgisiu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tadwtkzq.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ukekhwuv.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2auzahwxu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2oalncday.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2eulfgyxx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aitzitqp.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhqbahy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ezawnrkl.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2hksdcikx.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsgqbij.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzrxlvu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnjmotk.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzswysc.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkvsphf.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgpmsnc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2dzplkglb.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wpojihmv.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2mjaojujr.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2aauktksa.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtpafze.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdrdvqc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwmbvaw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxxmbge.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2scpeewqw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vdiustwl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmgybbl.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwhoqum.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2muaeappa.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zihdycsy.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzifhcc.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tzirvfpa.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlayvwn.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dknwjlie.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmenynd.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hajhuait.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2yarkykoe.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpgwlkx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpmoyoa.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2xypckwxs.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmdqjbq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2uugbmntd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ualneyky.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbyzwba.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2dukbzwhy.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wthlzrzg.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwjerdw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fslaqdup.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfawfjjc.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2uswqrzqq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2utshqlqp.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2icetnsdd.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2svyfsckq.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvjbzsm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tsroagea.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbsigdr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2glyadysa.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnamzmj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfpdhfb.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxnpjif.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmrgnzz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2oppmymyd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2owrzituu.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzwsctg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jfncibom.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2qifedgde.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpmjcod.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpbujxg.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lzaqblzi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtjyada.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsaifbf.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrounlc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdmshvm.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgcdtmc.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gckdlavo.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vomsztac.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrdjygn.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ebszhvvm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtdojtu.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2urglesjk.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebudwzxx.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtttitw.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnmstpy.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkdckew.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2cxaaznzn.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2bnryfdoe.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2rewoooyw.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2bhowrndr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxqpupe.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrtmowh.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkffyvxz.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrwpojr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdfseuf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkecikvl.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2aslxtscn.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpusioz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2icjflnhp.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2undsralg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2pobocnhy.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnyxwti.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmwbpjo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dltguuyb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnfoqbi.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2qsoeumnq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfdhxnr.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzbuute.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuflrek.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mnoqwbjf.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ioceamde.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpydzez.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdaxoxsg.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2frrtarwf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2owvdebls.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tgguglmf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqxpaxe.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2famlezxz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqckqfna.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tyerousl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkbythp.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdefjjz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuysglv.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2otfmurhb.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jloymziz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkcunti.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhvmdqq.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmpxlre.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzbgetn.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dxichwmd.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkyndhd.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ozryfuoe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2yirbupfp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2bexrlast.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2diduqsmv.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpzkjef.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjvcrny.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gpopaknu.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2axvqyork.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrgtass.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eclcrlvx.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ediwajkv.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2nkigxhpp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxojkmmb.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2yckkygot.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqtqulu.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2apnzcfug.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijupfbti.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2dsldigso.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnbyefb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqzipdp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uejpycts.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcdrfiq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fisbsoqp.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxmwgeq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgdldcz.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2myqvykpo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2edhrvodb.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ziaqetlx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lmeednlu.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ehggdgpe.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2iyaxqpmg.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2eklnrosw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvusvpk.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbxmrrm.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sarcxvqz.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2uonufnek.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ccttsqzv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kmffnmck.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwhqdnb.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfengbg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvvzwks.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rqaxiner.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogglbslb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dezlkyzm.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2molwwqyq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqreafi.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2okevzynn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2otyaxuxd.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ezglxuwh.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmkheug.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdzbcaf.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnchjhut.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmxodvp.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfawgle.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2btnrxqfj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpikebpy.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fblovxir.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2debgkgvg.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkwfvjt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlenlwty.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcczlsz.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzebcdja.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnlcnkf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpoouqr.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vucxutea.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2eiubplbm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2txlwvdkf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2flpraany.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zelixxjr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuebaxq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyyjvds.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2obnsyrbo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqjlhte.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bsskcosb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzddksq.html


<!-- 参考信息 -->