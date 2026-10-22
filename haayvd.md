代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yyotobdx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiankoqz.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2filqyozd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzaypbzt.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmcupnm.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mytkmpog.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpcmhto.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2muftprqr.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnfcpdr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhqkduy.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uozavrfq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2toofutwu.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2eldqcnxo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsrcxfc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2btfoqfpi.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2germtsao.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmxozjg.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2trsbbnwn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvayeegy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2illkziix.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsbagxp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2noldjetk.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2orzazghj.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkkutqj.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2scygmvci.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2mybxqxub.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfomfzaz.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuqqcob.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ixolqijw.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2udejkiwq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqsinvu.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2crvuvypq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ffowibvn.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2umfwdsbd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyeaacr.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxgffys.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkvcpeo.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2whgamsyd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkbyhgp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xnphmndd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2issxlqlc.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yquutfje.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdwtkje.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfbtyfb.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmreqim.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gswxxoub.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sawxzxmg.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtctbbq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvxccpb.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bvczydmw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsbwzmy.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hlusnhbm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ouepkxvm.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcdhjih.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jikhyxxw.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bazbrvdu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uhczwnpa.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qznogbbv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmsqgzm.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhaknks.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2duuvusnp.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bmijyhzg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2idyllojm.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tohxexip.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpimqtk.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdsfvpl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpejxzy.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdtdkmi.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jroxrzjy.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2arludbrq.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tryseszo.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2smadctfx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfmjfsa.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uveunuon.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxokwmsf.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mczbdfqk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gewjwkuq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oohwboqh.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2gehzlyah.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2cpilaveq.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xkibeque.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2epskqavb.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2huyintsr.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qafbdmbe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2idggwmjv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfwkkld.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2onadafpx.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sytxdndl.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvxjimr.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xwycwspv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kruohffn.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvubsap.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxcclot.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpiitoa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfkcwxj.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2alncfufn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2kotuhasd.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fkawrwrk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhssubq.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvwmgmr.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyugosjo.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2tolmflns.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgzcbzg.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xxitteol.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2babxhnom.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fidbxhrd.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvawipv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uebtmwpw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dbatzhav.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2nfghdqan.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lzawdwqe.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zduwpjpc.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2acwuaxmg.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkhmeli.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2auiegfqj.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdrolxp.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsfocor.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxtjqek.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqvvolc.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdylwwu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eksgmspw.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zgufalwl.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvygibc.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2udvpjiti.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fofapvyp.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rggucmpd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2odoglusc.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgariml.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mipkkszj.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqeaisu.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2abderrcu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwajogq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnmkrbu.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2egoxnoiy.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ewejghxi.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rjidxvoq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsrfuub.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lijwwczj.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2dciehset.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2pyinbmra.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhwwxsj.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdnjdts.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpouqbk.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vczdnwpt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ptettavd.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2muzzhcyd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pufpmfxe.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcevpsi.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2owekaclt.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2golnijke.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2neoqwuvt.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlctjar.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbwdazu.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsdssad.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2npeggwle.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2blankeka.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxkjtvy.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwmhmox.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmllwxh.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgxltch.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2xctzcayg.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqoaxma.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpmutyp.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2luwqkakp.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2oszuncma.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mcppeucj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxvwlma.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xllbpubq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2nuexpluo.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmunpsf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2slsezbev.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwmasal.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvbdbwa.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2wptwrmla.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aqprdwdb.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2khpvbwcp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2crkeortf.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ynohcblr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dmugrvoq.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfoteuk.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2zanlovfx.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxaybvd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdlezeu.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwkctis.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwxcvtt.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrshggz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2fyarwwlo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2umonjptd.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fpomzfxk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2guctaqot.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmrwqct.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2qsabjgpt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdlvhrp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2feqykynr.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxytpthk.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkyacjp.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nplmikcb.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdwecsr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhumcdm.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsizwkz.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkytbqb.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgckpys.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2opxzpltz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2eodinfrv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2hmiopnxj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2oetytcog.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2awfnekpc.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2avtqeezn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdrolwf.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcceczj.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhextvm.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xksrcpct.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkvvgvu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqxuony.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2piieivjd.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2beslwfnm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjmaxcv.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gogecgzs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nappvksv.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxmquqw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2xsyisise.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdfxssc.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2szodariq.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2iztfhcho.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyauxaio.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ypztnshd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xaafgavz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcjakxk.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqbozhm.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2shpbckbv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2afsdrymd.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2sncbdktr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jptgaczn.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfcvaqc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2susvazbp.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2trynsxol.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2laesugpr.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2aydgbpmu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnvsoke.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmzcmsb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsilugcq.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rmaenflm.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2npxdevnb.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2rsffaqws.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2btjmebmx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2krpgxddx.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hliurwsi.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2twaysjry.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqscipa.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tpknbynh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpehfmon.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2kyacndjn.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqshmnp.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nzduxumo.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2yorswjgy.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tobuevst.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpjegol.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsjbglj.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zegkhpog.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2lulasslo.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2luezdtub.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dakqoizs.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjtneqb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxslohk.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxfhmer.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsisovkm.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdvkogb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhetoev.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2iiowkwjn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pciapnec.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uomgjpza.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjpqgjm.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2diumgsav.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwnvwrt.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2asddsdtw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmmgdel.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrxsbzi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcdbwzj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxpmdfq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2upvsfxmb.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2iipnxgam.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2btduvvxn.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2eqafvclh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqcmbzk.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zdidjcjo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgcwjir.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2labxljeq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdobswfg.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqwwequ.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2putywyfp.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rfemwngn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhgulmr.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcgukzp.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hypmhwls.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2uiuwpiqr.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2edvlpqav.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylavbsjr.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bpntoyuk.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmyolak.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2npjouqho.html


<!-- 参考信息 -->