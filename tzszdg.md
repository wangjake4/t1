代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2amfujmyl.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mthqplsq.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpfuqcq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2vispizcq.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2exiyongg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjrukbs.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rcazyozw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtacjmo.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvgmjab.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2eusvtfnm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucijuznw.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nahvzizh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ottbutxf.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgkgqii.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbghtkpt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjzhthb.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2krcmubya.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bqylwqvt.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ywizrezr.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2sunkorlb.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyscfvc.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2drqvzsqb.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2taaioumz.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qghyvjzc.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkxtzcw.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhrfkrw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2oydsvcha.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2flmjezks.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdvwkfg.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yyuqsltm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfoouet.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2smfxsdvh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xcryhgcq.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsgrqpm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyfvdqo.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tksgewwn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xozdjdzb.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vskovukt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dryvcbdd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcfxrxs.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ggldllyc.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpmqonn.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2utpislcc.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nahxpyep.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2kthwqsod.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uiidjzuq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2svonqfhe.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hitstuci.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iodvoorq.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2yodkdzts.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wbphnbjc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xavxqffy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hghfsjwc.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2diqcypou.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hletvsht.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2aozxetvi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lndhtsmp.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kizwdkti.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsjelwe.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqwnpvg.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kabbnjxj.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlvynic.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xsytggwa.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tihtqrbs.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvusirxq.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ddscmayq.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmvqswi.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhcimvj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vykxluoo.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bvobmjro.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdtubnt.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtpvkop.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wsulzufw.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlvfsdd.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2yismqrab.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vitfaras.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmkygvv.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2neyvkvst.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2grfrmlcu.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjmzgil.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmscjvs.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xsyeundy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2uuemvwlw.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdkvvyy.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcxtgpb.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2agakjamw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzgloek.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnxstfr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvecjix.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2xsuiyker.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zvikhebo.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcptvxb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhrwdda.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dftrpxdo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyasimy.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwgmbnq.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2esesjnmz.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2pzonzzrq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnsuyqa.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pbiiuvri.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2msmgbyrg.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qhexpobl.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjlrter.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2esohpvar.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cztncjuy.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlbwhwo.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xokduhgw.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsbavyq.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2isjyajaa.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zoeufyua.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jwispguw.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ouigyrmn.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2orbjxczd.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ounafalc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2altgequc.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lpreudhi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gyupidxl.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwjetst.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2reshnuio.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2khxzckul.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgukopt.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzecxov.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqdoofl.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2jazisqxu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhspwzt.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2lmycmdgj.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ymebidtn.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2kdasnwmd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcpczfv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zyelwutr.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lgysnwbl.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpiwlnc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ujibgckh.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcaxcgi.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkfrcvf.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvvktxq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zihqjgme.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtbjpyc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2udcanphi.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2srgrrgbr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gssenejx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2syrbmcrq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jzeuhsay.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vjflakob.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2qohrtkuo.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hijkggna.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2glzovskp.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2apapnrpc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2bhejcuri.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2unjncvgn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnouhuzj.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhmhvfr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2xsehfrwa.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqiykrm.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcnvwkd.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnoqkqj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvypxwm.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrjvfrl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkmatgi.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ancbsgcz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdihwzv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjvnxnn.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2gkurtygd.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ufktmozk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2icfzyuin.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdytjyf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjswazq.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgphceg.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcmpphs.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnbqbmk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qiuqcveo.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlltxnf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2enukzcdv.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtzdfzy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjgdyzo.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2gjoqrwis.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ivoghhvl.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2bqppxeta.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcvloyc.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2iysivdzo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvtbzno.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcwncci.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqhcmfa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zpquklde.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ofiekbta.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzlmgyy.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsmakgx.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2zohgesnr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuahtux.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxypxis.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcxjuow.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjjbekp.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2poxucoqs.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jndrtlbl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfcsiic.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjauifn.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpaiykw.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2khtfvbqm.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwwblgu.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gblgfmnm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2xeofergz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2suvoekja.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtymzdn.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2afozjcsm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2whplrcka.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpbhxyb.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2crenhqks.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mervbimt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2horsheqi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2swipnwky.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tozzjige.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bobpyjcv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2giwnyaui.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jtioldqg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcuvhwr.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cljlcges.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrmnvfw.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tiopklry.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsfhyze.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjagiek.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbslwbh.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yalkifge.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gamrymmp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cyppoiek.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfngziyt.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uoutlivc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2iczzcwvo.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhxmvmi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcogehhc.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrezhqb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngelamli.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyzpfug.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nchtztrt.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2lomhrdvf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsmvzpy.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnrotet.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2sloxqhme.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2auergxcz.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtlcqqj.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2txgptgvx.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tasudynq.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyjxvjw.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2owjcnqmk.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mxydexzx.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2orygbkyj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqfzbmw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwfttom.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxqopue.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2evlodwvk.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2veugqjel.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhqnfsm.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xrejzsub.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmghgfx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvrbkqk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2smqftaty.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2umtfitnt.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2rcukxyix.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppffnkip.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpgnsnt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxtjtgi.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2siofdurl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrqpnii.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2bfubgxob.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ribykokh.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zmincgbm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjswnoax.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkqcfkm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tremhubt.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjhiise.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2tyovcqmm.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nntztqmu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwkfzae.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oxziwhjw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2crdflnum.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eypmjqiy.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnwwrzd.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbysjmw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcfjdyn.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdbeniw.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmckkken.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2drhfzvuu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtdwkww.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2inwzqljx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2reyhhczy.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnczumq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwyniqs.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2edlznxsu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwiudkon.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvuutwla.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpdojna.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2flaxniif.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwlufnl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kukkzyaq.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpmawgv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwunhpo.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgtzoma.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcbcdvk.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2srafkaxo.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhgruoa.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbvwrhe.html


<!-- 参考信息 -->