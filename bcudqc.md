代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jianghu66.top/Article/details/gtdqvbtzlm.html

user_id INT NOT NULL,
来源：http://dali.zhongyouzk.top/Article/details/gtfbfkvbpw.html

amount DECIMAL(10, 2),
来源：http://dali.yvedp.cn/Article/details/gtuacfrjyw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xziqi.cn/Article/details/gtiurevpcs.html

);
来源：http://dali.cqqwz.cn/Article/details/gtuuhoixsg.html

[Q03] 增加列
来源：http://dali.chenjidiqi.icu/Article/details/gtzqgwddfb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.tianlin.xyz/Article/details/gtrwplmuki.html

[Q04] 修改列类型
来源：http://dali.tian-w.cn/Article/details/gtzomixjop.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ydzc1.top/Article/details/gtnjeyjozr.html

[Q05] 重命名列
来源：http://dali.nwbrower.top/Article/details/gteqyqjvhk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xylfe.cn/Article/details/gtacvrugcu.html

[Q06] 删除列
来源：http://dali.sxryk.cn/Article/details/gtkmllxrzt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cheryme.top/Article/details/gtkmepzuoq.html

[Q07] 删除表
来源：http://dali.hongshengwenyu.top/Article/details/gtabbhiqzg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hfpthk.cn/Article/details/gtsejixheo.html

[Q08] 创建普通索引
来源：http://dali.shuidangran.top/Article/details/gtwgwmqubs.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangdashe.top/Article/details/gtlvrlzkuf.html

[Q09] 创建唯一索引
来源：http://dali.cqqwz.cn/Article/details/gtefnkiodk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gotoacloud.top/Article/details/gtjsjlhyqj.html

[Q10] 插入单行
来源：http://dali.316326.xyz/Article/details/gtfgfouaer.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hysaishi.cn/Article/details/gtxfnscmax.html

[Q11] 一次插入多行
来源：http://dali.chenjidiqi.icu/Article/details/gtawkzbehe.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj20258888.top/Article/details/gtequgsgbk.html

[Q12] 插入后取自增 ID
来源：http://dali.ppjwa.cn/Article/details/gtygzcuycr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.dianchejie.cn/Article/details/gtdkvfogkb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.wangdashe.top/Article/details/gttbygwdtf.html

[Q13] 忽略重复插入
来源：http://dali.guannengcc.top/Article/details/gtdkhfgiav.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pycfn.com/Article/details/gtkpevhivf.html

[Q14] 存在则更新（upsert）
来源：http://dali.mhx1999.top/Article/details/gtehlbzwxy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.aibaodan.cn/Article/details/gtkjexvihq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtalqcotkx.html

[Q15] 查询全部
来源：http://dali.c1oappe.top/Article/details/gthayoplbi.html

SELECT * FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtbhbpiieq.html

[Q16] 查询指定列
来源：http://dali.hysaishi.cn/Article/details/gtiummsaoc.html

SELECT id, name FROM users;
来源：http://dali.sysykeji.top/Article/details/gtiziguhnd.html

[Q17] 条件查询
来源：http://dali.shzxlz.cn/Article/details/gtmhhnvuxt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtxncxmidm.html

[Q18] 模糊匹配
来源：http://dali.yvedp.cn/Article/details/gtunksinhb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cdnleiting.top/Article/details/gtinzqsabn.html

[Q19] 范围查询
来源：http://dali.ydzc1.top/Article/details/gttrzdlccg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuetiantiany.cn/Article/details/gtqwgdrfik.html

[Q20] IN 列表
来源：http://dali.cheryme.top/Article/details/gtkvkdobux.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjeolziw.html

[Q21] 空值判断
来源：http://dali.cdnleiting.top/Article/details/gtscoqxhxd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cqqwz.cn/Article/details/gtyqpvlgob.html

[Q22] 排序
来源：http://dali.hnqzz.top/Article/details/gtlkwlwckp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.quarkkingdee.top/Article/details/gtkjdchorm.html

[Q23] 分页
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsluospic.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xziqi.cn/Article/details/gtijvchhjl.html

[Q24] 去重
来源：http://dali.bjfxy.top/Article/details/gtyhwciktr.html

SELECT DISTINCT city FROM users;
来源：http://dali.hywenlv.cn/Article/details/gteygfjfhd.html

[Q25] 只取前 N 条
来源：http://dali.yonumen.top/Article/details/gttkkeoxtr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yonumen.top/Article/details/gtzcqqiydv.html

[Q26] 计数
来源：http://dali.birdmap.top/Article/details/gtcwejkffn.html

SELECT COUNT(*) FROM users;
来源：http://dali.sweek.top/Article/details/gtkosirxnj.html

[Q27] 条件计数
来源：http://dali.guowangkeji.top/Article/details/gtvspacypm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtoivnzjxh.html

[Q28] 求和与平均
来源：http://dali.ppjwa.cn/Article/details/gteankfjxz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtzdrsjyvi.html

[Q29] 最大最小值
来源：http://dali.cqqwz.cn/Article/details/gthszciumh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtookyoxjr.html

[Q30] 分组统计
来源：http://dali.wangshuangyany.cn/Article/details/gtaqpyneqb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gtrlzlvxgl.html

[Q31] 分组后过滤
来源：http://dali.ppjwa.cn/Article/details/gtdywgieyt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.bjfxy.top/Article/details/gtsldasdds.html

[Q32] 分组拼接字符串
来源：http://dali.bjfxy.top/Article/details/gtecboaujj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gtidyqmnln.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cashguo.top/Article/details/gtabbfvauu.html

[Q33] 多列分组
来源：http://dali.tianlin.xyz/Article/details/gttwytaczo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.bjfxy.top/Article/details/gthuptrqcu.html

[Q34] 每组取第一条
来源：http://dali.snrcjt.cn/Article/details/gtwnxfsivh.html

SELECT * FROM (
来源：http://dali.ppjwa.cn/Article/details/gtmigecapl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenlongwang.top/Article/details/gtkdixxmlb.html

) t WHERE rn = 1;
来源：http://dali.sysykeji.top/Article/details/gtargzajzu.html

[Q35] 内连接
来源：http://dali.ppjwa.cn/Article/details/gtlcatdzrt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtuvyiyzam.html

[Q36] 左连接
来源：http://dali.haohaochexian.top/Article/details/gteqwzphwq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.pengpengdd.cyou/Article/details/gtfbcdsyoa.html

[Q37] 右连接
来源：http://dali.vqdsnc.cn/Article/details/gtkhexneya.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.mhx1999.top/Article/details/gtiibwxwer.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jqgufenzy.top/Article/details/gtbfajtlar.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.mhx1999.top/Article/details/gtwhislpxs.html

[Q39] 自连接（查上下级）
来源：http://dali.havefunace.top/Article/details/gtzsdxauft.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zdqjudy.top/Article/details/gtufvpmnju.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxnkduhz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangshuangyany.cn/Article/details/gticpawdmq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cqqwz.cn/Article/details/gtqpypmjjq.html

[Q41] 多表连接
来源：http://dali.nanxuanxn.top/Article/details/gtobkhioxt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gtjmwktild.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenlongwang.top/Article/details/gtcytrdzku.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yanxiufei.cn/Article/details/gtiabeuofw.html

[Q42] 连接条件附加过滤
来源：http://dali.hfpthk.cn/Article/details/gtwvyjzhpt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hywenlv.cn/Article/details/gtneebhvwd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shuidangran.top/Article/details/gtqpfnuyad.html

[Q43] 标量子查询
来源：http://dali.aizwys.cn/Article/details/gtivpskbse.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gogol.net.cn/Article/details/gtgfwqokpt.html

[Q44] IN 子查询
来源：http://dali.cqqwz.cn/Article/details/gtnbypzbzl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xinyue.icu/Article/details/gtxesqcnpl.html

[Q45] EXISTS 判断存在
来源：http://dali.yj20258.top/Article/details/gtjvluygzv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hysaishi.cn/Article/details/gtnevmwjxe.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jyoumei.cn/Article/details/gtcxposixn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gtcnfxglet.html

[Q47] 与平均值比较
来源：http://dali.yanxiufei.cn/Article/details/gtmqomafyz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jyoumei.cn/Article/details/gthxzshcek.html

[Q48] CTE 公用表表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvwesjkv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.haohaochexian.top/Article/details/gteopcoazd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.snrcjt.cn/Article/details/gtvgkuoxpd.html

[Q49] 更新单行
来源：http://dali.cucudq.cn/Article/details/gtnzrwbuhc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sysykeji.top/Article/details/gtwrxdofvx.html

[Q50] 批量更新
来源：http://dali.dianchejie.cn/Article/details/gtftgbisia.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sweek.top/Article/details/gtvcvfjcoy.html

[Q51] 用子查询更新
来源：http://dali.sxryk.cn/Article/details/gtywrvhnpz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhixingplan.top/Article/details/gteraellin.html

[Q52] 删除指定行
来源：http://dali.sysykeji.top/Article/details/gtgstxmwdy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ehwqpu.com/Article/details/gtjpfixnzo.html

[Q53] 按条件删除
来源：http://dali.smart0.xyz/Article/details/gtetisnkzt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gtuzxqaozg.html

[Q54] 清空表
来源：http://dali.guannengcc.top/Article/details/gtlpsbhnyz.html

TRUNCATE TABLE logs;
来源：http://dali.tian-w.cn/Article/details/gtvrurqsmb.html

[Q55] 排名（并列占位）
来源：http://dali.cashguo.top/Article/details/gtgjiozrut.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gotoacloud.top/Article/details/gtmuccxxsm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdsuqswiw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gthyhpsfpd.html

[Q57] 行号
来源：http://dali.gzhubu.top/Article/details/gtbwzgqkqk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtbcwiaffu.html

[Q58] 累计求和
来源：http://dali.jlsjyb.cn/Article/details/gtcucoklmk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtqouxdvtw.html

[Q59] 分组内累计
来源：http://dali.shanyushiyangtech.top/Article/details/gtigyykfst.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtbyplpfmm.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigfzy.top/Article/details/gtylymkfwh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.quarkkingdee.top/Article/details/gtacqyvkrr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtyonjyedv.html

[Q61] 移动平均
来源：http://dali.shangyingyoupin.top/Article/details/gteasuxari.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtvnrwsmni.html

[Q62] 分组占比
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgbmxmfj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gtlrafgwkr.html

[Q63] 开启事务
来源：http://dali.wangdashe.top/Article/details/gtchyghger.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.guowangkeji.top/Article/details/gtmdzfstxy.html

[Q64] 提交事务
来源：http://dali.cashguo.top/Article/details/gtdenjfvru.html

COMMIT;
来源：http://dali.chenjidiqi.icu/Article/details/gtxvwdfvrm.html

[Q65] 回滚事务
来源：http://dali.316326.xyz/Article/details/gtdnspalhv.html

ROLLBACK;
来源：http://dali.xuanzx.com/Article/details/gtlydvkbco.html

[Q66] 行锁查询
来源：http://dali.hnqzz.top/Article/details/gtkfxpariy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gtqkyqouzz.html

[Q67] 设置隔离级别
来源：http://dali.jqgufenzy.top/Article/details/gtucfjxubu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gaohongyu789.top/Article/details/gtldgitvze.html

[Q68] 保存点
来源：http://dali.zhongyouzk.top/Article/details/gtsnatezth.html

SAVEPOINT sp1;
来源：http://dali.ppjwa.cn/Article/details/gtyawcpcfl.html

ROLLBACK TO sp1;
来源：http://dali.c1oappe.top/Article/details/gtsnebilww.html

[Q69] 查看执行计划
来源：http://dali.yj202588.top/Article/details/gtvmkqtmug.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhiwuduotai.top/Article/details/gtwctgwekq.html

[Q70] 更新统计信息
来源：http://dali.wangdashe.top/Article/details/gtwsrwkcpt.html

ANALYZE TABLE users;
来源：http://dali.hongshengwenyu.top/Article/details/gtneyyyajb.html

[Q71] 查看建表语句
来源：http://dali.snrcjt.cn/Article/details/gtrhxpidja.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfvtyyub.html

[Q72] 查看索引
来源：http://dali.chenzaomai.com/Article/details/gtcpoootwi.html

SHOW INDEX FROM users;
来源：http://dali.cashguo.top/Article/details/gthyjhlmgh.html

[Q73] 查看表状态
来源：http://dali.hammf.cn/Article/details/gtuykhjnek.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycgtqvav.html

[Q74] 强制使用索引
来源：http://dali.havefunace.top/Article/details/gtzrvhcblq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenzaomai.com/Article/details/gtofmbkgsh.html

[Q75] 日期格式化
来源：http://dali.aibaodan.cn/Article/details/gtadeglhgq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtszqwkaqc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sufxvd.cn/Article/details/gtzdhpbxsr.html

[Q76] 按天统计
来源：http://dali.hongshengwenyu.top/Article/details/gtxmsplwmy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenlongwang.top/Article/details/gtuaoamveb.html

[Q77] 时间加减
来源：http://dali.cashguo.top/Article/details/gtwodejekn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hammf.cn/Article/details/gtmugwvvrj.html

[Q78] 当前时间
来源：http://dali.aibaodan.cn/Article/details/gtzrgbhwzm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.svipenyu.cn/Article/details/gtgaryoknm.html

[Q79] 字符串拼接
来源：http://dali.vqdsnc.cn/Article/details/gtziqabrel.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.fzhhl.top/Article/details/gtzowrllal.html

[Q80] 字符串截取
来源：http://dali.smart0.xyz/Article/details/gtzxfasffq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtvibiqfxb.html

[Q81] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gtogjfrlsc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtzpxnlfep.html

[Q82] 字符长度与字节长度
来源：http://dali.bjfxy.top/Article/details/gtytfnujih.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtxmyqaofh.html

[Q83] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gtfoquhgbk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtwivznfyb.html

[Q84] 去除首尾空格
来源：http://dali.mhx1999.top/Article/details/gtzrjwfzzk.html

SELECT TRIM(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtyycrehxz.html

[Q85] 数值取整
来源：http://dali.hywenlv.cn/Article/details/gtreguoycr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dashuyun.cn/Article/details/gtfllulpso.html

[Q86] 读取 JSON 字段
来源：http://dali.hfpthk.cn/Article/details/gtffjxigyw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shangyingyoupin.top/Article/details/gtqbvxlefz.html

[Q87] JSON 字段做条件
来源：http://dali.yj20258.top/Article/details/gtwzrfaqcz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.9152youxi.cn/Article/details/gtrpdbtggy.html

[Q88] 行转列（条件聚合）
来源：http://dali.gogol.net.cn/Article/details/gtemeblftx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guannengcc.top/Article/details/gtkwvsemqg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gttfhakbzt.html

[Q89] 判断表是否存在
来源：http://dali.yj20258888.top/Article/details/gtiuzlwgqu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.svipenyu.cn/Article/details/gtuiigubdu.html

[Q90] 生成序号列
来源：http://dali.9152youxi.cn/Article/details/gtcawymjyy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shangyingyoupin.top/Article/details/gtbzhpehbw.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gthduncpwm.html

R. Bash 专题
来源：http://dali.redwolf501.top/Article/details/gtwtmfxxxe.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtleabrtds.html

[R01] shebang 与严格模式
来源：http://dali.snrcjt.cn/Article/details/gtcmtxbmlb.html

#!/usr/bin/env bash
来源：http://dali.guowangkeji.top/Article/details/gtdomwfhjp.html

set -euo pipefail
来源：http://dali.redwolf501.top/Article/details/gtcykapuis.html

[R02] 变量赋值与使用
来源：http://dali.jyoumei.cn/Article/details/gtznfcqlxm.html

name="Tom"; echo "$name"
来源：http://dali.hysaishi.cn/Article/details/gtujtbeyky.html

[R03] 只读变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuexxlmpq.html

readonly PI=3.14
来源：http://dali.hongshengwenyu.top/Article/details/gtztyhtttw.html

[R04] 位置参数
来源：http://dali.zdqjudy.top/Article/details/gtkjnpaqvp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.havefunace.top/Article/details/gtjthvpwhi.html

[R05] 参数默认值
来源：http://dali.gogol.net.cn/Article/details/gtbkffrzob.html

name="${1:-default}"
来源：http://dali.shanyushiyangtech.top/Article/details/gttufidvmu.html

[R06] 判断命令是否存在
来源：http://dali.yvedp.cn/Article/details/gtslakzuvs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.9152youxi.cn/Article/details/gtqrwvsymm.html

[R07] if 判断文件
来源：http://dali.dashuyun.cn/Article/details/gtmzmciuiy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.0kj1m.cn/Article/details/gtujfnmsax.html

[R08] 数值比较
来源：http://dali.snrcjt.cn/Article/details/gtuhticcli.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtxbyqjbzz.html

[R09] 字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtruqtuacw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tian-w.cn/Article/details/gthynsosre.html

[R10] 正则匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtbqkohngz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuanzhike.top/Article/details/gtrmgmqqho.html

[R11] case 多分支
来源：http://dali.vqdsnc.cn/Article/details/gtspytwkhf.html

case "$1" in
来源：http://dali.zycfv.cn/Article/details/gtwwpygpvz.html

start) echo "启动" ;;
来源：http://dali.xuanzx.com/Article/details/gtflwxddeh.html

stop)  echo "停止" ;;
来源：http://dali.smart0.xyz/Article/details/gtwwmwiwgh.html

*)     echo "未知命令" ;;
来源：http://dali.iojbl.cn/Article/details/gtnvxacohr.html

esac
来源：http://dali.mhx1999.top/Article/details/gtjfohujfd.html

[R12] for 遍历文件
来源：http://dali.smart0.xyz/Article/details/gtzueqnmob.html

for f in *.txt; do echo "$f"; done
来源：http://dali.c1oappe.top/Article/details/gtcjqvkckk.html

[R13] for 计数循环
来源：http://dali.cqqwz.cn/Article/details/gtiyeyrcmt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.iojbl.cn/Article/details/gteubiqjho.html

[R14] C 风格 for
来源：http://dali.hysaishi.cn/Article/details/gtqjrrsgbc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtsmqxjihd.html

[R15] while 逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtocdaeyge.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.dashuyun.cn/Article/details/gtljlctndx.html

[R16] until 等待条件
来源：http://dali.hongshengwenyu.top/Article/details/gtknqqaytr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gaohongyu789.top/Article/details/gtbogiwvvb.html

[R17] 数组定义与取值
来源：http://dali.wangshuangyany.cn/Article/details/gtigldznff.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.redwolf501.top/Article/details/gtwbxukyyv.html

[R18] 遍历数组
来源：http://dali.zycfv.cn/Article/details/gtiwkdjzwg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yonumen.top/Article/details/gtelqouzpe.html

[R19] 数组长度
来源：http://dali.xylfe.cn/Article/details/gtqvprhgnj.html

echo "${#arr[@]}"
来源：http://dali.tianlin.xyz/Article/details/gtwpjucltu.html

[R20] 关联数组（字典）
来源：http://dali.zhixingplan.top/Article/details/gtedgwoodp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xuanzx.com/Article/details/gtnydalzfs.html

[R21] 字符串长度
来源：http://dali.yonumen.top/Article/details/gtzfaiiytv.html

echo "${#s}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtroylsdwy.html

[R22] 截取子串
来源：http://dali.cheryme.top/Article/details/gtnotupczn.html

echo "${s:0:5}"
来源：http://dali.shzxlz.cn/Article/details/gteedrjobh.html

[R23] 字符串替换
来源：http://dali.nanxinkj.top/Article/details/gtvdmmurmd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gogol.net.cn/Article/details/gtmfzbbntb.html

[R24] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gtgkzzxrjd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.redwolf501.top/Article/details/gtjvzkgppm.html

[R25] 去后缀 / 去前缀
来源：http://dali.nanxuanxn.top/Article/details/gtliennxrb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hywenlv.cn/Article/details/gtylwhgzik.html

[R26] 命令替换
来源：http://dali.xylfe.cn/Article/details/gtbbrxcoxp.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigfzy.top/Article/details/gtisyrzmlc.html

[R27] 算术展开
来源：http://dali.daria6918.cn/Article/details/gtfkioyqqq.html

echo $((1 + 2 * 3))
来源：http://dali.mhx1999.top/Article/details/gtvqyoemvf.html

[R28] 浮点运算
来源：http://dali.yongpay.top/Article/details/gtayrbqhns.html

echo "scale=2; 10/3" | bc
来源：http://dali.sxryk.cn/Article/details/gtpelqagdj.html

[R29] 定义函数
来源：http://dali.birdmap.top/Article/details/gtsjukqknk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.0kj1m.cn/Article/details/gtabhuwcoc.html

[R30] 函数返回状态码
来源：http://dali.dianchejie.cn/Article/details/gteqrusztg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhengqikj.top/Article/details/gtdgmzspmh.html

[R31] 局部变量
来源：http://dali.guowangkeji.top/Article/details/gtyznqhepq.html

f() { local x=1; echo "$x"; }
来源：http://dali.redwolf501.top/Article/details/gtrtuzadsk.html

[R32] 参数个数校验
来源：http://dali.hnqzz.top/Article/details/gtolyfgcjs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fzhhl.top/Article/details/gtipaeuhhs.html

[R33] 捕获错误并提示行号
来源：http://dali.hnxiangtu.top/Article/details/gtipefmvtv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tianlin.xyz/Article/details/gtcfmpcvcd.html

[R34] 退出时清理
来源：http://dali.cdnleiting.top/Article/details/gttaiqzcwp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gtyjqbvglx.html

[R35] 后台执行并等待
来源：http://dali.xziqi.cn/Article/details/gtmskppdfu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigfzy.top/Article/details/gtrfobezdi.html

[R36] 并发执行多个任务
来源：http://dali.shangyingyoupin.top/Article/details/gtiskukhxm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xylfe.cn/Article/details/gtdlmkjogr.html

[R37] 把输出赋给变量
来源：http://dali.pycfn.com/Article/details/gtjaemudbq.html

files=$(ls -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdoamgcs.html

[R38] 管道串联
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgkqjdxh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gtbepwpjop.html

[R39] 重定向标准输出与错误
来源：http://dali.cashguo.top/Article/details/gtwkfviktk.html

cmd > out.log 2>&1
来源：http://dali.cheryme.top/Article/details/gtjvpocxbu.html

[R40] 追加写日志
来源：http://dali.yangfankeji.com/Article/details/gttmdrxspm.html

echo "log" >> out.log
来源：http://dali.fzhhl.top/Article/details/gtuhklrjgn.html

[R41] 丢弃输出
来源：http://dali.ehwqpu.com/Article/details/gtktdrhcuz.html

cmd >/dev/null 2>&1
来源：http://dali.guowangkeji.top/Article/details/gttvqibstj.html

[R42] 输入重定向
来源：http://dali.guowangkeji.top/Article/details/gtxbfnepdx.html

wc -l < a.txt
来源：http://dali.andypj.xyz/Article/details/gtcujkhjil.html

[R43] 按名字查找文件
来源：http://dali.jyoumei.cn/Article/details/gtltalndvm.html

find . -name "*.log" -type f
来源：http://dali.haohaochexian.top/Article/details/gtdboywyry.html

[R44] 按修改时间查找
来源：http://dali.xziqi.cn/Article/details/gtqqcbwwss.html

find . -mtime -7 -type f
来源：http://dali.ydzc1.top/Article/details/gthdxlcgta.html

[R45] 批量删除
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpulcfefu.html

find . -name "*.tmp" -delete
来源：http://dali.316326.xyz/Article/details/gtnltuwvrn.html

[R46] 递归替换文件内容
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvicsskxj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nanxinkj.top/Article/details/gtfmraufcv.html

[R47] sed 单行替换
来源：http://dali.yanxiufei.cn/Article/details/gtngpgbiyk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cashguo.top/Article/details/gtijlkcygi.html

[R48] awk 取指定列
来源：http://dali.jqgfzy.top/Article/details/gthvvwjorm.html

awk '{print $1, $3}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtluwebdvg.html

[R49] awk 带条件
来源：http://dali.shuidangran.top/Article/details/gtbzdowixj.html


<!-- 参考信息 -->