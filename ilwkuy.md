代发 wailian999

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.meibo888.top/Article/details/gtdanooxcn.html

C#:   if (x is null) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtzxtqkmzq.html

[P07] 防抖与节流
来源：http://dali.cdnleiting.top/Article/details/gtvhmsbrgq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.pycfn.com/Article/details/gtnuqivhmk.html

PHP:  // 手写时间戳比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqtnhasi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gtyskfatcs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtmhpdcjuz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.snrcjt.cn/Article/details/gtzjzjbqzi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shuidangran.top/Article/details/gttoarzosw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.svipenyu.cn/Article/details/gttsvivlcc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj20258888.top/Article/details/gtxmorolhf.html

[P08] 处理浮点精度问题
来源：http://dali.jiagoushi.top/Article/details/gtjxiafzob.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yvedp.cn/Article/details/gtjuetlayb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jqgfzy.top/Article/details/gthxrdujge.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbxeqlro.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gtlrhbohhv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.haohaochexian.top/Article/details/gthyapoaak.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.snrcjt.cn/Article/details/gtqhjibjth.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.aizwys.cn/Article/details/gtqkyopbje.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgufenzy.top/Article/details/gttuuaebcn.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtravhyoss.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cucudq.cn/Article/details/gtljgzkjox.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtsayzfpao.html

[Q01] 创建表
来源：http://dali.fengsongda.top/Article/details/gtqdwtgvwu.html

CREATE TABLE users (
来源：http://dali.pycfn.com/Article/details/gtczgpgfcc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrncgpimt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zdqjudy.top/Article/details/gtepfmwgem.html

email VARCHAR(100) UNIQUE,
来源：http://dali.kuanghao11.cn/Article/details/gtvimyvrpa.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jlsjyb.cn/Article/details/gttlgkidqn.html

);
来源：http://dali.tian-w.cn/Article/details/gtrweihtju.html

[Q02] 创建带外键的表
来源：http://dali.smart0.xyz/Article/details/gtnufndbtg.html

CREATE TABLE orders (
来源：http://dali.sufxvd.cn/Article/details/gtfmbnewrs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gotoacloud.top/Article/details/gtbnjvsuze.html

user_id INT NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gtntuwjkll.html

amount DECIMAL(10, 2),
来源：http://dali.birdmap.top/Article/details/gtowsryjyq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgufenzy.top/Article/details/gtgkhnarnb.html

);
来源：http://dali.cashguo.top/Article/details/gtkrabccoz.html

[Q03] 增加列
来源：http://dali.yuxming.cn/Article/details/gtosobucag.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.quarkkingdee.top/Article/details/gtldaietzr.html

[Q04] 修改列类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfkwqozv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.wangshuangyany.cn/Article/details/gtmoacprrt.html

[Q05] 重命名列
来源：http://dali.wangdashe.top/Article/details/gtapwmfjwb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxixrzzdk.html

[Q06] 删除列
来源：http://dali.chenzaomai.com/Article/details/gtgpcqsheq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jlsjyb.cn/Article/details/gtwpgjfmvs.html

[Q07] 删除表
来源：http://dali.jinghuilouyu.cn/Article/details/gtpsocjdko.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yuxming.cn/Article/details/gtatoigzao.html

[Q08] 创建普通索引
来源：http://dali.yvedp.cn/Article/details/gtkouyphmc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gtfdyflrmj.html

[Q09] 创建唯一索引
来源：http://dali.yj20258888.top/Article/details/gtedafacdv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yuanzhike.top/Article/details/gtmcbpecbf.html

[Q10] 插入单行
来源：http://dali.zhixingplan.top/Article/details/gtvdnzdmpm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gteptpjdwm.html

[Q11] 一次插入多行
来源：http://dali.ppjwa.cn/Article/details/gtfmzwooyg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gotoacloud.top/Article/details/gtfkfcomso.html

[Q12] 插入后取自增 ID
来源：http://dali.wangdashe.top/Article/details/gtpvtdtvxo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.birdmap.top/Article/details/gtfjhlvsni.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.fzhhl.top/Article/details/gtzhxextyt.html

[Q13] 忽略重复插入
来源：http://dali.jqgufenzy.top/Article/details/gtpltaqbia.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sysykeji.top/Article/details/gtebtujyce.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxinkj.top/Article/details/gtcwgcywbi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.iojbl.cn/Article/details/gttlxengyz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ivvv.top/Article/details/gtwuzbngst.html

[Q15] 查询全部
来源：http://dali.ybcxt.top/Article/details/gtvgclxyun.html

SELECT * FROM users;
来源：http://dali.ydzc1.top/Article/details/gttokolcvn.html

[Q16] 查询指定列
来源：http://dali.iojbl.cn/Article/details/gtcizopimi.html

SELECT id, name FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtqdxuwutd.html

[Q17] 条件查询
来源：http://dali.haohaochexian.top/Article/details/gtjuzmxabu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.0kj1m.cn/Article/details/gtczojtqkn.html

[Q18] 模糊匹配
来源：http://dali.zhoulong.xyz/Article/details/gtxxitfzbf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxinkj.top/Article/details/gtaitvdikr.html

[Q19] 范围查询
来源：http://dali.yueranfly.top/Article/details/gtbgcqgakt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhengqikj.top/Article/details/gtubeozfpv.html

[Q20] IN 列表
来源：http://dali.shuidangran.top/Article/details/gtlpquzkgh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj202588.top/Article/details/gtbfjapauf.html

[Q21] 空值判断
来源：http://dali.haohaochexian.top/Article/details/gtlemkghyp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shuidangran.top/Article/details/gtulgnpjig.html

[Q22] 排序
来源：http://dali.zycfv.cn/Article/details/gtoozlxmdr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yvedp.cn/Article/details/gtjtpzfuro.html

[Q23] 分页
来源：http://dali.hfpthk.cn/Article/details/gtkxbaerag.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.pengpengdd.cyou/Article/details/gtygnmplvu.html

[Q24] 去重
来源：http://dali.sufxvd.cn/Article/details/gtzcgvctvg.html

SELECT DISTINCT city FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtzgwponkc.html

[Q25] 只取前 N 条
来源：http://dali.hammf.cn/Article/details/gtawkbbofh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nanxinkj.top/Article/details/gtxteddrjt.html

[Q26] 计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncuxlzop.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtdhegjrmr.html

[Q27] 条件计数
来源：http://dali.hongshengwenyu.top/Article/details/gtneeebvux.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtkyndfrtp.html

[Q28] 求和与平均
来源：http://dali.shuidangran.top/Article/details/gtmqpukdvs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtlbccezlp.html

[Q29] 最大最小值
来源：http://dali.yj202588.top/Article/details/gtgnibpfxz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtizvivtxp.html

[Q30] 分组统计
来源：http://dali.smart0.xyz/Article/details/gtjinzsgds.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwchupum.html

[Q31] 分组后过滤
来源：http://dali.dianchejie.cn/Article/details/gtfewwexsi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jiagoushi.top/Article/details/gtdblzrjbi.html

[Q32] 分组拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gtfcvzxvei.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtgsyajdjx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yongpay.top/Article/details/gtseclbqle.html

[Q33] 多列分组
来源：http://dali.shzxlz.cn/Article/details/gtoaldidla.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gotoacloud.top/Article/details/gtebugifqw.html

[Q34] 每组取第一条
来源：http://dali.hysaishi.cn/Article/details/gtosccznch.html

SELECT * FROM (
来源：http://dali.daxiang520.top/Article/details/gtrorcqgno.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigfzy.top/Article/details/gtamsozqbq.html

) t WHERE rn = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwxnvrxx.html

[Q35] 内连接
来源：http://dali.cucudq.cn/Article/details/gteefhxvaw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sufxvd.cn/Article/details/gtjpujtnqv.html

[Q36] 左连接
来源：http://dali.jqgfzy.top/Article/details/gtgjbzkzdn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.svipenyu.cn/Article/details/gtrksbtyso.html

[Q37] 右连接
来源：http://dali.hywenlv.cn/Article/details/gtowoiclqx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tanke756.top/Article/details/gtfmvxfpwn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nwbrower.top/Article/details/gtnrboflul.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.feifeiyinyue.top/Article/details/gtcwpjipre.html

[Q39] 自连接（查上下级）
来源：http://dali.yonumen.top/Article/details/gtrgrjwwim.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tian-w.cn/Article/details/gtpucutfok.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tian-w.cn/Article/details/gtwxenhlci.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yanxiufei.cn/Article/details/gtrxcgwhdo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.birdmap.top/Article/details/gtmhvjiyko.html

[Q41] 多表连接
来源：http://dali.sysykeji.top/Article/details/gtthtvqetq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yonumen.top/Article/details/gtcufwteyy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.bjfxy.top/Article/details/gthwrlpbdh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yvedp.cn/Article/details/gtoffwecuu.html

[Q42] 连接条件附加过滤
来源：http://dali.hammf.cn/Article/details/gtolhnbcfc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hysaishi.cn/Article/details/gtcfamjmwc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.smart0.xyz/Article/details/gthnzefhcf.html

[Q43] 标量子查询
来源：http://dali.hnqzz.top/Article/details/gtnfkqzsuy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.daxiang520.top/Article/details/gtksawcyyu.html

[Q44] IN 子查询
来源：http://dali.9152youxi.cn/Article/details/gtggmqtzui.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shzxlz.cn/Article/details/gtrzpojukz.html

[Q45] EXISTS 判断存在
来源：http://dali.gogol.net.cn/Article/details/gtdurzbaoh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.316326.xyz/Article/details/gtqhurkeoc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhoulong.xyz/Article/details/gtaqdbrlfw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shangyingyoupin.top/Article/details/gtmukitkwv.html

[Q47] 与平均值比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtrucgiifz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ybcxt.top/Article/details/gtpagktycy.html

[Q48] CTE 公用表表达式
来源：http://dali.daxiang520.top/Article/details/gtpstgodvx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gotoacloud.top/Article/details/gtrilldtzb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhiwuduotai.top/Article/details/gtvokpzqfl.html

[Q49] 更新单行
来源：http://dali.yuxming.cn/Article/details/gtqyxmfxto.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tanke756.top/Article/details/gtouyjkpwq.html

[Q50] 批量更新
来源：http://dali.ehwqpu.com/Article/details/gtlmmqcbge.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aizwys.cn/Article/details/gtcfhpmzmr.html

[Q51] 用子查询更新
来源：http://dali.shuidangran.top/Article/details/gtaidzojtw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokncdhza.html

[Q52] 删除指定行
来源：http://dali.tianlin.xyz/Article/details/gtxkhftits.html

DELETE FROM users WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gtibtxzvhv.html

[Q53] 按条件删除
来源：http://dali.nanxuanxn.top/Article/details/gtqofmueej.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhengqikj.top/Article/details/gtketofknb.html

[Q54] 清空表
来源：http://dali.zhoulong.xyz/Article/details/gtywmlgaef.html

TRUNCATE TABLE logs;
来源：http://dali.gzhubu.top/Article/details/gttowdkzlf.html

[Q55] 排名（并列占位）
来源：http://dali.chenlongwang.top/Article/details/gtbzapsemq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenlongwang.top/Article/details/gtqyrqnbkz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cqqwz.cn/Article/details/gttrsecezs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hnxiangtu.top/Article/details/gtfabnucwg.html

[Q57] 行号
来源：http://dali.daria6918.cn/Article/details/gtacgjwlso.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtupgyltpr.html

[Q58] 累计求和
来源：http://dali.c1oappe.top/Article/details/gtythblgin.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtyhsyccpl.html

[Q59] 分组内累计
来源：http://dali.aizwys.cn/Article/details/gtzkyhzsyc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtqilpdhau.html

[Q60] 取上一行 / 下一行
来源：http://dali.ivvv.top/Article/details/gtmwvffglu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhengqikj.top/Article/details/gttbsojcfe.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtxkkbyjci.html

[Q61] 移动平均
来源：http://dali.jqgfzy.top/Article/details/gthqzdyjtb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtmeowfmqq.html

[Q62] 分组占比
来源：http://dali.jinqigfzy.top/Article/details/gtsjmpxqfq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtlgftgztm.html

[Q63] 开启事务
来源：http://dali.cheryme.top/Article/details/gtefzixxyi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinghuilouyu.cn/Article/details/gttffsoyum.html

[Q64] 提交事务
来源：http://dali.yuxming.cn/Article/details/gttzevfqeo.html

COMMIT;
来源：http://dali.cucudq.cn/Article/details/gtrziyrpbi.html

[Q65] 回滚事务
来源：http://dali.yongpay.top/Article/details/gtyrauuptt.html

ROLLBACK;
来源：http://dali.jqgufenzy.top/Article/details/gtspstrvep.html

[Q66] 行锁查询
来源：http://dali.hnxiangtu.top/Article/details/gtiwwzulnx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzqqbvfd.html

[Q67] 设置隔离级别
来源：http://dali.ehwqpu.com/Article/details/gtepjevuei.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.wangdashe.top/Article/details/gtsprpcyus.html

[Q68] 保存点
来源：http://dali.mhx1999.top/Article/details/gtsmfoosbz.html

SAVEPOINT sp1;
来源：http://dali.zhongyouzk.top/Article/details/gtbgzokyui.html

ROLLBACK TO sp1;
来源：http://dali.yvedp.cn/Article/details/gtddfsgjaa.html

[Q69] 查看执行计划
来源：http://dali.guannengcc.top/Article/details/gtreoxjngt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jqgufenzy.top/Article/details/gtxlitijki.html

[Q70] 更新统计信息
来源：http://dali.jqgfzy.top/Article/details/gtihryaflc.html

ANALYZE TABLE users;
来源：http://dali.tanke756.top/Article/details/gtwokigywx.html

[Q71] 查看建表语句
来源：http://dali.ppjwa.cn/Article/details/gtdbjezbwr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daria6918.cn/Article/details/gtbzqnxpab.html

[Q72] 查看索引
来源：http://dali.jinqigfzy.top/Article/details/gtkdbzbhzx.html

SHOW INDEX FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtgqzajmpd.html

[Q73] 查看表状态
来源：http://dali.guannengcc.top/Article/details/gtyrftsuyt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jqgufenzy.top/Article/details/gtjyaebqwp.html

[Q74] 强制使用索引
来源：http://dali.316326.xyz/Article/details/gtvilaemfo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenjidiqi.icu/Article/details/gthzogkfkl.html

[Q75] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gtljxztixf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtdohaedcw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.guowangkeji.top/Article/details/gtpchezmvt.html

[Q76] 按天统计
来源：http://dali.fzhhl.top/Article/details/gtkyflwxtn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.pycfn.com/Article/details/gttrsgolro.html

[Q77] 时间加减
来源：http://dali.yj20258.top/Article/details/gtgprcphvd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.svipenyu.cn/Article/details/gtdwvzwiti.html

[Q78] 当前时间
来源：http://dali.jyoumei.cn/Article/details/gtziousjmb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.c1oappe.top/Article/details/gtbtncddnd.html

[Q79] 字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gtwgzqiywn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yongpay.top/Article/details/gtukaaumxp.html

[Q80] 字符串截取
来源：http://dali.nwbrower.top/Article/details/gtipsvnhye.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtgkkwgfbk.html

[Q81] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gtzflopdwz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtkzbqgqsu.html

[Q82] 字符长度与字节长度
来源：http://dali.ydzc1.top/Article/details/gtvjrfqbkz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gttjbnfvun.html

[Q83] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gtaslpbnxp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtfpdolfjb.html

[Q84] 去除首尾空格
来源：http://dali.tian-w.cn/Article/details/gttmwrdkyt.html

SELECT TRIM(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtkhcwjndt.html

[Q85] 数值取整
来源：http://dali.vqdsnc.cn/Article/details/gthqnfrwlc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hnxiangtu.top/Article/details/gtzocxzntq.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigufen.top/Article/details/gtycrwgykc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.smart0.xyz/Article/details/gtigcllitm.html

[Q87] JSON 字段做条件
来源：http://dali.hongshengwenyu.top/Article/details/gtzllvoxop.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.smart0.xyz/Article/details/gtqunpyyjw.html

[Q88] 行转列（条件聚合）
来源：http://dali.daxiang520.top/Article/details/gtnntyevvf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tanke756.top/Article/details/gtafcalkoh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtujupykyg.html

[Q89] 判断表是否存在
来源：http://dali.tian-w.cn/Article/details/gtggbdagqn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinqigfzy.top/Article/details/gtniwfcnjm.html

[Q90] 生成序号列
来源：http://dali.yj20258888.top/Article/details/gtkymooluq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhengqikj.top/Article/details/gtrrevxidm.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqiususf.html

R. Bash 专题
来源：http://dali.meibo888.top/Article/details/gtrqulyccg.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtpvzampud.html

[R01] shebang 与严格模式
来源：http://dali.aibaodan.cn/Article/details/gtvamnknon.html

#!/usr/bin/env bash
来源：http://dali.cdnleiting.top/Article/details/gtwuamzhwg.html

set -euo pipefail
来源：http://dali.gotoacloud.top/Article/details/gtznroomxf.html

[R02] 变量赋值与使用
来源：http://dali.tianlin.xyz/Article/details/gtikhgcqlj.html

name="Tom"; echo "$name"
来源：http://dali.jqgfzy.top/Article/details/gtzyfqmfkr.html

[R03] 只读变量
来源：http://dali.jianghu66.top/Article/details/gtwwhtvxdh.html

readonly PI=3.14
来源：http://dali.yj202588.top/Article/details/gttbgzjgeb.html

[R04] 位置参数
来源：http://dali.cheryme.top/Article/details/gtyddojvsb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuxming.cn/Article/details/gtwrndujgb.html

[R05] 参数默认值
来源：http://dali.ehwqpu.com/Article/details/gtcxhhaoxz.html

name="${1:-default}"
来源：http://dali.haohaochexian.top/Article/details/gtnyuxnvcg.html

[R06] 判断命令是否存在
来源：http://dali.ehwqpu.com/Article/details/gtopdoyace.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.smart0.xyz/Article/details/gtqgszmpyv.html

[R07] if 判断文件
来源：http://dali.zhiwuduotai.top/Article/details/gtskbgydkm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sysykeji.top/Article/details/gtwjbulgmb.html

[R08] 数值比较
来源：http://dali.sufxvd.cn/Article/details/gtysoyhymx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.mhx1999.top/Article/details/gtdydcunhu.html

[R09] 字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjyhpeqx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nanxinkj.top/Article/details/gtuuwynlfr.html

[R10] 正则匹配
来源：http://dali.yonumen.top/Article/details/gtptjnlswp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xziqi.cn/Article/details/gtezthtmgc.html

[R11] case 多分支
来源：http://dali.zhixingplan.top/Article/details/gtxkysuxxv.html

case "$1" in
来源：http://dali.cdnleiting.top/Article/details/gtxoczzvqf.html

start) echo "启动" ;;
来源：http://dali.sxryk.cn/Article/details/gtldmvllvo.html

stop)  echo "停止" ;;
来源：http://dali.smart0.xyz/Article/details/gtgyrpzoqy.html

*)     echo "未知命令" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gtpmegrmka.html

esac
来源：http://dali.ydzc1.top/Article/details/gtmxqlbjwi.html

[R12] for 遍历文件
来源：http://dali.wangdashe.top/Article/details/gtfyqyzrmw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yuxming.cn/Article/details/gtuwhhihdh.html

[R13] for 计数循环
来源：http://dali.shzxlz.cn/Article/details/gtyezwxkvy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtnnulauvp.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gtehjeixtv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gtqixlwoxr.html

[R15] while 逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtfkagrynl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gaohongyu789.top/Article/details/gtyrljtrfw.html

[R16] until 等待条件
来源：http://dali.quarkkingdee.top/Article/details/gthtdpmrkp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gtvkmpmqim.html

[R17] 数组定义与取值
来源：http://dali.jqgufenzy.top/Article/details/gticxjejkh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gogol.net.cn/Article/details/gthivuskyp.html

[R18] 遍历数组
来源：http://dali.sweek.top/Article/details/gtvnoiukar.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guannengcc.top/Article/details/gtfhoewgaz.html

[R19] 数组长度
来源：http://dali.316326.xyz/Article/details/gtbydbwskg.html

echo "${#arr[@]}"
来源：http://dali.wangdashe.top/Article/details/gtxemqpjyd.html

[R20] 关联数组（字典）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvhzbqyq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcokrnfea.html

[R21] 字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwmflycr.html

echo "${#s}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhqlmsjf.html

[R22] 截取子串
来源：http://dali.9152youxi.cn/Article/details/gtepgeuage.html

echo "${s:0:5}"
来源：http://dali.pengpengdd.cyou/Article/details/gtirxdpsej.html

[R23] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gtwlxtvsty.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.daxiang520.top/Article/details/gtobwcwnxj.html

[R24] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtzdzhqonk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.andypj.xyz/Article/details/gtfshrgvgy.html

[R25] 去后缀 / 去前缀
来源：http://dali.gzhubu.top/Article/details/gtyfmbnegb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xziqi.cn/Article/details/gtjowgtppk.html

[R26] 命令替换
来源：http://dali.vqdsnc.cn/Article/details/gtdzsfklbw.html

now=$(date +%F); echo "$now"
来源：http://dali.xinyue.icu/Article/details/gtnheyehdt.html

[R27] 算术展开
来源：http://dali.9152youxi.cn/Article/details/gtthdjehpx.html

echo $((1 + 2 * 3))
来源：http://dali.hongshengwenyu.top/Article/details/gtktbwrbyt.html

[R28] 浮点运算
来源：http://dali.wangdashe.top/Article/details/gtlgauvmkm.html

echo "scale=2; 10/3" | bc
来源：http://dali.guannengcc.top/Article/details/gtgrywjsty.html

[R29] 定义函数
来源：http://dali.c1oappe.top/Article/details/gteosghnxy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cdnleiting.top/Article/details/gtfqpcjfah.html

[R30] 函数返回状态码
来源：http://dali.snrcjt.cn/Article/details/gtfdsdvamj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj202588.top/Article/details/gtfmcrjxdd.html

[R31] 局部变量
来源：http://dali.birdmap.top/Article/details/gtyyxvquay.html

f() { local x=1; echo "$x"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkwguzysy.html

[R32] 参数个数校验
来源：http://dali.cucudq.cn/Article/details/gtadozzhrw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gtlmtputrh.html

[R33] 捕获错误并提示行号
来源：http://dali.dianchejie.cn/Article/details/gtlgwlncmf.html


<!-- 参考信息 -->