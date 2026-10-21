代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhiwuduotai.top/Article/details/gtiajmpcyg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tianlin.xyz/Article/details/gtoxyokmzt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.kuanghao11.cn/Article/details/gtbmgqsuiu.html

PHP:  if (empty($x)) {}
来源：http://dali.hnqzz.top/Article/details/gttvbweqfq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.pengpengdd.cyou/Article/details/gtwqgilncq.html

TS:   if (x == null) {}
来源：http://dali.jinqigfzy.top/Article/details/gtkwtzugyq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gtmmpflccc.html

Go:   if x == nil {}
来源：http://dali.jianghu66.top/Article/details/gtsvmhsbqf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.0kj1m.cn/Article/details/gtuunrnolt.html

C#:   if (x is null) {}
来源：http://dali.snrcjt.cn/Article/details/gtorbkdznh.html

[P07] 防抖与节流
来源：http://dali.yanxiufei.cn/Article/details/gtxetcmbvk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cheryme.top/Article/details/gtlzoomjam.html

PHP:  // 手写时间戳比较
来源：http://dali.jinqigfzy.top/Article/details/gtasaiqpnz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtzpcjswir.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gtqfvdlwof.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.iojbl.cn/Article/details/gtotnnswlb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jiagoushi.top/Article/details/gtwzglfpaf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenjidiqi.icu/Article/details/gtlhhmvqcr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxrbrjbn.html

[P08] 处理浮点精度问题
来源：http://dali.jqgfzy.top/Article/details/gtuuetruym.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.0kj1m.cn/Article/details/gtbymxksww.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenzaomai.com/Article/details/gtnnplewbn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hfpthk.cn/Article/details/gtqourzctz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.316326.xyz/Article/details/gtbsqoxbfr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gzhubu.top/Article/details/gtuofyzcja.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhiwuduotai.top/Article/details/gtcxfcluob.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cucudq.cn/Article/details/gtjuczompz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guowangkeji.top/Article/details/gtlfuyyytr.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtknswacik.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xuanzx.com/Article/details/gtohuqpglx.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtbsinclov.html

[Q01] 创建表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqyyzbfc.html

CREATE TABLE users (
来源：http://dali.zhengqikj.top/Article/details/gtgkrsbqeh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tian-w.cn/Article/details/gtfiaeyzih.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jyoumei.cn/Article/details/gtrwamtbfm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ydzc1.top/Article/details/gtkahtsgns.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shzxlz.cn/Article/details/gtbqynygaa.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gtmfzjlzay.html

[Q02] 创建带外键的表
来源：http://dali.mhx1999.top/Article/details/gtgzdnkrgj.html

CREATE TABLE orders (
来源：http://dali.nanxinkj.top/Article/details/gtkpmoinag.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hammf.cn/Article/details/gtwzvvyxgd.html

user_id INT NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gtxeaavlxu.html

amount DECIMAL(10, 2),
来源：http://dali.quarkkingdee.top/Article/details/gtosbzmbju.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.bjfxy.top/Article/details/gtjttppmsd.html

);
来源：http://dali.yangfankeji.com/Article/details/gteormjtte.html

[Q03] 增加列
来源：http://dali.dashuyun.cn/Article/details/gtoogmlydc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhengqikj.top/Article/details/gtdpoukkvu.html

[Q04] 修改列类型
来源：http://dali.chenzaomai.com/Article/details/gtdymwepjc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gtwuhykohx.html

[Q05] 重命名列
来源：http://dali.shzxlz.cn/Article/details/gtvwrblumf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.fengsongda.top/Article/details/gtcpdcqagf.html

[Q06] 删除列
来源：http://dali.meibo888.top/Article/details/gtwgglxkzv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvvurzlq.html

[Q07] 删除表
来源：http://dali.jinqigufen.top/Article/details/gtiaacpyoy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbrctpsm.html

[Q08] 创建普通索引
来源：http://dali.gotoacloud.top/Article/details/gtewgpabzy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.quarkkingdee.top/Article/details/gtazywgvvp.html

[Q09] 创建唯一索引
来源：http://dali.c1oappe.top/Article/details/gtucoihzjk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sweek.top/Article/details/gthonfmtrq.html

[Q10] 插入单行
来源：http://dali.sysykeji.top/Article/details/gtomzfmjoa.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hywenlv.cn/Article/details/gtsqmqukae.html

[Q11] 一次插入多行
来源：http://dali.yuxming.cn/Article/details/gtdcflmupz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yonumen.top/Article/details/gtesmqmois.html

[Q12] 插入后取自增 ID
来源：http://dali.yonumen.top/Article/details/gtybaaaawo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hysaishi.cn/Article/details/gthnuhhhrt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hnqzz.top/Article/details/gtpvhyyerh.html

[Q13] 忽略重复插入
来源：http://dali.cashguo.top/Article/details/gtlgvsbcbb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.aibaodan.cn/Article/details/gteyfukmke.html

[Q14] 存在则更新（upsert）
来源：http://dali.yanxiufei.cn/Article/details/gtqnpnouvt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gzhubu.top/Article/details/gtykocxavc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.smart0.xyz/Article/details/gtzmldbydl.html

[Q15] 查询全部
来源：http://dali.ydzc1.top/Article/details/gtirhsdkrx.html

SELECT * FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtksixhaic.html

[Q16] 查询指定列
来源：http://dali.nanxinkj.top/Article/details/gtsngwmohd.html

SELECT id, name FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtlcsiypkq.html

[Q17] 条件查询
来源：http://dali.birdmap.top/Article/details/gtkoodjjvn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daria6918.cn/Article/details/gtiyihmnbo.html

[Q18] 模糊匹配
来源：http://dali.zhengqikj.top/Article/details/gtevoxjjvm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fzhhl.top/Article/details/gtsgtigjsk.html

[Q19] 范围查询
来源：http://dali.ppjwa.cn/Article/details/gtfftwtqli.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.vqdsnc.cn/Article/details/gtbvrjhtzs.html

[Q20] IN 列表
来源：http://dali.shuidangran.top/Article/details/gtgbpzceat.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jyoumei.cn/Article/details/gtptdsisbm.html

[Q21] 空值判断
来源：http://dali.nwbrower.top/Article/details/gtdzdezgvw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhoulong.xyz/Article/details/gttnfcinit.html

[Q22] 排序
来源：http://dali.xuetiantiany.cn/Article/details/gtvekoavjt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tianlin.xyz/Article/details/gtrmjuwqkh.html

[Q23] 分页
来源：http://dali.gaohongyu789.top/Article/details/gtfqrbztcn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenzaomai.com/Article/details/gtcjgxmjls.html

[Q24] 去重
来源：http://dali.jqgufenzy.top/Article/details/gtzhcasfmj.html

SELECT DISTINCT city FROM users;
来源：http://dali.cucudq.cn/Article/details/gtpotygmzh.html

[Q25] 只取前 N 条
来源：http://dali.jinghuilouyu.cn/Article/details/gteuibcbkx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhixingplan.top/Article/details/gtyilucsuc.html

[Q26] 计数
来源：http://dali.zhongyouzk.top/Article/details/gtfncxetad.html

SELECT COUNT(*) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtxfhjbywl.html

[Q27] 条件计数
来源：http://dali.cqqwz.cn/Article/details/gtclkxcioh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yueranfly.top/Article/details/gtbcnpifaf.html

[Q28] 求和与平均
来源：http://dali.zhiwuduotai.top/Article/details/gtdkfugdxt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sweek.top/Article/details/gttsuzslzs.html

[Q29] 最大最小值
来源：http://dali.svipenyu.cn/Article/details/gtkvofhyrd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtqtwhzakb.html

[Q30] 分组统计
来源：http://dali.gzhubu.top/Article/details/gtunksvvln.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gtvwbrjdbg.html

[Q31] 分组后过滤
来源：http://dali.yvedp.cn/Article/details/gtcghtyhbp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkuanyfxm.html

[Q32] 分组拼接字符串
来源：http://dali.tanke756.top/Article/details/gtgrxixrty.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gtpscoghjn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yueranfly.top/Article/details/gtzvidmnos.html

[Q33] 多列分组
来源：http://dali.hywenlv.cn/Article/details/gtetkmzwyh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhongyouzk.top/Article/details/gtgdmidseq.html

[Q34] 每组取第一条
来源：http://dali.snrcjt.cn/Article/details/gtdheardsw.html

SELECT * FROM (
来源：http://dali.ivvv.top/Article/details/gtgylvsuel.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nwbrower.top/Article/details/gtvrhytjko.html

) t WHERE rn = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtikvybimp.html

[Q35] 内连接
来源：http://dali.jianghu66.top/Article/details/gtanocnytx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gtdvoofkyb.html

[Q36] 左连接
来源：http://dali.daria6918.cn/Article/details/gtthrvgvkh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gtoczxegou.html

[Q37] 右连接
来源：http://dali.vqdsnc.cn/Article/details/gtmpggrifb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.bjfxy.top/Article/details/gtemhhfxht.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yangfankeji.com/Article/details/gtflokywdb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shangyingyoupin.top/Article/details/gtzsqajlxd.html

[Q39] 自连接（查上下级）
来源：http://dali.havefunace.top/Article/details/gtoczbtkdl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gzhubu.top/Article/details/gtxzhlufef.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhixingplan.top/Article/details/gtfugdhjxq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.daxiang520.top/Article/details/gtoberadev.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.meibo888.top/Article/details/gthwbxirsi.html

[Q41] 多表连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuyznkznk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenjidiqi.icu/Article/details/gtimajucix.html

JOIN users u ON u.id = o.user_id
来源：http://dali.aizwys.cn/Article/details/gtvjqullap.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daxiang520.top/Article/details/gtwavpyykc.html

[Q42] 连接条件附加过滤
来源：http://dali.yongpay.top/Article/details/gtweeamskp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.svipenyu.cn/Article/details/gtforonbjw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xinyue.icu/Article/details/gtjupykvoc.html

[Q43] 标量子查询
来源：http://dali.wangshuangyany.cn/Article/details/gtjhflfeyz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yueranfly.top/Article/details/gtsoqrtasl.html

[Q44] IN 子查询
来源：http://dali.gzhubu.top/Article/details/gtfffifviq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hammf.cn/Article/details/gteaiisvht.html

[Q45] EXISTS 判断存在
来源：http://dali.iojbl.cn/Article/details/gtsqndvtrm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.iojbl.cn/Article/details/gtmdvktxrb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gzhubu.top/Article/details/gtqfhfvwep.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yanxiufei.cn/Article/details/gtrvjrbylg.html

[Q47] 与平均值比较
来源：http://dali.gzhubu.top/Article/details/gtpawqxhzr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gaohongyu789.top/Article/details/gthagtbfoq.html

[Q48] CTE 公用表表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwajtvds.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.birdmap.top/Article/details/gtrqjopscj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gtbifldihc.html

[Q49] 更新单行
来源：http://dali.smart0.xyz/Article/details/gtstrzbika.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.meibo888.top/Article/details/gtalcrsuoz.html

[Q50] 批量更新
来源：http://dali.andypj.xyz/Article/details/gtozdpmzsr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.0kj1m.cn/Article/details/gtftgkapxn.html

[Q51] 用子查询更新
来源：http://dali.redwolf501.top/Article/details/gtqaconwft.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hywenlv.cn/Article/details/gtmgzqbrae.html

[Q52] 删除指定行
来源：http://dali.fengsongda.top/Article/details/gtrlogfavg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258.top/Article/details/gtcoyffrtp.html

[Q53] 按条件删除
来源：http://dali.cucudq.cn/Article/details/gtkubqqlpw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hnxiangtu.top/Article/details/gtbdyoblle.html

[Q54] 清空表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrcmwhagt.html

TRUNCATE TABLE logs;
来源：http://dali.cdnleiting.top/Article/details/gtbnjtxapn.html

[Q55] 排名（并列占位）
来源：http://dali.yangfankeji.com/Article/details/gtvsydrdgp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgufenzy.top/Article/details/gtgjaabuej.html

[Q56] 密集排名（并列不占位）
来源：http://dali.birdmap.top/Article/details/gtkvyysfee.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guannengcc.top/Article/details/gtkbbyuxua.html

[Q57] 行号
来源：http://dali.cqqwz.cn/Article/details/gtkrhundqp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xylfe.cn/Article/details/gtvajdipic.html

[Q58] 累计求和
来源：http://dali.zhixingplan.top/Article/details/gttdlvlapx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtqiabbepk.html

[Q59] 分组内累计
来源：http://dali.ivvv.top/Article/details/gthcsuwwbv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtmbpetybu.html

[Q60] 取上一行 / 下一行
来源：http://dali.ydzc1.top/Article/details/gtahjierhv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cashguo.top/Article/details/gtfqswvatz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtowkyevev.html

[Q61] 移动平均
来源：http://dali.shzxlz.cn/Article/details/gttmweumgz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtakxkpmos.html

[Q62] 分组占比
来源：http://dali.yj20258888.top/Article/details/gtzqowvken.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gtiwoiyzfd.html

[Q63] 开启事务
来源：http://dali.gotoacloud.top/Article/details/gtjusrejtc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.dashuyun.cn/Article/details/gtknrlkhlm.html

[Q64] 提交事务
来源：http://dali.yanxiufei.cn/Article/details/gtqogwzvem.html

COMMIT;
来源：http://dali.wangdashe.top/Article/details/gtqhclanlp.html

[Q65] 回滚事务
来源：http://dali.sysykeji.top/Article/details/gtuuoxecsa.html

ROLLBACK;
来源：http://dali.aibaodan.cn/Article/details/gtnkltfrdm.html

[Q66] 行锁查询
来源：http://dali.c1oappe.top/Article/details/gtekyexops.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ppjwa.cn/Article/details/gtxtxrapnc.html

[Q67] 设置隔离级别
来源：http://dali.cucudq.cn/Article/details/gthbehzyvl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daxiang520.top/Article/details/gtxkmvonoc.html

[Q68] 保存点
来源：http://dali.yuanzhike.top/Article/details/gtubnurdjh.html

SAVEPOINT sp1;
来源：http://dali.nanxuanxn.top/Article/details/gtuheeodrx.html

ROLLBACK TO sp1;
来源：http://dali.gzhubu.top/Article/details/gtcacikmbc.html

[Q69] 查看执行计划
来源：http://dali.cqqwz.cn/Article/details/gtbtjlixon.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.andypj.xyz/Article/details/gtrxiqswxr.html

[Q70] 更新统计信息
来源：http://dali.fzhhl.top/Article/details/gtivmmmftn.html

ANALYZE TABLE users;
来源：http://dali.sweek.top/Article/details/gtozsbfqky.html

[Q71] 查看建表语句
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvfxpzvd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.meibo888.top/Article/details/gtvozpyxhm.html

[Q72] 查看索引
来源：http://dali.jinqigfzy.top/Article/details/gtnjlozsmp.html

SHOW INDEX FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtxqlizxnp.html

[Q73] 查看表状态
来源：http://dali.sufxvd.cn/Article/details/gtkwzgpwif.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.smart0.xyz/Article/details/gttgcegsja.html

[Q74] 强制使用索引
来源：http://dali.xylfe.cn/Article/details/gtzpcgwqfc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj20258.top/Article/details/gttyaourly.html

[Q75] 日期格式化
来源：http://dali.xziqi.cn/Article/details/gtfhetlyjr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtiqnsxibd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aibaodan.cn/Article/details/gtfiqgfyjo.html

[Q76] 按天统计
来源：http://dali.kuanghao11.cn/Article/details/gtbrkiqlbg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xinyue.icu/Article/details/gthogbbkdd.html

[Q77] 时间加减
来源：http://dali.chenzaomai.com/Article/details/gtgxbcepgm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxacaiydk.html

[Q78] 当前时间
来源：http://dali.gaohongyu789.top/Article/details/gtdlxgocka.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.vqdsnc.cn/Article/details/gtbzkhkjcz.html

[Q79] 字符串拼接
来源：http://dali.xuanzx.com/Article/details/gtbpmvhyyf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yongpay.top/Article/details/gthbqsbtcb.html

[Q80] 字符串截取
来源：http://dali.cdnleiting.top/Article/details/gtosiyaait.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtdtvxabqp.html

[Q81] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gtmmdzgmnt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtmepwujvy.html

[Q82] 字符长度与字节长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlzykdog.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtlxhhivjq.html

[Q83] 大小写转换
来源：http://dali.havefunace.top/Article/details/gteqtbiybf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtlbtlloet.html

[Q84] 去除首尾空格
来源：http://dali.bjfxy.top/Article/details/gtoayqqnwm.html

SELECT TRIM(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtrmtixnuc.html

[Q85] 数值取整
来源：http://dali.yuxming.cn/Article/details/gtcrmeolsq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.kuanghao11.cn/Article/details/gtdobiuoui.html

[Q86] 读取 JSON 字段
来源：http://dali.wangdashe.top/Article/details/gtapcalnth.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aibaodan.cn/Article/details/gtwanqnahj.html

[Q87] JSON 字段做条件
来源：http://dali.yongpay.top/Article/details/gtzmtruywq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gotoacloud.top/Article/details/gtmzttobat.html

[Q88] 行转列（条件聚合）
来源：http://dali.zycfv.cn/Article/details/gtrsjgsvet.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nanxuanxn.top/Article/details/gtvortswye.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yvedp.cn/Article/details/gtynvkmppe.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gtpixlhiyb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.svipenyu.cn/Article/details/gtcpnltbeh.html

[Q90] 生成序号列
来源：http://dali.iojbl.cn/Article/details/gtvjafckqv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shuidangran.top/Article/details/gtmaejlchm.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtqnitfxgh.html

R. Bash 专题
来源：http://dali.xinyue.icu/Article/details/gtxzabvkqx.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtmllpbmde.html

[R01] shebang 与严格模式
来源：http://dali.jiagoushi.top/Article/details/gtvsvsmpmy.html

#!/usr/bin/env bash
来源：http://dali.c1oappe.top/Article/details/gtyzomwntp.html

set -euo pipefail
来源：http://dali.hammf.cn/Article/details/gtazqiiwwf.html

[R02] 变量赋值与使用
来源：http://dali.aibaodan.cn/Article/details/gtwnfcfmmm.html

name="Tom"; echo "$name"
来源：http://dali.gogol.net.cn/Article/details/gtfsxeqcjn.html

[R03] 只读变量
来源：http://dali.kuanghao11.cn/Article/details/gtlewxuxyb.html

readonly PI=3.14
来源：http://dali.sufxvd.cn/Article/details/gtcvnkmjjv.html

[R04] 位置参数
来源：http://dali.aibaodan.cn/Article/details/gtqgcmycqj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhiwuduotai.top/Article/details/gterfppwla.html

[R05] 参数默认值
来源：http://dali.chenzaomai.com/Article/details/gtdflbapej.html

name="${1:-default}"
来源：http://dali.chenjidiqi.icu/Article/details/gtrjsjtdct.html

[R06] 判断命令是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnxngcsr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gtoojqipyg.html

[R07] if 判断文件
来源：http://dali.aizwys.cn/Article/details/gtmfwzaktl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jiagoushi.top/Article/details/gtvkpshejr.html

[R08] 数值比较
来源：http://dali.pycfn.com/Article/details/gthkbvakzt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtlnyrzfdk.html

[R09] 字符串比较
来源：http://dali.aizwys.cn/Article/details/gtxwvngdoi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dianchejie.cn/Article/details/gtabhvdjsi.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gtyclvpyqs.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yueranfly.top/Article/details/gtmfxwydcn.html

[R11] case 多分支
来源：http://dali.sxryk.cn/Article/details/gtmyjxbocu.html

case "$1" in
来源：http://dali.jyoumei.cn/Article/details/gtnphruwrr.html

start) echo "启动" ;;
来源：http://dali.shzxlz.cn/Article/details/gtnnqtdgvx.html

stop)  echo "停止" ;;
来源：http://dali.yj20258888.top/Article/details/gtovsqafqk.html

*)     echo "未知命令" ;;
来源：http://dali.xuanzx.com/Article/details/gtysxzlmgp.html

esac
来源：http://dali.tian-w.cn/Article/details/gtyrzggejt.html

[R12] for 遍历文件
来源：http://dali.chenlongwang.top/Article/details/gtjjbgoefd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthfalxfou.html

[R13] for 计数循环
来源：http://dali.hongshengwenyu.top/Article/details/gtohwffyho.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gtvansfvkn.html

[R14] C 风格 for
来源：http://dali.zhoulong.xyz/Article/details/gtlonleuea.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.wangdashe.top/Article/details/gtmykuuygk.html

[R15] while 逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtwcflqysa.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ybcxt.top/Article/details/gtvqskesrk.html

[R16] until 等待条件
来源：http://dali.hfpthk.cn/Article/details/gtqbixlgtr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.havefunace.top/Article/details/gtaexcbpdg.html

[R17] 数组定义与取值
来源：http://dali.pengpengdd.cyou/Article/details/gtaqoxhwfu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gzhubu.top/Article/details/gtdkeziksm.html

[R18] 遍历数组
来源：http://dali.zhixingplan.top/Article/details/gtzbxqjwhd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtitxopqvw.html

[R19] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gtgkfngnnw.html

echo "${#arr[@]}"
来源：http://dali.yj202588.top/Article/details/gteglrpsxy.html

[R20] 关联数组（字典）
来源：http://dali.jinqigufen.top/Article/details/gtoqhlqivm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tianlin.xyz/Article/details/gtqygfjtym.html

[R21] 字符串长度
来源：http://dali.sweek.top/Article/details/gtxsyndpkj.html

echo "${#s}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgezdiub.html

[R22] 截取子串
来源：http://dali.sufxvd.cn/Article/details/gttaalncak.html

echo "${s:0:5}"
来源：http://dali.yongpay.top/Article/details/gtvcbefltx.html

[R23] 字符串替换
来源：http://dali.tanke756.top/Article/details/gtnhorkdaj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinqigfzy.top/Article/details/gtnfdfbqvz.html

[R24] 大小写转换
来源：http://dali.vqdsnc.cn/Article/details/gttdsymdvd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.quarkkingdee.top/Article/details/gtzgfqwrge.html

[R25] 去后缀 / 去前缀
来源：http://dali.dashuyun.cn/Article/details/gtwbutymde.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ehwqpu.com/Article/details/gtuqkrnykc.html

[R26] 命令替换
来源：http://dali.chenjidiqi.icu/Article/details/gteqlulvfj.html

now=$(date +%F); echo "$now"
来源：http://dali.zhengqikj.top/Article/details/gttrirvnjd.html

[R27] 算术展开
来源：http://dali.ehwqpu.com/Article/details/gtllndtdjw.html

echo $((1 + 2 * 3))
来源：http://dali.snrcjt.cn/Article/details/gtogtimrxy.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gtkuduapez.html

echo "scale=2; 10/3" | bc
来源：http://dali.yuxming.cn/Article/details/gthcmomznw.html

[R29] 定义函数
来源：http://dali.redwolf501.top/Article/details/gtwzwysrip.html


<!-- 参考信息 -->