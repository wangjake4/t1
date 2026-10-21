代发 wailian999

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cashguo.top/Article/details/gtqrodjynk.html

[Q07] 删除表
来源：http://dali.shzxlz.cn/Article/details/gtaoobqabq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.kuanghao11.cn/Article/details/gtpvhywwkv.html

[Q08] 创建普通索引
来源：http://dali.gaohongyu789.top/Article/details/gtdldsqgib.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yueranfly.top/Article/details/gtpheeyaif.html

[Q09] 创建唯一索引
来源：http://dali.xziqi.cn/Article/details/gtznuzjfkd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.bjfxy.top/Article/details/gttwvwpqun.html

[Q10] 插入单行
来源：http://dali.dashuyun.cn/Article/details/gtleztbxkv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gtkbbvbcft.html

[Q11] 一次插入多行
来源：http://dali.xuetiantiany.cn/Article/details/gtjkkcygme.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gzhubu.top/Article/details/gtaxxhtexw.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gtepcpopcr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jqgfzy.top/Article/details/gtqfkapyym.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj202588.top/Article/details/gtluvagbhf.html

[Q13] 忽略重复插入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikvptrhv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhhejngl.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhongyouzk.top/Article/details/gtuputuwqf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.aizwys.cn/Article/details/gtrzthiccw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yongpay.top/Article/details/gtbqceoqqr.html

[Q15] 查询全部
来源：http://dali.guowangkeji.top/Article/details/gttialjjkp.html

SELECT * FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtfgaalsqe.html

[Q16] 查询指定列
来源：http://dali.yj20258888.top/Article/details/gttjalzums.html

SELECT id, name FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtinmvqfas.html

[Q17] 条件查询
来源：http://dali.xylfe.cn/Article/details/gtklfkotwl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj202588.top/Article/details/gtmipuhmkl.html

[Q18] 模糊匹配
来源：http://dali.hfpthk.cn/Article/details/gtsnbiehnp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinqigufen.top/Article/details/gtgsqyhyuv.html

[Q19] 范围查询
来源：http://dali.ydzc1.top/Article/details/gtltityaip.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.0kj1m.cn/Article/details/gtjrossoer.html

[Q20] IN 列表
来源：http://dali.yonumen.top/Article/details/gtnvoeitjm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cqqwz.cn/Article/details/gtjvtcfoya.html

[Q21] 空值判断
来源：http://dali.yangfankeji.com/Article/details/gtzotfhglu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gtopebsofz.html

[Q22] 排序
来源：http://dali.yongpay.top/Article/details/gthcqjviwv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.daxiang520.top/Article/details/gtzwwycidd.html

[Q23] 分页
来源：http://dali.jianghu66.top/Article/details/gtyehmeoyd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhengqikj.top/Article/details/gtvmgosxll.html

[Q24] 去重
来源：http://dali.wangshuangyany.cn/Article/details/gtadhipozq.html

SELECT DISTINCT city FROM users;
来源：http://dali.ydzc1.top/Article/details/gtwcvqjnyt.html

[Q25] 只取前 N 条
来源：http://dali.jqgufenzy.top/Article/details/gtncucvvgk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhengqikj.top/Article/details/gtrljasgyf.html

[Q26] 计数
来源：http://dali.9152youxi.cn/Article/details/gtdkmrhimg.html

SELECT COUNT(*) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gthbdviebk.html

[Q27] 条件计数
来源：http://dali.zhoulong.xyz/Article/details/gtdgjpblju.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtaakepejp.html

[Q28] 求和与平均
来源：http://dali.meibo888.top/Article/details/gtpxqiunmv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gttrhijtap.html

[Q29] 最大最小值
来源：http://dali.daxiang520.top/Article/details/gtuwgaaijk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtnunuagrl.html

[Q30] 分组统计
来源：http://dali.mhx1999.top/Article/details/gtezkmdzsc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gtwyrhotvo.html

[Q31] 分组后过滤
来源：http://dali.xinyue.icu/Article/details/gtptucnajz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinqigfzy.top/Article/details/gtyysrhqok.html

[Q32] 分组拼接字符串
来源：http://dali.yuxming.cn/Article/details/gtaadjimel.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gtuwhiqgne.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.c1oappe.top/Article/details/gtcyjzhwbn.html

[Q33] 多列分组
来源：http://dali.ybcxt.top/Article/details/gtthnldpxj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.c1oappe.top/Article/details/gtqopgxtfn.html

[Q34] 每组取第一条
来源：http://dali.sysykeji.top/Article/details/gtjkkrmuon.html

SELECT * FROM (
来源：http://dali.cucudq.cn/Article/details/gtgqruycnt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ehwqpu.com/Article/details/gthpxiunya.html

) t WHERE rn = 1;
来源：http://dali.sysykeji.top/Article/details/gtqezwrlhk.html

[Q35] 内连接
来源：http://dali.ehwqpu.com/Article/details/gtiebjqtxe.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gttekhozgf.html

[Q36] 左连接
来源：http://dali.cdnleiting.top/Article/details/gtwfdbadkl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gtmbabplfo.html

[Q37] 右连接
来源：http://dali.ehwqpu.com/Article/details/gtpzhzxoyk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.kuanghao11.cn/Article/details/gtdljdahgb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xylfe.cn/Article/details/gtxkhiyrzy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.mhx1999.top/Article/details/gtyvgoczfd.html

[Q39] 自连接（查上下级）
来源：http://dali.nanxuanxn.top/Article/details/gtgpnabrgm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.smart0.xyz/Article/details/gtpthcrwll.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtarwlbulr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhiwuduotai.top/Article/details/gtxsmodzal.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.daria6918.cn/Article/details/gtmhlmywww.html

[Q41] 多表连接
来源：http://dali.yvedp.cn/Article/details/gtnbxccqcf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.bjfxy.top/Article/details/gthwvvwgid.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yueranfly.top/Article/details/gttojlugml.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tian-w.cn/Article/details/gtomdcigmd.html

[Q42] 连接条件附加过滤
来源：http://dali.c1oappe.top/Article/details/gthdjzpzsc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnqzz.top/Article/details/gtocwevhtl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.iojbl.cn/Article/details/gtahyisbmw.html

[Q43] 标量子查询
来源：http://dali.cqqwz.cn/Article/details/gtablyumzz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aibaodan.cn/Article/details/gtzdzphwhg.html

[Q44] IN 子查询
来源：http://dali.yueranfly.top/Article/details/gthtzvnoou.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sweek.top/Article/details/gtfctejlqz.html

[Q45] EXISTS 判断存在
来源：http://dali.zhixingplan.top/Article/details/gtxeqvzjrq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvbnrbzz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yuxming.cn/Article/details/gtynjatsnk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gtaknxvmev.html

[Q47] 与平均值比较
来源：http://dali.wangshuangyany.cn/Article/details/gtlzmieppc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnxiangtu.top/Article/details/gtzggtteiu.html

[Q48] CTE 公用表表达式
来源：http://dali.yangfankeji.com/Article/details/gtqdiozbsn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hywenlv.cn/Article/details/gtosmkjmzv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nwbrower.top/Article/details/gtkhydrdgt.html

[Q49] 更新单行
来源：http://dali.cqqwz.cn/Article/details/gtcnfgubda.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtgmazkqwr.html

[Q50] 批量更新
来源：http://dali.iojbl.cn/Article/details/gtwnuyaaog.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xziqi.cn/Article/details/gtpxfpamyc.html

[Q51] 用子查询更新
来源：http://dali.cashguo.top/Article/details/gtlfcsomxe.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yongpay.top/Article/details/gtydkskcid.html

[Q52] 删除指定行
来源：http://dali.yueranfly.top/Article/details/gtgxtdnckx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtagwepfpq.html

[Q53] 按条件删除
来源：http://dali.dashuyun.cn/Article/details/gtyflwzjti.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.andypj.xyz/Article/details/gtrfwkzvdb.html

[Q54] 清空表
来源：http://dali.jinqigufen.top/Article/details/gthsyjplqr.html

TRUNCATE TABLE logs;
来源：http://dali.fengsongda.top/Article/details/gtzppbjwxi.html

[Q55] 排名（并列占位）
来源：http://dali.sufxvd.cn/Article/details/gtvifddzev.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hywenlv.cn/Article/details/gtcvvkmzwb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnelelfyf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sysykeji.top/Article/details/gtdovxxsqy.html

[Q57] 行号
来源：http://dali.yongpay.top/Article/details/gthofcqjig.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sysykeji.top/Article/details/gtwpwxhbmh.html

[Q58] 累计求和
来源：http://dali.aizwys.cn/Article/details/gtokhcimfu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.316326.xyz/Article/details/gtyllsvnws.html

[Q59] 分组内累计
来源：http://dali.nwbrower.top/Article/details/gtazqcuenn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtizqjzxhq.html

[Q60] 取上一行 / 下一行
来源：http://dali.guowangkeji.top/Article/details/gthyxrqbvl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nanxinkj.top/Article/details/gtyffyusgv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtlaxaugni.html

[Q61] 移动平均
来源：http://dali.yj20258.top/Article/details/gtbrwxwtxq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtrkmlmayc.html

[Q62] 分组占比
来源：http://dali.aizwys.cn/Article/details/gtcyfqdulc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gtsjukgxsm.html

[Q63] 开启事务
来源：http://dali.yuxming.cn/Article/details/gtqxpvmpfw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.meibo888.top/Article/details/gtjckfqxvo.html

[Q64] 提交事务
来源：http://dali.sxryk.cn/Article/details/gtnkvmvicj.html

COMMIT;
来源：http://dali.zdqjudy.top/Article/details/gtiwexcept.html

[Q65] 回滚事务
来源：http://dali.hywenlv.cn/Article/details/gtusdzpvii.html

ROLLBACK;
来源：http://dali.nwbrower.top/Article/details/gtzupvlcap.html

[Q66] 行锁查询
来源：http://dali.kuanghao11.cn/Article/details/gtfbfikwtd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.quarkkingdee.top/Article/details/gtrwusecgy.html

[Q67] 设置隔离级别
来源：http://dali.hywenlv.cn/Article/details/gtbbmbbaxx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.316326.xyz/Article/details/gtpuyvbyxi.html

[Q68] 保存点
来源：http://dali.daria6918.cn/Article/details/gtqdyhdgal.html

SAVEPOINT sp1;
来源：http://dali.yvedp.cn/Article/details/gtyahsjysy.html

ROLLBACK TO sp1;
来源：http://dali.ybcxt.top/Article/details/gtlybfdblg.html

[Q69] 查看执行计划
来源：http://dali.tian-w.cn/Article/details/gtwbruhumv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.bjfxy.top/Article/details/gtwszbdocz.html

[Q70] 更新统计信息
来源：http://dali.fzhhl.top/Article/details/gtzriqbebm.html

ANALYZE TABLE users;
来源：http://dali.yonumen.top/Article/details/gtfgjqjyaj.html

[Q71] 查看建表语句
来源：http://dali.yj202588.top/Article/details/gtozlzbvmg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj202588.top/Article/details/gtserjskgb.html

[Q72] 查看索引
来源：http://dali.jqgfzy.top/Article/details/gtamgvfglb.html

SHOW INDEX FROM users;
来源：http://dali.xinyue.icu/Article/details/gtqrsoxxgl.html

[Q73] 查看表状态
来源：http://dali.hnxiangtu.top/Article/details/gtszbgbkkd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.c1oappe.top/Article/details/gtanyolgkb.html

[Q74] 强制使用索引
来源：http://dali.havefunace.top/Article/details/gtspzjucke.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj20258888.top/Article/details/gtxptuqegn.html

[Q75] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gtnrbzhrai.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gthbfaamzk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cheryme.top/Article/details/gthawcroad.html

[Q76] 按天统计
来源：http://dali.yj20258.top/Article/details/gtsorihehz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jyoumei.cn/Article/details/gtilarljqb.html

[Q77] 时间加减
来源：http://dali.pengpengdd.cyou/Article/details/gtvqagsfgd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhiwuduotai.top/Article/details/gtsquigqif.html

[Q78] 当前时间
来源：http://dali.wangdashe.top/Article/details/gtqdlkbajj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.aibaodan.cn/Article/details/gtrfypysvw.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gthplndnba.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhixingplan.top/Article/details/gtabhoyoxd.html

[Q80] 字符串截取
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttclqnlvk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtznpicyus.html

[Q81] 字符串替换
来源：http://dali.pycfn.com/Article/details/gtbyqpuxmb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxyxfdfhz.html

[Q82] 字符长度与字节长度
来源：http://dali.gotoacloud.top/Article/details/gtjrvkdyba.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtprljzrbx.html

[Q83] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gtdmbmmxwa.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtiudartcg.html

[Q84] 去除首尾空格
来源：http://dali.zhongyouzk.top/Article/details/gtstzibsyp.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtfbtsawjq.html

[Q85] 数值取整
来源：http://dali.ybcxt.top/Article/details/gtxdkdffgu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gttjvyzjsi.html

[Q86] 读取 JSON 字段
来源：http://dali.birdmap.top/Article/details/gtyidxximk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yvedp.cn/Article/details/gtyhbwbugo.html

[Q87] JSON 字段做条件
来源：http://dali.nwbrower.top/Article/details/gtlkksipko.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ydzc1.top/Article/details/gtuiagvdox.html

[Q88] 行转列（条件聚合）
来源：http://dali.andypj.xyz/Article/details/gtqbugqnkx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cheryme.top/Article/details/gtmcjeqjkl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.smart0.xyz/Article/details/gtcfvzfjtg.html

[Q89] 判断表是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gttyvvijbo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.aizwys.cn/Article/details/gtlechgjhe.html

[Q90] 生成序号列
来源：http://dali.yuanzhike.top/Article/details/gttanzowjl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yuxming.cn/Article/details/gtzyeevrmj.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtghrfhsmc.html

R. Bash 专题
来源：http://dali.cdnleiting.top/Article/details/gtyfksiyil.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtqcxhnqfa.html

[R01] shebang 与严格模式
来源：http://dali.shangyingyoupin.top/Article/details/gtmkavakvr.html

#!/usr/bin/env bash
来源：http://dali.sxryk.cn/Article/details/gtsujpwcqd.html

set -euo pipefail
来源：http://dali.hysaishi.cn/Article/details/gtlvnlqdsx.html

[R02] 变量赋值与使用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfbmggkb.html

name="Tom"; echo "$name"
来源：http://dali.ppjwa.cn/Article/details/gtpkhgqrav.html

[R03] 只读变量
来源：http://dali.wangdashe.top/Article/details/gttoxbelbm.html

readonly PI=3.14
来源：http://dali.0kj1m.cn/Article/details/gtsdkbwcjd.html

[R04] 位置参数
来源：http://dali.hywenlv.cn/Article/details/gttggwvcky.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yvedp.cn/Article/details/gtqlgsnjxe.html

[R05] 参数默认值
来源：http://dali.jinqigufen.top/Article/details/gtzddrpvtv.html

name="${1:-default}"
来源：http://dali.ppjwa.cn/Article/details/gtwrqzbgjn.html

[R06] 判断命令是否存在
来源：http://dali.tian-w.cn/Article/details/gtxcoxijlx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sweek.top/Article/details/gtnuzrgapy.html

[R07] if 判断文件
来源：http://dali.yj20258.top/Article/details/gtqmbtqkki.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yuanzhike.top/Article/details/gtvghjqggv.html

[R08] 数值比较
来源：http://dali.pycfn.com/Article/details/gtrbmdswtf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.quarkkingdee.top/Article/details/gthdkwgrid.html

[R09] 字符串比较
来源：http://dali.redwolf501.top/Article/details/gtbybzyozb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtigtxldqr.html

[R10] 正则匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtjgztcyow.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cashguo.top/Article/details/gtskltqqmk.html

[R11] case 多分支
来源：http://dali.zhengqikj.top/Article/details/gtrjhemygt.html

case "$1" in
来源：http://dali.pycfn.com/Article/details/gteehhqiao.html

start) echo "启动" ;;
来源：http://dali.gaohongyu789.top/Article/details/gttqioobgw.html

stop)  echo "停止" ;;
来源：http://dali.sysykeji.top/Article/details/gtxfzrledb.html

*)     echo "未知命令" ;;
来源：http://dali.sweek.top/Article/details/gtkolfmbyn.html

esac
来源：http://dali.yj202588.top/Article/details/gtnjqobieg.html

[R12] for 遍历文件
来源：http://dali.yj20258.top/Article/details/gtsnjmqmys.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jiagoushi.top/Article/details/gtmxvorisp.html

[R13] for 计数循环
来源：http://dali.tanke756.top/Article/details/gtpcsozytq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.dashuyun.cn/Article/details/gtcrfxsivh.html

[R14] C 风格 for
来源：http://dali.xinyue.icu/Article/details/gtprhcrbxr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.snrcjt.cn/Article/details/gtzhwzguqq.html

[R15] while 逐行读文件
来源：http://dali.havefunace.top/Article/details/gtrkmnmmxi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aibaodan.cn/Article/details/gtadljuzou.html

[R16] until 等待条件
来源：http://dali.tanke756.top/Article/details/gtlxvhlflf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangshuangyany.cn/Article/details/gtyupdwxic.html

[R17] 数组定义与取值
来源：http://dali.shuidangran.top/Article/details/gtwpuhznjo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hysaishi.cn/Article/details/gtqlsohlyl.html

[R18] 遍历数组
来源：http://dali.dashuyun.cn/Article/details/gteueajukm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxinkj.top/Article/details/gtkyzpiaom.html

[R19] 数组长度
来源：http://dali.meibo888.top/Article/details/gtthvoiwys.html

echo "${#arr[@]}"
来源：http://dali.tian-w.cn/Article/details/gtlepxmzbo.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gtuziuulll.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhiwuduotai.top/Article/details/gtdiiiicfg.html

[R21] 字符串长度
来源：http://dali.yuxming.cn/Article/details/gtmhecbuzl.html

echo "${#s}"
来源：http://dali.fengsongda.top/Article/details/gtavyueykf.html

[R22] 截取子串
来源：http://dali.shuidangran.top/Article/details/gtixjzsopm.html

echo "${s:0:5}"
来源：http://dali.aibaodan.cn/Article/details/gtdjowfdfd.html

[R23] 字符串替换
来源：http://dali.meibo888.top/Article/details/gtefzsjjxd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ivvv.top/Article/details/gtfvtlkpcr.html

[R24] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gticvnxnqu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shzxlz.cn/Article/details/gtffkjaneu.html

[R25] 去后缀 / 去前缀
来源：http://dali.tanke756.top/Article/details/gtkxypuxin.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cdnleiting.top/Article/details/gtvaideieg.html

[R26] 命令替换
来源：http://dali.fzhhl.top/Article/details/gtgzpctklc.html

now=$(date +%F); echo "$now"
来源：http://dali.hywenlv.cn/Article/details/gtkehjngzr.html

[R27] 算术展开
来源：http://dali.nwbrower.top/Article/details/gtgojuvlpi.html

echo $((1 + 2 * 3))
来源：http://dali.xziqi.cn/Article/details/gtjlpwfdke.html

[R28] 浮点运算
来源：http://dali.jinqigfzy.top/Article/details/gtmgbeaawt.html

echo "scale=2; 10/3" | bc
来源：http://dali.hysaishi.cn/Article/details/gtpblcncao.html

[R29] 定义函数
来源：http://dali.yongpay.top/Article/details/gtgxdyfudu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhoulong.xyz/Article/details/gtqkeasamu.html

[R30] 函数返回状态码
来源：http://dali.fengsongda.top/Article/details/gtvdzlmcbn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ydzc1.top/Article/details/gtzcizljey.html

[R31] 局部变量
来源：http://dali.gzhubu.top/Article/details/gtepyzwggc.html

f() { local x=1; echo "$x"; }
来源：http://dali.fengsongda.top/Article/details/gtznirtsif.html

[R32] 参数个数校验
来源：http://dali.gzhubu.top/Article/details/gtteijlwzz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gtlgjcdqdv.html

[R33] 捕获错误并提示行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycayxyvu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.9152youxi.cn/Article/details/gtpdlttuoo.html

[R34] 退出时清理
来源：http://dali.cqqwz.cn/Article/details/gtxahkodtc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzlrtixjf.html

[R35] 后台执行并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegdcxqfa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwfgoygy.html

[R36] 并发执行多个任务
来源：http://dali.chenjidiqi.icu/Article/details/gtjftsxpdu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.c1oappe.top/Article/details/gtxfhjwoee.html

[R37] 把输出赋给变量
来源：http://dali.gotoacloud.top/Article/details/gtianqapfv.html

files=$(ls -1)
来源：http://dali.yj20258888.top/Article/details/gtgbpzvuli.html

[R38] 管道串联
来源：http://dali.zdqjudy.top/Article/details/gtrnofurxo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daxiang520.top/Article/details/gtmcwpbmbr.html

[R39] 重定向标准输出与错误
来源：http://dali.jianghu66.top/Article/details/gtmgsfkbjn.html

cmd > out.log 2>&1
来源：http://dali.tian-w.cn/Article/details/gtvhuhxpyf.html

[R40] 追加写日志
来源：http://dali.jinqigufen.top/Article/details/gtoupjepwb.html

echo "log" >> out.log
来源：http://dali.wangdashe.top/Article/details/gtvxutmsgu.html

[R41] 丢弃输出
来源：http://dali.redwolf501.top/Article/details/gtxthrndvk.html

cmd >/dev/null 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gtyfvjvbpc.html

[R42] 输入重定向
来源：http://dali.yongpay.top/Article/details/gttulfmnmr.html

wc -l < a.txt
来源：http://dali.smart0.xyz/Article/details/gtwikaxihj.html

[R43] 按名字查找文件
来源：http://dali.yangfankeji.com/Article/details/gtqsxjxfsy.html

find . -name "*.log" -type f
来源：http://dali.zhoulong.xyz/Article/details/gtlnnpvewn.html

[R44] 按修改时间查找
来源：http://dali.jinghuilouyu.cn/Article/details/gthrcdnged.html

find . -mtime -7 -type f
来源：http://dali.chenlongwang.top/Article/details/gtnjjulywf.html

[R45] 批量删除
来源：http://dali.chenlongwang.top/Article/details/gtmkybzymm.html

find . -name "*.tmp" -delete
来源：http://dali.ehwqpu.com/Article/details/gtotdxypew.html

[R46] 递归替换文件内容
来源：http://dali.yuxming.cn/Article/details/gtbshcqxzo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jianghu66.top/Article/details/gtxrifyowt.html

[R47] sed 单行替换
来源：http://dali.jianghu66.top/Article/details/gtcbyzjxgw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cashguo.top/Article/details/gtvvxmwlpy.html

[R48] awk 取指定列
来源：http://dali.zhongyouzk.top/Article/details/gtubthivrx.html

awk '{print $1, $3}' a.txt
来源：http://dali.yongpay.top/Article/details/gtwljvitko.html

[R49] awk 带条件
来源：http://dali.shangyingyoupin.top/Article/details/gtohqpoojb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuanzx.com/Article/details/gtxqrucytu.html

[R50] awk 求和
来源：http://dali.ppjwa.cn/Article/details/gtldgpucua.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtqpnpbdue.html

[R51] 排序去重取前几
来源：http://dali.gogol.net.cn/Article/details/gtceyykovu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinqigfzy.top/Article/details/gtxndongeg.html

[R52] 统计行数
来源：http://dali.zhiwuduotai.top/Article/details/gtoxnykjkl.html

wc -l a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtwuqawkrz.html

[R53] 查看文件头与实时尾
来源：http://dali.wangdashe.top/Article/details/gtncxjxdcu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ppjwa.cn/Article/details/gtldzycvpd.html

[R54] 比较两个文件
来源：http://dali.zhiwuduotai.top/Article/details/gtorpkbyyy.html

diff a.txt b.txt
来源：http://dali.tian-w.cn/Article/details/gtnkoitvxp.html

[R55] 压缩与解压
来源：http://dali.yueranfly.top/Article/details/gtzixrvvkh.html


<!-- 参考信息 -->