代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhoulong.xyz/Article/details/gtzbipvukz.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gtykqsjpmb.html

[Q02] 创建带外键的表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcyplalnj.html

CREATE TABLE orders (
来源：http://dali.ehwqpu.com/Article/details/gtnrpqntgd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yanxiufei.cn/Article/details/gtlznvyynn.html

user_id INT NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gtwjgzbxpi.html

amount DECIMAL(10, 2),
来源：http://dali.yj202588.top/Article/details/gtpqwnchhs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenlongwang.top/Article/details/gtuttesylt.html

);
来源：http://dali.nanxuanxn.top/Article/details/gtvlkmlejv.html

[Q03] 增加列
来源：http://dali.andypj.xyz/Article/details/gtjfihfgwm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.aizwys.cn/Article/details/gtiamaycsu.html

[Q04] 修改列类型
来源：http://dali.316326.xyz/Article/details/gtrbvzqivq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gtzniopski.html

[Q05] 重命名列
来源：http://dali.gaohongyu789.top/Article/details/gtxpojgotq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaybsurth.html

[Q06] 删除列
来源：http://dali.cdnleiting.top/Article/details/gtyhddzbtq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guannengcc.top/Article/details/gttetuwkpi.html

[Q07] 删除表
来源：http://dali.pengpengdd.cyou/Article/details/gtqotrgumy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodpqphas.html

[Q08] 创建普通索引
来源：http://dali.nwbrower.top/Article/details/gtfgbmfmga.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gtcdoeyjcj.html

[Q09] 创建唯一索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gttsvjxuci.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxinkj.top/Article/details/gtmvxybnrj.html

[Q10] 插入单行
来源：http://dali.gotoacloud.top/Article/details/gtitieldbi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.dashuyun.cn/Article/details/gthlmchtqh.html

[Q11] 一次插入多行
来源：http://dali.nanxuanxn.top/Article/details/gtzsxynqbg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gtsfswsnow.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangtech.top/Article/details/gtcyrtkzdk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.smart0.xyz/Article/details/gticlnxvki.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.quarkkingdee.top/Article/details/gtinsavfrb.html

[Q13] 忽略重复插入
来源：http://dali.yvedp.cn/Article/details/gtqoqduahg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gzhubu.top/Article/details/gttkeqdnxk.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj20258.top/Article/details/gtktngmfvv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hammf.cn/Article/details/gtigsnawsn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gtvqqoiofc.html

[Q15] 查询全部
来源：http://dali.mhx1999.top/Article/details/gtojxklsgu.html

SELECT * FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtwqcwhkiq.html

[Q16] 查询指定列
来源：http://dali.jqgfzy.top/Article/details/gtyswiohnf.html

SELECT id, name FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtbhuqzabx.html

[Q17] 条件查询
来源：http://dali.quarkkingdee.top/Article/details/gtwumlhfeb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.birdmap.top/Article/details/gtuliqedoa.html

[Q18] 模糊匹配
来源：http://dali.dianchejie.cn/Article/details/gtxsywgrnb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinghuilouyu.cn/Article/details/gtwgwxobgc.html

[Q19] 范围查询
来源：http://dali.smart0.xyz/Article/details/gtcpuuwfca.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shangyingyoupin.top/Article/details/gtkrhdtsma.html

[Q20] IN 列表
来源：http://dali.aizwys.cn/Article/details/gtcswdlypv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cucudq.cn/Article/details/gtylealkgg.html

[Q21] 空值判断
来源：http://dali.sweek.top/Article/details/gtfhxknrzy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sxryk.cn/Article/details/gtoaxnovwa.html

[Q22] 排序
来源：http://dali.sufxvd.cn/Article/details/gtwodmofqh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.daria6918.cn/Article/details/gtkyumfmfs.html

[Q23] 分页
来源：http://dali.hywenlv.cn/Article/details/gtbmfdmrzr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shangyingyoupin.top/Article/details/gtadwfzklh.html

[Q24] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gthhffqeij.html

SELECT DISTINCT city FROM users;
来源：http://dali.iojbl.cn/Article/details/gtoiwgspoj.html

[Q25] 只取前 N 条
来源：http://dali.tian-w.cn/Article/details/gtxxvrnrbx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shangyingyoupin.top/Article/details/gtlumxpofj.html

[Q26] 计数
来源：http://dali.guowangkeji.top/Article/details/gtokbgeqdp.html

SELECT COUNT(*) FROM users;
来源：http://dali.c1oappe.top/Article/details/gttechzlht.html

[Q27] 条件计数
来源：http://dali.dashuyun.cn/Article/details/gtqymewikj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtysreusiv.html

[Q28] 求和与平均
来源：http://dali.shzxlz.cn/Article/details/gtbuyolhbt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtqmdiwbdz.html

[Q29] 最大最小值
来源：http://dali.c1oappe.top/Article/details/gtidjtfpwu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gthzckrcxr.html

[Q30] 分组统计
来源：http://dali.ybcxt.top/Article/details/gtzuvambnc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gtijddrstn.html

[Q31] 分组后过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtkqhuqiig.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.aibaodan.cn/Article/details/gtrzbiovdw.html

[Q32] 分组拼接字符串
来源：http://dali.shuidangran.top/Article/details/gtqwghtgqj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gtsolzaotw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hfpthk.cn/Article/details/gtmspvvamx.html

[Q33] 多列分组
来源：http://dali.shuidangran.top/Article/details/gtdohnrbzu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhiwuduotai.top/Article/details/gtxjdjcqgq.html

[Q34] 每组取第一条
来源：http://dali.hywenlv.cn/Article/details/gtlzfuiyhk.html

SELECT * FROM (
来源：http://dali.kuanghao11.cn/Article/details/gtyjbeuqtv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sxryk.cn/Article/details/gtmcqxurcf.html

) t WHERE rn = 1;
来源：http://dali.sxryk.cn/Article/details/gtjbqoonfh.html

[Q35] 内连接
来源：http://dali.ydzc1.top/Article/details/gtrqyogrbx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gttrdohzhv.html

[Q36] 左连接
来源：http://dali.hfpthk.cn/Article/details/gtihqholnd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sysykeji.top/Article/details/gtkvejxnoq.html

[Q37] 右连接
来源：http://dali.andypj.xyz/Article/details/gtrqgrgcqe.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxjtlkvr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.bjfxy.top/Article/details/gtwqxqvfxh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.mhx1999.top/Article/details/gtdjjbysxr.html

[Q39] 自连接（查上下级）
来源：http://dali.wangshuangyany.cn/Article/details/gtufenjqwz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.haohaochexian.top/Article/details/gtldtwgyye.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.havefunace.top/Article/details/gtyxzsgmwu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhoulong.xyz/Article/details/gtdxznprcl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gzhubu.top/Article/details/gttdklugnf.html

[Q41] 多表连接
来源：http://dali.meibo888.top/Article/details/gtxmkzliki.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangdashe.top/Article/details/gtctxivqes.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hywenlv.cn/Article/details/gtoaizrpeh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.redwolf501.top/Article/details/gtnxzhirgs.html

[Q42] 连接条件附加过滤
来源：http://dali.ppjwa.cn/Article/details/gtwdiylgva.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shzxlz.cn/Article/details/gtpeuavffz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hysaishi.cn/Article/details/gtulxdfhto.html

[Q43] 标量子查询
来源：http://dali.shuidangran.top/Article/details/gtwoposawg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.tian-w.cn/Article/details/gtrkavdajb.html

[Q44] IN 子查询
来源：http://dali.hysaishi.cn/Article/details/gtikgehufo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tian-w.cn/Article/details/gtatxzmzml.html

[Q45] EXISTS 判断存在
来源：http://dali.tian-w.cn/Article/details/gtqsegxhiq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gtkohavihj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hnxiangtu.top/Article/details/gtddhyqggn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gtnohfeylu.html

[Q47] 与平均值比较
来源：http://dali.vqdsnc.cn/Article/details/gtvoiqhbfw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.birdmap.top/Article/details/gtvhndifkk.html

[Q48] CTE 公用表表达式
来源：http://dali.sysykeji.top/Article/details/gtfqbpqcah.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shuidangran.top/Article/details/gtjokxwamx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgfzy.top/Article/details/gteshnsmkn.html

[Q49] 更新单行
来源：http://dali.gogol.net.cn/Article/details/gtvbpmfeea.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.vqdsnc.cn/Article/details/gtocqdsimx.html

[Q50] 批量更新
来源：http://dali.quarkkingdee.top/Article/details/gtssnlktuq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gtphtxsstx.html

[Q51] 用子查询更新
来源：http://dali.meibo888.top/Article/details/gtmjxeuhjh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jiagoushi.top/Article/details/gtrpvffmkq.html

[Q52] 删除指定行
来源：http://dali.andypj.xyz/Article/details/gtcipptzie.html

DELETE FROM users WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gtqkrlmwyb.html

[Q53] 按条件删除
来源：http://dali.sweek.top/Article/details/gtayzyymbg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhengqikj.top/Article/details/gtkrmqqlud.html

[Q54] 清空表
来源：http://dali.feifeiyinyue.top/Article/details/gtwkkcnfbm.html

TRUNCATE TABLE logs;
来源：http://dali.yuanzhike.top/Article/details/gtsjerfvbl.html

[Q55] 排名（并列占位）
来源：http://dali.aizwys.cn/Article/details/gtbscodhps.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hywenlv.cn/Article/details/gtpvyjdlso.html

[Q56] 密集排名（并列不占位）
来源：http://dali.9152youxi.cn/Article/details/gttevxpocy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj202588.top/Article/details/gthdcrzasa.html

[Q57] 行号
来源：http://dali.yj20258.top/Article/details/gtoafoxhjt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnqzz.top/Article/details/gtsmpcwjma.html

[Q58] 累计求和
来源：http://dali.nanxinkj.top/Article/details/gtiftnxxuc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj202588.top/Article/details/gtfnllqckp.html

[Q59] 分组内累计
来源：http://dali.haohaochexian.top/Article/details/gtonuqervg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtxwsjjzyf.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj20258.top/Article/details/gttfyubzod.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.kuanghao11.cn/Article/details/gtfoxufvvt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtwcrohbxn.html

[Q61] 移动平均
来源：http://dali.yuxming.cn/Article/details/gtugjdzvbl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtypmkifti.html

[Q62] 分组占比
来源：http://dali.jqgufenzy.top/Article/details/gtydlqxrnx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gtmbvorsaq.html

[Q63] 开启事务
来源：http://dali.shzxlz.cn/Article/details/gteilraogl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ydzc1.top/Article/details/gtcsmuioeb.html

[Q64] 提交事务
来源：http://dali.snrcjt.cn/Article/details/gtygzgddtq.html

COMMIT;
来源：http://dali.nanxuanxn.top/Article/details/gtpabfogux.html

[Q65] 回滚事务
来源：http://dali.hywenlv.cn/Article/details/gtxovviers.html

ROLLBACK;
来源：http://dali.svipenyu.cn/Article/details/gtftcmyaqt.html

[Q66] 行锁查询
来源：http://dali.tian-w.cn/Article/details/gtymzbbjde.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.redwolf501.top/Article/details/gtykycrqpz.html

[Q67] 设置隔离级别
来源：http://dali.316326.xyz/Article/details/gtwxeaqfkn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.fzhhl.top/Article/details/gtmakzvhas.html

[Q68] 保存点
来源：http://dali.jqgfzy.top/Article/details/gtssbvifhd.html

SAVEPOINT sp1;
来源：http://dali.9152youxi.cn/Article/details/gtdrbohjnb.html

ROLLBACK TO sp1;
来源：http://dali.zhongyouzk.top/Article/details/gtemhuepmm.html

[Q69] 查看执行计划
来源：http://dali.svipenyu.cn/Article/details/gtvusasabh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqwdqywv.html

[Q70] 更新统计信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbuorjxzs.html

ANALYZE TABLE users;
来源：http://dali.yangfankeji.com/Article/details/gtocxaxkqt.html

[Q71] 查看建表语句
来源：http://dali.birdmap.top/Article/details/gtemesqhdz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.quarkkingdee.top/Article/details/gtfodrhczf.html

[Q72] 查看索引
来源：http://dali.yj20258.top/Article/details/gtqoiqtplk.html

SHOW INDEX FROM users;
来源：http://dali.fzhhl.top/Article/details/gtpwlvofhv.html

[Q73] 查看表状态
来源：http://dali.havefunace.top/Article/details/gtzdggynac.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhoulong.xyz/Article/details/gtgfdqnies.html

[Q74] 强制使用索引
来源：http://dali.gogol.net.cn/Article/details/gtubhkbgfs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ivvv.top/Article/details/gtvegdgesq.html

[Q75] 日期格式化
来源：http://dali.chenzaomai.com/Article/details/gtvzcwertb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtzwasejgb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shangyingyoupin.top/Article/details/gtokwvlscm.html

[Q76] 按天统计
来源：http://dali.ybcxt.top/Article/details/gtykmfchkn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hongshengwenyu.top/Article/details/gtmrduepmo.html

[Q77] 时间加减
来源：http://dali.sweek.top/Article/details/gtvjpmqfrc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcwnopmx.html

[Q78] 当前时间
来源：http://dali.c1oappe.top/Article/details/gtisirfzwj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.haohaochexian.top/Article/details/gtmthvhqkn.html

[Q79] 字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtteeokqia.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sxryk.cn/Article/details/gtddhhtuns.html

[Q80] 字符串截取
来源：http://dali.ivvv.top/Article/details/gthiriltpm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtttaarcge.html

[Q81] 字符串替换
来源：http://dali.cucudq.cn/Article/details/gtnqxiftlp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ybcxt.top/Article/details/gtgwmsrenf.html

[Q82] 字符长度与字节长度
来源：http://dali.c1oappe.top/Article/details/gtglndtpzq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtcelopqyh.html

[Q83] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gtjdfdqlpa.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtxiyxsqbc.html

[Q84] 去除首尾空格
来源：http://dali.xuanzx.com/Article/details/gtyvqxrpsn.html

SELECT TRIM(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtkzykwmys.html

[Q85] 数值取整
来源：http://dali.aibaodan.cn/Article/details/gtogifnasy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.vqdsnc.cn/Article/details/gtishtemaw.html

[Q86] 读取 JSON 字段
来源：http://dali.jlsjyb.cn/Article/details/gtcqtlkckl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jyoumei.cn/Article/details/gtweywvavn.html

[Q87] JSON 字段做条件
来源：http://dali.xinyue.icu/Article/details/gteqhenuwq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cucudq.cn/Article/details/gthedkasnx.html

[Q88] 行转列（条件聚合）
来源：http://dali.sxryk.cn/Article/details/gtxebtjvmr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenjidiqi.icu/Article/details/gtjrpwpgtp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gzhubu.top/Article/details/gtsrcbpjas.html

[Q89] 判断表是否存在
来源：http://dali.yj20258.top/Article/details/gtbhcfkuub.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yanxiufei.cn/Article/details/gtulayzkbi.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gtzxkegftq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.meibo888.top/Article/details/gteyyvunli.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtrvorwwcv.html

R. Bash 专题
来源：http://dali.jqgfzy.top/Article/details/gtbqfpechu.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtcxitlkbp.html

[R01] shebang 与严格模式
来源：http://dali.svipenyu.cn/Article/details/gtkerxkmqp.html

#!/usr/bin/env bash
来源：http://dali.shuidangran.top/Article/details/gtnogvixgm.html

set -euo pipefail
来源：http://dali.havefunace.top/Article/details/gtoxbelloi.html

[R02] 变量赋值与使用
来源：http://dali.xuanzx.com/Article/details/gtytupozqw.html

name="Tom"; echo "$name"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzokhqev.html

[R03] 只读变量
来源：http://dali.yonumen.top/Article/details/gtoadquebf.html

readonly PI=3.14
来源：http://dali.cashguo.top/Article/details/gtnsjtyguh.html

[R04] 位置参数
来源：http://dali.zhengqikj.top/Article/details/gtoniwnnqq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.0kj1m.cn/Article/details/gtgfhqxqtm.html

[R05] 参数默认值
来源：http://dali.ybcxt.top/Article/details/gtefdkxrmh.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gtwhkvhjbv.html

[R06] 判断命令是否存在
来源：http://dali.jianghu66.top/Article/details/gtvwxhhplj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gtnwzxymyl.html

[R07] if 判断文件
来源：http://dali.nanxinkj.top/Article/details/gtrotcxrrm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cheryme.top/Article/details/gtxrvukprd.html

[R08] 数值比较
来源：http://dali.iojbl.cn/Article/details/gtusmzmrfl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtyougfeey.html

[R09] 字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gtrgebhekb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtxxbumlds.html

[R10] 正则匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtyihodjmb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hfpthk.cn/Article/details/gtckbmumri.html

[R11] case 多分支
来源：http://dali.0kj1m.cn/Article/details/gtlutpkblj.html

case "$1" in
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncvfdxax.html

start) echo "启动" ;;
来源：http://dali.sweek.top/Article/details/gtlixsbugy.html

stop)  echo "停止" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtvozlusug.html

*)     echo "未知命令" ;;
来源：http://dali.guowangkeji.top/Article/details/gtspizkoej.html

esac
来源：http://dali.0kj1m.cn/Article/details/gtwsjhmshk.html

[R12] for 遍历文件
来源：http://dali.dianchejie.cn/Article/details/gtishmzwga.html

for f in *.txt; do echo "$f"; done
来源：http://dali.meibo888.top/Article/details/gtptnjvfbt.html

[R13] for 计数循环
来源：http://dali.tianlin.xyz/Article/details/gtgvoqqaeq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cucudq.cn/Article/details/gtckelgocf.html

[R14] C 风格 for
来源：http://dali.daxiang520.top/Article/details/gtwatiwxto.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygbtqowo.html

[R15] while 逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtzmrgaptw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hammf.cn/Article/details/gtnbbglkhl.html

[R16] until 等待条件
来源：http://dali.fzhhl.top/Article/details/gtawtvyxzt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nwbrower.top/Article/details/gtipkxmkzg.html

[R17] 数组定义与取值
来源：http://dali.shuidangran.top/Article/details/gthcdtytri.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtkaiovwiv.html

[R18] 遍历数组
来源：http://dali.cdnleiting.top/Article/details/gtmbavsspt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj20258888.top/Article/details/gtyftmfyri.html

[R19] 数组长度
来源：http://dali.shuidangran.top/Article/details/gtpastzijw.html

echo "${#arr[@]}"
来源：http://dali.jlsjyb.cn/Article/details/gthxlfvudr.html

[R20] 关联数组（字典）
来源：http://dali.9152youxi.cn/Article/details/gtdcsazzwt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.bjfxy.top/Article/details/gtpfznnegr.html

[R21] 字符串长度
来源：http://dali.guannengcc.top/Article/details/gtbsrpzvnl.html

echo "${#s}"
来源：http://dali.yonumen.top/Article/details/gtmiqgsfsq.html

[R22] 截取子串
来源：http://dali.birdmap.top/Article/details/gtlpuucoql.html

echo "${s:0:5}"
来源：http://dali.gzhubu.top/Article/details/gtulwzepuq.html

[R23] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gtfnxraifg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hysaishi.cn/Article/details/gtvqdfykdj.html

[R24] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gtlewqaazp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ehwqpu.com/Article/details/gteamifjfd.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhiwuduotai.top/Article/details/gtzxbwvecq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pycfn.com/Article/details/gtfipnluhu.html

[R26] 命令替换
来源：http://dali.fengsongda.top/Article/details/gtemredgzj.html

now=$(date +%F); echo "$now"
来源：http://dali.zhengqikj.top/Article/details/gtavpjkbnf.html

[R27] 算术展开
来源：http://dali.zhengqikj.top/Article/details/gtonsybomr.html

echo $((1 + 2 * 3))
来源：http://dali.guowangkeji.top/Article/details/gtacvnepcp.html

[R28] 浮点运算
来源：http://dali.jqgfzy.top/Article/details/gthfxenump.html

echo "scale=2; 10/3" | bc
来源：http://dali.yonumen.top/Article/details/gtbzxvlhqi.html

[R29] 定义函数
来源：http://dali.yanxiufei.cn/Article/details/gtjnylcfzw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuanzx.com/Article/details/gtwfbmxqmw.html

[R30] 函数返回状态码
来源：http://dali.smart0.xyz/Article/details/gtmboxqiyf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.kuanghao11.cn/Article/details/gteripnrxl.html

[R31] 局部变量
来源：http://dali.redwolf501.top/Article/details/gtqxccjlcf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhixingplan.top/Article/details/gtluiniimq.html

[R32] 参数个数校验
来源：http://dali.wangdashe.top/Article/details/gtmurqjmsq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yvedp.cn/Article/details/gtyetzvrud.html

[R33] 捕获错误并提示行号
来源：http://dali.hfpthk.cn/Article/details/gtgwpxglbc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tian-w.cn/Article/details/gtuxhkoikg.html

[R34] 退出时清理
来源：http://dali.yj20258.top/Article/details/gtjavtecyb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gtxrnjlkdb.html

[R35] 后台执行并等待
来源：http://dali.iojbl.cn/Article/details/gtcubyyjgt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pengpengdd.cyou/Article/details/gtvyagzpql.html

[R36] 并发执行多个任务
来源：http://dali.zhoulong.xyz/Article/details/gtjbqydlae.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuanzhike.top/Article/details/gtobucixyb.html

[R37] 把输出赋给变量
来源：http://dali.316326.xyz/Article/details/gtbpihtsxr.html

files=$(ls -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivjfglfd.html

[R38] 管道串联
来源：http://dali.xziqi.cn/Article/details/gtoczrowam.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tanke756.top/Article/details/gtruocrbrk.html

[R39] 重定向标准输出与错误
来源：http://dali.cucudq.cn/Article/details/gtgrzvfjje.html

cmd > out.log 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gtfatypbrp.html

[R40] 追加写日志
来源：http://dali.vqdsnc.cn/Article/details/gtefyhxhug.html

echo "log" >> out.log
来源：http://dali.daria6918.cn/Article/details/gtclzzdgcv.html

[R41] 丢弃输出
来源：http://dali.zycfv.cn/Article/details/gtzmayhwlw.html

cmd >/dev/null 2>&1
来源：http://dali.sxryk.cn/Article/details/gtijxoqijv.html

[R42] 输入重定向
来源：http://dali.yanxiufei.cn/Article/details/gtrnxbyhxe.html

wc -l < a.txt
来源：http://dali.yvedp.cn/Article/details/gtdadlyary.html

[R43] 按名字查找文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpnxohex.html

find . -name "*.log" -type f
来源：http://dali.cdnleiting.top/Article/details/gtzowwfsbg.html

[R44] 按修改时间查找
来源：http://dali.gzhubu.top/Article/details/gtxjbtkokb.html

find . -mtime -7 -type f
来源：http://dali.shangyingyoupin.top/Article/details/gtiexpgcgl.html

[R45] 批量删除
来源：http://dali.guannengcc.top/Article/details/gtqynfwxkl.html

find . -name "*.tmp" -delete
来源：http://dali.ydzc1.top/Article/details/gtyyveqzzz.html

[R46] 递归替换文件内容
来源：http://dali.jinqigufen.top/Article/details/gteotnqqtz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.0kj1m.cn/Article/details/gtfmfzwdbv.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtalyuacvp.html


<!-- 参考信息 -->