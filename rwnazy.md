代发 wailian999

CREATE TABLE users (
来源：http://dali.dashuyun.cn/Article/details/gt2juywwmgq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gotoacloud.top/Article/details/gt2pfkegnvi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gt2cotwgdms.html

email VARCHAR(100) UNIQUE,
来源：http://dali.aizwys.cn/Article/details/gt2fxnadnkv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yanxiufei.cn/Article/details/gt2dnfqxcaf.html

);
来源：http://dali.jlsjyb.cn/Article/details/gt2jyljcplj.html

[Q02] 创建带外键的表
来源：http://dali.hongshengwenyu.top/Article/details/gt2kyqrnelm.html

CREATE TABLE orders (
来源：http://dali.jianghu66.top/Article/details/gt2uuvrwpkd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhoulong.xyz/Article/details/gt2ikftpzxn.html

user_id INT NOT NULL,
来源：http://dali.nanxinkj.top/Article/details/gt2ofcfetsf.html

amount DECIMAL(10, 2),
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kulplcpn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.redwolf501.top/Article/details/gt2njooazrx.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gt2hwsxgqgs.html

[Q03] 增加列
来源：http://dali.jiagoushi.top/Article/details/gt2juvcxvvd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vbaihgrl.html

[Q04] 修改列类型
来源：http://dali.sysykeji.top/Article/details/gt2jdzxczwj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.c1oappe.top/Article/details/gt2ccpxujpb.html

[Q05] 重命名列
来源：http://dali.svipenyu.cn/Article/details/gt2fuhliphd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hammf.cn/Article/details/gt2dhmfrpgi.html

[Q06] 删除列
来源：http://dali.kuanghao11.cn/Article/details/gt2qaldkmpb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sxryk.cn/Article/details/gt2pxgukkeg.html

[Q07] 删除表
来源：http://dali.tianlin.xyz/Article/details/gt2qyfcqpol.html

DROP TABLE IF EXISTS orders;
来源：http://dali.dashuyun.cn/Article/details/gt2bradaycl.html

[Q08] 创建普通索引
来源：http://dali.yueranfly.top/Article/details/gt2ogfjgodf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hfpthk.cn/Article/details/gt2tmzymphu.html

[Q09] 创建唯一索引
来源：http://dali.316326.xyz/Article/details/gt2xcfirkue.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gt2xdzustpa.html

[Q10] 插入单行
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mmifokqg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ivvv.top/Article/details/gt2ulirfkkq.html

[Q11] 一次插入多行
来源：http://dali.zdqjudy.top/Article/details/gt2zchzuvha.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jiagoushi.top/Article/details/gt2vpunanwh.html

[Q12] 插入后取自增 ID
来源：http://dali.nanxuanxn.top/Article/details/gt2flbuaflk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xuetiantiany.cn/Article/details/gt2cvxmomvv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nwbrower.top/Article/details/gt2jkogmkip.html

[Q13] 忽略重复插入
来源：http://dali.c1oappe.top/Article/details/gt2ktjpazeg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gt2cjjbbcaa.html

[Q14] 存在则更新（upsert）
来源：http://dali.ivvv.top/Article/details/gt2qjxdoxiy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhongyouzk.top/Article/details/gt2iocwrkyu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gotoacloud.top/Article/details/gt2shfkjcxa.html

[Q15] 查询全部
来源：http://dali.cashguo.top/Article/details/gt2ajoddjrb.html

SELECT * FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2lazowzif.html

[Q16] 查询指定列
来源：http://dali.yj20258888.top/Article/details/gt2lglnzeys.html

SELECT id, name FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2ozdpjcdc.html

[Q17] 条件查询
来源：http://dali.xylfe.cn/Article/details/gt2mjuvzxiz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cdnleiting.top/Article/details/gt2svrltegz.html

[Q18] 模糊匹配
来源：http://dali.xinyue.icu/Article/details/gt2ihxoyapb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xuanzx.com/Article/details/gt2mkdqsoiq.html

[Q19] 范围查询
来源：http://dali.hnqzz.top/Article/details/gt2oaxjjkdi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenlongwang.top/Article/details/gt2gucnogsb.html

[Q20] IN 列表
来源：http://dali.jqgufenzy.top/Article/details/gt2vogeqofw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2vacvbakb.html

[Q21] 空值判断
来源：http://dali.gaohongyu789.top/Article/details/gt2lvpchsrj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxinkj.top/Article/details/gt2jtxurhnh.html

[Q22] 排序
来源：http://dali.jinqigfzy.top/Article/details/gt2khgtqebt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.haohaochexian.top/Article/details/gt2smymafui.html

[Q23] 分页
来源：http://dali.jinqigufen.top/Article/details/gt2ileyklqd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jlsjyb.cn/Article/details/gt2tbfhjlms.html

[Q24] 去重
来源：http://dali.gaohongyu789.top/Article/details/gt2lcstbzif.html

SELECT DISTINCT city FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2hllzwmxc.html

[Q25] 只取前 N 条
来源：http://dali.hongshengwenyu.top/Article/details/gt2kxsckewm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xuanzx.com/Article/details/gt2ngbmuidc.html

[Q26] 计数
来源：http://dali.chenzaomai.com/Article/details/gt2udoilfzg.html

SELECT COUNT(*) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2oebzquvy.html

[Q27] 条件计数
来源：http://dali.havefunace.top/Article/details/gt2arfbxoez.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj202588.top/Article/details/gt2efydturl.html

[Q28] 求和与平均
来源：http://dali.wangshuangyany.cn/Article/details/gt2yoavjfjs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2xexerllh.html

[Q29] 最大最小值
来源：http://dali.hysaishi.cn/Article/details/gt2oeckzqkp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2yvtbhldo.html

[Q30] 分组统计
来源：http://dali.gzhubu.top/Article/details/gt2tvkvfjkr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gt2fqmpilpt.html

[Q31] 分组后过滤
来源：http://dali.yueranfly.top/Article/details/gt2rlphrthh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj20258888.top/Article/details/gt2dcwyoxnr.html

[Q32] 分组拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2erasgboh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gt2ywfmzivt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jqgfzy.top/Article/details/gt2pgngwpjq.html

[Q33] 多列分组
来源：http://dali.wangshuangyany.cn/Article/details/gt2msnpdfbm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pycfn.com/Article/details/gt2wkbdmdai.html

[Q34] 每组取第一条
来源：http://dali.gotoacloud.top/Article/details/gt2acwkinna.html

SELECT * FROM (
来源：http://dali.316326.xyz/Article/details/gt2qcserbyj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yuxming.cn/Article/details/gt2lgutlzyp.html

) t WHERE rn = 1;
来源：http://dali.fengsongda.top/Article/details/gt2vidfpaev.html

[Q35] 内连接
来源：http://dali.svipenyu.cn/Article/details/gt2tczbjsgy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gt2gemhovej.html

[Q36] 左连接
来源：http://dali.dianchejie.cn/Article/details/gt2rimvmhfh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gt2mhawupij.html

[Q37] 右连接
来源：http://dali.xuanzx.com/Article/details/gt2vrofywdx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sweek.top/Article/details/gt2swrmdxno.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cucudq.cn/Article/details/gt2mhjsmfaw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.guowangkeji.top/Article/details/gt2iosssxlx.html

[Q39] 自连接（查上下级）
来源：http://dali.dianchejie.cn/Article/details/gt2bgdxsnbj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dianchejie.cn/Article/details/gt2qnfbkwec.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gogol.net.cn/Article/details/gt2hgrqowcz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.vqdsnc.cn/Article/details/gt2bgltkugs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.meibo888.top/Article/details/gt2cilakmzk.html

[Q41] 多表连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2exqvsajt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xziqi.cn/Article/details/gt2tuxbvuif.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ehwqpu.com/Article/details/gt2trciqkbd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jyoumei.cn/Article/details/gt2ltjmpskh.html

[Q42] 连接条件附加过滤
来源：http://dali.9152youxi.cn/Article/details/gt2thfmkkpw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tian-w.cn/Article/details/gt2pmichdhn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.pycfn.com/Article/details/gt2vyrttkhd.html

[Q43] 标量子查询
来源：http://dali.svipenyu.cn/Article/details/gt2zetcruth.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.snrcjt.cn/Article/details/gt2nbucwynf.html

[Q44] IN 子查询
来源：http://dali.nwbrower.top/Article/details/gt2bhgugtgl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cqqwz.cn/Article/details/gt2yffxdnjv.html

[Q45] EXISTS 判断存在
来源：http://dali.chenzaomai.com/Article/details/gt2rrhwnqqj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dianchejie.cn/Article/details/gt2daosagxr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.aibaodan.cn/Article/details/gt2eoqmpxhz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.havefunace.top/Article/details/gt2pdddurim.html

[Q47] 与平均值比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2clxhevse.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinqigufen.top/Article/details/gt2dxsprjai.html

[Q48] CTE 公用表表达式
来源：http://dali.fzhhl.top/Article/details/gt2nehxvxfs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yueranfly.top/Article/details/gt2nqhopzeu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.kuanghao11.cn/Article/details/gt2mjvmtutz.html

[Q49] 更新单行
来源：http://dali.316326.xyz/Article/details/gt2guhdgvbe.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhixingplan.top/Article/details/gt2skubgcxm.html

[Q50] 批量更新
来源：http://dali.jinqigfzy.top/Article/details/gt2owzgjoel.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.9152youxi.cn/Article/details/gt2gpxdmohc.html

[Q51] 用子查询更新
来源：http://dali.gogol.net.cn/Article/details/gt2gucehnpd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jyoumei.cn/Article/details/gt2rfzuvxlg.html

[Q52] 删除指定行
来源：http://dali.feifeiyinyue.top/Article/details/gt2fzqxpshc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gt2oumpiitf.html

[Q53] 按条件删除
来源：http://dali.mhx1999.top/Article/details/gt2xclopvlc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gotoacloud.top/Article/details/gt2ugsaeylo.html

[Q54] 清空表
来源：http://dali.jqgufenzy.top/Article/details/gt2dnibdyzx.html

TRUNCATE TABLE logs;
来源：http://dali.kuanghao11.cn/Article/details/gt2ajtdvdsn.html

[Q55] 排名（并列占位）
来源：http://dali.c1oappe.top/Article/details/gt2gesvuwcf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gt2klrkxnvj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cdnleiting.top/Article/details/gt2jecxlrbv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gt2isbzdakg.html

[Q57] 行号
来源：http://dali.0kj1m.cn/Article/details/gt2agwsmomw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2repsmdao.html

[Q58] 累计求和
来源：http://dali.ybcxt.top/Article/details/gt2yxfxbglu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.mhx1999.top/Article/details/gt2jgdbyjxn.html

[Q59] 分组内累计
来源：http://dali.yonumen.top/Article/details/gt2bkewvaad.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gt2zlqvkruh.html

[Q60] 取上一行 / 下一行
来源：http://dali.ybcxt.top/Article/details/gt2wpbpdwlt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jianghu66.top/Article/details/gt2olscqpvo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2enufcsbn.html

[Q61] 移动平均
来源：http://dali.yj20258.top/Article/details/gt2ywtvmgvm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.havefunace.top/Article/details/gt2drarkapv.html

[Q62] 分组占比
来源：http://dali.jianghu66.top/Article/details/gt2iswztchx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gt2zfvhmwos.html

[Q63] 开启事务
来源：http://dali.vqdsnc.cn/Article/details/gt2qrbmzcwb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yanxiufei.cn/Article/details/gt2lclczbjt.html

[Q64] 提交事务
来源：http://dali.tanke756.top/Article/details/gt2kgggtbeg.html

COMMIT;
来源：http://dali.sufxvd.cn/Article/details/gt2qlmdwkro.html

[Q65] 回滚事务
来源：http://dali.tian-w.cn/Article/details/gt2wmqizgck.html

ROLLBACK;
来源：http://dali.yonumen.top/Article/details/gt2watjiaku.html

[Q66] 行锁查询
来源：http://dali.meibo888.top/Article/details/gt2lnnvepts.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.quarkkingdee.top/Article/details/gt2eewixvhj.html

[Q67] 设置隔离级别
来源：http://dali.ehwqpu.com/Article/details/gt2suvpagro.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tianlin.xyz/Article/details/gt2rqdyccmn.html

[Q68] 保存点
来源：http://dali.sweek.top/Article/details/gt2xazlzwdu.html

SAVEPOINT sp1;
来源：http://dali.sufxvd.cn/Article/details/gt2gnabgxho.html

ROLLBACK TO sp1;
来源：http://dali.aibaodan.cn/Article/details/gt2audwcofc.html

[Q69] 查看执行计划
来源：http://dali.mhx1999.top/Article/details/gt2auixmtav.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tanke756.top/Article/details/gt2nbecwbqo.html

[Q70] 更新统计信息
来源：http://dali.tian-w.cn/Article/details/gt2jfqvqhod.html

ANALYZE TABLE users;
来源：http://dali.shzxlz.cn/Article/details/gt2lekmojvo.html

[Q71] 查看建表语句
来源：http://dali.shzxlz.cn/Article/details/gt2cyclyehp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.fzhhl.top/Article/details/gt2ycjatdkv.html

[Q72] 查看索引
来源：http://dali.zhengqikj.top/Article/details/gt2kpeiqxdp.html

SHOW INDEX FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2ftnvecof.html

[Q73] 查看表状态
来源：http://dali.hnxiangtu.top/Article/details/gt2otoqkozi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.meibo888.top/Article/details/gt2qxubdkaz.html

[Q74] 强制使用索引
来源：http://dali.zhiwuduotai.top/Article/details/gt2fsfrgoeq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hysaishi.cn/Article/details/gt2aikukbpu.html

[Q75] 日期格式化
来源：http://dali.wangdashe.top/Article/details/gt2onpzwusv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gt2qtbqwcsm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dyiyryfr.html

[Q76] 按天统计
来源：http://dali.yuxming.cn/Article/details/gt2ianspfzf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jlsjyb.cn/Article/details/gt2yntaxwnb.html

[Q77] 时间加减
来源：http://dali.gogol.net.cn/Article/details/gt2febitgym.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.snrcjt.cn/Article/details/gt2utedzacb.html

[Q78] 当前时间
来源：http://dali.birdmap.top/Article/details/gt2ahdgrnqt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.birdmap.top/Article/details/gt2rkunrodt.html

[Q79] 字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hungdrnj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgfzy.top/Article/details/gt2aknczsug.html

[Q80] 字符串截取
来源：http://dali.yangfankeji.com/Article/details/gt2fbesxwpd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2ajyuytvr.html

[Q81] 字符串替换
来源：http://dali.mhx1999.top/Article/details/gt2wfmonqra.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2gpocqbrj.html

[Q82] 字符长度与字节长度
来源：http://dali.sufxvd.cn/Article/details/gt2sknzwlix.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2dqdhbloq.html

[Q83] 大小写转换
来源：http://dali.birdmap.top/Article/details/gt2kjlfsywf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2qxdvyylp.html

[Q84] 去除首尾空格
来源：http://dali.0kj1m.cn/Article/details/gt2rlirbpmc.html

SELECT TRIM(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2nevpmvzf.html

[Q85] 数值取整
来源：http://dali.sufxvd.cn/Article/details/gt2mzywyhlm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhixingplan.top/Article/details/gt2dhfazfsc.html

[Q86] 读取 JSON 字段
来源：http://dali.tian-w.cn/Article/details/gt2bunznodw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.snrcjt.cn/Article/details/gt2ttnfuyok.html

[Q87] JSON 字段做条件
来源：http://dali.jqgufenzy.top/Article/details/gt2gvjdzkvp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xylfe.cn/Article/details/gt2niyvxjtl.html

[Q88] 行转列（条件聚合）
来源：http://dali.cucudq.cn/Article/details/gt2vcphmvws.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.dianchejie.cn/Article/details/gt2shligjrs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hammf.cn/Article/details/gt2ydyqbzry.html

[Q89] 判断表是否存在
来源：http://dali.nwbrower.top/Article/details/gt2eehvadjj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.aibaodan.cn/Article/details/gt2zirpodte.html

[Q90] 生成序号列
来源：http://dali.zhengqikj.top/Article/details/gt2usjqqfum.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.c1oappe.top/Article/details/gt2fncctuey.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2unkvjawh.html

R. Bash 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fjwkugne.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2uraqajkp.html

[R01] shebang 与严格模式
来源：http://dali.ivvv.top/Article/details/gt2tdsvhtzb.html

#!/usr/bin/env bash
来源：http://dali.sufxvd.cn/Article/details/gt2wqecmsak.html

set -euo pipefail
来源：http://dali.cashguo.top/Article/details/gt2elkmvibz.html

[R02] 变量赋值与使用
来源：http://dali.bjfxy.top/Article/details/gt2uwusrqnh.html

name="Tom"; echo "$name"
来源：http://dali.ydzc1.top/Article/details/gt2rsngjyni.html

[R03] 只读变量
来源：http://dali.guowangkeji.top/Article/details/gt2vnhkeltb.html

readonly PI=3.14
来源：http://dali.quarkkingdee.top/Article/details/gt2ciywairk.html

[R04] 位置参数
来源：http://dali.jianghu66.top/Article/details/gt2ugiwenks.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uvmcjrja.html

[R05] 参数默认值
来源：http://dali.svipenyu.cn/Article/details/gt2jdlmtkra.html

name="${1:-default}"
来源：http://dali.iojbl.cn/Article/details/gt2jrmqqviw.html

[R06] 判断命令是否存在
来源：http://dali.jinqigfzy.top/Article/details/gt2dmlbghti.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.haohaochexian.top/Article/details/gt2ecubtufi.html

[R07] if 判断文件
来源：http://dali.wangdashe.top/Article/details/gt2oqnmonqk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ehwqpu.com/Article/details/gt2incfcaax.html

[R08] 数值比较
来源：http://dali.xinyue.icu/Article/details/gt2gnkccjyx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.svipenyu.cn/Article/details/gt2ateucxcu.html

[R09] 字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2neudveok.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jianghu66.top/Article/details/gt2onwsdvhk.html

[R10] 正则匹配
来源：http://dali.hysaishi.cn/Article/details/gt2pctxengo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sweek.top/Article/details/gt2umnqhofa.html

[R11] case 多分支
来源：http://dali.hywenlv.cn/Article/details/gt2sirxhcqw.html

case "$1" in
来源：http://dali.fengsongda.top/Article/details/gt2sxwzeivv.html

start) echo "启动" ;;
来源：http://dali.smart0.xyz/Article/details/gt2wiuijgvp.html

stop)  echo "停止" ;;
来源：http://dali.jqgufenzy.top/Article/details/gt2kietwglj.html

*)     echo "未知命令" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mxljthis.html

esac
来源：http://dali.jianghu66.top/Article/details/gt2zbrqbbcz.html

[R12] for 遍历文件
来源：http://dali.ehwqpu.com/Article/details/gt2glhotspt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2izqgbxra.html

[R13] for 计数循环
来源：http://dali.yuanzhike.top/Article/details/gt2zazgalxf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gt2cgpvvyjs.html

[R14] C 风格 for
来源：http://dali.wangshuangyany.cn/Article/details/gt2wjrbvkoh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gt2sgmeckmt.html

[R15] while 逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gt2rzwdcllj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2hnwehoub.html

[R16] until 等待条件
来源：http://dali.xinyue.icu/Article/details/gt2czdffvkf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gaohongyu789.top/Article/details/gt2qyenevny.html

[R17] 数组定义与取值
来源：http://dali.yj20258.top/Article/details/gt2jnmvmtac.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sweek.top/Article/details/gt2bscqteji.html

[R18] 遍历数组
来源：http://dali.yueranfly.top/Article/details/gt2ldhddjen.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj202588.top/Article/details/gt2inaapzwk.html

[R19] 数组长度
来源：http://dali.fengsongda.top/Article/details/gt2idjswpjf.html

echo "${#arr[@]}"
来源：http://dali.tanke756.top/Article/details/gt2mvobetlo.html

[R20] 关联数组（字典）
来源：http://dali.jiagoushi.top/Article/details/gt2tmkiyoaw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jiagoushi.top/Article/details/gt2pdrpozcs.html

[R21] 字符串长度
来源：http://dali.ybcxt.top/Article/details/gt2ieqsdaqa.html

echo "${#s}"
来源：http://dali.cheryme.top/Article/details/gt2bthiwvvd.html

[R22] 截取子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vxoslqbn.html

echo "${s:0:5}"
来源：http://dali.fzhhl.top/Article/details/gt2hmdpsuyc.html

[R23] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mpvsnqso.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jianghu66.top/Article/details/gt2iabodias.html

[R24] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gt2qxskaagd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yueranfly.top/Article/details/gt2nkpfpshw.html

[R25] 去后缀 / 去前缀
来源：http://dali.mhx1999.top/Article/details/gt2uusojhfr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ybcxt.top/Article/details/gt2jndzefia.html

[R26] 命令替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2piwhbpmr.html

now=$(date +%F); echo "$now"
来源：http://dali.iojbl.cn/Article/details/gt2tsoaguqs.html

[R27] 算术展开
来源：http://dali.gogol.net.cn/Article/details/gt2uyaiqfhz.html

echo $((1 + 2 * 3))
来源：http://dali.yongpay.top/Article/details/gt2nhpekeql.html

[R28] 浮点运算
来源：http://dali.xuanzx.com/Article/details/gt2yrflrplf.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinqigfzy.top/Article/details/gt2ugkepisx.html

[R29] 定义函数
来源：http://dali.gzhubu.top/Article/details/gt2lninhwsw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangdashe.top/Article/details/gt2khzdvnvx.html

[R30] 函数返回状态码
来源：http://dali.vqdsnc.cn/Article/details/gt2napqczug.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.svipenyu.cn/Article/details/gt2lfifudcn.html

[R31] 局部变量
来源：http://dali.hfpthk.cn/Article/details/gt2isfwgpcp.html

f() { local x=1; echo "$x"; }
来源：http://dali.svipenyu.cn/Article/details/gt2ndjxmnbu.html

[R32] 参数个数校验
来源：http://dali.chenlongwang.top/Article/details/gt2muksseiu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yonumen.top/Article/details/gt2ujyftkue.html

[R33] 捕获错误并提示行号
来源：http://dali.yj20258.top/Article/details/gt2vsuszboq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenzaomai.com/Article/details/gt2kvlvmdza.html

[R34] 退出时清理
来源：http://dali.yongpay.top/Article/details/gt2bvgxzjiq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hysaishi.cn/Article/details/gt2tzuiyuft.html

[R35] 后台执行并等待
来源：http://dali.tianlin.xyz/Article/details/gt2mrnawdnd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pengpengdd.cyou/Article/details/gt2dlylzlab.html

[R36] 并发执行多个任务
来源：http://dali.chenlongwang.top/Article/details/gt2nwpagyps.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.c1oappe.top/Article/details/gt2qjnfxfmi.html

[R37] 把输出赋给变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wvnglqtd.html

files=$(ls -1)
来源：http://dali.xylfe.cn/Article/details/gt2wzhmfbar.html

[R38] 管道串联
来源：http://dali.jlsjyb.cn/Article/details/gt2gznfqaiw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhiwuduotai.top/Article/details/gt2gbnbacku.html

[R39] 重定向标准输出与错误
来源：http://dali.birdmap.top/Article/details/gt2gxbxqfmc.html

cmd > out.log 2>&1
来源：http://dali.cdnleiting.top/Article/details/gt2vljapnti.html

[R40] 追加写日志
来源：http://dali.nanxuanxn.top/Article/details/gt2drsqaqje.html

echo "log" >> out.log
来源：http://dali.andypj.xyz/Article/details/gt2sujspiax.html

[R41] 丢弃输出
来源：http://dali.smart0.xyz/Article/details/gt2beynywvl.html

cmd >/dev/null 2>&1
来源：http://dali.yongpay.top/Article/details/gt2riwmryxg.html

[R42] 输入重定向
来源：http://dali.zycfv.cn/Article/details/gt2svduwebz.html

wc -l < a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kwcotfgu.html

[R43] 按名字查找文件
来源：http://dali.jyoumei.cn/Article/details/gt2hmslfhkh.html

find . -name "*.log" -type f
来源：http://dali.yuxming.cn/Article/details/gt2tnrdndqm.html

[R44] 按修改时间查找
来源：http://dali.nanxuanxn.top/Article/details/gt2izmkster.html

find . -mtime -7 -type f
来源：http://dali.316326.xyz/Article/details/gt2nciahoxd.html

[R45] 批量删除
来源：http://dali.xuetiantiany.cn/Article/details/gt2fbsywjht.html


<!-- 参考信息 -->