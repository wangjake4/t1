代发 wailian999

CREATE TABLE users (
来源：http://dali.yuxming.cn/Article/details/gt2excowqyt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aizwys.cn/Article/details/gt2saaetpfc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenzaomai.com/Article/details/gt2pglyubwh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jiagoushi.top/Article/details/gt2gfureudn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigfzy.top/Article/details/gt2jizxtrpe.html

);
来源：http://dali.xylfe.cn/Article/details/gt2kysiwbtn.html

[Q02] 创建带外键的表
来源：http://dali.gzhubu.top/Article/details/gt2pzqmawmz.html

CREATE TABLE orders (
来源：http://dali.yuanzhike.top/Article/details/gt2vwkonyca.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hammf.cn/Article/details/gt2hndklbgr.html

user_id INT NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gt2xfymipvf.html

amount DECIMAL(10, 2),
来源：http://dali.chenzaomai.com/Article/details/gt2behhhgni.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ivvv.top/Article/details/gt2zaurnkqd.html

);
来源：http://dali.daria6918.cn/Article/details/gt2sljaicyp.html

[Q03] 增加列
来源：http://dali.sysykeji.top/Article/details/gt2yjzglszc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nwbrower.top/Article/details/gt2tukgljfj.html

[Q04] 修改列类型
来源：http://dali.shuidangran.top/Article/details/gt2rmokyekd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hysaishi.cn/Article/details/gt2woyhxkwy.html

[Q05] 重命名列
来源：http://dali.zdqjudy.top/Article/details/gt2qzncsvss.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenjidiqi.icu/Article/details/gt2zrbdqbdb.html

[Q06] 删除列
来源：http://dali.yonumen.top/Article/details/gt2ivagtawt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ybcxt.top/Article/details/gt2eypzwusx.html

[Q07] 删除表
来源：http://dali.9152youxi.cn/Article/details/gt2qdocmzbz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.9152youxi.cn/Article/details/gt2xbqlldps.html

[Q08] 创建普通索引
来源：http://dali.hfpthk.cn/Article/details/gt2onslvqqx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenzaomai.com/Article/details/gt2fapeguyw.html

[Q09] 创建唯一索引
来源：http://dali.pengpengdd.cyou/Article/details/gt2uthplddg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinqigfzy.top/Article/details/gt2vfzctgor.html

[Q10] 插入单行
来源：http://dali.tian-w.cn/Article/details/gt2ubzixiim.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj20258.top/Article/details/gt2jqyvefvm.html

[Q11] 一次插入多行
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2klvoacdb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dashuyun.cn/Article/details/gt2txatajjd.html

[Q12] 插入后取自增 ID
来源：http://dali.gogol.net.cn/Article/details/gt2nvvepbph.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.meibo888.top/Article/details/gt2vidinqfy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gaohongyu789.top/Article/details/gt2rklxfppj.html

[Q13] 忽略重复插入
来源：http://dali.hywenlv.cn/Article/details/gt2eecdcrde.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guowangkeji.top/Article/details/gt2hzhmwkgw.html

[Q14] 存在则更新（upsert）
来源：http://dali.xziqi.cn/Article/details/gt2etiilgoq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zycfv.cn/Article/details/gt2lgvedulg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yvedp.cn/Article/details/gt2wfqadumh.html

[Q15] 查询全部
来源：http://dali.gogol.net.cn/Article/details/gt2igxqrtyv.html

SELECT * FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2uziqaxyn.html

[Q16] 查询指定列
来源：http://dali.dashuyun.cn/Article/details/gt2cvfvhjcg.html

SELECT id, name FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2crqyeqkt.html

[Q17] 条件查询
来源：http://dali.vqdsnc.cn/Article/details/gt2rprpdraq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sysykeji.top/Article/details/gt2aijabyoz.html

[Q18] 模糊匹配
来源：http://dali.yueranfly.top/Article/details/gt2jqfzkjjb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yvedp.cn/Article/details/gt2tikkhhbs.html

[Q19] 范围查询
来源：http://dali.yonumen.top/Article/details/gt2jfemgvvx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hfpthk.cn/Article/details/gt2zadzzgov.html

[Q20] IN 列表
来源：http://dali.snrcjt.cn/Article/details/gt2jahjxncj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.pycfn.com/Article/details/gt2fahtvvre.html

[Q21] 空值判断
来源：http://dali.cdnleiting.top/Article/details/gt2eypvctvd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmaptypm.html

[Q22] 排序
来源：http://dali.hnqzz.top/Article/details/gt2nnhfvsvh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ybcxt.top/Article/details/gt2undlmfkz.html

[Q23] 分页
来源：http://dali.jiagoushi.top/Article/details/gt2vwuzwmiz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ybcxt.top/Article/details/gt2fiihpfun.html

[Q24] 去重
来源：http://dali.birdmap.top/Article/details/gt2supshghz.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258.top/Article/details/gt2oqwnulix.html

[Q25] 只取前 N 条
来源：http://dali.gaohongyu789.top/Article/details/gt2wqtqwhpl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhengqikj.top/Article/details/gt2nnktydpq.html

[Q26] 计数
来源：http://dali.c1oappe.top/Article/details/gt2fbphatae.html

SELECT COUNT(*) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2pwrbsxik.html

[Q27] 条件计数
来源：http://dali.jiagoushi.top/Article/details/gt2cmcabavo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2lrexdcky.html

[Q28] 求和与平均
来源：http://dali.sufxvd.cn/Article/details/gt2qjeghzoo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2nmexbobs.html

[Q29] 最大最小值
来源：http://dali.zdqjudy.top/Article/details/gt2ubfkiiua.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2frymzylw.html

[Q30] 分组统计
来源：http://dali.0kj1m.cn/Article/details/gt2jhaqwjsz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gt2petlxjpa.html

[Q31] 分组后过滤
来源：http://dali.birdmap.top/Article/details/gt2upeadvsn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ybcxt.top/Article/details/gt2wzeasjbq.html

[Q32] 分组拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2vxzebggl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gt2aeocbtvu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hfpthk.cn/Article/details/gt2nfceueqj.html

[Q33] 多列分组
来源：http://dali.jqgfzy.top/Article/details/gt2zktsuvst.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hammf.cn/Article/details/gt2jfesnhff.html

[Q34] 每组取第一条
来源：http://dali.cqqwz.cn/Article/details/gt2wlyayrqg.html

SELECT * FROM (
来源：http://dali.birdmap.top/Article/details/gt2aqnprwml.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hnqzz.top/Article/details/gt2qgazrmoc.html

) t WHERE rn = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2vkjirrhj.html

[Q35] 内连接
来源：http://dali.pengpengdd.cyou/Article/details/gt2ztoazndj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhengqikj.top/Article/details/gt2ekgyymuh.html

[Q36] 左连接
来源：http://dali.nwbrower.top/Article/details/gt2revgwjro.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gt2dzjapudm.html

[Q37] 右连接
来源：http://dali.svipenyu.cn/Article/details/gt2mprzwfhw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ybcxt.top/Article/details/gt2kewxwagl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gzhubu.top/Article/details/gt2kmfmoetc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.9152youxi.cn/Article/details/gt2bssfovoh.html

[Q39] 自连接（查上下级）
来源：http://dali.yonumen.top/Article/details/gt2iweyyeec.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yueranfly.top/Article/details/gt2cjfqmiyc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.vqdsnc.cn/Article/details/gt2csekesmk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cheryme.top/Article/details/gt2ukcywcrr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yueranfly.top/Article/details/gt2kkcsecga.html

[Q41] 多表连接
来源：http://dali.yueranfly.top/Article/details/gt2smctudoy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhongyouzk.top/Article/details/gt2bseyrarr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hammf.cn/Article/details/gt2txlpvcra.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vleknwrp.html

[Q42] 连接条件附加过滤
来源：http://dali.yanxiufei.cn/Article/details/gt2hajawkbo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tanke756.top/Article/details/gt2pvjsmapv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.havefunace.top/Article/details/gt2smqxymfg.html

[Q43] 标量子查询
来源：http://dali.zhongyouzk.top/Article/details/gt2zqeqhxpi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yonumen.top/Article/details/gt2dvwlewzw.html

[Q44] IN 子查询
来源：http://dali.9152youxi.cn/Article/details/gt2eoaasfzb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.0kj1m.cn/Article/details/gt2opdmjcpy.html

[Q45] EXISTS 判断存在
来源：http://dali.316326.xyz/Article/details/gt2qpfnufdf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhiwuduotai.top/Article/details/gt2jvvzndaq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hysaishi.cn/Article/details/gt2emmxftbc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gt2gwuoctuh.html

[Q47] 与平均值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yudvdkzg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.snrcjt.cn/Article/details/gt2nluydanv.html

[Q48] CTE 公用表表达式
来源：http://dali.zhengqikj.top/Article/details/gt2rodfasdr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.fengsongda.top/Article/details/gt2nllldnrz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigfzy.top/Article/details/gt2zauhavsd.html

[Q49] 更新单行
来源：http://dali.316326.xyz/Article/details/gt2xbeuyaef.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gt2klgrgttn.html

[Q50] 批量更新
来源：http://dali.zycfv.cn/Article/details/gt2iqnduatx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jianghu66.top/Article/details/gt2tmecfgdk.html

[Q51] 用子查询更新
来源：http://dali.shanyushiyangtech.top/Article/details/gt2belyssjt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.smart0.xyz/Article/details/gt2lhjqtirm.html

[Q52] 删除指定行
来源：http://dali.sufxvd.cn/Article/details/gt2egkzsufl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shzxlz.cn/Article/details/gt2djerkutm.html

[Q53] 按条件删除
来源：http://dali.birdmap.top/Article/details/gt2kcvqpaid.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.guowangkeji.top/Article/details/gt2zeywptvh.html

[Q54] 清空表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2injizuzk.html

TRUNCATE TABLE logs;
来源：http://dali.yueranfly.top/Article/details/gt2xwjmlpsr.html

[Q55] 排名（并列占位）
来源：http://dali.quarkkingdee.top/Article/details/gt2nlbbndnv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ydzc1.top/Article/details/gt2dhyltlsd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iogjyzit.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.smart0.xyz/Article/details/gt2twupgcku.html

[Q57] 行号
来源：http://dali.hongshengwenyu.top/Article/details/gt2fgqhdupr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2umcijkez.html

[Q58] 累计求和
来源：http://dali.yuxming.cn/Article/details/gt2qyhjyzpu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wpvtdchl.html

[Q59] 分组内累计
来源：http://dali.snrcjt.cn/Article/details/gt2atqzayrb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gt2mtoojwea.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigfzy.top/Article/details/gt2iodqrfju.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2wuejstxp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2uoehpnqz.html

[Q61] 移动平均
来源：http://dali.shangyingyoupin.top/Article/details/gt2jwsfizlk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2mzapgoru.html

[Q62] 分组占比
来源：http://dali.gaohongyu789.top/Article/details/gt2wssdvnfr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gt2rkssbrsr.html

[Q63] 开启事务
来源：http://dali.fzhhl.top/Article/details/gt2dfmhryai.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shzxlz.cn/Article/details/gt2jyihzqsf.html

[Q64] 提交事务
来源：http://dali.9152youxi.cn/Article/details/gt2pyxgcgxu.html

COMMIT;
来源：http://dali.guowangkeji.top/Article/details/gt2qfmnqlhd.html

[Q65] 回滚事务
来源：http://dali.cucudq.cn/Article/details/gt2ldhjzrjw.html

ROLLBACK;
来源：http://dali.ydzc1.top/Article/details/gt2tprodwkx.html

[Q66] 行锁查询
来源：http://dali.iojbl.cn/Article/details/gt2xbaaqzfy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bcoektdm.html

[Q67] 设置隔离级别
来源：http://dali.snrcjt.cn/Article/details/gt2tcletoqp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxinkj.top/Article/details/gt2tpblyubv.html

[Q68] 保存点
来源：http://dali.ivvv.top/Article/details/gt2nxniwjmi.html

SAVEPOINT sp1;
来源：http://dali.redwolf501.top/Article/details/gt2hjjrxrbd.html

ROLLBACK TO sp1;
来源：http://dali.zhongyouzk.top/Article/details/gt2jgxacynj.html

[Q69] 查看执行计划
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2msuzcbul.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.0kj1m.cn/Article/details/gt2xhlzopso.html

[Q70] 更新统计信息
来源：http://dali.snrcjt.cn/Article/details/gt2vbnyjpqy.html

ANALYZE TABLE users;
来源：http://dali.yj20258888.top/Article/details/gt2jbpsmtau.html

[Q71] 查看建表语句
来源：http://dali.shzxlz.cn/Article/details/gt2ntzevjeb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.smart0.xyz/Article/details/gt2itmhnubt.html

[Q72] 查看索引
来源：http://dali.smart0.xyz/Article/details/gt2cumzvxjz.html

SHOW INDEX FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2vxzwnmex.html

[Q73] 查看表状态
来源：http://dali.jinqigufen.top/Article/details/gt2iflvdelu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hywenlv.cn/Article/details/gt2pcepehmi.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gt2padkueyn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hfpthk.cn/Article/details/gt2izhlogad.html

[Q75] 日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gt2wxilvsut.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2fjotstny.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hywenlv.cn/Article/details/gt2pmfzxlxx.html

[Q76] 按天统计
来源：http://dali.yanxiufei.cn/Article/details/gt2pjjbibjr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnxiangtu.top/Article/details/gt2dhkfvtrv.html

[Q77] 时间加减
来源：http://dali.chenzaomai.com/Article/details/gt2jvapeouq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigfzy.top/Article/details/gt2akssshrk.html

[Q78] 当前时间
来源：http://dali.hnqzz.top/Article/details/gt2wssicyah.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2nqetwbnk.html

[Q79] 字符串拼接
来源：http://dali.hnxiangtu.top/Article/details/gt2bfrirsvx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj20258.top/Article/details/gt2ejcrqdnn.html

[Q80] 字符串截取
来源：http://dali.fzhhl.top/Article/details/gt2oygjllgf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2hmrivjjw.html

[Q81] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gt2nazysmij.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2wvwbdzdu.html

[Q82] 字符长度与字节长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2qhqjrcrc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2lgokmoxg.html

[Q83] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gt2lilqkaxl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2zzdxbdxl.html

[Q84] 去除首尾空格
来源：http://dali.dianchejie.cn/Article/details/gt2dsnefero.html

SELECT TRIM(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2fmasrwju.html

[Q85] 数值取整
来源：http://dali.sysykeji.top/Article/details/gt2aboovaog.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hammf.cn/Article/details/gt2pslhurup.html

[Q86] 读取 JSON 字段
来源：http://dali.kuanghao11.cn/Article/details/gt2wmodctmt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yangfankeji.com/Article/details/gt2akjvywfn.html

[Q87] JSON 字段做条件
来源：http://dali.jyoumei.cn/Article/details/gt2jvklcolt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.fengsongda.top/Article/details/gt2qqvnfbql.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhiwuduotai.top/Article/details/gt2iddtnlkj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gzhubu.top/Article/details/gt2ptjqtyth.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2wygfpmvn.html

[Q89] 判断表是否存在
来源：http://dali.yonumen.top/Article/details/gt2amjhtprw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuanzx.com/Article/details/gt2bchmrplr.html

[Q90] 生成序号列
来源：http://dali.yj20258.top/Article/details/gt2vkvapxct.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhixingplan.top/Article/details/gt2ngvbtkao.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2cowjiboy.html

R. Bash 专题
来源：http://dali.gogol.net.cn/Article/details/gt2tlqechgr.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lagnhmem.html

[R01] shebang 与严格模式
来源：http://dali.bjfxy.top/Article/details/gt2spolcldd.html

#!/usr/bin/env bash
来源：http://dali.hnqzz.top/Article/details/gt2dxjlzeph.html

set -euo pipefail
来源：http://dali.feifeiyinyue.top/Article/details/gt2wodlvpad.html

[R02] 变量赋值与使用
来源：http://dali.fzhhl.top/Article/details/gt2xyrcrmzb.html

name="Tom"; echo "$name"
来源：http://dali.hammf.cn/Article/details/gt2hmrcsxnx.html

[R03] 只读变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2eqosbvua.html

readonly PI=3.14
来源：http://dali.shzxlz.cn/Article/details/gt2oaijjrzw.html

[R04] 位置参数
来源：http://dali.yongpay.top/Article/details/gt2wigorpyp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigfzy.top/Article/details/gt2fhhffqvu.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2adzjnmxl.html

name="${1:-default}"
来源：http://dali.dashuyun.cn/Article/details/gt2ihorsdgk.html

[R06] 判断命令是否存在
来源：http://dali.ydzc1.top/Article/details/gt2uqyaxhjk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hywenlv.cn/Article/details/gt2cvkhcsdw.html

[R07] if 判断文件
来源：http://dali.tanke756.top/Article/details/gt2wmefwwkh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cucudq.cn/Article/details/gt2zwlgtxnk.html

[R08] 数值比较
来源：http://dali.ppjwa.cn/Article/details/gt2fbntdxqb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gt2obmidfff.html

[R09] 字符串比较
来源：http://dali.cheryme.top/Article/details/gt2dreszlno.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xylfe.cn/Article/details/gt2myzipxbs.html

[R10] 正则匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2elyunmkf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jlsjyb.cn/Article/details/gt2ssexpmqu.html

[R11] case 多分支
来源：http://dali.wangshuangyany.cn/Article/details/gt2mxmwvwvw.html

case "$1" in
来源：http://dali.nanxuanxn.top/Article/details/gt2xoiscglv.html

start) echo "启动" ;;
来源：http://dali.sysykeji.top/Article/details/gt2jbzokgdh.html

stop)  echo "停止" ;;
来源：http://dali.hnxiangtu.top/Article/details/gt2ooqufgzi.html

*)     echo "未知命令" ;;
来源：http://dali.xylfe.cn/Article/details/gt2rfmrutps.html

esac
来源：http://dali.svipenyu.cn/Article/details/gt2dkodqkgo.html

[R12] for 遍历文件
来源：http://dali.tian-w.cn/Article/details/gt2ehhuimmp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2ryjrtbsf.html

[R13] for 计数循环
来源：http://dali.daxiang520.top/Article/details/gt2tdofrhap.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.redwolf501.top/Article/details/gt2bvjjifiz.html

[R14] C 风格 for
来源：http://dali.hongshengwenyu.top/Article/details/gt2uzqgxvsy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hysaishi.cn/Article/details/gt2vzsasirv.html

[R15] while 逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gt2pftxlprp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zasucrqs.html

[R16] until 等待条件
来源：http://dali.ydzc1.top/Article/details/gt2fsjbzpsv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2aclmgsjd.html

[R17] 数组定义与取值
来源：http://dali.guowangkeji.top/Article/details/gt2fpqosqid.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigfzy.top/Article/details/gt2mjgtowxp.html

[R18] 遍历数组
来源：http://dali.zycfv.cn/Article/details/gt2erlbuvtw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sysykeji.top/Article/details/gt2fnrhdrkq.html

[R19] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gt2riqrqtqq.html

echo "${#arr[@]}"
来源：http://dali.yj202588.top/Article/details/gt2wgilqtlg.html

[R20] 关联数组（字典）
来源：http://dali.cashguo.top/Article/details/gt2bpoysyia.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.guowangkeji.top/Article/details/gt2rcexdynr.html

[R21] 字符串长度
来源：http://dali.c1oappe.top/Article/details/gt2hcxblisx.html

echo "${#s}"
来源：http://dali.yonumen.top/Article/details/gt2utkcveqn.html

[R22] 截取子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2brfpmdkc.html

echo "${s:0:5}"
来源：http://dali.tianlin.xyz/Article/details/gt2rzrrhjwz.html

[R23] 字符串替换
来源：http://dali.yj20258888.top/Article/details/gt2zrrsehwb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2xuokltdc.html

[R24] 大小写转换
来源：http://dali.smart0.xyz/Article/details/gt2jnuswygd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.316326.xyz/Article/details/gt2copaowga.html

[R25] 去后缀 / 去前缀
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fxjderpy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhoulong.xyz/Article/details/gt2xooiiwlh.html

[R26] 命令替换
来源：http://dali.nwbrower.top/Article/details/gt2xgupuuve.html

now=$(date +%F); echo "$now"
来源：http://dali.xuanzx.com/Article/details/gt2ccnxphkc.html

[R27] 算术展开
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ktmvedbm.html

echo $((1 + 2 * 3))
来源：http://dali.bjfxy.top/Article/details/gt2czsexied.html

[R28] 浮点运算
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wejaaweo.html

echo "scale=2; 10/3" | bc
来源：http://dali.jqgufenzy.top/Article/details/gt2zxvpmhtk.html

[R29] 定义函数
来源：http://dali.iojbl.cn/Article/details/gt2ekjrpkap.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigfzy.top/Article/details/gt2xdtoccyb.html

[R30] 函数返回状态码
来源：http://dali.ivvv.top/Article/details/gt2qdyqcjmm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhoulong.xyz/Article/details/gt2qrbqfxou.html

[R31] 局部变量
来源：http://dali.yongpay.top/Article/details/gt2iabfiymp.html

f() { local x=1; echo "$x"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2beuzwgjv.html

[R32] 参数个数校验
来源：http://dali.chenjidiqi.icu/Article/details/gt2wrxwvnfc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gt2jbzpbfpv.html

[R33] 捕获错误并提示行号
来源：http://dali.cheryme.top/Article/details/gt2yvvdaloc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jlsjyb.cn/Article/details/gt2lkbydqew.html

[R34] 退出时清理
来源：http://dali.iojbl.cn/Article/details/gt2ionqujfr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gt2kyvpfdbm.html

[R35] 后台执行并等待
来源：http://dali.svipenyu.cn/Article/details/gt2xjdudrrk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj202588.top/Article/details/gt2vpdhbdsq.html

[R36] 并发执行多个任务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mejpqmdm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.redwolf501.top/Article/details/gt2eyoxhdfa.html

[R37] 把输出赋给变量
来源：http://dali.316326.xyz/Article/details/gt2kywrdbjx.html

files=$(ls -1)
来源：http://dali.gotoacloud.top/Article/details/gt2asjuxhuw.html

[R38] 管道串联
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dhywszfx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zycfv.cn/Article/details/gt2njskpwog.html

[R39] 重定向标准输出与错误
来源：http://dali.tanke756.top/Article/details/gt2ewfqselt.html

cmd > out.log 2>&1
来源：http://dali.shuidangran.top/Article/details/gt2uboibqnm.html

[R40] 追加写日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dnphtlyi.html

echo "log" >> out.log
来源：http://dali.zhengqikj.top/Article/details/gt2iquzatbb.html

[R41] 丢弃输出
来源：http://dali.yvedp.cn/Article/details/gt2mfsjmtbr.html

cmd >/dev/null 2>&1
来源：http://dali.yuxming.cn/Article/details/gt2aoqxbuax.html

[R42] 输入重定向
来源：http://dali.jianghu66.top/Article/details/gt2ihemdwza.html

wc -l < a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2ctzufwmb.html

[R43] 按名字查找文件
来源：http://dali.yuxming.cn/Article/details/gt2wshdzfzb.html

find . -name "*.log" -type f
来源：http://dali.ehwqpu.com/Article/details/gt2tsgtgesz.html

[R44] 按修改时间查找
来源：http://dali.tianlin.xyz/Article/details/gt2ndftaqzf.html

find . -mtime -7 -type f
来源：http://dali.yj20258.top/Article/details/gt2vtcsamoy.html

[R45] 批量删除
来源：http://dali.chenjidiqi.icu/Article/details/gt2ypoosttp.html


<!-- 参考信息 -->