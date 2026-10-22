代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.iojbl.cn/Article/details/gtwnimzeiz.html

[Q05] 重命名列
来源：http://dali.gogol.net.cn/Article/details/gtkztidjgs.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daria6918.cn/Article/details/gttbhyklpv.html

[Q06] 删除列
来源：http://dali.jinghuilouyu.cn/Article/details/gtdnvditsf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tianlin.xyz/Article/details/gtqnfjawka.html

[Q07] 删除表
来源：http://dali.pengpengdd.cyou/Article/details/gtsgmnrfpl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfycjxfrs.html

[Q08] 创建普通索引
来源：http://dali.ydzc1.top/Article/details/gtczrjnwmk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhongyouzk.top/Article/details/gtecpapcde.html

[Q09] 创建唯一索引
来源：http://dali.jinqigfzy.top/Article/details/gtzajoqxxd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpouoofna.html

[Q10] 插入单行
来源：http://dali.kuanghao11.cn/Article/details/gteisqkrdp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yvedp.cn/Article/details/gtztzvkqlr.html

[Q11] 一次插入多行
来源：http://dali.chenzaomai.com/Article/details/gtgdxrloeu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gogol.net.cn/Article/details/gttvrysmbk.html

[Q12] 插入后取自增 ID
来源：http://dali.tianlin.xyz/Article/details/gtwfjoaaub.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.dianchejie.cn/Article/details/gtudgsytvr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xuetiantiany.cn/Article/details/gtckldbvdq.html

[Q13] 忽略重复插入
来源：http://dali.sysykeji.top/Article/details/gtrxxbxycc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tian-w.cn/Article/details/gtrtdkeydn.html

[Q14] 存在则更新（upsert）
来源：http://dali.jiagoushi.top/Article/details/gtqxrinolu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sxryk.cn/Article/details/gteoovdqxa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shangyingyoupin.top/Article/details/gtchuudkqp.html

[Q15] 查询全部
来源：http://dali.yongpay.top/Article/details/gtzqkwmzsb.html

SELECT * FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtaargiglo.html

[Q16] 查询指定列
来源：http://dali.zhixingplan.top/Article/details/gtjwpvnqab.html

SELECT id, name FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtdwxfezrh.html

[Q17] 条件查询
来源：http://dali.jinqigfzy.top/Article/details/gtgmqwmyxl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.snrcjt.cn/Article/details/gtvzuxarhh.html

[Q18] 模糊匹配
来源：http://dali.yanxiufei.cn/Article/details/gtoyggpjix.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jyoumei.cn/Article/details/gtdayegseh.html

[Q19] 范围查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsssnuoqy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuetiantiany.cn/Article/details/gtuvikkgcw.html

[Q20] IN 列表
来源：http://dali.andypj.xyz/Article/details/gtfsckolkh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgufenzy.top/Article/details/gtxgtejkxo.html

[Q21] 空值判断
来源：http://dali.nanxuanxn.top/Article/details/gtvvelhdny.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tian-w.cn/Article/details/gtvgztetjo.html

[Q22] 排序
来源：http://dali.zhengqikj.top/Article/details/gtnrraxyhs.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nanxuanxn.top/Article/details/gtruptwdfp.html

[Q23] 分页
来源：http://dali.snrcjt.cn/Article/details/gtyqvpeoob.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.vqdsnc.cn/Article/details/gtsrmljgim.html

[Q24] 去重
来源：http://dali.svipenyu.cn/Article/details/gtojtnflwh.html

SELECT DISTINCT city FROM users;
来源：http://dali.9152youxi.cn/Article/details/gturegkbpl.html

[Q25] 只取前 N 条
来源：http://dali.yj20258.top/Article/details/gthgtyyjud.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hfpthk.cn/Article/details/gtcftpmrzl.html

[Q26] 计数
来源：http://dali.sysykeji.top/Article/details/gtjjvpgobo.html

SELECT COUNT(*) FROM users;
来源：http://dali.sweek.top/Article/details/gtpoppsxlk.html

[Q27] 条件计数
来源：http://dali.yuxming.cn/Article/details/gthezbohgv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtytbjkbyw.html

[Q28] 求和与平均
来源：http://dali.jqgfzy.top/Article/details/gtzcrxwecz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtgqlzfdqv.html

[Q29] 最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gtuczzsdwe.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtldhijwtl.html

[Q30] 分组统计
来源：http://dali.sysykeji.top/Article/details/gtqgrmlptl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gtkdsnvgxd.html

[Q31] 分组后过滤
来源：http://dali.smart0.xyz/Article/details/gtgvlddyvp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ydzc1.top/Article/details/gtskqjqyxk.html

[Q32] 分组拼接字符串
来源：http://dali.mhx1999.top/Article/details/gtphbsobar.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwemccswk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hnxiangtu.top/Article/details/gtxtydyyrb.html

[Q33] 多列分组
来源：http://dali.cheryme.top/Article/details/gtfjtzbwil.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shzxlz.cn/Article/details/gtfwrjoyzy.html

[Q34] 每组取第一条
来源：http://dali.cashguo.top/Article/details/gtnjufylpc.html

SELECT * FROM (
来源：http://dali.wangdashe.top/Article/details/gtgsquypxb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yuanzhike.top/Article/details/gtoefwyxnv.html

) t WHERE rn = 1;
来源：http://dali.cucudq.cn/Article/details/gtilznadxc.html

[Q35] 内连接
来源：http://dali.hnqzz.top/Article/details/gtxpvaingx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gtjwqirqkb.html

[Q36] 左连接
来源：http://dali.daria6918.cn/Article/details/gtwdtolmnq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.quarkkingdee.top/Article/details/gtjnotghxg.html

[Q37] 右连接
来源：http://dali.aizwys.cn/Article/details/gtikvhqyzw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.svipenyu.cn/Article/details/gtswhnbpbk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yueranfly.top/Article/details/gtovdppymn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.haohaochexian.top/Article/details/gtwnjngzls.html

[Q39] 自连接（查上下级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkuvivxyl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangshuangyany.cn/Article/details/gtjigwnalg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnujezldj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.haohaochexian.top/Article/details/gtqjjgwchg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.haohaochexian.top/Article/details/gtnrosqnpx.html

[Q41] 多表连接
来源：http://dali.zhixingplan.top/Article/details/gtwqzznlkg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfraxnixk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ydzc1.top/Article/details/gtcusmwqpv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuniozson.html

[Q42] 连接条件附加过滤
来源：http://dali.hnxiangtu.top/Article/details/gtwnbssmcs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvmtesii.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jianghu66.top/Article/details/gtvoyjdzkq.html

[Q43] 标量子查询
来源：http://dali.hysaishi.cn/Article/details/gtgjlarcqi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrxvtohi.html

[Q44] IN 子查询
来源：http://dali.tanke756.top/Article/details/gtbwjprwcs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxohordu.html

[Q45] EXISTS 判断存在
来源：http://dali.cashguo.top/Article/details/gtpgufeuvu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daria6918.cn/Article/details/gtlxfleqtx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ppjwa.cn/Article/details/gtzpbdeszy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gtbnakbvbd.html

[Q47] 与平均值比较
来源：http://dali.sxryk.cn/Article/details/gtbhbllcdf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jiagoushi.top/Article/details/gtxeifutyh.html

[Q48] CTE 公用表表达式
来源：http://dali.havefunace.top/Article/details/gtpqighnbe.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zdqjudy.top/Article/details/gtnzccjurc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jiagoushi.top/Article/details/gtrivqqqhj.html

[Q49] 更新单行
来源：http://dali.hnqzz.top/Article/details/gtvmmsaswy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yanxiufei.cn/Article/details/gtgrearems.html

[Q50] 批量更新
来源：http://dali.zdqjudy.top/Article/details/gtvtznmkvc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sweek.top/Article/details/gthxajkwqu.html

[Q51] 用子查询更新
来源：http://dali.fengsongda.top/Article/details/gtkjtvkmlp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ppjwa.cn/Article/details/gtafbypnwl.html

[Q52] 删除指定行
来源：http://dali.xylfe.cn/Article/details/gtigbakwkj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.dianchejie.cn/Article/details/gtjayzkevz.html

[Q53] 按条件删除
来源：http://dali.feifeiyinyue.top/Article/details/gtqqpxnqjd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.c1oappe.top/Article/details/gtyxzlhqcn.html

[Q54] 清空表
来源：http://dali.shuidangran.top/Article/details/gtprlkfvgk.html

TRUNCATE TABLE logs;
来源：http://dali.yongpay.top/Article/details/gttsqsmdpd.html

[Q55] 排名（并列占位）
来源：http://dali.guowangkeji.top/Article/details/gtbipblfwo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sysykeji.top/Article/details/gtqxmgauvt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.pycfn.com/Article/details/gtrphtyxfi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gtdxdqyaln.html

[Q57] 行号
来源：http://dali.gogol.net.cn/Article/details/gtocxediub.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xylfe.cn/Article/details/gtxcpegkvz.html

[Q58] 累计求和
来源：http://dali.vqdsnc.cn/Article/details/gtjuanozub.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtfxtdrfzq.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gttznyvqpn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtjrlxbgpp.html

[Q60] 取上一行 / 下一行
来源：http://dali.yvedp.cn/Article/details/gtaxbomjvi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xinyue.icu/Article/details/gtpgqdjgns.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtjrjfhbrz.html

[Q61] 移动平均
来源：http://dali.ppjwa.cn/Article/details/gtgiwaplsk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtowywxekk.html

[Q62] 分组占比
来源：http://dali.zdqjudy.top/Article/details/gtyetsivjo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gthnuhziwb.html

[Q63] 开启事务
来源：http://dali.tianlin.xyz/Article/details/gtefhvvwak.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.vqdsnc.cn/Article/details/gtwcoywobw.html

[Q64] 提交事务
来源：http://dali.shangyingyoupin.top/Article/details/gtsqclxlql.html

COMMIT;
来源：http://dali.tian-w.cn/Article/details/gtyxlpkedy.html

[Q65] 回滚事务
来源：http://dali.meibo888.top/Article/details/gtivpgbldo.html

ROLLBACK;
来源：http://dali.jinghuilouyu.cn/Article/details/gtixtmrkbq.html

[Q66] 行锁查询
来源：http://dali.0kj1m.cn/Article/details/gtmlvtcchd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.smart0.xyz/Article/details/gtrbwhagoq.html

[Q67] 设置隔离级别
来源：http://dali.kuanghao11.cn/Article/details/gtdtropyts.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dianchejie.cn/Article/details/gthsmbbjxj.html

[Q68] 保存点
来源：http://dali.dianchejie.cn/Article/details/gtkunqzwlf.html

SAVEPOINT sp1;
来源：http://dali.sxryk.cn/Article/details/gtrtzpgmwf.html

ROLLBACK TO sp1;
来源：http://dali.jqgfzy.top/Article/details/gtjawdpxlt.html

[Q69] 查看执行计划
来源：http://dali.chenzaomai.com/Article/details/gtxkuveemx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jiagoushi.top/Article/details/gtxsgjicdv.html

[Q70] 更新统计信息
来源：http://dali.yangfankeji.com/Article/details/gttusgcmxw.html

ANALYZE TABLE users;
来源：http://dali.ppjwa.cn/Article/details/gtkndhlkbx.html

[Q71] 查看建表语句
来源：http://dali.aizwys.cn/Article/details/gtcsjkczzi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.snrcjt.cn/Article/details/gtgcolobgl.html

[Q72] 查看索引
来源：http://dali.meibo888.top/Article/details/gtvtircavi.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtsevszzyv.html

[Q73] 查看表状态
来源：http://dali.zhixingplan.top/Article/details/gtwamsjowu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xziqi.cn/Article/details/gtvnpzfjfh.html

[Q74] 强制使用索引
来源：http://dali.zycfv.cn/Article/details/gtramcemnr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ppjwa.cn/Article/details/gtpkhnepig.html

[Q75] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gtqhbuqoqg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtiywrfmbt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gzhubu.top/Article/details/gtsypslxwm.html

[Q76] 按天统计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklbsgihq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj20258888.top/Article/details/gtxpzcmwxq.html

[Q77] 时间加减
来源：http://dali.snrcjt.cn/Article/details/gtjsxxdffe.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pycfn.com/Article/details/gtpjuhgnte.html

[Q78] 当前时间
来源：http://dali.yongpay.top/Article/details/gtudrdcslk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj202588.top/Article/details/gtjfopkhho.html

[Q79] 字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gtqoyqyknr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yanxiufei.cn/Article/details/gtysqvxcmi.html

[Q80] 字符串截取
来源：http://dali.shzxlz.cn/Article/details/gttopkidiz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gthbplqahi.html

[Q81] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gtmhfygfew.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.bjfxy.top/Article/details/gtcxrhizjy.html

[Q82] 字符长度与字节长度
来源：http://dali.wangshuangyany.cn/Article/details/gtvsroryfn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtodamunuy.html

[Q83] 大小写转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtmtlbpq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtbfsqadub.html

[Q84] 去除首尾空格
来源：http://dali.pycfn.com/Article/details/gtrampodno.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gthrewbnvt.html

[Q85] 数值取整
来源：http://dali.aizwys.cn/Article/details/gtbtvmcmbc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.aizwys.cn/Article/details/gtlablqxei.html

[Q86] 读取 JSON 字段
来源：http://dali.fengsongda.top/Article/details/gtmuqwyxco.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yuanzhike.top/Article/details/gtqvymqfqt.html

[Q87] JSON 字段做条件
来源：http://dali.xylfe.cn/Article/details/gtejcvcvee.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezbednei.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgfzy.top/Article/details/gtejlgkstj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hysaishi.cn/Article/details/gtopyokxzi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yuxming.cn/Article/details/gtrhqdpgbf.html

[Q89] 判断表是否存在
来源：http://dali.yj20258888.top/Article/details/gtynvgftdp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.snrcjt.cn/Article/details/gtuvszkheb.html

[Q90] 生成序号列
来源：http://dali.hammf.cn/Article/details/gtrufpyflf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhongyouzk.top/Article/details/gtmrcnphot.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtccoudyee.html

R. Bash 专题
来源：http://dali.nanxinkj.top/Article/details/gtkjjkhhhv.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtqheotudn.html

[R01] shebang 与严格模式
来源：http://dali.yongpay.top/Article/details/gtjspaqwlc.html

#!/usr/bin/env bash
来源：http://dali.xziqi.cn/Article/details/gtkeylruhz.html

set -euo pipefail
来源：http://dali.9152youxi.cn/Article/details/gtmvtrpmuo.html

[R02] 变量赋值与使用
来源：http://dali.hammf.cn/Article/details/gtzgkkqpqz.html

name="Tom"; echo "$name"
来源：http://dali.zhengqikj.top/Article/details/gtxwlzselw.html

[R03] 只读变量
来源：http://dali.smart0.xyz/Article/details/gtkiyycvrw.html

readonly PI=3.14
来源：http://dali.c1oappe.top/Article/details/gtwoxbtdjr.html

[R04] 位置参数
来源：http://dali.snrcjt.cn/Article/details/gtpftvnpng.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yvedp.cn/Article/details/gttpryfzbv.html

[R05] 参数默认值
来源：http://dali.yonumen.top/Article/details/gtmpvxmhry.html

name="${1:-default}"
来源：http://dali.sweek.top/Article/details/gtidcntuag.html

[R06] 判断命令是否存在
来源：http://dali.tianlin.xyz/Article/details/gteiybdijs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqavivmiv.html

[R07] if 判断文件
来源：http://dali.bjfxy.top/Article/details/gtvxllxpvi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fengsongda.top/Article/details/gtjaexzmog.html

[R08] 数值比较
来源：http://dali.hywenlv.cn/Article/details/gtjyfabsmz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.316326.xyz/Article/details/gtfbwheufc.html

[R09] 字符串比较
来源：http://dali.hysaishi.cn/Article/details/gtmgbxmslr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jianghu66.top/Article/details/gtafhsrall.html

[R10] 正则匹配
来源：http://dali.vqdsnc.cn/Article/details/gttvxjggbj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.kuanghao11.cn/Article/details/gtsekjaxny.html

[R11] case 多分支
来源：http://dali.svipenyu.cn/Article/details/gtqknpibnq.html

case "$1" in
来源：http://dali.guannengcc.top/Article/details/gtsxftbhoj.html

start) echo "启动" ;;
来源：http://dali.gogol.net.cn/Article/details/gtfbqsfgyh.html

stop)  echo "停止" ;;
来源：http://dali.yonumen.top/Article/details/gtwbsykfgf.html

*)     echo "未知命令" ;;
来源：http://dali.yanxiufei.cn/Article/details/gtrlnpgonz.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gtmhugmikc.html

[R12] for 遍历文件
来源：http://dali.yuxming.cn/Article/details/gtgnmvxrzn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yuxming.cn/Article/details/gtsxvjsdqq.html

[R13] for 计数循环
来源：http://dali.gotoacloud.top/Article/details/gttzsgfuus.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gtnwxjnmxh.html

[R14] C 风格 for
来源：http://dali.zhoulong.xyz/Article/details/gtjtslfyrr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gtmarkdcub.html

[R15] while 逐行读文件
来源：http://dali.yonumen.top/Article/details/gtmrhnehfb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtazwbsfez.html

[R16] until 等待条件
来源：http://dali.zycfv.cn/Article/details/gtynccqynu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.andypj.xyz/Article/details/gtegytdzjh.html

[R17] 数组定义与取值
来源：http://dali.9152youxi.cn/Article/details/gtpkrlmnav.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.meibo888.top/Article/details/gtdzvaxkuw.html

[R18] 遍历数组
来源：http://dali.cdnleiting.top/Article/details/gtbmygmvae.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gzhubu.top/Article/details/gtcibngdls.html

[R19] 数组长度
来源：http://dali.kuanghao11.cn/Article/details/gtemwthfva.html

echo "${#arr[@]}"
来源：http://dali.yj202588.top/Article/details/gtuusyzpnl.html

[R20] 关联数组（字典）
来源：http://dali.chenlongwang.top/Article/details/gtrlrbgyuk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cashguo.top/Article/details/gtkoxxykce.html

[R21] 字符串长度
来源：http://dali.yongpay.top/Article/details/gtcezejvkd.html

echo "${#s}"
来源：http://dali.daxiang520.top/Article/details/gtfgohxqmm.html

[R22] 截取子串
来源：http://dali.pengpengdd.cyou/Article/details/gtnwzkmbvt.html

echo "${s:0:5}"
来源：http://dali.svipenyu.cn/Article/details/gtfkakjnzc.html

[R23] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gtgaldmhcg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.haohaochexian.top/Article/details/gtrdhotszz.html

[R24] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtqqhfxrjt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.andypj.xyz/Article/details/gtogyqagqv.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgfzy.top/Article/details/gtymwcucrg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jlsjyb.cn/Article/details/gthpmiwoul.html

[R26] 命令替换
来源：http://dali.hnxiangtu.top/Article/details/gtotaspivs.html

now=$(date +%F); echo "$now"
来源：http://dali.sweek.top/Article/details/gtxiklxlns.html

[R27] 算术展开
来源：http://dali.feifeiyinyue.top/Article/details/gtwykfrqjs.html

echo $((1 + 2 * 3))
来源：http://dali.aibaodan.cn/Article/details/gticnvdnsb.html

[R28] 浮点运算
来源：http://dali.c1oappe.top/Article/details/gtzzrkiyij.html

echo "scale=2; 10/3" | bc
来源：http://dali.hfpthk.cn/Article/details/gtogyeecdi.html

[R29] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gtxlpzqypj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xziqi.cn/Article/details/gtqnsbmfni.html

[R30] 函数返回状态码
来源：http://dali.birdmap.top/Article/details/gtcxwxdijh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yueranfly.top/Article/details/gtzyokbfhm.html

[R31] 局部变量
来源：http://dali.redwolf501.top/Article/details/gtxuvdnwxo.html

f() { local x=1; echo "$x"; }
来源：http://dali.0kj1m.cn/Article/details/gtjvhsjumg.html

[R32] 参数个数校验
来源：http://dali.jinghuilouyu.cn/Article/details/gttrzfpjik.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gtodskwqld.html

[R33] 捕获错误并提示行号
来源：http://dali.svipenyu.cn/Article/details/gtkgtjdjfj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.pycfn.com/Article/details/gtbqwlqyse.html

[R34] 退出时清理
来源：http://dali.andypj.xyz/Article/details/gtjkjnymxl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gtvucfyzfb.html

[R35] 后台执行并等待
来源：http://dali.nanxuanxn.top/Article/details/gtwhhkegsv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.vqdsnc.cn/Article/details/gtfizxxnho.html

[R36] 并发执行多个任务
来源：http://dali.chenjidiqi.icu/Article/details/gtzfzvwmsb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sufxvd.cn/Article/details/gtfdetrlie.html

[R37] 把输出赋给变量
来源：http://dali.yongpay.top/Article/details/gtfdrjycfm.html

files=$(ls -1)
来源：http://dali.quarkkingdee.top/Article/details/gtfgbrlvft.html

[R38] 管道串联
来源：http://dali.tanke756.top/Article/details/gtauyncsfc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ppjwa.cn/Article/details/gtddcxfrvx.html

[R39] 重定向标准输出与错误
来源：http://dali.cqqwz.cn/Article/details/gtnowvoiin.html

cmd > out.log 2>&1
来源：http://dali.smart0.xyz/Article/details/gtqceechny.html

[R40] 追加写日志
来源：http://dali.hnxiangtu.top/Article/details/gtfjgyndpu.html

echo "log" >> out.log
来源：http://dali.hfpthk.cn/Article/details/gtfepblcsp.html

[R41] 丢弃输出
来源：http://dali.mhx1999.top/Article/details/gtuebyomtt.html

cmd >/dev/null 2>&1
来源：http://dali.wangdashe.top/Article/details/gtomyyinfs.html

[R42] 输入重定向
来源：http://dali.pycfn.com/Article/details/gtithjetwh.html

wc -l < a.txt
来源：http://dali.yj20258.top/Article/details/gtrplfigud.html

[R43] 按名字查找文件
来源：http://dali.guannengcc.top/Article/details/gthiiysaxf.html

find . -name "*.log" -type f
来源：http://dali.wangshuangyany.cn/Article/details/gtsdbcltnv.html

[R44] 按修改时间查找
来源：http://dali.feifeiyinyue.top/Article/details/gtzszeenim.html

find . -mtime -7 -type f
来源：http://dali.xylfe.cn/Article/details/gtwyligkoe.html

[R45] 批量删除
来源：http://dali.tianlin.xyz/Article/details/gthfzmqigb.html

find . -name "*.tmp" -delete
来源：http://dali.yj20258888.top/Article/details/gtxlcoijmi.html

[R46] 递归替换文件内容
来源：http://dali.yongpay.top/Article/details/gtognlvrjw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ppjwa.cn/Article/details/gtlqpbuaoa.html

[R47] sed 单行替换
来源：http://dali.xuanzx.com/Article/details/gtahlemtnq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zdqjudy.top/Article/details/gtevquasqi.html

[R48] awk 取指定列
来源：http://dali.hywenlv.cn/Article/details/gtpejkxqcg.html

awk '{print $1, $3}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gtwnummemn.html

[R49] awk 带条件
来源：http://dali.gogol.net.cn/Article/details/gtpahrjomb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xziqi.cn/Article/details/gtuyhquuzz.html

[R50] awk 求和
来源：http://dali.daxiang520.top/Article/details/gtdrlpiyzg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtvaohchfx.html

[R51] 排序去重取前几
来源：http://dali.vqdsnc.cn/Article/details/gtmwwvrsuh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sweek.top/Article/details/gtlmzajywc.html

[R52] 统计行数
来源：http://dali.yanxiufei.cn/Article/details/gtxwyjdkhu.html

wc -l a.txt
来源：http://dali.bjfxy.top/Article/details/gtnhrhmhyv.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigfzy.top/Article/details/gtqarzjohq.html


<!-- 参考信息 -->