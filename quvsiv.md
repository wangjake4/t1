代发 wailian999

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.fzhhl.top/Article/details/gt2xhymnaau.html

[Q09] 创建唯一索引
来源：http://dali.9152youxi.cn/Article/details/gt2wrugdheo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yangfankeji.com/Article/details/gt2qadxcypv.html

[Q10] 插入单行
来源：http://dali.hongshengwenyu.top/Article/details/gt2qvzlhrhl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.guowangkeji.top/Article/details/gt2ubxrqppg.html

[Q11] 一次插入多行
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nkoottwc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gt2uuzjeodg.html

[Q12] 插入后取自增 ID
来源：http://dali.havefunace.top/Article/details/gt2kwhrxevx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cdnleiting.top/Article/details/gt2gfyyvcjc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.svipenyu.cn/Article/details/gt2ksxsygci.html

[Q13] 忽略重复插入
来源：http://dali.yj20258888.top/Article/details/gt2kxtpzlxk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenzaomai.com/Article/details/gt2wvrkcvsj.html

[Q14] 存在则更新（upsert）
来源：http://dali.quarkkingdee.top/Article/details/gt2luzwqwcq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gzhubu.top/Article/details/gt2qmkoeqyb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.fengsongda.top/Article/details/gt2qqejmpqe.html

[Q15] 查询全部
来源：http://dali.chenjidiqi.icu/Article/details/gt2pqfxjvyz.html

SELECT * FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2znithmha.html

[Q16] 查询指定列
来源：http://dali.meibo888.top/Article/details/gt2cvninzyt.html

SELECT id, name FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2mxzltfut.html

[Q17] 条件查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iynqrhzz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sweek.top/Article/details/gt2wwwiuftp.html

[Q18] 模糊匹配
来源：http://dali.0kj1m.cn/Article/details/gt2rqpddone.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yangfankeji.com/Article/details/gt2wmghuxuh.html

[Q19] 范围查询
来源：http://dali.svipenyu.cn/Article/details/gt2notlnbrj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jqgufenzy.top/Article/details/gt2sjhjvnpm.html

[Q20] IN 列表
来源：http://dali.yueranfly.top/Article/details/gt2xqsejjbr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yvedp.cn/Article/details/gt2aynfeywk.html

[Q21] 空值判断
来源：http://dali.yanxiufei.cn/Article/details/gt2fmuadpcr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.wangdashe.top/Article/details/gt2tiieqhau.html

[Q22] 排序
来源：http://dali.zhoulong.xyz/Article/details/gt2ffdhlsbt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.daria6918.cn/Article/details/gt2senpruop.html

[Q23] 分页
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qozlkdda.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jianghu66.top/Article/details/gt2qagqfteq.html

[Q24] 去重
来源：http://dali.gogol.net.cn/Article/details/gt2yswwrnwv.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2qgvzgpal.html

[Q25] 只取前 N 条
来源：http://dali.havefunace.top/Article/details/gt2kcgdrwqz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.smart0.xyz/Article/details/gt2jfxofbfy.html

[Q26] 计数
来源：http://dali.mhx1999.top/Article/details/gt2tuwwhwju.html

SELECT COUNT(*) FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2eykjphdb.html

[Q27] 条件计数
来源：http://dali.zhiwuduotai.top/Article/details/gt2nosyxpvf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2nsthfbca.html

[Q28] 求和与平均
来源：http://dali.smart0.xyz/Article/details/gt2wjnpjerq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2hdksfymp.html

[Q29] 最大最小值
来源：http://dali.quarkkingdee.top/Article/details/gt2tkngnthg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2cplkojwn.html

[Q30] 分组统计
来源：http://dali.tanke756.top/Article/details/gt2arpoesda.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gt2eqhjrouc.html

[Q31] 分组后过滤
来源：http://dali.ppjwa.cn/Article/details/gt2lshnthjh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.fzhhl.top/Article/details/gt2dpvfqqpb.html

[Q32] 分组拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gt2zpvsmwzg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gt2ieijioja.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.guannengcc.top/Article/details/gt2mgeclzqv.html

[Q33] 多列分组
来源：http://dali.jyoumei.cn/Article/details/gt2lhzsoabj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinqigfzy.top/Article/details/gt2marrptrm.html

[Q34] 每组取第一条
来源：http://dali.cdnleiting.top/Article/details/gt2nkglxlog.html

SELECT * FROM (
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qbfwgkzw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xziqi.cn/Article/details/gt2chszsvvj.html

) t WHERE rn = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ptrchnfo.html

[Q35] 内连接
来源：http://dali.daria6918.cn/Article/details/gt2nlhibrjq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gt2dyaoupzq.html

[Q36] 左连接
来源：http://dali.zdqjudy.top/Article/details/gt2ygllxqtp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.vqdsnc.cn/Article/details/gt2nqkofyws.html

[Q37] 右连接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nypecjyy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.vqdsnc.cn/Article/details/gt2qgtatgvt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhengqikj.top/Article/details/gt2unkwabzl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hnxiangtu.top/Article/details/gt2rtdfphxl.html

[Q39] 自连接（查上下级）
来源：http://dali.yvedp.cn/Article/details/gt2audlnsmn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.kuanghao11.cn/Article/details/gt2ymxwtkpc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daxiang520.top/Article/details/gt2rdvdmtpf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cdnleiting.top/Article/details/gt2xlruqrdv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oglvghya.html

[Q41] 多表连接
来源：http://dali.ehwqpu.com/Article/details/gt2iyzyinic.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.haohaochexian.top/Article/details/gt2lttiijys.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shzxlz.cn/Article/details/gt2ejkepxql.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.dashuyun.cn/Article/details/gt2vxeatkke.html

[Q42] 连接条件附加过滤
来源：http://dali.wangshuangyany.cn/Article/details/gt2ndwfjfiy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yuanzhike.top/Article/details/gt2fbufwcxd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dianchejie.cn/Article/details/gt2vaqqoxnk.html

[Q43] 标量子查询
来源：http://dali.dashuyun.cn/Article/details/gt2rylverru.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dashuyun.cn/Article/details/gt2dzzfestj.html

[Q44] IN 子查询
来源：http://dali.jlsjyb.cn/Article/details/gt2khgqzvaq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cheryme.top/Article/details/gt2jgcuhvqq.html

[Q45] EXISTS 判断存在
来源：http://dali.redwolf501.top/Article/details/gt2vvemycnp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.haohaochexian.top/Article/details/gt2rtwlrirf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gogol.net.cn/Article/details/gt2wrnmhluu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qazvhxxj.html

[Q47] 与平均值比较
来源：http://dali.zhongyouzk.top/Article/details/gt2xbygymhi.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yonumen.top/Article/details/gt2ztltaqeu.html

[Q48] CTE 公用表表达式
来源：http://dali.cheryme.top/Article/details/gt2zlipdfez.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.redwolf501.top/Article/details/gt2zgnaosya.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cqqwz.cn/Article/details/gt2taoywjbv.html

[Q49] 更新单行
来源：http://dali.zhixingplan.top/Article/details/gt2wibkkqkd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj20258888.top/Article/details/gt2fgixpvjh.html

[Q50] 批量更新
来源：http://dali.fengsongda.top/Article/details/gt2rfexywzg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ivvv.top/Article/details/gt2sddphwfw.html

[Q51] 用子查询更新
来源：http://dali.fzhhl.top/Article/details/gt2bkcqzhqd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yanxiufei.cn/Article/details/gt2wffiwgma.html

[Q52] 删除指定行
来源：http://dali.jqgufenzy.top/Article/details/gt2ewekrsyx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gt2wscpapiw.html

[Q53] 按条件删除
来源：http://dali.zhoulong.xyz/Article/details/gt2dtnsmcfv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ehwqpu.com/Article/details/gt2oslnqzov.html

[Q54] 清空表
来源：http://dali.shzxlz.cn/Article/details/gt2ioocwpfc.html

TRUNCATE TABLE logs;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ylbonwca.html

[Q55] 排名（并列占位）
来源：http://dali.jiagoushi.top/Article/details/gt2hfpfwgka.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gt2uplbwfhm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cucudq.cn/Article/details/gt2eqvntfei.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj202588.top/Article/details/gt2nxkmhniz.html

[Q57] 行号
来源：http://dali.quarkkingdee.top/Article/details/gt2cpnuzhzs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtwimai.html

[Q58] 累计求和
来源：http://dali.smart0.xyz/Article/details/gt2jdrjsggp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2oewwdwmk.html

[Q59] 分组内累计
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aribouwt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2ucednzou.html

[Q60] 取上一行 / 下一行
来源：http://dali.hongshengwenyu.top/Article/details/gt2crzxnwqq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenzaomai.com/Article/details/gt2zkvvdmnt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2meiwatyg.html

[Q61] 移动平均
来源：http://dali.sysykeji.top/Article/details/gt2dwptqchu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2cdqrhwse.html

[Q62] 分组占比
来源：http://dali.cheryme.top/Article/details/gt2jmbhmynv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gt2hoahgavd.html

[Q63] 开启事务
来源：http://dali.yueranfly.top/Article/details/gt2inyqgzga.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenjidiqi.icu/Article/details/gt2ghghdvmx.html

[Q64] 提交事务
来源：http://dali.shangyingyoupin.top/Article/details/gt2drqfgnvm.html

COMMIT;
来源：http://dali.pengpengdd.cyou/Article/details/gt2nncrugft.html

[Q65] 回滚事务
来源：http://dali.aibaodan.cn/Article/details/gt2crwwbaei.html

ROLLBACK;
来源：http://dali.birdmap.top/Article/details/gt2uneivktc.html

[Q66] 行锁查询
来源：http://dali.iojbl.cn/Article/details/gt2powzcrfn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj20258.top/Article/details/gt2jtfuqyfe.html

[Q67] 设置隔离级别
来源：http://dali.dianchejie.cn/Article/details/gt2zotlbrkh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xziqi.cn/Article/details/gt2exqftfhs.html

[Q68] 保存点
来源：http://dali.quarkkingdee.top/Article/details/gt2koitpeww.html

SAVEPOINT sp1;
来源：http://dali.gaohongyu789.top/Article/details/gt2koqykxtm.html

ROLLBACK TO sp1;
来源：http://dali.gzhubu.top/Article/details/gt2svsynnys.html

[Q69] 查看执行计划
来源：http://dali.aibaodan.cn/Article/details/gt2zfbdrrey.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yangfankeji.com/Article/details/gt2fasdhoua.html

[Q70] 更新统计信息
来源：http://dali.guowangkeji.top/Article/details/gt2dplsyvqy.html

ANALYZE TABLE users;
来源：http://dali.yanxiufei.cn/Article/details/gt2kilicnpa.html

[Q71] 查看建表语句
来源：http://dali.sweek.top/Article/details/gt2kcwvcbeq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.snrcjt.cn/Article/details/gt2aorhaoos.html

[Q72] 查看索引
来源：http://dali.hysaishi.cn/Article/details/gt2hfyneqla.html

SHOW INDEX FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2hurktfqt.html

[Q73] 查看表状态
来源：http://dali.jqgfzy.top/Article/details/gt2iehuewlu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ekvzvctn.html

[Q74] 强制使用索引
来源：http://dali.sysykeji.top/Article/details/gt2duitsmlw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sweek.top/Article/details/gt2rbppqzpg.html

[Q75] 日期格式化
来源：http://dali.zycfv.cn/Article/details/gt2ttpcdweu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gt2xisqmmuw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cheryme.top/Article/details/gt2qhxirfqi.html

[Q76] 按天统计
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kwuedwke.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yanxiufei.cn/Article/details/gt2tfcghpqv.html

[Q77] 时间加减
来源：http://dali.yj20258.top/Article/details/gt2exbubizr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pengpengdd.cyou/Article/details/gt2ijntiupb.html

[Q78] 当前时间
来源：http://dali.sxryk.cn/Article/details/gt2owmeeujr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jlsjyb.cn/Article/details/gt2yftwjfzw.html

[Q79] 字符串拼接
来源：http://dali.haohaochexian.top/Article/details/gt2qnehvkgi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.guowangkeji.top/Article/details/gt2ybfmqtxn.html

[Q80] 字符串截取
来源：http://dali.yvedp.cn/Article/details/gt2jbazsrxc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xnnxipip.html

[Q81] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2vuxxsxsl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2barczbrk.html

[Q82] 字符长度与字节长度
来源：http://dali.zdqjudy.top/Article/details/gt2apenorts.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2ilcufdhw.html

[Q83] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gt2fqrvknbz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2smjwajar.html

[Q84] 去除首尾空格
来源：http://dali.havefunace.top/Article/details/gt2gjbdgptv.html

SELECT TRIM(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2vddsbpbb.html

[Q85] 数值取整
来源：http://dali.c1oappe.top/Article/details/gt2abjnhmhy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.svipenyu.cn/Article/details/gt2ymxtjvte.html

[Q86] 读取 JSON 字段
来源：http://dali.nanxuanxn.top/Article/details/gt2kuhishgi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sxryk.cn/Article/details/gt2nbsgqaid.html

[Q87] JSON 字段做条件
来源：http://dali.chenjidiqi.icu/Article/details/gt2ufjnhuey.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dtuiceot.html

[Q88] 行转列（条件聚合）
来源：http://dali.cheryme.top/Article/details/gt2uqoxlcis.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258.top/Article/details/gt2zprtmzgq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2aaefjczr.html

[Q89] 判断表是否存在
来源：http://dali.jqgfzy.top/Article/details/gt2zpfnfqqm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgufenzy.top/Article/details/gt2nsyerxzi.html

[Q90] 生成序号列
来源：http://dali.nanxinkj.top/Article/details/gt2sgefakzk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhiwuduotai.top/Article/details/gt2pscdywac.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2drulfiik.html

R. Bash 专题
来源：http://dali.dashuyun.cn/Article/details/gt2zqwijewe.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2jvnntebh.html

[R01] shebang 与严格模式
来源：http://dali.gotoacloud.top/Article/details/gt2wyxvhvrl.html

#!/usr/bin/env bash
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2efrosxyv.html

set -euo pipefail
来源：http://dali.tian-w.cn/Article/details/gt2dnbkhqoy.html

[R02] 变量赋值与使用
来源：http://dali.jianghu66.top/Article/details/gt2ozthhzzi.html

name="Tom"; echo "$name"
来源：http://dali.tian-w.cn/Article/details/gt2osqkmwgd.html

[R03] 只读变量
来源：http://dali.daxiang520.top/Article/details/gt2agflfyfi.html

readonly PI=3.14
来源：http://dali.xinyue.icu/Article/details/gt2epipucuh.html

[R04] 位置参数
来源：http://dali.cashguo.top/Article/details/gt2xllolopd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xinyue.icu/Article/details/gt2rmguzjhi.html

[R05] 参数默认值
来源：http://dali.smart0.xyz/Article/details/gt2zxtwjvqq.html

name="${1:-default}"
来源：http://dali.gogol.net.cn/Article/details/gt2ghsyqpzs.html

[R06] 判断命令是否存在
来源：http://dali.gotoacloud.top/Article/details/gt2yjqptewm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nerwiysu.html

[R07] if 判断文件
来源：http://dali.jlsjyb.cn/Article/details/gt2gcfjmtut.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yuxming.cn/Article/details/gt2iowmvzaj.html

[R08] 数值比较
来源：http://dali.daria6918.cn/Article/details/gt2evsmeebh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.9152youxi.cn/Article/details/gt2msywvico.html

[R09] 字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2hqvowwls.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.svipenyu.cn/Article/details/gt2xftwmwnv.html

[R10] 正则匹配
来源：http://dali.sxryk.cn/Article/details/gt2aoqqtult.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sxryk.cn/Article/details/gt2twbgjydq.html

[R11] case 多分支
来源：http://dali.yj20258888.top/Article/details/gt2styejksn.html

case "$1" in
来源：http://dali.tian-w.cn/Article/details/gt2qfzjjniq.html

start) echo "启动" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gt2tgkustrw.html

stop)  echo "停止" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nnldcuyv.html

*)     echo "未知命令" ;;
来源：http://dali.zhongyouzk.top/Article/details/gt2hathokpu.html

esac
来源：http://dali.daxiang520.top/Article/details/gt2hskkxlzj.html

[R12] for 遍历文件
来源：http://dali.ydzc1.top/Article/details/gt2nkmaebmb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guannengcc.top/Article/details/gt2mydpkjil.html

[R13] for 计数循环
来源：http://dali.yuanzhike.top/Article/details/gt2dzsnrlxq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gotoacloud.top/Article/details/gt2chmglpja.html

[R14] C 风格 for
来源：http://dali.svipenyu.cn/Article/details/gt2eseljckb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gt2fjcelbau.html

[R15] while 逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gt2uvnzlmjd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hfpthk.cn/Article/details/gt2pmfqmsvo.html

[R16] until 等待条件
来源：http://dali.yangfankeji.com/Article/details/gt2txckcoan.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gt2flwbjuws.html

[R17] 数组定义与取值
来源：http://dali.yj20258888.top/Article/details/gt2xfmijwbq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daria6918.cn/Article/details/gt2ixrjavwb.html

[R18] 遍历数组
来源：http://dali.smart0.xyz/Article/details/gt2xakjgxwl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hfpthk.cn/Article/details/gt2rtrbbqmz.html

[R19] 数组长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tgbrqywf.html

echo "${#arr[@]}"
来源：http://dali.jyoumei.cn/Article/details/gt2raqnfbtr.html

[R20] 关联数组（字典）
来源：http://dali.feifeiyinyue.top/Article/details/gt2adhujlbp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.vqdsnc.cn/Article/details/gt2bxezxrle.html

[R21] 字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gt2qtdvdpic.html

echo "${#s}"
来源：http://dali.jqgfzy.top/Article/details/gt2eruvvvml.html

[R22] 截取子串
来源：http://dali.nanxuanxn.top/Article/details/gt2tvzqoger.html

echo "${s:0:5}"
来源：http://dali.sxryk.cn/Article/details/gt2vnzicsez.html

[R23] 字符串替换
来源：http://dali.yanxiufei.cn/Article/details/gt2ycyrimcq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zprowwaj.html

[R24] 大小写转换
来源：http://dali.xziqi.cn/Article/details/gt2txrgoljc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yonumen.top/Article/details/gt2hktdipkt.html

[R25] 去后缀 / 去前缀
来源：http://dali.cdnleiting.top/Article/details/gt2pqmqflvi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jianghu66.top/Article/details/gt2mtzzmhty.html

[R26] 命令替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vvwvrtia.html

now=$(date +%F); echo "$now"
来源：http://dali.cdnleiting.top/Article/details/gt2nkvaybxh.html

[R27] 算术展开
来源：http://dali.zhongyouzk.top/Article/details/gt2cranwsjm.html

echo $((1 + 2 * 3))
来源：http://dali.hammf.cn/Article/details/gt2kxcbdzcm.html

[R28] 浮点运算
来源：http://dali.nanxinkj.top/Article/details/gt2ilclimyl.html

echo "scale=2; 10/3" | bc
来源：http://dali.hongshengwenyu.top/Article/details/gt2vhgskorp.html

[R29] 定义函数
来源：http://dali.cashguo.top/Article/details/gt2axyllgpw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.iojbl.cn/Article/details/gt2bwlhfdda.html

[R30] 函数返回状态码
来源：http://dali.zhengqikj.top/Article/details/gt2ypmrrits.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hnxiangtu.top/Article/details/gt2ezkuaqvk.html

[R31] 局部变量
来源：http://dali.jqgufenzy.top/Article/details/gt2uyhpsntb.html

f() { local x=1; echo "$x"; }
来源：http://dali.ppjwa.cn/Article/details/gt2exwxzyiv.html

[R32] 参数个数校验
来源：http://dali.wangshuangyany.cn/Article/details/gt2dbzbrsen.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yvedp.cn/Article/details/gt2ymotztkx.html

[R33] 捕获错误并提示行号
来源：http://dali.cdnleiting.top/Article/details/gt2nfzpeibh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhongyouzk.top/Article/details/gt2xieworop.html

[R34] 退出时清理
来源：http://dali.gzhubu.top/Article/details/gt2nceyeitt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gt2tzlwylgf.html

[R35] 后台执行并等待
来源：http://dali.jyoumei.cn/Article/details/gt2hhgkwizx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenjidiqi.icu/Article/details/gt2qfxnmynj.html

[R36] 并发执行多个任务
来源：http://dali.cheryme.top/Article/details/gt2yzekcmhj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daria6918.cn/Article/details/gt2nzpumvne.html

[R37] 把输出赋给变量
来源：http://dali.fzhhl.top/Article/details/gt2kgqwgshh.html

files=$(ls -1)
来源：http://dali.birdmap.top/Article/details/gt2pgapiyls.html

[R38] 管道串联
来源：http://dali.hnxiangtu.top/Article/details/gt2omimshus.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zdqjudy.top/Article/details/gt2zsufcrpm.html

[R39] 重定向标准输出与错误
来源：http://dali.sxryk.cn/Article/details/gt2zewpvdfc.html

cmd > out.log 2>&1
来源：http://dali.tianlin.xyz/Article/details/gt2htpfimer.html

[R40] 追加写日志
来源：http://dali.xinyue.icu/Article/details/gt2kwxalsrl.html

echo "log" >> out.log
来源：http://dali.wangshuangyany.cn/Article/details/gt2bsrozzlo.html

[R41] 丢弃输出
来源：http://dali.yvedp.cn/Article/details/gt2epzryzvt.html

cmd >/dev/null 2>&1
来源：http://dali.smart0.xyz/Article/details/gt2iiknemff.html

[R42] 输入重定向
来源：http://dali.meibo888.top/Article/details/gt2ecsnfpxw.html

wc -l < a.txt
来源：http://dali.nwbrower.top/Article/details/gt2kntiauui.html

[R43] 按名字查找文件
来源：http://dali.yvedp.cn/Article/details/gt2embryyfy.html

find . -name "*.log" -type f
来源：http://dali.wangshuangyany.cn/Article/details/gt2lzdtajds.html

[R44] 按修改时间查找
来源：http://dali.nanxinkj.top/Article/details/gt2offfqyho.html

find . -mtime -7 -type f
来源：http://dali.fengsongda.top/Article/details/gt2evfmmnhd.html

[R45] 批量删除
来源：http://dali.zhongyouzk.top/Article/details/gt2xkikowic.html

find . -name "*.tmp" -delete
来源：http://dali.feifeiyinyue.top/Article/details/gt2zfvdpjis.html

[R46] 递归替换文件内容
来源：http://dali.hammf.cn/Article/details/gt2mufaiehw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jiagoushi.top/Article/details/gt2vmwyjkci.html

[R47] sed 单行替换
来源：http://dali.nwbrower.top/Article/details/gt2meiegvct.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.316326.xyz/Article/details/gt2sdjkbdod.html

[R48] awk 取指定列
来源：http://dali.sxryk.cn/Article/details/gt2uprstocc.html

awk '{print $1, $3}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2cichlpmm.html

[R49] awk 带条件
来源：http://dali.jyoumei.cn/Article/details/gt2syrndpqz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yanxiufei.cn/Article/details/gt2nrblqkdl.html

[R50] awk 求和
来源：http://dali.yj20258888.top/Article/details/gt2rfsqnhbm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hywenlv.cn/Article/details/gt2srpfxyec.html

[R51] 排序去重取前几
来源：http://dali.cqqwz.cn/Article/details/gt2xnincuut.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sxryk.cn/Article/details/gt2lxyklmkh.html

[R52] 统计行数
来源：http://dali.yj20258888.top/Article/details/gt2hkpcgmal.html

wc -l a.txt
来源：http://dali.pycfn.com/Article/details/gt2ujtmbvrr.html

[R53] 查看文件头与实时尾
来源：http://dali.hammf.cn/Article/details/gt2advveygf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.316326.xyz/Article/details/gt2zqbhgqzq.html

[R54] 比较两个文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2nptqcfuc.html

diff a.txt b.txt
来源：http://dali.snrcjt.cn/Article/details/gt2lwwnzsgx.html

[R55] 压缩与解压
来源：http://dali.birdmap.top/Article/details/gt2pjdxpmby.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tianlin.xyz/Article/details/gt2imcdwcfh.html

[R56] 远程拷贝
来源：http://dali.cqqwz.cn/Article/details/gt2lknobpea.html

scp file user@host:/path/
来源：http://dali.yueranfly.top/Article/details/gt2rylketkh.html

[R57] 远程执行命令
来源：http://dali.jinqigfzy.top/Article/details/gt2szwumlqt.html


<!-- 参考信息 -->