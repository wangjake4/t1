代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gtmounddmi.html

user_id INT NOT NULL,
来源：http://dali.shuidangran.top/Article/details/gtmlbylorw.html

amount DECIMAL(10, 2),
来源：http://dali.daria6918.cn/Article/details/gtnxdaxogi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.snrcjt.cn/Article/details/gtgwrrufpm.html

);
来源：http://dali.dashuyun.cn/Article/details/gtsyuzjgok.html

[Q03] 增加列
来源：http://dali.redwolf501.top/Article/details/gtuubauevu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrxlfdeh.html

[Q04] 修改列类型
来源：http://dali.snrcjt.cn/Article/details/gtlfzufqbd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cdnleiting.top/Article/details/gtqevitcpi.html

[Q05] 重命名列
来源：http://dali.shangyingyoupin.top/Article/details/gtyujbeohz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yvedp.cn/Article/details/gtlehpnghk.html

[Q06] 删除列
来源：http://dali.quarkkingdee.top/Article/details/gtoygoxttw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yonumen.top/Article/details/gtbsrgpqpo.html

[Q07] 删除表
来源：http://dali.yuanzhike.top/Article/details/gthzyrzxhf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cucudq.cn/Article/details/gtvllbougu.html

[Q08] 创建普通索引
来源：http://dali.jianghu66.top/Article/details/gtbrysbmvj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gtefiddgoc.html

[Q09] 创建唯一索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjoqbzor.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.aibaodan.cn/Article/details/gtwfnylqzt.html

[Q10] 插入单行
来源：http://dali.hfpthk.cn/Article/details/gtnyajbevy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gtjamawhyk.html

[Q11] 一次插入多行
来源：http://dali.xinyue.icu/Article/details/gttwszvhnn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.havefunace.top/Article/details/gtosclvejt.html

[Q12] 插入后取自增 ID
来源：http://dali.gogol.net.cn/Article/details/gthkrhzldx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xuanzx.com/Article/details/gtuxchiwlt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwccuaaq.html

[Q13] 忽略重复插入
来源：http://dali.ydzc1.top/Article/details/gtafnzfoki.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hysaishi.cn/Article/details/gtsgsuifux.html

[Q14] 存在则更新（upsert）
来源：http://dali.aizwys.cn/Article/details/gtrgaogtar.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ydzc1.top/Article/details/gtuwkpdhcu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jianghu66.top/Article/details/gtxfmpkjyo.html

[Q15] 查询全部
来源：http://dali.haohaochexian.top/Article/details/gtdmekkten.html

SELECT * FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtvklobivm.html

[Q16] 查询指定列
来源：http://dali.cheryme.top/Article/details/gtivqpqzjr.html

SELECT id, name FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdsylagya.html

[Q17] 条件查询
来源：http://dali.yuanzhike.top/Article/details/gtlsabdzxp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yuanzhike.top/Article/details/gtikyonwte.html

[Q18] 模糊匹配
来源：http://dali.zhongyouzk.top/Article/details/gtoflgsasf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.0kj1m.cn/Article/details/gtcgisopkg.html

[Q19] 范围查询
来源：http://dali.zhixingplan.top/Article/details/gtxlxjqziz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.svipenyu.cn/Article/details/gtmqtjjisa.html

[Q20] IN 列表
来源：http://dali.zhongyouzk.top/Article/details/gtfbdwlchc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.dashuyun.cn/Article/details/gttvmobdko.html

[Q21] 空值判断
来源：http://dali.ppjwa.cn/Article/details/gtgpbpevxf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jqgfzy.top/Article/details/gtzemexcql.html

[Q22] 排序
来源：http://dali.aibaodan.cn/Article/details/gtgqflgolh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.vqdsnc.cn/Article/details/gtpmaqoxhz.html

[Q23] 分页
来源：http://dali.smart0.xyz/Article/details/gtlfljbugu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinghuilouyu.cn/Article/details/gtegcklssc.html

[Q24] 去重
来源：http://dali.hnxiangtu.top/Article/details/gtubxpimdo.html

SELECT DISTINCT city FROM users;
来源：http://dali.yongpay.top/Article/details/gtjwfvxoay.html

[Q25] 只取前 N 条
来源：http://dali.jiagoushi.top/Article/details/gtuqrjelfb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gzhubu.top/Article/details/gtrgcvplvi.html

[Q26] 计数
来源：http://dali.birdmap.top/Article/details/gtncrhvqvm.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtfczhdigm.html

[Q27] 条件计数
来源：http://dali.jqgufenzy.top/Article/details/gtncfjyekt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtowqlkfeu.html

[Q28] 求和与平均
来源：http://dali.hnqzz.top/Article/details/gttubhgsdg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtgliligtq.html

[Q29] 最大最小值
来源：http://dali.dashuyun.cn/Article/details/gtetgttryq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtlshxdgjn.html

[Q30] 分组统计
来源：http://dali.hysaishi.cn/Article/details/gtomgsnprn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gtuzavqocb.html

[Q31] 分组后过滤
来源：http://dali.sweek.top/Article/details/gtncovleie.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cdnleiting.top/Article/details/gtrbuuouii.html

[Q32] 分组拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtpumawibx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gtpjangzfp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.snrcjt.cn/Article/details/gtvbzfnhso.html

[Q33] 多列分组
来源：http://dali.sufxvd.cn/Article/details/gtuarrzjnn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hammf.cn/Article/details/gtduynaglq.html

[Q34] 每组取第一条
来源：http://dali.sxryk.cn/Article/details/gtrmtxydnt.html

SELECT * FROM (
来源：http://dali.hysaishi.cn/Article/details/gtcuzkkpmc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ivvv.top/Article/details/gtqisebefc.html

) t WHERE rn = 1;
来源：http://dali.nwbrower.top/Article/details/gtwifxrpsk.html

[Q35] 内连接
来源：http://dali.gotoacloud.top/Article/details/gtlsplwwtg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.9152youxi.cn/Article/details/gtitcsapnm.html

[Q36] 左连接
来源：http://dali.hfpthk.cn/Article/details/gtdzctladl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gtlufwzoob.html

[Q37] 右连接
来源：http://dali.yanxiufei.cn/Article/details/gtplgvjrct.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.meibo888.top/Article/details/gtrjqlqqel.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zdqjudy.top/Article/details/gtptgntrkq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yanxiufei.cn/Article/details/gtrlpsgfil.html

[Q39] 自连接（查上下级）
来源：http://dali.tianlin.xyz/Article/details/gtepilglij.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.birdmap.top/Article/details/gtwvrrxwsr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zdqjudy.top/Article/details/gtcldlovka.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jyoumei.cn/Article/details/gtruzlctug.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.c1oappe.top/Article/details/gtelpcnbsq.html

[Q41] 多表连接
来源：http://dali.zhongyouzk.top/Article/details/gtlaxvcrmx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cashguo.top/Article/details/gtuhxhgrna.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xuanzx.com/Article/details/gtuiquflqw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shuidangran.top/Article/details/gtkbouqpbd.html

[Q42] 连接条件附加过滤
来源：http://dali.redwolf501.top/Article/details/gtnudkifos.html

SELECT u.name, o.amount FROM users u
来源：http://dali.quarkkingdee.top/Article/details/gtfyeopnwv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jyoumei.cn/Article/details/gtbvhsvgen.html

[Q43] 标量子查询
来源：http://dali.tianlin.xyz/Article/details/gtupizqfqi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xylfe.cn/Article/details/gtpntoepjg.html

[Q44] IN 子查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmlvfiff.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sweek.top/Article/details/gtgzahvgmu.html

[Q45] EXISTS 判断存在
来源：http://dali.xinyue.icu/Article/details/gtonhxyxmt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gtbaggsjqr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ivvv.top/Article/details/gtmbserxqi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gtketmznzb.html

[Q47] 与平均值比较
来源：http://dali.wangdashe.top/Article/details/gteaezwgbe.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ehwqpu.com/Article/details/gtbkdwjiaf.html

[Q48] CTE 公用表表达式
来源：http://dali.jiagoushi.top/Article/details/gtyaczcbcb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj20258888.top/Article/details/gtomqsrunr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhongyouzk.top/Article/details/gtkzvhjizq.html

[Q49] 更新单行
来源：http://dali.yangfankeji.com/Article/details/gtdpcnmarz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gtceqxhrws.html

[Q50] 批量更新
来源：http://dali.yangfankeji.com/Article/details/gtzuilosgq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tianlin.xyz/Article/details/gtoeidstld.html

[Q51] 用子查询更新
来源：http://dali.zycfv.cn/Article/details/gtcmnqkadd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nwbrower.top/Article/details/gtbtwqscew.html

[Q52] 删除指定行
来源：http://dali.aizwys.cn/Article/details/gtqlijtaal.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj202588.top/Article/details/gtyflbcoqc.html

[Q53] 按条件删除
来源：http://dali.aibaodan.cn/Article/details/gtikdzalyj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinghuilouyu.cn/Article/details/gtdubymsyr.html

[Q54] 清空表
来源：http://dali.zhaomingkeji.xyz/Article/details/gthlmuwlki.html

TRUNCATE TABLE logs;
来源：http://dali.yuanzhike.top/Article/details/gtgxnfiqhz.html

[Q55] 排名（并列占位）
来源：http://dali.zhixingplan.top/Article/details/gttyejysmd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.316326.xyz/Article/details/gtdkixchth.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yonumen.top/Article/details/gtqepxlkml.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gtpbvuuzpb.html

[Q57] 行号
来源：http://dali.andypj.xyz/Article/details/gtykerfmoq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xziqi.cn/Article/details/gttufuwojz.html

[Q58] 累计求和
来源：http://dali.redwolf501.top/Article/details/gtqfmfeasv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.pycfn.com/Article/details/gtpvpfzphx.html

[Q59] 分组内累计
来源：http://dali.wangshuangyany.cn/Article/details/gtsxubjoxh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtgrbwnqpk.html

[Q60] 取上一行 / 下一行
来源：http://dali.daria6918.cn/Article/details/gtwbdjnftk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.c1oappe.top/Article/details/gtfyrjzpxd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtymcegrrq.html

[Q61] 移动平均
来源：http://dali.shangyingyoupin.top/Article/details/gtvxqwbgzu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtrfqdisjg.html

[Q62] 分组占比
来源：http://dali.feifeiyinyue.top/Article/details/gtoeztilvp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gtflvrslzb.html

[Q63] 开启事务
来源：http://dali.hnxiangtu.top/Article/details/gtonseodpx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ppjwa.cn/Article/details/gtalpgnazv.html

[Q64] 提交事务
来源：http://dali.daria6918.cn/Article/details/gtqaxwxdvd.html

COMMIT;
来源：http://dali.jinqigfzy.top/Article/details/gtvcokanqz.html

[Q65] 回滚事务
来源：http://dali.hywenlv.cn/Article/details/gtusjxtako.html

ROLLBACK;
来源：http://dali.ybcxt.top/Article/details/gtrbldwbqg.html

[Q66] 行锁查询
来源：http://dali.sweek.top/Article/details/gttfuzyqlo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ivvv.top/Article/details/gtoyhvxane.html

[Q67] 设置隔离级别
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppytnzce.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xylfe.cn/Article/details/gtsgtbhdpv.html

[Q68] 保存点
来源：http://dali.kuanghao11.cn/Article/details/gtjygofjvc.html

SAVEPOINT sp1;
来源：http://dali.chenzaomai.com/Article/details/gthqffecig.html

ROLLBACK TO sp1;
来源：http://dali.gogol.net.cn/Article/details/gtawphwnjq.html

[Q69] 查看执行计划
来源：http://dali.sxryk.cn/Article/details/gtufulmdgv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gthsxzpoct.html

[Q70] 更新统计信息
来源：http://dali.pengpengdd.cyou/Article/details/gtevznnvsq.html

ANALYZE TABLE users;
来源：http://dali.hfpthk.cn/Article/details/gtwehtdkmj.html

[Q71] 查看建表语句
来源：http://dali.yongpay.top/Article/details/gtkromzqos.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbsgvykgb.html

[Q72] 查看索引
来源：http://dali.pycfn.com/Article/details/gtsczcmjhf.html

SHOW INDEX FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtonvapafh.html

[Q73] 查看表状态
来源：http://dali.dianchejie.cn/Article/details/gtmzhamycn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.pycfn.com/Article/details/gtnfydbzye.html

[Q74] 强制使用索引
来源：http://dali.cheryme.top/Article/details/gtsczovfxl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.316326.xyz/Article/details/gtlwjauoat.html

[Q75] 日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gtqtytdtch.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gthwmoleja.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.fengsongda.top/Article/details/gtpggqhsmr.html

[Q76] 按天统计
来源：http://dali.hnxiangtu.top/Article/details/gtmvczxdyi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aizwys.cn/Article/details/gtfmzsdxtm.html

[Q77] 时间加减
来源：http://dali.gotoacloud.top/Article/details/gtjdbgiiob.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqmfpzzi.html

[Q78] 当前时间
来源：http://dali.daria6918.cn/Article/details/gtswhhlplz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guowangkeji.top/Article/details/gtbexerdpk.html

[Q79] 字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gtqwftlnvw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xuetiantiany.cn/Article/details/gtqejysayv.html

[Q80] 字符串截取
来源：http://dali.ppjwa.cn/Article/details/gtymfcakrn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yongpay.top/Article/details/gtoovfrsnh.html

[Q81] 字符串替换
来源：http://dali.gotoacloud.top/Article/details/gtxzndsczs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuanzhike.top/Article/details/gthlbznaxp.html

[Q82] 字符长度与字节长度
来源：http://dali.guowangkeji.top/Article/details/gtmxxnoxek.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtrvcglpnw.html

[Q83] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gtiqjmiend.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gthacapdzq.html

[Q84] 去除首尾空格
来源：http://dali.9152youxi.cn/Article/details/gtllceyudc.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtdnlqfpbb.html

[Q85] 数值取整
来源：http://dali.kuanghao11.cn/Article/details/gtioefrspb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jlsjyb.cn/Article/details/gttpzbacxa.html

[Q86] 读取 JSON 字段
来源：http://dali.tianlin.xyz/Article/details/gtwuroszfz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tanke756.top/Article/details/gtrhmfyyvn.html

[Q87] JSON 字段做条件
来源：http://dali.aibaodan.cn/Article/details/gtilknqcaf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hfpthk.cn/Article/details/gtpjiwsrhx.html

[Q88] 行转列（条件聚合）
来源：http://dali.c1oappe.top/Article/details/gttugqmddb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.svipenyu.cn/Article/details/gtuytnlfee.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xziqi.cn/Article/details/gtgonjydlq.html

[Q89] 判断表是否存在
来源：http://dali.yongpay.top/Article/details/gtkkiylxod.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yvedp.cn/Article/details/gtvgftonae.html

[Q90] 生成序号列
来源：http://dali.chenjidiqi.icu/Article/details/gttbvtvvax.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sysykeji.top/Article/details/gtnabiaoyr.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtpvgnjncv.html

R. Bash 专题
来源：http://dali.shzxlz.cn/Article/details/gtlxevtqxc.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gthxlpfcyg.html

[R01] shebang 与严格模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxysfwrzl.html

#!/usr/bin/env bash
来源：http://dali.yuanzhike.top/Article/details/gtbwtwraxh.html

set -euo pipefail
来源：http://dali.xinyue.icu/Article/details/gtarubtzbk.html

[R02] 变量赋值与使用
来源：http://dali.chenzaomai.com/Article/details/gtfmnasrwr.html

name="Tom"; echo "$name"
来源：http://dali.gzhubu.top/Article/details/gtiyumgljl.html

[R03] 只读变量
来源：http://dali.wangshuangyany.cn/Article/details/gtbjotxtnt.html

readonly PI=3.14
来源：http://dali.zycfv.cn/Article/details/gtofygzlpe.html

[R04] 位置参数
来源：http://dali.xylfe.cn/Article/details/gtsklcrdwx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.vqdsnc.cn/Article/details/gtwegjbrrp.html

[R05] 参数默认值
来源：http://dali.wangshuangyany.cn/Article/details/gttzysjzao.html

name="${1:-default}"
来源：http://dali.ivvv.top/Article/details/gtafhrvhww.html

[R06] 判断命令是否存在
来源：http://dali.cucudq.cn/Article/details/gtobhpbjxd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yonumen.top/Article/details/gtljhrnbfn.html

[R07] if 判断文件
来源：http://dali.mhx1999.top/Article/details/gtlmukjzzh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.havefunace.top/Article/details/gtuazczxva.html

[R08] 数值比较
来源：http://dali.tanke756.top/Article/details/gtlelbqtoe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.havefunace.top/Article/details/gtyvgquboa.html

[R09] 字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnoamagc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daxiang520.top/Article/details/gtjdtkiynl.html

[R10] 正则匹配
来源：http://dali.nwbrower.top/Article/details/gtengwsqax.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hywenlv.cn/Article/details/gtigcyqyuz.html

[R11] case 多分支
来源：http://dali.chenjidiqi.icu/Article/details/gtgkvugzjg.html

case "$1" in
来源：http://dali.gaohongyu789.top/Article/details/gtkyprtpxf.html

start) echo "启动" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnelzdxfw.html

stop)  echo "停止" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtngswactn.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigufen.top/Article/details/gtcsdhwywi.html

esac
来源：http://dali.ybcxt.top/Article/details/gtchaikzrx.html

[R12] for 遍历文件
来源：http://dali.iojbl.cn/Article/details/gttgcdjuby.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxinkj.top/Article/details/gtvcrygquq.html

[R13] for 计数循环
来源：http://dali.gotoacloud.top/Article/details/gtcluhrwzv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gtxjwyvhln.html

[R14] C 风格 for
来源：http://dali.chenzaomai.com/Article/details/gttrxyozlf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.guowangkeji.top/Article/details/gtyhclvijo.html

[R15] while 逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtahsjrywv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yuxming.cn/Article/details/gtgsmghwtn.html

[R16] until 等待条件
来源：http://dali.sweek.top/Article/details/gtgeuyzech.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gtzcnwklry.html

[R17] 数组定义与取值
来源：http://dali.snrcjt.cn/Article/details/gtvkvsbocs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.feifeiyinyue.top/Article/details/gttjixgjqe.html

[R18] 遍历数组
来源：http://dali.sysykeji.top/Article/details/gtyvsdqono.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhongyouzk.top/Article/details/gtvvnngddv.html

[R19] 数组长度
来源：http://dali.0kj1m.cn/Article/details/gtnsiscnqi.html

echo "${#arr[@]}"
来源：http://dali.ivvv.top/Article/details/gtnlxxaipm.html

[R20] 关联数组（字典）
来源：http://dali.daria6918.cn/Article/details/gtuipzdzrc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jyoumei.cn/Article/details/gtvciziosz.html

[R21] 字符串长度
来源：http://dali.iojbl.cn/Article/details/gtotfauxig.html

echo "${#s}"
来源：http://dali.chenlongwang.top/Article/details/gtebtkfvpq.html

[R22] 截取子串
来源：http://dali.cheryme.top/Article/details/gtgcfyqopu.html

echo "${s:0:5}"
来源：http://dali.haohaochexian.top/Article/details/gtkapffawp.html

[R23] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gtemevfrgf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangshuangyany.cn/Article/details/gtuydfkleb.html

[R24] 大小写转换
来源：http://dali.yongpay.top/Article/details/gtscxkdjwd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gtjenlstsl.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuanzhike.top/Article/details/gtexpcujwf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.havefunace.top/Article/details/gtoehtgsqp.html

[R26] 命令替换
来源：http://dali.nanxuanxn.top/Article/details/gtzfphtthl.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgufenzy.top/Article/details/gtedvgtwzx.html

[R27] 算术展开
来源：http://dali.xziqi.cn/Article/details/gtywiycftg.html

echo $((1 + 2 * 3))
来源：http://dali.andypj.xyz/Article/details/gtjdgdztxl.html

[R28] 浮点运算
来源：http://dali.kuanghao11.cn/Article/details/gtcrtkxvfy.html

echo "scale=2; 10/3" | bc
来源：http://dali.hfpthk.cn/Article/details/gtbldsoawp.html

[R29] 定义函数
来源：http://dali.cqqwz.cn/Article/details/gtulfikcjc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xylfe.cn/Article/details/gtoxrmlyqf.html

[R30] 函数返回状态码
来源：http://dali.hysaishi.cn/Article/details/gtqkdznwwm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.meibo888.top/Article/details/gtdwziocnk.html

[R31] 局部变量
来源：http://dali.chenzaomai.com/Article/details/gtusmzdajx.html

f() { local x=1; echo "$x"; }
来源：http://dali.redwolf501.top/Article/details/gtzuvyccie.html

[R32] 参数个数校验
来源：http://dali.sweek.top/Article/details/gtarbknbna.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gtcwjruukb.html

[R33] 捕获错误并提示行号
来源：http://dali.dashuyun.cn/Article/details/gtekjmxxmy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jiagoushi.top/Article/details/gtkzxjmfrd.html

[R34] 退出时清理
来源：http://dali.cashguo.top/Article/details/gttutpfgtt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gtjplivkcy.html

[R35] 后台执行并等待
来源：http://dali.guowangkeji.top/Article/details/gtohyhtwgo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuxming.cn/Article/details/gtjkmhbgkb.html

[R36] 并发执行多个任务
来源：http://dali.sweek.top/Article/details/gteoaqkmsf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.haohaochexian.top/Article/details/gtdxkjkrfe.html

[R37] 把输出赋给变量
来源：http://dali.jqgufenzy.top/Article/details/gtwmszonta.html

files=$(ls -1)
来源：http://dali.tanke756.top/Article/details/gtcmnetckp.html

[R38] 管道串联
来源：http://dali.pycfn.com/Article/details/gtuitionin.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zycfv.cn/Article/details/gtfvynrjqi.html

[R39] 重定向标准输出与错误
来源：http://dali.cucudq.cn/Article/details/gtxaxqaajd.html

cmd > out.log 2>&1
来源：http://dali.havefunace.top/Article/details/gtsixsdeyc.html

[R40] 追加写日志
来源：http://dali.sweek.top/Article/details/gtsgpnubpm.html

echo "log" >> out.log
来源：http://dali.zhongyouzk.top/Article/details/gtpsnfvwab.html

[R41] 丢弃输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfrydkfh.html

cmd >/dev/null 2>&1
来源：http://dali.ivvv.top/Article/details/gtlzztnrsa.html

[R42] 输入重定向
来源：http://dali.chenjidiqi.icu/Article/details/gtfgwlxkqo.html

wc -l < a.txt
来源：http://dali.mhx1999.top/Article/details/gtndidzsie.html

[R43] 按名字查找文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuumrunrm.html

find . -name "*.log" -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gtniizlohy.html

[R44] 按修改时间查找
来源：http://dali.jyoumei.cn/Article/details/gtnltybzhb.html

find . -mtime -7 -type f
来源：http://dali.iojbl.cn/Article/details/gteujadggc.html

[R45] 批量删除
来源：http://dali.haohaochexian.top/Article/details/gthxurqrwk.html

find . -name "*.tmp" -delete
来源：http://dali.meibo888.top/Article/details/gtzftikdnt.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gtylsvsivy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jqgufenzy.top/Article/details/gtmcvebaaw.html

[R47] sed 单行替换
来源：http://dali.wangdashe.top/Article/details/gtfchgrvrk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.daria6918.cn/Article/details/gtddtwzizj.html

[R48] awk 取指定列
来源：http://dali.ppjwa.cn/Article/details/gtmaofloah.html

awk '{print $1, $3}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtdgcfdihl.html

[R49] awk 带条件
来源：http://dali.tian-w.cn/Article/details/gtbgtqkrdy.html


<!-- 参考信息 -->