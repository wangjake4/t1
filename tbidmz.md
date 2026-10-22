代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zdqjudy.top/Article/details/gt2qgvzjchf.html

);
来源：http://dali.dashuyun.cn/Article/details/gt2rqlttdmr.html

[Q02] 创建带外键的表
来源：http://dali.9152youxi.cn/Article/details/gt2hxwrcoru.html

CREATE TABLE orders (
来源：http://dali.shuidangran.top/Article/details/gt2fwdyocuu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hysaishi.cn/Article/details/gt2lusdowey.html

user_id INT NOT NULL,
来源：http://dali.jqgufenzy.top/Article/details/gt2glthyrez.html

amount DECIMAL(10, 2),
来源：http://dali.shzxlz.cn/Article/details/gt2mboicknm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eqwjpsen.html

);
来源：http://dali.daria6918.cn/Article/details/gt2ocbwbsam.html

[Q03] 增加列
来源：http://dali.zhengqikj.top/Article/details/gt2dfpjcqsx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jqgufenzy.top/Article/details/gt2fnkegrgg.html

[Q04] 修改列类型
来源：http://dali.yuanzhike.top/Article/details/gt2yolsiqmf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.vqdsnc.cn/Article/details/gt2ojlkshzo.html

[Q05] 重命名列
来源：http://dali.tanke756.top/Article/details/gt2dfvzmoil.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhixingplan.top/Article/details/gt2enuqwewx.html

[Q06] 删除列
来源：http://dali.quarkkingdee.top/Article/details/gt2malaruap.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.iojbl.cn/Article/details/gt2jvajvbip.html

[Q07] 删除表
来源：http://dali.jqgufenzy.top/Article/details/gt2fywqxpeu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.smart0.xyz/Article/details/gt2lgkexwhu.html

[Q08] 创建普通索引
来源：http://dali.tianlin.xyz/Article/details/gt2jlaewukh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shangyingyoupin.top/Article/details/gt2rodpknoq.html

[Q09] 创建唯一索引
来源：http://dali.xuetiantiany.cn/Article/details/gt2lpqecvrm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gt2qgiohfmk.html

[Q10] 插入单行
来源：http://dali.shuidangran.top/Article/details/gt2qmygdgqp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.svipenyu.cn/Article/details/gt2qhntwowu.html

[Q11] 一次插入多行
来源：http://dali.jiagoushi.top/Article/details/gt2hzcaxnnf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gt2josrvtwv.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qvabowkc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.dashuyun.cn/Article/details/gt2mcgaelkl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.snrcjt.cn/Article/details/gt2qzoyjker.html

[Q13] 忽略重复插入
来源：http://dali.tianlin.xyz/Article/details/gt2awrlketp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xuanzx.com/Article/details/gt2ddmopwnj.html

[Q14] 存在则更新（upsert）
来源：http://dali.yanxiufei.cn/Article/details/gt2abizkesz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jianghu66.top/Article/details/gt2cncktudo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yvedp.cn/Article/details/gt2lsbdufke.html

[Q15] 查询全部
来源：http://dali.jqgufenzy.top/Article/details/gt2ihiteqfn.html

SELECT * FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2gqdxpdcs.html

[Q16] 查询指定列
来源：http://dali.jqgufenzy.top/Article/details/gt2wktrrlis.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmkwwzq.html

[Q17] 条件查询
来源：http://dali.pengpengdd.cyou/Article/details/gt2klabvloe.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhengqikj.top/Article/details/gt2kbjkczvx.html

[Q18] 模糊匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2baakenux.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnxiangtu.top/Article/details/gt2ebeerunp.html

[Q19] 范围查询
来源：http://dali.xinyue.icu/Article/details/gt2dchtorfe.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cucudq.cn/Article/details/gt2gmxmtdcp.html

[Q20] IN 列表
来源：http://dali.cdnleiting.top/Article/details/gt2fwmyyknw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hywenlv.cn/Article/details/gt2qbguzmzd.html

[Q21] 空值判断
来源：http://dali.zhoulong.xyz/Article/details/gt2eoevflub.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj20258888.top/Article/details/gt2yxhmvums.html

[Q22] 排序
来源：http://dali.kuanghao11.cn/Article/details/gt2jodvybnk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.kuanghao11.cn/Article/details/gt2keowwmft.html

[Q23] 分页
来源：http://dali.nanxinkj.top/Article/details/gt2slmtuqxs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nnpfftwp.html

[Q24] 去重
来源：http://dali.cheryme.top/Article/details/gt2zzrqjlnn.html

SELECT DISTINCT city FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ltmreick.html

[Q25] 只取前 N 条
来源：http://dali.fzhhl.top/Article/details/gt2ruqzihpk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shangyingyoupin.top/Article/details/gt2ncfefgkn.html

[Q26] 计数
来源：http://dali.yangfankeji.com/Article/details/gt2xwnlacyj.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2xmaxmqlm.html

[Q27] 条件计数
来源：http://dali.cheryme.top/Article/details/gt2uejlzjlq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2kvnzgzlq.html

[Q28] 求和与平均
来源：http://dali.sweek.top/Article/details/gt2ujbmwgut.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tanke756.top/Article/details/gt2kpecbrps.html

[Q29] 最大最小值
来源：http://dali.xylfe.cn/Article/details/gt2gumhhgos.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2vpruibvi.html

[Q30] 分组统计
来源：http://dali.jiagoushi.top/Article/details/gt2veezambh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gt2njqudoog.html

[Q31] 分组后过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2obwltgcl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ehwqpu.com/Article/details/gt2cvhtpigc.html

[Q32] 分组拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2ufhqchkz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gt2qxysrgjs.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.dianchejie.cn/Article/details/gt2rjsfifxn.html

[Q33] 多列分组
来源：http://dali.chenlongwang.top/Article/details/gt2vxeqfbbu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cagusfsf.html

[Q34] 每组取第一条
来源：http://dali.yanxiufei.cn/Article/details/gt2lircozwf.html

SELECT * FROM (
来源：http://dali.smart0.xyz/Article/details/gt2elkhmmbo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pdnnoigc.html

) t WHERE rn = 1;
来源：http://dali.hnxiangtu.top/Article/details/gt2quteomya.html

[Q35] 内连接
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rryfrtxz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gt2xjhjrjle.html

[Q36] 左连接
来源：http://dali.chenlongwang.top/Article/details/gt2hnsbyiuc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxinkj.top/Article/details/gt2ykweuxqi.html

[Q37] 右连接
来源：http://dali.kuanghao11.cn/Article/details/gt2zlcdpbwu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2gxsdzyvb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hysaishi.cn/Article/details/gt2urdigvre.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.aibaodan.cn/Article/details/gt2valhtiwz.html

[Q39] 自连接（查上下级）
来源：http://dali.cheryme.top/Article/details/gt2xdijtfdo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxuanxn.top/Article/details/gt2xgahsvsq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenlongwang.top/Article/details/gt2fuzamkxl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nwbrower.top/Article/details/gt2csqjphnk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jqgfzy.top/Article/details/gt2oexehiyo.html

[Q41] 多表连接
来源：http://dali.xuanzx.com/Article/details/gt2sfsjuhzo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tanke756.top/Article/details/gt2nsbuzsaf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xinyue.icu/Article/details/gt2zdeigzja.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tzfhsmah.html

[Q42] 连接条件附加过滤
来源：http://dali.ppjwa.cn/Article/details/gt2snmglnfe.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sweek.top/Article/details/gt2dyqklsgw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nanxinkj.top/Article/details/gt2gzcpjmpi.html

[Q43] 标量子查询
来源：http://dali.zhongyouzk.top/Article/details/gt2quvixwti.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.guowangkeji.top/Article/details/gt2asztnefr.html

[Q44] IN 子查询
来源：http://dali.iojbl.cn/Article/details/gt2rndfeeow.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.316326.xyz/Article/details/gt2dyhzlipn.html

[Q45] EXISTS 判断存在
来源：http://dali.vqdsnc.cn/Article/details/gt2llrrztyp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gt2xloevsei.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mdypqedi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.mhx1999.top/Article/details/gt2cingaoqy.html

[Q47] 与平均值比较
来源：http://dali.sxryk.cn/Article/details/gt2okjwbire.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.andypj.xyz/Article/details/gt2hgpyvhwd.html

[Q48] CTE 公用表表达式
来源：http://dali.xuanzx.com/Article/details/gt2hsakpfrk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hfpthk.cn/Article/details/gt2uascoozo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aibaodan.cn/Article/details/gt2gamnulpt.html

[Q49] 更新单行
来源：http://dali.pycfn.com/Article/details/gt2qddujrqj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj20258888.top/Article/details/gt2oopqbkbx.html

[Q50] 批量更新
来源：http://dali.xylfe.cn/Article/details/gt2pioqmjnt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.andypj.xyz/Article/details/gt2pidmrpbo.html

[Q51] 用子查询更新
来源：http://dali.hnxiangtu.top/Article/details/gt2faacrlmo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2thvgnyrw.html

[Q52] 删除指定行
来源：http://dali.wangdashe.top/Article/details/gt2uybcylyb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gotoacloud.top/Article/details/gt2kgtflqfs.html

[Q53] 按条件删除
来源：http://dali.c1oappe.top/Article/details/gt2qksptldd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.snrcjt.cn/Article/details/gt2nqgiarrp.html

[Q54] 清空表
来源：http://dali.chenzaomai.com/Article/details/gt2xrbcwadc.html

TRUNCATE TABLE logs;
来源：http://dali.gzhubu.top/Article/details/gt2zbsncxjq.html

[Q55] 排名（并列占位）
来源：http://dali.0kj1m.cn/Article/details/gt2magbwytb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgufenzy.top/Article/details/gt2uontxpyl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.haohaochexian.top/Article/details/gt2wykzqapn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yuanzhike.top/Article/details/gt2hnsoszww.html

[Q57] 行号
来源：http://dali.0kj1m.cn/Article/details/gt2rcafeeuw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2mrxtrccd.html

[Q58] 累计求和
来源：http://dali.xuetiantiany.cn/Article/details/gt2xphlcjbj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2qtzorzgv.html

[Q59] 分组内累计
来源：http://dali.sweek.top/Article/details/gt2zpcamzyu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2lbfrukev.html

[Q60] 取上一行 / 下一行
来源：http://dali.sysykeji.top/Article/details/gt2ugedzlze.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ehwqpu.com/Article/details/gt2fxqnvitb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gqmfhekl.html

[Q61] 移动平均
来源：http://dali.aizwys.cn/Article/details/gt2qupknevi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gt2dsoaoclg.html

[Q62] 分组占比
来源：http://dali.hfpthk.cn/Article/details/gt2qlkaaqvi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gt2whwsfeyl.html

[Q63] 开启事务
来源：http://dali.316326.xyz/Article/details/gt2kyrbzofo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.smart0.xyz/Article/details/gt2qqhjexgk.html

[Q64] 提交事务
来源：http://dali.hnqzz.top/Article/details/gt2ctnbcjtt.html

COMMIT;
来源：http://dali.nanxinkj.top/Article/details/gt2xkbvqxiq.html

[Q65] 回滚事务
来源：http://dali.xziqi.cn/Article/details/gt2jopwhdaw.html

ROLLBACK;
来源：http://dali.nanxuanxn.top/Article/details/gt2dxaqzwdq.html

[Q66] 行锁查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2frvirmgy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tanke756.top/Article/details/gt2rtjnjtyv.html

[Q67] 设置隔离级别
来源：http://dali.iojbl.cn/Article/details/gt2rkfcyioj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dashuyun.cn/Article/details/gt2ojeueoao.html

[Q68] 保存点
来源：http://dali.zhixingplan.top/Article/details/gt2wlysqgjj.html

SAVEPOINT sp1;
来源：http://dali.birdmap.top/Article/details/gt2gkdcaprw.html

ROLLBACK TO sp1;
来源：http://dali.cucudq.cn/Article/details/gt2dighljcm.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrjlvzu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.wangshuangyany.cn/Article/details/gt2koczakxc.html

[Q70] 更新统计信息
来源：http://dali.tian-w.cn/Article/details/gt2hbnfwwfo.html

ANALYZE TABLE users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2qblihykc.html

[Q71] 查看建表语句
来源：http://dali.cdnleiting.top/Article/details/gt2iskqapft.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gotoacloud.top/Article/details/gt2tedxydzb.html

[Q72] 查看索引
来源：http://dali.shzxlz.cn/Article/details/gt2qxyvxyze.html

SHOW INDEX FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2noiarwks.html

[Q73] 查看表状态
来源：http://dali.smart0.xyz/Article/details/gt2drqehsms.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.daxiang520.top/Article/details/gt2sbalrwql.html

[Q74] 强制使用索引
来源：http://dali.guowangkeji.top/Article/details/gt2crbotekd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shzxlz.cn/Article/details/gt2usxcgjjm.html

[Q75] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gt2vtvmyrwf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2tohruyqu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xylfe.cn/Article/details/gt2rexlfztc.html

[Q76] 按天统计
来源：http://dali.aizwys.cn/Article/details/gt2ustzbrna.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnxiangtu.top/Article/details/gt2wgvgmlub.html

[Q77] 时间加减
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nxuxhvrn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.meibo888.top/Article/details/gt2ddgagjsv.html

[Q78] 当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gt2rcymamkk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sxryk.cn/Article/details/gt2zrcocldz.html

[Q79] 字符串拼接
来源：http://dali.cdnleiting.top/Article/details/gt2fkebktuu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.snrcjt.cn/Article/details/gt2tnoxwbtb.html

[Q80] 字符串截取
来源：http://dali.daxiang520.top/Article/details/gt2fyedesgl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2ckxislkh.html

[Q81] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2efgccdxi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2jenrzmuz.html

[Q82] 字符长度与字节长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gvtbkcke.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2kvextssm.html

[Q83] 大小写转换
来源：http://dali.tanke756.top/Article/details/gt2nhqwyrtb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2xiqsnfnp.html

[Q84] 去除首尾空格
来源：http://dali.yj20258.top/Article/details/gt2zkgyfedk.html

SELECT TRIM(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2hlzehjab.html

[Q85] 数值取整
来源：http://dali.zycfv.cn/Article/details/gt2nqxkopyh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.fzhhl.top/Article/details/gt2jehcktwp.html

[Q86] 读取 JSON 字段
来源：http://dali.jqgufenzy.top/Article/details/gt2xgwcwydf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fengsongda.top/Article/details/gt2ztclewlf.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigufen.top/Article/details/gt2ccfymvpo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shuidangran.top/Article/details/gt2qvoervap.html

[Q88] 行转列（条件聚合）
来源：http://dali.sysykeji.top/Article/details/gt2yjsssxhv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gotoacloud.top/Article/details/gt2dnwiapnh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2dwejmqsj.html

[Q89] 判断表是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2tgtzulkb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zycfv.cn/Article/details/gt2ltudtwwe.html

[Q90] 生成序号列
来源：http://dali.zhiwuduotai.top/Article/details/gt2swcbtawe.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hqzozzmq.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2fgdqgfxc.html

R. Bash 专题
来源：http://dali.wangshuangyany.cn/Article/details/gt2hfmuxpny.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2uxpzoxza.html

[R01] shebang 与严格模式
来源：http://dali.gotoacloud.top/Article/details/gt2kabrkron.html

#!/usr/bin/env bash
来源：http://dali.gzhubu.top/Article/details/gt2zdsxqovt.html

set -euo pipefail
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bzvvxznl.html

[R02] 变量赋值与使用
来源：http://dali.cqqwz.cn/Article/details/gt2rdoguntq.html

name="Tom"; echo "$name"
来源：http://dali.shangyingyoupin.top/Article/details/gt2vglchady.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxxdxwk.html

readonly PI=3.14
来源：http://dali.shuidangran.top/Article/details/gt2psornqnm.html

[R04] 位置参数
来源：http://dali.shzxlz.cn/Article/details/gt2iocmljqn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tanke756.top/Article/details/gt2ueqikpri.html

[R05] 参数默认值
来源：http://dali.hammf.cn/Article/details/gt2oioaixdh.html

name="${1:-default}"
来源：http://dali.quarkkingdee.top/Article/details/gt2nhpwmafk.html

[R06] 判断命令是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gt2awkwrehh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hywenlv.cn/Article/details/gt2ncuhtnfg.html

[R07] if 判断文件
来源：http://dali.yuxming.cn/Article/details/gt2mcfxhies.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yongpay.top/Article/details/gt2szpogqww.html

[R08] 数值比较
来源：http://dali.xylfe.cn/Article/details/gt2owwzuxud.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gt2eqqckhuq.html

[R09] 字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vmxwxhyu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenlongwang.top/Article/details/gt2qntyfcgn.html

[R10] 正则匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2nkixqetf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sxryk.cn/Article/details/gt2uqmxdbqq.html

[R11] case 多分支
来源：http://dali.pycfn.com/Article/details/gt2nylveymc.html

case "$1" in
来源：http://dali.hfpthk.cn/Article/details/gt2xgvgxvje.html

start) echo "启动" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ybqcqspu.html

stop)  echo "停止" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2scormyzx.html

*)     echo "未知命令" ;;
来源：http://dali.tanke756.top/Article/details/gt2ikkhmdkw.html

esac
来源：http://dali.yuanzhike.top/Article/details/gt2toabyavi.html

[R12] for 遍历文件
来源：http://dali.aibaodan.cn/Article/details/gt2htbuvqsi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenlongwang.top/Article/details/gt2wumcdjhv.html

[R13] for 计数循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2lqvnnhdy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gt2wwgewpbj.html

[R14] C 风格 for
来源：http://dali.dianchejie.cn/Article/details/gt2bzmdtekp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yangfankeji.com/Article/details/gt2pkbmiryr.html

[R15] while 逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gt2duxctdbi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cucudq.cn/Article/details/gt2vagxokzc.html

[R16] until 等待条件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gmgisonw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gt2vhcnmlwn.html

[R17] 数组定义与取值
来源：http://dali.zhiwuduotai.top/Article/details/gt2ctuufgtq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.guowangkeji.top/Article/details/gt2unmkdnay.html

[R18] 遍历数组
来源：http://dali.pengpengdd.cyou/Article/details/gt2hfozgfnj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ybcxt.top/Article/details/gt2iruewdme.html

[R19] 数组长度
来源：http://dali.dashuyun.cn/Article/details/gt2rjdmncfv.html

echo "${#arr[@]}"
来源：http://dali.yuxming.cn/Article/details/gt2blsdrhed.html

[R20] 关联数组（字典）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hmcclsfv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnqzz.top/Article/details/gt2alzomwji.html

[R21] 字符串长度
来源：http://dali.xziqi.cn/Article/details/gt2sfgqjhiq.html

echo "${#s}"
来源：http://dali.iojbl.cn/Article/details/gt2rwwuejjm.html

[R22] 截取子串
来源：http://dali.jqgfzy.top/Article/details/gt2vrdnsceo.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtuuqgv.html

[R23] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gt2uqkgkifi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gslzpldl.html

[R24] 大小写转换
来源：http://dali.havefunace.top/Article/details/gt2ifwrfivt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.c1oappe.top/Article/details/gt2hldneojg.html

[R25] 去后缀 / 去前缀
来源：http://dali.tianlin.xyz/Article/details/gt2jiuqpzfo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jianghu66.top/Article/details/gt2ipzkilfn.html

[R26] 命令替换
来源：http://dali.gzhubu.top/Article/details/gt2czvsaskb.html

now=$(date +%F); echo "$now"
来源：http://dali.shzxlz.cn/Article/details/gt2klsrnjrs.html

[R27] 算术展开
来源：http://dali.hammf.cn/Article/details/gt2zlhajntq.html

echo $((1 + 2 * 3))
来源：http://dali.wangdashe.top/Article/details/gt2wyqkgcxg.html

[R28] 浮点运算
来源：http://dali.ppjwa.cn/Article/details/gt2pwxmuhaa.html

echo "scale=2; 10/3" | bc
来源：http://dali.jianghu66.top/Article/details/gt2odxvgapw.html

[R29] 定义函数
来源：http://dali.nwbrower.top/Article/details/gt2qqhwibud.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.meibo888.top/Article/details/gt2tcjmccea.html

[R30] 函数返回状态码
来源：http://dali.yangfankeji.com/Article/details/gt2ckhcqfci.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ppjwa.cn/Article/details/gt2wmrzxmdt.html

[R31] 局部变量
来源：http://dali.meibo888.top/Article/details/gt2ryytixsi.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2syypgytn.html

[R32] 参数个数校验
来源：http://dali.yongpay.top/Article/details/gt2ivohjhae.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gt2lowizbzk.html

[R33] 捕获错误并提示行号
来源：http://dali.mhx1999.top/Article/details/gt2oaocvqcc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj20258888.top/Article/details/gt2afrumqha.html

[R34] 退出时清理
来源：http://dali.zycfv.cn/Article/details/gt2htfdpdmq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gt2xajlwbho.html

[R35] 后台执行并等待
来源：http://dali.mhx1999.top/Article/details/gt2jztczsme.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.316326.xyz/Article/details/gt2gxlyavgs.html

[R36] 并发执行多个任务
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzvqiqgp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.snrcjt.cn/Article/details/gt2uupykeul.html

[R37] 把输出赋给变量
来源：http://dali.quarkkingdee.top/Article/details/gt2gezajugj.html

files=$(ls -1)
来源：http://dali.gotoacloud.top/Article/details/gt2xoveoguq.html

[R38] 管道串联
来源：http://dali.guowangkeji.top/Article/details/gt2gpjcjhrt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhoulong.xyz/Article/details/gt2eiaaayzt.html

[R39] 重定向标准输出与错误
来源：http://dali.cucudq.cn/Article/details/gt2vteyblad.html

cmd > out.log 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gt2fhssfntz.html

[R40] 追加写日志
来源：http://dali.sweek.top/Article/details/gt2nesancjv.html

echo "log" >> out.log
来源：http://dali.daria6918.cn/Article/details/gt2crbdbmel.html

[R41] 丢弃输出
来源：http://dali.hfpthk.cn/Article/details/gt2dwtubzha.html

cmd >/dev/null 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gt2solyswvs.html

[R42] 输入重定向
来源：http://dali.9152youxi.cn/Article/details/gt2lbnaqovd.html

wc -l < a.txt
来源：http://dali.c1oappe.top/Article/details/gt2bwasyzno.html

[R43] 按名字查找文件
来源：http://dali.yuxming.cn/Article/details/gt2sveuanck.html

find . -name "*.log" -type f
来源：http://dali.hongshengwenyu.top/Article/details/gt2iqjdbnoy.html

[R44] 按修改时间查找
来源：http://dali.gzhubu.top/Article/details/gt2bbxagnmy.html

find . -mtime -7 -type f
来源：http://dali.sufxvd.cn/Article/details/gt2roxufhnl.html

[R45] 批量删除
来源：http://dali.zhiwuduotai.top/Article/details/gt2mmsjxdxq.html

find . -name "*.tmp" -delete
来源：http://dali.cdnleiting.top/Article/details/gt2uiobcudt.html

[R46] 递归替换文件内容
来源：http://dali.hnxiangtu.top/Article/details/gt2ybnszcxv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hysaishi.cn/Article/details/gt2nikmbtgz.html

[R47] sed 单行替换
来源：http://dali.yj20258.top/Article/details/gt2wxlovgbb.html


<!-- 参考信息 -->