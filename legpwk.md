代发 wailian999

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cucudq.cn/Article/details/gt2eoajpziv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.vqdsnc.cn/Article/details/gt2uiuumiic.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yuanzhike.top/Article/details/gt2iwjpdbkh.html

[P08] 处理浮点精度问题
来源：http://dali.cucudq.cn/Article/details/gt2hmkxryuv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cdnleiting.top/Article/details/gt2kiaotwff.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.iojbl.cn/Article/details/gt2psqbuche.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.iojbl.cn/Article/details/gt2tvnmgtvl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenzaomai.com/Article/details/gt2qyhfkwxy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinqigufen.top/Article/details/gt2jphnzgzu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gogol.net.cn/Article/details/gt2dcqcluye.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xuanzx.com/Article/details/gt2ydgtxbjg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tianlin.xyz/Article/details/gt2xykjdtfx.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2wizowqqg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xuetiantiany.cn/Article/details/gt2qnjtezks.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2gftqlthp.html

[Q01] 创建表
来源：http://dali.feifeiyinyue.top/Article/details/gt2gjseqigj.html

CREATE TABLE users (
来源：http://dali.andypj.xyz/Article/details/gt2ibsqxbby.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.meibo888.top/Article/details/gt2aavgzxqd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hfpthk.cn/Article/details/gt2ovlktbxr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yanxiufei.cn/Article/details/gt2usjvlcot.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ivvv.top/Article/details/gt2axlwuvpb.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqmrtbr.html

[Q02] 创建带外键的表
来源：http://dali.hongshengwenyu.top/Article/details/gt2pljfxapr.html

CREATE TABLE orders (
来源：http://dali.mhx1999.top/Article/details/gt2wzhmuzgh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangdashe.top/Article/details/gt2jbyjzpcw.html

user_id INT NOT NULL,
来源：http://dali.cheryme.top/Article/details/gt2zvfqvlhc.html

amount DECIMAL(10, 2),
来源：http://dali.tanke756.top/Article/details/gt2hatdxynz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ehwqpu.com/Article/details/gt2pizarpez.html

);
来源：http://dali.mhx1999.top/Article/details/gt2jgvscfvk.html

[Q03] 增加列
来源：http://dali.sysykeji.top/Article/details/gt2dqzcjlcy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cashguo.top/Article/details/gt2gipizehy.html

[Q04] 修改列类型
来源：http://dali.guannengcc.top/Article/details/gt2bdqdojst.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258888.top/Article/details/gt2xglhzbmc.html

[Q05] 重命名列
来源：http://dali.zhengqikj.top/Article/details/gt2gvezcolc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jlsjyb.cn/Article/details/gt2jkmkvwkg.html

[Q06] 删除列
来源：http://dali.hnqzz.top/Article/details/gt2dmnacfub.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zkkfcvke.html

[Q07] 删除表
来源：http://dali.hnxiangtu.top/Article/details/gt2aidcfuju.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2hkixtgjq.html

[Q08] 创建普通索引
来源：http://dali.zycfv.cn/Article/details/gt2sszpeboh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gt2cexrhomy.html

[Q09] 创建唯一索引
来源：http://dali.dianchejie.cn/Article/details/gt2heckngep.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.9152youxi.cn/Article/details/gt2eljkpzgx.html

[Q10] 插入单行
来源：http://dali.jqgfzy.top/Article/details/gt2linboffq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sxryk.cn/Article/details/gt2yoisyflp.html

[Q11] 一次插入多行
来源：http://dali.fengsongda.top/Article/details/gt2dznfpzfg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xuanzx.com/Article/details/gt2uzdlwgqa.html

[Q12] 插入后取自增 ID
来源：http://dali.chenjidiqi.icu/Article/details/gt2lqwsnzep.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sweek.top/Article/details/gt2cdndclqa.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.daxiang520.top/Article/details/gt2gjmtglrh.html

[Q13] 忽略重复插入
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2stunpknc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yongpay.top/Article/details/gt2hfewkief.html

[Q14] 存在则更新（upsert）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pukeaokw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guannengcc.top/Article/details/gt2lnrnlrcr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.svipenyu.cn/Article/details/gt2rhczxnep.html

[Q15] 查询全部
来源：http://dali.zhiwuduotai.top/Article/details/gt2cxtjpigc.html

SELECT * FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2fssbivoh.html

[Q16] 查询指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xtchqsad.html

SELECT id, name FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2ydvkhnqr.html

[Q17] 条件查询
来源：http://dali.cashguo.top/Article/details/gt2wgfmcykr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ppjwa.cn/Article/details/gt2tbcvhwfn.html

[Q18] 模糊匹配
来源：http://dali.ppjwa.cn/Article/details/gt2lqhkhbnx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.redwolf501.top/Article/details/gt2vfasdnzk.html

[Q19] 范围查询
来源：http://dali.quarkkingdee.top/Article/details/gt2sbethzxi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.kuanghao11.cn/Article/details/gt2capfvgot.html

[Q20] IN 列表
来源：http://dali.ppjwa.cn/Article/details/gt2ycsburhk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ydzc1.top/Article/details/gt2mtmzusqk.html

[Q21] 空值判断
来源：http://dali.jinqigfzy.top/Article/details/gt2enckilcn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.mhx1999.top/Article/details/gt2annpiswz.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rwyxkoib.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hnqzz.top/Article/details/gt2yplzevvb.html

[Q23] 分页
来源：http://dali.feifeiyinyue.top/Article/details/gt2vbbvlnko.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinqigfzy.top/Article/details/gt2lkybhdnl.html

[Q24] 去重
来源：http://dali.haohaochexian.top/Article/details/gt2tovpxczl.html

SELECT DISTINCT city FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2egllvhjl.html

[Q25] 只取前 N 条
来源：http://dali.redwolf501.top/Article/details/gt2thipajfv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.havefunace.top/Article/details/gt2ietihzou.html

[Q26] 计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xecnviwc.html

SELECT COUNT(*) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2bwwjbttp.html

[Q27] 条件计数
来源：http://dali.hongshengwenyu.top/Article/details/gt2icpsqequ.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2tfpqzvkt.html

[Q28] 求和与平均
来源：http://dali.cashguo.top/Article/details/gt2rhxizoyn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258.top/Article/details/gt2nxyeckfm.html

[Q29] 最大最小值
来源：http://dali.chenzaomai.com/Article/details/gt2pzfgkqml.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2jditeunr.html

[Q30] 分组统计
来源：http://dali.pengpengdd.cyou/Article/details/gt2nftxdlpe.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gt2puaqjslx.html

[Q31] 分组后过滤
来源：http://dali.aibaodan.cn/Article/details/gt2cktbecyp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.iojbl.cn/Article/details/gt2ytssevsu.html

[Q32] 分组拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gt2eaywcmdz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gt2cnnbbldd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ybcxt.top/Article/details/gt2qvsvrhlu.html

[Q33] 多列分组
来源：http://dali.cucudq.cn/Article/details/gt2uoptrybt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xuanzx.com/Article/details/gt2vninmlxr.html

[Q34] 每组取第一条
来源：http://dali.zdqjudy.top/Article/details/gt2deraitob.html

SELECT * FROM (
来源：http://dali.iojbl.cn/Article/details/gt2dtslukgu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guannengcc.top/Article/details/gt2sxbjdxfs.html

) t WHERE rn = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2lqkmcjbn.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtzmckw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258888.top/Article/details/gt2jdvcctjg.html

[Q36] 左连接
来源：http://dali.c1oappe.top/Article/details/gt2rhwfbprk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fkdagkcl.html

[Q37] 右连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dzqitvpq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.smart0.xyz/Article/details/gt2ynvlzpog.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xinyue.icu/Article/details/gt2qwqxnrza.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2doskpwnp.html

[Q39] 自连接（查上下级）
来源：http://dali.nanxinkj.top/Article/details/gt2anranzrj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yonumen.top/Article/details/gt2bphitaig.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenlongwang.top/Article/details/gt2lawgdsys.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tbgnskez.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nwbrower.top/Article/details/gt2ogdvzxvx.html

[Q41] 多表连接
来源：http://dali.yj20258888.top/Article/details/gt2gjigkajv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinqigfzy.top/Article/details/gt2xwhmopls.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sxryk.cn/Article/details/gt2usxbfqlf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhengqikj.top/Article/details/gt2rwljzmyq.html

[Q42] 连接条件附加过滤
来源：http://dali.tian-w.cn/Article/details/gt2oaslzfkr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gotoacloud.top/Article/details/gt2myjiwnby.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yangfankeji.com/Article/details/gt2checrurn.html

[Q43] 标量子查询
来源：http://dali.c1oappe.top/Article/details/gt2olmbgbqv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xylfe.cn/Article/details/gt2scozytxx.html

[Q44] IN 子查询
来源：http://dali.hywenlv.cn/Article/details/gt2kfwdeqgw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.birdmap.top/Article/details/gt2oajrqqdt.html

[Q45] EXISTS 判断存在
来源：http://dali.aizwys.cn/Article/details/gt2euvoxpxy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gt2usahevyo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhengqikj.top/Article/details/gt2fxxdicwk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhongyouzk.top/Article/details/gt2fcoujiii.html

[Q47] 与平均值比较
来源：http://dali.hywenlv.cn/Article/details/gt2cxgdlrmb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cheryme.top/Article/details/gt2gjkqnfpn.html

[Q48] CTE 公用表表达式
来源：http://dali.zhoulong.xyz/Article/details/gt2lnspdpyu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jianghu66.top/Article/details/gt2fvtguvuw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hnxiangtu.top/Article/details/gt2tlamqzte.html

[Q49] 更新单行
来源：http://dali.yangfankeji.com/Article/details/gt2xogbggxv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgfzy.top/Article/details/gt2osrspewf.html

[Q50] 批量更新
来源：http://dali.tian-w.cn/Article/details/gt2ozmampav.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jqgfzy.top/Article/details/gt2ofirdcyg.html

[Q51] 用子查询更新
来源：http://dali.kuanghao11.cn/Article/details/gt2tezcwjmn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bkudrjly.html

[Q52] 删除指定行
来源：http://dali.xylfe.cn/Article/details/gt2wsdldqnr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ujcqqzkk.html

[Q53] 按条件删除
来源：http://dali.jqgfzy.top/Article/details/gt2qkpkbjgn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.meibo888.top/Article/details/gt2vlzcuoxg.html

[Q54] 清空表
来源：http://dali.cdnleiting.top/Article/details/gt2ylmlgyex.html

TRUNCATE TABLE logs;
来源：http://dali.hnqzz.top/Article/details/gt2hqcdpksu.html

[Q55] 排名（并列占位）
来源：http://dali.dianchejie.cn/Article/details/gt2qovuouoc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhengqikj.top/Article/details/gt2uedgdaou.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jqgfzy.top/Article/details/gt2yujczdkm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.meibo888.top/Article/details/gt2avrmcrlj.html

[Q57] 行号
来源：http://dali.hywenlv.cn/Article/details/gt2apvxuuln.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2uymbiziw.html

[Q58] 累计求和
来源：http://dali.aibaodan.cn/Article/details/gt2zklxggzy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2whouxjjh.html

[Q59] 分组内累计
来源：http://dali.yj202588.top/Article/details/gt2czvubyhq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gt2sypxcwlt.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuanzx.com/Article/details/gt2levhwcrx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lehncfmi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj202588.top/Article/details/gt2bmnptrcv.html

[Q61] 移动平均
来源：http://dali.tian-w.cn/Article/details/gt2sgbohxpy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gt2nvkawpwc.html

[Q62] 分组占比
来源：http://dali.jinqigfzy.top/Article/details/gt2mbilctcb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gt2qswpcgyb.html

[Q63] 开启事务
来源：http://dali.xinyue.icu/Article/details/gt2hzfixbgc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgfzy.top/Article/details/gt2pvkkpplw.html

[Q64] 提交事务
来源：http://dali.9152youxi.cn/Article/details/gt2qlcprcih.html

COMMIT;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ixkxkloo.html

[Q65] 回滚事务
来源：http://dali.nanxinkj.top/Article/details/gt2cqysmtuy.html

ROLLBACK;
来源：http://dali.gogol.net.cn/Article/details/gt2ompnxrkg.html

[Q66] 行锁查询
来源：http://dali.jqgfzy.top/Article/details/gt2zwoawvej.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuxming.cn/Article/details/gt2hlnqeckc.html

[Q67] 设置隔离级别
来源：http://dali.zdqjudy.top/Article/details/gt2wsirekjx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ehwqpu.com/Article/details/gt2sqbnubsk.html

[Q68] 保存点
来源：http://dali.jiagoushi.top/Article/details/gt2nlsohhts.html

SAVEPOINT sp1;
来源：http://dali.daria6918.cn/Article/details/gt2iskfnkjc.html

ROLLBACK TO sp1;
来源：http://dali.yongpay.top/Article/details/gt2nbwqplyu.html

[Q69] 查看执行计划
来源：http://dali.cqqwz.cn/Article/details/gt2vhrmmcez.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ydzc1.top/Article/details/gt2xejrurec.html

[Q70] 更新统计信息
来源：http://dali.wangshuangyany.cn/Article/details/gt2uctblmuc.html

ANALYZE TABLE users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2dwnxmxqw.html

[Q71] 查看建表语句
来源：http://dali.c1oappe.top/Article/details/gt2dwcpxhdn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jlsjyb.cn/Article/details/gt2bkghrplc.html

[Q72] 查看索引
来源：http://dali.xuanzx.com/Article/details/gt2jivmtxpd.html

SHOW INDEX FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2rgfmjhkz.html

[Q73] 查看表状态
来源：http://dali.yangfankeji.com/Article/details/gt2iklywqgh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gotoacloud.top/Article/details/gt2btckskri.html

[Q74] 强制使用索引
来源：http://dali.zhiwuduotai.top/Article/details/gt2reexpbgd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangshuangyany.cn/Article/details/gt2nrjtfqex.html

[Q75] 日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gt2sunyxlpk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2lyxqeelg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.316326.xyz/Article/details/gt2cdycmfey.html

[Q76] 按天统计
来源：http://dali.9152youxi.cn/Article/details/gt2jbaxrerd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj202588.top/Article/details/gt2qgecgemr.html

[Q77] 时间加减
来源：http://dali.nanxinkj.top/Article/details/gt2mxclivzk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dashuyun.cn/Article/details/gt2xsgptpbn.html

[Q78] 当前时间
来源：http://dali.nanxuanxn.top/Article/details/gt2uwakhxbu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258888.top/Article/details/gt2sgbywxuk.html

[Q79] 字符串拼接
来源：http://dali.ybcxt.top/Article/details/gt2aosceghp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgfzy.top/Article/details/gt2gkjhkikg.html

[Q80] 字符串截取
来源：http://dali.dianchejie.cn/Article/details/gt2osernqmg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2hinahefy.html

[Q81] 字符串替换
来源：http://dali.chenlongwang.top/Article/details/gt2jmqxctum.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pycfn.com/Article/details/gt2kiryzijn.html

[Q82] 字符长度与字节长度
来源：http://dali.shangyingyoupin.top/Article/details/gt2liuyrioz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2sxwhpsmu.html

[Q83] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gt2ttpddidc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2vhwvtsoz.html

[Q84] 去除首尾空格
来源：http://dali.zdqjudy.top/Article/details/gt2ohizyzjp.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2xupvkiku.html

[Q85] 数值取整
来源：http://dali.jinqigfzy.top/Article/details/gt2hkujmuyl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyhedzk.html

[Q86] 读取 JSON 字段
来源：http://dali.tianlin.xyz/Article/details/gt2oljoliij.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zycfv.cn/Article/details/gt2tcfbhbhv.html

[Q87] JSON 字段做条件
来源：http://dali.yongpay.top/Article/details/gt2npqjbpox.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.pengpengdd.cyou/Article/details/gt2kmghgomb.html

[Q88] 行转列（条件聚合）
来源：http://dali.svipenyu.cn/Article/details/gt2pyokmtnd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangtech.top/Article/details/gt2prhrjbcp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.havefunace.top/Article/details/gt2fqofzbpt.html

[Q89] 判断表是否存在
来源：http://dali.andypj.xyz/Article/details/gt2bqbagvin.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenzaomai.com/Article/details/gt2deyceoxy.html

[Q90] 生成序号列
来源：http://dali.xuetiantiany.cn/Article/details/gt2tuaasxji.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tianlin.xyz/Article/details/gt2geujkvlp.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2fyakltkh.html

R. Bash 专题
来源：http://dali.jlsjyb.cn/Article/details/gt2tbaaqgjq.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2lpiotlks.html

[R01] shebang 与严格模式
来源：http://dali.quarkkingdee.top/Article/details/gt2qfzuryqs.html

#!/usr/bin/env bash
来源：http://dali.yonumen.top/Article/details/gt2fzwtompa.html

set -euo pipefail
来源：http://dali.wangdashe.top/Article/details/gt2kvlohxfe.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlhieww.html

name="Tom"; echo "$name"
来源：http://dali.pycfn.com/Article/details/gt2dtgbzukx.html

[R03] 只读变量
来源：http://dali.jyoumei.cn/Article/details/gt2yxjmvtle.html

readonly PI=3.14
来源：http://dali.gaohongyu789.top/Article/details/gt2mllkxxno.html

[R04] 位置参数
来源：http://dali.yongpay.top/Article/details/gt2giuqvefa.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hammf.cn/Article/details/gt2okvptugp.html

[R05] 参数默认值
来源：http://dali.bjfxy.top/Article/details/gt2jsqmzopv.html

name="${1:-default}"
来源：http://dali.xylfe.cn/Article/details/gt2gofrmtlb.html

[R06] 判断命令是否存在
来源：http://dali.snrcjt.cn/Article/details/gt2ttnwsrov.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.316326.xyz/Article/details/gt2dowfqbgw.html

[R07] if 判断文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qjrhinhl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gt2stkcudhe.html

[R08] 数值比较
来源：http://dali.tanke756.top/Article/details/gt2iagbbciu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.havefunace.top/Article/details/gt2ntwyzxfv.html

[R09] 字符串比较
来源：http://dali.svipenyu.cn/Article/details/gt2gpikrjrx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2itzqtcwp.html

[R10] 正则匹配
来源：http://dali.daxiang520.top/Article/details/gt2qnfznvhd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zdqjudy.top/Article/details/gt2fsozimdv.html

[R11] case 多分支
来源：http://dali.tanke756.top/Article/details/gt2lzfhnlyy.html

case "$1" in
来源：http://dali.ehwqpu.com/Article/details/gt2awvsjmim.html

start) echo "启动" ;;
来源：http://dali.cucudq.cn/Article/details/gt2dnrsaltv.html

stop)  echo "停止" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gt2sdetwdjk.html

*)     echo "未知命令" ;;
来源：http://dali.tian-w.cn/Article/details/gt2mwcuwfaf.html

esac
来源：http://dali.yuanzhike.top/Article/details/gt2dudnegfa.html

[R12] for 遍历文件
来源：http://dali.jiagoushi.top/Article/details/gt2dtlvzxxq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.andypj.xyz/Article/details/gt2emzlvcpi.html

[R13] for 计数循环
来源：http://dali.nanxinkj.top/Article/details/gt2zfgzcevb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gt2tbmjvxaz.html

[R14] C 风格 for
来源：http://dali.sysykeji.top/Article/details/gt2pojosbnl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gt2fjlpwyyu.html

[R15] while 逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gt2nsamsuaf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2gsyobnjy.html

[R16] until 等待条件
来源：http://dali.zhongyouzk.top/Article/details/gt2zbrsosqw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gt2neqvgyjr.html

[R17] 数组定义与取值
来源：http://dali.pycfn.com/Article/details/gt2ezuiglmd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xziqi.cn/Article/details/gt2sosfugvd.html

[R18] 遍历数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2imflugaj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hywenlv.cn/Article/details/gt2lmljmase.html

[R19] 数组长度
来源：http://dali.xuanzx.com/Article/details/gt2ytmfrdxl.html

echo "${#arr[@]}"
来源：http://dali.ydzc1.top/Article/details/gt2nvsraezs.html

[R20] 关联数组（字典）
来源：http://dali.gzhubu.top/Article/details/gt2zfeuskse.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zdqjudy.top/Article/details/gt2lrbufyfy.html

[R21] 字符串长度
来源：http://dali.tianlin.xyz/Article/details/gt2xqwdhpyg.html

echo "${#s}"
来源：http://dali.yueranfly.top/Article/details/gt2uklekmjl.html

[R22] 截取子串
来源：http://dali.ehwqpu.com/Article/details/gt2halundzf.html

echo "${s:0:5}"
来源：http://dali.zdqjudy.top/Article/details/gt2myodkfem.html

[R23] 字符串替换
来源：http://dali.yonumen.top/Article/details/gt2julwxacm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gogol.net.cn/Article/details/gt2pzlajazp.html

[R24] 大小写转换
来源：http://dali.hnxiangtu.top/Article/details/gt2mzmguhpd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gcvpcsty.html

[R25] 去后缀 / 去前缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ljjgkilj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangdashe.top/Article/details/gt2qdtbuaqk.html

[R26] 命令替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2wbkueyng.html

now=$(date +%F); echo "$now"
来源：http://dali.9152youxi.cn/Article/details/gt2hzvodkkp.html

[R27] 算术展开
来源：http://dali.mhx1999.top/Article/details/gt2pktgjozy.html

echo $((1 + 2 * 3))
来源：http://dali.yongpay.top/Article/details/gt2fqqrrysx.html

[R28] 浮点运算
来源：http://dali.sweek.top/Article/details/gt2usfhbfra.html

echo "scale=2; 10/3" | bc
来源：http://dali.shuidangran.top/Article/details/gt2xahcnnsw.html

[R29] 定义函数
来源：http://dali.nanxuanxn.top/Article/details/gt2lrtvxqre.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.smart0.xyz/Article/details/gt2ujqjjfmc.html

[R30] 函数返回状态码
来源：http://dali.mhx1999.top/Article/details/gt2cialhhtq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.bjfxy.top/Article/details/gt2mbxajpyu.html

[R31] 局部变量
来源：http://dali.cqqwz.cn/Article/details/gt2zqaneexs.html

f() { local x=1; echo "$x"; }
来源：http://dali.haohaochexian.top/Article/details/gt2ukahitjr.html

[R32] 参数个数校验
来源：http://dali.sufxvd.cn/Article/details/gt2vrajfats.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuxming.cn/Article/details/gt2reftbosl.html

[R33] 捕获错误并提示行号
来源：http://dali.xuanzx.com/Article/details/gt2ngjphszr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gogol.net.cn/Article/details/gt2msavmzwt.html

[R34] 退出时清理
来源：http://dali.tianlin.xyz/Article/details/gt2baqrskof.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gt2pztdnlkg.html

[R35] 后台执行并等待
来源：http://dali.jqgfzy.top/Article/details/gt2pnvqexra.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.birdmap.top/Article/details/gt2hhhlvotc.html

[R36] 并发执行多个任务
来源：http://dali.mhx1999.top/Article/details/gt2cpglwywr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hywenlv.cn/Article/details/gt2fkvgxpqo.html

[R37] 把输出赋给变量
来源：http://dali.yj20258888.top/Article/details/gt2sgsyjvrw.html


<!-- 参考信息 -->