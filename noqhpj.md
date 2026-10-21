代发 wailian999

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gtioqykmza.html

[Q09] 创建唯一索引
来源：http://dali.sysykeji.top/Article/details/gtjzuzqvse.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gtduskueau.html

[Q10] 插入单行
来源：http://dali.jqgfzy.top/Article/details/gtoyrmlhmh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.9152youxi.cn/Article/details/gthrlcqqex.html

[Q11] 一次插入多行
来源：http://dali.zhiwuduotai.top/Article/details/gtgjhiqlxe.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ydzc1.top/Article/details/gtckiuegcu.html

[Q12] 插入后取自增 ID
来源：http://dali.snrcjt.cn/Article/details/gtjvrbzxjh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xuanzx.com/Article/details/gtpfnrhhpf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ehwqpu.com/Article/details/gtsffcqkvq.html

[Q13] 忽略重复插入
来源：http://dali.hnxiangtu.top/Article/details/gtzscynmel.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.havefunace.top/Article/details/gtsjobmkqf.html

[Q14] 存在则更新（upsert）
来源：http://dali.pycfn.com/Article/details/gtthhuwaeb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hnqzz.top/Article/details/gtiaqzqqjq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgufenzy.top/Article/details/gtbmllqxlf.html

[Q15] 查询全部
来源：http://dali.yj20258888.top/Article/details/gtblwcbpqp.html

SELECT * FROM users;
来源：http://dali.guannengcc.top/Article/details/gtertbkwdd.html

[Q16] 查询指定列
来源：http://dali.ybcxt.top/Article/details/gtfsbvlkmy.html

SELECT id, name FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtzirrubdr.html

[Q17] 条件查询
来源：http://dali.hongshengwenyu.top/Article/details/gtmcfuzicn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.c1oappe.top/Article/details/gtefttedak.html

[Q18] 模糊匹配
来源：http://dali.snrcjt.cn/Article/details/gtgysjarhc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xziqi.cn/Article/details/gtqxhoptqt.html

[Q19] 范围查询
来源：http://dali.shzxlz.cn/Article/details/gtqzefluxl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.andypj.xyz/Article/details/gtotluvlte.html

[Q20] IN 列表
来源：http://dali.sxryk.cn/Article/details/gtwsxczzbm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.redwolf501.top/Article/details/gtgqnjymop.html

[Q21] 空值判断
来源：http://dali.shzxlz.cn/Article/details/gtappdqrko.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yongpay.top/Article/details/gtuxpcbvbz.html

[Q22] 排序
来源：http://dali.guannengcc.top/Article/details/gtywhmhwab.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sufxvd.cn/Article/details/gtasfbikaq.html

[Q23] 分页
来源：http://dali.zhixingplan.top/Article/details/gtltrwquua.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hongshengwenyu.top/Article/details/gtmhoqpzwr.html

[Q24] 去重
来源：http://dali.hysaishi.cn/Article/details/gtbskbizkk.html

SELECT DISTINCT city FROM users;
来源：http://dali.ivvv.top/Article/details/gtlbvumevf.html

[Q25] 只取前 N 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumhznluf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.feifeiyinyue.top/Article/details/gtknolxgtk.html

[Q26] 计数
来源：http://dali.zycfv.cn/Article/details/gtwoflloff.html

SELECT COUNT(*) FROM users;
来源：http://dali.pycfn.com/Article/details/gtvvvjqwal.html

[Q27] 条件计数
来源：http://dali.chenlongwang.top/Article/details/gttnitdiwh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtnoopynpp.html

[Q28] 求和与平均
来源：http://dali.daria6918.cn/Article/details/gtyuirxboe.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiytelqgh.html

[Q29] 最大最小值
来源：http://dali.guannengcc.top/Article/details/gtohttseiz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtruxmhhin.html

[Q30] 分组统计
来源：http://dali.wangdashe.top/Article/details/gtdgkvdicn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gtnmxgfzfb.html

[Q31] 分组后过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtvrbeistg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xziqi.cn/Article/details/gtsnaecrkq.html

[Q32] 分组拼接字符串
来源：http://dali.meibo888.top/Article/details/gttdissora.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gtofudsapl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hysaishi.cn/Article/details/gtlpmltemx.html

[Q33] 多列分组
来源：http://dali.ybcxt.top/Article/details/gtefkamhca.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.daria6918.cn/Article/details/gthtrzmjla.html

[Q34] 每组取第一条
来源：http://dali.pycfn.com/Article/details/gtemhzovhp.html

SELECT * FROM (
来源：http://dali.yuxming.cn/Article/details/gtbeuerask.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dianchejie.cn/Article/details/gtnzhacqrv.html

) t WHERE rn = 1;
来源：http://dali.daria6918.cn/Article/details/gtmxehdapz.html

[Q35] 内连接
来源：http://dali.jianghu66.top/Article/details/gtijczzkof.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtuzelwzsh.html

[Q36] 左连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtruwoorgl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gotoacloud.top/Article/details/gtkbtshfvo.html

[Q37] 右连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwyycrft.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ybcxt.top/Article/details/gtvpuzoxfq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sysykeji.top/Article/details/gtqdzkscra.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjgetjbi.html

[Q39] 自连接（查上下级）
来源：http://dali.wangdashe.top/Article/details/gteawmaews.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jlsjyb.cn/Article/details/gtwyxytael.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xziqi.cn/Article/details/gtrmqmouav.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.haohaochexian.top/Article/details/gtbkbghrui.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gtiedhzmtx.html

[Q41] 多表连接
来源：http://dali.cdnleiting.top/Article/details/gtseievsrb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.fengsongda.top/Article/details/gtospcialp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ehwqpu.com/Article/details/gtgzdjbchi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hfpthk.cn/Article/details/gtxtoebqsw.html

[Q42] 连接条件附加过滤
来源：http://dali.hywenlv.cn/Article/details/gtdncnpobq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cucudq.cn/Article/details/gtvzhebrdk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sxryk.cn/Article/details/gttmoflebd.html

[Q43] 标量子查询
来源：http://dali.haohaochexian.top/Article/details/gtsqilbqel.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenjidiqi.icu/Article/details/gtrhbohtsd.html

[Q44] IN 子查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqowhmis.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.9152youxi.cn/Article/details/gtaemfujbv.html

[Q45] EXISTS 判断存在
来源：http://dali.ehwqpu.com/Article/details/gtyxeaqjcl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yangfankeji.com/Article/details/gtoxrhqblq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinqigfzy.top/Article/details/gtqcrbhbzw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.birdmap.top/Article/details/gtvggjgwro.html

[Q47] 与平均值比较
来源：http://dali.tianlin.xyz/Article/details/gtkbiioden.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cdnleiting.top/Article/details/gtdxbcbvqo.html

[Q48] CTE 公用表表达式
来源：http://dali.dashuyun.cn/Article/details/gtsctqohcv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.birdmap.top/Article/details/gtigtifggj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yvedp.cn/Article/details/gtudpncijq.html

[Q49] 更新单行
来源：http://dali.kuanghao11.cn/Article/details/gtlgeqzkjs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.andypj.xyz/Article/details/gtmnuhowsn.html

[Q50] 批量更新
来源：http://dali.kuanghao11.cn/Article/details/gtiumqtbcq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.smart0.xyz/Article/details/gtqugfijgu.html

[Q51] 用子查询更新
来源：http://dali.9152youxi.cn/Article/details/gtokmwgjqe.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.pycfn.com/Article/details/gtaotujebe.html

[Q52] 删除指定行
来源：http://dali.tanke756.top/Article/details/gtfbsjnykq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hfpthk.cn/Article/details/gtywesjwnf.html

[Q53] 按条件删除
来源：http://dali.chenjidiqi.icu/Article/details/gtpxnuliss.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj202588.top/Article/details/gtmxedvfoh.html

[Q54] 清空表
来源：http://dali.guannengcc.top/Article/details/gtwamgjxtv.html

TRUNCATE TABLE logs;
来源：http://dali.yuanzhike.top/Article/details/gtpzhxfxba.html

[Q55] 排名（并列占位）
来源：http://dali.mhx1999.top/Article/details/gtqyckbifp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.pycfn.com/Article/details/gtpswvjbbr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtirqsrzyf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cucudq.cn/Article/details/gtknqmvknr.html

[Q57] 行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwxgibrs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.wangdashe.top/Article/details/gtvopmsqym.html

[Q58] 累计求和
来源：http://dali.dianchejie.cn/Article/details/gtzwnhugbp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtuxutplsy.html

[Q59] 分组内累计
来源：http://dali.tianlin.xyz/Article/details/gtgaxqpeig.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtrrbcawbf.html

[Q60] 取上一行 / 下一行
来源：http://dali.cucudq.cn/Article/details/gtqrifidng.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.iojbl.cn/Article/details/gtggmnparr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtobeqjqbg.html

[Q61] 移动平均
来源：http://dali.sufxvd.cn/Article/details/gtobgsaqbd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtvqrkzlij.html

[Q62] 分组占比
来源：http://dali.hnqzz.top/Article/details/gtlngsbaji.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gtauwcjqpz.html

[Q63] 开启事务
来源：http://dali.wangshuangyany.cn/Article/details/gtxinfwuri.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shanyushiyangtech.top/Article/details/gtbfjlfuei.html

[Q64] 提交事务
来源：http://dali.havefunace.top/Article/details/gtupigsari.html

COMMIT;
来源：http://dali.sweek.top/Article/details/gtdpahbkmd.html

[Q65] 回滚事务
来源：http://dali.jlsjyb.cn/Article/details/gtlhbhmtll.html

ROLLBACK;
来源：http://dali.snrcjt.cn/Article/details/gtrveioonr.html

[Q66] 行锁查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzategrr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hywenlv.cn/Article/details/gtiyqoayla.html

[Q67] 设置隔离级别
来源：http://dali.fzhhl.top/Article/details/gtljxnhycf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daria6918.cn/Article/details/gtwcihtbbq.html

[Q68] 保存点
来源：http://dali.zhiwuduotai.top/Article/details/gtghjvrelr.html

SAVEPOINT sp1;
来源：http://dali.pengpengdd.cyou/Article/details/gtyggtrvsh.html

ROLLBACK TO sp1;
来源：http://dali.jinqigufen.top/Article/details/gtgpayaixq.html

[Q69] 查看执行计划
来源：http://dali.gotoacloud.top/Article/details/gtdwcjrtgy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhoulong.xyz/Article/details/gthcnnypbk.html

[Q70] 更新统计信息
来源：http://dali.pycfn.com/Article/details/gtcqkdjkrq.html

ANALYZE TABLE users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpicchfo.html

[Q71] 查看建表语句
来源：http://dali.dashuyun.cn/Article/details/gtdikvfiko.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenlongwang.top/Article/details/gtlkaeuexp.html

[Q72] 查看索引
来源：http://dali.xylfe.cn/Article/details/gtinbgpmif.html

SHOW INDEX FROM users;
来源：http://dali.guannengcc.top/Article/details/gthyywxtyd.html

[Q73] 查看表状态
来源：http://dali.birdmap.top/Article/details/gtrskjfxah.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sysykeji.top/Article/details/gtxnvlanrp.html

[Q74] 强制使用索引
来源：http://dali.sysykeji.top/Article/details/gtuoryyrxu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuanzx.com/Article/details/gtrblrllov.html

[Q75] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gtazbziujh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtsupawfql.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gogol.net.cn/Article/details/gtgjjestum.html

[Q76] 按天统计
来源：http://dali.fengsongda.top/Article/details/gtpcizmokz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.meibo888.top/Article/details/gtlfalmhxm.html

[Q77] 时间加减
来源：http://dali.gzhubu.top/Article/details/gtqycpjsho.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.vqdsnc.cn/Article/details/gtgvedmrgr.html

[Q78] 当前时间
来源：http://dali.guannengcc.top/Article/details/gtghjshqfi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jianghu66.top/Article/details/gtznrmaxtu.html

[Q79] 字符串拼接
来源：http://dali.jianghu66.top/Article/details/gtioqsyhem.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.daxiang520.top/Article/details/gtbpswtqzk.html

[Q80] 字符串截取
来源：http://dali.haohaochexian.top/Article/details/gtneduafcj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gttrdbakeu.html

[Q81] 字符串替换
来源：http://dali.sysykeji.top/Article/details/gtjludxsbs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtgershsef.html

[Q82] 字符长度与字节长度
来源：http://dali.cheryme.top/Article/details/gtqzhiitvt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtouftqykz.html

[Q83] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gtgwlrfcvk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtkpnixxow.html

[Q84] 去除首尾空格
来源：http://dali.feifeiyinyue.top/Article/details/gtxhkljslp.html

SELECT TRIM(name) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtxcptygll.html

[Q85] 数值取整
来源：http://dali.yonumen.top/Article/details/gtwubfpbrq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangshuangyany.cn/Article/details/gtuaftwciy.html

[Q86] 读取 JSON 字段
来源：http://dali.jqgfzy.top/Article/details/gtitxfbfbi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dashuyun.cn/Article/details/gtsljncvjq.html

[Q87] JSON 字段做条件
来源：http://dali.yuanzhike.top/Article/details/gtfumneahd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj202588.top/Article/details/gtzenthnxx.html

[Q88] 行转列（条件聚合）
来源：http://dali.pycfn.com/Article/details/gtymehbrfc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.c1oappe.top/Article/details/gtqkcfqltm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.birdmap.top/Article/details/gtfzfnhvsh.html

[Q89] 判断表是否存在
来源：http://dali.xziqi.cn/Article/details/gtmejmzwxb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.aizwys.cn/Article/details/gtyoozkntg.html

[Q90] 生成序号列
来源：http://dali.yj20258.top/Article/details/gtrmiidwcl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xinyue.icu/Article/details/gtnpeyxshd.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtekwjyqmd.html

R. Bash 专题
来源：http://dali.jqgufenzy.top/Article/details/gtilpukqjy.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtnpdjlauz.html

[R01] shebang 与严格模式
来源：http://dali.9152youxi.cn/Article/details/gtbktjjmps.html

#!/usr/bin/env bash
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtejfenc.html

set -euo pipefail
来源：http://dali.bjfxy.top/Article/details/gtjhpktoyd.html

[R02] 变量赋值与使用
来源：http://dali.fengsongda.top/Article/details/gttuchshej.html

name="Tom"; echo "$name"
来源：http://dali.gogol.net.cn/Article/details/gtorzppbju.html

[R03] 只读变量
来源：http://dali.bjfxy.top/Article/details/gtbaoaprkz.html

readonly PI=3.14
来源：http://dali.bjfxy.top/Article/details/gtjmgkbuun.html

[R04] 位置参数
来源：http://dali.yj202588.top/Article/details/gtamwiwjew.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuanzx.com/Article/details/gtbiltilau.html

[R05] 参数默认值
来源：http://dali.hywenlv.cn/Article/details/gtktaonyzx.html

name="${1:-default}"
来源：http://dali.redwolf501.top/Article/details/gtmerzlaer.html

[R06] 判断命令是否存在
来源：http://dali.jinqigufen.top/Article/details/gtoanzxtyu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258.top/Article/details/gtnoaucjtb.html

[R07] if 判断文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtacjwsbfu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nwbrower.top/Article/details/gtmhauarqm.html

[R08] 数值比较
来源：http://dali.hammf.cn/Article/details/gtwbxljezm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sxryk.cn/Article/details/gtegkwwptc.html

[R09] 字符串比较
来源：http://dali.nanxinkj.top/Article/details/gthxmuhcrt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guowangkeji.top/Article/details/gtnbnckqzg.html

[R10] 正则匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfgicyps.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cdnleiting.top/Article/details/gtxfgdiiqa.html

[R11] case 多分支
来源：http://dali.ivvv.top/Article/details/gtfzlopqnm.html

case "$1" in
来源：http://dali.cqqwz.cn/Article/details/gtxamddmqu.html

start) echo "启动" ;;
来源：http://dali.aibaodan.cn/Article/details/gtsofswgrx.html

stop)  echo "停止" ;;
来源：http://dali.yueranfly.top/Article/details/gtbhxkffvp.html

*)     echo "未知命令" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtpymriwlx.html

esac
来源：http://dali.yuanzhike.top/Article/details/gtgismglko.html

[R12] for 遍历文件
来源：http://dali.shuidangran.top/Article/details/gtnspyecdb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenlongwang.top/Article/details/gtotcdfcqk.html

[R13] for 计数循环
来源：http://dali.316326.xyz/Article/details/gtyzykpqie.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gtxecgcbpm.html

[R14] C 风格 for
来源：http://dali.hammf.cn/Article/details/gtsxzvtdgv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.c1oappe.top/Article/details/gtzyfoztan.html

[R15] while 逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtzojhpzkx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hnxiangtu.top/Article/details/gtqvapctrh.html

[R16] until 等待条件
来源：http://dali.jinqigufen.top/Article/details/gtbcyxxlqh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gtettmbtdl.html

[R17] 数组定义与取值
来源：http://dali.zycfv.cn/Article/details/gtuubrhdja.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ivvv.top/Article/details/gtwrdqszyz.html

[R18] 遍历数组
来源：http://dali.zycfv.cn/Article/details/gtbzrfbwkj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ydzc1.top/Article/details/gtbvfvusdr.html

[R19] 数组长度
来源：http://dali.tanke756.top/Article/details/gtcnawstql.html

echo "${#arr[@]}"
来源：http://dali.hnqzz.top/Article/details/gtphqynmhu.html

[R20] 关联数组（字典）
来源：http://dali.hywenlv.cn/Article/details/gtodspiguo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yueranfly.top/Article/details/gtpnzlgomo.html

[R21] 字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gtfnnqefdk.html

echo "${#s}"
来源：http://dali.yvedp.cn/Article/details/gtwdlmtpeq.html

[R22] 截取子串
来源：http://dali.xylfe.cn/Article/details/gtyeuxbewh.html

echo "${s:0:5}"
来源：http://dali.xuetiantiany.cn/Article/details/gtuchrioyb.html

[R23] 字符串替换
来源：http://dali.daxiang520.top/Article/details/gtuwrkamsv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhiwuduotai.top/Article/details/gtxesbkduw.html

[R24] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gthioshoud.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj202588.top/Article/details/gtacdrioyt.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnqzz.top/Article/details/gtrdaeygfs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.snrcjt.cn/Article/details/gtrijqsntn.html

[R26] 命令替换
来源：http://dali.sysykeji.top/Article/details/gtwsjxxujx.html

now=$(date +%F); echo "$now"
来源：http://dali.shzxlz.cn/Article/details/gtsftcwyuw.html

[R27] 算术展开
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhyipuhx.html

echo $((1 + 2 * 3))
来源：http://dali.snrcjt.cn/Article/details/gtrkleemhk.html

[R28] 浮点运算
来源：http://dali.9152youxi.cn/Article/details/gtkoymziex.html

echo "scale=2; 10/3" | bc
来源：http://dali.smart0.xyz/Article/details/gtgfqadrdp.html

[R29] 定义函数
来源：http://dali.yueranfly.top/Article/details/gtgmgokjsa.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhongyouzk.top/Article/details/gtofcdbwqw.html

[R30] 函数返回状态码
来源：http://dali.zdqjudy.top/Article/details/gtcvwajhiq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.c1oappe.top/Article/details/gtftlfvkzc.html

[R31] 局部变量
来源：http://dali.yonumen.top/Article/details/gtzgdwopas.html

f() { local x=1; echo "$x"; }
来源：http://dali.ivvv.top/Article/details/gtdhjeeyfb.html

[R32] 参数个数校验
来源：http://dali.svipenyu.cn/Article/details/gtbmarhpqj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gtafbpiqvp.html

[R33] 捕获错误并提示行号
来源：http://dali.jyoumei.cn/Article/details/gtfcppizte.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sufxvd.cn/Article/details/gtlafzneyv.html

[R34] 退出时清理
来源：http://dali.chenzaomai.com/Article/details/gtrskmhcyp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gttczkmumj.html

[R35] 后台执行并等待
来源：http://dali.fengsongda.top/Article/details/gttozkpgzg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gzhubu.top/Article/details/gtbwlwbvwu.html

[R36] 并发执行多个任务
来源：http://dali.sxryk.cn/Article/details/gtcmiekggq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yvedp.cn/Article/details/gtkybfluwd.html

[R37] 把输出赋给变量
来源：http://dali.nwbrower.top/Article/details/gtshkbrtty.html

files=$(ls -1)
来源：http://dali.jqgufenzy.top/Article/details/gtwvjsuzet.html

[R38] 管道串联
来源：http://dali.sweek.top/Article/details/gtfrlmccpw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shangyingyoupin.top/Article/details/gtscodhklw.html

[R39] 重定向标准输出与错误
来源：http://dali.pengpengdd.cyou/Article/details/gtpqnfwmfb.html

cmd > out.log 2>&1
来源：http://dali.hfpthk.cn/Article/details/gtqafiatlw.html

[R40] 追加写日志
来源：http://dali.tanke756.top/Article/details/gtjleywsut.html

echo "log" >> out.log
来源：http://dali.jlsjyb.cn/Article/details/gtcuxztbww.html

[R41] 丢弃输出
来源：http://dali.ivvv.top/Article/details/gtzyzvjvxt.html

cmd >/dev/null 2>&1
来源：http://dali.tanke756.top/Article/details/gtukuznhlw.html

[R42] 输入重定向
来源：http://dali.yangfankeji.com/Article/details/gtridekswa.html

wc -l < a.txt
来源：http://dali.nanxuanxn.top/Article/details/gttpngxgsb.html

[R43] 按名字查找文件
来源：http://dali.gogol.net.cn/Article/details/gtskbvazks.html

find . -name "*.log" -type f
来源：http://dali.yanxiufei.cn/Article/details/gtkrnqvxpx.html

[R44] 按修改时间查找
来源：http://dali.jiagoushi.top/Article/details/gtsrlnaxni.html

find . -mtime -7 -type f
来源：http://dali.yj202588.top/Article/details/gtdmanubia.html

[R45] 批量删除
来源：http://dali.vqdsnc.cn/Article/details/gtpoduhhdj.html

find . -name "*.tmp" -delete
来源：http://dali.daria6918.cn/Article/details/gtiemfkoad.html

[R46] 递归替换文件内容
来源：http://dali.jqgufenzy.top/Article/details/gtjchhahgq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.bjfxy.top/Article/details/gtlaimpcui.html

[R47] sed 单行替换
来源：http://dali.hywenlv.cn/Article/details/gtvtpyndlq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pycfn.com/Article/details/gtpesweawo.html

[R48] awk 取指定列
来源：http://dali.haohaochexian.top/Article/details/gtbnnnauyq.html

awk '{print $1, $3}' a.txt
来源：http://dali.mhx1999.top/Article/details/gtsjecspgx.html

[R49] awk 带条件
来源：http://dali.cqqwz.cn/Article/details/gtxrxpihyu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sufxvd.cn/Article/details/gtbgofqbnd.html

[R50] awk 求和
来源：http://dali.ivvv.top/Article/details/gtjwyjggof.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gotoacloud.top/Article/details/gtjarnmytj.html

[R51] 排序去重取前几
来源：http://dali.xuanzx.com/Article/details/gtskjsrwen.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hammf.cn/Article/details/gtmqgadohh.html

[R52] 统计行数
来源：http://dali.gogol.net.cn/Article/details/gtkcauilhb.html

wc -l a.txt
来源：http://dali.dashuyun.cn/Article/details/gtrvqwwnby.html

[R53] 查看文件头与实时尾
来源：http://dali.xuanzx.com/Article/details/gtwducjqez.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ybcxt.top/Article/details/gtbjgzrbjl.html

[R54] 比较两个文件
来源：http://dali.bjfxy.top/Article/details/gtufefgkbd.html

diff a.txt b.txt
来源：http://dali.tanke756.top/Article/details/gtemzmhsai.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gtbeikheri.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gteehorjbg.html

[R56] 远程拷贝
来源：http://dali.yangfankeji.com/Article/details/gtgvsvejsh.html

scp file user@host:/path/
来源：http://dali.ppjwa.cn/Article/details/gtgpyiyktu.html

[R57] 远程执行命令
来源：http://dali.quarkkingdee.top/Article/details/gtstwstqoj.html


<!-- 参考信息 -->