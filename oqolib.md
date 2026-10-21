代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.feifeiyinyue.top/Article/details/gthdctzeje.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.guannengcc.top/Article/details/gthxqnfeuq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jqgufenzy.top/Article/details/gtyhmrvnog.html

PHP:  if (empty($x)) {}
来源：http://dali.yangfankeji.com/Article/details/gtkqxvcimr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgufenzy.top/Article/details/gtgzvkhsmd.html

TS:   if (x == null) {}
来源：http://dali.hammf.cn/Article/details/gtherfigtc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinqigfzy.top/Article/details/gtwrymieaw.html

Go:   if x == nil {}
来源：http://dali.hywenlv.cn/Article/details/gtaxkesanp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangdashe.top/Article/details/gtwigcbhhf.html

C#:   if (x is null) {}
来源：http://dali.hfpthk.cn/Article/details/gtxhrrdmhl.html

[P07] 防抖与节流
来源：http://dali.nwbrower.top/Article/details/gtqmyejxcq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.pycfn.com/Article/details/gtxpjxqnmt.html

PHP:  // 手写时间戳比较
来源：http://dali.haohaochexian.top/Article/details/gteviiqgzr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gtueqllrhx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gtquxmgizj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtamodhfpd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yueranfly.top/Article/details/gtghtmvdtw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xuetiantiany.cn/Article/details/gtmlnscqef.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tanke756.top/Article/details/gtyhfmxlay.html

[P08] 处理浮点精度问题
来源：http://dali.ivvv.top/Article/details/gtfvqjjujh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jiagoushi.top/Article/details/gtpmsvollh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jianghu66.top/Article/details/gtaqszxxvh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dashuyun.cn/Article/details/gtaxpqpqab.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cdnleiting.top/Article/details/gtaibdggfq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinqigfzy.top/Article/details/gthyrvfayz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zycfv.cn/Article/details/gtzbpuuhjl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ppjwa.cn/Article/details/gtfqfwxwhi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nwbrower.top/Article/details/gtjpivcurn.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtbryxvnws.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yvedp.cn/Article/details/gtmdfbmwzd.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtzjtsdqzg.html

[Q01] 创建表
来源：http://dali.c1oappe.top/Article/details/gthcdcotml.html

CREATE TABLE users (
来源：http://dali.zycfv.cn/Article/details/gtzxiqefjs.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.meibo888.top/Article/details/gttfnrkcbl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.birdmap.top/Article/details/gttmkyjntj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhoulong.xyz/Article/details/gtsuzlaqmw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daria6918.cn/Article/details/gtioayketz.html

);
来源：http://dali.hysaishi.cn/Article/details/gtckctruxl.html

[Q02] 创建带外键的表
来源：http://dali.yuanzhike.top/Article/details/gtekcgwmqs.html

CREATE TABLE orders (
来源：http://dali.9152youxi.cn/Article/details/gtoxmcecul.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenjidiqi.icu/Article/details/gtyeriecnf.html

user_id INT NOT NULL,
来源：http://dali.xuetiantiany.cn/Article/details/gtajpadkfi.html

amount DECIMAL(10, 2),
来源：http://dali.svipenyu.cn/Article/details/gtjddlbedh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.andypj.xyz/Article/details/gtjimfvuys.html

);
来源：http://dali.ppjwa.cn/Article/details/gtsnmmluiv.html

[Q03] 增加列
来源：http://dali.chenzaomai.com/Article/details/gtenyyyxdm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.0kj1m.cn/Article/details/gthfmqtabg.html

[Q04] 修改列类型
来源：http://dali.gogol.net.cn/Article/details/gtlyvpgsgq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jiagoushi.top/Article/details/gtsrfvnnyl.html

[Q05] 重命名列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxxggism.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jqgufenzy.top/Article/details/gtvdvjjmjq.html

[Q06] 删除列
来源：http://dali.ehwqpu.com/Article/details/gthwgptjcq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gzhubu.top/Article/details/gtwgjxozbi.html

[Q07] 删除表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbkaiwod.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtgszvfyhd.html

[Q08] 创建普通索引
来源：http://dali.yvedp.cn/Article/details/gtrmgmvgld.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yueranfly.top/Article/details/gtrhztsbnp.html

[Q09] 创建唯一索引
来源：http://dali.snrcjt.cn/Article/details/gtrmzytydz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xylfe.cn/Article/details/gtizmvzmfm.html

[Q10] 插入单行
来源：http://dali.wangshuangyany.cn/Article/details/gtgzfuxahk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gtpbdlygrq.html

[Q11] 一次插入多行
来源：http://dali.yj202588.top/Article/details/gtgogrwppe.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cheryme.top/Article/details/gtmcuqxfkx.html

[Q12] 插入后取自增 ID
来源：http://dali.xinyue.icu/Article/details/gttoncowtn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnqzz.top/Article/details/gtlgdjykko.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.feifeiyinyue.top/Article/details/gtsqbsftsz.html

[Q13] 忽略重复插入
来源：http://dali.sxryk.cn/Article/details/gtlnoecxdd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nwbrower.top/Article/details/gtudhrrrqe.html

[Q14] 存在则更新（upsert）
来源：http://dali.yueranfly.top/Article/details/gterjaxrhd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gtjjcjqngl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenlongwang.top/Article/details/gtxdzwmira.html

[Q15] 查询全部
来源：http://dali.xuetiantiany.cn/Article/details/gtsbyogokn.html

SELECT * FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gterfrbqvu.html

[Q16] 查询指定列
来源：http://dali.shanyushiyangtech.top/Article/details/gtefsdgalf.html

SELECT id, name FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtbaziplqq.html

[Q17] 条件查询
来源：http://dali.ybcxt.top/Article/details/gttksoahsn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtyitdeyjt.html

[Q18] 模糊匹配
来源：http://dali.gaohongyu789.top/Article/details/gthxqlitai.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xuanzx.com/Article/details/gtvqqifxep.html

[Q19] 范围查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxlobvifj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guannengcc.top/Article/details/gtsnnjeqov.html

[Q20] IN 列表
来源：http://dali.andypj.xyz/Article/details/gtatqbjaax.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.fzhhl.top/Article/details/gtavzcuwaf.html

[Q21] 空值判断
来源：http://dali.fengsongda.top/Article/details/gtseorwgtx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkytbqfb.html

[Q22] 排序
来源：http://dali.fzhhl.top/Article/details/gtqkfrghyw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gaohongyu789.top/Article/details/gtbxvapxtw.html

[Q23] 分页
来源：http://dali.9152youxi.cn/Article/details/gttnebonst.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.fengsongda.top/Article/details/gtayrkixdw.html

[Q24] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdktfipl.html

SELECT DISTINCT city FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtdvautlpf.html

[Q25] 只取前 N 条
来源：http://dali.zhiwuduotai.top/Article/details/gtgdckfuyp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gotoacloud.top/Article/details/gttnwqhdgc.html

[Q26] 计数
来源：http://dali.meibo888.top/Article/details/gtskxuwfgx.html

SELECT COUNT(*) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtldoilbob.html

[Q27] 条件计数
来源：http://dali.zhoulong.xyz/Article/details/gtvcogsfjk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fzhhl.top/Article/details/gtozvkdaae.html

[Q28] 求和与平均
来源：http://dali.gogol.net.cn/Article/details/gtdtivbjcx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtgrpykyfv.html

[Q29] 最大最小值
来源：http://dali.redwolf501.top/Article/details/gtfeibrzyn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ivvv.top/Article/details/gtnutlzslb.html

[Q30] 分组统计
来源：http://dali.zhengqikj.top/Article/details/gtmejrydbh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtxrvfidjg.html

[Q31] 分组后过滤
来源：http://dali.nanxuanxn.top/Article/details/gtdozqntmu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xziqi.cn/Article/details/gtrmzdvmzc.html

[Q32] 分组拼接字符串
来源：http://dali.hnqzz.top/Article/details/gtzvpphwqm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gtgkhvavgq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jlsjyb.cn/Article/details/gteizeonsp.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gttkgjpcec.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sweek.top/Article/details/gtkguwplxl.html

[Q34] 每组取第一条
来源：http://dali.yj20258888.top/Article/details/gtldsetokp.html

SELECT * FROM (
来源：http://dali.9152youxi.cn/Article/details/gtmsexbuaa.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigufen.top/Article/details/gteejeonao.html

) t WHERE rn = 1;
来源：http://dali.9152youxi.cn/Article/details/gtxwapopzv.html

[Q35] 内连接
来源：http://dali.guannengcc.top/Article/details/gtklmtphew.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhoulong.xyz/Article/details/gtgzyckkhc.html

[Q36] 左连接
来源：http://dali.zhiwuduotai.top/Article/details/gtohdcrqim.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gttxbduwko.html

[Q37] 右连接
来源：http://dali.yj202588.top/Article/details/gtkmqvxvxu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.pengpengdd.cyou/Article/details/gtwggbamvi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenjidiqi.icu/Article/details/gtrirxsbza.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sysykeji.top/Article/details/gtriadukkh.html

[Q39] 自连接（查上下级）
来源：http://dali.gaohongyu789.top/Article/details/gtykwxrczi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnqzz.top/Article/details/gtjhunnjqx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.0kj1m.cn/Article/details/gtlkbkkuao.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ppjwa.cn/Article/details/gthqlrkucr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xylfe.cn/Article/details/gtwkttycfx.html

[Q41] 多表连接
来源：http://dali.xinyue.icu/Article/details/gtorgvfrjb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.fengsongda.top/Article/details/gtcskimagb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hysaishi.cn/Article/details/gtjhtgfpgd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yonumen.top/Article/details/gtdnuavnww.html

[Q42] 连接条件附加过滤
来源：http://dali.dashuyun.cn/Article/details/gtdidoqvjd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gaohongyu789.top/Article/details/gtbvwalbze.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daria6918.cn/Article/details/gtrqyhbqzz.html

[Q43] 标量子查询
来源：http://dali.feifeiyinyue.top/Article/details/gtuafxpuhg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhixingplan.top/Article/details/gtszbrrcxm.html

[Q44] IN 子查询
来源：http://dali.yj202588.top/Article/details/gtfqsbksqc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.c1oappe.top/Article/details/gtozguvuuo.html

[Q45] EXISTS 判断存在
来源：http://dali.zhoulong.xyz/Article/details/gthvflszmt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gtpupqdkry.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yueranfly.top/Article/details/gtwfpsyrjt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gtuthpkyea.html

[Q47] 与平均值比较
来源：http://dali.wangshuangyany.cn/Article/details/gtlslzfmfc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttezpzcrn.html

[Q48] CTE 公用表表达式
来源：http://dali.zhixingplan.top/Article/details/gtjylrnkcr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigufen.top/Article/details/gtmwrqkbhe.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgfzy.top/Article/details/gtcsezcqxl.html

[Q49] 更新单行
来源：http://dali.sxryk.cn/Article/details/gtlhlblpkm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.dianchejie.cn/Article/details/gtzjtgysxi.html

[Q50] 批量更新
来源：http://dali.haohaochexian.top/Article/details/gtfgsewbnp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gtcstplblg.html

[Q51] 用子查询更新
来源：http://dali.haohaochexian.top/Article/details/gtqanxvbte.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xziqi.cn/Article/details/gtqwbjnzot.html

[Q52] 删除指定行
来源：http://dali.vqdsnc.cn/Article/details/gtsoruicbx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gtrkdpfvri.html

[Q53] 按条件删除
来源：http://dali.fengsongda.top/Article/details/gttuckefhi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xinyue.icu/Article/details/gtymqhamsj.html

[Q54] 清空表
来源：http://dali.yj20258.top/Article/details/gthnbqxkeu.html

TRUNCATE TABLE logs;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtytsgzt.html

[Q55] 排名（并列占位）
来源：http://dali.xinyue.icu/Article/details/gtemoagvpk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.0kj1m.cn/Article/details/gtluwqrbpk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenzaomai.com/Article/details/gtjsgcyhin.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yanxiufei.cn/Article/details/gtfnfgvfvq.html

[Q57] 行号
来源：http://dali.jinqigufen.top/Article/details/gtghurkrri.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.smart0.xyz/Article/details/gtvfzckhkf.html

[Q58] 累计求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgqmpfrt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cashguo.top/Article/details/gtzyrrgass.html

[Q59] 分组内累计
来源：http://dali.ppjwa.cn/Article/details/gtyzjnewio.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gttrxqzeua.html

[Q60] 取上一行 / 下一行
来源：http://dali.gzhubu.top/Article/details/gtybripjcf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shanyushiyangtech.top/Article/details/gttgqpfext.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsitlxhxd.html

[Q61] 移动平均
来源：http://dali.shuidangran.top/Article/details/gtryeuiccu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtnhyqmegd.html

[Q62] 分组占比
来源：http://dali.yonumen.top/Article/details/gtuhjbqmgf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtsfqyxcpe.html

[Q63] 开启事务
来源：http://dali.xuetiantiany.cn/Article/details/gtlhpkcxzp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zdqjudy.top/Article/details/gtnadfvzlf.html

[Q64] 提交事务
来源：http://dali.feifeiyinyue.top/Article/details/gtywozjufj.html

COMMIT;
来源：http://dali.shuidangran.top/Article/details/gtnpxiwqzx.html

[Q65] 回滚事务
来源：http://dali.dianchejie.cn/Article/details/gtgsoavika.html

ROLLBACK;
来源：http://dali.c1oappe.top/Article/details/gtpvlqcxgp.html

[Q66] 行锁查询
来源：http://dali.shzxlz.cn/Article/details/gtnhwzdhbk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.pycfn.com/Article/details/gtsudctgpf.html

[Q67] 设置隔离级别
来源：http://dali.jqgufenzy.top/Article/details/gtlzgonbrz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hongshengwenyu.top/Article/details/gtmmzyssjs.html

[Q68] 保存点
来源：http://dali.cheryme.top/Article/details/gtvlbttudg.html

SAVEPOINT sp1;
来源：http://dali.hnxiangtu.top/Article/details/gtyjhxfzch.html

ROLLBACK TO sp1;
来源：http://dali.cdnleiting.top/Article/details/gtymlxylhg.html

[Q69] 查看执行计划
来源：http://dali.yj202588.top/Article/details/gtrzmbmsuj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yanxiufei.cn/Article/details/gtqrvdgill.html

[Q70] 更新统计信息
来源：http://dali.9152youxi.cn/Article/details/gtpkaddqxa.html

ANALYZE TABLE users;
来源：http://dali.daria6918.cn/Article/details/gtjdljrenu.html

[Q71] 查看建表语句
来源：http://dali.yanxiufei.cn/Article/details/gthdetfage.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tanke756.top/Article/details/gtztyrrnri.html

[Q72] 查看索引
来源：http://dali.jqgfzy.top/Article/details/gtfxnkcfws.html

SHOW INDEX FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtuutnjtrw.html

[Q73] 查看表状态
来源：http://dali.yangfankeji.com/Article/details/gtpezdcpnk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258888.top/Article/details/gtlaqjyyxk.html

[Q74] 强制使用索引
来源：http://dali.nwbrower.top/Article/details/gtkcspgisf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cucudq.cn/Article/details/gtvyvytzfv.html

[Q75] 日期格式化
来源：http://dali.fzhhl.top/Article/details/gtldmckdxn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cheryme.top/Article/details/gtvpaoizcf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gotoacloud.top/Article/details/gtmtppmtyp.html

[Q76] 按天统计
来源：http://dali.smart0.xyz/Article/details/gtsjebuqhh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xinyue.icu/Article/details/gtylwtaujp.html

[Q77] 时间加减
来源：http://dali.jyoumei.cn/Article/details/gtfwsxphus.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yongpay.top/Article/details/gttjhdbldg.html

[Q78] 当前时间
来源：http://dali.sysykeji.top/Article/details/gtpklvkmox.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guannengcc.top/Article/details/gtdvnozcps.html

[Q79] 字符串拼接
来源：http://dali.aizwys.cn/Article/details/gtgyifgmky.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xinyue.icu/Article/details/gtzbltsrti.html

[Q80] 字符串截取
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwpmfnbx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtxucjtwdz.html

[Q81] 字符串替换
来源：http://dali.tian-w.cn/Article/details/gtgvorbpgl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jianghu66.top/Article/details/gthwjmpyom.html

[Q82] 字符长度与字节长度
来源：http://dali.aibaodan.cn/Article/details/gtvqfqyihv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtjbrupllk.html

[Q83] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gtjeslnsxf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtczqmgcpj.html

[Q84] 去除首尾空格
来源：http://dali.zdqjudy.top/Article/details/gtwkfierts.html

SELECT TRIM(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtpewsbxgj.html

[Q85] 数值取整
来源：http://dali.yj20258.top/Article/details/gtlzbzebpn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.meibo888.top/Article/details/gtsuqcygex.html

[Q86] 读取 JSON 字段
来源：http://dali.cashguo.top/Article/details/gtxbempxpw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.pycfn.com/Article/details/gtypenngsz.html

[Q87] JSON 字段做条件
来源：http://dali.pycfn.com/Article/details/gtxiuzrpwa.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmpexypk.html

[Q88] 行转列（条件聚合）
来源：http://dali.fengsongda.top/Article/details/gtbdmozwvo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yuxming.cn/Article/details/gtwrgjefqd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.birdmap.top/Article/details/gtnuexvyex.html

[Q89] 判断表是否存在
来源：http://dali.yvedp.cn/Article/details/gtenjvtlzl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zdqjudy.top/Article/details/gtmvsbgrwg.html

[Q90] 生成序号列
来源：http://dali.cashguo.top/Article/details/gtlscwqddg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangdashe.top/Article/details/gtlkpqkuir.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtiouyzuze.html

R. Bash 专题
来源：http://dali.yj20258.top/Article/details/gtldeqygmc.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtmibawmxs.html

[R01] shebang 与严格模式
来源：http://dali.wangdashe.top/Article/details/gtarlmqaca.html

#!/usr/bin/env bash
来源：http://dali.jinqigufen.top/Article/details/gtobyddoeg.html

set -euo pipefail
来源：http://dali.nanxuanxn.top/Article/details/gtswubbdxk.html

[R02] 变量赋值与使用
来源：http://dali.guannengcc.top/Article/details/gtdpkrrgyw.html

name="Tom"; echo "$name"
来源：http://dali.zhongyouzk.top/Article/details/gtqmmcoirc.html

[R03] 只读变量
来源：http://dali.0kj1m.cn/Article/details/gtpwepymzl.html

readonly PI=3.14
来源：http://dali.pengpengdd.cyou/Article/details/gtbrlgxqac.html

[R04] 位置参数
来源：http://dali.mhx1999.top/Article/details/gtbikgrcqd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangdashe.top/Article/details/gtifsvnlmh.html

[R05] 参数默认值
来源：http://dali.shanyushiyangtech.top/Article/details/gtliqvymqd.html

name="${1:-default}"
来源：http://dali.fzhhl.top/Article/details/gtoyvrbxeg.html

[R06] 判断命令是否存在
来源：http://dali.yangfankeji.com/Article/details/gttoiddbsr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gtimbgeatu.html

[R07] if 判断文件
来源：http://dali.nwbrower.top/Article/details/gtitklymyh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ivvv.top/Article/details/gtupguolda.html

[R08] 数值比较
来源：http://dali.jqgufenzy.top/Article/details/gtkssltefh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yuxming.cn/Article/details/gtxtbppxhq.html

[R09] 字符串比较
来源：http://dali.xinyue.icu/Article/details/gtlquayncj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtmozhnzti.html

[R10] 正则匹配
来源：http://dali.sysykeji.top/Article/details/gtgexbgiwe.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yvedp.cn/Article/details/gtnoxuvqhn.html

[R11] case 多分支
来源：http://dali.jinghuilouyu.cn/Article/details/gtdydfleim.html

case "$1" in
来源：http://dali.yj20258.top/Article/details/gtdeycgyyx.html

start) echo "启动" ;;
来源：http://dali.nanxinkj.top/Article/details/gtwoxyhnzj.html

stop)  echo "停止" ;;
来源：http://dali.316326.xyz/Article/details/gtidrsghop.html

*)     echo "未知命令" ;;
来源：http://dali.yuanzhike.top/Article/details/gttnaczois.html

esac
来源：http://dali.sufxvd.cn/Article/details/gtbpqgjcyl.html

[R12] for 遍历文件
来源：http://dali.jiagoushi.top/Article/details/gtubmgegoo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.redwolf501.top/Article/details/gtavauqdun.html

[R13] for 计数循环
来源：http://dali.jqgufenzy.top/Article/details/gtwdwmcggn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gtcrwiznma.html

[R14] C 风格 for
来源：http://dali.tanke756.top/Article/details/gtcokdztyb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gtoesngeer.html

[R15] while 逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqsblmjy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gogol.net.cn/Article/details/gtrcdxyfyg.html

[R16] until 等待条件
来源：http://dali.gogol.net.cn/Article/details/gtddytmvtj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cheryme.top/Article/details/gtuspaqkul.html

[R17] 数组定义与取值
来源：http://dali.mhx1999.top/Article/details/gtoesjcbam.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigufen.top/Article/details/gtqytqjwxk.html

[R18] 遍历数组
来源：http://dali.yongpay.top/Article/details/gtrkzuhdoh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gaohongyu789.top/Article/details/gtolcevjxg.html

[R19] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gtfqhausnd.html

echo "${#arr[@]}"
来源：http://dali.fengsongda.top/Article/details/gtawoyyien.html

[R20] 关联数组（字典）
来源：http://dali.316326.xyz/Article/details/gtcvrwctix.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.316326.xyz/Article/details/gtrhgftycf.html

[R21] 字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gtepcukumz.html

echo "${#s}"
来源：http://dali.yangfankeji.com/Article/details/gtnkkqdooy.html

[R22] 截取子串
来源：http://dali.xuanzx.com/Article/details/gtrfpcxuxx.html

echo "${s:0:5}"
来源：http://dali.ydzc1.top/Article/details/gtbpapdnbt.html

[R23] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gtybcqmqcd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tian-w.cn/Article/details/gttwvwbjux.html

[R24] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gtmmjvpukj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zdqjudy.top/Article/details/gtziblagwm.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinqigfzy.top/Article/details/gtichawzjq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuanzhike.top/Article/details/gtsydxzice.html

[R26] 命令替换
来源：http://dali.feifeiyinyue.top/Article/details/gtpkwtjujb.html

now=$(date +%F); echo "$now"
来源：http://dali.kuanghao11.cn/Article/details/gtnkykxojp.html

[R27] 算术展开
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnaesujta.html

echo $((1 + 2 * 3))
来源：http://dali.jinqigufen.top/Article/details/gtmtxnphrr.html

[R28] 浮点运算
来源：http://dali.gogol.net.cn/Article/details/gtnfggwait.html

echo "scale=2; 10/3" | bc
来源：http://dali.316326.xyz/Article/details/gtyeonxolw.html

[R29] 定义函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmiyuvurr.html


<!-- 参考信息 -->