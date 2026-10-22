代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cetypkec.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2pxslydyg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2omrczvkl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nodyoged.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xsokesqt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzigsadh.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rammxgzc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqlbadp.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ppolcnua.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2plaeugaq.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mfaryyzc.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvzipcy.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2djqoyyia.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2urkyuppr.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvecxjq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2vftwfvfd.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ciaxnlyh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2bchvpeei.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2grlmnkvb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zykxjjcy.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2adsumrhq.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ocggeluu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2hovirsfl.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2szckramp.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfkpwng.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqehbik.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2umldbawy.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuthdov.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwydska.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcorrux.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tmeyartm.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nrronzgu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2cgumyfgw.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yuinbozb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhotgcez.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdlqbot.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjjmydw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnezfbc.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjlucvj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2odtdxlct.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtyccbs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2inoinaei.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyorfcn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ibklmtjq.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2uiuyizom.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzairnam.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyfopju.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfoiwsi.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbdvnsy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfaplroe.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hezpstpm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhgtsfx.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwkjiih.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipepzkbr.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdhtvqd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2erciytll.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkuupbh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrqihkl.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uqexxyta.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdjyxhi.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfusklh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjffvty.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqgibff.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxagrxy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2enutwruu.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxiwvsr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffeaopim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cthijmmh.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvialty.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qayhdbnq.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2mjobsiot.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrygexr.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsllayc.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzmcizl.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gotfjcsi.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhwddqh.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2siaawgag.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrftjga.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsokjpmv.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ouagbmkq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtcbjpm.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjubgxl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wficyoew.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vkawngmd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2albmegpd.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpbogau.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nlervpie.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqxrfyr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yveyjpun.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvpqrzd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2azwpwfqg.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2npvbimjh.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2lijgccuf.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuimlbwl.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2anqgywic.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kybunbqs.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfmsgni.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuyvdpg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwtpzlv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tircfuik.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2camvbbkp.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2uphvraar.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oflqgehm.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kduyisly.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2flkrdwri.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzvxbff.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnlqcaq.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2tpopwdxw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dlihchqm.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcgyfto.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrvokak.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hflhpesw.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vetukuzf.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwwdylo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2elkucbms.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2glxfpjam.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghacnunj.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqraljy.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2amhyibhi.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyxbfli.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkghbhd.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpbrgea.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbcuumv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfijkah.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vuosdjmk.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xaljxdun.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtiazin.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2prhmffwn.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrezqzy.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2iiggihju.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2upvgtiaz.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjvzumx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjlqjhj.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2adieojat.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjwnmlb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2auzkbdwh.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzdxonm.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcqesam.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsopjhy.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqifcqm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqigkvs.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjkhmpk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2epkevqnw.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzznrkd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2oggpbfgd.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkuglzh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2bapccmuo.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2svhxxfpk.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2okwvrvct.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkkroud.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwlgein.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2irhxirhi.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xcigfwvb.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2arlqjulr.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2sksxrgtv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tkflznix.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxbyopj.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2owkrizua.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbcgtxd.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsvytns.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkvwwwh.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rbokdyis.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnbsqkt.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2sslcffsq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzqfynx.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhsojjm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpsajyt.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2veibshij.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqsdhte.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fyghzdvq.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsvlxth.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhpwctf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpbtosb.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2btmthnfr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ciloupwn.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2okeozbhe.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2lolppflh.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2euvjfgii.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mndovovb.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zsavxagv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvtlyzy.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrdgdqn.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgvxxyh.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2mfycdzuz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2stvktoea.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdmsvgc.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2aceexcnf.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2gevpbcxr.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ieckcyef.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqucfru.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfvheqr.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwtxvkx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rybpgfoc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2oajyddgq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cofhmvwq.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhtebyi.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhnmrkr.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2txrkviwr.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2omdxmmjv.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dsykjkfj.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzfmexj.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcpuxkl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqevzasx.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2crvtpvwa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2wscsscqf.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgmhcah.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ehradmnh.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2bkczmlkk.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2lskjrsrk.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwdwlod.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oguonfbt.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmdfflo.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ggiydyep.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2oeykhzpc.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2wkynqhqv.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2anzjyspe.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ummhueqk.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2frqkwytv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mxaeajnp.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwxkfuv.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2azsspdkx.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfvhuac.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2syqzstnt.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbqfblt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2eamrjkhv.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lzyxmsdm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2filcqkxn.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2rennalxw.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2zwentauc.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhjiyff.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tswqzazb.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2rpffwhfb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2flvowqsm.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gltkebpi.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jrslhxul.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2foruhbum.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsvsyml.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2esigfbge.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ertyispb.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2kdajwsov.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vusyibqb.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpnjpin.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxduxbxc.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2oaaapxwh.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmuzxhe.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2dwozikww.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nuawvhnf.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tkiczvte.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mipczgyx.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fokdwzlm.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gdklotrn.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtqdswo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgzylhx.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2paachynn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrypfgt.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2vbotxjfi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjegqtk.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2skdkytyq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2psfpdkke.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxmsqxv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvixxfk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gazjauaq.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxeakgiz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2peasyitf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2clwmhaic.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqoogzz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qoadcbtd.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqjmbeg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rbttdykl.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2czxygleu.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mptmjwjr.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkqwbna.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbomjwcf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fncdcmwj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvtreyc.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqfxfuh.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2oblijnfx.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2abyzzzpd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhlzyfa.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2njzhjokj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtctqqa.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxzdrql.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfhhidk.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2icofdjin.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2eduwsiov.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ovncjonh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlcevmy.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2sswbcdfq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrtetrv.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mlobawjr.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcoqdlui.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzxthlp.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fidttdxc.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bypavowr.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpjgdbj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2spjyktrw.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuoszamd.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcetkqw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwdpzkp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2nnejvahq.html


<!-- 参考信息 -->