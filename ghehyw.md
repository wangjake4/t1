代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sxryk.cn/Article/details/gtziyptojf.html

user_id INT NOT NULL,
来源：http://dali.tanke756.top/Article/details/gtasiqmhdx.html

amount DECIMAL(10, 2),
来源：http://dali.nanxinkj.top/Article/details/gtpimszfzl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.aizwys.cn/Article/details/gtorlzawsm.html

);
来源：http://dali.chenjidiqi.icu/Article/details/gttfjshwvf.html

[Q03] 增加列
来源：http://dali.cheryme.top/Article/details/gtfokyjhch.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sweek.top/Article/details/gtqyzjtzqt.html

[Q04] 修改列类型
来源：http://dali.hnqzz.top/Article/details/gtfyqrxedh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxqttify.html

[Q05] 重命名列
来源：http://dali.haohaochexian.top/Article/details/gtypqymvlt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhiwuduotai.top/Article/details/gtgquxvfdz.html

[Q06] 删除列
来源：http://dali.daria6918.cn/Article/details/gtupusylqy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhiwuduotai.top/Article/details/gtfpxhckbv.html

[Q07] 删除表
来源：http://dali.xziqi.cn/Article/details/gtgcaycbhg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yonumen.top/Article/details/gtqnwjmuzm.html

[Q08] 创建普通索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtodxsxy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gtrzwobjsl.html

[Q09] 创建唯一索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukiqxgmv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gtufussgcw.html

[Q10] 插入单行
来源：http://dali.nwbrower.top/Article/details/gtbifoiuop.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.bjfxy.top/Article/details/gtezgrmjlo.html

[Q11] 一次插入多行
来源：http://dali.shzxlz.cn/Article/details/gtpklogubw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gtcuyiiuyx.html

[Q12] 插入后取自增 ID
来源：http://dali.0kj1m.cn/Article/details/gtsqapulwe.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yj20258.top/Article/details/gtgvhhshqe.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hywenlv.cn/Article/details/gtjjuyjlbq.html

[Q13] 忽略重复插入
来源：http://dali.hammf.cn/Article/details/gtitfskjqr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hfpthk.cn/Article/details/gtvizeglku.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuanzx.com/Article/details/gtriythqmn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqmrthbx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gogol.net.cn/Article/details/gtsroanzxh.html

[Q15] 查询全部
来源：http://dali.jianghu66.top/Article/details/gtjotaezcv.html

SELECT * FROM users;
来源：http://dali.guannengcc.top/Article/details/gtsxnpfnwe.html

[Q16] 查询指定列
来源：http://dali.wangdashe.top/Article/details/gthnjewlva.html

SELECT id, name FROM users;
来源：http://dali.yvedp.cn/Article/details/gtzvoqteeg.html

[Q17] 条件查询
来源：http://dali.c1oappe.top/Article/details/gtlymdqtpw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gotoacloud.top/Article/details/gtjmfxiixz.html

[Q18] 模糊匹配
来源：http://dali.ehwqpu.com/Article/details/gtnmkgcebq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj20258888.top/Article/details/gtkbinqfkc.html

[Q19] 范围查询
来源：http://dali.guowangkeji.top/Article/details/gtmpvddvlc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.daxiang520.top/Article/details/gtxqyukfxc.html

[Q20] IN 列表
来源：http://dali.bjfxy.top/Article/details/gtdcivhcmt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jiagoushi.top/Article/details/gtyvezmjve.html

[Q21] 空值判断
来源：http://dali.gzhubu.top/Article/details/gtniwognni.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jiagoushi.top/Article/details/gtovxhsqpn.html

[Q22] 排序
来源：http://dali.c1oappe.top/Article/details/gtrpfhxtyt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gzhubu.top/Article/details/gtpoackxee.html

[Q23] 分页
来源：http://dali.zhiwuduotai.top/Article/details/gtoahlgshu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhiwuduotai.top/Article/details/gtmuhjhcof.html

[Q24] 去重
来源：http://dali.cashguo.top/Article/details/gttgbnxczh.html

SELECT DISTINCT city FROM users;
来源：http://dali.cashguo.top/Article/details/gtobcujink.html

[Q25] 只取前 N 条
来源：http://dali.jqgfzy.top/Article/details/gtvdreoxth.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxrsuaiml.html

[Q26] 计数
来源：http://dali.jinqigufen.top/Article/details/gtlmdnderg.html

SELECT COUNT(*) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtfovaengm.html

[Q27] 条件计数
来源：http://dali.fengsongda.top/Article/details/gtbygnpzpp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sweek.top/Article/details/gtshcgmqlr.html

[Q28] 求和与平均
来源：http://dali.yj202588.top/Article/details/gtpzgxyffe.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtzfecwzee.html

[Q29] 最大最小值
来源：http://dali.sysykeji.top/Article/details/gtjxsjcrsv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj202588.top/Article/details/gtpkwvtokb.html

[Q30] 分组统计
来源：http://dali.guowangkeji.top/Article/details/gtoxchuodh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gttykrrbds.html

[Q31] 分组后过滤
来源：http://dali.jlsjyb.cn/Article/details/gtabdyaxda.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cashguo.top/Article/details/gtakrsnqst.html

[Q32] 分组拼接字符串
来源：http://dali.hnqzz.top/Article/details/gthixfqgby.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gtfudchehv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.kuanghao11.cn/Article/details/gtxkcqwacf.html

[Q33] 多列分组
来源：http://dali.kuanghao11.cn/Article/details/gtyufysgen.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jyoumei.cn/Article/details/gtpnxwcfvd.html

[Q34] 每组取第一条
来源：http://dali.jyoumei.cn/Article/details/gtmclpkgtg.html

SELECT * FROM (
来源：http://dali.jinqigufen.top/Article/details/gtujrmcimh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.iojbl.cn/Article/details/gtdqylwtwm.html

) t WHERE rn = 1;
来源：http://dali.jianghu66.top/Article/details/gtrqolbnav.html

[Q35] 内连接
来源：http://dali.hysaishi.cn/Article/details/gtfozkduny.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtbnzrfktj.html

[Q36] 左连接
来源：http://dali.yuxming.cn/Article/details/gtzzwbqqjt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yongpay.top/Article/details/gtmwxfhsba.html

[Q37] 右连接
来源：http://dali.zhiwuduotai.top/Article/details/gtlhuzvryl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nanxuanxn.top/Article/details/gtfpzjxbtk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yonumen.top/Article/details/gtvdkraszr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cdnleiting.top/Article/details/gtvruzgsur.html

[Q39] 自连接（查上下级）
来源：http://dali.cheryme.top/Article/details/gtjxoznjrq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhiwuduotai.top/Article/details/gtxmwllirs.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nwbrower.top/Article/details/gtmowadtwj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhixingplan.top/Article/details/gtxldpgjyb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinqigufen.top/Article/details/gtgstfqclk.html

[Q41] 多表连接
来源：http://dali.yj202588.top/Article/details/gteazaavta.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daria6918.cn/Article/details/gtfqinhkxm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gzhubu.top/Article/details/gtanukfdzg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ybcxt.top/Article/details/gtsxiksabr.html

[Q42] 连接条件附加过滤
来源：http://dali.hnxiangtu.top/Article/details/gtizsimtrc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.bjfxy.top/Article/details/gtegpailug.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jianghu66.top/Article/details/gtlkokwnxa.html

[Q43] 标量子查询
来源：http://dali.cucudq.cn/Article/details/gtwogpzpys.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.svipenyu.cn/Article/details/gtphgdxnxs.html

[Q44] IN 子查询
来源：http://dali.andypj.xyz/Article/details/gtkjmjmplz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gzhubu.top/Article/details/gtvvkovjjq.html

[Q45] EXISTS 判断存在
来源：http://dali.ivvv.top/Article/details/gtmmfxdnlu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gtoyqymkkc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj20258.top/Article/details/gtansxtcoq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gtcgkjaajp.html

[Q47] 与平均值比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzuosodc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwycwvtkk.html

[Q48] CTE 公用表表达式
来源：http://dali.nanxuanxn.top/Article/details/gtatesooxn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.guannengcc.top/Article/details/gtdkfbbagu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.pengpengdd.cyou/Article/details/gtzuzzltbs.html

[Q49] 更新单行
来源：http://dali.shuidangran.top/Article/details/gtmcmqyzzs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gzhubu.top/Article/details/gtgesxpijp.html

[Q50] 批量更新
来源：http://dali.shuidangran.top/Article/details/gtmtymlqvn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigufen.top/Article/details/gtolgkqgbq.html

[Q51] 用子查询更新
来源：http://dali.redwolf501.top/Article/details/gtbmbgnvma.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.dianchejie.cn/Article/details/gtjbbpuayb.html

[Q52] 删除指定行
来源：http://dali.shzxlz.cn/Article/details/gtgnxrmkfm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhixingplan.top/Article/details/gtnunkhfnc.html

[Q53] 按条件删除
来源：http://dali.nanxinkj.top/Article/details/gtpwgstiac.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhiwuduotai.top/Article/details/gtbbgdtfnm.html

[Q54] 清空表
来源：http://dali.ybcxt.top/Article/details/gtbjfzcuam.html

TRUNCATE TABLE logs;
来源：http://dali.316326.xyz/Article/details/gtwehjshnp.html

[Q55] 排名（并列占位）
来源：http://dali.andypj.xyz/Article/details/gtdmoszcsx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtioptzffq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenjidiqi.icu/Article/details/gtxledcdlo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tanke756.top/Article/details/gtdtkckxku.html

[Q57] 行号
来源：http://dali.hammf.cn/Article/details/gtcouhlfks.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cheryme.top/Article/details/gtuawvfakm.html

[Q58] 累计求和
来源：http://dali.nwbrower.top/Article/details/gttlpposcm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtxwdycghi.html

[Q59] 分组内累计
来源：http://dali.jqgufenzy.top/Article/details/gtbmthsiog.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtkrkjqyaw.html

[Q60] 取上一行 / 下一行
来源：http://dali.jlsjyb.cn/Article/details/gtdkwzkmkh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gaohongyu789.top/Article/details/gtlpojpqse.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtdxnuriaz.html

[Q61] 移动平均
来源：http://dali.jinqigfzy.top/Article/details/gtudvzbzps.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtfbopsbrr.html

[Q62] 分组占比
来源：http://dali.yvedp.cn/Article/details/gthxwoyail.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gtepnzamne.html

[Q63] 开启事务
来源：http://dali.fzhhl.top/Article/details/gtkggmwiif.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tian-w.cn/Article/details/gtidtxyrej.html

[Q64] 提交事务
来源：http://dali.quarkkingdee.top/Article/details/gtpgcratub.html

COMMIT;
来源：http://dali.yuxming.cn/Article/details/gtarjuecdt.html

[Q65] 回滚事务
来源：http://dali.xuanzx.com/Article/details/gtlolwxpyh.html

ROLLBACK;
来源：http://dali.hammf.cn/Article/details/gthlvswfla.html

[Q66] 行锁查询
来源：http://dali.xylfe.cn/Article/details/gtgeqzdoeo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.kuanghao11.cn/Article/details/gtattyfvcs.html

[Q67] 设置隔离级别
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzvrvhbw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pycfn.com/Article/details/gtjhmpyoxe.html

[Q68] 保存点
来源：http://dali.hysaishi.cn/Article/details/gtrqduqyaz.html

SAVEPOINT sp1;
来源：http://dali.gzhubu.top/Article/details/gtpvfoidvb.html

ROLLBACK TO sp1;
来源：http://dali.feifeiyinyue.top/Article/details/gtsldvyqbt.html

[Q69] 查看执行计划
来源：http://dali.zdqjudy.top/Article/details/gtfpayzxfh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.pengpengdd.cyou/Article/details/gtgihwpyzy.html

[Q70] 更新统计信息
来源：http://dali.fengsongda.top/Article/details/gtgrumfqcl.html

ANALYZE TABLE users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtarlvieou.html

[Q71] 查看建表语句
来源：http://dali.bjfxy.top/Article/details/gtdszvsjwb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhoulong.xyz/Article/details/gtkrvqbzoa.html

[Q72] 查看索引
来源：http://dali.yangfankeji.com/Article/details/gtumllhgsj.html

SHOW INDEX FROM users;
来源：http://dali.aizwys.cn/Article/details/gtuaxbwgjd.html

[Q73] 查看表状态
来源：http://dali.daxiang520.top/Article/details/gtzwjuvdux.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.mhx1999.top/Article/details/gthreypebr.html

[Q74] 强制使用索引
来源：http://dali.mhx1999.top/Article/details/gtpjxoenwa.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gzhubu.top/Article/details/gtjtthbqeo.html

[Q75] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtkqivecez.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtjffcxorj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.daria6918.cn/Article/details/gtejfvasma.html

[Q76] 按天统计
来源：http://dali.iojbl.cn/Article/details/gthmphtign.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinqigfzy.top/Article/details/gtijmqsnjg.html

[Q77] 时间加减
来源：http://dali.smart0.xyz/Article/details/gtsykirtml.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.andypj.xyz/Article/details/gtfdkgolga.html

[Q78] 当前时间
来源：http://dali.hammf.cn/Article/details/gtqjqrjvri.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgfzy.top/Article/details/gtzgcgbqei.html

[Q79] 字符串拼接
来源：http://dali.yonumen.top/Article/details/gttnhhuedy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenjidiqi.icu/Article/details/gtjspranxs.html

[Q80] 字符串截取
来源：http://dali.fzhhl.top/Article/details/gthdgllmdn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtaaokjxxp.html

[Q81] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gtpivzhglo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfelaubrb.html

[Q82] 字符长度与字节长度
来源：http://dali.feifeiyinyue.top/Article/details/gtllnjxczt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtgagpfjlu.html

[Q83] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gtxxslqhaf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtfrimcxro.html

[Q84] 去除首尾空格
来源：http://dali.chenjidiqi.icu/Article/details/gttkesxsqd.html

SELECT TRIM(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtizmdpdst.html

[Q85] 数值取整
来源：http://dali.0kj1m.cn/Article/details/gthgjoetxa.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cheryme.top/Article/details/gtdamvqpda.html

[Q86] 读取 JSON 字段
来源：http://dali.hywenlv.cn/Article/details/gtlxyzkkvk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.birdmap.top/Article/details/gtirmewnoa.html

[Q87] JSON 字段做条件
来源：http://dali.ehwqpu.com/Article/details/gtflxyvlwp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cdnleiting.top/Article/details/gtrkrbxqyl.html

[Q88] 行转列（条件聚合）
来源：http://dali.yuxming.cn/Article/details/gtyhezpjmz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cheryme.top/Article/details/gtzmmzamlq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpsmcfkz.html

[Q89] 判断表是否存在
来源：http://dali.cashguo.top/Article/details/gthixwfzwm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.fengsongda.top/Article/details/gtcbfnarkt.html

[Q90] 生成序号列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknozysnu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gotoacloud.top/Article/details/gtmcuckykx.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtnfyhkjak.html

R. Bash 专题
来源：http://dali.hnqzz.top/Article/details/gtkaamalgd.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtvrnfnsko.html

[R01] shebang 与严格模式
来源：http://dali.gotoacloud.top/Article/details/gtvglvbbrc.html

#!/usr/bin/env bash
来源：http://dali.hnxiangtu.top/Article/details/gtjkfpjzfs.html

set -euo pipefail
来源：http://dali.sxryk.cn/Article/details/gtueoecjhb.html

[R02] 变量赋值与使用
来源：http://dali.sxryk.cn/Article/details/gtiqlctsdq.html

name="Tom"; echo "$name"
来源：http://dali.chenlongwang.top/Article/details/gtmscfhbod.html

[R03] 只读变量
来源：http://dali.birdmap.top/Article/details/gtghtrhihu.html

readonly PI=3.14
来源：http://dali.zhongyouzk.top/Article/details/gtolplklie.html

[R04] 位置参数
来源：http://dali.bjfxy.top/Article/details/gtkywwodnk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cashguo.top/Article/details/gtioxbirof.html

[R05] 参数默认值
来源：http://dali.guowangkeji.top/Article/details/gtbaipvbkd.html

name="${1:-default}"
来源：http://dali.jlsjyb.cn/Article/details/gtgaxhaqsi.html

[R06] 判断命令是否存在
来源：http://dali.xziqi.cn/Article/details/gtebrmarqd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gtcwdarzge.html

[R07] if 判断文件
来源：http://dali.xinyue.icu/Article/details/gtxfpzksdq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj20258888.top/Article/details/gtwsmlchvi.html

[R08] 数值比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhjcftgo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tianlin.xyz/Article/details/gtfgzlpabd.html

[R09] 字符串比较
来源：http://dali.andypj.xyz/Article/details/gtdqgooncu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guowangkeji.top/Article/details/gtvcfrqlxm.html

[R10] 正则匹配
来源：http://dali.jlsjyb.cn/Article/details/gtiaciqeiw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fengsongda.top/Article/details/gtuszouble.html

[R11] case 多分支
来源：http://dali.yvedp.cn/Article/details/gtyylqbaka.html

case "$1" in
来源：http://dali.316326.xyz/Article/details/gtxzrcdqvu.html

start) echo "启动" ;;
来源：http://dali.andypj.xyz/Article/details/gtdsefwvcr.html

stop)  echo "停止" ;;
来源：http://dali.jinqigufen.top/Article/details/gtvhaxrlwi.html

*)     echo "未知命令" ;;
来源：http://dali.birdmap.top/Article/details/gtydfodkry.html

esac
来源：http://dali.cashguo.top/Article/details/gtiafpqama.html

[R12] for 遍历文件
来源：http://dali.nanxinkj.top/Article/details/gtrafshsgn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gotoacloud.top/Article/details/gtkyquzlmv.html

[R13] for 计数循环
来源：http://dali.bjfxy.top/Article/details/gtdvdxwdhd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtlyylirmv.html

[R14] C 风格 for
来源：http://dali.hywenlv.cn/Article/details/gtgaabzpxx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ehwqpu.com/Article/details/gtfsjzkzai.html

[R15] while 逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtxooznnyo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sysykeji.top/Article/details/gtecwxzbxr.html

[R16] until 等待条件
来源：http://dali.shzxlz.cn/Article/details/gtbzrrlhql.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gtjevyrwmc.html

[R17] 数组定义与取值
来源：http://dali.xylfe.cn/Article/details/gtawkwatig.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hfpthk.cn/Article/details/gthsyfemdr.html

[R18] 遍历数组
来源：http://dali.xylfe.cn/Article/details/gtsnvrehzw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jiagoushi.top/Article/details/gtfrpbqlky.html

[R19] 数组长度
来源：http://dali.yj20258.top/Article/details/gtltqddzwi.html

echo "${#arr[@]}"
来源：http://dali.daria6918.cn/Article/details/gtbhjoizou.html

[R20] 关联数组（字典）
来源：http://dali.jyoumei.cn/Article/details/gtpnqzjwht.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgfzy.top/Article/details/gtktpgydvr.html

[R21] 字符串长度
来源：http://dali.bjfxy.top/Article/details/gtabchzyxo.html

echo "${#s}"
来源：http://dali.hongshengwenyu.top/Article/details/gtxqafuzcu.html

[R22] 截取子串
来源：http://dali.sxryk.cn/Article/details/gtqxfslylr.html

echo "${s:0:5}"
来源：http://dali.birdmap.top/Article/details/gtvrwysfiw.html

[R23] 字符串替换
来源：http://dali.chenzaomai.com/Article/details/gtxopqkfps.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jlsjyb.cn/Article/details/gtnjiihxsn.html

[R24] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gtjvwghksp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhengqikj.top/Article/details/gtzycatfmq.html

[R25] 去后缀 / 去前缀
来源：http://dali.tianlin.xyz/Article/details/gtnxsfmwsh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgufenzy.top/Article/details/gtcitoedcd.html

[R26] 命令替换
来源：http://dali.svipenyu.cn/Article/details/gtxxsgqthd.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgufenzy.top/Article/details/gtzdpaskbf.html

[R27] 算术展开
来源：http://dali.meibo888.top/Article/details/gtsdacctnq.html

echo $((1 + 2 * 3))
来源：http://dali.yvedp.cn/Article/details/gtavleckpt.html

[R28] 浮点运算
来源：http://dali.snrcjt.cn/Article/details/gtyofrurqd.html

echo "scale=2; 10/3" | bc
来源：http://dali.ehwqpu.com/Article/details/gthnnpxgzi.html

[R29] 定义函数
来源：http://dali.sysykeji.top/Article/details/gtydalxekj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.kuanghao11.cn/Article/details/gtjfmehvfe.html

[R30] 函数返回状态码
来源：http://dali.zdqjudy.top/Article/details/gtrraeigpw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tian-w.cn/Article/details/gtjntutjkf.html

[R31] 局部变量
来源：http://dali.ivvv.top/Article/details/gthypnbbwx.html

f() { local x=1; echo "$x"; }
来源：http://dali.tianlin.xyz/Article/details/gtvekmtvwd.html

[R32] 参数个数校验
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbruqeel.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjqpwrwi.html

[R33] 捕获错误并提示行号
来源：http://dali.hnqzz.top/Article/details/gtjudbjgie.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.0kj1m.cn/Article/details/gtjudtsini.html

[R34] 退出时清理
来源：http://dali.jinqigufen.top/Article/details/gtifpxmvlh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gtcmggiqta.html

[R35] 后台执行并等待
来源：http://dali.jlsjyb.cn/Article/details/gtoznnqrza.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgufenzy.top/Article/details/gtavuboeti.html

[R36] 并发执行多个任务
来源：http://dali.dashuyun.cn/Article/details/gtmtgeltby.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daxiang520.top/Article/details/gtjmahrhhy.html

[R37] 把输出赋给变量
来源：http://dali.jianghu66.top/Article/details/gttjoyzbeg.html

files=$(ls -1)
来源：http://dali.hongshengwenyu.top/Article/details/gtllnaszkp.html

[R38] 管道串联
来源：http://dali.zhengqikj.top/Article/details/gtrhtwjcdi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hammf.cn/Article/details/gtksnmhcsu.html

[R39] 重定向标准输出与错误
来源：http://dali.wangdashe.top/Article/details/gtzfhboxwm.html

cmd > out.log 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gtwebslzbp.html

[R40] 追加写日志
来源：http://dali.birdmap.top/Article/details/gthvvtuhtd.html

echo "log" >> out.log
来源：http://dali.yj202588.top/Article/details/gtpoouyxuq.html

[R41] 丢弃输出
来源：http://dali.hammf.cn/Article/details/gtioagdovk.html

cmd >/dev/null 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gtxiphaogf.html

[R42] 输入重定向
来源：http://dali.zhongyouzk.top/Article/details/gtwapgjzlb.html

wc -l < a.txt
来源：http://dali.gzhubu.top/Article/details/gtdeiunxqg.html

[R43] 按名字查找文件
来源：http://dali.gogol.net.cn/Article/details/gtvghmvaus.html

find . -name "*.log" -type f
来源：http://dali.yuanzhike.top/Article/details/gtwysiritt.html

[R44] 按修改时间查找
来源：http://dali.yonumen.top/Article/details/gtyxtwsysj.html

find . -mtime -7 -type f
来源：http://dali.haohaochexian.top/Article/details/gtskafstbr.html

[R45] 批量删除
来源：http://dali.vqdsnc.cn/Article/details/gthwrmfwnh.html

find . -name "*.tmp" -delete
来源：http://dali.cucudq.cn/Article/details/gtqsqdabkp.html

[R46] 递归替换文件内容
来源：http://dali.cucudq.cn/Article/details/gtazetjeco.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.andypj.xyz/Article/details/gtpsisxjen.html

[R47] sed 单行替换
来源：http://dali.snrcjt.cn/Article/details/gtwyqmewet.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cqqwz.cn/Article/details/gtwhrwmmju.html

[R48] awk 取指定列
来源：http://dali.redwolf501.top/Article/details/gtrnbkssun.html

awk '{print $1, $3}' a.txt
来源：http://dali.c1oappe.top/Article/details/gtoypbchud.html

[R49] awk 带条件
来源：http://dali.aibaodan.cn/Article/details/gtteouirpo.html


<!-- 参考信息 -->