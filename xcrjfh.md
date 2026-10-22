代发 wailian999

CREATE TABLE users (
来源：http://dali.shanyushiyangtech.top/Article/details/gtytxevjzp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gtalcbxdim.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ehwqpu.com/Article/details/gtpufeinbo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hysaishi.cn/Article/details/gteqixmxja.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cqqwz.cn/Article/details/gtvyavxaei.html

);
来源：http://dali.mhx1999.top/Article/details/gtwxvsookf.html

[Q02] 创建带外键的表
来源：http://dali.chenjidiqi.icu/Article/details/gtpzveneag.html

CREATE TABLE orders (
来源：http://dali.dashuyun.cn/Article/details/gtoqpivccr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cheryme.top/Article/details/gtjpxkusld.html

user_id INT NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gtpojizqfb.html

amount DECIMAL(10, 2),
来源：http://dali.jlsjyb.cn/Article/details/gtiyjvuljv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nanxuanxn.top/Article/details/gtkpddbfod.html

);
来源：http://dali.xuanzx.com/Article/details/gticcmzmzf.html

[Q03] 增加列
来源：http://dali.c1oappe.top/Article/details/gtwuluodks.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sweek.top/Article/details/gtdwthicwf.html

[Q04] 修改列类型
来源：http://dali.redwolf501.top/Article/details/gtetquudvb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgfzy.top/Article/details/gtrwnmbyvs.html

[Q05] 重命名列
来源：http://dali.chenlongwang.top/Article/details/gtzfxtfmpg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xylfe.cn/Article/details/gttiilxisb.html

[Q06] 删除列
来源：http://dali.jlsjyb.cn/Article/details/gtpmvqbcuo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shzxlz.cn/Article/details/gtmnxdbrlx.html

[Q07] 删除表
来源：http://dali.zhixingplan.top/Article/details/gttymfbwqa.html

DROP TABLE IF EXISTS orders;
来源：http://dali.havefunace.top/Article/details/gtoieyzslv.html

[Q08] 创建普通索引
来源：http://dali.vqdsnc.cn/Article/details/gtvjklczru.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.kuanghao11.cn/Article/details/gtzfqkrirf.html

[Q09] 创建唯一索引
来源：http://dali.bjfxy.top/Article/details/gtmmtqepug.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hysaishi.cn/Article/details/gtalitewuo.html

[Q10] 插入单行
来源：http://dali.vqdsnc.cn/Article/details/gtoodrgfsg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gtqooaftey.html

[Q11] 一次插入多行
来源：http://dali.pycfn.com/Article/details/gtmrxkwmjz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.pycfn.com/Article/details/gtuibwoxrm.html

[Q12] 插入后取自增 ID
来源：http://dali.c1oappe.top/Article/details/gtuthjyntm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhoulong.xyz/Article/details/gtkrhglxfm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nanxuanxn.top/Article/details/gtoonljwdu.html

[Q13] 忽略重复插入
来源：http://dali.meibo888.top/Article/details/gtohthadtb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.redwolf501.top/Article/details/gtdzejsgil.html

[Q14] 存在则更新（upsert）
来源：http://dali.hammf.cn/Article/details/gtrrcqhehj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cdnleiting.top/Article/details/gtlnnetzlc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hammf.cn/Article/details/gtcflvnzjm.html

[Q15] 查询全部
来源：http://dali.cucudq.cn/Article/details/gtmnwtfttd.html

SELECT * FROM users;
来源：http://dali.wangdashe.top/Article/details/gtoyyjgidu.html

[Q16] 查询指定列
来源：http://dali.mhx1999.top/Article/details/gtafjtgdet.html

SELECT id, name FROM users;
来源：http://dali.0kj1m.cn/Article/details/gthonuxsuk.html

[Q17] 条件查询
来源：http://dali.yueranfly.top/Article/details/gteoppixqy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jianghu66.top/Article/details/gtykwschik.html

[Q18] 模糊匹配
来源：http://dali.tianlin.xyz/Article/details/gtrchldhpn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpczkrpp.html

[Q19] 范围查询
来源：http://dali.birdmap.top/Article/details/gtosguaqvp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.fengsongda.top/Article/details/gtnshklfml.html

[Q20] IN 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtsblsnbpq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.mhx1999.top/Article/details/gtnycduyso.html

[Q21] 空值判断
来源：http://dali.jiagoushi.top/Article/details/gtumweydtd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jianghu66.top/Article/details/gtgirzgrfr.html

[Q22] 排序
来源：http://dali.yuxming.cn/Article/details/gtlquhpboi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ybcxt.top/Article/details/gtdioeqvmo.html

[Q23] 分页
来源：http://dali.sysykeji.top/Article/details/gtucnsrrrr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hongshengwenyu.top/Article/details/gtgeyqwnas.html

[Q24] 去重
来源：http://dali.yangfankeji.com/Article/details/gtofymtetq.html

SELECT DISTINCT city FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gttkxlrqhp.html

[Q25] 只取前 N 条
来源：http://dali.hnqzz.top/Article/details/gtifnwufjs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nanxuanxn.top/Article/details/gtpzvfiopf.html

[Q26] 计数
来源：http://dali.hongshengwenyu.top/Article/details/gtfheahdak.html

SELECT COUNT(*) FROM users;
来源：http://dali.fengsongda.top/Article/details/gttudfxthm.html

[Q27] 条件计数
来源：http://dali.bjfxy.top/Article/details/gtaklrzeia.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hammf.cn/Article/details/gtovwdzwyv.html

[Q28] 求和与平均
来源：http://dali.hammf.cn/Article/details/gtlqpyjfpk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gthldnnqgq.html

[Q29] 最大最小值
来源：http://dali.jiagoushi.top/Article/details/gtdcokcngi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtadpxxqpy.html

[Q30] 分组统计
来源：http://dali.nanxuanxn.top/Article/details/gtuvezambl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gtrvvziikd.html

[Q31] 分组后过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtzozsuzwe.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.daxiang520.top/Article/details/gtuwseyiyv.html

[Q32] 分组拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gtzhkbpsns.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gtxyznvmhk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.quarkkingdee.top/Article/details/gtpvffvzky.html

[Q33] 多列分组
来源：http://dali.mhx1999.top/Article/details/gttsttnvzl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hammf.cn/Article/details/gtwotipdju.html

[Q34] 每组取第一条
来源：http://dali.yuanzhike.top/Article/details/gtlhwnxgvh.html

SELECT * FROM (
来源：http://dali.gogol.net.cn/Article/details/gtcjghxcvf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hnxiangtu.top/Article/details/gtxxqpwdvy.html

) t WHERE rn = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtuyvumhsw.html

[Q35] 内连接
来源：http://dali.jlsjyb.cn/Article/details/gtdvylnxpy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ybcxt.top/Article/details/gtucfemigw.html

[Q36] 左连接
来源：http://dali.cucudq.cn/Article/details/gtbusaksiw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jlsjyb.cn/Article/details/gtvsfkbphp.html

[Q37] 右连接
来源：http://dali.daria6918.cn/Article/details/gtvebovlap.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yvedp.cn/Article/details/gtsqomnxeo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuanzx.com/Article/details/gtkuelubsw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.0kj1m.cn/Article/details/gtizbtkkpz.html

[Q39] 自连接（查上下级）
来源：http://dali.fengsongda.top/Article/details/gtmflzmxkq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xziqi.cn/Article/details/gtwsingdvp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xziqi.cn/Article/details/gtyayfulhq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yuanzhike.top/Article/details/gtmhsejzog.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.feifeiyinyue.top/Article/details/gtrgjezjrk.html

[Q41] 多表连接
来源：http://dali.chenzaomai.com/Article/details/gtyknskene.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.svipenyu.cn/Article/details/gtgugyjovi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.guowangkeji.top/Article/details/gtnlndaplp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yangfankeji.com/Article/details/gtfivbudfu.html

[Q42] 连接条件附加过滤
来源：http://dali.9152youxi.cn/Article/details/gtdxhbggio.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gtjforktif.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhengqikj.top/Article/details/gtfuunzmld.html

[Q43] 标量子查询
来源：http://dali.daria6918.cn/Article/details/gttlnffqdq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.pycfn.com/Article/details/gtkogdwfis.html

[Q44] IN 子查询
来源：http://dali.fzhhl.top/Article/details/gtlslgdglr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sweek.top/Article/details/gtlkefntuz.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxuanxn.top/Article/details/gthcvagwba.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gtbuumahmw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shangyingyoupin.top/Article/details/gtqwjvwefg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gtvquwvasn.html

[Q47] 与平均值比较
来源：http://dali.cucudq.cn/Article/details/gtcvscliuh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ydzc1.top/Article/details/gtqomffilx.html

[Q48] CTE 公用表表达式
来源：http://dali.xziqi.cn/Article/details/gthyusltze.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckkdlmhm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhoulong.xyz/Article/details/gtdliypous.html

[Q49] 更新单行
来源：http://dali.zhiwuduotai.top/Article/details/gtlpsdykvf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xylfe.cn/Article/details/gtgetgjssg.html

[Q50] 批量更新
来源：http://dali.cashguo.top/Article/details/gttfvisfun.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.snrcjt.cn/Article/details/gtvlqampju.html

[Q51] 用子查询更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtygvocnap.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.guowangkeji.top/Article/details/gtlziuxite.html

[Q52] 删除指定行
来源：http://dali.meibo888.top/Article/details/gtghrkfrdt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258888.top/Article/details/gttzypraqz.html

[Q53] 按条件删除
来源：http://dali.pycfn.com/Article/details/gtpjujsuhj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cheryme.top/Article/details/gtivdjicjb.html

[Q54] 清空表
来源：http://dali.ivvv.top/Article/details/gthkgpwohx.html

TRUNCATE TABLE logs;
来源：http://dali.sysykeji.top/Article/details/gthcphojod.html

[Q55] 排名（并列占位）
来源：http://dali.pengpengdd.cyou/Article/details/gtvbuqvpod.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.redwolf501.top/Article/details/gticcryqlh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sweek.top/Article/details/gthhtnjmns.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gtykqynpyc.html

[Q57] 行号
来源：http://dali.tanke756.top/Article/details/gttyawacca.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtenlqsloc.html

[Q58] 累计求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmlqwfhnj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hammf.cn/Article/details/gtnhrofxpo.html

[Q59] 分组内累计
来源：http://dali.sufxvd.cn/Article/details/gtuueuwatf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtububjsqi.html

[Q60] 取上一行 / 下一行
来源：http://dali.shzxlz.cn/Article/details/gtooeesvaf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yanxiufei.cn/Article/details/gtyoxrxxmo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ivvv.top/Article/details/gtvymretvn.html

[Q61] 移动平均
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgxjcnmw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtvcowrvym.html

[Q62] 分组占比
来源：http://dali.feifeiyinyue.top/Article/details/gtgvighbvz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gtyjrnqbzq.html

[Q63] 开启事务
来源：http://dali.9152youxi.cn/Article/details/gtdytpkotn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jiagoushi.top/Article/details/gtojfzbtgg.html

[Q64] 提交事务
来源：http://dali.ydzc1.top/Article/details/gtqnxfytnb.html

COMMIT;
来源：http://dali.c1oappe.top/Article/details/gturkbpfor.html

[Q65] 回滚事务
来源：http://dali.hfpthk.cn/Article/details/gthcxuddtd.html

ROLLBACK;
来源：http://dali.gzhubu.top/Article/details/gtzycqbtki.html

[Q66] 行锁查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfthgckcz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.dianchejie.cn/Article/details/gtozmcnbeh.html

[Q67] 设置隔离级别
来源：http://dali.jinqigufen.top/Article/details/gtznmtkfri.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hammf.cn/Article/details/gttffcgcib.html

[Q68] 保存点
来源：http://dali.zycfv.cn/Article/details/gtnkjlbery.html

SAVEPOINT sp1;
来源：http://dali.chenlongwang.top/Article/details/gteuixzgit.html

ROLLBACK TO sp1;
来源：http://dali.jianghu66.top/Article/details/gtldhchcpz.html

[Q69] 查看执行计划
来源：http://dali.jyoumei.cn/Article/details/gtxerpcjxl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gzhubu.top/Article/details/gtvxacxbqh.html

[Q70] 更新统计信息
来源：http://dali.xinyue.icu/Article/details/gthtxavrwy.html

ANALYZE TABLE users;
来源：http://dali.meibo888.top/Article/details/gtdsmtxhuz.html

[Q71] 查看建表语句
来源：http://dali.chenzaomai.com/Article/details/gtmunxhiln.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj202588.top/Article/details/gtmilfpbof.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gtznmjoipv.html

SHOW INDEX FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gttnqyeolt.html

[Q73] 查看表状态
来源：http://dali.zhixingplan.top/Article/details/gtdbfrlczq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenzaomai.com/Article/details/gtjmlmkhin.html

[Q74] 强制使用索引
来源：http://dali.redwolf501.top/Article/details/gturswzanr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hnqzz.top/Article/details/gtgniwhoab.html

[Q75] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtxnboyhts.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtkmcyykbz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.pengpengdd.cyou/Article/details/gthpxfkjem.html

[Q76] 按天统计
来源：http://dali.chenjidiqi.icu/Article/details/gtmedwevwr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nwbrower.top/Article/details/gtddxjqufh.html

[Q77] 时间加减
来源：http://dali.shuidangran.top/Article/details/gtwdjcttgk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigufen.top/Article/details/gtsapklglj.html

[Q78] 当前时间
来源：http://dali.0kj1m.cn/Article/details/gtgawycwqf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guowangkeji.top/Article/details/gtdwtfkjws.html

[Q79] 字符串拼接
来源：http://dali.pycfn.com/Article/details/gtrdprtwxz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhengqikj.top/Article/details/gtbpjfxcde.html

[Q80] 字符串截取
来源：http://dali.yangfankeji.com/Article/details/gtnjjqnewy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtdwqilhcf.html

[Q81] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gtutmkiatr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pycfn.com/Article/details/gtehhsxlbs.html

[Q82] 字符长度与字节长度
来源：http://dali.xuetiantiany.cn/Article/details/gttrwyfssb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtmmuhzqnb.html

[Q83] 大小写转换
来源：http://dali.mhx1999.top/Article/details/gtgikjwfga.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtnhskrpht.html

[Q84] 去除首尾空格
来源：http://dali.svipenyu.cn/Article/details/gtyqkgjieo.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtsethlwar.html

[Q85] 数值取整
来源：http://dali.nanxuanxn.top/Article/details/gtgjxfhgqy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yongpay.top/Article/details/gtsaujyisv.html

[Q86] 读取 JSON 字段
来源：http://dali.guannengcc.top/Article/details/gtcgxtnyty.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yuxming.cn/Article/details/gtemcblsyd.html

[Q87] JSON 字段做条件
来源：http://dali.aizwys.cn/Article/details/gtbtylamii.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.quarkkingdee.top/Article/details/gtijvsyxfe.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzjxsqdb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nwbrower.top/Article/details/gtdwzaqwvc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.c1oappe.top/Article/details/gtwhwrxytc.html

[Q89] 判断表是否存在
来源：http://dali.zdqjudy.top/Article/details/gtfeuvcbrq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yvedp.cn/Article/details/gtxrpgtnjy.html

[Q90] 生成序号列
来源：http://dali.xylfe.cn/Article/details/gtdcqebwda.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yvedp.cn/Article/details/gtiqbwypxn.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtkttnlzht.html

R. Bash 专题
来源：http://dali.sysykeji.top/Article/details/gtvsywugzz.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtuoktfsce.html

[R01] shebang 与严格模式
来源：http://dali.hnqzz.top/Article/details/gtiykrhzzq.html

#!/usr/bin/env bash
来源：http://dali.birdmap.top/Article/details/gtuqrikxka.html

set -euo pipefail
来源：http://dali.nanxuanxn.top/Article/details/gtnmoltcgg.html

[R02] 变量赋值与使用
来源：http://dali.bjfxy.top/Article/details/gtjqemyrem.html

name="Tom"; echo "$name"
来源：http://dali.dianchejie.cn/Article/details/gthpuzvhgd.html

[R03] 只读变量
来源：http://dali.pengpengdd.cyou/Article/details/gtkhuhmrpx.html

readonly PI=3.14
来源：http://dali.ehwqpu.com/Article/details/gtwcgjdmnw.html

[R04] 位置参数
来源：http://dali.dianchejie.cn/Article/details/gthblpggyt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hammf.cn/Article/details/gthbivtkbc.html

[R05] 参数默认值
来源：http://dali.redwolf501.top/Article/details/gtrfwxdgus.html

name="${1:-default}"
来源：http://dali.wangdashe.top/Article/details/gtqpwxsuyy.html

[R06] 判断命令是否存在
来源：http://dali.chenlongwang.top/Article/details/gtfeoeijbx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gtbrsatizd.html

[R07] if 判断文件
来源：http://dali.bjfxy.top/Article/details/gtanjpzlna.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.andypj.xyz/Article/details/gttoheaszr.html

[R08] 数值比较
来源：http://dali.jlsjyb.cn/Article/details/gtidwaiuuy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gotoacloud.top/Article/details/gtvlasgihd.html

[R09] 字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gtlkinqvoq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtlcopuwvg.html

[R10] 正则匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtagcqudxz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cqqwz.cn/Article/details/gtcivhkqyf.html

[R11] case 多分支
来源：http://dali.ybcxt.top/Article/details/gtpbcsvlfr.html

case "$1" in
来源：http://dali.ybcxt.top/Article/details/gthqvfiqqp.html

start) echo "启动" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gtzhmrauov.html

stop)  echo "停止" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaylmpgaj.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gtmqpsjieh.html

esac
来源：http://dali.gogol.net.cn/Article/details/gtiozlciao.html

[R12] for 遍历文件
来源：http://dali.kuanghao11.cn/Article/details/gtrkkvhyry.html

for f in *.txt; do echo "$f"; done
来源：http://dali.vqdsnc.cn/Article/details/gtecgwvncj.html

[R13] for 计数循环
来源：http://dali.bjfxy.top/Article/details/gtyqkylwmo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigfzy.top/Article/details/gtyubjvmpc.html

[R14] C 风格 for
来源：http://dali.yj202588.top/Article/details/gthtssdqlu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtnrmwzsgb.html

[R15] while 逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtomcxgktq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tian-w.cn/Article/details/gtvvszzfct.html

[R16] until 等待条件
来源：http://dali.zhongyouzk.top/Article/details/gtlhocqfmr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ehwqpu.com/Article/details/gtbgequcxt.html

[R17] 数组定义与取值
来源：http://dali.wangshuangyany.cn/Article/details/gtvifgjbij.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yueranfly.top/Article/details/gtwblbhunm.html

[R18] 遍历数组
来源：http://dali.9152youxi.cn/Article/details/gtlwoyetvw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dashuyun.cn/Article/details/gtjryuygou.html

[R19] 数组长度
来源：http://dali.sxryk.cn/Article/details/gtegykptcs.html

echo "${#arr[@]}"
来源：http://dali.cashguo.top/Article/details/gtgzrpskfh.html

[R20] 关联数组（字典）
来源：http://dali.hysaishi.cn/Article/details/gtnekydged.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.guowangkeji.top/Article/details/gtbcxhxuvx.html

[R21] 字符串长度
来源：http://dali.shuidangran.top/Article/details/gtnuhukncq.html

echo "${#s}"
来源：http://dali.gogol.net.cn/Article/details/gtlylivpuf.html

[R22] 截取子串
来源：http://dali.ybcxt.top/Article/details/gtvifyjodn.html

echo "${s:0:5}"
来源：http://dali.zhoulong.xyz/Article/details/gthisoiwog.html

[R23] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gtywlrqyue.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yueranfly.top/Article/details/gtshtbyegz.html

[R24] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gtcgxbfqpo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj20258888.top/Article/details/gtarjxzgwz.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj20258888.top/Article/details/gtzgjrluyn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yangfankeji.com/Article/details/gtcununbcn.html

[R26] 命令替换
来源：http://dali.ybcxt.top/Article/details/gtkqcquttw.html

now=$(date +%F); echo "$now"
来源：http://dali.smart0.xyz/Article/details/gtnowscabr.html

[R27] 算术展开
来源：http://dali.jyoumei.cn/Article/details/gtsnxeybbt.html

echo $((1 + 2 * 3))
来源：http://dali.hywenlv.cn/Article/details/gtdsqebnkk.html

[R28] 浮点运算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcgtxckh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhoulong.xyz/Article/details/gteogrmbix.html

[R29] 定义函数
来源：http://dali.zdqjudy.top/Article/details/gtwvnxvavr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zdqjudy.top/Article/details/gtoqnycbei.html

[R30] 函数返回状态码
来源：http://dali.cheryme.top/Article/details/gtjlfytdct.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.smart0.xyz/Article/details/gtwleynekn.html

[R31] 局部变量
来源：http://dali.c1oappe.top/Article/details/gtpnirrrlw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zycfv.cn/Article/details/gtiedgczwg.html

[R32] 参数个数校验
来源：http://dali.shzxlz.cn/Article/details/gtlkhthawu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gtebzrjcau.html

[R33] 捕获错误并提示行号
来源：http://dali.yvedp.cn/Article/details/gtzgtrawos.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jianghu66.top/Article/details/gtnqtywwno.html

[R34] 退出时清理
来源：http://dali.yuanzhike.top/Article/details/gtvxacqqax.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gtqzalmssc.html

[R35] 后台执行并等待
来源：http://dali.hammf.cn/Article/details/gtizpkbojt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.vqdsnc.cn/Article/details/gtgcfuhslv.html

[R36] 并发执行多个任务
来源：http://dali.dashuyun.cn/Article/details/gtygmdajth.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fzhhl.top/Article/details/gtzjsetgrr.html

[R37] 把输出赋给变量
来源：http://dali.yonumen.top/Article/details/gtvltbsycd.html

files=$(ls -1)
来源：http://dali.cucudq.cn/Article/details/gtzrajtbfv.html

[R38] 管道串联
来源：http://dali.guannengcc.top/Article/details/gtnezgnjlp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gogol.net.cn/Article/details/gttqzetvfk.html

[R39] 重定向标准输出与错误
来源：http://dali.snrcjt.cn/Article/details/gttpypgvcy.html

cmd > out.log 2>&1
来源：http://dali.bjfxy.top/Article/details/gtkucypncp.html

[R40] 追加写日志
来源：http://dali.ybcxt.top/Article/details/gthpucmfip.html

echo "log" >> out.log
来源：http://dali.haohaochexian.top/Article/details/gthqbormdt.html

[R41] 丢弃输出
来源：http://dali.xuetiantiany.cn/Article/details/gtyctwwzto.html

cmd >/dev/null 2>&1
来源：http://dali.shzxlz.cn/Article/details/gtesjtrfku.html

[R42] 输入重定向
来源：http://dali.havefunace.top/Article/details/gtngfkmwup.html

wc -l < a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtdbdeolvv.html

[R43] 按名字查找文件
来源：http://dali.pengpengdd.cyou/Article/details/gtkfzrhcnv.html

find . -name "*.log" -type f
来源：http://dali.jinqigfzy.top/Article/details/gtnavbraht.html

[R44] 按修改时间查找
来源：http://dali.feifeiyinyue.top/Article/details/gtemflwpcf.html

find . -mtime -7 -type f
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhjgbnbs.html

[R45] 批量删除
来源：http://dali.yueranfly.top/Article/details/gtzzjmcqkr.html


<!-- 参考信息 -->