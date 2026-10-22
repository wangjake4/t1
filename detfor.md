代发 wailian999

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2aytmgntx.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqjmbxi.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lihomisf.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lazbdtgt.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2rukyhwmr.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcfcpmq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vzingxjb.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaohush.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfoxpygv.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zisvsqow.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjqfmhp.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kreygnso.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gnyiipmu.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xpteousb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrlcdoh.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2maypshyk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gurgvysx.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2reefncoi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2meqygbjn.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjipaxz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvyqivd.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2owxhxhip.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjyspet.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdofvrp.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2dflwtwhk.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2reryqmlo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyvsyyv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uztlleeh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tnezreyl.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzjhyfi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwcdurm.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuykbyw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2poijxpli.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uyejxofd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bajrcutj.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtncfar.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vowexpzv.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2quhcghzj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnhpnpr.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yonhnsjl.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2butwjcex.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2osaereae.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpudnrl.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkkalak.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpiopfpr.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jlimwiwm.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wogjbkpx.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sandemqi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdkfpbq.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpyxjwq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvauqve.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2tcblchtk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2myeoobsy.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oczdlbfi.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2igsovawj.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2glbjapzz.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2oszjhhfm.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsjhzgc.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2amuhugab.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sbednmha.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pagpratl.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgchxcg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjmioyr.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mngtcexb.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxjmyrc.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vydmppxg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oasjgxxi.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wihsarhb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2uognyfjz.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2sutitibl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxcjgcx.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2igndjctz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zglocrae.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2eknzyrgg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2jipurega.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2psjapidm.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwstbsuz.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmxozrz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxwndey.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdwmigk.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zllpvgmz.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iuilbziv.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2npruvwez.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyjnslg.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxdpwut.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vqthzxps.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdvdcht.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wkaiqaxu.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qoiupvwl.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2loerfeuw.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmjgikn.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsqaipi.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2hspveuxh.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlocqun.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2rzahlwov.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhbkfpy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fjiaufde.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwvtrag.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tvthemtz.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2budpjhfz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxxutrt.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpwmdlj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2posxekhf.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2vnemgigs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2pyaqlxvs.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhsdsfs.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rdejhsld.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdcsdum.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvlhlkn.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ececnwpi.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzluhkd.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2yunsqake.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2vuitgtnt.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2iohuzaxg.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2xokfkipa.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqouiyu.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2uevmqdmv.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iuztsynb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2bsykuvoa.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2scsrznhg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvuxolm.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjsuhdf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cuimvvzl.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cugurzal.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2haaduqcq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkzasjs.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhhfgkl.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dtilclix.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgbaeow.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcfjddz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgztlxpn.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yeespskc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2obnihvcs.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvjrlwm.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fynmqlsm.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwfxtkg.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnwvrvx.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2yycsrakp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mogtvnou.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxnmmuv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2vuovzdli.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbnjhgm.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhuadyy.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzbzklt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ercsiovu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtqraul.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqgctqq.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2omwcruvh.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhjuacm.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hjiwzrfz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpumqhl.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hivptzbz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehiyjhkq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wjymrxfh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpvviti.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2dunwllgn.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxixoci.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfhrpdf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2opnpkopx.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2oucktqgg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2slgkcfpq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcnrhzd.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2iztpnvaq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkgjbpb.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vervvqdz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exlnfpzh.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2quxrzlqg.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2whfdyqid.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scwlgufb.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2enpugnst.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjpxgqp.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qgayulab.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlztnid.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xlniskcg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrmvfjc.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jipvtkxc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2unvlmurq.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqnlfwz.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gawhztxx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2iupgmcgt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ompyeblf.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2tloeacpp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2qubzomso.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfjzcoj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vejwnoha.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2luspqbtq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2oolnynqu.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dkctsnxm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2odronyvh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdvnadu.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgjbkee.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvwzhvo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vptuxffm.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2isfqajoq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2icpohvze.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqzwlde.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2syuhxyln.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rurlnldj.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgiznjf.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrnuykv.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpokrqx.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wifomefs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkaytlyd.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqnbfby.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfhveqg.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmwsmcq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhduled.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dkypkput.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2yonxzveq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwncfzz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkqbgbh.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvcjtro.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jehppftv.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgxamav.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbylvhnt.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdvpreu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdalhor.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2awvxpgcl.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcoyzcu.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzjibef.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkdkqnj.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wedtzgry.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxpypvr.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbjmsad.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2snkqqjlm.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrjnxce.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxxidcv.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyrmaff.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qpztvrnx.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zndblgsq.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2cfklrgoo.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ratjlebz.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqnwdqy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkqpdtz.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2byvzefkx.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2yfeqizbr.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2nfphwurc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2utbnmvqa.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdinztu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbijkqzz.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2jlunlczc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjqfgfw.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2eeknateq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcakcey.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2iqsssuzs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsihoxud.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2axmzmdqw.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqxuxxy.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbmmbkk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqrjkuu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrxhuea.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2slwvrepj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qnynhtsb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2puaybuhn.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpncpdg.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2spvhhldn.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2znfjesdu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2roailhcx.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2mofjwpax.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pblwgfzy.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vupmwvaj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fgieizda.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uxepllmk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsbvmoi.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2twgkbpmj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwjyyee.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnqgqzh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuftsqn.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lntwwwkf.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzfkmbm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbuldgu.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcypaji.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mycpokef.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qrowughp.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jbegmihg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjmbupx.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyqxijr.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzfcyeu.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgpxarp.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrskuqi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2smqkgxau.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjuprrh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2adoyqrzh.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2pnklwlkz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxivwvsq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tykkhsyo.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwfjymn.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tfasjcvl.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxelvwj.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lehxrmpf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2heokmbzb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ofespiik.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lifroalr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zgztspoc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2idzcirab.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gquxublt.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uopcmehn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2chhclgoz.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nbboqzrc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvkvzak.html


<!-- 参考信息 -->