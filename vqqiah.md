代发 wailian999

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpwdwkk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpnaktk.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cguveywh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2orvqpfyd.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2pguinaue.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2zocgbxcv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwzxzag.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yofewquh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzqletw.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ujurwwcn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkcmgzx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyomfok.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jbphofui.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aaepuoue.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2frhdwemn.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgwlpen.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2udvpwghc.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2gdohnppw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxynofk.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rihihhtx.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfmdnko.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lugsrkjx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2gesuizbl.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyhjhab.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bagbmuzd.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsqafve.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehazpykl.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ugazhvll.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcycdti.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qffivqdo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgvbfxx.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2djuwyxsu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lfveakss.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2szzyfbjz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2seajidhb.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xehnmcpl.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2yykhiuxw.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2enwaojig.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2eywlpibn.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdndgkw.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtueenq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tozknzge.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxlnwnb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfonwjb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqprdtu.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2wkanwzpg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qiegkhsq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2phbjshqu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qantyzca.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gmohpltc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2axsifhkw.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvuhdrt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpuufvh.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jotngnmm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2scuxotod.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxqijcc.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bruqknfc.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsfpkke.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkztvszb.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ilalyyss.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bejjhfso.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2iknfkuvv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvuhghbm.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbfmtqp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uitpszrf.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfizmra.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpmgvzx.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdusyrk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcaozws.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzrxopq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2kaszsvxq.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2gslmqogv.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgoqsua.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2aresjmcn.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2quddiwfk.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqeesbr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zqczasyv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkzzrhi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfqmrru.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yftljbgv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hauhuxva.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tawprzyg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xajikbma.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2atnfycva.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtjcmkw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2opahbvig.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hfabwxlr.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bclgopug.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdkqcej.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlhkzec.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2uyllzsjy.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2slzxubcd.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvaaddt.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnjyofq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2urkxzcma.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hvihsagy.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2oofckhsa.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtysnsb.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2svzfymas.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2isemredl.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bhikaytt.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2aulrkejr.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrwqabk.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2szdhaqhs.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzxntmn.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ndorjpui.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2owgcrrxw.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wfagcjyf.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2edsfsder.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2eecvxpiz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2fuezdlos.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2djqzfufl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsaynvl.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ateuktoj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2onocyvrh.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnpoqyq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrozoue.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kslukphw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zagszlic.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwyflvs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2zczvuhfv.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2jyuyvlux.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nreawcra.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtdejpg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gwspqdfj.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2opiimyoo.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrddgmc.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmcmqle.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2bkllugoe.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fbueziku.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxnelsa.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2pzknoyul.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsvsysi.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2helczcjm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwsumib.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnqxwia.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrvrdcl.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gezrwkij.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lhaxupxj.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2iryrmvoe.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjeqjer.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ypoawwdx.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2qcouimjj.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ptywfdsu.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2uddjakka.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2btcyjbcy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrzjvpk.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2iauazfvm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2uveywayd.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvicfuy.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2phjqxclm.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzjknpi.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwzhnhz.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2reatnjaa.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvhoces.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmnxiew.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbzeivt.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdinsie.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ksppeukx.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzjtmpq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfhucpp.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2bluucpbh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2adzttbnw.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2znfqjvzd.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xucmtxvv.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbqiwzn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2euvyzqbw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dxuvenyc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ettomqin.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdjcadx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkbziiw.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyxpooi.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2rituqcgp.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyotbyi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2muvsxysy.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrbfxip.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hywybigv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvubxey.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2iizmwrha.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kattpqgq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2cjiytdvt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dihmgjzu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mktjxbjn.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuxpgsz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxreuyun.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rzphgeoe.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxkbjig.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mophukom.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzaxoba.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2otafktys.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2efpdtjak.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jllzsxqr.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxofrbtc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fnadurpa.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fjofwizx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2upymnplr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2irhskwno.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mxelelzs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkykzdd.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqxcfqj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2gysikczf.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjiruoz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfifuww.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkghknu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2srppekrj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfoikgs.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2apqhupik.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2atqqplbu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2igznjxez.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqnabbw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2pmoenyfv.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxhqhlu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2swurnubz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpgovev.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwwaqme.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2xilskqku.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbsqgpt.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcidvpj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjyslur.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfmulec.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhwvixq.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqtkevt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkyxezm.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2atuauzvd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2glyxupoz.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xhoxkokl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2visexdxd.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnfdtmw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtyztzg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxxwfka.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tscbnlsw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqkdczq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2akzoddbw.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwpkzqn.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2qareicml.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuxxgtr.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzvwyhb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jvggnpuu.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwibyye.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkyinkw.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2veeewfzv.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cejlfrys.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2isertgmu.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2kdidouiq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnsfmme.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2brbmmrra.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzguahw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rznsncda.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2mefvbqhx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnswzbw.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2otyfdbvg.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkfcqzu.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcagfnt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuojzauh.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2houiivki.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekejtvjb.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2quuryygt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqhczum.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjmaohv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkeiojlx.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2tcukqlxb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwjmgdb.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zvoejved.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ckyveaep.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxomjyf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ydewgiws.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbttbmc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfxzwzz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtxrxvz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2flstqlpr.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqfnfqz.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2hgewuwge.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2orupvfcs.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cofuduic.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2mvipuwvp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2verbsozq.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yiobzahk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2llxiship.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jojnalit.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upzcmray.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jniotyvv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfikypb.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmrtqdc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2xiedikqk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2totwxobi.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpfvdhn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2akpryeiw.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cflgewph.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2huhvikbs.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwsiqbq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lkikvjtt.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2lhroeakj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2teeisbii.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjydfqt.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwahdjt.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2taxmquat.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkinizu.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hwavmfjx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrrfkbu.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxawffq.html


<!-- 参考信息 -->