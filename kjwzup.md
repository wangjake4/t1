代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gogol.net.cn/Article/details/gtkiwgluyp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jqgufenzy.top/Article/details/gthkfafyfy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.feifeiyinyue.top/Article/details/gthoqlznyf.html

PHP:  if (empty($x)) {}
来源：http://dali.iojbl.cn/Article/details/gtrkpoqjqi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnxiangtu.top/Article/details/gtvkonrexz.html

TS:   if (x == null) {}
来源：http://dali.yonumen.top/Article/details/gtpxtybzuh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hammf.cn/Article/details/gtnwtwazrj.html

Go:   if x == nil {}
来源：http://dali.guannengcc.top/Article/details/gtlwnhcsto.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aizwys.cn/Article/details/gtwanjatkd.html

C#:   if (x is null) {}
来源：http://dali.cdnleiting.top/Article/details/gtvygafhgq.html

[P07] 防抖与节流
来源：http://dali.cqqwz.cn/Article/details/gtaoslwsam.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daria6918.cn/Article/details/gtkksqcics.html

PHP:  // 手写时间戳比较
来源：http://dali.aizwys.cn/Article/details/gtjdbilwrm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gteqmlkqhx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yangfankeji.com/Article/details/gtumlxvwfq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daxiang520.top/Article/details/gtvwczxjtt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.bjfxy.top/Article/details/gtbiuspnht.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ydzc1.top/Article/details/gtrhpbyemm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hnqzz.top/Article/details/gtrymlnngj.html

[P08] 处理浮点精度问题
来源：http://dali.zhiwuduotai.top/Article/details/gtvbkrrohh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhiwuduotai.top/Article/details/gtcetbsphc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.aizwys.cn/Article/details/gtollxvigw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fengsongda.top/Article/details/gtkvxzjejm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.birdmap.top/Article/details/gtyxpztidn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yuxming.cn/Article/details/gtndemledc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnqzz.top/Article/details/gtrwtjkcur.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sweek.top/Article/details/gtvygdjsdm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj20258.top/Article/details/gtarikypco.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtmcroutax.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.andypj.xyz/Article/details/gtttebtdcc.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gttpziackv.html

[Q01] 创建表
来源：http://dali.andypj.xyz/Article/details/gtjygxswet.html

CREATE TABLE users (
来源：http://dali.aizwys.cn/Article/details/gtrhletiml.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gtskkkpsus.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shzxlz.cn/Article/details/gtghohnsxb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nanxinkj.top/Article/details/gttuaxoanu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cheryme.top/Article/details/gtwnwdppgn.html

);
来源：http://dali.svipenyu.cn/Article/details/gtmeqciuie.html

[Q02] 创建带外键的表
来源：http://dali.yueranfly.top/Article/details/gtbjqxyzsh.html

CREATE TABLE orders (
来源：http://dali.sxryk.cn/Article/details/gtakzheadp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dianchejie.cn/Article/details/gtvjiriaxi.html

user_id INT NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gtemqzjwtz.html

amount DECIMAL(10, 2),
来源：http://dali.zhoulong.xyz/Article/details/gtbkmmkvii.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nanxuanxn.top/Article/details/gtemizdhok.html

);
来源：http://dali.cqqwz.cn/Article/details/gtvsavwosr.html

[Q03] 增加列
来源：http://dali.jianghu66.top/Article/details/gtaxjjsxwl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gzhubu.top/Article/details/gtphklugmy.html

[Q04] 修改列类型
来源：http://dali.c1oappe.top/Article/details/gtdqaurrez.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.feifeiyinyue.top/Article/details/gtsvyavcxs.html

[Q05] 重命名列
来源：http://dali.ybcxt.top/Article/details/gtjskvvqug.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhongyouzk.top/Article/details/gtdmcmcekh.html

[Q06] 删除列
来源：http://dali.ybcxt.top/Article/details/gtywryegvl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cashguo.top/Article/details/gtemzagzsz.html

[Q07] 删除表
来源：http://dali.tanke756.top/Article/details/gtjclfgvjk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.fengsongda.top/Article/details/gtggwdolcg.html

[Q08] 创建普通索引
来源：http://dali.jqgufenzy.top/Article/details/gtufdpdzdp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhiwuduotai.top/Article/details/gtddihfiuw.html

[Q09] 创建唯一索引
来源：http://dali.mhx1999.top/Article/details/gtfdijozbu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.wangdashe.top/Article/details/gteclespfz.html

[Q10] 插入单行
来源：http://dali.aibaodan.cn/Article/details/gtjvongajz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gtyuaqbwgw.html

[Q11] 一次插入多行
来源：http://dali.pycfn.com/Article/details/gtclijcfdo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gtfjfzvbuv.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258.top/Article/details/gtckhhoyav.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.andypj.xyz/Article/details/gtfuafsszo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.andypj.xyz/Article/details/gtgbcahssk.html

[Q13] 忽略重复插入
来源：http://dali.0kj1m.cn/Article/details/gthrtmgnmv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.aibaodan.cn/Article/details/gtjepvvyfd.html

[Q14] 存在则更新（upsert）
来源：http://dali.tian-w.cn/Article/details/gtdcldjpda.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.birdmap.top/Article/details/gtipaqshio.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hnqzz.top/Article/details/gtkzeywwuc.html

[Q15] 查询全部
来源：http://dali.zhoulong.xyz/Article/details/gtgxfvfryw.html

SELECT * FROM users;
来源：http://dali.andypj.xyz/Article/details/gtpfoqqeia.html

[Q16] 查询指定列
来源：http://dali.yongpay.top/Article/details/gtyvutawqg.html

SELECT id, name FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtxcftjebc.html

[Q17] 条件查询
来源：http://dali.gotoacloud.top/Article/details/gtzoxyvfxl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtxdqehtvm.html

[Q18] 模糊匹配
来源：http://dali.316326.xyz/Article/details/gtkpfctibg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cdnleiting.top/Article/details/gtqeswvwkv.html

[Q19] 范围查询
来源：http://dali.jqgufenzy.top/Article/details/gtpolzcpsa.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cheryme.top/Article/details/gtswpyspvi.html

[Q20] IN 列表
来源：http://dali.ppjwa.cn/Article/details/gtlvyzyzul.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.andypj.xyz/Article/details/gtgmokxpoe.html

[Q21] 空值判断
来源：http://dali.hnxiangtu.top/Article/details/gtyuqhwimq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hammf.cn/Article/details/gtnizrusuc.html

[Q22] 排序
来源：http://dali.hongshengwenyu.top/Article/details/gtzeuzowha.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.mhx1999.top/Article/details/gtqokbshjx.html

[Q23] 分页
来源：http://dali.guowangkeji.top/Article/details/gtmtaltojy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gzhubu.top/Article/details/gtmwjngaqx.html

[Q24] 去重
来源：http://dali.xuanzx.com/Article/details/gtrieyzrxa.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtepccoiaz.html

[Q25] 只取前 N 条
来源：http://dali.cucudq.cn/Article/details/gtinifizcs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tanke756.top/Article/details/gtzxxvsdor.html

[Q26] 计数
来源：http://dali.yuxming.cn/Article/details/gtyikvivsk.html

SELECT COUNT(*) FROM users;
来源：http://dali.ivvv.top/Article/details/gtafgvlljw.html

[Q27] 条件计数
来源：http://dali.xinyue.icu/Article/details/gtwgytbitp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sxryk.cn/Article/details/gtstuazjyk.html

[Q28] 求和与平均
来源：http://dali.birdmap.top/Article/details/gtcpccoorh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gthydtzwrr.html

[Q29] 最大最小值
来源：http://dali.yj20258.top/Article/details/gtiqrpahko.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtlpbghrfl.html

[Q30] 分组统计
来源：http://dali.xylfe.cn/Article/details/gtjfpplxgw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gtxpjqcldb.html

[Q31] 分组后过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtcgxjcoqf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hfpthk.cn/Article/details/gtmmlukikg.html

[Q32] 分组拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gthjbpytql.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gtepijofoa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.guowangkeji.top/Article/details/gtpjxlkrwh.html

[Q33] 多列分组
来源：http://dali.shzxlz.cn/Article/details/gtqftmiadl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sweek.top/Article/details/gtvomtfmuh.html

[Q34] 每组取第一条
来源：http://dali.havefunace.top/Article/details/gthvadbrgc.html

SELECT * FROM (
来源：http://dali.svipenyu.cn/Article/details/gtvxtcpjtt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigfzy.top/Article/details/gtudgtjuhz.html

) t WHERE rn = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtyvzzgove.html

[Q35] 内连接
来源：http://dali.cashguo.top/Article/details/gtowbzsmcd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gtvpikofrj.html

[Q36] 左连接
来源：http://dali.kuanghao11.cn/Article/details/gtrkywxqfs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.smart0.xyz/Article/details/gtljehpuyp.html

[Q37] 右连接
来源：http://dali.yangfankeji.com/Article/details/gtnklwtsqx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnxiangtu.top/Article/details/gtqzhtcuen.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxuanxn.top/Article/details/gtvrkdmdhy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yanxiufei.cn/Article/details/gtfmdjehkt.html

[Q39] 自连接（查上下级）
来源：http://dali.wangdashe.top/Article/details/gthmzctpie.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.andypj.xyz/Article/details/gtaufvveor.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gtqivkhxex.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.pycfn.com/Article/details/gtuxsrsldd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xuanzx.com/Article/details/gtdxxxphko.html

[Q41] 多表连接
来源：http://dali.gaohongyu789.top/Article/details/gtssayybff.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.aibaodan.cn/Article/details/gtwexemywj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jianghu66.top/Article/details/gtclyxdpoq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sweek.top/Article/details/gtgmwehous.html

[Q42] 连接条件附加过滤
来源：http://dali.jianghu66.top/Article/details/gtmxpqkqpm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.guowangkeji.top/Article/details/gtyoqhvqlk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ppjwa.cn/Article/details/gtzdaqsnxc.html

[Q43] 标量子查询
来源：http://dali.havefunace.top/Article/details/gtdnngsyxy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nanxuanxn.top/Article/details/gtrpwzqzmy.html

[Q44] IN 子查询
来源：http://dali.gaohongyu789.top/Article/details/gthwayyozr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nwbrower.top/Article/details/gtxflkfvvc.html

[Q45] EXISTS 判断存在
来源：http://dali.9152youxi.cn/Article/details/gtevmjysya.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtouhakknb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xinyue.icu/Article/details/gtptelhjoc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gteuwhgndn.html

[Q47] 与平均值比较
来源：http://dali.sweek.top/Article/details/gtpvxlwpis.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.meibo888.top/Article/details/gtjbxwsryr.html

[Q48] CTE 公用表表达式
来源：http://dali.sweek.top/Article/details/gtefbuivgv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkyiuvpkf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhongyouzk.top/Article/details/gtcskuppis.html

[Q49] 更新单行
来源：http://dali.bjfxy.top/Article/details/gtdppozyuo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xinyue.icu/Article/details/gtfvnpawqk.html

[Q50] 批量更新
来源：http://dali.9152youxi.cn/Article/details/gtewgqvaxg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhixingplan.top/Article/details/gtdsltxrlk.html

[Q51] 用子查询更新
来源：http://dali.cqqwz.cn/Article/details/gtyvpstxdx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xylfe.cn/Article/details/gtovupfakp.html

[Q52] 删除指定行
来源：http://dali.sufxvd.cn/Article/details/gtcyqoovgz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gtubkdlany.html

[Q53] 按条件删除
来源：http://dali.hammf.cn/Article/details/gtubhqvaho.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gogol.net.cn/Article/details/gtlcbfuooc.html

[Q54] 清空表
来源：http://dali.yuxming.cn/Article/details/gtjkoooicq.html

TRUNCATE TABLE logs;
来源：http://dali.yj202588.top/Article/details/gtcjmwswjg.html

[Q55] 排名（并列占位）
来源：http://dali.tanke756.top/Article/details/gtysjpofst.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gtrrswdagt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.havefunace.top/Article/details/gtbnpxrwnu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xinyue.icu/Article/details/gtbcdndhgk.html

[Q57] 行号
来源：http://dali.guannengcc.top/Article/details/gthqgdoetu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtjegtjfnp.html

[Q58] 累计求和
来源：http://dali.hongshengwenyu.top/Article/details/gtjvykylwi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtjiluuhmf.html

[Q59] 分组内累计
来源：http://dali.feifeiyinyue.top/Article/details/gthnnninps.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtaqcrcvfn.html

[Q60] 取上一行 / 下一行
来源：http://dali.jlsjyb.cn/Article/details/gtomjxtvyq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinqigfzy.top/Article/details/gtqivkjxgv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtipyargox.html

[Q61] 移动平均
来源：http://dali.chenzaomai.com/Article/details/gtrmletgcp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtqzdixbap.html

[Q62] 分组占比
来源：http://dali.9152youxi.cn/Article/details/gtcmaozval.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gtnzznvbuh.html

[Q63] 开启事务
来源：http://dali.dianchejie.cn/Article/details/gtmcddbdbm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shuidangran.top/Article/details/gtevwbcazv.html

[Q64] 提交事务
来源：http://dali.daria6918.cn/Article/details/gtfjfgmqwm.html

COMMIT;
来源：http://dali.haohaochexian.top/Article/details/gtnmjrwweo.html

[Q65] 回滚事务
来源：http://dali.guowangkeji.top/Article/details/gteopfuuah.html

ROLLBACK;
来源：http://dali.fengsongda.top/Article/details/gtdmztxrvn.html

[Q66] 行锁查询
来源：http://dali.pengpengdd.cyou/Article/details/gtkdcjwnys.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zycfv.cn/Article/details/gtdyrkplgw.html

[Q67] 设置隔离级别
来源：http://dali.ybcxt.top/Article/details/gtcjunnhef.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ydzc1.top/Article/details/gtehmrtjrg.html

[Q68] 保存点
来源：http://dali.chenlongwang.top/Article/details/gtuasdfsbu.html

SAVEPOINT sp1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrdvwrac.html

ROLLBACK TO sp1;
来源：http://dali.ppjwa.cn/Article/details/gtneprkwpx.html

[Q69] 查看执行计划
来源：http://dali.dashuyun.cn/Article/details/gtavymbwko.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gaohongyu789.top/Article/details/gtmjqtxjee.html

[Q70] 更新统计信息
来源：http://dali.birdmap.top/Article/details/gttsfseied.html

ANALYZE TABLE users;
来源：http://dali.cucudq.cn/Article/details/gtbbowcwfr.html

[Q71] 查看建表语句
来源：http://dali.ybcxt.top/Article/details/gthopjwttm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dashuyun.cn/Article/details/gtfnknquwv.html

[Q72] 查看索引
来源：http://dali.pycfn.com/Article/details/gttqleuwkr.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqtbwjrs.html

[Q73] 查看表状态
来源：http://dali.daria6918.cn/Article/details/gtmotjjdpp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hnxiangtu.top/Article/details/gtfcfdtndd.html

[Q74] 强制使用索引
来源：http://dali.bjfxy.top/Article/details/gtlvvpbxhy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sysykeji.top/Article/details/gtoxgqafwq.html

[Q75] 日期格式化
来源：http://dali.redwolf501.top/Article/details/gtjxwflahr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtwwpgprok.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.fzhhl.top/Article/details/gtdlfglssy.html

[Q76] 按天统计
来源：http://dali.nwbrower.top/Article/details/gtcajnllsv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hywenlv.cn/Article/details/gteicicrpl.html

[Q77] 时间加减
来源：http://dali.ppjwa.cn/Article/details/gtbtvyeakp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.9152youxi.cn/Article/details/gtheuzegux.html

[Q78] 当前时间
来源：http://dali.jinqigufen.top/Article/details/gtldzwrzsc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gotoacloud.top/Article/details/gtxqduiqun.html

[Q79] 字符串拼接
来源：http://dali.xuanzx.com/Article/details/gtgkxdwkrg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hywenlv.cn/Article/details/gtxkdbujzw.html

[Q80] 字符串截取
来源：http://dali.hnqzz.top/Article/details/gtgbglkvwl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cashguo.top/Article/details/gthmhfomtc.html

[Q81] 字符串替换
来源：http://dali.aizwys.cn/Article/details/gtdrbeiulk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tian-w.cn/Article/details/gtvwvlvcit.html

[Q82] 字符长度与字节长度
来源：http://dali.zdqjudy.top/Article/details/gtinzogxne.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtpvsvsodc.html

[Q83] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gtgraasssh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtrmekewlk.html

[Q84] 去除首尾空格
来源：http://dali.hywenlv.cn/Article/details/gtawdgtkix.html

SELECT TRIM(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtkhhmmgfk.html

[Q85] 数值取整
来源：http://dali.cucudq.cn/Article/details/gtsvbjngxd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hysaishi.cn/Article/details/gtokflqipi.html

[Q86] 读取 JSON 字段
来源：http://dali.hysaishi.cn/Article/details/gtaciegrgn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dashuyun.cn/Article/details/gtamkdbjeo.html

[Q87] JSON 字段做条件
来源：http://dali.c1oappe.top/Article/details/gtzxzbhovp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxuanxn.top/Article/details/gtpmttduja.html

[Q88] 行转列（条件聚合）
来源：http://dali.mhx1999.top/Article/details/gtoltbdqqp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqutllhax.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtflduublt.html

[Q89] 判断表是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gtnerwtfiv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tian-w.cn/Article/details/gtxnoqfqvd.html

[Q90] 生成序号列
来源：http://dali.nwbrower.top/Article/details/gtqyqtkvhn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.guannengcc.top/Article/details/gtsdlcqtbz.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtmmbbagbw.html

R. Bash 专题
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkafkzyos.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtblesgxxy.html

[R01] shebang 与严格模式
来源：http://dali.yuxming.cn/Article/details/gtxwjntizs.html

#!/usr/bin/env bash
来源：http://dali.ywan-chungtsiang.top/Article/details/gttydoaobv.html

set -euo pipefail
来源：http://dali.tianlin.xyz/Article/details/gtawoezbdl.html

[R02] 变量赋值与使用
来源：http://dali.jqgufenzy.top/Article/details/gtyycrzjqd.html

name="Tom"; echo "$name"
来源：http://dali.meibo888.top/Article/details/gtnxyngvlc.html

[R03] 只读变量
来源：http://dali.yanxiufei.cn/Article/details/gtrxwfmvro.html

readonly PI=3.14
来源：http://dali.haohaochexian.top/Article/details/gtfjwecjgw.html

[R04] 位置参数
来源：http://dali.zhengqikj.top/Article/details/gtcgserlko.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxuanxn.top/Article/details/gttmvpzzom.html

[R05] 参数默认值
来源：http://dali.cucudq.cn/Article/details/gtfruabdpf.html

name="${1:-default}"
来源：http://dali.yj20258.top/Article/details/gtgcpxsyey.html

[R06] 判断命令是否存在
来源：http://dali.cashguo.top/Article/details/gtbuifozmy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenlongwang.top/Article/details/gtwowwlhmr.html

[R07] if 判断文件
来源：http://dali.pycfn.com/Article/details/gtlvkhtlzj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.smart0.xyz/Article/details/gtnaqygwyc.html

[R08] 数值比较
来源：http://dali.aibaodan.cn/Article/details/gtfpzwfvus.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.meibo888.top/Article/details/gtaxuwwyte.html

[R09] 字符串比较
来源：http://dali.guannengcc.top/Article/details/gtjqmwmjxh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tanke756.top/Article/details/gtuwtuqapi.html

[R10] 正则匹配
来源：http://dali.daria6918.cn/Article/details/gtyzfghwpx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.birdmap.top/Article/details/gtpvbhcsbc.html

[R11] case 多分支
来源：http://dali.ydzc1.top/Article/details/gtopcpjdfr.html

case "$1" in
来源：http://dali.chenzaomai.com/Article/details/gtnpyzeqpy.html

start) echo "启动" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdeirqsbr.html

stop)  echo "停止" ;;
来源：http://dali.cdnleiting.top/Article/details/gtetleweob.html

*)     echo "未知命令" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gtrxmibnjf.html

esac
来源：http://dali.daria6918.cn/Article/details/gtjjrnfszd.html

[R12] for 遍历文件
来源：http://dali.sxryk.cn/Article/details/gtfhgkwohz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cdnleiting.top/Article/details/gtddjnrygp.html

[R13] for 计数循环
来源：http://dali.cashguo.top/Article/details/gtudbgybvy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhengqikj.top/Article/details/gtvimfnnfg.html

[R14] C 风格 for
来源：http://dali.nanxinkj.top/Article/details/gtdthpwtos.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gtbgkwjlpd.html

[R15] while 逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtbsucnkhs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fengsongda.top/Article/details/gtkuyryalc.html

[R16] until 等待条件
来源：http://dali.zhixingplan.top/Article/details/gtfnkdstle.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gtxbvxtjgd.html

[R17] 数组定义与取值
来源：http://dali.guannengcc.top/Article/details/gtomqadwni.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangdashe.top/Article/details/gtvjgnquri.html

[R18] 遍历数组
来源：http://dali.chenjidiqi.icu/Article/details/gtlbewodsf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtplithcxr.html

[R19] 数组长度
来源：http://dali.wangdashe.top/Article/details/gtemscvrfi.html

echo "${#arr[@]}"
来源：http://dali.jlsjyb.cn/Article/details/gtfvzimhaa.html

[R20] 关联数组（字典）
来源：http://dali.vqdsnc.cn/Article/details/gtczqlmcna.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.fzhhl.top/Article/details/gtjxptufsc.html

[R21] 字符串长度
来源：http://dali.jqgfzy.top/Article/details/gtavviycir.html

echo "${#s}"
来源：http://dali.yj20258888.top/Article/details/gtxwtjmhxs.html

[R22] 截取子串
来源：http://dali.shzxlz.cn/Article/details/gtmkvshatz.html

echo "${s:0:5}"
来源：http://dali.nanxuanxn.top/Article/details/gtqthxskjb.html

[R23] 字符串替换
来源：http://dali.yongpay.top/Article/details/gtybtssked.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj202588.top/Article/details/gtcjyehjsc.html

[R24] 大小写转换
来源：http://dali.yuanzhike.top/Article/details/gtjnnqnlvz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yonumen.top/Article/details/gtgopponzs.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuanzx.com/Article/details/gthshxkcuc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.haohaochexian.top/Article/details/gtntutsyme.html

[R26] 命令替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqtcapie.html

now=$(date +%F); echo "$now"
来源：http://dali.sufxvd.cn/Article/details/gtypvrrqqn.html

[R27] 算术展开
来源：http://dali.sysykeji.top/Article/details/gtsgyiyfzj.html

echo $((1 + 2 * 3))
来源：http://dali.xinyue.icu/Article/details/gtxvpwmjsv.html

[R28] 浮点运算
来源：http://dali.vqdsnc.cn/Article/details/gtglenbpfc.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinqigfzy.top/Article/details/gturuurshj.html

[R29] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gthzdtmtmm.html


<!-- 参考信息 -->