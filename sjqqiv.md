代发 wailian999

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgnkzxzd.html

[Q07] 删除表
来源：http://dali.jyoumei.cn/Article/details/gtrgryohtq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hywenlv.cn/Article/details/gtqgmsgfor.html

[Q08] 创建普通索引
来源：http://dali.aizwys.cn/Article/details/gtddlrvmyj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tanke756.top/Article/details/gtqqyhlywi.html

[Q09] 创建唯一索引
来源：http://dali.yueranfly.top/Article/details/gteddueami.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgoqhpgg.html

[Q10] 插入单行
来源：http://dali.zdqjudy.top/Article/details/gtjlzgfvqx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj202588.top/Article/details/gtaczvxigl.html

[Q11] 一次插入多行
来源：http://dali.chenjidiqi.icu/Article/details/gtvplybsnf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hysaishi.cn/Article/details/gtpndkcgmt.html

[Q12] 插入后取自增 ID
来源：http://dali.pengpengdd.cyou/Article/details/gtwnawikmw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.haohaochexian.top/Article/details/gtbktssezz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.316326.xyz/Article/details/gtnryardlu.html

[Q13] 忽略重复插入
来源：http://dali.nanxinkj.top/Article/details/gttwbimnii.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pycfn.com/Article/details/gtgsnejsmb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhiwuduotai.top/Article/details/gtfzcazsfx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinqigfzy.top/Article/details/gtqqtehuzx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.guowangkeji.top/Article/details/gtewrokygu.html

[Q15] 查询全部
来源：http://dali.sxryk.cn/Article/details/gtdtfhhkpj.html

SELECT * FROM users;
来源：http://dali.redwolf501.top/Article/details/gtuigjiwih.html

[Q16] 查询指定列
来源：http://dali.tanke756.top/Article/details/gtjeurqvac.html

SELECT id, name FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdawfnhqa.html

[Q17] 条件查询
来源：http://dali.mhx1999.top/Article/details/gtcwuneyxg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258888.top/Article/details/gttyzzmbfv.html

[Q18] 模糊匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtubrisnqu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.aibaodan.cn/Article/details/gtyyckoceb.html

[Q19] 范围查询
来源：http://dali.pengpengdd.cyou/Article/details/gtezgkryak.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.mhx1999.top/Article/details/gttkudycxq.html

[Q20] IN 列表
来源：http://dali.daxiang520.top/Article/details/gtiugtsakw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gtteyieemq.html

[Q21] 空值判断
来源：http://dali.yuanzhike.top/Article/details/gtchdyzbzm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.bjfxy.top/Article/details/gtprgmcsjp.html

[Q22] 排序
来源：http://dali.xuanzx.com/Article/details/gtueszgfev.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nwbrower.top/Article/details/gtlzfqexnl.html

[Q23] 分页
来源：http://dali.bjfxy.top/Article/details/gtldkptaqc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.9152youxi.cn/Article/details/gthvvtapfi.html

[Q24] 去重
来源：http://dali.yj20258888.top/Article/details/gtmdjkcpon.html

SELECT DISTINCT city FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgxgaddn.html

[Q25] 只取前 N 条
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomcelenw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hysaishi.cn/Article/details/gtdnbrzhez.html

[Q26] 计数
来源：http://dali.zycfv.cn/Article/details/gthgzzvfda.html

SELECT COUNT(*) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtwstsuiet.html

[Q27] 条件计数
来源：http://dali.hammf.cn/Article/details/gtmzocumzy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tianlin.xyz/Article/details/gthjdwukug.html

[Q28] 求和与平均
来源：http://dali.nanxinkj.top/Article/details/gtbaqebbnn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gthcihvooq.html

[Q29] 最大最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxprsmkjy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtfecmgljz.html

[Q30] 分组统计
来源：http://dali.yonumen.top/Article/details/gthobiovfc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gthdxycfgt.html

[Q31] 分组后过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdlqpjsl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.kuanghao11.cn/Article/details/gtgydmzafp.html

[Q32] 分组拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gtpgwirxlk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gtqzigobhr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gaohongyu789.top/Article/details/gtstuylfio.html

[Q33] 多列分组
来源：http://dali.hywenlv.cn/Article/details/gtvpzgeeqw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zdqjudy.top/Article/details/gtwukhjdoq.html

[Q34] 每组取第一条
来源：http://dali.hnxiangtu.top/Article/details/gtfjhygzwe.html

SELECT * FROM (
来源：http://dali.haohaochexian.top/Article/details/gtefxkwpch.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.feifeiyinyue.top/Article/details/gtqitzpnrn.html

) t WHERE rn = 1;
来源：http://dali.hnqzz.top/Article/details/gthnxrwlth.html

[Q35] 内连接
来源：http://dali.jqgfzy.top/Article/details/gthmwicyea.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gtryntvhzq.html

[Q36] 左连接
来源：http://dali.jqgufenzy.top/Article/details/gtvqojlfwc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shzxlz.cn/Article/details/gtxlgucjln.html

[Q37] 右连接
来源：http://dali.zhengqikj.top/Article/details/gtaksyfkal.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.9152youxi.cn/Article/details/gtismcavwj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.andypj.xyz/Article/details/gtunatjbhg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fzhhl.top/Article/details/gtawhlmfkr.html

[Q39] 自连接（查上下级）
来源：http://dali.cashguo.top/Article/details/gtvckeretb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cqqwz.cn/Article/details/gtljjvvwqw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gzhubu.top/Article/details/gthgcvwztc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycykuzhz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangshuangyany.cn/Article/details/gtfgwvoknh.html

[Q41] 多表连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotqrfbag.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.316326.xyz/Article/details/gturjjuxyr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxuvkatgl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj202588.top/Article/details/gtewraldje.html

[Q42] 连接条件附加过滤
来源：http://dali.ybcxt.top/Article/details/gtjydjqwiz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yueranfly.top/Article/details/gtgcmoyzkr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gtfxsffauy.html

[Q43] 标量子查询
来源：http://dali.gotoacloud.top/Article/details/gtdbhmivvm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.iojbl.cn/Article/details/gtnwtafrvp.html

[Q44] IN 子查询
来源：http://dali.xziqi.cn/Article/details/gtypkyezdt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yanxiufei.cn/Article/details/gtulntpboy.html

[Q45] EXISTS 判断存在
来源：http://dali.quarkkingdee.top/Article/details/gtaiuvslar.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjsswczg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.havefunace.top/Article/details/gtvbemqeed.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gtxotvbqsj.html

[Q47] 与平均值比较
来源：http://dali.cqqwz.cn/Article/details/gtqhkwfqvo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yuanzhike.top/Article/details/gtdmzqqqjb.html

[Q48] CTE 公用表表达式
来源：http://dali.haohaochexian.top/Article/details/gtqtpnmbul.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhoulong.xyz/Article/details/gtfjhgezxp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.birdmap.top/Article/details/gtmncigayp.html

[Q49] 更新单行
来源：http://dali.yangfankeji.com/Article/details/gtgtlhkyqz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gtdjwkxavk.html

[Q50] 批量更新
来源：http://dali.birdmap.top/Article/details/gtapneqjue.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xinyue.icu/Article/details/gttbogyvwq.html

[Q51] 用子查询更新
来源：http://dali.shzxlz.cn/Article/details/gttcrfhfgt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jianghu66.top/Article/details/gtcipwmopq.html

[Q52] 删除指定行
来源：http://dali.svipenyu.cn/Article/details/gtotkrprsj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gtsvlytqhe.html

[Q53] 按条件删除
来源：http://dali.shzxlz.cn/Article/details/gtundkothf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigufen.top/Article/details/gtmhbyvkvx.html

[Q54] 清空表
来源：http://dali.zycfv.cn/Article/details/gtsttuueoa.html

TRUNCATE TABLE logs;
来源：http://dali.chenjidiqi.icu/Article/details/gtddnjfupw.html

[Q55] 排名（并列占位）
来源：http://dali.fengsongda.top/Article/details/gtqgfwnlrf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tanke756.top/Article/details/gtgbjcakcc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gogol.net.cn/Article/details/gtqteabkqs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yanxiufei.cn/Article/details/gtrzyfmnca.html

[Q57] 行号
来源：http://dali.cashguo.top/Article/details/gtmzmjjfzg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtnlvemhqu.html

[Q58] 累计求和
来源：http://dali.aizwys.cn/Article/details/gtsrocpveg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtviliqguk.html

[Q59] 分组内累计
来源：http://dali.mhx1999.top/Article/details/gtszwiwboe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtovxpoqsk.html

[Q60] 取上一行 / 下一行
来源：http://dali.smart0.xyz/Article/details/gthnhzwlfk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hammf.cn/Article/details/gttcnjtjbp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258.top/Article/details/gtnzilrguv.html

[Q61] 移动平均
来源：http://dali.0kj1m.cn/Article/details/gtgqrvxtge.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqgcysix.html

[Q62] 分组占比
来源：http://dali.sufxvd.cn/Article/details/gtnwyochmo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gtsbzjiamc.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gtzvafpkpc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.mhx1999.top/Article/details/gtjhtbevmx.html

[Q64] 提交事务
来源：http://dali.birdmap.top/Article/details/gtroylyvwi.html

COMMIT;
来源：http://dali.nwbrower.top/Article/details/gtflomwxtx.html

[Q65] 回滚事务
来源：http://dali.jqgfzy.top/Article/details/gtgpytieoy.html

ROLLBACK;
来源：http://dali.tian-w.cn/Article/details/gttdxkccgn.html

[Q66] 行锁查询
来源：http://dali.xuetiantiany.cn/Article/details/gtddakeuft.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sysykeji.top/Article/details/gttydgadhq.html

[Q67] 设置隔离级别
来源：http://dali.yvedp.cn/Article/details/gtazefrftj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgfzy.top/Article/details/gtxzvakcwp.html

[Q68] 保存点
来源：http://dali.tanke756.top/Article/details/gtwahsiimv.html

SAVEPOINT sp1;
来源：http://dali.cucudq.cn/Article/details/gtjzgylohx.html

ROLLBACK TO sp1;
来源：http://dali.svipenyu.cn/Article/details/gtbxhtuhhk.html

[Q69] 查看执行计划
来源：http://dali.c1oappe.top/Article/details/gtntrhveud.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrjvbuck.html

[Q70] 更新统计信息
来源：http://dali.shanyushiyangtech.top/Article/details/gtogimtdlc.html

ANALYZE TABLE users;
来源：http://dali.jinqigfzy.top/Article/details/gtkxcccawz.html

[Q71] 查看建表语句
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetaxibsw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yonumen.top/Article/details/gtpbhzkpjq.html

[Q72] 查看索引
来源：http://dali.svipenyu.cn/Article/details/gtgpkvqqcw.html

SHOW INDEX FROM users;
来源：http://dali.hnqzz.top/Article/details/gtzwamjrqi.html

[Q73] 查看表状态
来源：http://dali.hongshengwenyu.top/Article/details/gtnzxcnxhk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.316326.xyz/Article/details/gtfwmfycub.html

[Q74] 强制使用索引
来源：http://dali.yanxiufei.cn/Article/details/gtunyzzfbs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shangyingyoupin.top/Article/details/gttyqdygru.html

[Q75] 日期格式化
来源：http://dali.sufxvd.cn/Article/details/gtbvmbdxzm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtkgllcbnl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangtech.top/Article/details/gthlgrxjmy.html

[Q76] 按天统计
来源：http://dali.hysaishi.cn/Article/details/gttdwhxdeh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xziqi.cn/Article/details/gtzzbpifkm.html

[Q77] 时间加减
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtuhoxva.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cashguo.top/Article/details/gtpbotabed.html

[Q78] 当前时间
来源：http://dali.gogol.net.cn/Article/details/gtjrhfwowd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhoulong.xyz/Article/details/gtnvdenlpe.html

[Q79] 字符串拼接
来源：http://dali.ybcxt.top/Article/details/gtsyajbivs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.redwolf501.top/Article/details/gtkmsehmwj.html

[Q80] 字符串截取
来源：http://dali.haohaochexian.top/Article/details/gtagrtawuv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtowhjdyta.html

[Q81] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gtusuirnve.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtkatyvsme.html

[Q82] 字符长度与字节长度
来源：http://dali.zhixingplan.top/Article/details/gtoafhuswt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtxqdsptvp.html

[Q83] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gtxqjaaeai.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtqyptambd.html

[Q84] 去除首尾空格
来源：http://dali.zhiwuduotai.top/Article/details/gtbdgqdprc.html

SELECT TRIM(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhqbrqnw.html

[Q85] 数值取整
来源：http://dali.hongshengwenyu.top/Article/details/gtrryalhxn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sufxvd.cn/Article/details/gtoaxgwglv.html

[Q86] 读取 JSON 字段
来源：http://dali.haohaochexian.top/Article/details/gtvvlvrosi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gtrxtxwnvo.html

[Q87] JSON 字段做条件
来源：http://dali.chenjidiqi.icu/Article/details/gtlmurzgef.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangdashe.top/Article/details/gttlkljuae.html

[Q88] 行转列（条件聚合）
来源：http://dali.shuidangran.top/Article/details/gtyziijcrt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvthbapxk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtpzmwbhyb.html

[Q89] 判断表是否存在
来源：http://dali.mhx1999.top/Article/details/gtmygsmlhb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.0kj1m.cn/Article/details/gtnxbdgema.html

[Q90] 生成序号列
来源：http://dali.yuanzhike.top/Article/details/gtydoymwtn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.9152youxi.cn/Article/details/gtdtyjzqwz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtpzsvezbo.html

R. Bash 专题
来源：http://dali.feifeiyinyue.top/Article/details/gtrppmxnjh.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtbobfltou.html

[R01] shebang 与严格模式
来源：http://dali.yuanzhike.top/Article/details/gtfiunqtpt.html

#!/usr/bin/env bash
来源：http://dali.jlsjyb.cn/Article/details/gtzxtiklpe.html

set -euo pipefail
来源：http://dali.sxryk.cn/Article/details/gtvfjkhart.html

[R02] 变量赋值与使用
来源：http://dali.sxryk.cn/Article/details/gtlgufpxcm.html

name="Tom"; echo "$name"
来源：http://dali.zhengqikj.top/Article/details/gtboytlrvz.html

[R03] 只读变量
来源：http://dali.svipenyu.cn/Article/details/gtxqutmwub.html

readonly PI=3.14
来源：http://dali.xuanzx.com/Article/details/gtinegnxyr.html

[R04] 位置参数
来源：http://dali.ppjwa.cn/Article/details/gtygkshwdu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yonumen.top/Article/details/gtdzuigigt.html

[R05] 参数默认值
来源：http://dali.gzhubu.top/Article/details/gtlfuuyzzu.html

name="${1:-default}"
来源：http://dali.haohaochexian.top/Article/details/gtllsqyrll.html

[R06] 判断命令是否存在
来源：http://dali.316326.xyz/Article/details/gtuhkogmvh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenzaomai.com/Article/details/gtddibjvod.html

[R07] if 判断文件
来源：http://dali.zdqjudy.top/Article/details/gtjsctfazl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj20258888.top/Article/details/gtunvhusna.html

[R08] 数值比较
来源：http://dali.dashuyun.cn/Article/details/gtwjnaerwi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yueranfly.top/Article/details/gtegzhhmqe.html

[R09] 字符串比较
来源：http://dali.xziqi.cn/Article/details/gtvloagehj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtwegyuptc.html

[R10] 正则匹配
来源：http://dali.sweek.top/Article/details/gtqkfyvfka.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ydzc1.top/Article/details/gtclugwubq.html

[R11] case 多分支
来源：http://dali.hysaishi.cn/Article/details/gtmlpmansz.html

case "$1" in
来源：http://dali.daria6918.cn/Article/details/gtcxvgpowg.html

start) echo "启动" ;;
来源：http://dali.yuanzhike.top/Article/details/gtyreikznj.html

stop)  echo "停止" ;;
来源：http://dali.guowangkeji.top/Article/details/gtlarrmcdz.html

*)     echo "未知命令" ;;
来源：http://dali.fzhhl.top/Article/details/gtudkitwoa.html

esac
来源：http://dali.gotoacloud.top/Article/details/gtxwdckfmo.html

[R12] for 遍历文件
来源：http://dali.shangyingyoupin.top/Article/details/gtedvqiqik.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtpmobnbmw.html

[R13] for 计数循环
来源：http://dali.ivvv.top/Article/details/gtisfxtneb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj20258888.top/Article/details/gtetxobsge.html

[R14] C 风格 for
来源：http://dali.tanke756.top/Article/details/gtcueilxfs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxoookfhl.html

[R15] while 逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gthvgucvgs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jlsjyb.cn/Article/details/gtpphewqqy.html

[R16] until 等待条件
来源：http://dali.xziqi.cn/Article/details/gtvubsther.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gtmhzbkdbu.html

[R17] 数组定义与取值
来源：http://dali.haohaochexian.top/Article/details/gtfolwsldm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigufen.top/Article/details/gtxpsrqegq.html

[R18] 遍历数组
来源：http://dali.xinyue.icu/Article/details/gteouudwbz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dashuyun.cn/Article/details/gtihyqmyzd.html

[R19] 数组长度
来源：http://dali.guowangkeji.top/Article/details/gtyzxrnvjx.html

echo "${#arr[@]}"
来源：http://dali.yvedp.cn/Article/details/gteekkxjzq.html

[R20] 关联数组（字典）
来源：http://dali.9152youxi.cn/Article/details/gtelncxpqw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozmnyfhu.html

[R21] 字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gtwpcjeyct.html

echo "${#s}"
来源：http://dali.yanxiufei.cn/Article/details/gtpefxqdyb.html

[R22] 截取子串
来源：http://dali.cqqwz.cn/Article/details/gtudzbatwc.html

echo "${s:0:5}"
来源：http://dali.smart0.xyz/Article/details/gtaueuxoll.html

[R23] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gtneuatnun.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuxming.cn/Article/details/gtnjlnuqda.html

[R24] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gttpxnxkfa.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sufxvd.cn/Article/details/gtxrbpttwp.html

[R25] 去后缀 / 去前缀
来源：http://dali.hfpthk.cn/Article/details/gtruowdqvz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnxiangtu.top/Article/details/gtrqtwmyoo.html

[R26] 命令替换
来源：http://dali.jqgfzy.top/Article/details/gtyximozpv.html

now=$(date +%F); echo "$now"
来源：http://dali.feifeiyinyue.top/Article/details/gtrlroeazs.html

[R27] 算术展开
来源：http://dali.jinghuilouyu.cn/Article/details/gtznlphnxx.html

echo $((1 + 2 * 3))
来源：http://dali.chenzaomai.com/Article/details/gtnuvtufma.html

[R28] 浮点运算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnoszaol.html

echo "scale=2; 10/3" | bc
来源：http://dali.kuanghao11.cn/Article/details/gtndnopdrn.html

[R29] 定义函数
来源：http://dali.snrcjt.cn/Article/details/gtouzoigsk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.haohaochexian.top/Article/details/gtswikauyi.html

[R30] 函数返回状态码
来源：http://dali.chenzaomai.com/Article/details/gtovplfsfm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgufenzy.top/Article/details/gtqwttlwtp.html

[R31] 局部变量
来源：http://dali.daria6918.cn/Article/details/gtoouwvldj.html

f() { local x=1; echo "$x"; }
来源：http://dali.havefunace.top/Article/details/gtyrrhkeud.html

[R32] 参数个数校验
来源：http://dali.xuanzx.com/Article/details/gtndaifzql.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ydzc1.top/Article/details/gtszfkeadz.html

[R33] 捕获错误并提示行号
来源：http://dali.zhoulong.xyz/Article/details/gtaaxrzhin.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.0kj1m.cn/Article/details/gttssmiurx.html

[R34] 退出时清理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhdcacjx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gtwmriicdv.html

[R35] 后台执行并等待
来源：http://dali.ppjwa.cn/Article/details/gtybmdzdbu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ivvv.top/Article/details/gtpwnmjsnv.html

[R36] 并发执行多个任务
来源：http://dali.guowangkeji.top/Article/details/gthywouaxd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yangfankeji.com/Article/details/gtowxwqpne.html

[R37] 把输出赋给变量
来源：http://dali.tian-w.cn/Article/details/gtlrgahfwc.html

files=$(ls -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtmonflusj.html

[R38] 管道串联
来源：http://dali.cheryme.top/Article/details/gtaktmpukk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guowangkeji.top/Article/details/gtyhewpsuz.html

[R39] 重定向标准输出与错误
来源：http://dali.dianchejie.cn/Article/details/gtehpoeaho.html

cmd > out.log 2>&1
来源：http://dali.hnqzz.top/Article/details/gtfcjtymiz.html

[R40] 追加写日志
来源：http://dali.tian-w.cn/Article/details/gttwyfbstt.html

echo "log" >> out.log
来源：http://dali.sweek.top/Article/details/gtspvaczph.html

[R41] 丢弃输出
来源：http://dali.yuanzhike.top/Article/details/gtiiziiugo.html

cmd >/dev/null 2>&1
来源：http://dali.pycfn.com/Article/details/gtfljbxbxm.html

[R42] 输入重定向
来源：http://dali.cheryme.top/Article/details/gtivorbsfh.html

wc -l < a.txt
来源：http://dali.birdmap.top/Article/details/gtgpwlcbic.html

[R43] 按名字查找文件
来源：http://dali.tanke756.top/Article/details/gtidnmmjqd.html

find . -name "*.log" -type f
来源：http://dali.mhx1999.top/Article/details/gtxdjiaqge.html

[R44] 按修改时间查找
来源：http://dali.cashguo.top/Article/details/gtvxyfohfq.html

find . -mtime -7 -type f
来源：http://dali.wangdashe.top/Article/details/gtlpqjjalv.html

[R45] 批量删除
来源：http://dali.havefunace.top/Article/details/gtujmeqxuv.html

find . -name "*.tmp" -delete
来源：http://dali.jinqigfzy.top/Article/details/gtpmkyrgxo.html

[R46] 递归替换文件内容
来源：http://dali.hongshengwenyu.top/Article/details/gtmtkxijtc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gzhubu.top/Article/details/gtewofanej.html

[R47] sed 单行替换
来源：http://dali.zycfv.cn/Article/details/gtkqqtebwq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtsjumalwu.html

[R48] awk 取指定列
来源：http://dali.yuanzhike.top/Article/details/gtjmrhguwx.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gtxzsbtxem.html

[R49] awk 带条件
来源：http://dali.haohaochexian.top/Article/details/gtoeynnogk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.iojbl.cn/Article/details/gtwvnyqanv.html

[R50] awk 求和
来源：http://dali.jinqigufen.top/Article/details/gtbuiqdxvv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tian-w.cn/Article/details/gtwsextpto.html

[R51] 排序去重取前几
来源：http://dali.aizwys.cn/Article/details/gthwyqhvzf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.316326.xyz/Article/details/gttwffmhgn.html

[R52] 统计行数
来源：http://dali.aibaodan.cn/Article/details/gtngjeheqi.html

wc -l a.txt
来源：http://dali.cheryme.top/Article/details/gtyavciuug.html

[R53] 查看文件头与实时尾
来源：http://dali.xziqi.cn/Article/details/gtblabpnet.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgfzy.top/Article/details/gtrgohbbcy.html

[R54] 比较两个文件
来源：http://dali.wangdashe.top/Article/details/gtdjfzmajs.html

diff a.txt b.txt
来源：http://dali.yj202588.top/Article/details/gtzjttxnmz.html

[R55] 压缩与解压
来源：http://dali.yj20258.top/Article/details/gttfhaudme.html


<!-- 参考信息 -->