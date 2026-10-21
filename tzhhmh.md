代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zdqjudy.top/Article/details/gtiyowftas.html

[Q05] 重命名列
来源：http://dali.jqgfzy.top/Article/details/gtsaxvirug.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jiagoushi.top/Article/details/gtnhedfbtw.html

[Q06] 删除列
来源：http://dali.fengsongda.top/Article/details/gtnyzbofps.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhgkycoh.html

[Q07] 删除表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwbzugll.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jiagoushi.top/Article/details/gthwokqoij.html

[Q08] 创建普通索引
来源：http://dali.yj20258888.top/Article/details/gtafyccngn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gtivxepubq.html

[Q09] 创建唯一索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteviakmdk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.dianchejie.cn/Article/details/gthvyhyjse.html

[Q10] 插入单行
来源：http://dali.feifeiyinyue.top/Article/details/gtpjcvactf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gtsybrcrar.html

[Q11] 一次插入多行
来源：http://dali.aizwys.cn/Article/details/gtrhinlnpp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hnqzz.top/Article/details/gtcgeehxtk.html

[Q12] 插入后取自增 ID
来源：http://dali.hnqzz.top/Article/details/gtwcjowqcg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangshuangyany.cn/Article/details/gtetwjmfma.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tian-w.cn/Article/details/gtznvkvdwk.html

[Q13] 忽略重复插入
来源：http://dali.sysykeji.top/Article/details/gtsnyuuczm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yonumen.top/Article/details/gtagyzhonn.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenlongwang.top/Article/details/gtwllvrajd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nanxuanxn.top/Article/details/gtzdgndfyn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.guowangkeji.top/Article/details/gtcvksszgd.html

[Q15] 查询全部
来源：http://dali.bjfxy.top/Article/details/gtiomtwwms.html

SELECT * FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtqpwhrzqu.html

[Q16] 查询指定列
来源：http://dali.dashuyun.cn/Article/details/gteldnblnn.html

SELECT id, name FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtfkvryeps.html

[Q17] 条件查询
来源：http://dali.wangdashe.top/Article/details/gtzxjbdofy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtkiktvqbi.html

[Q18] 模糊匹配
来源：http://dali.gogol.net.cn/Article/details/gtnnkament.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fengsongda.top/Article/details/gtkyuggwho.html

[Q19] 范围查询
来源：http://dali.dianchejie.cn/Article/details/gtzctymrhx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.9152youxi.cn/Article/details/gtstpkwyjf.html

[Q20] IN 列表
来源：http://dali.bjfxy.top/Article/details/gturwwhaxv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuanzhike.top/Article/details/gtavrrueca.html

[Q21] 空值判断
来源：http://dali.yj20258.top/Article/details/gtzggiwkqe.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttbxunfne.html

[Q22] 排序
来源：http://dali.zycfv.cn/Article/details/gtaoqtwcdg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yangfankeji.com/Article/details/gtuxslogra.html

[Q23] 分页
来源：http://dali.mhx1999.top/Article/details/gtgjfwnznt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jianghu66.top/Article/details/gtqjyqxpky.html

[Q24] 去重
来源：http://dali.quarkkingdee.top/Article/details/gtqdinqnmz.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtbomocezr.html

[Q25] 只取前 N 条
来源：http://dali.hammf.cn/Article/details/gtifqawuyi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nanxuanxn.top/Article/details/gtxigpujfq.html

[Q26] 计数
来源：http://dali.sysykeji.top/Article/details/gtjxuhehyo.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtwnouossl.html

[Q27] 条件计数
来源：http://dali.iojbl.cn/Article/details/gtujbqyoap.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtcuzuncws.html

[Q28] 求和与平均
来源：http://dali.zdqjudy.top/Article/details/gtcgdilcdx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtfdurqkjh.html

[Q29] 最大最小值
来源：http://dali.yuxming.cn/Article/details/gtuuxbghry.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtuwmfzkhy.html

[Q30] 分组统计
来源：http://dali.hfpthk.cn/Article/details/gtlanefqcq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gtrcrxrcpr.html

[Q31] 分组后过滤
来源：http://dali.yueranfly.top/Article/details/gtddylezib.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj20258888.top/Article/details/gtjlnwfdbi.html

[Q32] 分组拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gteoxzjgyh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gthxzkdjas.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.fengsongda.top/Article/details/gtxcurlxfx.html

[Q33] 多列分组
来源：http://dali.0kj1m.cn/Article/details/gttjlgyzpc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj20258.top/Article/details/gtdnnrcsar.html

[Q34] 每组取第一条
来源：http://dali.c1oappe.top/Article/details/gttaldjifc.html

SELECT * FROM (
来源：http://dali.0kj1m.cn/Article/details/gtsazjpyjp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhengqikj.top/Article/details/gtemymwbhj.html

) t WHERE rn = 1;
来源：http://dali.gogol.net.cn/Article/details/gtnfyhmliv.html

[Q35] 内连接
来源：http://dali.gaohongyu789.top/Article/details/gtnkrmbygm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gtkrrswxvh.html

[Q36] 左连接
来源：http://dali.xuanzx.com/Article/details/gtypwngaer.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gtzxmgzldk.html

[Q37] 右连接
来源：http://dali.yonumen.top/Article/details/gtfyssjhzl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj20258.top/Article/details/gtatfuuwqz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hywenlv.cn/Article/details/gtgahwbvay.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cheryme.top/Article/details/gtuawjnhyq.html

[Q39] 自连接（查上下级）
来源：http://dali.c1oappe.top/Article/details/gtzjusbshb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cheryme.top/Article/details/gtvqscbeva.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jqgfzy.top/Article/details/gtmuhvngpk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gogol.net.cn/Article/details/gttltfaizj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tanke756.top/Article/details/gtxbtaoity.html

[Q41] 多表连接
来源：http://dali.jlsjyb.cn/Article/details/gtkxpwqogf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj202588.top/Article/details/gtdhyxglif.html

JOIN users u ON u.id = o.user_id
来源：http://dali.mhx1999.top/Article/details/gtehyguxja.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zycfv.cn/Article/details/gtkpidoufz.html

[Q42] 连接条件附加过滤
来源：http://dali.daria6918.cn/Article/details/gtfhfminmo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.haohaochexian.top/Article/details/gtlmdddkpo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yangfankeji.com/Article/details/gtejigfbnw.html

[Q43] 标量子查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjdiznxr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.0kj1m.cn/Article/details/gtspnqjlyt.html

[Q44] IN 子查询
来源：http://dali.9152youxi.cn/Article/details/gtqpqpmcer.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.dashuyun.cn/Article/details/gtwvijtzvj.html

[Q45] EXISTS 判断存在
来源：http://dali.xuanzx.com/Article/details/gtrhckkpiu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nwbrower.top/Article/details/gtjucxlyhx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fzhhl.top/Article/details/gtoutzoyfg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gtnqyktjkk.html

[Q47] 与平均值比较
来源：http://dali.feifeiyinyue.top/Article/details/gthytztzez.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yvedp.cn/Article/details/gtemfgiybj.html

[Q48] CTE 公用表表达式
来源：http://dali.nanxinkj.top/Article/details/gtznzknwcl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jyoumei.cn/Article/details/gtjwtogbvz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenjidiqi.icu/Article/details/gttmbtuoiy.html

[Q49] 更新单行
来源：http://dali.daria6918.cn/Article/details/gthysdgovz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gtkcsfzhpe.html

[Q50] 批量更新
来源：http://dali.smart0.xyz/Article/details/gtbziuqorz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenlongwang.top/Article/details/gtdvqlriaw.html

[Q51] 用子查询更新
来源：http://dali.sxryk.cn/Article/details/gtncfapjuq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yongpay.top/Article/details/gtthegvfsw.html

[Q52] 删除指定行
来源：http://dali.shzxlz.cn/Article/details/gtndfmgwux.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gtopbsyata.html

[Q53] 按条件删除
来源：http://dali.zhiwuduotai.top/Article/details/gtfvsufizu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yangfankeji.com/Article/details/gtjsdahhkq.html

[Q54] 清空表
来源：http://dali.yj20258888.top/Article/details/gtyhgfdatl.html

TRUNCATE TABLE logs;
来源：http://dali.tianlin.xyz/Article/details/gtkughrprh.html

[Q55] 排名（并列占位）
来源：http://dali.aibaodan.cn/Article/details/gtnmdbnrry.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yanxiufei.cn/Article/details/gtajyyonbx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.fzhhl.top/Article/details/gtdxvsjhfm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yangfankeji.com/Article/details/gtwsjivobd.html

[Q57] 行号
来源：http://dali.yuxming.cn/Article/details/gtcjssjvzu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtuoyubmks.html

[Q58] 累计求和
来源：http://dali.zhoulong.xyz/Article/details/gtuyqrxjrl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtknpoilzl.html

[Q59] 分组内累计
来源：http://dali.mhx1999.top/Article/details/gtfgeyzbor.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtvfnwygqm.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenjidiqi.icu/Article/details/gtzqvsomhj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cqqwz.cn/Article/details/gtaggztcmr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtmclgswym.html

[Q61] 移动平均
来源：http://dali.yuxming.cn/Article/details/gtqtykrlle.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hammf.cn/Article/details/gtcoboxiep.html

[Q62] 分组占比
来源：http://dali.dianchejie.cn/Article/details/gtfoclqoem.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gtwvfnocol.html

[Q63] 开启事务
来源：http://dali.meibo888.top/Article/details/gtkwrkfsfc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.haohaochexian.top/Article/details/gtmblpkklo.html

[Q64] 提交事务
来源：http://dali.zhongyouzk.top/Article/details/gtwekchocs.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gtnikgevcj.html

[Q65] 回滚事务
来源：http://dali.cucudq.cn/Article/details/gtohwqpsyr.html

ROLLBACK;
来源：http://dali.bjfxy.top/Article/details/gtvaqdutco.html

[Q66] 行锁查询
来源：http://dali.guannengcc.top/Article/details/gtkaokmpmu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptnliqdz.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnqcstku.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zdqjudy.top/Article/details/gtnaqiajlc.html

[Q68] 保存点
来源：http://dali.tian-w.cn/Article/details/gtppexjsbc.html

SAVEPOINT sp1;
来源：http://dali.ppjwa.cn/Article/details/gtjqygprpo.html

ROLLBACK TO sp1;
来源：http://dali.yj20258.top/Article/details/gthyefvcnw.html

[Q69] 查看执行计划
来源：http://dali.zhengqikj.top/Article/details/gtenejklle.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shangyingyoupin.top/Article/details/gtjfpyolbi.html

[Q70] 更新统计信息
来源：http://dali.tian-w.cn/Article/details/gtonpxnrqr.html

ANALYZE TABLE users;
来源：http://dali.birdmap.top/Article/details/gtzlmjwsqj.html

[Q71] 查看建表语句
来源：http://dali.nwbrower.top/Article/details/gtzfiorjhi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.svipenyu.cn/Article/details/gtdjxrladr.html

[Q72] 查看索引
来源：http://dali.gotoacloud.top/Article/details/gtjlqdzyla.html

SHOW INDEX FROM users;
来源：http://dali.yueranfly.top/Article/details/gtbxdkahxg.html

[Q73] 查看表状态
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfrdgjoc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cheryme.top/Article/details/gtyhpxnpmw.html

[Q74] 强制使用索引
来源：http://dali.pengpengdd.cyou/Article/details/gtieyvjadd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ppjwa.cn/Article/details/gtmxfngbbf.html

[Q75] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gtigkqehfw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtkytsqnrc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangdashe.top/Article/details/gthrhgqvxs.html

[Q76] 按天统计
来源：http://dali.zycfv.cn/Article/details/gtucfjqmjf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zdqjudy.top/Article/details/gtiptapqfz.html

[Q77] 时间加减
来源：http://dali.mhx1999.top/Article/details/gtnwwgwiiq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.kuanghao11.cn/Article/details/gtxzreodye.html

[Q78] 当前时间
来源：http://dali.xinyue.icu/Article/details/gtarhencmu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuanzx.com/Article/details/gtkwewjzaf.html

[Q79] 字符串拼接
来源：http://dali.havefunace.top/Article/details/gtfhvvlryo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cucudq.cn/Article/details/gtfphddkxx.html

[Q80] 字符串截取
来源：http://dali.andypj.xyz/Article/details/gtiuljwymb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtetgtsplp.html

[Q81] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gtjcmrluql.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtxpuocnxe.html

[Q82] 字符长度与字节长度
来源：http://dali.cdnleiting.top/Article/details/gtmxudyala.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtentbztba.html

[Q83] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gtcaqlpmou.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtukhygimf.html

[Q84] 去除首尾空格
来源：http://dali.9152youxi.cn/Article/details/gttewcnrwz.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtxwvkjxjd.html

[Q85] 数值取整
来源：http://dali.iojbl.cn/Article/details/gtjmxlkmus.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbmmociq.html

[Q86] 读取 JSON 字段
来源：http://dali.dashuyun.cn/Article/details/gtvctrxtpj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jiagoushi.top/Article/details/gtpstmcddn.html

[Q87] JSON 字段做条件
来源：http://dali.yanxiufei.cn/Article/details/gtwnkmitpk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.andypj.xyz/Article/details/gtcvzsheue.html

[Q88] 行转列（条件聚合）
来源：http://dali.hysaishi.cn/Article/details/gtbozqntxj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nwbrower.top/Article/details/gtgrfttqfa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtgbfjgksj.html

[Q89] 判断表是否存在
来源：http://dali.redwolf501.top/Article/details/gtssnjomvb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtscvqqxfx.html

[Q90] 生成序号列
来源：http://dali.iojbl.cn/Article/details/gteirvusan.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xylfe.cn/Article/details/gtnuiqtyet.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtoitbdbfn.html

R. Bash 专题
来源：http://dali.tanke756.top/Article/details/gtytpxzjqu.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtyvraaamy.html

[R01] shebang 与严格模式
来源：http://dali.cdnleiting.top/Article/details/gtbecuokfi.html

#!/usr/bin/env bash
来源：http://dali.c1oappe.top/Article/details/gtafqpyiba.html

set -euo pipefail
来源：http://dali.cdnleiting.top/Article/details/gtsmocdoyo.html

[R02] 变量赋值与使用
来源：http://dali.zhixingplan.top/Article/details/gtqpphgetr.html

name="Tom"; echo "$name"
来源：http://dali.snrcjt.cn/Article/details/gtxvlwjrxs.html

[R03] 只读变量
来源：http://dali.hammf.cn/Article/details/gtazjsboiz.html

readonly PI=3.14
来源：http://dali.shangyingyoupin.top/Article/details/gtswhmloou.html

[R04] 位置参数
来源：http://dali.hfpthk.cn/Article/details/gtnsolixfx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.snrcjt.cn/Article/details/gtjtfviyyw.html

[R05] 参数默认值
来源：http://dali.cqqwz.cn/Article/details/gtiakmudwv.html

name="${1:-default}"
来源：http://dali.yj20258.top/Article/details/gtwzktzjms.html

[R06] 判断命令是否存在
来源：http://dali.hywenlv.cn/Article/details/gtofhlyvim.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.meibo888.top/Article/details/gtcrvrgjms.html

[R07] if 判断文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqodmnfw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.havefunace.top/Article/details/gteydhrxut.html

[R08] 数值比较
来源：http://dali.sxryk.cn/Article/details/gtycfykiyb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sweek.top/Article/details/gtsiowlvxr.html

[R09] 字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gtnooxuylr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tianlin.xyz/Article/details/gtfittmycj.html

[R10] 正则匹配
来源：http://dali.tian-w.cn/Article/details/gttzaylrvu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hammf.cn/Article/details/gtlfyuhchz.html

[R11] case 多分支
来源：http://dali.haohaochexian.top/Article/details/gtbngwihcn.html

case "$1" in
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtchynxwtw.html

start) echo "启动" ;;
来源：http://dali.yangfankeji.com/Article/details/gtjgimuyii.html

stop)  echo "停止" ;;
来源：http://dali.ppjwa.cn/Article/details/gttftfiajf.html

*)     echo "未知命令" ;;
来源：http://dali.sweek.top/Article/details/gtszycwyyr.html

esac
来源：http://dali.mhx1999.top/Article/details/gtykuvjxfz.html

[R12] for 遍历文件
来源：http://dali.hammf.cn/Article/details/gtuymynkwh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yuxming.cn/Article/details/gttqbfbkhx.html

[R13] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarrngbzs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gtnrdiyjzg.html

[R14] C 风格 for
来源：http://dali.zycfv.cn/Article/details/gtbxlarmzm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.316326.xyz/Article/details/gtajsxegna.html

[R15] while 逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtfbvtojfh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cashguo.top/Article/details/gtatkikksk.html

[R16] until 等待条件
来源：http://dali.aibaodan.cn/Article/details/gtlfgrzqqn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ehwqpu.com/Article/details/gtsfiiwqfy.html

[R17] 数组定义与取值
来源：http://dali.hywenlv.cn/Article/details/gttehdfmdx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258888.top/Article/details/gtiuuviwrp.html

[R18] 遍历数组
来源：http://dali.tanke756.top/Article/details/gtflyjhrdw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cdnleiting.top/Article/details/gtwaofnxrd.html

[R19] 数组长度
来源：http://dali.yueranfly.top/Article/details/gtzmzsnndv.html

echo "${#arr[@]}"
来源：http://dali.aibaodan.cn/Article/details/gtzlgdyzzx.html

[R20] 关联数组（字典）
来源：http://dali.yueranfly.top/Article/details/gtkwdbdcte.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.vqdsnc.cn/Article/details/gtkpcyktry.html

[R21] 字符串长度
来源：http://dali.0kj1m.cn/Article/details/gtaeryageb.html

echo "${#s}"
来源：http://dali.yueranfly.top/Article/details/gtvuyilqra.html

[R22] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gtwhwrcrzb.html

echo "${s:0:5}"
来源：http://dali.yuxming.cn/Article/details/gtixlbvcdc.html

[R23] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gtxnyygklu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zdqjudy.top/Article/details/gtgvypapoa.html

[R24] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gtxxnhiqrc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sysykeji.top/Article/details/gtkwzrekgv.html

[R25] 去后缀 / 去前缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezmqavxo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ehwqpu.com/Article/details/gtvnzsjmdm.html

[R26] 命令替换
来源：http://dali.gzhubu.top/Article/details/gtbysigmjr.html

now=$(date +%F); echo "$now"
来源：http://dali.sysykeji.top/Article/details/gtjzfjspee.html

[R27] 算术展开
来源：http://dali.feifeiyinyue.top/Article/details/gthmxsbsed.html

echo $((1 + 2 * 3))
来源：http://dali.cdnleiting.top/Article/details/gtixcaauwd.html

[R28] 浮点运算
来源：http://dali.yueranfly.top/Article/details/gtytcrjrgz.html

echo "scale=2; 10/3" | bc
来源：http://dali.gogol.net.cn/Article/details/gtavegoaei.html

[R29] 定义函数
来源：http://dali.ehwqpu.com/Article/details/gtizyahful.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gtoxootfqk.html

[R30] 函数返回状态码
来源：http://dali.guowangkeji.top/Article/details/gtwaluosrl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yueranfly.top/Article/details/gtohcczkye.html

[R31] 局部变量
来源：http://dali.ppjwa.cn/Article/details/gtyzpgicuj.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxinkj.top/Article/details/gttmcumsor.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gtzdvphkgp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbgjzsmo.html

[R33] 捕获错误并提示行号
来源：http://dali.xuetiantiany.cn/Article/details/gtqdenjgqz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.c1oappe.top/Article/details/gtxucpjdgz.html

[R34] 退出时清理
来源：http://dali.redwolf501.top/Article/details/gtggmpmzpf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gtyvnmvaei.html

[R35] 后台执行并等待
来源：http://dali.ppjwa.cn/Article/details/gtiuqfctjx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nanxuanxn.top/Article/details/gthyplfgfp.html

[R36] 并发执行多个任务
来源：http://dali.cashguo.top/Article/details/gtpogyvhcg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.guowangkeji.top/Article/details/gtobjryaxa.html

[R37] 把输出赋给变量
来源：http://dali.gogol.net.cn/Article/details/gttbmhpdaf.html

files=$(ls -1)
来源：http://dali.nanxuanxn.top/Article/details/gttuwscuwp.html

[R38] 管道串联
来源：http://dali.shanyushiyangtech.top/Article/details/gtgphkbmel.html

cat a.txt | grep -i error | wc -l
来源：http://dali.bjfxy.top/Article/details/gtkfulhslu.html

[R39] 重定向标准输出与错误
来源：http://dali.redwolf501.top/Article/details/gtfxqhmzde.html

cmd > out.log 2>&1
来源：http://dali.sufxvd.cn/Article/details/gtdfwztfil.html

[R40] 追加写日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvupeckv.html

echo "log" >> out.log
来源：http://dali.yj20258.top/Article/details/gtiugamnsb.html

[R41] 丢弃输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwbvzysu.html

cmd >/dev/null 2>&1
来源：http://dali.iojbl.cn/Article/details/gtoqnvuimz.html

[R42] 输入重定向
来源：http://dali.jinghuilouyu.cn/Article/details/gtjirmrmce.html

wc -l < a.txt
来源：http://dali.jianghu66.top/Article/details/gtvprlxhsu.html

[R43] 按名字查找文件
来源：http://dali.gaohongyu789.top/Article/details/gtrfjsacal.html

find . -name "*.log" -type f
来源：http://dali.ehwqpu.com/Article/details/gtjuswfbdu.html

[R44] 按修改时间查找
来源：http://dali.yj20258.top/Article/details/gtvtbdsimb.html

find . -mtime -7 -type f
来源：http://dali.jqgfzy.top/Article/details/gtnklifqje.html

[R45] 批量删除
来源：http://dali.tian-w.cn/Article/details/gtxkjfbadl.html

find . -name "*.tmp" -delete
来源：http://dali.vqdsnc.cn/Article/details/gtnjexuusm.html

[R46] 递归替换文件内容
来源：http://dali.hnxiangtu.top/Article/details/gtmsbisvep.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.feifeiyinyue.top/Article/details/gtzhrhccgf.html

[R47] sed 单行替换
来源：http://dali.ydzc1.top/Article/details/gtrqamfaun.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tian-w.cn/Article/details/gtdlqhkyls.html

[R48] awk 取指定列
来源：http://dali.9152youxi.cn/Article/details/gtdknyhwyj.html

awk '{print $1, $3}' a.txt
来源：http://dali.andypj.xyz/Article/details/gtboyotcdz.html

[R49] awk 带条件
来源：http://dali.shuidangran.top/Article/details/gtlyreyfxc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.havefunace.top/Article/details/gtxittipoa.html

[R50] awk 求和
来源：http://dali.chenjidiqi.icu/Article/details/gtdbybmkxq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.mhx1999.top/Article/details/gtepieufqd.html

[R51] 排序去重取前几
来源：http://dali.aizwys.cn/Article/details/gtowbmngln.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxinkj.top/Article/details/gtwmjcgprd.html

[R52] 统计行数
来源：http://dali.dianchejie.cn/Article/details/gtqypjdyxr.html

wc -l a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtkgaodfis.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgufenzy.top/Article/details/gtsjonxpcw.html


<!-- 参考信息 -->