代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.pycfn.com/Article/details/gtnhvyrhou.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gtyscgoquz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtueuddxul.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxuanxn.top/Article/details/gtbjvgwsgp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yuanzhike.top/Article/details/gtzfqfphuk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gotoacloud.top/Article/details/gtlvwmrntp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jiagoushi.top/Article/details/gtmeotwxer.html

[P08] 处理浮点精度问题
来源：http://dali.haohaochexian.top/Article/details/gtrenhserb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj202588.top/Article/details/gtqpudshom.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yonumen.top/Article/details/gtpvdrfvub.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hammf.cn/Article/details/gtevgfjbxa.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ehwqpu.com/Article/details/gthpyoaddt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.redwolf501.top/Article/details/gtflpmvukc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dianchejie.cn/Article/details/gtvgvouwhn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigfzy.top/Article/details/gtflnyahfh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenjidiqi.icu/Article/details/gtjoixwlim.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtzxetrgfc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlefywsx.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gthbrjkxqs.html

[Q01] 创建表
来源：http://dali.wangshuangyany.cn/Article/details/gtpvfopwrd.html

CREATE TABLE users (
来源：http://dali.hysaishi.cn/Article/details/gtupegmybr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gtnaqgyhxp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gtammcluqo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.havefunace.top/Article/details/gtoyljhgze.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenzaomai.com/Article/details/gtywmfwjbm.html

);
来源：http://dali.aibaodan.cn/Article/details/gtjddzlykx.html

[Q02] 创建带外键的表
来源：http://dali.aibaodan.cn/Article/details/gtsslpmfsk.html

CREATE TABLE orders (
来源：http://dali.xylfe.cn/Article/details/gthkmggpyn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gtwoktrelt.html

user_id INT NOT NULL,
来源：http://dali.nanxinkj.top/Article/details/gtqvraiguu.html

amount DECIMAL(10, 2),
来源：http://dali.yanxiufei.cn/Article/details/gtczhcrunu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yueranfly.top/Article/details/gtcvetxjem.html

);
来源：http://dali.zdqjudy.top/Article/details/gtveqlgtno.html

[Q03] 增加列
来源：http://dali.tanke756.top/Article/details/gtbyvifouo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj20258888.top/Article/details/gtexnddlzo.html

[Q04] 修改列类型
来源：http://dali.daxiang520.top/Article/details/gtyxnhaheq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.aibaodan.cn/Article/details/gtlfuljrgc.html

[Q05] 重命名列
来源：http://dali.meibo888.top/Article/details/gtnvkehbwx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhoulong.xyz/Article/details/gtflmpjhjg.html

[Q06] 删除列
来源：http://dali.316326.xyz/Article/details/gtivegifsc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gtgseqcuoj.html

[Q07] 删除表
来源：http://dali.nwbrower.top/Article/details/gtaitblhkw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yanxiufei.cn/Article/details/gtdrotqzhz.html

[Q08] 创建普通索引
来源：http://dali.nwbrower.top/Article/details/gteubqmmqt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hysaishi.cn/Article/details/gtyfysioac.html

[Q09] 创建唯一索引
来源：http://dali.guannengcc.top/Article/details/gthsbkfbdb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gtzhopzvor.html

[Q10] 插入单行
来源：http://dali.yvedp.cn/Article/details/gtwnqmfzjm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj20258888.top/Article/details/gtnqnprvvw.html

[Q11] 一次插入多行
来源：http://dali.xziqi.cn/Article/details/gtpulnreai.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jqgufenzy.top/Article/details/gtzqvpywfb.html

[Q12] 插入后取自增 ID
来源：http://dali.zhengqikj.top/Article/details/gttzbkofnh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.daxiang520.top/Article/details/gtxiucmjro.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.havefunace.top/Article/details/gtbzjrpotq.html

[Q13] 忽略重复插入
来源：http://dali.guannengcc.top/Article/details/gtmgtbqlol.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ydzc1.top/Article/details/gtdkupxjoo.html

[Q14] 存在则更新（upsert）
来源：http://dali.gogol.net.cn/Article/details/gtynrxxekw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.dianchejie.cn/Article/details/gtzgjoosvt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ehwqpu.com/Article/details/gtdnnfxxmg.html

[Q15] 查询全部
来源：http://dali.cashguo.top/Article/details/gtdksfkwlx.html

SELECT * FROM users;
来源：http://dali.pycfn.com/Article/details/gtuzwqvdhk.html

[Q16] 查询指定列
来源：http://dali.fzhhl.top/Article/details/gtdspklfis.html

SELECT id, name FROM users;
来源：http://dali.nwbrower.top/Article/details/gtuxzkkwqa.html

[Q17] 条件查询
来源：http://dali.316326.xyz/Article/details/gtlcrhbaid.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guannengcc.top/Article/details/gtvpyrpxzy.html

[Q18] 模糊匹配
来源：http://dali.yj20258.top/Article/details/gtilzdltel.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkotoezte.html

[Q19] 范围查询
来源：http://dali.guannengcc.top/Article/details/gtyyndpbop.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.smart0.xyz/Article/details/gtpmxwhafv.html

[Q20] IN 列表
来源：http://dali.hywenlv.cn/Article/details/gtrhnbpxwb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtctgwgfou.html

[Q21] 空值判断
来源：http://dali.yongpay.top/Article/details/gtdxivlyyz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yangfankeji.com/Article/details/gtkdslvvfb.html

[Q22] 排序
来源：http://dali.sxryk.cn/Article/details/gtbluyrwcc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hfpthk.cn/Article/details/gtlitdgfph.html

[Q23] 分页
来源：http://dali.yj202588.top/Article/details/gtvjayamsr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.mhx1999.top/Article/details/gtzfkrklzl.html

[Q24] 去重
来源：http://dali.ppjwa.cn/Article/details/gttqqshbto.html

SELECT DISTINCT city FROM users;
来源：http://dali.yvedp.cn/Article/details/gtrbicizqs.html

[Q25] 只取前 N 条
来源：http://dali.zhoulong.xyz/Article/details/gtvgbttbbb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.meibo888.top/Article/details/gtixncmgju.html

[Q26] 计数
来源：http://dali.cashguo.top/Article/details/gtcftumbuh.html

SELECT COUNT(*) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtrodmpctx.html

[Q27] 条件计数
来源：http://dali.haohaochexian.top/Article/details/gtjuxpmzaw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozqygfpg.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaarhqwiy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtgvwkenbd.html

[Q29] 最大最小值
来源：http://dali.xuanzx.com/Article/details/gtoraevtfn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtkqmaydvt.html

[Q30] 分组统计
来源：http://dali.wangshuangyany.cn/Article/details/gtpdohwjhu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gthvkybuie.html

[Q31] 分组后过滤
来源：http://dali.cdnleiting.top/Article/details/gttzkpygyu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xylfe.cn/Article/details/gthifhelzg.html

[Q32] 分组拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gtxrczeosz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gtqoczbttc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj202588.top/Article/details/gtndvytxhk.html

[Q33] 多列分组
来源：http://dali.pengpengdd.cyou/Article/details/gtemguzdeq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gotoacloud.top/Article/details/gtqxjzngiw.html

[Q34] 每组取第一条
来源：http://dali.bjfxy.top/Article/details/gtkhwxdohc.html

SELECT * FROM (
来源：http://dali.sxryk.cn/Article/details/gtxfwjeqry.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ivvv.top/Article/details/gtqlplwmvg.html

) t WHERE rn = 1;
来源：http://dali.c1oappe.top/Article/details/gtmzhmjowc.html

[Q35] 内连接
来源：http://dali.snrcjt.cn/Article/details/gtfrpqjohc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gtauzwttbv.html

[Q36] 左连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtsagvjhgi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gtkauptmlm.html

[Q37] 右连接
来源：http://dali.haohaochexian.top/Article/details/gtajgatbtu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.0kj1m.cn/Article/details/gtnifsnvxh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.0kj1m.cn/Article/details/gtegchopib.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fengsongda.top/Article/details/gtepnawsov.html

[Q39] 自连接（查上下级）
来源：http://dali.xinyue.icu/Article/details/gtewvmbebc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.fengsongda.top/Article/details/gtmxfvgoko.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tianlin.xyz/Article/details/gtobvosqxs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zycfv.cn/Article/details/gtuiwasozj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zycfv.cn/Article/details/gteidqqafs.html

[Q41] 多表连接
来源：http://dali.yueranfly.top/Article/details/gtneqwtnym.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotjewmct.html

JOIN users u ON u.id = o.user_id
来源：http://dali.pengpengdd.cyou/Article/details/gtlzkezdnz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.birdmap.top/Article/details/gtujvdfyxp.html

[Q42] 连接条件附加过滤
来源：http://dali.yueranfly.top/Article/details/gtzrjmbwac.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hongshengwenyu.top/Article/details/gtpsgxwmzv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zdqjudy.top/Article/details/gtlarmtusy.html

[Q43] 标量子查询
来源：http://dali.xylfe.cn/Article/details/gtokfabkpv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.haohaochexian.top/Article/details/gtfhnyunuz.html

[Q44] IN 子查询
来源：http://dali.haohaochexian.top/Article/details/gtzgpzxkav.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcryglwpy.html

[Q45] EXISTS 判断存在
来源：http://dali.yonumen.top/Article/details/gtthiowygu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhixingplan.top/Article/details/gtxtbtesgs.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jianghu66.top/Article/details/gtuzsnlvns.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenlongwang.top/Article/details/gtlmchphzl.html

[Q47] 与平均值比较
来源：http://dali.jinqigufen.top/Article/details/gtcrhaxkqp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenlongwang.top/Article/details/gttrylntzi.html

[Q48] CTE 公用表表达式
来源：http://dali.birdmap.top/Article/details/gtjhcjxgkq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhoulong.xyz/Article/details/gtmcybkits.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gzhubu.top/Article/details/gtextmfczt.html

[Q49] 更新单行
来源：http://dali.dianchejie.cn/Article/details/gtkuklqvxy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gotoacloud.top/Article/details/gtphdpnxci.html

[Q50] 批量更新
来源：http://dali.ehwqpu.com/Article/details/gtcgabqbdk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jianghu66.top/Article/details/gtuiipxuwm.html

[Q51] 用子查询更新
来源：http://dali.ydzc1.top/Article/details/gtdwyumqip.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hnqzz.top/Article/details/gtndshwxlj.html

[Q52] 删除指定行
来源：http://dali.9152youxi.cn/Article/details/gtistepkub.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ybcxt.top/Article/details/gtztqnujaz.html

[Q53] 按条件删除
来源：http://dali.jyoumei.cn/Article/details/gtuzkbdnab.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daxiang520.top/Article/details/gtlxkvuzlv.html

[Q54] 清空表
来源：http://dali.ydzc1.top/Article/details/gttswkzygo.html

TRUNCATE TABLE logs;
来源：http://dali.jinqigufen.top/Article/details/gtkdiiwjpv.html

[Q55] 排名（并列占位）
来源：http://dali.ybcxt.top/Article/details/gtkrtdcxks.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gtjwhypvxf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhixingplan.top/Article/details/gtrhnlsktt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.316326.xyz/Article/details/gtobobkqbj.html

[Q57] 行号
来源：http://dali.cucudq.cn/Article/details/gtzqfegdhv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtuywpwctn.html

[Q58] 累计求和
来源：http://dali.aizwys.cn/Article/details/gtyfljbtph.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtbqxioqso.html

[Q59] 分组内累计
来源：http://dali.hnxiangtu.top/Article/details/gtgeoslwlk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gthxmovwkj.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj20258.top/Article/details/gtepcpclnm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hongshengwenyu.top/Article/details/gtclkvodad.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtwrolmtxy.html

[Q61] 移动平均
来源：http://dali.cdnleiting.top/Article/details/gtvywmhdba.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtibxczrdn.html

[Q62] 分组占比
来源：http://dali.vqdsnc.cn/Article/details/gtdjchpwkh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gtdtdxkwcl.html

[Q63] 开启事务
来源：http://dali.nanxuanxn.top/Article/details/gtinyleoxs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fengsongda.top/Article/details/gthoujdxzl.html

[Q64] 提交事务
来源：http://dali.yangfankeji.com/Article/details/gtwimweyta.html

COMMIT;
来源：http://dali.jiagoushi.top/Article/details/gtssudvnzm.html

[Q65] 回滚事务
来源：http://dali.yongpay.top/Article/details/gtpiticggz.html

ROLLBACK;
来源：http://dali.chenlongwang.top/Article/details/gtmjahykes.html

[Q66] 行锁查询
来源：http://dali.sweek.top/Article/details/gtpknxnjwg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cdnleiting.top/Article/details/gtwlmjegmj.html

[Q67] 设置隔离级别
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzxdydawr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yonumen.top/Article/details/gtdljtcxzj.html

[Q68] 保存点
来源：http://dali.jinqigfzy.top/Article/details/gtppchcatt.html

SAVEPOINT sp1;
来源：http://dali.dashuyun.cn/Article/details/gtsngzednh.html

ROLLBACK TO sp1;
来源：http://dali.jinqigufen.top/Article/details/gtddtgcrid.html

[Q69] 查看执行计划
来源：http://dali.jinqigufen.top/Article/details/gtmpjywney.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.dianchejie.cn/Article/details/gtvjwbzsxz.html

[Q70] 更新统计信息
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqcouuwm.html

ANALYZE TABLE users;
来源：http://dali.sufxvd.cn/Article/details/gtzjmqbsnc.html

[Q71] 查看建表语句
来源：http://dali.yuanzhike.top/Article/details/gtujbozhnu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yongpay.top/Article/details/gtfkczezex.html

[Q72] 查看索引
来源：http://dali.yongpay.top/Article/details/gtcpsvyalh.html

SHOW INDEX FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtnuhlhkup.html

[Q73] 查看表状态
来源：http://dali.fengsongda.top/Article/details/gtwhevwbry.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hywenlv.cn/Article/details/gtwvfgwcsl.html

[Q74] 强制使用索引
来源：http://dali.chenlongwang.top/Article/details/gtbknegooi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.fzhhl.top/Article/details/gtytbagwal.html

[Q75] 日期格式化
来源：http://dali.cashguo.top/Article/details/gteajdbuhb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtmfjwrlfv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aibaodan.cn/Article/details/gtishxztpr.html

[Q76] 按天统计
来源：http://dali.zdqjudy.top/Article/details/gtsnvbpkwi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.guannengcc.top/Article/details/gtbvaxesbl.html

[Q77] 时间加减
来源：http://dali.wangshuangyany.cn/Article/details/gthwlswhrf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cqqwz.cn/Article/details/gtmuebhzry.html

[Q78] 当前时间
来源：http://dali.iojbl.cn/Article/details/gtbwdccnpq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yangfankeji.com/Article/details/gtmblmvhnu.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gtesvvyoap.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gtpwcoclhv.html

[Q80] 字符串截取
来源：http://dali.nwbrower.top/Article/details/gtmnzxygfc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtsqfwba.html

[Q81] 字符串替换
来源：http://dali.yj20258.top/Article/details/gtyjmowpvi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fengsongda.top/Article/details/gtxmczoner.html

[Q82] 字符长度与字节长度
来源：http://dali.zhengqikj.top/Article/details/gtjwrogjde.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtmsdjvqbp.html

[Q83] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gtqzdgvgwm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtebbfjfev.html

[Q84] 去除首尾空格
来源：http://dali.c1oappe.top/Article/details/gtazfmsmsy.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmsqynesq.html

[Q85] 数值取整
来源：http://dali.guannengcc.top/Article/details/gtickiwxug.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yvedp.cn/Article/details/gtskmlzeoq.html

[Q86] 读取 JSON 字段
来源：http://dali.zhixingplan.top/Article/details/gtrxegsztd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtunvitgbk.html

[Q87] JSON 字段做条件
来源：http://dali.ybcxt.top/Article/details/gtamgxmwhv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shanyushiyangtech.top/Article/details/gtumswjevy.html

[Q88] 行转列（条件聚合）
来源：http://dali.gogol.net.cn/Article/details/gtdgtulqno.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.aizwys.cn/Article/details/gtqmougjki.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenzaomai.com/Article/details/gticfvzvuo.html

[Q89] 判断表是否存在
来源：http://dali.zhongyouzk.top/Article/details/gttvtnxwgp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hongshengwenyu.top/Article/details/gtbfelqtar.html

[Q90] 生成序号列
来源：http://dali.kuanghao11.cn/Article/details/gtwttfeouc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sweek.top/Article/details/gtmhxxgvil.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtuubisnmd.html

R. Bash 专题
来源：http://dali.dianchejie.cn/Article/details/gtodkansgu.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtwjdxspan.html

[R01] shebang 与严格模式
来源：http://dali.dianchejie.cn/Article/details/gtqtzytemn.html

#!/usr/bin/env bash
来源：http://dali.jinqigufen.top/Article/details/gtaforwbou.html

set -euo pipefail
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqhyngpq.html

[R02] 变量赋值与使用
来源：http://dali.jqgufenzy.top/Article/details/gtbbmmrgol.html

name="Tom"; echo "$name"
来源：http://dali.sweek.top/Article/details/gtjpgaorbi.html

[R03] 只读变量
来源：http://dali.gotoacloud.top/Article/details/gtmeqlysaj.html

readonly PI=3.14
来源：http://dali.sweek.top/Article/details/gtzuyjtqkz.html

[R04] 位置参数
来源：http://dali.hfpthk.cn/Article/details/gtymihuppl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.smart0.xyz/Article/details/gtgpsworan.html

[R05] 参数默认值
来源：http://dali.chenjidiqi.icu/Article/details/gtbotwgjts.html

name="${1:-default}"
来源：http://dali.ehwqpu.com/Article/details/gtcrhylrvm.html

[R06] 判断命令是否存在
来源：http://dali.yonumen.top/Article/details/gtqljzafpg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gtjjvshvub.html

[R07] if 判断文件
来源：http://dali.dashuyun.cn/Article/details/gtxlyvidli.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.guannengcc.top/Article/details/gtahqsmrbj.html

[R08] 数值比较
来源：http://dali.dashuyun.cn/Article/details/gttjusxqui.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.c1oappe.top/Article/details/gthcyiqdwh.html

[R09] 字符串比较
来源：http://dali.dashuyun.cn/Article/details/gtovujzafz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuanzx.com/Article/details/gtyqzyafxs.html

[R10] 正则匹配
来源：http://dali.ivvv.top/Article/details/gtbslwkcaj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenzaomai.com/Article/details/gtghzlwyda.html

[R11] case 多分支
来源：http://dali.shangyingyoupin.top/Article/details/gtztqwdvwo.html

case "$1" in
来源：http://dali.hysaishi.cn/Article/details/gtymnuybor.html

start) echo "启动" ;;
来源：http://dali.yonumen.top/Article/details/gtjpjvvlxf.html

stop)  echo "停止" ;;
来源：http://dali.guowangkeji.top/Article/details/gteakcjxnf.html

*)     echo "未知命令" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzgwzjyl.html

esac
来源：http://dali.feifeiyinyue.top/Article/details/gtijfyfich.html

[R12] for 遍历文件
来源：http://dali.snrcjt.cn/Article/details/gtrnbaxpic.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jlsjyb.cn/Article/details/gtxfvqhoii.html

[R13] for 计数循环
来源：http://dali.haohaochexian.top/Article/details/gtzxwnnqhc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gtqhscagev.html

[R14] C 风格 for
来源：http://dali.snrcjt.cn/Article/details/gtflavxpbw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hnqzz.top/Article/details/gtrzmhtgcz.html

[R15] while 逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtsjwsvqxt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jyoumei.cn/Article/details/gtkfdubzga.html

[R16] until 等待条件
来源：http://dali.hongshengwenyu.top/Article/details/gtjpskyoxu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwyectzh.html

[R17] 数组定义与取值
来源：http://dali.ppjwa.cn/Article/details/gtelnfznnh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.kuanghao11.cn/Article/details/gtnsqcgccx.html

[R18] 遍历数组
来源：http://dali.xziqi.cn/Article/details/gtywxlmndx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtiqouefwf.html

[R19] 数组长度
来源：http://dali.yueranfly.top/Article/details/gthmblyjcq.html

echo "${#arr[@]}"
来源：http://dali.zhoulong.xyz/Article/details/gthcvcscvq.html

[R20] 关联数组（字典）
来源：http://dali.cqqwz.cn/Article/details/gteoofgkei.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258.top/Article/details/gtdqsczsca.html

[R21] 字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gtuznrnhif.html

echo "${#s}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqxyexrj.html

[R22] 截取子串
来源：http://dali.havefunace.top/Article/details/gtfdnfcgfk.html

echo "${s:0:5}"
来源：http://dali.wangdashe.top/Article/details/gtgydzlygu.html

[R23] 字符串替换
来源：http://dali.pycfn.com/Article/details/gtgdzshacx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zycfv.cn/Article/details/gtzqiktmbu.html

[R24] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gtzgrkbcdw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shuidangran.top/Article/details/gtijgvbusx.html

[R25] 去后缀 / 去前缀
来源：http://dali.xylfe.cn/Article/details/gtibeolgas.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj20258888.top/Article/details/gtdynogiyp.html

[R26] 命令替换
来源：http://dali.xuanzx.com/Article/details/gtugwlddgu.html

now=$(date +%F); echo "$now"
来源：http://dali.aibaodan.cn/Article/details/gtazmrzccg.html

[R27] 算术展开
来源：http://dali.9152youxi.cn/Article/details/gtpuocmcax.html

echo $((1 + 2 * 3))
来源：http://dali.zhoulong.xyz/Article/details/gtfpgoskkl.html

[R28] 浮点运算
来源：http://dali.jqgfzy.top/Article/details/gthypspqmj.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuanzx.com/Article/details/gtpbrctlmw.html

[R29] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gtkljwtccz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hysaishi.cn/Article/details/gtqenwhilv.html

[R30] 函数返回状态码
来源：http://dali.shuidangran.top/Article/details/gtousludjo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.havefunace.top/Article/details/gtjpytpcka.html

[R31] 局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gttjtebory.html

f() { local x=1; echo "$x"; }
来源：http://dali.dashuyun.cn/Article/details/gtvdabxoqq.html

[R32] 参数个数校验
来源：http://dali.daria6918.cn/Article/details/gtrnhvbwpu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.kuanghao11.cn/Article/details/gtmuaklurn.html

[R33] 捕获错误并提示行号
来源：http://dali.tanke756.top/Article/details/gthojmmzsw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ehwqpu.com/Article/details/gthvvsrbii.html

[R34] 退出时清理
来源：http://dali.yuxming.cn/Article/details/gtvnbqlqae.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gtbtwlrrgh.html

[R35] 后台执行并等待
来源：http://dali.snrcjt.cn/Article/details/gtxzodgmca.html


<!-- 参考信息 -->