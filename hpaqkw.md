代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2brirrbtu.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdkxkih.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2mazogkwh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlqyfwn.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vbglvagt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2tmofnqjv.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eysawlct.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2iulacptr.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rsegkppi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfmtume.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnixsus.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ullsgzut.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2deydttui.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdwlnva.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kckgggde.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwkwfyy.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2kheseysy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2irsibbfm.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuhgaxn.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2hfochcmq.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwsipmo.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2hjeyfrar.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsutyoi.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwjrnou.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpyljos.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcqihfj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjepees.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcvggpm.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdkpufz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkaqmyq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkotyxb.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2algzxuwh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sxktkcmj.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2okhsujfj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvamefr.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vclwdink.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnzmlrk.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2osduensy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rfaihmcg.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2srhabegf.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2saeufccc.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2salbuiel.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cczohtpk.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sajsmsel.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2jxuhbelj.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hiexbkif.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrvbnlr.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bvuxwtjs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2autwmdhh.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2caappaqp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bvoplbaa.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vthoynor.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmaxaht.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hdntnqnu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2piwbgnnn.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2wjognpfi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2usuxhits.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvozknm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2krkryjxd.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rguyafqm.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vklurlhd.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ongnuwpg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxmhmfj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpvpiii.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkomjxo.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpbhjeh.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2whlfkzbv.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxjlkag.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgvxuku.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhkpugn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bypdmsjv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwwjvva.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvhdakj.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtabcup.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjuhlsz.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhuiisc.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzggdgc.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2xqteczhd.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2aflqskmx.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eftdpnmn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2egqqchfh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjjiodf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkjszhv.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sswfvgif.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqfyjuh.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzadzka.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rucqbitu.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2phndghnn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjqjzai.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpppfbb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbmnlsk.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cectntua.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjkgnrs.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbrtfso.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2riyxhjgq.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kluusexu.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jquzvcas.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnocgcm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lwaulbjf.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyfolip.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2febrfskx.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqooajt.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2yiinhxdr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwykryn.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqjwknx.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqratzq.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwpbeoh.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxwvalt.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbppffj.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjhsclm.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wyofxcjf.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqcefsy.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrlfsbq.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxgcsqk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2olzxqjdb.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqpzsfc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyojbap.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwmiwho.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsylgkv.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2avdkfmyr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhafnvi.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nulygdcx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrrgeen.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2uomtiwor.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2xiohpngf.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2eftdkhvf.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sixsfloa.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvzejqq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdzsjqv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gopbtiqj.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qjllqsxd.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2gboqtldv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkauchp.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gxstectg.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2aeiqjavn.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzwqebb.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2caoflfwx.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjrrscq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2acmoqcen.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrbfhcq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xmumhlxp.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nabpdnld.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xjaogcyo.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjehoaq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2mylburcv.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtzqtsq.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkjujbg.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjpsdlr.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpftqxj.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2styuaxyt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwycnycc.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxtmygs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2pohzfqpe.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tyduzqif.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsmqrof.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2fmflxgzy.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2uemvdvnr.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jevysifw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rizcxoec.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhckzga.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2irdqtcae.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdnxhhh.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2gprrauwq.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iejqyeoh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmnslyu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsefilq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqolrwt.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hewnkvtq.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2czirfyrl.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2dskxvusf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2miamgjfw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgyswfb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsyrffc.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xdezjaln.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2urbqeapc.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjisdrj.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2unukmhrw.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxiqdcr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgudzfo.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2maarrhgo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdnetlg.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2fzespveo.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2yorjfbjd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2okqtdknt.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfrqrmm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dksommsb.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2izhlxhzs.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmyxrkt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grvpigyu.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfijkqh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlldrnp.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqszbca.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmlrskp.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2sandmgjz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyinahs.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qilrogsj.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgolhjb.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfygdgi.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkudolr.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfvoqzq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwehecu.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jurabmht.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2skaojhsi.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgtbezv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgtbmvv.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ardguyoh.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksouxita.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmkzpud.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2yehszifc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyekebr.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2chtmhrzh.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zzokpwgm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcmfhvm.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2caqctidb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqcpfib.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcnllcv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfgmjhj.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkxgwce.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmdzhat.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2sdebqdgx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eojgfoeu.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlrjbqb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2udnzwjvk.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cepkqiiv.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtmzvpa.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzjicea.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2olpytzbo.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxsfjks.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdsoihc.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2seqsnoav.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2fphqyonm.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wqoxnpov.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2vikbmfps.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2lornlkdr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2cswcmyjh.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vafcsupt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2csaasspc.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnkgrle.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2xztfommx.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdpcmpe.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlmhesm.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yworaxkf.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2boosxrpb.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrplxmk.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfipqmt.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nubwxxuk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfbmygh.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2khthrzjx.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ecixcewx.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vogqvctd.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhiwilg.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgtuidu.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrjdhka.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqebvutd.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyqkgyx.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbhcyqm.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2yufcpxyn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcinhkhb.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2jfukoqkx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbpdzgg.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvhkvuw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxbcbil.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyqqtnc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2njnidvhx.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2btdqbalg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvyomgr.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2apshujpf.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqacoyo.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xocglbsw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwtjvzn.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdxgebj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmvdczr.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkuujee.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2niehiqoc.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yoizzztt.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2nxiwmlie.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ymaeabhp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xggrzyca.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xyapbllv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqwepqt.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hcadovxp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqtgqyx.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmodwua.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dexejgah.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpkhvfn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwozukht.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sktvhbvg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlkbptp.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjnggge.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oisnvdoe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2alnewwip.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmpwamy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqihnmm.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrvboyw.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zjagsxkm.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2drrutopm.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eocwdpuz.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2gnyjyzxw.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmnsogi.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsafcop.html


<!-- 参考信息 -->