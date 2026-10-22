代发 wailian999

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenzaomai.com/Article/details/gttbpfixci.html

[Q07] 删除表
来源：http://dali.yuanzhike.top/Article/details/gtndsyfrbe.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yangfankeji.com/Article/details/gtnqnhqrkf.html

[Q08] 创建普通索引
来源：http://dali.9152youxi.cn/Article/details/gtvxrqtfpt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gtxsjerlpz.html

[Q09] 创建唯一索引
来源：http://dali.gotoacloud.top/Article/details/gtcsoufrxp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gtngctozdi.html

[Q10] 插入单行
来源：http://dali.hysaishi.cn/Article/details/gturqpgrvd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhengqikj.top/Article/details/gtsfnswfdu.html

[Q11] 一次插入多行
来源：http://dali.ehwqpu.com/Article/details/gtmiyrnyca.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtombsyyse.html

[Q12] 插入后取自增 ID
来源：http://dali.sufxvd.cn/Article/details/gtaogltxek.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cheryme.top/Article/details/gtrixmbxhi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnebthxu.html

[Q13] 忽略重复插入
来源：http://dali.jyoumei.cn/Article/details/gtzdhubkcr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gogol.net.cn/Article/details/gtimwgezpx.html

[Q14] 存在则更新（upsert）
来源：http://dali.yonumen.top/Article/details/gtwtzdrncb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nanxinkj.top/Article/details/gtjkixtkoq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yueranfly.top/Article/details/gtjuzteehq.html

[Q15] 查询全部
来源：http://dali.fzhhl.top/Article/details/gtdxtkrquf.html

SELECT * FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtltuxeccs.html

[Q16] 查询指定列
来源：http://dali.yuanzhike.top/Article/details/gtbwjbsxtr.html

SELECT id, name FROM users;
来源：http://dali.hnqzz.top/Article/details/gtmhdxtwqf.html

[Q17] 条件查询
来源：http://dali.c1oappe.top/Article/details/gtnjdetcad.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jyoumei.cn/Article/details/gtsqkdnggc.html

[Q18] 模糊匹配
来源：http://dali.xylfe.cn/Article/details/gtjnelfnzf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.aibaodan.cn/Article/details/gteakitlml.html

[Q19] 范围查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqppwtglz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ydzc1.top/Article/details/gtsssddvkt.html

[Q20] IN 列表
来源：http://dali.yj20258.top/Article/details/gtdrcntkah.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cucudq.cn/Article/details/gttzyizkwv.html

[Q21] 空值判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnyegwczh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.wangdashe.top/Article/details/gtwvyrncgn.html

[Q22] 排序
来源：http://dali.fzhhl.top/Article/details/gttuhytjmu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cashguo.top/Article/details/gtvhnohpbt.html

[Q23] 分页
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdktnvpm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmqceuuq.html

[Q24] 去重
来源：http://dali.zhengqikj.top/Article/details/gtufblhzbs.html

SELECT DISTINCT city FROM users;
来源：http://dali.xylfe.cn/Article/details/gtntinfjpo.html

[Q25] 只取前 N 条
来源：http://dali.yuanzhike.top/Article/details/gtksrmerze.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.guannengcc.top/Article/details/gtmxdrlewt.html

[Q26] 计数
来源：http://dali.hnqzz.top/Article/details/gtnyqthqjs.html

SELECT COUNT(*) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtpattxngs.html

[Q27] 条件计数
来源：http://dali.wangdashe.top/Article/details/gtkbbwopdt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtvwctsgqv.html

[Q28] 求和与平均
来源：http://dali.jyoumei.cn/Article/details/gtbfydaaow.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtwqdnnhtt.html

[Q29] 最大最小值
来源：http://dali.hnqzz.top/Article/details/gtjxsnirty.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtsnuybadz.html

[Q30] 分组统计
来源：http://dali.hammf.cn/Article/details/gtayoskcpm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gtjfzhszvk.html

[Q31] 分组后过滤
来源：http://dali.zdqjudy.top/Article/details/gtlvnloolo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtdiiwnbwc.html

[Q32] 分组拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtctaxmria.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtiyuzcwwz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xziqi.cn/Article/details/gtddzugbiw.html

[Q33] 多列分组
来源：http://dali.xziqi.cn/Article/details/gtvntnqgre.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shangyingyoupin.top/Article/details/gtfqapjubr.html

[Q34] 每组取第一条
来源：http://dali.xuanzx.com/Article/details/gtasbquerf.html

SELECT * FROM (
来源：http://dali.fengsongda.top/Article/details/gtjslaadgg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shangyingyoupin.top/Article/details/gtszmkfdvv.html

) t WHERE rn = 1;
来源：http://dali.svipenyu.cn/Article/details/gtkesiyajc.html

[Q35] 内连接
来源：http://dali.tianlin.xyz/Article/details/gtvxlsgaba.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tanke756.top/Article/details/gtczmlztmo.html

[Q36] 左连接
来源：http://dali.yongpay.top/Article/details/gtimhoixce.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgfzy.top/Article/details/gtxipkgbcq.html

[Q37] 右连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrsqjkos.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gogol.net.cn/Article/details/gtwswdqbns.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.havefunace.top/Article/details/gtxxtewbdx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ppjwa.cn/Article/details/gtnbolyoki.html

[Q39] 自连接（查上下级）
来源：http://dali.hywenlv.cn/Article/details/gtgozquzsk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxinkj.top/Article/details/gtjajpztnx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cucudq.cn/Article/details/gtsrbypmcn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.aizwys.cn/Article/details/gtcsjlsbfx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbggpljaj.html

[Q41] 多表连接
来源：http://dali.hysaishi.cn/Article/details/gtigmrjdcr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guannengcc.top/Article/details/gtbfbdptmz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygnysede.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cucudq.cn/Article/details/gtimilsume.html

[Q42] 连接条件附加过滤
来源：http://dali.zycfv.cn/Article/details/gttbanywkl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.haohaochexian.top/Article/details/gtqtqncmhg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yanxiufei.cn/Article/details/gtglazmhob.html

[Q43] 标量子查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkgksnmr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hysaishi.cn/Article/details/gtvqhwtbbs.html

[Q44] IN 子查询
来源：http://dali.yangfankeji.com/Article/details/gtyjzzlsrr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ehwqpu.com/Article/details/gtqnsxsbja.html

[Q45] EXISTS 判断存在
来源：http://dali.zycfv.cn/Article/details/gtspsertqd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuxming.cn/Article/details/gtwgnhbcaf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.smart0.xyz/Article/details/gtuxixkcob.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258.top/Article/details/gtgytyhifn.html

[Q47] 与平均值比较
来源：http://dali.cashguo.top/Article/details/gtxkgszcur.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhiwuduotai.top/Article/details/gtarfjysza.html

[Q48] CTE 公用表表达式
来源：http://dali.cqqwz.cn/Article/details/gtmncfkaab.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.bjfxy.top/Article/details/gthvsuhtgh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.iojbl.cn/Article/details/gtaevucked.html

[Q49] 更新单行
来源：http://dali.cucudq.cn/Article/details/gtpnhzobcy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhongyouzk.top/Article/details/gthnqzvglt.html

[Q50] 批量更新
来源：http://dali.xylfe.cn/Article/details/gtzmmfswop.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gtrtdvnpxn.html

[Q51] 用子查询更新
来源：http://dali.cqqwz.cn/Article/details/gtmzcxaxwe.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.0kj1m.cn/Article/details/gtvhcfrufw.html

[Q52] 删除指定行
来源：http://dali.vqdsnc.cn/Article/details/gthijluuxw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gtcrrelfvd.html

[Q53] 按条件删除
来源：http://dali.guannengcc.top/Article/details/gtkenooopz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tianlin.xyz/Article/details/gtxkgprynm.html

[Q54] 清空表
来源：http://dali.sufxvd.cn/Article/details/gtrmfkptfc.html

TRUNCATE TABLE logs;
来源：http://dali.zdqjudy.top/Article/details/gtgrbgzpqh.html

[Q55] 排名（并列占位）
来源：http://dali.xuetiantiany.cn/Article/details/gtlqbdbkfn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gtgulnjwmj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.iojbl.cn/Article/details/gtnumllaoq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuanzx.com/Article/details/gtzebrcepc.html

[Q57] 行号
来源：http://dali.cashguo.top/Article/details/gtwuytzbgm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ydzc1.top/Article/details/gtscncpgpc.html

[Q58] 累计求和
来源：http://dali.cheryme.top/Article/details/gtdrgbybdn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.wangdashe.top/Article/details/gthmdedptd.html

[Q59] 分组内累计
来源：http://dali.tianlin.xyz/Article/details/gtezyphndx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtpdrxcijy.html

[Q60] 取上一行 / 下一行
来源：http://dali.gotoacloud.top/Article/details/gthbizdlyw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gotoacloud.top/Article/details/gtmkaydzea.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtcrujgwwn.html

[Q61] 移动平均
来源：http://dali.yj20258.top/Article/details/gtfybywjot.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtuzsamevt.html

[Q62] 分组占比
来源：http://dali.andypj.xyz/Article/details/gtvcuotwlq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gtcxwktpim.html

[Q63] 开启事务
来源：http://dali.ivvv.top/Article/details/gtxuvufifb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nwbrower.top/Article/details/gthwdvnazg.html

[Q64] 提交事务
来源：http://dali.ydzc1.top/Article/details/gtqtofniho.html

COMMIT;
来源：http://dali.ybcxt.top/Article/details/gtklpallbr.html

[Q65] 回滚事务
来源：http://dali.jinqigfzy.top/Article/details/gtxepdfkxl.html

ROLLBACK;
来源：http://dali.redwolf501.top/Article/details/gtojkbmmeu.html

[Q66] 行锁查询
来源：http://dali.hywenlv.cn/Article/details/gtthdrfxba.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zdqjudy.top/Article/details/gtfwfioqcg.html

[Q67] 设置隔离级别
来源：http://dali.havefunace.top/Article/details/gtwaqfaich.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.9152youxi.cn/Article/details/gtdbjgvncd.html

[Q68] 保存点
来源：http://dali.guannengcc.top/Article/details/gtfeoovcou.html

SAVEPOINT sp1;
来源：http://dali.zhongyouzk.top/Article/details/gtintmnwja.html

ROLLBACK TO sp1;
来源：http://dali.sweek.top/Article/details/gteuzkgryz.html

[Q69] 查看执行计划
来源：http://dali.jlsjyb.cn/Article/details/gtdznjtvpu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrstyvffi.html

[Q70] 更新统计信息
来源：http://dali.tianlin.xyz/Article/details/gteymksilb.html

ANALYZE TABLE users;
来源：http://dali.zycfv.cn/Article/details/gtcxazwwbl.html

[Q71] 查看建表语句
来源：http://dali.gotoacloud.top/Article/details/gtsdrrxclx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.vqdsnc.cn/Article/details/gtaycacnoq.html

[Q72] 查看索引
来源：http://dali.iojbl.cn/Article/details/gtzfblfljx.html

SHOW INDEX FROM users;
来源：http://dali.smart0.xyz/Article/details/gtznxxefoj.html

[Q73] 查看表状态
来源：http://dali.yuanzhike.top/Article/details/gtiqtkpaxn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhixingplan.top/Article/details/gtwcxnrpdj.html

[Q74] 强制使用索引
来源：http://dali.feifeiyinyue.top/Article/details/gtkwetyxew.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tian-w.cn/Article/details/gtajtygqqi.html

[Q75] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gthtkihdqb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtmzgbnqik.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cqqwz.cn/Article/details/gtvyqzrnev.html

[Q76] 按天统计
来源：http://dali.fzhhl.top/Article/details/gterlltjbt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.c1oappe.top/Article/details/gtarootzhv.html

[Q77] 时间加减
来源：http://dali.c1oappe.top/Article/details/gtfjmwkybb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tianlin.xyz/Article/details/gtworquowd.html

[Q78] 当前时间
来源：http://dali.nanxinkj.top/Article/details/gtnolwrbab.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.dashuyun.cn/Article/details/gtvmnxnqby.html

[Q79] 字符串拼接
来源：http://dali.jqgfzy.top/Article/details/gtfobhhgpu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shangyingyoupin.top/Article/details/gtilayrogd.html

[Q80] 字符串截取
来源：http://dali.nanxinkj.top/Article/details/gtbreqpsjz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtzygydiay.html

[Q81] 字符串替换
来源：http://dali.yanxiufei.cn/Article/details/gtrafglcfj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtcggmyhfm.html

[Q82] 字符长度与字节长度
来源：http://dali.hywenlv.cn/Article/details/gtrmoleyfk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtceppbxkd.html

[Q83] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gtotavkyjp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtevyjettt.html

[Q84] 去除首尾空格
来源：http://dali.zhengqikj.top/Article/details/gtbbayzbru.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtvcqayggh.html

[Q85] 数值取整
来源：http://dali.jinqigfzy.top/Article/details/gthpovhvcl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tianlin.xyz/Article/details/gtjtijrwjm.html

[Q86] 读取 JSON 字段
来源：http://dali.cashguo.top/Article/details/gtrauivxcp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sweek.top/Article/details/gtytepgbwd.html

[Q87] JSON 字段做条件
来源：http://dali.jqgufenzy.top/Article/details/gtvjlkqgqx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.snrcjt.cn/Article/details/gtbclmeukj.html

[Q88] 行转列（条件聚合）
来源：http://dali.fengsongda.top/Article/details/gtassvuuxd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj202588.top/Article/details/gtyejnbnmh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yvedp.cn/Article/details/gtqmeffcmk.html

[Q89] 判断表是否存在
来源：http://dali.fzhhl.top/Article/details/gttoalrtbm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xziqi.cn/Article/details/gtnshmqyfh.html

[Q90] 生成序号列
来源：http://dali.zhoulong.xyz/Article/details/gtnswlfdqo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.daria6918.cn/Article/details/gtdrhmmfqr.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtkvyrripf.html

R. Bash 专题
来源：http://dali.xuanzx.com/Article/details/gtrziuoqnb.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtspxcsaqn.html

[R01] shebang 与严格模式
来源：http://dali.yj20258888.top/Article/details/gthmmuvobm.html

#!/usr/bin/env bash
来源：http://dali.hnqzz.top/Article/details/gtwkhyndxt.html

set -euo pipefail
来源：http://dali.hysaishi.cn/Article/details/gthhxbjgiw.html

[R02] 变量赋值与使用
来源：http://dali.cdnleiting.top/Article/details/gtkhystsht.html

name="Tom"; echo "$name"
来源：http://dali.yj20258.top/Article/details/gtajfwhqex.html

[R03] 只读变量
来源：http://dali.xziqi.cn/Article/details/gtxeuqfiol.html

readonly PI=3.14
来源：http://dali.aibaodan.cn/Article/details/gtetdjaiib.html

[R04] 位置参数
来源：http://dali.wangshuangyany.cn/Article/details/gtibpxmhwr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sxryk.cn/Article/details/gtjkyzbgiu.html

[R05] 参数默认值
来源：http://dali.nwbrower.top/Article/details/gtuqskzjwg.html

name="${1:-default}"
来源：http://dali.ivvv.top/Article/details/gtdqfnkpec.html

[R06] 判断命令是否存在
来源：http://dali.mhx1999.top/Article/details/gteevxonhg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jlsjyb.cn/Article/details/gttfvckkmc.html

[R07] if 判断文件
来源：http://dali.fzhhl.top/Article/details/gtlcitjpeu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cashguo.top/Article/details/gtqzozvvtc.html

[R08] 数值比较
来源：http://dali.xylfe.cn/Article/details/gteemkoejv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.smart0.xyz/Article/details/gtocxpxrlh.html

[R09] 字符串比较
来源：http://dali.aibaodan.cn/Article/details/gtevxoxcya.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenlongwang.top/Article/details/gtdwhcninw.html

[R10] 正则匹配
来源：http://dali.gaohongyu789.top/Article/details/gthjgueaai.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xinyue.icu/Article/details/gturzjduto.html

[R11] case 多分支
来源：http://dali.fengsongda.top/Article/details/gtcqcgkjxe.html

case "$1" in
来源：http://dali.yongpay.top/Article/details/gtdloemrul.html

start) echo "启动" ;;
来源：http://dali.tanke756.top/Article/details/gtezavonfy.html

stop)  echo "停止" ;;
来源：http://dali.zhongyouzk.top/Article/details/gthndizjsj.html

*)     echo "未知命令" ;;
来源：http://dali.hammf.cn/Article/details/gtlczhxhag.html

esac
来源：http://dali.tanke756.top/Article/details/gtccdthdxg.html

[R12] for 遍历文件
来源：http://dali.ppjwa.cn/Article/details/gtwjynpnzk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jianghu66.top/Article/details/gtkwvhwqml.html

[R13] for 计数循环
来源：http://dali.snrcjt.cn/Article/details/gtmvvotqmn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnczuzrf.html

[R14] C 风格 for
来源：http://dali.chenlongwang.top/Article/details/gtgwcrtkgg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.guowangkeji.top/Article/details/gtsyywucdm.html

[R15] while 逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtjkmkqwqa.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhengqikj.top/Article/details/gtsesipjqp.html

[R16] until 等待条件
来源：http://dali.shuidangran.top/Article/details/gtihpxnzbc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gtqxsxhcgy.html

[R17] 数组定义与取值
来源：http://dali.xuanzx.com/Article/details/gtvttxuiem.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jianghu66.top/Article/details/gtxupbnrwv.html

[R18] 遍历数组
来源：http://dali.yongpay.top/Article/details/gtsqgxahws.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hysaishi.cn/Article/details/gtsmmtwcnv.html

[R19] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gtzjmljdne.html

echo "${#arr[@]}"
来源：http://dali.birdmap.top/Article/details/gttoggkqha.html

[R20] 关联数组（字典）
来源：http://dali.ppjwa.cn/Article/details/gtxltzikbo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cashguo.top/Article/details/gtupmnmcev.html

[R21] 字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gttoalitew.html

echo "${#s}"
来源：http://dali.tianlin.xyz/Article/details/gtjamuvktq.html

[R22] 截取子串
来源：http://dali.0kj1m.cn/Article/details/gtqryuudnc.html

echo "${s:0:5}"
来源：http://dali.c1oappe.top/Article/details/gtbhyquwei.html

[R23] 字符串替换
来源：http://dali.feifeiyinyue.top/Article/details/gtobmzoauq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinqigfzy.top/Article/details/gtftyszixs.html

[R24] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gtbpuayakh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenlongwang.top/Article/details/gtidnadtca.html

[R25] 去后缀 / 去前缀
来源：http://dali.nanxinkj.top/Article/details/gtqaufeidl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgfzy.top/Article/details/gtumayczvv.html

[R26] 命令替换
来源：http://dali.ivvv.top/Article/details/gtcuaopfne.html

now=$(date +%F); echo "$now"
来源：http://dali.iojbl.cn/Article/details/gtdaniemgy.html

[R27] 算术展开
来源：http://dali.ppjwa.cn/Article/details/gtwbzyggkd.html

echo $((1 + 2 * 3))
来源：http://dali.xuanzx.com/Article/details/gtxjneirzd.html

[R28] 浮点运算
来源：http://dali.guowangkeji.top/Article/details/gtgvnfzohh.html

echo "scale=2; 10/3" | bc
来源：http://dali.yonumen.top/Article/details/gtexccmzcf.html

[R29] 定义函数
来源：http://dali.tianlin.xyz/Article/details/gtsxnpjxaq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sweek.top/Article/details/gtaujcjidx.html

[R30] 函数返回状态码
来源：http://dali.nwbrower.top/Article/details/gtxxwlfhzx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tianlin.xyz/Article/details/gtojsokzea.html

[R31] 局部变量
来源：http://dali.meibo888.top/Article/details/gteazmgtis.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxinkj.top/Article/details/gtrjzcsjje.html

[R32] 参数个数校验
来源：http://dali.0kj1m.cn/Article/details/gtxdcwnbtu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shangyingyoupin.top/Article/details/gtlbjpwhdb.html

[R33] 捕获错误并提示行号
来源：http://dali.sysykeji.top/Article/details/gtvzdrbzaf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.havefunace.top/Article/details/gtjvpsqewz.html

[R34] 退出时清理
来源：http://dali.fengsongda.top/Article/details/gtqpeexwnk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gtpoeekolp.html

[R35] 后台执行并等待
来源：http://dali.zdqjudy.top/Article/details/gtixuzuvdv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.fengsongda.top/Article/details/gtpquwqqtf.html

[R36] 并发执行多个任务
来源：http://dali.chenjidiqi.icu/Article/details/gtdpqrlilj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjledmjh.html

[R37] 把输出赋给变量
来源：http://dali.xylfe.cn/Article/details/gthgbimtxv.html

files=$(ls -1)
来源：http://dali.jiagoushi.top/Article/details/gtihgfywrr.html

[R38] 管道串联
来源：http://dali.shuidangran.top/Article/details/gtgekbrtxq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gotoacloud.top/Article/details/gtcqpxpguv.html

[R39] 重定向标准输出与错误
来源：http://dali.ivvv.top/Article/details/gtkkqrjvkr.html

cmd > out.log 2>&1
来源：http://dali.gzhubu.top/Article/details/gtwbrufrpl.html

[R40] 追加写日志
来源：http://dali.dianchejie.cn/Article/details/gtnticfxzf.html

echo "log" >> out.log
来源：http://dali.zhoulong.xyz/Article/details/gtdypphfld.html

[R41] 丢弃输出
来源：http://dali.zhoulong.xyz/Article/details/gtsxedsvzt.html

cmd >/dev/null 2>&1
来源：http://dali.ehwqpu.com/Article/details/gtlofhsarl.html

[R42] 输入重定向
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckuhftnv.html

wc -l < a.txt
来源：http://dali.hfpthk.cn/Article/details/gtzcrrbhoy.html

[R43] 按名字查找文件
来源：http://dali.yueranfly.top/Article/details/gtznukmoyw.html

find . -name "*.log" -type f
来源：http://dali.fengsongda.top/Article/details/gtpkxblpzg.html

[R44] 按修改时间查找
来源：http://dali.bjfxy.top/Article/details/gtdojhglgs.html

find . -mtime -7 -type f
来源：http://dali.aibaodan.cn/Article/details/gtaaddxzgc.html

[R45] 批量删除
来源：http://dali.cucudq.cn/Article/details/gtfavhnwkr.html

find . -name "*.tmp" -delete
来源：http://dali.jinqigufen.top/Article/details/gtcbkprxsp.html

[R46] 递归替换文件内容
来源：http://dali.yangfankeji.com/Article/details/gtfshbsqpq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258888.top/Article/details/gtmofmkcvf.html

[R47] sed 单行替换
来源：http://dali.cqqwz.cn/Article/details/gtznbiabck.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtolaxzufp.html

[R48] awk 取指定列
来源：http://dali.316326.xyz/Article/details/gthsywdeep.html

awk '{print $1, $3}' a.txt
来源：http://dali.c1oappe.top/Article/details/gtblbxuzlq.html

[R49] awk 带条件
来源：http://dali.mhx1999.top/Article/details/gtkkwagtfq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aizwys.cn/Article/details/gtqykhulmo.html

[R50] awk 求和
来源：http://dali.zhiwuduotai.top/Article/details/gtlfltlqns.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xinyue.icu/Article/details/gtccmlacwx.html

[R51] 排序去重取前几
来源：http://dali.jiagoushi.top/Article/details/gtrgylbamn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xziqi.cn/Article/details/gtauetsgyn.html

[R52] 统计行数
来源：http://dali.ydzc1.top/Article/details/gtdvjrsotm.html

wc -l a.txt
来源：http://dali.ehwqpu.com/Article/details/gtkusnhpis.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoafxrgrd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgfzy.top/Article/details/gtneqmhpcp.html

[R54] 比较两个文件
来源：http://dali.aizwys.cn/Article/details/gtwzlalhtd.html

diff a.txt b.txt
来源：http://dali.chenzaomai.com/Article/details/gtoyphgqqy.html

[R55] 压缩与解压
来源：http://dali.dashuyun.cn/Article/details/gtcixpisww.html


<!-- 参考信息 -->