代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhoulong.xyz/Article/details/gtkmvegxkl.html

[Q05] 重命名列
来源：http://dali.wangshuangyany.cn/Article/details/gtghiozpms.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yonumen.top/Article/details/gtwgrwlloi.html

[Q06] 删除列
来源：http://dali.yueranfly.top/Article/details/gtyinqxkok.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hnqzz.top/Article/details/gtwxkrsxbf.html

[Q07] 删除表
来源：http://dali.c1oappe.top/Article/details/gtijhllyuy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.pycfn.com/Article/details/gtdyexikap.html

[Q08] 创建普通索引
来源：http://dali.ppjwa.cn/Article/details/gtivvkeqdj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gtrrotuguv.html

[Q09] 创建唯一索引
来源：http://dali.smart0.xyz/Article/details/gtgevxbypa.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shangyingyoupin.top/Article/details/gtjrumevnm.html

[Q10] 插入单行
来源：http://dali.kuanghao11.cn/Article/details/gtixhoxzss.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.iojbl.cn/Article/details/gtimchulwr.html

[Q11] 一次插入多行
来源：http://dali.yanxiufei.cn/Article/details/gtllrggcip.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtstjbmrdc.html

[Q12] 插入后取自增 ID
来源：http://dali.c1oappe.top/Article/details/gtqzujitqy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xuetiantiany.cn/Article/details/gtprzkpxwn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.iojbl.cn/Article/details/gtghnvkaam.html

[Q13] 忽略重复插入
来源：http://dali.hammf.cn/Article/details/gtebmaceal.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guannengcc.top/Article/details/gteczjzbox.html

[Q14] 存在则更新（upsert）
来源：http://dali.tanke756.top/Article/details/gtknjnnomd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fengsongda.top/Article/details/gtcaqqwdbk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.daria6918.cn/Article/details/gtybeaismh.html

[Q15] 查询全部
来源：http://dali.dashuyun.cn/Article/details/gtakwqolac.html

SELECT * FROM users;
来源：http://dali.yongpay.top/Article/details/gthrdtvnsl.html

[Q16] 查询指定列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhfymczm.html

SELECT id, name FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtvfrdwale.html

[Q17] 条件查询
来源：http://dali.daxiang520.top/Article/details/gtcsnzbfqw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yuxming.cn/Article/details/gtcfrgedhf.html

[Q18] 模糊匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmvazqpl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sysykeji.top/Article/details/gtecqjwsnk.html

[Q19] 范围查询
来源：http://dali.chenlongwang.top/Article/details/gtgwhwavpw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yvedp.cn/Article/details/gtuyastzna.html

[Q20] IN 列表
来源：http://dali.hysaishi.cn/Article/details/gttawhaofn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj202588.top/Article/details/gtxfumlsdf.html

[Q21] 空值判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwvtgidpx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xylfe.cn/Article/details/gtjmevvqur.html

[Q22] 排序
来源：http://dali.hywenlv.cn/Article/details/gtwgckzhsp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yueranfly.top/Article/details/gtttizyjhw.html

[Q23] 分页
来源：http://dali.cdnleiting.top/Article/details/gtvagyeeag.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tianlin.xyz/Article/details/gtdptientb.html

[Q24] 去重
来源：http://dali.jinqigufen.top/Article/details/gtsbegxmqz.html

SELECT DISTINCT city FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsospreog.html

[Q25] 只取前 N 条
来源：http://dali.pengpengdd.cyou/Article/details/gtozxdscnw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yueranfly.top/Article/details/gtkjcnzomf.html

[Q26] 计数
来源：http://dali.ywan-chungtsiang.top/Article/details/gticvgkxpm.html

SELECT COUNT(*) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtnorhmgnv.html

[Q27] 条件计数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqezevtdx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.daxiang520.top/Article/details/gtladkcvoz.html

[Q28] 求和与平均
来源：http://dali.zycfv.cn/Article/details/gtjhokqntn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtoehiltss.html

[Q29] 最大最小值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnyeudjw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtzafqtmjn.html

[Q30] 分组统计
来源：http://dali.cqqwz.cn/Article/details/gtkryyjzez.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gtmcwdqyfm.html

[Q31] 分组后过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtdzmqsoxg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jianghu66.top/Article/details/gtsecsjydn.html

[Q32] 分组拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtwofsdvcn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gttadvotpj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.vqdsnc.cn/Article/details/gtqpmiwwhb.html

[Q33] 多列分组
来源：http://dali.tianlin.xyz/Article/details/gtenaojbzr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jyoumei.cn/Article/details/gtebsgeacz.html

[Q34] 每组取第一条
来源：http://dali.ybcxt.top/Article/details/gtmqemmygb.html

SELECT * FROM (
来源：http://dali.cucudq.cn/Article/details/gtodyfjjez.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xinyue.icu/Article/details/gtalpkmxvo.html

) t WHERE rn = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtceeadsgr.html

[Q35] 内连接
来源：http://dali.jiagoushi.top/Article/details/gtnezxojys.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gtbujjgnfk.html

[Q36] 左连接
来源：http://dali.hysaishi.cn/Article/details/gtodefflbj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gtgjwndigb.html

[Q37] 右连接
来源：http://dali.dashuyun.cn/Article/details/gtzencesvr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.0kj1m.cn/Article/details/gtqejmoieu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.redwolf501.top/Article/details/gtrbdxphjb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jiagoushi.top/Article/details/gtwtlogjkt.html

[Q39] 自连接（查上下级）
来源：http://dali.zhengqikj.top/Article/details/gtkmctnypd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jiagoushi.top/Article/details/gtwralyplf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnqzz.top/Article/details/gtgwyoinso.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ppjwa.cn/Article/details/gttsgyzifk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yongpay.top/Article/details/gtfhxysgmn.html

[Q41] 多表连接
来源：http://dali.cashguo.top/Article/details/gtonvkqjak.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jyoumei.cn/Article/details/gtljtuzmmr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nwbrower.top/Article/details/gtusiedxtg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258888.top/Article/details/gtjwoaxrwk.html

[Q42] 连接条件附加过滤
来源：http://dali.jyoumei.cn/Article/details/gtixrkpqjp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sysykeji.top/Article/details/gtuxlfzynf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shangyingyoupin.top/Article/details/gtfjkueyrr.html

[Q43] 标量子查询
来源：http://dali.zhiwuduotai.top/Article/details/gthdtxmvjt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cheryme.top/Article/details/gtyfltmptg.html

[Q44] IN 子查询
来源：http://dali.9152youxi.cn/Article/details/gteuyiwezn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gzhubu.top/Article/details/gtxgymnmlw.html

[Q45] EXISTS 判断存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxlfsxha.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gtvmtizxig.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cucudq.cn/Article/details/gtpfucpmzr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zdqjudy.top/Article/details/gtalurniey.html

[Q47] 与平均值比较
来源：http://dali.hammf.cn/Article/details/gtcjqnxukd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.dashuyun.cn/Article/details/gthbohzgah.html

[Q48] CTE 公用表表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbzmoqul.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.wangshuangyany.cn/Article/details/gtoejqgpdg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tianlin.xyz/Article/details/gtqizivdsg.html

[Q49] 更新单行
来源：http://dali.yangfankeji.com/Article/details/gtbdideqwn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gtggokvrhq.html

[Q50] 批量更新
来源：http://dali.zycfv.cn/Article/details/gtxnfoyjfv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnqzz.top/Article/details/gtxpfkejxn.html

[Q51] 用子查询更新
来源：http://dali.yuanzhike.top/Article/details/gtxydmkiou.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ybcxt.top/Article/details/gtfoncfxyo.html

[Q52] 删除指定行
来源：http://dali.xuetiantiany.cn/Article/details/gtypolsakj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hammf.cn/Article/details/gtfeahwbty.html

[Q53] 按条件删除
来源：http://dali.zhongyouzk.top/Article/details/gtvsmmqomj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sweek.top/Article/details/gtmkhmhqmc.html

[Q54] 清空表
来源：http://dali.meibo888.top/Article/details/gtsuuluumy.html

TRUNCATE TABLE logs;
来源：http://dali.yangfankeji.com/Article/details/gtkmqtcdob.html

[Q55] 排名（并列占位）
来源：http://dali.hammf.cn/Article/details/gtaksbckkj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sxryk.cn/Article/details/gtlhksjbow.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnxiangtu.top/Article/details/gtgzcgzzfo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtesreivol.html

[Q57] 行号
来源：http://dali.jiagoushi.top/Article/details/gtjecszccq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtmmxgfpal.html

[Q58] 累计求和
来源：http://dali.pycfn.com/Article/details/gtgmfogcoq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gthnbxkqfs.html

[Q59] 分组内累计
来源：http://dali.jqgufenzy.top/Article/details/gtgbxgkohl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtqukntktl.html

[Q60] 取上一行 / 下一行
来源：http://dali.xylfe.cn/Article/details/gtwnccassw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.birdmap.top/Article/details/gttkxszlhn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtwydthiad.html

[Q61] 移动平均
来源：http://dali.wangdashe.top/Article/details/gtffjrxnjk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtetyhflha.html

[Q62] 分组占比
来源：http://dali.bjfxy.top/Article/details/gtushomdbz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gtegdakiez.html

[Q63] 开启事务
来源：http://dali.mhx1999.top/Article/details/gtnrcocrmy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ybcxt.top/Article/details/gttvsbvzao.html

[Q64] 提交事务
来源：http://dali.hysaishi.cn/Article/details/gtsabqtpfl.html

COMMIT;
来源：http://dali.gzhubu.top/Article/details/gthwgaaljf.html

[Q65] 回滚事务
来源：http://dali.jinqigfzy.top/Article/details/gtscoylauu.html

ROLLBACK;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqojnvwk.html

[Q66] 行锁查询
来源：http://dali.andypj.xyz/Article/details/gtqpaabymz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhengqikj.top/Article/details/gtiicgtske.html

[Q67] 设置隔离级别
来源：http://dali.redwolf501.top/Article/details/gtiokimtpx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.smart0.xyz/Article/details/gtoaqbfxnm.html

[Q68] 保存点
来源：http://dali.dashuyun.cn/Article/details/gttayuqqqo.html

SAVEPOINT sp1;
来源：http://dali.ydzc1.top/Article/details/gtuxhvuydt.html

ROLLBACK TO sp1;
来源：http://dali.haohaochexian.top/Article/details/gtamfduzrr.html

[Q69] 查看执行计划
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzekcyhz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shanyushiyangtech.top/Article/details/gtmddfufpo.html

[Q70] 更新统计信息
来源：http://dali.jqgfzy.top/Article/details/gtzqvinetg.html

ANALYZE TABLE users;
来源：http://dali.yuxming.cn/Article/details/gtgfskollu.html

[Q71] 查看建表语句
来源：http://dali.chenjidiqi.icu/Article/details/gtnjzezdlh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgfzy.top/Article/details/gtuqbodcgp.html

[Q72] 查看索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrzbelvk.html

SHOW INDEX FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtqjlcomhv.html

[Q73] 查看表状态
来源：http://dali.ppjwa.cn/Article/details/gttvsvbsow.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.9152youxi.cn/Article/details/gtzuyycnbx.html

[Q74] 强制使用索引
来源：http://dali.sweek.top/Article/details/gtkrjtutlz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinghuilouyu.cn/Article/details/gttwhszips.html

[Q75] 日期格式化
来源：http://dali.yongpay.top/Article/details/gtqbqxcddn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yongpay.top/Article/details/gthypelrao.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yanxiufei.cn/Article/details/gtttmutfzv.html

[Q76] 按天统计
来源：http://dali.yonumen.top/Article/details/gtlcobdopi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.meibo888.top/Article/details/gtbtqlrjbn.html

[Q77] 时间加减
来源：http://dali.jianghu66.top/Article/details/gtouyjzook.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gaohongyu789.top/Article/details/gtkoplmmcr.html

[Q78] 当前时间
来源：http://dali.shzxlz.cn/Article/details/gtvdsgkpzb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.meibo888.top/Article/details/gtxxsycpxh.html

[Q79] 字符串拼接
来源：http://dali.ybcxt.top/Article/details/gtkqohjpqv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yueranfly.top/Article/details/gtdenuhshy.html

[Q80] 字符串截取
来源：http://dali.hongshengwenyu.top/Article/details/gtzvwerijd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj20258888.top/Article/details/gttzaulczh.html

[Q81] 字符串替换
来源：http://dali.zhoulong.xyz/Article/details/gtblivwlib.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hammf.cn/Article/details/gtgpchzkiw.html

[Q82] 字符长度与字节长度
来源：http://dali.zhongyouzk.top/Article/details/gtgkygzhvp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtusdzivec.html

[Q83] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gtaetuxtgz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gtwtsarxli.html

[Q84] 去除首尾空格
来源：http://dali.fengsongda.top/Article/details/gtwfubrryy.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdioretiw.html

[Q85] 数值取整
来源：http://dali.zhoulong.xyz/Article/details/gtoyftbgcf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ybcxt.top/Article/details/gtqrfbikvb.html

[Q86] 读取 JSON 字段
来源：http://dali.xinyue.icu/Article/details/gtmckikhuq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.iojbl.cn/Article/details/gtbillumkv.html

[Q87] JSON 字段做条件
来源：http://dali.ehwqpu.com/Article/details/gtwomlvpzi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.quarkkingdee.top/Article/details/gtrviokznw.html

[Q88] 行转列（条件聚合）
来源：http://dali.c1oappe.top/Article/details/gtbcpgtrbg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jqgfzy.top/Article/details/gthlenoqtc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtgtworwci.html

[Q89] 判断表是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtejivepke.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gtibfhwkin.html

[Q90] 生成序号列
来源：http://dali.wangdashe.top/Article/details/gtcllcipza.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhengqikj.top/Article/details/gtbcuwwkyi.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtmankiwof.html

R. Bash 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gtqkyjdeze.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtrdyknxtl.html

[R01] shebang 与严格模式
来源：http://dali.daria6918.cn/Article/details/gtrglsjnbg.html

#!/usr/bin/env bash
来源：http://dali.jianghu66.top/Article/details/gtrujkxsye.html

set -euo pipefail
来源：http://dali.yuanzhike.top/Article/details/gtumirstig.html

[R02] 变量赋值与使用
来源：http://dali.svipenyu.cn/Article/details/gtjgmtriwh.html

name="Tom"; echo "$name"
来源：http://dali.nanxinkj.top/Article/details/gtjbhclcyj.html

[R03] 只读变量
来源：http://dali.zhixingplan.top/Article/details/gtnghgiard.html

readonly PI=3.14
来源：http://dali.kuanghao11.cn/Article/details/gtfvujwfmn.html

[R04] 位置参数
来源：http://dali.redwolf501.top/Article/details/gtmfqctcjn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuanzhike.top/Article/details/gtzxodfqgu.html

[R05] 参数默认值
来源：http://dali.jiagoushi.top/Article/details/gtnvgvvnhn.html

name="${1:-default}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtidzphnqa.html

[R06] 判断命令是否存在
来源：http://dali.yuanzhike.top/Article/details/gtbsbxanrn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tianlin.xyz/Article/details/gtefyscbam.html

[R07] if 判断文件
来源：http://dali.xuetiantiany.cn/Article/details/gtwuzomgbj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ehwqpu.com/Article/details/gtjugfqtgh.html

[R08] 数值比较
来源：http://dali.quarkkingdee.top/Article/details/gtwqwbeqbm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj20258888.top/Article/details/gtqgludwjg.html

[R09] 字符串比较
来源：http://dali.dianchejie.cn/Article/details/gtpqqqezho.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuanzx.com/Article/details/gtokrntypz.html

[R10] 正则匹配
来源：http://dali.quarkkingdee.top/Article/details/gtljunavop.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.svipenyu.cn/Article/details/gthqsvxfcx.html

[R11] case 多分支
来源：http://dali.yj20258.top/Article/details/gtwrdqergb.html

case "$1" in
来源：http://dali.0kj1m.cn/Article/details/gtusyjqxwp.html

start) echo "启动" ;;
来源：http://dali.cqqwz.cn/Article/details/gthtzyjhzp.html

stop)  echo "停止" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gtzxdimxfm.html

*)     echo "未知命令" ;;
来源：http://dali.yvedp.cn/Article/details/gtnqpdehue.html

esac
来源：http://dali.yongpay.top/Article/details/gtezmrhsui.html

[R12] for 遍历文件
来源：http://dali.zhongyouzk.top/Article/details/gtchwappbo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zdqjudy.top/Article/details/gtxqomupmg.html

[R13] for 计数循环
来源：http://dali.aizwys.cn/Article/details/gtehdpbvza.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.snrcjt.cn/Article/details/gtglkggccv.html

[R14] C 风格 for
来源：http://dali.ivvv.top/Article/details/gtfzvpnadv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkomsgor.html

[R15] while 逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtwguhffcw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yangfankeji.com/Article/details/gtsunwmowq.html

[R16] until 等待条件
来源：http://dali.gogol.net.cn/Article/details/gtoxhparql.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xziqi.cn/Article/details/gtukwzryqq.html

[R17] 数组定义与取值
来源：http://dali.jqgfzy.top/Article/details/gtrrkgylej.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nanxinkj.top/Article/details/gtksfrvscc.html

[R18] 遍历数组
来源：http://dali.jlsjyb.cn/Article/details/gttxpldyae.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.kuanghao11.cn/Article/details/gttxbrjwjc.html

[R19] 数组长度
来源：http://dali.nanxinkj.top/Article/details/gtfrrtsrlw.html

echo "${#arr[@]}"
来源：http://dali.fengsongda.top/Article/details/gtbmlgdzeb.html

[R20] 关联数组（字典）
来源：http://dali.meibo888.top/Article/details/gttfoqtjjp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgufenzy.top/Article/details/gtiyfenocm.html

[R21] 字符串长度
来源：http://dali.ybcxt.top/Article/details/gtlvnaizxu.html

echo "${#s}"
来源：http://dali.dashuyun.cn/Article/details/gtzwhtwyiz.html

[R22] 截取子串
来源：http://dali.meibo888.top/Article/details/gtfkothadn.html

echo "${s:0:5}"
来源：http://dali.yongpay.top/Article/details/gtbnmojwnm.html

[R23] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gtwprvngap.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ppjwa.cn/Article/details/gtyxqtfmei.html

[R24] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gtxsvdpshy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yvedp.cn/Article/details/gtjkkhzuul.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhengqikj.top/Article/details/gtxccksgxo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj202588.top/Article/details/gtxpzrihwx.html

[R26] 命令替换
来源：http://dali.guowangkeji.top/Article/details/gtvzfevoju.html

now=$(date +%F); echo "$now"
来源：http://dali.jinghuilouyu.cn/Article/details/gtgflsxiio.html

[R27] 算术展开
来源：http://dali.jianghu66.top/Article/details/gtwdroslpt.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gtlmxfizvc.html

[R28] 浮点运算
来源：http://dali.yj20258.top/Article/details/gttigawjkc.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj20258888.top/Article/details/gtczhcvric.html

[R29] 定义函数
来源：http://dali.pycfn.com/Article/details/gthuypgsit.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.andypj.xyz/Article/details/gtumzdtone.html

[R30] 函数返回状态码
来源：http://dali.redwolf501.top/Article/details/gtwkshmuak.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shuidangran.top/Article/details/gtuxquthme.html

[R31] 局部变量
来源：http://dali.feifeiyinyue.top/Article/details/gtisxulocy.html

f() { local x=1; echo "$x"; }
来源：http://dali.meibo888.top/Article/details/gtrusausps.html

[R32] 参数个数校验
来源：http://dali.zhiwuduotai.top/Article/details/gtnfhvgrbr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gtbcvxvcpd.html

[R33] 捕获错误并提示行号
来源：http://dali.xuetiantiany.cn/Article/details/gteowemgji.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xylfe.cn/Article/details/gtouijnqgi.html

[R34] 退出时清理
来源：http://dali.daria6918.cn/Article/details/gtdaeykpwg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuanzhike.top/Article/details/gttflaoqqz.html

[R35] 后台执行并等待
来源：http://dali.sxryk.cn/Article/details/gtuwxyiljf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqyqcgdu.html

[R36] 并发执行多个任务
来源：http://dali.snrcjt.cn/Article/details/gtqkssiekt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hysaishi.cn/Article/details/gtfthziuid.html

[R37] 把输出赋给变量
来源：http://dali.guannengcc.top/Article/details/gtxjzmqbrl.html

files=$(ls -1)
来源：http://dali.chenzaomai.com/Article/details/gtnnecmzcl.html

[R38] 管道串联
来源：http://dali.gotoacloud.top/Article/details/gteqrhfezl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xuetiantiany.cn/Article/details/gtuxpgajow.html

[R39] 重定向标准输出与错误
来源：http://dali.cashguo.top/Article/details/gtjqwoajzi.html

cmd > out.log 2>&1
来源：http://dali.fzhhl.top/Article/details/gtjpjiqbrr.html

[R40] 追加写日志
来源：http://dali.sxryk.cn/Article/details/gthndqphbo.html

echo "log" >> out.log
来源：http://dali.316326.xyz/Article/details/gtqoeqqizg.html

[R41] 丢弃输出
来源：http://dali.jiagoushi.top/Article/details/gtykqeelkl.html

cmd >/dev/null 2>&1
来源：http://dali.hammf.cn/Article/details/gtsqpnuivo.html

[R42] 输入重定向
来源：http://dali.yonumen.top/Article/details/gtcpdhxxgw.html

wc -l < a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtpgmxwtls.html

[R43] 按名字查找文件
来源：http://dali.zdqjudy.top/Article/details/gtnpidpyil.html

find . -name "*.log" -type f
来源：http://dali.xuetiantiany.cn/Article/details/gtzzqxasoz.html

[R44] 按修改时间查找
来源：http://dali.tian-w.cn/Article/details/gtpnxqckbw.html

find . -mtime -7 -type f
来源：http://dali.ydzc1.top/Article/details/gtoisocqdv.html

[R45] 批量删除
来源：http://dali.aibaodan.cn/Article/details/gtwklouhqi.html

find . -name "*.tmp" -delete
来源：http://dali.c1oappe.top/Article/details/gttybpitvd.html

[R46] 递归替换文件内容
来源：http://dali.yvedp.cn/Article/details/gttmtwebdm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.svipenyu.cn/Article/details/gtduiepefs.html

[R47] sed 单行替换
来源：http://dali.pycfn.com/Article/details/gtmwbfbjbq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gotoacloud.top/Article/details/gtpcguposy.html

[R48] awk 取指定列
来源：http://dali.yuxming.cn/Article/details/gteddwpual.html

awk '{print $1, $3}' a.txt
来源：http://dali.iojbl.cn/Article/details/gtfhzkrmwg.html

[R49] awk 带条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvbnsvec.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yonumen.top/Article/details/gtvotapdrr.html

[R50] awk 求和
来源：http://dali.ivvv.top/Article/details/gtqbvcjkve.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.bjfxy.top/Article/details/gtmgtpupva.html

[R51] 排序去重取前几
来源：http://dali.fengsongda.top/Article/details/gtrpymyiwq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gaohongyu789.top/Article/details/gtnhtlqhdv.html

[R52] 统计行数
来源：http://dali.sysykeji.top/Article/details/gtyzsognop.html

wc -l a.txt
来源：http://dali.jiagoushi.top/Article/details/gtlfkfykox.html

[R53] 查看文件头与实时尾
来源：http://dali.yj202588.top/Article/details/gtwblhgrox.html


<!-- 参考信息 -->