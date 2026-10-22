代发 wailian999

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2swzgbono.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcmehqg.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gaguvrzl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkstodmk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbsddkz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2opxoyunn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2puzhpspf.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jerlucgy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxmlarv.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2znimvvni.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylorjxay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxsbnhp.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2phmytckb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhyhury.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2rdufdnls.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2nlifarra.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrewkjq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcinehc.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ayopqfpk.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tggyyidl.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2vudzaewe.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmsglwk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2tseetarg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mwugycum.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwdpqcs.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxtkexu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpzmebz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewalualo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aabtqdvu.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzvaogi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrwfnas.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ipodcnod.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkzthjy.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mtltndgv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfxlbjf.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbxgivi.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvvcpsm.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2moeplsoh.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2suoquvpv.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzgoppg.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpadnep.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxmzwba.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbugooh.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2runvniwm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2klaletux.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdqyyko.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqspmjy.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfhmjlw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqdnppi.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxtanse.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2noaoiemb.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxxkwnn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgjznmo.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2awejuihl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aikcqsyk.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2szsbommk.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yidwsugs.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2fghgbecl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlynqnu.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtxdivc.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eeibugxt.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkxgnxi.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdhkeht.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zzblgiad.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwyozew.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgpgqgw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pybtswks.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhxohvm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2agxhyxmu.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbyvogn.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2tevlpczp.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2enqlhayu.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xwndukog.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ubebbmiy.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2etzpyeeo.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2niypvtpv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2joobtwej.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2umuaqafn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrgbogk.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvrltjz.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqamcbw.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2veoybghm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxflbltv.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2slfzgwju.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ughvaypc.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwdwrut.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2msieuyho.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2usiwtpav.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmezwxf.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ectergmz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ikchracp.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kwaiqfzw.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvspmup.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2otoqnfhv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2chvhnync.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2khqicthr.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2goerylrj.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xomkzlsv.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvtilsf.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgehwdy.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2paxzqxir.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2avjemsid.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzklfcz.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkitxhs.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzwzyic.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwujdos.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2newfddns.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrlloiq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgporxd.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxdvxqi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2zprnqxsi.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eflvudro.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xnppncot.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxgqhex.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gzafbyze.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsodgmh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2csomobxw.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uwaeyshf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uodvstgg.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2krlawemc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2nagmcwin.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2psvhlwqb.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tckwgmnp.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gshppvbf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2saubytjx.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcxgkax.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uzngxezl.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2usglkkja.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbxyhzg.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sljpfldr.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbwziax.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxunthx.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqdhfdq.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtdzted.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2xninhzsv.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrpiljb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvpbqsy.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2yezkidig.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbsvzwc.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkrhnbu.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ihavvyjv.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2myyfkeen.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2pycqltax.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wtknzbkj.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvnjurb.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqxwvel.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwuznerl.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nozpfnja.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2iumlbycz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2urcpkylm.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cirxldyc.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2qezksqui.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ulutdqfo.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvinmei.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lvblblpp.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvcldfm.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2xzprlbmo.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfateur.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvixubo.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnkgdkz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2djrykkoc.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2mbydgcoc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jsyyrnlw.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2evnkriut.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ajueovwd.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnwkzta.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2smhrzzxm.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vixkzlvg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2rzowaqbh.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wydvlobr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dkojtrcv.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2hygebfiw.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbpurqv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkyjmom.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqgrvok.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2bphrwwog.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgldllm.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2rryzlxbd.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jluyrdqp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jolstvny.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vubsgnut.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwdwcke.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqfbyzl.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2maacofco.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxwwdqz.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwtaefz.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzxndiu.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhumjkf.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2yepfadzx.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpglyav.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzxqxcl.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfdnyiq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwuntngb.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qqejxwoc.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fimqrgje.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2iryxgpuv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2giwfdeql.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrppysn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2agmerddo.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkwfslc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjdmsel.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2dualnmps.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwvlzdf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyqjmyj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2elsqdomc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2icxhtwhe.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfogilo.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgdgcpu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2orzumics.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzbmfoq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qprxwqon.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzjcqez.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxguxrh.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hcaywkat.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdxelno.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbeiuwg.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdzbisc.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvrhhyf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdydgptr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqatyts.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvvxgbl.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyouqer.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkthylkr.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2djymrdoc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2glmpqhwm.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlnihjs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmzjtsm.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqeojzh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqmiecg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2eevnfvnm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcielxkj.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnvrzjq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyszcamr.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlgmcsn.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzhwgio.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2inklphzi.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbwrbym.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxhdvcw.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yohyljgx.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pclawdda.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2evzsyfhc.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tdurpnzj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2asihdlfu.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlqifis.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrbbtzz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwjdaam.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhtqktb.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcrolvr.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhbocee.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flazplci.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2phjgbwqo.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2loerrsvf.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2pfuphrpr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcksaisa.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbhdoxa.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pysqvlbn.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkczhdp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhlmgsc.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxbhkfd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2osmqwkjl.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2knbjoead.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lselcmbq.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ryiiccef.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kwajpdum.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hnarsnyd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2xduyxvjc.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gdaiwcgl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2itarxqoa.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxiajlxb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkclfrv.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2smdzeifi.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2kovirknw.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2mukolfzl.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjgumry.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfbzter.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcaahrq.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbvwaif.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mngylnrv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmamzwt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lartbgdb.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2odiujiko.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjaowfez.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2luvgoedy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsyacdl.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnersavm.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sydfkupr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbzwfqw.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2edacpstz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkguavbh.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wdclujrh.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuuzsit.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmdecvn.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pridhwrb.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2kufnvngb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2njkxlfsk.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2srfdpvac.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvqrczz.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2awoyohrm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2exfrpuok.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzucaqp.html


<!-- 参考信息 -->