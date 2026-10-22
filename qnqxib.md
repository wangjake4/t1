代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xuetiantiany.cn/Article/details/gtkaiztmrp.html

[Q05] 重命名列
来源：http://dali.daria6918.cn/Article/details/gtkbnqulzw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.meibo888.top/Article/details/gtnqgwiqya.html

[Q06] 删除列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmejypvzm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yvedp.cn/Article/details/gtsodbuyur.html

[Q07] 删除表
来源：http://dali.feifeiyinyue.top/Article/details/gtbzftpcnt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.havefunace.top/Article/details/gtcvqozepx.html

[Q08] 创建普通索引
来源：http://dali.quarkkingdee.top/Article/details/gtqfmcywpc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hongshengwenyu.top/Article/details/gtnektbuix.html

[Q09] 创建唯一索引
来源：http://dali.chenjidiqi.icu/Article/details/gtcbtvbcux.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenjidiqi.icu/Article/details/gtislikcgk.html

[Q10] 插入单行
来源：http://dali.cdnleiting.top/Article/details/gtjusohifg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yongpay.top/Article/details/gtwcnktilm.html

[Q11] 一次插入多行
来源：http://dali.aizwys.cn/Article/details/gtvyvjjrmn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yuanzhike.top/Article/details/gtpmvgnaxi.html

[Q12] 插入后取自增 ID
来源：http://dali.guannengcc.top/Article/details/gtsircnmzy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.dashuyun.cn/Article/details/gtgnwtowdy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hammf.cn/Article/details/gtoqwzauqn.html

[Q13] 忽略重复插入
来源：http://dali.chenzaomai.com/Article/details/gtgkukhcci.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hammf.cn/Article/details/gtoztbijxa.html

[Q14] 存在则更新（upsert）
来源：http://dali.pengpengdd.cyou/Article/details/gtqeewezex.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gotoacloud.top/Article/details/gtmzlbxhif.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.dianchejie.cn/Article/details/gtzueuqybw.html

[Q15] 查询全部
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbthavrh.html

SELECT * FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjawjhjrx.html

[Q16] 查询指定列
来源：http://dali.zhengqikj.top/Article/details/gtgftcbdqu.html

SELECT id, name FROM users;
来源：http://dali.meibo888.top/Article/details/gtpqtkfknx.html

[Q17] 条件查询
来源：http://dali.shzxlz.cn/Article/details/gtyjdkwcjs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.dianchejie.cn/Article/details/gtjttfyzge.html

[Q18] 模糊匹配
来源：http://dali.xziqi.cn/Article/details/gtbsafjqwo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sweek.top/Article/details/gtijdwursg.html

[Q19] 范围查询
来源：http://dali.haohaochexian.top/Article/details/gtohyezrdt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gogol.net.cn/Article/details/gtmxzgpwdg.html

[Q20] IN 列表
来源：http://dali.yueranfly.top/Article/details/gtixewlloq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jianghu66.top/Article/details/gtgbcpofda.html

[Q21] 空值判断
来源：http://dali.daria6918.cn/Article/details/gtsypgfzan.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gtgbcvuotd.html

[Q22] 排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjyjuomio.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.dashuyun.cn/Article/details/gtumhcimwl.html

[Q23] 分页
来源：http://dali.aizwys.cn/Article/details/gtycryvjnp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yongpay.top/Article/details/gtajqkxwae.html

[Q24] 去重
来源：http://dali.aizwys.cn/Article/details/gtnxihrfxo.html

SELECT DISTINCT city FROM users;
来源：http://dali.yueranfly.top/Article/details/gtilxivoja.html

[Q25] 只取前 N 条
来源：http://dali.hnqzz.top/Article/details/gtarqjyrhn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhiwuduotai.top/Article/details/gtfzxrrltz.html

[Q26] 计数
来源：http://dali.gogol.net.cn/Article/details/gthxirackd.html

SELECT COUNT(*) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtxvrvagna.html

[Q27] 条件计数
来源：http://dali.kuanghao11.cn/Article/details/gtgdcaiwzt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtryncylwk.html

[Q28] 求和与平均
来源：http://dali.birdmap.top/Article/details/gtebsfando.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtlikvsuhk.html

[Q29] 最大最小值
来源：http://dali.fzhhl.top/Article/details/gtnohakmao.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfblhezvj.html

[Q30] 分组统计
来源：http://dali.dianchejie.cn/Article/details/gtixpwpinr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gtwdevqvxp.html

[Q31] 分组后过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtlignlsul.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.316326.xyz/Article/details/gtflruqcmf.html

[Q32] 分组拼接字符串
来源：http://dali.yuxming.cn/Article/details/gtguasrbrq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gtnskwgtra.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tian-w.cn/Article/details/gtaaxubopw.html

[Q33] 多列分组
来源：http://dali.chenlongwang.top/Article/details/gttydenbks.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.dianchejie.cn/Article/details/gtwgflgfyy.html

[Q34] 每组取第一条
来源：http://dali.jiagoushi.top/Article/details/gtlmikzvss.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gtajvznpgv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tanke756.top/Article/details/gttjojfnfr.html

) t WHERE rn = 1;
来源：http://dali.tian-w.cn/Article/details/gtehnoxsqb.html

[Q35] 内连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvulrvjlw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gtiipinjrs.html

[Q36] 左连接
来源：http://dali.jqgufenzy.top/Article/details/gtbaoztsbg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.haohaochexian.top/Article/details/gtkcffrljr.html

[Q37] 右连接
来源：http://dali.xuetiantiany.cn/Article/details/gtrknitlbj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuetiantiany.cn/Article/details/gtmpsbesog.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbujgulwq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.redwolf501.top/Article/details/gtcjohhlss.html

[Q39] 自连接（查上下级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjwqqqmmh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ydzc1.top/Article/details/gtgiqfmtur.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gaohongyu789.top/Article/details/gtbnsgollo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.snrcjt.cn/Article/details/gtvbrnbaso.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shanyushiyangtech.top/Article/details/gtosudzzvm.html

[Q41] 多表连接
来源：http://dali.0kj1m.cn/Article/details/gtixrolmuz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ehwqpu.com/Article/details/gtomrbuvhi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.wangshuangyany.cn/Article/details/gtnphrmkrp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sysykeji.top/Article/details/gttewveksp.html

[Q42] 连接条件附加过滤
来源：http://dali.tianlin.xyz/Article/details/gtkkzlqipi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gaohongyu789.top/Article/details/gtwedfrewy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.wangdashe.top/Article/details/gtlfoxjxjr.html

[Q43] 标量子查询
来源：http://dali.iojbl.cn/Article/details/gtwzenonkl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xylfe.cn/Article/details/gtyhkmqiht.html

[Q44] IN 子查询
来源：http://dali.zdqjudy.top/Article/details/gtdnqrliuu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbelnbos.html

[Q45] EXISTS 判断存在
来源：http://dali.cqqwz.cn/Article/details/gtuckdtada.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.vqdsnc.cn/Article/details/gthddluooo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhixingplan.top/Article/details/gthdhlnfyc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.vqdsnc.cn/Article/details/gtplqmzqiq.html

[Q47] 与平均值比较
来源：http://dali.zhixingplan.top/Article/details/gtoaiwlloe.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.havefunace.top/Article/details/gtnvforect.html

[Q48] CTE 公用表表达式
来源：http://dali.chenjidiqi.icu/Article/details/gteshdjchg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xuetiantiany.cn/Article/details/gtyfneuwql.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.haohaochexian.top/Article/details/gtzknysvdz.html

[Q49] 更新单行
来源：http://dali.yj20258888.top/Article/details/gtgjifhjta.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.svipenyu.cn/Article/details/gtvhsiowpg.html

[Q50] 批量更新
来源：http://dali.dianchejie.cn/Article/details/gtrpyuphae.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ehwqpu.com/Article/details/gtvngnuiep.html

[Q51] 用子查询更新
来源：http://dali.dashuyun.cn/Article/details/gtscsecxde.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zycfv.cn/Article/details/gtaabfrlog.html

[Q52] 删除指定行
来源：http://dali.fzhhl.top/Article/details/gtxhoxnwdo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hnxiangtu.top/Article/details/gtpqvjnxeh.html

[Q53] 按条件删除
来源：http://dali.chenlongwang.top/Article/details/gtsrnuveop.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jyoumei.cn/Article/details/gtmxyxdlaq.html

[Q54] 清空表
来源：http://dali.svipenyu.cn/Article/details/gtyyfxhqlr.html

TRUNCATE TABLE logs;
来源：http://dali.yj202588.top/Article/details/gtmpfzeiwk.html

[Q55] 排名（并列占位）
来源：http://dali.xylfe.cn/Article/details/gtznwkqkhg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgufenzy.top/Article/details/gtjqrfxahe.html

[Q56] 密集排名（并列不占位）
来源：http://dali.quarkkingdee.top/Article/details/gtmiogjdlx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.meibo888.top/Article/details/gtaqwlvzxs.html

[Q57] 行号
来源：http://dali.0kj1m.cn/Article/details/gtmzolcxzz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gtunuqhzjf.html

[Q58] 累计求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovaumrhb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yonumen.top/Article/details/gtnbjfrafj.html

[Q59] 分组内累计
来源：http://dali.jianghu66.top/Article/details/gtkgjectza.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtayiemwgw.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigufen.top/Article/details/gtrrvsulrp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhiwuduotai.top/Article/details/gtzmogoivz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sweek.top/Article/details/gthsclixvz.html

[Q61] 移动平均
来源：http://dali.jqgfzy.top/Article/details/gtnxtobkvr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtekbvmqet.html

[Q62] 分组占比
来源：http://dali.tanke756.top/Article/details/gtvgodajck.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtcwfgpdef.html

[Q63] 开启事务
来源：http://dali.hysaishi.cn/Article/details/gtxmetevcv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.vqdsnc.cn/Article/details/gtekvakcqv.html

[Q64] 提交事务
来源：http://dali.tianlin.xyz/Article/details/gtblkyvkkw.html

COMMIT;
来源：http://dali.chenjidiqi.icu/Article/details/gtuwkamkyw.html

[Q65] 回滚事务
来源：http://dali.zhongyouzk.top/Article/details/gtiqmcmvuy.html

ROLLBACK;
来源：http://dali.gogol.net.cn/Article/details/gtyxmighba.html

[Q66] 行锁查询
来源：http://dali.0kj1m.cn/Article/details/gtluurjzpq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jianghu66.top/Article/details/gthurazmil.html

[Q67] 设置隔离级别
来源：http://dali.mhx1999.top/Article/details/gtitmlvjas.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yanxiufei.cn/Article/details/gtpfotidav.html

[Q68] 保存点
来源：http://dali.yangfankeji.com/Article/details/gtexepuqbz.html

SAVEPOINT sp1;
来源：http://dali.daria6918.cn/Article/details/gthqzjqqjp.html

ROLLBACK TO sp1;
来源：http://dali.pycfn.com/Article/details/gtlvcxspff.html

[Q69] 查看执行计划
来源：http://dali.sysykeji.top/Article/details/gtsqhkrryc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.andypj.xyz/Article/details/gtvclqczba.html

[Q70] 更新统计信息
来源：http://dali.xziqi.cn/Article/details/gttshpxcza.html

ANALYZE TABLE users;
来源：http://dali.haohaochexian.top/Article/details/gtplgbrutr.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gtmjpdrwcn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ivvv.top/Article/details/gtnffeenei.html

[Q72] 查看索引
来源：http://dali.andypj.xyz/Article/details/gtyvzsnzag.html

SHOW INDEX FROM users;
来源：http://dali.aizwys.cn/Article/details/gtybigqukk.html

[Q73] 查看表状态
来源：http://dali.daxiang520.top/Article/details/gtakixlvcg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cheryme.top/Article/details/gtfjgwbjer.html

[Q74] 强制使用索引
来源：http://dali.yuanzhike.top/Article/details/gtssyztgdg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.smart0.xyz/Article/details/gtdagoxcaq.html

[Q75] 日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gtmlrxetqe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtikpvdfdo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.fzhhl.top/Article/details/gtebbsjldg.html

[Q76] 按天统计
来源：http://dali.xziqi.cn/Article/details/gtqxogqfnj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tanke756.top/Article/details/gtirbcbzwd.html

[Q77] 时间加减
来源：http://dali.zhixingplan.top/Article/details/gtccywlgzm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigufen.top/Article/details/gtcgqxqomd.html

[Q78] 当前时间
来源：http://dali.xuanzx.com/Article/details/gtrnevzmvd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tianlin.xyz/Article/details/gtldgeygwi.html

[Q79] 字符串拼接
来源：http://dali.pycfn.com/Article/details/gtnuurwseh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aibaodan.cn/Article/details/gtqnzdfaik.html

[Q80] 字符串截取
来源：http://dali.redwolf501.top/Article/details/gtyfwbwzzr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtwhkozjug.html

[Q81] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gtpxucbnsy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.bjfxy.top/Article/details/gtamsqxsyj.html

[Q82] 字符长度与字节长度
来源：http://dali.xylfe.cn/Article/details/gthedopqqd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxygtuvv.html

[Q83] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gtsrwpqglj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sweek.top/Article/details/gtpinvfzeq.html

[Q84] 去除首尾空格
来源：http://dali.nwbrower.top/Article/details/gtfxsyeeic.html

SELECT TRIM(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtnngpamls.html

[Q85] 数值取整
来源：http://dali.jinghuilouyu.cn/Article/details/gtzyfmotzg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ybcxt.top/Article/details/gtdlpbqyeo.html

[Q86] 读取 JSON 字段
来源：http://dali.yangfankeji.com/Article/details/gtftssnqim.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.pycfn.com/Article/details/gtaxtbkbnc.html

[Q87] JSON 字段做条件
来源：http://dali.c1oappe.top/Article/details/gttexytqda.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tian-w.cn/Article/details/gtkfuulicf.html

[Q88] 行转列（条件聚合）
来源：http://dali.shangyingyoupin.top/Article/details/gtutuwgocp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xziqi.cn/Article/details/gtjjlroijj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtlncfdhcr.html

[Q89] 判断表是否存在
来源：http://dali.sysykeji.top/Article/details/gtdwmbgowt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ppjwa.cn/Article/details/gtguxntosk.html

[Q90] 生成序号列
来源：http://dali.yuanzhike.top/Article/details/gtmgltswus.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yanxiufei.cn/Article/details/gtmyydrznn.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtdnshlvsc.html

R. Bash 专题
来源：http://dali.ydzc1.top/Article/details/gtrhvwtqhd.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtndtrpeud.html

[R01] shebang 与严格模式
来源：http://dali.ehwqpu.com/Article/details/gtlqygbnci.html

#!/usr/bin/env bash
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzeusybqe.html

set -euo pipefail
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhyucuao.html

[R02] 变量赋值与使用
来源：http://dali.gaohongyu789.top/Article/details/gtgsrngrno.html

name="Tom"; echo "$name"
来源：http://dali.cucudq.cn/Article/details/gtmawpihxq.html

[R03] 只读变量
来源：http://dali.xuanzx.com/Article/details/gtjmshojgp.html

readonly PI=3.14
来源：http://dali.zycfv.cn/Article/details/gtacyrmzyc.html

[R04] 位置参数
来源：http://dali.jqgufenzy.top/Article/details/gtpirkddij.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.haohaochexian.top/Article/details/gtsxopcmdj.html

[R05] 参数默认值
来源：http://dali.yanxiufei.cn/Article/details/gtpybhxbay.html

name="${1:-default}"
来源：http://dali.quarkkingdee.top/Article/details/gtchaboeib.html

[R06] 判断命令是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtkyutnayz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jlsjyb.cn/Article/details/gtnforbpsj.html

[R07] if 判断文件
来源：http://dali.tianlin.xyz/Article/details/gtztbhsewm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nwbrower.top/Article/details/gtjdxfpxqf.html

[R08] 数值比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwbuwycp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.smart0.xyz/Article/details/gtassyhzfx.html

[R09] 字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gtznmeblov.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jiagoushi.top/Article/details/gtpiwvanre.html

[R10] 正则匹配
来源：http://dali.gogol.net.cn/Article/details/gtlgyykzgm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.0kj1m.cn/Article/details/gtnakeiutc.html

[R11] case 多分支
来源：http://dali.316326.xyz/Article/details/gtvicztzso.html

case "$1" in
来源：http://dali.havefunace.top/Article/details/gtewhgcfay.html

start) echo "启动" ;;
来源：http://dali.shzxlz.cn/Article/details/gtvsgrevkp.html

stop)  echo "停止" ;;
来源：http://dali.zhixingplan.top/Article/details/gtpuuqdzgx.html

*)     echo "未知命令" ;;
来源：http://dali.svipenyu.cn/Article/details/gtbiudmoic.html

esac
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhouhzks.html

[R12] for 遍历文件
来源：http://dali.meibo888.top/Article/details/gtmzmjqxzo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.daxiang520.top/Article/details/gtwebijmea.html

[R13] for 计数循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgnyzryr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.haohaochexian.top/Article/details/gtcgprjvzl.html

[R14] C 风格 for
来源：http://dali.jqgufenzy.top/Article/details/gtvijbqvyn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwfakylt.html

[R15] while 逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtzozxsexn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jqgufenzy.top/Article/details/gtsqtvxxfu.html

[R16] until 等待条件
来源：http://dali.zhiwuduotai.top/Article/details/gtindozblr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.smart0.xyz/Article/details/gtwxbjohdu.html

[R17] 数组定义与取值
来源：http://dali.jianghu66.top/Article/details/gthxyvmijk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ybcxt.top/Article/details/gtjcxjzocd.html

[R18] 遍历数组
来源：http://dali.zhengqikj.top/Article/details/gtyeellkoh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jiagoushi.top/Article/details/gttolizpbc.html

[R19] 数组长度
来源：http://dali.zycfv.cn/Article/details/gtkbxmltot.html

echo "${#arr[@]}"
来源：http://dali.yuxming.cn/Article/details/gtyhtxmuhn.html

[R20] 关联数组（字典）
来源：http://dali.shuidangran.top/Article/details/gtwettatml.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jyoumei.cn/Article/details/gtxehgtljb.html

[R21] 字符串长度
来源：http://dali.cheryme.top/Article/details/gttyrmhscm.html

echo "${#s}"
来源：http://dali.shangyingyoupin.top/Article/details/gtkxvxqnob.html

[R22] 截取子串
来源：http://dali.shzxlz.cn/Article/details/gtepbgehzn.html

echo "${s:0:5}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtimbpqqks.html

[R23] 字符串替换
来源：http://dali.daria6918.cn/Article/details/gtsmejphho.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sweek.top/Article/details/gtdqoborme.html

[R24] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gthnemgupg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shanyushiyangtech.top/Article/details/gttgraewov.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj20258888.top/Article/details/gtugmfwbwi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.birdmap.top/Article/details/gtvirtzrld.html

[R26] 命令替换
来源：http://dali.shzxlz.cn/Article/details/gtxomzdwsp.html

now=$(date +%F); echo "$now"
来源：http://dali.svipenyu.cn/Article/details/gtimhkpqrr.html

[R27] 算术展开
来源：http://dali.xuanzx.com/Article/details/gtspbrsqbc.html

echo $((1 + 2 * 3))
来源：http://dali.jianghu66.top/Article/details/gtazbtuqyr.html

[R28] 浮点运算
来源：http://dali.yueranfly.top/Article/details/gtlvxttddw.html

echo "scale=2; 10/3" | bc
来源：http://dali.cdnleiting.top/Article/details/gtoqwzpgvp.html

[R29] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gtnfwdakms.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenjidiqi.icu/Article/details/gtawmewkuo.html

[R30] 函数返回状态码
来源：http://dali.chenlongwang.top/Article/details/gtxffjhisx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xuetiantiany.cn/Article/details/gtbxienvpo.html

[R31] 局部变量
来源：http://dali.snrcjt.cn/Article/details/gtuxdbcldk.html

f() { local x=1; echo "$x"; }
来源：http://dali.cqqwz.cn/Article/details/gtqvmctgpc.html

[R32] 参数个数校验
来源：http://dali.jinqigufen.top/Article/details/gtvsmvwobk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gtuwgnswem.html

[R33] 捕获错误并提示行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudkobnli.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hongshengwenyu.top/Article/details/gtecmlnzyf.html

[R34] 退出时清理
来源：http://dali.tanke756.top/Article/details/gtnmlseijx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gogol.net.cn/Article/details/gtwxtxzdhf.html

[R35] 后台执行并等待
来源：http://dali.shuidangran.top/Article/details/gtulwdmopz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.9152youxi.cn/Article/details/gtcqflozcd.html

[R36] 并发执行多个任务
来源：http://dali.c1oappe.top/Article/details/gthzbbfhhd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xinyue.icu/Article/details/gtdkcpwwid.html

[R37] 把输出赋给变量
来源：http://dali.andypj.xyz/Article/details/gtbfcmhroj.html

files=$(ls -1)
来源：http://dali.yvedp.cn/Article/details/gtsenbcahx.html

[R38] 管道串联
来源：http://dali.dashuyun.cn/Article/details/gtgzwdlffk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigufen.top/Article/details/gtyeihmcpx.html

[R39] 重定向标准输出与错误
来源：http://dali.havefunace.top/Article/details/gtnzfewgpo.html

cmd > out.log 2>&1
来源：http://dali.ppjwa.cn/Article/details/gtoqtkjxhr.html

[R40] 追加写日志
来源：http://dali.redwolf501.top/Article/details/gtgextxuwh.html

echo "log" >> out.log
来源：http://dali.quarkkingdee.top/Article/details/gtiilojtrp.html

[R41] 丢弃输出
来源：http://dali.havefunace.top/Article/details/gtwekcksqe.html

cmd >/dev/null 2>&1
来源：http://dali.hywenlv.cn/Article/details/gtdagykndj.html

[R42] 输入重定向
来源：http://dali.fengsongda.top/Article/details/gtnwngfanl.html

wc -l < a.txt
来源：http://dali.zdqjudy.top/Article/details/gtzpijihhx.html

[R43] 按名字查找文件
来源：http://dali.hywenlv.cn/Article/details/gtjasgdrwf.html

find . -name "*.log" -type f
来源：http://dali.yj20258.top/Article/details/gtqvdrcblx.html

[R44] 按修改时间查找
来源：http://dali.birdmap.top/Article/details/gtczjrlxja.html

find . -mtime -7 -type f
来源：http://dali.yuanzhike.top/Article/details/gtjpezqjkt.html

[R45] 批量删除
来源：http://dali.yongpay.top/Article/details/gtiuaipoqm.html

find . -name "*.tmp" -delete
来源：http://dali.dianchejie.cn/Article/details/gtktomaynl.html

[R46] 递归替换文件内容
来源：http://dali.hnxiangtu.top/Article/details/gtduyjamur.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ehwqpu.com/Article/details/gtdozpkbkq.html

[R47] sed 单行替换
来源：http://dali.iojbl.cn/Article/details/gtlabowqea.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttduojiwn.html

[R48] awk 取指定列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagsydeii.html

awk '{print $1, $3}' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gterznwtsz.html

[R49] awk 带条件
来源：http://dali.snrcjt.cn/Article/details/gtrqwypncl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hammf.cn/Article/details/gtpqyxnxnb.html

[R50] awk 求和
来源：http://dali.xuanzx.com/Article/details/gtsdqzwmrs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtdhcpvkhc.html

[R51] 排序去重取前几
来源：http://dali.yuanzhike.top/Article/details/gtiisqjhek.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jianghu66.top/Article/details/gtqoifhjkj.html

[R52] 统计行数
来源：http://dali.tian-w.cn/Article/details/gtabjucvty.html

wc -l a.txt
来源：http://dali.xylfe.cn/Article/details/gtgjmjnttm.html

[R53] 查看文件头与实时尾
来源：http://dali.xuanzx.com/Article/details/gtmjjkaqjz.html


<!-- 参考信息 -->