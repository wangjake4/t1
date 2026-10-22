代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjdeswd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjvfott.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbguimyi.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2icckfuoq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuqhwqi.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkghjau.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dntwujvm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wiaubewc.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwgoryy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqwbumz.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2yodseuvz.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2erxhuame.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgwnfnv.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkrjktx.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzrpftn.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qcljhgmj.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2padcjytk.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfztfqt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwdgegn.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2evhiatxv.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2elxzmzrp.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vahynixi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iodqroqk.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wktmlxtx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tobbupwl.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdzxtvr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gotwpbtv.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2phitdhzx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2crxacimp.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrhuzwe.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqlroxr.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2shvrmnmj.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqubqgb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggaftdoc.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwcaykd.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwaqqud.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvbjwfo.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmpqlyb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbgsxdm.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tuviotpt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2amafobhn.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2pedipkdt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwflqzh.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2isjydpij.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgfppuo.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2npoxdxrb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aucbbsmx.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2vegqqotg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqrhice.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpfunoh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2snrhexwu.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxipvzy.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcqscbu.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnbhtfb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfcyecu.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsbeyvq.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bclmnakd.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2aysmtkjt.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfympzo.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kepmjfih.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oufxxsti.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcfdjte.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyphage.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2uirsjqgc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxntaha.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2elcoaaed.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzmpobc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2bddqernh.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjyfiun.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2omkkxqxa.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzqkigp.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nontbloz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2duwxkgsh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fikzwual.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2zlagojhl.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuhvqhb.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbxftcm.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ociidaav.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnwsvtg.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnonrxf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwinpiv.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2asdyzdpz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cmskgjvg.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hdownpfn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxkijng.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqendbc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqsstjm.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcztobh.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbtmbef.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlicapv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgrixmn.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzndcuj.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2podiqlzy.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2krgcwmol.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnyxnqw.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hybnnyfa.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pxiyylvh.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqbqadh.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkytcnl.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmywlqw.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbnpwxq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2driivigy.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2oeiquaba.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbfsurn.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2pmaibqqj.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtojbhm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjgndys.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqcundk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tocdsdye.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wvndsrvm.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hvupkhmc.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gvycqddo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcctgpo.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2byfgsbmb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dimjnmte.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2bcybbcwp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2eiduxpst.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxnqyog.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2opgkybyu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qrilmpqo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbibdou.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxfdvyv.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gatofqry.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlgcaxy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2dzubvqjd.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bybcxwrk.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqwckcs.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2onacfknv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2caiowmjh.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ljakbjxw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2pdixehdk.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsehtio.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fxixtsdn.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzaomcu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2iqteiprl.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hxofkmmy.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ruugmkmn.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vyoflrkq.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2gptfugek.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsckjay.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjpgyhp.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvktufe.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2qohalhnb.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tfinwfyi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnisomv.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pgazngph.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hygoxqzt.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvuiijj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxexieh.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2dcinkhxy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pnostnqg.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjsvohp.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcmkkvr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbhksaj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpwqsja.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyyoimw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2udezlpuu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2xdiypjpv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgiybut.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xkiumqrh.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2anjeohkv.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2eurxpinw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqppyro.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2anmqxuyc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkvfvhh.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sbaccuse.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpsotjz.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtrekyt.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2qolmlfqa.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2qlliixzm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsetlud.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2setgttam.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2irmthube.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcwultj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwsnivi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2stocqevq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwtrutk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xowibssl.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsokcfv.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2jontzcxq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpkoiov.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cgczclyk.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnpmoyi.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gfullrjx.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfztdpnl.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2otukpnyo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsqyebk.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsdemud.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2omeisgme.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hdihalho.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rcicdjkv.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xmikvtfb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2oiutzrga.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2idyxvwvg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2avtptewq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqokiun.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2jeiccfxv.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2gaoaiols.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpsufdr.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhfqvpk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyrfcxa.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylijoocg.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjmoxhr.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lntbyelm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfhvfkz.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcvmlim.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2oxostxkb.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pcorhfpm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhmrqel.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvhlylf.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhbzerg.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjfgqtv.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2evyeqlsl.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjfqqkn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmpdhmt.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbnyvtt.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvajwcj.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfdxreq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2eovnxkwh.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfrdoac.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrlfjyg.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mihhbhho.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2bireciyg.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfkjnzi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jteucyng.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdzljvo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwufkixm.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2iggpolbd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnqzhsh.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yaifbbad.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxtaudc.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2aqetocbt.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2isoouefn.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2joyobrrz.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbljnhoe.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ltldbxrk.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gliotpxg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcbwrfe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2riezipky.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2eftcsyvt.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnvobmj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwywwnh.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqqunph.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2moybninz.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2izqvtmmh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buviguxg.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkavdax.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rilqlevz.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrgfnuq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzzojwj.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2errovtdt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svhnjnbf.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvhiung.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbrtjpv.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2fkafijgf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvvhjpr.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwtruqf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrxputk.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aorukeiw.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qapspzbr.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwhcejd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2mtaberfm.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ukekasmc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdpovyw.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvavoenb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2crybyolp.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfzmgwq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2kliztvoz.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ozghuvsk.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyaylou.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2lvltcbfg.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvlczxk.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2btkzedzx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfjsqxj.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2utlzygjk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amskbmfl.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvhpsbx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxibzjd.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ldskzeue.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybehbzsh.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcsosns.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxhafpv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dpiykxrh.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbzpfml.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgmvypu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdwcrjz.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2waffqjhq.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2bojeglna.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlpamcx.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfvoamd.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyprlyf.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pnglkceg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyeqwlc.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyxksua.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tejlhrpj.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jlezdryd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bynvvylw.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdzsdkc.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmkhxwy.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jalbwiix.html


<!-- 参考信息 -->