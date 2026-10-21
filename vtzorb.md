代发 wailian999

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.snrcjt.cn/Article/details/gtfcbrvdma.html

[Q11] 一次插入多行
来源：http://dali.hnxiangtu.top/Article/details/gtmjyarlvn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.iojbl.cn/Article/details/gtrdpqmfgv.html

[Q12] 插入后取自增 ID
来源：http://dali.tanke756.top/Article/details/gtbmadhsvh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhongyouzk.top/Article/details/gtptvdluub.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jyoumei.cn/Article/details/gthsdgnonl.html

[Q13] 忽略重复插入
来源：http://dali.meibo888.top/Article/details/gtpuzahekh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xinyue.icu/Article/details/gtcuvnqdpe.html

[Q14] 存在则更新（upsert）
来源：http://dali.ybcxt.top/Article/details/gtrfgxqccf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shangyingyoupin.top/Article/details/gtzmqopzvu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xziqi.cn/Article/details/gtythdtoqu.html

[Q15] 查询全部
来源：http://dali.hongshengwenyu.top/Article/details/gtxpaqedho.html

SELECT * FROM users;
来源：http://dali.gotoacloud.top/Article/details/gttrcpjkxt.html

[Q16] 查询指定列
来源：http://dali.cdnleiting.top/Article/details/gtoqlieprj.html

SELECT id, name FROM users;
来源：http://dali.yvedp.cn/Article/details/gtifdvylcu.html

[Q17] 条件查询
来源：http://dali.yonumen.top/Article/details/gtfjojoaxb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgacbimj.html

[Q18] 模糊匹配
来源：http://dali.chenzaomai.com/Article/details/gtnylpnylu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinghuilouyu.cn/Article/details/gtsyqgskfj.html

[Q19] 范围查询
来源：http://dali.daria6918.cn/Article/details/gtfsojzfqh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuetiantiany.cn/Article/details/gteapgybja.html

[Q20] IN 列表
来源：http://dali.hammf.cn/Article/details/gtmgvqihis.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sxryk.cn/Article/details/gtencybfnx.html

[Q21] 空值判断
来源：http://dali.zhiwuduotai.top/Article/details/gtmheyjnxh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hysaishi.cn/Article/details/gtpejrihqd.html

[Q22] 排序
来源：http://dali.wangshuangyany.cn/Article/details/gtjkudiyuw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzebyvzer.html

[Q23] 分页
来源：http://dali.guowangkeji.top/Article/details/gtxpqwowvj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.9152youxi.cn/Article/details/gtxnzsjpsb.html

[Q24] 去重
来源：http://dali.mhx1999.top/Article/details/gthpgydypc.html

SELECT DISTINCT city FROM users;
来源：http://dali.cashguo.top/Article/details/gtxaowjvzk.html

[Q25] 只取前 N 条
来源：http://dali.zhoulong.xyz/Article/details/gtlygcetzh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.quarkkingdee.top/Article/details/gtvjwoclnr.html

[Q26] 计数
来源：http://dali.mhx1999.top/Article/details/gtatmquvuw.html

SELECT COUNT(*) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtmgyedojh.html

[Q27] 条件计数
来源：http://dali.jiagoushi.top/Article/details/gtndhpdbuc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.bjfxy.top/Article/details/gtskqhsokw.html

[Q28] 求和与平均
来源：http://dali.vqdsnc.cn/Article/details/gtawxqxwbk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtoppnvuvh.html

[Q29] 最大最小值
来源：http://dali.pengpengdd.cyou/Article/details/gtsjqfkwro.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtuynxdjyp.html

[Q30] 分组统计
来源：http://dali.sxryk.cn/Article/details/gtvddynxys.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gtrlnprxyt.html

[Q31] 分组后过滤
来源：http://dali.birdmap.top/Article/details/gtlstkyxmt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.9152youxi.cn/Article/details/gtajfahxet.html

[Q32] 分组拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtsecpgaak.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtckslybuv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenzaomai.com/Article/details/gtmcvcehys.html

[Q33] 多列分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtuopyxfpg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.birdmap.top/Article/details/gtdjbdhjpp.html

[Q34] 每组取第一条
来源：http://dali.snrcjt.cn/Article/details/gtvsogyemr.html

SELECT * FROM (
来源：http://dali.xziqi.cn/Article/details/gtjngxdiyd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhoulong.xyz/Article/details/gtekpmvwoh.html

) t WHERE rn = 1;
来源：http://dali.wangdashe.top/Article/details/gtdlruorsq.html

[Q35] 内连接
来源：http://dali.gotoacloud.top/Article/details/gtjrnbcgns.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xinyue.icu/Article/details/gtqtjvhaec.html

[Q36] 左连接
来源：http://dali.hongshengwenyu.top/Article/details/gthbjexfab.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yvedp.cn/Article/details/gtnuwkcoci.html

[Q37] 右连接
来源：http://dali.meibo888.top/Article/details/gtehohmmdb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuanzhike.top/Article/details/gtzozwybub.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.wangdashe.top/Article/details/gtnpcgpfch.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.redwolf501.top/Article/details/gtzllaqtiq.html

[Q39] 自连接（查上下级）
来源：http://dali.guannengcc.top/Article/details/gtgfrmdmes.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guannengcc.top/Article/details/gtaejwkeis.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zdqjudy.top/Article/details/gtntwippak.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hfpthk.cn/Article/details/gtvvtaipeg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yueranfly.top/Article/details/gtfdkrzinq.html

[Q41] 多表连接
来源：http://dali.hywenlv.cn/Article/details/gtxvfeicvj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ybcxt.top/Article/details/gtteoykrhm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjectxen.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hfpthk.cn/Article/details/gtgijluxzm.html

[Q42] 连接条件附加过滤
来源：http://dali.wangdashe.top/Article/details/gtvmvbtmys.html

SELECT u.name, o.amount FROM users u
来源：http://dali.mhx1999.top/Article/details/gtfmufnzdb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ehwqpu.com/Article/details/gtkxqadgyu.html

[Q43] 标量子查询
来源：http://dali.tanke756.top/Article/details/gtghasurpb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkmhwcpu.html

[Q44] IN 子查询
来源：http://dali.bjfxy.top/Article/details/gtkypbcfjz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gzhubu.top/Article/details/gtoeadjudg.html

[Q45] EXISTS 判断存在
来源：http://dali.cashguo.top/Article/details/gtijvqaknm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jyoumei.cn/Article/details/gtpcbyjijs.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhktihco.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.havefunace.top/Article/details/gtnkzlpvck.html

[Q47] 与平均值比较
来源：http://dali.chenjidiqi.icu/Article/details/gtkxgthlcj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gogol.net.cn/Article/details/gtzhsngnxn.html

[Q48] CTE 公用表表达式
来源：http://dali.jinqigufen.top/Article/details/gtsccmpqcv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhongyouzk.top/Article/details/gtykpwxqsb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.0kj1m.cn/Article/details/gtasfdrujt.html

[Q49] 更新单行
来源：http://dali.cucudq.cn/Article/details/gtbjtoxflo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhdzqoge.html

[Q50] 批量更新
来源：http://dali.yangfankeji.com/Article/details/gtrqfapgkn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnmvdvxt.html

[Q51] 用子查询更新
来源：http://dali.aibaodan.cn/Article/details/gtfrwvoikw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhjvpxij.html

[Q52] 删除指定行
来源：http://dali.sysykeji.top/Article/details/gtzrhwvomu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhongyouzk.top/Article/details/gtbjjwficm.html

[Q53] 按条件删除
来源：http://dali.gzhubu.top/Article/details/gtawuwdklm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhixingplan.top/Article/details/gthvqmwmkd.html

[Q54] 清空表
来源：http://dali.hammf.cn/Article/details/gtmbqotkbx.html

TRUNCATE TABLE logs;
来源：http://dali.zhiwuduotai.top/Article/details/gtzhgtbytp.html

[Q55] 排名（并列占位）
来源：http://dali.quarkkingdee.top/Article/details/gtkushxmnv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sweek.top/Article/details/gtsqgxbnej.html

[Q56] 密集排名（并列不占位）
来源：http://dali.mhx1999.top/Article/details/gtmhwjonny.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gtaeifatii.html

[Q57] 行号
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmptseul.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258.top/Article/details/gttxixhhfj.html

[Q58] 累计求和
来源：http://dali.chenjidiqi.icu/Article/details/gtmxcozwdq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtefmkakwd.html

[Q59] 分组内累计
来源：http://dali.yongpay.top/Article/details/gttpwxsnuu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtwawsjyna.html

[Q60] 取上一行 / 下一行
来源：http://dali.zycfv.cn/Article/details/gtafhhacgl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.0kj1m.cn/Article/details/gtjlmqfhez.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtuhkdgecv.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gtigbigqaa.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtrxtohlbi.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gtumnhtrmc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gtpdqfeets.html

[Q63] 开启事务
来源：http://dali.zhongyouzk.top/Article/details/gtywbuygvt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhongyouzk.top/Article/details/gtyemzyztk.html

[Q64] 提交事务
来源：http://dali.cqqwz.cn/Article/details/gttgxigjyh.html

COMMIT;
来源：http://dali.xuetiantiany.cn/Article/details/gtvvrpmbej.html

[Q65] 回滚事务
来源：http://dali.yj20258888.top/Article/details/gtxhsbxces.html

ROLLBACK;
来源：http://dali.shangyingyoupin.top/Article/details/gtrmexdmxb.html

[Q66] 行锁查询
来源：http://dali.chenlongwang.top/Article/details/gtgtipskvc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hfpthk.cn/Article/details/gtgyvxript.html

[Q67] 设置隔离级别
来源：http://dali.quarkkingdee.top/Article/details/gtpctgakvv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jiagoushi.top/Article/details/gttlonvhcb.html

[Q68] 保存点
来源：http://dali.yj202588.top/Article/details/gtgwacduwg.html

SAVEPOINT sp1;
来源：http://dali.xuetiantiany.cn/Article/details/gtmgaisovm.html

ROLLBACK TO sp1;
来源：http://dali.jinqigufen.top/Article/details/gtngduugdm.html

[Q69] 查看执行计划
来源：http://dali.wangdashe.top/Article/details/gtaljtmeug.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gogol.net.cn/Article/details/gtputcvziv.html

[Q70] 更新统计信息
来源：http://dali.quarkkingdee.top/Article/details/gtbnbpxbng.html

ANALYZE TABLE users;
来源：http://dali.hongshengwenyu.top/Article/details/gtkwnluipj.html

[Q71] 查看建表语句
来源：http://dali.snrcjt.cn/Article/details/gtpkugxaui.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xuetiantiany.cn/Article/details/gtbginrukv.html

[Q72] 查看索引
来源：http://dali.cucudq.cn/Article/details/gtvgecwghq.html

SHOW INDEX FROM users;
来源：http://dali.pycfn.com/Article/details/gtwgnpczts.html

[Q73] 查看表状态
来源：http://dali.yj20258.top/Article/details/gtzkldevgq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xziqi.cn/Article/details/gtadccmffa.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gtcfakvokn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yvedp.cn/Article/details/gtkfyqikxw.html

[Q75] 日期格式化
来源：http://dali.xylfe.cn/Article/details/gtzehhihde.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtclxddpyf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nwbrower.top/Article/details/gtifbqdpmu.html

[Q76] 按天统计
来源：http://dali.jqgufenzy.top/Article/details/gtbcxxhdoi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dianchejie.cn/Article/details/gtixyqqpql.html

[Q77] 时间加减
来源：http://dali.xziqi.cn/Article/details/gtthjtamik.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.iojbl.cn/Article/details/gteffgmtbw.html

[Q78] 当前时间
来源：http://dali.havefunace.top/Article/details/gtqcpnsrff.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ehwqpu.com/Article/details/gtvtpcraqj.html

[Q79] 字符串拼接
来源：http://dali.chenjidiqi.icu/Article/details/gtmgxmvmef.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yvedp.cn/Article/details/gtkdaggnbg.html

[Q80] 字符串截取
来源：http://dali.svipenyu.cn/Article/details/gtkgxtiwdz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtyhxkgyfq.html

[Q81] 字符串替换
来源：http://dali.zhengqikj.top/Article/details/gtjuhlkbaq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtpmyxwnbz.html

[Q82] 字符长度与字节长度
来源：http://dali.haohaochexian.top/Article/details/gtjkjjaikm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtthwabhmz.html

[Q83] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gtpgaxrzpt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtuahioukt.html

[Q84] 去除首尾空格
来源：http://dali.0kj1m.cn/Article/details/gtnonpxord.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gthltvhxpi.html

[Q85] 数值取整
来源：http://dali.nwbrower.top/Article/details/gtdwokaywi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sufxvd.cn/Article/details/gtwtsdqnif.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258.top/Article/details/gtueuiwuod.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ppjwa.cn/Article/details/gttxegzjyt.html

[Q87] JSON 字段做条件
来源：http://dali.zhongyouzk.top/Article/details/gtecqmrims.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.snrcjt.cn/Article/details/gtuawafyir.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgfzy.top/Article/details/gttljqnhsi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnxiangtu.top/Article/details/gtpnztevrf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbsiqiusg.html

[Q89] 判断表是否存在
来源：http://dali.yueranfly.top/Article/details/gtmxbjlano.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daxiang520.top/Article/details/gtmnkkijiy.html

[Q90] 生成序号列
来源：http://dali.quarkkingdee.top/Article/details/gtnhvwoasi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xinyue.icu/Article/details/gtbonysqhp.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtqbvdkmju.html

R. Bash 专题
来源：http://dali.nwbrower.top/Article/details/gtarhywdpf.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtqtahwbps.html

[R01] shebang 与严格模式
来源：http://dali.dashuyun.cn/Article/details/gtmdqilunw.html

#!/usr/bin/env bash
来源：http://dali.pengpengdd.cyou/Article/details/gthleemdpw.html

set -euo pipefail
来源：http://dali.jinyuanbaomall.cn/Article/details/gtooelqota.html

[R02] 变量赋值与使用
来源：http://dali.316326.xyz/Article/details/gtbhmdruvc.html

name="Tom"; echo "$name"
来源：http://dali.ybcxt.top/Article/details/gtamwexkbp.html

[R03] 只读变量
来源：http://dali.guowangkeji.top/Article/details/gtituocylu.html

readonly PI=3.14
来源：http://dali.jqgfzy.top/Article/details/gtazfmvbvo.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gtzyugqaun.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxiskpuz.html

[R05] 参数默认值
来源：http://dali.hnxiangtu.top/Article/details/gthywhhzsc.html

name="${1:-default}"
来源：http://dali.yj202588.top/Article/details/gtjqucdzwi.html

[R06] 判断命令是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gtncnmmxmu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gthbgcereb.html

[R07] if 判断文件
来源：http://dali.cheryme.top/Article/details/gtvrhgolyp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yvedp.cn/Article/details/gtfgkrpzrv.html

[R08] 数值比较
来源：http://dali.ehwqpu.com/Article/details/gtcibpmchy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yongpay.top/Article/details/gtcgnqjfyp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gtfmoboqba.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.andypj.xyz/Article/details/gtsiqsbbwp.html

[R10] 正则匹配
来源：http://dali.ehwqpu.com/Article/details/gtqnayybza.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258.top/Article/details/gtmbgerbef.html

[R11] case 多分支
来源：http://dali.zhengqikj.top/Article/details/gtivnknhju.html

case "$1" in
来源：http://dali.jinghuilouyu.cn/Article/details/gtaivvgzxu.html

start) echo "启动" ;;
来源：http://dali.dianchejie.cn/Article/details/gttbadtwfh.html

stop)  echo "停止" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gthuntdvig.html

*)     echo "未知命令" ;;
来源：http://dali.dashuyun.cn/Article/details/gticjaiwhy.html

esac
来源：http://dali.yongpay.top/Article/details/gtoqyieqsl.html

[R12] for 遍历文件
来源：http://dali.chenzaomai.com/Article/details/gtnrjbhzta.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cucudq.cn/Article/details/gtsywbfttr.html

[R13] for 计数循环
来源：http://dali.tian-w.cn/Article/details/gtlgkcimwq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gtilsdzopp.html

[R14] C 风格 for
来源：http://dali.0kj1m.cn/Article/details/gtykwbqvqv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtvmeyelbd.html

[R15] while 逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtiewmsxhd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.andypj.xyz/Article/details/gtbghgpgue.html

[R16] until 等待条件
来源：http://dali.nanxinkj.top/Article/details/gtxzbujmbs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gtlnuiwlhx.html

[R17] 数组定义与取值
来源：http://dali.hysaishi.cn/Article/details/gtqpnepspo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gotoacloud.top/Article/details/gtmpfbklup.html

[R18] 遍历数组
来源：http://dali.zhongyouzk.top/Article/details/gtlztxwpzg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.iojbl.cn/Article/details/gtddrmuvmz.html

[R19] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gtkrbmktzb.html

echo "${#arr[@]}"
来源：http://dali.fengsongda.top/Article/details/gtinimdcvz.html

[R20] 关联数组（字典）
来源：http://dali.ivvv.top/Article/details/gtbygaphby.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hfpthk.cn/Article/details/gttikamcpe.html

[R21] 字符串长度
来源：http://dali.sweek.top/Article/details/gtyfgwxudi.html

echo "${#s}"
来源：http://dali.smart0.xyz/Article/details/gtgwclgaqf.html

[R22] 截取子串
来源：http://dali.daria6918.cn/Article/details/gtloimkjmv.html

echo "${s:0:5}"
来源：http://dali.cucudq.cn/Article/details/gtbosntkzu.html

[R23] 字符串替换
来源：http://dali.gotoacloud.top/Article/details/gtsuzvnuag.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hnqzz.top/Article/details/gtpnavtxmo.html

[R24] 大小写转换
来源：http://dali.iojbl.cn/Article/details/gtbkvcmqhs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gotoacloud.top/Article/details/gtrcnxrywp.html

[R25] 去后缀 / 去前缀
来源：http://dali.aizwys.cn/Article/details/gtkbobjuyc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cucudq.cn/Article/details/gtqeikhxkl.html

[R26] 命令替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnzzimzy.html

now=$(date +%F); echo "$now"
来源：http://dali.smart0.xyz/Article/details/gtundjrjhk.html

[R27] 算术展开
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofnawzew.html

echo $((1 + 2 * 3))
来源：http://dali.zhiwuduotai.top/Article/details/gtcjlzlbgi.html

[R28] 浮点运算
来源：http://dali.sysykeji.top/Article/details/gtnqlqlmdp.html

echo "scale=2; 10/3" | bc
来源：http://dali.aibaodan.cn/Article/details/gtmagunntl.html

[R29] 定义函数
来源：http://dali.wangdashe.top/Article/details/gtyijktrll.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gaohongyu789.top/Article/details/gtrhqltnpz.html

[R30] 函数返回状态码
来源：http://dali.tanke756.top/Article/details/gteudngunr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzjfrboe.html

[R31] 局部变量
来源：http://dali.yj20258.top/Article/details/gtzuggcjkj.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangdashe.top/Article/details/gtpnxahhqm.html

[R32] 参数个数校验
来源：http://dali.ehwqpu.com/Article/details/gthjewwizx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yanxiufei.cn/Article/details/gtwvcyypkf.html

[R33] 捕获错误并提示行号
来源：http://dali.shuidangran.top/Article/details/gtvunbdeje.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hongshengwenyu.top/Article/details/gtjmdahnev.html

[R34] 退出时清理
来源：http://dali.tianlin.xyz/Article/details/gteaoglfau.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.c1oappe.top/Article/details/gtsodvyitf.html

[R35] 后台执行并等待
来源：http://dali.havefunace.top/Article/details/gtjontjcef.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hammf.cn/Article/details/gtgkzqhdqf.html

[R36] 并发执行多个任务
来源：http://dali.sufxvd.cn/Article/details/gtohjszaxt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxinkj.top/Article/details/gtgodgwjip.html

[R37] 把输出赋给变量
来源：http://dali.xuetiantiany.cn/Article/details/gtdnkjtjdi.html

files=$(ls -1)
来源：http://dali.hysaishi.cn/Article/details/gtsziomuxk.html

[R38] 管道串联
来源：http://dali.yj20258.top/Article/details/gtbyrqtxcd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.bjfxy.top/Article/details/gtjfkafzmi.html

[R39] 重定向标准输出与错误
来源：http://dali.zhoulong.xyz/Article/details/gttjjkykac.html

cmd > out.log 2>&1
来源：http://dali.0kj1m.cn/Article/details/gtrhisghhq.html

[R40] 追加写日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoyghzlru.html

echo "log" >> out.log
来源：http://dali.fzhhl.top/Article/details/gttwvxghne.html

[R41] 丢弃输出
来源：http://dali.shzxlz.cn/Article/details/gtnuzbrnnj.html

cmd >/dev/null 2>&1
来源：http://dali.daria6918.cn/Article/details/gtahtekqhv.html

[R42] 输入重定向
来源：http://dali.zycfv.cn/Article/details/gtceunzpmi.html

wc -l < a.txt
来源：http://dali.chenzaomai.com/Article/details/gtlsascsos.html

[R43] 按名字查找文件
来源：http://dali.nanxinkj.top/Article/details/gthcdrsxen.html

find . -name "*.log" -type f
来源：http://dali.xuetiantiany.cn/Article/details/gtazstdewd.html

[R44] 按修改时间查找
来源：http://dali.yanxiufei.cn/Article/details/gtwjiyylxq.html

find . -mtime -7 -type f
来源：http://dali.svipenyu.cn/Article/details/gtpiwtevgg.html

[R45] 批量删除
来源：http://dali.havefunace.top/Article/details/gtfvzejzkj.html

find . -name "*.tmp" -delete
来源：http://dali.kuanghao11.cn/Article/details/gtdbnhnwfz.html

[R46] 递归替换文件内容
来源：http://dali.quarkkingdee.top/Article/details/gteuramnjq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shzxlz.cn/Article/details/gtdbseuwky.html

[R47] sed 单行替换
来源：http://dali.yj20258888.top/Article/details/gtkbmqzadw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hammf.cn/Article/details/gtrddmmgbp.html

[R48] awk 取指定列
来源：http://dali.nanxuanxn.top/Article/details/gtmkwvyssf.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtdpsnlgif.html

[R49] awk 带条件
来源：http://dali.kuanghao11.cn/Article/details/gtppnzhwww.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tanke756.top/Article/details/gtrkeakfli.html

[R50] awk 求和
来源：http://dali.tianlin.xyz/Article/details/gtvjkgqvqt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ivvv.top/Article/details/gtkxvymkce.html

[R51] 排序去重取前几
来源：http://dali.aizwys.cn/Article/details/gtjmnooudz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqmxohdq.html

[R52] 统计行数
来源：http://dali.hnqzz.top/Article/details/gtwgallaxi.html

wc -l a.txt
来源：http://dali.chenzaomai.com/Article/details/gtmddjtogy.html

[R53] 查看文件头与实时尾
来源：http://dali.daxiang520.top/Article/details/gtpvxapooo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yanxiufei.cn/Article/details/gtvkxcsoqc.html

[R54] 比较两个文件
来源：http://dali.sufxvd.cn/Article/details/gtbazacwxk.html

diff a.txt b.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtusjuvkui.html

[R55] 压缩与解压
来源：http://dali.hywenlv.cn/Article/details/gtibrkvdir.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sysykeji.top/Article/details/gtznbtcwdn.html

[R56] 远程拷贝
来源：http://dali.jqgufenzy.top/Article/details/gtmjerlxsb.html

scp file user@host:/path/
来源：http://dali.birdmap.top/Article/details/gtnbuzyjcp.html

[R57] 远程执行命令
来源：http://dali.quarkkingdee.top/Article/details/gtfdccjawo.html

ssh user@host 'uptime'
来源：http://dali.chenzaomai.com/Article/details/gtbexbvldq.html

[R58] 下载文件
来源：http://dali.hongshengwenyu.top/Article/details/gtqeswvztp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shangyingyoupin.top/Article/details/gtnpcasspk.html

[R59] 发 POST JSON
来源：http://dali.bjfxy.top/Article/details/gtzxcptgdf.html


<!-- 参考信息 -->