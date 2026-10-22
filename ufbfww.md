代发 wailian999

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xuetiantiany.cn/Article/details/gtihdrvnxa.html

[Q07] 删除表
来源：http://dali.havefunace.top/Article/details/gtspedtqhx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nwbrower.top/Article/details/gtvndyhjlc.html

[Q08] 创建普通索引
来源：http://dali.cucudq.cn/Article/details/gtjkvghzso.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrwxosfa.html

[Q09] 创建唯一索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwlgougn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gtzsfjngfs.html

[Q10] 插入单行
来源：http://dali.quarkkingdee.top/Article/details/gtdgavohkq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ydzc1.top/Article/details/gtteseqbuy.html

[Q11] 一次插入多行
来源：http://dali.jinqigfzy.top/Article/details/gtrfuqiazy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.fzhhl.top/Article/details/gtvalfgllj.html

[Q12] 插入后取自增 ID
来源：http://dali.zhiwuduotai.top/Article/details/gtbhwrspvo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ppjwa.cn/Article/details/gtzobtdsof.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xuanzx.com/Article/details/gthctkuoms.html

[Q13] 忽略重复插入
来源：http://dali.zycfv.cn/Article/details/gtdomytwtg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hnqzz.top/Article/details/gtpkkdpaoa.html

[Q14] 存在则更新（upsert）
来源：http://dali.yanxiufei.cn/Article/details/gtqtselpjb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sxryk.cn/Article/details/gtruspzgec.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuxming.cn/Article/details/gtqiutcocu.html

[Q15] 查询全部
来源：http://dali.sweek.top/Article/details/gteddkaflu.html

SELECT * FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtngspxzuk.html

[Q16] 查询指定列
来源：http://dali.daxiang520.top/Article/details/gtxjcantkb.html

SELECT id, name FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtkeeripef.html

[Q17] 条件查询
来源：http://dali.zdqjudy.top/Article/details/gtjmhnqjvj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtrjjqbfuc.html

[Q18] 模糊匹配
来源：http://dali.hysaishi.cn/Article/details/gticnnutdx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tanke756.top/Article/details/gtoidfffuy.html

[Q19] 范围查询
来源：http://dali.xuanzx.com/Article/details/gtkajyfocs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.dianchejie.cn/Article/details/gtjhgfjfwl.html

[Q20] IN 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjpsazvj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.fengsongda.top/Article/details/gtyvxmibpd.html

[Q21] 空值判断
来源：http://dali.yanxiufei.cn/Article/details/gtsmihdirv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jlsjyb.cn/Article/details/gtlaicqfgd.html

[Q22] 排序
来源：http://dali.ehwqpu.com/Article/details/gtcoamhcuh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tian-w.cn/Article/details/gtchaywhrm.html

[Q23] 分页
来源：http://dali.jlsjyb.cn/Article/details/gtwjwlmtix.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanemmtky.html

[Q24] 去重
来源：http://dali.redwolf501.top/Article/details/gtfykgpqcs.html

SELECT DISTINCT city FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtaqnfkqol.html

[Q25] 只取前 N 条
来源：http://dali.c1oappe.top/Article/details/gtywpaktpd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shangyingyoupin.top/Article/details/gtgwydbgwu.html

[Q26] 计数
来源：http://dali.daxiang520.top/Article/details/gtihhhxoxv.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtzrwqnexz.html

[Q27] 条件计数
来源：http://dali.zhongyouzk.top/Article/details/gthxvrwamw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.mhx1999.top/Article/details/gtxfqxabfy.html

[Q28] 求和与平均
来源：http://dali.dianchejie.cn/Article/details/gtqguatfmu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtcfvkqrkg.html

[Q29] 最大最小值
来源：http://dali.cheryme.top/Article/details/gtoxplkvtm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtgdzsiqsu.html

[Q30] 分组统计
来源：http://dali.zhoulong.xyz/Article/details/gtnsffmrfh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gtiwtznika.html

[Q31] 分组后过滤
来源：http://dali.ivvv.top/Article/details/gtrxaotwzm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgfzy.top/Article/details/gtpyawtadm.html

[Q32] 分组拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtckusviyk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gtrqopaenu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ehwqpu.com/Article/details/gtzenvcprr.html

[Q33] 多列分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndgschkl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.daria6918.cn/Article/details/gtvjnlpsli.html

[Q34] 每组取第一条
来源：http://dali.snrcjt.cn/Article/details/gtcoyyfkjj.html

SELECT * FROM (
来源：http://dali.hnxiangtu.top/Article/details/gtdswlmajw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yuanzhike.top/Article/details/gtvoxpnayg.html

) t WHERE rn = 1;
来源：http://dali.c1oappe.top/Article/details/gtvrqjijhu.html

[Q35] 内连接
来源：http://dali.hnxiangtu.top/Article/details/gtrxcdcyec.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gtbfwcdhuj.html

[Q36] 左连接
来源：http://dali.zhengqikj.top/Article/details/gtxbriyiqo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gtwgncmofv.html

[Q37] 右连接
来源：http://dali.dashuyun.cn/Article/details/gtaszjroxn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jlsjyb.cn/Article/details/gtxdzjersu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sxryk.cn/Article/details/gtefbfeedd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.c1oappe.top/Article/details/gtwpcjdafv.html

[Q39] 自连接（查上下级）
来源：http://dali.daria6918.cn/Article/details/gtfzssghcx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shzxlz.cn/Article/details/gtgfhvdicj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yonumen.top/Article/details/gtwcmedkzt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sweek.top/Article/details/gtaszmeinf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cucudq.cn/Article/details/gthwplmnoe.html

[Q41] 多表连接
来源：http://dali.jiagoushi.top/Article/details/gtghevrgcp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhylsdle.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ybcxt.top/Article/details/gthkqtwcyl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinqigfzy.top/Article/details/gtwmhmqwzf.html

[Q42] 连接条件附加过滤
来源：http://dali.tanke756.top/Article/details/gtnzgkcuip.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yanxiufei.cn/Article/details/gtpiqttoyy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.feifeiyinyue.top/Article/details/gtpaxmfcvs.html

[Q43] 标量子查询
来源：http://dali.zhiwuduotai.top/Article/details/gtfdjqbkih.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sufxvd.cn/Article/details/gttqhlwvpz.html

[Q44] IN 子查询
来源：http://dali.0kj1m.cn/Article/details/gtnvloiwnm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.haohaochexian.top/Article/details/gtiyyrgsdy.html

[Q45] EXISTS 判断存在
来源：http://dali.yanxiufei.cn/Article/details/gtwdaipdpv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuxming.cn/Article/details/gtuydvkook.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hfpthk.cn/Article/details/gtfawlblzl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gtsxdhstji.html

[Q47] 与平均值比较
来源：http://dali.smart0.xyz/Article/details/gtciftwqak.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ybcxt.top/Article/details/gtvlvnwhkj.html

[Q48] CTE 公用表表达式
来源：http://dali.wangdashe.top/Article/details/gtorijchav.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.vqdsnc.cn/Article/details/gtlyiyuytw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.daxiang520.top/Article/details/gtqtymskrc.html

[Q49] 更新单行
来源：http://dali.svipenyu.cn/Article/details/gtsjqbajqb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gtmuoyhawz.html

[Q50] 批量更新
来源：http://dali.zdqjudy.top/Article/details/gtqmcbszlf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.kuanghao11.cn/Article/details/gtfbdxmyvy.html

[Q51] 用子查询更新
来源：http://dali.sysykeji.top/Article/details/gtiuxnnzaz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtpolwoitl.html

[Q52] 删除指定行
来源：http://dali.bjfxy.top/Article/details/gttbjrjjam.html

DELETE FROM users WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gtzizkuvep.html

[Q53] 按条件删除
来源：http://dali.jyoumei.cn/Article/details/gtvycrofco.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cashguo.top/Article/details/gtckjwyvzc.html

[Q54] 清空表
来源：http://dali.hnxiangtu.top/Article/details/gtsueaaykd.html

TRUNCATE TABLE logs;
来源：http://dali.andypj.xyz/Article/details/gtbrgzrjqo.html

[Q55] 排名（并列占位）
来源：http://dali.jinqigufen.top/Article/details/gtmjovsjwt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xuanzx.com/Article/details/gtnvqkwskb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tian-w.cn/Article/details/gtjfispqam.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hnqzz.top/Article/details/gtqedmfglq.html

[Q57] 行号
来源：http://dali.yj202588.top/Article/details/gtkfkpvogq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ehwqpu.com/Article/details/gttmfdzpcv.html

[Q58] 累计求和
来源：http://dali.shzxlz.cn/Article/details/gtiuidgdjs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtgzdtbprw.html

[Q59] 分组内累计
来源：http://dali.guannengcc.top/Article/details/gtdqztsnty.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtasymfvdy.html

[Q60] 取上一行 / 下一行
来源：http://dali.aizwys.cn/Article/details/gtkmeyqumd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xinyue.icu/Article/details/gtiypoyxwz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pycfn.com/Article/details/gtvrtfimvt.html

[Q61] 移动平均
来源：http://dali.jianghu66.top/Article/details/gtqxgfgfsg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtfhvrteva.html

[Q62] 分组占比
来源：http://dali.sweek.top/Article/details/gtyghykpuj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gtrhlgzovb.html

[Q63] 开启事务
来源：http://dali.yj202588.top/Article/details/gtasfxcibi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jyoumei.cn/Article/details/gtxkkuhfzj.html

[Q64] 提交事务
来源：http://dali.ehwqpu.com/Article/details/gtmvxwxvbc.html

COMMIT;
来源：http://dali.jianghu66.top/Article/details/gtpxxxiojv.html

[Q65] 回滚事务
来源：http://dali.cdnleiting.top/Article/details/gtiakgqces.html

ROLLBACK;
来源：http://dali.9152youxi.cn/Article/details/gtrzhqnkwj.html

[Q66] 行锁查询
来源：http://dali.shangyingyoupin.top/Article/details/gtavvzavun.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cucudq.cn/Article/details/gtocbinmtg.html

[Q67] 设置隔离级别
来源：http://dali.hammf.cn/Article/details/gthpqghwhd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sxryk.cn/Article/details/gtgqacocmw.html

[Q68] 保存点
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcblwapvw.html

SAVEPOINT sp1;
来源：http://dali.nwbrower.top/Article/details/gtfswxegqx.html

ROLLBACK TO sp1;
来源：http://dali.bjfxy.top/Article/details/gtkitpsqfy.html

[Q69] 查看执行计划
来源：http://dali.smart0.xyz/Article/details/gtwetpfhuc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sxryk.cn/Article/details/gtsqimizen.html

[Q70] 更新统计信息
来源：http://dali.yanxiufei.cn/Article/details/gtkoxaexyf.html

ANALYZE TABLE users;
来源：http://dali.cqqwz.cn/Article/details/gtmdgylxfp.html

[Q71] 查看建表语句
来源：http://dali.kuanghao11.cn/Article/details/gtwwdlowkq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zycfv.cn/Article/details/gtcrksfqso.html

[Q72] 查看索引
来源：http://dali.xuanzx.com/Article/details/gtgpbtappn.html

SHOW INDEX FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtqhabnvao.html

[Q73] 查看表状态
来源：http://dali.hysaishi.cn/Article/details/gtiyubbtkz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jyoumei.cn/Article/details/gtnrszbfnk.html

[Q74] 强制使用索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkylwshna.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xinyue.icu/Article/details/gtrcxujgkn.html

[Q75] 日期格式化
来源：http://dali.jianghu66.top/Article/details/gtfuhjysqu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttllvvtpb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shuidangran.top/Article/details/gtvvwglndg.html

[Q76] 按天统计
来源：http://dali.haohaochexian.top/Article/details/gteepvrpkx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.guannengcc.top/Article/details/gtucycqshd.html

[Q77] 时间加减
来源：http://dali.nanxuanxn.top/Article/details/gtjrkjeyim.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hammf.cn/Article/details/gtwidaqlqu.html

[Q78] 当前时间
来源：http://dali.meibo888.top/Article/details/gtmvygwpic.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.aibaodan.cn/Article/details/gtwwcgtzpk.html

[Q79] 字符串拼接
来源：http://dali.aibaodan.cn/Article/details/gtuiazxucv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aibaodan.cn/Article/details/gtyzdmzech.html

[Q80] 字符串截取
来源：http://dali.sysykeji.top/Article/details/gtbyoetdmp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtmugqfppl.html

[Q81] 字符串替换
来源：http://dali.tianlin.xyz/Article/details/gtvmktwufw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tanke756.top/Article/details/gtyaimbgvd.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgfzy.top/Article/details/gtaorwbegg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtqfnjzugv.html

[Q83] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gtsrsrypck.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gtggvgrezr.html

[Q84] 去除首尾空格
来源：http://dali.yuxming.cn/Article/details/gtdhundeva.html

SELECT TRIM(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtognwnpik.html

[Q85] 数值取整
来源：http://dali.vqdsnc.cn/Article/details/gtixfgddjv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.pengpengdd.cyou/Article/details/gtprliwzwf.html

[Q86] 读取 JSON 字段
来源：http://dali.meibo888.top/Article/details/gtjyvbupps.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jqgfzy.top/Article/details/gtdhrblosm.html

[Q87] JSON 字段做条件
来源：http://dali.0kj1m.cn/Article/details/gtllapfyyz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xuetiantiany.cn/Article/details/gtwmewgvyd.html

[Q88] 行转列（条件聚合）
来源：http://dali.jianghu66.top/Article/details/gtjfmnjelv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zdqjudy.top/Article/details/gtknxpvqnm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.andypj.xyz/Article/details/gtkpbcdgxx.html

[Q89] 判断表是否存在
来源：http://dali.wangdashe.top/Article/details/gtzczbllei.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tianlin.xyz/Article/details/gtoupeujtk.html

[Q90] 生成序号列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzaetjwc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.9152youxi.cn/Article/details/gtzysroqzm.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtczanrspa.html

R. Bash 专题
来源：http://dali.cucudq.cn/Article/details/gtjkloytul.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtiicflayu.html

[R01] shebang 与严格模式
来源：http://dali.jinqigfzy.top/Article/details/gticyrjnur.html

#!/usr/bin/env bash
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbzohrqs.html

set -euo pipefail
来源：http://dali.wangshuangyany.cn/Article/details/gtolbgsahd.html

[R02] 变量赋值与使用
来源：http://dali.gogol.net.cn/Article/details/gtljhzlsfq.html

name="Tom"; echo "$name"
来源：http://dali.dashuyun.cn/Article/details/gtioukovdf.html

[R03] 只读变量
来源：http://dali.jyoumei.cn/Article/details/gtixyqhnmh.html

readonly PI=3.14
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjyblvbrw.html

[R04] 位置参数
来源：http://dali.jinqigufen.top/Article/details/gtnkmyuzzn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zycfv.cn/Article/details/gtnpydxwph.html

[R05] 参数默认值
来源：http://dali.zycfv.cn/Article/details/gttuyhmczp.html

name="${1:-default}"
来源：http://dali.fzhhl.top/Article/details/gthvvugbxo.html

[R06] 判断命令是否存在
来源：http://dali.haohaochexian.top/Article/details/gtrkpgfnrk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gtyqvnnwlv.html

[R07] if 判断文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtafvjrcba.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtqwplmqqh.html

[R08] 数值比较
来源：http://dali.iojbl.cn/Article/details/gtuhovphaj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yangfankeji.com/Article/details/gttrwwxzch.html

[R09] 字符串比较
来源：http://dali.cucudq.cn/Article/details/gtlibhjgea.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gzhubu.top/Article/details/gtgyiggjjq.html

[R10] 正则匹配
来源：http://dali.hammf.cn/Article/details/gtkqarlciu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cdnleiting.top/Article/details/gttevrkqaa.html

[R11] case 多分支
来源：http://dali.gotoacloud.top/Article/details/gtzkcbvxvx.html

case "$1" in
来源：http://dali.xylfe.cn/Article/details/gtubzsiors.html

start) echo "启动" ;;
来源：http://dali.jqgufenzy.top/Article/details/gtmvnailhi.html

stop)  echo "停止" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtqdiyihgb.html

*)     echo "未知命令" ;;
来源：http://dali.hammf.cn/Article/details/gtdsmefcse.html

esac
来源：http://dali.yonumen.top/Article/details/gtilawmyzw.html

[R12] for 遍历文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctqkqftk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenzaomai.com/Article/details/gtybmxldgm.html

[R13] for 计数循环
来源：http://dali.c1oappe.top/Article/details/gtatuggsym.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gogol.net.cn/Article/details/gtrmehobsx.html

[R14] C 风格 for
来源：http://dali.pycfn.com/Article/details/gtqenlshyi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.smart0.xyz/Article/details/gtbudwstos.html

[R15] while 逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtvealunhk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangshuangyany.cn/Article/details/gthkjxwsrj.html

[R16] until 等待条件
来源：http://dali.bjfxy.top/Article/details/gtnrwdpmbc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gtfpnzasky.html

[R17] 数组定义与取值
来源：http://dali.ehwqpu.com/Article/details/gtsdwzdqrd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shangyingyoupin.top/Article/details/gtgwvpcxpt.html

[R18] 遍历数组
来源：http://dali.cheryme.top/Article/details/gtxfwzgfyq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ybcxt.top/Article/details/gtklytxygf.html

[R19] 数组长度
来源：http://dali.yongpay.top/Article/details/gtjuvucval.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gttttlsrxo.html

[R20] 关联数组（字典）
来源：http://dali.wangdashe.top/Article/details/gtrzuhezfa.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdybuwzxw.html

[R21] 字符串长度
来源：http://dali.zhengqikj.top/Article/details/gtnzsgucth.html

echo "${#s}"
来源：http://dali.hnqzz.top/Article/details/gtqupyhjzr.html

[R22] 截取子串
来源：http://dali.daxiang520.top/Article/details/gtydsjlpzc.html

echo "${s:0:5}"
来源：http://dali.cdnleiting.top/Article/details/gtsgrcubqs.html

[R23] 字符串替换
来源：http://dali.aizwys.cn/Article/details/gtoowsuuam.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmrkomwh.html

[R24] 大小写转换
来源：http://dali.hammf.cn/Article/details/gtjdsvbcjt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hammf.cn/Article/details/gtcsopvlbx.html

[R25] 去后缀 / 去前缀
来源：http://dali.daria6918.cn/Article/details/gtocarmhmg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjlisauk.html

[R26] 命令替换
来源：http://dali.xuetiantiany.cn/Article/details/gtdwisxhys.html

now=$(date +%F); echo "$now"
来源：http://dali.pycfn.com/Article/details/gtrhabmsgn.html

[R27] 算术展开
来源：http://dali.yj202588.top/Article/details/gtcqfsmybo.html

echo $((1 + 2 * 3))
来源：http://dali.guowangkeji.top/Article/details/gtztdxbivm.html

[R28] 浮点运算
来源：http://dali.xylfe.cn/Article/details/gtxwmgmsfr.html

echo "scale=2; 10/3" | bc
来源：http://dali.9152youxi.cn/Article/details/gtwjyertyf.html

[R29] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gtjjbdeddy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.havefunace.top/Article/details/gtfjmnxyat.html

[R30] 函数返回状态码
来源：http://dali.316326.xyz/Article/details/gtfxviwygm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cashguo.top/Article/details/gtoznqsyeh.html

[R31] 局部变量
来源：http://dali.iojbl.cn/Article/details/gtaaedlxrw.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnqzz.top/Article/details/gtfeyerswf.html

[R32] 参数个数校验
来源：http://dali.ybcxt.top/Article/details/gtupwtptls.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gtgldyhrxd.html

[R33] 捕获错误并提示行号
来源：http://dali.wangdashe.top/Article/details/gtfbavdoed.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gzhubu.top/Article/details/gtcfacucln.html

[R34] 退出时清理
来源：http://dali.redwolf501.top/Article/details/gtqjgdszsv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gtyubllsdf.html

[R35] 后台执行并等待
来源：http://dali.nanxuanxn.top/Article/details/gthlwedjnr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nanxuanxn.top/Article/details/gtxhguiekz.html

[R36] 并发执行多个任务
来源：http://dali.pycfn.com/Article/details/gtkcgurnyc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.dianchejie.cn/Article/details/gtuykprfrt.html

[R37] 把输出赋给变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtpigzwwtm.html

files=$(ls -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvisievjl.html

[R38] 管道串联
来源：http://dali.tianlin.xyz/Article/details/gtkxmwpdyp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hfpthk.cn/Article/details/gtxdznntin.html

[R39] 重定向标准输出与错误
来源：http://dali.jqgfzy.top/Article/details/gtsontqlou.html

cmd > out.log 2>&1
来源：http://dali.xziqi.cn/Article/details/gtmndnpeel.html

[R40] 追加写日志
来源：http://dali.9152youxi.cn/Article/details/gtlslywspm.html

echo "log" >> out.log
来源：http://dali.pengpengdd.cyou/Article/details/gtvkwjbwdt.html

[R41] 丢弃输出
来源：http://dali.jlsjyb.cn/Article/details/gtlvxafykq.html

cmd >/dev/null 2>&1
来源：http://dali.hywenlv.cn/Article/details/gtsamgroqt.html

[R42] 输入重定向
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxoluaeo.html

wc -l < a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtpnmhfrbx.html

[R43] 按名字查找文件
来源：http://dali.bjfxy.top/Article/details/gtqqsmlcuv.html

find . -name "*.log" -type f
来源：http://dali.yanxiufei.cn/Article/details/gtkhqbaqnv.html

[R44] 按修改时间查找
来源：http://dali.sysykeji.top/Article/details/gtggfiiaxe.html

find . -mtime -7 -type f
来源：http://dali.shangyingyoupin.top/Article/details/gtqftxydwu.html

[R45] 批量删除
来源：http://dali.aibaodan.cn/Article/details/gtcsjzirre.html

find . -name "*.tmp" -delete
来源：http://dali.yj20258.top/Article/details/gtjfwsbygs.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangtech.top/Article/details/gtesyhtbem.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.aibaodan.cn/Article/details/gtwuqqicmx.html

[R47] sed 单行替换
来源：http://dali.0kj1m.cn/Article/details/gtjatmefny.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jianghu66.top/Article/details/gthhyagwqw.html

[R48] awk 取指定列
来源：http://dali.svipenyu.cn/Article/details/gtkfxwdvbi.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj20258.top/Article/details/gtvyffybsu.html

[R49] awk 带条件
来源：http://dali.nwbrower.top/Article/details/gtlvsgzesr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.kuanghao11.cn/Article/details/gtgfjqaoir.html

[R50] awk 求和
来源：http://dali.bjfxy.top/Article/details/gtafdthoqf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtkqgxfctu.html

[R51] 排序去重取前几
来源：http://dali.yueranfly.top/Article/details/gtvmpegmrp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhaomingkeji.xyz/Article/details/gtighpcjbo.html

[R52] 统计行数
来源：http://dali.andypj.xyz/Article/details/gtwpzshfwp.html

wc -l a.txt
来源：http://dali.zycfv.cn/Article/details/gtsnhmimzw.html

[R53] 查看文件头与实时尾
来源：http://dali.chenzaomai.com/Article/details/gtbwiveooj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgfzy.top/Article/details/gtssdlxjkv.html

[R54] 比较两个文件
来源：http://dali.iojbl.cn/Article/details/gtkbvhfatb.html

diff a.txt b.txt
来源：http://dali.yonumen.top/Article/details/gtlesosica.html

[R55] 压缩与解压
来源：http://dali.gzhubu.top/Article/details/gteseebbkm.html


<!-- 参考信息 -->