代发 wailian999

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.guowangkeji.top/Article/details/gt2xhnulrpq.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mastnsdg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dianchejie.cn/Article/details/gt2zkzloffz.html

[Q12] 插入后取自增 ID
来源：http://dali.vqdsnc.cn/Article/details/gt2ddqqewtx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.andypj.xyz/Article/details/gt2bervbjoy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.quarkkingdee.top/Article/details/gt2pqbljzrg.html

[Q13] 忽略重复插入
来源：http://dali.nwbrower.top/Article/details/gt2isafsmwd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gt2dlmnkvcg.html

[Q14] 存在则更新（upsert）
来源：http://dali.pengpengdd.cyou/Article/details/gt2akoasthi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cheryme.top/Article/details/gt2kdtiyijr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xylfe.cn/Article/details/gt2fyzjcmtb.html

[Q15] 查询全部
来源：http://dali.daxiang520.top/Article/details/gt2ckwjzovt.html

SELECT * FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2ksnrqfmh.html

[Q16] 查询指定列
来源：http://dali.zhixingplan.top/Article/details/gt2nxgqvrnz.html

SELECT id, name FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2tvzjuhkr.html

[Q17] 条件查询
来源：http://dali.tianlin.xyz/Article/details/gt2ndmbvszx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tian-w.cn/Article/details/gt2ccwmwrjr.html

[Q18] 模糊匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2icmlxjjx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yonumen.top/Article/details/gt2xnryntwp.html

[Q19] 范围查询
来源：http://dali.redwolf501.top/Article/details/gt2omhbaltl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yanxiufei.cn/Article/details/gt2lnzrpikd.html

[Q20] IN 列表
来源：http://dali.xylfe.cn/Article/details/gt2ljewauwo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xziqi.cn/Article/details/gt2fsrhfakr.html

[Q21] 空值判断
来源：http://dali.yuanzhike.top/Article/details/gt2kpxtmceh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sufxvd.cn/Article/details/gt2bodeuden.html

[Q22] 排序
来源：http://dali.tanke756.top/Article/details/gt2euyhotmt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fzhhl.top/Article/details/gt2cbgoecfq.html

[Q23] 分页
来源：http://dali.ivvv.top/Article/details/gt2fhhveqye.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhiwuduotai.top/Article/details/gt2cukirjhr.html

[Q24] 去重
来源：http://dali.havefunace.top/Article/details/gt2cxihbksw.html

SELECT DISTINCT city FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2eceqzmpt.html

[Q25] 只取前 N 条
来源：http://dali.hfpthk.cn/Article/details/gt2hwnlngiv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.haohaochexian.top/Article/details/gt2hngufreu.html

[Q26] 计数
来源：http://dali.meibo888.top/Article/details/gt2ggxtvpkn.html

SELECT COUNT(*) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2fdcstmfx.html

[Q27] 条件计数
来源：http://dali.cqqwz.cn/Article/details/gt2fvanoqbs.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2kmrpbnkv.html

[Q28] 求和与平均
来源：http://dali.guowangkeji.top/Article/details/gt2fqzjidtv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2rxxzqhdz.html

[Q29] 最大最小值
来源：http://dali.smart0.xyz/Article/details/gt2mldrnomm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2dtyiqamy.html

[Q30] 分组统计
来源：http://dali.ppjwa.cn/Article/details/gt2belcfwdc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gt2fqoabdeb.html

[Q31] 分组后过滤
来源：http://dali.yuxming.cn/Article/details/gt2bteiuhdw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.birdmap.top/Article/details/gt2rdgqlxpk.html

[Q32] 分组拼接字符串
来源：http://dali.ybcxt.top/Article/details/gt2khxzuyef.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gt2xeoddpon.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hongshengwenyu.top/Article/details/gt2khgiyvii.html

[Q33] 多列分组
来源：http://dali.xinyue.icu/Article/details/gt2vtzvgzeg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.redwolf501.top/Article/details/gt2tjvynrdq.html

[Q34] 每组取第一条
来源：http://dali.jinqigufen.top/Article/details/gt2lnzwxsgx.html

SELECT * FROM (
来源：http://dali.mhx1999.top/Article/details/gt2ibdtjphv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfturoz.html

) t WHERE rn = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ujnnsqba.html

[Q35] 内连接
来源：http://dali.xuanzx.com/Article/details/gt2pyfnoatx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgufenzy.top/Article/details/gt2imcdcdnd.html

[Q36] 左连接
来源：http://dali.sysykeji.top/Article/details/gt2iigivont.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ulubrxwc.html

[Q37] 右连接
来源：http://dali.hfpthk.cn/Article/details/gt2czxyvqfu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ydzc1.top/Article/details/gt2qnqqxjan.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yuanzhike.top/Article/details/gt2sjucoxig.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.vqdsnc.cn/Article/details/gt2kbudrqbj.html

[Q39] 自连接（查上下级）
来源：http://dali.daria6918.cn/Article/details/gt2kenqgztf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ppjwa.cn/Article/details/gt2iqqinnll.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nczmlouy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shzxlz.cn/Article/details/gt2drjblncb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zdqjudy.top/Article/details/gt2orsrtzti.html

[Q41] 多表连接
来源：http://dali.jyoumei.cn/Article/details/gt2giayqbrc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2feaftviv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xuetiantiany.cn/Article/details/gt2rkfbyonw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ybcxt.top/Article/details/gt2muxmmpwz.html

[Q42] 连接条件附加过滤
来源：http://dali.wangdashe.top/Article/details/gt2lmdcccdk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rhiqgobo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.svipenyu.cn/Article/details/gt2fdfjcmri.html

[Q43] 标量子查询
来源：http://dali.yuanzhike.top/Article/details/gt2upmqkmxs.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cheryme.top/Article/details/gt2umfqqrso.html

[Q44] IN 子查询
来源：http://dali.fengsongda.top/Article/details/gt2juekfkmc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pahxhonl.html

[Q45] EXISTS 判断存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hkzvabut.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gt2flscflce.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ppjwa.cn/Article/details/gt2leqevudm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gt2nrgvdsot.html

[Q47] 与平均值比较
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bbsqvbzb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gzhubu.top/Article/details/gt2tfekuavd.html

[Q48] CTE 公用表表达式
来源：http://dali.zhengqikj.top/Article/details/gt2nhvmsluc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xuanzx.com/Article/details/gt2ynlvgafu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgfzy.top/Article/details/gt2pxbfkawh.html

[Q49] 更新单行
来源：http://dali.hywenlv.cn/Article/details/gt2esszvurh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gt2cjdxddvg.html

[Q50] 批量更新
来源：http://dali.ehwqpu.com/Article/details/gt2nxirtyal.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yongpay.top/Article/details/gt2kqhvxwkt.html

[Q51] 用子查询更新
来源：http://dali.mhx1999.top/Article/details/gt2mqsuqxwj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhengqikj.top/Article/details/gt2dqlukhok.html

[Q52] 删除指定行
来源：http://dali.gogol.net.cn/Article/details/gt2euahulgz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xziqi.cn/Article/details/gt2wztssxuk.html

[Q53] 按条件删除
来源：http://dali.9152youxi.cn/Article/details/gt2bojdntru.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenjidiqi.icu/Article/details/gt2clgvxmtt.html

[Q54] 清空表
来源：http://dali.nwbrower.top/Article/details/gt2uwdnebax.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2btvclsgm.html

[Q55] 排名（并列占位）
来源：http://dali.andypj.xyz/Article/details/gt2damfljsf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yonumen.top/Article/details/gt2ldhsodob.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnxiangtu.top/Article/details/gt2iqicllac.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guannengcc.top/Article/details/gt2oitrlsdc.html

[Q57] 行号
来源：http://dali.birdmap.top/Article/details/gt2fwazguoh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2nhpykbyf.html

[Q58] 累计求和
来源：http://dali.yongpay.top/Article/details/gt2rjvhniex.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gzhubu.top/Article/details/gt2tnydtevo.html

[Q59] 分组内累计
来源：http://dali.chenzaomai.com/Article/details/gt2wbrhavlo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2cmdxromf.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuoxkys.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.dashuyun.cn/Article/details/gt2qcasqase.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2gimweicc.html

[Q61] 移动平均
来源：http://dali.ydzc1.top/Article/details/gt2ipcwgmft.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tanke756.top/Article/details/gt2kofwxsnf.html

[Q62] 分组占比
来源：http://dali.zhixingplan.top/Article/details/gt2gfqmidpf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gt2yimdbnkb.html

[Q63] 开启事务
来源：http://dali.cdnleiting.top/Article/details/gt2wxawbawg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj202588.top/Article/details/gt2kppcfqzj.html

[Q64] 提交事务
来源：http://dali.hnxiangtu.top/Article/details/gt2bfnktaig.html

COMMIT;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sbtzgiqu.html

[Q65] 回滚事务
来源：http://dali.0kj1m.cn/Article/details/gt2hssvqgrb.html

ROLLBACK;
来源：http://dali.bjfxy.top/Article/details/gt2pclkfdhn.html

[Q66] 行锁查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2zfaantrh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuxming.cn/Article/details/gt2gdurzucf.html

[Q67] 设置隔离级别
来源：http://dali.tian-w.cn/Article/details/gt2ktfhwelc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.wangshuangyany.cn/Article/details/gt2lcynwfcc.html

[Q68] 保存点
来源：http://dali.zhixingplan.top/Article/details/gt2kevvrqmi.html

SAVEPOINT sp1;
来源：http://dali.sxryk.cn/Article/details/gt2zyfgfucn.html

ROLLBACK TO sp1;
来源：http://dali.hnqzz.top/Article/details/gt2jtmrtnlq.html

[Q69] 查看执行计划
来源：http://dali.zhixingplan.top/Article/details/gt2afbgmxsg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.9152youxi.cn/Article/details/gt2pazjopfd.html

[Q70] 更新统计信息
来源：http://dali.zhengqikj.top/Article/details/gt2hjxzsiwj.html

ANALYZE TABLE users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hqsdqwgh.html

[Q71] 查看建表语句
来源：http://dali.hongshengwenyu.top/Article/details/gt2jzpmhdxg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hysaishi.cn/Article/details/gt2bqjpaavt.html

[Q72] 查看索引
来源：http://dali.guannengcc.top/Article/details/gt2yaoatbdm.html

SHOW INDEX FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2uuyxlqlc.html

[Q73] 查看表状态
来源：http://dali.cdnleiting.top/Article/details/gt2kyrhtknf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.vqdsnc.cn/Article/details/gt2fonaenpl.html

[Q74] 强制使用索引
来源：http://dali.hysaishi.cn/Article/details/gt2flwvvacf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.c1oappe.top/Article/details/gt2kbhwxrmn.html

[Q75] 日期格式化
来源：http://dali.0kj1m.cn/Article/details/gt2hlcxiecf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.c1oappe.top/Article/details/gt2euyuiidf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hongshengwenyu.top/Article/details/gt2revefsdf.html

[Q76] 按天统计
来源：http://dali.wangshuangyany.cn/Article/details/gt2eqnrdmds.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnqzz.top/Article/details/gt2faiaejyn.html

[Q77] 时间加减
来源：http://dali.c1oappe.top/Article/details/gt2cujwlqab.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.c1oappe.top/Article/details/gt2lexbsphp.html

[Q78] 当前时间
来源：http://dali.aizwys.cn/Article/details/gt2orvdupch.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhongyouzk.top/Article/details/gt2loyazwkv.html

[Q79] 字符串拼接
来源：http://dali.jianghu66.top/Article/details/gt2gfpxjskx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.iojbl.cn/Article/details/gt2flqyvtel.html

[Q80] 字符串截取
来源：http://dali.cqqwz.cn/Article/details/gt2lebsudhd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aryhpwpw.html

[Q81] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2cqpzdcco.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vggigepc.html

[Q82] 字符长度与字节长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pquerwoo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2ywplzfgb.html

[Q83] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gt2bfxgbcql.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2mifdwtra.html

[Q84] 去除首尾空格
来源：http://dali.meibo888.top/Article/details/gt2wmivdmks.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2zzoetutl.html

[Q85] 数值取整
来源：http://dali.haohaochexian.top/Article/details/gt2phlvxzey.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinqigfzy.top/Article/details/gt2azcmqpbl.html

[Q86] 读取 JSON 字段
来源：http://dali.sxryk.cn/Article/details/gt2luniuoqv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fengsongda.top/Article/details/gt2fwvmesyy.html

[Q87] JSON 字段做条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jkzzwbbj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258888.top/Article/details/gt2hwqundpt.html

[Q88] 行转列（条件聚合）
来源：http://dali.0kj1m.cn/Article/details/gt2tarfbwjg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kodwhhqr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2zznrejut.html

[Q89] 判断表是否存在
来源：http://dali.meibo888.top/Article/details/gt2uztiioun.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pycfn.com/Article/details/gt2gttkqtun.html

[Q90] 生成序号列
来源：http://dali.tianlin.xyz/Article/details/gt2tdsbqdoj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hammf.cn/Article/details/gt2gkhdddju.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2ywqhzzxm.html

R. Bash 专题
来源：http://dali.0kj1m.cn/Article/details/gt2tzotzvwo.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2hfjkroqd.html

[R01] shebang 与严格模式
来源：http://dali.ydzc1.top/Article/details/gt2hvcdauqh.html

#!/usr/bin/env bash
来源：http://dali.jqgfzy.top/Article/details/gt2uzrqwnyn.html

set -euo pipefail
来源：http://dali.chenzaomai.com/Article/details/gt2iksfwoqa.html

[R02] 变量赋值与使用
来源：http://dali.sysykeji.top/Article/details/gt2lcgklugk.html

name="Tom"; echo "$name"
来源：http://dali.quarkkingdee.top/Article/details/gt2ylknboza.html

[R03] 只读变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tnoltoit.html

readonly PI=3.14
来源：http://dali.meibo888.top/Article/details/gt2izkicccu.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdcofcb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pengpengdd.cyou/Article/details/gt2qibzujds.html

[R05] 参数默认值
来源：http://dali.daria6918.cn/Article/details/gt2ofctoeab.html

name="${1:-default}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2scbxobpj.html

[R06] 判断命令是否存在
来源：http://dali.gzhubu.top/Article/details/gt2pvpoeywm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gt2cbluivtq.html

[R07] if 判断文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2afnecmwj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cqqwz.cn/Article/details/gt2xpmekgfs.html

[R08] 数值比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2ktutkbcr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dianchejie.cn/Article/details/gt2ihtzyfxl.html

[R09] 字符串比较
来源：http://dali.jqgfzy.top/Article/details/gt2frgdentc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cdnleiting.top/Article/details/gt2symhkjkm.html

[R10] 正则匹配
来源：http://dali.svipenyu.cn/Article/details/gt2utsvgbrf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shzxlz.cn/Article/details/gt2lfkubvml.html

[R11] case 多分支
来源：http://dali.hammf.cn/Article/details/gt2uoyvckii.html

case "$1" in
来源：http://dali.yj202588.top/Article/details/gt2kzjkueqp.html

start) echo "启动" ;;
来源：http://dali.tianlin.xyz/Article/details/gt2oigoviss.html

stop)  echo "停止" ;;
来源：http://dali.sweek.top/Article/details/gt2ugfijlyq.html

*)     echo "未知命令" ;;
来源：http://dali.pycfn.com/Article/details/gt2qlmbarbj.html

esac
来源：http://dali.nanxinkj.top/Article/details/gt2swrfcuxd.html

[R12] for 遍历文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2udeagukg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jiagoushi.top/Article/details/gt2vcltumik.html

[R13] for 计数循环
来源：http://dali.hywenlv.cn/Article/details/gt2gfqqysrn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.c1oappe.top/Article/details/gt2acdlkngf.html

[R14] C 风格 for
来源：http://dali.cqqwz.cn/Article/details/gt2lblmvbps.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hnxiangtu.top/Article/details/gt2ysjboynw.html

[R15] while 逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gt2mkwnjblq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tianlin.xyz/Article/details/gt2ofamhxwk.html

[R16] until 等待条件
来源：http://dali.xinyue.icu/Article/details/gt2hnkhlpzr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zycfv.cn/Article/details/gt2ykkcaihi.html

[R17] 数组定义与取值
来源：http://dali.hammf.cn/Article/details/gt2funefpzj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258.top/Article/details/gt2ycytqwlj.html

[R18] 遍历数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hempchdz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wlonepok.html

[R19] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gt2qcggnswt.html

echo "${#arr[@]}"
来源：http://dali.snrcjt.cn/Article/details/gt2yqsgtdqv.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zsgrqfoj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ckizxebu.html

[R21] 字符串长度
来源：http://dali.sxryk.cn/Article/details/gt2ywsrvdut.html

echo "${#s}"
来源：http://dali.cashguo.top/Article/details/gt2hypxjkfs.html

[R22] 截取子串
来源：http://dali.vqdsnc.cn/Article/details/gt2ccxqttlv.html

echo "${s:0:5}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jmqdpxfz.html

[R23] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gt2marmjxpf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aibaodan.cn/Article/details/gt2biaydonp.html

[R24] 大小写转换
来源：http://dali.yuanzhike.top/Article/details/gt2tyvnbdaq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xinyue.icu/Article/details/gt2yabfywmk.html

[R25] 去后缀 / 去前缀
来源：http://dali.gaohongyu789.top/Article/details/gt2ruvycmac.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cdnleiting.top/Article/details/gt2mvdecwqw.html

[R26] 命令替换
来源：http://dali.hnxiangtu.top/Article/details/gt2ksmqaqrh.html

now=$(date +%F); echo "$now"
来源：http://dali.iojbl.cn/Article/details/gt2dswxzozs.html

[R27] 算术展开
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2olottjip.html

echo $((1 + 2 * 3))
来源：http://dali.ehwqpu.com/Article/details/gt2tjnebggx.html

[R28] 浮点运算
来源：http://dali.jyoumei.cn/Article/details/gt2dsarkpkp.html

echo "scale=2; 10/3" | bc
来源：http://dali.yanxiufei.cn/Article/details/gt2hnenvwhn.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwsgeqg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2yzzjykuc.html

[R30] 函数返回状态码
来源：http://dali.yueranfly.top/Article/details/gt2taethsep.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdototg.html

[R31] 局部变量
来源：http://dali.hysaishi.cn/Article/details/gt2tijsonrw.html

f() { local x=1; echo "$x"; }
来源：http://dali.ehwqpu.com/Article/details/gt2fepxkffj.html

[R32] 参数个数校验
来源：http://dali.hnxiangtu.top/Article/details/gt2uwidnnxx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gt2lkjwecfg.html

[R33] 捕获错误并提示行号
来源：http://dali.daria6918.cn/Article/details/gt2ndcfkytx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.9152youxi.cn/Article/details/gt2ealbtban.html

[R34] 退出时清理
来源：http://dali.feifeiyinyue.top/Article/details/gt2wydylxcf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gt2rfsknyob.html

[R35] 后台执行并等待
来源：http://dali.jianghu66.top/Article/details/gt2bmekosue.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.c1oappe.top/Article/details/gt2mtplhldv.html

[R36] 并发执行多个任务
来源：http://dali.ybcxt.top/Article/details/gt2ydbhqbur.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xuanzx.com/Article/details/gt2ymuubdah.html

[R37] 把输出赋给变量
来源：http://dali.cdnleiting.top/Article/details/gt2enigfeva.html

files=$(ls -1)
来源：http://dali.jinqigufen.top/Article/details/gt2mavwjtdu.html

[R38] 管道串联
来源：http://dali.yuanzhike.top/Article/details/gt2ufgtbqtd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nwbrower.top/Article/details/gt2ltaxavze.html

[R39] 重定向标准输出与错误
来源：http://dali.316326.xyz/Article/details/gt2pagoapad.html

cmd > out.log 2>&1
来源：http://dali.316326.xyz/Article/details/gt2fjuljawc.html

[R40] 追加写日志
来源：http://dali.hammf.cn/Article/details/gt2ddkpaqjs.html

echo "log" >> out.log
来源：http://dali.gaohongyu789.top/Article/details/gt2kythfara.html

[R41] 丢弃输出
来源：http://dali.jqgfzy.top/Article/details/gt2jghvbarm.html

cmd >/dev/null 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rxjinxha.html

[R42] 输入重定向
来源：http://dali.aibaodan.cn/Article/details/gt2mftuyfvw.html

wc -l < a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2njzbrdmh.html

[R43] 按名字查找文件
来源：http://dali.jiagoushi.top/Article/details/gt2lkprgmpk.html

find . -name "*.log" -type f
来源：http://dali.yonumen.top/Article/details/gt2swshofsf.html

[R44] 按修改时间查找
来源：http://dali.hnxiangtu.top/Article/details/gt2jmrsslzy.html

find . -mtime -7 -type f
来源：http://dali.gotoacloud.top/Article/details/gt2vmnypkaa.html

[R45] 批量删除
来源：http://dali.zhongyouzk.top/Article/details/gt2hnyjavdr.html

find . -name "*.tmp" -delete
来源：http://dali.gogol.net.cn/Article/details/gt2zhsdopyb.html

[R46] 递归替换文件内容
来源：http://dali.wangshuangyany.cn/Article/details/gt2rwifqjhn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.9152youxi.cn/Article/details/gt2yfydxapm.html

[R47] sed 单行替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nqfxzzbc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2poppexbp.html

[R48] awk 取指定列
来源：http://dali.jqgfzy.top/Article/details/gt2nwmredzk.html

awk '{print $1, $3}' a.txt
来源：http://dali.yueranfly.top/Article/details/gt2gqbjcnfb.html

[R49] awk 带条件
来源：http://dali.nwbrower.top/Article/details/gt2snmqjobi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cluahgro.html

[R50] awk 求和
来源：http://dali.yanxiufei.cn/Article/details/gt2qyydgrrg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.mhx1999.top/Article/details/gt2hyhyeise.html

[R51] 排序去重取前几
来源：http://dali.gogol.net.cn/Article/details/gt2awyuvnyc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhengqikj.top/Article/details/gt2dhikfssg.html

[R52] 统计行数
来源：http://dali.shuidangran.top/Article/details/gt2syndofoz.html

wc -l a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2pvkrojvs.html

[R53] 查看文件头与实时尾
来源：http://dali.ybcxt.top/Article/details/gt2askzzmvc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2whxzvyer.html

[R54] 比较两个文件
来源：http://dali.tian-w.cn/Article/details/gt2lgwiulpx.html

diff a.txt b.txt
来源：http://dali.guannengcc.top/Article/details/gt2qiuurlcx.html

[R55] 压缩与解压
来源：http://dali.yangfankeji.com/Article/details/gt2qnkjiudz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuanzhike.top/Article/details/gt2zpumzgbj.html

[R56] 远程拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gt2wmyuiozr.html

scp file user@host:/path/
来源：http://dali.yj20258888.top/Article/details/gt2bwaxvoew.html

[R57] 远程执行命令
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cnrtcoke.html

ssh user@host 'uptime'
来源：http://dali.birdmap.top/Article/details/gt2wphqhotw.html

[R58] 下载文件
来源：http://dali.fengsongda.top/Article/details/gt2vahaxfcx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fxpvwrap.html

[R59] 发 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gt2frtifqtu.html


<!-- 参考信息 -->