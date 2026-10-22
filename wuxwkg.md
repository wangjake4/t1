代发 wailian999

CREATE TABLE users (
来源：http://dali.yuxming.cn/Article/details/gt2bxlteveg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cqqwz.cn/Article/details/gt2zrylelqc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tian-w.cn/Article/details/gt2nhqgpjml.html

email VARCHAR(100) UNIQUE,
来源：http://dali.fengsongda.top/Article/details/gt2fznvsxkb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rezfgwrc.html

);
来源：http://dali.cheryme.top/Article/details/gt2uchvpiif.html

[Q02] 创建带外键的表
来源：http://dali.xinyue.icu/Article/details/gt2wmruzphs.html

CREATE TABLE orders (
来源：http://dali.ppjwa.cn/Article/details/gt2nddlxdil.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.havefunace.top/Article/details/gt2ptbdmchg.html

user_id INT NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gt2hmxokuzg.html

amount DECIMAL(10, 2),
来源：http://dali.bjfxy.top/Article/details/gt2rrtjygrw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yangfankeji.com/Article/details/gt2khumhpow.html

);
来源：http://dali.jiagoushi.top/Article/details/gt2piyeirgv.html

[Q03] 增加列
来源：http://dali.nanxuanxn.top/Article/details/gt2uxsdgwcj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.birdmap.top/Article/details/gt2bdywfsbh.html

[Q04] 修改列类型
来源：http://dali.kuanghao11.cn/Article/details/gt2grxjokcy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ydzc1.top/Article/details/gt2gjkktqhh.html

[Q05] 重命名列
来源：http://dali.snrcjt.cn/Article/details/gt2clrftklt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cucudq.cn/Article/details/gt2fclvpiwx.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvwoymg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.aibaodan.cn/Article/details/gt2lnrrictc.html

[Q07] 删除表
来源：http://dali.xylfe.cn/Article/details/gt2prjcddxs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2okxeyfnn.html

[Q08] 创建普通索引
来源：http://dali.yangfankeji.com/Article/details/gt2uvwneydk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gt2rwmzrbyo.html

[Q09] 创建唯一索引
来源：http://dali.zhoulong.xyz/Article/details/gt2mxxbswmb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gt2npnxvjhf.html

[Q10] 插入单行
来源：http://dali.yongpay.top/Article/details/gt2lsmzbejp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenzaomai.com/Article/details/gt2jrzgwnxf.html

[Q11] 一次插入多行
来源：http://dali.ydzc1.top/Article/details/gt2czchcrmb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xziqi.cn/Article/details/gt2ykosyplw.html

[Q12] 插入后取自增 ID
来源：http://dali.sysykeji.top/Article/details/gt2mwgrxhch.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yuanzhike.top/Article/details/gt2gengqslt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.feifeiyinyue.top/Article/details/gt2qfxbgwlk.html

[Q13] 忽略重复插入
来源：http://dali.xinyue.icu/Article/details/gt2mgchosue.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.meibo888.top/Article/details/gt2sffzxvdz.html

[Q14] 存在则更新（upsert）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gtmnydnh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guannengcc.top/Article/details/gt2nnpgjyaw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sweek.top/Article/details/gt2xjqntbqi.html

[Q15] 查询全部
来源：http://dali.xuetiantiany.cn/Article/details/gt2begojquq.html

SELECT * FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2ktqkqekc.html

[Q16] 查询指定列
来源：http://dali.hywenlv.cn/Article/details/gt2jtbatkxi.html

SELECT id, name FROM users;
来源：http://dali.yj20258.top/Article/details/gt2nzwijyux.html

[Q17] 条件查询
来源：http://dali.hnxiangtu.top/Article/details/gt2jxoyrbxd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sweek.top/Article/details/gt2rlrclopk.html

[Q18] 模糊匹配
来源：http://dali.gogol.net.cn/Article/details/gt2apxjsevs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jqgufenzy.top/Article/details/gt2aafjvzlz.html

[Q19] 范围查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2uixfbknq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jlsjyb.cn/Article/details/gt2sfqextgq.html

[Q20] IN 列表
来源：http://dali.pengpengdd.cyou/Article/details/gt2vchixovx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jianghu66.top/Article/details/gt2yaonkwdc.html

[Q21] 空值判断
来源：http://dali.cdnleiting.top/Article/details/gt2ojyzwelf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gzhubu.top/Article/details/gt2wvqegdiu.html

[Q22] 排序
来源：http://dali.daxiang520.top/Article/details/gt2jrknkcwg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xinyue.icu/Article/details/gt2dcxqolmu.html

[Q23] 分页
来源：http://dali.mhx1999.top/Article/details/gt2pzvbuehh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nfnivvqz.html

[Q24] 去重
来源：http://dali.yueranfly.top/Article/details/gt2dyivnlqt.html

SELECT DISTINCT city FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2jalokdnq.html

[Q25] 只取前 N 条
来源：http://dali.jinqigfzy.top/Article/details/gt2nookdghj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cashguo.top/Article/details/gt2wsronwqa.html

[Q26] 计数
来源：http://dali.cqqwz.cn/Article/details/gt2qmktxybq.html

SELECT COUNT(*) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2pqmoinii.html

[Q27] 条件计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lamzxnzn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2pqksyqgm.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uehmxtij.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sweek.top/Article/details/gt2ioadyeud.html

[Q29] 最大最小值
来源：http://dali.cdnleiting.top/Article/details/gt2ubjjzuqn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2olkhaqhj.html

[Q30] 分组统计
来源：http://dali.havefunace.top/Article/details/gt2ohxnmetm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gt2qsejqadh.html

[Q31] 分组后过滤
来源：http://dali.zhengqikj.top/Article/details/gt2vwjfyudv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ehwqpu.com/Article/details/gt2mgdqyqoq.html

[Q32] 分组拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gt2xlojaspt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gt2sifwesnm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.9152youxi.cn/Article/details/gt2zrxrcbal.html

[Q33] 多列分组
来源：http://dali.aizwys.cn/Article/details/gt2hwqdsckl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gogol.net.cn/Article/details/gt2tgnoynef.html

[Q34] 每组取第一条
来源：http://dali.sufxvd.cn/Article/details/gt2qoevfsxi.html

SELECT * FROM (
来源：http://dali.dashuyun.cn/Article/details/gt2gswwsbyo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhoulong.xyz/Article/details/gt2miwoyzei.html

) t WHERE rn = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2xlhmlhlt.html

[Q35] 内连接
来源：http://dali.316326.xyz/Article/details/gt2vbnoodey.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gt2ibwxvehu.html

[Q36] 左连接
来源：http://dali.chenjidiqi.icu/Article/details/gt2uiffszzz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.andypj.xyz/Article/details/gt2krstjtbf.html

[Q37] 右连接
来源：http://dali.fzhhl.top/Article/details/gt2qecroceo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jlsjyb.cn/Article/details/gt2onlqtwyt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinqigfzy.top/Article/details/gt2fdzqhhlm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ivvv.top/Article/details/gt2oicnrkhc.html

[Q39] 自连接（查上下级）
来源：http://dali.yuxming.cn/Article/details/gt2yhxswsxh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.redwolf501.top/Article/details/gt2zcrfovpz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnxiangtu.top/Article/details/gt2itxoeodn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangshuangyany.cn/Article/details/gt2tdlsqzcn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zycfv.cn/Article/details/gt2hohowvtl.html

[Q41] 多表连接
来源：http://dali.zhoulong.xyz/Article/details/gt2iflgkmwe.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.dianchejie.cn/Article/details/gt2eswtcxhd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ppjwa.cn/Article/details/gt2jmbgxtku.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.0kj1m.cn/Article/details/gt2rtgpwhwp.html

[Q42] 连接条件附加过滤
来源：http://dali.havefunace.top/Article/details/gt2zwkglfev.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ydzc1.top/Article/details/gt2ndjqcsbh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.snrcjt.cn/Article/details/gt2obtjhntc.html

[Q43] 标量子查询
来源：http://dali.ivvv.top/Article/details/gt2atmpyhuc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cdnleiting.top/Article/details/gt2czcyedxw.html

[Q44] IN 子查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cevcldto.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xziqi.cn/Article/details/gt2bwajxaxi.html

[Q45] EXISTS 判断存在
来源：http://dali.andypj.xyz/Article/details/gt2cplwwaee.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guannengcc.top/Article/details/gt2muwddhbx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yonumen.top/Article/details/gt2otxeqlgo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zycfv.cn/Article/details/gt2yqukfluo.html

[Q47] 与平均值比较
来源：http://dali.xylfe.cn/Article/details/gt2gylxesjb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xuetiantiany.cn/Article/details/gt2zujwrcjy.html

[Q48] CTE 公用表表达式
来源：http://dali.sufxvd.cn/Article/details/gt2yozcdpgc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zdqjudy.top/Article/details/gt2pvfjsdch.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yanxiufei.cn/Article/details/gt2onbwpfoq.html

[Q49] 更新单行
来源：http://dali.kuanghao11.cn/Article/details/gt2rhetyvxy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.svipenyu.cn/Article/details/gt2rqzoxclo.html

[Q50] 批量更新
来源：http://dali.haohaochexian.top/Article/details/gt2wmakzagw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jqgfzy.top/Article/details/gt2mgfbbeve.html

[Q51] 用子查询更新
来源：http://dali.dashuyun.cn/Article/details/gt2mccgrgrs.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2iniiedoh.html

[Q52] 删除指定行
来源：http://dali.yj20258.top/Article/details/gt2lmkvxnve.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gt2tvssfsvc.html

[Q53] 按条件删除
来源：http://dali.zycfv.cn/Article/details/gt2dwncqnor.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.birdmap.top/Article/details/gt2kzdybnln.html

[Q54] 清空表
来源：http://dali.yuanzhike.top/Article/details/gt2dovtkcnd.html

TRUNCATE TABLE logs;
来源：http://dali.316326.xyz/Article/details/gt2tahsanqa.html

[Q55] 排名（并列占位）
来源：http://dali.cdnleiting.top/Article/details/gt2znjojwcl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhengqikj.top/Article/details/gt2lbcxtcmc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj20258888.top/Article/details/gt2nzwyifxr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxuanxn.top/Article/details/gt2buphguav.html

[Q57] 行号
来源：http://dali.gotoacloud.top/Article/details/gt2bypsojtx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2qxykkkkc.html

[Q58] 累计求和
来源：http://dali.shzxlz.cn/Article/details/gt2nerrxsjw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2kjhatvme.html

[Q59] 分组内累计
来源：http://dali.cdnleiting.top/Article/details/gt2cqiemxwo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gt2kaqxnriw.html

[Q60] 取上一行 / 下一行
来源：http://dali.dashuyun.cn/Article/details/gt2wixyiamb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinqigfzy.top/Article/details/gt2wcgjqbby.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.havefunace.top/Article/details/gt2nlscivkp.html

[Q61] 移动平均
来源：http://dali.yuanzhike.top/Article/details/gt2qndtjhcn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2vfpkcziv.html

[Q62] 分组占比
来源：http://dali.0kj1m.cn/Article/details/gt2nvzyzour.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gt2zrchfqzn.html

[Q63] 开启事务
来源：http://dali.cucudq.cn/Article/details/gt2dwiapauq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ntbvejpu.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwukcyw.html

COMMIT;
来源：http://dali.xuetiantiany.cn/Article/details/gt2xaporqud.html

[Q65] 回滚事务
来源：http://dali.wangdashe.top/Article/details/gt2cvypbssz.html

ROLLBACK;
来源：http://dali.andypj.xyz/Article/details/gt2jzkufjsc.html

[Q66] 行锁查询
来源：http://dali.zhengqikj.top/Article/details/gt2suucbfgo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shuidangran.top/Article/details/gt2gmtljeiu.html

[Q67] 设置隔离级别
来源：http://dali.zhiwuduotai.top/Article/details/gt2iytjxvcl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jyoumei.cn/Article/details/gt2iszuxtgw.html

[Q68] 保存点
来源：http://dali.cdnleiting.top/Article/details/gt2tkcyahbw.html

SAVEPOINT sp1;
来源：http://dali.yonumen.top/Article/details/gt2noonollv.html

ROLLBACK TO sp1;
来源：http://dali.jqgufenzy.top/Article/details/gt2jsgtxgoo.html

[Q69] 查看执行计划
来源：http://dali.kuanghao11.cn/Article/details/gt2yjacsmok.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nwbrower.top/Article/details/gt2prjtpbbo.html

[Q70] 更新统计信息
来源：http://dali.hnxiangtu.top/Article/details/gt2vckpjpgc.html

ANALYZE TABLE users;
来源：http://dali.yj202588.top/Article/details/gt2ortdacjv.html

[Q71] 查看建表语句
来源：http://dali.ivvv.top/Article/details/gt2mygroygs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.vqdsnc.cn/Article/details/gt2najseuqr.html

[Q72] 查看索引
来源：http://dali.gogol.net.cn/Article/details/gt2pkhxkjni.html

SHOW INDEX FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2pjxugsmd.html

[Q73] 查看表状态
来源：http://dali.guowangkeji.top/Article/details/gt2mmhsgshc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yongpay.top/Article/details/gt2aohhvuxv.html

[Q74] 强制使用索引
来源：http://dali.yvedp.cn/Article/details/gt2uyknlfmc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hammf.cn/Article/details/gt2akkgwsag.html

[Q75] 日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gylxpjcm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gt2ehybkefh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yongpay.top/Article/details/gt2usartzaz.html

[Q76] 按天统计
来源：http://dali.fengsongda.top/Article/details/gt2jinvzklo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ydzc1.top/Article/details/gt2fblnrtby.html

[Q77] 时间加减
来源：http://dali.zycfv.cn/Article/details/gt2bwebwifj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.meibo888.top/Article/details/gt2elkpujfv.html

[Q78] 当前时间
来源：http://dali.birdmap.top/Article/details/gt2cqsthspw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuanzhike.top/Article/details/gt2emkldgoa.html

[Q79] 字符串拼接
来源：http://dali.hysaishi.cn/Article/details/gt2tuquimfz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dnawedgh.html

[Q80] 字符串截取
来源：http://dali.zhixingplan.top/Article/details/gt2wtfusddl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2xyskpfvh.html

[Q81] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gt2ovfwzsor.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2yaqgejgx.html

[Q82] 字符长度与字节长度
来源：http://dali.yuxming.cn/Article/details/gt2evsflric.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2simmmjrz.html

[Q83] 大小写转换
来源：http://dali.yj202588.top/Article/details/gt2msruxhcv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2ihqhcqtt.html

[Q84] 去除首尾空格
来源：http://dali.zhongyouzk.top/Article/details/gt2zqnoemgv.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2txpgilwu.html

[Q85] 数值取整
来源：http://dali.gaohongyu789.top/Article/details/gt2moctgsel.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.mhx1999.top/Article/details/gt2odydmlav.html

[Q86] 读取 JSON 字段
来源：http://dali.0kj1m.cn/Article/details/gt2britqtvk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.daria6918.cn/Article/details/gt2jfbqwsex.html

[Q87] JSON 字段做条件
来源：http://dali.havefunace.top/Article/details/gt2wnogpxit.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ergciijw.html

[Q88] 行转列（条件聚合）
来源：http://dali.xziqi.cn/Article/details/gt2kjdidvup.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.svipenyu.cn/Article/details/gt2oxlrwymt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2cydzzltm.html

[Q89] 判断表是否存在
来源：http://dali.hysaishi.cn/Article/details/gt2kunnxjdj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.fzhhl.top/Article/details/gt2hwhwwmcb.html

[Q90] 生成序号列
来源：http://dali.shzxlz.cn/Article/details/gt2zlwebfqn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwnqksk.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2pybqugqa.html

R. Bash 专题
来源：http://dali.zhiwuduotai.top/Article/details/gt2fwtgdgoe.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2sklhuddt.html

[R01] shebang 与严格模式
来源：http://dali.chenzaomai.com/Article/details/gt2vbtmqdxe.html

#!/usr/bin/env bash
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gphpznic.html

set -euo pipefail
来源：http://dali.gogol.net.cn/Article/details/gt2zdxxxkjo.html

[R02] 变量赋值与使用
来源：http://dali.hywenlv.cn/Article/details/gt2rzykiepl.html

name="Tom"; echo "$name"
来源：http://dali.chenlongwang.top/Article/details/gt2cqlsbnrx.html

[R03] 只读变量
来源：http://dali.hnqzz.top/Article/details/gt2wzzqtunn.html

readonly PI=3.14
来源：http://dali.hammf.cn/Article/details/gt2qtqzjxih.html

[R04] 位置参数
来源：http://dali.cheryme.top/Article/details/gt2iuwmhduu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.quarkkingdee.top/Article/details/gt2bllwjlhp.html

[R05] 参数默认值
来源：http://dali.tian-w.cn/Article/details/gt2fhwzeguk.html

name="${1:-default}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2lgflquij.html

[R06] 判断命令是否存在
来源：http://dali.nanxuanxn.top/Article/details/gt2jzlbazsi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gt2rdwxpoqk.html

[R07] if 判断文件
来源：http://dali.jinqigfzy.top/Article/details/gt2xhdqwimg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgufenzy.top/Article/details/gt2vbhkqewq.html

[R08] 数值比较
来源：http://dali.guowangkeji.top/Article/details/gt2nbauicws.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hfpthk.cn/Article/details/gt2ltaginek.html

[R09] 字符串比较
来源：http://dali.sxryk.cn/Article/details/gt2ymbqiajp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenzaomai.com/Article/details/gt2wrsczawo.html

[R10] 正则匹配
来源：http://dali.gzhubu.top/Article/details/gt2hxrbikwa.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fengsongda.top/Article/details/gt2dofepjyn.html

[R11] case 多分支
来源：http://dali.yanxiufei.cn/Article/details/gt2ckwbckft.html

case "$1" in
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ywdfqhyo.html

start) echo "启动" ;;
来源：http://dali.hysaishi.cn/Article/details/gt2qgrijxkh.html

stop)  echo "停止" ;;
来源：http://dali.cucudq.cn/Article/details/gt2qvygrxtp.html

*)     echo "未知命令" ;;
来源：http://dali.haohaochexian.top/Article/details/gt2ievouhlb.html

esac
来源：http://dali.sweek.top/Article/details/gt2isjftcdj.html

[R12] for 遍历文件
来源：http://dali.0kj1m.cn/Article/details/gt2xclcvzui.html

for f in *.txt; do echo "$f"; done
来源：http://dali.daxiang520.top/Article/details/gt2syzodtyr.html

[R13] for 计数循环
来源：http://dali.wangshuangyany.cn/Article/details/gt2aekwoxwh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gt2iwinjqqh.html

[R14] C 风格 for
来源：http://dali.nwbrower.top/Article/details/gt2xeboahme.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gt2djindcei.html

[R15] while 逐行读文件
来源：http://dali.iojbl.cn/Article/details/gt2kkfocgui.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jianghu66.top/Article/details/gt2pzdnuhwi.html

[R16] until 等待条件
来源：http://dali.xuanzx.com/Article/details/gt2qyzhfwet.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gt2firggtep.html

[R17] 数组定义与取值
来源：http://dali.ydzc1.top/Article/details/gt2snpbjicc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sufxvd.cn/Article/details/gt2mpwwoqhz.html

[R18] 遍历数组
来源：http://dali.shuidangran.top/Article/details/gt2awejchvz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hfpthk.cn/Article/details/gt2tuudzwoc.html

[R19] 数组长度
来源：http://dali.cheryme.top/Article/details/gt2mjavgrkr.html

echo "${#arr[@]}"
来源：http://dali.tian-w.cn/Article/details/gt2bhlzmtkk.html

[R20] 关联数组（字典）
来源：http://dali.xuetiantiany.cn/Article/details/gt2gwdjvuek.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2wjvddypv.html

[R21] 字符串长度
来源：http://dali.chenlongwang.top/Article/details/gt2nmsjifby.html

echo "${#s}"
来源：http://dali.316326.xyz/Article/details/gt2tnwcbxme.html

[R22] 截取子串
来源：http://dali.jinqigfzy.top/Article/details/gt2jbtwgszn.html

echo "${s:0:5}"
来源：http://dali.xziqi.cn/Article/details/gt2epeftdlg.html

[R23] 字符串替换
来源：http://dali.havefunace.top/Article/details/gt2hlbvdboy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cdnleiting.top/Article/details/gt2awvdytcr.html

[R24] 大小写转换
来源：http://dali.yonumen.top/Article/details/gt2xjpcihxj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hysaishi.cn/Article/details/gt2fpeaehkw.html

[R25] 去后缀 / 去前缀
来源：http://dali.daria6918.cn/Article/details/gt2dudwtxtz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gotoacloud.top/Article/details/gt2adhnhswr.html

[R26] 命令替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2knwwricx.html

now=$(date +%F); echo "$now"
来源：http://dali.fzhhl.top/Article/details/gt2rcglmcia.html

[R27] 算术展开
来源：http://dali.cheryme.top/Article/details/gt2gcjfkezp.html

echo $((1 + 2 * 3))
来源：http://dali.jinqigfzy.top/Article/details/gt2iwogsioa.html

[R28] 浮点运算
来源：http://dali.iojbl.cn/Article/details/gt2bcpliiez.html

echo "scale=2; 10/3" | bc
来源：http://dali.dianchejie.cn/Article/details/gt2qfqqorid.html

[R29] 定义函数
来源：http://dali.daria6918.cn/Article/details/gt2qzlomshu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sxryk.cn/Article/details/gt2ooeslfqq.html

[R30] 函数返回状态码
来源：http://dali.birdmap.top/Article/details/gt2yuqpekrh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.kuanghao11.cn/Article/details/gt2ziltbbwd.html

[R31] 局部变量
来源：http://dali.hammf.cn/Article/details/gt2sapacftc.html

f() { local x=1; echo "$x"; }
来源：http://dali.daria6918.cn/Article/details/gt2fwtkbzrt.html

[R32] 参数个数校验
来源：http://dali.jqgufenzy.top/Article/details/gt2hggaiinz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fengsongda.top/Article/details/gt2nsbesjvk.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigfzy.top/Article/details/gt2uslcswro.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.0kj1m.cn/Article/details/gt2wnxleqin.html

[R34] 退出时清理
来源：http://dali.meibo888.top/Article/details/gt2uaptkpdy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258888.top/Article/details/gt2kzsnjqgy.html

[R35] 后台执行并等待
来源：http://dali.xylfe.cn/Article/details/gt2ffhtwobu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zdqjudy.top/Article/details/gt2tgxxnqyx.html

[R36] 并发执行多个任务
来源：http://dali.xuetiantiany.cn/Article/details/gt2kwonczqk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nwbrower.top/Article/details/gt2hlxectec.html

[R37] 把输出赋给变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2umzzmybs.html

files=$(ls -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kdfidimo.html

[R38] 管道串联
来源：http://dali.sxryk.cn/Article/details/gt2hzzfxpcl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ehwqpu.com/Article/details/gt2vsoytxmx.html

[R39] 重定向标准输出与错误
来源：http://dali.andypj.xyz/Article/details/gt2qjijfjbx.html

cmd > out.log 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gt2jrvrvukk.html

[R40] 追加写日志
来源：http://dali.chenzaomai.com/Article/details/gt2wtxnyjpp.html

echo "log" >> out.log
来源：http://dali.jyoumei.cn/Article/details/gt2zjbalmri.html

[R41] 丢弃输出
来源：http://dali.cashguo.top/Article/details/gt2goydvzmc.html

cmd >/dev/null 2>&1
来源：http://dali.zhoulong.xyz/Article/details/gt2oodarusg.html

[R42] 输入重定向
来源：http://dali.zhongyouzk.top/Article/details/gt2cugtirhz.html

wc -l < a.txt
来源：http://dali.nanxinkj.top/Article/details/gt2syafynpy.html

[R43] 按名字查找文件
来源：http://dali.yj202588.top/Article/details/gt2yxkavcxv.html

find . -name "*.log" -type f
来源：http://dali.ivvv.top/Article/details/gt2icsrdhcx.html

[R44] 按修改时间查找
来源：http://dali.sxryk.cn/Article/details/gt2vcbaadkd.html

find . -mtime -7 -type f
来源：http://dali.hongshengwenyu.top/Article/details/gt2yydnleha.html

[R45] 批量删除
来源：http://dali.dashuyun.cn/Article/details/gt2xrqyzrys.html


<!-- 参考信息 -->