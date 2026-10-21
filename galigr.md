代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.yangfankeji.com/Article/details/gtenrnqgme.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gtypwxvbex.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpyvgbcd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenlongwang.top/Article/details/gtvqubbhsr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenlongwang.top/Article/details/gtrshnlkhz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fengsongda.top/Article/details/gtqlcfqjzu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yongpay.top/Article/details/gtntozeurt.html

[P08] 处理浮点精度问题
来源：http://dali.hnxiangtu.top/Article/details/gtpwdytmix.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xuanzx.com/Article/details/gtowqyrksx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xziqi.cn/Article/details/gtliouhjcr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.svipenyu.cn/Article/details/gtaxvhpkiw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtildfiste.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.316326.xyz/Article/details/gtqpymityt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yj20258.top/Article/details/gtayojsube.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jianghu66.top/Article/details/gtippcqdfd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ivvv.top/Article/details/gtlpipzglt.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtghlwevft.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ppjwa.cn/Article/details/gtqrclqjxs.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtbglfmxff.html

[Q01] 创建表
来源：http://dali.jiagoushi.top/Article/details/gtbcjernua.html

CREATE TABLE users (
来源：http://dali.zycfv.cn/Article/details/gtmhmqswke.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gtiafrbjii.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj202588.top/Article/details/gtmamphuof.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hysaishi.cn/Article/details/gtlpgnyxbr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenlongwang.top/Article/details/gtmianmkan.html

);
来源：http://dali.zycfv.cn/Article/details/gtoqficaax.html

[Q02] 创建带外键的表
来源：http://dali.cucudq.cn/Article/details/gtaexbmkoc.html

CREATE TABLE orders (
来源：http://dali.chenjidiqi.icu/Article/details/gtntqqcdwk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ydzc1.top/Article/details/gtcueioyxh.html

user_id INT NOT NULL,
来源：http://dali.hnxiangtu.top/Article/details/gtsfugvjym.html

amount DECIMAL(10, 2),
来源：http://dali.shuidangran.top/Article/details/gtserucazj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dianchejie.cn/Article/details/gtonigurew.html

);
来源：http://dali.guowangkeji.top/Article/details/gtmyqtfxva.html

[Q03] 增加列
来源：http://dali.cheryme.top/Article/details/gtbhdwrnvo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.9152youxi.cn/Article/details/gtenahnzmv.html

[Q04] 修改列类型
来源：http://dali.zhoulong.xyz/Article/details/gttrgyskjo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xziqi.cn/Article/details/gteopysgre.html

[Q05] 重命名列
来源：http://dali.hywenlv.cn/Article/details/gttiaffwzf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ppjwa.cn/Article/details/gtxmdgqcah.html

[Q06] 删除列
来源：http://dali.fzhhl.top/Article/details/gtgsntggnm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ehwqpu.com/Article/details/gthbwqzrtz.html

[Q07] 删除表
来源：http://dali.ivvv.top/Article/details/gtpxhpcita.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aizwys.cn/Article/details/gtwirxyafs.html

[Q08] 创建普通索引
来源：http://dali.cheryme.top/Article/details/gttlzrffqp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmartokk.html

[Q09] 创建唯一索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhjkjjqn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guannengcc.top/Article/details/gthqhwekpc.html

[Q10] 插入单行
来源：http://dali.aizwys.cn/Article/details/gtgdfgvbff.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.birdmap.top/Article/details/gtujdplecr.html

[Q11] 一次插入多行
来源：http://dali.yj20258.top/Article/details/gtyzdhflag.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nanxinkj.top/Article/details/gttwwgmtak.html

[Q12] 插入后取自增 ID
来源：http://dali.aizwys.cn/Article/details/gtltyeyaot.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yongpay.top/Article/details/gternmjzkd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.aizwys.cn/Article/details/gtjqgjosfj.html

[Q13] 忽略重复插入
来源：http://dali.chenjidiqi.icu/Article/details/gtnlbaqmxq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gttasufihh.html

[Q14] 存在则更新（upsert）
来源：http://dali.cqqwz.cn/Article/details/gtliweicxw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.vqdsnc.cn/Article/details/gtyybrqlsb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgufenzy.top/Article/details/gtrhqtbawb.html

[Q15] 查询全部
来源：http://dali.tianlin.xyz/Article/details/gtceuqkngr.html

SELECT * FROM users;
来源：http://dali.xuanzx.com/Article/details/gtgzapcxab.html

[Q16] 查询指定列
来源：http://dali.316326.xyz/Article/details/gtvttxbtef.html

SELECT id, name FROM users;
来源：http://dali.jinqigufen.top/Article/details/gttcbxywex.html

[Q17] 条件查询
来源：http://dali.vqdsnc.cn/Article/details/gtgxeijfbo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigufen.top/Article/details/gtxtrcnrxi.html

[Q18] 模糊匹配
来源：http://dali.meibo888.top/Article/details/gtloeypoam.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sysykeji.top/Article/details/gtaewclzmt.html

[Q19] 范围查询
来源：http://dali.xziqi.cn/Article/details/gtmxvrufsx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cheryme.top/Article/details/gtgnabiija.html

[Q20] IN 列表
来源：http://dali.yuxming.cn/Article/details/gtoyceryhh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgfzy.top/Article/details/gtqbigciog.html

[Q21] 空值判断
来源：http://dali.nanxinkj.top/Article/details/gtvzyhdmxa.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tianlin.xyz/Article/details/gtjbgkbhin.html

[Q22] 排序
来源：http://dali.shangyingyoupin.top/Article/details/gtepdbzoes.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zycfv.cn/Article/details/gtibibxnng.html

[Q23] 分页
来源：http://dali.yj202588.top/Article/details/gtyiijhrqs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gotoacloud.top/Article/details/gtlwkpifqg.html

[Q24] 去重
来源：http://dali.nanxuanxn.top/Article/details/gtdfrybneb.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258888.top/Article/details/gtasjfxhwy.html

[Q25] 只取前 N 条
来源：http://dali.gotoacloud.top/Article/details/gtrvntpreo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.guowangkeji.top/Article/details/gtjspowxio.html

[Q26] 计数
来源：http://dali.bjfxy.top/Article/details/gthwiiegqq.html

SELECT COUNT(*) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtrckmazje.html

[Q27] 条件计数
来源：http://dali.gzhubu.top/Article/details/gtsrxkkavq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtoqoqpgmh.html

[Q28] 求和与平均
来源：http://dali.chenjidiqi.icu/Article/details/gtwgxqikzl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtowxqptdp.html

[Q29] 最大最小值
来源：http://dali.havefunace.top/Article/details/gtpnpcexij.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtnraubspm.html

[Q30] 分组统计
来源：http://dali.nanxuanxn.top/Article/details/gtcrwxrwgs.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gtyqhtxdde.html

[Q31] 分组后过滤
来源：http://dali.iojbl.cn/Article/details/gttzspqowr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cashguo.top/Article/details/gthmbyqtzq.html

[Q32] 分组拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gtxoyxpyok.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtupfilaxc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shzxlz.cn/Article/details/gtukuijnwz.html

[Q33] 多列分组
来源：http://dali.daria6918.cn/Article/details/gtbljkrwlv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.fengsongda.top/Article/details/gtbmnsgnxa.html

[Q34] 每组取第一条
来源：http://dali.mhx1999.top/Article/details/gtdtwpjiqa.html

SELECT * FROM (
来源：http://dali.shuidangran.top/Article/details/gtliaxvnnu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pycfn.com/Article/details/gthgwdffif.html

) t WHERE rn = 1;
来源：http://dali.yvedp.cn/Article/details/gtdmnvqxcp.html

[Q35] 内连接
来源：http://dali.daxiang520.top/Article/details/gtzdrxtrtw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gtivautqnp.html

[Q36] 左连接
来源：http://dali.havefunace.top/Article/details/gteqmbtuky.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258.top/Article/details/gtnkqwsxzh.html

[Q37] 右连接
来源：http://dali.yuxming.cn/Article/details/gtepzjzozg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yonumen.top/Article/details/gtubbyczuw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cdnleiting.top/Article/details/gtulurfstk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xziqi.cn/Article/details/gtysecethi.html

[Q39] 自连接（查上下级）
来源：http://dali.9152youxi.cn/Article/details/gtlxtznciq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xinyue.icu/Article/details/gtunaelnum.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xuanzx.com/Article/details/gtnljvhawn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.snrcjt.cn/Article/details/gtbfzgpbzn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cdnleiting.top/Article/details/gtfhspbvyl.html

[Q41] 多表连接
来源：http://dali.fzhhl.top/Article/details/gtcrwephkf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.redwolf501.top/Article/details/gtknfwzyhm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrvqfjcq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hfpthk.cn/Article/details/gtmddpwylh.html

[Q42] 连接条件附加过滤
来源：http://dali.316326.xyz/Article/details/gtbzjubbby.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhiwuduotai.top/Article/details/gtpuanjphe.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jlsjyb.cn/Article/details/gtgwowcixu.html

[Q43] 标量子查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtfyygzevj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gogol.net.cn/Article/details/gtmjsgpqbk.html

[Q44] IN 子查询
来源：http://dali.tianlin.xyz/Article/details/gthzswietm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.pycfn.com/Article/details/gtupzesqkg.html

[Q45] EXISTS 判断存在
来源：http://dali.chenjidiqi.icu/Article/details/gtxogvxhxk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxuanxn.top/Article/details/gttsqldxor.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenzaomai.com/Article/details/gteualtyhc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.iojbl.cn/Article/details/gtacwnnehl.html

[Q47] 与平均值比较
来源：http://dali.zhongyouzk.top/Article/details/gtnqoxigqk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jyoumei.cn/Article/details/gtotjcuixq.html

[Q48] CTE 公用表表达式
来源：http://dali.guannengcc.top/Article/details/gtzowyvesy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.snrcjt.cn/Article/details/gtdnvxhakv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhongyouzk.top/Article/details/gtclhvvyuy.html

[Q49] 更新单行
来源：http://dali.smart0.xyz/Article/details/gtjqxzvzad.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gtzmqyhpwj.html

[Q50] 批量更新
来源：http://dali.ivvv.top/Article/details/gtjtwxcfbg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cqqwz.cn/Article/details/gtksyjasut.html

[Q51] 用子查询更新
来源：http://dali.yangfankeji.com/Article/details/gtcabgofpr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtgqocivxz.html

[Q52] 删除指定行
来源：http://dali.sweek.top/Article/details/gtxgyekydr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ehwqpu.com/Article/details/gteaciunrr.html

[Q53] 按条件删除
来源：http://dali.shuidangran.top/Article/details/gtretazzjc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shangyingyoupin.top/Article/details/gtosvutaag.html

[Q54] 清空表
来源：http://dali.vqdsnc.cn/Article/details/gtzxeybqog.html

TRUNCATE TABLE logs;
来源：http://dali.yvedp.cn/Article/details/gtzerphxba.html

[Q55] 排名（并列占位）
来源：http://dali.zhoulong.xyz/Article/details/gtrisenzpp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.mhx1999.top/Article/details/gtglaibtqy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guannengcc.top/Article/details/gtwgcgncfv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.snrcjt.cn/Article/details/gtkndiobaz.html

[Q57] 行号
来源：http://dali.svipenyu.cn/Article/details/gtdxlyzpmc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtpveiqihk.html

[Q58] 累计求和
来源：http://dali.hywenlv.cn/Article/details/gtghogfgeg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtnyrakryx.html

[Q59] 分组内累计
来源：http://dali.yongpay.top/Article/details/gtztoblbkr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtdpwouhdd.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhoulong.xyz/Article/details/gttwbhwypq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gogol.net.cn/Article/details/gtoftplmtz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdnufkrje.html

[Q61] 移动平均
来源：http://dali.cheryme.top/Article/details/gtuujywouz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gteoicqwih.html

[Q62] 分组占比
来源：http://dali.jqgfzy.top/Article/details/gtctwovhqk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gtwhnthzcv.html

[Q63] 开启事务
来源：http://dali.kuanghao11.cn/Article/details/gtqbxmtimc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.smart0.xyz/Article/details/gteajgpijj.html

[Q64] 提交事务
来源：http://dali.cqqwz.cn/Article/details/gthbdhncwa.html

COMMIT;
来源：http://dali.zhongyouzk.top/Article/details/gtoftwzuqu.html

[Q65] 回滚事务
来源：http://dali.zhixingplan.top/Article/details/gteeujrttd.html

ROLLBACK;
来源：http://dali.yuanzhike.top/Article/details/gthrwmotxc.html

[Q66] 行锁查询
来源：http://dali.meibo888.top/Article/details/gtzcullosr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuanzhike.top/Article/details/gtysyodzkt.html

[Q67] 设置隔离级别
来源：http://dali.svipenyu.cn/Article/details/gtdfxdsbiy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sxryk.cn/Article/details/gtpdvdmega.html

[Q68] 保存点
来源：http://dali.wangshuangyany.cn/Article/details/gtqujjdjry.html

SAVEPOINT sp1;
来源：http://dali.daxiang520.top/Article/details/gtbkrchnsp.html

ROLLBACK TO sp1;
来源：http://dali.jyoumei.cn/Article/details/gtpkxzvimr.html

[Q69] 查看执行计划
来源：http://dali.pycfn.com/Article/details/gtcxdqcmiv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinghuilouyu.cn/Article/details/gtoyeqbokp.html

[Q70] 更新统计信息
来源：http://dali.snrcjt.cn/Article/details/gtbhewgodj.html

ANALYZE TABLE users;
来源：http://dali.svipenyu.cn/Article/details/gtvcnceeqx.html

[Q71] 查看建表语句
来源：http://dali.yonumen.top/Article/details/gtbvcdebzf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhongyouzk.top/Article/details/gtmtkegzus.html

[Q72] 查看索引
来源：http://dali.gzhubu.top/Article/details/gtkrneexlv.html

SHOW INDEX FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtgisvygtj.html

[Q73] 查看表状态
来源：http://dali.nanxinkj.top/Article/details/gtuujqeovb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenzaomai.com/Article/details/gtvbijtjeb.html

[Q74] 强制使用索引
来源：http://dali.ppjwa.cn/Article/details/gtdbggxgml.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yangfankeji.com/Article/details/gtvnbdfydw.html

[Q75] 日期格式化
来源：http://dali.cdnleiting.top/Article/details/gtwabnlgjo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtuaqcfccn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.9152youxi.cn/Article/details/gtrynylzsp.html

[Q76] 按天统计
来源：http://dali.hnxiangtu.top/Article/details/gtrqddnqzp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqdqheka.html

[Q77] 时间加减
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpxrjjok.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenlongwang.top/Article/details/gtxbowtyrq.html

[Q78] 当前时间
来源：http://dali.sufxvd.cn/Article/details/gtgsxvlpmu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.birdmap.top/Article/details/gtrysvdbhz.html

[Q79] 字符串拼接
来源：http://dali.tian-w.cn/Article/details/gtpjytfmfb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pengpengdd.cyou/Article/details/gtkkjjreln.html

[Q80] 字符串截取
来源：http://dali.vqdsnc.cn/Article/details/gtnctvhozj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtooxvyleu.html

[Q81] 字符串替换
来源：http://dali.shangyingyoupin.top/Article/details/gtizoyeygm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtjaxmrlgt.html

[Q82] 字符长度与字节长度
来源：http://dali.feifeiyinyue.top/Article/details/gtlnsptrpj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtzyzsmxnx.html

[Q83] 大小写转换
来源：http://dali.hammf.cn/Article/details/gtglbikiyj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtlxeevlse.html

[Q84] 去除首尾空格
来源：http://dali.wangdashe.top/Article/details/gtggextolb.html

SELECT TRIM(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtrsidokji.html

[Q85] 数值取整
来源：http://dali.shangyingyoupin.top/Article/details/gtikdkvuug.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangdashe.top/Article/details/gtoeimakuu.html

[Q86] 读取 JSON 字段
来源：http://dali.gzhubu.top/Article/details/gttdftvald.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.vqdsnc.cn/Article/details/gtotzgpbyf.html

[Q87] JSON 字段做条件
来源：http://dali.xinyue.icu/Article/details/gtktnznahs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hnxiangtu.top/Article/details/gtlfawumxr.html

[Q88] 行转列（条件聚合）
来源：http://dali.sufxvd.cn/Article/details/gtbphqpfbv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yuanzhike.top/Article/details/gtppdltncv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ydzc1.top/Article/details/gttalzeyto.html

[Q89] 判断表是否存在
来源：http://dali.hnqzz.top/Article/details/gtdojqdgsu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgfzy.top/Article/details/gtgloofhys.html

[Q90] 生成序号列
来源：http://dali.snrcjt.cn/Article/details/gtcwmosonp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.fengsongda.top/Article/details/gtjnzklwdf.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtezmsllvn.html

R. Bash 专题
来源：http://dali.gogol.net.cn/Article/details/gthvnxlefd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtemyhpose.html

[R01] shebang 与严格模式
来源：http://dali.nwbrower.top/Article/details/gtoqdnfvpa.html

#!/usr/bin/env bash
来源：http://dali.zycfv.cn/Article/details/gtqpwikjuq.html

set -euo pipefail
来源：http://dali.nanxuanxn.top/Article/details/gtbxwtmxcg.html

[R02] 变量赋值与使用
来源：http://dali.gzhubu.top/Article/details/gtcihbigjp.html

name="Tom"; echo "$name"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhcivvpy.html

[R03] 只读变量
来源：http://dali.mhx1999.top/Article/details/gtqsueavto.html

readonly PI=3.14
来源：http://dali.hfpthk.cn/Article/details/gtmqgsyyhe.html

[R04] 位置参数
来源：http://dali.aibaodan.cn/Article/details/gtuyokfcnx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyotkaucd.html

[R05] 参数默认值
来源：http://dali.hammf.cn/Article/details/gtisexfqqq.html

name="${1:-default}"
来源：http://dali.hammf.cn/Article/details/gtcgfvluok.html

[R06] 判断命令是否存在
来源：http://dali.ydzc1.top/Article/details/gtkqmdqwyg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yueranfly.top/Article/details/gtmnmkdbtw.html

[R07] if 判断文件
来源：http://dali.fzhhl.top/Article/details/gtloezocqi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtrwiddvii.html

[R08] 数值比较
来源：http://dali.nwbrower.top/Article/details/gttnguprjy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jianghu66.top/Article/details/gtutasyolj.html

[R09] 字符串比较
来源：http://dali.ppjwa.cn/Article/details/gtfbjfgfvg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtyrhzxpvo.html

[R10] 正则匹配
来源：http://dali.jinqigfzy.top/Article/details/gtsxnacejk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cashguo.top/Article/details/gtvfalsbia.html

[R11] case 多分支
来源：http://dali.yonumen.top/Article/details/gtqljyulgg.html

case "$1" in
来源：http://dali.kuanghao11.cn/Article/details/gtaqwzgznc.html

start) echo "启动" ;;
来源：http://dali.iojbl.cn/Article/details/gtxrvfgwob.html

stop)  echo "停止" ;;
来源：http://dali.zhoulong.xyz/Article/details/gtvrgyewoi.html

*)     echo "未知命令" ;;
来源：http://dali.0kj1m.cn/Article/details/gtjmcmxjjk.html

esac
来源：http://dali.xuanzx.com/Article/details/gtucgmyulz.html

[R12] for 遍历文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdlhzirv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sweek.top/Article/details/gtpzyacjhw.html

[R13] for 计数循环
来源：http://dali.cheryme.top/Article/details/gtsiztgivd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gtbizvrohq.html

[R14] C 风格 for
来源：http://dali.iojbl.cn/Article/details/gtkivpzsex.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gtyfhyjtri.html

[R15] while 逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gttrlzmpzj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.guowangkeji.top/Article/details/gtxsymselv.html

[R16] until 等待条件
来源：http://dali.aizwys.cn/Article/details/gtjsidivhr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtikibtkqm.html

[R17] 数组定义与取值
来源：http://dali.yvedp.cn/Article/details/gtyuundjbj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nanxinkj.top/Article/details/gtnqaymjke.html

[R18] 遍历数组
来源：http://dali.mhx1999.top/Article/details/gtfehbxgtl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yongpay.top/Article/details/gtveanywpf.html

[R19] 数组长度
来源：http://dali.kuanghao11.cn/Article/details/gtryytiekd.html

echo "${#arr[@]}"
来源：http://dali.fzhhl.top/Article/details/gtqezdllyj.html

[R20] 关联数组（字典）
来源：http://dali.gogol.net.cn/Article/details/gtaeexcllq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhongyouzk.top/Article/details/gtksqhwrpl.html

[R21] 字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gtxhtgxkoj.html

echo "${#s}"
来源：http://dali.hammf.cn/Article/details/gtotkqnptc.html

[R22] 截取子串
来源：http://dali.mhx1999.top/Article/details/gtuxhsvwpn.html

echo "${s:0:5}"
来源：http://dali.yuxming.cn/Article/details/gtmkprfiho.html

[R23] 字符串替换
来源：http://dali.dianchejie.cn/Article/details/gtrkxxxmgy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.haohaochexian.top/Article/details/gtccjvbwjr.html

[R24] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gttfwagpjm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigfzy.top/Article/details/gtjyiveawm.html

[R25] 去后缀 / 去前缀
来源：http://dali.gzhubu.top/Article/details/gtiiaxkefg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pycfn.com/Article/details/gttuguuebe.html

[R26] 命令替换
来源：http://dali.fzhhl.top/Article/details/gtbvzgmgec.html

now=$(date +%F); echo "$now"
来源：http://dali.zhongyouzk.top/Article/details/gteefjaulu.html

[R27] 算术展开
来源：http://dali.hfpthk.cn/Article/details/gtatksedlp.html

echo $((1 + 2 * 3))
来源：http://dali.mhx1999.top/Article/details/gteyegjckx.html

[R28] 浮点运算
来源：http://dali.zhixingplan.top/Article/details/gtummrlpbm.html

echo "scale=2; 10/3" | bc
来源：http://dali.redwolf501.top/Article/details/gtjiqearoh.html

[R29] 定义函数
来源：http://dali.jianghu66.top/Article/details/gtqrledohe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yanxiufei.cn/Article/details/gtkjpcftlc.html

[R30] 函数返回状态码
来源：http://dali.zhiwuduotai.top/Article/details/gtndjciokf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.havefunace.top/Article/details/gtetmkewlc.html

[R31] 局部变量
来源：http://dali.feifeiyinyue.top/Article/details/gttwolorye.html

f() { local x=1; echo "$x"; }
来源：http://dali.ppjwa.cn/Article/details/gtmqqyzwto.html

[R32] 参数个数校验
来源：http://dali.hammf.cn/Article/details/gttctqbfjw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gaohongyu789.top/Article/details/gtlouqefhx.html

[R33] 捕获错误并提示行号
来源：http://dali.yangfankeji.com/Article/details/gtppnnkkxo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.mhx1999.top/Article/details/gtwrchdewi.html

[R34] 退出时清理
来源：http://dali.jiagoushi.top/Article/details/gtgfspacve.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gtwtytqejy.html

[R35] 后台执行并等待
来源：http://dali.gzhubu.top/Article/details/gtyguxcpax.html


<!-- 参考信息 -->