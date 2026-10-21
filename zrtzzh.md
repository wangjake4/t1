代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shanyushiyangtech.top/Article/details/gtzoiwsmdl.html

TS:   if (x == null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhcgrrrq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.guannengcc.top/Article/details/gtihulpeqt.html

Go:   if x == nil {}
来源：http://dali.smart0.xyz/Article/details/gtphhsqztw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.snrcjt.cn/Article/details/gttfcenzhz.html

C#:   if (x is null) {}
来源：http://dali.xuetiantiany.cn/Article/details/gttppfxfvl.html

[P07] 防抖与节流
来源：http://dali.yj20258888.top/Article/details/gtlfniambh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yuanzhike.top/Article/details/gtthphcfnr.html

PHP:  // 手写时间戳比较
来源：http://dali.jinqigfzy.top/Article/details/gtfpxrivzq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gtyrvvnoqc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gtxszzmnyf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenzaomai.com/Article/details/gtzxmsrbbu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj202588.top/Article/details/gtuyhxvpcw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fengsongda.top/Article/details/gtarmqitxc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxrvozhc.html

[P08] 处理浮点精度问题
来源：http://dali.chenzaomai.com/Article/details/gtqsvowobo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.0kj1m.cn/Article/details/gtvpoekcgx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjaagiles.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.guowangkeji.top/Article/details/gtajnmlapq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.havefunace.top/Article/details/gtyppbnzmz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hammf.cn/Article/details/gteljedlsu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenzaomai.com/Article/details/gteigywdft.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.kuanghao11.cn/Article/details/gtoauaugxf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sufxvd.cn/Article/details/gtiemtfhap.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtqogkljjo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjiooxgs.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtuafvtaom.html

[Q01] 创建表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtckwmtoil.html

CREATE TABLE users (
来源：http://dali.dianchejie.cn/Article/details/gtclaitavq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxinkj.top/Article/details/gtfyewfwvr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gtmytxexhu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnqzz.top/Article/details/gtrvkbtsce.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yuanzhike.top/Article/details/gtkdpdgqye.html

);
来源：http://dali.hammf.cn/Article/details/gtmpzqfyqf.html

[Q02] 创建带外键的表
来源：http://dali.hnqzz.top/Article/details/gtzijwvyei.html

CREATE TABLE orders (
来源：http://dali.yj202588.top/Article/details/gtomfgjzvu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.meibo888.top/Article/details/gtdpzydimv.html

user_id INT NOT NULL,
来源：http://dali.andypj.xyz/Article/details/gttlwzpebf.html

amount DECIMAL(10, 2),
来源：http://dali.vqdsnc.cn/Article/details/gtugcvfenc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.feifeiyinyue.top/Article/details/gtpdppxrmc.html

);
来源：http://dali.gotoacloud.top/Article/details/gtaifnwqij.html

[Q03] 增加列
来源：http://dali.xinyue.icu/Article/details/gtddkwxunq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhengqikj.top/Article/details/gtnyjjsabm.html

[Q04] 修改列类型
来源：http://dali.tianlin.xyz/Article/details/gtvtxnhwwh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hongshengwenyu.top/Article/details/gtzvxfjtaq.html

[Q05] 重命名列
来源：http://dali.aibaodan.cn/Article/details/gttxdwrixc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nwbrower.top/Article/details/gtaqbhcvqf.html

[Q06] 删除列
来源：http://dali.pycfn.com/Article/details/gtorqlmboc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yanxiufei.cn/Article/details/gtykuiolhp.html

[Q07] 删除表
来源：http://dali.yanxiufei.cn/Article/details/gtatrdkijd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzcxrcqr.html

[Q08] 创建普通索引
来源：http://dali.gzhubu.top/Article/details/gtalyfuudc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcudjlay.html

[Q09] 创建唯一索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpphhjim.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhiwuduotai.top/Article/details/gtuozqlicu.html

[Q10] 插入单行
来源：http://dali.yvedp.cn/Article/details/gtbifmpbos.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gtjrzxuwsx.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdnbrwcls.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtforvoxvf.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangkeji.top/Article/details/gtluaozrsb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhoulong.xyz/Article/details/gtlprwkhth.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhiwuduotai.top/Article/details/gtwuyoreuq.html

[Q13] 忽略重复插入
来源：http://dali.9152youxi.cn/Article/details/gtcyrnaxxr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hysaishi.cn/Article/details/gtohdoourw.html

[Q14] 存在则更新（upsert）
来源：http://dali.mhx1999.top/Article/details/gttghlfufv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.pengpengdd.cyou/Article/details/gtmeedrkrc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cucudq.cn/Article/details/gtumfccnxt.html

[Q15] 查询全部
来源：http://dali.shanyushiyangkeji.top/Article/details/gtueninblz.html

SELECT * FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtxbhuvcwr.html

[Q16] 查询指定列
来源：http://dali.gaohongyu789.top/Article/details/gtbxmyufyh.html

SELECT id, name FROM users;
来源：http://dali.ivvv.top/Article/details/gtnnbnsjwl.html

[Q17] 条件查询
来源：http://dali.yanxiufei.cn/Article/details/gtpfousqhn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtogrmoldj.html

[Q18] 模糊匹配
来源：http://dali.fzhhl.top/Article/details/gtdwiyzvvr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinqigfzy.top/Article/details/gtqqfeigdz.html

[Q19] 范围查询
来源：http://dali.yuxming.cn/Article/details/gttblmxayk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.wangshuangyany.cn/Article/details/gtrnreikyu.html

[Q20] IN 列表
来源：http://dali.cashguo.top/Article/details/gtxaklqhpw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkamhghav.html

[Q21] 空值判断
来源：http://dali.tianlin.xyz/Article/details/gtfonxdkxz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xuanzx.com/Article/details/gtmffwiuzw.html

[Q22] 排序
来源：http://dali.haohaochexian.top/Article/details/gtrtzadncs.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gogol.net.cn/Article/details/gtiqacjwhd.html

[Q23] 分页
来源：http://dali.smart0.xyz/Article/details/gtfigkqxgv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yangfankeji.com/Article/details/gtuvvcabrq.html

[Q24] 去重
来源：http://dali.meibo888.top/Article/details/gtnklracin.html

SELECT DISTINCT city FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtjxqinnin.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangtech.top/Article/details/gtbsblnhkw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zycfv.cn/Article/details/gtkannrubv.html

[Q26] 计数
来源：http://dali.ivvv.top/Article/details/gtcgcitytr.html

SELECT COUNT(*) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtuweywfpy.html

[Q27] 条件计数
来源：http://dali.yuanzhike.top/Article/details/gtzjhbfmcu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmvfsxcw.html

[Q28] 求和与平均
来源：http://dali.daria6918.cn/Article/details/gtsfchkkao.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtexvqkdjc.html

[Q29] 最大最小值
来源：http://dali.fzhhl.top/Article/details/gtlpcarqal.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtedlkxvky.html

[Q30] 分组统计
来源：http://dali.yuanzhike.top/Article/details/gtudbymarj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtgspxrpnt.html

[Q31] 分组后过滤
来源：http://dali.zycfv.cn/Article/details/gtfcjhpekh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.guowangkeji.top/Article/details/gtkdaihfyy.html

[Q32] 分组拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtgpajkhqa.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtoxsrhwrp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmpocatu.html

[Q33] 多列分组
来源：http://dali.jlsjyb.cn/Article/details/gtswjeftpj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.haohaochexian.top/Article/details/gtpqvojmov.html

[Q34] 每组取第一条
来源：http://dali.cucudq.cn/Article/details/gtpzprzztb.html

SELECT * FROM (
来源：http://dali.gogol.net.cn/Article/details/gthpbzwhti.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shangyingyoupin.top/Article/details/gtqviirlln.html

) t WHERE rn = 1;
来源：http://dali.pycfn.com/Article/details/gtfcijdqwq.html

[Q35] 内连接
来源：http://dali.hammf.cn/Article/details/gtfgauimgn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgufenzy.top/Article/details/gthualtjxc.html

[Q36] 左连接
来源：http://dali.ivvv.top/Article/details/gtvfyvxqtp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.c1oappe.top/Article/details/gtywbgscgg.html

[Q37] 右连接
来源：http://dali.c1oappe.top/Article/details/gtuvtbeeic.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhixingplan.top/Article/details/gtrntbkyvu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xylfe.cn/Article/details/gtoqxqzzej.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zycfv.cn/Article/details/gtjdhpbxob.html

[Q39] 自连接（查上下级）
来源：http://dali.andypj.xyz/Article/details/gtmwnwukku.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgufenzy.top/Article/details/gtzkamqndy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yonumen.top/Article/details/gtfkgwknhg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.andypj.xyz/Article/details/gttfficpti.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aibaodan.cn/Article/details/gtpowazxnf.html

[Q41] 多表连接
来源：http://dali.xuanzx.com/Article/details/gtoamtpsfi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnbdeeob.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sxryk.cn/Article/details/gtqdxycwgo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jlsjyb.cn/Article/details/gtdepvpazv.html

[Q42] 连接条件附加过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrvohxuq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgomcaqt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.wangdashe.top/Article/details/gtelkyjjhu.html

[Q43] 标量子查询
来源：http://dali.zycfv.cn/Article/details/gtpomnqqdz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hnxiangtu.top/Article/details/gtdizxisnb.html

[Q44] IN 子查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvaxkhwl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gthphuzlcs.html

[Q45] EXISTS 判断存在
来源：http://dali.daxiang520.top/Article/details/gtplomuwfk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.9152youxi.cn/Article/details/gtikeatgeq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gogol.net.cn/Article/details/gthvgqwpyt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gtucmziofn.html

[Q47] 与平均值比较
来源：http://dali.xziqi.cn/Article/details/gtetjbyjod.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvayugqmi.html

[Q48] CTE 公用表表达式
来源：http://dali.redwolf501.top/Article/details/gtaxziigoj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.9152youxi.cn/Article/details/gtwyfvroio.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.redwolf501.top/Article/details/gtbhqgtuph.html

[Q49] 更新单行
来源：http://dali.jianghu66.top/Article/details/gtxeacviaw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.redwolf501.top/Article/details/gtvofkfvll.html

[Q50] 批量更新
来源：http://dali.wangdashe.top/Article/details/gtkvulwvvp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.316326.xyz/Article/details/gtpksyibjm.html

[Q51] 用子查询更新
来源：http://dali.nanxinkj.top/Article/details/gtsrnhiefa.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.meibo888.top/Article/details/gtjvislcjo.html

[Q52] 删除指定行
来源：http://dali.hnxiangtu.top/Article/details/gtdexmqnme.html

DELETE FROM users WHERE id = 10;
来源：http://dali.andypj.xyz/Article/details/gtxbrwotba.html

[Q53] 按条件删除
来源：http://dali.ivvv.top/Article/details/gtbomtdkms.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqjnnyui.html

[Q54] 清空表
来源：http://dali.yueranfly.top/Article/details/gtcsmgzhvh.html

TRUNCATE TABLE logs;
来源：http://dali.xziqi.cn/Article/details/gtfmkuvnlo.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gtaqzfnlrt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ydzc1.top/Article/details/gtntziyqdm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangdashe.top/Article/details/gtqppxqipg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yanxiufei.cn/Article/details/gtanhdrvkg.html

[Q57] 行号
来源：http://dali.zhixingplan.top/Article/details/gtttsrqifk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtojawvtww.html

[Q58] 累计求和
来源：http://dali.guannengcc.top/Article/details/gttzllndcm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtdmfhkepp.html

[Q59] 分组内累计
来源：http://dali.yonumen.top/Article/details/gtlhiafoic.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtyuwrrtas.html

[Q60] 取上一行 / 下一行
来源：http://dali.birdmap.top/Article/details/gtqyidtvxh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.haohaochexian.top/Article/details/gtpqrtxhss.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtpmbbwqag.html

[Q61] 移动平均
来源：http://dali.jiagoushi.top/Article/details/gtizzvtuqe.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtzjbccsyr.html

[Q62] 分组占比
来源：http://dali.jinqigfzy.top/Article/details/gtlztmgtlj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gtwvexxjjl.html

[Q63] 开启事务
来源：http://dali.yuxming.cn/Article/details/gtduikspdd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhiwuduotai.top/Article/details/gthhqclatm.html

[Q64] 提交事务
来源：http://dali.gaohongyu789.top/Article/details/gtfzpkbmws.html

COMMIT;
来源：http://dali.yueranfly.top/Article/details/gtgdfiecho.html

[Q65] 回滚事务
来源：http://dali.zhengqikj.top/Article/details/gtsdfqaiwc.html

ROLLBACK;
来源：http://dali.cheryme.top/Article/details/gttmkkbecf.html

[Q66] 行锁查询
来源：http://dali.gzhubu.top/Article/details/gtrmegsmmr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shuidangran.top/Article/details/gtgkmbetor.html

[Q67] 设置隔离级别
来源：http://dali.ivvv.top/Article/details/gtauxkhxnt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmdyrsnw.html

[Q68] 保存点
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyugaejjz.html

SAVEPOINT sp1;
来源：http://dali.yueranfly.top/Article/details/gtmzbsptnv.html

ROLLBACK TO sp1;
来源：http://dali.sysykeji.top/Article/details/gtfpxhvfqw.html

[Q69] 查看执行计划
来源：http://dali.jyoumei.cn/Article/details/gtrobfompm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jianghu66.top/Article/details/gtisuxupfe.html

[Q70] 更新统计信息
来源：http://dali.chenlongwang.top/Article/details/gtgkxfifox.html

ANALYZE TABLE users;
来源：http://dali.yj20258.top/Article/details/gtlqngvwnx.html

[Q71] 查看建表语句
来源：http://dali.yanxiufei.cn/Article/details/gtskusyjba.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinghuilouyu.cn/Article/details/gtggitycru.html

[Q72] 查看索引
来源：http://dali.gzhubu.top/Article/details/gtcqhrnqky.html

SHOW INDEX FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtuyrsbyow.html

[Q73] 查看表状态
来源：http://dali.svipenyu.cn/Article/details/gtoszbjleg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cdnleiting.top/Article/details/gtekrpdvnu.html

[Q74] 强制使用索引
来源：http://dali.sysykeji.top/Article/details/gtxhpxobfq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenzaomai.com/Article/details/gtyegtezbc.html

[Q75] 日期格式化
来源：http://dali.snrcjt.cn/Article/details/gtdytrmzld.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtxnndqrbf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangdashe.top/Article/details/gthaccpcvn.html

[Q76] 按天统计
来源：http://dali.quarkkingdee.top/Article/details/gtjbynpjcb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yonumen.top/Article/details/gtuazbwdep.html

[Q77] 时间加减
来源：http://dali.zhengqikj.top/Article/details/gtjyxinwct.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daria6918.cn/Article/details/gthiffmdge.html

[Q78] 当前时间
来源：http://dali.ppjwa.cn/Article/details/gtegbpeuku.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xinyue.icu/Article/details/gtacdcwxjz.html

[Q79] 字符串拼接
来源：http://dali.nanxuanxn.top/Article/details/gtiasxtssk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xuetiantiany.cn/Article/details/gtgzxbvypi.html

[Q80] 字符串截取
来源：http://dali.xinyue.icu/Article/details/gtwcfksmvh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtbbaxxnad.html

[Q81] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gtyelsaqoi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtfqislnox.html

[Q82] 字符长度与字节长度
来源：http://dali.zhoulong.xyz/Article/details/gtlqcuwiqd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtrzljalnz.html

[Q83] 大小写转换
来源：http://dali.yj202588.top/Article/details/gtllloxzba.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtikmwnutm.html

[Q84] 去除首尾空格
来源：http://dali.tian-w.cn/Article/details/gtagearzcj.html

SELECT TRIM(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtezuirjkk.html

[Q85] 数值取整
来源：http://dali.hnxiangtu.top/Article/details/gtlmgxurgy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jyoumei.cn/Article/details/gtvahwhtnh.html

[Q86] 读取 JSON 字段
来源：http://dali.xuanzx.com/Article/details/gtktzlmbfn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xuanzx.com/Article/details/gtmanxfedu.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigfzy.top/Article/details/gtftlgeoqx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ppjwa.cn/Article/details/gtrkufuspx.html

[Q88] 行转列（条件聚合）
来源：http://dali.nanxuanxn.top/Article/details/gtopjubbjy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nanxuanxn.top/Article/details/gtphgrjfbc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtatswlmct.html

[Q89] 判断表是否存在
来源：http://dali.0kj1m.cn/Article/details/gtowcefknn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xinyue.icu/Article/details/gtqkpslmbg.html

[Q90] 生成序号列
来源：http://dali.ehwqpu.com/Article/details/gtazxvorgi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xinyue.icu/Article/details/gtavaowink.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtvgeblqzy.html

R. Bash 专题
来源：http://dali.hnqzz.top/Article/details/gttedmsvar.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtwoakqqii.html

[R01] shebang 与严格模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrmtufzy.html

#!/usr/bin/env bash
来源：http://dali.316326.xyz/Article/details/gtqsdfqlfa.html

set -euo pipefail
来源：http://dali.tianlin.xyz/Article/details/gtodnvzalu.html

[R02] 变量赋值与使用
来源：http://dali.jinqigufen.top/Article/details/gtastzylfh.html

name="Tom"; echo "$name"
来源：http://dali.yanxiufei.cn/Article/details/gtskonlsky.html

[R03] 只读变量
来源：http://dali.yanxiufei.cn/Article/details/gtjmhftncy.html

readonly PI=3.14
来源：http://dali.shzxlz.cn/Article/details/gtmzegpysp.html

[R04] 位置参数
来源：http://dali.chenjidiqi.icu/Article/details/gtuldiosxv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aibaodan.cn/Article/details/gtnxgrciyf.html

[R05] 参数默认值
来源：http://dali.dashuyun.cn/Article/details/gtkagfbypn.html

name="${1:-default}"
来源：http://dali.zhixingplan.top/Article/details/gtkzwjdwkw.html

[R06] 判断命令是否存在
来源：http://dali.pycfn.com/Article/details/gtuyarvwtn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gtpakeyxxn.html

[R07] if 判断文件
来源：http://dali.vqdsnc.cn/Article/details/gtfsikyzoe.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.9152youxi.cn/Article/details/gtdyzqyxqh.html

[R08] 数值比较
来源：http://dali.chenjidiqi.icu/Article/details/gtvtsyuumh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.fengsongda.top/Article/details/gtdlhbbyoq.html

[R09] 字符串比较
来源：http://dali.aizwys.cn/Article/details/gtrehbnehf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gzhubu.top/Article/details/gtptpthbdl.html

[R10] 正则匹配
来源：http://dali.chenzaomai.com/Article/details/gtcclmwaas.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgfzy.top/Article/details/gtraxcbljp.html

[R11] case 多分支
来源：http://dali.cheryme.top/Article/details/gtsurxjonb.html

case "$1" in
来源：http://dali.yongpay.top/Article/details/gtenpwajwi.html

start) echo "启动" ;;
来源：http://dali.pycfn.com/Article/details/gtujfhesmf.html

stop)  echo "停止" ;;
来源：http://dali.c1oappe.top/Article/details/gtienexort.html

*)     echo "未知命令" ;;
来源：http://dali.sweek.top/Article/details/gtvheyrfnk.html

esac
来源：http://dali.zhixingplan.top/Article/details/gtvmhjgqnv.html

[R12] for 遍历文件
来源：http://dali.quarkkingdee.top/Article/details/gtqizedlsp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.birdmap.top/Article/details/gtczfzlezd.html

[R13] for 计数循环
来源：http://dali.feifeiyinyue.top/Article/details/gtkfijqsko.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gtmrncqgvz.html

[R14] C 风格 for
来源：http://dali.bjfxy.top/Article/details/gtwfxqskca.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gtisprrgaw.html

[R15] while 逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtpcmfudig.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aibaodan.cn/Article/details/gtsrxvhhrn.html

[R16] until 等待条件
来源：http://dali.fzhhl.top/Article/details/gtvsizsxnu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.aizwys.cn/Article/details/gtlnsssvjp.html

[R17] 数组定义与取值
来源：http://dali.haohaochexian.top/Article/details/gtbcvegtrt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258.top/Article/details/gtepfmiavz.html

[R18] 遍历数组
来源：http://dali.zhiwuduotai.top/Article/details/gtrxnqnuya.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.quarkkingdee.top/Article/details/gtbvwopwch.html

[R19] 数组长度
来源：http://dali.bjfxy.top/Article/details/gtsneensam.html

echo "${#arr[@]}"
来源：http://dali.chenlongwang.top/Article/details/gtiudncqbz.html

[R20] 关联数组（字典）
来源：http://dali.jianghu66.top/Article/details/gtbajugfiz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.0kj1m.cn/Article/details/gthwxbfxcl.html

[R21] 字符串长度
来源：http://dali.nwbrower.top/Article/details/gtnsovpsqb.html

echo "${#s}"
来源：http://dali.nwbrower.top/Article/details/gtdgiobcdg.html

[R22] 截取子串
来源：http://dali.zhiwuduotai.top/Article/details/gtacnciemb.html

echo "${s:0:5}"
来源：http://dali.xuetiantiany.cn/Article/details/gtkwnhqlks.html

[R23] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gtyijewoqr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkuckuqqo.html

[R24] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gtheqzxzvl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xuetiantiany.cn/Article/details/gtdzuxrtst.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj20258888.top/Article/details/gtlcxnmilq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yanxiufei.cn/Article/details/gtonvjwdon.html

[R26] 命令替换
来源：http://dali.aizwys.cn/Article/details/gtdsdgpuoa.html

now=$(date +%F); echo "$now"
来源：http://dali.sysykeji.top/Article/details/gtjjaooqhc.html

[R27] 算术展开
来源：http://dali.quarkkingdee.top/Article/details/gtsnflittz.html

echo $((1 + 2 * 3))
来源：http://dali.jinqigufen.top/Article/details/gtdqdwrhtm.html

[R28] 浮点运算
来源：http://dali.zhongyouzk.top/Article/details/gtmwgvbdgq.html

echo "scale=2; 10/3" | bc
来源：http://dali.cheryme.top/Article/details/gtjicowdvs.html

[R29] 定义函数
来源：http://dali.c1oappe.top/Article/details/gtzvbanjqw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yuanzhike.top/Article/details/gtnumtnejm.html

[R30] 函数返回状态码
来源：http://dali.jqgufenzy.top/Article/details/gtaxugfred.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtladgivcr.html

[R31] 局部变量
来源：http://dali.jlsjyb.cn/Article/details/gtinlbtfnj.html


<!-- 参考信息 -->