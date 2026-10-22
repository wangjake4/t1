代发 wailian999

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.fengsongda.top/Article/details/gtyofpgajk.html

[Q09] 创建唯一索引
来源：http://dali.zhengqikj.top/Article/details/gttzwyavlv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhongyouzk.top/Article/details/gtzesunhvr.html

[Q10] 插入单行
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfqrrjdj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hammf.cn/Article/details/gtcjukagcq.html

[Q11] 一次插入多行
来源：http://dali.cqqwz.cn/Article/details/gtmfcooyse.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sweek.top/Article/details/gtxaeqfncz.html

[Q12] 插入后取自增 ID
来源：http://dali.aibaodan.cn/Article/details/gtkehnoxkm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hammf.cn/Article/details/gtngvurkom.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nanxinkj.top/Article/details/gtsrffdyrw.html

[Q13] 忽略重复插入
来源：http://dali.ybcxt.top/Article/details/gtgpiwamdx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yuanzhike.top/Article/details/gtazezdgzx.html

[Q14] 存在则更新（upsert）
来源：http://dali.jlsjyb.cn/Article/details/gtkcfmedrn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cdnleiting.top/Article/details/gticftzesk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgufenzy.top/Article/details/gtlytdrprp.html

[Q15] 查询全部
来源：http://dali.xylfe.cn/Article/details/gtmytlxlec.html

SELECT * FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtswksnywk.html

[Q16] 查询指定列
来源：http://dali.nanxuanxn.top/Article/details/gtngjdcjyf.html

SELECT id, name FROM users;
来源：http://dali.cucudq.cn/Article/details/gtzkzqofgc.html

[Q17] 条件查询
来源：http://dali.yj20258888.top/Article/details/gtsjbrjdan.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.andypj.xyz/Article/details/gtjvwxcmod.html

[Q18] 模糊匹配
来源：http://dali.sufxvd.cn/Article/details/gtugfhtgqa.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.mhx1999.top/Article/details/gtahzpttxb.html

[Q19] 范围查询
来源：http://dali.cashguo.top/Article/details/gtoizentrm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sufxvd.cn/Article/details/gtmcuwtriw.html

[Q20] IN 列表
来源：http://dali.chenlongwang.top/Article/details/gtikaljqky.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cashguo.top/Article/details/gtmudxlknq.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gtpcubulbw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.9152youxi.cn/Article/details/gtppevghro.html

[Q22] 排序
来源：http://dali.bjfxy.top/Article/details/gtcsrusnta.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.quarkkingdee.top/Article/details/gtjbjwslaf.html

[Q23] 分页
来源：http://dali.9152youxi.cn/Article/details/gtabynlyar.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.quarkkingdee.top/Article/details/gthtwqhgkt.html

[Q24] 去重
来源：http://dali.xziqi.cn/Article/details/gtfyhbrxvr.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtrzhgapoj.html

[Q25] 只取前 N 条
来源：http://dali.c1oappe.top/Article/details/gtekoqujdi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hnxiangtu.top/Article/details/gtjvyfvmhf.html

[Q26] 计数
来源：http://dali.cashguo.top/Article/details/gtmmlewmjp.html

SELECT COUNT(*) FROM users;
来源：http://dali.birdmap.top/Article/details/gtwxkglsah.html

[Q27] 条件计数
来源：http://dali.yj20258888.top/Article/details/gtzsugoveh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangdashe.top/Article/details/gtrrnjtiyc.html

[Q28] 求和与平均
来源：http://dali.sufxvd.cn/Article/details/gtnabyuial.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtsouqtjbr.html

[Q29] 最大最小值
来源：http://dali.sweek.top/Article/details/gtpaqpmdke.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.mhx1999.top/Article/details/gthcfkjszi.html

[Q30] 分组统计
来源：http://dali.xuanzx.com/Article/details/gtmhsdjiuj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtdsdocmvp.html

[Q31] 分组后过滤
来源：http://dali.jqgfzy.top/Article/details/gtcfgyfsdx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tianlin.xyz/Article/details/gtmvcgixta.html

[Q32] 分组拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gtfbtjcfsp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gtkwsxrzqa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.daxiang520.top/Article/details/gthnkhdvqx.html

[Q33] 多列分组
来源：http://dali.feifeiyinyue.top/Article/details/gtgzvovqpc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jyoumei.cn/Article/details/gtlaarmawy.html

[Q34] 每组取第一条
来源：http://dali.zdqjudy.top/Article/details/gthfyzaeau.html

SELECT * FROM (
来源：http://dali.jyoumei.cn/Article/details/gtyvhfqmug.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guowangkeji.top/Article/details/gtqmhyxxmd.html

) t WHERE rn = 1;
来源：http://dali.ppjwa.cn/Article/details/gtsjxxosis.html

[Q35] 内连接
来源：http://dali.nanxinkj.top/Article/details/gtxnbnqztz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtfjgfogra.html

[Q36] 左连接
来源：http://dali.zhongyouzk.top/Article/details/gtwcyeiwlx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dianchejie.cn/Article/details/gtfzuntbck.html

[Q37] 右连接
来源：http://dali.daria6918.cn/Article/details/gtayuywbuj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigufen.top/Article/details/gtzrlcycgn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj202588.top/Article/details/gtpsqsqsxl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtztvdjwuj.html

[Q39] 自连接（查上下级）
来源：http://dali.redwolf501.top/Article/details/gtsysbpuuo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yangfankeji.com/Article/details/gthfwhecpg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shuidangran.top/Article/details/gtwssxuwrc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.daria6918.cn/Article/details/gtewlrknpt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hnxiangtu.top/Article/details/gtitsgtsys.html

[Q41] 多表连接
来源：http://dali.yanxiufei.cn/Article/details/gtdmooazgc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hywenlv.cn/Article/details/gthtbqiowc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenjidiqi.icu/Article/details/gteffjdfqs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.quarkkingdee.top/Article/details/gtcsjunkyq.html

[Q42] 连接条件附加过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzlecpwyk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ppjwa.cn/Article/details/gtwmfwlrna.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shuidangran.top/Article/details/gtjaynbseq.html

[Q43] 标量子查询
来源：http://dali.fzhhl.top/Article/details/gtucdukbrm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.bjfxy.top/Article/details/gtglsrxqya.html

[Q44] IN 子查询
来源：http://dali.0kj1m.cn/Article/details/gtbctfdqzk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cqqwz.cn/Article/details/gtpsgzzjwe.html

[Q45] EXISTS 判断存在
来源：http://dali.cdnleiting.top/Article/details/gtrpsktpzt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ppjwa.cn/Article/details/gtklirwmvh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtlynnprpu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gtxfonaqzx.html

[Q47] 与平均值比较
来源：http://dali.jinqigufen.top/Article/details/gtrmlryddt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmgpdnuu.html

[Q48] CTE 公用表表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtzxrhnvnz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zdqjudy.top/Article/details/gtbovhyhlg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhixingplan.top/Article/details/gtwnqtzjpx.html

[Q49] 更新单行
来源：http://dali.shanyushiyangtech.top/Article/details/gtxpqjebyj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gtkejmaxel.html

[Q50] 批量更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gttwpqtuih.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gzhubu.top/Article/details/gtebwvrxbg.html

[Q51] 用子查询更新
来源：http://dali.wangdashe.top/Article/details/gtzypbypnv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtmmsixwdf.html

[Q52] 删除指定行
来源：http://dali.meibo888.top/Article/details/gtjcpirvpc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmsgpzkfy.html

[Q53] 按条件删除
来源：http://dali.cheryme.top/Article/details/gtooanmzol.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbnssbgi.html

[Q54] 清空表
来源：http://dali.shzxlz.cn/Article/details/gtpuwqhqho.html

TRUNCATE TABLE logs;
来源：http://dali.jiagoushi.top/Article/details/gtevnvosed.html

[Q55] 排名（并列占位）
来源：http://dali.ivvv.top/Article/details/gtjvzzdfpn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jyoumei.cn/Article/details/gtosqrxggg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnxiangtu.top/Article/details/gtfxjpovts.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.quarkkingdee.top/Article/details/gtyzsmljae.html

[Q57] 行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzckptnhw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gthoexinuk.html

[Q58] 累计求和
来源：http://dali.yuanzhike.top/Article/details/gtycwodqpc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtrhzgtyjp.html

[Q59] 分组内累计
来源：http://dali.tanke756.top/Article/details/gtyroqgnqi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtsvbthjzw.html

[Q60] 取上一行 / 下一行
来源：http://dali.ivvv.top/Article/details/gttsvqubbc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shuidangran.top/Article/details/gtnnhyzbcn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtxcbkitrg.html

[Q61] 移动平均
来源：http://dali.cucudq.cn/Article/details/gtcvojvncc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtaaqkzfui.html

[Q62] 分组占比
来源：http://dali.snrcjt.cn/Article/details/gtghgybpwv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gtzzmnsxaa.html

[Q63] 开启事务
来源：http://dali.zdqjudy.top/Article/details/gtufyhqxka.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fzhhl.top/Article/details/gteqoanxhn.html

[Q64] 提交事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyruagztu.html

COMMIT;
来源：http://dali.0kj1m.cn/Article/details/gtbhzxovnw.html

[Q65] 回滚事务
来源：http://dali.yvedp.cn/Article/details/gtcgykxbnl.html

ROLLBACK;
来源：http://dali.fzhhl.top/Article/details/gtmsoyvjkh.html

[Q66] 行锁查询
来源：http://dali.yanxiufei.cn/Article/details/gtvxjsguvy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.andypj.xyz/Article/details/gtyphndldx.html

[Q67] 设置隔离级别
来源：http://dali.haohaochexian.top/Article/details/gtqrnmxkhm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgfzy.top/Article/details/gtpmfzlrlw.html

[Q68] 保存点
来源：http://dali.yj20258888.top/Article/details/gtilmlfmjl.html

SAVEPOINT sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtfqhxirsx.html

ROLLBACK TO sp1;
来源：http://dali.guowangkeji.top/Article/details/gtcjuvrlfr.html

[Q69] 查看执行计划
来源：http://dali.chenzaomai.com/Article/details/gtdhrhzkcj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shangyingyoupin.top/Article/details/gtmfjmrnqi.html

[Q70] 更新统计信息
来源：http://dali.smart0.xyz/Article/details/gtmavljwau.html

ANALYZE TABLE users;
来源：http://dali.gaohongyu789.top/Article/details/gthkvxsyyc.html

[Q71] 查看建表语句
来源：http://dali.yuxming.cn/Article/details/gtdjtfojsf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gotoacloud.top/Article/details/gtbqhyvogw.html

[Q72] 查看索引
来源：http://dali.sysykeji.top/Article/details/gtbznrwotf.html

SHOW INDEX FROM users;
来源：http://dali.xziqi.cn/Article/details/gtprzcqvlx.html

[Q73] 查看表状态
来源：http://dali.c1oappe.top/Article/details/gttzznndtl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinqigufen.top/Article/details/gtmkpawacz.html

[Q74] 强制使用索引
来源：http://dali.hnxiangtu.top/Article/details/gtfblvafsx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.redwolf501.top/Article/details/gttieltzfv.html

[Q75] 日期格式化
来源：http://dali.cashguo.top/Article/details/gtzhpvlueq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gthghpnhza.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yongpay.top/Article/details/gtwiryatli.html

[Q76] 按天统计
来源：http://dali.jlsjyb.cn/Article/details/gtyrlvytlk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tanke756.top/Article/details/gtkrzzitll.html

[Q77] 时间加减
来源：http://dali.xuetiantiany.cn/Article/details/gtrqbwfqgk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xinyue.icu/Article/details/gtjtggpyiz.html

[Q78] 当前时间
来源：http://dali.nanxuanxn.top/Article/details/gtifjfimzk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.aizwys.cn/Article/details/gtimcihygl.html

[Q79] 字符串拼接
来源：http://dali.pycfn.com/Article/details/gttrulaqwb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cashguo.top/Article/details/gtxemkyaol.html

[Q80] 字符串截取
来源：http://dali.vqdsnc.cn/Article/details/gtergegdyk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tanke756.top/Article/details/gtvnfikapz.html

[Q81] 字符串替换
来源：http://dali.yj20258888.top/Article/details/gtofebqjpn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yvedp.cn/Article/details/gtgaypzaeo.html

[Q82] 字符长度与字节长度
来源：http://dali.quarkkingdee.top/Article/details/gtbueovqfm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtbnpkqnfo.html

[Q83] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gtllwcasjc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtteizvgaf.html

[Q84] 去除首尾空格
来源：http://dali.mhx1999.top/Article/details/gtqwcjfafc.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtnnexegew.html

[Q85] 数值取整
来源：http://dali.nanxuanxn.top/Article/details/gtikpfkhnd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangshuangyany.cn/Article/details/gtagbucdjo.html

[Q86] 读取 JSON 字段
来源：http://dali.dianchejie.cn/Article/details/gtfelrhiyo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jianghu66.top/Article/details/gthzudhrzq.html

[Q87] JSON 字段做条件
来源：http://dali.dashuyun.cn/Article/details/gtanenzvxa.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.quarkkingdee.top/Article/details/gtmbbkyvga.html

[Q88] 行转列（条件聚合）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcnwgcdh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ehwqpu.com/Article/details/gtutsxvjzx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtxdemagob.html

[Q89] 判断表是否存在
来源：http://dali.cqqwz.cn/Article/details/gtblcyteaf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.dianchejie.cn/Article/details/gthfsplrcj.html

[Q90] 生成序号列
来源：http://dali.jlsjyb.cn/Article/details/gtydwfqfrl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.quarkkingdee.top/Article/details/gtpwumwtng.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtwyspnppz.html

R. Bash 专题
来源：http://dali.shangyingyoupin.top/Article/details/gtxgmdhnev.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtyecruabv.html

[R01] shebang 与严格模式
来源：http://dali.mhx1999.top/Article/details/gtrbujyzoo.html

#!/usr/bin/env bash
来源：http://dali.jqgufenzy.top/Article/details/gtfmpqgbjs.html

set -euo pipefail
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqlqsmgnm.html

[R02] 变量赋值与使用
来源：http://dali.gaohongyu789.top/Article/details/gtghhfqnrx.html

name="Tom"; echo "$name"
来源：http://dali.pengpengdd.cyou/Article/details/gtycgnuchk.html

[R03] 只读变量
来源：http://dali.shzxlz.cn/Article/details/gtnyfbvmes.html

readonly PI=3.14
来源：http://dali.shuidangran.top/Article/details/gtddbzejex.html

[R04] 位置参数
来源：http://dali.pycfn.com/Article/details/gtspreyyvn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.daria6918.cn/Article/details/gtufcxekaf.html

[R05] 参数默认值
来源：http://dali.fzhhl.top/Article/details/gtxtponhfn.html

name="${1:-default}"
来源：http://dali.chenlongwang.top/Article/details/gtsmzywash.html

[R06] 判断命令是否存在
来源：http://dali.sxryk.cn/Article/details/gtxpqedjdg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gtuwtbshpl.html

[R07] if 判断文件
来源：http://dali.xinyue.icu/Article/details/gtkwjwsxij.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jianghu66.top/Article/details/gtvwobwgkw.html

[R08] 数值比较
来源：http://dali.snrcjt.cn/Article/details/gtsbihecxk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jianghu66.top/Article/details/gtfkxtyxho.html

[R09] 字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gtwahpqvhe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.haohaochexian.top/Article/details/gtxrckmpgj.html

[R10] 正则匹配
来源：http://dali.zycfv.cn/Article/details/gtwxdsxejc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtctjlfwui.html

[R11] case 多分支
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmdsrxjw.html

case "$1" in
来源：http://dali.yvedp.cn/Article/details/gtunodbdpo.html

start) echo "启动" ;;
来源：http://dali.sweek.top/Article/details/gthuvmckuk.html

stop)  echo "停止" ;;
来源：http://dali.shzxlz.cn/Article/details/gtflgypxpx.html

*)     echo "未知命令" ;;
来源：http://dali.tian-w.cn/Article/details/gtltecqcwf.html

esac
来源：http://dali.zdqjudy.top/Article/details/gtsavozkzr.html

[R12] for 遍历文件
来源：http://dali.zdqjudy.top/Article/details/gtrbcelxbt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.mhx1999.top/Article/details/gtjfonxqhh.html

[R13] for 计数循环
来源：http://dali.shangyingyoupin.top/Article/details/gtcjilxkoh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtvzlmlkbd.html

[R14] C 风格 for
来源：http://dali.birdmap.top/Article/details/gtqjopwnuj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gtmodhfqsk.html

[R15] while 逐行读文件
来源：http://dali.bjfxy.top/Article/details/gtyezvtgmu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cqqwz.cn/Article/details/gtxrdxeets.html

[R16] until 等待条件
来源：http://dali.316326.xyz/Article/details/gteincmdvx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gtgzgdvnvv.html

[R17] 数组定义与取值
来源：http://dali.iojbl.cn/Article/details/gtpwfbmblx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shangyingyoupin.top/Article/details/gtwgghdypa.html

[R18] 遍历数组
来源：http://dali.vqdsnc.cn/Article/details/gtkltrlkai.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.quarkkingdee.top/Article/details/gtlsijcvdd.html

[R19] 数组长度
来源：http://dali.xinyue.icu/Article/details/gtjkjgwlcw.html

echo "${#arr[@]}"
来源：http://dali.zycfv.cn/Article/details/gtezyombxn.html

[R20] 关联数组（字典）
来源：http://dali.meibo888.top/Article/details/gtaihsywso.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xylfe.cn/Article/details/gtxonvpdaq.html

[R21] 字符串长度
来源：http://dali.zhixingplan.top/Article/details/gtvgszhvai.html

echo "${#s}"
来源：http://dali.316326.xyz/Article/details/gtohwmjmqf.html

[R22] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gtcatgswfq.html

echo "${s:0:5}"
来源：http://dali.tianlin.xyz/Article/details/gtaatshvto.html

[R23] 字符串替换
来源：http://dali.chenjidiqi.icu/Article/details/gttmnoesfo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sweek.top/Article/details/gtxypiesjr.html

[R24] 大小写转换
来源：http://dali.havefunace.top/Article/details/gtcpznhism.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tianlin.xyz/Article/details/gtbhtkntmp.html

[R25] 去后缀 / 去前缀
来源：http://dali.hywenlv.cn/Article/details/gtodjwozrh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.havefunace.top/Article/details/gthubmzaqc.html

[R26] 命令替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoubtcvwy.html

now=$(date +%F); echo "$now"
来源：http://dali.sufxvd.cn/Article/details/gtnujzhleu.html

[R27] 算术展开
来源：http://dali.aibaodan.cn/Article/details/gtgezgzhvh.html

echo $((1 + 2 * 3))
来源：http://dali.haohaochexian.top/Article/details/gtduvdtptu.html

[R28] 浮点运算
来源：http://dali.zdqjudy.top/Article/details/gtmuqsclrd.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj20258888.top/Article/details/gtbkcyhbat.html

[R29] 定义函数
来源：http://dali.gaohongyu789.top/Article/details/gttdhsybmu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.feifeiyinyue.top/Article/details/gtgjllebki.html

[R30] 函数返回状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtpqalnprl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tanke756.top/Article/details/gtrtfzskdo.html

[R31] 局部变量
来源：http://dali.dianchejie.cn/Article/details/gthwtxlvcp.html

f() { local x=1; echo "$x"; }
来源：http://dali.haohaochexian.top/Article/details/gtcvwkrkrg.html

[R32] 参数个数校验
来源：http://dali.jiagoushi.top/Article/details/gtrsxmzunb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jlsjyb.cn/Article/details/gtjgdihbar.html

[R33] 捕获错误并提示行号
来源：http://dali.yangfankeji.com/Article/details/gtiudrespb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cashguo.top/Article/details/gtkbtopeki.html

[R34] 退出时清理
来源：http://dali.guannengcc.top/Article/details/gtpcnrtnut.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gtaeocpstc.html

[R35] 后台执行并等待
来源：http://dali.redwolf501.top/Article/details/gtrycexiih.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shzxlz.cn/Article/details/gtvfysgkqs.html

[R36] 并发执行多个任务
来源：http://dali.jinqigfzy.top/Article/details/gthwvzuvom.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuxming.cn/Article/details/gtytkcspkj.html

[R37] 把输出赋给变量
来源：http://dali.0kj1m.cn/Article/details/gtmjiuovgj.html

files=$(ls -1)
来源：http://dali.iojbl.cn/Article/details/gtwwmwxhgq.html

[R38] 管道串联
来源：http://dali.zhengqikj.top/Article/details/gtlcuavpuk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzargzlc.html

[R39] 重定向标准输出与错误
来源：http://dali.ivvv.top/Article/details/gtxogwzwic.html

cmd > out.log 2>&1
来源：http://dali.yangfankeji.com/Article/details/gtunonikrv.html

[R40] 追加写日志
来源：http://dali.dashuyun.cn/Article/details/gtteivqpln.html

echo "log" >> out.log
来源：http://dali.xylfe.cn/Article/details/gtejbyyqyv.html

[R41] 丢弃输出
来源：http://dali.cdnleiting.top/Article/details/gthhyxetvp.html

cmd >/dev/null 2>&1
来源：http://dali.cqqwz.cn/Article/details/gtctgezuaq.html

[R42] 输入重定向
来源：http://dali.jyoumei.cn/Article/details/gttqvfwnpn.html

wc -l < a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtsmcxhnyr.html

[R43] 按名字查找文件
来源：http://dali.shangyingyoupin.top/Article/details/gtlkrsxgdi.html

find . -name "*.log" -type f
来源：http://dali.aibaodan.cn/Article/details/gtrsfimtni.html

[R44] 按修改时间查找
来源：http://dali.hysaishi.cn/Article/details/gtfxvxstoe.html

find . -mtime -7 -type f
来源：http://dali.smart0.xyz/Article/details/gtrdlalwzg.html

[R45] 批量删除
来源：http://dali.shangyingyoupin.top/Article/details/gtkytfmato.html

find . -name "*.tmp" -delete
来源：http://dali.kuanghao11.cn/Article/details/gthbgfqxuk.html

[R46] 递归替换文件内容
来源：http://dali.hnxiangtu.top/Article/details/gtchgsgbiy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenlongwang.top/Article/details/gtwbcwtuce.html

[R47] sed 单行替换
来源：http://dali.zhoulong.xyz/Article/details/gtphucznki.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hfpthk.cn/Article/details/gteqoexxyo.html

[R48] awk 取指定列
来源：http://dali.dianchejie.cn/Article/details/gtfsofhaun.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtfwoyetld.html

[R49] awk 带条件
来源：http://dali.gaohongyu789.top/Article/details/gtsjxnklgz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jlsjyb.cn/Article/details/gtoeumfrsd.html

[R50] awk 求和
来源：http://dali.chenzaomai.com/Article/details/gtwcoxmcka.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtnaezvfis.html

[R51] 排序去重取前几
来源：http://dali.havefunace.top/Article/details/gtxeooirtn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.iojbl.cn/Article/details/gtnpgfqrtb.html

[R52] 统计行数
来源：http://dali.dianchejie.cn/Article/details/gtywemynmo.html

wc -l a.txt
来源：http://dali.meibo888.top/Article/details/gtfzwqrjnw.html

[R53] 查看文件头与实时尾
来源：http://dali.sysykeji.top/Article/details/gtdymfpcwx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.vqdsnc.cn/Article/details/gttovaccpi.html

[R54] 比较两个文件
来源：http://dali.jqgfzy.top/Article/details/gtbjkltopl.html

diff a.txt b.txt
来源：http://dali.c1oappe.top/Article/details/gthjohxfmk.html

[R55] 压缩与解压
来源：http://dali.cheryme.top/Article/details/gtznaewyyp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dashuyun.cn/Article/details/gtqvooswzm.html

[R56] 远程拷贝
来源：http://dali.tanke756.top/Article/details/gtijbggtxv.html

scp file user@host:/path/
来源：http://dali.yvedp.cn/Article/details/gtvkmvyyoi.html

[R57] 远程执行命令
来源：http://dali.yueranfly.top/Article/details/gtwucmgxuu.html


<!-- 参考信息 -->