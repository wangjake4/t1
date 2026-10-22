代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yloifrjc.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2hftbdzpr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcharvu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dtndelzb.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dkiwksdf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fetmskqt.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2yusywcwm.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2flbatzjx.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqbrfkb.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfmwshj.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mncrvrwi.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2evqutcwd.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyhicvd.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdaxwyuv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcmzcwz.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbwlbke.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hozwgflc.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuefpzr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymeksxbp.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zbazdblq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yycooafm.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrvzicp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kuabgxfm.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wcefmixe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2amcqapjo.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrhwiye.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zizdfrbp.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ojehneoq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2yeasvhgv.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkygymr.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjtjtmd.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbykzdj.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2awgsmyvf.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xphwgvzg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2loqjwfvt.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ounpcgef.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wkskcmkj.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlngznh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aqssvqlp.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdhrrai.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jelirjtx.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tusrgerz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ootoimip.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhmtiej.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sywfhtsh.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2eldocsms.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjaohet.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yafdveue.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fimygggj.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2nrngjgey.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2moccjhtl.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jehddqss.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2orljqsfa.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xozgwzze.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vsajjsie.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2umyxykuf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzrbyqi.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pxurqyud.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgqywkt.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ibiillxc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvzuyav.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgkdcpo.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2kohuhowc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkxkbhq.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxswdda.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2mvohjbby.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnxybpr.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ertbwfuq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfhfhns.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmshwvu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrndiep.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfbjrpy.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lawcutjh.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2htbbrwyn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyeewlms.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfbgrgq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjlvdbh.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2czxxhltk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsdmdwe.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2indvivjv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjlqjot.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qoaxkaju.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzcdpgk.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eplbyavz.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlhgamg.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2deurfacc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyyubhn.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2aobjmqlq.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbjfqsh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2shayrpfh.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqqfbre.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2urfzcafg.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqvuekw.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdqhzfj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aeagjual.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxclero.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhmceop.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2oikgdawq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fydudfsw.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzwcwgs.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2pdyiscss.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fekhkiph.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ryakceov.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2swhqndpr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzvemqj.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ndntvyms.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iycmdynj.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxxarxi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2begomkmi.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnhtbzi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbiofuq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwakexy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ewiotkva.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2nojvjwfm.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eoemiyzu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rranjybn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrqdayc.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqguwsw.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kldwtvdr.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2strixrvc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2cvoqstel.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjbhygm.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2skhdqyof.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2tfexdyrp.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2qejjpruz.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ealnzpwf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmmzbpy.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjdgaxy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ampknmcm.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wuifxjsl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwjcexy.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zbstffyk.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2dymmbusf.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfolraj.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2tloozibd.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mfofmclp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbfvhed.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvkatrv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2memneezk.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhtpick.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwjqbhz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ckiqdhsw.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2oucpqmmk.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkgavxa.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqtrwme.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2mvogegpz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2izpiapnb.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2tdiartiy.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2vtoilrfa.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2eimxanai.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfoxove.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqdbwjo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2sluuxjhy.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwdquwz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kwugnjtp.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgvksvb.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrygkwe.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2xkyiwhpd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdkcqbg.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lenacflh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqcwntj.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uamgtzpo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2itnohlra.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2hbirdhhe.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmeissq.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2rqolivil.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kpadrspz.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2rbiuvehk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbhqdei.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2sksjzium.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2qkakazee.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2allfkcxx.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2oufudiwv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ncburddq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2taoagwrt.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvzvbec.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csswphkq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bihkiyuj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwauyyl.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhnjdec.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxoosrbe.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwbzirq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zidhldpf.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjotndm.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eocjjdjc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2avzuswjw.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2evawqazs.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rwycsqyp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxrolnj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xzabyozs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2jghktlwr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2wsilpmmb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2iosxfria.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdexppl.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjgjuoh.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2foujocve.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqqdrqz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnryryin.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlcxmou.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2souprnyg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogswzemy.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wxolqpaa.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2paumjokx.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pemkmevg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2oqoymucy.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpjqypn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyknipd.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2imbcggkv.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfudjyz.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxxkbqn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2omyadxjh.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hfecuuqx.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2sndtvyen.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zssbsiyj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2oluxafuv.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2iczlndqb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyorjita.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwnrlwt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxigitu.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2prbmghzl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2olwupeqc.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wnonenao.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhutcez.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rshnxhpd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhxewdy.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kbilauwd.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnafupu.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnaanwa.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzoirik.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zyyladfv.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2arznxoid.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cqeiycfy.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsxdrgj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuezooa.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2yotjjdye.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2nifzrurr.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmwvzzy.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2urelqpas.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgsvycw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnbsvse.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvlyoei.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onrthwxy.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mltkwjda.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbywtuc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxibzte.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rintedxl.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2pdyofzps.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwsqwaj.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxkfeky.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2usgloujw.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2jdoocmsu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxwtvrw.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2abisouuo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2grqoezut.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dndjxpvv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrkiifd.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwtudej.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjpxdsc.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2obxeqxoj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgughhk.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpjkqfw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2goezzoui.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzifjwu.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqrpxcf.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2amatbgwn.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kskwbqiq.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2txbuxffz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2erovjqro.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvwrwym.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2heqkserm.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpljbav.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krhzkqvg.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lljddxfz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmwvxny.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwnvisx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjijkraq.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2aesgvxij.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qarcbkqi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bsiicnjq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbwrmpz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbonkibj.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrupdad.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lkteeklz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2mykjjkkv.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2borxfrmn.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2usgaqwjx.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2sifirtyp.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlsrnik.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfnsykc.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgzdjjy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkufbid.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2akltwkhn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfjcuzg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bicheyec.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2twmnlufn.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrvzijv.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgjhapv.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfwxyqv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2nkilxpio.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2csewxzbi.html


<!-- 参考信息 -->