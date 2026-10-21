代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.316326.xyz/Article/details/gtryulqqhi.html

);
来源：http://dali.jinqigfzy.top/Article/details/gtywvxguqa.html

[Q02] 创建带外键的表
来源：http://dali.ppjwa.cn/Article/details/gtnzbyxsez.html

CREATE TABLE orders (
来源：http://dali.redwolf501.top/Article/details/gtgyzugnsc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sweek.top/Article/details/gtiesenfxo.html

user_id INT NOT NULL,
来源：http://dali.yonumen.top/Article/details/gtbbexncxk.html

amount DECIMAL(10, 2),
来源：http://dali.chenlongwang.top/Article/details/gtcawkudkh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenzaomai.com/Article/details/gttgefeebm.html

);
来源：http://dali.hnxiangtu.top/Article/details/gtdnxuvdjk.html

[Q03] 增加列
来源：http://dali.yonumen.top/Article/details/gtbudnjbnr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xinyue.icu/Article/details/gtxhamkzqu.html

[Q04] 修改列类型
来源：http://dali.tian-w.cn/Article/details/gtfmcjyshq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.birdmap.top/Article/details/gtbjlwgoxe.html

[Q05] 重命名列
来源：http://dali.sweek.top/Article/details/gtflkfcatd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shzxlz.cn/Article/details/gtnpmbwamu.html

[Q06] 删除列
来源：http://dali.andypj.xyz/Article/details/gtkugahykf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.birdmap.top/Article/details/gtqkmpqdnt.html

[Q07] 删除表
来源：http://dali.aizwys.cn/Article/details/gttzwlggjj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtpifonydr.html

[Q08] 创建普通索引
来源：http://dali.tianlin.xyz/Article/details/gtkofuudvn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gtulfqysqd.html

[Q09] 创建唯一索引
来源：http://dali.hongshengwenyu.top/Article/details/gtycrrfuvm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tian-w.cn/Article/details/gtnkuvugvg.html

[Q10] 插入单行
来源：http://dali.cheryme.top/Article/details/gtfixlcriu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gtyfvrrgjm.html

[Q11] 一次插入多行
来源：http://dali.fzhhl.top/Article/details/gtdxlzuydf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhengqikj.top/Article/details/gtsfdqtuda.html

[Q12] 插入后取自增 ID
来源：http://dali.yuxming.cn/Article/details/gtvmgaaens.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tanke756.top/Article/details/gtofsqiegj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hnxiangtu.top/Article/details/gtrhzjyjrq.html

[Q13] 忽略重复插入
来源：http://dali.zhongyouzk.top/Article/details/gtwzneogao.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbodqwro.html

[Q14] 存在则更新（upsert）
来源：http://dali.snrcjt.cn/Article/details/gtrgezsgmv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.bjfxy.top/Article/details/gtbkobjjab.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zycfv.cn/Article/details/gtlyekasih.html

[Q15] 查询全部
来源：http://dali.xinyue.icu/Article/details/gtssotyjoo.html

SELECT * FROM users;
来源：http://dali.sysykeji.top/Article/details/gthjgdjrqq.html

[Q16] 查询指定列
来源：http://dali.jinqigufen.top/Article/details/gtxecyqznm.html

SELECT id, name FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtntoavxvz.html

[Q17] 条件查询
来源：http://dali.wangshuangyany.cn/Article/details/gtxrhefyok.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtbbsnvygc.html

[Q18] 模糊匹配
来源：http://dali.xziqi.cn/Article/details/gtluqujizw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yonumen.top/Article/details/gtnuabftjo.html

[Q19] 范围查询
来源：http://dali.ehwqpu.com/Article/details/gtarlrafmz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnqzz.top/Article/details/gtoxakaakr.html

[Q20] IN 列表
来源：http://dali.cashguo.top/Article/details/gtitftuywi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yvedp.cn/Article/details/gtvrsrvtbw.html

[Q21] 空值判断
来源：http://dali.havefunace.top/Article/details/gtdxidqxix.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nwbrower.top/Article/details/gtycmsqpha.html

[Q22] 排序
来源：http://dali.daxiang520.top/Article/details/gtracinvja.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinqigufen.top/Article/details/gtvsrnxbty.html

[Q23] 分页
来源：http://dali.smart0.xyz/Article/details/gtvaswfygv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gogol.net.cn/Article/details/gtolzqktbh.html

[Q24] 去重
来源：http://dali.9152youxi.cn/Article/details/gtuorediqz.html

SELECT DISTINCT city FROM users;
来源：http://dali.sxryk.cn/Article/details/gtgespling.html

[Q25] 只取前 N 条
来源：http://dali.nwbrower.top/Article/details/gtpkdwntrj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhengqikj.top/Article/details/gtkhdkppuk.html

[Q26] 计数
来源：http://dali.yangfankeji.com/Article/details/gtnenchzle.html

SELECT COUNT(*) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtkdylawln.html

[Q27] 条件计数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtluipbtoq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtdocpcuac.html

[Q28] 求和与平均
来源：http://dali.gotoacloud.top/Article/details/gtmfbozukg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtqoritrna.html

[Q29] 最大最小值
来源：http://dali.ybcxt.top/Article/details/gtitpuytbm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtrqyvbghp.html

[Q30] 分组统计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzzkxxet.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gtinmyxjdo.html

[Q31] 分组后过滤
来源：http://dali.nwbrower.top/Article/details/gtktulyror.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yanxiufei.cn/Article/details/gtcrxxlttp.html

[Q32] 分组拼接字符串
来源：http://dali.mhx1999.top/Article/details/gtivfcpbdp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gtfiynmugq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.redwolf501.top/Article/details/gtlwpsxayu.html

[Q33] 多列分组
来源：http://dali.haohaochexian.top/Article/details/gtiuxgjnig.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cashguo.top/Article/details/gtpgefftfi.html

[Q34] 每组取第一条
来源：http://dali.gogol.net.cn/Article/details/gtieqbmucr.html

SELECT * FROM (
来源：http://dali.hfpthk.cn/Article/details/gthyevncsg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.316326.xyz/Article/details/gtfvmhatnu.html

) t WHERE rn = 1;
来源：http://dali.sufxvd.cn/Article/details/gtstnovrhk.html

[Q35] 内连接
来源：http://dali.shangyingyoupin.top/Article/details/gtledoopgs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gtouexrywb.html

[Q36] 左连接
来源：http://dali.zdqjudy.top/Article/details/gtsofwpdad.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xziqi.cn/Article/details/gthztucgqp.html

[Q37] 右连接
来源：http://dali.316326.xyz/Article/details/gthfgcehya.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.wangdashe.top/Article/details/gtcstvnnjo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.dashuyun.cn/Article/details/gtsyfmlgwt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tianlin.xyz/Article/details/gtjntqavra.html

[Q39] 自连接（查上下级）
来源：http://dali.chenzaomai.com/Article/details/gttuphdlhg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.fengsongda.top/Article/details/gtgfyeqnec.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhiwuduotai.top/Article/details/gtgjvxazie.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sysykeji.top/Article/details/gtbwyzocgr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zdqjudy.top/Article/details/gtgvllcsrc.html

[Q41] 多表连接
来源：http://dali.zhiwuduotai.top/Article/details/gtstwcmpuj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xziqi.cn/Article/details/gtzqsplvxg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yangfankeji.com/Article/details/gtaazwotqr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hysaishi.cn/Article/details/gtnratytws.html

[Q42] 连接条件附加过滤
来源：http://dali.aizwys.cn/Article/details/gtmaeupoyy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.redwolf501.top/Article/details/gticuizxtn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xylfe.cn/Article/details/gtmdkglrep.html

[Q43] 标量子查询
来源：http://dali.yvedp.cn/Article/details/gtbffikbtc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sysykeji.top/Article/details/gttdizbssb.html

[Q44] IN 子查询
来源：http://dali.tanke756.top/Article/details/gtijgggawb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jqgfzy.top/Article/details/gtjkigzdvl.html

[Q45] EXISTS 判断存在
来源：http://dali.svipenyu.cn/Article/details/gtiejolfag.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hammf.cn/Article/details/gtwfmpobnk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvnxrvcnd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gttvzwamdh.html

[Q47] 与平均值比较
来源：http://dali.chenzaomai.com/Article/details/gtmtzigblq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jiagoushi.top/Article/details/gtsoupgnrg.html

[Q48] CTE 公用表表达式
来源：http://dali.zhoulong.xyz/Article/details/gtmyrrcbfp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhoulong.xyz/Article/details/gtttbulngv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.smart0.xyz/Article/details/gtxrnkpxng.html

[Q49] 更新单行
来源：http://dali.yuanzhike.top/Article/details/gtlnsmbtum.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gtkcdimruq.html

[Q50] 批量更新
来源：http://dali.yj20258.top/Article/details/gtmwjasbwn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jianghu66.top/Article/details/gtyqrxnktx.html

[Q51] 用子查询更新
来源：http://dali.yuxming.cn/Article/details/gtcapgbkvq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.fengsongda.top/Article/details/gtnsnqatnf.html

[Q52] 删除指定行
来源：http://dali.jiagoushi.top/Article/details/gtkvibjutq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtgejjxwfu.html

[Q53] 按条件删除
来源：http://dali.gzhubu.top/Article/details/gtnrnlovle.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.fzhhl.top/Article/details/gtrvkhggsd.html

[Q54] 清空表
来源：http://dali.dianchejie.cn/Article/details/gtkymtldxd.html

TRUNCATE TABLE logs;
来源：http://dali.yonumen.top/Article/details/gtertazbki.html

[Q55] 排名（并列占位）
来源：http://dali.birdmap.top/Article/details/gttsdbbixj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gtmlgcwfun.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cdnleiting.top/Article/details/gtfwmpulhs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.c1oappe.top/Article/details/gtiteewwxp.html

[Q57] 行号
来源：http://dali.fengsongda.top/Article/details/gtgdzsytxa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.andypj.xyz/Article/details/gtivcrjjfk.html

[Q58] 累计求和
来源：http://dali.gaohongyu789.top/Article/details/gtrmjejvjl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtnqynrwsj.html

[Q59] 分组内累计
来源：http://dali.bjfxy.top/Article/details/gtcocevsgc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtscwlfavo.html

[Q60] 取上一行 / 下一行
来源：http://dali.aibaodan.cn/Article/details/gtcqyobcbx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ivvv.top/Article/details/gtljguwdrf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yonumen.top/Article/details/gtmaiehzwe.html

[Q61] 移动平均
来源：http://dali.sweek.top/Article/details/gteabfkmel.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtoifzhdip.html

[Q62] 分组占比
来源：http://dali.yangfankeji.com/Article/details/gtyztwmbgc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gtmvebxand.html

[Q63] 开启事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcynbhubb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shangyingyoupin.top/Article/details/gtmrerynbh.html

[Q64] 提交事务
来源：http://dali.gotoacloud.top/Article/details/gtiitbkugu.html

COMMIT;
来源：http://dali.ybcxt.top/Article/details/gtyqhxmcth.html

[Q65] 回滚事务
来源：http://dali.aibaodan.cn/Article/details/gteanmkups.html

ROLLBACK;
来源：http://dali.pengpengdd.cyou/Article/details/gtxlmbtmuy.html

[Q66] 行锁查询
来源：http://dali.jlsjyb.cn/Article/details/gtiakifopq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cdnleiting.top/Article/details/gtjvzgborv.html

[Q67] 设置隔离级别
来源：http://dali.zhoulong.xyz/Article/details/gtkukswqce.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yvedp.cn/Article/details/gtdsjnuntf.html

[Q68] 保存点
来源：http://dali.dianchejie.cn/Article/details/gtbziaqwmp.html

SAVEPOINT sp1;
来源：http://dali.sweek.top/Article/details/gtyjtminyd.html

ROLLBACK TO sp1;
来源：http://dali.fengsongda.top/Article/details/gtbrplyqwf.html

[Q69] 查看执行计划
来源：http://dali.jinqigufen.top/Article/details/gtorfdthvl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cucudq.cn/Article/details/gtqjintwrf.html

[Q70] 更新统计信息
来源：http://dali.yueranfly.top/Article/details/gtzwrterdr.html

ANALYZE TABLE users;
来源：http://dali.tian-w.cn/Article/details/gtbolnkalp.html

[Q71] 查看建表语句
来源：http://dali.jinqigufen.top/Article/details/gtkwgzpccg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dianchejie.cn/Article/details/gtrbzrjzjj.html

[Q72] 查看索引
来源：http://dali.aizwys.cn/Article/details/gtovusabgj.html

SHOW INDEX FROM users;
来源：http://dali.yvedp.cn/Article/details/gthnqbyead.html

[Q73] 查看表状态
来源：http://dali.nwbrower.top/Article/details/gteoardduf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hnqzz.top/Article/details/gtzsanckvw.html

[Q74] 强制使用索引
来源：http://dali.yueranfly.top/Article/details/gtzrqfquam.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.aibaodan.cn/Article/details/gtuidempuz.html

[Q75] 日期格式化
来源：http://dali.daria6918.cn/Article/details/gtksofmhnx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gthpmfkiio.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cashguo.top/Article/details/gtdokefqqt.html

[Q76] 按天统计
来源：http://dali.jinqigufen.top/Article/details/gtekxbslfx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xziqi.cn/Article/details/gtosqagnym.html

[Q77] 时间加减
来源：http://dali.mhx1999.top/Article/details/gtddgjgfjo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jqgufenzy.top/Article/details/gtfdomqygp.html

[Q78] 当前时间
来源：http://dali.kuanghao11.cn/Article/details/gtysxnngoc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hammf.cn/Article/details/gtedbnlyof.html

[Q79] 字符串拼接
来源：http://dali.snrcjt.cn/Article/details/gtcqlphewb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shuidangran.top/Article/details/gtzmeodsvc.html

[Q80] 字符串截取
来源：http://dali.shuidangran.top/Article/details/gtozrszrny.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtahxnjhik.html

[Q81] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gtekpoxxpi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtubyfamlj.html

[Q82] 字符长度与字节长度
来源：http://dali.fzhhl.top/Article/details/gtfkddohxp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtotwioerw.html

[Q83] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gtwusqwhmi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtxevthzjl.html

[Q84] 去除首尾空格
来源：http://dali.sufxvd.cn/Article/details/gthrxgayow.html

SELECT TRIM(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gtjrfbptbc.html

[Q85] 数值取整
来源：http://dali.yvedp.cn/Article/details/gtetdxkvei.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoiiiqkfn.html

[Q86] 读取 JSON 字段
来源：http://dali.hywenlv.cn/Article/details/gtaqmmnjcw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.iojbl.cn/Article/details/gtbvsrmwdu.html

[Q87] JSON 字段做条件
来源：http://dali.ppjwa.cn/Article/details/gtbfojfyzl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.0kj1m.cn/Article/details/gtwlhgiuhp.html

[Q88] 行转列（条件聚合）
来源：http://dali.ivvv.top/Article/details/gtrdnswpcj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gotoacloud.top/Article/details/gtbhcxhjdw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtqmfevmsj.html

[Q89] 判断表是否存在
来源：http://dali.shuidangran.top/Article/details/gtyfqpzphv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ivvv.top/Article/details/gtazyyvmme.html

[Q90] 生成序号列
来源：http://dali.jinqigufen.top/Article/details/gtoqizjoge.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xziqi.cn/Article/details/gtfhbthwpt.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtdvqjapux.html

R. Bash 专题
来源：http://dali.shangyingyoupin.top/Article/details/gtzpholxai.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtspcamztp.html

[R01] shebang 与严格模式
来源：http://dali.ehwqpu.com/Article/details/gttyulnwza.html

#!/usr/bin/env bash
来源：http://dali.quarkkingdee.top/Article/details/gtbnekyvpa.html

set -euo pipefail
来源：http://dali.hfpthk.cn/Article/details/gtelshhuvm.html

[R02] 变量赋值与使用
来源：http://dali.tianlin.xyz/Article/details/gtfkxlitaq.html

name="Tom"; echo "$name"
来源：http://dali.chenzaomai.com/Article/details/gtkmaxpvsp.html

[R03] 只读变量
来源：http://dali.dashuyun.cn/Article/details/gtlxxmijev.html

readonly PI=3.14
来源：http://dali.daria6918.cn/Article/details/gtnfxanuup.html

[R04] 位置参数
来源：http://dali.shangyingyoupin.top/Article/details/gttckmdjdo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sxryk.cn/Article/details/gtfwdzvwie.html

[R05] 参数默认值
来源：http://dali.shuidangran.top/Article/details/gtwqcgqawk.html

name="${1:-default}"
来源：http://dali.zhoulong.xyz/Article/details/gtwbonrsxx.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gtowjimcko.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ivvv.top/Article/details/gttnqqpxcm.html

[R07] if 判断文件
来源：http://dali.svipenyu.cn/Article/details/gtoclnobxk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zdqjudy.top/Article/details/gtojeegqlp.html

[R08] 数值比较
来源：http://dali.zhengqikj.top/Article/details/gtqcvopacl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.meibo888.top/Article/details/gtbfhorvgg.html

[R09] 字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gtirvxlpee.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcxteqxn.html

[R10] 正则匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtgdyqwogj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yueranfly.top/Article/details/gtavuubrak.html

[R11] case 多分支
来源：http://dali.wangdashe.top/Article/details/gtpormjzpn.html

case "$1" in
来源：http://dali.zhiwuduotai.top/Article/details/gtcwkybqrv.html

start) echo "启动" ;;
来源：http://dali.nwbrower.top/Article/details/gtggwnkycw.html

stop)  echo "停止" ;;
来源：http://dali.daria6918.cn/Article/details/gtezjyyzur.html

*)     echo "未知命令" ;;
来源：http://dali.cqqwz.cn/Article/details/gtjheimmfm.html

esac
来源：http://dali.gogol.net.cn/Article/details/gtuoejbynv.html

[R12] for 遍历文件
来源：http://dali.andypj.xyz/Article/details/gtbqaucbmi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hammf.cn/Article/details/gtjdcvbzpd.html

[R13] for 计数循环
来源：http://dali.birdmap.top/Article/details/gtwfzftoht.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gtimqtdelj.html

[R14] C 风格 for
来源：http://dali.daria6918.cn/Article/details/gtqxsocftq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtsnnwxhsl.html

[R15] while 逐行读文件
来源：http://dali.tanke756.top/Article/details/gtngsnwkyp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjxnkpcr.html

[R16] until 等待条件
来源：http://dali.shuidangran.top/Article/details/gtheymztht.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gtywhnsewa.html

[R17] 数组定义与取值
来源：http://dali.zhongyouzk.top/Article/details/gtjumvfyix.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yueranfly.top/Article/details/gtzmivygxj.html

[R18] 遍历数组
来源：http://dali.sweek.top/Article/details/gtkngceqka.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnxiangtu.top/Article/details/gtmmlrsrzi.html

[R19] 数组长度
来源：http://dali.tian-w.cn/Article/details/gtyikhauwu.html

echo "${#arr[@]}"
来源：http://dali.pycfn.com/Article/details/gtbpwtdnrk.html

[R20] 关联数组（字典）
来源：http://dali.wangdashe.top/Article/details/gtukxagcfk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenlongwang.top/Article/details/gtwikxocap.html

[R21] 字符串长度
来源：http://dali.tian-w.cn/Article/details/gtnirdzpbi.html

echo "${#s}"
来源：http://dali.havefunace.top/Article/details/gtualqabwd.html

[R22] 截取子串
来源：http://dali.iojbl.cn/Article/details/gtiyyxkkpg.html

echo "${s:0:5}"
来源：http://dali.sufxvd.cn/Article/details/gtqrsxfjqx.html

[R23] 字符串替换
来源：http://dali.pengpengdd.cyou/Article/details/gtkjhuhsme.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nanxinkj.top/Article/details/gtrnfiwmeu.html

[R24] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gtcuelyjzj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gtuuabdwss.html

[R25] 去后缀 / 去前缀
来源：http://dali.bjfxy.top/Article/details/gtdhounofd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.iojbl.cn/Article/details/gtfkumsiuc.html

[R26] 命令替换
来源：http://dali.sxryk.cn/Article/details/gtckrjazuo.html

now=$(date +%F); echo "$now"
来源：http://dali.chenjidiqi.icu/Article/details/gtlerutuxf.html

[R27] 算术展开
来源：http://dali.daria6918.cn/Article/details/gtjtqktffj.html

echo $((1 + 2 * 3))
来源：http://dali.nanxinkj.top/Article/details/gtrornapnh.html

[R28] 浮点运算
来源：http://dali.cdnleiting.top/Article/details/gtsnoxvhlg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsroinoe.html

[R29] 定义函数
来源：http://dali.xylfe.cn/Article/details/gtdjyaoxkn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xylfe.cn/Article/details/gthbvtdleu.html

[R30] 函数返回状态码
来源：http://dali.guowangkeji.top/Article/details/gtgdutiqam.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhengqikj.top/Article/details/gtaggrnpuz.html

[R31] 局部变量
来源：http://dali.havefunace.top/Article/details/gtllsqjsbk.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gtabrfjlot.html

[R32] 参数个数校验
来源：http://dali.quarkkingdee.top/Article/details/gtxwzwkjvj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtsairyziu.html

[R33] 捕获错误并提示行号
来源：http://dali.hongshengwenyu.top/Article/details/gtygaewvcu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.andypj.xyz/Article/details/gthklgchbw.html

[R34] 退出时清理
来源：http://dali.sufxvd.cn/Article/details/gttmwmousd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gttkkoonwh.html

[R35] 后台执行并等待
来源：http://dali.fzhhl.top/Article/details/gtjobjogya.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pycfn.com/Article/details/gtmzpjczvu.html

[R36] 并发执行多个任务
来源：http://dali.aibaodan.cn/Article/details/gtmroekwvm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.haohaochexian.top/Article/details/gtnfxtpwcg.html

[R37] 把输出赋给变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccuwxmjc.html

files=$(ls -1)
来源：http://dali.xylfe.cn/Article/details/gtgdiulfwp.html

[R38] 管道串联
来源：http://dali.fzhhl.top/Article/details/gtnvmgztri.html

cat a.txt | grep -i error | wc -l
来源：http://dali.wangdashe.top/Article/details/gteyqvoctu.html

[R39] 重定向标准输出与错误
来源：http://dali.andypj.xyz/Article/details/gttopksvuc.html

cmd > out.log 2>&1
来源：http://dali.haohaochexian.top/Article/details/gttwhlrrlp.html

[R40] 追加写日志
来源：http://dali.c1oappe.top/Article/details/gtruoijqrb.html

echo "log" >> out.log
来源：http://dali.hongshengwenyu.top/Article/details/gtyapawcwv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gtplvjkhjy.html

cmd >/dev/null 2>&1
来源：http://dali.daxiang520.top/Article/details/gtxwqbxncn.html

[R42] 输入重定向
来源：http://dali.redwolf501.top/Article/details/gtropmpgsm.html

wc -l < a.txt
来源：http://dali.zhengqikj.top/Article/details/gtzqyneldj.html

[R43] 按名字查找文件
来源：http://dali.chenlongwang.top/Article/details/gtmuqmwaut.html

find . -name "*.log" -type f
来源：http://dali.nwbrower.top/Article/details/gtaipsiayp.html

[R44] 按修改时间查找
来源：http://dali.yuanzhike.top/Article/details/gtrszlfexr.html

find . -mtime -7 -type f
来源：http://dali.yueranfly.top/Article/details/gthmadgpbo.html

[R45] 批量删除
来源：http://dali.bjfxy.top/Article/details/gtvkhzgqlh.html

find . -name "*.tmp" -delete
来源：http://dali.xuetiantiany.cn/Article/details/gtetitdqxo.html

[R46] 递归替换文件内容
来源：http://dali.kuanghao11.cn/Article/details/gtjogdejbw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqsztmfg.html

[R47] sed 单行替换
来源：http://dali.pengpengdd.cyou/Article/details/gtbutzwsub.html


<!-- 参考信息 -->