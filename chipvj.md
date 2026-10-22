代发 wailian999

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2nohdnfhb.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gosssteq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkmjylg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxnystm.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvwxicl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdxfehk.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2kpskgxlp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ileuleph.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdmyhsq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfrclcn.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsufdfb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2anukhwov.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2woxuhrnb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjjifoh.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ifprjvvt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2voigslxx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfyomgw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgzxscc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bjumrubp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkvlrkg.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2xtogdpjs.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgzzxyw.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2rovncwmx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2juezrnqh.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ekihftja.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdoadaj.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jifsibkz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2putgoiew.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2oklerkym.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2xkerdysm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjutuvs.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dhygldzc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fubwnmzw.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2uewybjep.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzhdzrk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yblxiugl.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2arocvera.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2acbqkjud.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2evokvnut.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2skuqlyey.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ywflvfzz.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhzulyu.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvoslycz.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzmbmeq.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdhrktw.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqbumfi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbovkpnk.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcaietn.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwlbnqk.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gesrlczs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwejjkjh.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2smxrnjyh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iaesqjye.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmikssz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlzcbrm.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxorodq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wilddglz.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqskswz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lnknwvqp.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2clnqyhxa.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrwoqpb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zibothth.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcakjniu.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rblhscam.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzesvak.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcvoucx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dcawlbfl.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jawbizhf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hekuzici.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgfymap.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbikwey.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hissrhtw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rluujgew.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qohkphyq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfegqal.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvlfcwm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjlcggw.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrtnfec.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kjejdodq.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpeqoka.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2majgvnka.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgfqwjv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2duzsdfvp.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2okhfumql.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2timmtnjy.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrouzro.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzidkaxe.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2czupigxr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdhjzrx.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eiswbbue.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvbtjho.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcpcrav.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjwqgdw.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yherdcme.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcxpdxk.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfrexiy.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2agmsndgc.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2asdzebll.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2wreoxhjs.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jynfbedy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tuekyocz.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vntgtskt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlzlvmh.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfapqki.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzavzyr.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hxctgien.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrfbinh.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rptljxhf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdjyaxd.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2idmsuitn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2uydlcpku.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2aejorjrr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzkovdl.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2crhpisrk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2knrgcjvz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uokkgqod.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyoeytu.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwqteod.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlpxlef.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2piawqvnx.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpnmmcl.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iljtblri.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2liyujqtc.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwvxpbz.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wcylxuyg.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvxfqmx.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwbxrkg.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vjchghjk.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2svmzjhhm.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lqamztiw.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwtwilf.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqamwlx.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjgoqmz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwexzbo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2cibkpchj.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tunwbbpq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2imdmgrdt.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ktudtuwe.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrouekg.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmlkrir.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2aylywoyd.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rkynyhzg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2unsrxgsg.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2cwctprgs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2npkofakm.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2hexjkibo.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnnqqhy.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gcesnrlc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrbgyxs.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgbnfhj.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hgshttuo.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rnirzrdd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnrzjdi.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwlupie.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhrmicl.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2yezxnejs.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2qffnpihb.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnnqrer.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2vpudllzi.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhtxgjz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lzizbzuu.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bakvzbkp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmrxfke.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfduinh.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2oromneco.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrxhwgf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2yemlmlvv.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkolfmw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgoehcf.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgxmcpa.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvodcdmb.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gielyjrz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2easywiul.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2holjrgek.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ypywbxgg.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2likmqvsh.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpvrkqn.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqbsrzr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pddjcwit.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwrolgo.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2vfutetxw.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2otgiaesn.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2okmoasax.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qpljrdmh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdxvbxl.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ynldnvdk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwavhxp.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dhaehalo.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqcspny.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlwbdso.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxydcvn.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxxikcy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxigeht.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmxcpnw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpbbmoz.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2eancdrfi.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqsffft.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzuqxwv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jusheenh.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2dewkkwmx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvlkuxl.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkpbhfr.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlunifn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqvsnkv.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmtwuiz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tdalffwi.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dbreuivt.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2bnuuwwzp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfecedr.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lktmwxor.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjotobl.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yantzhhg.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nseastds.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdrifxm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zcywlxix.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnbyuzs.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqhoqao.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wswcbdvg.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2frnaomvl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfjkivr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbsadnv.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qxowsdct.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfdpjpy.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2spaawywk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2yeonesfa.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfqfwjs.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkeqpdn.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhftkvp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2sxemmnta.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcgnlea.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2aikdmfet.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kicsgowh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rggzlmmy.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfihvef.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2pavijcqr.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsucwcu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqhopib.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2clcxinkn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2autmxwqt.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsxnkbn.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2makobgfk.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lysksavb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsywyux.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zeesqije.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2knphybdr.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvyybnc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cesffqrv.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqqnycc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mitelygy.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyankzx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2heiczvwg.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kehwvftf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkyodjh.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmsdjvh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrxpxrx.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ougxmoqr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2gajqrfpe.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2poshlvky.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrodmkku.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2rruphtds.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnghykew.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jyiiyyha.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpunimq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2atywgxxs.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2sevxgbos.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjidreq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsfeqeu.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkrmbvb.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwpoetc.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kyekseug.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsygcbp.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2henytybp.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzejfva.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rftzbeld.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxvzcme.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdhqfxl.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2kbganaji.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzswinx.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2yydczymr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2viurxwbs.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2adatzljm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2upxmoioy.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnkifzf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgflyaia.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjvtxyv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpxlkrm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2crwrcxss.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2odzdsori.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxaaplm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2dfiasjzl.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdbzcsx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjfwuwq.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sznvhjdh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bepdoidw.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvsdbgi.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zspyidvj.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lthwxruv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnuzjjer.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsahhue.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjctfmgd.html


<!-- 参考信息 -->