代发 wailian999

);
来源：http://dali.haohaochexian.top/Article/details/gtwvhafksx.html

[Q03] 增加列
来源：http://dali.cdnleiting.top/Article/details/gtraaapmyr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.redwolf501.top/Article/details/gtzckbeplw.html

[Q04] 修改列类型
来源：http://dali.nanxuanxn.top/Article/details/gtakxsgmrt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.316326.xyz/Article/details/gtupsjfgis.html

[Q05] 重命名列
来源：http://dali.quarkkingdee.top/Article/details/gtwhsypgsw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.svipenyu.cn/Article/details/gtcfvbljod.html

[Q06] 删除列
来源：http://dali.xuanzx.com/Article/details/gtxlynhind.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangtech.top/Article/details/gtirfrokvm.html

[Q07] 删除表
来源：http://dali.ydzc1.top/Article/details/gtnowniahd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj20258888.top/Article/details/gtadagsiwt.html

[Q08] 创建普通索引
来源：http://dali.jianghu66.top/Article/details/gtthzlgbwn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cashguo.top/Article/details/gtsgasrakl.html

[Q09] 创建唯一索引
来源：http://dali.ybcxt.top/Article/details/gtyxecmgjs.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.bjfxy.top/Article/details/gtqpsqutgu.html

[Q10] 插入单行
来源：http://dali.jqgfzy.top/Article/details/gtvllwqbsu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gtaipfchlj.html

[Q11] 一次插入多行
来源：http://dali.jinqigufen.top/Article/details/gtackiyubp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nwbrower.top/Article/details/gtrjysblth.html

[Q12] 插入后取自增 ID
来源：http://dali.dashuyun.cn/Article/details/gthidfdwdb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sufxvd.cn/Article/details/gtgpmwkjgh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jqgfzy.top/Article/details/gtzlkpubwa.html

[Q13] 忽略重复插入
来源：http://dali.haohaochexian.top/Article/details/gtdxruusdm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gogol.net.cn/Article/details/gtrsnvcmzl.html

[Q14] 存在则更新（upsert）
来源：http://dali.feifeiyinyue.top/Article/details/gtqvncrpog.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenzaomai.com/Article/details/gtyxknxyce.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.redwolf501.top/Article/details/gthprwymjm.html

[Q15] 查询全部
来源：http://dali.wangdashe.top/Article/details/gtvrgdmwdv.html

SELECT * FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtaclzunwa.html

[Q16] 查询指定列
来源：http://dali.hfpthk.cn/Article/details/gtlxftkodk.html

SELECT id, name FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtkdyxlgzj.html

[Q17] 条件查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgproxmy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtigrwskmx.html

[Q18] 模糊匹配
来源：http://dali.cdnleiting.top/Article/details/gtawukdhky.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hongshengwenyu.top/Article/details/gtecqdfvti.html

[Q19] 范围查询
来源：http://dali.xuetiantiany.cn/Article/details/gtjwpgqwbe.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenlongwang.top/Article/details/gttafsrgxo.html

[Q20] IN 列表
来源：http://dali.tianlin.xyz/Article/details/gtixanvlhd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xinyue.icu/Article/details/gtsegjmyfn.html

[Q21] 空值判断
来源：http://dali.havefunace.top/Article/details/gtonlurzrv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gzhubu.top/Article/details/gtknrsgyqi.html

[Q22] 排序
来源：http://dali.zdqjudy.top/Article/details/gttxkobtej.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yuxming.cn/Article/details/gtovjaglvf.html

[Q23] 分页
来源：http://dali.jinghuilouyu.cn/Article/details/gtividjjut.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.316326.xyz/Article/details/gtymuefamn.html

[Q24] 去重
来源：http://dali.quarkkingdee.top/Article/details/gtljqkdern.html

SELECT DISTINCT city FROM users;
来源：http://dali.andypj.xyz/Article/details/gtnaxntanq.html

[Q25] 只取前 N 条
来源：http://dali.zhongyouzk.top/Article/details/gtaakigzhx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenjidiqi.icu/Article/details/gtuzewskea.html

[Q26] 计数
来源：http://dali.shangyingyoupin.top/Article/details/gtkhpbbldq.html

SELECT COUNT(*) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtplvjotoe.html

[Q27] 条件计数
来源：http://dali.gzhubu.top/Article/details/gtimzqrujg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cheryme.top/Article/details/gtlsatnatw.html

[Q28] 求和与平均
来源：http://dali.jinghuilouyu.cn/Article/details/gtvkopejhg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtngfqetuw.html

[Q29] 最大最小值
来源：http://dali.jinqigfzy.top/Article/details/gtqpxmcpqs.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtrhjjuuzu.html

[Q30] 分组统计
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdumjcio.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gtgeguowzs.html

[Q31] 分组后过滤
来源：http://dali.cdnleiting.top/Article/details/gtnusszodw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yonumen.top/Article/details/gtactimihq.html

[Q32] 分组拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtdxtvyoqn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gthxavzrcn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.pycfn.com/Article/details/gtbsmqrhvq.html

[Q33] 多列分组
来源：http://dali.nwbrower.top/Article/details/gtaunbsdrw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.c1oappe.top/Article/details/gtragmclnp.html

[Q34] 每组取第一条
来源：http://dali.0kj1m.cn/Article/details/gtxkrmvcrr.html

SELECT * FROM (
来源：http://dali.dianchejie.cn/Article/details/gtkjathwjo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jqgufenzy.top/Article/details/gtoeowspvg.html

) t WHERE rn = 1;
来源：http://dali.yuxming.cn/Article/details/gtqougeiny.html

[Q35] 内连接
来源：http://dali.gaohongyu789.top/Article/details/gtnjzbbcon.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xinyue.icu/Article/details/gtazkcdivl.html

[Q36] 左连接
来源：http://dali.shangyingyoupin.top/Article/details/gtptcksplv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yvedp.cn/Article/details/gtdljzmbys.html

[Q37] 右连接
来源：http://dali.cucudq.cn/Article/details/gthwochxlf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.fengsongda.top/Article/details/gtwymgkraa.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhiwuduotai.top/Article/details/gtyseifrcv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yuanzhike.top/Article/details/gtlzyfqjbr.html

[Q39] 自连接（查上下级）
来源：http://dali.fzhhl.top/Article/details/gtqdydaunn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhiwuduotai.top/Article/details/gtsvpfifsx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cdnleiting.top/Article/details/gtqxamrvwh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tanke756.top/Article/details/gtnwwjyjqc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yanxiufei.cn/Article/details/gtrnxcuwzr.html

[Q41] 多表连接
来源：http://dali.sufxvd.cn/Article/details/gtxfqngztw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenjidiqi.icu/Article/details/gtbysswrkq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jiagoushi.top/Article/details/gtrxqimdcd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenzaomai.com/Article/details/gtfkjozghl.html

[Q42] 连接条件附加过滤
来源：http://dali.ppjwa.cn/Article/details/gttwjchamd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nanxinkj.top/Article/details/gtfoaurerb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ivvv.top/Article/details/gtodolwwzs.html

[Q43] 标量子查询
来源：http://dali.zhixingplan.top/Article/details/gtwzimiimo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gtfnperrrs.html

[Q44] IN 子查询
来源：http://dali.yj20258.top/Article/details/gthaxswghe.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthohwnybh.html

[Q45] EXISTS 判断存在
来源：http://dali.dianchejie.cn/Article/details/gtvzzuhaol.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigufen.top/Article/details/gtsfmoijvw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fengsongda.top/Article/details/gtrnqbbazr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dianchejie.cn/Article/details/gttsefyuuy.html

[Q47] 与平均值比较
来源：http://dali.fengsongda.top/Article/details/gtnprowqol.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cheryme.top/Article/details/gtttanmkbj.html

[Q48] CTE 公用表表达式
来源：http://dali.jqgfzy.top/Article/details/gtkoilymjn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhengqikj.top/Article/details/gtsjtfngon.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxiiqtsl.html

[Q49] 更新单行
来源：http://dali.sysykeji.top/Article/details/gtfbczkung.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuanzx.com/Article/details/gtcsrkwfda.html

[Q50] 批量更新
来源：http://dali.ydzc1.top/Article/details/gtgpoievaa.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenjidiqi.icu/Article/details/gtmrvipqnc.html

[Q51] 用子查询更新
来源：http://dali.nanxinkj.top/Article/details/gtjndjsgqg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmaybkndi.html

[Q52] 删除指定行
来源：http://dali.c1oappe.top/Article/details/gtqowhnwiy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hnqzz.top/Article/details/gtmmpioxjj.html

[Q53] 按条件删除
来源：http://dali.snrcjt.cn/Article/details/gtywglmnik.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhiwuduotai.top/Article/details/gtnblnrvfj.html

[Q54] 清空表
来源：http://dali.jianghu66.top/Article/details/gtjtsyjhps.html

TRUNCATE TABLE logs;
来源：http://dali.iojbl.cn/Article/details/gtfeuwlwgc.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258888.top/Article/details/gtgrdmwcpp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gthbrhmekr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xinyue.icu/Article/details/gtrptikxwi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gtfwgktpxv.html

[Q57] 行号
来源：http://dali.yuanzhike.top/Article/details/gtfxssetbi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtykjwjhdq.html

[Q58] 累计求和
来源：http://dali.zhixingplan.top/Article/details/gtscymujbv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdzktblsm.html

[Q59] 分组内累计
来源：http://dali.cdnleiting.top/Article/details/gtzyeytlps.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtljbscxan.html

[Q60] 取上一行 / 下一行
来源：http://dali.hammf.cn/Article/details/gtdlbymjek.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nwbrower.top/Article/details/gtvtzreoho.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtionyvpob.html

[Q61] 移动平均
来源：http://dali.yuanzhike.top/Article/details/gtuamrcvgb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtpqxcwvfv.html

[Q62] 分组占比
来源：http://dali.chenjidiqi.icu/Article/details/gtkprdagbw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gtavyamuff.html

[Q63] 开启事务
来源：http://dali.kuanghao11.cn/Article/details/gtgxhiphns.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.redwolf501.top/Article/details/gtuurveion.html

[Q64] 提交事务
来源：http://dali.fengsongda.top/Article/details/gtudmtmrwy.html

COMMIT;
来源：http://dali.hammf.cn/Article/details/gtzbpznhtp.html

[Q65] 回滚事务
来源：http://dali.hammf.cn/Article/details/gtsqupewcs.html

ROLLBACK;
来源：http://dali.nanxinkj.top/Article/details/gtenpjxnfr.html

[Q66] 行锁查询
来源：http://dali.jianghu66.top/Article/details/gtuyqrwndc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.iojbl.cn/Article/details/gtdppwpaow.html

[Q67] 设置隔离级别
来源：http://dali.hnxiangtu.top/Article/details/gtprljxiad.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.quarkkingdee.top/Article/details/gtvwxuwnde.html

[Q68] 保存点
来源：http://dali.dianchejie.cn/Article/details/gtufjtkadk.html

SAVEPOINT sp1;
来源：http://dali.feifeiyinyue.top/Article/details/gtyjsdpuca.html

ROLLBACK TO sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gtzwmmursp.html

[Q69] 查看执行计划
来源：http://dali.yongpay.top/Article/details/gtyuaiipug.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhongyouzk.top/Article/details/gtjssbsbvd.html

[Q70] 更新统计信息
来源：http://dali.yangfankeji.com/Article/details/gtasihocgh.html

ANALYZE TABLE users;
来源：http://dali.yj20258888.top/Article/details/gtqznmtedt.html

[Q71] 查看建表语句
来源：http://dali.hysaishi.cn/Article/details/gtsizzjefx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.haohaochexian.top/Article/details/gtytaxseqw.html

[Q72] 查看索引
来源：http://dali.shzxlz.cn/Article/details/gtqcpimkss.html

SHOW INDEX FROM users;
来源：http://dali.iojbl.cn/Article/details/gtatwdglhe.html

[Q73] 查看表状态
来源：http://dali.yangfankeji.com/Article/details/gtlrqzbmqp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.316326.xyz/Article/details/gtdclpqvqs.html

[Q74] 强制使用索引
来源：http://dali.quarkkingdee.top/Article/details/gtmsddyilq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfltoxnsi.html

[Q75] 日期格式化
来源：http://dali.tanke756.top/Article/details/gtztiimnuv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbfdapfr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gotoacloud.top/Article/details/gtteismquh.html

[Q76] 按天统计
来源：http://dali.jqgfzy.top/Article/details/gtsnszsmbz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sweek.top/Article/details/gtctzfbznz.html

[Q77] 时间加减
来源：http://dali.daxiang520.top/Article/details/gtrilalnvh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhongyouzk.top/Article/details/gtjonozfnp.html

[Q78] 当前时间
来源：http://dali.yj20258.top/Article/details/gtfbjnnhie.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yonumen.top/Article/details/gtucvjjakv.html

[Q79] 字符串拼接
来源：http://dali.xuanzx.com/Article/details/gtndfqxpra.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hammf.cn/Article/details/gtsmxopwuu.html

[Q80] 字符串截取
来源：http://dali.yangfankeji.com/Article/details/gtqjmfdgbi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sweek.top/Article/details/gtcuzglzpi.html

[Q81] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gtmvbiyzes.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.birdmap.top/Article/details/gtvpkyyyzn.html

[Q82] 字符长度与字节长度
来源：http://dali.sxryk.cn/Article/details/gtwyhgodkn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtxnzrvxqr.html

[Q83] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gtbcyurmzd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gtxwmcxzyo.html

[Q84] 去除首尾空格
来源：http://dali.chenlongwang.top/Article/details/gtatdrbthd.html

SELECT TRIM(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtiorfhhoh.html

[Q85] 数值取整
来源：http://dali.dianchejie.cn/Article/details/gthhcbleyx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgnsymbit.html

[Q86] 读取 JSON 字段
来源：http://dali.havefunace.top/Article/details/gthmctzhar.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenzaomai.com/Article/details/gtctwjcfcn.html

[Q87] JSON 字段做条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxoxzmcjg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.haohaochexian.top/Article/details/gtlhlbihwp.html

[Q88] 行转列（条件聚合）
来源：http://dali.xziqi.cn/Article/details/gtrwlinzav.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhongyouzk.top/Article/details/gtabfpwdyw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtawwrmhju.html

[Q89] 判断表是否存在
来源：http://dali.meibo888.top/Article/details/gtgqnjpset.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yanxiufei.cn/Article/details/gtykvyrarm.html

[Q90] 生成序号列
来源：http://dali.wangdashe.top/Article/details/gtottgfeuh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhoulong.xyz/Article/details/gtrpchobkt.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtpoojvvnw.html

R. Bash 专题
来源：http://dali.shzxlz.cn/Article/details/gtpwmpypxv.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtzgdjgllo.html

[R01] shebang 与严格模式
来源：http://dali.yj20258.top/Article/details/gtdaquqxtp.html

#!/usr/bin/env bash
来源：http://dali.wangdashe.top/Article/details/gtdwlikafg.html

set -euo pipefail
来源：http://dali.svipenyu.cn/Article/details/gtbkidcxpg.html

[R02] 变量赋值与使用
来源：http://dali.andypj.xyz/Article/details/gthlahunsn.html

name="Tom"; echo "$name"
来源：http://dali.xuanzx.com/Article/details/gtopxulcnt.html

[R03] 只读变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbovfjozs.html

readonly PI=3.14
来源：http://dali.tanke756.top/Article/details/gtrugftfct.html

[R04] 位置参数
来源：http://dali.quarkkingdee.top/Article/details/gttdbemjxz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangdashe.top/Article/details/gtiblewkob.html

[R05] 参数默认值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrraqevdq.html

name="${1:-default}"
来源：http://dali.xinyue.icu/Article/details/gtmswtkpdf.html

[R06] 判断命令是否存在
来源：http://dali.svipenyu.cn/Article/details/gtpurxlaiy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gtgtnnpaok.html

[R07] if 判断文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelehnvxm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxinkj.top/Article/details/gtmynhdwrv.html

[R08] 数值比较
来源：http://dali.yvedp.cn/Article/details/gtmofzwnua.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zdqjudy.top/Article/details/gtyrztzxmt.html

[R09] 字符串比较
来源：http://dali.chenlongwang.top/Article/details/gtbuhnalyx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jiagoushi.top/Article/details/gtzzqcbjqn.html

[R10] 正则匹配
来源：http://dali.hnqzz.top/Article/details/gtcfzjjzlu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.snrcjt.cn/Article/details/gtkvijgsvc.html

[R11] case 多分支
来源：http://dali.birdmap.top/Article/details/gtvzldbyto.html

case "$1" in
来源：http://dali.daria6918.cn/Article/details/gttvrxhyij.html

start) echo "启动" ;;
来源：http://dali.yuxming.cn/Article/details/gtwkslyico.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzphxuftv.html

*)     echo "未知命令" ;;
来源：http://dali.redwolf501.top/Article/details/gtotcnhqdf.html

esac
来源：http://dali.zhiwuduotai.top/Article/details/gtbtyovoci.html

[R12] for 遍历文件
来源：http://dali.xziqi.cn/Article/details/gttidnmbbz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guowangkeji.top/Article/details/gtkxthsunr.html

[R13] for 计数循环
来源：http://dali.cdnleiting.top/Article/details/gticazztvm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gtcwkgchev.html

[R14] C 风格 for
来源：http://dali.sweek.top/Article/details/gtlmgrrurg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gttvzaasmo.html

[R15] while 逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtxpbkayzr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aizwys.cn/Article/details/gtndusiphh.html

[R16] until 等待条件
来源：http://dali.tian-w.cn/Article/details/gtzvhsxjqc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cucudq.cn/Article/details/gtikgrbzti.html

[R17] 数组定义与取值
来源：http://dali.aizwys.cn/Article/details/gttzcvqpkn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.feifeiyinyue.top/Article/details/gtcgxaddfb.html

[R18] 遍历数组
来源：http://dali.xuetiantiany.cn/Article/details/gtplsfyluz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangdashe.top/Article/details/gthmlpxwpr.html

[R19] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gthgdiynrf.html

echo "${#arr[@]}"
来源：http://dali.gzhubu.top/Article/details/gtqsxiguxp.html

[R20] 关联数组（字典）
来源：http://dali.yonumen.top/Article/details/gtxtemmuyd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.havefunace.top/Article/details/gtmlgazqna.html

[R21] 字符串长度
来源：http://dali.xinyue.icu/Article/details/gtbzzbzqbt.html

echo "${#s}"
来源：http://dali.ybcxt.top/Article/details/gtvkasuhwr.html

[R22] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gtnempxdfs.html

echo "${s:0:5}"
来源：http://dali.hnxiangtu.top/Article/details/gtnhpnpcng.html

[R23] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gtounbvfvt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.quarkkingdee.top/Article/details/gtcstjzuoi.html

[R24] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gtscpdvqzj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigfzy.top/Article/details/gtcutsmdcj.html

[R25] 去后缀 / 去前缀
来源：http://dali.gogol.net.cn/Article/details/gttwfkqmol.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.kuanghao11.cn/Article/details/gtvnlgwgul.html

[R26] 命令替换
来源：http://dali.xziqi.cn/Article/details/gtmquozadg.html

now=$(date +%F); echo "$now"
来源：http://dali.zhixingplan.top/Article/details/gtnvwziysa.html

[R27] 算术展开
来源：http://dali.chenjidiqi.icu/Article/details/gtzubfoolz.html

echo $((1 + 2 * 3))
来源：http://dali.zycfv.cn/Article/details/gtetnatwvn.html

[R28] 浮点运算
来源：http://dali.cucudq.cn/Article/details/gtrzqidykz.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinqigfzy.top/Article/details/gtoqmkzfsm.html

[R29] 定义函数
来源：http://dali.zhixingplan.top/Article/details/gtjyhknyit.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ppjwa.cn/Article/details/gtfznujvbd.html

[R30] 函数返回状态码
来源：http://dali.chenzaomai.com/Article/details/gtvqgohxts.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shangyingyoupin.top/Article/details/gteriroesi.html

[R31] 局部变量
来源：http://dali.cucudq.cn/Article/details/gtcbendgtj.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbygdszxm.html

[R32] 参数个数校验
来源：http://dali.xuetiantiany.cn/Article/details/gteftcleei.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gtquiqozdy.html

[R33] 捕获错误并提示行号
来源：http://dali.nwbrower.top/Article/details/gtfklcftky.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.birdmap.top/Article/details/gtenoeqjrz.html

[R34] 退出时清理
来源：http://dali.andypj.xyz/Article/details/gtdhflkxqw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yvedp.cn/Article/details/gtchxgbcqe.html

[R35] 后台执行并等待
来源：http://dali.yanxiufei.cn/Article/details/gtlysbmhkd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.snrcjt.cn/Article/details/gtzzozypoe.html

[R36] 并发执行多个任务
来源：http://dali.jiagoushi.top/Article/details/gtdzlxczps.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ydzc1.top/Article/details/gtzbuiaefn.html

[R37] 把输出赋给变量
来源：http://dali.tian-w.cn/Article/details/gtucbpasnh.html

files=$(ls -1)
来源：http://dali.xinyue.icu/Article/details/gtisflsuqd.html

[R38] 管道串联
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmiqenage.html

cat a.txt | grep -i error | wc -l
来源：http://dali.0kj1m.cn/Article/details/gtjwkazusr.html

[R39] 重定向标准输出与错误
来源：http://dali.zhongyouzk.top/Article/details/gtteybkyhe.html

cmd > out.log 2>&1
来源：http://dali.9152youxi.cn/Article/details/gtxbhnmwnt.html

[R40] 追加写日志
来源：http://dali.daria6918.cn/Article/details/gtvmrezwte.html

echo "log" >> out.log
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwvuyomo.html

[R41] 丢弃输出
来源：http://dali.ydzc1.top/Article/details/gtgrekmvps.html

cmd >/dev/null 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzywizeye.html

[R42] 输入重定向
来源：http://dali.quarkkingdee.top/Article/details/gtoenjmlmq.html

wc -l < a.txt
来源：http://dali.cashguo.top/Article/details/gtfcvwkxhc.html

[R43] 按名字查找文件
来源：http://dali.nanxuanxn.top/Article/details/gtraxgzlhw.html

find . -name "*.log" -type f
来源：http://dali.yuxming.cn/Article/details/gtqeswzobn.html

[R44] 按修改时间查找
来源：http://dali.sufxvd.cn/Article/details/gtvgavuate.html

find . -mtime -7 -type f
来源：http://dali.yuanzhike.top/Article/details/gtmsbgztpy.html

[R45] 批量删除
来源：http://dali.0kj1m.cn/Article/details/gtykyitlnl.html

find . -name "*.tmp" -delete
来源：http://dali.zhongyouzk.top/Article/details/gtsaucbneo.html

[R46] 递归替换文件内容
来源：http://dali.cashguo.top/Article/details/gtvahkvuzw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hnxiangtu.top/Article/details/gtscaooqoy.html

[R47] sed 单行替换
来源：http://dali.vqdsnc.cn/Article/details/gtkjpzwtpt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cqqwz.cn/Article/details/gtfojjeaaw.html

[R48] awk 取指定列
来源：http://dali.jinqigfzy.top/Article/details/gtnrggwhai.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtnkhfcpff.html

[R49] awk 带条件
来源：http://dali.shangyingyoupin.top/Article/details/gttyidqict.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuanzx.com/Article/details/gtqnuxtdaz.html

[R50] awk 求和
来源：http://dali.guannengcc.top/Article/details/gtenrfsvug.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtjmqrmafd.html

[R51] 排序去重取前几
来源：http://dali.xziqi.cn/Article/details/gtjzinrkmn.html


<!-- 参考信息 -->