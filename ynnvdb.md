代发 wailian999

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnzstyb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lasrifze.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2qsepptfi.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2txkqkqwy.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2inaqmimo.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqejptv.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpamwfys.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2duqngofa.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzffojn.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zarmafff.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2enbudouh.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2koxffxlj.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oznjavft.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqysjzx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krsthege.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwozxjsk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyjllnb.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vuttfvlu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2btjopcwx.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zbervvld.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2eqovbvxj.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rcshqgqt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pciqlpgd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2tyibyiak.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2yayyxzmd.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfadzsmk.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvxophv.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jozyuhyp.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2deuinttp.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjldjzd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrihlla.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvjmpmk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2djqbwhgt.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2pblfsfux.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrkeprq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjbcixg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pccrfatz.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnxzhnm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hpeesfje.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkqwsep.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpdczxq.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2daemphcx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fivlbyjx.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfroczu.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkhfayw.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2eiperasv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqxkfca.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yabaxuei.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpambrqo.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2eetqjnlq.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqiczaax.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzgmfwg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjbsyss.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtjgspz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xcglrvjc.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2cubngppr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gaurvwmx.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmtbjzw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2jogzjvie.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcndzdy.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmjfjtr.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jjveopcv.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdvprpo.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2odxyafak.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ighfwkvn.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtthnej.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2drfzhxdp.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qgoiwijr.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2koryhebr.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxxscvn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfkiler.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqamwoq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsmogrp.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2uogmbdxu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpjgpxx.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gquwlcpd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2vegwtjxe.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2oybukxuf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2mixsbffz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fyafsglt.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2euxqkzke.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcxgryo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsevnpz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsbfysu.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2axxixvtd.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2teprmkwd.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tposcctw.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2toogpmyw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rnphmmes.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2oiahgmlb.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gfegdsyl.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2grlcbjgv.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2azkvwaeo.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlygllt.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbllbtv.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjokatr.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2dokbnkqk.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrqlbys.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2wanzcgbw.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsgnwfh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrpgeqn.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwrdsvu.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkatzmz.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2smsmiadk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gaddmpcf.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zueiexim.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmbcras.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdmrkwy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwlhvbf.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuabtbt.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dufgvqpv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqudrrz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qrohsvlo.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvcxozi.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpitrys.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2scczstpm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2occyhfmb.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqzvsmb.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxygjag.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlpocuo.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ofivgyel.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzcmmzs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhnogbu.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlxymdy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyltuzq.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlegxrj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkpzgkd.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zekrjqmu.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvgqwni.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lutfbnbf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2orekvbll.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfgbqft.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkskgfv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjiesbp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzwncbw.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2oievhinv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2liserifz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zleykjen.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcijhop.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jambtwoe.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhkudlq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbugxbt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cjameygo.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2saxdpbbh.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2rsflotlm.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpsnyyt.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2atjiuaur.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xshbhwbj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2cakknzuj.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhyoaiy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2grylyzvc.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ymehuega.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2khaegnbx.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ivevftgr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lsentntz.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2whdpisbf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnhmchw.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aftgijii.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vlurttir.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2zydhpkfb.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2slbygsaz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2evjlstmg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxmwdmq.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwrmzyz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cloutsbh.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2tswavgfx.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2lbexzsqf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvtoffz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmkrzwl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ivopvaqz.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2itvcqale.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkphwff.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2geskjsqt.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gibuzbas.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwhghhy.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmamjfr.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmofyikc.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnzdnul.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hsaoixem.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tavavnjz.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlcoapz.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mufwzaou.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkdorqf.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rectzalc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2burqpykr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2stasoskl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2dswunhjh.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvgoezs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsvuzkp.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvgfrjb.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhqdpud.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsqzpwk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2uoycbsbx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2safltefj.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvudbqv.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2asvndtuj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qugcvnvo.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqapidi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqrlimq.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrvoidw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfmitmz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxbeoqr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bgoutdfk.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2mdukqocy.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gponfgod.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gwletsnw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwctltee.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2falqrmpl.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2fneydcxd.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzofgqc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2npzxvtfn.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2karbshul.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2teddclpw.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2covcmwhh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzoqdoc.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgedhyt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmuaysv.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxuwsjl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgxjukv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdfqtce.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcmoiye.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlqfcby.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzbgzve.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjfxbre.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfmpynl.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nwulevpe.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjsehhv.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2teufzyoa.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvijrzvk.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tepcztmw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrajxvwj.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2euewqdgs.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyhoepb.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2sberugyv.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2yeslfkyv.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpjkbhs.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2hxduveno.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2enlypdpk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2omygzhwt.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nvumvioa.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2egeeczng.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2egmabdko.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2njeioqpl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svcqklbl.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyvbpiu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2spjkdvff.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2fphlaeia.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nupwjgxj.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpyxpwr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvensey.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cmirkbwc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hynejxze.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tghoujuh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2kfclummn.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kgatxueh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmayhkjw.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dlerytqr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbyozqs.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfyqtfg.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2fidqsmlq.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2xqalcqvd.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdbcmsw.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2bylaazmm.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpttsaj.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyktlor.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwrekyb.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzhdogz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcwssof.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnrapbv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwiaawx.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxyduej.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfoqvwyz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hytprqvd.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2juezemnp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcggdup.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwonrcr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekoofisi.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2etgrvqvx.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2klrbgsib.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfwvgbn.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkrcdem.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2anvlcqis.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2okprgcys.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpgyawx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzsrvyw.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vshtnhpv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbylygpq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzaplwi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcevcrm.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2irbwawgd.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jidelfto.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nunwmbye.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2byiscuxc.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uatlzqmv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvxujoh.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvvuffg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzsrrta.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2elnjxyul.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzxjiba.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mgeshquj.html


<!-- 参考信息 -->