代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjxfoga.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2dwygkuhj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jakxqnwl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2umwzifrs.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxdsinu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvfbqpq.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2prchpfdg.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnecgbk.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2bcssyxti.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2foarwfvl.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuxsdly.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvpxgxh.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlncjgg.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxjggnc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzlikgv.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wuahrehf.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtagtmz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cormajfo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdkxben.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dszvhrru.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjsmwat.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2crmpgydp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jdciqmkk.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnuejdc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqoyguj.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2doaewarl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yabipifw.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzfbhbs.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2pokvydea.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cextuyro.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzddlryv.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzvmkcx.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrpqgcl.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wvppfykn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjmuseb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hizdvgfi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zprhnaiu.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrgbmtj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxqwydw.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lzyhpjic.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2isnrfjcm.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbwywfs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhchfwk.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwgpojp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ieazwttk.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvmyhvg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdbeurg.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqwyxte.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2doysbyzp.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2hghstkcd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2breeslev.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfwzuzz.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtbkjae.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqxmqpl.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjpaizt.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgvemuh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpniymy.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kacwffyd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfknyndd.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxhfxub.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iarxxcdf.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2knjdpkxq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqovxsd.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2cxteuukb.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2websqpoo.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkmgqgy.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfknhll.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qfflwpmh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xecqzzmu.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2klodnnza.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2bkyydnsm.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpawyjh.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdirztsl.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2oiojtmmf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eijxkovm.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yukiazvy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlqffwi.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2exyjyqbr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdfgkem.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lseskdvo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfrrqnv.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkznkjw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdrpowi.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2npiytxbg.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2swvwaivg.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2bfitglyl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2escgwfnx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dpojbzzv.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvndbsk.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bqixsrmt.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hknkzgnu.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvlsvxs.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsoavqb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2tcufcdto.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2chgruvru.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kodziycl.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tamugpja.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvbratf.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ioixymne.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2beavspqt.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhbstqa.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2untjtbbj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxmzckm.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sexgeild.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ydflfqzw.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zmiepzrw.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rqduzeeh.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnhsjxd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2syyeunba.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqhimss.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxjtskq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbhdsxe.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyhvzfd.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2vgodlzns.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2umlcyiiq.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gyaxhpow.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhxxvpq.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qigbdfxe.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2adntmyms.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2waqlmjrp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2myrqtqku.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpubesb.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnjdgoz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ubstlucu.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpawhpf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwyrugd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ammdhcjw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzfajtf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2oxptiicx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zgflskdb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2snxmwtue.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdfdhcj.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzbmkca.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hogqkfoo.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjrwdld.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bgntpegp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2hekewskm.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2sttpaogp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgkycfr.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwwzwhy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfjcpio.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nnodcsaq.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfdaapc.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2vldfulsv.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgeaooy.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2iulfbqdz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpoyjxg.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2easxbvdj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnjomle.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mzchkxoh.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2feevcqnw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2maycjatl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkekmbc.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfitnub.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbsadkj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2towmxhcz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwqyvvo.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2cnuiwcii.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2olyrldyc.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xoihnmho.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgxfkre.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwroxoh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpjuqni.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qpovokrv.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbfvbgy.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vasmuzth.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jnakcpni.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2xexquxwr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzaukeo.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2afcpyaww.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbjytzu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwxrqkl.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2eaculxfg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgbxgbw.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ylafvyju.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2qtiklaxl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwzfisr.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rsunvpug.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyfpstx.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmyvppf.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrqueji.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqdutsu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqrbgch.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxluwfk.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mozydsxv.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hackzdmh.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdlkfer.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2syoqzivp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2excsyvwl.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2oahztpsg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2tczxisbt.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qipavxcb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2sgttitqk.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbupimn.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhbiwsk.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uerimfun.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbmafdh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvzvwsb.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qthokhmp.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2izqmqolg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2djmhekjm.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyuxuag.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2mgufxhvu.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzztvsw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2kaijqysu.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzyugln.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2apzztwvx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxxaoxt.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrdfqyh.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mazwhqzt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2oufccxrn.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eadbsutk.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjcgang.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvtyieo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2icatbbas.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2iowpxtwi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2plwzovqk.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nxavaqkw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2mineghqe.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qeuqsywg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jixfhect.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2sagliapo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrfhykx.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vstccpjd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwltgszi.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sxclflqo.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcpcejq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmhpjvc.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlwqama.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrhefyn.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyythtp.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyznigk.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjualwet.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2egekslyl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkfqyfx.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsnndep.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2omaovfae.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgzmqal.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnnijmc.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2keiiboxt.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtcbeys.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgruwgwm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2scviolrx.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjguysg.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ovggpykf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpycnfzv.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcfksil.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otwksaiw.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvuxvzy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztddxahj.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgnpagk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tutlslzj.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2dgecsncg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlylxoog.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vmacogso.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjlfkoe.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aoiwimee.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2epgblymt.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzrfnnp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgthyobf.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2maewquxa.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcoaxrk.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsrbazl.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2cicgahpc.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2nerpxluv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2uskrsyns.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ywifqxhx.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umtfgjmc.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjtdzso.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgtnfjz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nefmdsjq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcylqvus.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfnbnek.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwuvzpq.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gitkkpdb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2frmnkqdk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwblyupi.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfzpfvd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcjmrbf.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdaymae.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugumsxqx.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2znymmcdb.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2goezvssj.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmdwsik.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmiiaoz.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwoxskm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhknouoz.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxensjw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sexxgenl.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vovghrml.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gevlswqc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2btndikdx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejotekkl.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mhudgbpj.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptudtozo.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlatvid.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkiqhayf.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vrckstah.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2inudpgta.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvfllne.html


<!-- 参考信息 -->