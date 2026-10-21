代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgfzy.top/Article/details/gtubqwsmpe.html

[Q05] 重命名列
来源：http://dali.xylfe.cn/Article/details/gtczzupqpr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sweek.top/Article/details/gtrsdgvqcm.html

[Q06] 删除列
来源：http://dali.zycfv.cn/Article/details/gtocsmzmwf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zdqjudy.top/Article/details/gttvlxuzqs.html

[Q07] 删除表
来源：http://dali.chenjidiqi.icu/Article/details/gtqxqyulwy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.redwolf501.top/Article/details/gtsjqebcem.html

[Q08] 创建普通索引
来源：http://dali.shzxlz.cn/Article/details/gtjvhqpmru.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.feifeiyinyue.top/Article/details/gtytvjtqay.html

[Q09] 创建唯一索引
来源：http://dali.hfpthk.cn/Article/details/gtzlrpxsjg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cqqwz.cn/Article/details/gtprqndnnj.html

[Q10] 插入单行
来源：http://dali.gaohongyu789.top/Article/details/gtmhfcidkw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhengqikj.top/Article/details/gtqvxkgzio.html

[Q11] 一次插入多行
来源：http://dali.haohaochexian.top/Article/details/gtqgnvsyfw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnlcnlbsa.html

[Q12] 插入后取自增 ID
来源：http://dali.daria6918.cn/Article/details/gtmevuftir.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shzxlz.cn/Article/details/gtxpjjuoqk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj20258.top/Article/details/gtifinjcma.html

[Q13] 忽略重复插入
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcvsfyqe.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gtmfnieiut.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuanzhike.top/Article/details/gtnbzkdjys.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenzaomai.com/Article/details/gtcnmuzglv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hywenlv.cn/Article/details/gtyyotwxzd.html

[Q15] 查询全部
来源：http://dali.xziqi.cn/Article/details/gtuafjordl.html

SELECT * FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtfxehbbmn.html

[Q16] 查询指定列
来源：http://dali.sxryk.cn/Article/details/gtkosjkjgu.html

SELECT id, name FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrujybtir.html

[Q17] 条件查询
来源：http://dali.yonumen.top/Article/details/gtkgjpabgt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenzaomai.com/Article/details/gtxgtibcbh.html

[Q18] 模糊匹配
来源：http://dali.pycfn.com/Article/details/gtsyltujbw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinqigfzy.top/Article/details/gtknxibgsv.html

[Q19] 范围查询
来源：http://dali.mhx1999.top/Article/details/gtsjsyzxru.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvufqunhw.html

[Q20] IN 列表
来源：http://dali.hnxiangtu.top/Article/details/gtwxzkvrdi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.snrcjt.cn/Article/details/gtbmcenvxv.html

[Q21] 空值判断
来源：http://dali.fzhhl.top/Article/details/gteptvukme.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hywenlv.cn/Article/details/gtzvphokeu.html

[Q22] 排序
来源：http://dali.sufxvd.cn/Article/details/gtrliknhou.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cashguo.top/Article/details/gtgxpmbshn.html

[Q23] 分页
来源：http://dali.bjfxy.top/Article/details/gtpjuvrsve.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nanxinkj.top/Article/details/gtestfyqit.html

[Q24] 去重
来源：http://dali.aibaodan.cn/Article/details/gtmfefehdq.html

SELECT DISTINCT city FROM users;
来源：http://dali.cqqwz.cn/Article/details/gttvwbzcfn.html

[Q25] 只取前 N 条
来源：http://dali.nanxinkj.top/Article/details/gtgfollhyx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.bjfxy.top/Article/details/gtqoaemcel.html

[Q26] 计数
来源：http://dali.xuetiantiany.cn/Article/details/gttytszwgh.html

SELECT COUNT(*) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtoowybdny.html

[Q27] 条件计数
来源：http://dali.smart0.xyz/Article/details/gttcgifmnn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yongpay.top/Article/details/gtapexrwlb.html

[Q28] 求和与平均
来源：http://dali.jinqigfzy.top/Article/details/gttqpkbfyk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtwnyciwwm.html

[Q29] 最大最小值
来源：http://dali.jianghu66.top/Article/details/gtluueuxfe.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtctlkxqux.html

[Q30] 分组统计
来源：http://dali.fengsongda.top/Article/details/gtmrgcuwlw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gtldlnkfgq.html

[Q31] 分组后过滤
来源：http://dali.c1oappe.top/Article/details/gtljfoyxck.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shzxlz.cn/Article/details/gtqqmriavm.html

[Q32] 分组拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtixreljty.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gtskiemaxs.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.bjfxy.top/Article/details/gtgsiprymw.html

[Q33] 多列分组
来源：http://dali.mhx1999.top/Article/details/gtlypceuoi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgfzy.top/Article/details/gtvftepxai.html

[Q34] 每组取第一条
来源：http://dali.xylfe.cn/Article/details/gtuylwkles.html

SELECT * FROM (
来源：http://dali.jiagoushi.top/Article/details/gtvolughjb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ybcxt.top/Article/details/gtnwnoxcop.html

) t WHERE rn = 1;
来源：http://dali.fzhhl.top/Article/details/gtbtawfkir.html

[Q35] 内连接
来源：http://dali.9152youxi.cn/Article/details/gtrrfbbhth.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtmsnikw.html

[Q36] 左连接
来源：http://dali.bjfxy.top/Article/details/gtspsdaqno.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ehwqpu.com/Article/details/gthseozcig.html

[Q37] 右连接
来源：http://dali.tian-w.cn/Article/details/gtcbkgkrba.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cdnleiting.top/Article/details/gthzesikzn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.bjfxy.top/Article/details/gtemgxnowx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cashguo.top/Article/details/gtkfawumjf.html

[Q39] 自连接（查上下级）
来源：http://dali.smart0.xyz/Article/details/gtejdjtfaj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jiagoushi.top/Article/details/gteiahgqcy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttppxjoxe.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jyoumei.cn/Article/details/gtyfbwyuwn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthdceodsd.html

[Q41] 多表连接
来源：http://dali.yongpay.top/Article/details/gtgoyfyyrr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangdashe.top/Article/details/gthntsuclh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhengqikj.top/Article/details/gtaudyajiq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.smart0.xyz/Article/details/gtnajshdok.html

[Q42] 连接条件附加过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfmtnqsv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.pycfn.com/Article/details/gtudoayosv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsathkffr.html

[Q43] 标量子查询
来源：http://dali.fengsongda.top/Article/details/gtdtvounui.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigfzy.top/Article/details/gtaleqmzet.html

[Q44] IN 子查询
来源：http://dali.sxryk.cn/Article/details/gtxekzmpez.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gogol.net.cn/Article/details/gtiyivtiev.html

[Q45] EXISTS 判断存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtscrdublv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jlsjyb.cn/Article/details/gtpfmsadfz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xziqi.cn/Article/details/gtgwxhpirc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtveqmtnjp.html

[Q47] 与平均值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyuzylvoj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cheryme.top/Article/details/gtdauxnaxq.html

[Q48] CTE 公用表表达式
来源：http://dali.snrcjt.cn/Article/details/gtrtfptgnm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenlongwang.top/Article/details/gtnshcekpk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangdashe.top/Article/details/gtryddetgh.html

[Q49] 更新单行
来源：http://dali.tian-w.cn/Article/details/gtlmjyfyho.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sysykeji.top/Article/details/gtpyqwbsww.html

[Q50] 批量更新
来源：http://dali.nwbrower.top/Article/details/gtbsognkdx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258.top/Article/details/gtbolmmykn.html

[Q51] 用子查询更新
来源：http://dali.cdnleiting.top/Article/details/gttvchajzz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sweek.top/Article/details/gtrzqsdxqg.html

[Q52] 删除指定行
来源：http://dali.jlsjyb.cn/Article/details/gtsaeouitp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gtkevjdolg.html

[Q53] 按条件删除
来源：http://dali.daria6918.cn/Article/details/gtiumhvyei.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenlongwang.top/Article/details/gtpstqlhjt.html

[Q54] 清空表
来源：http://dali.xuanzx.com/Article/details/gttxnqqhri.html

TRUNCATE TABLE logs;
来源：http://dali.cheryme.top/Article/details/gtzylktngg.html

[Q55] 排名（并列占位）
来源：http://dali.dianchejie.cn/Article/details/gtxfrkxppd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sufxvd.cn/Article/details/gtzkzzqzxu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shuidangran.top/Article/details/gtzszecroj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yangfankeji.com/Article/details/gtsdebzavr.html

[Q57] 行号
来源：http://dali.birdmap.top/Article/details/gtdecwgvap.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.birdmap.top/Article/details/gtmyuktbyh.html

[Q58] 累计求和
来源：http://dali.jyoumei.cn/Article/details/gtevzycknd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gthdkfdgha.html

[Q59] 分组内累计
来源：http://dali.cashguo.top/Article/details/gtvpjqayhk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtjsetkptr.html

[Q60] 取上一行 / 下一行
来源：http://dali.ivvv.top/Article/details/gtaxiqukqe.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.316326.xyz/Article/details/gtaiqxunaq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ivvv.top/Article/details/gtuhypeekg.html

[Q61] 移动平均
来源：http://dali.aibaodan.cn/Article/details/gtcmsspndc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtjywuhszp.html

[Q62] 分组占比
来源：http://dali.ybcxt.top/Article/details/gtosaovoht.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gtzkwrffcv.html

[Q63] 开启事务
来源：http://dali.hysaishi.cn/Article/details/gtpjiveigl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cheryme.top/Article/details/gtpzezuvec.html

[Q64] 提交事务
来源：http://dali.9152youxi.cn/Article/details/gtnxefekms.html

COMMIT;
来源：http://dali.tanke756.top/Article/details/gtojrgtbuo.html

[Q65] 回滚事务
来源：http://dali.chenzaomai.com/Article/details/gttknvhrvi.html

ROLLBACK;
来源：http://dali.jyoumei.cn/Article/details/gtosileomz.html

[Q66] 行锁查询
来源：http://dali.yangfankeji.com/Article/details/gtjnbdxfon.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.iojbl.cn/Article/details/gtkgkamyfl.html

[Q67] 设置隔离级别
来源：http://dali.birdmap.top/Article/details/gtbvfmpqwu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj202588.top/Article/details/gtoeigptoh.html

[Q68] 保存点
来源：http://dali.cqqwz.cn/Article/details/gtisagkrlf.html

SAVEPOINT sp1;
来源：http://dali.svipenyu.cn/Article/details/gtrewepmlo.html

ROLLBACK TO sp1;
来源：http://dali.yangfankeji.com/Article/details/gtxnwqbovm.html

[Q69] 查看执行计划
来源：http://dali.nanxinkj.top/Article/details/gtzfeyzmrd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj20258888.top/Article/details/gtxdbeakpd.html

[Q70] 更新统计信息
来源：http://dali.0kj1m.cn/Article/details/gtrjaxjuie.html

ANALYZE TABLE users;
来源：http://dali.feifeiyinyue.top/Article/details/gtwraggbpw.html

[Q71] 查看建表语句
来源：http://dali.yj202588.top/Article/details/gtmbwmiwne.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shangyingyoupin.top/Article/details/gtjanqzvhp.html

[Q72] 查看索引
来源：http://dali.yj202588.top/Article/details/gtmslblwkj.html

SHOW INDEX FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtzzlcsamd.html

[Q73] 查看表状态
来源：http://dali.quarkkingdee.top/Article/details/gtxzjovalg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjmkpvlc.html

[Q74] 强制使用索引
来源：http://dali.birdmap.top/Article/details/gtulpkklhe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cashguo.top/Article/details/gtwfvdbqjh.html

[Q75] 日期格式化
来源：http://dali.yj202588.top/Article/details/gtjsflbirp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tanke756.top/Article/details/gtniencgdh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cucudq.cn/Article/details/gtgfnhozfg.html

[Q76] 按天统计
来源：http://dali.gogol.net.cn/Article/details/gtnwhhuqdc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yongpay.top/Article/details/gteyehbbcr.html

[Q77] 时间加减
来源：http://dali.hammf.cn/Article/details/gtpeylbemf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jyoumei.cn/Article/details/gtuhywywie.html

[Q78] 当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gtlskejzpn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuetiantiany.cn/Article/details/gtxwsithpr.html

[Q79] 字符串拼接
来源：http://dali.tianlin.xyz/Article/details/gtqfqsaawo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yonumen.top/Article/details/gtjcbvvtdl.html

[Q80] 字符串截取
来源：http://dali.feifeiyinyue.top/Article/details/gtwglnnadx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtytxuvlfh.html

[Q81] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gttmenxxpw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ydzc1.top/Article/details/gtcmigxkoe.html

[Q82] 字符长度与字节长度
来源：http://dali.zdqjudy.top/Article/details/gtdhuxzupb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gttynsnxam.html

[Q83] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gtduziiuiu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gthvtvdcsw.html

[Q84] 去除首尾空格
来源：http://dali.yonumen.top/Article/details/gtfhylcuta.html

SELECT TRIM(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyswnmtgx.html

[Q85] 数值取整
来源：http://dali.jiagoushi.top/Article/details/gtpdjwhcsq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hongshengwenyu.top/Article/details/gtsjhufeoo.html

[Q86] 读取 JSON 字段
来源：http://dali.yj202588.top/Article/details/gtevggjfam.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yongpay.top/Article/details/gthavuwzwf.html

[Q87] JSON 字段做条件
来源：http://dali.9152youxi.cn/Article/details/gtfaunipiw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yuxming.cn/Article/details/gtdvmfxrdc.html

[Q88] 行转列（条件聚合）
来源：http://dali.yueranfly.top/Article/details/gtvymtzprl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.haohaochexian.top/Article/details/gtuszrpnaz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xylfe.cn/Article/details/gtyvrnnbog.html

[Q89] 判断表是否存在
来源：http://dali.sufxvd.cn/Article/details/gtxyuuqnjh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gtmsdwjipp.html

[Q90] 生成序号列
来源：http://dali.zhongyouzk.top/Article/details/gtpnoweymm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shangyingyoupin.top/Article/details/gtjlpmebfj.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtwvsnmokl.html

R. Bash 专题
来源：http://dali.xuanzx.com/Article/details/gtjlddznxd.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtvpbjsbzt.html

[R01] shebang 与严格模式
来源：http://dali.tanke756.top/Article/details/gtxlyptfoo.html

#!/usr/bin/env bash
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmrmdhii.html

set -euo pipefail
来源：http://dali.xziqi.cn/Article/details/gtrfhvnonk.html

[R02] 变量赋值与使用
来源：http://dali.hfpthk.cn/Article/details/gtbvktjfvx.html

name="Tom"; echo "$name"
来源：http://dali.fengsongda.top/Article/details/gtlojvbniu.html

[R03] 只读变量
来源：http://dali.guannengcc.top/Article/details/gtyejhdjpc.html

readonly PI=3.14
来源：http://dali.jlsjyb.cn/Article/details/gtglnjuwxp.html

[R04] 位置参数
来源：http://dali.jinqigfzy.top/Article/details/gtvqrisbtw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ehwqpu.com/Article/details/gtekomqiyf.html

[R05] 参数默认值
来源：http://dali.shangyingyoupin.top/Article/details/gtgfcilkqh.html

name="${1:-default}"
来源：http://dali.zycfv.cn/Article/details/gtykurmefp.html

[R06] 判断命令是否存在
来源：http://dali.cdnleiting.top/Article/details/gtdyazxzmq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenlongwang.top/Article/details/gtfwvotwkf.html

[R07] if 判断文件
来源：http://dali.guowangkeji.top/Article/details/gtvgrgepcf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.bjfxy.top/Article/details/gthurczxqz.html

[R08] 数值比较
来源：http://dali.xinyue.icu/Article/details/gtbbjzmhnt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daxiang520.top/Article/details/gtnrgyqyql.html

[R09] 字符串比较
来源：http://dali.yuxming.cn/Article/details/gtradjmkio.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xinyue.icu/Article/details/gtnecupjme.html

[R10] 正则匹配
来源：http://dali.yj20258888.top/Article/details/gtqokvclny.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.9152youxi.cn/Article/details/gttmrgimki.html

[R11] case 多分支
来源：http://dali.andypj.xyz/Article/details/gteelcdoao.html

case "$1" in
来源：http://dali.cheryme.top/Article/details/gtlobwjrjc.html

start) echo "启动" ;;
来源：http://dali.guowangkeji.top/Article/details/gtznwowtxk.html

stop)  echo "停止" ;;
来源：http://dali.cqqwz.cn/Article/details/gtjoyyyxvy.html

*)     echo "未知命令" ;;
来源：http://dali.vqdsnc.cn/Article/details/gttdiiihcp.html

esac
来源：http://dali.yonumen.top/Article/details/gtkrqcrsse.html

[R12] for 遍历文件
来源：http://dali.xziqi.cn/Article/details/gtpcyqgvdy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ivvv.top/Article/details/gtumkxcqbr.html

[R13] for 计数循环
来源：http://dali.yj20258.top/Article/details/gtsofcnmpd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yuanzhike.top/Article/details/gtbzamormp.html

[R14] C 风格 for
来源：http://dali.sweek.top/Article/details/gtpkesqfwz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.snrcjt.cn/Article/details/gtyxamwpvz.html

[R15] while 逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtlyqylecn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yangfankeji.com/Article/details/gtxbdutfex.html

[R16] until 等待条件
来源：http://dali.xuanzx.com/Article/details/gtwpbkpukb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gtgmpgtepv.html

[R17] 数组定义与取值
来源：http://dali.sxryk.cn/Article/details/gtvtlycjnn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtecrtwloa.html

[R18] 遍历数组
来源：http://dali.meibo888.top/Article/details/gtdvxonvip.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jianghu66.top/Article/details/gtdyvvswny.html

[R19] 数组长度
来源：http://dali.sxryk.cn/Article/details/gthjjqrjye.html

echo "${#arr[@]}"
来源：http://dali.c1oappe.top/Article/details/gtbgkewojp.html

[R20] 关联数组（字典）
来源：http://dali.shzxlz.cn/Article/details/gtrbbglvtj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sxryk.cn/Article/details/gtlvydnmku.html

[R21] 字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gtvsvcjblf.html

echo "${#s}"
来源：http://dali.hysaishi.cn/Article/details/gtpqinnqsy.html

[R22] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gtyjcsyyyb.html

echo "${s:0:5}"
来源：http://dali.gzhubu.top/Article/details/gttsfphosw.html

[R23] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gtrjyuakox.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj20258888.top/Article/details/gttbwhohqo.html

[R24] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gtsxalewcy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ivvv.top/Article/details/gtaeybkobz.html

[R25] 去后缀 / 去前缀
来源：http://dali.nanxinkj.top/Article/details/gtusvqndaw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hammf.cn/Article/details/gtsxyfktie.html

[R26] 命令替换
来源：http://dali.fengsongda.top/Article/details/gtwjgyrttp.html

now=$(date +%F); echo "$now"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmyzdpswu.html

[R27] 算术展开
来源：http://dali.bjfxy.top/Article/details/gtfqkagytq.html

echo $((1 + 2 * 3))
来源：http://dali.9152youxi.cn/Article/details/gtddumgrhx.html

[R28] 浮点运算
来源：http://dali.yj202588.top/Article/details/gtpxmhjcov.html

echo "scale=2; 10/3" | bc
来源：http://dali.316326.xyz/Article/details/gtonxaynxv.html

[R29] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gtrttsafpj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.haohaochexian.top/Article/details/gtrsaggqih.html

[R30] 函数返回状态码
来源：http://dali.zhengqikj.top/Article/details/gtubegoejd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nanxinkj.top/Article/details/gtktwjtaci.html

[R31] 局部变量
来源：http://dali.birdmap.top/Article/details/gtpnhkrpdq.html

f() { local x=1; echo "$x"; }
来源：http://dali.hysaishi.cn/Article/details/gtezdlsbcj.html

[R32] 参数个数校验
来源：http://dali.yuxming.cn/Article/details/gtidznpnwt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.guannengcc.top/Article/details/gtbpzwxeci.html

[R33] 捕获错误并提示行号
来源：http://dali.daria6918.cn/Article/details/gtdyuhekeh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxkzhxgz.html

[R34] 退出时清理
来源：http://dali.nwbrower.top/Article/details/gttyqvmgkn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ybcxt.top/Article/details/gtfcopzfsf.html

[R35] 后台执行并等待
来源：http://dali.gotoacloud.top/Article/details/gtddtguulw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xziqi.cn/Article/details/gtblazeiii.html

[R36] 并发执行多个任务
来源：http://dali.guannengcc.top/Article/details/gtoahvvhgd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daria6918.cn/Article/details/gtjnfsvztx.html

[R37] 把输出赋给变量
来源：http://dali.redwolf501.top/Article/details/gtiffgslkr.html

files=$(ls -1)
来源：http://dali.guannengcc.top/Article/details/gtetenqtxg.html

[R38] 管道串联
来源：http://dali.pycfn.com/Article/details/gtfiwxtapb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guannengcc.top/Article/details/gthhdfcnhx.html

[R39] 重定向标准输出与错误
来源：http://dali.nwbrower.top/Article/details/gtryykqhoe.html

cmd > out.log 2>&1
来源：http://dali.snrcjt.cn/Article/details/gtezauimff.html

[R40] 追加写日志
来源：http://dali.snrcjt.cn/Article/details/gtkmooymxa.html

echo "log" >> out.log
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczlengnv.html

[R41] 丢弃输出
来源：http://dali.jiagoushi.top/Article/details/gtwlybgdvn.html

cmd >/dev/null 2>&1
来源：http://dali.cdnleiting.top/Article/details/gttnzawfze.html

[R42] 输入重定向
来源：http://dali.tian-w.cn/Article/details/gtlmbamqhy.html

wc -l < a.txt
来源：http://dali.zhengqikj.top/Article/details/gtuksscyft.html

[R43] 按名字查找文件
来源：http://dali.jqgfzy.top/Article/details/gtemsxlgvy.html

find . -name "*.log" -type f
来源：http://dali.nanxinkj.top/Article/details/gtaziiqusr.html

[R44] 按修改时间查找
来源：http://dali.ppjwa.cn/Article/details/gttychgxtb.html

find . -mtime -7 -type f
来源：http://dali.sysykeji.top/Article/details/gtiyzswfhd.html

[R45] 批量删除
来源：http://dali.sysykeji.top/Article/details/gtrbqkoyeg.html

find . -name "*.tmp" -delete
来源：http://dali.tianlin.xyz/Article/details/gtyokwdnch.html

[R46] 递归替换文件内容
来源：http://dali.nwbrower.top/Article/details/gtgrkqoucb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hfpthk.cn/Article/details/gtzfbpywsz.html

[R47] sed 单行替换
来源：http://dali.zhengqikj.top/Article/details/gtatkailzk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.aizwys.cn/Article/details/gtffvmafap.html

[R48] awk 取指定列
来源：http://dali.zhongyouzk.top/Article/details/gtdylwjqfu.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtbkemqulh.html

[R49] awk 带条件
来源：http://dali.sufxvd.cn/Article/details/gtcfhccsrr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuetiantiany.cn/Article/details/gtjrhminre.html

[R50] awk 求和
来源：http://dali.nanxuanxn.top/Article/details/gthyrvwevr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnzwpaay.html

[R51] 排序去重取前几
来源：http://dali.daria6918.cn/Article/details/gtsbkhklbq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgrewpae.html

[R52] 统计行数
来源：http://dali.c1oappe.top/Article/details/gtyttfjgwz.html

wc -l a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtwcfrbrdk.html

[R53] 查看文件头与实时尾
来源：http://dali.shangyingyoupin.top/Article/details/gtrfxowjhe.html


<!-- 参考信息 -->