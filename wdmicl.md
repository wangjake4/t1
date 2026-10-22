代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yuxming.cn/Article/details/gt2bjpvxomz.html

);
来源：http://dali.zhongyouzk.top/Article/details/gt2abwpfdjp.html

[Q02] 创建带外键的表
来源：http://dali.andypj.xyz/Article/details/gt2xtjmaxhk.html

CREATE TABLE orders (
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pgotxcgw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ydzc1.top/Article/details/gt2lygmxqow.html

user_id INT NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gt2gbkydrqk.html

amount DECIMAL(10, 2),
来源：http://dali.ivvv.top/Article/details/gt2dmxrnnwf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cqqwz.cn/Article/details/gt2ksmhybpl.html

);
来源：http://dali.ppjwa.cn/Article/details/gt2yzzoqdyy.html

[Q03] 增加列
来源：http://dali.hnqzz.top/Article/details/gt2esxofevq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.smart0.xyz/Article/details/gt2fafpntwc.html

[Q04] 修改列类型
来源：http://dali.hfpthk.cn/Article/details/gt2phumaiyv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258.top/Article/details/gt2piexwgoz.html

[Q05] 重命名列
来源：http://dali.zhongyouzk.top/Article/details/gt2vrkzidtx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.snrcjt.cn/Article/details/gt2ymtmwlhu.html

[Q06] 删除列
来源：http://dali.ydzc1.top/Article/details/gt2dtdhlgwf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gzhubu.top/Article/details/gt2pvbnozgu.html

[Q07] 删除表
来源：http://dali.zhiwuduotai.top/Article/details/gt2xctsrlxx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj202588.top/Article/details/gt2bszxdflw.html

[Q08] 创建普通索引
来源：http://dali.redwolf501.top/Article/details/gt2vjizdqro.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2caufuzdj.html

[Q09] 创建唯一索引
来源：http://dali.vqdsnc.cn/Article/details/gt2tyncaitc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenzaomai.com/Article/details/gt2sxpnvszv.html

[Q10] 插入单行
来源：http://dali.haohaochexian.top/Article/details/gt2xkakrstu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.bjfxy.top/Article/details/gt2cnsxvopy.html

[Q11] 一次插入多行
来源：http://dali.hnqzz.top/Article/details/gt2zbdiwxjy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dashuyun.cn/Article/details/gt2nzykenmm.html

[Q12] 插入后取自增 ID
来源：http://dali.feifeiyinyue.top/Article/details/gt2vrvpbwze.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sysykeji.top/Article/details/gt2dytmsfmr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gaohongyu789.top/Article/details/gt2yhhiquso.html

[Q13] 忽略重复插入
来源：http://dali.jinqigufen.top/Article/details/gt2kjbvkdnn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zdqjudy.top/Article/details/gt2alkpbmnc.html

[Q14] 存在则更新（upsert）
来源：http://dali.daxiang520.top/Article/details/gt2hwbcjzxm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.snrcjt.cn/Article/details/gt2sbbxlfec.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.smart0.xyz/Article/details/gt2dbvgwftk.html

[Q15] 查询全部
来源：http://dali.yj202588.top/Article/details/gt2teshhmuc.html

SELECT * FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2mbwtqnir.html

[Q16] 查询指定列
来源：http://dali.0kj1m.cn/Article/details/gt2chvlixea.html

SELECT id, name FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2wbgsnqjv.html

[Q17] 条件查询
来源：http://dali.zhongyouzk.top/Article/details/gt2cyilfsmw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tianlin.xyz/Article/details/gt2ntfdngug.html

[Q18] 模糊匹配
来源：http://dali.cashguo.top/Article/details/gt2lpqxidlg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shangyingyoupin.top/Article/details/gt2axhxhqii.html

[Q19] 范围查询
来源：http://dali.fzhhl.top/Article/details/gt2yszyfplb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ybcxt.top/Article/details/gt2nuuusjse.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lokduixm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zdqjudy.top/Article/details/gt2emekiimg.html

[Q21] 空值判断
来源：http://dali.hongshengwenyu.top/Article/details/gt2ghwcacpj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jlsjyb.cn/Article/details/gt2kpvqmeru.html

[Q22] 排序
来源：http://dali.smart0.xyz/Article/details/gt2jmpdugtq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gaohongyu789.top/Article/details/gt2raeghrmp.html

[Q23] 分页
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hsabulyh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nwbrower.top/Article/details/gt2nvcqhwny.html

[Q24] 去重
来源：http://dali.jianghu66.top/Article/details/gt2givyvudr.html

SELECT DISTINCT city FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iensjsnj.html

[Q25] 只取前 N 条
来源：http://dali.haohaochexian.top/Article/details/gt2rlcjiuom.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gogol.net.cn/Article/details/gt2jwhpemlq.html

[Q26] 计数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pzvilshz.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2mpmhrafo.html

[Q27] 条件计数
来源：http://dali.tianlin.xyz/Article/details/gt2dqrwefff.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2byjnlurd.html

[Q28] 求和与平均
来源：http://dali.9152youxi.cn/Article/details/gt2xkldrsde.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gt2vuyafngy.html

[Q29] 最大最小值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ionbqizg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.birdmap.top/Article/details/gt2cinvtxvp.html

[Q30] 分组统计
来源：http://dali.redwolf501.top/Article/details/gt2nysikyfa.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gt2taeqscmr.html

[Q31] 分组后过滤
来源：http://dali.quarkkingdee.top/Article/details/gt2ianntpne.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jiagoushi.top/Article/details/gt2sjhpbxym.html

[Q32] 分组拼接字符串
来源：http://dali.yongpay.top/Article/details/gt2tuxdesej.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gt2lgidvodm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cdnleiting.top/Article/details/gt2lztzqhtp.html

[Q33] 多列分组
来源：http://dali.nwbrower.top/Article/details/gt2gxmvnejv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hammf.cn/Article/details/gt2yvbyuszv.html

[Q34] 每组取第一条
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2anskyxhv.html

SELECT * FROM (
来源：http://dali.daxiang520.top/Article/details/gt2djzjtzhh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fengsongda.top/Article/details/gt2ucauwmxj.html

) t WHERE rn = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2qrjxzfly.html

[Q35] 内连接
来源：http://dali.chenjidiqi.icu/Article/details/gt2ggrbebxm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gt2bdvwmylv.html

[Q36] 左连接
来源：http://dali.smart0.xyz/Article/details/gt2fijawkxp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yvedp.cn/Article/details/gt2eqkvivkq.html

[Q37] 右连接
来源：http://dali.c1oappe.top/Article/details/gt2evrbkaox.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigfzy.top/Article/details/gt2yzxnzkrq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.feifeiyinyue.top/Article/details/gt2zdxiozos.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daxiang520.top/Article/details/gt2zqnojihq.html

[Q39] 自连接（查上下级）
来源：http://dali.guowangkeji.top/Article/details/gt2mwvwwihl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tianlin.xyz/Article/details/gt2ogkjdanu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xziqi.cn/Article/details/gt2odpsioat.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenjidiqi.icu/Article/details/gt2hmkxrqyv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.bjfxy.top/Article/details/gt2aekyecgl.html

[Q41] 多表连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tjuuehvd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zycfv.cn/Article/details/gt2vhyrovun.html

JOIN users u ON u.id = o.user_id
来源：http://dali.c1oappe.top/Article/details/gt2ciylnbqa.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhengqikj.top/Article/details/gt2nhybjwfj.html

[Q42] 连接条件附加过滤
来源：http://dali.zhixingplan.top/Article/details/gt2olvavmny.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jianghu66.top/Article/details/gt2mmjwdlwu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.svipenyu.cn/Article/details/gt2ogdlyvun.html

[Q43] 标量子查询
来源：http://dali.jqgfzy.top/Article/details/gt2eejrvswo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.birdmap.top/Article/details/gt2syxkcooz.html

[Q44] IN 子查询
来源：http://dali.sufxvd.cn/Article/details/gt2uijticzh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.dianchejie.cn/Article/details/gt2jlcnizpk.html

[Q45] EXISTS 判断存在
来源：http://dali.chenzaomai.com/Article/details/gt2czxgbdfa.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.c1oappe.top/Article/details/gt2ulfgyakj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgfzy.top/Article/details/gt2ekvxjeoc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gt2cvnepini.html

[Q47] 与平均值比较
来源：http://dali.xziqi.cn/Article/details/gt2ugrfdfcc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hfpthk.cn/Article/details/gt2ylbypvhm.html

[Q48] CTE 公用表表达式
来源：http://dali.guowangkeji.top/Article/details/gt2jhmyjlwr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pkdkpqun.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.kuanghao11.cn/Article/details/gt2evascftr.html

[Q49] 更新单行
来源：http://dali.aibaodan.cn/Article/details/gt2ehsxbkvz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cqqwz.cn/Article/details/gt2naovzcbr.html

[Q50] 批量更新
来源：http://dali.fzhhl.top/Article/details/gt2dpiptdlx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xuanzx.com/Article/details/gt2hmtjkxrb.html

[Q51] 用子查询更新
来源：http://dali.nanxuanxn.top/Article/details/gt2brmbxcem.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.dianchejie.cn/Article/details/gt2cplpcvkn.html

[Q52] 删除指定行
来源：http://dali.xylfe.cn/Article/details/gt2halkxcej.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cucudq.cn/Article/details/gt2xzkuunjy.html

[Q53] 按条件删除
来源：http://dali.ivvv.top/Article/details/gt2rhykonkg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hfpthk.cn/Article/details/gt2kkeyxine.html

[Q54] 清空表
来源：http://dali.zhengqikj.top/Article/details/gt2hpwugygg.html

TRUNCATE TABLE logs;
来源：http://dali.yueranfly.top/Article/details/gt2thufzhfl.html

[Q55] 排名（并列占位）
来源：http://dali.birdmap.top/Article/details/gt2rsojgppn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.wangdashe.top/Article/details/gt2lokvplsv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigufen.top/Article/details/gt2lgdmntwy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gt2bboouzvt.html

[Q57] 行号
来源：http://dali.guannengcc.top/Article/details/gt2zutzklzr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fjnqqssb.html

[Q58] 累计求和
来源：http://dali.gotoacloud.top/Article/details/gt2sqkkgocm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hnqzz.top/Article/details/gt2fajfzvus.html

[Q59] 分组内累计
来源：http://dali.xinyue.icu/Article/details/gt2boriohez.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gt2yiguvyzx.html

[Q60] 取上一行 / 下一行
来源：http://dali.gaohongyu789.top/Article/details/gt2wmrkvhhl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nwbrower.top/Article/details/gt2tvkolmzt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gt2ukrtgnyg.html

[Q61] 移动平均
来源：http://dali.zhixingplan.top/Article/details/gt2efjcgvtt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2tlopknxl.html

[Q62] 分组占比
来源：http://dali.dianchejie.cn/Article/details/gt2wdtvoybl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gt2mktyerfi.html

[Q63] 开启事务
来源：http://dali.ydzc1.top/Article/details/gt2azzhftov.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cucudq.cn/Article/details/gt2ffblpegc.html

[Q64] 提交事务
来源：http://dali.fzhhl.top/Article/details/gt2clcditmt.html

COMMIT;
来源：http://dali.vqdsnc.cn/Article/details/gt2leamumto.html

[Q65] 回滚事务
来源：http://dali.jyoumei.cn/Article/details/gt2qjemgugb.html

ROLLBACK;
来源：http://dali.cucudq.cn/Article/details/gt2fdtwvbhn.html

[Q66] 行锁查询
来源：http://dali.andypj.xyz/Article/details/gt2amlftaoj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xinyue.icu/Article/details/gt2hvfwlohr.html

[Q67] 设置隔离级别
来源：http://dali.svipenyu.cn/Article/details/gt2tijowdxt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yongpay.top/Article/details/gt2czlmaynp.html

[Q68] 保存点
来源：http://dali.hysaishi.cn/Article/details/gt2plogdrht.html

SAVEPOINT sp1;
来源：http://dali.zdqjudy.top/Article/details/gt2dspbtvvb.html

ROLLBACK TO sp1;
来源：http://dali.zhengqikj.top/Article/details/gt2ruzdveml.html

[Q69] 查看执行计划
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wxxjyxjr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yanxiufei.cn/Article/details/gt2mzkmdggi.html

[Q70] 更新统计信息
来源：http://dali.jqgfzy.top/Article/details/gt2syfwexeq.html

ANALYZE TABLE users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2paiudehz.html

[Q71] 查看建表语句
来源：http://dali.chenzaomai.com/Article/details/gt2nxvvwlfp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ehwqpu.com/Article/details/gt2boqpuybc.html

[Q72] 查看索引
来源：http://dali.ivvv.top/Article/details/gt2yirtuoik.html

SHOW INDEX FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2aqsxrakw.html

[Q73] 查看表状态
来源：http://dali.sxryk.cn/Article/details/gt2wkitcrnz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lajxgkik.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gt2zmcxfbnt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.feifeiyinyue.top/Article/details/gt2pbjvrjje.html

[Q75] 日期格式化
来源：http://dali.jinqigufen.top/Article/details/gt2uxephptw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.c1oappe.top/Article/details/gt2hrxbjtgp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shzxlz.cn/Article/details/gt2luuikhwa.html

[Q76] 按天统计
来源：http://dali.hammf.cn/Article/details/gt2aamnzjyd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cqqwz.cn/Article/details/gt2zxjcgtem.html

[Q77] 时间加减
来源：http://dali.0kj1m.cn/Article/details/gt2qkdjopzb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sufxvd.cn/Article/details/gt2udwkmpvz.html

[Q78] 当前时间
来源：http://dali.dashuyun.cn/Article/details/gt2covuygej.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hysaishi.cn/Article/details/gt2zttvbogd.html

[Q79] 字符串拼接
来源：http://dali.ivvv.top/Article/details/gt2fjvicpcc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj20258.top/Article/details/gt2sozbwcds.html

[Q80] 字符串截取
来源：http://dali.yuanzhike.top/Article/details/gt2dedpqhbl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ltmlinfc.html

[Q81] 字符串替换
来源：http://dali.wangdashe.top/Article/details/gt2bipiuhsy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2unxmjzgn.html

[Q82] 字符长度与字节长度
来源：http://dali.yj20258.top/Article/details/gt2vixhnant.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2bugkyphg.html

[Q83] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gt2xtslimkj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2xcibduua.html

[Q84] 去除首尾空格
来源：http://dali.yongpay.top/Article/details/gt2jcoqmtzv.html

SELECT TRIM(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2mrunlrrq.html

[Q85] 数值取整
来源：http://dali.aibaodan.cn/Article/details/gt2yavxgnxe.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lqycqgos.html

[Q86] 读取 JSON 字段
来源：http://dali.zhiwuduotai.top/Article/details/gt2zcqbsury.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhiwuduotai.top/Article/details/gt2uvpsisug.html

[Q87] JSON 字段做条件
来源：http://dali.dashuyun.cn/Article/details/gt2fykuevdh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hongshengwenyu.top/Article/details/gt2zkvhtsak.html

[Q88] 行转列（条件聚合）
来源：http://dali.ydzc1.top/Article/details/gt2btyrkdwh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guannengcc.top/Article/details/gt2famsiwlx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2ruiuijvg.html

[Q89] 判断表是否存在
来源：http://dali.gotoacloud.top/Article/details/gt2ldcoesmw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vijbpynq.html

[Q90] 生成序号列
来源：http://dali.hysaishi.cn/Article/details/gt2uibbpqdf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpfzhtd.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2syyxkphi.html

R. Bash 专题
来源：http://dali.fengsongda.top/Article/details/gt2brduktcc.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2rvzburiv.html

[R01] shebang 与严格模式
来源：http://dali.hfpthk.cn/Article/details/gt2lebtujel.html

#!/usr/bin/env bash
来源：http://dali.yonumen.top/Article/details/gt2djgisupf.html

set -euo pipefail
来源：http://dali.snrcjt.cn/Article/details/gt2matpwcoj.html

[R02] 变量赋值与使用
来源：http://dali.dashuyun.cn/Article/details/gt2eofyitnd.html

name="Tom"; echo "$name"
来源：http://dali.aibaodan.cn/Article/details/gt2lnqrqjlc.html

[R03] 只读变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pisipofv.html

readonly PI=3.14
来源：http://dali.cashguo.top/Article/details/gt2ekugtejn.html

[R04] 位置参数
来源：http://dali.dianchejie.cn/Article/details/gt2nnxsyjfo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhengqikj.top/Article/details/gt2kpcpstur.html

[R05] 参数默认值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wxfzikag.html

name="${1:-default}"
来源：http://dali.nanxinkj.top/Article/details/gt2dfivwerp.html

[R06] 判断命令是否存在
来源：http://dali.havefunace.top/Article/details/gt2nigilsex.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgfzy.top/Article/details/gt2bienjlei.html

[R07] if 判断文件
来源：http://dali.gogol.net.cn/Article/details/gt2wgkwlxwy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gt2yfeuirfz.html

[R08] 数值比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2xqospkyp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhoulong.xyz/Article/details/gt2svskadgx.html

[R09] 字符串比较
来源：http://dali.tanke756.top/Article/details/gt2didzbunk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yanxiufei.cn/Article/details/gt2ypvaakzc.html

[R10] 正则匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2mgmtdheq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2waxzuweh.html

[R11] case 多分支
来源：http://dali.chenjidiqi.icu/Article/details/gt2soproigq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2fukbujod.html

start) echo "启动" ;;
来源：http://dali.yonumen.top/Article/details/gt2rzieqrkm.html

stop)  echo "停止" ;;
来源：http://dali.zhoulong.xyz/Article/details/gt2lidzqxwj.html

*)     echo "未知命令" ;;
来源：http://dali.hysaishi.cn/Article/details/gt2ubxyuujn.html

esac
来源：http://dali.hammf.cn/Article/details/gt2mtnaulfd.html

[R12] for 遍历文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2fngkspnn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nwbrower.top/Article/details/gt2pjaeftje.html

[R13] for 计数循环
来源：http://dali.nwbrower.top/Article/details/gt2svtrtdxf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hnxiangtu.top/Article/details/gt2jrjathrw.html

[R14] C 风格 for
来源：http://dali.guannengcc.top/Article/details/gt2hgtxbqvq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.havefunace.top/Article/details/gt2uqlnlfah.html

[R15] while 逐行读文件
来源：http://dali.xinyue.icu/Article/details/gt2gknqkbnp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gotoacloud.top/Article/details/gt2oejzxshb.html

[R16] until 等待条件
来源：http://dali.redwolf501.top/Article/details/gt2jiezzxwf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gt2ibdluuwi.html

[R17] 数组定义与取值
来源：http://dali.cucudq.cn/Article/details/gt2piwsupqx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izpbikds.html

[R18] 遍历数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2alivoybr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jiagoushi.top/Article/details/gt2njpugeke.html

[R19] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gt2qzvcmoio.html

echo "${#arr[@]}"
来源：http://dali.cheryme.top/Article/details/gt2culdedbs.html

[R20] 关联数组（字典）
来源：http://dali.svipenyu.cn/Article/details/gt2xgtzgaiv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.aibaodan.cn/Article/details/gt2fvtqqpbz.html

[R21] 字符串长度
来源：http://dali.gzhubu.top/Article/details/gt2kfpiifiz.html

echo "${#s}"
来源：http://dali.ydzc1.top/Article/details/gt2hwosohri.html

[R22] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gt2bylkgpvk.html

echo "${s:0:5}"
来源：http://dali.zdqjudy.top/Article/details/gt2wyeuiiwn.html

[R23] 字符串替换
来源：http://dali.cqqwz.cn/Article/details/gt2ccuojjlh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.kuanghao11.cn/Article/details/gt2aopluemp.html

[R24] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gt2irwkeuex.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cqqwz.cn/Article/details/gt2ynmiidbz.html

[R25] 去后缀 / 去前缀
来源：http://dali.snrcjt.cn/Article/details/gt2mymxlsau.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.quarkkingdee.top/Article/details/gt2dfhgoctk.html

[R26] 命令替换
来源：http://dali.jinqigufen.top/Article/details/gt2ovjqfxmm.html

now=$(date +%F); echo "$now"
来源：http://dali.pengpengdd.cyou/Article/details/gt2jjibfadl.html

[R27] 算术展开
来源：http://dali.svipenyu.cn/Article/details/gt2lsqtytam.html

echo $((1 + 2 * 3))
来源：http://dali.feifeiyinyue.top/Article/details/gt2wwrxftij.html

[R28] 浮点运算
来源：http://dali.yvedp.cn/Article/details/gt2iaftzxem.html

echo "scale=2; 10/3" | bc
来源：http://dali.nanxuanxn.top/Article/details/gt2dpaytfup.html

[R29] 定义函数
来源：http://dali.wangdashe.top/Article/details/gt2odznajzc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.andypj.xyz/Article/details/gt2rjfrfhnn.html

[R30] 函数返回状态码
来源：http://dali.chenjidiqi.icu/Article/details/gt2yxdtrudv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shzxlz.cn/Article/details/gt2yzcgjuuh.html

[R31] 局部变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2epthxpij.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuanzhike.top/Article/details/gt2askzrdbj.html

[R32] 参数个数校验
来源：http://dali.xylfe.cn/Article/details/gt2yftzlofv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gt2kfdqojzj.html

[R33] 捕获错误并提示行号
来源：http://dali.meibo888.top/Article/details/gt2cqvwzefk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nanxuanxn.top/Article/details/gt2oqvppfbw.html

[R34] 退出时清理
来源：http://dali.yongpay.top/Article/details/gt2ifwqulos.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhdbict.html

[R35] 后台执行并等待
来源：http://dali.xuanzx.com/Article/details/gt2zghhlslp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangdashe.top/Article/details/gt2qpydeolj.html

[R36] 并发执行多个任务
来源：http://dali.xylfe.cn/Article/details/gt2ghviknkk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yangfankeji.com/Article/details/gt2myljygod.html

[R37] 把输出赋给变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2huzhaapd.html

files=$(ls -1)
来源：http://dali.hnxiangtu.top/Article/details/gt2kzyrzulm.html

[R38] 管道串联
来源：http://dali.yueranfly.top/Article/details/gt2crycjzpq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gdstrdsn.html

[R39] 重定向标准输出与错误
来源：http://dali.vqdsnc.cn/Article/details/gt2virmbtrc.html

cmd > out.log 2>&1
来源：http://dali.snrcjt.cn/Article/details/gt2pkpabugy.html

[R40] 追加写日志
来源：http://dali.yonumen.top/Article/details/gt2yogelmzd.html

echo "log" >> out.log
来源：http://dali.yongpay.top/Article/details/gt2vfkiubod.html

[R41] 丢弃输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dmasdhgb.html

cmd >/dev/null 2>&1
来源：http://dali.chenzaomai.com/Article/details/gt2dnqdgxzv.html

[R42] 输入重定向
来源：http://dali.hfpthk.cn/Article/details/gt2raphxceh.html

wc -l < a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2udezjwyw.html

[R43] 按名字查找文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xcqpjuhw.html

find . -name "*.log" -type f
来源：http://dali.hywenlv.cn/Article/details/gt2lbujtxyc.html

[R44] 按修改时间查找
来源：http://dali.haohaochexian.top/Article/details/gt2enrhhbxm.html

find . -mtime -7 -type f
来源：http://dali.cashguo.top/Article/details/gt2utlfdenw.html

[R45] 批量删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zlnypxqn.html

find . -name "*.tmp" -delete
来源：http://dali.sxryk.cn/Article/details/gt2pwtqyhya.html

[R46] 递归替换文件内容
来源：http://dali.jqgfzy.top/Article/details/gt2mpplielc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.quarkkingdee.top/Article/details/gt2xcagfpny.html

[R47] sed 单行替换
来源：http://dali.9152youxi.cn/Article/details/gt2kaxiiute.html


<!-- 参考信息 -->