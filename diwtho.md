代发 wailian999

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gtrhhlmfcu.html

[Q09] 创建唯一索引
来源：http://dali.gzhubu.top/Article/details/gtyjkajbbo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gtlztsrvbd.html

[Q10] 插入单行
来源：http://dali.xuetiantiany.cn/Article/details/gtgsshhfxi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.svipenyu.cn/Article/details/gtxsbmnzdv.html

[Q11] 一次插入多行
来源：http://dali.jlsjyb.cn/Article/details/gtlotjxxgo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jiagoushi.top/Article/details/gtivwthqqm.html

[Q12] 插入后取自增 ID
来源：http://dali.aizwys.cn/Article/details/gtzdndgyng.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tanke756.top/Article/details/gtwwtogevl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xylfe.cn/Article/details/gtwuketdau.html

[Q13] 忽略重复插入
来源：http://dali.gotoacloud.top/Article/details/gtegmyidaf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tian-w.cn/Article/details/gtpxjityhx.html

[Q14] 存在则更新（upsert）
来源：http://dali.jyoumei.cn/Article/details/gtzhgedauk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nwbrower.top/Article/details/gtodgqwnvb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ehwqpu.com/Article/details/gtdtipxusw.html

[Q15] 查询全部
来源：http://dali.svipenyu.cn/Article/details/gtbspwvufr.html

SELECT * FROM users;
来源：http://dali.yj202588.top/Article/details/gtiyjrrdga.html

[Q16] 查询指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwnykadl.html

SELECT id, name FROM users;
来源：http://dali.zycfv.cn/Article/details/gtwmbijabr.html

[Q17] 条件查询
来源：http://dali.tianlin.xyz/Article/details/gtgitghbve.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258.top/Article/details/gtbmvejwjj.html

[Q18] 模糊匹配
来源：http://dali.gogol.net.cn/Article/details/gtsdvvyecw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xinyue.icu/Article/details/gtinkgofaz.html

[Q19] 范围查询
来源：http://dali.chenzaomai.com/Article/details/gtlldkdbfp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.haohaochexian.top/Article/details/gtljlrpsyw.html

[Q20] IN 列表
来源：http://dali.fengsongda.top/Article/details/gtjsxbzaed.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shzxlz.cn/Article/details/gttyimuhzx.html

[Q21] 空值判断
来源：http://dali.havefunace.top/Article/details/gtmanbqaaw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj20258888.top/Article/details/gtoecnipbf.html

[Q22] 排序
来源：http://dali.pengpengdd.cyou/Article/details/gtatiolkna.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jlsjyb.cn/Article/details/gtzwmfmqek.html

[Q23] 分页
来源：http://dali.daxiang520.top/Article/details/gtljsnlgvp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.pycfn.com/Article/details/gtfowgkeha.html

[Q24] 去重
来源：http://dali.316326.xyz/Article/details/gtazkjbgus.html

SELECT DISTINCT city FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtsydvugag.html

[Q25] 只取前 N 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtgihdxt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhengqikj.top/Article/details/gtchilqcqe.html

[Q26] 计数
来源：http://dali.haohaochexian.top/Article/details/gtrjiufvlu.html

SELECT COUNT(*) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtjzpxykom.html

[Q27] 条件计数
来源：http://dali.andypj.xyz/Article/details/gthdvftlyl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangdashe.top/Article/details/gtuxavyldv.html

[Q28] 求和与平均
来源：http://dali.yongpay.top/Article/details/gtexbpmjea.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtlrhvxxea.html

[Q29] 最大最小值
来源：http://dali.jinqigfzy.top/Article/details/gthoamjnts.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtryvyrfes.html

[Q30] 分组统计
来源：http://dali.hongshengwenyu.top/Article/details/gtidxpwsfe.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gtzmgoxtqb.html

[Q31] 分组后过滤
来源：http://dali.yj20258888.top/Article/details/gtviomukso.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cheryme.top/Article/details/gthyadclhm.html

[Q32] 分组拼接字符串
来源：http://dali.iojbl.cn/Article/details/gtlntbtkqk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gtilmefbsq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gzhubu.top/Article/details/gtihjjaaao.html

[Q33] 多列分组
来源：http://dali.gzhubu.top/Article/details/gtpwtgquxy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.feifeiyinyue.top/Article/details/gtilmosqlf.html

[Q34] 每组取第一条
来源：http://dali.fzhhl.top/Article/details/gtrjliwink.html

SELECT * FROM (
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflzktkqr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvhuyvge.html

) t WHERE rn = 1;
来源：http://dali.yuxming.cn/Article/details/gtunsppilv.html

[Q35] 内连接
来源：http://dali.jqgufenzy.top/Article/details/gtiqbdsnzx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.pycfn.com/Article/details/gtfgmxjdug.html

[Q36] 左连接
来源：http://dali.aibaodan.cn/Article/details/gtbgwdiipr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hywenlv.cn/Article/details/gtmncbiyng.html

[Q37] 右连接
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhkpgxjp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cheryme.top/Article/details/gtzgdnknff.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj202588.top/Article/details/gtxlqulbqt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fzhhl.top/Article/details/gtrtsxmubc.html

[Q39] 自连接（查上下级）
来源：http://dali.cashguo.top/Article/details/gtybpdaroh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.svipenyu.cn/Article/details/gtfsphfdpv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gaohongyu789.top/Article/details/gtsiqvyatg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.quarkkingdee.top/Article/details/gtmpczyvbx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.guannengcc.top/Article/details/gtfqrhumlh.html

[Q41] 多表连接
来源：http://dali.yuanzhike.top/Article/details/gtdpgcoqly.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxclohvp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fzhhl.top/Article/details/gtjdtdfnld.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yuanzhike.top/Article/details/gtiltryakh.html

[Q42] 连接条件附加过滤
来源：http://dali.birdmap.top/Article/details/gtnflkilld.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cheryme.top/Article/details/gtcyxkoszu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yanxiufei.cn/Article/details/gtmpbqhejs.html

[Q43] 标量子查询
来源：http://dali.yanxiufei.cn/Article/details/gtpmzuhzrf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gaohongyu789.top/Article/details/gtknzjyjbs.html

[Q44] IN 子查询
来源：http://dali.vqdsnc.cn/Article/details/gtinrqnpnt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nwbrower.top/Article/details/gtxixtnsze.html

[Q45] EXISTS 判断存在
来源：http://dali.wangdashe.top/Article/details/gtstjlvzki.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxuanxn.top/Article/details/gtkvfndcwg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtemfhzfdy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gtyxtdlzak.html

[Q47] 与平均值比较
来源：http://dali.yueranfly.top/Article/details/gtznqkezut.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.feifeiyinyue.top/Article/details/gtswhfhykm.html

[Q48] CTE 公用表表达式
来源：http://dali.yongpay.top/Article/details/gtikdgsrcd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.316326.xyz/Article/details/gtfudnpxhl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.meibo888.top/Article/details/gtynvtsdpm.html

[Q49] 更新单行
来源：http://dali.pengpengdd.cyou/Article/details/gtxboyhnnq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtywlopx.html

[Q50] 批量更新
来源：http://dali.guannengcc.top/Article/details/gtbioqrsxj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigufen.top/Article/details/gtjdzrmfdr.html

[Q51] 用子查询更新
来源：http://dali.yangfankeji.com/Article/details/gtmidyeenm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtbtmlzbeu.html

[Q52] 删除指定行
来源：http://dali.dashuyun.cn/Article/details/gtrxgenvyx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gaohongyu789.top/Article/details/gtmgmulzdk.html

[Q53] 按条件删除
来源：http://dali.jiagoushi.top/Article/details/gtjebbmzsx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jqgfzy.top/Article/details/gtxqtcoojd.html

[Q54] 清空表
来源：http://dali.guowangkeji.top/Article/details/gtlmkajbnm.html

TRUNCATE TABLE logs;
来源：http://dali.nanxuanxn.top/Article/details/gtovhqdmgm.html

[Q55] 排名（并列占位）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvyfihzw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.c1oappe.top/Article/details/gtzzhgalyi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj202588.top/Article/details/gtptmeedry.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.0kj1m.cn/Article/details/gtlrxgxaii.html

[Q57] 行号
来源：http://dali.meibo888.top/Article/details/gtdpnmjbkb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tanke756.top/Article/details/gtvuuazkjk.html

[Q58] 累计求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjdmkqco.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtfnidjkqe.html

[Q59] 分组内累计
来源：http://dali.xziqi.cn/Article/details/gtujhnulze.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtlgppcrfc.html

[Q60] 取上一行 / 下一行
来源：http://dali.hywenlv.cn/Article/details/gtnuvltvnd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ppjwa.cn/Article/details/gtnjtmyjfq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtirbmqfgf.html

[Q61] 移动平均
来源：http://dali.gaohongyu789.top/Article/details/gtbprmpsbq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtrucvzkve.html

[Q62] 分组占比
来源：http://dali.yueranfly.top/Article/details/gtdkhcyzdp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gthgccqzft.html

[Q63] 开启事务
来源：http://dali.svipenyu.cn/Article/details/gtwqqfosph.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.snrcjt.cn/Article/details/gtmcseecut.html

[Q64] 提交事务
来源：http://dali.pengpengdd.cyou/Article/details/gtntxroqif.html

COMMIT;
来源：http://dali.xylfe.cn/Article/details/gtssvbgsuc.html

[Q65] 回滚事务
来源：http://dali.chenzaomai.com/Article/details/gtsiysqans.html

ROLLBACK;
来源：http://dali.aizwys.cn/Article/details/gtgjymzsho.html

[Q66] 行锁查询
来源：http://dali.zhixingplan.top/Article/details/gttxjmytte.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvphtircy.html

[Q67] 设置隔离级别
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnjqbjwz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.meibo888.top/Article/details/gtefjjsqhd.html

[Q68] 保存点
来源：http://dali.xinyue.icu/Article/details/gtmlumbpyq.html

SAVEPOINT sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgkmnpbzc.html

ROLLBACK TO sp1;
来源：http://dali.ppjwa.cn/Article/details/gteintyzoi.html

[Q69] 查看执行计划
来源：http://dali.tanke756.top/Article/details/gtvwvlocai.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gaohongyu789.top/Article/details/gtqcfbcpbl.html

[Q70] 更新统计信息
来源：http://dali.shangyingyoupin.top/Article/details/gtwipeefcr.html

ANALYZE TABLE users;
来源：http://dali.tian-w.cn/Article/details/gtmezlbwmr.html

[Q71] 查看建表语句
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjuttuci.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgfzy.top/Article/details/gtoevwerge.html

[Q72] 查看索引
来源：http://dali.xylfe.cn/Article/details/gtdzthbqyd.html

SHOW INDEX FROM users;
来源：http://dali.xinyue.icu/Article/details/gtkixgdvof.html

[Q73] 查看表状态
来源：http://dali.9152youxi.cn/Article/details/gtmloboemy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuanzhike.top/Article/details/gteviaeehe.html

[Q74] 强制使用索引
来源：http://dali.haohaochexian.top/Article/details/gtgjqqppml.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.kuanghao11.cn/Article/details/gttuuqpdis.html

[Q75] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gtptgzdglq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdykpcaa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.c1oappe.top/Article/details/gteblgkkdi.html

[Q76] 按天统计
来源：http://dali.aizwys.cn/Article/details/gtltfpwutw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xuanzx.com/Article/details/gtouayjefn.html

[Q77] 时间加减
来源：http://dali.quarkkingdee.top/Article/details/gtxfzfafde.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tianlin.xyz/Article/details/gtoyfgkyxg.html

[Q78] 当前时间
来源：http://dali.yuxming.cn/Article/details/gtidtocvyg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.c1oappe.top/Article/details/gtayaaxlja.html

[Q79] 字符串拼接
来源：http://dali.sufxvd.cn/Article/details/gtlcxqjcpa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shangyingyoupin.top/Article/details/gtwculhocs.html

[Q80] 字符串截取
来源：http://dali.cheryme.top/Article/details/gtnhxcoxdb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtcctnemrq.html

[Q81] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gtnloivixv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xinyue.icu/Article/details/gtxurckquv.html

[Q82] 字符长度与字节长度
来源：http://dali.hnqzz.top/Article/details/gtmhypjzbz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtxvbovwjy.html

[Q83] 大小写转换
来源：http://dali.pycfn.com/Article/details/gtaaxmycoo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtxtuspzfv.html

[Q84] 去除首尾空格
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqjcovjwk.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gtpsbokfid.html

[Q85] 数值取整
来源：http://dali.meibo888.top/Article/details/gtajfnxvue.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.birdmap.top/Article/details/gttokcypvv.html

[Q86] 读取 JSON 字段
来源：http://dali.jlsjyb.cn/Article/details/gtyafcbbvu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shangyingyoupin.top/Article/details/gtqcwrlawa.html

[Q87] JSON 字段做条件
来源：http://dali.jianghu66.top/Article/details/gtvkrfpfnj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.andypj.xyz/Article/details/gtfazlntxj.html

[Q88] 行转列（条件聚合）
来源：http://dali.sysykeji.top/Article/details/gtikectdwr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cucudq.cn/Article/details/gthxtfvlac.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.meibo888.top/Article/details/gtevmkalyv.html

[Q89] 判断表是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gttfwpzjyh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj202588.top/Article/details/gtrjjfevso.html

[Q90] 生成序号列
来源：http://dali.xylfe.cn/Article/details/gtyevrkbym.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhengqikj.top/Article/details/gtdsafekls.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtuuswrecc.html

R. Bash 专题
来源：http://dali.wangshuangyany.cn/Article/details/gtetynagat.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtjuciwfua.html

[R01] shebang 与严格模式
来源：http://dali.gaohongyu789.top/Article/details/gtupviligr.html

#!/usr/bin/env bash
来源：http://dali.sweek.top/Article/details/gtiqptcvvn.html

set -euo pipefail
来源：http://dali.daxiang520.top/Article/details/gtswywxqkk.html

[R02] 变量赋值与使用
来源：http://dali.cashguo.top/Article/details/gtflkblshe.html

name="Tom"; echo "$name"
来源：http://dali.aibaodan.cn/Article/details/gtvlpzcluq.html

[R03] 只读变量
来源：http://dali.yanxiufei.cn/Article/details/gtaklxyaau.html

readonly PI=3.14
来源：http://dali.ivvv.top/Article/details/gtipcyjcpc.html

[R04] 位置参数
来源：http://dali.cqqwz.cn/Article/details/gttxqisvia.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.haohaochexian.top/Article/details/gthprdbmwj.html

[R05] 参数默认值
来源：http://dali.daria6918.cn/Article/details/gtcxmkqijt.html

name="${1:-default}"
来源：http://dali.hnqzz.top/Article/details/gtbdjkdgxt.html

[R06] 判断命令是否存在
来源：http://dali.redwolf501.top/Article/details/gtdzpqdgsx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gthwigpnwa.html

[R07] if 判断文件
来源：http://dali.cdnleiting.top/Article/details/gtxaqzbixh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cheryme.top/Article/details/gtyqmnalji.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gtpsnypojh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcfxtgzri.html

[R09] 字符串比较
来源：http://dali.tianlin.xyz/Article/details/gtbqiaccxx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtcmzoafgx.html

[R10] 正则匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxyeeqhga.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtiohnkkmy.html

[R11] case 多分支
来源：http://dali.shangyingyoupin.top/Article/details/gtltfoiemb.html

case "$1" in
来源：http://dali.ppjwa.cn/Article/details/gtozyboekz.html

start) echo "启动" ;;
来源：http://dali.xuanzx.com/Article/details/gtqljhtdwb.html

stop)  echo "停止" ;;
来源：http://dali.jinqigfzy.top/Article/details/gteazceqnv.html

*)     echo "未知命令" ;;
来源：http://dali.iojbl.cn/Article/details/gteqdpzidp.html

esac
来源：http://dali.shuidangran.top/Article/details/gtewqbbwoc.html

[R12] for 遍历文件
来源：http://dali.yj202588.top/Article/details/gtksqsqzuw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.birdmap.top/Article/details/gtzvbioawp.html

[R13] for 计数循环
来源：http://dali.zdqjudy.top/Article/details/gtgkqpawhc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.quarkkingdee.top/Article/details/gtsuuhtbri.html

[R14] C 风格 for
来源：http://dali.jianghu66.top/Article/details/gtzivxxhze.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjfzitsg.html

[R15] while 逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtxhcyirkd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jyoumei.cn/Article/details/gthvbcyrig.html

[R16] until 等待条件
来源：http://dali.xylfe.cn/Article/details/gtcqnqgjjl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gtaysllqua.html

[R17] 数组定义与取值
来源：http://dali.jyoumei.cn/Article/details/gtsqcgmvkv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nwbrower.top/Article/details/gtzinazeql.html

[R18] 遍历数组
来源：http://dali.andypj.xyz/Article/details/gtoiehvjtg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtfmrndedb.html

[R19] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gtefzvhntt.html

echo "${#arr[@]}"
来源：http://dali.gotoacloud.top/Article/details/gtpbfsecpc.html

[R20] 关联数组（字典）
来源：http://dali.haohaochexian.top/Article/details/gtsisxsfmj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gotoacloud.top/Article/details/gtmijvqzgl.html

[R21] 字符串长度
来源：http://dali.svipenyu.cn/Article/details/gtavnmtovd.html

echo "${#s}"
来源：http://dali.ivvv.top/Article/details/gtesctgxpp.html

[R22] 截取子串
来源：http://dali.cheryme.top/Article/details/gtapcweivl.html

echo "${s:0:5}"
来源：http://dali.jinqigufen.top/Article/details/gtftkrtmor.html

[R23] 字符串替换
来源：http://dali.hysaishi.cn/Article/details/gtlqzqevzr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.c1oappe.top/Article/details/gtkwlxaofd.html

[R24] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gtamongwri.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hammf.cn/Article/details/gtptmeccnq.html

[R25] 去后缀 / 去前缀
来源：http://dali.tanke756.top/Article/details/gtujbdsmzl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nwbrower.top/Article/details/gtqyzflirn.html

[R26] 命令替换
来源：http://dali.cashguo.top/Article/details/gtknwnztsb.html

now=$(date +%F); echo "$now"
来源：http://dali.redwolf501.top/Article/details/gtjczppded.html

[R27] 算术展开
来源：http://dali.jqgufenzy.top/Article/details/gteztjamnj.html

echo $((1 + 2 * 3))
来源：http://dali.yueranfly.top/Article/details/gtbhezarpg.html

[R28] 浮点运算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqrnggjkg.html

echo "scale=2; 10/3" | bc
来源：http://dali.ivvv.top/Article/details/gtyvuqremk.html

[R29] 定义函数
来源：http://dali.snrcjt.cn/Article/details/gtalwgkzke.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gogol.net.cn/Article/details/gtwvfmyewe.html

[R30] 函数返回状态码
来源：http://dali.aizwys.cn/Article/details/gtjibizbtv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.c1oappe.top/Article/details/gtingyosqi.html

[R31] 局部变量
来源：http://dali.mhx1999.top/Article/details/gtxrartfvp.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtntswwhde.html

[R32] 参数个数校验
来源：http://dali.wangshuangyany.cn/Article/details/gtltznsouc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jlsjyb.cn/Article/details/gtgntluffs.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gtieojxfti.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jqgfzy.top/Article/details/gtwjuituxm.html

[R34] 退出时清理
来源：http://dali.yvedp.cn/Article/details/gtbvoytlzv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xziqi.cn/Article/details/gtdrusxpug.html

[R35] 后台执行并等待
来源：http://dali.hfpthk.cn/Article/details/gtjwqtfipn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwosftatp.html

[R36] 并发执行多个任务
来源：http://dali.andypj.xyz/Article/details/gttberyqbh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhiwuduotai.top/Article/details/gtyjjjrxqz.html

[R37] 把输出赋给变量
来源：http://dali.smart0.xyz/Article/details/gthapnvwec.html

files=$(ls -1)
来源：http://dali.c1oappe.top/Article/details/gtktuycavm.html

[R38] 管道串联
来源：http://dali.yj20258.top/Article/details/gtnekclvsc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.pengpengdd.cyou/Article/details/gttsmjsygn.html

[R39] 重定向标准输出与错误
来源：http://dali.jianghu66.top/Article/details/gtoexacywk.html

cmd > out.log 2>&1
来源：http://dali.pycfn.com/Article/details/gtemsvmfhp.html

[R40] 追加写日志
来源：http://dali.ydzc1.top/Article/details/gtczxunlmo.html

echo "log" >> out.log
来源：http://dali.ivvv.top/Article/details/gtdfsbosui.html

[R41] 丢弃输出
来源：http://dali.tanke756.top/Article/details/gtppzowvds.html

cmd >/dev/null 2>&1
来源：http://dali.wangdashe.top/Article/details/gteakbxvzq.html

[R42] 输入重定向
来源：http://dali.redwolf501.top/Article/details/gtibvjpnbf.html

wc -l < a.txt
来源：http://dali.chenzaomai.com/Article/details/gtjwljvnjv.html

[R43] 按名字查找文件
来源：http://dali.feifeiyinyue.top/Article/details/gtsnxutuqx.html

find . -name "*.log" -type f
来源：http://dali.zhiwuduotai.top/Article/details/gtqldsufxh.html

[R44] 按修改时间查找
来源：http://dali.andypj.xyz/Article/details/gtlnfvcjyn.html

find . -mtime -7 -type f
来源：http://dali.hysaishi.cn/Article/details/gtxonnjbku.html

[R45] 批量删除
来源：http://dali.tianlin.xyz/Article/details/gtlctokkrx.html

find . -name "*.tmp" -delete
来源：http://dali.dashuyun.cn/Article/details/gtwqkxabsq.html

[R46] 递归替换文件内容
来源：http://dali.wangdashe.top/Article/details/gtucjpuahh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dashuyun.cn/Article/details/gtflujziwp.html

[R47] sed 单行替换
来源：http://dali.xylfe.cn/Article/details/gtbciikeld.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jiagoushi.top/Article/details/gtaztifmrb.html

[R48] awk 取指定列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsozmuwq.html

awk '{print $1, $3}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtwuxlhqah.html

[R49] awk 带条件
来源：http://dali.pycfn.com/Article/details/gtmefjnlwq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tanke756.top/Article/details/gtkezoqaln.html

[R50] awk 求和
来源：http://dali.wangshuangyany.cn/Article/details/gtxpqjxonk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nanxinkj.top/Article/details/gtozuytavx.html

[R51] 排序去重取前几
来源：http://dali.zhongyouzk.top/Article/details/gtaivwstzu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tanke756.top/Article/details/gtbeozgmih.html

[R52] 统计行数
来源：http://dali.yj20258888.top/Article/details/gtiknyygvr.html

wc -l a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gthitorhbg.html

[R53] 查看文件头与实时尾
来源：http://dali.xinyue.icu/Article/details/gtrzifcltj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj202588.top/Article/details/gtspoourng.html

[R54] 比较两个文件
来源：http://dali.guowangkeji.top/Article/details/gtncfrnwdc.html

diff a.txt b.txt
来源：http://dali.yonumen.top/Article/details/gtpzpvjovj.html

[R55] 压缩与解压
来源：http://dali.fzhhl.top/Article/details/gtkzrcfkut.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.c1oappe.top/Article/details/gtilcsuigd.html

[R56] 远程拷贝
来源：http://dali.fzhhl.top/Article/details/gtjkcyzkce.html

scp file user@host:/path/
来源：http://dali.aizwys.cn/Article/details/gtimfrczjm.html

[R57] 远程执行命令
来源：http://dali.mhx1999.top/Article/details/gtlgppbmel.html


<!-- 参考信息 -->