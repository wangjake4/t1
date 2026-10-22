代发 wailian999

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.0kj1m.cn/Article/details/gtqhvcmfsr.html

[Q09] 创建唯一索引
来源：http://dali.shzxlz.cn/Article/details/gtnjqibsny.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.iojbl.cn/Article/details/gtlkpcwjjk.html

[Q10] 插入单行
来源：http://dali.9152youxi.cn/Article/details/gtrbhdpume.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ehwqpu.com/Article/details/gtbzpksozk.html

[Q11] 一次插入多行
来源：http://dali.haohaochexian.top/Article/details/gtojrnjhex.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aibaodan.cn/Article/details/gtxwimrjvm.html

[Q12] 插入后取自增 ID
来源：http://dali.zhiwuduotai.top/Article/details/gtwwspncga.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnqzz.top/Article/details/gtzhiiowha.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.smart0.xyz/Article/details/gtdizvcxem.html

[Q13] 忽略重复插入
来源：http://dali.shangyingyoupin.top/Article/details/gtilcppjku.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nanxinkj.top/Article/details/gtuuexlpif.html

[Q14] 存在则更新（upsert）
来源：http://dali.redwolf501.top/Article/details/gtbslsqfio.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yanxiufei.cn/Article/details/gtmclzaweh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cqqwz.cn/Article/details/gtzcoyyvpw.html

[Q15] 查询全部
来源：http://dali.c1oappe.top/Article/details/gtxiogmmpn.html

SELECT * FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtrjkrapuw.html

[Q16] 查询指定列
来源：http://dali.gzhubu.top/Article/details/gtiuxordtv.html

SELECT id, name FROM users;
来源：http://dali.yj20258.top/Article/details/gtjwbfgcif.html

[Q17] 条件查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilmdhcdj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sufxvd.cn/Article/details/gtpzfscwtt.html

[Q18] 模糊匹配
来源：http://dali.jlsjyb.cn/Article/details/gtjwwijgsm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shangyingyoupin.top/Article/details/gtrxpqzcre.html

[Q19] 范围查询
来源：http://dali.zhengqikj.top/Article/details/gtrovozuiq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sweek.top/Article/details/gtubbjlvyi.html

[Q20] IN 列表
来源：http://dali.ehwqpu.com/Article/details/gtvpvuiged.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbxbhhyo.html

[Q21] 空值判断
来源：http://dali.jqgufenzy.top/Article/details/gtqyrzbxnc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.c1oappe.top/Article/details/gtvcqabsws.html

[Q22] 排序
来源：http://dali.xuetiantiany.cn/Article/details/gtfkhdxihd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenzaomai.com/Article/details/gtzkuueldw.html

[Q23] 分页
来源：http://dali.jinqigufen.top/Article/details/gtjeyvgcyo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shangyingyoupin.top/Article/details/gtzqephyzx.html

[Q24] 去重
来源：http://dali.shzxlz.cn/Article/details/gtvvynosbj.html

SELECT DISTINCT city FROM users;
来源：http://dali.jianghu66.top/Article/details/gthqtqatcw.html

[Q25] 只取前 N 条
来源：http://dali.gogol.net.cn/Article/details/gtnwhnbrmz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenlongwang.top/Article/details/gtoxfimbgb.html

[Q26] 计数
来源：http://dali.xylfe.cn/Article/details/gtzhrwvdzm.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvtafexf.html

[Q27] 条件计数
来源：http://dali.yj20258.top/Article/details/gtbyrrildo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ybcxt.top/Article/details/gtufhuinwc.html

[Q28] 求和与平均
来源：http://dali.xuanzx.com/Article/details/gthzldtzxn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhzlpger.html

[Q29] 最大最小值
来源：http://dali.sufxvd.cn/Article/details/gtzatrkdsa.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtnsuuavng.html

[Q30] 分组统计
来源：http://dali.hfpthk.cn/Article/details/gtoreajatd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gtjgdufzxk.html

[Q31] 分组后过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtkeknjvpz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jiagoushi.top/Article/details/gtzzsxpprj.html

[Q32] 分组拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gtwhzealam.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gtgndqfmon.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hfpthk.cn/Article/details/gtsxweyueo.html

[Q33] 多列分组
来源：http://dali.andypj.xyz/Article/details/gtqdgirjoj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.daria6918.cn/Article/details/gtempjoqwo.html

[Q34] 每组取第一条
来源：http://dali.guowangkeji.top/Article/details/gttskpxfzc.html

SELECT * FROM (
来源：http://dali.zhiwuduotai.top/Article/details/gtnfwogqfh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.bjfxy.top/Article/details/gtlyrhywpp.html

) t WHERE rn = 1;
来源：http://dali.nanxinkj.top/Article/details/gtipwpvmxs.html

[Q35] 内连接
来源：http://dali.meibo888.top/Article/details/gtzqmmjurc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cdnleiting.top/Article/details/gtgnltfxsz.html

[Q36] 左连接
来源：http://dali.tianlin.xyz/Article/details/gtayrhkgpm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.birdmap.top/Article/details/gtalqllkly.html

[Q37] 右连接
来源：http://dali.xziqi.cn/Article/details/gtduyyblac.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhnrvney.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nwbrower.top/Article/details/gtgfblbiao.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.quarkkingdee.top/Article/details/gtodwwrtzg.html

[Q39] 自连接（查上下级）
来源：http://dali.hammf.cn/Article/details/gtartuthto.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guowangkeji.top/Article/details/gtrnhjnkzz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xuanzx.com/Article/details/gtcasaqeaf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hammf.cn/Article/details/gtdrgjhtue.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthbfrbgn.html

[Q41] 多表连接
来源：http://dali.cashguo.top/Article/details/gtgsrkowsh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.mhx1999.top/Article/details/gtgfgyaome.html

JOIN users u ON u.id = o.user_id
来源：http://dali.9152youxi.cn/Article/details/gtrgbxghfc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cqqwz.cn/Article/details/gtqjtcuiwi.html

[Q42] 连接条件附加过滤
来源：http://dali.gogol.net.cn/Article/details/gtorgyjlru.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigufen.top/Article/details/gtysnfrgtm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.kuanghao11.cn/Article/details/gtnysayvts.html

[Q43] 标量子查询
来源：http://dali.cashguo.top/Article/details/gtkytmhqqi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttghdppbh.html

[Q44] IN 子查询
来源：http://dali.zhiwuduotai.top/Article/details/gtydqdfjyz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cdnleiting.top/Article/details/gtiksssruw.html

[Q45] EXISTS 判断存在
来源：http://dali.xuetiantiany.cn/Article/details/gtduamxllx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daria6918.cn/Article/details/gtrwruemrr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ydzc1.top/Article/details/gtjtpomirz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gtbhbnyhqf.html

[Q47] 与平均值比较
来源：http://dali.smart0.xyz/Article/details/gteykwihog.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.bjfxy.top/Article/details/gtqefqrbvk.html

[Q48] CTE 公用表表达式
来源：http://dali.hywenlv.cn/Article/details/gtirawjxhp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.fengsongda.top/Article/details/gtmidgfnvo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.kuanghao11.cn/Article/details/gtptacokmj.html

[Q49] 更新单行
来源：http://dali.shzxlz.cn/Article/details/gthjrsmwql.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yangfankeji.com/Article/details/gtunxnmats.html

[Q50] 批量更新
来源：http://dali.sysykeji.top/Article/details/gtczgdgliw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.c1oappe.top/Article/details/gtxknlsunr.html

[Q51] 用子查询更新
来源：http://dali.guowangkeji.top/Article/details/gtvzqoaozo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cashguo.top/Article/details/gticetbtoj.html

[Q52] 删除指定行
来源：http://dali.xziqi.cn/Article/details/gtolspaswb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nwbrower.top/Article/details/gttsjakmqg.html

[Q53] 按条件删除
来源：http://dali.sysykeji.top/Article/details/gthpnsezes.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ehwqpu.com/Article/details/gtocxwonzo.html

[Q54] 清空表
来源：http://dali.ybcxt.top/Article/details/gtqjbnfwti.html

TRUNCATE TABLE logs;
来源：http://dali.jinghuilouyu.cn/Article/details/gtiywqvalz.html

[Q55] 排名（并列占位）
来源：http://dali.chenlongwang.top/Article/details/gtlubvzjtj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nwbrower.top/Article/details/gtkwfernta.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnqzz.top/Article/details/gtnaixurbi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gtdvcthlzr.html

[Q57] 行号
来源：http://dali.yj20258888.top/Article/details/gtqbthpwrn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtmeuhmwdv.html

[Q58] 累计求和
来源：http://dali.yonumen.top/Article/details/gtlupcdqeh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtpnydjqnb.html

[Q59] 分组内累计
来源：http://dali.guowangkeji.top/Article/details/gtivsneaqc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtprkekjvl.html

[Q60] 取上一行 / 下一行
来源：http://dali.hongshengwenyu.top/Article/details/gtcqjyjasc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenzaomai.com/Article/details/gtuicqfnpu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtdqtskbuk.html

[Q61] 移动平均
来源：http://dali.zhiwuduotai.top/Article/details/gtbjawhxho.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtzqcsbjar.html

[Q62] 分组占比
来源：http://dali.fzhhl.top/Article/details/gtwpcsoigm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtgaulqfmc.html

[Q63] 开启事务
来源：http://dali.pycfn.com/Article/details/gtlrmvlktb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjygchxah.html

[Q64] 提交事务
来源：http://dali.cashguo.top/Article/details/gtgyazruka.html

COMMIT;
来源：http://dali.nanxuanxn.top/Article/details/gtcpwapows.html

[Q65] 回滚事务
来源：http://dali.haohaochexian.top/Article/details/gtqhlhaoep.html

ROLLBACK;
来源：http://dali.sxryk.cn/Article/details/gteklyhdzp.html

[Q66] 行锁查询
来源：http://dali.chenzaomai.com/Article/details/gtimzridna.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhengqikj.top/Article/details/gtxxijsmjm.html

[Q67] 设置隔离级别
来源：http://dali.nwbrower.top/Article/details/gtgqugejgm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmypyznzz.html

[Q68] 保存点
来源：http://dali.tian-w.cn/Article/details/gtjuihgyxp.html

SAVEPOINT sp1;
来源：http://dali.smart0.xyz/Article/details/gtskhiimpe.html

ROLLBACK TO sp1;
来源：http://dali.shzxlz.cn/Article/details/gtkqovyvdi.html

[Q69] 查看执行计划
来源：http://dali.wangdashe.top/Article/details/gtpbdhgspw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hammf.cn/Article/details/gtfkwocrec.html

[Q70] 更新统计信息
来源：http://dali.meibo888.top/Article/details/gtrhatkfkv.html

ANALYZE TABLE users;
来源：http://dali.hfpthk.cn/Article/details/gtyemjxpwo.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gtrrevuwsz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.0kj1m.cn/Article/details/gteesanhhv.html

[Q72] 查看索引
来源：http://dali.0kj1m.cn/Article/details/gtplgnczcf.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlxtkppl.html

[Q73] 查看表状态
来源：http://dali.cqqwz.cn/Article/details/gtvidduoxa.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.aizwys.cn/Article/details/gtwnnyxaxr.html

[Q74] 强制使用索引
来源：http://dali.yangfankeji.com/Article/details/gtsmmyzjzh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yonumen.top/Article/details/gthxltsoxh.html

[Q75] 日期格式化
来源：http://dali.cashguo.top/Article/details/gtpgbpopiw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtaiodagup.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.guowangkeji.top/Article/details/gtqzrcuprw.html

[Q76] 按天统计
来源：http://dali.smart0.xyz/Article/details/gtecercrkr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gzhubu.top/Article/details/gtntxggfou.html

[Q77] 时间加减
来源：http://dali.birdmap.top/Article/details/gtlzksecfk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhixingplan.top/Article/details/gttsarvuhv.html

[Q78] 当前时间
来源：http://dali.gogol.net.cn/Article/details/gtcnatqaxp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cdnleiting.top/Article/details/gtwxsepjxj.html

[Q79] 字符串拼接
来源：http://dali.wangdashe.top/Article/details/gttolcbdfi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ehwqpu.com/Article/details/gttqegcsdz.html

[Q80] 字符串截取
来源：http://dali.svipenyu.cn/Article/details/gtbvwjxfmp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtudzdmcat.html

[Q81] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gtbhyfbycg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtsjomkyfw.html

[Q82] 字符长度与字节长度
来源：http://dali.smart0.xyz/Article/details/gtcbevyzfo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtudgxiuri.html

[Q83] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gtmrfuappr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfpyxchn.html

[Q84] 去除首尾空格
来源：http://dali.xinyue.icu/Article/details/gtpycvxekq.html

SELECT TRIM(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gthuypbcnx.html

[Q85] 数值取整
来源：http://dali.guannengcc.top/Article/details/gtpswebodc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenlongwang.top/Article/details/gtydetsike.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigufen.top/Article/details/gthmiqpbmf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zdqjudy.top/Article/details/gtbobriohw.html

[Q87] JSON 字段做条件
来源：http://dali.tian-w.cn/Article/details/gtkeqerobd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hnxiangtu.top/Article/details/gtxcxnfjgu.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangdashe.top/Article/details/gtmazytkal.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ydzc1.top/Article/details/gtznxjqypl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpyuyfrur.html

[Q89] 判断表是否存在
来源：http://dali.havefunace.top/Article/details/gtpddwqfnv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hnqzz.top/Article/details/gtmcnlviwq.html

[Q90] 生成序号列
来源：http://dali.chenjidiqi.icu/Article/details/gtcfojjzyg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gogol.net.cn/Article/details/gtalkydylq.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtqtaaglqg.html

R. Bash 专题
来源：http://dali.shuidangran.top/Article/details/gtyplqcwhe.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtdzmgkhna.html

[R01] shebang 与严格模式
来源：http://dali.ppjwa.cn/Article/details/gtwechwrqe.html

#!/usr/bin/env bash
来源：http://dali.iojbl.cn/Article/details/gtlxwkahay.html

set -euo pipefail
来源：http://dali.xziqi.cn/Article/details/gtxqmqqqhr.html

[R02] 变量赋值与使用
来源：http://dali.chenzaomai.com/Article/details/gtblevcxda.html

name="Tom"; echo "$name"
来源：http://dali.birdmap.top/Article/details/gtpegsxiow.html

[R03] 只读变量
来源：http://dali.zycfv.cn/Article/details/gteuywllis.html

readonly PI=3.14
来源：http://dali.xinyue.icu/Article/details/gtznsndgrg.html

[R04] 位置参数
来源：http://dali.cashguo.top/Article/details/gtcaeyprlb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.mhx1999.top/Article/details/gtlyvdbcxr.html

[R05] 参数默认值
来源：http://dali.sysykeji.top/Article/details/gtqcpzcttn.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gtynguiylx.html

[R06] 判断命令是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtebsebqom.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dianchejie.cn/Article/details/gtlluuvxhj.html

[R07] if 判断文件
来源：http://dali.hnxiangtu.top/Article/details/gtjmkmjrml.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yuxming.cn/Article/details/gtjzuwhoat.html

[R08] 数值比较
来源：http://dali.yongpay.top/Article/details/gttzvrtpcr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yangfankeji.com/Article/details/gtkzdqjbtm.html

[R09] 字符串比较
来源：http://dali.sweek.top/Article/details/gtbdjozrnu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tanke756.top/Article/details/gtswykjkdk.html

[R10] 正则匹配
来源：http://dali.jlsjyb.cn/Article/details/gtjggppnqa.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sufxvd.cn/Article/details/gtjueohsaq.html

[R11] case 多分支
来源：http://dali.nanxinkj.top/Article/details/gtrodsuiji.html

case "$1" in
来源：http://dali.yj20258.top/Article/details/gtipnmbouq.html

start) echo "启动" ;;
来源：http://dali.xuanzx.com/Article/details/gthnskkapl.html

stop)  echo "停止" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gtnptoytsc.html

*)     echo "未知命令" ;;
来源：http://dali.yuxming.cn/Article/details/gtalodwvjv.html

esac
来源：http://dali.sysykeji.top/Article/details/gtklfhjocj.html

[R12] for 遍历文件
来源：http://dali.zhiwuduotai.top/Article/details/gtnsfxbpkl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gtrxmcznuy.html

[R13] for 计数循环
来源：http://dali.gotoacloud.top/Article/details/gtravwmely.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtumyjxhds.html

[R14] C 风格 for
来源：http://dali.andypj.xyz/Article/details/gtnlijpneo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fzhhl.top/Article/details/gtlbmmditn.html

[R15] while 逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtmwxwvoes.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sxryk.cn/Article/details/gtmdgjfxql.html

[R16] until 等待条件
来源：http://dali.ybcxt.top/Article/details/gttlnzitol.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gthkbvsfll.html

[R17] 数组定义与取值
来源：http://dali.ehwqpu.com/Article/details/gtispmqzfr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pycfn.com/Article/details/gtrpbmdxks.html

[R18] 遍历数组
来源：http://dali.shangyingyoupin.top/Article/details/gtfyaaxmcq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtdlvvxwzx.html

[R19] 数组长度
来源：http://dali.xinyue.icu/Article/details/gtjatekknq.html

echo "${#arr[@]}"
来源：http://dali.zhongyouzk.top/Article/details/gteamximsj.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrsmvahu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yvedp.cn/Article/details/gthpujozta.html

[R21] 字符串长度
来源：http://dali.yj20258.top/Article/details/gtioclpgey.html

echo "${#s}"
来源：http://dali.nwbrower.top/Article/details/gtlgosfytx.html

[R22] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gtddwvbhfj.html

echo "${s:0:5}"
来源：http://dali.jinqigufen.top/Article/details/gtsfwdikxx.html

[R23] 字符串替换
来源：http://dali.ppjwa.cn/Article/details/gtnjsajdde.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yonumen.top/Article/details/gtfttqbpbu.html

[R24] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gtkvxtoemt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zdqjudy.top/Article/details/gtnururebb.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj202588.top/Article/details/gtyvmnxjsz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.daxiang520.top/Article/details/gtosqzsiqk.html

[R26] 命令替换
来源：http://dali.9152youxi.cn/Article/details/gtfjywwbgl.html

now=$(date +%F); echo "$now"
来源：http://dali.hfpthk.cn/Article/details/gtowgrmaxk.html

[R27] 算术展开
来源：http://dali.chenlongwang.top/Article/details/gthomxvrfz.html

echo $((1 + 2 * 3))
来源：http://dali.zhengqikj.top/Article/details/gtmrscjral.html

[R28] 浮点运算
来源：http://dali.yuanzhike.top/Article/details/gtitjumttg.html

echo "scale=2; 10/3" | bc
来源：http://dali.cucudq.cn/Article/details/gtlmiqohyh.html

[R29] 定义函数
来源：http://dali.xuanzx.com/Article/details/gtxxhwlcof.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258888.top/Article/details/gtfuhssocp.html

[R30] 函数返回状态码
来源：http://dali.yueranfly.top/Article/details/gtwojcohxe.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenzaomai.com/Article/details/gtqbwcpycp.html

[R31] 局部变量
来源：http://dali.yj20258888.top/Article/details/gtvndolwyc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtzddjfcng.html

[R32] 参数个数校验
来源：http://dali.iojbl.cn/Article/details/gtyltrurxp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gtefkzdzdt.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigfzy.top/Article/details/gtfmmsjsoa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cdnleiting.top/Article/details/gttfyymzpn.html

[R34] 退出时清理
来源：http://dali.hnxiangtu.top/Article/details/gtxgolyyji.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gthktsioei.html

[R35] 后台执行并等待
来源：http://dali.sxryk.cn/Article/details/gtgdkwwwcu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.9152youxi.cn/Article/details/gtzebtbefz.html

[R36] 并发执行多个任务
来源：http://dali.sweek.top/Article/details/gtedywowjd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnqzz.top/Article/details/gtnxgjeutj.html

[R37] 把输出赋给变量
来源：http://dali.meibo888.top/Article/details/gtrsplvcan.html

files=$(ls -1)
来源：http://dali.jinqigfzy.top/Article/details/gttamwvwof.html

[R38] 管道串联
来源：http://dali.gaohongyu789.top/Article/details/gtsveltroq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ydzc1.top/Article/details/gtugngxwgs.html

[R39] 重定向标准输出与错误
来源：http://dali.yvedp.cn/Article/details/gtwszbdurg.html

cmd > out.log 2>&1
来源：http://dali.dashuyun.cn/Article/details/gtjgwxtuew.html

[R40] 追加写日志
来源：http://dali.snrcjt.cn/Article/details/gtytycmhjm.html

echo "log" >> out.log
来源：http://dali.zycfv.cn/Article/details/gtlrdkkzur.html

[R41] 丢弃输出
来源：http://dali.yueranfly.top/Article/details/gtkbevylxj.html

cmd >/dev/null 2>&1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngmuvrhz.html

[R42] 输入重定向
来源：http://dali.fzhhl.top/Article/details/gtwqspofky.html

wc -l < a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtmowhregd.html

[R43] 按名字查找文件
来源：http://dali.tianlin.xyz/Article/details/gtkrxfpsqx.html

find . -name "*.log" -type f
来源：http://dali.zhixingplan.top/Article/details/gtuvygnuiu.html

[R44] 按修改时间查找
来源：http://dali.pycfn.com/Article/details/gtixrupkuq.html

find . -mtime -7 -type f
来源：http://dali.vqdsnc.cn/Article/details/gthdaccbpj.html

[R45] 批量删除
来源：http://dali.cdnleiting.top/Article/details/gtlbjuxkwm.html

find . -name "*.tmp" -delete
来源：http://dali.havefunace.top/Article/details/gtnevacfce.html

[R46] 递归替换文件内容
来源：http://dali.haohaochexian.top/Article/details/gtytahtlhg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yanxiufei.cn/Article/details/gtduseuaux.html

[R47] sed 单行替换
来源：http://dali.meibo888.top/Article/details/gtpcwqwzqn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtlqgfypyq.html

[R48] awk 取指定列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtirypjpib.html

awk '{print $1, $3}' a.txt
来源：http://dali.jqgfzy.top/Article/details/gtlbqdghbm.html

[R49] awk 带条件
来源：http://dali.jinqigfzy.top/Article/details/gtynybiosv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhiwuduotai.top/Article/details/gtltemhtzb.html

[R50] awk 求和
来源：http://dali.zdqjudy.top/Article/details/gtzvtpluvy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtniylhivp.html

[R51] 排序去重取前几
来源：http://dali.shangyingyoupin.top/Article/details/gtpraulcvq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yongpay.top/Article/details/gtvklehneg.html

[R52] 统计行数
来源：http://dali.hysaishi.cn/Article/details/gtrkdzneph.html

wc -l a.txt
来源：http://dali.redwolf501.top/Article/details/gtsmragdmo.html

[R53] 查看文件头与实时尾
来源：http://dali.ydzc1.top/Article/details/gtnsmoydrm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yangfankeji.com/Article/details/gtesxowvmc.html

[R54] 比较两个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtjubqrdpx.html

diff a.txt b.txt
来源：http://dali.gzhubu.top/Article/details/gtpjbhihum.html

[R55] 压缩与解压
来源：http://dali.guannengcc.top/Article/details/gtjwuqrufd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jqgufenzy.top/Article/details/gtrudolquq.html

[R56] 远程拷贝
来源：http://dali.jinqigfzy.top/Article/details/gtintpwwyv.html

scp file user@host:/path/
来源：http://dali.xuanzx.com/Article/details/gtrrfhklgf.html

[R57] 远程执行命令
来源：http://dali.feifeiyinyue.top/Article/details/gtwtaobxtj.html


<!-- 参考信息 -->