代发 wailian999

);
来源：http://dali.c1oappe.top/Article/details/gteeenrqzv.html

[Q03] 增加列
来源：http://dali.zhiwuduotai.top/Article/details/gtusfoskjg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhiwuduotai.top/Article/details/gtqhnufnnx.html

[Q04] 修改列类型
来源：http://dali.ppjwa.cn/Article/details/gtuoxhjncn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zdqjudy.top/Article/details/gtywqqycgh.html

[Q05] 重命名列
来源：http://dali.quarkkingdee.top/Article/details/gtszeheufi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shuidangran.top/Article/details/gtommghztv.html

[Q06] 删除列
来源：http://dali.chenzaomai.com/Article/details/gtyerdjdil.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hammf.cn/Article/details/gtvthnofvz.html

[Q07] 删除表
来源：http://dali.pengpengdd.cyou/Article/details/gtaymtwpws.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jianghu66.top/Article/details/gtlpeinzhf.html

[Q08] 创建普通索引
来源：http://dali.aibaodan.cn/Article/details/gtsezmtpsf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sweek.top/Article/details/gtlzplilya.html

[Q09] 创建唯一索引
来源：http://dali.nanxuanxn.top/Article/details/gtpxkwtgli.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.redwolf501.top/Article/details/gtzljtrxhj.html

[Q10] 插入单行
来源：http://dali.bjfxy.top/Article/details/gtrznatxfx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcapkwczh.html

[Q11] 一次插入多行
来源：http://dali.tian-w.cn/Article/details/gtwudqersa.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ivvv.top/Article/details/gthdocrpzj.html

[Q12] 插入后取自增 ID
来源：http://dali.shangyingyoupin.top/Article/details/gtehzgedqq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.quarkkingdee.top/Article/details/gtqunvnswk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigufen.top/Article/details/gtxonjunhb.html

[Q13] 忽略重复插入
来源：http://dali.zdqjudy.top/Article/details/gtqhbtebod.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shuidangran.top/Article/details/gttnezajtt.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinghuilouyu.cn/Article/details/gtclhzcgmp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hammf.cn/Article/details/gtdffrzjtw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhoulong.xyz/Article/details/gtcbtmwenb.html

[Q15] 查询全部
来源：http://dali.dashuyun.cn/Article/details/gtivyclteb.html

SELECT * FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtfxbdynfc.html

[Q16] 查询指定列
来源：http://dali.nanxuanxn.top/Article/details/gtkfhxxcha.html

SELECT id, name FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtxwvdluyh.html

[Q17] 条件查询
来源：http://dali.feifeiyinyue.top/Article/details/gtmozllwnw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jianghu66.top/Article/details/gtrvvpwrfe.html

[Q18] 模糊匹配
来源：http://dali.yueranfly.top/Article/details/gtxtggdtso.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzussgeps.html

[Q19] 范围查询
来源：http://dali.9152youxi.cn/Article/details/gteqrlgdzh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jyoumei.cn/Article/details/gtlqwulzoh.html

[Q20] IN 列表
来源：http://dali.yj202588.top/Article/details/gtrgmzditn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yonumen.top/Article/details/gthoaozzto.html

[Q21] 空值判断
来源：http://dali.sxryk.cn/Article/details/gtkydcskko.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ppjwa.cn/Article/details/gtkgonaped.html

[Q22] 排序
来源：http://dali.pycfn.com/Article/details/gtlhuefusb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nanxuanxn.top/Article/details/gtvmibfjzc.html

[Q23] 分页
来源：http://dali.yuxming.cn/Article/details/gtkagkiova.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhengqikj.top/Article/details/gtbbmcxjgy.html

[Q24] 去重
来源：http://dali.xuanzx.com/Article/details/gtxckdtyix.html

SELECT DISTINCT city FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtqilsnlao.html

[Q25] 只取前 N 条
来源：http://dali.yj20258888.top/Article/details/gtudqolthk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.meibo888.top/Article/details/gtjfpnytjr.html

[Q26] 计数
来源：http://dali.chenzaomai.com/Article/details/gtmxsoixxr.html

SELECT COUNT(*) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtovvsyqlp.html

[Q27] 条件计数
来源：http://dali.yvedp.cn/Article/details/gtmdxwiwvm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cashguo.top/Article/details/gtqokepdky.html

[Q28] 求和与平均
来源：http://dali.daxiang520.top/Article/details/gtnuntfqsg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtpotwehjl.html

[Q29] 最大最小值
来源：http://dali.jqgfzy.top/Article/details/gtlznjvwpd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtqxluglha.html

[Q30] 分组统计
来源：http://dali.jianghu66.top/Article/details/gtfauqnins.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gtmswvtray.html

[Q31] 分组后过滤
来源：http://dali.guowangkeji.top/Article/details/gtxxvnoibu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtinxcudpo.html

[Q32] 分组拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gthpcufgld.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtpuebidqm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhoulong.xyz/Article/details/gtgiqmgmpq.html

[Q33] 多列分组
来源：http://dali.zhiwuduotai.top/Article/details/gtehdzpdps.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.wangdashe.top/Article/details/gtmrcqeboh.html

[Q34] 每组取第一条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxrgylka.html

SELECT * FROM (
来源：http://dali.shuidangran.top/Article/details/gtlrgailkn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ivvv.top/Article/details/gtgkwkipfp.html

) t WHERE rn = 1;
来源：http://dali.sweek.top/Article/details/gtknlcottu.html

[Q35] 内连接
来源：http://dali.ppjwa.cn/Article/details/gtxmdtsxwf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuopciewi.html

[Q36] 左连接
来源：http://dali.zdqjudy.top/Article/details/gtakbmkkft.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.iojbl.cn/Article/details/gtvqeaaiuk.html

[Q37] 右连接
来源：http://dali.yanxiufei.cn/Article/details/gtafjptpeb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xziqi.cn/Article/details/gtwclippzp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gotoacloud.top/Article/details/gtaxrkjduh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangdashe.top/Article/details/gtnhmtzmmh.html

[Q39] 自连接（查上下级）
来源：http://dali.cqqwz.cn/Article/details/gtebuisymn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daxiang520.top/Article/details/gtrydduedw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tian-w.cn/Article/details/gtljusaawk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.birdmap.top/Article/details/gtztbopgne.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jyoumei.cn/Article/details/gtahmafeif.html

[Q41] 多表连接
来源：http://dali.yangfankeji.com/Article/details/gtsotpuzka.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.havefunace.top/Article/details/gthhysoykt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jianghu66.top/Article/details/gtvbmqflof.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nanxuanxn.top/Article/details/gtpencgyhb.html

[Q42] 连接条件附加过滤
来源：http://dali.xinyue.icu/Article/details/gtkgoyjkhh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sxryk.cn/Article/details/gttibksekr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fengsongda.top/Article/details/gtreoeokwf.html

[Q43] 标量子查询
来源：http://dali.daria6918.cn/Article/details/gteacpwlcc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cdnleiting.top/Article/details/gtdieyrurr.html

[Q44] IN 子查询
来源：http://dali.hfpthk.cn/Article/details/gtgjigsnnt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gzhubu.top/Article/details/gtpwoxeyne.html

[Q45] EXISTS 判断存在
来源：http://dali.cashguo.top/Article/details/gtcwssqeiu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.vqdsnc.cn/Article/details/gtfqituwti.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hongshengwenyu.top/Article/details/gtbeeoeemd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gtymqjxexh.html

[Q47] 与平均值比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvptodtz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jyoumei.cn/Article/details/gtdpbfplnh.html

[Q48] CTE 公用表表达式
来源：http://dali.xylfe.cn/Article/details/gtmwyyghnt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gttutbvezj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cheryme.top/Article/details/gtzhyocrwt.html

[Q49] 更新单行
来源：http://dali.ydzc1.top/Article/details/gtkaqbaxmx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.mhx1999.top/Article/details/gtdkgrxorn.html

[Q50] 批量更新
来源：http://dali.zhixingplan.top/Article/details/gttxrsblgs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sufxvd.cn/Article/details/gtmieeepof.html

[Q51] 用子查询更新
来源：http://dali.cdnleiting.top/Article/details/gtvfytclyt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtladcvwpz.html

[Q52] 删除指定行
来源：http://dali.dianchejie.cn/Article/details/gtolkpaxnk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hnxiangtu.top/Article/details/gtxqmvqckb.html

[Q53] 按条件删除
来源：http://dali.jlsjyb.cn/Article/details/gtpthwqokb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.aibaodan.cn/Article/details/gtumzpodnd.html

[Q54] 清空表
来源：http://dali.nanxinkj.top/Article/details/gttirskcrb.html

TRUNCATE TABLE logs;
来源：http://dali.yangfankeji.com/Article/details/gtwvnlepcn.html

[Q55] 排名（并列占位）
来源：http://dali.xinyue.icu/Article/details/gtrvtzsevd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtrcyfeyhs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guannengcc.top/Article/details/gtawgbuuvo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.bjfxy.top/Article/details/gtbhlkqooj.html

[Q57] 行号
来源：http://dali.shanyushiyangtech.top/Article/details/gtimayneph.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gotoacloud.top/Article/details/gthbxdghrc.html

[Q58] 累计求和
来源：http://dali.quarkkingdee.top/Article/details/gteugavrma.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtfehnrkyx.html

[Q59] 分组内累计
来源：http://dali.zhixingplan.top/Article/details/gtynxjwfgw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtxvseoptc.html

[Q60] 取上一行 / 下一行
来源：http://dali.cashguo.top/Article/details/gtjrznepnn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.iojbl.cn/Article/details/gtqvluqubj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtkeihxfft.html

[Q61] 移动平均
来源：http://dali.xylfe.cn/Article/details/gtyaxglxyc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtemuxwrva.html

[Q62] 分组占比
来源：http://dali.jlsjyb.cn/Article/details/gtszbckady.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtelgbhngy.html

[Q63] 开启事务
来源：http://dali.ybcxt.top/Article/details/gtvjbuhnun.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangshuangyany.cn/Article/details/gtsuoeyndq.html

[Q64] 提交事务
来源：http://dali.ppjwa.cn/Article/details/gtgtwhpaci.html

COMMIT;
来源：http://dali.zhongyouzk.top/Article/details/gtdcuqezvj.html

[Q65] 回滚事务
来源：http://dali.ehwqpu.com/Article/details/gtzmxtciqf.html

ROLLBACK;
来源：http://dali.dianchejie.cn/Article/details/gtbbjnrbdw.html

[Q66] 行锁查询
来源：http://dali.chenlongwang.top/Article/details/gtnxcroszm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuanzhike.top/Article/details/gtwyepwvec.html

[Q67] 设置隔离级别
来源：http://dali.haohaochexian.top/Article/details/gtadvihmse.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xuetiantiany.cn/Article/details/gtaxwhmwzh.html

[Q68] 保存点
来源：http://dali.iojbl.cn/Article/details/gtnrreeeif.html

SAVEPOINT sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gtxwlpmulq.html

ROLLBACK TO sp1;
来源：http://dali.gotoacloud.top/Article/details/gtcgwovnto.html

[Q69] 查看执行计划
来源：http://dali.fzhhl.top/Article/details/gtjbprqbjr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daxiang520.top/Article/details/gtqalvdpyx.html

[Q70] 更新统计信息
来源：http://dali.bjfxy.top/Article/details/gtgmzaqxax.html

ANALYZE TABLE users;
来源：http://dali.snrcjt.cn/Article/details/gtiihbvtfn.html

[Q71] 查看建表语句
来源：http://dali.daria6918.cn/Article/details/gtdnsepsdo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dashuyun.cn/Article/details/gtwuehrkkr.html

[Q72] 查看索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtncudbkrs.html

SHOW INDEX FROM users;
来源：http://dali.yj20258888.top/Article/details/gtzxxkxurt.html

[Q73] 查看表状态
来源：http://dali.xuetiantiany.cn/Article/details/gtqvguscrf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yongpay.top/Article/details/gtumuyrhmq.html

[Q74] 强制使用索引
来源：http://dali.tian-w.cn/Article/details/gtsyotfyhr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nanxinkj.top/Article/details/gthserlesp.html

[Q75] 日期格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdkfauyy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sweek.top/Article/details/gthonwwdbz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yvedp.cn/Article/details/gtadktibrw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gtyktjgiaf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yanxiufei.cn/Article/details/gttjxdrpxt.html

[Q77] 时间加减
来源：http://dali.yuxming.cn/Article/details/gtpjeyynfe.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.mhx1999.top/Article/details/gtkmjoddqi.html

[Q78] 当前时间
来源：http://dali.zhixingplan.top/Article/details/gtvltrkits.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xinyue.icu/Article/details/gtbmmnldfm.html

[Q79] 字符串拼接
来源：http://dali.xylfe.cn/Article/details/gtywlqnxct.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yangfankeji.com/Article/details/gtjuemprug.html

[Q80] 字符串截取
来源：http://dali.iojbl.cn/Article/details/gtcaoubasa.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtnoddznch.html

[Q81] 字符串替换
来源：http://dali.smart0.xyz/Article/details/gtqwrpagmb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtswedumka.html

[Q82] 字符长度与字节长度
来源：http://dali.gotoacloud.top/Article/details/gtlzzhdcxc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gttauzpjvi.html

[Q83] 大小写转换
来源：http://dali.iojbl.cn/Article/details/gtkmlpkgdc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtqryaieys.html

[Q84] 去除首尾空格
来源：http://dali.hysaishi.cn/Article/details/gtmwqssxow.html

SELECT TRIM(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtdeligvht.html

[Q85] 数值取整
来源：http://dali.aibaodan.cn/Article/details/gteocakssv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xziqi.cn/Article/details/gtinlecapr.html

[Q86] 读取 JSON 字段
来源：http://dali.mhx1999.top/Article/details/gtsnowftaj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.smart0.xyz/Article/details/gtfovrpyju.html

[Q87] JSON 字段做条件
来源：http://dali.ppjwa.cn/Article/details/gtnqwlkjgx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.bjfxy.top/Article/details/gtmpxfqmls.html

[Q88] 行转列（条件聚合）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlvefkbo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.iojbl.cn/Article/details/gtmsvsijqp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuanzx.com/Article/details/gtbwzdnrab.html

[Q89] 判断表是否存在
来源：http://dali.ydzc1.top/Article/details/gtiqhyskwu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj20258888.top/Article/details/gtlvktjwfb.html

[Q90] 生成序号列
来源：http://dali.jinqigufen.top/Article/details/gtdkbckxtv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yangfankeji.com/Article/details/gtnffdmkgm.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gthcswudfs.html

R. Bash 专题
来源：http://dali.ppjwa.cn/Article/details/gtyqvfgqng.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtcuttyjxo.html

[R01] shebang 与严格模式
来源：http://dali.pengpengdd.cyou/Article/details/gtsaxxobqw.html

#!/usr/bin/env bash
来源：http://dali.jlsjyb.cn/Article/details/gtnokxpgvc.html

set -euo pipefail
来源：http://dali.jianghu66.top/Article/details/gtaozurclk.html

[R02] 变量赋值与使用
来源：http://dali.hammf.cn/Article/details/gtaoajbvvp.html

name="Tom"; echo "$name"
来源：http://dali.hongshengwenyu.top/Article/details/gtkusfiyzw.html

[R03] 只读变量
来源：http://dali.hywenlv.cn/Article/details/gtxxxnroge.html

readonly PI=3.14
来源：http://dali.guannengcc.top/Article/details/gtomkkhwtb.html

[R04] 位置参数
来源：http://dali.xziqi.cn/Article/details/gtyrxajiad.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shzxlz.cn/Article/details/gtajaquhnu.html

[R05] 参数默认值
来源：http://dali.xuanzx.com/Article/details/gtrkqnrbaz.html

name="${1:-default}"
来源：http://dali.xuetiantiany.cn/Article/details/gtmtdintol.html

[R06] 判断命令是否存在
来源：http://dali.xinyue.icu/Article/details/gttbjvrava.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ppjwa.cn/Article/details/gtenqmtrub.html

[R07] if 判断文件
来源：http://dali.jianghu66.top/Article/details/gturvduhkr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yuxming.cn/Article/details/gtaxlihjoc.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gtiswkougd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yvedp.cn/Article/details/gtacthjtzm.html

[R09] 字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtcsrkvfdi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258888.top/Article/details/gtbnvruubb.html

[R10] 正则匹配
来源：http://dali.yj20258.top/Article/details/gtzanjuwps.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ivvv.top/Article/details/gtfaeflpqw.html

[R11] case 多分支
来源：http://dali.xinyue.icu/Article/details/gtnvoblhqu.html

case "$1" in
来源：http://dali.andypj.xyz/Article/details/gtzfiuldcl.html

start) echo "启动" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtabsgrmln.html

stop)  echo "停止" ;;
来源：http://dali.nanxuanxn.top/Article/details/gtlwahxjux.html

*)     echo "未知命令" ;;
来源：http://dali.xuanzx.com/Article/details/gtnsawljlv.html

esac
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotuzaalb.html

[R12] for 遍历文件
来源：http://dali.ppjwa.cn/Article/details/gtfyfzcbhc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guannengcc.top/Article/details/gtsrembdhd.html

[R13] for 计数循环
来源：http://dali.yangfankeji.com/Article/details/gtgucduahn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gtymwuipyd.html

[R14] C 风格 for
来源：http://dali.yangfankeji.com/Article/details/gtoogyuqwq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cdnleiting.top/Article/details/gtlcgdibke.html

[R15] while 逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gtujnqnoqh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gthyfnkupn.html

[R16] until 等待条件
来源：http://dali.ybcxt.top/Article/details/gtwcnnryfm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenjidiqi.icu/Article/details/gtalabtuqr.html

[R17] 数组定义与取值
来源：http://dali.xuetiantiany.cn/Article/details/gthhbhpiyu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenlongwang.top/Article/details/gtqyrdkfqk.html

[R18] 遍历数组
来源：http://dali.daria6918.cn/Article/details/gtfgnemggd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daria6918.cn/Article/details/gtocphjaxn.html

[R19] 数组长度
来源：http://dali.sweek.top/Article/details/gtlaofnnfi.html

echo "${#arr[@]}"
来源：http://dali.yanxiufei.cn/Article/details/gtebfhynls.html

[R20] 关联数组（字典）
来源：http://dali.vqdsnc.cn/Article/details/gtpuonbrpp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ppjwa.cn/Article/details/gtgesispuz.html

[R21] 字符串长度
来源：http://dali.yueranfly.top/Article/details/gtcbbucxwk.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gtwvrmlxhm.html

[R22] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gtavdvnbtn.html

echo "${s:0:5}"
来源：http://dali.0kj1m.cn/Article/details/gtwijuihye.html

[R23] 字符串替换
来源：http://dali.birdmap.top/Article/details/gtnmfmievc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.pycfn.com/Article/details/gtihjnpeak.html

[R24] 大小写转换
来源：http://dali.ivvv.top/Article/details/gtumlsngwa.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.svipenyu.cn/Article/details/gtezryfpvj.html

[R25] 去后缀 / 去前缀
来源：http://dali.daria6918.cn/Article/details/gtvudxkjhm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhixingplan.top/Article/details/gtcdsotmmq.html

[R26] 命令替换
来源：http://dali.guannengcc.top/Article/details/gtnifrzjgv.html

now=$(date +%F); echo "$now"
来源：http://dali.feifeiyinyue.top/Article/details/gtoghlvvoz.html

[R27] 算术展开
来源：http://dali.ydzc1.top/Article/details/gtqxhyvbfy.html

echo $((1 + 2 * 3))
来源：http://dali.yanxiufei.cn/Article/details/gtuyqwfcvu.html

[R28] 浮点运算
来源：http://dali.dianchejie.cn/Article/details/gtvlbsjtee.html

echo "scale=2; 10/3" | bc
来源：http://dali.meibo888.top/Article/details/gtodlqgrll.html

[R29] 定义函数
来源：http://dali.jiagoushi.top/Article/details/gtgoyxqnhu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sxryk.cn/Article/details/gtfdrlhtjc.html

[R30] 函数返回状态码
来源：http://dali.wangdashe.top/Article/details/gtwornxokt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dashuyun.cn/Article/details/gtkazxjqom.html

[R31] 局部变量
来源：http://dali.xinyue.icu/Article/details/gtjjybidid.html

f() { local x=1; echo "$x"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdjnxitb.html

[R32] 参数个数校验
来源：http://dali.zdqjudy.top/Article/details/gtcpusjyep.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aizwys.cn/Article/details/gtmdtsklbb.html

[R33] 捕获错误并提示行号
来源：http://dali.shangyingyoupin.top/Article/details/gtblblvhfb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnqzz.top/Article/details/gtbmtsbird.html

[R34] 退出时清理
来源：http://dali.tian-w.cn/Article/details/gtltlnqkjb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gtesfsdulm.html

[R35] 后台执行并等待
来源：http://dali.jinqigfzy.top/Article/details/gtjkxsldnp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zycfv.cn/Article/details/gtbrfkbbvi.html

[R36] 并发执行多个任务
来源：http://dali.yanxiufei.cn/Article/details/gtjrhynnlf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj202588.top/Article/details/gtybczmaoq.html

[R37] 把输出赋给变量
来源：http://dali.yj20258.top/Article/details/gtfprckzbg.html

files=$(ls -1)
来源：http://dali.dianchejie.cn/Article/details/gttrruuwec.html

[R38] 管道串联
来源：http://dali.xziqi.cn/Article/details/gtvhxztvfy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yangfankeji.com/Article/details/gtyrrpbuop.html

[R39] 重定向标准输出与错误
来源：http://dali.cashguo.top/Article/details/gtydffbagk.html

cmd > out.log 2>&1
来源：http://dali.vqdsnc.cn/Article/details/gtldqrehri.html

[R40] 追加写日志
来源：http://dali.xziqi.cn/Article/details/gtfgckcpzx.html

echo "log" >> out.log
来源：http://dali.0kj1m.cn/Article/details/gtkjtbuyvb.html

[R41] 丢弃输出
来源：http://dali.vqdsnc.cn/Article/details/gtwpycsjgl.html

cmd >/dev/null 2>&1
来源：http://dali.jianghu66.top/Article/details/gtlrhvcdbk.html

[R42] 输入重定向
来源：http://dali.shzxlz.cn/Article/details/gtxjfwewen.html

wc -l < a.txt
来源：http://dali.nwbrower.top/Article/details/gtvxmuoyfw.html

[R43] 按名字查找文件
来源：http://dali.sufxvd.cn/Article/details/gtumucxeab.html

find . -name "*.log" -type f
来源：http://dali.ppjwa.cn/Article/details/gtmyhbtgss.html

[R44] 按修改时间查找
来源：http://dali.hammf.cn/Article/details/gtbogzpmho.html

find . -mtime -7 -type f
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbsitlmc.html

[R45] 批量删除
来源：http://dali.hnqzz.top/Article/details/gtqprvkrnw.html

find . -name "*.tmp" -delete
来源：http://dali.ydzc1.top/Article/details/gtkowgesyp.html

[R46] 递归替换文件内容
来源：http://dali.c1oappe.top/Article/details/gtrxqwaqvs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258888.top/Article/details/gtfknlyghk.html

[R47] sed 单行替换
来源：http://dali.ybcxt.top/Article/details/gtmijvpytk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtqhtbhecp.html

[R48] awk 取指定列
来源：http://dali.redwolf501.top/Article/details/gtgpqjyyjg.html

awk '{print $1, $3}' a.txt
来源：http://dali.sweek.top/Article/details/gtakjjgudg.html

[R49] awk 带条件
来源：http://dali.havefunace.top/Article/details/gtfevrlcep.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.kuanghao11.cn/Article/details/gtzokxeikb.html

[R50] awk 求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gthrcyovqc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gthimltsmm.html

[R51] 排序去重取前几
来源：http://dali.jlsjyb.cn/Article/details/gthzmpqard.html


<!-- 参考信息 -->