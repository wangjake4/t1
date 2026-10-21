代发 wailian999

);
来源：http://dali.haohaochexian.top/Article/details/gtcfckuhmc.html

[Q03] 增加列
来源：http://dali.yueranfly.top/Article/details/gtelttdpsv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pengpengdd.cyou/Article/details/gttmrpeknt.html

[Q04] 修改列类型
来源：http://dali.tanke756.top/Article/details/gtcczeiouq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.mhx1999.top/Article/details/gtyktwqbib.html

[Q05] 重命名列
来源：http://dali.vqdsnc.cn/Article/details/gtwlmaqjkw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sweek.top/Article/details/gtyerojgmr.html

[Q06] 删除列
来源：http://dali.gzhubu.top/Article/details/gtujupuejv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xylfe.cn/Article/details/gtnnkrddyk.html

[Q07] 删除表
来源：http://dali.vqdsnc.cn/Article/details/gtvbdnmavu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yonumen.top/Article/details/gtearlltrc.html

[Q08] 创建普通索引
来源：http://dali.ivvv.top/Article/details/gtlnzxhrpo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gtxgmqepcx.html

[Q09] 创建唯一索引
来源：http://dali.zycfv.cn/Article/details/gtqldhnxip.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gtwwazghzm.html

[Q10] 插入单行
来源：http://dali.hywenlv.cn/Article/details/gtanhrbrin.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.redwolf501.top/Article/details/gtnbkgruaz.html

[Q11] 一次插入多行
来源：http://dali.hysaishi.cn/Article/details/gtuctcgggi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aibaodan.cn/Article/details/gtlcnnnddx.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangtech.top/Article/details/gtwoojhudj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yangfankeji.com/Article/details/gtdmiubjpa.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj20258.top/Article/details/gtceqpusew.html

[Q13] 忽略重复插入
来源：http://dali.cqqwz.cn/Article/details/gtdptsvrjg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmycvkkjw.html

[Q14] 存在则更新（upsert）
来源：http://dali.ybcxt.top/Article/details/gtbtxbfxxz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.mhx1999.top/Article/details/gtqbrfhnwm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmoywtavg.html

[Q15] 查询全部
来源：http://dali.fengsongda.top/Article/details/gtsyehfumy.html

SELECT * FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtubyqfpag.html

[Q16] 查询指定列
来源：http://dali.yuxming.cn/Article/details/gtkywkomyk.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtktszbjeo.html

[Q17] 条件查询
来源：http://dali.yvedp.cn/Article/details/gtyyjxpwic.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xziqi.cn/Article/details/gtgbyvvdyj.html

[Q18] 模糊匹配
来源：http://dali.quarkkingdee.top/Article/details/gtqcnbktcd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ppjwa.cn/Article/details/gtpychhqag.html

[Q19] 范围查询
来源：http://dali.sxryk.cn/Article/details/gtdgukgxle.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.daria6918.cn/Article/details/gtrimhkpbc.html

[Q20] IN 列表
来源：http://dali.9152youxi.cn/Article/details/gtmhhagfsn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zdqjudy.top/Article/details/gtogadbsmc.html

[Q21] 空值判断
来源：http://dali.snrcjt.cn/Article/details/gtobrqgfng.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hysaishi.cn/Article/details/gtfcjhcadq.html

[Q22] 排序
来源：http://dali.guannengcc.top/Article/details/gtrwsnkfxj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shuidangran.top/Article/details/gtsidbyabv.html

[Q23] 分页
来源：http://dali.shzxlz.cn/Article/details/gtwpuadppr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xziqi.cn/Article/details/gtyzksrkaz.html

[Q24] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaamobeat.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtysnclsde.html

[Q25] 只取前 N 条
来源：http://dali.hnqzz.top/Article/details/gtzuntqrjf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.quarkkingdee.top/Article/details/gtvzvqnkep.html

[Q26] 计数
来源：http://dali.nanxinkj.top/Article/details/gtwhyxgjrq.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtapxhkfgh.html

[Q27] 条件计数
来源：http://dali.yonumen.top/Article/details/gtjhliikav.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj202588.top/Article/details/gtxbmcfqko.html

[Q28] 求和与平均
来源：http://dali.xylfe.cn/Article/details/gtnxhkrfzo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtwezqamyg.html

[Q29] 最大最小值
来源：http://dali.pycfn.com/Article/details/gtrjmuqjri.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtnppyymrs.html

[Q30] 分组统计
来源：http://dali.sufxvd.cn/Article/details/gtzpzoiipe.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gtzraadavz.html

[Q31] 分组后过滤
来源：http://dali.hfpthk.cn/Article/details/gtdlwwmkxo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jyoumei.cn/Article/details/gtyylvylmg.html

[Q32] 分组拼接字符串
来源：http://dali.yuxming.cn/Article/details/gtwufzptft.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gtednqcvpp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sweek.top/Article/details/gtxudbknlf.html

[Q33] 多列分组
来源：http://dali.shangyingyoupin.top/Article/details/gtrghbfhvn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.kuanghao11.cn/Article/details/gtzxmmntim.html

[Q34] 每组取第一条
来源：http://dali.xuanzx.com/Article/details/gtpftjxyev.html

SELECT * FROM (
来源：http://dali.fzhhl.top/Article/details/gtdmauhctw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dashuyun.cn/Article/details/gtjtcedqug.html

) t WHERE rn = 1;
来源：http://dali.pycfn.com/Article/details/gthrplnpmo.html

[Q35] 内连接
来源：http://dali.wangshuangyany.cn/Article/details/gtunilbadp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gogol.net.cn/Article/details/gtsublftpf.html

[Q36] 左连接
来源：http://dali.xuanzx.com/Article/details/gtzjndwfno.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gtsnxifjsr.html

[Q37] 右连接
来源：http://dali.wangdashe.top/Article/details/gtxooyxncm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yangfankeji.com/Article/details/gtxqsogdds.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sxryk.cn/Article/details/gtbqrbxehf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.pengpengdd.cyou/Article/details/gtjitigcrw.html

[Q39] 自连接（查上下级）
来源：http://dali.nwbrower.top/Article/details/gtgknkzxcb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.c1oappe.top/Article/details/gtloydzulp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gtpnityjzy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.havefunace.top/Article/details/gtqvrchdtc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.andypj.xyz/Article/details/gtbijyffgy.html

[Q41] 多表连接
来源：http://dali.zdqjudy.top/Article/details/gtvjgdxenr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xziqi.cn/Article/details/gtehsevzgk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvuderrul.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.fzhhl.top/Article/details/gtoiojhasw.html

[Q42] 连接条件附加过滤
来源：http://dali.mhx1999.top/Article/details/gtgfmkixpe.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xylfe.cn/Article/details/gtwsqdkflr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xinyue.icu/Article/details/gtbkvtvicb.html

[Q43] 标量子查询
来源：http://dali.fengsongda.top/Article/details/gtlnpfhycd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ybcxt.top/Article/details/gtomnuadsi.html

[Q44] IN 子查询
来源：http://dali.xinyue.icu/Article/details/gtizffevup.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yonumen.top/Article/details/gtrppvplab.html

[Q45] EXISTS 判断存在
来源：http://dali.zhoulong.xyz/Article/details/gtvdvyzgin.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.vqdsnc.cn/Article/details/gthabrrfdk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jyoumei.cn/Article/details/gtdhhuhyfa.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gtcdreumfk.html

[Q47] 与平均值比较
来源：http://dali.zhixingplan.top/Article/details/gtmyjsvitp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.dianchejie.cn/Article/details/gtajotonuc.html

[Q48] CTE 公用表表达式
来源：http://dali.daxiang520.top/Article/details/gtmhnehbrx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jqgufenzy.top/Article/details/gtlrclbnvi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.quarkkingdee.top/Article/details/gtfogunxxd.html

[Q49] 更新单行
来源：http://dali.0kj1m.cn/Article/details/gtclpzjhkt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gtbzvimdel.html

[Q50] 批量更新
来源：http://dali.ivvv.top/Article/details/gtnybkbbgt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.fengsongda.top/Article/details/gtzmktorga.html

[Q51] 用子查询更新
来源：http://dali.hongshengwenyu.top/Article/details/gtjugemejm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.wangdashe.top/Article/details/gtesimxmdm.html

[Q52] 删除指定行
来源：http://dali.gogol.net.cn/Article/details/gtajelatbp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.dashuyun.cn/Article/details/gtrjlvdrsk.html

[Q53] 按条件删除
来源：http://dali.feifeiyinyue.top/Article/details/gtpbizihwf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yongpay.top/Article/details/gtzursxcho.html

[Q54] 清空表
来源：http://dali.daria6918.cn/Article/details/gtkepwsvgv.html

TRUNCATE TABLE logs;
来源：http://dali.hongshengwenyu.top/Article/details/gtutjswfxg.html

[Q55] 排名（并列占位）
来源：http://dali.havefunace.top/Article/details/gtdcfpxqrf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yuxming.cn/Article/details/gtcpxdmthw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.svipenyu.cn/Article/details/gtlzktvybc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.dashuyun.cn/Article/details/gtdfibqolq.html

[Q57] 行号
来源：http://dali.redwolf501.top/Article/details/gtotpfufna.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sysykeji.top/Article/details/gtsntouqde.html

[Q58] 累计求和
来源：http://dali.jqgfzy.top/Article/details/gtbwvbhsds.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shuidangran.top/Article/details/gteedjdxui.html

[Q59] 分组内累计
来源：http://dali.cqqwz.cn/Article/details/gtduosvkrb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtouxtabit.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gtfazqlond.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zdqjudy.top/Article/details/gtenvptetz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtylamgtda.html

[Q61] 移动平均
来源：http://dali.jinqigfzy.top/Article/details/gtmkxiidpg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtrrkjouda.html

[Q62] 分组占比
来源：http://dali.bjfxy.top/Article/details/gtipuuuueh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gtzbmwotbk.html

[Q63] 开启事务
来源：http://dali.ivvv.top/Article/details/gtjkjzulhi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqasbeqz.html

[Q64] 提交事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcljoers.html

COMMIT;
来源：http://dali.316326.xyz/Article/details/gtautchmkc.html

[Q65] 回滚事务
来源：http://dali.jianghu66.top/Article/details/gtakkfzmqd.html

ROLLBACK;
来源：http://dali.zycfv.cn/Article/details/gthemezmuq.html

[Q66] 行锁查询
来源：http://dali.pengpengdd.cyou/Article/details/gtlcchnlkl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cdnleiting.top/Article/details/gtszaqvyre.html

[Q67] 设置隔离级别
来源：http://dali.nwbrower.top/Article/details/gtfqcrhjan.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hysaishi.cn/Article/details/gtehlqqyxf.html

[Q68] 保存点
来源：http://dali.ybcxt.top/Article/details/gthhauzzct.html

SAVEPOINT sp1;
来源：http://dali.yangfankeji.com/Article/details/gteyzxpxvd.html

ROLLBACK TO sp1;
来源：http://dali.zhongyouzk.top/Article/details/gtsxiaarwj.html

[Q69] 查看执行计划
来源：http://dali.yj20258.top/Article/details/gtkuewgvvv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hongshengwenyu.top/Article/details/gtdqqojjwx.html

[Q70] 更新统计信息
来源：http://dali.gaohongyu789.top/Article/details/gtmivoyilb.html

ANALYZE TABLE users;
来源：http://dali.c1oappe.top/Article/details/gthwwlxwep.html

[Q71] 查看建表语句
来源：http://dali.nwbrower.top/Article/details/gttpycbick.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xinyue.icu/Article/details/gtlzhqiqmg.html

[Q72] 查看索引
来源：http://dali.yvedp.cn/Article/details/gtkzytuomr.html

SHOW INDEX FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gttpqiroyq.html

[Q73] 查看表状态
来源：http://dali.havefunace.top/Article/details/gtsyoaywzm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cucudq.cn/Article/details/gtzqfnpeoe.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gtvqvnewix.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pengpengdd.cyou/Article/details/gtnclpoimq.html

[Q75] 日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtivzpepso.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtqfxgnkgc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcteqtxp.html

[Q76] 按天统计
来源：http://dali.guowangkeji.top/Article/details/gtxkywnsre.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangdashe.top/Article/details/gtaqinskgm.html

[Q77] 时间加减
来源：http://dali.hammf.cn/Article/details/gtbmlollkl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.smart0.xyz/Article/details/gtkgfsxjwy.html

[Q78] 当前时间
来源：http://dali.shuidangran.top/Article/details/gtpmnfupru.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hammf.cn/Article/details/gtqrbcdloz.html

[Q79] 字符串拼接
来源：http://dali.xuanzx.com/Article/details/gtmdzaapjv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgfzy.top/Article/details/gtosyaiuhl.html

[Q80] 字符串截取
来源：http://dali.nanxinkj.top/Article/details/gtxblcprrh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtzghakmmb.html

[Q81] 字符串替换
来源：http://dali.pengpengdd.cyou/Article/details/gtftnjhbja.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.mhx1999.top/Article/details/gtdpvelpsp.html

[Q82] 字符长度与字节长度
来源：http://dali.jlsjyb.cn/Article/details/gtoxusfdpa.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtrbsxcupt.html

[Q83] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gtlfimyaod.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtknvlpgue.html

[Q84] 去除首尾空格
来源：http://dali.xuanzx.com/Article/details/gtzzlpwxzn.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtranrnezt.html

[Q85] 数值取整
来源：http://dali.chenzaomai.com/Article/details/gtjzsbuigh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yvedp.cn/Article/details/gtpfrodsks.html

[Q86] 读取 JSON 字段
来源：http://dali.jinghuilouyu.cn/Article/details/gtiomkrfen.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jianghu66.top/Article/details/gtgwhkuprh.html

[Q87] JSON 字段做条件
来源：http://dali.zhengqikj.top/Article/details/gtasfphkxz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sufxvd.cn/Article/details/gtsgikakls.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhoulong.xyz/Article/details/gtshikwcrp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jyoumei.cn/Article/details/gttdksymot.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.guannengcc.top/Article/details/gtgkxgtegl.html

[Q89] 判断表是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtrsewkhba.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jianghu66.top/Article/details/gtgfnomljk.html

[Q90] 生成序号列
来源：http://dali.havefunace.top/Article/details/gtrcgtlskk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nanxinkj.top/Article/details/gtubiuknus.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtytktwmoy.html

R. Bash 专题
来源：http://dali.yueranfly.top/Article/details/gtqbjygrls.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtrufelezk.html

[R01] shebang 与严格模式
来源：http://dali.yj202588.top/Article/details/gtzghilavk.html

#!/usr/bin/env bash
来源：http://dali.cucudq.cn/Article/details/gtcvtvtmzz.html

set -euo pipefail
来源：http://dali.nanxuanxn.top/Article/details/gttjtmcoiz.html

[R02] 变量赋值与使用
来源：http://dali.sxryk.cn/Article/details/gtzyluurzt.html

name="Tom"; echo "$name"
来源：http://dali.c1oappe.top/Article/details/gtxsoeviaz.html

[R03] 只读变量
来源：http://dali.aizwys.cn/Article/details/gtvsuwuirv.html

readonly PI=3.14
来源：http://dali.nwbrower.top/Article/details/gtckxewbrk.html

[R04] 位置参数
来源：http://dali.shzxlz.cn/Article/details/gtdteedpmj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sweek.top/Article/details/gtlhyugiku.html

[R05] 参数默认值
来源：http://dali.chenlongwang.top/Article/details/gtpldkarhx.html

name="${1:-default}"
来源：http://dali.hnxiangtu.top/Article/details/gtoizveubq.html

[R06] 判断命令是否存在
来源：http://dali.hfpthk.cn/Article/details/gtbkqvfqcl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gtgrdtzkml.html

[R07] if 判断文件
来源：http://dali.yj202588.top/Article/details/gtglvtvyoh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jianghu66.top/Article/details/gtyfkldjht.html

[R08] 数值比较
来源：http://dali.xinyue.icu/Article/details/gtsmngsosv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.birdmap.top/Article/details/gtlykvjhtm.html

[R09] 字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtglensxcs.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yangfankeji.com/Article/details/gtqfbcchzr.html

[R10] 正则匹配
来源：http://dali.hysaishi.cn/Article/details/gtfjeykhia.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258888.top/Article/details/gtfkppthyu.html

[R11] case 多分支
来源：http://dali.sweek.top/Article/details/gtstmbzvrt.html

case "$1" in
来源：http://dali.cucudq.cn/Article/details/gtnjvznkiz.html

start) echo "启动" ;;
来源：http://dali.hysaishi.cn/Article/details/gtgsctchqw.html

stop)  echo "停止" ;;
来源：http://dali.dianchejie.cn/Article/details/gtaisdqhnm.html

*)     echo "未知命令" ;;
来源：http://dali.xziqi.cn/Article/details/gtqotwlbru.html

esac
来源：http://dali.yuanzhike.top/Article/details/gtyqnzoxrd.html

[R12] for 遍历文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlytmiks.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gtfvfgmcak.html

[R13] for 计数循环
来源：http://dali.sweek.top/Article/details/gtqisymcup.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gtbdrgqjfq.html

[R14] C 风格 for
来源：http://dali.yongpay.top/Article/details/gtjfubjndi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gtorgtgrmm.html

[R15] while 逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtwothjrdi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.birdmap.top/Article/details/gtzuivqvny.html

[R16] until 等待条件
来源：http://dali.shuidangran.top/Article/details/gtgerxnnsf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gtgzitqazt.html

[R17] 数组定义与取值
来源：http://dali.bjfxy.top/Article/details/gtzcjtprph.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.dianchejie.cn/Article/details/gtdkoudfmv.html

[R18] 遍历数组
来源：http://dali.zhoulong.xyz/Article/details/gtysbkjidz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ehwqpu.com/Article/details/gtihfyoywq.html

[R19] 数组长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkveysdkw.html

echo "${#arr[@]}"
来源：http://dali.jinqigufen.top/Article/details/gtzvvcfnfb.html

[R20] 关联数组（字典）
来源：http://dali.fzhhl.top/Article/details/gtwysgonxz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hfpthk.cn/Article/details/gthxputedw.html

[R21] 字符串长度
来源：http://dali.yvedp.cn/Article/details/gtuscxmdnv.html

echo "${#s}"
来源：http://dali.hnqzz.top/Article/details/gtwkapovsv.html

[R22] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gtfcpgpoha.html

echo "${s:0:5}"
来源：http://dali.yvedp.cn/Article/details/gtxyyvytpv.html

[R23] 字符串替换
来源：http://dali.shuidangran.top/Article/details/gtcquydyvh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.c1oappe.top/Article/details/gtgqcckqew.html

[R24] 大小写转换
来源：http://dali.hfpthk.cn/Article/details/gtdfpvdeaf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gotoacloud.top/Article/details/gtvjbctwdi.html

[R25] 去后缀 / 去前缀
来源：http://dali.guowangkeji.top/Article/details/gtbbjgoesv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cashguo.top/Article/details/gtyvpcwgco.html

[R26] 命令替换
来源：http://dali.tianlin.xyz/Article/details/gtpkgblmmx.html

now=$(date +%F); echo "$now"
来源：http://dali.yj20258888.top/Article/details/gtxgmlztco.html

[R27] 算术展开
来源：http://dali.yonumen.top/Article/details/gtjjvdkkra.html

echo $((1 + 2 * 3))
来源：http://dali.sufxvd.cn/Article/details/gtkwoszgef.html

[R28] 浮点运算
来源：http://dali.snrcjt.cn/Article/details/gttawpthqo.html

echo "scale=2; 10/3" | bc
来源：http://dali.cucudq.cn/Article/details/gtfjufmrvy.html

[R29] 定义函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumwhjthx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fengsongda.top/Article/details/gtgunxxivv.html

[R30] 函数返回状态码
来源：http://dali.iojbl.cn/Article/details/gtyxrglvsc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nanxinkj.top/Article/details/gtuugvztdb.html

[R31] 局部变量
来源：http://dali.kuanghao11.cn/Article/details/gthwigfrkf.html

f() { local x=1; echo "$x"; }
来源：http://dali.smart0.xyz/Article/details/gtetctdgzt.html

[R32] 参数个数校验
来源：http://dali.xylfe.cn/Article/details/gtjpwvtuev.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezghddgo.html

[R33] 捕获错误并提示行号
来源：http://dali.hywenlv.cn/Article/details/gteeejfubd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yanxiufei.cn/Article/details/gtfuxzedih.html

[R34] 退出时清理
来源：http://dali.smart0.xyz/Article/details/gtxxmwqbrr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gtkrqvztfm.html

[R35] 后台执行并等待
来源：http://dali.fzhhl.top/Article/details/gtiftnwhln.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtruvckajv.html

[R36] 并发执行多个任务
来源：http://dali.redwolf501.top/Article/details/gtinqzmiqx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhongyouzk.top/Article/details/gtswuzccgb.html

[R37] 把输出赋给变量
来源：http://dali.pycfn.com/Article/details/gtiemcbvas.html

files=$(ls -1)
来源：http://dali.zhixingplan.top/Article/details/gtorajyypn.html

[R38] 管道串联
来源：http://dali.jianghu66.top/Article/details/gttsbymqvf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhengqikj.top/Article/details/gtavkpoyuq.html

[R39] 重定向标准输出与错误
来源：http://dali.dashuyun.cn/Article/details/gtmwgmvdpz.html

cmd > out.log 2>&1
来源：http://dali.yj20258888.top/Article/details/gtzfsfuwvn.html

[R40] 追加写日志
来源：http://dali.redwolf501.top/Article/details/gthmhrseth.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gtiwhbezfx.html

[R41] 丢弃输出
来源：http://dali.hnxiangtu.top/Article/details/gtvqmqcixa.html

cmd >/dev/null 2>&1
来源：http://dali.xinyue.icu/Article/details/gtjpjflvzs.html

[R42] 输入重定向
来源：http://dali.iojbl.cn/Article/details/gtgnrlurfu.html

wc -l < a.txt
来源：http://dali.tanke756.top/Article/details/gtzddgjgiv.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtyeivckvc.html

find . -name "*.log" -type f
来源：http://dali.daria6918.cn/Article/details/gtzkenxgpk.html

[R44] 按修改时间查找
来源：http://dali.9152youxi.cn/Article/details/gtpgxrctdo.html

find . -mtime -7 -type f
来源：http://dali.chenlongwang.top/Article/details/gtfzjgzkqu.html

[R45] 批量删除
来源：http://dali.mhx1999.top/Article/details/gtkspqmwfj.html

find . -name "*.tmp" -delete
来源：http://dali.sysykeji.top/Article/details/gtuihquoqe.html

[R46] 递归替换文件内容
来源：http://dali.yuanzhike.top/Article/details/gtubjefahm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhongyouzk.top/Article/details/gtmncxjgai.html

[R47] sed 单行替换
来源：http://dali.ydzc1.top/Article/details/gtdqzzewsq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xylfe.cn/Article/details/gtbwgmbgie.html

[R48] awk 取指定列
来源：http://dali.kuanghao11.cn/Article/details/gtkewcxjgw.html

awk '{print $1, $3}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtkisesrsc.html

[R49] awk 带条件
来源：http://dali.chenlongwang.top/Article/details/gtzbczcdeh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xziqi.cn/Article/details/gtxnusmfiy.html

[R50] awk 求和
来源：http://dali.ydzc1.top/Article/details/gtfvwditwq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gthhnepckj.html

[R51] 排序去重取前几
来源：http://dali.daxiang520.top/Article/details/gtbghleoxp.html


<!-- 参考信息 -->