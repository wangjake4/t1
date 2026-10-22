代发 wailian999

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.mhx1999.top/Article/details/gt2yshujxhz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenlongwang.top/Article/details/gt2rstontwu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yueranfly.top/Article/details/gt2bpqsvscb.html

Ruby: a == b
来源：http://dali.xuetiantiany.cn/Article/details/gt2dvvzvdov.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ppjwa.cn/Article/details/gt2gcbqhrgk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cheryme.top/Article/details/gt2gwwecvvb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinqigufen.top/Article/details/gt2ilelukve.html

PHP:  if (empty($x)) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2lkkwnvvx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tianlin.xyz/Article/details/gt2nxcejoqm.html

TS:   if (x == null) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2awdcwmig.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.fzhhl.top/Article/details/gt2ccqwvcli.html

Go:   if x == nil {}
来源：http://dali.tian-w.cn/Article/details/gt2rodebrtg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.andypj.xyz/Article/details/gt2oobjdlrj.html

C#:   if (x is null) {}
来源：http://dali.fengsongda.top/Article/details/gt2bsvvsomg.html

[P07] 防抖与节流
来源：http://dali.zhiwuduotai.top/Article/details/gt2txytezin.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iukviyrv.html

PHP:  // 手写时间戳比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2drbxomiv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gt2ptxlmove.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gt2sqlqmvgu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ygqjixlc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yonumen.top/Article/details/gt2mhqydjtp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sxryk.cn/Article/details/gt2fqtyclzc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qxdnxzaz.html

[P08] 处理浮点精度问题
来源：http://dali.pycfn.com/Article/details/gt2kkpipsef.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cucudq.cn/Article/details/gt2gcnrxavc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ehwqpu.com/Article/details/gt2wzxpjvnh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hnxiangtu.top/Article/details/gt2lcfdzhgf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bzdexkxi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.daxiang520.top/Article/details/gt2uuimwppf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yvedp.cn/Article/details/gt2kzddhjfk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xylfe.cn/Article/details/gt2vvicutlo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2eobyfcap.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2mdeumnna.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xinyue.icu/Article/details/gt2igzngtrw.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2auhnjqeu.html

[Q01] 创建表
来源：http://dali.chenjidiqi.icu/Article/details/gt2xeiplpdu.html

CREATE TABLE users (
来源：http://dali.jqgfzy.top/Article/details/gt2ppgitgtz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenzaomai.com/Article/details/gt2iknnuhjj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fehxpmsa.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gogol.net.cn/Article/details/gt2rwzosgqn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2btgsatsn.html

);
来源：http://dali.sxryk.cn/Article/details/gt2cgrqwlhb.html

[Q02] 创建带外键的表
来源：http://dali.smart0.xyz/Article/details/gt2wfffsyej.html

CREATE TABLE orders (
来源：http://dali.zhiwuduotai.top/Article/details/gt2levldzun.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dguightp.html

user_id INT NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gt2zoqrlmns.html

amount DECIMAL(10, 2),
来源：http://dali.pengpengdd.cyou/Article/details/gt2usfnzywt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hysaishi.cn/Article/details/gt2zwjmdywc.html

);
来源：http://dali.snrcjt.cn/Article/details/gt2yrnhczom.html

[Q03] 增加列
来源：http://dali.birdmap.top/Article/details/gt2lrwpbjwd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hysaishi.cn/Article/details/gt2jmtsgeck.html

[Q04] 修改列类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2wvakclpa.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.redwolf501.top/Article/details/gt2nsfjbxcc.html

[Q05] 重命名列
来源：http://dali.dashuyun.cn/Article/details/gt2dsiicktt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2vamuifya.html

[Q06] 删除列
来源：http://dali.dianchejie.cn/Article/details/gt2fkwevodb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jiagoushi.top/Article/details/gt2fagozfye.html

[Q07] 删除表
来源：http://dali.bjfxy.top/Article/details/gt2fnloukim.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jqgfzy.top/Article/details/gt2hhahnsam.html

[Q08] 创建普通索引
来源：http://dali.haohaochexian.top/Article/details/gt2nqzyofgv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.kuanghao11.cn/Article/details/gt2ejglcqqf.html

[Q09] 创建唯一索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kpdbkzfl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cashguo.top/Article/details/gt2juqpgzas.html

[Q10] 插入单行
来源：http://dali.jqgfzy.top/Article/details/gt2alhouewa.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sufxvd.cn/Article/details/gt2hlsacvej.html

[Q11] 一次插入多行
来源：http://dali.sweek.top/Article/details/gt2hyrzrxyx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.iojbl.cn/Article/details/gt2wxdyfohc.html

[Q12] 插入后取自增 ID
来源：http://dali.yangfankeji.com/Article/details/gt2macicbwa.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xziqi.cn/Article/details/gt2rnrnmpcu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hywenlv.cn/Article/details/gt2akdomphg.html

[Q13] 忽略重复插入
来源：http://dali.shzxlz.cn/Article/details/gt2eouekqac.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dianchejie.cn/Article/details/gt2lobgcqbv.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhengqikj.top/Article/details/gt2kbigajmy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yuanzhike.top/Article/details/gt2efcrzhgm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinqigufen.top/Article/details/gt2xhloqicf.html

[Q15] 查询全部
来源：http://dali.zhongyouzk.top/Article/details/gt2jitkootc.html

SELECT * FROM users;
来源：http://dali.yongpay.top/Article/details/gt2ugbgwvzy.html

[Q16] 查询指定列
来源：http://dali.316326.xyz/Article/details/gt2ahbqqpzj.html

SELECT id, name FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2hnufhpld.html

[Q17] 条件查询
来源：http://dali.snrcjt.cn/Article/details/gt2dqshmbvf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2xvpgubsg.html

[Q18] 模糊匹配
来源：http://dali.cheryme.top/Article/details/gt2ntisdiob.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zdqjudy.top/Article/details/gt2bobnpfpp.html

[Q19] 范围查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zwceqfxq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.wangshuangyany.cn/Article/details/gt2wajxfybm.html

[Q20] IN 列表
来源：http://dali.yj202588.top/Article/details/gt2hszrbtcf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.pycfn.com/Article/details/gt2ykntmpno.html

[Q21] 空值判断
来源：http://dali.vqdsnc.cn/Article/details/gt2bsmkbkpu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjgccxj.html

[Q22] 排序
来源：http://dali.xylfe.cn/Article/details/gt2cwylsuus.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cashguo.top/Article/details/gt2qwqapiiy.html

[Q23] 分页
来源：http://dali.yangfankeji.com/Article/details/gt2vfmvcodg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hammf.cn/Article/details/gt2pwgxzdhz.html

[Q24] 去重
来源：http://dali.yj202588.top/Article/details/gt2inagphdg.html

SELECT DISTINCT city FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2yqtjfeaf.html

[Q25] 只取前 N 条
来源：http://dali.jyoumei.cn/Article/details/gt2zaifoiza.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.andypj.xyz/Article/details/gt2brrsueiw.html

[Q26] 计数
来源：http://dali.hywenlv.cn/Article/details/gt2diwkcewr.html

SELECT COUNT(*) FROM users;
来源：http://dali.pycfn.com/Article/details/gt2jscqjbzr.html

[Q27] 条件计数
来源：http://dali.xziqi.cn/Article/details/gt2xoajpdwz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2swpzbsdp.html

[Q28] 求和与平均
来源：http://dali.aibaodan.cn/Article/details/gt2wcerynmn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gt2fuuzgxjz.html

[Q29] 最大最小值
来源：http://dali.cdnleiting.top/Article/details/gt2bydxwfot.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2zsnyansa.html

[Q30] 分组统计
来源：http://dali.gogol.net.cn/Article/details/gt2npfbaqbv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zjviadhb.html

[Q31] 分组后过滤
来源：http://dali.fengsongda.top/Article/details/gt2ujswcspe.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hfpthk.cn/Article/details/gt2wqzlsrhq.html

[Q32] 分组拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gt2tpxuwnmd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gt2jkocdsvh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yuanzhike.top/Article/details/gt2juopljzk.html

[Q33] 多列分组
来源：http://dali.gaohongyu789.top/Article/details/gt2ejsfcuxs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ehwqpu.com/Article/details/gt2pzmfsciz.html

[Q34] 每组取第一条
来源：http://dali.hysaishi.cn/Article/details/gt2cfkrnonm.html

SELECT * FROM (
来源：http://dali.shangyingyoupin.top/Article/details/gt2yzwkbcpa.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nanxinkj.top/Article/details/gt2yiswzjmr.html

) t WHERE rn = 1;
来源：http://dali.pycfn.com/Article/details/gt2jzupyzxz.html

[Q35] 内连接
来源：http://dali.cdnleiting.top/Article/details/gt2wfntlgsh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yongpay.top/Article/details/gt2ckkcamlw.html

[Q36] 左连接
来源：http://dali.yongpay.top/Article/details/gt2rmbdbrak.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pmwiyquy.html

[Q37] 右连接
来源：http://dali.zdqjudy.top/Article/details/gt2uydeqlap.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gogol.net.cn/Article/details/gt2yoppzwmh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gtxpqgdh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmoavteh.html

[Q39] 自连接（查上下级）
来源：http://dali.xziqi.cn/Article/details/gt2bgnzhfiq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daria6918.cn/Article/details/gt2arvcplwy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gotoacloud.top/Article/details/gt2zikiqccr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sysykeji.top/Article/details/gt2smdtntht.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nanxinkj.top/Article/details/gt2mspzursr.html

[Q41] 多表连接
来源：http://dali.jqgufenzy.top/Article/details/gt2bokiggui.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shuidangran.top/Article/details/gt2dlmjping.html

JOIN users u ON u.id = o.user_id
来源：http://dali.vqdsnc.cn/Article/details/gt2eubyqdil.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.haohaochexian.top/Article/details/gt2qksevftv.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxinkj.top/Article/details/gt2idytjoff.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jqgufenzy.top/Article/details/gt2gztxcnxo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cheryme.top/Article/details/gt2ohrktoqw.html

[Q43] 标量子查询
来源：http://dali.jyoumei.cn/Article/details/gt2rmggqgqh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shangyingyoupin.top/Article/details/gt2gfatknbd.html

[Q44] IN 子查询
来源：http://dali.nanxuanxn.top/Article/details/gt2qcngqwet.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.guowangkeji.top/Article/details/gt2lsffdzmw.html

[Q45] EXISTS 判断存在
来源：http://dali.hongshengwenyu.top/Article/details/gt2nzzruggr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hammf.cn/Article/details/gt2cjdqcocm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sysykeji.top/Article/details/gt2popstkzt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gt2jhydqyyt.html

[Q47] 与平均值比较
来源：http://dali.zycfv.cn/Article/details/gt2ajtucmjx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jianghu66.top/Article/details/gt2zqhkybch.html

[Q48] CTE 公用表表达式
来源：http://dali.birdmap.top/Article/details/gt2vdqgpbjt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhongyouzk.top/Article/details/gt2kqohkval.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dnneoxhh.html

[Q49] 更新单行
来源：http://dali.iojbl.cn/Article/details/gt2xyavyjma.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gt2dzgzaikc.html

[Q50] 批量更新
来源：http://dali.ehwqpu.com/Article/details/gt2fpzcinth.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shangyingyoupin.top/Article/details/gt2ikiqnxlf.html

[Q51] 用子查询更新
来源：http://dali.nwbrower.top/Article/details/gt2suprhvae.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2rnbmbiww.html

[Q52] 删除指定行
来源：http://dali.tian-w.cn/Article/details/gt2qsgthjzi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gt2kmemskxv.html

[Q53] 按条件删除
来源：http://dali.pengpengdd.cyou/Article/details/gt2dthgcboa.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.redwolf501.top/Article/details/gt2iiyimnfu.html

[Q54] 清空表
来源：http://dali.dashuyun.cn/Article/details/gt2qtzaopdv.html

TRUNCATE TABLE logs;
来源：http://dali.havefunace.top/Article/details/gt2arexxdua.html

[Q55] 排名（并列占位）
来源：http://dali.dashuyun.cn/Article/details/gt2huescqnm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gt2cpqfmbtr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hysaishi.cn/Article/details/gt2nvbsaihs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gt2uqqppjyb.html

[Q57] 行号
来源：http://dali.sufxvd.cn/Article/details/gt2nurvqnos.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2jnoyvsbz.html

[Q58] 累计求和
来源：http://dali.xziqi.cn/Article/details/gt2kxcpvzcs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.iojbl.cn/Article/details/gt2richdzvy.html

[Q59] 分组内累计
来源：http://dali.zycfv.cn/Article/details/gt2srpxxmef.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2uplzwtis.html

[Q60] 取上一行 / 下一行
来源：http://dali.zdqjudy.top/Article/details/gt2wxqxyvpb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.smart0.xyz/Article/details/gt2dywzibyh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2bquolirw.html

[Q61] 移动平均
来源：http://dali.0kj1m.cn/Article/details/gt2bxybflao.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2gdirrggm.html

[Q62] 分组占比
来源：http://dali.zycfv.cn/Article/details/gt2xznjtjcm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gt2sxoafmhj.html

[Q63] 开启事务
来源：http://dali.cheryme.top/Article/details/gt2hykvnprk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tanke756.top/Article/details/gt2wwuflqpg.html

[Q64] 提交事务
来源：http://dali.gaohongyu789.top/Article/details/gt2lxbdhucr.html

COMMIT;
来源：http://dali.xinyue.icu/Article/details/gt2ttdiyxwx.html

[Q65] 回滚事务
来源：http://dali.dianchejie.cn/Article/details/gt2gwfvpnpo.html

ROLLBACK;
来源：http://dali.c1oappe.top/Article/details/gt2fzdqyexe.html

[Q66] 行锁查询
来源：http://dali.gotoacloud.top/Article/details/gt2rhctxxzb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.pengpengdd.cyou/Article/details/gt2gbfvzrxr.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fowfoxbs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hnqzz.top/Article/details/gt2odimjuxi.html

[Q68] 保存点
来源：http://dali.andypj.xyz/Article/details/gt2gdiyxjiw.html

SAVEPOINT sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vtgqftsh.html

ROLLBACK TO sp1;
来源：http://dali.shzxlz.cn/Article/details/gt2jwpnxnjj.html

[Q69] 查看执行计划
来源：http://dali.hysaishi.cn/Article/details/gt2xqcvculo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.quarkkingdee.top/Article/details/gt2hzsqxkzm.html

[Q70] 更新统计信息
来源：http://dali.daria6918.cn/Article/details/gt2smnwndkv.html

ANALYZE TABLE users;
来源：http://dali.jlsjyb.cn/Article/details/gt2xcwkilnt.html

[Q71] 查看建表语句
来源：http://dali.snrcjt.cn/Article/details/gt2lxtljwuu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hywenlv.cn/Article/details/gt2ouwoutee.html

[Q72] 查看索引
来源：http://dali.tian-w.cn/Article/details/gt2thtllogc.html

SHOW INDEX FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qltnoztf.html

[Q73] 查看表状态
来源：http://dali.yangfankeji.com/Article/details/gt2leafvmre.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nanxuanxn.top/Article/details/gt2tjplrnqj.html

[Q74] 强制使用索引
来源：http://dali.chenjidiqi.icu/Article/details/gt2ejznuitw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jyjyixux.html

[Q75] 日期格式化
来源：http://dali.0kj1m.cn/Article/details/gt2emlapdxs.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj202588.top/Article/details/gt2irtifadv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.mhx1999.top/Article/details/gt2cvmekwfi.html

[Q76] 按天统计
来源：http://dali.jinghuilouyu.cn/Article/details/gt2remgnpvz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.316326.xyz/Article/details/gt2dnxbupyk.html

[Q77] 时间加减
来源：http://dali.tanke756.top/Article/details/gt2kypjwvlm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hysaishi.cn/Article/details/gt2qpwogbfd.html

[Q78] 当前时间
来源：http://dali.aibaodan.cn/Article/details/gt2qwjvcrlm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.snrcjt.cn/Article/details/gt2bpqjpwfw.html

[Q79] 字符串拼接
来源：http://dali.pycfn.com/Article/details/gt2dwfawqpd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinqigfzy.top/Article/details/gt2tjrtudkz.html

[Q80] 字符串截取
来源：http://dali.316326.xyz/Article/details/gt2ulkwwidn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2mtgwvjmu.html

[Q81] 字符串替换
来源：http://dali.zhoulong.xyz/Article/details/gt2kvsisymw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2uifbftll.html

[Q82] 字符长度与字节长度
来源：http://dali.dianchejie.cn/Article/details/gt2berwaxce.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2qsrntjmz.html

[Q83] 大小写转换
来源：http://dali.yonumen.top/Article/details/gt2qvkurvln.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2dmeyijmq.html

[Q84] 去除首尾空格
来源：http://dali.chenlongwang.top/Article/details/gt2avtngcwv.html

SELECT TRIM(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2fbkiqznv.html

[Q85] 数值取整
来源：http://dali.pengpengdd.cyou/Article/details/gt2jvfvcwvt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.9152youxi.cn/Article/details/gt2gosdbixx.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258.top/Article/details/gt2zkwajoca.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aibaodan.cn/Article/details/gt2azzgxcjx.html

[Q87] JSON 字段做条件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tdcqbeqm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cdnleiting.top/Article/details/gt2nbvqurnw.html

[Q88] 行转列（条件聚合）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2reyskiub.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.fengsongda.top/Article/details/gt2wninzahj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2krpxtaia.html

[Q89] 判断表是否存在
来源：http://dali.ivvv.top/Article/details/gt2gyseqksv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgfzy.top/Article/details/gt2iyunzjhy.html

[Q90] 生成序号列
来源：http://dali.zdqjudy.top/Article/details/gt2cqmvdrsk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj202588.top/Article/details/gt2hizzhybh.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2pdzhlcix.html

R. Bash 专题
来源：http://dali.wangdashe.top/Article/details/gt2rnboptxw.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2tjbirnls.html

[R01] shebang 与严格模式
来源：http://dali.yongpay.top/Article/details/gt2rrspqrqn.html

#!/usr/bin/env bash
来源：http://dali.kuanghao11.cn/Article/details/gt2owzxjuzo.html

set -euo pipefail
来源：http://dali.jqgufenzy.top/Article/details/gt2umgxsqoq.html

[R02] 变量赋值与使用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uhsrrdjb.html

name="Tom"; echo "$name"
来源：http://dali.jinqigufen.top/Article/details/gt2yyjalgnr.html

[R03] 只读变量
来源：http://dali.fzhhl.top/Article/details/gt2fpwqxhmb.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2bphwzwck.html

[R04] 位置参数
来源：http://dali.yj20258888.top/Article/details/gt2yfefbqmq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gzhubu.top/Article/details/gt2ylxzmbka.html

[R05] 参数默认值
来源：http://dali.jqgfzy.top/Article/details/gt2kgonqclw.html

name="${1:-default}"
来源：http://dali.daria6918.cn/Article/details/gt2vfnxyevt.html

[R06] 判断命令是否存在
来源：http://dali.zhixingplan.top/Article/details/gt2wnqofmbj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinqigufen.top/Article/details/gt2bljgykon.html

[R07] if 判断文件
来源：http://dali.gaohongyu789.top/Article/details/gt2faptqosd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.snrcjt.cn/Article/details/gt2vrklsoia.html

[R08] 数值比较
来源：http://dali.ybcxt.top/Article/details/gt2znzfxmaq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.pycfn.com/Article/details/gt2nlmnbwnl.html

[R09] 字符串比较
来源：http://dali.hysaishi.cn/Article/details/gt2fstcamhw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gt2otkdzbvt.html

[R10] 正则匹配
来源：http://dali.smart0.xyz/Article/details/gt2kepudxai.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.mhx1999.top/Article/details/gt2alzuicbv.html

[R11] case 多分支
来源：http://dali.jyoumei.cn/Article/details/gt2xkdndjps.html

case "$1" in
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nevvamyx.html

start) echo "启动" ;;
来源：http://dali.cdnleiting.top/Article/details/gt2fuhygdyr.html

stop)  echo "停止" ;;
来源：http://dali.chenzaomai.com/Article/details/gt2argfbsqo.html

*)     echo "未知命令" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gt2oopubozh.html

esac
来源：http://dali.xziqi.cn/Article/details/gt2nzbtkpah.html

[R12] for 遍历文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pkydpibk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2grpuojeb.html

[R13] for 计数循环
来源：http://dali.fengsongda.top/Article/details/gt2nuykakco.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmirxst.html

[R14] C 风格 for
来源：http://dali.shangyingyoupin.top/Article/details/gt2uvruayep.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hnqzz.top/Article/details/gt2dwpaainx.html

[R15] while 逐行读文件
来源：http://dali.yongpay.top/Article/details/gt2abwhfmbo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.havefunace.top/Article/details/gt2jfqkecgf.html

[R16] until 等待条件
来源：http://dali.xuetiantiany.cn/Article/details/gt2fshvhqik.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gt2kpnewkcz.html

[R17] 数组定义与取值
来源：http://dali.pycfn.com/Article/details/gt2hsndhgje.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yanxiufei.cn/Article/details/gt2ygbtsydm.html

[R18] 遍历数组
来源：http://dali.9152youxi.cn/Article/details/gt2lvoyysji.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sysykeji.top/Article/details/gt2mprreogd.html

[R19] 数组长度
来源：http://dali.yongpay.top/Article/details/gt2gssyqzij.html

echo "${#arr[@]}"
来源：http://dali.xziqi.cn/Article/details/gt2dzjgmawe.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sqqcofkc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhoulong.xyz/Article/details/gt2wdqhzjrm.html

[R21] 字符串长度
来源：http://dali.ybcxt.top/Article/details/gt2yajtfwaw.html

echo "${#s}"
来源：http://dali.ehwqpu.com/Article/details/gt2vnyqwtye.html

[R22] 截取子串
来源：http://dali.yueranfly.top/Article/details/gt2hzncjqad.html

echo "${s:0:5}"
来源：http://dali.316326.xyz/Article/details/gt2cutxrwia.html

[R23] 字符串替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2sittfaoi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.mhx1999.top/Article/details/gt2hxfzpuig.html

[R24] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gt2psqsvgie.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yangfankeji.com/Article/details/gt2yefityyn.html

[R25] 去后缀 / 去前缀
来源：http://dali.yvedp.cn/Article/details/gt2ozyjcavs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhixingplan.top/Article/details/gt2dknphnou.html

[R26] 命令替换
来源：http://dali.gogol.net.cn/Article/details/gt2tefrqeyo.html

now=$(date +%F); echo "$now"
来源：http://dali.jianghu66.top/Article/details/gt2rqngswxe.html

[R27] 算术展开
来源：http://dali.zdqjudy.top/Article/details/gt2fespjjdb.html


<!-- 参考信息 -->