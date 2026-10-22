代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcmitjp.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmwyqgu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjstpen.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxuunng.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2siypeiin.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtaioos.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejflvxkz.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxgvtjn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdomdlt.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjhjmlp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2drrmwsnl.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2duireigh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aewllhnf.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2clhpvpru.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2xikotvly.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqklffzc.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2brxxrqfr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqodtcsf.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgqdfdq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpiagqdt.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwpjiun.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2czqzdbxm.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mosoxyhr.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2fznkjohi.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbgjksg.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2terqeoff.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvmebrw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2fviifomu.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2zacsbnav.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2relpqmaf.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2kivwbbob.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2axxfsfqs.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2injsxrti.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jcavaaxb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzykaqh.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xknohfjo.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oivbcprg.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbbzprs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2kilwqyar.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wgucehfp.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2daflypas.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzboqje.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfrewic.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhlbfkt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfmczaq.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ntycqovr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hugpinwi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhjbpxx.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2agmrmlnt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2geipwujh.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2yeblbslp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyfarlh.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwwycib.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2hzphuhqn.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2aywhwzxc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2lptgekuh.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmbobsu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqissdc.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rxshxsyp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mukezjcc.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cmccbepc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqljoky.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2awuhmsqw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2udygiwmo.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuuweuf.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbcyskk.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2tncglyko.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2omipvzgz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bywrlmxu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwdadcu.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pbapncvx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfecpqbb.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kiorgxwf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2zqivwllp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mubqowpl.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqkuror.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fffdolhp.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2kqspwecq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2roztsjwh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbcedek.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrziifn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrpevic.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2nwohxroq.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2qsauzdxe.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2lthuzqlu.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2uvplgdcd.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzfdfze.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtzzcrt.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2pevcxito.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jqejozdg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpaptkws.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zcruasxb.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2skaishaa.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mchhmngy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uygtiwqm.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lknbwczt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2byufpnaa.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wcceoiod.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcrlngx.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvplfwq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvhregf.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfiwnpg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxprirf.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2cabwpzmu.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgujmws.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxajtafo.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtkxsdu.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsugicsl.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2znfatebq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tsojzvhn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdrucet.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iycujygs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrsxhgc.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzhrvwl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrlcvba.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpfvrby.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jotexffn.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lzezcdfa.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhngcsp.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2pjobizur.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhmuzlb.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2crtmtwdc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sidieqbe.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wdplkprw.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtxeauv.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvveyczd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmxncqg.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxwmyyh.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nbemjmfa.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2iprwvbqs.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2efgcthdk.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2umesivmy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcquvaq.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2udiduhlc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyzemyq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2lojqazux.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gekkbrac.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwubwzo.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwllpjpb.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbsdddu.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2fuztovqo.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2uizqivsl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqqsfpc.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgenzlg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iucsytxc.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjgccnf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwbrrzp.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xfquogeu.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jstliwnw.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2auqefeev.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aufnlscy.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2khskhhxy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2isaosvce.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2wopxlmec.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lputndva.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2emyighct.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkeccpj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2npurdnsl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmyyepg.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2svwslblw.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ullkjpsk.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxrmtvq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2onbqpqxb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmamapd.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2myxbslbn.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rvuojnbw.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jakdttji.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2abxkndor.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xulupatw.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2epexjwgj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jihpcxeu.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xumtzgxr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxdmvwp.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmkhlin.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wjopotct.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrjezxv.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtibevl.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jajjgzmw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2nankltpp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2crmvbmtq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nglkzzby.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgsmoby.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sgncutmx.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rppilrzi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2utyfkuiz.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtsruep.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mrakqdpd.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsjbdau.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlqbvvc.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2jlobutpq.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fhguyeab.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uthjmevo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2egbupejq.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bddjtfiz.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmovpui.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2mtttetwe.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2wqredvnn.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vromxeqo.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2onpqjhnv.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vzoklqbq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2eccsowwm.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sevpfhwl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2awklhxnq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbbedvk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2utauvrhg.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2elzokfak.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yexthizb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxoxugp.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2eihshtua.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdcsvkc.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2fevzxjda.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrvftnj.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ryknmddu.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2acnghixj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgxcxnb.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsnlkbm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zxexxrhw.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2euuajegk.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2diifahdu.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfpuxon.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfejefw.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkyswpt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvtqkxg.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxyetfj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgepxyc.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2lgleekto.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzzkvxe.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmkpxgu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvynpoz.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqbalsb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kaofmion.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kkuifntt.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfuyhhu.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdzddik.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oiefcjod.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsrmvrj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2tueknyzo.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rthzpqqb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmakfhp.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnmhdsu.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzplljh.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2npxjdbsm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rbchbqpn.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2htfsgqhe.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwkxvxo.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2miondjpg.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2wozkgwdd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjgpodo.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gziudunf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwigwig.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qjojijem.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2radoujxs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzopzvj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mziurygd.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbyvwft.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jddaygty.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvqmuve.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2uwutebwn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqsnjpc.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsrgyzx.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2psrbocdo.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnsyfzo.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xepwqtjc.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pyamqbkx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vgajmptu.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2cftvtrwg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbvnyci.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqntguz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpudkhh.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbbibqf.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdacajbo.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2slufjhzc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtmocve.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeoorbcn.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmfmpnt.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2moaauaaz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhokmiif.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmqwqvj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpxyfvi.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jisfhrhl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbsgtgl.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfcwxki.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mglfiumd.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2uaiquvgj.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgmqynn.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2axxllead.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwtauoz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yyghlmbp.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxymhybe.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbsfcip.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbxdfio.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2buclemrk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2poxjujaz.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nrghlcok.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2mahpyjbj.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vxegdgmv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2iigcmfzv.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2unvftpiz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2oacuaewo.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tijyzlgo.html


<!-- 参考信息 -->