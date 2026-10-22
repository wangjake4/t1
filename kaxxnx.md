代发 wailian999

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2oizcomdq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2piuxzxgx.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tbagaxkg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqmqsbe.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxynxno.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2tpuhzlpi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zruiwurl.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmtgvld.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2spgawhvu.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgocoic.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2erqmkley.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyubypq.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbuwapc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2phkhvpdg.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ejujylmr.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmmkycf.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2egirrkjw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2zxljfgvd.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpmxzkh.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbswopc.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2tadusigc.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhuqvtmk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgizyjgu.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tmoyughn.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsqlpjs.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2clkyhvbm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2inenptdp.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eetgsarc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjtgixd.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyqysre.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfshive.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wszhqlrn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpkxidp.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ccywmtps.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2eubuvnib.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2bmblhltv.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ewaopixk.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzvnmcv.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnrxauy.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcfimws.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2kvelpeld.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrtkkts.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyqpdvo.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gggvosja.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nhemlczy.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2zndxfsjv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2efposbcs.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xjybhqaj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2weclbsnz.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmpstvs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jptfkfys.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdtvsqk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ptllrcmh.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2momrheya.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqgronq.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxidbdp.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmmryfy.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2cyntdwcs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwraddt.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rnokxwcj.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdymves.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqwcgcf.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2onpmsaot.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cocjkzsn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2owhtlygo.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqandrj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyiltiy.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyfslns.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cidqifkv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqdctao.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2kushzcsm.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrsbppr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2iaogkcmy.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtmgtrz.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2suvywfrk.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pogqwzya.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvcypqt.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqdsdgk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzzmpra.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuuqlhd.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orvuqgyr.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tobolqnz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxspduh.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dttezzqu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2tndzgahu.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2milplpup.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wiamquvl.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkgqcsv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaabsfb.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrpgkac.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkgdcnr.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhcinho.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkqvqcy.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxiykgw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqwmrja.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cihknqdd.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnxzbhg.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xehvzxux.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjkvwdj.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2odijnqou.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuysbxf.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2tbiyjmfu.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iuitgdrd.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bowbwjdi.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmqjqjg.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtfamla.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxmvvua.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrpnmam.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2asodcdjq.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvzpwpj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2lqiiiidx.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsruuht.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pqowyuqq.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lqybxgju.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dksoijjp.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2btyeuxyx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rndibpun.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxrulru.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iufwrmks.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2jwuvipjs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpabtzi.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrbxigl.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgjpwwi.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2adiczxik.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2buboplso.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkgsbab.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mxebwvfy.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2jebnftsp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbrkqbu.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxengbg.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxaejub.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhqyjge.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2cryqkpus.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqtjvot.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2tscryfsz.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqxegpq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhwedhz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ajleshap.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2osnporsp.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lppttlkx.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyayfxc.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlatxdl.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2kslpkhkk.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwbtapl.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcqdrst.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2chtfhekf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqinlcy.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbayzhl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2trujwnuo.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwpufug.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2njnnlswa.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2koitisxc.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2oznpmpxx.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2hxphqybq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wddinkth.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2istgslta.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrdouxf.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2awtonanu.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjbxwlj.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyhrefv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2clmhrcgf.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjowluy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2crtkbwok.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hofzpeat.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2mnakppyv.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyxudjf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2useopjhj.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqzmbjs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbvnghp.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2obhjydeg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2glegdala.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcuuduf.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ztetmkpd.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpnieus.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pmygfaip.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvluoag.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cuahklaa.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2umfeloea.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmsctan.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kltyocfk.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ewshcvlu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cntdvibq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvomrbd.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxrfiyk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjvsoce.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2imqijenv.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qypgwaqx.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpsccxd.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2brrzcoub.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdotbtf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qavymumc.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzwvcww.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ingjrujy.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pexbtyxu.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2khvohlaq.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2egkghkzc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2aekzguam.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlampce.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2stydgeeq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hbimduwp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2prbeslia.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2kowkhmwc.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2aouwugpt.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nmumxlnv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2mtiajekg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbfpghk.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjlotbz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oebcmkzs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfggehne.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2opzgdmfo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvjwgog.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2odfioaht.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rkukqwfz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xadwmajh.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgfskmb.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2begeolkh.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bibybzse.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2shxelzcs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvomxuhi.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdnkvtq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbeeranb.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ianuissp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fydsxfmt.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmqxnft.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ragehyyf.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2shsxotbq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjucyyau.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2feevdudi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2iultauay.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dhiqjrcj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwyaffz.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2igqseedc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbvepwp.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlxikct.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2tujofssr.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjjmgxg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2axsyvyjm.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkimxun.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgimcyxd.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2psaqrytq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhhsosb.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2edabwvye.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2glyxmorn.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2cssxjqhb.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjbunjp.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jrskadjn.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2hktaokyw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpacceb.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ptukexfq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzaqfmdl.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2whvjkrkr.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2uoawbkod.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2rqccqijx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzcumcm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2wiavfoyu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpifqoas.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2asxuogie.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdivtul.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcuevio.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2clwvhfua.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdyjcml.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlhkwkv.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2isiyakhl.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ktptwdki.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2btmstfhj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2llnotcpz.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2msjeztoa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjogaes.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjuezph.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxjbzwn.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvjfjax.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2optthsrc.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbsiuet.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxafstib.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ruouzwde.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmntkma.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwtgvxn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xdehxneu.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtrxalo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oiznnrno.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tglnkmmh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2estlndgo.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdcdfct.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2meyctxau.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgjjtoy.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gvopfdck.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2sruwpncl.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtkwnck.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2koxfawlb.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwxlrqk.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2sugdcswp.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2yahbxvit.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btdyxmjn.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2csrgfpjy.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2llawuzrt.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kltwntbp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2etwkfmdc.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pftouhuv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2owrerljk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2aeklmycx.html


<!-- 参考信息 -->