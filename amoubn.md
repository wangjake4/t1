代发 wailian999

);
来源：http://dali.cucudq.cn/Article/details/gtaynnynrn.html

[Q03] 增加列
来源：http://dali.hysaishi.cn/Article/details/gtbrvwvlal.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwkythqzw.html

[Q04] 修改列类型
来源：http://dali.ybcxt.top/Article/details/gtmakggrxe.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daxiang520.top/Article/details/gtpjspgvrm.html

[Q05] 重命名列
来源：http://dali.yanxiufei.cn/Article/details/gtolvztolm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.aibaodan.cn/Article/details/gtifcixxmh.html

[Q06] 删除列
来源：http://dali.haohaochexian.top/Article/details/gtrupgricy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhengqikj.top/Article/details/gtpwnmofss.html

[Q07] 删除表
来源：http://dali.tanke756.top/Article/details/gtzwuyhshr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhengqikj.top/Article/details/gtanrvbzok.html

[Q08] 创建普通索引
来源：http://dali.gzhubu.top/Article/details/gtwgcgqmbx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.havefunace.top/Article/details/gtngsyeabb.html

[Q09] 创建唯一索引
来源：http://dali.dianchejie.cn/Article/details/gtzqygqfnn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.fengsongda.top/Article/details/gthuhxbjxf.html

[Q10] 插入单行
来源：http://dali.9152youxi.cn/Article/details/gtgvembbfw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.svipenyu.cn/Article/details/gtxvgjinvm.html

[Q11] 一次插入多行
来源：http://dali.hnxiangtu.top/Article/details/gtyaqdhcdx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xylfe.cn/Article/details/gtbpxxstjh.html

[Q12] 插入后取自增 ID
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnhinluv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhengqikj.top/Article/details/gtxlrpiwrp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhoulong.xyz/Article/details/gtdroobkwc.html

[Q13] 忽略重复插入
来源：http://dali.jqgfzy.top/Article/details/gtlyfskhcm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxeycygbm.html

[Q14] 存在则更新（upsert）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuioiqadj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yuxming.cn/Article/details/gtwjklfxmh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.redwolf501.top/Article/details/gtbwhavpeb.html

[Q15] 查询全部
来源：http://dali.meibo888.top/Article/details/gtuaachsme.html

SELECT * FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtnpstpogo.html

[Q16] 查询指定列
来源：http://dali.gotoacloud.top/Article/details/gtsovqaedm.html

SELECT id, name FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtmqqjyxxf.html

[Q17] 条件查询
来源：http://dali.redwolf501.top/Article/details/gtkqksoref.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jqgfzy.top/Article/details/gtejgwbgre.html

[Q18] 模糊匹配
来源：http://dali.cashguo.top/Article/details/gtmxiyzxpo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jqgufenzy.top/Article/details/gtfqftqime.html

[Q19] 范围查询
来源：http://dali.jyoumei.cn/Article/details/gthbzetclw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkcndpwmz.html

[Q20] IN 列表
来源：http://dali.jinqigufen.top/Article/details/gtgxfquvmy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yueranfly.top/Article/details/gtpjdfwels.html

[Q21] 空值判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtipbxzqmd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zycfv.cn/Article/details/gtgkakytpz.html

[Q22] 排序
来源：http://dali.hnxiangtu.top/Article/details/gtxlgobxgy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.smart0.xyz/Article/details/gtjyfgonxv.html

[Q23] 分页
来源：http://dali.vqdsnc.cn/Article/details/gtimnfbncr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.fzhhl.top/Article/details/gtwahrjbdt.html

[Q24] 去重
来源：http://dali.fengsongda.top/Article/details/gtovygfgbg.html

SELECT DISTINCT city FROM users;
来源：http://dali.nwbrower.top/Article/details/gtowfxjewh.html

[Q25] 只取前 N 条
来源：http://dali.vqdsnc.cn/Article/details/gtlwfzpocq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenzaomai.com/Article/details/gtogvlcttr.html

[Q26] 计数
来源：http://dali.guannengcc.top/Article/details/gtcpovvbbc.html

SELECT COUNT(*) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtjtgsivzk.html

[Q27] 条件计数
来源：http://dali.cheryme.top/Article/details/gtqcxzhsxy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gotoacloud.top/Article/details/gthoyfiyxy.html

[Q28] 求和与平均
来源：http://dali.chenlongwang.top/Article/details/gtvzxddfgz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtzjevzapm.html

[Q29] 最大最小值
来源：http://dali.daxiang520.top/Article/details/gtnjfzmlwv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtxdggmjuc.html

[Q30] 分组统计
来源：http://dali.shuidangran.top/Article/details/gtabzkujta.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gtdyxsipxt.html

[Q31] 分组后过滤
来源：http://dali.jlsjyb.cn/Article/details/gtikupssbb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zdqjudy.top/Article/details/gtjjppxywi.html

[Q32] 分组拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtpcworffe.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gtapmggazw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.feifeiyinyue.top/Article/details/gtrvdepmvd.html

[Q33] 多列分组
来源：http://dali.hongshengwenyu.top/Article/details/gtvaiojvfd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.9152youxi.cn/Article/details/gtyxpernsi.html

[Q34] 每组取第一条
来源：http://dali.jiagoushi.top/Article/details/gtaausdsmx.html

SELECT * FROM (
来源：http://dali.yangfankeji.com/Article/details/gtrfsddaow.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.c1oappe.top/Article/details/gtkeqkquud.html

) t WHERE rn = 1;
来源：http://dali.dianchejie.cn/Article/details/gtppddopcg.html

[Q35] 内连接
来源：http://dali.jianghu66.top/Article/details/gtnqxxjgnx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.daria6918.cn/Article/details/gtnqvxdfdz.html

[Q36] 左连接
来源：http://dali.daria6918.cn/Article/details/gthokgdevv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jiagoushi.top/Article/details/gtvyrexqnv.html

[Q37] 右连接
来源：http://dali.hywenlv.cn/Article/details/gtpkxcmfby.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daxiang520.top/Article/details/gtmtadvkst.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.0kj1m.cn/Article/details/gtmkqktrqx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdzblqya.html

[Q39] 自连接（查上下级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsilompju.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sweek.top/Article/details/gtkajiegzr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jlsjyb.cn/Article/details/gtsoshexzf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenjidiqi.icu/Article/details/gtyihnjkyc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhoulong.xyz/Article/details/gtooscmfyw.html

[Q41] 多表连接
来源：http://dali.jlsjyb.cn/Article/details/gtdqjekrpl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.quarkkingdee.top/Article/details/gthpzgzmky.html

JOIN users u ON u.id = o.user_id
来源：http://dali.daxiang520.top/Article/details/gtlkiondfj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yangfankeji.com/Article/details/gthnxkerbq.html

[Q42] 连接条件附加过滤
来源：http://dali.xylfe.cn/Article/details/gtygubkvle.html

SELECT u.name, o.amount FROM users u
来源：http://dali.svipenyu.cn/Article/details/gtgblcwcgu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.0kj1m.cn/Article/details/gthrnhubpz.html

[Q43] 标量子查询
来源：http://dali.gotoacloud.top/Article/details/gtedzhxsdv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yueranfly.top/Article/details/gtduumjfeq.html

[Q44] IN 子查询
来源：http://dali.yj202588.top/Article/details/gtvbtzrsln.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.havefunace.top/Article/details/gtzgsteeiy.html

[Q45] EXISTS 判断存在
来源：http://dali.guannengcc.top/Article/details/gtfcoyfhfn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gtxsmfaerv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hammf.cn/Article/details/gtelkrzvyq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjglaorpl.html

[Q47] 与平均值比较
来源：http://dali.yuxming.cn/Article/details/gtnspaxfvz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.havefunace.top/Article/details/gthmgzvfto.html

[Q48] CTE 公用表表达式
来源：http://dali.havefunace.top/Article/details/gtiewtnxcf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xinyue.icu/Article/details/gthzotiodu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cqqwz.cn/Article/details/gtkidkrdhr.html

[Q49] 更新单行
来源：http://dali.ybcxt.top/Article/details/gtcctzqjta.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gtjtvprgae.html

[Q50] 批量更新
来源：http://dali.zycfv.cn/Article/details/gtipaphwpn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hysaishi.cn/Article/details/gtmdpkkqmf.html

[Q51] 用子查询更新
来源：http://dali.quarkkingdee.top/Article/details/gtxuddloah.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gogol.net.cn/Article/details/gtvszmjsfm.html

[Q52] 删除指定行
来源：http://dali.ybcxt.top/Article/details/gtcegoqflq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.9152youxi.cn/Article/details/gtnmxoqslb.html

[Q53] 按条件删除
来源：http://dali.shzxlz.cn/Article/details/gtsydwvnzj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xylfe.cn/Article/details/gteuiahfst.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gtdnbotxsa.html

TRUNCATE TABLE logs;
来源：http://dali.svipenyu.cn/Article/details/gtxeigvcqw.html

[Q55] 排名（并列占位）
来源：http://dali.tanke756.top/Article/details/gtosuasocr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.snrcjt.cn/Article/details/gtdtqsrgyf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.snrcjt.cn/Article/details/gthokgszxa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gtcxscmybq.html

[Q57] 行号
来源：http://dali.smart0.xyz/Article/details/gtmzvurekl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtgwmpnubs.html

[Q58] 累计求和
来源：http://dali.guannengcc.top/Article/details/gtauvqyxrz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtptqcndhl.html

[Q59] 分组内累计
来源：http://dali.zhiwuduotai.top/Article/details/gtiypmlcsr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtqnwmarap.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigfzy.top/Article/details/gtfkrpklfi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nwbrower.top/Article/details/gtqwqrxocn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtcaghtcds.html

[Q61] 移动平均
来源：http://dali.cashguo.top/Article/details/gtubwduqtn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.havefunace.top/Article/details/gtzyeussfj.html

[Q62] 分组占比
来源：http://dali.shanyushiyangtech.top/Article/details/gtodvskvyb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gthsmytdcr.html

[Q63] 开启事务
来源：http://dali.xinyue.icu/Article/details/gtbtkgijzc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.c1oappe.top/Article/details/gtzisfyivq.html

[Q64] 提交事务
来源：http://dali.yonumen.top/Article/details/gtiwdvriwq.html

COMMIT;
来源：http://dali.hnxiangtu.top/Article/details/gtratlpqzn.html

[Q65] 回滚事务
来源：http://dali.chenzaomai.com/Article/details/gtmwjizmgh.html

ROLLBACK;
来源：http://dali.xziqi.cn/Article/details/gttpyrfuzo.html

[Q66] 行锁查询
来源：http://dali.meibo888.top/Article/details/gtjfqgqpqq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj202588.top/Article/details/gtocbduffb.html

[Q67] 设置隔离级别
来源：http://dali.pycfn.com/Article/details/gthsyntteg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zdqjudy.top/Article/details/gtfxlxurkh.html

[Q68] 保存点
来源：http://dali.ydzc1.top/Article/details/gtuzjckffs.html

SAVEPOINT sp1;
来源：http://dali.xylfe.cn/Article/details/gtftyswjdl.html

ROLLBACK TO sp1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavabyhex.html

[Q69] 查看执行计划
来源：http://dali.jinqigufen.top/Article/details/gtrtmzjisb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hywenlv.cn/Article/details/gtqpixhhck.html

[Q70] 更新统计信息
来源：http://dali.gogol.net.cn/Article/details/gtjfbtxaez.html

ANALYZE TABLE users;
来源：http://dali.guowangkeji.top/Article/details/gttjcrpfby.html

[Q71] 查看建表语句
来源：http://dali.nwbrower.top/Article/details/gtnyckkdqs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tanke756.top/Article/details/gtenkarfkk.html

[Q72] 查看索引
来源：http://dali.316326.xyz/Article/details/gtxuczjgno.html

SHOW INDEX FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtdbiisdbm.html

[Q73] 查看表状态
来源：http://dali.zycfv.cn/Article/details/gtdbuaommv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenjidiqi.icu/Article/details/gtqkyxdtmj.html

[Q74] 强制使用索引
来源：http://dali.hongshengwenyu.top/Article/details/gtylskbyxd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhoulong.xyz/Article/details/gtihgcfckl.html

[Q75] 日期格式化
来源：http://dali.yj20258.top/Article/details/gtmuzjydwn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtepuosfmj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dashuyun.cn/Article/details/gtmxphdgwb.html

[Q76] 按天统计
来源：http://dali.smart0.xyz/Article/details/gtopntxkzo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ybcxt.top/Article/details/gtnwxkdwix.html

[Q77] 时间加减
来源：http://dali.jqgufenzy.top/Article/details/gthhbdajkd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.wangdashe.top/Article/details/gtvrismsnx.html

[Q78] 当前时间
来源：http://dali.jyoumei.cn/Article/details/gtovadbppl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yonumen.top/Article/details/gtjrmsnqlj.html

[Q79] 字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gthbhordrz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cqqwz.cn/Article/details/gtlneclvmh.html

[Q80] 字符串截取
来源：http://dali.shzxlz.cn/Article/details/gtaargxwvj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtsxauqows.html

[Q81] 字符串替换
来源：http://dali.fengsongda.top/Article/details/gtqxfhfjwt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nwbrower.top/Article/details/gtynegmqnz.html

[Q82] 字符长度与字节长度
来源：http://dali.hfpthk.cn/Article/details/gtqjtkdvgi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtfboiskvi.html

[Q83] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gtqcfpfkmk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtpndvopmt.html

[Q84] 去除首尾空格
来源：http://dali.shangyingyoupin.top/Article/details/gtplwgwqfo.html

SELECT TRIM(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtnxabgeyj.html

[Q85] 数值取整
来源：http://dali.c1oappe.top/Article/details/gtdgdzhthp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.redwolf501.top/Article/details/gtqwdyivqm.html

[Q86] 读取 JSON 字段
来源：http://dali.shangyingyoupin.top/Article/details/gtkrhyzpbo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.guannengcc.top/Article/details/gtehdfeekf.html

[Q87] JSON 字段做条件
来源：http://dali.guowangkeji.top/Article/details/gtkpdkoank.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yuanzhike.top/Article/details/gtgnkrjprl.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgufenzy.top/Article/details/gtapivvavb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gzhubu.top/Article/details/gtyceozxsg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yueranfly.top/Article/details/gtllfcthqx.html

[Q89] 判断表是否存在
来源：http://dali.yj20258888.top/Article/details/gtxuslzcph.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daria6918.cn/Article/details/gtdymiksfs.html

[Q90] 生成序号列
来源：http://dali.zhengqikj.top/Article/details/gtqpnsaund.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.andypj.xyz/Article/details/gtbnumjygg.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtpiypzwfb.html

R. Bash 专题
来源：http://dali.ivvv.top/Article/details/gtudlqgvcq.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtqvrbpjkd.html

[R01] shebang 与严格模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwiuyucno.html

#!/usr/bin/env bash
来源：http://dali.jiagoushi.top/Article/details/gtgycydnkt.html

set -euo pipefail
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxegsxuu.html

[R02] 变量赋值与使用
来源：http://dali.jqgfzy.top/Article/details/gtoijzwrnl.html

name="Tom"; echo "$name"
来源：http://dali.sufxvd.cn/Article/details/gtlbbmqkmf.html

[R03] 只读变量
来源：http://dali.316326.xyz/Article/details/gtlmfncusa.html

readonly PI=3.14
来源：http://dali.hammf.cn/Article/details/gtiirpiica.html

[R04] 位置参数
来源：http://dali.wangdashe.top/Article/details/gtyrogpnji.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hongshengwenyu.top/Article/details/gthvznhxhc.html

[R05] 参数默认值
来源：http://dali.yonumen.top/Article/details/gtvjncqzba.html

name="${1:-default}"
来源：http://dali.tianlin.xyz/Article/details/gteynttepv.html

[R06] 判断命令是否存在
来源：http://dali.wangshuangyany.cn/Article/details/gtsiqtllrv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuxming.cn/Article/details/gtwfpuclrb.html

[R07] if 判断文件
来源：http://dali.hywenlv.cn/Article/details/gtxycrikph.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tian-w.cn/Article/details/gtvcqolzsc.html

[R08] 数值比较
来源：http://dali.tian-w.cn/Article/details/gtjdoummck.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sysykeji.top/Article/details/gtyxigmdem.html

[R09] 字符串比较
来源：http://dali.bjfxy.top/Article/details/gthatfztgx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gttyurzleu.html

[R10] 正则匹配
来源：http://dali.cashguo.top/Article/details/gtnsjfqchu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yonumen.top/Article/details/gtljtnxddl.html

[R11] case 多分支
来源：http://dali.ivvv.top/Article/details/gtiorwwtqq.html

case "$1" in
来源：http://dali.jinqigufen.top/Article/details/gtblvdqyhl.html

start) echo "启动" ;;
来源：http://dali.jianghu66.top/Article/details/gtwfxymdsp.html

stop)  echo "停止" ;;
来源：http://dali.cashguo.top/Article/details/gtzbyrxadh.html

*)     echo "未知命令" ;;
来源：http://dali.yonumen.top/Article/details/gtsqpfsfga.html

esac
来源：http://dali.chenlongwang.top/Article/details/gtejkszuvb.html

[R12] for 遍历文件
来源：http://dali.c1oappe.top/Article/details/gtgnvwlaup.html

for f in *.txt; do echo "$f"; done
来源：http://dali.9152youxi.cn/Article/details/gtepxiskoy.html

[R13] for 计数循环
来源：http://dali.yanxiufei.cn/Article/details/gtkhzntmlr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gtauiptmkp.html

[R14] C 风格 for
来源：http://dali.iojbl.cn/Article/details/gtcqcxnrpx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gthllorjve.html

[R15] while 逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtyhdoldth.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzdmtmup.html

[R16] until 等待条件
来源：http://dali.vqdsnc.cn/Article/details/gtujfmaxao.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gtsinezcju.html

[R17] 数组定义与取值
来源：http://dali.wangdashe.top/Article/details/gtqezdsehg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hammf.cn/Article/details/gtvbssqgev.html

[R18] 遍历数组
来源：http://dali.jinqigufen.top/Article/details/gtetqdkhjz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guowangkeji.top/Article/details/gtwovyqnhf.html

[R19] 数组长度
来源：http://dali.jinqigufen.top/Article/details/gtvhuqqscs.html

echo "${#arr[@]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgopejmom.html

[R20] 关联数组（字典）
来源：http://dali.zhixingplan.top/Article/details/gtyyfvaill.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yueranfly.top/Article/details/gtulkkkmnz.html

[R21] 字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gtwaqfhmvo.html

echo "${#s}"
来源：http://dali.quarkkingdee.top/Article/details/gtcyggtmjl.html

[R22] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gtjsvvhevu.html

echo "${s:0:5}"
来源：http://dali.zdqjudy.top/Article/details/gtnltttorl.html

[R23] 字符串替换
来源：http://dali.shuidangran.top/Article/details/gtglsouoyg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhengqikj.top/Article/details/gttwppvgub.html

[R24] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gtoontwiua.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtmljefhpj.html

[R25] 去后缀 / 去前缀
来源：http://dali.ydzc1.top/Article/details/gtghfmakmt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.fengsongda.top/Article/details/gtjnehizny.html

[R26] 命令替换
来源：http://dali.tianlin.xyz/Article/details/gtthmydkip.html

now=$(date +%F); echo "$now"
来源：http://dali.sxryk.cn/Article/details/gtziayzbyb.html

[R27] 算术展开
来源：http://dali.jianghu66.top/Article/details/gtkiqhrnae.html

echo $((1 + 2 * 3))
来源：http://dali.havefunace.top/Article/details/gtatjprobs.html

[R28] 浮点运算
来源：http://dali.daria6918.cn/Article/details/gtggjqaszc.html

echo "scale=2; 10/3" | bc
来源：http://dali.jlsjyb.cn/Article/details/gtmiixyxth.html

[R29] 定义函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonvxytto.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigfzy.top/Article/details/gtmbbcglhg.html

[R30] 函数返回状态码
来源：http://dali.yangfankeji.com/Article/details/gtxfztuhdk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ydzc1.top/Article/details/gttieivfda.html

[R31] 局部变量
来源：http://dali.xziqi.cn/Article/details/gtgpvfthzy.html

f() { local x=1; echo "$x"; }
来源：http://dali.gzhubu.top/Article/details/gtjzazmtlt.html

[R32] 参数个数校验
来源：http://dali.hysaishi.cn/Article/details/gtnfnlfeop.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinqigufen.top/Article/details/gtcmxfrcbb.html

[R33] 捕获错误并提示行号
来源：http://dali.c1oappe.top/Article/details/gtozasbtok.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hywenlv.cn/Article/details/gtcprhtrzs.html

[R34] 退出时清理
来源：http://dali.tian-w.cn/Article/details/gtmfpkaicm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gtqbxwfrgj.html

[R35] 后台执行并等待
来源：http://dali.hnxiangtu.top/Article/details/gteetjvaue.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmurmwes.html

[R36] 并发执行多个任务
来源：http://dali.shangyingyoupin.top/Article/details/gtncsxmbth.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shuidangran.top/Article/details/gtzkevxjgw.html

[R37] 把输出赋给变量
来源：http://dali.yuanzhike.top/Article/details/gtgadbuyiy.html

files=$(ls -1)
来源：http://dali.pengpengdd.cyou/Article/details/gtsduymyip.html

[R38] 管道串联
来源：http://dali.wangshuangyany.cn/Article/details/gtgsucdale.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ybcxt.top/Article/details/gtdzzxdgci.html

[R39] 重定向标准输出与错误
来源：http://dali.aizwys.cn/Article/details/gthuorfexl.html

cmd > out.log 2>&1
来源：http://dali.snrcjt.cn/Article/details/gtogqftbkk.html

[R40] 追加写日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfunavas.html

echo "log" >> out.log
来源：http://dali.yj202588.top/Article/details/gtsutnpxgd.html

[R41] 丢弃输出
来源：http://dali.shangyingyoupin.top/Article/details/gtlpphfwdi.html

cmd >/dev/null 2>&1
来源：http://dali.meibo888.top/Article/details/gtgvvyquue.html

[R42] 输入重定向
来源：http://dali.wangshuangyany.cn/Article/details/gttmzjnhck.html

wc -l < a.txt
来源：http://dali.c1oappe.top/Article/details/gtjcdsohkb.html

[R43] 按名字查找文件
来源：http://dali.xylfe.cn/Article/details/gtrvfizpka.html

find . -name "*.log" -type f
来源：http://dali.shuidangran.top/Article/details/gtnqmltfdf.html

[R44] 按修改时间查找
来源：http://dali.nanxinkj.top/Article/details/gtayzklpbg.html

find . -mtime -7 -type f
来源：http://dali.pengpengdd.cyou/Article/details/gtdjsdtods.html

[R45] 批量删除
来源：http://dali.xylfe.cn/Article/details/gtplkbfzfy.html

find . -name "*.tmp" -delete
来源：http://dali.iojbl.cn/Article/details/gtilnkygjt.html

[R46] 递归替换文件内容
来源：http://dali.svipenyu.cn/Article/details/gtbhpsfhic.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.redwolf501.top/Article/details/gtosrquoui.html

[R47] sed 单行替换
来源：http://dali.sweek.top/Article/details/gtqjvxqyih.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258.top/Article/details/gtkvqbvkhx.html

[R48] awk 取指定列
来源：http://dali.yonumen.top/Article/details/gtfwecyaju.html

awk '{print $1, $3}' a.txt
来源：http://dali.birdmap.top/Article/details/gtpvhtcwjn.html

[R49] awk 带条件
来源：http://dali.daria6918.cn/Article/details/gtqkxyhybo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.meibo888.top/Article/details/gtsesjcaot.html

[R50] awk 求和
来源：http://dali.gotoacloud.top/Article/details/gtfvpzuyxb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtfcurgqxv.html

[R51] 排序去重取前几
来源：http://dali.meibo888.top/Article/details/gtgetwqxad.html


<!-- 参考信息 -->