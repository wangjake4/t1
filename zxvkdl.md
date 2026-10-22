代发 wailian999

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cucudq.cn/Article/details/gt2ttgygsgd.html

C#:   if (x is null) {}
来源：http://dali.shzxlz.cn/Article/details/gt2nxyakmgv.html

[P07] 防抖与节流
来源：http://dali.yangfankeji.com/Article/details/gt2gsyiznhi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangdashe.top/Article/details/gt2kxmogiye.html

PHP:  // 手写时间戳比较
来源：http://dali.snrcjt.cn/Article/details/gt2qxqfdlyt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gt2fmidopcp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gt2ohujakmu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kiwvmgua.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj20258.top/Article/details/gt2wonwxmlk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenlongwang.top/Article/details/gt2rbpzcddn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jyoumei.cn/Article/details/gt2ihmnfkmb.html

[P08] 处理浮点精度问题
来源：http://dali.fengsongda.top/Article/details/gt2nifhoqzr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jlsjyb.cn/Article/details/gt2geyrlvrq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zdqjudy.top/Article/details/gt2ibakqudt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zdqjudy.top/Article/details/gt2iibnxzkc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ivvv.top/Article/details/gt2gqvyvnic.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yvedp.cn/Article/details/gt2stkplqaj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gaohongyu789.top/Article/details/gt2vglgjsne.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.mhx1999.top/Article/details/gt2iwmsnxdr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jlsjyb.cn/Article/details/gt2suylaboe.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2yuexaeif.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gotoacloud.top/Article/details/gt2jhcwulbo.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2ahsfquss.html

[Q01] 创建表
来源：http://dali.sysykeji.top/Article/details/gt2mdtmowfb.html

CREATE TABLE users (
来源：http://dali.cheryme.top/Article/details/gt2qfopmgml.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ttncudyq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.feifeiyinyue.top/Article/details/gt2vdtqsbsj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jcymkrzr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2jcihdvvv.html

);
来源：http://dali.yueranfly.top/Article/details/gt2qhnyezhc.html

[Q02] 创建带外键的表
来源：http://dali.yuanzhike.top/Article/details/gt2njccubab.html

CREATE TABLE orders (
来源：http://dali.hnqzz.top/Article/details/gt2hxvtyrks.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yueranfly.top/Article/details/gt2bhjhssvi.html

user_id INT NOT NULL,
来源：http://dali.shuidangran.top/Article/details/gt2gdxzfwwe.html

amount DECIMAL(10, 2),
来源：http://dali.iojbl.cn/Article/details/gt2wqqjlsue.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenzaomai.com/Article/details/gt2mawhojbq.html

);
来源：http://dali.tanke756.top/Article/details/gt2mlerynsj.html

[Q03] 增加列
来源：http://dali.ivvv.top/Article/details/gt2kkpqgynr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yanxiufei.cn/Article/details/gt2zwyuuswd.html

[Q04] 修改列类型
来源：http://dali.aizwys.cn/Article/details/gt2xlmfrokq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnxiangtu.top/Article/details/gt2fwhxiqln.html

[Q05] 重命名列
来源：http://dali.xuetiantiany.cn/Article/details/gt2lzjhvlhl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.aizwys.cn/Article/details/gt2tcjlvwlt.html

[Q06] 删除列
来源：http://dali.yonumen.top/Article/details/gt2yutmyedm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.haohaochexian.top/Article/details/gt2rbfajbmp.html

[Q07] 删除表
来源：http://dali.hnqzz.top/Article/details/gt2yggllyos.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zycfv.cn/Article/details/gt2lnpjvwrc.html

[Q08] 创建普通索引
来源：http://dali.gaohongyu789.top/Article/details/gt2lppuklae.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gt2mgswakdw.html

[Q09] 创建唯一索引
来源：http://dali.zycfv.cn/Article/details/gt2pxidbjid.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenzaomai.com/Article/details/gt2fpknrady.html

[Q10] 插入单行
来源：http://dali.yuxming.cn/Article/details/gt2ogujehlh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cdnleiting.top/Article/details/gt2lenbwphu.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hhqwnxje.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zpsxwwgg.html

[Q12] 插入后取自增 ID
来源：http://dali.sxryk.cn/Article/details/gt2ouhctcmc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jiagoushi.top/Article/details/gt2nfrqjoiq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xuetiantiany.cn/Article/details/gt2uhdbcdtw.html

[Q13] 忽略重复插入
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vobvultd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gt2giypsctk.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rkmbzwrj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yvedp.cn/Article/details/gt2paqnyhed.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yj20258.top/Article/details/gt2syvceovb.html

[Q15] 查询全部
来源：http://dali.hfpthk.cn/Article/details/gt2pdgsgeeh.html

SELECT * FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2uukobuex.html

[Q16] 查询指定列
来源：http://dali.jyoumei.cn/Article/details/gt2mjeebqqx.html

SELECT id, name FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2yltohfon.html

[Q17] 条件查询
来源：http://dali.hnxiangtu.top/Article/details/gt2yycvcbzk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jvmcwyzm.html

[Q18] 模糊匹配
来源：http://dali.yueranfly.top/Article/details/gt2qsjklwnx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.andypj.xyz/Article/details/gt2xgsodmyr.html

[Q19] 范围查询
来源：http://dali.tianlin.xyz/Article/details/gt2vwvdamcu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhoulong.xyz/Article/details/gt2umtvmrzn.html

[Q20] IN 列表
来源：http://dali.cheryme.top/Article/details/gt2qnovjofc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.fzhhl.top/Article/details/gt2tfgwqsln.html

[Q21] 空值判断
来源：http://dali.hongshengwenyu.top/Article/details/gt2mgpzffkh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gt2rmghashu.html

[Q22] 排序
来源：http://dali.yangfankeji.com/Article/details/gt2monpbbfp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yonumen.top/Article/details/gt2eendljoz.html

[Q23] 分页
来源：http://dali.cucudq.cn/Article/details/gt2agqwxsor.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhengqikj.top/Article/details/gt2jtppdktk.html

[Q24] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fvghhxre.html

SELECT DISTINCT city FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2lqxlvdpi.html

[Q25] 只取前 N 条
来源：http://dali.gotoacloud.top/Article/details/gt2zfdlqcmo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ybcxt.top/Article/details/gt2uleaobwk.html

[Q26] 计数
来源：http://dali.xuetiantiany.cn/Article/details/gt2jarnzuyb.html

SELECT COUNT(*) FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2zwsoovuq.html

[Q27] 条件计数
来源：http://dali.snrcjt.cn/Article/details/gt2qoouzijt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2dbbhbwvq.html

[Q28] 求和与平均
来源：http://dali.yangfankeji.com/Article/details/gt2zoklkmuz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tanke756.top/Article/details/gt2viumobpm.html

[Q29] 最大最小值
来源：http://dali.sysykeji.top/Article/details/gt2cbpvbkcs.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2lzllhurs.html

[Q30] 分组统计
来源：http://dali.fzhhl.top/Article/details/gt2ocqfreyw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gt2xsvtwxaq.html

[Q31] 分组后过滤
来源：http://dali.wangshuangyany.cn/Article/details/gt2jaebwftw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhoulong.xyz/Article/details/gt2tdaspvgq.html

[Q32] 分组拼接字符串
来源：http://dali.iojbl.cn/Article/details/gt2shccmyta.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gt2jddjaepv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jyoumei.cn/Article/details/gt2dyqsmixr.html

[Q33] 多列分组
来源：http://dali.dashuyun.cn/Article/details/gt2rekssbzh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cqqwz.cn/Article/details/gt2ofurrplk.html

[Q34] 每组取第一条
来源：http://dali.sysykeji.top/Article/details/gt2zvajbclu.html

SELECT * FROM (
来源：http://dali.yueranfly.top/Article/details/gt2gzvkract.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zdqjudy.top/Article/details/gt2tchjxjdm.html

) t WHERE rn = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2bjicdcoa.html

[Q35] 内连接
来源：http://dali.daxiang520.top/Article/details/gt2uawfehwl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zakqnhct.html

[Q36] 左连接
来源：http://dali.jlsjyb.cn/Article/details/gt2azxbhoym.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jxkjknwn.html

[Q37] 右连接
来源：http://dali.yanxiufei.cn/Article/details/gt2bcbjhcze.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ubqhuawy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sxryk.cn/Article/details/gt2ufisqqxk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.haohaochexian.top/Article/details/gt2zfusjspi.html

[Q39] 自连接（查上下级）
来源：http://dali.smart0.xyz/Article/details/gt2ouxztgmy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.pengpengdd.cyou/Article/details/gt2kknesuqk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qhfdsufa.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hfpthk.cn/Article/details/gt2bqmhiqoj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.c1oappe.top/Article/details/gt2hoxofflw.html

[Q41] 多表连接
来源：http://dali.guannengcc.top/Article/details/gt2vpytpvvo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yuxming.cn/Article/details/gt2vasyffvn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gotoacloud.top/Article/details/gt2lngkqthe.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.9152youxi.cn/Article/details/gt2gnjixvme.html

[Q42] 连接条件附加过滤
来源：http://dali.xuetiantiany.cn/Article/details/gt2mfwfxzje.html

SELECT u.name, o.amount FROM users u
来源：http://dali.daxiang520.top/Article/details/gt2mxeuukuc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuxming.cn/Article/details/gt2yhyfdiqv.html

[Q43] 标量子查询
来源：http://dali.andypj.xyz/Article/details/gt2cpjshkpj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bhtraoum.html

[Q44] IN 子查询
来源：http://dali.cqqwz.cn/Article/details/gt2emonqdxz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sjznyver.html

[Q45] EXISTS 判断存在
来源：http://dali.nwbrower.top/Article/details/gt2pdnjbxsw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gt2akvwhvit.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.pycfn.com/Article/details/gt2vhostlgt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gt2irduqnve.html

[Q47] 与平均值比较
来源：http://dali.gogol.net.cn/Article/details/gt2cyajqrsn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhongyouzk.top/Article/details/gt2ktngxzhw.html

[Q48] CTE 公用表表达式
来源：http://dali.ybcxt.top/Article/details/gt2sebraxzo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.iojbl.cn/Article/details/gt2erwacekr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xziqi.cn/Article/details/gt2djagpnlh.html

[Q49] 更新单行
来源：http://dali.shangyingyoupin.top/Article/details/gt2aknqjyor.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhongyouzk.top/Article/details/gt2tybatkrp.html

[Q50] 批量更新
来源：http://dali.yangfankeji.com/Article/details/gt2clxknwmu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2idctrsvg.html

[Q51] 用子查询更新
来源：http://dali.zycfv.cn/Article/details/gt2zdittdgy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ppjwa.cn/Article/details/gt2yaawtqky.html

[Q52] 删除指定行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gjyaifgy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.daxiang520.top/Article/details/gt2pxhlpaps.html

[Q53] 按条件删除
来源：http://dali.shzxlz.cn/Article/details/gt2evhvvppu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ydzc1.top/Article/details/gt2cbzbpgsa.html

[Q54] 清空表
来源：http://dali.hywenlv.cn/Article/details/gt2uttvmtbm.html

TRUNCATE TABLE logs;
来源：http://dali.cucudq.cn/Article/details/gt2sbrrtzgf.html

[Q55] 排名（并列占位）
来源：http://dali.yuanzhike.top/Article/details/gt2xogblimf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sufxvd.cn/Article/details/gt2rqyelvgi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhixingplan.top/Article/details/gt2tsnbhnnd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nplnstpn.html

[Q57] 行号
来源：http://dali.gzhubu.top/Article/details/gt2uwkvsoyx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2muhenqea.html

[Q58] 累计求和
来源：http://dali.yongpay.top/Article/details/gt2dlihwxip.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2pmglqdlv.html

[Q59] 分组内累计
来源：http://dali.zhixingplan.top/Article/details/gt2tsybfsoz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gt2rpxzhrpa.html

[Q60] 取上一行 / 下一行
来源：http://dali.daxiang520.top/Article/details/gt2cnhbgnie.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ydzc1.top/Article/details/gt2coupipmz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hjexpcap.html

[Q61] 移动平均
来源：http://dali.iojbl.cn/Article/details/gt2htmovtwq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lvekeasm.html

[Q62] 分组占比
来源：http://dali.birdmap.top/Article/details/gt2qrxoxbue.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gt2fyevykal.html

[Q63] 开启事务
来源：http://dali.svipenyu.cn/Article/details/gt2whgutgrf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.guowangkeji.top/Article/details/gt2pyerhenq.html

[Q64] 提交事务
来源：http://dali.jianghu66.top/Article/details/gt2jzudgrwd.html

COMMIT;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wiozdzky.html

[Q65] 回滚事务
来源：http://dali.xylfe.cn/Article/details/gt2fvoavyyo.html

ROLLBACK;
来源：http://dali.yvedp.cn/Article/details/gt2ssepheui.html

[Q66] 行锁查询
来源：http://dali.316326.xyz/Article/details/gt2zhvcsmtm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnxiangtu.top/Article/details/gt2lbldvwtd.html

[Q67] 设置隔离级别
来源：http://dali.kuanghao11.cn/Article/details/gt2dgdymgev.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shzxlz.cn/Article/details/gt2lyzeazqz.html

[Q68] 保存点
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eesmhvux.html

SAVEPOINT sp1;
来源：http://dali.c1oappe.top/Article/details/gt2ctoabhya.html

ROLLBACK TO sp1;
来源：http://dali.hnqzz.top/Article/details/gt2kdvjwoop.html

[Q69] 查看执行计划
来源：http://dali.ppjwa.cn/Article/details/gt2gotaaaym.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sxryk.cn/Article/details/gt2mkqsydkq.html

[Q70] 更新统计信息
来源：http://dali.chenzaomai.com/Article/details/gt2oxvhmiod.html

ANALYZE TABLE users;
来源：http://dali.cashguo.top/Article/details/gt2osxxkqka.html

[Q71] 查看建表语句
来源：http://dali.xuetiantiany.cn/Article/details/gt2szssplnc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhoulong.xyz/Article/details/gt2vupufwxr.html

[Q72] 查看索引
来源：http://dali.hnxiangtu.top/Article/details/gt2vsouzity.html

SHOW INDEX FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2eggtnald.html

[Q73] 查看表状态
来源：http://dali.0kj1m.cn/Article/details/gt2eejhavol.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.redwolf501.top/Article/details/gt2phtrgvpk.html

[Q74] 强制使用索引
来源：http://dali.guowangkeji.top/Article/details/gt2jxvkkdpb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cheryme.top/Article/details/gt2epqovwvz.html

[Q75] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gt2rlphmwri.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2gvlyhion.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zycfv.cn/Article/details/gt2tpetemye.html

[Q76] 按天统计
来源：http://dali.jianghu66.top/Article/details/gt2obvuxmte.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.0kj1m.cn/Article/details/gt2nmnycvxm.html

[Q77] 时间加减
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gubeoitn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj202588.top/Article/details/gt2stjxivvn.html

[Q78] 当前时间
来源：http://dali.316326.xyz/Article/details/gt2apmmowku.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhengqikj.top/Article/details/gt2atkcfxnr.html

[Q79] 字符串拼接
来源：http://dali.daria6918.cn/Article/details/gt2elundksy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cheryme.top/Article/details/gt2jibsoxns.html

[Q80] 字符串截取
来源：http://dali.mhx1999.top/Article/details/gt2pmrzeoog.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2kaownfbe.html

[Q81] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gt2scnvtieg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2tmoovctv.html

[Q82] 字符长度与字节长度
来源：http://dali.kuanghao11.cn/Article/details/gt2aumjstww.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2joatuawj.html

[Q83] 大小写转换
来源：http://dali.vqdsnc.cn/Article/details/gt2zuzhsqkx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2wqvdwiec.html

[Q84] 去除首尾空格
来源：http://dali.xziqi.cn/Article/details/gt2tzzxdydp.html

SELECT TRIM(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2xbssxsyg.html

[Q85] 数值取整
来源：http://dali.shuidangran.top/Article/details/gt2esldfkhc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.guannengcc.top/Article/details/gt2lhacodum.html

[Q86] 读取 JSON 字段
来源：http://dali.xylfe.cn/Article/details/gt2cwjpwoeg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jqgfzy.top/Article/details/gt2myoixofv.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwgazti.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zdqjudy.top/Article/details/gt2pzprnehf.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinqigufen.top/Article/details/gt2hekvzjak.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.havefunace.top/Article/details/gt2knvibitw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2mswvgjgk.html

[Q89] 判断表是否存在
来源：http://dali.yonumen.top/Article/details/gt2rniaeofz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuanzx.com/Article/details/gt2wanwhymv.html

[Q90] 生成序号列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dmyyuroo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gzhubu.top/Article/details/gt2xzlskwxa.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2qyvmoncm.html

R. Bash 专题
来源：http://dali.gzhubu.top/Article/details/gt2dlpabfts.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2eueydklp.html

[R01] shebang 与严格模式
来源：http://dali.zhiwuduotai.top/Article/details/gt2etucppnv.html

#!/usr/bin/env bash
来源：http://dali.pengpengdd.cyou/Article/details/gt2lkxsldmd.html

set -euo pipefail
来源：http://dali.sufxvd.cn/Article/details/gt2ydbcppdi.html

[R02] 变量赋值与使用
来源：http://dali.aibaodan.cn/Article/details/gt2doexldcc.html

name="Tom"; echo "$name"
来源：http://dali.ivvv.top/Article/details/gt2kuoaawlw.html

[R03] 只读变量
来源：http://dali.yj20258.top/Article/details/gt2ccovmnod.html

readonly PI=3.14
来源：http://dali.iojbl.cn/Article/details/gt2vigjgynj.html

[R04] 位置参数
来源：http://dali.shuidangran.top/Article/details/gt2xgjdjlyq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.smart0.xyz/Article/details/gt2cluzskdl.html

[R05] 参数默认值
来源：http://dali.svipenyu.cn/Article/details/gt2rjjzbmcg.html

name="${1:-default}"
来源：http://dali.cdnleiting.top/Article/details/gt2rgzfrrwe.html

[R06] 判断命令是否存在
来源：http://dali.xuanzx.com/Article/details/gt2pfeiwmdj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuxming.cn/Article/details/gt2yjinxiyh.html

[R07] if 判断文件
来源：http://dali.jyoumei.cn/Article/details/gt2pdkzyezu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.wangdashe.top/Article/details/gt2nshmnxjz.html

[R08] 数值比较
来源：http://dali.smart0.xyz/Article/details/gt2jckgymsd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.meibo888.top/Article/details/gt2ggsiyjrz.html

[R09] 字符串比较
来源：http://dali.pycfn.com/Article/details/gt2mtjsgcmt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xylfe.cn/Article/details/gt2rwyoacig.html

[R10] 正则匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jagnvgef.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fengsongda.top/Article/details/gt2kxoabuie.html

[R11] case 多分支
来源：http://dali.zhixingplan.top/Article/details/gt2blpgymsh.html

case "$1" in
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zbgslhdr.html

start) echo "启动" ;;
来源：http://dali.hysaishi.cn/Article/details/gt2qkpbycsd.html

stop)  echo "停止" ;;
来源：http://dali.yongpay.top/Article/details/gt2xngwmjqg.html

*)     echo "未知命令" ;;
来源：http://dali.snrcjt.cn/Article/details/gt2gdkwgmpi.html

esac
来源：http://dali.xuetiantiany.cn/Article/details/gt2zjbngtml.html

[R12] for 遍历文件
来源：http://dali.havefunace.top/Article/details/gt2hkqeqgnt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.iojbl.cn/Article/details/gt2eplbfbzt.html

[R13] for 计数循环
来源：http://dali.jqgfzy.top/Article/details/gt2tximrori.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gt2bdlffqxe.html

[R14] C 风格 for
来源：http://dali.hongshengwenyu.top/Article/details/gt2hnansalq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinqigufen.top/Article/details/gt2tdbyeuub.html

[R15] while 逐行读文件
来源：http://dali.smart0.xyz/Article/details/gt2iqhhubgl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jianghu66.top/Article/details/gt2dnhxlxwa.html

[R16] until 等待条件
来源：http://dali.vqdsnc.cn/Article/details/gt2pyniddnq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuxming.cn/Article/details/gt2lalaqefy.html

[R17] 数组定义与取值
来源：http://dali.cucudq.cn/Article/details/gt2vosiypot.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ybcxt.top/Article/details/gt2bldgaufv.html

[R18] 遍历数组
来源：http://dali.yj202588.top/Article/details/gt2atbojbch.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shzxlz.cn/Article/details/gt2pqcgmjpu.html

[R19] 数组长度
来源：http://dali.hnqzz.top/Article/details/gt2dhbseebw.html

echo "${#arr[@]}"
来源：http://dali.ydzc1.top/Article/details/gt2hyiwally.html

[R20] 关联数组（字典）
来源：http://dali.sysykeji.top/Article/details/gt2jhtdfsty.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.smart0.xyz/Article/details/gt2wsjimedq.html

[R21] 字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gt2lhmfsdrk.html

echo "${#s}"
来源：http://dali.yongpay.top/Article/details/gt2lcwprwmc.html

[R22] 截取子串
来源：http://dali.chenlongwang.top/Article/details/gt2vqfzlewv.html

echo "${s:0:5}"
来源：http://dali.zycfv.cn/Article/details/gt2xuonizai.html

[R23] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rejqeauj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hammf.cn/Article/details/gt2hdomiisq.html

[R24] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gt2tbtodfws.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zycfv.cn/Article/details/gt2bjgjqxus.html

[R25] 去后缀 / 去前缀
来源：http://dali.daxiang520.top/Article/details/gt2mnfvxckf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cheryme.top/Article/details/gt2vgbxxocq.html

[R26] 命令替换
来源：http://dali.shuidangran.top/Article/details/gt2ipakgmpq.html

now=$(date +%F); echo "$now"
来源：http://dali.haohaochexian.top/Article/details/gt2uldqkykq.html

[R27] 算术展开
来源：http://dali.fengsongda.top/Article/details/gt2iaqshxtq.html

echo $((1 + 2 * 3))
来源：http://dali.shzxlz.cn/Article/details/gt2iftpnkrf.html

[R28] 浮点运算
来源：http://dali.sysykeji.top/Article/details/gt2ssrktvvu.html

echo "scale=2; 10/3" | bc
来源：http://dali.shangyingyoupin.top/Article/details/gt2jibqjtfi.html

[R29] 定义函数
来源：http://dali.havefunace.top/Article/details/gt2giaeipji.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hongshengwenyu.top/Article/details/gt2phewczqb.html

[R30] 函数返回状态码
来源：http://dali.kuanghao11.cn/Article/details/gt2ztbjarrh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yueranfly.top/Article/details/gt2gxergsvl.html

[R31] 局部变量
来源：http://dali.yj202588.top/Article/details/gt2entxrhyl.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2usnefzqx.html

[R32] 参数个数校验
来源：http://dali.gogol.net.cn/Article/details/gt2hhlyxonu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gt2frxuymly.html

[R33] 捕获错误并提示行号
来源：http://dali.wangdashe.top/Article/details/gt2wjwrdjqr.html


<!-- 参考信息 -->