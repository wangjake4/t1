代发 wailian999

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yonumen.top/Article/details/gt2iqjywcdo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dianchejie.cn/Article/details/gt2hbteymje.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yongpay.top/Article/details/gt2peofvxoj.html

[P08] 处理浮点精度问题
来源：http://dali.chenzaomai.com/Article/details/gt2nipqzvrz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.aibaodan.cn/Article/details/gt2pjvoaszf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shangyingyoupin.top/Article/details/gt2llvjkemm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tianlin.xyz/Article/details/gt2vlghywky.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shuidangran.top/Article/details/gt2wcqsxraz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tanke756.top/Article/details/gt2bmqjjpjx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.feifeiyinyue.top/Article/details/gt2czadjajm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj20258.top/Article/details/gt2agkowjpg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.fzhhl.top/Article/details/gt2qvitdenk.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bsyysgcz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.aibaodan.cn/Article/details/gt2vgimvxho.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2bjknoung.html

[Q01] 创建表
来源：http://dali.guannengcc.top/Article/details/gt2zjbemwgq.html

CREATE TABLE users (
来源：http://dali.yueranfly.top/Article/details/gt2usdrkmgg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhengqikj.top/Article/details/gt2pkwuxaej.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gt2rrbspgdv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yueranfly.top/Article/details/gt2wxwppiqc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hongshengwenyu.top/Article/details/gt2jykutpmp.html

);
来源：http://dali.nanxuanxn.top/Article/details/gt2myavuszl.html

[Q02] 创建带外键的表
来源：http://dali.chenzaomai.com/Article/details/gt2oxoqnwwh.html

CREATE TABLE orders (
来源：http://dali.shangyingyoupin.top/Article/details/gt2plldytcm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gt2vcahyiav.html

user_id INT NOT NULL,
来源：http://dali.fzhhl.top/Article/details/gt2davxuzay.html

amount DECIMAL(10, 2),
来源：http://dali.bjfxy.top/Article/details/gt2rrzoyotz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sweek.top/Article/details/gt2zdqbzcxc.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2euelgpeu.html

[Q03] 增加列
来源：http://dali.yonumen.top/Article/details/gt2xvdasyyo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hnqzz.top/Article/details/gt2ceowebbt.html

[Q04] 修改列类型
来源：http://dali.yuanzhike.top/Article/details/gt2nqqcjhzk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sysykeji.top/Article/details/gt2vjkzwndt.html

[Q05] 重命名列
来源：http://dali.aibaodan.cn/Article/details/gt2bzhuqaum.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.0kj1m.cn/Article/details/gt2rfriqncp.html

[Q06] 删除列
来源：http://dali.shangyingyoupin.top/Article/details/gt2hvlekdyh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mtxgbbla.html

[Q07] 删除表
来源：http://dali.ppjwa.cn/Article/details/gt2swbutrci.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenlongwang.top/Article/details/gt2vnlchehl.html

[Q08] 创建普通索引
来源：http://dali.nanxuanxn.top/Article/details/gt2soauwnjl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cucudq.cn/Article/details/gt2dppnhljq.html

[Q09] 创建唯一索引
来源：http://dali.hfpthk.cn/Article/details/gt2qkohtswp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xylfe.cn/Article/details/gt2fhdjvdep.html

[Q10] 插入单行
来源：http://dali.zhongyouzk.top/Article/details/gt2ptmljjdc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tianlin.xyz/Article/details/gt2pteoqeij.html

[Q11] 一次插入多行
来源：http://dali.meibo888.top/Article/details/gt2dykykxhv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhongyouzk.top/Article/details/gt2zzrzbbvf.html

[Q12] 插入后取自增 ID
来源：http://dali.0kj1m.cn/Article/details/gt2tuwelfpd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pengpengdd.cyou/Article/details/gt2friausub.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sysykeji.top/Article/details/gt2hhjomrwn.html

[Q13] 忽略重复插入
来源：http://dali.daxiang520.top/Article/details/gt2costppdv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.9152youxi.cn/Article/details/gt2ucmlcvnv.html

[Q14] 存在则更新（upsert）
来源：http://dali.yangfankeji.com/Article/details/gt2uqlivpew.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guannengcc.top/Article/details/gt2kfuzyozt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hnqzz.top/Article/details/gt2dwhoilwj.html

[Q15] 查询全部
来源：http://dali.birdmap.top/Article/details/gt2aiealljn.html

SELECT * FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2mckvngyd.html

[Q16] 查询指定列
来源：http://dali.shzxlz.cn/Article/details/gt2pwxohqbj.html

SELECT id, name FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2axvhqaud.html

[Q17] 条件查询
来源：http://dali.svipenyu.cn/Article/details/gt2kpjtbumi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2jlkepekh.html

[Q18] 模糊匹配
来源：http://dali.fzhhl.top/Article/details/gt2cjdevtsk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uczwiuup.html

[Q19] 范围查询
来源：http://dali.yonumen.top/Article/details/gt2bytmxnon.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.9152youxi.cn/Article/details/gt2mstyddye.html

[Q20] IN 列表
来源：http://dali.hfpthk.cn/Article/details/gt2jnizjnyo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2gglyazim.html

[Q21] 空值判断
来源：http://dali.chenzaomai.com/Article/details/gt2iwusierz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.c1oappe.top/Article/details/gt2tdmfhkfo.html

[Q22] 排序
来源：http://dali.0kj1m.cn/Article/details/gt2vmscpiyh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ehwqpu.com/Article/details/gt2puoejtit.html

[Q23] 分页
来源：http://dali.andypj.xyz/Article/details/gt2gjvghwbu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.birdmap.top/Article/details/gt2jcjykkbr.html

[Q24] 去重
来源：http://dali.xziqi.cn/Article/details/gt2eextabxi.html

SELECT DISTINCT city FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2gxnyarzx.html

[Q25] 只取前 N 条
来源：http://dali.chenjidiqi.icu/Article/details/gt2wfbrykea.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sufxvd.cn/Article/details/gt2fqyubrgm.html

[Q26] 计数
来源：http://dali.iojbl.cn/Article/details/gt2aswctfpb.html

SELECT COUNT(*) FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2cjvkjsmm.html

[Q27] 条件计数
来源：http://dali.gaohongyu789.top/Article/details/gt2sdfivgqp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2fbihiqbb.html

[Q28] 求和与平均
来源：http://dali.zhixingplan.top/Article/details/gt2elfwfmbu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gt2hfkfgptn.html

[Q29] 最大最小值
来源：http://dali.yangfankeji.com/Article/details/gt2vqouhsmt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2myhifplk.html

[Q30] 分组统计
来源：http://dali.daxiang520.top/Article/details/gt2bkvootvd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gt2ldthvxul.html

[Q31] 分组后过滤
来源：http://dali.yj202588.top/Article/details/gt2hirqnvfw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.aibaodan.cn/Article/details/gt2dhgrbxyq.html

[Q32] 分组拼接字符串
来源：http://dali.nwbrower.top/Article/details/gt2lwjvymer.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gt2tgnpheiu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aeubqjcj.html

[Q33] 多列分组
来源：http://dali.shzxlz.cn/Article/details/gt2jkdjwqcl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cucudq.cn/Article/details/gt2ssusgkii.html

[Q34] 每组取第一条
来源：http://dali.xylfe.cn/Article/details/gt2jfflrppu.html

SELECT * FROM (
来源：http://dali.yanxiufei.cn/Article/details/gt2iyevkrpt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pjcjpjmv.html

) t WHERE rn = 1;
来源：http://dali.jinqigfzy.top/Article/details/gt2inprgzsw.html

[Q35] 内连接
来源：http://dali.ydzc1.top/Article/details/gt2momfxqbp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258888.top/Article/details/gt2zltrkptn.html

[Q36] 左连接
来源：http://dali.daria6918.cn/Article/details/gt2vobpwuxe.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.9152youxi.cn/Article/details/gt2srojwzei.html

[Q37] 右连接
来源：http://dali.hongshengwenyu.top/Article/details/gt2bckhjvev.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yvedp.cn/Article/details/gt2hshxglkf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tian-w.cn/Article/details/gt2erfakewe.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tanke756.top/Article/details/gt2ufvxbjpb.html

[Q39] 自连接（查上下级）
来源：http://dali.dashuyun.cn/Article/details/gt2nckdespl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.smart0.xyz/Article/details/gt2tqbclohz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gotoacloud.top/Article/details/gt2sltsrdsl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tian-w.cn/Article/details/gt2lzjoudmr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.meibo888.top/Article/details/gt2cssudftq.html

[Q41] 多表连接
来源：http://dali.guowangkeji.top/Article/details/gt2hhbohbqs.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj20258888.top/Article/details/gt2rjnotuck.html

JOIN users u ON u.id = o.user_id
来源：http://dali.havefunace.top/Article/details/gt2nirpxokg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sysykeji.top/Article/details/gt2cswjbnkd.html

[Q42] 连接条件附加过滤
来源：http://dali.cashguo.top/Article/details/gt2lqxfxrfg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj20258.top/Article/details/gt2ugqifqqu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sufxvd.cn/Article/details/gt2zmxezfbu.html

[Q43] 标量子查询
来源：http://dali.yuanzhike.top/Article/details/gt2trevbsef.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hfpthk.cn/Article/details/gt2zuupasgn.html

[Q44] IN 子查询
来源：http://dali.hnqzz.top/Article/details/gt2nnmixjnz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.redwolf501.top/Article/details/gt2wwivjkva.html

[Q45] EXISTS 判断存在
来源：http://dali.quarkkingdee.top/Article/details/gt2fttnennn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gt2jhuiyqbh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.c1oappe.top/Article/details/gt2eeazwmlf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.vqdsnc.cn/Article/details/gt2wxhaquhy.html

[Q47] 与平均值比较
来源：http://dali.daria6918.cn/Article/details/gt2pswvhhqj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tianlin.xyz/Article/details/gt2dymdfebq.html

[Q48] CTE 公用表表达式
来源：http://dali.fengsongda.top/Article/details/gt2sctmvhzs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.meibo888.top/Article/details/gt2iuaxfqze.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jlsjyb.cn/Article/details/gt2hbkfevym.html

[Q49] 更新单行
来源：http://dali.nanxuanxn.top/Article/details/gt2ipbjamih.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gt2zpqjbanv.html

[Q50] 批量更新
来源：http://dali.tianlin.xyz/Article/details/gt2hvvrqyqw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gt2rqlfhgew.html

[Q51] 用子查询更新
来源：http://dali.pycfn.com/Article/details/gt2rhnqqoti.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.c1oappe.top/Article/details/gt2clguyufd.html

[Q52] 删除指定行
来源：http://dali.yanxiufei.cn/Article/details/gt2ysqyaebq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gizzzxxm.html

[Q53] 按条件删除
来源：http://dali.gotoacloud.top/Article/details/gt2eahqdyrw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj202588.top/Article/details/gt2teixzitv.html

[Q54] 清空表
来源：http://dali.jinqigufen.top/Article/details/gt2vsldzzay.html

TRUNCATE TABLE logs;
来源：http://dali.zdqjudy.top/Article/details/gt2feyacpeb.html

[Q55] 排名（并列占位）
来源：http://dali.wangshuangyany.cn/Article/details/gt2iotzhkdz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gt2xswqidsc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.meibo888.top/Article/details/gt2ryvbrzqv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gt2hemptcnr.html

[Q57] 行号
来源：http://dali.hongshengwenyu.top/Article/details/gt2omyghnaz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2tvapcigk.html

[Q58] 累计求和
来源：http://dali.aizwys.cn/Article/details/gt2twstwipf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gt2phbufcnl.html

[Q59] 分组内累计
来源：http://dali.zhongyouzk.top/Article/details/gt2upowdkgh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gt2dvxpkmix.html

[Q60] 取上一行 / 下一行
来源：http://dali.nanxuanxn.top/Article/details/gt2neqfglfi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenjidiqi.icu/Article/details/gt2upiabxkg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2txxfjnip.html

[Q61] 移动平均
来源：http://dali.kuanghao11.cn/Article/details/gt2pimkgsrg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.birdmap.top/Article/details/gt2hfncfuik.html

[Q62] 分组占比
来源：http://dali.0kj1m.cn/Article/details/gt2rsyyddrj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gt2xywtauec.html

[Q63] 开启事务
来源：http://dali.316326.xyz/Article/details/gt2oflkpdhk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yuxming.cn/Article/details/gt2ejciwmoh.html

[Q64] 提交事务
来源：http://dali.yanxiufei.cn/Article/details/gt2scvfnmlm.html

COMMIT;
来源：http://dali.yj20258888.top/Article/details/gt2gujfsfnh.html

[Q65] 回滚事务
来源：http://dali.zhengqikj.top/Article/details/gt2djsjeraj.html

ROLLBACK;
来源：http://dali.guannengcc.top/Article/details/gt2cxocuxin.html

[Q66] 行锁查询
来源：http://dali.daxiang520.top/Article/details/gt2xjywfdvz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.aibaodan.cn/Article/details/gt2gsjjords.html

[Q67] 设置隔离级别
来源：http://dali.yj202588.top/Article/details/gt2nmdxvgph.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhengqikj.top/Article/details/gt2cwksrlvs.html

[Q68] 保存点
来源：http://dali.yj202588.top/Article/details/gt2bbxcqcks.html

SAVEPOINT sp1;
来源：http://dali.nanxuanxn.top/Article/details/gt2uhcqnska.html

ROLLBACK TO sp1;
来源：http://dali.haohaochexian.top/Article/details/gt2qkzdjpzj.html

[Q69] 查看执行计划
来源：http://dali.xuetiantiany.cn/Article/details/gt2rvzftvia.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yongpay.top/Article/details/gt2thsbrmdu.html

[Q70] 更新统计信息
来源：http://dali.sufxvd.cn/Article/details/gt2nngiousq.html

ANALYZE TABLE users;
来源：http://dali.shuidangran.top/Article/details/gt2aofpmaqb.html

[Q71] 查看建表语句
来源：http://dali.9152youxi.cn/Article/details/gt2ycosxjsa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.quarkkingdee.top/Article/details/gt2fskadplm.html

[Q72] 查看索引
来源：http://dali.fengsongda.top/Article/details/gt2lysljpbw.html

SHOW INDEX FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2pboxgrtr.html

[Q73] 查看表状态
来源：http://dali.jinqigfzy.top/Article/details/gt2hxqhcapa.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258888.top/Article/details/gt2zfkizvcc.html

[Q74] 强制使用索引
来源：http://dali.yongpay.top/Article/details/gt2erihmmcr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tanke756.top/Article/details/gt2dhpgltkm.html

[Q75] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gt2pnpojmuo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cheryme.top/Article/details/gt2cgwgnlbk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xylfe.cn/Article/details/gt2etgdppuv.html

[Q76] 按天统计
来源：http://dali.yuanzhike.top/Article/details/gt2jvifaqkm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gogol.net.cn/Article/details/gt2ciibezce.html

[Q77] 时间加减
来源：http://dali.yj20258888.top/Article/details/gt2lmyiyoco.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yangfankeji.com/Article/details/gt2mhvkoklc.html

[Q78] 当前时间
来源：http://dali.sxryk.cn/Article/details/gt2nmyviwnx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shzxlz.cn/Article/details/gt2afgtvwnk.html

[Q79] 字符串拼接
来源：http://dali.yonumen.top/Article/details/gt2lzeqvmtu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ivvv.top/Article/details/gt2ysnidyjj.html

[Q80] 字符串截取
来源：http://dali.cdnleiting.top/Article/details/gt2qgkrfqbw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2htidnzym.html

[Q81] 字符串替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cobaqgrn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2bteijsve.html

[Q82] 字符长度与字节长度
来源：http://dali.ybcxt.top/Article/details/gt2klgqedci.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gt2ctjkmvxe.html

[Q83] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gt2hcthtblu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gt2ntftccjh.html

[Q84] 去除首尾空格
来源：http://dali.jiagoushi.top/Article/details/gt2fxruoast.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwvahla.html

[Q85] 数值取整
来源：http://dali.yangfankeji.com/Article/details/gt2rneafmcl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hongshengwenyu.top/Article/details/gt2khoppowc.html

[Q86] 读取 JSON 字段
来源：http://dali.yonumen.top/Article/details/gt2uprqtyyi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gotoacloud.top/Article/details/gt2qcgnruhh.html

[Q87] JSON 字段做条件
来源：http://dali.snrcjt.cn/Article/details/gt2mefruqbp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hnxiangtu.top/Article/details/gt2tpakvroi.html

[Q88] 行转列（条件聚合）
来源：http://dali.shzxlz.cn/Article/details/gt2uewqcqjg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.iojbl.cn/Article/details/gt2tbachijo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2ovbgfkvg.html

[Q89] 判断表是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gt2uthyowwb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jianghu66.top/Article/details/gt2nsxgiwaz.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2crrhkace.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yuanzhike.top/Article/details/gt2czagwtjr.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2anxquqrr.html

R. Bash 专题
来源：http://dali.pengpengdd.cyou/Article/details/gt2jarqynvw.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2xvyiapup.html

[R01] shebang 与严格模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jhfhmfpp.html

#!/usr/bin/env bash
来源：http://dali.zdqjudy.top/Article/details/gt2rehetnax.html

set -euo pipefail
来源：http://dali.hnqzz.top/Article/details/gt2zyawzztn.html

[R02] 变量赋值与使用
来源：http://dali.yvedp.cn/Article/details/gt2ovlzwzpe.html

name="Tom"; echo "$name"
来源：http://dali.jianghu66.top/Article/details/gt2xyvllrfx.html

[R03] 只读变量
来源：http://dali.yonumen.top/Article/details/gt2gptctlkg.html

readonly PI=3.14
来源：http://dali.tianlin.xyz/Article/details/gt2oqybvddh.html

[R04] 位置参数
来源：http://dali.c1oappe.top/Article/details/gt2lrcztbjf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxuanxn.top/Article/details/gt2hshrskxt.html

[R05] 参数默认值
来源：http://dali.yuxming.cn/Article/details/gt2cgkigxsv.html

name="${1:-default}"
来源：http://dali.aizwys.cn/Article/details/gt2efurogaa.html

[R06] 判断命令是否存在
来源：http://dali.zhoulong.xyz/Article/details/gt2mjhpfsgd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2aafxdzgn.html

[R07] if 判断文件
来源：http://dali.gotoacloud.top/Article/details/gt2fahvvkiv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gzhubu.top/Article/details/gt2drsdqilm.html

[R08] 数值比较
来源：http://dali.tian-w.cn/Article/details/gt2ngsrwxhs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenlongwang.top/Article/details/gt2qxlubdpt.html

[R09] 字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gt2leubndwh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xinyue.icu/Article/details/gt2czacfndj.html

[R10] 正则匹配
来源：http://dali.jiagoushi.top/Article/details/gt2wgrvffie.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.c1oappe.top/Article/details/gt2mjwipvxh.html

[R11] case 多分支
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ihgdnqoo.html

case "$1" in
来源：http://dali.wangdashe.top/Article/details/gt2nkjzbeob.html

start) echo "启动" ;;
来源：http://dali.9152youxi.cn/Article/details/gt2cyxgbxnz.html

stop)  echo "停止" ;;
来源：http://dali.gotoacloud.top/Article/details/gt2snaikftl.html

*)     echo "未知命令" ;;
来源：http://dali.gaohongyu789.top/Article/details/gt2zymlzrsv.html

esac
来源：http://dali.cqqwz.cn/Article/details/gt2uyknyboo.html

[R12] for 遍历文件
来源：http://dali.zhongyouzk.top/Article/details/gt2vjpcqzsj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cdnleiting.top/Article/details/gt2qhtbxhqs.html

[R13] for 计数循环
来源：http://dali.jinqigfzy.top/Article/details/gt2bwbeidoj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yangfankeji.com/Article/details/gt2rltrpsje.html

[R14] C 风格 for
来源：http://dali.yueranfly.top/Article/details/gt2coochmuh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.smart0.xyz/Article/details/gt2bhgkmtcm.html

[R15] while 逐行读文件
来源：http://dali.xziqi.cn/Article/details/gt2xkzvcyak.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2dsszfjxy.html

[R16] until 等待条件
来源：http://dali.zhengqikj.top/Article/details/gt2pwscbcrr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gaohongyu789.top/Article/details/gt2xflikkhq.html

[R17] 数组定义与取值
来源：http://dali.shuidangran.top/Article/details/gt2yrojerxh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.iojbl.cn/Article/details/gt2jacmqvta.html

[R18] 遍历数组
来源：http://dali.yongpay.top/Article/details/gt2bonbqpnx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigufen.top/Article/details/gt2blnfgddv.html

[R19] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uftgcpux.html

echo "${#arr[@]}"
来源：http://dali.cucudq.cn/Article/details/gt2ediilgro.html

[R20] 关联数组（字典）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lrsthbza.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xinyue.icu/Article/details/gt2wynnvwkx.html

[R21] 字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kzttufvy.html

echo "${#s}"
来源：http://dali.hysaishi.cn/Article/details/gt2egrclnjt.html

[R22] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gt2cgdwnhdt.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2smrkrgrj.html

[R23] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gt2ieskepit.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhengqikj.top/Article/details/gt2isvtmfmo.html

[R24] 大小写转换
来源：http://dali.xinyue.icu/Article/details/gt2dbsizjri.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zycfv.cn/Article/details/gt2tftjpxpt.html

[R25] 去后缀 / 去前缀
来源：http://dali.gogol.net.cn/Article/details/gt2pxeekedm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.snrcjt.cn/Article/details/gt2eecgkocg.html

[R26] 命令替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2olgnjovh.html

now=$(date +%F); echo "$now"
来源：http://dali.redwolf501.top/Article/details/gt2eiqvakjl.html

[R27] 算术展开
来源：http://dali.fengsongda.top/Article/details/gt2hixwwbgr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2bjalsslo.html

[R28] 浮点运算
来源：http://dali.yongpay.top/Article/details/gt2zgybrzct.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinqigfzy.top/Article/details/gt2wxnugsap.html

[R29] 定义函数
来源：http://dali.cashguo.top/Article/details/gt2xnwrjved.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.smart0.xyz/Article/details/gt2gzdsaejp.html

[R30] 函数返回状态码
来源：http://dali.xuetiantiany.cn/Article/details/gt2azfyflhy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.bjfxy.top/Article/details/gt2pelnqfzq.html

[R31] 局部变量
来源：http://dali.zycfv.cn/Article/details/gt2jflwzxih.html

f() { local x=1; echo "$x"; }
来源：http://dali.jqgfzy.top/Article/details/gt2tyvyiktj.html

[R32] 参数个数校验
来源：http://dali.daxiang520.top/Article/details/gt2glnpvwwz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.guannengcc.top/Article/details/gt2fldzzuxa.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigfzy.top/Article/details/gt2ttujwayk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.daria6918.cn/Article/details/gt2rzjqtzdr.html

[R34] 退出时清理
来源：http://dali.dianchejie.cn/Article/details/gt2fqdypval.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gt2noeucpdo.html

[R35] 后台执行并等待
来源：http://dali.dashuyun.cn/Article/details/gt2yyhvgjov.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuanzhike.top/Article/details/gt2jonzkibt.html

[R36] 并发执行多个任务
来源：http://dali.iojbl.cn/Article/details/gt2tzaiihay.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aibaodan.cn/Article/details/gt2gagdkdjh.html

[R37] 把输出赋给变量
来源：http://dali.smart0.xyz/Article/details/gt2mbveirxp.html


<!-- 参考信息 -->