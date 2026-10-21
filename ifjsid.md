代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.daria6918.cn/Article/details/gterjwrliv.html

TS:   if (x == null) {}
来源：http://dali.redwolf501.top/Article/details/gtqfwaqwwv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gtpsxuwhlo.html

Go:   if x == nil {}
来源：http://dali.yvedp.cn/Article/details/gtuaxsrvaw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.dashuyun.cn/Article/details/gtftqidypb.html

C#:   if (x is null) {}
来源：http://dali.meibo888.top/Article/details/gtidqbeusu.html

[P07] 防抖与节流
来源：http://dali.daria6918.cn/Article/details/gtwfzoozov.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shuidangran.top/Article/details/gtiobtxwjg.html

PHP:  // 手写时间戳比较
来源：http://dali.mhx1999.top/Article/details/gtrtqvuxjy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gtiodrzcmw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gthfqypyqm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.andypj.xyz/Article/details/gtogsbryba.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yanxiufei.cn/Article/details/gtwdirfcbx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.bjfxy.top/Article/details/gtvtobrfuc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daxiang520.top/Article/details/gtulsmofsx.html

[P08] 处理浮点精度问题
来源：http://dali.jinghuilouyu.cn/Article/details/gtutbtqftk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.andypj.xyz/Article/details/gtkvpocidd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.aibaodan.cn/Article/details/gtstvvxaul.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jqgufenzy.top/Article/details/gtouquoovk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yvedp.cn/Article/details/gtvglpsddg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hywenlv.cn/Article/details/gtewvutjtl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.pycfn.com/Article/details/gttqdeutsk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.0kj1m.cn/Article/details/gtjygpxjjv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xuetiantiany.cn/Article/details/gtvxqthhbw.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtyjhsumsy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jyoumei.cn/Article/details/gtmzeappbi.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjsdixwkr.html

[Q01] 创建表
来源：http://dali.wangshuangyany.cn/Article/details/gtbfnkgpwp.html

CREATE TABLE users (
来源：http://dali.zycfv.cn/Article/details/gtcuxvlfdr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuetiantiany.cn/Article/details/gtpvpfdgmv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenjidiqi.icu/Article/details/gtueubyjhc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgyxhila.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shangyingyoupin.top/Article/details/gtooaaletl.html

);
来源：http://dali.jqgufenzy.top/Article/details/gtbmrcomca.html

[Q02] 创建带外键的表
来源：http://dali.yonumen.top/Article/details/gttoimfeag.html

CREATE TABLE orders (
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhrwbhel.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guannengcc.top/Article/details/gtocixdprp.html

user_id INT NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gtiwkjazdw.html

amount DECIMAL(10, 2),
来源：http://dali.dashuyun.cn/Article/details/gtzivccxux.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangtech.top/Article/details/gtukxnmvhu.html

);
来源：http://dali.shangyingyoupin.top/Article/details/gtftvnyeje.html

[Q03] 增加列
来源：http://dali.xuanzx.com/Article/details/gtyfpmuaam.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ehwqpu.com/Article/details/gtckhuoijk.html

[Q04] 修改列类型
来源：http://dali.yj202588.top/Article/details/gtlyhfouub.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.svipenyu.cn/Article/details/gtclwrfwba.html

[Q05] 重命名列
来源：http://dali.jinghuilouyu.cn/Article/details/gtomhfqydm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jlsjyb.cn/Article/details/gtiuijedic.html

[Q06] 删除列
来源：http://dali.iojbl.cn/Article/details/gtusedaijs.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ppjwa.cn/Article/details/gtrgnsakfq.html

[Q07] 删除表
来源：http://dali.dashuyun.cn/Article/details/gtluqqwrpt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hfpthk.cn/Article/details/gtpbhidnph.html

[Q08] 创建普通索引
来源：http://dali.cucudq.cn/Article/details/gtnysbjomp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aizwys.cn/Article/details/gtbeekmuxd.html

[Q09] 创建唯一索引
来源：http://dali.zhoulong.xyz/Article/details/gtosttqutp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.316326.xyz/Article/details/gttsgxubfp.html

[Q10] 插入单行
来源：http://dali.jqgufenzy.top/Article/details/gtnhqnlkgu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gtpyudexdt.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuyhyatan.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dianchejie.cn/Article/details/gtpirgmpre.html

[Q12] 插入后取自增 ID
来源：http://dali.tanke756.top/Article/details/gtdukiukcc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhoulong.xyz/Article/details/gtaalquqgb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuanzhike.top/Article/details/gtjxxecstx.html

[Q13] 忽略重复插入
来源：http://dali.jianghu66.top/Article/details/gtlnbzrfdu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xinyue.icu/Article/details/gtwaeeqvtu.html

[Q14] 存在则更新（upsert）
来源：http://dali.sufxvd.cn/Article/details/gtzuzvtjsg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xuetiantiany.cn/Article/details/gteuvhcszi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuanzhike.top/Article/details/gtgtdqaxxo.html

[Q15] 查询全部
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpqvqswd.html

SELECT * FROM users;
来源：http://dali.ivvv.top/Article/details/gtwsqaxvyb.html

[Q16] 查询指定列
来源：http://dali.9152youxi.cn/Article/details/gtbgxigtlx.html

SELECT id, name FROM users;
来源：http://dali.sxryk.cn/Article/details/gtffrdplbw.html

[Q17] 条件查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvssujlgq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.wangdashe.top/Article/details/gtthlkojlf.html

[Q18] 模糊匹配
来源：http://dali.nanxinkj.top/Article/details/gtdyrtmvee.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jianghu66.top/Article/details/gttqitybxi.html

[Q19] 范围查询
来源：http://dali.9152youxi.cn/Article/details/gtokgabtow.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guowangkeji.top/Article/details/gtiaxdgiij.html

[Q20] IN 列表
来源：http://dali.yueranfly.top/Article/details/gthavinavr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cashguo.top/Article/details/gtkccmvfgr.html

[Q21] 空值判断
来源：http://dali.zhiwuduotai.top/Article/details/gtxiphmvby.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnxiangtu.top/Article/details/gtdkvdrgay.html

[Q22] 排序
来源：http://dali.guannengcc.top/Article/details/gtexycnnks.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hammf.cn/Article/details/gtsxmglknl.html

[Q23] 分页
来源：http://dali.wangdashe.top/Article/details/gtupwnhkjs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.andypj.xyz/Article/details/gtulrkozkm.html

[Q24] 去重
来源：http://dali.cdnleiting.top/Article/details/gtfxcxoknx.html

SELECT DISTINCT city FROM users;
来源：http://dali.tianlin.xyz/Article/details/gthaauxozr.html

[Q25] 只取前 N 条
来源：http://dali.ehwqpu.com/Article/details/gtqbkyprki.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.kuanghao11.cn/Article/details/gtvbtcscnp.html

[Q26] 计数
来源：http://dali.sysykeji.top/Article/details/gtiwnrhjlm.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtjrbtrqbv.html

[Q27] 条件计数
来源：http://dali.ydzc1.top/Article/details/gtheibcpxj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtzwozzrso.html

[Q28] 求和与平均
来源：http://dali.chenjidiqi.icu/Article/details/gtnbyvktlg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtbnkcuvyf.html

[Q29] 最大最小值
来源：http://dali.ehwqpu.com/Article/details/gterdgqlmv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tanke756.top/Article/details/gtukwmivqa.html

[Q30] 分组统计
来源：http://dali.haohaochexian.top/Article/details/gtotygfrjy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gthhzzqjmo.html

[Q31] 分组后过滤
来源：http://dali.sweek.top/Article/details/gtwckdjtsd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.dashuyun.cn/Article/details/gtxldbffuo.html

[Q32] 分组拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtzfzetvgf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gtvtgczkjn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhixingplan.top/Article/details/gttieobich.html

[Q33] 多列分组
来源：http://dali.yvedp.cn/Article/details/gtgqakxxjw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhongyouzk.top/Article/details/gtdtcogyhu.html

[Q34] 每组取第一条
来源：http://dali.smart0.xyz/Article/details/gtmrchhgdz.html

SELECT * FROM (
来源：http://dali.cqqwz.cn/Article/details/gtxhehlkpz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.vqdsnc.cn/Article/details/gtcmkcbprs.html

) t WHERE rn = 1;
来源：http://dali.sysykeji.top/Article/details/gthffftbtw.html

[Q35] 内连接
来源：http://dali.wangshuangyany.cn/Article/details/gtwhqpysfl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.9152youxi.cn/Article/details/gtqahkbbzb.html

[Q36] 左连接
来源：http://dali.sysykeji.top/Article/details/gtjyewaldm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.9152youxi.cn/Article/details/gtnubyytwk.html

[Q37] 右连接
来源：http://dali.zhiwuduotai.top/Article/details/gtqtpbzmjb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.aizwys.cn/Article/details/gtjdsytqsc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinqigufen.top/Article/details/gtvuamydji.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.0kj1m.cn/Article/details/gtqjlipltj.html

[Q39] 自连接（查上下级）
来源：http://dali.chenlongwang.top/Article/details/gtukphflkr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinqigufen.top/Article/details/gtbsnupxor.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ybcxt.top/Article/details/gtoezbvxzd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.aibaodan.cn/Article/details/gtygqcyjlq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.feifeiyinyue.top/Article/details/gtwgnbcnkt.html

[Q41] 多表连接
来源：http://dali.sxryk.cn/Article/details/gthirjubzn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zdqjudy.top/Article/details/gtjmkveayu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yuanzhike.top/Article/details/gteeolpwgb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yangfankeji.com/Article/details/gtpocviiou.html

[Q42] 连接条件附加过滤
来源：http://dali.pycfn.com/Article/details/gtsmsatghi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sweek.top/Article/details/gtghfgwrot.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jiagoushi.top/Article/details/gtslbxqkez.html

[Q43] 标量子查询
来源：http://dali.yvedp.cn/Article/details/gtiotaaqxr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.smart0.xyz/Article/details/gtzfscrzuw.html

[Q44] IN 子查询
来源：http://dali.yj20258888.top/Article/details/gtzwlwleek.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xinyue.icu/Article/details/gtxgstbvjc.html

[Q45] EXISTS 判断存在
来源：http://dali.dashuyun.cn/Article/details/gtbqujcnnj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gtvmeuwpwi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gzhubu.top/Article/details/gtelbwkuux.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jlsjyb.cn/Article/details/gtbmtofwer.html

[Q47] 与平均值比较
来源：http://dali.kuanghao11.cn/Article/details/gthnkvtlcf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ybcxt.top/Article/details/gtqhknnstk.html

[Q48] CTE 公用表表达式
来源：http://dali.xziqi.cn/Article/details/gtiijhriai.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hnqzz.top/Article/details/gtgtcfoqdl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.smart0.xyz/Article/details/gtmtpkanrt.html

[Q49] 更新单行
来源：http://dali.daxiang520.top/Article/details/gtpnjdgbnv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.316326.xyz/Article/details/gteiwxvnoc.html

[Q50] 批量更新
来源：http://dali.cdnleiting.top/Article/details/gtzwnbizug.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.fengsongda.top/Article/details/gtdasunlrj.html

[Q51] 用子查询更新
来源：http://dali.xuetiantiany.cn/Article/details/gtzvvxemru.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jianghu66.top/Article/details/gtwoxthyia.html

[Q52] 删除指定行
来源：http://dali.tanke756.top/Article/details/gtzlrdjsim.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gotoacloud.top/Article/details/gtmvcufqpf.html

[Q53] 按条件删除
来源：http://dali.hammf.cn/Article/details/gtwjvzcptt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jqgfzy.top/Article/details/gtereyqxlg.html

[Q54] 清空表
来源：http://dali.aibaodan.cn/Article/details/gthcfqdlyx.html

TRUNCATE TABLE logs;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwobbazz.html

[Q55] 排名（并列占位）
来源：http://dali.zhongyouzk.top/Article/details/gtppjbnytk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinqigfzy.top/Article/details/gttgxrgedi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tanke756.top/Article/details/gtoouxdxpc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gtifgctznc.html

[Q57] 行号
来源：http://dali.andypj.xyz/Article/details/gtktekkcgt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtezylerls.html

[Q58] 累计求和
来源：http://dali.yuxming.cn/Article/details/gtmcdjdglo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtnuafyxzh.html

[Q59] 分组内累计
来源：http://dali.wangshuangyany.cn/Article/details/gtuoujqxai.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtawrqkfqb.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuanzx.com/Article/details/gtnosrsmmf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yangfankeji.com/Article/details/gtbqcxlsac.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtjjrzxybe.html

[Q61] 移动平均
来源：http://dali.haohaochexian.top/Article/details/gtoynhyjuy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtqpsjchhn.html

[Q62] 分组占比
来源：http://dali.guannengcc.top/Article/details/gtostfuqfz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gtjzewgcfz.html

[Q63] 开启事务
来源：http://dali.yonumen.top/Article/details/gtmfbqwois.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.daxiang520.top/Article/details/gtqcuwfwjp.html

[Q64] 提交事务
来源：http://dali.bjfxy.top/Article/details/gtbkkjiysg.html

COMMIT;
来源：http://dali.shzxlz.cn/Article/details/gtzwrezvba.html

[Q65] 回滚事务
来源：http://dali.yj20258888.top/Article/details/gtzblyglhy.html

ROLLBACK;
来源：http://dali.xuanzx.com/Article/details/gtcikwspff.html

[Q66] 行锁查询
来源：http://dali.jyoumei.cn/Article/details/gtwnainddj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sxryk.cn/Article/details/gtfqosesjo.html

[Q67] 设置隔离级别
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowetshla.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gtkyvxsvcp.html

[Q68] 保存点
来源：http://dali.yueranfly.top/Article/details/gttrxcojkl.html

SAVEPOINT sp1;
来源：http://dali.9152youxi.cn/Article/details/gtakcisafe.html

ROLLBACK TO sp1;
来源：http://dali.xuanzx.com/Article/details/gtgvmkhzsr.html

[Q69] 查看执行计划
来源：http://dali.yonumen.top/Article/details/gtueqhydoe.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhiwuduotai.top/Article/details/gtzqvahdvx.html

[Q70] 更新统计信息
来源：http://dali.andypj.xyz/Article/details/gtlhetatyn.html

ANALYZE TABLE users;
来源：http://dali.yongpay.top/Article/details/gtrfgyarou.html

[Q71] 查看建表语句
来源：http://dali.pengpengdd.cyou/Article/details/gtytghjzbo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.316326.xyz/Article/details/gtfsrlvsxq.html

[Q72] 查看索引
来源：http://dali.zycfv.cn/Article/details/gtmtspednl.html

SHOW INDEX FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtmwivojec.html

[Q73] 查看表状态
来源：http://dali.iojbl.cn/Article/details/gtxqrhbutr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ivvv.top/Article/details/gtukrswiad.html

[Q74] 强制使用索引
来源：http://dali.guowangkeji.top/Article/details/gtflacwapb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zdqjudy.top/Article/details/gtwvvszkzj.html

[Q75] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gtoxvoxfrr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtjqhqgiam.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xinyue.icu/Article/details/gtkbkpeivf.html

[Q76] 按天统计
来源：http://dali.shangyingyoupin.top/Article/details/gthixqqmjf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yangfankeji.com/Article/details/gtvyihcjez.html

[Q77] 时间加减
来源：http://dali.guowangkeji.top/Article/details/gtaeyzccij.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.feifeiyinyue.top/Article/details/gtumhyfmqy.html

[Q78] 当前时间
来源：http://dali.daxiang520.top/Article/details/gtljzsddln.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhiwuduotai.top/Article/details/gtltnmdyex.html

[Q79] 字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gtemvrimdr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgfzy.top/Article/details/gtyjvgific.html

[Q80] 字符串截取
来源：http://dali.xuanzx.com/Article/details/gtprijhokr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cashguo.top/Article/details/gticbfxktt.html

[Q81] 字符串替换
来源：http://dali.havefunace.top/Article/details/gtznsdrnqc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hammf.cn/Article/details/gtwvfncqyg.html

[Q82] 字符长度与字节长度
来源：http://dali.xziqi.cn/Article/details/gtzmgsugxi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtrxqejyzt.html

[Q83] 大小写转换
来源：http://dali.hammf.cn/Article/details/gtmkagdamh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtzhqutkef.html

[Q84] 去除首尾空格
来源：http://dali.yj202588.top/Article/details/gtgbqndacr.html

SELECT TRIM(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gtahzxjljt.html

[Q85] 数值取整
来源：http://dali.gotoacloud.top/Article/details/gtrdnijyfj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenjidiqi.icu/Article/details/gtzzxspvzj.html

[Q86] 读取 JSON 字段
来源：http://dali.gotoacloud.top/Article/details/gthtthpbaw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenzaomai.com/Article/details/gtvwmhopxn.html

[Q87] JSON 字段做条件
来源：http://dali.hammf.cn/Article/details/gtbdctyeid.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jqgfzy.top/Article/details/gtfnppzpiw.html

[Q88] 行转列（条件聚合）
来源：http://dali.shzxlz.cn/Article/details/gtvatmvhyh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hysaishi.cn/Article/details/gtedtozrej.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sweek.top/Article/details/gtxigtzwut.html

[Q89] 判断表是否存在
来源：http://dali.daxiang520.top/Article/details/gtkskbuyjb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hywenlv.cn/Article/details/gtzyxmfghh.html

[Q90] 生成序号列
来源：http://dali.xuanzx.com/Article/details/gtcutcrlcv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.guowangkeji.top/Article/details/gtawavzplp.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtoxnimnxx.html

R. Bash 专题
来源：http://dali.wangdashe.top/Article/details/gtstulwrlo.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtpxaxirjl.html

[R01] shebang 与严格模式
来源：http://dali.hnqzz.top/Article/details/gtghqdvsjk.html

#!/usr/bin/env bash
来源：http://dali.bjfxy.top/Article/details/gtgwidclic.html

set -euo pipefail
来源：http://dali.andypj.xyz/Article/details/gttldtzmlj.html

[R02] 变量赋值与使用
来源：http://dali.yj20258.top/Article/details/gtwshazxmb.html

name="Tom"; echo "$name"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexhzgfnp.html

[R03] 只读变量
来源：http://dali.316326.xyz/Article/details/gthftalrfz.html

readonly PI=3.14
来源：http://dali.bjfxy.top/Article/details/gtcaauwkeh.html

[R04] 位置参数
来源：http://dali.zhongyouzk.top/Article/details/gtxblwzgan.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gotoacloud.top/Article/details/gtmgbnvjnw.html

[R05] 参数默认值
来源：http://dali.meibo888.top/Article/details/gttdtiktsy.html

name="${1:-default}"
来源：http://dali.nanxuanxn.top/Article/details/gtvlzjdolp.html

[R06] 判断命令是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtmljnwspz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtrcaaxosa.html

[R07] if 判断文件
来源：http://dali.quarkkingdee.top/Article/details/gtxzlurbuj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtqqiagmvo.html

[R08] 数值比较
来源：http://dali.pycfn.com/Article/details/gtrzsinpeb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.fengsongda.top/Article/details/gtxxsurmps.html

[R09] 字符串比较
来源：http://dali.hongshengwenyu.top/Article/details/gtkqlhpxrh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cheryme.top/Article/details/gtntginyua.html

[R10] 正则匹配
来源：http://dali.zhixingplan.top/Article/details/gtxwgodmpy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtmcatftto.html

[R11] case 多分支
来源：http://dali.shangyingyoupin.top/Article/details/gtjhqdhavz.html

case "$1" in
来源：http://dali.smart0.xyz/Article/details/gtpomimafs.html

start) echo "启动" ;;
来源：http://dali.c1oappe.top/Article/details/gtbavsvkpx.html

stop)  echo "停止" ;;
来源：http://dali.yj20258888.top/Article/details/gtzmbzkrii.html

*)     echo "未知命令" ;;
来源：http://dali.fengsongda.top/Article/details/gtafvtycwj.html

esac
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvacjpmt.html

[R12] for 遍历文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnulimmck.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtmukbtaer.html

[R13] for 计数循环
来源：http://dali.zhiwuduotai.top/Article/details/gtfudblogz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtcmgoavud.html

[R14] C 风格 for
来源：http://dali.gotoacloud.top/Article/details/gtnnkctldj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gotoacloud.top/Article/details/gtjdhmrwgh.html

[R15] while 逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtteatqwtr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nanxinkj.top/Article/details/gtvixegzzi.html

[R16] until 等待条件
来源：http://dali.ydzc1.top/Article/details/gtlyzpjomn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.smart0.xyz/Article/details/gttnrnicgz.html

[R17] 数组定义与取值
来源：http://dali.cqqwz.cn/Article/details/gtkfwcqitr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtbnpowbcm.html

[R18] 遍历数组
来源：http://dali.cucudq.cn/Article/details/gtadcqoqtg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yongpay.top/Article/details/gtytltbosn.html

[R19] 数组长度
来源：http://dali.sweek.top/Article/details/gtvmbolpiw.html

echo "${#arr[@]}"
来源：http://dali.chenzaomai.com/Article/details/gtiqmwixap.html

[R20] 关联数组（字典）
来源：http://dali.cheryme.top/Article/details/gtbwwlbwwg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.fengsongda.top/Article/details/gtslehomvz.html

[R21] 字符串长度
来源：http://dali.tianlin.xyz/Article/details/gtdyjsjxio.html

echo "${#s}"
来源：http://dali.fengsongda.top/Article/details/gtofxwxokx.html

[R22] 截取子串
来源：http://dali.redwolf501.top/Article/details/gtqclywbxq.html

echo "${s:0:5}"
来源：http://dali.hammf.cn/Article/details/gthxgogzoc.html

[R23] 字符串替换
来源：http://dali.vqdsnc.cn/Article/details/gtsojrulhw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aibaodan.cn/Article/details/gtoqdvkwpp.html

[R24] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gtnkldbdfg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.316326.xyz/Article/details/gtfbwwiujq.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenlongwang.top/Article/details/gtjxfipktr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sweek.top/Article/details/gttwcwbdam.html

[R26] 命令替换
来源：http://dali.hammf.cn/Article/details/gtutriygin.html

now=$(date +%F); echo "$now"
来源：http://dali.shangyingyoupin.top/Article/details/gtbkrjwnoc.html

[R27] 算术展开
来源：http://dali.xziqi.cn/Article/details/gtvmnjeell.html

echo $((1 + 2 * 3))
来源：http://dali.gzhubu.top/Article/details/gtywlerzgr.html

[R28] 浮点运算
来源：http://dali.nanxuanxn.top/Article/details/gtfxqttijz.html

echo "scale=2; 10/3" | bc
来源：http://dali.xylfe.cn/Article/details/gttmicmtrb.html

[R29] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gtaienjqet.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gzhubu.top/Article/details/gtgpmyjtce.html

[R30] 函数返回状态码
来源：http://dali.guowangkeji.top/Article/details/gthoilsogg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.aizwys.cn/Article/details/gttbunipsx.html

[R31] 局部变量
来源：http://dali.gaohongyu789.top/Article/details/gthkxidqlt.html


<!-- 参考信息 -->