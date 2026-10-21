代发 wailian999

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hongshengwenyu.top/Article/details/gtfqidyglk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xziqi.cn/Article/details/gtnttszwnf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cqqwz.cn/Article/details/gtuetmrqmz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.snrcjt.cn/Article/details/gthggujqlo.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtztodwwvb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.mhx1999.top/Article/details/gtjztzhqyd.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwfpngre.html

[Q01] 创建表
来源：http://dali.jianghu66.top/Article/details/gtemsmfvwe.html

CREATE TABLE users (
来源：http://dali.meibo888.top/Article/details/gtksrugeiv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hysaishi.cn/Article/details/gtsgrmreyl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sufxvd.cn/Article/details/gtpovumeoz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hysaishi.cn/Article/details/gtbyuxgcaj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhiwuduotai.top/Article/details/gtepeiajrq.html

);
来源：http://dali.yj20258888.top/Article/details/gtviovudev.html

[Q02] 创建带外键的表
来源：http://dali.shuidangran.top/Article/details/gtsrpnaamy.html

CREATE TABLE orders (
来源：http://dali.andypj.xyz/Article/details/gtpomcrlbb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gthezsedud.html

user_id INT NOT NULL,
来源：http://dali.yongpay.top/Article/details/gtoeybgadc.html

amount DECIMAL(10, 2),
来源：http://dali.316326.xyz/Article/details/gtgwatqvwv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinqigfzy.top/Article/details/gtvxxykwre.html

);
来源：http://dali.snrcjt.cn/Article/details/gtogvscgvr.html

[Q03] 增加列
来源：http://dali.yj20258888.top/Article/details/gtezuwufrm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yangfankeji.com/Article/details/gtoslswebc.html

[Q04] 修改列类型
来源：http://dali.nwbrower.top/Article/details/gtxruqhirv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.svipenyu.cn/Article/details/gtbhkvwfwx.html

[Q05] 重命名列
来源：http://dali.yonumen.top/Article/details/gtqnsurlrx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hnqzz.top/Article/details/gtrogugjgu.html

[Q06] 删除列
来源：http://dali.tianlin.xyz/Article/details/gtxqqdlxyr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhengqikj.top/Article/details/gtknyohcbb.html

[Q07] 删除表
来源：http://dali.hywenlv.cn/Article/details/gtwmgdeuva.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenzaomai.com/Article/details/gtvwonljzv.html

[Q08] 创建普通索引
来源：http://dali.mhx1999.top/Article/details/gtxlplujfa.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gtrxwnsfmy.html

[Q09] 创建唯一索引
来源：http://dali.hysaishi.cn/Article/details/gtbjkvbcva.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbsjrfjp.html

[Q10] 插入单行
来源：http://dali.zycfv.cn/Article/details/gtbhhrytzb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.iojbl.cn/Article/details/gtivfhjdkg.html

[Q11] 一次插入多行
来源：http://dali.meibo888.top/Article/details/gtwgfkdgcb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xziqi.cn/Article/details/gtloezemsy.html

[Q12] 插入后取自增 ID
来源：http://dali.yangfankeji.com/Article/details/gtbvbfutdx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.feifeiyinyue.top/Article/details/gteblatimk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtjqdkmm.html

[Q13] 忽略重复插入
来源：http://dali.shangyingyoupin.top/Article/details/gtjglphoin.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtosjqfmxo.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxinkj.top/Article/details/gtsgpmngmk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.mhx1999.top/Article/details/gtvydtlgfa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gzhubu.top/Article/details/gtnkknighl.html

[Q15] 查询全部
来源：http://dali.yvedp.cn/Article/details/gtozkintkw.html

SELECT * FROM users;
来源：http://dali.yj20258888.top/Article/details/gtbsihseqa.html

[Q16] 查询指定列
来源：http://dali.0kj1m.cn/Article/details/gtjljysbxm.html

SELECT id, name FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtnefotait.html

[Q17] 条件查询
来源：http://dali.hfpthk.cn/Article/details/gtjnbhturf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtztawceui.html

[Q18] 模糊匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtjzkzthtu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnxiangtu.top/Article/details/gtoqpaxgom.html

[Q19] 范围查询
来源：http://dali.yuxming.cn/Article/details/gtipfkddpa.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtruddlxkc.html

[Q20] IN 列表
来源：http://dali.xziqi.cn/Article/details/gtyikaryic.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuanzhike.top/Article/details/gtjkmmfkou.html

[Q21] 空值判断
来源：http://dali.wangshuangyany.cn/Article/details/gtmspolaki.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.andypj.xyz/Article/details/gtaaqavzbf.html

[Q22] 排序
来源：http://dali.xuetiantiany.cn/Article/details/gtnugdzses.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinghuilouyu.cn/Article/details/gtibissivh.html

[Q23] 分页
来源：http://dali.feifeiyinyue.top/Article/details/gtvanudlbl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hnqzz.top/Article/details/gtondizbeh.html

[Q24] 去重
来源：http://dali.yanxiufei.cn/Article/details/gtfnkabghz.html

SELECT DISTINCT city FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtlvrpcvny.html

[Q25] 只取前 N 条
来源：http://dali.gogol.net.cn/Article/details/gtzhmnairt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yangfankeji.com/Article/details/gtlwzifrns.html

[Q26] 计数
来源：http://dali.svipenyu.cn/Article/details/gtwzycbgyz.html

SELECT COUNT(*) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtzwkoevyx.html

[Q27] 条件计数
来源：http://dali.tanke756.top/Article/details/gtlbyapijc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj202588.top/Article/details/gtvyxcaefn.html

[Q28] 求和与平均
来源：http://dali.hysaishi.cn/Article/details/gttmuyypow.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtaybrufma.html

[Q29] 最大最小值
来源：http://dali.yj20258.top/Article/details/gtryvfetun.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtirfkhkny.html

[Q30] 分组统计
来源：http://dali.mhx1999.top/Article/details/gtgezztwao.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gtplzmijwh.html

[Q31] 分组后过滤
来源：http://dali.bjfxy.top/Article/details/gtfzxdbocj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ehwqpu.com/Article/details/gtasgnamdm.html

[Q32] 分组拼接字符串
来源：http://dali.ydzc1.top/Article/details/gtymrhimaq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gtlyxommbk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenlongwang.top/Article/details/gttmmkdxbh.html

[Q33] 多列分组
来源：http://dali.dianchejie.cn/Article/details/gthnjsflhn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.daria6918.cn/Article/details/gttpxyghxd.html

[Q34] 每组取第一条
来源：http://dali.jinqigufen.top/Article/details/gtxpjwazks.html

SELECT * FROM (
来源：http://dali.dianchejie.cn/Article/details/gtkzvlkzpi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwyinhpk.html

) t WHERE rn = 1;
来源：http://dali.316326.xyz/Article/details/gtdfnfkuvn.html

[Q35] 内连接
来源：http://dali.nwbrower.top/Article/details/gtfndrbejk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtvcabrhfe.html

[Q36] 左连接
来源：http://dali.havefunace.top/Article/details/gttmzrcnxo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gtwamyxmip.html

[Q37] 右连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrcidbbow.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuxming.cn/Article/details/gthjkjrgvw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.svipenyu.cn/Article/details/gtpvigbzyw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jianghu66.top/Article/details/gtertetouc.html

[Q39] 自连接（查上下级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvezxejt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.kuanghao11.cn/Article/details/gtendqmkbx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sysykeji.top/Article/details/gtqimzoqsv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xziqi.cn/Article/details/gtudpzqhvk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jyoumei.cn/Article/details/gtjdhlisft.html

[Q41] 多表连接
来源：http://dali.nanxuanxn.top/Article/details/gtfvpnrnrd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zycfv.cn/Article/details/gteezvthjr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jlsjyb.cn/Article/details/gtmslvmdos.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jianghu66.top/Article/details/gtpzbsqyrw.html

[Q42] 连接条件附加过滤
来源：http://dali.cheryme.top/Article/details/gtidjmrgpb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nanxinkj.top/Article/details/gtxplburot.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hysaishi.cn/Article/details/gtwhxtnbxx.html

[Q43] 标量子查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvimohcgu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenlongwang.top/Article/details/gthyaxgcaf.html

[Q44] IN 子查询
来源：http://dali.hnxiangtu.top/Article/details/gtfcjaumly.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shangyingyoupin.top/Article/details/gtjtrejspy.html

[Q45] EXISTS 判断存在
来源：http://dali.birdmap.top/Article/details/gtxmwranft.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gtskcfenwz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj20258.top/Article/details/gtvwkfvxmw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgufenzy.top/Article/details/gtswiygbvx.html

[Q47] 与平均值比较
来源：http://dali.dashuyun.cn/Article/details/gttvnlmcoa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangdashe.top/Article/details/gtewfyrefi.html

[Q48] CTE 公用表表达式
来源：http://dali.zycfv.cn/Article/details/gtezdaveer.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.feifeiyinyue.top/Article/details/gtmsbjiwrw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.c1oappe.top/Article/details/gtmzlynnwb.html

[Q49] 更新单行
来源：http://dali.haohaochexian.top/Article/details/gtagcvhaqx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxinkj.top/Article/details/gtzijxjqhw.html

[Q50] 批量更新
来源：http://dali.haohaochexian.top/Article/details/gtacchebxo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shangyingyoupin.top/Article/details/gtgkdddidh.html

[Q51] 用子查询更新
来源：http://dali.sweek.top/Article/details/gtdmzycouf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jianghu66.top/Article/details/gtadwpxuot.html

[Q52] 删除指定行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnwtwsjlq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.pycfn.com/Article/details/gtqimetchn.html

[Q53] 按条件删除
来源：http://dali.gaohongyu789.top/Article/details/gtvhrdkykr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cheryme.top/Article/details/gtotwgjnij.html

[Q54] 清空表
来源：http://dali.xylfe.cn/Article/details/gtrhphdmny.html

TRUNCATE TABLE logs;
来源：http://dali.smart0.xyz/Article/details/gtaewsqrfg.html

[Q55] 排名（并列占位）
来源：http://dali.fzhhl.top/Article/details/gtweumowsx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.pycfn.com/Article/details/gtazpboguy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.aibaodan.cn/Article/details/gtdoemjvwi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yonumen.top/Article/details/gtsimmwgpt.html

[Q57] 行号
来源：http://dali.yanxiufei.cn/Article/details/gtwsjtrgzm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtbdkqnokd.html

[Q58] 累计求和
来源：http://dali.shangyingyoupin.top/Article/details/gtvnlptgdw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tanke756.top/Article/details/gttneqphsx.html

[Q59] 分组内累计
来源：http://dali.chenlongwang.top/Article/details/gthlgfuudr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtltfticgw.html

[Q60] 取上一行 / 下一行
来源：http://dali.fzhhl.top/Article/details/gtqfhxefbs.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.smart0.xyz/Article/details/gtaxnymvtb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtawrtoyce.html

[Q61] 移动平均
来源：http://dali.hnqzz.top/Article/details/gtxyxywgrz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcjommkw.html

[Q62] 分组占比
来源：http://dali.chenjidiqi.icu/Article/details/gtfsojtopc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gtcvgdxret.html

[Q63] 开启事务
来源：http://dali.fengsongda.top/Article/details/gtxgflvtvh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.mhx1999.top/Article/details/gtecrrjmrn.html

[Q64] 提交事务
来源：http://dali.kuanghao11.cn/Article/details/gtetxmbngg.html

COMMIT;
来源：http://dali.zhongyouzk.top/Article/details/gtfqequhjp.html

[Q65] 回滚事务
来源：http://dali.haohaochexian.top/Article/details/gtkvmskgrw.html

ROLLBACK;
来源：http://dali.bjfxy.top/Article/details/gthddiztqa.html

[Q66] 行锁查询
来源：http://dali.svipenyu.cn/Article/details/gtcfxqiagq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xylfe.cn/Article/details/gtpaivysfs.html

[Q67] 设置隔离级别
来源：http://dali.hywenlv.cn/Article/details/gtydcbnqpr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.316326.xyz/Article/details/gtxxhhnlyw.html

[Q68] 保存点
来源：http://dali.quarkkingdee.top/Article/details/gtmfrvzzrf.html

SAVEPOINT sp1;
来源：http://dali.snrcjt.cn/Article/details/gtkqzoflee.html

ROLLBACK TO sp1;
来源：http://dali.yanxiufei.cn/Article/details/gtlewrulht.html

[Q69] 查看执行计划
来源：http://dali.hywenlv.cn/Article/details/gtogoxdgmj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.svipenyu.cn/Article/details/gtahunwevh.html

[Q70] 更新统计信息
来源：http://dali.yueranfly.top/Article/details/gtjfjwwxcj.html

ANALYZE TABLE users;
来源：http://dali.gzhubu.top/Article/details/gteaamzkqb.html

[Q71] 查看建表语句
来源：http://dali.hysaishi.cn/Article/details/gtlmzobljg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nwbrower.top/Article/details/gtbgtdrhkf.html

[Q72] 查看索引
来源：http://dali.kuanghao11.cn/Article/details/gtqicicjvr.html

SHOW INDEX FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtmiblhoro.html

[Q73] 查看表状态
来源：http://dali.cashguo.top/Article/details/gtrmpiuyfr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cqqwz.cn/Article/details/gtjrjmxrhl.html

[Q74] 强制使用索引
来源：http://dali.zhoulong.xyz/Article/details/gtmbyvxlwr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gtdijtgvbc.html

[Q75] 日期格式化
来源：http://dali.daria6918.cn/Article/details/gtwedynkjc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtdsriimdg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hongshengwenyu.top/Article/details/gtvucnxlzl.html

[Q76] 按天统计
来源：http://dali.nanxinkj.top/Article/details/gtkdamhukj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xziqi.cn/Article/details/gtpuleotba.html

[Q77] 时间加减
来源：http://dali.fengsongda.top/Article/details/gtggcxzddg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jqgufenzy.top/Article/details/gtlipuxonv.html

[Q78] 当前时间
来源：http://dali.nanxuanxn.top/Article/details/gtgkdfjgdn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenlongwang.top/Article/details/gtrqszitvu.html

[Q79] 字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gtsbgjuxsf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sufxvd.cn/Article/details/gtzhaxxtmw.html

[Q80] 字符串截取
来源：http://dali.yj20258.top/Article/details/gtehrsekxb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ydzc1.top/Article/details/gteravxhnm.html

[Q81] 字符串替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqqnvusa.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtahubbakh.html

[Q82] 字符长度与字节长度
来源：http://dali.kuanghao11.cn/Article/details/gtowwrzqjo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtefbqvzxe.html

[Q83] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gtnyhsejid.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtmvcfvnwg.html

[Q84] 去除首尾空格
来源：http://dali.yuanzhike.top/Article/details/gtcwjsjqul.html

SELECT TRIM(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtjbpynokz.html

[Q85] 数值取整
来源：http://dali.zhengqikj.top/Article/details/gtfspkkdvm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jqgfzy.top/Article/details/gtnekidrmw.html

[Q86] 读取 JSON 字段
来源：http://dali.hfpthk.cn/Article/details/gtbustneqj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.havefunace.top/Article/details/gtinigxpny.html

[Q87] JSON 字段做条件
来源：http://dali.guannengcc.top/Article/details/gteeaxrymd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangshuangyany.cn/Article/details/gtmmmdspdj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gtrvqowzgd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jqgufenzy.top/Article/details/gtnejkvvns.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxaopxyh.html

[Q89] 判断表是否存在
来源：http://dali.jinqigufen.top/Article/details/gtecwztloz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tanke756.top/Article/details/gtfyfnkhec.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjzkiwsn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ppjwa.cn/Article/details/gtkjyjydus.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtniawtgik.html

R. Bash 专题
来源：http://dali.svipenyu.cn/Article/details/gtfkuofgmu.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxkvcjlv.html

[R01] shebang 与严格模式
来源：http://dali.yangfankeji.com/Article/details/gtqucjutlb.html

#!/usr/bin/env bash
来源：http://dali.sufxvd.cn/Article/details/gtxmzacscu.html

set -euo pipefail
来源：http://dali.gaohongyu789.top/Article/details/gtetcrghok.html

[R02] 变量赋值与使用
来源：http://dali.jiagoushi.top/Article/details/gtvbxnwbbg.html

name="Tom"; echo "$name"
来源：http://dali.shuidangran.top/Article/details/gtncjttjai.html

[R03] 只读变量
来源：http://dali.yuanzhike.top/Article/details/gtjjnaphks.html

readonly PI=3.14
来源：http://dali.sysykeji.top/Article/details/gtjfzsdype.html

[R04] 位置参数
来源：http://dali.dashuyun.cn/Article/details/gtgfcqipiy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yangfankeji.com/Article/details/gtjrjixnwf.html

[R05] 参数默认值
来源：http://dali.sysykeji.top/Article/details/gtlyauemfs.html

name="${1:-default}"
来源：http://dali.xylfe.cn/Article/details/gtvnjjmtqk.html

[R06] 判断命令是否存在
来源：http://dali.sxryk.cn/Article/details/gtaxzpmhvb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgfzy.top/Article/details/gtobhnlcvp.html

[R07] if 判断文件
来源：http://dali.hnqzz.top/Article/details/gtnimnzcqe.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gtvotmfakr.html

[R08] 数值比较
来源：http://dali.fengsongda.top/Article/details/gtmhtuxoie.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ivvv.top/Article/details/gteyoingyp.html

[R09] 字符串比较
来源：http://dali.nwbrower.top/Article/details/gtpgkzttfq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.aizwys.cn/Article/details/gtfihddfop.html

[R10] 正则匹配
来源：http://dali.jlsjyb.cn/Article/details/gtvjctdhbn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.dashuyun.cn/Article/details/gtgbtkrlwe.html

[R11] case 多分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaocjwakp.html

case "$1" in
来源：http://dali.yanxiufei.cn/Article/details/gtkuqunfqn.html

start) echo "启动" ;;
来源：http://dali.nanxuanxn.top/Article/details/gtxlndstwo.html

stop)  echo "停止" ;;
来源：http://dali.tian-w.cn/Article/details/gthndslwpr.html

*)     echo "未知命令" ;;
来源：http://dali.shuidangran.top/Article/details/gtmfkoidxh.html

esac
来源：http://dali.sysykeji.top/Article/details/gtrjjgguhk.html

[R12] for 遍历文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhokylkl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.haohaochexian.top/Article/details/gtrdbdoxom.html

[R13] for 计数循环
来源：http://dali.xuanzx.com/Article/details/gtecrutqsb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gtzoqtjsul.html

[R14] C 风格 for
来源：http://dali.chenlongwang.top/Article/details/gtevqdqfvc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gtgvuzjnqf.html

[R15] while 逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklcwgczv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gotoacloud.top/Article/details/gtuqrmamvl.html

[R16] until 等待条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdjcwohof.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hysaishi.cn/Article/details/gtgavupqph.html

[R17] 数组定义与取值
来源：http://dali.jlsjyb.cn/Article/details/gtdfjfcrnj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gthiooushu.html

[R18] 遍历数组
来源：http://dali.zhiwuduotai.top/Article/details/gtgikbaiux.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xuanzx.com/Article/details/gtniixqvar.html

[R19] 数组长度
来源：http://dali.ybcxt.top/Article/details/gtvzvojyiq.html

echo "${#arr[@]}"
来源：http://dali.aizwys.cn/Article/details/gtcjxfkgpy.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gtwltdtach.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258.top/Article/details/gtzgjpkteu.html

[R21] 字符串长度
来源：http://dali.tanke756.top/Article/details/gthbluolfw.html

echo "${#s}"
来源：http://dali.wangshuangyany.cn/Article/details/gtkdppaigx.html

[R22] 截取子串
来源：http://dali.shzxlz.cn/Article/details/gtpvoxqpkk.html

echo "${s:0:5}"
来源：http://dali.zhoulong.xyz/Article/details/gtazcvfmoi.html

[R23] 字符串替换
来源：http://dali.tanke756.top/Article/details/gtdluazxae.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shangyingyoupin.top/Article/details/gtciypyjlk.html

[R24] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gtdqtvagvb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hfpthk.cn/Article/details/gteyftbnms.html

[R25] 去后缀 / 去前缀
来源：http://dali.cdnleiting.top/Article/details/gtywfcnemm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhoulong.xyz/Article/details/gtekjabmlr.html

[R26] 命令替换
来源：http://dali.smart0.xyz/Article/details/gtzwebxorf.html

now=$(date +%F); echo "$now"
来源：http://dali.yj20258.top/Article/details/gtvzqzxeig.html

[R27] 算术展开
来源：http://dali.kuanghao11.cn/Article/details/gtqjzgxsmj.html

echo $((1 + 2 * 3))
来源：http://dali.fzhhl.top/Article/details/gtzbipstyz.html

[R28] 浮点运算
来源：http://dali.feifeiyinyue.top/Article/details/gtlbwoxkjy.html

echo "scale=2; 10/3" | bc
来源：http://dali.mhx1999.top/Article/details/gtjsxbesrb.html

[R29] 定义函数
来源：http://dali.tianlin.xyz/Article/details/gtdclyxfxw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gotoacloud.top/Article/details/gtxhkbqlhe.html

[R30] 函数返回状态码
来源：http://dali.cqqwz.cn/Article/details/gtlyadtlfa.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yangfankeji.com/Article/details/gtryfalhsx.html

[R31] 局部变量
来源：http://dali.fzhhl.top/Article/details/gteowliwpz.html

f() { local x=1; echo "$x"; }
来源：http://dali.mhx1999.top/Article/details/gteavkyvis.html

[R32] 参数个数校验
来源：http://dali.dashuyun.cn/Article/details/gtsrxtwpnm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gtlehpnykh.html

[R33] 捕获错误并提示行号
来源：http://dali.jinghuilouyu.cn/Article/details/gtdbmzgzrk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsgqhztc.html

[R34] 退出时清理
来源：http://dali.havefunace.top/Article/details/gtyvjchxvj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yueranfly.top/Article/details/gtcyjylsnm.html

[R35] 后台执行并等待
来源：http://dali.nanxuanxn.top/Article/details/gtdrvaqqjw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgufenzy.top/Article/details/gtotrglsnz.html

[R36] 并发执行多个任务
来源：http://dali.jqgufenzy.top/Article/details/gtjotkeeoh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gotoacloud.top/Article/details/gteelivkxh.html

[R37] 把输出赋给变量
来源：http://dali.sweek.top/Article/details/gtdlzqvktx.html

files=$(ls -1)
来源：http://dali.jyoumei.cn/Article/details/gtkyrdnrkp.html

[R38] 管道串联
来源：http://dali.jiagoushi.top/Article/details/gtttvijsqa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gotoacloud.top/Article/details/gtospbkeur.html

[R39] 重定向标准输出与错误
来源：http://dali.wangdashe.top/Article/details/gthemttnto.html

cmd > out.log 2>&1
来源：http://dali.yj202588.top/Article/details/gtihqvltsg.html

[R40] 追加写日志
来源：http://dali.zhengqikj.top/Article/details/gtnhzxjdlt.html

echo "log" >> out.log
来源：http://dali.hnxiangtu.top/Article/details/gtqsuzpeqi.html

[R41] 丢弃输出
来源：http://dali.zdqjudy.top/Article/details/gtyzyegdjb.html


<!-- 参考信息 -->