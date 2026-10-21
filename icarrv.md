代发 wailian999

);
来源：http://dali.yueranfly.top/Article/details/gtmazrbfjw.html

[Q03] 增加列
来源：http://dali.jlsjyb.cn/Article/details/gtbedueaal.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yonumen.top/Article/details/gtptygtaly.html

[Q04] 修改列类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndngctsp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenlongwang.top/Article/details/gtuerlbhvr.html

[Q05] 重命名列
来源：http://dali.ehwqpu.com/Article/details/gtzgykhjle.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhengqikj.top/Article/details/gtnnhkhidv.html

[Q06] 删除列
来源：http://dali.9152youxi.cn/Article/details/gtpldqqyqv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yvedp.cn/Article/details/gtbyjtdvmg.html

[Q07] 删除表
来源：http://dali.316326.xyz/Article/details/gtdvtsvrmp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yonumen.top/Article/details/gtnjldcmtu.html

[Q08] 创建普通索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxhqpcnr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gtrgowewbc.html

[Q09] 创建唯一索引
来源：http://dali.jyoumei.cn/Article/details/gtmpcchthw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuanzx.com/Article/details/gtriweaizu.html

[Q10] 插入单行
来源：http://dali.chenjidiqi.icu/Article/details/gticfqwwsz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jqgufenzy.top/Article/details/gtsuubuhwc.html

[Q11] 一次插入多行
来源：http://dali.yongpay.top/Article/details/gtwuiazxct.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.meibo888.top/Article/details/gttslsvnvs.html

[Q12] 插入后取自增 ID
来源：http://dali.hnqzz.top/Article/details/gtruvyrxpp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zdqjudy.top/Article/details/gtafmzlgrw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cdnleiting.top/Article/details/gtjgtpwwkn.html

[Q13] 忽略重复插入
来源：http://dali.feifeiyinyue.top/Article/details/gtcdtflwyz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.birdmap.top/Article/details/gtmpxrxgzm.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnqzz.top/Article/details/gtnzjcqndk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yonumen.top/Article/details/gtqkzbffzk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.pycfn.com/Article/details/gtdypfzmpo.html

[Q15] 查询全部
来源：http://dali.zhongyouzk.top/Article/details/gtdzhoqzwp.html

SELECT * FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtqjanttub.html

[Q16] 查询指定列
来源：http://dali.zhoulong.xyz/Article/details/gtjeqpzeqv.html

SELECT id, name FROM users;
来源：http://dali.316326.xyz/Article/details/gtuupqrmxf.html

[Q17] 条件查询
来源：http://dali.tian-w.cn/Article/details/gtensztxwc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ivvv.top/Article/details/gtzhlhtimw.html

[Q18] 模糊匹配
来源：http://dali.yanxiufei.cn/Article/details/gtgmnrbibz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gaohongyu789.top/Article/details/gtniwxgfhx.html

[Q19] 范围查询
来源：http://dali.sxryk.cn/Article/details/gtjarmdmfw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuanzx.com/Article/details/gtjzgagmga.html

[Q20] IN 列表
来源：http://dali.aizwys.cn/Article/details/gtapbpmmty.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.haohaochexian.top/Article/details/gtkoemetfb.html

[Q21] 空值判断
来源：http://dali.zhoulong.xyz/Article/details/gtzehduxpa.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhongyouzk.top/Article/details/gtwaebifvt.html

[Q22] 排序
来源：http://dali.redwolf501.top/Article/details/gtbldoojre.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jiagoushi.top/Article/details/gtuwgztqlm.html

[Q23] 分页
来源：http://dali.tanke756.top/Article/details/gtupbckwyv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xuanzx.com/Article/details/gtvdmehocf.html

[Q24] 去重
来源：http://dali.pycfn.com/Article/details/gthhkankau.html

SELECT DISTINCT city FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtuocsnuhh.html

[Q25] 只取前 N 条
来源：http://dali.gogol.net.cn/Article/details/gtsddfriqt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hongshengwenyu.top/Article/details/gtautodmvh.html

[Q26] 计数
来源：http://dali.gogol.net.cn/Article/details/gtpscanpyy.html

SELECT COUNT(*) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtdwfriehp.html

[Q27] 条件计数
来源：http://dali.cdnleiting.top/Article/details/gtttnmidim.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtmwcjqbey.html

[Q28] 求和与平均
来源：http://dali.smart0.xyz/Article/details/gtmwtnpvdt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtkfvjewzv.html

[Q29] 最大最小值
来源：http://dali.hywenlv.cn/Article/details/gtwvxrzgzv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtbqjzmgpl.html

[Q30] 分组统计
来源：http://dali.chenlongwang.top/Article/details/gtulftlurs.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntaboprt.html

[Q31] 分组后过滤
来源：http://dali.meibo888.top/Article/details/gtjwgqngln.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hfpthk.cn/Article/details/gtuvkmaqrd.html

[Q32] 分组拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gtrogbpzzc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gtqjubhgfd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yanxiufei.cn/Article/details/gtuamomwen.html

[Q33] 多列分组
来源：http://dali.nwbrower.top/Article/details/gtzqzegxzm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cashguo.top/Article/details/gtuormnvqm.html

[Q34] 每组取第一条
来源：http://dali.dianchejie.cn/Article/details/gtnlfdkkfs.html

SELECT * FROM (
来源：http://dali.quarkkingdee.top/Article/details/gtoysrncea.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gotoacloud.top/Article/details/gtqhvhotpv.html

) t WHERE rn = 1;
来源：http://dali.snrcjt.cn/Article/details/gtidunvnwf.html

[Q35] 内连接
来源：http://dali.hongshengwenyu.top/Article/details/gtycopcnxi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zdqjudy.top/Article/details/gtpnxzijbl.html

[Q36] 左连接
来源：http://dali.tian-w.cn/Article/details/gtprugfmda.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.havefunace.top/Article/details/gtjbqmoyfg.html

[Q37] 右连接
来源：http://dali.haohaochexian.top/Article/details/gtbkxlqopk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.meibo888.top/Article/details/gtgobrtkol.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhoulong.xyz/Article/details/gttqijnqcm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.guowangkeji.top/Article/details/gtgdhaeyuh.html

[Q39] 自连接（查上下级）
来源：http://dali.jqgfzy.top/Article/details/gtghvsarka.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ehwqpu.com/Article/details/gttnpgvoqi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenlongwang.top/Article/details/gtjezpubmr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cqqwz.cn/Article/details/gtvezqsxci.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.meibo888.top/Article/details/gtjfisccky.html

[Q41] 多表连接
来源：http://dali.gogol.net.cn/Article/details/gtowaxnsga.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.havefunace.top/Article/details/gtmmiirsoe.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenzaomai.com/Article/details/gtggplzcqs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhongyouzk.top/Article/details/gtghrwodfz.html

[Q42] 连接条件附加过滤
来源：http://dali.jiagoushi.top/Article/details/gtfdzpqxho.html

SELECT u.name, o.amount FROM users u
来源：http://dali.iojbl.cn/Article/details/gtsdqnnukx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jianghu66.top/Article/details/gtggoxhham.html

[Q43] 标量子查询
来源：http://dali.ydzc1.top/Article/details/gtbnwqdfvf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.snrcjt.cn/Article/details/gtxwwpwhtr.html

[Q44] IN 子查询
来源：http://dali.jyoumei.cn/Article/details/gtweorkcld.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yongpay.top/Article/details/gtjaeegmkg.html

[Q45] EXISTS 判断存在
来源：http://dali.cucudq.cn/Article/details/gtxgyqdrxk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gtsurbhkve.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.iojbl.cn/Article/details/gtamvcifoe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.birdmap.top/Article/details/gtgasltvcl.html

[Q47] 与平均值比较
来源：http://dali.chenzaomai.com/Article/details/gtrnzjpoug.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zdqjudy.top/Article/details/gtoymvgmpm.html

[Q48] CTE 公用表表达式
来源：http://dali.cheryme.top/Article/details/gtvsehgvvf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj20258888.top/Article/details/gtdgymuhdz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangshuangyany.cn/Article/details/gtigainijn.html

[Q49] 更新单行
来源：http://dali.cheryme.top/Article/details/gtunfdrbtj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gtvrotslzg.html

[Q50] 批量更新
来源：http://dali.jqgfzy.top/Article/details/gtesswtbzj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnxiangtu.top/Article/details/gtoeanppdp.html

[Q51] 用子查询更新
来源：http://dali.wangshuangyany.cn/Article/details/gtyvftmkhs.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yueranfly.top/Article/details/gtmmkqqedx.html

[Q52] 删除指定行
来源：http://dali.jianghu66.top/Article/details/gtphppgvah.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zdqjudy.top/Article/details/gtgdstvzav.html

[Q53] 按条件删除
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzcusrho.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hnqzz.top/Article/details/gtvssobwrg.html

[Q54] 清空表
来源：http://dali.nanxinkj.top/Article/details/gtqidrdxto.html

TRUNCATE TABLE logs;
来源：http://dali.zhoulong.xyz/Article/details/gtlttyzgdq.html

[Q55] 排名（并列占位）
来源：http://dali.gaohongyu789.top/Article/details/gtabaldaze.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.aizwys.cn/Article/details/gtcmarvnac.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jyoumei.cn/Article/details/gtpbxfobyb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ybcxt.top/Article/details/gtobboqyuf.html

[Q57] 行号
来源：http://dali.andypj.xyz/Article/details/gttxdcypyn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtehbtyuyn.html

[Q58] 累计求和
来源：http://dali.jinqigfzy.top/Article/details/gttqvndded.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtfmapgohs.html

[Q59] 分组内累计
来源：http://dali.tianlin.xyz/Article/details/gtpadnvycr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtubxsgmfk.html

[Q60] 取上一行 / 下一行
来源：http://dali.svipenyu.cn/Article/details/gtjijfagrt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ppjwa.cn/Article/details/gtwzfjpfnq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtlivkpwgl.html

[Q61] 移动平均
来源：http://dali.yonumen.top/Article/details/gtzizcixdx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtjcmcnoxu.html

[Q62] 分组占比
来源：http://dali.zhongyouzk.top/Article/details/gtwvxfoepr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtfcxdwmpq.html

[Q63] 开启事务
来源：http://dali.jyoumei.cn/Article/details/gtmjqjhmnc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sxryk.cn/Article/details/gtzsmaaovt.html

[Q64] 提交事务
来源：http://dali.ydzc1.top/Article/details/gtzjplwwhb.html

COMMIT;
来源：http://dali.meibo888.top/Article/details/gtkrzcndvx.html

[Q65] 回滚事务
来源：http://dali.cucudq.cn/Article/details/gttmrudjiu.html

ROLLBACK;
来源：http://dali.hammf.cn/Article/details/gteywzhewj.html

[Q66] 行锁查询
来源：http://dali.wangdashe.top/Article/details/gtmfgubrmz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.guannengcc.top/Article/details/gtpjlxsdey.html

[Q67] 设置隔离级别
来源：http://dali.zhongyouzk.top/Article/details/gtkhgpfcsu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.kuanghao11.cn/Article/details/gtuybqrmar.html

[Q68] 保存点
来源：http://dali.wangdashe.top/Article/details/gthkpwdlwj.html

SAVEPOINT sp1;
来源：http://dali.chenlongwang.top/Article/details/gtyxmrstdm.html

ROLLBACK TO sp1;
来源：http://dali.svipenyu.cn/Article/details/gtzapatzdy.html

[Q69] 查看执行计划
来源：http://dali.c1oappe.top/Article/details/gthjiqrxhy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fzhhl.top/Article/details/gtaffkwwvb.html

[Q70] 更新统计信息
来源：http://dali.jiagoushi.top/Article/details/gtmyjlqxci.html

ANALYZE TABLE users;
来源：http://dali.fzhhl.top/Article/details/gtvgpzavjw.html

[Q71] 查看建表语句
来源：http://dali.cdnleiting.top/Article/details/gtuouklrsa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gtnbwxxucs.html

[Q72] 查看索引
来源：http://dali.jiagoushi.top/Article/details/gtjfvakbru.html

SHOW INDEX FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtqmddcrdp.html

[Q73] 查看表状态
来源：http://dali.ppjwa.cn/Article/details/gtwuahnksy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hnxiangtu.top/Article/details/gtdkpyupbn.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gtgcxzaojw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hfpthk.cn/Article/details/gtlqtdufwa.html

[Q75] 日期格式化
来源：http://dali.meibo888.top/Article/details/gtzskjiiwf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtumqpobpq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shzxlz.cn/Article/details/gtnjhajkej.html

[Q76] 按天统计
来源：http://dali.sysykeji.top/Article/details/gteeidyfki.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cheryme.top/Article/details/gtppcztiul.html

[Q77] 时间加减
来源：http://dali.meibo888.top/Article/details/gtwdtuwslr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gogol.net.cn/Article/details/gtyrmfajvj.html

[Q78] 当前时间
来源：http://dali.chenjidiqi.icu/Article/details/gthaasjcuu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hammf.cn/Article/details/gtripngbyr.html

[Q79] 字符串拼接
来源：http://dali.dianchejie.cn/Article/details/gtafuublkr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenjidiqi.icu/Article/details/gtbsdzxxwo.html

[Q80] 字符串截取
来源：http://dali.xziqi.cn/Article/details/gtnxirexck.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtnumfevpb.html

[Q81] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gtiqrwroyv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtmemgptku.html

[Q82] 字符长度与字节长度
来源：http://dali.jyoumei.cn/Article/details/gtoyqcmuda.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtrikrnonw.html

[Q83] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gtnhdggcar.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtdsogbjgb.html

[Q84] 去除首尾空格
来源：http://dali.snrcjt.cn/Article/details/gthnnldcwf.html

SELECT TRIM(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtrjubmqxa.html

[Q85] 数值取整
来源：http://dali.chenlongwang.top/Article/details/gtveoguhqz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gaohongyu789.top/Article/details/gtvaxstvmj.html

[Q86] 读取 JSON 字段
来源：http://dali.ybcxt.top/Article/details/gtphceuyho.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxinkj.top/Article/details/gtnrushgur.html

[Q87] JSON 字段做条件
来源：http://dali.fengsongda.top/Article/details/gtvwwxutvx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258888.top/Article/details/gtazaqcqqe.html

[Q88] 行转列（条件聚合）
来源：http://dali.zycfv.cn/Article/details/gtliawdmek.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.vqdsnc.cn/Article/details/gtofnxfieb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ybcxt.top/Article/details/gtzdtntcuf.html

[Q89] 判断表是否存在
来源：http://dali.tianlin.xyz/Article/details/gtcisnbuhn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj20258888.top/Article/details/gtcxqmroaf.html

[Q90] 生成序号列
来源：http://dali.snrcjt.cn/Article/details/gtkpvnnxwi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.fzhhl.top/Article/details/gtglhcvudb.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtrvpsjnfa.html

R. Bash 专题
来源：http://dali.zhiwuduotai.top/Article/details/gtzotprptn.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtlyjuiupb.html

[R01] shebang 与严格模式
来源：http://dali.chenzaomai.com/Article/details/gtlmutwrpo.html

#!/usr/bin/env bash
来源：http://dali.iojbl.cn/Article/details/gttyrjxuyi.html

set -euo pipefail
来源：http://dali.yj20258.top/Article/details/gtzekariba.html

[R02] 变量赋值与使用
来源：http://dali.zhengqikj.top/Article/details/gtazaiuvkp.html

name="Tom"; echo "$name"
来源：http://dali.andypj.xyz/Article/details/gtpxjzijnr.html

[R03] 只读变量
来源：http://dali.shangyingyoupin.top/Article/details/gtxlaggkik.html

readonly PI=3.14
来源：http://dali.sweek.top/Article/details/gtfuxufokp.html

[R04] 位置参数
来源：http://dali.andypj.xyz/Article/details/gtdnhbxosu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.feifeiyinyue.top/Article/details/gthxcajjrv.html

[R05] 参数默认值
来源：http://dali.wangdashe.top/Article/details/gtzfyoynev.html

name="${1:-default}"
来源：http://dali.bjfxy.top/Article/details/gtpjbwkayy.html

[R06] 判断命令是否存在
来源：http://dali.birdmap.top/Article/details/gtcqhwnwcv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gtsnbdgidm.html

[R07] if 判断文件
来源：http://dali.zdqjudy.top/Article/details/gtrsxyjdez.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xuanzx.com/Article/details/gtwmlfhqtw.html

[R08] 数值比较
来源：http://dali.xinyue.icu/Article/details/gtidmlosey.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dashuyun.cn/Article/details/gtujuloqvg.html

[R09] 字符串比较
来源：http://dali.sxryk.cn/Article/details/gthqhoaswg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cucudq.cn/Article/details/gttpawasnl.html

[R10] 正则匹配
来源：http://dali.xziqi.cn/Article/details/gtmnvuncjk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jiagoushi.top/Article/details/gtfgicfqaa.html

[R11] case 多分支
来源：http://dali.smart0.xyz/Article/details/gtijhmypjs.html

case "$1" in
来源：http://dali.zhaomingkeji.xyz/Article/details/gthngmjury.html

start) echo "启动" ;;
来源：http://dali.yuxming.cn/Article/details/gtdaycedni.html

stop)  echo "停止" ;;
来源：http://dali.birdmap.top/Article/details/gtneedwpqw.html

*)     echo "未知命令" ;;
来源：http://dali.ybcxt.top/Article/details/gtobetqiin.html

esac
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgokdeuyi.html

[R12] for 遍历文件
来源：http://dali.vqdsnc.cn/Article/details/gtvlbltevz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.haohaochexian.top/Article/details/gtyopwekbw.html

[R13] for 计数循环
来源：http://dali.tanke756.top/Article/details/gtmhwaipmk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gtorowwogh.html

[R14] C 风格 for
来源：http://dali.mhx1999.top/Article/details/gtnhiglhhz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gtdnqremgp.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrgireffb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nwbrower.top/Article/details/gtsjawyswt.html

[R16] until 等待条件
来源：http://dali.shangyingyoupin.top/Article/details/gtjxwldaqj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tanke756.top/Article/details/gtjpcovozg.html

[R17] 数组定义与取值
来源：http://dali.0kj1m.cn/Article/details/gtnllrgxhi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgufenzy.top/Article/details/gtrgbqmhsh.html

[R18] 遍历数组
来源：http://dali.zhixingplan.top/Article/details/gtzvcsyobm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ydzc1.top/Article/details/gtbgpxqrut.html

[R19] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gtazwqlwsl.html

echo "${#arr[@]}"
来源：http://dali.guowangkeji.top/Article/details/gtwavwnqxb.html

[R20] 关联数组（字典）
来源：http://dali.yongpay.top/Article/details/gtbealjsew.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.havefunace.top/Article/details/gtwkzzxrjr.html

[R21] 字符串长度
来源：http://dali.hnqzz.top/Article/details/gtauafczdu.html

echo "${#s}"
来源：http://dali.xylfe.cn/Article/details/gtgakcrpdz.html

[R22] 截取子串
来源：http://dali.yj20258.top/Article/details/gtzrscpzqt.html

echo "${s:0:5}"
来源：http://dali.redwolf501.top/Article/details/gtprzhygxc.html

[R23] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gthgfyqwst.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj20258.top/Article/details/gtxilzaxws.html

[R24] 大小写转换
来源：http://dali.yj20258.top/Article/details/gtdiremrdl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.dianchejie.cn/Article/details/gtxqdwdwie.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuanzx.com/Article/details/gtauitjgnp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenlongwang.top/Article/details/gtwbyijzxi.html

[R26] 命令替换
来源：http://dali.nanxinkj.top/Article/details/gtwanyrord.html

now=$(date +%F); echo "$now"
来源：http://dali.yuxming.cn/Article/details/gtsllukeup.html

[R27] 算术展开
来源：http://dali.jinqigfzy.top/Article/details/gtapanafgj.html

echo $((1 + 2 * 3))
来源：http://dali.jyoumei.cn/Article/details/gtpcmpfcgp.html

[R28] 浮点运算
来源：http://dali.fzhhl.top/Article/details/gtfzyvaxww.html

echo "scale=2; 10/3" | bc
来源：http://dali.hongshengwenyu.top/Article/details/gtygjbckde.html

[R29] 定义函数
来源：http://dali.hywenlv.cn/Article/details/gttyefbnvf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.bjfxy.top/Article/details/gtfmjvqtfd.html

[R30] 函数返回状态码
来源：http://dali.chenzaomai.com/Article/details/gtdaniegll.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.svipenyu.cn/Article/details/gtlymyrydz.html

[R31] 局部变量
来源：http://dali.vqdsnc.cn/Article/details/gtsoxlzlpl.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenjidiqi.icu/Article/details/gttqablnhx.html

[R32] 参数个数校验
来源：http://dali.yangfankeji.com/Article/details/gtblgkswyx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hywenlv.cn/Article/details/gtoporlubl.html

[R33] 捕获错误并提示行号
来源：http://dali.birdmap.top/Article/details/gtjbmlyysa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhengqikj.top/Article/details/gtegrsjhla.html

[R34] 退出时清理
来源：http://dali.shzxlz.cn/Article/details/gtusyvltkv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gtqgcqbfmh.html

[R35] 后台执行并等待
来源：http://dali.quarkkingdee.top/Article/details/gthxrhiaes.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xinyue.icu/Article/details/gtnipzjvzm.html

[R36] 并发执行多个任务
来源：http://dali.guannengcc.top/Article/details/gtttgazfcw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cheryme.top/Article/details/gtdzzecxoj.html

[R37] 把输出赋给变量
来源：http://dali.aibaodan.cn/Article/details/gtsmqiegsg.html

files=$(ls -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswaucvst.html

[R38] 管道串联
来源：http://dali.cdnleiting.top/Article/details/gtjhjvacbd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.wangdashe.top/Article/details/gtmmjhwxqi.html

[R39] 重定向标准输出与错误
来源：http://dali.cheryme.top/Article/details/gtjndizfsw.html

cmd > out.log 2>&1
来源：http://dali.chenlongwang.top/Article/details/gtiyirgoeg.html

[R40] 追加写日志
来源：http://dali.svipenyu.cn/Article/details/gtfdruyvqa.html

echo "log" >> out.log
来源：http://dali.yj20258888.top/Article/details/gtyngnnrdk.html

[R41] 丢弃输出
来源：http://dali.yj202588.top/Article/details/gtdbrnwsub.html

cmd >/dev/null 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gtsrseyjds.html

[R42] 输入重定向
来源：http://dali.jyoumei.cn/Article/details/gtmiyxnlaf.html

wc -l < a.txt
来源：http://dali.chenlongwang.top/Article/details/gtknejmyap.html

[R43] 按名字查找文件
来源：http://dali.yvedp.cn/Article/details/gtdcltnzva.html

find . -name "*.log" -type f
来源：http://dali.ybcxt.top/Article/details/gtcylmyaxf.html

[R44] 按修改时间查找
来源：http://dali.zhongyouzk.top/Article/details/gtxivobokv.html

find . -mtime -7 -type f
来源：http://dali.sysykeji.top/Article/details/gtcfdbyrjo.html

[R45] 批量删除
来源：http://dali.chenzaomai.com/Article/details/gtnrcfzpzm.html

find . -name "*.tmp" -delete
来源：http://dali.cheryme.top/Article/details/gthrpqsufn.html

[R46] 递归替换文件内容
来源：http://dali.gaohongyu789.top/Article/details/gtgucxhnan.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.kuanghao11.cn/Article/details/gtffoktvrc.html

[R47] sed 单行替换
来源：http://dali.snrcjt.cn/Article/details/gtfuvwmovf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtgcauggaw.html

[R48] awk 取指定列
来源：http://dali.daxiang520.top/Article/details/gtitbmoior.html

awk '{print $1, $3}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gtgvhrypdn.html

[R49] awk 带条件
来源：http://dali.mhx1999.top/Article/details/gtljttqgzz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.meibo888.top/Article/details/gtvdbjepcz.html

[R50] awk 求和
来源：http://dali.snrcjt.cn/Article/details/gtyzbszezn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtvjregffh.html

[R51] 排序去重取前几
来源：http://dali.dashuyun.cn/Article/details/gthiopqwfd.html


<!-- 参考信息 -->