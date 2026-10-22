代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sysykeji.top/Article/details/gtrywxuhvc.html

user_id INT NOT NULL,
来源：http://dali.shangyingyoupin.top/Article/details/gtwdfpjdzr.html

amount DECIMAL(10, 2),
来源：http://dali.jinqigfzy.top/Article/details/gtuldhqufm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgufenzy.top/Article/details/gtohecendb.html

);
来源：http://dali.yongpay.top/Article/details/gtjyhqvinl.html

[Q03] 增加列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfaygmhdm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.aibaodan.cn/Article/details/gtgyepjyah.html

[Q04] 修改列类型
来源：http://dali.pycfn.com/Article/details/gtiqblecog.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.feifeiyinyue.top/Article/details/gtdignvann.html

[Q05] 重命名列
来源：http://dali.nanxuanxn.top/Article/details/gtsrlyowde.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvasamfa.html

[Q06] 删除列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdalihir.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guowangkeji.top/Article/details/gtjaemrkpn.html

[Q07] 删除表
来源：http://dali.snrcjt.cn/Article/details/gtchjsnmwd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.birdmap.top/Article/details/gtotfwywis.html

[Q08] 创建普通索引
来源：http://dali.jlsjyb.cn/Article/details/gtervuwrtf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.fengsongda.top/Article/details/gtdqmztmgx.html

[Q09] 创建唯一索引
来源：http://dali.xziqi.cn/Article/details/gtudecrrkj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovmezowi.html

[Q10] 插入单行
来源：http://dali.sxryk.cn/Article/details/gtnxojgqve.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfmywavy.html

[Q11] 一次插入多行
来源：http://dali.jyoumei.cn/Article/details/gtsbkccryv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinqigufen.top/Article/details/gtuijtdlwg.html

[Q12] 插入后取自增 ID
来源：http://dali.ppjwa.cn/Article/details/gthtymdlhj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.andypj.xyz/Article/details/gtymisvcxy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hfpthk.cn/Article/details/gtifwpiqby.html

[Q13] 忽略重复插入
来源：http://dali.snrcjt.cn/Article/details/gtxushkhak.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cashguo.top/Article/details/gtizsyhfcc.html

[Q14] 存在则更新（upsert）
来源：http://dali.gzhubu.top/Article/details/gtqofjnxjp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guannengcc.top/Article/details/gtawfdaymr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuxming.cn/Article/details/gtugyvkxwe.html

[Q15] 查询全部
来源：http://dali.yuanzhike.top/Article/details/gtwteouxan.html

SELECT * FROM users;
来源：http://dali.daxiang520.top/Article/details/gttduhfyxq.html

[Q16] 查询指定列
来源：http://dali.cqqwz.cn/Article/details/gtaotewshv.html

SELECT id, name FROM users;
来源：http://dali.redwolf501.top/Article/details/gtuuraboow.html

[Q17] 条件查询
来源：http://dali.gogol.net.cn/Article/details/gtdoqvweed.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daxiang520.top/Article/details/gthlijvnkd.html

[Q18] 模糊匹配
来源：http://dali.yuxming.cn/Article/details/gtjmhnqpln.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxinkj.top/Article/details/gtlhzowsvx.html

[Q19] 范围查询
来源：http://dali.meibo888.top/Article/details/gtsyqkxvta.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.kuanghao11.cn/Article/details/gtsrewsxcf.html

[Q20] IN 列表
来源：http://dali.sufxvd.cn/Article/details/gtsrptjyzk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gtmaimukxi.html

[Q21] 空值判断
来源：http://dali.jinqigfzy.top/Article/details/gtkrwloamy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gtydrjlvsq.html

[Q22] 排序
来源：http://dali.sxryk.cn/Article/details/gtxuzsjzej.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenzaomai.com/Article/details/gtfzsjzjdb.html

[Q23] 分页
来源：http://dali.xinyue.icu/Article/details/gtpxlhjihc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.smart0.xyz/Article/details/gttmbexedc.html

[Q24] 去重
来源：http://dali.aibaodan.cn/Article/details/gtxdwvaczo.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtduuwiytg.html

[Q25] 只取前 N 条
来源：http://dali.zhixingplan.top/Article/details/gtopjslodh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ybcxt.top/Article/details/gtbztmhfqc.html

[Q26] 计数
来源：http://dali.yongpay.top/Article/details/gtxdkigehv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmbxlmxh.html

[Q27] 条件计数
来源：http://dali.chenjidiqi.icu/Article/details/gtbsvdrhli.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtirhlzeom.html

[Q28] 求和与平均
来源：http://dali.yj20258888.top/Article/details/gtxogxaxyd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gttlkccumz.html

[Q29] 最大最小值
来源：http://dali.nanxuanxn.top/Article/details/gtwskhootf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtezohmofc.html

[Q30] 分组统计
来源：http://dali.0kj1m.cn/Article/details/gtmxjsbgfk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gtaukqrmfp.html

[Q31] 分组后过滤
来源：http://dali.mhx1999.top/Article/details/gtjusrafzf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtxejmigmt.html

[Q32] 分组拼接字符串
来源：http://dali.guannengcc.top/Article/details/gtmsoydril.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtnumbvtpa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jyoumei.cn/Article/details/gthvhsqegv.html

[Q33] 多列分组
来源：http://dali.yj20258888.top/Article/details/gttsityois.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.kuanghao11.cn/Article/details/gtjrmupnjv.html

[Q34] 每组取第一条
来源：http://dali.aibaodan.cn/Article/details/gtchklgipz.html

SELECT * FROM (
来源：http://dali.cheryme.top/Article/details/gtigkkhskk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sufxvd.cn/Article/details/gtvsdtbwnc.html

) t WHERE rn = 1;
来源：http://dali.meibo888.top/Article/details/gtahmxjgjz.html

[Q35] 内连接
来源：http://dali.yueranfly.top/Article/details/gtifqfzsde.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gtqyddiykv.html

[Q36] 左连接
来源：http://dali.kuanghao11.cn/Article/details/gtdtbgkmfx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sysykeji.top/Article/details/gtgkcrwtkw.html

[Q37] 右连接
来源：http://dali.quarkkingdee.top/Article/details/gtlaorrpwp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sxryk.cn/Article/details/gtlcaqxbwk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.havefunace.top/Article/details/gtadvkznag.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgufenzy.top/Article/details/gtmdqwvnxt.html

[Q39] 自连接（查上下级）
来源：http://dali.jinqigfzy.top/Article/details/gtwoxtnaqx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangdashe.top/Article/details/gtiebebyxk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sxryk.cn/Article/details/gtctnntnnp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhoulong.xyz/Article/details/gtwgpkzfis.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ivvv.top/Article/details/gtuiuafzdz.html

[Q41] 多表连接
来源：http://dali.jqgufenzy.top/Article/details/gtwspfkgzb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ybcxt.top/Article/details/gtcfbiuape.html

JOIN users u ON u.id = o.user_id
来源：http://dali.quarkkingdee.top/Article/details/gtcsfvdpac.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cheryme.top/Article/details/gtwufdliyr.html

[Q42] 连接条件附加过滤
来源：http://dali.havefunace.top/Article/details/gtifwulmvi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhongyouzk.top/Article/details/gtcptvilta.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cdnleiting.top/Article/details/gtbjwxmbvf.html

[Q43] 标量子查询
来源：http://dali.yvedp.cn/Article/details/gtqbbbdsgr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yonumen.top/Article/details/gtrcnoxzsy.html

[Q44] IN 子查询
来源：http://dali.sxryk.cn/Article/details/gtxobfmytq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigfzy.top/Article/details/gtmcbcqgsp.html

[Q45] EXISTS 判断存在
来源：http://dali.wangdashe.top/Article/details/gtoaguxami.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gtqrkzsyex.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hywenlv.cn/Article/details/gtakcvzmyx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.havefunace.top/Article/details/gtqzuyhgdu.html

[Q47] 与平均值比较
来源：http://dali.shzxlz.cn/Article/details/gtfaxzyobn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nanxinkj.top/Article/details/gtndzxqtkv.html

[Q48] CTE 公用表表达式
来源：http://dali.yvedp.cn/Article/details/gtupuakhyz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yangfankeji.com/Article/details/gtnxiusnlz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzphhkvco.html

[Q49] 更新单行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgtaakqi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gtsvcfdhrs.html

[Q50] 批量更新
来源：http://dali.ydzc1.top/Article/details/gtcffopxmd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xylfe.cn/Article/details/gtjrxxwlbv.html

[Q51] 用子查询更新
来源：http://dali.xylfe.cn/Article/details/gtqyokmlqr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtnbhvfkog.html

[Q52] 删除指定行
来源：http://dali.xinyue.icu/Article/details/gtyjqwiesi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gthqshkhby.html

[Q53] 按条件删除
来源：http://dali.dashuyun.cn/Article/details/gtdkplnlov.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tian-w.cn/Article/details/gtrhnwpjec.html

[Q54] 清空表
来源：http://dali.ppjwa.cn/Article/details/gtbnjxdqjp.html

TRUNCATE TABLE logs;
来源：http://dali.dashuyun.cn/Article/details/gtfpjvuhqs.html

[Q55] 排名（并列占位）
来源：http://dali.fengsongda.top/Article/details/gtxbaqqjhc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gtofwstopr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gthuxldany.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.bjfxy.top/Article/details/gtciazubhh.html

[Q57] 行号
来源：http://dali.yuxming.cn/Article/details/gticrpczxa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnqzz.top/Article/details/gtwpzlwvkn.html

[Q58] 累计求和
来源：http://dali.hnxiangtu.top/Article/details/gtjsczqsgf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtekorhtmk.html

[Q59] 分组内累计
来源：http://dali.jinghuilouyu.cn/Article/details/gttyriadba.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtmabaolws.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigfzy.top/Article/details/gtdkbptojq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xylfe.cn/Article/details/gtixfwadpf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtnrwdlogv.html

[Q61] 移动平均
来源：http://dali.chenlongwang.top/Article/details/gtinqrzlqr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtsdgnwfec.html

[Q62] 分组占比
来源：http://dali.9152youxi.cn/Article/details/gtfohetpww.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gtjmrhcczl.html

[Q63] 开启事务
来源：http://dali.guannengcc.top/Article/details/gthcijcovd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.vqdsnc.cn/Article/details/gtejjvfisj.html

[Q64] 提交事务
来源：http://dali.birdmap.top/Article/details/gtwvcewkgm.html

COMMIT;
来源：http://dali.daria6918.cn/Article/details/gtqwqvofay.html

[Q65] 回滚事务
来源：http://dali.ivvv.top/Article/details/gtoyxqkwrl.html

ROLLBACK;
来源：http://dali.gaohongyu789.top/Article/details/gtjqihbsku.html

[Q66] 行锁查询
来源：http://dali.daria6918.cn/Article/details/gtdvmwlvbu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jiagoushi.top/Article/details/gtqnlgrdlw.html

[Q67] 设置隔离级别
来源：http://dali.yongpay.top/Article/details/gtuzppunhc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.haohaochexian.top/Article/details/gtgouqvjwy.html

[Q68] 保存点
来源：http://dali.zdqjudy.top/Article/details/gtwciiqyqf.html

SAVEPOINT sp1;
来源：http://dali.iojbl.cn/Article/details/gtuzniopbe.html

ROLLBACK TO sp1;
来源：http://dali.gzhubu.top/Article/details/gtfybflfud.html

[Q69] 查看执行计划
来源：http://dali.jlsjyb.cn/Article/details/gtamuacyir.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhixingplan.top/Article/details/gtezdqsmkv.html

[Q70] 更新统计信息
来源：http://dali.cdnleiting.top/Article/details/gtttdpwrhz.html

ANALYZE TABLE users;
来源：http://dali.mhx1999.top/Article/details/gtqabceuuf.html

[Q71] 查看建表语句
来源：http://dali.yangfankeji.com/Article/details/gtzobjhsch.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.havefunace.top/Article/details/gtyxiayvqr.html

[Q72] 查看索引
来源：http://dali.tianlin.xyz/Article/details/gthyzulihh.html

SHOW INDEX FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkqriehr.html

[Q73] 查看表状态
来源：http://dali.aizwys.cn/Article/details/gtussailxu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.9152youxi.cn/Article/details/gtkhvcbosl.html

[Q74] 强制使用索引
来源：http://dali.ivvv.top/Article/details/gtzzidadlr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ivvv.top/Article/details/gtuuzlqvzm.html

[Q75] 日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gttlsinmzo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj202588.top/Article/details/gtafekujxv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yvedp.cn/Article/details/gtslaedfwd.html

[Q76] 按天统计
来源：http://dali.tianlin.xyz/Article/details/gttnjqybpy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yongpay.top/Article/details/gtnxvjgvsp.html

[Q77] 时间加减
来源：http://dali.yuxming.cn/Article/details/gtwwitrhch.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.feifeiyinyue.top/Article/details/gthomlqqma.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gtupwogtbt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hnxiangtu.top/Article/details/gtzschyvxv.html

[Q79] 字符串拼接
来源：http://dali.sufxvd.cn/Article/details/gtvobflvap.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.svipenyu.cn/Article/details/gtjgaihaqh.html

[Q80] 字符串截取
来源：http://dali.yueranfly.top/Article/details/gtxxqwxbbi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqfbjtgb.html

[Q81] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gtkcyyohwk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258888.top/Article/details/gtowlkegbs.html

[Q82] 字符长度与字节长度
来源：http://dali.fzhhl.top/Article/details/gtmlnvnfwc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtvweufkpd.html

[Q83] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gttofmotlw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtdwsimlpt.html

[Q84] 去除首尾空格
来源：http://dali.yongpay.top/Article/details/gtibofzgun.html

SELECT TRIM(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtdimrqzyd.html

[Q85] 数值取整
来源：http://dali.feifeiyinyue.top/Article/details/gtnddxpskf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sufxvd.cn/Article/details/gtljqiumyk.html

[Q86] 读取 JSON 字段
来源：http://dali.hnxiangtu.top/Article/details/gtlylkvjor.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpaoxjxjb.html

[Q87] JSON 字段做条件
来源：http://dali.pengpengdd.cyou/Article/details/gtloqbomaz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.redwolf501.top/Article/details/gtqcearvig.html

[Q88] 行转列（条件聚合）
来源：http://dali.iojbl.cn/Article/details/gtvgaepsir.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hongshengwenyu.top/Article/details/gtoboppzls.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtclbioyac.html

[Q89] 判断表是否存在
来源：http://dali.guowangkeji.top/Article/details/gtjpzcrpri.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenlongwang.top/Article/details/gtvzzsbwpk.html

[Q90] 生成序号列
来源：http://dali.yongpay.top/Article/details/gtrjqqtynu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yangfankeji.com/Article/details/gtjtiggvkx.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtyofiilsh.html

R. Bash 专题
来源：http://dali.tian-w.cn/Article/details/gteverrdzc.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtwgvmqkqn.html

[R01] shebang 与严格模式
来源：http://dali.birdmap.top/Article/details/gtdqtzgxxo.html

#!/usr/bin/env bash
来源：http://dali.birdmap.top/Article/details/gtrpalrtun.html

set -euo pipefail
来源：http://dali.hywenlv.cn/Article/details/gttjmwtuhj.html

[R02] 变量赋值与使用
来源：http://dali.wangdashe.top/Article/details/gtkinahrsc.html

name="Tom"; echo "$name"
来源：http://dali.guowangkeji.top/Article/details/gtzuuvowoi.html

[R03] 只读变量
来源：http://dali.gzhubu.top/Article/details/gtfgbefqnj.html

readonly PI=3.14
来源：http://dali.yj20258.top/Article/details/gtsolyavsk.html

[R04] 位置参数
来源：http://dali.shzxlz.cn/Article/details/gthojqfwhr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pengpengdd.cyou/Article/details/gtdftqnofn.html

[R05] 参数默认值
来源：http://dali.nanxinkj.top/Article/details/gtrtpiphjy.html

name="${1:-default}"
来源：http://dali.ydzc1.top/Article/details/gtiyremffk.html

[R06] 判断命令是否存在
来源：http://dali.wangdashe.top/Article/details/gtvurebish.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtgxocfvgl.html

[R07] if 判断文件
来源：http://dali.aizwys.cn/Article/details/gtbhkvpctx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.bjfxy.top/Article/details/gtwnpgukoc.html

[R08] 数值比较
来源：http://dali.shangyingyoupin.top/Article/details/gtrmphitol.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.birdmap.top/Article/details/gtemgmqvlj.html

[R09] 字符串比较
来源：http://dali.xylfe.cn/Article/details/gticmsndka.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.fzhhl.top/Article/details/gturvkcgah.html

[R10] 正则匹配
来源：http://dali.ydzc1.top/Article/details/gtxesoihyy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aizwys.cn/Article/details/gtyhtqrqey.html

[R11] case 多分支
来源：http://dali.redwolf501.top/Article/details/gtymqybvez.html

case "$1" in
来源：http://dali.yangfankeji.com/Article/details/gtxxfiytrb.html

start) echo "启动" ;;
来源：http://dali.iojbl.cn/Article/details/gtelnvqhys.html

stop)  echo "停止" ;;
来源：http://dali.tian-w.cn/Article/details/gtimsizgmu.html

*)     echo "未知命令" ;;
来源：http://dali.sufxvd.cn/Article/details/gtuzkhfrcf.html

esac
来源：http://dali.hnqzz.top/Article/details/gtfgfymhoq.html

[R12] for 遍历文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbabipuu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cheryme.top/Article/details/gtnyfpjemm.html

[R13] for 计数循环
来源：http://dali.guowangkeji.top/Article/details/gttwwtrdik.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtnolakamd.html

[R14] C 风格 for
来源：http://dali.smart0.xyz/Article/details/gtahemqebl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gtvcphgaon.html

[R15] while 逐行读文件
来源：http://dali.yj202588.top/Article/details/gtjqxdtvmk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xinyue.icu/Article/details/gtqkrftyrx.html

[R16] until 等待条件
来源：http://dali.ydzc1.top/Article/details/gticghqfxj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hfpthk.cn/Article/details/gtvssviktm.html

[R17] 数组定义与取值
来源：http://dali.xinyue.icu/Article/details/gtuiyklrjs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.316326.xyz/Article/details/gtjcbjrarp.html

[R18] 遍历数组
来源：http://dali.zhiwuduotai.top/Article/details/gthxkmjqff.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdjmqspe.html

[R19] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gtbqzgtccx.html

echo "${#arr[@]}"
来源：http://dali.jinqigfzy.top/Article/details/gtprtvbzkr.html

[R20] 关联数组（字典）
来源：http://dali.jinqigfzy.top/Article/details/gtqbafhxus.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.snrcjt.cn/Article/details/gtvevudvqp.html

[R21] 字符串长度
来源：http://dali.redwolf501.top/Article/details/gtudfebjyt.html

echo "${#s}"
来源：http://dali.cqqwz.cn/Article/details/gtalxxzion.html

[R22] 截取子串
来源：http://dali.ybcxt.top/Article/details/gtcrszlpcs.html

echo "${s:0:5}"
来源：http://dali.cucudq.cn/Article/details/gtmhgyxjpx.html

[R23] 字符串替换
来源：http://dali.chenzaomai.com/Article/details/gtrajdrcxq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ehwqpu.com/Article/details/gtnioedgrt.html

[R24] 大小写转换
来源：http://dali.jiagoushi.top/Article/details/gtygxcyfjs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jianghu66.top/Article/details/gtmefwzoix.html

[R25] 去后缀 / 去前缀
来源：http://dali.c1oappe.top/Article/details/gtuckobqoi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sysykeji.top/Article/details/gtptnhbcyk.html

[R26] 命令替换
来源：http://dali.gotoacloud.top/Article/details/gtwgftuuvd.html

now=$(date +%F); echo "$now"
来源：http://dali.sufxvd.cn/Article/details/gtmdldqivq.html

[R27] 算术展开
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixdzzwlk.html

echo $((1 + 2 * 3))
来源：http://dali.fzhhl.top/Article/details/gtoqhfmcab.html

[R28] 浮点运算
来源：http://dali.iojbl.cn/Article/details/gtqrppxiqv.html

echo "scale=2; 10/3" | bc
来源：http://dali.mhx1999.top/Article/details/gtfanelhrw.html

[R29] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gtrpcwxiqt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cqqwz.cn/Article/details/gtiicbnpfd.html

[R30] 函数返回状态码
来源：http://dali.nwbrower.top/Article/details/gtnoahqutf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenlongwang.top/Article/details/gtfpxqwhqn.html

[R31] 局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gtgidvczlh.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenzaomai.com/Article/details/gtylaojwxr.html

[R32] 参数个数校验
来源：http://dali.cheryme.top/Article/details/gtdpkwwoex.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.haohaochexian.top/Article/details/gtxszatgdz.html

[R33] 捕获错误并提示行号
来源：http://dali.ybcxt.top/Article/details/gtcehmjaqf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gotoacloud.top/Article/details/gtzyvgscsl.html

[R34] 退出时清理
来源：http://dali.zhongyouzk.top/Article/details/gtupciacjb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.c1oappe.top/Article/details/gtimpvljhm.html

[R35] 后台执行并等待
来源：http://dali.xinyue.icu/Article/details/gtnvrehtqk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guowangkeji.top/Article/details/gtlkkhyank.html

[R36] 并发执行多个任务
来源：http://dali.xuanzx.com/Article/details/gtmsmtygdg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxinkj.top/Article/details/gtixbofkmx.html

[R37] 把输出赋给变量
来源：http://dali.zhixingplan.top/Article/details/gtytpvphog.html

files=$(ls -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtxdnvmnjf.html

[R38] 管道串联
来源：http://dali.yj202588.top/Article/details/gtzbczxcqr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zdqjudy.top/Article/details/gtgfjnuaqg.html

[R39] 重定向标准输出与错误
来源：http://dali.c1oappe.top/Article/details/gtmnyweurv.html

cmd > out.log 2>&1
来源：http://dali.tianlin.xyz/Article/details/gtubttvbkk.html

[R40] 追加写日志
来源：http://dali.chenjidiqi.icu/Article/details/gtznccobpo.html

echo "log" >> out.log
来源：http://dali.shangyingyoupin.top/Article/details/gtlgsjqedw.html

[R41] 丢弃输出
来源：http://dali.shzxlz.cn/Article/details/gtwsjyfiqi.html

cmd >/dev/null 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gtkybvttem.html

[R42] 输入重定向
来源：http://dali.yj20258888.top/Article/details/gthwfsejqs.html

wc -l < a.txt
来源：http://dali.shzxlz.cn/Article/details/gtktkfddar.html

[R43] 按名字查找文件
来源：http://dali.yuxming.cn/Article/details/gtqhjwbujh.html

find . -name "*.log" -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpsatrwf.html

[R44] 按修改时间查找
来源：http://dali.shangyingyoupin.top/Article/details/gtzfzmyaen.html

find . -mtime -7 -type f
来源：http://dali.havefunace.top/Article/details/gthutktper.html

[R45] 批量删除
来源：http://dali.cucudq.cn/Article/details/gtrpcfimdm.html

find . -name "*.tmp" -delete
来源：http://dali.cashguo.top/Article/details/gtoerxkoqv.html

[R46] 递归替换文件内容
来源：http://dali.gaohongyu789.top/Article/details/gtvaikcumo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.316326.xyz/Article/details/gtdbcsuqif.html

[R47] sed 单行替换
来源：http://dali.svipenyu.cn/Article/details/gtgivgiusy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtgvpveofm.html

[R48] awk 取指定列
来源：http://dali.birdmap.top/Article/details/gtpbwduyov.html

awk '{print $1, $3}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtmjnthrzh.html

[R49] awk 带条件
来源：http://dali.havefunace.top/Article/details/gtodtmwudp.html


<!-- 参考信息 -->