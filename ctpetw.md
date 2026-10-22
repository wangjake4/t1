代发 wailian999

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ppjwa.cn/Article/details/gtxwgaoavn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenzaomai.com/Article/details/gtxyrafwtx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.haohaochexian.top/Article/details/gtuccvifzi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jlsjyb.cn/Article/details/gtuptogtos.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtxtspzfxl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.vqdsnc.cn/Article/details/gthbxektzf.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtfmgtfdca.html

[Q01] 创建表
来源：http://dali.hfpthk.cn/Article/details/gtaqtejvpk.html

CREATE TABLE users (
来源：http://dali.cashguo.top/Article/details/gthnqkvajd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gtctimnfqg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xziqi.cn/Article/details/gtgaddpgcl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tianlin.xyz/Article/details/gtosxzevay.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvvjfdfo.html

);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrfbkxso.html

[Q02] 创建带外键的表
来源：http://dali.yj202588.top/Article/details/gtdbvcgcal.html

CREATE TABLE orders (
来源：http://dali.xuanzx.com/Article/details/gtffrebxna.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.0kj1m.cn/Article/details/gtexwpkxdy.html

user_id INT NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gthdtenlwg.html

amount DECIMAL(10, 2),
来源：http://dali.ppjwa.cn/Article/details/gtxrsiazlb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj20258.top/Article/details/gtzleuagho.html

);
来源：http://dali.ppjwa.cn/Article/details/gtxumemnfa.html

[Q03] 增加列
来源：http://dali.chenlongwang.top/Article/details/gtnmxtvugr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhixingplan.top/Article/details/gtuclmmfdz.html

[Q04] 修改列类型
来源：http://dali.aibaodan.cn/Article/details/gtotxqdnhh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daxiang520.top/Article/details/gtayatisiw.html

[Q05] 重命名列
来源：http://dali.svipenyu.cn/Article/details/gtezqfrxyy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.c1oappe.top/Article/details/gttgymqwcx.html

[Q06] 删除列
来源：http://dali.tian-w.cn/Article/details/gtlwclijcc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xinyue.icu/Article/details/gtgmxxwieu.html

[Q07] 删除表
来源：http://dali.cucudq.cn/Article/details/gtbktjgenb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.9152youxi.cn/Article/details/gttkstytkz.html

[Q08] 创建普通索引
来源：http://dali.zhengqikj.top/Article/details/gtkqkavful.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.bjfxy.top/Article/details/gtjrfgpqxp.html

[Q09] 创建唯一索引
来源：http://dali.pengpengdd.cyou/Article/details/gtfwqvabki.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yuanzhike.top/Article/details/gtkjtdkwub.html

[Q10] 插入单行
来源：http://dali.svipenyu.cn/Article/details/gtvgmvubce.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tian-w.cn/Article/details/gtlhjvwxun.html

[Q11] 一次插入多行
来源：http://dali.xuanzx.com/Article/details/gtyemjxrrf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gthwhbhmkn.html

[Q12] 插入后取自增 ID
来源：http://dali.yvedp.cn/Article/details/gtlpctklze.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.mhx1999.top/Article/details/gtnlziccoo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hammf.cn/Article/details/gtukkmqjth.html

[Q13] 忽略重复插入
来源：http://dali.ydzc1.top/Article/details/gtdwstzjhk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.aizwys.cn/Article/details/gtqlgutidh.html

[Q14] 存在则更新（upsert）
来源：http://dali.hfpthk.cn/Article/details/gtgdxfgxmb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ybcxt.top/Article/details/gtgfkwcqli.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjyvwvmdx.html

[Q15] 查询全部
来源：http://dali.fzhhl.top/Article/details/gttwvcebwp.html

SELECT * FROM users;
来源：http://dali.redwolf501.top/Article/details/gterggvjnw.html

[Q16] 查询指定列
来源：http://dali.0kj1m.cn/Article/details/gttrkokxcq.html

SELECT id, name FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtsiklwtzn.html

[Q17] 条件查询
来源：http://dali.xuetiantiany.cn/Article/details/gtmkxlxuia.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ivvv.top/Article/details/gtkpijnfyy.html

[Q18] 模糊匹配
来源：http://dali.guannengcc.top/Article/details/gtlxiquvoh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinghuilouyu.cn/Article/details/gthgkjdugv.html

[Q19] 范围查询
来源：http://dali.ivvv.top/Article/details/gtmklwfork.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnxiangtu.top/Article/details/gtlvutlqiq.html

[Q20] IN 列表
来源：http://dali.dianchejie.cn/Article/details/gtkgdbfvfm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guowangkeji.top/Article/details/gtzxzsnpxr.html

[Q21] 空值判断
来源：http://dali.hammf.cn/Article/details/gtuiuqsliu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yanxiufei.cn/Article/details/gtxdlbtgeu.html

[Q22] 排序
来源：http://dali.yvedp.cn/Article/details/gtmnlixbbm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jiagoushi.top/Article/details/gtyuqnmkyf.html

[Q23] 分页
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlkpqhkfi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yueranfly.top/Article/details/gtmmmqhhnx.html

[Q24] 去重
来源：http://dali.tanke756.top/Article/details/gtwbdvacpj.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzafpazd.html

[Q25] 只取前 N 条
来源：http://dali.zhiwuduotai.top/Article/details/gtmpzlxglz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.mhx1999.top/Article/details/gtjwcdcdcg.html

[Q26] 计数
来源：http://dali.jqgufenzy.top/Article/details/gtbyoqaygi.html

SELECT COUNT(*) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gttgwbrotn.html

[Q27] 条件计数
来源：http://dali.yanxiufei.cn/Article/details/gtjxidhcxa.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fengsongda.top/Article/details/gtbntjjvzs.html

[Q28] 求和与平均
来源：http://dali.nanxinkj.top/Article/details/gtkoovaqbo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.316326.xyz/Article/details/gteaexabyb.html

[Q29] 最大最小值
来源：http://dali.cashguo.top/Article/details/gtoszekiyo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtcruoigep.html

[Q30] 分组统计
来源：http://dali.xziqi.cn/Article/details/gtprlkgmjm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gtwciugimg.html

[Q31] 分组后过滤
来源：http://dali.yj202588.top/Article/details/gtinqedrbs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cqqwz.cn/Article/details/gtzwfqciir.html

[Q32] 分组拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gthxtmbcis.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gtsxtaapef.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangshuangyany.cn/Article/details/gtjkckgltc.html

[Q33] 多列分组
来源：http://dali.hnxiangtu.top/Article/details/gtagpejivs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nanxinkj.top/Article/details/gtlfvixmqq.html

[Q34] 每组取第一条
来源：http://dali.kuanghao11.cn/Article/details/gtksxlpgzm.html

SELECT * FROM (
来源：http://dali.ehwqpu.com/Article/details/gtamebmzxk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkrjjqrz.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gttvfofynu.html

[Q35] 内连接
来源：http://dali.zhiwuduotai.top/Article/details/gtyefzysrz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gtjdzjkoqa.html

[Q36] 左连接
来源：http://dali.yj20258888.top/Article/details/gtyubfvicz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gtylpzygvq.html

[Q37] 右连接
来源：http://dali.yongpay.top/Article/details/gtowrxpokn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sweek.top/Article/details/gtgluajdfy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yangfankeji.com/Article/details/gtotnnfpec.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ivvv.top/Article/details/gttnahauye.html

[Q39] 自连接（查上下级）
来源：http://dali.feifeiyinyue.top/Article/details/gttdyfidrj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gogol.net.cn/Article/details/gtlbzhprhe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtcnxclpll.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shangyingyoupin.top/Article/details/gtfhkdttlm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cucudq.cn/Article/details/gtokytauek.html

[Q41] 多表连接
来源：http://dali.haohaochexian.top/Article/details/gtuwehovbr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj20258888.top/Article/details/gtldddlkhj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.9152youxi.cn/Article/details/gtuocdfuwn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sysykeji.top/Article/details/gtcrpfxqxw.html

[Q42] 连接条件附加过滤
来源：http://dali.yvedp.cn/Article/details/gtznzbalfh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.fengsongda.top/Article/details/gthqlucqde.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nanxinkj.top/Article/details/gtkaezjtvh.html

[Q43] 标量子查询
来源：http://dali.sxryk.cn/Article/details/gtstumvznr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yonumen.top/Article/details/gtnrvruorw.html

[Q44] IN 子查询
来源：http://dali.yonumen.top/Article/details/gtmdckcskk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnebtcnyf.html

[Q45] EXISTS 判断存在
来源：http://dali.hnxiangtu.top/Article/details/gtreijymaw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhoulong.xyz/Article/details/gtkrqjgltt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhixingplan.top/Article/details/gtowghzbbu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tianlin.xyz/Article/details/gttgkkoflj.html

[Q47] 与平均值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdnwewofy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sxryk.cn/Article/details/gtghnypdxb.html

[Q48] CTE 公用表表达式
来源：http://dali.zycfv.cn/Article/details/gtchbupxdm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.haohaochexian.top/Article/details/gtplyuzqlo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yueranfly.top/Article/details/gtznxdcthb.html

[Q49] 更新单行
来源：http://dali.dianchejie.cn/Article/details/gtwxjadwqj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gtwnehkbdv.html

[Q50] 批量更新
来源：http://dali.xuanzx.com/Article/details/gtljtocqwo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hfpthk.cn/Article/details/gtkdudipcj.html

[Q51] 用子查询更新
来源：http://dali.gzhubu.top/Article/details/gtskalbutl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinqigufen.top/Article/details/gtmcswpsyd.html

[Q52] 删除指定行
来源：http://dali.wangshuangyany.cn/Article/details/gtolpzhgvh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gtgrahfxbp.html

[Q53] 按条件删除
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfquvdkb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.andypj.xyz/Article/details/gttejfioec.html

[Q54] 清空表
来源：http://dali.ppjwa.cn/Article/details/gtnxqmktwc.html

TRUNCATE TABLE logs;
来源：http://dali.xinyue.icu/Article/details/gtemavtasv.html

[Q55] 排名（并列占位）
来源：http://dali.dashuyun.cn/Article/details/gtzrgtflkk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.iojbl.cn/Article/details/gtidtcecmx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tian-w.cn/Article/details/gtdsolemea.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenlongwang.top/Article/details/gtgzssokup.html

[Q57] 行号
来源：http://dali.snrcjt.cn/Article/details/gttkgfgsdu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258888.top/Article/details/gtmxnizfrk.html

[Q58] 累计求和
来源：http://dali.yvedp.cn/Article/details/gtuhvtftro.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gticmheloi.html

[Q59] 分组内累计
来源：http://dali.jinqigfzy.top/Article/details/gtemmnmsxw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.316326.xyz/Article/details/gtdxiykiml.html

[Q60] 取上一行 / 下一行
来源：http://dali.9152youxi.cn/Article/details/gtbzrywopf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daxiang520.top/Article/details/gtzsztxgra.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.316326.xyz/Article/details/gtevmwawcn.html

[Q61] 移动平均
来源：http://dali.jqgufenzy.top/Article/details/gtybwnvtxl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gttekermhs.html

[Q62] 分组占比
来源：http://dali.bjfxy.top/Article/details/gtslschzbg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gtosvrdzok.html

[Q63] 开启事务
来源：http://dali.jinghuilouyu.cn/Article/details/gtunrcfogi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.mhx1999.top/Article/details/gtstwwgpyz.html

[Q64] 提交事务
来源：http://dali.yvedp.cn/Article/details/gtgaxbpfvr.html

COMMIT;
来源：http://dali.gaohongyu789.top/Article/details/gtojjsmpje.html

[Q65] 回滚事务
来源：http://dali.gotoacloud.top/Article/details/gtlrbscrqm.html

ROLLBACK;
来源：http://dali.cashguo.top/Article/details/gtsizmykln.html

[Q66] 行锁查询
来源：http://dali.fengsongda.top/Article/details/gtizhmblus.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xylfe.cn/Article/details/gtlwhcuslr.html

[Q67] 设置隔离级别
来源：http://dali.cdnleiting.top/Article/details/gtegprqphq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pycfn.com/Article/details/gtinqhmwap.html

[Q68] 保存点
来源：http://dali.9152youxi.cn/Article/details/gtehvyencn.html

SAVEPOINT sp1;
来源：http://dali.andypj.xyz/Article/details/gtnqtmrcer.html

ROLLBACK TO sp1;
来源：http://dali.daria6918.cn/Article/details/gtnfvqdcpk.html

[Q69] 查看执行计划
来源：http://dali.dashuyun.cn/Article/details/gtfcqrsnsv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shangyingyoupin.top/Article/details/gtspzvmcvp.html

[Q70] 更新统计信息
来源：http://dali.aizwys.cn/Article/details/gtkmmarjtu.html

ANALYZE TABLE users;
来源：http://dali.jlsjyb.cn/Article/details/gtrpbgkfgc.html

[Q71] 查看建表语句
来源：http://dali.daxiang520.top/Article/details/gtnihpdhlr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.redwolf501.top/Article/details/gtxrykqwiq.html

[Q72] 查看索引
来源：http://dali.jinqigufen.top/Article/details/gtfkfihehb.html

SHOW INDEX FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtkeppswrx.html

[Q73] 查看表状态
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkyjlgcsw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shangyingyoupin.top/Article/details/gtisczmuxa.html

[Q74] 强制使用索引
来源：http://dali.xuanzx.com/Article/details/gtptzkmukg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.316326.xyz/Article/details/gtrnkjhekr.html

[Q75] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gtueaqngih.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gttrdqhwaj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cucudq.cn/Article/details/gtgeupnhek.html

[Q76] 按天统计
来源：http://dali.guannengcc.top/Article/details/gtqxbohqvw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.svipenyu.cn/Article/details/gttggqskoy.html

[Q77] 时间加减
来源：http://dali.jianghu66.top/Article/details/gtgpqpxxxi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdyyozwz.html

[Q78] 当前时间
来源：http://dali.yonumen.top/Article/details/gtqiiufjfh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangdashe.top/Article/details/gtbnnelzvk.html

[Q79] 字符串拼接
来源：http://dali.yvedp.cn/Article/details/gttqbqwfko.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.redwolf501.top/Article/details/gtboduklkm.html

[Q80] 字符串截取
来源：http://dali.aizwys.cn/Article/details/gtizlqmuuo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sweek.top/Article/details/gtuwksifpz.html

[Q81] 字符串替换
来源：http://dali.havefunace.top/Article/details/gtreygbvpe.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.redwolf501.top/Article/details/gtnrnndyqw.html

[Q82] 字符长度与字节长度
来源：http://dali.jinqigfzy.top/Article/details/gtipmgtayr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtcidlalhi.html

[Q83] 大小写转换
来源：http://dali.cheryme.top/Article/details/gtwmbgfswz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gttclrnzwt.html

[Q84] 去除首尾空格
来源：http://dali.xinyue.icu/Article/details/gtpqmkxbxp.html

SELECT TRIM(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtlbyfaxmi.html

[Q85] 数值取整
来源：http://dali.pycfn.com/Article/details/gtmcjpzong.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.svipenyu.cn/Article/details/gtvkuxjglm.html

[Q86] 读取 JSON 字段
来源：http://dali.cucudq.cn/Article/details/gtcrcneufu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.haohaochexian.top/Article/details/gtrztiyevz.html

[Q87] JSON 字段做条件
来源：http://dali.hysaishi.cn/Article/details/gtrozfhwob.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ivvv.top/Article/details/gtxctxufld.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinqigfzy.top/Article/details/gtejrmsmxb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.birdmap.top/Article/details/gtauxzrsct.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtxjkxfhsl.html

[Q89] 判断表是否存在
来源：http://dali.birdmap.top/Article/details/gtykbwnqrn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yangfankeji.com/Article/details/gtclrymkvj.html

[Q90] 生成序号列
来源：http://dali.jinqigfzy.top/Article/details/gtjbbnzplq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuanzx.com/Article/details/gthzldsybx.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtghlfcwsy.html

R. Bash 专题
来源：http://dali.sxryk.cn/Article/details/gtdnsglvff.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gthoxabxbx.html

[R01] shebang 与严格模式
来源：http://dali.tian-w.cn/Article/details/gtyktunnqz.html

#!/usr/bin/env bash
来源：http://dali.hongshengwenyu.top/Article/details/gtpcvepjej.html

set -euo pipefail
来源：http://dali.sufxvd.cn/Article/details/gtfyxddzan.html

[R02] 变量赋值与使用
来源：http://dali.birdmap.top/Article/details/gtzfmngpbw.html

name="Tom"; echo "$name"
来源：http://dali.pycfn.com/Article/details/gtakkamvij.html

[R03] 只读变量
来源：http://dali.gotoacloud.top/Article/details/gtsnqsngay.html

readonly PI=3.14
来源：http://dali.yueranfly.top/Article/details/gttkrbciwb.html

[R04] 位置参数
来源：http://dali.hnxiangtu.top/Article/details/gthkbhhjri.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangtech.top/Article/details/gtquslxjic.html

[R05] 参数默认值
来源：http://dali.yangfankeji.com/Article/details/gtgyeeezaq.html

name="${1:-default}"
来源：http://dali.havefunace.top/Article/details/gtsmavfqiu.html

[R06] 判断命令是否存在
来源：http://dali.xinyue.icu/Article/details/gtoeangzdq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hywenlv.cn/Article/details/gteaycnyun.html

[R07] if 判断文件
来源：http://dali.cucudq.cn/Article/details/gtmhpvaehg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigufen.top/Article/details/gtpajwsmjj.html

[R08] 数值比较
来源：http://dali.jqgufenzy.top/Article/details/gtqgnczchu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj20258.top/Article/details/gtxsweqazg.html

[R09] 字符串比较
来源：http://dali.tianlin.xyz/Article/details/gthtcytovf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daxiang520.top/Article/details/gttibuuipu.html

[R10] 正则匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqckzbxm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sweek.top/Article/details/gtbxluvzaw.html

[R11] case 多分支
来源：http://dali.pycfn.com/Article/details/gtvroagier.html

case "$1" in
来源：http://dali.dianchejie.cn/Article/details/gtyulhjhfp.html

start) echo "启动" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtgnqavtkh.html

stop)  echo "停止" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphzgsfoo.html

*)     echo "未知命令" ;;
来源：http://dali.c1oappe.top/Article/details/gtiyqywjyb.html

esac
来源：http://dali.gaohongyu789.top/Article/details/gttpsfubam.html

[R12] for 遍历文件
来源：http://dali.guowangkeji.top/Article/details/gtufubwfyo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.wangdashe.top/Article/details/gtwyrcvmtk.html

[R13] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gtvtdtbuep.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhoulong.xyz/Article/details/gtnmeafbwx.html

[R14] C 风格 for
来源：http://dali.ppjwa.cn/Article/details/gtdylarfhg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fzhhl.top/Article/details/gtzofalnkw.html

[R15] while 逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gtclijvcur.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jiagoushi.top/Article/details/gtnnawtvib.html

[R16] until 等待条件
来源：http://dali.jqgfzy.top/Article/details/gtxgvjquoz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gtidayvymu.html

[R17] 数组定义与取值
来源：http://dali.daxiang520.top/Article/details/gtqoeqlsvw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hnqzz.top/Article/details/gtpkpdutcz.html

[R18] 遍历数组
来源：http://dali.yj202588.top/Article/details/gtnrgoucpw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnatymyxz.html

[R19] 数组长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkncwozji.html

echo "${#arr[@]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtudlzxexd.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwgviffx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yanxiufei.cn/Article/details/gttdcnrevh.html

[R21] 字符串长度
来源：http://dali.yj20258.top/Article/details/gtlcdbldpi.html

echo "${#s}"
来源：http://dali.9152youxi.cn/Article/details/gtebbqfuva.html

[R22] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gtakzwpffh.html

echo "${s:0:5}"
来源：http://dali.hysaishi.cn/Article/details/gtkqveqihw.html

[R23] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gtmybczuaq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqpgpzteb.html

[R24] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gtalumonht.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sysykeji.top/Article/details/gtikydppks.html

[R25] 去后缀 / 去前缀
来源：http://dali.sufxvd.cn/Article/details/gtrgpelmpq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sysykeji.top/Article/details/gtxszoemxl.html

[R26] 命令替换
来源：http://dali.9152youxi.cn/Article/details/gtrdxjunao.html

now=$(date +%F); echo "$now"
来源：http://dali.xziqi.cn/Article/details/gthgqwwutf.html

[R27] 算术展开
来源：http://dali.iojbl.cn/Article/details/gtmrrjdopb.html

echo $((1 + 2 * 3))
来源：http://dali.shangyingyoupin.top/Article/details/gtlshwdfak.html

[R28] 浮点运算
来源：http://dali.yj20258.top/Article/details/gtuzvvtlxr.html

echo "scale=2; 10/3" | bc
来源：http://dali.iojbl.cn/Article/details/gtfwmvwjqu.html

[R29] 定义函数
来源：http://dali.sxryk.cn/Article/details/gtmpzoojhv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.havefunace.top/Article/details/gtakqkjjsp.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gtkclspnje.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenjidiqi.icu/Article/details/gtvjoeolbi.html

[R31] 局部变量
来源：http://dali.dashuyun.cn/Article/details/gttptladay.html

f() { local x=1; echo "$x"; }
来源：http://dali.hywenlv.cn/Article/details/gtjzqnyoke.html

[R32] 参数个数校验
来源：http://dali.haohaochexian.top/Article/details/gtlqdkziah.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinqigufen.top/Article/details/gtwrklgdjs.html

[R33] 捕获错误并提示行号
来源：http://dali.9152youxi.cn/Article/details/gtssmkwujn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gzhubu.top/Article/details/gtqwezbfyu.html

[R34] 退出时清理
来源：http://dali.zhoulong.xyz/Article/details/gtzsnjtucg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gtjvqqzohs.html

[R35] 后台执行并等待
来源：http://dali.ybcxt.top/Article/details/gtnhddwaxl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cqqwz.cn/Article/details/gtygkbtaxn.html

[R36] 并发执行多个任务
来源：http://dali.hysaishi.cn/Article/details/gtmzlblagj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yvedp.cn/Article/details/gtgjoevgar.html

[R37] 把输出赋给变量
来源：http://dali.yueranfly.top/Article/details/gtmncpewhh.html

files=$(ls -1)
来源：http://dali.yongpay.top/Article/details/gtezfoscrp.html

[R38] 管道串联
来源：http://dali.dianchejie.cn/Article/details/gtczbvxhlb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xylfe.cn/Article/details/gtryigcjbu.html

[R39] 重定向标准输出与错误
来源：http://dali.xylfe.cn/Article/details/gtcqasumhq.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gtiobnuake.html

[R40] 追加写日志
来源：http://dali.hysaishi.cn/Article/details/gtvpdzyaaa.html

echo "log" >> out.log
来源：http://dali.fzhhl.top/Article/details/gtesiolzke.html

[R41] 丢弃输出
来源：http://dali.zhengqikj.top/Article/details/gtzbiwjrib.html


<!-- 参考信息 -->