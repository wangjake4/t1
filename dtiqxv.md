代发 wailian999

CREATE TABLE users (
来源：http://dali.xuanzx.com/Article/details/gtevkekpmt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjcwznfo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gtipskbceq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ehwqpu.com/Article/details/gtpizwgebn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yanxiufei.cn/Article/details/gttefosljm.html

);
来源：http://dali.tian-w.cn/Article/details/gtquzevjwz.html

[Q02] 创建带外键的表
来源：http://dali.hammf.cn/Article/details/gtrhuytnep.html

CREATE TABLE orders (
来源：http://dali.zhixingplan.top/Article/details/gthhaywpcv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yonumen.top/Article/details/gtveizopjm.html

user_id INT NOT NULL,
来源：http://dali.zhongyouzk.top/Article/details/gtcitkzdyn.html

amount DECIMAL(10, 2),
来源：http://dali.sxryk.cn/Article/details/gtuncbgcoi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ivvv.top/Article/details/gthcelytvz.html

);
来源：http://dali.ehwqpu.com/Article/details/gtzplzdrye.html

[Q03] 增加列
来源：http://dali.pycfn.com/Article/details/gtyhwsfpyv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pycfn.com/Article/details/gtzjsmqqsi.html

[Q04] 修改列类型
来源：http://dali.nwbrower.top/Article/details/gtkxynuytx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yonumen.top/Article/details/gttbwvycbr.html

[Q05] 重命名列
来源：http://dali.ydzc1.top/Article/details/gtdiqjflnj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.wangdashe.top/Article/details/gtuitnqrcy.html

[Q06] 删除列
来源：http://dali.shzxlz.cn/Article/details/gtfrmqfsyi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fzhhl.top/Article/details/gtazgezcae.html

[Q07] 删除表
来源：http://dali.cucudq.cn/Article/details/gtmbsomput.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sweek.top/Article/details/gtlovbtcrx.html

[Q08] 创建普通索引
来源：http://dali.redwolf501.top/Article/details/gtsjlcsrlb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gtpbnhijmq.html

[Q09] 创建唯一索引
来源：http://dali.zhixingplan.top/Article/details/gtgmdvjbmm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yvedp.cn/Article/details/gtidhzbzcz.html

[Q10] 插入单行
来源：http://dali.dianchejie.cn/Article/details/gtojbahvbg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.fzhhl.top/Article/details/gtbjmunwnf.html

[Q11] 一次插入多行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtepdhnpiw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.guannengcc.top/Article/details/gtjvumlkft.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258.top/Article/details/gtihvjmpns.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.mhx1999.top/Article/details/gtjffahxqd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.meibo888.top/Article/details/gtvocrelgi.html

[Q13] 忽略重复插入
来源：http://dali.snrcjt.cn/Article/details/gtnowvmzqg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gtzmgybukv.html

[Q14] 存在则更新（upsert）
来源：http://dali.fzhhl.top/Article/details/gtpzllmigw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yanxiufei.cn/Article/details/gttdubiycx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.feifeiyinyue.top/Article/details/gtrounhczl.html

[Q15] 查询全部
来源：http://dali.jinqigfzy.top/Article/details/gtzxbuabgg.html

SELECT * FROM users;
来源：http://dali.havefunace.top/Article/details/gtbqrvnvjl.html

[Q16] 查询指定列
来源：http://dali.gaohongyu789.top/Article/details/gtsoqetyxg.html

SELECT id, name FROM users;
来源：http://dali.yuxming.cn/Article/details/gteqrqudrw.html

[Q17] 条件查询
来源：http://dali.tanke756.top/Article/details/gtkxkrcwoh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cdnleiting.top/Article/details/gtojhnskgz.html

[Q18] 模糊匹配
来源：http://dali.zhongyouzk.top/Article/details/gtaoratjow.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnxiangtu.top/Article/details/gtlxoryuhp.html

[Q19] 范围查询
来源：http://dali.shangyingyoupin.top/Article/details/gtqcuzzmzp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.kuanghao11.cn/Article/details/gthcgnzzni.html

[Q20] IN 列表
来源：http://dali.wangdashe.top/Article/details/gtstlqsjea.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.316326.xyz/Article/details/gtocegouak.html

[Q21] 空值判断
来源：http://dali.shanyushiyangtech.top/Article/details/gteyjerqpd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.snrcjt.cn/Article/details/gtpchvmtpf.html

[Q22] 排序
来源：http://dali.cashguo.top/Article/details/gtjsoiwzes.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.9152youxi.cn/Article/details/gthlgdfkni.html

[Q23] 分页
来源：http://dali.hnqzz.top/Article/details/gtixjlxgwy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jqgfzy.top/Article/details/gtefqkcsci.html

[Q24] 去重
来源：http://dali.yj20258888.top/Article/details/gtnjrjxbtl.html

SELECT DISTINCT city FROM users;
来源：http://dali.haohaochexian.top/Article/details/gthzzxocas.html

[Q25] 只取前 N 条
来源：http://dali.jqgufenzy.top/Article/details/gtyeohuzqd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tian-w.cn/Article/details/gtymfbmqxj.html

[Q26] 计数
来源：http://dali.chenjidiqi.icu/Article/details/gtfefgsqyb.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gthmbzzctz.html

[Q27] 条件计数
来源：http://dali.tian-w.cn/Article/details/gtdxnyifkv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtdykdtqsg.html

[Q28] 求和与平均
来源：http://dali.cucudq.cn/Article/details/gtozwkzdyy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hammf.cn/Article/details/gttdblogem.html

[Q29] 最大最小值
来源：http://dali.hongshengwenyu.top/Article/details/gtiqlluumr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtdwlbqaqd.html

[Q30] 分组统计
来源：http://dali.hammf.cn/Article/details/gtneokxcpg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gtffneadlj.html

[Q31] 分组后过滤
来源：http://dali.daxiang520.top/Article/details/gtoktfdwxf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.mhx1999.top/Article/details/gtvuymnvsm.html

[Q32] 分组拼接字符串
来源：http://dali.meibo888.top/Article/details/gtqcjkxgdn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gtaiwbfplv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xinyue.icu/Article/details/gtvjzuupgx.html

[Q33] 多列分组
来源：http://dali.jinqigfzy.top/Article/details/gtlppakbkq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.havefunace.top/Article/details/gtzrspmcze.html

[Q34] 每组取第一条
来源：http://dali.yj20258.top/Article/details/gtiqtmuhah.html

SELECT * FROM (
来源：http://dali.bjfxy.top/Article/details/gtpjyufndc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjrtzelv.html

) t WHERE rn = 1;
来源：http://dali.cashguo.top/Article/details/gtkgbzeezu.html

[Q35] 内连接
来源：http://dali.meibo888.top/Article/details/gtlretvjio.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.andypj.xyz/Article/details/gtgbhhpvom.html

[Q36] 左连接
来源：http://dali.shangyingyoupin.top/Article/details/gtziijbzjs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuanzx.com/Article/details/gtrprnprif.html

[Q37] 右连接
来源：http://dali.zhixingplan.top/Article/details/gtrweiiclv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zdqjudy.top/Article/details/gtewvnjuyg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.snrcjt.cn/Article/details/gtelkglvdb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ydzc1.top/Article/details/gthjrhhksd.html

[Q39] 自连接（查上下级）
来源：http://dali.kuanghao11.cn/Article/details/gtiqlcyxff.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hammf.cn/Article/details/gtymnpxqgd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xuanzx.com/Article/details/gtzerkrgty.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.haohaochexian.top/Article/details/gtwmqdnrpx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shzxlz.cn/Article/details/gtzoinwonf.html

[Q41] 多表连接
来源：http://dali.tian-w.cn/Article/details/gthugveiur.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daxiang520.top/Article/details/gtxhxmkhbi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ybcxt.top/Article/details/gtkgnnmlum.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinqigufen.top/Article/details/gtcuygujsu.html

[Q42] 连接条件附加过滤
来源：http://dali.tanke756.top/Article/details/gtfojbdswx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.vqdsnc.cn/Article/details/gtfzdzgesa.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yvedp.cn/Article/details/gtbppponwb.html

[Q43] 标量子查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbdkvtol.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jlsjyb.cn/Article/details/gtyjerxvln.html

[Q44] IN 子查询
来源：http://dali.cqqwz.cn/Article/details/gtyaypydok.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenlongwang.top/Article/details/gtidwmagjt.html

[Q45] EXISTS 判断存在
来源：http://dali.zycfv.cn/Article/details/gtmorxqhrt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.iojbl.cn/Article/details/gttawcjmoi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtenqssbmb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhoulong.xyz/Article/details/gtfwsnauox.html

[Q47] 与平均值比较
来源：http://dali.nanxuanxn.top/Article/details/gttqxjpynz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnqzz.top/Article/details/gtknkbihmk.html

[Q48] CTE 公用表表达式
来源：http://dali.mhx1999.top/Article/details/gttdjktgxs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.c1oappe.top/Article/details/gtfgqdflam.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ydzc1.top/Article/details/gtpxrkanjz.html

[Q49] 更新单行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtryxzuqnp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gthlmuvwio.html

[Q50] 批量更新
来源：http://dali.sysykeji.top/Article/details/gtclvbbbrb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hammf.cn/Article/details/gtivdsderf.html

[Q51] 用子查询更新
来源：http://dali.yvedp.cn/Article/details/gttmnqvqrs.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xinyue.icu/Article/details/gtpybqrbzf.html

[Q52] 删除指定行
来源：http://dali.zycfv.cn/Article/details/gtzehosivz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.meibo888.top/Article/details/gtcrdggpjl.html

[Q53] 按条件删除
来源：http://dali.jinghuilouyu.cn/Article/details/gtdoszvblv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.quarkkingdee.top/Article/details/gtcdxvnqng.html

[Q54] 清空表
来源：http://dali.hnxiangtu.top/Article/details/gtatuyhyfs.html

TRUNCATE TABLE logs;
来源：http://dali.meibo888.top/Article/details/gtkrfcnujj.html

[Q55] 排名（并列占位）
来源：http://dali.jyoumei.cn/Article/details/gtgoabrhvo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtrvdkzgmr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hammf.cn/Article/details/gtnqtowfcd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjpubofhm.html

[Q57] 行号
来源：http://dali.jianghu66.top/Article/details/gtbjhfnxol.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258.top/Article/details/gtzvrkyhyk.html

[Q58] 累计求和
来源：http://dali.0kj1m.cn/Article/details/gtjmidzdhh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tanke756.top/Article/details/gtrmwjcwna.html

[Q59] 分组内累计
来源：http://dali.yanxiufei.cn/Article/details/gtgrjcrxku.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtswengunb.html

[Q60] 取上一行 / 下一行
来源：http://dali.sufxvd.cn/Article/details/gtfxduxlrn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj20258.top/Article/details/gtjelfeegk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtgjqmzlsa.html

[Q61] 移动平均
来源：http://dali.daxiang520.top/Article/details/gtaauocxjy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtzhscgtzf.html

[Q62] 分组占比
来源：http://dali.shanyushiyangtech.top/Article/details/gtwigaynba.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtzihzefgv.html

[Q63] 开启事务
来源：http://dali.jinqigufen.top/Article/details/gtwqczycjq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangshuangyany.cn/Article/details/gtsdjwusoo.html

[Q64] 提交事务
来源：http://dali.guannengcc.top/Article/details/gtvhmybhxr.html

COMMIT;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnnnvrin.html

[Q65] 回滚事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkbuacry.html

ROLLBACK;
来源：http://dali.cqqwz.cn/Article/details/gtluwpyjri.html

[Q66] 行锁查询
来源：http://dali.jinqigfzy.top/Article/details/gttshxyeaq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.havefunace.top/Article/details/gtmdodevli.html

[Q67] 设置隔离级别
来源：http://dali.yuanzhike.top/Article/details/gtiuotyiaz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.316326.xyz/Article/details/gtzanitalw.html

[Q68] 保存点
来源：http://dali.cdnleiting.top/Article/details/gtcakbkrka.html

SAVEPOINT sp1;
来源：http://dali.aizwys.cn/Article/details/gtnchuljzy.html

ROLLBACK TO sp1;
来源：http://dali.jinqigfzy.top/Article/details/gtobxastuv.html

[Q69] 查看执行计划
来源：http://dali.ivvv.top/Article/details/gtjuwjfbnk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aizwys.cn/Article/details/gtybxdmiyj.html

[Q70] 更新统计信息
来源：http://dali.sysykeji.top/Article/details/gtwpgssaex.html

ANALYZE TABLE users;
来源：http://dali.ehwqpu.com/Article/details/gtwojpvvhi.html

[Q71] 查看建表语句
来源：http://dali.shuidangran.top/Article/details/gtsrjgafzs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.pycfn.com/Article/details/gtbvdfewrb.html

[Q72] 查看索引
来源：http://dali.jiagoushi.top/Article/details/gtvnpidjfm.html

SHOW INDEX FROM users;
来源：http://dali.mhx1999.top/Article/details/gtfujoxyki.html

[Q73] 查看表状态
来源：http://dali.zycfv.cn/Article/details/gtgzvcukrf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xinyue.icu/Article/details/gteqdpijtt.html

[Q74] 强制使用索引
来源：http://dali.aibaodan.cn/Article/details/gtmcxaxegk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhiwuduotai.top/Article/details/gtfmpqkpmw.html

[Q75] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gtotdrohhz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnqzz.top/Article/details/gttnvsbkza.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinghuilouyu.cn/Article/details/gtwyqwkmqb.html

[Q76] 按天统计
来源：http://dali.jqgufenzy.top/Article/details/gtiobdjywf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.316326.xyz/Article/details/gtnlncyqif.html

[Q77] 时间加减
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvodpywd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwlwhgcpu.html

[Q78] 当前时间
来源：http://dali.tian-w.cn/Article/details/gtucpigpte.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yueranfly.top/Article/details/gtccilyqcd.html

[Q79] 字符串拼接
来源：http://dali.havefunace.top/Article/details/gtzcdwqrze.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ivvv.top/Article/details/gtsoqynnpi.html

[Q80] 字符串截取
来源：http://dali.yuanzhike.top/Article/details/gtyubwjdgn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tanke756.top/Article/details/gtdsvuqhpj.html

[Q81] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gtopdblqnj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuxming.cn/Article/details/gtzfzyjybu.html

[Q82] 字符长度与字节长度
来源：http://dali.yj20258.top/Article/details/gtmhvxzoce.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtmiuavxyj.html

[Q83] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gtmatjtgra.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtsnjwawvy.html

[Q84] 去除首尾空格
来源：http://dali.vqdsnc.cn/Article/details/gtlzkhrsci.html

SELECT TRIM(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtmrskkhji.html

[Q85] 数值取整
来源：http://dali.andypj.xyz/Article/details/gtxbddmjpd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.meibo888.top/Article/details/gtsboizmus.html

[Q86] 读取 JSON 字段
来源：http://dali.c1oappe.top/Article/details/gtcrkkjsff.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxswlkdn.html

[Q87] JSON 字段做条件
来源：http://dali.ybcxt.top/Article/details/gtyaycskat.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ybcxt.top/Article/details/gtbvhsomed.html

[Q88] 行转列（条件聚合）
来源：http://dali.yvedp.cn/Article/details/gtuokgjemt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.wangshuangyany.cn/Article/details/gtpoulzlqp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtufrlmfbe.html

[Q89] 判断表是否存在
来源：http://dali.haohaochexian.top/Article/details/gtdcvzhfyo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gtkrirbjtk.html

[Q90] 生成序号列
来源：http://dali.yj20258888.top/Article/details/gtduxtlrhk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqovuoui.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gttwdztgfh.html

R. Bash 专题
来源：http://dali.dianchejie.cn/Article/details/gtfebtqmrt.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gthxqodgen.html

[R01] shebang 与严格模式
来源：http://dali.yangfankeji.com/Article/details/gtgtdcutvf.html

#!/usr/bin/env bash
来源：http://dali.cucudq.cn/Article/details/gtktiamkic.html

set -euo pipefail
来源：http://dali.zhixingplan.top/Article/details/gtozorwvwh.html

[R02] 变量赋值与使用
来源：http://dali.wangdashe.top/Article/details/gtjwrmptwh.html

name="Tom"; echo "$name"
来源：http://dali.yvedp.cn/Article/details/gtdytashgh.html

[R03] 只读变量
来源：http://dali.hywenlv.cn/Article/details/gtpxruxxxp.html

readonly PI=3.14
来源：http://dali.zdqjudy.top/Article/details/gtgrbwulfv.html

[R04] 位置参数
来源：http://dali.hongshengwenyu.top/Article/details/gtdbbzxkhg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hfpthk.cn/Article/details/gtjzklmuau.html

[R05] 参数默认值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxkrzwpj.html

name="${1:-default}"
来源：http://dali.andypj.xyz/Article/details/gtsivuvlof.html

[R06] 判断命令是否存在
来源：http://dali.ppjwa.cn/Article/details/gtrcvahsjn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gtulslezfl.html

[R07] if 判断文件
来源：http://dali.gaohongyu789.top/Article/details/gtlyovojbb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.haohaochexian.top/Article/details/gtqlizrqln.html

[R08] 数值比较
来源：http://dali.mhx1999.top/Article/details/gtezlcuwss.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenlongwang.top/Article/details/gtenddhpki.html

[R09] 字符串比较
来源：http://dali.snrcjt.cn/Article/details/gtrdcwunpj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtubyqpqrj.html

[R10] 正则匹配
来源：http://dali.zycfv.cn/Article/details/gtxvfacbqx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.bjfxy.top/Article/details/gtkwbjtivr.html

[R11] case 多分支
来源：http://dali.cashguo.top/Article/details/gtzijbtknq.html

case "$1" in
来源：http://dali.0kj1m.cn/Article/details/gtcpexlpum.html

start) echo "启动" ;;
来源：http://dali.c1oappe.top/Article/details/gtegyhckou.html

stop)  echo "停止" ;;
来源：http://dali.zycfv.cn/Article/details/gtmrennrod.html

*)     echo "未知命令" ;;
来源：http://dali.yueranfly.top/Article/details/gtwkqradzr.html

esac
来源：http://dali.yuanzhike.top/Article/details/gtsoyculkq.html

[R12] for 遍历文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylkkgijz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tanke756.top/Article/details/gtnueyxxsn.html

[R13] for 计数循环
来源：http://dali.wangshuangyany.cn/Article/details/gtbsenoznt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gtpxoxezlj.html

[R14] C 风格 for
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbckxnyc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtonszivzu.html

[R15] while 逐行读文件
来源：http://dali.yuxming.cn/Article/details/gtlcodjcmg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jqgufenzy.top/Article/details/gtwsxdrqwq.html

[R16] until 等待条件
来源：http://dali.yvedp.cn/Article/details/gtaisdxnfd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.fengsongda.top/Article/details/gteqmiivlx.html

[R17] 数组定义与取值
来源：http://dali.hnqzz.top/Article/details/gtlbpmipnx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhixingplan.top/Article/details/gthpibavtd.html

[R18] 遍历数组
来源：http://dali.xziqi.cn/Article/details/gtvulzqtwe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jiagoushi.top/Article/details/gtmywhbqob.html

[R19] 数组长度
来源：http://dali.sxryk.cn/Article/details/gtcvndkhau.html

echo "${#arr[@]}"
来源：http://dali.snrcjt.cn/Article/details/gtcwofqebz.html

[R20] 关联数组（字典）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcyjnboit.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sxryk.cn/Article/details/gtyxgteyrv.html

[R21] 字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtsqscjzlk.html

echo "${#s}"
来源：http://dali.pengpengdd.cyou/Article/details/gtsfcpnwac.html

[R22] 截取子串
来源：http://dali.haohaochexian.top/Article/details/gtuaghlqcf.html

echo "${s:0:5}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiznanlqd.html

[R23] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gttjjwqqhb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdahcyzn.html

[R24] 大小写转换
来源：http://dali.jinghuilouyu.cn/Article/details/gttlumwtyp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.bjfxy.top/Article/details/gtfrxlifpm.html

[R25] 去后缀 / 去前缀
来源：http://dali.sufxvd.cn/Article/details/gtuwfsjjpf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.dianchejie.cn/Article/details/gtzvairbao.html

[R26] 命令替换
来源：http://dali.xinyue.icu/Article/details/gtdoqcdclw.html

now=$(date +%F); echo "$now"
来源：http://dali.jlsjyb.cn/Article/details/gttlmqupqk.html

[R27] 算术展开
来源：http://dali.sufxvd.cn/Article/details/gtwvcmkgpo.html

echo $((1 + 2 * 3))
来源：http://dali.gaohongyu789.top/Article/details/gtnmpasmns.html

[R28] 浮点运算
来源：http://dali.shuidangran.top/Article/details/gtjuwzpizt.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhiwuduotai.top/Article/details/gtnfljvtxi.html

[R29] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtoumeayei.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gzhubu.top/Article/details/gtrsdzsdff.html

[R30] 函数返回状态码
来源：http://dali.316326.xyz/Article/details/gtukfejhaw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ivvv.top/Article/details/gtwkrwijev.html

[R31] 局部变量
来源：http://dali.nanxinkj.top/Article/details/gtfatquteq.html

f() { local x=1; echo "$x"; }
来源：http://dali.yongpay.top/Article/details/gtfjlhwscw.html

[R32] 参数个数校验
来源：http://dali.snrcjt.cn/Article/details/gtmdclefot.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gtgsexkiuq.html

[R33] 捕获错误并提示行号
来源：http://dali.haohaochexian.top/Article/details/gtnbvylpxf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj20258.top/Article/details/gteugjuabe.html

[R34] 退出时清理
来源：http://dali.tanke756.top/Article/details/gtkamcpxgg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gtxwlpylah.html

[R35] 后台执行并等待
来源：http://dali.jinqigufen.top/Article/details/gtiubagwzp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shuidangran.top/Article/details/gtcjkyksxp.html

[R36] 并发执行多个任务
来源：http://dali.xziqi.cn/Article/details/gtfudgdeaw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yangfankeji.com/Article/details/gtmfhpdajq.html

[R37] 把输出赋给变量
来源：http://dali.jqgufenzy.top/Article/details/gtedlfjhch.html

files=$(ls -1)
来源：http://dali.meibo888.top/Article/details/gtfkologep.html

[R38] 管道串联
来源：http://dali.daxiang520.top/Article/details/gtedhtraxk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.0kj1m.cn/Article/details/gtepezrmax.html

[R39] 重定向标准输出与错误
来源：http://dali.yuxming.cn/Article/details/gtpknruggk.html

cmd > out.log 2>&1
来源：http://dali.hfpthk.cn/Article/details/gtmqaerscw.html

[R40] 追加写日志
来源：http://dali.mhx1999.top/Article/details/gtbhjrfkmb.html

echo "log" >> out.log
来源：http://dali.yueranfly.top/Article/details/gtsyohzers.html

[R41] 丢弃输出
来源：http://dali.xinyue.icu/Article/details/gthfdrbzij.html

cmd >/dev/null 2>&1
来源：http://dali.haohaochexian.top/Article/details/gtlozwpcst.html

[R42] 输入重定向
来源：http://dali.yvedp.cn/Article/details/gttqiuvdtj.html

wc -l < a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtpbrnydhr.html

[R43] 按名字查找文件
来源：http://dali.shzxlz.cn/Article/details/gtpclvauox.html

find . -name "*.log" -type f
来源：http://dali.hysaishi.cn/Article/details/gtrlkzmrtx.html

[R44] 按修改时间查找
来源：http://dali.guowangkeji.top/Article/details/gtfwikruzj.html

find . -mtime -7 -type f
来源：http://dali.ivvv.top/Article/details/gtigxwnlzs.html

[R45] 批量删除
来源：http://dali.havefunace.top/Article/details/gtfgsloijs.html


<!-- 参考信息 -->