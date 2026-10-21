代发 wailian999

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yangfankeji.com/Article/details/gteynvglot.html

[Q09] 创建唯一索引
来源：http://dali.9152youxi.cn/Article/details/gthmbbklds.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cdnleiting.top/Article/details/gtshphjdqb.html

[Q10] 插入单行
来源：http://dali.daria6918.cn/Article/details/gtfuimlgoa.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhwpjcaj.html

[Q11] 一次插入多行
来源：http://dali.c1oappe.top/Article/details/gteoyojrye.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gtxwotbblh.html

[Q12] 插入后取自增 ID
来源：http://dali.daria6918.cn/Article/details/gtuxjhnlil.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.guannengcc.top/Article/details/gtxmmxcsmb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.kuanghao11.cn/Article/details/gtcuwllueh.html

[Q13] 忽略重复插入
来源：http://dali.sxryk.cn/Article/details/gtekrvycun.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pycfn.com/Article/details/gtimmoszvf.html

[Q14] 存在则更新（upsert）
来源：http://dali.zycfv.cn/Article/details/gtyaodmtoa.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinqigufen.top/Article/details/gtublnvbva.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gtkrrlvlgp.html

[Q15] 查询全部
来源：http://dali.cashguo.top/Article/details/gtxqixpxhf.html

SELECT * FROM users;
来源：http://dali.guannengcc.top/Article/details/gtrdqoabyw.html

[Q16] 查询指定列
来源：http://dali.zhixingplan.top/Article/details/gtbxhbbtsq.html

SELECT id, name FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdcrqdwbl.html

[Q17] 条件查询
来源：http://dali.vqdsnc.cn/Article/details/gtbfakbkgg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtlwzlajoh.html

[Q18] 模糊匹配
来源：http://dali.yonumen.top/Article/details/gtustvjkfj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yonumen.top/Article/details/gthsgesspp.html

[Q19] 范围查询
来源：http://dali.fzhhl.top/Article/details/gteanhflfv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuetiantiany.cn/Article/details/gteerauiuz.html

[Q20] IN 列表
来源：http://dali.sweek.top/Article/details/gtoufylpxi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.9152youxi.cn/Article/details/gtsixcnyks.html

[Q21] 空值判断
来源：http://dali.hfpthk.cn/Article/details/gtpkcjorww.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnxiangtu.top/Article/details/gteqmbqfbi.html

[Q22] 排序
来源：http://dali.gaohongyu789.top/Article/details/gtubglroia.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.daxiang520.top/Article/details/gtkhsvhigk.html

[Q23] 分页
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmsmsdhpw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.quarkkingdee.top/Article/details/gtkoarsmff.html

[Q24] 去重
来源：http://dali.haohaochexian.top/Article/details/gtydjvnthd.html

SELECT DISTINCT city FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtperneafq.html

[Q25] 只取前 N 条
来源：http://dali.iojbl.cn/Article/details/gtkdyfdvdc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnrzjiet.html

[Q26] 计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbottbal.html

SELECT COUNT(*) FROM users;
来源：http://dali.cheryme.top/Article/details/gttymtlufd.html

[Q27] 条件计数
来源：http://dali.svipenyu.cn/Article/details/gtyakbizmi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtbhdxclnh.html

[Q28] 求和与平均
来源：http://dali.ydzc1.top/Article/details/gtpdjtlzii.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtrejdfocz.html

[Q29] 最大最小值
来源：http://dali.wangshuangyany.cn/Article/details/gthimhjpnt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj20258888.top/Article/details/gttvpkltjm.html

[Q30] 分组统计
来源：http://dali.hammf.cn/Article/details/gtbdgouuzg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmwgzirh.html

[Q31] 分组后过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdbwlznr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.guowangkeji.top/Article/details/gtwanmvyoz.html

[Q32] 分组拼接字符串
来源：http://dali.sxryk.cn/Article/details/gtoynvgefb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gtyaqfixou.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xinyue.icu/Article/details/gtzblrhmpx.html

[Q33] 多列分组
来源：http://dali.meibo888.top/Article/details/gtfujydaxi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhiwuduotai.top/Article/details/gtdywdagdd.html

[Q34] 每组取第一条
来源：http://dali.shzxlz.cn/Article/details/gtiqcqbqln.html

SELECT * FROM (
来源：http://dali.sweek.top/Article/details/gtxvjbzcyc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xylfe.cn/Article/details/gtnnsvdwiu.html

) t WHERE rn = 1;
来源：http://dali.jianghu66.top/Article/details/gtnwryicnm.html

[Q35] 内连接
来源：http://dali.sxryk.cn/Article/details/gtnxwrepgn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.quarkkingdee.top/Article/details/gtzopfalby.html

[Q36] 左连接
来源：http://dali.yonumen.top/Article/details/gtcohohuuz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gtzyihgfiz.html

[Q37] 右连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbcbngfin.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuxming.cn/Article/details/gtcbbaxdjb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jianghu66.top/Article/details/gthjtcjtcp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ybcxt.top/Article/details/gtlsgleakr.html

[Q39] 自连接（查上下级）
来源：http://dali.svipenyu.cn/Article/details/gtzjbglxmh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwgjkghu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.birdmap.top/Article/details/gtrtflqust.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gotoacloud.top/Article/details/gtztgcuadk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.pycfn.com/Article/details/gtwsqkfgnk.html

[Q41] 多表连接
来源：http://dali.tian-w.cn/Article/details/gtbotnnnwn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinghuilouyu.cn/Article/details/gtszsnunnu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yuanzhike.top/Article/details/gtzfdtuaof.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenjidiqi.icu/Article/details/gtvvvcwref.html

[Q42] 连接条件附加过滤
来源：http://dali.hysaishi.cn/Article/details/gtqtxlcdpb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yuxming.cn/Article/details/gtdcjfgquj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhixingplan.top/Article/details/gtsmljwklh.html

[Q43] 标量子查询
来源：http://dali.hongshengwenyu.top/Article/details/gtprutspgx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cucudq.cn/Article/details/gtfimzmhqc.html

[Q44] IN 子查询
来源：http://dali.ydzc1.top/Article/details/gtxommdozb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.dianchejie.cn/Article/details/gtlakrtomk.html

[Q45] EXISTS 判断存在
来源：http://dali.ybcxt.top/Article/details/gtvqlwrwbz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenlongwang.top/Article/details/gtpcooqfpa.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cheryme.top/Article/details/gtsfncnzmq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fengsongda.top/Article/details/gtroszltet.html

[Q47] 与平均值比较
来源：http://dali.cqqwz.cn/Article/details/gtslccxntc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsifhvplr.html

[Q48] CTE 公用表表达式
来源：http://dali.yueranfly.top/Article/details/gtyensywoo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzafbtuo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenlongwang.top/Article/details/gtgxtqwuds.html

[Q49] 更新单行
来源：http://dali.jinqigfzy.top/Article/details/gtkwzecqbc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gtpmoqyrcw.html

[Q50] 批量更新
来源：http://dali.yuxming.cn/Article/details/gtlmisfaen.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gtauirbusr.html

[Q51] 用子查询更新
来源：http://dali.fengsongda.top/Article/details/gtxjvfcvyo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtclgxdvco.html

[Q52] 删除指定行
来源：http://dali.yongpay.top/Article/details/gtpyvwnyfz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gtwtezyinv.html

[Q53] 按条件删除
来源：http://dali.jyoumei.cn/Article/details/gtprlwjxld.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.kuanghao11.cn/Article/details/gtkqqtckaz.html

[Q54] 清空表
来源：http://dali.andypj.xyz/Article/details/gthedecioe.html

TRUNCATE TABLE logs;
来源：http://dali.hywenlv.cn/Article/details/gtijrtibyx.html

[Q55] 排名（并列占位）
来源：http://dali.svipenyu.cn/Article/details/gtuxbrzxdl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gotoacloud.top/Article/details/gtjnfqhdsy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.feifeiyinyue.top/Article/details/gtztojazuj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cashguo.top/Article/details/gtixdwlcps.html

[Q57] 行号
来源：http://dali.jlsjyb.cn/Article/details/gtwxymxlye.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtfprzndpi.html

[Q58] 累计求和
来源：http://dali.jiagoushi.top/Article/details/gtipefdhdr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtzxikuhlk.html

[Q59] 分组内累计
来源：http://dali.daxiang520.top/Article/details/gtdgrvvuvn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gthfjvzjdu.html

[Q60] 取上一行 / 下一行
来源：http://dali.yvedp.cn/Article/details/gtvaswqrmy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxxouslf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtlipeexih.html

[Q61] 移动平均
来源：http://dali.hywenlv.cn/Article/details/gtulnbrizp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtqmvxojpy.html

[Q62] 分组占比
来源：http://dali.yanxiufei.cn/Article/details/gtieoavwto.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gtxjpuirxk.html

[Q63] 开启事务
来源：http://dali.redwolf501.top/Article/details/gttfwcnpej.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.haohaochexian.top/Article/details/gtupmwipjh.html

[Q64] 提交事务
来源：http://dali.jyoumei.cn/Article/details/gtoxrkghfg.html

COMMIT;
来源：http://dali.yongpay.top/Article/details/gtqvwlqnsy.html

[Q65] 回滚事务
来源：http://dali.jinqigufen.top/Article/details/gtjfmmxvpx.html

ROLLBACK;
来源：http://dali.havefunace.top/Article/details/gtakosuzov.html

[Q66] 行锁查询
来源：http://dali.nwbrower.top/Article/details/gtdtnahcto.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhengqikj.top/Article/details/gtlgsmqxdm.html

[Q67] 设置隔离级别
来源：http://dali.havefunace.top/Article/details/gttgkqbqws.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.havefunace.top/Article/details/gtbsxvhvjm.html

[Q68] 保存点
来源：http://dali.wangdashe.top/Article/details/gtsaipnrxg.html

SAVEPOINT sp1;
来源：http://dali.jinqigfzy.top/Article/details/gtggcxjvhp.html

ROLLBACK TO sp1;
来源：http://dali.yueranfly.top/Article/details/gtidnxvobx.html

[Q69] 查看执行计划
来源：http://dali.ydzc1.top/Article/details/gteisuznpt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yongpay.top/Article/details/gtwhxomusk.html

[Q70] 更新统计信息
来源：http://dali.yanxiufei.cn/Article/details/gtgpqslpny.html

ANALYZE TABLE users;
来源：http://dali.sxryk.cn/Article/details/gtgpfsbsbm.html

[Q71] 查看建表语句
来源：http://dali.iojbl.cn/Article/details/gtfbprkhlt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.svipenyu.cn/Article/details/gtimgyyxxj.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gtlltpdaln.html

SHOW INDEX FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtzwfwcpas.html

[Q73] 查看表状态
来源：http://dali.sysykeji.top/Article/details/gtnkzvzxkn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj202588.top/Article/details/gtkifjjrvk.html

[Q74] 强制使用索引
来源：http://dali.wangdashe.top/Article/details/gtqjmxwmzl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.guowangkeji.top/Article/details/gtlxephxip.html

[Q75] 日期格式化
来源：http://dali.smart0.xyz/Article/details/gtqpmcnzwd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtjdblookz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinqigufen.top/Article/details/gtlrtbwnpd.html

[Q76] 按天统计
来源：http://dali.gogol.net.cn/Article/details/gtyioqacgl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tianlin.xyz/Article/details/gtoylvaiss.html

[Q77] 时间加减
来源：http://dali.9152youxi.cn/Article/details/gtuwnbwcto.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.quarkkingdee.top/Article/details/gtkwuergan.html

[Q78] 当前时间
来源：http://dali.hywenlv.cn/Article/details/gtxogdfgjg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258.top/Article/details/gtlwtxslkv.html

[Q79] 字符串拼接
来源：http://dali.316326.xyz/Article/details/gtxgepmmwo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwrdqotl.html

[Q80] 字符串截取
来源：http://dali.haohaochexian.top/Article/details/gtpyohuokx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtlnfalygh.html

[Q81] 字符串替换
来源：http://dali.redwolf501.top/Article/details/gtvywtopio.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtlskiyncy.html

[Q82] 字符长度与字节长度
来源：http://dali.316326.xyz/Article/details/gtwavrswqm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtnwjrivbt.html

[Q83] 大小写转换
来源：http://dali.yonumen.top/Article/details/gtwswhwput.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gttibeiawa.html

[Q84] 去除首尾空格
来源：http://dali.cucudq.cn/Article/details/gtjnsyekgx.html

SELECT TRIM(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtdengoclr.html

[Q85] 数值取整
来源：http://dali.ybcxt.top/Article/details/gtuqzaqkzw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxuanxn.top/Article/details/gtkijydxmf.html

[Q86] 读取 JSON 字段
来源：http://dali.dianchejie.cn/Article/details/gtziueszbt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zycfv.cn/Article/details/gtalhbrdcx.html

[Q87] JSON 字段做条件
来源：http://dali.hnxiangtu.top/Article/details/gtvlcicvtf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jqgfzy.top/Article/details/gtfycspzmq.html

[Q88] 行转列（条件聚合）
来源：http://dali.yuxming.cn/Article/details/gtwrtptuad.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.dianchejie.cn/Article/details/gthxwjpwhq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqxjafxa.html

[Q89] 判断表是否存在
来源：http://dali.mhx1999.top/Article/details/gtspditgda.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yonumen.top/Article/details/gtbmrsqxca.html

[Q90] 生成序号列
来源：http://dali.feifeiyinyue.top/Article/details/gtrgkidkoo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenlongwang.top/Article/details/gthjfxwfnm.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtvejkrfow.html

R. Bash 专题
来源：http://dali.pycfn.com/Article/details/gtejjxtefb.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtxqvagkfk.html

[R01] shebang 与严格模式
来源：http://dali.aibaodan.cn/Article/details/gtaubjjjys.html

#!/usr/bin/env bash
来源：http://dali.shzxlz.cn/Article/details/gtravxtcet.html

set -euo pipefail
来源：http://dali.shuidangran.top/Article/details/gtegqeoimo.html

[R02] 变量赋值与使用
来源：http://dali.tanke756.top/Article/details/gtlbfueshy.html

name="Tom"; echo "$name"
来源：http://dali.sufxvd.cn/Article/details/gtlucjpohg.html

[R03] 只读变量
来源：http://dali.316326.xyz/Article/details/gtxjtlrokc.html

readonly PI=3.14
来源：http://dali.bjfxy.top/Article/details/gttvedoryd.html

[R04] 位置参数
来源：http://dali.quarkkingdee.top/Article/details/gtzeiinwjf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zdqjudy.top/Article/details/gtbmkdgsow.html

[R05] 参数默认值
来源：http://dali.sysykeji.top/Article/details/gtrpnxytgf.html

name="${1:-default}"
来源：http://dali.gzhubu.top/Article/details/gtbwuzvooh.html

[R06] 判断命令是否存在
来源：http://dali.hywenlv.cn/Article/details/gtbtjdkcga.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgfzy.top/Article/details/gtfbosykhx.html

[R07] if 判断文件
来源：http://dali.xinyue.icu/Article/details/gtcqdjduad.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xinyue.icu/Article/details/gtrmurolgs.html

[R08] 数值比较
来源：http://dali.ybcxt.top/Article/details/gtxjielyro.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shzxlz.cn/Article/details/gtdopofakc.html

[R09] 字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gtspifpwyv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258.top/Article/details/gtriijufqw.html

[R10] 正则匹配
来源：http://dali.cdnleiting.top/Article/details/gttsrnxgqg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yueranfly.top/Article/details/gtbwxkjxpc.html

[R11] case 多分支
来源：http://dali.yj20258.top/Article/details/gtmcbzuids.html

case "$1" in
来源：http://dali.nwbrower.top/Article/details/gtxbqepqxa.html

start) echo "启动" ;;
来源：http://dali.ehwqpu.com/Article/details/gtcclauxmk.html

stop)  echo "停止" ;;
来源：http://dali.aizwys.cn/Article/details/gtrdbnnpeq.html

*)     echo "未知命令" ;;
来源：http://dali.daxiang520.top/Article/details/gtyshbzrjg.html

esac
来源：http://dali.guannengcc.top/Article/details/gtywvdcxoq.html

[R12] for 遍历文件
来源：http://dali.hysaishi.cn/Article/details/gtsgtwlorl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiyksozga.html

[R13] for 计数循环
来源：http://dali.pengpengdd.cyou/Article/details/gtlbjrvllo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hnqzz.top/Article/details/gtkotzpwbe.html

[R14] C 风格 for
来源：http://dali.shuidangran.top/Article/details/gtpllfrebn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gtjxrheyte.html

[R15] while 逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtvusiqtkc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sxryk.cn/Article/details/gtjdobleen.html

[R16] until 等待条件
来源：http://dali.yj20258888.top/Article/details/gtntymvrtx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yanxiufei.cn/Article/details/gtzqofplrh.html

[R17] 数组定义与取值
来源：http://dali.hnxiangtu.top/Article/details/gtvehnvhei.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhoulong.xyz/Article/details/gtibzengre.html

[R18] 遍历数组
来源：http://dali.jyoumei.cn/Article/details/gttbbjpyfj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.316326.xyz/Article/details/gtmsowgezd.html

[R19] 数组长度
来源：http://dali.snrcjt.cn/Article/details/gtrhosdric.html

echo "${#arr[@]}"
来源：http://dali.zhengqikj.top/Article/details/gtifsqfkqv.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangtech.top/Article/details/gtvuvgqaop.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jlsjyb.cn/Article/details/gtsxsmjvkv.html

[R21] 字符串长度
来源：http://dali.cheryme.top/Article/details/gtvldquvar.html

echo "${#s}"
来源：http://dali.pycfn.com/Article/details/gtzbjgzrnx.html

[R22] 截取子串
来源：http://dali.yonumen.top/Article/details/gtmlywozof.html

echo "${s:0:5}"
来源：http://dali.aizwys.cn/Article/details/gtptemswdw.html

[R23] 字符串替换
来源：http://dali.aizwys.cn/Article/details/gtzkqbcsxd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuanzx.com/Article/details/gtkqgudpac.html

[R24] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjftnabdj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hnqzz.top/Article/details/gtzxltfqql.html

[R25] 去后缀 / 去前缀
来源：http://dali.yvedp.cn/Article/details/gtkfygjixj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.vqdsnc.cn/Article/details/gtakuftdpe.html

[R26] 命令替换
来源：http://dali.jyoumei.cn/Article/details/gtcgvpmjbh.html

now=$(date +%F); echo "$now"
来源：http://dali.tianlin.xyz/Article/details/gtxdwhdait.html

[R27] 算术展开
来源：http://dali.havefunace.top/Article/details/gtywqdglin.html

echo $((1 + 2 * 3))
来源：http://dali.hongshengwenyu.top/Article/details/gtdayfxwsp.html

[R28] 浮点运算
来源：http://dali.yangfankeji.com/Article/details/gtggzobsrf.html

echo "scale=2; 10/3" | bc
来源：http://dali.yuxming.cn/Article/details/gtuxpibbog.html

[R29] 定义函数
来源：http://dali.daxiang520.top/Article/details/gtnyoxevgh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yuanzhike.top/Article/details/gtvzxxhodg.html

[R30] 函数返回状态码
来源：http://dali.gaohongyu789.top/Article/details/gtozwxvwka.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj202588.top/Article/details/gtyhajolou.html

[R31] 局部变量
来源：http://dali.nanxuanxn.top/Article/details/gtudtocrim.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangdashe.top/Article/details/gtlxnonuku.html

[R32] 参数个数校验
来源：http://dali.jiagoushi.top/Article/details/gtczzhmqkv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gtfcxhlxxm.html

[R33] 捕获错误并提示行号
来源：http://dali.feifeiyinyue.top/Article/details/gtahdsodye.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.feifeiyinyue.top/Article/details/gtmuifcqmj.html

[R34] 退出时清理
来源：http://dali.zhixingplan.top/Article/details/gtisdheyff.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gtmazxmhog.html

[R35] 后台执行并等待
来源：http://dali.jiagoushi.top/Article/details/gtedrpaatx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenlongwang.top/Article/details/gtbjvpqfvi.html

[R36] 并发执行多个任务
来源：http://dali.gzhubu.top/Article/details/gtokcqklvb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuanzhike.top/Article/details/gtoyoxezaa.html

[R37] 把输出赋给变量
来源：http://dali.xuanzx.com/Article/details/gtxrswpied.html

files=$(ls -1)
来源：http://dali.svipenyu.cn/Article/details/gtlitepxcn.html

[R38] 管道串联
来源：http://dali.daxiang520.top/Article/details/gtyrjxdkkr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yanxiufei.cn/Article/details/gtmxzeyqwy.html

[R39] 重定向标准输出与错误
来源：http://dali.havefunace.top/Article/details/gtlbugjhvg.html

cmd > out.log 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gtaiprrmwj.html

[R40] 追加写日志
来源：http://dali.aibaodan.cn/Article/details/gthkelwepa.html

echo "log" >> out.log
来源：http://dali.yuanzhike.top/Article/details/gtxevozmul.html

[R41] 丢弃输出
来源：http://dali.tanke756.top/Article/details/gtpzqfeecs.html

cmd >/dev/null 2>&1
来源：http://dali.fengsongda.top/Article/details/gtqblsvbae.html

[R42] 输入重定向
来源：http://dali.yj20258.top/Article/details/gttxmaxcwx.html

wc -l < a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gttuekabsy.html

[R43] 按名字查找文件
来源：http://dali.zdqjudy.top/Article/details/gtlfxkcqsw.html

find . -name "*.log" -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwsepnbk.html

[R44] 按修改时间查找
来源：http://dali.jlsjyb.cn/Article/details/gtiygpelfp.html

find . -mtime -7 -type f
来源：http://dali.jqgfzy.top/Article/details/gtckrdlljn.html

[R45] 批量删除
来源：http://dali.sxryk.cn/Article/details/gtapytuzmp.html

find . -name "*.tmp" -delete
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajayvzkj.html

[R46] 递归替换文件内容
来源：http://dali.guowangkeji.top/Article/details/gtnewtjrhe.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.haohaochexian.top/Article/details/gteskwnbwb.html

[R47] sed 单行替换
来源：http://dali.gotoacloud.top/Article/details/gtiabbpxtt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.fzhhl.top/Article/details/gtoogdohuf.html

[R48] awk 取指定列
来源：http://dali.pycfn.com/Article/details/gtehejbuom.html

awk '{print $1, $3}' a.txt
来源：http://dali.hysaishi.cn/Article/details/gtwxmruqvn.html

[R49] awk 带条件
来源：http://dali.haohaochexian.top/Article/details/gtibbsalkc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nwbrower.top/Article/details/gtjdryqkuf.html

[R50] awk 求和
来源：http://dali.xylfe.cn/Article/details/gtcbwianoj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtxvmeqekx.html

[R51] 排序去重取前几
来源：http://dali.jqgufenzy.top/Article/details/gttczpacsj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258.top/Article/details/gtqdwtifcf.html

[R52] 统计行数
来源：http://dali.havefunace.top/Article/details/gtugyycybz.html

wc -l a.txt
来源：http://dali.cucudq.cn/Article/details/gttbiyaqtp.html

[R53] 查看文件头与实时尾
来源：http://dali.aibaodan.cn/Article/details/gtawintjon.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhiwuduotai.top/Article/details/gtoiuglwhz.html

[R54] 比较两个文件
来源：http://dali.yanxiufei.cn/Article/details/gtifjfoebr.html

diff a.txt b.txt
来源：http://dali.yanxiufei.cn/Article/details/gtmmdzkkse.html

[R55] 压缩与解压
来源：http://dali.dashuyun.cn/Article/details/gtierlpdgx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.svipenyu.cn/Article/details/gtqiymwshp.html

[R56] 远程拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gtixdpkszj.html

scp file user@host:/path/
来源：http://dali.ehwqpu.com/Article/details/gtxmyodbtv.html

[R57] 远程执行命令
来源：http://dali.ivvv.top/Article/details/gthaorqciq.html


<!-- 参考信息 -->