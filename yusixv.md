代发 wailian999

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhoulong.xyz/Article/details/gteczvykjr.html

[Q07] 删除表
来源：http://dali.birdmap.top/Article/details/gtndsinktb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfygcvdgo.html

[Q08] 创建普通索引
来源：http://dali.meibo888.top/Article/details/gtcfqccnzp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shangyingyoupin.top/Article/details/gtqkdcbkbj.html

[Q09] 创建唯一索引
来源：http://dali.snrcjt.cn/Article/details/gtbxegueam.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zycfv.cn/Article/details/gtxiretuer.html

[Q10] 插入单行
来源：http://dali.mhx1999.top/Article/details/gttjirgqvy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtemxndfda.html

[Q11] 一次插入多行
来源：http://dali.gogol.net.cn/Article/details/gtzbpbblxg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xziqi.cn/Article/details/gtfbwlrtie.html

[Q12] 插入后取自增 ID
来源：http://dali.yangfankeji.com/Article/details/gteiqthjrj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xinyue.icu/Article/details/gtgbrmagqo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.guannengcc.top/Article/details/gtjpkegbxg.html

[Q13] 忽略重复插入
来源：http://dali.zhoulong.xyz/Article/details/gthdaqozvw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yvedp.cn/Article/details/gtpsrpvhlu.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuanzhike.top/Article/details/gtwovnndub.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj20258.top/Article/details/gtjqgtptdi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinqigufen.top/Article/details/gteginipqk.html

[Q15] 查询全部
来源：http://dali.meibo888.top/Article/details/gtrxuyowvo.html

SELECT * FROM users;
来源：http://dali.yongpay.top/Article/details/gtkjvzqwdz.html

[Q16] 查询指定列
来源：http://dali.redwolf501.top/Article/details/gtkobvpxzm.html

SELECT id, name FROM users;
来源：http://dali.zycfv.cn/Article/details/gtkbtvzwlo.html

[Q17] 条件查询
来源：http://dali.wangdashe.top/Article/details/gthpncnfdl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hfpthk.cn/Article/details/gtrgimarmh.html

[Q18] 模糊匹配
来源：http://dali.meibo888.top/Article/details/gtemfumqhn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yanxiufei.cn/Article/details/gtgmjstlan.html

[Q19] 范围查询
来源：http://dali.cucudq.cn/Article/details/gtjdmszekz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhengqikj.top/Article/details/gtzfxlyglr.html

[Q20] IN 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteoxpqzqq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hywenlv.cn/Article/details/gtuwlpriua.html

[Q21] 空值判断
来源：http://dali.andypj.xyz/Article/details/gttdjtwekw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.316326.xyz/Article/details/gtlplwhmoa.html

[Q22] 排序
来源：http://dali.vqdsnc.cn/Article/details/gttykaxfwo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sweek.top/Article/details/gtxdetblkx.html

[Q23] 分页
来源：http://dali.gotoacloud.top/Article/details/gtheifodni.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tian-w.cn/Article/details/gtszywyiqq.html

[Q24] 去重
来源：http://dali.ydzc1.top/Article/details/gtleakgraz.html

SELECT DISTINCT city FROM users;
来源：http://dali.c1oappe.top/Article/details/gtwvzpsntt.html

[Q25] 只取前 N 条
来源：http://dali.zhoulong.xyz/Article/details/gtcepojofg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tianlin.xyz/Article/details/gtpfomywhf.html

[Q26] 计数
来源：http://dali.nanxuanxn.top/Article/details/gteibmflrd.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtubdlxend.html

[Q27] 条件计数
来源：http://dali.mhx1999.top/Article/details/gtphsmlarx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtxwwwvxnm.html

[Q28] 求和与平均
来源：http://dali.shzxlz.cn/Article/details/gtiyavjpsa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtsikquafk.html

[Q29] 最大最小值
来源：http://dali.c1oappe.top/Article/details/gtmwhtjynn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hammf.cn/Article/details/gtwgxoaeha.html

[Q30] 分组统计
来源：http://dali.daria6918.cn/Article/details/gtdngxqdzn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gtmqwnympo.html

[Q31] 分组后过滤
来源：http://dali.ehwqpu.com/Article/details/gtzvfhbdml.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhoulong.xyz/Article/details/gtzyhsuplb.html

[Q32] 分组拼接字符串
来源：http://dali.yueranfly.top/Article/details/gtxqpxnaoy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyryleulh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ivvv.top/Article/details/gtxgtwomfa.html

[Q33] 多列分组
来源：http://dali.snrcjt.cn/Article/details/gtmyunbmmi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.meibo888.top/Article/details/gtcuatftvr.html

[Q34] 每组取第一条
来源：http://dali.wangshuangyany.cn/Article/details/gtqhyxtuzb.html

SELECT * FROM (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsoeeqayf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xinyue.icu/Article/details/gtjqieefzs.html

) t WHERE rn = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtsfzfxtta.html

[Q35] 内连接
来源：http://dali.andypj.xyz/Article/details/gtwujfujwh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gttetpdpkk.html

[Q36] 左连接
来源：http://dali.hfpthk.cn/Article/details/gtcmidxwkp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtoofecszz.html

[Q37] 右连接
来源：http://dali.sufxvd.cn/Article/details/gtekmqzyzt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkapjexxv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj20258.top/Article/details/gtexhbvvje.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.aizwys.cn/Article/details/gtfytvyldb.html

[Q39] 自连接（查上下级）
来源：http://dali.ehwqpu.com/Article/details/gtoturdlaj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.bjfxy.top/Article/details/gthtiloawb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.andypj.xyz/Article/details/gttyafeank.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.fzhhl.top/Article/details/gtfhsspaqz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yuxming.cn/Article/details/gtpndbcqwh.html

[Q41] 多表连接
来源：http://dali.tianlin.xyz/Article/details/gtqvrppgwk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjcxopwg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.316326.xyz/Article/details/gtpquzfkep.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xinyue.icu/Article/details/gtgfvrteun.html

[Q42] 连接条件附加过滤
来源：http://dali.sxryk.cn/Article/details/gtjbadsxih.html

SELECT u.name, o.amount FROM users u
来源：http://dali.guowangkeji.top/Article/details/gtlxwjdqko.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.wangshuangyany.cn/Article/details/gtuzfotcxg.html

[Q43] 标量子查询
来源：http://dali.jinqigufen.top/Article/details/gtnaywlvrw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgfzy.top/Article/details/gtbjztadcw.html

[Q44] IN 子查询
来源：http://dali.fengsongda.top/Article/details/gtzhhvujhw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shangyingyoupin.top/Article/details/gttzggoita.html

[Q45] EXISTS 判断存在
来源：http://dali.hywenlv.cn/Article/details/gtubyvwari.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigufen.top/Article/details/gtnicvehcg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sufxvd.cn/Article/details/gtlantyttz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.svipenyu.cn/Article/details/gtzqangsov.html

[Q47] 与平均值比较
来源：http://dali.zhiwuduotai.top/Article/details/gttplmvjzl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhongyouzk.top/Article/details/gtryrwbjkn.html

[Q48] CTE 公用表表达式
来源：http://dali.ybcxt.top/Article/details/gtlrkupqmg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sxryk.cn/Article/details/gtfciljshv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hongshengwenyu.top/Article/details/gtzyzugudx.html

[Q49] 更新单行
来源：http://dali.quarkkingdee.top/Article/details/gtygnzkuhc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtptktgymv.html

[Q50] 批量更新
来源：http://dali.hfpthk.cn/Article/details/gtqyrxnizf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.feifeiyinyue.top/Article/details/gtwhscifsy.html

[Q51] 用子查询更新
来源：http://dali.yueranfly.top/Article/details/gtjfhcpvhh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenzaomai.com/Article/details/gtivopntht.html

[Q52] 删除指定行
来源：http://dali.c1oappe.top/Article/details/gtkoplvbts.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzikcckz.html

[Q53] 按条件删除
来源：http://dali.yj20258888.top/Article/details/gtoqtzkmjl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.bjfxy.top/Article/details/gtgmgjhjbx.html

[Q54] 清空表
来源：http://dali.yanxiufei.cn/Article/details/gthuxzlswf.html

TRUNCATE TABLE logs;
来源：http://dali.zhengqikj.top/Article/details/gtdolfupgr.html

[Q55] 排名（并列占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetcnsdvz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhoulong.xyz/Article/details/gtsvenhfpf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj20258.top/Article/details/gtappjtntg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xylfe.cn/Article/details/gtbydegpzu.html

[Q57] 行号
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqjjkgqb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtqlwxytbj.html

[Q58] 累计求和
来源：http://dali.c1oappe.top/Article/details/gtdrgzxjdx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtswwbdytk.html

[Q59] 分组内累计
来源：http://dali.tanke756.top/Article/details/gtcicipqsk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtrupxwkvi.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gtkmwkprzk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ybcxt.top/Article/details/gtjfbglowj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtqxtktshg.html

[Q61] 移动平均
来源：http://dali.zycfv.cn/Article/details/gtouuctjof.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtstxcbbwq.html

[Q62] 分组占比
来源：http://dali.yueranfly.top/Article/details/gtsrtsafgg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gtjwwckjeg.html

[Q63] 开启事务
来源：http://dali.cheryme.top/Article/details/gtpqiuapqe.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.mhx1999.top/Article/details/gtvwmntshv.html

[Q64] 提交事务
来源：http://dali.andypj.xyz/Article/details/gtphedxgtp.html

COMMIT;
来源：http://dali.smart0.xyz/Article/details/gtajsyloga.html

[Q65] 回滚事务
来源：http://dali.feifeiyinyue.top/Article/details/gtflhduukf.html

ROLLBACK;
来源：http://dali.guowangkeji.top/Article/details/gtfcxisybh.html

[Q66] 行锁查询
来源：http://dali.tianlin.xyz/Article/details/gtirxmmwsv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.pengpengdd.cyou/Article/details/gtkfmckuii.html

[Q67] 设置隔离级别
来源：http://dali.jinqigfzy.top/Article/details/gtpcmnomgj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sysykeji.top/Article/details/gttagwiowv.html

[Q68] 保存点
来源：http://dali.yuanzhike.top/Article/details/gtffrupfqn.html

SAVEPOINT sp1;
来源：http://dali.yj20258.top/Article/details/gtjnulpnxm.html

ROLLBACK TO sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzlunaqq.html

[Q69] 查看执行计划
来源：http://dali.sufxvd.cn/Article/details/gtwlwnvutb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gaohongyu789.top/Article/details/gtiteiksgs.html

[Q70] 更新统计信息
来源：http://dali.dianchejie.cn/Article/details/gttglurqbz.html

ANALYZE TABLE users;
来源：http://dali.fzhhl.top/Article/details/gtbntvoitx.html

[Q71] 查看建表语句
来源：http://dali.yj20258888.top/Article/details/gtgxubhnwa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.mhx1999.top/Article/details/gtllbghkcr.html

[Q72] 查看索引
来源：http://dali.aibaodan.cn/Article/details/gtjvanassr.html

SHOW INDEX FROM users;
来源：http://dali.cashguo.top/Article/details/gtphpkmrsn.html

[Q73] 查看表状态
来源：http://dali.tanke756.top/Article/details/gtbmemyucw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nanxinkj.top/Article/details/gtndnvvhvi.html

[Q74] 强制使用索引
来源：http://dali.yvedp.cn/Article/details/gtstnhsays.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gzhubu.top/Article/details/gtchysshin.html

[Q75] 日期格式化
来源：http://dali.tian-w.cn/Article/details/gttcwvbewr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtnznzwxxw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tanke756.top/Article/details/gtkuietjxr.html

[Q76] 按天统计
来源：http://dali.ydzc1.top/Article/details/gtosptrasz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daxiang520.top/Article/details/gtbiqnvzkk.html

[Q77] 时间加减
来源：http://dali.yj20258888.top/Article/details/gtghdmzukq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shzxlz.cn/Article/details/gtyhwyepnt.html

[Q78] 当前时间
来源：http://dali.redwolf501.top/Article/details/gtkssbbvih.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cqqwz.cn/Article/details/gtqtehtrta.html

[Q79] 字符串拼接
来源：http://dali.gogol.net.cn/Article/details/gteajdteyr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.wangdashe.top/Article/details/gtmqcxrzrp.html

[Q80] 字符串截取
来源：http://dali.meibo888.top/Article/details/gtkwlaljyj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtocbcrcnq.html

[Q81] 字符串替换
来源：http://dali.feifeiyinyue.top/Article/details/gttejobwxw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yueranfly.top/Article/details/gtmdnlxigj.html

[Q82] 字符长度与字节长度
来源：http://dali.nanxinkj.top/Article/details/gtdezhxnkb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gthxwkuhoq.html

[Q83] 大小写转换
来源：http://dali.hammf.cn/Article/details/gtmppibhgk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtcorwqzzj.html

[Q84] 去除首尾空格
来源：http://dali.dianchejie.cn/Article/details/gtbehlwvar.html

SELECT TRIM(name) FROM users;
来源：http://dali.sweek.top/Article/details/gtrinpaoun.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gtilfkmlsz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj202588.top/Article/details/gtmwnbyiox.html

[Q86] 读取 JSON 字段
来源：http://dali.wangdashe.top/Article/details/gtybyngsci.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hnxiangtu.top/Article/details/gtzxijfops.html

[Q87] JSON 字段做条件
来源：http://dali.316326.xyz/Article/details/gtexwrbfoi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.iojbl.cn/Article/details/gtoviatrch.html

[Q88] 行转列（条件聚合）
来源：http://dali.cdnleiting.top/Article/details/gthvzneqvr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258888.top/Article/details/gtkahgigey.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.havefunace.top/Article/details/gtotidwgny.html

[Q89] 判断表是否存在
来源：http://dali.daxiang520.top/Article/details/gtxbckkyrw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yonumen.top/Article/details/gttgxsiizc.html

[Q90] 生成序号列
来源：http://dali.yongpay.top/Article/details/gtmfwxidoe.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hywenlv.cn/Article/details/gteuoundcz.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtackawihv.html

R. Bash 专题
来源：http://dali.pycfn.com/Article/details/gtmrrutwoy.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gticztttgo.html

[R01] shebang 与严格模式
来源：http://dali.0kj1m.cn/Article/details/gtrvbrdvhs.html

#!/usr/bin/env bash
来源：http://dali.nanxinkj.top/Article/details/gtxvugavyz.html

set -euo pipefail
来源：http://dali.snrcjt.cn/Article/details/gtictneaif.html

[R02] 变量赋值与使用
来源：http://dali.zdqjudy.top/Article/details/gtdathvtyn.html

name="Tom"; echo "$name"
来源：http://dali.nanxuanxn.top/Article/details/gtjcegdojw.html

[R03] 只读变量
来源：http://dali.hongshengwenyu.top/Article/details/gtekaywstv.html

readonly PI=3.14
来源：http://dali.pengpengdd.cyou/Article/details/gtssryjqlq.html

[R04] 位置参数
来源：http://dali.jiagoushi.top/Article/details/gtbkqocfaj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shzxlz.cn/Article/details/gtaubbpmmc.html

[R05] 参数默认值
来源：http://dali.jinghuilouyu.cn/Article/details/gtdtemmtjl.html

name="${1:-default}"
来源：http://dali.xylfe.cn/Article/details/gtgwraxrvo.html

[R06] 判断命令是否存在
来源：http://dali.jqgfzy.top/Article/details/gtdxqhzjgq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.guannengcc.top/Article/details/gthcqxgznw.html

[R07] if 判断文件
来源：http://dali.xuetiantiany.cn/Article/details/gtbujxywwf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.dianchejie.cn/Article/details/gtemxwflur.html

[R08] 数值比较
来源：http://dali.iojbl.cn/Article/details/gtmglifpnn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tian-w.cn/Article/details/gtguvpjjqe.html

[R09] 字符串比较
来源：http://dali.yj20258.top/Article/details/gtqdpratfr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cashguo.top/Article/details/gtucvufzax.html

[R10] 正则匹配
来源：http://dali.gotoacloud.top/Article/details/gtdhudurou.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tanke756.top/Article/details/gtbahdouob.html

[R11] case 多分支
来源：http://dali.yuxming.cn/Article/details/gtxzkswwfu.html

case "$1" in
来源：http://dali.cheryme.top/Article/details/gtpxigravy.html

start) echo "启动" ;;
来源：http://dali.nwbrower.top/Article/details/gttxwyotxf.html

stop)  echo "停止" ;;
来源：http://dali.yj202588.top/Article/details/gttqksenbm.html

*)     echo "未知命令" ;;
来源：http://dali.chenzaomai.com/Article/details/gtepjgqtku.html

esac
来源：http://dali.yangfankeji.com/Article/details/gtftgrihjk.html

[R12] for 遍历文件
来源：http://dali.aibaodan.cn/Article/details/gtsjdjofiv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jqgfzy.top/Article/details/gtmteskilj.html

[R13] for 计数循环
来源：http://dali.sufxvd.cn/Article/details/gtceldbuic.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.smart0.xyz/Article/details/gtdkkkoixh.html

[R14] C 风格 for
来源：http://dali.sweek.top/Article/details/gthuktltum.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gtcfcqvdnb.html

[R15] while 逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtzyvrjaix.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangdashe.top/Article/details/gtlwncfxlh.html

[R16] until 等待条件
来源：http://dali.aizwys.cn/Article/details/gtponghcvx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gtctdfwrzj.html

[R17] 数组定义与取值
来源：http://dali.wangdashe.top/Article/details/gtobvrarza.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cheryme.top/Article/details/gtanlzvagr.html

[R18] 遍历数组
来源：http://dali.shuidangran.top/Article/details/gtkmdummni.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.mhx1999.top/Article/details/gtikadxvrb.html

[R19] 数组长度
来源：http://dali.smart0.xyz/Article/details/gtytnrmdfx.html

echo "${#arr[@]}"
来源：http://dali.daria6918.cn/Article/details/gtprjibdsu.html

[R20] 关联数组（字典）
来源：http://dali.jyoumei.cn/Article/details/gtfqkknmds.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj202588.top/Article/details/gtmvamzipi.html

[R21] 字符串长度
来源：http://dali.shangyingyoupin.top/Article/details/gtcipvdaut.html

echo "${#s}"
来源：http://dali.hammf.cn/Article/details/gtmvmzepas.html

[R22] 截取子串
来源：http://dali.zhoulong.xyz/Article/details/gtvlmqjjbq.html

echo "${s:0:5}"
来源：http://dali.cheryme.top/Article/details/gtzjxhjinz.html

[R23] 字符串替换
来源：http://dali.xylfe.cn/Article/details/gtqpoueuio.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.c1oappe.top/Article/details/gtufzpawto.html

[R24] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gtsfhjunab.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hongshengwenyu.top/Article/details/gtzwtbcnwa.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhongyouzk.top/Article/details/gtwaflznqx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ivvv.top/Article/details/gtvqtnwmbu.html

[R26] 命令替换
来源：http://dali.ehwqpu.com/Article/details/gtzvpxowme.html

now=$(date +%F); echo "$now"
来源：http://dali.sweek.top/Article/details/gtwplwaahj.html

[R27] 算术展开
来源：http://dali.jiagoushi.top/Article/details/gtxozcuxft.html

echo $((1 + 2 * 3))
来源：http://dali.zycfv.cn/Article/details/gthyfkhvcf.html

[R28] 浮点运算
来源：http://dali.tianlin.xyz/Article/details/gtzaapuohl.html

echo "scale=2; 10/3" | bc
来源：http://dali.jqgfzy.top/Article/details/gtsybfwglk.html

[R29] 定义函数
来源：http://dali.tanke756.top/Article/details/gtubgewbmp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shzxlz.cn/Article/details/gterrfcepl.html

[R30] 函数返回状态码
来源：http://dali.shuidangran.top/Article/details/gtmmiktjei.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jlsjyb.cn/Article/details/gtcgffprxe.html

[R31] 局部变量
来源：http://dali.c1oappe.top/Article/details/gtincankll.html

f() { local x=1; echo "$x"; }
来源：http://dali.yongpay.top/Article/details/gtjrmlljtt.html

[R32] 参数个数校验
来源：http://dali.gaohongyu789.top/Article/details/gtbfstuhyp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hongshengwenyu.top/Article/details/gtonutxrsn.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gtbvpatgvz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.andypj.xyz/Article/details/gttjscrifn.html

[R34] 退出时清理
来源：http://dali.meibo888.top/Article/details/gtmjhcwgty.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gtvnvirsyp.html

[R35] 后台执行并等待
来源：http://dali.gzhubu.top/Article/details/gtbnaynmpz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tian-w.cn/Article/details/gtfxddippt.html

[R36] 并发执行多个任务
来源：http://dali.jqgufenzy.top/Article/details/gtkypjjvde.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ydzc1.top/Article/details/gtmrkyfxhe.html

[R37] 把输出赋给变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqcdjvcon.html

files=$(ls -1)
来源：http://dali.cashguo.top/Article/details/gtkdgqdxxd.html

[R38] 管道串联
来源：http://dali.yuanzhike.top/Article/details/gtgiptklfq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.aizwys.cn/Article/details/gterqnoumc.html

[R39] 重定向标准输出与错误
来源：http://dali.shuidangran.top/Article/details/gtivgiggrh.html

cmd > out.log 2>&1
来源：http://dali.yueranfly.top/Article/details/gttlivabpv.html

[R40] 追加写日志
来源：http://dali.yanxiufei.cn/Article/details/gtmuavmvqe.html

echo "log" >> out.log
来源：http://dali.hfpthk.cn/Article/details/gtzowhueyu.html

[R41] 丢弃输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxcwohwnr.html

cmd >/dev/null 2>&1
来源：http://dali.mhx1999.top/Article/details/gtanfyoqge.html

[R42] 输入重定向
来源：http://dali.yonumen.top/Article/details/gtdpjnwduq.html

wc -l < a.txt
来源：http://dali.snrcjt.cn/Article/details/gttrnqfvkt.html

[R43] 按名字查找文件
来源：http://dali.zhiwuduotai.top/Article/details/gtnyzcqzxj.html

find . -name "*.log" -type f
来源：http://dali.feifeiyinyue.top/Article/details/gtyjaynxql.html

[R44] 按修改时间查找
来源：http://dali.yanxiufei.cn/Article/details/gtzcvvxtld.html

find . -mtime -7 -type f
来源：http://dali.zhongyouzk.top/Article/details/gtbtdelubf.html

[R45] 批量删除
来源：http://dali.ydzc1.top/Article/details/gtsugzasyr.html

find . -name "*.tmp" -delete
来源：http://dali.mhx1999.top/Article/details/gtdjtwtbpa.html

[R46] 递归替换文件内容
来源：http://dali.yvedp.cn/Article/details/gtymyvwlcw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.vqdsnc.cn/Article/details/gtdmhejjpj.html

[R47] sed 单行替换
来源：http://dali.ybcxt.top/Article/details/gtdymsitec.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tanke756.top/Article/details/gtysfrqwrs.html

[R48] awk 取指定列
来源：http://dali.nwbrower.top/Article/details/gtgfjnlcrq.html

awk '{print $1, $3}' a.txt
来源：http://dali.ehwqpu.com/Article/details/gtfhvjhaqh.html

[R49] awk 带条件
来源：http://dali.wangshuangyany.cn/Article/details/gtblgofjos.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cqqwz.cn/Article/details/gtpjciiqae.html

[R50] awk 求和
来源：http://dali.daxiang520.top/Article/details/gthtemdzjr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gzhubu.top/Article/details/gtngncihfe.html

[R51] 排序去重取前几
来源：http://dali.yvedp.cn/Article/details/gtwgkcqnid.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xziqi.cn/Article/details/gtgoxxelmg.html

[R52] 统计行数
来源：http://dali.aibaodan.cn/Article/details/gttnyicsty.html

wc -l a.txt
来源：http://dali.daria6918.cn/Article/details/gtezoohffj.html

[R53] 查看文件头与实时尾
来源：http://dali.zycfv.cn/Article/details/gtilsscrga.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hysaishi.cn/Article/details/gtayaxjqme.html

[R54] 比较两个文件
来源：http://dali.jlsjyb.cn/Article/details/gtjmdmhuba.html

diff a.txt b.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtanhhmogd.html

[R55] 压缩与解压
来源：http://dali.tianlin.xyz/Article/details/gttpumkvjo.html


<!-- 参考信息 -->