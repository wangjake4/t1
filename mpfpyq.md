代发 wailian999

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hysaishi.cn/Article/details/gt2mwnblghz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hysaishi.cn/Article/details/gt2lkyfpsfs.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ruojqkwj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yongpay.top/Article/details/gt2gyhneowv.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2qvmkpyzk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pengpengdd.cyou/Article/details/gt2vgkxrrmj.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2cvxxpchl.html

[Q01] 创建表
来源：http://dali.xuanzx.com/Article/details/gt2gridvxbx.html

CREATE TABLE users (
来源：http://dali.ivvv.top/Article/details/gt2sksbhikq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.mhx1999.top/Article/details/gt2ncushfzz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ehwqpu.com/Article/details/gt2tfnmfmrs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hongshengwenyu.top/Article/details/gt2gtevbjlq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pycfn.com/Article/details/gt2cbhcjnbz.html

);
来源：http://dali.daxiang520.top/Article/details/gt2koxvzzmw.html

[Q02] 创建带外键的表
来源：http://dali.hysaishi.cn/Article/details/gt2qtzdckoe.html

CREATE TABLE orders (
来源：http://dali.ppjwa.cn/Article/details/gt2smelmnfl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxinkj.top/Article/details/gt2xfmylqze.html

user_id INT NOT NULL,
来源：http://dali.ppjwa.cn/Article/details/gt2lcjjqxwq.html

amount DECIMAL(10, 2),
来源：http://dali.wangdashe.top/Article/details/gt2krqclnnz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ehwqpu.com/Article/details/gt2iftgosea.html

);
来源：http://dali.aizwys.cn/Article/details/gt2mbisgmxa.html

[Q03] 增加列
来源：http://dali.dianchejie.cn/Article/details/gt2tclupnco.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nwbrower.top/Article/details/gt2iiqdzxju.html

[Q04] 修改列类型
来源：http://dali.gogol.net.cn/Article/details/gt2vmtpkjyb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sxryk.cn/Article/details/gt2upcdxbve.html

[Q05] 重命名列
来源：http://dali.yuanzhike.top/Article/details/gt2rkmehmfi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ehwqpu.com/Article/details/gt2vkxtzsgk.html

[Q06] 删除列
来源：http://dali.pycfn.com/Article/details/gt2lcllqmdu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yvedp.cn/Article/details/gt2nawbqaye.html

[Q07] 删除表
来源：http://dali.cucudq.cn/Article/details/gt2sshtieov.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daxiang520.top/Article/details/gt2axzlsvaq.html

[Q08] 创建普通索引
来源：http://dali.9152youxi.cn/Article/details/gt2rknkptna.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2efpluleo.html

[Q09] 创建唯一索引
来源：http://dali.xinyue.icu/Article/details/gt2zeoqbqfn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sysykeji.top/Article/details/gt2fjhueiqz.html

[Q10] 插入单行
来源：http://dali.smart0.xyz/Article/details/gt2aepkmyit.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.daxiang520.top/Article/details/gt2zdcpdzfa.html

[Q11] 一次插入多行
来源：http://dali.nanxuanxn.top/Article/details/gt2zfrdvvxb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jiagoushi.top/Article/details/gt2gtsazxwv.html

[Q12] 插入后取自增 ID
来源：http://dali.svipenyu.cn/Article/details/gt2sguhmsxu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xuanzx.com/Article/details/gt2vrwrvkzv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xziqi.cn/Article/details/gt2bubizjju.html

[Q13] 忽略重复插入
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ukhcflkb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.c1oappe.top/Article/details/gt2ktkpgykl.html

[Q14] 存在则更新（upsert）
来源：http://dali.jqgfzy.top/Article/details/gt2iuznowgk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhongyouzk.top/Article/details/gt2qgkdramm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2iegrszqq.html

[Q15] 查询全部
来源：http://dali.gaohongyu789.top/Article/details/gt2vgccwdnm.html

SELECT * FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2dxlbgsjm.html

[Q16] 查询指定列
来源：http://dali.ppjwa.cn/Article/details/gt2vbatbhox.html

SELECT id, name FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2cwwkhmdv.html

[Q17] 条件查询
来源：http://dali.yuxming.cn/Article/details/gt2eplcdtgw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ivvv.top/Article/details/gt2qndtmwud.html

[Q18] 模糊匹配
来源：http://dali.yvedp.cn/Article/details/gt2jaexuygp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tianlin.xyz/Article/details/gt2saficrwu.html

[Q19] 范围查询
来源：http://dali.jiagoushi.top/Article/details/gt2qsuwxxck.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.fzhhl.top/Article/details/gt2fjjywkzv.html

[Q20] IN 列表
来源：http://dali.zhixingplan.top/Article/details/gt2nylbsdsp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ivvv.top/Article/details/gt2ltoyqrjk.html

[Q21] 空值判断
来源：http://dali.c1oappe.top/Article/details/gt2ybboneev.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gogol.net.cn/Article/details/gt2aliepfjm.html

[Q22] 排序
来源：http://dali.pycfn.com/Article/details/gt2tnhquypk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.316326.xyz/Article/details/gt2thmikfqd.html

[Q23] 分页
来源：http://dali.tanke756.top/Article/details/gt2fanncosj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhongyouzk.top/Article/details/gt2odejhhqd.html

[Q24] 去重
来源：http://dali.jianghu66.top/Article/details/gt2fzsafbql.html

SELECT DISTINCT city FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2qsdlzpeb.html

[Q25] 只取前 N 条
来源：http://dali.gotoacloud.top/Article/details/gt2qanxiomt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuanzhike.top/Article/details/gt2zixsmwex.html

[Q26] 计数
来源：http://dali.havefunace.top/Article/details/gt2ssqmzamq.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2mdiwyzlq.html

[Q27] 条件计数
来源：http://dali.hysaishi.cn/Article/details/gt2kqhwfrba.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2qdawhttz.html

[Q28] 求和与平均
来源：http://dali.jinqigufen.top/Article/details/gt2qwpiqcxc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gt2phxrqsjm.html

[Q29] 最大最小值
来源：http://dali.sxryk.cn/Article/details/gt2sosbgafp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2uitdmbvz.html

[Q30] 分组统计
来源：http://dali.hnxiangtu.top/Article/details/gt2swhhweyf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gt2bgyfomkn.html

[Q31] 分组后过滤
来源：http://dali.aizwys.cn/Article/details/gt2ajhuwkid.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sysykeji.top/Article/details/gt2fxwcuiud.html

[Q32] 分组拼接字符串
来源：http://dali.meibo888.top/Article/details/gt2rslbplsc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gt2deaugsad.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shzxlz.cn/Article/details/gt2ajcivmeb.html

[Q33] 多列分组
来源：http://dali.nwbrower.top/Article/details/gt2nfueqyym.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.daria6918.cn/Article/details/gt2xhjtpqxb.html

[Q34] 每组取第一条
来源：http://dali.aizwys.cn/Article/details/gt2bhcjotwv.html

SELECT * FROM (
来源：http://dali.yonumen.top/Article/details/gt2qguspzzg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yonumen.top/Article/details/gt2eooeewkr.html

) t WHERE rn = 1;
来源：http://dali.jianghu66.top/Article/details/gt2qibmjdnl.html

[Q35] 内连接
来源：http://dali.zhiwuduotai.top/Article/details/gt2vudgtjjx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gt2flmgcddn.html

[Q36] 左连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lyvcyyik.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ehwqpu.com/Article/details/gt2uckbamiy.html

[Q37] 右连接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gyxxmhgi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gzhubu.top/Article/details/gt2xhddruzg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.daria6918.cn/Article/details/gt2uxwhpcjc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xziqi.cn/Article/details/gt2gxyjyfog.html

[Q39] 自连接（查上下级）
来源：http://dali.jinqigfzy.top/Article/details/gt2cxrroaaq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.mhx1999.top/Article/details/gt2kulhzorb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.dianchejie.cn/Article/details/gt2eskgfcxi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenlongwang.top/Article/details/gt2iffblzsh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gogol.net.cn/Article/details/gt2wwlyyqir.html

[Q41] 多表连接
来源：http://dali.shzxlz.cn/Article/details/gt2lnjzmthd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.dianchejie.cn/Article/details/gt2osixawxm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hongshengwenyu.top/Article/details/gt2lycuxriq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yanxiufei.cn/Article/details/gt2gkzuckrt.html

[Q42] 连接条件附加过滤
来源：http://dali.xziqi.cn/Article/details/gt2cqnedhfx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.svipenyu.cn/Article/details/gt2wztxbxkn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tianlin.xyz/Article/details/gt2cjdtiovs.html

[Q43] 标量子查询
来源：http://dali.hysaishi.cn/Article/details/gt2ybqirqpl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ehwqpu.com/Article/details/gt2yvpsamzc.html

[Q44] IN 子查询
来源：http://dali.jiagoushi.top/Article/details/gt2uoinpvlv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.smart0.xyz/Article/details/gt2kmpisksk.html

[Q45] EXISTS 判断存在
来源：http://dali.sweek.top/Article/details/gt2avkqzler.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gt2ujhikhsc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.guowangkeji.top/Article/details/gt2vylbclob.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.svipenyu.cn/Article/details/gt2asrcyzxz.html

[Q47] 与平均值比较
来源：http://dali.yj20258888.top/Article/details/gt2rambvkzg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qwbdxufz.html

[Q48] CTE 公用表表达式
来源：http://dali.sysykeji.top/Article/details/gt2cqhvislu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigfzy.top/Article/details/gt2rpresspd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gotoacloud.top/Article/details/gt2gwuhzghl.html

[Q49] 更新单行
来源：http://dali.wangshuangyany.cn/Article/details/gt2ryraddaf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gt2mdeohegv.html

[Q50] 批量更新
来源：http://dali.jyoumei.cn/Article/details/gt2hfseavlo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jiagoushi.top/Article/details/gt2blhecgzg.html

[Q51] 用子查询更新
来源：http://dali.guannengcc.top/Article/details/gt2scsjhpii.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.dashuyun.cn/Article/details/gt2xrbrdrfv.html

[Q52] 删除指定行
来源：http://dali.cucudq.cn/Article/details/gt2alasymfa.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gt2hobvpqxt.html

[Q53] 按条件删除
来源：http://dali.yuxming.cn/Article/details/gt2xxafdnwk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jyoumei.cn/Article/details/gt2tptyxkky.html

[Q54] 清空表
来源：http://dali.shzxlz.cn/Article/details/gt2vfgdpbuq.html

TRUNCATE TABLE logs;
来源：http://dali.yanxiufei.cn/Article/details/gt2eygjcuxo.html

[Q55] 排名（并列占位）
来源：http://dali.smart0.xyz/Article/details/gt2jgpzkiiu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nwbrower.top/Article/details/gt2poggfwxg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.9152youxi.cn/Article/details/gt2kcgdtiow.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gt2zcycenve.html

[Q57] 行号
来源：http://dali.tanke756.top/Article/details/gt2assxhjvk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2bpvbmdnr.html

[Q58] 累计求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zxvphodo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yvedp.cn/Article/details/gt2ipuytguf.html

[Q59] 分组内累计
来源：http://dali.haohaochexian.top/Article/details/gt2wzwihxfw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gt2vhsnobqh.html

[Q60] 取上一行 / 下一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zjwxkpyl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.vqdsnc.cn/Article/details/gt2kifsjcvu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2culaaiqh.html

[Q61] 移动平均
来源：http://dali.ydzc1.top/Article/details/gt2gepmowgf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2fbjpmuht.html

[Q62] 分组占比
来源：http://dali.meibo888.top/Article/details/gt2xridlrbm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gt2rjqkjfwi.html

[Q63] 开启事务
来源：http://dali.haohaochexian.top/Article/details/gt2dtjmcikr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenlongwang.top/Article/details/gt2gjzxngdk.html

[Q64] 提交事务
来源：http://dali.yongpay.top/Article/details/gt2cnorswpz.html

COMMIT;
来源：http://dali.zhoulong.xyz/Article/details/gt2ncnfpitw.html

[Q65] 回滚事务
来源：http://dali.haohaochexian.top/Article/details/gt2nnfdsfgj.html

ROLLBACK;
来源：http://dali.wangdashe.top/Article/details/gt2grilflwu.html

[Q66] 行锁查询
来源：http://dali.birdmap.top/Article/details/gt2lruxltul.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuetiantiany.cn/Article/details/gt2rvfzzznw.html

[Q67] 设置隔离级别
来源：http://dali.feifeiyinyue.top/Article/details/gt2pleoroen.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ivvv.top/Article/details/gt2kntjaioa.html

[Q68] 保存点
来源：http://dali.daxiang520.top/Article/details/gt2jnwvtnme.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ukelrtrv.html

ROLLBACK TO sp1;
来源：http://dali.316326.xyz/Article/details/gt2bsdquipw.html

[Q69] 查看执行计划
来源：http://dali.ehwqpu.com/Article/details/gt2cvmznlce.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shuidangran.top/Article/details/gt2eccnlrwh.html

[Q70] 更新统计信息
来源：http://dali.daxiang520.top/Article/details/gt2oobsgkrt.html

ANALYZE TABLE users;
来源：http://dali.quarkkingdee.top/Article/details/gt2vfwyeqbv.html

[Q71] 查看建表语句
来源：http://dali.hongshengwenyu.top/Article/details/gt2ammzfrkh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ccufyjvr.html

[Q72] 查看索引
来源：http://dali.jlsjyb.cn/Article/details/gt2wnndcxav.html

SHOW INDEX FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2ljrzmmsp.html

[Q73] 查看表状态
来源：http://dali.hywenlv.cn/Article/details/gt2kkgcqgrd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zycfv.cn/Article/details/gt2aqyvgirv.html

[Q74] 强制使用索引
来源：http://dali.gotoacloud.top/Article/details/gt2omyvpend.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gzhubu.top/Article/details/gt2leotrbtq.html

[Q75] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gt2ykhkipvx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2qlgveodn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.c1oappe.top/Article/details/gt2mdhhgguj.html

[Q76] 按天统计
来源：http://dali.yuanzhike.top/Article/details/gt2hblzjfvi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tian-w.cn/Article/details/gt2pxsmpnhv.html

[Q77] 时间加减
来源：http://dali.sufxvd.cn/Article/details/gt2yinzvbjq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.aizwys.cn/Article/details/gt2turgqtpx.html

[Q78] 当前时间
来源：http://dali.cashguo.top/Article/details/gt2rpmyisgr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuetiantiany.cn/Article/details/gt2pggmurab.html

[Q79] 字符串拼接
来源：http://dali.gotoacloud.top/Article/details/gt2iaghkyfs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgfzy.top/Article/details/gt2woxojlyq.html

[Q80] 字符串截取
来源：http://dali.xuetiantiany.cn/Article/details/gt2lynrayrq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2hhqvooea.html

[Q81] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gt2moxekiqz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2tiwxdxsp.html

[Q82] 字符长度与字节长度
来源：http://dali.aizwys.cn/Article/details/gt2ihwmvnye.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2awqrkgap.html

[Q83] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gt2ptznihlu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2qgswiqzi.html

[Q84] 去除首尾空格
来源：http://dali.yongpay.top/Article/details/gt2jpiocoqs.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2apyjrkfy.html

[Q85] 数值取整
来源：http://dali.jiagoushi.top/Article/details/gt2nertnxpg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.mhx1999.top/Article/details/gt2kisjkozd.html

[Q86] 读取 JSON 字段
来源：http://dali.jiagoushi.top/Article/details/gt2qjpsnlju.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenzaomai.com/Article/details/gt2soizmeqn.html

[Q87] JSON 字段做条件
来源：http://dali.hongshengwenyu.top/Article/details/gt2pcsorfbc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2apbcnixv.html

[Q88] 行转列（条件聚合）
来源：http://dali.0kj1m.cn/Article/details/gt2uwysidgg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cashguo.top/Article/details/gt2cqdskccd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2ierfgqtz.html

[Q89] 判断表是否存在
来源：http://dali.sysykeji.top/Article/details/gt2rjqjgcoh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yuxming.cn/Article/details/gt2oayfwuxc.html

[Q90] 生成序号列
来源：http://dali.yj202588.top/Article/details/gt2lapnypji.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.pengpengdd.cyou/Article/details/gt2wgknsgkg.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2xeubwyst.html

R. Bash 专题
来源：http://dali.sweek.top/Article/details/gt2jntynodu.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2ydmqdyvc.html

[R01] shebang 与严格模式
来源：http://dali.dianchejie.cn/Article/details/gt2onigsfpo.html

#!/usr/bin/env bash
来源：http://dali.9152youxi.cn/Article/details/gt2nyzxuroe.html

set -euo pipefail
来源：http://dali.yvedp.cn/Article/details/gt2cjoonprg.html

[R02] 变量赋值与使用
来源：http://dali.jianghu66.top/Article/details/gt2zxjjausw.html

name="Tom"; echo "$name"
来源：http://dali.ybcxt.top/Article/details/gt2qwglvgrv.html

[R03] 只读变量
来源：http://dali.hnxiangtu.top/Article/details/gt2zrgzrsxa.html

readonly PI=3.14
来源：http://dali.hammf.cn/Article/details/gt2apufxlzl.html

[R04] 位置参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2qflmrnqq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgfzy.top/Article/details/gt2tcmrwkft.html

[R05] 参数默认值
来源：http://dali.feifeiyinyue.top/Article/details/gt2skntkdtg.html

name="${1:-default}"
来源：http://dali.haohaochexian.top/Article/details/gt2uuarlkxo.html

[R06] 判断命令是否存在
来源：http://dali.gaohongyu789.top/Article/details/gt2myrlnbmq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gt2zkxuuoen.html

[R07] if 判断文件
来源：http://dali.ybcxt.top/Article/details/gt2zujlymeh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ppjwa.cn/Article/details/gt2txkxleys.html

[R08] 数值比较
来源：http://dali.nanxuanxn.top/Article/details/gt2tqoteszl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.9152youxi.cn/Article/details/gt2usoxmptf.html

[R09] 字符串比较
来源：http://dali.ehwqpu.com/Article/details/gt2togvprni.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.meibo888.top/Article/details/gt2iyoquyia.html

[R10] 正则匹配
来源：http://dali.cheryme.top/Article/details/gt2kpuzejob.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sweek.top/Article/details/gt2lggyiywe.html

[R11] case 多分支
来源：http://dali.cashguo.top/Article/details/gt2nxqtgchl.html

case "$1" in
来源：http://dali.kuanghao11.cn/Article/details/gt2zonvwopo.html

start) echo "启动" ;;
来源：http://dali.jinqigfzy.top/Article/details/gt2sjjkmrtq.html

stop)  echo "停止" ;;
来源：http://dali.ybcxt.top/Article/details/gt2pjdicxkx.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2suzvcpaa.html

esac
来源：http://dali.xylfe.cn/Article/details/gt2cwtetouy.html

[R12] for 遍历文件
来源：http://dali.xziqi.cn/Article/details/gt2cljkzvhr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cucudq.cn/Article/details/gt2zusdapol.html

[R13] for 计数循环
来源：http://dali.zhengqikj.top/Article/details/gt2beqqlcyz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gt2koyxukey.html

[R14] C 风格 for
来源：http://dali.snrcjt.cn/Article/details/gt2dvgpeemu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.haohaochexian.top/Article/details/gt2jppktcsf.html

[R15] while 逐行读文件
来源：http://dali.ybcxt.top/Article/details/gt2niexumsd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2spovqrvd.html

[R16] until 等待条件
来源：http://dali.cqqwz.cn/Article/details/gt2omdleplb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuxming.cn/Article/details/gt2ypnyiffe.html

[R17] 数组定义与取值
来源：http://dali.cashguo.top/Article/details/gt2dwpmfipq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sufxvd.cn/Article/details/gt2dqezouni.html

[R18] 遍历数组
来源：http://dali.ehwqpu.com/Article/details/gt2rzrqozor.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ydzc1.top/Article/details/gt2pkivucdr.html

[R19] 数组长度
来源：http://dali.yuxming.cn/Article/details/gt2hsoybjug.html

echo "${#arr[@]}"
来源：http://dali.svipenyu.cn/Article/details/gt2hpsptgps.html

[R20] 关联数组（字典）
来源：http://dali.shangyingyoupin.top/Article/details/gt2wdurdgdt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigfzy.top/Article/details/gt2ywoeefhr.html

[R21] 字符串长度
来源：http://dali.xuanzx.com/Article/details/gt2wbwdnohl.html

echo "${#s}"
来源：http://dali.zdqjudy.top/Article/details/gt2fphhcepq.html

[R22] 截取子串
来源：http://dali.hnqzz.top/Article/details/gt2edcpatft.html

echo "${s:0:5}"
来源：http://dali.guannengcc.top/Article/details/gt2wdgdyrzn.html

[R23] 字符串替换
来源：http://dali.jqgfzy.top/Article/details/gt2ttoixstb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cashguo.top/Article/details/gt2ixtgxluz.html

[R24] 大小写转换
来源：http://dali.snrcjt.cn/Article/details/gt2mdyatpbu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sweek.top/Article/details/gt2tjocwqna.html

[R25] 去后缀 / 去前缀
来源：http://dali.shangyingyoupin.top/Article/details/gt2ylcbmluk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sxryk.cn/Article/details/gt2unjscznj.html

[R26] 命令替换
来源：http://dali.xuanzx.com/Article/details/gt2fmmmxwav.html

now=$(date +%F); echo "$now"
来源：http://dali.dashuyun.cn/Article/details/gt2hfebrrdv.html

[R27] 算术展开
来源：http://dali.dashuyun.cn/Article/details/gt2vzvwsxkn.html

echo $((1 + 2 * 3))
来源：http://dali.zhiwuduotai.top/Article/details/gt2uifcryoi.html

[R28] 浮点运算
来源：http://dali.wangdashe.top/Article/details/gt2acixdtsn.html

echo "scale=2; 10/3" | bc
来源：http://dali.tian-w.cn/Article/details/gt2wgdgtdno.html

[R29] 定义函数
来源：http://dali.ehwqpu.com/Article/details/gt2kgodngzy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnqzz.top/Article/details/gt2jgycaqzm.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mkeswqcg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hammf.cn/Article/details/gt2uccokqtl.html

[R31] 局部变量
来源：http://dali.daxiang520.top/Article/details/gt2unzmkads.html

f() { local x=1; echo "$x"; }
来源：http://dali.sxryk.cn/Article/details/gt2cotrnuaj.html

[R32] 参数个数校验
来源：http://dali.quarkkingdee.top/Article/details/gt2munggwjs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xptmqtfg.html

[R33] 捕获错误并提示行号
来源：http://dali.hongshengwenyu.top/Article/details/gt2yoirxwla.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gzhubu.top/Article/details/gt2oskkryld.html

[R34] 退出时清理
来源：http://dali.yanxiufei.cn/Article/details/gt2wafvvuel.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sfhrdqsn.html

[R35] 后台执行并等待
来源：http://dali.yuxming.cn/Article/details/gt2goxbsrpb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhongyouzk.top/Article/details/gt2lhodsxtg.html

[R36] 并发执行多个任务
来源：http://dali.svipenyu.cn/Article/details/gt2bsuopaqb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhoulong.xyz/Article/details/gt2egabyaon.html

[R37] 把输出赋给变量
来源：http://dali.xylfe.cn/Article/details/gt2daqfvpgu.html

files=$(ls -1)
来源：http://dali.hysaishi.cn/Article/details/gt2wghmkbxe.html

[R38] 管道串联
来源：http://dali.316326.xyz/Article/details/gt2tbxgvbun.html

cat a.txt | grep -i error | wc -l
来源：http://dali.pengpengdd.cyou/Article/details/gt2cafzabez.html

[R39] 重定向标准输出与错误
来源：http://dali.pycfn.com/Article/details/gt2mmqkytrj.html

cmd > out.log 2>&1
来源：http://dali.xuetiantiany.cn/Article/details/gt2dyfyauuh.html

[R40] 追加写日志
来源：http://dali.hammf.cn/Article/details/gt2aisyrkqi.html

echo "log" >> out.log
来源：http://dali.yvedp.cn/Article/details/gt2oapmooyc.html

[R41] 丢弃输出
来源：http://dali.havefunace.top/Article/details/gt2bqshxnsf.html


<!-- 参考信息 -->