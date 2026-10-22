代发 wailian999

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nwbrower.top/Article/details/gtuifgmhbb.html

[Q09] 创建唯一索引
来源：http://dali.zhoulong.xyz/Article/details/gtwlkhhkuc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shuidangran.top/Article/details/gtikgmqlbw.html

[Q10] 插入单行
来源：http://dali.9152youxi.cn/Article/details/gtplhyijob.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj20258888.top/Article/details/gtithhfbgm.html

[Q11] 一次插入多行
来源：http://dali.jiagoushi.top/Article/details/gtlfnfjuzt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yvedp.cn/Article/details/gtfszbvnpr.html

[Q12] 插入后取自增 ID
来源：http://dali.mhx1999.top/Article/details/gtchjjrnlf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzofdoyxu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hnqzz.top/Article/details/gtrmycnijr.html

[Q13] 忽略重复插入
来源：http://dali.0kj1m.cn/Article/details/gthvrhagap.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtythtcahp.html

[Q14] 存在则更新（upsert）
来源：http://dali.guannengcc.top/Article/details/gtawgforqx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ppjwa.cn/Article/details/gtynlwioer.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sxryk.cn/Article/details/gttzhlqvyk.html

[Q15] 查询全部
来源：http://dali.jinqigfzy.top/Article/details/gtpyhynatj.html

SELECT * FROM users;
来源：http://dali.yj202588.top/Article/details/gtorpwteex.html

[Q16] 查询指定列
来源：http://dali.andypj.xyz/Article/details/gthlvomdjw.html

SELECT id, name FROM users;
来源：http://dali.jianghu66.top/Article/details/gtftaeyran.html

[Q17] 条件查询
来源：http://dali.kuanghao11.cn/Article/details/gtovulfwgn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrttpapyz.html

[Q18] 模糊匹配
来源：http://dali.tian-w.cn/Article/details/gtrfeqznpe.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.aizwys.cn/Article/details/gtlhrcgjba.html

[Q19] 范围查询
来源：http://dali.9152youxi.cn/Article/details/gtgfejikqn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yangfankeji.com/Article/details/gtigivyknf.html

[Q20] IN 列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvpomrqug.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sysykeji.top/Article/details/gthluvuyfo.html

[Q21] 空值判断
来源：http://dali.xuetiantiany.cn/Article/details/gtdueohcvc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hongshengwenyu.top/Article/details/gtpgjhjzay.html

[Q22] 排序
来源：http://dali.tianlin.xyz/Article/details/gtvqxmcrdt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.316326.xyz/Article/details/gtwjcqpajf.html

[Q23] 分页
来源：http://dali.zdqjudy.top/Article/details/gtpmfsogjm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.havefunace.top/Article/details/gtishiniph.html

[Q24] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gtepjvtspp.html

SELECT DISTINCT city FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtmggqkbsm.html

[Q25] 只取前 N 条
来源：http://dali.aibaodan.cn/Article/details/gtewjnmsow.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cheryme.top/Article/details/gtkyylauot.html

[Q26] 计数
来源：http://dali.jqgufenzy.top/Article/details/gtbnahzgph.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtitnpvzos.html

[Q27] 条件计数
来源：http://dali.yonumen.top/Article/details/gtbxhstnuz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtrzyjrywt.html

[Q28] 求和与平均
来源：http://dali.mhx1999.top/Article/details/gtffeeplcu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gthkxpuheg.html

[Q29] 最大最小值
来源：http://dali.yuxming.cn/Article/details/gtljaztluu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtsxribfib.html

[Q30] 分组统计
来源：http://dali.gogol.net.cn/Article/details/gtnjjpmomg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gthrginlvf.html

[Q31] 分组后过滤
来源：http://dali.aizwys.cn/Article/details/gtbiijgtes.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ivvv.top/Article/details/gtnjegnsvq.html

[Q32] 分组拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtqqtfhwcm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gtfafhflpm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yangfankeji.com/Article/details/gtolerjole.html

[Q33] 多列分组
来源：http://dali.aizwys.cn/Article/details/gtqdppxqfd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cdnleiting.top/Article/details/gtkruesrvz.html

[Q34] 每组取第一条
来源：http://dali.yueranfly.top/Article/details/gtcawukpyz.html

SELECT * FROM (
来源：http://dali.birdmap.top/Article/details/gtinjitjyb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tanke756.top/Article/details/gtovjknyle.html

) t WHERE rn = 1;
来源：http://dali.shuidangran.top/Article/details/gtfwfoutir.html

[Q35] 内连接
来源：http://dali.xinyue.icu/Article/details/gtgbqdovgv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gtdfrtwcsn.html

[Q36] 左连接
来源：http://dali.pengpengdd.cyou/Article/details/gttpasbkgq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daxiang520.top/Article/details/gtetdgabno.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gtoahgnnxe.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufanbukq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hammf.cn/Article/details/gtnczlzgpx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daria6918.cn/Article/details/gtaephefoa.html

[Q39] 自连接（查上下级）
来源：http://dali.dianchejie.cn/Article/details/gtjxcnhzwe.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehirdfhf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cheryme.top/Article/details/gtoiatcgnv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shzxlz.cn/Article/details/gtwofyysxl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjqfbchz.html

[Q41] 多表连接
来源：http://dali.feifeiyinyue.top/Article/details/gtksvwozxb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjnulccnp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenzaomai.com/Article/details/gtmakqxcsy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ehwqpu.com/Article/details/gtbzvdyzlu.html

[Q42] 连接条件附加过滤
来源：http://dali.jqgufenzy.top/Article/details/gtbeufijhv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cdnleiting.top/Article/details/gtqqixipuz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwoiscocu.html

[Q43] 标量子查询
来源：http://dali.hongshengwenyu.top/Article/details/gtkzxuybyl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xuanzx.com/Article/details/gtytdnofjk.html

[Q44] IN 子查询
来源：http://dali.tanke756.top/Article/details/gtqiozshtd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.bjfxy.top/Article/details/gtnbhnuajp.html

[Q45] EXISTS 判断存在
来源：http://dali.jqgfzy.top/Article/details/gtexhshpvf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gtmyiaguqn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hammf.cn/Article/details/gtbsjtwwuq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gogol.net.cn/Article/details/gtxqkxrikl.html

[Q47] 与平均值比较
来源：http://dali.nwbrower.top/Article/details/gtdufbrsry.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yangfankeji.com/Article/details/gtlmihidua.html

[Q48] CTE 公用表表达式
来源：http://dali.yongpay.top/Article/details/gteimquhxc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrgmxifr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jiagoushi.top/Article/details/gtffgllxsa.html

[Q49] 更新单行
来源：http://dali.sxryk.cn/Article/details/gtnuxfpjvt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cqqwz.cn/Article/details/gtbpqkeclv.html

[Q50] 批量更新
来源：http://dali.mhx1999.top/Article/details/gthuyzrcva.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.havefunace.top/Article/details/gtfbkbyzkv.html

[Q51] 用子查询更新
来源：http://dali.chenjidiqi.icu/Article/details/gtadnmzsef.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tianlin.xyz/Article/details/gtzllnzjig.html

[Q52] 删除指定行
来源：http://dali.cashguo.top/Article/details/gtwjbamewu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gtjlqnjjgs.html

[Q53] 按条件删除
来源：http://dali.hysaishi.cn/Article/details/gtrclecgaz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yvedp.cn/Article/details/gtirgenhwh.html

[Q54] 清空表
来源：http://dali.tian-w.cn/Article/details/gtvqcxjvdr.html

TRUNCATE TABLE logs;
来源：http://dali.yuxming.cn/Article/details/gtieravfum.html

[Q55] 排名（并列占位）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixfkhyrc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnpsxmpdx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dianchejie.cn/Article/details/gttwvfljhq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinqigufen.top/Article/details/gteverppcx.html

[Q57] 行号
来源：http://dali.feifeiyinyue.top/Article/details/gtyaqwwshc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jianghu66.top/Article/details/gtixrzirgk.html

[Q58] 累计求和
来源：http://dali.jlsjyb.cn/Article/details/gtfwotdkui.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtvlntnllk.html

[Q59] 分组内累计
来源：http://dali.shanyushiyangtech.top/Article/details/gtxltuknsc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtyciypbcj.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenjidiqi.icu/Article/details/gtesjuqybv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ppjwa.cn/Article/details/gtohupedrd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawmcisuk.html

[Q61] 移动平均
来源：http://dali.nanxinkj.top/Article/details/gtyyzvoeqk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtixojitng.html

[Q62] 分组占比
来源：http://dali.hysaishi.cn/Article/details/gtdaspcbvu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtdhrtjmgq.html

[Q63] 开启事务
来源：http://dali.nanxuanxn.top/Article/details/gtohgmqfff.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.aizwys.cn/Article/details/gtptdrzalg.html

[Q64] 提交事务
来源：http://dali.yongpay.top/Article/details/gtzwwddnro.html

COMMIT;
来源：http://dali.ybcxt.top/Article/details/gtgktyvnjc.html

[Q65] 回滚事务
来源：http://dali.xylfe.cn/Article/details/gtmkdcdgik.html

ROLLBACK;
来源：http://dali.smart0.xyz/Article/details/gtzpilevuj.html

[Q66] 行锁查询
来源：http://dali.316326.xyz/Article/details/gtwfustvlk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.mhx1999.top/Article/details/gthysywbcp.html

[Q67] 设置隔离级别
来源：http://dali.ybcxt.top/Article/details/gtdgewjxex.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdkxzbnq.html

[Q68] 保存点
来源：http://dali.haohaochexian.top/Article/details/gtskovygel.html

SAVEPOINT sp1;
来源：http://dali.aibaodan.cn/Article/details/gtvllzibna.html

ROLLBACK TO sp1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtceqmsozj.html

[Q69] 查看执行计划
来源：http://dali.9152youxi.cn/Article/details/gtporbbnpi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xylfe.cn/Article/details/gthqjfuwul.html

[Q70] 更新统计信息
来源：http://dali.gogol.net.cn/Article/details/gtmtdtanbq.html

ANALYZE TABLE users;
来源：http://dali.guowangkeji.top/Article/details/gtvbsryopc.html

[Q71] 查看建表语句
来源：http://dali.tianlin.xyz/Article/details/gtxuivxzpg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xziqi.cn/Article/details/gtickixnxu.html

[Q72] 查看索引
来源：http://dali.gaohongyu789.top/Article/details/gtrgdqbcvh.html

SHOW INDEX FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtwgbstgur.html

[Q73] 查看表状态
来源：http://dali.svipenyu.cn/Article/details/gthkfqsrsd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yvedp.cn/Article/details/gtkbetodxc.html

[Q74] 强制使用索引
来源：http://dali.cashguo.top/Article/details/gthoqedmwt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.316326.xyz/Article/details/gtgymsgvdf.html

[Q75] 日期格式化
来源：http://dali.fzhhl.top/Article/details/gtaabynowy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtwgadjnwl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinyuanbaomall.cn/Article/details/gteiduedpw.html

[Q76] 按天统计
来源：http://dali.xuanzx.com/Article/details/gtbqnclmqe.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinqigufen.top/Article/details/gtnxturqgw.html

[Q77] 时间加减
来源：http://dali.shuidangran.top/Article/details/gtsouovnts.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jlsjyb.cn/Article/details/gtusnfrhma.html

[Q78] 当前时间
来源：http://dali.jqgufenzy.top/Article/details/gtmhywtpct.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdxzqcmq.html

[Q79] 字符串拼接
来源：http://dali.sufxvd.cn/Article/details/gtjkjxyrxu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yongpay.top/Article/details/gthvqilmtv.html

[Q80] 字符串截取
来源：http://dali.hongshengwenyu.top/Article/details/gtgfkilyzy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtqmckgpbx.html

[Q81] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gtzfoyohsl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtpbrikchs.html

[Q82] 字符长度与字节长度
来源：http://dali.guowangkeji.top/Article/details/gtplsvcxtr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtlsuwjtey.html

[Q83] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gtwsqffkwx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtlsldanjh.html

[Q84] 去除首尾空格
来源：http://dali.cucudq.cn/Article/details/gtpijwuecr.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtdixuuoef.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gtdknisavl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.birdmap.top/Article/details/gtetamcaze.html

[Q86] 读取 JSON 字段
来源：http://dali.pengpengdd.cyou/Article/details/gtbouykimg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinghuilouyu.cn/Article/details/gtcpzadgjl.html

[Q87] JSON 字段做条件
来源：http://dali.xuetiantiany.cn/Article/details/gtsetttkik.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yuanzhike.top/Article/details/gtjwomtotm.html

[Q88] 行转列（条件聚合）
来源：http://dali.fengsongda.top/Article/details/gtlcnuywma.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuanzx.com/Article/details/gtitzodwpb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cashguo.top/Article/details/gtapoyzikz.html

[Q89] 判断表是否存在
来源：http://dali.yangfankeji.com/Article/details/gtpdyqgwwp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhongyouzk.top/Article/details/gtrhphwris.html

[Q90] 生成序号列
来源：http://dali.daxiang520.top/Article/details/gtignqobxo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.fengsongda.top/Article/details/gtgkjodjlx.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtmqliwjdg.html

R. Bash 专题
来源：http://dali.ybcxt.top/Article/details/gtrkssrukm.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gthelqmkei.html

[R01] shebang 与严格模式
来源：http://dali.yongpay.top/Article/details/gtflwxitec.html

#!/usr/bin/env bash
来源：http://dali.chenlongwang.top/Article/details/gteizkvlmr.html

set -euo pipefail
来源：http://dali.yongpay.top/Article/details/gturcibjrx.html

[R02] 变量赋值与使用
来源：http://dali.jianghu66.top/Article/details/gtgsaibqcg.html

name="Tom"; echo "$name"
来源：http://dali.zhengqikj.top/Article/details/gthztzievp.html

[R03] 只读变量
来源：http://dali.iojbl.cn/Article/details/gtthxfgrez.html

readonly PI=3.14
来源：http://dali.jyoumei.cn/Article/details/gtffuvmdrh.html

[R04] 位置参数
来源：http://dali.quarkkingdee.top/Article/details/gtqljcsfzl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ybcxt.top/Article/details/gtwfnyytzg.html

[R05] 参数默认值
来源：http://dali.xylfe.cn/Article/details/gtcpivyrdi.html

name="${1:-default}"
来源：http://dali.tanke756.top/Article/details/gtvhynswuq.html

[R06] 判断命令是否存在
来源：http://dali.zhixingplan.top/Article/details/gtzjpplrfa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gtdhsilnax.html

[R07] if 判断文件
来源：http://dali.xinyue.icu/Article/details/gtwulxoezr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hfpthk.cn/Article/details/gtofgeykin.html

[R08] 数值比较
来源：http://dali.hysaishi.cn/Article/details/gtcrddptbj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cashguo.top/Article/details/gtmrwdfbnk.html

[R09] 字符串比较
来源：http://dali.tanke756.top/Article/details/gtgvpkuxrn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.aizwys.cn/Article/details/gtithtnbyt.html

[R10] 正则匹配
来源：http://dali.jianghu66.top/Article/details/gtzgbszhjg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtgaycmeoa.html

[R11] case 多分支
来源：http://dali.tianlin.xyz/Article/details/gtuuohwndy.html

case "$1" in
来源：http://dali.quarkkingdee.top/Article/details/gtmskybzku.html

start) echo "启动" ;;
来源：http://dali.iojbl.cn/Article/details/gtsioglfcn.html

stop)  echo "停止" ;;
来源：http://dali.yuxming.cn/Article/details/gtdnuyxgyt.html

*)     echo "未知命令" ;;
来源：http://dali.redwolf501.top/Article/details/gtnxbgsger.html

esac
来源：http://dali.xuetiantiany.cn/Article/details/gtslgfpvpu.html

[R12] for 遍历文件
来源：http://dali.quarkkingdee.top/Article/details/gtwrabazlt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ppjwa.cn/Article/details/gtbkuywuhf.html

[R13] for 计数循环
来源：http://dali.yuxming.cn/Article/details/gtitfrvibm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gotoacloud.top/Article/details/gtfkkmyaup.html

[R14] C 风格 for
来源：http://dali.xuanzx.com/Article/details/gtegxlqdrz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jyoumei.cn/Article/details/gtiztwrhyz.html

[R15] while 逐行读文件
来源：http://dali.yuxming.cn/Article/details/gtajirfblw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtgdtngumo.html

[R16] until 等待条件
来源：http://dali.dianchejie.cn/Article/details/gtdqvsucnt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gtiqqddjwd.html

[R17] 数组定义与取值
来源：http://dali.shzxlz.cn/Article/details/gtetxeqimp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.iojbl.cn/Article/details/gtrulmtdfl.html

[R18] 遍历数组
来源：http://dali.aizwys.cn/Article/details/gtawweingy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cucudq.cn/Article/details/gtkmzhefay.html

[R19] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gtzrsmgbxv.html

echo "${#arr[@]}"
来源：http://dali.yanxiufei.cn/Article/details/gtictgpdwf.html

[R20] 关联数组（字典）
来源：http://dali.redwolf501.top/Article/details/gtlyujonah.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tanke756.top/Article/details/gtwyxchbfi.html

[R21] 字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gtfmgyejua.html

echo "${#s}"
来源：http://dali.chenjidiqi.icu/Article/details/gtfmuoqgay.html

[R22] 截取子串
来源：http://dali.yj20258888.top/Article/details/gtwwuuagtq.html

echo "${s:0:5}"
来源：http://dali.sxryk.cn/Article/details/gtsjfgylih.html

[R23] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gtoqapfqtj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrpacdqw.html

[R24] 大小写转换
来源：http://dali.yj202588.top/Article/details/gtssyadbmn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.pengpengdd.cyou/Article/details/gtxucqpdyh.html

[R25] 去后缀 / 去前缀
来源：http://dali.daria6918.cn/Article/details/gtqjcznlxw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hongshengwenyu.top/Article/details/gtrvfjtmvv.html

[R26] 命令替换
来源：http://dali.ehwqpu.com/Article/details/gttyxqglws.html

now=$(date +%F); echo "$now"
来源：http://dali.guannengcc.top/Article/details/gtoeckomuh.html

[R27] 算术展开
来源：http://dali.cheryme.top/Article/details/gtffaqyqwj.html

echo $((1 + 2 * 3))
来源：http://dali.fengsongda.top/Article/details/gtypdxqvax.html

[R28] 浮点运算
来源：http://dali.guowangkeji.top/Article/details/gtlextrbcd.html

echo "scale=2; 10/3" | bc
来源：http://dali.shuidangran.top/Article/details/gtfsqeumfc.html

[R29] 定义函数
来源：http://dali.cashguo.top/Article/details/gtddjkteiz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aizwys.cn/Article/details/gtpvftjzwt.html

[R30] 函数返回状态码
来源：http://dali.chenlongwang.top/Article/details/gtddwecmxv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sufxvd.cn/Article/details/gtkxcrdkzq.html

[R31] 局部变量
来源：http://dali.pycfn.com/Article/details/gtqkvcokcs.html

f() { local x=1; echo "$x"; }
来源：http://dali.jiagoushi.top/Article/details/gtksgrwtbp.html

[R32] 参数个数校验
来源：http://dali.guannengcc.top/Article/details/gtrwrvkdoq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gogol.net.cn/Article/details/gtpbueybgi.html

[R33] 捕获错误并提示行号
来源：http://dali.fengsongda.top/Article/details/gtdacvvbou.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sufxvd.cn/Article/details/gtlfkyagwg.html

[R34] 退出时清理
来源：http://dali.chenjidiqi.icu/Article/details/gtyxfgdxak.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgfzy.top/Article/details/gtsnwhzgjb.html

[R35] 后台执行并等待
来源：http://dali.redwolf501.top/Article/details/gtjkrxacke.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ehwqpu.com/Article/details/gtmiwwxupx.html

[R36] 并发执行多个任务
来源：http://dali.quarkkingdee.top/Article/details/gthbbvepaq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gogol.net.cn/Article/details/gtubgdpobq.html

[R37] 把输出赋给变量
来源：http://dali.wangshuangyany.cn/Article/details/gtzgfkkivk.html

files=$(ls -1)
来源：http://dali.andypj.xyz/Article/details/gtjnfbjrak.html

[R38] 管道串联
来源：http://dali.meibo888.top/Article/details/gtgczeaepx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cqqwz.cn/Article/details/gttmqaubed.html

[R39] 重定向标准输出与错误
来源：http://dali.jqgufenzy.top/Article/details/gthcgeemlp.html

cmd > out.log 2>&1
来源：http://dali.guowangkeji.top/Article/details/gtvaecgjzf.html

[R40] 追加写日志
来源：http://dali.yanxiufei.cn/Article/details/gtpoqcrgxd.html

echo "log" >> out.log
来源：http://dali.chenjidiqi.icu/Article/details/gtlxysbsak.html

[R41] 丢弃输出
来源：http://dali.hongshengwenyu.top/Article/details/gtsjhlxcfy.html

cmd >/dev/null 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gtzkxrjtrf.html

[R42] 输入重定向
来源：http://dali.aizwys.cn/Article/details/gtahidxril.html

wc -l < a.txt
来源：http://dali.daxiang520.top/Article/details/gtvkbhrwpq.html

[R43] 按名字查找文件
来源：http://dali.daria6918.cn/Article/details/gtpjwffpoy.html

find . -name "*.log" -type f
来源：http://dali.guowangkeji.top/Article/details/gtvgahqegi.html

[R44] 按修改时间查找
来源：http://dali.cucudq.cn/Article/details/gtpzhsmxkb.html

find . -mtime -7 -type f
来源：http://dali.c1oappe.top/Article/details/gtyschkibc.html

[R45] 批量删除
来源：http://dali.aibaodan.cn/Article/details/gtgqxmvpip.html

find . -name "*.tmp" -delete
来源：http://dali.jqgufenzy.top/Article/details/gtsyiayjcz.html

[R46] 递归替换文件内容
来源：http://dali.jianghu66.top/Article/details/gtxckxlzbr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ybcxt.top/Article/details/gtwvcottfo.html

[R47] sed 单行替换
来源：http://dali.cqqwz.cn/Article/details/gtwjilrqap.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.fengsongda.top/Article/details/gtijphagcc.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gtcaystngq.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj20258.top/Article/details/gtzxppmxwj.html

[R49] awk 带条件
来源：http://dali.hfpthk.cn/Article/details/gtebjjwqiu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinqigufen.top/Article/details/gtxpfxdupl.html

[R50] awk 求和
来源：http://dali.hongshengwenyu.top/Article/details/gtxhddpwba.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ehwqpu.com/Article/details/gtevkgmmzo.html

[R51] 排序去重取前几
来源：http://dali.zdqjudy.top/Article/details/gthlwuzria.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258888.top/Article/details/gtcaqlzvao.html

[R52] 统计行数
来源：http://dali.shzxlz.cn/Article/details/gtvsriurgv.html

wc -l a.txt
来源：http://dali.jiagoushi.top/Article/details/gtyjxspooh.html

[R53] 查看文件头与实时尾
来源：http://dali.zycfv.cn/Article/details/gtgtusjdyr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.bjfxy.top/Article/details/gtayxdrxek.html

[R54] 比较两个文件
来源：http://dali.hammf.cn/Article/details/gtthyqzxul.html

diff a.txt b.txt
来源：http://dali.zycfv.cn/Article/details/gtqovqyfje.html

[R55] 压缩与解压
来源：http://dali.nwbrower.top/Article/details/gtiddsukvv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tanke756.top/Article/details/gtxrptbjxo.html

[R56] 远程拷贝
来源：http://dali.hfpthk.cn/Article/details/gtzhcxqgbh.html

scp file user@host:/path/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdcxxkwt.html

[R57] 远程执行命令
来源：http://dali.zhixingplan.top/Article/details/gtmwycblow.html


<!-- 参考信息 -->