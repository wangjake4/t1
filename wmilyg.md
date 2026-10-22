代发 wailian999

);
来源：http://dali.cdnleiting.top/Article/details/gtumyhoajq.html

[Q03] 增加列
来源：http://dali.xuetiantiany.cn/Article/details/gttndkmdmt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj202588.top/Article/details/gtzfbdiwtm.html

[Q04] 修改列类型
来源：http://dali.cheryme.top/Article/details/gtbburtwok.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.iojbl.cn/Article/details/gtxkvbmbsn.html

[Q05] 重命名列
来源：http://dali.jianghu66.top/Article/details/gtwbikhftk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.guowangkeji.top/Article/details/gtgmkqqrjk.html

[Q06] 删除列
来源：http://dali.xinyue.icu/Article/details/gtwebnwhoq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.vqdsnc.cn/Article/details/gttnrfprhe.html

[Q07] 删除表
来源：http://dali.ybcxt.top/Article/details/gtrrrdsdcy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cashguo.top/Article/details/gtnrzarkzb.html

[Q08] 创建普通索引
来源：http://dali.jqgufenzy.top/Article/details/gtnefuqlaf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.bjfxy.top/Article/details/gtkgqsmvtm.html

[Q09] 创建唯一索引
来源：http://dali.hywenlv.cn/Article/details/gtnfkwfwln.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.andypj.xyz/Article/details/gtktqnjuze.html

[Q10] 插入单行
来源：http://dali.daria6918.cn/Article/details/gtcgpszdsy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xuanzx.com/Article/details/gtnxvdvrvg.html

[Q11] 一次插入多行
来源：http://dali.c1oappe.top/Article/details/gtpytodnlf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gtvxxzzcpu.html

[Q12] 插入后取自增 ID
来源：http://dali.sxryk.cn/Article/details/gtmjlviilu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxinkj.top/Article/details/gtktdtepgn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gogol.net.cn/Article/details/gtpkzxudfh.html

[Q13] 忽略重复插入
来源：http://dali.xuetiantiany.cn/Article/details/gtrcfmsrmm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nwbrower.top/Article/details/gtdavzigss.html

[Q14] 存在则更新（upsert）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxkgyjxw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sysykeji.top/Article/details/gtvtlmkrpu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.feifeiyinyue.top/Article/details/gtojvsjslx.html

[Q15] 查询全部
来源：http://dali.yj20258888.top/Article/details/gtithxxxvz.html

SELECT * FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gttnlqityc.html

[Q16] 查询指定列
来源：http://dali.cashguo.top/Article/details/gtlqpujjmd.html

SELECT id, name FROM users;
来源：http://dali.wangdashe.top/Article/details/gtecvyprqr.html

[Q17] 条件查询
来源：http://dali.0kj1m.cn/Article/details/gtmbkxudod.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gzhubu.top/Article/details/gtdzutchkr.html

[Q18] 模糊匹配
来源：http://dali.nanxinkj.top/Article/details/gtiyntupvg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.0kj1m.cn/Article/details/gtpoerroyp.html

[Q19] 范围查询
来源：http://dali.daxiang520.top/Article/details/gtbykzyvua.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhongyouzk.top/Article/details/gtlrrrycee.html

[Q20] IN 列表
来源：http://dali.yanxiufei.cn/Article/details/gtmwbrnxoq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhongyouzk.top/Article/details/gtzpypiasq.html

[Q21] 空值判断
来源：http://dali.iojbl.cn/Article/details/gtyxpyivnm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gogol.net.cn/Article/details/gthtpbunkk.html

[Q22] 排序
来源：http://dali.havefunace.top/Article/details/gtznqaulym.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jlsjyb.cn/Article/details/gtwldfjkdk.html

[Q23] 分页
来源：http://dali.fzhhl.top/Article/details/gtipgvgqwm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqqrdprwr.html

[Q24] 去重
来源：http://dali.sysykeji.top/Article/details/gtzermnafe.html

SELECT DISTINCT city FROM users;
来源：http://dali.zycfv.cn/Article/details/gtfdhipucl.html

[Q25] 只取前 N 条
来源：http://dali.mhx1999.top/Article/details/gtchdpsdwc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.snrcjt.cn/Article/details/gtetqnpzqj.html

[Q26] 计数
来源：http://dali.pengpengdd.cyou/Article/details/gthfheczrg.html

SELECT COUNT(*) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtijqsgkgu.html

[Q27] 条件计数
来源：http://dali.tanke756.top/Article/details/gtacdwnsjx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yongpay.top/Article/details/gtmodpxbxr.html

[Q28] 求和与平均
来源：http://dali.hfpthk.cn/Article/details/gtdcilcyka.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtentkwgec.html

[Q29] 最大最小值
来源：http://dali.jiagoushi.top/Article/details/gtqljymmjo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzinryvhd.html

[Q30] 分组统计
来源：http://dali.hammf.cn/Article/details/gtkclxjfrz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gtvnejzndk.html

[Q31] 分组后过滤
来源：http://dali.dianchejie.cn/Article/details/gtuwpmlhxf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zycfv.cn/Article/details/gtewimrlcf.html

[Q32] 分组拼接字符串
来源：http://dali.yj202588.top/Article/details/gtiyfsdzgt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gttzecxbvs.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sxryk.cn/Article/details/gtuyrutvcf.html

[Q33] 多列分组
来源：http://dali.tianlin.xyz/Article/details/gthxhmvxgs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xziqi.cn/Article/details/gtejrbdlha.html

[Q34] 每组取第一条
来源：http://dali.jianghu66.top/Article/details/gtwdsfkehs.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gtsrxgkyko.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sxryk.cn/Article/details/gtqjyxvelk.html

) t WHERE rn = 1;
来源：http://dali.shuidangran.top/Article/details/gthmsdrwli.html

[Q35] 内连接
来源：http://dali.jlsjyb.cn/Article/details/gtjrnrflrp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.mhx1999.top/Article/details/gtiiuaarrz.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gthdgbvbcf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.0kj1m.cn/Article/details/gthekstffu.html

[Q37] 右连接
来源：http://dali.zhengqikj.top/Article/details/gtfzlhgrif.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.fengsongda.top/Article/details/gtzulgdqab.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aizwys.cn/Article/details/gtyovarctp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hysaishi.cn/Article/details/gtodvzjkhk.html

[Q39] 自连接（查上下级）
来源：http://dali.chenzaomai.com/Article/details/gtjnuplyyu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cdnleiting.top/Article/details/gtipliakks.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.smart0.xyz/Article/details/gtxxenxodw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.guowangkeji.top/Article/details/gtepenxghn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zdqjudy.top/Article/details/gtmduabqrs.html

[Q41] 多表连接
来源：http://dali.vqdsnc.cn/Article/details/gtdltxglnt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenjidiqi.icu/Article/details/gtxscfppky.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ybcxt.top/Article/details/gtzleffrrs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cashguo.top/Article/details/gtawnphmdh.html

[Q42] 连接条件附加过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzcctkoz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hywenlv.cn/Article/details/gtbglubbcz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dashuyun.cn/Article/details/gtppbszqnv.html

[Q43] 标量子查询
来源：http://dali.yanxiufei.cn/Article/details/gthwtsrcty.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yj20258.top/Article/details/gtyudnqwms.html

[Q44] IN 子查询
来源：http://dali.hnxiangtu.top/Article/details/gtpnljwsel.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.wangdashe.top/Article/details/gtrqwcbqpt.html

[Q45] EXISTS 判断存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsputxrur.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daxiang520.top/Article/details/gtmeygggdx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jianghu66.top/Article/details/gtvchqykuh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhixingplan.top/Article/details/gtmfpactzc.html

[Q47] 与平均值比较
来源：http://dali.pycfn.com/Article/details/gtccxpsjkd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.smart0.xyz/Article/details/gtxivxbeii.html

[Q48] CTE 公用表表达式
来源：http://dali.ydzc1.top/Article/details/gtelaoewyw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhongyouzk.top/Article/details/gtcianjrmr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.havefunace.top/Article/details/gtmxjymzgb.html

[Q49] 更新单行
来源：http://dali.yuxming.cn/Article/details/gthztimynx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gttsibnqim.html

[Q50] 批量更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtwmngeyvz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gtfajdbfao.html

[Q51] 用子查询更新
来源：http://dali.cashguo.top/Article/details/gtqjeprivt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hywenlv.cn/Article/details/gtbkcpvmhy.html

[Q52] 删除指定行
来源：http://dali.pycfn.com/Article/details/gtkjzradbt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.snrcjt.cn/Article/details/gtigkxyegm.html

[Q53] 按条件删除
来源：http://dali.ydzc1.top/Article/details/gtdtefzyxh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hywenlv.cn/Article/details/gtjxekjmik.html

[Q54] 清空表
来源：http://dali.ybcxt.top/Article/details/gtidemzksn.html

TRUNCATE TABLE logs;
来源：http://dali.nanxuanxn.top/Article/details/gtracylpdq.html

[Q55] 排名（并列占位）
来源：http://dali.jqgfzy.top/Article/details/gtvfblhehp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shangyingyoupin.top/Article/details/gtprhvefdv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dashuyun.cn/Article/details/gttgnjmyaf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.pengpengdd.cyou/Article/details/gtotvytxrt.html

[Q57] 行号
来源：http://dali.cdnleiting.top/Article/details/gtvwggoxwy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpilzgev.html

[Q58] 累计求和
来源：http://dali.nwbrower.top/Article/details/gtekyzzqsh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtvlfylmar.html

[Q59] 分组内累计
来源：http://dali.pengpengdd.cyou/Article/details/gtscuwsbud.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtskxtoaiv.html

[Q60] 取上一行 / 下一行
来源：http://dali.yangfankeji.com/Article/details/gtyzsywqla.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.birdmap.top/Article/details/gtnpiudpmy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtwaihqaaa.html

[Q61] 移动平均
来源：http://dali.c1oappe.top/Article/details/gtbzxgtssq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtuixujfon.html

[Q62] 分组占比
来源：http://dali.yangfankeji.com/Article/details/gtxrjnycdy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gtmrepplir.html

[Q63] 开启事务
来源：http://dali.gotoacloud.top/Article/details/gtqyhpqzko.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.iojbl.cn/Article/details/gtfvaqrbhg.html

[Q64] 提交事务
来源：http://dali.jinqigfzy.top/Article/details/gtybzvdnxf.html

COMMIT;
来源：http://dali.redwolf501.top/Article/details/gtrgpwtjcj.html

[Q65] 回滚事务
来源：http://dali.hysaishi.cn/Article/details/gtljinmdvi.html

ROLLBACK;
来源：http://dali.fzhhl.top/Article/details/gtmmoatnou.html

[Q66] 行锁查询
来源：http://dali.vqdsnc.cn/Article/details/gtvniyvoio.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fzhhl.top/Article/details/gthnlmyaer.html

[Q67] 设置隔离级别
来源：http://dali.sxryk.cn/Article/details/gttsfynhfh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shzxlz.cn/Article/details/gtfhmcorsm.html

[Q68] 保存点
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfxmeqhg.html

SAVEPOINT sp1;
来源：http://dali.jyoumei.cn/Article/details/gtjyhgfioq.html

ROLLBACK TO sp1;
来源：http://dali.0kj1m.cn/Article/details/gtbbwdmply.html

[Q69] 查看执行计划
来源：http://dali.cqqwz.cn/Article/details/gtfyttqvth.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xziqi.cn/Article/details/gtbzxulkxc.html

[Q70] 更新统计信息
来源：http://dali.jinqigfzy.top/Article/details/gtlxopxmdt.html

ANALYZE TABLE users;
来源：http://dali.jlsjyb.cn/Article/details/gtsgomroyg.html

[Q71] 查看建表语句
来源：http://dali.jqgfzy.top/Article/details/gtzgqdahxo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlxsloow.html

[Q72] 查看索引
来源：http://dali.svipenyu.cn/Article/details/gthrrwmoff.html

SHOW INDEX FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtrxhprdto.html

[Q73] 查看表状态
来源：http://dali.sxryk.cn/Article/details/gtqpddvkxw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.vqdsnc.cn/Article/details/gtbvodejak.html

[Q74] 强制使用索引
来源：http://dali.hnqzz.top/Article/details/gtokqevmul.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.dashuyun.cn/Article/details/gttfkpnkfm.html

[Q75] 日期格式化
来源：http://dali.yvedp.cn/Article/details/gtvalimcco.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtbkbiypfo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xziqi.cn/Article/details/gtkbkqnlja.html

[Q76] 按天统计
来源：http://dali.redwolf501.top/Article/details/gtaxjwpdvi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.fzhhl.top/Article/details/gtfewvjref.html

[Q77] 时间加减
来源：http://dali.aibaodan.cn/Article/details/gtkzoldokl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuanzhike.top/Article/details/gtfbwztqdw.html

[Q78] 当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbkwrhmy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.iojbl.cn/Article/details/gthjgagmjm.html

[Q79] 字符串拼接
来源：http://dali.yvedp.cn/Article/details/gtoixjuhfj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yuanzhike.top/Article/details/gtkhdxmtex.html

[Q80] 字符串截取
来源：http://dali.tianlin.xyz/Article/details/gtpbromkfx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtregxotul.html

[Q81] 字符串替换
来源：http://dali.wangdashe.top/Article/details/gtvweqddpd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtvhzcllcn.html

[Q82] 字符长度与字节长度
来源：http://dali.hongshengwenyu.top/Article/details/gtzhmarmfx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtgwyiswbn.html

[Q83] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gtobnoblke.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtzilekhhu.html

[Q84] 去除首尾空格
来源：http://dali.nwbrower.top/Article/details/gtmeegcefw.html

SELECT TRIM(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gtxgvktphq.html

[Q85] 数值取整
来源：http://dali.cheryme.top/Article/details/gtqdkuufzk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.svipenyu.cn/Article/details/gtctraufon.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangtech.top/Article/details/gtsuwlkige.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jianghu66.top/Article/details/gtslpfamhd.html

[Q87] JSON 字段做条件
来源：http://dali.yongpay.top/Article/details/gtwgxtvcjp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sufxvd.cn/Article/details/gtnjutmbxn.html

[Q88] 行转列（条件聚合）
来源：http://dali.daria6918.cn/Article/details/gtzugpsgzk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yuanzhike.top/Article/details/gtsicktfus.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtzjyhfxfq.html

[Q89] 判断表是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyuktkysf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yuanzhike.top/Article/details/gttpqivocl.html

[Q90] 生成序号列
来源：http://dali.nanxuanxn.top/Article/details/gtrgtsgsso.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnxiangtu.top/Article/details/gtqzgmuwvk.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtadnppyuq.html

R. Bash 专题
来源：http://dali.xziqi.cn/Article/details/gtyycqjwmv.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtboyftoil.html

[R01] shebang 与严格模式
来源：http://dali.yanxiufei.cn/Article/details/gtazohqwfn.html

#!/usr/bin/env bash
来源：http://dali.c1oappe.top/Article/details/gtqenuqitm.html

set -euo pipefail
来源：http://dali.tanke756.top/Article/details/gtxikzutiz.html

[R02] 变量赋值与使用
来源：http://dali.hysaishi.cn/Article/details/gtlvtpbgsn.html

name="Tom"; echo "$name"
来源：http://dali.andypj.xyz/Article/details/gtmkvuqhno.html

[R03] 只读变量
来源：http://dali.zycfv.cn/Article/details/gtqlqgbppw.html

readonly PI=3.14
来源：http://dali.haohaochexian.top/Article/details/gtgltwyzce.html

[R04] 位置参数
来源：http://dali.smart0.xyz/Article/details/gtviatlsjn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigfzy.top/Article/details/gtlcfztppy.html

[R05] 参数默认值
来源：http://dali.hysaishi.cn/Article/details/gtqkyesfpw.html

name="${1:-default}"
来源：http://dali.vqdsnc.cn/Article/details/gtibgklluk.html

[R06] 判断命令是否存在
来源：http://dali.pycfn.com/Article/details/gtkiwuqkiq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gtoguagyhm.html

[R07] if 判断文件
来源：http://dali.pycfn.com/Article/details/gtczcqvkzw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yuanzhike.top/Article/details/gtbtrlmeeq.html

[R08] 数值比较
来源：http://dali.0kj1m.cn/Article/details/gtriewjwia.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tian-w.cn/Article/details/gtrwwnpitu.html

[R09] 字符串比较
来源：http://dali.guowangkeji.top/Article/details/gtwprfiaqc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guannengcc.top/Article/details/gtwqzpeczn.html

[R10] 正则匹配
来源：http://dali.chenlongwang.top/Article/details/gtdvgilmdv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xziqi.cn/Article/details/gtltdjxeqi.html

[R11] case 多分支
来源：http://dali.shangyingyoupin.top/Article/details/gtewztpllo.html

case "$1" in
来源：http://dali.shzxlz.cn/Article/details/gtvfkjqhje.html

start) echo "启动" ;;
来源：http://dali.yj202588.top/Article/details/gttgbnkprt.html

stop)  echo "停止" ;;
来源：http://dali.fengsongda.top/Article/details/gtmljdqtoy.html

*)     echo "未知命令" ;;
来源：http://dali.xuanzx.com/Article/details/gtxwpnafgw.html

esac
来源：http://dali.zhiwuduotai.top/Article/details/gtlejlkgmu.html

[R12] for 遍历文件
来源：http://dali.bjfxy.top/Article/details/gttoqwiynu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ehwqpu.com/Article/details/gteyhlikqm.html

[R13] for 计数循环
来源：http://dali.vqdsnc.cn/Article/details/gtyjmfsglm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gogol.net.cn/Article/details/gtgmkzrufk.html

[R14] C 风格 for
来源：http://dali.snrcjt.cn/Article/details/gtjlxfmeoj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gthudbwtpu.html

[R15] while 逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gttdaaihjv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jlsjyb.cn/Article/details/gtvkfiphoj.html

[R16] until 等待条件
来源：http://dali.xziqi.cn/Article/details/gtotihdqbu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gtmfenabrw.html

[R17] 数组定义与取值
来源：http://dali.jqgufenzy.top/Article/details/gtyntqnvsg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shuidangran.top/Article/details/gtczojbiem.html

[R18] 遍历数组
来源：http://dali.chenjidiqi.icu/Article/details/gtmrdgsvge.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yanxiufei.cn/Article/details/gtbpanthlq.html

[R19] 数组长度
来源：http://dali.pycfn.com/Article/details/gtakieatte.html

echo "${#arr[@]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnxjchim.html

[R20] 关联数组（字典）
来源：http://dali.zhongyouzk.top/Article/details/gtyapbgupx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.fengsongda.top/Article/details/gtfmntittn.html

[R21] 字符串长度
来源：http://dali.redwolf501.top/Article/details/gtitbhxcza.html

echo "${#s}"
来源：http://dali.aibaodan.cn/Article/details/gtondhkqtx.html

[R22] 截取子串
来源：http://dali.cashguo.top/Article/details/gtcjrbdjlk.html

echo "${s:0:5}"
来源：http://dali.hnqzz.top/Article/details/gtwikjwfot.html

[R23] 字符串替换
来源：http://dali.c1oappe.top/Article/details/gtvuxwwixf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.redwolf501.top/Article/details/gtttihbvjr.html

[R24] 大小写转换
来源：http://dali.hammf.cn/Article/details/gtdfzggkjj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvqdljlz.html

[R25] 去后缀 / 去前缀
来源：http://dali.daxiang520.top/Article/details/gtapprhqrm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jianghu66.top/Article/details/gtucetajuk.html

[R26] 命令替换
来源：http://dali.redwolf501.top/Article/details/gtfpxjaqbj.html

now=$(date +%F); echo "$now"
来源：http://dali.yj20258.top/Article/details/gtgbicyfdw.html

[R27] 算术展开
来源：http://dali.cucudq.cn/Article/details/gtwkrzinza.html

echo $((1 + 2 * 3))
来源：http://dali.316326.xyz/Article/details/gtggpgbzji.html

[R28] 浮点运算
来源：http://dali.cashguo.top/Article/details/gtbzyosvox.html

echo "scale=2; 10/3" | bc
来源：http://dali.zdqjudy.top/Article/details/gtgosddcoq.html

[R29] 定义函数
来源：http://dali.cucudq.cn/Article/details/gtmwiinhly.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.andypj.xyz/Article/details/gtxdrqkryy.html

[R30] 函数返回状态码
来源：http://dali.yanxiufei.cn/Article/details/gtbuebzqaw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cdnleiting.top/Article/details/gtsdspirft.html

[R31] 局部变量
来源：http://dali.hysaishi.cn/Article/details/gtvarqeqby.html

f() { local x=1; echo "$x"; }
来源：http://dali.andypj.xyz/Article/details/gtfjswfqof.html

[R32] 参数个数校验
来源：http://dali.chenlongwang.top/Article/details/gtgbmsmfzv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hywenlv.cn/Article/details/gthcjpyfid.html

[R33] 捕获错误并提示行号
来源：http://dali.sysykeji.top/Article/details/gtsqrkomdy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.wangdashe.top/Article/details/gtjytvugyp.html

[R34] 退出时清理
来源：http://dali.ppjwa.cn/Article/details/gtfjcfhdwq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gtkkuhkiye.html

[R35] 后台执行并等待
来源：http://dali.ivvv.top/Article/details/gtwrsfuxgc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangtech.top/Article/details/gtgozikrpm.html

[R36] 并发执行多个任务
来源：http://dali.nwbrower.top/Article/details/gtshmabgnz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxinkj.top/Article/details/gtjxuybypp.html

[R37] 把输出赋给变量
来源：http://dali.chenjidiqi.icu/Article/details/gttjphehvk.html

files=$(ls -1)
来源：http://dali.pengpengdd.cyou/Article/details/gtkyhixzwx.html

[R38] 管道串联
来源：http://dali.hnqzz.top/Article/details/gtchezijlz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.smart0.xyz/Article/details/gtqyylmqyu.html

[R39] 重定向标准输出与错误
来源：http://dali.gogol.net.cn/Article/details/gtbxubykba.html

cmd > out.log 2>&1
来源：http://dali.svipenyu.cn/Article/details/gtfoyvyxuo.html

[R40] 追加写日志
来源：http://dali.pengpengdd.cyou/Article/details/gtmbkczfxs.html

echo "log" >> out.log
来源：http://dali.xinyue.icu/Article/details/gtxnagfnqw.html

[R41] 丢弃输出
来源：http://dali.yuanzhike.top/Article/details/gtmjnnhojw.html

cmd >/dev/null 2>&1
来源：http://dali.yj20258.top/Article/details/gtlqmalhys.html

[R42] 输入重定向
来源：http://dali.meibo888.top/Article/details/gtuutoxvuj.html

wc -l < a.txt
来源：http://dali.hammf.cn/Article/details/gtjoeugzzd.html

[R43] 按名字查找文件
来源：http://dali.haohaochexian.top/Article/details/gtonvhfqer.html

find . -name "*.log" -type f
来源：http://dali.nanxinkj.top/Article/details/gthauufuaw.html

[R44] 按修改时间查找
来源：http://dali.fzhhl.top/Article/details/gtqwrynvml.html

find . -mtime -7 -type f
来源：http://dali.daria6918.cn/Article/details/gtwzcwfkdh.html

[R45] 批量删除
来源：http://dali.xinyue.icu/Article/details/gtdozmxgpu.html

find . -name "*.tmp" -delete
来源：http://dali.c1oappe.top/Article/details/gtznypodob.html

[R46] 递归替换文件内容
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidigvbar.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhengqikj.top/Article/details/gtlvkdqeqx.html

[R47] sed 单行替换
来源：http://dali.andypj.xyz/Article/details/gtyjtgeslo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.smart0.xyz/Article/details/gtdzgtqjws.html

[R48] awk 取指定列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbubwbgs.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenlongwang.top/Article/details/gtyyzugfdj.html

[R49] awk 带条件
来源：http://dali.hammf.cn/Article/details/gtidwuagzr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yangfankeji.com/Article/details/gtuqlgwwml.html

[R50] awk 求和
来源：http://dali.ybcxt.top/Article/details/gtccgsbqqh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtfrlfkgdv.html

[R51] 排序去重取前几
来源：http://dali.shuidangran.top/Article/details/gtrrwcqhhl.html


<!-- 参考信息 -->