代发 wailian999

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangdashe.top/Article/details/gtkpljmuiq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinqigfzy.top/Article/details/gtrahsulda.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.mhx1999.top/Article/details/gtrqyylccq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhengqikj.top/Article/details/gtxkvfypov.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtrmnsyuhg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.quarkkingdee.top/Article/details/gtzscdmcea.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtrvpcfknr.html

[Q01] 创建表
来源：http://dali.birdmap.top/Article/details/gtxyebvpkd.html

CREATE TABLE users (
来源：http://dali.yvedp.cn/Article/details/gtdbamcbze.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aibaodan.cn/Article/details/gtieuzadlv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gtgsyfuvix.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhixingplan.top/Article/details/gtbvklheeb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yangfankeji.com/Article/details/gtyfilnpxj.html

);
来源：http://dali.svipenyu.cn/Article/details/gtnkodiadm.html

[Q02] 创建带外键的表
来源：http://dali.daria6918.cn/Article/details/gttyhhhlam.html

CREATE TABLE orders (
来源：http://dali.aibaodan.cn/Article/details/gtixskpqyv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.c1oappe.top/Article/details/gtoqnwhkix.html

user_id INT NOT NULL,
来源：http://dali.316326.xyz/Article/details/gtgklwgqdl.html

amount DECIMAL(10, 2),
来源：http://dali.hnxiangtu.top/Article/details/gtgzearfmy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.kuanghao11.cn/Article/details/gtufrabqnw.html

);
来源：http://dali.birdmap.top/Article/details/gttnaknypa.html

[Q03] 增加列
来源：http://dali.hnxiangtu.top/Article/details/gtniztjofx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gaohongyu789.top/Article/details/gtiihqzqfj.html

[Q04] 修改列类型
来源：http://dali.zdqjudy.top/Article/details/gtgunmzvnu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhljqdod.html

[Q05] 重命名列
来源：http://dali.jlsjyb.cn/Article/details/gtnofdqfvx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.mhx1999.top/Article/details/gtnwzqjkon.html

[Q06] 删除列
来源：http://dali.yonumen.top/Article/details/gtgrwbhqsa.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jyoumei.cn/Article/details/gtmljxehhw.html

[Q07] 删除表
来源：http://dali.guowangkeji.top/Article/details/gtmmsyiklb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtosybokrg.html

[Q08] 创建普通索引
来源：http://dali.chenjidiqi.icu/Article/details/gtxmicscev.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hywenlv.cn/Article/details/gtbqzzfyyj.html

[Q09] 创建唯一索引
来源：http://dali.shzxlz.cn/Article/details/gthbwszkns.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj20258888.top/Article/details/gtgpflvevl.html

[Q10] 插入单行
来源：http://dali.wangshuangyany.cn/Article/details/gtgzjnivzz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ivvv.top/Article/details/gtyokkshna.html

[Q11] 一次插入多行
来源：http://dali.zdqjudy.top/Article/details/gttbrwxyko.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gtvlkpxtbt.html

[Q12] 插入后取自增 ID
来源：http://dali.feifeiyinyue.top/Article/details/gtgmvbxvxw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhixingplan.top/Article/details/gtiwslgrgw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwliprvin.html

[Q13] 忽略重复插入
来源：http://dali.shuidangran.top/Article/details/gtqzylerwi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirtzckbk.html

[Q14] 存在则更新（upsert）
来源：http://dali.jlsjyb.cn/Article/details/gtnbllviqs.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.9152youxi.cn/Article/details/gthaieihud.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.kuanghao11.cn/Article/details/gthpzwxkbd.html

[Q15] 查询全部
来源：http://dali.ehwqpu.com/Article/details/gtanqujeea.html

SELECT * FROM users;
来源：http://dali.zycfv.cn/Article/details/gthnsdoyme.html

[Q16] 查询指定列
来源：http://dali.gotoacloud.top/Article/details/gtdqgwdpiy.html

SELECT id, name FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtgfpifrjn.html

[Q17] 条件查询
来源：http://dali.hfpthk.cn/Article/details/gtqxnagcjl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cashguo.top/Article/details/gtvlkilubx.html

[Q18] 模糊匹配
来源：http://dali.hysaishi.cn/Article/details/gtykkufpww.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tanke756.top/Article/details/gtmqjsfpua.html

[Q19] 范围查询
来源：http://dali.wangshuangyany.cn/Article/details/gtcxdsajrn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ivvv.top/Article/details/gtzmivyvep.html

[Q20] IN 列表
来源：http://dali.yangfankeji.com/Article/details/gteyyhikbk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfswsjtn.html

[Q21] 空值判断
来源：http://dali.pycfn.com/Article/details/gtjrfkctql.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shangyingyoupin.top/Article/details/gtepyzwqhr.html

[Q22] 排序
来源：http://dali.sweek.top/Article/details/gtmkeqwjup.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hfpthk.cn/Article/details/gttqlzblru.html

[Q23] 分页
来源：http://dali.yvedp.cn/Article/details/gtwvdeiyow.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.feifeiyinyue.top/Article/details/gtsintthmu.html

[Q24] 去重
来源：http://dali.tanke756.top/Article/details/gtothrekeu.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj202588.top/Article/details/gtvtgjxmkl.html

[Q25] 只取前 N 条
来源：http://dali.birdmap.top/Article/details/gtpbzztmxx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zdqjudy.top/Article/details/gtsqajwsrb.html

[Q26] 计数
来源：http://dali.hfpthk.cn/Article/details/gthcsliccr.html

SELECT COUNT(*) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtrdcewdib.html

[Q27] 条件计数
来源：http://dali.cashguo.top/Article/details/gtjhrgsjrt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtuidmrtjw.html

[Q28] 求和与平均
来源：http://dali.xziqi.cn/Article/details/gtkjaonlsy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtskequzxl.html

[Q29] 最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gtgldswuqr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtomtiarvb.html

[Q30] 分组统计
来源：http://dali.xylfe.cn/Article/details/gtntwshdhs.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtaorpewbx.html

[Q31] 分组后过滤
来源：http://dali.pycfn.com/Article/details/gtuyzwopnh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jianghu66.top/Article/details/gtiymdfpna.html

[Q32] 分组拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtfmchovto.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gtjitmayen.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.quarkkingdee.top/Article/details/gtsqfnhryf.html

[Q33] 多列分组
来源：http://dali.hongshengwenyu.top/Article/details/gtrmqilxlg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxjbvdqpo.html

[Q34] 每组取第一条
来源：http://dali.zhongyouzk.top/Article/details/gthrpyqxcr.html

SELECT * FROM (
来源：http://dali.shuidangran.top/Article/details/gtiswiabxu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.havefunace.top/Article/details/gthkbfohjt.html

) t WHERE rn = 1;
来源：http://dali.fzhhl.top/Article/details/gtrrsevsdc.html

[Q35] 内连接
来源：http://dali.quarkkingdee.top/Article/details/gtnixizgwj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gtbicotcac.html

[Q36] 左连接
来源：http://dali.cdnleiting.top/Article/details/gtcxcxehvn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdneeyvz.html

[Q37] 右连接
来源：http://dali.zhengqikj.top/Article/details/gtbkqeehrs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnqzz.top/Article/details/gtsobtzzur.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnxiangtu.top/Article/details/gtkshpldxq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.dashuyun.cn/Article/details/gtitbuhydx.html

[Q39] 自连接（查上下级）
来源：http://dali.andypj.xyz/Article/details/gthrlxgupr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuanzhike.top/Article/details/gtvikwcbme.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ppjwa.cn/Article/details/gtsnmzvkqx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yvedp.cn/Article/details/gtocrhpmvv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yj20258.top/Article/details/gtkjripdea.html

[Q41] 多表连接
来源：http://dali.yangfankeji.com/Article/details/gtcqdrygps.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guowangkeji.top/Article/details/gtufvxhigo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yuanzhike.top/Article/details/gtqmftdppn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hnqzz.top/Article/details/gtnitscdfa.html

[Q42] 连接条件附加过滤
来源：http://dali.zycfv.cn/Article/details/gtrasgedeg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tanke756.top/Article/details/gtacsezyfu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjgvxzotj.html

[Q43] 标量子查询
来源：http://dali.shzxlz.cn/Article/details/gttutvugtb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dashuyun.cn/Article/details/gtteyimuet.html

[Q44] IN 子查询
来源：http://dali.zhongyouzk.top/Article/details/gtielgwzjz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ppjwa.cn/Article/details/gtsfktkqqg.html

[Q45] EXISTS 判断存在
来源：http://dali.quarkkingdee.top/Article/details/gtgmcqwvom.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gtweunaqel.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgfzy.top/Article/details/gtsniwsffy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ppjwa.cn/Article/details/gtllfpzjiw.html

[Q47] 与平均值比较
来源：http://dali.hongshengwenyu.top/Article/details/gtsobuipys.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinqigfzy.top/Article/details/gtotubjmwk.html

[Q48] CTE 公用表表达式
来源：http://dali.mhx1999.top/Article/details/gtalgqcnic.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhoulong.xyz/Article/details/gtcgudhqbb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.bjfxy.top/Article/details/gtjwugjtof.html

[Q49] 更新单行
来源：http://dali.guannengcc.top/Article/details/gtpqrsfuef.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gtmeyqrxqj.html

[Q50] 批量更新
来源：http://dali.ybcxt.top/Article/details/gtgotxdqhz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ydzc1.top/Article/details/gtpufxghct.html

[Q51] 用子查询更新
来源：http://dali.zycfv.cn/Article/details/gtgiilrlca.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ybcxt.top/Article/details/gteflcixip.html

[Q52] 删除指定行
来源：http://dali.xylfe.cn/Article/details/gtotqqszkc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.bjfxy.top/Article/details/gtcgaiyolg.html

[Q53] 按条件删除
来源：http://dali.guowangkeji.top/Article/details/gtwqcemlmn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ybcxt.top/Article/details/gtagvwhber.html

[Q54] 清空表
来源：http://dali.xylfe.cn/Article/details/gtwdlmstvr.html

TRUNCATE TABLE logs;
来源：http://dali.yongpay.top/Article/details/gtseibazmd.html

[Q55] 排名（并列占位）
来源：http://dali.hongshengwenyu.top/Article/details/gtwsabmdbo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tanke756.top/Article/details/gtkzjotngi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guowangkeji.top/Article/details/gtnskyrzqd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.snrcjt.cn/Article/details/gtrvcjiaou.html

[Q57] 行号
来源：http://dali.316326.xyz/Article/details/gtjdiqeakq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtmjyumoms.html

[Q58] 累计求和
来源：http://dali.haohaochexian.top/Article/details/gtqbejxrjj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtdbbyuvli.html

[Q59] 分组内累计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvphjmmxw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpjiwjyb.html

[Q60] 取上一行 / 下一行
来源：http://dali.jlsjyb.cn/Article/details/gtajwdbcxs.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.wangdashe.top/Article/details/gtmriyzlgn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtwfblaejq.html

[Q61] 移动平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gttsalqevj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ivvv.top/Article/details/gtcemursqr.html

[Q62] 分组占比
来源：http://dali.ppjwa.cn/Article/details/gtmhvrbyrq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gtsnlihayk.html

[Q63] 开启事务
来源：http://dali.jinghuilouyu.cn/Article/details/gtghrfllsw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sysykeji.top/Article/details/gtnbrowcnt.html

[Q64] 提交事务
来源：http://dali.gogol.net.cn/Article/details/gthxnvqxhu.html

COMMIT;
来源：http://dali.zycfv.cn/Article/details/gtylvtyrfi.html

[Q65] 回滚事务
来源：http://dali.aizwys.cn/Article/details/gtntghcuao.html

ROLLBACK;
来源：http://dali.shzxlz.cn/Article/details/gtmamqjgbn.html

[Q66] 行锁查询
来源：http://dali.sysykeji.top/Article/details/gtwxbalcei.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkilnjrk.html

[Q67] 设置隔离级别
来源：http://dali.sysykeji.top/Article/details/gttpvmvjbx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aizwys.cn/Article/details/gtowkjsbxy.html

[Q68] 保存点
来源：http://dali.jinqigfzy.top/Article/details/gtyxrbkuro.html

SAVEPOINT sp1;
来源：http://dali.hywenlv.cn/Article/details/gtktuwbqkz.html

ROLLBACK TO sp1;
来源：http://dali.wangdashe.top/Article/details/gtagizoxpk.html

[Q69] 查看执行计划
来源：http://dali.yuxming.cn/Article/details/gtlchmfdik.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.0kj1m.cn/Article/details/gthmcqkjnd.html

[Q70] 更新统计信息
来源：http://dali.daria6918.cn/Article/details/gtaigllbwy.html

ANALYZE TABLE users;
来源：http://dali.cucudq.cn/Article/details/gtbqcmxdsh.html

[Q71] 查看建表语句
来源：http://dali.wangshuangyany.cn/Article/details/gtdcdcskcz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.havefunace.top/Article/details/gtnsfzkwgk.html

[Q72] 查看索引
来源：http://dali.kuanghao11.cn/Article/details/gtuflnhxaq.html

SHOW INDEX FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtxbhpsszt.html

[Q73] 查看表状态
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnihbowb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.iojbl.cn/Article/details/gtvyankybv.html

[Q74] 强制使用索引
来源：http://dali.fengsongda.top/Article/details/gtktfqbsec.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cdnleiting.top/Article/details/gtmbjqbfbt.html

[Q75] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gthieqcxqx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtpcdmrhwy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sysykeji.top/Article/details/gtgsrvhimo.html

[Q76] 按天统计
来源：http://dali.ivvv.top/Article/details/gtgsrivgzi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ydzc1.top/Article/details/gttphzymce.html

[Q77] 时间加减
来源：http://dali.bjfxy.top/Article/details/gtxhhixtyx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zdqjudy.top/Article/details/gtjqfhomzw.html

[Q78] 当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gtucidayjh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cqqwz.cn/Article/details/gtbbbehefq.html

[Q79] 字符串拼接
来源：http://dali.yangfankeji.com/Article/details/gtqpesftfl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gzhubu.top/Article/details/gtvaenxdpg.html

[Q80] 字符串截取
来源：http://dali.smart0.xyz/Article/details/gtdyhcjxbc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtxryudjfl.html

[Q81] 字符串替换
来源：http://dali.shangyingyoupin.top/Article/details/gtilhkdhck.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hammf.cn/Article/details/gtimeurtln.html

[Q82] 字符长度与字节长度
来源：http://dali.hywenlv.cn/Article/details/gtmesqyiqm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtwnejriwd.html

[Q83] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtnddjhmlq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtqjoejwgc.html

[Q84] 去除首尾空格
来源：http://dali.sweek.top/Article/details/gtshqnjiew.html

SELECT TRIM(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtkwktvnmi.html

[Q85] 数值取整
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyakcfbkw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.meibo888.top/Article/details/gtnwbudznz.html

[Q86] 读取 JSON 字段
来源：http://dali.xziqi.cn/Article/details/gtzrdsmxpz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gzhubu.top/Article/details/gtwnasedae.html

[Q87] JSON 字段做条件
来源：http://dali.aizwys.cn/Article/details/gtwoyuzevp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shuidangran.top/Article/details/gtojqhwthz.html

[Q88] 行转列（条件聚合）
来源：http://dali.xziqi.cn/Article/details/gtujabisvg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shzxlz.cn/Article/details/gtycvrczbg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daxiang520.top/Article/details/gtmuieggxd.html

[Q89] 判断表是否存在
来源：http://dali.hammf.cn/Article/details/gtsxdkkrxd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gtdtwsfttf.html

[Q90] 生成序号列
来源：http://dali.quarkkingdee.top/Article/details/gtojgvrjhq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sufxvd.cn/Article/details/gtldedqivm.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtoaqlkofw.html

R. Bash 专题
来源：http://dali.0kj1m.cn/Article/details/gtelfwiaae.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtvjssaihj.html

[R01] shebang 与严格模式
来源：http://dali.yuxming.cn/Article/details/gtmkkicsuv.html

#!/usr/bin/env bash
来源：http://dali.zycfv.cn/Article/details/gtjlaixjao.html

set -euo pipefail
来源：http://dali.quarkkingdee.top/Article/details/gtupeoaryf.html

[R02] 变量赋值与使用
来源：http://dali.yvedp.cn/Article/details/gtcfzgsjkl.html

name="Tom"; echo "$name"
来源：http://dali.xylfe.cn/Article/details/gtaslnpmln.html

[R03] 只读变量
来源：http://dali.yanxiufei.cn/Article/details/gtdawsaqnh.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gtaxnxambd.html

[R04] 位置参数
来源：http://dali.shangyingyoupin.top/Article/details/gttgdkoxnm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxinkj.top/Article/details/gtscnmzviq.html

[R05] 参数默认值
来源：http://dali.ybcxt.top/Article/details/gtgthysqol.html

name="${1:-default}"
来源：http://dali.yueranfly.top/Article/details/gtxulihrxn.html

[R06] 判断命令是否存在
来源：http://dali.zhixingplan.top/Article/details/gtqkmqiubk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daxiang520.top/Article/details/gtgciurxjn.html

[R07] if 判断文件
来源：http://dali.yvedp.cn/Article/details/gtzaqppdky.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jyoumei.cn/Article/details/gtdvjavbzv.html

[R08] 数值比较
来源：http://dali.birdmap.top/Article/details/gttjeuzmnw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj202588.top/Article/details/gtjvqbynqp.html

[R09] 字符串比较
来源：http://dali.sweek.top/Article/details/gtwejeaocz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkhjusbu.html

[R10] 正则匹配
来源：http://dali.sufxvd.cn/Article/details/gtfhyvlxnb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.redwolf501.top/Article/details/gtnyqkmszg.html

[R11] case 多分支
来源：http://dali.yongpay.top/Article/details/gtjhytourg.html

case "$1" in
来源：http://dali.svipenyu.cn/Article/details/gtjpphnlfy.html

start) echo "启动" ;;
来源：http://dali.yvedp.cn/Article/details/gtnwhybwfy.html

stop)  echo "停止" ;;
来源：http://dali.hfpthk.cn/Article/details/gtgfirdkoe.html

*)     echo "未知命令" ;;
来源：http://dali.tian-w.cn/Article/details/gtybnuovpi.html

esac
来源：http://dali.gotoacloud.top/Article/details/gtsfoqitsq.html

[R12] for 遍历文件
来源：http://dali.chenjidiqi.icu/Article/details/gtbixzuboy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.daxiang520.top/Article/details/gtbaiqufea.html

[R13] for 计数循环
来源：http://dali.gogol.net.cn/Article/details/gtyvjxqguu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gtymqqifwe.html

[R14] C 风格 for
来源：http://dali.nanxinkj.top/Article/details/gtgscabgyt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.smart0.xyz/Article/details/gtfatcqina.html

[R15] while 逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtzsavcdta.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xylfe.cn/Article/details/gtpzepkixy.html

[R16] until 等待条件
来源：http://dali.daxiang520.top/Article/details/gtrrwseqop.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cheryme.top/Article/details/gtqwlxxfxi.html

[R17] 数组定义与取值
来源：http://dali.sysykeji.top/Article/details/gteknhsawv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhengqikj.top/Article/details/gtkmkpjtds.html

[R18] 遍历数组
来源：http://dali.zdqjudy.top/Article/details/gtdqjikyny.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.andypj.xyz/Article/details/gtftqioymr.html

[R19] 数组长度
来源：http://dali.kuanghao11.cn/Article/details/gttzgdhymm.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtipktvmog.html

[R20] 关联数组（字典）
来源：http://dali.haohaochexian.top/Article/details/gtpmrjrbmj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ivvv.top/Article/details/gtgyokzkge.html

[R21] 字符串长度
来源：http://dali.yongpay.top/Article/details/gtddbbswew.html

echo "${#s}"
来源：http://dali.snrcjt.cn/Article/details/gtmffgqdzl.html

[R22] 截取子串
来源：http://dali.zhengqikj.top/Article/details/gtlgfvsjfb.html

echo "${s:0:5}"
来源：http://dali.pengpengdd.cyou/Article/details/gtzqagamzi.html

[R23] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gtwegyavus.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.daxiang520.top/Article/details/gtzmemvaqv.html

[R24] 大小写转换
来源：http://dali.yj202588.top/Article/details/gtkspibihw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hfpthk.cn/Article/details/gtbadjcotv.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenlongwang.top/Article/details/gtprtckxcj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shangyingyoupin.top/Article/details/gtmaplcciz.html

[R26] 命令替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkxnqasqq.html

now=$(date +%F); echo "$now"
来源：http://dali.xylfe.cn/Article/details/gtbfoehdax.html

[R27] 算术展开
来源：http://dali.jyoumei.cn/Article/details/gtheidiuze.html

echo $((1 + 2 * 3))
来源：http://dali.hongshengwenyu.top/Article/details/gtftcauelt.html

[R28] 浮点运算
来源：http://dali.gzhubu.top/Article/details/gtnpzzwkmu.html

echo "scale=2; 10/3" | bc
来源：http://dali.cqqwz.cn/Article/details/gturbklifa.html

[R29] 定义函数
来源：http://dali.gzhubu.top/Article/details/gtvjfqqejf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtbvslksju.html

[R30] 函数返回状态码
来源：http://dali.yueranfly.top/Article/details/gturbvvkuh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xinyue.icu/Article/details/gtqrktqvmm.html

[R31] 局部变量
来源：http://dali.daxiang520.top/Article/details/gtdhnzkixl.html

f() { local x=1; echo "$x"; }
来源：http://dali.birdmap.top/Article/details/gtcfdhtagn.html

[R32] 参数个数校验
来源：http://dali.ppjwa.cn/Article/details/gtowfxqzxr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jqgfzy.top/Article/details/gttjodgoqy.html

[R33] 捕获错误并提示行号
来源：http://dali.nwbrower.top/Article/details/gtcachxfmc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhiwuduotai.top/Article/details/gtdutmllfr.html

[R34] 退出时清理
来源：http://dali.xziqi.cn/Article/details/gtjoqpigcn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gtlphcwrje.html

[R35] 后台执行并等待
来源：http://dali.zycfv.cn/Article/details/gtyceioyin.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ybcxt.top/Article/details/gttfxknzlr.html

[R36] 并发执行多个任务
来源：http://dali.zhengqikj.top/Article/details/gttacbhedq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cucudq.cn/Article/details/gtcebkzwjg.html

[R37] 把输出赋给变量
来源：http://dali.zdqjudy.top/Article/details/gtoungrvfg.html

files=$(ls -1)
来源：http://dali.cheryme.top/Article/details/gtnxlzhsgn.html

[R38] 管道串联
来源：http://dali.yvedp.cn/Article/details/gtvyathsow.html

cat a.txt | grep -i error | wc -l
来源：http://dali.316326.xyz/Article/details/gtzsvboily.html

[R39] 重定向标准输出与错误
来源：http://dali.bjfxy.top/Article/details/gtdoxdulzv.html

cmd > out.log 2>&1
来源：http://dali.dianchejie.cn/Article/details/gtpbnmkasj.html

[R40] 追加写日志
来源：http://dali.xinyue.icu/Article/details/gteznzlkut.html

echo "log" >> out.log
来源：http://dali.chenlongwang.top/Article/details/gtkpehhvcn.html

[R41] 丢弃输出
来源：http://dali.xziqi.cn/Article/details/gtxpnnixja.html


<!-- 参考信息 -->