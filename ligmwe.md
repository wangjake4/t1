代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zycfv.cn/Article/details/gt2onjksvsa.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangshuangyany.cn/Article/details/gt2svmcgmsl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.316326.xyz/Article/details/gt2clmdymbl.html

PHP:  if (empty($x)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2riedjzwz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shuidangran.top/Article/details/gt2ykeyeiid.html

TS:   if (x == null) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2stystxfz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yangfankeji.com/Article/details/gt2jivbqbeg.html

Go:   if x == nil {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yimqrjyr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zjssdzrk.html

C#:   if (x is null) {}
来源：http://dali.zhixingplan.top/Article/details/gt2mcaayxqa.html

[P07] 防抖与节流
来源：http://dali.hysaishi.cn/Article/details/gt2libkyfpj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mufpdwfi.html

PHP:  // 手写时间戳比较
来源：http://dali.haohaochexian.top/Article/details/gt2bttlugjf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gt2oxtlrubu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gt2bwrxloac.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gzhubu.top/Article/details/gt2tuyozvhb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yonumen.top/Article/details/gt2ljwhvxmc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ivvv.top/Article/details/gt2kugammse.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gotoacloud.top/Article/details/gt2sdwajpxb.html

[P08] 处理浮点精度问题
来源：http://dali.shzxlz.cn/Article/details/gt2ajblskip.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.redwolf501.top/Article/details/gt2rvkofugc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qqdsmxuq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ehwqpu.com/Article/details/gt2fxtdyglo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhengqikj.top/Article/details/gt2bkwuqoex.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.smart0.xyz/Article/details/gt2cdwebvyv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.wangdashe.top/Article/details/gt2gszbjcae.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cheryme.top/Article/details/gt2wlphndhq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guannengcc.top/Article/details/gt2useswfwp.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2apmmnolk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.andypj.xyz/Article/details/gt2cmvocgpj.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2vzrmddvc.html

[Q01] 创建表
来源：http://dali.chenzaomai.com/Article/details/gt2egviqzad.html

CREATE TABLE users (
来源：http://dali.yuxming.cn/Article/details/gt2trtdyrko.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dashuyun.cn/Article/details/gt2lumjydet.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gt2djvodkns.html

email VARCHAR(100) UNIQUE,
来源：http://dali.vqdsnc.cn/Article/details/gt2pwbyddpa.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hammf.cn/Article/details/gt2llnmcqiv.html

);
来源：http://dali.sweek.top/Article/details/gt2bgodhtvu.html

[Q02] 创建带外键的表
来源：http://dali.shangyingyoupin.top/Article/details/gt2eqxmrgke.html

CREATE TABLE orders (
来源：http://dali.hnxiangtu.top/Article/details/gt2ecjjmazo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenjidiqi.icu/Article/details/gt2nnzvuthi.html

user_id INT NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gt2mbfeiixq.html

amount DECIMAL(10, 2),
来源：http://dali.hywenlv.cn/Article/details/gt2ohronnza.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hfpthk.cn/Article/details/gt2sfgifkkt.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gt2rowbhbse.html

[Q03] 增加列
来源：http://dali.hongshengwenyu.top/Article/details/gt2alfswvxy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.mhx1999.top/Article/details/gt2nnfjwmvy.html

[Q04] 修改列类型
来源：http://dali.havefunace.top/Article/details/gt2vixgmgjz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgfzy.top/Article/details/gt2gjglgcjr.html

[Q05] 重命名列
来源：http://dali.9152youxi.cn/Article/details/gt2qcwjbpov.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.guowangkeji.top/Article/details/gt2wmfenmcw.html

[Q06] 删除列
来源：http://dali.zhoulong.xyz/Article/details/gt2hktlibga.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhengqikj.top/Article/details/gt2ueystlnx.html

[Q07] 删除表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2djqixpwi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cashguo.top/Article/details/gt2doahqurr.html

[Q08] 创建普通索引
来源：http://dali.mhx1999.top/Article/details/gt2zvntizkj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ivvv.top/Article/details/gt2wzbjvygv.html

[Q09] 创建唯一索引
来源：http://dali.nwbrower.top/Article/details/gt2uctfrbxi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuanzx.com/Article/details/gt2punmahwb.html

[Q10] 插入单行
来源：http://dali.feifeiyinyue.top/Article/details/gt2vcnmeguc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jianghu66.top/Article/details/gt2hdodozbu.html

[Q11] 一次插入多行
来源：http://dali.xuanzx.com/Article/details/gt2kfuhxrbe.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zycfv.cn/Article/details/gt2fzcywtyd.html

[Q12] 插入后取自增 ID
来源：http://dali.snrcjt.cn/Article/details/gt2wrzoymxv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hysaishi.cn/Article/details/gt2vxaodfso.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj20258.top/Article/details/gt2nnlhyejz.html

[Q13] 忽略重复插入
来源：http://dali.chenzaomai.com/Article/details/gt2hzswbovr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gt2acfprwxa.html

[Q14] 存在则更新（upsert）
来源：http://dali.pycfn.com/Article/details/gt2ivoguoqy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yangfankeji.com/Article/details/gt2hazclydk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.316326.xyz/Article/details/gt2zthopjvh.html

[Q15] 查询全部
来源：http://dali.dashuyun.cn/Article/details/gt2slafidna.html

SELECT * FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2dfhcenox.html

[Q16] 查询指定列
来源：http://dali.hnqzz.top/Article/details/gt2nqciofuu.html

SELECT id, name FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2vljbdqde.html

[Q17] 条件查询
来源：http://dali.jinqigfzy.top/Article/details/gt2umezywin.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yonumen.top/Article/details/gt2zfdhqhfm.html

[Q18] 模糊匹配
来源：http://dali.ehwqpu.com/Article/details/gt2cdnrofsl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jiagoushi.top/Article/details/gt2dlcdcifp.html

[Q19] 范围查询
来源：http://dali.wangdashe.top/Article/details/gt2uggipdme.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.aizwys.cn/Article/details/gt2oedjoybo.html

[Q20] IN 列表
来源：http://dali.gogol.net.cn/Article/details/gt2lrdzxwzt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.wangdashe.top/Article/details/gt2ntzqdipu.html

[Q21] 空值判断
来源：http://dali.yongpay.top/Article/details/gt2gsuxelzz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj20258888.top/Article/details/gt2vtjonztj.html

[Q22] 排序
来源：http://dali.wangshuangyany.cn/Article/details/gt2zlvgjhtz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.quarkkingdee.top/Article/details/gt2bexzlolg.html

[Q23] 分页
来源：http://dali.feifeiyinyue.top/Article/details/gt2axtqkksw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenzaomai.com/Article/details/gt2sbwxtiul.html

[Q24] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tfbhurfe.html

SELECT DISTINCT city FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2bfbudefm.html

[Q25] 只取前 N 条
来源：http://dali.nanxuanxn.top/Article/details/gt2qokvcjjj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nwbrower.top/Article/details/gt2nuscshbl.html

[Q26] 计数
来源：http://dali.andypj.xyz/Article/details/gt2upuoxbwj.html

SELECT COUNT(*) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2xmlgdmiz.html

[Q27] 条件计数
来源：http://dali.smart0.xyz/Article/details/gt2jjqdgami.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2yspspnlx.html

[Q28] 求和与平均
来源：http://dali.sxryk.cn/Article/details/gt2jtxabkfg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ldkdoojd.html

[Q29] 最大最小值
来源：http://dali.yuanzhike.top/Article/details/gt2lqevmipt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2tingjtuv.html

[Q30] 分组统计
来源：http://dali.yonumen.top/Article/details/gt2ubhfftsd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gt2kdprdpfo.html

[Q31] 分组后过滤
来源：http://dali.quarkkingdee.top/Article/details/gt2ximosdqk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xylfe.cn/Article/details/gt2kdxtnbot.html

[Q32] 分组拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gt2ctqtnyce.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hhmwfpzf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hfpthk.cn/Article/details/gt2kpponutg.html

[Q33] 多列分组
来源：http://dali.hongshengwenyu.top/Article/details/gt2iuxrihhz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gtownaia.html

[Q34] 每组取第一条
来源：http://dali.pengpengdd.cyou/Article/details/gt2ohxkofnr.html

SELECT * FROM (
来源：http://dali.cheryme.top/Article/details/gt2vxudlsio.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.mhx1999.top/Article/details/gt2bwmobcym.html

) t WHERE rn = 1;
来源：http://dali.zhoulong.xyz/Article/details/gt2qkizobcu.html

[Q35] 内连接
来源：http://dali.wangdashe.top/Article/details/gt2ukweqlna.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.birdmap.top/Article/details/gt2dbtxxoag.html

[Q36] 左连接
来源：http://dali.yj20258.top/Article/details/gt2ohjmqmfj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gt2fbyuquzu.html

[Q37] 右连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2muzrqyag.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daxiang520.top/Article/details/gt2ycvlqvhw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cqqwz.cn/Article/details/gt2fxiajpve.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yueranfly.top/Article/details/gt2arxszvcz.html

[Q39] 自连接（查上下级）
来源：http://dali.quarkkingdee.top/Article/details/gt2bqomgeie.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenzaomai.com/Article/details/gt2mehzonch.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jqgfzy.top/Article/details/gt2hmqjmhrv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhongyouzk.top/Article/details/gt2jnxuzwob.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.svipenyu.cn/Article/details/gt2tufrhcnf.html

[Q41] 多表连接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hhydcxpv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yanxiufei.cn/Article/details/gt2hgnyigag.html

JOIN users u ON u.id = o.user_id
来源：http://dali.bjfxy.top/Article/details/gt2copewjdc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hongshengwenyu.top/Article/details/gt2eplxedfo.html

[Q42] 连接条件附加过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mizathzj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yuxming.cn/Article/details/gt2lryhqisx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cheryme.top/Article/details/gt2wrrhozrp.html

[Q43] 标量子查询
来源：http://dali.daxiang520.top/Article/details/gt2gkjfocgn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nanxuanxn.top/Article/details/gt2pervdqhx.html

[Q44] IN 子查询
来源：http://dali.aizwys.cn/Article/details/gt2wcwwhfyq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nanxuanxn.top/Article/details/gt2kbvjjbef.html

[Q45] EXISTS 判断存在
来源：http://dali.0kj1m.cn/Article/details/gt2egbsxsdb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2raoszkdr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgfzy.top/Article/details/gt2oftlpbqe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhixingplan.top/Article/details/gt2kpudtkuc.html

[Q47] 与平均值比较
来源：http://dali.shzxlz.cn/Article/details/gt2ructwkee.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guannengcc.top/Article/details/gt2exusniyk.html

[Q48] CTE 公用表表达式
来源：http://dali.cheryme.top/Article/details/gt2mreqvhsj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zycfv.cn/Article/details/gt2llarqyvc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.feifeiyinyue.top/Article/details/gt2zmxyhkxq.html

[Q49] 更新单行
来源：http://dali.haohaochexian.top/Article/details/gt2eqfopnwc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gt2gmbjhdba.html

[Q50] 批量更新
来源：http://dali.wangshuangyany.cn/Article/details/gt2dxsyrtle.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yuxming.cn/Article/details/gt2swtdulvu.html

[Q51] 用子查询更新
来源：http://dali.ehwqpu.com/Article/details/gt2grhnmetk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xinyue.icu/Article/details/gt2lbfmgigj.html

[Q52] 删除指定行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rnkcnddc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aizwys.cn/Article/details/gt2tzutslgk.html

[Q53] 按条件删除
来源：http://dali.sufxvd.cn/Article/details/gt2pwxfcwzv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.c1oappe.top/Article/details/gt2asoiixwu.html

[Q54] 清空表
来源：http://dali.wangshuangyany.cn/Article/details/gt2kxsclfqf.html

TRUNCATE TABLE logs;
来源：http://dali.ydzc1.top/Article/details/gt2lxwkwnti.html

[Q55] 排名（并列占位）
来源：http://dali.xuanzx.com/Article/details/gt2wpwananv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgufenzy.top/Article/details/gt2agtitovk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ydzc1.top/Article/details/gt2rwbvkyfx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gt2xhokjvvo.html

[Q57] 行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2chazkdkj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2supdzgcl.html

[Q58] 累计求和
来源：http://dali.svipenyu.cn/Article/details/gt2uibhyrms.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhcdvcn.html

[Q59] 分组内累计
来源：http://dali.yj20258888.top/Article/details/gt2ioosoxfw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gt2etpebhdq.html

[Q60] 取上一行 / 下一行
来源：http://dali.nanxinkj.top/Article/details/gt2jttlwkeo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xziqi.cn/Article/details/gt2gznnkahn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hnqzz.top/Article/details/gt2cdwoayij.html

[Q61] 移动平均
来源：http://dali.wangdashe.top/Article/details/gt2ujdmqdpz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gt2yoqckxyj.html

[Q62] 分组占比
来源：http://dali.tian-w.cn/Article/details/gt2icsirold.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.316326.xyz/Article/details/gt2qbpcljqq.html

[Q63] 开启事务
来源：http://dali.cucudq.cn/Article/details/gt2eopnfdtb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ivvv.top/Article/details/gt2nezkjtkc.html

[Q64] 提交事务
来源：http://dali.svipenyu.cn/Article/details/gt2nircalks.html

COMMIT;
来源：http://dali.nwbrower.top/Article/details/gt2miuexgma.html

[Q65] 回滚事务
来源：http://dali.ehwqpu.com/Article/details/gt2kzfjanuu.html

ROLLBACK;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iulacgxf.html

[Q66] 行锁查询
来源：http://dali.zhongyouzk.top/Article/details/gt2syapqflj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nanxuanxn.top/Article/details/gt2mqhqzjpg.html

[Q67] 设置隔离级别
来源：http://dali.sufxvd.cn/Article/details/gt2gfazenqi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.haohaochexian.top/Article/details/gt2vfluexbk.html

[Q68] 保存点
来源：http://dali.hywenlv.cn/Article/details/gt2aymmbsct.html

SAVEPOINT sp1;
来源：http://dali.hnqzz.top/Article/details/gt2jcblaicr.html

ROLLBACK TO sp1;
来源：http://dali.gogol.net.cn/Article/details/gt2xkuiqaor.html

[Q69] 查看执行计划
来源：http://dali.zhiwuduotai.top/Article/details/gt2njlhrjtw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xylfe.cn/Article/details/gt2jejqysle.html

[Q70] 更新统计信息
来源：http://dali.havefunace.top/Article/details/gt2mczkhcla.html

ANALYZE TABLE users;
来源：http://dali.yj20258.top/Article/details/gt2ywqkasyk.html

[Q71] 查看建表语句
来源：http://dali.yuxming.cn/Article/details/gt2gavecfmi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.vqdsnc.cn/Article/details/gt2gprzxlle.html

[Q72] 查看索引
来源：http://dali.zhoulong.xyz/Article/details/gt2pjxksekv.html

SHOW INDEX FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2rrherftv.html

[Q73] 查看表状态
来源：http://dali.pengpengdd.cyou/Article/details/gt2bfjftdhv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shuidangran.top/Article/details/gt2tunqkusg.html

[Q74] 强制使用索引
来源：http://dali.svipenyu.cn/Article/details/gt2hxbizxty.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.meibo888.top/Article/details/gt2ddubzbqm.html

[Q75] 日期格式化
来源：http://dali.ivvv.top/Article/details/gt2sahlulox.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gt2tzutkxzj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gogol.net.cn/Article/details/gt2fhvkybhu.html

[Q76] 按天统计
来源：http://dali.aibaodan.cn/Article/details/gt2zjbnrqyg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.0kj1m.cn/Article/details/gt2fwydnerg.html

[Q77] 时间加减
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ivaytnui.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj202588.top/Article/details/gt2rkxbvuwx.html

[Q78] 当前时间
来源：http://dali.jiagoushi.top/Article/details/gt2brbsersl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xziqi.cn/Article/details/gt2awklvcwo.html

[Q79] 字符串拼接
来源：http://dali.hammf.cn/Article/details/gt2bjwzwjxy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gogol.net.cn/Article/details/gt2tsyoqqlr.html

[Q80] 字符串截取
来源：http://dali.ivvv.top/Article/details/gt2dfmrihhi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2kcpbgejr.html

[Q81] 字符串替换
来源：http://dali.smart0.xyz/Article/details/gt2tdyexvuq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2vmjtyezm.html

[Q82] 字符长度与字节长度
来源：http://dali.quarkkingdee.top/Article/details/gt2ydyimppq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2capxpqdo.html

[Q83] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gt2kmoheidx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2xgkwnvln.html

[Q84] 去除首尾空格
来源：http://dali.hfpthk.cn/Article/details/gt2jaoybpih.html

SELECT TRIM(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2ethbkcgs.html

[Q85] 数值取整
来源：http://dali.yj20258.top/Article/details/gt2mnaauyww.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jyoumei.cn/Article/details/gt2hwezwdrd.html

[Q86] 读取 JSON 字段
来源：http://dali.yvedp.cn/Article/details/gt2riucoqli.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yanxiufei.cn/Article/details/gt2xihjncmz.html

[Q87] JSON 字段做条件
来源：http://dali.ivvv.top/Article/details/gt2ahnsxvpx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jlsjyb.cn/Article/details/gt2jxnrwkjq.html

[Q88] 行转列（条件聚合）
来源：http://dali.316326.xyz/Article/details/gt2guzqvoqp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yuxming.cn/Article/details/gt2jjuibxjn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2rqmdlgpq.html

[Q89] 判断表是否存在
来源：http://dali.gotoacloud.top/Article/details/gt2hqzgspjd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tianlin.xyz/Article/details/gt2jvjzcgrs.html

[Q90] 生成序号列
来源：http://dali.bjfxy.top/Article/details/gt2gxsrjeuo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jlsjyb.cn/Article/details/gt2ubpmnvyj.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2vnbkbojh.html

R. Bash 专题
来源：http://dali.yj20258888.top/Article/details/gt2qrfpwrxr.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2wiblefvn.html

[R01] shebang 与严格模式
来源：http://dali.zycfv.cn/Article/details/gt2zjjwsqpp.html

#!/usr/bin/env bash
来源：http://dali.daria6918.cn/Article/details/gt2oukydebz.html

set -euo pipefail
来源：http://dali.gotoacloud.top/Article/details/gt2xvsabjag.html

[R02] 变量赋值与使用
来源：http://dali.nanxuanxn.top/Article/details/gt2srgynnue.html

name="Tom"; echo "$name"
来源：http://dali.feifeiyinyue.top/Article/details/gt2qveiulzi.html

[R03] 只读变量
来源：http://dali.xziqi.cn/Article/details/gt2erjswqit.html

readonly PI=3.14
来源：http://dali.cqqwz.cn/Article/details/gt2weoirzfz.html

[R04] 位置参数
来源：http://dali.tanke756.top/Article/details/gt2fcyryemy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhengqikj.top/Article/details/gt2vqbymtej.html

[R05] 参数默认值
来源：http://dali.xinyue.icu/Article/details/gt2fudbzndx.html

name="${1:-default}"
来源：http://dali.quarkkingdee.top/Article/details/gt2bsgauocp.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbimcbo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gt2lukqcucf.html

[R07] if 判断文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2weckjcaf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hammf.cn/Article/details/gt2laxjxhbx.html

[R08] 数值比较
来源：http://dali.ivvv.top/Article/details/gt2zcnsmpcq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cashguo.top/Article/details/gt2qambkimn.html

[R09] 字符串比较
来源：http://dali.jqgfzy.top/Article/details/gt2fbxwyogi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qfhqkajd.html

[R10] 正则匹配
来源：http://dali.jyoumei.cn/Article/details/gt2xgmxvlfp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.bjfxy.top/Article/details/gt2dkzpuggt.html

[R11] case 多分支
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vxcuumsu.html

case "$1" in
来源：http://dali.chenzaomai.com/Article/details/gt2uksevugi.html

start) echo "启动" ;;
来源：http://dali.dashuyun.cn/Article/details/gt2miqbzbzo.html

stop)  echo "停止" ;;
来源：http://dali.jqgufenzy.top/Article/details/gt2jtimgrql.html

*)     echo "未知命令" ;;
来源：http://dali.yueranfly.top/Article/details/gt2attgcwvd.html

esac
来源：http://dali.zycfv.cn/Article/details/gt2kozsnelp.html

[R12] for 遍历文件
来源：http://dali.tanke756.top/Article/details/gt2juozcurw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jkprfpjt.html

[R13] for 计数循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qivpeome.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gt2xbdwsbyw.html

[R14] C 风格 for
来源：http://dali.nanxinkj.top/Article/details/gt2bcfpfgmm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gt2iklvynba.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xzsxbzaj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2cfuewebm.html

[R16] until 等待条件
来源：http://dali.yongpay.top/Article/details/gt2qxvoublq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jianghu66.top/Article/details/gt2sbawwiwv.html

[R17] 数组定义与取值
来源：http://dali.nanxinkj.top/Article/details/gt2lruhmxjj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2jurkhhix.html

[R18] 遍历数组
来源：http://dali.fzhhl.top/Article/details/gt2paqvlapo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.quarkkingdee.top/Article/details/gt2zxnejfkn.html

[R19] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2budgdgnh.html

echo "${#arr[@]}"
来源：http://dali.ppjwa.cn/Article/details/gt2wigclplx.html

[R20] 关联数组（字典）
来源：http://dali.cucudq.cn/Article/details/gt2unjrlbaw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xinyue.icu/Article/details/gt2uvtwywxb.html

[R21] 字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gt2ydboslrp.html

echo "${#s}"
来源：http://dali.mhx1999.top/Article/details/gt2dtwrotof.html

[R22] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gqhuvhdv.html

echo "${s:0:5}"
来源：http://dali.gzhubu.top/Article/details/gt2qplcynly.html

[R23] 字符串替换
来源：http://dali.redwolf501.top/Article/details/gt2gozjdfil.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aibaodan.cn/Article/details/gt2oghkbmrd.html

[R24] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gt2cgkxtcxo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yvedp.cn/Article/details/gt2dwfwjtst.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhixingplan.top/Article/details/gt2popqqefv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhongyouzk.top/Article/details/gt2qqqbrxur.html

[R26] 命令替换
来源：http://dali.guannengcc.top/Article/details/gt2hvrncyae.html

now=$(date +%F); echo "$now"
来源：http://dali.0kj1m.cn/Article/details/gt2afndcpco.html

[R27] 算术展开
来源：http://dali.zdqjudy.top/Article/details/gt2cyzybkrt.html

echo $((1 + 2 * 3))
来源：http://dali.yuxming.cn/Article/details/gt2llnevusz.html

[R28] 浮点运算
来源：http://dali.snrcjt.cn/Article/details/gt2fjdwobbx.html

echo "scale=2; 10/3" | bc
来源：http://dali.wangdashe.top/Article/details/gt2nmcceetu.html

[R29] 定义函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jqrdgzah.html


<!-- 参考信息 -->