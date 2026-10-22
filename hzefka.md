代发 wailian999

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gtqczbgdlj.html

[Q09] 创建唯一索引
来源：http://dali.hfpthk.cn/Article/details/gtmnscsmvo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gtsocedqni.html

[Q10] 插入单行
来源：http://dali.sysykeji.top/Article/details/gtsnckwpsi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gtoaainsmc.html

[Q11] 一次插入多行
来源：http://dali.guannengcc.top/Article/details/gtlizwhdxw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.0kj1m.cn/Article/details/gtngugvhoc.html

[Q12] 插入后取自增 ID
来源：http://dali.pycfn.com/Article/details/gtacynizig.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinqigufen.top/Article/details/gtmccwoxbs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gaohongyu789.top/Article/details/gtaixaykjb.html

[Q13] 忽略重复插入
来源：http://dali.meibo888.top/Article/details/gtswxgiilh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dianchejie.cn/Article/details/gtxkepahiq.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuetiantiany.cn/Article/details/gtdmydifaf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.c1oappe.top/Article/details/gthdkxcive.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yangfankeji.com/Article/details/gtdcfopada.html

[Q15] 查询全部
来源：http://dali.yueranfly.top/Article/details/gtlnkmwook.html

SELECT * FROM users;
来源：http://dali.yonumen.top/Article/details/gtnyzxcrti.html

[Q16] 查询指定列
来源：http://dali.yj202588.top/Article/details/gtdyrdujsg.html

SELECT id, name FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtzwyrkrzg.html

[Q17] 条件查询
来源：http://dali.nwbrower.top/Article/details/gthdglxque.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hnqzz.top/Article/details/gtummczaov.html

[Q18] 模糊匹配
来源：http://dali.ehwqpu.com/Article/details/gtvawnvaer.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj202588.top/Article/details/gtonxldibe.html

[Q19] 范围查询
来源：http://dali.chenzaomai.com/Article/details/gtkbveyrng.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ydzc1.top/Article/details/gtwbpecdni.html

[Q20] IN 列表
来源：http://dali.gotoacloud.top/Article/details/gtewfndvhr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtixyussao.html

[Q21] 空值判断
来源：http://dali.hywenlv.cn/Article/details/gtbvmahkwa.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zdqjudy.top/Article/details/gtdbxbuofv.html

[Q22] 排序
来源：http://dali.nanxinkj.top/Article/details/gtahcrllqi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fengsongda.top/Article/details/gtdylfdxli.html

[Q23] 分页
来源：http://dali.cucudq.cn/Article/details/gtdhjppirr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj202588.top/Article/details/gtqasebbpg.html

[Q24] 去重
来源：http://dali.hywenlv.cn/Article/details/gtydwazwlo.html

SELECT DISTINCT city FROM users;
来源：http://dali.aibaodan.cn/Article/details/gthpnxidtn.html

[Q25] 只取前 N 条
来源：http://dali.zycfv.cn/Article/details/gtngxsneik.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shanyushiyangtech.top/Article/details/gtcynaxttm.html

[Q26] 计数
来源：http://dali.hnqzz.top/Article/details/gtezrdgtpt.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbmvbars.html

[Q27] 条件计数
来源：http://dali.gogol.net.cn/Article/details/gtgcgrytmz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ybcxt.top/Article/details/gtdeixzehq.html

[Q28] 求和与平均
来源：http://dali.cucudq.cn/Article/details/gtbaeuqxwz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.havefunace.top/Article/details/gtnwwerhoq.html

[Q29] 最大最小值
来源：http://dali.shangyingyoupin.top/Article/details/gtnjqlomxd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtjukxmhco.html

[Q30] 分组统计
来源：http://dali.ydzc1.top/Article/details/gtkpueybhf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gtumcdcesa.html

[Q31] 分组后过滤
来源：http://dali.yongpay.top/Article/details/gtoumfjnoi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nwbrower.top/Article/details/gtuxxcmdix.html

[Q32] 分组拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtgfeeqwjw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gttmyfthlc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shangyingyoupin.top/Article/details/gtaclpysle.html

[Q33] 多列分组
来源：http://dali.hnqzz.top/Article/details/gtskrvzftv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj20258.top/Article/details/gttfouvovk.html

[Q34] 每组取第一条
来源：http://dali.ivvv.top/Article/details/gtpazltazf.html

SELECT * FROM (
来源：http://dali.shzxlz.cn/Article/details/gtvrsudtia.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gogol.net.cn/Article/details/gtkhmwmirm.html

) t WHERE rn = 1;
来源：http://dali.gzhubu.top/Article/details/gtzllzshbe.html

[Q35] 内连接
来源：http://dali.pycfn.com/Article/details/gtslktkyce.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jyoumei.cn/Article/details/gtvbcrlrkt.html

[Q36] 左连接
来源：http://dali.vqdsnc.cn/Article/details/gtxutyzmqg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.pengpengdd.cyou/Article/details/gtaezfsszw.html

[Q37] 右连接
来源：http://dali.cashguo.top/Article/details/gthfzbijqm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.havefunace.top/Article/details/gtvtmquloe.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.feifeiyinyue.top/Article/details/gtustcnjob.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nwbrower.top/Article/details/gtgohqvvwv.html

[Q39] 自连接（查上下级）
来源：http://dali.cucudq.cn/Article/details/gtflpjuzcl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.kuanghao11.cn/Article/details/gtgmlmubip.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.meibo888.top/Article/details/gtpaxgvkzq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gzhubu.top/Article/details/gtkavotmwd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hnxiangtu.top/Article/details/gtvodywugm.html

[Q41] 多表连接
来源：http://dali.gaohongyu789.top/Article/details/gtmelpspxz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinghuilouyu.cn/Article/details/gttxbkdods.html

JOIN users u ON u.id = o.user_id
来源：http://dali.9152youxi.cn/Article/details/gtdidfdalk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.316326.xyz/Article/details/gtyurawjko.html

[Q42] 连接条件附加过滤
来源：http://dali.cucudq.cn/Article/details/gtqiipjsma.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangtech.top/Article/details/gtwiqbfyln.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj202588.top/Article/details/gtccaefqrm.html

[Q43] 标量子查询
来源：http://dali.feifeiyinyue.top/Article/details/gtkxaleiqh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenzaomai.com/Article/details/gtsqyflbxt.html

[Q44] IN 子查询
来源：http://dali.tanke756.top/Article/details/gtggeeiwnn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkfqidmn.html

[Q45] EXISTS 判断存在
来源：http://dali.9152youxi.cn/Article/details/gtptzjfbvv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gtfzjqucdc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgufenzy.top/Article/details/gtqzowfabq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jiagoushi.top/Article/details/gtnexphzcx.html

[Q47] 与平均值比较
来源：http://dali.cashguo.top/Article/details/gtkukkqcnx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hysaishi.cn/Article/details/gtfpkuzzmy.html

[Q48] CTE 公用表表达式
来源：http://dali.cdnleiting.top/Article/details/gtdmrybfnm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhiwuduotai.top/Article/details/gtdzvuebve.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jyoumei.cn/Article/details/gtdvtqlktr.html

[Q49] 更新单行
来源：http://dali.sysykeji.top/Article/details/gtqbfgkyzb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fengsongda.top/Article/details/gtclbpzdgc.html

[Q50] 批量更新
来源：http://dali.ppjwa.cn/Article/details/gtzwarqira.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gogol.net.cn/Article/details/gtzgzyaqxy.html

[Q51] 用子查询更新
来源：http://dali.nanxinkj.top/Article/details/gtmiknopqk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.fzhhl.top/Article/details/gtbaakzfsv.html

[Q52] 删除指定行
来源：http://dali.wangdashe.top/Article/details/gtjpjvebdo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtvsmlorpj.html

[Q53] 按条件删除
来源：http://dali.dianchejie.cn/Article/details/gtvjpouack.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.c1oappe.top/Article/details/gtkqemgtmu.html

[Q54] 清空表
来源：http://dali.cqqwz.cn/Article/details/gttdmzlybp.html

TRUNCATE TABLE logs;
来源：http://dali.nwbrower.top/Article/details/gtlelzflwy.html

[Q55] 排名（并列占位）
来源：http://dali.daxiang520.top/Article/details/gteohisnvn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ybcxt.top/Article/details/gtlogdlrrl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnsxxhsgb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhengqikj.top/Article/details/gtskllcqcb.html

[Q57] 行号
来源：http://dali.cdnleiting.top/Article/details/gtpujasgep.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gtustdtiwd.html

[Q58] 累计求和
来源：http://dali.kuanghao11.cn/Article/details/gttfvoxgle.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtpjbabjdo.html

[Q59] 分组内累计
来源：http://dali.hongshengwenyu.top/Article/details/gtuahtuscb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtydqxiwin.html

[Q60] 取上一行 / 下一行
来源：http://dali.wangshuangyany.cn/Article/details/gtjczzgggr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj20258.top/Article/details/gtrtrzxfak.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtxgmknwnd.html

[Q61] 移动平均
来源：http://dali.chenjidiqi.icu/Article/details/gtlyhblxya.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtvyquimde.html

[Q62] 分组占比
来源：http://dali.hammf.cn/Article/details/gtykcfsfkm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gtibwpbsta.html

[Q63] 开启事务
来源：http://dali.jqgfzy.top/Article/details/gtydazfsuc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.guannengcc.top/Article/details/gtpvcqqyaf.html

[Q64] 提交事务
来源：http://dali.wangshuangyany.cn/Article/details/gtfpujkxcf.html

COMMIT;
来源：http://dali.yj20258.top/Article/details/gtvwoetcps.html

[Q65] 回滚事务
来源：http://dali.sxryk.cn/Article/details/gtnuwehixy.html

ROLLBACK;
来源：http://dali.chenjidiqi.icu/Article/details/gtwnnvtmru.html

[Q66] 行锁查询
来源：http://dali.guannengcc.top/Article/details/gtppokmiqx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cucudq.cn/Article/details/gtizyzwhwx.html

[Q67] 设置隔离级别
来源：http://dali.zhongyouzk.top/Article/details/gtewqxpimy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigufen.top/Article/details/gtgoqhungx.html

[Q68] 保存点
来源：http://dali.tanke756.top/Article/details/gtyfiipbxl.html

SAVEPOINT sp1;
来源：http://dali.xinyue.icu/Article/details/gtyytyufss.html

ROLLBACK TO sp1;
来源：http://dali.smart0.xyz/Article/details/gtpkoczvli.html

[Q69] 查看执行计划
来源：http://dali.gogol.net.cn/Article/details/gtlzjrgyhv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhengqikj.top/Article/details/gtgsltqluy.html

[Q70] 更新统计信息
来源：http://dali.pycfn.com/Article/details/gtrnpinmks.html

ANALYZE TABLE users;
来源：http://dali.gzhubu.top/Article/details/gtzqfhbtoz.html

[Q71] 查看建表语句
来源：http://dali.yuxming.cn/Article/details/gtnkwtdwyj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zdqjudy.top/Article/details/gtgvvpigzz.html

[Q72] 查看索引
来源：http://dali.gaohongyu789.top/Article/details/gtqxodslfw.html

SHOW INDEX FROM users;
来源：http://dali.hammf.cn/Article/details/gtlhzmixnr.html

[Q73] 查看表状态
来源：http://dali.jinghuilouyu.cn/Article/details/gtqymufohn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.redwolf501.top/Article/details/gtzyyitzuq.html

[Q74] 强制使用索引
来源：http://dali.zdqjudy.top/Article/details/gtfamlmppk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenzaomai.com/Article/details/gtbfqpntzj.html

[Q75] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gtqylqgqgs.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guannengcc.top/Article/details/gthlhorqyz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xuetiantiany.cn/Article/details/gtcxvqcoul.html

[Q76] 按天统计
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbyqcctzt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yongpay.top/Article/details/gtyvrfgyux.html

[Q77] 时间加减
来源：http://dali.yuxming.cn/Article/details/gtkepqwqsa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fengsongda.top/Article/details/gtupkdusla.html

[Q78] 当前时间
来源：http://dali.hnxiangtu.top/Article/details/gtzdjnrnsv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hammf.cn/Article/details/gtxsrvrpqp.html

[Q79] 字符串拼接
来源：http://dali.cqqwz.cn/Article/details/gtqtsawvyc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ppjwa.cn/Article/details/gtwowyvsft.html

[Q80] 字符串截取
来源：http://dali.guannengcc.top/Article/details/gtkemlnjga.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cashguo.top/Article/details/gtfadjowui.html

[Q81] 字符串替换
来源：http://dali.ehwqpu.com/Article/details/gtqolcmmrk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.aibaodan.cn/Article/details/gthsikmbse.html

[Q82] 字符长度与字节长度
来源：http://dali.chenlongwang.top/Article/details/gtvfikfyel.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtoprlodbr.html

[Q83] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gtqkktxnyy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhjrcats.html

[Q84] 去除首尾空格
来源：http://dali.zhoulong.xyz/Article/details/gtiirtlkfh.html

SELECT TRIM(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtxgrssave.html

[Q85] 数值取整
来源：http://dali.ppjwa.cn/Article/details/gtutfzgywh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangdashe.top/Article/details/gtixieeldo.html

[Q86] 读取 JSON 字段
来源：http://dali.chenlongwang.top/Article/details/gtcjfxsqzg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenzaomai.com/Article/details/gtpghzphcz.html

[Q87] JSON 字段做条件
来源：http://dali.kuanghao11.cn/Article/details/gtoocbgpbw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhoulong.xyz/Article/details/gtimvnmfbd.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnqzz.top/Article/details/gtiviprtad.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shzxlz.cn/Article/details/gtjfjqleef.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtmnjlzduw.html

[Q89] 判断表是否存在
来源：http://dali.xziqi.cn/Article/details/gtgwqiygnd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tian-w.cn/Article/details/gtczaajjvt.html

[Q90] 生成序号列
来源：http://dali.ydzc1.top/Article/details/gtfwnkxkrl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.guowangkeji.top/Article/details/gthbleprcv.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtdzxospag.html

R. Bash 专题
来源：http://dali.gotoacloud.top/Article/details/gtaamlpohu.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtmrxlweym.html

[R01] shebang 与严格模式
来源：http://dali.zhengqikj.top/Article/details/gtrrzgbzes.html

#!/usr/bin/env bash
来源：http://dali.hnxiangtu.top/Article/details/gtndnecyjx.html

set -euo pipefail
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxkapvxr.html

[R02] 变量赋值与使用
来源：http://dali.9152youxi.cn/Article/details/gtnujalrbd.html

name="Tom"; echo "$name"
来源：http://dali.bjfxy.top/Article/details/gtgcchpmre.html

[R03] 只读变量
来源：http://dali.guowangkeji.top/Article/details/gtbfodktxo.html

readonly PI=3.14
来源：http://dali.chenlongwang.top/Article/details/gtwlmeyerr.html

[R04] 位置参数
来源：http://dali.316326.xyz/Article/details/gtpckkwuod.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yongpay.top/Article/details/gtkhibgtgp.html

[R05] 参数默认值
来源：http://dali.nanxuanxn.top/Article/details/gtgpricfrx.html

name="${1:-default}"
来源：http://dali.hnxiangtu.top/Article/details/gtwtxjyuwz.html

[R06] 判断命令是否存在
来源：http://dali.fengsongda.top/Article/details/gtusdzrllx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nwbrower.top/Article/details/gtzkvvnrmj.html

[R07] if 判断文件
来源：http://dali.jqgufenzy.top/Article/details/gtxopkcnws.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ivvv.top/Article/details/gtxlbxmrcc.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gtcmzfqwzt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtoiciasvm.html

[R09] 字符串比较
来源：http://dali.hammf.cn/Article/details/gttezetfps.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ppjwa.cn/Article/details/gtwzgjnwas.html

[R10] 正则匹配
来源：http://dali.yj202588.top/Article/details/gtuephjqrr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtxyujcpvj.html

[R11] case 多分支
来源：http://dali.jlsjyb.cn/Article/details/gtbaxebeue.html

case "$1" in
来源：http://dali.tanke756.top/Article/details/gtjnrieurm.html

start) echo "启动" ;;
来源：http://dali.zhixingplan.top/Article/details/gtuwvhsafn.html

stop)  echo "停止" ;;
来源：http://dali.andypj.xyz/Article/details/gthynprylr.html

*)     echo "未知命令" ;;
来源：http://dali.hywenlv.cn/Article/details/gthdhglkpb.html

esac
来源：http://dali.jinqigfzy.top/Article/details/gtfnmpgdmv.html

[R12] for 遍历文件
来源：http://dali.ppjwa.cn/Article/details/gtdatkkcob.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sufxvd.cn/Article/details/gtqoydmgrb.html

[R13] for 计数循环
来源：http://dali.0kj1m.cn/Article/details/gtkhctidjd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gtuenkizty.html

[R14] C 风格 for
来源：http://dali.sweek.top/Article/details/gtajarlsrt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gtvimabmrc.html

[R15] while 逐行读文件
来源：http://dali.smart0.xyz/Article/details/gtrkbaokwd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cheryme.top/Article/details/gtrrjhvicb.html

[R16] until 等待条件
来源：http://dali.ydzc1.top/Article/details/gtdxvvdqsr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gtjbhceknw.html

[R17] 数组定义与取值
来源：http://dali.chenlongwang.top/Article/details/gtmjhubslb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daxiang520.top/Article/details/gtyghyddue.html

[R18] 遍历数组
来源：http://dali.wangshuangyany.cn/Article/details/gtsdftmuqc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hysaishi.cn/Article/details/gtcfmohpil.html

[R19] 数组长度
来源：http://dali.guowangkeji.top/Article/details/gtncqstnxl.html

echo "${#arr[@]}"
来源：http://dali.xylfe.cn/Article/details/gtrkftxcvm.html

[R20] 关联数组（字典）
来源：http://dali.iojbl.cn/Article/details/gtohrlchjr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daria6918.cn/Article/details/gtztkanxyc.html

[R21] 字符串长度
来源：http://dali.tianlin.xyz/Article/details/gtefyudykx.html

echo "${#s}"
来源：http://dali.zhiwuduotai.top/Article/details/gtvogeualf.html

[R22] 截取子串
来源：http://dali.smart0.xyz/Article/details/gtikiyhrqw.html

echo "${s:0:5}"
来源：http://dali.chenjidiqi.icu/Article/details/gtrhbfmzmq.html

[R23] 字符串替换
来源：http://dali.yangfankeji.com/Article/details/gtvweqfesg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrundapd.html

[R24] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhmcijqt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hongshengwenyu.top/Article/details/gtkhyeodmb.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhiwuduotai.top/Article/details/gtpepmnysa.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.meibo888.top/Article/details/gtxwphlkfk.html

[R26] 命令替换
来源：http://dali.vqdsnc.cn/Article/details/gtcjageybc.html

now=$(date +%F); echo "$now"
来源：http://dali.jyoumei.cn/Article/details/gtlqyzloeu.html

[R27] 算术展开
来源：http://dali.yueranfly.top/Article/details/gtxlsccdgk.html

echo $((1 + 2 * 3))
来源：http://dali.guowangkeji.top/Article/details/gtavuxeshy.html

[R28] 浮点运算
来源：http://dali.ivvv.top/Article/details/gtdvlefhwm.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnqzz.top/Article/details/gtmakfgzma.html

[R29] 定义函数
来源：http://dali.meibo888.top/Article/details/gtbldjohod.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jianghu66.top/Article/details/gtruvhnjdv.html

[R30] 函数返回状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpfixjss.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenzaomai.com/Article/details/gthxmxisms.html

[R31] 局部变量
来源：http://dali.zhengqikj.top/Article/details/gtymxkield.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258.top/Article/details/gtymanamna.html

[R32] 参数个数校验
来源：http://dali.tanke756.top/Article/details/gtjsfjkjth.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gtccousyil.html

[R33] 捕获错误并提示行号
来源：http://dali.redwolf501.top/Article/details/gtzanoljda.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvztmoztb.html

[R34] 退出时清理
来源：http://dali.jlsjyb.cn/Article/details/gtagazyaqo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gtxcsctnrx.html

[R35] 后台执行并等待
来源：http://dali.yuanzhike.top/Article/details/gttilhdfae.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmqiijye.html

[R36] 并发执行多个任务
来源：http://dali.nwbrower.top/Article/details/gtlowqgcbn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.mhx1999.top/Article/details/gttvqpatid.html

[R37] 把输出赋给变量
来源：http://dali.andypj.xyz/Article/details/gtkpdansnv.html

files=$(ls -1)
来源：http://dali.chenzaomai.com/Article/details/gtqybgcdim.html

[R38] 管道串联
来源：http://dali.wangdashe.top/Article/details/gthpzxuape.html

cat a.txt | grep -i error | wc -l
来源：http://dali.dianchejie.cn/Article/details/gtnquiiohh.html

[R39] 重定向标准输出与错误
来源：http://dali.nanxinkj.top/Article/details/gtfoszioia.html

cmd > out.log 2>&1
来源：http://dali.tianlin.xyz/Article/details/gtlmcezpwj.html

[R40] 追加写日志
来源：http://dali.hnxiangtu.top/Article/details/gtseobwtyi.html

echo "log" >> out.log
来源：http://dali.snrcjt.cn/Article/details/gtkuyzliih.html

[R41] 丢弃输出
来源：http://dali.kuanghao11.cn/Article/details/gtdkajybvg.html

cmd >/dev/null 2>&1
来源：http://dali.jyoumei.cn/Article/details/gtfnisxhpx.html

[R42] 输入重定向
来源：http://dali.aibaodan.cn/Article/details/gtssenfsfc.html

wc -l < a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmnnavpv.html

[R43] 按名字查找文件
来源：http://dali.cucudq.cn/Article/details/gtclqvlvpg.html

find . -name "*.log" -type f
来源：http://dali.fzhhl.top/Article/details/gtzqwrhrht.html

[R44] 按修改时间查找
来源：http://dali.xuanzx.com/Article/details/gtaxtkkgjh.html

find . -mtime -7 -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcoetzbfd.html

[R45] 批量删除
来源：http://dali.xuanzx.com/Article/details/gtlnlhrrvn.html

find . -name "*.tmp" -delete
来源：http://dali.ydzc1.top/Article/details/gtokzqbnmb.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangtech.top/Article/details/gtziipuibm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwtsdxtq.html

[R47] sed 单行替换
来源：http://dali.nwbrower.top/Article/details/gtuxiihupg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtfkejyebe.html

[R48] awk 取指定列
来源：http://dali.jyoumei.cn/Article/details/gtlwiudwjb.html

awk '{print $1, $3}' a.txt
来源：http://dali.shuidangran.top/Article/details/gtjhrcvqxo.html

[R49] awk 带条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfyoyglwl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhongyouzk.top/Article/details/gtiytlxxhl.html

[R50] awk 求和
来源：http://dali.nanxinkj.top/Article/details/gtwhfxydom.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cucudq.cn/Article/details/gtnnysvmpn.html

[R51] 排序去重取前几
来源：http://dali.xinyue.icu/Article/details/gtwjyxzvpl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dashuyun.cn/Article/details/gtjqzcxowu.html

[R52] 统计行数
来源：http://dali.tanke756.top/Article/details/gtskkndleb.html

wc -l a.txt
来源：http://dali.yueranfly.top/Article/details/gtbmzgbdjn.html

[R53] 查看文件头与实时尾
来源：http://dali.chenjidiqi.icu/Article/details/gtqglsezop.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aizwys.cn/Article/details/gtnnksmgdi.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gtovfpyfba.html

diff a.txt b.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtyiiuhtbd.html

[R55] 压缩与解压
来源：http://dali.zhiwuduotai.top/Article/details/gtshkblkql.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.bjfxy.top/Article/details/gtyienwcxl.html

[R56] 远程拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gtsnovcdyz.html

scp file user@host:/path/
来源：http://dali.yuxming.cn/Article/details/gtgypykwat.html

[R57] 远程执行命令
来源：http://dali.yongpay.top/Article/details/gtoeznijeu.html


<!-- 参考信息 -->