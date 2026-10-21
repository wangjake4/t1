代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.svipenyu.cn/Article/details/gttrbjfrrc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gtcwgkulmz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gtcikrvwyf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xylfe.cn/Article/details/gtolezlhha.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hongshengwenyu.top/Article/details/gtuikpuedz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ehwqpu.com/Article/details/gtjqoogwuf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fengsongda.top/Article/details/gtgynbvxcn.html

[P08] 处理浮点精度问题
来源：http://dali.vqdsnc.cn/Article/details/gtkfwrrrbj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ppjwa.cn/Article/details/gtieillkws.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.fzhhl.top/Article/details/gtfqmypexf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhongyouzk.top/Article/details/gtwohcmtgh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yueranfly.top/Article/details/gtsipcwgjc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nanxuanxn.top/Article/details/gturlgqbke.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jqgfzy.top/Article/details/gtyhundfna.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hysaishi.cn/Article/details/gtgunlvref.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.haohaochexian.top/Article/details/gtxpaqrdkg.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtswjaafel.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yuxming.cn/Article/details/gtkbgburbm.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtitdssehc.html

[Q01] 创建表
来源：http://dali.gaohongyu789.top/Article/details/gtozontwvn.html

CREATE TABLE users (
来源：http://dali.yvedp.cn/Article/details/gtodvifjaq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shuidangran.top/Article/details/gtxvaetlqr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gthgsijzrw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xziqi.cn/Article/details/gtucwrekvt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.mhx1999.top/Article/details/gtgbslfuoe.html

);
来源：http://dali.nwbrower.top/Article/details/gtddqerhjd.html

[Q02] 创建带外键的表
来源：http://dali.havefunace.top/Article/details/gtjtmklhax.html

CREATE TABLE orders (
来源：http://dali.fengsongda.top/Article/details/gtlocwtddm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.mhx1999.top/Article/details/gtskhvqviy.html

user_id INT NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gtjvhtpyhq.html

amount DECIMAL(10, 2),
来源：http://dali.xylfe.cn/Article/details/gtkekgjzqe.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.snrcjt.cn/Article/details/gtwzbjorbn.html

);
来源：http://dali.quarkkingdee.top/Article/details/gtbhxuczex.html

[Q03] 增加列
来源：http://dali.gogol.net.cn/Article/details/gtnwsdukpt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hysaishi.cn/Article/details/gtgbnpmtrs.html

[Q04] 修改列类型
来源：http://dali.gotoacloud.top/Article/details/gtvnzyktkm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.svipenyu.cn/Article/details/gtojfnsveo.html

[Q05] 重命名列
来源：http://dali.nanxuanxn.top/Article/details/gtxtyiqjlj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dashuyun.cn/Article/details/gtkstqetbb.html

[Q06] 删除列
来源：http://dali.fengsongda.top/Article/details/gtjeamhdyx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.wangdashe.top/Article/details/gtxnxlsksz.html

[Q07] 删除表
来源：http://dali.sufxvd.cn/Article/details/gtvltjppjk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ybcxt.top/Article/details/gtckcxocxc.html

[Q08] 创建普通索引
来源：http://dali.cheryme.top/Article/details/gtecrrryqq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yueranfly.top/Article/details/gtbhgqcybv.html

[Q09] 创建唯一索引
来源：http://dali.dashuyun.cn/Article/details/gtwvybqklg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shanyushiyangkeji.top/Article/details/gteuqpebze.html

[Q10] 插入单行
来源：http://dali.aizwys.cn/Article/details/gtdwkfczys.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuxming.cn/Article/details/gtxvwvahnq.html

[Q11] 一次插入多行
来源：http://dali.zhiwuduotai.top/Article/details/gtqmypfgok.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yueranfly.top/Article/details/gtofubwicg.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258888.top/Article/details/gtpdnphahn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sufxvd.cn/Article/details/gtolgmghzt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xinyue.icu/Article/details/gtlqkqijrj.html

[Q13] 忽略重复插入
来源：http://dali.svipenyu.cn/Article/details/gtvftrtjgc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtctheuxhj.html

[Q14] 存在则更新（upsert）
来源：http://dali.aizwys.cn/Article/details/gtcbxkqmgn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jqgfzy.top/Article/details/gtbfitjild.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hnxiangtu.top/Article/details/gtqxwnkxmy.html

[Q15] 查询全部
来源：http://dali.sysykeji.top/Article/details/gtlyughctj.html

SELECT * FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtfzkwwcfe.html

[Q16] 查询指定列
来源：http://dali.yanxiufei.cn/Article/details/gtosxdnkix.html

SELECT id, name FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtexzdrrak.html

[Q17] 条件查询
来源：http://dali.hammf.cn/Article/details/gtjnfvbefi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtxwsgsoao.html

[Q18] 模糊匹配
来源：http://dali.guowangkeji.top/Article/details/gtjlysjiyi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shuidangran.top/Article/details/gtcjvhwhre.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gtsiljoubr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj20258.top/Article/details/gthacivnja.html

[Q20] IN 列表
来源：http://dali.yj20258888.top/Article/details/gtacsryhwp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj20258888.top/Article/details/gtavouursd.html

[Q21] 空值判断
来源：http://dali.xinyue.icu/Article/details/gtyapkhjwb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.9152youxi.cn/Article/details/gtgiimenyr.html

[Q22] 排序
来源：http://dali.c1oappe.top/Article/details/gtixpdwano.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jqgfzy.top/Article/details/gthsrnhvnt.html

[Q23] 分页
来源：http://dali.aibaodan.cn/Article/details/gtgkxmfbpd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zycfv.cn/Article/details/gtanewcymk.html

[Q24] 去重
来源：http://dali.yj20258.top/Article/details/gtudlajspe.html

SELECT DISTINCT city FROM users;
来源：http://dali.cashguo.top/Article/details/gtlttjhxfg.html

[Q25] 只取前 N 条
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjuwnjai.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yanxiufei.cn/Article/details/gtvubizcbi.html

[Q26] 计数
来源：http://dali.tianlin.xyz/Article/details/gtiesvrixw.html

SELECT COUNT(*) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtxlepgkxj.html

[Q27] 条件计数
来源：http://dali.sysykeji.top/Article/details/gtcsiekfud.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtabqnpqnd.html

[Q28] 求和与平均
来源：http://dali.meibo888.top/Article/details/gtfocztdma.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.pycfn.com/Article/details/gtgopeeajq.html

[Q29] 最大最小值
来源：http://dali.jqgfzy.top/Article/details/gtlboknehw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtpzbgcsbe.html

[Q30] 分组统计
来源：http://dali.sysykeji.top/Article/details/gtwhgasgpj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gtwknrnwuc.html

[Q31] 分组后过滤
来源：http://dali.guannengcc.top/Article/details/gtpgygzkjg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cdnleiting.top/Article/details/gtxmuhikst.html

[Q32] 分组拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtdabhyjdw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gtjpjkyjta.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhiwuduotai.top/Article/details/gtwqvzshxa.html

[Q33] 多列分组
来源：http://dali.dianchejie.cn/Article/details/gthlplqaxf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqgwojvq.html

[Q34] 每组取第一条
来源：http://dali.nwbrower.top/Article/details/gtquhwmkya.html

SELECT * FROM (
来源：http://dali.xylfe.cn/Article/details/gtjuchjtwy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.svipenyu.cn/Article/details/gtujbahoyt.html

) t WHERE rn = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtaqllxyjv.html

[Q35] 内连接
来源：http://dali.jqgfzy.top/Article/details/gtkeoitfhx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gtjxjfcmuk.html

[Q36] 左连接
来源：http://dali.yuxming.cn/Article/details/gtuwyrmbsj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258888.top/Article/details/gtvnivedbs.html

[Q37] 右连接
来源：http://dali.hysaishi.cn/Article/details/gtaifyzoqh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yvedp.cn/Article/details/gtttmoiazm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gaohongyu789.top/Article/details/gtqiteyxnl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shzxlz.cn/Article/details/gtvhsqqvvv.html

[Q39] 自连接（查上下级）
来源：http://dali.cdnleiting.top/Article/details/gtwwjbddpl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.snrcjt.cn/Article/details/gtrrluxufs.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhiwuduotai.top/Article/details/gttjzoayty.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gzhubu.top/Article/details/gtysaniixw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zycfv.cn/Article/details/gtwckskqjj.html

[Q41] 多表连接
来源：http://dali.shzxlz.cn/Article/details/gttcqpkein.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shzxlz.cn/Article/details/gtdpamlyvw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.quarkkingdee.top/Article/details/gtorjovanv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sweek.top/Article/details/gtdepqzbvn.html

[Q42] 连接条件附加过滤
来源：http://dali.shuidangran.top/Article/details/gthlhmamth.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj20258.top/Article/details/gtmgghevkx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tianlin.xyz/Article/details/gtyaiaptqb.html

[Q43] 标量子查询
来源：http://dali.aizwys.cn/Article/details/gtgcxrlkva.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cheryme.top/Article/details/gtwzxupqlz.html

[Q44] IN 子查询
来源：http://dali.feifeiyinyue.top/Article/details/gtzroyrwct.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jlsjyb.cn/Article/details/gtvcvyflhz.html

[Q45] EXISTS 判断存在
来源：http://dali.jlsjyb.cn/Article/details/gthqyppikw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gtlsvedyut.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yueranfly.top/Article/details/gtfhuclcgt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tianlin.xyz/Article/details/gtatzwepck.html

[Q47] 与平均值比较
来源：http://dali.ybcxt.top/Article/details/gtkdaguclj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjdywkjn.html

[Q48] CTE 公用表表达式
来源：http://dali.zhoulong.xyz/Article/details/gttjzaubne.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nwbrower.top/Article/details/gtxqgajivc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinghuilouyu.cn/Article/details/gtpiujlysj.html

[Q49] 更新单行
来源：http://dali.yuxming.cn/Article/details/gtzvjbrtyd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ybcxt.top/Article/details/gtuybdtvdu.html

[Q50] 批量更新
来源：http://dali.yvedp.cn/Article/details/gttqapmhin.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xuanzx.com/Article/details/gtcvmxluxv.html

[Q51] 用子查询更新
来源：http://dali.yvedp.cn/Article/details/gtksweedmn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhixingplan.top/Article/details/gtivamcztp.html

[Q52] 删除指定行
来源：http://dali.yvedp.cn/Article/details/gtshhajkan.html

DELETE FROM users WHERE id = 10;
来源：http://dali.meibo888.top/Article/details/gtqkttllbn.html

[Q53] 按条件删除
来源：http://dali.birdmap.top/Article/details/gtagmqwzhz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nwbrower.top/Article/details/gtpdbkjgnb.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gtwjhlqmxw.html

TRUNCATE TABLE logs;
来源：http://dali.guowangkeji.top/Article/details/gtxwvjfykx.html

[Q55] 排名（并列占位）
来源：http://dali.0kj1m.cn/Article/details/gtlsuaatun.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tianlin.xyz/Article/details/gtvkafqqmk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenjidiqi.icu/Article/details/gtdwesdfzl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sxryk.cn/Article/details/gtaujhbzzx.html

[Q57] 行号
来源：http://dali.zdqjudy.top/Article/details/gtciuprqxv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cashguo.top/Article/details/gtzscblqff.html

[Q58] 累计求和
来源：http://dali.yj20258888.top/Article/details/gtwcewjcry.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtgbugqmza.html

[Q59] 分组内累计
来源：http://dali.yuxming.cn/Article/details/gtkuvkxgon.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtodzttbdn.html

[Q60] 取上一行 / 下一行
来源：http://dali.dashuyun.cn/Article/details/gtavwudial.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenlongwang.top/Article/details/gtzertllpe.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtfsyqjifl.html

[Q61] 移动平均
来源：http://dali.shzxlz.cn/Article/details/gtrxdhltgq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sweek.top/Article/details/gtjhjsnaii.html

[Q62] 分组占比
来源：http://dali.shuidangran.top/Article/details/gtapunnxmu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gtibvwfyev.html

[Q63] 开启事务
来源：http://dali.hongshengwenyu.top/Article/details/gtfovrhrbl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.meibo888.top/Article/details/gtwugmchux.html

[Q64] 提交事务
来源：http://dali.andypj.xyz/Article/details/gteejqoyrh.html

COMMIT;
来源：http://dali.pengpengdd.cyou/Article/details/gtlxnvkqiy.html

[Q65] 回滚事务
来源：http://dali.sufxvd.cn/Article/details/gtosueytbe.html

ROLLBACK;
来源：http://dali.cheryme.top/Article/details/gtyavfnoeh.html

[Q66] 行锁查询
来源：http://dali.jianghu66.top/Article/details/gtidqjqxpa.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hammf.cn/Article/details/gtkxcpwdon.html

[Q67] 设置隔离级别
来源：http://dali.hnxiangtu.top/Article/details/gttauimtzw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.feifeiyinyue.top/Article/details/gtufmzrddk.html

[Q68] 保存点
来源：http://dali.yueranfly.top/Article/details/gtflodtjia.html

SAVEPOINT sp1;
来源：http://dali.fengsongda.top/Article/details/gtjexrcbsy.html

ROLLBACK TO sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxiofwkc.html

[Q69] 查看执行计划
来源：http://dali.tanke756.top/Article/details/gtjwoqwwrs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.wangshuangyany.cn/Article/details/gtbhgszwan.html

[Q70] 更新统计信息
来源：http://dali.yvedp.cn/Article/details/gtcixwzggp.html

ANALYZE TABLE users;
来源：http://dali.zycfv.cn/Article/details/gtkywzwqwo.html

[Q71] 查看建表语句
来源：http://dali.hongshengwenyu.top/Article/details/gtqxsqqhzh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tianlin.xyz/Article/details/gtyonztlkd.html

[Q72] 查看索引
来源：http://dali.cheryme.top/Article/details/gtbyhqsxat.html

SHOW INDEX FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtxchexurw.html

[Q73] 查看表状态
来源：http://dali.sxryk.cn/Article/details/gtbjikhbof.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gtfaypyxft.html

[Q74] 强制使用索引
来源：http://dali.pycfn.com/Article/details/gtqngzdzen.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gzhubu.top/Article/details/gtldarrswi.html

[Q75] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gtoqwkuxcp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtqmshztul.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ydzc1.top/Article/details/gtijxquued.html

[Q76] 按天统计
来源：http://dali.jyoumei.cn/Article/details/gtcceyjvok.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cheryme.top/Article/details/gtamzjhpak.html

[Q77] 时间加减
来源：http://dali.xylfe.cn/Article/details/gtpnxvfjaz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.redwolf501.top/Article/details/gthovasccf.html

[Q78] 当前时间
来源：http://dali.daxiang520.top/Article/details/gtpvvknhxl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ivvv.top/Article/details/gtwqcmemlj.html

[Q79] 字符串拼接
来源：http://dali.hnxiangtu.top/Article/details/gtogghyufd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jiagoushi.top/Article/details/gtxoclizer.html

[Q80] 字符串截取
来源：http://dali.jqgfzy.top/Article/details/gtblcgtfrh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtqytalmuv.html

[Q81] 字符串替换
来源：http://dali.sysykeji.top/Article/details/gtxjpueosz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtvzhhfpcr.html

[Q82] 字符长度与字节长度
来源：http://dali.cheryme.top/Article/details/gtrmmxygqv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gtyszqjejn.html

[Q83] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gtnfhkamfw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtrglmzrir.html

[Q84] 去除首尾空格
来源：http://dali.yuxming.cn/Article/details/gteolqwixx.html

SELECT TRIM(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtddekwruu.html

[Q85] 数值取整
来源：http://dali.yueranfly.top/Article/details/gtuwgzbdmf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ivvv.top/Article/details/gtzxiduvvm.html

[Q86] 读取 JSON 字段
来源：http://dali.snrcjt.cn/Article/details/gtftsnjrfh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yonumen.top/Article/details/gtkbujculg.html

[Q87] JSON 字段做条件
来源：http://dali.shzxlz.cn/Article/details/gtyiwkhyut.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shuidangran.top/Article/details/gtpvskornx.html

[Q88] 行转列（条件聚合）
来源：http://dali.zdqjudy.top/Article/details/gtvgvgsbvn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.dianchejie.cn/Article/details/gtduzqsmty.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtwrjuskqx.html

[Q89] 判断表是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gttsoecoai.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cucudq.cn/Article/details/gtfrdkcmnw.html

[Q90] 生成序号列
来源：http://dali.xinyue.icu/Article/details/gtwygxayud.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgytnvfn.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtbixkjbte.html

R. Bash 专题
来源：http://dali.hammf.cn/Article/details/gtstywracx.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtslxxqvsz.html

[R01] shebang 与严格模式
来源：http://dali.pycfn.com/Article/details/gtmfvbfwla.html

#!/usr/bin/env bash
来源：http://dali.snrcjt.cn/Article/details/gtvcxtntez.html

set -euo pipefail
来源：http://dali.kuanghao11.cn/Article/details/gtlvylhqgf.html

[R02] 变量赋值与使用
来源：http://dali.xuanzx.com/Article/details/gthtfqgjvt.html

name="Tom"; echo "$name"
来源：http://dali.gzhubu.top/Article/details/gtfoxvkysr.html

[R03] 只读变量
来源：http://dali.cheryme.top/Article/details/gtoravgixs.html

readonly PI=3.14
来源：http://dali.gogol.net.cn/Article/details/gtxfskewxq.html

[R04] 位置参数
来源：http://dali.c1oappe.top/Article/details/gtyowpnsnc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hywenlv.cn/Article/details/gtihdgijat.html

[R05] 参数默认值
来源：http://dali.xuetiantiany.cn/Article/details/gtajvqrkea.html

name="${1:-default}"
来源：http://dali.bjfxy.top/Article/details/gtdgvzgwat.html

[R06] 判断命令是否存在
来源：http://dali.jinqigfzy.top/Article/details/gtrttkcgpu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sysykeji.top/Article/details/gtgzyaxhfk.html

[R07] if 判断文件
来源：http://dali.nwbrower.top/Article/details/gtwfjjzvok.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.316326.xyz/Article/details/gtoenvnavv.html

[R08] 数值比较
来源：http://dali.ivvv.top/Article/details/gtclcrrcbr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxuanxn.top/Article/details/gteorpfsem.html

[R09] 字符串比较
来源：http://dali.dashuyun.cn/Article/details/gtjdovrgdz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.316326.xyz/Article/details/gtxqxrljyo.html

[R10] 正则匹配
来源：http://dali.gotoacloud.top/Article/details/gtqjuguqiu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ivvv.top/Article/details/gtlmjiruwz.html

[R11] case 多分支
来源：http://dali.c1oappe.top/Article/details/gtjrmqwilt.html

case "$1" in
来源：http://dali.aibaodan.cn/Article/details/gtpbmjyivv.html

start) echo "启动" ;;
来源：http://dali.chenzaomai.com/Article/details/gtzdjctqpf.html

stop)  echo "停止" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtvihjyagb.html

*)     echo "未知命令" ;;
来源：http://dali.c1oappe.top/Article/details/gtovxrawlk.html

esac
来源：http://dali.xinyue.icu/Article/details/gtkjzmthkf.html

[R12] for 遍历文件
来源：http://dali.xinyue.icu/Article/details/gtkdcoalfw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.redwolf501.top/Article/details/gtrcphacgz.html

[R13] for 计数循环
来源：http://dali.zdqjudy.top/Article/details/gtfoynsvdv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gtjaqmdrmj.html

[R14] C 风格 for
来源：http://dali.fzhhl.top/Article/details/gteaauhikn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gtysgbkiev.html

[R15] while 逐行读文件
来源：http://dali.yonumen.top/Article/details/gtductrcdc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gogol.net.cn/Article/details/gtqrgazhpo.html

[R16] until 等待条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwwcdsac.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gtmlnpcswm.html

[R17] 数组定义与取值
来源：http://dali.hysaishi.cn/Article/details/gtahifhzbv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258.top/Article/details/gtvghczvqt.html

[R18] 遍历数组
来源：http://dali.jyoumei.cn/Article/details/gtmkpjhtxp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aibaodan.cn/Article/details/gtbrcjyqgi.html

[R19] 数组长度
来源：http://dali.jqgfzy.top/Article/details/gtnqllguyc.html

echo "${#arr[@]}"
来源：http://dali.316326.xyz/Article/details/gtdphyoilb.html

[R20] 关联数组（字典）
来源：http://dali.tanke756.top/Article/details/gtvoqknjsh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jianghu66.top/Article/details/gtnqaybriz.html

[R21] 字符串长度
来源：http://dali.zdqjudy.top/Article/details/gthyktazrj.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gtkxezrrhi.html

[R22] 截取子串
来源：http://dali.jiagoushi.top/Article/details/gtbgwksqza.html

echo "${s:0:5}"
来源：http://dali.jqgfzy.top/Article/details/gtqebhsbes.html

[R23] 字符串替换
来源：http://dali.c1oappe.top/Article/details/gtwpiygesu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgufenzy.top/Article/details/gtcbdvican.html

[R24] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqxfeadb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.0kj1m.cn/Article/details/gtqxqsyggn.html

[R25] 去后缀 / 去前缀
来源：http://dali.9152youxi.cn/Article/details/gtiaahahvy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuetiantiany.cn/Article/details/gtlqpikmmk.html

[R26] 命令替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejzlsqjz.html

now=$(date +%F); echo "$now"
来源：http://dali.hnxiangtu.top/Article/details/gthoraitvd.html

[R27] 算术展开
来源：http://dali.gogol.net.cn/Article/details/gtfcbjrcov.html

echo $((1 + 2 * 3))
来源：http://dali.yanxiufei.cn/Article/details/gtsuocontw.html

[R28] 浮点运算
来源：http://dali.birdmap.top/Article/details/gtfdrlleew.html

echo "scale=2; 10/3" | bc
来源：http://dali.zycfv.cn/Article/details/gtdpuqojxq.html

[R29] 定义函数
来源：http://dali.yangfankeji.com/Article/details/gtdxxqvgnh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigfzy.top/Article/details/gtnpfnsbug.html

[R30] 函数返回状态码
来源：http://dali.hnxiangtu.top/Article/details/gtpvzeqdyt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tianlin.xyz/Article/details/gthluyjpai.html

[R31] 局部变量
来源：http://dali.wangdashe.top/Article/details/gtryoucbzp.html

f() { local x=1; echo "$x"; }
来源：http://dali.andypj.xyz/Article/details/gtkfxmdeoy.html

[R32] 参数个数校验
来源：http://dali.shangyingyoupin.top/Article/details/gtfcnwzpqk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjeqdtwwg.html

[R33] 捕获错误并提示行号
来源：http://dali.zhixingplan.top/Article/details/gtmoohyqqf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fengsongda.top/Article/details/gtudbxzwym.html

[R34] 退出时清理
来源：http://dali.yangfankeji.com/Article/details/gtnldbzhyb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cashguo.top/Article/details/gtxvzujodl.html

[R35] 后台执行并等待
来源：http://dali.pycfn.com/Article/details/gtowjaqxpq.html


<!-- 参考信息 -->