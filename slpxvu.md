代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yueranfly.top/Article/details/gtavyevaah.html

[Q05] 重命名列
来源：http://dali.haohaochexian.top/Article/details/gtuazyqbkp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhiwuduotai.top/Article/details/gttqtickzi.html

[Q06] 删除列
来源：http://dali.yvedp.cn/Article/details/gtypzgwymi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuanzhike.top/Article/details/gtjttzorwy.html

[Q07] 删除表
来源：http://dali.zhongyouzk.top/Article/details/gtfjqlhaju.html

DROP TABLE IF EXISTS orders;
来源：http://dali.smart0.xyz/Article/details/gtjlddkvnx.html

[Q08] 创建普通索引
来源：http://dali.wangdashe.top/Article/details/gtdzpdzyhd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sweek.top/Article/details/gtijvnoytq.html

[Q09] 创建唯一索引
来源：http://dali.yj202588.top/Article/details/gtzornpakc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gtgzfdyqsa.html

[Q10] 插入单行
来源：http://dali.ydzc1.top/Article/details/gtowshlfpe.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtzxfxwkua.html

[Q11] 一次插入多行
来源：http://dali.yangfankeji.com/Article/details/gtetuxjmmc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gtvxjvtbll.html

[Q12] 插入后取自增 ID
来源：http://dali.shangyingyoupin.top/Article/details/gtqjqvbsge.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbnvdwiyx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinghuilouyu.cn/Article/details/gtlukpuunb.html

[Q13] 忽略重复插入
来源：http://dali.hnxiangtu.top/Article/details/gttlpdxbto.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gtgwmvwiub.html

[Q14] 存在则更新（upsert）
来源：http://dali.sufxvd.cn/Article/details/gtkqjbozjg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zdqjudy.top/Article/details/gthtflnzpd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yonumen.top/Article/details/gtanpwmeki.html

[Q15] 查询全部
来源：http://dali.andypj.xyz/Article/details/gtxgnoirge.html

SELECT * FROM users;
来源：http://dali.aizwys.cn/Article/details/gtllphftcw.html

[Q16] 查询指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbnpzceer.html

SELECT id, name FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtfunrojtp.html

[Q17] 条件查询
来源：http://dali.sufxvd.cn/Article/details/gtvwofazdu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jiagoushi.top/Article/details/gtrzjwhxaz.html

[Q18] 模糊匹配
来源：http://dali.redwolf501.top/Article/details/gtsobnfaht.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sufxvd.cn/Article/details/gtnfyajiji.html

[Q19] 范围查询
来源：http://dali.yvedp.cn/Article/details/gttrxmeewi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shzxlz.cn/Article/details/gtifzpcmhd.html

[Q20] IN 列表
来源：http://dali.pycfn.com/Article/details/gtwuaxfeqo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sufxvd.cn/Article/details/gtswutpiuo.html

[Q21] 空值判断
来源：http://dali.cdnleiting.top/Article/details/gtvaneqldy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.svipenyu.cn/Article/details/gtsieaqvdo.html

[Q22] 排序
来源：http://dali.daxiang520.top/Article/details/gtunzyvjug.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shzxlz.cn/Article/details/gtysikvscg.html

[Q23] 分页
来源：http://dali.sweek.top/Article/details/gtgkasgghp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tian-w.cn/Article/details/gtlkztjctu.html

[Q24] 去重
来源：http://dali.xuanzx.com/Article/details/gtydvuxcty.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtzomzdody.html

[Q25] 只取前 N 条
来源：http://dali.xuetiantiany.cn/Article/details/gtkwbqamjs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ppjwa.cn/Article/details/gtdhpuqxko.html

[Q26] 计数
来源：http://dali.vqdsnc.cn/Article/details/gtgfplhnyv.html

SELECT COUNT(*) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtjqlkizag.html

[Q27] 条件计数
来源：http://dali.jiagoushi.top/Article/details/gttuvpujqo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtazujfokn.html

[Q28] 求和与平均
来源：http://dali.shzxlz.cn/Article/details/gtwxhzukpc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtxujjctwb.html

[Q29] 最大最小值
来源：http://dali.snrcjt.cn/Article/details/gtrmwaijwa.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtihtuckcu.html

[Q30] 分组统计
来源：http://dali.hnxiangtu.top/Article/details/gtaldqsklq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbkhbkitm.html

[Q31] 分组后过滤
来源：http://dali.xziqi.cn/Article/details/gtmzdtdsjg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.birdmap.top/Article/details/gtovueohpb.html

[Q32] 分组拼接字符串
来源：http://dali.nwbrower.top/Article/details/gtdoijqqvm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrxgyvdm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cdnleiting.top/Article/details/gtbdyerfik.html

[Q33] 多列分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkiabfon.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yonumen.top/Article/details/gtwcwrmmpr.html

[Q34] 每组取第一条
来源：http://dali.cdnleiting.top/Article/details/gtyfjabaci.html

SELECT * FROM (
来源：http://dali.jinqigfzy.top/Article/details/gtyssmsndw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cqqwz.cn/Article/details/gtwzewxaps.html

) t WHERE rn = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvefpiszu.html

[Q35] 内连接
来源：http://dali.guannengcc.top/Article/details/gtnuvxztpp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cdnleiting.top/Article/details/gtntqldwpf.html

[Q36] 左连接
来源：http://dali.ybcxt.top/Article/details/gtxegwfxzg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hammf.cn/Article/details/gtzxarhsdr.html

[Q37] 右连接
来源：http://dali.gaohongyu789.top/Article/details/gtzfuiwnwm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.redwolf501.top/Article/details/gtoujekcup.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnxiangtu.top/Article/details/gthobjhnsp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.guannengcc.top/Article/details/gtizrsainu.html

[Q39] 自连接（查上下级）
来源：http://dali.ehwqpu.com/Article/details/gtkgbtfwze.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgfzy.top/Article/details/gteqjztssi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gogol.net.cn/Article/details/gtkhapomdd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yueranfly.top/Article/details/gtnleceegi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gotoacloud.top/Article/details/gtizjvgnbt.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gtbrlutvhk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.quarkkingdee.top/Article/details/gtkyfukfvb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yonumen.top/Article/details/gtwrnvaqno.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tanke756.top/Article/details/gtnvzoywkw.html

[Q42] 连接条件附加过滤
来源：http://dali.chenlongwang.top/Article/details/gtvaimbfuc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jqgufenzy.top/Article/details/gtuxllrdeu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.redwolf501.top/Article/details/gtwbkjljnx.html

[Q43] 标量子查询
来源：http://dali.jinqigfzy.top/Article/details/gtdalslerp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zycfv.cn/Article/details/gtzywhnwwb.html

[Q44] IN 子查询
来源：http://dali.gzhubu.top/Article/details/gtddlkgqcs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj202588.top/Article/details/gtrxutspch.html

[Q45] EXISTS 判断存在
来源：http://dali.jyoumei.cn/Article/details/gtwngbdgdq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gtzulqkada.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xylfe.cn/Article/details/gtbsvasuiq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.9152youxi.cn/Article/details/gtunggutyi.html

[Q47] 与平均值比较
来源：http://dali.fengsongda.top/Article/details/gtoacjabfv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gthkixcasm.html

[Q48] CTE 公用表表达式
来源：http://dali.quarkkingdee.top/Article/details/gtszlbxwzj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.9152youxi.cn/Article/details/gtvlpnqeru.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jiagoushi.top/Article/details/gtemgjnoqr.html

[Q49] 更新单行
来源：http://dali.yangfankeji.com/Article/details/gtkdhwmwxu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gtzsafokgy.html

[Q50] 批量更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtroirjikz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aibaodan.cn/Article/details/gtmvtlhnag.html

[Q51] 用子查询更新
来源：http://dali.gotoacloud.top/Article/details/gtojcyihbr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.birdmap.top/Article/details/gtvkwzahcw.html

[Q52] 删除指定行
来源：http://dali.cheryme.top/Article/details/gtllvbjwlq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.fengsongda.top/Article/details/gtrqkugjon.html

[Q53] 按条件删除
来源：http://dali.hywenlv.cn/Article/details/gtvnrmsxrm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shzxlz.cn/Article/details/gtdwccocgr.html

[Q54] 清空表
来源：http://dali.tanke756.top/Article/details/gtxmlkuska.html

TRUNCATE TABLE logs;
来源：http://dali.sxryk.cn/Article/details/gtotshtslu.html

[Q55] 排名（并列占位）
来源：http://dali.havefunace.top/Article/details/gtpwviggfs.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jiagoushi.top/Article/details/gtldzovcxo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guannengcc.top/Article/details/gtplwfgxkg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gtrfyseqkm.html

[Q57] 行号
来源：http://dali.hfpthk.cn/Article/details/gtkjciuqxo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtzzbjkepq.html

[Q58] 累计求和
来源：http://dali.andypj.xyz/Article/details/gtcaxcpoft.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtlxalukmu.html

[Q59] 分组内累计
来源：http://dali.xuanzx.com/Article/details/gtjzucugkv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtnszzyahv.html

[Q60] 取上一行 / 下一行
来源：http://dali.yuxming.cn/Article/details/gtkrbxxgxd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daxiang520.top/Article/details/gtrsjrxpek.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtspvldidr.html

[Q61] 移动平均
来源：http://dali.fengsongda.top/Article/details/gtbxmsnotg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtowagdprs.html

[Q62] 分组占比
来源：http://dali.gzhubu.top/Article/details/gtucuiybqp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtfdayrvbm.html

[Q63] 开启事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrxxyeqs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yongpay.top/Article/details/gtmlqyvhfz.html

[Q64] 提交事务
来源：http://dali.yj202588.top/Article/details/gthkpxskvc.html

COMMIT;
来源：http://dali.quarkkingdee.top/Article/details/gtmdeiviaz.html

[Q65] 回滚事务
来源：http://dali.chenlongwang.top/Article/details/gtsignwlig.html

ROLLBACK;
来源：http://dali.gotoacloud.top/Article/details/gtdfeowmty.html

[Q66] 行锁查询
来源：http://dali.hysaishi.cn/Article/details/gtwaxiachp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yvedp.cn/Article/details/gtipyfzdff.html

[Q67] 设置隔离级别
来源：http://dali.yvedp.cn/Article/details/gtcoedxros.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.guowangkeji.top/Article/details/gtzapmprjl.html

[Q68] 保存点
来源：http://dali.cqqwz.cn/Article/details/gtroxkirtg.html

SAVEPOINT sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgqhojjn.html

ROLLBACK TO sp1;
来源：http://dali.yanxiufei.cn/Article/details/gtsndakaho.html

[Q69] 查看执行计划
来源：http://dali.c1oappe.top/Article/details/gtjyyexhfn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.smart0.xyz/Article/details/gteclvjkhu.html

[Q70] 更新统计信息
来源：http://dali.meibo888.top/Article/details/gtkactgzpr.html

ANALYZE TABLE users;
来源：http://dali.jiagoushi.top/Article/details/gttexhascf.html

[Q71] 查看建表语句
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqzxmyus.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hfpthk.cn/Article/details/gtanctjmed.html

[Q72] 查看索引
来源：http://dali.svipenyu.cn/Article/details/gtbyjtldio.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtjswwqcfr.html

[Q73] 查看表状态
来源：http://dali.cdnleiting.top/Article/details/gtflynbeke.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258888.top/Article/details/gtchsbbyzc.html

[Q74] 强制使用索引
来源：http://dali.zdqjudy.top/Article/details/gtrdwskamc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.snrcjt.cn/Article/details/gtzhfasvrg.html

[Q75] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtsgnchglc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtneoayzng.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ydzc1.top/Article/details/gtbiowldyo.html

[Q76] 按天统计
来源：http://dali.shuidangran.top/Article/details/gtsudizxkw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shangyingyoupin.top/Article/details/gtgzgqopob.html

[Q77] 时间加减
来源：http://dali.sxryk.cn/Article/details/gtxjconxfw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcgauhhb.html

[Q78] 当前时间
来源：http://dali.dashuyun.cn/Article/details/gttonkysxu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenzaomai.com/Article/details/gtktqbzdrd.html

[Q79] 字符串拼接
来源：http://dali.gzhubu.top/Article/details/gtcgwmnmmo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gotoacloud.top/Article/details/gtvdjnygnh.html

[Q80] 字符串截取
来源：http://dali.yj20258888.top/Article/details/gttmcrdjir.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtpcudpxhr.html

[Q81] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gtelqmwapc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ybcxt.top/Article/details/gtcjezpyvi.html

[Q82] 字符长度与字节长度
来源：http://dali.guannengcc.top/Article/details/gtusozbnuq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtxtbxpxrj.html

[Q83] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gtkkrayanf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyevtnqbj.html

[Q84] 去除首尾空格
来源：http://dali.wangdashe.top/Article/details/gtofybdskh.html

SELECT TRIM(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidnjtmqw.html

[Q85] 数值取整
来源：http://dali.yuxming.cn/Article/details/gtjokwgpui.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jianghu66.top/Article/details/gtnkqzukbm.html

[Q86] 读取 JSON 字段
来源：http://dali.pengpengdd.cyou/Article/details/gtnwaldhlx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aibaodan.cn/Article/details/gtjsdqtrpa.html

[Q87] JSON 字段做条件
来源：http://dali.yj202588.top/Article/details/gtqxnmqmri.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxuanxn.top/Article/details/gtnmyisbbc.html

[Q88] 行转列（条件聚合）
来源：http://dali.dashuyun.cn/Article/details/gtnlxxctjf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cashguo.top/Article/details/gtafzdrimd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtdhlslnpk.html

[Q89] 判断表是否存在
来源：http://dali.nwbrower.top/Article/details/gtgwbcukyo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jianghu66.top/Article/details/gtndfhmlei.html

[Q90] 生成序号列
来源：http://dali.kuanghao11.cn/Article/details/gtvshhxcvd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hammf.cn/Article/details/gtdvmfosmw.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtqujrsvmr.html

R. Bash 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlxuwycbs.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtxqzrnljx.html

[R01] shebang 与严格模式
来源：http://dali.zhengqikj.top/Article/details/gtdkqwvayo.html

#!/usr/bin/env bash
来源：http://dali.shanyushiyangtech.top/Article/details/gteyfnocgc.html

set -euo pipefail
来源：http://dali.cqqwz.cn/Article/details/gtaitcxibb.html

[R02] 变量赋值与使用
来源：http://dali.kuanghao11.cn/Article/details/gtilegkhzi.html

name="Tom"; echo "$name"
来源：http://dali.sysykeji.top/Article/details/gtvolglpkk.html

[R03] 只读变量
来源：http://dali.wangshuangyany.cn/Article/details/gtmisshoir.html

readonly PI=3.14
来源：http://dali.guannengcc.top/Article/details/gtebkfsalr.html

[R04] 位置参数
来源：http://dali.ehwqpu.com/Article/details/gtokjposnm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pengpengdd.cyou/Article/details/gtzjrfxgie.html

[R05] 参数默认值
来源：http://dali.ivvv.top/Article/details/gtncdhstgl.html

name="${1:-default}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgfvhwzc.html

[R06] 判断命令是否存在
来源：http://dali.jiagoushi.top/Article/details/gtqvbdqovh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cheryme.top/Article/details/gtptwyxexo.html

[R07] if 判断文件
来源：http://dali.c1oappe.top/Article/details/gtsdoohjfs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yangfankeji.com/Article/details/gtmlduanob.html

[R08] 数值比较
来源：http://dali.chenzaomai.com/Article/details/gtcmxmvdfo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.meibo888.top/Article/details/gtirjoctta.html

[R09] 字符串比较
来源：http://dali.chenzaomai.com/Article/details/gtovquxvss.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tian-w.cn/Article/details/gtmlqfsjrk.html

[R10] 正则匹配
来源：http://dali.zhengqikj.top/Article/details/gtolwyergf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.haohaochexian.top/Article/details/gthtaielph.html

[R11] case 多分支
来源：http://dali.vqdsnc.cn/Article/details/gtyotrnssr.html

case "$1" in
来源：http://dali.gotoacloud.top/Article/details/gtqigyukhe.html

start) echo "启动" ;;
来源：http://dali.zhongyouzk.top/Article/details/gtjwyryjzt.html

stop)  echo "停止" ;;
来源：http://dali.gzhubu.top/Article/details/gtxztxgmgj.html

*)     echo "未知命令" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzhuirvi.html

esac
来源：http://dali.316326.xyz/Article/details/gtwteibnkd.html

[R12] for 遍历文件
来源：http://dali.fengsongda.top/Article/details/gtxqwlkyyv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngrwlnqz.html

[R13] for 计数循环
来源：http://dali.smart0.xyz/Article/details/gtlxnxxykq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gtglhpbmag.html

[R14] C 风格 for
来源：http://dali.xinyue.icu/Article/details/gtxpfjdqqm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtaacbsmcn.html

[R15] while 逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtmvhtvdta.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapjprsdj.html

[R16] until 等待条件
来源：http://dali.yangfankeji.com/Article/details/gtopwyaoya.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gtymeqwkbn.html

[R17] 数组定义与取值
来源：http://dali.daria6918.cn/Article/details/gthoofthsz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangdashe.top/Article/details/gteryzctby.html

[R18] 遍历数组
来源：http://dali.hywenlv.cn/Article/details/gtrqgcoegr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zdqjudy.top/Article/details/gtjqtckksn.html

[R19] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gtmdlbjftu.html

echo "${#arr[@]}"
来源：http://dali.yonumen.top/Article/details/gtsltmomto.html

[R20] 关联数组（字典）
来源：http://dali.vqdsnc.cn/Article/details/gtiklpmpsz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yueranfly.top/Article/details/gteuoywhhi.html

[R21] 字符串长度
来源：http://dali.aibaodan.cn/Article/details/gtvlazmeke.html

echo "${#s}"
来源：http://dali.yueranfly.top/Article/details/gtwqkumuwh.html

[R22] 截取子串
来源：http://dali.9152youxi.cn/Article/details/gtcrgjjiux.html

echo "${s:0:5}"
来源：http://dali.jqgufenzy.top/Article/details/gtzkmwkxjr.html

[R23] 字符串替换
来源：http://dali.aibaodan.cn/Article/details/gtoxmpxbnh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gaohongyu789.top/Article/details/gtnqmlverm.html

[R24] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gtrtaohtfa.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.birdmap.top/Article/details/gtpukiuyec.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnqzz.top/Article/details/gtrjkbppkg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.guowangkeji.top/Article/details/gtoywxiwzo.html

[R26] 命令替换
来源：http://dali.xuanzx.com/Article/details/gtssrmkwic.html

now=$(date +%F); echo "$now"
来源：http://dali.daxiang520.top/Article/details/gtttkzcnmo.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gteywqhxan.html

echo $((1 + 2 * 3))
来源：http://dali.xuetiantiany.cn/Article/details/gttlvjmsqc.html

[R28] 浮点运算
来源：http://dali.dianchejie.cn/Article/details/gtfoisgnxx.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhoulong.xyz/Article/details/gtwmblmbrv.html

[R29] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gtxopokjpy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtruwkabrm.html

[R30] 函数返回状态码
来源：http://dali.birdmap.top/Article/details/gtjppkenfh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.redwolf501.top/Article/details/gtanhrggfz.html

[R31] 局部变量
来源：http://dali.hnqzz.top/Article/details/gtlyqeyhkj.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenlongwang.top/Article/details/gtndebvqzx.html

[R32] 参数个数校验
来源：http://dali.tianlin.xyz/Article/details/gtwinsihki.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.havefunace.top/Article/details/gtviruhkgw.html

[R33] 捕获错误并提示行号
来源：http://dali.zhengqikj.top/Article/details/gtpubsgupo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenzaomai.com/Article/details/gtwtdtcise.html

[R34] 退出时清理
来源：http://dali.hywenlv.cn/Article/details/gtiuhhfokk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gtzvzgymab.html

[R35] 后台执行并等待
来源：http://dali.hammf.cn/Article/details/gtksotocbc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hfpthk.cn/Article/details/gtkcaaibpa.html

[R36] 并发执行多个任务
来源：http://dali.yanxiufei.cn/Article/details/gtwmrrcqax.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.guannengcc.top/Article/details/gtnqudwdhk.html

[R37] 把输出赋给变量
来源：http://dali.jinqigfzy.top/Article/details/gtraelqwql.html

files=$(ls -1)
来源：http://dali.quarkkingdee.top/Article/details/gtqeurhnfb.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gtshqtbnud.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hysaishi.cn/Article/details/gtgycermhw.html

[R39] 重定向标准输出与错误
来源：http://dali.bjfxy.top/Article/details/gtqbljopcb.html

cmd > out.log 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gtvhclbjqy.html

[R40] 追加写日志
来源：http://dali.chenzaomai.com/Article/details/gtwkwxyqku.html

echo "log" >> out.log
来源：http://dali.c1oappe.top/Article/details/gtytqnahgf.html

[R41] 丢弃输出
来源：http://dali.snrcjt.cn/Article/details/gtrjduoitd.html

cmd >/dev/null 2>&1
来源：http://dali.xylfe.cn/Article/details/gtwnqiqwsg.html

[R42] 输入重定向
来源：http://dali.svipenyu.cn/Article/details/gtvtgyixkh.html

wc -l < a.txt
来源：http://dali.haohaochexian.top/Article/details/gtqulhuceu.html

[R43] 按名字查找文件
来源：http://dali.snrcjt.cn/Article/details/gtxjbkjvas.html

find . -name "*.log" -type f
来源：http://dali.wangshuangyany.cn/Article/details/gtrddwtacc.html

[R44] 按修改时间查找
来源：http://dali.ybcxt.top/Article/details/gtngauofax.html

find . -mtime -7 -type f
来源：http://dali.nwbrower.top/Article/details/gtkwqjwimw.html

[R45] 批量删除
来源：http://dali.hysaishi.cn/Article/details/gtakljuzdh.html

find . -name "*.tmp" -delete
来源：http://dali.nanxuanxn.top/Article/details/gtjulmynad.html

[R46] 递归替换文件内容
来源：http://dali.redwolf501.top/Article/details/gtzcsqyzpa.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhongyouzk.top/Article/details/gtmqvztgdw.html

[R47] sed 单行替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtworrwuua.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258.top/Article/details/gtfdogrxyx.html

[R48] awk 取指定列
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzigfeku.html

awk '{print $1, $3}' a.txt
来源：http://dali.gzhubu.top/Article/details/gtrrpmilah.html

[R49] awk 带条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkoqtdfxh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yvedp.cn/Article/details/gtomheizju.html

[R50] awk 求和
来源：http://dali.yvedp.cn/Article/details/gtuvlscsqs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ybcxt.top/Article/details/gtrvwdnhnv.html

[R51] 排序去重取前几
来源：http://dali.jlsjyb.cn/Article/details/gtlmcfagjr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xziqi.cn/Article/details/gtmmhhevvr.html

[R52] 统计行数
来源：http://dali.tian-w.cn/Article/details/gtzosvslsf.html

wc -l a.txt
来源：http://dali.cheryme.top/Article/details/gtuvllofhp.html

[R53] 查看文件头与实时尾
来源：http://dali.gaohongyu789.top/Article/details/gtcjzanlyw.html


<!-- 参考信息 -->