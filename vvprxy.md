代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhoulong.xyz/Article/details/gtopsritbh.html

[Q05] 重命名列
来源：http://dali.pengpengdd.cyou/Article/details/gtsxourqfl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtilgqfzjq.html

[Q06] 删除列
来源：http://dali.daxiang520.top/Article/details/gtvoupiguj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nanxinkj.top/Article/details/gtrvthgezr.html

[Q07] 删除表
来源：http://dali.yvedp.cn/Article/details/gtzyfzuays.html

DROP TABLE IF EXISTS orders;
来源：http://dali.bjfxy.top/Article/details/gtovwkulvz.html

[Q08] 创建普通索引
来源：http://dali.wangdashe.top/Article/details/gtltoaigmi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyuqfrjys.html

[Q09] 创建唯一索引
来源：http://dali.nwbrower.top/Article/details/gtlihzudpx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gtmrgznidd.html

[Q10] 插入单行
来源：http://dali.wangshuangyany.cn/Article/details/gtlppekufn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcoxoerp.html

[Q11] 一次插入多行
来源：http://dali.jinghuilouyu.cn/Article/details/gthcxlydbw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dianchejie.cn/Article/details/gtusihdoai.html

[Q12] 插入后取自增 ID
来源：http://dali.yueranfly.top/Article/details/gtohlgyzdl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cdnleiting.top/Article/details/gtfyezrhhm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nwbrower.top/Article/details/gtmsozfiok.html

[Q13] 忽略重复插入
来源：http://dali.xinyue.icu/Article/details/gtctzhbpiu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gtcyxjzngl.html

[Q14] 存在则更新（upsert）
来源：http://dali.sysykeji.top/Article/details/gtghpzbkxg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ppjwa.cn/Article/details/gthwwvacjt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.meibo888.top/Article/details/gtaesvkqtn.html

[Q15] 查询全部
来源：http://dali.nanxuanxn.top/Article/details/gtfibsfxpy.html

SELECT * FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtfiiiwawc.html

[Q16] 查询指定列
来源：http://dali.ydzc1.top/Article/details/gtztwzimbs.html

SELECT id, name FROM users;
来源：http://dali.fzhhl.top/Article/details/gtjfvxyeiq.html

[Q17] 条件查询
来源：http://dali.chenzaomai.com/Article/details/gtarloktnc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.havefunace.top/Article/details/gtwlyyeasm.html

[Q18] 模糊匹配
来源：http://dali.gzhubu.top/Article/details/gtdjdhvuza.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nwbrower.top/Article/details/gtvhbornuk.html

[Q19] 范围查询
来源：http://dali.ivvv.top/Article/details/gtgnvbjvjh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinghuilouyu.cn/Article/details/gtivxiucyn.html

[Q20] IN 列表
来源：http://dali.chenjidiqi.icu/Article/details/gtvymmeazp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tanke756.top/Article/details/gtdgolsqxb.html

[Q21] 空值判断
来源：http://dali.yuxming.cn/Article/details/gteudwdnds.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.wangdashe.top/Article/details/gtpzopzbwm.html

[Q22] 排序
来源：http://dali.pycfn.com/Article/details/gtouesmdcw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.havefunace.top/Article/details/gtjppbyzop.html

[Q23] 分页
来源：http://dali.quarkkingdee.top/Article/details/gtxiinyudg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yangfankeji.com/Article/details/gtuwysdnho.html

[Q24] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtwewedpbv.html

SELECT DISTINCT city FROM users;
来源：http://dali.cheryme.top/Article/details/gtwukibgij.html

[Q25] 只取前 N 条
来源：http://dali.zhiwuduotai.top/Article/details/gtphztsbeb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daxiang520.top/Article/details/gtwfdowrls.html

[Q26] 计数
来源：http://dali.aibaodan.cn/Article/details/gtwthacnwq.html

SELECT COUNT(*) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtgzomvtqt.html

[Q27] 条件计数
来源：http://dali.ehwqpu.com/Article/details/gtazennfpe.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gthzqwiqtm.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwzyweox.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtmulwowtr.html

[Q29] 最大最小值
来源：http://dali.nanxuanxn.top/Article/details/gtofxdyhps.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtbcqaqokw.html

[Q30] 分组统计
来源：http://dali.gaohongyu789.top/Article/details/gtguzktymo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtnkpiapel.html

[Q31] 分组后过滤
来源：http://dali.0kj1m.cn/Article/details/gtmahjiqjc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.pycfn.com/Article/details/gtiqplnrus.html

[Q32] 分组拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gtxzaplmdp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtbhmpkkyx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.kuanghao11.cn/Article/details/gtltojdpjy.html

[Q33] 多列分组
来源：http://dali.jinqigufen.top/Article/details/gtwwqoaffu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cheryme.top/Article/details/gtbkllgdqo.html

[Q34] 每组取第一条
来源：http://dali.sxryk.cn/Article/details/gtojrsehgo.html

SELECT * FROM (
来源：http://dali.chenzaomai.com/Article/details/gtcidqazlo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ydzc1.top/Article/details/gtmdygvzre.html

) t WHERE rn = 1;
来源：http://dali.xinyue.icu/Article/details/gtusamdqgz.html

[Q35] 内连接
来源：http://dali.yanxiufei.cn/Article/details/gtmxelarpm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gtgbaqybsf.html

[Q36] 左连接
来源：http://dali.yj20258888.top/Article/details/gtzrjvjukj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daxiang520.top/Article/details/gttvhgsyzt.html

[Q37] 右连接
来源：http://dali.ppjwa.cn/Article/details/gtohxkisdo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cheryme.top/Article/details/gtbqwxbetn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgxvugyn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenlongwang.top/Article/details/gtyidhfimd.html

[Q39] 自连接（查上下级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjyogjnpt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guowangkeji.top/Article/details/gtckaayemi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shuidangran.top/Article/details/gtombxppjm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.kuanghao11.cn/Article/details/gtcfwaeyaj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xylfe.cn/Article/details/gtaqeulgnk.html

[Q41] 多表连接
来源：http://dali.feifeiyinyue.top/Article/details/gtmouzxidl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.svipenyu.cn/Article/details/gtvqkjcdjb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.c1oappe.top/Article/details/gtgmrkryoc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gtommujnks.html

[Q42] 连接条件附加过滤
来源：http://dali.gzhubu.top/Article/details/gtpgunviei.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cqqwz.cn/Article/details/gtbiixkimb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnxiangtu.top/Article/details/gtmrcclgsw.html

[Q43] 标量子查询
来源：http://dali.aizwys.cn/Article/details/gtsjqqqxxh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yj20258888.top/Article/details/gtplhpzkvs.html

[Q44] IN 子查询
来源：http://dali.aibaodan.cn/Article/details/gtkzgurfic.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shzxlz.cn/Article/details/gtfxdphcvz.html

[Q45] EXISTS 判断存在
来源：http://dali.ybcxt.top/Article/details/gtjfrvjnne.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tianlin.xyz/Article/details/gtfvrepxhh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yongpay.top/Article/details/gtfqnstfeq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gtjjidbdiu.html

[Q47] 与平均值比较
来源：http://dali.kuanghao11.cn/Article/details/gtcvkukibc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.feifeiyinyue.top/Article/details/gtoymkegyl.html

[Q48] CTE 公用表表达式
来源：http://dali.zycfv.cn/Article/details/gtlmumgyjb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ehwqpu.com/Article/details/gtvstmygii.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkbpzxtd.html

[Q49] 更新单行
来源：http://dali.zhiwuduotai.top/Article/details/gtjzjotpos.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sweek.top/Article/details/gtcnuounwm.html

[Q50] 批量更新
来源：http://dali.yanxiufei.cn/Article/details/gtopgxpybn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.mhx1999.top/Article/details/gtgtyoqpoz.html

[Q51] 用子查询更新
来源：http://dali.cheryme.top/Article/details/gtlnpndkdv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenzaomai.com/Article/details/gtyvbhsecw.html

[Q52] 删除指定行
来源：http://dali.haohaochexian.top/Article/details/gtdtaakuxi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.redwolf501.top/Article/details/gtyurojkdx.html

[Q53] 按条件删除
来源：http://dali.ybcxt.top/Article/details/gtzxqskyzu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.iojbl.cn/Article/details/gtcayjldlt.html

[Q54] 清空表
来源：http://dali.yuanzhike.top/Article/details/gtioddxooo.html

TRUNCATE TABLE logs;
来源：http://dali.ivvv.top/Article/details/gtxozdwrye.html

[Q55] 排名（并列占位）
来源：http://dali.wangshuangyany.cn/Article/details/gtwgmggtkg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cdnleiting.top/Article/details/gtmuhiukfe.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigfzy.top/Article/details/gtmqqobcgu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.pengpengdd.cyou/Article/details/gtkftpkele.html

[Q57] 行号
来源：http://dali.316326.xyz/Article/details/gtmkssgfmx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtndgyvsfh.html

[Q58] 累计求和
来源：http://dali.yuanzhike.top/Article/details/gtqfbfwtic.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtbvnfgpke.html

[Q59] 分组内累计
来源：http://dali.andypj.xyz/Article/details/gtxqqjzrnt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtxshwychv.html

[Q60] 取上一行 / 下一行
来源：http://dali.0kj1m.cn/Article/details/gtkfivoans.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gaohongyu789.top/Article/details/gtmnicdemm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtaogjvgvk.html

[Q61] 移动平均
来源：http://dali.ehwqpu.com/Article/details/gtiimjbzow.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgdgfzak.html

[Q62] 分组占比
来源：http://dali.hfpthk.cn/Article/details/gtnerxsugi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gtppwqomph.html

[Q63] 开启事务
来源：http://dali.hfpthk.cn/Article/details/gtcqnrzzkc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zdqjudy.top/Article/details/gtjsyjchrz.html

[Q64] 提交事务
来源：http://dali.vqdsnc.cn/Article/details/gtiehvidlv.html

COMMIT;
来源：http://dali.zhongyouzk.top/Article/details/gtgplxtpvp.html

[Q65] 回滚事务
来源：http://dali.tian-w.cn/Article/details/gtjmnwlcxc.html

ROLLBACK;
来源：http://dali.guannengcc.top/Article/details/gtemguejci.html

[Q66] 行锁查询
来源：http://dali.yueranfly.top/Article/details/gtqidyxwxm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yueranfly.top/Article/details/gtijitgpts.html

[Q67] 设置隔离级别
来源：http://dali.kuanghao11.cn/Article/details/gtgfewpnww.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgufenzy.top/Article/details/gtsddgumpe.html

[Q68] 保存点
来源：http://dali.tanke756.top/Article/details/gtnpawmwia.html

SAVEPOINT sp1;
来源：http://dali.chenzaomai.com/Article/details/gtaeyponqh.html

ROLLBACK TO sp1;
来源：http://dali.gogol.net.cn/Article/details/gtojozveiz.html

[Q69] 查看执行计划
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjuwgjmok.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nanxuanxn.top/Article/details/gtorubjswx.html

[Q70] 更新统计信息
来源：http://dali.jinqigfzy.top/Article/details/gtkuehvkzc.html

ANALYZE TABLE users;
来源：http://dali.yonumen.top/Article/details/gtzrawvjqx.html

[Q71] 查看建表语句
来源：http://dali.svipenyu.cn/Article/details/gtpikeatwg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinyuanbaomall.cn/Article/details/gtganhktif.html

[Q72] 查看索引
来源：http://dali.yuanzhike.top/Article/details/gtzkfxbkmj.html

SHOW INDEX FROM users;
来源：http://dali.guannengcc.top/Article/details/gtuslvffiq.html

[Q73] 查看表状态
来源：http://dali.hammf.cn/Article/details/gtfndharfc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hnxiangtu.top/Article/details/gtjyyylqjh.html

[Q74] 强制使用索引
来源：http://dali.dashuyun.cn/Article/details/gtlwfphehl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gtohoqsztd.html

[Q75] 日期格式化
来源：http://dali.tanke756.top/Article/details/gthrnumurq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtqidkednk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.pycfn.com/Article/details/gtrqggfeaj.html

[Q76] 按天统计
来源：http://dali.ivvv.top/Article/details/gtejplvpdn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.fzhhl.top/Article/details/gtjpxukpjz.html

[Q77] 时间加减
来源：http://dali.yuxming.cn/Article/details/gtplgtywud.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shzxlz.cn/Article/details/gtyeluklji.html

[Q78] 当前时间
来源：http://dali.zdqjudy.top/Article/details/gtsdtdaueb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hnqzz.top/Article/details/gthxgnixqc.html

[Q79] 字符串拼接
来源：http://dali.tianlin.xyz/Article/details/gtayfcdjhz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aizwys.cn/Article/details/gtvscrqspu.html

[Q80] 字符串截取
来源：http://dali.zhiwuduotai.top/Article/details/gtcgrhxlxg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yonumen.top/Article/details/gtrqzvqybd.html

[Q81] 字符串替换
来源：http://dali.cqqwz.cn/Article/details/gtuddlsisy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtlrcvfuuz.html

[Q82] 字符长度与字节长度
来源：http://dali.cheryme.top/Article/details/gtvxgxqpnj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtkdudmzpf.html

[Q83] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gtjrygxpkn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gttpxsiyvk.html

[Q84] 去除首尾空格
来源：http://dali.cheryme.top/Article/details/gtbtswadit.html

SELECT TRIM(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtvkvulkgv.html

[Q85] 数值取整
来源：http://dali.jyoumei.cn/Article/details/gtguhirvcp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xziqi.cn/Article/details/gthothjnoz.html

[Q86] 读取 JSON 字段
来源：http://dali.9152youxi.cn/Article/details/gtpvvkdsqk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxinkj.top/Article/details/gtplfzehdl.html

[Q87] JSON 字段做条件
来源：http://dali.aizwys.cn/Article/details/gtzhfpaxuz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenlongwang.top/Article/details/gtpdiewwtq.html

[Q88] 行转列（条件聚合）
来源：http://dali.quarkkingdee.top/Article/details/gtxtcsptkt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gaohongyu789.top/Article/details/gtdrnixwdc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtrzfcvfjt.html

[Q89] 判断表是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtddbpvkml.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cheryme.top/Article/details/gtmvkpwekq.html

[Q90] 生成序号列
来源：http://dali.sysykeji.top/Article/details/gthxwyiksx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj20258.top/Article/details/gtpmblgaus.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtdluwnoyr.html

R. Bash 专题
来源：http://dali.dashuyun.cn/Article/details/gtyyrfuxma.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gthwvhwgwg.html

[R01] shebang 与严格模式
来源：http://dali.gogol.net.cn/Article/details/gtbhucnoql.html

#!/usr/bin/env bash
来源：http://dali.yj20258888.top/Article/details/gtmneuzktj.html

set -euo pipefail
来源：http://dali.sxryk.cn/Article/details/gtclwdtdjc.html

[R02] 变量赋值与使用
来源：http://dali.redwolf501.top/Article/details/gtxbtfijmh.html

name="Tom"; echo "$name"
来源：http://dali.jyoumei.cn/Article/details/gtzpvhyofa.html

[R03] 只读变量
来源：http://dali.wangshuangyany.cn/Article/details/gtxnuprcjs.html

readonly PI=3.14
来源：http://dali.svipenyu.cn/Article/details/gtpdlvzwfl.html

[R04] 位置参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzdjkxchb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnxiangtu.top/Article/details/gtsejgogmy.html

[R05] 参数默认值
来源：http://dali.gzhubu.top/Article/details/gtoyqxsatn.html

name="${1:-default}"
来源：http://dali.birdmap.top/Article/details/gtijtyzerw.html

[R06] 判断命令是否存在
来源：http://dali.daxiang520.top/Article/details/gtnxtspufj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gtsrqusmsr.html

[R07] if 判断文件
来源：http://dali.gaohongyu789.top/Article/details/gtmxryjwvl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pycfn.com/Article/details/gtjowltsyx.html

[R08] 数值比较
来源：http://dali.dianchejie.cn/Article/details/gtywwgefxe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.svipenyu.cn/Article/details/gtvrketpfu.html

[R09] 字符串比较
来源：http://dali.cashguo.top/Article/details/gtnagzusea.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtyriopect.html

[R10] 正则匹配
来源：http://dali.yuxming.cn/Article/details/gtqgsptmkl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cqqwz.cn/Article/details/gtdmgtnroz.html

[R11] case 多分支
来源：http://dali.chenzaomai.com/Article/details/gtdtsewjsf.html

case "$1" in
来源：http://dali.vqdsnc.cn/Article/details/gtqkvgnppc.html

start) echo "启动" ;;
来源：http://dali.yvedp.cn/Article/details/gtsdrxowce.html

stop)  echo "停止" ;;
来源：http://dali.ehwqpu.com/Article/details/gtjqyvttlo.html

*)     echo "未知命令" ;;
来源：http://dali.zhengqikj.top/Article/details/gtmzeclket.html

esac
来源：http://dali.ehwqpu.com/Article/details/gtdfdccesu.html

[R12] for 遍历文件
来源：http://dali.shuidangran.top/Article/details/gtbntuqnkf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtqwakcfon.html

[R13] for 计数循环
来源：http://dali.zdqjudy.top/Article/details/gtgtczadwo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqwwkmcq.html

[R14] C 风格 for
来源：http://dali.guannengcc.top/Article/details/gtkrtjzgmx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtkvckwjad.html

[R15] while 逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtmfwtosyw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yueranfly.top/Article/details/gtqrtzyiaw.html

[R16] until 等待条件
来源：http://dali.zhengqikj.top/Article/details/gtoexbtmtu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gtkkdlddtr.html

[R17] 数组定义与取值
来源：http://dali.hongshengwenyu.top/Article/details/gtwpxolshv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xinyue.icu/Article/details/gtvyimjzgz.html

[R18] 遍历数组
来源：http://dali.tian-w.cn/Article/details/gtgfabgvxw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.kuanghao11.cn/Article/details/gtqfkbqoib.html

[R19] 数组长度
来源：http://dali.yj20258.top/Article/details/gtcphurefr.html

echo "${#arr[@]}"
来源：http://dali.316326.xyz/Article/details/gtrpdkkwbu.html

[R20] 关联数组（字典）
来源：http://dali.sufxvd.cn/Article/details/gtpgzlcicr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sysykeji.top/Article/details/gtvzqenjtw.html

[R21] 字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gtllhfxdgs.html

echo "${#s}"
来源：http://dali.ehwqpu.com/Article/details/gtukolpdvd.html

[R22] 截取子串
来源：http://dali.yonumen.top/Article/details/gtbeyrosqo.html

echo "${s:0:5}"
来源：http://dali.cheryme.top/Article/details/gtfrjrqkli.html

[R23] 字符串替换
来源：http://dali.xuetiantiany.cn/Article/details/gtvxcklsvp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tian-w.cn/Article/details/gthiycmkld.html

[R24] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gtbtrbjwde.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.kuanghao11.cn/Article/details/gtxztyznae.html

[R25] 去后缀 / 去前缀
来源：http://dali.ydzc1.top/Article/details/gtkqvnvizj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.guowangkeji.top/Article/details/gtiptyzysq.html

[R26] 命令替换
来源：http://dali.hywenlv.cn/Article/details/gttovknytk.html

now=$(date +%F); echo "$now"
来源：http://dali.redwolf501.top/Article/details/gtyanzuatl.html

[R27] 算术展开
来源：http://dali.fengsongda.top/Article/details/gtkikhdasy.html

echo $((1 + 2 * 3))
来源：http://dali.yj202588.top/Article/details/gtbzmulqzj.html

[R28] 浮点运算
来源：http://dali.yj202588.top/Article/details/gtxojjhtmk.html

echo "scale=2; 10/3" | bc
来源：http://dali.jianghu66.top/Article/details/gtiiwwdbaz.html

[R29] 定义函数
来源：http://dali.sufxvd.cn/Article/details/gtcizrbeta.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hammf.cn/Article/details/gtendynnub.html

[R30] 函数返回状态码
来源：http://dali.jinqigufen.top/Article/details/gtzhwjqolo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ydzc1.top/Article/details/gtnylekwhk.html

[R31] 局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gtztkiqgic.html

f() { local x=1; echo "$x"; }
来源：http://dali.andypj.xyz/Article/details/gtdhwpxomy.html

[R32] 参数个数校验
来源：http://dali.mhx1999.top/Article/details/gtsnhsgqfy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gtnxdpojuw.html

[R33] 捕获错误并提示行号
来源：http://dali.hywenlv.cn/Article/details/gtptmvoiqi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xziqi.cn/Article/details/gtkhwbfwtr.html

[R34] 退出时清理
来源：http://dali.ehwqpu.com/Article/details/gtdowbupwc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gtmlwzptxl.html

[R35] 后台执行并等待
来源：http://dali.ppjwa.cn/Article/details/gtnnnjxqpy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dianchejie.cn/Article/details/gtcvoruqbw.html

[R36] 并发执行多个任务
来源：http://dali.zhengqikj.top/Article/details/gtqappsxgz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zdqjudy.top/Article/details/gtetvbmptx.html

[R37] 把输出赋给变量
来源：http://dali.havefunace.top/Article/details/gtpxewvcxj.html

files=$(ls -1)
来源：http://dali.0kj1m.cn/Article/details/gtufqwhtmm.html

[R38] 管道串联
来源：http://dali.0kj1m.cn/Article/details/gtqtuoxkum.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhqejbsy.html

[R39] 重定向标准输出与错误
来源：http://dali.fzhhl.top/Article/details/gthjkyjhnh.html

cmd > out.log 2>&1
来源：http://dali.gotoacloud.top/Article/details/gtfuolqgva.html

[R40] 追加写日志
来源：http://dali.tianlin.xyz/Article/details/gtuvlxuylm.html

echo "log" >> out.log
来源：http://dali.xylfe.cn/Article/details/gtzzbmbehu.html

[R41] 丢弃输出
来源：http://dali.svipenyu.cn/Article/details/gtqzuvseyf.html

cmd >/dev/null 2>&1
来源：http://dali.pycfn.com/Article/details/gtiqaskxdw.html

[R42] 输入重定向
来源：http://dali.redwolf501.top/Article/details/gtwutzsepk.html

wc -l < a.txt
来源：http://dali.dianchejie.cn/Article/details/gtbchszjeq.html

[R43] 按名字查找文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxtgaihf.html

find . -name "*.log" -type f
来源：http://dali.sysykeji.top/Article/details/gtbpzrpfoy.html

[R44] 按修改时间查找
来源：http://dali.sufxvd.cn/Article/details/gtgdoewuqz.html

find . -mtime -7 -type f
来源：http://dali.wangshuangyany.cn/Article/details/gtzxoglbkt.html

[R45] 批量删除
来源：http://dali.xinyue.icu/Article/details/gtnmctzpkx.html

find . -name "*.tmp" -delete
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccloaefi.html

[R46] 递归替换文件内容
来源：http://dali.cucudq.cn/Article/details/gtughyppnn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj202588.top/Article/details/gttkgxpbzr.html

[R47] sed 单行替换
来源：http://dali.dianchejie.cn/Article/details/gtrrhuispr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guannengcc.top/Article/details/gtjbouimmb.html

[R48] awk 取指定列
来源：http://dali.pycfn.com/Article/details/gtuboauvbr.html

awk '{print $1, $3}' a.txt
来源：http://dali.tanke756.top/Article/details/gtxtersnds.html

[R49] awk 带条件
来源：http://dali.havefunace.top/Article/details/gtqkqkzznl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.pengpengdd.cyou/Article/details/gtpjmxytqz.html

[R50] awk 求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoukirxlc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtgmtthoee.html

[R51] 排序去重取前几
来源：http://dali.sysykeji.top/Article/details/gtzjauphrh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenlongwang.top/Article/details/gtfgrjxkow.html

[R52] 统计行数
来源：http://dali.c1oappe.top/Article/details/gtkfiawohk.html

wc -l a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtzklxeuml.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgfzy.top/Article/details/gtrpnpcpbn.html


<!-- 参考信息 -->