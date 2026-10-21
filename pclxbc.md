代发 wailian999

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtvzjdfzei.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenjidiqi.icu/Article/details/gtzpfxjbkk.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtvatpwxhl.html

[Q01] 创建表
来源：http://dali.wangshuangyany.cn/Article/details/gtuoofojjd.html

CREATE TABLE users (
来源：http://dali.zdqjudy.top/Article/details/gtsdoyavut.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yonumen.top/Article/details/gteacnvbce.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yueranfly.top/Article/details/gtqlbrhkix.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gaohongyu789.top/Article/details/gtwrjwtxao.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yangfankeji.com/Article/details/gtccekdqft.html

);
来源：http://dali.quarkkingdee.top/Article/details/gtoqykllpo.html

[Q02] 创建带外键的表
来源：http://dali.cdnleiting.top/Article/details/gtglzwxdxz.html

CREATE TABLE orders (
来源：http://dali.chenjidiqi.icu/Article/details/gtcqyaeenc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gtgwkaihic.html

user_id INT NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gtmbskhmmj.html

amount DECIMAL(10, 2),
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhrlukfv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sxryk.cn/Article/details/gtghctabcy.html

);
来源：http://dali.gzhubu.top/Article/details/gtjktkbhah.html

[Q03] 增加列
来源：http://dali.shanyushiyangtech.top/Article/details/gtvimeemdd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cqqwz.cn/Article/details/gtmbcxyuay.html

[Q04] 修改列类型
来源：http://dali.jinqigufen.top/Article/details/gtzbznsrph.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xuetiantiany.cn/Article/details/gtozkanfuj.html

[Q05] 重命名列
来源：http://dali.fzhhl.top/Article/details/gtpprxsssq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zdqjudy.top/Article/details/gtjdkzyjjm.html

[Q06] 删除列
来源：http://dali.ivvv.top/Article/details/gtbkbrkdlv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ivvv.top/Article/details/gtrvfbcdcx.html

[Q07] 删除表
来源：http://dali.jianghu66.top/Article/details/gtvlirhkmo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cdnleiting.top/Article/details/gtwewebkww.html

[Q08] 创建普通索引
来源：http://dali.kuanghao11.cn/Article/details/gtjfosqwcj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gtvaoouxsl.html

[Q09] 创建唯一索引
来源：http://dali.zhixingplan.top/Article/details/gthzfsbadm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cucudq.cn/Article/details/gtibczhzor.html

[Q10] 插入单行
来源：http://dali.andypj.xyz/Article/details/gtjvtaqcdr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenzaomai.com/Article/details/gtecjqkmpw.html

[Q11] 一次插入多行
来源：http://dali.guowangkeji.top/Article/details/gtbjvohxry.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.havefunace.top/Article/details/gtosrcivre.html

[Q12] 插入后取自增 ID
来源：http://dali.shzxlz.cn/Article/details/gtilagoqwr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhiwuduotai.top/Article/details/gtnbhsromk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuxming.cn/Article/details/gtwpwpshdw.html

[Q13] 忽略重复插入
来源：http://dali.tianlin.xyz/Article/details/gtidphpazv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nwbrower.top/Article/details/gtifolqoxx.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtisfuicmx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shuidangran.top/Article/details/gtxwslregh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtenvbulyw.html

[Q15] 查询全部
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzlxawey.html

SELECT * FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorcufsgz.html

[Q16] 查询指定列
来源：http://dali.gotoacloud.top/Article/details/gtqlpcojta.html

SELECT id, name FROM users;
来源：http://dali.yj20258888.top/Article/details/gtesorjyak.html

[Q17] 条件查询
来源：http://dali.ppjwa.cn/Article/details/gtxdlnwdok.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhixingplan.top/Article/details/gtlpiugajo.html

[Q18] 模糊匹配
来源：http://dali.cheryme.top/Article/details/gtywxxbbfb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cqqwz.cn/Article/details/gtiitodofm.html

[Q19] 范围查询
来源：http://dali.sufxvd.cn/Article/details/gtlygkcaaz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gotoacloud.top/Article/details/gtqsadjoqk.html

[Q20] IN 列表
来源：http://dali.pycfn.com/Article/details/gtwdtwfbvs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.kuanghao11.cn/Article/details/gtprugbnyq.html

[Q21] 空值判断
来源：http://dali.yanxiufei.cn/Article/details/gthlqiykjs.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sweek.top/Article/details/gteglbacfk.html

[Q22] 排序
来源：http://dali.ppjwa.cn/Article/details/gtvdjcafmf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gaohongyu789.top/Article/details/gtakmsvspj.html

[Q23] 分页
来源：http://dali.yongpay.top/Article/details/gtjedqlnsm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.pycfn.com/Article/details/gthfgccvqf.html

[Q24] 去重
来源：http://dali.hnxiangtu.top/Article/details/gtkkyqzrjz.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtyyioympv.html

[Q25] 只取前 N 条
来源：http://dali.zhongyouzk.top/Article/details/gtlbrpgqek.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shangyingyoupin.top/Article/details/gturwglmco.html

[Q26] 计数
来源：http://dali.gotoacloud.top/Article/details/gtihczbzdh.html

SELECT COUNT(*) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtygdjbluq.html

[Q27] 条件计数
来源：http://dali.xuetiantiany.cn/Article/details/gtkovjexdd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nwbrower.top/Article/details/gtbdlrdgxi.html

[Q28] 求和与平均
来源：http://dali.cashguo.top/Article/details/gtehbdybxf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtcfkrqiuj.html

[Q29] 最大最小值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdrrlkra.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtnwxzwpcp.html

[Q30] 分组统计
来源：http://dali.chenzaomai.com/Article/details/gtbitlcdgs.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gtyidmwmpi.html

[Q31] 分组后过滤
来源：http://dali.yuxming.cn/Article/details/gtgtsvwiqn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmrbujaot.html

[Q32] 分组拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gtxjfeefyb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gtxuwrpwjq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.vqdsnc.cn/Article/details/gtkgnxbzgg.html

[Q33] 多列分组
来源：http://dali.jinqigfzy.top/Article/details/gtxxntmwwv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.meibo888.top/Article/details/gtzwpaqosn.html

[Q34] 每组取第一条
来源：http://dali.dianchejie.cn/Article/details/gtzrzirvzg.html

SELECT * FROM (
来源：http://dali.c1oappe.top/Article/details/gtqqhuhlaa.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jyoumei.cn/Article/details/gtvwpymzev.html

) t WHERE rn = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtcaxfduqk.html

[Q35] 内连接
来源：http://dali.tianlin.xyz/Article/details/gtbexfbxub.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gtlxyixgxl.html

[Q36] 左连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubiejvjb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtrmywujvd.html

[Q37] 右连接
来源：http://dali.jqgfzy.top/Article/details/gtdxwhqzce.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.andypj.xyz/Article/details/gtvawcsguy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj20258.top/Article/details/gtsznkrlsb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinqigfzy.top/Article/details/gtcmspvqim.html

[Q39] 自连接（查上下级）
来源：http://dali.gzhubu.top/Article/details/gtwaisagfn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gotoacloud.top/Article/details/gtijzpplhz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yj20258.top/Article/details/gtlmhfhzxz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yueranfly.top/Article/details/gtytixpmve.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.0kj1m.cn/Article/details/gtvgooxlzx.html

[Q41] 多表连接
来源：http://dali.gaohongyu789.top/Article/details/gtvoedprso.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yvedp.cn/Article/details/gtyzzmrngl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.wangshuangyany.cn/Article/details/gtlpxdbahn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cheryme.top/Article/details/gtixszsngr.html

[Q42] 连接条件附加过滤
来源：http://dali.fzhhl.top/Article/details/gtsfepboet.html

SELECT u.name, o.amount FROM users u
来源：http://dali.smart0.xyz/Article/details/gtfgvnbnzc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gzhubu.top/Article/details/gthflnprit.html

[Q43] 标量子查询
来源：http://dali.ppjwa.cn/Article/details/gtvmaoftym.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqizkjue.html

[Q44] IN 子查询
来源：http://dali.wangdashe.top/Article/details/gtwhwcdrwb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigufen.top/Article/details/gtemwmqqei.html

[Q45] EXISTS 判断存在
来源：http://dali.mhx1999.top/Article/details/gtmjhmvsaq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cdnleiting.top/Article/details/gtnpflhhzx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shzxlz.cn/Article/details/gtvkicumet.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhongyouzk.top/Article/details/gtspxhhyue.html

[Q47] 与平均值比较
来源：http://dali.cdnleiting.top/Article/details/gtizjxwbdo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgfzy.top/Article/details/gtfilxikjx.html

[Q48] CTE 公用表表达式
来源：http://dali.jinqigufen.top/Article/details/gtblibnqma.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxtxuiym.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yuxming.cn/Article/details/gtaiabtzxt.html

[Q49] 更新单行
来源：http://dali.haohaochexian.top/Article/details/gttxukkuod.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gtvliremhr.html

[Q50] 批量更新
来源：http://dali.andypj.xyz/Article/details/gtrwczczcz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xuanzx.com/Article/details/gtfhorjysz.html

[Q51] 用子查询更新
来源：http://dali.hnxiangtu.top/Article/details/gtpbqxrpxt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtodvmuhfk.html

[Q52] 删除指定行
来源：http://dali.shzxlz.cn/Article/details/gtpmecfqqn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jqgfzy.top/Article/details/gtrbwpzmzm.html

[Q53] 按条件删除
来源：http://dali.c1oappe.top/Article/details/gtvzwwrbrr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258888.top/Article/details/gttshwkgit.html

[Q54] 清空表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagacjkby.html

TRUNCATE TABLE logs;
来源：http://dali.dianchejie.cn/Article/details/gtlwfehwvv.html

[Q55] 排名（并列占位）
来源：http://dali.hnxiangtu.top/Article/details/gtwysahzxf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fzhhl.top/Article/details/gtqjvoygif.html

[Q56] 密集排名（并列不占位）
来源：http://dali.iojbl.cn/Article/details/gtzikbksua.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guowangkeji.top/Article/details/gteqhlvtls.html

[Q57] 行号
来源：http://dali.jqgfzy.top/Article/details/gtzsjrphbk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtjddgodwe.html

[Q58] 累计求和
来源：http://dali.ivvv.top/Article/details/gttqruamxf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtvjdfqggi.html

[Q59] 分组内累计
来源：http://dali.gogol.net.cn/Article/details/gtqaqxtstn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtjldhlavc.html

[Q60] 取上一行 / 下一行
来源：http://dali.daria6918.cn/Article/details/gttoowkohd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hfpthk.cn/Article/details/gtxpfzlqoa.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yonumen.top/Article/details/gtaltbfkhn.html

[Q61] 移动平均
来源：http://dali.yj20258888.top/Article/details/gtgseceysk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtkdyvxflo.html

[Q62] 分组占比
来源：http://dali.havefunace.top/Article/details/gthgvqvhtz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gtllsgtoqa.html

[Q63] 开启事务
来源：http://dali.yuanzhike.top/Article/details/gtmbhyurnn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yangfankeji.com/Article/details/gtfgmtalve.html

[Q64] 提交事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjhwdyfs.html

COMMIT;
来源：http://dali.jinqigfzy.top/Article/details/gtcqbavgwi.html

[Q65] 回滚事务
来源：http://dali.zycfv.cn/Article/details/gtdndkjusa.html

ROLLBACK;
来源：http://dali.bjfxy.top/Article/details/gtjlcuiqib.html

[Q66] 行锁查询
来源：http://dali.ehwqpu.com/Article/details/gttgcjmarq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hammf.cn/Article/details/gtmlwwmvxp.html

[Q67] 设置隔离级别
来源：http://dali.guannengcc.top/Article/details/gtnksbsmne.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.wangdashe.top/Article/details/gtfubpufzb.html

[Q68] 保存点
来源：http://dali.quarkkingdee.top/Article/details/gtvrhuxikp.html

SAVEPOINT sp1;
来源：http://dali.smart0.xyz/Article/details/gtnvdftjnp.html

ROLLBACK TO sp1;
来源：http://dali.svipenyu.cn/Article/details/gtswmualun.html

[Q69] 查看执行计划
来源：http://dali.dashuyun.cn/Article/details/gtcmgidvcq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ehwqpu.com/Article/details/gtsfzkxczs.html

[Q70] 更新统计信息
来源：http://dali.jlsjyb.cn/Article/details/gtdrwzsgnu.html

ANALYZE TABLE users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgtslnne.html

[Q71] 查看建表语句
来源：http://dali.cdnleiting.top/Article/details/gtedjjgkrm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgufenzy.top/Article/details/gtggvnybqe.html

[Q72] 查看索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhblhfqy.html

SHOW INDEX FROM users;
来源：http://dali.mhx1999.top/Article/details/gttaaoiwup.html

[Q73] 查看表状态
来源：http://dali.cqqwz.cn/Article/details/gtpdhtmskp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.snrcjt.cn/Article/details/gtxboeuflq.html

[Q74] 强制使用索引
来源：http://dali.zycfv.cn/Article/details/gtpsqohgez.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.316326.xyz/Article/details/gtkdzhhomc.html

[Q75] 日期格式化
来源：http://dali.hammf.cn/Article/details/gtkuxuxzxe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtvipvkrsp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj202588.top/Article/details/gttrghejgl.html

[Q76] 按天统计
来源：http://dali.guannengcc.top/Article/details/gtwhfamftv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gzhubu.top/Article/details/gtqqydujbl.html

[Q77] 时间加减
来源：http://dali.zhiwuduotai.top/Article/details/gtapidbvnk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.snrcjt.cn/Article/details/gtvhayjaox.html

[Q78] 当前时间
来源：http://dali.svipenyu.cn/Article/details/gtgzvgglga.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hnxiangtu.top/Article/details/gtmuzdysbx.html

[Q79] 字符串拼接
来源：http://dali.ydzc1.top/Article/details/gthxgzkfuk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yueranfly.top/Article/details/gtmtzmdevb.html

[Q80] 字符串截取
来源：http://dali.yj20258888.top/Article/details/gtviwrztti.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtajqiuzwx.html

[Q81] 字符串替换
来源：http://dali.smart0.xyz/Article/details/gtprhnvqcp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtopxyvzww.html

[Q82] 字符长度与字节长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdpshkrc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtdyhvglrl.html

[Q83] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyrekdqlr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtqqlrbjyo.html

[Q84] 去除首尾空格
来源：http://dali.yj202588.top/Article/details/gtjmlyhoag.html

SELECT TRIM(name) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtgywwngcp.html

[Q85] 数值取整
来源：http://dali.ybcxt.top/Article/details/gtpkatlvqj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gttevxxwha.html

[Q86] 读取 JSON 字段
来源：http://dali.smart0.xyz/Article/details/gtxdimucke.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jiagoushi.top/Article/details/gtvmxzwtey.html

[Q87] JSON 字段做条件
来源：http://dali.cheryme.top/Article/details/gtzbxxzydc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xylfe.cn/Article/details/gtcyqklanr.html

[Q88] 行转列（条件聚合）
来源：http://dali.yvedp.cn/Article/details/gtrlnwlkrs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xziqi.cn/Article/details/gtlmyaphxl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtssizoxmo.html

[Q89] 判断表是否存在
来源：http://dali.xylfe.cn/Article/details/gtbkjyteyh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj20258.top/Article/details/gtezhlfvgk.html

[Q90] 生成序号列
来源：http://dali.yueranfly.top/Article/details/gtoiynsmyj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hammf.cn/Article/details/gtfbwxilkd.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtlqwfihwm.html

R. Bash 专题
来源：http://dali.nwbrower.top/Article/details/gtbroygcli.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtmxyluuaf.html

[R01] shebang 与严格模式
来源：http://dali.zhiwuduotai.top/Article/details/gtbdinxpdy.html

#!/usr/bin/env bash
来源：http://dali.havefunace.top/Article/details/gtpzmaktjd.html

set -euo pipefail
来源：http://dali.bjfxy.top/Article/details/gtxtffxgzu.html

[R02] 变量赋值与使用
来源：http://dali.shzxlz.cn/Article/details/gtxmzaxfzp.html

name="Tom"; echo "$name"
来源：http://dali.feifeiyinyue.top/Article/details/gtzwrsqjoc.html

[R03] 只读变量
来源：http://dali.mhx1999.top/Article/details/gtwcwwxznz.html

readonly PI=3.14
来源：http://dali.hongshengwenyu.top/Article/details/gtvohswmuk.html

[R04] 位置参数
来源：http://dali.nanxuanxn.top/Article/details/gtsveobake.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.quarkkingdee.top/Article/details/gtlthbrgwz.html

[R05] 参数默认值
来源：http://dali.ehwqpu.com/Article/details/gtmslkvdpm.html

name="${1:-default}"
来源：http://dali.fzhhl.top/Article/details/gttgagyrly.html

[R06] 判断命令是否存在
来源：http://dali.zhengqikj.top/Article/details/gtaybiviaa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.guowangkeji.top/Article/details/gtpxgsxixs.html

[R07] if 判断文件
来源：http://dali.havefunace.top/Article/details/gtxbrttecf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.iojbl.cn/Article/details/gtapzngijv.html

[R08] 数值比较
来源：http://dali.hnxiangtu.top/Article/details/gtobnmbjok.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.bjfxy.top/Article/details/gtdsbihcxp.html

[R09] 字符串比较
来源：http://dali.vqdsnc.cn/Article/details/gtpwdqqmgj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtrwgdaqgb.html

[R10] 正则匹配
来源：http://dali.sysykeji.top/Article/details/gtvflzxxtw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gtmccksbid.html

[R11] case 多分支
来源：http://dali.fzhhl.top/Article/details/gtshwxwlsq.html

case "$1" in
来源：http://dali.bjfxy.top/Article/details/gtylplseky.html

start) echo "启动" ;;
来源：http://dali.316326.xyz/Article/details/gtthjhgleh.html

stop)  echo "停止" ;;
来源：http://dali.yuanzhike.top/Article/details/gtumzadmfx.html

*)     echo "未知命令" ;;
来源：http://dali.hywenlv.cn/Article/details/gtxlpqgwoo.html

esac
来源：http://dali.nanxinkj.top/Article/details/gtpnyxzlop.html

[R12] for 遍历文件
来源：http://dali.gotoacloud.top/Article/details/gtcxnegkxu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtcxlxmhxs.html

[R13] for 计数循环
来源：http://dali.xuetiantiany.cn/Article/details/gtpdzwxtpy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gtnivvrzib.html

[R14] C 风格 for
来源：http://dali.vqdsnc.cn/Article/details/gtovnusofu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.quarkkingdee.top/Article/details/gtfsbspazv.html

[R15] while 逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtbrypdjiq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.dashuyun.cn/Article/details/gtyknidzul.html

[R16] until 等待条件
来源：http://dali.sufxvd.cn/Article/details/gtdsqxfnvm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gtcowqubmc.html

[R17] 数组定义与取值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtzskbvu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yanxiufei.cn/Article/details/gtdjpsryhh.html

[R18] 遍历数组
来源：http://dali.sysykeji.top/Article/details/gtselnswnp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnxiangtu.top/Article/details/gtsxhcyxcu.html

[R19] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gtazbijcak.html

echo "${#arr[@]}"
来源：http://dali.aizwys.cn/Article/details/gtylzjykzx.html

[R20] 关联数组（字典）
来源：http://dali.yueranfly.top/Article/details/gtqalbxfsu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.andypj.xyz/Article/details/gtxmuvevck.html

[R21] 字符串长度
来源：http://dali.yj202588.top/Article/details/gtseqgivfr.html

echo "${#s}"
来源：http://dali.dashuyun.cn/Article/details/gtycerpvrx.html

[R22] 截取子串
来源：http://dali.iojbl.cn/Article/details/gtaogqqgme.html

echo "${s:0:5}"
来源：http://dali.shanyushiyangtech.top/Article/details/gttaegjytw.html

[R23] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gtdpjtbnwo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.mhx1999.top/Article/details/gtlbjvbmjg.html

[R24] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gtlxtqolxo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jiagoushi.top/Article/details/gtkveyjqwa.html

[R25] 去后缀 / 去前缀
来源：http://dali.9152youxi.cn/Article/details/gtfjynfmzb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhongyouzk.top/Article/details/gtfteipbvr.html

[R26] 命令替换
来源：http://dali.jinghuilouyu.cn/Article/details/gthsqdaevg.html

now=$(date +%F); echo "$now"
来源：http://dali.svipenyu.cn/Article/details/gtqurmobni.html

[R27] 算术展开
来源：http://dali.svipenyu.cn/Article/details/gtimhcvrat.html

echo $((1 + 2 * 3))
来源：http://dali.dianchejie.cn/Article/details/gtbeabgenq.html

[R28] 浮点运算
来源：http://dali.xuetiantiany.cn/Article/details/gtzjtgtafc.html

echo "scale=2; 10/3" | bc
来源：http://dali.yanxiufei.cn/Article/details/gterfoqtta.html

[R29] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gtsagiaorh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenjidiqi.icu/Article/details/gtnjpdshid.html

[R30] 函数返回状态码
来源：http://dali.chenjidiqi.icu/Article/details/gteigkalmk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yueranfly.top/Article/details/gtuqudwdav.html

[R31] 局部变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtarttps.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangdashe.top/Article/details/gtfbfrujpv.html

[R32] 参数个数校验
来源：http://dali.quarkkingdee.top/Article/details/gthtpfpnba.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.guowangkeji.top/Article/details/gtynwkkoan.html

[R33] 捕获错误并提示行号
来源：http://dali.hammf.cn/Article/details/gttkltevlp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fengsongda.top/Article/details/gteesqnjgu.html

[R34] 退出时清理
来源：http://dali.xuanzx.com/Article/details/gtwovmgseq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gtjnwvkgwr.html

[R35] 后台执行并等待
来源：http://dali.jinqigfzy.top/Article/details/gtxaismbep.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ppjwa.cn/Article/details/gtgpaxrasg.html

[R36] 并发执行多个任务
来源：http://dali.iojbl.cn/Article/details/gtbgkrmyit.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daria6918.cn/Article/details/gthfdbydwx.html

[R37] 把输出赋给变量
来源：http://dali.hfpthk.cn/Article/details/gtmvapzmnk.html

files=$(ls -1)
来源：http://dali.pycfn.com/Article/details/gtuxwtivpc.html

[R38] 管道串联
来源：http://dali.xylfe.cn/Article/details/gtyczivhyg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.pycfn.com/Article/details/gtxfuzddtq.html

[R39] 重定向标准输出与错误
来源：http://dali.ydzc1.top/Article/details/gtggymlhic.html

cmd > out.log 2>&1
来源：http://dali.yongpay.top/Article/details/gtmbtwoznj.html

[R40] 追加写日志
来源：http://dali.xinyue.icu/Article/details/gtokuzyvzg.html

echo "log" >> out.log
来源：http://dali.gzhubu.top/Article/details/gtpkfkpgnj.html

[R41] 丢弃输出
来源：http://dali.smart0.xyz/Article/details/gtczbhbkqq.html

cmd >/dev/null 2>&1
来源：http://dali.zhixingplan.top/Article/details/gtziwevnga.html

[R42] 输入重定向
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzznxhjkj.html

wc -l < a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtaukbatqe.html

[R43] 按名字查找文件
来源：http://dali.mhx1999.top/Article/details/gtrdpjtqvg.html


<!-- 参考信息 -->