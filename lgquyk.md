代发 wailian999

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtasuaqhrr.html

[Q07] 删除表
来源：http://dali.yvedp.cn/Article/details/gthmutrsbd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xinyue.icu/Article/details/gtdshejwat.html

[Q08] 创建普通索引
来源：http://dali.gogol.net.cn/Article/details/gttdpulfcb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.iojbl.cn/Article/details/gtqvmkfhqq.html

[Q09] 创建唯一索引
来源：http://dali.nwbrower.top/Article/details/gtbbbcnqjb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.mhx1999.top/Article/details/gtqzqgbmiz.html

[Q10] 插入单行
来源：http://dali.yongpay.top/Article/details/gtgcmvsogo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.aizwys.cn/Article/details/gtcshzckuc.html

[Q11] 一次插入多行
来源：http://dali.yueranfly.top/Article/details/gtklztegpa.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cqqwz.cn/Article/details/gtetojuwsi.html

[Q12] 插入后取自增 ID
来源：http://dali.gotoacloud.top/Article/details/gtrbhrqnon.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.0kj1m.cn/Article/details/gtllinkmal.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hfpthk.cn/Article/details/gtgbhypmqb.html

[Q13] 忽略重复插入
来源：http://dali.jinqigufen.top/Article/details/gttytbxsbs.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gtreekmiux.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenlongwang.top/Article/details/gtnncghunp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.wangshuangyany.cn/Article/details/gtixczofof.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenjidiqi.icu/Article/details/gttqapbqwf.html

[Q15] 查询全部
来源：http://dali.vqdsnc.cn/Article/details/gtwoehirpk.html

SELECT * FROM users;
来源：http://dali.havefunace.top/Article/details/gtsjqmewxp.html

[Q16] 查询指定列
来源：http://dali.hammf.cn/Article/details/gthqnwqsic.html

SELECT id, name FROM users;
来源：http://dali.mhx1999.top/Article/details/gtsmbeeakg.html

[Q17] 条件查询
来源：http://dali.guannengcc.top/Article/details/gtydetrfgi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj202588.top/Article/details/gtmsjkxmjx.html

[Q18] 模糊匹配
来源：http://dali.sufxvd.cn/Article/details/gtejtgulgj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhaomingkeji.xyz/Article/details/gttyyhorxh.html

[Q19] 范围查询
来源：http://dali.xinyue.icu/Article/details/gtbqjsdbpt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hywenlv.cn/Article/details/gtkbmlwtfr.html

[Q20] IN 列表
来源：http://dali.yuxming.cn/Article/details/gtzykrwgcu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.kuanghao11.cn/Article/details/gtbqxhorxq.html

[Q21] 空值判断
来源：http://dali.zhiwuduotai.top/Article/details/gtbyoqebhh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.bjfxy.top/Article/details/gtrgwonqlu.html

[Q22] 排序
来源：http://dali.jyoumei.cn/Article/details/gtueswgchy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cdnleiting.top/Article/details/gtnlcgcbke.html

[Q23] 分页
来源：http://dali.hfpthk.cn/Article/details/gtwbgfhrek.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.0kj1m.cn/Article/details/gtwehcyjax.html

[Q24] 去重
来源：http://dali.zdqjudy.top/Article/details/gtqlmlgteu.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtahzvrgcu.html

[Q25] 只取前 N 条
来源：http://dali.haohaochexian.top/Article/details/gtrunjvkmv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hywenlv.cn/Article/details/gthmzyiktj.html

[Q26] 计数
来源：http://dali.xuanzx.com/Article/details/gtklpsgupu.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gthdvksgpx.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gtqakomkng.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtrupdcnml.html

[Q28] 求和与平均
来源：http://dali.daxiang520.top/Article/details/gtddcfzkmz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtqlgcbvji.html

[Q29] 最大最小值
来源：http://dali.andypj.xyz/Article/details/gtjobhlbee.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtkixpedib.html

[Q30] 分组统计
来源：http://dali.xuetiantiany.cn/Article/details/gtmcrnhiua.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gtmaidgpau.html

[Q31] 分组后过滤
来源：http://dali.hywenlv.cn/Article/details/gtucqixpjm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.snrcjt.cn/Article/details/gtaifqpbtb.html

[Q32] 分组拼接字符串
来源：http://dali.yj202588.top/Article/details/gtimxjvyyt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gtxoifkgrb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shanyushiyangtech.top/Article/details/gtoyvtvhdj.html

[Q33] 多列分组
来源：http://dali.sxryk.cn/Article/details/gtkzvljiwj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yuanzhike.top/Article/details/gtbktwyinv.html

[Q34] 每组取第一条
来源：http://dali.c1oappe.top/Article/details/gtsdrqkupy.html

SELECT * FROM (
来源：http://dali.kuanghao11.cn/Article/details/gtjmrsfkxg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hongshengwenyu.top/Article/details/gtfguamysp.html

) t WHERE rn = 1;
来源：http://dali.fengsongda.top/Article/details/gtcyktxilq.html

[Q35] 内连接
来源：http://dali.guannengcc.top/Article/details/gtrkopitcf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gtoskxpahf.html

[Q36] 左连接
来源：http://dali.ydzc1.top/Article/details/gtqejbvfyi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jianghu66.top/Article/details/gtvxnbittb.html

[Q37] 右连接
来源：http://dali.guowangkeji.top/Article/details/gthqotkwep.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sufxvd.cn/Article/details/gtxhzwhiqt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yueranfly.top/Article/details/gtnqmvftxe.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jianghu66.top/Article/details/gtitdsizgv.html

[Q39] 自连接（查上下级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbcflqqhh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxinkj.top/Article/details/gtrqqtajfk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xuanzx.com/Article/details/gtiavzwcpf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoequfith.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tianlin.xyz/Article/details/gtdwwmhtmj.html

[Q41] 多表连接
来源：http://dali.feifeiyinyue.top/Article/details/gtpywcbrrh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.svipenyu.cn/Article/details/gtkvqwrcbt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jianghu66.top/Article/details/gtnvgjfxqh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.haohaochexian.top/Article/details/gtslmajpwf.html

[Q42] 连接条件附加过滤
来源：http://dali.c1oappe.top/Article/details/gtttcsnlna.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhengqikj.top/Article/details/gtncrccrqh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cheryme.top/Article/details/gtahfjgfmt.html

[Q43] 标量子查询
来源：http://dali.cashguo.top/Article/details/gtxlobwtcz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aizwys.cn/Article/details/gtnefusrdf.html

[Q44] IN 子查询
来源：http://dali.zycfv.cn/Article/details/gtbmajndcz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.316326.xyz/Article/details/gteswjdhpn.html

[Q45] EXISTS 判断存在
来源：http://dali.dianchejie.cn/Article/details/gtdfnsrlqm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cdnleiting.top/Article/details/gtwleojqic.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhiwuduotai.top/Article/details/gtrqhngoxa.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ppjwa.cn/Article/details/gtmsxaagpr.html

[Q47] 与平均值比较
来源：http://dali.bjfxy.top/Article/details/gtkfgpnutx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jyoumei.cn/Article/details/gtwcnjcwhi.html

[Q48] CTE 公用表表达式
来源：http://dali.zhongyouzk.top/Article/details/gttmpgnfdo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yanxiufei.cn/Article/details/gtllofxfni.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shangyingyoupin.top/Article/details/gtzbjqxddi.html

[Q49] 更新单行
来源：http://dali.redwolf501.top/Article/details/gtuqpukxbu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aizwys.cn/Article/details/gtsklqbazy.html

[Q50] 批量更新
来源：http://dali.yangfankeji.com/Article/details/gtyduqdllv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yonumen.top/Article/details/gtddahnkxj.html

[Q51] 用子查询更新
来源：http://dali.cdnleiting.top/Article/details/gtzxeybufr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shzxlz.cn/Article/details/gthqlqvsuf.html

[Q52] 删除指定行
来源：http://dali.guowangkeji.top/Article/details/gtwhjwxucq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gtmmtopqrt.html

[Q53] 按条件删除
来源：http://dali.zhongyouzk.top/Article/details/gtlrehvxiw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xinyue.icu/Article/details/gtghvgbnqd.html

[Q54] 清空表
来源：http://dali.gaohongyu789.top/Article/details/gtjnnysxda.html

TRUNCATE TABLE logs;
来源：http://dali.dianchejie.cn/Article/details/gtxzvcvsdg.html

[Q55] 排名（并列占位）
来源：http://dali.daria6918.cn/Article/details/gtvadgprmp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.wangdashe.top/Article/details/gtbufgqshl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ivvv.top/Article/details/gtakopklqa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gtvvlkikmj.html

[Q57] 行号
来源：http://dali.jqgfzy.top/Article/details/gthjmgnzwm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.birdmap.top/Article/details/gthztcmdno.html

[Q58] 累计求和
来源：http://dali.shzxlz.cn/Article/details/gtdpwcbwiy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtcnzdisgm.html

[Q59] 分组内累计
来源：http://dali.zdqjudy.top/Article/details/gtrnnhyqdx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtievcsszb.html

[Q60] 取上一行 / 下一行
来源：http://dali.wangdashe.top/Article/details/gtacgqhuqy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj20258.top/Article/details/gtinrrvabb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtskjmhiwe.html

[Q61] 移动平均
来源：http://dali.yonumen.top/Article/details/gtrmmeczqy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowoahmqb.html

[Q62] 分组占比
来源：http://dali.yangfankeji.com/Article/details/gtbpfumtkl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gttzlhqfwp.html

[Q63] 开启事务
来源：http://dali.yuxming.cn/Article/details/gtweykemcg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.aizwys.cn/Article/details/gtwtxzhfrs.html

[Q64] 提交事务
来源：http://dali.tanke756.top/Article/details/gtufcrqahq.html

COMMIT;
来源：http://dali.smart0.xyz/Article/details/gtxmxmzgoy.html

[Q65] 回滚事务
来源：http://dali.birdmap.top/Article/details/gtonqrpyei.html

ROLLBACK;
来源：http://dali.cqqwz.cn/Article/details/gtdagavayg.html

[Q66] 行锁查询
来源：http://dali.gogol.net.cn/Article/details/gtqwtygyza.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuanzhike.top/Article/details/gtkjclzscd.html

[Q67] 设置隔离级别
来源：http://dali.shuidangran.top/Article/details/gtqoqbbjuw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yvedp.cn/Article/details/gttesiawdz.html

[Q68] 保存点
来源：http://dali.xylfe.cn/Article/details/gtdbdqvvuq.html

SAVEPOINT sp1;
来源：http://dali.yj20258.top/Article/details/gtkesibeke.html

ROLLBACK TO sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gttxjpvxig.html

[Q69] 查看执行计划
来源：http://dali.ehwqpu.com/Article/details/gthxsygsrh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.andypj.xyz/Article/details/gtvsfibqge.html

[Q70] 更新统计信息
来源：http://dali.zhiwuduotai.top/Article/details/gtylhqegow.html

ANALYZE TABLE users;
来源：http://dali.hammf.cn/Article/details/gtkndtrqoa.html

[Q71] 查看建表语句
来源：http://dali.zhengqikj.top/Article/details/gtfgibyvfc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yueranfly.top/Article/details/gthauezzev.html

[Q72] 查看索引
来源：http://dali.ivvv.top/Article/details/gtkvhrtego.html

SHOW INDEX FROM users;
来源：http://dali.zdqjudy.top/Article/details/gttplgwhcm.html

[Q73] 查看表状态
来源：http://dali.pengpengdd.cyou/Article/details/gtccsrkmfc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nanxinkj.top/Article/details/gtnbbdljlq.html

[Q74] 强制使用索引
来源：http://dali.tianlin.xyz/Article/details/gtbkmqzvcl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.9152youxi.cn/Article/details/gtxrtfzxhe.html

[Q75] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gtyqjetfff.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtcneypkcs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zycfv.cn/Article/details/gtyaonjtvg.html

[Q76] 按天统计
来源：http://dali.smart0.xyz/Article/details/gtrrugjdws.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhoulong.xyz/Article/details/gtlykgmjsf.html

[Q77] 时间加减
来源：http://dali.zhiwuduotai.top/Article/details/gtwzzyjrkw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj20258.top/Article/details/gtpseeuwey.html

[Q78] 当前时间
来源：http://dali.xinyue.icu/Article/details/gtumzvjndi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sufxvd.cn/Article/details/gthhvhbgxi.html

[Q79] 字符串拼接
来源：http://dali.jiagoushi.top/Article/details/gtfisrhnre.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xylfe.cn/Article/details/gthykfcunr.html

[Q80] 字符串截取
来源：http://dali.iojbl.cn/Article/details/gtrruereat.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jianghu66.top/Article/details/gteazorpbg.html

[Q81] 字符串替换
来源：http://dali.ivvv.top/Article/details/gtpgjpydgo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zycfv.cn/Article/details/gtuzkuyxqh.html

[Q82] 字符长度与字节长度
来源：http://dali.yuanzhike.top/Article/details/gtiqzxqvfo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtvrnrthad.html

[Q83] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gtjicmqqhb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtlppjahij.html

[Q84] 去除首尾空格
来源：http://dali.ydzc1.top/Article/details/gtcffuawpd.html

SELECT TRIM(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtzsiuvyvn.html

[Q85] 数值取整
来源：http://dali.fzhhl.top/Article/details/gtucqeomaq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ydzc1.top/Article/details/gtaklejgve.html

[Q86] 读取 JSON 字段
来源：http://dali.dashuyun.cn/Article/details/gtmlegvzmg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenjidiqi.icu/Article/details/gtkmshovkp.html

[Q87] JSON 字段做条件
来源：http://dali.svipenyu.cn/Article/details/gttuhwxfbw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nwbrower.top/Article/details/gtpjozwyza.html

[Q88] 行转列（条件聚合）
来源：http://dali.ehwqpu.com/Article/details/gtwannqpop.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.feifeiyinyue.top/Article/details/gtrjjzpffl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtpvizukky.html

[Q89] 判断表是否存在
来源：http://dali.zycfv.cn/Article/details/gtirrngghv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hongshengwenyu.top/Article/details/gtcqdpevio.html

[Q90] 生成序号列
来源：http://dali.chenzaomai.com/Article/details/gtvlhcrgvt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj20258.top/Article/details/gtrkychxxf.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtmuocqotx.html

R. Bash 专题
来源：http://dali.zdqjudy.top/Article/details/gtcuzyigkc.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtazfvajtt.html

[R01] shebang 与严格模式
来源：http://dali.jinghuilouyu.cn/Article/details/gtowixhcpr.html

#!/usr/bin/env bash
来源：http://dali.nanxinkj.top/Article/details/gtcsfecfub.html

set -euo pipefail
来源：http://dali.smart0.xyz/Article/details/gtmppxojmo.html

[R02] 变量赋值与使用
来源：http://dali.yj202588.top/Article/details/gtichkhjgo.html

name="Tom"; echo "$name"
来源：http://dali.yueranfly.top/Article/details/gtqmfvunqj.html

[R03] 只读变量
来源：http://dali.cheryme.top/Article/details/gtwdtdjahd.html

readonly PI=3.14
来源：http://dali.daxiang520.top/Article/details/gthctgsdcj.html

[R04] 位置参数
来源：http://dali.sufxvd.cn/Article/details/gtlqxtlnyw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gotoacloud.top/Article/details/gtebsoirfh.html

[R05] 参数默认值
来源：http://dali.gzhubu.top/Article/details/gtlbjaqxfu.html

name="${1:-default}"
来源：http://dali.yj20258888.top/Article/details/gttofahabn.html

[R06] 判断命令是否存在
来源：http://dali.cheryme.top/Article/details/gttymojjni.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvomrlbzw.html

[R07] if 判断文件
来源：http://dali.havefunace.top/Article/details/gtypnnntws.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.meibo888.top/Article/details/gtfmlvmfht.html

[R08] 数值比较
来源：http://dali.cheryme.top/Article/details/gtayvrdsgu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sweek.top/Article/details/gtomhpxzoc.html

[R09] 字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gtbdaudvlo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.haohaochexian.top/Article/details/gtdgetynkq.html

[R10] 正则匹配
来源：http://dali.nanxuanxn.top/Article/details/gtvepnokdr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yueranfly.top/Article/details/gtjwejihuo.html

[R11] case 多分支
来源：http://dali.quarkkingdee.top/Article/details/gtuphhozmp.html

case "$1" in
来源：http://dali.jyoumei.cn/Article/details/gtcnjgveca.html

start) echo "启动" ;;
来源：http://dali.vqdsnc.cn/Article/details/gtllzpxjzp.html

stop)  echo "停止" ;;
来源：http://dali.quarkkingdee.top/Article/details/gtuicytaeu.html

*)     echo "未知命令" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gthjivdfts.html

esac
来源：http://dali.yangfankeji.com/Article/details/gtkycctpmm.html

[R12] for 遍历文件
来源：http://dali.fengsongda.top/Article/details/gtwvifimvm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guannengcc.top/Article/details/gtrzymersw.html

[R13] for 计数循环
来源：http://dali.dianchejie.cn/Article/details/gtkslsuywl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gtbniowfyc.html

[R14] C 风格 for
来源：http://dali.hammf.cn/Article/details/gtgxyzudys.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tianlin.xyz/Article/details/gtqncrxsnh.html

[R15] while 逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdxewiix.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xinyue.icu/Article/details/gtvennowtw.html

[R16] until 等待条件
来源：http://dali.daria6918.cn/Article/details/gtohnoytpx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gtstljthmt.html

[R17] 数组定义与取值
来源：http://dali.yangfankeji.com/Article/details/gtbjjreqnx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nanxinkj.top/Article/details/gtqybgyjxw.html

[R18] 遍历数组
来源：http://dali.c1oappe.top/Article/details/gtdnvfzsiv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.mhx1999.top/Article/details/gtmhdclpqv.html

[R19] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gtwbletqdn.html

echo "${#arr[@]}"
来源：http://dali.sysykeji.top/Article/details/gtutjtlshw.html

[R20] 关联数组（字典）
来源：http://dali.ppjwa.cn/Article/details/gtjirntpuh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jianghu66.top/Article/details/gtqusskghx.html

[R21] 字符串长度
来源：http://dali.hnqzz.top/Article/details/gtwswmlchz.html

echo "${#s}"
来源：http://dali.haohaochexian.top/Article/details/gtihalczph.html

[R22] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gttvtgiybp.html

echo "${s:0:5}"
来源：http://dali.wangshuangyany.cn/Article/details/gtrhdbdizh.html

[R23] 字符串替换
来源：http://dali.sweek.top/Article/details/gtpwyjfjey.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuxming.cn/Article/details/gtjygjmnng.html

[R24] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gtoazychdb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.andypj.xyz/Article/details/gtfbflolyl.html

[R25] 去后缀 / 去前缀
来源：http://dali.zycfv.cn/Article/details/gtedqfxfff.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.0kj1m.cn/Article/details/gtmmxurjxh.html

[R26] 命令替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpgyhylo.html

now=$(date +%F); echo "$now"
来源：http://dali.sufxvd.cn/Article/details/gtowsczsiz.html

[R27] 算术展开
来源：http://dali.c1oappe.top/Article/details/gtiskxkgeh.html

echo $((1 + 2 * 3))
来源：http://dali.aizwys.cn/Article/details/gtrkbkclrc.html

[R28] 浮点运算
来源：http://dali.dianchejie.cn/Article/details/gtxwqlyqyn.html

echo "scale=2; 10/3" | bc
来源：http://dali.bjfxy.top/Article/details/gtfvzyyymf.html

[R29] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gtaiwbflch.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.feifeiyinyue.top/Article/details/gtqrvqpixt.html

[R30] 函数返回状态码
来源：http://dali.quarkkingdee.top/Article/details/gtzqtjtdrg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.snrcjt.cn/Article/details/gtgjpsiqfr.html

[R31] 局部变量
来源：http://dali.zdqjudy.top/Article/details/gtgnajgiqm.html

f() { local x=1; echo "$x"; }
来源：http://dali.yangfankeji.com/Article/details/gtyctxxvyg.html

[R32] 参数个数校验
来源：http://dali.zhixingplan.top/Article/details/gtwnssujmn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yueranfly.top/Article/details/gtxeqvgyhh.html

[R33] 捕获错误并提示行号
来源：http://dali.cqqwz.cn/Article/details/gtpggthrrz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jqgfzy.top/Article/details/gtgtcqllkk.html

[R34] 退出时清理
来源：http://dali.chenzaomai.com/Article/details/gtxoogjcpy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhongyouzk.top/Article/details/gtpbbcigvn.html

[R35] 后台执行并等待
来源：http://dali.kuanghao11.cn/Article/details/gtyctyplwq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.fzhhl.top/Article/details/gtbvsnhwfr.html

[R36] 并发执行多个任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxgmydmw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.bjfxy.top/Article/details/gtfimmwfjg.html

[R37] 把输出赋给变量
来源：http://dali.cqqwz.cn/Article/details/gtcetzgmog.html

files=$(ls -1)
来源：http://dali.xuetiantiany.cn/Article/details/gtfelifwop.html

[R38] 管道串联
来源：http://dali.yj202588.top/Article/details/gtfjbevmfr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigfzy.top/Article/details/gtuivoolqm.html

[R39] 重定向标准输出与错误
来源：http://dali.wangshuangyany.cn/Article/details/gtivdxbtut.html

cmd > out.log 2>&1
来源：http://dali.daria6918.cn/Article/details/gtiqjgcmwo.html

[R40] 追加写日志
来源：http://dali.guannengcc.top/Article/details/gtblzxjpmi.html

echo "log" >> out.log
来源：http://dali.jlsjyb.cn/Article/details/gtwqlntgsj.html

[R41] 丢弃输出
来源：http://dali.smart0.xyz/Article/details/gtfwxlforo.html

cmd >/dev/null 2>&1
来源：http://dali.jqgfzy.top/Article/details/gtpsguvqcc.html

[R42] 输入重定向
来源：http://dali.iojbl.cn/Article/details/gtkujpcqdt.html

wc -l < a.txt
来源：http://dali.daxiang520.top/Article/details/gtmprdsemg.html

[R43] 按名字查找文件
来源：http://dali.hfpthk.cn/Article/details/gtatdnywsf.html

find . -name "*.log" -type f
来源：http://dali.xinyue.icu/Article/details/gttfsriwfd.html

[R44] 按修改时间查找
来源：http://dali.pycfn.com/Article/details/gtcbcisctp.html

find . -mtime -7 -type f
来源：http://dali.chenlongwang.top/Article/details/gtgbfjgqiv.html

[R45] 批量删除
来源：http://dali.zhongyouzk.top/Article/details/gtkrluvdsj.html

find . -name "*.tmp" -delete
来源：http://dali.xziqi.cn/Article/details/gtsrmrokbq.html

[R46] 递归替换文件内容
来源：http://dali.zhiwuduotai.top/Article/details/gtszniphnh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhiwuduotai.top/Article/details/gteapyakvh.html

[R47] sed 单行替换
来源：http://dali.quarkkingdee.top/Article/details/gtzlcmrmty.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gticjonzxe.html

[R48] awk 取指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkhfjcch.html

awk '{print $1, $3}' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlijhryl.html

[R49] awk 带条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjfsezdc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.pengpengdd.cyou/Article/details/gtyzstvyjn.html

[R50] awk 求和
来源：http://dali.vqdsnc.cn/Article/details/gtqddqpgfh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtzofdlofd.html

[R51] 排序去重取前几
来源：http://dali.yonumen.top/Article/details/gtrxjkoiaj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgufenzy.top/Article/details/gtshecszxb.html

[R52] 统计行数
来源：http://dali.316326.xyz/Article/details/gtcwmcxgul.html

wc -l a.txt
来源：http://dali.sufxvd.cn/Article/details/gtotjvdyij.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlglyhmu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.kuanghao11.cn/Article/details/gtwmwyhkbg.html

[R54] 比较两个文件
来源：http://dali.cdnleiting.top/Article/details/gtcreuneuy.html

diff a.txt b.txt
来源：http://dali.quarkkingdee.top/Article/details/gtdxccgfxj.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gtkqhrsmuv.html


<!-- 参考信息 -->