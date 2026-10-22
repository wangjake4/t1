代发 wailian999

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yvedp.cn/Article/details/gt2gkpxuagm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhengqikj.top/Article/details/gt2byrfipkc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.snrcjt.cn/Article/details/gt2ryghywwu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gt2vclaowio.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hammf.cn/Article/details/gt2okrnmfbk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gnhqelcy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yanxiufei.cn/Article/details/gt2nqnpspgb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dashuyun.cn/Article/details/gt2tamoxmoe.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2wekbgsht.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mrnwzneo.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2hddqclwq.html

[Q01] 创建表
来源：http://dali.tian-w.cn/Article/details/gt2uummmduw.html

CREATE TABLE users (
来源：http://dali.daria6918.cn/Article/details/gt2dtqhmdjg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gt2ntysivrm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gt2kacqgyjt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ehwqpu.com/Article/details/gt2vhsigmwb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2azgncbrt.html

);
来源：http://dali.daxiang520.top/Article/details/gt2gpbvlwjh.html

[Q02] 创建带外键的表
来源：http://dali.c1oappe.top/Article/details/gt2jiyonpfy.html

CREATE TABLE orders (
来源：http://dali.9152youxi.cn/Article/details/gt2lihwqvpc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pengpengdd.cyou/Article/details/gt2orozvegs.html

user_id INT NOT NULL,
来源：http://dali.birdmap.top/Article/details/gt2xmdahbsn.html

amount DECIMAL(10, 2),
来源：http://dali.shuidangran.top/Article/details/gt2hnfvlkwt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.birdmap.top/Article/details/gt2ohwvqsdm.html

);
来源：http://dali.gzhubu.top/Article/details/gt2zoncqhrm.html

[Q03] 增加列
来源：http://dali.c1oappe.top/Article/details/gt2bbiuujhk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.dashuyun.cn/Article/details/gt2bwhdovmg.html

[Q04] 修改列类型
来源：http://dali.cdnleiting.top/Article/details/gt2rwzrvajn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sysykeji.top/Article/details/gt2hldrygao.html

[Q05] 重命名列
来源：http://dali.cucudq.cn/Article/details/gt2gwmotwpr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.wangdashe.top/Article/details/gt2cdymxzht.html

[Q06] 删除列
来源：http://dali.hnxiangtu.top/Article/details/gt2omgvqlax.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2itvpjddl.html

[Q07] 删除表
来源：http://dali.tianlin.xyz/Article/details/gt2sthebytq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2xphjjfag.html

[Q08] 创建普通索引
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mxqsdzjj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tanke756.top/Article/details/gt2ubmrdpsg.html

[Q09] 创建唯一索引
来源：http://dali.zhiwuduotai.top/Article/details/gt2idybymnh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gt2ndxqzcea.html

[Q10] 插入单行
来源：http://dali.xuanzx.com/Article/details/gt2xfkewnsc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shzxlz.cn/Article/details/gt2cktndsgh.html

[Q11] 一次插入多行
来源：http://dali.ybcxt.top/Article/details/gt2byvqqwmm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oiwxtstw.html

[Q12] 插入后取自增 ID
来源：http://dali.chenzaomai.com/Article/details/gt2qlzrnxwy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tian-w.cn/Article/details/gt2nmejlzwh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xinyue.icu/Article/details/gt2gcfkkyhr.html

[Q13] 忽略重复插入
来源：http://dali.tanke756.top/Article/details/gt2zmvomqyr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jyoumei.cn/Article/details/gt2ncozzkgi.html

[Q14] 存在则更新（upsert）
来源：http://dali.hammf.cn/Article/details/gt2vzbphexw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jyoumei.cn/Article/details/gt2wshntjge.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sxryk.cn/Article/details/gt2tvmcwrja.html

[Q15] 查询全部
来源：http://dali.aizwys.cn/Article/details/gt2nkrjvkfr.html

SELECT * FROM users;
来源：http://dali.yonumen.top/Article/details/gt2tswfkqtv.html

[Q16] 查询指定列
来源：http://dali.jianghu66.top/Article/details/gt2zdnzlvkk.html

SELECT id, name FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2acybwiix.html

[Q17] 条件查询
来源：http://dali.pycfn.com/Article/details/gt2yepfdqjg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daxiang520.top/Article/details/gt2fnknqaxh.html

[Q18] 模糊匹配
来源：http://dali.daxiang520.top/Article/details/gt2gtzxobxi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nwbrower.top/Article/details/gt2vthaelop.html

[Q19] 范围查询
来源：http://dali.yongpay.top/Article/details/gt2dwkdymmj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xylfe.cn/Article/details/gt2xgcgrves.html

[Q20] IN 列表
来源：http://dali.kuanghao11.cn/Article/details/gt2wdwutxst.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zycfv.cn/Article/details/gt2zamrxkak.html

[Q21] 空值判断
来源：http://dali.svipenyu.cn/Article/details/gt2ogupiskf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gt2miijvart.html

[Q22] 排序
来源：http://dali.quarkkingdee.top/Article/details/gt2wsmhndhc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhiwuduotai.top/Article/details/gt2xyeobbcz.html

[Q23] 分页
来源：http://dali.jiagoushi.top/Article/details/gt2eaotguom.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj20258888.top/Article/details/gt2okjbnzjl.html

[Q24] 去重
来源：http://dali.sxryk.cn/Article/details/gt2zdwtspju.html

SELECT DISTINCT city FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2ajrwkqii.html

[Q25] 只取前 N 条
来源：http://dali.andypj.xyz/Article/details/gt2emzetenn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2leyhjagb.html

[Q26] 计数
来源：http://dali.zdqjudy.top/Article/details/gt2cosmqxmf.html

SELECT COUNT(*) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2dmwgfdch.html

[Q27] 条件计数
来源：http://dali.aibaodan.cn/Article/details/gt2clbjxgwd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2qeryiiqu.html

[Q28] 求和与平均
来源：http://dali.wangshuangyany.cn/Article/details/gt2kjtumxke.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gt2ubxjrsef.html

[Q29] 最大最小值
来源：http://dali.shzxlz.cn/Article/details/gt2kkngvdvi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2gfcvietf.html

[Q30] 分组统计
来源：http://dali.ehwqpu.com/Article/details/gt2lbctvrgk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gt2xljlocsy.html

[Q31] 分组后过滤
来源：http://dali.fengsongda.top/Article/details/gt2wsorfppz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhengqikj.top/Article/details/gt2asnlwwow.html

[Q32] 分组拼接字符串
来源：http://dali.meibo888.top/Article/details/gt2drqzbidu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gt2gxtqoovb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhoulong.xyz/Article/details/gt2pmubjwdp.html

[Q33] 多列分组
来源：http://dali.iojbl.cn/Article/details/gt2kxzcvkol.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xuanzx.com/Article/details/gt2taewdosw.html

[Q34] 每组取第一条
来源：http://dali.pengpengdd.cyou/Article/details/gt2vowitadf.html

SELECT * FROM (
来源：http://dali.wangshuangyany.cn/Article/details/gt2emubjnfu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhiwuduotai.top/Article/details/gt2foqtnkjx.html

) t WHERE rn = 1;
来源：http://dali.xinyue.icu/Article/details/gt2jpompnrq.html

[Q35] 内连接
来源：http://dali.tanke756.top/Article/details/gt2wyjjgajy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lnogwlua.html

[Q36] 左连接
来源：http://dali.xylfe.cn/Article/details/gt2cixwrydv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gt2grzwhbqj.html

[Q37] 右连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sibphdzr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.guannengcc.top/Article/details/gt2xnqdvysh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.wangdashe.top/Article/details/gt2cyjfthjw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.smart0.xyz/Article/details/gt2zdbptxua.html

[Q39] 自连接（查上下级）
来源：http://dali.nanxuanxn.top/Article/details/gt2cuijbltz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2geqhlxrw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aizwys.cn/Article/details/gt2metaxaex.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhongyouzk.top/Article/details/gt2ueijhzcy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhixingplan.top/Article/details/gt2reodmzhy.html

[Q41] 多表连接
来源：http://dali.jianghu66.top/Article/details/gt2modrcrpa.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ubitiqic.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hfpthk.cn/Article/details/gt2vosyiomq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.fengsongda.top/Article/details/gt2zcwqawyu.html

[Q42] 连接条件附加过滤
来源：http://dali.chenlongwang.top/Article/details/gt2apddolym.html

SELECT u.name, o.amount FROM users u
来源：http://dali.guowangkeji.top/Article/details/gt2fnzabffz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yonumen.top/Article/details/gt2pyfiqgst.html

[Q43] 标量子查询
来源：http://dali.nanxuanxn.top/Article/details/gt2rfxfelub.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cheryme.top/Article/details/gt2iclsupht.html

[Q44] IN 子查询
来源：http://dali.yj20258.top/Article/details/gt2imphazso.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rdgfvwoo.html

[Q45] EXISTS 判断存在
来源：http://dali.chenjidiqi.icu/Article/details/gt2kzwxnugo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yongpay.top/Article/details/gt2jteszfrb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj20258888.top/Article/details/gt2fdyxpxda.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gt2whovdqai.html

[Q47] 与平均值比较
来源：http://dali.xziqi.cn/Article/details/gt2ewtfzgwm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hywenlv.cn/Article/details/gt2fwgqoogb.html

[Q48] CTE 公用表表达式
来源：http://dali.havefunace.top/Article/details/gt2unmcnjpy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jqgfzy.top/Article/details/gt2xavtrbuu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hnqzz.top/Article/details/gt2njzfveqf.html

[Q49] 更新单行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yucmdzwc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gt2yeactwyq.html

[Q50] 批量更新
来源：http://dali.chenzaomai.com/Article/details/gt2lsnaarqz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.feifeiyinyue.top/Article/details/gt2jbqmoxmx.html

[Q51] 用子查询更新
来源：http://dali.jianghu66.top/Article/details/gt2tamskhis.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jqgfzy.top/Article/details/gt2pwrfypfm.html

[Q52] 删除指定行
来源：http://dali.cashguo.top/Article/details/gt2klgvblvn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.daxiang520.top/Article/details/gt2yhlqxgyz.html

[Q53] 按条件删除
来源：http://dali.nanxuanxn.top/Article/details/gt2mstlyuka.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jiagoushi.top/Article/details/gt2ttjzrvlo.html

[Q54] 清空表
来源：http://dali.daria6918.cn/Article/details/gt2vngfwtgj.html

TRUNCATE TABLE logs;
来源：http://dali.jqgufenzy.top/Article/details/gt2kkzghcni.html

[Q55] 排名（并列占位）
来源：http://dali.zdqjudy.top/Article/details/gt2tbplftte.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj20258.top/Article/details/gt2eouzdtjr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yvedp.cn/Article/details/gt2uveaeyzv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yuanzhike.top/Article/details/gt2nogaklkb.html

[Q57] 行号
来源：http://dali.gogol.net.cn/Article/details/gt2vsgqmvnu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2vaqotdac.html

[Q58] 累计求和
来源：http://dali.cheryme.top/Article/details/gt2qjnormay.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xziqi.cn/Article/details/gt2okfzzlxq.html

[Q59] 分组内累计
来源：http://dali.ivvv.top/Article/details/gt2jwcwaqza.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2forpndvf.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigfzy.top/Article/details/gt2uidldlws.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhengqikj.top/Article/details/gt2gwspbjny.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tian-w.cn/Article/details/gt2fpmxqszz.html

[Q61] 移动平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2blhltrgx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gt2kyffnorc.html

[Q62] 分组占比
来源：http://dali.hongshengwenyu.top/Article/details/gt2inzkipop.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gt2pqxlkjef.html

[Q63] 开启事务
来源：http://dali.chenlongwang.top/Article/details/gt2vghnkquu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hywenlv.cn/Article/details/gt2cqhpezno.html

[Q64] 提交事务
来源：http://dali.pycfn.com/Article/details/gt2duubebeo.html

COMMIT;
来源：http://dali.zhongyouzk.top/Article/details/gt2dwlxqrzp.html

[Q65] 回滚事务
来源：http://dali.nwbrower.top/Article/details/gt2bajoppew.html

ROLLBACK;
来源：http://dali.tianlin.xyz/Article/details/gt2lzpudvty.html

[Q66] 行锁查询
来源：http://dali.yangfankeji.com/Article/details/gt2gkzayfcc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.daxiang520.top/Article/details/gt2pzduhell.html

[Q67] 设置隔离级别
来源：http://dali.wangdashe.top/Article/details/gt2vdsvyiqt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.vqdsnc.cn/Article/details/gt2mpohuntk.html

[Q68] 保存点
来源：http://dali.shangyingyoupin.top/Article/details/gt2apaifgtz.html

SAVEPOINT sp1;
来源：http://dali.shzxlz.cn/Article/details/gt2dysrnzmy.html

ROLLBACK TO sp1;
来源：http://dali.sweek.top/Article/details/gt2skkuonwq.html

[Q69] 查看执行计划
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2slttalpz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rzqrvnph.html

[Q70] 更新统计信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nfvaevgn.html

ANALYZE TABLE users;
来源：http://dali.chenzaomai.com/Article/details/gt2hmmwvoil.html

[Q71] 查看建表语句
来源：http://dali.yj202588.top/Article/details/gt2mqyeuzfi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zycfv.cn/Article/details/gt2tvcyffbw.html

[Q72] 查看索引
来源：http://dali.jqgfzy.top/Article/details/gt2uxvrgnlz.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2stivqpoj.html

[Q73] 查看表状态
来源：http://dali.andypj.xyz/Article/details/gt2qctrfxqt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuanzhike.top/Article/details/gt2nunyzfdd.html

[Q74] 强制使用索引
来源：http://dali.sysykeji.top/Article/details/gt2nadzvozv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhoulong.xyz/Article/details/gt2evzfrxgt.html

[Q75] 日期格式化
来源：http://dali.xziqi.cn/Article/details/gt2fqswydyn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ezxkngff.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhongyouzk.top/Article/details/gt2eobvjvms.html

[Q76] 按天统计
来源：http://dali.andypj.xyz/Article/details/gt2xylawkss.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.haohaochexian.top/Article/details/gt2zlzreuqo.html

[Q77] 时间加减
来源：http://dali.shzxlz.cn/Article/details/gt2pwqujbgl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhengqikj.top/Article/details/gt2xksjsntn.html

[Q78] 当前时间
来源：http://dali.0kj1m.cn/Article/details/gt2qhhimqgy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ktrrhegv.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mtxvcyym.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nanxinkj.top/Article/details/gt2twpxfvnq.html

[Q80] 字符串截取
来源：http://dali.yvedp.cn/Article/details/gt2swboombt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2nnygkrqs.html

[Q81] 字符串替换
来源：http://dali.tianlin.xyz/Article/details/gt2hujesmes.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.316326.xyz/Article/details/gt2ayjoydqm.html

[Q82] 字符长度与字节长度
来源：http://dali.hnxiangtu.top/Article/details/gt2xgjphdjf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2pbrudjiy.html

[Q83] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gt2kpthkarz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2affutmld.html

[Q84] 去除首尾空格
来源：http://dali.zhixingplan.top/Article/details/gt2grqlpfqr.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2jlavrple.html

[Q85] 数值取整
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vbzmkozq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ojhjunaw.html

[Q86] 读取 JSON 字段
来源：http://dali.9152youxi.cn/Article/details/gt2bhtkatzv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yrmheohc.html

[Q87] JSON 字段做条件
来源：http://dali.shangyingyoupin.top/Article/details/gt2yookqidp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hysaishi.cn/Article/details/gt2qvcxprgo.html

[Q88] 行转列（条件聚合）
来源：http://dali.guowangkeji.top/Article/details/gt2cshzsbrg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shuidangran.top/Article/details/gt2rgcsthgn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2khnbsmxo.html

[Q89] 判断表是否存在
来源：http://dali.tanke756.top/Article/details/gt2wxdyfttx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.redwolf501.top/Article/details/gt2bmmqnktr.html

[Q90] 生成序号列
来源：http://dali.hywenlv.cn/Article/details/gt2brhbphzw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yueranfly.top/Article/details/gt2tqdirgpr.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2wmkokcjq.html

R. Bash 专题
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uxkxtvip.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2rordmztq.html

[R01] shebang 与严格模式
来源：http://dali.kuanghao11.cn/Article/details/gt2xqlqtcdz.html

#!/usr/bin/env bash
来源：http://dali.feifeiyinyue.top/Article/details/gt2ewalvraq.html

set -euo pipefail
来源：http://dali.zdqjudy.top/Article/details/gt2wpvybcdb.html

[R02] 变量赋值与使用
来源：http://dali.zhiwuduotai.top/Article/details/gt2hqykmodv.html

name="Tom"; echo "$name"
来源：http://dali.tianlin.xyz/Article/details/gt2toulohka.html

[R03] 只读变量
来源：http://dali.bjfxy.top/Article/details/gt2oumvftru.html

readonly PI=3.14
来源：http://dali.ppjwa.cn/Article/details/gt2yqjvwfqa.html

[R04] 位置参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2aoadunkh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangshuangyany.cn/Article/details/gt2jgtwvoqu.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhyixhz.html

name="${1:-default}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ozeldagp.html

[R06] 判断命令是否存在
来源：http://dali.cashguo.top/Article/details/gt2metsrpwn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsekuyj.html

[R07] if 判断文件
来源：http://dali.meibo888.top/Article/details/gt2sjbvnjna.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gaohongyu789.top/Article/details/gt2scemsgbg.html

[R08] 数值比较
来源：http://dali.yuxming.cn/Article/details/gt2yjobmypi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gogol.net.cn/Article/details/gt2tcrcfayk.html

[R09] 字符串比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lqtmjciu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xziqi.cn/Article/details/gt2vuiwuggy.html

[R10] 正则匹配
来源：http://dali.jqgfzy.top/Article/details/gt2qkcsxcve.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yvedp.cn/Article/details/gt2msajcwbv.html

[R11] case 多分支
来源：http://dali.shangyingyoupin.top/Article/details/gt2tcudlzir.html

case "$1" in
来源：http://dali.tanke756.top/Article/details/gt2qejaayia.html

start) echo "启动" ;;
来源：http://dali.ydzc1.top/Article/details/gt2sikaltqy.html

stop)  echo "停止" ;;
来源：http://dali.xinyue.icu/Article/details/gt2zipgxpue.html

*)     echo "未知命令" ;;
来源：http://dali.chenlongwang.top/Article/details/gt2hgidmqcm.html

esac
来源：http://dali.9152youxi.cn/Article/details/gt2clfyfycq.html

[R12] for 遍历文件
来源：http://dali.yj20258888.top/Article/details/gt2frnakipi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jianghu66.top/Article/details/gt2tbachvpa.html

[R13] for 计数循环
来源：http://dali.vqdsnc.cn/Article/details/gt2njjgnccm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.9152youxi.cn/Article/details/gt2mxoielfy.html

[R14] C 风格 for
来源：http://dali.yangfankeji.com/Article/details/gt2zdthywhg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gt2cckhcgbf.html

[R15] while 逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gt2fynckdrx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.daxiang520.top/Article/details/gt2ececndkx.html

[R16] until 等待条件
来源：http://dali.fzhhl.top/Article/details/gt2walinyfe.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gt2dwolmjtf.html

[R17] 数组定义与取值
来源：http://dali.chenlongwang.top/Article/details/gt2xqfviiui.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.snrcjt.cn/Article/details/gt2piziydiv.html

[R18] 遍历数组
来源：http://dali.cqqwz.cn/Article/details/gt2ivyqtelj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnqzz.top/Article/details/gt2jdiuqxdl.html

[R19] 数组长度
来源：http://dali.daxiang520.top/Article/details/gt2nrlyqheq.html

echo "${#arr[@]}"
来源：http://dali.nanxinkj.top/Article/details/gt2dismgkon.html

[R20] 关联数组（字典）
来源：http://dali.yangfankeji.com/Article/details/gt2qevqrufs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shzxlz.cn/Article/details/gt2lbxbdhdl.html

[R21] 字符串长度
来源：http://dali.yj20258888.top/Article/details/gt2wskrjfgf.html

echo "${#s}"
来源：http://dali.nanxuanxn.top/Article/details/gt2tfnfxoys.html

[R22] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gt2exxczcfw.html

echo "${s:0:5}"
来源：http://dali.snrcjt.cn/Article/details/gt2rtvsjxyd.html

[R23] 字符串替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2aymophkl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hysaishi.cn/Article/details/gt2yjmmzphs.html

[R24] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gt2utkpkzca.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shzxlz.cn/Article/details/gt2wkudgprr.html

[R25] 去后缀 / 去前缀
来源：http://dali.andypj.xyz/Article/details/gt2bbpzaqqm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.0kj1m.cn/Article/details/gt2udgplxgt.html

[R26] 命令替换
来源：http://dali.yj20258.top/Article/details/gt2yctqslho.html

now=$(date +%F); echo "$now"
来源：http://dali.wangdashe.top/Article/details/gt2rnwifedf.html

[R27] 算术展开
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yssiuuxi.html

echo $((1 + 2 * 3))
来源：http://dali.chenjidiqi.icu/Article/details/gt2rbwusjxw.html

[R28] 浮点运算
来源：http://dali.daria6918.cn/Article/details/gt2qpreycxj.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenlongwang.top/Article/details/gt2ydzvufmb.html

[R29] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gt2fxbcooed.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ydzc1.top/Article/details/gt2fsdmoyfo.html

[R30] 函数返回状态码
来源：http://dali.yuxming.cn/Article/details/gt2tbkxnnny.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.snrcjt.cn/Article/details/gt2iqbhkumc.html

[R31] 局部变量
来源：http://dali.ppjwa.cn/Article/details/gt2ibovamdt.html

f() { local x=1; echo "$x"; }
来源：http://dali.yonumen.top/Article/details/gt2dzyvlesh.html

[R32] 参数个数校验
来源：http://dali.yangfankeji.com/Article/details/gt2yojedkez.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gt2nyfqkdhf.html

[R33] 捕获错误并提示行号
来源：http://dali.tian-w.cn/Article/details/gt2jdoglncr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jqgufenzy.top/Article/details/gt2myqwlqyh.html

[R34] 退出时清理
来源：http://dali.bjfxy.top/Article/details/gt2mvwpfwsn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gt2lrsxfxyh.html

[R35] 后台执行并等待
来源：http://dali.gaohongyu789.top/Article/details/gt2bhagndtb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnqzz.top/Article/details/gt2otbbtkjo.html

[R36] 并发执行多个任务
来源：http://dali.meibo888.top/Article/details/gt2xxdzsevu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhoulong.xyz/Article/details/gt2xgmpvrlw.html

[R37] 把输出赋给变量
来源：http://dali.havefunace.top/Article/details/gt2nmvankve.html

files=$(ls -1)
来源：http://dali.ivvv.top/Article/details/gt2viuscsst.html

[R38] 管道串联
来源：http://dali.hfpthk.cn/Article/details/gt2wnroclfr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenzaomai.com/Article/details/gt2dusijtvs.html

[R39] 重定向标准输出与错误
来源：http://dali.aibaodan.cn/Article/details/gt2qfyunwqh.html


<!-- 参考信息 -->