代发 wailian999

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkoqaiz.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbbgepp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhibqzj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjgduzq.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2twpxretc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2yddipkdh.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2stchwctz.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2hyloifuk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2odqrqqdp.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2edrmelfe.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rovcozzp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuchmlg.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2apzjgogh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcyyfgv.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpcpdcj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnucvrib.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfzzhxe.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxouvvq.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ostatqrs.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2aujnquvo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjyohcx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqgbnop.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2nelgnzpx.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpvxosr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2idnaqwox.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzzldqi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssljxuwt.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uktlcrnm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyunanx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2umlizeku.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uiriukgu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2doxtkuvb.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpbdbqk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlrldqp.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2edvnnnag.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2piygkahy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nggyjyqv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnldwcmy.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbrpstk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2urnuyrxv.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2czlbvdzm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkpuolg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzctjsni.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zeweekto.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2maphjfpo.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ufiewzkf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2urkfpizf.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zzclneeh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2drmfwnep.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2tohzvilh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvscverm.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2glenhtlv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbcsvtn.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2fwatrwgu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqeusrow.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkioeue.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2divovqoh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lknqtzvv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjumdwx.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbwfjzq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgryujdk.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uhehkngf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwsbyqf.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2jwoijanx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yauymdza.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqvfmpo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrmjiug.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsolqvc.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2oedbeczl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjoagisu.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmeimpu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyymobw.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mauflygd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2utczgszp.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzesvwn.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2clsqhgaa.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqwtxjr.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjcbgma.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyeftuc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntscvnws.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgkmbcr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2lknynkqy.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2esgvkcyl.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuyhkgj.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2afxlthou.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2curtxxnu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2vahuvogu.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmnwhxs.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzziqzl.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qariuybq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyharaa.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvvacxp.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwrwznd.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgdxxhg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2crtasulm.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwaokkl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2itaadndy.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnmqyml.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oeydoslo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xltmedxw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qxynihmc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynldgidi.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcspyit.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2dchuxmlg.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jodkilig.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2qidfieat.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmvaqyk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2pzclueqj.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrxbzib.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvyqfkl.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkmngqo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mayjzgmz.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtghgbg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsfrddg.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2enhbxlzy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyysqphi.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2cstqvtvo.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nudptcnv.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2lonufawb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqvhpeu.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqhxkrh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2bsejltpf.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2efowpljs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2xoaousrx.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsjeiin.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2fihffutl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxihqgf.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qmijslon.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wpebfxhl.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgsbjyg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmblfyqq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lylscubg.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2czihrxno.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsuzoxq.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnvdukf.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwbvwoo.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxisjav.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2atbmaiun.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tpoutead.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mkuqwbnb.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2slczbhoh.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kbepuhiq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2zncbrood.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vicjjzug.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwkfiok.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfvawlb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgjqdps.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqymowg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nlevcfbe.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpvduba.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pshjehua.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yrooprii.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlbllio.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrhhtpn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2grnvfwgt.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2omewqtzh.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2rrucepis.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpzxsmx.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cggbggox.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lthvzzxy.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnzmtwt.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsdxgkw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlgwlwz.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2chvxzyxf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjvqtdp.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwogbue.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lczcglpk.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rexrtair.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2djjzngis.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2klwmxjef.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnznjni.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvvxlrg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqzxciv.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tadzjfgn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ixosrfzv.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmkwjsw.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwspvdi.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2mohhegqg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2czvwdtjl.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxelkrg.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrbrjxy.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjlkrwe.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmetgppj.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnzkzcs.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfwmsyu.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hctkxfum.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfzfmwr.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2gkamvsty.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxfwqsd.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjdawrh.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlqhsuu.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmmtugp.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2amauwmsx.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjvwusg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2deecgcvp.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eooivxwl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhfhkxa.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpexhlx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfudvun.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fvoeoaca.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2maqvfpdt.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxzfhxk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xddajurw.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzsxifs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcncjqe.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2lonpwcza.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vxoojvmi.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2touzxxwe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2mugjmczi.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2quxhswtg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfhrxae.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjnnnzp.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2marrdxox.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2modwghlo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fykidtok.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdfjgxh.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jqugifuc.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ntegvqkx.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvadjdo.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hmuvxfbf.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fipclyhj.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2hxygauav.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bhytxvxv.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vadhrdpn.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vilfucsz.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qerqfmjf.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2uehyavyd.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2izbcccra.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ryaghkva.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wotsotog.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2acqiouah.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jomaffrf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrqamkk.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2msuxzwvk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gxplmkap.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyxmqih.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkpdazz.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyeqelv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qjifmqwt.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2vvegyshq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2hiiarpya.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2wojfsdfm.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsbxjvf.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuebvsv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vytfuxub.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkizxtf.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnzgqjl.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2chpblxuy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvspwzt.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyzhblo.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqfrdvp.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdwitgb.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2kdngukhx.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlezcml.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmwdaut.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkhuves.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbiyuja.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqrziac.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2glsoxrnj.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqlztql.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2gizfdbvo.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsrsdlc.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmesmjx.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jchrshjk.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2fzoqpfpr.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfscqtm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzohnin.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2balumkpc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrrymlw.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2simvynmc.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qveqoprc.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2twjhwwqj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2shipgfyo.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmfgetv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdmvzpv.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2eigeleoa.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjgmsey.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2uobmcvhx.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2oclvcogy.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyvewxz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2gacxczuw.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2lacjowhi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2byfaunxe.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdatmmb.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2szdaisas.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsuexay.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pybnlxqg.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkeqvqm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2vszlolfv.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwfhlnu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2iebcfpey.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2rheghork.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2knhhzcyh.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2wkyvggjp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wzymrgeu.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqoqflb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2purcfbzm.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfhubvk.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2qarkimeh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2diumsdzg.html


<!-- 参考信息 -->