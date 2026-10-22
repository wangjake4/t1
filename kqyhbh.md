代发 wailian999

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vfseqrbi.html

C#:   if (x is null) {}
来源：http://dali.cucudq.cn/Article/details/gt2ptarunzy.html

[P07] 防抖与节流
来源：http://dali.cheryme.top/Article/details/gt2smnluvie.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nbfankcz.html

PHP:  // 手写时间戳比较
来源：http://dali.yuanzhike.top/Article/details/gt2qqxozbex.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gt2mhlazkqx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jlvdfomj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nwbrower.top/Article/details/gt2zhguqcla.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cucudq.cn/Article/details/gt2oxhxvagk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.wangdashe.top/Article/details/gt2kegefljq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ehwqpu.com/Article/details/gt2difnuzqs.html

[P08] 处理浮点精度问题
来源：http://dali.yuanzhike.top/Article/details/gt2ocdtoqkm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ybcxt.top/Article/details/gt2zgupacwi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.aizwys.cn/Article/details/gt2egejobfd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hongshengwenyu.top/Article/details/gt2epumdyls.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.pycfn.com/Article/details/gt2pepjjdhy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhongyouzk.top/Article/details/gt2fisftjfp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.haohaochexian.top/Article/details/gt2zjuwiiom.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhongyouzk.top/Article/details/gt2qwfletkn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cdnleiting.top/Article/details/gt2ntydpwuk.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2ektqagkr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jianghu66.top/Article/details/gt2craccjwt.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2bhghjegx.html

[Q01] 创建表
来源：http://dali.shzxlz.cn/Article/details/gt2imyxeuoz.html

CREATE TABLE users (
来源：http://dali.xuanzx.com/Article/details/gt2vofxiiqb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yongpay.top/Article/details/gt2hsbpuwax.html

name VARCHAR(50) NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gt2jaoyoybd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zdqjudy.top/Article/details/gt2umkqnoua.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yuxming.cn/Article/details/gt2phildgbe.html

);
来源：http://dali.yj202588.top/Article/details/gt2bknrfmez.html

[Q02] 创建带外键的表
来源：http://dali.havefunace.top/Article/details/gt2expfipjb.html

CREATE TABLE orders (
来源：http://dali.yuanzhike.top/Article/details/gt2pkxxdeuo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.vqdsnc.cn/Article/details/gt2lylegvdr.html

user_id INT NOT NULL,
来源：http://dali.316326.xyz/Article/details/gt2gzsprjnv.html

amount DECIMAL(10, 2),
来源：http://dali.xylfe.cn/Article/details/gt2nfjgbpvt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cashguo.top/Article/details/gt2jvntqwzz.html

);
来源：http://dali.pycfn.com/Article/details/gt2doplquej.html

[Q03] 增加列
来源：http://dali.hongshengwenyu.top/Article/details/gt2xfkdiiky.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xuanzx.com/Article/details/gt2qdjofrsu.html

[Q04] 修改列类型
来源：http://dali.jiagoushi.top/Article/details/gt2zdrdkaqa.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.havefunace.top/Article/details/gt2wmyojhye.html

[Q05] 重命名列
来源：http://dali.hysaishi.cn/Article/details/gt2abiqohtj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cdnleiting.top/Article/details/gt2tuvwyguu.html

[Q06] 删除列
来源：http://dali.yj20258.top/Article/details/gt2wjpglftd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.kuanghao11.cn/Article/details/gt2llzppakq.html

[Q07] 删除表
来源：http://dali.feifeiyinyue.top/Article/details/gt2rquvexop.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yonumen.top/Article/details/gt2rwonuzhc.html

[Q08] 创建普通索引
来源：http://dali.xuetiantiany.cn/Article/details/gt2sygjosyd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hammf.cn/Article/details/gt2gnvcezqy.html

[Q09] 创建唯一索引
来源：http://dali.cucudq.cn/Article/details/gt2xmtsupmd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hysaishi.cn/Article/details/gt2gymrerfp.html

[Q10] 插入单行
来源：http://dali.aizwys.cn/Article/details/gt2cpftixdb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuxming.cn/Article/details/gt2neccuacs.html

[Q11] 一次插入多行
来源：http://dali.cashguo.top/Article/details/gt2lpsncemc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.fzhhl.top/Article/details/gt2bjtadbng.html

[Q12] 插入后取自增 ID
来源：http://dali.jianghu66.top/Article/details/gt2smphfgxw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gogol.net.cn/Article/details/gt2ekclzrnt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj20258888.top/Article/details/gt2lkzxlnkh.html

[Q13] 忽略重复插入
来源：http://dali.jqgfzy.top/Article/details/gt2nmndskhz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gt2xcseezoc.html

[Q14] 存在则更新（upsert）
来源：http://dali.redwolf501.top/Article/details/gt2bcppeowp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.dianchejie.cn/Article/details/gt2doxfrhne.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ydzc1.top/Article/details/gt2aurfmdsg.html

[Q15] 查询全部
来源：http://dali.hywenlv.cn/Article/details/gt2izljrrui.html

SELECT * FROM users;
来源：http://dali.hammf.cn/Article/details/gt2kqdvonan.html

[Q16] 查询指定列
来源：http://dali.sysykeji.top/Article/details/gt2sndjgafg.html

SELECT id, name FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2rsfjjdfs.html

[Q17] 条件查询
来源：http://dali.hnxiangtu.top/Article/details/gt2bnnivpyq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2uywesvvo.html

[Q18] 模糊匹配
来源：http://dali.snrcjt.cn/Article/details/gt2xcpvexvp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tian-w.cn/Article/details/gt2pojsomre.html

[Q19] 范围查询
来源：http://dali.svipenyu.cn/Article/details/gt2ddcrmhrg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnqzz.top/Article/details/gt2aldtqgfx.html

[Q20] IN 列表
来源：http://dali.c1oappe.top/Article/details/gt2quvkswfo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.havefunace.top/Article/details/gt2fnfkweht.html

[Q21] 空值判断
来源：http://dali.c1oappe.top/Article/details/gt2xqidoggg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.bjfxy.top/Article/details/gt2piylejyv.html

[Q22] 排序
来源：http://dali.fzhhl.top/Article/details/gt2jdfnvneu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cucudq.cn/Article/details/gt2rgwqrbqe.html

[Q23] 分页
来源：http://dali.yangfankeji.com/Article/details/gt2kchrfafo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinqigufen.top/Article/details/gt2fpealeof.html

[Q24] 去重
来源：http://dali.hongshengwenyu.top/Article/details/gt2ggtmuilc.html

SELECT DISTINCT city FROM users;
来源：http://dali.tanke756.top/Article/details/gt2vsapqhwj.html

[Q25] 只取前 N 条
来源：http://dali.daria6918.cn/Article/details/gt2gmjyvtay.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xziqi.cn/Article/details/gt2wjellbtk.html

[Q26] 计数
来源：http://dali.jiagoushi.top/Article/details/gt2bhnchlvn.html

SELECT COUNT(*) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2xyhndbyr.html

[Q27] 条件计数
来源：http://dali.hammf.cn/Article/details/gt2suxxfbyu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2svxoijza.html

[Q28] 求和与平均
来源：http://dali.daria6918.cn/Article/details/gt2khaodylf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gt2xsnxxusa.html

[Q29] 最大最小值
来源：http://dali.yangfankeji.com/Article/details/gt2fzwdtazr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2jkuxfizs.html

[Q30] 分组统计
来源：http://dali.fengsongda.top/Article/details/gt2eigloymn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gt2vmphdwwk.html

[Q31] 分组后过滤
来源：http://dali.smart0.xyz/Article/details/gt2ccwztuuj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jiagoushi.top/Article/details/gt2djyfbpeo.html

[Q32] 分组拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2eybwymfg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gt2vfgfwxxh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.daxiang520.top/Article/details/gt2tlfvsndk.html

[Q33] 多列分组
来源：http://dali.xuetiantiany.cn/Article/details/gt2aumnthne.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.bjfxy.top/Article/details/gt2uttxesxb.html

[Q34] 每组取第一条
来源：http://dali.sweek.top/Article/details/gt2lnagwwhs.html

SELECT * FROM (
来源：http://dali.havefunace.top/Article/details/gt2eawtztbb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.wangshuangyany.cn/Article/details/gt2yqlnqdbq.html

) t WHERE rn = 1;
来源：http://dali.hywenlv.cn/Article/details/gt2arhwxpmw.html

[Q35] 内连接
来源：http://dali.cheryme.top/Article/details/gt2yletxjcp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwgmgdz.html

[Q36] 左连接
来源：http://dali.tian-w.cn/Article/details/gt2pnvoejyu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gt2gpikdmgd.html

[Q37] 右连接
来源：http://dali.smart0.xyz/Article/details/gt2bgxknrzr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nwbrower.top/Article/details/gt2ujbegfbf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jianghu66.top/Article/details/gt2mtzdhfmh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.aizwys.cn/Article/details/gt2inwrjjku.html

[Q39] 自连接（查上下级）
来源：http://dali.fzhhl.top/Article/details/gt2tqepaeyd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinqigufen.top/Article/details/gt2meunaywn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fengsongda.top/Article/details/gt2rzbmcrjq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.havefunace.top/Article/details/gt2pgyibeqj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shangyingyoupin.top/Article/details/gt2vvimugqv.html

[Q41] 多表连接
来源：http://dali.meibo888.top/Article/details/gt2zottjmtb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.0kj1m.cn/Article/details/gt2lqhkjcxy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jiagoushi.top/Article/details/gt2xtvdlmuz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.guowangkeji.top/Article/details/gt2qmzcjcgd.html

[Q42] 连接条件附加过滤
来源：http://dali.jinqigufen.top/Article/details/gt2ejjlwush.html

SELECT u.name, o.amount FROM users u
来源：http://dali.aizwys.cn/Article/details/gt2opkoqpxm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhongyouzk.top/Article/details/gt2ljzupjsg.html

[Q43] 标量子查询
来源：http://dali.aizwys.cn/Article/details/gt2qvvttrdt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.smart0.xyz/Article/details/gt2bniptfma.html

[Q44] IN 子查询
来源：http://dali.zhoulong.xyz/Article/details/gt2mnoaqtwm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhiwuduotai.top/Article/details/gt2nignsayo.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xsrpfpgs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gt2zhsvvwts.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dashuyun.cn/Article/details/gt2zjzemuiq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2losjgvhw.html

[Q47] 与平均值比较
来源：http://dali.yuxming.cn/Article/details/gt2rmyvolwc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangdashe.top/Article/details/gt2ncudfidy.html

[Q48] CTE 公用表表达式
来源：http://dali.yj20258888.top/Article/details/gt2smdghwwg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenlongwang.top/Article/details/gt2tndoqgsc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yangfankeji.com/Article/details/gt2xtnivpjo.html

[Q49] 更新单行
来源：http://dali.jlsjyb.cn/Article/details/gt2ycvcsfun.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hysaishi.cn/Article/details/gt2jmqpucbg.html

[Q50] 批量更新
来源：http://dali.andypj.xyz/Article/details/gt2nemjwhll.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gt2sptasxwt.html

[Q51] 用子查询更新
来源：http://dali.jqgufenzy.top/Article/details/gt2lmyvzwur.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2joyfwqfd.html

[Q52] 删除指定行
来源：http://dali.nanxinkj.top/Article/details/gt2okyrphan.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigfzy.top/Article/details/gt2ntcvwvld.html

[Q53] 按条件删除
来源：http://dali.shuidangran.top/Article/details/gt2iysesnug.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dianchejie.cn/Article/details/gt2shbodcti.html

[Q54] 清空表
来源：http://dali.xuetiantiany.cn/Article/details/gt2hnrbqtzi.html

TRUNCATE TABLE logs;
来源：http://dali.daria6918.cn/Article/details/gt2qltofwlm.html

[Q55] 排名（并列占位）
来源：http://dali.xuanzx.com/Article/details/gt2cdyfgklc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.0kj1m.cn/Article/details/gt2uzcanbky.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ohisjcct.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.redwolf501.top/Article/details/gt2xtklixmo.html

[Q57] 行号
来源：http://dali.xziqi.cn/Article/details/gt2rckibxqz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2zbrkcryg.html

[Q58] 累计求和
来源：http://dali.cdnleiting.top/Article/details/gt2hdlehyrr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2cshhsymc.html

[Q59] 分组内累计
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dnqfnsey.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gt2ymxvdrla.html

[Q60] 取上一行 / 下一行
来源：http://dali.iojbl.cn/Article/details/gt2gwhwflfr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gaohongyu789.top/Article/details/gt2gvjuloyq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gt2nlssnknn.html

[Q61] 移动平均
来源：http://dali.fzhhl.top/Article/details/gt2xwftyktk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qkxlmaff.html

[Q62] 分组占比
来源：http://dali.shangyingyoupin.top/Article/details/gt2rxjsfosg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gt2robypmao.html

[Q63] 开启事务
来源：http://dali.gzhubu.top/Article/details/gt2gsyfckzu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.havefunace.top/Article/details/gt2tvaaakdu.html

[Q64] 提交事务
来源：http://dali.cdnleiting.top/Article/details/gt2pgrnfgpi.html

COMMIT;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ndpjbdyy.html

[Q65] 回滚事务
来源：http://dali.smart0.xyz/Article/details/gt2pigeinxy.html

ROLLBACK;
来源：http://dali.xuetiantiany.cn/Article/details/gt2bgozvarv.html

[Q66] 行锁查询
来源：http://dali.xuetiantiany.cn/Article/details/gt2vyehctta.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sxryk.cn/Article/details/gt2rzjmkgxp.html

[Q67] 设置隔离级别
来源：http://dali.zhiwuduotai.top/Article/details/gt2ksxiykhr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oivxiftq.html

[Q68] 保存点
来源：http://dali.daria6918.cn/Article/details/gt2afvtxska.html

SAVEPOINT sp1;
来源：http://dali.nwbrower.top/Article/details/gt2ldhjtmtx.html

ROLLBACK TO sp1;
来源：http://dali.mhx1999.top/Article/details/gt2yyvvomcj.html

[Q69] 查看执行计划
来源：http://dali.nwbrower.top/Article/details/gt2blkgxfrl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aibaodan.cn/Article/details/gt2xhmzlhzi.html

[Q70] 更新统计信息
来源：http://dali.hywenlv.cn/Article/details/gt2evwsynir.html

ANALYZE TABLE users;
来源：http://dali.aizwys.cn/Article/details/gt2ikaskwcx.html

[Q71] 查看建表语句
来源：http://dali.aizwys.cn/Article/details/gt2duzdscvu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hywenlv.cn/Article/details/gt2ckzftzwm.html

[Q72] 查看索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zonurdxd.html

SHOW INDEX FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2mdpuiwax.html

[Q73] 查看表状态
来源：http://dali.jqgufenzy.top/Article/details/gt2zkgxdojo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gogol.net.cn/Article/details/gt2wacpghsx.html

[Q74] 强制使用索引
来源：http://dali.hywenlv.cn/Article/details/gt2zkwbhhxi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ehwqpu.com/Article/details/gt2yzpptwxh.html

[Q75] 日期格式化
来源：http://dali.cashguo.top/Article/details/gt2rgghumls.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xziqi.cn/Article/details/gt2xikcfjln.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.mhx1999.top/Article/details/gt2motjtazx.html

[Q76] 按天统计
来源：http://dali.smart0.xyz/Article/details/gt2grpwbvri.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxuanxn.top/Article/details/gt2bdefazqj.html

[Q77] 时间加减
来源：http://dali.jqgfzy.top/Article/details/gt2dowzffpn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bkathrqt.html

[Q78] 当前时间
来源：http://dali.yuanzhike.top/Article/details/gt2xpjwrbgh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.vqdsnc.cn/Article/details/gt2kotbkgmu.html

[Q79] 字符串拼接
来源：http://dali.quarkkingdee.top/Article/details/gt2qkvbqlwq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vkshelsp.html

[Q80] 字符串截取
来源：http://dali.kuanghao11.cn/Article/details/gt2olckzqaq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2voqzqruq.html

[Q81] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gt2bescckwo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2ayoryxxu.html

[Q82] 字符长度与字节长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yfxmlozu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2bnycpdns.html

[Q83] 大小写转换
来源：http://dali.ivvv.top/Article/details/gt2whpmwxbo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2urgeawjk.html

[Q84] 去除首尾空格
来源：http://dali.ppjwa.cn/Article/details/gt2kxizaoqk.html

SELECT TRIM(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2dlbmimrl.html

[Q85] 数值取整
来源：http://dali.zhixingplan.top/Article/details/gt2yunnctqh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sxryk.cn/Article/details/gt2mwylebux.html

[Q86] 读取 JSON 字段
来源：http://dali.nanxinkj.top/Article/details/gt2vhimjljy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhixingplan.top/Article/details/gt2scizfxss.html

[Q87] JSON 字段做条件
来源：http://dali.yvedp.cn/Article/details/gt2vyikcytg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xuetiantiany.cn/Article/details/gt2xqzvbvgd.html

[Q88] 行转列（条件聚合）
来源：http://dali.gogol.net.cn/Article/details/gt2ljbwlokn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ehwqpu.com/Article/details/gt2tuoakblu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2dhuoiysj.html

[Q89] 判断表是否存在
来源：http://dali.zhoulong.xyz/Article/details/gt2cqjanqax.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sufxvd.cn/Article/details/gt2ynqumvkn.html

[Q90] 生成序号列
来源：http://dali.fzhhl.top/Article/details/gt2vlncgocj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2baymyjdi.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2ogrhdshz.html

R. Bash 专题
来源：http://dali.haohaochexian.top/Article/details/gt2hzednanm.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2ftbkuaar.html

[R01] shebang 与严格模式
来源：http://dali.tianlin.xyz/Article/details/gt2fptqvsfc.html

#!/usr/bin/env bash
来源：http://dali.xuanzx.com/Article/details/gt2kfmvowme.html

set -euo pipefail
来源：http://dali.guowangkeji.top/Article/details/gt2kbunnvfs.html

[R02] 变量赋值与使用
来源：http://dali.zhiwuduotai.top/Article/details/gt2htwmpvly.html

name="Tom"; echo "$name"
来源：http://dali.gotoacloud.top/Article/details/gt2tlczlygj.html

[R03] 只读变量
来源：http://dali.yonumen.top/Article/details/gt2dnyodkje.html

readonly PI=3.14
来源：http://dali.pengpengdd.cyou/Article/details/gt2xlwqwmde.html

[R04] 位置参数
来源：http://dali.dashuyun.cn/Article/details/gt2qttjenwn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.quarkkingdee.top/Article/details/gt2ngkzlvco.html

[R05] 参数默认值
来源：http://dali.yangfankeji.com/Article/details/gt2ngcqpmgy.html

name="${1:-default}"
来源：http://dali.hnqzz.top/Article/details/gt2brzugcpl.html

[R06] 判断命令是否存在
来源：http://dali.sweek.top/Article/details/gt2phxjhwnn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.andypj.xyz/Article/details/gt2mzxadsma.html

[R07] if 判断文件
来源：http://dali.cdnleiting.top/Article/details/gt2vjouidbl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daxiang520.top/Article/details/gt2isbgrkwn.html

[R08] 数值比较
来源：http://dali.shuidangran.top/Article/details/gt2lvunncpu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ydzc1.top/Article/details/gt2zmdeqpwx.html

[R09] 字符串比较
来源：http://dali.smart0.xyz/Article/details/gt2avcfypsy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guowangkeji.top/Article/details/gt2qhobqemg.html

[R10] 正则匹配
来源：http://dali.andypj.xyz/Article/details/gt2oeylduor.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xziqi.cn/Article/details/gt2vxjmetlk.html

[R11] case 多分支
来源：http://dali.yongpay.top/Article/details/gt2fzdbnecz.html

case "$1" in
来源：http://dali.yangfankeji.com/Article/details/gt2xfiwkcfo.html

start) echo "启动" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bzuskudq.html

stop)  echo "停止" ;;
来源：http://dali.fzhhl.top/Article/details/gt2hhixycqn.html

*)     echo "未知命令" ;;
来源：http://dali.yuanzhike.top/Article/details/gt2ufevuvah.html

esac
来源：http://dali.shzxlz.cn/Article/details/gt2fcfgmyqs.html

[R12] for 遍历文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xjphpheu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.meibo888.top/Article/details/gt2mknpfsqw.html

[R13] for 计数循环
来源：http://dali.daria6918.cn/Article/details/gt2utrcmkrs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nodxepil.html

[R14] C 风格 for
来源：http://dali.zhengqikj.top/Article/details/gt2uqtdsxiw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gt2vjalphra.html

[R15] while 逐行读文件
来源：http://dali.yuxming.cn/Article/details/gt2wafrqsht.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zdqjudy.top/Article/details/gt2ezbsobiw.html

[R16] until 等待条件
来源：http://dali.hongshengwenyu.top/Article/details/gt2lealowlz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gt2jppirjer.html

[R17] 数组定义与取值
来源：http://dali.jyoumei.cn/Article/details/gt2usjkoxmq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2kznbubwi.html

[R18] 遍历数组
来源：http://dali.ivvv.top/Article/details/gt2ixciibzb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tianlin.xyz/Article/details/gt2efaxfgzm.html

[R19] 数组长度
来源：http://dali.yongpay.top/Article/details/gt2ibazguok.html

echo "${#arr[@]}"
来源：http://dali.yj202588.top/Article/details/gt2qaziykke.html

[R20] 关联数组（字典）
来源：http://dali.jiagoushi.top/Article/details/gt2vdlgaiai.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.kuanghao11.cn/Article/details/gt2iwhdbwbw.html

[R21] 字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gt2eehhhrgy.html

echo "${#s}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fyzianqs.html

[R22] 截取子串
来源：http://dali.hysaishi.cn/Article/details/gt2anzpyowm.html

echo "${s:0:5}"
来源：http://dali.mhx1999.top/Article/details/gt2lisxkgvh.html

[R23] 字符串替换
来源：http://dali.yongpay.top/Article/details/gt2jfcmadah.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ydzc1.top/Article/details/gt2akccqpyo.html

[R24] 大小写转换
来源：http://dali.aizwys.cn/Article/details/gt2gdpgywsi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2otxsuhgr.html

[R25] 去后缀 / 去前缀
来源：http://dali.xziqi.cn/Article/details/gt2qqguspbs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.svipenyu.cn/Article/details/gt2xtyjcjoo.html

[R26] 命令替换
来源：http://dali.jlsjyb.cn/Article/details/gt2svxtbvwd.html

now=$(date +%F); echo "$now"
来源：http://dali.smart0.xyz/Article/details/gt2mkxfwccl.html

[R27] 算术展开
来源：http://dali.zhongyouzk.top/Article/details/gt2qhzpbfbr.html

echo $((1 + 2 * 3))
来源：http://dali.jianghu66.top/Article/details/gt2dtmgrdqe.html

[R28] 浮点运算
来源：http://dali.sweek.top/Article/details/gt2ydmbwinj.html

echo "scale=2; 10/3" | bc
来源：http://dali.tianlin.xyz/Article/details/gt2ztjmoclg.html

[R29] 定义函数
来源：http://dali.yanxiufei.cn/Article/details/gt2jmzikdow.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.quarkkingdee.top/Article/details/gt2fpbytmtl.html

[R30] 函数返回状态码
来源：http://dali.havefunace.top/Article/details/gt2jnpvmioi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhiwuduotai.top/Article/details/gt2icnuxrjq.html

[R31] 局部变量
来源：http://dali.yj202588.top/Article/details/gt2jailbhjb.html

f() { local x=1; echo "$x"; }
来源：http://dali.yueranfly.top/Article/details/gt2wxeiubnb.html

[R32] 参数个数校验
来源：http://dali.hfpthk.cn/Article/details/gt2ousliqsh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gt2bmclwrnd.html

[R33] 捕获错误并提示行号
来源：http://dali.meibo888.top/Article/details/gt2cxflqkpx.html


<!-- 参考信息 -->