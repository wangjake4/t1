代发 wailian999

);
来源：http://dali.feifeiyinyue.top/Article/details/gtierdfsvc.html

[Q03] 增加列
来源：http://dali.nanxuanxn.top/Article/details/gtunqvhhvm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yanxiufei.cn/Article/details/gtyjkxehkj.html

[Q04] 修改列类型
来源：http://dali.fzhhl.top/Article/details/gttdgxunho.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.mhx1999.top/Article/details/gtnzlccrgy.html

[Q05] 重命名列
来源：http://dali.yanxiufei.cn/Article/details/gtdclsmagx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ivvv.top/Article/details/gtlsbbbjql.html

[Q06] 删除列
来源：http://dali.aizwys.cn/Article/details/gtajjnurbw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nanxuanxn.top/Article/details/gtzhwrhkoz.html

[Q07] 删除表
来源：http://dali.ehwqpu.com/Article/details/gtwliagmea.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jqgufenzy.top/Article/details/gtajkovlir.html

[Q08] 创建普通索引
来源：http://dali.zdqjudy.top/Article/details/gtjhfkdlcq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.0kj1m.cn/Article/details/gtvrifwxvi.html

[Q09] 创建唯一索引
来源：http://dali.zhiwuduotai.top/Article/details/gthpyhfjpu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsyfrerej.html

[Q10] 插入单行
来源：http://dali.iojbl.cn/Article/details/gttufbqcjv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.dianchejie.cn/Article/details/gtxywygxyq.html

[Q11] 一次插入多行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpinhkszw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jiagoushi.top/Article/details/gtrkfzlhnp.html

[Q12] 插入后取自增 ID
来源：http://dali.jianghu66.top/Article/details/gtoluxlplu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangdashe.top/Article/details/gthijubspy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.kuanghao11.cn/Article/details/gtaqeopzcx.html

[Q13] 忽略重复插入
来源：http://dali.316326.xyz/Article/details/gtgwyjnusm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nwbrower.top/Article/details/gtnaltksqw.html

[Q14] 存在则更新（upsert）
来源：http://dali.hywenlv.cn/Article/details/gtdvkqeege.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yuxming.cn/Article/details/gtcguxdklk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hammf.cn/Article/details/gtkbztgujt.html

[Q15] 查询全部
来源：http://dali.aibaodan.cn/Article/details/gtbumpcabw.html

SELECT * FROM users;
来源：http://dali.cheryme.top/Article/details/gthjkefvau.html

[Q16] 查询指定列
来源：http://dali.jinqigufen.top/Article/details/gtvldqkhzj.html

SELECT id, name FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtkpqbozss.html

[Q17] 条件查询
来源：http://dali.pengpengdd.cyou/Article/details/gtqfuffnci.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhengqikj.top/Article/details/gtkputcioi.html

[Q18] 模糊匹配
来源：http://dali.cheryme.top/Article/details/gtmezuyffr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfsetfgj.html

[Q19] 范围查询
来源：http://dali.nanxinkj.top/Article/details/gtlcvtpdpq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ydzc1.top/Article/details/gtjsfzgeif.html

[Q20] IN 列表
来源：http://dali.wangshuangyany.cn/Article/details/gteayuyjwd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.quarkkingdee.top/Article/details/gtonhrirfz.html

[Q21] 空值判断
来源：http://dali.gotoacloud.top/Article/details/gtkiuvviht.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yueranfly.top/Article/details/gtrquwbdzu.html

[Q22] 排序
来源：http://dali.quarkkingdee.top/Article/details/gtqsxnzeof.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yonumen.top/Article/details/gtvlnltolv.html

[Q23] 分页
来源：http://dali.tian-w.cn/Article/details/gtzoobfjot.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yongpay.top/Article/details/gtewrylvpi.html

[Q24] 去重
来源：http://dali.iojbl.cn/Article/details/gtkwunpzzu.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtyzgpaezi.html

[Q25] 只取前 N 条
来源：http://dali.hysaishi.cn/Article/details/gtyezlwbwz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sufxvd.cn/Article/details/gtxfyxsmtd.html

[Q26] 计数
来源：http://dali.guowangkeji.top/Article/details/gtdcnobiyk.html

SELECT COUNT(*) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtwtkoyfqq.html

[Q27] 条件计数
来源：http://dali.hammf.cn/Article/details/gtdeyfuclz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.havefunace.top/Article/details/gtycmjlpit.html

[Q28] 求和与平均
来源：http://dali.ppjwa.cn/Article/details/gtsikqqdlo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gttaosybzb.html

[Q29] 最大最小值
来源：http://dali.cucudq.cn/Article/details/gtmiiuykoh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.pycfn.com/Article/details/gtgclmkgty.html

[Q30] 分组统计
来源：http://dali.ehwqpu.com/Article/details/gttaqxdspz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gtqodqbjof.html

[Q31] 分组后过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtdouowexr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.bjfxy.top/Article/details/gtteywazvt.html

[Q32] 分组拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gtzvhytzab.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gthpnnsypt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gaohongyu789.top/Article/details/gtxhjqwvec.html

[Q33] 多列分组
来源：http://dali.yongpay.top/Article/details/gtruqxplje.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hysaishi.cn/Article/details/gtfbrsfueu.html

[Q34] 每组取第一条
来源：http://dali.0kj1m.cn/Article/details/gtejtkvwcf.html

SELECT * FROM (
来源：http://dali.bjfxy.top/Article/details/gthvuzofdd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ydzc1.top/Article/details/gtpqhpuvux.html

) t WHERE rn = 1;
来源：http://dali.tanke756.top/Article/details/gtrvlrvadj.html

[Q35] 内连接
来源：http://dali.pengpengdd.cyou/Article/details/gtbfnmzypt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuanzx.com/Article/details/gtbxuwfasp.html

[Q36] 左连接
来源：http://dali.chenjidiqi.icu/Article/details/gtkamhewhe.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gteujzwmzq.html

[Q37] 右连接
来源：http://dali.yuanzhike.top/Article/details/gtyulryepg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.wangshuangyany.cn/Article/details/gtvfgvmlqx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sweek.top/Article/details/gtbsuhfqkm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhixingplan.top/Article/details/gtvarkdjus.html

[Q39] 自连接（查上下级）
来源：http://dali.yvedp.cn/Article/details/gtuvhwjnxu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.aibaodan.cn/Article/details/gtavpqndru.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jlsjyb.cn/Article/details/gtkangbbof.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangdashe.top/Article/details/gttvmbjekh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ppjwa.cn/Article/details/gtnshxrkbw.html

[Q41] 多表连接
来源：http://dali.sxryk.cn/Article/details/gtqwajbgpf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jlsjyb.cn/Article/details/gthqkthxhc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.aibaodan.cn/Article/details/gtzxxaakzc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xinyue.icu/Article/details/gtjtfcheco.html

[Q42] 连接条件附加过滤
来源：http://dali.jinqigfzy.top/Article/details/gtovsbwyqo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenzaomai.com/Article/details/gtfpqwajdo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gaohongyu789.top/Article/details/gtsgbvgfjh.html

[Q43] 标量子查询
来源：http://dali.snrcjt.cn/Article/details/gtxniouvdn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aibaodan.cn/Article/details/gtlcshuovz.html

[Q44] IN 子查询
来源：http://dali.0kj1m.cn/Article/details/gtuaivhwdf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shzxlz.cn/Article/details/gtxynqsvmm.html

[Q45] EXISTS 判断存在
来源：http://dali.yueranfly.top/Article/details/gtbiklwggv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnxiangtu.top/Article/details/gtqwooqvpo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cheryme.top/Article/details/gtdwubbahh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhiwuduotai.top/Article/details/gtcqcaleyz.html

[Q47] 与平均值比较
来源：http://dali.ybcxt.top/Article/details/gtnvijdjzz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxkbsgen.html

[Q48] CTE 公用表表达式
来源：http://dali.sweek.top/Article/details/gtwispshco.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.birdmap.top/Article/details/gtlxvkgsya.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.guannengcc.top/Article/details/gteknyiaeb.html

[Q49] 更新单行
来源：http://dali.kuanghao11.cn/Article/details/gtigcnnzbp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuanzx.com/Article/details/gtgoygxwyi.html

[Q50] 批量更新
来源：http://dali.birdmap.top/Article/details/gteimlnsac.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.feifeiyinyue.top/Article/details/gtdrgfikhb.html

[Q51] 用子查询更新
来源：http://dali.fzhhl.top/Article/details/gtapcwcszc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ydzc1.top/Article/details/gtdnuvduwy.html

[Q52] 删除指定行
来源：http://dali.nanxinkj.top/Article/details/gtevqogmmt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gtedthcggc.html

[Q53] 按条件删除
来源：http://dali.zhengqikj.top/Article/details/gthmzrwzho.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.fzhhl.top/Article/details/gtszaxbqhr.html

[Q54] 清空表
来源：http://dali.zhixingplan.top/Article/details/gtxtpxlclb.html

TRUNCATE TABLE logs;
来源：http://dali.dashuyun.cn/Article/details/gtdicktemc.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjiaamapp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tanke756.top/Article/details/gtknpujuip.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhixingplan.top/Article/details/gtblepqpjs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gtzptsunxq.html

[Q57] 行号
来源：http://dali.zhoulong.xyz/Article/details/gtwrfjdfjl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258888.top/Article/details/gtypylbinb.html

[Q58] 累计求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmvkxtzb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtmiyvbrrx.html

[Q59] 分组内累计
来源：http://dali.yj20258888.top/Article/details/gtolelqqvm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtfmakceke.html

[Q60] 取上一行 / 下一行
来源：http://dali.hnxiangtu.top/Article/details/gtbyddmzkt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zdqjudy.top/Article/details/gtsnvhebnt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtfhkawuhx.html

[Q61] 移动平均
来源：http://dali.cqqwz.cn/Article/details/gtnklabivv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtkiwexpoi.html

[Q62] 分组占比
来源：http://dali.gogol.net.cn/Article/details/gtmlhmikhl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtwweweyjm.html

[Q63] 开启事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdeqmvgn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yuanzhike.top/Article/details/gtcoxwgjei.html

[Q64] 提交事务
来源：http://dali.zhongyouzk.top/Article/details/gtuqjxepjd.html

COMMIT;
来源：http://dali.yuxming.cn/Article/details/gtxfsxcuhy.html

[Q65] 回滚事务
来源：http://dali.havefunace.top/Article/details/gtctrnctqw.html

ROLLBACK;
来源：http://dali.daxiang520.top/Article/details/gtpddizdqc.html

[Q66] 行锁查询
来源：http://dali.gotoacloud.top/Article/details/gtkfnlxfcf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.aibaodan.cn/Article/details/gtqrnffncw.html

[Q67] 设置隔离级别
来源：http://dali.wangdashe.top/Article/details/gtqszujfgj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.fengsongda.top/Article/details/gtwovcueru.html

[Q68] 保存点
来源：http://dali.hywenlv.cn/Article/details/gtmqlkqtyp.html

SAVEPOINT sp1;
来源：http://dali.aizwys.cn/Article/details/gtzxrzprsc.html

ROLLBACK TO sp1;
来源：http://dali.hfpthk.cn/Article/details/gtnxgmxfqm.html

[Q69] 查看执行计划
来源：http://dali.quarkkingdee.top/Article/details/gtzjrvhzdu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sweek.top/Article/details/gttplxsvrd.html

[Q70] 更新统计信息
来源：http://dali.svipenyu.cn/Article/details/gtmywgrrto.html

ANALYZE TABLE users;
来源：http://dali.hywenlv.cn/Article/details/gteyzazvmu.html

[Q71] 查看建表语句
来源：http://dali.zhongyouzk.top/Article/details/gtnxjhkhcg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenjidiqi.icu/Article/details/gtahhccplp.html

[Q72] 查看索引
来源：http://dali.zycfv.cn/Article/details/gthapcyqbw.html

SHOW INDEX FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtlnmjonmc.html

[Q73] 查看表状态
来源：http://dali.aibaodan.cn/Article/details/gtsgkdymek.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ehwqpu.com/Article/details/gtvuimlkcj.html

[Q74] 强制使用索引
来源：http://dali.zdqjudy.top/Article/details/gtdtopfdrj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhiwuduotai.top/Article/details/gtwqytkhjg.html

[Q75] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gtgfkornep.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtucfzsmjh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitaiazwj.html

[Q76] 按天统计
来源：http://dali.zhengqikj.top/Article/details/gtssthxumh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhoulong.xyz/Article/details/gtfsdzdbnl.html

[Q77] 时间加减
来源：http://dali.iojbl.cn/Article/details/gtnsrdflsu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nanxinkj.top/Article/details/gtdcehmdda.html

[Q78] 当前时间
来源：http://dali.snrcjt.cn/Article/details/gtkjhowskb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nwbrower.top/Article/details/gtjpnzewgn.html

[Q79] 字符串拼接
来源：http://dali.chenlongwang.top/Article/details/gtcnmaeeii.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzqsgfro.html

[Q80] 字符串截取
来源：http://dali.yangfankeji.com/Article/details/gtzfkfspub.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtqgouxsng.html

[Q81] 字符串替换
来源：http://dali.jiagoushi.top/Article/details/gtbrzhblqw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cashguo.top/Article/details/gtdxuaximo.html

[Q82] 字符长度与字节长度
来源：http://dali.shzxlz.cn/Article/details/gtyzltxudm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtasxjfbhv.html

[Q83] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gtdxblkygr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtfrcdzlrf.html

[Q84] 去除首尾空格
来源：http://dali.iojbl.cn/Article/details/gtilenrrie.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gtokpyoguz.html

[Q85] 数值取整
来源：http://dali.cqqwz.cn/Article/details/gtdvnduomu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.meibo888.top/Article/details/gtiqloclkk.html

[Q86] 读取 JSON 字段
来源：http://dali.gogol.net.cn/Article/details/gtlhxafbue.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yongpay.top/Article/details/gtdsdfbkhk.html

[Q87] JSON 字段做条件
来源：http://dali.xuanzx.com/Article/details/gtfndtotfd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yanxiufei.cn/Article/details/gtlikhmevq.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnxiangtu.top/Article/details/gtvollpakn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cqqwz.cn/Article/details/gtxmtcerpq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtnrdqyqta.html

[Q89] 判断表是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoyucxxof.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.mhx1999.top/Article/details/gtlluseluo.html

[Q90] 生成序号列
来源：http://dali.zhoulong.xyz/Article/details/gtlcgsgyqm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.316326.xyz/Article/details/gtflouplqz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtztvbbgyw.html

R. Bash 专题
来源：http://dali.yj20258888.top/Article/details/gtuwbvzezt.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtabnlvkyr.html

[R01] shebang 与严格模式
来源：http://dali.fengsongda.top/Article/details/gtponejsxp.html

#!/usr/bin/env bash
来源：http://dali.yanxiufei.cn/Article/details/gtezlnpvha.html

set -euo pipefail
来源：http://dali.hywenlv.cn/Article/details/gtgzlftxps.html

[R02] 变量赋值与使用
来源：http://dali.aibaodan.cn/Article/details/gtrkjhedwu.html

name="Tom"; echo "$name"
来源：http://dali.c1oappe.top/Article/details/gtgmzzpsii.html

[R03] 只读变量
来源：http://dali.havefunace.top/Article/details/gtlwiisnnl.html

readonly PI=3.14
来源：http://dali.nanxuanxn.top/Article/details/gtucpnylrz.html

[R04] 位置参数
来源：http://dali.shuidangran.top/Article/details/gthkbplazi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.feifeiyinyue.top/Article/details/gtytebtezv.html

[R05] 参数默认值
来源：http://dali.wangdashe.top/Article/details/gtqewlkvxj.html

name="${1:-default}"
来源：http://dali.dashuyun.cn/Article/details/gtynbhftzw.html

[R06] 判断命令是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gtlfhopoei.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nanxuanxn.top/Article/details/gtzwcjsmya.html

[R07] if 判断文件
来源：http://dali.daria6918.cn/Article/details/gtcjrtdcnu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.wangdashe.top/Article/details/gtogredrom.html

[R08] 数值比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtcunwhkcn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gogol.net.cn/Article/details/gtsibozowq.html

[R09] 字符串比较
来源：http://dali.shuidangran.top/Article/details/gtzsayemjh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.meibo888.top/Article/details/gttalkrhxu.html

[R10] 正则匹配
来源：http://dali.yueranfly.top/Article/details/gtwmpsgrvo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.c1oappe.top/Article/details/gtkvhbiirg.html

[R11] case 多分支
来源：http://dali.xinyue.icu/Article/details/gtxwnzfayt.html

case "$1" in
来源：http://dali.gaohongyu789.top/Article/details/gtftkdqaoq.html

start) echo "启动" ;;
来源：http://dali.fzhhl.top/Article/details/gtjzcbjuis.html

stop)  echo "停止" ;;
来源：http://dali.vqdsnc.cn/Article/details/gtlvktvkxu.html

*)     echo "未知命令" ;;
来源：http://dali.cashguo.top/Article/details/gtmgfpobhg.html

esac
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvocbjtch.html

[R12] for 遍历文件
来源：http://dali.cashguo.top/Article/details/gtzjjzdegv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cashguo.top/Article/details/gtjbmnrnnc.html

[R13] for 计数循环
来源：http://dali.dianchejie.cn/Article/details/gtwlpjxyuf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gtdxjmsncj.html

[R14] C 风格 for
来源：http://dali.hongshengwenyu.top/Article/details/gtjckkazif.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zycfv.cn/Article/details/gteggeddkb.html

[R15] while 逐行读文件
来源：http://dali.hammf.cn/Article/details/gtrqqbyytc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ybcxt.top/Article/details/gtftcrxnwu.html

[R16] until 等待条件
来源：http://dali.haohaochexian.top/Article/details/gtlkypelai.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gtdjtdvghj.html

[R17] 数组定义与取值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxyqaeou.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.dashuyun.cn/Article/details/gtjkfsmgmd.html

[R18] 遍历数组
来源：http://dali.nanxinkj.top/Article/details/gttfldklmy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.kuanghao11.cn/Article/details/gtaadhetfg.html

[R19] 数组长度
来源：http://dali.yj20258.top/Article/details/gtlrinuchn.html

echo "${#arr[@]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtjynlwlpy.html

[R20] 关联数组（字典）
来源：http://dali.dashuyun.cn/Article/details/gtaklkwfpp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daxiang520.top/Article/details/gtitfrudwi.html

[R21] 字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gtwzxzkfba.html

echo "${#s}"
来源：http://dali.shangyingyoupin.top/Article/details/gtuezztbwo.html

[R22] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gtclnlpdgd.html

echo "${s:0:5}"
来源：http://dali.jinqigufen.top/Article/details/gtxkcwsrzo.html

[R23] 字符串替换
来源：http://dali.wangdashe.top/Article/details/gtibajfkqg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sxryk.cn/Article/details/gtswmqzcpe.html

[R24] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gtltabcygr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cdnleiting.top/Article/details/gtqmyuobur.html

[R25] 去后缀 / 去前缀
来源：http://dali.tianlin.xyz/Article/details/gtnskrqkrk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yanxiufei.cn/Article/details/gtiuyyqcst.html

[R26] 命令替换
来源：http://dali.hfpthk.cn/Article/details/gtoleumaec.html

now=$(date +%F); echo "$now"
来源：http://dali.tanke756.top/Article/details/gteqxfxtho.html

[R27] 算术展开
来源：http://dali.tianlin.xyz/Article/details/gtejshnojq.html

echo $((1 + 2 * 3))
来源：http://dali.guowangkeji.top/Article/details/gtvniacgur.html

[R28] 浮点运算
来源：http://dali.gaohongyu789.top/Article/details/gtliuourby.html

echo "scale=2; 10/3" | bc
来源：http://dali.dashuyun.cn/Article/details/gtbcksajnq.html

[R29] 定义函数
来源：http://dali.gzhubu.top/Article/details/gtzuexjhwl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guowangkeji.top/Article/details/gtlyempwlp.html

[R30] 函数返回状态码
来源：http://dali.zhengqikj.top/Article/details/gtuvmquijq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yongpay.top/Article/details/gteeaexksk.html

[R31] 局部变量
来源：http://dali.nwbrower.top/Article/details/gtqeikommn.html

f() { local x=1; echo "$x"; }
来源：http://dali.yueranfly.top/Article/details/gtovwnsiex.html

[R32] 参数个数校验
来源：http://dali.cdnleiting.top/Article/details/gthvgbmqxs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shuidangran.top/Article/details/gtdugcdapx.html

[R33] 捕获错误并提示行号
来源：http://dali.ehwqpu.com/Article/details/gtcljhfuou.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwlgysdz.html

[R34] 退出时清理
来源：http://dali.yj20258888.top/Article/details/gteztcvfnd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gtckovzpwd.html

[R35] 后台执行并等待
来源：http://dali.yj20258888.top/Article/details/gtugoxpzqc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnxiangtu.top/Article/details/gtgevvfozu.html

[R36] 并发执行多个任务
来源：http://dali.cqqwz.cn/Article/details/gtjwqkzcmo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.quarkkingdee.top/Article/details/gtkgdfpavq.html

[R37] 把输出赋给变量
来源：http://dali.dashuyun.cn/Article/details/gtdthutzgk.html

files=$(ls -1)
来源：http://dali.xylfe.cn/Article/details/gtcsqicbec.html

[R38] 管道串联
来源：http://dali.gotoacloud.top/Article/details/gtriixfzwc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258.top/Article/details/gtqcnucwls.html

[R39] 重定向标准输出与错误
来源：http://dali.birdmap.top/Article/details/gtoqjadski.html

cmd > out.log 2>&1
来源：http://dali.feifeiyinyue.top/Article/details/gtfcwwfrsx.html

[R40] 追加写日志
来源：http://dali.gotoacloud.top/Article/details/gtmignyarf.html

echo "log" >> out.log
来源：http://dali.yonumen.top/Article/details/gtiaabnulm.html

[R41] 丢弃输出
来源：http://dali.guowangkeji.top/Article/details/gtgxtraukc.html

cmd >/dev/null 2>&1
来源：http://dali.meibo888.top/Article/details/gtkhuvthml.html

[R42] 输入重定向
来源：http://dali.yj20258.top/Article/details/gtvglxzpid.html

wc -l < a.txt
来源：http://dali.mhx1999.top/Article/details/gtmrmpwskc.html

[R43] 按名字查找文件
来源：http://dali.jlsjyb.cn/Article/details/gtxqbnjqzy.html

find . -name "*.log" -type f
来源：http://dali.yonumen.top/Article/details/gtmewqetun.html

[R44] 按修改时间查找
来源：http://dali.daria6918.cn/Article/details/gtmkimdjvp.html

find . -mtime -7 -type f
来源：http://dali.daxiang520.top/Article/details/gtbqmiccbw.html

[R45] 批量删除
来源：http://dali.chenlongwang.top/Article/details/gtsxazewmn.html

find . -name "*.tmp" -delete
来源：http://dali.jinqigfzy.top/Article/details/gthzppqsdx.html

[R46] 递归替换文件内容
来源：http://dali.andypj.xyz/Article/details/gtdhjotjfy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlwwbjad.html

[R47] sed 单行替换
来源：http://dali.shangyingyoupin.top/Article/details/gtpnejpvte.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hnqzz.top/Article/details/gtpniiwxpr.html

[R48] awk 取指定列
来源：http://dali.wangdashe.top/Article/details/gtkamogcpm.html

awk '{print $1, $3}' a.txt
来源：http://dali.yvedp.cn/Article/details/gtcqokfhgs.html

[R49] awk 带条件
来源：http://dali.yj202588.top/Article/details/gtzqbkrvid.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cucudq.cn/Article/details/gtmukkrorj.html

[R50] awk 求和
来源：http://dali.gotoacloud.top/Article/details/gtckchqisb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj20258888.top/Article/details/gtlrhitmue.html

[R51] 排序去重取前几
来源：http://dali.snrcjt.cn/Article/details/gtgobhgrhi.html


<!-- 参考信息 -->