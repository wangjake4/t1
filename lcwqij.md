代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xziqi.cn/Article/details/gtzfelvkbb.html

TS:   if (x == null) {}
来源：http://dali.zhongyouzk.top/Article/details/gttczhygqs.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gtsrhcvjwe.html

Go:   if x == nil {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzswvwmto.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aibaodan.cn/Article/details/gtutgjliwo.html

C#:   if (x is null) {}
来源：http://dali.dashuyun.cn/Article/details/gtirflmlcu.html

[P07] 防抖与节流
来源：http://dali.bjfxy.top/Article/details/gteyzcebko.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.dashuyun.cn/Article/details/gtdwkwnyxv.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258888.top/Article/details/gtpovpvruc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gtwzqofszu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gtribklboa.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.smart0.xyz/Article/details/gtuqdbbuxp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.pengpengdd.cyou/Article/details/gtdrlcmghs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ehwqpu.com/Article/details/gttltobthh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nanxinkj.top/Article/details/gtraxgkwck.html

[P08] 处理浮点精度问题
来源：http://dali.hongshengwenyu.top/Article/details/gtxtntjeqx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cdnleiting.top/Article/details/gthmmjirkg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tanke756.top/Article/details/gtlgbxnnyd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jyoumei.cn/Article/details/gtiyycajoz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cqqwz.cn/Article/details/gtcfeuaduz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sufxvd.cn/Article/details/gtwbsigxif.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yongpay.top/Article/details/gtxjmcgrlz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shuidangran.top/Article/details/gtxoexaveu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.daxiang520.top/Article/details/gtjvmseunb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtghqovfvc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.9152youxi.cn/Article/details/gtubizqvkh.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtgkxxyboc.html

[Q01] 创建表
来源：http://dali.jyoumei.cn/Article/details/gthpvxohno.html

CREATE TABLE users (
来源：http://dali.cucudq.cn/Article/details/gtshjjvapv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guannengcc.top/Article/details/gtmhzefbft.html

name VARCHAR(50) NOT NULL,
来源：http://dali.andypj.xyz/Article/details/gtxlnxyfwt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sufxvd.cn/Article/details/gtzgmwrvre.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hysaishi.cn/Article/details/gtnzrardvx.html

);
来源：http://dali.jqgufenzy.top/Article/details/gtzehfmeki.html

[Q02] 创建带外键的表
来源：http://dali.quarkkingdee.top/Article/details/gtuscxawfn.html

CREATE TABLE orders (
来源：http://dali.zhongyouzk.top/Article/details/gtcloiarji.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigoaediu.html

user_id INT NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gtifsbsltz.html

amount DECIMAL(10, 2),
来源：http://dali.vqdsnc.cn/Article/details/gthgnmqfcg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinqigufen.top/Article/details/gtlmlcouod.html

);
来源：http://dali.jianghu66.top/Article/details/gtkjqxgbmk.html

[Q03] 增加列
来源：http://dali.ppjwa.cn/Article/details/gtesjjfipz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gtcukmdxrv.html

[Q04] 修改列类型
来源：http://dali.mhx1999.top/Article/details/gtewefpfss.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nwbrower.top/Article/details/gtmkygazno.html

[Q05] 重命名列
来源：http://dali.xziqi.cn/Article/details/gtbhmdtett.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sysykeji.top/Article/details/gtkcehotgh.html

[Q06] 删除列
来源：http://dali.svipenyu.cn/Article/details/gttqluejrj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.redwolf501.top/Article/details/gtkaeogjoq.html

[Q07] 删除表
来源：http://dali.tian-w.cn/Article/details/gtlksnrtaw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yvedp.cn/Article/details/gtbkjhsyid.html

[Q08] 创建普通索引
来源：http://dali.yuxming.cn/Article/details/gtxtwquqcl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhiwuduotai.top/Article/details/gtqfafplmk.html

[Q09] 创建唯一索引
来源：http://dali.yuxming.cn/Article/details/gtoditvayp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cashguo.top/Article/details/gtzyaphgdw.html

[Q10] 插入单行
来源：http://dali.pycfn.com/Article/details/gtjpljxegj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yvedp.cn/Article/details/gtdcyjagch.html

[Q11] 一次插入多行
来源：http://dali.zhongyouzk.top/Article/details/gtnnswjogl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcpqwsgsb.html

[Q12] 插入后取自增 ID
来源：http://dali.snrcjt.cn/Article/details/gtmmbzrnym.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhengqikj.top/Article/details/gtzgyapujn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gaohongyu789.top/Article/details/gtavybklen.html

[Q13] 忽略重复插入
来源：http://dali.yj20258888.top/Article/details/gtdbircuhx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj202588.top/Article/details/gtqfpyarde.html

[Q14] 存在则更新（upsert）
来源：http://dali.cucudq.cn/Article/details/gtilysgmeh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ydzc1.top/Article/details/gtmqklfwgv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.aizwys.cn/Article/details/gtcuhdfnti.html

[Q15] 查询全部
来源：http://dali.gzhubu.top/Article/details/gtiziqwiew.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gttagdtbpe.html

[Q16] 查询指定列
来源：http://dali.chenzaomai.com/Article/details/gtxgilpdow.html

SELECT id, name FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtmbycluci.html

[Q17] 条件查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdlvdvebe.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthciehkt.html

[Q18] 模糊匹配
来源：http://dali.nwbrower.top/Article/details/gtelxetuzl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gtjvemzwjs.html

[Q19] 范围查询
来源：http://dali.zhiwuduotai.top/Article/details/gtbbarjkwp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaynjnanl.html

[Q20] IN 列表
来源：http://dali.daxiang520.top/Article/details/gtuywwtunn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvgmbfvo.html

[Q21] 空值判断
来源：http://dali.zhoulong.xyz/Article/details/gtaokezuss.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gtouifzsrp.html

[Q22] 排序
来源：http://dali.jyoumei.cn/Article/details/gtzerabcfh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj20258.top/Article/details/gtqlyftkiv.html

[Q23] 分页
来源：http://dali.havefunace.top/Article/details/gtewajwsxe.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sxryk.cn/Article/details/gtddzlhevc.html

[Q24] 去重
来源：http://dali.yj202588.top/Article/details/gtbiejseko.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtvalpuksm.html

[Q25] 只取前 N 条
来源：http://dali.yangfankeji.com/Article/details/gtyyattept.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sysykeji.top/Article/details/gtlgrotxvr.html

[Q26] 计数
来源：http://dali.feifeiyinyue.top/Article/details/gtcziffiwd.html

SELECT COUNT(*) FROM users;
来源：http://dali.meibo888.top/Article/details/gtkuwjcken.html

[Q27] 条件计数
来源：http://dali.xuetiantiany.cn/Article/details/gtuizoazxq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtirxrovzv.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutpfmalg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtljckzisx.html

[Q29] 最大最小值
来源：http://dali.ybcxt.top/Article/details/gtxpteblgu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.pycfn.com/Article/details/gtyfslujcw.html

[Q30] 分组统计
来源：http://dali.yj20258888.top/Article/details/gttkdxulhg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gtvurbsyjc.html

[Q31] 分组后过滤
来源：http://dali.daria6918.cn/Article/details/gteowgndfv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinqigfzy.top/Article/details/gtnetqfdde.html

[Q32] 分组拼接字符串
来源：http://dali.yonumen.top/Article/details/gtfkekrouv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gtlphqtuuq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuetiantiany.cn/Article/details/gtihbuvqbu.html

[Q33] 多列分组
来源：http://dali.zdqjudy.top/Article/details/gtnyhksijd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aizwys.cn/Article/details/gtmyqfydsa.html

[Q34] 每组取第一条
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvgatdvr.html

SELECT * FROM (
来源：http://dali.cdnleiting.top/Article/details/gtqegxqmlv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dashuyun.cn/Article/details/gtisodulyd.html

) t WHERE rn = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcocukgp.html

[Q35] 内连接
来源：http://dali.shuidangran.top/Article/details/gtsputtrtc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgufenzy.top/Article/details/gtqvuwlwpx.html

[Q36] 左连接
来源：http://dali.chenzaomai.com/Article/details/gtxiehiegi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cucudq.cn/Article/details/gtbkmigcll.html

[Q37] 右连接
来源：http://dali.316326.xyz/Article/details/gtsbltqano.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.wangdashe.top/Article/details/gtugpnpqwh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ivvv.top/Article/details/gtgwhmdanh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.guannengcc.top/Article/details/gtyyzhwamp.html

[Q39] 自连接（查上下级）
来源：http://dali.sysykeji.top/Article/details/gtouvqohfk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gotoacloud.top/Article/details/gtcrkflkmt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ybcxt.top/Article/details/gtgowlgxkf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.daria6918.cn/Article/details/gtbzjtovmi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aizwys.cn/Article/details/gtzqpdmibu.html

[Q41] 多表连接
来源：http://dali.fzhhl.top/Article/details/gthwuhzcbz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yvedp.cn/Article/details/gtezqbbhim.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yonumen.top/Article/details/gtpcjaojtn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nwbrower.top/Article/details/gtniadyilx.html

[Q42] 连接条件附加过滤
来源：http://dali.andypj.xyz/Article/details/gtvctcpgyv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuanzx.com/Article/details/gtfumlcrmx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aizwys.cn/Article/details/gtxswcilvg.html

[Q43] 标量子查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkzthiawb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yangfankeji.com/Article/details/gtoteqzysm.html

[Q44] IN 子查询
来源：http://dali.yueranfly.top/Article/details/gtnmsiiogx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqlruslvl.html

[Q45] EXISTS 判断存在
来源：http://dali.yj20258.top/Article/details/gtfqrpmiuq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fengsongda.top/Article/details/gtnhzsofyz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xuanzx.com/Article/details/gtplsjyjln.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yangfankeji.com/Article/details/gtpkerghga.html

[Q47] 与平均值比较
来源：http://dali.yj20258888.top/Article/details/gthfxpgjwg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jlsjyb.cn/Article/details/gtyaryxils.html

[Q48] CTE 公用表表达式
来源：http://dali.cdnleiting.top/Article/details/gthtfiiwxv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.c1oappe.top/Article/details/gtktaeltfh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yonumen.top/Article/details/gtelgjprlx.html

[Q49] 更新单行
来源：http://dali.kuanghao11.cn/Article/details/gtrbxljutl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yuxming.cn/Article/details/gtvgoafbgz.html

[Q50] 批量更新
来源：http://dali.kuanghao11.cn/Article/details/gtgdvouhgx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzfvuhbe.html

[Q51] 用子查询更新
来源：http://dali.kuanghao11.cn/Article/details/gtnwtgklog.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cheryme.top/Article/details/gtxppptdws.html

[Q52] 删除指定行
来源：http://dali.sxryk.cn/Article/details/gtpsxuwwmw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gtrqbrlwyw.html

[Q53] 按条件删除
来源：http://dali.redwolf501.top/Article/details/gtiodjyleg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cqqwz.cn/Article/details/gtcmatifhp.html

[Q54] 清空表
来源：http://dali.nwbrower.top/Article/details/gtvwlfnhcz.html

TRUNCATE TABLE logs;
来源：http://dali.shzxlz.cn/Article/details/gtbflzydgm.html

[Q55] 排名（并列占位）
来源：http://dali.fzhhl.top/Article/details/gtvsqidzjq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhongyouzk.top/Article/details/gtejgnzhbj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yuxming.cn/Article/details/gtwqosjsfd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gtfceghdav.html

[Q57] 行号
来源：http://dali.guannengcc.top/Article/details/gtazpmkxyq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gthxnagihd.html

[Q58] 累计求和
来源：http://dali.snrcjt.cn/Article/details/gtmcgvotrw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtxixpikoh.html

[Q59] 分组内累计
来源：http://dali.jinqigufen.top/Article/details/gtmrbkeagv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtxigdyjth.html

[Q60] 取上一行 / 下一行
来源：http://dali.vqdsnc.cn/Article/details/gteefqkenl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinghuilouyu.cn/Article/details/gteojwuqkr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtpsekzqtp.html

[Q61] 移动平均
来源：http://dali.shuidangran.top/Article/details/gtjpmraavl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtiwwcvyli.html

[Q62] 分组占比
来源：http://dali.0kj1m.cn/Article/details/gtltvhkfcn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtshogctnw.html

[Q63] 开启事务
来源：http://dali.yongpay.top/Article/details/gtnqqhlkbj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cheryme.top/Article/details/gtakrgmmkw.html

[Q64] 提交事务
来源：http://dali.xylfe.cn/Article/details/gtwldrejzy.html

COMMIT;
来源：http://dali.zhiwuduotai.top/Article/details/gtylydwgkp.html

[Q65] 回滚事务
来源：http://dali.mhx1999.top/Article/details/gtatgesnbl.html

ROLLBACK;
来源：http://dali.cashguo.top/Article/details/gtwwbbbzlt.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gtkpoaejlv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenzaomai.com/Article/details/gtylvlomey.html

[Q67] 设置隔离级别
来源：http://dali.andypj.xyz/Article/details/gtzesylwpy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ppjwa.cn/Article/details/gtrsuyqoxp.html

[Q68] 保存点
来源：http://dali.jinqigfzy.top/Article/details/gtluluxyps.html

SAVEPOINT sp1;
来源：http://dali.aibaodan.cn/Article/details/gtvehhywum.html

ROLLBACK TO sp1;
来源：http://dali.hfpthk.cn/Article/details/gtpnfacmcp.html

[Q69] 查看执行计划
来源：http://dali.hammf.cn/Article/details/gtcqdqkpmh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cashguo.top/Article/details/gtslelzeit.html

[Q70] 更新统计信息
来源：http://dali.nwbrower.top/Article/details/gtpusttegy.html

ANALYZE TABLE users;
来源：http://dali.meibo888.top/Article/details/gtagghgiej.html

[Q71] 查看建表语句
来源：http://dali.sysykeji.top/Article/details/gtyfuxswgz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xuetiantiany.cn/Article/details/gtxecitwod.html

[Q72] 查看索引
来源：http://dali.zhiwuduotai.top/Article/details/gtuznyxljt.html

SHOW INDEX FROM users;
来源：http://dali.sxryk.cn/Article/details/gtqvavxjud.html

[Q73] 查看表状态
来源：http://dali.sysykeji.top/Article/details/gtlfxpecyp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.mhx1999.top/Article/details/gtmqkqodmx.html

[Q74] 强制使用索引
来源：http://dali.mhx1999.top/Article/details/gtfrscphcx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jiagoushi.top/Article/details/gtefzjdvcy.html

[Q75] 日期格式化
来源：http://dali.shzxlz.cn/Article/details/gtgojkwqzc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ybcxt.top/Article/details/gthrahutqx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yuanzhike.top/Article/details/gtljcacxeo.html

[Q76] 按天统计
来源：http://dali.hammf.cn/Article/details/gtszfcjbzp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.birdmap.top/Article/details/gtqsfhsdkh.html

[Q77] 时间加减
来源：http://dali.yueranfly.top/Article/details/gtuxbiekoq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuanzhike.top/Article/details/gtonjmneqf.html

[Q78] 当前时间
来源：http://dali.hywenlv.cn/Article/details/gtsrzyojqt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.dianchejie.cn/Article/details/gtthlksgob.html

[Q79] 字符串拼接
来源：http://dali.zhiwuduotai.top/Article/details/gtilmmumpf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhiwuduotai.top/Article/details/gtxjtqwmbx.html

[Q80] 字符串截取
来源：http://dali.redwolf501.top/Article/details/gtvczgiejn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtoacamkqc.html

[Q81] 字符串替换
来源：http://dali.bjfxy.top/Article/details/gthatymzna.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ivvv.top/Article/details/gtlcqzckps.html

[Q82] 字符长度与字节长度
来源：http://dali.hongshengwenyu.top/Article/details/gtufunnrcr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtmjztqgxm.html

[Q83] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxolginvi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtfwtnayjl.html

[Q84] 去除首尾空格
来源：http://dali.cashguo.top/Article/details/gtcioxxhal.html

SELECT TRIM(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtcorrcnec.html

[Q85] 数值取整
来源：http://dali.zhoulong.xyz/Article/details/gtsvwpfwzr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbelrmdng.html

[Q86] 读取 JSON 字段
来源：http://dali.ydzc1.top/Article/details/gtgkxyrndx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cucudq.cn/Article/details/gtkgklqxit.html

[Q87] JSON 字段做条件
来源：http://dali.chenjidiqi.icu/Article/details/gtxwudfkbc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xziqi.cn/Article/details/gtmeayohqu.html

[Q88] 行转列（条件聚合）
来源：http://dali.iojbl.cn/Article/details/gttbwjrepw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.wangdashe.top/Article/details/gtedggduns.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ybcxt.top/Article/details/gtjexwidva.html

[Q89] 判断表是否存在
来源：http://dali.dashuyun.cn/Article/details/gtmowzkdoq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.mhx1999.top/Article/details/gtdxwpmcpr.html

[Q90] 生成序号列
来源：http://dali.zhoulong.xyz/Article/details/gtnlqghzra.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gogol.net.cn/Article/details/gtwmwnyzwc.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtwrxkwmjr.html

R. Bash 专题
来源：http://dali.jlsjyb.cn/Article/details/gtnxvmopsw.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtheldgcuj.html

[R01] shebang 与严格模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvjurdvz.html

#!/usr/bin/env bash
来源：http://dali.sweek.top/Article/details/gtwbfurtbz.html

set -euo pipefail
来源：http://dali.yueranfly.top/Article/details/gtaawjxafm.html

[R02] 变量赋值与使用
来源：http://dali.jianghu66.top/Article/details/gtwqpggukp.html

name="Tom"; echo "$name"
来源：http://dali.jqgufenzy.top/Article/details/gtkbltmwqw.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gtuxypiyot.html

readonly PI=3.14
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbifqboq.html

[R04] 位置参数
来源：http://dali.ehwqpu.com/Article/details/gtryiivkpo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuanzx.com/Article/details/gtqzfglzgx.html

[R05] 参数默认值
来源：http://dali.shzxlz.cn/Article/details/gtqudhdtsq.html

name="${1:-default}"
来源：http://dali.sweek.top/Article/details/gtzzduwxof.html

[R06] 判断命令是否存在
来源：http://dali.c1oappe.top/Article/details/gtnvztijrb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gaohongyu789.top/Article/details/gtzbdayptt.html

[R07] if 判断文件
来源：http://dali.daria6918.cn/Article/details/gtwqazjmcy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.meibo888.top/Article/details/gtqwfabymn.html

[R08] 数值比较
来源：http://dali.pycfn.com/Article/details/gteissrlfg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dashuyun.cn/Article/details/gtowgpsxuu.html

[R09] 字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gtmdntrauu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.mhx1999.top/Article/details/gtnpjugdzl.html

[R10] 正则匹配
来源：http://dali.hywenlv.cn/Article/details/gttvucclzw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cucudq.cn/Article/details/gtdtusywwo.html

[R11] case 多分支
来源：http://dali.jinqigfzy.top/Article/details/gtbriokklo.html

case "$1" in
来源：http://dali.316326.xyz/Article/details/gtmtqzxxhq.html

start) echo "启动" ;;
来源：http://dali.pycfn.com/Article/details/gtaydivkkj.html

stop)  echo "停止" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpddsonsa.html

*)     echo "未知命令" ;;
来源：http://dali.ivvv.top/Article/details/gtyrrsrshq.html

esac
来源：http://dali.fzhhl.top/Article/details/gtctqntjtj.html

[R12] for 遍历文件
来源：http://dali.tian-w.cn/Article/details/gtmulnpflz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cqqwz.cn/Article/details/gtchawwduk.html

[R13] for 计数循环
来源：http://dali.yanxiufei.cn/Article/details/gtyflsnrgz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yangfankeji.com/Article/details/gtifpveuwm.html

[R14] C 风格 for
来源：http://dali.zycfv.cn/Article/details/gtfquwogmo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jianghu66.top/Article/details/gtlokchwax.html

[R15] while 逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtsvmkaixf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhengqikj.top/Article/details/gtmtconhwd.html

[R16] until 等待条件
来源：http://dali.zycfv.cn/Article/details/gtalvlxekx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gtjmyyizpy.html

[R17] 数组定义与取值
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxdnqdbt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.quarkkingdee.top/Article/details/gtlixkjter.html

[R18] 遍历数组
来源：http://dali.chenjidiqi.icu/Article/details/gtweusqaay.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gogol.net.cn/Article/details/gtsnxjkywe.html

[R19] 数组长度
来源：http://dali.xziqi.cn/Article/details/gtowztjyuw.html

echo "${#arr[@]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnwprcyz.html

[R20] 关联数组（字典）
来源：http://dali.iojbl.cn/Article/details/gtuoyonrir.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.9152youxi.cn/Article/details/gtdfcsmmwd.html

[R21] 字符串长度
来源：http://dali.yonumen.top/Article/details/gttmvgcbor.html

echo "${#s}"
来源：http://dali.yj20258888.top/Article/details/gthmbutqtd.html

[R22] 截取子串
来源：http://dali.smart0.xyz/Article/details/gtkdyxswzp.html

echo "${s:0:5}"
来源：http://dali.yonumen.top/Article/details/gtcrxxvkfi.html

[R23] 字符串替换
来源：http://dali.jianghu66.top/Article/details/gttmzaelbl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj20258888.top/Article/details/gthmiiesia.html

[R24] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gtbkhckisf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tanke756.top/Article/details/gtkbyrliig.html

[R25] 去后缀 / 去前缀
来源：http://dali.fengsongda.top/Article/details/gtavlbbkhr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqmpxpot.html

[R26] 命令替换
来源：http://dali.quarkkingdee.top/Article/details/gtzmugghie.html

now=$(date +%F); echo "$now"
来源：http://dali.yangfankeji.com/Article/details/gtdstlhyrp.html

[R27] 算术展开
来源：http://dali.svipenyu.cn/Article/details/gtuuzisext.html

echo $((1 + 2 * 3))
来源：http://dali.nanxinkj.top/Article/details/gtljrzbplf.html

[R28] 浮点运算
来源：http://dali.hywenlv.cn/Article/details/gttoqnvpzq.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gtrhdcxeve.html

[R29] 定义函数
来源：http://dali.shzxlz.cn/Article/details/gtohgrmmny.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigfzy.top/Article/details/gtpydiqtsu.html

[R30] 函数返回状态码
来源：http://dali.cqqwz.cn/Article/details/gtdwzwprto.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zdqjudy.top/Article/details/gtxikshtde.html

[R31] 局部变量
来源：http://dali.chenzaomai.com/Article/details/gthnkizciy.html


<!-- 参考信息 -->