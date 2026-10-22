代发 wailian999

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hfpthk.cn/Article/details/gt2enjadrst.html

[Q07] 删除表
来源：http://dali.svipenyu.cn/Article/details/gt2njzewnuc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ybcxt.top/Article/details/gt2wfbphhcw.html

[Q08] 创建普通索引
来源：http://dali.hammf.cn/Article/details/gt2hfyiudtr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gt2xixggqss.html

[Q09] 创建唯一索引
来源：http://dali.sysykeji.top/Article/details/gt2euqjtjhk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gt2zuslfbbo.html

[Q10] 插入单行
来源：http://dali.yonumen.top/Article/details/gt2gntiewqb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuxming.cn/Article/details/gt2iybtjrvn.html

[Q11] 一次插入多行
来源：http://dali.yj202588.top/Article/details/gt2iraghcyc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gt2tddgqudv.html

[Q12] 插入后取自增 ID
来源：http://dali.hnqzz.top/Article/details/gt2wwklboej.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nwbrower.top/Article/details/gt2hzhazhzp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.mhx1999.top/Article/details/gt2pxiorjiu.html

[Q13] 忽略重复插入
来源：http://dali.dashuyun.cn/Article/details/gt2lkyierqx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jqgufenzy.top/Article/details/gt2hvakwnzp.html

[Q14] 存在则更新（upsert）
来源：http://dali.pycfn.com/Article/details/gt2uokwidhz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.redwolf501.top/Article/details/gt2ptvqoksc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenjidiqi.icu/Article/details/gt2cfsyggmn.html

[Q15] 查询全部
来源：http://dali.ydzc1.top/Article/details/gt2tbmmddkt.html

SELECT * FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cqltcmit.html

[Q16] 查询指定列
来源：http://dali.daxiang520.top/Article/details/gt2bdiylswg.html

SELECT id, name FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2csqnbobo.html

[Q17] 条件查询
来源：http://dali.ppjwa.cn/Article/details/gt2bwsrgiig.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2wjzlxmxi.html

[Q18] 模糊匹配
来源：http://dali.316326.xyz/Article/details/gt2uitxsugb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hongshengwenyu.top/Article/details/gt2aaapcxao.html

[Q19] 范围查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zhlljtss.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhengqikj.top/Article/details/gt2zitkukuc.html

[Q20] IN 列表
来源：http://dali.cheryme.top/Article/details/gt2wkejkxle.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hfpthk.cn/Article/details/gt2mzskohuf.html

[Q21] 空值判断
来源：http://dali.hongshengwenyu.top/Article/details/gt2vkllqwhv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ybcxt.top/Article/details/gt2npozrnwt.html

[Q22] 排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ehquuvkv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.havefunace.top/Article/details/gt2zstfbkku.html

[Q23] 分页
来源：http://dali.zhengqikj.top/Article/details/gt2xboswfbs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.bjfxy.top/Article/details/gt2ftffvofq.html

[Q24] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qmwbjwqp.html

SELECT DISTINCT city FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2yoearphy.html

[Q25] 只取前 N 条
来源：http://dali.birdmap.top/Article/details/gt2lrpezlzb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gogol.net.cn/Article/details/gt2avzxoxyu.html

[Q26] 计数
来源：http://dali.zhixingplan.top/Article/details/gt2porrhffh.html

SELECT COUNT(*) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2etdvoxcb.html

[Q27] 条件计数
来源：http://dali.yvedp.cn/Article/details/gt2pxmcaipb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2mmwhszan.html

[Q28] 求和与平均
来源：http://dali.yvedp.cn/Article/details/gt2vrtfvnzd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gt2xywfoqiy.html

[Q29] 最大最小值
来源：http://dali.xinyue.icu/Article/details/gt2jdrgxdob.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2ntjdmksn.html

[Q30] 分组统计
来源：http://dali.iojbl.cn/Article/details/gt2dhishszl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gt2dfsadtib.html

[Q31] 分组后过滤
来源：http://dali.daria6918.cn/Article/details/gt2cumoouwp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj20258.top/Article/details/gt2lkdduwjk.html

[Q32] 分组拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2sviiommr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gt2rwdvyjdr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhengqikj.top/Article/details/gt2yjmokmlg.html

[Q33] 多列分组
来源：http://dali.xuetiantiany.cn/Article/details/gt2pgoexsog.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xinyue.icu/Article/details/gt2phjthpbv.html

[Q34] 每组取第一条
来源：http://dali.cqqwz.cn/Article/details/gt2teautmva.html

SELECT * FROM (
来源：http://dali.tianlin.xyz/Article/details/gt2dqcoqpnj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sxryk.cn/Article/details/gt2hnyuurjo.html

) t WHERE rn = 1;
来源：http://dali.cashguo.top/Article/details/gt2dhpzbuvy.html

[Q35] 内连接
来源：http://dali.yj20258.top/Article/details/gt2vipxdjld.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.snrcjt.cn/Article/details/gt2crnbswjn.html

[Q36] 左连接
来源：http://dali.sysykeji.top/Article/details/gt2twqtdmhj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gt2gtytjxvl.html

[Q37] 右连接
来源：http://dali.aizwys.cn/Article/details/gt2boemnvsv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnqzz.top/Article/details/gt2rflqnsdo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnqzz.top/Article/details/gt2vlfvcdfs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.haohaochexian.top/Article/details/gt2epzgqkap.html

[Q39] 自连接（查上下级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lhjkfqol.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sufxvd.cn/Article/details/gt2bktghcxx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hysaishi.cn/Article/details/gt2wmwgssdd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shangyingyoupin.top/Article/details/gt2byrubjqa.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.pycfn.com/Article/details/gt2gzxlcbzq.html

[Q41] 多表连接
来源：http://dali.tanke756.top/Article/details/gt2zsllobji.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnqzz.top/Article/details/gt2jiqtwgwy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shangyingyoupin.top/Article/details/gt2rektquxt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zdqjudy.top/Article/details/gt2wxtevvda.html

[Q42] 连接条件附加过滤
来源：http://dali.jqgfzy.top/Article/details/gt2crbokxgi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yuanzhike.top/Article/details/gt2vooikgcc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jyoumei.cn/Article/details/gt2aspflzma.html

[Q43] 标量子查询
来源：http://dali.sysykeji.top/Article/details/gt2zevceyst.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenjidiqi.icu/Article/details/gt2coepswee.html

[Q44] IN 子查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qrqarpcf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lxaebzas.html

[Q45] EXISTS 判断存在
来源：http://dali.yonumen.top/Article/details/gt2fkuusobl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gt2yxhmiccv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangshuangyany.cn/Article/details/gt2izfsxumu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ftzuzapc.html

[Q47] 与平均值比较
来源：http://dali.tanke756.top/Article/details/gt2sifvhazh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhengqikj.top/Article/details/gt2lhgodkzq.html

[Q48] CTE 公用表表达式
来源：http://dali.c1oappe.top/Article/details/gt2braxcjkj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xinyue.icu/Article/details/gt2vqzacwpq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shzxlz.cn/Article/details/gt2reolgggb.html

[Q49] 更新单行
来源：http://dali.snrcjt.cn/Article/details/gt2pwlndxkv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gt2rfjwggws.html

[Q50] 批量更新
来源：http://dali.feifeiyinyue.top/Article/details/gt2yayxqtzn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yuxming.cn/Article/details/gt2gbefopfc.html

[Q51] 用子查询更新
来源：http://dali.vqdsnc.cn/Article/details/gt2xktkwzsc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2ukaigfhx.html

[Q52] 删除指定行
来源：http://dali.chenlongwang.top/Article/details/gt2rwojicgo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jianghu66.top/Article/details/gt2cvxoixhs.html

[Q53] 按条件删除
来源：http://dali.tanke756.top/Article/details/gt2keteptno.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.aibaodan.cn/Article/details/gt2ztcfnlsm.html

[Q54] 清空表
来源：http://dali.jqgfzy.top/Article/details/gt2ccgpyhfc.html

TRUNCATE TABLE logs;
来源：http://dali.yj20258.top/Article/details/gt2ebjlmwkq.html

[Q55] 排名（并列占位）
来源：http://dali.guowangkeji.top/Article/details/gt2pirwgkep.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rbprswfa.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ncmmvbpl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.kuanghao11.cn/Article/details/gt2glpifvkp.html

[Q57] 行号
来源：http://dali.jqgfzy.top/Article/details/gt2tjfbtqfd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2aqwlobns.html

[Q58] 累计求和
来源：http://dali.xuanzx.com/Article/details/gt2iwuayvcu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.mhx1999.top/Article/details/gt2idgsprwu.html

[Q59] 分组内累计
来源：http://dali.ehwqpu.com/Article/details/gt2fmhvplfs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2kmkdxhrq.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuetiantiany.cn/Article/details/gt2zpdgoqxr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sxryk.cn/Article/details/gt2yqzexzmf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gt2wybzumwt.html

[Q61] 移动平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wjyyddob.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gt2rspzugwq.html

[Q62] 分组占比
来源：http://dali.yj20258.top/Article/details/gt2szdtnfju.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gt2bqhxycvj.html

[Q63] 开启事务
来源：http://dali.yvedp.cn/Article/details/gt2tlraonod.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuetiantiany.cn/Article/details/gt2qgseduvn.html

[Q64] 提交事务
来源：http://dali.gotoacloud.top/Article/details/gt2lsjlipni.html

COMMIT;
来源：http://dali.feifeiyinyue.top/Article/details/gt2xtragunb.html

[Q65] 回滚事务
来源：http://dali.hfpthk.cn/Article/details/gt2jnrnzmnx.html

ROLLBACK;
来源：http://dali.jyoumei.cn/Article/details/gt2bfijhkza.html

[Q66] 行锁查询
来源：http://dali.jqgufenzy.top/Article/details/gt2raxamdoj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenlongwang.top/Article/details/gt2axzknouv.html

[Q67] 设置隔离级别
来源：http://dali.jyoumei.cn/Article/details/gt2irphkkhn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lrhcekkh.html

[Q68] 保存点
来源：http://dali.yj202588.top/Article/details/gt2nbfwkmok.html

SAVEPOINT sp1;
来源：http://dali.sweek.top/Article/details/gt2jwtlgawz.html

ROLLBACK TO sp1;
来源：http://dali.daxiang520.top/Article/details/gt2nkqtbtip.html

[Q69] 查看执行计划
来源：http://dali.yj20258.top/Article/details/gt2hkxlfcdu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hysaishi.cn/Article/details/gt2wwtqvrug.html

[Q70] 更新统计信息
来源：http://dali.shangyingyoupin.top/Article/details/gt2udxejshz.html

ANALYZE TABLE users;
来源：http://dali.yuanzhike.top/Article/details/gt2utrdhyyb.html

[Q71] 查看建表语句
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kjmpgzti.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jiagoushi.top/Article/details/gt2asuhxnax.html

[Q72] 查看索引
来源：http://dali.gogol.net.cn/Article/details/gt2rvstltnd.html

SHOW INDEX FROM users;
来源：http://dali.meibo888.top/Article/details/gt2ehujsntr.html

[Q73] 查看表状态
来源：http://dali.zycfv.cn/Article/details/gt2ouzgtynu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dianchejie.cn/Article/details/gt2dpdqdvyc.html

[Q74] 强制使用索引
来源：http://dali.vqdsnc.cn/Article/details/gt2namvemja.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj20258888.top/Article/details/gt2zkwnukll.html

[Q75] 日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gt2aijfhgfl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gt2gyvhrizc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.quarkkingdee.top/Article/details/gt2yfcyurtx.html

[Q76] 按天统计
来源：http://dali.dianchejie.cn/Article/details/gt2bnvtmomd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.andypj.xyz/Article/details/gt2brfeocaf.html

[Q77] 时间加减
来源：http://dali.chenzaomai.com/Article/details/gt2geufuwyx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jyoumei.cn/Article/details/gt2skrepnbz.html

[Q78] 当前时间
来源：http://dali.guannengcc.top/Article/details/gt2rmbzgfid.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yongpay.top/Article/details/gt2jtecqxih.html

[Q79] 字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gt2rhihmgfl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nwbrower.top/Article/details/gt2ybrjusci.html

[Q80] 字符串截取
来源：http://dali.hysaishi.cn/Article/details/gt2gtgmiwid.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2idsrvvcr.html

[Q81] 字符串替换
来源：http://dali.iojbl.cn/Article/details/gt2erxgcure.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2ajygadbm.html

[Q82] 字符长度与字节长度
来源：http://dali.xylfe.cn/Article/details/gt2fvimkuaj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2lmgghyrx.html

[Q83] 大小写转换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2peqqbikg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2gvxoonji.html

[Q84] 去除首尾空格
来源：http://dali.cdnleiting.top/Article/details/gt2wkouwmym.html

SELECT TRIM(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2ghwxcbho.html

[Q85] 数值取整
来源：http://dali.nanxuanxn.top/Article/details/gt2uqwdfrjv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.guowangkeji.top/Article/details/gt2xajhvbci.html

[Q86] 读取 JSON 字段
来源：http://dali.xziqi.cn/Article/details/gt2cpazoyor.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.andypj.xyz/Article/details/gt2hmxgxtcz.html

[Q87] JSON 字段做条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2voqxdikk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yangfankeji.com/Article/details/gt2lxxvvqfm.html

[Q88] 行转列（条件聚合）
来源：http://dali.gaohongyu789.top/Article/details/gt2rlpozsav.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ojkkidwp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2ialqhxpn.html

[Q89] 判断表是否存在
来源：http://dali.hnqzz.top/Article/details/gt2dcyntxxi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sufnxips.html

[Q90] 生成序号列
来源：http://dali.bjfxy.top/Article/details/gt2dyjoaiio.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sweek.top/Article/details/gt2nljbvwob.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2ocaobpym.html

R. Bash 专题
来源：http://dali.aibaodan.cn/Article/details/gt2anyqjekz.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2qazldvjh.html

[R01] shebang 与严格模式
来源：http://dali.andypj.xyz/Article/details/gt2rpsylsbd.html

#!/usr/bin/env bash
来源：http://dali.hammf.cn/Article/details/gt2lorscfnu.html

set -euo pipefail
来源：http://dali.wangshuangyany.cn/Article/details/gt2mbeiifbg.html

[R02] 变量赋值与使用
来源：http://dali.tanke756.top/Article/details/gt2hpkkahnl.html

name="Tom"; echo "$name"
来源：http://dali.aibaodan.cn/Article/details/gt2todfkilf.html

[R03] 只读变量
来源：http://dali.zhixingplan.top/Article/details/gt2xxhojiwu.html

readonly PI=3.14
来源：http://dali.tianlin.xyz/Article/details/gt2jsmkhzzn.html

[R04] 位置参数
来源：http://dali.andypj.xyz/Article/details/gt2dlaxwefr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.kuanghao11.cn/Article/details/gt2cljfjrrh.html

[R05] 参数默认值
来源：http://dali.yuanzhike.top/Article/details/gt2kdsphxqn.html

name="${1:-default}"
来源：http://dali.jianghu66.top/Article/details/gt2wbpfvrpo.html

[R06] 判断命令是否存在
来源：http://dali.hammf.cn/Article/details/gt2tauglzrp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.fengsongda.top/Article/details/gt2aiuukmge.html

[R07] if 判断文件
来源：http://dali.yj20258888.top/Article/details/gt2ddwxevuq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cucudq.cn/Article/details/gt2bvhzsyjx.html

[R08] 数值比较
来源：http://dali.yonumen.top/Article/details/gt2qbgfvcyc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yuxming.cn/Article/details/gt2htclnjqd.html

[R09] 字符串比较
来源：http://dali.shangyingyoupin.top/Article/details/gt2nqeinjsp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yvedp.cn/Article/details/gt2zjrmdksn.html

[R10] 正则匹配
来源：http://dali.jyoumei.cn/Article/details/gt2sbxydash.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258.top/Article/details/gt2mvfffsrh.html

[R11] case 多分支
来源：http://dali.zhixingplan.top/Article/details/gt2uzyqwwcv.html

case "$1" in
来源：http://dali.yueranfly.top/Article/details/gt2crozrbrx.html

start) echo "启动" ;;
来源：http://dali.nanxuanxn.top/Article/details/gt2ydsnyaex.html

stop)  echo "停止" ;;
来源：http://dali.ppjwa.cn/Article/details/gt2caouxeop.html

*)     echo "未知命令" ;;
来源：http://dali.0kj1m.cn/Article/details/gt2zcziixty.html

esac
来源：http://dali.yonumen.top/Article/details/gt2adljaoag.html

[R12] for 遍历文件
来源：http://dali.redwolf501.top/Article/details/gt2jljiipox.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tian-w.cn/Article/details/gt2mqldvchw.html

[R13] for 计数循环
来源：http://dali.smart0.xyz/Article/details/gt2ezkysork.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gt2qibycmtq.html

[R14] C 风格 for
来源：http://dali.cheryme.top/Article/details/gt2hulkmgqc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hpqeynya.html

[R15] while 逐行读文件
来源：http://dali.yueranfly.top/Article/details/gt2clablnvk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.316326.xyz/Article/details/gt2focaducw.html

[R16] until 等待条件
来源：http://dali.guowangkeji.top/Article/details/gt2yhzuybxo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gt2hkwiopbc.html

[R17] 数组定义与取值
来源：http://dali.ybcxt.top/Article/details/gt2trkbiasi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.redwolf501.top/Article/details/gt2twodanys.html

[R18] 遍历数组
来源：http://dali.iojbl.cn/Article/details/gt2jvrdoubi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jianghu66.top/Article/details/gt2ellhxkfu.html

[R19] 数组长度
来源：http://dali.jlsjyb.cn/Article/details/gt2gekidmrc.html

echo "${#arr[@]}"
来源：http://dali.gogol.net.cn/Article/details/gt2heigoxww.html

[R20] 关联数组（字典）
来源：http://dali.xylfe.cn/Article/details/gt2gwtrqjlp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigfzy.top/Article/details/gt2kgfkwviu.html

[R21] 字符串长度
来源：http://dali.tian-w.cn/Article/details/gt2eadnvcpo.html

echo "${#s}"
来源：http://dali.birdmap.top/Article/details/gt2glkzevje.html

[R22] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gt2csqlxodb.html

echo "${s:0:5}"
来源：http://dali.snrcjt.cn/Article/details/gt2rjmmqauf.html

[R23] 字符串替换
来源：http://dali.yj202588.top/Article/details/gt2dckhaesk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jianghu66.top/Article/details/gt2tdlscvzo.html

[R24] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gt2opcpkgjj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ecjkzsva.html

[R25] 去后缀 / 去前缀
来源：http://dali.hysaishi.cn/Article/details/gt2mxmqzlrp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rxaduwaw.html

[R26] 命令替换
来源：http://dali.9152youxi.cn/Article/details/gt2gjlgccwt.html

now=$(date +%F); echo "$now"
来源：http://dali.sweek.top/Article/details/gt2qztcpryd.html

[R27] 算术展开
来源：http://dali.hysaishi.cn/Article/details/gt2apguloin.html

echo $((1 + 2 * 3))
来源：http://dali.shuidangran.top/Article/details/gt2dxfnpoxm.html

[R28] 浮点运算
来源：http://dali.aibaodan.cn/Article/details/gt2yuubswph.html

echo "scale=2; 10/3" | bc
来源：http://dali.zycfv.cn/Article/details/gt2yygpwgfk.html

[R29] 定义函数
来源：http://dali.ehwqpu.com/Article/details/gt2qrtcwydv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hammf.cn/Article/details/gt2bxqptwar.html

[R30] 函数返回状态码
来源：http://dali.aizwys.cn/Article/details/gt2lohamtbm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.vqdsnc.cn/Article/details/gt2dxzuuwys.html

[R31] 局部变量
来源：http://dali.chenzaomai.com/Article/details/gt2jumdswkq.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2cwgvxyjx.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pppswklf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.andypj.xyz/Article/details/gt2yrqedgov.html

[R33] 捕获错误并提示行号
来源：http://dali.xziqi.cn/Article/details/gt2kmijyxpe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ppjwa.cn/Article/details/gt2qeiswsbl.html

[R34] 退出时清理
来源：http://dali.cdnleiting.top/Article/details/gt2xvwiopbw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dashuyun.cn/Article/details/gt2apaugdfw.html

[R35] 后台执行并等待
来源：http://dali.fzhhl.top/Article/details/gt2xgxkeboj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.haohaochexian.top/Article/details/gt2nqgzstiy.html

[R36] 并发执行多个任务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jfwidrpa.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shzxlz.cn/Article/details/gt2ixalgppk.html

[R37] 把输出赋给变量
来源：http://dali.ybcxt.top/Article/details/gt2nzchodmg.html

files=$(ls -1)
来源：http://dali.gzhubu.top/Article/details/gt2xppjuzef.html

[R38] 管道串联
来源：http://dali.zhongyouzk.top/Article/details/gt2lvdsteaw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nwbrower.top/Article/details/gt2psqskvgr.html

[R39] 重定向标准输出与错误
来源：http://dali.hysaishi.cn/Article/details/gt2mvhswvpb.html

cmd > out.log 2>&1
来源：http://dali.cheryme.top/Article/details/gt2xuhvykod.html

[R40] 追加写日志
来源：http://dali.guowangkeji.top/Article/details/gt2hclnftvx.html

echo "log" >> out.log
来源：http://dali.tian-w.cn/Article/details/gt2bqavorhk.html

[R41] 丢弃输出
来源：http://dali.shzxlz.cn/Article/details/gt2uacfgxvj.html

cmd >/dev/null 2>&1
来源：http://dali.jqgfzy.top/Article/details/gt2piifbzzp.html

[R42] 输入重定向
来源：http://dali.ydzc1.top/Article/details/gt2cpwsqebj.html

wc -l < a.txt
来源：http://dali.yj20258.top/Article/details/gt2ikvkyoho.html

[R43] 按名字查找文件
来源：http://dali.gotoacloud.top/Article/details/gt2smtjsclg.html

find . -name "*.log" -type f
来源：http://dali.wangdashe.top/Article/details/gt2iuolieod.html

[R44] 按修改时间查找
来源：http://dali.ppjwa.cn/Article/details/gt2myvdiqad.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyxplnp.html

[R45] 批量删除
来源：http://dali.cashguo.top/Article/details/gt2obldgmfj.html

find . -name "*.tmp" -delete
来源：http://dali.yanxiufei.cn/Article/details/gt2wyvjjxsp.html

[R46] 递归替换文件内容
来源：http://dali.jyoumei.cn/Article/details/gt2xnymlqlz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xinyue.icu/Article/details/gt2pceupatd.html

[R47] sed 单行替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2drrqjhne.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2lczswgoi.html

[R48] awk 取指定列
来源：http://dali.guowangkeji.top/Article/details/gt2hogyhadf.html

awk '{print $1, $3}' a.txt
来源：http://dali.xinyue.icu/Article/details/gt2ixztdfkr.html

[R49] awk 带条件
来源：http://dali.svipenyu.cn/Article/details/gt2yhnyelpa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangshuangyany.cn/Article/details/gt2cpavawkl.html

[R50] awk 求和
来源：http://dali.hysaishi.cn/Article/details/gt2exksouyr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2idjecitq.html

[R51] 排序去重取前几
来源：http://dali.chenlongwang.top/Article/details/gt2xfhrkdqs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yangfankeji.com/Article/details/gt2jliqquye.html

[R52] 统计行数
来源：http://dali.yueranfly.top/Article/details/gt2jusnzveq.html

wc -l a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2rdnfrrqb.html

[R53] 查看文件头与实时尾
来源：http://dali.hysaishi.cn/Article/details/gt2oelsljjl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ybcxt.top/Article/details/gt2groptfye.html

[R54] 比较两个文件
来源：http://dali.aibaodan.cn/Article/details/gt2prevvgdy.html

diff a.txt b.txt
来源：http://dali.aibaodan.cn/Article/details/gt2fdtvyoov.html

[R55] 压缩与解压
来源：http://dali.snrcjt.cn/Article/details/gt2jvlbihtr.html


<!-- 参考信息 -->