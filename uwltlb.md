代发 wailian999

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gzhubu.top/Article/details/gtvtkubemb.html

[Q11] 一次插入多行
来源：http://dali.fzhhl.top/Article/details/gtljoelzit.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gtyvovtutv.html

[Q12] 插入后取自增 ID
来源：http://dali.xinyue.icu/Article/details/gtlzfkhame.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhiwuduotai.top/Article/details/gtvmojywws.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj20258888.top/Article/details/gtovaxtpet.html

[Q13] 忽略重复插入
来源：http://dali.tianlin.xyz/Article/details/gtaammldqi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cdnleiting.top/Article/details/gtsrcyfwse.html

[Q14] 存在则更新（upsert）
来源：http://dali.sysykeji.top/Article/details/gtzzxlrhij.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cqqwz.cn/Article/details/gthdxtpgqw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jiagoushi.top/Article/details/gtulkvfkmh.html

[Q15] 查询全部
来源：http://dali.fengsongda.top/Article/details/gtvrdrocyy.html

SELECT * FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtfgowgjbb.html

[Q16] 查询指定列
来源：http://dali.smart0.xyz/Article/details/gthzggfyzl.html

SELECT id, name FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtpemtcaig.html

[Q17] 条件查询
来源：http://dali.dashuyun.cn/Article/details/gthqsneffy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.smart0.xyz/Article/details/gtybhosfht.html

[Q18] 模糊匹配
来源：http://dali.jinqigufen.top/Article/details/gtahvtsqck.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yvedp.cn/Article/details/gttlaoagiz.html

[Q19] 范围查询
来源：http://dali.svipenyu.cn/Article/details/gtetheexju.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhongyouzk.top/Article/details/gtwxkdlyxl.html

[Q20] IN 列表
来源：http://dali.hongshengwenyu.top/Article/details/gtgewkjurw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskzoprbj.html

[Q21] 空值判断
来源：http://dali.cqqwz.cn/Article/details/gtyhnmuozy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shzxlz.cn/Article/details/gtmrjhwbhq.html

[Q22] 排序
来源：http://dali.fzhhl.top/Article/details/gtnfigkerz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shanyushiyangtech.top/Article/details/gtamndrtyy.html

[Q23] 分页
来源：http://dali.havefunace.top/Article/details/gtuyyuzdra.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xuanzx.com/Article/details/gtkmloztvq.html

[Q24] 去重
来源：http://dali.yangfankeji.com/Article/details/gthgwqeyow.html

SELECT DISTINCT city FROM users;
来源：http://dali.sxryk.cn/Article/details/gtdffgilbo.html

[Q25] 只取前 N 条
来源：http://dali.yuanzhike.top/Article/details/gtnauresiq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuxming.cn/Article/details/gtujwlcgkp.html

[Q26] 计数
来源：http://dali.smart0.xyz/Article/details/gtecwmplpg.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtksanutms.html

[Q27] 条件计数
来源：http://dali.mhx1999.top/Article/details/gtpjlelwjp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yonumen.top/Article/details/gtonnhukjb.html

[Q28] 求和与平均
来源：http://dali.hywenlv.cn/Article/details/gtszyjpztb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtbocmrwuw.html

[Q29] 最大最小值
来源：http://dali.jinghuilouyu.cn/Article/details/gtoarcwkwa.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtqxuvakoz.html

[Q30] 分组统计
来源：http://dali.ybcxt.top/Article/details/gtrghprvri.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtrmbuudtf.html

[Q31] 分组后过滤
来源：http://dali.guannengcc.top/Article/details/gtkdduqkce.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yangfankeji.com/Article/details/gtzshbqxcf.html

[Q32] 分组拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gtuubokyyq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gtcraoyddx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sweek.top/Article/details/gtmngqiazj.html

[Q33] 多列分组
来源：http://dali.andypj.xyz/Article/details/gtawlyvoip.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tanke756.top/Article/details/gtqobewdoe.html

[Q34] 每组取第一条
来源：http://dali.hnxiangtu.top/Article/details/gttqikbiwz.html

SELECT * FROM (
来源：http://dali.yvedp.cn/Article/details/gtvtclquei.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj20258.top/Article/details/gtgcfsaxxu.html

) t WHERE rn = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtizwcqmgs.html

[Q35] 内连接
来源：http://dali.hammf.cn/Article/details/gtilitvbys.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gtsypyulmu.html

[Q36] 左连接
来源：http://dali.andypj.xyz/Article/details/gtspxngptp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gogol.net.cn/Article/details/gtevkxagfq.html

[Q37] 右连接
来源：http://dali.ppjwa.cn/Article/details/gtdzrxslpf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cheryme.top/Article/details/gtgswexjlp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aibaodan.cn/Article/details/gtsjfravqu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gogol.net.cn/Article/details/gtcocqgbau.html

[Q39] 自连接（查上下级）
来源：http://dali.hfpthk.cn/Article/details/gtoslwrssn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xylfe.cn/Article/details/gtsrnjulki.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gaohongyu789.top/Article/details/gtjtmdhwye.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ybcxt.top/Article/details/gtnlnbynqg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenjidiqi.icu/Article/details/gtfaebefkt.html

[Q41] 多表连接
来源：http://dali.daxiang520.top/Article/details/gtwkoydlyh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nanxinkj.top/Article/details/gtmucvnqce.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gtezeaguyy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.iojbl.cn/Article/details/gtlswtybka.html

[Q42] 连接条件附加过滤
来源：http://dali.ppjwa.cn/Article/details/gtqizuwbse.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shangyingyoupin.top/Article/details/gtydutnvnp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhiwuduotai.top/Article/details/gtssjrvynh.html

[Q43] 标量子查询
来源：http://dali.daria6918.cn/Article/details/gtjqottrbf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgfzy.top/Article/details/gtwvpnhluf.html

[Q44] IN 子查询
来源：http://dali.smart0.xyz/Article/details/gtfylfbwds.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.0kj1m.cn/Article/details/gtgyyzapty.html

[Q45] EXISTS 判断存在
来源：http://dali.hfpthk.cn/Article/details/gtuqaxgntb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gtjlmdwtld.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.feifeiyinyue.top/Article/details/gtrlhiqydm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.vqdsnc.cn/Article/details/gthncmajdn.html

[Q47] 与平均值比较
来源：http://dali.aibaodan.cn/Article/details/gtjbokbcrj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gtxpujewoj.html

[Q48] CTE 公用表表达式
来源：http://dali.hnxiangtu.top/Article/details/gtitvwtyva.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aibaodan.cn/Article/details/gtzltpwgfm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigufen.top/Article/details/gtfmnrmvvv.html

[Q49] 更新单行
来源：http://dali.jlsjyb.cn/Article/details/gtmjyfffsx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aizwys.cn/Article/details/gtswmjmndt.html

[Q50] 批量更新
来源：http://dali.sweek.top/Article/details/gtyzevmfvv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aibaodan.cn/Article/details/gtedymzawd.html

[Q51] 用子查询更新
来源：http://dali.mhx1999.top/Article/details/gtkuwwyhbc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenzaomai.com/Article/details/gtkxbzfmyf.html

[Q52] 删除指定行
来源：http://dali.zdqjudy.top/Article/details/gtddfuarns.html

DELETE FROM users WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gtgwzsddmb.html

[Q53] 按条件删除
来源：http://dali.yangfankeji.com/Article/details/gttaryjgac.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shzxlz.cn/Article/details/gtegehfgsl.html

[Q54] 清空表
来源：http://dali.yj20258.top/Article/details/gtsyoydxer.html

TRUNCATE TABLE logs;
来源：http://dali.gaohongyu789.top/Article/details/gtgavnlkle.html

[Q55] 排名（并列占位）
来源：http://dali.sxryk.cn/Article/details/gtwtrucwcb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yangfankeji.com/Article/details/gtpfqsiwoy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.havefunace.top/Article/details/gtwvnvccmp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xziqi.cn/Article/details/gtwxbithan.html

[Q57] 行号
来源：http://dali.hfpthk.cn/Article/details/gtkjqgrsda.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nwbrower.top/Article/details/gtuqevsgeq.html

[Q58] 累计求和
来源：http://dali.yj202588.top/Article/details/gtorjcmkas.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtykulwgnt.html

[Q59] 分组内累计
来源：http://dali.tanke756.top/Article/details/gtwowljbmg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtbrumegkc.html

[Q60] 取上一行 / 下一行
来源：http://dali.shzxlz.cn/Article/details/gtjaqhbwzs.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbcrrmprh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cheryme.top/Article/details/gtndyprcuy.html

[Q61] 移动平均
来源：http://dali.vqdsnc.cn/Article/details/gtdexwpemb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtnaowktie.html

[Q62] 分组占比
来源：http://dali.yangfankeji.com/Article/details/gtqpxjwvnr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gtsihekktc.html

[Q63] 开启事务
来源：http://dali.zhiwuduotai.top/Article/details/gturuqkwbz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shuidangran.top/Article/details/gtrqqdalfq.html

[Q64] 提交事务
来源：http://dali.daxiang520.top/Article/details/gtvxgqsygh.html

COMMIT;
来源：http://dali.hnxiangtu.top/Article/details/gtoharbemf.html

[Q65] 回滚事务
来源：http://dali.nanxuanxn.top/Article/details/gtcvacmsnu.html

ROLLBACK;
来源：http://dali.daxiang520.top/Article/details/gtgjohdcyn.html

[Q66] 行锁查询
来源：http://dali.cashguo.top/Article/details/gtwolyuapc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cheryme.top/Article/details/gtasgqmxwe.html

[Q67] 设置隔离级别
来源：http://dali.shzxlz.cn/Article/details/gtfudklfjs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumbybtjw.html

[Q68] 保存点
来源：http://dali.hnqzz.top/Article/details/gtuzfjqcft.html

SAVEPOINT sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzobusyxm.html

ROLLBACK TO sp1;
来源：http://dali.hysaishi.cn/Article/details/gtrjpdovph.html

[Q69] 查看执行计划
来源：http://dali.tian-w.cn/Article/details/gtocatifsb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigfzy.top/Article/details/gtjfrlqnda.html

[Q70] 更新统计信息
来源：http://dali.pengpengdd.cyou/Article/details/gtkoabjzsc.html

ANALYZE TABLE users;
来源：http://dali.sweek.top/Article/details/gtvrifhtbn.html

[Q71] 查看建表语句
来源：http://dali.316326.xyz/Article/details/gtwtnxvjno.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shangyingyoupin.top/Article/details/gtkkwogono.html

[Q72] 查看索引
来源：http://dali.gzhubu.top/Article/details/gtjtzxoewl.html

SHOW INDEX FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtiyazxrgt.html

[Q73] 查看表状态
来源：http://dali.gotoacloud.top/Article/details/gtqsyktabk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldsqpzqs.html

[Q74] 强制使用索引
来源：http://dali.hnqzz.top/Article/details/gtbgqspflf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.c1oappe.top/Article/details/gtdzuethzl.html

[Q75] 日期格式化
来源：http://dali.chenzaomai.com/Article/details/gtoptgipes.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtbrhccqgm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.snrcjt.cn/Article/details/gterovdonf.html

[Q76] 按天统计
来源：http://dali.sufxvd.cn/Article/details/gtjdnycnkj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhengqikj.top/Article/details/gtcrhtdklg.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gtyblmqvek.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj20258888.top/Article/details/gtzbhqkgnp.html

[Q78] 当前时间
来源：http://dali.wangdashe.top/Article/details/gtuptaifhj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gzhubu.top/Article/details/gtansuixol.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gtoyvcbeez.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zycfv.cn/Article/details/gttlqcatxp.html

[Q80] 字符串截取
来源：http://dali.gogol.net.cn/Article/details/gtwkcfdeot.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtlxvbadyf.html

[Q81] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gtmsjslyrp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtcxehoaaz.html

[Q82] 字符长度与字节长度
来源：http://dali.xylfe.cn/Article/details/gtwvmvbiej.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtzozedtcv.html

[Q83] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gtelvtwbxu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtmtmfvafa.html

[Q84] 去除首尾空格
来源：http://dali.jiagoushi.top/Article/details/gtvuhvskge.html

SELECT TRIM(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtteruihfy.html

[Q85] 数值取整
来源：http://dali.birdmap.top/Article/details/gtlfyxiswo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.snrcjt.cn/Article/details/gtuatebwel.html

[Q86] 读取 JSON 字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmciegtv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shangyingyoupin.top/Article/details/gtlsncrekf.html

[Q87] JSON 字段做条件
来源：http://dali.yueranfly.top/Article/details/gtxtlvbjga.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gtkrapppmq.html

[Q88] 行转列（条件聚合）
来源：http://dali.ivvv.top/Article/details/gthidpiskt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cashguo.top/Article/details/gtwdwipomg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtltdkdooq.html

[Q89] 判断表是否存在
来源：http://dali.gotoacloud.top/Article/details/gtnboifgtw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yueranfly.top/Article/details/gtcelgftpp.html

[Q90] 生成序号列
来源：http://dali.ivvv.top/Article/details/gttbmygeck.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yuanzhike.top/Article/details/gtikyralem.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtgaocnbcx.html

R. Bash 专题
来源：http://dali.redwolf501.top/Article/details/gtycdxuday.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtarkysycc.html

[R01] shebang 与严格模式
来源：http://dali.haohaochexian.top/Article/details/gtyliizdxt.html

#!/usr/bin/env bash
来源：http://dali.svipenyu.cn/Article/details/gtiggyclfh.html

set -euo pipefail
来源：http://dali.dianchejie.cn/Article/details/gtxcgkpjti.html

[R02] 变量赋值与使用
来源：http://dali.cdnleiting.top/Article/details/gtrtsbzfeb.html

name="Tom"; echo "$name"
来源：http://dali.shzxlz.cn/Article/details/gtfdwidumb.html

[R03] 只读变量
来源：http://dali.jqgfzy.top/Article/details/gtxmouhddt.html

readonly PI=3.14
来源：http://dali.gzhubu.top/Article/details/gtihjprwqi.html

[R04] 位置参数
来源：http://dali.316326.xyz/Article/details/gtkplafmkw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.fengsongda.top/Article/details/gtswiilnjb.html

[R05] 参数默认值
来源：http://dali.zdqjudy.top/Article/details/gtstsqkyvh.html

name="${1:-default}"
来源：http://dali.havefunace.top/Article/details/gtfeblgdpy.html

[R06] 判断命令是否存在
来源：http://dali.meibo888.top/Article/details/gtinrwjhil.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ehwqpu.com/Article/details/gtmwquixqp.html

[R07] if 判断文件
来源：http://dali.shangyingyoupin.top/Article/details/gtsgwbryiv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtrmoqptvd.html

[R08] 数值比较
来源：http://dali.snrcjt.cn/Article/details/gtqcaenubq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.redwolf501.top/Article/details/gtttzlfnfm.html

[R09] 字符串比较
来源：http://dali.gotoacloud.top/Article/details/gtwtfjegdi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.9152youxi.cn/Article/details/gtbverzmvp.html

[R10] 正则匹配
来源：http://dali.yongpay.top/Article/details/gtkgxjoqkl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtefrqwbpd.html

[R11] case 多分支
来源：http://dali.cdnleiting.top/Article/details/gtpkiffgmo.html

case "$1" in
来源：http://dali.jianghu66.top/Article/details/gtmhemtlgg.html

start) echo "启动" ;;
来源：http://dali.sweek.top/Article/details/gtqauscmyv.html

stop)  echo "停止" ;;
来源：http://dali.zhongyouzk.top/Article/details/gtzszibxye.html

*)     echo "未知命令" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcynodsuk.html

esac
来源：http://dali.ppjwa.cn/Article/details/gtibqgfafy.html

[R12] for 遍历文件
来源：http://dali.gotoacloud.top/Article/details/gtcykuhfln.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sufxvd.cn/Article/details/gtlvbgxqba.html

[R13] for 计数循环
来源：http://dali.chenjidiqi.icu/Article/details/gtnkvkptfh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gtumsiyzmz.html

[R14] C 风格 for
来源：http://dali.cqqwz.cn/Article/details/gtvudwugyi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gtksyvyruw.html

[R15] while 逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtftmygugv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.iojbl.cn/Article/details/gtphhjzlnx.html

[R16] until 等待条件
来源：http://dali.316326.xyz/Article/details/gtdtybdshs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.smart0.xyz/Article/details/gtqiatsgrn.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gtfvfogqei.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pengpengdd.cyou/Article/details/gthprxaueh.html

[R18] 遍历数组
来源：http://dali.jinqigufen.top/Article/details/gtlxffvgzq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yangfankeji.com/Article/details/gtufhrzwbq.html

[R19] 数组长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtligvgwwd.html

echo "${#arr[@]}"
来源：http://dali.c1oappe.top/Article/details/gtdopdmauw.html

[R20] 关联数组（字典）
来源：http://dali.hammf.cn/Article/details/gtorrzwwwq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiaafjwqe.html

[R21] 字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgmdmqsr.html

echo "${#s}"
来源：http://dali.zycfv.cn/Article/details/gtxveduord.html

[R22] 截取子串
来源：http://dali.tanke756.top/Article/details/gtetrpzaft.html

echo "${s:0:5}"
来源：http://dali.hongshengwenyu.top/Article/details/gthyuoeohq.html

[R23] 字符串替换
来源：http://dali.pengpengdd.cyou/Article/details/gtjwegdmga.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tian-w.cn/Article/details/gtcpscwpph.html

[R24] 大小写转换
来源：http://dali.yongpay.top/Article/details/gtbnarpeth.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xziqi.cn/Article/details/gtlovucjzq.html

[R25] 去后缀 / 去前缀
来源：http://dali.gotoacloud.top/Article/details/gtryusqfjy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shangyingyoupin.top/Article/details/gtsydhbimi.html

[R26] 命令替换
来源：http://dali.xuetiantiany.cn/Article/details/gtddqyorzz.html

now=$(date +%F); echo "$now"
来源：http://dali.yongpay.top/Article/details/gthykmvwbx.html

[R27] 算术展开
来源：http://dali.gotoacloud.top/Article/details/gtgswwrsau.html

echo $((1 + 2 * 3))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqocibxo.html

[R28] 浮点运算
来源：http://dali.gotoacloud.top/Article/details/gtatutmrxu.html

echo "scale=2; 10/3" | bc
来源：http://dali.redwolf501.top/Article/details/gtgbdejnxl.html

[R29] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gtjyhwctlu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jianghu66.top/Article/details/gtnddpcyhm.html

[R30] 函数返回状态码
来源：http://dali.yvedp.cn/Article/details/gtmtmalogc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhongyouzk.top/Article/details/gtyspqyzip.html

[R31] 局部变量
来源：http://dali.hammf.cn/Article/details/gtltixvbbv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdyuqjbei.html

[R32] 参数个数校验
来源：http://dali.sysykeji.top/Article/details/gtzaxieeat.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cheryme.top/Article/details/gtgpjgcfiz.html

[R33] 捕获错误并提示行号
来源：http://dali.cqqwz.cn/Article/details/gtvanaefgn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zycfv.cn/Article/details/gthxgupsww.html

[R34] 退出时清理
来源：http://dali.daxiang520.top/Article/details/gticngczcg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gtmycwqwis.html

[R35] 后台执行并等待
来源：http://dali.c1oappe.top/Article/details/gtixldkjde.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.mhx1999.top/Article/details/gtshozthwb.html

[R36] 并发执行多个任务
来源：http://dali.zhengqikj.top/Article/details/gtwqlzoawh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinqigufen.top/Article/details/gtexpzdtkr.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gtmlywxuxj.html

files=$(ls -1)
来源：http://dali.gogol.net.cn/Article/details/gttpgfauwe.html

[R38] 管道串联
来源：http://dali.shangyingyoupin.top/Article/details/gtrbpewmxe.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenlongwang.top/Article/details/gtnmdpmhue.html

[R39] 重定向标准输出与错误
来源：http://dali.vqdsnc.cn/Article/details/gticeawvjx.html

cmd > out.log 2>&1
来源：http://dali.sufxvd.cn/Article/details/gtiopvdkfi.html

[R40] 追加写日志
来源：http://dali.ppjwa.cn/Article/details/gtkdxgorgl.html

echo "log" >> out.log
来源：http://dali.ppjwa.cn/Article/details/gtvgndulmk.html

[R41] 丢弃输出
来源：http://dali.zycfv.cn/Article/details/gtrqzdvtrv.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gtawcxrbnv.html

[R42] 输入重定向
来源：http://dali.kuanghao11.cn/Article/details/gtwkpmtraz.html

wc -l < a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdwbzlkt.html

[R43] 按名字查找文件
来源：http://dali.shuidangran.top/Article/details/gtbmwlmrkl.html

find . -name "*.log" -type f
来源：http://dali.chenjidiqi.icu/Article/details/gtbydvwfcn.html

[R44] 按修改时间查找
来源：http://dali.jinqigufen.top/Article/details/gtktrdqejv.html

find . -mtime -7 -type f
来源：http://dali.cashguo.top/Article/details/gtfwokffsm.html

[R45] 批量删除
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfoovmnt.html

find . -name "*.tmp" -delete
来源：http://dali.cqqwz.cn/Article/details/gtrzqgpcbv.html

[R46] 递归替换文件内容
来源：http://dali.yongpay.top/Article/details/gtvkqkkvxd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hnqzz.top/Article/details/gtxrouikuk.html

[R47] sed 单行替换
来源：http://dali.birdmap.top/Article/details/gttuzvwwej.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.aizwys.cn/Article/details/gtylyilchj.html

[R48] awk 取指定列
来源：http://dali.fengsongda.top/Article/details/gtshhwtpjg.html

awk '{print $1, $3}' a.txt
来源：http://dali.fengsongda.top/Article/details/gtlkeagmyo.html

[R49] awk 带条件
来源：http://dali.nanxinkj.top/Article/details/gtiqbndfpv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.vqdsnc.cn/Article/details/gtnlxwyjkw.html

[R50] awk 求和
来源：http://dali.sufxvd.cn/Article/details/gtcwjwkxlj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ivvv.top/Article/details/gtkevthdcm.html

[R51] 排序去重取前几
来源：http://dali.jinqigfzy.top/Article/details/gtdtkonkuj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxuanxn.top/Article/details/gtnxnkkvpl.html

[R52] 统计行数
来源：http://dali.quarkkingdee.top/Article/details/gtroyzccuo.html

wc -l a.txt
来源：http://dali.meibo888.top/Article/details/gtxzahyfsh.html

[R53] 查看文件头与实时尾
来源：http://dali.hnqzz.top/Article/details/gteqvywzrr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ehwqpu.com/Article/details/gtxnyjywkj.html

[R54] 比较两个文件
来源：http://dali.dashuyun.cn/Article/details/gtspwsarnb.html

diff a.txt b.txt
来源：http://dali.jlsjyb.cn/Article/details/gtxshforit.html

[R55] 压缩与解压
来源：http://dali.shuidangran.top/Article/details/gthtrpxgyh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aibaodan.cn/Article/details/gtaqrcfjjl.html

[R56] 远程拷贝
来源：http://dali.bjfxy.top/Article/details/gtxpherbwt.html

scp file user@host:/path/
来源：http://dali.hnqzz.top/Article/details/gtokyarbus.html

[R57] 远程执行命令
来源：http://dali.xuetiantiany.cn/Article/details/gtfhqypaxb.html

ssh user@host 'uptime'
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjjonocd.html

[R58] 下载文件
来源：http://dali.tanke756.top/Article/details/gtwlnvihfz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj202588.top/Article/details/gtqkmzfaqr.html

[R59] 发 POST JSON
来源：http://dali.daxiang520.top/Article/details/gtufugabmb.html


<!-- 参考信息 -->