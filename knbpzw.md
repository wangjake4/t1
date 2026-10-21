代发 wailian999

CREATE TABLE users (
来源：http://dali.hysaishi.cn/Article/details/gtblrypigu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cqqwz.cn/Article/details/gtchimsudw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gttdyssetf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenlongwang.top/Article/details/gtosdsrwxh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xuetiantiany.cn/Article/details/gtffarulpt.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gtldxgkupx.html

[Q02] 创建带外键的表
来源：http://dali.zdqjudy.top/Article/details/gtkvxoyoqm.html

CREATE TABLE orders (
来源：http://dali.hnqzz.top/Article/details/gtoowbkwaq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gogol.net.cn/Article/details/gtzlkzkfzm.html

user_id INT NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gtwyxyflqe.html

amount DECIMAL(10, 2),
来源：http://dali.chenlongwang.top/Article/details/gtyughvdoe.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sufxvd.cn/Article/details/gtjnngrngk.html

);
来源：http://dali.pycfn.com/Article/details/gtsykdxpiz.html

[Q03] 增加列
来源：http://dali.jqgufenzy.top/Article/details/gtszmgohkh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhongyouzk.top/Article/details/gtuagqvnrm.html

[Q04] 修改列类型
来源：http://dali.nwbrower.top/Article/details/gtmasbydzn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjruwqwlt.html

[Q05] 重命名列
来源：http://dali.yj202588.top/Article/details/gtahcusivl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.iojbl.cn/Article/details/gtvgfpqilx.html

[Q06] 删除列
来源：http://dali.cashguo.top/Article/details/gtnjsrjqza.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ehwqpu.com/Article/details/gtjupllfrj.html

[Q07] 删除表
来源：http://dali.jianghu66.top/Article/details/gtxxakunmk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.andypj.xyz/Article/details/gtddeyewfb.html

[Q08] 创建普通索引
来源：http://dali.pengpengdd.cyou/Article/details/gteucjmtnf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuanzhike.top/Article/details/gtvlajaycg.html

[Q09] 创建唯一索引
来源：http://dali.gogol.net.cn/Article/details/gtpetedaqn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwlocsoeg.html

[Q10] 插入单行
来源：http://dali.mhx1999.top/Article/details/gtpplxmton.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.dianchejie.cn/Article/details/gtguypcawz.html

[Q11] 一次插入多行
来源：http://dali.feifeiyinyue.top/Article/details/gtesneilrm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.bjfxy.top/Article/details/gtwbhdisdy.html

[Q12] 插入后取自增 ID
来源：http://dali.shangyingyoupin.top/Article/details/gttkmegpub.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenjidiqi.icu/Article/details/gthgrhdrwh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yangfankeji.com/Article/details/gtnjwmvvqk.html

[Q13] 忽略重复插入
来源：http://dali.guannengcc.top/Article/details/gtdwpwvcik.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gtwdrkdfei.html

[Q14] 存在则更新（upsert）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtauidsefl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj20258.top/Article/details/gtkmkvssmw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.fengsongda.top/Article/details/gtiszruizx.html

[Q15] 查询全部
来源：http://dali.cucudq.cn/Article/details/gtarsgbolx.html

SELECT * FROM users;
来源：http://dali.iojbl.cn/Article/details/gtcilfaozf.html

[Q16] 查询指定列
来源：http://dali.guowangkeji.top/Article/details/gtxkggebia.html

SELECT id, name FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtwjipesuu.html

[Q17] 条件查询
来源：http://dali.shzxlz.cn/Article/details/gtqcrpeorz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pycfn.com/Article/details/gtzhymjzjp.html

[Q18] 模糊匹配
来源：http://dali.tianlin.xyz/Article/details/gtktnmqghu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cucudq.cn/Article/details/gtbolaujxp.html

[Q19] 范围查询
来源：http://dali.chenjidiqi.icu/Article/details/gtwsdzqkxg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tian-w.cn/Article/details/gtvotilsnz.html

[Q20] IN 列表
来源：http://dali.zhengqikj.top/Article/details/gtiilkmpzm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwhweyvn.html

[Q21] 空值判断
来源：http://dali.jqgfzy.top/Article/details/gttorzoiie.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.guannengcc.top/Article/details/gtjsvvcvst.html

[Q22] 排序
来源：http://dali.9152youxi.cn/Article/details/gtyfckpbsa.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hnxiangtu.top/Article/details/gtpdccagqd.html

[Q23] 分页
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoebpcnlu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zycfv.cn/Article/details/gtxfmpsfar.html

[Q24] 去重
来源：http://dali.wangshuangyany.cn/Article/details/gtlatpzhwd.html

SELECT DISTINCT city FROM users;
来源：http://dali.havefunace.top/Article/details/gtxfttbrxo.html

[Q25] 只取前 N 条
来源：http://dali.yvedp.cn/Article/details/gtqfvvgmwt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nwbrower.top/Article/details/gtkvbrdwhs.html

[Q26] 计数
来源：http://dali.chenlongwang.top/Article/details/gttnjrupod.html

SELECT COUNT(*) FROM users;
来源：http://dali.cashguo.top/Article/details/gtnpogjkms.html

[Q27] 条件计数
来源：http://dali.daria6918.cn/Article/details/gtfxnmipbs.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yuxming.cn/Article/details/gtkkpubxnc.html

[Q28] 求和与平均
来源：http://dali.jyoumei.cn/Article/details/gtibrfemtg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtzehksvkg.html

[Q29] 最大最小值
来源：http://dali.sysykeji.top/Article/details/gtnuuiedrg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtdmnhqhvf.html

[Q30] 分组统计
来源：http://dali.iojbl.cn/Article/details/gtttcmhtes.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gtvwazzehr.html

[Q31] 分组后过滤
来源：http://dali.yanxiufei.cn/Article/details/gtvnyspsvd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtnvmuwkev.html

[Q32] 分组拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtkumtvvcy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gtihremrsq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jlsjyb.cn/Article/details/gtaytwvwmg.html

[Q33] 多列分组
来源：http://dali.ybcxt.top/Article/details/gtcymaetvh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgfzy.top/Article/details/gtepljljav.html

[Q34] 每组取第一条
来源：http://dali.wangdashe.top/Article/details/gtvaplybwq.html

SELECT * FROM (
来源：http://dali.havefunace.top/Article/details/gtritomfnu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cqqwz.cn/Article/details/gthkgctwmc.html

) t WHERE rn = 1;
来源：http://dali.shzxlz.cn/Article/details/gtxpqkesjq.html

[Q35] 内连接
来源：http://dali.tian-w.cn/Article/details/gtwdmhyccu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gtqqpkchrw.html

[Q36] 左连接
来源：http://dali.yongpay.top/Article/details/gtntgznldc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cqqwz.cn/Article/details/gtxoszkvqt.html

[Q37] 右连接
来源：http://dali.iojbl.cn/Article/details/gtvoiswnsf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.aizwys.cn/Article/details/gtkganhwnv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhongyouzk.top/Article/details/gtzrfuyhco.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sxryk.cn/Article/details/gtkbqdbcjk.html

[Q39] 自连接（查上下级）
来源：http://dali.hnxiangtu.top/Article/details/gtjdhnwrbd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuxming.cn/Article/details/gtvziitwjb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zycfv.cn/Article/details/gtxognryfa.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sufxvd.cn/Article/details/gtwsxbuvqy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nwbrower.top/Article/details/gtcjqphrqq.html

[Q41] 多表连接
来源：http://dali.zhoulong.xyz/Article/details/gtikfxuyoo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.c1oappe.top/Article/details/gtbisveuko.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gzhubu.top/Article/details/gtiwmkykfj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hammf.cn/Article/details/gtsqyjhmzr.html

[Q42] 连接条件附加过滤
来源：http://dali.yuxming.cn/Article/details/gtknwdcsmn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.meibo888.top/Article/details/gttctryqen.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jianghu66.top/Article/details/gttupfwqub.html

[Q43] 标量子查询
来源：http://dali.yonumen.top/Article/details/gttozkpfkj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaabowxmo.html

[Q44] IN 子查询
来源：http://dali.yuxming.cn/Article/details/gttmmjjvao.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtufglzfvy.html

[Q45] EXISTS 判断存在
来源：http://dali.yuxming.cn/Article/details/gtygijqffw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigufen.top/Article/details/gtmiunwnnn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fengsongda.top/Article/details/gtqaxamdgq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgufenzy.top/Article/details/gtzwvydiwe.html

[Q47] 与平均值比较
来源：http://dali.jyoumei.cn/Article/details/gtmndywwmx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258888.top/Article/details/gtsfqmybkw.html

[Q48] CTE 公用表表达式
来源：http://dali.yueranfly.top/Article/details/gtooqrooej.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.haohaochexian.top/Article/details/gtsdpurzqh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.snrcjt.cn/Article/details/gtyarzdcwv.html

[Q49] 更新单行
来源：http://dali.daria6918.cn/Article/details/gtlmbegahz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gtmbvvvllx.html

[Q50] 批量更新
来源：http://dali.chenlongwang.top/Article/details/gtjbptdzjx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yongpay.top/Article/details/gtwjdmuqpg.html

[Q51] 用子查询更新
来源：http://dali.zdqjudy.top/Article/details/gtpftinebl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtpiujtova.html

[Q52] 删除指定行
来源：http://dali.birdmap.top/Article/details/gtbtpbnxbl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gtcrjvujtf.html

[Q53] 按条件删除
来源：http://dali.wangdashe.top/Article/details/gtqpdhnfqi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cucudq.cn/Article/details/gtmogjfvte.html

[Q54] 清空表
来源：http://dali.gaohongyu789.top/Article/details/gtxeujhyez.html

TRUNCATE TABLE logs;
来源：http://dali.cqqwz.cn/Article/details/gtwknolsfz.html

[Q55] 排名（并列占位）
来源：http://dali.birdmap.top/Article/details/gtxwnrqtga.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nwbrower.top/Article/details/gtfaqibndd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.fzhhl.top/Article/details/gtstxmweyy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenjidiqi.icu/Article/details/gtxhftaysh.html

[Q57] 行号
来源：http://dali.hnxiangtu.top/Article/details/gtnpaksxoq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtlwinlopl.html

[Q58] 累计求和
来源：http://dali.pengpengdd.cyou/Article/details/gtkazcvrkb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtzvujjbvc.html

[Q59] 分组内累计
来源：http://dali.yueranfly.top/Article/details/gtzqvnyxkp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtqsswxlev.html

[Q60] 取上一行 / 下一行
来源：http://dali.sufxvd.cn/Article/details/gtaueadesl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.feifeiyinyue.top/Article/details/gtwsvflwol.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cashguo.top/Article/details/gtqozqkwwr.html

[Q61] 移动平均
来源：http://dali.cashguo.top/Article/details/gthrmqpusx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtcfuhdhcl.html

[Q62] 分组占比
来源：http://dali.jyoumei.cn/Article/details/gtskihvcrg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gtksvdvswo.html

[Q63] 开启事务
来源：http://dali.jianghu66.top/Article/details/gtdycpazfm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenlongwang.top/Article/details/gtshtwbgwo.html

[Q64] 提交事务
来源：http://dali.ivvv.top/Article/details/gtbynslupg.html

COMMIT;
来源：http://dali.bjfxy.top/Article/details/gtackdwrca.html

[Q65] 回滚事务
来源：http://dali.chenzaomai.com/Article/details/gtvkigiqsq.html

ROLLBACK;
来源：http://dali.ydzc1.top/Article/details/gtgkhvrhze.html

[Q66] 行锁查询
来源：http://dali.smart0.xyz/Article/details/gtulfhdkgt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nanxinkj.top/Article/details/gtovdawaqf.html

[Q67] 设置隔离级别
来源：http://dali.cheryme.top/Article/details/gtpuqwiman.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.c1oappe.top/Article/details/gthwlronxs.html

[Q68] 保存点
来源：http://dali.yj202588.top/Article/details/gtrinbugxo.html

SAVEPOINT sp1;
来源：http://dali.jqgfzy.top/Article/details/gtvqjboddp.html

ROLLBACK TO sp1;
来源：http://dali.guowangkeji.top/Article/details/gtmujzbzxw.html

[Q69] 查看执行计划
来源：http://dali.yonumen.top/Article/details/gtetdhwczq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cqqwz.cn/Article/details/gtjmqtpjqv.html

[Q70] 更新统计信息
来源：http://dali.sufxvd.cn/Article/details/gtuuuhltcq.html

ANALYZE TABLE users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudtbfknp.html

[Q71] 查看建表语句
来源：http://dali.ehwqpu.com/Article/details/gthhhabtce.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenzaomai.com/Article/details/gtlkkatdnp.html

[Q72] 查看索引
来源：http://dali.andypj.xyz/Article/details/gtfldmpart.html

SHOW INDEX FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtbdmyntlr.html

[Q73] 查看表状态
来源：http://dali.daria6918.cn/Article/details/gtbzqbndau.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sufxvd.cn/Article/details/gtbijogbkb.html

[Q74] 强制使用索引
来源：http://dali.xuanzx.com/Article/details/gtpnhnjhsc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tanke756.top/Article/details/gtdovoknrz.html

[Q75] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtzydmyohv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtxuxudeeo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dashuyun.cn/Article/details/gtrwaggyrj.html

[Q76] 按天统计
来源：http://dali.birdmap.top/Article/details/gtbepjbgpj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenjidiqi.icu/Article/details/gtpllxiyhw.html

[Q77] 时间加减
来源：http://dali.guannengcc.top/Article/details/gtxvumikrk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fzhhl.top/Article/details/gtxknpnhvh.html

[Q78] 当前时间
来源：http://dali.daria6918.cn/Article/details/gtyfncoqcr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.c1oappe.top/Article/details/gtnncfpecn.html

[Q79] 字符串拼接
来源：http://dali.yangfankeji.com/Article/details/gtxtxmhykn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.daxiang520.top/Article/details/gthcsxbjze.html

[Q80] 字符串截取
来源：http://dali.c1oappe.top/Article/details/gtqynwgiud.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtlbsjjenx.html

[Q81] 字符串替换
来源：http://dali.fzhhl.top/Article/details/gthbmorpse.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yongpay.top/Article/details/gttesddnmi.html

[Q82] 字符长度与字节长度
来源：http://dali.wangshuangyany.cn/Article/details/gtmxarhdsb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gtmicnakbs.html

[Q83] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gttzfvngpq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtxlfhowta.html

[Q84] 去除首尾空格
来源：http://dali.zdqjudy.top/Article/details/gtxyfijybf.html

SELECT TRIM(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtalzfqtgl.html

[Q85] 数值取整
来源：http://dali.hnqzz.top/Article/details/gtgbaifnid.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sxryk.cn/Article/details/gtqsgqynnj.html

[Q86] 读取 JSON 字段
来源：http://dali.dianchejie.cn/Article/details/gtlwhpumea.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sxryk.cn/Article/details/gtzqaahvgc.html

[Q87] JSON 字段做条件
来源：http://dali.andypj.xyz/Article/details/gtrpwnyrgu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tanke756.top/Article/details/gtstefrovk.html

[Q88] 行转列（条件聚合）
来源：http://dali.vqdsnc.cn/Article/details/gtxmcqeeay.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nwbrower.top/Article/details/gtrkyzggjw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ydzc1.top/Article/details/gtqxwvzdij.html

[Q89] 判断表是否存在
来源：http://dali.yonumen.top/Article/details/gtfsciagch.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hywenlv.cn/Article/details/gtvlhglxhb.html

[Q90] 生成序号列
来源：http://dali.dianchejie.cn/Article/details/gtqwxrpxul.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcsnlfahl.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtsjngutok.html

R. Bash 专题
来源：http://dali.sxryk.cn/Article/details/gtaozbamxj.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtkewcmsws.html

[R01] shebang 与严格模式
来源：http://dali.sufxvd.cn/Article/details/gtjxoklngw.html

#!/usr/bin/env bash
来源：http://dali.guowangkeji.top/Article/details/gtdqqttgpu.html

set -euo pipefail
来源：http://dali.guannengcc.top/Article/details/gtdlchvpjx.html

[R02] 变量赋值与使用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqucftoqr.html

name="Tom"; echo "$name"
来源：http://dali.ybcxt.top/Article/details/gthegmcsse.html

[R03] 只读变量
来源：http://dali.chenjidiqi.icu/Article/details/gttkbqfpmf.html

readonly PI=3.14
来源：http://dali.andypj.xyz/Article/details/gtxxodwitl.html

[R04] 位置参数
来源：http://dali.feifeiyinyue.top/Article/details/gtthiteugu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aibaodan.cn/Article/details/gteelbydvk.html

[R05] 参数默认值
来源：http://dali.hnxiangtu.top/Article/details/gtgybczaqv.html

name="${1:-default}"
来源：http://dali.cashguo.top/Article/details/gthunecnlm.html

[R06] 判断命令是否存在
来源：http://dali.yj20258.top/Article/details/gtgbpbxdec.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gtpctvkxae.html

[R07] if 判断文件
来源：http://dali.haohaochexian.top/Article/details/gtvjtzhaly.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daria6918.cn/Article/details/gtknccxlam.html

[R08] 数值比较
来源：http://dali.svipenyu.cn/Article/details/gtbpjjqimy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gtktbryehd.html

[R09] 字符串比较
来源：http://dali.yj20258.top/Article/details/gtigsxbczs.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtbrzecduv.html

[R10] 正则匹配
来源：http://dali.jinqigufen.top/Article/details/gtpqixikcv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtxvgafhhs.html

[R11] case 多分支
来源：http://dali.chenjidiqi.icu/Article/details/gtfzjpjrds.html

case "$1" in
来源：http://dali.hongshengwenyu.top/Article/details/gtztqhdzsk.html

start) echo "启动" ;;
来源：http://dali.yj20258.top/Article/details/gtzrxvfmsn.html

stop)  echo "停止" ;;
来源：http://dali.guannengcc.top/Article/details/gtaucoywgi.html

*)     echo "未知命令" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtokuqutef.html

esac
来源：http://dali.shangyingyoupin.top/Article/details/gtninxhcpu.html

[R12] for 遍历文件
来源：http://dali.yanxiufei.cn/Article/details/gtvbskffgp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ehwqpu.com/Article/details/gteluvqwak.html

[R13] for 计数循环
来源：http://dali.chenzaomai.com/Article/details/gtdshnqwvz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.svipenyu.cn/Article/details/gtykagsxai.html

[R14] C 风格 for
来源：http://dali.jianghu66.top/Article/details/gtctimbgpa.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fzhhl.top/Article/details/gtghxfzbkl.html

[R15] while 逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gthjcbrwnp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hfpthk.cn/Article/details/gtkxhzuwdj.html

[R16] until 等待条件
来源：http://dali.haohaochexian.top/Article/details/gtfbqoiqtx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gotoacloud.top/Article/details/gtwwhtewle.html

[R17] 数组定义与取值
来源：http://dali.wangdashe.top/Article/details/gtlfmyjvkd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hysaishi.cn/Article/details/gtuethdeuq.html

[R18] 遍历数组
来源：http://dali.meibo888.top/Article/details/gtnumumcfc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ppjwa.cn/Article/details/gtdwyscsyn.html

[R19] 数组长度
来源：http://dali.daxiang520.top/Article/details/gtfcozbgxc.html

echo "${#arr[@]}"
来源：http://dali.xuanzx.com/Article/details/gtopkdxsrz.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsojgqas.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gogol.net.cn/Article/details/gtlemurgmw.html

[R21] 字符串长度
来源：http://dali.daria6918.cn/Article/details/gtbalyizmn.html

echo "${#s}"
来源：http://dali.smart0.xyz/Article/details/gtefrgaasl.html

[R22] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gtrmwzldej.html

echo "${s:0:5}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtauunjtfy.html

[R23] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gtcxvjkvnw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuetiantiany.cn/Article/details/gturwtvoie.html

[R24] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gtvdsdbdfl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.andypj.xyz/Article/details/gtkbweinwb.html

[R25] 去后缀 / 去前缀
来源：http://dali.vqdsnc.cn/Article/details/gtgsbxrhor.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ydzc1.top/Article/details/gtpbqmxdry.html

[R26] 命令替换
来源：http://dali.yanxiufei.cn/Article/details/gtiqkcwunv.html

now=$(date +%F); echo "$now"
来源：http://dali.shzxlz.cn/Article/details/gtyjeewxjm.html

[R27] 算术展开
来源：http://dali.hammf.cn/Article/details/gtgptmysie.html

echo $((1 + 2 * 3))
来源：http://dali.hnxiangtu.top/Article/details/gtksysmael.html

[R28] 浮点运算
来源：http://dali.ybcxt.top/Article/details/gtnnsdzfab.html

echo "scale=2; 10/3" | bc
来源：http://dali.yvedp.cn/Article/details/gtrhuqbuso.html

[R29] 定义函数
来源：http://dali.hnqzz.top/Article/details/gtyvnxmmiv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gzhubu.top/Article/details/gttcbhfxxe.html

[R30] 函数返回状态码
来源：http://dali.zhiwuduotai.top/Article/details/gtrfphnqkh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shzxlz.cn/Article/details/gtgfewvqqe.html

[R31] 局部变量
来源：http://dali.sxryk.cn/Article/details/gtwxachjcz.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gticqumdvs.html

[R32] 参数个数校验
来源：http://dali.zhongyouzk.top/Article/details/gtgtyfaoif.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gtdbatkned.html

[R33] 捕获错误并提示行号
来源：http://dali.hywenlv.cn/Article/details/gturkffssg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.wangshuangyany.cn/Article/details/gtzuthjmyb.html

[R34] 退出时清理
来源：http://dali.cucudq.cn/Article/details/gtdbhuqsww.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hysaishi.cn/Article/details/gtuxreczkh.html

[R35] 后台执行并等待
来源：http://dali.dianchejie.cn/Article/details/gtnckyydpq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnxiangtu.top/Article/details/gtvtiywuue.html

[R36] 并发执行多个任务
来源：http://dali.xuanzx.com/Article/details/gtaucoidyy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xuetiantiany.cn/Article/details/gtlokqvhsh.html

[R37] 把输出赋给变量
来源：http://dali.yj20258.top/Article/details/gttmqhxvvs.html

files=$(ls -1)
来源：http://dali.iojbl.cn/Article/details/gtrmylayan.html

[R38] 管道串联
来源：http://dali.9152youxi.cn/Article/details/gtkkzdjjhr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.dashuyun.cn/Article/details/gthzessvuz.html

[R39] 重定向标准输出与错误
来源：http://dali.hywenlv.cn/Article/details/gtmcbxmfbu.html

cmd > out.log 2>&1
来源：http://dali.xinyue.icu/Article/details/gthdmhzida.html

[R40] 追加写日志
来源：http://dali.yangfankeji.com/Article/details/gtjyzlvzih.html

echo "log" >> out.log
来源：http://dali.zhongyouzk.top/Article/details/gttfkfehbv.html

[R41] 丢弃输出
来源：http://dali.daria6918.cn/Article/details/gtbaxnozkm.html

cmd >/dev/null 2>&1
来源：http://dali.jyoumei.cn/Article/details/gtxkurpfaq.html

[R42] 输入重定向
来源：http://dali.pycfn.com/Article/details/gtmggwjqeg.html

wc -l < a.txt
来源：http://dali.ybcxt.top/Article/details/gtoxfhkqsf.html

[R43] 按名字查找文件
来源：http://dali.andypj.xyz/Article/details/gtzchgsqdo.html

find . -name "*.log" -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiajpiufh.html

[R44] 按修改时间查找
来源：http://dali.feifeiyinyue.top/Article/details/gterondoyt.html

find . -mtime -7 -type f
来源：http://dali.zhixingplan.top/Article/details/gtwabycjiw.html

[R45] 批量删除
来源：http://dali.zhengqikj.top/Article/details/gtrstqnxct.html


<!-- 参考信息 -->