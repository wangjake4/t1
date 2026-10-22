代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yueranfly.top/Article/details/gt2kpywllab.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hmkzfxwi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yangfankeji.com/Article/details/gt2vvgpkahb.html

PHP:  if (empty($x)) {}
来源：http://dali.dashuyun.cn/Article/details/gt2zqgjxohm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shangyingyoupin.top/Article/details/gt2laubgzug.html

TS:   if (x == null) {}
来源：http://dali.daxiang520.top/Article/details/gt2qvcngzrx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gt2jzoanveq.html

Go:   if x == nil {}
来源：http://dali.cucudq.cn/Article/details/gt2glphcgqm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.fzhhl.top/Article/details/gt2tnwxacxf.html

C#:   if (x is null) {}
来源：http://dali.sweek.top/Article/details/gt2buszsigy.html

[P07] 防抖与节流
来源：http://dali.nwbrower.top/Article/details/gt2fotvteoz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jqgufenzy.top/Article/details/gt2mgqqswgv.html

PHP:  // 手写时间戳比较
来源：http://dali.yonumen.top/Article/details/gt2hlbpqaxf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gt2ozgrkddv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gt2rjotjnhq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ppjwa.cn/Article/details/gt2fgtawtqs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cqqwz.cn/Article/details/gt2piobnvyu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.aizwys.cn/Article/details/gt2ixglhdok.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj20258888.top/Article/details/gt2sdayqmjv.html

[P08] 处理浮点精度问题
来源：http://dali.shangyingyoupin.top/Article/details/gt2txzxnvln.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.daria6918.cn/Article/details/gt2jrirxbfp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yonumen.top/Article/details/gt2bpcgduam.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hnqzz.top/Article/details/gt2owvuztzm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenlongwang.top/Article/details/gt2sovlkijq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangdashe.top/Article/details/gt2kwhmtzrv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.andypj.xyz/Article/details/gt2aohptuvh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jqgfzy.top/Article/details/gt2wmqrinkh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.aizwys.cn/Article/details/gt2zjxqobis.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2mhwdxqpd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.bjfxy.top/Article/details/gt2oahqupum.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2hfojxzrn.html

[Q01] 创建表
来源：http://dali.pengpengdd.cyou/Article/details/gt2mtjhktyu.html

CREATE TABLE users (
来源：http://dali.jqgufenzy.top/Article/details/gt2sjzgzlie.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhiwuduotai.top/Article/details/gt2zzbyskfl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ybcxt.top/Article/details/gt2booibmvk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.daxiang520.top/Article/details/gt2jgpjahqb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.316326.xyz/Article/details/gt2gwxdgkeh.html

);
来源：http://dali.cheryme.top/Article/details/gt2eerfynrh.html

[Q02] 创建带外键的表
来源：http://dali.yvedp.cn/Article/details/gt2gilokckz.html

CREATE TABLE orders (
来源：http://dali.guannengcc.top/Article/details/gt2dznnwhmj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenlongwang.top/Article/details/gt2acswyron.html

user_id INT NOT NULL,
来源：http://dali.shuidangran.top/Article/details/gt2gflydqxe.html

amount DECIMAL(10, 2),
来源：http://dali.yangfankeji.com/Article/details/gt2rehxfwnb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cashguo.top/Article/details/gt2tumozrsd.html

);
来源：http://dali.kuanghao11.cn/Article/details/gt2ifhhpxjs.html

[Q03] 增加列
来源：http://dali.cheryme.top/Article/details/gt2ypimjrup.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.andypj.xyz/Article/details/gt2ltggptlr.html

[Q04] 修改列类型
来源：http://dali.xinyue.icu/Article/details/gt2llmrrkmh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.svipenyu.cn/Article/details/gt2ouqdxhgk.html

[Q05] 重命名列
来源：http://dali.yueranfly.top/Article/details/gt2nsprvghm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xziqi.cn/Article/details/gt2xfsbuajo.html

[Q06] 删除列
来源：http://dali.zhixingplan.top/Article/details/gt2pjvdldyn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.daria6918.cn/Article/details/gt2hziddhpg.html

[Q07] 删除表
来源：http://dali.yueranfly.top/Article/details/gt2soarnvkj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.svipenyu.cn/Article/details/gt2kqgszqic.html

[Q08] 创建普通索引
来源：http://dali.gotoacloud.top/Article/details/gt2qdllnwdb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gt2gejhpfzo.html

[Q09] 创建唯一索引
来源：http://dali.pengpengdd.cyou/Article/details/gt2gsbgtaus.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xegpinnf.html

[Q10] 插入单行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mzxucsci.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hnqzz.top/Article/details/gt2wuaupjen.html

[Q11] 一次插入多行
来源：http://dali.jianghu66.top/Article/details/gt2autnvhis.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.daxiang520.top/Article/details/gt2aejxkwnw.html

[Q12] 插入后取自增 ID
来源：http://dali.redwolf501.top/Article/details/gt2vjitzjyi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.daxiang520.top/Article/details/gt2ungdnwqv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.feifeiyinyue.top/Article/details/gt2rmseremp.html

[Q13] 忽略重复插入
来源：http://dali.tian-w.cn/Article/details/gt2hylxyeiq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangdashe.top/Article/details/gt2oxxmoihb.html

[Q14] 存在则更新（upsert）
来源：http://dali.nwbrower.top/Article/details/gt2nveejnsm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.daria6918.cn/Article/details/gt2jdinyjky.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.feifeiyinyue.top/Article/details/gt2enwfxsml.html

[Q15] 查询全部
来源：http://dali.kuanghao11.cn/Article/details/gt2cyfysmgt.html

SELECT * FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2nsdfsulq.html

[Q16] 查询指定列
来源：http://dali.jyoumei.cn/Article/details/gt2tqkdqnfm.html

SELECT id, name FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2dzhzlwmu.html

[Q17] 条件查询
来源：http://dali.zhongyouzk.top/Article/details/gt2ebgexysr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.redwolf501.top/Article/details/gt2fqrrwbww.html

[Q18] 模糊匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pcawvudc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hongshengwenyu.top/Article/details/gt2vsjchkle.html

[Q19] 范围查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nvmhshzu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhoulong.xyz/Article/details/gt2wkogrpnl.html

[Q20] IN 列表
来源：http://dali.ydzc1.top/Article/details/gt2gftrujvz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ppjwa.cn/Article/details/gt2jovldfoa.html

[Q21] 空值判断
来源：http://dali.daxiang520.top/Article/details/gt2otyjexfi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ycgdpiko.html

[Q22] 排序
来源：http://dali.pycfn.com/Article/details/gt2gkkkplou.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xinyue.icu/Article/details/gt2qlcwwmbs.html

[Q23] 分页
来源：http://dali.zycfv.cn/Article/details/gt2rlpahlfk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sxryk.cn/Article/details/gt2fqnamnlf.html

[Q24] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uhwqfgcy.html

SELECT DISTINCT city FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2uapclsvq.html

[Q25] 只取前 N 条
来源：http://dali.nanxuanxn.top/Article/details/gt2gqbrihii.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yueranfly.top/Article/details/gt2jvadbtgs.html

[Q26] 计数
来源：http://dali.hfpthk.cn/Article/details/gt2rmhapuqz.html

SELECT COUNT(*) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2nppqhdkg.html

[Q27] 条件计数
来源：http://dali.andypj.xyz/Article/details/gt2bjtucgxq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2kudumqib.html

[Q28] 求和与平均
来源：http://dali.yvedp.cn/Article/details/gt2ypiijssv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2ymuegkxw.html

[Q29] 最大最小值
来源：http://dali.0kj1m.cn/Article/details/gt2ithrgsqr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2xxchcywi.html

[Q30] 分组统计
来源：http://dali.jianghu66.top/Article/details/gt2uivrfiri.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gt2rrjvgwlk.html

[Q31] 分组后过滤
来源：http://dali.sysykeji.top/Article/details/gt2vbifthlq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yuanzhike.top/Article/details/gt2mivpwhol.html

[Q32] 分组拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2auuqoqju.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gt2hqkxcxtc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenjidiqi.icu/Article/details/gt2dxvbszaj.html

[Q33] 多列分组
来源：http://dali.guowangkeji.top/Article/details/gt2dnjizluw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenzaomai.com/Article/details/gt2xjtuuotj.html

[Q34] 每组取第一条
来源：http://dali.hfpthk.cn/Article/details/gt2fbpdfwli.html

SELECT * FROM (
来源：http://dali.ehwqpu.com/Article/details/gt2iebtnzqq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xinyue.icu/Article/details/gt2smarktgn.html

) t WHERE rn = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2mbsyvajf.html

[Q35] 内连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2namhmepp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.guannengcc.top/Article/details/gt2zeihauyn.html

[Q36] 左连接
来源：http://dali.cqqwz.cn/Article/details/gt2jzuibjoo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.pengpengdd.cyou/Article/details/gt2bziosufy.html

[Q37] 右连接
来源：http://dali.zhongyouzk.top/Article/details/gt2icqsqyux.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.haohaochexian.top/Article/details/gt2ahpeahje.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.dianchejie.cn/Article/details/gt2lirepicy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yueranfly.top/Article/details/gt2fjvwqbsf.html

[Q39] 自连接（查上下级）
来源：http://dali.fengsongda.top/Article/details/gt2rnlvgsam.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yongpay.top/Article/details/gt2ojxafdsg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yueranfly.top/Article/details/gt2rlxedops.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangdashe.top/Article/details/gt2xfhhsuqh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cqqwz.cn/Article/details/gt2viegrcen.html

[Q41] 多表连接
来源：http://dali.yangfankeji.com/Article/details/gt2feobyupm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hongshengwenyu.top/Article/details/gt2xzapnvgc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yueranfly.top/Article/details/gt2evyfbfbq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.kuanghao11.cn/Article/details/gt2futhlwuk.html

[Q42] 连接条件附加过滤
来源：http://dali.smart0.xyz/Article/details/gt2qxrlbkqa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhixingplan.top/Article/details/gt2dwpowyyc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ieymazsv.html

[Q43] 标量子查询
来源：http://dali.yj202588.top/Article/details/gt2aufkulsi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xinyue.icu/Article/details/gt2ezdeyyke.html

[Q44] IN 子查询
来源：http://dali.yueranfly.top/Article/details/gt2torfsjoe.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.9152youxi.cn/Article/details/gt2tpmbizpq.html

[Q45] EXISTS 判断存在
来源：http://dali.zhengqikj.top/Article/details/gt2mtxkiadi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yonumen.top/Article/details/gt2fjtxostc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.9152youxi.cn/Article/details/gt2lyokissr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gt2zxanipdu.html

[Q47] 与平均值比较
来源：http://dali.daxiang520.top/Article/details/gt2smglkrwd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.feifeiyinyue.top/Article/details/gt2vumsqcaq.html

[Q48] CTE 公用表表达式
来源：http://dali.ppjwa.cn/Article/details/gt2bhpqvfqc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lrwczxtt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.quarkkingdee.top/Article/details/gt2vqncwjrp.html

[Q49] 更新单行
来源：http://dali.xziqi.cn/Article/details/gt2chreibxd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gt2acaktfcz.html

[Q50] 批量更新
来源：http://dali.chenzaomai.com/Article/details/gt2vsehcptz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gt2dkuyncmq.html

[Q51] 用子查询更新
来源：http://dali.yueranfly.top/Article/details/gt2haohdmun.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tanke756.top/Article/details/gt2etkbzvxx.html

[Q52] 删除指定行
来源：http://dali.feifeiyinyue.top/Article/details/gt2drltboru.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yanxiufei.cn/Article/details/gt2okxcedga.html

[Q53] 按条件删除
来源：http://dali.gogol.net.cn/Article/details/gt2zoeylotk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yvedp.cn/Article/details/gt2ntyjceki.html

[Q54] 清空表
来源：http://dali.daxiang520.top/Article/details/gt2zzdjjhoz.html

TRUNCATE TABLE logs;
来源：http://dali.xuanzx.com/Article/details/gt2enwztpao.html

[Q55] 排名（并列占位）
来源：http://dali.hnxiangtu.top/Article/details/gt2candzbwq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jiagoushi.top/Article/details/gt2nakwfosg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cashguo.top/Article/details/gt2ewtdonat.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.wangdashe.top/Article/details/gt2mucyrgti.html

[Q57] 行号
来源：http://dali.nwbrower.top/Article/details/gt2pcbcqtwt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2sesgvray.html

[Q58] 累计求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2paecoulg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sxryk.cn/Article/details/gt2ycluizgq.html

[Q59] 分组内累计
来源：http://dali.zhiwuduotai.top/Article/details/gt2mexwlgqi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2wiyyhhie.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhixingplan.top/Article/details/gt2yeuxyfdr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iwbqtlju.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2iespohok.html

[Q61] 移动平均
来源：http://dali.dianchejie.cn/Article/details/gt2guwtpmpt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2sfhdvegp.html

[Q62] 分组占比
来源：http://dali.gaohongyu789.top/Article/details/gt2vulondcc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gt2kocfnjbp.html

[Q63] 开启事务
来源：http://dali.wangdashe.top/Article/details/gt2arapeyes.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.feifeiyinyue.top/Article/details/gt2qfmcterq.html

[Q64] 提交事务
来源：http://dali.hfpthk.cn/Article/details/gt2pgvkvgai.html

COMMIT;
来源：http://dali.zhixingplan.top/Article/details/gt2girwcwaq.html

[Q65] 回滚事务
来源：http://dali.zhongyouzk.top/Article/details/gt2ynvskjpl.html

ROLLBACK;
来源：http://dali.meibo888.top/Article/details/gt2yjlohqmv.html

[Q66] 行锁查询
来源：http://dali.nanxinkj.top/Article/details/gt2ffqmiozc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.mhx1999.top/Article/details/gt2xqblcaoc.html

[Q67] 设置隔离级别
来源：http://dali.9152youxi.cn/Article/details/gt2cybxcztg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.bjfxy.top/Article/details/gt2ipnminnj.html

[Q68] 保存点
来源：http://dali.yj202588.top/Article/details/gt2fkkmfmzz.html

SAVEPOINT sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2pxtmicas.html

ROLLBACK TO sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wueczhvw.html

[Q69] 查看执行计划
来源：http://dali.chenjidiqi.icu/Article/details/gt2hdcxjlul.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ehwqpu.com/Article/details/gt2mwfgtrsn.html

[Q70] 更新统计信息
来源：http://dali.hysaishi.cn/Article/details/gt2ckhfenth.html

ANALYZE TABLE users;
来源：http://dali.yongpay.top/Article/details/gt2uqatatge.html

[Q71] 查看建表语句
来源：http://dali.ydzc1.top/Article/details/gt2vjobzazi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sxryk.cn/Article/details/gt2ypalpilw.html

[Q72] 查看索引
来源：http://dali.jiagoushi.top/Article/details/gt2jiuzjyun.html

SHOW INDEX FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2dikimeze.html

[Q73] 查看表状态
来源：http://dali.birdmap.top/Article/details/gt2xssxdtoa.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ywtoeqbb.html

[Q74] 强制使用索引
来源：http://dali.vqdsnc.cn/Article/details/gt2sfgjijil.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jlsjyb.cn/Article/details/gt2gqrtyvtu.html

[Q75] 日期格式化
来源：http://dali.yuanzhike.top/Article/details/gt2qdtipqre.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gt2rehewwtb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2grgenlam.html

[Q76] 按天统计
来源：http://dali.xuanzx.com/Article/details/gt2lrkluwjd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nwbrower.top/Article/details/gt2ahhbxodd.html

[Q77] 时间加减
来源：http://dali.hongshengwenyu.top/Article/details/gt2omlmxcpp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.0kj1m.cn/Article/details/gt2yvnrbymi.html

[Q78] 当前时间
来源：http://dali.meibo888.top/Article/details/gt2brqyqwnt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangdashe.top/Article/details/gt2sbchbsug.html

[Q79] 字符串拼接
来源：http://dali.fzhhl.top/Article/details/gt2cmezycgt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.haohaochexian.top/Article/details/gt2ucfarnil.html

[Q80] 字符串截取
来源：http://dali.cheryme.top/Article/details/gt2zuxcaapg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2jobmvehy.html

[Q81] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kyybqwyu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2yfknhove.html

[Q82] 字符长度与字节长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2kkyvphph.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2etglilnx.html

[Q83] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gt2mktdbbtp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2ibwyvtcp.html

[Q84] 去除首尾空格
来源：http://dali.quarkkingdee.top/Article/details/gt2doazxpsk.html

SELECT TRIM(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2yumgaqcn.html

[Q85] 数值取整
来源：http://dali.yj202588.top/Article/details/gt2ikzfegkq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenjidiqi.icu/Article/details/gt2uejbomhl.html

[Q86] 读取 JSON 字段
来源：http://dali.smart0.xyz/Article/details/gt2pnlxohqu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.iojbl.cn/Article/details/gt2uxxzfnux.html

[Q87] JSON 字段做条件
来源：http://dali.gogol.net.cn/Article/details/gt2nlttiqzt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangdashe.top/Article/details/gt2joabxmop.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinqigfzy.top/Article/details/gt2csswucbc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.vqdsnc.cn/Article/details/gt2jfavmqng.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj20258.top/Article/details/gt2kczbjsre.html

[Q89] 判断表是否存在
来源：http://dali.haohaochexian.top/Article/details/gt2sbegftfc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ydzc1.top/Article/details/gt2yluwgezf.html

[Q90] 生成序号列
来源：http://dali.ivvv.top/Article/details/gt2qfviazye.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gogol.net.cn/Article/details/gt2xqslpyoh.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2mrxjsniw.html

R. Bash 专题
来源：http://dali.yonumen.top/Article/details/gt2eakyluem.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2qkkkxxwp.html

[R01] shebang 与严格模式
来源：http://dali.gogol.net.cn/Article/details/gt2rwulawzt.html

#!/usr/bin/env bash
来源：http://dali.vqdsnc.cn/Article/details/gt2htetysoy.html

set -euo pipefail
来源：http://dali.mhx1999.top/Article/details/gt2rzbhoroa.html

[R02] 变量赋值与使用
来源：http://dali.yongpay.top/Article/details/gt2zyqdarxx.html

name="Tom"; echo "$name"
来源：http://dali.zhoulong.xyz/Article/details/gt2vzuosqqm.html

[R03] 只读变量
来源：http://dali.wangdashe.top/Article/details/gt2jdrtrlqb.html

readonly PI=3.14
来源：http://dali.316326.xyz/Article/details/gt2yazcarqw.html

[R04] 位置参数
来源：http://dali.aizwys.cn/Article/details/gt2mnzqkefu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tanke756.top/Article/details/gt2ysfonsrf.html

[R05] 参数默认值
来源：http://dali.zycfv.cn/Article/details/gt2tcpjkksx.html

name="${1:-default}"
来源：http://dali.xinyue.icu/Article/details/gt2ciqrrggd.html

[R06] 判断命令是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hgqyrebl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuxming.cn/Article/details/gt2cpgzaeqs.html

[R07] if 判断文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2thfnhxdm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.mhx1999.top/Article/details/gt2cjlajyjn.html

[R08] 数值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wrrlgmuv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zdqjudy.top/Article/details/gt2trhlkhmd.html

[R09] 字符串比较
来源：http://dali.xziqi.cn/Article/details/gt2wrdnqbhq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shzxlz.cn/Article/details/gt2lsnpfrcs.html

[R10] 正则匹配
来源：http://dali.aizwys.cn/Article/details/gt2ldvbdqpq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yvedp.cn/Article/details/gt2hmeunfsc.html

[R11] case 多分支
来源：http://dali.aizwys.cn/Article/details/gt2rawumxce.html

case "$1" in
来源：http://dali.vqdsnc.cn/Article/details/gt2zslgjhcs.html

start) echo "启动" ;;
来源：http://dali.zhongyouzk.top/Article/details/gt2vectkhlx.html

stop)  echo "停止" ;;
来源：http://dali.cucudq.cn/Article/details/gt2pzpssdeh.html

*)     echo "未知命令" ;;
来源：http://dali.vqdsnc.cn/Article/details/gt2jatselmf.html

esac
来源：http://dali.yj20258.top/Article/details/gt2zwexhuau.html

[R12] for 遍历文件
来源：http://dali.sysykeji.top/Article/details/gt2dnhmnkbq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cdnleiting.top/Article/details/gt2jeosxbpc.html

[R13] for 计数循环
来源：http://dali.nanxuanxn.top/Article/details/gt2mhridefq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gt2hknftpqh.html

[R14] C 风格 for
来源：http://dali.jinqigfzy.top/Article/details/gt2izowxnps.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gt2xaccbzog.html

[R15] while 逐行读文件
来源：http://dali.guannengcc.top/Article/details/gt2wnmhfnvs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jyoumei.cn/Article/details/gt2pxyvxvzw.html

[R16] until 等待条件
来源：http://dali.chenzaomai.com/Article/details/gt2crrexwsc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xuanzx.com/Article/details/gt2wowktkey.html

[R17] 数组定义与取值
来源：http://dali.smart0.xyz/Article/details/gt2apqgmlmu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shuidangran.top/Article/details/gt2manomxyv.html

[R18] 遍历数组
来源：http://dali.daria6918.cn/Article/details/gt2hunogylf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daria6918.cn/Article/details/gt2qlilngbz.html

[R19] 数组长度
来源：http://dali.aibaodan.cn/Article/details/gt2qfabogaj.html

echo "${#arr[@]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2taambjbu.html

[R20] 关联数组（字典）
来源：http://dali.chenjidiqi.icu/Article/details/gt2dfrnrtkv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhengqikj.top/Article/details/gt2duaxhovc.html

[R21] 字符串长度
来源：http://dali.gotoacloud.top/Article/details/gt2otachjgu.html

echo "${#s}"
来源：http://dali.tianlin.xyz/Article/details/gt2muxkojoz.html

[R22] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gt2fhwvbfns.html

echo "${s:0:5}"
来源：http://dali.c1oappe.top/Article/details/gt2pfuvsokz.html

[R23] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gt2pkvzzljr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jianghu66.top/Article/details/gt2xqsoynby.html

[R24] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gt2aynlters.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2npaouvry.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhixingplan.top/Article/details/gt2sfottytg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhoulong.xyz/Article/details/gt2yrmsmbrp.html

[R26] 命令替换
来源：http://dali.jinqigfzy.top/Article/details/gt2uhvgjkhi.html

now=$(date +%F); echo "$now"
来源：http://dali.daxiang520.top/Article/details/gt2ncruqanv.html

[R27] 算术展开
来源：http://dali.gotoacloud.top/Article/details/gt2krrbaywt.html

echo $((1 + 2 * 3))
来源：http://dali.hnxiangtu.top/Article/details/gt2jymhoqss.html

[R28] 浮点运算
来源：http://dali.yuanzhike.top/Article/details/gt2kedbgvwb.html

echo "scale=2; 10/3" | bc
来源：http://dali.ybcxt.top/Article/details/gt2vtummdtr.html

[R29] 定义函数
来源：http://dali.shuidangran.top/Article/details/gt2ncrtdfvo.html


<!-- 参考信息 -->