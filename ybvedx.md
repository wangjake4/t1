代发 wailian999

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zaftnmhq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjecrivh.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uozvhvxg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfohnwp.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2huxqfodb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppooinpn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsphhajp.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbalebg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjheeukw.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhbcrau.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wxitdmzd.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2njfvrvud.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhkugmz.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2qnluepuw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbedmyd.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjycrcj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jehdqibn.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcvnzja.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxkyyit.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhftiiku.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqglnqix.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqpuora.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2thguqber.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fnufdlox.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iecofgwy.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqypxld.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmcogbi.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnfhhdl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bytndsqf.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gnurtunp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2dyeshcio.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqdjswy.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2loerflkv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cywfpyeh.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqtwtmv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxzbvmj.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfzjsvs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzdqasx.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nqacvbqh.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xeimkbov.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlepxxg.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvigizti.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lkehcwti.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqctzcqg.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2oimmdaxd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlqgmpp.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcgccqr.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpcqytw.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjllybsw.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnjrjou.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkvqgbj.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2kuihvqwf.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifoxpcpi.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2gzquktnl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2melkngat.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pbyrtzpi.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxdyddv.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxgqylu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2krmeszxm.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfckvlr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2swbrfaxb.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqsbwsi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhguvpdl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjzbqfo.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqpajhf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkhujkn.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2krrsdbjl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2zpusxcvy.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bpezaxnf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2gykdiwmu.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzefkrw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2dboxfqfm.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcbxtrn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehefeuns.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdaggeu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbfmfqe.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhcdjgh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2enccqemq.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gelgfihn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpdnbxr.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2scwswkud.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjigkss.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhqexdc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2itpempep.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ellfrrsd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2zgaiycsn.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2efjmwssm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqiivuq.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrhmway.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2paaxflib.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vulwbncg.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lmoyfpca.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2awxtkfoz.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2aesbbeln.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjwvcmt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjfyxkn.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2kexsqgsp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgdsjyu.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bsthsqtl.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtcrmhs.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbfsyrv.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2vfeeeckj.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbxlywm.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zossrfiz.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ottwgwvg.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vhamldko.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2poisydna.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzhjnqf.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kktbdrzv.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kastjuep.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgakqbnt.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbnusmf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2slptalgl.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhffwkt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pkimlgpq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxitmvr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cexrpiho.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjepdma.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2eikjvexq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2srahzava.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkvcddx.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxeecnc.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bljydwwr.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mskafbxj.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhiykav.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpcfhxu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2klagiopb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lldrlqca.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gzimhzuo.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxwgrhz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ouatfsnq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nahpszty.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnxkrwa.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmbwwtq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2chgqcwjq.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxdbgru.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtcydte.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rysyyrpg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2orpzyhdq.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvlzkur.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvmlstv.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbljvtyd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2umnfbvqq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnhyokx.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgaiuidq.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hhuvjokr.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2olacsvrj.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqomhpf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jumltmyn.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfduuhz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcaoboe.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ddklhuds.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pepqwata.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyaffbj.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2cuaabmlu.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2hgygyscd.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2pnryamtz.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2cedmqnoc.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgxgyvd.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2opczttrv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfpxuny.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ywthzgym.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2nejauror.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zjaigaqz.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixennipi.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2exoqtxyr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkurvkux.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqlkcqg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ppewvsuw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2xeowziqy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhapfzc.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2geafmlov.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2clocrvei.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fyeoadar.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2bivncztp.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xyphsmyo.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2slptvqii.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ravqfyxf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzfjgii.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2azkeqmln.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2eedhobtg.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pugaeqeg.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmvpxjv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbbmkwg.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmufrjl.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2btgdiedr.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwgwibh.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxptafa.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmjognk.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpxvfji.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nplaovsr.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsoeuva.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwtdpps.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2byhwpztx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdqwanp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmmknpd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzsypef.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wxelisdq.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxaexiz.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxtaepj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2goakwzlt.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vmltlirf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnsrbom.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfsnxfa.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdugmhn.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpyarrf.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rgswgmyl.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhbvxkc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gutxwybs.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tjuqipzb.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nabsbcjo.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2mnaxleum.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzdlesi.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqoeehq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2sefqluyq.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ontzjbgm.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjjabdt.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qbysklsi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2whuigfkt.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xmuyronz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fhflepqd.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2anvaixbc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zimltltl.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dtedblmw.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2pctcnjdo.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjfgkpy.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2emjmpafz.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qbenoxyd.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmdljpf.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2naggazfb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2xymxqlsa.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xdiauypr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfewpmc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyxtdip.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ginzkbdp.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzrlcyu.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2irzceeqj.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2deqmmyju.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqkstrp.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgjftyv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2vdysibsx.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwijihe.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2juvcurko.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvbeirs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2zyahppwr.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxzxblz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdereib.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lratidmp.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2fbczpltl.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfdwncx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgskrgf.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmukgld.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvuzbms.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbdioxd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2scdewrzb.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2oiolkeou.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2vptuvsoo.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ueoncrur.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2omjluyhw.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2kcuxezcu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rszswgsi.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwcwsqa.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2clsgoczw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bsegqmff.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpqnlgy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjpyodv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvnipdq.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbquslg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwlrxzj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2eyutpxsj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2iuulvkru.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2aonoumxo.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzutrkbe.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xspejcdj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgvezcu.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2daquvlml.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaccmgfm.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ryypwfbd.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2nixxtvuz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rztolual.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgvtjvo.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2vijxfynw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2cabyhvae.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2bkiqbkdw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xucmktdb.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2xoeqcblr.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2neksynzf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpkliou.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcihgmb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvlpqlh.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vulhqfzb.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lihxeirv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkqzrzs.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxssylx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rcuosfsx.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzvpsmz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzairem.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlcjvwo.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xddjhmwv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgqmmin.html


<!-- 参考信息 -->