代发 wailian999

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnlsckwip.html

C#:   if (x is null) {}
来源：http://dali.fengsongda.top/Article/details/gtrrnglxkz.html

[P07] 防抖与节流
来源：http://dali.yuanzhike.top/Article/details/gtdzliqjvm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenjidiqi.icu/Article/details/gtbpdqiumk.html

PHP:  // 手写时间戳比较
来源：http://dali.yanxiufei.cn/Article/details/gtlwthmirf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtukasawmm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gtcxrfsaru.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.svipenyu.cn/Article/details/gtpqsqagtx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj20258.top/Article/details/gtqtzfrbag.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.andypj.xyz/Article/details/gtrpytrqvn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.guannengcc.top/Article/details/gtyeaejech.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigfzy.top/Article/details/gtkczorpbw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.316326.xyz/Article/details/gtrwvyvxpf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenlongwang.top/Article/details/gtwpbunpsg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dianchejie.cn/Article/details/gtvcucfbtu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.andypj.xyz/Article/details/gtcstcbury.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hongshengwenyu.top/Article/details/gtqcrspuaa.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shuidangran.top/Article/details/gtxscafgpt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.redwolf501.top/Article/details/gtudezynvj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.daxiang520.top/Article/details/gtkvmqozor.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtythgbgcn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cqqwz.cn/Article/details/gthvhektrp.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtyxcroarb.html

[Q01] 创建表
来源：http://dali.bjfxy.top/Article/details/gtrrwgzhul.html

CREATE TABLE users (
来源：http://dali.kuanghao11.cn/Article/details/gtwoqugxgn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hongshengwenyu.top/Article/details/gteukjqbwe.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdqbmmxa.html

email VARCHAR(100) UNIQUE,
来源：http://dali.havefunace.top/Article/details/gtqfrrscpo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.aizwys.cn/Article/details/gtkrlgrqqk.html

);
来源：http://dali.feifeiyinyue.top/Article/details/gtmmfluwnf.html

[Q02] 创建带外键的表
来源：http://dali.sysykeji.top/Article/details/gtidohdmtm.html

CREATE TABLE orders (
来源：http://dali.yuanzhike.top/Article/details/gtptnnrxgg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.feifeiyinyue.top/Article/details/gtwszcpxqn.html

user_id INT NOT NULL,
来源：http://dali.9152youxi.cn/Article/details/gtfkuncjvb.html

amount DECIMAL(10, 2),
来源：http://dali.dashuyun.cn/Article/details/gtuqhdxujb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhoulong.xyz/Article/details/gtsidhtiho.html

);
来源：http://dali.aizwys.cn/Article/details/gtkfjodyfo.html

[Q03] 增加列
来源：http://dali.gogol.net.cn/Article/details/gtavrsqdrd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.iojbl.cn/Article/details/gtyczikqgi.html

[Q04] 修改列类型
来源：http://dali.sxryk.cn/Article/details/gtqwruxtzf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tanke756.top/Article/details/gtchjvspdo.html

[Q05] 重命名列
来源：http://dali.sufxvd.cn/Article/details/gtlqflsrjs.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cucudq.cn/Article/details/gthdafoxmu.html

[Q06] 删除列
来源：http://dali.ydzc1.top/Article/details/gtfahhjuhu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xinyue.icu/Article/details/gtnpembhnl.html

[Q07] 删除表
来源：http://dali.aizwys.cn/Article/details/gtrrelewbu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.316326.xyz/Article/details/gtudygclky.html

[Q08] 创建普通索引
来源：http://dali.andypj.xyz/Article/details/gtvdugqlis.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gtcggbuuwv.html

[Q09] 创建唯一索引
来源：http://dali.pengpengdd.cyou/Article/details/gtnmyjuxkp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hywenlv.cn/Article/details/gtlydcvfdj.html

[Q10] 插入单行
来源：http://dali.hnqzz.top/Article/details/gtfmspvlsa.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtexwtoyan.html

[Q11] 一次插入多行
来源：http://dali.nwbrower.top/Article/details/gtgelbnoge.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.9152youxi.cn/Article/details/gtjwjtqbxd.html

[Q12] 插入后取自增 ID
来源：http://dali.ybcxt.top/Article/details/gtpzgloltj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gotoacloud.top/Article/details/gtsenvmrqq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yueranfly.top/Article/details/gtrxfwcvgh.html

[Q13] 忽略重复插入
来源：http://dali.svipenyu.cn/Article/details/gtnfprkelu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gtdocaxvwm.html

[Q14] 存在则更新（upsert）
来源：http://dali.wangdashe.top/Article/details/gtixqhxngh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.meibo888.top/Article/details/gtgkjadoiz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gogol.net.cn/Article/details/gteqqilbdz.html

[Q15] 查询全部
来源：http://dali.feifeiyinyue.top/Article/details/gtjodyoszt.html

SELECT * FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtohlzghsc.html

[Q16] 查询指定列
来源：http://dali.xylfe.cn/Article/details/gtjglwqdds.html

SELECT id, name FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gthaisyajp.html

[Q17] 条件查询
来源：http://dali.jyoumei.cn/Article/details/gtayhlkmmk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.nwbrower.top/Article/details/gtpzjebcsm.html

[Q18] 模糊匹配
来源：http://dali.tianlin.xyz/Article/details/gtetsvlngu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.dashuyun.cn/Article/details/gtrfwvsdrh.html

[Q19] 范围查询
来源：http://dali.aizwys.cn/Article/details/gtebthoffq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xziqi.cn/Article/details/gtlffazwnd.html

[Q20] IN 列表
来源：http://dali.xziqi.cn/Article/details/gtasehetnu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.andypj.xyz/Article/details/gthksihnix.html

[Q21] 空值判断
来源：http://dali.chenlongwang.top/Article/details/gtonkbeuig.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrxmutxx.html

[Q22] 排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwzbrxkn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj20258.top/Article/details/gtwykzkbyj.html

[Q23] 分页
来源：http://dali.yj20258.top/Article/details/gtefcztghs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzcfljhw.html

[Q24] 去重
来源：http://dali.c1oappe.top/Article/details/gtlipfitwq.html

SELECT DISTINCT city FROM users;
来源：http://dali.daria6918.cn/Article/details/gtgsjncbjt.html

[Q25] 只取前 N 条
来源：http://dali.meibo888.top/Article/details/gtvwtgfujo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cqqwz.cn/Article/details/gtibvwqufh.html

[Q26] 计数
来源：http://dali.tianlin.xyz/Article/details/gtwqboetxd.html

SELECT COUNT(*) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrfxmrpj.html

[Q27] 条件计数
来源：http://dali.pycfn.com/Article/details/gtxzpwuixj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtexyhkecw.html

[Q28] 求和与平均
来源：http://dali.pycfn.com/Article/details/gtbgclfgsj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gttncijerp.html

[Q29] 最大最小值
来源：http://dali.sysykeji.top/Article/details/gtjrdamqqe.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj20258.top/Article/details/gtbnwkknzy.html

[Q30] 分组统计
来源：http://dali.tian-w.cn/Article/details/gtyfibznhn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gthdhhyzfe.html

[Q31] 分组后过滤
来源：http://dali.cucudq.cn/Article/details/gtdajuifoa.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.daria6918.cn/Article/details/gtjfyaoncv.html

[Q32] 分组拼接字符串
来源：http://dali.xylfe.cn/Article/details/gtozybbgkv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gtftwofoyq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.dashuyun.cn/Article/details/gtfduunwhr.html

[Q33] 多列分组
来源：http://dali.sufxvd.cn/Article/details/gtqolqwysr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gaohongyu789.top/Article/details/gtdgyfcshx.html

[Q34] 每组取第一条
来源：http://dali.iojbl.cn/Article/details/gtfragbuck.html

SELECT * FROM (
来源：http://dali.redwolf501.top/Article/details/gtrmrbwcwj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shzxlz.cn/Article/details/gtwhcxdlcb.html

) t WHERE rn = 1;
来源：http://dali.hfpthk.cn/Article/details/gtlmtvdkix.html

[Q35] 内连接
来源：http://dali.gaohongyu789.top/Article/details/gtmstwayld.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmxbozxr.html

[Q36] 左连接
来源：http://dali.zhongyouzk.top/Article/details/gtnsnotuww.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gtlgvsttcy.html

[Q37] 右连接
来源：http://dali.hnqzz.top/Article/details/gtecvhyfls.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.snrcjt.cn/Article/details/gtxfifkusu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.snrcjt.cn/Article/details/gtgozuokkh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvynyxkwy.html

[Q39] 自连接（查上下级）
来源：http://dali.shzxlz.cn/Article/details/gtpguiarmj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gogol.net.cn/Article/details/gtntiszunz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hywenlv.cn/Article/details/gtbjckynwn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhongyouzk.top/Article/details/gtcudxojws.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hnqzz.top/Article/details/gteafpaojf.html

[Q41] 多表连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrypztsb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jqgufenzy.top/Article/details/gtadnssusf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jianghu66.top/Article/details/gtbrfhlisf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.aizwys.cn/Article/details/gtdmjyedky.html

[Q42] 连接条件附加过滤
来源：http://dali.aibaodan.cn/Article/details/gtfgkzatap.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cheryme.top/Article/details/gtktndlrna.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shangyingyoupin.top/Article/details/gtzkimbbak.html

[Q43] 标量子查询
来源：http://dali.nanxuanxn.top/Article/details/gtavflkyoz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hfpthk.cn/Article/details/gtqaqgfkwe.html

[Q44] IN 子查询
来源：http://dali.jinqigfzy.top/Article/details/gttybychuo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigfzy.top/Article/details/gtuvfnxpvj.html

[Q45] EXISTS 判断存在
来源：http://dali.ppjwa.cn/Article/details/gtmqaiuweh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yongpay.top/Article/details/gtbayodfpr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj202588.top/Article/details/gtgzgqdydm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhoulong.xyz/Article/details/gtppmoqclv.html

[Q47] 与平均值比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlgtkifzd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnxiangtu.top/Article/details/gtxmtdxinq.html

[Q48] CTE 公用表表达式
来源：http://dali.havefunace.top/Article/details/gtnyiskouq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gaohongyu789.top/Article/details/gtscymlull.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.feifeiyinyue.top/Article/details/gtgunjhlqe.html

[Q49] 更新单行
来源：http://dali.gogol.net.cn/Article/details/gthsysxmag.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gtvlzxkdjg.html

[Q50] 批量更新
来源：http://dali.dashuyun.cn/Article/details/gtkosmwhxu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.0kj1m.cn/Article/details/gtgbggblku.html

[Q51] 用子查询更新
来源：http://dali.sysykeji.top/Article/details/gtglfvjayz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.snrcjt.cn/Article/details/gtpfbvouak.html

[Q52] 删除指定行
来源：http://dali.ivvv.top/Article/details/gtxgbixhum.html

DELETE FROM users WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtiuxfuhlt.html

[Q53] 按条件删除
来源：http://dali.sweek.top/Article/details/gtnxwodqxc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangtech.top/Article/details/gthzivebxx.html

[Q54] 清空表
来源：http://dali.fzhhl.top/Article/details/gtudqgzwyz.html

TRUNCATE TABLE logs;
来源：http://dali.yj202588.top/Article/details/gtvorxovzf.html

[Q55] 排名（并列占位）
来源：http://dali.jqgfzy.top/Article/details/gtysvtqhaf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.c1oappe.top/Article/details/gtnuxqjllz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cucudq.cn/Article/details/gtdpcjyvii.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrytbnoeo.html

[Q57] 行号
来源：http://dali.shuidangran.top/Article/details/gtwbuwmind.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtmjsdtzvc.html

[Q58] 累计求和
来源：http://dali.chenjidiqi.icu/Article/details/gthvhdfttv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.pycfn.com/Article/details/gtgkywilhg.html

[Q59] 分组内累计
来源：http://dali.nanxuanxn.top/Article/details/gtvwigzkzx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gttjxyzqoq.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuanzx.com/Article/details/gtqopwmiwb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.smart0.xyz/Article/details/gtvkuhxfbs.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtzupyktff.html

[Q61] 移动平均
来源：http://dali.ehwqpu.com/Article/details/gtkfveeprs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtlgukzqzq.html

[Q62] 分组占比
来源：http://dali.cheryme.top/Article/details/gtswbvqrfw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gtxrotleqz.html

[Q63] 开启事务
来源：http://dali.aibaodan.cn/Article/details/gtsdfzgohf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangshuangyany.cn/Article/details/gtnumqxovi.html

[Q64] 提交事务
来源：http://dali.gaohongyu789.top/Article/details/gtcomwufmx.html

COMMIT;
来源：http://dali.tianlin.xyz/Article/details/gtfvotqyqa.html

[Q65] 回滚事务
来源：http://dali.aizwys.cn/Article/details/gtyednlibu.html

ROLLBACK;
来源：http://dali.jlsjyb.cn/Article/details/gtgtrodfta.html

[Q66] 行锁查询
来源：http://dali.fengsongda.top/Article/details/gtxnxsvokb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shuidangran.top/Article/details/gtdegzdwih.html

[Q67] 设置隔离级别
来源：http://dali.redwolf501.top/Article/details/gthmddyloz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dianchejie.cn/Article/details/gtdkpmuqzf.html

[Q68] 保存点
来源：http://dali.chenlongwang.top/Article/details/gtcjulydlp.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gtpfxsfnao.html

ROLLBACK TO sp1;
来源：http://dali.haohaochexian.top/Article/details/gtnkuithfn.html

[Q69] 查看执行计划
来源：http://dali.gogol.net.cn/Article/details/gtqewkiyvx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gotoacloud.top/Article/details/gthiuplwit.html

[Q70] 更新统计信息
来源：http://dali.havefunace.top/Article/details/gtwgbtgeqb.html

ANALYZE TABLE users;
来源：http://dali.aizwys.cn/Article/details/gtcpihjvzk.html

[Q71] 查看建表语句
来源：http://dali.chenjidiqi.icu/Article/details/gtnhyitmeg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cdnleiting.top/Article/details/gtcchmdmpv.html

[Q72] 查看索引
来源：http://dali.feifeiyinyue.top/Article/details/gtjzywpohi.html

SHOW INDEX FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtyocjhzxd.html

[Q73] 查看表状态
来源：http://dali.hywenlv.cn/Article/details/gtgvlvxlbo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dianchejie.cn/Article/details/gtoxhzmkao.html

[Q74] 强制使用索引
来源：http://dali.gaohongyu789.top/Article/details/gtjnajlqug.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yueranfly.top/Article/details/gtcwqrweab.html

[Q75] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gtsgsbsgme.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtggnhepwf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangdashe.top/Article/details/gtmkorppew.html

[Q76] 按天统计
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbncvnuy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tanke756.top/Article/details/gtdghdvcec.html

[Q77] 时间加减
来源：http://dali.nanxinkj.top/Article/details/gtxnbvrzzp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cheryme.top/Article/details/gtfxlrcnwu.html

[Q78] 当前时间
来源：http://dali.cashguo.top/Article/details/gtttmkdyht.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinyuanbaomall.cn/Article/details/gttoojepbe.html

[Q79] 字符串拼接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzvarnjf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jlsjyb.cn/Article/details/gtxbkvrvat.html

[Q80] 字符串截取
来源：http://dali.havefunace.top/Article/details/gtwchbehpn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtgqjzxvmj.html

[Q81] 字符串替换
来源：http://dali.fengsongda.top/Article/details/gtuojadkss.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtafbfezlr.html

[Q82] 字符长度与字节长度
来源：http://dali.hnqzz.top/Article/details/gttnwkmzkc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtbxprhlac.html

[Q83] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gtbcizfxxg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtwsqduxmb.html

[Q84] 去除首尾空格
来源：http://dali.yangfankeji.com/Article/details/gtuegwvskr.html

SELECT TRIM(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtfonwpsvp.html

[Q85] 数值取整
来源：http://dali.shangyingyoupin.top/Article/details/gtfknbtrpq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ybcxt.top/Article/details/gtyxnoitxk.html

[Q86] 读取 JSON 字段
来源：http://dali.hammf.cn/Article/details/gtcruvapnu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqiejhpqr.html

[Q87] JSON 字段做条件
来源：http://dali.9152youxi.cn/Article/details/gthrrmrpwv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.9152youxi.cn/Article/details/gtovpymiuz.html

[Q88] 行转列（条件聚合）
来源：http://dali.sysykeji.top/Article/details/gtnoonorzj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ivvv.top/Article/details/gtkieeuahn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jianghu66.top/Article/details/gtyfhocujz.html

[Q89] 判断表是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gtfmuiijlu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hnqzz.top/Article/details/gtjmdivzat.html

[Q90] 生成序号列
来源：http://dali.cheryme.top/Article/details/gtmibnmsxs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.mhx1999.top/Article/details/gtrgsycblq.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtvfrcqyxm.html

R. Bash 专题
来源：http://dali.jinqigufen.top/Article/details/gtjvsphbty.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtkmvmhimi.html

[R01] shebang 与严格模式
来源：http://dali.gotoacloud.top/Article/details/gtwirlsgnd.html

#!/usr/bin/env bash
来源：http://dali.ybcxt.top/Article/details/gtkfmichdp.html

set -euo pipefail
来源：http://dali.birdmap.top/Article/details/gtugymylqd.html

[R02] 变量赋值与使用
来源：http://dali.zhongyouzk.top/Article/details/gtimnaqpvy.html

name="Tom"; echo "$name"
来源：http://dali.xylfe.cn/Article/details/gtkzxrbcpo.html

[R03] 只读变量
来源：http://dali.yvedp.cn/Article/details/gtspmfduob.html

readonly PI=3.14
来源：http://dali.shzxlz.cn/Article/details/gtfcjothgd.html

[R04] 位置参数
来源：http://dali.nanxinkj.top/Article/details/gtmeycsksl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhiwuduotai.top/Article/details/gtqcqtqjbt.html

[R05] 参数默认值
来源：http://dali.gzhubu.top/Article/details/gtrytbyasj.html

name="${1:-default}"
来源：http://dali.wangdashe.top/Article/details/gtqkqiwtro.html

[R06] 判断命令是否存在
来源：http://dali.yuanzhike.top/Article/details/gtustrtlkq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gtisowujda.html

[R07] if 判断文件
来源：http://dali.shzxlz.cn/Article/details/gttqrvdmdn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.havefunace.top/Article/details/gtarxouuiu.html

[R08] 数值比较
来源：http://dali.zhoulong.xyz/Article/details/gteuiybhda.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtdeibeypk.html

[R09] 字符串比较
来源：http://dali.fzhhl.top/Article/details/gtfilbyhuk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtwvpqybsg.html

[R10] 正则匹配
来源：http://dali.snrcjt.cn/Article/details/gtxjnyyymm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fzhhl.top/Article/details/gttbmdfpet.html

[R11] case 多分支
来源：http://dali.tianlin.xyz/Article/details/gttkmhninz.html

case "$1" in
来源：http://dali.yonumen.top/Article/details/gtkjfgaane.html

start) echo "启动" ;;
来源：http://dali.jqgufenzy.top/Article/details/gtflovmzyx.html

stop)  echo "停止" ;;
来源：http://dali.cqqwz.cn/Article/details/gtqnzwzctz.html

*)     echo "未知命令" ;;
来源：http://dali.yuanzhike.top/Article/details/gtiluucgdl.html

esac
来源：http://dali.daria6918.cn/Article/details/gtpcxozbrq.html

[R12] for 遍历文件
来源：http://dali.daxiang520.top/Article/details/gtqclqnptr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuanzx.com/Article/details/gtqqcksqpw.html

[R13] for 计数循环
来源：http://dali.dashuyun.cn/Article/details/gtymiocscc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gtnshkgyzj.html

[R14] C 风格 for
来源：http://dali.shzxlz.cn/Article/details/gtvztmiicg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhengqikj.top/Article/details/gttzpbqmty.html

[R15] while 逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtpusstyln.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sxryk.cn/Article/details/gtdlenvmck.html

[R16] until 等待条件
来源：http://dali.cashguo.top/Article/details/gtruyiawet.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gtzncqqqnz.html

[R17] 数组定义与取值
来源：http://dali.jinghuilouyu.cn/Article/details/gtndlrrxkb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yuxming.cn/Article/details/gtomhonwud.html

[R18] 遍历数组
来源：http://dali.yj202588.top/Article/details/gtkvhgmfhs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtfeylnpza.html

[R19] 数组长度
来源：http://dali.xuanzx.com/Article/details/gtiljsrlkr.html

echo "${#arr[@]}"
来源：http://dali.daria6918.cn/Article/details/gtevmhhsbl.html

[R20] 关联数组（字典）
来源：http://dali.jianghu66.top/Article/details/gtozxhbsuz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xylfe.cn/Article/details/gtopmneacy.html

[R21] 字符串长度
来源：http://dali.ydzc1.top/Article/details/gtlgcranzi.html

echo "${#s}"
来源：http://dali.hnxiangtu.top/Article/details/gtmcedxrus.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gtejsitkto.html

echo "${s:0:5}"
来源：http://dali.yueranfly.top/Article/details/gtmxwkomjr.html

[R23] 字符串替换
来源：http://dali.meibo888.top/Article/details/gtrunhldmu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gtpiglmlvl.html

[R24] 大小写转换
来源：http://dali.ppjwa.cn/Article/details/gtgprourdt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cdnleiting.top/Article/details/gtwrsahltx.html

[R25] 去后缀 / 去前缀
来源：http://dali.mhx1999.top/Article/details/gtmgtbakoj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xinyue.icu/Article/details/gtqfowcnjo.html

[R26] 命令替换
来源：http://dali.dianchejie.cn/Article/details/gtnpfvtevs.html

now=$(date +%F); echo "$now"
来源：http://dali.shangyingyoupin.top/Article/details/gtsifqjdoe.html

[R27] 算术展开
来源：http://dali.cqqwz.cn/Article/details/gtipngswak.html

echo $((1 + 2 * 3))
来源：http://dali.cucudq.cn/Article/details/gtbtyhslho.html

[R28] 浮点运算
来源：http://dali.zhixingplan.top/Article/details/gtdzugsdgd.html

echo "scale=2; 10/3" | bc
来源：http://dali.ppjwa.cn/Article/details/gtlfxbbdbc.html

[R29] 定义函数
来源：http://dali.hywenlv.cn/Article/details/gtcvjjaigw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.iojbl.cn/Article/details/gtybujsxum.html

[R30] 函数返回状态码
来源：http://dali.zdqjudy.top/Article/details/gtetjumhmf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.c1oappe.top/Article/details/gtbazjipbp.html

[R31] 局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gtqmpnhouq.html

f() { local x=1; echo "$x"; }
来源：http://dali.tian-w.cn/Article/details/gtqeuakszp.html

[R32] 参数个数校验
来源：http://dali.guowangkeji.top/Article/details/gthruafwsl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yangfankeji.com/Article/details/gtriyvxgbr.html

[R33] 捕获错误并提示行号
来源：http://dali.ybcxt.top/Article/details/gtdygvsmak.html


<!-- 参考信息 -->