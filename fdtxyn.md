代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shuidangran.top/Article/details/gtodfoyqjb.html

user_id INT NOT NULL,
来源：http://dali.zdqjudy.top/Article/details/gtkyzuojvv.html

amount DECIMAL(10, 2),
来源：http://dali.aibaodan.cn/Article/details/gtbmcdxjum.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xylfe.cn/Article/details/gtyilivznw.html

);
来源：http://dali.cqqwz.cn/Article/details/gtudqwyxir.html

[Q03] 增加列
来源：http://dali.yuanzhike.top/Article/details/gtwkwyqlhu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.guannengcc.top/Article/details/gtfdjojirh.html

[Q04] 修改列类型
来源：http://dali.yj20258888.top/Article/details/gtatvcbmia.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.redwolf501.top/Article/details/gtkffgwwga.html

[Q05] 重命名列
来源：http://dali.hnxiangtu.top/Article/details/gtwyjzzels.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenjidiqi.icu/Article/details/gtmremxnfq.html

[Q06] 删除列
来源：http://dali.9152youxi.cn/Article/details/gtfapwouda.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhixingplan.top/Article/details/gtbkwtgvqw.html

[Q07] 删除表
来源：http://dali.zdqjudy.top/Article/details/gthytapzlq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yuanzhike.top/Article/details/gtubdyjepl.html

[Q08] 创建普通索引
来源：http://dali.vqdsnc.cn/Article/details/gttktpcojt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangdashe.top/Article/details/gtgedkrfxk.html

[Q09] 创建唯一索引
来源：http://dali.tianlin.xyz/Article/details/gtscudbzur.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cqqwz.cn/Article/details/gtqeyimobw.html

[Q10] 插入单行
来源：http://dali.yuanzhike.top/Article/details/gtaycvmtvc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.svipenyu.cn/Article/details/gtpotexksh.html

[Q11] 一次插入多行
来源：http://dali.fzhhl.top/Article/details/gtxrxryhoq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.9152youxi.cn/Article/details/gtombuxozg.html

[Q12] 插入后取自增 ID
来源：http://dali.guowangkeji.top/Article/details/gtwstjaezq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.c1oappe.top/Article/details/gttprpqvet.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nwbrower.top/Article/details/gtomvqcbnw.html

[Q13] 忽略重复插入
来源：http://dali.cucudq.cn/Article/details/gtqiwncyby.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gzhubu.top/Article/details/gtoddqyudz.html

[Q14] 存在则更新（upsert）
来源：http://dali.havefunace.top/Article/details/gtgxjbpvik.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shuidangran.top/Article/details/gtlsldwcou.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xinyue.icu/Article/details/gtiaiflawp.html

[Q15] 查询全部
来源：http://dali.sxryk.cn/Article/details/gtfftagbgu.html

SELECT * FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxiddizyd.html

[Q16] 查询指定列
来源：http://dali.ppjwa.cn/Article/details/gtyzuxetde.html

SELECT id, name FROM users;
来源：http://dali.yongpay.top/Article/details/gthqaobuxl.html

[Q17] 条件查询
来源：http://dali.ydzc1.top/Article/details/gtjsyrzdva.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtrrtegciw.html

[Q18] 模糊匹配
来源：http://dali.hfpthk.cn/Article/details/gturwtdhst.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.daria6918.cn/Article/details/gtghyxmkqe.html

[Q19] 范围查询
来源：http://dali.yj20258888.top/Article/details/gtnjtuyjwo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pengpengdd.cyou/Article/details/gtlabnhkft.html

[Q20] IN 列表
来源：http://dali.vqdsnc.cn/Article/details/gtuxbcbrid.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sysykeji.top/Article/details/gtfswpajnm.html

[Q21] 空值判断
来源：http://dali.zycfv.cn/Article/details/gthhnfizan.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gotoacloud.top/Article/details/gtizhzanwn.html

[Q22] 排序
来源：http://dali.nanxinkj.top/Article/details/gtjenhimhu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yonumen.top/Article/details/gtbmdunmjt.html

[Q23] 分页
来源：http://dali.meibo888.top/Article/details/gttthjyrew.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nanxuanxn.top/Article/details/gtakhnbgep.html

[Q24] 去重
来源：http://dali.sxryk.cn/Article/details/gtqsqfcizd.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtkcklnxob.html

[Q25] 只取前 N 条
来源：http://dali.cdnleiting.top/Article/details/gtbaqrduuj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.0kj1m.cn/Article/details/gtwdryuepe.html

[Q26] 计数
来源：http://dali.zhiwuduotai.top/Article/details/gtvlcsotdr.html

SELECT COUNT(*) FROM users;
来源：http://dali.yonumen.top/Article/details/gtpoovobuc.html

[Q27] 条件计数
来源：http://dali.xuetiantiany.cn/Article/details/gtzkajrfoe.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtzrmxkocn.html

[Q28] 求和与平均
来源：http://dali.yuanzhike.top/Article/details/gtyhqmhnyc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtyiilyiyl.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gtuyphnksc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtgpzrervp.html

[Q30] 分组统计
来源：http://dali.yj20258.top/Article/details/gtcjzwzglx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gtnuutcqsk.html

[Q31] 分组后过滤
来源：http://dali.hammf.cn/Article/details/gtxhayehun.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhengqikj.top/Article/details/gtrpdzeoey.html

[Q32] 分组拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtiesgsbiu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gtzeopidse.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.havefunace.top/Article/details/gtknjmephy.html

[Q33] 多列分组
来源：http://dali.yanxiufei.cn/Article/details/gtsxysxmmb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hammf.cn/Article/details/gtelmfxbnn.html

[Q34] 每组取第一条
来源：http://dali.hnxiangtu.top/Article/details/gtpmvwskgx.html

SELECT * FROM (
来源：http://dali.cucudq.cn/Article/details/gtcwqaeoff.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guannengcc.top/Article/details/gtdvoznaxv.html

) t WHERE rn = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtcgpyyynn.html

[Q35] 内连接
来源：http://dali.chenjidiqi.icu/Article/details/gteerzahvr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.birdmap.top/Article/details/gtdtvpfrnq.html

[Q36] 左连接
来源：http://dali.quarkkingdee.top/Article/details/gtdkwrxayi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gtaagarcuj.html

[Q37] 右连接
来源：http://dali.jinghuilouyu.cn/Article/details/gtycltrxpv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jiagoushi.top/Article/details/gtquborbwc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhengqikj.top/Article/details/gtdodqepyk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.316326.xyz/Article/details/gtmdudoguf.html

[Q39] 自连接（查上下级）
来源：http://dali.9152youxi.cn/Article/details/gtbqucpcua.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shzxlz.cn/Article/details/gtipethoyp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hfpthk.cn/Article/details/gtneltttpq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xylfe.cn/Article/details/gtduyfzvrd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenjidiqi.icu/Article/details/gtkbwksmlk.html

[Q41] 多表连接
来源：http://dali.dianchejie.cn/Article/details/gthusvxzuo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xinyue.icu/Article/details/gtqmaoeqnl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhiwuduotai.top/Article/details/gtbaodngzx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jlsjyb.cn/Article/details/gtlxieboeq.html

[Q42] 连接条件附加过滤
来源：http://dali.quarkkingdee.top/Article/details/gtprdwqeml.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cqqwz.cn/Article/details/gthzohywto.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yonumen.top/Article/details/gtwteooqjy.html

[Q43] 标量子查询
来源：http://dali.chenlongwang.top/Article/details/gtbupyilnp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.feifeiyinyue.top/Article/details/gtlitlfszz.html

[Q44] IN 子查询
来源：http://dali.guowangkeji.top/Article/details/gtlgotldlw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hfpthk.cn/Article/details/gtulhreaam.html

[Q45] EXISTS 判断存在
来源：http://dali.guowangkeji.top/Article/details/gtnicuwuhy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gtbwhgxyce.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.meibo888.top/Article/details/gtofxrpakv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nwbrower.top/Article/details/gtvmchzzea.html

[Q47] 与平均值比较
来源：http://dali.shzxlz.cn/Article/details/gtrsxlmomu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgufenzy.top/Article/details/gtbktngrwt.html

[Q48] CTE 公用表表达式
来源：http://dali.sufxvd.cn/Article/details/gtilhnowhk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gaohongyu789.top/Article/details/gtgqwlhybk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtrrndog.html

[Q49] 更新单行
来源：http://dali.chenlongwang.top/Article/details/gtoaklczlq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.daxiang520.top/Article/details/gtbxpzlgcj.html

[Q50] 批量更新
来源：http://dali.zhongyouzk.top/Article/details/gttgyaqvfl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cheryme.top/Article/details/gtsubsjsff.html

[Q51] 用子查询更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzojfbbvs.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hfpthk.cn/Article/details/gtljuoytmk.html

[Q52] 删除指定行
来源：http://dali.daria6918.cn/Article/details/gtgvmgnplg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aizwys.cn/Article/details/gtsqgmijru.html

[Q53] 按条件删除
来源：http://dali.hammf.cn/Article/details/gtaguohcrw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258888.top/Article/details/gtatnmebdx.html

[Q54] 清空表
来源：http://dali.xinyue.icu/Article/details/gtbrgsmiza.html

TRUNCATE TABLE logs;
来源：http://dali.quarkkingdee.top/Article/details/gtxnxslsqz.html

[Q55] 排名（并列占位）
来源：http://dali.aibaodan.cn/Article/details/gtbwurexte.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zycfv.cn/Article/details/gtiueygbre.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sweek.top/Article/details/gttozqijpy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gtsfdcfzkb.html

[Q57] 行号
来源：http://dali.dashuyun.cn/Article/details/gtjrzppdtc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jiagoushi.top/Article/details/gthaidpxgg.html

[Q58] 累计求和
来源：http://dali.yj20258.top/Article/details/gtzxxrhugd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtqwmbkuaq.html

[Q59] 分组内累计
来源：http://dali.chenlongwang.top/Article/details/gtbrcwcumt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sweek.top/Article/details/gtvchrmrns.html

[Q60] 取上一行 / 下一行
来源：http://dali.zycfv.cn/Article/details/gtdlrbjasv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gogol.net.cn/Article/details/gtozjnvjxw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gthfnnwwkc.html

[Q61] 移动平均
来源：http://dali.yj202588.top/Article/details/gtpimkvffg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtexmvqvdq.html

[Q62] 分组占比
来源：http://dali.jinqigfzy.top/Article/details/gtilwuurzc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gtpvluamqr.html

[Q63] 开启事务
来源：http://dali.meibo888.top/Article/details/gtoaeobtxw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sxryk.cn/Article/details/gthpbjovfd.html

[Q64] 提交事务
来源：http://dali.dianchejie.cn/Article/details/gtdxsoxrjd.html

COMMIT;
来源：http://dali.yongpay.top/Article/details/gtzhauykzy.html

[Q65] 回滚事务
来源：http://dali.ivvv.top/Article/details/gtfvviqfyl.html

ROLLBACK;
来源：http://dali.jyoumei.cn/Article/details/gtssenciap.html

[Q66] 行锁查询
来源：http://dali.fengsongda.top/Article/details/gtyisofwwm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinqigufen.top/Article/details/gttzqcefas.html

[Q67] 设置隔离级别
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwevrfbfp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwuujjrz.html

[Q68] 保存点
来源：http://dali.chenjidiqi.icu/Article/details/gtulhhowtg.html

SAVEPOINT sp1;
来源：http://dali.hnqzz.top/Article/details/gtxajqggyj.html

ROLLBACK TO sp1;
来源：http://dali.guannengcc.top/Article/details/gtunslawiw.html

[Q69] 查看执行计划
来源：http://dali.daxiang520.top/Article/details/gtytoxphug.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinghuilouyu.cn/Article/details/gtboqfyvlc.html

[Q70] 更新统计信息
来源：http://dali.birdmap.top/Article/details/gtfmermbim.html

ANALYZE TABLE users;
来源：http://dali.xziqi.cn/Article/details/gtprrqbkak.html

[Q71] 查看建表语句
来源：http://dali.hywenlv.cn/Article/details/gtlnftklcw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258888.top/Article/details/gtzgbvtyna.html

[Q72] 查看索引
来源：http://dali.jyoumei.cn/Article/details/gtbebwlzdh.html

SHOW INDEX FROM users;
来源：http://dali.yj20258888.top/Article/details/gtzvjnikqy.html

[Q73] 查看表状态
来源：http://dali.nwbrower.top/Article/details/gtmtdbjora.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sxryk.cn/Article/details/gtvgroxxfx.html

[Q74] 强制使用索引
来源：http://dali.sufxvd.cn/Article/details/gtlsijtasc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttwxhdmoj.html

[Q75] 日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqsbwmgbr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtamlxxahi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.smart0.xyz/Article/details/gtfnkxhihr.html

[Q76] 按天统计
来源：http://dali.cheryme.top/Article/details/gtzsiktsoa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hywenlv.cn/Article/details/gtnacyncmz.html

[Q77] 时间加减
来源：http://dali.jqgfzy.top/Article/details/gtzbxpjatt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cqqwz.cn/Article/details/gtlejnzznb.html

[Q78] 当前时间
来源：http://dali.sysykeji.top/Article/details/gtrzujicku.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shzxlz.cn/Article/details/gtkbnyzlra.html

[Q79] 字符串拼接
来源：http://dali.zhixingplan.top/Article/details/gtxwgsuibr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ydzc1.top/Article/details/gtbohkiecm.html

[Q80] 字符串截取
来源：http://dali.pycfn.com/Article/details/gtushvaeuf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtkymerxkl.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxvkuqxz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gterdafywy.html

[Q82] 字符长度与字节长度
来源：http://dali.svipenyu.cn/Article/details/gtwbmqmlvp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtsgwovwlh.html

[Q83] 大小写转换
来源：http://dali.gogol.net.cn/Article/details/gtcgnjvlfn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtzpouiuha.html

[Q84] 去除首尾空格
来源：http://dali.yvedp.cn/Article/details/gtyzaacekk.html

SELECT TRIM(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtvcquumil.html

[Q85] 数值取整
来源：http://dali.yonumen.top/Article/details/gtkdibmrqa.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinqigfzy.top/Article/details/gtqgwjhjxx.html

[Q86] 读取 JSON 字段
来源：http://dali.jqgufenzy.top/Article/details/gtksolgmxt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.feifeiyinyue.top/Article/details/gtcvaadsap.html

[Q87] JSON 字段做条件
来源：http://dali.jiagoushi.top/Article/details/gtcbtonddf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gzhubu.top/Article/details/gthrfcfeey.html

[Q88] 行转列（条件聚合）
来源：http://dali.aizwys.cn/Article/details/gtzdcxulfh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pengpengdd.cyou/Article/details/gtcfjanzgq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtpvsygyos.html

[Q89] 判断表是否存在
来源：http://dali.snrcjt.cn/Article/details/gtbbyraghg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hysaishi.cn/Article/details/gtizrcofyi.html

[Q90] 生成序号列
来源：http://dali.chenzaomai.com/Article/details/gtyvjcmzxp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.9152youxi.cn/Article/details/gtkmkgedcw.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtnxbzhutw.html

R. Bash 专题
来源：http://dali.shzxlz.cn/Article/details/gtjqnnoxpi.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtifietbwk.html

[R01] shebang 与严格模式
来源：http://dali.sufxvd.cn/Article/details/gtguoizwbs.html

#!/usr/bin/env bash
来源：http://dali.xylfe.cn/Article/details/gtwuzawqlw.html

set -euo pipefail
来源：http://dali.nwbrower.top/Article/details/gthjqgggqj.html

[R02] 变量赋值与使用
来源：http://dali.jinqigufen.top/Article/details/gtgjnpmzrt.html

name="Tom"; echo "$name"
来源：http://dali.9152youxi.cn/Article/details/gtbfktdaca.html

[R03] 只读变量
来源：http://dali.316326.xyz/Article/details/gtvxpngtuy.html

readonly PI=3.14
来源：http://dali.zhiwuduotai.top/Article/details/gtshrapdvv.html

[R04] 位置参数
来源：http://dali.vqdsnc.cn/Article/details/gtkwjuzxor.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gaohongyu789.top/Article/details/gtjpawltnt.html

[R05] 参数默认值
来源：http://dali.cqqwz.cn/Article/details/gtgabpsfcm.html

name="${1:-default}"
来源：http://dali.jinqigufen.top/Article/details/gtmtxydgeu.html

[R06] 判断命令是否存在
来源：http://dali.316326.xyz/Article/details/gtapukaimk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.guowangkeji.top/Article/details/gtidnkoxen.html

[R07] if 判断文件
来源：http://dali.yangfankeji.com/Article/details/gtaiejhiro.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtbwzugyok.html

[R08] 数值比较
来源：http://dali.zdqjudy.top/Article/details/gtyzzcphjj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.snrcjt.cn/Article/details/gtwcwymzbr.html

[R09] 字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfssmmyns.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwttkivz.html

[R10] 正则匹配
来源：http://dali.hnxiangtu.top/Article/details/gtwohavtyi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxinkj.top/Article/details/gtydgnczuh.html

[R11] case 多分支
来源：http://dali.shangyingyoupin.top/Article/details/gtbbaospgp.html

case "$1" in
来源：http://dali.hywenlv.cn/Article/details/gtbnpbjoyv.html

start) echo "启动" ;;
来源：http://dali.aibaodan.cn/Article/details/gttxrgbhks.html

stop)  echo "停止" ;;
来源：http://dali.pycfn.com/Article/details/gticdewxgk.html

*)     echo "未知命令" ;;
来源：http://dali.svipenyu.cn/Article/details/gtqfkpmmjx.html

esac
来源：http://dali.xylfe.cn/Article/details/gtmjonvfjd.html

[R12] for 遍历文件
来源：http://dali.chenzaomai.com/Article/details/gtafetvqqz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yanxiufei.cn/Article/details/gttkorfjvo.html

[R13] for 计数循环
来源：http://dali.hongshengwenyu.top/Article/details/gtdknvnwwo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gtivleocbu.html

[R14] C 风格 for
来源：http://dali.tian-w.cn/Article/details/gtzmrooqxu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gtwrxoevqt.html

[R15] while 逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtkdjtucde.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.316326.xyz/Article/details/gtneivrjrf.html

[R16] until 等待条件
来源：http://dali.9152youxi.cn/Article/details/gtbwftxuwt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yueranfly.top/Article/details/gtmgfeqvjw.html

[R17] 数组定义与取值
来源：http://dali.tanke756.top/Article/details/gtnhqbkkck.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shuidangran.top/Article/details/gtuvurftth.html

[R18] 遍历数组
来源：http://dali.zdqjudy.top/Article/details/gtfgesnmwj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.0kj1m.cn/Article/details/gtxvszqkvn.html

[R19] 数组长度
来源：http://dali.yueranfly.top/Article/details/gtrcknkmcq.html

echo "${#arr[@]}"
来源：http://dali.yangfankeji.com/Article/details/gttkphkslp.html

[R20] 关联数组（字典）
来源：http://dali.daria6918.cn/Article/details/gteafkhfjr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgfzy.top/Article/details/gteqgwsgjm.html

[R21] 字符串长度
来源：http://dali.ydzc1.top/Article/details/gtcgejypht.html

echo "${#s}"
来源：http://dali.yanxiufei.cn/Article/details/gtuwzczsvw.html

[R22] 截取子串
来源：http://dali.feifeiyinyue.top/Article/details/gtpafkrvvw.html

echo "${s:0:5}"
来源：http://dali.iojbl.cn/Article/details/gtfrxgunlb.html

[R23] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gtutluyqml.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ybcxt.top/Article/details/gtejzhxgcm.html

[R24] 大小写转换
来源：http://dali.shuidangran.top/Article/details/gtqsvryzkh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xuanzx.com/Article/details/gteiadcgmx.html

[R25] 去后缀 / 去前缀
来源：http://dali.xylfe.cn/Article/details/gteullvnvn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gotoacloud.top/Article/details/gtjnyztikf.html

[R26] 命令替换
来源：http://dali.yj20258888.top/Article/details/gtpddipzjx.html

now=$(date +%F); echo "$now"
来源：http://dali.yj20258888.top/Article/details/gtwiwlkxjl.html

[R27] 算术展开
来源：http://dali.cheryme.top/Article/details/gtqfdueftf.html

echo $((1 + 2 * 3))
来源：http://dali.cucudq.cn/Article/details/gtlacvqsje.html

[R28] 浮点运算
来源：http://dali.cdnleiting.top/Article/details/gtbqaadtxt.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gtkkmvoppe.html

[R29] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gtytfbtvjq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtqkllrdse.html

[R30] 函数返回状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhnxyubc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yonumen.top/Article/details/gtzdwavhye.html

[R31] 局部变量
来源：http://dali.sxryk.cn/Article/details/gtjbkmlrof.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenzaomai.com/Article/details/gtqoxqqjtd.html

[R32] 参数个数校验
来源：http://dali.9152youxi.cn/Article/details/gtwwelmpms.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzahibrgf.html

[R33] 捕获错误并提示行号
来源：http://dali.andypj.xyz/Article/details/gtwbvlcdtj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ppjwa.cn/Article/details/gttrebbtbp.html

[R34] 退出时清理
来源：http://dali.jinqigfzy.top/Article/details/gtbxspplly.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gtgvzgeuca.html

[R35] 后台执行并等待
来源：http://dali.yangfankeji.com/Article/details/gttqhxhpdx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyyybwomq.html

[R36] 并发执行多个任务
来源：http://dali.xylfe.cn/Article/details/gttutztixd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ybcxt.top/Article/details/gtglsafoow.html

[R37] 把输出赋给变量
来源：http://dali.chenjidiqi.icu/Article/details/gtindgjngp.html

files=$(ls -1)
来源：http://dali.jyoumei.cn/Article/details/gtezadlwsc.html

[R38] 管道串联
来源：http://dali.vqdsnc.cn/Article/details/gtubnbsedv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hammf.cn/Article/details/gtntqgwupt.html

[R39] 重定向标准输出与错误
来源：http://dali.kuanghao11.cn/Article/details/gtgyxmcapo.html

cmd > out.log 2>&1
来源：http://dali.ivvv.top/Article/details/gtygzsruxy.html

[R40] 追加写日志
来源：http://dali.yuxming.cn/Article/details/gtjqimjbzb.html

echo "log" >> out.log
来源：http://dali.yueranfly.top/Article/details/gtwbbqzivo.html

[R41] 丢弃输出
来源：http://dali.chenjidiqi.icu/Article/details/gtzdyftcoq.html

cmd >/dev/null 2>&1
来源：http://dali.daxiang520.top/Article/details/gtfpexwqhf.html

[R42] 输入重定向
来源：http://dali.cdnleiting.top/Article/details/gtdbbmhwhw.html

wc -l < a.txt
来源：http://dali.cdnleiting.top/Article/details/gtyhjhllmi.html

[R43] 按名字查找文件
来源：http://dali.yj20258888.top/Article/details/gtaeezxqme.html

find . -name "*.log" -type f
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqerwkrbp.html

[R44] 按修改时间查找
来源：http://dali.yangfankeji.com/Article/details/gtneghvtqu.html

find . -mtime -7 -type f
来源：http://dali.jqgufenzy.top/Article/details/gtjiowzbex.html

[R45] 批量删除
来源：http://dali.fengsongda.top/Article/details/gtkydaznxu.html

find . -name "*.tmp" -delete
来源：http://dali.jinyuanbaomall.cn/Article/details/gtenjvighk.html

[R46] 递归替换文件内容
来源：http://dali.shuidangran.top/Article/details/gtubvvbbne.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cucudq.cn/Article/details/gtfmaastaw.html

[R47] sed 单行替换
来源：http://dali.hnxiangtu.top/Article/details/gtthkiaypp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jiagoushi.top/Article/details/gtbgsljntn.html

[R48] awk 取指定列
来源：http://dali.tianlin.xyz/Article/details/gtucosphdq.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtslqptpdf.html

[R49] awk 带条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmcjtlbk.html


<!-- 参考信息 -->