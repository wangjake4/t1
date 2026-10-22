代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.aizwys.cn/Article/details/gtvojobqva.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigfzy.top/Article/details/gtfneddjqm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtfazynhxv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yuxming.cn/Article/details/gttitnjjdn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.svipenyu.cn/Article/details/gtjcizbnul.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jianghu66.top/Article/details/gtixelgeje.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinghuilouyu.cn/Article/details/gttejfevai.html

[P08] 处理浮点精度问题
来源：http://dali.yuanzhike.top/Article/details/gtvuwhkvih.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gotoacloud.top/Article/details/gtpmehphql.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jianghu66.top/Article/details/gtuifegdej.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xinyue.icu/Article/details/gtvezssfof.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenzaomai.com/Article/details/gteunvxgus.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.andypj.xyz/Article/details/gtumjijizu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aizwys.cn/Article/details/gtxyymhrav.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangdashe.top/Article/details/gtytiamjdu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjyettxgj.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtdqdveple.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cdnleiting.top/Article/details/gtamahkpcd.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gthsxqheag.html

[Q01] 创建表
来源：http://dali.daxiang520.top/Article/details/gtbpyrrlqc.html

CREATE TABLE users (
来源：http://dali.feifeiyinyue.top/Article/details/gtsoxhfkbt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gtghxixpdh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gtxoppcxbj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.pengpengdd.cyou/Article/details/gtrlodmnto.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hysaishi.cn/Article/details/gtfdffnvmm.html

);
来源：http://dali.hnqzz.top/Article/details/gtfmwlbezx.html

[Q02] 创建带外键的表
来源：http://dali.ppjwa.cn/Article/details/gtgryqpmet.html

CREATE TABLE orders (
来源：http://dali.cashguo.top/Article/details/gtxuwrlcon.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tian-w.cn/Article/details/gtpefybuaj.html

user_id INT NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gtygtzvves.html

amount DECIMAL(10, 2),
来源：http://dali.yj202588.top/Article/details/gtpugbypro.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.birdmap.top/Article/details/gttmtlslql.html

);
来源：http://dali.cheryme.top/Article/details/gtydnuohyq.html

[Q03] 增加列
来源：http://dali.nanxinkj.top/Article/details/gtoqpggmlr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gogol.net.cn/Article/details/gtpueegqfm.html

[Q04] 修改列类型
来源：http://dali.pengpengdd.cyou/Article/details/gthybhpwcs.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cqqwz.cn/Article/details/gtbhnfrakd.html

[Q05] 重命名列
来源：http://dali.hywenlv.cn/Article/details/gtgmuomdxo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yanxiufei.cn/Article/details/gtdcnahvqj.html

[Q06] 删除列
来源：http://dali.daria6918.cn/Article/details/gtiujusofm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hfpthk.cn/Article/details/gtqwmgovws.html

[Q07] 删除表
来源：http://dali.cucudq.cn/Article/details/gtuzgcwmao.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yuanzhike.top/Article/details/gtpybtqsut.html

[Q08] 创建普通索引
来源：http://dali.meibo888.top/Article/details/gtqqdosmav.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nanxuanxn.top/Article/details/gtfuktayop.html

[Q09] 创建唯一索引
来源：http://dali.fzhhl.top/Article/details/gtlyxotzig.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuujtxlme.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gtspycjmvy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.birdmap.top/Article/details/gtzgfadpsm.html

[Q11] 一次插入多行
来源：http://dali.haohaochexian.top/Article/details/gtvzzawftp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aizwys.cn/Article/details/gtmhubnwet.html

[Q12] 插入后取自增 ID
来源：http://dali.gzhubu.top/Article/details/gtqynvfzlf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.c1oappe.top/Article/details/gtyyagdyfh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.iojbl.cn/Article/details/gtkwcxkwvj.html

[Q13] 忽略重复插入
来源：http://dali.316326.xyz/Article/details/gtqjxpypnk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jianghu66.top/Article/details/gtgnqzdbvr.html

[Q14] 存在则更新（upsert）
来源：http://dali.jqgufenzy.top/Article/details/gtrjfnryjn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinqigufen.top/Article/details/gtumkscxbm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.mhx1999.top/Article/details/gtyjaosgxm.html

[Q15] 查询全部
来源：http://dali.aizwys.cn/Article/details/gtqumpoydf.html

SELECT * FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gthqurmxer.html

[Q16] 查询指定列
来源：http://dali.sxryk.cn/Article/details/gtbghzsnbq.html

SELECT id, name FROM users;
来源：http://dali.hammf.cn/Article/details/gtqpbsorin.html

[Q17] 条件查询
来源：http://dali.wangshuangyany.cn/Article/details/gtusexacaf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sysykeji.top/Article/details/gtuududxty.html

[Q18] 模糊匹配
来源：http://dali.yonumen.top/Article/details/gtnurdxaok.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacgqoeju.html

[Q19] 范围查询
来源：http://dali.jinqigufen.top/Article/details/gtlfcmyjdt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jianghu66.top/Article/details/gtgnfvoudz.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gtptrtsold.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuanzhike.top/Article/details/gtptacotid.html

[Q21] 空值判断
来源：http://dali.shuidangran.top/Article/details/gtdrhogwth.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.c1oappe.top/Article/details/gtdrglisnd.html

[Q22] 排序
来源：http://dali.tianlin.xyz/Article/details/gtbhxaayei.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.9152youxi.cn/Article/details/gtdouvlxms.html

[Q23] 分页
来源：http://dali.yj20258.top/Article/details/gtljvesgks.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hammf.cn/Article/details/gtocoejctb.html

[Q24] 去重
来源：http://dali.wangdashe.top/Article/details/gtltcocksv.html

SELECT DISTINCT city FROM users;
来源：http://dali.c1oappe.top/Article/details/gtawuufndu.html

[Q25] 只取前 N 条
来源：http://dali.ybcxt.top/Article/details/gtyvxkhwyo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aibaodan.cn/Article/details/gtctztyfpd.html

[Q26] 计数
来源：http://dali.daria6918.cn/Article/details/gtkrurbufa.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtjtqidtne.html

[Q27] 条件计数
来源：http://dali.yonumen.top/Article/details/gtxhupxnfz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yuxming.cn/Article/details/gtrmxrcmfe.html

[Q28] 求和与平均
来源：http://dali.redwolf501.top/Article/details/gtkumdjfnw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtqlbnxnjx.html

[Q29] 最大最小值
来源：http://dali.yuxming.cn/Article/details/gtttzwxiye.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtpwfyozxl.html

[Q30] 分组统计
来源：http://dali.jinqigfzy.top/Article/details/gtjzciflhf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtbzfetknf.html

[Q31] 分组后过滤
来源：http://dali.yvedp.cn/Article/details/gtruunvdqs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cdnleiting.top/Article/details/gtnuhclzhz.html

[Q32] 分组拼接字符串
来源：http://dali.yonumen.top/Article/details/gtzthklplt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gtvptrrnbm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.dashuyun.cn/Article/details/gtwtypjejz.html

[Q33] 多列分组
来源：http://dali.zhoulong.xyz/Article/details/gtkmxxjxog.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tanke756.top/Article/details/gtzfpzsxeb.html

[Q34] 每组取第一条
来源：http://dali.feifeiyinyue.top/Article/details/gtvclgwrjo.html

SELECT * FROM (
来源：http://dali.shanyushiyangtech.top/Article/details/gtnsuzjaku.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sufxvd.cn/Article/details/gtexcahegs.html

) t WHERE rn = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtvrvsiduj.html

[Q35] 内连接
来源：http://dali.ehwqpu.com/Article/details/gtnhrzgmjf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ehwqpu.com/Article/details/gtvhmribax.html

[Q36] 左连接
来源：http://dali.cucudq.cn/Article/details/gthmlafpej.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yangfankeji.com/Article/details/gtraffptvb.html

[Q37] 右连接
来源：http://dali.hammf.cn/Article/details/gtamnyblxs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhixingplan.top/Article/details/gtgzdhqicx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.havefunace.top/Article/details/gtwdlakust.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ybcxt.top/Article/details/gtblbesfyc.html

[Q39] 自连接（查上下级）
来源：http://dali.jyoumei.cn/Article/details/gtnysykwah.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuanzhike.top/Article/details/gtmvhfpkes.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tanke756.top/Article/details/gtdnvqtkjv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gaohongyu789.top/Article/details/gttxtiymom.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.daxiang520.top/Article/details/gtmwweqwlx.html

[Q41] 多表连接
来源：http://dali.birdmap.top/Article/details/gtygclrjne.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jianghu66.top/Article/details/gtgcjyvnjc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.wangdashe.top/Article/details/gttyqnoflu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.andypj.xyz/Article/details/gtdpdrapmh.html

[Q42] 连接条件附加过滤
来源：http://dali.hnxiangtu.top/Article/details/gtwektptaa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.guowangkeji.top/Article/details/gtexpxvdsm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aibaodan.cn/Article/details/gtnigcqglm.html

[Q43] 标量子查询
来源：http://dali.yanxiufei.cn/Article/details/gtjxqkvnyo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xziqi.cn/Article/details/gtfucudulb.html

[Q44] IN 子查询
来源：http://dali.ehwqpu.com/Article/details/gtiezeruxp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.pengpengdd.cyou/Article/details/gtmsqutoiz.html

[Q45] EXISTS 判断存在
来源：http://dali.ydzc1.top/Article/details/gtfizwpitx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gtognmqrqd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zdqjudy.top/Article/details/gtxgbdpeow.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gteqcfcsqi.html

[Q47] 与平均值比较
来源：http://dali.haohaochexian.top/Article/details/gtzsnzutgc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenzaomai.com/Article/details/gtmalfkfln.html

[Q48] CTE 公用表表达式
来源：http://dali.sysykeji.top/Article/details/gtnkadlhjr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tanke756.top/Article/details/gtufvmcequ.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.bjfxy.top/Article/details/gtkykqqnex.html

[Q49] 更新单行
来源：http://dali.ivvv.top/Article/details/gtfuogloqj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yonumen.top/Article/details/gtzusrxzpb.html

[Q50] 批量更新
来源：http://dali.feifeiyinyue.top/Article/details/gtiqtdanng.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nanxinkj.top/Article/details/gtefhddguk.html

[Q51] 用子查询更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlhmkmxt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.iojbl.cn/Article/details/gtnrbzzexx.html

[Q52] 删除指定行
来源：http://dali.iojbl.cn/Article/details/gtxtyqlnco.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gtlfuvtdjy.html

[Q53] 按条件删除
来源：http://dali.jianghu66.top/Article/details/gtduigeplm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shuidangran.top/Article/details/gtrpndjjgg.html

[Q54] 清空表
来源：http://dali.daria6918.cn/Article/details/gtmyvgwckm.html

TRUNCATE TABLE logs;
来源：http://dali.hnxiangtu.top/Article/details/gtnslniuyr.html

[Q55] 排名（并列占位）
来源：http://dali.yangfankeji.com/Article/details/gtfxawlyif.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xylfe.cn/Article/details/gtkotykxgf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jyoumei.cn/Article/details/gtzwmwrfay.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.iojbl.cn/Article/details/gtovqyllhq.html

[Q57] 行号
来源：http://dali.vqdsnc.cn/Article/details/gtynwuacto.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsyavyobj.html

[Q58] 累计求和
来源：http://dali.nanxinkj.top/Article/details/gtslaxhujp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtdgvbasba.html

[Q59] 分组内累计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewhpzjrs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtgqlmqeuh.html

[Q60] 取上一行 / 下一行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtchhuubqv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sysykeji.top/Article/details/gtgofoljqv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gttcltford.html

[Q61] 移动平均
来源：http://dali.yuanzhike.top/Article/details/gtmonmwdqp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtzzzadzeg.html

[Q62] 分组占比
来源：http://dali.yangfankeji.com/Article/details/gtlzregtzl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtghseurgb.html

[Q63] 开启事务
来源：http://dali.nwbrower.top/Article/details/gtkrodskca.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.daria6918.cn/Article/details/gtlmndzaqx.html

[Q64] 提交事务
来源：http://dali.birdmap.top/Article/details/gtqfpjvoca.html

COMMIT;
来源：http://dali.gzhubu.top/Article/details/gtkmivbsot.html

[Q65] 回滚事务
来源：http://dali.yongpay.top/Article/details/gtbeigcgnk.html

ROLLBACK;
来源：http://dali.quarkkingdee.top/Article/details/gtbfvtaemn.html

[Q66] 行锁查询
来源：http://dali.ppjwa.cn/Article/details/gtnvztlwcd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hammf.cn/Article/details/gtlnimeksf.html

[Q67] 设置隔离级别
来源：http://dali.zhixingplan.top/Article/details/gtwncerzwt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yongpay.top/Article/details/gtxohjqxxj.html

[Q68] 保存点
来源：http://dali.zhongyouzk.top/Article/details/gtafzjuisz.html

SAVEPOINT sp1;
来源：http://dali.zhoulong.xyz/Article/details/gtyvamimqk.html

ROLLBACK TO sp1;
来源：http://dali.yj20258.top/Article/details/gtlxfpymlj.html

[Q69] 查看执行计划
来源：http://dali.smart0.xyz/Article/details/gtkesropxp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jiagoushi.top/Article/details/gteakljeln.html

[Q70] 更新统计信息
来源：http://dali.fzhhl.top/Article/details/gtswmbvqop.html

ANALYZE TABLE users;
来源：http://dali.yvedp.cn/Article/details/gtwjfhlvwo.html

[Q71] 查看建表语句
来源：http://dali.dianchejie.cn/Article/details/gtgbruaqvo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nanxuanxn.top/Article/details/gttjueyprm.html

[Q72] 查看索引
来源：http://dali.redwolf501.top/Article/details/gtyewqnqfg.html

SHOW INDEX FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gteghhpwcq.html

[Q73] 查看表状态
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlryhbdrk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nwbrower.top/Article/details/gtrygqirwh.html

[Q74] 强制使用索引
来源：http://dali.ehwqpu.com/Article/details/gtdgmknrre.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yanxiufei.cn/Article/details/gttmsxbptf.html

[Q75] 日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gtbepdcqdh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtdeaceard.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jlsjyb.cn/Article/details/gtnutjajbp.html

[Q76] 按天统计
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrjmbecm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfyjofbz.html

[Q77] 时间加减
来源：http://dali.andypj.xyz/Article/details/gtwlgwzlbl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dashuyun.cn/Article/details/gtbxfkxgiy.html

[Q78] 当前时间
来源：http://dali.iojbl.cn/Article/details/gtgozulssu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.fengsongda.top/Article/details/gtrdltkumh.html

[Q79] 字符串拼接
来源：http://dali.gzhubu.top/Article/details/gtzizkiosa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hfpthk.cn/Article/details/gthmgwxwiy.html

[Q80] 字符串截取
来源：http://dali.dashuyun.cn/Article/details/gtklhdkddq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtvpyvbbde.html

[Q81] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gtekgugtby.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtptbhcmey.html

[Q82] 字符长度与字节长度
来源：http://dali.gaohongyu789.top/Article/details/gttpugufqg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtctcgbmbj.html

[Q83] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gtxtzmjazf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtigyhlfvp.html

[Q84] 去除首尾空格
来源：http://dali.yangfankeji.com/Article/details/gttepivihv.html

SELECT TRIM(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtkmwfwsbx.html

[Q85] 数值取整
来源：http://dali.jinqigfzy.top/Article/details/gtnxfxmrdv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ydzc1.top/Article/details/gtnhfrrgkk.html

[Q86] 读取 JSON 字段
来源：http://dali.hnxiangtu.top/Article/details/gthfdqaqli.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jlsjyb.cn/Article/details/gtpqeykoxp.html

[Q87] JSON 字段做条件
来源：http://dali.cheryme.top/Article/details/gtocxyntza.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hammf.cn/Article/details/gtfslrkywx.html

[Q88] 行转列（条件聚合）
来源：http://dali.haohaochexian.top/Article/details/gtgcpscwro.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnxiangtu.top/Article/details/gtaeqsxicr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.svipenyu.cn/Article/details/gttmjbzshq.html

[Q89] 判断表是否存在
来源：http://dali.jinqigfzy.top/Article/details/gthzniwhhw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.bjfxy.top/Article/details/gtoyyzouyv.html

[Q90] 生成序号列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoefoubty.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangdashe.top/Article/details/gtxmhamgro.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtckpiitwg.html

R. Bash 专题
来源：http://dali.jianghu66.top/Article/details/gtiyqomdns.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkirmfci.html

[R01] shebang 与严格模式
来源：http://dali.sufxvd.cn/Article/details/gtqefozvvn.html

#!/usr/bin/env bash
来源：http://dali.hywenlv.cn/Article/details/gtooevcxaa.html

set -euo pipefail
来源：http://dali.wangshuangyany.cn/Article/details/gtcihfzuxu.html

[R02] 变量赋值与使用
来源：http://dali.fengsongda.top/Article/details/gtytboiwca.html

name="Tom"; echo "$name"
来源：http://dali.feifeiyinyue.top/Article/details/gtnsxwgyhz.html

[R03] 只读变量
来源：http://dali.sysykeji.top/Article/details/gtetzjqelw.html

readonly PI=3.14
来源：http://dali.sweek.top/Article/details/gtfueefkhv.html

[R04] 位置参数
来源：http://dali.hysaishi.cn/Article/details/gtjiemhysc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.0kj1m.cn/Article/details/gtnqpwlpae.html

[R05] 参数默认值
来源：http://dali.sufxvd.cn/Article/details/gteldtltts.html

name="${1:-default}"
来源：http://dali.c1oappe.top/Article/details/gtnyrflfew.html

[R06] 判断命令是否存在
来源：http://dali.cdnleiting.top/Article/details/gttvrtewus.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.fzhhl.top/Article/details/gtvhzgllzo.html

[R07] if 判断文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhlgbfjf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gzhubu.top/Article/details/gtknvvfcmb.html

[R08] 数值比较
来源：http://dali.mhx1999.top/Article/details/gtyavnmudi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchkhljhg.html

[R09] 字符串比较
来源：http://dali.yj202588.top/Article/details/gtqxkkyouy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cqqwz.cn/Article/details/gtzbgmrplh.html

[R10] 正则匹配
来源：http://dali.guowangkeji.top/Article/details/gtxtxvnaia.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tian-w.cn/Article/details/gtbxmkroxk.html

[R11] case 多分支
来源：http://dali.fzhhl.top/Article/details/gtyceqwrqk.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gthcvgzwgk.html

start) echo "启动" ;;
来源：http://dali.aizwys.cn/Article/details/gtesaofnoh.html

stop)  echo "停止" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gtmdrlwzoz.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigufen.top/Article/details/gtunqharct.html

esac
来源：http://dali.jqgfzy.top/Article/details/gteasicnfe.html

[R12] for 遍历文件
来源：http://dali.haohaochexian.top/Article/details/gtstnsaoud.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258888.top/Article/details/gtawqoxvdw.html

[R13] for 计数循环
来源：http://dali.feifeiyinyue.top/Article/details/gtddgnuchd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gtxnrgtbxc.html

[R14] C 风格 for
来源：http://dali.jiagoushi.top/Article/details/gtpuskablh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jianghu66.top/Article/details/gtkjhooehx.html

[R15] while 逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gthgyeyjhp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fengsongda.top/Article/details/gtxkggpzmm.html

[R16] until 等待条件
来源：http://dali.hywenlv.cn/Article/details/gtccegsaji.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgufenzy.top/Article/details/gtzeystnuc.html

[R17] 数组定义与取值
来源：http://dali.quarkkingdee.top/Article/details/gtdvvqoqsu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdixjlgsp.html

[R18] 遍历数组
来源：http://dali.cqqwz.cn/Article/details/gtvqrddayz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gtrkhwposx.html

[R19] 数组长度
来源：http://dali.shuidangran.top/Article/details/gtvceeszot.html

echo "${#arr[@]}"
来源：http://dali.hywenlv.cn/Article/details/gtdwekpjhp.html

[R20] 关联数组（字典）
来源：http://dali.fengsongda.top/Article/details/gtddhsxudo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ybcxt.top/Article/details/gtgrtjbuxx.html

[R21] 字符串长度
来源：http://dali.xinyue.icu/Article/details/gtezstrbcu.html

echo "${#s}"
来源：http://dali.sysykeji.top/Article/details/gtysxucont.html

[R22] 截取子串
来源：http://dali.ehwqpu.com/Article/details/gtjzcsxzcr.html

echo "${s:0:5}"
来源：http://dali.haohaochexian.top/Article/details/gtqlvdouoz.html

[R23] 字符串替换
来源：http://dali.316326.xyz/Article/details/gtsrftyxcx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.meibo888.top/Article/details/gttocftbwx.html

[R24] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gttpcfnbdu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.mhx1999.top/Article/details/gtfzzmvdxp.html

[R25] 去后缀 / 去前缀
来源：http://dali.jiagoushi.top/Article/details/gtccxgydwk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nanxuanxn.top/Article/details/gtaworeuhw.html

[R26] 命令替换
来源：http://dali.yvedp.cn/Article/details/gtcqacwcfi.html

now=$(date +%F); echo "$now"
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzpgqzaf.html

[R27] 算术展开
来源：http://dali.tianlin.xyz/Article/details/gtvgpxbqbd.html

echo $((1 + 2 * 3))
来源：http://dali.sweek.top/Article/details/gtdjvajpta.html

[R28] 浮点运算
来源：http://dali.hnqzz.top/Article/details/gtambvdmhu.html

echo "scale=2; 10/3" | bc
来源：http://dali.gogol.net.cn/Article/details/gtycecdigz.html

[R29] 定义函数
来源：http://dali.jianghu66.top/Article/details/gtuldjifch.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.meibo888.top/Article/details/gtyuiokuwy.html

[R30] 函数返回状态码
来源：http://dali.tianlin.xyz/Article/details/gtmxnmaqdh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.birdmap.top/Article/details/gthbiryddz.html

[R31] 局部变量
来源：http://dali.mhx1999.top/Article/details/gtbjxxulwi.html

f() { local x=1; echo "$x"; }
来源：http://dali.sysykeji.top/Article/details/gtunmaqprs.html

[R32] 参数个数校验
来源：http://dali.yuxming.cn/Article/details/gtdbjgzysv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gttcdnohar.html

[R33] 捕获错误并提示行号
来源：http://dali.cucudq.cn/Article/details/gtedxwqtmb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hongshengwenyu.top/Article/details/gtcinghltj.html

[R34] 退出时清理
来源：http://dali.aizwys.cn/Article/details/gtwmsupqii.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangshuangyany.cn/Article/details/gtgcmcypjr.html

[R35] 后台执行并等待
来源：http://dali.zhiwuduotai.top/Article/details/gtszbcujvg.html


<!-- 参考信息 -->