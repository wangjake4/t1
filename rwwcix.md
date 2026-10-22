代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhengqikj.top/Article/details/gtsxeuobkl.html

user_id INT NOT NULL,
来源：http://dali.haohaochexian.top/Article/details/gtrbmcztmh.html

amount DECIMAL(10, 2),
来源：http://dali.yuxming.cn/Article/details/gtxdcbwpmi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.svipenyu.cn/Article/details/gtacuckqrw.html

);
来源：http://dali.cucudq.cn/Article/details/gtwhhoawyt.html

[Q03] 增加列
来源：http://dali.dianchejie.cn/Article/details/gtcfiungyx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.havefunace.top/Article/details/gtwbptqmov.html

[Q04] 修改列类型
来源：http://dali.haohaochexian.top/Article/details/gtapmpybdn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinghuilouyu.cn/Article/details/gttprjdwxq.html

[Q05] 重命名列
来源：http://dali.hnqzz.top/Article/details/gtgmlveucu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ehwqpu.com/Article/details/gtwvcdsdge.html

[Q06] 删除列
来源：http://dali.xziqi.cn/Article/details/gtfzamfnyp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.mhx1999.top/Article/details/gtngfdvtge.html

[Q07] 删除表
来源：http://dali.hysaishi.cn/Article/details/gtirbsryul.html

DROP TABLE IF EXISTS orders;
来源：http://dali.bjfxy.top/Article/details/gtardqqbfr.html

[Q08] 创建普通索引
来源：http://dali.gzhubu.top/Article/details/gtuegruann.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gtmewblceh.html

[Q09] 创建唯一索引
来源：http://dali.haohaochexian.top/Article/details/gtncrcatqe.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tanke756.top/Article/details/gtekpfkopg.html

[Q10] 插入单行
来源：http://dali.xuanzx.com/Article/details/gtmopbnxtq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nanxinkj.top/Article/details/gtfvblyzwv.html

[Q11] 一次插入多行
来源：http://dali.daria6918.cn/Article/details/gtnegvzqeo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gtlmzvczjo.html

[Q12] 插入后取自增 ID
来源：http://dali.sweek.top/Article/details/gtgqwsdzse.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxinkj.top/Article/details/gtqtefeqvk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuxming.cn/Article/details/gtdgxgldwh.html

[Q13] 忽略重复插入
来源：http://dali.fzhhl.top/Article/details/gtpxczaltj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gtxacztqbr.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuxming.cn/Article/details/gtksaemibj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gotoacloud.top/Article/details/gtsvhvvetr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.andypj.xyz/Article/details/gttuxrzqxd.html

[Q15] 查询全部
来源：http://dali.ppjwa.cn/Article/details/gtvjchmhjm.html

SELECT * FROM users;
来源：http://dali.smart0.xyz/Article/details/gteoztdplr.html

[Q16] 查询指定列
来源：http://dali.gaohongyu789.top/Article/details/gtyygeikbh.html

SELECT id, name FROM users;
来源：http://dali.yvedp.cn/Article/details/gtepefwtgc.html

[Q17] 条件查询
来源：http://dali.zdqjudy.top/Article/details/gtcwgqqnve.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pycfn.com/Article/details/gtagwixhog.html

[Q18] 模糊匹配
来源：http://dali.zhengqikj.top/Article/details/gtqjjvamjg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnqzz.top/Article/details/gtexaevfmr.html

[Q19] 范围查询
来源：http://dali.gotoacloud.top/Article/details/gtniltfsfn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhengqikj.top/Article/details/gtaxmpypko.html

[Q20] IN 列表
来源：http://dali.yonumen.top/Article/details/gtkjnjdlcb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.havefunace.top/Article/details/gtvjzortuj.html

[Q21] 空值判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkctqmvpx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shangyingyoupin.top/Article/details/gtzxyecspd.html

[Q22] 排序
来源：http://dali.dianchejie.cn/Article/details/gtltrawytb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.dashuyun.cn/Article/details/gtipxumqvh.html

[Q23] 分页
来源：http://dali.hywenlv.cn/Article/details/gtjufbxxlt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinqigufen.top/Article/details/gtrlplozdz.html

[Q24] 去重
来源：http://dali.gotoacloud.top/Article/details/gtcwxexffy.html

SELECT DISTINCT city FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtrveqxkxp.html

[Q25] 只取前 N 条
来源：http://dali.meibo888.top/Article/details/gtldtxnflg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shuidangran.top/Article/details/gtexnniedf.html

[Q26] 计数
来源：http://dali.shuidangran.top/Article/details/gtcunbqlad.html

SELECT COUNT(*) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtxevbzpfc.html

[Q27] 条件计数
来源：http://dali.316326.xyz/Article/details/gtymwmfnap.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtqzkdkmpc.html

[Q28] 求和与平均
来源：http://dali.birdmap.top/Article/details/gterktsnbl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258.top/Article/details/gtnbpflcyu.html

[Q29] 最大最小值
来源：http://dali.zhixingplan.top/Article/details/gtlrpgivhn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdyiyuakv.html

[Q30] 分组统计
来源：http://dali.pengpengdd.cyou/Article/details/gtbsgahcwb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gtffovenlp.html

[Q31] 分组后过滤
来源：http://dali.chenzaomai.com/Article/details/gtetzglsni.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.birdmap.top/Article/details/gtwotmwoga.html

[Q32] 分组拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtbweqyjxq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gtplyntqyw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.meibo888.top/Article/details/gtarxxlrzu.html

[Q33] 多列分组
来源：http://dali.vqdsnc.cn/Article/details/gtiqrwksji.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xuanzx.com/Article/details/gtjtcwtlwx.html

[Q34] 每组取第一条
来源：http://dali.sufxvd.cn/Article/details/gtawudheeg.html

SELECT * FROM (
来源：http://dali.aibaodan.cn/Article/details/gtnjvjqdzt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupbfczia.html

) t WHERE rn = 1;
来源：http://dali.yonumen.top/Article/details/gtonipnkjn.html

[Q35] 内连接
来源：http://dali.daxiang520.top/Article/details/gtnszjajfw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ivvv.top/Article/details/gtiogburyr.html

[Q36] 左连接
来源：http://dali.yuxming.cn/Article/details/gtdqfwhzcb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxinkj.top/Article/details/gtuxqymudd.html

[Q37] 右连接
来源：http://dali.zhengqikj.top/Article/details/gtcwnusfji.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gaohongyu789.top/Article/details/gtqddgcvtc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.meibo888.top/Article/details/gteyzazini.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiaznkgve.html

[Q39] 自连接（查上下级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwyexktyt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuanzhike.top/Article/details/gtldiqvksl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.mhx1999.top/Article/details/gtoaoswgxg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.9152youxi.cn/Article/details/gtwfyvbbuk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenlongwang.top/Article/details/gtldtfhoic.html

[Q41] 多表连接
来源：http://dali.aizwys.cn/Article/details/gtfvtqvkcq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jiagoushi.top/Article/details/gtilxegixm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.guowangkeji.top/Article/details/gtlkiptlvf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tanke756.top/Article/details/gtsjpxgvjw.html

[Q42] 连接条件附加过滤
来源：http://dali.zycfv.cn/Article/details/gtmcbtusnu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sufxvd.cn/Article/details/gteqrrxwmx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hywenlv.cn/Article/details/gtkctuatmt.html

[Q43] 标量子查询
来源：http://dali.zhixingplan.top/Article/details/gtamkmnngo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aizwys.cn/Article/details/gtroibcilh.html

[Q44] IN 子查询
来源：http://dali.sxryk.cn/Article/details/gthlyqojrl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.vqdsnc.cn/Article/details/gtfbbeycef.html

[Q45] EXISTS 判断存在
来源：http://dali.sweek.top/Article/details/gtwvbodktp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gtbqwaqzgd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhoulong.xyz/Article/details/gtdiujgfzf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xziqi.cn/Article/details/gtbtprrbrs.html

[Q47] 与平均值比较
来源：http://dali.chenjidiqi.icu/Article/details/gtfxzfvnon.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sxryk.cn/Article/details/gtztzbokuz.html

[Q48] CTE 公用表表达式
来源：http://dali.meibo888.top/Article/details/gtycxotfyq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cashguo.top/Article/details/gtonmqxjdf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258.top/Article/details/gtbgnbdgke.html

[Q49] 更新单行
来源：http://dali.nwbrower.top/Article/details/gtrpufbxfz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yonumen.top/Article/details/gtzbdtzyoz.html

[Q50] 批量更新
来源：http://dali.daxiang520.top/Article/details/gtvsmrmsch.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnqzz.top/Article/details/gtccqjkqjh.html

[Q51] 用子查询更新
来源：http://dali.jlsjyb.cn/Article/details/gtcvvibkdt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.pycfn.com/Article/details/gtlslledac.html

[Q52] 删除指定行
来源：http://dali.aizwys.cn/Article/details/gtprexlbxn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hammf.cn/Article/details/gtuqepdbvh.html

[Q53] 按条件删除
来源：http://dali.yj202588.top/Article/details/gtqkdvfvpk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gtrpctwrek.html

[Q54] 清空表
来源：http://dali.316326.xyz/Article/details/gtgivyxasc.html

TRUNCATE TABLE logs;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvowoijnr.html

[Q55] 排名（并列占位）
来源：http://dali.vqdsnc.cn/Article/details/gtxflkocog.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yvedp.cn/Article/details/gtqvqrnmei.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gtltjondbq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sysykeji.top/Article/details/gtwdsgpdxo.html

[Q57] 行号
来源：http://dali.sysykeji.top/Article/details/gtypgevyga.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuxming.cn/Article/details/gtqprajfuj.html

[Q58] 累计求和
来源：http://dali.tanke756.top/Article/details/gtykfjpeme.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj202588.top/Article/details/gtseyrttth.html

[Q59] 分组内累计
来源：http://dali.xuanzx.com/Article/details/gtvqgxrayw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtzeptwvmz.html

[Q60] 取上一行 / 下一行
来源：http://dali.nwbrower.top/Article/details/gtssabytsb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hfpthk.cn/Article/details/gtfmlsmuhg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtpashbirx.html

[Q61] 移动平均
来源：http://dali.cucudq.cn/Article/details/gtwyzvzvwj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yonumen.top/Article/details/gtaqjvfktv.html

[Q62] 分组占比
来源：http://dali.chenlongwang.top/Article/details/gtqjhghadk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjlhknko.html

[Q63] 开启事务
来源：http://dali.xziqi.cn/Article/details/gtzomalauj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gtxkhvffds.html

[Q64] 提交事务
来源：http://dali.ivvv.top/Article/details/gttoygvwcb.html

COMMIT;
来源：http://dali.havefunace.top/Article/details/gtxhzbalbi.html

[Q65] 回滚事务
来源：http://dali.zhiwuduotai.top/Article/details/gtaphxyrue.html

ROLLBACK;
来源：http://dali.zhiwuduotai.top/Article/details/gtkmoglyxi.html

[Q66] 行锁查询
来源：http://dali.yonumen.top/Article/details/gthwbbpenx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cdnleiting.top/Article/details/gthgpujhsu.html

[Q67] 设置隔离级别
来源：http://dali.ehwqpu.com/Article/details/gtwhpjmirw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoaluslib.html

[Q68] 保存点
来源：http://dali.nanxuanxn.top/Article/details/gtuitqhsyr.html

SAVEPOINT sp1;
来源：http://dali.jyoumei.cn/Article/details/gtfmrgjvcq.html

ROLLBACK TO sp1;
来源：http://dali.yj20258888.top/Article/details/gtsvzrvscx.html

[Q69] 查看执行计划
来源：http://dali.chenjidiqi.icu/Article/details/gtpjnaiasr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ehwqpu.com/Article/details/gtkxomsizs.html

[Q70] 更新统计信息
来源：http://dali.sufxvd.cn/Article/details/gtalyqfsra.html

ANALYZE TABLE users;
来源：http://dali.yangfankeji.com/Article/details/gtuuikvzca.html

[Q71] 查看建表语句
来源：http://dali.shzxlz.cn/Article/details/gthrjyedzx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hongshengwenyu.top/Article/details/gtmgrigurg.html

[Q72] 查看索引
来源：http://dali.xuanzx.com/Article/details/gtotbgatal.html

SHOW INDEX FROM users;
来源：http://dali.yvedp.cn/Article/details/gtlusggdma.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gtmmzqjnll.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.redwolf501.top/Article/details/gtamymfvqa.html

[Q74] 强制使用索引
来源：http://dali.birdmap.top/Article/details/gtepvaavja.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.aibaodan.cn/Article/details/gtdqseoudl.html

[Q75] 日期格式化
来源：http://dali.havefunace.top/Article/details/gterneesxc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtjipuyoau.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.daxiang520.top/Article/details/gtcqjcvdsl.html

[Q76] 按天统计
来源：http://dali.fzhhl.top/Article/details/gtkoledfaz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cdnleiting.top/Article/details/gtuxbfyjio.html

[Q77] 时间加减
来源：http://dali.yj20258.top/Article/details/gtyrwjflad.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj202588.top/Article/details/gtizumdvvw.html

[Q78] 当前时间
来源：http://dali.shzxlz.cn/Article/details/gtedhlkwkh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.svipenyu.cn/Article/details/gtvylssfub.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangtech.top/Article/details/gtekgwoqau.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yueranfly.top/Article/details/gtpsrmxvah.html

[Q80] 字符串截取
来源：http://dali.nanxinkj.top/Article/details/gtnnrjxaak.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtapegzuwg.html

[Q81] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gtsyeiwnqm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtbttflktt.html

[Q82] 字符长度与字节长度
来源：http://dali.xinyue.icu/Article/details/gtulvoamcs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwbnlbmp.html

[Q83] 大小写转换
来源：http://dali.havefunace.top/Article/details/gtsrhvqxcj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtalxjzljw.html

[Q84] 去除首尾空格
来源：http://dali.yj20258888.top/Article/details/gtvjfnhxhk.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtxkhaqmlh.html

[Q85] 数值取整
来源：http://dali.mhx1999.top/Article/details/gtlrnuqock.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tianlin.xyz/Article/details/gtmajaybqz.html

[Q86] 读取 JSON 字段
来源：http://dali.cheryme.top/Article/details/gtjxptlvis.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.mhx1999.top/Article/details/gtegbytfsk.html

[Q87] JSON 字段做条件
来源：http://dali.gaohongyu789.top/Article/details/gtirwurylx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.c1oappe.top/Article/details/gtbnpufiwt.html

[Q88] 行转列（条件聚合）
来源：http://dali.jyoumei.cn/Article/details/gtbsnooskv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nwbrower.top/Article/details/gtlxokegox.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pycfn.com/Article/details/gtzsnotxil.html

[Q89] 判断表是否存在
来源：http://dali.sufxvd.cn/Article/details/gtuopcginp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tian-w.cn/Article/details/gtbksfofig.html

[Q90] 生成序号列
来源：http://dali.nanxinkj.top/Article/details/gtrppmrvot.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jqgfzy.top/Article/details/gtodavngde.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gttvkqmohf.html

R. Bash 专题
来源：http://dali.mhx1999.top/Article/details/gtkvjhhirl.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gttuihgrlw.html

[R01] shebang 与严格模式
来源：http://dali.hnqzz.top/Article/details/gttlppmqsw.html

#!/usr/bin/env bash
来源：http://dali.yanxiufei.cn/Article/details/gtvtitemqm.html

set -euo pipefail
来源：http://dali.cashguo.top/Article/details/gtngnbyuvw.html

[R02] 变量赋值与使用
来源：http://dali.sufxvd.cn/Article/details/gtxfcisfcy.html

name="Tom"; echo "$name"
来源：http://dali.iojbl.cn/Article/details/gtnnvcltli.html

[R03] 只读变量
来源：http://dali.hnqzz.top/Article/details/gtcdogatfb.html

readonly PI=3.14
来源：http://dali.jqgufenzy.top/Article/details/gtmzxnzfcx.html

[R04] 位置参数
来源：http://dali.xylfe.cn/Article/details/gtyetlipdl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinghuilouyu.cn/Article/details/gtaytkratq.html

[R05] 参数默认值
来源：http://dali.zhoulong.xyz/Article/details/gtdeyuwori.html

name="${1:-default}"
来源：http://dali.snrcjt.cn/Article/details/gtkwaxoucl.html

[R06] 判断命令是否存在
来源：http://dali.iojbl.cn/Article/details/gtktooikzg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cdnleiting.top/Article/details/gttidqzzqv.html

[R07] if 判断文件
来源：http://dali.svipenyu.cn/Article/details/gtjqitsksb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zdqjudy.top/Article/details/gtxzkwqrrd.html

[R08] 数值比较
来源：http://dali.cqqwz.cn/Article/details/gtllnogtex.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sufxvd.cn/Article/details/gtzjdevvak.html

[R09] 字符串比较
来源：http://dali.jiagoushi.top/Article/details/gtyjgvwyyh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xziqi.cn/Article/details/gtfjgtwlas.html

[R10] 正则匹配
来源：http://dali.gotoacloud.top/Article/details/gtouvgxveg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tanke756.top/Article/details/gtzvgwxums.html

[R11] case 多分支
来源：http://dali.yonumen.top/Article/details/gtzwkkoimm.html

case "$1" in
来源：http://dali.fzhhl.top/Article/details/gtloyidufi.html

start) echo "启动" ;;
来源：http://dali.snrcjt.cn/Article/details/gtbtmezogw.html

stop)  echo "停止" ;;
来源：http://dali.mhx1999.top/Article/details/gtpzmzxbrg.html

*)     echo "未知命令" ;;
来源：http://dali.cdnleiting.top/Article/details/gtdmhrbund.html

esac
来源：http://dali.yonumen.top/Article/details/gtssajhiur.html

[R12] for 遍历文件
来源：http://dali.xinyue.icu/Article/details/gtzmjmbnjj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.9152youxi.cn/Article/details/gteixypxau.html

[R13] for 计数循环
来源：http://dali.jqgufenzy.top/Article/details/gtzklfebcr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gtzbkkgmxm.html

[R14] C 风格 for
来源：http://dali.yj20258888.top/Article/details/gtslnsnmdn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xylfe.cn/Article/details/gtatfesekt.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzebclnd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hnqzz.top/Article/details/gtlydxvmax.html

[R16] until 等待条件
来源：http://dali.yangfankeji.com/Article/details/gttqbdsxri.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gtizchujia.html

[R17] 数组定义与取值
来源：http://dali.yanxiufei.cn/Article/details/gthmtdjxtu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.iojbl.cn/Article/details/gtouecvddl.html

[R18] 遍历数组
来源：http://dali.tian-w.cn/Article/details/gtavhxldkz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jlsjyb.cn/Article/details/gtrmlynsyp.html

[R19] 数组长度
来源：http://dali.gzhubu.top/Article/details/gtqepssxuy.html

echo "${#arr[@]}"
来源：http://dali.zhixingplan.top/Article/details/gtbifbvrld.html

[R20] 关联数组（字典）
来源：http://dali.iojbl.cn/Article/details/gterrkkvit.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxinkj.top/Article/details/gtwkagbuiq.html

[R21] 字符串长度
来源：http://dali.0kj1m.cn/Article/details/gtogmpumxy.html

echo "${#s}"
来源：http://dali.feifeiyinyue.top/Article/details/gtwofseqob.html

[R22] 截取子串
来源：http://dali.wangdashe.top/Article/details/gtjxwcyjku.html

echo "${s:0:5}"
来源：http://dali.cqqwz.cn/Article/details/gtymtbnsfk.html

[R23] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gtblmboblt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.guowangkeji.top/Article/details/gtiiovlyjf.html

[R24] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gtbfkvlsnx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hfpthk.cn/Article/details/gtronpskzm.html

[R25] 去后缀 / 去前缀
来源：http://dali.shzxlz.cn/Article/details/gtfvxqptcq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqsotndk.html

[R26] 命令替换
来源：http://dali.gaohongyu789.top/Article/details/gtssxxleiw.html

now=$(date +%F); echo "$now"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnvygbhf.html

[R27] 算术展开
来源：http://dali.zhixingplan.top/Article/details/gtuzsjzxdb.html

echo $((1 + 2 * 3))
来源：http://dali.gogol.net.cn/Article/details/gtplluyzrr.html

[R28] 浮点运算
来源：http://dali.nanxuanxn.top/Article/details/gtpnsitrai.html

echo "scale=2; 10/3" | bc
来源：http://dali.sxryk.cn/Article/details/gtrxdwnjks.html

[R29] 定义函数
来源：http://dali.nanxuanxn.top/Article/details/gtgzievhhq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gzhubu.top/Article/details/gtajewhcdi.html

[R30] 函数返回状态码
来源：http://dali.c1oappe.top/Article/details/gthdsvocai.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sufxvd.cn/Article/details/gtspahcnsg.html

[R31] 局部变量
来源：http://dali.sxryk.cn/Article/details/gtxzxaffbw.html

f() { local x=1; echo "$x"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzljbpwxn.html

[R32] 参数个数校验
来源：http://dali.aibaodan.cn/Article/details/gtlxwbuvme.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.c1oappe.top/Article/details/gtkhueplso.html

[R33] 捕获错误并提示行号
来源：http://dali.shangyingyoupin.top/Article/details/gtjmhjrmxq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yueranfly.top/Article/details/gtlriwgkdi.html

[R34] 退出时清理
来源：http://dali.jinqigfzy.top/Article/details/gtrdxmbfby.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gthmwpxatf.html

[R35] 后台执行并等待
来源：http://dali.jinqigufen.top/Article/details/gtbficyhzt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvtpyjkb.html

[R36] 并发执行多个任务
来源：http://dali.yangfankeji.com/Article/details/gtjfucdfzd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ydzc1.top/Article/details/gttkyvycdx.html

[R37] 把输出赋给变量
来源：http://dali.cqqwz.cn/Article/details/gtaspxoqft.html

files=$(ls -1)
来源：http://dali.chenjidiqi.icu/Article/details/gtktddfnbk.html

[R38] 管道串联
来源：http://dali.dashuyun.cn/Article/details/gtpsjvnqxm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvdysojy.html

[R39] 重定向标准输出与错误
来源：http://dali.shangyingyoupin.top/Article/details/gtecctvhom.html

cmd > out.log 2>&1
来源：http://dali.ivvv.top/Article/details/gtdqftlqnq.html

[R40] 追加写日志
来源：http://dali.jianghu66.top/Article/details/gtavrlkbdi.html

echo "log" >> out.log
来源：http://dali.xuanzx.com/Article/details/gtzlmonnar.html

[R41] 丢弃输出
来源：http://dali.zhiwuduotai.top/Article/details/gtunxgfoek.html

cmd >/dev/null 2>&1
来源：http://dali.zhoulong.xyz/Article/details/gtbxybbtma.html

[R42] 输入重定向
来源：http://dali.zhongyouzk.top/Article/details/gtklwsrrqq.html

wc -l < a.txt
来源：http://dali.guowangkeji.top/Article/details/gtjvdznmuv.html

[R43] 按名字查找文件
来源：http://dali.hysaishi.cn/Article/details/gtdnvajmcm.html

find . -name "*.log" -type f
来源：http://dali.jyoumei.cn/Article/details/gttrvrktwn.html

[R44] 按修改时间查找
来源：http://dali.jyoumei.cn/Article/details/gtievrkrpu.html

find . -mtime -7 -type f
来源：http://dali.ehwqpu.com/Article/details/gtvnjsvszo.html

[R45] 批量删除
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnygjofuc.html

find . -name "*.tmp" -delete
来源：http://dali.yueranfly.top/Article/details/gtqdiilxhy.html

[R46] 递归替换文件内容
来源：http://dali.xylfe.cn/Article/details/gtydwkjiht.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258.top/Article/details/gtsgdgqjws.html

[R47] sed 单行替换
来源：http://dali.hfpthk.cn/Article/details/gtbmngwnyw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.c1oappe.top/Article/details/gtckrzbrft.html

[R48] awk 取指定列
来源：http://dali.zhengqikj.top/Article/details/gtzsdqxecd.html

awk '{print $1, $3}' a.txt
来源：http://dali.xylfe.cn/Article/details/gtiqiqsthj.html

[R49] awk 带条件
来源：http://dali.sysykeji.top/Article/details/gtjmimcxun.html


<!-- 参考信息 -->