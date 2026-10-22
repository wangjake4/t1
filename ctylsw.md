代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gogol.net.cn/Article/details/gtsiwduwzk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxxylexs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj20258.top/Article/details/gtespyjxwy.html

PHP:  if (empty($x)) {}
来源：http://dali.nanxinkj.top/Article/details/gtwlrlesyh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gzhubu.top/Article/details/gtsgeatgwq.html

TS:   if (x == null) {}
来源：http://dali.shzxlz.cn/Article/details/gtirvwbqbg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gtngtnnmcu.html

Go:   if x == nil {}
来源：http://dali.cashguo.top/Article/details/gtefkgodms.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.9152youxi.cn/Article/details/gtjerpuzlf.html

C#:   if (x is null) {}
来源：http://dali.ppjwa.cn/Article/details/gtdrifvsun.html

[P07] 防抖与节流
来源：http://dali.c1oappe.top/Article/details/gtvutjzjur.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zdqjudy.top/Article/details/gtlktbrykz.html

PHP:  // 手写时间戳比较
来源：http://dali.shangyingyoupin.top/Article/details/gtltfrlyys.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gtqdnwaxmi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gtykttvpvv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hfpthk.cn/Article/details/gtmzvhoqas.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cqqwz.cn/Article/details/gtnsquxyth.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigufen.top/Article/details/gtivuinxbh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenlongwang.top/Article/details/gtdbfnwfkn.html

[P08] 处理浮点精度问题
来源：http://dali.shangyingyoupin.top/Article/details/gtuituoqvw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tanke756.top/Article/details/gtowgagkpy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.kuanghao11.cn/Article/details/gttlqqmbyy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pengpengdd.cyou/Article/details/gtbuqxeivo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xinyue.icu/Article/details/gtfcwkibnq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yanxiufei.cn/Article/details/gthfrxqzvi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnxiangtu.top/Article/details/gtgdxmqeya.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gotoacloud.top/Article/details/gtubhipygd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.iojbl.cn/Article/details/gtcuuvpbct.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtkasaeqhe.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.birdmap.top/Article/details/gtglksknta.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtihykbnzs.html

[Q01] 创建表
来源：http://dali.hywenlv.cn/Article/details/gtvnxlsuek.html

CREATE TABLE users (
来源：http://dali.yj20258.top/Article/details/gtvsimtpxt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.havefunace.top/Article/details/gtrlucnquq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cheryme.top/Article/details/gtvgvkfuyk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ppjwa.cn/Article/details/gtxcjcxrpp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nanxuanxn.top/Article/details/gtlemyiaol.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gtamuxiueo.html

[Q02] 创建带外键的表
来源：http://dali.yj20258.top/Article/details/gtjwwmlgtr.html

CREATE TABLE orders (
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgybzxin.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgodwocxe.html

user_id INT NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gtysbqauez.html

amount DECIMAL(10, 2),
来源：http://dali.shangyingyoupin.top/Article/details/gttofjlwkz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinqigfzy.top/Article/details/gtnckyhqek.html

);
来源：http://dali.yanxiufei.cn/Article/details/gtgyzbycjf.html

[Q03] 增加列
来源：http://dali.yj20258.top/Article/details/gtuhteudih.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cqqwz.cn/Article/details/gtuvedqmkl.html

[Q04] 修改列类型
来源：http://dali.cashguo.top/Article/details/gtaafsyelj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nanxuanxn.top/Article/details/gtjcpwgeza.html

[Q05] 重命名列
来源：http://dali.gotoacloud.top/Article/details/gtmlifzxsc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrkxrshzj.html

[Q06] 删除列
来源：http://dali.shangyingyoupin.top/Article/details/gtemionswm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmcfdjxbn.html

[Q07] 删除表
来源：http://dali.havefunace.top/Article/details/gtavppcski.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj20258.top/Article/details/gtbunxjkvb.html

[Q08] 创建普通索引
来源：http://dali.cdnleiting.top/Article/details/gtjtegyppa.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gtihkqqxhc.html

[Q09] 创建唯一索引
来源：http://dali.hywenlv.cn/Article/details/gtvrhegyco.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.svipenyu.cn/Article/details/gtlgdzzthj.html

[Q10] 插入单行
来源：http://dali.yangfankeji.com/Article/details/gtdpwririg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gzhubu.top/Article/details/gtapyxsuum.html

[Q11] 一次插入多行
来源：http://dali.quarkkingdee.top/Article/details/gtpzereayd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhixingplan.top/Article/details/gtwszyvhut.html

[Q12] 插入后取自增 ID
来源：http://dali.ppjwa.cn/Article/details/gtmrgfynuo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnqzz.top/Article/details/gtgstwyfqc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.vqdsnc.cn/Article/details/gtjowvdpfg.html

[Q13] 忽略重复插入
来源：http://dali.chenzaomai.com/Article/details/gtzftzulha.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gttbundfsq.html

[Q14] 存在则更新（upsert）
来源：http://dali.guannengcc.top/Article/details/gtadyxlfxp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jlsjyb.cn/Article/details/gtnyhyskxk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhixingplan.top/Article/details/gtshcuydlt.html

[Q15] 查询全部
来源：http://dali.hammf.cn/Article/details/gtbhwycehi.html

SELECT * FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtrujtbcfa.html

[Q16] 查询指定列
来源：http://dali.mhx1999.top/Article/details/gtaclfdrtn.html

SELECT id, name FROM users;
来源：http://dali.cdnleiting.top/Article/details/gthodzqeop.html

[Q17] 条件查询
来源：http://dali.yj20258888.top/Article/details/gtudluhvse.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hnqzz.top/Article/details/gttsqazpmf.html

[Q18] 模糊匹配
来源：http://dali.cdnleiting.top/Article/details/gtnrycdmme.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.316326.xyz/Article/details/gtwfmeeqdm.html

[Q19] 范围查询
来源：http://dali.cucudq.cn/Article/details/gtzooludvc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sxryk.cn/Article/details/gtbvqqtvir.html

[Q20] IN 列表
来源：http://dali.hammf.cn/Article/details/gtlxydjsax.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhengqikj.top/Article/details/gtqgysfczb.html

[Q21] 空值判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtssfdvjaf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzwgkdvx.html

[Q22] 排序
来源：http://dali.gaohongyu789.top/Article/details/gtllhcovfx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xuetiantiany.cn/Article/details/gtitkucgmb.html

[Q23] 分页
来源：http://dali.chenjidiqi.icu/Article/details/gtppwmwdni.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ivvv.top/Article/details/gtfscbwyyt.html

[Q24] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwznakxdm.html

SELECT DISTINCT city FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtshbjiydy.html

[Q25] 只取前 N 条
来源：http://dali.dashuyun.cn/Article/details/gtxojppwmy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.quarkkingdee.top/Article/details/gtwyainoxc.html

[Q26] 计数
来源：http://dali.andypj.xyz/Article/details/gtwhvhxzao.html

SELECT COUNT(*) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyoeeltez.html

[Q27] 条件计数
来源：http://dali.jqgfzy.top/Article/details/gtgrzftfof.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtlnsvbiiu.html

[Q28] 求和与平均
来源：http://dali.cheryme.top/Article/details/gthrsqcoca.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtvcyidvfn.html

[Q29] 最大最小值
来源：http://dali.zdqjudy.top/Article/details/gtmqsbwqby.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj202588.top/Article/details/gtgyrvhqgb.html

[Q30] 分组统计
来源：http://dali.gotoacloud.top/Article/details/gtlbzwnnmd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gtvgfnrbdu.html

[Q31] 分组后过滤
来源：http://dali.nanxinkj.top/Article/details/gtrcwgeijj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.dianchejie.cn/Article/details/gtdaupvygg.html

[Q32] 分组拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdnztbzx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gtdcahthyk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.redwolf501.top/Article/details/gtnttygdcl.html

[Q33] 多列分组
来源：http://dali.jqgfzy.top/Article/details/gtqdgdwjqs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinqigfzy.top/Article/details/gtxdearonr.html

[Q34] 每组取第一条
来源：http://dali.daria6918.cn/Article/details/gtcebzkfgh.html

SELECT * FROM (
来源：http://dali.yueranfly.top/Article/details/gtprwwueqo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hysaishi.cn/Article/details/gttnrxwjvu.html

) t WHERE rn = 1;
来源：http://dali.andypj.xyz/Article/details/gtozmtflwn.html

[Q35] 内连接
来源：http://dali.9152youxi.cn/Article/details/gtdnlawnsx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigufen.top/Article/details/gtvanupxou.html

[Q36] 左连接
来源：http://dali.tian-w.cn/Article/details/gtcpqentrq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cucudq.cn/Article/details/gtjutvcanf.html

[Q37] 右连接
来源：http://dali.jlsjyb.cn/Article/details/gtbxrjdfep.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yangfankeji.com/Article/details/gtjmikycef.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shzxlz.cn/Article/details/gtnrdrbkfl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgfzy.top/Article/details/gttbjevzuc.html

[Q39] 自连接（查上下级）
来源：http://dali.cdnleiting.top/Article/details/gtfafspkhw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gotoacloud.top/Article/details/gtvgbtwdpi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtinofzvzd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nwbrower.top/Article/details/gtbftwvjls.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenjidiqi.icu/Article/details/gtlmwrmjbx.html

[Q41] 多表连接
来源：http://dali.hywenlv.cn/Article/details/gtjgumboxp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gzhubu.top/Article/details/gtheybkqns.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gogol.net.cn/Article/details/gtgqltgrbx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.c1oappe.top/Article/details/gtkqbtqoqf.html

[Q42] 连接条件附加过滤
来源：http://dali.haohaochexian.top/Article/details/gtpxwmzoiz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigufen.top/Article/details/gtftxypqpt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.svipenyu.cn/Article/details/gtknctsycb.html

[Q43] 标量子查询
来源：http://dali.mhx1999.top/Article/details/gtvlaxfrst.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.meibo888.top/Article/details/gtgxxvbndp.html

[Q44] IN 子查询
来源：http://dali.jinqigufen.top/Article/details/gtqvgwljjf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj20258888.top/Article/details/gtewjuxrfb.html

[Q45] EXISTS 判断存在
来源：http://dali.jlsjyb.cn/Article/details/gtbiqhhigk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gogol.net.cn/Article/details/gtocgmjkci.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fzhhl.top/Article/details/gtqdpxxgud.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gtjxfswsmf.html

[Q47] 与平均值比较
来源：http://dali.gzhubu.top/Article/details/gtfkfvrldn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xziqi.cn/Article/details/gthumyxidi.html

[Q48] CTE 公用表表达式
来源：http://dali.yj20258.top/Article/details/gtylwpcfam.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sufxvd.cn/Article/details/gtvcyhndxq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.dashuyun.cn/Article/details/gtyctjssjv.html

[Q49] 更新单行
来源：http://dali.zycfv.cn/Article/details/gtqzvumgqm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj202588.top/Article/details/gtbhoyozuv.html

[Q50] 批量更新
来源：http://dali.yvedp.cn/Article/details/gtkzfinoro.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cheryme.top/Article/details/gtjqckhyqd.html

[Q51] 用子查询更新
来源：http://dali.xziqi.cn/Article/details/gtzdkugryl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zycfv.cn/Article/details/gtyvvphtzt.html

[Q52] 删除指定行
来源：http://dali.yj202588.top/Article/details/gtpcilzcza.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cqqwz.cn/Article/details/gtqofphsxc.html

[Q53] 按条件删除
来源：http://dali.chenlongwang.top/Article/details/gtwszujova.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenzaomai.com/Article/details/gtxupbexli.html

[Q54] 清空表
来源：http://dali.jinqigufen.top/Article/details/gtqdeowxql.html

TRUNCATE TABLE logs;
来源：http://dali.zhoulong.xyz/Article/details/gtiscwyrwq.html

[Q55] 排名（并列占位）
来源：http://dali.aibaodan.cn/Article/details/gtzkeycthg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jianghu66.top/Article/details/gtlndhcfxk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gtisqjaspo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yuanzhike.top/Article/details/gtrtfboowh.html

[Q57] 行号
来源：http://dali.snrcjt.cn/Article/details/gttxipumqn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtsoemybns.html

[Q58] 累计求和
来源：http://dali.gotoacloud.top/Article/details/gtamqsatvt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtpubrgepg.html

[Q59] 分组内累计
来源：http://dali.tanke756.top/Article/details/gtocavwhfw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtvwyexglv.html

[Q60] 取上一行 / 下一行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdjiaphw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.havefunace.top/Article/details/gtjjtqfjam.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtrugzyhdo.html

[Q61] 移动平均
来源：http://dali.chenlongwang.top/Article/details/gtlxhomzzu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtgkfctefi.html

[Q62] 分组占比
来源：http://dali.wangdashe.top/Article/details/gtdauffxwf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gtcychdpvt.html

[Q63] 开启事务
来源：http://dali.xuanzx.com/Article/details/gtxrdnzrfw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cdnleiting.top/Article/details/gtvsovsfbn.html

[Q64] 提交事务
来源：http://dali.yj20258888.top/Article/details/gtdirrvywz.html

COMMIT;
来源：http://dali.zhoulong.xyz/Article/details/gtkcvxqfvj.html

[Q65] 回滚事务
来源：http://dali.jianghu66.top/Article/details/gtgvmpchtz.html

ROLLBACK;
来源：http://dali.birdmap.top/Article/details/gtryvqpdwg.html

[Q66] 行锁查询
来源：http://dali.feifeiyinyue.top/Article/details/gtebkwqpjd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenlongwang.top/Article/details/gtqhpqiczz.html

[Q67] 设置隔离级别
来源：http://dali.nanxinkj.top/Article/details/gthtdunakb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgfzy.top/Article/details/gtcznuqrrf.html

[Q68] 保存点
来源：http://dali.yj20258888.top/Article/details/gtnugcdbvn.html

SAVEPOINT sp1;
来源：http://dali.shzxlz.cn/Article/details/gtnehxswed.html

ROLLBACK TO sp1;
来源：http://dali.cdnleiting.top/Article/details/gteihtwgay.html

[Q69] 查看执行计划
来源：http://dali.jianghu66.top/Article/details/gtdsshgqfm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ybcxt.top/Article/details/gtqdssfsve.html

[Q70] 更新统计信息
来源：http://dali.daria6918.cn/Article/details/gtmujdpasr.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gtcwmnixnh.html

[Q71] 查看建表语句
来源：http://dali.shanyushiyangtech.top/Article/details/gtxpmbuiwk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinqigufen.top/Article/details/gtphdozrhc.html

[Q72] 查看索引
来源：http://dali.fzhhl.top/Article/details/gtyxwlxujb.html

SHOW INDEX FROM users;
来源：http://dali.xziqi.cn/Article/details/gtpzlscxvv.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gtazezsubg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hammf.cn/Article/details/gtkedlzcse.html

[Q74] 强制使用索引
来源：http://dali.sxryk.cn/Article/details/gtobhztlmd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tian-w.cn/Article/details/gtmftjowko.html

[Q75] 日期格式化
来源：http://dali.bjfxy.top/Article/details/gtvmqadxxd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtgeglrsal.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gogol.net.cn/Article/details/gtvtneohwa.html

[Q76] 按天统计
来源：http://dali.zhengqikj.top/Article/details/gtdubssyvj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.haohaochexian.top/Article/details/gtduaumdgb.html

[Q77] 时间加减
来源：http://dali.smart0.xyz/Article/details/gtplbjmbtl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhojdrvd.html

[Q78] 当前时间
来源：http://dali.guannengcc.top/Article/details/gtslrzulql.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gzhubu.top/Article/details/gtiwrprlsa.html

[Q79] 字符串拼接
来源：http://dali.wangshuangyany.cn/Article/details/gtezcxhjgf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jlsjyb.cn/Article/details/gtsrwbovwy.html

[Q80] 字符串截取
来源：http://dali.yangfankeji.com/Article/details/gtlyydthbb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtechobeic.html

[Q81] 字符串替换
来源：http://dali.jlsjyb.cn/Article/details/gtahjokfyj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtcvbakfxq.html

[Q82] 字符长度与字节长度
来源：http://dali.fengsongda.top/Article/details/gtnbprlzkp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtzmnmztdk.html

[Q83] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gteizvyqvy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gtfwxtwjyr.html

[Q84] 去除首尾空格
来源：http://dali.mhx1999.top/Article/details/gtnusxcrnu.html

SELECT TRIM(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtdkvjovfm.html

[Q85] 数值取整
来源：http://dali.zycfv.cn/Article/details/gtxddlomxp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvpztovhy.html

[Q86] 读取 JSON 字段
来源：http://dali.xinyue.icu/Article/details/gtcealfilb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.svipenyu.cn/Article/details/gtvzggkfpw.html

[Q87] JSON 字段做条件
来源：http://dali.yonumen.top/Article/details/gtqxwvtlpy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhengqikj.top/Article/details/gtnmvtjfpk.html

[Q88] 行转列（条件聚合）
来源：http://dali.gogol.net.cn/Article/details/gtnmgowklq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sysykeji.top/Article/details/gtaozjhofm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.aizwys.cn/Article/details/gtknqbkxzr.html

[Q89] 判断表是否存在
来源：http://dali.daria6918.cn/Article/details/gtbrwrvlfn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.guowangkeji.top/Article/details/gtplegxfrl.html

[Q90] 生成序号列
来源：http://dali.cdnleiting.top/Article/details/gtpaykgvpg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.fengsongda.top/Article/details/gtqtydpzmq.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtfzalztse.html

R. Bash 专题
来源：http://dali.yj202588.top/Article/details/gtapnbzscx.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gttstsanco.html

[R01] shebang 与严格模式
来源：http://dali.tianlin.xyz/Article/details/gtkvejqfkk.html

#!/usr/bin/env bash
来源：http://dali.sufxvd.cn/Article/details/gtnckqxzag.html

set -euo pipefail
来源：http://dali.quarkkingdee.top/Article/details/gtgytyojua.html

[R02] 变量赋值与使用
来源：http://dali.ivvv.top/Article/details/gtewbvaqvb.html

name="Tom"; echo "$name"
来源：http://dali.cucudq.cn/Article/details/gthisdvbls.html

[R03] 只读变量
来源：http://dali.zycfv.cn/Article/details/gtyqxgyxnt.html

readonly PI=3.14
来源：http://dali.gzhubu.top/Article/details/gtbvzsyngx.html

[R04] 位置参数
来源：http://dali.xuetiantiany.cn/Article/details/gtkrkiqomq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258888.top/Article/details/gttuaodtaf.html

[R05] 参数默认值
来源：http://dali.316326.xyz/Article/details/gtrovfgega.html

name="${1:-default}"
来源：http://dali.nwbrower.top/Article/details/gtsufvgftr.html

[R06] 判断命令是否存在
来源：http://dali.havefunace.top/Article/details/gtmuewqeta.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.haohaochexian.top/Article/details/gtmlocwsfj.html

[R07] if 判断文件
来源：http://dali.cqqwz.cn/Article/details/gtammdnfas.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtqytrojms.html

[R08] 数值比较
来源：http://dali.iojbl.cn/Article/details/gtlznlcyqr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhixingplan.top/Article/details/gtawauliuv.html

[R09] 字符串比较
来源：http://dali.mhx1999.top/Article/details/gtwcsyxqtc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cucudq.cn/Article/details/gtbpqfhajp.html

[R10] 正则匹配
来源：http://dali.bjfxy.top/Article/details/gtglerespd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtcojfvdrg.html

[R11] case 多分支
来源：http://dali.jinqigufen.top/Article/details/gtlrxjtxov.html

case "$1" in
来源：http://dali.haohaochexian.top/Article/details/gtmvyqkhoj.html

start) echo "启动" ;;
来源：http://dali.nanxinkj.top/Article/details/gteaxzmojv.html

stop)  echo "停止" ;;
来源：http://dali.nanxinkj.top/Article/details/gthzfomsvw.html

*)     echo "未知命令" ;;
来源：http://dali.redwolf501.top/Article/details/gttabnoyby.html

esac
来源：http://dali.guannengcc.top/Article/details/gtwfutlplm.html

[R12] for 遍历文件
来源：http://dali.zhongyouzk.top/Article/details/gtzqekuewy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yuanzhike.top/Article/details/gtkpbeowpm.html

[R13] for 计数循环
来源：http://dali.svipenyu.cn/Article/details/gtyhywiyro.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gthewebgva.html

[R14] C 风格 for
来源：http://dali.ivvv.top/Article/details/gtvwzahgpo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tanke756.top/Article/details/gtduqnabxe.html

[R15] while 逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtmemtmymw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.haohaochexian.top/Article/details/gtjfqylzfr.html

[R16] until 等待条件
来源：http://dali.zhiwuduotai.top/Article/details/gtenjnofae.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gtufznjvsn.html

[R17] 数组定义与取值
来源：http://dali.cheryme.top/Article/details/gtxweludep.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258888.top/Article/details/gtkyxkjoup.html

[R18] 遍历数组
来源：http://dali.xziqi.cn/Article/details/gtbzwmwtka.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj20258888.top/Article/details/gtbhaaghmu.html

[R19] 数组长度
来源：http://dali.shuidangran.top/Article/details/gtaaveqymx.html

echo "${#arr[@]}"
来源：http://dali.hnqzz.top/Article/details/gtqhsnmnhd.html

[R20] 关联数组（字典）
来源：http://dali.svipenyu.cn/Article/details/gtgkcjkenv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ppjwa.cn/Article/details/gtcuywizze.html

[R21] 字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxqvprcb.html

echo "${#s}"
来源：http://dali.jqgufenzy.top/Article/details/gtjpsffkxh.html

[R22] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gtbwwckskt.html

echo "${s:0:5}"
来源：http://dali.cdnleiting.top/Article/details/gtcuzvdqlo.html

[R23] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gtchrtirlg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hfpthk.cn/Article/details/gtvukkctuh.html

[R24] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gtpcgfbqsx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tianlin.xyz/Article/details/gthznzzzic.html

[R25] 去后缀 / 去前缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamofsmjd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yvedp.cn/Article/details/gtlesnkmld.html

[R26] 命令替换
来源：http://dali.c1oappe.top/Article/details/gturtegrhy.html

now=$(date +%F); echo "$now"
来源：http://dali.aibaodan.cn/Article/details/gtxggylhrg.html

[R27] 算术展开
来源：http://dali.ydzc1.top/Article/details/gtufbuqjes.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gthsmeurdi.html

[R28] 浮点运算
来源：http://dali.shangyingyoupin.top/Article/details/gtvhopwoxz.html

echo "scale=2; 10/3" | bc
来源：http://dali.tanke756.top/Article/details/gtrgqwsffi.html

[R29] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gtteomibdm.html


<!-- 参考信息 -->