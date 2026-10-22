代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenzaomai.com/Article/details/gt2jlkqfehp.html

TS:   if (x == null) {}
来源：http://dali.sweek.top/Article/details/gt2zzeljlwj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dessmaah.html

Go:   if x == nil {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2mvafoawl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.0kj1m.cn/Article/details/gt2kunpbpkz.html

C#:   if (x is null) {}
来源：http://dali.ybcxt.top/Article/details/gt2enabuhfd.html

[P07] 防抖与节流
来源：http://dali.yanxiufei.cn/Article/details/gt2sahkbcih.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zrkqagyh.html

PHP:  // 手写时间戳比较
来源：http://dali.zhixingplan.top/Article/details/gt2wyqmdbok.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gt2onyewxjc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.birdmap.top/Article/details/gt2lgmjdoxd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hzsbxbir.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj202588.top/Article/details/gt2eluagpbb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xylfe.cn/Article/details/gt2adoggehq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.meibo888.top/Article/details/gt2okbffunw.html

[P08] 处理浮点精度问题
来源：http://dali.tanke756.top/Article/details/gt2wapsrmur.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cheryme.top/Article/details/gt2fnjgpkbt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shuidangran.top/Article/details/gt2nvfvmsks.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xziqi.cn/Article/details/gt2lohxhswx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.havefunace.top/Article/details/gt2obtybhvj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2elotulnw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zycfv.cn/Article/details/gt2firxokwc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.quarkkingdee.top/Article/details/gt2lvznhzlv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zdqjudy.top/Article/details/gt2mxlugizu.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2hnukursa.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ivvv.top/Article/details/gt2peggegna.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2eqtuzwdx.html

[Q01] 创建表
来源：http://dali.havefunace.top/Article/details/gt2zbhxulki.html

CREATE TABLE users (
来源：http://dali.zhiwuduotai.top/Article/details/gt2zaqgblvp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gt2eyrxzemo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gt2kqgekboj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shanyushiyangtech.top/Article/details/gt2apssgzrb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.snrcjt.cn/Article/details/gt2rrymccnv.html

);
来源：http://dali.xuetiantiany.cn/Article/details/gt2wokbgztr.html

[Q02] 创建带外键的表
来源：http://dali.wangdashe.top/Article/details/gt2nfcdfgyy.html

CREATE TABLE orders (
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mkvfdzjp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgfzy.top/Article/details/gt2bzdnqryu.html

user_id INT NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gt2diiyswdo.html

amount DECIMAL(10, 2),
来源：http://dali.meibo888.top/Article/details/gt2sfmtlkvw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shuidangran.top/Article/details/gt2zqmvmbmq.html

);
来源：http://dali.zhengqikj.top/Article/details/gt2gzzpksyh.html

[Q03] 增加列
来源：http://dali.chenjidiqi.icu/Article/details/gt2wxrruyul.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ivvv.top/Article/details/gt2roouehdf.html

[Q04] 修改列类型
来源：http://dali.shuidangran.top/Article/details/gt2wfwsvqbe.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yongpay.top/Article/details/gt2ggpaptqg.html

[Q05] 重命名列
来源：http://dali.sysykeji.top/Article/details/gt2jgvqyryy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenzaomai.com/Article/details/gt2hzlnmftx.html

[Q06] 删除列
来源：http://dali.xuanzx.com/Article/details/gt2wvgawyzk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.quarkkingdee.top/Article/details/gt2pdoyvdht.html

[Q07] 删除表
来源：http://dali.sysykeji.top/Article/details/gt2lfnqttfz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hysaishi.cn/Article/details/gt2currbuuv.html

[Q08] 创建普通索引
来源：http://dali.birdmap.top/Article/details/gt2nurldztw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.iojbl.cn/Article/details/gt2squbjqsm.html

[Q09] 创建唯一索引
来源：http://dali.316326.xyz/Article/details/gt2jkrbppdp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj202588.top/Article/details/gt2tnnphhpc.html

[Q10] 插入单行
来源：http://dali.cheryme.top/Article/details/gt2paykzsvj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yonumen.top/Article/details/gt2htcvmlps.html

[Q11] 一次插入多行
来源：http://dali.feifeiyinyue.top/Article/details/gt2byhoqutc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.andypj.xyz/Article/details/gt2jcyzttiz.html

[Q12] 插入后取自增 ID
来源：http://dali.kuanghao11.cn/Article/details/gt2kykfzhxs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qqdaqegl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhoulong.xyz/Article/details/gt2djkhjdhv.html

[Q13] 忽略重复插入
来源：http://dali.316326.xyz/Article/details/gt2huwgeqvw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cdnleiting.top/Article/details/gt2qkjtcvxx.html

[Q14] 存在则更新（upsert）
来源：http://dali.yonumen.top/Article/details/gt2ktzdcfnj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.feifeiyinyue.top/Article/details/gt2wnixguic.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.dashuyun.cn/Article/details/gt2eqpktlpm.html

[Q15] 查询全部
来源：http://dali.ybcxt.top/Article/details/gt2gcoemevj.html

SELECT * FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2omxixulj.html

[Q16] 查询指定列
来源：http://dali.yonumen.top/Article/details/gt2cdplqzin.html

SELECT id, name FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2jemlxbqb.html

[Q17] 条件查询
来源：http://dali.yongpay.top/Article/details/gt2iulmgaiu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2ustlqusj.html

[Q18] 模糊匹配
来源：http://dali.yj20258888.top/Article/details/gt2fjewjhxq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hfpthk.cn/Article/details/gt2augtvwji.html

[Q19] 范围查询
来源：http://dali.yongpay.top/Article/details/gt2ydyhwkgq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.mhx1999.top/Article/details/gt2uydsofwd.html

[Q20] IN 列表
来源：http://dali.nwbrower.top/Article/details/gt2udeenhih.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2ncxdghjo.html

[Q21] 空值判断
来源：http://dali.jqgufenzy.top/Article/details/gt2razsucyo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenlongwang.top/Article/details/gt2puuhvxhn.html

[Q22] 排序
来源：http://dali.meibo888.top/Article/details/gt2ojcgfgcx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sysykeji.top/Article/details/gt2skyjpbem.html

[Q23] 分页
来源：http://dali.yangfankeji.com/Article/details/gt2jhuxkvbc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hnqzz.top/Article/details/gt2mtnmcwxd.html

[Q24] 去重
来源：http://dali.gotoacloud.top/Article/details/gt2zyqlfqji.html

SELECT DISTINCT city FROM users;
来源：http://dali.hammf.cn/Article/details/gt2hweijvxw.html

[Q25] 只取前 N 条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jbcjqutu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ayzuxdwz.html

[Q26] 计数
来源：http://dali.yuanzhike.top/Article/details/gt2wmybnxhk.html

SELECT COUNT(*) FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2kbsqazyg.html

[Q27] 条件计数
来源：http://dali.chenjidiqi.icu/Article/details/gt2xyhgykyh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2sgygsjjh.html

[Q28] 求和与平均
来源：http://dali.hywenlv.cn/Article/details/gt2gzqcxuoc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gt2qwomoipa.html

[Q29] 最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gt2ewzqpkla.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzemqrlf.html

[Q30] 分组统计
来源：http://dali.sweek.top/Article/details/gt2rfkplsow.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gt2oqumuzsz.html

[Q31] 分组后过滤
来源：http://dali.snrcjt.cn/Article/details/gt2rjfvvvsu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ofonqflt.html

[Q32] 分组拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gt2aomgzjmk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gt2fdbewnyl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.svipenyu.cn/Article/details/gt2rbufxdnp.html

[Q33] 多列分组
来源：http://dali.snrcjt.cn/Article/details/gt2hgynudae.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xylfe.cn/Article/details/gt2jwdjehmq.html

[Q34] 每组取第一条
来源：http://dali.hammf.cn/Article/details/gt2aofnqtpt.html

SELECT * FROM (
来源：http://dali.jiagoushi.top/Article/details/gt2admqxeny.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xuetiantiany.cn/Article/details/gt2zwawvirf.html

) t WHERE rn = 1;
来源：http://dali.zdqjudy.top/Article/details/gt2oblcxqwr.html

[Q35] 内连接
来源：http://dali.xziqi.cn/Article/details/gt2asuovgno.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.pycfn.com/Article/details/gt2oajfuwol.html

[Q36] 左连接
来源：http://dali.shuidangran.top/Article/details/gt2rqwqftej.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gt2gsxaajiy.html

[Q37] 右连接
来源：http://dali.ydzc1.top/Article/details/gt2xtwvgqxf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnxiangtu.top/Article/details/gt2rxvfujcs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.guannengcc.top/Article/details/gt2qvogebif.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.pycfn.com/Article/details/gt2umqmbcde.html

[Q39] 自连接（查上下级）
来源：http://dali.tanke756.top/Article/details/gt2ldzgdoty.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jofgrows.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nwbrower.top/Article/details/gt2qhrlvlrs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.fzhhl.top/Article/details/gt2zcobgztr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zycfv.cn/Article/details/gt2szzxsrmd.html

[Q41] 多表连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gnicqkoy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hongshengwenyu.top/Article/details/gt2ardhqqsz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.9152youxi.cn/Article/details/gt2sfmbwrpo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zycfv.cn/Article/details/gt2tyueqzjj.html

[Q42] 连接条件附加过滤
来源：http://dali.feifeiyinyue.top/Article/details/gt2tvfazlbh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.aizwys.cn/Article/details/gt2henxnrym.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenjidiqi.icu/Article/details/gt2wnlsinvp.html

[Q43] 标量子查询
来源：http://dali.zycfv.cn/Article/details/gt2emxrwsqr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sxryk.cn/Article/details/gt2goshzoid.html

[Q44] IN 子查询
来源：http://dali.yonumen.top/Article/details/gt2nejyqois.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zdqjudy.top/Article/details/gt2cxyheult.html

[Q45] EXISTS 判断存在
来源：http://dali.hywenlv.cn/Article/details/gt2szzuxcqv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.mhx1999.top/Article/details/gt2iwvgizgo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tanke756.top/Article/details/gt2vqxcjhdm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangdashe.top/Article/details/gt2ixrunrpl.html

[Q47] 与平均值比较
来源：http://dali.cashguo.top/Article/details/gt2zmtesuuh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhoulong.xyz/Article/details/gt2fcnreqpa.html

[Q48] CTE 公用表表达式
来源：http://dali.cheryme.top/Article/details/gt2ghxubhtp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.daria6918.cn/Article/details/gt2xuaubdhx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.guannengcc.top/Article/details/gt2dvcacina.html

[Q49] 更新单行
来源：http://dali.hnxiangtu.top/Article/details/gt2gmzkmycg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgfzy.top/Article/details/gt2zbraaemq.html

[Q50] 批量更新
来源：http://dali.aizwys.cn/Article/details/gt2woaozxth.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenjidiqi.icu/Article/details/gt2smdshecj.html

[Q51] 用子查询更新
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqfxamsp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.c1oappe.top/Article/details/gt2hwrcdwhg.html

[Q52] 删除指定行
来源：http://dali.jinqigfzy.top/Article/details/gt2sbzyzrth.html

DELETE FROM users WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gt2vdomvxuh.html

[Q53] 按条件删除
来源：http://dali.fzhhl.top/Article/details/gt2qbuqzylw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.haohaochexian.top/Article/details/gt2djrmlvaz.html

[Q54] 清空表
来源：http://dali.shzxlz.cn/Article/details/gt2lfdcdvms.html

TRUNCATE TABLE logs;
来源：http://dali.yueranfly.top/Article/details/gt2ebannqwe.html

[Q55] 排名（并列占位）
来源：http://dali.sxryk.cn/Article/details/gt2ejdfvzmb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.redwolf501.top/Article/details/gt2yclqszkq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tanke756.top/Article/details/gt2fhxmjrsl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zycfv.cn/Article/details/gt2ngojacvd.html

[Q57] 行号
来源：http://dali.iojbl.cn/Article/details/gt2aqufzlro.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cashguo.top/Article/details/gt2ylrjposh.html

[Q58] 累计求和
来源：http://dali.gaohongyu789.top/Article/details/gt2jcygzukh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gt2ybsrnphw.html

[Q59] 分组内累计
来源：http://dali.yangfankeji.com/Article/details/gt2jbkvgrki.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj20258.top/Article/details/gt2eokdawwv.html

[Q60] 取上一行 / 下一行
来源：http://dali.wangshuangyany.cn/Article/details/gt2fdjwebjm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.quarkkingdee.top/Article/details/gt2ezdgpppe.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2kxbmmmps.html

[Q61] 移动平均
来源：http://dali.svipenyu.cn/Article/details/gt2gbttqabo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2lxtijmgs.html

[Q62] 分组占比
来源：http://dali.quarkkingdee.top/Article/details/gt2axduvukf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gt2aimlchfc.html

[Q63] 开启事务
来源：http://dali.jinqigfzy.top/Article/details/gt2pqbqjzqe.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenjidiqi.icu/Article/details/gt2yddmfixl.html

[Q64] 提交事务
来源：http://dali.havefunace.top/Article/details/gt2dtopcoxr.html

COMMIT;
来源：http://dali.cashguo.top/Article/details/gt2bdyvevsi.html

[Q65] 回滚事务
来源：http://dali.jqgufenzy.top/Article/details/gt2qnlwliwl.html

ROLLBACK;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ewapgkpf.html

[Q66] 行锁查询
来源：http://dali.hfpthk.cn/Article/details/gt2groczwql.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj202588.top/Article/details/gt2mzqhxqor.html

[Q67] 设置隔离级别
来源：http://dali.yanxiufei.cn/Article/details/gt2kgrjcidc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.0kj1m.cn/Article/details/gt2jsfxmhkv.html

[Q68] 保存点
来源：http://dali.ppjwa.cn/Article/details/gt2xfxycqqz.html

SAVEPOINT sp1;
来源：http://dali.jinqigfzy.top/Article/details/gt2fouxjchb.html

ROLLBACK TO sp1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cklskmth.html

[Q69] 查看执行计划
来源：http://dali.nanxuanxn.top/Article/details/gt2gzxroauq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.havefunace.top/Article/details/gt2yvjbolpj.html

[Q70] 更新统计信息
来源：http://dali.nanxinkj.top/Article/details/gt2ipbzwnyj.html

ANALYZE TABLE users;
来源：http://dali.vqdsnc.cn/Article/details/gt2tatkypbh.html

[Q71] 查看建表语句
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jkzudfqm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.feifeiyinyue.top/Article/details/gt2zncorexn.html

[Q72] 查看索引
来源：http://dali.andypj.xyz/Article/details/gt2tybqangb.html

SHOW INDEX FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2oputqtkf.html

[Q73] 查看表状态
来源：http://dali.gaohongyu789.top/Article/details/gt2xsyiaofk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shangyingyoupin.top/Article/details/gt2vghbgjpt.html

[Q74] 强制使用索引
来源：http://dali.c1oappe.top/Article/details/gt2zhyfdiqj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj20258888.top/Article/details/gt2yehnzfep.html

[Q75] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gt2jtkzbqvv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2atvvhocw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhengqikj.top/Article/details/gt2svptzpdw.html

[Q76] 按天统计
来源：http://dali.c1oappe.top/Article/details/gt2mdgudafi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dianchejie.cn/Article/details/gt2grvrgrmu.html

[Q77] 时间加减
来源：http://dali.cucudq.cn/Article/details/gt2crhlhifv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cheryme.top/Article/details/gt2vvtkgxpi.html

[Q78] 当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ryqjqmyr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xziqi.cn/Article/details/gt2qjbzqyqz.html

[Q79] 字符串拼接
来源：http://dali.jinqigufen.top/Article/details/gt2sivnqlhc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pycfn.com/Article/details/gt2bboquaqm.html

[Q80] 字符串截取
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ublpstnu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2iuvfwwvv.html

[Q81] 字符串替换
来源：http://dali.ppjwa.cn/Article/details/gt2ljpxaybz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2gsohpyrt.html

[Q82] 字符长度与字节长度
来源：http://dali.c1oappe.top/Article/details/gt2vngtchnf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lyxyfzie.html

[Q83] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gt2jnzhides.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2mclygari.html

[Q84] 去除首尾空格
来源：http://dali.chenjidiqi.icu/Article/details/gt2wddhksjz.html

SELECT TRIM(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2vmqzlnkc.html

[Q85] 数值取整
来源：http://dali.xziqi.cn/Article/details/gt2oxzfpbvb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj20258888.top/Article/details/gt2drtaiyjz.html

[Q86] 读取 JSON 字段
来源：http://dali.jiagoushi.top/Article/details/gt2lqooxzcf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hammf.cn/Article/details/gt2rkamzzgp.html

[Q87] JSON 字段做条件
来源：http://dali.xziqi.cn/Article/details/gt2ddqnokcn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.feifeiyinyue.top/Article/details/gt2jtobwqpt.html

[Q88] 行转列（条件聚合）
来源：http://dali.sufxvd.cn/Article/details/gt2ckzsvdve.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qwfnipxh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj20258.top/Article/details/gt2arvlnhsz.html

[Q89] 判断表是否存在
来源：http://dali.jinqigufen.top/Article/details/gt2pxrbfwte.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.0kj1m.cn/Article/details/gt2dttfslep.html

[Q90] 生成序号列
来源：http://dali.jiagoushi.top/Article/details/gt2bltybopf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jianghu66.top/Article/details/gt2npztpcdh.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2vriankqy.html

R. Bash 专题
来源：http://dali.haohaochexian.top/Article/details/gt2wqqfwqgc.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2euhmcojt.html

[R01] shebang 与严格模式
来源：http://dali.nanxinkj.top/Article/details/gt2zpeulxuh.html

#!/usr/bin/env bash
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dtyxztbh.html

set -euo pipefail
来源：http://dali.jqgufenzy.top/Article/details/gt2abnopqnr.html

[R02] 变量赋值与使用
来源：http://dali.zhiwuduotai.top/Article/details/gt2tjbbupzd.html

name="Tom"; echo "$name"
来源：http://dali.zhengqikj.top/Article/details/gt2qywarmfv.html

[R03] 只读变量
来源：http://dali.nanxinkj.top/Article/details/gt2mlkrdtqy.html

readonly PI=3.14
来源：http://dali.redwolf501.top/Article/details/gt2ccazyuuz.html

[R04] 位置参数
来源：http://dali.bjfxy.top/Article/details/gt2wnymqzit.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gogol.net.cn/Article/details/gt2mtzbosjj.html

[R05] 参数默认值
来源：http://dali.yongpay.top/Article/details/gt2etsyzcba.html

name="${1:-default}"
来源：http://dali.hnqzz.top/Article/details/gt2eibbgjnd.html

[R06] 判断命令是否存在
来源：http://dali.yangfankeji.com/Article/details/gt2xvwqmwzh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ydzc1.top/Article/details/gt2rzrtuplh.html

[R07] if 判断文件
来源：http://dali.aizwys.cn/Article/details/gt2hrfhybjr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sufxvd.cn/Article/details/gt2usweoqkf.html

[R08] 数值比较
来源：http://dali.cheryme.top/Article/details/gt2ingxoedn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yuxming.cn/Article/details/gt2awpmywwv.html

[R09] 字符串比较
来源：http://dali.ydzc1.top/Article/details/gt2ktghgbqh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yueranfly.top/Article/details/gt2irjwkaox.html

[R10] 正则匹配
来源：http://dali.shzxlz.cn/Article/details/gt2bjxhvhtq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhongyouzk.top/Article/details/gt2radllbxa.html

[R11] case 多分支
来源：http://dali.xinyue.icu/Article/details/gt2ozvejhqz.html

case "$1" in
来源：http://dali.cdnleiting.top/Article/details/gt2mopalasg.html

start) echo "启动" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vuwkksqt.html

stop)  echo "停止" ;;
来源：http://dali.sufxvd.cn/Article/details/gt2yzbncgzk.html

*)     echo "未知命令" ;;
来源：http://dali.quarkkingdee.top/Article/details/gt2mrwlswuj.html

esac
来源：http://dali.zhoulong.xyz/Article/details/gt2xiqkvurk.html

[R12] for 遍历文件
来源：http://dali.chenlongwang.top/Article/details/gt2hzxrfzow.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yueranfly.top/Article/details/gt2jmzbxcpt.html

[R13] for 计数循环
来源：http://dali.ivvv.top/Article/details/gt2cqwknpbm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gt2oqghrpgw.html

[R14] C 风格 for
来源：http://dali.hammf.cn/Article/details/gt2zrkbnqwr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gt2fqfderxw.html

[R15] while 逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gt2fptbvzax.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.dianchejie.cn/Article/details/gt2wceakuot.html

[R16] until 等待条件
来源：http://dali.havefunace.top/Article/details/gt2babzteas.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gt2ibvomedh.html

[R17] 数组定义与取值
来源：http://dali.hfpthk.cn/Article/details/gt2iqirjepz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xziqi.cn/Article/details/gt2frmuivtj.html

[R18] 遍历数组
来源：http://dali.pycfn.com/Article/details/gt2qciupjpe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxuanxn.top/Article/details/gt2gqlxhtxc.html

[R19] 数组长度
来源：http://dali.cheryme.top/Article/details/gt2vsbmqfmc.html

echo "${#arr[@]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2opiamiep.html

[R20] 关联数组（字典）
来源：http://dali.chenjidiqi.icu/Article/details/gt2omhhxhvz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tanke756.top/Article/details/gt2zyizdavx.html

[R21] 字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gt2loasfila.html

echo "${#s}"
来源：http://dali.havefunace.top/Article/details/gt2tzotswpz.html

[R22] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gt2xmafkjxd.html

echo "${s:0:5}"
来源：http://dali.ybcxt.top/Article/details/gt2chirolkt.html

[R23] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gt2ybtvozux.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2olpgryzb.html

[R24] 大小写转换
来源：http://dali.aizwys.cn/Article/details/gt2mgjhthme.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.vqdsnc.cn/Article/details/gt2uxubtbst.html

[R25] 去后缀 / 去前缀
来源：http://dali.quarkkingdee.top/Article/details/gt2ysskbtpx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.316326.xyz/Article/details/gt2ekuphcxx.html

[R26] 命令替换
来源：http://dali.jyoumei.cn/Article/details/gt2ctztjijw.html

now=$(date +%F); echo "$now"
来源：http://dali.xylfe.cn/Article/details/gt2xeyuwmeq.html

[R27] 算术展开
来源：http://dali.hongshengwenyu.top/Article/details/gt2spzytljk.html

echo $((1 + 2 * 3))
来源：http://dali.jqgfzy.top/Article/details/gt2wlrqlrhu.html

[R28] 浮点运算
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xriwgovl.html

echo "scale=2; 10/3" | bc
来源：http://dali.jyoumei.cn/Article/details/gt2xzowpbxy.html

[R29] 定义函数
来源：http://dali.tianlin.xyz/Article/details/gt2tmwqvauo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yvedp.cn/Article/details/gt2hscbdyfz.html

[R30] 函数返回状态码
来源：http://dali.feifeiyinyue.top/Article/details/gt2cbjjvnct.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shzxlz.cn/Article/details/gt2xtldndpe.html

[R31] 局部变量
来源：http://dali.mhx1999.top/Article/details/gt2qoqgmhov.html


<!-- 参考信息 -->