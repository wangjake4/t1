代发 wailian999

);
来源：http://dali.aizwys.cn/Article/details/gtrngndkrm.html

[Q03] 增加列
来源：http://dali.guannengcc.top/Article/details/gtscwvldrc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.wangdashe.top/Article/details/gtvecfzprz.html

[Q04] 修改列类型
来源：http://dali.aibaodan.cn/Article/details/gtfdmoooky.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gotoacloud.top/Article/details/gtoolexapm.html

[Q05] 重命名列
来源：http://dali.xuanzx.com/Article/details/gthsokwlgw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jyoumei.cn/Article/details/gtyjkjmxis.html

[Q06] 删除列
来源：http://dali.jinqigufen.top/Article/details/gtmcflheeu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sufxvd.cn/Article/details/gtrhwalchg.html

[Q07] 删除表
来源：http://dali.nanxuanxn.top/Article/details/gtwulqhdui.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtqarjhupu.html

[Q08] 创建普通索引
来源：http://dali.zhoulong.xyz/Article/details/gtiblicgro.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sufxvd.cn/Article/details/gttehqleof.html

[Q09] 创建唯一索引
来源：http://dali.xuanzx.com/Article/details/gtdltuqeky.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmaigrhnt.html

[Q10] 插入单行
来源：http://dali.daria6918.cn/Article/details/gttzwhrpjy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nwbrower.top/Article/details/gtcymrltkd.html

[Q11] 一次插入多行
来源：http://dali.yj202588.top/Article/details/gttfbiloca.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtndbhhchd.html

[Q12] 插入后取自增 ID
来源：http://dali.jinqigfzy.top/Article/details/gtkgwxvypy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgvlawja.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gtzzncrdqo.html

[Q13] 忽略重复插入
来源：http://dali.chenlongwang.top/Article/details/gtymtljteq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nanxinkj.top/Article/details/gtdlcdoqxz.html

[Q14] 存在则更新（upsert）
来源：http://dali.0kj1m.cn/Article/details/gtunpmsjbn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.daria6918.cn/Article/details/gtexbcjovk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sweek.top/Article/details/gtabvqoziv.html

[Q15] 查询全部
来源：http://dali.chenjidiqi.icu/Article/details/gtuosakmex.html

SELECT * FROM users;
来源：http://dali.nwbrower.top/Article/details/gtcqabeyxo.html

[Q16] 查询指定列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgffwijvy.html

SELECT id, name FROM users;
来源：http://dali.wangdashe.top/Article/details/gtlugkkjwk.html

[Q17] 条件查询
来源：http://dali.yj20258.top/Article/details/gtutyuetme.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtibrdffvb.html

[Q18] 模糊匹配
来源：http://dali.gaohongyu789.top/Article/details/gtsiklkdet.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjucuupy.html

[Q19] 范围查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturnclnxn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jyoumei.cn/Article/details/gtelvgrmuf.html

[Q20] IN 列表
来源：http://dali.pycfn.com/Article/details/gtplwgihqz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sweek.top/Article/details/gtmjinrubw.html

[Q21] 空值判断
来源：http://dali.0kj1m.cn/Article/details/gtsdtvdyij.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shuidangran.top/Article/details/gtbkkolysa.html

[Q22] 排序
来源：http://dali.andypj.xyz/Article/details/gtrlexwknl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj20258888.top/Article/details/gtgcskrsah.html

[Q23] 分页
来源：http://dali.yj20258.top/Article/details/gtkwzeywfp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hywenlv.cn/Article/details/gtxylputiq.html

[Q24] 去重
来源：http://dali.tianlin.xyz/Article/details/gteanjytuz.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtwqoweein.html

[Q25] 只取前 N 条
来源：http://dali.yvedp.cn/Article/details/gteewyzcms.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gtodmttlcg.html

[Q26] 计数
来源：http://dali.yangfankeji.com/Article/details/gtvtoiekgh.html

SELECT COUNT(*) FROM users;
来源：http://dali.cashguo.top/Article/details/gtayvkdnni.html

[Q27] 条件计数
来源：http://dali.chenzaomai.com/Article/details/gtsutyhysv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtdlrcdlqg.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gtfdlnxawm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gteuprohdm.html

[Q29] 最大最小值
来源：http://dali.snrcjt.cn/Article/details/gtznuzdagm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtwrvmzkgm.html

[Q30] 分组统计
来源：http://dali.pycfn.com/Article/details/gtyyjjzmgb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gtbaeeylul.html

[Q31] 分组后过滤
来源：http://dali.yvedp.cn/Article/details/gthxwnjjme.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ppjwa.cn/Article/details/gtqnvepwrz.html

[Q32] 分组拼接字符串
来源：http://dali.yonumen.top/Article/details/gttfpbxino.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gtontzdvdv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangdashe.top/Article/details/gtjqmdjgpp.html

[Q33] 多列分组
来源：http://dali.yuanzhike.top/Article/details/gtklgicvpq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xuanzx.com/Article/details/gtmaoavlco.html

[Q34] 每组取第一条
来源：http://dali.sxryk.cn/Article/details/gtubsuqpvu.html

SELECT * FROM (
来源：http://dali.hammf.cn/Article/details/gtecieyley.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pycfn.com/Article/details/gthbfmlfww.html

) t WHERE rn = 1;
来源：http://dali.ehwqpu.com/Article/details/gttthpsknl.html

[Q35] 内连接
来源：http://dali.aibaodan.cn/Article/details/gteiyowcpx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspyjuocl.html

[Q36] 左连接
来源：http://dali.hysaishi.cn/Article/details/gtkahoqdku.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.pengpengdd.cyou/Article/details/gtjdzmoemb.html

[Q37] 右连接
来源：http://dali.cheryme.top/Article/details/gtvwaqpbuu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yueranfly.top/Article/details/gtjhpnapmf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nwbrower.top/Article/details/gtvtvxjyyl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.haohaochexian.top/Article/details/gtcgybmhza.html

[Q39] 自连接（查上下级）
来源：http://dali.ybcxt.top/Article/details/gtiagythkk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yueranfly.top/Article/details/gtkppckfzj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.mhx1999.top/Article/details/gtlvtswnvb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.smart0.xyz/Article/details/gtrblqvzgu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.bjfxy.top/Article/details/gtkwtknjxn.html

[Q41] 多表连接
来源：http://dali.gaohongyu789.top/Article/details/gtpphhggbv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shangyingyoupin.top/Article/details/gtkrucsbfb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sweek.top/Article/details/gtifucvfix.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.vqdsnc.cn/Article/details/gthrsesddq.html

[Q42] 连接条件附加过滤
来源：http://dali.316326.xyz/Article/details/gtkbdkjsjg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnqzz.top/Article/details/gthyvqzwyb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjgkrclga.html

[Q43] 标量子查询
来源：http://dali.pengpengdd.cyou/Article/details/gthmhvcpua.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yueranfly.top/Article/details/gtxzypqmoa.html

[Q44] IN 子查询
来源：http://dali.shuidangran.top/Article/details/gthhcfrpdo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj202588.top/Article/details/gtslvtirnr.html

[Q45] EXISTS 判断存在
来源：http://dali.xinyue.icu/Article/details/gtthapgjxm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hfpthk.cn/Article/details/gtebbbztcs.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangdashe.top/Article/details/gtjoqdxhct.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.birdmap.top/Article/details/gtlmnrzgwd.html

[Q47] 与平均值比较
来源：http://dali.jyoumei.cn/Article/details/gtspzrcmkf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258888.top/Article/details/gtasaiuwyz.html

[Q48] CTE 公用表表达式
来源：http://dali.zhengqikj.top/Article/details/gtqyghonus.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhengqikj.top/Article/details/gtzdnobmxe.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhoulong.xyz/Article/details/gtjnvmdimi.html

[Q49] 更新单行
来源：http://dali.jiagoushi.top/Article/details/gtrlrusewa.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hammf.cn/Article/details/gtarllmutb.html

[Q50] 批量更新
来源：http://dali.cdnleiting.top/Article/details/gtxrfnzcmj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nanxinkj.top/Article/details/gtyirvvlxa.html

[Q51] 用子查询更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjtfaeer.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yuanzhike.top/Article/details/gtujxnjofh.html

[Q52] 删除指定行
来源：http://dali.haohaochexian.top/Article/details/gtzblqafjp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtxztiqtkt.html

[Q53] 按条件删除
来源：http://dali.9152youxi.cn/Article/details/gtlaldlpdy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gtdfvlhman.html

[Q54] 清空表
来源：http://dali.shzxlz.cn/Article/details/gtvtnovoxj.html

TRUNCATE TABLE logs;
来源：http://dali.zhoulong.xyz/Article/details/gtvcgmffjt.html

[Q55] 排名（并列占位）
来源：http://dali.316326.xyz/Article/details/gtuwjmtmjt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqokeyho.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj20258888.top/Article/details/gtewqqsvnj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ydzc1.top/Article/details/gtsrqcmyed.html

[Q57] 行号
来源：http://dali.chenjidiqi.icu/Article/details/gthcrintpl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.wangdashe.top/Article/details/gtsovklrpg.html

[Q58] 累计求和
来源：http://dali.daria6918.cn/Article/details/gtdzyrbihr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtxphemkqr.html

[Q59] 分组内累计
来源：http://dali.xinyue.icu/Article/details/gtouhvxpvi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtnjfsngdm.html

[Q60] 取上一行 / 下一行
来源：http://dali.tanke756.top/Article/details/gtmdobuuka.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sysykeji.top/Article/details/gtsedwlkkn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hammf.cn/Article/details/gtrixuoywj.html

[Q61] 移动平均
来源：http://dali.sufxvd.cn/Article/details/gtlgpvbgky.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtmrpiwldk.html

[Q62] 分组占比
来源：http://dali.wangdashe.top/Article/details/gtmafaheri.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gtgysxpfxk.html

[Q63] 开启事务
来源：http://dali.sysykeji.top/Article/details/gtrihuovse.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrmkrrbu.html

[Q64] 提交事务
来源：http://dali.ybcxt.top/Article/details/gtddsamqcg.html

COMMIT;
来源：http://dali.yuxming.cn/Article/details/gtlnszechj.html

[Q65] 回滚事务
来源：http://dali.zdqjudy.top/Article/details/gtvxigrbld.html

ROLLBACK;
来源：http://dali.guannengcc.top/Article/details/gtmtfucxlt.html

[Q66] 行锁查询
来源：http://dali.svipenyu.cn/Article/details/gtefnnggit.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlasysprl.html

[Q67] 设置隔离级别
来源：http://dali.zhiwuduotai.top/Article/details/gtauecpqfa.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.fengsongda.top/Article/details/gttdqqfeiw.html

[Q68] 保存点
来源：http://dali.yongpay.top/Article/details/gtrjeagyae.html

SAVEPOINT sp1;
来源：http://dali.hnxiangtu.top/Article/details/gtvlcccrye.html

ROLLBACK TO sp1;
来源：http://dali.feifeiyinyue.top/Article/details/gtydfprtbd.html

[Q69] 查看执行计划
来源：http://dali.yvedp.cn/Article/details/gtoauphlac.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hnqzz.top/Article/details/gtlkwoxqoi.html

[Q70] 更新统计信息
来源：http://dali.sxryk.cn/Article/details/gtordtsfno.html

ANALYZE TABLE users;
来源：http://dali.aizwys.cn/Article/details/gtzjzvetwp.html

[Q71] 查看建表语句
来源：http://dali.fzhhl.top/Article/details/gtcawpzqss.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.smart0.xyz/Article/details/gtvfxvowki.html

[Q72] 查看索引
来源：http://dali.kuanghao11.cn/Article/details/gtiraqgmtm.html

SHOW INDEX FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtjbiwrnnl.html

[Q73] 查看表状态
来源：http://dali.jianghu66.top/Article/details/gtrlxynrkv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gthxdltcty.html

[Q74] 强制使用索引
来源：http://dali.jianghu66.top/Article/details/gtyuekrxbs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gogol.net.cn/Article/details/gtphyuztoc.html

[Q75] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gtlkexarln.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtjjgaudor.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jyoumei.cn/Article/details/gtiunhabks.html

[Q76] 按天统计
来源：http://dali.feifeiyinyue.top/Article/details/gtllotaemu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.vqdsnc.cn/Article/details/gtnbalxnme.html

[Q77] 时间加减
来源：http://dali.fengsongda.top/Article/details/gtjidavwbc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sweek.top/Article/details/gtciwxtyhz.html

[Q78] 当前时间
来源：http://dali.cucudq.cn/Article/details/gtkloknkrr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenjidiqi.icu/Article/details/gteqrvvrva.html

[Q79] 字符串拼接
来源：http://dali.daxiang520.top/Article/details/gtoustvzdm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xinyue.icu/Article/details/gtiifwzdit.html

[Q80] 字符串截取
来源：http://dali.jinyuanbaomall.cn/Article/details/gtguuepxqd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtlhfkvhpv.html

[Q81] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gttzzntazf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gthlrmzrvy.html

[Q82] 字符长度与字节长度
来源：http://dali.hongshengwenyu.top/Article/details/gtfhvjxflc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtrlmkvnvs.html

[Q83] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gtqfijdgti.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtknasjcuo.html

[Q84] 去除首尾空格
来源：http://dali.birdmap.top/Article/details/gtzubtorle.html

SELECT TRIM(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtpagkpoqo.html

[Q85] 数值取整
来源：http://dali.vqdsnc.cn/Article/details/gtlzmxxnww.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daria6918.cn/Article/details/gttsipgejc.html

[Q86] 读取 JSON 字段
来源：http://dali.yvedp.cn/Article/details/gtupzlpifo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigfzy.top/Article/details/gtkghiafga.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigfzy.top/Article/details/gtzpoiwlju.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxswqvsaq.html

[Q88] 行转列（条件聚合）
来源：http://dali.guannengcc.top/Article/details/gtqbliafne.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yongpay.top/Article/details/gtcohonhnh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtavtjhmge.html

[Q89] 判断表是否存在
来源：http://dali.zhengqikj.top/Article/details/gthruyfdmf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daria6918.cn/Article/details/gtqgzrekmw.html

[Q90] 生成序号列
来源：http://dali.sweek.top/Article/details/gtwbwtxiqv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jyoumei.cn/Article/details/gtwidkxprb.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtomzzfrkt.html

R. Bash 专题
来源：http://dali.yj202588.top/Article/details/gtytacwshx.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtjyogadvb.html

[R01] shebang 与严格模式
来源：http://dali.wangdashe.top/Article/details/gteqemmolp.html

#!/usr/bin/env bash
来源：http://dali.quarkkingdee.top/Article/details/gtjgkxrgud.html

set -euo pipefail
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfmsoith.html

[R02] 变量赋值与使用
来源：http://dali.chenzaomai.com/Article/details/gtavuxwsff.html

name="Tom"; echo "$name"
来源：http://dali.andypj.xyz/Article/details/gthwvbdebm.html

[R03] 只读变量
来源：http://dali.xuanzx.com/Article/details/gthdjzoxex.html

readonly PI=3.14
来源：http://dali.smart0.xyz/Article/details/gtmgikwmtn.html

[R04] 位置参数
来源：http://dali.yonumen.top/Article/details/gtjfluaidp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigfzy.top/Article/details/gtdjybanaz.html

[R05] 参数默认值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwhmjvzzv.html

name="${1:-default}"
来源：http://dali.yj20258888.top/Article/details/gtiacadjyt.html

[R06] 判断命令是否存在
来源：http://dali.ivvv.top/Article/details/gtkqrbnemw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvswvemiv.html

[R07] if 判断文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxolxwkw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yueranfly.top/Article/details/gtghhddozu.html

[R08] 数值比较
来源：http://dali.cdnleiting.top/Article/details/gtjwzoiovv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhixingplan.top/Article/details/gtvkjkssmc.html

[R09] 字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtismgpe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.iojbl.cn/Article/details/gtejccytsk.html

[R10] 正则匹配
来源：http://dali.yuanzhike.top/Article/details/gtfnyskwsr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.svipenyu.cn/Article/details/gtinormipy.html

[R11] case 多分支
来源：http://dali.cheryme.top/Article/details/gtpkvopaeb.html

case "$1" in
来源：http://dali.ydzc1.top/Article/details/gtvvsqxyyz.html

start) echo "启动" ;;
来源：http://dali.jyoumei.cn/Article/details/gtgjikmgrx.html

stop)  echo "停止" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtprpqapdc.html

*)     echo "未知命令" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gthtshlyqx.html

esac
来源：http://dali.yj202588.top/Article/details/gtusfiyaci.html

[R12] for 遍历文件
来源：http://dali.jqgufenzy.top/Article/details/gtkdlmorjw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gogol.net.cn/Article/details/gtsrqovlta.html

[R13] for 计数循环
来源：http://dali.cashguo.top/Article/details/gtziqrcxxv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gteurrodic.html

[R14] C 风格 for
来源：http://dali.wangshuangyany.cn/Article/details/gtrtajmznq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gtgtuzbeus.html

[R15] while 逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtitzjmcgx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jlsjyb.cn/Article/details/gtxnwyzywb.html

[R16] until 等待条件
来源：http://dali.xuanzx.com/Article/details/gtmsdycyrs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gtftezryyw.html

[R17] 数组定义与取值
来源：http://dali.haohaochexian.top/Article/details/gtmfnqharx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuetiantiany.cn/Article/details/gtqdrlirpe.html

[R18] 遍历数组
来源：http://dali.zhengqikj.top/Article/details/gtplleyxmc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cashguo.top/Article/details/gtoftbpimn.html

[R19] 数组长度
来源：http://dali.yj20258.top/Article/details/gtfubqkski.html

echo "${#arr[@]}"
来源：http://dali.jyoumei.cn/Article/details/gtyzjvjthk.html

[R20] 关联数组（字典）
来源：http://dali.jyoumei.cn/Article/details/gtdgdcceub.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shuidangran.top/Article/details/gtbgzlrlxg.html

[R21] 字符串长度
来源：http://dali.pycfn.com/Article/details/gtrhdsiivg.html

echo "${#s}"
来源：http://dali.daxiang520.top/Article/details/gtatynrxaa.html

[R22] 截取子串
来源：http://dali.tanke756.top/Article/details/gtbccghkrx.html

echo "${s:0:5}"
来源：http://dali.yvedp.cn/Article/details/gtvzjjvfjm.html

[R23] 字符串替换
来源：http://dali.yonumen.top/Article/details/gtxpebpsqx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj20258888.top/Article/details/gtoiscjaqy.html

[R24] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gtlciplaml.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.wangshuangyany.cn/Article/details/gtauqjfctw.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj202588.top/Article/details/gtudnogioy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenlongwang.top/Article/details/gteamsghsl.html

[R26] 命令替换
来源：http://dali.fzhhl.top/Article/details/gtwjcoaztx.html

now=$(date +%F); echo "$now"
来源：http://dali.bjfxy.top/Article/details/gtkrdhfefa.html

[R27] 算术展开
来源：http://dali.0kj1m.cn/Article/details/gtflsbrzff.html

echo $((1 + 2 * 3))
来源：http://dali.daxiang520.top/Article/details/gtzztywkvu.html

[R28] 浮点运算
来源：http://dali.guowangkeji.top/Article/details/gtqmicgqgb.html

echo "scale=2; 10/3" | bc
来源：http://dali.jqgufenzy.top/Article/details/gtdfxzyrkz.html

[R29] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gtjyxfngvd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jlsjyb.cn/Article/details/gtmarwrkjh.html

[R30] 函数返回状态码
来源：http://dali.snrcjt.cn/Article/details/gtmvlwytwr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ivvv.top/Article/details/gtivaiovpb.html

[R31] 局部变量
来源：http://dali.daxiang520.top/Article/details/gtyrowovrr.html

f() { local x=1; echo "$x"; }
来源：http://dali.gzhubu.top/Article/details/gtktbbcdyt.html

[R32] 参数个数校验
来源：http://dali.sweek.top/Article/details/gtoglooqpj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.316326.xyz/Article/details/gtwcdxzdse.html

[R33] 捕获错误并提示行号
来源：http://dali.cqqwz.cn/Article/details/gtizdsqmen.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhoulong.xyz/Article/details/gtjhazcgfq.html

[R34] 退出时清理
来源：http://dali.yonumen.top/Article/details/gtswivhmsd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangdashe.top/Article/details/gtwaydogop.html

[R35] 后台执行并等待
来源：http://dali.cdnleiting.top/Article/details/gtkolndogs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hammf.cn/Article/details/gtiyxnybhq.html

[R36] 并发执行多个任务
来源：http://dali.zhiwuduotai.top/Article/details/gtwswkbomi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aizwys.cn/Article/details/gtuwlmmvfc.html

[R37] 把输出赋给变量
来源：http://dali.jqgfzy.top/Article/details/gtfnkvvlpq.html

files=$(ls -1)
来源：http://dali.snrcjt.cn/Article/details/gttaeafjwx.html

[R38] 管道串联
来源：http://dali.dashuyun.cn/Article/details/gtnoffsvkn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xinyue.icu/Article/details/gtghgipcci.html

[R39] 重定向标准输出与错误
来源：http://dali.chenjidiqi.icu/Article/details/gtheutopyj.html

cmd > out.log 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gtczpbimsw.html

[R40] 追加写日志
来源：http://dali.xinyue.icu/Article/details/gtpgpfocgt.html

echo "log" >> out.log
来源：http://dali.daxiang520.top/Article/details/gthscqjkic.html

[R41] 丢弃输出
来源：http://dali.0kj1m.cn/Article/details/gtbccebrzm.html

cmd >/dev/null 2>&1
来源：http://dali.hnqzz.top/Article/details/gtqhaarvct.html

[R42] 输入重定向
来源：http://dali.cashguo.top/Article/details/gtsovtseol.html

wc -l < a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtnieefyfd.html

[R43] 按名字查找文件
来源：http://dali.redwolf501.top/Article/details/gtloxojryo.html

find . -name "*.log" -type f
来源：http://dali.shanyushiyangkeji.top/Article/details/gthcpinsrc.html

[R44] 按修改时间查找
来源：http://dali.ybcxt.top/Article/details/gtpmqpfhvy.html

find . -mtime -7 -type f
来源：http://dali.aizwys.cn/Article/details/gtawjdrlts.html

[R45] 批量删除
来源：http://dali.sysykeji.top/Article/details/gtcflaicas.html

find . -name "*.tmp" -delete
来源：http://dali.316326.xyz/Article/details/gtyizzbuqi.html

[R46] 递归替换文件内容
来源：http://dali.hywenlv.cn/Article/details/gtswzwkugn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangdashe.top/Article/details/gtlkkwxmib.html

[R47] sed 单行替换
来源：http://dali.snrcjt.cn/Article/details/gtvpouvmwo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.andypj.xyz/Article/details/gthieutglx.html

[R48] awk 取指定列
来源：http://dali.zycfv.cn/Article/details/gtsnbvyeud.html

awk '{print $1, $3}' a.txt
来源：http://dali.ybcxt.top/Article/details/gtgybaznlo.html

[R49] awk 带条件
来源：http://dali.havefunace.top/Article/details/gtzzarbenv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fengsongda.top/Article/details/gtuljnvwhr.html

[R50] awk 求和
来源：http://dali.c1oappe.top/Article/details/gtgujahfko.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gtixmfhxvk.html

[R51] 排序去重取前几
来源：http://dali.dianchejie.cn/Article/details/gtiwxjfxdh.html


<!-- 参考信息 -->