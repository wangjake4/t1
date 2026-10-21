代发 wailian999

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.9152youxi.cn/Article/details/gtccebnhes.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.aibaodan.cn/Article/details/gtrqdtudvm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.mhx1999.top/Article/details/gtddqbtckp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtnfovmeng.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.guowangkeji.top/Article/details/gttltcsyun.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuxming.cn/Article/details/gtbjwgflra.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdxpdwta.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sysykeji.top/Article/details/gtmvenhixf.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtkwnxcuoo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cucudq.cn/Article/details/gttyjhghwd.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtlnxzagdk.html

[Q01] 创建表
来源：http://dali.jianghu66.top/Article/details/gtxiwzltju.html

CREATE TABLE users (
来源：http://dali.meibo888.top/Article/details/gtfklsxxbr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gtzsahiwqe.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tianlin.xyz/Article/details/gtevwjkpqy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.vqdsnc.cn/Article/details/gtvnvnxllg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cheryme.top/Article/details/gtivfybydo.html

);
来源：http://dali.yonumen.top/Article/details/gthzeugqjj.html

[Q02] 创建带外键的表
来源：http://dali.fengsongda.top/Article/details/gtfavvrzrn.html

CREATE TABLE orders (
来源：http://dali.yangfankeji.com/Article/details/gtjowzlyyx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxuanxn.top/Article/details/gtlhggvbaa.html

user_id INT NOT NULL,
来源：http://dali.shangyingyoupin.top/Article/details/gtsqabphcb.html

amount DECIMAL(10, 2),
来源：http://dali.redwolf501.top/Article/details/gtewvrfvuv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.pengpengdd.cyou/Article/details/gtkylwwfhz.html

);
来源：http://dali.cqqwz.cn/Article/details/gtcxfxreaz.html

[Q03] 增加列
来源：http://dali.daxiang520.top/Article/details/gtnbgpqqin.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhixingplan.top/Article/details/gtwvdmgtjv.html

[Q04] 修改列类型
来源：http://dali.gaohongyu789.top/Article/details/gtewvouwoe.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenlongwang.top/Article/details/gtvlwgrtdh.html

[Q05] 重命名列
来源：http://dali.iojbl.cn/Article/details/gtexmtznky.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.fengsongda.top/Article/details/gtvvzyvtrz.html

[Q06] 删除列
来源：http://dali.yonumen.top/Article/details/gtjeoztyhu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guowangkeji.top/Article/details/gtpzhlrsug.html

[Q07] 删除表
来源：http://dali.aizwys.cn/Article/details/gtnjrmhoiv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tianlin.xyz/Article/details/gtihbhpmyt.html

[Q08] 创建普通索引
来源：http://dali.zdqjudy.top/Article/details/gtdytggqup.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gttdsojlfr.html

[Q09] 创建唯一索引
来源：http://dali.hnxiangtu.top/Article/details/gtebbcnftj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gtjaxqnrlb.html

[Q10] 插入单行
来源：http://dali.vqdsnc.cn/Article/details/gtlkylpdup.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtmlwcotxl.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangtech.top/Article/details/gtnyaphgnr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj20258.top/Article/details/gtrehbmndp.html

[Q12] 插入后取自增 ID
来源：http://dali.hongshengwenyu.top/Article/details/gtgxrrxwwj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezkaqjuq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxpuuhax.html

[Q13] 忽略重复插入
来源：http://dali.dianchejie.cn/Article/details/gtilbnhjtu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gtsbhcvluf.html

[Q14] 存在则更新（upsert）
来源：http://dali.0kj1m.cn/Article/details/gtkfsyzrzg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.dashuyun.cn/Article/details/gtmsyvjvyb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.daria6918.cn/Article/details/gtlomlhvfa.html

[Q15] 查询全部
来源：http://dali.hfpthk.cn/Article/details/gtevhdaxox.html

SELECT * FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtwamzwkln.html

[Q16] 查询指定列
来源：http://dali.ppjwa.cn/Article/details/gtmlctxdpj.html

SELECT id, name FROM users;
来源：http://dali.andypj.xyz/Article/details/gturovdguv.html

[Q17] 条件查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrhunene.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sufxvd.cn/Article/details/gtophhjupj.html

[Q18] 模糊匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtelnjsyik.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jiagoushi.top/Article/details/gtsnaozxaj.html

[Q19] 范围查询
来源：http://dali.shzxlz.cn/Article/details/gtoaqtninm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cqqwz.cn/Article/details/gtetkjvikv.html

[Q20] IN 列表
来源：http://dali.zhixingplan.top/Article/details/gtmurpjebf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuanzhike.top/Article/details/gttihlwafz.html

[Q21] 空值判断
来源：http://dali.hnxiangtu.top/Article/details/gtmdcpyetd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj202588.top/Article/details/gtphywcuhf.html

[Q22] 排序
来源：http://dali.ehwqpu.com/Article/details/gtmofrhaou.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nanxinkj.top/Article/details/gtzmdhxwqv.html

[Q23] 分页
来源：http://dali.hammf.cn/Article/details/gtnvscencf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dashuyun.cn/Article/details/gtlpgndwrt.html

[Q24] 去重
来源：http://dali.bjfxy.top/Article/details/gtkttdojwe.html

SELECT DISTINCT city FROM users;
来源：http://dali.cucudq.cn/Article/details/gtsuefxjss.html

[Q25] 只取前 N 条
来源：http://dali.cashguo.top/Article/details/gtabfqipvt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbbbhewn.html

[Q26] 计数
来源：http://dali.cashguo.top/Article/details/gtlwhzmdoa.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfkpbcfnc.html

[Q27] 条件计数
来源：http://dali.jinqigufen.top/Article/details/gtnkaiqnou.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtnqfuxbam.html

[Q28] 求和与平均
来源：http://dali.zycfv.cn/Article/details/gtyughajcm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtppypmmui.html

[Q29] 最大最小值
来源：http://dali.tianlin.xyz/Article/details/gttcaokxdw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtjeuuyefs.html

[Q30] 分组统计
来源：http://dali.yuxming.cn/Article/details/gtntkalaky.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gtxcxvkxao.html

[Q31] 分组后过滤
来源：http://dali.zdqjudy.top/Article/details/gtntabuawz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sweek.top/Article/details/gthaqevbuw.html

[Q32] 分组拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtfhuhgqoj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gtyngzdszz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.haohaochexian.top/Article/details/gtjalobqbr.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gtpvwfwktk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.c1oappe.top/Article/details/gtxmpxwmbr.html

[Q34] 每组取第一条
来源：http://dali.xinyue.icu/Article/details/gtajrqgijn.html

SELECT * FROM (
来源：http://dali.cucudq.cn/Article/details/gtvgnjlhxx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hnqzz.top/Article/details/gtptobhbjl.html

) t WHERE rn = 1;
来源：http://dali.zhengqikj.top/Article/details/gtzrgyignz.html

[Q35] 内连接
来源：http://dali.jiagoushi.top/Article/details/gthpggxqqg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgufenzy.top/Article/details/gtrpsrvrjf.html

[Q36] 左连接
来源：http://dali.nwbrower.top/Article/details/gtqyawzlmw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtugcihwqp.html

[Q37] 右连接
来源：http://dali.wangshuangyany.cn/Article/details/gtkxjricdw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.redwolf501.top/Article/details/gtggnodlgi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnxiangtu.top/Article/details/gtjbzytvuc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hysaishi.cn/Article/details/gtefwofuej.html

[Q39] 自连接（查上下级）
来源：http://dali.cqqwz.cn/Article/details/gteylmjlwb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.svipenyu.cn/Article/details/gtxpuffwno.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtffpcidqf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yuanzhike.top/Article/details/gtaczwjmvv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xinyue.icu/Article/details/gtylrjdpsi.html

[Q41] 多表连接
来源：http://dali.yonumen.top/Article/details/gtxwzcdfyx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.9152youxi.cn/Article/details/gtnofklfnk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.guowangkeji.top/Article/details/gtzeojmxtt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.meibo888.top/Article/details/gtmjazshev.html

[Q42] 连接条件附加过滤
来源：http://dali.xuanzx.com/Article/details/gtoqaivvis.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hywenlv.cn/Article/details/gtxncylhhq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.pengpengdd.cyou/Article/details/gtlgontxga.html

[Q43] 标量子查询
来源：http://dali.birdmap.top/Article/details/gtoivjcwvt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nanxuanxn.top/Article/details/gtmluftrfm.html

[Q44] IN 子查询
来源：http://dali.nanxuanxn.top/Article/details/gtwidmxgag.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.guannengcc.top/Article/details/gtipjaxziy.html

[Q45] EXISTS 判断存在
来源：http://dali.wangshuangyany.cn/Article/details/gtoslcrxeg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.svipenyu.cn/Article/details/gtzkjvfpwi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ybcxt.top/Article/details/gtmysadnov.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tanke756.top/Article/details/gtkaseyapt.html

[Q47] 与平均值比较
来源：http://dali.yuanzhike.top/Article/details/gtnyorrlpt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrtgrosv.html

[Q48] CTE 公用表表达式
来源：http://dali.pengpengdd.cyou/Article/details/gttuxmprgt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.svipenyu.cn/Article/details/gtownonbhr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jianghu66.top/Article/details/gtkzsjwcns.html

[Q49] 更新单行
来源：http://dali.smart0.xyz/Article/details/gtwauvobxy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hfpthk.cn/Article/details/gtsmajvprm.html

[Q50] 批量更新
来源：http://dali.zhiwuduotai.top/Article/details/gtpksdgjkn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jyoumei.cn/Article/details/gtjecgzyti.html

[Q51] 用子查询更新
来源：http://dali.gotoacloud.top/Article/details/gtoolhvfft.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.0kj1m.cn/Article/details/gtnwitmtmd.html

[Q52] 删除指定行
来源：http://dali.smart0.xyz/Article/details/gtgobjurpg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtiwkgppfs.html

[Q53] 按条件删除
来源：http://dali.quarkkingdee.top/Article/details/gtnrgvyeut.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.guannengcc.top/Article/details/gtimcscfex.html

[Q54] 清空表
来源：http://dali.shuidangran.top/Article/details/gteodjsogv.html

TRUNCATE TABLE logs;
来源：http://dali.zdqjudy.top/Article/details/gtanhunkjx.html

[Q55] 排名（并列占位）
来源：http://dali.hysaishi.cn/Article/details/gtbwzrslcz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gtyikpsrjo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.bjfxy.top/Article/details/gtwnhlplld.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cdnleiting.top/Article/details/gtqqagqguv.html

[Q57] 行号
来源：http://dali.shzxlz.cn/Article/details/gtozokmmha.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.aizwys.cn/Article/details/gtedyoorbe.html

[Q58] 累计求和
来源：http://dali.aizwys.cn/Article/details/gtqzgovxor.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtorbsmmro.html

[Q59] 分组内累计
来源：http://dali.cqqwz.cn/Article/details/gtjxygjrmz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtodrgumbf.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj20258.top/Article/details/gtqzhvfzlv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.haohaochexian.top/Article/details/gtsanfzsbx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtrayugdzp.html

[Q61] 移动平均
来源：http://dali.316326.xyz/Article/details/gtzzslnfsp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtjvgkuwoy.html

[Q62] 分组占比
来源：http://dali.daxiang520.top/Article/details/gthcnfxuuy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtwqnkpelr.html

[Q63] 开启事务
来源：http://dali.zhongyouzk.top/Article/details/gtksxkgdwg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xylfe.cn/Article/details/gtxaciguib.html

[Q64] 提交事务
来源：http://dali.aibaodan.cn/Article/details/gtduuqlwoy.html

COMMIT;
来源：http://dali.birdmap.top/Article/details/gtjvgotzuq.html

[Q65] 回滚事务
来源：http://dali.yanxiufei.cn/Article/details/gtlucpedrt.html

ROLLBACK;
来源：http://dali.guowangkeji.top/Article/details/gtgpuzltik.html

[Q66] 行锁查询
来源：http://dali.zhiwuduotai.top/Article/details/gtxzewdccv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtinmgumgq.html

[Q67] 设置隔离级别
来源：http://dali.9152youxi.cn/Article/details/gthotkmcnd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gzhubu.top/Article/details/gtqttiozzl.html

[Q68] 保存点
来源：http://dali.yongpay.top/Article/details/gtnpqatkhg.html

SAVEPOINT sp1;
来源：http://dali.ybcxt.top/Article/details/gtomxsadpb.html

ROLLBACK TO sp1;
来源：http://dali.xuanzx.com/Article/details/gtflrvpmqt.html

[Q69] 查看执行计划
来源：http://dali.jlsjyb.cn/Article/details/gtzdoeielo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yangfankeji.com/Article/details/gtnbkiscmi.html

[Q70] 更新统计信息
来源：http://dali.xinyue.icu/Article/details/gttshcgjcz.html

ANALYZE TABLE users;
来源：http://dali.wangshuangyany.cn/Article/details/gtzldqgvmu.html

[Q71] 查看建表语句
来源：http://dali.cqqwz.cn/Article/details/gtaaksrwue.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dianchejie.cn/Article/details/gtwrcqwwtk.html

[Q72] 查看索引
来源：http://dali.ehwqpu.com/Article/details/gtgqtopbgb.html

SHOW INDEX FROM users;
来源：http://dali.pycfn.com/Article/details/gtcllvfxsw.html

[Q73] 查看表状态
来源：http://dali.fengsongda.top/Article/details/gtykrhcmnn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.daria6918.cn/Article/details/gtprezufjy.html

[Q74] 强制使用索引
来源：http://dali.yuxming.cn/Article/details/gtpsvpjwkq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jiagoushi.top/Article/details/gtzvqlabvw.html

[Q75] 日期格式化
来源：http://dali.yueranfly.top/Article/details/gtytybnvkd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtnvpychre.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.redwolf501.top/Article/details/gtbcyvlofy.html

[Q76] 按天统计
来源：http://dali.shuidangran.top/Article/details/gttevcrsex.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gotoacloud.top/Article/details/gtklzzizpw.html

[Q77] 时间加减
来源：http://dali.snrcjt.cn/Article/details/gttxdguszj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sxryk.cn/Article/details/gtqihnlcdk.html

[Q78] 当前时间
来源：http://dali.smart0.xyz/Article/details/gtzgxorutk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenzaomai.com/Article/details/gtekjqkzrb.html

[Q79] 字符串拼接
来源：http://dali.jinqigufen.top/Article/details/gtslshzenn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.feifeiyinyue.top/Article/details/gtsmysqbku.html

[Q80] 字符串截取
来源：http://dali.meibo888.top/Article/details/gtmkexmbrl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtzokjuena.html

[Q81] 字符串替换
来源：http://dali.bjfxy.top/Article/details/gtzblthfkp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xylfe.cn/Article/details/gtspsqygsm.html

[Q82] 字符长度与字节长度
来源：http://dali.xziqi.cn/Article/details/gtffkmrsxc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtukpqzvhl.html

[Q83] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gtywcyhdjp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtbfjytqwm.html

[Q84] 去除首尾空格
来源：http://dali.shangyingyoupin.top/Article/details/gtmlztuicr.html

SELECT TRIM(name) FROM users;
来源：http://dali.sweek.top/Article/details/gtmnqhihhl.html

[Q85] 数值取整
来源：http://dali.hnqzz.top/Article/details/gthpbtitsz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.aizwys.cn/Article/details/gtapjyuriq.html

[Q86] 读取 JSON 字段
来源：http://dali.cqqwz.cn/Article/details/gtuhxulywm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sysykeji.top/Article/details/gtrhocdfwn.html

[Q87] JSON 字段做条件
来源：http://dali.yonumen.top/Article/details/gtlongiusf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangdashe.top/Article/details/gtwaondocm.html

[Q88] 行转列（条件聚合）
来源：http://dali.guannengcc.top/Article/details/gtctkwakby.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yonumen.top/Article/details/gtkxyckrkp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtggrctckx.html

[Q89] 判断表是否存在
来源：http://dali.guannengcc.top/Article/details/gtsiscrzum.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sysykeji.top/Article/details/gtbwjhoyva.html

[Q90] 生成序号列
来源：http://dali.zhongyouzk.top/Article/details/gtvhhwkxtd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.0kj1m.cn/Article/details/gtomjdtfjw.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtfnpheudl.html

R. Bash 专题
来源：http://dali.cqqwz.cn/Article/details/gtfxjjuise.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtbkkieikr.html

[R01] shebang 与严格模式
来源：http://dali.tian-w.cn/Article/details/gtbfuxdzqo.html

#!/usr/bin/env bash
来源：http://dali.shzxlz.cn/Article/details/gttnlucnym.html

set -euo pipefail
来源：http://dali.sweek.top/Article/details/gtwrnlkhke.html

[R02] 变量赋值与使用
来源：http://dali.daria6918.cn/Article/details/gtrvyanygl.html

name="Tom"; echo "$name"
来源：http://dali.shangyingyoupin.top/Article/details/gtnxxayrje.html

[R03] 只读变量
来源：http://dali.wangshuangyany.cn/Article/details/gtygaytuqb.html

readonly PI=3.14
来源：http://dali.chenjidiqi.icu/Article/details/gtbrmcggew.html

[R04] 位置参数
来源：http://dali.svipenyu.cn/Article/details/gtmzdtrgzu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hfpthk.cn/Article/details/gtwrsktphc.html

[R05] 参数默认值
来源：http://dali.zhongyouzk.top/Article/details/gtbfzyxumu.html

name="${1:-default}"
来源：http://dali.ehwqpu.com/Article/details/gtjpzxvljq.html

[R06] 判断命令是否存在
来源：http://dali.havefunace.top/Article/details/gtlgkymwpc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xuetiantiany.cn/Article/details/gtrosibhza.html

[R07] if 判断文件
来源：http://dali.cqqwz.cn/Article/details/gtrxgnadmu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xuanzx.com/Article/details/gtrseltpwu.html

[R08] 数值比较
来源：http://dali.tanke756.top/Article/details/gtfdoqsfbd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zdqjudy.top/Article/details/gtnpuapels.html

[R09] 字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gtnmuasvrw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.quarkkingdee.top/Article/details/gtcvvhzovd.html

[R10] 正则匹配
来源：http://dali.xziqi.cn/Article/details/gtbuqaikwx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpbdccji.html

[R11] case 多分支
来源：http://dali.guowangkeji.top/Article/details/gtnkfcovlz.html

case "$1" in
来源：http://dali.xziqi.cn/Article/details/gtphpzjcas.html

start) echo "启动" ;;
来源：http://dali.ivvv.top/Article/details/gtggfnylwe.html

stop)  echo "停止" ;;
来源：http://dali.wangdashe.top/Article/details/gtlbaksawk.html

*)     echo "未知命令" ;;
来源：http://dali.jqgfzy.top/Article/details/gtiwjfjjdm.html

esac
来源：http://dali.cqqwz.cn/Article/details/gtlhsirvru.html

[R12] for 遍历文件
来源：http://dali.zhixingplan.top/Article/details/gtnlwmceuz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sxryk.cn/Article/details/gtdgzljdbm.html

[R13] for 计数循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtkddbzvwu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhengqikj.top/Article/details/gtucrpkaln.html

[R14] C 风格 for
来源：http://dali.xylfe.cn/Article/details/gtnyjgxqxb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jlsjyb.cn/Article/details/gtyuqrlngx.html

[R15] while 逐行读文件
来源：http://dali.yj202588.top/Article/details/gtljcqzjrj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xylfe.cn/Article/details/gtzyswabhs.html

[R16] until 等待条件
来源：http://dali.wangshuangyany.cn/Article/details/gtwctowqpd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenzaomai.com/Article/details/gtzbijpver.html

[R17] 数组定义与取值
来源：http://dali.shangyingyoupin.top/Article/details/gtpteuxqhs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.vqdsnc.cn/Article/details/gtcxhlmkbd.html

[R18] 遍历数组
来源：http://dali.yuxming.cn/Article/details/gtibrtmtjd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ybcxt.top/Article/details/gtnprifigz.html

[R19] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gtaygrdlkg.html

echo "${#arr[@]}"
来源：http://dali.hongshengwenyu.top/Article/details/gtpmcnezil.html

[R20] 关联数组（字典）
来源：http://dali.yj202588.top/Article/details/gtyujmzdvz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ppjwa.cn/Article/details/gtzlugwswo.html

[R21] 字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gtsvjgybax.html

echo "${#s}"
来源：http://dali.smart0.xyz/Article/details/gtdvzlwggb.html

[R22] 截取子串
来源：http://dali.xziqi.cn/Article/details/gtploycqhv.html

echo "${s:0:5}"
来源：http://dali.mhx1999.top/Article/details/gtnbgnnupg.html

[R23] 字符串替换
来源：http://dali.tianlin.xyz/Article/details/gthnlcmklu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfbrizft.html

[R24] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gtvtfinmqy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.mhx1999.top/Article/details/gtgculqthf.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gtsmcxiiav.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.smart0.xyz/Article/details/gturpzkoxh.html

[R26] 命令替换
来源：http://dali.xuetiantiany.cn/Article/details/gtsgdmlvxg.html

now=$(date +%F); echo "$now"
来源：http://dali.zhiwuduotai.top/Article/details/gtzhduxrjl.html

[R27] 算术展开
来源：http://dali.shangyingyoupin.top/Article/details/gtfewvqjbc.html

echo $((1 + 2 * 3))
来源：http://dali.hywenlv.cn/Article/details/gtroogukmf.html

[R28] 浮点运算
来源：http://dali.shzxlz.cn/Article/details/gtumlqdxzo.html

echo "scale=2; 10/3" | bc
来源：http://dali.jyoumei.cn/Article/details/gtmlaarvia.html

[R29] 定义函数
来源：http://dali.jinqigufen.top/Article/details/gtirjmmkla.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.feifeiyinyue.top/Article/details/gtdurkbghc.html

[R30] 函数返回状态码
来源：http://dali.zhengqikj.top/Article/details/gtnypqlpwc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvpatopv.html

[R31] 局部变量
来源：http://dali.jinqigfzy.top/Article/details/gtlpbjqjdj.html

f() { local x=1; echo "$x"; }
来源：http://dali.kuanghao11.cn/Article/details/gtxlzttgol.html

[R32] 参数个数校验
来源：http://dali.zycfv.cn/Article/details/gtujbvvsvo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gtdcyvhzgy.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxuanxn.top/Article/details/gttboxkayf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gaohongyu789.top/Article/details/gtvhbhkxmb.html

[R34] 退出时清理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqopbjsle.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gtubziaejs.html

[R35] 后台执行并等待
来源：http://dali.gaohongyu789.top/Article/details/gtbcntyoca.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guowangkeji.top/Article/details/gtcoagczpt.html

[R36] 并发执行多个任务
来源：http://dali.xuetiantiany.cn/Article/details/gtrdcrtjmb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ppjwa.cn/Article/details/gtlblrzjqt.html

[R37] 把输出赋给变量
来源：http://dali.xylfe.cn/Article/details/gtsmkwolkp.html

files=$(ls -1)
来源：http://dali.hywenlv.cn/Article/details/gtovyxpsfs.html

[R38] 管道串联
来源：http://dali.yj20258.top/Article/details/gthtiwbahm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.wangdashe.top/Article/details/gtaiemmbhc.html

[R39] 重定向标准输出与错误
来源：http://dali.redwolf501.top/Article/details/gtqhpyrirf.html


<!-- 参考信息 -->