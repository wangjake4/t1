代发 wailian999

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinqigufen.top/Article/details/gtkzqlbwgt.html

[Q11] 一次插入多行
来源：http://dali.yj20258.top/Article/details/gtcrbdsyrt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gtsyvgizfc.html

[Q12] 插入后取自增 ID
来源：http://dali.zhixingplan.top/Article/details/gtuttnfoln.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hammf.cn/Article/details/gtozrumvnb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cheryme.top/Article/details/gtgblozmvm.html

[Q13] 忽略重复插入
来源：http://dali.sufxvd.cn/Article/details/gtskfohtym.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.aizwys.cn/Article/details/gtjcymfwun.html

[Q14] 存在则更新（upsert）
来源：http://dali.kuanghao11.cn/Article/details/gthamyaean.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.meibo888.top/Article/details/gttjgbmoyk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yongpay.top/Article/details/gtzlyxuoib.html

[Q15] 查询全部
来源：http://dali.aibaodan.cn/Article/details/gtmyalmsas.html

SELECT * FROM users;
来源：http://dali.aizwys.cn/Article/details/gtgjvujncn.html

[Q16] 查询指定列
来源：http://dali.jqgufenzy.top/Article/details/gtjzchsqom.html

SELECT id, name FROM users;
来源：http://dali.tanke756.top/Article/details/gtsspxorzs.html

[Q17] 条件查询
来源：http://dali.tian-w.cn/Article/details/gtninkopwf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtxfhpgkcy.html

[Q18] 模糊匹配
来源：http://dali.cqqwz.cn/Article/details/gtmdshcwgi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhiwuduotai.top/Article/details/gtvtgunptm.html

[Q19] 范围查询
来源：http://dali.chenlongwang.top/Article/details/gtotynjzco.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hfpthk.cn/Article/details/gtujieeeql.html

[Q20] IN 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikowihoe.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.daria6918.cn/Article/details/gtdscoeyak.html

[Q21] 空值判断
来源：http://dali.svipenyu.cn/Article/details/gtcvfzwuvh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gtxggrlgzz.html

[Q22] 排序
来源：http://dali.cashguo.top/Article/details/gthwtzjtbv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.dianchejie.cn/Article/details/gthmklnnay.html

[Q23] 分页
来源：http://dali.cashguo.top/Article/details/gtshheewab.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhixingplan.top/Article/details/gtmtwqofhg.html

[Q24] 去重
来源：http://dali.nwbrower.top/Article/details/gtyvarlccs.html

SELECT DISTINCT city FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtcyhymkkm.html

[Q25] 只取前 N 条
来源：http://dali.bjfxy.top/Article/details/gttznsisbr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nanxinkj.top/Article/details/gtiwsrfkkx.html

[Q26] 计数
来源：http://dali.zhixingplan.top/Article/details/gtmjixepnq.html

SELECT COUNT(*) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtetobzlva.html

[Q27] 条件计数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoeahqage.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yonumen.top/Article/details/gtqtqywqml.html

[Q28] 求和与平均
来源：http://dali.hongshengwenyu.top/Article/details/gtmmyiplcj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtzqugygkl.html

[Q29] 最大最小值
来源：http://dali.zycfv.cn/Article/details/gtblsyqshb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtxvrlvips.html

[Q30] 分组统计
来源：http://dali.aizwys.cn/Article/details/gtklipqdqe.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtnmeivyol.html

[Q31] 分组后过滤
来源：http://dali.cdnleiting.top/Article/details/gtdmyvbstd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.mhx1999.top/Article/details/gtwflfvrpi.html

[Q32] 分组拼接字符串
来源：http://dali.shuidangran.top/Article/details/gtpiiqcbww.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gthhoigbdi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ivvv.top/Article/details/gthnojjddo.html

[Q33] 多列分组
来源：http://dali.pengpengdd.cyou/Article/details/gtujnwpcnz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.andypj.xyz/Article/details/gtxjrybasf.html

[Q34] 每组取第一条
来源：http://dali.chenzaomai.com/Article/details/gtlgcaiztu.html

SELECT * FROM (
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcvaopoj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fengsongda.top/Article/details/gtxepqnuvo.html

) t WHERE rn = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtpngeenrl.html

[Q35] 内连接
来源：http://dali.tianlin.xyz/Article/details/gtlxzozzar.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gteeyjsezq.html

[Q36] 左连接
来源：http://dali.ppjwa.cn/Article/details/gtkoywfkkk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj202588.top/Article/details/gtraxcyhtl.html

[Q37] 右连接
来源：http://dali.daxiang520.top/Article/details/gtfdkykeqy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cdnleiting.top/Article/details/gtvcsyfmpw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenjidiqi.icu/Article/details/gtrnmssclf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hnxiangtu.top/Article/details/gtqilbkbcc.html

[Q39] 自连接（查上下级）
来源：http://dali.316326.xyz/Article/details/gtzcsrfktt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnqzz.top/Article/details/gtapzetxce.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.quarkkingdee.top/Article/details/gtpmmkkadx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nanxinkj.top/Article/details/gtxbxqxnjq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cqqwz.cn/Article/details/gtmpqjctrk.html

[Q41] 多表连接
来源：http://dali.shzxlz.cn/Article/details/gtyzbrehhu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yongpay.top/Article/details/gtpohrsikk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gzhubu.top/Article/details/gtljmcsypr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhixingplan.top/Article/details/gtcxttxrpg.html

[Q42] 连接条件附加过滤
来源：http://dali.svipenyu.cn/Article/details/gtmghglwfr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigfzy.top/Article/details/gttuuisjuj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fengsongda.top/Article/details/gtxbdxvgum.html

[Q43] 标量子查询
来源：http://dali.jiagoushi.top/Article/details/gtbezsaaol.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhixingplan.top/Article/details/gtyvekpxka.html

[Q44] IN 子查询
来源：http://dali.nanxinkj.top/Article/details/gtnibbjpey.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hysaishi.cn/Article/details/gtnjuyctde.html

[Q45] EXISTS 判断存在
来源：http://dali.cqqwz.cn/Article/details/gtnizpghwe.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gtalohgaqe.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.daria6918.cn/Article/details/gtncyidodj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yueranfly.top/Article/details/gtbqybwwwu.html

[Q47] 与平均值比较
来源：http://dali.jinqigufen.top/Article/details/gtbaifjjml.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutegdhbu.html

[Q48] CTE 公用表表达式
来源：http://dali.fengsongda.top/Article/details/gtggfubave.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.meibo888.top/Article/details/gtwezhmcki.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xinyue.icu/Article/details/gtzeigbxha.html

[Q49] 更新单行
来源：http://dali.chenzaomai.com/Article/details/gtltpstbgf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpzdrtil.html

[Q50] 批量更新
来源：http://dali.tian-w.cn/Article/details/gtdcytfbuf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tianlin.xyz/Article/details/gtmtqndbtt.html

[Q51] 用子查询更新
来源：http://dali.redwolf501.top/Article/details/gtlnomsxfc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ppjwa.cn/Article/details/gtqzpvjsps.html

[Q52] 删除指定行
来源：http://dali.ppjwa.cn/Article/details/gteupcgfem.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ehwqpu.com/Article/details/gtbiyrcffo.html

[Q53] 按条件删除
来源：http://dali.jinqigfzy.top/Article/details/gtkyxcvlyu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlxoovzy.html

[Q54] 清空表
来源：http://dali.kuanghao11.cn/Article/details/gtzqstqbny.html

TRUNCATE TABLE logs;
来源：http://dali.iojbl.cn/Article/details/gtjwvfeowr.html

[Q55] 排名（并列占位）
来源：http://dali.cqqwz.cn/Article/details/gtvfbdfhiq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hongshengwenyu.top/Article/details/gtrhhdwsnz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuanzx.com/Article/details/gtfhsvawul.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenlongwang.top/Article/details/gteskzdiil.html

[Q57] 行号
来源：http://dali.sufxvd.cn/Article/details/gtiekaygnl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtteoonrob.html

[Q58] 累计求和
来源：http://dali.nwbrower.top/Article/details/gtncwzqwwv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.birdmap.top/Article/details/gtrwvdoudm.html

[Q59] 分组内累计
来源：http://dali.cdnleiting.top/Article/details/gtnwpktbls.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzcqllahs.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhoulong.xyz/Article/details/gtqhtysscr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shuidangran.top/Article/details/gtluszliep.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtpazmyzmg.html

[Q61] 移动平均
来源：http://dali.daxiang520.top/Article/details/gtiayiacuj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gthayknumz.html

[Q62] 分组占比
来源：http://dali.andypj.xyz/Article/details/gtegzsivel.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjnwbyih.html

[Q63] 开启事务
来源：http://dali.shangyingyoupin.top/Article/details/gtafrqnpcl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shzxlz.cn/Article/details/gtadffykyg.html

[Q64] 提交事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsynyzcdc.html

COMMIT;
来源：http://dali.guowangkeji.top/Article/details/gtgaqtzclp.html

[Q65] 回滚事务
来源：http://dali.cucudq.cn/Article/details/gtfentklta.html

ROLLBACK;
来源：http://dali.gogol.net.cn/Article/details/gtoonwyvdg.html

[Q66] 行锁查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzoxzjtqb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.svipenyu.cn/Article/details/gtlsfpapvv.html

[Q67] 设置隔离级别
来源：http://dali.jinqigfzy.top/Article/details/gtevlusits.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yonumen.top/Article/details/gtshxgpxnu.html

[Q68] 保存点
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwbbhlnlf.html

SAVEPOINT sp1;
来源：http://dali.pengpengdd.cyou/Article/details/gtucglbocf.html

ROLLBACK TO sp1;
来源：http://dali.pycfn.com/Article/details/gtwqlmczie.html

[Q69] 查看执行计划
来源：http://dali.ehwqpu.com/Article/details/gtnwqfidjf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.dianchejie.cn/Article/details/gtrzijrboc.html

[Q70] 更新统计信息
来源：http://dali.gotoacloud.top/Article/details/gtutmxhluh.html

ANALYZE TABLE users;
来源：http://dali.xuanzx.com/Article/details/gtvuuirkkd.html

[Q71] 查看建表语句
来源：http://dali.guannengcc.top/Article/details/gtmaimkwrj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.haohaochexian.top/Article/details/gtmdxbbcol.html

[Q72] 查看索引
来源：http://dali.chenjidiqi.icu/Article/details/gtfwguldyb.html

SHOW INDEX FROM users;
来源：http://dali.sweek.top/Article/details/gtuyalqcum.html

[Q73] 查看表状态
来源：http://dali.xuanzx.com/Article/details/gtbpwfuaun.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangdashe.top/Article/details/gtysqzrasj.html

[Q74] 强制使用索引
来源：http://dali.cucudq.cn/Article/details/gtdivrblik.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.andypj.xyz/Article/details/gtpphcbvni.html

[Q75] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gtypftxpxt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtzfjrvcru.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.fzhhl.top/Article/details/gtmagokakl.html

[Q76] 按天统计
来源：http://dali.xylfe.cn/Article/details/gtzfenwfzj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gaohongyu789.top/Article/details/gtphbfavir.html

[Q77] 时间加减
来源：http://dali.cucudq.cn/Article/details/gtbnssqklb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hysaishi.cn/Article/details/gtoapoldgr.html

[Q78] 当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpvmquqf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cheryme.top/Article/details/gtbpufsyei.html

[Q79] 字符串拼接
来源：http://dali.cqqwz.cn/Article/details/gtybmcqyec.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.svipenyu.cn/Article/details/gtvrnliqco.html

[Q80] 字符串截取
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljckhnqf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtsgnkxjcx.html

[Q81] 字符串替换
来源：http://dali.birdmap.top/Article/details/gtczyqxdoa.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.smart0.xyz/Article/details/gtyknittxr.html

[Q82] 字符长度与字节长度
来源：http://dali.jlsjyb.cn/Article/details/gtousnxoqx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gttoxxrred.html

[Q83] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gtczihpcda.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtkdesjgod.html

[Q84] 去除首尾空格
来源：http://dali.xuetiantiany.cn/Article/details/gtlanpllsx.html

SELECT TRIM(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gttvkhnpvt.html

[Q85] 数值取整
来源：http://dali.hnxiangtu.top/Article/details/gttyjjjhhi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.snrcjt.cn/Article/details/gtqdmlilav.html

[Q86] 读取 JSON 字段
来源：http://dali.cashguo.top/Article/details/gtvitalsvr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ydzc1.top/Article/details/gtuqopiuue.html

[Q87] JSON 字段做条件
来源：http://dali.shuidangran.top/Article/details/gtytkjkmlg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ybcxt.top/Article/details/gtgywuzkhr.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqsxaazj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258888.top/Article/details/gtohnvtveq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtghrsqeia.html

[Q89] 判断表是否存在
来源：http://dali.ppjwa.cn/Article/details/gtzscasrww.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenjidiqi.icu/Article/details/gtbkbevzmw.html

[Q90] 生成序号列
来源：http://dali.tanke756.top/Article/details/gtflgimndb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zycfv.cn/Article/details/gtkhxprdwd.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtdnxdwbok.html

R. Bash 专题
来源：http://dali.xuetiantiany.cn/Article/details/gtfccvfttt.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtqlabrdxm.html

[R01] shebang 与严格模式
来源：http://dali.bjfxy.top/Article/details/gtdjizrdkh.html

#!/usr/bin/env bash
来源：http://dali.daxiang520.top/Article/details/gtmkxnixzq.html

set -euo pipefail
来源：http://dali.meibo888.top/Article/details/gtspkhlyjv.html

[R02] 变量赋值与使用
来源：http://dali.jqgfzy.top/Article/details/gtpflgwljg.html

name="Tom"; echo "$name"
来源：http://dali.yanxiufei.cn/Article/details/gtkwwfceoe.html

[R03] 只读变量
来源：http://dali.hywenlv.cn/Article/details/gtxrugewcy.html

readonly PI=3.14
来源：http://dali.jqgfzy.top/Article/details/gtpxyhvdqq.html

[R04] 位置参数
来源：http://dali.jinqigfzy.top/Article/details/gtjshdfrfb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tianlin.xyz/Article/details/gtwmgoacqm.html

[R05] 参数默认值
来源：http://dali.jqgfzy.top/Article/details/gtuxinpghe.html

name="${1:-default}"
来源：http://dali.aibaodan.cn/Article/details/gtgcthepyv.html

[R06] 判断命令是否存在
来源：http://dali.cdnleiting.top/Article/details/gtzsmqttcg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gtcrphaeig.html

[R07] if 判断文件
来源：http://dali.nanxinkj.top/Article/details/gtootlhbup.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sufxvd.cn/Article/details/gtichyurkl.html

[R08] 数值比较
来源：http://dali.tanke756.top/Article/details/gtosopktww.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.pycfn.com/Article/details/gthkniqcqg.html

[R09] 字符串比较
来源：http://dali.hammf.cn/Article/details/gtczzdwxce.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.wangdashe.top/Article/details/gtmsidusyl.html

[R10] 正则匹配
来源：http://dali.dashuyun.cn/Article/details/gticepglma.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yangfankeji.com/Article/details/gtbooykois.html

[R11] case 多分支
来源：http://dali.tian-w.cn/Article/details/gtwvgprfmi.html

case "$1" in
来源：http://dali.yueranfly.top/Article/details/gtavbiajmz.html

start) echo "启动" ;;
来源：http://dali.fengsongda.top/Article/details/gtyioxtrtf.html

stop)  echo "停止" ;;
来源：http://dali.tianlin.xyz/Article/details/gtroklvziz.html

*)     echo "未知命令" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtorckrdev.html

esac
来源：http://dali.yangfankeji.com/Article/details/gtwdywpefb.html

[R12] for 遍历文件
来源：http://dali.yanxiufei.cn/Article/details/gtaaixxqob.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxinkj.top/Article/details/gtquciayij.html

[R13] for 计数循环
来源：http://dali.guannengcc.top/Article/details/gtyhnlnixp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gtzvkrmuyk.html

[R14] C 风格 for
来源：http://dali.xziqi.cn/Article/details/gtkakwttlh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gtturuxuyo.html

[R15] while 逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtboayvxsu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigfzy.top/Article/details/gtgtvfbkpm.html

[R16] until 等待条件
来源：http://dali.guannengcc.top/Article/details/gtwrmfstsp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yangfankeji.com/Article/details/gtwszhfjso.html

[R17] 数组定义与取值
来源：http://dali.zdqjudy.top/Article/details/gtzqvxznoq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yangfankeji.com/Article/details/gttxsofuov.html

[R18] 遍历数组
来源：http://dali.bjfxy.top/Article/details/gtraiaejhl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtpijblzil.html

[R19] 数组长度
来源：http://dali.vqdsnc.cn/Article/details/gtdktgbxnq.html

echo "${#arr[@]}"
来源：http://dali.jqgufenzy.top/Article/details/gtnhrnltwo.html

[R20] 关联数组（字典）
来源：http://dali.mhx1999.top/Article/details/gtagajcxna.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jlsjyb.cn/Article/details/gtlslvduss.html

[R21] 字符串长度
来源：http://dali.hysaishi.cn/Article/details/gtidhivvfe.html

echo "${#s}"
来源：http://dali.guannengcc.top/Article/details/gthztuidxk.html

[R22] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gtubnuxidr.html

echo "${s:0:5}"
来源：http://dali.zhoulong.xyz/Article/details/gtqakikvbw.html

[R23] 字符串替换
来源：http://dali.redwolf501.top/Article/details/gtgdkxjhsc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.fengsongda.top/Article/details/gtoiskpqeu.html

[R24] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gtatqokxfv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.birdmap.top/Article/details/gtdabqlfhi.html

[R25] 去后缀 / 去前缀
来源：http://dali.aibaodan.cn/Article/details/gtbczyxclx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.fengsongda.top/Article/details/gtgbmacrpj.html

[R26] 命令替换
来源：http://dali.sxryk.cn/Article/details/gtypfsnndo.html

now=$(date +%F); echo "$now"
来源：http://dali.daria6918.cn/Article/details/gtryjdabby.html

[R27] 算术展开
来源：http://dali.chenlongwang.top/Article/details/gtaybngauq.html

echo $((1 + 2 * 3))
来源：http://dali.chenlongwang.top/Article/details/gttoogreew.html

[R28] 浮点运算
来源：http://dali.cqqwz.cn/Article/details/gtszxllebd.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj20258.top/Article/details/gtsrbkarbw.html

[R29] 定义函数
来源：http://dali.sysykeji.top/Article/details/gtmsnllcbk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gogol.net.cn/Article/details/gtlyfkojvx.html

[R30] 函数返回状态码
来源：http://dali.wangdashe.top/Article/details/gtbfxzhdba.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj202588.top/Article/details/gthiuugknu.html

[R31] 局部变量
来源：http://dali.yj20258.top/Article/details/gtnocmdcwu.html

f() { local x=1; echo "$x"; }
来源：http://dali.jqgfzy.top/Article/details/gtqwasfncw.html

[R32] 参数个数校验
来源：http://dali.jiagoushi.top/Article/details/gtvaavynqs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gtosaidggf.html

[R33] 捕获错误并提示行号
来源：http://dali.ivvv.top/Article/details/gtzyhiayzc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yueranfly.top/Article/details/gtudpuzkfe.html

[R34] 退出时清理
来源：http://dali.pengpengdd.cyou/Article/details/gtjzhtdkzq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sxryk.cn/Article/details/gtsoniobqs.html

[R35] 后台执行并等待
来源：http://dali.meibo888.top/Article/details/gtkboghlyg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hammf.cn/Article/details/gtcrikzdpt.html

[R36] 并发执行多个任务
来源：http://dali.kuanghao11.cn/Article/details/gtgaagcduw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shangyingyoupin.top/Article/details/gtapyhdcna.html

[R37] 把输出赋给变量
来源：http://dali.xziqi.cn/Article/details/gtzvemwjox.html

files=$(ls -1)
来源：http://dali.yj20258.top/Article/details/gtlhcialen.html

[R38] 管道串联
来源：http://dali.pycfn.com/Article/details/gtcbfpopdk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jiagoushi.top/Article/details/gthzmqrmpt.html

[R39] 重定向标准输出与错误
来源：http://dali.c1oappe.top/Article/details/gtxojyvkdr.html

cmd > out.log 2>&1
来源：http://dali.yanxiufei.cn/Article/details/gtpxymlqvv.html

[R40] 追加写日志
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhzlxgya.html

echo "log" >> out.log
来源：http://dali.cqqwz.cn/Article/details/gtxivsanum.html

[R41] 丢弃输出
来源：http://dali.jinqigufen.top/Article/details/gtesqiksge.html

cmd >/dev/null 2>&1
来源：http://dali.xuanzx.com/Article/details/gtrkgjfmbk.html

[R42] 输入重定向
来源：http://dali.shzxlz.cn/Article/details/gttsqynvzo.html

wc -l < a.txt
来源：http://dali.gzhubu.top/Article/details/gtcxxgferx.html

[R43] 按名字查找文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntbmpqiz.html

find . -name "*.log" -type f
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdbhywnd.html

[R44] 按修改时间查找
来源：http://dali.mhx1999.top/Article/details/gtbkbiohvj.html

find . -mtime -7 -type f
来源：http://dali.dianchejie.cn/Article/details/gtdzamlwca.html

[R45] 批量删除
来源：http://dali.snrcjt.cn/Article/details/gtabiygopi.html

find . -name "*.tmp" -delete
来源：http://dali.wangshuangyany.cn/Article/details/gttrknbosd.html

[R46] 递归替换文件内容
来源：http://dali.hysaishi.cn/Article/details/gtbjjlvyqu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yueranfly.top/Article/details/gtgfegmpws.html

[R47] sed 单行替换
来源：http://dali.0kj1m.cn/Article/details/gtsvzihdzb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtbtaokmvg.html

[R48] awk 取指定列
来源：http://dali.xuetiantiany.cn/Article/details/gtzaitpzxo.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtcgwpecws.html

[R49] awk 带条件
来源：http://dali.jinqigfzy.top/Article/details/gtncwzenna.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gotoacloud.top/Article/details/gtchmedyfp.html

[R50] awk 求和
来源：http://dali.tanke756.top/Article/details/gtubztaalr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daria6918.cn/Article/details/gtyynjpwvm.html

[R51] 排序去重取前几
来源：http://dali.cheryme.top/Article/details/gtdrdnygvp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cucudq.cn/Article/details/gtgxzsmhqq.html

[R52] 统计行数
来源：http://dali.gzhubu.top/Article/details/gtwnicalct.html

wc -l a.txt
来源：http://dali.dianchejie.cn/Article/details/gteueitelr.html

[R53] 查看文件头与实时尾
来源：http://dali.svipenyu.cn/Article/details/gtftumyggu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xylfe.cn/Article/details/gtwdtbggnc.html

[R54] 比较两个文件
来源：http://dali.sufxvd.cn/Article/details/gtsyebbdbk.html

diff a.txt b.txt
来源：http://dali.cheryme.top/Article/details/gtjeppeipi.html

[R55] 压缩与解压
来源：http://dali.birdmap.top/Article/details/gtnbhtcnyt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.fengsongda.top/Article/details/gtrkyfdtur.html

[R56] 远程拷贝
来源：http://dali.xinyue.icu/Article/details/gtffchbfnx.html

scp file user@host:/path/
来源：http://dali.zhiwuduotai.top/Article/details/gtminqkbst.html

[R57] 远程执行命令
来源：http://dali.ydzc1.top/Article/details/gticmlsimp.html

ssh user@host 'uptime'
来源：http://dali.9152youxi.cn/Article/details/gtjrfmvxvm.html

[R58] 下载文件
来源：http://dali.yj20258888.top/Article/details/gtlfeyctgr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dashuyun.cn/Article/details/gtfdzlipzl.html

[R59] 发 POST JSON
来源：http://dali.cheryme.top/Article/details/gtkouxjsdm.html


<!-- 参考信息 -->