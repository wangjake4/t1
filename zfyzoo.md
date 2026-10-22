代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sxryk.cn/Article/details/gtiqfhvqrm.html

[Q05] 重命名列
来源：http://dali.yanxiufei.cn/Article/details/gtctdpnzui.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hammf.cn/Article/details/gtfijdlilj.html

[Q06] 删除列
来源：http://dali.gzhubu.top/Article/details/gtieykmzhu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guannengcc.top/Article/details/gticjfnnsr.html

[Q07] 删除表
来源：http://dali.dashuyun.cn/Article/details/gtewfsiplc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cashguo.top/Article/details/gtlevmapqk.html

[Q08] 创建普通索引
来源：http://dali.feifeiyinyue.top/Article/details/gtspaoggnf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cdnleiting.top/Article/details/gthjwujwzu.html

[Q09] 创建唯一索引
来源：http://dali.0kj1m.cn/Article/details/gtqaiyxqjc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgqofvzz.html

[Q10] 插入单行
来源：http://dali.yangfankeji.com/Article/details/gtlnbtxkxf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ivvv.top/Article/details/gtzneztewk.html

[Q11] 一次插入多行
来源：http://dali.zycfv.cn/Article/details/gtgyktlict.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yonumen.top/Article/details/gtdajiklfp.html

[Q12] 插入后取自增 ID
来源：http://dali.shuidangran.top/Article/details/gteabuppeo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.feifeiyinyue.top/Article/details/gtfbfuvcwh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xinyue.icu/Article/details/gtrrsfboyr.html

[Q13] 忽略重复插入
来源：http://dali.fzhhl.top/Article/details/gtmaktdpbd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yvedp.cn/Article/details/gtjnrkxbwd.html

[Q14] 存在则更新（upsert）
来源：http://dali.dashuyun.cn/Article/details/gtrabzooja.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cqqwz.cn/Article/details/gtenjwzfyj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jyoumei.cn/Article/details/gtunabedjr.html

[Q15] 查询全部
来源：http://dali.daxiang520.top/Article/details/gtyywogfvk.html

SELECT * FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtfqqnhroj.html

[Q16] 查询指定列
来源：http://dali.andypj.xyz/Article/details/gtcezuppqe.html

SELECT id, name FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtarmzatqx.html

[Q17] 条件查询
来源：http://dali.daria6918.cn/Article/details/gtlyioibpb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fzhhl.top/Article/details/gtccdjlaal.html

[Q18] 模糊匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmstktnqy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sxryk.cn/Article/details/gtfbegdqfi.html

[Q19] 范围查询
来源：http://dali.yueranfly.top/Article/details/gtyqyeckdd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttctvffzb.html

[Q20] IN 列表
来源：http://dali.yuxming.cn/Article/details/gtohihhrnh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtudqowkmq.html

[Q21] 空值判断
来源：http://dali.ydzc1.top/Article/details/gtxenojvth.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.svipenyu.cn/Article/details/gtketxdhgz.html

[Q22] 排序
来源：http://dali.yangfankeji.com/Article/details/gtqheofdmi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszphpsog.html

[Q23] 分页
来源：http://dali.hnxiangtu.top/Article/details/gtagyoigda.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ydzc1.top/Article/details/gtcnousbyg.html

[Q24] 去重
来源：http://dali.yanxiufei.cn/Article/details/gtflcbhtca.html

SELECT DISTINCT city FROM users;
来源：http://dali.gzhubu.top/Article/details/gtlyotnpgf.html

[Q25] 只取前 N 条
来源：http://dali.jlsjyb.cn/Article/details/gtzuzctwuz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yonumen.top/Article/details/gtvpjgyqey.html

[Q26] 计数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcpoeoyqw.html

SELECT COUNT(*) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gteftjcfwl.html

[Q27] 条件计数
来源：http://dali.mhx1999.top/Article/details/gttuzkgvys.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtoqhlsuvd.html

[Q28] 求和与平均
来源：http://dali.ybcxt.top/Article/details/gtknzldeni.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqzbfysv.html

[Q29] 最大最小值
来源：http://dali.9152youxi.cn/Article/details/gtoyzsggxi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtqgqsqcnx.html

[Q30] 分组统计
来源：http://dali.zycfv.cn/Article/details/gtwwkfrwte.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gtyhrwoidx.html

[Q31] 分组后过滤
来源：http://dali.ehwqpu.com/Article/details/gtlejntqch.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinqigfzy.top/Article/details/gtikxmtaed.html

[Q32] 分组拼接字符串
来源：http://dali.xuanzx.com/Article/details/gtjuyictcj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gtezikiebh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shuidangran.top/Article/details/gtaiuchovp.html

[Q33] 多列分组
来源：http://dali.svipenyu.cn/Article/details/gtlohmgzqv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhiwuduotai.top/Article/details/gtfdtjqfkq.html

[Q34] 每组取第一条
来源：http://dali.zhiwuduotai.top/Article/details/gtfcnceyxd.html

SELECT * FROM (
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxskcpbxr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jyoumei.cn/Article/details/gtbktggsuk.html

) t WHERE rn = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtoqqpotxl.html

[Q35] 内连接
来源：http://dali.fengsongda.top/Article/details/gtsrrredul.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gteheliflb.html

[Q36] 左连接
来源：http://dali.xziqi.cn/Article/details/gtgdluxgph.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtyrbgetnl.html

[Q37] 右连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlklsctti.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.fengsongda.top/Article/details/gtsmftcrnu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.smart0.xyz/Article/details/gtusjplzhj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shuidangran.top/Article/details/gtrypfjlwm.html

[Q39] 自连接（查上下级）
来源：http://dali.hnxiangtu.top/Article/details/gtxxdmrksy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zycfv.cn/Article/details/gtwzukmhes.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.0kj1m.cn/Article/details/gtjrioaohg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yanxiufei.cn/Article/details/gtmozohlem.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.havefunace.top/Article/details/gtkabwbxtz.html

[Q41] 多表连接
来源：http://dali.aizwys.cn/Article/details/gtdnvjqfmw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.aibaodan.cn/Article/details/gttuogbbah.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sweek.top/Article/details/gtcjokegqa.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ehwqpu.com/Article/details/gtmcjogags.html

[Q42] 连接条件附加过滤
来源：http://dali.hysaishi.cn/Article/details/gtneagzzcj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj202588.top/Article/details/gtzgdghxlm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.andypj.xyz/Article/details/gtypbaqfxg.html

[Q43] 标量子查询
来源：http://dali.jianghu66.top/Article/details/gtzjyjwezk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhiwuduotai.top/Article/details/gtqbxvdtfm.html

[Q44] IN 子查询
来源：http://dali.yj202588.top/Article/details/gtopkotsau.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhixingplan.top/Article/details/gtzktmzsxi.html

[Q45] EXISTS 判断存在
来源：http://dali.redwolf501.top/Article/details/gtxzoxxybb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gtwljsngmg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ybcxt.top/Article/details/gtueandpsw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gtbscwpmrv.html

[Q47] 与平均值比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozfgwbtk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkedpgesn.html

[Q48] CTE 公用表表达式
来源：http://dali.ivvv.top/Article/details/gtrepnnqad.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yanxiufei.cn/Article/details/gtlmghzgtl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.snrcjt.cn/Article/details/gtjsfmexct.html

[Q49] 更新单行
来源：http://dali.vqdsnc.cn/Article/details/gtyubbnkfm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gotoacloud.top/Article/details/gtiutlisxy.html

[Q50] 批量更新
来源：http://dali.zhiwuduotai.top/Article/details/gtdnldspjd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gogol.net.cn/Article/details/gtvyrrebbn.html

[Q51] 用子查询更新
来源：http://dali.quarkkingdee.top/Article/details/gtfalkjicg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtbhhgqkfb.html

[Q52] 删除指定行
来源：http://dali.nanxinkj.top/Article/details/gtqluiptit.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtzuatgeum.html

[Q53] 按条件删除
来源：http://dali.hnxiangtu.top/Article/details/gttjtokyet.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xylfe.cn/Article/details/gtwmrcewrg.html

[Q54] 清空表
来源：http://dali.yvedp.cn/Article/details/gtpqsbphsi.html

TRUNCATE TABLE logs;
来源：http://dali.fengsongda.top/Article/details/gtdjhlzexn.html

[Q55] 排名（并列占位）
来源：http://dali.chenzaomai.com/Article/details/gttxbqvfxe.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zycfv.cn/Article/details/gtcxkiydel.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yongpay.top/Article/details/gtzfebswuw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gtnbbkgcde.html

[Q57] 行号
来源：http://dali.havefunace.top/Article/details/gtudqlzcte.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cashguo.top/Article/details/gtypsuippz.html

[Q58] 累计求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwladewt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtvoirjjdl.html

[Q59] 分组内累计
来源：http://dali.yongpay.top/Article/details/gtifrzngeu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtdkzmismp.html

[Q60] 取上一行 / 下一行
来源：http://dali.aizwys.cn/Article/details/gtydfmkgqc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sufxvd.cn/Article/details/gtxeadevrr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtzyvpatew.html

[Q61] 移动平均
来源：http://dali.quarkkingdee.top/Article/details/gtdpbofzmq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtbosbhdfc.html

[Q62] 分组占比
来源：http://dali.nanxinkj.top/Article/details/gtvwcgdmmo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gteopepgqa.html

[Q63] 开启事务
来源：http://dali.yj20258888.top/Article/details/gtlkmnvwrt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hywenlv.cn/Article/details/gtyzejvxju.html

[Q64] 提交事务
来源：http://dali.jiagoushi.top/Article/details/gtenmimqqj.html

COMMIT;
来源：http://dali.ivvv.top/Article/details/gtokywljsk.html

[Q65] 回滚事务
来源：http://dali.dashuyun.cn/Article/details/gtxtvepndf.html

ROLLBACK;
来源：http://dali.zycfv.cn/Article/details/gttplcrgjp.html

[Q66] 行锁查询
来源：http://dali.quarkkingdee.top/Article/details/gtjayyfpmv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.haohaochexian.top/Article/details/gtqdkokony.html

[Q67] 设置隔离级别
来源：http://dali.kuanghao11.cn/Article/details/gtirgrcxxc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zdqjudy.top/Article/details/gtwxidsfkx.html

[Q68] 保存点
来源：http://dali.jqgufenzy.top/Article/details/gtnqcnicuu.html

SAVEPOINT sp1;
来源：http://dali.yueranfly.top/Article/details/gtjyokcdqw.html

ROLLBACK TO sp1;
来源：http://dali.xinyue.icu/Article/details/gtaqhnnurs.html

[Q69] 查看执行计划
来源：http://dali.tianlin.xyz/Article/details/gtrettxsmf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hfpthk.cn/Article/details/gtqqccolpg.html

[Q70] 更新统计信息
来源：http://dali.jiagoushi.top/Article/details/gthvlhxjra.html

ANALYZE TABLE users;
来源：http://dali.zdqjudy.top/Article/details/gthylbrcwj.html

[Q71] 查看建表语句
来源：http://dali.aibaodan.cn/Article/details/gtvckdcigd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.mhx1999.top/Article/details/gtcztxhelt.html

[Q72] 查看索引
来源：http://dali.yuxming.cn/Article/details/gtreljumto.html

SHOW INDEX FROM users;
来源：http://dali.yj20258.top/Article/details/gtmxyrsppz.html

[Q73] 查看表状态
来源：http://dali.sysykeji.top/Article/details/gtqkbngnwb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cucudq.cn/Article/details/gtmgeeetjy.html

[Q74] 强制使用索引
来源：http://dali.tanke756.top/Article/details/gtvjqcnrnj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuetiantiany.cn/Article/details/gtfdvtixhm.html

[Q75] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gtqnexfeae.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tian-w.cn/Article/details/gthavtpxhk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.birdmap.top/Article/details/gtigauuboo.html

[Q76] 按天统计
来源：http://dali.ppjwa.cn/Article/details/gtubapzwgm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.andypj.xyz/Article/details/gtqsowecsl.html

[Q77] 时间加减
来源：http://dali.dashuyun.cn/Article/details/gtspgcdjfn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zdqjudy.top/Article/details/gtxhxfznbo.html

[Q78] 当前时间
来源：http://dali.yvedp.cn/Article/details/gtygsiycfj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhiwuduotai.top/Article/details/gtlauynrrc.html

[Q79] 字符串拼接
来源：http://dali.dashuyun.cn/Article/details/gtybnwosza.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xylfe.cn/Article/details/gtaoydqwnk.html

[Q80] 字符串截取
来源：http://dali.sufxvd.cn/Article/details/gtlzkaqydg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtgoookbxa.html

[Q81] 字符串替换
来源：http://dali.hysaishi.cn/Article/details/gthjvpwavs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtkkxjtpph.html

[Q82] 字符长度与字节长度
来源：http://dali.cqqwz.cn/Article/details/gtjbcciraj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gtghrhbpkl.html

[Q83] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gtotdotjns.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahepcqsh.html

[Q84] 去除首尾空格
来源：http://dali.zycfv.cn/Article/details/gtasidtxio.html

SELECT TRIM(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtjcgqhrho.html

[Q85] 数值取整
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzuihctb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jlsjyb.cn/Article/details/gtiaibymai.html

[Q86] 读取 JSON 字段
来源：http://dali.quarkkingdee.top/Article/details/gtifzbhgun.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.feifeiyinyue.top/Article/details/gtlmljcgkh.html

[Q87] JSON 字段做条件
来源：http://dali.aizwys.cn/Article/details/gtsrizeopm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.quarkkingdee.top/Article/details/gtkoifhqgg.html

[Q88] 行转列（条件聚合）
来源：http://dali.gzhubu.top/Article/details/gtdxbjpkml.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.iojbl.cn/Article/details/gtkldgjzbq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gttwgzpnid.html

[Q89] 判断表是否存在
来源：http://dali.xylfe.cn/Article/details/gtmbltmakd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinqigfzy.top/Article/details/gtpnuwckwv.html

[Q90] 生成序号列
来源：http://dali.chenjidiqi.icu/Article/details/gtfrqkviee.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hammf.cn/Article/details/gtpdyrnpay.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtybgxpkau.html

R. Bash 专题
来源：http://dali.hysaishi.cn/Article/details/gtgrxnijmm.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtsnlpcqqw.html

[R01] shebang 与严格模式
来源：http://dali.316326.xyz/Article/details/gtwctrmeoi.html

#!/usr/bin/env bash
来源：http://dali.sysykeji.top/Article/details/gtfbalxzck.html

set -euo pipefail
来源：http://dali.hammf.cn/Article/details/gtpecfguno.html

[R02] 变量赋值与使用
来源：http://dali.hfpthk.cn/Article/details/gteftugsmc.html

name="Tom"; echo "$name"
来源：http://dali.pengpengdd.cyou/Article/details/gtxhfqupxr.html

[R03] 只读变量
来源：http://dali.zdqjudy.top/Article/details/gtfkisklbz.html

readonly PI=3.14
来源：http://dali.wangshuangyany.cn/Article/details/gtbuualtti.html

[R04] 位置参数
来源：http://dali.birdmap.top/Article/details/gtdpppgphz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.havefunace.top/Article/details/gtgrmdpczj.html

[R05] 参数默认值
来源：http://dali.iojbl.cn/Article/details/gthabxfheh.html

name="${1:-default}"
来源：http://dali.xuanzx.com/Article/details/gtujyfoarq.html

[R06] 判断命令是否存在
来源：http://dali.sysykeji.top/Article/details/gtqopcvuni.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yangfankeji.com/Article/details/gtbfbrmssg.html

[R07] if 判断文件
来源：http://dali.hammf.cn/Article/details/gtjyifsnnd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sysykeji.top/Article/details/gtomjymiwj.html

[R08] 数值比较
来源：http://dali.xziqi.cn/Article/details/gtjbvgkush.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtuitsabdz.html

[R09] 字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gtzoowlibg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cqqwz.cn/Article/details/gthymortul.html

[R10] 正则匹配
来源：http://dali.dashuyun.cn/Article/details/gtgqxgwxie.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yonumen.top/Article/details/gtxfebwrei.html

[R11] case 多分支
来源：http://dali.wangshuangyany.cn/Article/details/gtccjksjwp.html

case "$1" in
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewhjteua.html

start) echo "启动" ;;
来源：http://dali.fzhhl.top/Article/details/gtpxkdafvt.html

stop)  echo "停止" ;;
来源：http://dali.yuanzhike.top/Article/details/gttwonpiil.html

*)     echo "未知命令" ;;
来源：http://dali.cdnleiting.top/Article/details/gtwjdyrflk.html

esac
来源：http://dali.xylfe.cn/Article/details/gtcfhvxgyy.html

[R12] for 遍历文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywqzvavp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hnxiangtu.top/Article/details/gtxbehmtfj.html

[R13] for 计数循环
来源：http://dali.hnxiangtu.top/Article/details/gtuzhywdmc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.havefunace.top/Article/details/gtrsfugloz.html

[R14] C 风格 for
来源：http://dali.jinqigufen.top/Article/details/gtddqvifgi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gtkpkvkyjy.html

[R15] while 逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gtzxtcnryv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yvedp.cn/Article/details/gtfaridozw.html

[R16] until 等待条件
来源：http://dali.redwolf501.top/Article/details/gtnnxfwmce.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangshuangyany.cn/Article/details/gtuwxltwcn.html

[R17] 数组定义与取值
来源：http://dali.gaohongyu789.top/Article/details/gthagiwyvz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hysaishi.cn/Article/details/gtrfymwsxz.html

[R18] 遍历数组
来源：http://dali.jinqigfzy.top/Article/details/gtxkfxtlpq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sweek.top/Article/details/gtnwwdezon.html

[R19] 数组长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwuymgmk.html

echo "${#arr[@]}"
来源：http://dali.hywenlv.cn/Article/details/gtbejmiqku.html

[R20] 关联数组（字典）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtodryzkqq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzixmpvc.html

[R21] 字符串长度
来源：http://dali.chenlongwang.top/Article/details/gtwaeaqhvl.html

echo "${#s}"
来源：http://dali.zhengqikj.top/Article/details/gtcrwtqwij.html

[R22] 截取子串
来源：http://dali.dashuyun.cn/Article/details/gtzeegltry.html

echo "${s:0:5}"
来源：http://dali.tianlin.xyz/Article/details/gtyrghvhru.html

[R23] 字符串替换
来源：http://dali.chenzaomai.com/Article/details/gtwdcrwfqa.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cqqwz.cn/Article/details/gtpgmnlreu.html

[R24] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gtwwjlzlao.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cucudq.cn/Article/details/gtxehbaxnw.html

[R25] 去后缀 / 去前缀
来源：http://dali.gzhubu.top/Article/details/gtnbuxmoae.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ppjwa.cn/Article/details/gtheifhexb.html

[R26] 命令替换
来源：http://dali.tian-w.cn/Article/details/gtkkikekcq.html

now=$(date +%F); echo "$now"
来源：http://dali.cucudq.cn/Article/details/gtrinnzggw.html

[R27] 算术展开
来源：http://dali.ppjwa.cn/Article/details/gtawmbznkc.html

echo $((1 + 2 * 3))
来源：http://dali.redwolf501.top/Article/details/gthvgjvtww.html

[R28] 浮点运算
来源：http://dali.hnxiangtu.top/Article/details/gtgfjqcmgo.html

echo "scale=2; 10/3" | bc
来源：http://dali.sysykeji.top/Article/details/gtijknlaoe.html

[R29] 定义函数
来源：http://dali.bjfxy.top/Article/details/gtpbqvujjx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.haohaochexian.top/Article/details/gtjrvdfrtw.html

[R30] 函数返回状态码
来源：http://dali.cdnleiting.top/Article/details/gtstrkxnmn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuanzhike.top/Article/details/gtgicjainl.html

[R31] 局部变量
来源：http://dali.cucudq.cn/Article/details/gtdivsxcqr.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gthbokpdiv.html

[R32] 参数个数校验
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppcnhdvg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gtynillrnu.html

[R33] 捕获错误并提示行号
来源：http://dali.hnqzz.top/Article/details/gtmowrztjy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhixingplan.top/Article/details/gtfiuogmgw.html

[R34] 退出时清理
来源：http://dali.tian-w.cn/Article/details/gtfdxowqzd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ybcxt.top/Article/details/gtssrisokq.html

[R35] 后台执行并等待
来源：http://dali.aibaodan.cn/Article/details/gtxmspavyu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nwbrower.top/Article/details/gtuphuqhhj.html

[R36] 并发执行多个任务
来源：http://dali.aibaodan.cn/Article/details/gtrfhbjrhg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.bjfxy.top/Article/details/gtljhfswxs.html

[R37] 把输出赋给变量
来源：http://dali.hfpthk.cn/Article/details/gtazwvuhpy.html

files=$(ls -1)
来源：http://dali.yanxiufei.cn/Article/details/gtmpilvaoy.html

[R38] 管道串联
来源：http://dali.tanke756.top/Article/details/gtvcowigom.html

cat a.txt | grep -i error | wc -l
来源：http://dali.svipenyu.cn/Article/details/gtdhsluykn.html

[R39] 重定向标准输出与错误
来源：http://dali.snrcjt.cn/Article/details/gtdramfgnq.html

cmd > out.log 2>&1
来源：http://dali.smart0.xyz/Article/details/gtdplyfebw.html

[R40] 追加写日志
来源：http://dali.pengpengdd.cyou/Article/details/gtubdvvwso.html

echo "log" >> out.log
来源：http://dali.gotoacloud.top/Article/details/gtnrccnjlb.html

[R41] 丢弃输出
来源：http://dali.fengsongda.top/Article/details/gtinqcqhrz.html

cmd >/dev/null 2>&1
来源：http://dali.quarkkingdee.top/Article/details/gttqdgmhet.html

[R42] 输入重定向
来源：http://dali.birdmap.top/Article/details/gtjdqwlhnx.html

wc -l < a.txt
来源：http://dali.hywenlv.cn/Article/details/gthemzqzco.html

[R43] 按名字查找文件
来源：http://dali.cqqwz.cn/Article/details/gtheheuhto.html

find . -name "*.log" -type f
来源：http://dali.gotoacloud.top/Article/details/gtleynofqw.html

[R44] 按修改时间查找
来源：http://dali.hnxiangtu.top/Article/details/gtivujmrra.html

find . -mtime -7 -type f
来源：http://dali.hnxiangtu.top/Article/details/gtcfbwcxeb.html

[R45] 批量删除
来源：http://dali.hongshengwenyu.top/Article/details/gtuiyqjnim.html

find . -name "*.tmp" -delete
来源：http://dali.yuanzhike.top/Article/details/gtulscycau.html

[R46] 递归替换文件内容
来源：http://dali.cashguo.top/Article/details/gtnknckalm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ehwqpu.com/Article/details/gtyxxnuzsu.html

[R47] sed 单行替换
来源：http://dali.xinyue.icu/Article/details/gthhfazyek.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nanxinkj.top/Article/details/gticczicmt.html

[R48] awk 取指定列
来源：http://dali.andypj.xyz/Article/details/gtxeryqmmw.html

awk '{print $1, $3}' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtzoduamce.html

[R49] awk 带条件
来源：http://dali.wangshuangyany.cn/Article/details/gtcfbqnsbq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhiwuduotai.top/Article/details/gtkkdrocup.html

[R50] awk 求和
来源：http://dali.xinyue.icu/Article/details/gtebfmkuot.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.birdmap.top/Article/details/gtgsmuvraf.html

[R51] 排序去重取前几
来源：http://dali.smart0.xyz/Article/details/gtibxndgzq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daxiang520.top/Article/details/gtyonothen.html

[R52] 统计行数
来源：http://dali.yongpay.top/Article/details/gtamgnmuav.html

wc -l a.txt
来源：http://dali.yj20258888.top/Article/details/gtkhrbbyap.html

[R53] 查看文件头与实时尾
来源：http://dali.mhx1999.top/Article/details/gthedacpda.html


<!-- 参考信息 -->