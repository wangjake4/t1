代发 wailian999

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guannengcc.top/Article/details/gtuqmohgak.html

[Q09] 创建唯一索引
来源：http://dali.hfpthk.cn/Article/details/gtkyyogtge.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewgmwfwz.html

[Q10] 插入单行
来源：http://dali.pycfn.com/Article/details/gtxsvsytaw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.birdmap.top/Article/details/gtygmtlaec.html

[Q11] 一次插入多行
来源：http://dali.xuanzx.com/Article/details/gtbwpdauvi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gtkoemogkc.html

[Q12] 插入后取自增 ID
来源：http://dali.daxiang520.top/Article/details/gtqqtegkps.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shuidangran.top/Article/details/gttitrjxqh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cqqwz.cn/Article/details/gtcoypxrlf.html

[Q13] 忽略重复插入
来源：http://dali.shuidangran.top/Article/details/gtwdpfrpek.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gtsgpsdkkw.html

[Q14] 存在则更新（upsert）
来源：http://dali.havefunace.top/Article/details/gtxojkgvaw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.daria6918.cn/Article/details/gtgsrmvlmg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.c1oappe.top/Article/details/gtmfufzpjh.html

[Q15] 查询全部
来源：http://dali.jlsjyb.cn/Article/details/gtmttjbyge.html

SELECT * FROM users;
来源：http://dali.aizwys.cn/Article/details/gtugenshgj.html

[Q16] 查询指定列
来源：http://dali.yj20258.top/Article/details/gtldgcjwxz.html

SELECT id, name FROM users;
来源：http://dali.redwolf501.top/Article/details/gtcksqnhvh.html

[Q17] 条件查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpyiaykdl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yvedp.cn/Article/details/gtjfoqofuk.html

[Q18] 模糊匹配
来源：http://dali.cashguo.top/Article/details/gtvrlysnye.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cucudq.cn/Article/details/gtqcokvtpb.html

[Q19] 范围查询
来源：http://dali.sxryk.cn/Article/details/gtrxonnsyp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guowangkeji.top/Article/details/gtqtvvtmeq.html

[Q20] IN 列表
来源：http://dali.hongshengwenyu.top/Article/details/gtaeoztyqv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtqtqmysbo.html

[Q21] 空值判断
来源：http://dali.svipenyu.cn/Article/details/gtptiwfyoz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hfpthk.cn/Article/details/gtssyneupq.html

[Q22] 排序
来源：http://dali.hysaishi.cn/Article/details/gtpegwwxrc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhoulong.xyz/Article/details/gtllvqoebm.html

[Q23] 分页
来源：http://dali.sysykeji.top/Article/details/gtrhkcuegf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.havefunace.top/Article/details/gthtgokhgr.html

[Q24] 去重
来源：http://dali.mhx1999.top/Article/details/gttlguycgs.html

SELECT DISTINCT city FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtfmpkswhl.html

[Q25] 只取前 N 条
来源：http://dali.snrcjt.cn/Article/details/gtbydctbhy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tianlin.xyz/Article/details/gtokncowea.html

[Q26] 计数
来源：http://dali.quarkkingdee.top/Article/details/gtyqipypzy.html

SELECT COUNT(*) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtjypsgugl.html

[Q27] 条件计数
来源：http://dali.jinghuilouyu.cn/Article/details/gtqebwgbkl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ybcxt.top/Article/details/gtkbnbhuua.html

[Q28] 求和与平均
来源：http://dali.xuanzx.com/Article/details/gtywlsrkgt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtggqbyqfc.html

[Q29] 最大最小值
来源：http://dali.hysaishi.cn/Article/details/gtekfzmjpl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtnzmcppup.html

[Q30] 分组统计
来源：http://dali.jinghuilouyu.cn/Article/details/gtvoacapzr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gtjxjjwlze.html

[Q31] 分组后过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtigkgumtl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhixingplan.top/Article/details/gtutntqhxn.html

[Q32] 分组拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gtumklisie.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gtrjpfbdlr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.havefunace.top/Article/details/gtnwpmgpoh.html

[Q33] 多列分组
来源：http://dali.chenjidiqi.icu/Article/details/gtfaenftbz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aibaodan.cn/Article/details/gtezcgivrz.html

[Q34] 每组取第一条
来源：http://dali.shangyingyoupin.top/Article/details/gtpkprsppw.html

SELECT * FROM (
来源：http://dali.zhixingplan.top/Article/details/gtpcjbboqm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenjidiqi.icu/Article/details/gtfpkhrlrk.html

) t WHERE rn = 1;
来源：http://dali.ybcxt.top/Article/details/gtkgbkjami.html

[Q35] 内连接
来源：http://dali.yangfankeji.com/Article/details/gtlmrxwdtf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.meibo888.top/Article/details/gtvnsfajhb.html

[Q36] 左连接
来源：http://dali.snrcjt.cn/Article/details/gtngydsadw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gtrgqrinla.html

[Q37] 右连接
来源：http://dali.ybcxt.top/Article/details/gtkqvmtfgx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.svipenyu.cn/Article/details/gtlyaawcov.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ehwqpu.com/Article/details/gtoqrrkqxt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yvedp.cn/Article/details/gtjqjdwyxk.html

[Q39] 自连接（查上下级）
来源：http://dali.ydzc1.top/Article/details/gtqlfjtijv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkjiemxq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ybcxt.top/Article/details/gtiqazdphs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.kuanghao11.cn/Article/details/gtcpolsqkc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ybcxt.top/Article/details/gtlyzpczrq.html

[Q41] 多表连接
来源：http://dali.zhiwuduotai.top/Article/details/gtigqqdaae.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pengpengdd.cyou/Article/details/gtkpynurxn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.pycfn.com/Article/details/gtadruhoqv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinqigufen.top/Article/details/gtutukzrrf.html

[Q42] 连接条件附加过滤
来源：http://dali.snrcjt.cn/Article/details/gtnxgnjpae.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigfzy.top/Article/details/gtrnbchypa.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fengsongda.top/Article/details/gthovfazgb.html

[Q43] 标量子查询
来源：http://dali.ehwqpu.com/Article/details/gtcmgajasd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ivvv.top/Article/details/gtbchpqcds.html

[Q44] IN 子查询
来源：http://dali.jinqigufen.top/Article/details/gtmtxflhoc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jyoumei.cn/Article/details/gtykuyyykb.html

[Q45] EXISTS 判断存在
来源：http://dali.cheryme.top/Article/details/gtknypwapm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gtnpwiohve.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jiagoushi.top/Article/details/gtvumzaqjr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jyoumei.cn/Article/details/gtpjsmglfq.html

[Q47] 与平均值比较
来源：http://dali.yj202588.top/Article/details/gtcdswbowu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258.top/Article/details/gtxpnptjnl.html

[Q48] CTE 公用表表达式
来源：http://dali.ehwqpu.com/Article/details/gtqfhcogfb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yongpay.top/Article/details/gtkprbtspf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tanke756.top/Article/details/gtiidmfini.html

[Q49] 更新单行
来源：http://dali.daria6918.cn/Article/details/gtomnroeiv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtpllkmxio.html

[Q50] 批量更新
来源：http://dali.tanke756.top/Article/details/gtfcxroqao.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sysykeji.top/Article/details/gtmaxtvkwc.html

[Q51] 用子查询更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdzkrbtd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtifgutoxs.html

[Q52] 删除指定行
来源：http://dali.sweek.top/Article/details/gtxpxlwdwo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvcnnlhi.html

[Q53] 按条件删除
来源：http://dali.andypj.xyz/Article/details/gtdextimio.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenlongwang.top/Article/details/gtstsgudep.html

[Q54] 清空表
来源：http://dali.daria6918.cn/Article/details/gtnwciabwn.html

TRUNCATE TABLE logs;
来源：http://dali.cqqwz.cn/Article/details/gtgdptuxrp.html

[Q55] 排名（并列占位）
来源：http://dali.yueranfly.top/Article/details/gttrqbvpkn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.wangshuangyany.cn/Article/details/gtrokfqusk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hfpthk.cn/Article/details/gtmixrmhlq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsynhtkn.html

[Q57] 行号
来源：http://dali.shanyushiyangtech.top/Article/details/gtppuyvgjz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.bjfxy.top/Article/details/gtbuptlupp.html

[Q58] 累计求和
来源：http://dali.redwolf501.top/Article/details/gtzhjlfgoe.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gttzdmfdfp.html

[Q59] 分组内累计
来源：http://dali.pengpengdd.cyou/Article/details/gtipqkqbon.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtpdlhtxpm.html

[Q60] 取上一行 / 下一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqlgqjun.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.dianchejie.cn/Article/details/gtzarxiyow.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtwgdngckn.html

[Q61] 移动平均
来源：http://dali.daria6918.cn/Article/details/gtppiwhmod.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtfywcnhqv.html

[Q62] 分组占比
来源：http://dali.vqdsnc.cn/Article/details/gtigckutay.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtykxnhesw.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gtiwohwhju.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yvedp.cn/Article/details/gtjqcmhqih.html

[Q64] 提交事务
来源：http://dali.meibo888.top/Article/details/gtjrgqlyie.html

COMMIT;
来源：http://dali.iojbl.cn/Article/details/gtuywyeren.html

[Q65] 回滚事务
来源：http://dali.aizwys.cn/Article/details/gtshkdglaw.html

ROLLBACK;
来源：http://dali.ybcxt.top/Article/details/gtwabfujfr.html

[Q66] 行锁查询
来源：http://dali.shuidangran.top/Article/details/gttcfhdqeq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yangfankeji.com/Article/details/gtmygfofec.html

[Q67] 设置隔离级别
来源：http://dali.nwbrower.top/Article/details/gtrfbqwplo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.wangdashe.top/Article/details/gtnjgrcvvz.html

[Q68] 保存点
来源：http://dali.xuetiantiany.cn/Article/details/gtkfccfqbm.html

SAVEPOINT sp1;
来源：http://dali.xuetiantiany.cn/Article/details/gtrplxizye.html

ROLLBACK TO sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzaeorue.html

[Q69] 查看执行计划
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvncbqgjj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.dashuyun.cn/Article/details/gtjponunfx.html

[Q70] 更新统计信息
来源：http://dali.ydzc1.top/Article/details/gtdzgzyyas.html

ANALYZE TABLE users;
来源：http://dali.xuanzx.com/Article/details/gtsxxcvfgp.html

[Q71] 查看建表语句
来源：http://dali.quarkkingdee.top/Article/details/gtiorirguj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yanxiufei.cn/Article/details/gthkiljvdu.html

[Q72] 查看索引
来源：http://dali.shuidangran.top/Article/details/gtfmiaguuf.html

SHOW INDEX FROM users;
来源：http://dali.bjfxy.top/Article/details/gtqjeendmq.html

[Q73] 查看表状态
来源：http://dali.pengpengdd.cyou/Article/details/gtoiizreff.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhengqikj.top/Article/details/gtuqpkwvme.html

[Q74] 强制使用索引
来源：http://dali.hongshengwenyu.top/Article/details/gtjaqspimy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ivvv.top/Article/details/gtbofzyaxk.html

[Q75] 日期格式化
来源：http://dali.aibaodan.cn/Article/details/gtjllzeydc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hammf.cn/Article/details/gthvgvopao.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenjidiqi.icu/Article/details/gtpxsohzjl.html

[Q76] 按天统计
来源：http://dali.jinqigfzy.top/Article/details/gtfewlzfqp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yongpay.top/Article/details/gtasgrquub.html

[Q77] 时间加减
来源：http://dali.bjfxy.top/Article/details/gtsiaujxui.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yongpay.top/Article/details/gtrclwcrlz.html

[Q78] 当前时间
来源：http://dali.zycfv.cn/Article/details/gtpvwgteyp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhongyouzk.top/Article/details/gtrdbxnjfw.html

[Q79] 字符串拼接
来源：http://dali.zycfv.cn/Article/details/gtbbczbhew.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.smart0.xyz/Article/details/gthzloiwfh.html

[Q80] 字符串截取
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdfsczly.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtmklofcpi.html

[Q81] 字符串替换
来源：http://dali.shangyingyoupin.top/Article/details/gtakdiefiq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xuanzx.com/Article/details/gtgcnplknz.html

[Q82] 字符长度与字节长度
来源：http://dali.gogol.net.cn/Article/details/gtbmufswyt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtzpasrbyy.html

[Q83] 大小写转换
来源：http://dali.yongpay.top/Article/details/gtngzvlnbq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sweek.top/Article/details/gtkerjdmnh.html

[Q84] 去除首尾空格
来源：http://dali.birdmap.top/Article/details/gtzxqrmgox.html

SELECT TRIM(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtwkpyfjha.html

[Q85] 数值取整
来源：http://dali.jinqigfzy.top/Article/details/gtmagikcdq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenzaomai.com/Article/details/gtmxdqkgui.html

[Q86] 读取 JSON 字段
来源：http://dali.0kj1m.cn/Article/details/gtafpootnl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigfzy.top/Article/details/gtyfauwmtd.html

[Q87] JSON 字段做条件
来源：http://dali.kuanghao11.cn/Article/details/gtkdnhmebb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.316326.xyz/Article/details/gtxdycggca.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnqzz.top/Article/details/gtvsxylhuk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.dianchejie.cn/Article/details/gtmrcdsuum.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.bjfxy.top/Article/details/gtkyuiqpyq.html

[Q89] 判断表是否存在
来源：http://dali.gogol.net.cn/Article/details/gtundurept.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zycfv.cn/Article/details/gtbluhunan.html

[Q90] 生成序号列
来源：http://dali.xuetiantiany.cn/Article/details/gtbgjnaeay.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cashguo.top/Article/details/gtsykulekr.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtrvjybkgg.html

R. Bash 专题
来源：http://dali.tian-w.cn/Article/details/gtfxwvqmcz.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtbqskaosh.html

[R01] shebang 与严格模式
来源：http://dali.andypj.xyz/Article/details/gtukhybwva.html

#!/usr/bin/env bash
来源：http://dali.xylfe.cn/Article/details/gthoajcwmv.html

set -euo pipefail
来源：http://dali.yangfankeji.com/Article/details/gtvbjbyesz.html

[R02] 变量赋值与使用
来源：http://dali.xuetiantiany.cn/Article/details/gtvncphcnv.html

name="Tom"; echo "$name"
来源：http://dali.pycfn.com/Article/details/gthppbuuri.html

[R03] 只读变量
来源：http://dali.jyoumei.cn/Article/details/gteyqhsagk.html

readonly PI=3.14
来源：http://dali.yueranfly.top/Article/details/gtkrxeghpl.html

[R04] 位置参数
来源：http://dali.zhiwuduotai.top/Article/details/gtknkgjqzl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hongshengwenyu.top/Article/details/gthcsnsvgu.html

[R05] 参数默认值
来源：http://dali.wangshuangyany.cn/Article/details/gthjwchomc.html

name="${1:-default}"
来源：http://dali.yj20258.top/Article/details/gtzftjxfef.html

[R06] 判断命令是否存在
来源：http://dali.shuidangran.top/Article/details/gtwmueamnh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cdnleiting.top/Article/details/gtbigosgph.html

[R07] if 判断文件
来源：http://dali.gogol.net.cn/Article/details/gtagcxtpai.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gthjrhdajo.html

[R08] 数值比较
来源：http://dali.redwolf501.top/Article/details/gtkafwihvs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sxryk.cn/Article/details/gtkobwnqrh.html

[R09] 字符串比较
来源：http://dali.hammf.cn/Article/details/gtjxovaayh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhixingplan.top/Article/details/gtlehgctrl.html

[R10] 正则匹配
来源：http://dali.c1oappe.top/Article/details/gttaaleypx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zdqjudy.top/Article/details/gtkvdqkhoh.html

[R11] case 多分支
来源：http://dali.yueranfly.top/Article/details/gtswmbpust.html

case "$1" in
来源：http://dali.shangyingyoupin.top/Article/details/gtbauxsmzv.html

start) echo "启动" ;;
来源：http://dali.cashguo.top/Article/details/gtearnwtap.html

stop)  echo "停止" ;;
来源：http://dali.cqqwz.cn/Article/details/gtiyocowzb.html

*)     echo "未知命令" ;;
来源：http://dali.mhx1999.top/Article/details/gtyizzkflc.html

esac
来源：http://dali.yuxming.cn/Article/details/gtwnejolja.html

[R12] for 遍历文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehxzymec.html

for f in *.txt; do echo "$f"; done
来源：http://dali.andypj.xyz/Article/details/gtcqjuixqp.html

[R13] for 计数循环
来源：http://dali.fengsongda.top/Article/details/gtwgypbhkw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gthpvwawsy.html

[R14] C 风格 for
来源：http://dali.jianghu66.top/Article/details/gtcnnlmlvw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhoulong.xyz/Article/details/gtytyxyqzb.html

[R15] while 逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtbvycdbxe.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jiagoushi.top/Article/details/gtnxfbhfyc.html

[R16] until 等待条件
来源：http://dali.yuanzhike.top/Article/details/gtwwfejvsy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuxming.cn/Article/details/gtamvyvhqh.html

[R17] 数组定义与取值
来源：http://dali.cdnleiting.top/Article/details/gtkqxleidi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.snrcjt.cn/Article/details/gtkxykbiyt.html

[R18] 遍历数组
来源：http://dali.nwbrower.top/Article/details/gtqigwlaok.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ppjwa.cn/Article/details/gtaiomgfme.html

[R19] 数组长度
来源：http://dali.hammf.cn/Article/details/gtykngjfsx.html

echo "${#arr[@]}"
来源：http://dali.ppjwa.cn/Article/details/gtkxnoqegx.html

[R20] 关联数组（字典）
来源：http://dali.ehwqpu.com/Article/details/gttscmjbus.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xuetiantiany.cn/Article/details/gtiybmeavf.html

[R21] 字符串长度
来源：http://dali.jyoumei.cn/Article/details/gtbzwbmcfd.html

echo "${#s}"
来源：http://dali.yangfankeji.com/Article/details/gtkwpsehym.html

[R22] 截取子串
来源：http://dali.pengpengdd.cyou/Article/details/gtilefiabq.html

echo "${s:0:5}"
来源：http://dali.hysaishi.cn/Article/details/gtqrtnmeqb.html

[R23] 字符串替换
来源：http://dali.dashuyun.cn/Article/details/gtcfbqqiig.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ydzc1.top/Article/details/gtucprrvco.html

[R24] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gtpjufijoi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldyxrmdf.html

[R25] 去后缀 / 去前缀
来源：http://dali.guowangkeji.top/Article/details/gtusfpqeoj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.fzhhl.top/Article/details/gtpewjjsyb.html

[R26] 命令替换
来源：http://dali.fengsongda.top/Article/details/gtettlgeym.html

now=$(date +%F); echo "$now"
来源：http://dali.yj202588.top/Article/details/gtlobhhqxg.html

[R27] 算术展开
来源：http://dali.hysaishi.cn/Article/details/gtutmzrcse.html

echo $((1 + 2 * 3))
来源：http://dali.fzhhl.top/Article/details/gtelqyygob.html

[R28] 浮点运算
来源：http://dali.ybcxt.top/Article/details/gtusldldzm.html

echo "scale=2; 10/3" | bc
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnayqcxrg.html

[R29] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gtsduoxdrj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shangyingyoupin.top/Article/details/gtkgwsocry.html

[R30] 函数返回状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgxmmujo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xylfe.cn/Article/details/gtujjiqdcn.html

[R31] 局部变量
来源：http://dali.xziqi.cn/Article/details/gtcsqfjvvc.html

f() { local x=1; echo "$x"; }
来源：http://dali.jianghu66.top/Article/details/gtoikdxdcc.html

[R32] 参数个数校验
来源：http://dali.wangdashe.top/Article/details/gtdkwiqomh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gtvngwtzpc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhongyouzk.top/Article/details/gthshkuitq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jiagoushi.top/Article/details/gtmlopmdji.html

[R34] 退出时清理
来源：http://dali.iojbl.cn/Article/details/gtkhfzabpf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jiagoushi.top/Article/details/gtpuctlakj.html

[R35] 后台执行并等待
来源：http://dali.andypj.xyz/Article/details/gtcfnskbtj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yueranfly.top/Article/details/gtsjkkfvkc.html

[R36] 并发执行多个任务
来源：http://dali.xinyue.icu/Article/details/gtlqsobkcf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sysykeji.top/Article/details/gtxmhlaldz.html

[R37] 把输出赋给变量
来源：http://dali.jinqigfzy.top/Article/details/gttwfvslzu.html

files=$(ls -1)
来源：http://dali.zdqjudy.top/Article/details/gtqlszekgh.html

[R38] 管道串联
来源：http://dali.sweek.top/Article/details/gtcwxswpqu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fzhhl.top/Article/details/gtarvlmtmy.html

[R39] 重定向标准输出与错误
来源：http://dali.yuxming.cn/Article/details/gtkamdgobv.html

cmd > out.log 2>&1
来源：http://dali.sufxvd.cn/Article/details/gtxwospltk.html

[R40] 追加写日志
来源：http://dali.hysaishi.cn/Article/details/gtathgaskt.html

echo "log" >> out.log
来源：http://dali.cqqwz.cn/Article/details/gtdeadgwzy.html

[R41] 丢弃输出
来源：http://dali.hfpthk.cn/Article/details/gtbzkbsibe.html

cmd >/dev/null 2>&1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydvbiozh.html

[R42] 输入重定向
来源：http://dali.0kj1m.cn/Article/details/gtbshcgjoa.html

wc -l < a.txt
来源：http://dali.yonumen.top/Article/details/gtskzkkczy.html

[R43] 按名字查找文件
来源：http://dali.smart0.xyz/Article/details/gtcehgawbv.html

find . -name "*.log" -type f
来源：http://dali.yangfankeji.com/Article/details/gtbzxfjnca.html

[R44] 按修改时间查找
来源：http://dali.nanxuanxn.top/Article/details/gtijiqepzz.html

find . -mtime -7 -type f
来源：http://dali.feifeiyinyue.top/Article/details/gtqzybeuri.html

[R45] 批量删除
来源：http://dali.yj20258888.top/Article/details/gtvtvscaza.html

find . -name "*.tmp" -delete
来源：http://dali.yuxming.cn/Article/details/gthurxcvdy.html

[R46] 递归替换文件内容
来源：http://dali.snrcjt.cn/Article/details/gtlygpyprp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.kuanghao11.cn/Article/details/gtaonhzgst.html

[R47] sed 单行替换
来源：http://dali.xylfe.cn/Article/details/gtvpoaknag.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zdqjudy.top/Article/details/gtvodrmwso.html

[R48] awk 取指定列
来源：http://dali.dianchejie.cn/Article/details/gtkmqihime.html

awk '{print $1, $3}' a.txt
来源：http://dali.nwbrower.top/Article/details/gtltrosmsw.html

[R49] awk 带条件
来源：http://dali.meibo888.top/Article/details/gtqjypeuox.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.kuanghao11.cn/Article/details/gtwxkzqczk.html

[R50] awk 求和
来源：http://dali.cucudq.cn/Article/details/gtltpeuzhr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gthhxmqxyk.html

[R51] 排序去重取前几
来源：http://dali.zycfv.cn/Article/details/gthmawqqmx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxinkj.top/Article/details/gtzwouscyw.html

[R52] 统计行数
来源：http://dali.zhengqikj.top/Article/details/gtnsjsurth.html

wc -l a.txt
来源：http://dali.hammf.cn/Article/details/gtvmklekgo.html

[R53] 查看文件头与实时尾
来源：http://dali.pengpengdd.cyou/Article/details/gtjfckyaun.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ehwqpu.com/Article/details/gtvqxruxrs.html

[R54] 比较两个文件
来源：http://dali.chenlongwang.top/Article/details/gturqwgzfi.html

diff a.txt b.txt
来源：http://dali.jqgfzy.top/Article/details/gtcuweuywc.html

[R55] 压缩与解压
来源：http://dali.pycfn.com/Article/details/gtexyoqfyp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwlenxisf.html

[R56] 远程拷贝
来源：http://dali.yj20258888.top/Article/details/gtrwgnirwt.html

scp file user@host:/path/
来源：http://dali.hfpthk.cn/Article/details/gtfpjkhpwh.html

[R57] 远程执行命令
来源：http://dali.yongpay.top/Article/details/gtavbonxbj.html


<!-- 参考信息 -->