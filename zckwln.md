代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxuebpau.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lulmjptl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmyziou.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2bqomffst.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mybqgpat.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhboxky.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2gfevknue.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2swafulnc.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kpoablva.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fppysxbg.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwqhrux.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeucdinq.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxyokci.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2sulpncwz.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kklgsgmg.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2diimiomp.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjhtyrd.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbsilqm.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwicjri.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrotwdds.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ruecxuix.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2betshqyq.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2mloanezy.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dllnosfe.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sogveolw.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2kctcmyks.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2dzojiesf.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxigzum.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ablglsmg.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2igfdjuyl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2qdivgyzf.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2iiudnxsq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmncoztu.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjtqpfb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cveosfyf.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kejjoyhv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwktrtj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bibbnzva.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxbwclx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdapfoc.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2svtogqvx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzfymjj.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkczfoq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvtrxrn.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhgycje.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzkdlby.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzlolsk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2veqtjyrw.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2hxahtrqi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmocjxa.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kixflgvx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnccycs.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hybrqykk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxdqxfy.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qopnbctz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uivmqfgb.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ntoltmcy.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdrvrfh.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2nfooffav.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxrgkfx.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ykooxfaj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2awawjssf.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gepngcna.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjyhhoh.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnohbjj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2zcuxpdjv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvuqnve.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tukuyngn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cubprcvz.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnqsjxh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkmladi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvsvnkk.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2anbcxrwb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2shwagfjz.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmjnsmx.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrmrtge.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwbjztw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2bfukimpb.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfvosqd.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjsnnog.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2gckgkbdt.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lsiyiatv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgpdkiz.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnydjfj.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2brptdsql.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkwkbbs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onupzihc.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bsohware.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2heomrvyg.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2swwlkjxj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpvjxyn.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlgjyoy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyaweyf.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2galxhetj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uijxcyrq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2mliilkuc.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2hwerqgqh.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqifvyk.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcdkcir.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2exgsmzqj.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqntuyf.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2knzkrkxa.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjqykdv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dwaruluz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2huketpxl.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2fygucilr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2baxmxmka.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2usrksgbk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2doiswuso.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmpirkd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fezdahvg.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2wctzbbmp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbknzrv.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2livfboxc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zldkexlx.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cgiaiodl.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmichdw.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhsdvse.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwykaypk.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kfklddde.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wivgzodd.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hyeoywry.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2efczdalo.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hwikvzlu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2upxfhmzz.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsdqhqm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvahzjvd.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbwnfmr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozuaaxym.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ybswsvhs.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvqpplt.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2thggxqqh.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qomspukf.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvzjekt.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjprtlo.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cqeakjfg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2appsrdnd.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2yenhwhqt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qphchdxg.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yppxalbp.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzznjzy.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfavvzj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vquxwfvg.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dafehqrw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ylypmwjv.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2laborvkc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzbknwe.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnevucs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwbvkbe.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2thngutzd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2engwmejj.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2riatjbxz.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxixpwu.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2sptjenhe.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ppstticr.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkvouhw.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2adlhhqjw.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqfgaxa.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cvacxorr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pbeicofh.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nridrszb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjpolgs.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jblnsjmh.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnijahk.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtcinsb.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsfinhl.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2evctmaok.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kalugyyk.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2rspbupns.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2cugfduqq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2onzpxeno.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iobbleeg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqdcpgv.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xnyfjmzh.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cnaddhka.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2istgrsfl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dekuxchl.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yxslgbar.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtvqxri.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2bvynvimq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qywzwkfr.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2rilquaos.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwiprfs.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2okalmrpf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2juvcrmny.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrpgqfs.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gqloksvg.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2osksqnyu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2vyipviyk.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uvenmwss.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ihplckdy.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcxwkrp.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2waxzicwe.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ssntcrqj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2psasbkda.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrqmmrz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkuaxsd.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2entbrfmz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmfztui.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2peqpvbsb.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2tudmbngd.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fdroxfrc.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2uegjdkug.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzwkufw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqjbcxg.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtkaqzs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiddqobx.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmylloq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnlrger.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yvekqbbo.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ultqufcy.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2gszoghir.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2zislrkyv.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxaqcmo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqfbmpz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2gwerjgtf.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2oigveezr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2acemtkru.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2cynpfscf.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrsdkjy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2midtbvzx.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqvofqs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkjahve.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwjiflp.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqurwkf.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2gfibfutu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtzwzru.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dykfftka.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2crogxjvv.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmopcyp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2esgmcbfa.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wrflfnck.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2pbilrqxs.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2crnivews.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nprgtlpb.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzedgbi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2isfqqyhz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2urwbucqu.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2yswfqmfy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxqacws.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfsiejv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcebtxm.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbbjczu.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxongyl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpatalvd.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fdadklwj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnyszvk.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2uufconbb.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xacwwaam.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqlvpfx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fgstptbj.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmvsedn.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfddlzbt.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2thzfygio.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdkpvmf.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxxdtmq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrvptns.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2umyhjnqi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ircmycqu.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qafcckbi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2uvljbxsn.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyifkln.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzyuipqz.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nwonajmq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2zaihftwz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tukqllbq.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2osmaokpv.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcvjpkd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvfkbak.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xdehtzju.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrjdtvj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqvpbso.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwzgutf.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2disvthed.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wcaojocg.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwktsvc.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xutfrinl.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dbeuqopz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvsztza.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tflvvpgk.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2awynrvmr.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qxntdzer.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2evuqabfh.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jmuiqaet.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwxlrik.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qkowfdmg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2jescyatt.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2brfbdlfj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2frxkgzpo.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnotyhe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kabhassf.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpqajtr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2letfzblf.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdzanvv.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ityhacdy.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2madoebyz.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqboxorp.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqcsivt.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2raysbzou.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkfatpr.html


<!-- 参考信息 -->