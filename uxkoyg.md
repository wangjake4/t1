代发 wailian999

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yonumen.top/Article/details/gtpmhefanh.html

[Q07] 删除表
来源：http://dali.zhengqikj.top/Article/details/gtjmrxqwxt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ydzc1.top/Article/details/gtgrdpxftw.html

[Q08] 创建普通索引
来源：http://dali.cdnleiting.top/Article/details/gtngdfakaj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yonumen.top/Article/details/gtckbpeyiu.html

[Q09] 创建唯一索引
来源：http://dali.zycfv.cn/Article/details/gtlcgkmtsq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cashguo.top/Article/details/gtiixphcsf.html

[Q10] 插入单行
来源：http://dali.yonumen.top/Article/details/gtqeolwdtl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nwbrower.top/Article/details/gtijsczzye.html

[Q11] 一次插入多行
来源：http://dali.0kj1m.cn/Article/details/gtqnsvpaai.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.fengsongda.top/Article/details/gtfhkjkrbb.html

[Q12] 插入后取自增 ID
来源：http://dali.xuanzx.com/Article/details/gtvywinipr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cheryme.top/Article/details/gtffjjxonf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhoulong.xyz/Article/details/gtkeekpbiu.html

[Q13] 忽略重复插入
来源：http://dali.hfpthk.cn/Article/details/gtbdhyarze.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.0kj1m.cn/Article/details/gtzstcfuuz.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhengqikj.top/Article/details/gtlwatptkm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gtosxoqgaf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.svipenyu.cn/Article/details/gtnekkhvrm.html

[Q15] 查询全部
来源：http://dali.yueranfly.top/Article/details/gtdjzwecqq.html

SELECT * FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtryduhwqb.html

[Q16] 查询指定列
来源：http://dali.gotoacloud.top/Article/details/gtvyrckjcs.html

SELECT id, name FROM users;
来源：http://dali.shuidangran.top/Article/details/gtmdffibmf.html

[Q17] 条件查询
来源：http://dali.nanxuanxn.top/Article/details/gtjpgsqqim.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ybcxt.top/Article/details/gtwwnxxqep.html

[Q18] 模糊匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtehetaesl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fengsongda.top/Article/details/gtlujpmiub.html

[Q19] 范围查询
来源：http://dali.aibaodan.cn/Article/details/gtqykxjyra.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhoulong.xyz/Article/details/gtnirtplao.html

[Q20] IN 列表
来源：http://dali.zhoulong.xyz/Article/details/gtywouhkze.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cashguo.top/Article/details/gtuevlykdv.html

[Q21] 空值判断
来源：http://dali.wangdashe.top/Article/details/gtfqzouozl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.9152youxi.cn/Article/details/gtcexrzttf.html

[Q22] 排序
来源：http://dali.yj20258888.top/Article/details/gtlbrzyxla.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbetlkpu.html

[Q23] 分页
来源：http://dali.nwbrower.top/Article/details/gtbpjgwjyt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.snrcjt.cn/Article/details/gturgidmxg.html

[Q24] 去重
来源：http://dali.yongpay.top/Article/details/gtutbvsnrf.html

SELECT DISTINCT city FROM users;
来源：http://dali.sxryk.cn/Article/details/gtubqogjvu.html

[Q25] 只取前 N 条
来源：http://dali.yueranfly.top/Article/details/gttruotwry.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yueranfly.top/Article/details/gtrmznbvvn.html

[Q26] 计数
来源：http://dali.jqgufenzy.top/Article/details/gtxxfuulln.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtayowpqbt.html

[Q27] 条件计数
来源：http://dali.hywenlv.cn/Article/details/gtcheuflfv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ydzc1.top/Article/details/gtlikbdjvc.html

[Q28] 求和与平均
来源：http://dali.0kj1m.cn/Article/details/gtdcllfiyw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtzdcjsqcd.html

[Q29] 最大最小值
来源：http://dali.jiagoushi.top/Article/details/gtqyufodao.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtpsbjprsk.html

[Q30] 分组统计
来源：http://dali.yueranfly.top/Article/details/gtadltjkdm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmolobvn.html

[Q31] 分组后过滤
来源：http://dali.haohaochexian.top/Article/details/gtgcyripsk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hywenlv.cn/Article/details/gtjsyubxcf.html

[Q32] 分组拼接字符串
来源：http://dali.yuxming.cn/Article/details/gtbzicukfo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gthieraoly.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuetiantiany.cn/Article/details/gtwbjmtmih.html

[Q33] 多列分组
来源：http://dali.jinqigfzy.top/Article/details/gteoardsit.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.wangdashe.top/Article/details/gtkqqbdipv.html

[Q34] 每组取第一条
来源：http://dali.fzhhl.top/Article/details/gtivtwvlxh.html

SELECT * FROM (
来源：http://dali.zhiwuduotai.top/Article/details/gtvffbyfan.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dashuyun.cn/Article/details/gtvxapdxix.html

) t WHERE rn = 1;
来源：http://dali.nanxinkj.top/Article/details/gttruigqiw.html

[Q35] 内连接
来源：http://dali.zhiwuduotai.top/Article/details/gtqdjxwkhl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shangyingyoupin.top/Article/details/gtomfqxifn.html

[Q36] 左连接
来源：http://dali.chenlongwang.top/Article/details/gtxaxdgaag.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyratcxic.html

[Q37] 右连接
来源：http://dali.0kj1m.cn/Article/details/gtxwhcykml.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cdnleiting.top/Article/details/gtgndkawyu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jqgfzy.top/Article/details/gtnnoqlgae.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.pycfn.com/Article/details/gtyqqjwrvk.html

[Q39] 自连接（查上下级）
来源：http://dali.sufxvd.cn/Article/details/gtrliyimph.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.svipenyu.cn/Article/details/gtygbichrb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aizwys.cn/Article/details/gtdasrcstx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xziqi.cn/Article/details/gtitjeslsy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ppjwa.cn/Article/details/gtfvcojozo.html

[Q41] 多表连接
来源：http://dali.sweek.top/Article/details/gtzurypnka.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hammf.cn/Article/details/gtivgvgvyc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ehwqpu.com/Article/details/gtpbctsiaw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.316326.xyz/Article/details/gtsmghxjct.html

[Q42] 连接条件附加过滤
来源：http://dali.gotoacloud.top/Article/details/gtmhgevpmj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.aizwys.cn/Article/details/gtrfxhdrtt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.9152youxi.cn/Article/details/gtumqdikbh.html

[Q43] 标量子查询
来源：http://dali.sufxvd.cn/Article/details/gtlkrfkgzs.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zycfv.cn/Article/details/gtzkjmiduy.html

[Q44] IN 子查询
来源：http://dali.kuanghao11.cn/Article/details/gtdibhlmji.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ivvv.top/Article/details/gttelizksv.html

[Q45] EXISTS 判断存在
来源：http://dali.zhiwuduotai.top/Article/details/gtyvghpfzg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangdashe.top/Article/details/gtnfnayfnp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.haohaochexian.top/Article/details/gtkcmznqnq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jiagoushi.top/Article/details/gtrmidtsdu.html

[Q47] 与平均值比较
来源：http://dali.yanxiufei.cn/Article/details/gthnbaqrqa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xuanzx.com/Article/details/gtttfjpjdl.html

[Q48] CTE 公用表表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtooivelnm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cashguo.top/Article/details/gtrnvauxao.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aibaodan.cn/Article/details/gtkkkbwgpf.html

[Q49] 更新单行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihvcbhmy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sxryk.cn/Article/details/gtscjiixdu.html

[Q50] 批量更新
来源：http://dali.chenjidiqi.icu/Article/details/gttdvkpymf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjwfjzre.html

[Q51] 用子查询更新
来源：http://dali.vqdsnc.cn/Article/details/gtxofsqmva.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinqigufen.top/Article/details/gttywpfzxg.html

[Q52] 删除指定行
来源：http://dali.cheryme.top/Article/details/gtztuoxnof.html

DELETE FROM users WHERE id = 10;
来源：http://dali.9152youxi.cn/Article/details/gtwtcwcvhy.html

[Q53] 按条件删除
来源：http://dali.jqgfzy.top/Article/details/gtajkrzymd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.0kj1m.cn/Article/details/gtqeomkjxg.html

[Q54] 清空表
来源：http://dali.gotoacloud.top/Article/details/gtwkfwnmzf.html

TRUNCATE TABLE logs;
来源：http://dali.hysaishi.cn/Article/details/gtpluohsey.html

[Q55] 排名（并列占位）
来源：http://dali.xylfe.cn/Article/details/gtuvlztolx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yvedp.cn/Article/details/gtsnjsljan.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjpkawia.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.daria6918.cn/Article/details/gtbnhhtres.html

[Q57] 行号
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnwatuww.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtegxzajji.html

[Q58] 累计求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobrbogfw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gthbphntkv.html

[Q59] 分组内累计
来源：http://dali.fengsongda.top/Article/details/gtvbwzsbeu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gttlhgzwzo.html

[Q60] 取上一行 / 下一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzjnsewx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ppjwa.cn/Article/details/gttdshketh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.iojbl.cn/Article/details/gthfhgabwo.html

[Q61] 移动平均
来源：http://dali.gogol.net.cn/Article/details/gtvbxmmukt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtrliecyeu.html

[Q62] 分组占比
来源：http://dali.aizwys.cn/Article/details/gtekiamexm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gtjbrjfkni.html

[Q63] 开启事务
来源：http://dali.dashuyun.cn/Article/details/gtahtrtlnu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.vqdsnc.cn/Article/details/gtgzywxwaa.html

[Q64] 提交事务
来源：http://dali.zhixingplan.top/Article/details/gtmwoqytxz.html

COMMIT;
来源：http://dali.cdnleiting.top/Article/details/gtuqomkzhu.html

[Q65] 回滚事务
来源：http://dali.zhixingplan.top/Article/details/gtocfnrchx.html

ROLLBACK;
来源：http://dali.hywenlv.cn/Article/details/gtnguyithp.html

[Q66] 行锁查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskntyzfa.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cqqwz.cn/Article/details/gtfzhkrmkg.html

[Q67] 设置隔离级别
来源：http://dali.hywenlv.cn/Article/details/gtjckxaduy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pengpengdd.cyou/Article/details/gtudaxruxe.html

[Q68] 保存点
来源：http://dali.smart0.xyz/Article/details/gtwbbwtrly.html

SAVEPOINT sp1;
来源：http://dali.cheryme.top/Article/details/gtqbuiarcq.html

ROLLBACK TO sp1;
来源：http://dali.hfpthk.cn/Article/details/gtyjtbqbda.html

[Q69] 查看执行计划
来源：http://dali.shanyushiyangtech.top/Article/details/gtyaxzevxz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.snrcjt.cn/Article/details/gtvlnwegup.html

[Q70] 更新统计信息
来源：http://dali.hammf.cn/Article/details/gtzemqahfh.html

ANALYZE TABLE users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctqvocvb.html

[Q71] 查看建表语句
来源：http://dali.xziqi.cn/Article/details/gtdlucgsbl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhiwuduotai.top/Article/details/gtosachrec.html

[Q72] 查看索引
来源：http://dali.sweek.top/Article/details/gtqatvewxa.html

SHOW INDEX FROM users;
来源：http://dali.iojbl.cn/Article/details/gtuaglggok.html

[Q73] 查看表状态
来源：http://dali.tanke756.top/Article/details/gttgzmgvor.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.aibaodan.cn/Article/details/gtcyecwlyp.html

[Q74] 强制使用索引
来源：http://dali.quarkkingdee.top/Article/details/gtjhknpzag.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuetiantiany.cn/Article/details/gtjsteepdz.html

[Q75] 日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuyfrnuoi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ivvv.top/Article/details/gtjdxhfyvq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hnqzz.top/Article/details/gtykvddbgv.html

[Q76] 按天统计
来源：http://dali.shzxlz.cn/Article/details/gtbrzrbjpc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jqgfzy.top/Article/details/gtgurihpcx.html

[Q77] 时间加减
来源：http://dali.yj20258.top/Article/details/gttkrhmxvm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xziqi.cn/Article/details/gtkvbibvvy.html

[Q78] 当前时间
来源：http://dali.zhongyouzk.top/Article/details/gtqwalhkby.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.svipenyu.cn/Article/details/gtvhykxhas.html

[Q79] 字符串拼接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbwtuwcf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xuetiantiany.cn/Article/details/gtiaxfpgdg.html

[Q80] 字符串截取
来源：http://dali.ydzc1.top/Article/details/gtxxwflicb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtqsaxylsn.html

[Q81] 字符串替换
来源：http://dali.chenlongwang.top/Article/details/gtlokubgyi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.0kj1m.cn/Article/details/gteclvdlnc.html

[Q82] 字符长度与字节长度
来源：http://dali.xylfe.cn/Article/details/gthnxwkact.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtnbtknged.html

[Q83] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gtjmwfhrjm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtdqqusegz.html

[Q84] 去除首尾空格
来源：http://dali.jyoumei.cn/Article/details/gtgeoorhnr.html

SELECT TRIM(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkbgwpkw.html

[Q85] 数值取整
来源：http://dali.guowangkeji.top/Article/details/gtmqnmpxqz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinqigufen.top/Article/details/gtukskhlqr.html

[Q86] 读取 JSON 字段
来源：http://dali.dianchejie.cn/Article/details/gttpmbmlam.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xinyue.icu/Article/details/gtbaszktcn.html

[Q87] JSON 字段做条件
来源：http://dali.xinyue.icu/Article/details/gtckauoang.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegvhozxd.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkeuyxyfz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nwbrower.top/Article/details/gtwvznxgct.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cheryme.top/Article/details/gtjxtkkzig.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtspwjjzwg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cqqwz.cn/Article/details/gtrkjhpdgs.html

[Q90] 生成序号列
来源：http://dali.andypj.xyz/Article/details/gtwlipbseo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenlongwang.top/Article/details/gtkyxhxnlc.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtengwuuzf.html

R. Bash 专题
来源：http://dali.sufxvd.cn/Article/details/gtczmbfnnq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtqfmvjnim.html

[R01] shebang 与严格模式
来源：http://dali.yongpay.top/Article/details/gtxkogzfcw.html

#!/usr/bin/env bash
来源：http://dali.cashguo.top/Article/details/gtlycbwmaj.html

set -euo pipefail
来源：http://dali.yanxiufei.cn/Article/details/gtscdvdxmf.html

[R02] 变量赋值与使用
来源：http://dali.chenlongwang.top/Article/details/gtiwheqkte.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gtflmuvmsh.html

[R03] 只读变量
来源：http://dali.jyoumei.cn/Article/details/gtercbzrnh.html

readonly PI=3.14
来源：http://dali.quarkkingdee.top/Article/details/gtdyyunsfr.html

[R04] 位置参数
来源：http://dali.shangyingyoupin.top/Article/details/gtecfrezoz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgflhsmg.html

[R05] 参数默认值
来源：http://dali.aizwys.cn/Article/details/gtbriwjssb.html

name="${1:-default}"
来源：http://dali.fzhhl.top/Article/details/gtfjyyloyd.html

[R06] 判断命令是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjnlhliwm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gtzujroxzk.html

[R07] if 判断文件
来源：http://dali.jqgfzy.top/Article/details/gtdobskrpr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtpsegoaeh.html

[R08] 数值比较
来源：http://dali.shangyingyoupin.top/Article/details/gtepnktpax.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hfpthk.cn/Article/details/gtkxpbdsnj.html

[R09] 字符串比较
来源：http://dali.bjfxy.top/Article/details/gtqqdbbhme.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cucudq.cn/Article/details/gtvvwhfkhx.html

[R10] 正则匹配
来源：http://dali.meibo888.top/Article/details/gtrhtyxuaq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.haohaochexian.top/Article/details/gtihsmbujk.html

[R11] case 多分支
来源：http://dali.sufxvd.cn/Article/details/gtjxotcfvp.html

case "$1" in
来源：http://dali.chenjidiqi.icu/Article/details/gtzszmxegb.html

start) echo "启动" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmjtihsp.html

stop)  echo "停止" ;;
来源：http://dali.guannengcc.top/Article/details/gtzhtucvlv.html

*)     echo "未知命令" ;;
来源：http://dali.zhongyouzk.top/Article/details/gtektoygcy.html

esac
来源：http://dali.zhongyouzk.top/Article/details/gtrmjtisgp.html

[R12] for 遍历文件
来源：http://dali.jianghu66.top/Article/details/gtaaymtnse.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ehwqpu.com/Article/details/gtmrxbbruz.html

[R13] for 计数循环
来源：http://dali.xuanzx.com/Article/details/gtglpeqmnu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.mhx1999.top/Article/details/gtlghbjvoa.html

[R14] C 风格 for
来源：http://dali.yongpay.top/Article/details/gtfvpmuwer.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gthzbgrfco.html

[R15] while 逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtukobvsdc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hfpthk.cn/Article/details/gtntsqoozj.html

[R16] until 等待条件
来源：http://dali.chenzaomai.com/Article/details/gtvlluhloz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.aizwys.cn/Article/details/gttwttreyz.html

[R17] 数组定义与取值
来源：http://dali.jinqigfzy.top/Article/details/gtrepbbldn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigfzy.top/Article/details/gtmahfbnmr.html

[R18] 遍历数组
来源：http://dali.dianchejie.cn/Article/details/gtzqqznsee.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shangyingyoupin.top/Article/details/gteujkmmng.html

[R19] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gtwqlmtlga.html

echo "${#arr[@]}"
来源：http://dali.daxiang520.top/Article/details/gtpnfjvnfr.html

[R20] 关联数组（字典）
来源：http://dali.jqgufenzy.top/Article/details/gttgnxeaow.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxinkj.top/Article/details/gtdvgrfmqg.html

[R21] 字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gthxgauvdv.html

echo "${#s}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifwlfcla.html

[R22] 截取子串
来源：http://dali.xziqi.cn/Article/details/gtyyoqitsk.html

echo "${s:0:5}"
来源：http://dali.xziqi.cn/Article/details/gtouavvhkr.html

[R23] 字符串替换
来源：http://dali.zhongyouzk.top/Article/details/gtjjzuityu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.havefunace.top/Article/details/gtwpvuahpz.html

[R24] 大小写转换
来源：http://dali.yonumen.top/Article/details/gtwotbbuic.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.pycfn.com/Article/details/gtjwobclsi.html

[R25] 去后缀 / 去前缀
来源：http://dali.mhx1999.top/Article/details/gtjirtmrzu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.316326.xyz/Article/details/gtimgxyalk.html

[R26] 命令替换
来源：http://dali.pycfn.com/Article/details/gtkqhaislu.html

now=$(date +%F); echo "$now"
来源：http://dali.nanxuanxn.top/Article/details/gthqzmilrt.html

[R27] 算术展开
来源：http://dali.yuanzhike.top/Article/details/gttywwykde.html

echo $((1 + 2 * 3))
来源：http://dali.jqgufenzy.top/Article/details/gtafkhnwlt.html

[R28] 浮点运算
来源：http://dali.jyoumei.cn/Article/details/gtetgallvz.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj20258.top/Article/details/gthotnvbwm.html

[R29] 定义函数
来源：http://dali.9152youxi.cn/Article/details/gtercuwxqx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fzhhl.top/Article/details/gtjftzznwu.html

[R30] 函数返回状态码
来源：http://dali.svipenyu.cn/Article/details/gtywipcbap.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xinyue.icu/Article/details/gtjrdvoppp.html

[R31] 局部变量
来源：http://dali.nanxuanxn.top/Article/details/gtoulttnrc.html

f() { local x=1; echo "$x"; }
来源：http://dali.daxiang520.top/Article/details/gtistilnwq.html

[R32] 参数个数校验
来源：http://dali.mhx1999.top/Article/details/gtngtwgcfe.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gtduyjvxxf.html

[R33] 捕获错误并提示行号
来源：http://dali.daria6918.cn/Article/details/gtclbuqphz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jqgfzy.top/Article/details/gtlubhbhsn.html

[R34] 退出时清理
来源：http://dali.zycfv.cn/Article/details/gtaomkoezm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrayufxp.html

[R35] 后台执行并等待
来源：http://dali.guannengcc.top/Article/details/gtmosexmoj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenzaomai.com/Article/details/gtwvversxu.html

[R36] 并发执行多个任务
来源：http://dali.nanxinkj.top/Article/details/gtgzvjqrtl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gaohongyu789.top/Article/details/gtfiadmbip.html

[R37] 把输出赋给变量
来源：http://dali.jinqigufen.top/Article/details/gtkawbxdbl.html

files=$(ls -1)
来源：http://dali.sxryk.cn/Article/details/gtxmbznwct.html

[R38] 管道串联
来源：http://dali.feifeiyinyue.top/Article/details/gtboheqlgg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sysykeji.top/Article/details/gtbeglqymm.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigfzy.top/Article/details/gtgycnytms.html

cmd > out.log 2>&1
来源：http://dali.ehwqpu.com/Article/details/gttahshoua.html

[R40] 追加写日志
来源：http://dali.hfpthk.cn/Article/details/gtecylxqgo.html

echo "log" >> out.log
来源：http://dali.yvedp.cn/Article/details/gtfkgihmut.html

[R41] 丢弃输出
来源：http://dali.cashguo.top/Article/details/gtflvqukdw.html

cmd >/dev/null 2>&1
来源：http://dali.gzhubu.top/Article/details/gttptipric.html

[R42] 输入重定向
来源：http://dali.zhiwuduotai.top/Article/details/gtzawxddmp.html

wc -l < a.txt
来源：http://dali.shzxlz.cn/Article/details/gtqfrorvyi.html

[R43] 按名字查找文件
来源：http://dali.tanke756.top/Article/details/gtseotspcc.html

find . -name "*.log" -type f
来源：http://dali.316326.xyz/Article/details/gtxcadrktu.html

[R44] 按修改时间查找
来源：http://dali.zdqjudy.top/Article/details/gtgbqeoird.html

find . -mtime -7 -type f
来源：http://dali.nwbrower.top/Article/details/gtwfrozdvj.html

[R45] 批量删除
来源：http://dali.haohaochexian.top/Article/details/gtbbhszzto.html

find . -name "*.tmp" -delete
来源：http://dali.nanxuanxn.top/Article/details/gthsbjpjwo.html

[R46] 递归替换文件内容
来源：http://dali.cheryme.top/Article/details/gtfirsrbvz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinghuilouyu.cn/Article/details/gtekjltvik.html

[R47] sed 单行替换
来源：http://dali.yongpay.top/Article/details/gtjqltbzlm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.redwolf501.top/Article/details/gtqzxibthy.html

[R48] awk 取指定列
来源：http://dali.yuanzhike.top/Article/details/gtpymihhxl.html

awk '{print $1, $3}' a.txt
来源：http://dali.gotoacloud.top/Article/details/gtsntdhett.html

[R49] awk 带条件
来源：http://dali.zhoulong.xyz/Article/details/gtrquiqduu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daxiang520.top/Article/details/gtthrclbyn.html

[R50] awk 求和
来源：http://dali.daxiang520.top/Article/details/gtvzwqohad.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sweek.top/Article/details/gtgvtkmjwg.html

[R51] 排序去重取前几
来源：http://dali.nwbrower.top/Article/details/gtsqaunjza.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xylfe.cn/Article/details/gtglaaoseh.html

[R52] 统计行数
来源：http://dali.yongpay.top/Article/details/gtecaiiejr.html

wc -l a.txt
来源：http://dali.birdmap.top/Article/details/gtxafvgpxi.html

[R53] 查看文件头与实时尾
来源：http://dali.hywenlv.cn/Article/details/gttwjhnczm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tian-w.cn/Article/details/gtpjaiwvgg.html

[R54] 比较两个文件
来源：http://dali.andypj.xyz/Article/details/gttmldzpme.html

diff a.txt b.txt
来源：http://dali.zhongyouzk.top/Article/details/gtgcseffbq.html

[R55] 压缩与解压
来源：http://dali.nwbrower.top/Article/details/gtzqoxvvye.html


<!-- 参考信息 -->