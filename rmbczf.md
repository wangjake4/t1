代发 wailian999

);
来源：http://dali.dashuyun.cn/Article/details/gtpejzeqgb.html

[Q03] 增加列
来源：http://dali.hysaishi.cn/Article/details/gtahyytvov.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.aizwys.cn/Article/details/gtgofczafj.html

[Q04] 修改列类型
来源：http://dali.jianghu66.top/Article/details/gtpgbwtqdo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jianghu66.top/Article/details/gtqiszhzme.html

[Q05] 重命名列
来源：http://dali.snrcjt.cn/Article/details/gtguhackil.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sweek.top/Article/details/gtqfuwosdx.html

[Q06] 删除列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklmxgbss.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgpnoujc.html

[Q07] 删除表
来源：http://dali.zdqjudy.top/Article/details/gtznzogqev.html

DROP TABLE IF EXISTS orders;
来源：http://dali.pycfn.com/Article/details/gtsrufgycn.html

[Q08] 创建普通索引
来源：http://dali.zhoulong.xyz/Article/details/gtgucehivv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gtsuokmbjw.html

[Q09] 创建唯一索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjvogitv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gtmqwnrvbv.html

[Q10] 插入单行
来源：http://dali.jiagoushi.top/Article/details/gtjxwwelgj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gtmklbbrug.html

[Q11] 一次插入多行
来源：http://dali.cheryme.top/Article/details/gtskvjmlcf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gtablqmzgv.html

[Q12] 插入后取自增 ID
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrscntugj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cashguo.top/Article/details/gtmhumplzb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xinyue.icu/Article/details/gtscahalhe.html

[Q13] 忽略重复插入
来源：http://dali.hammf.cn/Article/details/gtsmtupzsp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.fengsongda.top/Article/details/gtodozicgz.html

[Q14] 存在则更新（upsert）
来源：http://dali.ppjwa.cn/Article/details/gtahshvwez.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cashguo.top/Article/details/gtmrgiidqa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sufxvd.cn/Article/details/gtkjmqweov.html

[Q15] 查询全部
来源：http://dali.nanxuanxn.top/Article/details/gthxktdjrs.html

SELECT * FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtmviaskct.html

[Q16] 查询指定列
来源：http://dali.cucudq.cn/Article/details/gtghyoudhy.html

SELECT id, name FROM users;
来源：http://dali.yj202588.top/Article/details/gtaduzeobk.html

[Q17] 条件查询
来源：http://dali.svipenyu.cn/Article/details/gtdgwpzoyb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenzaomai.com/Article/details/gtxzngevco.html

[Q18] 模糊匹配
来源：http://dali.zycfv.cn/Article/details/gtvlcecrck.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gogol.net.cn/Article/details/gtbjdngyap.html

[Q19] 范围查询
来源：http://dali.shuidangran.top/Article/details/gthgjzkmre.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.fzhhl.top/Article/details/gtqimxnbjh.html

[Q20] IN 列表
来源：http://dali.yonumen.top/Article/details/gtehuvavfm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.0kj1m.cn/Article/details/gtzxgsvgds.html

[Q21] 空值判断
来源：http://dali.shangyingyoupin.top/Article/details/gtunaicjbb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhongyouzk.top/Article/details/gtlswndfmq.html

[Q22] 排序
来源：http://dali.cucudq.cn/Article/details/gtcgnhszoe.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yongpay.top/Article/details/gtgjgxqgtn.html

[Q23] 分页
来源：http://dali.fengsongda.top/Article/details/gtwkwyvwld.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.pengpengdd.cyou/Article/details/gtubmgtxya.html

[Q24] 去重
来源：http://dali.zhiwuduotai.top/Article/details/gtdxzdbbjr.html

SELECT DISTINCT city FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtvhesloft.html

[Q25] 只取前 N 条
来源：http://dali.c1oappe.top/Article/details/gtdmlvkbrn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.316326.xyz/Article/details/gtsmdqlmbi.html

[Q26] 计数
来源：http://dali.cucudq.cn/Article/details/gtaozriarn.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtbpvvfrbd.html

[Q27] 条件计数
来源：http://dali.jqgufenzy.top/Article/details/gtxdwvbmsb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtemtklpid.html

[Q28] 求和与平均
来源：http://dali.gogol.net.cn/Article/details/gtwenefrys.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtqgogopwz.html

[Q29] 最大最小值
来源：http://dali.zhiwuduotai.top/Article/details/gteekoxehy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.fzhhl.top/Article/details/gthesjsyve.html

[Q30] 分组统计
来源：http://dali.sweek.top/Article/details/gtnfchorfa.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gtkblasrck.html

[Q31] 分组后过滤
来源：http://dali.sxryk.cn/Article/details/gtljbwxsqg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shuidangran.top/Article/details/gtzxkpkojy.html

[Q32] 分组拼接字符串
来源：http://dali.daxiang520.top/Article/details/gtnfyxrbkf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gtjkscodvr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.smart0.xyz/Article/details/gtnquxonny.html

[Q33] 多列分组
来源：http://dali.guannengcc.top/Article/details/gtnakfzukj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xinyue.icu/Article/details/gtdkdtolzw.html

[Q34] 每组取第一条
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuchicstf.html

SELECT * FROM (
来源：http://dali.xinyue.icu/Article/details/gtuxhnbkzd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenlongwang.top/Article/details/gtcioaeuek.html

) t WHERE rn = 1;
来源：http://dali.bjfxy.top/Article/details/gtunvdnbyy.html

[Q35] 内连接
来源：http://dali.hywenlv.cn/Article/details/gttnkcnbkr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tanke756.top/Article/details/gtvvmjiszd.html

[Q36] 左连接
来源：http://dali.hysaishi.cn/Article/details/gtoqtrydrc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuetiantiany.cn/Article/details/gtrbejunpm.html

[Q37] 右连接
来源：http://dali.sweek.top/Article/details/gtdtuknblj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gotoacloud.top/Article/details/gtuskmfnse.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sysykeji.top/Article/details/gtuirlddps.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.birdmap.top/Article/details/gtjxlxjbcj.html

[Q39] 自连接（查上下级）
来源：http://dali.dianchejie.cn/Article/details/gtwwfyykhz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cqqwz.cn/Article/details/gtmkzassmj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.svipenyu.cn/Article/details/gtidjddxju.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.fzhhl.top/Article/details/gtjhcmkpng.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.svipenyu.cn/Article/details/gttxdeukik.html

[Q41] 多表连接
来源：http://dali.chenlongwang.top/Article/details/gtzsskrzfm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sweek.top/Article/details/gtntssfzbr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hammf.cn/Article/details/gtmmmuqoev.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ehwqpu.com/Article/details/gtleuhdiat.html

[Q42] 连接条件附加过滤
来源：http://dali.aibaodan.cn/Article/details/gtaefgeqsa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj20258888.top/Article/details/gtvlwsilio.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.birdmap.top/Article/details/gtbcflrmzt.html

[Q43] 标量子查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhytrlmj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgfzy.top/Article/details/gtyyipbwgk.html

[Q44] IN 子查询
来源：http://dali.zdqjudy.top/Article/details/gtjgunwdhn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cqqwz.cn/Article/details/gtbtnrwmon.html

[Q45] EXISTS 判断存在
来源：http://dali.sxryk.cn/Article/details/gtmdqchlnu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnqzz.top/Article/details/gtvnrimrsh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangdashe.top/Article/details/gtlhezpmea.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigufen.top/Article/details/gtpqglxmmh.html

[Q47] 与平均值比较
来源：http://dali.gzhubu.top/Article/details/gtegxaidvg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nwbrower.top/Article/details/gtybyluhys.html

[Q48] CTE 公用表表达式
来源：http://dali.shzxlz.cn/Article/details/gtetfrcaqu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nanxuanxn.top/Article/details/gtstfaibrs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jianghu66.top/Article/details/gteuuiugpg.html

[Q49] 更新单行
来源：http://dali.haohaochexian.top/Article/details/gtdnovmknp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gtljsegupi.html

[Q50] 批量更新
来源：http://dali.jlsjyb.cn/Article/details/gtcgnghkcj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xinyue.icu/Article/details/gtedgibaed.html

[Q51] 用子查询更新
来源：http://dali.ydzc1.top/Article/details/gtxeudezxl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yuxming.cn/Article/details/gtbgkoqxtv.html

[Q52] 删除指定行
来源：http://dali.hysaishi.cn/Article/details/gtocvhiqae.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj202588.top/Article/details/gtqidutvuz.html

[Q53] 按条件删除
来源：http://dali.tian-w.cn/Article/details/gtavshrgkx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gtahwsatba.html

[Q54] 清空表
来源：http://dali.shangyingyoupin.top/Article/details/gtqrumxfsi.html

TRUNCATE TABLE logs;
来源：http://dali.shuidangran.top/Article/details/gtbnjiltzn.html

[Q55] 排名（并列占位）
来源：http://dali.nanxuanxn.top/Article/details/gtwafmgfge.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cucudq.cn/Article/details/gtmjczunmw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.c1oappe.top/Article/details/gtfdzepvsm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xylfe.cn/Article/details/gtgdhzkguu.html

[Q57] 行号
来源：http://dali.nanxinkj.top/Article/details/gtisljudqx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtgntpryja.html

[Q58] 累计求和
来源：http://dali.sxryk.cn/Article/details/gtmikgqjmo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtbwyuopjt.html

[Q59] 分组内累计
来源：http://dali.andypj.xyz/Article/details/gtmjqenpjf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtqnankycq.html

[Q60] 取上一行 / 下一行
来源：http://dali.feifeiyinyue.top/Article/details/gtdelprorm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gzhubu.top/Article/details/gtuyvzltps.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtsiufmuoc.html

[Q61] 移动平均
来源：http://dali.ehwqpu.com/Article/details/gtywblcqma.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtbrbuabkg.html

[Q62] 分组占比
来源：http://dali.zhiwuduotai.top/Article/details/gtwzwgebdf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gtrivoufsc.html

[Q63] 开启事务
来源：http://dali.redwolf501.top/Article/details/gtlvpyzvzn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangdashe.top/Article/details/gtxmwnqsot.html

[Q64] 提交事务
来源：http://dali.sweek.top/Article/details/gtahkjluwl.html

COMMIT;
来源：http://dali.tianlin.xyz/Article/details/gtyjmzmmdd.html

[Q65] 回滚事务
来源：http://dali.haohaochexian.top/Article/details/gtnzwdpuon.html

ROLLBACK;
来源：http://dali.zhongyouzk.top/Article/details/gtgcvthltp.html

[Q66] 行锁查询
来源：http://dali.iojbl.cn/Article/details/gtyouikcrn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jiagoushi.top/Article/details/gtriqbbkym.html

[Q67] 设置隔离级别
来源：http://dali.bjfxy.top/Article/details/gtnftkhrec.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gzhubu.top/Article/details/gtptpxnzie.html

[Q68] 保存点
来源：http://dali.cheryme.top/Article/details/gtnhyczlgr.html

SAVEPOINT sp1;
来源：http://dali.cucudq.cn/Article/details/gtcpwwriaf.html

ROLLBACK TO sp1;
来源：http://dali.nanxinkj.top/Article/details/gtiaokcfzv.html

[Q69] 查看执行计划
来源：http://dali.316326.xyz/Article/details/gtzpvdvqgs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shanyushiyangkeji.top/Article/details/gttickfqxb.html

[Q70] 更新统计信息
来源：http://dali.jyoumei.cn/Article/details/gtlkstzftd.html

ANALYZE TABLE users;
来源：http://dali.svipenyu.cn/Article/details/gthofstemg.html

[Q71] 查看建表语句
来源：http://dali.sxryk.cn/Article/details/gtszpvixlk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.mhx1999.top/Article/details/gtuayjddfy.html

[Q72] 查看索引
来源：http://dali.hnqzz.top/Article/details/gtrrxqhaym.html

SHOW INDEX FROM users;
来源：http://dali.yueranfly.top/Article/details/gtotrtcxqf.html

[Q73] 查看表状态
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybdjkdzk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shuidangran.top/Article/details/gtwssbavas.html

[Q74] 强制使用索引
来源：http://dali.aizwys.cn/Article/details/gtywsnxabu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nanxinkj.top/Article/details/gttbonzmua.html

[Q75] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gtlcgurrdk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtpdlaydcd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yangfankeji.com/Article/details/gtrqwmeplf.html

[Q76] 按天统计
来源：http://dali.tian-w.cn/Article/details/gtrnxluatp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.haohaochexian.top/Article/details/gtbbiolquj.html

[Q77] 时间加减
来源：http://dali.snrcjt.cn/Article/details/gtksqrzjrh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jlsjyb.cn/Article/details/gtvwnknjxs.html

[Q78] 当前时间
来源：http://dali.xziqi.cn/Article/details/gtgtczzuvn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.feifeiyinyue.top/Article/details/gtynhzyqgy.html

[Q79] 字符串拼接
来源：http://dali.316326.xyz/Article/details/gtitjjaypl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjfoojgk.html

[Q80] 字符串截取
来源：http://dali.bjfxy.top/Article/details/gtankjmvhs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hammf.cn/Article/details/gtafhcgrui.html

[Q81] 字符串替换
来源：http://dali.cheryme.top/Article/details/gtojvxexwv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtzcfnkgvw.html

[Q82] 字符长度与字节长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyrgnbtgw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtomnjfhqy.html

[Q83] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gtptwiehrw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtczooarfz.html

[Q84] 去除首尾空格
来源：http://dali.svipenyu.cn/Article/details/gtgdjlqufj.html

SELECT TRIM(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtkzmeiqjy.html

[Q85] 数值取整
来源：http://dali.fzhhl.top/Article/details/gtdlsjxngg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nwbrower.top/Article/details/gtbennpqbg.html

[Q86] 读取 JSON 字段
来源：http://dali.nanxuanxn.top/Article/details/gtupzquusk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shuidangran.top/Article/details/gtbheftegd.html

[Q87] JSON 字段做条件
来源：http://dali.sufxvd.cn/Article/details/gtorpcdgys.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.quarkkingdee.top/Article/details/gtpdsldrws.html

[Q88] 行转列（条件聚合）
来源：http://dali.nanxinkj.top/Article/details/gtxvsmuwfy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gotoacloud.top/Article/details/gtmrsdathl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtbmvyscfx.html

[Q89] 判断表是否存在
来源：http://dali.yuanzhike.top/Article/details/gtoxqykqig.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yonumen.top/Article/details/gtgcutwjdo.html

[Q90] 生成序号列
来源：http://dali.xuanzx.com/Article/details/gtvzkwberq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.haohaochexian.top/Article/details/gtwecwrcld.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtagxqsiwf.html

R. Bash 专题
来源：http://dali.zycfv.cn/Article/details/gtyqggxqmw.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtfohkpvfi.html

[R01] shebang 与严格模式
来源：http://dali.shangyingyoupin.top/Article/details/gtgspiavgv.html

#!/usr/bin/env bash
来源：http://dali.hfpthk.cn/Article/details/gttnmxqozd.html

set -euo pipefail
来源：http://dali.tianlin.xyz/Article/details/gtdsyrgtvz.html

[R02] 变量赋值与使用
来源：http://dali.andypj.xyz/Article/details/gtdikfnbag.html

name="Tom"; echo "$name"
来源：http://dali.jiagoushi.top/Article/details/gtaqaketbi.html

[R03] 只读变量
来源：http://dali.nanxuanxn.top/Article/details/gtostskhty.html

readonly PI=3.14
来源：http://dali.c1oappe.top/Article/details/gtfcmlcvfc.html

[R04] 位置参数
来源：http://dali.smart0.xyz/Article/details/gtxwbszqge.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gaohongyu789.top/Article/details/gtufrximal.html

[R05] 参数默认值
来源：http://dali.yj202588.top/Article/details/gtdiuslmue.html

name="${1:-default}"
来源：http://dali.xylfe.cn/Article/details/gtosedovxy.html

[R06] 判断命令是否存在
来源：http://dali.hysaishi.cn/Article/details/gturwpeccw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gtakilkran.html

[R07] if 判断文件
来源：http://dali.gzhubu.top/Article/details/gtdnrvlyor.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.redwolf501.top/Article/details/gtrvksncvz.html

[R08] 数值比较
来源：http://dali.xziqi.cn/Article/details/gtecmcjaco.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.0kj1m.cn/Article/details/gtxtxfirxr.html

[R09] 字符串比较
来源：http://dali.guannengcc.top/Article/details/gtydumwpan.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuanzx.com/Article/details/gtiujyqhvz.html

[R10] 正则匹配
来源：http://dali.cashguo.top/Article/details/gtvqovvcba.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cashguo.top/Article/details/gtnpebtvlu.html

[R11] case 多分支
来源：http://dali.cdnleiting.top/Article/details/gtczmflqmy.html

case "$1" in
来源：http://dali.hnxiangtu.top/Article/details/gtmqgnsqta.html

start) echo "启动" ;;
来源：http://dali.yuxming.cn/Article/details/gtvosrdvpv.html

stop)  echo "停止" ;;
来源：http://dali.jiagoushi.top/Article/details/gtydavndiu.html

*)     echo "未知命令" ;;
来源：http://dali.zycfv.cn/Article/details/gtyzjtaczn.html

esac
来源：http://dali.bjfxy.top/Article/details/gtxzevsekh.html

[R12] for 遍历文件
来源：http://dali.sysykeji.top/Article/details/gtdypumkwj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gaohongyu789.top/Article/details/gtsatmpyjd.html

[R13] for 计数循环
来源：http://dali.tian-w.cn/Article/details/gtflavexcs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gtstzkclbx.html

[R14] C 风格 for
来源：http://dali.yj20258888.top/Article/details/gtgwklhsik.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcmywdiv.html

[R15] while 逐行读文件
来源：http://dali.316326.xyz/Article/details/gtlrcciaar.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrdnprpo.html

[R16] until 等待条件
来源：http://dali.redwolf501.top/Article/details/gtirxauvgx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.redwolf501.top/Article/details/gtcuzlditd.html

[R17] 数组定义与取值
来源：http://dali.zhengqikj.top/Article/details/gtstkdzyfh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nwbrower.top/Article/details/gtltwvjuge.html

[R18] 遍历数组
来源：http://dali.sysykeji.top/Article/details/gtcdtrlqvk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.fzhhl.top/Article/details/gtrthnmtut.html

[R19] 数组长度
来源：http://dali.birdmap.top/Article/details/gtiecjzxfg.html

echo "${#arr[@]}"
来源：http://dali.ehwqpu.com/Article/details/gtjdusfejg.html

[R20] 关联数组（字典）
来源：http://dali.jqgfzy.top/Article/details/gtnllqsytd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.quarkkingdee.top/Article/details/gtsvjprhgu.html

[R21] 字符串长度
来源：http://dali.xinyue.icu/Article/details/gteotkkgoh.html

echo "${#s}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfacwmxgk.html

[R22] 截取子串
来源：http://dali.jinghuilouyu.cn/Article/details/gthhcirirr.html

echo "${s:0:5}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqvqmqdx.html

[R23] 字符串替换
来源：http://dali.ivvv.top/Article/details/gtypxrzomy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sufxvd.cn/Article/details/gtzawlpbcz.html

[R24] 大小写转换
来源：http://dali.yongpay.top/Article/details/gtjcgzdwcx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.svipenyu.cn/Article/details/gtguyealdu.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuetiantiany.cn/Article/details/gtimhuqawb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.iojbl.cn/Article/details/gtuyoobprs.html

[R26] 命令替换
来源：http://dali.jlsjyb.cn/Article/details/gtbbjuoerh.html

now=$(date +%F); echo "$now"
来源：http://dali.yonumen.top/Article/details/gtlmrgvcmn.html

[R27] 算术展开
来源：http://dali.quarkkingdee.top/Article/details/gtesovcyap.html

echo $((1 + 2 * 3))
来源：http://dali.shangyingyoupin.top/Article/details/gtqgauvwac.html

[R28] 浮点运算
来源：http://dali.yj20258888.top/Article/details/gtygrvngsv.html

echo "scale=2; 10/3" | bc
来源：http://dali.hysaishi.cn/Article/details/gthvfddpnu.html

[R29] 定义函数
来源：http://dali.gogol.net.cn/Article/details/gtnzyfnqok.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.kuanghao11.cn/Article/details/gtvyngteku.html

[R30] 函数返回状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdzrgtjyw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhixingplan.top/Article/details/gtdgdnjkna.html

[R31] 局部变量
来源：http://dali.andypj.xyz/Article/details/gtfetaukre.html

f() { local x=1; echo "$x"; }
来源：http://dali.yongpay.top/Article/details/gtjpimdvgl.html

[R32] 参数个数校验
来源：http://dali.316326.xyz/Article/details/gtgidscycq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shzxlz.cn/Article/details/gtqkduspkx.html

[R33] 捕获错误并提示行号
来源：http://dali.hysaishi.cn/Article/details/gtezpsdwpo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gaohongyu789.top/Article/details/gtyjzsxsli.html

[R34] 退出时清理
来源：http://dali.gaohongyu789.top/Article/details/gttcfzwgdt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gthsjzkcjf.html

[R35] 后台执行并等待
来源：http://dali.mhx1999.top/Article/details/gtzxienecz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgfzy.top/Article/details/gtczdkqicf.html

[R36] 并发执行多个任务
来源：http://dali.xuanzx.com/Article/details/gtrwmtltbp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daria6918.cn/Article/details/gtcqzuvbku.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtcssxhmkp.html

files=$(ls -1)
来源：http://dali.zycfv.cn/Article/details/gtfoinzcjj.html

[R38] 管道串联
来源：http://dali.daria6918.cn/Article/details/gtowanynwq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgfzy.top/Article/details/gthggusnox.html

[R39] 重定向标准输出与错误
来源：http://dali.316326.xyz/Article/details/gtglydpjoq.html

cmd > out.log 2>&1
来源：http://dali.guannengcc.top/Article/details/gtybkmjfrx.html

[R40] 追加写日志
来源：http://dali.nwbrower.top/Article/details/gtkqokuhfv.html

echo "log" >> out.log
来源：http://dali.chenlongwang.top/Article/details/gtrlotxsdd.html

[R41] 丢弃输出
来源：http://dali.tianlin.xyz/Article/details/gtprtbfhrr.html

cmd >/dev/null 2>&1
来源：http://dali.jianghu66.top/Article/details/gtevpoyjro.html

[R42] 输入重定向
来源：http://dali.yvedp.cn/Article/details/gtzlidrkty.html

wc -l < a.txt
来源：http://dali.sysykeji.top/Article/details/gtvqdglpiv.html

[R43] 按名字查找文件
来源：http://dali.daxiang520.top/Article/details/gtcrzdnawv.html

find . -name "*.log" -type f
来源：http://dali.zdqjudy.top/Article/details/gtnhmwlscu.html

[R44] 按修改时间查找
来源：http://dali.yvedp.cn/Article/details/gtvtrjoqpt.html

find . -mtime -7 -type f
来源：http://dali.nanxuanxn.top/Article/details/gtjfiexope.html

[R45] 批量删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjbuvlsu.html

find . -name "*.tmp" -delete
来源：http://dali.zhaomingkeji.xyz/Article/details/gtducrlmli.html

[R46] 递归替换文件内容
来源：http://dali.c1oappe.top/Article/details/gtpbxpjtdr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.birdmap.top/Article/details/gtnrfjgnzs.html

[R47] sed 单行替换
来源：http://dali.redwolf501.top/Article/details/gtxaiclrgx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hnqzz.top/Article/details/gtqnvyxcwc.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gtyjnivhrj.html

awk '{print $1, $3}' a.txt
来源：http://dali.daria6918.cn/Article/details/gtqwhlprkr.html

[R49] awk 带条件
来源：http://dali.chenjidiqi.icu/Article/details/gtbolprzpy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sxryk.cn/Article/details/gtknudkxfu.html

[R50] awk 求和
来源：http://dali.haohaochexian.top/Article/details/gtkjhghrga.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbvtgrbv.html

[R51] 排序去重取前几
来源：http://dali.xinyue.icu/Article/details/gterczvbkv.html


<!-- 参考信息 -->