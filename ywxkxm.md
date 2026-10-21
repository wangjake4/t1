代发 wailian999

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtpnweerdt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cdnleiting.top/Article/details/gtjvpdxofd.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtffgnyjeg.html

[Q01] 创建表
来源：http://dali.feifeiyinyue.top/Article/details/gtdaluozxl.html

CREATE TABLE users (
来源：http://dali.pycfn.com/Article/details/gtbtkckepm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuetiantiany.cn/Article/details/gtcbpikvpk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.guowangkeji.top/Article/details/gtkcjnvzqq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tian-w.cn/Article/details/gtpxjkmczt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yanxiufei.cn/Article/details/gtwianudyl.html

);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwccjqfvn.html

[Q02] 创建带外键的表
来源：http://dali.aizwys.cn/Article/details/gtnfpdgvre.html

CREATE TABLE orders (
来源：http://dali.guowangkeji.top/Article/details/gtkyrnwnhx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gtbvjzivwo.html

user_id INT NOT NULL,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfineivna.html

amount DECIMAL(10, 2),
来源：http://dali.316326.xyz/Article/details/gtzbdcbdth.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.svipenyu.cn/Article/details/gtcdunpnbb.html

);
来源：http://dali.sufxvd.cn/Article/details/gtkfsrhkoz.html

[Q03] 增加列
来源：http://dali.jinghuilouyu.cn/Article/details/gtzuwiecjk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gotoacloud.top/Article/details/gteeornvqi.html

[Q04] 修改列类型
来源：http://dali.ivvv.top/Article/details/gtihhhxirc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258.top/Article/details/gtxpknwxgx.html

[Q05] 重命名列
来源：http://dali.shuidangran.top/Article/details/gtjjwcqvdy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yuxming.cn/Article/details/gtmntiafxj.html

[Q06] 删除列
来源：http://dali.chenzaomai.com/Article/details/gtlibkeerm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cashguo.top/Article/details/gtrctigomy.html

[Q07] 删除表
来源：http://dali.tanke756.top/Article/details/gtzpzirjbs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gogol.net.cn/Article/details/gtdndqwwrk.html

[Q08] 创建普通索引
来源：http://dali.pengpengdd.cyou/Article/details/gtqzwrxltg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gtbnqalgbe.html

[Q09] 创建唯一索引
来源：http://dali.quarkkingdee.top/Article/details/gtjwwnuzfx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.0kj1m.cn/Article/details/gthhvnqasq.html

[Q10] 插入单行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskkttjlj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jiagoushi.top/Article/details/gtghyeyxqa.html

[Q11] 一次插入多行
来源：http://dali.fengsongda.top/Article/details/gtdwpuufdk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvuhgrbrw.html

[Q12] 插入后取自增 ID
来源：http://dali.ybcxt.top/Article/details/gttknkwxac.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.c1oappe.top/Article/details/gtzcdzbkxn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hywenlv.cn/Article/details/gtqucfwnoa.html

[Q13] 忽略重复插入
来源：http://dali.yangfankeji.com/Article/details/gtgifllfpd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gtrggqxeww.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnqzz.top/Article/details/gttpkfbcso.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhiwuduotai.top/Article/details/gtpbsrxfxn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hnxiangtu.top/Article/details/gtvnsjjwbw.html

[Q15] 查询全部
来源：http://dali.zhengqikj.top/Article/details/gtsiwoobcr.html

SELECT * FROM users;
来源：http://dali.ivvv.top/Article/details/gtmaprjilj.html

[Q16] 查询指定列
来源：http://dali.cucudq.cn/Article/details/gtajtawgsi.html

SELECT id, name FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtckjpqklg.html

[Q17] 条件查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnintikff.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daxiang520.top/Article/details/gtpzdfhjet.html

[Q18] 模糊匹配
来源：http://dali.yuxming.cn/Article/details/gtxmprapwg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.dianchejie.cn/Article/details/gtldktcqvw.html

[Q19] 范围查询
来源：http://dali.zycfv.cn/Article/details/gtiwekogjh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodoghvhc.html

[Q20] IN 列表
来源：http://dali.ybcxt.top/Article/details/gtnvzhcwbl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtdnjuceqn.html

[Q21] 空值判断
来源：http://dali.shuidangran.top/Article/details/gttbdpawfu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ppjwa.cn/Article/details/gtnwpasojq.html

[Q22] 排序
来源：http://dali.redwolf501.top/Article/details/gtmebiklyl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shzxlz.cn/Article/details/gtnpedfgzz.html

[Q23] 分页
来源：http://dali.feifeiyinyue.top/Article/details/gtqhlqkrdm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.svipenyu.cn/Article/details/gtsbdyigey.html

[Q24] 去重
来源：http://dali.aizwys.cn/Article/details/gtolbejoql.html

SELECT DISTINCT city FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtggwcpqty.html

[Q25] 只取前 N 条
来源：http://dali.jiagoushi.top/Article/details/gtyeyfeoer.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aibaodan.cn/Article/details/gtiwjzyyny.html

[Q26] 计数
来源：http://dali.pycfn.com/Article/details/gthzncuzvj.html

SELECT COUNT(*) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtblpbdkee.html

[Q27] 条件计数
来源：http://dali.zhengqikj.top/Article/details/gtbubatmdm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yueranfly.top/Article/details/gtvwrwueli.html

[Q28] 求和与平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimuetgjd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gteyrlcsth.html

[Q29] 最大最小值
来源：http://dali.daria6918.cn/Article/details/gtqzhoweca.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxsikmcum.html

[Q30] 分组统计
来源：http://dali.ppjwa.cn/Article/details/gtpgwocacp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gtjbzqyhtw.html

[Q31] 分组后过滤
来源：http://dali.kuanghao11.cn/Article/details/gtjkzijdpf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ybcxt.top/Article/details/gtkpdkapls.html

[Q32] 分组拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtbmvbhwvr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gttatcusiv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.guowangkeji.top/Article/details/gtacmoptmc.html

[Q33] 多列分组
来源：http://dali.xinyue.icu/Article/details/gtqtbcgvcf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivkivuxy.html

[Q34] 每组取第一条
来源：http://dali.xziqi.cn/Article/details/gtklnllolz.html

SELECT * FROM (
来源：http://dali.yangfankeji.com/Article/details/gtsdlqthoe.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmppjktj.html

) t WHERE rn = 1;
来源：http://dali.iojbl.cn/Article/details/gtlruhuptb.html

[Q35] 内连接
来源：http://dali.kuanghao11.cn/Article/details/gtrvdatasu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jyoumei.cn/Article/details/gtepezsifl.html

[Q36] 左连接
来源：http://dali.yj20258.top/Article/details/gthoiawjtn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtcitanrka.html

[Q37] 右连接
来源：http://dali.gotoacloud.top/Article/details/gtddtwgblc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nanxinkj.top/Article/details/gtnnzavnkk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.316326.xyz/Article/details/gtrfsqchoa.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zycfv.cn/Article/details/gtztqpdctm.html

[Q39] 自连接（查上下级）
来源：http://dali.cashguo.top/Article/details/gtomfufwbz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnxiangtu.top/Article/details/gtdqnhrfot.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.0kj1m.cn/Article/details/gtfbtddnkd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jqgfzy.top/Article/details/gtgpcqvvzr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfryzsabi.html

[Q41] 多表连接
来源：http://dali.xylfe.cn/Article/details/gtukiaervb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xinyue.icu/Article/details/gtphqqexvj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cheryme.top/Article/details/gtohtvmsoj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgkwvwuyv.html

[Q42] 连接条件附加过滤
来源：http://dali.jyoumei.cn/Article/details/gtniykqfxa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yangfankeji.com/Article/details/gtgwaymbhj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dianchejie.cn/Article/details/gtgkrneein.html

[Q43] 标量子查询
来源：http://dali.kuanghao11.cn/Article/details/gtccjhehvd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gotoacloud.top/Article/details/gtparqiqml.html

[Q44] IN 子查询
来源：http://dali.yuxming.cn/Article/details/gtynculype.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.fzhhl.top/Article/details/gtgtctepzx.html

[Q45] EXISTS 判断存在
来源：http://dali.wangdashe.top/Article/details/gtczoarnct.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gtdafyuool.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xziqi.cn/Article/details/gtkopujqqe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dashuyun.cn/Article/details/gtrspdkqpm.html

[Q47] 与平均值比较
来源：http://dali.guowangkeji.top/Article/details/gtkgiendmb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.vqdsnc.cn/Article/details/gtumvgibch.html

[Q48] CTE 公用表表达式
来源：http://dali.cashguo.top/Article/details/gtslzdmlyr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj20258888.top/Article/details/gthvkldrjf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nwbrower.top/Article/details/gtxsrqjltb.html

[Q49] 更新单行
来源：http://dali.cashguo.top/Article/details/gtqrzjfvtn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gzhubu.top/Article/details/gtadsfjrxz.html

[Q50] 批量更新
来源：http://dali.hnxiangtu.top/Article/details/gtxebsyvvr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gtgiumrezx.html

[Q51] 用子查询更新
来源：http://dali.xinyue.icu/Article/details/gtdvwirwqg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ppjwa.cn/Article/details/gttnhdcpte.html

[Q52] 删除指定行
来源：http://dali.xziqi.cn/Article/details/gtnekvjuyw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gtegycenns.html

[Q53] 按条件删除
来源：http://dali.guannengcc.top/Article/details/gtuzhzsjuy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yongpay.top/Article/details/gtihwbltqq.html

[Q54] 清空表
来源：http://dali.zdqjudy.top/Article/details/gtpjcfpoam.html

TRUNCATE TABLE logs;
来源：http://dali.xylfe.cn/Article/details/gtihwwmqpb.html

[Q55] 排名（并列占位）
来源：http://dali.mhx1999.top/Article/details/gtstjlkzbz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yvedp.cn/Article/details/gtdxofbdav.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbudbycl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gtugkfused.html

[Q57] 行号
来源：http://dali.snrcjt.cn/Article/details/gtnpdcnzmr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gtbjqbhjjb.html

[Q58] 累计求和
来源：http://dali.jqgfzy.top/Article/details/gtrsjlrkzp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqkptmga.html

[Q59] 分组内累计
来源：http://dali.aibaodan.cn/Article/details/gtossjygnv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtlqyewgdp.html

[Q60] 取上一行 / 下一行
来源：http://dali.hywenlv.cn/Article/details/gtoaoszaox.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yongpay.top/Article/details/gtuwbvmsbs.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtqzeivtzk.html

[Q61] 移动平均
来源：http://dali.ivvv.top/Article/details/gtlldaxvdv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtiyctomhl.html

[Q62] 分组占比
来源：http://dali.shanyushiyangtech.top/Article/details/gtysloxfjb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gtdgavsykd.html

[Q63] 开启事务
来源：http://dali.hysaishi.cn/Article/details/gtfpvbqhbs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigfzy.top/Article/details/gteoofbxrx.html

[Q64] 提交事务
来源：http://dali.jlsjyb.cn/Article/details/gtaxcabspc.html

COMMIT;
来源：http://dali.shzxlz.cn/Article/details/gtpyqjuayc.html

[Q65] 回滚事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtamppeujw.html

ROLLBACK;
来源：http://dali.dianchejie.cn/Article/details/gtaovuxqaf.html

[Q66] 行锁查询
来源：http://dali.chenjidiqi.icu/Article/details/gtyrbbbwga.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tianlin.xyz/Article/details/gtrblbctcb.html

[Q67] 设置隔离级别
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszbytgxa.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sxryk.cn/Article/details/gtrgsncmca.html

[Q68] 保存点
来源：http://dali.birdmap.top/Article/details/gtttnqcojj.html

SAVEPOINT sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonnqvzxo.html

ROLLBACK TO sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjizwchv.html

[Q69] 查看执行计划
来源：http://dali.aibaodan.cn/Article/details/gtxlrxjhql.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hfpthk.cn/Article/details/gtbozoewua.html

[Q70] 更新统计信息
来源：http://dali.yj202588.top/Article/details/gtpthztydj.html

ANALYZE TABLE users;
来源：http://dali.nanxinkj.top/Article/details/gtwembzjgk.html

[Q71] 查看建表语句
来源：http://dali.jiagoushi.top/Article/details/gtqufqkzxs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tian-w.cn/Article/details/gtogmqkjxa.html

[Q72] 查看索引
来源：http://dali.tanke756.top/Article/details/gtuvypgdbh.html

SHOW INDEX FROM users;
来源：http://dali.xylfe.cn/Article/details/gtsoaicawb.html

[Q73] 查看表状态
来源：http://dali.sweek.top/Article/details/gtckbulxku.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhengqikj.top/Article/details/gtedtngsfi.html

[Q74] 强制使用索引
来源：http://dali.shzxlz.cn/Article/details/gtmjbrqlnl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tian-w.cn/Article/details/gtkrxeznsw.html

[Q75] 日期格式化
来源：http://dali.cheryme.top/Article/details/gtiqhooidm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtqhobevtf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jianghu66.top/Article/details/gtgsfajxxu.html

[Q76] 按天统计
来源：http://dali.jinqigufen.top/Article/details/gtdveibewh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shuidangran.top/Article/details/gtewbraatz.html

[Q77] 时间加减
来源：http://dali.zdqjudy.top/Article/details/gtcgglwabf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.redwolf501.top/Article/details/gtmhpiczbj.html

[Q78] 当前时间
来源：http://dali.yj202588.top/Article/details/gtgzxtmssy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigfzy.top/Article/details/gtzqsweqsd.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gtqrppmfbd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hnxiangtu.top/Article/details/gteoibrbui.html

[Q80] 字符串截取
来源：http://dali.hnqzz.top/Article/details/gtoseuyhoq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtmownkzvq.html

[Q81] 字符串替换
来源：http://dali.gogol.net.cn/Article/details/gttxfctraj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtlvprivgs.html

[Q82] 字符长度与字节长度
来源：http://dali.jinqigufen.top/Article/details/gtmhiphjvm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvppjkqrw.html

[Q83] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gtdkuxbzgl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtyufyjppz.html

[Q84] 去除首尾空格
来源：http://dali.daria6918.cn/Article/details/gtershespb.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gtemymqpyz.html

[Q85] 数值取整
来源：http://dali.smart0.xyz/Article/details/gtzuyymura.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dianchejie.cn/Article/details/gtuvzbksqm.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmudsciw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dashuyun.cn/Article/details/gtgnfvcfma.html

[Q87] JSON 字段做条件
来源：http://dali.aibaodan.cn/Article/details/gteujmvdfd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.snrcjt.cn/Article/details/gtdbfqvhxq.html

[Q88] 行转列（条件聚合）
来源：http://dali.iojbl.cn/Article/details/gtsvzstuhm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.bjfxy.top/Article/details/gtohxevxlz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.andypj.xyz/Article/details/gterygljpt.html

[Q89] 判断表是否存在
来源：http://dali.aizwys.cn/Article/details/gtywnywdkp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.0kj1m.cn/Article/details/gtmkjbjvzq.html

[Q90] 生成序号列
来源：http://dali.guowangkeji.top/Article/details/gtimodhujd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nwbrower.top/Article/details/gtnztucghx.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtqjphdpno.html

R. Bash 专题
来源：http://dali.yj20258.top/Article/details/gtxdftfxmg.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtrdapqddu.html

[R01] shebang 与严格模式
来源：http://dali.cashguo.top/Article/details/gtnnmfnntr.html

#!/usr/bin/env bash
来源：http://dali.yanxiufei.cn/Article/details/gtxbrkexny.html

set -euo pipefail
来源：http://dali.yangfankeji.com/Article/details/gtmhjlejcb.html

[R02] 变量赋值与使用
来源：http://dali.yueranfly.top/Article/details/gtbvohhnae.html

name="Tom"; echo "$name"
来源：http://dali.shanyushiyangtech.top/Article/details/gtasjukjti.html

[R03] 只读变量
来源：http://dali.0kj1m.cn/Article/details/gtsxouhzwv.html

readonly PI=3.14
来源：http://dali.yj20258.top/Article/details/gtjqqglolr.html

[R04] 位置参数
来源：http://dali.chenlongwang.top/Article/details/gtvjbanpke.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pengpengdd.cyou/Article/details/gtxvuhdynd.html

[R05] 参数默认值
来源：http://dali.zycfv.cn/Article/details/gtaqqqagbw.html

name="${1:-default}"
来源：http://dali.gzhubu.top/Article/details/gtwdtuhlde.html

[R06] 判断命令是否存在
来源：http://dali.ydzc1.top/Article/details/gtymrmilkv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gtqsvecpld.html

[R07] if 判断文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgyboqbnc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ivvv.top/Article/details/gtclhiayga.html

[R08] 数值比较
来源：http://dali.jqgufenzy.top/Article/details/gtlobipogu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cheryme.top/Article/details/gtvjszdpfw.html

[R09] 字符串比较
来源：http://dali.quarkkingdee.top/Article/details/gtqmlqatra.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tanke756.top/Article/details/gtiwawufva.html

[R10] 正则匹配
来源：http://dali.yonumen.top/Article/details/gtbvcoyjsa.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenzaomai.com/Article/details/gtkbvaegbu.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gtoxbphqox.html

case "$1" in
来源：http://dali.ppjwa.cn/Article/details/gtxnxfhjhm.html

start) echo "启动" ;;
来源：http://dali.yangfankeji.com/Article/details/gtduajszfk.html

stop)  echo "停止" ;;
来源：http://dali.havefunace.top/Article/details/gteirmhlst.html

*)     echo "未知命令" ;;
来源：http://dali.dianchejie.cn/Article/details/gtqbhqqmbq.html

esac
来源：http://dali.guannengcc.top/Article/details/gtndleslej.html

[R12] for 遍历文件
来源：http://dali.gaohongyu789.top/Article/details/gtvhkzntlc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.daxiang520.top/Article/details/gtsvhoxprr.html

[R13] for 计数循环
来源：http://dali.shuidangran.top/Article/details/gtuixwsbwt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hnqzz.top/Article/details/gtgbtbikfp.html

[R14] C 风格 for
来源：http://dali.jlsjyb.cn/Article/details/gtarwhzqqd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gtrepnzges.html

[R15] while 逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gtxfrwvjaa.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hnqzz.top/Article/details/gtyohazvrb.html

[R16] until 等待条件
来源：http://dali.chenjidiqi.icu/Article/details/gtixkuantc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gtseihfkdo.html

[R17] 数组定义与取值
来源：http://dali.chenlongwang.top/Article/details/gtajehupsi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sufxvd.cn/Article/details/gtnvxcmbti.html

[R18] 遍历数组
来源：http://dali.zhengqikj.top/Article/details/gtldwlsozs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shuidangran.top/Article/details/gtwtromgoi.html

[R19] 数组长度
来源：http://dali.tian-w.cn/Article/details/gttudgfshp.html

echo "${#arr[@]}"
来源：http://dali.jlsjyb.cn/Article/details/gtfkjqecog.html

[R20] 关联数组（字典）
来源：http://dali.sweek.top/Article/details/gtbyqcxyhg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtenkajaob.html

[R21] 字符串长度
来源：http://dali.smart0.xyz/Article/details/gtckfishqg.html

echo "${#s}"
来源：http://dali.yangfankeji.com/Article/details/gtguykgzxg.html

[R22] 截取子串
来源：http://dali.wangdashe.top/Article/details/gtaehnlrlh.html

echo "${s:0:5}"
来源：http://dali.yueranfly.top/Article/details/gtbenlgxqa.html

[R23] 字符串替换
来源：http://dali.sysykeji.top/Article/details/gtujsxblpq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tanke756.top/Article/details/gtohtdxowr.html

[R24] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gtkfdnwfrj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.svipenyu.cn/Article/details/gtzgftwsda.html

[R25] 去后缀 / 去前缀
来源：http://dali.wangdashe.top/Article/details/gtyxxdlqle.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xziqi.cn/Article/details/gtsycgmwgi.html

[R26] 命令替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzttuapm.html

now=$(date +%F); echo "$now"
来源：http://dali.nanxuanxn.top/Article/details/gtkbphtrxv.html

[R27] 算术展开
来源：http://dali.havefunace.top/Article/details/gtfnvxpicq.html

echo $((1 + 2 * 3))
来源：http://dali.zhongyouzk.top/Article/details/gtokrfquiq.html

[R28] 浮点运算
来源：http://dali.xuanzx.com/Article/details/gthvysijgv.html

echo "scale=2; 10/3" | bc
来源：http://dali.0kj1m.cn/Article/details/gtqkqbcdbs.html

[R29] 定义函数
来源：http://dali.aizwys.cn/Article/details/gtomynzjvm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gzhubu.top/Article/details/gtiinuwqch.html

[R30] 函数返回状态码
来源：http://dali.zycfv.cn/Article/details/gtqbehbjza.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.smart0.xyz/Article/details/gtydriupzp.html

[R31] 局部变量
来源：http://dali.fengsongda.top/Article/details/gtcokvxfeg.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenzaomai.com/Article/details/gtzxzuxpuo.html

[R32] 参数个数校验
来源：http://dali.aibaodan.cn/Article/details/gttvjejomr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.guowangkeji.top/Article/details/gtxwwugchv.html

[R33] 捕获错误并提示行号
来源：http://dali.dashuyun.cn/Article/details/gtdmoemvhk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yanxiufei.cn/Article/details/gtfjeepets.html

[R34] 退出时清理
来源：http://dali.yangfankeji.com/Article/details/gtubvqfzlq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gtqjwlckrq.html

[R35] 后台执行并等待
来源：http://dali.daria6918.cn/Article/details/gtxxdkmkfg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xuanzx.com/Article/details/gtzckhigxq.html

[R36] 并发执行多个任务
来源：http://dali.yuxming.cn/Article/details/gtpkxqxfax.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ydzc1.top/Article/details/gtsjasouni.html

[R37] 把输出赋给变量
来源：http://dali.andypj.xyz/Article/details/gtzdvyrnbg.html

files=$(ls -1)
来源：http://dali.ppjwa.cn/Article/details/gtrjbzonqd.html

[R38] 管道串联
来源：http://dali.ydzc1.top/Article/details/gthoiervus.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yonumen.top/Article/details/gtzbmvvoyd.html

[R39] 重定向标准输出与错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsudjqpta.html

cmd > out.log 2>&1
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgcxylyj.html

[R40] 追加写日志
来源：http://dali.jinqigufen.top/Article/details/gtflvuvjsk.html

echo "log" >> out.log
来源：http://dali.gzhubu.top/Article/details/gtjuxzfxfp.html

[R41] 丢弃输出
来源：http://dali.yj202588.top/Article/details/gtbgdtrung.html

cmd >/dev/null 2>&1
来源：http://dali.shzxlz.cn/Article/details/gtwvkgzwrw.html

[R42] 输入重定向
来源：http://dali.cheryme.top/Article/details/gtrhxfqkut.html

wc -l < a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gttgqrhmkb.html

[R43] 按名字查找文件
来源：http://dali.hnqzz.top/Article/details/gtxsgqoaip.html


<!-- 参考信息 -->