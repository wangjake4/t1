代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2msojfqwn.html

TS:   if (x == null) {}
来源：http://dali.nanxinkj.top/Article/details/gt2dwjhmcpk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cashguo.top/Article/details/gt2epwiubau.html

Go:   if x == nil {}
来源：http://dali.c1oappe.top/Article/details/gt2ygbwqemo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jqgufenzy.top/Article/details/gt2jpwcreas.html

C#:   if (x is null) {}
来源：http://dali.tian-w.cn/Article/details/gt2cabthcze.html

[P07] 防抖与节流
来源：http://dali.zhongyouzk.top/Article/details/gt2lkcfinfl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jqgfzy.top/Article/details/gt2irydimbt.html

PHP:  // 手写时间戳比较
来源：http://dali.xziqi.cn/Article/details/gt2oyvomhhz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gt2hzekxscy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gt2qvmotkce.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2ebhlzhfa.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hnxiangtu.top/Article/details/gt2ohllnauh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj20258.top/Article/details/gt2ocdepjdl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eonlolgb.html

[P08] 处理浮点精度问题
来源：http://dali.tian-w.cn/Article/details/gt2bycvkrhw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xylfe.cn/Article/details/gt2dpwvyqso.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2inbktjbc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.daria6918.cn/Article/details/gt2qmmnbpkz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.aibaodan.cn/Article/details/gt2kadatgob.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.dianchejie.cn/Article/details/gt2cgavkgzm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shangyingyoupin.top/Article/details/gt2pgxnvskt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cheryme.top/Article/details/gt2topbndjg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenlongwang.top/Article/details/gt2nzgqwyha.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2qhxuexpm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yueranfly.top/Article/details/gt2nzldhvzj.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2hbiyarlg.html

[Q01] 创建表
来源：http://dali.havefunace.top/Article/details/gt2fockdrmo.html

CREATE TABLE users (
来源：http://dali.ydzc1.top/Article/details/gt2xbgnywhg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxuanxn.top/Article/details/gt2qpkhdrfl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yfgkbvoe.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ivvv.top/Article/details/gt2wysfqius.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cashguo.top/Article/details/gt2awazbxsz.html

);
来源：http://dali.tianlin.xyz/Article/details/gt2htdwlzyi.html

[Q02] 创建带外键的表
来源：http://dali.sxryk.cn/Article/details/gt2tvaomufb.html

CREATE TABLE orders (
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qszncsvc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tanke756.top/Article/details/gt2wuutfyav.html

user_id INT NOT NULL,
来源：http://dali.yonumen.top/Article/details/gt2rrhdvjwr.html

amount DECIMAL(10, 2),
来源：http://dali.gaohongyu789.top/Article/details/gt2hjgcybfl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hywenlv.cn/Article/details/gt2rwdazcws.html

);
来源：http://dali.zhoulong.xyz/Article/details/gt2sfstdqiw.html

[Q03] 增加列
来源：http://dali.yueranfly.top/Article/details/gt2blysjoub.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xinyue.icu/Article/details/gt2ggvvpzoh.html

[Q04] 修改列类型
来源：http://dali.316326.xyz/Article/details/gt2tzwnjvxr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnqzz.top/Article/details/gt2rhpypnot.html

[Q05] 重命名列
来源：http://dali.sysykeji.top/Article/details/gt2hbxqcosd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhengqikj.top/Article/details/gt2lrgrhkow.html

[Q06] 删除列
来源：http://dali.0kj1m.cn/Article/details/gt2tptwodkr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenzaomai.com/Article/details/gt2niafpiez.html

[Q07] 删除表
来源：http://dali.ybcxt.top/Article/details/gt2ibvjltdl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.0kj1m.cn/Article/details/gt2xwwpdotg.html

[Q08] 创建普通索引
来源：http://dali.haohaochexian.top/Article/details/gt2xkcncrux.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gt2fnmwcvfj.html

[Q09] 创建唯一索引
来源：http://dali.hammf.cn/Article/details/gt2mtotofld.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yvedp.cn/Article/details/gt2nbcmnxjm.html

[Q10] 插入单行
来源：http://dali.aibaodan.cn/Article/details/gt2gcsktnly.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gzhubu.top/Article/details/gt2lfcnvmzm.html

[Q11] 一次插入多行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nyzbonkp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yangfankeji.com/Article/details/gt2izncshow.html

[Q12] 插入后取自增 ID
来源：http://dali.zycfv.cn/Article/details/gt2lxsoxxer.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.feifeiyinyue.top/Article/details/gt2brgayzoy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nanxuanxn.top/Article/details/gt2cdunrmrj.html

[Q13] 忽略重复插入
来源：http://dali.zhongyouzk.top/Article/details/gt2tffyrfzm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gt2oeqfxtoi.html

[Q14] 存在则更新（upsert）
来源：http://dali.sxryk.cn/Article/details/gt2nvmmaghc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jtrnmenp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.316326.xyz/Article/details/gt2rpwqdqny.html

[Q15] 查询全部
来源：http://dali.sxryk.cn/Article/details/gt2sbxnunij.html

SELECT * FROM users;
来源：http://dali.pycfn.com/Article/details/gt2qzulolfv.html

[Q16] 查询指定列
来源：http://dali.yj202588.top/Article/details/gt2ltaouhko.html

SELECT id, name FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2gliartsc.html

[Q17] 条件查询
来源：http://dali.fengsongda.top/Article/details/gt2peqsrctz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2vpbafomj.html

[Q18] 模糊匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2fsefymja.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.pengpengdd.cyou/Article/details/gt2frukwnnj.html

[Q19] 范围查询
来源：http://dali.guowangkeji.top/Article/details/gt2azqkmrat.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cdnleiting.top/Article/details/gt2wobjrpyi.html

[Q20] IN 列表
来源：http://dali.316326.xyz/Article/details/gt2lfuijhwm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yueranfly.top/Article/details/gt2uxcrccxu.html

[Q21] 空值判断
来源：http://dali.9152youxi.cn/Article/details/gt2qmmqmsjj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.redwolf501.top/Article/details/gt2loqqzcuf.html

[Q22] 排序
来源：http://dali.chenjidiqi.icu/Article/details/gt2daygxazq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sufxvd.cn/Article/details/gt2nlotpomt.html

[Q23] 分页
来源：http://dali.gotoacloud.top/Article/details/gt2fpdgwhev.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.snrcjt.cn/Article/details/gt2qcukcjxi.html

[Q24] 去重
来源：http://dali.pycfn.com/Article/details/gt2nrbdiyjj.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2hsyblzqc.html

[Q25] 只取前 N 条
来源：http://dali.redwolf501.top/Article/details/gt2aotptsrr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vdeturgp.html

[Q26] 计数
来源：http://dali.bjfxy.top/Article/details/gt2qpbjxlai.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2hkcdzfnr.html

[Q27] 条件计数
来源：http://dali.chenzaomai.com/Article/details/gt2mtrurwku.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2wkijgpoc.html

[Q28] 求和与平均
来源：http://dali.chenlongwang.top/Article/details/gt2nfbiouvu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kguirhwg.html

[Q29] 最大最小值
来源：http://dali.smart0.xyz/Article/details/gt2pgavdfyj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2imbovtwh.html

[Q30] 分组统计
来源：http://dali.fengsongda.top/Article/details/gt2lwdnumyd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gt2oyghxrxj.html

[Q31] 分组后过滤
来源：http://dali.yuanzhike.top/Article/details/gt2irdfqvss.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.fengsongda.top/Article/details/gt2uzmtsurf.html

[Q32] 分组拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gt2kszodwtx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gt2aihbyqfy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ybcxt.top/Article/details/gt2gpovsjhk.html

[Q33] 多列分组
来源：http://dali.gogol.net.cn/Article/details/gt2erkaecgh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zycfv.cn/Article/details/gt2pflbftsb.html

[Q34] 每组取第一条
来源：http://dali.smart0.xyz/Article/details/gt2naddljfi.html

SELECT * FROM (
来源：http://dali.sufxvd.cn/Article/details/gt2quosasly.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.vqdsnc.cn/Article/details/gt2jtwptdox.html

) t WHERE rn = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2amvlxuix.html

[Q35] 内连接
来源：http://dali.sweek.top/Article/details/gt2qamlruyy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gt2tsbkqzxv.html

[Q36] 左连接
来源：http://dali.wangdashe.top/Article/details/gt2eikywfgu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cdnleiting.top/Article/details/gt2akxmszyf.html

[Q37] 右连接
来源：http://dali.0kj1m.cn/Article/details/gt2imwacjlv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jiagoushi.top/Article/details/gt2mfsdefrq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cucudq.cn/Article/details/gt2xnahajzk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sxryk.cn/Article/details/gt2ulxrzrhr.html

[Q39] 自连接（查上下级）
来源：http://dali.tianlin.xyz/Article/details/gt2uxhntllf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuxming.cn/Article/details/gt2pnppkokn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenlongwang.top/Article/details/gt2bmfgqrhi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sufxvd.cn/Article/details/gt2uisqyail.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.birdmap.top/Article/details/gt2zlblkbhi.html

[Q41] 多表连接
来源：http://dali.ppjwa.cn/Article/details/gt2zmkijpjn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shangyingyoupin.top/Article/details/gt2hdqfgqrd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ybcxt.top/Article/details/gt2ilocgstb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj202588.top/Article/details/gt2lrqyzxqn.html

[Q42] 连接条件附加过滤
来源：http://dali.chenjidiqi.icu/Article/details/gt2nhxxdsnx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ehwqpu.com/Article/details/gt2cihbqcql.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhengqikj.top/Article/details/gt2egwgazpw.html

[Q43] 标量子查询
来源：http://dali.xuanzx.com/Article/details/gt2hwlnazdl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jiagoushi.top/Article/details/gt2ncsjxuln.html

[Q44] IN 子查询
来源：http://dali.guannengcc.top/Article/details/gt2hhkmawiz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlbkgia.html

[Q45] EXISTS 判断存在
来源：http://dali.xinyue.icu/Article/details/gt2zkpnnmwe.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guowangkeji.top/Article/details/gt2jmcwjqdu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ojfrsemp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shangyingyoupin.top/Article/details/gt2txwaoiqn.html

[Q47] 与平均值比较
来源：http://dali.sufxvd.cn/Article/details/gt2wivosomm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xinyue.icu/Article/details/gt2joopyfls.html

[Q48] CTE 公用表表达式
来源：http://dali.yueranfly.top/Article/details/gt2lbouddug.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuanzhike.top/Article/details/gt2orohdbnz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.guannengcc.top/Article/details/gt2xjfbfbdu.html

[Q49] 更新单行
来源：http://dali.snrcjt.cn/Article/details/gt2nlrxatbi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gt2avlcxjls.html

[Q50] 批量更新
来源：http://dali.chenjidiqi.icu/Article/details/gt2eivrarwg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xylfe.cn/Article/details/gt2qreonbrw.html

[Q51] 用子查询更新
来源：http://dali.quarkkingdee.top/Article/details/gt2xjjkhhkk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2szptnank.html

[Q52] 删除指定行
来源：http://dali.andypj.xyz/Article/details/gt2qfsacvir.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gotoacloud.top/Article/details/gt2uylzipbd.html

[Q53] 按条件删除
来源：http://dali.shzxlz.cn/Article/details/gt2srfrtqry.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xuetiantiany.cn/Article/details/gt2xomsncgo.html

[Q54] 清空表
来源：http://dali.jinqigfzy.top/Article/details/gt2iqkgscqb.html

TRUNCATE TABLE logs;
来源：http://dali.yuanzhike.top/Article/details/gt2sntpacrf.html

[Q55] 排名（并列占位）
来源：http://dali.redwolf501.top/Article/details/gt2lbxnjxlp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj202588.top/Article/details/gt2ydcmjdak.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2skhpjkar.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.dashuyun.cn/Article/details/gt2jlakuqkk.html

[Q57] 行号
来源：http://dali.ppjwa.cn/Article/details/gt2aqrezsnc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2xxdhplyf.html

[Q58] 累计求和
来源：http://dali.meibo888.top/Article/details/gt2mzlmdjhu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.316326.xyz/Article/details/gt2sxutgrjr.html

[Q59] 分组内累计
来源：http://dali.birdmap.top/Article/details/gt2avsejqym.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2vjskdnpe.html

[Q60] 取上一行 / 下一行
来源：http://dali.snrcjt.cn/Article/details/gt2mwxgcaff.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.haohaochexian.top/Article/details/gt2zuuntrrp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2jdgxtelp.html

[Q61] 移动平均
来源：http://dali.vqdsnc.cn/Article/details/gt2xwlspjog.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2flirflgc.html

[Q62] 分组占比
来源：http://dali.chenjidiqi.icu/Article/details/gt2dgyslmrs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gt2czppysly.html

[Q63] 开启事务
来源：http://dali.hammf.cn/Article/details/gt2dikbpygr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.guowangkeji.top/Article/details/gt2ggnwnnft.html

[Q64] 提交事务
来源：http://dali.chenlongwang.top/Article/details/gt2ubrvbndt.html

COMMIT;
来源：http://dali.yangfankeji.com/Article/details/gt2bpvdfgzu.html

[Q65] 回滚事务
来源：http://dali.snrcjt.cn/Article/details/gt2zdtbqgzk.html

ROLLBACK;
来源：http://dali.cucudq.cn/Article/details/gt2ajutuwzn.html

[Q66] 行锁查询
来源：http://dali.iojbl.cn/Article/details/gt2eflcluto.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.snrcjt.cn/Article/details/gt2zulanfer.html

[Q67] 设置隔离级别
来源：http://dali.zhoulong.xyz/Article/details/gt2ykrsfujl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gotoacloud.top/Article/details/gt2nkaudjny.html

[Q68] 保存点
来源：http://dali.yuxming.cn/Article/details/gt2rauviboo.html

SAVEPOINT sp1;
来源：http://dali.guowangkeji.top/Article/details/gt2asvbbgkm.html

ROLLBACK TO sp1;
来源：http://dali.nwbrower.top/Article/details/gt2khzqpemb.html

[Q69] 查看执行计划
来源：http://dali.nanxinkj.top/Article/details/gt2plnyilkr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hywenlv.cn/Article/details/gt2xzpsidlj.html

[Q70] 更新统计信息
来源：http://dali.ehwqpu.com/Article/details/gt2ununaigi.html

ANALYZE TABLE users;
来源：http://dali.yj20258.top/Article/details/gt2qzvrxpql.html

[Q71] 查看建表语句
来源：http://dali.zhiwuduotai.top/Article/details/gt2cfilyvlz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daxiang520.top/Article/details/gt2wnywidgy.html

[Q72] 查看索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ezroxkfg.html

SHOW INDEX FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2cijozchy.html

[Q73] 查看表状态
来源：http://dali.ydzc1.top/Article/details/gt2mbhkkhsn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.9152youxi.cn/Article/details/gt2lmeflajl.html

[Q74] 强制使用索引
来源：http://dali.jlsjyb.cn/Article/details/gt2vqpzvwsr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.meibo888.top/Article/details/gt2hxiegtjp.html

[Q75] 日期格式化
来源：http://dali.0kj1m.cn/Article/details/gt2muoearph.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2osaluovw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhiwuduotai.top/Article/details/gt2tmhgltod.html

[Q76] 按天统计
来源：http://dali.jinqigufen.top/Article/details/gt2ltomfcse.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jqgfzy.top/Article/details/gt2qjquoetm.html

[Q77] 时间加减
来源：http://dali.hnqzz.top/Article/details/gt2kqpcstbv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.redwolf501.top/Article/details/gt2eskpqafz.html

[Q78] 当前时间
来源：http://dali.shangyingyoupin.top/Article/details/gt2axfoqbxh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hysaishi.cn/Article/details/gt2kjaadmdn.html

[Q79] 字符串拼接
来源：http://dali.daria6918.cn/Article/details/gt2bqgncozd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ppjwa.cn/Article/details/gt2pmuybgcn.html

[Q80] 字符串截取
来源：http://dali.sweek.top/Article/details/gt2bqrctbxo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2pcapamxz.html

[Q81] 字符串替换
来源：http://dali.havefunace.top/Article/details/gt2baquoscb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2aizfgopa.html

[Q82] 字符长度与字节长度
来源：http://dali.hammf.cn/Article/details/gt2bwncqrjs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2ttkquoym.html

[Q83] 大小写转换
来源：http://dali.yj20258.top/Article/details/gt2cllxfjil.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2gixzskzn.html

[Q84] 去除首尾空格
来源：http://dali.tian-w.cn/Article/details/gt2gjmskxbo.html

SELECT TRIM(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2zzbclblo.html

[Q85] 数值取整
来源：http://dali.smart0.xyz/Article/details/gt2dqsnmjam.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.316326.xyz/Article/details/gt2rdsqeimq.html

[Q86] 读取 JSON 字段
来源：http://dali.yanxiufei.cn/Article/details/gt2hnbvriul.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wwhjhvmz.html

[Q87] JSON 字段做条件
来源：http://dali.sysykeji.top/Article/details/gt2eojvkqkq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jqgufenzy.top/Article/details/gt2iklkklqk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zdqjudy.top/Article/details/gt2modmvryb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.haohaochexian.top/Article/details/gt2gzzvswvb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2gxitaped.html

[Q89] 判断表是否存在
来源：http://dali.jlsjyb.cn/Article/details/gt2xkvogsol.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hongshengwenyu.top/Article/details/gt2gewjquzn.html

[Q90] 生成序号列
来源：http://dali.hnqzz.top/Article/details/gt2hvrtyrzy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tanke756.top/Article/details/gt2bxcdyosy.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2pcihantj.html

R. Bash 专题
来源：http://dali.yongpay.top/Article/details/gt2nmlgcsui.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2ywszbtmx.html

[R01] shebang 与严格模式
来源：http://dali.zhengqikj.top/Article/details/gt2mqlzzjyk.html

#!/usr/bin/env bash
来源：http://dali.mhx1999.top/Article/details/gt2darjxiky.html

set -euo pipefail
来源：http://dali.aizwys.cn/Article/details/gt2ppdwaonn.html

[R02] 变量赋值与使用
来源：http://dali.nwbrower.top/Article/details/gt2ngwsfuwm.html

name="Tom"; echo "$name"
来源：http://dali.bjfxy.top/Article/details/gt2bfrlnyrq.html

[R03] 只读变量
来源：http://dali.guannengcc.top/Article/details/gt2amqpquch.html

readonly PI=3.14
来源：http://dali.cashguo.top/Article/details/gt2yuqfcsaz.html

[R04] 位置参数
来源：http://dali.ehwqpu.com/Article/details/gt2armiqksy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hongshengwenyu.top/Article/details/gt2fcoytnat.html

[R05] 参数默认值
来源：http://dali.yj20258.top/Article/details/gt2zeyjfsgo.html

name="${1:-default}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2nrzsmpgm.html

[R06] 判断命令是否存在
来源：http://dali.ybcxt.top/Article/details/gt2elojxauj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gt2geppqfle.html

[R07] if 判断文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vipkadmg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gogol.net.cn/Article/details/gt2sircikqr.html

[R08] 数值比较
来源：http://dali.guowangkeji.top/Article/details/gt2qqzcjnad.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yongpay.top/Article/details/gt2omtrogyc.html

[R09] 字符串比较
来源：http://dali.sysykeji.top/Article/details/gt2muitdcqs.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.kuanghao11.cn/Article/details/gt2tzhhjtnz.html

[R10] 正则匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2znwprbsr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenlongwang.top/Article/details/gt2vcxjxhoc.html

[R11] case 多分支
来源：http://dali.fengsongda.top/Article/details/gt2inycpbkd.html

case "$1" in
来源：http://dali.yongpay.top/Article/details/gt2cfotluuv.html

start) echo "启动" ;;
来源：http://dali.zdqjudy.top/Article/details/gt2ynixlauz.html

stop)  echo "停止" ;;
来源：http://dali.cheryme.top/Article/details/gt2wujqanwr.html

*)     echo "未知命令" ;;
来源：http://dali.shzxlz.cn/Article/details/gt2ecnlmjvl.html

esac
来源：http://dali.cucudq.cn/Article/details/gt2uvwpjmhm.html

[R12] for 遍历文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cgtoieis.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hnxiangtu.top/Article/details/gt2eurdighn.html

[R13] for 计数循环
来源：http://dali.jiagoushi.top/Article/details/gt2uiqolhan.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gt2vnxxgzbw.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvcmtor.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cdnleiting.top/Article/details/gt2ccxumkyn.html

[R15] while 逐行读文件
来源：http://dali.fengsongda.top/Article/details/gt2vdvydadn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2gkfnktbk.html

[R16] until 等待条件
来源：http://dali.chenzaomai.com/Article/details/gt2jtwzyqje.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gt2swxqfpig.html

[R17] 数组定义与取值
来源：http://dali.sufxvd.cn/Article/details/gt2czqznkcy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nujyrnif.html

[R18] 遍历数组
来源：http://dali.svipenyu.cn/Article/details/gt2ikjskjlq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2eypofhoi.html

[R19] 数组长度
来源：http://dali.0kj1m.cn/Article/details/gt2bhzqqgii.html

echo "${#arr[@]}"
来源：http://dali.sxryk.cn/Article/details/gt2hbxgsgrm.html

[R20] 关联数组（字典）
来源：http://dali.guowangkeji.top/Article/details/gt2ftcfvjvy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xuanzx.com/Article/details/gt2cwmimmkm.html

[R21] 字符串长度
来源：http://dali.sufxvd.cn/Article/details/gt2fttbovjo.html

echo "${#s}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cjoknkiw.html

[R22] 截取子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ztpfgoys.html

echo "${s:0:5}"
来源：http://dali.yj202588.top/Article/details/gt2abctyckb.html

[R23] 字符串替换
来源：http://dali.jlsjyb.cn/Article/details/gt2ukgdiyhp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2fpvkyvti.html

[R24] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gt2qadkvarq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenlongwang.top/Article/details/gt2oobcpvkb.html

[R25] 去后缀 / 去前缀
来源：http://dali.haohaochexian.top/Article/details/gt2xpcvpclj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nanxuanxn.top/Article/details/gt2gaoubohb.html

[R26] 命令替换
来源：http://dali.sxryk.cn/Article/details/gt2fgskfctm.html

now=$(date +%F); echo "$now"
来源：http://dali.birdmap.top/Article/details/gt2wckpejzw.html

[R27] 算术展开
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bnltebar.html

echo $((1 + 2 * 3))
来源：http://dali.chenlongwang.top/Article/details/gt2dpqndkzl.html

[R28] 浮点运算
来源：http://dali.cashguo.top/Article/details/gt2pgfzqqzt.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuanzx.com/Article/details/gt2zxpuwrjm.html

[R29] 定义函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xkzjrsli.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yvedp.cn/Article/details/gt2iqnuxbcm.html

[R30] 函数返回状态码
来源：http://dali.jyoumei.cn/Article/details/gt2rxblljsd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tianlin.xyz/Article/details/gt2twrcewwe.html

[R31] 局部变量
来源：http://dali.zhengqikj.top/Article/details/gt2hdpftbad.html


<!-- 参考信息 -->