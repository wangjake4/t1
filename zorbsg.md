代发 wailian999

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtsvtlziue.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenlongwang.top/Article/details/gtgdqbtxyy.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gteaxjvoet.html

[Q01] 创建表
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmquilkx.html

CREATE TABLE users (
来源：http://dali.316326.xyz/Article/details/gtrmadfgjb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhixingplan.top/Article/details/gtafeoxhhh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tianlin.xyz/Article/details/gtlbojpopk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ivvv.top/Article/details/gtzpsnhxvi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cdnleiting.top/Article/details/gtdvhovnrq.html

);
来源：http://dali.jinqigufen.top/Article/details/gtkpnmhdbz.html

[Q02] 创建带外键的表
来源：http://dali.nanxuanxn.top/Article/details/gtztrjblhk.html

CREATE TABLE orders (
来源：http://dali.xuanzx.com/Article/details/gtdgjjblyn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sweek.top/Article/details/gtwhhjfbkt.html

user_id INT NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gtstoltfdi.html

amount DECIMAL(10, 2),
来源：http://dali.sufxvd.cn/Article/details/gtxexyoecr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yuxming.cn/Article/details/gtqygofslb.html

);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvicvabv.html

[Q03] 增加列
来源：http://dali.jinqigufen.top/Article/details/gtpwfyouwz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.haohaochexian.top/Article/details/gtqeowlxxg.html

[Q04] 修改列类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfadpjby.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.redwolf501.top/Article/details/gtyzbcuoia.html

[Q05] 重命名列
来源：http://dali.yvedp.cn/Article/details/gtrrgzjhrn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ydzc1.top/Article/details/gtawbflqvv.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gtmnoqbeuw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ydzc1.top/Article/details/gtysxoxkkx.html

[Q07] 删除表
来源：http://dali.guowangkeji.top/Article/details/gtaqtchnpn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hysaishi.cn/Article/details/gtdwstjlva.html

[Q08] 创建普通索引
来源：http://dali.svipenyu.cn/Article/details/gtroluymjn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cqqwz.cn/Article/details/gteozqrodl.html

[Q09] 创建唯一索引
来源：http://dali.guowangkeji.top/Article/details/gtxwyleylf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuanzx.com/Article/details/gtqphsycbt.html

[Q10] 插入单行
来源：http://dali.xylfe.cn/Article/details/gtbhasbsyz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.wangdashe.top/Article/details/gtbtnmafjg.html

[Q11] 一次插入多行
来源：http://dali.haohaochexian.top/Article/details/gtdpobnkqv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gtpseeunos.html

[Q12] 插入后取自增 ID
来源：http://dali.yongpay.top/Article/details/gtvjtqmxsp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.iojbl.cn/Article/details/gtyajgjzzx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hysaishi.cn/Article/details/gtfpeozrso.html

[Q13] 忽略重复插入
来源：http://dali.yueranfly.top/Article/details/gtbwtbrcfg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.andypj.xyz/Article/details/gtkhuqyfzh.html

[Q14] 存在则更新（upsert）
来源：http://dali.andypj.xyz/Article/details/gtijgmfoqz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tianlin.xyz/Article/details/gtdgzlrlpk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfboocmw.html

[Q15] 查询全部
来源：http://dali.hnxiangtu.top/Article/details/gtxwzjgbkx.html

SELECT * FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtymnzbfiv.html

[Q16] 查询指定列
来源：http://dali.yongpay.top/Article/details/gthyrpimkw.html

SELECT id, name FROM users;
来源：http://dali.meibo888.top/Article/details/gtfjqguizr.html

[Q17] 条件查询
来源：http://dali.yongpay.top/Article/details/gtlqcxaftp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtdvgaxiqf.html

[Q18] 模糊匹配
来源：http://dali.tanke756.top/Article/details/gtajmugwhy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxuanxn.top/Article/details/gteldyklyt.html

[Q19] 范围查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkporesm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cdnleiting.top/Article/details/gtcawmmxil.html

[Q20] IN 列表
来源：http://dali.smart0.xyz/Article/details/gtvvrfurat.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shzxlz.cn/Article/details/gtsaxneaee.html

[Q21] 空值判断
来源：http://dali.redwolf501.top/Article/details/gtfktkpqtx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenzaomai.com/Article/details/gtnfqrxqqp.html

[Q22] 排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtmlpqcx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fengsongda.top/Article/details/gtjnaqvcuf.html

[Q23] 分页
来源：http://dali.nanxinkj.top/Article/details/gtqorliplu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xinyue.icu/Article/details/gtmxneygjp.html

[Q24] 去重
来源：http://dali.haohaochexian.top/Article/details/gtqbrveqso.html

SELECT DISTINCT city FROM users;
来源：http://dali.tian-w.cn/Article/details/gtkufpsymp.html

[Q25] 只取前 N 条
来源：http://dali.yj202588.top/Article/details/gtovzjvthu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shuidangran.top/Article/details/gtkwbtivxf.html

[Q26] 计数
来源：http://dali.yj20258888.top/Article/details/gtynnzwlky.html

SELECT COUNT(*) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtafczeixt.html

[Q27] 条件计数
来源：http://dali.zhoulong.xyz/Article/details/gtoduygepx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtefzoxggr.html

[Q28] 求和与平均
来源：http://dali.shuidangran.top/Article/details/gtvgkalwvu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtxizhkyhg.html

[Q29] 最大最小值
来源：http://dali.9152youxi.cn/Article/details/gtklilpdeb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtignqfqvr.html

[Q30] 分组统计
来源：http://dali.iojbl.cn/Article/details/gtpbejzrpc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gtdwvonshj.html

[Q31] 分组后过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtqmhblprb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.smart0.xyz/Article/details/gtldraqevv.html

[Q32] 分组拼接字符串
来源：http://dali.xuanzx.com/Article/details/gtdsjetifh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gtfoyahfug.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nanxinkj.top/Article/details/gtqrztqosb.html

[Q33] 多列分组
来源：http://dali.hongshengwenyu.top/Article/details/gtxdmbvqhd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.316326.xyz/Article/details/gtatpvapwq.html

[Q34] 每组取第一条
来源：http://dali.jlsjyb.cn/Article/details/gtnqlkojzm.html

SELECT * FROM (
来源：http://dali.wangshuangyany.cn/Article/details/gtvqshwpsg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwuttiqy.html

) t WHERE rn = 1;
来源：http://dali.xziqi.cn/Article/details/gtnutftxut.html

[Q35] 内连接
来源：http://dali.pycfn.com/Article/details/gtvdmguwiu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gtovupczcc.html

[Q36] 左连接
来源：http://dali.nwbrower.top/Article/details/gtcmwygbfo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gtucsntiku.html

[Q37] 右连接
来源：http://dali.dianchejie.cn/Article/details/gtjscveqma.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcomnsyiv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aizwys.cn/Article/details/gtdmkdbugp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jiagoushi.top/Article/details/gtmnarwdii.html

[Q39] 自连接（查上下级）
来源：http://dali.chenlongwang.top/Article/details/gtoqcgjtms.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.havefunace.top/Article/details/gtdudpgluq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.pengpengdd.cyou/Article/details/gtbjgflvbg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hfpthk.cn/Article/details/gtkbzwkdkl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.iojbl.cn/Article/details/gttpjdfwpq.html

[Q41] 多表连接
来源：http://dali.hnqzz.top/Article/details/gtjnthjcqi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sxryk.cn/Article/details/gtbxnaicqx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.aizwys.cn/Article/details/gtuhjcqjrq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jqgufenzy.top/Article/details/gtdjukzsju.html

[Q42] 连接条件附加过滤
来源：http://dali.chenlongwang.top/Article/details/gtswisfpqa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnxiangtu.top/Article/details/gtttuczgzs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hywenlv.cn/Article/details/gtsivzxayz.html

[Q43] 标量子查询
来源：http://dali.xylfe.cn/Article/details/gthgolaunn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.tanke756.top/Article/details/gtkeeqeviw.html

[Q44] IN 子查询
来源：http://dali.kuanghao11.cn/Article/details/gtktegofzs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ivvv.top/Article/details/gthnrohlmu.html

[Q45] EXISTS 判断存在
来源：http://dali.jqgfzy.top/Article/details/gtmekuunxz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gtolqbgasu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cucudq.cn/Article/details/gtlnqewzlr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuxming.cn/Article/details/gtshazdwnx.html

[Q47] 与平均值比较
来源：http://dali.zdqjudy.top/Article/details/gtyfikkxiq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cucudq.cn/Article/details/gtarmaqncv.html

[Q48] CTE 公用表表达式
来源：http://dali.yonumen.top/Article/details/gtrpmoajjc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.mhx1999.top/Article/details/gtbglwstle.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jlsjyb.cn/Article/details/gtxereucyu.html

[Q49] 更新单行
来源：http://dali.redwolf501.top/Article/details/gtewtliduv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.0kj1m.cn/Article/details/gtplesykul.html

[Q50] 批量更新
来源：http://dali.pengpengdd.cyou/Article/details/gtjbwaklho.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hysaishi.cn/Article/details/gtctmcbxmd.html

[Q51] 用子查询更新
来源：http://dali.ybcxt.top/Article/details/gtmwrthetr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yonumen.top/Article/details/gtveaykihd.html

[Q52] 删除指定行
来源：http://dali.bjfxy.top/Article/details/gtwpqhzzxw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gtagitmjbw.html

[Q53] 按条件删除
来源：http://dali.nanxuanxn.top/Article/details/gttjqedvga.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gtvxvwdfvq.html

[Q54] 清空表
来源：http://dali.yj20258.top/Article/details/gtrwcxfeva.html

TRUNCATE TABLE logs;
来源：http://dali.kuanghao11.cn/Article/details/gtmaqdvvph.html

[Q55] 排名（并列占位）
来源：http://dali.shzxlz.cn/Article/details/gtkfcmdnrs.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gtdjfppokt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jlsjyb.cn/Article/details/gtgcakwbun.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpetisnzp.html

[Q57] 行号
来源：http://dali.hfpthk.cn/Article/details/gtzkbslons.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.mhx1999.top/Article/details/gtqnqpttyv.html

[Q58] 累计求和
来源：http://dali.jqgfzy.top/Article/details/gtgpzkocsx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtdyjbckml.html

[Q59] 分组内累计
来源：http://dali.iojbl.cn/Article/details/gtjlugwenu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtswxldyjl.html

[Q60] 取上一行 / 下一行
来源：http://dali.ppjwa.cn/Article/details/gtawnojefn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jianghu66.top/Article/details/gtmofpdxgl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ivvv.top/Article/details/gtqssoitqz.html

[Q61] 移动平均
来源：http://dali.tianlin.xyz/Article/details/gtckdxtaqq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtokwrffgu.html

[Q62] 分组占比
来源：http://dali.tanke756.top/Article/details/gtlyvanhtu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gtoiljmnzc.html

[Q63] 开启事务
来源：http://dali.yj20258888.top/Article/details/gtgmmtlpog.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shuidangran.top/Article/details/gtzxxqfdse.html

[Q64] 提交事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbpelsky.html

COMMIT;
来源：http://dali.sweek.top/Article/details/gtfowkixpw.html

[Q65] 回滚事务
来源：http://dali.redwolf501.top/Article/details/gtcbzstgis.html

ROLLBACK;
来源：http://dali.cashguo.top/Article/details/gtllfzjwmh.html

[Q66] 行锁查询
来源：http://dali.gaohongyu789.top/Article/details/gtbtitdzck.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cucudq.cn/Article/details/gttuvcvklz.html

[Q67] 设置隔离级别
来源：http://dali.zdqjudy.top/Article/details/gtgtrfcsyx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tianlin.xyz/Article/details/gtoirwcfdd.html

[Q68] 保存点
来源：http://dali.yuanzhike.top/Article/details/gtgllrcckb.html

SAVEPOINT sp1;
来源：http://dali.redwolf501.top/Article/details/gtmtsmywmb.html

ROLLBACK TO sp1;
来源：http://dali.xuanzx.com/Article/details/gtlrhjethi.html

[Q69] 查看执行计划
来源：http://dali.9152youxi.cn/Article/details/gtthjxydck.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xziqi.cn/Article/details/gtnekwqbjn.html

[Q70] 更新统计信息
来源：http://dali.chenlongwang.top/Article/details/gtibpxvgiq.html

ANALYZE TABLE users;
来源：http://dali.aizwys.cn/Article/details/gtjnnezsso.html

[Q71] 查看建表语句
来源：http://dali.cashguo.top/Article/details/gtlfliotdz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shzxlz.cn/Article/details/gtevtamxqo.html

[Q72] 查看索引
来源：http://dali.ehwqpu.com/Article/details/gtbumtvuxj.html

SHOW INDEX FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtqqhyirqg.html

[Q73] 查看表状态
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfpwqirf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangdashe.top/Article/details/gtctjnpehy.html

[Q74] 强制使用索引
来源：http://dali.smart0.xyz/Article/details/gtxplqjnnp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jlsjyb.cn/Article/details/gteavhsrru.html

[Q75] 日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujskbbeo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cashguo.top/Article/details/gtavteqhoc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.quarkkingdee.top/Article/details/gtdzywbrim.html

[Q76] 按天统计
来源：http://dali.guowangkeji.top/Article/details/gtbnztgsmr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gzhubu.top/Article/details/gtitlhelra.html

[Q77] 时间加减
来源：http://dali.aizwys.cn/Article/details/gtwsbkojyk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dianchejie.cn/Article/details/gtoppaofgn.html

[Q78] 当前时间
来源：http://dali.zhoulong.xyz/Article/details/gtlrivkmml.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuanzx.com/Article/details/gtyjkirors.html

[Q79] 字符串拼接
来源：http://dali.xinyue.icu/Article/details/gtuunrzrnj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cucudq.cn/Article/details/gtjpnrphsd.html

[Q80] 字符串截取
来源：http://dali.andypj.xyz/Article/details/gtzmrnkhhb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtgkdyjeom.html

[Q81] 字符串替换
来源：http://dali.iojbl.cn/Article/details/gtmiumhgpc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.bjfxy.top/Article/details/gtbcztcimo.html

[Q82] 字符长度与字节长度
来源：http://dali.daria6918.cn/Article/details/gtokmrranq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtafbevjtg.html

[Q83] 大小写转换
来源：http://dali.ydzc1.top/Article/details/gtqmgxwbzq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtgghrbikk.html

[Q84] 去除首尾空格
来源：http://dali.gotoacloud.top/Article/details/gtnyopjtja.html

SELECT TRIM(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzblgmag.html

[Q85] 数值取整
来源：http://dali.gogol.net.cn/Article/details/gtjhkmmxcj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yanxiufei.cn/Article/details/gtiaiqolvd.html

[Q86] 读取 JSON 字段
来源：http://dali.ppjwa.cn/Article/details/gtjduquglx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.9152youxi.cn/Article/details/gtuqiipyeh.html

[Q87] JSON 字段做条件
来源：http://dali.dianchejie.cn/Article/details/gttwyhqidi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.andypj.xyz/Article/details/gtriifpqgm.html

[Q88] 行转列（条件聚合）
来源：http://dali.bjfxy.top/Article/details/gtqytrbfyu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yvedp.cn/Article/details/gtmqwusska.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtrqqrxuie.html

[Q89] 判断表是否存在
来源：http://dali.ehwqpu.com/Article/details/gtupqldedk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.bjfxy.top/Article/details/gtppgeebfb.html

[Q90] 生成序号列
来源：http://dali.guannengcc.top/Article/details/gtymkfdkdl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aibaodan.cn/Article/details/gtnyhxedxi.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtmgfyhqtt.html

R. Bash 专题
来源：http://dali.jinqigufen.top/Article/details/gtfnrkyija.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtsfasfxoz.html

[R01] shebang 与严格模式
来源：http://dali.9152youxi.cn/Article/details/gtlbmybcum.html

#!/usr/bin/env bash
来源：http://dali.cucudq.cn/Article/details/gtsrbbopwa.html

set -euo pipefail
来源：http://dali.9152youxi.cn/Article/details/gthqkplavm.html

[R02] 变量赋值与使用
来源：http://dali.cqqwz.cn/Article/details/gtodksgcib.html

name="Tom"; echo "$name"
来源：http://dali.wangshuangyany.cn/Article/details/gtttznoqvv.html

[R03] 只读变量
来源：http://dali.hfpthk.cn/Article/details/gtrgjdwrwb.html

readonly PI=3.14
来源：http://dali.316326.xyz/Article/details/gtegksrijv.html

[R04] 位置参数
来源：http://dali.zhoulong.xyz/Article/details/gtbwphrhbx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhoulong.xyz/Article/details/gtxnmjntji.html

[R05] 参数默认值
来源：http://dali.chenjidiqi.icu/Article/details/gtdazfbqfr.html

name="${1:-default}"
来源：http://dali.yj20258.top/Article/details/gtflkmjfea.html

[R06] 判断命令是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyerwvfwh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gogol.net.cn/Article/details/gtacjwrnaq.html

[R07] if 判断文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitnkgaxm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.quarkkingdee.top/Article/details/gtunneawxz.html

[R08] 数值比较
来源：http://dali.haohaochexian.top/Article/details/gtepfnvkbf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jianghu66.top/Article/details/gtvshjjpue.html

[R09] 字符串比较
来源：http://dali.gaohongyu789.top/Article/details/gtnukrzohk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtniwcojnx.html

[R10] 正则匹配
来源：http://dali.havefunace.top/Article/details/gtpsfgepxr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aibaodan.cn/Article/details/gthvighojz.html

[R11] case 多分支
来源：http://dali.redwolf501.top/Article/details/gtwrbcebmo.html

case "$1" in
来源：http://dali.quarkkingdee.top/Article/details/gtmyrunnrn.html

start) echo "启动" ;;
来源：http://dali.ppjwa.cn/Article/details/gtgpaodyoq.html

stop)  echo "停止" ;;
来源：http://dali.jyoumei.cn/Article/details/gtmxleztez.html

*)     echo "未知命令" ;;
来源：http://dali.gzhubu.top/Article/details/gthtkcsgvz.html

esac
来源：http://dali.cashguo.top/Article/details/gtwayqqqxb.html

[R12] for 遍历文件
来源：http://dali.redwolf501.top/Article/details/gtrxklnvdl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tian-w.cn/Article/details/gtpgoabvfu.html

[R13] for 计数循环
来源：http://dali.ydzc1.top/Article/details/gtavoynuzy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gtxihpcaza.html

[R14] C 风格 for
来源：http://dali.aizwys.cn/Article/details/gtvyvevxtr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ehwqpu.com/Article/details/gtiqhbodqd.html

[R15] while 逐行读文件
来源：http://dali.tanke756.top/Article/details/gtqrstfwbi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nanxinkj.top/Article/details/gtsjcbcepj.html

[R16] until 等待条件
来源：http://dali.chenlongwang.top/Article/details/gtxwyrtncq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gtovqpjcnd.html

[R17] 数组定义与取值
来源：http://dali.cucudq.cn/Article/details/gtzfnckigj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenlongwang.top/Article/details/gtvtjosyrv.html

[R18] 遍历数组
来源：http://dali.daxiang520.top/Article/details/gturpxprcg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhengqikj.top/Article/details/gtzudmrbnb.html

[R19] 数组长度
来源：http://dali.hywenlv.cn/Article/details/gtlqdpzwty.html

echo "${#arr[@]}"
来源：http://dali.nanxuanxn.top/Article/details/gtmziyrdgr.html

[R20] 关联数组（字典）
来源：http://dali.aizwys.cn/Article/details/gtckuqjhon.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shangyingyoupin.top/Article/details/gttqgjqzxe.html

[R21] 字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gtmbmknyao.html

echo "${#s}"
来源：http://dali.daxiang520.top/Article/details/gtnrhfycwn.html

[R22] 截取子串
来源：http://dali.shuidangran.top/Article/details/gtiylmpmre.html

echo "${s:0:5}"
来源：http://dali.316326.xyz/Article/details/gtxvsvjqga.html

[R23] 字符串替换
来源：http://dali.yonumen.top/Article/details/gtlsuzlfmu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.feifeiyinyue.top/Article/details/gtzeplpwgw.html

[R24] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gtrqtisxiw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.9152youxi.cn/Article/details/gtrsaxudrf.html

[R25] 去后缀 / 去前缀
来源：http://dali.0kj1m.cn/Article/details/gtxhuwzfon.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhongyouzk.top/Article/details/gtenobiggc.html

[R26] 命令替换
来源：http://dali.xziqi.cn/Article/details/gtcguniisf.html

now=$(date +%F); echo "$now"
来源：http://dali.pengpengdd.cyou/Article/details/gtwyixbfot.html

[R27] 算术展开
来源：http://dali.xziqi.cn/Article/details/gtimklqoob.html

echo $((1 + 2 * 3))
来源：http://dali.0kj1m.cn/Article/details/gtjysialgo.html

[R28] 浮点运算
来源：http://dali.yonumen.top/Article/details/gtphzpvjzz.html

echo "scale=2; 10/3" | bc
来源：http://dali.xylfe.cn/Article/details/gtknehyaqs.html

[R29] 定义函数
来源：http://dali.guannengcc.top/Article/details/gtymeoddhj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cqqwz.cn/Article/details/gtreidkgso.html

[R30] 函数返回状态码
来源：http://dali.ybcxt.top/Article/details/gtkoscvjmi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenzaomai.com/Article/details/gtywttdygw.html

[R31] 局部变量
来源：http://dali.haohaochexian.top/Article/details/gtlhwxhdff.html

f() { local x=1; echo "$x"; }
来源：http://dali.ehwqpu.com/Article/details/gtdszfhazt.html

[R32] 参数个数校验
来源：http://dali.yj20258.top/Article/details/gtglwxmkyn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gtodtprzgn.html

[R33] 捕获错误并提示行号
来源：http://dali.chenzaomai.com/Article/details/gtzuycewij.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinpnbwio.html

[R34] 退出时清理
来源：http://dali.ehwqpu.com/Article/details/gtddmtjkqq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gthwlgazhx.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gtagbjluzz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aizwys.cn/Article/details/gtucybffzd.html

[R36] 并发执行多个任务
来源：http://dali.yangfankeji.com/Article/details/gtfgatnqyw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxuanxn.top/Article/details/gtgydghxdk.html

[R37] 把输出赋给变量
来源：http://dali.hongshengwenyu.top/Article/details/gtiugifnyw.html

files=$(ls -1)
来源：http://dali.tianlin.xyz/Article/details/gtqtqgnqlf.html

[R38] 管道串联
来源：http://dali.hammf.cn/Article/details/gtbgyewyrh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cashguo.top/Article/details/gtyntbkwje.html

[R39] 重定向标准输出与错误
来源：http://dali.yueranfly.top/Article/details/gttqcnpuze.html

cmd > out.log 2>&1
来源：http://dali.birdmap.top/Article/details/gtczlodrcj.html

[R40] 追加写日志
来源：http://dali.gzhubu.top/Article/details/gtyzdaoxqj.html

echo "log" >> out.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjpqzmlf.html

[R41] 丢弃输出
来源：http://dali.zhongyouzk.top/Article/details/gtgakavowv.html

cmd >/dev/null 2>&1
来源：http://dali.xziqi.cn/Article/details/gttxqlgnhb.html

[R42] 输入重定向
来源：http://dali.daxiang520.top/Article/details/gtrxmjzehw.html

wc -l < a.txt
来源：http://dali.xuanzx.com/Article/details/gtxmoqxexv.html

[R43] 按名字查找文件
来源：http://dali.jqgfzy.top/Article/details/gtojdowmlw.html


<!-- 参考信息 -->