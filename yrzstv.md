代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnhqzpl.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcytxqe.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvmmoyw.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kyazgsmu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgzwcph.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ykeewvlu.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bublguok.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2daoawewu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcdnqxw.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wckizmzr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2adrcmzdx.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2luqpfgch.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2azimijpp.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2znaplxll.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mddosjts.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2smnzjohk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2khuncdel.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrskmat.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2msksemyz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2umsapqxz.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ajujrtqf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2scmztngu.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjuknhr.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmrtcdo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2bidbrsto.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdjcaqt.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfkyvye.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2piwtrnsd.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvtskwl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhaqong.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjjhejt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsevdlru.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2hympiokh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzemwys.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzwrkqy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkdgrmc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpumrfj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2tnymlxjr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2veuaquog.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xgroivep.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxwuton.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2trclezyi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tliaicpk.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2durkilsv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ufulndnm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nosjxvma.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pohrxvkd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2mraeougd.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcxymye.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhslfjee.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpuuewi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgoxfje.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qepzvjrn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2azrtewas.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfkwhpp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqihekpc.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2plpdvbfw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwhanmw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwfwpku.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmekusv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkxegme.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2spojgtmk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbdmasw.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfzqxjk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdymvubl.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmlnrtm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pysipukc.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bxaxfxvb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2foruethc.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmknyfo.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2wolszexk.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ontpqtip.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzkomkg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxmsxdv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2echnemdr.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgpztjd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2httnvwpl.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuhvmql.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gukkycyh.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2gozncmus.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2evwocdsi.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnefjxv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcgohdh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oagrcrnd.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnjvqzb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dylekuor.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2uysgkytr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzzmtof.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrhybsf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdvfdfi.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjmetby.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzntqywr.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2emovjecj.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2lycrkpai.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyzvxcu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2plbabhls.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsepimj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgouyvj.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2bedfcifw.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqotnxit.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfojbpzc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgsiwtg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2xirehznv.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgiyxri.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecoetstb.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2rubbtahj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2lqszsiav.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nurtkqxd.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdugyyr.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2jahspspd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2nkicelbe.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kbeysybo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsiuuwh.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkzaprb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbrvflk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxmefll.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkmgljx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2digfmfzv.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2pudnurax.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcymbed.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zriqsbjw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2eivnditu.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfwtogu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqmyfmv.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ausonbzs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjvjnwz.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yewvgbiv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpskdjm.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wbafdceo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rayjxjvv.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eoskyqng.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqetejg.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2rkiztznw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgklauy.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2syiqppah.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuuftuf.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2emqagchl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxvsoen.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rwposkcz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuljzjxx.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxhfrac.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2otimddic.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iesnnsom.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2afcwmxlu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfvaojs.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsynmjo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzfgvtg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqcexzu.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmtfuag.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgxdrfg.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdmogrj.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2hgorsyay.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2emgmirap.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2bujcgjji.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuaecux.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hgafcsdn.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtendgx.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sracehzt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnatlvm.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbrvuow.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrbqybm.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqjttum.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etlkxtjm.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tszffgzk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxvkeco.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fovmbmgz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nglcrjla.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bshgavjd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2amibhyqq.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbedsby.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2joghfwpu.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2dyiiyoma.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2eenkkpnf.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdwqtuv.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdctuoq.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgodrzs.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2qkldaaxl.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oysxmzzv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jmraumoz.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vhohskaw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2byyfbuvk.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jowhvpin.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjfhgoa.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qisfrcqq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2epmpulxh.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcebbka.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2acaolrft.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcgtgeu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pazufnes.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2eckyzxee.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zizqwuje.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzvwgco.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uheldcwh.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpubexv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2umyjjoju.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjnrafe.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzpnzaw.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hzswhfbi.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvamyfm.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pincstuy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbypcym.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsqgoph.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2buzoobtt.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvlnxoj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxonohx.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2glovckiv.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdbdnov.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2knrdtlyw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzilhms.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhjpmeh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkrmaev.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tgignhop.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gspcexci.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2difdgwoq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2jufmnkgl.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hiiayzzq.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uozzegxf.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qzukmdzt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvprxau.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fertxeff.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2msjzkbtl.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfiwsxp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bibylosa.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xthzclpb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuztiux.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cvavhpmb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2bttidfbr.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wbybhsty.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtpcmig.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2umaxqwpd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zihttftr.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2erzbrtya.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgybyod.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2csspdltp.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2uukqfcxx.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjmjtzm.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqxmnjw.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzcrfcp.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kpycpaqq.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2drkezztt.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nenjnisv.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvakgnd.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnjduhl.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kpygvogp.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ibulkumo.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2knjgeqbb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnyphtd.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2njfuqcxw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbbpozv.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kckmkqdj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ushdxkwi.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrrycmy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2knwixddt.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyxdmwu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpawgmq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2eklluzkw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2svhwdraf.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2aolxjywh.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hgiwsfbs.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qaroydxl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cmletzgv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mycpjpgu.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyvgptj.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ondgdmon.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2kobtbcyu.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ahstrwjt.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2bucqpuyu.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2prjghcjx.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfntzgq.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qdshcbsv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfitqma.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjuehzt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwbqlma.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfqkzzv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2orwarjcu.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgttgdb.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2byvenjgf.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2chqkftmt.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2txenbytf.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ogefgihg.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2nzexlwhr.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cjldyqwb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqffcuce.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2foopasjw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2oypgvaud.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpmmlxy.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpyuppe.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2sjaitmza.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2mimkvrhk.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2aubvolbl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gndxlqwy.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2pciafomc.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2cnettsts.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhwtbuz.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdrsqqd.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jogbgwgo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivttpjss.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrlwcvn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fuoycuer.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsadeaa.html


<!-- 参考信息 -->