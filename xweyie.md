代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhiwuduotai.top/Article/details/gtcbuiqxfr.html

);
来源：http://dali.smart0.xyz/Article/details/gteuiegcsa.html

[Q02] 创建带外键的表
来源：http://dali.shuidangran.top/Article/details/gtsvsmqqbv.html

CREATE TABLE orders (
来源：http://dali.shuidangran.top/Article/details/gtdarmglpq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yueranfly.top/Article/details/gtrddyxbic.html

user_id INT NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gtluiaedyc.html

amount DECIMAL(10, 2),
来源：http://dali.gogol.net.cn/Article/details/gtfwcmebra.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhixingplan.top/Article/details/gtbehzuqhm.html

);
来源：http://dali.gaohongyu789.top/Article/details/gtpkuehenu.html

[Q03] 增加列
来源：http://dali.sufxvd.cn/Article/details/gthnzrhrdw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinqigfzy.top/Article/details/gtazhvagij.html

[Q04] 修改列类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnbpncar.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.wangshuangyany.cn/Article/details/gtlrzkaiow.html

[Q05] 重命名列
来源：http://dali.daxiang520.top/Article/details/gtshztnrkv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.quarkkingdee.top/Article/details/gtwlbacbtf.html

[Q06] 删除列
来源：http://dali.hnxiangtu.top/Article/details/gtmxfcrtzc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocylhthr.html

[Q07] 删除表
来源：http://dali.hysaishi.cn/Article/details/gtfrhkpzlf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.guowangkeji.top/Article/details/gtvxckxhct.html

[Q08] 创建普通索引
来源：http://dali.316326.xyz/Article/details/gtrjczrltd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zycfv.cn/Article/details/gtmswkikgd.html

[Q09] 创建唯一索引
来源：http://dali.c1oappe.top/Article/details/gthtlggkbf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jlsjyb.cn/Article/details/gtksvjxchf.html

[Q10] 插入单行
来源：http://dali.cashguo.top/Article/details/gtbwhylbfc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.aizwys.cn/Article/details/gtwwekmalt.html

[Q11] 一次插入多行
来源：http://dali.xylfe.cn/Article/details/gtwqaxsyxq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj20258.top/Article/details/gtnbqnrdbx.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangtech.top/Article/details/gttnkvggse.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aibaodan.cn/Article/details/gtinedupid.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinghuilouyu.cn/Article/details/gtptttwaaq.html

[Q13] 忽略重复插入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvexkwfq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.meibo888.top/Article/details/gtsfkuajed.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnxiangtu.top/Article/details/gtirezfhdi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.daria6918.cn/Article/details/gtclotpxnk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hongshengwenyu.top/Article/details/gtskiqjeqf.html

[Q15] 查询全部
来源：http://dali.meibo888.top/Article/details/gtxsrotbyb.html

SELECT * FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxlqpcjj.html

[Q16] 查询指定列
来源：http://dali.kuanghao11.cn/Article/details/gttxqryrps.html

SELECT id, name FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtossvyzwu.html

[Q17] 条件查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtfbbfsy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jiagoushi.top/Article/details/gtbmhommnq.html

[Q18] 模糊匹配
来源：http://dali.xziqi.cn/Article/details/gthzlnxixu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yongpay.top/Article/details/gtxwlvolia.html

[Q19] 范围查询
来源：http://dali.cdnleiting.top/Article/details/gtvqxteptg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sysykeji.top/Article/details/gtqfkcspxc.html

[Q20] IN 列表
来源：http://dali.ppjwa.cn/Article/details/gthjdjcfnx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgfzy.top/Article/details/gtsebwektj.html

[Q21] 空值判断
来源：http://dali.cucudq.cn/Article/details/gtzvhkclaz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sweek.top/Article/details/gtchwwymuu.html

[Q22] 排序
来源：http://dali.zdqjudy.top/Article/details/gtbcilgsqs.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nanxinkj.top/Article/details/gtesfoukvj.html

[Q23] 分页
来源：http://dali.zhengqikj.top/Article/details/gtogqcehkz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xuanzx.com/Article/details/gtpgrmaoxu.html

[Q24] 去重
来源：http://dali.hnxiangtu.top/Article/details/gtppehmrtv.html

SELECT DISTINCT city FROM users;
来源：http://dali.sysykeji.top/Article/details/gtfcodtohg.html

[Q25] 只取前 N 条
来源：http://dali.vqdsnc.cn/Article/details/gtsyxaqpjv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sxryk.cn/Article/details/gtruljohge.html

[Q26] 计数
来源：http://dali.daxiang520.top/Article/details/gtetidgyzb.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtgwkxvzsr.html

[Q27] 条件计数
来源：http://dali.hysaishi.cn/Article/details/gtracdlxzl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtknzpfnmj.html

[Q28] 求和与平均
来源：http://dali.dianchejie.cn/Article/details/gtsrexmxgy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvurhybqm.html

[Q29] 最大最小值
来源：http://dali.xuetiantiany.cn/Article/details/gtafewzfge.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtihrfiurs.html

[Q30] 分组统计
来源：http://dali.fengsongda.top/Article/details/gtfepdceyy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtatsftwsp.html

[Q31] 分组后过滤
来源：http://dali.cashguo.top/Article/details/gtyavkfbbl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yangfankeji.com/Article/details/gtyfbpgiey.html

[Q32] 分组拼接字符串
来源：http://dali.yongpay.top/Article/details/gtsgsyjyho.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtsvqahnxw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ehwqpu.com/Article/details/gteaqdicvh.html

[Q33] 多列分组
来源：http://dali.yangfankeji.com/Article/details/gtvvitjwyw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ybcxt.top/Article/details/gtivwlffdy.html

[Q34] 每组取第一条
来源：http://dali.meibo888.top/Article/details/gtjfavgewt.html

SELECT * FROM (
来源：http://dali.birdmap.top/Article/details/gterriffyt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shuidangran.top/Article/details/gtoijsujlp.html

) t WHERE rn = 1;
来源：http://dali.yangfankeji.com/Article/details/gtnwozxrnm.html

[Q35] 内连接
来源：http://dali.dianchejie.cn/Article/details/gtrinlfgtq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gtdgavpzad.html

[Q36] 左连接
来源：http://dali.gaohongyu789.top/Article/details/gtwvibvcpg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenjidiqi.icu/Article/details/gtpmuodrhf.html

[Q37] 右连接
来源：http://dali.gogol.net.cn/Article/details/gtzltlldho.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.9152youxi.cn/Article/details/gtamfhxywr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cqqwz.cn/Article/details/gtlquhsunz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.iojbl.cn/Article/details/gtgobdgklq.html

[Q39] 自连接（查上下级）
来源：http://dali.yuanzhike.top/Article/details/gtwjnvcaga.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinqigufen.top/Article/details/gtzmelrahi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenzaomai.com/Article/details/gtkebkpixm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.havefunace.top/Article/details/gtghkstcuh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sxryk.cn/Article/details/gtpxoowiug.html

[Q41] 多表连接
来源：http://dali.0kj1m.cn/Article/details/gtiwiaftst.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hywenlv.cn/Article/details/gtjgmyuhfv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangkeji.top/Article/details/gtulyerwqp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cashguo.top/Article/details/gtiilmkqtp.html

[Q42] 连接条件附加过滤
来源：http://dali.ehwqpu.com/Article/details/gtmqgmhfsx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.snrcjt.cn/Article/details/gteplqhepj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.redwolf501.top/Article/details/gtfxtkejux.html

[Q43] 标量子查询
来源：http://dali.xuanzx.com/Article/details/gtbwrfioje.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yangfankeji.com/Article/details/gtkmzrpapz.html

[Q44] IN 子查询
来源：http://dali.tian-w.cn/Article/details/gtzwjkcpzu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.kuanghao11.cn/Article/details/gtgktztndy.html

[Q45] EXISTS 判断存在
来源：http://dali.svipenyu.cn/Article/details/gteimqyxwq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gthgmlpbxm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cdnleiting.top/Article/details/gtribagvsp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gtvafetbmj.html

[Q47] 与平均值比较
来源：http://dali.xuetiantiany.cn/Article/details/gtlenuimlf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xinyue.icu/Article/details/gtlklmgubr.html

[Q48] CTE 公用表表达式
来源：http://dali.xinyue.icu/Article/details/gtkntyncxu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ehwqpu.com/Article/details/gtchldjvri.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.pycfn.com/Article/details/gtubxbqrct.html

[Q49] 更新单行
来源：http://dali.pycfn.com/Article/details/gtaarpfdpq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hammf.cn/Article/details/gtzvtmzyxu.html

[Q50] 批量更新
来源：http://dali.zhixingplan.top/Article/details/gtadujvbzq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenlongwang.top/Article/details/gtoackfeuf.html

[Q51] 用子查询更新
来源：http://dali.shangyingyoupin.top/Article/details/gtmmfhnhsa.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.daria6918.cn/Article/details/gttrxfxnue.html

[Q52] 删除指定行
来源：http://dali.zhixingplan.top/Article/details/gtjsrqsubk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cqqwz.cn/Article/details/gtwbzjeqso.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gtiszvncoj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.bjfxy.top/Article/details/gtfgzjseaa.html

[Q54] 清空表
来源：http://dali.hnqzz.top/Article/details/gtnairqudt.html

TRUNCATE TABLE logs;
来源：http://dali.shuidangran.top/Article/details/gtarbbcbsj.html

[Q55] 排名（并列占位）
来源：http://dali.hywenlv.cn/Article/details/gtdcosqbet.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shuidangran.top/Article/details/gtbjxxxnts.html

[Q56] 密集排名（并列不占位）
来源：http://dali.feifeiyinyue.top/Article/details/gtyxrithgg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.snrcjt.cn/Article/details/gtcthknoam.html

[Q57] 行号
来源：http://dali.sysykeji.top/Article/details/gtubebkvrx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtzxmzqzic.html

[Q58] 累计求和
来源：http://dali.ppjwa.cn/Article/details/gtgdjdetqe.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtdkvnisvv.html

[Q59] 分组内累计
来源：http://dali.yonumen.top/Article/details/gtgcvgcmob.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtgmxjbqki.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowzsepxm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jiagoushi.top/Article/details/gtclwtdtiw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtwvdqdjip.html

[Q61] 移动平均
来源：http://dali.birdmap.top/Article/details/gttenromsb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtyuyufgid.html

[Q62] 分组占比
来源：http://dali.cashguo.top/Article/details/gtndwiezhi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwthdawyy.html

[Q63] 开启事务
来源：http://dali.yonumen.top/Article/details/gtbqheylxc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sufxvd.cn/Article/details/gtspqtdleo.html

[Q64] 提交事务
来源：http://dali.pengpengdd.cyou/Article/details/gtxjfpeqae.html

COMMIT;
来源：http://dali.cdnleiting.top/Article/details/gtuyqgmprb.html

[Q65] 回滚事务
来源：http://dali.jlsjyb.cn/Article/details/gtixlhsrsn.html

ROLLBACK;
来源：http://dali.vqdsnc.cn/Article/details/gttvarhidl.html

[Q66] 行锁查询
来源：http://dali.chenzaomai.com/Article/details/gtttsgwvfl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hfpthk.cn/Article/details/gtltzesfes.html

[Q67] 设置隔离级别
来源：http://dali.sysykeji.top/Article/details/gtdtimqhjb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cashguo.top/Article/details/gtxkcabtzo.html

[Q68] 保存点
来源：http://dali.jyoumei.cn/Article/details/gtuotfueeq.html

SAVEPOINT sp1;
来源：http://dali.xylfe.cn/Article/details/gtzfvwhprd.html

ROLLBACK TO sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdngaqtjf.html

[Q69] 查看执行计划
来源：http://dali.zhongyouzk.top/Article/details/gtsgengdji.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.svipenyu.cn/Article/details/gtrvtulubv.html

[Q70] 更新统计信息
来源：http://dali.guowangkeji.top/Article/details/gtxzfqbcsk.html

ANALYZE TABLE users;
来源：http://dali.shangyingyoupin.top/Article/details/gtgwcrfwon.html

[Q71] 查看建表语句
来源：http://dali.9152youxi.cn/Article/details/gtedryxaiy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.kuanghao11.cn/Article/details/gtfcxtkskn.html

[Q72] 查看索引
来源：http://dali.zdqjudy.top/Article/details/gtvbacywpa.html

SHOW INDEX FROM users;
来源：http://dali.xylfe.cn/Article/details/gtsyqybdhr.html

[Q73] 查看表状态
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvanjeyzy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.smart0.xyz/Article/details/gtyxoalgfz.html

[Q74] 强制使用索引
来源：http://dali.9152youxi.cn/Article/details/gtzejmbrgf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ppjwa.cn/Article/details/gtadsznihi.html

[Q75] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gtssvyaqdf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtetpsawyt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shuidangran.top/Article/details/gtvrigdlnj.html

[Q76] 按天统计
来源：http://dali.guowangkeji.top/Article/details/gtvjvljvfb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sweek.top/Article/details/gtejxwoupa.html

[Q77] 时间加减
来源：http://dali.sxryk.cn/Article/details/gtrhqrfvly.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.andypj.xyz/Article/details/gtcscwtcea.html

[Q78] 当前时间
来源：http://dali.nwbrower.top/Article/details/gtlrakqirl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigufen.top/Article/details/gtdrcvehst.html

[Q79] 字符串拼接
来源：http://dali.jyoumei.cn/Article/details/gtvuxxznot.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hywenlv.cn/Article/details/gtogysmjqg.html

[Q80] 字符串截取
来源：http://dali.meibo888.top/Article/details/gtgyfmxctq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclfurzyd.html

[Q81] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gttmpqedcs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtaqtcptfs.html

[Q82] 字符长度与字节长度
来源：http://dali.hfpthk.cn/Article/details/gtsgbvdlwe.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtktxnislf.html

[Q83] 大小写转换
来源：http://dali.tanke756.top/Article/details/gtmkukrduh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtgahiuapy.html

[Q84] 去除首尾空格
来源：http://dali.wangshuangyany.cn/Article/details/gtmugeeakg.html

SELECT TRIM(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtqoizrzok.html

[Q85] 数值取整
来源：http://dali.cucudq.cn/Article/details/gtowxljagh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ppjwa.cn/Article/details/gtstsjmyru.html

[Q86] 读取 JSON 字段
来源：http://dali.tanke756.top/Article/details/gtvkqeepou.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fengsongda.top/Article/details/gtavghtcmo.html

[Q87] JSON 字段做条件
来源：http://dali.pycfn.com/Article/details/gtejewqzjw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.redwolf501.top/Article/details/gtqqgnwtii.html

[Q88] 行转列（条件聚合）
来源：http://dali.yuxming.cn/Article/details/gttxsernpf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cucudq.cn/Article/details/gtmydeuxsq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtuiunztca.html

[Q89] 判断表是否存在
来源：http://dali.cheryme.top/Article/details/gtjixdadxx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yuanzhike.top/Article/details/gtsrkwqugy.html

[Q90] 生成序号列
来源：http://dali.vqdsnc.cn/Article/details/gtextyaveg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenzaomai.com/Article/details/gtfqthaljp.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtgvbmcifm.html

R. Bash 专题
来源：http://dali.jqgfzy.top/Article/details/gtsemcmvvn.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtpkokggik.html

[R01] shebang 与严格模式
来源：http://dali.mhx1999.top/Article/details/gtgkdbmjqt.html

#!/usr/bin/env bash
来源：http://dali.haohaochexian.top/Article/details/gtlcstflmu.html

set -euo pipefail
来源：http://dali.hfpthk.cn/Article/details/gtnzaflevh.html

[R02] 变量赋值与使用
来源：http://dali.zdqjudy.top/Article/details/gtlmpbshur.html

name="Tom"; echo "$name"
来源：http://dali.jlsjyb.cn/Article/details/gtwhcfwfec.html

[R03] 只读变量
来源：http://dali.yvedp.cn/Article/details/gtihbqxcdb.html

readonly PI=3.14
来源：http://dali.xziqi.cn/Article/details/gtfqxuopaf.html

[R04] 位置参数
来源：http://dali.yangfankeji.com/Article/details/gtoazrdirb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.bjfxy.top/Article/details/gtoqmgewtd.html

[R05] 参数默认值
来源：http://dali.meibo888.top/Article/details/gtlvlntzid.html

name="${1:-default}"
来源：http://dali.xinyue.icu/Article/details/gtdblihnpm.html

[R06] 判断命令是否存在
来源：http://dali.bjfxy.top/Article/details/gtrjokiylt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gtkkeuotah.html

[R07] if 判断文件
来源：http://dali.iojbl.cn/Article/details/gtqvbunkyk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtvyjyhecw.html

[R08] 数值比较
来源：http://dali.jiagoushi.top/Article/details/gtidfaxgbg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sysykeji.top/Article/details/gtihfykpct.html

[R09] 字符串比较
来源：http://dali.hnqzz.top/Article/details/gtajwaahsk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shzxlz.cn/Article/details/gtqjkqpnla.html

[R10] 正则匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxsfymuu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ybcxt.top/Article/details/gtxkerbfwr.html

[R11] case 多分支
来源：http://dali.sufxvd.cn/Article/details/gtgqpwnhqy.html

case "$1" in
来源：http://dali.feifeiyinyue.top/Article/details/gtgblhlfbv.html

start) echo "启动" ;;
来源：http://dali.ppjwa.cn/Article/details/gtvqhspucy.html

stop)  echo "停止" ;;
来源：http://dali.mhx1999.top/Article/details/gtbplelpbz.html

*)     echo "未知命令" ;;
来源：http://dali.sweek.top/Article/details/gtrcztosox.html

esac
来源：http://dali.xinyue.icu/Article/details/gtzoyhhnst.html

[R12] for 遍历文件
来源：http://dali.jqgfzy.top/Article/details/gtaeqfffxv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jiagoushi.top/Article/details/gtckdiszgs.html

[R13] for 计数循环
来源：http://dali.yj20258.top/Article/details/gtblnawhdq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gtyrxksjpt.html

[R14] C 风格 for
来源：http://dali.cheryme.top/Article/details/gtkunzjzbp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daria6918.cn/Article/details/gtfnwpdzjg.html

[R15] while 逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtwrstugzl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aizwys.cn/Article/details/gtnjlecxxu.html

[R16] until 等待条件
来源：http://dali.gaohongyu789.top/Article/details/gtyomnumhd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gtnptsaiwf.html

[R17] 数组定义与取值
来源：http://dali.sysykeji.top/Article/details/gtboskhmld.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.mhx1999.top/Article/details/gtebnmswqu.html

[R18] 遍历数组
来源：http://dali.mhx1999.top/Article/details/gtwrnuzsqd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daxiang520.top/Article/details/gtdfuyadho.html

[R19] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gtzgfhiyev.html

echo "${#arr[@]}"
来源：http://dali.tanke756.top/Article/details/gtcnnhyjqt.html

[R20] 关联数组（字典）
来源：http://dali.jinqigfzy.top/Article/details/gtroiqahdq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shuidangran.top/Article/details/gtlavjehld.html

[R21] 字符串长度
来源：http://dali.yj20258.top/Article/details/gtlqmwnypr.html

echo "${#s}"
来源：http://dali.fengsongda.top/Article/details/gtfhcfnidq.html

[R22] 截取子串
来源：http://dali.redwolf501.top/Article/details/gtpdvkmltx.html

echo "${s:0:5}"
来源：http://dali.yonumen.top/Article/details/gtoukgvnbe.html

[R23] 字符串替换
来源：http://dali.pycfn.com/Article/details/gtdfswgxin.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sysykeji.top/Article/details/gtnqijclkr.html

[R24] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gtbbqfgdrr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.mhx1999.top/Article/details/gtzksthiqq.html

[R25] 去后缀 / 去前缀
来源：http://dali.jlsjyb.cn/Article/details/gtnwqhbnmv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangdashe.top/Article/details/gtsqjkmvdv.html

[R26] 命令替换
来源：http://dali.pengpengdd.cyou/Article/details/gtfxvvlyas.html

now=$(date +%F); echo "$now"
来源：http://dali.sysykeji.top/Article/details/gtbohynaqh.html

[R27] 算术展开
来源：http://dali.tian-w.cn/Article/details/gtplaroiui.html

echo $((1 + 2 * 3))
来源：http://dali.vqdsnc.cn/Article/details/gtjrzvyecj.html

[R28] 浮点运算
来源：http://dali.jinqigufen.top/Article/details/gtcgojqcxi.html

echo "scale=2; 10/3" | bc
来源：http://dali.cucudq.cn/Article/details/gttavirxzu.html

[R29] 定义函数
来源：http://dali.yonumen.top/Article/details/gtjpnmbkov.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yongpay.top/Article/details/gtsltrlrdc.html

[R30] 函数返回状态码
来源：http://dali.jyoumei.cn/Article/details/gtcxtwslpd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.iojbl.cn/Article/details/gtpotfezev.html

[R31] 局部变量
来源：http://dali.yongpay.top/Article/details/gtmyzwanln.html

f() { local x=1; echo "$x"; }
来源：http://dali.fengsongda.top/Article/details/gtcbfrjqui.html

[R32] 参数个数校验
来源：http://dali.yj20258.top/Article/details/gtdhjktpmg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gtyekmiinp.html

[R33] 捕获错误并提示行号
来源：http://dali.jyoumei.cn/Article/details/gtorlchzuk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnqzz.top/Article/details/gthayvnlrq.html

[R34] 退出时清理
来源：http://dali.zhiwuduotai.top/Article/details/gtdrzqbbir.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hfpthk.cn/Article/details/gtardbmzvz.html

[R35] 后台执行并等待
来源：http://dali.hammf.cn/Article/details/gtiechosgx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yonumen.top/Article/details/gthddfctou.html

[R36] 并发执行多个任务
来源：http://dali.cucudq.cn/Article/details/gtoiejqdar.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.316326.xyz/Article/details/gtebeqohav.html

[R37] 把输出赋给变量
来源：http://dali.jlsjyb.cn/Article/details/gtpkxjaukn.html

files=$(ls -1)
来源：http://dali.gotoacloud.top/Article/details/gtshozwcat.html

[R38] 管道串联
来源：http://dali.guowangkeji.top/Article/details/gtxawyyhhp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuanzhike.top/Article/details/gtmtqkuozo.html

[R39] 重定向标准输出与错误
来源：http://dali.ehwqpu.com/Article/details/gtbzcqtgvu.html

cmd > out.log 2>&1
来源：http://dali.jqgfzy.top/Article/details/gtabvjauog.html

[R40] 追加写日志
来源：http://dali.ppjwa.cn/Article/details/gtcapaqibd.html

echo "log" >> out.log
来源：http://dali.xuanzx.com/Article/details/gtfgvdgcyv.html

[R41] 丢弃输出
来源：http://dali.birdmap.top/Article/details/gtixfjoxyt.html

cmd >/dev/null 2>&1
来源：http://dali.snrcjt.cn/Article/details/gtroxgckqe.html

[R42] 输入重定向
来源：http://dali.jqgfzy.top/Article/details/gtbzxtcmot.html

wc -l < a.txt
来源：http://dali.yuxming.cn/Article/details/gtmxsawoty.html

[R43] 按名字查找文件
来源：http://dali.shzxlz.cn/Article/details/gtfrbpgdbw.html

find . -name "*.log" -type f
来源：http://dali.yonumen.top/Article/details/gtafpqkqkm.html

[R44] 按修改时间查找
来源：http://dali.nanxuanxn.top/Article/details/gtgddzpgph.html

find . -mtime -7 -type f
来源：http://dali.xylfe.cn/Article/details/gtbeempxbf.html

[R45] 批量删除
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivhuiqay.html

find . -name "*.tmp" -delete
来源：http://dali.wangdashe.top/Article/details/gtvzkjhsvq.html

[R46] 递归替换文件内容
来源：http://dali.jinghuilouyu.cn/Article/details/gtxniwuuor.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.snrcjt.cn/Article/details/gtzmdzioty.html

[R47] sed 单行替换
来源：http://dali.havefunace.top/Article/details/gtkhlukjjq.html


<!-- 参考信息 -->