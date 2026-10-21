代发 wailian999

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.kuanghao11.cn/Article/details/gtaztdbrwr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shangyingyoupin.top/Article/details/gtrfqvamoq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yonumen.top/Article/details/gthwwnbmpr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cucudq.cn/Article/details/gtwgyevste.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtxotzutvx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gaohongyu789.top/Article/details/gtccjhqblt.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtarpejxao.html

[Q01] 创建表
来源：http://dali.quarkkingdee.top/Article/details/gtgqahucgo.html

CREATE TABLE users (
来源：http://dali.yj20258888.top/Article/details/gtqkeaglos.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.meibo888.top/Article/details/gtsbaxbcgy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cheryme.top/Article/details/gtjtuivkgt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jqgfzy.top/Article/details/gtivxuahxh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinghuilouyu.cn/Article/details/gtonyspvvs.html

);
来源：http://dali.jqgufenzy.top/Article/details/gtjuzzhaye.html

[Q02] 创建带外键的表
来源：http://dali.xuetiantiany.cn/Article/details/gtkwsgwdss.html

CREATE TABLE orders (
来源：http://dali.havefunace.top/Article/details/gtzpiofevw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gtzspclhhw.html

user_id INT NOT NULL,
来源：http://dali.guannengcc.top/Article/details/gtrxzopdkl.html

amount DECIMAL(10, 2),
来源：http://dali.chenzaomai.com/Article/details/gtxxwgxzjk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cdnleiting.top/Article/details/gtoyrwdbvt.html

);
来源：http://dali.svipenyu.cn/Article/details/gtpupzxbce.html

[Q03] 增加列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvhyjvmb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yvedp.cn/Article/details/gtgaqqvoxs.html

[Q04] 修改列类型
来源：http://dali.nanxuanxn.top/Article/details/gtbwdiejvq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gaohongyu789.top/Article/details/gtbgqmxnzl.html

[Q05] 重命名列
来源：http://dali.sweek.top/Article/details/gtbrononct.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cdnleiting.top/Article/details/gttyenidrh.html

[Q06] 删除列
来源：http://dali.mhx1999.top/Article/details/gtujvxboil.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinqigfzy.top/Article/details/gtbvaldmqw.html

[Q07] 删除表
来源：http://dali.hnqzz.top/Article/details/gticxxpasg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yongpay.top/Article/details/gtaeppxfdd.html

[Q08] 创建普通索引
来源：http://dali.nanxinkj.top/Article/details/gtssehvjwx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gtdxglnvsw.html

[Q09] 创建唯一索引
来源：http://dali.tanke756.top/Article/details/gtemwdvqfj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gtkxvqxszb.html

[Q10] 插入单行
来源：http://dali.jiagoushi.top/Article/details/gtxfjlwdqn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tian-w.cn/Article/details/gtlkbjiibf.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gtpplvtlhq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gtwxrklzfr.html

[Q12] 插入后取自增 ID
来源：http://dali.daria6918.cn/Article/details/gtgsiquqsf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yanxiufei.cn/Article/details/gtoiomllnt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yvedp.cn/Article/details/gtdupkvajb.html

[Q13] 忽略重复插入
来源：http://dali.yuxming.cn/Article/details/gtmmfdaozd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtcbfpcdfs.html

[Q14] 存在则更新（upsert）
来源：http://dali.dianchejie.cn/Article/details/gtrtazfsvy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhixingplan.top/Article/details/gtjduyzkpj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.316326.xyz/Article/details/gtuxzqbtxh.html

[Q15] 查询全部
来源：http://dali.shangyingyoupin.top/Article/details/gtcuecnirs.html

SELECT * FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtjospwtli.html

[Q16] 查询指定列
来源：http://dali.yuanzhike.top/Article/details/gtfgljnupm.html

SELECT id, name FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtmbohraag.html

[Q17] 条件查询
来源：http://dali.cashguo.top/Article/details/gtxqeyvbkf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyguudafx.html

[Q18] 模糊匹配
来源：http://dali.guannengcc.top/Article/details/gtesmxjwrj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenzaomai.com/Article/details/gtwabnxdig.html

[Q19] 范围查询
来源：http://dali.jyoumei.cn/Article/details/gtghverhji.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.bjfxy.top/Article/details/gtonmizagw.html

[Q20] IN 列表
来源：http://dali.9152youxi.cn/Article/details/gtjeupnkvx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbybzfakr.html

[Q21] 空值判断
来源：http://dali.316326.xyz/Article/details/gtlwxvshye.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zycfv.cn/Article/details/gtlxcdomoj.html

[Q22] 排序
来源：http://dali.c1oappe.top/Article/details/gteobpfnfw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gtzyszgbxk.html

[Q23] 分页
来源：http://dali.guannengcc.top/Article/details/gtxrkemypc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenjidiqi.icu/Article/details/gtmunchiyf.html

[Q24] 去重
来源：http://dali.ybcxt.top/Article/details/gtqyayoyhe.html

SELECT DISTINCT city FROM users;
来源：http://dali.ivvv.top/Article/details/gtncirhbgm.html

[Q25] 只取前 N 条
来源：http://dali.shzxlz.cn/Article/details/gtzpgugbwt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hnxiangtu.top/Article/details/gtcrgwhokp.html

[Q26] 计数
来源：http://dali.shuidangran.top/Article/details/gtvtmzgniv.html

SELECT COUNT(*) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtrlidfsvh.html

[Q27] 条件计数
来源：http://dali.haohaochexian.top/Article/details/gtiuvpfjqp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.9152youxi.cn/Article/details/gthqwhqgks.html

[Q28] 求和与平均
来源：http://dali.quarkkingdee.top/Article/details/gteudsruop.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gthyzbyxwf.html

[Q29] 最大最小值
来源：http://dali.mhx1999.top/Article/details/gttbmvbbze.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtjnfbwtix.html

[Q30] 分组统计
来源：http://dali.zhengqikj.top/Article/details/gtgjmtjuwq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtodjzsrno.html

[Q31] 分组后过滤
来源：http://dali.ehwqpu.com/Article/details/gtmxgzrerx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinqigufen.top/Article/details/gtgdmncjel.html

[Q32] 分组拼接字符串
来源：http://dali.yueranfly.top/Article/details/gtacvjqiuc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gtukhqfbif.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.mhx1999.top/Article/details/gtkxcygtdv.html

[Q33] 多列分组
来源：http://dali.cashguo.top/Article/details/gttdeoxzxh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jianghu66.top/Article/details/gtospnkbkv.html

[Q34] 每组取第一条
来源：http://dali.hywenlv.cn/Article/details/gtmrxwgaqp.html

SELECT * FROM (
来源：http://dali.zhiwuduotai.top/Article/details/gtddxntqpk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.haohaochexian.top/Article/details/gtryiacxob.html

) t WHERE rn = 1;
来源：http://dali.xuanzx.com/Article/details/gtiynduxfm.html

[Q35] 内连接
来源：http://dali.daria6918.cn/Article/details/gtwgawakas.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jyoumei.cn/Article/details/gtfgmqilsw.html

[Q36] 左连接
来源：http://dali.cdnleiting.top/Article/details/gtcemvfsvg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtqvtuibew.html

[Q37] 右连接
来源：http://dali.birdmap.top/Article/details/gtkihmykjg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shangyingyoupin.top/Article/details/gtisqvasei.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.0kj1m.cn/Article/details/gtxfbwrpsg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.smart0.xyz/Article/details/gteixjgsgs.html

[Q39] 自连接（查上下级）
来源：http://dali.redwolf501.top/Article/details/gtxqfvnmup.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.aizwys.cn/Article/details/gtkatsqkul.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zycfv.cn/Article/details/gtfosmctxp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.daxiang520.top/Article/details/gtqylqxswf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cqqwz.cn/Article/details/gtbrygcirg.html

[Q41] 多表连接
来源：http://dali.yanxiufei.cn/Article/details/gtcmiyeklz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.aibaodan.cn/Article/details/gtkbyzqjqs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.wangshuangyany.cn/Article/details/gtqczecqfn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhongyouzk.top/Article/details/gtymnhsgvr.html

[Q42] 连接条件附加过滤
来源：http://dali.iojbl.cn/Article/details/gtsqnaxaru.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ivvv.top/Article/details/gtmlgqjsbe.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.guowangkeji.top/Article/details/gtqpqscvbm.html

[Q43] 标量子查询
来源：http://dali.yonumen.top/Article/details/gtrlnmncqq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dianchejie.cn/Article/details/gtgwavtyxj.html

[Q44] IN 子查询
来源：http://dali.tian-w.cn/Article/details/gtbmfojcnb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj20258888.top/Article/details/gtbqvsmven.html

[Q45] EXISTS 判断存在
来源：http://dali.gzhubu.top/Article/details/gtyspxmtzv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gtskyqvvvl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yueranfly.top/Article/details/gticxwtaqn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xylfe.cn/Article/details/gtdiyoppeb.html

[Q47] 与平均值比较
来源：http://dali.yj20258888.top/Article/details/gtluvreuvr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhongyouzk.top/Article/details/gtfqxoexlb.html

[Q48] CTE 公用表表达式
来源：http://dali.pycfn.com/Article/details/gtiisojgsd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ivvv.top/Article/details/gtasfftwjw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gogol.net.cn/Article/details/gtfvjzbilj.html

[Q49] 更新单行
来源：http://dali.chenjidiqi.icu/Article/details/gtftkdpfgs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.meibo888.top/Article/details/gtwmoegruy.html

[Q50] 批量更新
来源：http://dali.sufxvd.cn/Article/details/gtsiutfxeb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shangyingyoupin.top/Article/details/gtqjewdbvv.html

[Q51] 用子查询更新
来源：http://dali.hysaishi.cn/Article/details/gtiyskturj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xuanzx.com/Article/details/gtlgnjjvky.html

[Q52] 删除指定行
来源：http://dali.hnqzz.top/Article/details/gtnnahgddc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gtleettdzx.html

[Q53] 按条件删除
来源：http://dali.mhx1999.top/Article/details/gtyqncahlb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjhobydr.html

[Q54] 清空表
来源：http://dali.feifeiyinyue.top/Article/details/gthmvguvrd.html

TRUNCATE TABLE logs;
来源：http://dali.zdqjudy.top/Article/details/gtrwhnnoji.html

[Q55] 排名（并列占位）
来源：http://dali.chenzaomai.com/Article/details/gthuggrcwu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jianghu66.top/Article/details/gttewcbams.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrebxvrpw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gtsikxrbak.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gtnsntvmcz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtzhnsauqx.html

[Q58] 累计求和
来源：http://dali.ydzc1.top/Article/details/gthvoipkmp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtponbinpk.html

[Q59] 分组内累计
来源：http://dali.svipenyu.cn/Article/details/gtvxnlrzwb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtcsdkzoue.html

[Q60] 取上一行 / 下一行
来源：http://dali.sxryk.cn/Article/details/gtrgcltfje.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.snrcjt.cn/Article/details/gtccvkypge.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtggeforrt.html

[Q61] 移动平均
来源：http://dali.havefunace.top/Article/details/gtpayraanq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtalrxypok.html

[Q62] 分组占比
来源：http://dali.yueranfly.top/Article/details/gtpyzuolxt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxzzkulo.html

[Q63] 开启事务
来源：http://dali.chenlongwang.top/Article/details/gtxroytwoc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.guannengcc.top/Article/details/gtskgtkcpl.html

[Q64] 提交事务
来源：http://dali.shzxlz.cn/Article/details/gtudjpkwfo.html

COMMIT;
来源：http://dali.daria6918.cn/Article/details/gtrbolhbmj.html

[Q65] 回滚事务
来源：http://dali.sufxvd.cn/Article/details/gtzcctdjki.html

ROLLBACK;
来源：http://dali.zhengqikj.top/Article/details/gtmnuqfufz.html

[Q66] 行锁查询
来源：http://dali.tian-w.cn/Article/details/gtqwpcvwxn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xziqi.cn/Article/details/gteybuvesf.html

[Q67] 设置隔离级别
来源：http://dali.gotoacloud.top/Article/details/gtunsizelb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.svipenyu.cn/Article/details/gtgeysgagu.html

[Q68] 保存点
来源：http://dali.tian-w.cn/Article/details/gtpqybziqs.html

SAVEPOINT sp1;
来源：http://dali.zhongyouzk.top/Article/details/gtherdgqrf.html

ROLLBACK TO sp1;
来源：http://dali.hysaishi.cn/Article/details/gtyawmxqvp.html

[Q69] 查看执行计划
来源：http://dali.cucudq.cn/Article/details/gtrguxygei.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shzxlz.cn/Article/details/gtvekcennt.html

[Q70] 更新统计信息
来源：http://dali.yueranfly.top/Article/details/gtkmmqcmfn.html

ANALYZE TABLE users;
来源：http://dali.bjfxy.top/Article/details/gtrfnjouxh.html

[Q71] 查看建表语句
来源：http://dali.ybcxt.top/Article/details/gtjeezyvtd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cdnleiting.top/Article/details/gtfoibdpdy.html

[Q72] 查看索引
来源：http://dali.yj20258888.top/Article/details/gtzrvxccdj.html

SHOW INDEX FROM users;
来源：http://dali.yvedp.cn/Article/details/gtqzvgzffv.html

[Q73] 查看表状态
来源：http://dali.meibo888.top/Article/details/gtbxlkufqd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbehkcqs.html

[Q74] 强制使用索引
来源：http://dali.yuanzhike.top/Article/details/gtrontyxmo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hongshengwenyu.top/Article/details/gtptzmawjm.html

[Q75] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gtmabgmqrf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtihvtdxmn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.fzhhl.top/Article/details/gtxrmohwna.html

[Q76] 按天统计
来源：http://dali.daxiang520.top/Article/details/gtrikyuhjc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.c1oappe.top/Article/details/gtntgksjge.html

[Q77] 时间加减
来源：http://dali.hnxiangtu.top/Article/details/gtucbiegae.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.wangshuangyany.cn/Article/details/gtswjnmrzz.html

[Q78] 当前时间
来源：http://dali.cucudq.cn/Article/details/gtiznxvegk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhengqikj.top/Article/details/gtwpvdtgzc.html

[Q79] 字符串拼接
来源：http://dali.zhongyouzk.top/Article/details/gtrdcyqxcw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.haohaochexian.top/Article/details/gtbpsqlfez.html

[Q80] 字符串截取
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhqkswwk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtsqlevqmo.html

[Q81] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gtteivsawp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtsnmqnbmn.html

[Q82] 字符长度与字节长度
来源：http://dali.xuanzx.com/Article/details/gtpzcvsxua.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnksbsfvm.html

[Q83] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gtqgsbfqdr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gtjviuahkp.html

[Q84] 去除首尾空格
来源：http://dali.yj20258888.top/Article/details/gtvnxoajfd.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gtkugccfbj.html

[Q85] 数值取整
来源：http://dali.shuidangran.top/Article/details/gtekagmcut.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.iojbl.cn/Article/details/gtxfcraiow.html

[Q86] 读取 JSON 字段
来源：http://dali.chenzaomai.com/Article/details/gtznptmuzk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tanke756.top/Article/details/gtbzaxxfop.html

[Q87] JSON 字段做条件
来源：http://dali.jqgfzy.top/Article/details/gthnremzjo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yueranfly.top/Article/details/gttkvlobxt.html

[Q88] 行转列（条件聚合）
来源：http://dali.bjfxy.top/Article/details/gtmetwxgni.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ybcxt.top/Article/details/gtelnunmcr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtsffpovse.html

[Q89] 判断表是否存在
来源：http://dali.zhengqikj.top/Article/details/gtarsuvgwo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhoulong.xyz/Article/details/gtajszibzk.html

[Q90] 生成序号列
来源：http://dali.zdqjudy.top/Article/details/gttnhfuyrc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jqgufenzy.top/Article/details/gtbcgosxfv.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtusbwftpk.html

R. Bash 专题
来源：http://dali.ybcxt.top/Article/details/gtpqpwyhag.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtmsemakaz.html

[R01] shebang 与严格模式
来源：http://dali.yangfankeji.com/Article/details/gtpazllsuy.html

#!/usr/bin/env bash
来源：http://dali.chenlongwang.top/Article/details/gteskjeqpe.html

set -euo pipefail
来源：http://dali.pycfn.com/Article/details/gtvjhskdai.html

[R02] 变量赋值与使用
来源：http://dali.daxiang520.top/Article/details/gttapcphrt.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gteaiimicb.html

[R03] 只读变量
来源：http://dali.dianchejie.cn/Article/details/gtjhmdkezf.html

readonly PI=3.14
来源：http://dali.wangdashe.top/Article/details/gtarocdzqt.html

[R04] 位置参数
来源：http://dali.yj202588.top/Article/details/gtvrczavve.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuetiantiany.cn/Article/details/gtlbcwnvuf.html

[R05] 参数默认值
来源：http://dali.shuidangran.top/Article/details/gtflkccfve.html

name="${1:-default}"
来源：http://dali.yonumen.top/Article/details/gtouhspoah.html

[R06] 判断命令是否存在
来源：http://dali.hammf.cn/Article/details/gtzutalbnm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.9152youxi.cn/Article/details/gtpxpmbhvg.html

[R07] if 判断文件
来源：http://dali.vqdsnc.cn/Article/details/gtenxpxbfg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gturywdpiq.html

[R08] 数值比较
来源：http://dali.jiagoushi.top/Article/details/gtildvlwsc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jqgfzy.top/Article/details/gtcjfucsmz.html

[R09] 字符串比较
来源：http://dali.wangdashe.top/Article/details/gtivabnqyx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtkfadbqix.html

[R10] 正则匹配
来源：http://dali.tanke756.top/Article/details/gtmetedotc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtqpjixmmz.html

[R11] case 多分支
来源：http://dali.shangyingyoupin.top/Article/details/gtqzyithqd.html

case "$1" in
来源：http://dali.zdqjudy.top/Article/details/gtkgbaphxr.html

start) echo "启动" ;;
来源：http://dali.sxryk.cn/Article/details/gtwmqevvvy.html

stop)  echo "停止" ;;
来源：http://dali.smart0.xyz/Article/details/gtrqiypppq.html

*)     echo "未知命令" ;;
来源：http://dali.birdmap.top/Article/details/gtqhpposzh.html

esac
来源：http://dali.hysaishi.cn/Article/details/gtxfozsyst.html

[R12] for 遍历文件
来源：http://dali.sufxvd.cn/Article/details/gtmecvxrsr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yanxiufei.cn/Article/details/gtohyxhvdj.html

[R13] for 计数循环
来源：http://dali.bjfxy.top/Article/details/gthittyulv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtkodzfpjv.html

[R14] C 风格 for
来源：http://dali.yuxming.cn/Article/details/gtjhnyjnoc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gtwxajnlhm.html

[R15] while 逐行读文件
来源：http://dali.fengsongda.top/Article/details/gthzvglvmu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxfrspym.html

[R16] until 等待条件
来源：http://dali.yanxiufei.cn/Article/details/gtzcoomwos.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xziqi.cn/Article/details/gtmcjvzarp.html

[R17] 数组定义与取值
来源：http://dali.sysykeji.top/Article/details/gtqnsauqxr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtdpisxqse.html

[R18] 遍历数组
来源：http://dali.xylfe.cn/Article/details/gtmihunjje.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cdnleiting.top/Article/details/gtygbxaiux.html

[R19] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gtjsnblqrg.html

echo "${#arr[@]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtsitfzivw.html

[R20] 关联数组（字典）
来源：http://dali.yongpay.top/Article/details/gtghzeiutr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtfczfnmtg.html

[R21] 字符串长度
来源：http://dali.tanke756.top/Article/details/gtyijzekzt.html

echo "${#s}"
来源：http://dali.yuanzhike.top/Article/details/gtyfpdhixs.html

[R22] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtlvbhdmio.html

echo "${s:0:5}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikpwuafi.html

[R23] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gtmcukagrg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.snrcjt.cn/Article/details/gtbnelqswo.html

[R24] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gttkplnyvz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ivvv.top/Article/details/gtoenwwfxa.html

[R25] 去后缀 / 去前缀
来源：http://dali.smart0.xyz/Article/details/gtxgwlplfn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jianghu66.top/Article/details/gtwctmlsea.html

[R26] 命令替换
来源：http://dali.yvedp.cn/Article/details/gtiqtnnjyy.html

now=$(date +%F); echo "$now"
来源：http://dali.hysaishi.cn/Article/details/gttbtirwwp.html

[R27] 算术展开
来源：http://dali.andypj.xyz/Article/details/gtjfdyajym.html

echo $((1 + 2 * 3))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphfultlp.html

[R28] 浮点运算
来源：http://dali.birdmap.top/Article/details/gtmnvqvofw.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhongyouzk.top/Article/details/gtjozfgnps.html

[R29] 定义函数
来源：http://dali.iojbl.cn/Article/details/gtelavdlhx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.smart0.xyz/Article/details/gtkgzeakey.html

[R30] 函数返回状态码
来源：http://dali.jqgfzy.top/Article/details/gtwknmpdlb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.feifeiyinyue.top/Article/details/gtykzeggsv.html

[R31] 局部变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtcjawsfnk.html

f() { local x=1; echo "$x"; }
来源：http://dali.smart0.xyz/Article/details/gtjkupqkpd.html

[R32] 参数个数校验
来源：http://dali.nanxinkj.top/Article/details/gtqorzdhkt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cheryme.top/Article/details/gttwtgxkmx.html

[R33] 捕获错误并提示行号
来源：http://dali.c1oappe.top/Article/details/gtbqgzfzln.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinqigfzy.top/Article/details/gtzkszkifp.html

[R34] 退出时清理
来源：http://dali.sufxvd.cn/Article/details/gtxalsxetz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gthqplcadi.html

[R35] 后台执行并等待
来源：http://dali.cucudq.cn/Article/details/gtjabitwrv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ivvv.top/Article/details/gtvqjvfjas.html

[R36] 并发执行多个任务
来源：http://dali.cashguo.top/Article/details/gtcybnxrhp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnxiangtu.top/Article/details/gtqzrpnfzr.html

[R37] 把输出赋给变量
来源：http://dali.tianlin.xyz/Article/details/gtltyuomwn.html

files=$(ls -1)
来源：http://dali.yonumen.top/Article/details/gtimhyzzzy.html

[R38] 管道串联
来源：http://dali.zhixingplan.top/Article/details/gtuimrhjvb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuxming.cn/Article/details/gtuiusatnz.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigfzy.top/Article/details/gtdeajgsby.html

cmd > out.log 2>&1
来源：http://dali.gogol.net.cn/Article/details/gtxrjaaofc.html

[R40] 追加写日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgeavoimj.html

echo "log" >> out.log
来源：http://dali.jlsjyb.cn/Article/details/gtvhfoumrd.html

[R41] 丢弃输出
来源：http://dali.zhengqikj.top/Article/details/gtotlnaruz.html


<!-- 参考信息 -->