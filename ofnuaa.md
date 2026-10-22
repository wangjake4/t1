代发 wailian999

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.kuanghao11.cn/Article/details/gt2zjzwdxri.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2appsvtki.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj20258888.top/Article/details/gt2iayjzwpr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.smart0.xyz/Article/details/gt2hrrraeof.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2pujmwvlt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.smart0.xyz/Article/details/gt2xkvyqhzx.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2joyascga.html

[Q01] 创建表
来源：http://dali.ehwqpu.com/Article/details/gt2kylxagpw.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtasrei.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.quarkkingdee.top/Article/details/gt2knuciydx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wjnksyoa.html

email VARCHAR(100) UNIQUE,
来源：http://dali.guannengcc.top/Article/details/gt2tequijnl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gogol.net.cn/Article/details/gt2yqcrhycy.html

);
来源：http://dali.yonumen.top/Article/details/gt2pdrsgocp.html

[Q02] 创建带外键的表
来源：http://dali.feifeiyinyue.top/Article/details/gt2ecqpohzc.html

CREATE TABLE orders (
来源：http://dali.nanxinkj.top/Article/details/gt2jorxxrvt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iktuwbms.html

user_id INT NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gt2bgkgmmak.html

amount DECIMAL(10, 2),
来源：http://dali.yj202588.top/Article/details/gt2tsxcltmk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cdnleiting.top/Article/details/gt2wwbprury.html

);
来源：http://dali.redwolf501.top/Article/details/gt2komiudqr.html

[Q03] 增加列
来源：http://dali.cqqwz.cn/Article/details/gt2vbxtetlx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.c1oappe.top/Article/details/gt2cdezmsto.html

[Q04] 修改列类型
来源：http://dali.meibo888.top/Article/details/gt2xgqyteoy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daxiang520.top/Article/details/gt2cpgkrday.html

[Q05] 重命名列
来源：http://dali.gaohongyu789.top/Article/details/gt2acgdhnni.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sxryk.cn/Article/details/gt2hdcpfxmv.html

[Q06] 删除列
来源：http://dali.daxiang520.top/Article/details/gt2pskefiea.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tanke756.top/Article/details/gt2gdjfvbbn.html

[Q07] 删除表
来源：http://dali.zhiwuduotai.top/Article/details/gt2zkmpuhgp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yongpay.top/Article/details/gt2fgjxuksj.html

[Q08] 创建普通索引
来源：http://dali.sysykeji.top/Article/details/gt2wfnwgatz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tianlin.xyz/Article/details/gt2pawxwfyd.html

[Q09] 创建唯一索引
来源：http://dali.jianghu66.top/Article/details/gt2epwhuwng.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cbwnramm.html

[Q10] 插入单行
来源：http://dali.feifeiyinyue.top/Article/details/gt2iahllxbn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.guannengcc.top/Article/details/gt2eotfitrb.html

[Q11] 一次插入多行
来源：http://dali.hnqzz.top/Article/details/gt2lhfkuzga.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zycfv.cn/Article/details/gt2olwryogt.html

[Q12] 插入后取自增 ID
来源：http://dali.jlsjyb.cn/Article/details/gt2ujwfelzn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jqgfzy.top/Article/details/gt2hcrsavgb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.316326.xyz/Article/details/gt2otzbkugz.html

[Q13] 忽略重复插入
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2igzgxifg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yonumen.top/Article/details/gt2gxvrfxav.html

[Q14] 存在则更新（upsert）
来源：http://dali.daxiang520.top/Article/details/gt2eozgjrqk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.birdmap.top/Article/details/gt2rsaydbbi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xuanzx.com/Article/details/gt2aulcuyeh.html

[Q15] 查询全部
来源：http://dali.meibo888.top/Article/details/gt2oheuyjzi.html

SELECT * FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbpoqqrw.html

[Q16] 查询指定列
来源：http://dali.fzhhl.top/Article/details/gt2hjybxyud.html

SELECT id, name FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2noupauxn.html

[Q17] 条件查询
来源：http://dali.gzhubu.top/Article/details/gt2eijvutcv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pycfn.com/Article/details/gt2qakxvlsz.html

[Q18] 模糊匹配
来源：http://dali.shuidangran.top/Article/details/gt2xxedgqmk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yuanzhike.top/Article/details/gt2klaaereh.html

[Q19] 范围查询
来源：http://dali.nwbrower.top/Article/details/gt2odbxgnfy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yuanzhike.top/Article/details/gt2uaikimlx.html

[Q20] IN 列表
来源：http://dali.iojbl.cn/Article/details/gt2nrptepsh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qiztxpgs.html

[Q21] 空值判断
来源：http://dali.smart0.xyz/Article/details/gt2vbjbrxgm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhengqikj.top/Article/details/gt2jthpfygl.html

[Q22] 排序
来源：http://dali.jianghu66.top/Article/details/gt2rmmdjmxr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenzaomai.com/Article/details/gt2hleowqal.html

[Q23] 分页
来源：http://dali.cheryme.top/Article/details/gt2edndprtm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dianchejie.cn/Article/details/gt2lkolgfwd.html

[Q24] 去重
来源：http://dali.dashuyun.cn/Article/details/gt2bmucxvcq.html

SELECT DISTINCT city FROM users;
来源：http://dali.havefunace.top/Article/details/gt2vkaqltew.html

[Q25] 只取前 N 条
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lztlbmce.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gogol.net.cn/Article/details/gt2nzowgfou.html

[Q26] 计数
来源：http://dali.yj20258.top/Article/details/gt2gzymoxhx.html

SELECT COUNT(*) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2rgyihmgc.html

[Q27] 条件计数
来源：http://dali.hysaishi.cn/Article/details/gt2socirzbp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2njarnpkj.html

[Q28] 求和与平均
来源：http://dali.shangyingyoupin.top/Article/details/gt2muvwzjvb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2mflcooxg.html

[Q29] 最大最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2arzuqmtm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2altxkjvc.html

[Q30] 分组统计
来源：http://dali.jqgufenzy.top/Article/details/gt2grasmzfy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gt2uumvandd.html

[Q31] 分组后过滤
来源：http://dali.tianlin.xyz/Article/details/gt2hiuaurru.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tianlin.xyz/Article/details/gt2tulcufuu.html

[Q32] 分组拼接字符串
来源：http://dali.hnqzz.top/Article/details/gt2bhkniljz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gt2dlofmwjk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yuanzhike.top/Article/details/gt2turkxrka.html

[Q33] 多列分组
来源：http://dali.c1oappe.top/Article/details/gt2iewppdac.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.0kj1m.cn/Article/details/gt2crkchbyi.html

[Q34] 每组取第一条
来源：http://dali.hywenlv.cn/Article/details/gt2zminzrmx.html

SELECT * FROM (
来源：http://dali.xylfe.cn/Article/details/gt2ytlyfpbm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenjidiqi.icu/Article/details/gt2kxvmrxcc.html

) t WHERE rn = 1;
来源：http://dali.yongpay.top/Article/details/gt2nbomszko.html

[Q35] 内连接
来源：http://dali.yanxiufei.cn/Article/details/gt2duaapkeb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gt2pvfxpckm.html

[Q36] 左连接
来源：http://dali.ehwqpu.com/Article/details/gt2niwnpcms.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gt2fetpjohb.html

[Q37] 右连接
来源：http://dali.hfpthk.cn/Article/details/gt2jfummmlu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sysykeji.top/Article/details/gt2oabveuhu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenjidiqi.icu/Article/details/gt2aeecerkz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xziqi.cn/Article/details/gt2acoymuvz.html

[Q39] 自连接（查上下级）
来源：http://dali.redwolf501.top/Article/details/gt2nfexlcht.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.iojbl.cn/Article/details/gt2eeevdpde.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jlsjyb.cn/Article/details/gt2ffagwgeq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tanke756.top/Article/details/gt2blfapjjy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aizwys.cn/Article/details/gt2ofbutimx.html

[Q41] 多表连接
来源：http://dali.shzxlz.cn/Article/details/gt2ahfmpcag.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sufxvd.cn/Article/details/gt2kaaqmcmq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.redwolf501.top/Article/details/gt2xxgdrtmt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tianlin.xyz/Article/details/gt2xxeqqpak.html

[Q42] 连接条件附加过滤
来源：http://dali.jqgfzy.top/Article/details/gt2vvtlhuzs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jqgufenzy.top/Article/details/gt2aqtttmrd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jlsjyb.cn/Article/details/gt2mpcglvyh.html

[Q43] 标量子查询
来源：http://dali.dashuyun.cn/Article/details/gt2pciqfivj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuxming.cn/Article/details/gt2bslyrccy.html

[Q44] IN 子查询
来源：http://dali.0kj1m.cn/Article/details/gt2qdlxwanp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xylfe.cn/Article/details/gt2mgzdogba.html

[Q45] EXISTS 判断存在
来源：http://dali.andypj.xyz/Article/details/gt2exwcyfix.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gt2gcriiqcz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.redwolf501.top/Article/details/gt2wmdltdxm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.c1oappe.top/Article/details/gt2nuunyqxu.html

[Q47] 与平均值比较
来源：http://dali.pycfn.com/Article/details/gt2inefnrle.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.iojbl.cn/Article/details/gt2qmlnriud.html

[Q48] CTE 公用表表达式
来源：http://dali.yonumen.top/Article/details/gt2xyegaght.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kicxvxef.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhixingplan.top/Article/details/gt2tbpetwqg.html

[Q49] 更新单行
来源：http://dali.cashguo.top/Article/details/gt2vexpxyno.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.redwolf501.top/Article/details/gt2jytmyfwe.html

[Q50] 批量更新
来源：http://dali.gogol.net.cn/Article/details/gt2soqiadua.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yuanzhike.top/Article/details/gt2hvyehqxk.html

[Q51] 用子查询更新
来源：http://dali.ybcxt.top/Article/details/gt2amuwibcw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hammf.cn/Article/details/gt2lqihcjtw.html

[Q52] 删除指定行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tpuepybm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2elalljfc.html

[Q53] 按条件删除
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bjwizndq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenzaomai.com/Article/details/gt2pdbrkxuf.html

[Q54] 清空表
来源：http://dali.cucudq.cn/Article/details/gt2ochpizdl.html

TRUNCATE TABLE logs;
来源：http://dali.yuxming.cn/Article/details/gt2mfxrviba.html

[Q55] 排名（并列占位）
来源：http://dali.cashguo.top/Article/details/gt2bncoxbcn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gt2nfbopkhu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dashuyun.cn/Article/details/gt2evezyxgc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hfpthk.cn/Article/details/gt2bichvmke.html

[Q57] 行号
来源：http://dali.jinqigfzy.top/Article/details/gt2nmhefcck.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2ifgahuno.html

[Q58] 累计求和
来源：http://dali.hfpthk.cn/Article/details/gt2krlqharm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2iidtzmcw.html

[Q59] 分组内累计
来源：http://dali.nanxinkj.top/Article/details/gt2mtsoevuj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2eurweqfs.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhixingplan.top/Article/details/gt2lmefjwyw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hywenlv.cn/Article/details/gt2eqnkcuny.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bzhccdxb.html

[Q61] 移动平均
来源：http://dali.tian-w.cn/Article/details/gt2llrjtimf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2sawecovr.html

[Q62] 分组占比
来源：http://dali.snrcjt.cn/Article/details/gt2bvgpqjla.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gt2omdqvybp.html

[Q63] 开启事务
来源：http://dali.jinqigufen.top/Article/details/gt2dngijylu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ybcxt.top/Article/details/gt2egdmwovs.html

[Q64] 提交事务
来源：http://dali.hongshengwenyu.top/Article/details/gt2liecomue.html

COMMIT;
来源：http://dali.zhixingplan.top/Article/details/gt2cnfoifci.html

[Q65] 回滚事务
来源：http://dali.gaohongyu789.top/Article/details/gt2zgwalizw.html

ROLLBACK;
来源：http://dali.cqqwz.cn/Article/details/gt2tsuluoqx.html

[Q66] 行锁查询
来源：http://dali.tianlin.xyz/Article/details/gt2ysjzqlfw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zdqjudy.top/Article/details/gt2essaqdgs.html

[Q67] 设置隔离级别
来源：http://dali.yj20258.top/Article/details/gt2kpaheitj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xylfe.cn/Article/details/gt2fmfymsen.html

[Q68] 保存点
来源：http://dali.yonumen.top/Article/details/gt2dqlrvqsu.html

SAVEPOINT sp1;
来源：http://dali.daxiang520.top/Article/details/gt2cwaquugt.html

ROLLBACK TO sp1;
来源：http://dali.redwolf501.top/Article/details/gt2rkljbexm.html

[Q69] 查看执行计划
来源：http://dali.pycfn.com/Article/details/gt2cfldynjm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hammf.cn/Article/details/gt2gpxpxtgy.html

[Q70] 更新统计信息
来源：http://dali.yj20258.top/Article/details/gt2fpdpdvqw.html

ANALYZE TABLE users;
来源：http://dali.hfpthk.cn/Article/details/gt2illizgid.html

[Q71] 查看建表语句
来源：http://dali.havefunace.top/Article/details/gt2vokjzkgv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yuxming.cn/Article/details/gt2gxkdbndl.html

[Q72] 查看索引
来源：http://dali.guannengcc.top/Article/details/gt2fztjcfkb.html

SHOW INDEX FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2bmsdpbok.html

[Q73] 查看表状态
来源：http://dali.sufxvd.cn/Article/details/gt2kpqdtlda.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.316326.xyz/Article/details/gt2bjjqqyge.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangtech.top/Article/details/gt2axzwavrh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yangfankeji.com/Article/details/gt2prjzexsd.html

[Q75] 日期格式化
来源：http://dali.gaohongyu789.top/Article/details/gt2nrswfipo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj20258.top/Article/details/gt2mlyfyeeb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.birdmap.top/Article/details/gt2drhlfjde.html

[Q76] 按天统计
来源：http://dali.nanxinkj.top/Article/details/gt2rexireiy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.andypj.xyz/Article/details/gt2dsijkijq.html

[Q77] 时间加减
来源：http://dali.wangdashe.top/Article/details/gt2quragtal.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fjqwvdsh.html

[Q78] 当前时间
来源：http://dali.dianchejie.cn/Article/details/gt2pfabuodz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hfpthk.cn/Article/details/gt2mmytcpaq.html

[Q79] 字符串拼接
来源：http://dali.shangyingyoupin.top/Article/details/gt2ruieusxi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xinyue.icu/Article/details/gt2jvosnfaa.html

[Q80] 字符串截取
来源：http://dali.feifeiyinyue.top/Article/details/gt2prdwxzyb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2llageknp.html

[Q81] 字符串替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rfdighuq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2xezaizda.html

[Q82] 字符长度与字节长度
来源：http://dali.daxiang520.top/Article/details/gt2vvqtjorb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2lmtzixur.html

[Q83] 大小写转换
来源：http://dali.aizwys.cn/Article/details/gt2hwhxllci.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2pygmxqcy.html

[Q84] 去除首尾空格
来源：http://dali.snrcjt.cn/Article/details/gt2epdirsrh.html

SELECT TRIM(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2etdmughp.html

[Q85] 数值取整
来源：http://dali.nanxinkj.top/Article/details/gt2dutrkhcu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2hegrrval.html

[Q86] 读取 JSON 字段
来源：http://dali.shuidangran.top/Article/details/gt2azunbujd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fzhhl.top/Article/details/gt2nyusjoip.html

[Q87] JSON 字段做条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2akgmfrlx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xylfe.cn/Article/details/gt2arvsaoqd.html

[Q88] 行转列（条件聚合）
来源：http://dali.9152youxi.cn/Article/details/gt2sqsbmzkm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pengpengdd.cyou/Article/details/gt2htcqcnmw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2qzcbtxbt.html

[Q89] 判断表是否存在
来源：http://dali.yangfankeji.com/Article/details/gt2iuygsihw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jyoumei.cn/Article/details/gt2rtqjommm.html

[Q90] 生成序号列
来源：http://dali.dashuyun.cn/Article/details/gt2lsmkcdox.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ivvv.top/Article/details/gt2sfmquexa.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2lrykokud.html

R. Bash 专题
来源：http://dali.vqdsnc.cn/Article/details/gt2jjwgemho.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2stpjwfih.html

[R01] shebang 与严格模式
来源：http://dali.nanxuanxn.top/Article/details/gt2trvtqlse.html

#!/usr/bin/env bash
来源：http://dali.zdqjudy.top/Article/details/gt2virkvzvo.html

set -euo pipefail
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rxpbfjxh.html

[R02] 变量赋值与使用
来源：http://dali.xziqi.cn/Article/details/gt2allgbbjy.html

name="Tom"; echo "$name"
来源：http://dali.sxryk.cn/Article/details/gt2punotloi.html

[R03] 只读变量
来源：http://dali.c1oappe.top/Article/details/gt2whffzsgl.html

readonly PI=3.14
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sjjarcfi.html

[R04] 位置参数
来源：http://dali.yongpay.top/Article/details/gt2glbhdygz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jianghu66.top/Article/details/gt2oovoohgp.html

[R05] 参数默认值
来源：http://dali.bjfxy.top/Article/details/gt2yklreuzd.html

name="${1:-default}"
来源：http://dali.xuanzx.com/Article/details/gt2fjtmnjvz.html

[R06] 判断命令是否存在
来源：http://dali.yanxiufei.cn/Article/details/gt2mffyiawo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258.top/Article/details/gt2yheehikx.html

[R07] if 判断文件
来源：http://dali.hnxiangtu.top/Article/details/gt2rtxsebcd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gt2cnaikvcb.html

[R08] 数值比较
来源：http://dali.xziqi.cn/Article/details/gt2crlzpylp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhixingplan.top/Article/details/gt2ficlzzja.html

[R09] 字符串比较
来源：http://dali.shzxlz.cn/Article/details/gt2ahxzfjuc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zdqjudy.top/Article/details/gt2etugrovk.html

[R10] 正则匹配
来源：http://dali.yvedp.cn/Article/details/gt2rensbcto.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vpanidpt.html

[R11] case 多分支
来源：http://dali.ehwqpu.com/Article/details/gt2kdxsxugt.html

case "$1" in
来源：http://dali.yj202588.top/Article/details/gt2eqvvauut.html

start) echo "启动" ;;
来源：http://dali.daxiang520.top/Article/details/gt2ihlxhroh.html

stop)  echo "停止" ;;
来源：http://dali.cucudq.cn/Article/details/gt2fnabfvww.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2crlijgrl.html

esac
来源：http://dali.yj20258888.top/Article/details/gt2imihggee.html

[R12] for 遍历文件
来源：http://dali.ivvv.top/Article/details/gt2exovknvm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zdqjudy.top/Article/details/gt2yirkxyjv.html

[R13] for 计数循环
来源：http://dali.zhixingplan.top/Article/details/gt2hdnifwnc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hysaishi.cn/Article/details/gt2ucgbocrk.html

[R14] C 风格 for
来源：http://dali.cheryme.top/Article/details/gt2aybcsaxm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rmdmeoyv.html

[R15] while 逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gt2vkoretml.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hysaishi.cn/Article/details/gt2qwkxyqww.html

[R16] until 等待条件
来源：http://dali.sweek.top/Article/details/gt2iqheliik.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gt2puabmprc.html

[R17] 数组定义与取值
来源：http://dali.nanxuanxn.top/Article/details/gt2ncpgjqvj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rxoojfzk.html

[R18] 遍历数组
来源：http://dali.gaohongyu789.top/Article/details/gt2lcrxuuqz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hfpthk.cn/Article/details/gt2ceelvdno.html

[R19] 数组长度
来源：http://dali.xuanzx.com/Article/details/gt2wgwhquvj.html

echo "${#arr[@]}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2upzjtvip.html

[R20] 关联数组（字典）
来源：http://dali.chenlongwang.top/Article/details/gt2sweffmpj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258888.top/Article/details/gt2nfaqzdpa.html

[R21] 字符串长度
来源：http://dali.haohaochexian.top/Article/details/gt2lfvjgrbf.html

echo "${#s}"
来源：http://dali.ivvv.top/Article/details/gt2kkznmvcm.html

[R22] 截取子串
来源：http://dali.gotoacloud.top/Article/details/gt2pyiwnhyw.html

echo "${s:0:5}"
来源：http://dali.hysaishi.cn/Article/details/gt2bzuhcpuh.html

[R23] 字符串替换
来源：http://dali.cucudq.cn/Article/details/gt2pbgnnfod.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gaohongyu789.top/Article/details/gt2jofrzsdv.html

[R24] 大小写转换
来源：http://dali.smart0.xyz/Article/details/gt2jiqucfgz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2nwefgyzd.html

[R25] 去后缀 / 去前缀
来源：http://dali.tianlin.xyz/Article/details/gt2sddnjdth.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hywenlv.cn/Article/details/gt2pzuchhdj.html

[R26] 命令替换
来源：http://dali.xylfe.cn/Article/details/gt2ttybgvni.html

now=$(date +%F); echo "$now"
来源：http://dali.xuanzx.com/Article/details/gt2iyrsjzar.html

[R27] 算术展开
来源：http://dali.shuidangran.top/Article/details/gt2kyaqdzlx.html

echo $((1 + 2 * 3))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jbvcwxvc.html

[R28] 浮点运算
来源：http://dali.hnqzz.top/Article/details/gt2seelecqu.html

echo "scale=2; 10/3" | bc
来源：http://dali.nwbrower.top/Article/details/gt2feoikiia.html

[R29] 定义函数
来源：http://dali.cashguo.top/Article/details/gt2dxnpkzer.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aizwys.cn/Article/details/gt2ndpoxpne.html

[R30] 函数返回状态码
来源：http://dali.jinqigufen.top/Article/details/gt2wbpichmg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ydzc1.top/Article/details/gt2gedrdqzg.html

[R31] 局部变量
来源：http://dali.gogol.net.cn/Article/details/gt2ctiypmso.html

f() { local x=1; echo "$x"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2gidcvtia.html

[R32] 参数个数校验
来源：http://dali.yj202588.top/Article/details/gt2fxjitqwm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinqigufen.top/Article/details/gt2rsnltich.html

[R33] 捕获错误并提示行号
来源：http://dali.cdnleiting.top/Article/details/gt2bcesthue.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yangfankeji.com/Article/details/gt2dzfrjxnc.html

[R34] 退出时清理
来源：http://dali.shuidangran.top/Article/details/gt2aibjvufz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangshuangyany.cn/Article/details/gt2iedaelal.html

[R35] 后台执行并等待
来源：http://dali.chenzaomai.com/Article/details/gt2fvgdgisi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lejyzwpv.html

[R36] 并发执行多个任务
来源：http://dali.shuidangran.top/Article/details/gt2kezxqzrh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yueranfly.top/Article/details/gt2qbxqoklz.html

[R37] 把输出赋给变量
来源：http://dali.sufxvd.cn/Article/details/gt2rdbxevib.html

files=$(ls -1)
来源：http://dali.yj20258.top/Article/details/gt2esooalzz.html

[R38] 管道串联
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fdcoozjw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daxiang520.top/Article/details/gt2jtrvjlmi.html

[R39] 重定向标准输出与错误
来源：http://dali.hnxiangtu.top/Article/details/gt2furlhxhs.html

cmd > out.log 2>&1
来源：http://dali.316326.xyz/Article/details/gt2nfmbmola.html

[R40] 追加写日志
来源：http://dali.jinqigfzy.top/Article/details/gt2fgrtnuqx.html

echo "log" >> out.log
来源：http://dali.hammf.cn/Article/details/gt2rbmyntzn.html

[R41] 丢弃输出
来源：http://dali.zhiwuduotai.top/Article/details/gt2avmjnukh.html


<!-- 参考信息 -->