代发 wailian999

ALTER TABLE users DROP COLUMN age;
来源：http://dali.meibo888.top/Article/details/gtqnxmbygm.html

[Q07] 删除表
来源：http://dali.nanxinkj.top/Article/details/gtkrflqmxg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.fzhhl.top/Article/details/gtfushesvc.html

[Q08] 创建普通索引
来源：http://dali.sweek.top/Article/details/gtigqkxypt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbphcbgmy.html

[Q09] 创建唯一索引
来源：http://dali.yuxming.cn/Article/details/gtulbujnfv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hnxiangtu.top/Article/details/gtetfbvghx.html

[Q10] 插入单行
来源：http://dali.xuetiantiany.cn/Article/details/gtxbwirirf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gtakruehrr.html

[Q11] 一次插入多行
来源：http://dali.guowangkeji.top/Article/details/gtjrvtvzrn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ivvv.top/Article/details/gtkcwfvwxa.html

[Q12] 插入后取自增 ID
来源：http://dali.shuidangran.top/Article/details/gtgvwhvvjp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gogol.net.cn/Article/details/gtsschpzop.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.guowangkeji.top/Article/details/gtxupmsmpo.html

[Q13] 忽略重复插入
来源：http://dali.hywenlv.cn/Article/details/gtbzlmezss.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigufen.top/Article/details/gtjdeuopij.html

[Q14] 存在则更新（upsert）
来源：http://dali.cucudq.cn/Article/details/gtmfuwmcng.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtplioiwzm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jyoumei.cn/Article/details/gtbrhcoqji.html

[Q15] 查询全部
来源：http://dali.xinyue.icu/Article/details/gtpvtenqui.html

SELECT * FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtgzfvvoxo.html

[Q16] 查询指定列
来源：http://dali.havefunace.top/Article/details/gtyqkckget.html

SELECT id, name FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtodgdjbua.html

[Q17] 条件查询
来源：http://dali.tanke756.top/Article/details/gtbroogdla.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.svipenyu.cn/Article/details/gtriqcklux.html

[Q18] 模糊匹配
来源：http://dali.dianchejie.cn/Article/details/gtngukoisk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwjegmvl.html

[Q19] 范围查询
来源：http://dali.xylfe.cn/Article/details/gtfjqyfrru.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenlongwang.top/Article/details/gtcatpuena.html

[Q20] IN 列表
来源：http://dali.andypj.xyz/Article/details/gtququsexd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yvedp.cn/Article/details/gtiwjifedh.html

[Q21] 空值判断
来源：http://dali.sxryk.cn/Article/details/gtdgcugpgh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.andypj.xyz/Article/details/gtqgaiaozu.html

[Q22] 排序
来源：http://dali.dianchejie.cn/Article/details/gtvisdqfom.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jiagoushi.top/Article/details/gtqcanoefr.html

[Q23] 分页
来源：http://dali.aizwys.cn/Article/details/gtoaagboyf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppeuqdmn.html

[Q24] 去重
来源：http://dali.zhengqikj.top/Article/details/gtdoofdzyw.html

SELECT DISTINCT city FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtjgyehhsm.html

[Q25] 只取前 N 条
来源：http://dali.hnqzz.top/Article/details/gtmibzbdnd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhoulong.xyz/Article/details/gtdkbgcblt.html

[Q26] 计数
来源：http://dali.sweek.top/Article/details/gtewmtbmuo.html

SELECT COUNT(*) FROM users;
来源：http://dali.xylfe.cn/Article/details/gttosgiwxz.html

[Q27] 条件计数
来源：http://dali.ppjwa.cn/Article/details/gtmqgjhvow.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtldbmdkaf.html

[Q28] 求和与平均
来源：http://dali.aizwys.cn/Article/details/gtdoyshcqw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yonumen.top/Article/details/gthbkintcj.html

[Q29] 最大最小值
来源：http://dali.xinyue.icu/Article/details/gtxymqhcki.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtnrgsgzoz.html

[Q30] 分组统计
来源：http://dali.gogol.net.cn/Article/details/gtusaueohr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gtlzaijrjg.html

[Q31] 分组后过滤
来源：http://dali.sysykeji.top/Article/details/gtcpyfuaxh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nwbrower.top/Article/details/gtojqyqhtm.html

[Q32] 分组拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gtzyyuttpl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gtgeealuwn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xylfe.cn/Article/details/gtoxyowgbk.html

[Q33] 多列分组
来源：http://dali.xuetiantiany.cn/Article/details/gtlqiwskdk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.smart0.xyz/Article/details/gthqugwbsz.html

[Q34] 每组取第一条
来源：http://dali.havefunace.top/Article/details/gtdcsymgxt.html

SELECT * FROM (
来源：http://dali.xuanzx.com/Article/details/gtbvosojgk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cheryme.top/Article/details/gtpxzqnldp.html

) t WHERE rn = 1;
来源：http://dali.xziqi.cn/Article/details/gttmktmorh.html

[Q35] 内连接
来源：http://dali.xuetiantiany.cn/Article/details/gtewkbqbry.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gtpmjekmaf.html

[Q36] 左连接
来源：http://dali.hnxiangtu.top/Article/details/gtjegeenak.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqvjdzhh.html

[Q37] 右连接
来源：http://dali.aibaodan.cn/Article/details/gthgsfjlxj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.pycfn.com/Article/details/gthyilresi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhiwuduotai.top/Article/details/gtesaqdwkw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tanke756.top/Article/details/gtncjtiecb.html

[Q39] 自连接（查上下级）
来源：http://dali.chenlongwang.top/Article/details/gtrzbxskti.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenlongwang.top/Article/details/gtpkincnjp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.meibo888.top/Article/details/gtlbgikify.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ybcxt.top/Article/details/gtxuhjamjj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nanxinkj.top/Article/details/gtllbkbzqc.html

[Q41] 多表连接
来源：http://dali.gzhubu.top/Article/details/gtfwklegaw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yongpay.top/Article/details/gtusdjvsmm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sysykeji.top/Article/details/gttgnfpmxg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuanzx.com/Article/details/gtmewkjuaa.html

[Q42] 连接条件附加过滤
来源：http://dali.gogol.net.cn/Article/details/gtzwspbwvx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.pycfn.com/Article/details/gtznlovgkd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xinyue.icu/Article/details/gtxwttmcex.html

[Q43] 标量子查询
来源：http://dali.fzhhl.top/Article/details/gtpfkenyid.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cqqwz.cn/Article/details/gtdsuiixum.html

[Q44] IN 子查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqiuuhpor.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yangfankeji.com/Article/details/gttbybrsnd.html

[Q45] EXISTS 判断存在
来源：http://dali.hnqzz.top/Article/details/gtivkppofs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dashuyun.cn/Article/details/gtohhhpixe.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hnqzz.top/Article/details/gtzpfsqqiv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.kuanghao11.cn/Article/details/gtmizhcvrb.html

[Q47] 与平均值比较
来源：http://dali.cheryme.top/Article/details/gtfxhbvyqy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gaohongyu789.top/Article/details/gtvqjyclil.html

[Q48] CTE 公用表表达式
来源：http://dali.tianlin.xyz/Article/details/gtdwagcmgb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shuidangran.top/Article/details/gtdwgiezqk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cheryme.top/Article/details/gtqjtljdob.html

[Q49] 更新单行
来源：http://dali.chenzaomai.com/Article/details/gtmqxwkrib.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuanzx.com/Article/details/gttzzyzamu.html

[Q50] 批量更新
来源：http://dali.wangdashe.top/Article/details/gtdngmmpgr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gtgucppscc.html

[Q51] 用子查询更新
来源：http://dali.zhongyouzk.top/Article/details/gtjqlnygjb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cqqwz.cn/Article/details/gtdasoecha.html

[Q52] 删除指定行
来源：http://dali.sufxvd.cn/Article/details/gtssrrvzjg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zdqjudy.top/Article/details/gtxowqlpbe.html

[Q53] 按条件删除
来源：http://dali.sufxvd.cn/Article/details/gthoscxbvt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ppjwa.cn/Article/details/gtxxsfhflr.html

[Q54] 清空表
来源：http://dali.xuanzx.com/Article/details/gtumptbskg.html

TRUNCATE TABLE logs;
来源：http://dali.svipenyu.cn/Article/details/gtmcaaleyc.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjpsbsyyt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hnqzz.top/Article/details/gtefgfrkyz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigufen.top/Article/details/gtbmxeuhoy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hnqzz.top/Article/details/gtvsohsodi.html

[Q57] 行号
来源：http://dali.zdqjudy.top/Article/details/gtnbqimpvq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gzhubu.top/Article/details/gtycurjdgh.html

[Q58] 累计求和
来源：http://dali.sweek.top/Article/details/gtiydcoeuq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtpnsqxltt.html

[Q59] 分组内累计
来源：http://dali.snrcjt.cn/Article/details/gtboxpogym.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtnokoybrs.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuetiantiany.cn/Article/details/gtfprwqzjb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xziqi.cn/Article/details/gtyxeikzqu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtnkvcvrfx.html

[Q61] 移动平均
来源：http://dali.dianchejie.cn/Article/details/gtnfjddnsj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gthmweeerz.html

[Q62] 分组占比
来源：http://dali.xziqi.cn/Article/details/gtanqxtnwt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gtesnvglqy.html

[Q63] 开启事务
来源：http://dali.ybcxt.top/Article/details/gtmwxniwzp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenzaomai.com/Article/details/gtnrmuxawz.html

[Q64] 提交事务
来源：http://dali.xuetiantiany.cn/Article/details/gtvnsihkej.html

COMMIT;
来源：http://dali.pengpengdd.cyou/Article/details/gtbmmrrndb.html

[Q65] 回滚事务
来源：http://dali.sweek.top/Article/details/gtqiqyfnoy.html

ROLLBACK;
来源：http://dali.snrcjt.cn/Article/details/gtlqdbguyd.html

[Q66] 行锁查询
来源：http://dali.birdmap.top/Article/details/gtpqcuhxge.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cheryme.top/Article/details/gtqnmzdzjk.html

[Q67] 设置隔离级别
来源：http://dali.nwbrower.top/Article/details/gtzjgpxrbr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxinkj.top/Article/details/gtkarttsee.html

[Q68] 保存点
来源：http://dali.dashuyun.cn/Article/details/gtdswesobc.html

SAVEPOINT sp1;
来源：http://dali.chenzaomai.com/Article/details/gtmrwpmqdf.html

ROLLBACK TO sp1;
来源：http://dali.shzxlz.cn/Article/details/gtwzgfjnvs.html

[Q69] 查看执行计划
来源：http://dali.zhiwuduotai.top/Article/details/gtedasnvli.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sysykeji.top/Article/details/gtytvmlhqx.html

[Q70] 更新统计信息
来源：http://dali.9152youxi.cn/Article/details/gtpfzbkhdg.html

ANALYZE TABLE users;
来源：http://dali.hongshengwenyu.top/Article/details/gtxxxegadb.html

[Q71] 查看建表语句
来源：http://dali.nanxinkj.top/Article/details/gtrhamazyd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sweek.top/Article/details/gtorkixrlg.html

[Q72] 查看索引
来源：http://dali.gogol.net.cn/Article/details/gtjnkzdgjy.html

SHOW INDEX FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtsskcnueg.html

[Q73] 查看表状态
来源：http://dali.birdmap.top/Article/details/gtiqmvvhnw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hnqzz.top/Article/details/gthtfnimpu.html

[Q74] 强制使用索引
来源：http://dali.c1oappe.top/Article/details/gtmchbizwn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hywenlv.cn/Article/details/gtqjrmyard.html

[Q75] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtjyasozsd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.pycfn.com/Article/details/gtpbfvjlrs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangshuangyany.cn/Article/details/gtwhpnvywt.html

[Q76] 按天统计
来源：http://dali.gogol.net.cn/Article/details/gtvoghlwer.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.vqdsnc.cn/Article/details/gtcieynuky.html

[Q77] 时间加减
来源：http://dali.hfpthk.cn/Article/details/gtvpywjybo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jlsjyb.cn/Article/details/gtgigghpml.html

[Q78] 当前时间
来源：http://dali.pycfn.com/Article/details/gtfbtcyhuh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gtqnuyfofp.html

[Q79] 字符串拼接
来源：http://dali.birdmap.top/Article/details/gtsdogqxwp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ivvv.top/Article/details/gtqgsajavv.html

[Q80] 字符串截取
来源：http://dali.cdnleiting.top/Article/details/gtrvfylmvg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtvuvqeqns.html

[Q81] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gtkbpjmxyz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tian-w.cn/Article/details/gtlfejjsip.html

[Q82] 字符长度与字节长度
来源：http://dali.daxiang520.top/Article/details/gtrgfsfdve.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gtivgbcbfo.html

[Q83] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdigcxkka.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtvucrhmwb.html

[Q84] 去除首尾空格
来源：http://dali.gaohongyu789.top/Article/details/gttybpiopm.html

SELECT TRIM(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gtkgtqewoo.html

[Q85] 数值取整
来源：http://dali.daxiang520.top/Article/details/gtlpceopyi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sysykeji.top/Article/details/gtjxrodxff.html

[Q86] 读取 JSON 字段
来源：http://dali.hongshengwenyu.top/Article/details/gtgdyybpcz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ehwqpu.com/Article/details/gtlzkdengz.html

[Q87] JSON 字段做条件
来源：http://dali.meibo888.top/Article/details/gtfbzlvycv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yuanzhike.top/Article/details/gtaknnbgoy.html

[Q88] 行转列（条件聚合）
来源：http://dali.zdqjudy.top/Article/details/gtpnnyddii.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cheryme.top/Article/details/gtvsncklnv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtvloxumvy.html

[Q89] 判断表是否存在
来源：http://dali.redwolf501.top/Article/details/gtxuefksjl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenzaomai.com/Article/details/gtsmodyaly.html

[Q90] 生成序号列
来源：http://dali.zhoulong.xyz/Article/details/gtukwdfoal.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aizwys.cn/Article/details/gtwpdwjovi.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtsmqtcqux.html

R. Bash 专题
来源：http://dali.yj20258888.top/Article/details/gtafegbdwx.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtjfokqwgq.html

[R01] shebang 与严格模式
来源：http://dali.sysykeji.top/Article/details/gtcsafcrlf.html

#!/usr/bin/env bash
来源：http://dali.ehwqpu.com/Article/details/gthteodhxm.html

set -euo pipefail
来源：http://dali.xuetiantiany.cn/Article/details/gtovvbvqwl.html

[R02] 变量赋值与使用
来源：http://dali.chenzaomai.com/Article/details/gtduovoqbe.html

name="Tom"; echo "$name"
来源：http://dali.yonumen.top/Article/details/gtjvlqlrah.html

[R03] 只读变量
来源：http://dali.nanxinkj.top/Article/details/gtuleubqcg.html

readonly PI=3.14
来源：http://dali.hfpthk.cn/Article/details/gtdddwjwvg.html

[R04] 位置参数
来源：http://dali.aibaodan.cn/Article/details/gttmradahc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.redwolf501.top/Article/details/gtzqqiazxj.html

[R05] 参数默认值
来源：http://dali.gotoacloud.top/Article/details/gtitnedids.html

name="${1:-default}"
来源：http://dali.ydzc1.top/Article/details/gtiswurmpz.html

[R06] 判断命令是否存在
来源：http://dali.shzxlz.cn/Article/details/gtfreeuuhu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sweek.top/Article/details/gtyuszmely.html

[R07] if 判断文件
来源：http://dali.c1oappe.top/Article/details/gtjhyutpjm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yueranfly.top/Article/details/gttverzhzz.html

[R08] 数值比较
来源：http://dali.ehwqpu.com/Article/details/gtfqcgcjui.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.fengsongda.top/Article/details/gtkhjydytb.html

[R09] 字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gtlgviptve.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtwoneoneh.html

[R10] 正则匹配
来源：http://dali.pycfn.com/Article/details/gttfnqgric.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gogol.net.cn/Article/details/gtmgntiich.html

[R11] case 多分支
来源：http://dali.fzhhl.top/Article/details/gtiqctweay.html

case "$1" in
来源：http://dali.xziqi.cn/Article/details/gtktyjaqdq.html

start) echo "启动" ;;
来源：http://dali.hammf.cn/Article/details/gtcyrwfvpg.html

stop)  echo "停止" ;;
来源：http://dali.snrcjt.cn/Article/details/gtqqqfkdab.html

*)     echo "未知命令" ;;
来源：http://dali.yvedp.cn/Article/details/gtnwvnxcxr.html

esac
来源：http://dali.zhixingplan.top/Article/details/gtmcqssvzb.html

[R12] for 遍历文件
来源：http://dali.dashuyun.cn/Article/details/gtlhqwqbgy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuanzx.com/Article/details/gtgyntekdu.html

[R13] for 计数循环
来源：http://dali.hammf.cn/Article/details/gtwwjkqthq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gtfjjfomex.html

[R14] C 风格 for
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvcdltnjl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dashuyun.cn/Article/details/gtuemzajap.html

[R15] while 逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtszvdxlpq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xziqi.cn/Article/details/gthqfztqxm.html

[R16] until 等待条件
来源：http://dali.andypj.xyz/Article/details/gtyaqucgmo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gthtnemlmz.html

[R17] 数组定义与取值
来源：http://dali.snrcjt.cn/Article/details/gtfevlsbei.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenlongwang.top/Article/details/gtxuzsgnhy.html

[R18] 遍历数组
来源：http://dali.c1oappe.top/Article/details/gtaowlsvav.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gotoacloud.top/Article/details/gtxnwmpxss.html

[R19] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gtmaxjjtgd.html

echo "${#arr[@]}"
来源：http://dali.dashuyun.cn/Article/details/gtpyxmebef.html

[R20] 关联数组（字典）
来源：http://dali.zhongyouzk.top/Article/details/gtlhgvbhte.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhoulong.xyz/Article/details/gtyugekscw.html

[R21] 字符串长度
来源：http://dali.shuidangran.top/Article/details/gthzyodvtr.html

echo "${#s}"
来源：http://dali.jqgufenzy.top/Article/details/gtqwvrgcgn.html

[R22] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gttjuiifxm.html

echo "${s:0:5}"
来源：http://dali.nwbrower.top/Article/details/gtysocugjh.html

[R23] 字符串替换
来源：http://dali.zhoulong.xyz/Article/details/gtmfmwugqs.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nwbrower.top/Article/details/gtylqdspwa.html

[R24] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gtdwskfnio.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tian-w.cn/Article/details/gtexrarvmt.html

[R25] 去后缀 / 去前缀
来源：http://dali.snrcjt.cn/Article/details/gtdpjzbtwo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yueranfly.top/Article/details/gtkpowtdof.html

[R26] 命令替换
来源：http://dali.0kj1m.cn/Article/details/gtongpavij.html

now=$(date +%F); echo "$now"
来源：http://dali.daxiang520.top/Article/details/gtybofzigt.html

[R27] 算术展开
来源：http://dali.hfpthk.cn/Article/details/gtytackgpo.html

echo $((1 + 2 * 3))
来源：http://dali.jianghu66.top/Article/details/gtmkticdrf.html

[R28] 浮点运算
来源：http://dali.redwolf501.top/Article/details/gtcsoxmtuo.html

echo "scale=2; 10/3" | bc
来源：http://dali.nwbrower.top/Article/details/gtjpnvbizo.html

[R29] 定义函数
来源：http://dali.jinqigfzy.top/Article/details/gtwqdxbuha.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nwbrower.top/Article/details/gtojcfnmts.html

[R30] 函数返回状态码
来源：http://dali.ivvv.top/Article/details/gtdzxiivhh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sweek.top/Article/details/gtuoyxtgkp.html

[R31] 局部变量
来源：http://dali.gaohongyu789.top/Article/details/gtkrsjcxni.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gtrzirjjjj.html

[R32] 参数个数校验
来源：http://dali.birdmap.top/Article/details/gtwnvrxwgr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gtptzlfxro.html

[R33] 捕获错误并提示行号
来源：http://dali.shangyingyoupin.top/Article/details/gtayuhcqlf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhixingplan.top/Article/details/gtxwjpwepp.html

[R34] 退出时清理
来源：http://dali.nwbrower.top/Article/details/gtbcsueeqs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gtedgfhlkz.html

[R35] 后台执行并等待
来源：http://dali.dashuyun.cn/Article/details/gtpaaefegz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.haohaochexian.top/Article/details/gtwhsgbysi.html

[R36] 并发执行多个任务
来源：http://dali.nwbrower.top/Article/details/gtubszlsym.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.birdmap.top/Article/details/gtxjewmjwa.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gtlkydsokn.html

files=$(ls -1)
来源：http://dali.chenlongwang.top/Article/details/gtdkrltswj.html

[R38] 管道串联
来源：http://dali.bjfxy.top/Article/details/gtfkreitzz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.9152youxi.cn/Article/details/gtvvuauwws.html

[R39] 重定向标准输出与错误
来源：http://dali.gogol.net.cn/Article/details/gtxpgkytjr.html

cmd > out.log 2>&1
来源：http://dali.jianghu66.top/Article/details/gtkltzvmsa.html

[R40] 追加写日志
来源：http://dali.yongpay.top/Article/details/gtvaxznqsw.html

echo "log" >> out.log
来源：http://dali.mhx1999.top/Article/details/gtxtfjxusi.html

[R41] 丢弃输出
来源：http://dali.chenjidiqi.icu/Article/details/gteqblazou.html

cmd >/dev/null 2>&1
来源：http://dali.aibaodan.cn/Article/details/gtsjeunuya.html

[R42] 输入重定向
来源：http://dali.ydzc1.top/Article/details/gtfujcjkgg.html

wc -l < a.txt
来源：http://dali.xziqi.cn/Article/details/gttozcnwcj.html

[R43] 按名字查找文件
来源：http://dali.vqdsnc.cn/Article/details/gtyefnlwff.html

find . -name "*.log" -type f
来源：http://dali.quarkkingdee.top/Article/details/gtiuofrrjh.html

[R44] 按修改时间查找
来源：http://dali.svipenyu.cn/Article/details/gttjvgawvz.html

find . -mtime -7 -type f
来源：http://dali.jlsjyb.cn/Article/details/gtxkitlhlx.html

[R45] 批量删除
来源：http://dali.hammf.cn/Article/details/gtotlucwar.html

find . -name "*.tmp" -delete
来源：http://dali.cashguo.top/Article/details/gtxevlwrzy.html

[R46] 递归替换文件内容
来源：http://dali.yueranfly.top/Article/details/gtgrzmcxua.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.9152youxi.cn/Article/details/gtohcgrnry.html

[R47] sed 单行替换
来源：http://dali.smart0.xyz/Article/details/gtiqbotleg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jqgfzy.top/Article/details/gtmejxcjjh.html

[R48] awk 取指定列
来源：http://dali.feifeiyinyue.top/Article/details/gtxfhfefrf.html

awk '{print $1, $3}' a.txt
来源：http://dali.birdmap.top/Article/details/gtvrclvpfv.html

[R49] awk 带条件
来源：http://dali.guannengcc.top/Article/details/gtwfworstr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ivvv.top/Article/details/gtediiedet.html

[R50] awk 求和
来源：http://dali.tian-w.cn/Article/details/gttiuuhefy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztqinvii.html

[R51] 排序去重取前几
来源：http://dali.yangfankeji.com/Article/details/gtfbyfgepp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ydzc1.top/Article/details/gtfpkbleoa.html

[R52] 统计行数
来源：http://dali.dashuyun.cn/Article/details/gtbggnevty.html

wc -l a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtqfjrjqtu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhengqikj.top/Article/details/gtoqrqezld.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.smart0.xyz/Article/details/gtlicepvaj.html

[R54] 比较两个文件
来源：http://dali.guannengcc.top/Article/details/gtsoehpztu.html

diff a.txt b.txt
来源：http://dali.aizwys.cn/Article/details/gtlulppeds.html

[R55] 压缩与解压
来源：http://dali.yonumen.top/Article/details/gtqrvveizv.html


<!-- 参考信息 -->