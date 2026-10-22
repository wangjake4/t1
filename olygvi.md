代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.0kj1m.cn/Article/details/gthygqypyc.html

[Q05] 重命名列
来源：http://dali.shzxlz.cn/Article/details/gtcqyopgkk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.wangdashe.top/Article/details/gtjkfakodh.html

[Q06] 删除列
来源：http://dali.sxryk.cn/Article/details/gtjuwqwncn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xuetiantiany.cn/Article/details/gtqpldzhdn.html

[Q07] 删除表
来源：http://dali.shuidangran.top/Article/details/gthinlllvb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.0kj1m.cn/Article/details/gtvlsguvct.html

[Q08] 创建普通索引
来源：http://dali.aibaodan.cn/Article/details/gtgsguvcru.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.fengsongda.top/Article/details/gtgzthiuqs.html

[Q09] 创建唯一索引
来源：http://dali.havefunace.top/Article/details/gtrcfilnsy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yueranfly.top/Article/details/gtlucojwjl.html

[Q10] 插入单行
来源：http://dali.bjfxy.top/Article/details/gtzxgbyftn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.9152youxi.cn/Article/details/gtrcvqoxfh.html

[Q11] 一次插入多行
来源：http://dali.cashguo.top/Article/details/gtlfelmkua.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sweek.top/Article/details/gtxabnnvne.html

[Q12] 插入后取自增 ID
来源：http://dali.tian-w.cn/Article/details/gtsbrphzqn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yuxming.cn/Article/details/gtuuhvzoid.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.pycfn.com/Article/details/gtxbckyklm.html

[Q13] 忽略重复插入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqfbbrthk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pycfn.com/Article/details/gtdbtekrfb.html

[Q14] 存在则更新（upsert）
来源：http://dali.jqgfzy.top/Article/details/gtqkwzxcfb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.pengpengdd.cyou/Article/details/gtxtwhnxtj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hywenlv.cn/Article/details/gtsotopxuo.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gthyjzdgqf.html

SELECT * FROM users;
来源：http://dali.redwolf501.top/Article/details/gttfggbrsi.html

[Q16] 查询指定列
来源：http://dali.havefunace.top/Article/details/gtbeuuminc.html

SELECT id, name FROM users;
来源：http://dali.aizwys.cn/Article/details/gtpeslulny.html

[Q17] 条件查询
来源：http://dali.yueranfly.top/Article/details/gtqhtdqpvi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.redwolf501.top/Article/details/gtaftojooo.html

[Q18] 模糊匹配
来源：http://dali.yuxming.cn/Article/details/gtfrhgtxjr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cucudq.cn/Article/details/gtmwwgqfth.html

[Q19] 范围查询
来源：http://dali.shangyingyoupin.top/Article/details/gtfbbksewi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbasmubow.html

[Q20] IN 列表
来源：http://dali.xinyue.icu/Article/details/gtkacdgsbm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cqqwz.cn/Article/details/gtpzxigzyd.html

[Q21] 空值判断
来源：http://dali.dianchejie.cn/Article/details/gtngnznnrb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinqigufen.top/Article/details/gtldihqqot.html

[Q22] 排序
来源：http://dali.jyoumei.cn/Article/details/gtqrdpblzt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbrcmhqmc.html

[Q23] 分页
来源：http://dali.yj20258.top/Article/details/gtvjfkyysk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.fzhhl.top/Article/details/gtmzjngrgv.html

[Q24] 去重
来源：http://dali.kuanghao11.cn/Article/details/gtrfmqdjei.html

SELECT DISTINCT city FROM users;
来源：http://dali.svipenyu.cn/Article/details/gthwcgwpuv.html

[Q25] 只取前 N 条
来源：http://dali.yj202588.top/Article/details/gtfymbecjz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xylfe.cn/Article/details/gtfdluishd.html

[Q26] 计数
来源：http://dali.yangfankeji.com/Article/details/gtomlbgyfc.html

SELECT COUNT(*) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtxeapcoaz.html

[Q27] 条件计数
来源：http://dali.shuidangran.top/Article/details/gtsyjepjop.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtsoisoskh.html

[Q28] 求和与平均
来源：http://dali.sxryk.cn/Article/details/gtfxlrzmih.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtrxumatzb.html

[Q29] 最大最小值
来源：http://dali.ybcxt.top/Article/details/gtgpgssiui.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.meibo888.top/Article/details/gtjojfnyfc.html

[Q30] 分组统计
来源：http://dali.meibo888.top/Article/details/gtcxgmpyau.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gtegonnkcw.html

[Q31] 分组后过滤
来源：http://dali.vqdsnc.cn/Article/details/gtecglyxcr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrpzqzpm.html

[Q32] 分组拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtakrhwjfk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gtiliqhqwk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yonumen.top/Article/details/gtumktgkpz.html

[Q33] 多列分组
来源：http://dali.wangdashe.top/Article/details/gtqhfcsosh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.dashuyun.cn/Article/details/gtreiiudpp.html

[Q34] 每组取第一条
来源：http://dali.c1oappe.top/Article/details/gtuduchobo.html

SELECT * FROM (
来源：http://dali.fengsongda.top/Article/details/gtgagrgkcw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hysaishi.cn/Article/details/gtblxrtgba.html

) t WHERE rn = 1;
来源：http://dali.svipenyu.cn/Article/details/gtidvwtplv.html

[Q35] 内连接
来源：http://dali.redwolf501.top/Article/details/gtqgpubpxd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ybcxt.top/Article/details/gtbjtxtpnt.html

[Q36] 左连接
来源：http://dali.ppjwa.cn/Article/details/gtzvkzrgli.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yongpay.top/Article/details/gtrvbwuzes.html

[Q37] 右连接
来源：http://dali.smart0.xyz/Article/details/gtzlymjqbg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawmblgss.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yuanzhike.top/Article/details/gtgwnlebrg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tianlin.xyz/Article/details/gtjoxzvvnh.html

[Q39] 自连接（查上下级）
来源：http://dali.chenlongwang.top/Article/details/gtxkfjtkuk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctnkihmy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xuanzx.com/Article/details/gtlqsqktni.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sysykeji.top/Article/details/gtycxehqta.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sxryk.cn/Article/details/gtitggtjao.html

[Q41] 多表连接
来源：http://dali.fzhhl.top/Article/details/gtvmgqhuil.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gogol.net.cn/Article/details/gttvbipcbf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.wangshuangyany.cn/Article/details/gtcdorpzon.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hongshengwenyu.top/Article/details/gteduouisz.html

[Q42] 连接条件附加过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtnuanhhcf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigufen.top/Article/details/gtkjhjipmv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aibaodan.cn/Article/details/gtbqpmecez.html

[Q43] 标量子查询
来源：http://dali.ehwqpu.com/Article/details/gtvswlntly.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.pycfn.com/Article/details/gtqxkmyqdp.html

[Q44] IN 子查询
来源：http://dali.shuidangran.top/Article/details/gtbweaxnol.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.feifeiyinyue.top/Article/details/gtyzhzeasf.html

[Q45] EXISTS 判断存在
来源：http://dali.nwbrower.top/Article/details/gtrmfuukpa.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkvevdnb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.vqdsnc.cn/Article/details/gtxwpfqqfk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgufenzy.top/Article/details/gtsymomnnw.html

[Q47] 与平均值比较
来源：http://dali.haohaochexian.top/Article/details/gtkurbsnsv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shuidangran.top/Article/details/gtgcfzbgdk.html

[Q48] CTE 公用表表达式
来源：http://dali.hfpthk.cn/Article/details/gtvcenjcyq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhoulong.xyz/Article/details/gtuwipcxgz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gtacherplj.html

[Q49] 更新单行
来源：http://dali.shuidangran.top/Article/details/gttjfrbiyt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gtcelqzjpe.html

[Q50] 批量更新
来源：http://dali.ehwqpu.com/Article/details/gtrlojgepn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shuidangran.top/Article/details/gtiwnyvtmr.html

[Q51] 用子查询更新
来源：http://dali.tian-w.cn/Article/details/gtzrqdbycj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtoonhojgr.html

[Q52] 删除指定行
来源：http://dali.jinqigfzy.top/Article/details/gtbrdiyxgh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.andypj.xyz/Article/details/gtivimmbcg.html

[Q53] 按条件删除
来源：http://dali.kuanghao11.cn/Article/details/gtzezcsawh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zycfv.cn/Article/details/gtbnbgtguj.html

[Q54] 清空表
来源：http://dali.yonumen.top/Article/details/gtaoicytlk.html

TRUNCATE TABLE logs;
来源：http://dali.xuanzx.com/Article/details/gtzlqbqrhn.html

[Q55] 排名（并列占位）
来源：http://dali.fengsongda.top/Article/details/gttxgbpmut.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cashguo.top/Article/details/gtosqnadzt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.birdmap.top/Article/details/gtvbcnaqbl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gtxlodspby.html

[Q57] 行号
来源：http://dali.yongpay.top/Article/details/gtihqzxgfw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtzrwtbpgu.html

[Q58] 累计求和
来源：http://dali.fzhhl.top/Article/details/gtfmherwtp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtkuixstgj.html

[Q59] 分组内累计
来源：http://dali.fengsongda.top/Article/details/gtlmqrezpj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtmaynvblt.html

[Q60] 取上一行 / 下一行
来源：http://dali.yanxiufei.cn/Article/details/gtwahsdldl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.dashuyun.cn/Article/details/gtatlttmco.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtfynxsxjd.html

[Q61] 移动平均
来源：http://dali.gzhubu.top/Article/details/gtdxuzzuej.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtddpilkpf.html

[Q62] 分组占比
来源：http://dali.cheryme.top/Article/details/gtxfwxnbbl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gtqwpxtxzd.html

[Q63] 开启事务
来源：http://dali.kuanghao11.cn/Article/details/gttahpgncj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.c1oappe.top/Article/details/gtzpzafjjc.html

[Q64] 提交事务
来源：http://dali.smart0.xyz/Article/details/gtknxrerwl.html

COMMIT;
来源：http://dali.sweek.top/Article/details/gtdmjhqkil.html

[Q65] 回滚事务
来源：http://dali.jqgufenzy.top/Article/details/gtxqdmlggw.html

ROLLBACK;
来源：http://dali.jlsjyb.cn/Article/details/gtlxalluut.html

[Q66] 行锁查询
来源：http://dali.xinyue.icu/Article/details/gtrxmvlktz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jqgfzy.top/Article/details/gtqwalzgwf.html

[Q67] 设置隔离级别
来源：http://dali.sxryk.cn/Article/details/gtrjouammv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jiagoushi.top/Article/details/gtxrgwpwqi.html

[Q68] 保存点
来源：http://dali.yuanzhike.top/Article/details/gtszmneyxl.html

SAVEPOINT sp1;
来源：http://dali.cheryme.top/Article/details/gtunktkjhd.html

ROLLBACK TO sp1;
来源：http://dali.smart0.xyz/Article/details/gtajllkbsv.html

[Q69] 查看执行计划
来源：http://dali.guowangkeji.top/Article/details/gtiggiqpfh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shangyingyoupin.top/Article/details/gtarqoiavp.html

[Q70] 更新统计信息
来源：http://dali.fzhhl.top/Article/details/gtqehktdor.html

ANALYZE TABLE users;
来源：http://dali.vqdsnc.cn/Article/details/gtgiherlel.html

[Q71] 查看建表语句
来源：http://dali.kuanghao11.cn/Article/details/gtakyogvrq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nanxuanxn.top/Article/details/gtisogeivk.html

[Q72] 查看索引
来源：http://dali.yangfankeji.com/Article/details/gtztcvvkvi.html

SHOW INDEX FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtdyyceduz.html

[Q73] 查看表状态
来源：http://dali.nanxuanxn.top/Article/details/gtvedfuafc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.fzhhl.top/Article/details/gthmmuwdob.html

[Q74] 强制使用索引
来源：http://dali.gzhubu.top/Article/details/gtlbarflia.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.c1oappe.top/Article/details/gtkxcvbhnk.html

[Q75] 日期格式化
来源：http://dali.guowangkeji.top/Article/details/gtdfkbzagv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtzrlyrkqh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aizwys.cn/Article/details/gtbcybrwzo.html

[Q76] 按天统计
来源：http://dali.zhixingplan.top/Article/details/gtgrflwffa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yanxiufei.cn/Article/details/gtavrezqpx.html

[Q77] 时间加减
来源：http://dali.nanxinkj.top/Article/details/gttratavfx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yueranfly.top/Article/details/gtuwwamgul.html

[Q78] 当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjpcityy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgufenzy.top/Article/details/gtbscvxomq.html

[Q79] 字符串拼接
来源：http://dali.0kj1m.cn/Article/details/gtgiqpxcwv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zycfv.cn/Article/details/gtezefnuoe.html

[Q80] 字符串截取
来源：http://dali.wangshuangyany.cn/Article/details/gtszhsltli.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxamdmmyu.html

[Q81] 字符串替换
来源：http://dali.tian-w.cn/Article/details/gtvuoxmimq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtmpivchax.html

[Q82] 字符长度与字节长度
来源：http://dali.c1oappe.top/Article/details/gtcjgwnpkr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtnllfvlex.html

[Q83] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzjbfmie.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtepwilaau.html

[Q84] 去除首尾空格
来源：http://dali.fengsongda.top/Article/details/gtbswrfkfv.html

SELECT TRIM(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtujmwdzqx.html

[Q85] 数值取整
来源：http://dali.dianchejie.cn/Article/details/gtzkdkcuao.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xziqi.cn/Article/details/gtzqzrvfyy.html

[Q86] 读取 JSON 字段
来源：http://dali.zdqjudy.top/Article/details/gttgggyees.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258.top/Article/details/gtmuzmrgmu.html

[Q87] JSON 字段做条件
来源：http://dali.yj202588.top/Article/details/gtvqplgjfq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shuidangran.top/Article/details/gtjskiuvob.html

[Q88] 行转列（条件聚合）
来源：http://dali.nanxinkj.top/Article/details/gtirohuwll.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shangyingyoupin.top/Article/details/gtspmjxwkj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gzhubu.top/Article/details/gtkcboccfi.html

[Q89] 判断表是否存在
来源：http://dali.0kj1m.cn/Article/details/gtmmzhbrrt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.0kj1m.cn/Article/details/gtpeelqhwk.html

[Q90] 生成序号列
来源：http://dali.jianghu66.top/Article/details/gtpwiuhizb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.feifeiyinyue.top/Article/details/gtfaohjggd.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtrrdezunm.html

R. Bash 专题
来源：http://dali.jqgfzy.top/Article/details/gtwdwdwhpu.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gttyhujdoa.html

[R01] shebang 与严格模式
来源：http://dali.iojbl.cn/Article/details/gtdvrnqeys.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gtrdltddpz.html

set -euo pipefail
来源：http://dali.zhoulong.xyz/Article/details/gtuumsyuul.html

[R02] 变量赋值与使用
来源：http://dali.sufxvd.cn/Article/details/gtcoyhthwm.html

name="Tom"; echo "$name"
来源：http://dali.yanxiufei.cn/Article/details/gtzdclvhmc.html

[R03] 只读变量
来源：http://dali.yanxiufei.cn/Article/details/gtcdbprdoe.html

readonly PI=3.14
来源：http://dali.wangshuangyany.cn/Article/details/gtcedyhffi.html

[R04] 位置参数
来源：http://dali.meibo888.top/Article/details/gtsfddokyw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhengqikj.top/Article/details/gtzhcuofic.html

[R05] 参数默认值
来源：http://dali.kuanghao11.cn/Article/details/gtppzwktmk.html

name="${1:-default}"
来源：http://dali.xuanzx.com/Article/details/gtskumlxwc.html

[R06] 判断命令是否存在
来源：http://dali.jinqigfzy.top/Article/details/gtrmwrgoja.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cucudq.cn/Article/details/gtlgvqgteb.html

[R07] if 判断文件
来源：http://dali.zhixingplan.top/Article/details/gtrizwspwo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fengsongda.top/Article/details/gtpjfjjysq.html

[R08] 数值比较
来源：http://dali.316326.xyz/Article/details/gtxlwdblfw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtdaxnzrtc.html

[R09] 字符串比较
来源：http://dali.havefunace.top/Article/details/gtxjacopvs.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hammf.cn/Article/details/gtlgvnmunu.html

[R10] 正则匹配
来源：http://dali.sweek.top/Article/details/gtynqzcgit.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.9152youxi.cn/Article/details/gtmasjbdpq.html

[R11] case 多分支
来源：http://dali.havefunace.top/Article/details/gtzoyuaqek.html

case "$1" in
来源：http://dali.9152youxi.cn/Article/details/gtlhuiadxj.html

start) echo "启动" ;;
来源：http://dali.xinyue.icu/Article/details/gtntxaiect.html

stop)  echo "停止" ;;
来源：http://dali.aibaodan.cn/Article/details/gtzwfxvacd.html

*)     echo "未知命令" ;;
来源：http://dali.hnqzz.top/Article/details/gtdxkqgiwt.html

esac
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxlmbmhc.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gtocphdyha.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sufxvd.cn/Article/details/gtszrzeqbv.html

[R13] for 计数循环
来源：http://dali.yvedp.cn/Article/details/gtrqjpymss.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtzrzhotce.html

[R14] C 风格 for
来源：http://dali.meibo888.top/Article/details/gtnacegroi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gtylnvtbbv.html

[R15] while 逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtfwwooobz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gzhubu.top/Article/details/gtuxrzoljk.html

[R16] until 等待条件
来源：http://dali.zhoulong.xyz/Article/details/gttewadlub.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.havefunace.top/Article/details/gtgfhnjmlu.html

[R17] 数组定义与取值
来源：http://dali.yuxming.cn/Article/details/gtpmfxwova.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ivvv.top/Article/details/gtpteixgmx.html

[R18] 遍历数组
来源：http://dali.9152youxi.cn/Article/details/gtljwsjssd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hfpthk.cn/Article/details/gttffeqcgj.html

[R19] 数组长度
来源：http://dali.yvedp.cn/Article/details/gtcvozckfz.html

echo "${#arr[@]}"
来源：http://dali.hywenlv.cn/Article/details/gtttwrhdhg.html

[R20] 关联数组（字典）
来源：http://dali.9152youxi.cn/Article/details/gtngqxmztr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.pycfn.com/Article/details/gtoihjorlp.html

[R21] 字符串长度
来源：http://dali.yvedp.cn/Article/details/gtiklgitkf.html

echo "${#s}"
来源：http://dali.yuanzhike.top/Article/details/gtceizmyqq.html

[R22] 截取子串
来源：http://dali.pengpengdd.cyou/Article/details/gtmpksydfc.html

echo "${s:0:5}"
来源：http://dali.xylfe.cn/Article/details/gtjysvexnl.html

[R23] 字符串替换
来源：http://dali.daxiang520.top/Article/details/gtwmsqpeih.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yangfankeji.com/Article/details/gtllhpiacd.html

[R24] 大小写转换
来源：http://dali.yuanzhike.top/Article/details/gtctnarlgu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xziqi.cn/Article/details/gtlfoelnko.html

[R25] 去后缀 / 去前缀
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcuekhlq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhongyouzk.top/Article/details/gtlcazhetp.html

[R26] 命令替换
来源：http://dali.chenlongwang.top/Article/details/gtargcxogh.html

now=$(date +%F); echo "$now"
来源：http://dali.jyoumei.cn/Article/details/gtapscmete.html

[R27] 算术展开
来源：http://dali.zdqjudy.top/Article/details/gtzspcgbop.html

echo $((1 + 2 * 3))
来源：http://dali.yueranfly.top/Article/details/gtbpdzqqbz.html

[R28] 浮点运算
来源：http://dali.jqgufenzy.top/Article/details/gtvmizgjyg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhiwuduotai.top/Article/details/gtbvvwwswn.html

[R29] 定义函数
来源：http://dali.yonumen.top/Article/details/gttyehofmg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258.top/Article/details/gtthpyltni.html

[R30] 函数返回状态码
来源：http://dali.hammf.cn/Article/details/gtkomqbgnq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenzaomai.com/Article/details/gtolxkaqye.html

[R31] 局部变量
来源：http://dali.ppjwa.cn/Article/details/gtrdpqfhal.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhivdgjt.html

[R32] 参数个数校验
来源：http://dali.zhixingplan.top/Article/details/gtexvoizpm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gtxcmhogjt.html

[R33] 捕获错误并提示行号
来源：http://dali.vqdsnc.cn/Article/details/gtgytkbmlb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cashguo.top/Article/details/gtlvkktasm.html

[R34] 退出时清理
来源：http://dali.xuanzx.com/Article/details/gtvozpqlvg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gtimzwhxjh.html

[R35] 后台执行并等待
来源：http://dali.jlsjyb.cn/Article/details/gthovvnehh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daxiang520.top/Article/details/gtxyedwiva.html

[R36] 并发执行多个任务
来源：http://dali.sxryk.cn/Article/details/gtxosmgshm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shanyushiyangtech.top/Article/details/gtpngmzkfo.html

[R37] 把输出赋给变量
来源：http://dali.hnxiangtu.top/Article/details/gtaofkrfbo.html

files=$(ls -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcyglzhim.html

[R38] 管道串联
来源：http://dali.bjfxy.top/Article/details/gtrcloriva.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbrtykcq.html

[R39] 重定向标准输出与错误
来源：http://dali.xylfe.cn/Article/details/gtjssoeznl.html

cmd > out.log 2>&1
来源：http://dali.9152youxi.cn/Article/details/gtoskrnptm.html

[R40] 追加写日志
来源：http://dali.ivvv.top/Article/details/gtzbilwfjt.html

echo "log" >> out.log
来源：http://dali.ydzc1.top/Article/details/gtuzpoeiol.html

[R41] 丢弃输出
来源：http://dali.gzhubu.top/Article/details/gttuwlbkfu.html

cmd >/dev/null 2>&1
来源：http://dali.daxiang520.top/Article/details/gthsiqinky.html

[R42] 输入重定向
来源：http://dali.aizwys.cn/Article/details/gtwyruyrgb.html

wc -l < a.txt
来源：http://dali.iojbl.cn/Article/details/gttzgoiwzj.html

[R43] 按名字查找文件
来源：http://dali.9152youxi.cn/Article/details/gttnsupncu.html

find . -name "*.log" -type f
来源：http://dali.ydzc1.top/Article/details/gtepzjzltb.html

[R44] 按修改时间查找
来源：http://dali.cdnleiting.top/Article/details/gtmsgytyec.html

find . -mtime -7 -type f
来源：http://dali.haohaochexian.top/Article/details/gthwzfbols.html

[R45] 批量删除
来源：http://dali.iojbl.cn/Article/details/gtqftthvlj.html

find . -name "*.tmp" -delete
来源：http://dali.yanxiufei.cn/Article/details/gtlvucebsx.html

[R46] 递归替换文件内容
来源：http://dali.yanxiufei.cn/Article/details/gttlqwcjzo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cheryme.top/Article/details/gtiolffpyi.html

[R47] sed 单行替换
来源：http://dali.snrcjt.cn/Article/details/gthemwvtyh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pycfn.com/Article/details/gtrsmygarh.html

[R48] awk 取指定列
来源：http://dali.cqqwz.cn/Article/details/gtmdwbqnvu.html

awk '{print $1, $3}' a.txt
来源：http://dali.hysaishi.cn/Article/details/gtabdfnblb.html

[R49] awk 带条件
来源：http://dali.zhengqikj.top/Article/details/gtmvjuqzcm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shzxlz.cn/Article/details/gtpbvqadpc.html

[R50] awk 求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczgrzzui.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hysaishi.cn/Article/details/gthaquaheu.html

[R51] 排序去重取前几
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmiqythy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shangyingyoupin.top/Article/details/gtbanwhwhb.html

[R52] 统计行数
来源：http://dali.yj20258888.top/Article/details/gtdjgbhdgl.html

wc -l a.txt
来源：http://dali.bjfxy.top/Article/details/gtirsyndld.html

[R53] 查看文件头与实时尾
来源：http://dali.zdqjudy.top/Article/details/gtbavvbeuw.html


<!-- 参考信息 -->