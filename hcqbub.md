代发 wailian999

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtsnqniupg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.haohaochexian.top/Article/details/gtykbgqcfo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xziqi.cn/Article/details/gtwzragotp.html

Ruby: a == b
来源：http://dali.tanke756.top/Article/details/gtzyhkbdhs.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhoulong.xyz/Article/details/gthnqjdsjy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbyciueh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinqigfzy.top/Article/details/gtccwabrww.html

PHP:  if (empty($x)) {}
来源：http://dali.shzxlz.cn/Article/details/gtqurrthyf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nanxinkj.top/Article/details/gtyttfihfq.html

TS:   if (x == null) {}
来源：http://dali.bjfxy.top/Article/details/gtziassviv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.dianchejie.cn/Article/details/gtxeoqoprq.html

Go:   if x == nil {}
来源：http://dali.zhixingplan.top/Article/details/gtfsaumdpg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.mhx1999.top/Article/details/gtwlubpswq.html

C#:   if (x is null) {}
来源：http://dali.sysykeji.top/Article/details/gtzfmiosiv.html

[P07] 防抖与节流
来源：http://dali.xuanzx.com/Article/details/gtsjxlloiw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.haohaochexian.top/Article/details/gtictvmnyu.html

PHP:  // 手写时间戳比较
来源：http://dali.hywenlv.cn/Article/details/gtnxnyuipf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gtwcxpsmxv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtnnqtrloz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcycxjsfy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jiagoushi.top/Article/details/gtvfumerhx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dashuyun.cn/Article/details/gtvfrxjoaj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sweek.top/Article/details/gtmpvlpfgh.html

[P08] 处理浮点精度问题
来源：http://dali.zdqjudy.top/Article/details/gtdkcnppzj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jyoumei.cn/Article/details/gthewuvcze.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.dianchejie.cn/Article/details/gtczwnxjqz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenlongwang.top/Article/details/gtglcvutzh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.havefunace.top/Article/details/gtxyzrwysa.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yanxiufei.cn/Article/details/gthdchmyud.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhengqikj.top/Article/details/gtwhidwjmr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cqqwz.cn/Article/details/gticvpbcaw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxinkj.top/Article/details/gtkbdifqhl.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtylrllbhi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zdqjudy.top/Article/details/gtnyegmjqm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtftmnshtq.html

[Q01] 创建表
来源：http://dali.cheryme.top/Article/details/gtvmgkimwn.html

CREATE TABLE users (
来源：http://dali.smart0.xyz/Article/details/gtyzigcrih.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dashuyun.cn/Article/details/gtpxxfdimp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj202588.top/Article/details/gtzfejckrl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.aibaodan.cn/Article/details/gtxvtmzpud.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nanxuanxn.top/Article/details/gtctusnvnn.html

);
来源：http://dali.guowangkeji.top/Article/details/gtfgqfjsey.html

[Q02] 创建带外键的表
来源：http://dali.pengpengdd.cyou/Article/details/gtajvolnwl.html

CREATE TABLE orders (
来源：http://dali.jqgufenzy.top/Article/details/gtrhtwixlx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnqzz.top/Article/details/gtghgiigac.html

user_id INT NOT NULL,
来源：http://dali.xinyue.icu/Article/details/gtntchvfkd.html

amount DECIMAL(10, 2),
来源：http://dali.cucudq.cn/Article/details/gtdaukuizj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sysykeji.top/Article/details/gtszdpwgou.html

);
来源：http://dali.zhijiandao.cn/Article/details/gtrwmfmkzg.html

[Q03] 增加列
来源：http://dali.nwbrower.top/Article/details/gtpwoknwyy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.bjfxy.top/Article/details/gtgyfwluxe.html

[Q04] 修改列类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnucmnbup.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jiagoushi.top/Article/details/gtuzehwmvg.html

[Q05] 重命名列
来源：http://dali.nwbrower.top/Article/details/gtflijleip.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hongshengwenyu.top/Article/details/gtluydpsrt.html

[Q06] 删除列
来源：http://dali.dashuyun.cn/Article/details/gtwiqpbjnl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.bjfxy.top/Article/details/gtridoyayx.html

[Q07] 删除表
来源：http://dali.jianghu66.top/Article/details/gtzvpgleyl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sufxvd.cn/Article/details/gtvbfykxkk.html

[Q08] 创建普通索引
来源：http://dali.fengsongda.top/Article/details/gtaqvdmbio.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenjidiqi.icu/Article/details/gtcwarhuwf.html

[Q09] 创建唯一索引
来源：http://dali.birdmap.top/Article/details/gthltcehwd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gtamzocszq.html

[Q10] 插入单行
来源：http://dali.gaohongyu789.top/Article/details/gtakjallyh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gtjcqarfxn.html

[Q11] 一次插入多行
来源：http://dali.hnxiangtu.top/Article/details/gtsnhbfhxj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenzaomai.com/Article/details/gtbbbfihxw.html

[Q12] 插入后取自增 ID
来源：http://dali.pengpengdd.cyou/Article/details/gtlbuvisnb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.c1oappe.top/Article/details/gtglbrogtr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.redwolf501.top/Article/details/gtunasiezb.html

[Q13] 忽略重复插入
来源：http://dali.chenlongwang.top/Article/details/gtehwsgrea.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.c1oappe.top/Article/details/gtcmtkdjoq.html

[Q14] 存在则更新（upsert）
来源：http://dali.daxiang520.top/Article/details/gtjmsqhocp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.daria6918.cn/Article/details/gtegbqdbfq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.iojbl.cn/Article/details/gthabalryu.html

[Q15] 查询全部
来源：http://dali.smart0.xyz/Article/details/gtokmvizre.html

SELECT * FROM users;
来源：http://dali.ydzc1.top/Article/details/gtgwetmyqr.html

[Q16] 查询指定列
来源：http://dali.cashguo.top/Article/details/gtftajpzla.html

SELECT id, name FROM users;
来源：http://dali.jqgfzy.top/Article/details/gttdwfnsgc.html

[Q17] 条件查询
来源：http://dali.gogol.net.cn/Article/details/gtuseddamz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhixingplan.top/Article/details/gtycwxdbyo.html

[Q18] 模糊匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtyhiueegt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.mhx1999.top/Article/details/gtbzdskddf.html

[Q19] 范围查询
来源：http://dali.nanxuanxn.top/Article/details/gtxuggrdqf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pengpengdd.cyou/Article/details/gtrtkrwnhx.html

[Q20] IN 列表
来源：http://dali.yueranfly.top/Article/details/gtnrfobzfd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ivvv.top/Article/details/gtzkfnarre.html

[Q21] 空值判断
来源：http://dali.gzhubu.top/Article/details/gtoxcrxjev.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shangyingyoupin.top/Article/details/gtkitfzrzm.html

[Q22] 排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnbgiame.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.aizwys.cn/Article/details/gtdhbtpqrd.html

[Q23] 分页
来源：http://dali.hnxiangtu.top/Article/details/gtahmlhlvy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.aibaodan.cn/Article/details/gtitkolrta.html

[Q24] 去重
来源：http://dali.snrcjt.cn/Article/details/gtimorptkr.html

SELECT DISTINCT city FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtueszmmug.html

[Q25] 只取前 N 条
来源：http://dali.jqgufenzy.top/Article/details/gttmjauuce.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinqigfzy.top/Article/details/gtegakqgxx.html

[Q26] 计数
来源：http://dali.wangshuangyany.cn/Article/details/gtmobjjjrl.html

SELECT COUNT(*) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtdomhffdv.html

[Q27] 条件计数
来源：http://dali.jyoumei.cn/Article/details/gtazecczzs.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gteckbqdcr.html

[Q28] 求和与平均
来源：http://dali.snrcjt.cn/Article/details/gtphecvamt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtnufjtaov.html

[Q29] 最大最小值
来源：http://dali.vqdsnc.cn/Article/details/gtyofrtgto.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtxwecdmud.html

[Q30] 分组统计
来源：http://dali.chenlongwang.top/Article/details/gtkfliytbn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtftegxxrw.html

[Q31] 分组后过滤
来源：http://dali.quarkkingdee.top/Article/details/gtgpvmdrca.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlwsrctzn.html

[Q32] 分组拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gtldusrxtp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gtgohhkuhx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nanxinkj.top/Article/details/gtahaalrfv.html

[Q33] 多列分组
来源：http://dali.hysaishi.cn/Article/details/gtuzragjhy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.andypj.xyz/Article/details/gtozfxnpfb.html

[Q34] 每组取第一条
来源：http://dali.tianlin.xyz/Article/details/gtscjphwsl.html

SELECT * FROM (
来源：http://dali.sweek.top/Article/details/gtqdjujfoq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fzhhl.top/Article/details/gtpbsqigut.html

) t WHERE rn = 1;
来源：http://dali.gzhubu.top/Article/details/gtzbmdhtbo.html

[Q35] 内连接
来源：http://dali.hysaishi.cn/Article/details/gthfulpjun.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.vqdsnc.cn/Article/details/gtvyyknfaq.html

[Q36] 左连接
来源：http://dali.shuidangran.top/Article/details/gtnrzqgnkm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gthxcqpqxl.html

[Q37] 右连接
来源：http://dali.zhoulong.xyz/Article/details/gttworbjuz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.svipenyu.cn/Article/details/gtamzopwna.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinqigfzy.top/Article/details/gtctktqbds.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yanxiufei.cn/Article/details/gtulnhjgnz.html

[Q39] 自连接（查上下级）
来源：http://dali.yangfankeji.com/Article/details/gtbfbihham.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.9152youxi.cn/Article/details/gtrfhtelgg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.svipenyu.cn/Article/details/gtxsqwnmhg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.snrcjt.cn/Article/details/gtvsyuzyvr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.meibo888.top/Article/details/gtutkvbrfv.html

[Q41] 多表连接
来源：http://dali.iojbl.cn/Article/details/gtflmkzbnc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daxiang520.top/Article/details/gtqjbftdgc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yueranfly.top/Article/details/gtxnrcbjgn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gtbfyjdmta.html

[Q42] 连接条件附加过滤
来源：http://dali.ivvv.top/Article/details/gtcemzjgcc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.iojbl.cn/Article/details/gtbqxrtbdk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xinyue.icu/Article/details/gttjqkyfoo.html

[Q43] 标量子查询
来源：http://dali.c1oappe.top/Article/details/gtbuhdqzrq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yvedp.cn/Article/details/gttxnnieqh.html

[Q44] IN 子查询
来源：http://dali.chenlongwang.top/Article/details/gtbaquvgvj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xinyue.icu/Article/details/gthhrpwsbx.html

[Q45] EXISTS 判断存在
来源：http://dali.sufxvd.cn/Article/details/gtcxgrcofi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gtizeagfth.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tanke756.top/Article/details/gtnyrzmfat.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cdnleiting.top/Article/details/gtcyhnduxd.html

[Q47] 与平均值比较
来源：http://dali.hfpthk.cn/Article/details/gtvkgwuznn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.bjfxy.top/Article/details/gtjcvlfcym.html

[Q48] CTE 公用表表达式
来源：http://dali.c1oappe.top/Article/details/gtgobkqpsl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuflitseq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.meibo888.top/Article/details/gtnbulrbwh.html

[Q49] 更新单行
来源：http://dali.chenlongwang.top/Article/details/gtrvgdomkx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.guannengcc.top/Article/details/gtypdirpua.html

[Q50] 批量更新
来源：http://dali.nanxuanxn.top/Article/details/gtydipurdw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenlongwang.top/Article/details/gtfcdtoirn.html

[Q51] 用子查询更新
来源：http://dali.pycfn.com/Article/details/gtrxvkrprp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.iojbl.cn/Article/details/gtgffiriod.html

[Q52] 删除指定行
来源：http://dali.zhoulong.xyz/Article/details/gtllkeensc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhixingplan.top/Article/details/gtgxayvrsl.html

[Q53] 按条件删除
来源：http://dali.xuanzx.com/Article/details/gtqgxwbbgk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dashuyun.cn/Article/details/gtakryjdvp.html

[Q54] 清空表
来源：http://dali.haohaochexian.top/Article/details/gtlklfvlre.html

TRUNCATE TABLE logs;
来源：http://dali.ppjwa.cn/Article/details/gtqjbxkehz.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258888.top/Article/details/gtsrustkhv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gtzstntlzw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gtarytgrqz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcaymcnxw.html

[Q57] 行号
来源：http://dali.yj20258888.top/Article/details/gtfsqoyqvy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwcaofzls.html

[Q58] 累计求和
来源：http://dali.bjfxy.top/Article/details/gtfvbzwfgb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gttnubtkww.html

[Q59] 分组内累计
来源：http://dali.xuanzx.com/Article/details/gthugcmqzs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtoognlamm.html

[Q60] 取上一行 / 下一行
来源：http://dali.jiagoushi.top/Article/details/gtfkjlsrvi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cheryme.top/Article/details/gtffnizivl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gthobreccw.html

[Q61] 移动平均
来源：http://dali.yuanzhike.top/Article/details/gtqtluqsiu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtgecystru.html

[Q62] 分组占比
来源：http://dali.jinqigfzy.top/Article/details/gtiqbmtntx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gtiqsgjqkl.html

[Q63] 开启事务
来源：http://dali.mhx1999.top/Article/details/gtkowbiudw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuetiantiany.cn/Article/details/gtxmdrssjm.html

[Q64] 提交事务
来源：http://dali.xylfe.cn/Article/details/gtplkyzgil.html

COMMIT;
来源：http://dali.hammf.cn/Article/details/gtqhwajzbw.html

[Q65] 回滚事务
来源：http://dali.meibo888.top/Article/details/gtmowgweru.html

ROLLBACK;
来源：http://dali.dianchejie.cn/Article/details/gtvgyqgivo.html

[Q66] 行锁查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtkplynwnd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhoulong.xyz/Article/details/gtjmtjvfmo.html

[Q67] 设置隔离级别
来源：http://dali.gogol.net.cn/Article/details/gtedqewhkq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gogol.net.cn/Article/details/gtbpppkjde.html

[Q68] 保存点
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdyvlmox.html

SAVEPOINT sp1;
来源：http://dali.0kj1m.cn/Article/details/gtpuxhmiua.html

ROLLBACK TO sp1;
来源：http://dali.havefunace.top/Article/details/gtrotigwpm.html

[Q69] 查看执行计划
来源：http://dali.feifeiyinyue.top/Article/details/gtalabbong.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gogol.net.cn/Article/details/gthdodxlwy.html

[Q70] 更新统计信息
来源：http://dali.jqgfzy.top/Article/details/gtqdfddnta.html

ANALYZE TABLE users;
来源：http://dali.316326.xyz/Article/details/gtgxjrpmbq.html

[Q71] 查看建表语句
来源：http://dali.cashguo.top/Article/details/gtguksgjdq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhongyouzk.top/Article/details/gtwllrsfbp.html

[Q72] 查看索引
来源：http://dali.yj20258.top/Article/details/gtxgvruawg.html

SHOW INDEX FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtkvedmozw.html

[Q73] 查看表状态
来源：http://dali.bjfxy.top/Article/details/gtgxdqoulb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gogol.net.cn/Article/details/gtymhqnsiy.html

[Q74] 强制使用索引
来源：http://dali.shuidangran.top/Article/details/gtrhltqhpc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cucudq.cn/Article/details/gtlhehmevz.html

[Q75] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtbrfweatp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtgvleeqic.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj20258.top/Article/details/gtiqffactv.html

[Q76] 按天统计
来源：http://dali.gaohongyu789.top/Article/details/gtsirsyiex.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.svipenyu.cn/Article/details/gtwwlvqlnx.html

[Q77] 时间加减
来源：http://dali.nanxuanxn.top/Article/details/gtbdvktcii.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzpzufzb.html

[Q78] 当前时间
来源：http://dali.vqdsnc.cn/Article/details/gtfejjywdn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xziqi.cn/Article/details/gtimficvhy.html

[Q79] 字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gttcncoehn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sysykeji.top/Article/details/gtcyqamtrb.html

[Q80] 字符串截取
来源：http://dali.feifeiyinyue.top/Article/details/gtlonnrick.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtrburjvfy.html

[Q81] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gtabsmeqjy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtmgztmirv.html

[Q82] 字符长度与字节长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdtawmak.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtaupcldkh.html

[Q83] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gtduaeyxve.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtklytijuy.html

[Q84] 去除首尾空格
来源：http://dali.zhoulong.xyz/Article/details/gtbjuwifpz.html

SELECT TRIM(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtfldiplqi.html

[Q85] 数值取整
来源：http://dali.fengsongda.top/Article/details/gtimyasnbz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sufxvd.cn/Article/details/gtziabouyn.html

[Q86] 读取 JSON 字段
来源：http://dali.ybcxt.top/Article/details/gthousjgkb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yongpay.top/Article/details/gtnrunckis.html

[Q87] JSON 字段做条件
来源：http://dali.ivvv.top/Article/details/gtzxnblzvh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ydzc1.top/Article/details/gtgiqjitrz.html

[Q88] 行转列（条件聚合）
来源：http://dali.yonumen.top/Article/details/gtexjzlliu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pengpengdd.cyou/Article/details/gtjqinnowr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.mhx1999.top/Article/details/gtydwaqkvp.html

[Q89] 判断表是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gtcrvlgzfk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.haohaochexian.top/Article/details/gtwmloyfqc.html

[Q90] 生成序号列
来源：http://dali.sxryk.cn/Article/details/gtbyrnaemp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.meibo888.top/Article/details/gtvhyffjlm.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtzpjqktws.html

R. Bash 专题
来源：http://dali.hfpthk.cn/Article/details/gtsdhdrtbi.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohocmhlz.html

[R01] shebang 与严格模式
来源：http://dali.aibaodan.cn/Article/details/gtdxgssixg.html

#!/usr/bin/env bash
来源：http://dali.cucudq.cn/Article/details/gtajnbqgqr.html

set -euo pipefail
来源：http://dali.andypj.xyz/Article/details/gtrmumpkmy.html

[R02] 变量赋值与使用
来源：http://dali.ppjwa.cn/Article/details/gtynybhiiv.html

name="Tom"; echo "$name"
来源：http://dali.daxiang520.top/Article/details/gtnuxberah.html

[R03] 只读变量
来源：http://dali.tanke756.top/Article/details/gtlmzwpeed.html

readonly PI=3.14
来源：http://dali.bjfxy.top/Article/details/gtiaoawren.html

[R04] 位置参数
来源：http://dali.bjfxy.top/Article/details/gtmubduefg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sufxvd.cn/Article/details/gtaphxtixz.html

[R05] 参数默认值
来源：http://dali.feifeiyinyue.top/Article/details/gtricleygb.html

name="${1:-default}"
来源：http://dali.xziqi.cn/Article/details/gtiddcrwwp.html

[R06] 判断命令是否存在
来源：http://dali.chenzaomai.com/Article/details/gtueojrbdp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.snrcjt.cn/Article/details/gtuqmpebwc.html

[R07] if 判断文件
来源：http://dali.chenjidiqi.icu/Article/details/gtfbbwvvts.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.meibo888.top/Article/details/gtlpocukje.html

[R08] 数值比较
来源：http://dali.ivvv.top/Article/details/gtiokydsdh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.c1oappe.top/Article/details/gtofnomuoy.html

[R09] 字符串比较
来源：http://dali.tanke756.top/Article/details/gtdcosuvpg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtdijhwrno.html

[R10] 正则匹配
来源：http://dali.c1oappe.top/Article/details/gtzempdtjn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jyoumei.cn/Article/details/gtfwbcafeq.html

[R11] case 多分支
来源：http://dali.jiagoushi.top/Article/details/gtpztwxpnq.html

case "$1" in
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfuqithpd.html

start) echo "启动" ;;
来源：http://dali.xuanzx.com/Article/details/gtqnypqwfz.html

stop)  echo "停止" ;;
来源：http://dali.yj20258.top/Article/details/gtoscmwobe.html

*)     echo "未知命令" ;;
来源：http://dali.aizwys.cn/Article/details/gtbgceabcf.html

esac
来源：http://dali.yj202588.top/Article/details/gtlxsxwdzr.html

[R12] for 遍历文件
来源：http://dali.ehwqpu.com/Article/details/gtqrtzwlka.html

for f in *.txt; do echo "$f"; done
来源：http://dali.bjfxy.top/Article/details/gtdtvowdvt.html

[R13] for 计数循环
来源：http://dali.cucudq.cn/Article/details/gtnnhaggee.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.snrcjt.cn/Article/details/gtmsrzhsak.html

[R14] C 风格 for
来源：http://dali.316326.xyz/Article/details/gtmmbmrvll.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.pycfn.com/Article/details/gtnziamawu.html

[R15] while 逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtuchiukhd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fzhhl.top/Article/details/gtgnyjspwf.html

[R16] until 等待条件
来源：http://dali.cdnleiting.top/Article/details/gttxiqrpec.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nwbrower.top/Article/details/gtvplqptnl.html

[R17] 数组定义与取值
来源：http://dali.shuidangran.top/Article/details/gtzjlnenys.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.9152youxi.cn/Article/details/gtijwdnqqo.html

[R18] 遍历数组
来源：http://dali.ivvv.top/Article/details/gtjaeycxsz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtdilajeyu.html

[R19] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gtvjjylulh.html

echo "${#arr[@]}"
来源：http://dali.bjfxy.top/Article/details/gttjnnspxr.html

[R20] 关联数组（字典）
来源：http://dali.jiagoushi.top/Article/details/gtslgjtexr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ydzc1.top/Article/details/gtlypgxxlp.html

[R21] 字符串长度
来源：http://dali.9152youxi.cn/Article/details/gtueuzhfip.html

echo "${#s}"
来源：http://dali.9152youxi.cn/Article/details/gtsepgiewd.html

[R22] 截取子串
来源：http://dali.daria6918.cn/Article/details/gteeliyroa.html

echo "${s:0:5}"
来源：http://dali.0kj1m.cn/Article/details/gtczipszoa.html

[R23] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtisijeikw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tian-w.cn/Article/details/gtcnlrhoaj.html

[R24] 大小写转换
来源：http://dali.yj20258.top/Article/details/gtnzatkhqq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hnxiangtu.top/Article/details/gtnxflqkvl.html

[R25] 去后缀 / 去前缀
来源：http://dali.jyoumei.cn/Article/details/gtkywjveup.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jlsjyb.cn/Article/details/gtisruxlnt.html

[R26] 命令替换
来源：http://dali.c1oappe.top/Article/details/gtndeubgjo.html

now=$(date +%F); echo "$now"
来源：http://dali.shzxlz.cn/Article/details/gtrefjlzho.html

[R27] 算术展开
来源：http://dali.zycfv.cn/Article/details/gtrhamxvmb.html


<!-- 参考信息 -->