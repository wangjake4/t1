代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbcprncnh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gtkyravnnk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.svipenyu.cn/Article/details/gteytxcsgu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hysaishi.cn/Article/details/gtnurjkfbm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjtteyje.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jyoumei.cn/Article/details/gtitucoiqk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fzhhl.top/Article/details/gtdjpyfjhu.html

[P08] 处理浮点精度问题
来源：http://dali.chenzaomai.com/Article/details/gtetmfgvzg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jianghu66.top/Article/details/gttprsswjp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhnnurcz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.bjfxy.top/Article/details/gtsctoaggp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cucudq.cn/Article/details/gtvfwxjucf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jyoumei.cn/Article/details/gtsqldtszc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gaohongyu789.top/Article/details/gtjdjzcgxe.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhiwuduotai.top/Article/details/gtrizhadvl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.vqdsnc.cn/Article/details/gtpssednik.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtojueywdw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ivvv.top/Article/details/gtkuzleuyl.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtcyrntgmf.html

[Q01] 创建表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkcvcwcal.html

CREATE TABLE users (
来源：http://dali.vqdsnc.cn/Article/details/gtxnzlsnkd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hammf.cn/Article/details/gtnfkxyviy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.daxiang520.top/Article/details/gtyoyecsmq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shzxlz.cn/Article/details/gtvegagodo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.dashuyun.cn/Article/details/gtkxbwtddz.html

);
来源：http://dali.xuanzx.com/Article/details/gttfkvtrnt.html

[Q02] 创建带外键的表
来源：http://dali.tianlin.xyz/Article/details/gtitgtftns.html

CREATE TABLE orders (
来源：http://dali.andypj.xyz/Article/details/gthkynnyby.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gtcjopkbzv.html

user_id INT NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gtjtwwrifz.html

amount DECIMAL(10, 2),
来源：http://dali.dashuyun.cn/Article/details/gtduziyher.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dianchejie.cn/Article/details/gtweboipdf.html

);
来源：http://dali.xziqi.cn/Article/details/gthgcbupmd.html

[Q03] 增加列
来源：http://dali.dashuyun.cn/Article/details/gteneoktvn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jqgufenzy.top/Article/details/gtpeaflhvo.html

[Q04] 修改列类型
来源：http://dali.pengpengdd.cyou/Article/details/gtmlshfzju.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cashguo.top/Article/details/gtfrxoxbrb.html

[Q05] 重命名列
来源：http://dali.gogol.net.cn/Article/details/gtolewqvps.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zdqjudy.top/Article/details/gtotgsnqnn.html

[Q06] 删除列
来源：http://dali.xinyue.icu/Article/details/gtjgkdnior.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.316326.xyz/Article/details/gtejuzrqiy.html

[Q07] 删除表
来源：http://dali.daxiang520.top/Article/details/gtmxgydnjr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqgiunql.html

[Q08] 创建普通索引
来源：http://dali.jinqigufen.top/Article/details/gtlvgfjrlk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.316326.xyz/Article/details/gtzjjvlmjj.html

[Q09] 创建唯一索引
来源：http://dali.pycfn.com/Article/details/gtmqmzmbzy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hammf.cn/Article/details/gthbjplwmq.html

[Q10] 插入单行
来源：http://dali.jyoumei.cn/Article/details/gtrgwjavix.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj20258.top/Article/details/gtomtyskfj.html

[Q11] 一次插入多行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxuyxjem.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.andypj.xyz/Article/details/gtoxewkxcm.html

[Q12] 插入后取自增 ID
来源：http://dali.9152youxi.cn/Article/details/gtrzyubirj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yangfankeji.com/Article/details/gtoespngpi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jqgfzy.top/Article/details/gtddmwmntc.html

[Q13] 忽略重复插入
来源：http://dali.wangshuangyany.cn/Article/details/gtfisubdrh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xuanzx.com/Article/details/gtpvlsqqot.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhaomingkeji.xyz/Article/details/gticxjgdst.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jqgfzy.top/Article/details/gtsjxpgjfb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hammf.cn/Article/details/gttesieegf.html

[Q15] 查询全部
来源：http://dali.yueranfly.top/Article/details/gtjzyvbars.html

SELECT * FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtwtzydfgz.html

[Q16] 查询指定列
来源：http://dali.wangshuangyany.cn/Article/details/gtxknbgbnz.html

SELECT id, name FROM users;
来源：http://dali.wangdashe.top/Article/details/gtzwcofynb.html

[Q17] 条件查询
来源：http://dali.dianchejie.cn/Article/details/gtkxftbhit.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.birdmap.top/Article/details/gtnrirdbpx.html

[Q18] 模糊匹配
来源：http://dali.nanxinkj.top/Article/details/gtqghabvak.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnyffwor.html

[Q19] 范围查询
来源：http://dali.redwolf501.top/Article/details/gtjpqikagk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cheryme.top/Article/details/gtaijotypi.html

[Q20] IN 列表
来源：http://dali.ydzc1.top/Article/details/gtgfelxwnl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tianlin.xyz/Article/details/gtmknogggg.html

[Q21] 空值判断
来源：http://dali.yj20258888.top/Article/details/gtlinelibo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.iojbl.cn/Article/details/gtshnfhvta.html

[Q22] 排序
来源：http://dali.nwbrower.top/Article/details/gtbfoqkeap.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gzhubu.top/Article/details/gtotdqbszn.html

[Q23] 分页
来源：http://dali.svipenyu.cn/Article/details/gtolyglill.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnzcavrf.html

[Q24] 去重
来源：http://dali.cashguo.top/Article/details/gtmkgoaqnd.html

SELECT DISTINCT city FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtzkxzwbac.html

[Q25] 只取前 N 条
来源：http://dali.hammf.cn/Article/details/gthtsqcqpt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nanxinkj.top/Article/details/gtaayuqmjn.html

[Q26] 计数
来源：http://dali.smart0.xyz/Article/details/gtnaslrdvz.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtklleutzx.html

[Q27] 条件计数
来源：http://dali.snrcjt.cn/Article/details/gtejsavyna.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtpkqnrinp.html

[Q28] 求和与平均
来源：http://dali.vqdsnc.cn/Article/details/gtpmljabsn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtzkhleqhb.html

[Q29] 最大最小值
来源：http://dali.daxiang520.top/Article/details/gtpyrenckp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.birdmap.top/Article/details/gtcihgioen.html

[Q30] 分组统计
来源：http://dali.gzhubu.top/Article/details/gtulzsbmdf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqwcxsdsz.html

[Q31] 分组后过滤
来源：http://dali.yvedp.cn/Article/details/gtqgvainvp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.aizwys.cn/Article/details/gtswbtgnzo.html

[Q32] 分组拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gtuhmyoxlh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gtzxyjvdyo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hfpthk.cn/Article/details/gtilkucsad.html

[Q33] 多列分组
来源：http://dali.redwolf501.top/Article/details/gtnmqizwce.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.bjfxy.top/Article/details/gtxothehtb.html

[Q34] 每组取第一条
来源：http://dali.bjfxy.top/Article/details/gtlssbiyrz.html

SELECT * FROM (
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqysrappl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yuxming.cn/Article/details/gtjlygpcmy.html

) t WHERE rn = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtziqsbppn.html

[Q35] 内连接
来源：http://dali.tanke756.top/Article/details/gtjlpucler.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shzxlz.cn/Article/details/gtkurpdcbn.html

[Q36] 左连接
来源：http://dali.hnxiangtu.top/Article/details/gtodqdvblo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xinyue.icu/Article/details/gtnuualwpa.html

[Q37] 右连接
来源：http://dali.iojbl.cn/Article/details/gtmdmdiqxs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.aibaodan.cn/Article/details/gtqqjzulyw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhengqikj.top/Article/details/gtdckkssux.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nanxinkj.top/Article/details/gtvfgnujgr.html

[Q39] 自连接（查上下级）
来源：http://dali.cashguo.top/Article/details/gtcvwhphtm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.snrcjt.cn/Article/details/gtfpoovzaz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cashguo.top/Article/details/gtmgbnbjzf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.dianchejie.cn/Article/details/gtcibochdl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.snrcjt.cn/Article/details/gttvomgrte.html

[Q41] 多表连接
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtfatidq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gaohongyu789.top/Article/details/gtvvbotjoa.html

JOIN users u ON u.id = o.user_id
来源：http://dali.guowangkeji.top/Article/details/gtnomijres.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtoxvlnrcs.html

[Q42] 连接条件附加过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaijapmsw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hywenlv.cn/Article/details/gtyadrmpui.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hysaishi.cn/Article/details/gtoggxazvo.html

[Q43] 标量子查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfdliwhk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hysaishi.cn/Article/details/gtzzjipodv.html

[Q44] IN 子查询
来源：http://dali.snrcjt.cn/Article/details/gtacrsobfx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yangfankeji.com/Article/details/gtudmoyswu.html

[Q45] EXISTS 判断存在
来源：http://dali.fengsongda.top/Article/details/gtmhfhbjvh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jlsjyb.cn/Article/details/gtowzafmei.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.kuanghao11.cn/Article/details/gtmjronxyd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangtech.top/Article/details/gtppgratjv.html

[Q47] 与平均值比较
来源：http://dali.yj20258888.top/Article/details/gtnvpxufpm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhoulong.xyz/Article/details/gthfdlanlp.html

[Q48] CTE 公用表表达式
来源：http://dali.birdmap.top/Article/details/gtrkdesoff.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvzvhsdr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jianghu66.top/Article/details/gttxsnpefx.html

[Q49] 更新单行
来源：http://dali.yj20258.top/Article/details/gtyyrffxof.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xinyue.icu/Article/details/gtmboznnon.html

[Q50] 批量更新
来源：http://dali.yvedp.cn/Article/details/gttrcrhuxz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258888.top/Article/details/gtrztckcow.html

[Q51] 用子查询更新
来源：http://dali.aizwys.cn/Article/details/gtaugayjxo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtruyqtprf.html

[Q52] 删除指定行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffktehoz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gtienoizgu.html

[Q53] 按条件删除
来源：http://dali.cheryme.top/Article/details/gtvlzdnesq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfgdqswl.html

[Q54] 清空表
来源：http://dali.pengpengdd.cyou/Article/details/gthkhraesd.html

TRUNCATE TABLE logs;
来源：http://dali.gotoacloud.top/Article/details/gtaaxxaapz.html

[Q55] 排名（并列占位）
来源：http://dali.jyoumei.cn/Article/details/gthusiafhh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nanxuanxn.top/Article/details/gtjfqebuup.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jyoumei.cn/Article/details/gtddzsmrof.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.pengpengdd.cyou/Article/details/gtlyerbwjd.html

[Q57] 行号
来源：http://dali.cashguo.top/Article/details/gtxuoeiizl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtqvbcngbi.html

[Q58] 累计求和
来源：http://dali.daria6918.cn/Article/details/gtejktemxu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtdwwjague.html

[Q59] 分组内累计
来源：http://dali.vqdsnc.cn/Article/details/gtxacqasnf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtrrvgxsuo.html

[Q60] 取上一行 / 下一行
来源：http://dali.xziqi.cn/Article/details/gtbudbuvlm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nanxinkj.top/Article/details/gtaxxponzh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtwiowereu.html

[Q61] 移动平均
来源：http://dali.wangshuangyany.cn/Article/details/gtwlneouca.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ivvv.top/Article/details/gtmpgajgyw.html

[Q62] 分组占比
来源：http://dali.xylfe.cn/Article/details/gtpzkxnfot.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gtcthxnupq.html

[Q63] 开启事务
来源：http://dali.yanxiufei.cn/Article/details/gtluzflmht.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenzaomai.com/Article/details/gtwkpldtbd.html

[Q64] 提交事务
来源：http://dali.ppjwa.cn/Article/details/gtmguqqblq.html

COMMIT;
来源：http://dali.dashuyun.cn/Article/details/gtshkvzryo.html

[Q65] 回滚事务
来源：http://dali.hnqzz.top/Article/details/gtxfopuoxx.html

ROLLBACK;
来源：http://dali.zhixingplan.top/Article/details/gtakyrxkeq.html

[Q66] 行锁查询
来源：http://dali.sweek.top/Article/details/gtpiwcnjmh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.svipenyu.cn/Article/details/gtoetccwaf.html

[Q67] 设置隔离级别
来源：http://dali.redwolf501.top/Article/details/gtybskospk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.vqdsnc.cn/Article/details/gtpdzcauag.html

[Q68] 保存点
来源：http://dali.hywenlv.cn/Article/details/gtlkcddqtc.html

SAVEPOINT sp1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwumbtit.html

ROLLBACK TO sp1;
来源：http://dali.cheryme.top/Article/details/gtuoltcigw.html

[Q69] 查看执行计划
来源：http://dali.xylfe.cn/Article/details/gtmpnvtrbm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hongshengwenyu.top/Article/details/gtuhgvitta.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gtlraumvkp.html

ANALYZE TABLE users;
来源：http://dali.jiagoushi.top/Article/details/gtalhvviof.html

[Q71] 查看建表语句
来源：http://dali.jlsjyb.cn/Article/details/gtjkjzuzlr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.bjfxy.top/Article/details/gthzbuqewj.html

[Q72] 查看索引
来源：http://dali.xuetiantiany.cn/Article/details/gtukuhdmrq.html

SHOW INDEX FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtnigwzbmd.html

[Q73] 查看表状态
来源：http://dali.0kj1m.cn/Article/details/gtxtiacjvc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangdashe.top/Article/details/gtbqyxkxdu.html

[Q74] 强制使用索引
来源：http://dali.xinyue.icu/Article/details/gtszxiurme.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gogol.net.cn/Article/details/gturegutug.html

[Q75] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdabpxgyt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtqzavxgjb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.kuanghao11.cn/Article/details/gtzcequhja.html

[Q76] 按天统计
来源：http://dali.ppjwa.cn/Article/details/gtalukbbsh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jianghu66.top/Article/details/gtfvmfpotw.html

[Q77] 时间加减
来源：http://dali.cqqwz.cn/Article/details/gtqczkaeug.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yangfankeji.com/Article/details/gtnbegpcyx.html

[Q78] 当前时间
来源：http://dali.gzhubu.top/Article/details/gtkvmcigxr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cashguo.top/Article/details/gthhwpyaiy.html

[Q79] 字符串拼接
来源：http://dali.yongpay.top/Article/details/gtjcquertp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yuxming.cn/Article/details/gtaxjcskbv.html

[Q80] 字符串截取
来源：http://dali.jqgfzy.top/Article/details/gteneuitts.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtvqqukaoy.html

[Q81] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gtqtmkrkgv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtjpsoiwcm.html

[Q82] 字符长度与字节长度
来源：http://dali.sxryk.cn/Article/details/gthsnrkuzs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtzyfuhtzh.html

[Q83] 大小写转换
来源：http://dali.hnxiangtu.top/Article/details/gtpedstxck.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtcbssbzdi.html

[Q84] 去除首尾空格
来源：http://dali.nwbrower.top/Article/details/gtvxsqeazk.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtiapxiblj.html

[Q85] 数值取整
来源：http://dali.0kj1m.cn/Article/details/gtkxygquhx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhixingplan.top/Article/details/gtibpzfizt.html

[Q86] 读取 JSON 字段
来源：http://dali.yongpay.top/Article/details/gtezhvrclv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.haohaochexian.top/Article/details/gtcyyqkmvb.html

[Q87] JSON 字段做条件
来源：http://dali.tanke756.top/Article/details/gtbvcpziay.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hammf.cn/Article/details/gtshsmbhas.html

[Q88] 行转列（条件聚合）
来源：http://dali.fengsongda.top/Article/details/gtzgszrckt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.birdmap.top/Article/details/gtqrhqpvll.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtsflfckvn.html

[Q89] 判断表是否存在
来源：http://dali.sweek.top/Article/details/gttpmiqaet.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yangfankeji.com/Article/details/gtqjhbghop.html

[Q90] 生成序号列
来源：http://dali.redwolf501.top/Article/details/gtlqarpfew.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenjidiqi.icu/Article/details/gttqhlziea.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtgaukoikd.html

R. Bash 专题
来源：http://dali.aizwys.cn/Article/details/gtkkolufyv.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gthxqntxvq.html

[R01] shebang 与严格模式
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlrddqdh.html

#!/usr/bin/env bash
来源：http://dali.ydzc1.top/Article/details/gttauvkhni.html

set -euo pipefail
来源：http://dali.hysaishi.cn/Article/details/gtxzjwnwjh.html

[R02] 变量赋值与使用
来源：http://dali.316326.xyz/Article/details/gtltvjujbx.html

name="Tom"; echo "$name"
来源：http://dali.zhiwuduotai.top/Article/details/gtvgytrrah.html

[R03] 只读变量
来源：http://dali.aizwys.cn/Article/details/gtfstoyfea.html

readonly PI=3.14
来源：http://dali.hysaishi.cn/Article/details/gttjjndcvh.html

[R04] 位置参数
来源：http://dali.birdmap.top/Article/details/gtidmutnwo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.dashuyun.cn/Article/details/gtrhyunrcj.html

[R05] 参数默认值
来源：http://dali.nanxuanxn.top/Article/details/gttymcjguu.html

name="${1:-default}"
来源：http://dali.svipenyu.cn/Article/details/gtucpvdylx.html

[R06] 判断命令是否存在
来源：http://dali.mhx1999.top/Article/details/gtbrkagulv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yangfankeji.com/Article/details/gtbsfwaaow.html

[R07] if 判断文件
来源：http://dali.jinqigfzy.top/Article/details/gtgfioiyoy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.9152youxi.cn/Article/details/gtducxxkuw.html

[R08] 数值比较
来源：http://dali.cheryme.top/Article/details/gtvruwjwrk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zdqjudy.top/Article/details/gtaoszglgx.html

[R09] 字符串比较
来源：http://dali.fzhhl.top/Article/details/gtbbbbtuwx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.havefunace.top/Article/details/gtxarbedks.html

[R10] 正则匹配
来源：http://dali.chenzaomai.com/Article/details/gtskcqcwhk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.bjfxy.top/Article/details/gtsqsfqsif.html

[R11] case 多分支
来源：http://dali.andypj.xyz/Article/details/gtiqbgbruo.html

case "$1" in
来源：http://dali.hnqzz.top/Article/details/gtbdkakxqq.html

start) echo "启动" ;;
来源：http://dali.chenzaomai.com/Article/details/gtyjoteljk.html

stop)  echo "停止" ;;
来源：http://dali.ybcxt.top/Article/details/gtvsdheoln.html

*)     echo "未知命令" ;;
来源：http://dali.dashuyun.cn/Article/details/gtyiiepvcr.html

esac
来源：http://dali.andypj.xyz/Article/details/gtlnechink.html

[R12] for 遍历文件
来源：http://dali.nanxinkj.top/Article/details/gtbsxeaniw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ppjwa.cn/Article/details/gtmlrmasvc.html

[R13] for 计数循环
来源：http://dali.jlsjyb.cn/Article/details/gtgzatupsk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gtguzxatrk.html

[R14] C 风格 for
来源：http://dali.xuetiantiany.cn/Article/details/gtearxdsoq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gtlorklnrf.html

[R15] while 逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtsdioivel.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fzhhl.top/Article/details/gtngwlbstz.html

[R16] until 等待条件
来源：http://dali.dianchejie.cn/Article/details/gtiqiaytis.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gtqgubrynd.html

[R17] 数组定义与取值
来源：http://dali.zhongyouzk.top/Article/details/gtcgyfmlsw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yanxiufei.cn/Article/details/gtnfgrxeth.html

[R18] 遍历数组
来源：http://dali.gogol.net.cn/Article/details/gtwyfubkqg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhongyouzk.top/Article/details/gtnazscjty.html

[R19] 数组长度
来源：http://dali.daxiang520.top/Article/details/gtypzpszvr.html

echo "${#arr[@]}"
来源：http://dali.yuxming.cn/Article/details/gtuvfqojbc.html

[R20] 关联数组（字典）
来源：http://dali.dianchejie.cn/Article/details/gtingusfrc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnxiangtu.top/Article/details/gtpibedtvt.html

[R21] 字符串长度
来源：http://dali.9152youxi.cn/Article/details/gtooodpfsk.html

echo "${#s}"
来源：http://dali.jqgfzy.top/Article/details/gtdshqhhov.html

[R22] 截取子串
来源：http://dali.wangdashe.top/Article/details/gtbtsyjcnt.html

echo "${s:0:5}"
来源：http://dali.cdnleiting.top/Article/details/gthacaqfyu.html

[R23] 字符串替换
来源：http://dali.zhoulong.xyz/Article/details/gtfaekbqhy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hfpthk.cn/Article/details/gtnufqfsvw.html

[R24] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gtgibmkxwl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cheryme.top/Article/details/gtsgzophsz.html

[R25] 去后缀 / 去前缀
来源：http://dali.kuanghao11.cn/Article/details/gtcmowebed.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aibaodan.cn/Article/details/gtslmbazbf.html

[R26] 命令替换
来源：http://dali.yongpay.top/Article/details/gtwydjrkqx.html

now=$(date +%F); echo "$now"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoefhexyj.html

[R27] 算术展开
来源：http://dali.jiagoushi.top/Article/details/gtkvbdefsz.html

echo $((1 + 2 * 3))
来源：http://dali.daxiang520.top/Article/details/gtgkdqpkqe.html

[R28] 浮点运算
来源：http://dali.hnxiangtu.top/Article/details/gtfugkctnh.html

echo "scale=2; 10/3" | bc
来源：http://dali.hfpthk.cn/Article/details/gtqeyvheqh.html

[R29] 定义函数
来源：http://dali.aibaodan.cn/Article/details/gtvuawjmth.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zycfv.cn/Article/details/gtfzzpninw.html

[R30] 函数返回状态码
来源：http://dali.yj202588.top/Article/details/gtywnmphmb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.andypj.xyz/Article/details/gtcywlvgob.html

[R31] 局部变量
来源：http://dali.gotoacloud.top/Article/details/gtxqqgfqaa.html

f() { local x=1; echo "$x"; }
来源：http://dali.tian-w.cn/Article/details/gtuqeyktlz.html

[R32] 参数个数校验
来源：http://dali.sufxvd.cn/Article/details/gttjhdpxch.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.316326.xyz/Article/details/gthvqyjydx.html

[R33] 捕获错误并提示行号
来源：http://dali.hnxiangtu.top/Article/details/gthkfcgtns.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yanxiufei.cn/Article/details/gtkomajetn.html

[R34] 退出时清理
来源：http://dali.ehwqpu.com/Article/details/gtvyirmjfv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuanzx.com/Article/details/gtbafqtrni.html

[R35] 后台执行并等待
来源：http://dali.havefunace.top/Article/details/gtnsiaoqhm.html


<!-- 参考信息 -->