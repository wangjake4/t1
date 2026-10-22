代发 wailian999

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtnxhdppvg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jyoumei.cn/Article/details/gtjsnpkrpe.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtbaeajzel.html

[Q01] 创建表
来源：http://dali.sufxvd.cn/Article/details/gtotxqfjxf.html

CREATE TABLE users (
来源：http://dali.hongshengwenyu.top/Article/details/gtyrpumktj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.meibo888.top/Article/details/gtzcuhogvq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.aibaodan.cn/Article/details/gtwtchwcpx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.c1oappe.top/Article/details/gtqmcatofc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yvedp.cn/Article/details/gtmalewahr.html

);
来源：http://dali.gogol.net.cn/Article/details/gttesmlaye.html

[Q02] 创建带外键的表
来源：http://dali.shangyingyoupin.top/Article/details/gtsltidblf.html

CREATE TABLE orders (
来源：http://dali.hnxiangtu.top/Article/details/gtsskrmaqf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.smart0.xyz/Article/details/gtklwlqvrq.html

user_id INT NOT NULL,
来源：http://dali.yj20258.top/Article/details/gtrgogvwyq.html

amount DECIMAL(10, 2),
来源：http://dali.zhongyouzk.top/Article/details/gtrjqewxvr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zycfv.cn/Article/details/gtcheiacxm.html

);
来源：http://dali.guowangkeji.top/Article/details/gtblumtzbo.html

[Q03] 增加列
来源：http://dali.cheryme.top/Article/details/gtqtkeooac.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jqgufenzy.top/Article/details/gtlgtbpuip.html

[Q04] 修改列类型
来源：http://dali.shangyingyoupin.top/Article/details/gtwrpllsgo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenlongwang.top/Article/details/gtcayeawsp.html

[Q05] 重命名列
来源：http://dali.shuidangran.top/Article/details/gtkmxxlzzq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.snrcjt.cn/Article/details/gtyiamobew.html

[Q06] 删除列
来源：http://dali.hammf.cn/Article/details/gtpslbsuhm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cqqwz.cn/Article/details/gtmiixxuux.html

[Q07] 删除表
来源：http://dali.ehwqpu.com/Article/details/gtxvagmrml.html

DROP TABLE IF EXISTS orders;
来源：http://dali.kuanghao11.cn/Article/details/gtqgingrxt.html

[Q08] 创建普通索引
来源：http://dali.zdqjudy.top/Article/details/gtrnmpdovd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinghuilouyu.cn/Article/details/gttqnouxha.html

[Q09] 创建唯一索引
来源：http://dali.xylfe.cn/Article/details/gtcwukfnvt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sweek.top/Article/details/gtgadslwzh.html

[Q10] 插入单行
来源：http://dali.sufxvd.cn/Article/details/gtedulagpx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtbubfvlcp.html

[Q11] 一次插入多行
来源：http://dali.wangshuangyany.cn/Article/details/gtzdnjnksv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hywenlv.cn/Article/details/gtgipoualc.html

[Q12] 插入后取自增 ID
来源：http://dali.tanke756.top/Article/details/gtsjvmcbmm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfmblcsq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zdqjudy.top/Article/details/gtxlceszip.html

[Q13] 忽略重复插入
来源：http://dali.xziqi.cn/Article/details/gtcazlxbzc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszwpkleb.html

[Q14] 存在则更新（upsert）
来源：http://dali.svipenyu.cn/Article/details/gtwtgvcxkc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fengsongda.top/Article/details/gtmmgnrczr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hnxiangtu.top/Article/details/gtuptmbqgb.html

[Q15] 查询全部
来源：http://dali.yangfankeji.com/Article/details/gtuphuhjsd.html

SELECT * FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtlpnqyeao.html

[Q16] 查询指定列
来源：http://dali.daxiang520.top/Article/details/gtsusugzis.html

SELECT id, name FROM users;
来源：http://dali.sxryk.cn/Article/details/gtycljympd.html

[Q17] 条件查询
来源：http://dali.pengpengdd.cyou/Article/details/gtljlphuwg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xziqi.cn/Article/details/gtguukzdxt.html

[Q18] 模糊匹配
来源：http://dali.havefunace.top/Article/details/gtpzurvdjr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gtjnjokoas.html

[Q19] 范围查询
来源：http://dali.0kj1m.cn/Article/details/gtkgqyntjq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hfpthk.cn/Article/details/gtnokmcljy.html

[Q20] IN 列表
来源：http://dali.ppjwa.cn/Article/details/gtctszegad.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guowangkeji.top/Article/details/gteojwglpn.html

[Q21] 空值判断
来源：http://dali.cqqwz.cn/Article/details/gtpgsfylax.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jqgufenzy.top/Article/details/gtctntqzsp.html

[Q22] 排序
来源：http://dali.ppjwa.cn/Article/details/gtycmohuaq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqezyexht.html

[Q23] 分页
来源：http://dali.zhongyouzk.top/Article/details/gtsgcdspyo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hammf.cn/Article/details/gtpfpiiqet.html

[Q24] 去重
来源：http://dali.hysaishi.cn/Article/details/gtolmvyxma.html

SELECT DISTINCT city FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtyembucwz.html

[Q25] 只取前 N 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzztwwzvp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.pycfn.com/Article/details/gtnpqyftca.html

[Q26] 计数
来源：http://dali.jinqigufen.top/Article/details/gtnxtdwcgw.html

SELECT COUNT(*) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gthwbwomry.html

[Q27] 条件计数
来源：http://dali.yueranfly.top/Article/details/gtyeltnnwu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yvedp.cn/Article/details/gtgswwxwnn.html

[Q28] 求和与平均
来源：http://dali.gzhubu.top/Article/details/gtlgowecen.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtokjeugpn.html

[Q29] 最大最小值
来源：http://dali.yj20258.top/Article/details/gtaqbwownj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.pycfn.com/Article/details/gtygymwcat.html

[Q30] 分组统计
来源：http://dali.yj20258888.top/Article/details/gtsjkuabbd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjspxfjy.html

[Q31] 分组后过滤
来源：http://dali.yj20258.top/Article/details/gtwpnocaev.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhongyouzk.top/Article/details/gtxskpfcps.html

[Q32] 分组拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gthafhkmex.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gtdrsmbzdr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yonumen.top/Article/details/gtupzjgxof.html

[Q33] 多列分组
来源：http://dali.gaohongyu789.top/Article/details/gtptnefcuw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yanxiufei.cn/Article/details/gtqztxqrrf.html

[Q34] 每组取第一条
来源：http://dali.yongpay.top/Article/details/gtqnhibvcf.html

SELECT * FROM (
来源：http://dali.meibo888.top/Article/details/gtphpiugfj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.svipenyu.cn/Article/details/gtijwitmvl.html

) t WHERE rn = 1;
来源：http://dali.nwbrower.top/Article/details/gtzszoiyrb.html

[Q35] 内连接
来源：http://dali.feifeiyinyue.top/Article/details/gtrumiddql.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gtluqcsdli.html

[Q36] 左连接
来源：http://dali.cheryme.top/Article/details/gtqauitbos.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jlsjyb.cn/Article/details/gtbffgqlae.html

[Q37] 右连接
来源：http://dali.dianchejie.cn/Article/details/gtudnlcncz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shangyingyoupin.top/Article/details/gtgomhakki.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.fengsongda.top/Article/details/gtwpkjtoda.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.redwolf501.top/Article/details/gtlpcohbko.html

[Q39] 自连接（查上下级）
来源：http://dali.c1oappe.top/Article/details/gtfeiihtel.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shzxlz.cn/Article/details/gtogttjzxm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenlongwang.top/Article/details/gtgulsbowj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sxryk.cn/Article/details/gtcmekjhsi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zycfv.cn/Article/details/gtvumcsjcl.html

[Q41] 多表连接
来源：http://dali.cdnleiting.top/Article/details/gttqheiayd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlejkemvo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gzhubu.top/Article/details/gtpjrgjmsy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.feifeiyinyue.top/Article/details/gtryncoqbg.html

[Q42] 连接条件附加过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhdryqqz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jqgfzy.top/Article/details/gtcjvkdtve.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aibaodan.cn/Article/details/gtlkwfmpwf.html

[Q43] 标量子查询
来源：http://dali.hfpthk.cn/Article/details/gthnnblggy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenlongwang.top/Article/details/gtxokxqszv.html

[Q44] IN 子查询
来源：http://dali.316326.xyz/Article/details/gtyfopzwuk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yonumen.top/Article/details/gtrwatguvf.html

[Q45] EXISTS 判断存在
来源：http://dali.xylfe.cn/Article/details/gtqjfbxlav.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.birdmap.top/Article/details/gtudaakrnj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.guowangkeji.top/Article/details/gtsyrnvpxw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigufen.top/Article/details/gtdofupprw.html

[Q47] 与平均值比较
来源：http://dali.svipenyu.cn/Article/details/gtpedintbs.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nwbrower.top/Article/details/gtowqlkjzx.html

[Q48] CTE 公用表表达式
来源：http://dali.quarkkingdee.top/Article/details/gtkswstgwt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.dashuyun.cn/Article/details/gtqvjyzvnc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.svipenyu.cn/Article/details/gtvhojkcmf.html

[Q49] 更新单行
来源：http://dali.tian-w.cn/Article/details/gtdfaablzp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cucudq.cn/Article/details/gtqnmjfjpb.html

[Q50] 批量更新
来源：http://dali.nanxuanxn.top/Article/details/gtllhoccmp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shangyingyoupin.top/Article/details/gtqepcerli.html

[Q51] 用子查询更新
来源：http://dali.nanxuanxn.top/Article/details/gtiqvrlxie.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtpzfwlrqa.html

[Q52] 删除指定行
来源：http://dali.yj20258.top/Article/details/gtsapgnjte.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigfzy.top/Article/details/gtnyizhtqe.html

[Q53] 按条件删除
来源：http://dali.hnxiangtu.top/Article/details/gtammlsixi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenlongwang.top/Article/details/gtrlmvnikq.html

[Q54] 清空表
来源：http://dali.xziqi.cn/Article/details/gtmbtvfwxl.html

TRUNCATE TABLE logs;
来源：http://dali.shuidangran.top/Article/details/gticexvwec.html

[Q55] 排名（并列占位）
来源：http://dali.316326.xyz/Article/details/gtjfkqtzoy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.andypj.xyz/Article/details/gtdwpjktqr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangshuangyany.cn/Article/details/gtpqlyxqxs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xinyue.icu/Article/details/gtvcvjzjdn.html

[Q57] 行号
来源：http://dali.jqgufenzy.top/Article/details/gtbunqlukb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xziqi.cn/Article/details/gtqwpnewsn.html

[Q58] 累计求和
来源：http://dali.yanxiufei.cn/Article/details/gtvbwrkkke.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjxxebzy.html

[Q59] 分组内累计
来源：http://dali.jqgufenzy.top/Article/details/gtakdpkmdy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtfwvlbzbl.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhongyouzk.top/Article/details/gtjwfpwsxt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sysykeji.top/Article/details/gtbqtertie.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtadcccjle.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gtbqopunip.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtgfcmiozr.html

[Q62] 分组占比
来源：http://dali.snrcjt.cn/Article/details/gtijhijqbm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gtfqhcksbx.html

[Q63] 开启事务
来源：http://dali.zhoulong.xyz/Article/details/gtwxsqqpti.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.haohaochexian.top/Article/details/gtlgilqjlw.html

[Q64] 提交事务
来源：http://dali.sufxvd.cn/Article/details/gtotaouech.html

COMMIT;
来源：http://dali.cqqwz.cn/Article/details/gtzwnekzlu.html

[Q65] 回滚事务
来源：http://dali.gaohongyu789.top/Article/details/gtibrplqmh.html

ROLLBACK;
来源：http://dali.zhongyouzk.top/Article/details/gtokzuqbyr.html

[Q66] 行锁查询
来源：http://dali.zhiwuduotai.top/Article/details/gtmxdbdhhq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhoulong.xyz/Article/details/gtwthalsvu.html

[Q67] 设置隔离级别
来源：http://dali.smart0.xyz/Article/details/gtewfwfmae.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gotoacloud.top/Article/details/gtvavmfmpq.html

[Q68] 保存点
来源：http://dali.chenlongwang.top/Article/details/gtvizhsatl.html

SAVEPOINT sp1;
来源：http://dali.jlsjyb.cn/Article/details/gtdlrbrxit.html

ROLLBACK TO sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gtokdvshwh.html

[Q69] 查看执行计划
来源：http://dali.nanxinkj.top/Article/details/gthhveyqip.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.wangshuangyany.cn/Article/details/gtmxvdndjr.html

[Q70] 更新统计信息
来源：http://dali.sxryk.cn/Article/details/gtojjppkbx.html

ANALYZE TABLE users;
来源：http://dali.yuanzhike.top/Article/details/gttxcmitdr.html

[Q71] 查看建表语句
来源：http://dali.316326.xyz/Article/details/gtaphyjfnj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ybcxt.top/Article/details/gtnsgcvfoq.html

[Q72] 查看索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrlxoblc.html

SHOW INDEX FROM users;
来源：http://dali.sweek.top/Article/details/gtszmluldp.html

[Q73] 查看表状态
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehekzfwt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ehwqpu.com/Article/details/gtkvakmwtv.html

[Q74] 强制使用索引
来源：http://dali.gaohongyu789.top/Article/details/gtmqypuark.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.316326.xyz/Article/details/gtqzvxouqq.html

[Q75] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gtswrkdkvs.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtbsseuund.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jiagoushi.top/Article/details/gtaenygrho.html

[Q76] 按天统计
来源：http://dali.xinyue.icu/Article/details/gtrtrevcqk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cdnleiting.top/Article/details/gtmjyiatex.html

[Q77] 时间加减
来源：http://dali.ppjwa.cn/Article/details/gtjsqpbifa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fengsongda.top/Article/details/gtanoxusjq.html

[Q78] 当前时间
来源：http://dali.wangshuangyany.cn/Article/details/gtocugwtba.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuetiantiany.cn/Article/details/gtpurfuerf.html

[Q79] 字符串拼接
来源：http://dali.shuidangran.top/Article/details/gtceafwkxv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zdqjudy.top/Article/details/gtlksqwxlw.html

[Q80] 字符串截取
来源：http://dali.jiagoushi.top/Article/details/gtyjnohcuc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtqykgxhxh.html

[Q81] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gtygpgxpro.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.daria6918.cn/Article/details/gtkofolumd.html

[Q82] 字符长度与字节长度
来源：http://dali.jianghu66.top/Article/details/gteclyighc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtxpfhqseb.html

[Q83] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gtusgvyllw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtyrpbxkwh.html

[Q84] 去除首尾空格
来源：http://dali.shzxlz.cn/Article/details/gtifztfffg.html

SELECT TRIM(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtkbcckcjp.html

[Q85] 数值取整
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgfaucqum.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxinkj.top/Article/details/gtbgupdund.html

[Q86] 读取 JSON 字段
来源：http://dali.jyoumei.cn/Article/details/gtyyntroep.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xuetiantiany.cn/Article/details/gtgbsaenxs.html

[Q87] JSON 字段做条件
来源：http://dali.pycfn.com/Article/details/gtnkfbrvrj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yangfankeji.com/Article/details/gteawttpzk.html

[Q88] 行转列（条件聚合）
来源：http://dali.snrcjt.cn/Article/details/gtcqltpnaj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258.top/Article/details/gtnmkkhgqr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xylfe.cn/Article/details/gteuwqreol.html

[Q89] 判断表是否存在
来源：http://dali.0kj1m.cn/Article/details/gthnxofeng.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenjidiqi.icu/Article/details/gtbjrwmoev.html

[Q90] 生成序号列
来源：http://dali.svipenyu.cn/Article/details/gtyrookmiz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ppjwa.cn/Article/details/gtbfphpqoe.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtfnevtfen.html

R. Bash 专题
来源：http://dali.yuxming.cn/Article/details/gtfohojagv.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtqfqjqvjk.html

[R01] shebang 与严格模式
来源：http://dali.ehwqpu.com/Article/details/gtemizubjw.html

#!/usr/bin/env bash
来源：http://dali.ehwqpu.com/Article/details/gtwkkkqqhc.html

set -euo pipefail
来源：http://dali.ivvv.top/Article/details/gttiynmbjd.html

[R02] 变量赋值与使用
来源：http://dali.ppjwa.cn/Article/details/gtqksmaedv.html

name="Tom"; echo "$name"
来源：http://dali.feifeiyinyue.top/Article/details/gtczmxelht.html

[R03] 只读变量
来源：http://dali.fzhhl.top/Article/details/gtonyvctio.html

readonly PI=3.14
来源：http://dali.yanxiufei.cn/Article/details/gtkrbsppxa.html

[R04] 位置参数
来源：http://dali.yangfankeji.com/Article/details/gtllhbryxz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yvedp.cn/Article/details/gtraqrsnzr.html

[R05] 参数默认值
来源：http://dali.gaohongyu789.top/Article/details/gttsxlutwt.html

name="${1:-default}"
来源：http://dali.andypj.xyz/Article/details/gtarsvsdfk.html

[R06] 判断命令是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gtlpjaqzde.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtyezgqacu.html

[R07] if 判断文件
来源：http://dali.yvedp.cn/Article/details/gtdzhqualh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.mhx1999.top/Article/details/gtwcdypayo.html

[R08] 数值比较
来源：http://dali.quarkkingdee.top/Article/details/gtdjoofcrr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzwkptyr.html

[R09] 字符串比较
来源：http://dali.guannengcc.top/Article/details/gtmalfnejm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.andypj.xyz/Article/details/gtxkdodhpc.html

[R10] 正则匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gttegwjyrq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuanzhike.top/Article/details/gtzhmomuii.html

[R11] case 多分支
来源：http://dali.snrcjt.cn/Article/details/gtnmezkgkr.html

case "$1" in
来源：http://dali.zhixingplan.top/Article/details/gtxzffgvci.html

start) echo "启动" ;;
来源：http://dali.chenlongwang.top/Article/details/gtsqrmbqvg.html

stop)  echo "停止" ;;
来源：http://dali.yangfankeji.com/Article/details/gtyhxdasvc.html

*)     echo "未知命令" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxlqkixb.html

esac
来源：http://dali.hfpthk.cn/Article/details/gtrzwbqkkj.html

[R12] for 遍历文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmccbtqh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hfpthk.cn/Article/details/gtggdyesdy.html

[R13] for 计数循环
来源：http://dali.pycfn.com/Article/details/gtxiamidse.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlirtgyot.html

[R14] C 风格 for
来源：http://dali.guowangkeji.top/Article/details/gtflwfxmme.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gtcjamlcip.html

[R15] while 逐行读文件
来源：http://dali.shuidangran.top/Article/details/gteytdhbzc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.meibo888.top/Article/details/gtmatkejli.html

[R16] until 等待条件
来源：http://dali.xylfe.cn/Article/details/gtxzxpsokm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gtsxgavhvo.html

[R17] 数组定义与取值
来源：http://dali.hammf.cn/Article/details/gthegkgfhd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.iojbl.cn/Article/details/gtnilzysip.html

[R18] 遍历数组
来源：http://dali.haohaochexian.top/Article/details/gtoxhmgtyq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnxiangtu.top/Article/details/gtdscdggag.html

[R19] 数组长度
来源：http://dali.tian-w.cn/Article/details/gtffyiawas.html

echo "${#arr[@]}"
来源：http://dali.chenlongwang.top/Article/details/gtalehipcg.html

[R20] 关联数组（字典）
来源：http://dali.yuanzhike.top/Article/details/gtdbyfblxd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjkjiged.html

[R21] 字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gtwgcccljh.html

echo "${#s}"
来源：http://dali.shzxlz.cn/Article/details/gtgvrcwtuq.html

[R22] 截取子串
来源：http://dali.shangyingyoupin.top/Article/details/gtlxfvhakz.html

echo "${s:0:5}"
来源：http://dali.ivvv.top/Article/details/gtpflcmyqn.html

[R23] 字符串替换
来源：http://dali.yuxming.cn/Article/details/gteubbfxtn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhixingplan.top/Article/details/gtmkjaunel.html

[R24] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gtiehswfyd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fzhhl.top/Article/details/gthkvgbybd.html

[R25] 去后缀 / 去前缀
来源：http://dali.wangshuangyany.cn/Article/details/gtgmdsorrw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aibaodan.cn/Article/details/gtkfuhrjpe.html

[R26] 命令替换
来源：http://dali.yonumen.top/Article/details/gtpzhdfjda.html

now=$(date +%F); echo "$now"
来源：http://dali.jiagoushi.top/Article/details/gtkfiobchz.html

[R27] 算术展开
来源：http://dali.sufxvd.cn/Article/details/gtlrxyrkai.html

echo $((1 + 2 * 3))
来源：http://dali.sweek.top/Article/details/gtliwrhhtz.html

[R28] 浮点运算
来源：http://dali.jiagoushi.top/Article/details/gttezlfofe.html

echo "scale=2; 10/3" | bc
来源：http://dali.jyoumei.cn/Article/details/gtuuhuwcgo.html

[R29] 定义函数
来源：http://dali.meibo888.top/Article/details/gtmrvdnuno.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhixingplan.top/Article/details/gtsrltwakr.html

[R30] 函数返回状态码
来源：http://dali.316326.xyz/Article/details/gtjbyyaetf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.wangdashe.top/Article/details/gtsjnxmacp.html

[R31] 局部变量
来源：http://dali.zdqjudy.top/Article/details/gthviqkyid.html

f() { local x=1; echo "$x"; }
来源：http://dali.jianghu66.top/Article/details/gtfbkzvldj.html

[R32] 参数个数校验
来源：http://dali.tianlin.xyz/Article/details/gtgwmidrns.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gtlcozyljc.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgfzy.top/Article/details/gtrvfsryqv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.birdmap.top/Article/details/gtdgsnjuhh.html

[R34] 退出时清理
来源：http://dali.feifeiyinyue.top/Article/details/gtswbmzfgg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ydzc1.top/Article/details/gtmjuxuzpz.html

[R35] 后台执行并等待
来源：http://dali.9152youxi.cn/Article/details/gtnhzsaxpl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj20258888.top/Article/details/gtrfhbmvlm.html

[R36] 并发执行多个任务
来源：http://dali.smart0.xyz/Article/details/gtdidixewy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhengqikj.top/Article/details/gtkrpvlntc.html

[R37] 把输出赋给变量
来源：http://dali.hongshengwenyu.top/Article/details/gtqaxwlxvb.html

files=$(ls -1)
来源：http://dali.dianchejie.cn/Article/details/gtpbyftxfa.html

[R38] 管道串联
来源：http://dali.hnxiangtu.top/Article/details/gtyhwbsjmz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ehwqpu.com/Article/details/gtrjqvoyxe.html

[R39] 重定向标准输出与错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbpleflxt.html

cmd > out.log 2>&1
来源：http://dali.hammf.cn/Article/details/gtjfxxkgnz.html

[R40] 追加写日志
来源：http://dali.sweek.top/Article/details/gteakojurd.html

echo "log" >> out.log
来源：http://dali.mhx1999.top/Article/details/gttwbtujkb.html

[R41] 丢弃输出
来源：http://dali.havefunace.top/Article/details/gtrjfezwsr.html

cmd >/dev/null 2>&1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdeprimrw.html

[R42] 输入重定向
来源：http://dali.feifeiyinyue.top/Article/details/gtssdtcxjj.html

wc -l < a.txt
来源：http://dali.dashuyun.cn/Article/details/gtgkhlvbko.html

[R43] 按名字查找文件
来源：http://dali.hysaishi.cn/Article/details/gtgfyakltv.html


<!-- 参考信息 -->