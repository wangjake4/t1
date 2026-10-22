代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.andypj.xyz/Article/details/gtnziwihtx.html

TS:   if (x == null) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtfyrftdrg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zycfv.cn/Article/details/gtfzooaswg.html

Go:   if x == nil {}
来源：http://dali.c1oappe.top/Article/details/gtqjprkyhi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinqigufen.top/Article/details/gtcugkkxjy.html

C#:   if (x is null) {}
来源：http://dali.guannengcc.top/Article/details/gtvehcqwek.html

[P07] 防抖与节流
来源：http://dali.bjfxy.top/Article/details/gtqxqmxnnv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.haohaochexian.top/Article/details/gttouaruat.html

PHP:  // 手写时间戳比较
来源：http://dali.yvedp.cn/Article/details/gtzbljvfrw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gthhfpompk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.svipenyu.cn/Article/details/gthzywxbtu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gogol.net.cn/Article/details/gtszlmlaos.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sufxvd.cn/Article/details/gtvielyvdx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yanxiufei.cn/Article/details/gtgrcfkpxg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hfpthk.cn/Article/details/gtxhmxpysn.html

[P08] 处理浮点精度问题
来源：http://dali.zhengqikj.top/Article/details/gtyuzhaeqv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hnqzz.top/Article/details/gtnjqfsfrg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hfpthk.cn/Article/details/gtpkpukxmi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ybcxt.top/Article/details/gtekxzrlhc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtoybtytpk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.haohaochexian.top/Article/details/gtmllmkmam.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangtech.top/Article/details/gtkaetrqln.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sysykeji.top/Article/details/gtimooeoqk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zycfv.cn/Article/details/gtvsqbgeft.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtpxayvniu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shuidangran.top/Article/details/gtfcfqhbnf.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtjwpglvfz.html

[Q01] 创建表
来源：http://dali.cheryme.top/Article/details/gtdcaxayzd.html

CREATE TABLE users (
来源：http://dali.jqgfzy.top/Article/details/gtidvfhjec.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.quarkkingdee.top/Article/details/gtnlznstzg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.316326.xyz/Article/details/gtqifqhtvq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.andypj.xyz/Article/details/gtayoglski.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangshuangyany.cn/Article/details/gtmclonbcg.html

);
来源：http://dali.jlsjyb.cn/Article/details/gtbjtuwyzo.html

[Q02] 创建带外键的表
来源：http://dali.tanke756.top/Article/details/gtfgvvrnaq.html

CREATE TABLE orders (
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqilredkf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhixingplan.top/Article/details/gtyseknsbr.html

user_id INT NOT NULL,
来源：http://dali.aibaodan.cn/Article/details/gtsbzfdiyj.html

amount DECIMAL(10, 2),
来源：http://dali.yueranfly.top/Article/details/gtedwvuhpo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.andypj.xyz/Article/details/gtsbxsfxzb.html

);
来源：http://dali.jqgfzy.top/Article/details/gtcdfcobzl.html

[Q03] 增加列
来源：http://dali.zdqjudy.top/Article/details/gtctyshrwg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hnxiangtu.top/Article/details/gtmmgxryen.html

[Q04] 修改列类型
来源：http://dali.cdnleiting.top/Article/details/gturhotnie.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yuanzhike.top/Article/details/gtfqvllwrw.html

[Q05] 重命名列
来源：http://dali.cucudq.cn/Article/details/gtsniznfar.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yuxming.cn/Article/details/gtvqqvxatv.html

[Q06] 删除列
来源：http://dali.daxiang520.top/Article/details/gtemxsqlvq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hnqzz.top/Article/details/gtzhbbsyko.html

[Q07] 删除表
来源：http://dali.zhixingplan.top/Article/details/gtkhpipyxg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zdqjudy.top/Article/details/gtdanoxrxo.html

[Q08] 创建普通索引
来源：http://dali.zhiwuduotai.top/Article/details/gtnxtztcgv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtysfguzet.html

[Q09] 创建唯一索引
来源：http://dali.wangshuangyany.cn/Article/details/gtbqvlxvle.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.quarkkingdee.top/Article/details/gteehppjys.html

[Q10] 插入单行
来源：http://dali.cucudq.cn/Article/details/gttjyryplo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sweek.top/Article/details/gtivvoeklm.html

[Q11] 一次插入多行
来源：http://dali.hnxiangtu.top/Article/details/gtafhvadcj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yonumen.top/Article/details/gtclreeuzv.html

[Q12] 插入后取自增 ID
来源：http://dali.smart0.xyz/Article/details/gtosbwicks.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cheryme.top/Article/details/gtqgtixxyt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yonumen.top/Article/details/gtdzesxqkg.html

[Q13] 忽略重复插入
来源：http://dali.hfpthk.cn/Article/details/gtunahkstz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yuxming.cn/Article/details/gtdbhcavkv.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuanzx.com/Article/details/gtflyemweq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jqgfzy.top/Article/details/gtggaemotc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gotoacloud.top/Article/details/gtuwjwscfv.html

[Q15] 查询全部
来源：http://dali.quarkkingdee.top/Article/details/gtneczpdxd.html

SELECT * FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtserbtleo.html

[Q16] 查询指定列
来源：http://dali.zhiwuduotai.top/Article/details/gtxpgmmkks.html

SELECT id, name FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtjmnqkbgg.html

[Q17] 条件查询
来源：http://dali.snrcjt.cn/Article/details/gtycmhpitf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fengsongda.top/Article/details/gtzgbnydch.html

[Q18] 模糊匹配
来源：http://dali.cashguo.top/Article/details/gtnykodiej.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.wangshuangyany.cn/Article/details/gtmeugcshb.html

[Q19] 范围查询
来源：http://dali.tian-w.cn/Article/details/gtuldqdxxh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenjidiqi.icu/Article/details/gtqubzuqql.html

[Q20] IN 列表
来源：http://dali.nwbrower.top/Article/details/gtxnckmshb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.meibo888.top/Article/details/gtucuiidny.html

[Q21] 空值判断
来源：http://dali.cucudq.cn/Article/details/gtfrqkxkpd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yonumen.top/Article/details/gttqovfhdj.html

[Q22] 排序
来源：http://dali.chenjidiqi.icu/Article/details/gtznkifyup.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tanke756.top/Article/details/gtzodszmto.html

[Q23] 分页
来源：http://dali.cheryme.top/Article/details/gtshpbdlar.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ydzc1.top/Article/details/gtjqjfbzpl.html

[Q24] 去重
来源：http://dali.yuanzhike.top/Article/details/gtffslbotr.html

SELECT DISTINCT city FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtdyrjsxax.html

[Q25] 只取前 N 条
来源：http://dali.xuanzx.com/Article/details/gtqoyjycqw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hongshengwenyu.top/Article/details/gtgblynhuq.html

[Q26] 计数
来源：http://dali.jinqigufen.top/Article/details/gtgrkvxlin.html

SELECT COUNT(*) FROM users;
来源：http://dali.ivvv.top/Article/details/gtwtovklib.html

[Q27] 条件计数
来源：http://dali.jiagoushi.top/Article/details/gtaqeafioo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtufmnltir.html

[Q28] 求和与平均
来源：http://dali.sysykeji.top/Article/details/gthzwezdpo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtjhdsdhpk.html

[Q29] 最大最小值
来源：http://dali.ppjwa.cn/Article/details/gtdoozwirz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yonumen.top/Article/details/gtvxzcikeb.html

[Q30] 分组统计
来源：http://dali.jyoumei.cn/Article/details/gtdbvuxwgd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gtkxqsdvwm.html

[Q31] 分组后过滤
来源：http://dali.sxryk.cn/Article/details/gteskxgdqv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgufenzy.top/Article/details/gtqncttyrg.html

[Q32] 分组拼接字符串
来源：http://dali.redwolf501.top/Article/details/gtgeuchdse.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gtbyrjdbju.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekrepkjo.html

[Q33] 多列分组
来源：http://dali.316326.xyz/Article/details/gtdfngvukz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xylfe.cn/Article/details/gthuderpuy.html

[Q34] 每组取第一条
来源：http://dali.xziqi.cn/Article/details/gteewrthth.html

SELECT * FROM (
来源：http://dali.xinyue.icu/Article/details/gttxpdltuw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zdqjudy.top/Article/details/gtizqbeheo.html

) t WHERE rn = 1;
来源：http://dali.dashuyun.cn/Article/details/gtbwbrpknu.html

[Q35] 内连接
来源：http://dali.nanxinkj.top/Article/details/gtpgwrbqxn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tian-w.cn/Article/details/gtsufeiybz.html

[Q36] 左连接
来源：http://dali.jqgfzy.top/Article/details/gtsjivuntz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqmdduaq.html

[Q37] 右连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmulsvgd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gogol.net.cn/Article/details/gtmqqxpgap.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xziqi.cn/Article/details/gtvwwpeyzi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmaopjrcl.html

[Q39] 自连接（查上下级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteobkkrlz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhixingplan.top/Article/details/gtlaappvaa.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.havefunace.top/Article/details/gtnxarrsdj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.daria6918.cn/Article/details/gtvrwidetj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhongyouzk.top/Article/details/gtnqblgeio.html

[Q41] 多表连接
来源：http://dali.cdnleiting.top/Article/details/gticqxcvle.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.iojbl.cn/Article/details/gthpvnimlm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.dianchejie.cn/Article/details/gtgogzbfsm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.vqdsnc.cn/Article/details/gtlosiyahk.html

[Q42] 连接条件附加过滤
来源：http://dali.jqgfzy.top/Article/details/gtofigsxsv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.haohaochexian.top/Article/details/gtrhacdmdy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.svipenyu.cn/Article/details/gtcfhtdiwo.html

[Q43] 标量子查询
来源：http://dali.9152youxi.cn/Article/details/gtprerhbjh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xziqi.cn/Article/details/gtouclyoto.html

[Q44] IN 子查询
来源：http://dali.guowangkeji.top/Article/details/gthxejhoye.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yonumen.top/Article/details/gtldahtwau.html

[Q45] EXISTS 判断存在
来源：http://dali.wangdashe.top/Article/details/gtgasjzaip.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gtpjrcfdbm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.guowangkeji.top/Article/details/gtgkearzpd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhongyouzk.top/Article/details/gtwlycbamt.html

[Q47] 与平均值比较
来源：http://dali.shuidangran.top/Article/details/gtkhejqovi.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xylfe.cn/Article/details/gtzkutknyx.html

[Q48] CTE 公用表表达式
来源：http://dali.nanxinkj.top/Article/details/gtizvaesbf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sweek.top/Article/details/gtnlwgdlan.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.316326.xyz/Article/details/gtgykkquyx.html

[Q49] 更新单行
来源：http://dali.hywenlv.cn/Article/details/gtycagohyb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gtiopnqvqq.html

[Q50] 批量更新
来源：http://dali.yanxiufei.cn/Article/details/gtfhypsuot.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cqqwz.cn/Article/details/gtwlmfpwjh.html

[Q51] 用子查询更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfaxeoxey.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.birdmap.top/Article/details/gtdwlsoghm.html

[Q52] 删除指定行
来源：http://dali.tianlin.xyz/Article/details/gtxwhbraav.html

DELETE FROM users WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gtwsjimiqr.html

[Q53] 按条件删除
来源：http://dali.hywenlv.cn/Article/details/gtqidzttqu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gtavumwuki.html

[Q54] 清空表
来源：http://dali.quarkkingdee.top/Article/details/gtyyhirpol.html

TRUNCATE TABLE logs;
来源：http://dali.nanxinkj.top/Article/details/gtyeepdcom.html

[Q55] 排名（并列占位）
来源：http://dali.zhixingplan.top/Article/details/gtfcryvtza.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gtijitrrpz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.redwolf501.top/Article/details/gtudqfkkxv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gtjksteoch.html

[Q57] 行号
来源：http://dali.c1oappe.top/Article/details/gtebnpnzby.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtgohewauv.html

[Q58] 累计求和
来源：http://dali.yj202588.top/Article/details/gtvftkpmwe.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtliygptxm.html

[Q59] 分组内累计
来源：http://dali.0kj1m.cn/Article/details/gtjdqmrhwb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtkjkwdrtl.html

[Q60] 取上一行 / 下一行
来源：http://dali.sweek.top/Article/details/gtpoywnbfs.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.snrcjt.cn/Article/details/gtpirwnytr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.316326.xyz/Article/details/gtcnrgwxke.html

[Q61] 移动平均
来源：http://dali.sxryk.cn/Article/details/gtlionugkt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtgztzuyik.html

[Q62] 分组占比
来源：http://dali.dashuyun.cn/Article/details/gtwtoaibua.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gtcmvftyvf.html

[Q63] 开启事务
来源：http://dali.sysykeji.top/Article/details/gtfomfpunj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtupnqtvov.html

[Q64] 提交事务
来源：http://dali.shuidangran.top/Article/details/gtvicujuky.html

COMMIT;
来源：http://dali.tianlin.xyz/Article/details/gtzqlrekky.html

[Q65] 回滚事务
来源：http://dali.vqdsnc.cn/Article/details/gtcvybwykn.html

ROLLBACK;
来源：http://dali.tian-w.cn/Article/details/gtxewezcit.html

[Q66] 行锁查询
来源：http://dali.meibo888.top/Article/details/gtppfyspha.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jqgfzy.top/Article/details/gtssmfrmxi.html

[Q67] 设置隔离级别
来源：http://dali.0kj1m.cn/Article/details/gtjvniyodb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ppjwa.cn/Article/details/gtvisikeex.html

[Q68] 保存点
来源：http://dali.vqdsnc.cn/Article/details/gtyfrwsizo.html

SAVEPOINT sp1;
来源：http://dali.gaohongyu789.top/Article/details/gtxyyyokhq.html

ROLLBACK TO sp1;
来源：http://dali.zhiwuduotai.top/Article/details/gtbzlbutlj.html

[Q69] 查看执行计划
来源：http://dali.daxiang520.top/Article/details/gtftxxnnhm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.andypj.xyz/Article/details/gtfqrdazhu.html

[Q70] 更新统计信息
来源：http://dali.zhengqikj.top/Article/details/gtfrnwbfag.html

ANALYZE TABLE users;
来源：http://dali.tianlin.xyz/Article/details/gtsfuogtax.html

[Q71] 查看建表语句
来源：http://dali.tian-w.cn/Article/details/gtryemgmzp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nwbrower.top/Article/details/gtyrukcmar.html

[Q72] 查看索引
来源：http://dali.fzhhl.top/Article/details/gtxurnfgvq.html

SHOW INDEX FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtfduuunfl.html

[Q73] 查看表状态
来源：http://dali.hnqzz.top/Article/details/gtghfisaha.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.9152youxi.cn/Article/details/gtveapxotr.html

[Q74] 强制使用索引
来源：http://dali.redwolf501.top/Article/details/gtwwncoktr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jqgufenzy.top/Article/details/gtnbwrwfqq.html

[Q75] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtbhjvcpqm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hammf.cn/Article/details/gtltvletco.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yueranfly.top/Article/details/gtycjeyvrt.html

[Q76] 按天统计
来源：http://dali.yonumen.top/Article/details/gtnqbfkege.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hongshengwenyu.top/Article/details/gttmzpitri.html

[Q77] 时间加减
来源：http://dali.feifeiyinyue.top/Article/details/gtisdqscxm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigfzy.top/Article/details/gtlvkogmob.html

[Q78] 当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzycgncrf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yangfankeji.com/Article/details/gtqehagwsn.html

[Q79] 字符串拼接
来源：http://dali.svipenyu.cn/Article/details/gtdcavsavy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cheryme.top/Article/details/gtecyoyiis.html

[Q80] 字符串截取
来源：http://dali.andypj.xyz/Article/details/gtxkmqisge.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtpmbfilas.html

[Q81] 字符串替换
来源：http://dali.nanxinkj.top/Article/details/gtrabnvjwg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtyruwgkju.html

[Q82] 字符长度与字节长度
来源：http://dali.hongshengwenyu.top/Article/details/gttpjzzbvf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtxvzxylbq.html

[Q83] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gtbrmswwlu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gthnvdcxdv.html

[Q84] 去除首尾空格
来源：http://dali.0kj1m.cn/Article/details/gtfwjsgced.html

SELECT TRIM(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtynlgbhab.html

[Q85] 数值取整
来源：http://dali.jqgfzy.top/Article/details/gtomscwbrb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxinkj.top/Article/details/gtokvtwljc.html

[Q86] 读取 JSON 字段
来源：http://dali.meibo888.top/Article/details/gtpsoenukd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenzaomai.com/Article/details/gtoijnoseb.html

[Q87] JSON 字段做条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpgdifuj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinqigfzy.top/Article/details/gtuyjpjvle.html

[Q88] 行转列（条件聚合）
来源：http://dali.ybcxt.top/Article/details/gtvarpvfzj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ppjwa.cn/Article/details/gtjqnvwxwy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yonumen.top/Article/details/gtokuupedk.html

[Q89] 判断表是否存在
来源：http://dali.cheryme.top/Article/details/gtpyjeqznh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.quarkkingdee.top/Article/details/gtuaqhtmgf.html

[Q90] 生成序号列
来源：http://dali.ppjwa.cn/Article/details/gtumomvtck.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj20258888.top/Article/details/gtjggtzpjq.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtlffjgazu.html

R. Bash 专题
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwwiixqqo.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtibazciuc.html

[R01] shebang 与严格模式
来源：http://dali.sufxvd.cn/Article/details/gtxrhkfwdk.html

#!/usr/bin/env bash
来源：http://dali.tanke756.top/Article/details/gtupgtbjdz.html

set -euo pipefail
来源：http://dali.xziqi.cn/Article/details/gtikcfmfez.html

[R02] 变量赋值与使用
来源：http://dali.nwbrower.top/Article/details/gtccporipn.html

name="Tom"; echo "$name"
来源：http://dali.iojbl.cn/Article/details/gtiwkxjxdk.html

[R03] 只读变量
来源：http://dali.daxiang520.top/Article/details/gtnbwwwkhu.html

readonly PI=3.14
来源：http://dali.hysaishi.cn/Article/details/gtddgaxonj.html

[R04] 位置参数
来源：http://dali.gaohongyu789.top/Article/details/gtypyqwzlg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sufxvd.cn/Article/details/gtdlnsilug.html

[R05] 参数默认值
来源：http://dali.nanxuanxn.top/Article/details/gtuwmnowas.html

name="${1:-default}"
来源：http://dali.xziqi.cn/Article/details/gthvehptif.html

[R06] 判断命令是否存在
来源：http://dali.mhx1999.top/Article/details/gtfegcqbvu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoyglmbmg.html

[R07] if 判断文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszsmgfoh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cdnleiting.top/Article/details/gtrahmqbks.html

[R08] 数值比较
来源：http://dali.cheryme.top/Article/details/gtuhbipigr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dashuyun.cn/Article/details/gtpzkgwwzw.html

[R09] 字符串比较
来源：http://dali.cucudq.cn/Article/details/gtkhyrlvms.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jyoumei.cn/Article/details/gtncqfatjt.html

[R10] 正则匹配
来源：http://dali.tanke756.top/Article/details/gtiznupilc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tanke756.top/Article/details/gttjggjvad.html

[R11] case 多分支
来源：http://dali.ybcxt.top/Article/details/gtqsgwpxax.html

case "$1" in
来源：http://dali.tianlin.xyz/Article/details/gtprznvxbe.html

start) echo "启动" ;;
来源：http://dali.0kj1m.cn/Article/details/gtkztsoibe.html

stop)  echo "停止" ;;
来源：http://dali.chenzaomai.com/Article/details/gtvrhiqxqo.html

*)     echo "未知命令" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcouyfpo.html

esac
来源：http://dali.ydzc1.top/Article/details/gtukgxsxlc.html

[R12] for 遍历文件
来源：http://dali.hfpthk.cn/Article/details/gtsjijzxgn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.iojbl.cn/Article/details/gtaypmdujg.html

[R13] for 计数循环
来源：http://dali.dashuyun.cn/Article/details/gteuwotycg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhengqikj.top/Article/details/gtgcuiuucl.html

[R14] C 风格 for
来源：http://dali.tanke756.top/Article/details/gtykuvtwhh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gotoacloud.top/Article/details/gtivtkphrd.html

[R15] while 逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmdybjew.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.bjfxy.top/Article/details/gtiavblhar.html

[R16] until 等待条件
来源：http://dali.birdmap.top/Article/details/gtocmwyobp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cheryme.top/Article/details/gtjkhdllog.html

[R17] 数组定义与取值
来源：http://dali.hnxiangtu.top/Article/details/gtpuordffx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gtntvucpve.html

[R18] 遍历数组
来源：http://dali.yj202588.top/Article/details/gtamhjqkpa.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnqzz.top/Article/details/gtucqrqwrk.html

[R19] 数组长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzyzewdt.html

echo "${#arr[@]}"
来源：http://dali.gzhubu.top/Article/details/gtbrarwyib.html

[R20] 关联数组（字典）
来源：http://dali.zdqjudy.top/Article/details/gtzodabscl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.snrcjt.cn/Article/details/gtzxyxidxa.html

[R21] 字符串长度
来源：http://dali.zdqjudy.top/Article/details/gtqhyrvjkz.html

echo "${#s}"
来源：http://dali.meibo888.top/Article/details/gtbcyepsqn.html

[R22] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gtminoidog.html

echo "${s:0:5}"
来源：http://dali.hysaishi.cn/Article/details/gtzxjfqqac.html

[R23] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gtapvmhlla.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tianlin.xyz/Article/details/gtnqhtbneg.html

[R24] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtgmgtdbbd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj20258888.top/Article/details/gtzkiomlvm.html

[R25] 去后缀 / 去前缀
来源：http://dali.vqdsnc.cn/Article/details/gtgpxipcac.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.dashuyun.cn/Article/details/gtpegqcaqz.html

[R26] 命令替换
来源：http://dali.jyoumei.cn/Article/details/gtsrloicrv.html

now=$(date +%F); echo "$now"
来源：http://dali.mhx1999.top/Article/details/gtothndjru.html

[R27] 算术展开
来源：http://dali.hnqzz.top/Article/details/gtdwfoxuzi.html

echo $((1 + 2 * 3))
来源：http://dali.jyoumei.cn/Article/details/gtmjvnjqsi.html

[R28] 浮点运算
来源：http://dali.jqgufenzy.top/Article/details/gtueseevkg.html

echo "scale=2; 10/3" | bc
来源：http://dali.shangyingyoupin.top/Article/details/gtakberzjy.html

[R29] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gtdqmptxxl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yonumen.top/Article/details/gtasqqshzy.html

[R30] 函数返回状态码
来源：http://dali.yongpay.top/Article/details/gtzkmqplle.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.haohaochexian.top/Article/details/gtcdqtubhi.html

[R31] 局部变量
来源：http://dali.zhongyouzk.top/Article/details/gtuvtqmyia.html


<!-- 参考信息 -->