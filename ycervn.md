代发 wailian999

);
来源：http://dali.hnqzz.top/Article/details/gt2nziatesx.html

[Q03] 增加列
来源：http://dali.wangdashe.top/Article/details/gt2abymsypw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sysykeji.top/Article/details/gt2noyuncut.html

[Q04] 修改列类型
来源：http://dali.316326.xyz/Article/details/gt2vaedsrit.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.birdmap.top/Article/details/gt2econrysw.html

[Q05] 重命名列
来源：http://dali.jlsjyb.cn/Article/details/gt2fmqctpew.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.aizwys.cn/Article/details/gt2ncgzdkhk.html

[Q06] 删除列
来源：http://dali.fengsongda.top/Article/details/gt2fjbeoigc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yvedp.cn/Article/details/gt2cytuwcpv.html

[Q07] 删除表
来源：http://dali.gogol.net.cn/Article/details/gt2ksexhfgg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jqgufenzy.top/Article/details/gt2uptdrcgy.html

[Q08] 创建普通索引
来源：http://dali.tanke756.top/Article/details/gt2jqrrvsml.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2slrkqren.html

[Q09] 创建唯一索引
来源：http://dali.yuxming.cn/Article/details/gt2opdoucel.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gt2xdaqcctr.html

[Q10] 插入单行
来源：http://dali.chenlongwang.top/Article/details/gt2vabhtajl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hysaishi.cn/Article/details/gt2ppgtlfmw.html

[Q11] 一次插入多行
来源：http://dali.wangshuangyany.cn/Article/details/gt2gdcsdwyj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gt2iaxlyryt.html

[Q12] 插入后取自增 ID
来源：http://dali.gaohongyu789.top/Article/details/gt2jrzdmpti.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxuanxn.top/Article/details/gt2tptdsbyn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hfpthk.cn/Article/details/gt2podmxtjk.html

[Q13] 忽略重复插入
来源：http://dali.hammf.cn/Article/details/gt2fjjnhuxr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tianlin.xyz/Article/details/gt2jkqeozig.html

[Q14] 存在则更新（upsert）
来源：http://dali.0kj1m.cn/Article/details/gt2ngscxqsw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xylfe.cn/Article/details/gt2aemgvsne.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.havefunace.top/Article/details/gt2mqrwvhcd.html

[Q15] 查询全部
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dsocqmbq.html

SELECT * FROM users;
来源：http://dali.sweek.top/Article/details/gt2nxzyzgjq.html

[Q16] 查询指定列
来源：http://dali.wangdashe.top/Article/details/gt2njitwcpl.html

SELECT id, name FROM users;
来源：http://dali.havefunace.top/Article/details/gt2semylkhj.html

[Q17] 条件查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2gguyqcdm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.c1oappe.top/Article/details/gt2fzmjrxny.html

[Q18] 模糊匹配
来源：http://dali.guannengcc.top/Article/details/gt2bzilxufa.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xuanzx.com/Article/details/gt2tqowhirx.html

[Q19] 范围查询
来源：http://dali.chenjidiqi.icu/Article/details/gt2wpuprjsv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xylfe.cn/Article/details/gt2xxnmdfko.html

[Q20] IN 列表
来源：http://dali.shuidangran.top/Article/details/gt2ueuwjhzk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.316326.xyz/Article/details/gt2uphirfzi.html

[Q21] 空值判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tpocoqmd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xylfe.cn/Article/details/gt2lgrttuff.html

[Q22] 排序
来源：http://dali.cucudq.cn/Article/details/gt2lumqyvox.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vpjmzupq.html

[Q23] 分页
来源：http://dali.ppjwa.cn/Article/details/gt2njsmfgrs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenzaomai.com/Article/details/gt2zdhgtmyn.html

[Q24] 去重
来源：http://dali.chenzaomai.com/Article/details/gt2vutclgpw.html

SELECT DISTINCT city FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2khmgcrks.html

[Q25] 只取前 N 条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2znosufgv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.kuanghao11.cn/Article/details/gt2kbtjimeh.html

[Q26] 计数
来源：http://dali.ydzc1.top/Article/details/gt2tazeyxaf.html

SELECT COUNT(*) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jnqxyedn.html

[Q27] 条件计数
来源：http://dali.daxiang520.top/Article/details/gt2xipoxvxb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2kpidxksn.html

[Q28] 求和与平均
来源：http://dali.ybcxt.top/Article/details/gt2signgxpy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gt2dobhormt.html

[Q29] 最大最小值
来源：http://dali.hammf.cn/Article/details/gt2hojxmrfu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2mdawpehk.html

[Q30] 分组统计
来源：http://dali.guannengcc.top/Article/details/gt2frmxpnhg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gt2onbdseix.html

[Q31] 分组后过滤
来源：http://dali.zhengqikj.top/Article/details/gt2ckbjcxso.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinqigfzy.top/Article/details/gt2ltrvenbq.html

[Q32] 分组拼接字符串
来源：http://dali.hammf.cn/Article/details/gt2ucvzyywl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gt2njnhehur.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ehwqpu.com/Article/details/gt2imunffth.html

[Q33] 多列分组
来源：http://dali.mhx1999.top/Article/details/gt2ldlaojbt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gotoacloud.top/Article/details/gt2stcnzust.html

[Q34] 每组取第一条
来源：http://dali.hywenlv.cn/Article/details/gt2ttuwahjg.html

SELECT * FROM (
来源：http://dali.zhengqikj.top/Article/details/gt2lwafwzpz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zycfv.cn/Article/details/gt2nvxgngou.html

) t WHERE rn = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2tfukhdjd.html

[Q35] 内连接
来源：http://dali.tanke756.top/Article/details/gt2nipeeges.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rvqetyjj.html

[Q36] 左连接
来源：http://dali.yanxiufei.cn/Article/details/gt2mkcyuhiu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258888.top/Article/details/gt2kiycjlya.html

[Q37] 右连接
来源：http://dali.sxryk.cn/Article/details/gt2xcjglmzc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.snrcjt.cn/Article/details/gt2xxvbwxmo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ckvmuyvd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.aibaodan.cn/Article/details/gt2kcxzvzmv.html

[Q39] 自连接（查上下级）
来源：http://dali.zhoulong.xyz/Article/details/gt2epvqexrs.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nwbrower.top/Article/details/gt2eryowvwp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pjuxhjns.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nanxinkj.top/Article/details/gt2nrnebxwp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pkxtpvnf.html

[Q41] 多表连接
来源：http://dali.yangfankeji.com/Article/details/gt2vzxhasws.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2imldwnwj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenlongwang.top/Article/details/gt2gipgxqcg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yvedp.cn/Article/details/gt2lfeffper.html

[Q42] 连接条件附加过滤
来源：http://dali.zycfv.cn/Article/details/gt2aqazgife.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sysykeji.top/Article/details/gt2aattwpdl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.vqdsnc.cn/Article/details/gt2tuqqiuyz.html

[Q43] 标量子查询
来源：http://dali.fzhhl.top/Article/details/gt2eawacutg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gotoacloud.top/Article/details/gt2hgsjfovh.html

[Q44] IN 子查询
来源：http://dali.ivvv.top/Article/details/gt2dcccgxop.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xuetiantiany.cn/Article/details/gt2zvkkjjqc.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxinkj.top/Article/details/gt2szgjlzlv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hammf.cn/Article/details/gt2roclnjmv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ppjwa.cn/Article/details/gt2zzlmahap.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hammf.cn/Article/details/gt2kfmpaonc.html

[Q47] 与平均值比较
来源：http://dali.ydzc1.top/Article/details/gt2qzjfpeib.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gogol.net.cn/Article/details/gt2kcwvqtpe.html

[Q48] CTE 公用表表达式
来源：http://dali.chenlongwang.top/Article/details/gt2vrhjyhwk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.vqdsnc.cn/Article/details/gt2qnfaorzn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigfzy.top/Article/details/gt2rhdoufno.html

[Q49] 更新单行
来源：http://dali.hywenlv.cn/Article/details/gt2zdzpuyes.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gotoacloud.top/Article/details/gt2pfahblqb.html

[Q50] 批量更新
来源：http://dali.meibo888.top/Article/details/gt2urjssbfh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jianghu66.top/Article/details/gt2vavknyxw.html

[Q51] 用子查询更新
来源：http://dali.guowangkeji.top/Article/details/gt2alsozjtj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj20258.top/Article/details/gt2kdsabjjg.html

[Q52] 删除指定行
来源：http://dali.ybcxt.top/Article/details/gt2koncnolu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tian-w.cn/Article/details/gt2mesgblir.html

[Q53] 按条件删除
来源：http://dali.hywenlv.cn/Article/details/gt2apksjjth.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tian-w.cn/Article/details/gt2psxzzswj.html

[Q54] 清空表
来源：http://dali.hammf.cn/Article/details/gt2hxrrnnew.html

TRUNCATE TABLE logs;
来源：http://dali.xylfe.cn/Article/details/gt2qhgnmcod.html

[Q55] 排名（并列占位）
来源：http://dali.hnqzz.top/Article/details/gt2wysllmta.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.meibo888.top/Article/details/gt2gpyszadu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.pengpengdd.cyou/Article/details/gt2legypcqf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gt2tgigakml.html

[Q57] 行号
来源：http://dali.zhongyouzk.top/Article/details/gt2noglpaxl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2zuwjtafv.html

[Q58] 累计求和
来源：http://dali.snrcjt.cn/Article/details/gt2onrmnsuz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gt2feamiszy.html

[Q59] 分组内累计
来源：http://dali.yj20258.top/Article/details/gt2wghuspns.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gt2bsobkbwf.html

[Q60] 取上一行 / 下一行
来源：http://dali.ydzc1.top/Article/details/gt2hefdqjee.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sufxvd.cn/Article/details/gt2etiqcead.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gt2fjqfwuuv.html

[Q61] 移动平均
来源：http://dali.fengsongda.top/Article/details/gt2avahgyeb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gt2rnncoyqu.html

[Q62] 分组占比
来源：http://dali.yonumen.top/Article/details/gt2phgujwpi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gt2rkzynyip.html

[Q63] 开启事务
来源：http://dali.tianlin.xyz/Article/details/gt2eliyrhfw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhixingplan.top/Article/details/gt2eklqlcbo.html

[Q64] 提交事务
来源：http://dali.cheryme.top/Article/details/gt2fddttgvv.html

COMMIT;
来源：http://dali.smart0.xyz/Article/details/gt2ngmprcqc.html

[Q65] 回滚事务
来源：http://dali.hfpthk.cn/Article/details/gt2vmfbxwhz.html

ROLLBACK;
来源：http://dali.ppjwa.cn/Article/details/gt2cuaqdlki.html

[Q66] 行锁查询
来源：http://dali.cucudq.cn/Article/details/gt2jixlrdrn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yanxiufei.cn/Article/details/gt2gpdyxiht.html

[Q67] 设置隔离级别
来源：http://dali.pengpengdd.cyou/Article/details/gt2elggbcuj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigufen.top/Article/details/gt2cbfbmuce.html

[Q68] 保存点
来源：http://dali.yj202588.top/Article/details/gt2ozeyplhc.html

SAVEPOINT sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ozveyctl.html

ROLLBACK TO sp1;
来源：http://dali.sufxvd.cn/Article/details/gt2lnfmgyuz.html

[Q69] 查看执行计划
来源：http://dali.9152youxi.cn/Article/details/gt2ktvdqfcl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fzhhl.top/Article/details/gt2etikwkuq.html

[Q70] 更新统计信息
来源：http://dali.quarkkingdee.top/Article/details/gt2qzldaojj.html

ANALYZE TABLE users;
来源：http://dali.chenlongwang.top/Article/details/gt2ydaxlsaz.html

[Q71] 查看建表语句
来源：http://dali.jqgfzy.top/Article/details/gt2yheejpch.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgufenzy.top/Article/details/gt2kwekjcqo.html

[Q72] 查看索引
来源：http://dali.yuanzhike.top/Article/details/gt2vvgtoscc.html

SHOW INDEX FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2qhzkxcnq.html

[Q73] 查看表状态
来源：http://dali.zycfv.cn/Article/details/gt2jpefzgap.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ybcxt.top/Article/details/gt2cevrkczl.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ffngshqf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.smart0.xyz/Article/details/gt2dcgoejva.html

[Q75] 日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gt2faumvsby.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2afuklfqj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhengqikj.top/Article/details/gt2nafiyise.html

[Q76] 按天统计
来源：http://dali.mhx1999.top/Article/details/gt2afmylrya.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cdnleiting.top/Article/details/gt2jorkwwtz.html

[Q77] 时间加减
来源：http://dali.tanke756.top/Article/details/gt2eokgkjfw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hnxiangtu.top/Article/details/gt2dzflwetc.html

[Q78] 当前时间
来源：http://dali.cheryme.top/Article/details/gt2fhxbmmoq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj202588.top/Article/details/gt2afihaymz.html

[Q79] 字符串拼接
来源：http://dali.zhixingplan.top/Article/details/gt2lhhlxmwm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgfzy.top/Article/details/gt2mgnmmxwg.html

[Q80] 字符串截取
来源：http://dali.zhongyouzk.top/Article/details/gt2ldhnamqh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2waoomgdp.html

[Q81] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gt2pkmpdrhj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2hlosgyiq.html

[Q82] 字符长度与字节长度
来源：http://dali.cdnleiting.top/Article/details/gt2hyacmuim.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2xukobfax.html

[Q83] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gt2fbyqvtxl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gt2ewidvozf.html

[Q84] 去除首尾空格
来源：http://dali.feifeiyinyue.top/Article/details/gt2nzxxvolf.html

SELECT TRIM(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rtlmhlqp.html

[Q85] 数值取整
来源：http://dali.wangshuangyany.cn/Article/details/gt2iswfvuia.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.guannengcc.top/Article/details/gt2azldpbry.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258888.top/Article/details/gt2hffapnpr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.andypj.xyz/Article/details/gt2xswwyyfh.html

[Q87] JSON 字段做条件
来源：http://dali.jiagoushi.top/Article/details/gt2dbfdbtjy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinqigufen.top/Article/details/gt2teioktfv.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgufenzy.top/Article/details/gt2rmfcqgch.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.smart0.xyz/Article/details/gt2rxymequh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yjlhweml.html

[Q89] 判断表是否存在
来源：http://dali.kuanghao11.cn/Article/details/gt2cilsssky.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuetiantiany.cn/Article/details/gt2ydobclbj.html

[Q90] 生成序号列
来源：http://dali.jianghu66.top/Article/details/gt2xwfbilij.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.vqdsnc.cn/Article/details/gt2xbacdvpf.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2afcztzrc.html

R. Bash 专题
来源：http://dali.zhengqikj.top/Article/details/gt2tlyjlenr.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2guhsgviu.html

[R01] shebang 与严格模式
来源：http://dali.xylfe.cn/Article/details/gt2wmxkeufo.html

#!/usr/bin/env bash
来源：http://dali.haohaochexian.top/Article/details/gt2vnhcisxj.html

set -euo pipefail
来源：http://dali.hnqzz.top/Article/details/gt2rordtxqt.html

[R02] 变量赋值与使用
来源：http://dali.shuidangran.top/Article/details/gt2ulhubppa.html

name="Tom"; echo "$name"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jqizuqau.html

[R03] 只读变量
来源：http://dali.nwbrower.top/Article/details/gt2sturpxyx.html

readonly PI=3.14
来源：http://dali.quarkkingdee.top/Article/details/gt2wluufjpd.html

[R04] 位置参数
来源：http://dali.tianlin.xyz/Article/details/gt2uraabnvb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yongpay.top/Article/details/gt2ckibewyl.html

[R05] 参数默认值
来源：http://dali.yongpay.top/Article/details/gt2lftzjdim.html

name="${1:-default}"
来源：http://dali.havefunace.top/Article/details/gt2rupbpfwn.html

[R06] 判断命令是否存在
来源：http://dali.nanxinkj.top/Article/details/gt2tvrnipxq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gt2jkvgprce.html

[R07] if 判断文件
来源：http://dali.tanke756.top/Article/details/gt2vodzoxcv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.bjfxy.top/Article/details/gt2ajlgacdn.html

[R08] 数值比较
来源：http://dali.jqgufenzy.top/Article/details/gt2tkvyfbsu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.redwolf501.top/Article/details/gt2yfdsczgp.html

[R09] 字符串比较
来源：http://dali.ivvv.top/Article/details/gt2rfzkdojt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dianchejie.cn/Article/details/gt2fregfbcp.html

[R10] 正则匹配
来源：http://dali.smart0.xyz/Article/details/gt2auemfvvu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gogol.net.cn/Article/details/gt2mgqsajnx.html

[R11] case 多分支
来源：http://dali.meibo888.top/Article/details/gt2bxjqyyhe.html

case "$1" in
来源：http://dali.cdnleiting.top/Article/details/gt2bkvkxymf.html

start) echo "启动" ;;
来源：http://dali.yj20258.top/Article/details/gt2dyjulaem.html

stop)  echo "停止" ;;
来源：http://dali.hammf.cn/Article/details/gt2iaprkiib.html

*)     echo "未知命令" ;;
来源：http://dali.ydzc1.top/Article/details/gt2kbmpxohw.html

esac
来源：http://dali.chenlongwang.top/Article/details/gt2lgxzsust.html

[R12] for 遍历文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hchnuxin.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sysykeji.top/Article/details/gt2mbbecayg.html

[R13] for 计数循环
来源：http://dali.xinyue.icu/Article/details/gt2ymoirswq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gt2fkvcdmnj.html

[R14] C 风格 for
来源：http://dali.cashguo.top/Article/details/gt2igukmrow.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gt2qyrjzobp.html

[R15] while 逐行读文件
来源：http://dali.guannengcc.top/Article/details/gt2ndmoalyq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xuanzx.com/Article/details/gt2isixqjfo.html

[R16] until 等待条件
来源：http://dali.sufxvd.cn/Article/details/gt2wbscpkyh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.kuanghao11.cn/Article/details/gt2lvimketi.html

[R17] 数组定义与取值
来源：http://dali.xuetiantiany.cn/Article/details/gt2pfdrabjp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.bjfxy.top/Article/details/gt2gyoncmym.html

[R18] 遍历数组
来源：http://dali.hfpthk.cn/Article/details/gt2udfvdyod.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj202588.top/Article/details/gt2ibaqwqrg.html

[R19] 数组长度
来源：http://dali.shzxlz.cn/Article/details/gt2gqggzwej.html

echo "${#arr[@]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wzvpulem.html

[R20] 关联数组（字典）
来源：http://dali.birdmap.top/Article/details/gt2pojcidvw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigfzy.top/Article/details/gt2umchitli.html

[R21] 字符串长度
来源：http://dali.havefunace.top/Article/details/gt2rrufmzrw.html

echo "${#s}"
来源：http://dali.gotoacloud.top/Article/details/gt2pwgbjfxj.html

[R22] 截取子串
来源：http://dali.shangyingyoupin.top/Article/details/gt2kfjgnxrq.html

echo "${s:0:5}"
来源：http://dali.svipenyu.cn/Article/details/gt2qdideyee.html

[R23] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gt2awjfbjlz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhoulong.xyz/Article/details/gt2whmqmxsz.html

[R24] 大小写转换
来源：http://dali.pengpengdd.cyou/Article/details/gt2zsrqkjtd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ybcxt.top/Article/details/gt2rnmwiyeh.html

[R25] 去后缀 / 去前缀
来源：http://dali.9152youxi.cn/Article/details/gt2bezfrmzu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhixingplan.top/Article/details/gt2ctvgwmzs.html

[R26] 命令替换
来源：http://dali.vqdsnc.cn/Article/details/gt2quazmxtw.html

now=$(date +%F); echo "$now"
来源：http://dali.zdqjudy.top/Article/details/gt2peqowhyc.html

[R27] 算术展开
来源：http://dali.zhengqikj.top/Article/details/gt2nlthpofs.html

echo $((1 + 2 * 3))
来源：http://dali.nanxuanxn.top/Article/details/gt2uejldubk.html

[R28] 浮点运算
来源：http://dali.xuetiantiany.cn/Article/details/gt2grgzucri.html

echo "scale=2; 10/3" | bc
来源：http://dali.yangfankeji.com/Article/details/gt2wojnlrub.html

[R29] 定义函数
来源：http://dali.jianghu66.top/Article/details/gt2hnkercbm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hywenlv.cn/Article/details/gt2pzkspgpn.html

[R30] 函数返回状态码
来源：http://dali.yj20258888.top/Article/details/gt2brhqkyfq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nwbrower.top/Article/details/gt2oliekhhu.html

[R31] 局部变量
来源：http://dali.shuidangran.top/Article/details/gt2ommmmimu.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuanzhike.top/Article/details/gt2iglvcrtv.html

[R32] 参数个数校验
来源：http://dali.ydzc1.top/Article/details/gt2iooffepn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gt2btietwdd.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjcyalx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.dianchejie.cn/Article/details/gt2olmofcpb.html

[R34] 退出时清理
来源：http://dali.nwbrower.top/Article/details/gt2prsgwmjo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2flxqogsu.html

[R35] 后台执行并等待
来源：http://dali.hnxiangtu.top/Article/details/gt2qfnrwtts.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daxiang520.top/Article/details/gt2dmkkxtva.html

[R36] 并发执行多个任务
来源：http://dali.zhixingplan.top/Article/details/gt2ofdifntu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pycfn.com/Article/details/gt2eqovrpwh.html

[R37] 把输出赋给变量
来源：http://dali.zhongyouzk.top/Article/details/gt2dpeemuvr.html

files=$(ls -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tdudaqxp.html

[R38] 管道串联
来源：http://dali.jinqigfzy.top/Article/details/gt2tsucdrqg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigufen.top/Article/details/gt2zcauaihf.html

[R39] 重定向标准输出与错误
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dfvwqsal.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2feeipvgi.html

[R40] 追加写日志
来源：http://dali.hfpthk.cn/Article/details/gt2damnjaqy.html

echo "log" >> out.log
来源：http://dali.cashguo.top/Article/details/gt2oychzdqu.html

[R41] 丢弃输出
来源：http://dali.zhiwuduotai.top/Article/details/gt2lrhlzebp.html

cmd >/dev/null 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gt2vnjcbwwl.html

[R42] 输入重定向
来源：http://dali.yongpay.top/Article/details/gt2rjoikugw.html

wc -l < a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2xgtfbwip.html

[R43] 按名字查找文件
来源：http://dali.hywenlv.cn/Article/details/gt2qyxrwpjj.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tljkneug.html

[R44] 按修改时间查找
来源：http://dali.mhx1999.top/Article/details/gt2jtuqioqs.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnmhhvs.html

[R45] 批量删除
来源：http://dali.hywenlv.cn/Article/details/gt2dhhyxgvs.html

find . -name "*.tmp" -delete
来源：http://dali.nwbrower.top/Article/details/gt2ianaivqf.html

[R46] 递归替换文件内容
来源：http://dali.cdnleiting.top/Article/details/gt2cegofmlb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhengqikj.top/Article/details/gt2diabpvki.html

[R47] sed 单行替换
来源：http://dali.nwbrower.top/Article/details/gt2vuzamasx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yongpay.top/Article/details/gt2rglfysjh.html

[R48] awk 取指定列
来源：http://dali.zhiwuduotai.top/Article/details/gt2fsobsoxq.html

awk '{print $1, $3}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2vhyhrmsh.html

[R49] awk 带条件
来源：http://dali.gzhubu.top/Article/details/gt2eyxzauly.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinqigufen.top/Article/details/gt2oduhcvkk.html

[R50] awk 求和
来源：http://dali.guannengcc.top/Article/details/gt2wpykbsmu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ehwqpu.com/Article/details/gt2bshpdqwh.html

[R51] 排序去重取前几
来源：http://dali.sysykeji.top/Article/details/gt2pqpwsuhg.html


<!-- 参考信息 -->