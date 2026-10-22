代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oiihfnqw.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2otoxweie.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2saapjmti.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxgrswn.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2czhyvgor.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2otbpfsga.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2imphwxog.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zisfzorl.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sexyvjbt.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2qanbfjnb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2chxlhjox.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2csmvxbfi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyjscfe.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyoghgj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrilisyq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2byxgkvsm.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqfeqgx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnujaos.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxscfdg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2uoddcole.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kehgvjuc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2bokxtfwf.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2raqvabxn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ftuochkh.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ucviywdp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2atnauqgu.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dszlfsfr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbyvhaw.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuzezqv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwoqfpf.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2szpuquly.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2goryozck.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2zaaruacf.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iglindrc.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbhzqoh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhbxjsl.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxhpaxn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmpzsdx.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iypjcoyr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2yurnnjpa.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpohdag.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2iinsjjvp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mehjpqdw.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vyegklqy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlezpit.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqeyqpi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wowgnqba.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2swqzhjas.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hnberjur.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bisfvtwt.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2saczngah.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmaotsx.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2gmutavaw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2zcngyzhz.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jknqrdyi.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2scfqtzqz.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjtxrse.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fwusngya.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2yprqpgtj.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmtykom.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmorjzu.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2holhxaxu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlwukmi.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ushfmele.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpfxhpc.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2efndswqy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rmiozuel.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjwnnhg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oigamdpv.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2svizrmqm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kapvntvt.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wttgnjuy.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwvecqz.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzzdyme.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsmlpve.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2puktucno.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdszgep.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpthfgf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oszfjret.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfwmckz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qkenoodg.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2mkamradw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pabtixfl.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qkoukycd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwghabk.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eccsphxi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iopqacuh.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2rykzhybd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdkrnmt.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgvwmej.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pomhczrm.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rlomjoqv.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxqrgut.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2narimbdk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnmihpy.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jmiciwac.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tkuscgni.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2akslhhqu.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfzdaub.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfshdti.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrbqezi.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpspxck.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnhubzs.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrsajdz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkhdzgy.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vchkvlan.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2maoxjzli.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxbbnra.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qnalsnpk.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbqvyfo.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2balfotcm.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwimswo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkhfnta.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2iznajdyd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkwddhr.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmnjmhf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lawfadxw.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjeqndq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqndcma.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zlscnlqs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmognan.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2jehddbri.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2apkxmque.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqdotpi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqroity.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tolyzyzo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhyeabk.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sktjhnbg.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzvkbph.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmykikw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvtvpmk.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nawujskx.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2szmeelts.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqdrhae.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjrbdlo.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kytywory.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrqustm.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2wanotqlq.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjaavfm.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwzsqkz.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ychsclrg.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pyazepzz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zofhmulw.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnusnfs.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2rafhztpn.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rbaoiwrh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2adwknnju.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpkcklu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzjwelw.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgeilwh.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jlusifqt.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dujmyrxg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxslwys.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2effvwmxz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2khpqmgjn.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2gdiwxxjq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2deqvppqu.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzpzqos.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxtxqfu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2diozkeqg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2txzzqjll.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2obhieuib.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2onozspzs.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzcrazw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2aaztytym.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvbksnd.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2idwrrhmt.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2uttoogbr.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2blbzsqqk.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxcdthi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjbxohx.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ndozzfjm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tofiippi.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cswjnrns.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rngxbnaw.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrxhrzf.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zapycmre.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpsyhwm.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2srtwhzio.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qokjdpka.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzcxvfl.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jdguuqvp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajoafejg.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwjatwh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbmpksn.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kzemyhwk.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2csclhuqn.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvvaxjn.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2lujclmqg.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2utrfcvdl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbjebxd.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlwxjgd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrqkspv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbxavrq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkyoumn.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vehpkoea.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtdmpfu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2tsokhmqa.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyuphrs.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtchczd.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrzjbvw.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuihwdr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdbmmvf.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxvzday.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhthsrb.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rtapervv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2iurqiamp.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2cxadmpkc.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2woskkgcv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxogdxo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2crknnvbn.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2zepnahsu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwtwqml.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhtlmyn.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2flhiawpf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmbwnoq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdzqycw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqbvqjb.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rewknpau.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqrtrhu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omhiyohc.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kjoxexfx.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcnqaxc.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjowbjq.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2saftoghc.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqjpzxl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nljeqzer.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqitvad.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwpvnka.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2epnppnlj.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgpcqaz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2azcbwlyw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2obadquym.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2yyahwroc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpbezsi.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbaxijc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2hzewbmam.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfndksd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqrgbwo.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yptuqpcg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxtqhmo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhssgil.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtiweqxz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pkudjgqn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxapsdw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2oededvki.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyxsocx.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dorwxaqd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2gtuzyenw.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2inveswao.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtzwlqv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2hzauzhlp.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jillvazt.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tqipueis.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2udfwuexo.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmxcogh.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvaftoqv.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2liqpnbhj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2crdezvqj.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnkccxr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzdexjw.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zcujzzyo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzwiolz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtcmrlf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygilnxyr.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdxcblt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtlixrv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmhnruk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbmvwck.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxubzbf.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2erauyqjc.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbydaak.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2aykislrr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pvomkirn.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2toicguee.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrvynli.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyliiaxm.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hdztrmdp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrsubor.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvitzhq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fliolfyw.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvvrycf.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnggxxf.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sovmowmz.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2dslfzbjx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdjphyw.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uelzdwmw.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fndkbvsx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ositafjg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oykkrvhr.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2mrifkmoj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2viwqmjhm.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2daohabge.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbkbypl.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2rpamuyhu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmjczll.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2erjncczb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2utdlynih.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkpqoda.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uimakrtt.html


<!-- 参考信息 -->