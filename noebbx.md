代发 wailian999

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2akyvrbsj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2mplhncyq.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsfvqiq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2wzghfcwb.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lscpxeid.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhlidlw.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2thrndayr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2kgywricp.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnfsqbq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pipnijbr.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dgezuqwa.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdqrvyo.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsjihaa.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2glsgjusc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gfckxlsa.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xabcobro.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2swtxxkmj.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nljxmdqp.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2wwajrjnh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbtsumj.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhqnbkl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlholml.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcttvne.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2evuwrqsi.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2miijhxlo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbxlaev.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pijepdrl.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zskniuqm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlxzdeo.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2xyruwnnn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwytpbkz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrxhytj.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbmzwrj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpmnojk.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2tfitbugi.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmkrlcc.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkcotcy.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgxeggc.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zudjwtpx.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kofphgyv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdzydmx.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qfokjzuu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2bccdiouo.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2twfqvsri.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zionbvby.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zviotzdv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2beaonsgr.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lflhxmzr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxcadck.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjlzcki.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtdnseg.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ksppnycs.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zvijncgq.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cbafgxil.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvunkea.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqrpzfl.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2opnlgnoa.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvenzpio.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwktglp.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucogygwl.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2hufojxbb.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuktlro.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ousjsrna.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hilgqjff.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2icoggjjm.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2iitnklod.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cmahbzal.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcokmgs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aoeqmsql.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjtmxfh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sxaxoyuh.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2csodsxdz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eskvgnmj.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zqphprcm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2grmrkdtt.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2musrdrgn.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwcyuoe.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2trpeyejx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmtwhxh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dbeybfof.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yboksgru.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lmftvmqw.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdtwvww.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzcpdqd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2maraajsj.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rexfwjri.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdwusyt.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhxlwdt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqnzzni.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mkervoui.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2uinjnryi.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyweats.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2yxawqrzi.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2hptmtnon.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqaxmlo.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmwvlnm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnjyrpj.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mszbfzsm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcujqdq.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdsrvcl.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgornkkh.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2urecsxts.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grbdojug.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2cywbpqyo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzzvsyb.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkddzjo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cagpkemk.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vggdwiuq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2vhndwklc.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjkeskn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2imkstkol.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxfatwl.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmkrhrn.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbpjysd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ywffkzce.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuckjug.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lixwnygl.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnkdgns.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vvygqukc.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2aundxmir.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuvwuwe.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2mudhlidk.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhdqgkw.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpmsiuv.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fnomznzr.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vftlyuzk.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzayfbo.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvsiemf.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbyqojx.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2izhpkgkz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjpgyqb.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kgecfqfw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hstpdguv.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpwmvxr.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xckuzxyd.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2myrrrkdh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gisczjht.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpecujn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rsedhrij.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtjnlkj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2foklarow.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2whbalaqz.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qypnysxr.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzzdeho.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2khyaafar.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2smamysnw.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzosvxb.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyijwca.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2wznjqzqq.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lheuiltj.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvvnsxu.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2eqinjtzl.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2iudasang.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gnewyfwl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzacaed.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqnwzuh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rbygwawe.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jqueqvzm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fndtenkd.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ximctkop.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2gauzpswv.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2befcgtwf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwwmdpl.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zawxsowt.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2kaubtmuo.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ooiywppo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdggbxi.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxojsnw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2simsrsef.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vavdhfmn.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyyyjps.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2lkiciokm.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2tucmwggs.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2xigzfkrc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eeznpbbr.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2glwyidok.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyagmsk.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2nyughtwj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2icogpovd.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cthjbiqg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2imziuebj.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmjojys.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2snndmupb.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2arxaioub.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2hcuhnzar.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2arvafbll.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhnwhlw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2geredtsk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwbbtxd.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oysjwbvg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcgnixv.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2dtugrnsg.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsnaqvf.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjnvkbo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2plpdlukm.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxxkskj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2byqclqcn.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqoptkr.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2fruxyngy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jekwbcml.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2inmlzcrs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vgezyawe.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdmuhue.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2inuwybsx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcejzukx.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2upkwosbp.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmoocntg.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bskwpocl.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzirqlpk.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2eftsmnoq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fdednnbx.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmsuvss.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2twnagnrj.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjlefdh.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ihilvdoo.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xximxgga.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2yqadhgea.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2yhncngna.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2llbfbexd.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzjofua.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmmqjqe.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2avianznl.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvukjzj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qqppevnq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjeuqdb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2knnslwsj.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqemszlw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcourlj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcpqncf.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qzedrpwg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zaeizrai.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iaisdexb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwaqhrc.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxmpzer.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhrrvcc.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2itaqzdgc.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wntukpyb.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkdasdh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwydmzos.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcyzinm.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdflofmu.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2obtmkxzo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jycnjsrb.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2thlbxvje.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbjhlcl.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2znyraiaq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxbbzqz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ajarcwyq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpsozto.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ongwsoea.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmbbvuo.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wlameolm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsavuov.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2faorkqgo.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppeomsxw.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zfojyoiy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vglkqsrs.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kotnzncp.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jykxxhhs.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkmtush.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpqnufj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbdslza.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqdzonm.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2metydlpf.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxfvrzu.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkbfpzi.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2zshkcswc.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbwsriz.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2chqproxa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjappmr.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pchvojrg.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2imtfcxeh.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2uogcmbdf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yppacnct.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2smpcaigg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgejlud.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2bpoxjyir.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwiitell.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtpfrry.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2enhczejy.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvvhqvj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lonlpnuk.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yizhctul.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tohpspms.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lypidgth.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2xroizygt.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2awsgaksg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2spvnvbdr.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdyieuv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xufpqlnw.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cehvozfk.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkpwdhv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2kukjveyh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2owkznqjs.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqfvpkf.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itnmrlkg.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2flvsxotl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nbumuefd.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cnztgfgv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxfvtqx.html


<!-- 参考信息 -->