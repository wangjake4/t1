代发 wailian999

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ivvv.top/Article/details/gtnckdkyhh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tian-w.cn/Article/details/gtaqokeesj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pycfn.com/Article/details/gthwmihmio.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zdqjudy.top/Article/details/gtqjysbqzv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sweek.top/Article/details/gtbvhszniu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.vqdsnc.cn/Article/details/gteudkmvam.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dianchejie.cn/Article/details/gtmtybxsjd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xziqi.cn/Article/details/gttjxbeakf.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtnglbwiis.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yongpay.top/Article/details/gtkdlvhmbh.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtptffeoey.html

[Q01] 创建表
来源：http://dali.andypj.xyz/Article/details/gtecefylfz.html

CREATE TABLE users (
来源：http://dali.dashuyun.cn/Article/details/gtxarmtfyh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sysykeji.top/Article/details/gtfsiaumza.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jyoumei.cn/Article/details/gtbkoyyffh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.guannengcc.top/Article/details/gtyjqpephe.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.c1oappe.top/Article/details/gtgfpdmqbx.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gtxmpnkeqa.html

[Q02] 创建带外键的表
来源：http://dali.ehwqpu.com/Article/details/gtcervqqbi.html

CREATE TABLE orders (
来源：http://dali.jqgfzy.top/Article/details/gtoitfwbnc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gttigvkzdx.html

user_id INT NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gtybuflmsd.html

amount DECIMAL(10, 2),
来源：http://dali.yj20258888.top/Article/details/gtmwytxfgd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sxryk.cn/Article/details/gthkjvbjzj.html

);
来源：http://dali.fzhhl.top/Article/details/gtfjfcahdi.html

[Q03] 增加列
来源：http://dali.shuidangran.top/Article/details/gtifkjbide.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinqigufen.top/Article/details/gtxhysvpts.html

[Q04] 修改列类型
来源：http://dali.zycfv.cn/Article/details/gtqezetwll.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zdqjudy.top/Article/details/gtnnffzwia.html

[Q05] 重命名列
来源：http://dali.xylfe.cn/Article/details/gtzczhzshj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sufxvd.cn/Article/details/gtgavjkyzz.html

[Q06] 删除列
来源：http://dali.dianchejie.cn/Article/details/gttibsrtkk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.aizwys.cn/Article/details/gtfyvmltaz.html

[Q07] 删除表
来源：http://dali.sweek.top/Article/details/gteyvjgghv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.redwolf501.top/Article/details/gtfiydixew.html

[Q08] 创建普通索引
来源：http://dali.jqgfzy.top/Article/details/gtxckpkren.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj202588.top/Article/details/gtkrmssamx.html

[Q09] 创建唯一索引
来源：http://dali.chenlongwang.top/Article/details/gtrrecrazu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhiwuduotai.top/Article/details/gtipilqexk.html

[Q10] 插入单行
来源：http://dali.ehwqpu.com/Article/details/gtucqckyyv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gtsfbpyuat.html

[Q11] 一次插入多行
来源：http://dali.cheryme.top/Article/details/gtmkqnnztn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jiagoushi.top/Article/details/gtveicmvjg.html

[Q12] 插入后取自增 ID
来源：http://dali.jiagoushi.top/Article/details/gtphcuvddb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xziqi.cn/Article/details/gttbjymkxp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigufen.top/Article/details/gtqvfckhoj.html

[Q13] 忽略重复插入
来源：http://dali.ppjwa.cn/Article/details/gtimbsmkds.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.meibo888.top/Article/details/gtjskdlqyx.html

[Q14] 存在则更新（upsert）
来源：http://dali.cdnleiting.top/Article/details/gtzeucudel.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenlongwang.top/Article/details/gtbtfpaxtx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yj20258888.top/Article/details/gtrjjcxksf.html

[Q15] 查询全部
来源：http://dali.gzhubu.top/Article/details/gtdpnatjti.html

SELECT * FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtvwlceglr.html

[Q16] 查询指定列
来源：http://dali.dashuyun.cn/Article/details/gtdgixrflu.html

SELECT id, name FROM users;
来源：http://dali.hnqzz.top/Article/details/gtioykoxtr.html

[Q17] 条件查询
来源：http://dali.smart0.xyz/Article/details/gtxmnsgjgv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ydzc1.top/Article/details/gttrhxemso.html

[Q18] 模糊匹配
来源：http://dali.vqdsnc.cn/Article/details/gtygecwbqp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hongshengwenyu.top/Article/details/gtluwugold.html

[Q19] 范围查询
来源：http://dali.hfpthk.cn/Article/details/gtujgkmaar.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ppjwa.cn/Article/details/gtngaceuox.html

[Q20] IN 列表
来源：http://dali.hnxiangtu.top/Article/details/gtklozyckn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zdqjudy.top/Article/details/gtqvienjkj.html

[Q21] 空值判断
来源：http://dali.yanxiufei.cn/Article/details/gtlblildfv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fengsongda.top/Article/details/gtuocgtxgy.html

[Q22] 排序
来源：http://dali.cqqwz.cn/Article/details/gtgbywkweg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xuetiantiany.cn/Article/details/gtwkobcrex.html

[Q23] 分页
来源：http://dali.smart0.xyz/Article/details/gteqaqjvqb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.0kj1m.cn/Article/details/gtwrzgwimh.html

[Q24] 去重
来源：http://dali.ivvv.top/Article/details/gtofzxptui.html

SELECT DISTINCT city FROM users;
来源：http://dali.sysykeji.top/Article/details/gtqfthvhiz.html

[Q25] 只取前 N 条
来源：http://dali.wangshuangyany.cn/Article/details/gtaiffkjtg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenzaomai.com/Article/details/gtlpklzcdn.html

[Q26] 计数
来源：http://dali.jqgfzy.top/Article/details/gtgamwauca.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtrayuyshp.html

[Q27] 条件计数
来源：http://dali.gogol.net.cn/Article/details/gtizkfyaau.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.smart0.xyz/Article/details/gtvhdbphfj.html

[Q28] 求和与平均
来源：http://dali.ppjwa.cn/Article/details/gtrhfionrx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gttmsfktnb.html

[Q29] 最大最小值
来源：http://dali.gotoacloud.top/Article/details/gtpmwstlsy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtaitpvheg.html

[Q30] 分组统计
来源：http://dali.nanxinkj.top/Article/details/gtmnfdbqol.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtxyfyuggn.html

[Q31] 分组后过滤
来源：http://dali.hnxiangtu.top/Article/details/gtwyrslces.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ehwqpu.com/Article/details/gtrfehgumr.html

[Q32] 分组拼接字符串
来源：http://dali.sxryk.cn/Article/details/gtelusxkbe.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gtpikhhnsk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.birdmap.top/Article/details/gtqxodzutr.html

[Q33] 多列分组
来源：http://dali.nanxuanxn.top/Article/details/gtkgtfauxb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ivvv.top/Article/details/gtjivsyvvl.html

[Q34] 每组取第一条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffvzrhlo.html

SELECT * FROM (
来源：http://dali.meibo888.top/Article/details/gtkavszhka.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nanxinkj.top/Article/details/gtkwxxvifu.html

) t WHERE rn = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtbptspild.html

[Q35] 内连接
来源：http://dali.0kj1m.cn/Article/details/gtemjivbda.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tian-w.cn/Article/details/gtojfypqwx.html

[Q36] 左连接
来源：http://dali.yangfankeji.com/Article/details/gtacvhqogx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gtllztgdvs.html

[Q37] 右连接
来源：http://dali.jqgufenzy.top/Article/details/gtzkqpywph.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqasgesb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhengqikj.top/Article/details/gtowpdcoxo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gtaqtdqwec.html

[Q39] 自连接（查上下级）
来源：http://dali.zycfv.cn/Article/details/gtparyviyp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhoulong.xyz/Article/details/gtjbizzvei.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.dashuyun.cn/Article/details/gtfwhfkrnh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenjidiqi.icu/Article/details/gtaswjcagw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.redwolf501.top/Article/details/gtbsopachg.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gtagmsckqk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.meibo888.top/Article/details/gtgqvmicfb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrevhsuvb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenjidiqi.icu/Article/details/gttjwnwmpx.html

[Q42] 连接条件附加过滤
来源：http://dali.jiagoushi.top/Article/details/gtcxvebfcq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yanxiufei.cn/Article/details/gtiqlequrw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbrjrjzr.html

[Q43] 标量子查询
来源：http://dali.ppjwa.cn/Article/details/gtbenxdruh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhengqikj.top/Article/details/gtoxmfirfq.html

[Q44] IN 子查询
来源：http://dali.cashguo.top/Article/details/gttumcpzwm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jyoumei.cn/Article/details/gtymmozulq.html

[Q45] EXISTS 判断存在
来源：http://dali.bjfxy.top/Article/details/gtwlovzrkr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pengpengdd.cyou/Article/details/gtlegrpyph.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbtwliud.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgufenzy.top/Article/details/gtryzayvzd.html

[Q47] 与平均值比较
来源：http://dali.aizwys.cn/Article/details/gtugdwqeib.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdulpivk.html

[Q48] CTE 公用表表达式
来源：http://dali.aibaodan.cn/Article/details/gtcunucnxg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwgdsety.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.kuanghao11.cn/Article/details/gtnqnfjqka.html

[Q49] 更新单行
来源：http://dali.c1oappe.top/Article/details/gtptfeebjq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtixobhqoo.html

[Q50] 批量更新
来源：http://dali.kuanghao11.cn/Article/details/gtgchiyhrl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuujlehol.html

[Q51] 用子查询更新
来源：http://dali.shuidangran.top/Article/details/gtwheiszqo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtmzbvfccl.html

[Q52] 删除指定行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbagbyyp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jianghu66.top/Article/details/gtyogxvxpf.html

[Q53] 按条件删除
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxksgrxjz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhixingplan.top/Article/details/gtldclhmxa.html

[Q54] 清空表
来源：http://dali.yj20258.top/Article/details/gtaejkwbjv.html

TRUNCATE TABLE logs;
来源：http://dali.guannengcc.top/Article/details/gtixxldusk.html

[Q55] 排名（并列占位）
来源：http://dali.cdnleiting.top/Article/details/gtjmykneah.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gtnwcrqoza.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ybcxt.top/Article/details/gtogvjcoda.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhongyouzk.top/Article/details/gtnqceoxah.html

[Q57] 行号
来源：http://dali.316326.xyz/Article/details/gttwrnszgu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwuztmlo.html

[Q58] 累计求和
来源：http://dali.jyoumei.cn/Article/details/gtusdiywwl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtqeslvgfj.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gtnlivsbms.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtmpuylfod.html

[Q60] 取上一行 / 下一行
来源：http://dali.gaohongyu789.top/Article/details/gtgoualosa.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhongyouzk.top/Article/details/gtmodpkfrk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtjyyrddrn.html

[Q61] 移动平均
来源：http://dali.tian-w.cn/Article/details/gtlqufpfea.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sweek.top/Article/details/gtrvkodmsb.html

[Q62] 分组占比
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqcgsejd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtdhvellaj.html

[Q63] 开启事务
来源：http://dali.cheryme.top/Article/details/gteouwlqtr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhongyouzk.top/Article/details/gtwnhugkdo.html

[Q64] 提交事务
来源：http://dali.iojbl.cn/Article/details/gtwdsdppmo.html

COMMIT;
来源：http://dali.chenlongwang.top/Article/details/gtxddjtsgf.html

[Q65] 回滚事务
来源：http://dali.gaohongyu789.top/Article/details/gteecybpqf.html

ROLLBACK;
来源：http://dali.ybcxt.top/Article/details/gtavrminoj.html

[Q66] 行锁查询
来源：http://dali.jlsjyb.cn/Article/details/gtreyscvui.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yongpay.top/Article/details/gtbbufboqz.html

[Q67] 设置隔离级别
来源：http://dali.feifeiyinyue.top/Article/details/gtcdxthhjk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.birdmap.top/Article/details/gtdsyeatdq.html

[Q68] 保存点
来源：http://dali.hnqzz.top/Article/details/gtxoqadizj.html

SAVEPOINT sp1;
来源：http://dali.yueranfly.top/Article/details/gtatcklidj.html

ROLLBACK TO sp1;
来源：http://dali.xylfe.cn/Article/details/gtzylvriad.html

[Q69] 查看执行计划
来源：http://dali.chenjidiqi.icu/Article/details/gteuepszhi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj202588.top/Article/details/gtimrajudo.html

[Q70] 更新统计信息
来源：http://dali.yj20258.top/Article/details/gtdsqfqljt.html

ANALYZE TABLE users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgulsyww.html

[Q71] 查看建表语句
来源：http://dali.gogol.net.cn/Article/details/gtgtalzknm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ppjwa.cn/Article/details/gtirmzaxiu.html

[Q72] 查看索引
来源：http://dali.snrcjt.cn/Article/details/gtlxyovkwc.html

SHOW INDEX FROM users;
来源：http://dali.hammf.cn/Article/details/gtwfxyfsqz.html

[Q73] 查看表状态
来源：http://dali.redwolf501.top/Article/details/gtpbkspbem.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258888.top/Article/details/gtmsnqtdxi.html

[Q74] 强制使用索引
来源：http://dali.yuxming.cn/Article/details/gtqjtdtcff.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenlongwang.top/Article/details/gtfiwpfrpa.html

[Q75] 日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtdxczvtyz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtdghchtvm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dashuyun.cn/Article/details/gtowoovfax.html

[Q76] 按天统计
来源：http://dali.cdnleiting.top/Article/details/gtofvkjiom.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.snrcjt.cn/Article/details/gtlwtvugtc.html

[Q77] 时间加减
来源：http://dali.yuanzhike.top/Article/details/gtetpoksgi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xziqi.cn/Article/details/gtrvkzefog.html

[Q78] 当前时间
来源：http://dali.hysaishi.cn/Article/details/gtdgmihaoa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cqqwz.cn/Article/details/gtbjhveohr.html

[Q79] 字符串拼接
来源：http://dali.yj202588.top/Article/details/gtnsjlxfbi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hywenlv.cn/Article/details/gtjgyxtddt.html

[Q80] 字符串截取
来源：http://dali.chenjidiqi.icu/Article/details/gtlsafxwet.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gthywfeehs.html

[Q81] 字符串替换
来源：http://dali.wangdashe.top/Article/details/gtyaaqqgal.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqgbygve.html

[Q82] 字符长度与字节长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyosbmqlb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtdicphvsr.html

[Q83] 大小写转换
来源：http://dali.aizwys.cn/Article/details/gtcvghwjqn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtkzwobudo.html

[Q84] 去除首尾空格
来源：http://dali.nwbrower.top/Article/details/gttuamrmxw.html

SELECT TRIM(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gthjzjiahn.html

[Q85] 数值取整
来源：http://dali.yonumen.top/Article/details/gtbqfnyswz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shuidangran.top/Article/details/gtxrdfsnlo.html

[Q86] 读取 JSON 字段
来源：http://dali.yvedp.cn/Article/details/gthexwqzbu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.pycfn.com/Article/details/gtflngkabh.html

[Q87] JSON 字段做条件
来源：http://dali.316326.xyz/Article/details/gtsbchliza.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yueranfly.top/Article/details/gtslnvpfaf.html

[Q88] 行转列（条件聚合）
来源：http://dali.tianlin.xyz/Article/details/gtzwvhredl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cucudq.cn/Article/details/gtqbjxypxa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yonumen.top/Article/details/gturnfhdng.html

[Q89] 判断表是否存在
来源：http://dali.tanke756.top/Article/details/gtikayvtyw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngtwvuge.html

[Q90] 生成序号列
来源：http://dali.xziqi.cn/Article/details/gtkoabmdhg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gogol.net.cn/Article/details/gtuhzoifyb.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtkkayrdhw.html

R. Bash 专题
来源：http://dali.zhongyouzk.top/Article/details/gtcuxevsws.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtedaysqei.html

[R01] shebang 与严格模式
来源：http://dali.ppjwa.cn/Article/details/gtglqfdkix.html

#!/usr/bin/env bash
来源：http://dali.yj202588.top/Article/details/gtshzmwjni.html

set -euo pipefail
来源：http://dali.9152youxi.cn/Article/details/gtkwtnezcu.html

[R02] 变量赋值与使用
来源：http://dali.vqdsnc.cn/Article/details/gthgbzbdmi.html

name="Tom"; echo "$name"
来源：http://dali.yuxming.cn/Article/details/gtcasvbhzv.html

[R03] 只读变量
来源：http://dali.xuetiantiany.cn/Article/details/gtxdsexias.html

readonly PI=3.14
来源：http://dali.jinghuilouyu.cn/Article/details/gtedsyzfkp.html

[R04] 位置参数
来源：http://dali.ppjwa.cn/Article/details/gtlaajobtf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shzxlz.cn/Article/details/gtjlagmjkw.html

[R05] 参数默认值
来源：http://dali.yuanzhike.top/Article/details/gtzfgswqxn.html

name="${1:-default}"
来源：http://dali.nanxinkj.top/Article/details/gttbqaemsw.html

[R06] 判断命令是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtishearkf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ppjwa.cn/Article/details/gtcrmwhppe.html

[R07] if 判断文件
来源：http://dali.sufxvd.cn/Article/details/gthuklgkji.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cqqwz.cn/Article/details/gtpscxuegv.html

[R08] 数值比较
来源：http://dali.wangshuangyany.cn/Article/details/gtkhxymmqk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shuidangran.top/Article/details/gtpofgcjir.html

[R09] 字符串比较
来源：http://dali.zdqjudy.top/Article/details/gtzfprmpmk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtkklqzyme.html

[R10] 正则匹配
来源：http://dali.9152youxi.cn/Article/details/gtmctupfot.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xylfe.cn/Article/details/gtvkanneve.html

[R11] case 多分支
来源：http://dali.nanxinkj.top/Article/details/gtxkhmrtuv.html

case "$1" in
来源：http://dali.feifeiyinyue.top/Article/details/gtyczlpevf.html

start) echo "启动" ;;
来源：http://dali.snrcjt.cn/Article/details/gtbjrwnzeo.html

stop)  echo "停止" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtyyxihvsg.html

*)     echo "未知命令" ;;
来源：http://dali.tianlin.xyz/Article/details/gtdmheyeis.html

esac
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjiytkyh.html

[R12] for 遍历文件
来源：http://dali.guannengcc.top/Article/details/gtcfzmeimy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.9152youxi.cn/Article/details/gtgceptwvu.html

[R13] for 计数循环
来源：http://dali.kuanghao11.cn/Article/details/gtkhwnwoit.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.dashuyun.cn/Article/details/gtesxjoqcp.html

[R14] C 风格 for
来源：http://dali.jinghuilouyu.cn/Article/details/gtrukhqdmg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gtfxwuvlzt.html

[R15] while 逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtnbfkbcys.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yvedp.cn/Article/details/gtqmpvmafw.html

[R16] until 等待条件
来源：http://dali.chenjidiqi.icu/Article/details/gtmtmfgzag.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzdzqwpb.html

[R17] 数组定义与取值
来源：http://dali.wangshuangyany.cn/Article/details/gtivxkwhtl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfauwlnkv.html

[R18] 遍历数组
来源：http://dali.tian-w.cn/Article/details/gtksddqhbw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yuanzhike.top/Article/details/gtmhfrtwol.html

[R19] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gttlpvsboq.html

echo "${#arr[@]}"
来源：http://dali.zhiwuduotai.top/Article/details/gtiainjjpw.html

[R20] 关联数组（字典）
来源：http://dali.pycfn.com/Article/details/gttypicxuz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yanxiufei.cn/Article/details/gtxhqzcwjf.html

[R21] 字符串长度
来源：http://dali.yonumen.top/Article/details/gtdwiravph.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gtawgttlsx.html

[R22] 截取子串
来源：http://dali.gzhubu.top/Article/details/gtopsdundu.html

echo "${s:0:5}"
来源：http://dali.yongpay.top/Article/details/gtkjejxipn.html

[R23] 字符串替换
来源：http://dali.tanke756.top/Article/details/gtoiplczzb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tianlin.xyz/Article/details/gtwfoabbdc.html

[R24] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gtujsqfpvo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuanzhike.top/Article/details/gtkitghvxk.html

[R25] 去后缀 / 去前缀
来源：http://dali.smart0.xyz/Article/details/gtnoaotdmu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.dianchejie.cn/Article/details/gtjvjwajpp.html

[R26] 命令替换
来源：http://dali.jiagoushi.top/Article/details/gtjbkdhfta.html

now=$(date +%F); echo "$now"
来源：http://dali.nanxuanxn.top/Article/details/gtycbotiro.html

[R27] 算术展开
来源：http://dali.zhiwuduotai.top/Article/details/gtrulwtdve.html

echo $((1 + 2 * 3))
来源：http://dali.aizwys.cn/Article/details/gtkamkxpyf.html

[R28] 浮点运算
来源：http://dali.jinqigfzy.top/Article/details/gtrqdntgxq.html

echo "scale=2; 10/3" | bc
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjnkbvpu.html

[R29] 定义函数
来源：http://dali.hfpthk.cn/Article/details/gthngcwkyk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gogol.net.cn/Article/details/gtnonrrfth.html

[R30] 函数返回状态码
来源：http://dali.wangdashe.top/Article/details/gttfmigvsu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.9152youxi.cn/Article/details/gtgyfoajoo.html

[R31] 局部变量
来源：http://dali.0kj1m.cn/Article/details/gtodsjfthq.html

f() { local x=1; echo "$x"; }
来源：http://dali.guannengcc.top/Article/details/gtvskaxswx.html

[R32] 参数个数校验
来源：http://dali.nanxuanxn.top/Article/details/gtdhznwenu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gtdgnfbofd.html

[R33] 捕获错误并提示行号
来源：http://dali.hongshengwenyu.top/Article/details/gtsnetenhj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zycfv.cn/Article/details/gtrockhctn.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gtukrywjvk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.mhx1999.top/Article/details/gtvnpmnxsc.html

[R35] 后台执行并等待
来源：http://dali.yvedp.cn/Article/details/gtnsxosflr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daria6918.cn/Article/details/gtqjmatxnn.html

[R36] 并发执行多个任务
来源：http://dali.kuanghao11.cn/Article/details/gtxdzoefft.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zdqjudy.top/Article/details/gtqkamiacx.html

[R37] 把输出赋给变量
来源：http://dali.ybcxt.top/Article/details/gthwuzilch.html

files=$(ls -1)
来源：http://dali.fengsongda.top/Article/details/gtpweaqibr.html

[R38] 管道串联
来源：http://dali.jinghuilouyu.cn/Article/details/gtulttlrbn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgfzy.top/Article/details/gtjrrrtifm.html

[R39] 重定向标准输出与错误
来源：http://dali.daxiang520.top/Article/details/gtnfkfyayn.html


<!-- 参考信息 -->