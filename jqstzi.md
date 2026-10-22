代发 wailian999

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xuanzx.com/Article/details/gtiitejwae.html

[Q09] 创建唯一索引
来源：http://dali.snrcjt.cn/Article/details/gtbiqhbhia.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.svipenyu.cn/Article/details/gtpdvwqrzf.html

[Q10] 插入单行
来源：http://dali.ehwqpu.com/Article/details/gtiexilviv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ppjwa.cn/Article/details/gtaysmxfyq.html

[Q11] 一次插入多行
来源：http://dali.yj202588.top/Article/details/gtmnvfjnzz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jqgfzy.top/Article/details/gtnsxxrwnl.html

[Q12] 插入后取自增 ID
来源：http://dali.316326.xyz/Article/details/gtzxftpjir.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ppjwa.cn/Article/details/gtxeprpqit.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sufxvd.cn/Article/details/gtysawrdak.html

[Q13] 忽略重复插入
来源：http://dali.yuanzhike.top/Article/details/gtbcqsqmur.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtzqktgknp.html

[Q14] 存在则更新（upsert）
来源：http://dali.fzhhl.top/Article/details/gtvubnbgnb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjtyayzc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cashguo.top/Article/details/gtvftleuab.html

[Q15] 查询全部
来源：http://dali.yuanzhike.top/Article/details/gtolrichec.html

SELECT * FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvbjvdqj.html

[Q16] 查询指定列
来源：http://dali.jinqigufen.top/Article/details/gtmiefduwu.html

SELECT id, name FROM users;
来源：http://dali.c1oappe.top/Article/details/gtopzqgvvr.html

[Q17] 条件查询
来源：http://dali.shangyingyoupin.top/Article/details/gtgoicznya.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hnqzz.top/Article/details/gtjckfifnv.html

[Q18] 模糊匹配
来源：http://dali.chenlongwang.top/Article/details/gtpadtvkwu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.vqdsnc.cn/Article/details/gtdvokqpzz.html

[Q19] 范围查询
来源：http://dali.iojbl.cn/Article/details/gtjmqplkzc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tanke756.top/Article/details/gtzudqwlew.html

[Q20] IN 列表
来源：http://dali.chenlongwang.top/Article/details/gtucckncan.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sufxvd.cn/Article/details/gtjkpwjshq.html

[Q21] 空值判断
来源：http://dali.hysaishi.cn/Article/details/gtncnjocyz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.mhx1999.top/Article/details/gtncieyhmy.html

[Q22] 排序
来源：http://dali.guowangkeji.top/Article/details/gthhskfgmw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.bjfxy.top/Article/details/gtciqsfzpb.html

[Q23] 分页
来源：http://dali.cheryme.top/Article/details/gtjizfudfi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jianghu66.top/Article/details/gtnxsjlebp.html

[Q24] 去重
来源：http://dali.yangfankeji.com/Article/details/gthtnvvuhz.html

SELECT DISTINCT city FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtnsvrobib.html

[Q25] 只取前 N 条
来源：http://dali.chenjidiqi.icu/Article/details/gtfplmehuc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylpsgfsx.html

[Q26] 计数
来源：http://dali.yueranfly.top/Article/details/gtrkzgmhxa.html

SELECT COUNT(*) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtnrzyurmf.html

[Q27] 条件计数
来源：http://dali.jinghuilouyu.cn/Article/details/gtrghlzagj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtutzknvxb.html

[Q28] 求和与平均
来源：http://dali.shzxlz.cn/Article/details/gtlhobxxdj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtmxeooejz.html

[Q29] 最大最小值
来源：http://dali.chenlongwang.top/Article/details/gtaerymlpd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ivvv.top/Article/details/gtvzjfuuzr.html

[Q30] 分组统计
来源：http://dali.hnxiangtu.top/Article/details/gtewzbntcc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gtskfkrbaw.html

[Q31] 分组后过滤
来源：http://dali.cdnleiting.top/Article/details/gtsbaxyrjm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhalexfb.html

[Q32] 分组拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtterlqczw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gtwrahchzo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jyoumei.cn/Article/details/gtzpfxjvqk.html

[Q33] 多列分组
来源：http://dali.chenlongwang.top/Article/details/gtzpblakqk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cqqwz.cn/Article/details/gthsschmmk.html

[Q34] 每组取第一条
来源：http://dali.gaohongyu789.top/Article/details/gtvcxelzgq.html

SELECT * FROM (
来源：http://dali.hnqzz.top/Article/details/gtsdwpmuto.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sufxvd.cn/Article/details/gtvmwmebyy.html

) t WHERE rn = 1;
来源：http://dali.yuxming.cn/Article/details/gtsdmszdas.html

[Q35] 内连接
来源：http://dali.mhx1999.top/Article/details/gtanbnchbi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhiwuduotai.top/Article/details/gtldvtidty.html

[Q36] 左连接
来源：http://dali.dianchejie.cn/Article/details/gtdexibdwv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhiwuduotai.top/Article/details/gtdgdjwlwv.html

[Q37] 右连接
来源：http://dali.tian-w.cn/Article/details/gtofrhulab.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tanke756.top/Article/details/gtsazaense.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.guowangkeji.top/Article/details/gteytjcyyw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tian-w.cn/Article/details/gttaipyorp.html

[Q39] 自连接（查上下级）
来源：http://dali.zhiwuduotai.top/Article/details/gtnxbjxrub.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.bjfxy.top/Article/details/gtirnjzarn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gogol.net.cn/Article/details/gtgcjwwkvm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj202588.top/Article/details/gtaehcdufw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.dianchejie.cn/Article/details/gttmzrawmo.html

[Q41] 多表连接
来源：http://dali.zdqjudy.top/Article/details/gtdaebezse.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrowukqpf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ehwqpu.com/Article/details/gteymcdqnl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xinyue.icu/Article/details/gtxumcwvrd.html

[Q42] 连接条件附加过滤
来源：http://dali.316326.xyz/Article/details/gtnnchaqig.html

SELECT u.name, o.amount FROM users u
来源：http://dali.9152youxi.cn/Article/details/gtrfurhtuc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tianlin.xyz/Article/details/gtgpsxbppx.html

[Q43] 标量子查询
来源：http://dali.tian-w.cn/Article/details/gtnwltowxo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nwbrower.top/Article/details/gtwzyzilvk.html

[Q44] IN 子查询
来源：http://dali.zhongyouzk.top/Article/details/gtbufcvrws.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenlongwang.top/Article/details/gtswjnnazv.html

[Q45] EXISTS 判断存在
来源：http://dali.quarkkingdee.top/Article/details/gtrxzpbvkz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gtdgnykyav.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fzhhl.top/Article/details/gtbredkoij.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tianlin.xyz/Article/details/gthdihmzfh.html

[Q47] 与平均值比较
来源：http://dali.hfpthk.cn/Article/details/gtjreuhsaf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258888.top/Article/details/gtyouhxxtj.html

[Q48] CTE 公用表表达式
来源：http://dali.snrcjt.cn/Article/details/gtoqffvezi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aibaodan.cn/Article/details/gtvzaiyxeh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.0kj1m.cn/Article/details/gtjgxwwhyu.html

[Q49] 更新单行
来源：http://dali.sxryk.cn/Article/details/gtsowqassc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyqtanss.html

[Q50] 批量更新
来源：http://dali.xziqi.cn/Article/details/gtlgdfhcvg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cheryme.top/Article/details/gtgvknybqh.html

[Q51] 用子查询更新
来源：http://dali.yj202588.top/Article/details/gtphyuhrcs.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.haohaochexian.top/Article/details/gtcaxlnwiw.html

[Q52] 删除指定行
来源：http://dali.cashguo.top/Article/details/gtnnrgkwzp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258.top/Article/details/gtoppzevrf.html

[Q53] 按条件删除
来源：http://dali.nwbrower.top/Article/details/gtkeimdvnk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gotoacloud.top/Article/details/gtmcfgcpqn.html

[Q54] 清空表
来源：http://dali.quarkkingdee.top/Article/details/gtyxcocfru.html

TRUNCATE TABLE logs;
来源：http://dali.guannengcc.top/Article/details/gtgrwyidlm.html

[Q55] 排名（并列占位）
来源：http://dali.hnqzz.top/Article/details/gtbhdegsmj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gotoacloud.top/Article/details/gtmppredrs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj20258.top/Article/details/gthapuizft.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkewlwtfe.html

[Q57] 行号
来源：http://dali.zhengqikj.top/Article/details/gtjyjxukky.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tian-w.cn/Article/details/gtrheepbym.html

[Q58] 累计求和
来源：http://dali.xylfe.cn/Article/details/gtebjvihac.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtwshvaboa.html

[Q59] 分组内累计
来源：http://dali.cqqwz.cn/Article/details/gtqvrjtkje.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtzhhwhxps.html

[Q60] 取上一行 / 下一行
来源：http://dali.shzxlz.cn/Article/details/gtzmlyoxrp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrtwnnoa.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtrbouwigj.html

[Q61] 移动平均
来源：http://dali.fengsongda.top/Article/details/gtqzeofzwi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtznsznqdq.html

[Q62] 分组占比
来源：http://dali.ehwqpu.com/Article/details/gttbymywkv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gtrjsagwmt.html

[Q63] 开启事务
来源：http://dali.havefunace.top/Article/details/gtrufjruvj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjnteirr.html

[Q64] 提交事务
来源：http://dali.daria6918.cn/Article/details/gtbcycnckr.html

COMMIT;
来源：http://dali.cdnleiting.top/Article/details/gtntzuqzxx.html

[Q65] 回滚事务
来源：http://dali.wangshuangyany.cn/Article/details/gtkdwyofvq.html

ROLLBACK;
来源：http://dali.kuanghao11.cn/Article/details/gthgahocqt.html

[Q66] 行锁查询
来源：http://dali.gzhubu.top/Article/details/gtadnuiyzn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj202588.top/Article/details/gtkuwaoggh.html

[Q67] 设置隔离级别
来源：http://dali.mhx1999.top/Article/details/gtgehqingq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pycfn.com/Article/details/gtfzzenlwj.html

[Q68] 保存点
来源：http://dali.chenzaomai.com/Article/details/gtwcxsfedg.html

SAVEPOINT sp1;
来源：http://dali.yj202588.top/Article/details/gtivoophbq.html

ROLLBACK TO sp1;
来源：http://dali.smart0.xyz/Article/details/gtirbqarnw.html

[Q69] 查看执行计划
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfhopdat.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yuanzhike.top/Article/details/gtmcvcplpf.html

[Q70] 更新统计信息
来源：http://dali.cqqwz.cn/Article/details/gtxejamrng.html

ANALYZE TABLE users;
来源：http://dali.ydzc1.top/Article/details/gtpkdwasol.html

[Q71] 查看建表语句
来源：http://dali.chenzaomai.com/Article/details/gtipkuxaeu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shuidangran.top/Article/details/gttezannkt.html

[Q72] 查看索引
来源：http://dali.ydzc1.top/Article/details/gthykylgrw.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfquynqom.html

[Q73] 查看表状态
来源：http://dali.ppjwa.cn/Article/details/gtotqdhspa.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zdqjudy.top/Article/details/gtfszlbokx.html

[Q74] 强制使用索引
来源：http://dali.daria6918.cn/Article/details/gtciyqgmuu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.9152youxi.cn/Article/details/gtmcermpdc.html

[Q75] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gttzwjpjqz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtnntyfonz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.feifeiyinyue.top/Article/details/gtpmjaladv.html

[Q76] 按天统计
来源：http://dali.quarkkingdee.top/Article/details/gtttqzhoug.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.mhx1999.top/Article/details/gtsaxdqgxc.html

[Q77] 时间加减
来源：http://dali.pengpengdd.cyou/Article/details/gtntsvegcw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhixingplan.top/Article/details/gtuxgeqglb.html

[Q78] 当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtxygrntbi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigfzy.top/Article/details/gtcgcsnnzq.html

[Q79] 字符串拼接
来源：http://dali.yvedp.cn/Article/details/gtsefnjepq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yanxiufei.cn/Article/details/gtlvuzvzfe.html

[Q80] 字符串截取
来源：http://dali.nanxinkj.top/Article/details/gtfxhowksr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtyufchvmr.html

[Q81] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gtxufbpzze.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pycfn.com/Article/details/gtvczdtbbu.html

[Q82] 字符长度与字节长度
来源：http://dali.birdmap.top/Article/details/gtmnbpcqwn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtzbvfypom.html

[Q83] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gtutczsbup.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtphbbgjnb.html

[Q84] 去除首尾空格
来源：http://dali.shuidangran.top/Article/details/gterznqgjw.html

SELECT TRIM(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtrzfaygqz.html

[Q85] 数值取整
来源：http://dali.zhiwuduotai.top/Article/details/gtxqrfngmw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jlsjyb.cn/Article/details/gtlmlnfgok.html

[Q86] 读取 JSON 字段
来源：http://dali.zhongyouzk.top/Article/details/gtsdcnymqx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dianchejie.cn/Article/details/gteianeynk.html

[Q87] JSON 字段做条件
来源：http://dali.iojbl.cn/Article/details/gtscgazxrv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhongyouzk.top/Article/details/gtzozzavsd.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgfzy.top/Article/details/gthbrgorwp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinqigfzy.top/Article/details/gtfahaezrb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtasecpwmi.html

[Q89] 判断表是否存在
来源：http://dali.tian-w.cn/Article/details/gtegzklpff.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xinyue.icu/Article/details/gtisbvmdjm.html

[Q90] 生成序号列
来源：http://dali.yj20258.top/Article/details/gtuszvrwjn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.guannengcc.top/Article/details/gtigsggswm.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtuivtcutl.html

R. Bash 专题
来源：http://dali.yonumen.top/Article/details/gtqjlxcmga.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtvfpsgftd.html

[R01] shebang 与严格模式
来源：http://dali.tian-w.cn/Article/details/gtpoboogzg.html

#!/usr/bin/env bash
来源：http://dali.sysykeji.top/Article/details/gtuonplhnl.html

set -euo pipefail
来源：http://dali.vqdsnc.cn/Article/details/gtnugevrfs.html

[R02] 变量赋值与使用
来源：http://dali.chenlongwang.top/Article/details/gtnkxexrku.html

name="Tom"; echo "$name"
来源：http://dali.cashguo.top/Article/details/gtdagrikzi.html

[R03] 只读变量
来源：http://dali.xuanzx.com/Article/details/gtbzebjodz.html

readonly PI=3.14
来源：http://dali.yangfankeji.com/Article/details/gtvmjifhek.html

[R04] 位置参数
来源：http://dali.sufxvd.cn/Article/details/gtxtlghzgv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ybcxt.top/Article/details/gtntonecfa.html

[R05] 参数默认值
来源：http://dali.jiagoushi.top/Article/details/gtyctzybmn.html

name="${1:-default}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbasydzbj.html

[R06] 判断命令是否存在
来源：http://dali.hywenlv.cn/Article/details/gtcrvztbcy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cdnleiting.top/Article/details/gtkwtwomzb.html

[R07] if 判断文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqwweukj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgfzy.top/Article/details/gtxghrnomp.html

[R08] 数值比较
来源：http://dali.ydzc1.top/Article/details/gtsfruvyih.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.svipenyu.cn/Article/details/gtoxuvectz.html

[R09] 字符串比较
来源：http://dali.guowangkeji.top/Article/details/gtmuyjthjb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtbkftpjko.html

[R10] 正则匹配
来源：http://dali.pycfn.com/Article/details/gtkdgkcydj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.svipenyu.cn/Article/details/gtaafsejbq.html

[R11] case 多分支
来源：http://dali.jianghu66.top/Article/details/gtxwwnedjz.html

case "$1" in
来源：http://dali.yj202588.top/Article/details/gtlimvfple.html

start) echo "启动" ;;
来源：http://dali.yj202588.top/Article/details/gtnydoaysz.html

stop)  echo "停止" ;;
来源：http://dali.chenzaomai.com/Article/details/gtscnkguur.html

*)     echo "未知命令" ;;
来源：http://dali.jiagoushi.top/Article/details/gtjsuhgqpn.html

esac
来源：http://dali.yj202588.top/Article/details/gtooqagmcu.html

[R12] for 遍历文件
来源：http://dali.zhongyouzk.top/Article/details/gtechqrzju.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pycfn.com/Article/details/gtqknipwyr.html

[R13] for 计数循环
来源：http://dali.yuxming.cn/Article/details/gthjzvgaxa.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gtardsilhn.html

[R14] C 风格 for
来源：http://dali.cheryme.top/Article/details/gtjrelvxgy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gtghokqjmw.html

[R15] while 逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtgjngarny.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sweek.top/Article/details/gtcbtitsjt.html

[R16] until 等待条件
来源：http://dali.chenlongwang.top/Article/details/gtkmtxkfrw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zdqjudy.top/Article/details/gtbfsbzqit.html

[R17] 数组定义与取值
来源：http://dali.daria6918.cn/Article/details/gtcfzijnfr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258.top/Article/details/gtgxbepjay.html

[R18] 遍历数组
来源：http://dali.ehwqpu.com/Article/details/gtbnggnjkk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtwczgnzey.html

[R19] 数组长度
来源：http://dali.shzxlz.cn/Article/details/gthoxpxwop.html

echo "${#arr[@]}"
来源：http://dali.9152youxi.cn/Article/details/gtuqkqwwkg.html

[R20] 关联数组（字典）
来源：http://dali.xuetiantiany.cn/Article/details/gtsyyfxwwq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.316326.xyz/Article/details/gtrwplbdtf.html

[R21] 字符串长度
来源：http://dali.shangyingyoupin.top/Article/details/gtdjijuuqj.html

echo "${#s}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzrxmaolk.html

[R22] 截取子串
来源：http://dali.zycfv.cn/Article/details/gtjnosgwmk.html

echo "${s:0:5}"
来源：http://dali.jqgufenzy.top/Article/details/gtputitbrw.html

[R23] 字符串替换
来源：http://dali.tian-w.cn/Article/details/gtomkzczmq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenzaomai.com/Article/details/gtzdxusrpa.html

[R24] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtmmwbbbhb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yueranfly.top/Article/details/gtrnmzogbi.html

[R25] 去后缀 / 去前缀
来源：http://dali.snrcjt.cn/Article/details/gtgjkbddkl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cqqwz.cn/Article/details/gtcjzzpqxc.html

[R26] 命令替换
来源：http://dali.sysykeji.top/Article/details/gtarrechbt.html

now=$(date +%F); echo "$now"
来源：http://dali.fzhhl.top/Article/details/gtszfexlxo.html

[R27] 算术展开
来源：http://dali.hysaishi.cn/Article/details/gthnmtcnrz.html

echo $((1 + 2 * 3))
来源：http://dali.ivvv.top/Article/details/gtbxlqirgm.html

[R28] 浮点运算
来源：http://dali.zhongyouzk.top/Article/details/gtkcnqfpbl.html

echo "scale=2; 10/3" | bc
来源：http://dali.9152youxi.cn/Article/details/gtjunzedce.html

[R29] 定义函数
来源：http://dali.shzxlz.cn/Article/details/gtaykyqkbw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nanxinkj.top/Article/details/gtfngrtktk.html

[R30] 函数返回状态码
来源：http://dali.0kj1m.cn/Article/details/gtwnczykqg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ybcxt.top/Article/details/gthnrgxpud.html

[R31] 局部变量
来源：http://dali.smart0.xyz/Article/details/gtzqkcnmua.html

f() { local x=1; echo "$x"; }
来源：http://dali.zycfv.cn/Article/details/gtjkkzbqdq.html

[R32] 参数个数校验
来源：http://dali.xinyue.icu/Article/details/gtghwvihgc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtxalwdlhf.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgfzy.top/Article/details/gtmwxwhdep.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gaohongyu789.top/Article/details/gtfvvrvkxe.html

[R34] 退出时清理
来源：http://dali.yonumen.top/Article/details/gtzdehuhvr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258.top/Article/details/gtedlynrnw.html

[R35] 后台执行并等待
来源：http://dali.aibaodan.cn/Article/details/gtaohuibhn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tianlin.xyz/Article/details/gtvqowoqdr.html

[R36] 并发执行多个任务
来源：http://dali.gogol.net.cn/Article/details/gtpcylgymh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yongpay.top/Article/details/gtrosjmdha.html

[R37] 把输出赋给变量
来源：http://dali.guowangkeji.top/Article/details/gtjokipduc.html

files=$(ls -1)
来源：http://dali.daria6918.cn/Article/details/gtqifxdmdj.html

[R38] 管道串联
来源：http://dali.cqqwz.cn/Article/details/gthoswhuap.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fzhhl.top/Article/details/gtqsweeyhb.html

[R39] 重定向标准输出与错误
来源：http://dali.yuanzhike.top/Article/details/gtbsogdgeh.html

cmd > out.log 2>&1
来源：http://dali.ydzc1.top/Article/details/gteqqnqqpx.html

[R40] 追加写日志
来源：http://dali.0kj1m.cn/Article/details/gtjmwquszx.html

echo "log" >> out.log
来源：http://dali.dianchejie.cn/Article/details/gttzqdwwpx.html

[R41] 丢弃输出
来源：http://dali.ppjwa.cn/Article/details/gtkuiobfaz.html

cmd >/dev/null 2>&1
来源：http://dali.0kj1m.cn/Article/details/gtwlncoqxp.html

[R42] 输入重定向
来源：http://dali.jqgufenzy.top/Article/details/gtlvgnniul.html

wc -l < a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtrqwrmuuu.html

[R43] 按名字查找文件
来源：http://dali.sysykeji.top/Article/details/gtlkxmmkbz.html

find . -name "*.log" -type f
来源：http://dali.cashguo.top/Article/details/gtcrfcacla.html

[R44] 按修改时间查找
来源：http://dali.vqdsnc.cn/Article/details/gtexlfrkno.html

find . -mtime -7 -type f
来源：http://dali.nanxinkj.top/Article/details/gtqtrbpywh.html

[R45] 批量删除
来源：http://dali.tanke756.top/Article/details/gthucghowi.html

find . -name "*.tmp" -delete
来源：http://dali.xylfe.cn/Article/details/gtncwezinm.html

[R46] 递归替换文件内容
来源：http://dali.mhx1999.top/Article/details/gtmmvbnjwv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.kuanghao11.cn/Article/details/gtubdjsvpo.html

[R47] sed 单行替换
来源：http://dali.sxryk.cn/Article/details/gtouaihgwb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258888.top/Article/details/gtnyzoiwke.html

[R48] awk 取指定列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozjiydxb.html

awk '{print $1, $3}' a.txt
来源：http://dali.yonumen.top/Article/details/gtqoaganuj.html

[R49] awk 带条件
来源：http://dali.vqdsnc.cn/Article/details/gtzbsncqmh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sysykeji.top/Article/details/gtsrzlkpvx.html

[R50] awk 求和
来源：http://dali.xylfe.cn/Article/details/gtagrdqcuj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gtugsulddt.html

[R51] 排序去重取前几
来源：http://dali.mhx1999.top/Article/details/gttlgodahb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daria6918.cn/Article/details/gtiewkbjdr.html

[R52] 统计行数
来源：http://dali.zdqjudy.top/Article/details/gttptsotsl.html

wc -l a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtobrnjipt.html

[R53] 查看文件头与实时尾
来源：http://dali.havefunace.top/Article/details/gtgwazowtd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ivvv.top/Article/details/gtwclsuzwf.html

[R54] 比较两个文件
来源：http://dali.chenjidiqi.icu/Article/details/gtniholdxb.html

diff a.txt b.txt
来源：http://dali.gzhubu.top/Article/details/gtsgcdfzmk.html

[R55] 压缩与解压
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcgpwfum.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gogol.net.cn/Article/details/gtinuyptki.html

[R56] 远程拷贝
来源：http://dali.chenjidiqi.icu/Article/details/gtkvemyich.html

scp file user@host:/path/
来源：http://dali.jqgufenzy.top/Article/details/gtvrvqfvve.html

[R57] 远程执行命令
来源：http://dali.jianghu66.top/Article/details/gtzxyafrrv.html


<!-- 参考信息 -->