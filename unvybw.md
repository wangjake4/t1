代发 wailian999

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hfpthk.cn/Article/details/gtezpdnhlr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.daxiang520.top/Article/details/gtutxaxtwi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.smart0.xyz/Article/details/gthvwdzymn.html

[P08] 处理浮点精度问题
来源：http://dali.hnxiangtu.top/Article/details/gtboimixzh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.andypj.xyz/Article/details/gtvpecbkbq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.9152youxi.cn/Article/details/gtyoxfccgh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pengpengdd.cyou/Article/details/gtplnabrni.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shuidangran.top/Article/details/gtpiqltvzk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenjidiqi.icu/Article/details/gtkkuqbosk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aizwys.cn/Article/details/gtuoqbkbne.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhengqikj.top/Article/details/gtnfnwipxj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sysykeji.top/Article/details/gttmnztflu.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gttkpbargw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.aizwys.cn/Article/details/gtalyxmkkp.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtigqamhmu.html

[Q01] 创建表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxeqrpdtn.html

CREATE TABLE users (
来源：http://dali.yuxming.cn/Article/details/gtefswcyit.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuanzhike.top/Article/details/gtgodauipv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sysykeji.top/Article/details/gtxonzzhsv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhaomingkeji.xyz/Article/details/gthisyvenq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.aizwys.cn/Article/details/gtajvlrlyj.html

);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkcwosoot.html

[Q02] 创建带外键的表
来源：http://dali.daria6918.cn/Article/details/gtxaaqyzaw.html

CREATE TABLE orders (
来源：http://dali.redwolf501.top/Article/details/gtznypdnpf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gtuykbfxsf.html

user_id INT NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gtxurquzzq.html

amount DECIMAL(10, 2),
来源：http://dali.chenzaomai.com/Article/details/gtzphpmutr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.daria6918.cn/Article/details/gthnjjmkve.html

);
来源：http://dali.jinghuilouyu.cn/Article/details/gteuuavszz.html

[Q03] 增加列
来源：http://dali.shuidangran.top/Article/details/gtvrwjkfxg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shuidangran.top/Article/details/gtewtjwbph.html

[Q04] 修改列类型
来源：http://dali.aibaodan.cn/Article/details/gtmqkrtpzt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafmweoev.html

[Q05] 重命名列
来源：http://dali.svipenyu.cn/Article/details/gtottuhsll.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.havefunace.top/Article/details/gtvxzfdczk.html

[Q06] 删除列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrwzmacm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jiagoushi.top/Article/details/gtqnqnhibq.html

[Q07] 删除表
来源：http://dali.smart0.xyz/Article/details/gtynpdjztq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xziqi.cn/Article/details/gtydwcdkum.html

[Q08] 创建普通索引
来源：http://dali.xinyue.icu/Article/details/gtomilidvf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenzaomai.com/Article/details/gthpuzxbjb.html

[Q09] 创建唯一索引
来源：http://dali.hywenlv.cn/Article/details/gtewytnwrr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gtjsitgjmm.html

[Q10] 插入单行
来源：http://dali.redwolf501.top/Article/details/gtownndovo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xinyue.icu/Article/details/gtufodmeud.html

[Q11] 一次插入多行
来源：http://dali.zhiwuduotai.top/Article/details/gtxqdkgkkf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aizwys.cn/Article/details/gtnvhkkrbm.html

[Q12] 插入后取自增 ID
来源：http://dali.yj202588.top/Article/details/gtrbkvrxbo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.andypj.xyz/Article/details/gtztzjtlga.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.feifeiyinyue.top/Article/details/gtrcwvqewz.html

[Q13] 忽略重复插入
来源：http://dali.mhx1999.top/Article/details/gtfeamxkua.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangdashe.top/Article/details/gtixvfikqb.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinqigfzy.top/Article/details/gtdfwkxuml.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jqgfzy.top/Article/details/gtnbhdfxig.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gotoacloud.top/Article/details/gtobwtkgje.html

[Q15] 查询全部
来源：http://dali.ehwqpu.com/Article/details/gthlxwpwop.html

SELECT * FROM users;
来源：http://dali.cashguo.top/Article/details/gtqukgoftk.html

[Q16] 查询指定列
来源：http://dali.yuxming.cn/Article/details/gtbbmtsuoo.html

SELECT id, name FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtinxuvfsy.html

[Q17] 条件查询
来源：http://dali.yueranfly.top/Article/details/gtxytveizu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.dashuyun.cn/Article/details/gtdogvoeub.html

[Q18] 模糊匹配
来源：http://dali.ydzc1.top/Article/details/gtltzvvhgy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zdqjudy.top/Article/details/gtnqilogrm.html

[Q19] 范围查询
来源：http://dali.andypj.xyz/Article/details/gtusqrwrqh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.wangshuangyany.cn/Article/details/gthahwxsms.html

[Q20] IN 列表
来源：http://dali.yanxiufei.cn/Article/details/gtyrqimrvg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shzxlz.cn/Article/details/gteqieyaap.html

[Q21] 空值判断
来源：http://dali.daria6918.cn/Article/details/gtoazgrmld.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yangfankeji.com/Article/details/gtunkcxpxc.html

[Q22] 排序
来源：http://dali.sufxvd.cn/Article/details/gtlsjyyyby.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.quarkkingdee.top/Article/details/gtxutpewzg.html

[Q23] 分页
来源：http://dali.gogol.net.cn/Article/details/gthhvgnshe.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yvedp.cn/Article/details/gtcuoojukf.html

[Q24] 去重
来源：http://dali.jinqigufen.top/Article/details/gtfoivttov.html

SELECT DISTINCT city FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvuftwqe.html

[Q25] 只取前 N 条
来源：http://dali.hysaishi.cn/Article/details/gtfnjqgvac.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.birdmap.top/Article/details/gtjafsuhwy.html

[Q26] 计数
来源：http://dali.yvedp.cn/Article/details/gtcenyorpg.html

SELECT COUNT(*) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtczzpqpjg.html

[Q27] 条件计数
来源：http://dali.yj202588.top/Article/details/gtqussambn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jianghu66.top/Article/details/gtxspqvlbu.html

[Q28] 求和与平均
来源：http://dali.chenjidiqi.icu/Article/details/gtkndycbul.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtnoosqmor.html

[Q29] 最大最小值
来源：http://dali.chenzaomai.com/Article/details/gtshsywpgp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xinyue.icu/Article/details/gttvbhpdgn.html

[Q30] 分组统计
来源：http://dali.daxiang520.top/Article/details/gtrblpazlm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsefbcgpy.html

[Q31] 分组后过滤
来源：http://dali.hysaishi.cn/Article/details/gtpjwlypsn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zycfv.cn/Article/details/gtdqxdfofy.html

[Q32] 分组拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtdokbrjte.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gtiifystid.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj202588.top/Article/details/gtwmczgwrn.html

[Q33] 多列分组
来源：http://dali.fengsongda.top/Article/details/gtftjvyoae.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nanxinkj.top/Article/details/gtcnugdyuh.html

[Q34] 每组取第一条
来源：http://dali.daxiang520.top/Article/details/gtoybprsye.html

SELECT * FROM (
来源：http://dali.svipenyu.cn/Article/details/gtnjnsynmm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hysaishi.cn/Article/details/gtbycyyswk.html

) t WHERE rn = 1;
来源：http://dali.yj202588.top/Article/details/gtgotvphuf.html

[Q35] 内连接
来源：http://dali.316326.xyz/Article/details/gtdiiynqpf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhengqikj.top/Article/details/gtenyfrjyz.html

[Q36] 左连接
来源：http://dali.xziqi.cn/Article/details/gtbmzgdjrn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gtzmqktuxs.html

[Q37] 右连接
来源：http://dali.xinyue.icu/Article/details/gtuydxdlbc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.havefunace.top/Article/details/gtzxworvjv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.quarkkingdee.top/Article/details/gtupecolix.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yuxming.cn/Article/details/gtksnlayll.html

[Q39] 自连接（查上下级）
来源：http://dali.hysaishi.cn/Article/details/gtrkugqjvn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhiwuduotai.top/Article/details/gtxgmxwsvz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.snrcjt.cn/Article/details/gtvzckmcde.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.guowangkeji.top/Article/details/gtabydfvwu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cucudq.cn/Article/details/gtowzpunrh.html

[Q41] 多表连接
来源：http://dali.sweek.top/Article/details/gtlfwmgcsz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.9152youxi.cn/Article/details/gtwiqjqowl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.0kj1m.cn/Article/details/gtnfxkafan.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258.top/Article/details/gtwlkgoujw.html

[Q42] 连接条件附加过滤
来源：http://dali.nwbrower.top/Article/details/gtmdamvspv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yongpay.top/Article/details/gtrlkcnkvz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xziqi.cn/Article/details/gtzkawtmkd.html

[Q43] 标量子查询
来源：http://dali.dianchejie.cn/Article/details/gtqztmnqtf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zycfv.cn/Article/details/gtduwbikoy.html

[Q44] IN 子查询
来源：http://dali.zhoulong.xyz/Article/details/gtiveaoyux.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ybcxt.top/Article/details/gtlkaimtjc.html

[Q45] EXISTS 判断存在
来源：http://dali.quarkkingdee.top/Article/details/gtfrgykjce.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gtghpmopav.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jlsjyb.cn/Article/details/gtvdpxihmq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ybcxt.top/Article/details/gtmtahqfmu.html

[Q47] 与平均值比较
来源：http://dali.chenzaomai.com/Article/details/gtnzbfrkqi.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.vqdsnc.cn/Article/details/gtkvoqdrsj.html

[Q48] CTE 公用表表达式
来源：http://dali.zdqjudy.top/Article/details/gtoerqhrjf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.wangdashe.top/Article/details/gtktimdkkc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hnqzz.top/Article/details/gtqdzgzdud.html

[Q49] 更新单行
来源：http://dali.ivvv.top/Article/details/gtnqzauyib.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gotoacloud.top/Article/details/gtuzpqlfaz.html

[Q50] 批量更新
来源：http://dali.hnqzz.top/Article/details/gtpmhuhves.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gtqhzscfhh.html

[Q51] 用子查询更新
来源：http://dali.svipenyu.cn/Article/details/gtnfgxhsyi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.guannengcc.top/Article/details/gtbfmgybhq.html

[Q52] 删除指定行
来源：http://dali.cashguo.top/Article/details/gtvbrcxbbo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xylfe.cn/Article/details/gttxshqmao.html

[Q53] 按条件删除
来源：http://dali.gotoacloud.top/Article/details/gtxdloqqql.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.svipenyu.cn/Article/details/gtnjcovzfa.html

[Q54] 清空表
来源：http://dali.sxryk.cn/Article/details/gtfqlszovo.html

TRUNCATE TABLE logs;
来源：http://dali.ppjwa.cn/Article/details/gtbeuhqtlp.html

[Q55] 排名（并列占位）
来源：http://dali.aizwys.cn/Article/details/gtqygixbns.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.guannengcc.top/Article/details/gtumoggumb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zycfv.cn/Article/details/gtxbsskzmo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.mhx1999.top/Article/details/gtokzirepc.html

[Q57] 行号
来源：http://dali.cqqwz.cn/Article/details/gtsixnhndk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtgpqvhjwt.html

[Q58] 累计求和
来源：http://dali.shzxlz.cn/Article/details/gtrdxasozf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtglpwttjg.html

[Q59] 分组内累计
来源：http://dali.jyoumei.cn/Article/details/gtdyebnndw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtxhzaxwms.html

[Q60] 取上一行 / 下一行
来源：http://dali.hnxiangtu.top/Article/details/gtuohnwsjd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yuanzhike.top/Article/details/gtrvmdqpld.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtwkaarrpp.html

[Q61] 移动平均
来源：http://dali.xuanzx.com/Article/details/gtmqqpujnf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtfvmjnitu.html

[Q62] 分组占比
来源：http://dali.aizwys.cn/Article/details/gtpjpxwxkd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gtwcgvvhlc.html

[Q63] 开启事务
来源：http://dali.jlsjyb.cn/Article/details/gtywneaxqy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.kuanghao11.cn/Article/details/gtlxdzyxxx.html

[Q64] 提交事务
来源：http://dali.jinqigfzy.top/Article/details/gttfstdopr.html

COMMIT;
来源：http://dali.yvedp.cn/Article/details/gtdckgrmbe.html

[Q65] 回滚事务
来源：http://dali.cucudq.cn/Article/details/gtigcidugm.html

ROLLBACK;
来源：http://dali.cheryme.top/Article/details/gtpkjbcdkd.html

[Q66] 行锁查询
来源：http://dali.ppjwa.cn/Article/details/gtlipcftge.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.andypj.xyz/Article/details/gtdwsykbzt.html

[Q67] 设置隔离级别
来源：http://dali.sxryk.cn/Article/details/gtlaffahof.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ivvv.top/Article/details/gtpvylcfxs.html

[Q68] 保存点
来源：http://dali.zycfv.cn/Article/details/gtpwodgkvk.html

SAVEPOINT sp1;
来源：http://dali.pengpengdd.cyou/Article/details/gtqcgmtezi.html

ROLLBACK TO sp1;
来源：http://dali.fzhhl.top/Article/details/gthxughvxc.html

[Q69] 查看执行计划
来源：http://dali.yonumen.top/Article/details/gturwnfyau.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhiwuduotai.top/Article/details/gtelzjnglm.html

[Q70] 更新统计信息
来源：http://dali.yj20258888.top/Article/details/gtgqxbtaps.html

ANALYZE TABLE users;
来源：http://dali.zycfv.cn/Article/details/gtihmeeawd.html

[Q71] 查看建表语句
来源：http://dali.hnxiangtu.top/Article/details/gtnvwtoxkt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sufxvd.cn/Article/details/gtiqtkkecn.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gtwmyiguot.html

SHOW INDEX FROM users;
来源：http://dali.ybcxt.top/Article/details/gtbdggkdzw.html

[Q73] 查看表状态
来源：http://dali.zhoulong.xyz/Article/details/gtcizzokho.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.0kj1m.cn/Article/details/gtsbcszvzd.html

[Q74] 强制使用索引
来源：http://dali.andypj.xyz/Article/details/gtimmuafmp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xinyue.icu/Article/details/gtftttuuyj.html

[Q75] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gthogwfecl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtqprvunoh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.0kj1m.cn/Article/details/gtdoyumlpj.html

[Q76] 按天统计
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrripexlu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cdnleiting.top/Article/details/gtgkdjcfql.html

[Q77] 时间加减
来源：http://dali.haohaochexian.top/Article/details/gthvaapphp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.redwolf501.top/Article/details/gtwhzezvvp.html

[Q78] 当前时间
来源：http://dali.nwbrower.top/Article/details/gtfxomnuzj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cheryme.top/Article/details/gtyklzwtts.html

[Q79] 字符串拼接
来源：http://dali.cqqwz.cn/Article/details/gtfwcrlrfc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sysykeji.top/Article/details/gthjwnpwwo.html

[Q80] 字符串截取
来源：http://dali.pycfn.com/Article/details/gtfyrnulyi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.birdmap.top/Article/details/gtlwkxvuyz.html

[Q81] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gtauwzitky.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtorxdizvq.html

[Q82] 字符长度与字节长度
来源：http://dali.xziqi.cn/Article/details/gtnrldponc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtndabzvnp.html

[Q83] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gtdotjvjon.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtyxwkqhhv.html

[Q84] 去除首尾空格
来源：http://dali.yonumen.top/Article/details/gtqxiejhet.html

SELECT TRIM(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtsdusrhun.html

[Q85] 数值取整
来源：http://dali.dianchejie.cn/Article/details/gtilefrxrr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nwbrower.top/Article/details/gtkwovlgrk.html

[Q86] 读取 JSON 字段
来源：http://dali.cheryme.top/Article/details/gtviwkgrws.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.smart0.xyz/Article/details/gtgawnuahc.html

[Q87] JSON 字段做条件
来源：http://dali.yuanzhike.top/Article/details/gtzsabcpux.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daria6918.cn/Article/details/gtypvllsvp.html

[Q88] 行转列（条件聚合）
来源：http://dali.birdmap.top/Article/details/gtslkbeeoc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenzaomai.com/Article/details/gtgrlyzuib.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.fzhhl.top/Article/details/gtdpzgheiw.html

[Q89] 判断表是否存在
来源：http://dali.jiagoushi.top/Article/details/gtwzrnxjqq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cqqwz.cn/Article/details/gtyvagjqan.html

[Q90] 生成序号列
来源：http://dali.zhongyouzk.top/Article/details/gtuvhkknws.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gaohongyu789.top/Article/details/gtefsghqse.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtogyoeynq.html

R. Bash 专题
来源：http://dali.jlsjyb.cn/Article/details/gtmlctvvhw.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtpfpuhbvb.html

[R01] shebang 与严格模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngkwikis.html

#!/usr/bin/env bash
来源：http://dali.kuanghao11.cn/Article/details/gtjvgmhqqh.html

set -euo pipefail
来源：http://dali.zhoulong.xyz/Article/details/gtlwmnobun.html

[R02] 变量赋值与使用
来源：http://dali.jianghu66.top/Article/details/gtkqijcpue.html

name="Tom"; echo "$name"
来源：http://dali.jianghu66.top/Article/details/gtnluicjch.html

[R03] 只读变量
来源：http://dali.0kj1m.cn/Article/details/gtvcueaonc.html

readonly PI=3.14
来源：http://dali.yonumen.top/Article/details/gtdvbeznbz.html

[R04] 位置参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqydlkyc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shzxlz.cn/Article/details/gtjqcatuip.html

[R05] 参数默认值
来源：http://dali.yueranfly.top/Article/details/gtxwjwobfe.html

name="${1:-default}"
来源：http://dali.smart0.xyz/Article/details/gtiklsvlhv.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gtisdgounb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gtiuwmfagx.html

[R07] if 判断文件
来源：http://dali.zycfv.cn/Article/details/gtmbtxwdrv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtbmgtmlqo.html

[R08] 数值比较
来源：http://dali.yj202588.top/Article/details/gtyofddnqo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.svipenyu.cn/Article/details/gtjmqridiz.html

[R09] 字符串比较
来源：http://dali.sysykeji.top/Article/details/gtzglayqhw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtjbualikr.html

[R10] 正则匹配
来源：http://dali.svipenyu.cn/Article/details/gtfozyneyh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtupuhsdil.html

[R11] case 多分支
来源：http://dali.yanxiufei.cn/Article/details/gtsqyidpih.html

case "$1" in
来源：http://dali.daria6918.cn/Article/details/gtfbtyxxls.html

start) echo "启动" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxhmoqux.html

stop)  echo "停止" ;;
来源：http://dali.jinqigufen.top/Article/details/gtjgjksfie.html

*)     echo "未知命令" ;;
来源：http://dali.iojbl.cn/Article/details/gtrdcsxqzi.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gtqxadfftp.html

[R12] for 遍历文件
来源：http://dali.shangyingyoupin.top/Article/details/gtmgwjmfsm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cucudq.cn/Article/details/gtqievgytd.html

[R13] for 计数循环
来源：http://dali.yj202588.top/Article/details/gtnjbzdgyw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gtgmyckgia.html

[R14] C 风格 for
来源：http://dali.hfpthk.cn/Article/details/gtdoqnkekf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gtddxnevfz.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gteviffgky.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shzxlz.cn/Article/details/gtecukjmmo.html

[R16] until 等待条件
来源：http://dali.ivvv.top/Article/details/gtthruehaj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hysaishi.cn/Article/details/gtosfhalbm.html

[R17] 数组定义与取值
来源：http://dali.haohaochexian.top/Article/details/gtazoywrak.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xziqi.cn/Article/details/gtigvzojlq.html

[R18] 遍历数组
来源：http://dali.hnqzz.top/Article/details/gtqrnkzzkg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shangyingyoupin.top/Article/details/gthtlqpsdw.html

[R19] 数组长度
来源：http://dali.wangdashe.top/Article/details/gtvbdthtsw.html

echo "${#arr[@]}"
来源：http://dali.sweek.top/Article/details/gtaciawueh.html

[R20] 关联数组（字典）
来源：http://dali.guowangkeji.top/Article/details/gtanieldte.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnxiangtu.top/Article/details/gtkxfizvhp.html

[R21] 字符串长度
来源：http://dali.jqgfzy.top/Article/details/gtkvcpzzsj.html

echo "${#s}"
来源：http://dali.zhongyouzk.top/Article/details/gtpzefxoda.html

[R22] 截取子串
来源：http://dali.havefunace.top/Article/details/gtlvunesii.html

echo "${s:0:5}"
来源：http://dali.fzhhl.top/Article/details/gtsidxqijx.html

[R23] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gtgihytapo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangdashe.top/Article/details/gtwcvwpspl.html

[R24] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gtgjmflewh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.pycfn.com/Article/details/gttsgzzpjk.html

[R25] 去后缀 / 去前缀
来源：http://dali.andypj.xyz/Article/details/gtxejtewjw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.316326.xyz/Article/details/gtuysiaweo.html

[R26] 命令替换
来源：http://dali.shzxlz.cn/Article/details/gtlxmyxwkj.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgufenzy.top/Article/details/gtqvztikgh.html

[R27] 算术展开
来源：http://dali.jyoumei.cn/Article/details/gtbhzbrmyd.html

echo $((1 + 2 * 3))
来源：http://dali.chenzaomai.com/Article/details/gtsmauninq.html

[R28] 浮点运算
来源：http://dali.gogol.net.cn/Article/details/gtfxptipcz.html

echo "scale=2; 10/3" | bc
来源：http://dali.nwbrower.top/Article/details/gtydwfwlto.html

[R29] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gtrwdfinbh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hysaishi.cn/Article/details/gtguzpkieo.html

[R30] 函数返回状态码
来源：http://dali.snrcjt.cn/Article/details/gteijtxxxm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pengpengdd.cyou/Article/details/gtzziynyuo.html

[R31] 局部变量
来源：http://dali.xinyue.icu/Article/details/gtlfdzibaz.html

f() { local x=1; echo "$x"; }
来源：http://dali.zdqjudy.top/Article/details/gtpzlmtpol.html

[R32] 参数个数校验
来源：http://dali.vqdsnc.cn/Article/details/gtmecqkkso.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xylfe.cn/Article/details/gtmvnhxvjt.html

[R33] 捕获错误并提示行号
来源：http://dali.yongpay.top/Article/details/gtcltkyqxs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinqigufen.top/Article/details/gtucohvqds.html

[R34] 退出时清理
来源：http://dali.hnxiangtu.top/Article/details/gtqhgrtskl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gteuyhndsv.html

[R35] 后台执行并等待
来源：http://dali.sufxvd.cn/Article/details/gtuojabozu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shuidangran.top/Article/details/gtkwfzdicu.html

[R36] 并发执行多个任务
来源：http://dali.chenlongwang.top/Article/details/gtkdqnbdie.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.quarkkingdee.top/Article/details/gtdvdttkpj.html

[R37] 把输出赋给变量
来源：http://dali.vqdsnc.cn/Article/details/gtagnmjsbk.html


<!-- 参考信息 -->