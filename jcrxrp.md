代发 wailian999

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2etsbkhof.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qufjtlve.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrahdvq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2amqyunmn.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hjccvqzn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzdjqif.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwfhbuj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2wthnvhnp.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2werenpnp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2edgstypm.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2srwjstrn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjkwvfk.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkmoklp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbduwszh.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rimxaxgj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrheynb.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzsceeo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpuuujpf.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2euoowmof.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrafipr.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxqrvra.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvjohit.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2aoumerfp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dagkybfx.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwrlwwm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrirwwm.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwecurhc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2xaowrysv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjjxozv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ismdzacw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhnpkba.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bxncgovi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxzxyrf.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2arefmhdp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kisiduzw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmglord.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bexgtrix.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjbbwqs.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcdalop.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2eesybsgr.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ejeetvus.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2fjiqzxea.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmndxerv.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcyivno.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwiotgp.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhefzib.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvluwpll.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdjolpa.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2abqturgm.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wcilkukh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzpvwiq.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2veayddtd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rinxwgwp.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsbmvlh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rvuummhb.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2emzrdhvd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwmckka.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlsjjms.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vwusdgic.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2uabymdtj.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2cljeuuvp.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbzuhld.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmawvaut.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2heaqcvxk.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyatxel.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tkznxgpw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2umrpczlr.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2msrqazdj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mvppkgkv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjooajj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qudaedjm.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2srwmfglq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjwfuva.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nxffyksi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfyqbpc.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2veamrdgj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pujwtvce.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pweyhgby.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbcdkqv.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhjnhlx.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgbunbf.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdelfgy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcpxpch.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyyzbpo.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yygrgwpv.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpjbtqf.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uuejeppn.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ytippolk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xpciyfvp.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xmamnbcu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2czdqfhky.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2eshojzdk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2axsirbxc.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xhepqllq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2aotqlooa.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnaednm.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2sfehjmdx.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnphzxc.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2osaljzcp.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tilcorzy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2febgqpms.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhwlwwz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2jmonjlit.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdgaslz.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znmochii.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrbovby.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlstqhh.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xknmarjy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjeeswc.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbmyhpi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rznmcrss.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2mttujkrq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrimemy.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ukghqzce.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2lioayynq.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tszmhoee.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxexpejv.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxgzatp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpdsefs.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzrxvrh.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwpuxfx.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2okkoojcp.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ctsvgoqc.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hvedzfht.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2frwknrvh.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2zxspzxgm.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmdrbsr.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkjnkax.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zausbjgp.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdgniiw.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmyarej.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bihxnwlx.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2okmqfqos.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2tayvphfq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhcywyf.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kngueajy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2slqqxhad.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2takuysrt.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqbndpc.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wltvuucl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2aeahsyvj.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvqmzld.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gihxnadz.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2jfozilwa.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2cidcbpbh.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2wqycywfd.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pagiofrq.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhrywgt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lxztnjmb.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqgflbq.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ihemmfxe.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwppljw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfigwyt.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgrqfcs.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2fiomtwey.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2nvaramfd.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnxelwz.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyxuhdo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnjdpsy.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fpugniii.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjejhyy.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcdekmg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjecavd.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ebctvpvu.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2bvytegbu.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2csjfdgsd.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2yervscdg.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxmryih.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwgqmts.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tuihqjis.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2eerlbyby.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmrbcvb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbwpwqt.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vnogeczp.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxwmymg.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2kiaqwrfj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2hamyadxj.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtyavrp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2njuhxuqv.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2rykbvhwq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhdkjis.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2fdomztme.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2tgumvytn.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2imsqaoin.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2rsosevtl.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2pftudebf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lfohotur.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxohvsm.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkulbuo.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2naktwjxx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vtedcecu.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dexwfytl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbgaeuj.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdfywtw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bmadvavj.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhftgna.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2czemelny.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfldltt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2byvsmazy.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2buqkakeq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwlkfeq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2qblifxtr.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnmmvxo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2icmnwvcs.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzjmynh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2benedeip.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2elzaknqe.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtibaxn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmsgqoq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwuxtoh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvilbwp.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxvttxi.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jacrncoj.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ezspxhel.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2eupaijjc.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2viplrgzt.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxxoblg.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2enghodad.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2corxuhrc.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxtrksg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2khwighsv.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnoyiey.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2osjfjgjj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzkbssa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2khsivdqn.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrtilup.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmclnqp.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrpalyn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmrvpid.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gysvqjnj.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwengzo.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wzospwxl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdlemhi.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mxniiwtk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqixphr.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2waourqqh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2endwujmb.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwrcuur.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jtenmxdb.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2whlezejj.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzoezbs.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcrnxod.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2aszxvvoj.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvciqyka.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2euyqvvie.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdufwav.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxgitkf.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xulnuxxh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2emfdcwyx.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxyvkpw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvshakg.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zpadodmt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2htoypysw.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jshwoozj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkrmgod.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkceqnm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mndxhdlt.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2srqqtmkb.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfalmtbo.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxfphta.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nirbzwah.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2akqpzdlg.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsneatcz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2erpfrjsh.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqmghse.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aastlxsw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2unpkxrjp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdvdsmx.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cltkwiel.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xwigdopv.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfkhrcc.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dczgnuxa.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrzfguw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuaffjh.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tczjpxbo.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtlpfob.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlnivgd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdqrkyd.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2myzhdqhz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyrwxwz.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqgrfzk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxglppip.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ivujqhxl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wywnyphb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zggacrpg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2orwblkai.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2abkhkwxz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wravtiil.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iiscipku.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdvhfmg.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzeeugu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvzbysd.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdcgiqk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbnyomu.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdsrqoc.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwwqikh.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2exioquzg.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2npjvesie.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2skpagrfx.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfuxpvuo.html


<!-- 参考信息 -->