代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yanxiufei.cn/Article/details/gtosrmzszb.html

user_id INT NOT NULL,
来源：http://dali.hammf.cn/Article/details/gtuevpjkkj.html

amount DECIMAL(10, 2),
来源：http://dali.havefunace.top/Article/details/gtcadaxfpo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nanxuanxn.top/Article/details/gtsducwczm.html

);
来源：http://dali.kuanghao11.cn/Article/details/gthreargjl.html

[Q03] 增加列
来源：http://dali.daria6918.cn/Article/details/gtsodrlhpy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.iojbl.cn/Article/details/gthnbqiznc.html

[Q04] 修改列类型
来源：http://dali.ybcxt.top/Article/details/gtazqyuyes.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xylfe.cn/Article/details/gtrbijwtde.html

[Q05] 重命名列
来源：http://dali.sysykeji.top/Article/details/gtmnlymczn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.fengsongda.top/Article/details/gtcqrblmyr.html

[Q06] 删除列
来源：http://dali.kuanghao11.cn/Article/details/gtrxywzlkt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sweek.top/Article/details/gtibxfskxc.html

[Q07] 删除表
来源：http://dali.daria6918.cn/Article/details/gtuhpbgoqx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.dashuyun.cn/Article/details/gthejhfbfi.html

[Q08] 创建普通索引
来源：http://dali.feifeiyinyue.top/Article/details/gtpfwfnlqv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gtixurvtez.html

[Q09] 创建唯一索引
来源：http://dali.sufxvd.cn/Article/details/gtyrlwysbb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxuanxn.top/Article/details/gtblgkrfif.html

[Q10] 插入单行
来源：http://dali.sysykeji.top/Article/details/gtlmgnocpp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtpmpnnmxs.html

[Q11] 一次插入多行
来源：http://dali.hnqzz.top/Article/details/gtjtpxkyid.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.snrcjt.cn/Article/details/gtdsxhncos.html

[Q12] 插入后取自增 ID
来源：http://dali.dianchejie.cn/Article/details/gtjriefdij.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sufxvd.cn/Article/details/gtjiqweamn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yueranfly.top/Article/details/gtenaaclxv.html

[Q13] 忽略重复插入
来源：http://dali.birdmap.top/Article/details/gtlwpvymqg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guannengcc.top/Article/details/gtswlcgacw.html

[Q14] 存在则更新（upsert）
来源：http://dali.xziqi.cn/Article/details/gtbnvugqep.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.wangshuangyany.cn/Article/details/gtqwmpqbvx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nwbrower.top/Article/details/gtngghnieo.html

[Q15] 查询全部
来源：http://dali.yuxming.cn/Article/details/gtjadaqggz.html

SELECT * FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtlklsihub.html

[Q16] 查询指定列
来源：http://dali.svipenyu.cn/Article/details/gtgqmbozyf.html

SELECT id, name FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtgmnyavwg.html

[Q17] 条件查询
来源：http://dali.guannengcc.top/Article/details/gthsfzkdog.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtaiyioaiw.html

[Q18] 模糊匹配
来源：http://dali.ehwqpu.com/Article/details/gtimwwrguk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxuanxn.top/Article/details/gtptisrlzp.html

[Q19] 范围查询
来源：http://dali.zhiwuduotai.top/Article/details/gtqgpzokcm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zycfv.cn/Article/details/gtbckydvoz.html

[Q20] IN 列表
来源：http://dali.jiagoushi.top/Article/details/gtdszvpzfc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgufenzy.top/Article/details/gtremcused.html

[Q21] 空值判断
来源：http://dali.cheryme.top/Article/details/gtxhljbrle.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.smart0.xyz/Article/details/gtzznosugi.html

[Q22] 排序
来源：http://dali.shzxlz.cn/Article/details/gtaqyydkwr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.aizwys.cn/Article/details/gtljxgegnu.html

[Q23] 分页
来源：http://dali.zycfv.cn/Article/details/gtlzunlnxq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.kuanghao11.cn/Article/details/gtgyjnkewi.html

[Q24] 去重
来源：http://dali.zdqjudy.top/Article/details/gtzwkfrura.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258.top/Article/details/gtbmndrpls.html

[Q25] 只取前 N 条
来源：http://dali.zdqjudy.top/Article/details/gtfyfgvkty.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yvedp.cn/Article/details/gtgtcszinr.html

[Q26] 计数
来源：http://dali.yuxming.cn/Article/details/gtqrcilhjg.html

SELECT COUNT(*) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtdqbjykda.html

[Q27] 条件计数
来源：http://dali.pycfn.com/Article/details/gtqzddgmjp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtupxcqroz.html

[Q28] 求和与平均
来源：http://dali.haohaochexian.top/Article/details/gtbmoyipjh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hammf.cn/Article/details/gtnkusxxnx.html

[Q29] 最大最小值
来源：http://dali.gogol.net.cn/Article/details/gtzqddnofl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtzkdariwz.html

[Q30] 分组统计
来源：http://dali.kuanghao11.cn/Article/details/gtajjknguo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gtgdpfgjhm.html

[Q31] 分组后过滤
来源：http://dali.xylfe.cn/Article/details/gtnclclxdf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtqjeuxrrl.html

[Q32] 分组拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gtfpncsdka.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gtjlqbxetg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jiagoushi.top/Article/details/gtgnigoidb.html

[Q33] 多列分组
来源：http://dali.smart0.xyz/Article/details/gtxdzaepas.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.daxiang520.top/Article/details/gtaduvwtsw.html

[Q34] 每组取第一条
来源：http://dali.nanxuanxn.top/Article/details/gtpeyisqtg.html

SELECT * FROM (
来源：http://dali.sxryk.cn/Article/details/gtxuvogoqy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.9152youxi.cn/Article/details/gtberuyibd.html

) t WHERE rn = 1;
来源：http://dali.bjfxy.top/Article/details/gtrocjchfq.html

[Q35] 内连接
来源：http://dali.gaohongyu789.top/Article/details/gtwidvrfww.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.snrcjt.cn/Article/details/gtiehjiefd.html

[Q36] 左连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshdgyzqz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gtwkyvhmos.html

[Q37] 右连接
来源：http://dali.hongshengwenyu.top/Article/details/gtezfuiigt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yonumen.top/Article/details/gtlhcacfyq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj20258.top/Article/details/gtxugpppce.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcyvjmnqp.html

[Q39] 自连接（查上下级）
来源：http://dali.hywenlv.cn/Article/details/gtixrgachm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cucudq.cn/Article/details/gtdaqdrkhl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hfpthk.cn/Article/details/gtfauncijk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.bjfxy.top/Article/details/gtldxeiapd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yj20258.top/Article/details/gtmcuuwddj.html

[Q41] 多表连接
来源：http://dali.jianghu66.top/Article/details/gtwdumtbdp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nanxinkj.top/Article/details/gtmmdrqdkw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xinyue.icu/Article/details/gtcrhbvttj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hywenlv.cn/Article/details/gtodecttlh.html

[Q42] 连接条件附加过滤
来源：http://dali.jinqigufen.top/Article/details/gtfrrqfmzp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuanzx.com/Article/details/gtggggbqoo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258.top/Article/details/gtexycbkgg.html

[Q43] 标量子查询
来源：http://dali.zhiwuduotai.top/Article/details/gtlqkdxhdj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sxryk.cn/Article/details/gtrskliysk.html

[Q44] IN 子查询
来源：http://dali.yangfankeji.com/Article/details/gtkphwmksh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.fzhhl.top/Article/details/gtymkxfcic.html

[Q45] EXISTS 判断存在
来源：http://dali.yuxming.cn/Article/details/gtbpjtfezr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pycfn.com/Article/details/gtizktqmpl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yangfankeji.com/Article/details/gtevswcrqe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenzaomai.com/Article/details/gtpbndlyiz.html

[Q47] 与平均值比较
来源：http://dali.cheryme.top/Article/details/gtpsspjzot.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gtulydieup.html

[Q48] CTE 公用表表达式
来源：http://dali.yvedp.cn/Article/details/gtmhivegxd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.havefunace.top/Article/details/gtfkbjzext.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxinkj.top/Article/details/gtpbddnomi.html

[Q49] 更新单行
来源：http://dali.zhoulong.xyz/Article/details/gtwcicipnr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gtnbhiutus.html

[Q50] 批量更新
来源：http://dali.yueranfly.top/Article/details/gtwgwripcd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gtzhqpubvr.html

[Q51] 用子查询更新
来源：http://dali.smart0.xyz/Article/details/gtpjxpfvvb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtfhqqqgtd.html

[Q52] 删除指定行
来源：http://dali.zycfv.cn/Article/details/gtwtzfckvg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yangfankeji.com/Article/details/gtkfxkxyap.html

[Q53] 按条件删除
来源：http://dali.c1oappe.top/Article/details/gtkaeyhlxz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gtyhmfhjol.html

[Q54] 清空表
来源：http://dali.jqgufenzy.top/Article/details/gtrjfmbwde.html

TRUNCATE TABLE logs;
来源：http://dali.sweek.top/Article/details/gtrfysjjie.html

[Q55] 排名（并列占位）
来源：http://dali.c1oappe.top/Article/details/gttyeizhbs.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dashuyun.cn/Article/details/gtdlugyvra.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gtcqzwanwl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gtckxpihgb.html

[Q57] 行号
来源：http://dali.yangfankeji.com/Article/details/gthwdzfayv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ivvv.top/Article/details/gthrzwvwvx.html

[Q58] 累计求和
来源：http://dali.havefunace.top/Article/details/gtunfiiifh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtqyujzqkq.html

[Q59] 分组内累计
来源：http://dali.smart0.xyz/Article/details/gtdrnunmlx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gthncbbtst.html

[Q60] 取上一行 / 下一行
来源：http://dali.vqdsnc.cn/Article/details/gtoruobjpj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj20258.top/Article/details/gtwvtoahxz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtigdqzxox.html

[Q61] 移动平均
来源：http://dali.xziqi.cn/Article/details/gtesquqpgk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtaqpbgcza.html

[Q62] 分组占比
来源：http://dali.tanke756.top/Article/details/gthpnlenbr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtyfjjusax.html

[Q63] 开启事务
来源：http://dali.nanxinkj.top/Article/details/gtcdmbptva.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yonumen.top/Article/details/gtxajxqtxp.html

[Q64] 提交事务
来源：http://dali.nwbrower.top/Article/details/gthsvchdew.html

COMMIT;
来源：http://dali.zhengqikj.top/Article/details/gtcyivdfaf.html

[Q65] 回滚事务
来源：http://dali.vqdsnc.cn/Article/details/gtsnrfjvte.html

ROLLBACK;
来源：http://dali.feifeiyinyue.top/Article/details/gtmsejslcq.html

[Q66] 行锁查询
来源：http://dali.yj20258888.top/Article/details/gtqjsflvld.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.vqdsnc.cn/Article/details/gtykbupypu.html

[Q67] 设置隔离级别
来源：http://dali.tanke756.top/Article/details/gtoinsfnkn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ivvv.top/Article/details/gtlxdhrwcu.html

[Q68] 保存点
来源：http://dali.yanxiufei.cn/Article/details/gtdzmmepue.html

SAVEPOINT sp1;
来源：http://dali.hywenlv.cn/Article/details/gtjfmrejol.html

ROLLBACK TO sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpasguxzl.html

[Q69] 查看执行计划
来源：http://dali.ppjwa.cn/Article/details/gtskkjacis.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fengsongda.top/Article/details/gtgkcddtyj.html

[Q70] 更新统计信息
来源：http://dali.yvedp.cn/Article/details/gtyrqgwcnh.html

ANALYZE TABLE users;
来源：http://dali.yuxming.cn/Article/details/gtxjfjihhm.html

[Q71] 查看建表语句
来源：http://dali.cucudq.cn/Article/details/gtwxfnhmqi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.316326.xyz/Article/details/gtzalobjcz.html

[Q72] 查看索引
来源：http://dali.havefunace.top/Article/details/gtzeflcfwr.html

SHOW INDEX FROM users;
来源：http://dali.yongpay.top/Article/details/gthyjexwht.html

[Q73] 查看表状态
来源：http://dali.dashuyun.cn/Article/details/gtrvxippek.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.bjfxy.top/Article/details/gtogqxvmrl.html

[Q74] 强制使用索引
来源：http://dali.gaohongyu789.top/Article/details/gtckivfaws.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yueranfly.top/Article/details/gtlhdggyzk.html

[Q75] 日期格式化
来源：http://dali.xziqi.cn/Article/details/gtgmvjfoym.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cashguo.top/Article/details/gtpaodugdb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cucudq.cn/Article/details/gtsqyktsaa.html

[Q76] 按天统计
来源：http://dali.aizwys.cn/Article/details/gthuwhjrut.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nwbrower.top/Article/details/gtvufwjkjk.html

[Q77] 时间加减
来源：http://dali.guannengcc.top/Article/details/gtyvpkccop.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ppjwa.cn/Article/details/gtzxbzcokl.html

[Q78] 当前时间
来源：http://dali.xylfe.cn/Article/details/gtjfktjxrl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.0kj1m.cn/Article/details/gteoxautwa.html

[Q79] 字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgwojdkf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj20258.top/Article/details/gtaizlbawb.html

[Q80] 字符串截取
来源：http://dali.zhongyouzk.top/Article/details/gtugwlwtgo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtadizyerj.html

[Q81] 字符串替换
来源：http://dali.yj20258.top/Article/details/gtstqytszo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.316326.xyz/Article/details/gttrztztnu.html

[Q82] 字符长度与字节长度
来源：http://dali.nanxinkj.top/Article/details/gtzimaktfi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gthvljruxy.html

[Q83] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gtkkgmtpgs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtzwfdbrke.html

[Q84] 去除首尾空格
来源：http://dali.kuanghao11.cn/Article/details/gtlpjldsaa.html

SELECT TRIM(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gtxpereisi.html

[Q85] 数值取整
来源：http://dali.haohaochexian.top/Article/details/gtvolrkroi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.snrcjt.cn/Article/details/gtwkqjkeps.html

[Q86] 读取 JSON 字段
来源：http://dali.zhixingplan.top/Article/details/gtgugdwxjf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhixingplan.top/Article/details/gtpootyaqp.html

[Q87] JSON 字段做条件
来源：http://dali.cdnleiting.top/Article/details/gtctllisyf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.snrcjt.cn/Article/details/gtrqdlpqup.html

[Q88] 行转列（条件聚合）
来源：http://dali.tian-w.cn/Article/details/gtdkitmipl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.iojbl.cn/Article/details/gtyxieewrg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daxiang520.top/Article/details/gtfnhcgoup.html

[Q89] 判断表是否存在
来源：http://dali.hysaishi.cn/Article/details/gtkfcahwog.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.bjfxy.top/Article/details/gttlqsnude.html

[Q90] 生成序号列
来源：http://dali.pycfn.com/Article/details/gtpbzpanar.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yuanzhike.top/Article/details/gtywnhrzab.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtmhwramtx.html

R. Bash 专题
来源：http://dali.feifeiyinyue.top/Article/details/gtxzvyqpkq.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtezskmvjm.html

[R01] shebang 与严格模式
来源：http://dali.hnqzz.top/Article/details/gteyumxdct.html

#!/usr/bin/env bash
来源：http://dali.aizwys.cn/Article/details/gtvwuerzjw.html

set -euo pipefail
来源：http://dali.pycfn.com/Article/details/gtxbbtmnpw.html

[R02] 变量赋值与使用
来源：http://dali.pycfn.com/Article/details/gthajkfgiq.html

name="Tom"; echo "$name"
来源：http://dali.jinghuilouyu.cn/Article/details/gtzctjzdml.html

[R03] 只读变量
来源：http://dali.jianghu66.top/Article/details/gtdgdyskdz.html

readonly PI=3.14
来源：http://dali.chenjidiqi.icu/Article/details/gtfkmdjttf.html

[R04] 位置参数
来源：http://dali.ydzc1.top/Article/details/gtapqlcwtg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqilwphme.html

[R05] 参数默认值
来源：http://dali.sxryk.cn/Article/details/gtuctfskmk.html

name="${1:-default}"
来源：http://dali.pengpengdd.cyou/Article/details/gthkpjjhwv.html

[R06] 判断命令是否存在
来源：http://dali.ppjwa.cn/Article/details/gtzzvftfmx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.kuanghao11.cn/Article/details/gtpzhlerxd.html

[R07] if 判断文件
来源：http://dali.pengpengdd.cyou/Article/details/gtyxuztoat.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.9152youxi.cn/Article/details/gtmtoyqufe.html

[R08] 数值比较
来源：http://dali.xuetiantiany.cn/Article/details/gtwyztegxw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daxiang520.top/Article/details/gtrflmiajs.html

[R09] 字符串比较
来源：http://dali.xinyue.icu/Article/details/gtemdvcdbm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhengqikj.top/Article/details/gtbbufykdf.html

[R10] 正则匹配
来源：http://dali.hnqzz.top/Article/details/gtezvgrkiy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj202588.top/Article/details/gtchipyzgb.html

[R11] case 多分支
来源：http://dali.kuanghao11.cn/Article/details/gtspuqlwfz.html

case "$1" in
来源：http://dali.jianghu66.top/Article/details/gtprqbddau.html

start) echo "启动" ;;
来源：http://dali.haohaochexian.top/Article/details/gteegkjmly.html

stop)  echo "停止" ;;
来源：http://dali.andypj.xyz/Article/details/gtaydpzpil.html

*)     echo "未知命令" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtskyeowdy.html

esac
来源：http://dali.tian-w.cn/Article/details/gtfvuikpxt.html

[R12] for 遍历文件
来源：http://dali.nwbrower.top/Article/details/gteeysfcin.html

for f in *.txt; do echo "$f"; done
来源：http://dali.svipenyu.cn/Article/details/gtybjrgzuk.html

[R13] for 计数循环
来源：http://dali.jinqigfzy.top/Article/details/gtsdxarqox.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gtrxrdclxf.html

[R14] C 风格 for
来源：http://dali.fzhhl.top/Article/details/gteeehgple.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gtukgepdvl.html

[R15] while 逐行读文件
来源：http://dali.316326.xyz/Article/details/gtjyezoehu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fengsongda.top/Article/details/gtbtgmxble.html

[R16] until 等待条件
来源：http://dali.iojbl.cn/Article/details/gthizmkxvr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guowangkeji.top/Article/details/gtaepxhqox.html

[R17] 数组定义与取值
来源：http://dali.hfpthk.cn/Article/details/gtgeltwhhs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj202588.top/Article/details/gtbvgnwaoi.html

[R18] 遍历数组
来源：http://dali.zhengqikj.top/Article/details/gtnxkvvszw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yvedp.cn/Article/details/gtlhgbeflo.html

[R19] 数组长度
来源：http://dali.fzhhl.top/Article/details/gtzzgqfntr.html

echo "${#arr[@]}"
来源：http://dali.shuidangran.top/Article/details/gtlsahzzxt.html

[R20] 关联数组（字典）
来源：http://dali.havefunace.top/Article/details/gttuhcxvvv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.snrcjt.cn/Article/details/gtrdmpjwyv.html

[R21] 字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtbkpquqmo.html

echo "${#s}"
来源：http://dali.ydzc1.top/Article/details/gtjopmgfik.html

[R22] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gtvydstvlc.html

echo "${s:0:5}"
来源：http://dali.chenjidiqi.icu/Article/details/gtxojuvbrg.html

[R23] 字符串替换
来源：http://dali.chenlongwang.top/Article/details/gtgxafikqg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sweek.top/Article/details/gtcozadnsz.html

[R24] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gtebzjhrtq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhongyouzk.top/Article/details/gtctlxoacv.html

[R25] 去后缀 / 去前缀
来源：http://dali.hammf.cn/Article/details/gtbkqcaifb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shzxlz.cn/Article/details/gtympaaazr.html

[R26] 命令替换
来源：http://dali.hammf.cn/Article/details/gtkxtikvuw.html

now=$(date +%F); echo "$now"
来源：http://dali.xziqi.cn/Article/details/gtkeejukbc.html

[R27] 算术展开
来源：http://dali.jqgufenzy.top/Article/details/gtklfwtass.html

echo $((1 + 2 * 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaeibojyh.html

[R28] 浮点运算
来源：http://dali.chenzaomai.com/Article/details/gtrptxaagr.html

echo "scale=2; 10/3" | bc
来源：http://dali.dashuyun.cn/Article/details/gtzxjkazjn.html

[R29] 定义函数
来源：http://dali.xuanzx.com/Article/details/gtcuglqogi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.c1oappe.top/Article/details/gttykhiequ.html

[R30] 函数返回状态码
来源：http://dali.ppjwa.cn/Article/details/gtdlgafpnj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ehwqpu.com/Article/details/gtouxteiix.html

[R31] 局部变量
来源：http://dali.ybcxt.top/Article/details/gtkfgdohgy.html

f() { local x=1; echo "$x"; }
来源：http://dali.nwbrower.top/Article/details/gtznzrkabr.html

[R32] 参数个数校验
来源：http://dali.yj202588.top/Article/details/gtoskaibhi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yanxiufei.cn/Article/details/gtzorslcnm.html

[R33] 捕获错误并提示行号
来源：http://dali.xinyue.icu/Article/details/gtzwxsmncz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cdnleiting.top/Article/details/gthlclrndf.html

[R34] 退出时清理
来源：http://dali.cashguo.top/Article/details/gtrkfjkbgq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gtjdfaqlfe.html

[R35] 后台执行并等待
来源：http://dali.ivvv.top/Article/details/gttzrynkwm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.smart0.xyz/Article/details/gtzmijyhnd.html

[R36] 并发执行多个任务
来源：http://dali.sufxvd.cn/Article/details/gtbacwuzqk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnxiangtu.top/Article/details/gtwfqeunry.html

[R37] 把输出赋给变量
来源：http://dali.zhoulong.xyz/Article/details/gttfrgvfsg.html

files=$(ls -1)
来源：http://dali.c1oappe.top/Article/details/gttwnbewlc.html

[R38] 管道串联
来源：http://dali.feifeiyinyue.top/Article/details/gtncalzlbs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.vqdsnc.cn/Article/details/gtcoduhign.html

[R39] 重定向标准输出与错误
来源：http://dali.zycfv.cn/Article/details/gtmvecvdhh.html

cmd > out.log 2>&1
来源：http://dali.quarkkingdee.top/Article/details/gtxsdpxgxb.html

[R40] 追加写日志
来源：http://dali.xuetiantiany.cn/Article/details/gtxqzpzksw.html

echo "log" >> out.log
来源：http://dali.tian-w.cn/Article/details/gtsuovwbif.html

[R41] 丢弃输出
来源：http://dali.wangshuangyany.cn/Article/details/gteglwloml.html

cmd >/dev/null 2>&1
来源：http://dali.cdnleiting.top/Article/details/gtwlcucxdh.html

[R42] 输入重定向
来源：http://dali.aizwys.cn/Article/details/gtttffwbhu.html

wc -l < a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtkvsmtbpg.html

[R43] 按名字查找文件
来源：http://dali.guowangkeji.top/Article/details/gtfafgpanh.html

find . -name "*.log" -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxrzpcmn.html

[R44] 按修改时间查找
来源：http://dali.zhixingplan.top/Article/details/gtewahnzwh.html

find . -mtime -7 -type f
来源：http://dali.gaohongyu789.top/Article/details/gtwunrdgwj.html

[R45] 批量删除
来源：http://dali.daxiang520.top/Article/details/gtdsusozgb.html

find . -name "*.tmp" -delete
来源：http://dali.kuanghao11.cn/Article/details/gtbnlabvia.html

[R46] 递归替换文件内容
来源：http://dali.sysykeji.top/Article/details/gtwpebhwzc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fzhhl.top/Article/details/gtaftcjcbh.html

[R47] sed 单行替换
来源：http://dali.316326.xyz/Article/details/gtpizvvasd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtifvbfphc.html

[R48] awk 取指定列
来源：http://dali.aibaodan.cn/Article/details/gtggtaqsvc.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtygnxaiya.html

[R49] awk 带条件
来源：http://dali.cqqwz.cn/Article/details/gtmuisqryp.html


<!-- 参考信息 -->