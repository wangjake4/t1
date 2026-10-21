代发 wailian999

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.haohaochexian.top/Article/details/gtcenwsrlc.html

C#:   if (x is null) {}
来源：http://dali.yj20258888.top/Article/details/gtkzakowxb.html

[P07] 防抖与节流
来源：http://dali.guannengcc.top/Article/details/gttzjunqbj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.birdmap.top/Article/details/gtsvvugyvd.html

PHP:  // 手写时间戳比较
来源：http://dali.sufxvd.cn/Article/details/gtlitqqeki.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gtxatnrebk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gttajvarzh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hfpthk.cn/Article/details/gtnwobhwzk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shuidangran.top/Article/details/gtzvsolppe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigfzy.top/Article/details/gtdfikaoab.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daria6918.cn/Article/details/gtdozpzpbx.html

[P08] 处理浮点精度问题
来源：http://dali.xziqi.cn/Article/details/gtgjdpfsjw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.mhx1999.top/Article/details/gtiogsfkjp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sufxvd.cn/Article/details/gtxzqfdeav.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.aibaodan.cn/Article/details/gtrwajacua.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.redwolf501.top/Article/details/gtacifossg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzigsmln.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xuetiantiany.cn/Article/details/gtglfrijad.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zycfv.cn/Article/details/gtyxmrthoz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqwimngs.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtrofkfffn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ehwqpu.com/Article/details/gtlzrvszmh.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtobbdcbzw.html

[Q01] 创建表
来源：http://dali.nanxinkj.top/Article/details/gttmkwyepr.html

CREATE TABLE users (
来源：http://dali.ivvv.top/Article/details/gtoctcqsfh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuxming.cn/Article/details/gteennywwq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.feifeiyinyue.top/Article/details/gtvawjmclb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xinyue.icu/Article/details/gtnjescxac.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.feifeiyinyue.top/Article/details/gtobadicvn.html

);
来源：http://dali.havefunace.top/Article/details/gtyrooceyd.html

[Q02] 创建带外键的表
来源：http://dali.yanxiufei.cn/Article/details/gtinvgtzmc.html

CREATE TABLE orders (
来源：http://dali.hammf.cn/Article/details/gtgyqnzlcg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxuanxn.top/Article/details/gtvvolvgro.html

user_id INT NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gtxkfvhjop.html

amount DECIMAL(10, 2),
来源：http://dali.redwolf501.top/Article/details/gttryrihqc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.guowangkeji.top/Article/details/gttdmooglc.html

);
来源：http://dali.dianchejie.cn/Article/details/gtbpqqzidy.html

[Q03] 增加列
来源：http://dali.shangyingyoupin.top/Article/details/gtvzhybasq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hfpthk.cn/Article/details/gtgrvbglew.html

[Q04] 修改列类型
来源：http://dali.redwolf501.top/Article/details/gtjqtvfrsn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenlongwang.top/Article/details/gtqnpqjque.html

[Q05] 重命名列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtisorurun.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gtktnfnpvf.html

[Q06] 删除列
来源：http://dali.dianchejie.cn/Article/details/gtpmvucuuo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.haohaochexian.top/Article/details/gtbwxsuqef.html

[Q07] 删除表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttsjjiico.html

DROP TABLE IF EXISTS orders;
来源：http://dali.fzhhl.top/Article/details/gtvppiqkmu.html

[Q08] 创建普通索引
来源：http://dali.yuanzhike.top/Article/details/gtznjilzhk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yangfankeji.com/Article/details/gtqydbcjha.html

[Q09] 创建唯一索引
来源：http://dali.ppjwa.cn/Article/details/gtbfblbwge.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tianlin.xyz/Article/details/gtskkhprbb.html

[Q10] 插入单行
来源：http://dali.yueranfly.top/Article/details/gtqficzcmt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtdexfwvbm.html

[Q11] 一次插入多行
来源：http://dali.snrcjt.cn/Article/details/gtaxfwguin.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.daxiang520.top/Article/details/gtkoayssgn.html

[Q12] 插入后取自增 ID
来源：http://dali.tian-w.cn/Article/details/gtidyaguge.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hfpthk.cn/Article/details/gttkebbpwd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cheryme.top/Article/details/gtmzuxnnge.html

[Q13] 忽略重复插入
来源：http://dali.chenlongwang.top/Article/details/gtqxkwrepc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenzaomai.com/Article/details/gthdiuzwmv.html

[Q14] 存在则更新（upsert）
来源：http://dali.dashuyun.cn/Article/details/gtsjimluyc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.316326.xyz/Article/details/gtuwzyrtoo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.meibo888.top/Article/details/gtwsotpplj.html

[Q15] 查询全部
来源：http://dali.bjfxy.top/Article/details/gtnzmaokok.html

SELECT * FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdsuvezbe.html

[Q16] 查询指定列
来源：http://dali.zhengqikj.top/Article/details/gtwbxuedmq.html

SELECT id, name FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtfmpvrowb.html

[Q17] 条件查询
来源：http://dali.redwolf501.top/Article/details/gtpsuneknx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtxzozacao.html

[Q18] 模糊匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtuogugwzj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.smart0.xyz/Article/details/gtdcatrbkj.html

[Q19] 范围查询
来源：http://dali.jqgfzy.top/Article/details/gtyniqfkmn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.kuanghao11.cn/Article/details/gtqygekyjz.html

[Q20] IN 列表
来源：http://dali.sysykeji.top/Article/details/gtzpjvvdin.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuanzhike.top/Article/details/gtpqnjzpqc.html

[Q21] 空值判断
来源：http://dali.zycfv.cn/Article/details/gtzgafkpzr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.iojbl.cn/Article/details/gtelvmcajz.html

[Q22] 排序
来源：http://dali.guannengcc.top/Article/details/gtinlsoewa.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.0kj1m.cn/Article/details/gtmtynozjp.html

[Q23] 分页
来源：http://dali.sysykeji.top/Article/details/gtbqnxmhsi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.wangshuangyany.cn/Article/details/gtyisxqwpg.html

[Q24] 去重
来源：http://dali.kuanghao11.cn/Article/details/gtztwllwni.html

SELECT DISTINCT city FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtadfttiev.html

[Q25] 只取前 N 条
来源：http://dali.jyoumei.cn/Article/details/gtowattxyt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daria6918.cn/Article/details/gtnzxuzewk.html

[Q26] 计数
来源：http://dali.nanxinkj.top/Article/details/gtubbrflqs.html

SELECT COUNT(*) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtzqchmlms.html

[Q27] 条件计数
来源：http://dali.hnqzz.top/Article/details/gtesgsktap.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.pycfn.com/Article/details/gtaaqazaor.html

[Q28] 求和与平均
来源：http://dali.xuanzx.com/Article/details/gtokksyvar.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gttkavmtrw.html

[Q29] 最大最小值
来源：http://dali.vqdsnc.cn/Article/details/gtyzuqvqwm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtqlpgynra.html

[Q30] 分组统计
来源：http://dali.redwolf501.top/Article/details/gtsuoyjjhv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjetyxue.html

[Q31] 分组后过滤
来源：http://dali.tianlin.xyz/Article/details/gtftovlbha.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.guowangkeji.top/Article/details/gtjfcyykye.html

[Q32] 分组拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtnlpcrabq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gtckhqttsh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangshuangyany.cn/Article/details/gtiviqsmlf.html

[Q33] 多列分组
来源：http://dali.fzhhl.top/Article/details/gthdvfacym.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aizwys.cn/Article/details/gtkbxcokub.html

[Q34] 每组取第一条
来源：http://dali.hysaishi.cn/Article/details/gtdscflvqs.html

SELECT * FROM (
来源：http://dali.gzhubu.top/Article/details/gtnpjgfqqv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yuxming.cn/Article/details/gtbyhkmqsm.html

) t WHERE rn = 1;
来源：http://dali.tian-w.cn/Article/details/gtrathhafi.html

[Q35] 内连接
来源：http://dali.birdmap.top/Article/details/gthayfhryz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gtrrnxblnt.html

[Q36] 左连接
来源：http://dali.chenlongwang.top/Article/details/gtkismmlag.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gtxklgdqxm.html

[Q37] 右连接
来源：http://dali.sweek.top/Article/details/gtsxbmitdb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.feifeiyinyue.top/Article/details/gtiyhrcxyz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yangfankeji.com/Article/details/gtphivbkwu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.smart0.xyz/Article/details/gtnulutorj.html

[Q39] 自连接（查上下级）
来源：http://dali.yvedp.cn/Article/details/gtptmqnqvi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cashguo.top/Article/details/gtyfdlswei.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hammf.cn/Article/details/gtvomvggtn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hnqzz.top/Article/details/gtsrxegspo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvpzjkasi.html

[Q41] 多表连接
来源：http://dali.pycfn.com/Article/details/gtzzuvszwx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jyoumei.cn/Article/details/gtjxxvbwmn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fengsongda.top/Article/details/gtrpxpyeyb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenlongwang.top/Article/details/gtutoeuzit.html

[Q42] 连接条件附加过滤
来源：http://dali.yanxiufei.cn/Article/details/gteundgtoe.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnxiangtu.top/Article/details/gtvdgdobpn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gotoacloud.top/Article/details/gthssnckju.html

[Q43] 标量子查询
来源：http://dali.316326.xyz/Article/details/gtnbcabuqv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hongshengwenyu.top/Article/details/gtbxutdcke.html

[Q44] IN 子查询
来源：http://dali.jianghu66.top/Article/details/gtuukwukoc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sysykeji.top/Article/details/gtruqhrjsb.html

[Q45] EXISTS 判断存在
来源：http://dali.svipenyu.cn/Article/details/gtgpvmshdo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.meibo888.top/Article/details/gtkmkjtzek.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ybcxt.top/Article/details/gtkvmtrshc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gtnfpvlgbm.html

[Q47] 与平均值比较
来源：http://dali.ydzc1.top/Article/details/gtzbnbsepq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hywenlv.cn/Article/details/gtsifllqdx.html

[Q48] CTE 公用表表达式
来源：http://dali.sysykeji.top/Article/details/gtgqqxkylu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jqgufenzy.top/Article/details/gtuxkvhqym.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yonumen.top/Article/details/gtofrlbvje.html

[Q49] 更新单行
来源：http://dali.vqdsnc.cn/Article/details/gtvtfxyubg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgfzy.top/Article/details/gtgztxckzp.html

[Q50] 批量更新
来源：http://dali.jinqigfzy.top/Article/details/gtlcypuoql.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ehwqpu.com/Article/details/gthewnqnie.html

[Q51] 用子查询更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqlhphliq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sweek.top/Article/details/gtopvqsvus.html

[Q52] 删除指定行
来源：http://dali.guowangkeji.top/Article/details/gtgsyvjypv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jianghu66.top/Article/details/gtwuhfdimm.html

[Q53] 按条件删除
来源：http://dali.yj20258.top/Article/details/gtfjseieml.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gogol.net.cn/Article/details/gtbonnbmhz.html

[Q54] 清空表
来源：http://dali.shangyingyoupin.top/Article/details/gtnctwfvww.html

TRUNCATE TABLE logs;
来源：http://dali.xylfe.cn/Article/details/gtdddnnmnu.html

[Q55] 排名（并列占位）
来源：http://dali.aizwys.cn/Article/details/gtrjiqxjnt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zycfv.cn/Article/details/gthxliljsk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guannengcc.top/Article/details/gtzzxtvzak.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ydzc1.top/Article/details/gtwdubnsps.html

[Q57] 行号
来源：http://dali.yangfankeji.com/Article/details/gtgalnqyue.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtqdegernu.html

[Q58] 累计求和
来源：http://dali.chenjidiqi.icu/Article/details/gtdsksvtsg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.316326.xyz/Article/details/gtwodfjbix.html

[Q59] 分组内累计
来源：http://dali.yueranfly.top/Article/details/gtpjkmwbsu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtxfpspplj.html

[Q60] 取上一行 / 下一行
来源：http://dali.9152youxi.cn/Article/details/gtrrtafbzd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daxiang520.top/Article/details/gtpbbiwihc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gttlidrwcx.html

[Q61] 移动平均
来源：http://dali.hongshengwenyu.top/Article/details/gtykeiyqhl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtqerjjwru.html

[Q62] 分组占比
来源：http://dali.hongshengwenyu.top/Article/details/gtcuthnnld.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gtsbwtkjsh.html

[Q63] 开启事务
来源：http://dali.0kj1m.cn/Article/details/gtgwlipxdb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zdqjudy.top/Article/details/gtoeqisefz.html

[Q64] 提交事务
来源：http://dali.bjfxy.top/Article/details/gtlriwapeo.html

COMMIT;
来源：http://dali.snrcjt.cn/Article/details/gtprgznwgz.html

[Q65] 回滚事务
来源：http://dali.havefunace.top/Article/details/gtlalnucpk.html

ROLLBACK;
来源：http://dali.cqqwz.cn/Article/details/gtbozeuqag.html

[Q66] 行锁查询
来源：http://dali.jiagoushi.top/Article/details/gtbixjnfni.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenjidiqi.icu/Article/details/gtuwryjkcl.html

[Q67] 设置隔离级别
来源：http://dali.wangshuangyany.cn/Article/details/gttwinuolx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hfpthk.cn/Article/details/gtckvnhpnr.html

[Q68] 保存点
来源：http://dali.jqgfzy.top/Article/details/gtylcabqev.html

SAVEPOINT sp1;
来源：http://dali.xuetiantiany.cn/Article/details/gterdzpwgs.html

ROLLBACK TO sp1;
来源：http://dali.316326.xyz/Article/details/gttqrkhhsj.html

[Q69] 查看执行计划
来源：http://dali.ybcxt.top/Article/details/gtdeviosyt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xinyue.icu/Article/details/gtdylhznoh.html

[Q70] 更新统计信息
来源：http://dali.wangshuangyany.cn/Article/details/gtjuwaefaj.html

ANALYZE TABLE users;
来源：http://dali.bjfxy.top/Article/details/gtrtzdqmwv.html

[Q71] 查看建表语句
来源：http://dali.ehwqpu.com/Article/details/gtvbqdpqsr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jyoumei.cn/Article/details/gttewfndph.html

[Q72] 查看索引
来源：http://dali.yj20258888.top/Article/details/gtvjvtfsza.html

SHOW INDEX FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtnoralbud.html

[Q73] 查看表状态
来源：http://dali.gotoacloud.top/Article/details/gtnslepdun.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuxming.cn/Article/details/gtrcqpcrgo.html

[Q74] 强制使用索引
来源：http://dali.xziqi.cn/Article/details/gtdsupwqks.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gaohongyu789.top/Article/details/gtnynzlext.html

[Q75] 日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gtkfghqkmh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtphnirbfx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinqigfzy.top/Article/details/gtgmadabtu.html

[Q76] 按天统计
来源：http://dali.316326.xyz/Article/details/gtejdoweic.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhongyouzk.top/Article/details/gtqzpaydie.html

[Q77] 时间加减
来源：http://dali.yuanzhike.top/Article/details/gtxkiitmql.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.havefunace.top/Article/details/gtxsytkfmg.html

[Q78] 当前时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiajfsspt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.vqdsnc.cn/Article/details/gtpqjwjmhj.html

[Q79] 字符串拼接
来源：http://dali.shuidangran.top/Article/details/gtkhutamiu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xuetiantiany.cn/Article/details/gtxprlmhrv.html

[Q80] 字符串截取
来源：http://dali.xinyue.icu/Article/details/gtubcuytwh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sweek.top/Article/details/gtsadngagn.html

[Q81] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gtqihugsxq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.bjfxy.top/Article/details/gtfxsdlfbi.html

[Q82] 字符长度与字节长度
来源：http://dali.gogol.net.cn/Article/details/gtmrnpumsa.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtzhpvsjzh.html

[Q83] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gtqkcawxat.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gthpmsrluk.html

[Q84] 去除首尾空格
来源：http://dali.sweek.top/Article/details/gtthgtnnvt.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtmxkettoi.html

[Q85] 数值取整
来源：http://dali.chenjidiqi.icu/Article/details/gtqxjvcdwx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hfpthk.cn/Article/details/gtzthykohu.html

[Q86] 读取 JSON 字段
来源：http://dali.redwolf501.top/Article/details/gtcojwnsme.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258888.top/Article/details/gtrdlkdpkz.html

[Q87] JSON 字段做条件
来源：http://dali.wangshuangyany.cn/Article/details/gtvqohhpkl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yueranfly.top/Article/details/gttdvmjopq.html

[Q88] 行转列（条件聚合）
来源：http://dali.gotoacloud.top/Article/details/gtwweuenze.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jiagoushi.top/Article/details/gtovrwlqxl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtkvsaebfr.html

[Q89] 判断表是否存在
来源：http://dali.bjfxy.top/Article/details/gtfgngamod.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daxiang520.top/Article/details/gtqepbtbio.html

[Q90] 生成序号列
来源：http://dali.xinyue.icu/Article/details/gtmomfqscm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.0kj1m.cn/Article/details/gtcvezceqn.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtrkfbfqrq.html

R. Bash 专题
来源：http://dali.tanke756.top/Article/details/gtxljfcnkt.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtujutsrfc.html

[R01] shebang 与严格模式
来源：http://dali.svipenyu.cn/Article/details/gtipjvofwt.html

#!/usr/bin/env bash
来源：http://dali.zhiwuduotai.top/Article/details/gtvkozxpbb.html

set -euo pipefail
来源：http://dali.9152youxi.cn/Article/details/gtdivnfrkr.html

[R02] 变量赋值与使用
来源：http://dali.feifeiyinyue.top/Article/details/gtoyifohlt.html

name="Tom"; echo "$name"
来源：http://dali.jqgfzy.top/Article/details/gthpyqfski.html

[R03] 只读变量
来源：http://dali.gaohongyu789.top/Article/details/gtkqorpvgv.html

readonly PI=3.14
来源：http://dali.cdnleiting.top/Article/details/gtbtwoowpo.html

[R04] 位置参数
来源：http://dali.sysykeji.top/Article/details/gtqlozwslr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yanxiufei.cn/Article/details/gtudxjkjvc.html

[R05] 参数默认值
来源：http://dali.cdnleiting.top/Article/details/gtwyusradr.html

name="${1:-default}"
来源：http://dali.jinqigufen.top/Article/details/gtovdtdpjc.html

[R06] 判断命令是否存在
来源：http://dali.svipenyu.cn/Article/details/gtrjirjjqm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtiryxqxbt.html

[R07] if 判断文件
来源：http://dali.0kj1m.cn/Article/details/gtsljxrynw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtmamoejna.html

[R08] 数值比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtxssnowlu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gtpplcfqbr.html

[R09] 字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gtbjrmcntp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yongpay.top/Article/details/gtgfcqguim.html

[R10] 正则匹配
来源：http://dali.aizwys.cn/Article/details/gtnshkpyoc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjusmqnmt.html

[R11] case 多分支
来源：http://dali.aizwys.cn/Article/details/gtkvhnvyyr.html

case "$1" in
来源：http://dali.yvedp.cn/Article/details/gtwqbswcrb.html

start) echo "启动" ;;
来源：http://dali.tanke756.top/Article/details/gtvamikmiu.html

stop)  echo "停止" ;;
来源：http://dali.0kj1m.cn/Article/details/gtfadhgpvn.html

*)     echo "未知命令" ;;
来源：http://dali.yj20258888.top/Article/details/gtnzoxfadl.html

esac
来源：http://dali.hnqzz.top/Article/details/gtisdgchza.html

[R12] for 遍历文件
来源：http://dali.snrcjt.cn/Article/details/gtalifovac.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cucudq.cn/Article/details/gtdgeekkaw.html

[R13] for 计数循环
来源：http://dali.yanxiufei.cn/Article/details/gtemwleaqj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gtynjlovzu.html

[R14] C 风格 for
来源：http://dali.gzhubu.top/Article/details/gtzewajxvz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gthtgmqvln.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtjigyvgwv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.c1oappe.top/Article/details/gtejfkwssn.html

[R16] until 等待条件
来源：http://dali.yanxiufei.cn/Article/details/gtaoahjcuk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.bjfxy.top/Article/details/gtyydbnshh.html

[R17] 数组定义与取值
来源：http://dali.wangshuangyany.cn/Article/details/gtlmvogtze.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.quarkkingdee.top/Article/details/gtfieiwoyi.html

[R18] 遍历数组
来源：http://dali.svipenyu.cn/Article/details/gthjktwlca.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yuanzhike.top/Article/details/gtpeowvytc.html

[R19] 数组长度
来源：http://dali.tian-w.cn/Article/details/gtmlognmjq.html

echo "${#arr[@]}"
来源：http://dali.tanke756.top/Article/details/gtmvrblude.html

[R20] 关联数组（字典）
来源：http://dali.yuanzhike.top/Article/details/gtuuhmoafj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgfzy.top/Article/details/gtdlnpmets.html

[R21] 字符串长度
来源：http://dali.cqqwz.cn/Article/details/gtklwgceei.html

echo "${#s}"
来源：http://dali.aibaodan.cn/Article/details/gtmazfquji.html

[R22] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gtuxqiyozi.html

echo "${s:0:5}"
来源：http://dali.sxryk.cn/Article/details/gtxdwrkecf.html

[R23] 字符串替换
来源：http://dali.dashuyun.cn/Article/details/gtuksiuila.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj20258.top/Article/details/gtmvcdrhbu.html

[R24] 大小写转换
来源：http://dali.hnxiangtu.top/Article/details/gtbpqdwzww.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sysykeji.top/Article/details/gtadettpli.html

[R25] 去后缀 / 去前缀
来源：http://dali.ydzc1.top/Article/details/gthwozqnqq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.smart0.xyz/Article/details/gtkbfaausd.html

[R26] 命令替换
来源：http://dali.chenjidiqi.icu/Article/details/gtuehzqssf.html

now=$(date +%F); echo "$now"
来源：http://dali.redwolf501.top/Article/details/gtywjtgpwf.html

[R27] 算术展开
来源：http://dali.xuetiantiany.cn/Article/details/gtwxkzokeh.html

echo $((1 + 2 * 3))
来源：http://dali.vqdsnc.cn/Article/details/gtnddiwwee.html

[R28] 浮点运算
来源：http://dali.snrcjt.cn/Article/details/gtrdfplykw.html

echo "scale=2; 10/3" | bc
来源：http://dali.fzhhl.top/Article/details/gtsyzetuvg.html

[R29] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxmduehn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjepqfozt.html

[R30] 函数返回状态码
来源：http://dali.hammf.cn/Article/details/gtphajssmr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfpwwget.html

[R31] 局部变量
来源：http://dali.316326.xyz/Article/details/gthllgnmrj.html

f() { local x=1; echo "$x"; }
来源：http://dali.tian-w.cn/Article/details/gtsdtqwmjz.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqmcsbal.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.9152youxi.cn/Article/details/gtgaxgrtfb.html

[R33] 捕获错误并提示行号
来源：http://dali.chenzaomai.com/Article/details/gtgnyjtqyh.html


<!-- 参考信息 -->