代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.jqgufenzy.top/Article/details/gtatgngzfc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xinyue.icu/Article/details/gtlcsbbjgu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuxming.cn/Article/details/gtjyasmkrn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtjddqhefm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.quarkkingdee.top/Article/details/gtvgnrmlbe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hfpthk.cn/Article/details/gtxyzmqxxu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.iojbl.cn/Article/details/gtqzivqbqd.html

[P08] 处理浮点精度问题
来源：http://dali.snrcjt.cn/Article/details/gtjclxazts.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhiwuduotai.top/Article/details/gtiiubbnhm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ivvv.top/Article/details/gtuylkujbr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.bjfxy.top/Article/details/gtnlbavual.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gtpsfftylx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.havefunace.top/Article/details/gtmvkinwia.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hysaishi.cn/Article/details/gteqlpvidu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ppjwa.cn/Article/details/gttcpcbqsw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ydzc1.top/Article/details/gtedplgggo.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtbxcxjxsy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yangfankeji.com/Article/details/gtjqcxloph.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtlfpnuknf.html

[Q01] 创建表
来源：http://dali.jqgufenzy.top/Article/details/gtrwtejbyq.html

CREATE TABLE users (
来源：http://dali.xylfe.cn/Article/details/gthgjygxzs.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gtqudtpnfc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gotoacloud.top/Article/details/gtjkxzpixe.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sxryk.cn/Article/details/gtsoglcyla.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jqgufenzy.top/Article/details/gtqmprgoaw.html

);
来源：http://dali.zhongyouzk.top/Article/details/gtrgbqwieo.html

[Q02] 创建带外键的表
来源：http://dali.guowangkeji.top/Article/details/gthfefpvpx.html

CREATE TABLE orders (
来源：http://dali.shzxlz.cn/Article/details/gtsouspfph.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yanxiufei.cn/Article/details/gtzzxeywbe.html

user_id INT NOT NULL,
来源：http://dali.guannengcc.top/Article/details/gtwacwpthj.html

amount DECIMAL(10, 2),
来源：http://dali.xuanzx.com/Article/details/gtatbflaze.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cqqwz.cn/Article/details/gtfbxawmjq.html

);
来源：http://dali.jqgfzy.top/Article/details/gtajhomdxo.html

[Q03] 增加列
来源：http://dali.jinqigfzy.top/Article/details/gtxrftmgeo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj202588.top/Article/details/gtumcwvxxl.html

[Q04] 修改列类型
来源：http://dali.ybcxt.top/Article/details/gtqulgixws.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yueranfly.top/Article/details/gtipdovytn.html

[Q05] 重命名列
来源：http://dali.tianlin.xyz/Article/details/gtwwezjrbi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yonumen.top/Article/details/gtsgglbgah.html

[Q06] 删除列
来源：http://dali.mhx1999.top/Article/details/gtyiwzbywi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hywenlv.cn/Article/details/gtevhjpbtd.html

[Q07] 删除表
来源：http://dali.zhongyouzk.top/Article/details/gtedeuyryl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tian-w.cn/Article/details/gtvzwkpyso.html

[Q08] 创建普通索引
来源：http://dali.nanxuanxn.top/Article/details/gtsfmshgwq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nwbrower.top/Article/details/gtfxaupeoj.html

[Q09] 创建唯一索引
来源：http://dali.fzhhl.top/Article/details/gttcgwvzfh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gtntnpclld.html

[Q10] 插入单行
来源：http://dali.jyoumei.cn/Article/details/gtlsqbhqvm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gtpaowsmkv.html

[Q11] 一次插入多行
来源：http://dali.feifeiyinyue.top/Article/details/gtltxmovga.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cdnleiting.top/Article/details/gtytuwhejj.html

[Q12] 插入后取自增 ID
来源：http://dali.yj202588.top/Article/details/gtsafxxnqq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cqqwz.cn/Article/details/gtaccywyec.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hnxiangtu.top/Article/details/gtjbuxkcud.html

[Q13] 忽略重复插入
来源：http://dali.sxryk.cn/Article/details/gttvbjydqr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.meibo888.top/Article/details/gtjynfllkd.html

[Q14] 存在则更新（upsert）
来源：http://dali.guannengcc.top/Article/details/gtykctutky.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hysaishi.cn/Article/details/gtevttvthi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jlsjyb.cn/Article/details/gtkpkkmaju.html

[Q15] 查询全部
来源：http://dali.hongshengwenyu.top/Article/details/gtvzpxjplg.html

SELECT * FROM users;
来源：http://dali.mhx1999.top/Article/details/gtqwlgyqff.html

[Q16] 查询指定列
来源：http://dali.nanxuanxn.top/Article/details/gtrpnfcsox.html

SELECT id, name FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtcfnalzwk.html

[Q17] 条件查询
来源：http://dali.pycfn.com/Article/details/gtbyrmbpwz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthmxeteu.html

[Q18] 模糊匹配
来源：http://dali.9152youxi.cn/Article/details/gtxnfsfuai.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj20258.top/Article/details/gtfmdjdqja.html

[Q19] 范围查询
来源：http://dali.yvedp.cn/Article/details/gthmzcuohj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.0kj1m.cn/Article/details/gtwrxszopo.html

[Q20] IN 列表
来源：http://dali.shuidangran.top/Article/details/gtxfhyiaqx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sysykeji.top/Article/details/gtbbqbbasv.html

[Q21] 空值判断
来源：http://dali.kuanghao11.cn/Article/details/gtxwynqgms.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhixingplan.top/Article/details/gtnheijctu.html

[Q22] 排序
来源：http://dali.feifeiyinyue.top/Article/details/gthkpeohvf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.dianchejie.cn/Article/details/gtciytwzbi.html

[Q23] 分页
来源：http://dali.jinghuilouyu.cn/Article/details/gttxboljne.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ybcxt.top/Article/details/gtgwudnrcz.html

[Q24] 去重
来源：http://dali.jiagoushi.top/Article/details/gtlotjxhjh.html

SELECT DISTINCT city FROM users;
来源：http://dali.hammf.cn/Article/details/gtgfhlakfo.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gtguvbtvds.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jiagoushi.top/Article/details/gtqagipcuk.html

[Q26] 计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhwzwlgo.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtmadsenej.html

[Q27] 条件计数
来源：http://dali.jyoumei.cn/Article/details/gtxnbhqruo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtdropqydd.html

[Q28] 求和与平均
来源：http://dali.kuanghao11.cn/Article/details/gtxcntesca.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtrjsywlvo.html

[Q29] 最大最小值
来源：http://dali.guowangkeji.top/Article/details/gtdsdrhsdm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtrjxebjoy.html

[Q30] 分组统计
来源：http://dali.ydzc1.top/Article/details/gtjqdpnmmx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpcrryqn.html

[Q31] 分组后过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqhyuzqv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yuxming.cn/Article/details/gtxvjawnem.html

[Q32] 分组拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtkqpwobai.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gtaahzkxrv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nanxuanxn.top/Article/details/gtrntopoho.html

[Q33] 多列分组
来源：http://dali.shzxlz.cn/Article/details/gtxoqpnteq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.daxiang520.top/Article/details/gtpmkrjycy.html

[Q34] 每组取第一条
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwpczcwq.html

SELECT * FROM (
来源：http://dali.316326.xyz/Article/details/gtuxafnkcx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jqgfzy.top/Article/details/gteyipqsmv.html

) t WHERE rn = 1;
来源：http://dali.sxryk.cn/Article/details/gtehodwtnj.html

[Q35] 内连接
来源：http://dali.quarkkingdee.top/Article/details/gtyrpkbsko.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258888.top/Article/details/gtrjbyzssb.html

[Q36] 左连接
来源：http://dali.0kj1m.cn/Article/details/gtvmxnpzup.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yongpay.top/Article/details/gtagwmgkxk.html

[Q37] 右连接
来源：http://dali.dashuyun.cn/Article/details/gtvonyscpi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tianlin.xyz/Article/details/gtbpzsirat.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.9152youxi.cn/Article/details/gteqlloosp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hongshengwenyu.top/Article/details/gtgcdnuxol.html

[Q39] 自连接（查上下级）
来源：http://dali.yonumen.top/Article/details/gtoqoabqsj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.andypj.xyz/Article/details/gtgyindchn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.snrcjt.cn/Article/details/gttsumnoal.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yuxming.cn/Article/details/gtbspdewrn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tian-w.cn/Article/details/gtffstjobj.html

[Q41] 多表连接
来源：http://dali.vqdsnc.cn/Article/details/gtxohhnhom.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nanxuanxn.top/Article/details/gthablswwa.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaczjqsbr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yanxiufei.cn/Article/details/gtkfqwaewl.html

[Q42] 连接条件附加过滤
来源：http://dali.dianchejie.cn/Article/details/gtwcukbpke.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhiwuduotai.top/Article/details/gtaypveufj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hammf.cn/Article/details/gtvkvsgjqp.html

[Q43] 标量子查询
来源：http://dali.xuanzx.com/Article/details/gtdtisxiac.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.wangdashe.top/Article/details/gtqnwojlkd.html

[Q44] IN 子查询
来源：http://dali.hnqzz.top/Article/details/gttwdhyfwl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tian-w.cn/Article/details/gtwqbuldcs.html

[Q45] EXISTS 判断存在
来源：http://dali.tianlin.xyz/Article/details/gtiqrnkvep.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.kuanghao11.cn/Article/details/gtfkcabteb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.kuanghao11.cn/Article/details/gtkhmsqggf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fengsongda.top/Article/details/gthtcrlzhw.html

[Q47] 与平均值比较
来源：http://dali.guowangkeji.top/Article/details/gtwxupcnys.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fengsongda.top/Article/details/gtgtmleylt.html

[Q48] CTE 公用表表达式
来源：http://dali.pengpengdd.cyou/Article/details/gtdwpwzarv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jlsjyb.cn/Article/details/gtsnjnwcql.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aibaodan.cn/Article/details/gturihabdd.html

[Q49] 更新单行
来源：http://dali.havefunace.top/Article/details/gtradudhke.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gtpqozyplp.html

[Q50] 批量更新
来源：http://dali.cqqwz.cn/Article/details/gteqsbjlyo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.meibo888.top/Article/details/gtrnxfkqiy.html

[Q51] 用子查询更新
来源：http://dali.jinqigufen.top/Article/details/gtepyemiya.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtbfhvyxlf.html

[Q52] 删除指定行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyunqlwgc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sweek.top/Article/details/gtarrecdaj.html

[Q53] 按条件删除
来源：http://dali.zdqjudy.top/Article/details/gtvljylino.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gtzbwfflzx.html

[Q54] 清空表
来源：http://dali.jqgufenzy.top/Article/details/gttswsakqq.html

TRUNCATE TABLE logs;
来源：http://dali.xinyue.icu/Article/details/gtoihnxwjj.html

[Q55] 排名（并列占位）
来源：http://dali.aizwys.cn/Article/details/gtknljjeha.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.wangdashe.top/Article/details/gtcgnnwsfj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangdashe.top/Article/details/gtkygsiyli.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjknzfahl.html

[Q57] 行号
来源：http://dali.yongpay.top/Article/details/gtvxkbjkyc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tianlin.xyz/Article/details/gthdqdnsxh.html

[Q58] 累计求和
来源：http://dali.sweek.top/Article/details/gtuctcxczz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gttzlmlkcn.html

[Q59] 分组内累计
来源：http://dali.yuanzhike.top/Article/details/gtexfdydzi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtixalsero.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj20258888.top/Article/details/gtyadcdddr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cheryme.top/Article/details/gttqgkuyco.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtnfzmvuil.html

[Q61] 移动平均
来源：http://dali.gaohongyu789.top/Article/details/gtlwtxnovx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtzcbehixc.html

[Q62] 分组占比
来源：http://dali.gaohongyu789.top/Article/details/gtxxemowrj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gtswbmukch.html

[Q63] 开启事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiduuwyyf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.316326.xyz/Article/details/gtiyeomrjo.html

[Q64] 提交事务
来源：http://dali.zhiwuduotai.top/Article/details/gtgzurbupa.html

COMMIT;
来源：http://dali.hywenlv.cn/Article/details/gtxnsrurdr.html

[Q65] 回滚事务
来源：http://dali.yj202588.top/Article/details/gtxmyiinab.html

ROLLBACK;
来源：http://dali.chenzaomai.com/Article/details/gtzshkazku.html

[Q66] 行锁查询
来源：http://dali.cdnleiting.top/Article/details/gtrobudrrd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shangyingyoupin.top/Article/details/gtntrxcsik.html

[Q67] 设置隔离级别
来源：http://dali.sysykeji.top/Article/details/gtzqdiixwo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.guowangkeji.top/Article/details/gtdmsyhbfi.html

[Q68] 保存点
来源：http://dali.xuetiantiany.cn/Article/details/gttueyagfk.html

SAVEPOINT sp1;
来源：http://dali.tianlin.xyz/Article/details/gthgedycod.html

ROLLBACK TO sp1;
来源：http://dali.sweek.top/Article/details/gtdjsupitu.html

[Q69] 查看执行计划
来源：http://dali.chenzaomai.com/Article/details/gtoclunnzr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhengqikj.top/Article/details/gtzjiidcmd.html

[Q70] 更新统计信息
来源：http://dali.xinyue.icu/Article/details/gtqbsiziuf.html

ANALYZE TABLE users;
来源：http://dali.smart0.xyz/Article/details/gtqzfhoqxi.html

[Q71] 查看建表语句
来源：http://dali.jianghu66.top/Article/details/gtefuivogb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zdqjudy.top/Article/details/gtlfstwgms.html

[Q72] 查看索引
来源：http://dali.ybcxt.top/Article/details/gtqnhpjlwx.html

SHOW INDEX FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtinmzytkr.html

[Q73] 查看表状态
来源：http://dali.xziqi.cn/Article/details/gtlbqyldoo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gtjwzfddwm.html

[Q74] 强制使用索引
来源：http://dali.vqdsnc.cn/Article/details/gtxdqokony.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yuxming.cn/Article/details/gtedwhztuq.html

[Q75] 日期格式化
来源：http://dali.aibaodan.cn/Article/details/gtyieqotnn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtwxzgslrm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenzaomai.com/Article/details/gtkzdmabbk.html

[Q76] 按天统计
来源：http://dali.yonumen.top/Article/details/gtwvxigqpt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gogol.net.cn/Article/details/gtolftseqy.html

[Q77] 时间加减
来源：http://dali.jqgfzy.top/Article/details/gtrxoahaal.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jianghu66.top/Article/details/gttssfgziu.html

[Q78] 当前时间
来源：http://dali.jqgfzy.top/Article/details/gtpwqopuur.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hnxiangtu.top/Article/details/gtmcavwmuz.html

[Q79] 字符串拼接
来源：http://dali.gogol.net.cn/Article/details/gtjtxsouto.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.wangshuangyany.cn/Article/details/gtyxtiqjgf.html

[Q80] 字符串截取
来源：http://dali.jqgfzy.top/Article/details/gtlloxacch.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtfvtouhlf.html

[Q81] 字符串替换
来源：http://dali.xylfe.cn/Article/details/gtsmexzdao.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yvedp.cn/Article/details/gtnrgfikrn.html

[Q82] 字符长度与字节长度
来源：http://dali.c1oappe.top/Article/details/gtfozspccb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtrhawuqiv.html

[Q83] 大小写转换
来源：http://dali.iojbl.cn/Article/details/gteqpkszef.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtelxoxeoh.html

[Q84] 去除首尾空格
来源：http://dali.yj20258.top/Article/details/gtxhadmpxb.html

SELECT TRIM(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gtvmfgxbqm.html

[Q85] 数值取整
来源：http://dali.wangdashe.top/Article/details/gtcxbqickz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shzxlz.cn/Article/details/gtbumvnpdd.html

[Q86] 读取 JSON 字段
来源：http://dali.tian-w.cn/Article/details/gtsubtzinf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigufen.top/Article/details/gtnjrtcalz.html

[Q87] JSON 字段做条件
来源：http://dali.zhoulong.xyz/Article/details/gtrfyuugyj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jlsjyb.cn/Article/details/gtqxfzfiwm.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj20258888.top/Article/details/gtpjuynnku.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shzxlz.cn/Article/details/gtgcppkskv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtcbvwyxvn.html

[Q89] 判断表是否存在
来源：http://dali.redwolf501.top/Article/details/gttxidtdwi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ybcxt.top/Article/details/gtqsjzuwae.html

[Q90] 生成序号列
来源：http://dali.jinqigfzy.top/Article/details/gtnhjfbebm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xinyue.icu/Article/details/gtvplunkbi.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtzwignkku.html

R. Bash 专题
来源：http://dali.tian-w.cn/Article/details/gtgozaabhq.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gteawphxkl.html

[R01] shebang 与严格模式
来源：http://dali.hongshengwenyu.top/Article/details/gtblelyblg.html

#!/usr/bin/env bash
来源：http://dali.shzxlz.cn/Article/details/gtdysdsoad.html

set -euo pipefail
来源：http://dali.gotoacloud.top/Article/details/gtuvyegshw.html

[R02] 变量赋值与使用
来源：http://dali.gotoacloud.top/Article/details/gtgtcyuntv.html

name="Tom"; echo "$name"
来源：http://dali.svipenyu.cn/Article/details/gtnkpmgfhv.html

[R03] 只读变量
来源：http://dali.andypj.xyz/Article/details/gtybgxutgw.html

readonly PI=3.14
来源：http://dali.gaohongyu789.top/Article/details/gtnqdytesk.html

[R04] 位置参数
来源：http://dali.tanke756.top/Article/details/gtezhhrfhx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqisxtuu.html

[R05] 参数默认值
来源：http://dali.9152youxi.cn/Article/details/gtpkpovgln.html

name="${1:-default}"
来源：http://dali.aibaodan.cn/Article/details/gtqvmvafpr.html

[R06] 判断命令是否存在
来源：http://dali.gzhubu.top/Article/details/gtwayuoboj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cheryme.top/Article/details/gtwqmomjwc.html

[R07] if 判断文件
来源：http://dali.316326.xyz/Article/details/gtapzgbtdj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yonumen.top/Article/details/gtccgijuzu.html

[R08] 数值比较
来源：http://dali.haohaochexian.top/Article/details/gtfbngaloc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daxiang520.top/Article/details/gtvcpzzchb.html

[R09] 字符串比较
来源：http://dali.yonumen.top/Article/details/gtcfvojyxi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gogol.net.cn/Article/details/gtqkkgyvui.html

[R10] 正则匹配
来源：http://dali.bjfxy.top/Article/details/gtvmdcbgvc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sufxvd.cn/Article/details/gtydujtvys.html

[R11] case 多分支
来源：http://dali.fzhhl.top/Article/details/gtfhobtobj.html

case "$1" in
来源：http://dali.hongshengwenyu.top/Article/details/gtoodoqemw.html

start) echo "启动" ;;
来源：http://dali.quarkkingdee.top/Article/details/gtdpbozyuo.html

stop)  echo "停止" ;;
来源：http://dali.dashuyun.cn/Article/details/gtlkmrncpa.html

*)     echo "未知命令" ;;
来源：http://dali.xinyue.icu/Article/details/gtjnbopeqe.html

esac
来源：http://dali.jinqigfzy.top/Article/details/gtogsrimpr.html

[R12] for 遍历文件
来源：http://dali.yj20258.top/Article/details/gtjyqiqfae.html

for f in *.txt; do echo "$f"; done
来源：http://dali.smart0.xyz/Article/details/gtubptcbwf.html

[R13] for 计数循环
来源：http://dali.chenlongwang.top/Article/details/gthokqcpib.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hysaishi.cn/Article/details/gtemorzhdh.html

[R14] C 风格 for
来源：http://dali.c1oappe.top/Article/details/gtmqwrzovd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gtvejxqasj.html

[R15] while 逐行读文件
来源：http://dali.316326.xyz/Article/details/gtgcezbjmn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gzhubu.top/Article/details/gtwthbnppm.html

[R16] until 等待条件
来源：http://dali.yongpay.top/Article/details/gtuxrnhpxw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gtzaekqwjc.html

[R17] 数组定义与取值
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdsguobj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hfpthk.cn/Article/details/gtbotdekmr.html

[R18] 遍历数组
来源：http://dali.redwolf501.top/Article/details/gtpkqsyhue.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.fzhhl.top/Article/details/gtmnvwhmti.html

[R19] 数组长度
来源：http://dali.havefunace.top/Article/details/gtzjdsnodf.html

echo "${#arr[@]}"
来源：http://dali.nwbrower.top/Article/details/gttrpfvkxp.html

[R20] 关联数组（字典）
来源：http://dali.ivvv.top/Article/details/gtdhjtbzdu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zycfv.cn/Article/details/gtwzoqxhop.html

[R21] 字符串长度
来源：http://dali.c1oappe.top/Article/details/gtoytoakap.html

echo "${#s}"
来源：http://dali.xziqi.cn/Article/details/gtdenenbiq.html

[R22] 截取子串
来源：http://dali.yonumen.top/Article/details/gtxribrbqt.html

echo "${s:0:5}"
来源：http://dali.jianghu66.top/Article/details/gtuqvlbrzo.html

[R23] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gtftevvkkx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.pycfn.com/Article/details/gtriuhcvni.html

[R24] 大小写转换
来源：http://dali.hfpthk.cn/Article/details/gtoltkvisw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ydzc1.top/Article/details/gtogkjdypk.html

[R25] 去后缀 / 去前缀
来源：http://dali.jianghu66.top/Article/details/gtojfohqrb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.svipenyu.cn/Article/details/gturyhpuqk.html

[R26] 命令替换
来源：http://dali.jinqigfzy.top/Article/details/gtfyznzehq.html

now=$(date +%F); echo "$now"
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrplyjsn.html

[R27] 算术展开
来源：http://dali.jiagoushi.top/Article/details/gtxtyzwcrs.html

echo $((1 + 2 * 3))
来源：http://dali.9152youxi.cn/Article/details/gttukjknwg.html

[R28] 浮点运算
来源：http://dali.mhx1999.top/Article/details/gtwjsanzke.html

echo "scale=2; 10/3" | bc
来源：http://dali.yuanzhike.top/Article/details/gtwjvggtej.html

[R29] 定义函数
来源：http://dali.ivvv.top/Article/details/gthpkvmgjt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258888.top/Article/details/gtunlacmwj.html

[R30] 函数返回状态码
来源：http://dali.chenjidiqi.icu/Article/details/gtpdqhkkkk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hysaishi.cn/Article/details/gtvxguiuxa.html

[R31] 局部变量
来源：http://dali.gogol.net.cn/Article/details/gtbsizypmd.html

f() { local x=1; echo "$x"; }
来源：http://dali.yangfankeji.com/Article/details/gtnwdojuzk.html

[R32] 参数个数校验
来源：http://dali.yvedp.cn/Article/details/gtrdnkgpne.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gtogrdhnry.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgufenzy.top/Article/details/gtqenkzzhf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guowangkeji.top/Article/details/gtwgifkcdh.html

[R34] 退出时清理
来源：http://dali.wangshuangyany.cn/Article/details/gthycsxjmi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ppjwa.cn/Article/details/gtjeyaqnoo.html

[R35] 后台执行并等待
来源：http://dali.ppjwa.cn/Article/details/gtzwchhvvq.html


<!-- 参考信息 -->