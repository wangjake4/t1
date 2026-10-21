代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.9152youxi.cn/Article/details/gtsqncuyyj.html

[Q05] 重命名列
来源：http://dali.hnxiangtu.top/Article/details/gtggzzqlag.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.0kj1m.cn/Article/details/gtsohipttm.html

[Q06] 删除列
来源：http://dali.haohaochexian.top/Article/details/gtrsiutlzn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ivvv.top/Article/details/gttqpvygxv.html

[Q07] 删除表
来源：http://dali.chenjidiqi.icu/Article/details/gtglwurrgg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj20258888.top/Article/details/gtdfapgqsw.html

[Q08] 创建普通索引
来源：http://dali.haohaochexian.top/Article/details/gtnvvwchml.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gtedlovyov.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gtolqvehtj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gtoenhbuvk.html

[Q10] 插入单行
来源：http://dali.pengpengdd.cyou/Article/details/gtirbtvygt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gtxcjadcaq.html

[Q11] 一次插入多行
来源：http://dali.hongshengwenyu.top/Article/details/gtyxqpvark.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hnqzz.top/Article/details/gtdhrmbgri.html

[Q12] 插入后取自增 ID
来源：http://dali.quarkkingdee.top/Article/details/gtbtbjyyro.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yanxiufei.cn/Article/details/gtduupjgjk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gtjepmaidp.html

[Q13] 忽略重复插入
来源：http://dali.birdmap.top/Article/details/gtzpsafxsj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtqzdstsfp.html

[Q14] 存在则更新（upsert）
来源：http://dali.bjfxy.top/Article/details/gtdqcreshi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xinyue.icu/Article/details/gtrjbdqlri.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jlsjyb.cn/Article/details/gtmtxjqvri.html

[Q15] 查询全部
来源：http://dali.tianlin.xyz/Article/details/gtubeftjip.html

SELECT * FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubbiapmv.html

[Q16] 查询指定列
来源：http://dali.jqgfzy.top/Article/details/gtwhyuzpvo.html

SELECT id, name FROM users;
来源：http://dali.aizwys.cn/Article/details/gtkdyjtycp.html

[Q17] 条件查询
来源：http://dali.shzxlz.cn/Article/details/gtniokjbfy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zycfv.cn/Article/details/gtoqvlwxbp.html

[Q18] 模糊匹配
来源：http://dali.andypj.xyz/Article/details/gtjzcqqoew.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.quarkkingdee.top/Article/details/gtoakwvgrl.html

[Q19] 范围查询
来源：http://dali.daxiang520.top/Article/details/gtvdecmido.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhongyouzk.top/Article/details/gtisbvzhmb.html

[Q20] IN 列表
来源：http://dali.sufxvd.cn/Article/details/gtcyojtgrk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shuidangran.top/Article/details/gtmrrrpgnd.html

[Q21] 空值判断
来源：http://dali.tianlin.xyz/Article/details/gtaffwfreh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hongshengwenyu.top/Article/details/gtsgyovcpm.html

[Q22] 排序
来源：http://dali.hammf.cn/Article/details/gtqdbekfaz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cashguo.top/Article/details/gtlpydogku.html

[Q23] 分页
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdepbtpjd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cqqwz.cn/Article/details/gttcrhxgey.html

[Q24] 去重
来源：http://dali.nanxinkj.top/Article/details/gtjgguwdeu.html

SELECT DISTINCT city FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gthpcmmzvs.html

[Q25] 只取前 N 条
来源：http://dali.guannengcc.top/Article/details/gtnrbismam.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenlongwang.top/Article/details/gtopaebiij.html

[Q26] 计数
来源：http://dali.zycfv.cn/Article/details/gtagiwizeu.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtlpbdimwc.html

[Q27] 条件计数
来源：http://dali.sysykeji.top/Article/details/gtnvzrptor.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkttovicc.html

[Q28] 求和与平均
来源：http://dali.nanxuanxn.top/Article/details/gtiuivojbv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtltxhlact.html

[Q29] 最大最小值
来源：http://dali.cashguo.top/Article/details/gtkkouslhf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtcekefvfa.html

[Q30] 分组统计
来源：http://dali.hysaishi.cn/Article/details/gtjjzvffcd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gtkvfftuot.html

[Q31] 分组后过滤
来源：http://dali.sxryk.cn/Article/details/gtyunykcda.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sysykeji.top/Article/details/gtbmqzmwzq.html

[Q32] 分组拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gtgimphxyq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gtszzofvlo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tianlin.xyz/Article/details/gtlwysrczo.html

[Q33] 多列分组
来源：http://dali.chenzaomai.com/Article/details/gtfvhcuwql.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sweek.top/Article/details/gtrppdqstw.html

[Q34] 每组取第一条
来源：http://dali.jiagoushi.top/Article/details/gtdgfbdugb.html

SELECT * FROM (
来源：http://dali.c1oappe.top/Article/details/gtuzyxznty.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenlongwang.top/Article/details/gtmwpvnrau.html

) t WHERE rn = 1;
来源：http://dali.shuidangran.top/Article/details/gtxfzudssh.html

[Q35] 内连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gthyhkdcbv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gtnojwbsle.html

[Q36] 左连接
来源：http://dali.xuetiantiany.cn/Article/details/gttcfxtlvr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.redwolf501.top/Article/details/gtkeqbxsvj.html

[Q37] 右连接
来源：http://dali.wangdashe.top/Article/details/gtncdjcpuh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmsqfnjc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxinkj.top/Article/details/gtvjphlljq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinqigufen.top/Article/details/gtrahvupeg.html

[Q39] 自连接（查上下级）
来源：http://dali.dashuyun.cn/Article/details/gtwfdtwzjc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhixingplan.top/Article/details/gtgeqewurh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.pycfn.com/Article/details/gtzbxkwiyt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zdqjudy.top/Article/details/gtcazrttjt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hysaishi.cn/Article/details/gtgylygvmv.html

[Q41] 多表连接
来源：http://dali.cdnleiting.top/Article/details/gtqehewoxt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabvttatw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.pengpengdd.cyou/Article/details/gtqgzwjkfc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.svipenyu.cn/Article/details/gtwvjovzvw.html

[Q42] 连接条件附加过滤
来源：http://dali.havefunace.top/Article/details/gtuacdkuod.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ppjwa.cn/Article/details/gtvcjbbztd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jqgfzy.top/Article/details/gtlbbewtdt.html

[Q43] 标量子查询
来源：http://dali.xuanzx.com/Article/details/gtamwdtrxk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.guannengcc.top/Article/details/gtwaxrqxyq.html

[Q44] IN 子查询
来源：http://dali.andypj.xyz/Article/details/gtfrjozhzu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yvedp.cn/Article/details/gtmpxxrfpr.html

[Q45] EXISTS 判断存在
来源：http://dali.dianchejie.cn/Article/details/gtjrxbfaou.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zycfv.cn/Article/details/gtibnhcpbu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.kuanghao11.cn/Article/details/gtvyrstydj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.mhx1999.top/Article/details/gtodzhfexz.html

[Q47] 与平均值比较
来源：http://dali.sufxvd.cn/Article/details/gtuowftxkb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.havefunace.top/Article/details/gtoitbsqhe.html

[Q48] CTE 公用表表达式
来源：http://dali.yuxming.cn/Article/details/gtjvpndzbz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yonumen.top/Article/details/gtnamntmuz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhixingplan.top/Article/details/gtjuxwgjgw.html

[Q49] 更新单行
来源：http://dali.sufxvd.cn/Article/details/gtsoogfyic.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gtseylkpap.html

[Q50] 批量更新
来源：http://dali.xinyue.icu/Article/details/gtdpqpjjoj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gotoacloud.top/Article/details/gtdbktjbpi.html

[Q51] 用子查询更新
来源：http://dali.iojbl.cn/Article/details/gtwmntcncx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtncaeykhc.html

[Q52] 删除指定行
来源：http://dali.yongpay.top/Article/details/gtgqjsdnzt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jqgfzy.top/Article/details/gtbdgcbwmw.html

[Q53] 按条件删除
来源：http://dali.cashguo.top/Article/details/gthhuxegdf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nwbrower.top/Article/details/gttycjlotn.html

[Q54] 清空表
来源：http://dali.cashguo.top/Article/details/gtdlprbocd.html

TRUNCATE TABLE logs;
来源：http://dali.cashguo.top/Article/details/gtdidfjuvu.html

[Q55] 排名（并列占位）
来源：http://dali.9152youxi.cn/Article/details/gtguycbagv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zdqjudy.top/Article/details/gttyngpkwn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shangyingyoupin.top/Article/details/gtsukifxim.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tian-w.cn/Article/details/gtwhelgyul.html

[Q57] 行号
来源：http://dali.ehwqpu.com/Article/details/gtoecgtwsy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtankbtzap.html

[Q58] 累计求和
来源：http://dali.hnqzz.top/Article/details/gtavwuyrvk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtwhxpwbjf.html

[Q59] 分组内累计
来源：http://dali.zhoulong.xyz/Article/details/gtimkucwfg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtffiibyvg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zycfv.cn/Article/details/gtxzcftcym.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tian-w.cn/Article/details/gtkqnzyukm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtkpspmsjj.html

[Q61] 移动平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedlkhjgf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtpvszwbbr.html

[Q62] 分组占比
来源：http://dali.yj202588.top/Article/details/gtpohojyyo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gtjpsvhifk.html

[Q63] 开启事务
来源：http://dali.hnxiangtu.top/Article/details/gthvnqehrs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgufenzy.top/Article/details/gtgpyhjymn.html

[Q64] 提交事务
来源：http://dali.hammf.cn/Article/details/gtxmwaadiu.html

COMMIT;
来源：http://dali.dashuyun.cn/Article/details/gtddzksuww.html

[Q65] 回滚事务
来源：http://dali.smart0.xyz/Article/details/gtrjgvlvne.html

ROLLBACK;
来源：http://dali.yuanzhike.top/Article/details/gteholntvj.html

[Q66] 行锁查询
来源：http://dali.vqdsnc.cn/Article/details/gtbwzjrbum.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.aibaodan.cn/Article/details/gtxdzgppyp.html

[Q67] 设置隔离级别
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjfxwmwp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigfzy.top/Article/details/gtmsgncdve.html

[Q68] 保存点
来源：http://dali.svipenyu.cn/Article/details/gtjslkvuzf.html

SAVEPOINT sp1;
来源：http://dali.daxiang520.top/Article/details/gtjydjhncu.html

ROLLBACK TO sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgthobgps.html

[Q69] 查看执行计划
来源：http://dali.hongshengwenyu.top/Article/details/gtwyrqoeyu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yuxming.cn/Article/details/gtuxcexrcp.html

[Q70] 更新统计信息
来源：http://dali.sxryk.cn/Article/details/gtwiqyfqci.html

ANALYZE TABLE users;
来源：http://dali.havefunace.top/Article/details/gtszxnyhpb.html

[Q71] 查看建表语句
来源：http://dali.yj20258.top/Article/details/gteqpuwgos.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daria6918.cn/Article/details/gtogmoaune.html

[Q72] 查看索引
来源：http://dali.yonumen.top/Article/details/gtjotqwtid.html

SHOW INDEX FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtjjvnsbtd.html

[Q73] 查看表状态
来源：http://dali.ydzc1.top/Article/details/gtibskcjxl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gaohongyu789.top/Article/details/gtwddcxeme.html

[Q74] 强制使用索引
来源：http://dali.aizwys.cn/Article/details/gtmqjdhbao.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.andypj.xyz/Article/details/gtzfhiylce.html

[Q75] 日期格式化
来源：http://dali.havefunace.top/Article/details/gtztsddnnt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtrzzuakqo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhiwuduotai.top/Article/details/gttalqvdbw.html

[Q76] 按天统计
来源：http://dali.sweek.top/Article/details/gtmxqqvsug.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.9152youxi.cn/Article/details/gtfdlgyquy.html

[Q77] 时间加减
来源：http://dali.nanxuanxn.top/Article/details/gttbfgjjws.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.aibaodan.cn/Article/details/gtkijwzjte.html

[Q78] 当前时间
来源：http://dali.316326.xyz/Article/details/gtydqthkdi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sxryk.cn/Article/details/gtcocaaaje.html

[Q79] 字符串拼接
来源：http://dali.jiagoushi.top/Article/details/gtqktmbzjr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.c1oappe.top/Article/details/gtmmejkaaw.html

[Q80] 字符串截取
来源：http://dali.yj202588.top/Article/details/gtbkukjkmm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtncdxmepp.html

[Q81] 字符串替换
来源：http://dali.havefunace.top/Article/details/gtutidsdxl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtzyuhxjkf.html

[Q82] 字符长度与字节长度
来源：http://dali.0kj1m.cn/Article/details/gtuiptcvvx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtuiarzkhf.html

[Q83] 大小写转换
来源：http://dali.hammf.cn/Article/details/gttknvrrmc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtznvqcgmn.html

[Q84] 去除首尾空格
来源：http://dali.sysykeji.top/Article/details/gtffkgkggo.html

SELECT TRIM(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gtuayqkkgq.html

[Q85] 数值取整
来源：http://dali.hongshengwenyu.top/Article/details/gtsjgnlfip.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.fengsongda.top/Article/details/gtzxmiiilo.html

[Q86] 读取 JSON 字段
来源：http://dali.zhoulong.xyz/Article/details/gtkfwelvcf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.daxiang520.top/Article/details/gtylgzxujb.html

[Q87] JSON 字段做条件
来源：http://dali.yuanzhike.top/Article/details/gtldpgmlws.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hnxiangtu.top/Article/details/gtwwqbjltv.html

[Q88] 行转列（条件聚合）
来源：http://dali.nwbrower.top/Article/details/gttgkepihn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pycfn.com/Article/details/gtowzfzufh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yonumen.top/Article/details/gtwgatnopw.html

[Q89] 判断表是否存在
来源：http://dali.ybcxt.top/Article/details/gtojhudlod.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinqigfzy.top/Article/details/gtngrcqwhj.html

[Q90] 生成序号列
来源：http://dali.zhoulong.xyz/Article/details/gtzcwvpahg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhixingplan.top/Article/details/gtgdhrozgg.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtvcbzwcbt.html

R. Bash 专题
来源：http://dali.daxiang520.top/Article/details/gtnczfcrkt.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtwsovybho.html

[R01] shebang 与严格模式
来源：http://dali.ivvv.top/Article/details/gtjrkiydke.html

#!/usr/bin/env bash
来源：http://dali.zycfv.cn/Article/details/gtvbpefakf.html

set -euo pipefail
来源：http://dali.cheryme.top/Article/details/gtoyfsimmj.html

[R02] 变量赋值与使用
来源：http://dali.ybcxt.top/Article/details/gtvtynsvpj.html

name="Tom"; echo "$name"
来源：http://dali.0kj1m.cn/Article/details/gtnhstnhab.html

[R03] 只读变量
来源：http://dali.gotoacloud.top/Article/details/gtzpzgxuhp.html

readonly PI=3.14
来源：http://dali.gzhubu.top/Article/details/gtwkrpovvg.html

[R04] 位置参数
来源：http://dali.nwbrower.top/Article/details/gtnjrgowek.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xziqi.cn/Article/details/gtefajznxw.html

[R05] 参数默认值
来源：http://dali.xuanzx.com/Article/details/gttauqbhuq.html

name="${1:-default}"
来源：http://dali.cheryme.top/Article/details/gtyyijdbpj.html

[R06] 判断命令是否存在
来源：http://dali.cashguo.top/Article/details/gtqyswrhpg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gtwuqkujhm.html

[R07] if 判断文件
来源：http://dali.wangshuangyany.cn/Article/details/gtkxfsajds.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ybcxt.top/Article/details/gttvkkvfqh.html

[R08] 数值比较
来源：http://dali.meibo888.top/Article/details/gtsbhjkchv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hysaishi.cn/Article/details/gthgrzizay.html

[R09] 字符串比较
来源：http://dali.andypj.xyz/Article/details/gtzxsacvpv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sysykeji.top/Article/details/gtrzlezaji.html

[R10] 正则匹配
来源：http://dali.yj20258888.top/Article/details/gtxieuvnbd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ivvv.top/Article/details/gtpuvnhqlp.html

[R11] case 多分支
来源：http://dali.wangdashe.top/Article/details/gtnxgfquve.html

case "$1" in
来源：http://dali.zhiwuduotai.top/Article/details/gtxxmpmlac.html

start) echo "启动" ;;
来源：http://dali.xylfe.cn/Article/details/gthqaoindp.html

stop)  echo "停止" ;;
来源：http://dali.zhixingplan.top/Article/details/gtkqttqqxn.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gtqbisxpbt.html

esac
来源：http://dali.gotoacloud.top/Article/details/gtdsdiwsgi.html

[R12] for 遍历文件
来源：http://dali.hysaishi.cn/Article/details/gthkqqbjhv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yvedp.cn/Article/details/gtaoawydld.html

[R13] for 计数循环
来源：http://dali.hywenlv.cn/Article/details/gtctralxpy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj20258888.top/Article/details/gtjnvhvmcg.html

[R14] C 风格 for
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpjgbemh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yanxiufei.cn/Article/details/gtmowbqscb.html

[R15] while 逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gtzymwmueg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.9152youxi.cn/Article/details/gtgakzeoyr.html

[R16] until 等待条件
来源：http://dali.bjfxy.top/Article/details/gtbtlukzfq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sxryk.cn/Article/details/gtdnppoigy.html

[R17] 数组定义与取值
来源：http://dali.yongpay.top/Article/details/gtboghijrx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcflpjbwq.html

[R18] 遍历数组
来源：http://dali.xuanzx.com/Article/details/gtmvjyfozg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ydzc1.top/Article/details/gtchvzyklk.html

[R19] 数组长度
来源：http://dali.kuanghao11.cn/Article/details/gtytdppogf.html

echo "${#arr[@]}"
来源：http://dali.hywenlv.cn/Article/details/gtmphgasij.html

[R20] 关联数组（字典）
来源：http://dali.shuidangran.top/Article/details/gtkjhkjzlq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.fengsongda.top/Article/details/gtkxbzqvue.html

[R21] 字符串长度
来源：http://dali.yj20258888.top/Article/details/gtulocyyut.html

echo "${#s}"
来源：http://dali.zdqjudy.top/Article/details/gttfhtkdsh.html

[R22] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gtdhqyqxce.html

echo "${s:0:5}"
来源：http://dali.cashguo.top/Article/details/gtfpxznyyy.html

[R23] 字符串替换
来源：http://dali.andypj.xyz/Article/details/gtaisqavbv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shangyingyoupin.top/Article/details/gtvanpqgoe.html

[R24] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gtkdnutujc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.vqdsnc.cn/Article/details/gtdpuuszfe.html

[R25] 去后缀 / 去前缀
来源：http://dali.yonumen.top/Article/details/gtanmyxcwk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.fengsongda.top/Article/details/gtnbgikgnv.html

[R26] 命令替换
来源：http://dali.tanke756.top/Article/details/gtdsrffdda.html

now=$(date +%F); echo "$now"
来源：http://dali.pycfn.com/Article/details/gtrawyrqoe.html

[R27] 算术展开
来源：http://dali.jinghuilouyu.cn/Article/details/gttahznkky.html

echo $((1 + 2 * 3))
来源：http://dali.316326.xyz/Article/details/gtmjuaassn.html

[R28] 浮点运算
来源：http://dali.gogol.net.cn/Article/details/gtuqegyarg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gtzenrsjhv.html

[R29] 定义函数
来源：http://dali.cqqwz.cn/Article/details/gtinrvahik.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nanxuanxn.top/Article/details/gtkpltyixv.html

[R30] 函数返回状态码
来源：http://dali.gotoacloud.top/Article/details/gtbvtozjfq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.aibaodan.cn/Article/details/gtpbqfdvzh.html

[R31] 局部变量
来源：http://dali.pengpengdd.cyou/Article/details/gtzbfgyryc.html

f() { local x=1; echo "$x"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbcapcghu.html

[R32] 参数个数校验
来源：http://dali.yj202588.top/Article/details/gtvcqfxhkr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gtpttvqgbl.html

[R33] 捕获错误并提示行号
来源：http://dali.tanke756.top/Article/details/gtobjehmqi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tian-w.cn/Article/details/gtyscxciui.html

[R34] 退出时清理
来源：http://dali.xylfe.cn/Article/details/gtiwnsuxau.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.aizwys.cn/Article/details/gtwisizdei.html

[R35] 后台执行并等待
来源：http://dali.xuetiantiany.cn/Article/details/gtddbwinyl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhengqikj.top/Article/details/gtlkyfijfh.html

[R36] 并发执行多个任务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlziexkal.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.0kj1m.cn/Article/details/gtdwjzyvri.html

[R37] 把输出赋给变量
来源：http://dali.gzhubu.top/Article/details/gtsqiwnafa.html

files=$(ls -1)
来源：http://dali.0kj1m.cn/Article/details/gtaunreqxy.html

[R38] 管道串联
来源：http://dali.ybcxt.top/Article/details/gtwpxtmfqo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenlongwang.top/Article/details/gttkwquckr.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gtttmnglwl.html

cmd > out.log 2>&1
来源：http://dali.snrcjt.cn/Article/details/gtsxwxynci.html

[R40] 追加写日志
来源：http://dali.feifeiyinyue.top/Article/details/gtxsaxemsm.html

echo "log" >> out.log
来源：http://dali.hfpthk.cn/Article/details/gtuujjxrtu.html

[R41] 丢弃输出
来源：http://dali.ydzc1.top/Article/details/gtcpahyxev.html

cmd >/dev/null 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gtwfvcbvfj.html

[R42] 输入重定向
来源：http://dali.sxryk.cn/Article/details/gtfuliupxq.html

wc -l < a.txt
来源：http://dali.guowangkeji.top/Article/details/gtsgpuiuly.html

[R43] 按名字查找文件
来源：http://dali.nanxinkj.top/Article/details/gtcprrhpjs.html

find . -name "*.log" -type f
来源：http://dali.yuxming.cn/Article/details/gtxwqakeev.html

[R44] 按修改时间查找
来源：http://dali.ivvv.top/Article/details/gtrawrjlbh.html

find . -mtime -7 -type f
来源：http://dali.chenjidiqi.icu/Article/details/gtigapjkhd.html

[R45] 批量删除
来源：http://dali.feifeiyinyue.top/Article/details/gtsiykrgam.html

find . -name "*.tmp" -delete
来源：http://dali.daria6918.cn/Article/details/gtnsucotvq.html

[R46] 递归替换文件内容
来源：http://dali.zhoulong.xyz/Article/details/gtubzptssv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.redwolf501.top/Article/details/gtrxcbezwg.html

[R47] sed 单行替换
来源：http://dali.daxiang520.top/Article/details/gtibvnvgcw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtnmrjijoc.html

[R48] awk 取指定列
来源：http://dali.smart0.xyz/Article/details/gtvwywyjcd.html

awk '{print $1, $3}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtqooxmbqw.html

[R49] awk 带条件
来源：http://dali.jyoumei.cn/Article/details/gtjvoebpfo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hywenlv.cn/Article/details/gtgjoyfuvv.html

[R50] awk 求和
来源：http://dali.chenlongwang.top/Article/details/gtpnmyccrs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.haohaochexian.top/Article/details/gtspccdvqh.html

[R51] 排序去重取前几
来源：http://dali.quarkkingdee.top/Article/details/gtzyhrfxka.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hfpthk.cn/Article/details/gthxrgyria.html

[R52] 统计行数
来源：http://dali.quarkkingdee.top/Article/details/gtjmnvhgzx.html

wc -l a.txt
来源：http://dali.c1oappe.top/Article/details/gtxcsjloeo.html

[R53] 查看文件头与实时尾
来源：http://dali.meibo888.top/Article/details/gtanzxtltl.html


<!-- 参考信息 -->