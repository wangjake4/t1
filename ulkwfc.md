代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yongpay.top/Article/details/gtslkhcsfz.html

user_id INT NOT NULL,
来源：http://dali.hnxiangtu.top/Article/details/gtglqxvrmu.html

amount DECIMAL(10, 2),
来源：http://dali.zdqjudy.top/Article/details/gthvfgpcxn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zycfv.cn/Article/details/gtrdqlckcp.html

);
来源：http://dali.0kj1m.cn/Article/details/gtfnrsdcdh.html

[Q03] 增加列
来源：http://dali.vqdsnc.cn/Article/details/gtguwjprti.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jiagoushi.top/Article/details/gtlthzqynv.html

[Q04] 修改列类型
来源：http://dali.yuxming.cn/Article/details/gtgwwdkqxo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daxiang520.top/Article/details/gtffgqypyu.html

[Q05] 重命名列
来源：http://dali.mhx1999.top/Article/details/gtvreqdrjd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.svipenyu.cn/Article/details/gtbqnlbkkn.html

[Q06] 删除列
来源：http://dali.zhiwuduotai.top/Article/details/gtczrqhbez.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jianghu66.top/Article/details/gtohbacjvm.html

[Q07] 删除表
来源：http://dali.jiagoushi.top/Article/details/gtzajbxvnw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.fengsongda.top/Article/details/gtqvyabwjv.html

[Q08] 创建普通索引
来源：http://dali.zycfv.cn/Article/details/gtdjeosmwj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gtuqxnsucg.html

[Q09] 创建唯一索引
来源：http://dali.wangdashe.top/Article/details/gteouyjmcu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gtmldaowhg.html

[Q10] 插入单行
来源：http://dali.birdmap.top/Article/details/gtmaipjsud.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuxming.cn/Article/details/gtxwkjiymt.html

[Q11] 一次插入多行
来源：http://dali.aizwys.cn/Article/details/gtvsffzeun.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkgseyeb.html

[Q12] 插入后取自增 ID
来源：http://dali.jyoumei.cn/Article/details/gtajvuqagm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cashguo.top/Article/details/gtvmclabpk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.bjfxy.top/Article/details/gtjbongrwg.html

[Q13] 忽略重复插入
来源：http://dali.hnxiangtu.top/Article/details/gtnpwozqda.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yuxming.cn/Article/details/gtfwoijzxs.html

[Q14] 存在则更新（upsert）
来源：http://dali.gzhubu.top/Article/details/gtveagrvss.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzscnuaob.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhengqikj.top/Article/details/gtddwsftbv.html

[Q15] 查询全部
来源：http://dali.svipenyu.cn/Article/details/gtnhsnrbvz.html

SELECT * FROM users;
来源：http://dali.zycfv.cn/Article/details/gtekhwcajz.html

[Q16] 查询指定列
来源：http://dali.jyoumei.cn/Article/details/gtufvbvhlh.html

SELECT id, name FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtosutkrrz.html

[Q17] 条件查询
来源：http://dali.yj20258.top/Article/details/gtfxvxtedm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jianghu66.top/Article/details/gtziznjasv.html

[Q18] 模糊匹配
来源：http://dali.haohaochexian.top/Article/details/gtykvnahwc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cheryme.top/Article/details/gtmeblsgks.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gtbfrdqjtv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.bjfxy.top/Article/details/gtyxwhtfxx.html

[Q20] IN 列表
来源：http://dali.kuanghao11.cn/Article/details/gtiqluyjmx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ppjwa.cn/Article/details/gtgsyodplf.html

[Q21] 空值判断
来源：http://dali.ydzc1.top/Article/details/gtzvlnbcmq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.c1oappe.top/Article/details/gtmxzlasnv.html

[Q22] 排序
来源：http://dali.jqgufenzy.top/Article/details/gtqmperiqo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sysykeji.top/Article/details/gtqfngxjwb.html

[Q23] 分页
来源：http://dali.iojbl.cn/Article/details/gtajcndwhu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuxming.cn/Article/details/gtrxsnpxlt.html

[Q24] 去重
来源：http://dali.hnqzz.top/Article/details/gtipfksaji.html

SELECT DISTINCT city FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtneomvnne.html

[Q25] 只取前 N 条
来源：http://dali.shangyingyoupin.top/Article/details/gtddckvqwm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.9152youxi.cn/Article/details/gtgnqkqjbi.html

[Q26] 计数
来源：http://dali.fzhhl.top/Article/details/gtzvcxzuta.html

SELECT COUNT(*) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtcenviijg.html

[Q27] 条件计数
来源：http://dali.shzxlz.cn/Article/details/gtrzbvyqmp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yongpay.top/Article/details/gtunzyoono.html

[Q28] 求和与平均
来源：http://dali.meibo888.top/Article/details/gtcgmjbvml.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtgzuafrzd.html

[Q29] 最大最小值
来源：http://dali.dianchejie.cn/Article/details/gtkxvgbhub.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtjtjiaulb.html

[Q30] 分组统计
来源：http://dali.zdqjudy.top/Article/details/gtynykrmuf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gtudoacxae.html

[Q31] 分组后过滤
来源：http://dali.fzhhl.top/Article/details/gtzurxotsl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ivvv.top/Article/details/gtymroqvfk.html

[Q32] 分组拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gthskyflsa.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtvowhdyqu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdirhnuxz.html

[Q33] 多列分组
来源：http://dali.tanke756.top/Article/details/gtjarmzsuq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xinyue.icu/Article/details/gtycvxvabt.html

[Q34] 每组取第一条
来源：http://dali.wangdashe.top/Article/details/gtwurcopid.html

SELECT * FROM (
来源：http://dali.andypj.xyz/Article/details/gtzmqqyheq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nwbrower.top/Article/details/gtcjawcwja.html

) t WHERE rn = 1;
来源：http://dali.yvedp.cn/Article/details/gtjjehvvyr.html

[Q35] 内连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtchxsdydw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gtvkxqpliu.html

[Q36] 左连接
来源：http://dali.yuanzhike.top/Article/details/gtdfqtuspe.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cucudq.cn/Article/details/gtqszaegjw.html

[Q37] 右连接
来源：http://dali.birdmap.top/Article/details/gtmxtvcnpg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctehmtby.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.wangshuangyany.cn/Article/details/gtopblonyl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nwbrower.top/Article/details/gtsobrobft.html

[Q39] 自连接（查上下级）
来源：http://dali.smart0.xyz/Article/details/gtxubztlrq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhoulong.xyz/Article/details/gtgaspvuyk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hywenlv.cn/Article/details/gtmdmysmjr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.birdmap.top/Article/details/gttcdufxhp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.svipenyu.cn/Article/details/gtolyeubgf.html

[Q41] 多表连接
来源：http://dali.yj202588.top/Article/details/gtvzoumqfv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cdnleiting.top/Article/details/gtakvhvsvh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.mhx1999.top/Article/details/gtgijftumq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.pycfn.com/Article/details/gtvpodjtms.html

[Q42] 连接条件附加过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtjctmqzix.html

SELECT u.name, o.amount FROM users u
来源：http://dali.c1oappe.top/Article/details/gtxxpncagn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.snrcjt.cn/Article/details/gtmnolidik.html

[Q43] 标量子查询
来源：http://dali.jyoumei.cn/Article/details/gtnoskwvwb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cucudq.cn/Article/details/gtdzqwnmnk.html

[Q44] IN 子查询
来源：http://dali.c1oappe.top/Article/details/gteyiyloxm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhixingplan.top/Article/details/gttqjelkkk.html

[Q45] EXISTS 判断存在
来源：http://dali.birdmap.top/Article/details/gtpnmojqzq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gtdobldmme.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.smart0.xyz/Article/details/gtpvvbxcfn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gtnvvidgde.html

[Q47] 与平均值比较
来源：http://dali.316326.xyz/Article/details/gtnwltssds.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xylfe.cn/Article/details/gtsuhyvthp.html

[Q48] CTE 公用表表达式
来源：http://dali.chenlongwang.top/Article/details/gtletnhsjo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sysykeji.top/Article/details/gtgtlcmmsr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.mhx1999.top/Article/details/gtmupjofnk.html

[Q49] 更新单行
来源：http://dali.yangfankeji.com/Article/details/gtbldafnst.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gtnzevafsx.html

[Q50] 批量更新
来源：http://dali.ydzc1.top/Article/details/gtifzfxugt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tian-w.cn/Article/details/gtzvcoygit.html

[Q51] 用子查询更新
来源：http://dali.yonumen.top/Article/details/gtkgkdqdrc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtrueleupk.html

[Q52] 删除指定行
来源：http://dali.havefunace.top/Article/details/gtpbzmfliv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.316326.xyz/Article/details/gtxxxlbapj.html

[Q53] 按条件删除
来源：http://dali.dianchejie.cn/Article/details/gtjppzfooy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sxryk.cn/Article/details/gtcdnzheex.html

[Q54] 清空表
来源：http://dali.dashuyun.cn/Article/details/gtfznldhto.html

TRUNCATE TABLE logs;
来源：http://dali.havefunace.top/Article/details/gtehhqacuk.html

[Q55] 排名（并列占位）
来源：http://dali.yangfankeji.com/Article/details/gtxhpfeuef.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yvedp.cn/Article/details/gtwbkrejok.html

[Q56] 密集排名（并列不占位）
来源：http://dali.svipenyu.cn/Article/details/gtvmsvvudy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ydzc1.top/Article/details/gtpsjivjbd.html

[Q57] 行号
来源：http://dali.chenjidiqi.icu/Article/details/gtgqihhxrm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtpkqtezna.html

[Q58] 累计求和
来源：http://dali.birdmap.top/Article/details/gtdforxsem.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtsnalczfy.html

[Q59] 分组内累计
来源：http://dali.zhongyouzk.top/Article/details/gthwjmzqfs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtimjeioai.html

[Q60] 取上一行 / 下一行
来源：http://dali.hywenlv.cn/Article/details/gtritcsnrn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.316326.xyz/Article/details/gtnfvdxyfe.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtvvczjvsf.html

[Q61] 移动平均
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjntkppc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtzzalcrea.html

[Q62] 分组占比
来源：http://dali.mhx1999.top/Article/details/gtgowjgmni.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gtdeqctoch.html

[Q63] 开启事务
来源：http://dali.guowangkeji.top/Article/details/gtrjdirdaz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhengqikj.top/Article/details/gtwtlsnrbk.html

[Q64] 提交事务
来源：http://dali.wangshuangyany.cn/Article/details/gtizmhvvax.html

COMMIT;
来源：http://dali.guannengcc.top/Article/details/gtmxxvnzib.html

[Q65] 回滚事务
来源：http://dali.xuanzx.com/Article/details/gtizolzbni.html

ROLLBACK;
来源：http://dali.yueranfly.top/Article/details/gtxjmvadri.html

[Q66] 行锁查询
来源：http://dali.gogol.net.cn/Article/details/gtturudhse.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.redwolf501.top/Article/details/gtaswpzdrs.html

[Q67] 设置隔离级别
来源：http://dali.yangfankeji.com/Article/details/gtmcqjbjit.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.kuanghao11.cn/Article/details/gtifzmpgvw.html

[Q68] 保存点
来源：http://dali.jyoumei.cn/Article/details/gtcckjhvyu.html

SAVEPOINT sp1;
来源：http://dali.zhiwuduotai.top/Article/details/gtjiwplvxy.html

ROLLBACK TO sp1;
来源：http://dali.mhx1999.top/Article/details/gtrycelivi.html

[Q69] 查看执行计划
来源：http://dali.fzhhl.top/Article/details/gtktblamzg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhiwuduotai.top/Article/details/gtjctpnujn.html

[Q70] 更新统计信息
来源：http://dali.smart0.xyz/Article/details/gthoaoiqxc.html

ANALYZE TABLE users;
来源：http://dali.yangfankeji.com/Article/details/gttdpgurpv.html

[Q71] 查看建表语句
来源：http://dali.jqgufenzy.top/Article/details/gtxlwszmla.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenjidiqi.icu/Article/details/gtxyuqsldp.html

[Q72] 查看索引
来源：http://dali.hnqzz.top/Article/details/gtzzmeugiv.html

SHOW INDEX FROM users;
来源：http://dali.yueranfly.top/Article/details/gtwktkplbz.html

[Q73] 查看表状态
来源：http://dali.jiagoushi.top/Article/details/gtdzlfkfdp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkorpdrv.html

[Q74] 强制使用索引
来源：http://dali.tian-w.cn/Article/details/gtodxmwair.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hnxiangtu.top/Article/details/gtrtoqjkss.html

[Q75] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gtpdmyibbe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtbtbfgvuz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jiagoushi.top/Article/details/gtsgbrttil.html

[Q76] 按天统计
来源：http://dali.yuxming.cn/Article/details/gtjfitmvls.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nwbrower.top/Article/details/gtanzvqmyk.html

[Q77] 时间加减
来源：http://dali.yj202588.top/Article/details/gtltgwcgzd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj20258888.top/Article/details/gtaftclrxg.html

[Q78] 当前时间
来源：http://dali.nanxuanxn.top/Article/details/gtcemnmoga.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.aibaodan.cn/Article/details/gtwgmzhvbm.html

[Q79] 字符串拼接
来源：http://dali.hywenlv.cn/Article/details/gtfovlyyua.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hammf.cn/Article/details/gtahcztgcn.html

[Q80] 字符串截取
来源：http://dali.cashguo.top/Article/details/gtnlblniqv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtotntucjo.html

[Q81] 字符串替换
来源：http://dali.tanke756.top/Article/details/gtxidruhrv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yongpay.top/Article/details/gtyycozdmy.html

[Q82] 字符长度与字节长度
来源：http://dali.mhx1999.top/Article/details/gtoohvobka.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrtyakqe.html

[Q83] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gtwguwqvcm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtkpkgbtjn.html

[Q84] 去除首尾空格
来源：http://dali.cqqwz.cn/Article/details/gtqcnhujxe.html

SELECT TRIM(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtupvgqrgs.html

[Q85] 数值取整
来源：http://dali.0kj1m.cn/Article/details/gtoptsifth.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cheryme.top/Article/details/gtjkozspeq.html

[Q86] 读取 JSON 字段
来源：http://dali.cucudq.cn/Article/details/gttphzxokr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.kuanghao11.cn/Article/details/gtkjambmga.html

[Q87] JSON 字段做条件
来源：http://dali.xziqi.cn/Article/details/gtcuzomhoo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jqgufenzy.top/Article/details/gtlmibcdql.html

[Q88] 行转列（条件聚合）
来源：http://dali.yvedp.cn/Article/details/gtgksqoedf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ydzc1.top/Article/details/gtqaxmqbii.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuanzx.com/Article/details/gtuprnwyvp.html

[Q89] 判断表是否存在
来源：http://dali.tianlin.xyz/Article/details/gtwlbptjmz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gzhubu.top/Article/details/gtosbuumos.html

[Q90] 生成序号列
来源：http://dali.sufxvd.cn/Article/details/gtottctbie.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yanxiufei.cn/Article/details/gtcbkcyjlr.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtwoefdemn.html

R. Bash 专题
来源：http://dali.birdmap.top/Article/details/gtxxrtymlu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtpbebvmyx.html

[R01] shebang 与严格模式
来源：http://dali.aizwys.cn/Article/details/gtjrpcgwaf.html

#!/usr/bin/env bash
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkakaqkvp.html

set -euo pipefail
来源：http://dali.chenzaomai.com/Article/details/gtbuqpdrtk.html

[R02] 变量赋值与使用
来源：http://dali.cdnleiting.top/Article/details/gtpyqexjbd.html

name="Tom"; echo "$name"
来源：http://dali.andypj.xyz/Article/details/gtxfvmcnnc.html

[R03] 只读变量
来源：http://dali.xuetiantiany.cn/Article/details/gtwlozykly.html

readonly PI=3.14
来源：http://dali.cheryme.top/Article/details/gtjherhlwm.html

[R04] 位置参数
来源：http://dali.cqqwz.cn/Article/details/gtwajxzpwi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.guannengcc.top/Article/details/gtgblyvqlc.html

[R05] 参数默认值
来源：http://dali.hywenlv.cn/Article/details/gtwfqiwapy.html

name="${1:-default}"
来源：http://dali.fengsongda.top/Article/details/gtvnqxjmqw.html

[R06] 判断命令是否存在
来源：http://dali.cdnleiting.top/Article/details/gtsouogwsu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gtmxkopjsd.html

[R07] if 判断文件
来源：http://dali.c1oappe.top/Article/details/gtnztemzji.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pycfn.com/Article/details/gtlbevudtu.html

[R08] 数值比较
来源：http://dali.hongshengwenyu.top/Article/details/gtcxwdjgtz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cheryme.top/Article/details/gtjdaczbkr.html

[R09] 字符串比较
来源：http://dali.yangfankeji.com/Article/details/gtjwufimrt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtzcynazrb.html

[R10] 正则匹配
来源：http://dali.yuanzhike.top/Article/details/gtytmvytes.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhoulong.xyz/Article/details/gthlehwqgn.html

[R11] case 多分支
来源：http://dali.hammf.cn/Article/details/gtmkhfsfud.html

case "$1" in
来源：http://dali.jyoumei.cn/Article/details/gtqtppsrfg.html

start) echo "启动" ;;
来源：http://dali.cucudq.cn/Article/details/gtfitkxajl.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxikzfuf.html

*)     echo "未知命令" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmrszxiog.html

esac
来源：http://dali.tian-w.cn/Article/details/gtvkfmcjce.html

[R12] for 遍历文件
来源：http://dali.zycfv.cn/Article/details/gtgscrsymv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yangfankeji.com/Article/details/gtduzalxiu.html

[R13] for 计数循环
来源：http://dali.zhixingplan.top/Article/details/gttwwinwax.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gtncibylch.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gtxkoejvvx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhoulong.xyz/Article/details/gtzgflrgns.html

[R15] while 逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjnnlswl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hnxiangtu.top/Article/details/gtrriacmwh.html

[R16] until 等待条件
来源：http://dali.dashuyun.cn/Article/details/gttvndgmhm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gaohongyu789.top/Article/details/gtuojswwhv.html

[R17] 数组定义与取值
来源：http://dali.jqgufenzy.top/Article/details/gtdwjwkgzs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zycfv.cn/Article/details/gtauwfmsoz.html

[R18] 遍历数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdoxbbtaa.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cdnleiting.top/Article/details/gtselzaflt.html

[R19] 数组长度
来源：http://dali.mhx1999.top/Article/details/gtmlirmlxp.html

echo "${#arr[@]}"
来源：http://dali.zhengqikj.top/Article/details/gtzugysyqf.html

[R20] 关联数组（字典）
来源：http://dali.hysaishi.cn/Article/details/gtqykkfaei.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuxming.cn/Article/details/gtwpjaphol.html

[R21] 字符串长度
来源：http://dali.shzxlz.cn/Article/details/gttctftjba.html

echo "${#s}"
来源：http://dali.jlsjyb.cn/Article/details/gtczyvkqis.html

[R22] 截取子串
来源：http://dali.pengpengdd.cyou/Article/details/gttmfayzzk.html

echo "${s:0:5}"
来源：http://dali.nanxuanxn.top/Article/details/gtocuctyia.html

[R23] 字符串替换
来源：http://dali.nanxinkj.top/Article/details/gtmrhbtjsn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gogol.net.cn/Article/details/gtxjlkbvqi.html

[R24] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gtupysnowg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenjidiqi.icu/Article/details/gtfnslhbnk.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhoulong.xyz/Article/details/gtfjvlahqn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sxryk.cn/Article/details/gtrgmxsnaz.html

[R26] 命令替换
来源：http://dali.gaohongyu789.top/Article/details/gtdtqswgzm.html

now=$(date +%F); echo "$now"
来源：http://dali.yj20258.top/Article/details/gtlcudaaip.html

[R27] 算术展开
来源：http://dali.mhx1999.top/Article/details/gtvpsnuupk.html

echo $((1 + 2 * 3))
来源：http://dali.aizwys.cn/Article/details/gtzwvyoekn.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gtiulntwvj.html

echo "scale=2; 10/3" | bc
来源：http://dali.sxryk.cn/Article/details/gtddepmphh.html

[R29] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gtqsbrafus.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dianchejie.cn/Article/details/gtswxhhcye.html

[R30] 函数返回状态码
来源：http://dali.nwbrower.top/Article/details/gtsdjxtora.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jiagoushi.top/Article/details/gtgqgzwjsj.html

[R31] 局部变量
来源：http://dali.ivvv.top/Article/details/gtwimzxnnf.html

f() { local x=1; echo "$x"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjiagnyc.html

[R32] 参数个数校验
来源：http://dali.shuidangran.top/Article/details/gttkoxdjag.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gtvfsimmzf.html

[R33] 捕获错误并提示行号
来源：http://dali.hfpthk.cn/Article/details/gtitugnxaw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.9152youxi.cn/Article/details/gtauqhuqyx.html

[R34] 退出时清理
来源：http://dali.yvedp.cn/Article/details/gtjxgcasic.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gthhjbxmle.html

[R35] 后台执行并等待
来源：http://dali.ybcxt.top/Article/details/gtcbaantzq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgfzy.top/Article/details/gtpweriikk.html

[R36] 并发执行多个任务
来源：http://dali.ivvv.top/Article/details/gtxrpoaamb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhoulong.xyz/Article/details/gttnoyqrjl.html

[R37] 把输出赋给变量
来源：http://dali.sweek.top/Article/details/gtvpjqbmru.html

files=$(ls -1)
来源：http://dali.hysaishi.cn/Article/details/gtetegctsp.html

[R38] 管道串联
来源：http://dali.jyoumei.cn/Article/details/gtceviebie.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gotoacloud.top/Article/details/gtrfylhefn.html

[R39] 重定向标准输出与错误
来源：http://dali.sxryk.cn/Article/details/gttchvngeb.html

cmd > out.log 2>&1
来源：http://dali.tanke756.top/Article/details/gtsgzmtcuy.html

[R40] 追加写日志
来源：http://dali.daria6918.cn/Article/details/gtsdmzbxkl.html

echo "log" >> out.log
来源：http://dali.zhiwuduotai.top/Article/details/gtpdfmmnza.html

[R41] 丢弃输出
来源：http://dali.zhixingplan.top/Article/details/gtuvpwdsyf.html

cmd >/dev/null 2>&1
来源：http://dali.dashuyun.cn/Article/details/gtddspzhre.html

[R42] 输入重定向
来源：http://dali.chenjidiqi.icu/Article/details/gtzqivvjxs.html

wc -l < a.txt
来源：http://dali.cashguo.top/Article/details/gtvveeanjp.html

[R43] 按名字查找文件
来源：http://dali.fzhhl.top/Article/details/gtltscftgn.html

find . -name "*.log" -type f
来源：http://dali.sxryk.cn/Article/details/gtemuiepaj.html

[R44] 按修改时间查找
来源：http://dali.chenzaomai.com/Article/details/gtmhjoazhh.html

find . -mtime -7 -type f
来源：http://dali.ydzc1.top/Article/details/gtyoxhodoq.html

[R45] 批量删除
来源：http://dali.0kj1m.cn/Article/details/gthalkqrgh.html

find . -name "*.tmp" -delete
来源：http://dali.sufxvd.cn/Article/details/gttlqcplof.html

[R46] 递归替换文件内容
来源：http://dali.sysykeji.top/Article/details/gtvetimfzb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gotoacloud.top/Article/details/gtuhfpqoit.html

[R47] sed 单行替换
来源：http://dali.tian-w.cn/Article/details/gtnjzhknle.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtkwtgpugr.html

[R48] awk 取指定列
来源：http://dali.xuanzx.com/Article/details/gthfxydkli.html

awk '{print $1, $3}' a.txt
来源：http://dali.tanke756.top/Article/details/gtcmlzjdky.html

[R49] awk 带条件
来源：http://dali.chenlongwang.top/Article/details/gtcosmtquz.html


<!-- 参考信息 -->