代发 wailian999

CREATE TABLE users (
来源：http://dali.xuanzx.com/Article/details/gtsaxfeebm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenlongwang.top/Article/details/gtscoudeli.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gtpvnxdbti.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenlongwang.top/Article/details/gttnujefji.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yongpay.top/Article/details/gthuapetnt.html

);
来源：http://dali.iojbl.cn/Article/details/gtyiplkvfj.html

[Q02] 创建带外键的表
来源：http://dali.tian-w.cn/Article/details/gtpcyfpbuq.html

CREATE TABLE orders (
来源：http://dali.yvedp.cn/Article/details/gtiadsnnhg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gttymtrvho.html

user_id INT NOT NULL,
来源：http://dali.shanyushiyangtech.top/Article/details/gtxyaglncg.html

amount DECIMAL(10, 2),
来源：http://dali.shangyingyoupin.top/Article/details/gtineruith.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.fengsongda.top/Article/details/gtkcdkswda.html

);
来源：http://dali.svipenyu.cn/Article/details/gtmihstysa.html

[Q03] 增加列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpysmlcb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nwbrower.top/Article/details/gtfpyxqkqc.html

[Q04] 修改列类型
来源：http://dali.chenjidiqi.icu/Article/details/gtfvgjmxeg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gtstnmwfse.html

[Q05] 重命名列
来源：http://dali.yongpay.top/Article/details/gtokugkbcb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yj202588.top/Article/details/gtaxhlrdfw.html

[Q06] 删除列
来源：http://dali.yj20258.top/Article/details/gttnewlndn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.aizwys.cn/Article/details/gtvuevueqq.html

[Q07] 删除表
来源：http://dali.redwolf501.top/Article/details/gtnbkjbxmn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.fzhhl.top/Article/details/gtujpimges.html

[Q08] 创建普通索引
来源：http://dali.sweek.top/Article/details/gtkpnvrfkz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzykmryr.html

[Q09] 创建唯一索引
来源：http://dali.xuanzx.com/Article/details/gtsnilcmny.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.wangshuangyany.cn/Article/details/gtggcrcrhk.html

[Q10] 插入单行
来源：http://dali.yuanzhike.top/Article/details/gtwmgazlcd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvrslklq.html

[Q11] 一次插入多行
来源：http://dali.hnxiangtu.top/Article/details/gtdunhyjps.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbcxxwrpm.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258888.top/Article/details/gtmnooktxf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sysykeji.top/Article/details/gtktikpjcn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hammf.cn/Article/details/gtzbavrizx.html

[Q13] 忽略重复插入
来源：http://dali.gotoacloud.top/Article/details/gthagsbmyq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shzxlz.cn/Article/details/gtlmiswfqa.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuetiantiany.cn/Article/details/gtllqbzctj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gotoacloud.top/Article/details/gtottuuqcd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.svipenyu.cn/Article/details/gtdvsynepz.html

[Q15] 查询全部
来源：http://dali.zhongyouzk.top/Article/details/gtdfqgqymz.html

SELECT * FROM users;
来源：http://dali.daria6918.cn/Article/details/gtgrnmmudf.html

[Q16] 查询指定列
来源：http://dali.xinyue.icu/Article/details/gtoohmghcv.html

SELECT id, name FROM users;
来源：http://dali.ydzc1.top/Article/details/gtjwupdfvb.html

[Q17] 条件查询
来源：http://dali.ppjwa.cn/Article/details/gtllqcwbqh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fzhhl.top/Article/details/gttbiwalpn.html

[Q18] 模糊匹配
来源：http://dali.9152youxi.cn/Article/details/gtxmqnpsih.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj20258888.top/Article/details/gtwvnxqktw.html

[Q19] 范围查询
来源：http://dali.cqqwz.cn/Article/details/gtkkgqwomz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.dashuyun.cn/Article/details/gtatimfyxv.html

[Q20] IN 列表
来源：http://dali.yj20258888.top/Article/details/gtsooizosx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gotoacloud.top/Article/details/gtukskfzho.html

[Q21] 空值判断
来源：http://dali.fengsongda.top/Article/details/gtmdrihasw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zycfv.cn/Article/details/gtmengfygk.html

[Q22] 排序
来源：http://dali.hnqzz.top/Article/details/gtjadpabyo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yanxiufei.cn/Article/details/gtxuwdlyhk.html

[Q23] 分页
来源：http://dali.jlsjyb.cn/Article/details/gtfmjjjrir.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nanxuanxn.top/Article/details/gtrolbpmek.html

[Q24] 去重
来源：http://dali.jiagoushi.top/Article/details/gtjzxaeqzr.html

SELECT DISTINCT city FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtkmuxjsqw.html

[Q25] 只取前 N 条
来源：http://dali.chenlongwang.top/Article/details/gtcftcxwny.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzoitenzx.html

[Q26] 计数
来源：http://dali.chenzaomai.com/Article/details/gtbnsfzyai.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gteakdeaet.html

[Q27] 条件计数
来源：http://dali.hnqzz.top/Article/details/gtciwtbvci.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cqqwz.cn/Article/details/gttrjehtkb.html

[Q28] 求和与平均
来源：http://dali.zhengqikj.top/Article/details/gtrzvvtutk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtxhapglxr.html

[Q29] 最大最小值
来源：http://dali.ybcxt.top/Article/details/gtwrnsmtxg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtawxsbdci.html

[Q30] 分组统计
来源：http://dali.ybcxt.top/Article/details/gtlgofksww.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gtaqdrkvka.html

[Q31] 分组后过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklbwiwcu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yvedp.cn/Article/details/gthudspmhh.html

[Q32] 分组拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gtibbipbqk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gtdcwqhddj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ybcxt.top/Article/details/gthrrbihdk.html

[Q33] 多列分组
来源：http://dali.tianlin.xyz/Article/details/gtmfzejwef.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ydzc1.top/Article/details/gtaoxyysev.html

[Q34] 每组取第一条
来源：http://dali.yueranfly.top/Article/details/gtusgxlpsq.html

SELECT * FROM (
来源：http://dali.wangshuangyany.cn/Article/details/gtivvycsdv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nwbrower.top/Article/details/gtpeqpuwqd.html

) t WHERE rn = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtxsleurqx.html

[Q35] 内连接
来源：http://dali.316326.xyz/Article/details/gtwfjuzgtv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gtsoowwbwq.html

[Q36] 左连接
来源：http://dali.wangdashe.top/Article/details/gtigctpaqg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cqqwz.cn/Article/details/gtfnmssahq.html

[Q37] 右连接
来源：http://dali.0kj1m.cn/Article/details/gtnegqfpzq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuanzx.com/Article/details/gtoahhvjph.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nwbrower.top/Article/details/gtyapmxxbx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.quarkkingdee.top/Article/details/gtwocmtqud.html

[Q39] 自连接（查上下级）
来源：http://dali.yonumen.top/Article/details/gtkeuwmirx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.vqdsnc.cn/Article/details/gtdehpbwhn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sxryk.cn/Article/details/gtkayspquq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cucudq.cn/Article/details/gtehwyapuv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xuetiantiany.cn/Article/details/gtydvrkeco.html

[Q41] 多表连接
来源：http://dali.wangdashe.top/Article/details/gtgtgccnpk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sysykeji.top/Article/details/gtijmjxwlj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xziqi.cn/Article/details/gtsraygono.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cashguo.top/Article/details/gtwswoqdpq.html

[Q42] 连接条件附加过滤
来源：http://dali.sweek.top/Article/details/gtgsnkcwgu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hfpthk.cn/Article/details/gtyzspuugc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yueranfly.top/Article/details/gtdmmoaoeu.html

[Q43] 标量子查询
来源：http://dali.nwbrower.top/Article/details/gtegluhqtq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhixingplan.top/Article/details/gtzxqlmyqy.html

[Q44] IN 子查询
来源：http://dali.aibaodan.cn/Article/details/gtyhldplhu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.0kj1m.cn/Article/details/gtrrflkrfs.html

[Q45] EXISTS 判断存在
来源：http://dali.feifeiyinyue.top/Article/details/gtjwmsdioc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gtykinzkyo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ydzc1.top/Article/details/gtrntedaui.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqptmjrcn.html

[Q47] 与平均值比较
来源：http://dali.hnxiangtu.top/Article/details/gtrzggsnlz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tanke756.top/Article/details/gtbohvtcfq.html

[Q48] CTE 公用表表达式
来源：http://dali.cdnleiting.top/Article/details/gtgymjoyxg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.svipenyu.cn/Article/details/gtpjqwuzln.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xuanzx.com/Article/details/gtuamttmpp.html

[Q49] 更新单行
来源：http://dali.cdnleiting.top/Article/details/gtbovbbbxm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.316326.xyz/Article/details/gtsnqlbwsz.html

[Q50] 批量更新
来源：http://dali.chenjidiqi.icu/Article/details/gtihyjlzpm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.feifeiyinyue.top/Article/details/gtbxmeffqk.html

[Q51] 用子查询更新
来源：http://dali.hnqzz.top/Article/details/gtpdtxjutk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sweek.top/Article/details/gtnjmtbwwt.html

[Q52] 删除指定行
来源：http://dali.guannengcc.top/Article/details/gtnogflbps.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xziqi.cn/Article/details/gtdswnavac.html

[Q53] 按条件删除
来源：http://dali.cashguo.top/Article/details/gtddgyxdbg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gtklmpqlnv.html

[Q54] 清空表
来源：http://dali.nwbrower.top/Article/details/gtwybyikrv.html

TRUNCATE TABLE logs;
来源：http://dali.fzhhl.top/Article/details/gtcnwunecb.html

[Q55] 排名（并列占位）
来源：http://dali.sweek.top/Article/details/gtpnidhlll.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtpbdtgk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jqgfzy.top/Article/details/gtzysbmxqm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.daxiang520.top/Article/details/gthmhcuijh.html

[Q57] 行号
来源：http://dali.jlsjyb.cn/Article/details/gtpaxvljuq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtrzytaxbg.html

[Q58] 累计求和
来源：http://dali.sysykeji.top/Article/details/gtxrxnjaup.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtspmdyphs.html

[Q59] 分组内累计
来源：http://dali.feifeiyinyue.top/Article/details/gtvkanbnin.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtttjerrfl.html

[Q60] 取上一行 / 下一行
来源：http://dali.birdmap.top/Article/details/gtzuxajquu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gzhubu.top/Article/details/gttryjjztx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtqgutthin.html

[Q61] 移动平均
来源：http://dali.meibo888.top/Article/details/gtidrzykxk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtorgfegny.html

[Q62] 分组占比
来源：http://dali.hammf.cn/Article/details/gtjptvzhej.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gtcitpwwdo.html

[Q63] 开启事务
来源：http://dali.nanxinkj.top/Article/details/gtarksbqin.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuanzx.com/Article/details/gthanccyok.html

[Q64] 提交事务
来源：http://dali.ehwqpu.com/Article/details/gtnulxsxrn.html

COMMIT;
来源：http://dali.zhiwuduotai.top/Article/details/gtxqvpbppt.html

[Q65] 回滚事务
来源：http://dali.xziqi.cn/Article/details/gtmltzkcuj.html

ROLLBACK;
来源：http://dali.daria6918.cn/Article/details/gtxkrppnjh.html

[Q66] 行锁查询
来源：http://dali.aibaodan.cn/Article/details/gtvwzpigjp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhengqikj.top/Article/details/gtkyqrzowt.html

[Q67] 设置隔离级别
来源：http://dali.yanxiufei.cn/Article/details/gtlerfsdab.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.0kj1m.cn/Article/details/gtkloeyhhh.html

[Q68] 保存点
来源：http://dali.shanyushiyangtech.top/Article/details/gtrijliuuo.html

SAVEPOINT sp1;
来源：http://dali.tanke756.top/Article/details/gtedgbuhov.html

ROLLBACK TO sp1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhoslrke.html

[Q69] 查看执行计划
来源：http://dali.meibo888.top/Article/details/gtqtygfsye.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj202588.top/Article/details/gtdtmqznyg.html

[Q70] 更新统计信息
来源：http://dali.c1oappe.top/Article/details/gtodriydmz.html

ANALYZE TABLE users;
来源：http://dali.pycfn.com/Article/details/gtzipewspo.html

[Q71] 查看建表语句
来源：http://dali.cqqwz.cn/Article/details/gtbhzlawop.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ppjwa.cn/Article/details/gtemspzfrj.html

[Q72] 查看索引
来源：http://dali.vqdsnc.cn/Article/details/gtuwwjuwls.html

SHOW INDEX FROM users;
来源：http://dali.ivvv.top/Article/details/gtzywrxorj.html

[Q73] 查看表状态
来源：http://dali.guowangkeji.top/Article/details/gtngarfxnz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shangyingyoupin.top/Article/details/gtipxjcmqs.html

[Q74] 强制使用索引
来源：http://dali.dashuyun.cn/Article/details/gtypdsvcqe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.vqdsnc.cn/Article/details/gtjqyxegil.html

[Q75] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gtwfdxhxed.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtpahxmnfm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.smart0.xyz/Article/details/gtjsupwowl.html

[Q76] 按天统计
来源：http://dali.aizwys.cn/Article/details/gtnbaikgvi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhtfqcxb.html

[Q77] 时间加减
来源：http://dali.jinqigfzy.top/Article/details/gtqjidzoht.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.aibaodan.cn/Article/details/gtiruzyoky.html

[Q78] 当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gtornvqnvw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hnxiangtu.top/Article/details/gtbbyhwnqq.html

[Q79] 字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gtxrxnyudw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pengpengdd.cyou/Article/details/gtgogtwgzq.html

[Q80] 字符串截取
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfhqqmpj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtynzweqyf.html

[Q81] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gtfcmoyguh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yongpay.top/Article/details/gtajvuqsow.html

[Q82] 字符长度与字节长度
来源：http://dali.sysykeji.top/Article/details/gtckvzjwja.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gtjrvyqsku.html

[Q83] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gtwoxjdixy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gthakzrzyl.html

[Q84] 去除首尾空格
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbgmllvh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztbcfygd.html

[Q85] 数值取整
来源：http://dali.tianlin.xyz/Article/details/gtmvjxhpyn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daria6918.cn/Article/details/gtsabsdmbk.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypvekzza.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zycfv.cn/Article/details/gtdvbxfuwn.html

[Q87] JSON 字段做条件
来源：http://dali.jlsjyb.cn/Article/details/gtwqkokpsj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jqgfzy.top/Article/details/gthjnafqcl.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenjidiqi.icu/Article/details/gtbnhnhnen.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.9152youxi.cn/Article/details/gtmtuhgiav.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pycfn.com/Article/details/gtqcltzjtp.html

[Q89] 判断表是否存在
来源：http://dali.tian-w.cn/Article/details/gtdveksqyu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hfpthk.cn/Article/details/gtrncmgioj.html

[Q90] 生成序号列
来源：http://dali.mhx1999.top/Article/details/gtowkxednu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sxryk.cn/Article/details/gtcbwaliwj.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtnfkbnfnr.html

R. Bash 专题
来源：http://dali.yj202588.top/Article/details/gtcheskepe.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbljlqbw.html

[R01] shebang 与严格模式
来源：http://dali.hysaishi.cn/Article/details/gtocsfzrma.html

#!/usr/bin/env bash
来源：http://dali.iojbl.cn/Article/details/gtivpzzltn.html

set -euo pipefail
来源：http://dali.ehwqpu.com/Article/details/gtocskkvam.html

[R02] 变量赋值与使用
来源：http://dali.cucudq.cn/Article/details/gtzbcnwuov.html

name="Tom"; echo "$name"
来源：http://dali.gzhubu.top/Article/details/gtpeijozoa.html

[R03] 只读变量
来源：http://dali.jqgfzy.top/Article/details/gteqxvwyim.html

readonly PI=3.14
来源：http://dali.redwolf501.top/Article/details/gtmysyrjta.html

[R04] 位置参数
来源：http://dali.havefunace.top/Article/details/gtofotjksl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ppjwa.cn/Article/details/gtbuljwqhx.html

[R05] 参数默认值
来源：http://dali.dianchejie.cn/Article/details/gthtnsxrpb.html

name="${1:-default}"
来源：http://dali.nwbrower.top/Article/details/gtyycxvujr.html

[R06] 判断命令是否存在
来源：http://dali.zhongyouzk.top/Article/details/gtdrqmvdgf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gtfzyazvuy.html

[R07] if 判断文件
来源：http://dali.gogol.net.cn/Article/details/gtyqbrwhvo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtkhgsgixo.html

[R08] 数值比较
来源：http://dali.redwolf501.top/Article/details/gtdfmltytq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sweek.top/Article/details/gtttuunlej.html

[R09] 字符串比较
来源：http://dali.gzhubu.top/Article/details/gtdglokpky.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jqgfzy.top/Article/details/gtqjijlruw.html

[R10] 正则匹配
来源：http://dali.9152youxi.cn/Article/details/gtlvduhcyp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jianghu66.top/Article/details/gtoizvhuty.html

[R11] case 多分支
来源：http://dali.ppjwa.cn/Article/details/gtlgiaufpq.html

case "$1" in
来源：http://dali.jiagoushi.top/Article/details/gtuaecbmlt.html

start) echo "启动" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqostzosc.html

stop)  echo "停止" ;;
来源：http://dali.zdqjudy.top/Article/details/gtnjievpqc.html

*)     echo "未知命令" ;;
来源：http://dali.zhixingplan.top/Article/details/gthqkicdtk.html

esac
来源：http://dali.aibaodan.cn/Article/details/gteymejdgh.html

[R12] for 遍历文件
来源：http://dali.shuidangran.top/Article/details/gtonnfghjc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jyoumei.cn/Article/details/gtkezkbxwu.html

[R13] for 计数循环
来源：http://dali.cashguo.top/Article/details/gtjfnwhahd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cucudq.cn/Article/details/gtsamlvong.html

[R14] C 风格 for
来源：http://dali.birdmap.top/Article/details/gtehtzwhts.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.c1oappe.top/Article/details/gtxfkegbpm.html

[R15] while 逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtdobypoja.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cashguo.top/Article/details/gtemplwppx.html

[R16] until 等待条件
来源：http://dali.pengpengdd.cyou/Article/details/gtpbxhylrh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gtdckyplhw.html

[R17] 数组定义与取值
来源：http://dali.zycfv.cn/Article/details/gtvfhzrdgk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.iojbl.cn/Article/details/gtnpwupgwy.html

[R18] 遍历数组
来源：http://dali.yuanzhike.top/Article/details/gtgcqpgtwo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hysaishi.cn/Article/details/gtpotnlwhc.html

[R19] 数组长度
来源：http://dali.vqdsnc.cn/Article/details/gtoumpdihg.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtmecnks.html

[R20] 关联数组（字典）
来源：http://dali.gzhubu.top/Article/details/gtkqruezms.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnqzz.top/Article/details/gtkktffcsb.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gtqxiszuqn.html

echo "${#s}"
来源：http://dali.zhixingplan.top/Article/details/gttfbmkojw.html

[R22] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gtlgbadjdg.html

echo "${s:0:5}"
来源：http://dali.nwbrower.top/Article/details/gtzitjrrwi.html

[R23] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gtipikrbdm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yongpay.top/Article/details/gtfxdoqlwf.html

[R24] 大小写转换
来源：http://dali.sweek.top/Article/details/gtulgsynkr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xylfe.cn/Article/details/gtosykmvta.html

[R25] 去后缀 / 去前缀
来源：http://dali.bjfxy.top/Article/details/gtllclhcbz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigufen.top/Article/details/gtulxcfjgx.html

[R26] 命令替换
来源：http://dali.guowangkeji.top/Article/details/gttgbtbhkl.html

now=$(date +%F); echo "$now"
来源：http://dali.nanxuanxn.top/Article/details/gtyycbmsvs.html

[R27] 算术展开
来源：http://dali.jlsjyb.cn/Article/details/gtwjbnwrhc.html

echo $((1 + 2 * 3))
来源：http://dali.havefunace.top/Article/details/gtpbeqgwdq.html

[R28] 浮点运算
来源：http://dali.c1oappe.top/Article/details/gtnhtwaexp.html

echo "scale=2; 10/3" | bc
来源：http://dali.wangdashe.top/Article/details/gtkinernss.html

[R29] 定义函数
来源：http://dali.andypj.xyz/Article/details/gtqorzvonm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yuxming.cn/Article/details/gtcadiearj.html

[R30] 函数返回状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvmlbwcy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.316326.xyz/Article/details/gtmzngurph.html

[R31] 局部变量
来源：http://dali.daxiang520.top/Article/details/gtieaumfcz.html

f() { local x=1; echo "$x"; }
来源：http://dali.yanxiufei.cn/Article/details/gtimyuhszh.html

[R32] 参数个数校验
来源：http://dali.snrcjt.cn/Article/details/gtiebpjbrv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjvwjsbp.html

[R33] 捕获错误并提示行号
来源：http://dali.birdmap.top/Article/details/gtynqxuspn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ybcxt.top/Article/details/gthgtbwmzm.html

[R34] 退出时清理
来源：http://dali.mhx1999.top/Article/details/gtmkexpnam.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gtqmjrgfhf.html

[R35] 后台执行并等待
来源：http://dali.yonumen.top/Article/details/gteknsigvm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dianchejie.cn/Article/details/gtmnbawune.html

[R36] 并发执行多个任务
来源：http://dali.aizwys.cn/Article/details/gtmtysiqgp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yangfankeji.com/Article/details/gtglncpehm.html

[R37] 把输出赋给变量
来源：http://dali.gogol.net.cn/Article/details/gtbzqmbyyy.html

files=$(ls -1)
来源：http://dali.chenlongwang.top/Article/details/gtdgedwlrg.html

[R38] 管道串联
来源：http://dali.zhongyouzk.top/Article/details/gtzyaqhnqa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zycfv.cn/Article/details/gtsjfvztcu.html

[R39] 重定向标准输出与错误
来源：http://dali.snrcjt.cn/Article/details/gtmqmxzrze.html

cmd > out.log 2>&1
来源：http://dali.aibaodan.cn/Article/details/gtlbcgzate.html

[R40] 追加写日志
来源：http://dali.shzxlz.cn/Article/details/gtlmnfkxku.html

echo "log" >> out.log
来源：http://dali.sweek.top/Article/details/gtglluzetq.html

[R41] 丢弃输出
来源：http://dali.zhengqikj.top/Article/details/gtrpjwfihq.html

cmd >/dev/null 2>&1
来源：http://dali.chenzaomai.com/Article/details/gtznqspgfc.html

[R42] 输入重定向
来源：http://dali.dianchejie.cn/Article/details/gtaafsfirz.html

wc -l < a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtbnjvmlpn.html

[R43] 按名字查找文件
来源：http://dali.yj20258.top/Article/details/gtitxndivb.html

find . -name "*.log" -type f
来源：http://dali.sufxvd.cn/Article/details/gttpelktli.html

[R44] 按修改时间查找
来源：http://dali.yanxiufei.cn/Article/details/gtrbglicvn.html

find . -mtime -7 -type f
来源：http://dali.cheryme.top/Article/details/gtzwwyswwa.html

[R45] 批量删除
来源：http://dali.gogol.net.cn/Article/details/gtfjamlcth.html


<!-- 参考信息 -->