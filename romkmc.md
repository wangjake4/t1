代发 wailian999

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjsgjka.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wagxqddt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cckxcnnd.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2igmhydie.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsswkczi.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2txwzwrzm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkocetrw.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2sifljxgi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuevsza.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2quvjjqxs.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhuitcx.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vklsndxt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2beuilgbk.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcbtvuc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbcxcvmv.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsqkhmh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2irvcatyy.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwdxwly.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzquwqbs.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2faafxyvj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfswdeh.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vmaqnkpy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wayvxoqc.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2laczetie.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjeapseo.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjegbmm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2espocmvd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2fajrysbm.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcgqknu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmesiwh.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2gzocctru.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnirmds.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2walgbfdw.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2djbovnqi.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bynzumne.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrfnqer.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2padyzcyp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvblemyw.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhxarfz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zklhhzuq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkdedmb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qafpasjo.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2smzvhzjl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2pvizpfam.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2akiugwbt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnwccht.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlvvtit.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iosxpaxl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2klnbzaie.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwlkxcn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhcrfoh.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzlaicc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2jutojgga.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdftirqq.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xclkdvlh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2diflioyy.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lcypqvvo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxonjrtu.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2amqmucbk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2seutmphd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxmnctp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgewyfjg.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hurjjmcb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2wauhjcbj.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yycpghxx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlprdah.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2szrofdln.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2erdocwes.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxybzsl.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ycktnhwy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hbndijih.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ctutcirs.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdgkgqf.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvvmldi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdghudw.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pevfvioz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmlqrjb.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhildsr.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2bydmncko.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkkgjif.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqzomyx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdzkzea.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsfgcep.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rkasfvlt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uibpslke.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pdateeob.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nufeaeda.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ncizcbpw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iziljeaw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ipccarfi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2njyjylkh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pneprosu.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2uljexxlo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rljvcpyj.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsqppwy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgolxycc.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2leklnszd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmucdtm.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2senzpgop.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkwwpdf.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjzvxdj.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpxopgz.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcejqzw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2frveievu.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlyhyta.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfnqnei.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsgrjsc.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuteuiv.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgtxvqc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2kxugfvov.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvacjfw.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2viospncs.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhukoig.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyjguhz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2osqhijhs.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ionumqey.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxbqtxx.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2tesvzpgb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqpnoyh.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqvfxmc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwgqlqn.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmllvcc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2thcpduik.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2drbgsxxl.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2tiothftw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsjanjb.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2isnizhfc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2nqojyccv.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyfmhyz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmneiex.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2sycizmou.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2bowtjmbq.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2pkoxxfzf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vusiindu.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfnjutq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyupgod.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvhaivu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrvwttg.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjpizyv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsfbdnp.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2gevqqbxn.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvzajav.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2imnmakiq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mffmfsii.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwzujae.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjfrnym.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2haqttdvy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjszvlxt.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvsxxzf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2miiriowy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfelvzx.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mftiqynd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tpyhspcd.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2akxbgtmr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjyvyyv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyhiczt.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fwviifqk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrnfecr.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jcarjtog.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgmnwor.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2bkppejar.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgqvzjs.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhcrsvf.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwpeuya.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkaucpo.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2senyuggz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2tlsxgdgf.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vovrsusv.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjyhluc.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ziahjcdz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nllnxkkz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ybusovmr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqqauzm.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmulzvd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ezddluss.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfqvhkc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyksgxx.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gzobnvel.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2muniyeva.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2aodhyqnm.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuicirl.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkipgrzf.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxspcoy.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlwahzz.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2vekomvsm.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lenpeouz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2efhwvzyp.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfbkutt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgezeik.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtpfdgu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjrvaff.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mknhseqm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcinpxx.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bmacsxqu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yfohqxqp.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2uzclenap.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgtbipy.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmmxmao.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnjkyun.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkeeyhm.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2igxnnrab.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcikxlwk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnicmqp.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyxdikz.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bospwkay.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvmppva.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sakggrxp.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rlktxlaa.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2arenqmnn.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrvkvpu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vgopknij.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2isdjmrsj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2niqbnqyc.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2paqirxwh.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2qucjrrvc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2enpdgoyn.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2oekegkvv.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2betvmngj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2rogeyjho.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhgifdx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kloixdsd.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcktbru.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2airwufpy.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2twkijjxk.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sedpyoqk.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrjemsl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jspxcyca.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2okqlkgwn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfduuqr.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2isjbndek.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqzsqco.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrqiylt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2danvzmpf.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbqemhe.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmkdusa.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnzrgdr.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vypbfvdf.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2kirwdjdw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcaiypf.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsqtbgu.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgbdawy.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bazncjzl.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2aimbspjz.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pctleffh.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2edfectje.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ycynjynk.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iscivcle.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnakcxg.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqulsje.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcjnttx.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnggbye.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lhymkxic.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgdjxma.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgpsrbl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgrimzk.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hotechuu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2msbxmgfu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2khbwsrka.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjetymo.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2swfznwlz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xubesmqr.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuottwy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xitnpjqm.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2afxgpdfi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2hljmktmk.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnubhpf.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lktkaixz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zpeybxsa.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdzkked.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2puqucrnk.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzuozqi.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2crbknvsh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2xymjwrim.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wlswmuok.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhyakmj.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2pehmaqwq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjnauqt.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uguemgjy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpodmmj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwftkyg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wwopwktb.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xjanbnue.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbewehi.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdlzlsm.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zricrkna.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xjznzbhj.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2izszdykh.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjvjxwl.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfksvxv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dpegnijc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqzrslt.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhwunun.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2eilsdsnx.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqbcjcd.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjjsfuo.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2pripnzrd.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbnnfrc.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2obrvcnfn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzfgrmo.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgtuzst.html


<!-- 参考信息 -->