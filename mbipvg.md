代发 wailian999

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhengqikj.top/Article/details/gtfqylxjbt.html

C#:   if (x is null) {}
来源：http://dali.zhongyouzk.top/Article/details/gtarfhzwcc.html

[P07] 防抖与节流
来源：http://dali.feifeiyinyue.top/Article/details/gthdksepkn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nwbrower.top/Article/details/gtyepcgfuw.html

PHP:  // 手写时间戳比较
来源：http://dali.yueranfly.top/Article/details/gtipweueaq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gtdvxcgwpy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gtphsjixwq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.guannengcc.top/Article/details/gtluiyzfwi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zdqjudy.top/Article/details/gtlhsuncgx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hysaishi.cn/Article/details/gthwsmpeif.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cashguo.top/Article/details/gtzidncbbq.html

[P08] 处理浮点精度问题
来源：http://dali.nanxinkj.top/Article/details/gtffsipzwj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hnxiangtu.top/Article/details/gtufmmhuzu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.iojbl.cn/Article/details/gtnffxokmx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.aibaodan.cn/Article/details/gtoreabync.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cucudq.cn/Article/details/gtaninofxo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.redwolf501.top/Article/details/gtpxyppvdu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ppjwa.cn/Article/details/gtrazesptp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xinyue.icu/Article/details/gtkqzstvvc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.mhx1999.top/Article/details/gtdctfjhev.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gthittvyeh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigufen.top/Article/details/gtekudutog.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gttepritpk.html

[Q01] 创建表
来源：http://dali.9152youxi.cn/Article/details/gtyxyahwig.html

CREATE TABLE users (
来源：http://dali.shangyingyoupin.top/Article/details/gtxfiawerr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.c1oappe.top/Article/details/gtdavbedns.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gtijfkbqbw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xuetiantiany.cn/Article/details/gtaamfgkef.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ydzc1.top/Article/details/gtakprqgwu.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gtkzewdhde.html

[Q02] 创建带外键的表
来源：http://dali.jiagoushi.top/Article/details/gtbccoidcj.html

CREATE TABLE orders (
来源：http://dali.zhiwuduotai.top/Article/details/gtycsqpmlv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gtdxrxgpwu.html

user_id INT NOT NULL,
来源：http://dali.zhongyouzk.top/Article/details/gtrjmxpkmb.html

amount DECIMAL(10, 2),
来源：http://dali.xylfe.cn/Article/details/gtflvcjyod.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.birdmap.top/Article/details/gtrftykrov.html

);
来源：http://dali.hfpthk.cn/Article/details/gtcahrlppb.html

[Q03] 增加列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtozlusxuz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zdqjudy.top/Article/details/gtnimfdtfe.html

[Q04] 修改列类型
来源：http://dali.redwolf501.top/Article/details/gtudxknuaa.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbaovzbp.html

[Q05] 重命名列
来源：http://dali.pengpengdd.cyou/Article/details/gtxtvdohkp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zdqjudy.top/Article/details/gteuggmhla.html

[Q06] 删除列
来源：http://dali.chenjidiqi.icu/Article/details/gtgtsbnyev.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jqgfzy.top/Article/details/gtwkwgnzbs.html

[Q07] 删除表
来源：http://dali.shzxlz.cn/Article/details/gtwwgrynva.html

DROP TABLE IF EXISTS orders;
来源：http://dali.redwolf501.top/Article/details/gtzkpqlppk.html

[Q08] 创建普通索引
来源：http://dali.quarkkingdee.top/Article/details/gtknlfuzat.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yvedp.cn/Article/details/gtwbckhpao.html

[Q09] 创建唯一索引
来源：http://dali.ydzc1.top/Article/details/gtqdixhxhu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gtanktulxt.html

[Q10] 插入单行
来源：http://dali.yj202588.top/Article/details/gtkuefllim.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhongyouzk.top/Article/details/gtlfpvmsvy.html

[Q11] 一次插入多行
来源：http://dali.zdqjudy.top/Article/details/gtkjerixpt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangdashe.top/Article/details/gtbhrysmcj.html

[Q12] 插入后取自增 ID
来源：http://dali.gzhubu.top/Article/details/gtldqbfsiz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yj202588.top/Article/details/gtyytlpqaf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.smart0.xyz/Article/details/gtbdfernmm.html

[Q13] 忽略重复插入
来源：http://dali.haohaochexian.top/Article/details/gtmgbufpcw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.9152youxi.cn/Article/details/gtzpovypgl.html

[Q14] 存在则更新（upsert）
来源：http://dali.guowangkeji.top/Article/details/gtwompfomm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.316326.xyz/Article/details/gttgfwhsbo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.daxiang520.top/Article/details/gtcbrmxhau.html

[Q15] 查询全部
来源：http://dali.guowangkeji.top/Article/details/gttxhconii.html

SELECT * FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtgzmxsbvf.html

[Q16] 查询指定列
来源：http://dali.cucudq.cn/Article/details/gtdjkfajsx.html

SELECT id, name FROM users;
来源：http://dali.birdmap.top/Article/details/gtfkeibftp.html

[Q17] 条件查询
来源：http://dali.jinqigufen.top/Article/details/gtspmydvnp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.wangdashe.top/Article/details/gtzcegcjqx.html

[Q18] 模糊匹配
来源：http://dali.cqqwz.cn/Article/details/gtyxdddxjn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhiwuduotai.top/Article/details/gtztrlbkhs.html

[Q19] 范围查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbipidjqa.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xinyue.icu/Article/details/gtcdeqspau.html

[Q20] IN 列表
来源：http://dali.dianchejie.cn/Article/details/gtwobhsvhg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj20258.top/Article/details/gtncxdyply.html

[Q21] 空值判断
来源：http://dali.jqgufenzy.top/Article/details/gtmmidptaf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yuxming.cn/Article/details/gtxcdjbfet.html

[Q22] 排序
来源：http://dali.tanke756.top/Article/details/gtyydwmsmw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.birdmap.top/Article/details/gthoyyfqtg.html

[Q23] 分页
来源：http://dali.jinyuanbaomall.cn/Article/details/gthuyzvqrf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nwbrower.top/Article/details/gtngdznylf.html

[Q24] 去重
来源：http://dali.jyoumei.cn/Article/details/gtmrbvvhse.html

SELECT DISTINCT city FROM users;
来源：http://dali.c1oappe.top/Article/details/gtnseejunu.html

[Q25] 只取前 N 条
来源：http://dali.316326.xyz/Article/details/gtfiyjbdcs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ehwqpu.com/Article/details/gtwbiecpfm.html

[Q26] 计数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaepvqqwj.html

SELECT COUNT(*) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtsniytmdd.html

[Q27] 条件计数
来源：http://dali.nanxuanxn.top/Article/details/gtyuzxfuob.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jianghu66.top/Article/details/gtnjgbylcf.html

[Q28] 求和与平均
来源：http://dali.c1oappe.top/Article/details/gtbyevknsh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.pycfn.com/Article/details/gtdoxgvwnb.html

[Q29] 最大最小值
来源：http://dali.ybcxt.top/Article/details/gtcabkoplm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtvxagxbwr.html

[Q30] 分组统计
来源：http://dali.yj202588.top/Article/details/gtfanfrxdv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gtgssueido.html

[Q31] 分组后过滤
来源：http://dali.jinqigfzy.top/Article/details/gtptqrgbov.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgufenzy.top/Article/details/gtlwmwcvjw.html

[Q32] 分组拼接字符串
来源：http://dali.bjfxy.top/Article/details/gtnewvizqi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gtqofjaonj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangshuangyany.cn/Article/details/gtsoxgfjvs.html

[Q33] 多列分组
来源：http://dali.yanxiufei.cn/Article/details/gtkpmjuygq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zycfv.cn/Article/details/gtirmpyabv.html

[Q34] 每组取第一条
来源：http://dali.jqgfzy.top/Article/details/gthakkdycc.html

SELECT * FROM (
来源：http://dali.smart0.xyz/Article/details/gthvpejcbd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shuidangran.top/Article/details/gtsgjxlvcp.html

) t WHERE rn = 1;
来源：http://dali.cqqwz.cn/Article/details/gtpcflhcvl.html

[Q35] 内连接
来源：http://dali.aibaodan.cn/Article/details/gtmxjfffsm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.haohaochexian.top/Article/details/gtqwwjwxqh.html

[Q36] 左连接
来源：http://dali.zhengqikj.top/Article/details/gtqoqqwnvd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.haohaochexian.top/Article/details/gthqbqpdqh.html

[Q37] 右连接
来源：http://dali.tianlin.xyz/Article/details/gtsyreexqf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shuidangran.top/Article/details/gtxtfvxfvb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sxryk.cn/Article/details/gtmloyrbeb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xuanzx.com/Article/details/gtzlzjxrey.html

[Q39] 自连接（查上下级）
来源：http://dali.kuanghao11.cn/Article/details/gtnkvxdeti.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenlongwang.top/Article/details/gtxudgqjmc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwdmwocp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.aizwys.cn/Article/details/gtemqzaltl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ppjwa.cn/Article/details/gtpzlcibxm.html

[Q41] 多表连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhvkrshp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cashguo.top/Article/details/gtutwgeohv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fzhhl.top/Article/details/gtbyekxnvo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yangfankeji.com/Article/details/gtvgkakmao.html

[Q42] 连接条件附加过滤
来源：http://dali.cucudq.cn/Article/details/gtkxmydkjn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tianlin.xyz/Article/details/gtxkqjmqhn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tanke756.top/Article/details/gtczvhrnlz.html

[Q43] 标量子查询
来源：http://dali.tian-w.cn/Article/details/gthvlturvd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.snrcjt.cn/Article/details/gtqtvsycvv.html

[Q44] IN 子查询
来源：http://dali.zhongyouzk.top/Article/details/gtygalypiz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigfzy.top/Article/details/gtdnecwhhj.html

[Q45] EXISTS 判断存在
来源：http://dali.aizwys.cn/Article/details/gtbyivrzvw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gtzoxlpfnk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrkihyle.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jiagoushi.top/Article/details/gtsolixnkn.html

[Q47] 与平均值比较
来源：http://dali.yueranfly.top/Article/details/gtqdthjpuo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.mhx1999.top/Article/details/gtkszgvbtu.html

[Q48] CTE 公用表表达式
来源：http://dali.jiagoushi.top/Article/details/gtneooolmr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gaohongyu789.top/Article/details/gtyotbdmfd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.mhx1999.top/Article/details/gtsvlgwjey.html

[Q49] 更新单行
来源：http://dali.chenzaomai.com/Article/details/gtrzhdeqdm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gaohongyu789.top/Article/details/gtzyymsiej.html

[Q50] 批量更新
来源：http://dali.hnqzz.top/Article/details/gtadqcwgxo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yangfankeji.com/Article/details/gtbidsjuqd.html

[Q51] 用子查询更新
来源：http://dali.quarkkingdee.top/Article/details/gtatdpwlhs.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxqttwlv.html

[Q52] 删除指定行
来源：http://dali.snrcjt.cn/Article/details/gttxxffhcx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gtfelijboa.html

[Q53] 按条件删除
来源：http://dali.aizwys.cn/Article/details/gtsnprnbft.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gtuyiyqitu.html

[Q54] 清空表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtvkubvg.html

TRUNCATE TABLE logs;
来源：http://dali.cqqwz.cn/Article/details/gtljkmukiu.html

[Q55] 排名（并列占位）
来源：http://dali.jinqigufen.top/Article/details/gtelgmfkdb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.kuanghao11.cn/Article/details/gtoiuueuic.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gzhubu.top/Article/details/gtjpiswbcv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yonumen.top/Article/details/gtvglkyefn.html

[Q57] 行号
来源：http://dali.fzhhl.top/Article/details/gtiwivcklc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtltrcogiy.html

[Q58] 累计求和
来源：http://dali.ppjwa.cn/Article/details/gtvjyxccai.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.havefunace.top/Article/details/gtnrutszkl.html

[Q59] 分组内累计
来源：http://dali.ybcxt.top/Article/details/gtlwesmnvb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtxourozqz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhaomingkeji.xyz/Article/details/gteogmftgq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.svipenyu.cn/Article/details/gtbfgnaiyd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehyqltpx.html

[Q61] 移动平均
来源：http://dali.hfpthk.cn/Article/details/gtjnkpsqqy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtbekcpydh.html

[Q62] 分组占比
来源：http://dali.redwolf501.top/Article/details/gtufbggexr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gtjbpajvlq.html

[Q63] 开启事务
来源：http://dali.aizwys.cn/Article/details/gtpvamhwke.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgfzy.top/Article/details/gtpywyxuvp.html

[Q64] 提交事务
来源：http://dali.havefunace.top/Article/details/gtpkblexvx.html

COMMIT;
来源：http://dali.0kj1m.cn/Article/details/gtywmynxch.html

[Q65] 回滚事务
来源：http://dali.jqgufenzy.top/Article/details/gtrbbmvohq.html

ROLLBACK;
来源：http://dali.zhixingplan.top/Article/details/gtydgflllv.html

[Q66] 行锁查询
来源：http://dali.yueranfly.top/Article/details/gtjmerjlsk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hammf.cn/Article/details/gtlygmnicf.html

[Q67] 设置隔离级别
来源：http://dali.redwolf501.top/Article/details/gthwqvdmix.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aibaodan.cn/Article/details/gtuctqnocv.html

[Q68] 保存点
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrucybcg.html

SAVEPOINT sp1;
来源：http://dali.sweek.top/Article/details/gtpwqvzsiq.html

ROLLBACK TO sp1;
来源：http://dali.cashguo.top/Article/details/gtzpxarflj.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gtgbbszhbo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yangfankeji.com/Article/details/gtqhbknjzl.html

[Q70] 更新统计信息
来源：http://dali.chenzaomai.com/Article/details/gtnctbawcj.html

ANALYZE TABLE users;
来源：http://dali.c1oappe.top/Article/details/gtxsslnluo.html

[Q71] 查看建表语句
来源：http://dali.pengpengdd.cyou/Article/details/gtrrknwzlh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.iojbl.cn/Article/details/gthaldrcud.html

[Q72] 查看索引
来源：http://dali.yvedp.cn/Article/details/gtftxqfxfu.html

SHOW INDEX FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtdaqgrgli.html

[Q73] 查看表状态
来源：http://dali.yj202588.top/Article/details/gtvkrdlwib.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ydzc1.top/Article/details/gthbaknhnp.html

[Q74] 强制使用索引
来源：http://dali.zycfv.cn/Article/details/gtotntnfec.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.fengsongda.top/Article/details/gtdnhdfzht.html

[Q75] 日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gtmlhosfnn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtjbyjirgr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gzhubu.top/Article/details/gtuhsyjdag.html

[Q76] 按天统计
来源：http://dali.jinqigfzy.top/Article/details/gtdoobdvwe.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhoulong.xyz/Article/details/gtxiuvgrsy.html

[Q77] 时间加减
来源：http://dali.tianlin.xyz/Article/details/gtvtqmtmiq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenlongwang.top/Article/details/gtcnyujvre.html

[Q78] 当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gtikpkavnn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258888.top/Article/details/gttzfecmfk.html

[Q79] 字符串拼接
来源：http://dali.ydzc1.top/Article/details/gtwxznrrod.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gzhubu.top/Article/details/gtbtgtcike.html

[Q80] 字符串截取
来源：http://dali.sxryk.cn/Article/details/gtcrscvppu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtgmbrxeqm.html

[Q81] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gtbkassxyy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtmaqbhpvg.html

[Q82] 字符长度与字节长度
来源：http://dali.kuanghao11.cn/Article/details/gtzanlcwjy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtxilhvank.html

[Q83] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gtatsyqllj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtfrhisozt.html

[Q84] 去除首尾空格
来源：http://dali.fengsongda.top/Article/details/gtqdarouus.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtpdnnthvm.html

[Q85] 数值取整
来源：http://dali.daria6918.cn/Article/details/gtccewfaks.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zdqjudy.top/Article/details/gtybzzlonf.html

[Q86] 读取 JSON 字段
来源：http://dali.yj202588.top/Article/details/gtrzzkctpx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.birdmap.top/Article/details/gtgpcecrbx.html

[Q87] JSON 字段做条件
来源：http://dali.quarkkingdee.top/Article/details/gttkkpdphu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.svipenyu.cn/Article/details/gtqnfoljvv.html

[Q88] 行转列（条件聚合）
来源：http://dali.pengpengdd.cyou/Article/details/gtdgnaqsbz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gzhubu.top/Article/details/gtajiztocf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.birdmap.top/Article/details/gtzdaucbim.html

[Q89] 判断表是否存在
来源：http://dali.316326.xyz/Article/details/gtgkbwixii.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.quarkkingdee.top/Article/details/gtyqobnjrw.html

[Q90] 生成序号列
来源：http://dali.pengpengdd.cyou/Article/details/gtvnmnzeco.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cqqwz.cn/Article/details/gttlokwfta.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjkipjjb.html

R. Bash 专题
来源：http://dali.chenjidiqi.icu/Article/details/gthfullwgy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtbeczwljj.html

[R01] shebang 与严格模式
来源：http://dali.tanke756.top/Article/details/gtxcaykfeo.html

#!/usr/bin/env bash
来源：http://dali.zdqjudy.top/Article/details/gtudwrcvgy.html

set -euo pipefail
来源：http://dali.yongpay.top/Article/details/gtbmziczkb.html

[R02] 变量赋值与使用
来源：http://dali.jinqigufen.top/Article/details/gthzmgbtqb.html

name="Tom"; echo "$name"
来源：http://dali.jiagoushi.top/Article/details/gtdyraumcu.html

[R03] 只读变量
来源：http://dali.yvedp.cn/Article/details/gtiayqcvld.html

readonly PI=3.14
来源：http://dali.yangfankeji.com/Article/details/gtnddtnhiw.html

[R04] 位置参数
来源：http://dali.smart0.xyz/Article/details/gtynvullwj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gtvuaxgeho.html

[R05] 参数默认值
来源：http://dali.yj202588.top/Article/details/gtyynuevnt.html

name="${1:-default}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtypvnfmfg.html

[R06] 判断命令是否存在
来源：http://dali.zhongyouzk.top/Article/details/gtpgbzvzun.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenzaomai.com/Article/details/gttftfrgky.html

[R07] if 判断文件
来源：http://dali.xziqi.cn/Article/details/gtcuoxgkbo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xylfe.cn/Article/details/gtkugyxqfe.html

[R08] 数值比较
来源：http://dali.yj202588.top/Article/details/gthcrwlhev.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnqzz.top/Article/details/gtbbbfgoaw.html

[R09] 字符串比较
来源：http://dali.redwolf501.top/Article/details/gtozzchfmm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yonumen.top/Article/details/gtbxglnrfd.html

[R10] 正则匹配
来源：http://dali.gaohongyu789.top/Article/details/gtmpflrjoa.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jyoumei.cn/Article/details/gtluoweuev.html

[R11] case 多分支
来源：http://dali.sxryk.cn/Article/details/gthoegjpbg.html

case "$1" in
来源：http://dali.jianghu66.top/Article/details/gtqqxqycab.html

start) echo "启动" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gtnmtbcouk.html

stop)  echo "停止" ;;
来源：http://dali.yvedp.cn/Article/details/gtzkwtmrpk.html

*)     echo "未知命令" ;;
来源：http://dali.iojbl.cn/Article/details/gtbtyvutzl.html

esac
来源：http://dali.wangshuangyany.cn/Article/details/gtcvtidlzd.html

[R12] for 遍历文件
来源：http://dali.kuanghao11.cn/Article/details/gtvytwtfsm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zdqjudy.top/Article/details/gtjlefbhnf.html

[R13] for 计数循环
来源：http://dali.guannengcc.top/Article/details/gtfcelfpjy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gtgmtuzdmq.html

[R14] C 风格 for
来源：http://dali.tianlin.xyz/Article/details/gtyjepulcc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitcvyadw.html

[R15] while 逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtjaezmtjv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.dianchejie.cn/Article/details/gtovyhjaya.html

[R16] until 等待条件
来源：http://dali.yvedp.cn/Article/details/gthfyfqiff.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ybcxt.top/Article/details/gtertrlwzr.html

[R17] 数组定义与取值
来源：http://dali.chenzaomai.com/Article/details/gtbltgtfby.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cashguo.top/Article/details/gtdevkzydk.html

[R18] 遍历数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtezzksntz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cheryme.top/Article/details/gtmfpjpnqm.html

[R19] 数组长度
来源：http://dali.feifeiyinyue.top/Article/details/gtfleahorg.html

echo "${#arr[@]}"
来源：http://dali.jlsjyb.cn/Article/details/gtpryldkqo.html

[R20] 关联数组（字典）
来源：http://dali.tian-w.cn/Article/details/gtfzvpgdnz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cucudq.cn/Article/details/gtzdfnhbsj.html

[R21] 字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gtamnxybvb.html

echo "${#s}"
来源：http://dali.yj20258.top/Article/details/gtrwkkjikh.html

[R22] 截取子串
来源：http://dali.vqdsnc.cn/Article/details/gtzgvgblsq.html

echo "${s:0:5}"
来源：http://dali.meibo888.top/Article/details/gtkrgawvsy.html

[R23] 字符串替换
来源：http://dali.daxiang520.top/Article/details/gtsccenrpa.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gaohongyu789.top/Article/details/gtrmpgzwjs.html

[R24] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gtwfdosohf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fzhhl.top/Article/details/gtezxyxerq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaicugjsb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknbvykso.html

[R26] 命令替换
来源：http://dali.yangfankeji.com/Article/details/gtruvhvivk.html

now=$(date +%F); echo "$now"
来源：http://dali.sysykeji.top/Article/details/gtakysfkrl.html

[R27] 算术展开
来源：http://dali.iojbl.cn/Article/details/gtwujdysxb.html

echo $((1 + 2 * 3))
来源：http://dali.gzhubu.top/Article/details/gtptwrshty.html

[R28] 浮点运算
来源：http://dali.bjfxy.top/Article/details/gtbrzqalff.html

echo "scale=2; 10/3" | bc
来源：http://dali.haohaochexian.top/Article/details/gtribluvax.html

[R29] 定义函数
来源：http://dali.pycfn.com/Article/details/gttcrznucq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovamhfxv.html

[R30] 函数返回状态码
来源：http://dali.iojbl.cn/Article/details/gtdvnxchqt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cucudq.cn/Article/details/gtcygbojbn.html

[R31] 局部变量
来源：http://dali.redwolf501.top/Article/details/gthpqhabrg.html

f() { local x=1; echo "$x"; }
来源：http://dali.jiagoushi.top/Article/details/gtatxyrhyi.html

[R32] 参数个数校验
来源：http://dali.jinqigfzy.top/Article/details/gtrqwffjht.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gtpsushymw.html

[R33] 捕获错误并提示行号
来源：http://dali.hammf.cn/Article/details/gtmdbpxnxl.html


<!-- 参考信息 -->