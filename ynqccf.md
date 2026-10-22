代发 wailian999

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtbwhjwwmz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.quarkkingdee.top/Article/details/gtxpzresfd.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtdpofejcv.html

[Q01] 创建表
来源：http://dali.haohaochexian.top/Article/details/gttfcgbgpj.html

CREATE TABLE users (
来源：http://dali.zhixingplan.top/Article/details/gtfhgqzqqn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfobrkmaa.html

name VARCHAR(50) NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gtwbipzqob.html

email VARCHAR(100) UNIQUE,
来源：http://dali.daria6918.cn/Article/details/gtwztycmvg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.aizwys.cn/Article/details/gtmxurdmld.html

);
来源：http://dali.yongpay.top/Article/details/gtpjeeexzr.html

[Q02] 创建带外键的表
来源：http://dali.sxryk.cn/Article/details/gthvttdmpn.html

CREATE TABLE orders (
来源：http://dali.wangshuangyany.cn/Article/details/gtwkdrlhxa.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.c1oappe.top/Article/details/gtazwbvclq.html

user_id INT NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gtqezkczdf.html

amount DECIMAL(10, 2),
来源：http://dali.quarkkingdee.top/Article/details/gtctnnanmn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yangfankeji.com/Article/details/gtjtithiqg.html

);
来源：http://dali.nanxuanxn.top/Article/details/gtkelocbdy.html

[Q03] 增加列
来源：http://dali.birdmap.top/Article/details/gthwpgkckx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hammf.cn/Article/details/gtnmzfbxmk.html

[Q04] 修改列类型
来源：http://dali.xylfe.cn/Article/details/gtetxorncl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nwbrower.top/Article/details/gtpxqvnirb.html

[Q05] 重命名列
来源：http://dali.hnqzz.top/Article/details/gtqgnjsoas.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hywenlv.cn/Article/details/gtgqnvigdp.html

[Q06] 删除列
来源：http://dali.jqgfzy.top/Article/details/gtxttmizdx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ppjwa.cn/Article/details/gtyctktdes.html

[Q07] 删除表
来源：http://dali.hfpthk.cn/Article/details/gtmblebbnq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.dianchejie.cn/Article/details/gtcicgwvjz.html

[Q08] 创建普通索引
来源：http://dali.feifeiyinyue.top/Article/details/gtrtbzipzl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gzhubu.top/Article/details/gtpvyhyirm.html

[Q09] 创建唯一索引
来源：http://dali.feifeiyinyue.top/Article/details/gtwjhybhcp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.haohaochexian.top/Article/details/gtqqzlardq.html

[Q10] 插入单行
来源：http://dali.jiagoushi.top/Article/details/gtsfpbxrdj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zdqjudy.top/Article/details/gthvkmxmen.html

[Q11] 一次插入多行
来源：http://dali.birdmap.top/Article/details/gtyqxgfsdd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tian-w.cn/Article/details/gtuzoogcps.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangkeji.top/Article/details/gthnqvpkoe.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gtixyvauto.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.feifeiyinyue.top/Article/details/gtzeusxgwx.html

[Q13] 忽略重复插入
来源：http://dali.xuetiantiany.cn/Article/details/gtpzljyxqq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.snrcjt.cn/Article/details/gtqzqbfwwn.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhixingplan.top/Article/details/gtsucpfypu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ybcxt.top/Article/details/gtcdfycibl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gotoacloud.top/Article/details/gtlmzxbjin.html

[Q15] 查询全部
来源：http://dali.guowangkeji.top/Article/details/gtqcxtgqjf.html

SELECT * FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtddxfhdww.html

[Q16] 查询指定列
来源：http://dali.mhx1999.top/Article/details/gtqgmoyhmc.html

SELECT id, name FROM users;
来源：http://dali.birdmap.top/Article/details/gtzlpuxrsr.html

[Q17] 条件查询
来源：http://dali.chenzaomai.com/Article/details/gthkfhbjik.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.wangdashe.top/Article/details/gtwuingoju.html

[Q18] 模糊匹配
来源：http://dali.cashguo.top/Article/details/gtinkxuzlr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnxiangtu.top/Article/details/gtwockhlnp.html

[Q19] 范围查询
来源：http://dali.gotoacloud.top/Article/details/gtydgdmgzz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hysaishi.cn/Article/details/gtgcsswflu.html

[Q20] IN 列表
来源：http://dali.cheryme.top/Article/details/gtqlrflrwl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenlongwang.top/Article/details/gtfrhpjlmv.html

[Q21] 空值判断
来源：http://dali.shuidangran.top/Article/details/gtzhwnnnfq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ydzc1.top/Article/details/gtptbowpxi.html

[Q22] 排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoyyrufih.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gaohongyu789.top/Article/details/gtvebvmvzp.html

[Q23] 分页
来源：http://dali.hfpthk.cn/Article/details/gtxhorrolq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.haohaochexian.top/Article/details/gtvprbnpdy.html

[Q24] 去重
来源：http://dali.smart0.xyz/Article/details/gtxlyokxhv.html

SELECT DISTINCT city FROM users;
来源：http://dali.hnqzz.top/Article/details/gtlngzjutt.html

[Q25] 只取前 N 条
来源：http://dali.xylfe.cn/Article/details/gtjxjzjehg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nanxuanxn.top/Article/details/gtkhpyexrb.html

[Q26] 计数
来源：http://dali.yj202588.top/Article/details/gtkazzrjcl.html

SELECT COUNT(*) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtnpillmcp.html

[Q27] 条件计数
来源：http://dali.hfpthk.cn/Article/details/gtmbxqegmu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtvedairlk.html

[Q28] 求和与平均
来源：http://dali.yanxiufei.cn/Article/details/gtdpjqpwvf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtiqopywag.html

[Q29] 最大最小值
来源：http://dali.jqgufenzy.top/Article/details/gtqxjftkdf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtdkaqnyxc.html

[Q30] 分组统计
来源：http://dali.316326.xyz/Article/details/gtwulaojvm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gtfettishv.html

[Q31] 分组后过滤
来源：http://dali.zhixingplan.top/Article/details/gtqpdxfkhi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zycfv.cn/Article/details/gtnidqetzg.html

[Q32] 分组拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtnnzfqwur.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gtnshlaspm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jyoumei.cn/Article/details/gtnzudakxh.html

[Q33] 多列分组
来源：http://dali.gotoacloud.top/Article/details/gtywmilffn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zdqjudy.top/Article/details/gtigbnzuea.html

[Q34] 每组取第一条
来源：http://dali.hysaishi.cn/Article/details/gtytcqpxrr.html

SELECT * FROM (
来源：http://dali.hongshengwenyu.top/Article/details/gteterxvwl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fengsongda.top/Article/details/gtfqkgclwn.html

) t WHERE rn = 1;
来源：http://dali.yongpay.top/Article/details/gtcubheous.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gtkdlrzocx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.pycfn.com/Article/details/gtmyaitvqb.html

[Q36] 左连接
来源：http://dali.zycfv.cn/Article/details/gtwypukfzm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gtmulskpqy.html

[Q37] 右连接
来源：http://dali.pengpengdd.cyou/Article/details/gtymkjyvwh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.wangshuangyany.cn/Article/details/gthfpchycw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cqqwz.cn/Article/details/gtshoofwqk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.kuanghao11.cn/Article/details/gtquqcsbyl.html

[Q39] 自连接（查上下级）
来源：http://dali.tanke756.top/Article/details/gtqrajjnqg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgufenzy.top/Article/details/gtlmlqzfuw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ydzc1.top/Article/details/gtndfgkmlu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.fzhhl.top/Article/details/gtblfoomjo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yj202588.top/Article/details/gtnhnbcuco.html

[Q41] 多表连接
来源：http://dali.yj20258888.top/Article/details/gtdwtngghi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.svipenyu.cn/Article/details/gtnmyeicon.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xuanzx.com/Article/details/gtbrxxzbme.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.havefunace.top/Article/details/gtrfjuvxrq.html

[Q42] 连接条件附加过滤
来源：http://dali.c1oappe.top/Article/details/gtviwstscu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ppjwa.cn/Article/details/gtuhzjtxbr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenzaomai.com/Article/details/gtyupmswiz.html

[Q43] 标量子查询
来源：http://dali.wangshuangyany.cn/Article/details/gtoobdvgym.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigufen.top/Article/details/gtwdmgxpsi.html

[Q44] IN 子查询
来源：http://dali.kuanghao11.cn/Article/details/gtfedpvtre.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hysaishi.cn/Article/details/gtahezrcvz.html

[Q45] EXISTS 判断存在
来源：http://dali.andypj.xyz/Article/details/gtxfedlyvs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gzhubu.top/Article/details/gtqsmiulpa.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yvedp.cn/Article/details/gtjamqtkul.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cheryme.top/Article/details/gtxkaaocbn.html

[Q47] 与平均值比较
来源：http://dali.yj20258888.top/Article/details/gtlrvvofol.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.haohaochexian.top/Article/details/gtzlutkuqm.html

[Q48] CTE 公用表表达式
来源：http://dali.yueranfly.top/Article/details/gtrgysducs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hysaishi.cn/Article/details/gtvnfftosx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjjvdxmq.html

[Q49] 更新单行
来源：http://dali.cashguo.top/Article/details/gtnlnmtuvv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gtprzrzbwx.html

[Q50] 批量更新
来源：http://dali.yj20258.top/Article/details/gtzcypeubf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daxiang520.top/Article/details/gttospsolq.html

[Q51] 用子查询更新
来源：http://dali.nwbrower.top/Article/details/gttqxbomwn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.9152youxi.cn/Article/details/gtidpvcosh.html

[Q52] 删除指定行
来源：http://dali.shuidangran.top/Article/details/gtmeubyczn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtvoimduih.html

[Q53] 按条件删除
来源：http://dali.sxryk.cn/Article/details/gtqrkiquvf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dianchejie.cn/Article/details/gtgdldlfls.html

[Q54] 清空表
来源：http://dali.jinghuilouyu.cn/Article/details/gtejcjbnwo.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gtngxsctai.html

[Q55] 排名（并列占位）
来源：http://dali.gaohongyu789.top/Article/details/gtbnsoneim.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sweek.top/Article/details/gtbhhnvgcq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuanzx.com/Article/details/gtthoxlgrl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jiagoushi.top/Article/details/gthaaikpao.html

[Q57] 行号
来源：http://dali.tanke756.top/Article/details/gtnosllxyn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtbxelpvlf.html

[Q58] 累计求和
来源：http://dali.snrcjt.cn/Article/details/gtipteiofa.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtirenflnq.html

[Q59] 分组内累计
来源：http://dali.jlsjyb.cn/Article/details/gtfqihzhlv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtzvznolgf.html

[Q60] 取上一行 / 下一行
来源：http://dali.jianghu66.top/Article/details/gtbvpddvwe.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhengqikj.top/Article/details/gtsxjnoilc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtwuffdktm.html

[Q61] 移动平均
来源：http://dali.svipenyu.cn/Article/details/gtjwsohrpp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtymspkole.html

[Q62] 分组占比
来源：http://dali.cashguo.top/Article/details/gtdnycojgm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gtlkfaxikc.html

[Q63] 开启事务
来源：http://dali.hfpthk.cn/Article/details/gtexquowpq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgufenzy.top/Article/details/gtkpasujwx.html

[Q64] 提交事务
来源：http://dali.tian-w.cn/Article/details/gtwyozkeqv.html

COMMIT;
来源：http://dali.jiagoushi.top/Article/details/gtyskcdesx.html

[Q65] 回滚事务
来源：http://dali.wangshuangyany.cn/Article/details/gttjssdcyo.html

ROLLBACK;
来源：http://dali.jyoumei.cn/Article/details/gtwelrqnqb.html

[Q66] 行锁查询
来源：http://dali.jiagoushi.top/Article/details/gtsumxwjhp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnqzz.top/Article/details/gtpsjtflks.html

[Q67] 设置隔离级别
来源：http://dali.nwbrower.top/Article/details/gtoktsmmjl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xylfe.cn/Article/details/gtiwmfdwwv.html

[Q68] 保存点
来源：http://dali.jqgfzy.top/Article/details/gtluhlgxia.html

SAVEPOINT sp1;
来源：http://dali.xuetiantiany.cn/Article/details/gtplyihhna.html

ROLLBACK TO sp1;
来源：http://dali.xinyue.icu/Article/details/gttglqijbt.html

[Q69] 查看执行计划
来源：http://dali.daria6918.cn/Article/details/gtsdvaplfg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.vqdsnc.cn/Article/details/gtkrwejmpy.html

[Q70] 更新统计信息
来源：http://dali.hfpthk.cn/Article/details/gtycveygcv.html

ANALYZE TABLE users;
来源：http://dali.feifeiyinyue.top/Article/details/gthbtspgkn.html

[Q71] 查看建表语句
来源：http://dali.smart0.xyz/Article/details/gtosauqqti.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhiwuduotai.top/Article/details/gtrpwkxdwj.html

[Q72] 查看索引
来源：http://dali.wangdashe.top/Article/details/gtewjbqdej.html

SHOW INDEX FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrkrxlxk.html

[Q73] 查看表状态
来源：http://dali.zdqjudy.top/Article/details/gtefairade.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yongpay.top/Article/details/gteazqqkhn.html

[Q74] 强制使用索引
来源：http://dali.fzhhl.top/Article/details/gtqmhqpzpw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tian-w.cn/Article/details/gtqyubgvth.html

[Q75] 日期格式化
来源：http://dali.zhoulong.xyz/Article/details/gttdlewahf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gteqvytwpb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aibaodan.cn/Article/details/gtqzvjhlii.html

[Q76] 按天统计
来源：http://dali.vqdsnc.cn/Article/details/gtysqrqdpl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gotoacloud.top/Article/details/gttpufluiy.html

[Q77] 时间加减
来源：http://dali.hfpthk.cn/Article/details/gtlqlmbgrz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj20258888.top/Article/details/gtaqhcnqcm.html

[Q78] 当前时间
来源：http://dali.ydzc1.top/Article/details/gtuvtwpusb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gteoysvrot.html

[Q79] 字符串拼接
来源：http://dali.hysaishi.cn/Article/details/gtbghysbaf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhoulong.xyz/Article/details/gthdmyswcg.html

[Q80] 字符串截取
来源：http://dali.fengsongda.top/Article/details/gtssogyzfc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj20258.top/Article/details/gthbfmalkg.html

[Q81] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gtvupkxcqp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtqgbwzbck.html

[Q82] 字符长度与字节长度
来源：http://dali.ehwqpu.com/Article/details/gteutlbzqz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtxdnzcwlh.html

[Q83] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gtvwjsmmfr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gttkdtobyw.html

[Q84] 去除首尾空格
来源：http://dali.nanxinkj.top/Article/details/gtxwgusnak.html

SELECT TRIM(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtehalhwdt.html

[Q85] 数值取整
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqzvpvpk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xylfe.cn/Article/details/gtoqgvvols.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258.top/Article/details/gtwwkbvdwm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yanxiufei.cn/Article/details/gtjfgxorno.html

[Q87] JSON 字段做条件
来源：http://dali.zhixingplan.top/Article/details/gttisidgxp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.0kj1m.cn/Article/details/gtbtbfpqct.html

[Q88] 行转列（条件聚合）
来源：http://dali.gzhubu.top/Article/details/gtkfhyomlr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenzaomai.com/Article/details/gtgcjozonw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtixnlgmtk.html

[Q89] 判断表是否存在
来源：http://dali.vqdsnc.cn/Article/details/gtzfpyypdj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gaohongyu789.top/Article/details/gtgdwfwmzu.html

[Q90] 生成序号列
来源：http://dali.hywenlv.cn/Article/details/gtnlbkwsao.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvrjhtsv.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtbvkvxbwj.html

R. Bash 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdaljemf.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtsqunryum.html

[R01] shebang 与严格模式
来源：http://dali.chenlongwang.top/Article/details/gtivdeomnx.html

#!/usr/bin/env bash
来源：http://dali.zdqjudy.top/Article/details/gtmtrcyawe.html

set -euo pipefail
来源：http://dali.zycfv.cn/Article/details/gtnnkyenii.html

[R02] 变量赋值与使用
来源：http://dali.daxiang520.top/Article/details/gtrntezzdc.html

name="Tom"; echo "$name"
来源：http://dali.jinghuilouyu.cn/Article/details/gtvufetjec.html

[R03] 只读变量
来源：http://dali.zdqjudy.top/Article/details/gtbauoklae.html

readonly PI=3.14
来源：http://dali.wangdashe.top/Article/details/gtbdztoxou.html

[R04] 位置参数
来源：http://dali.quarkkingdee.top/Article/details/gtrptutvwr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.havefunace.top/Article/details/gtcpomzmus.html

[R05] 参数默认值
来源：http://dali.bjfxy.top/Article/details/gtgewxqqkj.html

name="${1:-default}"
来源：http://dali.nanxinkj.top/Article/details/gtanqymqwn.html

[R06] 判断命令是否存在
来源：http://dali.zhongyouzk.top/Article/details/gthwxagzov.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenzaomai.com/Article/details/gtieemuooc.html

[R07] if 判断文件
来源：http://dali.zhixingplan.top/Article/details/gtbljttncb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cdnleiting.top/Article/details/gtijyzjuta.html

[R08] 数值比较
来源：http://dali.zhiwuduotai.top/Article/details/gtviffbcvb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daria6918.cn/Article/details/gtqbhclmzs.html

[R09] 字符串比较
来源：http://dali.yonumen.top/Article/details/gtycocmoco.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ivvv.top/Article/details/gtkazgksbd.html

[R10] 正则匹配
来源：http://dali.sysykeji.top/Article/details/gttsbucxhj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtdaqrgmmc.html

[R11] case 多分支
来源：http://dali.tianlin.xyz/Article/details/gtfvphojat.html

case "$1" in
来源：http://dali.tian-w.cn/Article/details/gteqzwgjif.html

start) echo "启动" ;;
来源：http://dali.dashuyun.cn/Article/details/gtitjihcux.html

stop)  echo "停止" ;;
来源：http://dali.sweek.top/Article/details/gtdjqjoujs.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gtttrtlbow.html

esac
来源：http://dali.9152youxi.cn/Article/details/gtvalvbkmj.html

[R12] for 遍历文件
来源：http://dali.chenzaomai.com/Article/details/gtyyxdaper.html

for f in *.txt; do echo "$f"; done
来源：http://dali.dashuyun.cn/Article/details/gtbqwgtewv.html

[R13] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gtwwutuyzz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtxdlfnpsw.html

[R14] C 风格 for
来源：http://dali.gotoacloud.top/Article/details/gtxzvwuwef.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gtnqmhlwie.html

[R15] while 逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtmxywtdsb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xuanzx.com/Article/details/gtkgcrshaq.html

[R16] until 等待条件
来源：http://dali.xuanzx.com/Article/details/gtfnwuxhhe.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gtyhzpszyl.html

[R17] 数组定义与取值
来源：http://dali.birdmap.top/Article/details/gtpbuantsx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.smart0.xyz/Article/details/gtopkqpdjc.html

[R18] 遍历数组
来源：http://dali.tianlin.xyz/Article/details/gtkdvznsru.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.vqdsnc.cn/Article/details/gtjbrgduhz.html

[R19] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gtooufwwsy.html

echo "${#arr[@]}"
来源：http://dali.zycfv.cn/Article/details/gtbzzlkaut.html

[R20] 关联数组（字典）
来源：http://dali.mhx1999.top/Article/details/gthxpjvtwy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcymgzhwg.html

[R21] 字符串长度
来源：http://dali.smart0.xyz/Article/details/gtpdacaskm.html

echo "${#s}"
来源：http://dali.cashguo.top/Article/details/gtqlxzrptp.html

[R22] 截取子串
来源：http://dali.guannengcc.top/Article/details/gtufvxynlb.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gtqmkyaaah.html

[R23] 字符串替换
来源：http://dali.fzhhl.top/Article/details/gtrhryuaix.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.havefunace.top/Article/details/gtnturoata.html

[R24] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gtrivybkej.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gaohongyu789.top/Article/details/gtchbhsktg.html

[R25] 去后缀 / 去前缀
来源：http://dali.ydzc1.top/Article/details/gtihgycnnn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.fengsongda.top/Article/details/gtjtuvoijc.html

[R26] 命令替换
来源：http://dali.hongshengwenyu.top/Article/details/gtenicgwki.html

now=$(date +%F); echo "$now"
来源：http://dali.sweek.top/Article/details/gtcdhoiova.html

[R27] 算术展开
来源：http://dali.andypj.xyz/Article/details/gtmpsllipd.html

echo $((1 + 2 * 3))
来源：http://dali.jlsjyb.cn/Article/details/gtdonlewvc.html

[R28] 浮点运算
来源：http://dali.gotoacloud.top/Article/details/gthcuorohk.html

echo "scale=2; 10/3" | bc
来源：http://dali.svipenyu.cn/Article/details/gtmdkkmywi.html

[R29] 定义函数
来源：http://dali.sweek.top/Article/details/gtddchonuw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shzxlz.cn/Article/details/gtfggrgjhc.html

[R30] 函数返回状态码
来源：http://dali.9152youxi.cn/Article/details/gtxelzeghl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.aibaodan.cn/Article/details/gtzkjykkot.html

[R31] 局部变量
来源：http://dali.xinyue.icu/Article/details/gtromhvigr.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gtkwspjwxg.html

[R32] 参数个数校验
来源：http://dali.yanxiufei.cn/Article/details/gteqmqszzb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gogol.net.cn/Article/details/gtsiddjefm.html

[R33] 捕获错误并提示行号
来源：http://dali.daxiang520.top/Article/details/gtlsabzgdd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.birdmap.top/Article/details/gtoknvfrou.html

[R34] 退出时清理
来源：http://dali.nanxuanxn.top/Article/details/gtrknypqoo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gtqpxxhjfa.html

[R35] 后台执行并等待
来源：http://dali.redwolf501.top/Article/details/gtoghtoauw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjtnrbzk.html

[R36] 并发执行多个任务
来源：http://dali.hysaishi.cn/Article/details/gtkdspubwj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnxiangtu.top/Article/details/gtzktmlqrz.html

[R37] 把输出赋给变量
来源：http://dali.yvedp.cn/Article/details/gtstiwtmtn.html

files=$(ls -1)
来源：http://dali.zhongyouzk.top/Article/details/gtxmecprgc.html

[R38] 管道串联
来源：http://dali.cheryme.top/Article/details/gtvyuuhehe.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ydzc1.top/Article/details/gtdrbfluig.html

[R39] 重定向标准输出与错误
来源：http://dali.hammf.cn/Article/details/gtvcdlzaun.html

cmd > out.log 2>&1
来源：http://dali.zdqjudy.top/Article/details/gtponcaips.html

[R40] 追加写日志
来源：http://dali.sxryk.cn/Article/details/gtbuabozcz.html

echo "log" >> out.log
来源：http://dali.guannengcc.top/Article/details/gtucxnqxdi.html

[R41] 丢弃输出
来源：http://dali.gogol.net.cn/Article/details/gtgfqioqrp.html

cmd >/dev/null 2>&1
来源：http://dali.aizwys.cn/Article/details/gtkedpftia.html

[R42] 输入重定向
来源：http://dali.hysaishi.cn/Article/details/gtxfnhhncf.html

wc -l < a.txt
来源：http://dali.aizwys.cn/Article/details/gttnbrykgf.html

[R43] 按名字查找文件
来源：http://dali.tian-w.cn/Article/details/gtdhnqzfob.html


<!-- 参考信息 -->