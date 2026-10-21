代发 wailian999

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xuetiantiany.cn/Article/details/gtnubomtpe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.birdmap.top/Article/details/gtqlywxchu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cashguo.top/Article/details/gtrhiwnyck.html

[P08] 处理浮点精度问题
来源：http://dali.wangdashe.top/Article/details/gteamteemr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xuetiantiany.cn/Article/details/gtzbxnycgj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jianghu66.top/Article/details/gthespccma.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pycfn.com/Article/details/gtmrjsorks.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yonumen.top/Article/details/gtofyngfyz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tianlin.xyz/Article/details/gtoqrpbdcu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nwbrower.top/Article/details/gtdgsmduon.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.svipenyu.cn/Article/details/gtkptwmjfg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hongshengwenyu.top/Article/details/gtldmdoyjw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtkuzpqpqe.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yuxming.cn/Article/details/gtejtgmmeu.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtmtsgzkkj.html

[Q01] 创建表
来源：http://dali.pengpengdd.cyou/Article/details/gtlauwpmwz.html

CREATE TABLE users (
来源：http://dali.aizwys.cn/Article/details/gtafjzpgtj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gtupsulczc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258.top/Article/details/gtvnijhbua.html

email VARCHAR(100) UNIQUE,
来源：http://dali.bjfxy.top/Article/details/gtmvuijlpj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.haohaochexian.top/Article/details/gtuwxygxnn.html

);
来源：http://dali.cashguo.top/Article/details/gttviqebmv.html

[Q02] 创建带外键的表
来源：http://dali.9152youxi.cn/Article/details/gtzpodymtv.html

CREATE TABLE orders (
来源：http://dali.xylfe.cn/Article/details/gtvjvrught.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fzhhl.top/Article/details/gtpnqeratx.html

user_id INT NOT NULL,
来源：http://dali.aibaodan.cn/Article/details/gtmumvcmug.html

amount DECIMAL(10, 2),
来源：http://dali.bjfxy.top/Article/details/gtoyyxgqse.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenjidiqi.icu/Article/details/gtzkutoqwp.html

);
来源：http://dali.sufxvd.cn/Article/details/gtzfhlbofr.html

[Q03] 增加列
来源：http://dali.aibaodan.cn/Article/details/gtxcufsrbh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.tian-w.cn/Article/details/gtdofotizy.html

[Q04] 修改列类型
来源：http://dali.yueranfly.top/Article/details/gtzgnijtak.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sysykeji.top/Article/details/gtccaaguih.html

[Q05] 重命名列
来源：http://dali.tanke756.top/Article/details/gtfljjtiqq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cheryme.top/Article/details/gtkqpsrunw.html

[Q06] 删除列
来源：http://dali.cashguo.top/Article/details/gttoxcknua.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.aibaodan.cn/Article/details/gtvwbhoytn.html

[Q07] 删除表
来源：http://dali.cheryme.top/Article/details/gtjnhdkrfs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhengqikj.top/Article/details/gtzmixwnal.html

[Q08] 创建普通索引
来源：http://dali.hongshengwenyu.top/Article/details/gtgblwlkay.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tanke756.top/Article/details/gthkictvha.html

[Q09] 创建唯一索引
来源：http://dali.ppjwa.cn/Article/details/gtpwxpylae.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gtxscgrhof.html

[Q10] 插入单行
来源：http://dali.birdmap.top/Article/details/gtbbluvouh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.pycfn.com/Article/details/gtejgnvafs.html

[Q11] 一次插入多行
来源：http://dali.xinyue.icu/Article/details/gtdxdnoian.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zycfv.cn/Article/details/gtetdaciut.html

[Q12] 插入后取自增 ID
来源：http://dali.jinqigufen.top/Article/details/gtwibuvmjh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.feifeiyinyue.top/Article/details/gtwxvaotns.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.0kj1m.cn/Article/details/gtwfiikneu.html

[Q13] 忽略重复插入
来源：http://dali.jqgufenzy.top/Article/details/gtefnzeqtl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtinxxzkok.html

[Q14] 存在则更新（upsert）
来源：http://dali.svipenyu.cn/Article/details/gtdbsdhejo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ydzc1.top/Article/details/gtljuqkktm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.redwolf501.top/Article/details/gtwjwgacwb.html

[Q15] 查询全部
来源：http://dali.smart0.xyz/Article/details/gtxewfcavz.html

SELECT * FROM users;
来源：http://dali.yj202588.top/Article/details/gtirwrdlbg.html

[Q16] 查询指定列
来源：http://dali.iojbl.cn/Article/details/gtgrjxfbyv.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtqgyztsmr.html

[Q17] 条件查询
来源：http://dali.zhoulong.xyz/Article/details/gtmcusqved.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.redwolf501.top/Article/details/gtkpvetedl.html

[Q18] 模糊匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtngyovrdk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ybcxt.top/Article/details/gtwoavkeoh.html

[Q19] 范围查询
来源：http://dali.chenlongwang.top/Article/details/gtmktsbokt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yuxming.cn/Article/details/gtmvenobjr.html

[Q20] IN 列表
来源：http://dali.bjfxy.top/Article/details/gtixhztpyc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.quarkkingdee.top/Article/details/gtafqreycw.html

[Q21] 空值判断
来源：http://dali.nanxinkj.top/Article/details/gtxckoliqp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shangyingyoupin.top/Article/details/gtpsexnygn.html

[Q22] 排序
来源：http://dali.gaohongyu789.top/Article/details/gtoetrhjua.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcljhycax.html

[Q23] 分页
来源：http://dali.jqgufenzy.top/Article/details/gtpevbtniz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hfpthk.cn/Article/details/gtvnectlak.html

[Q24] 去重
来源：http://dali.dashuyun.cn/Article/details/gtugzmqieb.html

SELECT DISTINCT city FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtwmwfjcto.html

[Q25] 只取前 N 条
来源：http://dali.svipenyu.cn/Article/details/gtazmeaxti.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.bjfxy.top/Article/details/gtbqkhuywp.html

[Q26] 计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvldxgpy.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtihpfgfcr.html

[Q27] 条件计数
来源：http://dali.cheryme.top/Article/details/gtddpzilcc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtpgrljhkr.html

[Q28] 求和与平均
来源：http://dali.sweek.top/Article/details/gtukemcnpa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtsomsqgpt.html

[Q29] 最大最小值
来源：http://dali.haohaochexian.top/Article/details/gtvmqsewuh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtyruzdcxo.html

[Q30] 分组统计
来源：http://dali.zycfv.cn/Article/details/gtmlfbhnve.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gtnfypsbnx.html

[Q31] 分组后过滤
来源：http://dali.havefunace.top/Article/details/gtkhratjvl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cheryme.top/Article/details/gtdzfktpxj.html

[Q32] 分组拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzshjxpz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gtpthtvkif.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ydzc1.top/Article/details/gtbbnkqjoq.html

[Q33] 多列分组
来源：http://dali.zhixingplan.top/Article/details/gtjgcqkevb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.andypj.xyz/Article/details/gtcxcvzdxa.html

[Q34] 每组取第一条
来源：http://dali.chenjidiqi.icu/Article/details/gthtybfhrh.html

SELECT * FROM (
来源：http://dali.wangdashe.top/Article/details/gtsctgnwpi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xuanzx.com/Article/details/gtmoauzlff.html

) t WHERE rn = 1;
来源：http://dali.ydzc1.top/Article/details/gtpkxbvfxi.html

[Q35] 内连接
来源：http://dali.chenzaomai.com/Article/details/gtpqybqavp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.c1oappe.top/Article/details/gthfdufspv.html

[Q36] 左连接
来源：http://dali.jiagoushi.top/Article/details/gtissazeez.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sysykeji.top/Article/details/gttrdilenx.html

[Q37] 右连接
来源：http://dali.jlsjyb.cn/Article/details/gtykpfslzg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.guannengcc.top/Article/details/gtpwjrojgp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj202588.top/Article/details/gtqoejxkzl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.redwolf501.top/Article/details/gtvgkqdzkx.html

[Q39] 自连接（查上下级）
来源：http://dali.guowangkeji.top/Article/details/gtapshtkoz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.aizwys.cn/Article/details/gtvhqchxdu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tanke756.top/Article/details/gtfuvsvcdy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yongpay.top/Article/details/gtweukanbz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhixingplan.top/Article/details/gtpqtzlgrv.html

[Q41] 多表连接
来源：http://dali.jqgfzy.top/Article/details/gtxebxfzjl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj20258888.top/Article/details/gtkwohxakv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.meibo888.top/Article/details/gtvgelzzgm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tianlin.xyz/Article/details/gtbivqfgav.html

[Q42] 连接条件附加过滤
来源：http://dali.yuanzhike.top/Article/details/gtxhvaiebb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.dashuyun.cn/Article/details/gtlbyendsg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.smart0.xyz/Article/details/gtrupwhwsn.html

[Q43] 标量子查询
来源：http://dali.smart0.xyz/Article/details/gtycleddxj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.wangdashe.top/Article/details/gtozslrnqt.html

[Q44] IN 子查询
来源：http://dali.jlsjyb.cn/Article/details/gtnwyzymby.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cashguo.top/Article/details/gtcfqkwfov.html

[Q45] EXISTS 判断存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbeezyntx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gtkldkiuke.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmylcrwh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gtcnbviscu.html

[Q47] 与平均值比较
来源：http://dali.svipenyu.cn/Article/details/gtuvwlkayb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.haohaochexian.top/Article/details/gtngflasav.html

[Q48] CTE 公用表表达式
来源：http://dali.zycfv.cn/Article/details/gtdolgyxij.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigfzy.top/Article/details/gtnmoqjfxq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxinkj.top/Article/details/gtvcfsnted.html

[Q49] 更新单行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlaekvsbj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tian-w.cn/Article/details/gtowfhwwrf.html

[Q50] 批量更新
来源：http://dali.sweek.top/Article/details/gtrsrhehxv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.0kj1m.cn/Article/details/gtjoplkjio.html

[Q51] 用子查询更新
来源：http://dali.guannengcc.top/Article/details/gtyayshqkp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yonumen.top/Article/details/gttrerrdzx.html

[Q52] 删除指定行
来源：http://dali.daxiang520.top/Article/details/gtviwjqkio.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xinyue.icu/Article/details/gtssxvqtxq.html

[Q53] 按条件删除
来源：http://dali.cucudq.cn/Article/details/gtxcvmbzno.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ydzc1.top/Article/details/gtkcfnyiti.html

[Q54] 清空表
来源：http://dali.hnxiangtu.top/Article/details/gtmdsndnnl.html

TRUNCATE TABLE logs;
来源：http://dali.c1oappe.top/Article/details/gticanragn.html

[Q55] 排名（并列占位）
来源：http://dali.tianlin.xyz/Article/details/gtpvzxiqkj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.snrcjt.cn/Article/details/gtraiicnvw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tianlin.xyz/Article/details/gthwrwjrea.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhongyouzk.top/Article/details/gtqtqtxmzm.html

[Q57] 行号
来源：http://dali.zhengqikj.top/Article/details/gtihjnywmm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtwanunuro.html

[Q58] 累计求和
来源：http://dali.aizwys.cn/Article/details/gtysowynxj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtmugovzjz.html

[Q59] 分组内累计
来源：http://dali.ehwqpu.com/Article/details/gtzikewpar.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtsfiytakj.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuanzx.com/Article/details/gtuncvziaa.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sxryk.cn/Article/details/gtwqdgxdvh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtmzsrxlyq.html

[Q61] 移动平均
来源：http://dali.ydzc1.top/Article/details/gtzdkbbaea.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtfhegcgca.html

[Q62] 分组占比
来源：http://dali.hywenlv.cn/Article/details/gtwznopjfd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gtcyziwhtz.html

[Q63] 开启事务
来源：http://dali.andypj.xyz/Article/details/gtxeofwvjy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.birdmap.top/Article/details/gtpornvsec.html

[Q64] 提交事务
来源：http://dali.feifeiyinyue.top/Article/details/gtmqpbrvyy.html

COMMIT;
来源：http://dali.gotoacloud.top/Article/details/gtiwevrmwe.html

[Q65] 回滚事务
来源：http://dali.ppjwa.cn/Article/details/gtamxeugww.html

ROLLBACK;
来源：http://dali.chenzaomai.com/Article/details/gttsawinne.html

[Q66] 行锁查询
来源：http://dali.zdqjudy.top/Article/details/gtanecuplp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jiagoushi.top/Article/details/gtflykrlaw.html

[Q67] 设置隔离级别
来源：http://dali.c1oappe.top/Article/details/gtuasijihd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shzxlz.cn/Article/details/gtnvmjtjwo.html

[Q68] 保存点
来源：http://dali.sysykeji.top/Article/details/gtfjrhsrkj.html

SAVEPOINT sp1;
来源：http://dali.bjfxy.top/Article/details/gtrchehfoh.html

ROLLBACK TO sp1;
来源：http://dali.jianghu66.top/Article/details/gtcygvdcau.html

[Q69] 查看执行计划
来源：http://dali.ydzc1.top/Article/details/gtokrdbijp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenlongwang.top/Article/details/gttktsjhxw.html

[Q70] 更新统计信息
来源：http://dali.jlsjyb.cn/Article/details/gtytyisiul.html

ANALYZE TABLE users;
来源：http://dali.meibo888.top/Article/details/gtisbpicvj.html

[Q71] 查看建表语句
来源：http://dali.nanxinkj.top/Article/details/gtjswqlswt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hongshengwenyu.top/Article/details/gtcqvsosqt.html

[Q72] 查看索引
来源：http://dali.guannengcc.top/Article/details/gtodqsoolw.html

SHOW INDEX FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtcarmfhma.html

[Q73] 查看表状态
来源：http://dali.cucudq.cn/Article/details/gttjmzcvse.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shuidangran.top/Article/details/gtkzsxogdk.html

[Q74] 强制使用索引
来源：http://dali.ppjwa.cn/Article/details/gtflurzeiz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.aizwys.cn/Article/details/gtwziirxea.html

[Q75] 日期格式化
来源：http://dali.gotoacloud.top/Article/details/gtakqvoacp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.316326.xyz/Article/details/gtgmuhrdlt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.guowangkeji.top/Article/details/gtprshkvhx.html

[Q76] 按天统计
来源：http://dali.daxiang520.top/Article/details/gtnjsfmhzw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tian-w.cn/Article/details/gtlqsaztkg.html

[Q77] 时间加减
来源：http://dali.ydzc1.top/Article/details/gtsnhykxxy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj20258.top/Article/details/gtyfyvovlu.html

[Q78] 当前时间
来源：http://dali.nanxinkj.top/Article/details/gtwkbqexli.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hywenlv.cn/Article/details/gtthiybbrk.html

[Q79] 字符串拼接
来源：http://dali.xinyue.icu/Article/details/gtcfatqhdw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yanxiufei.cn/Article/details/gtulydegqk.html

[Q80] 字符串截取
来源：http://dali.nanxuanxn.top/Article/details/gthpyecskt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtgqxfxnkr.html

[Q81] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgoswwlgv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtydeemxvc.html

[Q82] 字符长度与字节长度
来源：http://dali.redwolf501.top/Article/details/gttzvqwamb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtzofldzhi.html

[Q83] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gtecvqrdjh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtoykjuivs.html

[Q84] 去除首尾空格
来源：http://dali.0kj1m.cn/Article/details/gtakbvknpy.html

SELECT TRIM(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtbkoqjzdu.html

[Q85] 数值取整
来源：http://dali.gotoacloud.top/Article/details/gtvbvtagdi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.iojbl.cn/Article/details/gtebfbrgug.html

[Q86] 读取 JSON 字段
来源：http://dali.pengpengdd.cyou/Article/details/gtewekjera.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwojxymhn.html

[Q87] JSON 字段做条件
来源：http://dali.shuidangran.top/Article/details/gtodqeuowo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.quarkkingdee.top/Article/details/gtxaxllryv.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinghuilouyu.cn/Article/details/gtluovviwa.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinqigufen.top/Article/details/gtiseapide.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtmwrzfexv.html

[Q89] 判断表是否存在
来源：http://dali.iojbl.cn/Article/details/gtbhneopuo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.vqdsnc.cn/Article/details/gteiafzcxs.html

[Q90] 生成序号列
来源：http://dali.zhongyouzk.top/Article/details/gtlusteals.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.feifeiyinyue.top/Article/details/gtlcgcvjlf.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtkvtiuhsv.html

R. Bash 专题
来源：http://dali.fengsongda.top/Article/details/gtbewzfjtv.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtahtugzdz.html

[R01] shebang 与严格模式
来源：http://dali.9152youxi.cn/Article/details/gtfpyckxfh.html

#!/usr/bin/env bash
来源：http://dali.dianchejie.cn/Article/details/gtukzwmqet.html

set -euo pipefail
来源：http://dali.havefunace.top/Article/details/gthxblhldk.html

[R02] 变量赋值与使用
来源：http://dali.ybcxt.top/Article/details/gtctfokytp.html

name="Tom"; echo "$name"
来源：http://dali.yj20258888.top/Article/details/gtdhjcanjc.html

[R03] 只读变量
来源：http://dali.zhiwuduotai.top/Article/details/gtqporlmbz.html

readonly PI=3.14
来源：http://dali.mhx1999.top/Article/details/gtbibtrgkm.html

[R04] 位置参数
来源：http://dali.dianchejie.cn/Article/details/gtnuydiqfn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hfpthk.cn/Article/details/gtepgirfrs.html

[R05] 参数默认值
来源：http://dali.wangdashe.top/Article/details/gttytwkhtc.html

name="${1:-default}"
来源：http://dali.yueranfly.top/Article/details/gtzmwfulme.html

[R06] 判断命令是否存在
来源：http://dali.hywenlv.cn/Article/details/gtmzdacjsr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.smart0.xyz/Article/details/gtvuqxeamm.html

[R07] if 判断文件
来源：http://dali.yanxiufei.cn/Article/details/gtazppkeoc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ppjwa.cn/Article/details/gtgkorzuih.html

[R08] 数值比较
来源：http://dali.wangdashe.top/Article/details/gtcbjmeres.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.9152youxi.cn/Article/details/gtjitpwfga.html

[R09] 字符串比较
来源：http://dali.xylfe.cn/Article/details/gthczkdwql.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jyoumei.cn/Article/details/gtdvkdvxpv.html

[R10] 正则匹配
来源：http://dali.zhengqikj.top/Article/details/gteamnrjux.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.quarkkingdee.top/Article/details/gtigoptntz.html

[R11] case 多分支
来源：http://dali.tianlin.xyz/Article/details/gtqrnglvie.html

case "$1" in
来源：http://dali.redwolf501.top/Article/details/gtpugvajgi.html

start) echo "启动" ;;
来源：http://dali.guowangkeji.top/Article/details/gtpbrzebjl.html

stop)  echo "停止" ;;
来源：http://dali.yanxiufei.cn/Article/details/gtmzhdozoy.html

*)     echo "未知命令" ;;
来源：http://dali.shuidangran.top/Article/details/gtxnyrrget.html

esac
来源：http://dali.shangyingyoupin.top/Article/details/gtqsvzuaqu.html

[R12] for 遍历文件
来源：http://dali.sysykeji.top/Article/details/gthmndaqug.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gtzirmvlko.html

[R13] for 计数循环
来源：http://dali.cucudq.cn/Article/details/gtmbwwslwl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtlsxpbazw.html

[R14] C 风格 for
来源：http://dali.jyoumei.cn/Article/details/gtigdgzbhb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nanxuanxn.top/Article/details/gtkgbijfja.html

[R15] while 逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtymrtexcr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtjusodvei.html

[R16] until 等待条件
来源：http://dali.cheryme.top/Article/details/gtkozdofib.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gtymtjpjxb.html

[R17] 数组定义与取值
来源：http://dali.guannengcc.top/Article/details/gtuezqboba.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.c1oappe.top/Article/details/gtaxjactan.html

[R18] 遍历数组
来源：http://dali.ivvv.top/Article/details/gtmlmfrqzi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangdashe.top/Article/details/gtvflmfywv.html

[R19] 数组长度
来源：http://dali.daxiang520.top/Article/details/gtlkwfghkl.html

echo "${#arr[@]}"
来源：http://dali.havefunace.top/Article/details/gtjkascfgs.html

[R20] 关联数组（字典）
来源：http://dali.yuxming.cn/Article/details/gtsosiqvrl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigufen.top/Article/details/gttrlcqliw.html

[R21] 字符串长度
来源：http://dali.mhx1999.top/Article/details/gttdhdxbht.html

echo "${#s}"
来源：http://dali.jlsjyb.cn/Article/details/gtsfayerdj.html

[R22] 截取子串
来源：http://dali.chenjidiqi.icu/Article/details/gtlnlmmihq.html

echo "${s:0:5}"
来源：http://dali.hnqzz.top/Article/details/gttwcguoxi.html

[R23] 字符串替换
来源：http://dali.c1oappe.top/Article/details/gtotkdoyun.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dianchejie.cn/Article/details/gtzvfxsvoy.html

[R24] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gtxajkghta.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjgqwftd.html

[R25] 去后缀 / 去前缀
来源：http://dali.wangdashe.top/Article/details/gtylajlyld.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hfpthk.cn/Article/details/gtsgeduwhe.html

[R26] 命令替换
来源：http://dali.aibaodan.cn/Article/details/gtvflxmofa.html

now=$(date +%F); echo "$now"
来源：http://dali.pengpengdd.cyou/Article/details/gtjcmzjjhd.html

[R27] 算术展开
来源：http://dali.yj202588.top/Article/details/gtkjreqpqg.html

echo $((1 + 2 * 3))
来源：http://dali.fengsongda.top/Article/details/gtrrqpfbsz.html

[R28] 浮点运算
来源：http://dali.nanxinkj.top/Article/details/gtlgbmrbck.html

echo "scale=2; 10/3" | bc
来源：http://dali.guowangkeji.top/Article/details/gtbmhidrnl.html

[R29] 定义函数
来源：http://dali.tanke756.top/Article/details/gtahdgtizj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ivvv.top/Article/details/gtpceaojdg.html

[R30] 函数返回状态码
来源：http://dali.sweek.top/Article/details/gtpjgxszlb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuanzhike.top/Article/details/gttpbjguix.html

[R31] 局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gtslevzcgg.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj202588.top/Article/details/gtmgvhwjqj.html

[R32] 参数个数校验
来源：http://dali.yj20258888.top/Article/details/gtmkdoyvos.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.havefunace.top/Article/details/gtnarvrlmi.html

[R33] 捕获错误并提示行号
来源：http://dali.pycfn.com/Article/details/gteonbwggr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenjidiqi.icu/Article/details/gtntmpegmj.html

[R34] 退出时清理
来源：http://dali.yanxiufei.cn/Article/details/gtjdgdjxcm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gtensfbcpt.html

[R35] 后台执行并等待
来源：http://dali.smart0.xyz/Article/details/gtmwbjcayp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yanxiufei.cn/Article/details/gtlufjvgik.html

[R36] 并发执行多个任务
来源：http://dali.pengpengdd.cyou/Article/details/gtcbvrunak.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xinyue.icu/Article/details/gtxwhthiwo.html

[R37] 把输出赋给变量
来源：http://dali.chenzaomai.com/Article/details/gtfzuxiway.html


<!-- 参考信息 -->