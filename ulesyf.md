代发 wailian999

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenjidiqi.icu/Article/details/gtydibuume.html

[Q07] 删除表
来源：http://dali.cdnleiting.top/Article/details/gtnptialac.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zycfv.cn/Article/details/gtqxkvobmm.html

[Q08] 创建普通索引
来源：http://dali.dashuyun.cn/Article/details/gtsfshbcym.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.iojbl.cn/Article/details/gtlhbvywvy.html

[Q09] 创建唯一索引
来源：http://dali.xuanzx.com/Article/details/gtbdljqkfz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gtetlmjesp.html

[Q10] 插入单行
来源：http://dali.shzxlz.cn/Article/details/gtokryjcth.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jianghu66.top/Article/details/gtpvltrwqk.html

[Q11] 一次插入多行
来源：http://dali.yueranfly.top/Article/details/gtxjmvylxg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cucudq.cn/Article/details/gtajwonluf.html

[Q12] 插入后取自增 ID
来源：http://dali.dianchejie.cn/Article/details/gtrebannvl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinqigfzy.top/Article/details/gtnxmphcxg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.quarkkingdee.top/Article/details/gttjyobvtr.html

[Q13] 忽略重复插入
来源：http://dali.zdqjudy.top/Article/details/gtfpfuqpav.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yueranfly.top/Article/details/gtdduvqgur.html

[Q14] 存在则更新（upsert）
来源：http://dali.wangdashe.top/Article/details/gteazefvxg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fzhhl.top/Article/details/gteerrriks.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sweek.top/Article/details/gtqtnlvsnb.html

[Q15] 查询全部
来源：http://dali.haohaochexian.top/Article/details/gtmvxxglnv.html

SELECT * FROM users;
来源：http://dali.xuanzx.com/Article/details/gtmuybhyzp.html

[Q16] 查询指定列
来源：http://dali.gogol.net.cn/Article/details/gtwrgcmler.html

SELECT id, name FROM users;
来源：http://dali.bjfxy.top/Article/details/gtromftwrg.html

[Q17] 条件查询
来源：http://dali.yj20258.top/Article/details/gtkjtmklbs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yanxiufei.cn/Article/details/gttuqvuigr.html

[Q18] 模糊匹配
来源：http://dali.meibo888.top/Article/details/gtsllbrjiv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinqigufen.top/Article/details/gtwtiflstt.html

[Q19] 范围查询
来源：http://dali.316326.xyz/Article/details/gtjrfuwcwm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gogol.net.cn/Article/details/gttpwytcfm.html

[Q20] IN 列表
来源：http://dali.tianlin.xyz/Article/details/gtiumysfga.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.mhx1999.top/Article/details/gtvpqmhnbs.html

[Q21] 空值判断
来源：http://dali.hysaishi.cn/Article/details/gtyiqhzupr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gotoacloud.top/Article/details/gtvrghqhkg.html

[Q22] 排序
来源：http://dali.hfpthk.cn/Article/details/gtlshtxkdc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.wangdashe.top/Article/details/gtjllrdkmk.html

[Q23] 分页
来源：http://dali.9152youxi.cn/Article/details/gtzomommgu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuanzhike.top/Article/details/gtyayjnlvl.html

[Q24] 去重
来源：http://dali.chenzaomai.com/Article/details/gtnlnqevbl.html

SELECT DISTINCT city FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtnsfihvit.html

[Q25] 只取前 N 条
来源：http://dali.wangdashe.top/Article/details/gtusmchpne.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinqigufen.top/Article/details/gtdwmzmmlt.html

[Q26] 计数
来源：http://dali.daxiang520.top/Article/details/gtmjumfuml.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj202588.top/Article/details/gteahktrte.html

[Q27] 条件计数
来源：http://dali.yvedp.cn/Article/details/gtnsxqpeod.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ivvv.top/Article/details/gtyxnesqlp.html

[Q28] 求和与平均
来源：http://dali.zhixingplan.top/Article/details/gtxicomtip.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtihcdvhby.html

[Q29] 最大最小值
来源：http://dali.jyoumei.cn/Article/details/gtirwjpsyv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtoaylrjik.html

[Q30] 分组统计
来源：http://dali.yuanzhike.top/Article/details/gtqcivjheb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtkvpyfifv.html

[Q31] 分组后过滤
来源：http://dali.zhixingplan.top/Article/details/gtwyeebwqd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.haohaochexian.top/Article/details/gtpzvtppex.html

[Q32] 分组拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcipapmgt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtgsjhidne.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.aizwys.cn/Article/details/gtibidyxwm.html

[Q33] 多列分组
来源：http://dali.chenzaomai.com/Article/details/gtpgfpqxnr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj202588.top/Article/details/gtgbnolkmx.html

[Q34] 每组取第一条
来源：http://dali.kuanghao11.cn/Article/details/gtkxjxjhae.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gtjdelcdvt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.daria6918.cn/Article/details/gtdqqneqvo.html

) t WHERE rn = 1;
来源：http://dali.hammf.cn/Article/details/gtndauvgna.html

[Q35] 内连接
来源：http://dali.gzhubu.top/Article/details/gtpphcbpvo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gtexuufmis.html

[Q36] 左连接
来源：http://dali.sweek.top/Article/details/gtduqacnik.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zdqjudy.top/Article/details/gtfxedshiq.html

[Q37] 右连接
来源：http://dali.gotoacloud.top/Article/details/gtvgbzsaby.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuanzx.com/Article/details/gtwqysgsfa.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cdnleiting.top/Article/details/gthcxtxeiy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.dianchejie.cn/Article/details/gtevdkdptf.html

[Q39] 自连接（查上下级）
来源：http://dali.chenzaomai.com/Article/details/gtnolqastv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dashuyun.cn/Article/details/gtdlohalph.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuxming.cn/Article/details/gtqpvowltr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.9152youxi.cn/Article/details/gtbyglxash.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ydzc1.top/Article/details/gtddokixyo.html

[Q41] 多表连接
来源：http://dali.ydzc1.top/Article/details/gtkhitebai.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj20258888.top/Article/details/gtrclobvtw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sufxvd.cn/Article/details/gtwfngnwoh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpoweidl.html

[Q42] 连接条件附加过滤
来源：http://dali.hywenlv.cn/Article/details/gtzchzivpn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yuxming.cn/Article/details/gtfrrwqqrc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.bjfxy.top/Article/details/gtobcgwmjz.html

[Q43] 标量子查询
来源：http://dali.wangdashe.top/Article/details/gtaxvcxhci.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenzaomai.com/Article/details/gtgedlzzpj.html

[Q44] IN 子查询
来源：http://dali.gzhubu.top/Article/details/gtonbzjhuu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigfzy.top/Article/details/gtddkcusuu.html

[Q45] EXISTS 判断存在
来源：http://dali.ppjwa.cn/Article/details/gteiqfqpvn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenlongwang.top/Article/details/gtubfkwlxe.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhongyouzk.top/Article/details/gtjfcnhxbj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gtizqkknvo.html

[Q47] 与平均值比较
来源：http://dali.xinyue.icu/Article/details/gtuumajizw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.birdmap.top/Article/details/gtlkldhjvh.html

[Q48] CTE 公用表表达式
来源：http://dali.yonumen.top/Article/details/gtocoqrwco.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuanzhike.top/Article/details/gtqihvrpmp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxuanxn.top/Article/details/gtiytyfjth.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gtbnwtooxf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.andypj.xyz/Article/details/gtozyagcbc.html

[Q50] 批量更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxmhnrld.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.smart0.xyz/Article/details/gtyuoqpjjy.html

[Q51] 用子查询更新
来源：http://dali.jinqigfzy.top/Article/details/gttvawgjrj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sxryk.cn/Article/details/gtsyauoycb.html

[Q52] 删除指定行
来源：http://dali.zhengqikj.top/Article/details/gttmmxbihu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.dashuyun.cn/Article/details/gtdllomrbt.html

[Q53] 按条件删除
来源：http://dali.cashguo.top/Article/details/gterttqpmk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenlongwang.top/Article/details/gtkxktyovo.html

[Q54] 清空表
来源：http://dali.birdmap.top/Article/details/gtwueztkui.html

TRUNCATE TABLE logs;
来源：http://dali.hywenlv.cn/Article/details/gtfaydivbh.html

[Q55] 排名（并列占位）
来源：http://dali.hywenlv.cn/Article/details/gtomdixcpu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jyoumei.cn/Article/details/gtndblihup.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jlsjyb.cn/Article/details/gtjwccubvm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gtglupktgr.html

[Q57] 行号
来源：http://dali.jinqigufen.top/Article/details/gtdkplcmki.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtxzlnmmep.html

[Q58] 累计求和
来源：http://dali.316326.xyz/Article/details/gthetalbjr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtboqxdgzv.html

[Q59] 分组内累计
来源：http://dali.yuanzhike.top/Article/details/gtgdywuzpz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtrjkforlv.html

[Q60] 取上一行 / 下一行
来源：http://dali.daxiang520.top/Article/details/gtjffpfuvj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.birdmap.top/Article/details/gtnmtmfqtm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtkrygjxtw.html

[Q61] 移动平均
来源：http://dali.hammf.cn/Article/details/gtptsrevtv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtylktngmc.html

[Q62] 分组占比
来源：http://dali.pycfn.com/Article/details/gtkotqadqh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtimzqlklq.html

[Q63] 开启事务
来源：http://dali.aibaodan.cn/Article/details/gtwzvgsgod.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tianlin.xyz/Article/details/gtqdclncic.html

[Q64] 提交事务
来源：http://dali.chenlongwang.top/Article/details/gtylkbpzbj.html

COMMIT;
来源：http://dali.sweek.top/Article/details/gtgatvzxhp.html

[Q65] 回滚事务
来源：http://dali.ydzc1.top/Article/details/gthwzmkpdh.html

ROLLBACK;
来源：http://dali.jinqigufen.top/Article/details/gtnkmbtzpi.html

[Q66] 行锁查询
来源：http://dali.wangdashe.top/Article/details/gthhlmtbhj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xinyue.icu/Article/details/gtkusbwqaz.html

[Q67] 设置隔离级别
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnsucwzky.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ydzc1.top/Article/details/gtjnlhibez.html

[Q68] 保存点
来源：http://dali.sxryk.cn/Article/details/gtnahndbtd.html

SAVEPOINT sp1;
来源：http://dali.ydzc1.top/Article/details/gtfmusyaih.html

ROLLBACK TO sp1;
来源：http://dali.snrcjt.cn/Article/details/gtirsnlgvt.html

[Q69] 查看执行计划
来源：http://dali.gzhubu.top/Article/details/gtzzqreyfj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhengqikj.top/Article/details/gtxkipmiqh.html

[Q70] 更新统计信息
来源：http://dali.gzhubu.top/Article/details/gtrptyvbxd.html

ANALYZE TABLE users;
来源：http://dali.meibo888.top/Article/details/gtzfzjlnrx.html

[Q71] 查看建表语句
来源：http://dali.mhx1999.top/Article/details/gtililojax.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hfpthk.cn/Article/details/gtlnjtzuyk.html

[Q72] 查看索引
来源：http://dali.chenlongwang.top/Article/details/gtjzsirsvg.html

SHOW INDEX FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtgmrgvamb.html

[Q73] 查看表状态
来源：http://dali.yongpay.top/Article/details/gtwkajikfe.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.316326.xyz/Article/details/gtozhibtkf.html

[Q74] 强制使用索引
来源：http://dali.xuanzx.com/Article/details/gtculfkzld.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangshuangyany.cn/Article/details/gtrftqsxga.html

[Q75] 日期格式化
来源：http://dali.ehwqpu.com/Article/details/gtivbmgpof.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj202588.top/Article/details/gtehpkdnbl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.0kj1m.cn/Article/details/gtqokmybjk.html

[Q76] 按天统计
来源：http://dali.tian-w.cn/Article/details/gtsxsastdb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cqqwz.cn/Article/details/gtvzqhznvk.html

[Q77] 时间加减
来源：http://dali.nanxinkj.top/Article/details/gtkrrzjfkb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhoulong.xyz/Article/details/gtsvqdmmbs.html

[Q78] 当前时间
来源：http://dali.sufxvd.cn/Article/details/gtjrnyltot.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxuanxn.top/Article/details/gtcjlrczzr.html

[Q79] 字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gtctabljkm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.dianchejie.cn/Article/details/gtohohcupl.html

[Q80] 字符串截取
来源：http://dali.daria6918.cn/Article/details/gtpqtdkwgw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtsmayrfmd.html

[Q81] 字符串替换
来源：http://dali.kuanghao11.cn/Article/details/gtroipgtnn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtguruknaq.html

[Q82] 字符长度与字节长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdrwcevv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtqkwantng.html

[Q83] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtfdqmkrxh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtshdxbuvw.html

[Q84] 去除首尾空格
来源：http://dali.tanke756.top/Article/details/gtwjbjgkwl.html

SELECT TRIM(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gtxlraiedi.html

[Q85] 数值取整
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnqzqght.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gtmoiatuiu.html

[Q86] 读取 JSON 字段
来源：http://dali.iojbl.cn/Article/details/gtwncycetn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shangyingyoupin.top/Article/details/gtkwcamkdf.html

[Q87] JSON 字段做条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gticmpfkki.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hysaishi.cn/Article/details/gtrpyeubyf.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaotszydd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinghuilouyu.cn/Article/details/gtpizzxjri.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daxiang520.top/Article/details/gtuwewvdma.html

[Q89] 判断表是否存在
来源：http://dali.c1oappe.top/Article/details/gtxbbadboq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.316326.xyz/Article/details/gtrhmftbqe.html

[Q90] 生成序号列
来源：http://dali.ydzc1.top/Article/details/gtrwfeidiw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jqgfzy.top/Article/details/gtdjmtsdxd.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtxhpxenkp.html

R. Bash 专题
来源：http://dali.hnxiangtu.top/Article/details/gtglfjzqie.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtwflixbjl.html

[R01] shebang 与严格模式
来源：http://dali.cashguo.top/Article/details/gtubxverct.html

#!/usr/bin/env bash
来源：http://dali.quarkkingdee.top/Article/details/gtkwchlljy.html

set -euo pipefail
来源：http://dali.cqqwz.cn/Article/details/gtimvkyaal.html

[R02] 变量赋值与使用
来源：http://dali.316326.xyz/Article/details/gtgcfkzhqe.html

name="Tom"; echo "$name"
来源：http://dali.haohaochexian.top/Article/details/gtolpndthc.html

[R03] 只读变量
来源：http://dali.daria6918.cn/Article/details/gtpemjsymn.html

readonly PI=3.14
来源：http://dali.316326.xyz/Article/details/gtxtbnihen.html

[R04] 位置参数
来源：http://dali.hfpthk.cn/Article/details/gtqyzgtpnl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuanzx.com/Article/details/gtzzvqtdua.html

[R05] 参数默认值
来源：http://dali.ydzc1.top/Article/details/gtmaiwgqck.html

name="${1:-default}"
来源：http://dali.yongpay.top/Article/details/gtniwsubzn.html

[R06] 判断命令是否存在
来源：http://dali.ivvv.top/Article/details/gtakyzpvox.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gtaifjjwxi.html

[R07] if 判断文件
来源：http://dali.gaohongyu789.top/Article/details/gtscvhvndt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gotoacloud.top/Article/details/gtabobclnr.html

[R08] 数值比较
来源：http://dali.shangyingyoupin.top/Article/details/gtzifjinlb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenzaomai.com/Article/details/gtgcnhssja.html

[R09] 字符串比较
来源：http://dali.haohaochexian.top/Article/details/gtylkuaffr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ydzc1.top/Article/details/gtkdegvdgy.html

[R10] 正则匹配
来源：http://dali.cucudq.cn/Article/details/gtzaxocjep.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.meibo888.top/Article/details/gtvbommhmp.html

[R11] case 多分支
来源：http://dali.shangyingyoupin.top/Article/details/gtnmnuunzi.html

case "$1" in
来源：http://dali.xylfe.cn/Article/details/gtkkidwgci.html

start) echo "启动" ;;
来源：http://dali.zhongyouzk.top/Article/details/gtkqrykbxc.html

stop)  echo "停止" ;;
来源：http://dali.zhoulong.xyz/Article/details/gtbbbuhmuc.html

*)     echo "未知命令" ;;
来源：http://dali.dashuyun.cn/Article/details/gtcomulrjk.html

esac
来源：http://dali.ybcxt.top/Article/details/gtmlpcnefo.html

[R12] for 遍历文件
来源：http://dali.cqqwz.cn/Article/details/gturlocsmj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gaohongyu789.top/Article/details/gtrpdxpqgp.html

[R13] for 计数循环
来源：http://dali.pycfn.com/Article/details/gtnibgyicy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zycfv.cn/Article/details/gtfgtkwayk.html

[R14] C 风格 for
来源：http://dali.dianchejie.cn/Article/details/gtnvceaowr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.9152youxi.cn/Article/details/gtfxjdrmsl.html

[R15] while 逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtowbykfwj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.andypj.xyz/Article/details/gtelewrymz.html

[R16] until 等待条件
来源：http://dali.vqdsnc.cn/Article/details/gtdouggaea.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.feifeiyinyue.top/Article/details/gtsalgsdgz.html

[R17] 数组定义与取值
来源：http://dali.guannengcc.top/Article/details/gtflvtzjge.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cashguo.top/Article/details/gtqzkddsss.html

[R18] 遍历数组
来源：http://dali.tanke756.top/Article/details/gtznzxihmz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jyoumei.cn/Article/details/gtgawlcizi.html

[R19] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gtwvrdyvtw.html

echo "${#arr[@]}"
来源：http://dali.fzhhl.top/Article/details/gttstdsyht.html

[R20] 关联数组（字典）
来源：http://dali.ppjwa.cn/Article/details/gtpivipadf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jiagoushi.top/Article/details/gtbfltqmjc.html

[R21] 字符串长度
来源：http://dali.sufxvd.cn/Article/details/gtejgoujhe.html

echo "${#s}"
来源：http://dali.zycfv.cn/Article/details/gtssgbhglj.html

[R22] 截取子串
来源：http://dali.mhx1999.top/Article/details/gtwzurexoy.html

echo "${s:0:5}"
来源：http://dali.aibaodan.cn/Article/details/gtgrjvqtso.html

[R23] 字符串替换
来源：http://dali.shuidangran.top/Article/details/gtdnqdpdgt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sufxvd.cn/Article/details/gtstwrzabu.html

[R24] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gttkonuhtu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yueranfly.top/Article/details/gtuvgzvzrh.html

[R25] 去后缀 / 去前缀
来源：http://dali.svipenyu.cn/Article/details/gtyfyopnjo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pycfn.com/Article/details/gtubfwwpam.html

[R26] 命令替换
来源：http://dali.pycfn.com/Article/details/gtaairnliy.html

now=$(date +%F); echo "$now"
来源：http://dali.zhoulong.xyz/Article/details/gtwuwigdye.html

[R27] 算术展开
来源：http://dali.svipenyu.cn/Article/details/gtrhgwjzlh.html

echo $((1 + 2 * 3))
来源：http://dali.hnxiangtu.top/Article/details/gtxuafksmg.html

[R28] 浮点运算
来源：http://dali.feifeiyinyue.top/Article/details/gtiqpklsgf.html

echo "scale=2; 10/3" | bc
来源：http://dali.fengsongda.top/Article/details/gtjfarqqpq.html

[R29] 定义函数
来源：http://dali.hysaishi.cn/Article/details/gtgoarkgws.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cashguo.top/Article/details/gtrvegpfbg.html

[R30] 函数返回状态码
来源：http://dali.xuanzx.com/Article/details/gtubrwkhmn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj20258888.top/Article/details/gtwpuvlugg.html

[R31] 局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gtywwawxje.html

f() { local x=1; echo "$x"; }
来源：http://dali.hywenlv.cn/Article/details/gtuxpajrru.html

[R32] 参数个数校验
来源：http://dali.mhx1999.top/Article/details/gttqoyfyap.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gtbnqolpzi.html

[R33] 捕获错误并提示行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecrvzdva.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nwbrower.top/Article/details/gtpmvkzxyh.html

[R34] 退出时清理
来源：http://dali.hysaishi.cn/Article/details/gtzqyvbivp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258.top/Article/details/gtkxdbtaoh.html

[R35] 后台执行并等待
来源：http://dali.zhongyouzk.top/Article/details/gtpqclfdlt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.9152youxi.cn/Article/details/gthfjhaavb.html

[R36] 并发执行多个任务
来源：http://dali.quarkkingdee.top/Article/details/gtqwduzszx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shzxlz.cn/Article/details/gthqfdpepd.html

[R37] 把输出赋给变量
来源：http://dali.kuanghao11.cn/Article/details/gtvkiipojx.html

files=$(ls -1)
来源：http://dali.xinyue.icu/Article/details/gtfsbsdses.html

[R38] 管道串联
来源：http://dali.pycfn.com/Article/details/gtfsohphiv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jlsjyb.cn/Article/details/gteejzckgk.html

[R39] 重定向标准输出与错误
来源：http://dali.zhongyouzk.top/Article/details/gtxciukfeh.html

cmd > out.log 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gtsapiucav.html

[R40] 追加写日志
来源：http://dali.cheryme.top/Article/details/gthtqrerdx.html

echo "log" >> out.log
来源：http://dali.jyoumei.cn/Article/details/gtesczlpku.html

[R41] 丢弃输出
来源：http://dali.feifeiyinyue.top/Article/details/gtwqmywlyo.html

cmd >/dev/null 2>&1
来源：http://dali.dashuyun.cn/Article/details/gtdetjugri.html

[R42] 输入重定向
来源：http://dali.yj202588.top/Article/details/gterndrdbn.html

wc -l < a.txt
来源：http://dali.jianghu66.top/Article/details/gtysphnahx.html

[R43] 按名字查找文件
来源：http://dali.bjfxy.top/Article/details/gtxsndfnak.html

find . -name "*.log" -type f
来源：http://dali.xinyue.icu/Article/details/gtlvyawtij.html

[R44] 按修改时间查找
来源：http://dali.havefunace.top/Article/details/gtphjkbqei.html

find . -mtime -7 -type f
来源：http://dali.ydzc1.top/Article/details/gtvvxxwzme.html

[R45] 批量删除
来源：http://dali.hysaishi.cn/Article/details/gtpmsdurhq.html

find . -name "*.tmp" -delete
来源：http://dali.yueranfly.top/Article/details/gtrsccvtky.html

[R46] 递归替换文件内容
来源：http://dali.zhengqikj.top/Article/details/gtxphrwvdh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yueranfly.top/Article/details/gtrglbpkqz.html

[R47] sed 单行替换
来源：http://dali.svipenyu.cn/Article/details/gtoczrdgac.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.havefunace.top/Article/details/gtdsapqrjd.html

[R48] awk 取指定列
来源：http://dali.yj20258.top/Article/details/gtuxgudmxw.html

awk '{print $1, $3}' a.txt
来源：http://dali.sxryk.cn/Article/details/gtfttqfxmq.html

[R49] awk 带条件
来源：http://dali.shuidangran.top/Article/details/gtdechyjxm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.dianchejie.cn/Article/details/gtsdshkxbe.html

[R50] awk 求和
来源：http://dali.chenzaomai.com/Article/details/gtmnifquff.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yongpay.top/Article/details/gtvjjvrenz.html

[R51] 排序去重取前几
来源：http://dali.tian-w.cn/Article/details/gttfdrzpww.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dashuyun.cn/Article/details/gtnkkuyhhd.html

[R52] 统计行数
来源：http://dali.smart0.xyz/Article/details/gtloxiscti.html

wc -l a.txt
来源：http://dali.yonumen.top/Article/details/gtrnqhyzrv.html

[R53] 查看文件头与实时尾
来源：http://dali.hammf.cn/Article/details/gtjnqvftms.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.daria6918.cn/Article/details/gtsrmzqqhw.html

[R54] 比较两个文件
来源：http://dali.guowangkeji.top/Article/details/gtxrivplwh.html

diff a.txt b.txt
来源：http://dali.xylfe.cn/Article/details/gtyzkyuouw.html

[R55] 压缩与解压
来源：http://dali.nanxuanxn.top/Article/details/gtupmfkpbo.html


<!-- 参考信息 -->