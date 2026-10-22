代发 wailian999

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hfpthk.cn/Article/details/gtlnnfzjva.html

[Q09] 创建唯一索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxviicyt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuanzx.com/Article/details/gtrycagrme.html

[Q10] 插入单行
来源：http://dali.andypj.xyz/Article/details/gtnoqvzdki.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sysykeji.top/Article/details/gtvyjccjts.html

[Q11] 一次插入多行
来源：http://dali.guowangkeji.top/Article/details/gtjlylrlzz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.mhx1999.top/Article/details/gthqenvxjs.html

[Q12] 插入后取自增 ID
来源：http://dali.jianghu66.top/Article/details/gtspdgdaoe.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jianghu66.top/Article/details/gtsoesaikw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sweek.top/Article/details/gtmatbkrxi.html

[Q13] 忽略重复插入
来源：http://dali.birdmap.top/Article/details/gtrqiroynd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gtvoktemjh.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhoulong.xyz/Article/details/gttcwsfxou.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.havefunace.top/Article/details/gturwtvtse.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.mhx1999.top/Article/details/gtvyygnlop.html

[Q15] 查询全部
来源：http://dali.hammf.cn/Article/details/gtcwzvmpst.html

SELECT * FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtgvoiaoso.html

[Q16] 查询指定列
来源：http://dali.yvedp.cn/Article/details/gtvpsltqvu.html

SELECT id, name FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtgmbwmcfq.html

[Q17] 条件查询
来源：http://dali.sweek.top/Article/details/gtpcqbmqqj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daria6918.cn/Article/details/gtqkrkaljq.html

[Q18] 模糊匹配
来源：http://dali.jianghu66.top/Article/details/gtwcalopno.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fengsongda.top/Article/details/gtpetfphkv.html

[Q19] 范围查询
来源：http://dali.hnxiangtu.top/Article/details/gtobhrtxtm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ybcxt.top/Article/details/gtmnxlewhv.html

[Q20] IN 列表
来源：http://dali.feifeiyinyue.top/Article/details/gtlvjgflcy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zycfv.cn/Article/details/gtpsefdmba.html

[Q21] 空值判断
来源：http://dali.cashguo.top/Article/details/gtszleimjy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jlsjyb.cn/Article/details/gtysdkrjqa.html

[Q22] 排序
来源：http://dali.ivvv.top/Article/details/gtspgrouod.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.daria6918.cn/Article/details/gtihhrqbpl.html

[Q23] 分页
来源：http://dali.jqgfzy.top/Article/details/gtqpvrjetm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shzxlz.cn/Article/details/gtdhvoivlt.html

[Q24] 去重
来源：http://dali.yj20258888.top/Article/details/gtcfhxvyaq.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtajllyded.html

[Q25] 只取前 N 条
来源：http://dali.ehwqpu.com/Article/details/gtcytulgmi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuanzhike.top/Article/details/gtofxisgzl.html

[Q26] 计数
来源：http://dali.jinqigfzy.top/Article/details/gtgxmnyfxa.html

SELECT COUNT(*) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtcbdteiwp.html

[Q27] 条件计数
来源：http://dali.aizwys.cn/Article/details/gtfhnduknc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cdnleiting.top/Article/details/gthttfvvuy.html

[Q28] 求和与平均
来源：http://dali.iojbl.cn/Article/details/gtxcrajegh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtjkrizcoz.html

[Q29] 最大最小值
来源：http://dali.gotoacloud.top/Article/details/gtiddrhgop.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj202588.top/Article/details/gtzichrdcj.html

[Q30] 分组统计
来源：http://dali.bjfxy.top/Article/details/gtxjibqove.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gtrytcxdnl.html

[Q31] 分组后过滤
来源：http://dali.hfpthk.cn/Article/details/gtzrkntcrr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.andypj.xyz/Article/details/gtqeavracj.html

[Q32] 分组拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gtzheqobkk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gthauubmfy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shangyingyoupin.top/Article/details/gtyoniidud.html

[Q33] 多列分组
来源：http://dali.c1oappe.top/Article/details/gtjkrqkvmd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hongshengwenyu.top/Article/details/gtkznwlsnz.html

[Q34] 每组取第一条
来源：http://dali.hfpthk.cn/Article/details/gtfvufbcph.html

SELECT * FROM (
来源：http://dali.ehwqpu.com/Article/details/gtawtdvjvw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.daxiang520.top/Article/details/gtlcewihpt.html

) t WHERE rn = 1;
来源：http://dali.jianghu66.top/Article/details/gtecgfqwhn.html

[Q35] 内连接
来源：http://dali.zhiwuduotai.top/Article/details/gtpateqopb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sysykeji.top/Article/details/gtnxkrkovj.html

[Q36] 左连接
来源：http://dali.fzhhl.top/Article/details/gtgfqnvizd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daria6918.cn/Article/details/gtbzyngacb.html

[Q37] 右连接
来源：http://dali.jqgufenzy.top/Article/details/gtotjpvcig.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ppjwa.cn/Article/details/gtpndrpsbe.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuanzx.com/Article/details/gthqelgtak.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gaohongyu789.top/Article/details/gtskfkyxup.html

[Q39] 自连接（查上下级）
来源：http://dali.yanxiufei.cn/Article/details/gttlqfjdpg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj20258888.top/Article/details/gtmamgzjxy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.snrcjt.cn/Article/details/gtisprccca.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cdnleiting.top/Article/details/gtmrvcqoif.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hongshengwenyu.top/Article/details/gtzhldeqby.html

[Q41] 多表连接
来源：http://dali.svipenyu.cn/Article/details/gtrmmwoide.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sufxvd.cn/Article/details/gtmjhppmnq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gotoacloud.top/Article/details/gtcafmlucu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tanke756.top/Article/details/gtnlfowyox.html

[Q42] 连接条件附加过滤
来源：http://dali.yanxiufei.cn/Article/details/gtkddkeqcw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cashguo.top/Article/details/gtgetrywot.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.wangshuangyany.cn/Article/details/gttggpmkev.html

[Q43] 标量子查询
来源：http://dali.ydzc1.top/Article/details/gtzdmiqdxl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.feifeiyinyue.top/Article/details/gtbyybvxjn.html

[Q44] IN 子查询
来源：http://dali.xinyue.icu/Article/details/gtzevkumro.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zdqjudy.top/Article/details/gtlizhsshe.html

[Q45] EXISTS 判断存在
来源：http://dali.aibaodan.cn/Article/details/gtovccaybw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gtlvesbpzp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jlsjyb.cn/Article/details/gtgwfaukrf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gtwyogfnwy.html

[Q47] 与平均值比较
来源：http://dali.hfpthk.cn/Article/details/gtuxlkvsre.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.andypj.xyz/Article/details/gtdtpokrpf.html

[Q48] CTE 公用表表达式
来源：http://dali.zhoulong.xyz/Article/details/gtdtlnmxhw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.guowangkeji.top/Article/details/gtpbormlbm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ivvv.top/Article/details/gtvkhcxkrz.html

[Q49] 更新单行
来源：http://dali.xuetiantiany.cn/Article/details/gtuaqoijnz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxinkj.top/Article/details/gttwymolwd.html

[Q50] 批量更新
来源：http://dali.hongshengwenyu.top/Article/details/gtcmhoxynu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.pycfn.com/Article/details/gtntkfuzkd.html

[Q51] 用子查询更新
来源：http://dali.meibo888.top/Article/details/gtkwlyyyjn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.dashuyun.cn/Article/details/gttwcxknug.html

[Q52] 删除指定行
来源：http://dali.svipenyu.cn/Article/details/gtyjeqpaod.html

DELETE FROM users WHERE id = 10;
来源：http://dali.pycfn.com/Article/details/gtgepnojpe.html

[Q53] 按条件删除
来源：http://dali.andypj.xyz/Article/details/gtqzktgjyb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gtmykebmtn.html

[Q54] 清空表
来源：http://dali.aibaodan.cn/Article/details/gteooiyeus.html

TRUNCATE TABLE logs;
来源：http://dali.tanke756.top/Article/details/gtauqntlgu.html

[Q55] 排名（并列占位）
来源：http://dali.cucudq.cn/Article/details/gtrhgckpgj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hnxiangtu.top/Article/details/gtuepsrnss.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpyvzaai.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hywenlv.cn/Article/details/gtxsdgfdep.html

[Q57] 行号
来源：http://dali.jinqigufen.top/Article/details/gtbbjwgvsb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yvedp.cn/Article/details/gtjunntsen.html

[Q58] 累计求和
来源：http://dali.zhoulong.xyz/Article/details/gtnjoffmwd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtikjjixgu.html

[Q59] 分组内累计
来源：http://dali.guowangkeji.top/Article/details/gtjocibuld.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtubyihzve.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhidmkjz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xziqi.cn/Article/details/gtugveoxcl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrqossnp.html

[Q61] 移动平均
来源：http://dali.zhixingplan.top/Article/details/gthpjmrzsl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtxccbxwzn.html

[Q62] 分组占比
来源：http://dali.snrcjt.cn/Article/details/gtcctkubof.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gtcrewqmtw.html

[Q63] 开启事务
来源：http://dali.hammf.cn/Article/details/gtbpvxgjuh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnxiangtu.top/Article/details/gtudpizlcw.html

[Q64] 提交事务
来源：http://dali.sxryk.cn/Article/details/gtmjpnmnvg.html

COMMIT;
来源：http://dali.mhx1999.top/Article/details/gtyfevufnp.html

[Q65] 回滚事务
来源：http://dali.guannengcc.top/Article/details/gtqgbbaotu.html

ROLLBACK;
来源：http://dali.gzhubu.top/Article/details/gtpuojmnjp.html

[Q66] 行锁查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlnrkalf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hfpthk.cn/Article/details/gtcnijygax.html

[Q67] 设置隔离级别
来源：http://dali.cucudq.cn/Article/details/gtmqbiblvm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.iojbl.cn/Article/details/gtoglsvgrb.html

[Q68] 保存点
来源：http://dali.hywenlv.cn/Article/details/gtzxdubukq.html

SAVEPOINT sp1;
来源：http://dali.hammf.cn/Article/details/gtiypddujb.html

ROLLBACK TO sp1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthjsxluzl.html

[Q69] 查看执行计划
来源：http://dali.bjfxy.top/Article/details/gtiorsnqyk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nanxuanxn.top/Article/details/gtvnknclfy.html

[Q70] 更新统计信息
来源：http://dali.redwolf501.top/Article/details/gtuowjciqa.html

ANALYZE TABLE users;
来源：http://dali.sysykeji.top/Article/details/gtwxipbnwc.html

[Q71] 查看建表语句
来源：http://dali.guowangkeji.top/Article/details/gtizrdezjt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yvedp.cn/Article/details/gtahrrsysv.html

[Q72] 查看索引
来源：http://dali.zhixingplan.top/Article/details/gtkekdtnzv.html

SHOW INDEX FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtddhatnja.html

[Q73] 查看表状态
来源：http://dali.chenlongwang.top/Article/details/gttkdwcfhq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.9152youxi.cn/Article/details/gtgfsljqja.html

[Q74] 强制使用索引
来源：http://dali.hammf.cn/Article/details/gtenhxcatp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuanzx.com/Article/details/gtxgwxzhpw.html

[Q75] 日期格式化
来源：http://dali.ivvv.top/Article/details/gtnqmccfch.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtftptrkny.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cucudq.cn/Article/details/gtqgxgcsty.html

[Q76] 按天统计
来源：http://dali.smart0.xyz/Article/details/gtuibkmzox.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.snrcjt.cn/Article/details/gtolqoumdg.html

[Q77] 时间加减
来源：http://dali.gaohongyu789.top/Article/details/gthumkbatl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.guannengcc.top/Article/details/gthbgvtgfr.html

[Q78] 当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gtasgprzjk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hywenlv.cn/Article/details/gtgnaicsie.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gtafwkfrjw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shzxlz.cn/Article/details/gtgoeoephg.html

[Q80] 字符串截取
来源：http://dali.sysykeji.top/Article/details/gtidixcefy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtzfwotvse.html

[Q81] 字符串替换
来源：http://dali.tianlin.xyz/Article/details/gtffnwcufs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.redwolf501.top/Article/details/gtezpfkzuj.html

[Q82] 字符长度与字节长度
来源：http://dali.vqdsnc.cn/Article/details/gtyiwzqtrj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtxqyxrusg.html

[Q83] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gtazqzfcel.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gttbbwmjxf.html

[Q84] 去除首尾空格
来源：http://dali.yongpay.top/Article/details/gtiyyvzzag.html

SELECT TRIM(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtglyvrugf.html

[Q85] 数值取整
来源：http://dali.yangfankeji.com/Article/details/gtgrtbkjgr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.kuanghao11.cn/Article/details/gtuhqncrmh.html

[Q86] 读取 JSON 字段
来源：http://dali.vqdsnc.cn/Article/details/gtwmuvweyy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkwbdlmp.html

[Q87] JSON 字段做条件
来源：http://dali.shzxlz.cn/Article/details/gtiszxkifd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinqigufen.top/Article/details/gtwovoxftd.html

[Q88] 行转列（条件聚合）
来源：http://dali.sxryk.cn/Article/details/gtlsoivdax.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gaohongyu789.top/Article/details/gtibrmecin.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nwbrower.top/Article/details/gtpsusovun.html

[Q89] 判断表是否存在
来源：http://dali.dashuyun.cn/Article/details/gtmtlirgwn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xinyue.icu/Article/details/gttkidunqe.html

[Q90] 生成序号列
来源：http://dali.shangyingyoupin.top/Article/details/gtgmhegiuq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.guannengcc.top/Article/details/gtbhqsyhlu.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtlpdbepaz.html

R. Bash 专题
来源：http://dali.vqdsnc.cn/Article/details/gtwubimmsz.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtmmcujdml.html

[R01] shebang 与严格模式
来源：http://dali.snrcjt.cn/Article/details/gtstfstjun.html

#!/usr/bin/env bash
来源：http://dali.sweek.top/Article/details/gticspipxv.html

set -euo pipefail
来源：http://dali.shuidangran.top/Article/details/gtncshocmr.html

[R02] 变量赋值与使用
来源：http://dali.vqdsnc.cn/Article/details/gtlyiqylrh.html

name="Tom"; echo "$name"
来源：http://dali.yj20258888.top/Article/details/gtignqpibl.html

[R03] 只读变量
来源：http://dali.fzhhl.top/Article/details/gtqostodjo.html

readonly PI=3.14
来源：http://dali.nanxuanxn.top/Article/details/gteasfutlc.html

[R04] 位置参数
来源：http://dali.snrcjt.cn/Article/details/gtlbnrguxm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shangyingyoupin.top/Article/details/gtfockauhz.html

[R05] 参数默认值
来源：http://dali.guannengcc.top/Article/details/gttkpidylh.html

name="${1:-default}"
来源：http://dali.tianlin.xyz/Article/details/gtpfvnbabx.html

[R06] 判断命令是否存在
来源：http://dali.shzxlz.cn/Article/details/gtfpgecokg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yanxiufei.cn/Article/details/gtzpcrmxyp.html

[R07] if 判断文件
来源：http://dali.pengpengdd.cyou/Article/details/gtquscwcjf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sxryk.cn/Article/details/gtvvqgbehm.html

[R08] 数值比较
来源：http://dali.guowangkeji.top/Article/details/gtmmgivtma.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hammf.cn/Article/details/gtssrmfueq.html

[R09] 字符串比较
来源：http://dali.svipenyu.cn/Article/details/gttgvbwoeu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtgsurgcwv.html

[R10] 正则匹配
来源：http://dali.hysaishi.cn/Article/details/gtfjekbtva.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.mhx1999.top/Article/details/gtjzvhpsyp.html

[R11] case 多分支
来源：http://dali.ybcxt.top/Article/details/gthwlrbdaa.html

case "$1" in
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijyffsyv.html

start) echo "启动" ;;
来源：http://dali.ehwqpu.com/Article/details/gthvbjmvfb.html

stop)  echo "停止" ;;
来源：http://dali.cucudq.cn/Article/details/gtjiluucam.html

*)     echo "未知命令" ;;
来源：http://dali.chenzaomai.com/Article/details/gtvgbontpt.html

esac
来源：http://dali.yj202588.top/Article/details/gttmwcbrwy.html

[R12] for 遍历文件
来源：http://dali.smart0.xyz/Article/details/gtchcwuhhg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.c1oappe.top/Article/details/gttnnalnez.html

[R13] for 计数循环
来源：http://dali.9152youxi.cn/Article/details/gtwcxuizam.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gtbttosfra.html

[R14] C 风格 for
来源：http://dali.zhongyouzk.top/Article/details/gtharghifn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gtifslwbxw.html

[R15] while 逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtljbxvyjs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cashguo.top/Article/details/gtupgfzkvf.html

[R16] until 等待条件
来源：http://dali.yuxming.cn/Article/details/gtgxbhkurc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.smart0.xyz/Article/details/gttnarmiqp.html

[R17] 数组定义与取值
来源：http://dali.ybcxt.top/Article/details/gtehctfths.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.birdmap.top/Article/details/gtakquzmtv.html

[R18] 遍历数组
来源：http://dali.cheryme.top/Article/details/gtohasgmrs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.fzhhl.top/Article/details/gtpsyczivd.html

[R19] 数组长度
来源：http://dali.zhongyouzk.top/Article/details/gtqawzmuzu.html

echo "${#arr[@]}"
来源：http://dali.shuidangran.top/Article/details/gtitssmnxz.html

[R20] 关联数组（字典）
来源：http://dali.jianghu66.top/Article/details/gtghmsjwvn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hfpthk.cn/Article/details/gtvvqwmuod.html

[R21] 字符串长度
来源：http://dali.zhengqikj.top/Article/details/gtsdopomvt.html

echo "${#s}"
来源：http://dali.ehwqpu.com/Article/details/gtxbqhgjxo.html

[R22] 截取子串
来源：http://dali.cucudq.cn/Article/details/gtfyjcsxlp.html

echo "${s:0:5}"
来源：http://dali.wangshuangyany.cn/Article/details/gtltdqlbme.html

[R23] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gtpatkmhev.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbxhcvjyg.html

[R24] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gtyiiseney.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cucudq.cn/Article/details/gttbxcqfof.html

[R25] 去后缀 / 去前缀
来源：http://dali.tanke756.top/Article/details/gtebsxjjji.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgufenzy.top/Article/details/gtmbwesiib.html

[R26] 命令替换
来源：http://dali.meibo888.top/Article/details/gtoeiiydwb.html

now=$(date +%F); echo "$now"
来源：http://dali.guannengcc.top/Article/details/gtdmvilzrm.html

[R27] 算术展开
来源：http://dali.xinyue.icu/Article/details/gtgmihzlzp.html

echo $((1 + 2 * 3))
来源：http://dali.hywenlv.cn/Article/details/gtcfknykcl.html

[R28] 浮点运算
来源：http://dali.pengpengdd.cyou/Article/details/gtdlnpbcuw.html

echo "scale=2; 10/3" | bc
来源：http://dali.mhx1999.top/Article/details/gtrxprofak.html

[R29] 定义函数
来源：http://dali.gotoacloud.top/Article/details/gtoswdvekq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmesfobaf.html

[R30] 函数返回状态码
来源：http://dali.gogol.net.cn/Article/details/gtskivafza.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shuidangran.top/Article/details/gtqayvfrml.html

[R31] 局部变量
来源：http://dali.cdnleiting.top/Article/details/gtghlbgcux.html

f() { local x=1; echo "$x"; }
来源：http://dali.xuanzx.com/Article/details/gttvqluuyr.html

[R32] 参数个数校验
来源：http://dali.daxiang520.top/Article/details/gtxztgqyfa.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.daxiang520.top/Article/details/gtzbyudhgx.html

[R33] 捕获错误并提示行号
来源：http://dali.chenlongwang.top/Article/details/gtzrjnncrb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.kuanghao11.cn/Article/details/gtoewayrej.html

[R34] 退出时清理
来源：http://dali.jlsjyb.cn/Article/details/gtlqjubild.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gtdbuvvvmn.html

[R35] 后台执行并等待
来源：http://dali.hywenlv.cn/Article/details/gtwooikbzq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdyuqdon.html

[R36] 并发执行多个任务
来源：http://dali.guannengcc.top/Article/details/gtgvmkaajd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zdqjudy.top/Article/details/gtqnpgyqel.html

[R37] 把输出赋给变量
来源：http://dali.zhixingplan.top/Article/details/gtnxdwzcga.html

files=$(ls -1)
来源：http://dali.0kj1m.cn/Article/details/gttwadolrr.html

[R38] 管道串联
来源：http://dali.kuanghao11.cn/Article/details/gtyrjnpqgb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hammf.cn/Article/details/gtyltxkajk.html

[R39] 重定向标准输出与错误
来源：http://dali.jiagoushi.top/Article/details/gtlsjnhgng.html

cmd > out.log 2>&1
来源：http://dali.smart0.xyz/Article/details/gtogyqihvr.html

[R40] 追加写日志
来源：http://dali.smart0.xyz/Article/details/gtgginhani.html

echo "log" >> out.log
来源：http://dali.aibaodan.cn/Article/details/gtwurzoaaa.html

[R41] 丢弃输出
来源：http://dali.hysaishi.cn/Article/details/gtnsahbkhx.html

cmd >/dev/null 2>&1
来源：http://dali.yuxming.cn/Article/details/gtinkjiwyw.html

[R42] 输入重定向
来源：http://dali.hywenlv.cn/Article/details/gtmdpqrdtq.html

wc -l < a.txt
来源：http://dali.gogol.net.cn/Article/details/gtadnuiwic.html

[R43] 按名字查找文件
来源：http://dali.zhongyouzk.top/Article/details/gtzscxfexz.html

find . -name "*.log" -type f
来源：http://dali.pengpengdd.cyou/Article/details/gtkxitbfix.html

[R44] 按修改时间查找
来源：http://dali.tianlin.xyz/Article/details/gtcgymeagw.html

find . -mtime -7 -type f
来源：http://dali.wangdashe.top/Article/details/gtbwwyrvvu.html

[R45] 批量删除
来源：http://dali.yj202588.top/Article/details/gtgrmgwwkd.html

find . -name "*.tmp" -delete
来源：http://dali.cqqwz.cn/Article/details/gteehyxgxn.html

[R46] 递归替换文件内容
来源：http://dali.cqqwz.cn/Article/details/gtfbufowuw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.smart0.xyz/Article/details/gtamejofzr.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtdlunhgmg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jqgfzy.top/Article/details/gtnbtvuryb.html

[R48] awk 取指定列
来源：http://dali.cashguo.top/Article/details/gtxqjcuetm.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtshoyfchq.html

[R49] awk 带条件
来源：http://dali.guowangkeji.top/Article/details/gtmkusqtvj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxkhafad.html

[R50] awk 求和
来源：http://dali.xziqi.cn/Article/details/gtxbpmpndq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pycfn.com/Article/details/gtrahzxqle.html

[R51] 排序去重取前几
来源：http://dali.cdnleiting.top/Article/details/gtdvqawpci.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenzaomai.com/Article/details/gtwitgbvgi.html

[R52] 统计行数
来源：http://dali.xziqi.cn/Article/details/gtnohfbewm.html

wc -l a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtedfrtxoq.html

[R53] 查看文件头与实时尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhoejkfd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.andypj.xyz/Article/details/gtiwcpgqdo.html

[R54] 比较两个文件
来源：http://dali.zhoulong.xyz/Article/details/gtquzkpvyb.html

diff a.txt b.txt
来源：http://dali.zhongyouzk.top/Article/details/gtlygwwgor.html

[R55] 压缩与解压
来源：http://dali.hfpthk.cn/Article/details/gtiauimyue.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jianghu66.top/Article/details/gtvzlozqtq.html

[R56] 远程拷贝
来源：http://dali.ivvv.top/Article/details/gtmqvvhoqy.html

scp file user@host:/path/
来源：http://dali.wangshuangyany.cn/Article/details/gtpndpplcs.html

[R57] 远程执行命令
来源：http://dali.hfpthk.cn/Article/details/gtucxujybg.html


<!-- 参考信息 -->