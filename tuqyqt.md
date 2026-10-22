代发 wailian999

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zyneipga.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfitxvw.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zcungasc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2noovhyaj.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxnljxr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyiqlkyq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvfqdsi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2grzheayp.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rqaiqqfd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvarukat.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjulvwy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaesfgus.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkfrlya.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nniirpfo.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2kbttfhxa.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhnzptk.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzpemea.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2nrohaofx.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbwmzzx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2euwpmwau.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnaysiwj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ohumhuxp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpdnimc.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rkemmcct.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbdyhmw.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2cchruwuj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2aspwjtxu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zznesxzd.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgeikyy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tudbgvxp.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2isgkfylx.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyjanil.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2pidkroyr.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2vfoxkgdz.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2akjijuqn.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sffhjfcj.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2srhqtmkh.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jadrsdhj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzdegwl.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gopeedeu.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xtarmqxf.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xavrdqqy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdygukq.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqtgibf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrbvtoj.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ewoypyyn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2svxmhfnc.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrbaecy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hmuzvxey.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jyewlhzn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2raezukoy.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxiawfe.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2rvytpotw.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkgfpes.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyknlep.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gazfimum.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2toftvnuj.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuxnneg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqbvlyb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bmeqppqg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwwxeut.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjpghjq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2spfrnmza.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuouldy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvifzvm.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrtbnys.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pkutsmzr.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2iipmzeqg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yaehzmax.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2brgqzcim.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2joxvmbah.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2arafksbh.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tetbqrrf.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2lykcjnzr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxztvvw.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwlwgjq.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjjcixw.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnioqjt.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvlifsu.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjpiyrb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzthppz.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2crhpowvq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqujslsu.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2npryojvf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jccowftv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2clsqcrvv.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2rguinwjs.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vwylqyqa.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmkomfo.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2sojgxono.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2aenahtvx.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qohoaeem.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hskqpttj.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bovpejuq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcgyiep.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmsifpj.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqhwoxg.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ealldkgg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvxlkvy.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmtistr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2krmqqpih.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzvtrfz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2addipoug.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ronucvgr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2tconjlie.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzypwfh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdwbvmb.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqtypjp.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbcbptnw.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2lqttaodo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xuogebok.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2itxccmvi.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdluriw.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kujavqvr.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xwowgfej.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmvxnrs.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjmzgfz.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2myfejmyk.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxtxhur.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyiuqbw.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kgolmoop.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ratqrsvg.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2atocoejs.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfgnqrq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2thqlgraf.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lokerjsu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjyfnce.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxzaurm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvgmqdy.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rynkjdjx.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2smbhjbaq.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wndcjqeo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jyuagiuk.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2irbspkxs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpdtaen.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2nkooahjn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ndydozuf.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2olpprapc.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yaabyfvu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlmhfyj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrmhifo.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpktgtu.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjcuhjg.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zpezdzvx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2xajyjqzu.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgzmryo.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgdrxyb.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2smphfwmk.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2tikzschu.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tyidfxmm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2larijfvb.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmgqvbg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvkgjds.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nizkqycq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cssegjtd.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdrachn.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2dcygvfhx.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2haamqnhr.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2rntfokpv.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgscqve.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2liomrmxb.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rmerkoor.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2skqhdhud.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdwolne.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2psbejgxx.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xvchqygr.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yunaglzi.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2fbulreoe.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2tvuyywch.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfkypgi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfsbsxc.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnwmwib.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcbgwjc.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlowwed.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2tstrsqbg.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jhidegiv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjwpzsz.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxyylza.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfjtzrh.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnuvtnu.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2lscllvho.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hihaoxre.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgdpdco.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nuucsahj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2autxtial.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tubwgivf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxojoze.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2rozcnuca.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2mprsuijh.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdcgxzz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2makmlpnc.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqorjad.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kofjqcsf.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2popfdnxf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2crymwcpd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcfbmgp.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfmopet.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyllxux.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvtekqx.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2dueosrar.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfnltwb.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvfmhvf.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdqexix.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdmrjye.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhypsss.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jovcfkka.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2spgekmqj.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfenwxz.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2phalizkr.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lpschnqu.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhtskdz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgopbnn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2twxotpvx.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qljnmcae.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkbdtsn.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2tonlnujt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vntgdgbm.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnctlms.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwmebfz.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2obydphgh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2nomqpmqe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxdqrrz.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvmhzzj.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yetkmxnj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsjpjoz.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zqidyqri.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xphbchok.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mxoafvrj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdbhxhv.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2avkpkcmr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mxboefpm.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqemjqf.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2txlktsnb.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mythmchs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2srguyqfc.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqmtphm.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzxwrfh.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dexnimjr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgarlcxq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqomdnv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkuidzbo.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cslcstue.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2eolcllbu.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gdewonhq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2orxuhrpk.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmkpgqm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyyhxlp.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2oskizeme.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2crwfojan.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2aeznjlzb.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrlzppg.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2jhatgmex.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdralbq.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ioauobkg.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbtmlxq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jghifend.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qihpoffy.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uaysommj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsomsyun.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhzlmbu.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxxzvva.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gvftrauv.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2fczbwila.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkfpobd.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvuikxz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eurksphz.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yaegjjpx.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2dudepqms.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlkoxuw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndutfbju.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjgdwaj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usrxtdxi.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvywyls.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlhlpbj.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2gruzvodr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2csjfkcxr.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2tywcndvw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvsralb.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nabnbqcs.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2whansmrq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kohypuab.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2innrqozr.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sikpzknm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujoqveue.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lvffmpdc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wkchigkt.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcdahmf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2evcqtipp.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbehnlk.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjodtwig.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqricis.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efsievpr.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvwozkw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2enfjqcre.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qvaqprsm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pimktgxk.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzoxqty.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpxeqku.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2guvptpse.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ireqfsex.html


<!-- 参考信息 -->