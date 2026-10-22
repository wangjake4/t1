代发 wailian999

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2ipzhtojw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.dashuyun.cn/Article/details/gt2vhshiyny.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2zpbqeujk.html

[Q01] 创建表
来源：http://dali.xuanzx.com/Article/details/gt2avwtiokb.html

CREATE TABLE users (
来源：http://dali.yvedp.cn/Article/details/gt2gynqztco.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.redwolf501.top/Article/details/gt2vbmnkdgm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xinyue.icu/Article/details/gt2luyhaohj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sxryk.cn/Article/details/gt2nvxptiob.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.smart0.xyz/Article/details/gt2tphrcrni.html

);
来源：http://dali.aibaodan.cn/Article/details/gt2cgukzgwr.html

[Q02] 创建带外键的表
来源：http://dali.zdqjudy.top/Article/details/gt2dyfqzjre.html

CREATE TABLE orders (
来源：http://dali.daria6918.cn/Article/details/gt2hajnkmcn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nywtolhq.html

user_id INT NOT NULL,
来源：http://dali.shuidangran.top/Article/details/gt2xcpkwwbn.html

amount DECIMAL(10, 2),
来源：http://dali.vqdsnc.cn/Article/details/gt2ixhhapao.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gaohongyu789.top/Article/details/gt2pkggfadu.html

);
来源：http://dali.ydzc1.top/Article/details/gt2eoszmvto.html

[Q03] 增加列
来源：http://dali.yuanzhike.top/Article/details/gt2uivvotkp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hammf.cn/Article/details/gt2irgrgowf.html

[Q04] 修改列类型
来源：http://dali.vqdsnc.cn/Article/details/gt2inlfdowv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yongpay.top/Article/details/gt2eyzrpjlg.html

[Q05] 重命名列
来源：http://dali.jyoumei.cn/Article/details/gt2dzibkggm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xziqi.cn/Article/details/gt2vfmzefzu.html

[Q06] 删除列
来源：http://dali.jqgfzy.top/Article/details/gt2hddnjkxq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hongshengwenyu.top/Article/details/gt2majycyls.html

[Q07] 删除表
来源：http://dali.smart0.xyz/Article/details/gt2ddpgogci.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhixingplan.top/Article/details/gt2smefnskk.html

[Q08] 创建普通索引
来源：http://dali.cashguo.top/Article/details/gt2otdlnuam.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangshuangyany.cn/Article/details/gt2pbecosza.html

[Q09] 创建唯一索引
来源：http://dali.tian-w.cn/Article/details/gt2hjrsbrmc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.haohaochexian.top/Article/details/gt2arsgaaqu.html

[Q10] 插入单行
来源：http://dali.yvedp.cn/Article/details/gt2gpkryvxq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.birdmap.top/Article/details/gt2ninzfwyf.html

[Q11] 一次插入多行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sukbuflo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tanke756.top/Article/details/gt2naswaxwp.html

[Q12] 插入后取自增 ID
来源：http://dali.shangyingyoupin.top/Article/details/gt2ntnnzoxm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.daxiang520.top/Article/details/gt2wrprkkov.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhoulong.xyz/Article/details/gt2sqrxszjr.html

[Q13] 忽略重复插入
来源：http://dali.hysaishi.cn/Article/details/gt2fyvpnllv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qxlvuyli.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnqzz.top/Article/details/gt2fenwqrnv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.dianchejie.cn/Article/details/gt2umzngxsn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.fzhhl.top/Article/details/gt2uikmzdwr.html

[Q15] 查询全部
来源：http://dali.tianlin.xyz/Article/details/gt2jgipoege.html

SELECT * FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2qdidlmfj.html

[Q16] 查询指定列
来源：http://dali.hnxiangtu.top/Article/details/gt2xrxamhdb.html

SELECT id, name FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2fsoosdjp.html

[Q17] 条件查询
来源：http://dali.ivvv.top/Article/details/gt2nbixnqsb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigufen.top/Article/details/gt2tciecrbg.html

[Q18] 模糊匹配
来源：http://dali.cucudq.cn/Article/details/gt2zgtrgleh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.meibo888.top/Article/details/gt2hkgtxlky.html

[Q19] 范围查询
来源：http://dali.hnxiangtu.top/Article/details/gt2yxtfpsxn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.haohaochexian.top/Article/details/gt2anscugil.html

[Q20] IN 列表
来源：http://dali.hammf.cn/Article/details/gt2vrbodnqz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tian-w.cn/Article/details/gt2gmibbjmq.html

[Q21] 空值判断
来源：http://dali.c1oappe.top/Article/details/gt2dfseiuro.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sweek.top/Article/details/gt2mazbjrsn.html

[Q22] 排序
来源：http://dali.chenjidiqi.icu/Article/details/gt2wlwzgdye.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.guowangkeji.top/Article/details/gt2ptlxxvtg.html

[Q23] 分页
来源：http://dali.dianchejie.cn/Article/details/gt2cbshrsjn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhiwuduotai.top/Article/details/gt2hmzfajlj.html

[Q24] 去重
来源：http://dali.hnxiangtu.top/Article/details/gt2xnixvazk.html

SELECT DISTINCT city FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2rneudikz.html

[Q25] 只取前 N 条
来源：http://dali.yvedp.cn/Article/details/gt2qikrfhaw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xylfe.cn/Article/details/gt2lqgytqal.html

[Q26] 计数
来源：http://dali.mhx1999.top/Article/details/gt2sfqhcrrh.html

SELECT COUNT(*) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2yovttwpr.html

[Q27] 条件计数
来源：http://dali.nwbrower.top/Article/details/gt2rmroynwb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mxupfpod.html

[Q28] 求和与平均
来源：http://dali.tanke756.top/Article/details/gt2pumfjpql.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gt2jqkzhjyq.html

[Q29] 最大最小值
来源：http://dali.yj20258888.top/Article/details/gt2nntjkhcy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2wmdcjctg.html

[Q30] 分组统计
来源：http://dali.tian-w.cn/Article/details/gt2eurbpvhf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gt2rhibzfjq.html

[Q31] 分组后过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2metxulgt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yanxiufei.cn/Article/details/gt2etoxwhhc.html

[Q32] 分组拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gt2bxdnnrsm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gt2vfhvcrdv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.feifeiyinyue.top/Article/details/gt2wklfhdxf.html

[Q33] 多列分组
来源：http://dali.cqqwz.cn/Article/details/gt2rhgjsnfp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.guannengcc.top/Article/details/gt2jrfrtdlw.html

[Q34] 每组取第一条
来源：http://dali.c1oappe.top/Article/details/gt2makxernr.html

SELECT * FROM (
来源：http://dali.yangfankeji.com/Article/details/gt2vnojamsd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yongpay.top/Article/details/gt2icjuhmel.html

) t WHERE rn = 1;
来源：http://dali.ybcxt.top/Article/details/gt2jzqadszx.html

[Q35] 内连接
来源：http://dali.zhongyouzk.top/Article/details/gt2woulbdkr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258888.top/Article/details/gt2pqyeulcv.html

[Q36] 左连接
来源：http://dali.zycfv.cn/Article/details/gt2qaimygeq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ivvv.top/Article/details/gt2mdwrqzzz.html

[Q37] 右连接
来源：http://dali.meibo888.top/Article/details/gt2ehcgpbpj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uofroqfo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gogol.net.cn/Article/details/gt2opxrioih.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.c1oappe.top/Article/details/gt2denqcxxg.html

[Q39] 自连接（查上下级）
来源：http://dali.chenlongwang.top/Article/details/gt2algudcxw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangshuangyany.cn/Article/details/gt2cumhjrpb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aizwys.cn/Article/details/gt2mpditpae.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhengqikj.top/Article/details/gt2hnaepegy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.feifeiyinyue.top/Article/details/gt2cpphqpmi.html

[Q41] 多表连接
来源：http://dali.316326.xyz/Article/details/gt2aduljkiy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sysykeji.top/Article/details/gt2zwlitaoj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shuidangran.top/Article/details/gt2ddmxwfnm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sweek.top/Article/details/gt2obquzmtj.html

[Q42] 连接条件附加过滤
来源：http://dali.hammf.cn/Article/details/gt2cagdczem.html

SELECT u.name, o.amount FROM users u
来源：http://dali.fengsongda.top/Article/details/gt2aqbsshub.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtjdppt.html

[Q43] 标量子查询
来源：http://dali.cqqwz.cn/Article/details/gt2rsxrwsgv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yongpay.top/Article/details/gt2psjaapes.html

[Q44] IN 子查询
来源：http://dali.mhx1999.top/Article/details/gt2cepfzazq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ppjwa.cn/Article/details/gt2mpefbpzq.html

[Q45] EXISTS 判断存在
来源：http://dali.sweek.top/Article/details/gt2oizjiuyh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.c1oappe.top/Article/details/gt2ytampazz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.birdmap.top/Article/details/gt2fwxtwlov.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wmjodwfs.html

[Q47] 与平均值比较
来源：http://dali.shuidangran.top/Article/details/gt2pwvglszk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nanxinkj.top/Article/details/gt2poerslzo.html

[Q48] CTE 公用表表达式
来源：http://dali.kuanghao11.cn/Article/details/gt2btaofhgr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.iojbl.cn/Article/details/gt2eusmuosx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gotoacloud.top/Article/details/gt2pkovevyh.html

[Q49] 更新单行
来源：http://dali.zhiwuduotai.top/Article/details/gt2gtvhwxas.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinqigfzy.top/Article/details/gt2yuoruxmh.html

[Q50] 批量更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ktyikwww.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cqqwz.cn/Article/details/gt2pcxciwkw.html

[Q51] 用子查询更新
来源：http://dali.pengpengdd.cyou/Article/details/gt2orgujdpf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hysaishi.cn/Article/details/gt2jfnfjxzh.html

[Q52] 删除指定行
来源：http://dali.svipenyu.cn/Article/details/gt2lebijgpz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gt2felcghxo.html

[Q53] 按条件删除
来源：http://dali.jqgufenzy.top/Article/details/gt2yldgufqc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxuanxn.top/Article/details/gt2ywxlyafc.html

[Q54] 清空表
来源：http://dali.yonumen.top/Article/details/gt2cdtllzls.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qfwuiddj.html

[Q55] 排名（并列占位）
来源：http://dali.yuanzhike.top/Article/details/gt2hcwrywyy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.c1oappe.top/Article/details/gt2ifxfzoci.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuetiantiany.cn/Article/details/gt2fwjomueg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gt2escgjvhe.html

[Q57] 行号
来源：http://dali.tanke756.top/Article/details/gt2rsiybfod.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2oxesmfbz.html

[Q58] 累计求和
来源：http://dali.guannengcc.top/Article/details/gt2bkfzexcz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gt2cualmadh.html

[Q59] 分组内累计
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vrfgpvdy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2rjxpwcwq.html

[Q60] 取上一行 / 下一行
来源：http://dali.andypj.xyz/Article/details/gt2mykiuupi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xwqthjob.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2zhadpjyq.html

[Q61] 移动平均
来源：http://dali.tianlin.xyz/Article/details/gt2cwmycrrl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gt2byacfwfs.html

[Q62] 分组占比
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gkqtrzut.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gt2ecuaucfo.html

[Q63] 开启事务
来源：http://dali.shuidangran.top/Article/details/gt2vvaeaunv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.0kj1m.cn/Article/details/gt2xjgfzchj.html

[Q64] 提交事务
来源：http://dali.redwolf501.top/Article/details/gt2uoqiyvgj.html

COMMIT;
来源：http://dali.ydzc1.top/Article/details/gt2yqfppeml.html

[Q65] 回滚事务
来源：http://dali.fengsongda.top/Article/details/gt2thjbdjvk.html

ROLLBACK;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ralpqtfy.html

[Q66] 行锁查询
来源：http://dali.aibaodan.cn/Article/details/gt2pukcgolb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhongyouzk.top/Article/details/gt2jvoqvbnm.html

[Q67] 设置隔离级别
来源：http://dali.jiagoushi.top/Article/details/gt2ujraksxo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgfzy.top/Article/details/gt2pypyfikc.html

[Q68] 保存点
来源：http://dali.redwolf501.top/Article/details/gt2ngmvnmam.html

SAVEPOINT sp1;
来源：http://dali.nanxuanxn.top/Article/details/gt2xmgfhbzc.html

ROLLBACK TO sp1;
来源：http://dali.zhoulong.xyz/Article/details/gt2xpbcywmy.html

[Q69] 查看执行计划
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iizcranu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jyoumei.cn/Article/details/gt2arcgvjyt.html

[Q70] 更新统计信息
来源：http://dali.fzhhl.top/Article/details/gt2ocwanrmd.html

ANALYZE TABLE users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bwwhfmyh.html

[Q71] 查看建表语句
来源：http://dali.zhiwuduotai.top/Article/details/gt2htmkudtv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ppjwa.cn/Article/details/gt2zulxeoyh.html

[Q72] 查看索引
来源：http://dali.yvedp.cn/Article/details/gt2govmtsaw.html

SHOW INDEX FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2nbhijujv.html

[Q73] 查看表状态
来源：http://dali.vqdsnc.cn/Article/details/gt2ycukmdrz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yueranfly.top/Article/details/gt2tofmnurp.html

[Q74] 强制使用索引
来源：http://dali.pengpengdd.cyou/Article/details/gt2xixulytr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xylfe.cn/Article/details/gt2pcmtkzfi.html

[Q75] 日期格式化
来源：http://dali.guowangkeji.top/Article/details/gt2pkufqdnn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2gwkyielo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hywenlv.cn/Article/details/gt2ocfcholw.html

[Q76] 按天统计
来源：http://dali.cheryme.top/Article/details/gt2pkenjblu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj202588.top/Article/details/gt2nufkcifq.html

[Q77] 时间加减
来源：http://dali.yuanzhike.top/Article/details/gt2eoloubsh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jiagoushi.top/Article/details/gt2cfxwgscl.html

[Q78] 当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gt2culwntvq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yonumen.top/Article/details/gt2ggmiqowb.html

[Q79] 字符串拼接
来源：http://dali.wangdashe.top/Article/details/gt2jyyymzvh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yongpay.top/Article/details/gt2lifefnsy.html

[Q80] 字符串截取
来源：http://dali.yangfankeji.com/Article/details/gt2vhrtngic.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2ltjniyoc.html

[Q81] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2fvvgawfg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2sruoyhok.html

[Q82] 字符长度与字节长度
来源：http://dali.zdqjudy.top/Article/details/gt2sahrcuyz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gt2siezzjsy.html

[Q83] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gt2zsonnxzf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2pczbarze.html

[Q84] 去除首尾空格
来源：http://dali.gogol.net.cn/Article/details/gt2rbacrqdh.html

SELECT TRIM(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gt2yxotptjv.html

[Q85] 数值取整
来源：http://dali.yuanzhike.top/Article/details/gt2tiyizxve.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.redwolf501.top/Article/details/gt2dllyvpfo.html

[Q86] 读取 JSON 字段
来源：http://dali.jianghu66.top/Article/details/gt2xdlyglpd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aibaodan.cn/Article/details/gt2hbhadnns.html

[Q87] JSON 字段做条件
来源：http://dali.haohaochexian.top/Article/details/gt2uvhokrkd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shuidangran.top/Article/details/gt2jjsqqhxn.html

[Q88] 行转列（条件聚合）
来源：http://dali.vqdsnc.cn/Article/details/gt2uzyuxlri.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pengpengdd.cyou/Article/details/gt2mgdenrfr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tanke756.top/Article/details/gt2uvgwpcpr.html

[Q89] 判断表是否存在
来源：http://dali.hammf.cn/Article/details/gt2ewoeffhx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhoulong.xyz/Article/details/gt2fdwrfbvf.html

[Q90] 生成序号列
来源：http://dali.sufxvd.cn/Article/details/gt2omlioheb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cdnleiting.top/Article/details/gt2qssxcyqj.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2htdulrsx.html

R. Bash 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rqgmqday.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2mezulvnd.html

[R01] shebang 与严格模式
来源：http://dali.fengsongda.top/Article/details/gt2zxyflgia.html

#!/usr/bin/env bash
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mrxahinu.html

set -euo pipefail
来源：http://dali.nwbrower.top/Article/details/gt2uhrtvudn.html

[R02] 变量赋值与使用
来源：http://dali.yanxiufei.cn/Article/details/gt2fsvriaco.html

name="Tom"; echo "$name"
来源：http://dali.wangshuangyany.cn/Article/details/gt2gwsdxlrf.html

[R03] 只读变量
来源：http://dali.smart0.xyz/Article/details/gt2xfobchde.html

readonly PI=3.14
来源：http://dali.fengsongda.top/Article/details/gt2guixocyu.html

[R04] 位置参数
来源：http://dali.cashguo.top/Article/details/gt2kqvigjai.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jianghu66.top/Article/details/gt2prdyqeib.html

[R05] 参数默认值
来源：http://dali.9152youxi.cn/Article/details/gt2dmtrrrht.html

name="${1:-default}"
来源：http://dali.shzxlz.cn/Article/details/gt2sbsocnbz.html

[R06] 判断命令是否存在
来源：http://dali.chenzaomai.com/Article/details/gt2apolakzu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gt2toypklce.html

[R07] if 判断文件
来源：http://dali.smart0.xyz/Article/details/gt2sordhyon.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ivvv.top/Article/details/gt2vgkqzqgi.html

[R08] 数值比较
来源：http://dali.0kj1m.cn/Article/details/gt2kofdnpbk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tianlin.xyz/Article/details/gt2jxejttty.html

[R09] 字符串比较
来源：http://dali.dashuyun.cn/Article/details/gt2goxcpvmt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258888.top/Article/details/gt2dnywrlpe.html

[R10] 正则匹配
来源：http://dali.yueranfly.top/Article/details/gt2agpzdbpx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gt2vmglkdct.html

[R11] case 多分支
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nmkcbwcd.html

case "$1" in
来源：http://dali.dashuyun.cn/Article/details/gt2runcshbo.html

start) echo "启动" ;;
来源：http://dali.gzhubu.top/Article/details/gt2oycbflai.html

stop)  echo "停止" ;;
来源：http://dali.sufxvd.cn/Article/details/gt2ducirzzq.html

*)     echo "未知命令" ;;
来源：http://dali.0kj1m.cn/Article/details/gt2onqbkekq.html

esac
来源：http://dali.sxryk.cn/Article/details/gt2gnmclkqm.html

[R12] for 遍历文件
来源：http://dali.dianchejie.cn/Article/details/gt2bvlbxict.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhengqikj.top/Article/details/gt2hhxeiuls.html

[R13] for 计数循环
来源：http://dali.nwbrower.top/Article/details/gt2xnfxamcc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gt2aavhrdqk.html

[R14] C 风格 for
来源：http://dali.tianlin.xyz/Article/details/gt2stroanmh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ollmrxlw.html

[R15] while 逐行读文件
来源：http://dali.ydzc1.top/Article/details/gt2sekqyfgb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenzaomai.com/Article/details/gt2ymgzxeau.html

[R16] until 等待条件
来源：http://dali.andypj.xyz/Article/details/gt2lajubdei.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gotoacloud.top/Article/details/gt2mxepzywi.html

[R17] 数组定义与取值
来源：http://dali.nanxinkj.top/Article/details/gt2gnpnlbht.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgufenzy.top/Article/details/gt2caafmbtg.html

[R18] 遍历数组
来源：http://dali.hammf.cn/Article/details/gt2ajxiwwfk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sdtfqoot.html

[R19] 数组长度
来源：http://dali.cashguo.top/Article/details/gt2fflmihfv.html

echo "${#arr[@]}"
来源：http://dali.aibaodan.cn/Article/details/gt2ihjeuwxx.html

[R20] 关联数组（字典）
来源：http://dali.andypj.xyz/Article/details/gt2plymzubb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sweek.top/Article/details/gt2yidwjyiq.html

[R21] 字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kbzuaffo.html

echo "${#s}"
来源：http://dali.guowangkeji.top/Article/details/gt2ckgupnvt.html

[R22] 截取子串
来源：http://dali.yj202588.top/Article/details/gt2tenhxcpf.html

echo "${s:0:5}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cqorpleq.html

[R23] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nizoieea.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dianchejie.cn/Article/details/gt2vpdlzgte.html

[R24] 大小写转换
来源：http://dali.meibo888.top/Article/details/gt2ejpqipix.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhixingplan.top/Article/details/gt2wdsvbijl.html

[R25] 去后缀 / 去前缀
来源：http://dali.guowangkeji.top/Article/details/gt2zvtufcwy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hfpthk.cn/Article/details/gt2huortixw.html

[R26] 命令替换
来源：http://dali.jinqigufen.top/Article/details/gt2mrngzfei.html

now=$(date +%F); echo "$now"
来源：http://dali.gaohongyu789.top/Article/details/gt2fxpeneok.html

[R27] 算术展开
来源：http://dali.hnxiangtu.top/Article/details/gt2zqnprrko.html

echo $((1 + 2 * 3))
来源：http://dali.wangdashe.top/Article/details/gt2ajxpovvp.html

[R28] 浮点运算
来源：http://dali.0kj1m.cn/Article/details/gt2mbfooqfz.html

echo "scale=2; 10/3" | bc
来源：http://dali.ivvv.top/Article/details/gt2actxzfgy.html

[R29] 定义函数
来源：http://dali.daxiang520.top/Article/details/gt2cydasoqb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jiagoushi.top/Article/details/gt2lclyfbqc.html

[R30] 函数返回状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ndcnvxsk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cheryme.top/Article/details/gt2jarfkahi.html

[R31] 局部变量
来源：http://dali.bjfxy.top/Article/details/gt2rtlhzwuh.html

f() { local x=1; echo "$x"; }
来源：http://dali.svipenyu.cn/Article/details/gt2veoebbiy.html

[R32] 参数个数校验
来源：http://dali.hfpthk.cn/Article/details/gt2bkgfltuk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gt2bgasmczl.html

[R33] 捕获错误并提示行号
来源：http://dali.jlsjyb.cn/Article/details/gt2mxhcckpe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gotoacloud.top/Article/details/gt2ymswkesx.html

[R34] 退出时清理
来源：http://dali.nwbrower.top/Article/details/gt2kztelfbt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2couwlfcp.html

[R35] 后台执行并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2scfypatv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj202588.top/Article/details/gt2pwbcdujn.html

[R36] 并发执行多个任务
来源：http://dali.svipenyu.cn/Article/details/gt2zxtavrye.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gotoacloud.top/Article/details/gt2cnyuyttl.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2upckqviq.html

files=$(ls -1)
来源：http://dali.cheryme.top/Article/details/gt2mltxvubq.html

[R38] 管道串联
来源：http://dali.gaohongyu789.top/Article/details/gt2sxyrxwrj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shzxlz.cn/Article/details/gt2tejnzkou.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxzxlas.html

cmd > out.log 2>&1
来源：http://dali.guannengcc.top/Article/details/gt2yuvwqsbk.html

[R40] 追加写日志
来源：http://dali.yueranfly.top/Article/details/gt2mcwxczyc.html

echo "log" >> out.log
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mbenikbb.html

[R41] 丢弃输出
来源：http://dali.haohaochexian.top/Article/details/gt2jdrqmtko.html

cmd >/dev/null 2>&1
来源：http://dali.0kj1m.cn/Article/details/gt2ahqwbcyh.html

[R42] 输入重定向
来源：http://dali.nanxuanxn.top/Article/details/gt2bbowlqit.html

wc -l < a.txt
来源：http://dali.xuanzx.com/Article/details/gt2bgwanaqt.html

[R43] 按名字查找文件
来源：http://dali.yj202588.top/Article/details/gt2zpmzhsfm.html


<!-- 参考信息 -->