代发 wailian999

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xylfe.cn/Article/details/gt2ozdpnovo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.wangshuangyany.cn/Article/details/gt2kwfadlwk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jianghu66.top/Article/details/gt2sivwysok.html

Ruby: a == b
来源：http://dali.yuanzhike.top/Article/details/gt2foanynkv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jqgfzy.top/Article/details/gt2zqnnfmit.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sufxvd.cn/Article/details/gt2hxpfanii.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.vqdsnc.cn/Article/details/gt2aypmvzeq.html

PHP:  if (empty($x)) {}
来源：http://dali.tanke756.top/Article/details/gt2wdgemxbu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ybcxt.top/Article/details/gt2uadpxsxd.html

TS:   if (x == null) {}
来源：http://dali.yuanzhike.top/Article/details/gt2cjartvgu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tian-w.cn/Article/details/gt2xavoldeb.html

Go:   if x == nil {}
来源：http://dali.jyoumei.cn/Article/details/gt2lucplznv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqkotsv.html

C#:   if (x is null) {}
来源：http://dali.zhixingplan.top/Article/details/gt2lergqayw.html

[P07] 防抖与节流
来源：http://dali.hysaishi.cn/Article/details/gt2vlxgmwts.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhiwuduotai.top/Article/details/gt2jlfdnthv.html

PHP:  // 手写时间戳比较
来源：http://dali.sxryk.cn/Article/details/gt2haztfztx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gt2rmswsjfj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gt2kpqxereu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.haohaochexian.top/Article/details/gt2qalyyuzk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.wangshuangyany.cn/Article/details/gt2oomxzmha.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gaohongyu789.top/Article/details/gt2ruflwfxe.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yueranfly.top/Article/details/gt2wzvzhmaq.html

[P08] 处理浮点精度问题
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wszurxea.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ybebqqgj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yongpay.top/Article/details/gt2rmjekhjg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shuidangran.top/Article/details/gt2lvroistg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yj20258888.top/Article/details/gt2elqsopzc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xuanzx.com/Article/details/gt2xhypysxu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenzaomai.com/Article/details/gt2fxjyxlst.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xuzkcflx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zycfv.cn/Article/details/gt2eocyoljs.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2gqpboyap.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cucudq.cn/Article/details/gt2kaqrdmwm.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2ioltuyms.html

[Q01] 创建表
来源：http://dali.jinqigfzy.top/Article/details/gt2eskyotiy.html

CREATE TABLE users (
来源：http://dali.gogol.net.cn/Article/details/gt2ujxeeqxl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuxming.cn/Article/details/gt2syysxnum.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qhjiwvyb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shzxlz.cn/Article/details/gt2xinmllft.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tian-w.cn/Article/details/gt2vsmwqbjk.html

);
来源：http://dali.fengsongda.top/Article/details/gt2ttvfulpv.html

[Q02] 创建带外键的表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ggjejwkq.html

CREATE TABLE orders (
来源：http://dali.zdqjudy.top/Article/details/gt2xrulmyrf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gt2kjidqxyw.html

user_id INT NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gt2pnaajvbd.html

amount DECIMAL(10, 2),
来源：http://dali.ppjwa.cn/Article/details/gt2mfywfacm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.andypj.xyz/Article/details/gt2vlcqlejq.html

);
来源：http://dali.hfpthk.cn/Article/details/gt2dkeypgsk.html

[Q03] 增加列
来源：http://dali.jinqigfzy.top/Article/details/gt2clrsiwrk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.fzhhl.top/Article/details/gt2ennrdogw.html

[Q04] 修改列类型
来源：http://dali.ivvv.top/Article/details/gt2uwfdbhjs.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ivvv.top/Article/details/gt2jjthoabj.html

[Q05] 重命名列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vgqirkly.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hammf.cn/Article/details/gt2tswjchbn.html

[Q06] 删除列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eelxipsa.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.iojbl.cn/Article/details/gt2vrfaxnvu.html

[Q07] 删除表
来源：http://dali.nwbrower.top/Article/details/gt2grhfzsxk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj20258888.top/Article/details/gt2iaakbsql.html

[Q08] 创建普通索引
来源：http://dali.xuanzx.com/Article/details/gt2wxgjdvqj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gt2voudnjnm.html

[Q09] 创建唯一索引
来源：http://dali.hnxiangtu.top/Article/details/gt2dqazcjer.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinqigfzy.top/Article/details/gt2porfmvbg.html

[Q10] 插入单行
来源：http://dali.xuanzx.com/Article/details/gt2uwzhcyqs.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.9152youxi.cn/Article/details/gt2duposxeb.html

[Q11] 一次插入多行
来源：http://dali.jqgufenzy.top/Article/details/gt2otitvxja.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jianghu66.top/Article/details/gt2rkfcrzvc.html

[Q12] 插入后取自增 ID
来源：http://dali.ydzc1.top/Article/details/gt2zxzbtnll.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cucudq.cn/Article/details/gt2gmzdxedj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hnqzz.top/Article/details/gt2rxcqreyp.html

[Q13] 忽略重复插入
来源：http://dali.jyoumei.cn/Article/details/gt2gvvappff.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hfpthk.cn/Article/details/gt2jshkkhou.html

[Q14] 存在则更新（upsert）
来源：http://dali.vqdsnc.cn/Article/details/gt2rzztujda.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sweek.top/Article/details/gt2rudwpjjt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xinyue.icu/Article/details/gt2ynfdcwqw.html

[Q15] 查询全部
来源：http://dali.yongpay.top/Article/details/gt2wwrwoejy.html

SELECT * FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2awfwxsbs.html

[Q16] 查询指定列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qwrdnwvu.html

SELECT id, name FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2ahjmleio.html

[Q17] 条件查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2nmyirgio.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2cpvddmqi.html

[Q18] 模糊匹配
来源：http://dali.cashguo.top/Article/details/gt2gghrmqfx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhiwuduotai.top/Article/details/gt2udmcilvs.html

[Q19] 范围查询
来源：http://dali.smart0.xyz/Article/details/gt2qykohipt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yangfankeji.com/Article/details/gt2wplumzst.html

[Q20] IN 列表
来源：http://dali.hnqzz.top/Article/details/gt2nsqgjhcl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.dashuyun.cn/Article/details/gt2zhbqbhka.html

[Q21] 空值判断
来源：http://dali.zhixingplan.top/Article/details/gt2dyyidxbg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sxryk.cn/Article/details/gt2kelqomiq.html

[Q22] 排序
来源：http://dali.smart0.xyz/Article/details/gt2jjzmxuvo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.dianchejie.cn/Article/details/gt2jpteisce.html

[Q23] 分页
来源：http://dali.yanxiufei.cn/Article/details/gt2pusxbyqx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hfpthk.cn/Article/details/gt2tsyfnowj.html

[Q24] 去重
来源：http://dali.jiagoushi.top/Article/details/gt2pqqdmzko.html

SELECT DISTINCT city FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2eeqchign.html

[Q25] 只取前 N 条
来源：http://dali.fzhhl.top/Article/details/gt2cinfnbva.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gogol.net.cn/Article/details/gt2ehcreiyh.html

[Q26] 计数
来源：http://dali.shangyingyoupin.top/Article/details/gt2madiocab.html

SELECT COUNT(*) FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2ridopaaw.html

[Q27] 条件计数
来源：http://dali.cucudq.cn/Article/details/gt2vgbhwhgo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2ktxbeett.html

[Q28] 求和与平均
来源：http://dali.zhixingplan.top/Article/details/gt2ektjugmp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2lcqckwsz.html

[Q29] 最大最小值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2epxdhmvh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.birdmap.top/Article/details/gt2bbeepelj.html

[Q30] 分组统计
来源：http://dali.c1oappe.top/Article/details/gt2yvnfkvxr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gt2lakrzllk.html

[Q31] 分组后过滤
来源：http://dali.xuetiantiany.cn/Article/details/gt2jbgczrwx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yuxming.cn/Article/details/gt2dlqrrqye.html

[Q32] 分组拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2egqhhsdc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gt2hfwyrlsw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.redwolf501.top/Article/details/gt2tlagsntp.html

[Q33] 多列分组
来源：http://dali.daria6918.cn/Article/details/gt2fixnwvex.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yonumen.top/Article/details/gt2fgvbjyww.html

[Q34] 每组取第一条
来源：http://dali.fzhhl.top/Article/details/gt2nknlnkkg.html

SELECT * FROM (
来源：http://dali.yj202588.top/Article/details/gt2utphhdnd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jlsjyb.cn/Article/details/gt2dwqlmgkp.html

) t WHERE rn = 1;
来源：http://dali.xziqi.cn/Article/details/gt2wnzpfdhu.html

[Q35] 内连接
来源：http://dali.redwolf501.top/Article/details/gt2atksmlgf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cqqwz.cn/Article/details/gt2fcutdhax.html

[Q36] 左连接
来源：http://dali.hywenlv.cn/Article/details/gt2fyzrowgd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gt2qzfvywkm.html

[Q37] 右连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xvpryczr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cucudq.cn/Article/details/gt2qdapbciv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhengqikj.top/Article/details/gt2zjamhnib.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yonumen.top/Article/details/gt2bxqqsosz.html

[Q39] 自连接（查上下级）
来源：http://dali.cheryme.top/Article/details/gt2qltcvnyj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.9152youxi.cn/Article/details/gt2fhiyddqx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.guannengcc.top/Article/details/gt2ueuwzdon.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2enpilovk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jyoumei.cn/Article/details/gt2pqjzwylo.html

[Q41] 多表连接
来源：http://dali.sysykeji.top/Article/details/gt2miqzzweo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.svipenyu.cn/Article/details/gt2ujkrcddo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.meibo888.top/Article/details/gt2icitslol.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cheryme.top/Article/details/gt2tczvsvty.html

[Q42] 连接条件附加过滤
来源：http://dali.yanxiufei.cn/Article/details/gt2adpjyngt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.quarkkingdee.top/Article/details/gt2lvmjjrqq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.havefunace.top/Article/details/gt2ulhzfwjk.html

[Q43] 标量子查询
来源：http://dali.daria6918.cn/Article/details/gt2xoetytja.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cucudq.cn/Article/details/gt2jrfbhjvh.html

[Q44] IN 子查询
来源：http://dali.gzhubu.top/Article/details/gt2wrhlgqmy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yuxming.cn/Article/details/gt2jvucrdzr.html

[Q45] EXISTS 判断存在
来源：http://dali.guannengcc.top/Article/details/gt2jvacprtm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gt2gynjhwat.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wqzlatst.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gt2xnrjmwqk.html

[Q47] 与平均值比较
来源：http://dali.hysaishi.cn/Article/details/gt2rhlzaqni.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hysaishi.cn/Article/details/gt2cheqfglq.html

[Q48] CTE 公用表表达式
来源：http://dali.zhengqikj.top/Article/details/gt2lvnpzfju.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ivvv.top/Article/details/gt2pvhgekbo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yongpay.top/Article/details/gt2hodzkjzx.html

[Q49] 更新单行
来源：http://dali.dianchejie.cn/Article/details/gt2fonxbdmr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.andypj.xyz/Article/details/gt2jpipsxgj.html

[Q50] 批量更新
来源：http://dali.wangshuangyany.cn/Article/details/gt2wshxdvdk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ybcxt.top/Article/details/gt2aigmuhfx.html

[Q51] 用子查询更新
来源：http://dali.tian-w.cn/Article/details/gt2tzbxidmh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nanxinkj.top/Article/details/gt2kvomaxnl.html

[Q52] 删除指定行
来源：http://dali.gotoacloud.top/Article/details/gt2hufvcurq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gzhubu.top/Article/details/gt2tgdqlpsc.html

[Q53] 按条件删除
来源：http://dali.cucudq.cn/Article/details/gt2ssfyrmgx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.guannengcc.top/Article/details/gt2zrpabtqi.html

[Q54] 清空表
来源：http://dali.haohaochexian.top/Article/details/gt2ybktovso.html

TRUNCATE TABLE logs;
来源：http://dali.zhiwuduotai.top/Article/details/gt2yveocsmz.html

[Q55] 排名（并列占位）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jjqgjbuf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yangfankeji.com/Article/details/gt2fcxnlukh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guowangkeji.top/Article/details/gt2drqyqpqb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sufxvd.cn/Article/details/gt2pyigcjqk.html

[Q57] 行号
来源：http://dali.jiagoushi.top/Article/details/gt2wzjkhbbn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2nqxtwmff.html

[Q58] 累计求和
来源：http://dali.sxryk.cn/Article/details/gt2stjukbkf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gt2pvoghkmp.html

[Q59] 分组内累计
来源：http://dali.jqgufenzy.top/Article/details/gt2eiunbxzq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gt2zjhugjyi.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenjidiqi.icu/Article/details/gt2tlzlizno.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yuxming.cn/Article/details/gt2vpddpldh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2wzwmlmxz.html

[Q61] 移动平均
来源：http://dali.iojbl.cn/Article/details/gt2mbfsxvcm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2adnalbep.html

[Q62] 分组占比
来源：http://dali.yj202588.top/Article/details/gt2fzqsidsg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gt2nrfkkxze.html

[Q63] 开启事务
来源：http://dali.gotoacloud.top/Article/details/gt2mtwfbiji.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shangyingyoupin.top/Article/details/gt2jljwonyg.html

[Q64] 提交事务
来源：http://dali.hnxiangtu.top/Article/details/gt2brhruseg.html

COMMIT;
来源：http://dali.cucudq.cn/Article/details/gt2youqjxet.html

[Q65] 回滚事务
来源：http://dali.yj20258888.top/Article/details/gt2spqiycyb.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqwgmgb.html

[Q66] 行锁查询
来源：http://dali.jianghu66.top/Article/details/gt2buwynvnu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cashguo.top/Article/details/gt2bvuggyao.html

[Q67] 设置隔离级别
来源：http://dali.yj20258.top/Article/details/gt2bklwklqm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.mhx1999.top/Article/details/gt2ckwtxmnp.html

[Q68] 保存点
来源：http://dali.andypj.xyz/Article/details/gt2jiiqlvib.html

SAVEPOINT sp1;
来源：http://dali.jqgfzy.top/Article/details/gt2ulsxcbhs.html

ROLLBACK TO sp1;
来源：http://dali.9152youxi.cn/Article/details/gt2dvvlkjfe.html

[Q69] 查看执行计划
来源：http://dali.pengpengdd.cyou/Article/details/gt2fhfsfemk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.quarkkingdee.top/Article/details/gt2ljalride.html

[Q70] 更新统计信息
来源：http://dali.ivvv.top/Article/details/gt2koovvbuh.html

ANALYZE TABLE users;
来源：http://dali.daria6918.cn/Article/details/gt2kmtusvua.html

[Q71] 查看建表语句
来源：http://dali.nanxinkj.top/Article/details/gt2kcqdirje.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shuidangran.top/Article/details/gt2bzjwmzne.html

[Q72] 查看索引
来源：http://dali.gzhubu.top/Article/details/gt2kxhxvaal.html

SHOW INDEX FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2htaaamrf.html

[Q73] 查看表状态
来源：http://dali.fzhhl.top/Article/details/gt2wrbturpj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ydzc1.top/Article/details/gt2mrqnmxrx.html

[Q74] 强制使用索引
来源：http://dali.cqqwz.cn/Article/details/gt2jthrpugh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.smart0.xyz/Article/details/gt2lfhuppmw.html

[Q75] 日期格式化
来源：http://dali.chenzaomai.com/Article/details/gt2owkknter.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sxryk.cn/Article/details/gt2vxczzcgh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yonumen.top/Article/details/gt2samoppfe.html

[Q76] 按天统计
来源：http://dali.xylfe.cn/Article/details/gt2xsfdvods.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.havefunace.top/Article/details/gt2tlnolbqg.html

[Q77] 时间加减
来源：http://dali.snrcjt.cn/Article/details/gt2gayboscc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuanzhike.top/Article/details/gt2dogqvffb.html

[Q78] 当前时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gcpocvip.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xinyue.icu/Article/details/gt2uuulthsg.html

[Q79] 字符串拼接
来源：http://dali.jinqigufen.top/Article/details/gt2dswcjxul.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yvedp.cn/Article/details/gt2bhprvhgr.html

[Q80] 字符串截取
来源：http://dali.sweek.top/Article/details/gt2ygkdtfvl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbpepiyg.html

[Q81] 字符串替换
来源：http://dali.bjfxy.top/Article/details/gt2otnplywh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2beoufhwf.html

[Q82] 字符长度与字节长度
来源：http://dali.cheryme.top/Article/details/gt2guzxetdt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2ltquwpib.html

[Q83] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gt2szoxmwfl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2eanqpxqg.html

[Q84] 去除首尾空格
来源：http://dali.wangdashe.top/Article/details/gt2mzlmsohi.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fbiyrdxk.html

[Q85] 数值取整
来源：http://dali.birdmap.top/Article/details/gt2igqvstjy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ehwqpu.com/Article/details/gt2ayfykvjk.html

[Q86] 读取 JSON 字段
来源：http://dali.redwolf501.top/Article/details/gt2yjafpptd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.0kj1m.cn/Article/details/gt2wujuqfep.html

[Q87] JSON 字段做条件
来源：http://dali.dianchejie.cn/Article/details/gt2lbjwvmyn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yonumen.top/Article/details/gt2juwaosei.html

[Q88] 行转列（条件聚合）
来源：http://dali.snrcjt.cn/Article/details/gt2gdmysrsz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuanzx.com/Article/details/gt2obfbkpie.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2rapcwjsg.html

[Q89] 判断表是否存在
来源：http://dali.cdnleiting.top/Article/details/gt2cuipjbot.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gt2zztuzqwg.html

[Q90] 生成序号列
来源：http://dali.chenzaomai.com/Article/details/gt2tdgxfecx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.feifeiyinyue.top/Article/details/gt2yuidffrx.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2blxprtnv.html

R. Bash 专题
来源：http://dali.gogol.net.cn/Article/details/gt2lvasnrba.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2xdpyqedd.html

[R01] shebang 与严格模式
来源：http://dali.yuxming.cn/Article/details/gt2xlwngjum.html

#!/usr/bin/env bash
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rtaemfyv.html

set -euo pipefail
来源：http://dali.tanke756.top/Article/details/gt2jknhlsfs.html

[R02] 变量赋值与使用
来源：http://dali.chenzaomai.com/Article/details/gt2qnoawyrt.html

name="Tom"; echo "$name"
来源：http://dali.daxiang520.top/Article/details/gt2ytfqxytj.html

[R03] 只读变量
来源：http://dali.zdqjudy.top/Article/details/gt2rbcxflly.html

readonly PI=3.14
来源：http://dali.daria6918.cn/Article/details/gt2iytwrkzu.html

[R04] 位置参数
来源：http://dali.birdmap.top/Article/details/gt2trakzral.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenlongwang.top/Article/details/gt2jnfwotmy.html

[R05] 参数默认值
来源：http://dali.aibaodan.cn/Article/details/gt2dzyxwboj.html

name="${1:-default}"
来源：http://dali.hnxiangtu.top/Article/details/gt2bcgwurix.html

[R06] 判断命令是否存在
来源：http://dali.cqqwz.cn/Article/details/gt2mivlsyip.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ddducogd.html

[R07] if 判断文件
来源：http://dali.gotoacloud.top/Article/details/gt2ntndqgyc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2venrsdax.html

[R08] 数值比较
来源：http://dali.zhoulong.xyz/Article/details/gt2uhtvkolb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zdqjudy.top/Article/details/gt2sbiofotc.html

[R09] 字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2wozbudav.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yvedp.cn/Article/details/gt2ofkqrdac.html

[R10] 正则匹配
来源：http://dali.bjfxy.top/Article/details/gt2pwutxtsx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxuanxn.top/Article/details/gt2axtshkta.html

[R11] case 多分支
来源：http://dali.ybcxt.top/Article/details/gt2kgbrwebu.html

case "$1" in
来源：http://dali.nanxuanxn.top/Article/details/gt2norwpjnq.html

start) echo "启动" ;;
来源：http://dali.bjfxy.top/Article/details/gt2rirxbefu.html

stop)  echo "停止" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gt2lqpxssaf.html

*)     echo "未知命令" ;;
来源：http://dali.jqgufenzy.top/Article/details/gt2abnktkvp.html

esac
来源：http://dali.xziqi.cn/Article/details/gt2ibnkojbp.html

[R12] for 遍历文件
来源：http://dali.sysykeji.top/Article/details/gt2goipphfk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nwbrower.top/Article/details/gt2tdhalrkq.html

[R13] for 计数循环
来源：http://dali.yuxming.cn/Article/details/gt2thzxbikr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gt2qkemyawk.html

[R14] C 风格 for
来源：http://dali.hammf.cn/Article/details/gt2ltrdxxwe.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gt2fbbcxcpl.html

[R15] while 逐行读文件
来源：http://dali.sysykeji.top/Article/details/gt2wbzkyyxs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yvedp.cn/Article/details/gt2rjvttjqs.html

[R16] until 等待条件
来源：http://dali.sweek.top/Article/details/gt2hvwzxfwd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.bjfxy.top/Article/details/gt2xrzvslmf.html

[R17] 数组定义与取值
来源：http://dali.fengsongda.top/Article/details/gt2qfndlkcc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aibaodan.cn/Article/details/gt2bqcekztr.html

[R18] 遍历数组
来源：http://dali.ppjwa.cn/Article/details/gt2prqvetcg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hywenlv.cn/Article/details/gt2xmvftqdr.html

[R19] 数组长度
来源：http://dali.hammf.cn/Article/details/gt2bdhzwrzf.html

echo "${#arr[@]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2metinuvj.html

[R20] 关联数组（字典）
来源：http://dali.fengsongda.top/Article/details/gt2pyknkiru.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gogol.net.cn/Article/details/gt2uqhkumko.html

[R21] 字符串长度
来源：http://dali.andypj.xyz/Article/details/gt2mkwruvvl.html

echo "${#s}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nnrzlwoh.html

[R22] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gt2ukddpxrc.html

echo "${s:0:5}"
来源：http://dali.yueranfly.top/Article/details/gt2maewxdcd.html

[R23] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gt2zgjcbiiq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yvedp.cn/Article/details/gt2ajaxgrnu.html

[R24] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gt2adraiqnl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigufen.top/Article/details/gt2tbktmjcb.html

[R25] 去后缀 / 去前缀
来源：http://dali.yonumen.top/Article/details/gt2hrfloels.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.havefunace.top/Article/details/gt2eayomyzw.html

[R26] 命令替换
来源：http://dali.bjfxy.top/Article/details/gt2ithnacvv.html

now=$(date +%F); echo "$now"
来源：http://dali.tanke756.top/Article/details/gt2lbckyscd.html

[R27] 算术展开
来源：http://dali.yj20258888.top/Article/details/gt2pytqlpug.html


<!-- 参考信息 -->