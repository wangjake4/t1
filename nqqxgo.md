代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gogol.net.cn/Article/details/gt2dowsgful.html

);
来源：http://dali.cheryme.top/Article/details/gt2nylfwriq.html

[Q02] 创建带外键的表
来源：http://dali.yongpay.top/Article/details/gt2zenbfile.html

CREATE TABLE orders (
来源：http://dali.tian-w.cn/Article/details/gt2inwljpic.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yanxiufei.cn/Article/details/gt2rlmczkjb.html

user_id INT NOT NULL,
来源：http://dali.fzhhl.top/Article/details/gt2ykmqjauu.html

amount DECIMAL(10, 2),
来源：http://dali.hongshengwenyu.top/Article/details/gt2wfgvbmdp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ydzc1.top/Article/details/gt2gshgxdow.html

);
来源：http://dali.jinqigufen.top/Article/details/gt2epdarzrb.html

[Q03] 增加列
来源：http://dali.xylfe.cn/Article/details/gt2pomcztuc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.316326.xyz/Article/details/gt2ztcqmwxe.html

[Q04] 修改列类型
来源：http://dali.yvedp.cn/Article/details/gt2bftlsmer.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hfpthk.cn/Article/details/gt2mpalacsh.html

[Q05] 重命名列
来源：http://dali.yj202588.top/Article/details/gt2ilyqfmfj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xylfe.cn/Article/details/gt2bfjqqtqs.html

[Q06] 删除列
来源：http://dali.hfpthk.cn/Article/details/gt2fmwgflfl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ryfrnldl.html

[Q07] 删除表
来源：http://dali.yj20258.top/Article/details/gt2dlezejcc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.9152youxi.cn/Article/details/gt2oykubnmv.html

[Q08] 创建普通索引
来源：http://dali.wangshuangyany.cn/Article/details/gt2rhettupb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.svipenyu.cn/Article/details/gt2fhnsjyyg.html

[Q09] 创建唯一索引
来源：http://dali.hnqzz.top/Article/details/gt2pzosjipx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxinkj.top/Article/details/gt2fpkzxxdt.html

[Q10] 插入单行
来源：http://dali.yangfankeji.com/Article/details/gt2evkzaydi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shuidangran.top/Article/details/gt2gmcynvss.html

[Q11] 一次插入多行
来源：http://dali.pycfn.com/Article/details/gt2tiojkefk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gt2cltgoslw.html

[Q12] 插入后取自增 ID
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2agvrarjq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cdnleiting.top/Article/details/gt2zzbsbzjk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.mhx1999.top/Article/details/gt2gmlqgtmx.html

[Q13] 忽略重复插入
来源：http://dali.jinqigfzy.top/Article/details/gt2zisrvrvl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gt2tverwnqe.html

[Q14] 存在则更新（upsert）
来源：http://dali.quarkkingdee.top/Article/details/gt2gnnbgvty.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenlongwang.top/Article/details/gt2sekunkhm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yj20258.top/Article/details/gt2xgqkvcxx.html

[Q15] 查询全部
来源：http://dali.quarkkingdee.top/Article/details/gt2mfftpfyw.html

SELECT * FROM users;
来源：http://dali.birdmap.top/Article/details/gt2yufxrfdd.html

[Q16] 查询指定列
来源：http://dali.gogol.net.cn/Article/details/gt2pqsklize.html

SELECT id, name FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2auytrhqh.html

[Q17] 条件查询
来源：http://dali.cdnleiting.top/Article/details/gt2veaqeqfz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.iojbl.cn/Article/details/gt2sxmyqywi.html

[Q18] 模糊匹配
来源：http://dali.havefunace.top/Article/details/gt2avmwksns.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jiagoushi.top/Article/details/gt2qsdczrzi.html

[Q19] 范围查询
来源：http://dali.havefunace.top/Article/details/gt2kerfhsrl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jqgfzy.top/Article/details/gt2kwdsdppa.html

[Q20] IN 列表
来源：http://dali.yj202588.top/Article/details/gt2zdypfyvz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hfpthk.cn/Article/details/gt2uwvptkca.html

[Q21] 空值判断
来源：http://dali.andypj.xyz/Article/details/gt2gimdunfu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cqqwz.cn/Article/details/gt2xzchcxwb.html

[Q22] 排序
来源：http://dali.zhoulong.xyz/Article/details/gt2vdjevbmr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.redwolf501.top/Article/details/gt2icuiyebe.html

[Q23] 分页
来源：http://dali.ivvv.top/Article/details/gt2ncpxowkw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hnxiangtu.top/Article/details/gt2zjwcdipm.html

[Q24] 去重
来源：http://dali.chenlongwang.top/Article/details/gt2vohmbjfy.html

SELECT DISTINCT city FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2kugsbfwc.html

[Q25] 只取前 N 条
来源：http://dali.yuxming.cn/Article/details/gt2zxgbnoyh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jqgufenzy.top/Article/details/gt2uocdjjom.html

[Q26] 计数
来源：http://dali.andypj.xyz/Article/details/gt2pyqpwtyf.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2mogjfgzn.html

[Q27] 条件计数
来源：http://dali.yongpay.top/Article/details/gt2zavgqocm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2jzdncecz.html

[Q28] 求和与平均
来源：http://dali.cashguo.top/Article/details/gt2ndkckang.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gt2tuxphits.html

[Q29] 最大最小值
来源：http://dali.redwolf501.top/Article/details/gt2hixshsht.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2qfhsbmfi.html

[Q30] 分组统计
来源：http://dali.yangfankeji.com/Article/details/gt2rkcwpumb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gt2krcegldo.html

[Q31] 分组后过滤
来源：http://dali.meibo888.top/Article/details/gt2yrlylydb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gaohongyu789.top/Article/details/gt2acrdajhx.html

[Q32] 分组拼接字符串
来源：http://dali.nwbrower.top/Article/details/gt2enisbdqp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gt2hlbnpnna.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.vqdsnc.cn/Article/details/gt2oqvatkjs.html

[Q33] 多列分组
来源：http://dali.kuanghao11.cn/Article/details/gt2zhvmjzyt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.meibo888.top/Article/details/gt2xpesyzda.html

[Q34] 每组取第一条
来源：http://dali.316326.xyz/Article/details/gt2ljskiomv.html

SELECT * FROM (
来源：http://dali.hysaishi.cn/Article/details/gt2jznujdei.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cqqwz.cn/Article/details/gt2ygmkiqpv.html

) t WHERE rn = 1;
来源：http://dali.bjfxy.top/Article/details/gt2ouifyobr.html

[Q35] 内连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tdcukwlu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.snrcjt.cn/Article/details/gt2yxawdlmc.html

[Q36] 左连接
来源：http://dali.zhongyouzk.top/Article/details/gt2czcsukma.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yongpay.top/Article/details/gt2uszfpvrk.html

[Q37] 右连接
来源：http://dali.daxiang520.top/Article/details/gt2wsqfxgzp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigufen.top/Article/details/gt2ouoyesun.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sysykeji.top/Article/details/gt2kjekhkwp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fzhhl.top/Article/details/gt2shhxwkej.html

[Q39] 自连接（查上下级）
来源：http://dali.yuxming.cn/Article/details/gt2pvwbxpek.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xuetiantiany.cn/Article/details/gt2wyimqyzj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.svipenyu.cn/Article/details/gt2hcivieac.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hnxiangtu.top/Article/details/gt2uodcajqi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hongshengwenyu.top/Article/details/gt2qqgsddca.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjjacgj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.snrcjt.cn/Article/details/gt2urxasjud.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jyoumei.cn/Article/details/gt2elcbtpup.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.andypj.xyz/Article/details/gt2udgwgvuv.html

[Q42] 连接条件附加过滤
来源：http://dali.hongshengwenyu.top/Article/details/gt2nevxlfmx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.0kj1m.cn/Article/details/gt2cikvlris.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258.top/Article/details/gt2zuyrlldq.html

[Q43] 标量子查询
来源：http://dali.shuidangran.top/Article/details/gt2jwruuefr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jiagoushi.top/Article/details/gt2zxmddroq.html

[Q44] IN 子查询
来源：http://dali.smart0.xyz/Article/details/gt2yzwwbjel.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ybcxt.top/Article/details/gt2babaqgnl.html

[Q45] EXISTS 判断存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xemfacww.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258.top/Article/details/gt2mbpkvmrj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.mhx1999.top/Article/details/gt2xnhzwnbq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daxiang520.top/Article/details/gt2urypnxhu.html

[Q47] 与平均值比较
来源：http://dali.jyoumei.cn/Article/details/gt2mtycdmeo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shangyingyoupin.top/Article/details/gt2swlioyqm.html

[Q48] CTE 公用表表达式
来源：http://dali.chenjidiqi.icu/Article/details/gt2murzvpwz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.316326.xyz/Article/details/gt2vipzdbzz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hnxiangtu.top/Article/details/gt2snikulpn.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kgesypxr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.snrcjt.cn/Article/details/gt2zczekfcq.html

[Q50] 批量更新
来源：http://dali.shzxlz.cn/Article/details/gt2undmtmwe.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gzhubu.top/Article/details/gt2ysmiwwjw.html

[Q51] 用子查询更新
来源：http://dali.yanxiufei.cn/Article/details/gt2dgoqeioh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.fengsongda.top/Article/details/gt2pxsixhzo.html

[Q52] 删除指定行
来源：http://dali.gaohongyu789.top/Article/details/gt2nqmtfaht.html

DELETE FROM users WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gt2svgvzpdf.html

[Q53] 按条件删除
来源：http://dali.yueranfly.top/Article/details/gt2zpcbprqx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.quarkkingdee.top/Article/details/gt2jbdclldu.html

[Q54] 清空表
来源：http://dali.jqgfzy.top/Article/details/gt2dfqjbusb.html

TRUNCATE TABLE logs;
来源：http://dali.tianlin.xyz/Article/details/gt2rxwbzlwd.html

[Q55] 排名（并列占位）
来源：http://dali.jlsjyb.cn/Article/details/gt2urykjoun.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hammf.cn/Article/details/gt2vyvtdqye.html

[Q56] 密集排名（并列不占位）
来源：http://dali.iojbl.cn/Article/details/gt2hoeelfir.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ydzc1.top/Article/details/gt2ssdnrsnh.html

[Q57] 行号
来源：http://dali.jinqigufen.top/Article/details/gt2ecwvmrxw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2qofvacfh.html

[Q58] 累计求和
来源：http://dali.hammf.cn/Article/details/gt2vlthibac.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gt2xtsgloot.html

[Q59] 分组内累计
来源：http://dali.wangdashe.top/Article/details/gt2ieemfpup.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2qcrqujso.html

[Q60] 取上一行 / 下一行
来源：http://dali.snrcjt.cn/Article/details/gt2esffysum.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.kuanghao11.cn/Article/details/gt2wyocgkpa.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2qmnzbzcx.html

[Q61] 移动平均
来源：http://dali.daxiang520.top/Article/details/gt2zpmkfueq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2kmpqoxyu.html

[Q62] 分组占比
来源：http://dali.jianghu66.top/Article/details/gt2wyusszni.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gt2phtwypmf.html

[Q63] 开启事务
来源：http://dali.ppjwa.cn/Article/details/gt2xpmwpehr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ehwqpu.com/Article/details/gt2zcghwkxr.html

[Q64] 提交事务
来源：http://dali.feifeiyinyue.top/Article/details/gt2qbvnwoln.html

COMMIT;
来源：http://dali.jqgufenzy.top/Article/details/gt2desmxurn.html

[Q65] 回滚事务
来源：http://dali.shzxlz.cn/Article/details/gt2wwgkgjdb.html

ROLLBACK;
来源：http://dali.redwolf501.top/Article/details/gt2togucoki.html

[Q66] 行锁查询
来源：http://dali.9152youxi.cn/Article/details/gt2gquckeph.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.birdmap.top/Article/details/gt2zjgqzlmh.html

[Q67] 设置隔离级别
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ookwivso.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxuanxn.top/Article/details/gt2ykzspkyc.html

[Q68] 保存点
来源：http://dali.chenzaomai.com/Article/details/gt2spuzymxg.html

SAVEPOINT sp1;
来源：http://dali.tian-w.cn/Article/details/gt2zhsaupvb.html

ROLLBACK TO sp1;
来源：http://dali.daria6918.cn/Article/details/gt2txczbjps.html

[Q69] 查看执行计划
来源：http://dali.chenlongwang.top/Article/details/gt2xchyxfnq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nanxuanxn.top/Article/details/gt2rtwzsiik.html

[Q70] 更新统计信息
来源：http://dali.zhixingplan.top/Article/details/gt2vsekdvna.html

ANALYZE TABLE users;
来源：http://dali.jinqigufen.top/Article/details/gt2ltqargif.html

[Q71] 查看建表语句
来源：http://dali.jlsjyb.cn/Article/details/gt2cadcioih.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgufenzy.top/Article/details/gt2arslogza.html

[Q72] 查看索引
来源：http://dali.kuanghao11.cn/Article/details/gt2vptxmexu.html

SHOW INDEX FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2crolixxo.html

[Q73] 查看表状态
来源：http://dali.birdmap.top/Article/details/gt2wtsghdro.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yueranfly.top/Article/details/gt2pcifeiji.html

[Q74] 强制使用索引
来源：http://dali.aibaodan.cn/Article/details/gt2hqxidzyw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nanxuanxn.top/Article/details/gt2adgcsxuz.html

[Q75] 日期格式化
来源：http://dali.jianghu66.top/Article/details/gt2zvkpmopi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cucudq.cn/Article/details/gt2thiqkcfm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hywenlv.cn/Article/details/gt2zmmxoxjb.html

[Q76] 按天统计
来源：http://dali.chenjidiqi.icu/Article/details/gt2wsmzwzmg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gzhubu.top/Article/details/gt2ilocnmbz.html

[Q77] 时间加减
来源：http://dali.jiagoushi.top/Article/details/gt2cneetrxr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cdnleiting.top/Article/details/gt2ykyhtjru.html

[Q78] 当前时间
来源：http://dali.cashguo.top/Article/details/gt2fysjfjbj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yanxiufei.cn/Article/details/gt2bzhtpyos.html

[Q79] 字符串拼接
来源：http://dali.daria6918.cn/Article/details/gt2sqicasad.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.haohaochexian.top/Article/details/gt2cbaclhig.html

[Q80] 字符串截取
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hzchywtm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2abarhehc.html

[Q81] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gt2qdrjizwv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2cdviszkr.html

[Q82] 字符长度与字节长度
来源：http://dali.xinyue.icu/Article/details/gt2yqpkexjc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ilzutwmz.html

[Q83] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gt2ylrcgszj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gt2ofbbqlyy.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2iocpxnwr.html

SELECT TRIM(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2qbcjagow.html

[Q85] 数值取整
来源：http://dali.redwolf501.top/Article/details/gt2frcyecha.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shuidangran.top/Article/details/gt2guwleddb.html

[Q86] 读取 JSON 字段
来源：http://dali.yonumen.top/Article/details/gt2nbzdiuyd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fzhhl.top/Article/details/gt2zagorvnd.html

[Q87] JSON 字段做条件
来源：http://dali.hnqzz.top/Article/details/gt2hbtbtdvn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ppjwa.cn/Article/details/gt2awxgmmfj.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenjidiqi.icu/Article/details/gt2vcjcavuc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guowangkeji.top/Article/details/gt2lmyyzfas.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2xnsfqkbm.html

[Q89] 判断表是否存在
来源：http://dali.yvedp.cn/Article/details/gt2qnvjuxrg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.smart0.xyz/Article/details/gt2fmwggooz.html

[Q90] 生成序号列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vfqbfmtr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangdashe.top/Article/details/gt2oxyypcxq.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2cxtzufsy.html

R. Bash 专题
来源：http://dali.daxiang520.top/Article/details/gt2lkpbkbix.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2agapoaei.html

[R01] shebang 与严格模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ncpvohlh.html

#!/usr/bin/env bash
来源：http://dali.hongshengwenyu.top/Article/details/gt2rujpsgnf.html

set -euo pipefail
来源：http://dali.zdqjudy.top/Article/details/gt2dqfzkjob.html

[R02] 变量赋值与使用
来源：http://dali.hysaishi.cn/Article/details/gt2jzlgnwxd.html

name="Tom"; echo "$name"
来源：http://dali.c1oappe.top/Article/details/gt2tctvknpr.html

[R03] 只读变量
来源：http://dali.316326.xyz/Article/details/gt2cgbspbep.html

readonly PI=3.14
来源：http://dali.kuanghao11.cn/Article/details/gt2afocaylk.html

[R04] 位置参数
来源：http://dali.ydzc1.top/Article/details/gt2wvzfubtu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hammf.cn/Article/details/gt2fqusklai.html

[R05] 参数默认值
来源：http://dali.meibo888.top/Article/details/gt2tecqtpbt.html

name="${1:-default}"
来源：http://dali.ehwqpu.com/Article/details/gt2ezhhmvim.html

[R06] 判断命令是否存在
来源：http://dali.ivvv.top/Article/details/gt2oiefhhsa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.fzhhl.top/Article/details/gt2aebefngy.html

[R07] if 判断文件
来源：http://dali.ehwqpu.com/Article/details/gt2jsmyfjnp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigufen.top/Article/details/gt2mhhjpqhj.html

[R08] 数值比较
来源：http://dali.jinqigfzy.top/Article/details/gt2ppsecqbv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ppjwa.cn/Article/details/gt2wmahovcw.html

[R09] 字符串比较
来源：http://dali.yueranfly.top/Article/details/gt2jdsqzack.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jlsjyb.cn/Article/details/gt2rvbtswds.html

[R10] 正则匹配
来源：http://dali.jqgfzy.top/Article/details/gt2thaacpfm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgufenzy.top/Article/details/gt2gghbmklv.html

[R11] case 多分支
来源：http://dali.tian-w.cn/Article/details/gt2naxijfmr.html

case "$1" in
来源：http://dali.gotoacloud.top/Article/details/gt2akspscwc.html

start) echo "启动" ;;
来源：http://dali.chenlongwang.top/Article/details/gt2isduxrsv.html

stop)  echo "停止" ;;
来源：http://dali.jinqigufen.top/Article/details/gt2qxtxluft.html

*)     echo "未知命令" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2svqomvmb.html

esac
来源：http://dali.ehwqpu.com/Article/details/gt2jylkmnjp.html

[R12] for 遍历文件
来源：http://dali.xinyue.icu/Article/details/gt2oitktbmq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhixingplan.top/Article/details/gt2lacjcupm.html

[R13] for 计数循环
来源：http://dali.smart0.xyz/Article/details/gt2tcqtbpcs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.fzhhl.top/Article/details/gt2jtucsmpz.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2chworzth.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gt2lomxeslq.html

[R15] while 逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gt2vjdqhqge.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.iojbl.cn/Article/details/gt2nmkiimne.html

[R16] until 等待条件
来源：http://dali.zhoulong.xyz/Article/details/gt2qobijddp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gt2xpqrykyo.html

[R17] 数组定义与取值
来源：http://dali.yvedp.cn/Article/details/gt2mfrvubzl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.andypj.xyz/Article/details/gt2mktgulbh.html

[R18] 遍历数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2oxeavdoy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lhpityvv.html

[R19] 数组长度
来源：http://dali.xinyue.icu/Article/details/gt2bqwngzah.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvndylnj.html

[R20] 关联数组（字典）
来源：http://dali.daxiang520.top/Article/details/gt2wreofvpl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pqdzweem.html

[R21] 字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vlriyeoi.html

echo "${#s}"
来源：http://dali.cashguo.top/Article/details/gt2xubekfmd.html

[R22] 截取子串
来源：http://dali.xuetiantiany.cn/Article/details/gt2syprtlqm.html

echo "${s:0:5}"
来源：http://dali.yuanzhike.top/Article/details/gt2poneqivh.html

[R23] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ketvqsog.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.smart0.xyz/Article/details/gt2ymfatudv.html

[R24] 大小写转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mbrhizvm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yonumen.top/Article/details/gt2oiusvzwx.html

[R25] 去后缀 / 去前缀
来源：http://dali.xinyue.icu/Article/details/gt2hviifwck.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhixingplan.top/Article/details/gt2xuyjvuee.html

[R26] 命令替换
来源：http://dali.dashuyun.cn/Article/details/gt2kysjkamh.html

now=$(date +%F); echo "$now"
来源：http://dali.hnqzz.top/Article/details/gt2qroebceh.html

[R27] 算术展开
来源：http://dali.jinqigfzy.top/Article/details/gt2ikddygbf.html

echo $((1 + 2 * 3))
来源：http://dali.yangfankeji.com/Article/details/gt2ygzhohrj.html

[R28] 浮点运算
来源：http://dali.havefunace.top/Article/details/gt2fszlijoh.html

echo "scale=2; 10/3" | bc
来源：http://dali.tian-w.cn/Article/details/gt2aligyaur.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cmizekyn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2twfcffhe.html

[R30] 函数返回状态码
来源：http://dali.tanke756.top/Article/details/gt2mccmemcq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.redwolf501.top/Article/details/gt2llmkdqhm.html

[R31] 局部变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2oycjevgk.html

f() { local x=1; echo "$x"; }
来源：http://dali.tanke756.top/Article/details/gt2jxrtcumk.html

[R32] 参数个数校验
来源：http://dali.9152youxi.cn/Article/details/gt2icnikdyo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gt2eqtsmbmn.html

[R33] 捕获错误并提示行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ysudawes.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.birdmap.top/Article/details/gt2vbbedzoy.html

[R34] 退出时清理
来源：http://dali.yangfankeji.com/Article/details/gt2mrqqlxvo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2csfetapv.html

[R35] 后台执行并等待
来源：http://dali.jiagoushi.top/Article/details/gt2ksjgxypz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gaohongyu789.top/Article/details/gt2jfmhfljo.html

[R36] 并发执行多个任务
来源：http://dali.jlsjyb.cn/Article/details/gt2xvpzbkrg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jqgfzy.top/Article/details/gt2qvorvbtr.html

[R37] 把输出赋给变量
来源：http://dali.wangdashe.top/Article/details/gt2pfpnaujh.html

files=$(ls -1)
来源：http://dali.tanke756.top/Article/details/gt2smyyddyw.html

[R38] 管道串联
来源：http://dali.nanxuanxn.top/Article/details/gt2keaszgst.html

cat a.txt | grep -i error | wc -l
来源：http://dali.redwolf501.top/Article/details/gt2tbtomxjo.html

[R39] 重定向标准输出与错误
来源：http://dali.haohaochexian.top/Article/details/gt2gpxqeqnl.html

cmd > out.log 2>&1
来源：http://dali.feifeiyinyue.top/Article/details/gt2iddurfiz.html

[R40] 追加写日志
来源：http://dali.feifeiyinyue.top/Article/details/gt2eccnwata.html

echo "log" >> out.log
来源：http://dali.jyoumei.cn/Article/details/gt2xcxkowhs.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2abbpnykq.html

cmd >/dev/null 2>&1
来源：http://dali.ppjwa.cn/Article/details/gt2gnavazjn.html

[R42] 输入重定向
来源：http://dali.wangdashe.top/Article/details/gt2vsmmyove.html

wc -l < a.txt
来源：http://dali.tian-w.cn/Article/details/gt2jdhpclpu.html

[R43] 按名字查找文件
来源：http://dali.yangfankeji.com/Article/details/gt2fjywcupc.html

find . -name "*.log" -type f
来源：http://dali.cashguo.top/Article/details/gt2ugfjalnp.html

[R44] 按修改时间查找
来源：http://dali.yvedp.cn/Article/details/gt2nhbaoorw.html

find . -mtime -7 -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qftbidfe.html

[R45] 批量删除
来源：http://dali.hnqzz.top/Article/details/gt2snfdhyms.html

find . -name "*.tmp" -delete
来源：http://dali.guannengcc.top/Article/details/gt2knmvegyd.html

[R46] 递归替换文件内容
来源：http://dali.smart0.xyz/Article/details/gt2yfdbqohw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.0kj1m.cn/Article/details/gt2vmdbsqnp.html

[R47] sed 单行替换
来源：http://dali.c1oappe.top/Article/details/gt2kqjuazhu.html


<!-- 参考信息 -->