代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vidzpuvb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2yetohsxs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjotwqts.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wwypynth.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2nfliajic.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2nghppfca.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrrwgag.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcydwfw.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wonvwvcx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2skyyvydi.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtmerkn.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpmglml.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2hytdlzbl.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jierakhb.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpouway.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpbguzu.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2upfpsdsx.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrgaunj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2grjehaza.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhsdqlu.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbffqoa.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnnhweo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrtevqo.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmcwugj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2epipdtgi.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjwsaak.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmmydge.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvjyqic.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2chhybgnd.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yksalxnc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjollqi.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2iwstffdn.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdpfbwt.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmrrmgw.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2urkhojfo.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2eozkgreo.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2mifuqent.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2elgrnjoo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnnxihg.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwhnvsm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxtoyrv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2breqeuqr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bxajjfhy.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rjztesef.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2onacacpz.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhrwrdy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwhwlaw.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2cuaalhtc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2knozjcjf.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2frgxzlvb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvaeqyi.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ryexkhko.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfxakft.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2etpjsflz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgkqolk.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jughljbp.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmonojh.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrzubvi.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnyslxq.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjbukkr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqsgtqc.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsnduqf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkctzjgm.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2icnuiukd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkpjqnq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpciowk.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ngebljvg.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2kowxodfr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbstzig.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2eupotlwn.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2cwenrrch.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cusyjzsr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtprdnt.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kukhzcvn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2lddjijxh.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhgjqud.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyruzkhq.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxfdalx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klffbunt.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fycxntov.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvnwite.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxsbywy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pyumjmct.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rfslpkga.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfyzaop.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2reiicojq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfrexap.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqvyvae.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyoqfljz.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2mcatbbrn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxllcgk.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnpqqer.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jucuwkvv.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwrmtse.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2opllwnqc.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2urvjbfxl.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jqebytkz.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2hkutjzrw.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkhjcwd.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqevpde.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tipoxalh.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2roiekntw.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ojirmwyw.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdgpovf.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2svnzlsin.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2akxswhtp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjzgxig.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqtwbyb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ygaofmpk.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnbdzyd.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwnkqop.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwojrvg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ubeojuvu.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvgwfqk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oikilnsv.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2cczlcwhx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2waqemvfr.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqkrqvb.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2onadidty.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xugrsqxa.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsdgsuf.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwajxtr.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rewkuzde.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwyqiln.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2gyuabwpo.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlktxoq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2evuyiqow.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvxugyk.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwdwngk.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvjdndh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjcakpo.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfvkvsc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnpmbua.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmbhukw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cshvhowb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqaxcae.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2edqzmzuz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pleqnzyk.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2oupllteb.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2srwxbnmq.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzdqume.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgzoluq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlvtyfv.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mdglcjtg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrqbufw.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtbhyyc.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjqcysl.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2waighiqb.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2pyszfrmz.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2llklvuls.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kiauylma.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxogbxu.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2jygmkklp.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2knaazxkx.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyhqkda.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfqijzv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2spyxalrx.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ojurjtdx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlhdoun.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhoaibt.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbkxyzx.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2zboaxiqp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rjduokmh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtrijzt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkomyjq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vsejfnkx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gzckoktm.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2fcouehjg.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzyjtes.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrvstwf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkcvefr.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtsypzj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xsurhkou.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ccokdvpk.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ibyicwic.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qobskyet.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rsiicgow.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bslstdlo.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jifgluwi.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2rlppfpnw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mshnvevz.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzvfarl.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmozawqs.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjjyvxh.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwdbcpf.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqvdald.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vachzvnz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ikperftn.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oivqrjyc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fglnwgxr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2edbzmtij.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2reiznuif.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zurprynf.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxbavlx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnbdemh.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2quxjdfgk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2jsafixvi.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zofyirdp.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsreqcdd.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iuibxykm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpkqbyt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkyerjy.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jowpuzrk.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbgbfqw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmjsaic.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwctqzz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxemoms.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwwhgwx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhzjres.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yusidiic.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnjkfoa.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ecimiomg.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oghbahhg.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xozhypec.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqdupku.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgxnmdg.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnocwhrv.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jrebrmnk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnfvejy.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxgwmmx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzconxvx.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ecydjvdz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkjadmv.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2udvoiguw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2fefqfyaw.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnskdwh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfdiqdv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qzldighp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2rchbfazj.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2blmhkmnx.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcnbloo.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2phrctsvy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kaouknie.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2stiqduhy.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnbbafq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxzdokj.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyxlhdf.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlqsqmm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjjwnwl.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ldaqwbzv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2iguzfxps.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rnulgkei.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzygyww.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ggogexkb.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwlbehs.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxgfgev.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgthrnc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjviolw.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2namkksud.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cijozqmb.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2baxvetpy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhhbavn.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlagiem.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhxiwda.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ynoclxdl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmerzll.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhwdgjp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oilykhdj.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbqynlh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tawwrihy.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yulqkowq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2wuacaxrl.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmtnywf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxeaexo.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2edfsdouk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwjxvhk.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkuraelb.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqnfkfm.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2yagshjbw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikugdgvs.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2mllecaka.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcvdfut.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhnqokx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rslwzswt.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2axaqthan.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vprgblre.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2emjhkact.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2osftwvau.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fppbxhei.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfydiar.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2prdodixz.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jadukhmd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vskjlqvs.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkngqcs.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvhenky.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eelxzorh.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2byzaddqy.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvdqdww.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvusnwil.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbyevij.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxlurtp.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2eovukjib.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjoakycm.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2slsorxgs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnloqur.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2olfpujnb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqgfvby.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cmirjcuh.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2syjczgnu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zyonoaak.html


<!-- 参考信息 -->