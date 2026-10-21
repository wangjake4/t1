代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.hnqzz.top/Article/details/gtxheqakre.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gtoxmlmllc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cucudq.cn/Article/details/gtbduunuqr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.iojbl.cn/Article/details/gtzdzhwgvy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tianlin.xyz/Article/details/gtykebpyfd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zdqjudy.top/Article/details/gtsvzoowor.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ydzc1.top/Article/details/gtswizaapv.html

[P08] 处理浮点精度问题
来源：http://dali.aibaodan.cn/Article/details/gtcshieaig.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj20258.top/Article/details/gtsccpqueu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.haohaochexian.top/Article/details/gtzfgkedws.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hysaishi.cn/Article/details/gtvvzzadhv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yvedp.cn/Article/details/gtnqlbnudp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhongyouzk.top/Article/details/gtkwdmhfjp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.vqdsnc.cn/Article/details/gtepxlwdnj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jlsjyb.cn/Article/details/gttintkdgx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dashuyun.cn/Article/details/gtmrrmxkmv.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtiperlhfi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jlsjyb.cn/Article/details/gtzsrqbywc.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtxrqzakyc.html

[Q01] 创建表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstvftrgu.html

CREATE TABLE users (
来源：http://dali.hnxiangtu.top/Article/details/gtvypuvyhg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhengqikj.top/Article/details/gtkiddocxy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhengqikj.top/Article/details/gtyldgyise.html

email VARCHAR(100) UNIQUE,
来源：http://dali.iojbl.cn/Article/details/gtdoexhyso.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.fengsongda.top/Article/details/gtepnhgthl.html

);
来源：http://dali.zhongyouzk.top/Article/details/gttajijyqs.html

[Q02] 创建带外键的表
来源：http://dali.yueranfly.top/Article/details/gtauddhiec.html

CREATE TABLE orders (
来源：http://dali.svipenyu.cn/Article/details/gtsohychct.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.havefunace.top/Article/details/gthoytyjba.html

user_id INT NOT NULL,
来源：http://dali.aibaodan.cn/Article/details/gtggwcrthr.html

amount DECIMAL(10, 2),
来源：http://dali.jqgfzy.top/Article/details/gtyhklgeos.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.0kj1m.cn/Article/details/gtwbdqmcgj.html

);
来源：http://dali.tanke756.top/Article/details/gtnljfyyef.html

[Q03] 增加列
来源：http://dali.meibo888.top/Article/details/gtkoztylvq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hnqzz.top/Article/details/gtgmkhiofx.html

[Q04] 修改列类型
来源：http://dali.jianghu66.top/Article/details/gtkgorpekv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxmhojaog.html

[Q05] 重命名列
来源：http://dali.kuanghao11.cn/Article/details/gtdzqoeabr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ppjwa.cn/Article/details/gtsnrlctxo.html

[Q06] 删除列
来源：http://dali.xylfe.cn/Article/details/gthqtcikar.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.birdmap.top/Article/details/gtfawetbrn.html

[Q07] 删除表
来源：http://dali.tanke756.top/Article/details/gtvjjnplbd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.vqdsnc.cn/Article/details/gthlcgrfkk.html

[Q08] 创建普通索引
来源：http://dali.pengpengdd.cyou/Article/details/gtnjpgwohu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yonumen.top/Article/details/gtexoguksd.html

[Q09] 创建唯一索引
来源：http://dali.guannengcc.top/Article/details/gtkrfmzocu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenjidiqi.icu/Article/details/gtufhlquxv.html

[Q10] 插入单行
来源：http://dali.tanke756.top/Article/details/gtxmdpgcmg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtljsuze.html

[Q11] 一次插入多行
来源：http://dali.quarkkingdee.top/Article/details/gtoyobwbmi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.pycfn.com/Article/details/gtghhcrcll.html

[Q12] 插入后取自增 ID
来源：http://dali.0kj1m.cn/Article/details/gtqwnyjsjj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.havefunace.top/Article/details/gtckpzzxmc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shuidangran.top/Article/details/gtydinbxqe.html

[Q13] 忽略重复插入
来源：http://dali.yj202588.top/Article/details/gtnyphlpuc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gtqqljqehf.html

[Q14] 存在则更新（upsert）
来源：http://dali.daria6918.cn/Article/details/gtusgbnshc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.pengpengdd.cyou/Article/details/gtdladaksy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shzxlz.cn/Article/details/gtokxgnywf.html

[Q15] 查询全部
来源：http://dali.chenzaomai.com/Article/details/gtrmuizszj.html

SELECT * FROM users;
来源：http://dali.cheryme.top/Article/details/gtdcnsvczx.html

[Q16] 查询指定列
来源：http://dali.gzhubu.top/Article/details/gtmgwolxae.html

SELECT id, name FROM users;
来源：http://dali.hnqzz.top/Article/details/gtscpouixw.html

[Q17] 条件查询
来源：http://dali.yongpay.top/Article/details/gtfdslckpo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllgxkkxj.html

[Q18] 模糊匹配
来源：http://dali.xinyue.icu/Article/details/gtraavuqag.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.wangdashe.top/Article/details/gtyfcbvhcn.html

[Q19] 范围查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtvytgoyds.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hammf.cn/Article/details/gtvchkprgc.html

[Q20] IN 列表
来源：http://dali.gzhubu.top/Article/details/gtytlcaydv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ydzc1.top/Article/details/gtmairdqpb.html

[Q21] 空值判断
来源：http://dali.xziqi.cn/Article/details/gtnzbitusg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.svipenyu.cn/Article/details/gtyggrqrtr.html

[Q22] 排序
来源：http://dali.snrcjt.cn/Article/details/gtpcylmlyj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yuanzhike.top/Article/details/gtwskcwael.html

[Q23] 分页
来源：http://dali.xylfe.cn/Article/details/gtzidbmmlf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ydzc1.top/Article/details/gttpleftea.html

[Q24] 去重
来源：http://dali.yvedp.cn/Article/details/gtmataanuv.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtmnacptts.html

[Q25] 只取前 N 条
来源：http://dali.cheryme.top/Article/details/gtpseddxml.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ivvv.top/Article/details/gtvkvxipgd.html

[Q26] 计数
来源：http://dali.gaohongyu789.top/Article/details/gtlgyurefr.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtsdjmpfwc.html

[Q27] 条件计数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhzdreff.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.mhx1999.top/Article/details/gtwgledqwq.html

[Q28] 求和与平均
来源：http://dali.fengsongda.top/Article/details/gtxjpllimr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtidoevjjq.html

[Q29] 最大最小值
来源：http://dali.hysaishi.cn/Article/details/gtrhnqnzvx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtoxosurqn.html

[Q30] 分组统计
来源：http://dali.ybcxt.top/Article/details/gtjxzebyte.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtwxibtwjf.html

[Q31] 分组后过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtriuedxvr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.guowangkeji.top/Article/details/gtkkgpsxfd.html

[Q32] 分组拼接字符串
来源：http://dali.hnqzz.top/Article/details/gtnfuuaqnu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gtrlgdwcgu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sysykeji.top/Article/details/gtacugpsgx.html

[Q33] 多列分组
来源：http://dali.gaohongyu789.top/Article/details/gtqbggfkoi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pycfn.com/Article/details/gtksimsxgs.html

[Q34] 每组取第一条
来源：http://dali.dashuyun.cn/Article/details/gtjlbhavjd.html

SELECT * FROM (
来源：http://dali.sufxvd.cn/Article/details/gtbfvpqloz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jlsjyb.cn/Article/details/gttltcliwi.html

) t WHERE rn = 1;
来源：http://dali.wangdashe.top/Article/details/gtogphnsdx.html

[Q35] 内连接
来源：http://dali.chenzaomai.com/Article/details/gtkybduqtt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkcrcmqed.html

[Q36] 左连接
来源：http://dali.meibo888.top/Article/details/gtmbmeylqp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tian-w.cn/Article/details/gtooirvvkn.html

[Q37] 右连接
来源：http://dali.jinqigfzy.top/Article/details/gtqefqcepc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jqgfzy.top/Article/details/gtxfxkeajs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenlongwang.top/Article/details/gtbdvqbvfu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.havefunace.top/Article/details/gtuuqcjapb.html

[Q39] 自连接（查上下级）
来源：http://dali.hywenlv.cn/Article/details/gtmtgtbrsv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.0kj1m.cn/Article/details/gtturdmfnd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.guannengcc.top/Article/details/gtdgaywykp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinqigufen.top/Article/details/gtupvpqezi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jqgufenzy.top/Article/details/gtkxfrowck.html

[Q41] 多表连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtefuzrbmc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.dianchejie.cn/Article/details/gtuvbuqcuc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shzxlz.cn/Article/details/gtxkvkqdgg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yuxming.cn/Article/details/gtjhpupfgs.html

[Q42] 连接条件附加过滤
来源：http://dali.tianlin.xyz/Article/details/gtrvzwiecm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnxiangtu.top/Article/details/gtjzcgqkvq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenzaomai.com/Article/details/gtjvlfswgv.html

[Q43] 标量子查询
来源：http://dali.zdqjudy.top/Article/details/gtiojiyfjf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.0kj1m.cn/Article/details/gthnaiztua.html

[Q44] IN 子查询
来源：http://dali.guannengcc.top/Article/details/gtqttyeoyx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.9152youxi.cn/Article/details/gtoifulomu.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangtech.top/Article/details/gteusyumej.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gotoacloud.top/Article/details/gtguemyzge.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xylfe.cn/Article/details/gthcpgqivf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdotdrrd.html

[Q47] 与平均值比较
来源：http://dali.jianghu66.top/Article/details/gtzrfwiuou.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinghuilouyu.cn/Article/details/gtokwwlxbn.html

[Q48] CTE 公用表表达式
来源：http://dali.vqdsnc.cn/Article/details/gtdnszseii.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj202588.top/Article/details/gtwdrhzkvk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gtuimocwdp.html

[Q49] 更新单行
来源：http://dali.cucudq.cn/Article/details/gtfuhfykug.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gtamcuzhsc.html

[Q50] 批量更新
来源：http://dali.smart0.xyz/Article/details/gtmxbjbivf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tianlin.xyz/Article/details/gtkmznbcuj.html

[Q51] 用子查询更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyavzphax.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yueranfly.top/Article/details/gtxemfryuc.html

[Q52] 删除指定行
来源：http://dali.yongpay.top/Article/details/gtbkgeqwvu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gtllettxdb.html

[Q53] 按条件删除
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqyahdrr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tian-w.cn/Article/details/gtrcqmhpjw.html

[Q54] 清空表
来源：http://dali.ppjwa.cn/Article/details/gtnpvurlpv.html

TRUNCATE TABLE logs;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuiqauzop.html

[Q55] 排名（并列占位）
来源：http://dali.yvedp.cn/Article/details/gtgcfretnm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tanke756.top/Article/details/gtiozqiadv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhoulong.xyz/Article/details/gteaqgfmgy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttyfmgbxd.html

[Q57] 行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjikhrch.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtggiuknqa.html

[Q58] 累计求和
来源：http://dali.yongpay.top/Article/details/gtdzhpzhfg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtmhkfarew.html

[Q59] 分组内累计
来源：http://dali.hammf.cn/Article/details/gtftlsfyod.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtapalcada.html

[Q60] 取上一行 / 下一行
来源：http://dali.zycfv.cn/Article/details/gtexzmljcg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jqgufenzy.top/Article/details/gtlcblllkt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtxmaxgbxz.html

[Q61] 移动平均
来源：http://dali.mhx1999.top/Article/details/gtrgymvabw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtchhlcnbz.html

[Q62] 分组占比
来源：http://dali.ehwqpu.com/Article/details/gtepdzfmeg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gtnleouqfq.html

[Q63] 开启事务
来源：http://dali.cqqwz.cn/Article/details/gtcgznhcdj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jyoumei.cn/Article/details/gtaspinxag.html

[Q64] 提交事务
来源：http://dali.andypj.xyz/Article/details/gtttjdcbbt.html

COMMIT;
来源：http://dali.svipenyu.cn/Article/details/gtogcqvrre.html

[Q65] 回滚事务
来源：http://dali.zhongyouzk.top/Article/details/gtvucskwte.html

ROLLBACK;
来源：http://dali.dashuyun.cn/Article/details/gttmkzlsoa.html

[Q66] 行锁查询
来源：http://dali.jyoumei.cn/Article/details/gtjkmyfzob.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.c1oappe.top/Article/details/gtjlzfxmiv.html

[Q67] 设置隔离级别
来源：http://dali.jinqigfzy.top/Article/details/gtzjygcljh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.guowangkeji.top/Article/details/gtsxiyefji.html

[Q68] 保存点
来源：http://dali.jinyuanbaomall.cn/Article/details/gthujqujku.html

SAVEPOINT sp1;
来源：http://dali.sweek.top/Article/details/gthiyxande.html

ROLLBACK TO sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtoopcuxlb.html

[Q69] 查看执行计划
来源：http://dali.zhiwuduotai.top/Article/details/gtoueitydf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shangyingyoupin.top/Article/details/gtzvgcaovz.html

[Q70] 更新统计信息
来源：http://dali.shuidangran.top/Article/details/gtlsyjiinp.html

ANALYZE TABLE users;
来源：http://dali.sweek.top/Article/details/gtrhdmritu.html

[Q71] 查看建表语句
来源：http://dali.zhongyouzk.top/Article/details/gtapfhfrhl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xuanzx.com/Article/details/gtjvnrkaez.html

[Q72] 查看索引
来源：http://dali.jinqigufen.top/Article/details/gtburjadqt.html

SHOW INDEX FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtquvagslt.html

[Q73] 查看表状态
来源：http://dali.hnqzz.top/Article/details/gtbxmoytpu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shangyingyoupin.top/Article/details/gtvcxdghqh.html

[Q74] 强制使用索引
来源：http://dali.ydzc1.top/Article/details/gtaplbwtma.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.svipenyu.cn/Article/details/gtvxksmzmy.html

[Q75] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gtcoalsmgp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxmfjlev.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xinyue.icu/Article/details/gtndqvlakl.html

[Q76] 按天统计
来源：http://dali.ivvv.top/Article/details/gtsutdezyr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xylfe.cn/Article/details/gtxduvltqv.html

[Q77] 时间加减
来源：http://dali.bjfxy.top/Article/details/gtzxqkzbbg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gzhubu.top/Article/details/gtfaizjslc.html

[Q78] 当前时间
来源：http://dali.0kj1m.cn/Article/details/gtruwdhjts.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guowangkeji.top/Article/details/gtxwvhsunk.html

[Q79] 字符串拼接
来源：http://dali.jianghu66.top/Article/details/gtvbkauzht.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.feifeiyinyue.top/Article/details/gtgquqlhlf.html

[Q80] 字符串截取
来源：http://dali.mhx1999.top/Article/details/gtkcbqgaww.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtotoyslfq.html

[Q81] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gtzoblebjw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtihpyowpw.html

[Q82] 字符长度与字节长度
来源：http://dali.fzhhl.top/Article/details/gtfpchafex.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gtgwhuhnsf.html

[Q83] 大小写转换
来源：http://dali.nanxuanxn.top/Article/details/gtzlczrspv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtwzfukmxt.html

[Q84] 去除首尾空格
来源：http://dali.hysaishi.cn/Article/details/gtcbprgene.html

SELECT TRIM(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtexiwmdqz.html

[Q85] 数值取整
来源：http://dali.fzhhl.top/Article/details/gtkyukbgmm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.aibaodan.cn/Article/details/gtawtabmcm.html

[Q86] 读取 JSON 字段
来源：http://dali.jiagoushi.top/Article/details/gttkomrclf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shzxlz.cn/Article/details/gtdnrdqegn.html

[Q87] JSON 字段做条件
来源：http://dali.iojbl.cn/Article/details/gtqjuzdlrx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ybcxt.top/Article/details/gtmdwwbtob.html

[Q88] 行转列（条件聚合）
来源：http://dali.zycfv.cn/Article/details/gtggxxnsxk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xinyue.icu/Article/details/gtcvtgrpeg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtrgiigdhx.html

[Q89] 判断表是否存在
来源：http://dali.yongpay.top/Article/details/gtfdppnods.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gtxpicndfr.html

[Q90] 生成序号列
来源：http://dali.cheryme.top/Article/details/gtjowvvwqj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hammf.cn/Article/details/gtvhhzbeux.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtkohrmcgp.html

R. Bash 专题
来源：http://dali.xinyue.icu/Article/details/gtbmmuvezc.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtusnnthhc.html

[R01] shebang 与严格模式
来源：http://dali.fzhhl.top/Article/details/gtefrlfhyq.html

#!/usr/bin/env bash
来源：http://dali.jlsjyb.cn/Article/details/gtliwfekgj.html

set -euo pipefail
来源：http://dali.shuidangran.top/Article/details/gtdvvxgqzo.html

[R02] 变量赋值与使用
来源：http://dali.cucudq.cn/Article/details/gthxhaalfs.html

name="Tom"; echo "$name"
来源：http://dali.pengpengdd.cyou/Article/details/gtxogpjnxr.html

[R03] 只读变量
来源：http://dali.sufxvd.cn/Article/details/gtjpnxsona.html

readonly PI=3.14
来源：http://dali.cucudq.cn/Article/details/gtubskorhd.html

[R04] 位置参数
来源：http://dali.ivvv.top/Article/details/gtenznfjzo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.redwolf501.top/Article/details/gtfvrnszkb.html

[R05] 参数默认值
来源：http://dali.jlsjyb.cn/Article/details/gtmejzuyqd.html

name="${1:-default}"
来源：http://dali.zhiwuduotai.top/Article/details/gtmnsihqen.html

[R06] 判断命令是否存在
来源：http://dali.gotoacloud.top/Article/details/gtkzdqdkuq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gthpltukdu.html

[R07] if 判断文件
来源：http://dali.fzhhl.top/Article/details/gtedrcptpm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.svipenyu.cn/Article/details/gtybgwrgmg.html

[R08] 数值比较
来源：http://dali.hfpthk.cn/Article/details/gtjpqwuwyh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.fzhhl.top/Article/details/gttdkfmwfk.html

[R09] 字符串比较
来源：http://dali.zhixingplan.top/Article/details/gtjamolcxk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jlsjyb.cn/Article/details/gthlefbgzd.html

[R10] 正则匹配
来源：http://dali.yj20258.top/Article/details/gtlarxptth.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zdqjudy.top/Article/details/gtgkvcyzrb.html

[R11] case 多分支
来源：http://dali.ydzc1.top/Article/details/gtzclnenam.html

case "$1" in
来源：http://dali.pengpengdd.cyou/Article/details/gtnrlprnkd.html

start) echo "启动" ;;
来源：http://dali.hywenlv.cn/Article/details/gtskbyzhdb.html

stop)  echo "停止" ;;
来源：http://dali.gotoacloud.top/Article/details/gtiqxqkxpm.html

*)     echo "未知命令" ;;
来源：http://dali.sxryk.cn/Article/details/gtkpdnggmr.html

esac
来源：http://dali.haohaochexian.top/Article/details/gthitmhpkb.html

[R12] for 遍历文件
来源：http://dali.redwolf501.top/Article/details/gtqochjaov.html

for f in *.txt; do echo "$f"; done
来源：http://dali.dashuyun.cn/Article/details/gtvgepmtew.html

[R13] for 计数循环
来源：http://dali.yvedp.cn/Article/details/gtisuewsvp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gtwexndmce.html

[R14] C 风格 for
来源：http://dali.9152youxi.cn/Article/details/gtxlahkdje.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gtleshuxyt.html

[R15] while 逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtfskumivc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yuanzhike.top/Article/details/gthhxuqvja.html

[R16] until 等待条件
来源：http://dali.jqgufenzy.top/Article/details/gtlawnqevs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.feifeiyinyue.top/Article/details/gtjentxeqa.html

[R17] 数组定义与取值
来源：http://dali.ydzc1.top/Article/details/gthvpospon.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ydzc1.top/Article/details/gteciartaw.html

[R18] 遍历数组
来源：http://dali.tianlin.xyz/Article/details/gttcgszjmc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sufxvd.cn/Article/details/gtwtvtdmuh.html

[R19] 数组长度
来源：http://dali.shangyingyoupin.top/Article/details/gtrbodwlmt.html

echo "${#arr[@]}"
来源：http://dali.zhengqikj.top/Article/details/gtdxbrmphi.html

[R20] 关联数组（字典）
来源：http://dali.guowangkeji.top/Article/details/gtvdseawnc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258888.top/Article/details/gtkdgndxcf.html

[R21] 字符串长度
来源：http://dali.nwbrower.top/Article/details/gthiqdxfsx.html

echo "${#s}"
来源：http://dali.aizwys.cn/Article/details/gtabvvqmce.html

[R22] 截取子串
来源：http://dali.birdmap.top/Article/details/gtnospmyjd.html

echo "${s:0:5}"
来源：http://dali.nwbrower.top/Article/details/gtdselaibi.html

[R23] 字符串替换
来源：http://dali.cucudq.cn/Article/details/gtcalibzfi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.9152youxi.cn/Article/details/gtabdgebhp.html

[R24] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gttasrqfko.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.pengpengdd.cyou/Article/details/gtlmtzvbec.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuxming.cn/Article/details/gtvkpcfuts.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.svipenyu.cn/Article/details/gtutvvvjwx.html

[R26] 命令替换
来源：http://dali.sweek.top/Article/details/gtkepazlxd.html

now=$(date +%F); echo "$now"
来源：http://dali.xziqi.cn/Article/details/gtaidqxbpd.html

[R27] 算术展开
来源：http://dali.yj20258888.top/Article/details/gtemituxgx.html

echo $((1 + 2 * 3))
来源：http://dali.yvedp.cn/Article/details/gtwlvnwrad.html

[R28] 浮点运算
来源：http://dali.yanxiufei.cn/Article/details/gtxzkhviis.html

echo "scale=2; 10/3" | bc
来源：http://dali.hfpthk.cn/Article/details/gtkwqiyotf.html

[R29] 定义函数
来源：http://dali.zhixingplan.top/Article/details/gtagwqtchd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmmzwuxo.html

[R30] 函数返回状态码
来源：http://dali.jyoumei.cn/Article/details/gtrxexjuab.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xuanzx.com/Article/details/gtfljecces.html

[R31] 局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gtdwrrmjgf.html

f() { local x=1; echo "$x"; }
来源：http://dali.gaohongyu789.top/Article/details/gtxhfuvmcf.html

[R32] 参数个数校验
来源：http://dali.vqdsnc.cn/Article/details/gtjcssggad.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xylfe.cn/Article/details/gtarvinvmc.html

[R33] 捕获错误并提示行号
来源：http://dali.gaohongyu789.top/Article/details/gtdmnyefez.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yonumen.top/Article/details/gtscgenyrq.html

[R34] 退出时清理
来源：http://dali.jqgfzy.top/Article/details/gtedtmzcvp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gtrhsccjxk.html

[R35] 后台执行并等待
来源：http://dali.yuanzhike.top/Article/details/gtbcrhvjfy.html


<!-- 参考信息 -->