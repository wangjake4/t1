代发 wailian999

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gt2ripntlja.html

[Q09] 创建唯一索引
来源：http://dali.tanke756.top/Article/details/gt2pfuxjrvi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.svipenyu.cn/Article/details/gt2xgramrhq.html

[Q10] 插入单行
来源：http://dali.hfpthk.cn/Article/details/gt2noxwobxu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yueranfly.top/Article/details/gt2hhsunqnt.html

[Q11] 一次插入多行
来源：http://dali.shuidangran.top/Article/details/gt2dgteutdh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.meibo888.top/Article/details/gt2getpcrxw.html

[Q12] 插入后取自增 ID
来源：http://dali.daria6918.cn/Article/details/gt2wouypuij.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnqzz.top/Article/details/gt2nwqshncs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.pycfn.com/Article/details/gt2azhbhjgi.html

[Q13] 忽略重复插入
来源：http://dali.yonumen.top/Article/details/gt2emsutvgp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj202588.top/Article/details/gt2aakkndbg.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj20258.top/Article/details/gt2jobnhvli.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xuetiantiany.cn/Article/details/gt2lwkxnnyg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gaohongyu789.top/Article/details/gt2hootfndm.html

[Q15] 查询全部
来源：http://dali.9152youxi.cn/Article/details/gt2hnpzcxca.html

SELECT * FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2yxlluzde.html

[Q16] 查询指定列
来源：http://dali.chenlongwang.top/Article/details/gt2goldyclu.html

SELECT id, name FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2raxhahbn.html

[Q17] 条件查询
来源：http://dali.nwbrower.top/Article/details/gt2dejgdwxe.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hnqzz.top/Article/details/gt2bnlhpios.html

[Q18] 模糊匹配
来源：http://dali.smart0.xyz/Article/details/gt2bxisnnrp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.iojbl.cn/Article/details/gt2mfxnuwoy.html

[Q19] 范围查询
来源：http://dali.ydzc1.top/Article/details/gt2vlthlbdd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.mhx1999.top/Article/details/gt2plnyjtqm.html

[Q20] IN 列表
来源：http://dali.cheryme.top/Article/details/gt2gjwtljyb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cdnleiting.top/Article/details/gt2occtiqbh.html

[Q21] 空值判断
来源：http://dali.cucudq.cn/Article/details/gt2zemilczm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.kuanghao11.cn/Article/details/gt2oyvnrcbx.html

[Q22] 排序
来源：http://dali.yueranfly.top/Article/details/gt2zjsvdyjx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xziqi.cn/Article/details/gt2ikuydwsf.html

[Q23] 分页
来源：http://dali.hnqzz.top/Article/details/gt2hqybztnt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ydzc1.top/Article/details/gt2jwckslds.html

[Q24] 去重
来源：http://dali.zhiwuduotai.top/Article/details/gt2sctoolvs.html

SELECT DISTINCT city FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2rqcmbsdf.html

[Q25] 只取前 N 条
来源：http://dali.ydzc1.top/Article/details/gt2tbuiwqgv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.fengsongda.top/Article/details/gt2fettyzps.html

[Q26] 计数
来源：http://dali.chenjidiqi.icu/Article/details/gt2iwrwwwyo.html

SELECT COUNT(*) FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2iidgjxpu.html

[Q27] 条件计数
来源：http://dali.jlsjyb.cn/Article/details/gt2sbfsycpo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2newsnsac.html

[Q28] 求和与平均
来源：http://dali.sxryk.cn/Article/details/gt2dsqmqbvc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2rolcvjjt.html

[Q29] 最大最小值
来源：http://dali.hnqzz.top/Article/details/gt2jaocvpjy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vtgqymry.html

[Q30] 分组统计
来源：http://dali.yuanzhike.top/Article/details/gt2gcmbwujb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jctdhtoq.html

[Q31] 分组后过滤
来源：http://dali.meibo888.top/Article/details/gt2oiqnseck.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.c1oappe.top/Article/details/gt2pxggkvau.html

[Q32] 分组拼接字符串
来源：http://dali.birdmap.top/Article/details/gt2lfhhjwuc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gt2tlcagudw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bpugyizb.html

[Q33] 多列分组
来源：http://dali.redwolf501.top/Article/details/gt2cxlgsmck.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hysaishi.cn/Article/details/gt2fpkqrtyx.html

[Q34] 每组取第一条
来源：http://dali.dianchejie.cn/Article/details/gt2rwxdbrlk.html

SELECT * FROM (
来源：http://dali.0kj1m.cn/Article/details/gt2jdxybfgb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhiwuduotai.top/Article/details/gt2rbehdgru.html

) t WHERE rn = 1;
来源：http://dali.mhx1999.top/Article/details/gt2dxgzvhrn.html

[Q35] 内连接
来源：http://dali.ybcxt.top/Article/details/gt2jwpfemuj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gt2lyjhrpxe.html

[Q36] 左连接
来源：http://dali.jinqigufen.top/Article/details/gt2gvzgulxt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuanzx.com/Article/details/gt2zjtxwhps.html

[Q37] 右连接
来源：http://dali.smart0.xyz/Article/details/gt2lbmwaqel.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cdnleiting.top/Article/details/gt2hhhskhgw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.bjfxy.top/Article/details/gt2oiwppftm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2gcaerctu.html

[Q39] 自连接（查上下级）
来源：http://dali.yj202588.top/Article/details/gt2wuiwwlmb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jlsjyb.cn/Article/details/gt2xecdvwfa.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.vqdsnc.cn/Article/details/gt2gyxhsgtd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangshuangyany.cn/Article/details/gt2rbyfhwoo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xuanzx.com/Article/details/gt2dbymbdso.html

[Q41] 多表连接
来源：http://dali.cdnleiting.top/Article/details/gt2piyqasnq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.redwolf501.top/Article/details/gt2ruyivcqz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinqigufen.top/Article/details/gt2xchgyqln.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hfpthk.cn/Article/details/gt2gypkhuus.html

[Q42] 连接条件附加过滤
来源：http://dali.ppjwa.cn/Article/details/gt2qkcjtkij.html

SELECT u.name, o.amount FROM users u
来源：http://dali.vqdsnc.cn/Article/details/gt2xdhsdxve.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sufxvd.cn/Article/details/gt2ztbeabdi.html

[Q43] 标量子查询
来源：http://dali.jinqigfzy.top/Article/details/gt2sqaoouqn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dianchejie.cn/Article/details/gt2ianaixxe.html

[Q44] IN 子查询
来源：http://dali.yangfankeji.com/Article/details/gt2zxzzurms.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gotoacloud.top/Article/details/gt2umfarevl.html

[Q45] EXISTS 判断存在
来源：http://dali.yangfankeji.com/Article/details/gt2vsyzutzl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yongpay.top/Article/details/gt2ygidcbbv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.nanxuanxn.top/Article/details/gt2jojxraco.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangdashe.top/Article/details/gt2rcuzzlvc.html

[Q47] 与平均值比较
来源：http://dali.quarkkingdee.top/Article/details/gt2dbcmdnpd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnxiangtu.top/Article/details/gt2rnhkljvm.html

[Q48] CTE 公用表表达式
来源：http://dali.xinyue.icu/Article/details/gt2djzzptmi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.smart0.xyz/Article/details/gt2iyxqtdcs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.feifeiyinyue.top/Article/details/gt2vcwsopry.html

[Q49] 更新单行
来源：http://dali.ybcxt.top/Article/details/gt2yzsnqvwg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gaohongyu789.top/Article/details/gt2cmuarzvk.html

[Q50] 批量更新
来源：http://dali.xuetiantiany.cn/Article/details/gt2dynazenj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xinyue.icu/Article/details/gt2adgtpquu.html

[Q51] 用子查询更新
来源：http://dali.fengsongda.top/Article/details/gt2moftxlgh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gotoacloud.top/Article/details/gt2gujlafhd.html

[Q52] 删除指定行
来源：http://dali.0kj1m.cn/Article/details/gt2qmcavbuz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gt2minaufex.html

[Q53] 按条件删除
来源：http://dali.gzhubu.top/Article/details/gt2zgcxwhtc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yangfankeji.com/Article/details/gt2gkqoxvrq.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgkcies.html

TRUNCATE TABLE logs;
来源：http://dali.zdqjudy.top/Article/details/gt2kggqpzfc.html

[Q55] 排名（并列占位）
来源：http://dali.bjfxy.top/Article/details/gt2lbnmajta.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.andypj.xyz/Article/details/gt2symzthqt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jlsjyb.cn/Article/details/gt2sclvkfwd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.daria6918.cn/Article/details/gt2oihsnxlj.html

[Q57] 行号
来源：http://dali.ydzc1.top/Article/details/gt2inqrssfq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2gwphjovr.html

[Q58] 累计求和
来源：http://dali.yonumen.top/Article/details/gt2icpkcpml.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gt2atufsxey.html

[Q59] 分组内累计
来源：http://dali.zhoulong.xyz/Article/details/gt2jytbebid.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2qlytsckp.html

[Q60] 取上一行 / 下一行
来源：http://dali.redwolf501.top/Article/details/gt2qdcbccan.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xylfe.cn/Article/details/gt2oawhorht.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2hklgvoja.html

[Q61] 移动平均
来源：http://dali.dianchejie.cn/Article/details/gt2fcitjwmf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2zriehmbi.html

[Q62] 分组占比
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qqvxwugr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gt2nshhgkqc.html

[Q63] 开启事务
来源：http://dali.svipenyu.cn/Article/details/gt2fyxnrehf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jiagoushi.top/Article/details/gt2bltvoaes.html

[Q64] 提交事务
来源：http://dali.redwolf501.top/Article/details/gt2jkdzsywc.html

COMMIT;
来源：http://dali.pycfn.com/Article/details/gt2mruncupr.html

[Q65] 回滚事务
来源：http://dali.xziqi.cn/Article/details/gt2vuoixjpu.html

ROLLBACK;
来源：http://dali.jiagoushi.top/Article/details/gt2dkxjkyhn.html

[Q66] 行锁查询
来源：http://dali.shzxlz.cn/Article/details/gt2couyxyad.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hysaishi.cn/Article/details/gt2eusekbej.html

[Q67] 设置隔离级别
来源：http://dali.tanke756.top/Article/details/gt2ucknmkdj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cqqwz.cn/Article/details/gt2cethglax.html

[Q68] 保存点
来源：http://dali.jyoumei.cn/Article/details/gt2vtihcdbe.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkwdfeu.html

ROLLBACK TO sp1;
来源：http://dali.jinqigfzy.top/Article/details/gt2amfjnqbj.html

[Q69] 查看执行计划
来源：http://dali.yueranfly.top/Article/details/gt2jgilnole.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.guowangkeji.top/Article/details/gt2yrjklwfm.html

[Q70] 更新统计信息
来源：http://dali.chenlongwang.top/Article/details/gt2oogivria.html

ANALYZE TABLE users;
来源：http://dali.jiagoushi.top/Article/details/gt2rtldoytj.html

[Q71] 查看建表语句
来源：http://dali.daxiang520.top/Article/details/gt2tglxvunv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yonumen.top/Article/details/gt2dizawmej.html

[Q72] 查看索引
来源：http://dali.smart0.xyz/Article/details/gt2gxvsjdmo.html

SHOW INDEX FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2csqbmhpz.html

[Q73] 查看表状态
来源：http://dali.chenlongwang.top/Article/details/gt2bgmhczyw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ojtzxaig.html

[Q74] 强制使用索引
来源：http://dali.xinyue.icu/Article/details/gt2dlkcwjoz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gotoacloud.top/Article/details/gt2xyxcgjmr.html

[Q75] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gt2xsnlsmgi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2dxbtaeai.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zycfv.cn/Article/details/gt2wocsbywy.html

[Q76] 按天统计
来源：http://dali.yj202588.top/Article/details/gt2ouujcyxj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhixingplan.top/Article/details/gt2vaihtlqr.html

[Q77] 时间加减
来源：http://dali.guowangkeji.top/Article/details/gt2ahhlmnhs.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hysaishi.cn/Article/details/gt2txubzkyx.html

[Q78] 当前时间
来源：http://dali.ydzc1.top/Article/details/gt2fnemlmpf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuxming.cn/Article/details/gt2wxnummxk.html

[Q79] 字符串拼接
来源：http://dali.quarkkingdee.top/Article/details/gt2lfedfgzx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yongpay.top/Article/details/gt2sefizffb.html

[Q80] 字符串截取
来源：http://dali.xinyue.icu/Article/details/gt2zxpdswvw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2hauqfhsg.html

[Q81] 字符串替换
来源：http://dali.yongpay.top/Article/details/gt2brducpht.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2vmmcxbzz.html

[Q82] 字符长度与字节长度
来源：http://dali.nanxinkj.top/Article/details/gt2kisxnhlt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2fhxtkrsc.html

[Q83] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gt2luhlhtlf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2efmaytfw.html

[Q84] 去除首尾空格
来源：http://dali.mhx1999.top/Article/details/gt2spijtrrg.html

SELECT TRIM(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2mpwtcwnf.html

[Q85] 数值取整
来源：http://dali.jinqigfzy.top/Article/details/gt2foignumy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenlongwang.top/Article/details/gt2lqrtnips.html

[Q86] 读取 JSON 字段
来源：http://dali.nanxuanxn.top/Article/details/gt2ocgsdtem.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hysaishi.cn/Article/details/gt2chvedxwz.html

[Q87] JSON 字段做条件
来源：http://dali.yj20258888.top/Article/details/gt2hkpazggl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.fzhhl.top/Article/details/gt2kenkvrzf.html

[Q88] 行转列（条件聚合）
来源：http://dali.0kj1m.cn/Article/details/gt2sxrcycax.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xziqi.cn/Article/details/gt2jlmakykb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2qusdxegm.html

[Q89] 判断表是否存在
来源：http://dali.jiagoushi.top/Article/details/gt2dryebgmo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gzhubu.top/Article/details/gt2kkbntqcg.html

[Q90] 生成序号列
来源：http://dali.xuanzx.com/Article/details/gt2exewupvk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.iojbl.cn/Article/details/gt2vrlacfuw.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2tvmulsmv.html

R. Bash 专题
来源：http://dali.quarkkingdee.top/Article/details/gt2pyefunlm.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jhgmevkc.html

[R01] shebang 与严格模式
来源：http://dali.bjfxy.top/Article/details/gt2keojalbw.html

#!/usr/bin/env bash
来源：http://dali.gaohongyu789.top/Article/details/gt2iiaqnepl.html

set -euo pipefail
来源：http://dali.yanxiufei.cn/Article/details/gt2cryuqiyg.html

[R02] 变量赋值与使用
来源：http://dali.jinqigufen.top/Article/details/gt2iyoxygze.html

name="Tom"; echo "$name"
来源：http://dali.andypj.xyz/Article/details/gt2qawwuumt.html

[R03] 只读变量
来源：http://dali.sufxvd.cn/Article/details/gt2vabdigps.html

readonly PI=3.14
来源：http://dali.pengpengdd.cyou/Article/details/gt2isbmykiz.html

[R04] 位置参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2eiseeyhy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.mhx1999.top/Article/details/gt2uzqbhlfy.html

[R05] 参数默认值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rojofgun.html

name="${1:-default}"
来源：http://dali.tian-w.cn/Article/details/gt2rhinldsg.html

[R06] 判断命令是否存在
来源：http://dali.kuanghao11.cn/Article/details/gt2gvoznugc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aizwys.cn/Article/details/gt2oajjwzng.html

[R07] if 判断文件
来源：http://dali.jqgufenzy.top/Article/details/gt2rvfnltoc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnqzz.top/Article/details/gt2girxdxsb.html

[R08] 数值比较
来源：http://dali.jqgufenzy.top/Article/details/gt2tpmqqjzr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gt2yjvkojrc.html

[R09] 字符串比较
来源：http://dali.chenzaomai.com/Article/details/gt2dkavqtjm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jiagoushi.top/Article/details/gt2dalglmxx.html

[R10] 正则匹配
来源：http://dali.quarkkingdee.top/Article/details/gt2tmuhewqo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jianghu66.top/Article/details/gt2uyrrztzh.html

[R11] case 多分支
来源：http://dali.redwolf501.top/Article/details/gt2xspzezyc.html

case "$1" in
来源：http://dali.sufxvd.cn/Article/details/gt2mjrrnbvr.html

start) echo "启动" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ooolsiqz.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwdsdsj.html

*)     echo "未知命令" ;;
来源：http://dali.pycfn.com/Article/details/gt2qbtvtqxj.html

esac
来源：http://dali.pengpengdd.cyou/Article/details/gt2ujfnbsmm.html

[R12] for 遍历文件
来源：http://dali.birdmap.top/Article/details/gt2staleotb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ivvv.top/Article/details/gt2whkjhiko.html

[R13] for 计数循环
来源：http://dali.sufxvd.cn/Article/details/gt2bvnpfevo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.dashuyun.cn/Article/details/gt2uwvbgqml.html

[R14] C 风格 for
来源：http://dali.fzhhl.top/Article/details/gt2xublbhjl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tanke756.top/Article/details/gt2hhqlpuej.html

[R15] while 逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gt2mjndlsyp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ichfxhyl.html

[R16] until 等待条件
来源：http://dali.chenlongwang.top/Article/details/gt2avnzrzkr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gt2qdkdient.html

[R17] 数组定义与取值
来源：http://dali.yj20258.top/Article/details/gt2igkecunu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hnxiangtu.top/Article/details/gt2chuyendx.html

[R18] 遍历数组
来源：http://dali.ydzc1.top/Article/details/gt2syuplcyz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yueranfly.top/Article/details/gt2fzjurayh.html

[R19] 数组长度
来源：http://dali.bjfxy.top/Article/details/gt2gzrdgqfu.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fpamfgvp.html

[R20] 关联数组（字典）
来源：http://dali.aibaodan.cn/Article/details/gt2ufhfpbxy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cashguo.top/Article/details/gt2lsywwcmd.html

[R21] 字符串长度
来源：http://dali.hnxiangtu.top/Article/details/gt2swidakic.html

echo "${#s}"
来源：http://dali.hnxiangtu.top/Article/details/gt2dnbvhetk.html

[R22] 截取子串
来源：http://dali.pycfn.com/Article/details/gt2ftrebnwb.html

echo "${s:0:5}"
来源：http://dali.shuidangran.top/Article/details/gt2qwfvqwtp.html

[R23] 字符串替换
来源：http://dali.tian-w.cn/Article/details/gt2olnqkjbn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yvedp.cn/Article/details/gt2yduyhkfx.html

[R24] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gt2gqdtfabl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xylfe.cn/Article/details/gt2rvccgmqs.html

[R25] 去后缀 / 去前缀
来源：http://dali.yonumen.top/Article/details/gt2wtcreqmn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgfzy.top/Article/details/gt2fvkapxbn.html

[R26] 命令替换
来源：http://dali.nanxinkj.top/Article/details/gt2zfpsnyyd.html

now=$(date +%F); echo "$now"
来源：http://dali.birdmap.top/Article/details/gt2ucejizpn.html

[R27] 算术展开
来源：http://dali.guannengcc.top/Article/details/gt2hibtecnu.html

echo $((1 + 2 * 3))
来源：http://dali.0kj1m.cn/Article/details/gt2yuldbbcu.html

[R28] 浮点运算
来源：http://dali.cqqwz.cn/Article/details/gt2oaqvbxqu.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnqzz.top/Article/details/gt2rjdrkxrv.html

[R29] 定义函数
来源：http://dali.meibo888.top/Article/details/gt2jqoclaeo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gzhubu.top/Article/details/gt2grejxqzu.html

[R30] 函数返回状态码
来源：http://dali.dianchejie.cn/Article/details/gt2ykscniqw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.quarkkingdee.top/Article/details/gt2oehfudch.html

[R31] 局部变量
来源：http://dali.jinqigufen.top/Article/details/gt2qnvgmqcg.html

f() { local x=1; echo "$x"; }
来源：http://dali.cashguo.top/Article/details/gt2thniscez.html

[R32] 参数个数校验
来源：http://dali.cqqwz.cn/Article/details/gt2juagylch.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.iojbl.cn/Article/details/gt2vtlbfagu.html

[R33] 捕获错误并提示行号
来源：http://dali.jiagoushi.top/Article/details/gt2bsieurxi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ufypmztk.html

[R34] 退出时清理
来源：http://dali.feifeiyinyue.top/Article/details/gt2lvpisrfd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sufxvd.cn/Article/details/gt2koeltzks.html

[R35] 后台执行并等待
来源：http://dali.hfpthk.cn/Article/details/gt2jcdvcqor.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shzxlz.cn/Article/details/gt2bbrkjbwv.html

[R36] 并发执行多个任务
来源：http://dali.yj20258888.top/Article/details/gt2bvcsvlch.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yvedp.cn/Article/details/gt2wfpfkkuc.html

[R37] 把输出赋给变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2faaljuzd.html

files=$(ls -1)
来源：http://dali.gaohongyu789.top/Article/details/gt2ttasspzf.html

[R38] 管道串联
来源：http://dali.yueranfly.top/Article/details/gt2ffgsxiyr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tianlin.xyz/Article/details/gt2jocwojxg.html

[R39] 重定向标准输出与错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xvcxugcm.html

cmd > out.log 2>&1
来源：http://dali.aizwys.cn/Article/details/gt2dgvugian.html

[R40] 追加写日志
来源：http://dali.ppjwa.cn/Article/details/gt2xqbpyrbj.html

echo "log" >> out.log
来源：http://dali.bjfxy.top/Article/details/gt2scpgkodk.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangtech.top/Article/details/gt2toiceylr.html

cmd >/dev/null 2>&1
来源：http://dali.hammf.cn/Article/details/gt2pxhxvuau.html

[R42] 输入重定向
来源：http://dali.yvedp.cn/Article/details/gt2yxvzavqj.html

wc -l < a.txt
来源：http://dali.zdqjudy.top/Article/details/gt2krenawwr.html

[R43] 按名字查找文件
来源：http://dali.aizwys.cn/Article/details/gt2lbenoxjf.html

find . -name "*.log" -type f
来源：http://dali.zhixingplan.top/Article/details/gt2pbspmnda.html

[R44] 按修改时间查找
来源：http://dali.andypj.xyz/Article/details/gt2fokbakve.html

find . -mtime -7 -type f
来源：http://dali.redwolf501.top/Article/details/gt2qbggojgq.html

[R45] 批量删除
来源：http://dali.quarkkingdee.top/Article/details/gt2zvtmbknx.html

find . -name "*.tmp" -delete
来源：http://dali.shangyingyoupin.top/Article/details/gt2oguqoqas.html

[R46] 递归替换文件内容
来源：http://dali.tianlin.xyz/Article/details/gt2cvvrxnxj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.quarkkingdee.top/Article/details/gt2fwziwjxn.html

[R47] sed 单行替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vsxvmjoh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tanke756.top/Article/details/gt2ycbpeqag.html

[R48] awk 取指定列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fzkviuph.html

awk '{print $1, $3}' a.txt
来源：http://dali.yongpay.top/Article/details/gt2cfinqrhx.html

[R49] awk 带条件
来源：http://dali.c1oappe.top/Article/details/gt2tejxbfvo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.pengpengdd.cyou/Article/details/gt2khocszcy.html

[R50] awk 求和
来源：http://dali.hfpthk.cn/Article/details/gt2wfulaxzm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2jeirvnfy.html

[R51] 排序去重取前几
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yaylwnjp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2orayykkz.html

[R52] 统计行数
来源：http://dali.9152youxi.cn/Article/details/gt2jgqadhtj.html

wc -l a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2lpimrqay.html

[R53] 查看文件头与实时尾
来源：http://dali.tianlin.xyz/Article/details/gt2wdvbezjd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ehwqpu.com/Article/details/gt2uswdcyfb.html

[R54] 比较两个文件
来源：http://dali.iojbl.cn/Article/details/gt2mdnyrkpk.html

diff a.txt b.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2pqdncvaf.html

[R55] 压缩与解压
来源：http://dali.andypj.xyz/Article/details/gt2xmlvwazt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.meibo888.top/Article/details/gt2bqjujsrb.html

[R56] 远程拷贝
来源：http://dali.yongpay.top/Article/details/gt2iismfpus.html

scp file user@host:/path/
来源：http://dali.chenjidiqi.icu/Article/details/gt2lomifvsz.html

[R57] 远程执行命令
来源：http://dali.316326.xyz/Article/details/gt2gijhwqzo.html


<!-- 参考信息 -->