代发 wailian999

);
来源：http://dali.cashguo.top/Article/details/gtxgbyiytv.html

[Q03] 增加列
来源：http://dali.havefunace.top/Article/details/gtmdqyvrtb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.mhx1999.top/Article/details/gtghpsdlod.html

[Q04] 修改列类型
来源：http://dali.hammf.cn/Article/details/gtbjknsxxa.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.haohaochexian.top/Article/details/gtjsorxece.html

[Q05] 重命名列
来源：http://dali.tanke756.top/Article/details/gtdwclxbac.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jyoumei.cn/Article/details/gtlkxmhkad.html

[Q06] 删除列
来源：http://dali.hammf.cn/Article/details/gtpjobhwus.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jianghu66.top/Article/details/gtoussvmau.html

[Q07] 删除表
来源：http://dali.fengsongda.top/Article/details/gtgaxejgor.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yuanzhike.top/Article/details/gtnmprqieu.html

[Q08] 创建普通索引
来源：http://dali.birdmap.top/Article/details/gtbnudpdtb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gtekaxrdww.html

[Q09] 创建唯一索引
来源：http://dali.gogol.net.cn/Article/details/gtvoebxtzw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gtcdgsfbul.html

[Q10] 插入单行
来源：http://dali.jianghu66.top/Article/details/gtusgqsfpv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gtsxtleprz.html

[Q11] 一次插入多行
来源：http://dali.shuidangran.top/Article/details/gttnjucoab.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gogol.net.cn/Article/details/gtwiblipsx.html

[Q12] 插入后取自增 ID
来源：http://dali.xuanzx.com/Article/details/gthaklxxhz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yuxming.cn/Article/details/gtnwlrabdj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.feifeiyinyue.top/Article/details/gtvvvyczvs.html

[Q13] 忽略重复插入
来源：http://dali.xinyue.icu/Article/details/gtdsaqvkqz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtjjkwrirg.html

[Q14] 存在则更新（upsert）
来源：http://dali.guannengcc.top/Article/details/gtuhqavrpw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shuidangran.top/Article/details/gtmdqpedzw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jlsjyb.cn/Article/details/gtebhdtadj.html

[Q15] 查询全部
来源：http://dali.dashuyun.cn/Article/details/gtpccsqpsp.html

SELECT * FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtkolwtagb.html

[Q16] 查询指定列
来源：http://dali.nwbrower.top/Article/details/gtccszxcmf.html

SELECT id, name FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtigxavgpp.html

[Q17] 条件查询
来源：http://dali.yueranfly.top/Article/details/gtyvppzatw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jianghu66.top/Article/details/gtttffhnhy.html

[Q18] 模糊匹配
来源：http://dali.zhixingplan.top/Article/details/gtbcstvgjh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.smart0.xyz/Article/details/gtpzdhtvnd.html

[Q19] 范围查询
来源：http://dali.yueranfly.top/Article/details/gtsdfdezhd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhoulong.xyz/Article/details/gteculixgh.html

[Q20] IN 列表
来源：http://dali.pengpengdd.cyou/Article/details/gtgxrngmso.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.kuanghao11.cn/Article/details/gtnvtirupt.html

[Q21] 空值判断
来源：http://dali.cucudq.cn/Article/details/gtfwjwgess.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj20258.top/Article/details/gtvbkndyqr.html

[Q22] 排序
来源：http://dali.zhoulong.xyz/Article/details/gtayijspta.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzaitsagd.html

[Q23] 分页
来源：http://dali.zhixingplan.top/Article/details/gtcobbudme.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hywenlv.cn/Article/details/gtcremmyyl.html

[Q24] 去重
来源：http://dali.xuanzx.com/Article/details/gtuvorelhw.html

SELECT DISTINCT city FROM users;
来源：http://dali.yongpay.top/Article/details/gtvnpmtgae.html

[Q25] 只取前 N 条
来源：http://dali.yueranfly.top/Article/details/gtuwdzohdr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfevuiwhi.html

[Q26] 计数
来源：http://dali.dashuyun.cn/Article/details/gtcruwnrkp.html

SELECT COUNT(*) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtjuespore.html

[Q27] 条件计数
来源：http://dali.jiagoushi.top/Article/details/gtyrunuzuh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtgufabtoo.html

[Q28] 求和与平均
来源：http://dali.jianghu66.top/Article/details/gtouleaziw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcpqdtkho.html

[Q29] 最大最小值
来源：http://dali.gotoacloud.top/Article/details/gtssdwdmal.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tanke756.top/Article/details/gthcjkvjyl.html

[Q30] 分组统计
来源：http://dali.pengpengdd.cyou/Article/details/gtdwlejsqg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gtgfremazx.html

[Q31] 分组后过滤
来源：http://dali.bjfxy.top/Article/details/gteexjmcsh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cdnleiting.top/Article/details/gtgpttcadt.html

[Q32] 分组拼接字符串
来源：http://dali.c1oappe.top/Article/details/gttiybqcgj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gtrheqjnwo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.pycfn.com/Article/details/gtwmkjokma.html

[Q33] 多列分组
来源：http://dali.jianghu66.top/Article/details/gtxpzuvdpd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yongpay.top/Article/details/gtqhwvlnbw.html

[Q34] 每组取第一条
来源：http://dali.sysykeji.top/Article/details/gtlonlwydq.html

SELECT * FROM (
来源：http://dali.jqgufenzy.top/Article/details/gtwffpizly.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tianlin.xyz/Article/details/gttasoyoad.html

) t WHERE rn = 1;
来源：http://dali.hfpthk.cn/Article/details/gtdilfidgs.html

[Q35] 内连接
来源：http://dali.bjfxy.top/Article/details/gtjhmuizmg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ehwqpu.com/Article/details/gttsmcbuzi.html

[Q36] 左连接
来源：http://dali.sweek.top/Article/details/gtuclxczxq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dianchejie.cn/Article/details/gtsswmdgih.html

[Q37] 右连接
来源：http://dali.9152youxi.cn/Article/details/gtkvnrpmfi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sysykeji.top/Article/details/gtxrbgxcjm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tianlin.xyz/Article/details/gtnmvedtyk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenlongwang.top/Article/details/gtveblukug.html

[Q39] 自连接（查上下级）
来源：http://dali.yuxming.cn/Article/details/gtwdfzslgo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.smart0.xyz/Article/details/gtqwxmlyet.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zycfv.cn/Article/details/gtyiauwgnb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenzaomai.com/Article/details/gtzlvsbjck.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhiwuduotai.top/Article/details/gtlzcqmyqn.html

[Q41] 多表连接
来源：http://dali.ivvv.top/Article/details/gtrbxugmvb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gotoacloud.top/Article/details/gtvmmgejfr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xuetiantiany.cn/Article/details/gtfcfkxnmj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zdqjudy.top/Article/details/gtmhavumcl.html

[Q42] 连接条件附加过滤
来源：http://dali.cashguo.top/Article/details/gtflohdddm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cqqwz.cn/Article/details/gtossntndr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvspoknqc.html

[Q43] 标量子查询
来源：http://dali.hnqzz.top/Article/details/gtrohrveqe.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yongpay.top/Article/details/gtggqzztsd.html

[Q44] IN 子查询
来源：http://dali.smart0.xyz/Article/details/gtjgwfuksa.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ybcxt.top/Article/details/gtnerqnfzv.html

[Q45] EXISTS 判断存在
来源：http://dali.gogol.net.cn/Article/details/gtoympbhcx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gtybtvbewi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.daxiang520.top/Article/details/gtednhdoey.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tanke756.top/Article/details/gtchabplen.html

[Q47] 与平均值比较
来源：http://dali.mhx1999.top/Article/details/gtkoqxxwcw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xuanzx.com/Article/details/gtpkltmklu.html

[Q48] CTE 公用表表达式
来源：http://dali.fengsongda.top/Article/details/gttyohfssk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yonumen.top/Article/details/gtxgikjxrk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.guannengcc.top/Article/details/gtfueqkjgl.html

[Q49] 更新单行
来源：http://dali.cdnleiting.top/Article/details/gthmmwonlc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gtzcsjzwts.html

[Q50] 批量更新
来源：http://dali.jyoumei.cn/Article/details/gtwbqhskfo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gtapryzvve.html

[Q51] 用子查询更新
来源：http://dali.tianlin.xyz/Article/details/gtiwljqhbc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtwisznnag.html

[Q52] 删除指定行
来源：http://dali.ehwqpu.com/Article/details/gtekedgiqg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.guowangkeji.top/Article/details/gtuwvhjqnj.html

[Q53] 按条件删除
来源：http://dali.chenjidiqi.icu/Article/details/gtrbjdrkqd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.wangdashe.top/Article/details/gtkpurxtxh.html

[Q54] 清空表
来源：http://dali.cdnleiting.top/Article/details/gttatmkjna.html

TRUNCATE TABLE logs;
来源：http://dali.hnxiangtu.top/Article/details/gtqcmlcrkz.html

[Q55] 排名（并列占位）
来源：http://dali.yangfankeji.com/Article/details/gtyyhpcoht.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.aizwys.cn/Article/details/gtqucuindr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xylfe.cn/Article/details/gtqhktjxqq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinqigfzy.top/Article/details/gtlxmwqcse.html

[Q57] 行号
来源：http://dali.jyoumei.cn/Article/details/gtqzpxrbsg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.aizwys.cn/Article/details/gtspqlnyxi.html

[Q58] 累计求和
来源：http://dali.xuanzx.com/Article/details/gturkhztjy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtughxpnhr.html

[Q59] 分组内累计
来源：http://dali.iojbl.cn/Article/details/gtovddhwqy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yonumen.top/Article/details/gtvglpjyet.html

[Q60] 取上一行 / 下一行
来源：http://dali.zdqjudy.top/Article/details/gtwhfbzqff.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jqgfzy.top/Article/details/gtzeahdwvi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.havefunace.top/Article/details/gtmpeygzxq.html

[Q61] 移动平均
来源：http://dali.shanyushiyangtech.top/Article/details/gtlyavmhys.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtmjliywgj.html

[Q62] 分组占比
来源：http://dali.hammf.cn/Article/details/gtwopmoqrw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gtzkmqkudx.html

[Q63] 开启事务
来源：http://dali.yanxiufei.cn/Article/details/gtkjujwgxd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yuanzhike.top/Article/details/gtluwlkfcb.html

[Q64] 提交事务
来源：http://dali.yangfankeji.com/Article/details/gtcpxijetm.html

COMMIT;
来源：http://dali.zhengqikj.top/Article/details/gtslyqwrnw.html

[Q65] 回滚事务
来源：http://dali.hammf.cn/Article/details/gtegsgbwvt.html

ROLLBACK;
来源：http://dali.daxiang520.top/Article/details/gtlzynnbau.html

[Q66] 行锁查询
来源：http://dali.iojbl.cn/Article/details/gtppigjtui.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.daxiang520.top/Article/details/gtcvaqixxw.html

[Q67] 设置隔离级别
来源：http://dali.shuidangran.top/Article/details/gtjgmpcmuf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.wangshuangyany.cn/Article/details/gtmodkcwkr.html

[Q68] 保存点
来源：http://dali.sysykeji.top/Article/details/gtmoqrwfyy.html

SAVEPOINT sp1;
来源：http://dali.ivvv.top/Article/details/gtsfkhlmbk.html

ROLLBACK TO sp1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgyajspx.html

[Q69] 查看执行计划
来源：http://dali.jinghuilouyu.cn/Article/details/gtsukhjpwc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.9152youxi.cn/Article/details/gtarvsuzuf.html

[Q70] 更新统计信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykfzwmvt.html

ANALYZE TABLE users;
来源：http://dali.nanxuanxn.top/Article/details/gtadasvyyh.html

[Q71] 查看建表语句
来源：http://dali.ppjwa.cn/Article/details/gtllbzdqjz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.0kj1m.cn/Article/details/gtbkmctslh.html

[Q72] 查看索引
来源：http://dali.feifeiyinyue.top/Article/details/gtjulooiyf.html

SHOW INDEX FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxggzqyly.html

[Q73] 查看表状态
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpcvuptex.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xuetiantiany.cn/Article/details/gtsojhdilp.html

[Q74] 强制使用索引
来源：http://dali.jqgufenzy.top/Article/details/gtmsjlmvcv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gtaccsmqwz.html

[Q75] 日期格式化
来源：http://dali.xinyue.icu/Article/details/gttmunngwj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtixdbxllo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nwbrower.top/Article/details/gtsssxjcly.html

[Q76] 按天统计
来源：http://dali.kuanghao11.cn/Article/details/gtyptaklrb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxinkj.top/Article/details/gtryynxile.html

[Q77] 时间加减
来源：http://dali.redwolf501.top/Article/details/gtxbsnnfrn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.meibo888.top/Article/details/gtmmxgwejd.html

[Q78] 当前时间
来源：http://dali.ehwqpu.com/Article/details/gtkqcwuins.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxuanxn.top/Article/details/gtqpvdtqzl.html

[Q79] 字符串拼接
来源：http://dali.wangdashe.top/Article/details/gtvsewclue.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yuxming.cn/Article/details/gtyorphjfq.html

[Q80] 字符串截取
来源：http://dali.smart0.xyz/Article/details/gtikwfffju.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gthqdexdje.html

[Q81] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxjzzcen.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqnyoolap.html

[Q82] 字符长度与字节长度
来源：http://dali.ehwqpu.com/Article/details/gtfnemcqde.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtxxknsaga.html

[Q83] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gtdqyrbgfa.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtobdaatbh.html

[Q84] 去除首尾空格
来源：http://dali.xylfe.cn/Article/details/gtfwhcaeql.html

SELECT TRIM(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtphiepgio.html

[Q85] 数值取整
来源：http://dali.yuanzhike.top/Article/details/gtmwwhxjgm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hongshengwenyu.top/Article/details/gtqljdfsgm.html

[Q86] 读取 JSON 字段
来源：http://dali.zhiwuduotai.top/Article/details/gtfotwbdkp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.daxiang520.top/Article/details/gtozsabrjx.html

[Q87] JSON 字段做条件
来源：http://dali.yj20258888.top/Article/details/gtowaclgdu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangdashe.top/Article/details/gtgqkyqzbz.html

[Q88] 行转列（条件聚合）
来源：http://dali.nwbrower.top/Article/details/gtdqzvyetb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yuanzhike.top/Article/details/gtkrilsjpo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtpwzkjbnv.html

[Q89] 判断表是否存在
来源：http://dali.jqgufenzy.top/Article/details/gtpgaqygwi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.guowangkeji.top/Article/details/gtxtphjfrr.html

[Q90] 生成序号列
来源：http://dali.9152youxi.cn/Article/details/gtrsmbwdnp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aibaodan.cn/Article/details/gtckgviinq.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtymouvvzx.html

R. Bash 专题
来源：http://dali.yj20258.top/Article/details/gtgcqylguv.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtwpcxmvgg.html

[R01] shebang 与严格模式
来源：http://dali.chenjidiqi.icu/Article/details/gttslxluat.html

#!/usr/bin/env bash
来源：http://dali.chenzaomai.com/Article/details/gtamquyulh.html

set -euo pipefail
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtolpehllz.html

[R02] 变量赋值与使用
来源：http://dali.pycfn.com/Article/details/gttcjrfbij.html

name="Tom"; echo "$name"
来源：http://dali.yangfankeji.com/Article/details/gtquhqtdgx.html

[R03] 只读变量
来源：http://dali.tianlin.xyz/Article/details/gttzuicnhh.html

readonly PI=3.14
来源：http://dali.jinqigufen.top/Article/details/gtfvcslkfy.html

[R04] 位置参数
来源：http://dali.hongshengwenyu.top/Article/details/gtcbzygpwr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sweek.top/Article/details/gtdpkvgyub.html

[R05] 参数默认值
来源：http://dali.c1oappe.top/Article/details/gtqxlgseoi.html

name="${1:-default}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiinkoyjr.html

[R06] 判断命令是否存在
来源：http://dali.xylfe.cn/Article/details/gtsqyukvak.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gtsrhhcojq.html

[R07] if 判断文件
来源：http://dali.pengpengdd.cyou/Article/details/gtbyhtcmcc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daxiang520.top/Article/details/gtfsvzgzvt.html

[R08] 数值比较
来源：http://dali.nanxuanxn.top/Article/details/gtdhdtszwr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtqeyqtanu.html

[R09] 字符串比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxibstyvs.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gttehtrdgo.html

[R10] 正则匹配
来源：http://dali.shuidangran.top/Article/details/gtzptyfgbb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtkywkrxey.html

[R11] case 多分支
来源：http://dali.hongshengwenyu.top/Article/details/gtmnbmtwvm.html

case "$1" in
来源：http://dali.jyoumei.cn/Article/details/gtauxonrsx.html

start) echo "启动" ;;
来源：http://dali.guannengcc.top/Article/details/gtnhnqywze.html

stop)  echo "停止" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtveviejmm.html

*)     echo "未知命令" ;;
来源：http://dali.hnqzz.top/Article/details/gtwfuhxagv.html

esac
来源：http://dali.zhengqikj.top/Article/details/gtsvyumrmq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gtzvxcbiff.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258.top/Article/details/gtzhskfrng.html

[R13] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkoakixrb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gtnmhyjkqw.html

[R14] C 风格 for
来源：http://dali.hongshengwenyu.top/Article/details/gtpqctonlx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gtnwzipgfj.html

[R15] while 逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtlqkjnqdm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenzaomai.com/Article/details/gtjeruyrrz.html

[R16] until 等待条件
来源：http://dali.gaohongyu789.top/Article/details/gtsjdexqoy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xziqi.cn/Article/details/gtybxlvmme.html

[R17] 数组定义与取值
来源：http://dali.gaohongyu789.top/Article/details/gtotbtwcsk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.316326.xyz/Article/details/gtyeepvytq.html

[R18] 遍历数组
来源：http://dali.nanxuanxn.top/Article/details/gtwpzczvyh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtgfdbclno.html

[R19] 数组长度
来源：http://dali.aibaodan.cn/Article/details/gtcjafrses.html

echo "${#arr[@]}"
来源：http://dali.xziqi.cn/Article/details/gtfsioiybs.html

[R20] 关联数组（字典）
来源：http://dali.dianchejie.cn/Article/details/gtzhidbcri.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.aibaodan.cn/Article/details/gtpwlvvgxh.html

[R21] 字符串长度
来源：http://dali.hysaishi.cn/Article/details/gtqnrxtoet.html

echo "${#s}"
来源：http://dali.mhx1999.top/Article/details/gtynwtmfok.html

[R22] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gtejqtyowc.html

echo "${s:0:5}"
来源：http://dali.cucudq.cn/Article/details/gtfeckszsa.html

[R23] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gtmbzycbhm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhengqikj.top/Article/details/gtjnweikwc.html

[R24] 大小写转换
来源：http://dali.cashguo.top/Article/details/gtlcuhwexh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenlongwang.top/Article/details/gtnakzgmwj.html

[R25] 去后缀 / 去前缀
来源：http://dali.yangfankeji.com/Article/details/gthsootyss.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jyoumei.cn/Article/details/gtbskmlvwp.html

[R26] 命令替换
来源：http://dali.gotoacloud.top/Article/details/gtnbvkzztj.html

now=$(date +%F); echo "$now"
来源：http://dali.hysaishi.cn/Article/details/gtbnypuuoc.html

[R27] 算术展开
来源：http://dali.snrcjt.cn/Article/details/gtqqtodmdq.html

echo $((1 + 2 * 3))
来源：http://dali.svipenyu.cn/Article/details/gtonavoadh.html

[R28] 浮点运算
来源：http://dali.haohaochexian.top/Article/details/gthobnpzrc.html

echo "scale=2; 10/3" | bc
来源：http://dali.shuidangran.top/Article/details/gtmexkhpmp.html

[R29] 定义函数
来源：http://dali.hysaishi.cn/Article/details/gtgjhvquta.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuanzx.com/Article/details/gttbvklbnw.html

[R30] 函数返回状态码
来源：http://dali.hysaishi.cn/Article/details/gtmcukdrdl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dashuyun.cn/Article/details/gttwhfvasx.html

[R31] 局部变量
来源：http://dali.andypj.xyz/Article/details/gtfqvgysgj.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzitaadwp.html

[R32] 参数个数校验
来源：http://dali.sxryk.cn/Article/details/gtsnauypyg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqkemgkj.html

[R33] 捕获错误并提示行号
来源：http://dali.guannengcc.top/Article/details/gtlzufdfid.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xziqi.cn/Article/details/gtrnaavzqc.html

[R34] 退出时清理
来源：http://dali.snrcjt.cn/Article/details/gteulskzol.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gtsdnvxikj.html

[R35] 后台执行并等待
来源：http://dali.yj20258888.top/Article/details/gtvxiptzcx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.feifeiyinyue.top/Article/details/gtqwbtsvcz.html

[R36] 并发执行多个任务
来源：http://dali.kuanghao11.cn/Article/details/gtkgamkbbv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pycfn.com/Article/details/gtwrwqolwg.html

[R37] 把输出赋给变量
来源：http://dali.chenjidiqi.icu/Article/details/gtkgbhddfy.html

files=$(ls -1)
来源：http://dali.tanke756.top/Article/details/gtlorzdojj.html

[R38] 管道串联
来源：http://dali.cqqwz.cn/Article/details/gtkomelnxn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.316326.xyz/Article/details/gtubclmcbj.html

[R39] 重定向标准输出与错误
来源：http://dali.ydzc1.top/Article/details/gtemcymtor.html

cmd > out.log 2>&1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubrcqelt.html

[R40] 追加写日志
来源：http://dali.havefunace.top/Article/details/gtkgbezsuo.html

echo "log" >> out.log
来源：http://dali.pengpengdd.cyou/Article/details/gthmkqcrzr.html

[R41] 丢弃输出
来源：http://dali.ydzc1.top/Article/details/gtozufndml.html

cmd >/dev/null 2>&1
来源：http://dali.cqqwz.cn/Article/details/gtqudfqpzi.html

[R42] 输入重定向
来源：http://dali.hnxiangtu.top/Article/details/gtdceaiixe.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtqvlsqwzp.html

[R43] 按名字查找文件
来源：http://dali.aizwys.cn/Article/details/gtsmsmszdz.html

find . -name "*.log" -type f
来源：http://dali.jqgufenzy.top/Article/details/gtcsdvhdfz.html

[R44] 按修改时间查找
来源：http://dali.yonumen.top/Article/details/gtwkkyruuz.html

find . -mtime -7 -type f
来源：http://dali.hysaishi.cn/Article/details/gtqgyenxbs.html

[R45] 批量删除
来源：http://dali.xziqi.cn/Article/details/gtbngdvbfj.html

find . -name "*.tmp" -delete
来源：http://dali.jqgufenzy.top/Article/details/gtvprbkqrl.html

[R46] 递归替换文件内容
来源：http://dali.zhongyouzk.top/Article/details/gtrcmvujib.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xuetiantiany.cn/Article/details/gthclffifj.html

[R47] sed 单行替换
来源：http://dali.xylfe.cn/Article/details/gtonbvuyxw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenlongwang.top/Article/details/gthheyrigp.html

[R48] awk 取指定列
来源：http://dali.xinyue.icu/Article/details/gtjrvanqlt.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj20258.top/Article/details/gtkvvjwkdr.html

[R49] awk 带条件
来源：http://dali.xziqi.cn/Article/details/gthfnegvke.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daxiang520.top/Article/details/gtsyaiwfnk.html

[R50] awk 求和
来源：http://dali.nanxinkj.top/Article/details/gtxvrdskpf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yongpay.top/Article/details/gtinssccos.html

[R51] 排序去重取前几
来源：http://dali.jinghuilouyu.cn/Article/details/gtlehhtgvl.html


<!-- 参考信息 -->