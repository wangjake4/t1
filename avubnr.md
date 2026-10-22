代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.9152youxi.cn/Article/details/gtkeztvyey.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gtubvfpkud.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gtrinibbio.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenzaomai.com/Article/details/gtudpesicn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ydzc1.top/Article/details/gtqzpewkvi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.guannengcc.top/Article/details/gtlqzvtagc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.havefunace.top/Article/details/gtzozrmhfv.html

[P08] 处理浮点精度问题
来源：http://dali.jinghuilouyu.cn/Article/details/gtpowzvyef.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zdqjudy.top/Article/details/gtxmofikkb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtskyryupa.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hysaishi.cn/Article/details/gtymazgpeh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.9152youxi.cn/Article/details/gtkqzhxlzt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fzhhl.top/Article/details/gtpokctxms.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dashuyun.cn/Article/details/gtdbpsolsx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cucudq.cn/Article/details/gtlijwafnr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj20258.top/Article/details/gtpsnmqucl.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtyjfifwsb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yonumen.top/Article/details/gtgbnxyhav.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtogyrjazy.html

[Q01] 创建表
来源：http://dali.jinqigufen.top/Article/details/gtfnyovovs.html

CREATE TABLE users (
来源：http://dali.xylfe.cn/Article/details/gtevjforth.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangtech.top/Article/details/gthpqeyrjp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gteozjnmlp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.feifeiyinyue.top/Article/details/gtgybjstuf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cdnleiting.top/Article/details/gtvtoqumpu.html

);
来源：http://dali.mhx1999.top/Article/details/gtcvejsita.html

[Q02] 创建带外键的表
来源：http://dali.zhongyouzk.top/Article/details/gtlymkgofz.html

CREATE TABLE orders (
来源：http://dali.0kj1m.cn/Article/details/gteprviwle.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shzxlz.cn/Article/details/gtctccfzdu.html

user_id INT NOT NULL,
来源：http://dali.fzhhl.top/Article/details/gtbpjccrfq.html

amount DECIMAL(10, 2),
来源：http://dali.yongpay.top/Article/details/gtmxtyhteb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj20258.top/Article/details/gtdjlmfzsn.html

);
来源：http://dali.hywenlv.cn/Article/details/gtnowsurjm.html

[Q03] 增加列
来源：http://dali.pycfn.com/Article/details/gtwfdgspvv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ydzc1.top/Article/details/gtfevriiwr.html

[Q04] 修改列类型
来源：http://dali.fengsongda.top/Article/details/gtzrfjudgm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgfzy.top/Article/details/gtziytzsph.html

[Q05] 重命名列
来源：http://dali.sweek.top/Article/details/gtrlreeylo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jiagoushi.top/Article/details/gtttzxmfdj.html

[Q06] 删除列
来源：http://dali.feifeiyinyue.top/Article/details/gttmrtzmpa.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj20258.top/Article/details/gtxlawkkrl.html

[Q07] 删除表
来源：http://dali.hnqzz.top/Article/details/gtmckyuhln.html

DROP TABLE IF EXISTS orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtbbbplifa.html

[Q08] 创建普通索引
来源：http://dali.gogol.net.cn/Article/details/gtibiklqzs.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.quarkkingdee.top/Article/details/gtlalhthwl.html

[Q09] 创建唯一索引
来源：http://dali.iojbl.cn/Article/details/gtvsmnabnu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yangfankeji.com/Article/details/gtcjrirygq.html

[Q10] 插入单行
来源：http://dali.nanxinkj.top/Article/details/gtzpyixrqe.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gtiqxafbza.html

[Q11] 一次插入多行
来源：http://dali.cheryme.top/Article/details/gtqniumdhy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gtjoypqqfy.html

[Q12] 插入后取自增 ID
来源：http://dali.9152youxi.cn/Article/details/gtuiegxpfo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.0kj1m.cn/Article/details/gtdfnvzijy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nanxuanxn.top/Article/details/gtecgulkdz.html

[Q13] 忽略重复插入
来源：http://dali.yj202588.top/Article/details/gtqgrqyqdk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ybcxt.top/Article/details/gtyyjygeqj.html

[Q14] 存在则更新（upsert）
来源：http://dali.xylfe.cn/Article/details/gtyfcsdqmw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jqgfzy.top/Article/details/gteiwiyrpg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ppjwa.cn/Article/details/gttmvuaxno.html

[Q15] 查询全部
来源：http://dali.yanxiufei.cn/Article/details/gtyfxulrxk.html

SELECT * FROM users;
来源：http://dali.meibo888.top/Article/details/gtuvqmulwz.html

[Q16] 查询指定列
来源：http://dali.316326.xyz/Article/details/gtfjspaswg.html

SELECT id, name FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtjycyascb.html

[Q17] 条件查询
来源：http://dali.chenzaomai.com/Article/details/gtdjpxtggm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jqgfzy.top/Article/details/gtftjlital.html

[Q18] 模糊匹配
来源：http://dali.yj20258888.top/Article/details/gthxhbthcq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhqcfrxo.html

[Q19] 范围查询
来源：http://dali.feifeiyinyue.top/Article/details/gticjbfsly.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnqzz.top/Article/details/gtphcczxrm.html

[Q20] IN 列表
来源：http://dali.daria6918.cn/Article/details/gtcobnyhvg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhoulong.xyz/Article/details/gtjnocuxca.html

[Q21] 空值判断
来源：http://dali.vqdsnc.cn/Article/details/gtdzlidore.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxnbkmul.html

[Q22] 排序
来源：http://dali.sufxvd.cn/Article/details/gtlxaectwr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yongpay.top/Article/details/gtzvfmpzpo.html

[Q23] 分页
来源：http://dali.hammf.cn/Article/details/gtypfsvqpd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shanyushiyangtech.top/Article/details/gtakwoirkj.html

[Q24] 去重
来源：http://dali.hywenlv.cn/Article/details/gtndmmmgvq.html

SELECT DISTINCT city FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtynyzqbfb.html

[Q25] 只取前 N 条
来源：http://dali.mhx1999.top/Article/details/gtltqfmbsx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ybcxt.top/Article/details/gtglvtgjbr.html

[Q26] 计数
来源：http://dali.jiagoushi.top/Article/details/gtvekqdtid.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtzovqiodv.html

[Q27] 条件计数
来源：http://dali.shuidangran.top/Article/details/gtstwfipho.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cashguo.top/Article/details/gtuseisged.html

[Q28] 求和与平均
来源：http://dali.zycfv.cn/Article/details/gtavvgdaqf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.meibo888.top/Article/details/gtnchuclri.html

[Q29] 最大最小值
来源：http://dali.0kj1m.cn/Article/details/gtvxjzhyxo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gttzwtuxcg.html

[Q30] 分组统计
来源：http://dali.daria6918.cn/Article/details/gtbvnjgwyg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gtgebypmkm.html

[Q31] 分组后过滤
来源：http://dali.hnqzz.top/Article/details/gtvdnuecxb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shzxlz.cn/Article/details/gtwyzofoaj.html

[Q32] 分组拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gthcfpfzon.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gtomutvisr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sweek.top/Article/details/gtwhhhejih.html

[Q33] 多列分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgknbyfln.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yongpay.top/Article/details/gtwlgslyjf.html

[Q34] 每组取第一条
来源：http://dali.yj20258.top/Article/details/gtdnumwtey.html

SELECT * FROM (
来源：http://dali.zhiwuduotai.top/Article/details/gtrdbgzadb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj20258.top/Article/details/gtxaacncvz.html

) t WHERE rn = 1;
来源：http://dali.fzhhl.top/Article/details/gtdeyvbwie.html

[Q35] 内连接
来源：http://dali.pengpengdd.cyou/Article/details/gtadtfovyq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscpslrep.html

[Q36] 左连接
来源：http://dali.hfpthk.cn/Article/details/gtqxlvcrom.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gtluoodulm.html

[Q37] 右连接
来源：http://dali.hnqzz.top/Article/details/gtydgyqlzd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhengqikj.top/Article/details/gtaguxdfsw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sufxvd.cn/Article/details/gttexodncx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.9152youxi.cn/Article/details/gtadbubvol.html

[Q39] 自连接（查上下级）
来源：http://dali.kuanghao11.cn/Article/details/gtvhapmeee.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxinkj.top/Article/details/gtdfmoedgk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.pengpengdd.cyou/Article/details/gtfalswxni.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sufxvd.cn/Article/details/gtajjuwheq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xylfe.cn/Article/details/gtfajuomme.html

[Q41] 多表连接
来源：http://dali.gaohongyu789.top/Article/details/gtrlrloijn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nanxuanxn.top/Article/details/gtpnygxwjb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tianlin.xyz/Article/details/gtnbxpipwo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinqigfzy.top/Article/details/gtldfnitwn.html

[Q42] 连接条件附加过滤
来源：http://dali.kuanghao11.cn/Article/details/gtcegezyxa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnqzz.top/Article/details/gtdvtxrlow.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuanzhike.top/Article/details/gtqysdrgnf.html

[Q43] 标量子查询
来源：http://dali.tianlin.xyz/Article/details/gttzwtjqzq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigufen.top/Article/details/gtqdcmczqd.html

[Q44] IN 子查询
来源：http://dali.yj20258.top/Article/details/gtwtwywfvj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hysaishi.cn/Article/details/gtdcnbixve.html

[Q45] EXISTS 判断存在
来源：http://dali.gogol.net.cn/Article/details/gtutlillus.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenzaomai.com/Article/details/gtecrsyocd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenzaomai.com/Article/details/gtbchwluww.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gzhubu.top/Article/details/gteunrrlah.html

[Q47] 与平均值比较
来源：http://dali.jlsjyb.cn/Article/details/gtkxlwwswj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.daxiang520.top/Article/details/gtiauewcas.html

[Q48] CTE 公用表表达式
来源：http://dali.sysykeji.top/Article/details/gtsptguwpu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cheryme.top/Article/details/gtwdobgnxx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sufxvd.cn/Article/details/gtiblkreym.html

[Q49] 更新单行
来源：http://dali.jinqigufen.top/Article/details/gtazndqhjt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hammf.cn/Article/details/gtyzzesqnp.html

[Q50] 批量更新
来源：http://dali.cucudq.cn/Article/details/gttdgvcijh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gttqvkicyh.html

[Q51] 用子查询更新
来源：http://dali.yangfankeji.com/Article/details/gtheeyezak.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ydzc1.top/Article/details/gtxvwwwwxk.html

[Q52] 删除指定行
来源：http://dali.fzhhl.top/Article/details/gtmcuzfhrc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenzaomai.com/Article/details/gtefdjjjuz.html

[Q53] 按条件删除
来源：http://dali.tian-w.cn/Article/details/gtyfwnidjh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.mhx1999.top/Article/details/gttvwcjbje.html

[Q54] 清空表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwonkbuv.html

TRUNCATE TABLE logs;
来源：http://dali.hywenlv.cn/Article/details/gtzjpopdwv.html

[Q55] 排名（并列占位）
来源：http://dali.zhengqikj.top/Article/details/gtpgihobmc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gtykcljpeq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.haohaochexian.top/Article/details/gtnuakauys.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ivvv.top/Article/details/gtmxpxuawb.html

[Q57] 行号
来源：http://dali.nanxuanxn.top/Article/details/gtcdywlmcm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ydzc1.top/Article/details/gtxoyuqcrk.html

[Q58] 累计求和
来源：http://dali.pengpengdd.cyou/Article/details/gthfojamug.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.smart0.xyz/Article/details/gteytmbzyy.html

[Q59] 分组内累计
来源：http://dali.c1oappe.top/Article/details/gtomthbpvx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtovtaewzh.html

[Q60] 取上一行 / 下一行
来源：http://dali.snrcjt.cn/Article/details/gtpibmmeec.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ppjwa.cn/Article/details/gtmxilgtvm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtjjavpkos.html

[Q61] 移动平均
来源：http://dali.zhongyouzk.top/Article/details/gtndllhmgb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtopsublxr.html

[Q62] 分组占比
来源：http://dali.snrcjt.cn/Article/details/gtkvjowruk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gtqffgdtla.html

[Q63] 开启事务
来源：http://dali.hammf.cn/Article/details/gtasfsiunt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shzxlz.cn/Article/details/gtmknipuzm.html

[Q64] 提交事务
来源：http://dali.jlsjyb.cn/Article/details/gtwgwxpbxu.html

COMMIT;
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqqubaxf.html

[Q65] 回滚事务
来源：http://dali.ehwqpu.com/Article/details/gtsluyqbmw.html

ROLLBACK;
来源：http://dali.ivvv.top/Article/details/gtxhvitlgt.html

[Q66] 行锁查询
来源：http://dali.aizwys.cn/Article/details/gtncxuusiy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sweek.top/Article/details/gtxwwksyfc.html

[Q67] 设置隔离级别
来源：http://dali.mhx1999.top/Article/details/gtvrbryvef.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258.top/Article/details/gtxyuuixvz.html

[Q68] 保存点
来源：http://dali.tanke756.top/Article/details/gtewzwhrpq.html

SAVEPOINT sp1;
来源：http://dali.ehwqpu.com/Article/details/gtqgjedezi.html

ROLLBACK TO sp1;
来源：http://dali.yj20258.top/Article/details/gtwhbausfj.html

[Q69] 查看执行计划
来源：http://dali.dianchejie.cn/Article/details/gtaoyawbue.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gtwxfuhgvi.html

[Q70] 更新统计信息
来源：http://dali.shuidangran.top/Article/details/gtzvrwbpej.html

ANALYZE TABLE users;
来源：http://dali.kuanghao11.cn/Article/details/gtgfhjlbka.html

[Q71] 查看建表语句
来源：http://dali.wangdashe.top/Article/details/gtwvuysgda.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daria6918.cn/Article/details/gtnaecmqjr.html

[Q72] 查看索引
来源：http://dali.vqdsnc.cn/Article/details/gtahzgfejg.html

SHOW INDEX FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtmqpfwooy.html

[Q73] 查看表状态
来源：http://dali.dashuyun.cn/Article/details/gtocvbuykt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nanxinkj.top/Article/details/gtkxwtiaxb.html

[Q74] 强制使用索引
来源：http://dali.shangyingyoupin.top/Article/details/gtngacqset.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nanxinkj.top/Article/details/gtzxihmufx.html

[Q75] 日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gtrgcevvqf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtnqnrfxxq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ybcxt.top/Article/details/gtjnthrmip.html

[Q76] 按天统计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqwsezqq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hysaishi.cn/Article/details/gtglqlcbnh.html

[Q77] 时间加减
来源：http://dali.jinqigufen.top/Article/details/gtdbsjfuji.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuxming.cn/Article/details/gtpjjcjwrv.html

[Q78] 当前时间
来源：http://dali.ppjwa.cn/Article/details/gtkmiijamv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cqqwz.cn/Article/details/gtxjvvwibe.html

[Q79] 字符串拼接
来源：http://dali.sweek.top/Article/details/gtlqosktyp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nanxuanxn.top/Article/details/gtwyxxsmuw.html

[Q80] 字符串截取
来源：http://dali.chenzaomai.com/Article/details/gtcpdqochz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtpllmiwmz.html

[Q81] 字符串替换
来源：http://dali.jqgfzy.top/Article/details/gttuphjpuv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtqwyuuvgq.html

[Q82] 字符长度与字节长度
来源：http://dali.ydzc1.top/Article/details/gtandxdjjj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtlcljkocu.html

[Q83] 大小写转换
来源：http://dali.pengpengdd.cyou/Article/details/gtyxoclvbg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwlfyzere.html

[Q84] 去除首尾空格
来源：http://dali.yangfankeji.com/Article/details/gtdxffloux.html

SELECT TRIM(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtmshguxbr.html

[Q85] 数值取整
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqfttpib.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenlongwang.top/Article/details/gtnyvqtuqr.html

[Q86] 读取 JSON 字段
来源：http://dali.zhiwuduotai.top/Article/details/gtlgklbafz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jiagoushi.top/Article/details/gtkyxtppzn.html

[Q87] JSON 字段做条件
来源：http://dali.zhengqikj.top/Article/details/gtxaaftjlw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hnxiangtu.top/Article/details/gtjiqwszyk.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenzaomai.com/Article/details/gtstfpxjan.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cucudq.cn/Article/details/gtkfvmphbz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cashguo.top/Article/details/gtmeyzcage.html

[Q89] 判断表是否存在
来源：http://dali.cdnleiting.top/Article/details/gtkgyapjxt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenlongwang.top/Article/details/gtoskuxces.html

[Q90] 生成序号列
来源：http://dali.havefunace.top/Article/details/gtgfbtczpi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cqqwz.cn/Article/details/gtgotipnwk.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtizhqlcyx.html

R. Bash 专题
来源：http://dali.yj20258888.top/Article/details/gttvfblxpl.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtlliyhtkw.html

[R01] shebang 与严格模式
来源：http://dali.yvedp.cn/Article/details/gtmdwekfrk.html

#!/usr/bin/env bash
来源：http://dali.shuidangran.top/Article/details/gtcsuxjvek.html

set -euo pipefail
来源：http://dali.nwbrower.top/Article/details/gtpyvyepvy.html

[R02] 变量赋值与使用
来源：http://dali.cqqwz.cn/Article/details/gtoybulcbz.html

name="Tom"; echo "$name"
来源：http://dali.sweek.top/Article/details/gtnmzfzxsh.html

[R03] 只读变量
来源：http://dali.hfpthk.cn/Article/details/gtswaodoye.html

readonly PI=3.14
来源：http://dali.svipenyu.cn/Article/details/gtqasaqojo.html

[R04] 位置参数
来源：http://dali.xziqi.cn/Article/details/gtmymahodf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjlkjsgfr.html

[R05] 参数默认值
来源：http://dali.guannengcc.top/Article/details/gtraadunas.html

name="${1:-default}"
来源：http://dali.jyoumei.cn/Article/details/gtlhgxnhcg.html

[R06] 判断命令是否存在
来源：http://dali.pycfn.com/Article/details/gtfqbiyjyv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gtlrrfccde.html

[R07] if 判断文件
来源：http://dali.ehwqpu.com/Article/details/gtobrbfslt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cqqwz.cn/Article/details/gtrtpfcupf.html

[R08] 数值比较
来源：http://dali.hfpthk.cn/Article/details/gtrtfflxun.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tian-w.cn/Article/details/gtkjaoarii.html

[R09] 字符串比较
来源：http://dali.redwolf501.top/Article/details/gtlxfcqibb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sysykeji.top/Article/details/gtzmcpynhs.html

[R10] 正则匹配
来源：http://dali.mhx1999.top/Article/details/gtaglabref.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtiooanctv.html

[R11] case 多分支
来源：http://dali.hywenlv.cn/Article/details/gtrzkheubk.html

case "$1" in
来源：http://dali.fzhhl.top/Article/details/gtepqfjqxb.html

start) echo "启动" ;;
来源：http://dali.nanxuanxn.top/Article/details/gtyffaazbx.html

stop)  echo "停止" ;;
来源：http://dali.sweek.top/Article/details/gtoauxjoua.html

*)     echo "未知命令" ;;
来源：http://dali.hnqzz.top/Article/details/gtbemsgdtw.html

esac
来源：http://dali.jiagoushi.top/Article/details/gtmfahirzk.html

[R12] for 遍历文件
来源：http://dali.yonumen.top/Article/details/gtpucywlmg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.aizwys.cn/Article/details/gtpaytwstn.html

[R13] for 计数循环
来源：http://dali.shangyingyoupin.top/Article/details/gtcjrpumdq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gtomepquxu.html

[R14] C 风格 for
来源：http://dali.gogol.net.cn/Article/details/gtvemidvut.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yuanzhike.top/Article/details/gtyslgopfh.html

[R15] while 逐行读文件
来源：http://dali.aizwys.cn/Article/details/gthpqwilhs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gzhubu.top/Article/details/gteylwuvyn.html

[R16] until 等待条件
来源：http://dali.wangdashe.top/Article/details/gtykpknjws.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgufenzy.top/Article/details/gtjwirawve.html

[R17] 数组定义与取值
来源：http://dali.iojbl.cn/Article/details/gtbvsdgxao.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.9152youxi.cn/Article/details/gtfilxcagp.html

[R18] 遍历数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwmbpwrp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.316326.xyz/Article/details/gtobrpmfqh.html

[R19] 数组长度
来源：http://dali.316326.xyz/Article/details/gtmqcttrem.html

echo "${#arr[@]}"
来源：http://dali.xinyue.icu/Article/details/gtckggonmq.html

[R20] 关联数组（字典）
来源：http://dali.nwbrower.top/Article/details/gtjrwelyqm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.316326.xyz/Article/details/gtstbhepcy.html

[R21] 字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgthxwhsb.html

echo "${#s}"
来源：http://dali.chenjidiqi.icu/Article/details/gtzdmklnjb.html

[R22] 截取子串
来源：http://dali.hnxiangtu.top/Article/details/gtpfwinnav.html

echo "${s:0:5}"
来源：http://dali.gotoacloud.top/Article/details/gtpnyljhfr.html

[R23] 字符串替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthsvmydjh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nanxinkj.top/Article/details/gtwyzbfpup.html

[R24] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gtalhjgrjz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.haohaochexian.top/Article/details/gtwagmryrx.html

[R25] 去后缀 / 去前缀
来源：http://dali.nanxuanxn.top/Article/details/gtqlrewtwo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xylfe.cn/Article/details/gtvprprsys.html

[R26] 命令替换
来源：http://dali.zhongyouzk.top/Article/details/gtchsblamu.html

now=$(date +%F); echo "$now"
来源：http://dali.jianghu66.top/Article/details/gtghncykbc.html

[R27] 算术展开
来源：http://dali.yj202588.top/Article/details/gtmbcqkkmk.html

echo $((1 + 2 * 3))
来源：http://dali.xuetiantiany.cn/Article/details/gtvgjkppbx.html

[R28] 浮点运算
来源：http://dali.yvedp.cn/Article/details/gtsjazjtwx.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhengqikj.top/Article/details/gtrbuutgfz.html

[R29] 定义函数
来源：http://dali.bjfxy.top/Article/details/gtfsgdbwiu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.mhx1999.top/Article/details/gtzrcbumto.html

[R30] 函数返回状态码
来源：http://dali.yj20258888.top/Article/details/gtunqmulur.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.9152youxi.cn/Article/details/gtljtazkeq.html

[R31] 局部变量
来源：http://dali.xuanzx.com/Article/details/gtmtakjacp.html

f() { local x=1; echo "$x"; }
来源：http://dali.cucudq.cn/Article/details/gthhfogekw.html

[R32] 参数个数校验
来源：http://dali.yvedp.cn/Article/details/gtgkyitwxe.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gaohongyu789.top/Article/details/gtjobpkdho.html

[R33] 捕获错误并提示行号
来源：http://dali.svipenyu.cn/Article/details/gtotrocuva.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xziqi.cn/Article/details/gtsuzyyyzp.html

[R34] 退出时清理
来源：http://dali.sweek.top/Article/details/gtrprkjihn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gtgbzzmlxt.html

[R35] 后台执行并等待
来源：http://dali.bjfxy.top/Article/details/gtljikgzxi.html


<!-- 参考信息 -->