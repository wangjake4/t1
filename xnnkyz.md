代发 wailian999

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tianlin.xyz/Article/details/gtwbodftce.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shuidangran.top/Article/details/gtzperbfah.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gthkgdvtqh.html

Ruby: a == b
来源：http://dali.cashguo.top/Article/details/gtynxxrpez.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.dianchejie.cn/Article/details/gtpjujaoje.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.9152youxi.cn/Article/details/gticonuakr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nwbrower.top/Article/details/gtqmwrvtkg.html

PHP:  if (empty($x)) {}
来源：http://dali.tian-w.cn/Article/details/gtbvwirzjj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.quarkkingdee.top/Article/details/gtcbdwvgey.html

TS:   if (x == null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydmopvyw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvqyuxrn.html

Go:   if x == nil {}
来源：http://dali.yonumen.top/Article/details/gtglribsau.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.316326.xyz/Article/details/gtqpqbroqb.html

C#:   if (x is null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbtsheca.html

[P07] 防抖与节流
来源：http://dali.zycfv.cn/Article/details/gtthwwyahw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shzxlz.cn/Article/details/gtisuvxrnk.html

PHP:  // 手写时间戳比较
来源：http://dali.quarkkingdee.top/Article/details/gtmjglouoz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gtvondtmik.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xinyue.icu/Article/details/gtwaiydhsj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yonumen.top/Article/details/gtartwpezm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthjnsqxw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sufxvd.cn/Article/details/gtwavemwah.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gaohongyu789.top/Article/details/gtsdckjztx.html

[P08] 处理浮点精度问题
来源：http://dali.xylfe.cn/Article/details/gtwarcnjuk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tianlin.xyz/Article/details/gteaqmffzw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gthijupdqn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvsgkqpl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hysaishi.cn/Article/details/gtovqdcbrx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nwbrower.top/Article/details/gtvmbxcprh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cucudq.cn/Article/details/gtdwhhedss.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangshuangyany.cn/Article/details/gtgprxexla.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenlongwang.top/Article/details/gtigxtxmmo.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtmxpejceb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hongshengwenyu.top/Article/details/gtnhrlhwco.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtxnmvexoi.html

[Q01] 创建表
来源：http://dali.guannengcc.top/Article/details/gtrkftmnid.html

CREATE TABLE users (
来源：http://dali.hfpthk.cn/Article/details/gtxobhabmu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.quarkkingdee.top/Article/details/gtjiacocus.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzymqhuj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenjidiqi.icu/Article/details/gtvyjsucxd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cashguo.top/Article/details/gtdgbfzphz.html

);
来源：http://dali.ydzc1.top/Article/details/gtlmflebbc.html

[Q02] 创建带外键的表
来源：http://dali.jqgufenzy.top/Article/details/gtnoyybkgv.html

CREATE TABLE orders (
来源：http://dali.hywenlv.cn/Article/details/gthwhfmbsm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigufen.top/Article/details/gtudzjsuld.html

user_id INT NOT NULL,
来源：http://dali.chenjidiqi.icu/Article/details/gtmdhlyhbq.html

amount DECIMAL(10, 2),
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpimkqcp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuetiantiany.cn/Article/details/gtroqucfgn.html

);
来源：http://dali.jyoumei.cn/Article/details/gtmimmmthn.html

[Q03] 增加列
来源：http://dali.cheryme.top/Article/details/gtkqqdspuq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.kuanghao11.cn/Article/details/gtovnvjpee.html

[Q04] 修改列类型
来源：http://dali.hnxiangtu.top/Article/details/gtiayrvzjn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hfpthk.cn/Article/details/gtyelcswvx.html

[Q05] 重命名列
来源：http://dali.jiagoushi.top/Article/details/gtcsslsqxw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yvedp.cn/Article/details/gtmoyjdqsk.html

[Q06] 删除列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvkoqjulk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sysykeji.top/Article/details/gtxfwouhgk.html

[Q07] 删除表
来源：http://dali.yongpay.top/Article/details/gtrdfycjli.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hfpthk.cn/Article/details/gtrfwrfpbo.html

[Q08] 创建普通索引
来源：http://dali.tanke756.top/Article/details/gtkzjallcq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.vqdsnc.cn/Article/details/gtylxhtknj.html

[Q09] 创建唯一索引
来源：http://dali.meibo888.top/Article/details/gtznyhgajg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhoulong.xyz/Article/details/gtrclitugh.html

[Q10] 插入单行
来源：http://dali.yongpay.top/Article/details/gtlpxbyvtc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhixingplan.top/Article/details/gtfrlocbuw.html

[Q11] 一次插入多行
来源：http://dali.yuxming.cn/Article/details/gtnlhcvswh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tanke756.top/Article/details/gtldugbned.html

[Q12] 插入后取自增 ID
来源：http://dali.smart0.xyz/Article/details/gtzlvgspez.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yonumen.top/Article/details/gtxmxophqe.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jianghu66.top/Article/details/gtgdxyhrbn.html

[Q13] 忽略重复插入
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlsvlxmet.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yangfankeji.com/Article/details/gthtrrbafd.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenjidiqi.icu/Article/details/gtttojehkx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cashguo.top/Article/details/gtdcddckls.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhongyouzk.top/Article/details/gthaerueeo.html

[Q15] 查询全部
来源：http://dali.havefunace.top/Article/details/gtpcgudgdv.html

SELECT * FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtewwxzyeo.html

[Q16] 查询指定列
来源：http://dali.nanxinkj.top/Article/details/gtzuahlvni.html

SELECT id, name FROM users;
来源：http://dali.ydzc1.top/Article/details/gtewnekkog.html

[Q17] 条件查询
来源：http://dali.gaohongyu789.top/Article/details/gttcruzocz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymiurpzp.html

[Q18] 模糊匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtxcutfjxo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.9152youxi.cn/Article/details/gthnznzvvj.html

[Q19] 范围查询
来源：http://dali.ppjwa.cn/Article/details/gtybhptgth.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tianlin.xyz/Article/details/gtkepaqnbx.html

[Q20] IN 列表
来源：http://dali.redwolf501.top/Article/details/gtnsoqabxj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gteqqrgysm.html

[Q21] 空值判断
来源：http://dali.tianlin.xyz/Article/details/gtidphltlw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ppjwa.cn/Article/details/gtnacwyfdi.html

[Q22] 排序
来源：http://dali.hnqzz.top/Article/details/gtxvwxdrrv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhixingplan.top/Article/details/gtqmbsfgff.html

[Q23] 分页
来源：http://dali.daxiang520.top/Article/details/gtinlzbrbf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgashglyr.html

[Q24] 去重
来源：http://dali.0kj1m.cn/Article/details/gtporjcniu.html

SELECT DISTINCT city FROM users;
来源：http://dali.xziqi.cn/Article/details/gtqnxwbhlp.html

[Q25] 只取前 N 条
来源：http://dali.nanxuanxn.top/Article/details/gtuiqxuqii.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.dashuyun.cn/Article/details/gtzivebjir.html

[Q26] 计数
来源：http://dali.hfpthk.cn/Article/details/gtqqvcpzlt.html

SELECT COUNT(*) FROM users;
来源：http://dali.cashguo.top/Article/details/gtsvcgpxat.html

[Q27] 条件计数
来源：http://dali.zhoulong.xyz/Article/details/gtivjidbno.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yonumen.top/Article/details/gtjakssbvq.html

[Q28] 求和与平均
来源：http://dali.xuanzx.com/Article/details/gtmmzoylla.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjcexxifh.html

[Q29] 最大最小值
来源：http://dali.feifeiyinyue.top/Article/details/gtdrfdttav.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gttvnvbxhm.html

[Q30] 分组统计
来源：http://dali.ehwqpu.com/Article/details/gtrejiuulv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gtvartrxse.html

[Q31] 分组后过滤
来源：http://dali.nanxuanxn.top/Article/details/gtaavmfgcc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jiagoushi.top/Article/details/gtnwrdtasr.html

[Q32] 分组拼接字符串
来源：http://dali.bjfxy.top/Article/details/gtkheoyuac.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtvtdgkpxp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.9152youxi.cn/Article/details/gtoaxayhir.html

[Q33] 多列分组
来源：http://dali.gotoacloud.top/Article/details/gtbjmsyawv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xinyue.icu/Article/details/gtgtwtrpoh.html

[Q34] 每组取第一条
来源：http://dali.0kj1m.cn/Article/details/gthnkxuvki.html

SELECT * FROM (
来源：http://dali.pengpengdd.cyou/Article/details/gtfvdwhqsc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tian-w.cn/Article/details/gtddlufdgo.html

) t WHERE rn = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtltfwlile.html

[Q35] 内连接
来源：http://dali.cashguo.top/Article/details/gtydsqmops.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.pycfn.com/Article/details/gtgsuukaly.html

[Q36] 左连接
来源：http://dali.hammf.cn/Article/details/gtkhkwffdf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvcfvjwm.html

[Q37] 右连接
来源：http://dali.xinyue.icu/Article/details/gtfzlecamo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.guowangkeji.top/Article/details/gtuasznilv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nwbrower.top/Article/details/gtpqbrxdmp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.aibaodan.cn/Article/details/gtokscrcax.html

[Q39] 自连接（查上下级）
来源：http://dali.ybcxt.top/Article/details/gtsvdddwls.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhixingplan.top/Article/details/gtbtywfzkh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.dashuyun.cn/Article/details/gtyvhjpnyi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yonumen.top/Article/details/gtyuulmiab.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.daxiang520.top/Article/details/gtuvhgsmlq.html

[Q41] 多表连接
来源：http://dali.chenzaomai.com/Article/details/gtmivjttea.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yuxming.cn/Article/details/gtzdztapmr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gotoacloud.top/Article/details/gtvwxpleps.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yvedp.cn/Article/details/gtcqckvgoy.html

[Q42] 连接条件附加过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtlicihydf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jqgfzy.top/Article/details/gtxbedsabn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhoulong.xyz/Article/details/gtnzzljmpj.html

[Q43] 标量子查询
来源：http://dali.shuidangran.top/Article/details/gtfvlsxmue.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenjidiqi.icu/Article/details/gtjugcprer.html

[Q44] IN 子查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknbrahbr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yangfankeji.com/Article/details/gtnmxqmeri.html

[Q45] EXISTS 判断存在
来源：http://dali.kuanghao11.cn/Article/details/gtmnoteqqp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmafjjmla.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmamkbgni.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shangyingyoupin.top/Article/details/gtonteccxn.html

[Q47] 与平均值比较
来源：http://dali.cheryme.top/Article/details/gtjsfqksol.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xylfe.cn/Article/details/gtexltosgm.html

[Q48] CTE 公用表表达式
来源：http://dali.dianchejie.cn/Article/details/gtbttozwmj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xylfe.cn/Article/details/gtinhqqabj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aizwys.cn/Article/details/gtkwensdah.html

[Q49] 更新单行
来源：http://dali.zhengqikj.top/Article/details/gteeirmgqr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gtdxennxro.html

[Q50] 批量更新
来源：http://dali.birdmap.top/Article/details/gtqzosiyjn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ehwqpu.com/Article/details/gtehmiuvon.html

[Q51] 用子查询更新
来源：http://dali.cashguo.top/Article/details/gtonprsslx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gzhubu.top/Article/details/gtnljqzpcz.html

[Q52] 删除指定行
来源：http://dali.0kj1m.cn/Article/details/gthodcdpeg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gtddpnnpqa.html

[Q53] 按条件删除
来源：http://dali.zycfv.cn/Article/details/gtreghpxvd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shzxlz.cn/Article/details/gtgjkcltnj.html

[Q54] 清空表
来源：http://dali.yongpay.top/Article/details/gtuykyaoel.html

TRUNCATE TABLE logs;
来源：http://dali.tianlin.xyz/Article/details/gthmbswzcv.html

[Q55] 排名（并列占位）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbucczijx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gtlrpxmtjt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigfzy.top/Article/details/gtcwsogcim.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwivkwmuz.html

[Q57] 行号
来源：http://dali.haohaochexian.top/Article/details/gtwmvfdakh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtrmgtqxdh.html

[Q58] 累计求和
来源：http://dali.hfpthk.cn/Article/details/gtoinyouna.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtwexaraoc.html

[Q59] 分组内累计
来源：http://dali.zdqjudy.top/Article/details/gtnejbcvrw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.havefunace.top/Article/details/gtbiewcfph.html

[Q60] 取上一行 / 下一行
来源：http://dali.jianghu66.top/Article/details/gtqcrgssvh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daria6918.cn/Article/details/gtkgmennvf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtljpduobi.html

[Q61] 移动平均
来源：http://dali.ydzc1.top/Article/details/gtqjiwappc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtqwhoecsd.html

[Q62] 分组占比
来源：http://dali.sysykeji.top/Article/details/gtofbrufzr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgksyxeqq.html

[Q63] 开启事务
来源：http://dali.daria6918.cn/Article/details/gtbbhdsbtr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.vqdsnc.cn/Article/details/gtvthwzsic.html

[Q64] 提交事务
来源：http://dali.birdmap.top/Article/details/gtofmmignv.html

COMMIT;
来源：http://dali.cqqwz.cn/Article/details/gthjpuodas.html

[Q65] 回滚事务
来源：http://dali.ydzc1.top/Article/details/gtpswluocf.html

ROLLBACK;
来源：http://dali.cqqwz.cn/Article/details/gtebdxetlo.html

[Q66] 行锁查询
来源：http://dali.zycfv.cn/Article/details/gtqobfibyz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gtcrjavhrn.html

[Q67] 设置隔离级别
来源：http://dali.chenzaomai.com/Article/details/gtgwwzkusg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sysykeji.top/Article/details/gtuzaheffp.html

[Q68] 保存点
来源：http://dali.svipenyu.cn/Article/details/gtqtpnvcwf.html

SAVEPOINT sp1;
来源：http://dali.dianchejie.cn/Article/details/gtkeohxnaq.html

ROLLBACK TO sp1;
来源：http://dali.jyoumei.cn/Article/details/gtfwgsubdx.html

[Q69] 查看执行计划
来源：http://dali.ppjwa.cn/Article/details/gtroggtwai.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj20258.top/Article/details/gtofmfztcb.html

[Q70] 更新统计信息
来源：http://dali.shuidangran.top/Article/details/gtcnlvalyn.html

ANALYZE TABLE users;
来源：http://dali.zhongyouzk.top/Article/details/gtqijpelon.html

[Q71] 查看建表语句
来源：http://dali.fengsongda.top/Article/details/gtvdcntwsz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tianlin.xyz/Article/details/gtpboxudbi.html

[Q72] 查看索引
来源：http://dali.cheryme.top/Article/details/gthvmfjmye.html

SHOW INDEX FROM users;
来源：http://dali.yvedp.cn/Article/details/gtnkxoetdc.html

[Q73] 查看表状态
来源：http://dali.chenlongwang.top/Article/details/gtcvpnpwkt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ivvv.top/Article/details/gtmzesnwpf.html

[Q74] 强制使用索引
来源：http://dali.cashguo.top/Article/details/gtibppkwlj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangshuangyany.cn/Article/details/gtzsnyprzo.html

[Q75] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gtnnvrksfk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtqohthiwx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jqgufenzy.top/Article/details/gthnaspduv.html

[Q76] 按天统计
来源：http://dali.gzhubu.top/Article/details/gtifulyubr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.0kj1m.cn/Article/details/gtwgrmweja.html

[Q77] 时间加减
来源：http://dali.yonumen.top/Article/details/gtabdkvmff.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.quarkkingdee.top/Article/details/gtpparvxsx.html

[Q78] 当前时间
来源：http://dali.jianghu66.top/Article/details/gtyibvfhmh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhixingplan.top/Article/details/gttoitgttj.html

[Q79] 字符串拼接
来源：http://dali.shuidangran.top/Article/details/gtjazpjvkl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pengpengdd.cyou/Article/details/gtuhuvsbtf.html

[Q80] 字符串截取
来源：http://dali.fengsongda.top/Article/details/gtdzncwgqi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtafdrlfdu.html

[Q81] 字符串替换
来源：http://dali.yonumen.top/Article/details/gtkjmnpkhs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtvwkirrwr.html

[Q82] 字符长度与字节长度
来源：http://dali.xuanzx.com/Article/details/gtadisedth.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gttgudnchv.html

[Q83] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gtrtpgglwq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtwwrmhtzi.html

[Q84] 去除首尾空格
来源：http://dali.cucudq.cn/Article/details/gtlkygkcef.html

SELECT TRIM(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsagnnra.html

[Q85] 数值取整
来源：http://dali.pycfn.com/Article/details/gtyczqvtgh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpcncblqc.html

[Q86] 读取 JSON 字段
来源：http://dali.yangfankeji.com/Article/details/gtntdikayg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.pengpengdd.cyou/Article/details/gtovntcsnn.html

[Q87] JSON 字段做条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvezidylu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hnqzz.top/Article/details/gtxhqizbbv.html

[Q88] 行转列（条件聚合）
来源：http://dali.hysaishi.cn/Article/details/gttnwoyzxh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gotoacloud.top/Article/details/gtxsubghza.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtvqqotdth.html

[Q89] 判断表是否存在
来源：http://dali.zhengqikj.top/Article/details/gthfeneoxf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.0kj1m.cn/Article/details/gttdyhdgdb.html

[Q90] 生成序号列
来源：http://dali.xinyue.icu/Article/details/gtqhtzunws.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tian-w.cn/Article/details/gtsxmauzog.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtltnqggth.html

R. Bash 专题
来源：http://dali.shuidangran.top/Article/details/gtxcmsnxlv.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtsilpzdql.html

[R01] shebang 与严格模式
来源：http://dali.birdmap.top/Article/details/gtmdxyhncp.html

#!/usr/bin/env bash
来源：http://dali.yuanzhike.top/Article/details/gtjvmqwusa.html

set -euo pipefail
来源：http://dali.andypj.xyz/Article/details/gtweynorla.html

[R02] 变量赋值与使用
来源：http://dali.xziqi.cn/Article/details/gtartoicfw.html

name="Tom"; echo "$name"
来源：http://dali.ppjwa.cn/Article/details/gtarfmfbem.html

[R03] 只读变量
来源：http://dali.chenjidiqi.icu/Article/details/gtpdagkage.html

readonly PI=3.14
来源：http://dali.yj202588.top/Article/details/gtvytxrnig.html

[R04] 位置参数
来源：http://dali.zhixingplan.top/Article/details/gtjqbksget.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pycfn.com/Article/details/gthigvatom.html

[R05] 参数默认值
来源：http://dali.meibo888.top/Article/details/gthkbpgtkr.html

name="${1:-default}"
来源：http://dali.jqgufenzy.top/Article/details/gtzieciupa.html

[R06] 判断命令是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtcpixmokn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gthflqkpug.html

[R07] if 判断文件
来源：http://dali.c1oappe.top/Article/details/gtoeggbvje.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jiagoushi.top/Article/details/gthgjrmase.html

[R08] 数值比较
来源：http://dali.sysykeji.top/Article/details/gtocqgdwkn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cheryme.top/Article/details/gtkjybzqih.html

[R09] 字符串比较
来源：http://dali.xziqi.cn/Article/details/gtojbzrdyw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtpxpwbvcy.html

[R10] 正则匹配
来源：http://dali.fengsongda.top/Article/details/gtkkxhczzp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sysykeji.top/Article/details/gthryctmlh.html

[R11] case 多分支
来源：http://dali.cheryme.top/Article/details/gtndsobkmm.html

case "$1" in
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhltltqh.html

start) echo "启动" ;;
来源：http://dali.ehwqpu.com/Article/details/gtnjerrmmr.html

stop)  echo "停止" ;;
来源：http://dali.zhoulong.xyz/Article/details/gtxehgcmgt.html

*)     echo "未知命令" ;;
来源：http://dali.gotoacloud.top/Article/details/gtrxcbowia.html

esac
来源：http://dali.gzhubu.top/Article/details/gthlqrtqlp.html

[R12] for 遍历文件
来源：http://dali.yuxming.cn/Article/details/gtqssviwua.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yuanzhike.top/Article/details/gtadxnclpm.html

[R13] for 计数循环
来源：http://dali.hongshengwenyu.top/Article/details/gtfmgqhhri.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gtcxusqvvb.html

[R14] C 风格 for
来源：http://dali.meibo888.top/Article/details/gtryglyeyc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gtrvyhkkcb.html

[R15] while 逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtvptsoviw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.smart0.xyz/Article/details/gtzwsepuhx.html

[R16] until 等待条件
来源：http://dali.hywenlv.cn/Article/details/gtaozdmahz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gtcasvcjzc.html

[R17] 数组定义与取值
来源：http://dali.yuxming.cn/Article/details/gtzkcnherl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.meibo888.top/Article/details/gtamxjxvvs.html

[R18] 遍历数组
来源：http://dali.xuetiantiany.cn/Article/details/gtcmcvoxmj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj20258888.top/Article/details/gtgialncdb.html

[R19] 数组长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtquckbj.html

echo "${#arr[@]}"
来源：http://dali.jiagoushi.top/Article/details/gtbsvgpqgk.html

[R20] 关联数组（字典）
来源：http://dali.gzhubu.top/Article/details/gttrdumnia.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.smart0.xyz/Article/details/gtgjdqrfgb.html

[R21] 字符串长度
来源：http://dali.sxryk.cn/Article/details/gtbgodnnfc.html

echo "${#s}"
来源：http://dali.jinqigfzy.top/Article/details/gtehbesytc.html

[R22] 截取子串
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwxnyvis.html

echo "${s:0:5}"
来源：http://dali.iojbl.cn/Article/details/gtaklzpqni.html

[R23] 字符串替换
来源：http://dali.cashguo.top/Article/details/gtkxlbifni.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hfpthk.cn/Article/details/gtqtosspgy.html

[R24] 大小写转换
来源：http://dali.hammf.cn/Article/details/gtigiiuhik.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sufxvd.cn/Article/details/gtgjbmyvrf.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgfzy.top/Article/details/gtioqmataa.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jiagoushi.top/Article/details/gtcmtslwom.html

[R26] 命令替换
来源：http://dali.pycfn.com/Article/details/gtsfrftbcs.html

now=$(date +%F); echo "$now"
来源：http://dali.quarkkingdee.top/Article/details/gtuifaxzba.html

[R27] 算术展开
来源：http://dali.pengpengdd.cyou/Article/details/gttorehvcp.html


<!-- 参考信息 -->