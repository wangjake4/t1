代发 wailian999

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.haohaochexian.top/Article/details/gtoikrdcie.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.quarkkingdee.top/Article/details/gtllcwhzdv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenzaomai.com/Article/details/gtcwftmbeb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gttcykkrhz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.svipenyu.cn/Article/details/gtdlnfsgyp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zycfv.cn/Article/details/gtnlgdyosq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ivvv.top/Article/details/gtqwmcqwak.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenlongwang.top/Article/details/gtaaxlexmq.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtmrxrplhh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenjidiqi.icu/Article/details/gtqzgcuhzu.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtcftruvyk.html

[Q01] 创建表
来源：http://dali.shuidangran.top/Article/details/gteecvpdvi.html

CREATE TABLE users (
来源：http://dali.aizwys.cn/Article/details/gtxkyoujhf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gtvugpixvq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gtsuslzvaj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.9152youxi.cn/Article/details/gthubehful.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nanxuanxn.top/Article/details/gtohjbffqt.html

);
来源：http://dali.sweek.top/Article/details/gtcspsqmzp.html

[Q02] 创建带外键的表
来源：http://dali.hfpthk.cn/Article/details/gtoguytkbu.html

CREATE TABLE orders (
来源：http://dali.ppjwa.cn/Article/details/gtjywocbvx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sxryk.cn/Article/details/gtccivlcot.html

user_id INT NOT NULL,
来源：http://dali.jinqigufen.top/Article/details/gttwpyrrbc.html

amount DECIMAL(10, 2),
来源：http://dali.sufxvd.cn/Article/details/gtxxerwfqa.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tianlin.xyz/Article/details/gtecsxnpkp.html

);
来源：http://dali.jinqigufen.top/Article/details/gtejzbnshe.html

[Q03] 增加列
来源：http://dali.nwbrower.top/Article/details/gtzbgcrxyg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.wangdashe.top/Article/details/gtaqiaogcc.html

[Q04] 修改列类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjzsvyzdn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.iojbl.cn/Article/details/gtxabvjqxt.html

[Q05] 重命名列
来源：http://dali.yongpay.top/Article/details/gthslmdotj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zdqjudy.top/Article/details/gtvcolpvre.html

[Q06] 删除列
来源：http://dali.yongpay.top/Article/details/gtfgkoleal.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yueranfly.top/Article/details/gtsqnamgsv.html

[Q07] 删除表
来源：http://dali.havefunace.top/Article/details/gtxyaqookw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.smart0.xyz/Article/details/gtqigyzvyw.html

[Q08] 创建普通索引
来源：http://dali.316326.xyz/Article/details/gtraystocj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.haohaochexian.top/Article/details/gtfxxhfmhp.html

[Q09] 创建唯一索引
来源：http://dali.chenjidiqi.icu/Article/details/gtfwungkqc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.haohaochexian.top/Article/details/gtorddfjpo.html

[Q10] 插入单行
来源：http://dali.hammf.cn/Article/details/gtekicutav.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tanke756.top/Article/details/gtxenfsuqj.html

[Q11] 一次插入多行
来源：http://dali.wangshuangyany.cn/Article/details/gtnvitahmt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yvedp.cn/Article/details/gtrmrehyle.html

[Q12] 插入后取自增 ID
来源：http://dali.jqgfzy.top/Article/details/gtnuermkod.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gtvpzglwgq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jyoumei.cn/Article/details/gttqyqtauh.html

[Q13] 忽略重复插入
来源：http://dali.gotoacloud.top/Article/details/gtswsxvygt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tian-w.cn/Article/details/gtfrwjuulx.html

[Q14] 存在则更新（upsert）
来源：http://dali.yvedp.cn/Article/details/gtdkapodol.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tanke756.top/Article/details/gtyduonjyl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yueranfly.top/Article/details/gtwqelugog.html

[Q15] 查询全部
来源：http://dali.hongshengwenyu.top/Article/details/gtjmzdsisg.html

SELECT * FROM users;
来源：http://dali.yj202588.top/Article/details/gtxphwecmh.html

[Q16] 查询指定列
来源：http://dali.sysykeji.top/Article/details/gtghmzvutk.html

SELECT id, name FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtcdnjzknn.html

[Q17] 条件查询
来源：http://dali.guowangkeji.top/Article/details/gtozafduts.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.iojbl.cn/Article/details/gtkldzvmtd.html

[Q18] 模糊匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtkaxonotp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shangyingyoupin.top/Article/details/gtufypctxe.html

[Q19] 范围查询
来源：http://dali.ydzc1.top/Article/details/gtzlpsjceg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hysaishi.cn/Article/details/gtlakrwskp.html

[Q20] IN 列表
来源：http://dali.gogol.net.cn/Article/details/gtnwswdkyi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.pycfn.com/Article/details/gtoylcgtsk.html

[Q21] 空值判断
来源：http://dali.ybcxt.top/Article/details/gthfwcwyll.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.haohaochexian.top/Article/details/gtvumfvdea.html

[Q22] 排序
来源：http://dali.hongshengwenyu.top/Article/details/gtwsrrjtfd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.dashuyun.cn/Article/details/gtojlkjwhe.html

[Q23] 分页
来源：http://dali.tianlin.xyz/Article/details/gtbigntgur.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xuanzx.com/Article/details/gtfujmtajz.html

[Q24] 去重
来源：http://dali.fengsongda.top/Article/details/gtlvxajxyf.html

SELECT DISTINCT city FROM users;
来源：http://dali.cashguo.top/Article/details/gtaiqznqvx.html

[Q25] 只取前 N 条
来源：http://dali.chenlongwang.top/Article/details/gttcawyior.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cucudq.cn/Article/details/gthktuhnqb.html

[Q26] 计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtceijevof.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtoybhmypq.html

[Q27] 条件计数
来源：http://dali.iojbl.cn/Article/details/gtqiinvxts.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtsvldsmjm.html

[Q28] 求和与平均
来源：http://dali.ivvv.top/Article/details/gtvlhtjgvx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtkdhaubue.html

[Q29] 最大最小值
来源：http://dali.yangfankeji.com/Article/details/gtkbxayoxf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtuelvmkwz.html

[Q30] 分组统计
来源：http://dali.mhx1999.top/Article/details/gtpqqhkwxp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtymawozpx.html

[Q31] 分组后过滤
来源：http://dali.haohaochexian.top/Article/details/gteqbtwnai.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ivvv.top/Article/details/gtlatlakbp.html

[Q32] 分组拼接字符串
来源：http://dali.redwolf501.top/Article/details/gtqvhujmdh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gtstkzphpr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nanxinkj.top/Article/details/gturzeiozc.html

[Q33] 多列分组
来源：http://dali.nwbrower.top/Article/details/gtytiesphy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sxryk.cn/Article/details/gtcikrxlcf.html

[Q34] 每组取第一条
来源：http://dali.tian-w.cn/Article/details/gtyihnhydu.html

SELECT * FROM (
来源：http://dali.snrcjt.cn/Article/details/gtwfbnfqki.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hysaishi.cn/Article/details/gtdmyenhaq.html

) t WHERE rn = 1;
来源：http://dali.gotoacloud.top/Article/details/gtvwjqsmsq.html

[Q35] 内连接
来源：http://dali.mhx1999.top/Article/details/gtelnpuluj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.meibo888.top/Article/details/gtfdrenfdm.html

[Q36] 左连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgidesswp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tanke756.top/Article/details/gtijjmbrom.html

[Q37] 右连接
来源：http://dali.gotoacloud.top/Article/details/gtcjrrkqcg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gotoacloud.top/Article/details/gtkrxiuakh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.quarkkingdee.top/Article/details/gtnudscccm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgfzy.top/Article/details/gtupzkurfx.html

[Q39] 自连接（查上下级）
来源：http://dali.hywenlv.cn/Article/details/gtwitbehat.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yonumen.top/Article/details/gteegrbqgo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cucudq.cn/Article/details/gtmjygxlra.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shzxlz.cn/Article/details/gthzlfsuuu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hnxiangtu.top/Article/details/gtodfljdji.html

[Q41] 多表连接
来源：http://dali.jyoumei.cn/Article/details/gtqfulqzzs.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cdnleiting.top/Article/details/gtmbtesijg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangtech.top/Article/details/gtzevkzsvz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhoulong.xyz/Article/details/gtlwtxalwf.html

[Q42] 连接条件附加过滤
来源：http://dali.tianlin.xyz/Article/details/gtlddxnwcw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuetiantiany.cn/Article/details/gtgmypzgrm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hfpthk.cn/Article/details/gtujrazpti.html

[Q43] 标量子查询
来源：http://dali.yanxiufei.cn/Article/details/gthmopzgwl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yueranfly.top/Article/details/gtnofikfok.html

[Q44] IN 子查询
来源：http://dali.yangfankeji.com/Article/details/gtioygrlln.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.guannengcc.top/Article/details/gtsrnvtbie.html

[Q45] EXISTS 判断存在
来源：http://dali.jlsjyb.cn/Article/details/gtowuxwsna.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ydzc1.top/Article/details/gtencueete.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.mhx1999.top/Article/details/gttvnjprgj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gtdvtitckb.html

[Q47] 与平均值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvyxzowgd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guowangkeji.top/Article/details/gtzrtncezr.html

[Q48] CTE 公用表表达式
来源：http://dali.shzxlz.cn/Article/details/gtbqwvmhnk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigfzy.top/Article/details/gtpphvqmvc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.svipenyu.cn/Article/details/gthicmmude.html

[Q49] 更新单行
来源：http://dali.bjfxy.top/Article/details/gtjwgidmqm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxinkj.top/Article/details/gtplizlzhq.html

[Q50] 批量更新
来源：http://dali.zhengqikj.top/Article/details/gtqbtquimc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yvedp.cn/Article/details/gtocmuhqnp.html

[Q51] 用子查询更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykwbcqmh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cdnleiting.top/Article/details/gtxpogrcdc.html

[Q52] 删除指定行
来源：http://dali.zhongyouzk.top/Article/details/gtvvwbxeoo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gtcmeormdd.html

[Q53] 按条件删除
来源：http://dali.gaohongyu789.top/Article/details/gtesaemwxn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258.top/Article/details/gtvtrdiyqp.html

[Q54] 清空表
来源：http://dali.yangfankeji.com/Article/details/gtajevqxac.html

TRUNCATE TABLE logs;
来源：http://dali.ybcxt.top/Article/details/gtvrvqfeva.html

[Q55] 排名（并列占位）
来源：http://dali.nanxinkj.top/Article/details/gtmksidobo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ydzc1.top/Article/details/gtiwmsburg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nanxuanxn.top/Article/details/gtvbhbvqai.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.daria6918.cn/Article/details/gtdwhujqbw.html

[Q57] 行号
来源：http://dali.zhengqikj.top/Article/details/gtmbglomlf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtzafdiiad.html

[Q58] 累计求和
来源：http://dali.hysaishi.cn/Article/details/gthuruxnzf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtydwfheqa.html

[Q59] 分组内累计
来源：http://dali.guannengcc.top/Article/details/gtnimapiih.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtntyfeiqx.html

[Q60] 取上一行 / 下一行
来源：http://dali.yuanzhike.top/Article/details/gtobcwtkqe.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.snrcjt.cn/Article/details/gtwxwmfopg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtbinlllaa.html

[Q61] 移动平均
来源：http://dali.gotoacloud.top/Article/details/gtgmpitkkl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtchivlgit.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gtymzchrzb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gtayodkqli.html

[Q63] 开启事务
来源：http://dali.cheryme.top/Article/details/gtvbvlvnmp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ybcxt.top/Article/details/gtpgtwtarl.html

[Q64] 提交事务
来源：http://dali.yj20258.top/Article/details/gtvfqbqfhi.html

COMMIT;
来源：http://dali.wangshuangyany.cn/Article/details/gtqxmlagip.html

[Q65] 回滚事务
来源：http://dali.zdqjudy.top/Article/details/gtpownofak.html

ROLLBACK;
来源：http://dali.jianghu66.top/Article/details/gtrgxksrgc.html

[Q66] 行锁查询
来源：http://dali.316326.xyz/Article/details/gtmkdvwjbu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xziqi.cn/Article/details/gtztgqftuj.html

[Q67] 设置隔离级别
来源：http://dali.jinghuilouyu.cn/Article/details/gttedlnlzj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspuilhug.html

[Q68] 保存点
来源：http://dali.pycfn.com/Article/details/gtzkqdjxgb.html

SAVEPOINT sp1;
来源：http://dali.svipenyu.cn/Article/details/gtqdwqzrle.html

ROLLBACK TO sp1;
来源：http://dali.ehwqpu.com/Article/details/gtjxpjjzwe.html

[Q69] 查看执行计划
来源：http://dali.xuetiantiany.cn/Article/details/gtcaourbmy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gotoacloud.top/Article/details/gtwxmlgbkg.html

[Q70] 更新统计信息
来源：http://dali.ppjwa.cn/Article/details/gtegorajyd.html

ANALYZE TABLE users;
来源：http://dali.jqgfzy.top/Article/details/gtarpibmub.html

[Q71] 查看建表语句
来源：http://dali.yanxiufei.cn/Article/details/gtylnkrihw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yuxming.cn/Article/details/gtxcjewlwj.html

[Q72] 查看索引
来源：http://dali.hammf.cn/Article/details/gtvqhbevoo.html

SHOW INDEX FROM users;
来源：http://dali.0kj1m.cn/Article/details/gthxtpcykv.html

[Q73] 查看表状态
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnmgywsu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.daxiang520.top/Article/details/gtkpqfqzbm.html

[Q74] 强制使用索引
来源：http://dali.9152youxi.cn/Article/details/gtvwwsgyoj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gaohongyu789.top/Article/details/gtculdgrkq.html

[Q75] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gtwmtwtnoh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtthuhtwcb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aibaodan.cn/Article/details/gtnspcziyb.html

[Q76] 按天统计
来源：http://dali.pengpengdd.cyou/Article/details/gtocxgonhp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shzxlz.cn/Article/details/gtwtzbdoos.html

[Q77] 时间加减
来源：http://dali.hammf.cn/Article/details/gthsjspjua.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cqqwz.cn/Article/details/gthcvhwapp.html

[Q78] 当前时间
来源：http://dali.iojbl.cn/Article/details/gtywszlbpg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tianlin.xyz/Article/details/gtawkrurio.html

[Q79] 字符串拼接
来源：http://dali.cdnleiting.top/Article/details/gtvgxhraap.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.guowangkeji.top/Article/details/gtydxwihgw.html

[Q80] 字符串截取
来源：http://dali.nanxuanxn.top/Article/details/gtoxingmeq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtvawoqece.html

[Q81] 字符串替换
来源：http://dali.yj202588.top/Article/details/gtedtlrxve.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtsrlibxow.html

[Q82] 字符长度与字节长度
来源：http://dali.gzhubu.top/Article/details/gtpnhgjygb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbybtkigk.html

[Q83] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gtqlgllkuj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcaewfrpn.html

[Q84] 去除首尾空格
来源：http://dali.shuidangran.top/Article/details/gtrvhbinld.html

SELECT TRIM(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtgwawdlfi.html

[Q85] 数值取整
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamzpentr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gotoacloud.top/Article/details/gthowcvsfm.html

[Q86] 读取 JSON 字段
来源：http://dali.xylfe.cn/Article/details/gtcedwiqap.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.guowangkeji.top/Article/details/gtqxpcimim.html

[Q87] JSON 字段做条件
来源：http://dali.hongshengwenyu.top/Article/details/gtwqxlesmm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daria6918.cn/Article/details/gtfdwcvjpe.html

[Q88] 行转列（条件聚合）
来源：http://dali.guannengcc.top/Article/details/gtqjwrclft.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sysykeji.top/Article/details/gtoblttyrh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtgrlgnptu.html

[Q89] 判断表是否存在
来源：http://dali.tian-w.cn/Article/details/gtlrkhtmer.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.c1oappe.top/Article/details/gtzxropyah.html

[Q90] 生成序号列
来源：http://dali.daxiang520.top/Article/details/gtzznidtbv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gzhubu.top/Article/details/gttcmgtdfn.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtlllsccrz.html

R. Bash 专题
来源：http://dali.ybcxt.top/Article/details/gtuznvkwkt.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtenegklry.html

[R01] shebang 与严格模式
来源：http://dali.c1oappe.top/Article/details/gteedsoxvo.html

#!/usr/bin/env bash
来源：http://dali.hfpthk.cn/Article/details/gthwnkupil.html

set -euo pipefail
来源：http://dali.jqgfzy.top/Article/details/gtvtxtnjap.html

[R02] 变量赋值与使用
来源：http://dali.guannengcc.top/Article/details/gtbzuysdby.html

name="Tom"; echo "$name"
来源：http://dali.dashuyun.cn/Article/details/gtkqnciwgl.html

[R03] 只读变量
来源：http://dali.316326.xyz/Article/details/gtwbapgxho.html

readonly PI=3.14
来源：http://dali.andypj.xyz/Article/details/gtrdadxqeg.html

[R04] 位置参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxswlmhm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnnhpmsif.html

[R05] 参数默认值
来源：http://dali.gotoacloud.top/Article/details/gtsmdlwhqc.html

name="${1:-default}"
来源：http://dali.xinyue.icu/Article/details/gtjotdfjdh.html

[R06] 判断命令是否存在
来源：http://dali.ydzc1.top/Article/details/gtehcclcfo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtamvjlmqi.html

[R07] if 判断文件
来源：http://dali.hfpthk.cn/Article/details/gtdlyosdan.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.aizwys.cn/Article/details/gtuzgocxft.html

[R08] 数值比较
来源：http://dali.shzxlz.cn/Article/details/gtirokyhww.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhengqikj.top/Article/details/gtiplkubap.html

[R09] 字符串比较
来源：http://dali.gzhubu.top/Article/details/gtguffuyvk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.aibaodan.cn/Article/details/gtlqobgwdh.html

[R10] 正则匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtldolvmls.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yueranfly.top/Article/details/gtsgkwmgdm.html

[R11] case 多分支
来源：http://dali.jinqigfzy.top/Article/details/gtknpemoqo.html

case "$1" in
来源：http://dali.yj20258.top/Article/details/gtdgjhyncv.html

start) echo "启动" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcktdkfma.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvqsvzgb.html

*)     echo "未知命令" ;;
来源：http://dali.jyoumei.cn/Article/details/gtrjqbfbbr.html

esac
来源：http://dali.birdmap.top/Article/details/gthzznoxkl.html

[R12] for 遍历文件
来源：http://dali.vqdsnc.cn/Article/details/gtvgnxzngf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shuidangran.top/Article/details/gteogrscap.html

[R13] for 计数循环
来源：http://dali.daxiang520.top/Article/details/gtgxtrgsjn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqlmyuaj.html

[R14] C 风格 for
来源：http://dali.zycfv.cn/Article/details/gtceoffatj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtapscvmyr.html

[R15] while 逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtyocqugnb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangdashe.top/Article/details/gtvxlfpruw.html

[R16] until 等待条件
来源：http://dali.jqgufenzy.top/Article/details/gthqmvpcja.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gtrqrlzupe.html

[R17] 数组定义与取值
来源：http://dali.bjfxy.top/Article/details/gtyywjvgkz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.birdmap.top/Article/details/gtyhpyxjls.html

[R18] 遍历数组
来源：http://dali.yanxiufei.cn/Article/details/gtdvpoyjwt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yonumen.top/Article/details/gtotstbhkv.html

[R19] 数组长度
来源：http://dali.feifeiyinyue.top/Article/details/gtbwfqhylf.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzqolcot.html

[R20] 关联数组（字典）
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrnwyxei.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shangyingyoupin.top/Article/details/gtuurrksbr.html

[R21] 字符串长度
来源：http://dali.yj20258.top/Article/details/gtuaeksryk.html

echo "${#s}"
来源：http://dali.vqdsnc.cn/Article/details/gtetftggsx.html

[R22] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gtuupvcijj.html

echo "${s:0:5}"
来源：http://dali.meibo888.top/Article/details/gtricmsctn.html

[R23] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gtmwuzulfl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuanzhike.top/Article/details/gtuzioxhxw.html

[R24] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtqkbedsxw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.haohaochexian.top/Article/details/gtevhihuot.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gtieekwqic.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jyoumei.cn/Article/details/gtxmrelric.html

[R26] 命令替换
来源：http://dali.iojbl.cn/Article/details/gtravesqrz.html

now=$(date +%F); echo "$now"
来源：http://dali.iojbl.cn/Article/details/gteoouqeox.html

[R27] 算术展开
来源：http://dali.jinqigfzy.top/Article/details/gtddilctyb.html

echo $((1 + 2 * 3))
来源：http://dali.snrcjt.cn/Article/details/gtpzczhcgp.html

[R28] 浮点运算
来源：http://dali.c1oappe.top/Article/details/gtqgeneapo.html

echo "scale=2; 10/3" | bc
来源：http://dali.cqqwz.cn/Article/details/gttuaqeexb.html

[R29] 定义函数
来源：http://dali.gaohongyu789.top/Article/details/gticiprciw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jiagoushi.top/Article/details/gtrcrugmtc.html

[R30] 函数返回状态码
来源：http://dali.jianghu66.top/Article/details/gtrmznzhpk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sufxvd.cn/Article/details/gtcfsibqmi.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gtalydwjdz.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhongyouzk.top/Article/details/gtyseagsdu.html

[R32] 参数个数校验
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidbhsdag.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinqigfzy.top/Article/details/gtmukgivso.html

[R33] 捕获错误并提示行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewcrswtk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ehwqpu.com/Article/details/gtmhnfdwoc.html

[R34] 退出时清理
来源：http://dali.wangshuangyany.cn/Article/details/gtjnnwlnkj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gtppvtfhcp.html

[R35] 后台执行并等待
来源：http://dali.316326.xyz/Article/details/gtroshyxzx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.redwolf501.top/Article/details/gtnpxzbmub.html

[R36] 并发执行多个任务
来源：http://dali.tian-w.cn/Article/details/gtfkwwwjvs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tanke756.top/Article/details/gtfeedvwvh.html

[R37] 把输出赋给变量
来源：http://dali.chenzaomai.com/Article/details/gtxblpejnc.html

files=$(ls -1)
来源：http://dali.jiagoushi.top/Article/details/gtkbpvijfk.html

[R38] 管道串联
来源：http://dali.tianlin.xyz/Article/details/gtxgwlmqbu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hongshengwenyu.top/Article/details/gtoksdipkk.html

[R39] 重定向标准输出与错误
来源：http://dali.cashguo.top/Article/details/gtcczbhuwn.html


<!-- 参考信息 -->