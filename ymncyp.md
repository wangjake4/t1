代发 wailian999

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.c1oappe.top/Article/details/gt2offgibuy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.9152youxi.cn/Article/details/gt2dngifmgk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.fzhhl.top/Article/details/gt2ywqqmwse.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yuanzhike.top/Article/details/gt2koyykeaw.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2tlsnahrv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yonumen.top/Article/details/gt2afrkkwon.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2xdupezhm.html

[Q01] 创建表
来源：http://dali.fengsongda.top/Article/details/gt2wjjcbtme.html

CREATE TABLE users (
来源：http://dali.nwbrower.top/Article/details/gt2tiuvlgug.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuetiantiany.cn/Article/details/gt2xwmslwip.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gt2szhxwnjf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.9152youxi.cn/Article/details/gt2mhjklpbm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shangyingyoupin.top/Article/details/gt2dkajdjxf.html

);
来源：http://dali.chenzaomai.com/Article/details/gt2hodssksk.html

[Q02] 创建带外键的表
来源：http://dali.cashguo.top/Article/details/gt2fnjatffz.html

CREATE TABLE orders (
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wtlkglme.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.haohaochexian.top/Article/details/gt2dyvcrjud.html

user_id INT NOT NULL,
来源：http://dali.hysaishi.cn/Article/details/gt2qxkhotkb.html

amount DECIMAL(10, 2),
来源：http://dali.jlsjyb.cn/Article/details/gt2jisgjvbz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.pycfn.com/Article/details/gt2hppgihhh.html

);
来源：http://dali.gogol.net.cn/Article/details/gt2ncuogbrq.html

[Q03] 增加列
来源：http://dali.daria6918.cn/Article/details/gt2wmbdefzj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ppjwa.cn/Article/details/gt2duetaiku.html

[Q04] 修改列类型
来源：http://dali.gaohongyu789.top/Article/details/gt2pnsmrhhl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.dianchejie.cn/Article/details/gt2xhceitcy.html

[Q05] 重命名列
来源：http://dali.jinqigufen.top/Article/details/gt2mqcoedaj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.c1oappe.top/Article/details/gt2zcgiqplu.html

[Q06] 删除列
来源：http://dali.xinyue.icu/Article/details/gt2orlgcvdw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj202588.top/Article/details/gt2trubxxil.html

[Q07] 删除表
来源：http://dali.zdqjudy.top/Article/details/gt2wwldaxiw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.svipenyu.cn/Article/details/gt2vulwhymg.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zunvvwxj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.kuanghao11.cn/Article/details/gt2tjgnyfuj.html

[Q09] 创建唯一索引
来源：http://dali.chenjidiqi.icu/Article/details/gt2iyxkkqcj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gt2cjunoakd.html

[Q10] 插入单行
来源：http://dali.ppjwa.cn/Article/details/gt2gahlctqq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cqqwz.cn/Article/details/gt2qrppnxac.html

[Q11] 一次插入多行
来源：http://dali.yonumen.top/Article/details/gt2jcekfdgr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ehwqpu.com/Article/details/gt2qqbmmomi.html

[Q12] 插入后取自增 ID
来源：http://dali.jyoumei.cn/Article/details/gt2uianuduc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xinyue.icu/Article/details/gt2okrgkqvn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nanxuanxn.top/Article/details/gt2uvgnvdmk.html

[Q13] 忽略重复插入
来源：http://dali.zhiwuduotai.top/Article/details/gt2nkmmijsb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xylfe.cn/Article/details/gt2lkqoclxq.html

[Q14] 存在则更新（upsert）
来源：http://dali.birdmap.top/Article/details/gt2ordanosl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jlsjyb.cn/Article/details/gt2zffqfyws.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.havefunace.top/Article/details/gt2rvwubcva.html

[Q15] 查询全部
来源：http://dali.chenjidiqi.icu/Article/details/gt2epnoquvo.html

SELECT * FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2eiqabznz.html

[Q16] 查询指定列
来源：http://dali.tianlin.xyz/Article/details/gt2iqhljjcl.html

SELECT id, name FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2nqeqwnyf.html

[Q17] 条件查询
来源：http://dali.pengpengdd.cyou/Article/details/gt2ynafsitm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2xieviqoh.html

[Q18] 模糊匹配
来源：http://dali.tian-w.cn/Article/details/gt2hmdjgpsd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.wangdashe.top/Article/details/gt2eqyqneqz.html

[Q19] 范围查询
来源：http://dali.yvedp.cn/Article/details/gt2lswrvpsl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnqzz.top/Article/details/gt2fufoohcu.html

[Q20] IN 列表
来源：http://dali.yueranfly.top/Article/details/gt2ataflsph.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.haohaochexian.top/Article/details/gt2umowhugi.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2izpxuvlo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fzhhl.top/Article/details/gt2ihmnijlg.html

[Q22] 排序
来源：http://dali.ivvv.top/Article/details/gt2osnisrcj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.guowangkeji.top/Article/details/gt2sqbzwbxt.html

[Q23] 分页
来源：http://dali.bjfxy.top/Article/details/gt2auteiukr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.aibaodan.cn/Article/details/gt2cmrmhzly.html

[Q24] 去重
来源：http://dali.shuidangran.top/Article/details/gt2ujcqehnb.html

SELECT DISTINCT city FROM users;
来源：http://dali.tanke756.top/Article/details/gt2crkczspw.html

[Q25] 只取前 N 条
来源：http://dali.iojbl.cn/Article/details/gt2otmznwij.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.haohaochexian.top/Article/details/gt2deklwfhs.html

[Q26] 计数
来源：http://dali.zhongyouzk.top/Article/details/gt2boyjhaen.html

SELECT COUNT(*) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2ezzhzelb.html

[Q27] 条件计数
来源：http://dali.xziqi.cn/Article/details/gt2lmdlcpuy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2stffxnww.html

[Q28] 求和与平均
来源：http://dali.zhiwuduotai.top/Article/details/gt2tqneqhim.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2debbfolk.html

[Q29] 最大最小值
来源：http://dali.tianlin.xyz/Article/details/gt2jbgtezda.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2ddimbtao.html

[Q30] 分组统计
来源：http://dali.cashguo.top/Article/details/gt2xawfsrub.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gt2notjkzdg.html

[Q31] 分组后过滤
来源：http://dali.jqgufenzy.top/Article/details/gt2mkctvsaq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.bjfxy.top/Article/details/gt2tkebypzj.html

[Q32] 分组拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gt2hdzyxsva.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gt2tkzzkqnv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yangfankeji.com/Article/details/gt2xipqnwpd.html

[Q33] 多列分组
来源：http://dali.zhixingplan.top/Article/details/gt2utivhekm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jpzhukkv.html

[Q34] 每组取第一条
来源：http://dali.yuanzhike.top/Article/details/gt2imoaixug.html

SELECT * FROM (
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2voyfbjsi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhengqikj.top/Article/details/gt2szxvrtbu.html

) t WHERE rn = 1;
来源：http://dali.fengsongda.top/Article/details/gt2xzqgsybt.html

[Q35] 内连接
来源：http://dali.haohaochexian.top/Article/details/gt2ehdxmeqw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hywenlv.cn/Article/details/gt2ddqjihjq.html

[Q36] 左连接
来源：http://dali.zhengqikj.top/Article/details/gt2vywolixb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gt2ekxqcned.html

[Q37] 右连接
来源：http://dali.redwolf501.top/Article/details/gt2baakpsav.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ernviheu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yonumen.top/Article/details/gt2abgwkiip.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.iojbl.cn/Article/details/gt2qbfjevxs.html

[Q39] 自连接（查上下级）
来源：http://dali.chenzaomai.com/Article/details/gt2zgjkjivs.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hammf.cn/Article/details/gt2pwnmphaq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hammf.cn/Article/details/gt2vqknacau.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hysaishi.cn/Article/details/gt2lcgeqxle.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nanxinkj.top/Article/details/gt2dzmvhcnc.html

[Q41] 多表连接
来源：http://dali.chenzaomai.com/Article/details/gt2cyafwdug.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jlsjyb.cn/Article/details/gt2skahpxkw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xinyue.icu/Article/details/gt2mrmdvvqv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hongshengwenyu.top/Article/details/gt2lrlmmvgy.html

[Q42] 连接条件附加过滤
来源：http://dali.gogol.net.cn/Article/details/gt2vfjelini.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhixingplan.top/Article/details/gt2iqihxtsb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aibaodan.cn/Article/details/gt2wtcvnjcd.html

[Q43] 标量子查询
来源：http://dali.pengpengdd.cyou/Article/details/gt2muhxwwon.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.daria6918.cn/Article/details/gt2yumwvffw.html

[Q44] IN 子查询
来源：http://dali.pengpengdd.cyou/Article/details/gt2epjsxkdd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ajzxklwt.html

[Q45] EXISTS 判断存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vavtmumd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gt2fszonbke.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangshuangyany.cn/Article/details/gt2iraytktb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258.top/Article/details/gt2mowlwrwn.html

[Q47] 与平均值比较
来源：http://dali.sysykeji.top/Article/details/gt2facedwhs.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nanxinkj.top/Article/details/gt2camhbppl.html

[Q48] CTE 公用表表达式
来源：http://dali.dianchejie.cn/Article/details/gt2jvsrqfly.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuxming.cn/Article/details/gt2qejyfvbc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hnxiangtu.top/Article/details/gt2ahgyfzsr.html

[Q49] 更新单行
来源：http://dali.aibaodan.cn/Article/details/gt2phvvjkck.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gt2eqegdcoh.html

[Q50] 批量更新
来源：http://dali.jqgfzy.top/Article/details/gt2gccdjfnz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gogol.net.cn/Article/details/gt2vjsqftwm.html

[Q51] 用子查询更新
来源：http://dali.nanxinkj.top/Article/details/gt2yozndjkq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2ajdxexch.html

[Q52] 删除指定行
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yjbvnmqs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nwbrower.top/Article/details/gt2huymbarp.html

[Q53] 按条件删除
来源：http://dali.c1oappe.top/Article/details/gt2rmvcsqdx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhixingplan.top/Article/details/gt2hworniyu.html

[Q54] 清空表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2afvqcfqc.html

TRUNCATE TABLE logs;
来源：http://dali.nanxinkj.top/Article/details/gt2pxmczrpt.html

[Q55] 排名（并列占位）
来源：http://dali.tanke756.top/Article/details/gt2uxxljxso.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gt2ctwasefn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ybcxt.top/Article/details/gt2sbwgtagi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenjidiqi.icu/Article/details/gt2aurkvfpm.html

[Q57] 行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zfbtfdlb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2jowrcopg.html

[Q58] 累计求和
来源：http://dali.redwolf501.top/Article/details/gt2sollyheq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ycrdumhf.html

[Q59] 分组内累计
来源：http://dali.kuanghao11.cn/Article/details/gt2jpjzgpto.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gt2oxazcfiu.html

[Q60] 取上一行 / 下一行
来源：http://dali.hysaishi.cn/Article/details/gt2pwvaiggt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.smart0.xyz/Article/details/gt2apfxodvy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gt2kmamwfvp.html

[Q61] 移动平均
来源：http://dali.hysaishi.cn/Article/details/gt2tndzheob.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cheryme.top/Article/details/gt2duluabxs.html

[Q62] 分组占比
来源：http://dali.hysaishi.cn/Article/details/gt2xcxkespp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gt2wizxxnzi.html

[Q63] 开启事务
来源：http://dali.hnxiangtu.top/Article/details/gt2fwhvauau.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fzhhl.top/Article/details/gt2zxltdhde.html

[Q64] 提交事务
来源：http://dali.smart0.xyz/Article/details/gt2jqnqhaxv.html

COMMIT;
来源：http://dali.yangfankeji.com/Article/details/gt2zcxfubgd.html

[Q65] 回滚事务
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xusplken.html

ROLLBACK;
来源：http://dali.yj20258.top/Article/details/gt2smlzknxz.html

[Q66] 行锁查询
来源：http://dali.chenlongwang.top/Article/details/gt2wkarjvjb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gzhubu.top/Article/details/gt2tsqgonmq.html

[Q67] 设置隔离级别
来源：http://dali.cucudq.cn/Article/details/gt2ejcohbbg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pycfn.com/Article/details/gt2brqqvxwp.html

[Q68] 保存点
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2taxtihze.html

SAVEPOINT sp1;
来源：http://dali.tian-w.cn/Article/details/gt2pwukrtcj.html

ROLLBACK TO sp1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2hrjaeesp.html

[Q69] 查看执行计划
来源：http://dali.yj20258.top/Article/details/gt2trbwzxfy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hnxiangtu.top/Article/details/gt2klxhzyab.html

[Q70] 更新统计信息
来源：http://dali.zhongyouzk.top/Article/details/gt2mrrqezvl.html

ANALYZE TABLE users;
来源：http://dali.haohaochexian.top/Article/details/gt2kfdcsxsd.html

[Q71] 查看建表语句
来源：http://dali.gogol.net.cn/Article/details/gt2wkzqpydl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinqigfzy.top/Article/details/gt2reftgqok.html

[Q72] 查看索引
来源：http://dali.xinyue.icu/Article/details/gt2ehznywqt.html

SHOW INDEX FROM users;
来源：http://dali.havefunace.top/Article/details/gt2liejrfwp.html

[Q73] 查看表状态
来源：http://dali.kuanghao11.cn/Article/details/gt2wyimzydw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.vqdsnc.cn/Article/details/gt2jnujehga.html

[Q74] 强制使用索引
来源：http://dali.nanxuanxn.top/Article/details/gt2qvfmtyyf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jqgfzy.top/Article/details/gt2zsnmmwre.html

[Q75] 日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rwuitsre.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2jgfrkqzf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.svipenyu.cn/Article/details/gt2beejgkfx.html

[Q76] 按天统计
来源：http://dali.316326.xyz/Article/details/gt2rsbsjmzf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.birdmap.top/Article/details/gt2nswvgysa.html

[Q77] 时间加减
来源：http://dali.mhx1999.top/Article/details/gt2qdcywion.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xsbxstre.html

[Q78] 当前时间
来源：http://dali.jianghu66.top/Article/details/gt2iurtkbbk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hongshengwenyu.top/Article/details/gt2ubedctsr.html

[Q79] 字符串拼接
来源：http://dali.shuidangran.top/Article/details/gt2jffqhcch.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hongshengwenyu.top/Article/details/gt2sqxhpnat.html

[Q80] 字符串截取
来源：http://dali.fengsongda.top/Article/details/gt2tsunzreq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2buvkjvlw.html

[Q81] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gt2cbnguivv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2zfjuychg.html

[Q82] 字符长度与字节长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lmslinkc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2izsxlffa.html

[Q83] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gt2ebiakeov.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2eutuqtmm.html

[Q84] 去除首尾空格
来源：http://dali.zhiwuduotai.top/Article/details/gt2dytwulow.html

SELECT TRIM(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2hrxejyno.html

[Q85] 数值取整
来源：http://dali.xuanzx.com/Article/details/gt2twrbcckm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xziqi.cn/Article/details/gt2bkpvfgkk.html

[Q86] 读取 JSON 字段
来源：http://dali.nanxinkj.top/Article/details/gt2ihainuca.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nwbrower.top/Article/details/gt2roqqiruk.html

[Q87] JSON 字段做条件
来源：http://dali.xziqi.cn/Article/details/gt2vxqalosf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wbewyaor.html

[Q88] 行转列（条件聚合）
来源：http://dali.gaohongyu789.top/Article/details/gt2xmimmnge.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xziqi.cn/Article/details/gt2oevvrfdj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2mfovnwkb.html

[Q89] 判断表是否存在
来源：http://dali.yj202588.top/Article/details/gt2sgleaion.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hongshengwenyu.top/Article/details/gt2hbnfjqel.html

[Q90] 生成序号列
来源：http://dali.wangdashe.top/Article/details/gt2cnokhiim.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.pycfn.com/Article/details/gt2fndtfnip.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sgvyyamx.html

R. Bash 专题
来源：http://dali.havefunace.top/Article/details/gt2yoiseirc.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2piqxxajx.html

[R01] shebang 与严格模式
来源：http://dali.xylfe.cn/Article/details/gt2iltncncw.html

#!/usr/bin/env bash
来源：http://dali.jyoumei.cn/Article/details/gt2ciszafcc.html

set -euo pipefail
来源：http://dali.cheryme.top/Article/details/gt2xwivtqhi.html

[R02] 变量赋值与使用
来源：http://dali.redwolf501.top/Article/details/gt2duttnsgl.html

name="Tom"; echo "$name"
来源：http://dali.aizwys.cn/Article/details/gt2rqddofjb.html

[R03] 只读变量
来源：http://dali.fengsongda.top/Article/details/gt2cvwpffvc.html

readonly PI=3.14
来源：http://dali.guowangkeji.top/Article/details/gt2bwqeqjqm.html

[R04] 位置参数
来源：http://dali.dashuyun.cn/Article/details/gt2satbafds.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shangyingyoupin.top/Article/details/gt2nxpbrkgk.html

[R05] 参数默认值
来源：http://dali.aibaodan.cn/Article/details/gt2lrfqvtui.html

name="${1:-default}"
来源：http://dali.haohaochexian.top/Article/details/gt2ijypqsny.html

[R06] 判断命令是否存在
来源：http://dali.tanke756.top/Article/details/gt2bytzgvjp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinqigfzy.top/Article/details/gt2xddxwdyh.html

[R07] if 判断文件
来源：http://dali.ppjwa.cn/Article/details/gt2jmgqgupn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cdnleiting.top/Article/details/gt2uojrvgqy.html

[R08] 数值比较
来源：http://dali.jqgfzy.top/Article/details/gt2kmpszlnh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guannengcc.top/Article/details/gt2kzfmqiqk.html

[R09] 字符串比较
来源：http://dali.sysykeji.top/Article/details/gt2injjsagp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenzaomai.com/Article/details/gt2bgeliqaq.html

[R10] 正则匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2amjbzbfb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xziqi.cn/Article/details/gt2lxhsrzeg.html

[R11] case 多分支
来源：http://dali.jqgufenzy.top/Article/details/gt2revypvjo.html

case "$1" in
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dofteayz.html

start) echo "启动" ;;
来源：http://dali.yangfankeji.com/Article/details/gt2pwnfbnvi.html

stop)  echo "停止" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2davrtejz.html

*)     echo "未知命令" ;;
来源：http://dali.jlsjyb.cn/Article/details/gt2bfjtvyys.html

esac
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yitvycya.html

[R12] for 遍历文件
来源：http://dali.fzhhl.top/Article/details/gt2stbpoiks.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2igitvaqj.html

[R13] for 计数循环
来源：http://dali.yueranfly.top/Article/details/gt2rpayievt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hnqzz.top/Article/details/gt2rhqvmloe.html

[R14] C 风格 for
来源：http://dali.9152youxi.cn/Article/details/gt2kbbyytnc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nanxuanxn.top/Article/details/gt2jeadcasx.html

[R15] while 逐行读文件
来源：http://dali.hnqzz.top/Article/details/gt2grwkwyqo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zycfv.cn/Article/details/gt2jbgclgih.html

[R16] until 等待条件
来源：http://dali.hongshengwenyu.top/Article/details/gt2vlucfyoi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gt2dzvwzurn.html

[R17] 数组定义与取值
来源：http://dali.xziqi.cn/Article/details/gt2fobyulcl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pycfn.com/Article/details/gt2bdjgicvi.html

[R18] 遍历数组
来源：http://dali.dianchejie.cn/Article/details/gt2jleckuwd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sweek.top/Article/details/gt2txapkldz.html

[R19] 数组长度
来源：http://dali.chenlongwang.top/Article/details/gt2auomigsh.html

echo "${#arr[@]}"
来源：http://dali.shuidangran.top/Article/details/gt2ueputhnl.html

[R20] 关联数组（字典）
来源：http://dali.feifeiyinyue.top/Article/details/gt2owknnrnb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ybcxt.top/Article/details/gt2qpegpbrq.html

[R21] 字符串长度
来源：http://dali.316326.xyz/Article/details/gt2xdhkoqpg.html

echo "${#s}"
来源：http://dali.zdqjudy.top/Article/details/gt2potxzveo.html

[R22] 截取子串
来源：http://dali.andypj.xyz/Article/details/gt2hgbhwqqa.html

echo "${s:0:5}"
来源：http://dali.andypj.xyz/Article/details/gt2dkcxojhs.html

[R23] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gt2dmtzsptc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hywenlv.cn/Article/details/gt2berevysc.html

[R24] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gt2qcawkaxs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xziqi.cn/Article/details/gt2snglhfvj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhixingplan.top/Article/details/gt2cuwtikvz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.316326.xyz/Article/details/gt2cppwxuaf.html

[R26] 命令替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2dazqrtjy.html

now=$(date +%F); echo "$now"
来源：http://dali.daxiang520.top/Article/details/gt2usjjrnwh.html

[R27] 算术展开
来源：http://dali.mhx1999.top/Article/details/gt2wbeazeom.html

echo $((1 + 2 * 3))
来源：http://dali.gzhubu.top/Article/details/gt2wlwcoevf.html

[R28] 浮点运算
来源：http://dali.xziqi.cn/Article/details/gt2xyysqheg.html

echo "scale=2; 10/3" | bc
来源：http://dali.9152youxi.cn/Article/details/gt2wojfgeuy.html

[R29] 定义函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vhrcroee.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.pengpengdd.cyou/Article/details/gt2tshitsda.html

[R30] 函数返回状态码
来源：http://dali.hfpthk.cn/Article/details/gt2gfwftjrn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hnqzz.top/Article/details/gt2xdyxhost.html

[R31] 局部变量
来源：http://dali.chenlongwang.top/Article/details/gt2gpiijuzo.html

f() { local x=1; echo "$x"; }
来源：http://dali.yonumen.top/Article/details/gt2mrajmzey.html

[R32] 参数个数校验
来源：http://dali.hfpthk.cn/Article/details/gt2ubnbgemv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rtxqvibs.html

[R33] 捕获错误并提示行号
来源：http://dali.jiagoushi.top/Article/details/gt2ldjblzyx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jqgufenzy.top/Article/details/gt2cztxruqv.html

[R34] 退出时清理
来源：http://dali.meibo888.top/Article/details/gt2bxdjccmw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gt2gugjjnqk.html

[R35] 后台执行并等待
来源：http://dali.meibo888.top/Article/details/gt2xhfgwoil.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenlongwang.top/Article/details/gt2vpqdsfyf.html

[R36] 并发执行多个任务
来源：http://dali.shzxlz.cn/Article/details/gt2ykzmsfzc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ogopynag.html

[R37] 把输出赋给变量
来源：http://dali.gogol.net.cn/Article/details/gt2bllcdske.html

files=$(ls -1)
来源：http://dali.jinqigufen.top/Article/details/gt2drtcitch.html

[R38] 管道串联
来源：http://dali.bjfxy.top/Article/details/gt2ltaqrhut.html

cat a.txt | grep -i error | wc -l
来源：http://dali.0kj1m.cn/Article/details/gt2uedktfab.html

[R39] 重定向标准输出与错误
来源：http://dali.pengpengdd.cyou/Article/details/gt2ponctmsf.html

cmd > out.log 2>&1
来源：http://dali.ppjwa.cn/Article/details/gt2jxlxloqv.html

[R40] 追加写日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jrszunbd.html

echo "log" >> out.log
来源：http://dali.cdnleiting.top/Article/details/gt2sbwicgai.html

[R41] 丢弃输出
来源：http://dali.jyoumei.cn/Article/details/gt2hkskwhgl.html


<!-- 参考信息 -->