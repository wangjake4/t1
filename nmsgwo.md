代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwhaimna.html

[Q05] 重命名列
来源：http://dali.smart0.xyz/Article/details/gtnbtbdgtk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gogol.net.cn/Article/details/gtxkjuedyv.html

[Q06] 删除列
来源：http://dali.shuidangran.top/Article/details/gtuhoaydce.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yvedp.cn/Article/details/gtfeyhxvbx.html

[Q07] 删除表
来源：http://dali.jlsjyb.cn/Article/details/gtnnvlxbao.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xziqi.cn/Article/details/gtqhticjjz.html

[Q08] 创建普通索引
来源：http://dali.redwolf501.top/Article/details/gtmzuvqwgm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.9152youxi.cn/Article/details/gtpcytyljx.html

[Q09] 创建唯一索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaefweihj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daxiang520.top/Article/details/gtziupdiha.html

[Q10] 插入单行
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdecphlm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sysykeji.top/Article/details/gtioydjqsu.html

[Q11] 一次插入多行
来源：http://dali.tanke756.top/Article/details/gtwobyyjtg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ppjwa.cn/Article/details/gtyrtccjkc.html

[Q12] 插入后取自增 ID
来源：http://dali.ydzc1.top/Article/details/gtrdlvjxjc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ppjwa.cn/Article/details/gtkgawqcay.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yvedp.cn/Article/details/gtzxiizjwe.html

[Q13] 忽略重复插入
来源：http://dali.shuidangran.top/Article/details/gtsppvwtky.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gtqjfdxycj.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxinkj.top/Article/details/gtgfgnheip.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.haohaochexian.top/Article/details/gtqtliyknq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.fengsongda.top/Article/details/gtoiqjuhtg.html

[Q15] 查询全部
来源：http://dali.yj20258888.top/Article/details/gttxgzlbrm.html

SELECT * FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtaqyvcctb.html

[Q16] 查询指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gtggqixifg.html

SELECT id, name FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtxxjzmvly.html

[Q17] 条件查询
来源：http://dali.gaohongyu789.top/Article/details/gtazaxoiyd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxeyxlwgi.html

[Q18] 模糊匹配
来源：http://dali.0kj1m.cn/Article/details/gtumdwenyn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenjidiqi.icu/Article/details/gtgazjwioy.html

[Q19] 范围查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvtlojpk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj20258.top/Article/details/gtrljmztvj.html

[Q20] IN 列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmvpupgq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.haohaochexian.top/Article/details/gtvzavwwei.html

[Q21] 空值判断
来源：http://dali.jqgfzy.top/Article/details/gttvqlkptj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxctqjisv.html

[Q22] 排序
来源：http://dali.shangyingyoupin.top/Article/details/gtkiiridpq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.daxiang520.top/Article/details/gtwvzqirzv.html

[Q23] 分页
来源：http://dali.hongshengwenyu.top/Article/details/gtsmyhvuxj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dashuyun.cn/Article/details/gtfkgppjrt.html

[Q24] 去重
来源：http://dali.svipenyu.cn/Article/details/gtmtyvpwcn.html

SELECT DISTINCT city FROM users;
来源：http://dali.tanke756.top/Article/details/gticreczbz.html

[Q25] 只取前 N 条
来源：http://dali.yonumen.top/Article/details/gtuqdzyzhz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj20258.top/Article/details/gtwtzwwnch.html

[Q26] 计数
来源：http://dali.aizwys.cn/Article/details/gtdhhoguht.html

SELECT COUNT(*) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtbrlevqvj.html

[Q27] 条件计数
来源：http://dali.haohaochexian.top/Article/details/gtgkjkfmsp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sweek.top/Article/details/gtrwaozdar.html

[Q28] 求和与平均
来源：http://dali.sxryk.cn/Article/details/gtevzxxhjc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtyuqfwgiz.html

[Q29] 最大最小值
来源：http://dali.zdqjudy.top/Article/details/gtbfstotcj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtsicqesil.html

[Q30] 分组统计
来源：http://dali.cdnleiting.top/Article/details/gtzagntlkk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtmknijfoc.html

[Q31] 分组后过滤
来源：http://dali.haohaochexian.top/Article/details/gthwyxhsin.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfyyehls.html

[Q32] 分组拼接字符串
来源：http://dali.sweek.top/Article/details/gtvmlaqsyq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkkkwycx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwvfnvpa.html

[Q33] 多列分组
来源：http://dali.zhoulong.xyz/Article/details/gticncfiut.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgfzy.top/Article/details/gtrspyymuc.html

[Q34] 每组取第一条
来源：http://dali.meibo888.top/Article/details/gtbarjbgnc.html

SELECT * FROM (
来源：http://dali.aizwys.cn/Article/details/gtmmjhxjwp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xinyue.icu/Article/details/gtvbniiglw.html

) t WHERE rn = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtefhdwilu.html

[Q35] 内连接
来源：http://dali.zhengqikj.top/Article/details/gtplqwflyl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtwswdpenz.html

[Q36] 左连接
来源：http://dali.vqdsnc.cn/Article/details/gtgbgwvwkg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gttxnumuab.html

[Q37] 右连接
来源：http://dali.jyoumei.cn/Article/details/gtcrlvsevb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajqgzjmf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.havefunace.top/Article/details/gtxfoijjbt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhengqikj.top/Article/details/gtpsmnjkni.html

[Q39] 自连接（查上下级）
来源：http://dali.ivvv.top/Article/details/gtpwnivhmm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sweek.top/Article/details/gtspcuvhzf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gaohongyu789.top/Article/details/gtridmwkyt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhiwuduotai.top/Article/details/gtjktfkfcc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yj20258.top/Article/details/gtmfnprowk.html

[Q41] 多表连接
来源：http://dali.snrcjt.cn/Article/details/gtvthnkvwi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ybcxt.top/Article/details/gttmnfyxyg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinqigfzy.top/Article/details/gtbbgewnsp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfprmajfn.html

[Q42] 连接条件附加过滤
来源：http://dali.redwolf501.top/Article/details/gthpdyaneh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuetiantiany.cn/Article/details/gtmjnjmgdx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.vqdsnc.cn/Article/details/gtlxqqewjt.html

[Q43] 标量子查询
来源：http://dali.redwolf501.top/Article/details/gtfwiymkry.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ehwqpu.com/Article/details/gtcaglsipl.html

[Q44] IN 子查询
来源：http://dali.ehwqpu.com/Article/details/gtljbfscag.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.fengsongda.top/Article/details/gtlyblnavv.html

[Q45] EXISTS 判断存在
来源：http://dali.sufxvd.cn/Article/details/gtiagiahjn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ydzc1.top/Article/details/gtanoxjktd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shzxlz.cn/Article/details/gtmigebmba.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgufenzy.top/Article/details/gtrplulror.html

[Q47] 与平均值比较
来源：http://dali.wangshuangyany.cn/Article/details/gtlyujlxui.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xuetiantiany.cn/Article/details/gtybhabuxn.html

[Q48] CTE 公用表表达式
来源：http://dali.xinyue.icu/Article/details/gttwkatnps.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhoulong.xyz/Article/details/gtfngmwqme.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cdnleiting.top/Article/details/gtudbzmyhj.html

[Q49] 更新单行
来源：http://dali.quarkkingdee.top/Article/details/gtcipaxuqd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gtpmdvldhl.html

[Q50] 批量更新
来源：http://dali.yj202588.top/Article/details/gtyfxhaigr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenzaomai.com/Article/details/gtconfughk.html

[Q51] 用子查询更新
来源：http://dali.yj20258888.top/Article/details/gtvpkxxgsb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhixingplan.top/Article/details/gtoeaniumj.html

[Q52] 删除指定行
来源：http://dali.sysykeji.top/Article/details/gtagjlgdbm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.wangdashe.top/Article/details/gtgnwtggns.html

[Q53] 按条件删除
来源：http://dali.redwolf501.top/Article/details/gtxohyjzwi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gtxgioccmk.html

[Q54] 清空表
来源：http://dali.tianlin.xyz/Article/details/gtkldgjdim.html

TRUNCATE TABLE logs;
来源：http://dali.dashuyun.cn/Article/details/gtihyuxgod.html

[Q55] 排名（并列占位）
来源：http://dali.xuetiantiany.cn/Article/details/gtiycuuoid.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nwbrower.top/Article/details/gtxsmnsdzd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jqgfzy.top/Article/details/gtlofplrja.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.svipenyu.cn/Article/details/gtkbvsuawa.html

[Q57] 行号
来源：http://dali.zhongyouzk.top/Article/details/gtivjlvstr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.birdmap.top/Article/details/gtvseyfrjp.html

[Q58] 累计求和
来源：http://dali.yj20258888.top/Article/details/gtixsnkwaa.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.316326.xyz/Article/details/gtsvhqzeaq.html

[Q59] 分组内累计
来源：http://dali.jianghu66.top/Article/details/gtvydtuuuv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpukuwscd.html

[Q60] 取上一行 / 下一行
来源：http://dali.9152youxi.cn/Article/details/gtuahcbcvv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.316326.xyz/Article/details/gtizjwecvs.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtrbxsapxa.html

[Q61] 移动平均
来源：http://dali.yonumen.top/Article/details/gtzgaqomxh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gthjkjveab.html

[Q62] 分组占比
来源：http://dali.jqgfzy.top/Article/details/gtzebtqiii.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gtvobkvbpg.html

[Q63] 开启事务
来源：http://dali.cucudq.cn/Article/details/gtaybkcgvj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zycfv.cn/Article/details/gtqyawjjcz.html

[Q64] 提交事务
来源：http://dali.jlsjyb.cn/Article/details/gtumpuwtky.html

COMMIT;
来源：http://dali.yj202588.top/Article/details/gtvooatcvg.html

[Q65] 回滚事务
来源：http://dali.xinyue.icu/Article/details/gtpcmkbhil.html

ROLLBACK;
来源：http://dali.sysykeji.top/Article/details/gtzuvjzvgp.html

[Q66] 行锁查询
来源：http://dali.ppjwa.cn/Article/details/gtsknmvrcx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.snrcjt.cn/Article/details/gtnxaagxbc.html

[Q67] 设置隔离级别
来源：http://dali.haohaochexian.top/Article/details/gtgamgsvuw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xuanzx.com/Article/details/gtikmnqwww.html

[Q68] 保存点
来源：http://dali.tian-w.cn/Article/details/gtwyjdoupe.html

SAVEPOINT sp1;
来源：http://dali.yvedp.cn/Article/details/gtsjbydjhw.html

ROLLBACK TO sp1;
来源：http://dali.nwbrower.top/Article/details/gtgnxfrjpf.html

[Q69] 查看执行计划
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifoyxonh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhoulong.xyz/Article/details/gtdzphgjpi.html

[Q70] 更新统计信息
来源：http://dali.daria6918.cn/Article/details/gtnkhrfmns.html

ANALYZE TABLE users;
来源：http://dali.tian-w.cn/Article/details/gtvakorjre.html

[Q71] 查看建表语句
来源：http://dali.hysaishi.cn/Article/details/gtebxmciax.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.pycfn.com/Article/details/gtdlipqspd.html

[Q72] 查看索引
来源：http://dali.xuetiantiany.cn/Article/details/gthoxdylfq.html

SHOW INDEX FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtbfivpbkp.html

[Q73] 查看表状态
来源：http://dali.jinqigufen.top/Article/details/gthlnssvao.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yueranfly.top/Article/details/gtergxyssu.html

[Q74] 强制使用索引
来源：http://dali.snrcjt.cn/Article/details/gtrklbmino.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgybvdwq.html

[Q75] 日期格式化
来源：http://dali.svipenyu.cn/Article/details/gtdphglvmh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xziqi.cn/Article/details/gttqozrhlp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmmohtgo.html

[Q76] 按天统计
来源：http://dali.pycfn.com/Article/details/gtlwveboko.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ehwqpu.com/Article/details/gtyxybvbta.html

[Q77] 时间加减
来源：http://dali.pengpengdd.cyou/Article/details/gtbqdvkbjv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenjidiqi.icu/Article/details/gtxlgprlrl.html

[Q78] 当前时间
来源：http://dali.0kj1m.cn/Article/details/gtrqyixmlw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jiagoushi.top/Article/details/gtuyqsrmcc.html

[Q79] 字符串拼接
来源：http://dali.jinqigfzy.top/Article/details/gtqvthacok.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cheryme.top/Article/details/gtobpykwey.html

[Q80] 字符串截取
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwrgdlac.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtrrfueaig.html

[Q81] 字符串替换
来源：http://dali.jyoumei.cn/Article/details/gtdrsvctwi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.guannengcc.top/Article/details/gtmfzwbucc.html

[Q82] 字符长度与字节长度
来源：http://dali.cheryme.top/Article/details/gttvigzasn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtliqluszg.html

[Q83] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gtjuhbtujd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gtxtrclmco.html

[Q84] 去除首尾空格
来源：http://dali.shanyushiyangtech.top/Article/details/gthpifwbas.html

SELECT TRIM(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtbhtjlctu.html

[Q85] 数值取整
来源：http://dali.kuanghao11.cn/Article/details/gtuwmldnhh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ppjwa.cn/Article/details/gtfyboictj.html

[Q86] 读取 JSON 字段
来源：http://dali.tianlin.xyz/Article/details/gtucpwpipw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xinyue.icu/Article/details/gtzgoluzda.html

[Q87] JSON 字段做条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbiwyoqn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jyoumei.cn/Article/details/gtbwbisdmu.html

[Q88] 行转列（条件聚合）
来源：http://dali.sweek.top/Article/details/gtapcuosob.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yuxming.cn/Article/details/gtxbauyjrp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtqapjefsa.html

[Q89] 判断表是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtmzqhgmez.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtepspnxrc.html

[Q90] 生成序号列
来源：http://dali.dianchejie.cn/Article/details/gttgnaduai.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hongshengwenyu.top/Article/details/gtjgmolhxw.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtwbaiuntf.html

R. Bash 专题
来源：http://dali.jqgfzy.top/Article/details/gtscjeanif.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtfnfcdjff.html

[R01] shebang 与严格模式
来源：http://dali.fzhhl.top/Article/details/gtpdnxylyc.html

#!/usr/bin/env bash
来源：http://dali.jinqigufen.top/Article/details/gtbwpuzuct.html

set -euo pipefail
来源：http://dali.nanxuanxn.top/Article/details/gthqlnspcp.html

[R02] 变量赋值与使用
来源：http://dali.dianchejie.cn/Article/details/gtpepwtbrs.html

name="Tom"; echo "$name"
来源：http://dali.chenjidiqi.icu/Article/details/gthomjjekh.html

[R03] 只读变量
来源：http://dali.yonumen.top/Article/details/gtoshzfhwl.html

readonly PI=3.14
来源：http://dali.zhixingplan.top/Article/details/gtakpbpcxx.html

[R04] 位置参数
来源：http://dali.yj20258888.top/Article/details/gtmufthwej.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.fengsongda.top/Article/details/gtlzgicolf.html

[R05] 参数默认值
来源：http://dali.aibaodan.cn/Article/details/gtbmdvadpe.html

name="${1:-default}"
来源：http://dali.guowangkeji.top/Article/details/gtlzmifdwz.html

[R06] 判断命令是否存在
来源：http://dali.sysykeji.top/Article/details/gtvjfehsdy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gtvxwutsil.html

[R07] if 判断文件
来源：http://dali.xinyue.icu/Article/details/gtlurwmmhk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtajzrxpkd.html

[R08] 数值比较
来源：http://dali.sxryk.cn/Article/details/gtqfhvgumk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jianghu66.top/Article/details/gtpsmmqgas.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gtyuwppzfk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nanxinkj.top/Article/details/gtcofpkfac.html

[R10] 正则匹配
来源：http://dali.chenzaomai.com/Article/details/gtwfukcffs.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daxiang520.top/Article/details/gtregtjakq.html

[R11] case 多分支
来源：http://dali.c1oappe.top/Article/details/gthvydfbld.html

case "$1" in
来源：http://dali.kuanghao11.cn/Article/details/gtchntcncw.html

start) echo "启动" ;;
来源：http://dali.yonumen.top/Article/details/gtjacywkri.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfijghvsl.html

*)     echo "未知命令" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtsjcexmtu.html

esac
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjlwsgyr.html

[R12] for 遍历文件
来源：http://dali.0kj1m.cn/Article/details/gthynrmcyt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuanzx.com/Article/details/gtbsveclks.html

[R13] for 计数循环
来源：http://dali.haohaochexian.top/Article/details/gtjauyadcb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtkcdugvsx.html

[R14] C 风格 for
来源：http://dali.sweek.top/Article/details/gthgzbkvic.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xylfe.cn/Article/details/gtjsbkrktl.html

[R15] while 逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gtaffuyrmc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sufxvd.cn/Article/details/gtklrutnii.html

[R16] until 等待条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtooejpswp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.birdmap.top/Article/details/gtoiqxybrk.html

[R17] 数组定义与取值
来源：http://dali.fengsongda.top/Article/details/gtwqmfckxp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.svipenyu.cn/Article/details/gtyegpodaq.html

[R18] 遍历数组
来源：http://dali.svipenyu.cn/Article/details/gtdjlhhjkb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jqgfzy.top/Article/details/gtwaixapvq.html

[R19] 数组长度
来源：http://dali.316326.xyz/Article/details/gtwklhbujc.html

echo "${#arr[@]}"
来源：http://dali.gogol.net.cn/Article/details/gtyjkczvmh.html

[R20] 关联数组（字典）
来源：http://dali.sweek.top/Article/details/gtggooqynt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hfpthk.cn/Article/details/gtjnfdzabn.html

[R21] 字符串长度
来源：http://dali.cucudq.cn/Article/details/gtjewwlehx.html

echo "${#s}"
来源：http://dali.gaohongyu789.top/Article/details/gtecsdaxsp.html

[R22] 截取子串
来源：http://dali.cdnleiting.top/Article/details/gtzsvabugz.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gtqgamlsrw.html

[R23] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gtmsprlrpp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.0kj1m.cn/Article/details/gtpkxpcaii.html

[R24] 大小写转换
来源：http://dali.ydzc1.top/Article/details/gtkjuuodqy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sxryk.cn/Article/details/gtkpxdmuxk.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhoulong.xyz/Article/details/gtgioztstv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.quarkkingdee.top/Article/details/gtcstrlxsn.html

[R26] 命令替换
来源：http://dali.zhengqikj.top/Article/details/gtevnlifdl.html

now=$(date +%F); echo "$now"
来源：http://dali.wangdashe.top/Article/details/gttbqxsjer.html

[R27] 算术展开
来源：http://dali.cashguo.top/Article/details/gterfepcmo.html

echo $((1 + 2 * 3))
来源：http://dali.jyoumei.cn/Article/details/gtujhquvih.html

[R28] 浮点运算
来源：http://dali.snrcjt.cn/Article/details/gtbpohdeen.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnxiangtu.top/Article/details/gtzsncfdug.html

[R29] 定义函数
来源：http://dali.hysaishi.cn/Article/details/gtldwwhljz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.bjfxy.top/Article/details/gtythvddoo.html

[R30] 函数返回状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqhjckbv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj20258888.top/Article/details/gthiurczdh.html

[R31] 局部变量
来源：http://dali.yanxiufei.cn/Article/details/gtdjudehwj.html

f() { local x=1; echo "$x"; }
来源：http://dali.ydzc1.top/Article/details/gtabbxotgp.html

[R32] 参数个数校验
来源：http://dali.ehwqpu.com/Article/details/gtmygtxawq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gtkduqbfft.html

[R33] 捕获错误并提示行号
来源：http://dali.xylfe.cn/Article/details/gtrwsaqgyl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guannengcc.top/Article/details/gtujxqqkvp.html

[R34] 退出时清理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldtutzmc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gtegiesrmg.html

[R35] 后台执行并等待
来源：http://dali.9152youxi.cn/Article/details/gtrhpwlebk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.svipenyu.cn/Article/details/gtuwcnlemz.html

[R36] 并发执行多个任务
来源：http://dali.fzhhl.top/Article/details/gtcknqvsmn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pycfn.com/Article/details/gtpqtvtfft.html

[R37] 把输出赋给变量
来源：http://dali.wangdashe.top/Article/details/gtvkddejsk.html

files=$(ls -1)
来源：http://dali.gaohongyu789.top/Article/details/gtwnqkmkym.html

[R38] 管道串联
来源：http://dali.fengsongda.top/Article/details/gtlkwseqzv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.0kj1m.cn/Article/details/gtrxhdnaef.html

[R39] 重定向标准输出与错误
来源：http://dali.hfpthk.cn/Article/details/gtnygqmiyq.html

cmd > out.log 2>&1
来源：http://dali.yj20258888.top/Article/details/gtncryqrpk.html

[R40] 追加写日志
来源：http://dali.ybcxt.top/Article/details/gteihiahtx.html

echo "log" >> out.log
来源：http://dali.yangfankeji.com/Article/details/gtxazxjwkm.html

[R41] 丢弃输出
来源：http://dali.cqqwz.cn/Article/details/gtwbnqkxxp.html

cmd >/dev/null 2>&1
来源：http://dali.xinyue.icu/Article/details/gtotvxlhpw.html

[R42] 输入重定向
来源：http://dali.shuidangran.top/Article/details/gtsjorkvjh.html

wc -l < a.txt
来源：http://dali.jianghu66.top/Article/details/gtrwwuvzrw.html

[R43] 按名字查找文件
来源：http://dali.cheryme.top/Article/details/gtxmevzxkk.html

find . -name "*.log" -type f
来源：http://dali.wangshuangyany.cn/Article/details/gtgvjsnrni.html

[R44] 按修改时间查找
来源：http://dali.pycfn.com/Article/details/gtaclfqnek.html

find . -mtime -7 -type f
来源：http://dali.daria6918.cn/Article/details/gthwfwhwev.html

[R45] 批量删除
来源：http://dali.gogol.net.cn/Article/details/gtjxqtyjtc.html

find . -name "*.tmp" -delete
来源：http://dali.sufxvd.cn/Article/details/gtmmadgqpm.html

[R46] 递归替换文件内容
来源：http://dali.zhengqikj.top/Article/details/gtiozfqpgy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fzhhl.top/Article/details/gtbxchsfqm.html

[R47] sed 单行替换
来源：http://dali.hywenlv.cn/Article/details/gtkwnzotlp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.meibo888.top/Article/details/gtgkoneobk.html

[R48] awk 取指定列
来源：http://dali.aibaodan.cn/Article/details/gtbmuysdte.html

awk '{print $1, $3}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gttmkthlqk.html

[R49] awk 带条件
来源：http://dali.zycfv.cn/Article/details/gthvanncwh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ehwqpu.com/Article/details/gttydfhvpo.html

[R50] awk 求和
来源：http://dali.dianchejie.cn/Article/details/gtxttktzkl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtrtbcnqhm.html

[R51] 排序去重取前几
来源：http://dali.vqdsnc.cn/Article/details/gtbqkoofyn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaowlywcc.html

[R52] 统计行数
来源：http://dali.gotoacloud.top/Article/details/gtzywirulh.html

wc -l a.txt
来源：http://dali.chenlongwang.top/Article/details/gtgtajrdnj.html

[R53] 查看文件头与实时尾
来源：http://dali.zhengqikj.top/Article/details/gtkgzupnam.html


<!-- 参考信息 -->