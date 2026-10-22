代发 wailian999

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzehgfa.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpnmadh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmdbwjz.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mteztoxf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2afvaiagi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ifscbjyz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2acnvnsey.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2esimsvsj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkfegyg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpfwvcw.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nedjvidv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfjgtra.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpvyhyy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpceoqg.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzsmfge.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbkqwwv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxhbbys.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdykzcq.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvztroe.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrvvbbc.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ophkgjct.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcemhsw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgiglqpa.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hawiogvw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjsswgo.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2occoqzgc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gaecihqv.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ortvtrql.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqwfigv.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2aomdunar.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uynsztrl.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2iocbaubf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgssjpe.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2avccjwcq.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxofzmu.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ulznydvx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtpfevj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2adtykafj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfzkvqg.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkqbbxi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwmeujb.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2unajutqp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wviftehs.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2demkkbst.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjyvpsz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmywpal.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2wkevizgg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2axonshop.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqtsbtc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2grwycelv.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfbxxxv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qauguxmw.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vmiqtvus.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtxjaqq.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2beruhevl.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2cumbfbmg.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhnbkud.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbagqvhb.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jjckcwdl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2pblqgqgz.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2lnilwtrn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2aztvcdga.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdopvbs.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdstpju.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpgomnf.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdqjiwp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2twtfiico.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ybeqekkb.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ektvmwqi.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgfbbzc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2miwjvzab.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzlamhk.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2focshwjn.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzaaiiw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmojjaf.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfyfuyf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2psolfkzu.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqwwdvz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjinbisi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2cybhouho.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcbejhq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjumfbz.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2odahjfed.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2jiirqjjc.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwbcewb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2nugerbrm.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxozpjd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2aybhkznz.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2osleroos.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbqeffy.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qfinpgia.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2irzrgftz.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kukioqim.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzqwngs.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuxyrvm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpedlel.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvgaalv.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuusbri.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2jtndfcck.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsbgzgg.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbmhbeu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qsznfpja.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmxvibt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtaeoon.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2dibsrfpy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2fodnkaaz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlyrxkwc.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnpilux.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bvuenehp.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ahggiwya.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbaznuru.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eppdktam.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2onhwknwz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jhidouus.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2aafoguxu.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2spzrxxgc.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdjxeed.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2pyihjsws.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tffavydk.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrcntmm.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrweyoj.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pkoioaac.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsymvaf.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vfohnkzt.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlddunz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqzavqv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnwfoas.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dcewtjuu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwdxuqt.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjannbr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxwkdgq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qszljovq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qlaisdri.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2anniyhet.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sropojgp.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2dtslajrm.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2njwcgzys.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2slwzhvqo.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2epsgkcrl.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjqtrku.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2pugakvyz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iydyzwya.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2buvdrnvn.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgrhegl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqtscop.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2boifbfdk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzeewxa.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eewzwqya.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jmecqecp.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jogrbnqd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2evnunzda.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2evpeobmg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwjfuna.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bujfyboe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nayfxelw.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ortabzjo.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2irywvghf.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxlcnvy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbffatcc.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjjiqgn.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kczfedhe.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwwiakx.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2phahbzpn.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ourribrx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xuiehabn.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vquzlpus.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fiodprdy.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2bidlbckf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvftdcfo.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpovykw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbozflr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgmmjer.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2mklxxbpt.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2pyquxuqr.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlslnlm.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2impzdipt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rywccfmb.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsncgda.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvosxcf.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aibtmlwe.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdvrssm.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtmejvb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dknlqoae.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gidvxdwl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2fdppysug.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2kodlqphh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zaloexdd.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2svxaylbc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2brjejuxb.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2edbajqes.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgfrxox.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzqwpqf.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiblqjl.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzvsson.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrmmtom.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqsjvtj.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2srjawzsl.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpyxgdo.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkfawbf.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bulyzesx.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzllfxd.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2fslyozdr.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rrylyjml.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrbggzr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgqipvl.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wapptxup.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrzzpjm.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrxzjkj.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ppejllnm.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkqbxwx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2smmkilss.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfnsrjf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mjckhmow.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqlcpbj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2syyjnzim.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcxrigf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2bekiczte.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hxynpefy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkyalax.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2jywlgljr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2leyouqur.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2mktbwkcf.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhmxjap.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmryiij.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbtrgpb.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmqxhqe.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fodsrtnt.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2yissrgeq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2oioqkibg.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2khhyunxz.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2vppvfjfb.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqlqcsk.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2pfofdyss.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwknbrl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2buoganwe.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bndwugbd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbsxjlu.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2udaxwhmx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rlekfsxh.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbyhthg.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbzgvvv.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxfqkbt.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzqrnyn.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlzwcur.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjfuczc.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2iserocgb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ookpqxqu.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2buczckpa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2rthjiulr.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fiktrzvd.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lanrxxdi.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2woxqvonl.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2cpduiodn.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrayqgi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nivizani.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyrfemh.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqlchbe.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbqkqym.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xloifogx.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2shzslghf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkubwtr.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvukgsh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mpswhbha.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sogjobse.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcntyvs.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxtfjqf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvkmork.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbsvtau.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2uxiattoj.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrnufqt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2stprcokw.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbmntyq.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xupoyiiv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmuiodn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qprawyta.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2cgldquhx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qosfnbaf.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxelimc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2mortkgml.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xgarwabs.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wcoqimjd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qlylbkua.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2embocpsw.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbmcixq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2suubyyer.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2evuorcsc.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hckwosgt.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2enrwmsql.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2miscenke.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2etvdbdra.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkudify.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxhuxyq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfeoffl.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oodztxhr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2caxadoin.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zctizjsq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2punggbpo.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuyxrzw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqpxtil.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2tyadtkfd.html


<!-- 参考信息 -->