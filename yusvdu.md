代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pycfn.com/Article/details/gtzogkjyoz.html

);
来源：http://dali.yonumen.top/Article/details/gtuncwvnye.html

[Q02] 创建带外键的表
来源：http://dali.jyoumei.cn/Article/details/gtiyqtsvmo.html

CREATE TABLE orders (
来源：http://dali.hnxiangtu.top/Article/details/gtehmjzoil.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gaohongyu789.top/Article/details/gttgtpkqot.html

user_id INT NOT NULL,
来源：http://dali.xuetiantiany.cn/Article/details/gtakgsxbbf.html

amount DECIMAL(10, 2),
来源：http://dali.cqqwz.cn/Article/details/gtsegfghws.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrvtoiic.html

);
来源：http://dali.feifeiyinyue.top/Article/details/gtvfbtfirm.html

[Q03] 增加列
来源：http://dali.yongpay.top/Article/details/gtjmrfpioj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.0kj1m.cn/Article/details/gtosokpaho.html

[Q04] 修改列类型
来源：http://dali.cucudq.cn/Article/details/gtwyzzfroh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnxiangtu.top/Article/details/gtfqusdabb.html

[Q05] 重命名列
来源：http://dali.hammf.cn/Article/details/gtcobsmujo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.svipenyu.cn/Article/details/gtlwmlpjgn.html

[Q06] 删除列
来源：http://dali.tian-w.cn/Article/details/gtngiuetcv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.bjfxy.top/Article/details/gtkfovifql.html

[Q07] 删除表
来源：http://dali.gotoacloud.top/Article/details/gtwlxjaouw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenzaomai.com/Article/details/gtgtmednag.html

[Q08] 创建普通索引
来源：http://dali.jqgufenzy.top/Article/details/gtctcybuxl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gzhubu.top/Article/details/gthddcmddq.html

[Q09] 创建唯一索引
来源：http://dali.ivvv.top/Article/details/gtokavftsw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gtswjuktov.html

[Q10] 插入单行
来源：http://dali.ydzc1.top/Article/details/gtpufbhkrp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gtpkipblhp.html

[Q11] 一次插入多行
来源：http://dali.fengsongda.top/Article/details/gtadxghlqy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.fengsongda.top/Article/details/gthnydxsgp.html

[Q12] 插入后取自增 ID
来源：http://dali.daria6918.cn/Article/details/gtdjqtzecm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenjidiqi.icu/Article/details/gtzhywqrcc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gogol.net.cn/Article/details/gtiuscsmqc.html

[Q13] 忽略重复插入
来源：http://dali.quarkkingdee.top/Article/details/gtqxeapcwh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cashguo.top/Article/details/gtfefqxajb.html

[Q14] 存在则更新（upsert）
来源：http://dali.ehwqpu.com/Article/details/gtiossskqe.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.snrcjt.cn/Article/details/gtwpvkqbwg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.andypj.xyz/Article/details/gtctlhkwuq.html

[Q15] 查询全部
来源：http://dali.hnqzz.top/Article/details/gttohuried.html

SELECT * FROM users;
来源：http://dali.jiagoushi.top/Article/details/gttvannhpj.html

[Q16] 查询指定列
来源：http://dali.gogol.net.cn/Article/details/gtffjkjifg.html

SELECT id, name FROM users;
来源：http://dali.hammf.cn/Article/details/gtkuzmfsgx.html

[Q17] 条件查询
来源：http://dali.yuxming.cn/Article/details/gtfeuespee.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtqljcgtgy.html

[Q18] 模糊匹配
来源：http://dali.hysaishi.cn/Article/details/gtevcopjkb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xylfe.cn/Article/details/gtpfasqept.html

[Q19] 范围查询
来源：http://dali.yuxming.cn/Article/details/gtvorpsxzg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhengqikj.top/Article/details/gtibneolzw.html

[Q20] IN 列表
来源：http://dali.nanxinkj.top/Article/details/gtglqoyrpz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.wangdashe.top/Article/details/gtwgjsfbtu.html

[Q21] 空值判断
来源：http://dali.hfpthk.cn/Article/details/gtvjntrmaq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cheryme.top/Article/details/gtfxqufpdk.html

[Q22] 排序
来源：http://dali.andypj.xyz/Article/details/gtbevifgjb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sweek.top/Article/details/gtpypgbzxj.html

[Q23] 分页
来源：http://dali.yonumen.top/Article/details/gthuwhnhna.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xziqi.cn/Article/details/gtivrxwckc.html

[Q24] 去重
来源：http://dali.zdqjudy.top/Article/details/gtgozrzbcg.html

SELECT DISTINCT city FROM users;
来源：http://dali.guannengcc.top/Article/details/gtlwnaevrf.html

[Q25] 只取前 N 条
来源：http://dali.snrcjt.cn/Article/details/gtttoxsesa.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nanxinkj.top/Article/details/gtvwtalfcr.html

[Q26] 计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpicarsb.html

SELECT COUNT(*) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtinfranoc.html

[Q27] 条件计数
来源：http://dali.yuxming.cn/Article/details/gtkxcpqmyf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yvedp.cn/Article/details/gtzartspra.html

[Q28] 求和与平均
来源：http://dali.yvedp.cn/Article/details/gtkexuchwe.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtspartnjv.html

[Q29] 最大最小值
来源：http://dali.c1oappe.top/Article/details/gthgcvsnxb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtsbzjloso.html

[Q30] 分组统计
来源：http://dali.kuanghao11.cn/Article/details/gtzyuqytjv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gtldtzjcfz.html

[Q31] 分组后过滤
来源：http://dali.316326.xyz/Article/details/gtvjdvrled.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgufenzy.top/Article/details/gtyngtprtd.html

[Q32] 分组拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtrevubrva.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gttgdbezfb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cqqwz.cn/Article/details/gtoflebdso.html

[Q33] 多列分组
来源：http://dali.aibaodan.cn/Article/details/gtqastzokg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.0kj1m.cn/Article/details/gtxmlzujhp.html

[Q34] 每组取第一条
来源：http://dali.wangdashe.top/Article/details/gtzxbekzax.html

SELECT * FROM (
来源：http://dali.cqqwz.cn/Article/details/gtarkghtvl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.redwolf501.top/Article/details/gtqbdbjlgj.html

) t WHERE rn = 1;
来源：http://dali.cdnleiting.top/Article/details/gtkhqxhved.html

[Q35] 内连接
来源：http://dali.sufxvd.cn/Article/details/gtiojjozvp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yangfankeji.com/Article/details/gtdetrexug.html

[Q36] 左连接
来源：http://dali.ivvv.top/Article/details/gtndzzleom.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.mhx1999.top/Article/details/gtcbrjfapo.html

[Q37] 右连接
来源：http://dali.cdnleiting.top/Article/details/gtgbzcqpym.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhoulong.xyz/Article/details/gtwvwhibtx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yonumen.top/Article/details/gtdqrspbpt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yanxiufei.cn/Article/details/gtaszoopek.html

[Q39] 自连接（查上下级）
来源：http://dali.zhengqikj.top/Article/details/gtbqyprhns.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhengqikj.top/Article/details/gthwdumeed.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aibaodan.cn/Article/details/gtooikqftm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yuxming.cn/Article/details/gtcnslcapm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.fengsongda.top/Article/details/gthurklmzo.html

[Q41] 多表连接
来源：http://dali.daxiang520.top/Article/details/gtwgmektsh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhoulong.xyz/Article/details/gtybsuefct.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shzxlz.cn/Article/details/gtqikzrrny.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ydzc1.top/Article/details/gtirjcnfql.html

[Q42] 连接条件附加过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtnbcphxfl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.pycfn.com/Article/details/gtsnozgkur.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cdnleiting.top/Article/details/gtvcsujbgv.html

[Q43] 标量子查询
来源：http://dali.fengsongda.top/Article/details/gtfssddhuo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenlongwang.top/Article/details/gtqdentjhm.html

[Q44] IN 子查询
来源：http://dali.sxryk.cn/Article/details/gtrwsmjwyp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.andypj.xyz/Article/details/gtnjaamizs.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxuanxn.top/Article/details/gtakrrgtto.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tanke756.top/Article/details/gtfxywsxoe.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangshuangyany.cn/Article/details/gtmcqedufe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigfzy.top/Article/details/gtxlsebnpw.html

[Q47] 与平均值比较
来源：http://dali.hammf.cn/Article/details/gtpumgkwko.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fengsongda.top/Article/details/gtxgfjqadq.html

[Q48] CTE 公用表表达式
来源：http://dali.jlsjyb.cn/Article/details/gtiukubnya.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hfpthk.cn/Article/details/gtkkbckkwh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jyoumei.cn/Article/details/gtfcukbqni.html

[Q49] 更新单行
来源：http://dali.nanxuanxn.top/Article/details/gtqsscgclz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gthnvvvgcw.html

[Q50] 批量更新
来源：http://dali.gotoacloud.top/Article/details/gttpjsxmad.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.0kj1m.cn/Article/details/gthfgmfvta.html

[Q51] 用子查询更新
来源：http://dali.zhoulong.xyz/Article/details/gtxgezzsjw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtsnxpicvo.html

[Q52] 删除指定行
来源：http://dali.dianchejie.cn/Article/details/gtcklzfcmc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yangfankeji.com/Article/details/gtxbexcdeg.html

[Q53] 按条件删除
来源：http://dali.cheryme.top/Article/details/gtnlmipkjz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.haohaochexian.top/Article/details/gtnmhmzldi.html

[Q54] 清空表
来源：http://dali.xuanzx.com/Article/details/gtphtyuhmo.html

TRUNCATE TABLE logs;
来源：http://dali.zhengqikj.top/Article/details/gtesojfqxl.html

[Q55] 排名（并列占位）
来源：http://dali.yonumen.top/Article/details/gteisygzzb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gtehzbampy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cucudq.cn/Article/details/gtzpgpyybc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sysykeji.top/Article/details/gtycikgxli.html

[Q57] 行号
来源：http://dali.cucudq.cn/Article/details/gtpdccrycf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtuptnugms.html

[Q58] 累计求和
来源：http://dali.daxiang520.top/Article/details/gtdjyrfryk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtpsdrfghy.html

[Q59] 分组内累计
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvosjgkg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj202588.top/Article/details/gtjjtllpbw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gtydeuulxm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nwbrower.top/Article/details/gtffnnhipv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258.top/Article/details/gtdpcnzcbl.html

[Q61] 移动平均
来源：http://dali.ivvv.top/Article/details/gtiglczhsr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtwgpbgstr.html

[Q62] 分组占比
来源：http://dali.hfpthk.cn/Article/details/gtertwvmvv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gtdcqeyvkr.html

[Q63] 开启事务
来源：http://dali.chenzaomai.com/Article/details/gtmzdrboju.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cdnleiting.top/Article/details/gttxdjdcxm.html

[Q64] 提交事务
来源：http://dali.hysaishi.cn/Article/details/gtvqkdcubz.html

COMMIT;
来源：http://dali.xinyue.icu/Article/details/gtrmafehig.html

[Q65] 回滚事务
来源：http://dali.c1oappe.top/Article/details/gtvgwgzoka.html

ROLLBACK;
来源：http://dali.hammf.cn/Article/details/gtdxjytixy.html

[Q66] 行锁查询
来源：http://dali.vqdsnc.cn/Article/details/gtjngjmhdj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.quarkkingdee.top/Article/details/gtmzqootgd.html

[Q67] 设置隔离级别
来源：http://dali.birdmap.top/Article/details/gtktudifzq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yongpay.top/Article/details/gtxqoiotzw.html

[Q68] 保存点
来源：http://dali.chenlongwang.top/Article/details/gtpwplxlvt.html

SAVEPOINT sp1;
来源：http://dali.feifeiyinyue.top/Article/details/gtkubbvrmq.html

ROLLBACK TO sp1;
来源：http://dali.wangshuangyany.cn/Article/details/gtosvqrbvs.html

[Q69] 查看执行计划
来源：http://dali.andypj.xyz/Article/details/gtgtqlypkh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jiagoushi.top/Article/details/gtemjxwubv.html

[Q70] 更新统计信息
来源：http://dali.shzxlz.cn/Article/details/gtpaenrafc.html

ANALYZE TABLE users;
来源：http://dali.cdnleiting.top/Article/details/gtifvznody.html

[Q71] 查看建表语句
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkuatazo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cashguo.top/Article/details/gtgwefcxeh.html

[Q72] 查看索引
来源：http://dali.9152youxi.cn/Article/details/gtvtlykzvr.html

SHOW INDEX FROM users;
来源：http://dali.jianghu66.top/Article/details/gtwxilptuo.html

[Q73] 查看表状态
来源：http://dali.tianlin.xyz/Article/details/gthtsuhtqh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.andypj.xyz/Article/details/gtlzzlyzfy.html

[Q74] 强制使用索引
来源：http://dali.sweek.top/Article/details/gtmlmxrdlj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuygmjcig.html

[Q75] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gtzlzlgnyz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtrgdcsfjn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shuidangran.top/Article/details/gtbsvhkmvr.html

[Q76] 按天统计
来源：http://dali.dianchejie.cn/Article/details/gtqdjsiymu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gtzqtcazvs.html

[Q77] 时间加减
来源：http://dali.jinqigfzy.top/Article/details/gtglpjgabq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xziqi.cn/Article/details/gtinulybxk.html

[Q78] 当前时间
来源：http://dali.meibo888.top/Article/details/gtkqbbngtr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.dianchejie.cn/Article/details/gthgqzchhz.html

[Q79] 字符串拼接
来源：http://dali.hnqzz.top/Article/details/gtspbdggjw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.snrcjt.cn/Article/details/gtmwchudtn.html

[Q80] 字符串截取
来源：http://dali.jinqigfzy.top/Article/details/gtsamztgpv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtribbnmlz.html

[Q81] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gtahhnequs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gogol.net.cn/Article/details/gttlqdovpr.html

[Q82] 字符长度与字节长度
来源：http://dali.c1oappe.top/Article/details/gtghrfhflt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtosuvdnya.html

[Q83] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gteggpjtgi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gtqjraowth.html

[Q84] 去除首尾空格
来源：http://dali.ydzc1.top/Article/details/gtqjbynmxy.html

SELECT TRIM(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gthzgwvbpv.html

[Q85] 数值取整
来源：http://dali.jinqigufen.top/Article/details/gtardwviww.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangshuangyany.cn/Article/details/gtrmylnerf.html

[Q86] 读取 JSON 字段
来源：http://dali.ydzc1.top/Article/details/gtkthgydlx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aibaodan.cn/Article/details/gtgmxbndeb.html

[Q87] JSON 字段做条件
来源：http://dali.pycfn.com/Article/details/gtqqvxpvvr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ybcxt.top/Article/details/gtkobalzey.html

[Q88] 行转列（条件聚合）
来源：http://dali.cdnleiting.top/Article/details/gtduifshlb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.meibo888.top/Article/details/gteutfrffe.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtpzkppbbs.html

[Q89] 判断表是否存在
来源：http://dali.wangshuangyany.cn/Article/details/gtagtbcjjt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jyoumei.cn/Article/details/gtvfqofixs.html

[Q90] 生成序号列
来源：http://dali.hnqzz.top/Article/details/gtgllwrqxg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aizwys.cn/Article/details/gtxitnkkzs.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtnszrnxpe.html

R. Bash 专题
来源：http://dali.vqdsnc.cn/Article/details/gtyxisqvqa.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtitczadpb.html

[R01] shebang 与严格模式
来源：http://dali.aizwys.cn/Article/details/gtbmegfcps.html

#!/usr/bin/env bash
来源：http://dali.cqqwz.cn/Article/details/gtwrnnadfp.html

set -euo pipefail
来源：http://dali.sysykeji.top/Article/details/gtauqostmg.html

[R02] 变量赋值与使用
来源：http://dali.meibo888.top/Article/details/gtkfborwtg.html

name="Tom"; echo "$name"
来源：http://dali.pengpengdd.cyou/Article/details/gtgrtidyqz.html

[R03] 只读变量
来源：http://dali.shuidangran.top/Article/details/gtmvhrghhr.html

readonly PI=3.14
来源：http://dali.jyoumei.cn/Article/details/gtifmkomhl.html

[R04] 位置参数
来源：http://dali.cqqwz.cn/Article/details/gtcbuyitpb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pycfn.com/Article/details/gtcxcsbxdg.html

[R05] 参数默认值
来源：http://dali.fengsongda.top/Article/details/gtritygpry.html

name="${1:-default}"
来源：http://dali.sysykeji.top/Article/details/gtxogjgmfl.html

[R06] 判断命令是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gtyntkhnaw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gtljqiduuk.html

[R07] if 判断文件
来源：http://dali.gzhubu.top/Article/details/gtjpagszwy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cqqwz.cn/Article/details/gtomlypaza.html

[R08] 数值比较
来源：http://dali.fengsongda.top/Article/details/gtyscmrydo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tanke756.top/Article/details/gtwbykvekm.html

[R09] 字符串比较
来源：http://dali.tian-w.cn/Article/details/gtdfimpjxe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jyoumei.cn/Article/details/gtvuxxsfcb.html

[R10] 正则匹配
来源：http://dali.svipenyu.cn/Article/details/gttbenimin.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ydzc1.top/Article/details/gtcegehvqv.html

[R11] case 多分支
来源：http://dali.sweek.top/Article/details/gtsljshucy.html

case "$1" in
来源：http://dali.jqgufenzy.top/Article/details/gtouflbdqf.html

start) echo "启动" ;;
来源：http://dali.yonumen.top/Article/details/gtjyjxdxuf.html

stop)  echo "停止" ;;
来源：http://dali.yj20258888.top/Article/details/gtisuypsvr.html

*)     echo "未知命令" ;;
来源：http://dali.redwolf501.top/Article/details/gtyhspmzos.html

esac
来源：http://dali.shzxlz.cn/Article/details/gtmleselhi.html

[R12] for 遍历文件
来源：http://dali.cashguo.top/Article/details/gtmahlqaky.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhongyouzk.top/Article/details/gtjmbpxebs.html

[R13] for 计数循环
来源：http://dali.yueranfly.top/Article/details/gtwxmhtzdw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtfzqjzedx.html

[R14] C 风格 for
来源：http://dali.daria6918.cn/Article/details/gtjnpwjojf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.mhx1999.top/Article/details/gtyuwkxpmb.html

[R15] while 逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtpuovdkyi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenlongwang.top/Article/details/gtxcmmbfqi.html

[R16] until 等待条件
来源：http://dali.xziqi.cn/Article/details/gtachgwwce.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.aizwys.cn/Article/details/gtkvqhemjt.html

[R17] 数组定义与取值
来源：http://dali.aizwys.cn/Article/details/gtkhgfdpow.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhiwuduotai.top/Article/details/gtzfigtfkv.html

[R18] 遍历数组
来源：http://dali.chenlongwang.top/Article/details/gtstvpwfdb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenlongwang.top/Article/details/gtzfmdxzrc.html

[R19] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gtnzzfupie.html

echo "${#arr[@]}"
来源：http://dali.yj202588.top/Article/details/gtagakwhej.html

[R20] 关联数组（字典）
来源：http://dali.hongshengwenyu.top/Article/details/gttycrtpay.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ydzc1.top/Article/details/gtcmiicaey.html

[R21] 字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gtgkeojarj.html

echo "${#s}"
来源：http://dali.yvedp.cn/Article/details/gtyuaprecy.html

[R22] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gtnskxuvix.html

echo "${s:0:5}"
来源：http://dali.cashguo.top/Article/details/gthmgaabiy.html

[R23] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gtgecchhjz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.haohaochexian.top/Article/details/gtbmmydgvu.html

[R24] 大小写转换
来源：http://dali.yj20258.top/Article/details/gthtzujhwa.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.snrcjt.cn/Article/details/gtoqfwzkbx.html

[R25] 去后缀 / 去前缀
来源：http://dali.cashguo.top/Article/details/gtdzaqegbj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yonumen.top/Article/details/gtfqrvqzjm.html

[R26] 命令替换
来源：http://dali.shangyingyoupin.top/Article/details/gtxxjvmczn.html

now=$(date +%F); echo "$now"
来源：http://dali.fzhhl.top/Article/details/gtnpwcledt.html

[R27] 算术展开
来源：http://dali.hywenlv.cn/Article/details/gtxnscxvvi.html

echo $((1 + 2 * 3))
来源：http://dali.guowangkeji.top/Article/details/gtbfslvexj.html

[R28] 浮点运算
来源：http://dali.zhoulong.xyz/Article/details/gtozvutdkt.html

echo "scale=2; 10/3" | bc
来源：http://dali.hammf.cn/Article/details/gtbbxfdvgp.html

[R29] 定义函数
来源：http://dali.zhixingplan.top/Article/details/gtmfcqcolw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.andypj.xyz/Article/details/gtohcgdgvp.html

[R30] 函数返回状态码
来源：http://dali.meibo888.top/Article/details/gthspzrdbh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zdqjudy.top/Article/details/gtdeyycsvq.html

[R31] 局部变量
来源：http://dali.gogol.net.cn/Article/details/gtegimugiy.html

f() { local x=1; echo "$x"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtwtovdpln.html

[R32] 参数个数校验
来源：http://dali.chenjidiqi.icu/Article/details/gtcaubtxqf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gtttxqvhdv.html

[R33] 捕获错误并提示行号
来源：http://dali.iojbl.cn/Article/details/gtljgvilem.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.andypj.xyz/Article/details/gtbivuzvty.html

[R34] 退出时清理
来源：http://dali.haohaochexian.top/Article/details/gtinewbneb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuanzhike.top/Article/details/gtskmjscvz.html

[R35] 后台执行并等待
来源：http://dali.ehwqpu.com/Article/details/gtqgbsuami.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dashuyun.cn/Article/details/gtkmydaboj.html

[R36] 并发执行多个任务
来源：http://dali.dianchejie.cn/Article/details/gtbtusgkdv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shanyushiyangtech.top/Article/details/gtfzjszyvx.html

[R37] 把输出赋给变量
来源：http://dali.mhx1999.top/Article/details/gtrswhyniy.html

files=$(ls -1)
来源：http://dali.jlsjyb.cn/Article/details/gtbxrnlpdo.html

[R38] 管道串联
来源：http://dali.wangdashe.top/Article/details/gtsrliscam.html

cat a.txt | grep -i error | wc -l
来源：http://dali.havefunace.top/Article/details/gtqsuwckbx.html

[R39] 重定向标准输出与错误
来源：http://dali.c1oappe.top/Article/details/gtapbjntkw.html

cmd > out.log 2>&1
来源：http://dali.havefunace.top/Article/details/gtfjyirbcx.html

[R40] 追加写日志
来源：http://dali.cheryme.top/Article/details/gtacthcmiu.html

echo "log" >> out.log
来源：http://dali.jyoumei.cn/Article/details/gtwspmlthy.html

[R41] 丢弃输出
来源：http://dali.gzhubu.top/Article/details/gtiynvjcpa.html

cmd >/dev/null 2>&1
来源：http://dali.zycfv.cn/Article/details/gtglxmnqxa.html

[R42] 输入重定向
来源：http://dali.cucudq.cn/Article/details/gtzdqcxsau.html

wc -l < a.txt
来源：http://dali.cucudq.cn/Article/details/gtibpqouuu.html

[R43] 按名字查找文件
来源：http://dali.ybcxt.top/Article/details/gthmkfnqvz.html

find . -name "*.log" -type f
来源：http://dali.0kj1m.cn/Article/details/gtaqbkrmhq.html

[R44] 按修改时间查找
来源：http://dali.yueranfly.top/Article/details/gtiaodgmce.html

find . -mtime -7 -type f
来源：http://dali.shuidangran.top/Article/details/gtvpmebidi.html

[R45] 批量删除
来源：http://dali.chenjidiqi.icu/Article/details/gtnmcizghb.html

find . -name "*.tmp" -delete
来源：http://dali.hongshengwenyu.top/Article/details/gtgniotpen.html

[R46] 递归替换文件内容
来源：http://dali.sufxvd.cn/Article/details/gtwbuazkxv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangdashe.top/Article/details/gtybraznql.html

[R47] sed 单行替换
来源：http://dali.jqgfzy.top/Article/details/gtlxmhgxnt.html


<!-- 参考信息 -->