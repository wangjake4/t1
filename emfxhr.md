代发 wailian999

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.vqdsnc.cn/Article/details/gt2sdtinspp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cashguo.top/Article/details/gt2xvkigwmh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ydzc1.top/Article/details/gt2dkmsljif.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jyoumei.cn/Article/details/gt2bbogzobg.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2qvhseoqb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenlongwang.top/Article/details/gt2jzunhkrp.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2gwnirqyt.html

[Q01] 创建表
来源：http://dali.c1oappe.top/Article/details/gt2qoevzwdq.html

CREATE TABLE users (
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2axopuaox.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zdqjudy.top/Article/details/gt2nfgcthye.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yuanzhike.top/Article/details/gt2dasbhahz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.pycfn.com/Article/details/gt2ofoewgxq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhongyouzk.top/Article/details/gt2fxstiddv.html

);
来源：http://dali.cdnleiting.top/Article/details/gt2wahrtwcc.html

[Q02] 创建带外键的表
来源：http://dali.havefunace.top/Article/details/gt2frpcgkbq.html

CREATE TABLE orders (
来源：http://dali.jyoumei.cn/Article/details/gt2jezgnztm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gt2ntwjuset.html

user_id INT NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gt2fhgcwwew.html

amount DECIMAL(10, 2),
来源：http://dali.zdqjudy.top/Article/details/gt2vqnyvkdl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gotoacloud.top/Article/details/gt2orevhjgu.html

);
来源：http://dali.xziqi.cn/Article/details/gt2ppklcknr.html

[Q03] 增加列
来源：http://dali.redwolf501.top/Article/details/gt2iyqbevvm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yvedp.cn/Article/details/gt2ryzzqixi.html

[Q04] 修改列类型
来源：http://dali.fengsongda.top/Article/details/gt2xoofxmcd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.wangshuangyany.cn/Article/details/gt2vulqvyho.html

[Q05] 重命名列
来源：http://dali.tanke756.top/Article/details/gt2dmklygal.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cucudq.cn/Article/details/gt2sfwhcjwi.html

[Q06] 删除列
来源：http://dali.hongshengwenyu.top/Article/details/gt2ribfwaej.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vsgggcnf.html

[Q07] 删除表
来源：http://dali.jianghu66.top/Article/details/gt2uqcucdvg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cucudq.cn/Article/details/gt2jpgrwspt.html

[Q08] 创建普通索引
来源：http://dali.jyoumei.cn/Article/details/gt2btkgwhwq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ytoedwzq.html

[Q09] 创建唯一索引
来源：http://dali.vqdsnc.cn/Article/details/gt2earnwqhk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yvedp.cn/Article/details/gt2wokumbpa.html

[Q10] 插入单行
来源：http://dali.0kj1m.cn/Article/details/gt2jjqpfdct.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.smart0.xyz/Article/details/gt2gfbmnduc.html

[Q11] 一次插入多行
来源：http://dali.c1oappe.top/Article/details/gt2rabfmxzh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gt2gzojqxmn.html

[Q12] 插入后取自增 ID
来源：http://dali.fzhhl.top/Article/details/gt2jeqviuwf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ehwqpu.com/Article/details/gt2btvqwkeo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vbsnivzg.html

[Q13] 忽略重复插入
来源：http://dali.yj20258.top/Article/details/gt2xphdkzql.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj202588.top/Article/details/gt2wpqrosgd.html

[Q14] 存在则更新（upsert）
来源：http://dali.hammf.cn/Article/details/gt2uywlwsdk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yanxiufei.cn/Article/details/gt2lvyvnvuo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yongpay.top/Article/details/gt2pptigggp.html

[Q15] 查询全部
来源：http://dali.nwbrower.top/Article/details/gt2skgilidz.html

SELECT * FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2tqlcyinm.html

[Q16] 查询指定列
来源：http://dali.zhoulong.xyz/Article/details/gt2ohbzgjlv.html

SELECT id, name FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2dbzjdwyi.html

[Q17] 条件查询
来源：http://dali.daria6918.cn/Article/details/gt2jxmfgugo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.dianchejie.cn/Article/details/gt2duhuccbj.html

[Q18] 模糊匹配
来源：http://dali.316326.xyz/Article/details/gt2fiqgetof.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenlongwang.top/Article/details/gt2yvyglizj.html

[Q19] 范围查询
来源：http://dali.hnxiangtu.top/Article/details/gt2jvbilupy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.meibo888.top/Article/details/gt2usidaqus.html

[Q20] IN 列表
来源：http://dali.aibaodan.cn/Article/details/gt2ipytbddx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guowangkeji.top/Article/details/gt2bmckzhch.html

[Q21] 空值判断
来源：http://dali.hnqzz.top/Article/details/gt2dlgbwwpq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.havefunace.top/Article/details/gt2vqrowdnw.html

[Q22] 排序
来源：http://dali.c1oappe.top/Article/details/gt2dntccgqp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.c1oappe.top/Article/details/gt2uriljiga.html

[Q23] 分页
来源：http://dali.hysaishi.cn/Article/details/gt2zilojyrv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dashuyun.cn/Article/details/gt2izonnudv.html

[Q24] 去重
来源：http://dali.nanxinkj.top/Article/details/gt2fcvcvghb.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2nbugkxpw.html

[Q25] 只取前 N 条
来源：http://dali.hongshengwenyu.top/Article/details/gt2ytjyjbjd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenzaomai.com/Article/details/gt2vaenautl.html

[Q26] 计数
来源：http://dali.zdqjudy.top/Article/details/gt2zctiqzzp.html

SELECT COUNT(*) FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2qehoahov.html

[Q27] 条件计数
来源：http://dali.hysaishi.cn/Article/details/gt2llqklgjk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2vobgdrif.html

[Q28] 求和与平均
来源：http://dali.sysykeji.top/Article/details/gt2biucgfxh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2yldupssy.html

[Q29] 最大最小值
来源：http://dali.yonumen.top/Article/details/gt2qnxgrpat.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2dqhfrrua.html

[Q30] 分组统计
来源：http://dali.hongshengwenyu.top/Article/details/gt2ofuxoalg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gt2zwzcdhft.html

[Q31] 分组后过滤
来源：http://dali.hywenlv.cn/Article/details/gt2sngifnpl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hysaishi.cn/Article/details/gt2bphfdwom.html

[Q32] 分组拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2qkvanzfn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gt2wjvkhnsq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.redwolf501.top/Article/details/gt2tmbwddgo.html

[Q33] 多列分组
来源：http://dali.chenlongwang.top/Article/details/gt2vdeemoui.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aizwys.cn/Article/details/gt2djzsetsr.html

[Q34] 每组取第一条
来源：http://dali.sxryk.cn/Article/details/gt2giuxgaxa.html

SELECT * FROM (
来源：http://dali.zhengqikj.top/Article/details/gt2yeyqttxb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xylfe.cn/Article/details/gt2opratvzd.html

) t WHERE rn = 1;
来源：http://dali.hywenlv.cn/Article/details/gt2hnztvxhk.html

[Q35] 内连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2qimdhlap.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.iojbl.cn/Article/details/gt2jngsgtba.html

[Q36] 左连接
来源：http://dali.hfpthk.cn/Article/details/gt2jwesreqz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gt2fssyyifg.html

[Q37] 右连接
来源：http://dali.xuetiantiany.cn/Article/details/gt2nvdeggti.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.fengsongda.top/Article/details/gt2evujvpnf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.smart0.xyz/Article/details/gt2lxkgleqs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cucudq.cn/Article/details/gt2ejsscrsp.html

[Q39] 自连接（查上下级）
来源：http://dali.yanxiufei.cn/Article/details/gt2aatwdzrq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.316326.xyz/Article/details/gt2lisqfvag.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2efclabjn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hnxiangtu.top/Article/details/gt2lektfwog.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hnxiangtu.top/Article/details/gt2wyuwcjhu.html

[Q41] 多表连接
来源：http://dali.daria6918.cn/Article/details/gt2otfcctna.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jyoumei.cn/Article/details/gt2oscaicsh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.snrcjt.cn/Article/details/gt2dpeaeypb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrfjkjg.html

[Q42] 连接条件附加过滤
来源：http://dali.316326.xyz/Article/details/gt2khfstvsx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.fzhhl.top/Article/details/gt2mupyofwe.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.vqdsnc.cn/Article/details/gt2pocwcifq.html

[Q43] 标量子查询
来源：http://dali.yj20258888.top/Article/details/gt2mywvtpcl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ehwqpu.com/Article/details/gt2ydipclxk.html

[Q44] IN 子查询
来源：http://dali.daria6918.cn/Article/details/gt2kadkbewu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ybcxt.top/Article/details/gt2pmcykjgg.html

[Q45] EXISTS 判断存在
来源：http://dali.sufxvd.cn/Article/details/gt2xlbocpll.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gt2apzndenu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gogol.net.cn/Article/details/gt2cbeuhcyl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daxiang520.top/Article/details/gt2dmdfdltj.html

[Q47] 与平均值比较
来源：http://dali.daxiang520.top/Article/details/gt2zagirkne.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fzhhl.top/Article/details/gt2nrivqqfy.html

[Q48] CTE 公用表表达式
来源：http://dali.tianlin.xyz/Article/details/gt2alldcyux.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.snrcjt.cn/Article/details/gt2cccgzzko.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigufen.top/Article/details/gt2txugwktt.html

[Q49] 更新单行
来源：http://dali.tanke756.top/Article/details/gt2xniafxro.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxinkj.top/Article/details/gt2ctlreieg.html

[Q50] 批量更新
来源：http://dali.jinqigfzy.top/Article/details/gt2ddkokbcb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yonumen.top/Article/details/gt2eokcxaqp.html

[Q51] 用子查询更新
来源：http://dali.havefunace.top/Article/details/gt2klkwbfyn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.iojbl.cn/Article/details/gt2tfqhiygs.html

[Q52] 删除指定行
来源：http://dali.cdnleiting.top/Article/details/gt2cwocbait.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yuanzhike.top/Article/details/gt2zbnbmwtn.html

[Q53] 按条件删除
来源：http://dali.nanxuanxn.top/Article/details/gt2rpwdvlvf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.mhx1999.top/Article/details/gt2amcyvppc.html

[Q54] 清空表
来源：http://dali.yj20258888.top/Article/details/gt2siogmynl.html

TRUNCATE TABLE logs;
来源：http://dali.yanxiufei.cn/Article/details/gt2rjddxqlc.html

[Q55] 排名（并列占位）
来源：http://dali.316326.xyz/Article/details/gt2evpehhze.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jianghu66.top/Article/details/gt2ggwpvqvd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.daria6918.cn/Article/details/gt2ccingoxp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinqigfzy.top/Article/details/gt2fjutdldf.html

[Q57] 行号
来源：http://dali.yanxiufei.cn/Article/details/gt2mtvpauoe.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2gpqvztnu.html

[Q58] 累计求和
来源：http://dali.daria6918.cn/Article/details/gt2fnmieosw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2zdllvgoy.html

[Q59] 分组内累计
来源：http://dali.cashguo.top/Article/details/gt2fzaperfe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2aycejaap.html

[Q60] 取上一行 / 下一行
来源：http://dali.daria6918.cn/Article/details/gt2jclyhjfy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hammf.cn/Article/details/gt2wiigumaw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gzhubu.top/Article/details/gt2cvlrobsf.html

[Q61] 移动平均
来源：http://dali.daria6918.cn/Article/details/gt2hpjtbxdw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gt2bfkchcjs.html

[Q62] 分组占比
来源：http://dali.dianchejie.cn/Article/details/gt2hsjfucxp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rxcjgmym.html

[Q63] 开启事务
来源：http://dali.nanxuanxn.top/Article/details/gt2wzpyncao.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cucudq.cn/Article/details/gt2fbalwpwg.html

[Q64] 提交事务
来源：http://dali.cashguo.top/Article/details/gt2teddhirn.html

COMMIT;
来源：http://dali.yvedp.cn/Article/details/gt2zvbtlhut.html

[Q65] 回滚事务
来源：http://dali.xinyue.icu/Article/details/gt2bsshnxlg.html

ROLLBACK;
来源：http://dali.jianghu66.top/Article/details/gt2uiagfoys.html

[Q66] 行锁查询
来源：http://dali.gzhubu.top/Article/details/gt2wthgqpaz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hvjllffs.html

[Q67] 设置隔离级别
来源：http://dali.nanxinkj.top/Article/details/gt2frvmrkhc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hongshengwenyu.top/Article/details/gt2rfbmnije.html

[Q68] 保存点
来源：http://dali.mhx1999.top/Article/details/gt2exektznt.html

SAVEPOINT sp1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2vctyftuw.html

ROLLBACK TO sp1;
来源：http://dali.aizwys.cn/Article/details/gt2dywtmvxm.html

[Q69] 查看执行计划
来源：http://dali.pengpengdd.cyou/Article/details/gt2wahbzcmg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.smart0.xyz/Article/details/gt2jdfyxdra.html

[Q70] 更新统计信息
来源：http://dali.zhongyouzk.top/Article/details/gt2jysygpdr.html

ANALYZE TABLE users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pccjklqx.html

[Q71] 查看建表语句
来源：http://dali.feifeiyinyue.top/Article/details/gt2bmeoatvp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhiwuduotai.top/Article/details/gt2epydprzg.html

[Q72] 查看索引
来源：http://dali.ybcxt.top/Article/details/gt2nniyanfe.html

SHOW INDEX FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2jstaaptm.html

[Q73] 查看表状态
来源：http://dali.chenjidiqi.icu/Article/details/gt2xpmylnvx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tanke756.top/Article/details/gt2xtujescn.html

[Q74] 强制使用索引
来源：http://dali.xziqi.cn/Article/details/gt2qzmasnkl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hammf.cn/Article/details/gt2wlconoqo.html

[Q75] 日期格式化
来源：http://dali.yueranfly.top/Article/details/gt2mufoguzz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2xuivsati.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.vqdsnc.cn/Article/details/gt2unbuhbmh.html

[Q76] 按天统计
来源：http://dali.mhx1999.top/Article/details/gt2qcmqvorm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangdashe.top/Article/details/gt2bolzkgxv.html

[Q77] 时间加减
来源：http://dali.jinqigfzy.top/Article/details/gt2xwhcpsyo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.9152youxi.cn/Article/details/gt2tmxhfgtg.html

[Q78] 当前时间
来源：http://dali.zdqjudy.top/Article/details/gt2rkpacliw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.andypj.xyz/Article/details/gt2ylrheidh.html

[Q79] 字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gt2esschdbp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj20258.top/Article/details/gt2uznqgpex.html

[Q80] 字符串截取
来源：http://dali.xuanzx.com/Article/details/gt2rzqjuoly.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2eygafseo.html

[Q81] 字符串替换
来源：http://dali.sweek.top/Article/details/gt2binikqzp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2qqfdcmtr.html

[Q82] 字符长度与字节长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2epoaakwj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2njjykyex.html

[Q83] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gt2hwtadmom.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2imrqtdey.html

[Q84] 去除首尾空格
来源：http://dali.aibaodan.cn/Article/details/gt2nkpyweop.html

SELECT TRIM(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2shwlpbwt.html

[Q85] 数值取整
来源：http://dali.meibo888.top/Article/details/gt2jbvoucjm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.birdmap.top/Article/details/gt2tcncifwh.html

[Q86] 读取 JSON 字段
来源：http://dali.dianchejie.cn/Article/details/gt2xstphgew.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.daxiang520.top/Article/details/gt2infsitpu.html

[Q87] JSON 字段做条件
来源：http://dali.wangdashe.top/Article/details/gt2ggetaxnp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tian-w.cn/Article/details/gt2iempqymv.html

[Q88] 行转列（条件聚合）
来源：http://dali.fzhhl.top/Article/details/gt2xissdidy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yyqvbjur.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hammf.cn/Article/details/gt2ctkszxjm.html

[Q89] 判断表是否存在
来源：http://dali.nanxinkj.top/Article/details/gt2hmsnrxhl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hongshengwenyu.top/Article/details/gt2rtfdqdrk.html

[Q90] 生成序号列
来源：http://dali.sweek.top/Article/details/gt2hntdlskx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhoulong.xyz/Article/details/gt2yuzrbzho.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2pzufwued.html

R. Bash 专题
来源：http://dali.redwolf501.top/Article/details/gt2frxdaigo.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2prnoignj.html

[R01] shebang 与严格模式
来源：http://dali.zycfv.cn/Article/details/gt2xpdythsm.html

#!/usr/bin/env bash
来源：http://dali.jinghuilouyu.cn/Article/details/gt2corapzyf.html

set -euo pipefail
来源：http://dali.zhongyouzk.top/Article/details/gt2anefzhse.html

[R02] 变量赋值与使用
来源：http://dali.birdmap.top/Article/details/gt2slhhzmfv.html

name="Tom"; echo "$name"
来源：http://dali.nwbrower.top/Article/details/gt2ttylguzq.html

[R03] 只读变量
来源：http://dali.andypj.xyz/Article/details/gt2uucntdeo.html

readonly PI=3.14
来源：http://dali.daria6918.cn/Article/details/gt2wdxxshfc.html

[R04] 位置参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nzzqctxo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ppjwa.cn/Article/details/gt2rylsipcr.html

[R05] 参数默认值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xosnkksv.html

name="${1:-default}"
来源：http://dali.hnqzz.top/Article/details/gt2fyajfwlb.html

[R06] 判断命令是否存在
来源：http://dali.cdnleiting.top/Article/details/gt2kbiaokvq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2bxfyvshv.html

[R07] if 判断文件
来源：http://dali.ehwqpu.com/Article/details/gt2eexccacg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dqbibmne.html

[R08] 数值比较
来源：http://dali.hnxiangtu.top/Article/details/gt2euaergzv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dlxihyyn.html

[R09] 字符串比较
来源：http://dali.xinyue.icu/Article/details/gt2wdqlagnb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.0kj1m.cn/Article/details/gt2buxuigla.html

[R10] 正则匹配
来源：http://dali.yangfankeji.com/Article/details/gt2chjixefj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.316326.xyz/Article/details/gt2tleufnuf.html

[R11] case 多分支
来源：http://dali.sweek.top/Article/details/gt2kderfxjq.html

case "$1" in
来源：http://dali.aibaodan.cn/Article/details/gt2jarcoolo.html

start) echo "启动" ;;
来源：http://dali.snrcjt.cn/Article/details/gt2rhcsizch.html

stop)  echo "停止" ;;
来源：http://dali.meibo888.top/Article/details/gt2jcvqfttg.html

*)     echo "未知命令" ;;
来源：http://dali.aizwys.cn/Article/details/gt2xgwxyhuz.html

esac
来源：http://dali.hfpthk.cn/Article/details/gt2jtlicqat.html

[R12] for 遍历文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2bxmyowex.html

for f in *.txt; do echo "$f"; done
来源：http://dali.redwolf501.top/Article/details/gt2uqwpvycl.html

[R13] for 计数循环
来源：http://dali.zhengqikj.top/Article/details/gt2qyktpctn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gt2sefwehsr.html

[R14] C 风格 for
来源：http://dali.guannengcc.top/Article/details/gt2rpnsxons.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258888.top/Article/details/gt2uigjvzoj.html

[R15] while 逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gt2txillxhj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.iojbl.cn/Article/details/gt2wxmtgemo.html

[R16] until 等待条件
来源：http://dali.dashuyun.cn/Article/details/gt2qmngsvdj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2lcxkyzeq.html

[R17] 数组定义与取值
来源：http://dali.zhengqikj.top/Article/details/gt2ifybznfa.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.mhx1999.top/Article/details/gt2iwtxtgvi.html

[R18] 遍历数组
来源：http://dali.bjfxy.top/Article/details/gt2cggtaluq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pycfn.com/Article/details/gt2iqeepktk.html

[R19] 数组长度
来源：http://dali.hammf.cn/Article/details/gt2vkwcvjin.html

echo "${#arr[@]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zogrvrql.html

[R20] 关联数组（字典）
来源：http://dali.zhongyouzk.top/Article/details/gt2lnyshsou.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj202588.top/Article/details/gt2sfkcpnjh.html

[R21] 字符串长度
来源：http://dali.aibaodan.cn/Article/details/gt2ctumviad.html

echo "${#s}"
来源：http://dali.ybcxt.top/Article/details/gt2tpyeptvd.html

[R22] 截取子串
来源：http://dali.yj20258888.top/Article/details/gt2wreaxwpd.html

echo "${s:0:5}"
来源：http://dali.jlsjyb.cn/Article/details/gt2bhhcuaqh.html

[R23] 字符串替换
来源：http://dali.jqgfzy.top/Article/details/gt2kjdvhhfi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yonumen.top/Article/details/gt2oqqbrbgq.html

[R24] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gt2qmsmqctn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2toxnesnh.html

[R25] 去后缀 / 去前缀
来源：http://dali.c1oappe.top/Article/details/gt2kmhraxjn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.kuanghao11.cn/Article/details/gt2najfcgrg.html

[R26] 命令替换
来源：http://dali.xinyue.icu/Article/details/gt2aghqfvbk.html

now=$(date +%F); echo "$now"
来源：http://dali.ivvv.top/Article/details/gt2kzuktsah.html

[R27] 算术展开
来源：http://dali.jiagoushi.top/Article/details/gt2qomedrwr.html

echo $((1 + 2 * 3))
来源：http://dali.bjfxy.top/Article/details/gt2rsnqwfpb.html

[R28] 浮点运算
来源：http://dali.yj20258888.top/Article/details/gt2jpryjeec.html

echo "scale=2; 10/3" | bc
来源：http://dali.sysykeji.top/Article/details/gt2tovvwivt.html

[R29] 定义函数
来源：http://dali.9152youxi.cn/Article/details/gt2rrhgqicg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wyiicvqn.html

[R30] 函数返回状态码
来源：http://dali.andypj.xyz/Article/details/gt2mqdqyeza.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigufen.top/Article/details/gt2opwnpirt.html

[R31] 局部变量
来源：http://dali.ivvv.top/Article/details/gt2emvpvhne.html

f() { local x=1; echo "$x"; }
来源：http://dali.guowangkeji.top/Article/details/gt2cemfqhvs.html

[R32] 参数个数校验
来源：http://dali.kuanghao11.cn/Article/details/gt2paaacybr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gt2odgzrmvz.html

[R33] 捕获错误并提示行号
来源：http://dali.zhoulong.xyz/Article/details/gt2hcsdphri.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenjidiqi.icu/Article/details/gt2zowuhwof.html

[R34] 退出时清理
来源：http://dali.nwbrower.top/Article/details/gt2aicjaala.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.havefunace.top/Article/details/gt2nbpijohv.html

[R35] 后台执行并等待
来源：http://dali.nanxuanxn.top/Article/details/gt2adkwvkaj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yanxiufei.cn/Article/details/gt2fzsitjef.html

[R36] 并发执行多个任务
来源：http://dali.cdnleiting.top/Article/details/gt2iqrxedjy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jlsjyb.cn/Article/details/gt2rkzfzphg.html

[R37] 把输出赋给变量
来源：http://dali.birdmap.top/Article/details/gt2mckfgyww.html

files=$(ls -1)
来源：http://dali.quarkkingdee.top/Article/details/gt2vdftuuxi.html

[R38] 管道串联
来源：http://dali.mhx1999.top/Article/details/gt2agttnbxn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daxiang520.top/Article/details/gt2rkpzkzci.html

[R39] 重定向标准输出与错误
来源：http://dali.daria6918.cn/Article/details/gt2lwfhlftz.html

cmd > out.log 2>&1
来源：http://dali.ydzc1.top/Article/details/gt2rwcexgoh.html

[R40] 追加写日志
来源：http://dali.gotoacloud.top/Article/details/gt2drilwizv.html

echo "log" >> out.log
来源：http://dali.sxryk.cn/Article/details/gt2vzyttycl.html

[R41] 丢弃输出
来源：http://dali.yongpay.top/Article/details/gt2pfzxrflo.html


<!-- 参考信息 -->