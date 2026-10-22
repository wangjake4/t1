代发 wailian999

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2jqwymxeh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.tianlin.xyz/Article/details/gt2ojtmkjni.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2uhrhyhfl.html

[Q01] 创建表
来源：http://dali.hnqzz.top/Article/details/gt2dgjrwtbm.html

CREATE TABLE users (
来源：http://dali.tianlin.xyz/Article/details/gt2xzwxhzua.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zbopqpky.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gt2ozxlwjrx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.snrcjt.cn/Article/details/gt2vnnuruhb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xuetiantiany.cn/Article/details/gt2rmxbsypm.html

);
来源：http://dali.kuanghao11.cn/Article/details/gt2qrbmhnxu.html

[Q02] 创建带外键的表
来源：http://dali.gzhubu.top/Article/details/gt2jnaxvckj.html

CREATE TABLE orders (
来源：http://dali.nanxinkj.top/Article/details/gt2eretskgy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sweek.top/Article/details/gt2hfdtipxr.html

user_id INT NOT NULL,
来源：http://dali.meibo888.top/Article/details/gt2hktbvkyb.html

amount DECIMAL(10, 2),
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2btbsdhfo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.bjfxy.top/Article/details/gt2xjgjnuhv.html

);
来源：http://dali.yanxiufei.cn/Article/details/gt2ivqpotsf.html

[Q03] 增加列
来源：http://dali.jinqigfzy.top/Article/details/gt2bhjslvgx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hongshengwenyu.top/Article/details/gt2kqyvtakt.html

[Q04] 修改列类型
来源：http://dali.mhx1999.top/Article/details/gt2hpikpxcs.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tanke756.top/Article/details/gt2gzlqgnrp.html

[Q05] 重命名列
来源：http://dali.sweek.top/Article/details/gt2bfknpqdd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.aizwys.cn/Article/details/gt2ylkfaoir.html

[Q06] 删除列
来源：http://dali.yvedp.cn/Article/details/gt2ykigbsof.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.daria6918.cn/Article/details/gt2kfzgappi.html

[Q07] 删除表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qgmogadp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2qjenzero.html

[Q08] 创建普通索引
来源：http://dali.zhengqikj.top/Article/details/gt2zbrapwvg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guannengcc.top/Article/details/gt2ncjtwfky.html

[Q09] 创建唯一索引
来源：http://dali.nanxinkj.top/Article/details/gt2nnjkdtgd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gt2mbadewhc.html

[Q10] 插入单行
来源：http://dali.9152youxi.cn/Article/details/gt2wxwnspbi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gt2hhzohmml.html

[Q11] 一次插入多行
来源：http://dali.yueranfly.top/Article/details/gt2wezyghhu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj202588.top/Article/details/gt2ptkdkewg.html

[Q12] 插入后取自增 ID
来源：http://dali.gogol.net.cn/Article/details/gt2wohpqgvk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenzaomai.com/Article/details/gt2yxiuucwl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xylfe.cn/Article/details/gt2ckrcbfit.html

[Q13] 忽略重复插入
来源：http://dali.c1oappe.top/Article/details/gt2ysppwwiq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pycfn.com/Article/details/gt2gyiqbsev.html

[Q14] 存在则更新（upsert）
来源：http://dali.hongshengwenyu.top/Article/details/gt2yxgsmcst.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenzaomai.com/Article/details/gt2ztbganbl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gaohongyu789.top/Article/details/gt2xkzrfxgf.html

[Q15] 查询全部
来源：http://dali.zhixingplan.top/Article/details/gt2zframrai.html

SELECT * FROM users;
来源：http://dali.yj202588.top/Article/details/gt2tdwcjqyt.html

[Q16] 查询指定列
来源：http://dali.sxryk.cn/Article/details/gt2vyobmsgl.html

SELECT id, name FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2spltjpcj.html

[Q17] 条件查询
来源：http://dali.gotoacloud.top/Article/details/gt2vjjehyoy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yvedp.cn/Article/details/gt2mseorrjm.html

[Q18] 模糊匹配
来源：http://dali.ybcxt.top/Article/details/gt2xanufwku.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fzhhl.top/Article/details/gt2xwvrivea.html

[Q19] 范围查询
来源：http://dali.sweek.top/Article/details/gt2frfwnxpi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yanxiufei.cn/Article/details/gt2drfqclgj.html

[Q20] IN 列表
来源：http://dali.shangyingyoupin.top/Article/details/gt2brncryou.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2aukfsduu.html

[Q21] 空值判断
来源：http://dali.wangshuangyany.cn/Article/details/gt2hnhtsqic.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gaohongyu789.top/Article/details/gt2brmkpnzo.html

[Q22] 排序
来源：http://dali.hywenlv.cn/Article/details/gt2qugohtpu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.daria6918.cn/Article/details/gt2csarwvkf.html

[Q23] 分页
来源：http://dali.guannengcc.top/Article/details/gt2tdarflld.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yvfismfm.html

[Q24] 去重
来源：http://dali.hnqzz.top/Article/details/gt2vghxyvso.html

SELECT DISTINCT city FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2jypyksym.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangtech.top/Article/details/gt2agoidcag.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cashguo.top/Article/details/gt2csvjlnrf.html

[Q26] 计数
来源：http://dali.birdmap.top/Article/details/gt2vpkzqvqn.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2zpgxofwd.html

[Q27] 条件计数
来源：http://dali.aizwys.cn/Article/details/gt2xalndfbu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2vxteraqn.html

[Q28] 求和与平均
来源：http://dali.ydzc1.top/Article/details/gt2jqmtbjkc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sweek.top/Article/details/gt2kflanrii.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmvzflc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cnusnghk.html

[Q30] 分组统计
来源：http://dali.chenjidiqi.icu/Article/details/gt2ewnaeijx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gt2bpwncixo.html

[Q31] 分组后过滤
来源：http://dali.sysykeji.top/Article/details/gt2onextxxa.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.c1oappe.top/Article/details/gt2tbjzzuie.html

[Q32] 分组拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gt2jrmbvoag.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gt2oubhvoys.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cucudq.cn/Article/details/gt2cdiuuivc.html

[Q33] 多列分组
来源：http://dali.meibo888.top/Article/details/gt2imbgzemx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhengqikj.top/Article/details/gt2wdsvlkct.html

[Q34] 每组取第一条
来源：http://dali.fzhhl.top/Article/details/gt2naqckqke.html

SELECT * FROM (
来源：http://dali.fengsongda.top/Article/details/gt2vbnnkalm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zdqjudy.top/Article/details/gt2lhjsbiul.html

) t WHERE rn = 1;
来源：http://dali.jianghu66.top/Article/details/gt2iaejiuqp.html

[Q35] 内连接
来源：http://dali.sufxvd.cn/Article/details/gt2bmetceur.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gogol.net.cn/Article/details/gt2tznmyqgi.html

[Q36] 左连接
来源：http://dali.hnxiangtu.top/Article/details/gt2dzlyjwao.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gt2lxzmfrva.html

[Q37] 右连接
来源：http://dali.vqdsnc.cn/Article/details/gt2drtixtmo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuxming.cn/Article/details/gt2ikmqvjme.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yuxming.cn/Article/details/gt2mppgaulx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj202588.top/Article/details/gt2poosrxsg.html

[Q39] 自连接（查上下级）
来源：http://dali.vqdsnc.cn/Article/details/gt2yuxiwhmj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhiwuduotai.top/Article/details/gt2nnfobfgq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nanxinkj.top/Article/details/gt2dijyfiso.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.c1oappe.top/Article/details/gt2lglwmyps.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nanxinkj.top/Article/details/gt2zkvnivsc.html

[Q41] 多表连接
来源：http://dali.yueranfly.top/Article/details/gt2zabjyvqn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangdashe.top/Article/details/gt2ilqhuand.html

JOIN users u ON u.id = o.user_id
来源：http://dali.daxiang520.top/Article/details/gt2kvhjlded.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhengqikj.top/Article/details/gt2bvpgipyo.html

[Q42] 连接条件附加过滤
来源：http://dali.cashguo.top/Article/details/gt2obvgejsd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yuxming.cn/Article/details/gt2ejqmfchg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hywenlv.cn/Article/details/gt2xzxgjjhk.html

[Q43] 标量子查询
来源：http://dali.tanke756.top/Article/details/gt2mopehwjk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yonumen.top/Article/details/gt2uwgpsrju.html

[Q44] IN 子查询
来源：http://dali.jinqigufen.top/Article/details/gt2zfeypcur.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ppjwa.cn/Article/details/gt2dxktcacl.html

[Q45] EXISTS 判断存在
来源：http://dali.xziqi.cn/Article/details/gt2pnjcqggd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gt2hgrtxjsk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.bjfxy.top/Article/details/gt2zpfsfyeg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gt2jmtfujgc.html

[Q47] 与平均值比较
来源：http://dali.hfpthk.cn/Article/details/gt2dlvawgwu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shzxlz.cn/Article/details/gt2ilohygtj.html

[Q48] CTE 公用表表达式
来源：http://dali.pycfn.com/Article/details/gt2crippkgg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.birdmap.top/Article/details/gt2aptlszcz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ppnqeead.html

[Q49] 更新单行
来源：http://dali.cqqwz.cn/Article/details/gt2ftzmqkub.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenzaomai.com/Article/details/gt2bbowjwlw.html

[Q50] 批量更新
来源：http://dali.yongpay.top/Article/details/gt2hehzxyqs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.fzhhl.top/Article/details/gt2ezbhymox.html

[Q51] 用子查询更新
来源：http://dali.sweek.top/Article/details/gt2fcsxkfnw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.pycfn.com/Article/details/gt2xjozqgja.html

[Q52] 删除指定行
来源：http://dali.gotoacloud.top/Article/details/gt2cfnvjunr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gt2sfxearbf.html

[Q53] 按条件删除
来源：http://dali.zhengqikj.top/Article/details/gt2qwzdwfob.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cqqwz.cn/Article/details/gt2mqazewbc.html

[Q54] 清空表
来源：http://dali.cucudq.cn/Article/details/gt2cwtlajhi.html

TRUNCATE TABLE logs;
来源：http://dali.nanxinkj.top/Article/details/gt2nalpobew.html

[Q55] 排名（并列占位）
来源：http://dali.yangfankeji.com/Article/details/gt2loilmija.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yongpay.top/Article/details/gt2zhqrpkac.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yuanzhike.top/Article/details/gt2octyftww.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shuidangran.top/Article/details/gt2dzewfyym.html

[Q57] 行号
来源：http://dali.yuxming.cn/Article/details/gt2ystdtyvm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ivvv.top/Article/details/gt2ushmwcju.html

[Q58] 累计求和
来源：http://dali.yueranfly.top/Article/details/gt2csrxcowj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yueranfly.top/Article/details/gt2snkmqowr.html

[Q59] 分组内累计
来源：http://dali.gotoacloud.top/Article/details/gt2bmqbtwpj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gt2vmedxlaw.html

[Q60] 取上一行 / 下一行
来源：http://dali.hammf.cn/Article/details/gt2zucpllax.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnqzz.top/Article/details/gt2nmzqwckz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2yalvlhic.html

[Q61] 移动平均
来源：http://dali.9152youxi.cn/Article/details/gt2ztfkvcxg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gt2ckbrbemb.html

[Q62] 分组占比
来源：http://dali.pycfn.com/Article/details/gt2ivgqfdpx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gt2yatjpyeb.html

[Q63] 开启事务
来源：http://dali.hnxiangtu.top/Article/details/gt2lkwhxyfd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuetiantiany.cn/Article/details/gt2hazmwihs.html

[Q64] 提交事务
来源：http://dali.tanke756.top/Article/details/gt2knxlmufp.html

COMMIT;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bhtgeyhs.html

[Q65] 回滚事务
来源：http://dali.shangyingyoupin.top/Article/details/gt2pfrxwjsg.html

ROLLBACK;
来源：http://dali.andypj.xyz/Article/details/gt2jguldssj.html

[Q66] 行锁查询
来源：http://dali.hywenlv.cn/Article/details/gt2yzfzivny.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.vqdsnc.cn/Article/details/gt2qnjskmmo.html

[Q67] 设置隔离级别
来源：http://dali.cashguo.top/Article/details/gt2jnmpqits.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hammf.cn/Article/details/gt2ngxrxxti.html

[Q68] 保存点
来源：http://dali.shangyingyoupin.top/Article/details/gt2mirtkxzy.html

SAVEPOINT sp1;
来源：http://dali.guannengcc.top/Article/details/gt2jszkwlri.html

ROLLBACK TO sp1;
来源：http://dali.iojbl.cn/Article/details/gt2hxrzdgir.html

[Q69] 查看执行计划
来源：http://dali.jianghu66.top/Article/details/gt2jzoazrkr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.havefunace.top/Article/details/gt2lntloswb.html

[Q70] 更新统计信息
来源：http://dali.sysykeji.top/Article/details/gt2qrwugddx.html

ANALYZE TABLE users;
来源：http://dali.yvedp.cn/Article/details/gt2ypiajcwv.html

[Q71] 查看建表语句
来源：http://dali.bjfxy.top/Article/details/gt2jkvmnzgr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgfzy.top/Article/details/gt2hfeyehny.html

[Q72] 查看索引
来源：http://dali.zhixingplan.top/Article/details/gt2wnbkvyas.html

SHOW INDEX FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2bvzeeghe.html

[Q73] 查看表状态
来源：http://dali.ivvv.top/Article/details/gt2gnogqrkq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gaohongyu789.top/Article/details/gt2lwfuridv.html

[Q74] 强制使用索引
来源：http://dali.iojbl.cn/Article/details/gt2tvdnrhit.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yangfankeji.com/Article/details/gt2srmbhtve.html

[Q75] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gt2oknplrdg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pfclymvz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hongshengwenyu.top/Article/details/gt2zhvcyidz.html

[Q76] 按天统计
来源：http://dali.hfpthk.cn/Article/details/gt2keeiszcr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hysaishi.cn/Article/details/gt2usojhsqf.html

[Q77] 时间加减
来源：http://dali.fzhhl.top/Article/details/gt2warjsskr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.quarkkingdee.top/Article/details/gt2bbeisnib.html

[Q78] 当前时间
来源：http://dali.tianlin.xyz/Article/details/gt2krvnmspk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.quarkkingdee.top/Article/details/gt2uhbwwpog.html

[Q79] 字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gt2leoskxfr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.dianchejie.cn/Article/details/gt2gdwvmzxc.html

[Q80] 字符串截取
来源：http://dali.pycfn.com/Article/details/gt2tybxpvte.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2wvllzivu.html

[Q81] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gt2cyvtrgai.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2zeopbnus.html

[Q82] 字符长度与字节长度
来源：http://dali.yvedp.cn/Article/details/gt2wrrhmfrm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2atthfdfk.html

[Q83] 大小写转换
来源：http://dali.gogol.net.cn/Article/details/gt2ncttegna.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2tpaevwoh.html

[Q84] 去除首尾空格
来源：http://dali.iojbl.cn/Article/details/gt2lfrbpyln.html

SELECT TRIM(name) FROM users;
来源：http://dali.sweek.top/Article/details/gt2wdtjjgjv.html

[Q85] 数值取整
来源：http://dali.cucudq.cn/Article/details/gt2ouzsonew.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tian-w.cn/Article/details/gt2yoprndqe.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigufen.top/Article/details/gt2lgkdffxp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.316326.xyz/Article/details/gt2ylhyzdeo.html

[Q87] JSON 字段做条件
来源：http://dali.hammf.cn/Article/details/gt2sctojqgi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gogol.net.cn/Article/details/gt2msxmlrwz.html

[Q88] 行转列（条件聚合）
来源：http://dali.9152youxi.cn/Article/details/gt2uxznhtlt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shzxlz.cn/Article/details/gt2vmchhwgu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2qqstonux.html

[Q89] 判断表是否存在
来源：http://dali.zhengqikj.top/Article/details/gt2abvrymsg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.fengsongda.top/Article/details/gt2nhvkdrci.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrzhjae.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhixingplan.top/Article/details/gt2beubmhky.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2pcuyqlue.html

R. Bash 专题
来源：http://dali.gogol.net.cn/Article/details/gt2srukgeto.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2pdnhzmgr.html

[R01] shebang 与严格模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2knoyukjl.html

#!/usr/bin/env bash
来源：http://dali.xinyue.icu/Article/details/gt2mswdiegr.html

set -euo pipefail
来源：http://dali.ivvv.top/Article/details/gt2ycklqhaa.html

[R02] 变量赋值与使用
来源：http://dali.daxiang520.top/Article/details/gt2auwnqxlk.html

name="Tom"; echo "$name"
来源：http://dali.ybcxt.top/Article/details/gt2bzmyqbir.html

[R03] 只读变量
来源：http://dali.aizwys.cn/Article/details/gt2eopybyzz.html

readonly PI=3.14
来源：http://dali.shzxlz.cn/Article/details/gt2zfpmdazw.html

[R04] 位置参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2zxbgciae.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258888.top/Article/details/gt2sooqiroi.html

[R05] 参数默认值
来源：http://dali.gogol.net.cn/Article/details/gt2hryxkmzy.html

name="${1:-default}"
来源：http://dali.yvedp.cn/Article/details/gt2ffcijbjz.html

[R06] 判断命令是否存在
来源：http://dali.sxryk.cn/Article/details/gt2paongtdo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nwbrower.top/Article/details/gt2nfxhslxm.html

[R07] if 判断文件
来源：http://dali.yj202588.top/Article/details/gt2uqrcvmao.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgufenzy.top/Article/details/gt2xxuyssxu.html

[R08] 数值比较
来源：http://dali.mhx1999.top/Article/details/gt2yxhxkeox.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sufxvd.cn/Article/details/gt2ziuerweg.html

[R09] 字符串比较
来源：http://dali.jiagoushi.top/Article/details/gt2pyqubbfi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.snrcjt.cn/Article/details/gt2prgseeee.html

[R10] 正则匹配
来源：http://dali.zhixingplan.top/Article/details/gt2biuypvjd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xziqi.cn/Article/details/gt2qrmfumyf.html

[R11] case 多分支
来源：http://dali.nwbrower.top/Article/details/gt2fwzzkffr.html

case "$1" in
来源：http://dali.chenzaomai.com/Article/details/gt2nuiknlpn.html

start) echo "启动" ;;
来源：http://dali.bjfxy.top/Article/details/gt2lnhjxbyz.html

stop)  echo "停止" ;;
来源：http://dali.xziqi.cn/Article/details/gt2xkznspms.html

*)     echo "未知命令" ;;
来源：http://dali.daxiang520.top/Article/details/gt2fyynponn.html

esac
来源：http://dali.316326.xyz/Article/details/gt2wkxmcede.html

[R12] for 遍历文件
来源：http://dali.c1oappe.top/Article/details/gt2kkckllik.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yangfankeji.com/Article/details/gt2lftgjeuz.html

[R13] for 计数循环
来源：http://dali.9152youxi.cn/Article/details/gt2gwphklao.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gt2cchdnkmv.html

[R14] C 风格 for
来源：http://dali.ivvv.top/Article/details/gt2ppzqiqsp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gt2tzvnptas.html

[R15] while 逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2kaoaditd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenlongwang.top/Article/details/gt2uuoimtrm.html

[R16] until 等待条件
来源：http://dali.gzhubu.top/Article/details/gt2gmtfajky.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zycfv.cn/Article/details/gt2sulsijjr.html

[R17] 数组定义与取值
来源：http://dali.zdqjudy.top/Article/details/gt2cqktnpuy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2kzyrtfde.html

[R18] 遍历数组
来源：http://dali.zycfv.cn/Article/details/gt2tyaimvwv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tian-w.cn/Article/details/gt2difklcwo.html

[R19] 数组长度
来源：http://dali.cheryme.top/Article/details/gt2wrmlkdst.html

echo "${#arr[@]}"
来源：http://dali.jinqigufen.top/Article/details/gt2ovcgldhk.html

[R20] 关联数组（字典）
来源：http://dali.zhengqikj.top/Article/details/gt2vbvkpcgo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.316326.xyz/Article/details/gt2necissaq.html

[R21] 字符串长度
来源：http://dali.shangyingyoupin.top/Article/details/gt2kwzqgozu.html

echo "${#s}"
来源：http://dali.redwolf501.top/Article/details/gt2ueytviet.html

[R22] 截取子串
来源：http://dali.xuetiantiany.cn/Article/details/gt2kkwxlmka.html

echo "${s:0:5}"
来源：http://dali.wangdashe.top/Article/details/gt2jgytuprd.html

[R23] 字符串替换
来源：http://dali.yj202588.top/Article/details/gt2vpqirebu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hywenlv.cn/Article/details/gt2srvficgr.html

[R24] 大小写转换
来源：http://dali.xziqi.cn/Article/details/gt2uhztjkrx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guowangkeji.top/Article/details/gt2uiubooki.html

[R25] 去后缀 / 去前缀
来源：http://dali.smart0.xyz/Article/details/gt2goidctel.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.snrcjt.cn/Article/details/gt2tnrbzmni.html

[R26] 命令替换
来源：http://dali.snrcjt.cn/Article/details/gt2atzwfosz.html

now=$(date +%F); echo "$now"
来源：http://dali.yangfankeji.com/Article/details/gt2xbgdixjr.html

[R27] 算术展开
来源：http://dali.dianchejie.cn/Article/details/gt2ppqmffsr.html

echo $((1 + 2 * 3))
来源：http://dali.yonumen.top/Article/details/gt2xlossvzh.html

[R28] 浮点运算
来源：http://dali.hysaishi.cn/Article/details/gt2odtnindk.html

echo "scale=2; 10/3" | bc
来源：http://dali.sysykeji.top/Article/details/gt2ryeehayn.html

[R29] 定义函数
来源：http://dali.shuidangran.top/Article/details/gt2ppqorzus.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj202588.top/Article/details/gt2xrctghty.html

[R30] 函数返回状态码
来源：http://dali.316326.xyz/Article/details/gt2whilcfqn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj202588.top/Article/details/gt2ukhjmsqm.html

[R31] 局部变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lelxcubq.html

f() { local x=1; echo "$x"; }
来源：http://dali.sysykeji.top/Article/details/gt2jwwvxfma.html

[R32] 参数个数校验
来源：http://dali.vqdsnc.cn/Article/details/gt2iedehxan.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gt2rpqphwtf.html

[R33] 捕获错误并提示行号
来源：http://dali.meibo888.top/Article/details/gt2hikfbcap.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.aibaodan.cn/Article/details/gt2lbvpsylg.html

[R34] 退出时清理
来源：http://dali.nanxinkj.top/Article/details/gt2kkykvvee.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cashguo.top/Article/details/gt2hmbiwrly.html

[R35] 后台执行并等待
来源：http://dali.jlsjyb.cn/Article/details/gt2pruythtq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tian-w.cn/Article/details/gt2kjfejiir.html

[R36] 并发执行多个任务
来源：http://dali.zhengqikj.top/Article/details/gt2updsanyn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shangyingyoupin.top/Article/details/gt2uctyvwwu.html

[R37] 把输出赋给变量
来源：http://dali.vqdsnc.cn/Article/details/gt2avbovmfn.html

files=$(ls -1)
来源：http://dali.zycfv.cn/Article/details/gt2asglfwvf.html

[R38] 管道串联
来源：http://dali.hnqzz.top/Article/details/gt2rpoetvtp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nwbrower.top/Article/details/gt2oamfsxng.html

[R39] 重定向标准输出与错误
来源：http://dali.andypj.xyz/Article/details/gt2ddywxzkg.html

cmd > out.log 2>&1
来源：http://dali.hnqzz.top/Article/details/gt2aoelcmoo.html

[R40] 追加写日志
来源：http://dali.bjfxy.top/Article/details/gt2nbpxwcfd.html

echo "log" >> out.log
来源：http://dali.sufxvd.cn/Article/details/gt2ypmrdfsp.html

[R41] 丢弃输出
来源：http://dali.tanke756.top/Article/details/gt2cirsutcz.html

cmd >/dev/null 2>&1
来源：http://dali.cashguo.top/Article/details/gt2yhntjche.html

[R42] 输入重定向
来源：http://dali.jyoumei.cn/Article/details/gt2euzxobpx.html

wc -l < a.txt
来源：http://dali.yuxming.cn/Article/details/gt2mwenqhcn.html

[R43] 按名字查找文件
来源：http://dali.ydzc1.top/Article/details/gt2gddqtdux.html


<!-- 参考信息 -->