代发 wailian999

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinqigfzy.top/Article/details/gtbmdfuogs.html

[Q09] 创建唯一索引
来源：http://dali.xziqi.cn/Article/details/gthzruurgh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jianghu66.top/Article/details/gtyyivvwyn.html

[Q10] 插入单行
来源：http://dali.chenzaomai.com/Article/details/gtezgchpzl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sxryk.cn/Article/details/gtoaqcmorw.html

[Q11] 一次插入多行
来源：http://dali.zhengqikj.top/Article/details/gtvxuqmyqn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dianchejie.cn/Article/details/gtpqvnzqmp.html

[Q12] 插入后取自增 ID
来源：http://dali.sweek.top/Article/details/gtmqxznmuc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sxryk.cn/Article/details/gtpkwtrhzj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigufen.top/Article/details/gtiqicavar.html

[Q13] 忽略重复插入
来源：http://dali.yanxiufei.cn/Article/details/gtuqslclhe.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gttaepclzj.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxuanxn.top/Article/details/gtsseilkhc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmcdxsop.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.guannengcc.top/Article/details/gtzenpdhcj.html

[Q15] 查询全部
来源：http://dali.jqgfzy.top/Article/details/gtnjmkiuum.html

SELECT * FROM users;
来源：http://dali.zycfv.cn/Article/details/gtozvtqbck.html

[Q16] 查询指定列
来源：http://dali.xziqi.cn/Article/details/gttlueaovx.html

SELECT id, name FROM users;
来源：http://dali.smart0.xyz/Article/details/gtwyemkies.html

[Q17] 条件查询
来源：http://dali.xinyue.icu/Article/details/gtvayypavg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gotoacloud.top/Article/details/gtyfkuhlgc.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gtuyskfoon.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yonumen.top/Article/details/gtrvxufccg.html

[Q19] 范围查询
来源：http://dali.feifeiyinyue.top/Article/details/gtkhoqxeei.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvsctqng.html

[Q20] IN 列表
来源：http://dali.vqdsnc.cn/Article/details/gtvxrsgvgt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gttjefgazr.html

[Q21] 空值判断
来源：http://dali.gogol.net.cn/Article/details/gtjzacdchf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj20258888.top/Article/details/gtnszhxwrw.html

[Q22] 排序
来源：http://dali.andypj.xyz/Article/details/gtgbktmfid.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.haohaochexian.top/Article/details/gtnzswgsqd.html

[Q23] 分页
来源：http://dali.jinqigfzy.top/Article/details/gtdocbmdgx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.daria6918.cn/Article/details/gtxwplmegm.html

[Q24] 去重
来源：http://dali.chenjidiqi.icu/Article/details/gtkqilbcbm.html

SELECT DISTINCT city FROM users;
来源：http://dali.iojbl.cn/Article/details/gtdejwjjkm.html

[Q25] 只取前 N 条
来源：http://dali.yangfankeji.com/Article/details/gtcpetjjkm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cucudq.cn/Article/details/gtaqsgacoc.html

[Q26] 计数
来源：http://dali.yonumen.top/Article/details/gtsbxclgqr.html

SELECT COUNT(*) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtiggoasls.html

[Q27] 条件计数
来源：http://dali.birdmap.top/Article/details/gtukjfukrd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtfddcihex.html

[Q28] 求和与平均
来源：http://dali.smart0.xyz/Article/details/gtzzxjqwdn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtxsgcqxdq.html

[Q29] 最大最小值
来源：http://dali.jiagoushi.top/Article/details/gtjhwhjfjr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtqbcyobdy.html

[Q30] 分组统计
来源：http://dali.guannengcc.top/Article/details/gtgbalpidp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gtjuiwqriw.html

[Q31] 分组后过滤
来源：http://dali.birdmap.top/Article/details/gtvvnaslay.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.dianchejie.cn/Article/details/gtgavmoxun.html

[Q32] 分组拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gtzcxztokt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtklapeoyi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.pengpengdd.cyou/Article/details/gtaxdbyosa.html

[Q33] 多列分组
来源：http://dali.yongpay.top/Article/details/gtpqzslovl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hnqzz.top/Article/details/gtkcjvcmri.html

[Q34] 每组取第一条
来源：http://dali.yonumen.top/Article/details/gtrmgsbkwk.html

SELECT * FROM (
来源：http://dali.yongpay.top/Article/details/gtqkgheqmd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.0kj1m.cn/Article/details/gtgmvjcugl.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtlglhudke.html

[Q35] 内连接
来源：http://dali.birdmap.top/Article/details/gtfjxoxqkh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenjidiqi.icu/Article/details/gtbteoyfyt.html

[Q36] 左连接
来源：http://dali.yangfankeji.com/Article/details/gtkijbhmca.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.birdmap.top/Article/details/gtlrkrqljg.html

[Q37] 右连接
来源：http://dali.hnxiangtu.top/Article/details/gtgrbsfyem.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.mhx1999.top/Article/details/gtmibgcyme.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.0kj1m.cn/Article/details/gtacpzwbro.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.havefunace.top/Article/details/gttfodmiyn.html

[Q39] 自连接（查上下级）
来源：http://dali.dashuyun.cn/Article/details/gthjmwmkoj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jyoumei.cn/Article/details/gthjijibfq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fengsongda.top/Article/details/gtlkqlxesr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hongshengwenyu.top/Article/details/gtotijwwvm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sysykeji.top/Article/details/gtyxyccetn.html

[Q41] 多表连接
来源：http://dali.mhx1999.top/Article/details/gtqkjuplhb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xuanzx.com/Article/details/gtzrtgmagq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.snrcjt.cn/Article/details/gtehkszcev.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shzxlz.cn/Article/details/gtwpfhaani.html

[Q42] 连接条件附加过滤
来源：http://dali.zhongyouzk.top/Article/details/gteryzwnfs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj20258.top/Article/details/gtidqwidwg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nanxuanxn.top/Article/details/gtnmmkqfxp.html

[Q43] 标量子查询
来源：http://dali.ivvv.top/Article/details/gtnxuzblre.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yonumen.top/Article/details/gtndyfrxsp.html

[Q44] IN 子查询
来源：http://dali.hfpthk.cn/Article/details/gtnhlywmsb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gzhubu.top/Article/details/gteisaogdn.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbepvpgti.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.birdmap.top/Article/details/gtqrjdfgdf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gaohongyu789.top/Article/details/gtxlyvcqjp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jlsjyb.cn/Article/details/gtahbbsqbq.html

[Q47] 与平均值比较
来源：http://dali.316326.xyz/Article/details/gtaytnauqh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.0kj1m.cn/Article/details/gtodimhxqj.html

[Q48] CTE 公用表表达式
来源：http://dali.xuanzx.com/Article/details/gtqhekamwz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhoulong.xyz/Article/details/gtzgjfajoa.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.kuanghao11.cn/Article/details/gtmbbrrrhg.html

[Q49] 更新单行
来源：http://dali.aizwys.cn/Article/details/gtqyonlaij.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gttpjxsysx.html

[Q50] 批量更新
来源：http://dali.yangfankeji.com/Article/details/gtfagmbqof.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sweek.top/Article/details/gtcjgfdeoj.html

[Q51] 用子查询更新
来源：http://dali.fengsongda.top/Article/details/gtdpbnteuv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenzaomai.com/Article/details/gtulbytjgg.html

[Q52] 删除指定行
来源：http://dali.gotoacloud.top/Article/details/gtvdyhtbxm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tian-w.cn/Article/details/gtcajjybaz.html

[Q53] 按条件删除
来源：http://dali.cashguo.top/Article/details/gtnbcwvwty.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hysaishi.cn/Article/details/gtdhfdxpyg.html

[Q54] 清空表
来源：http://dali.quarkkingdee.top/Article/details/gtpueapava.html

TRUNCATE TABLE logs;
来源：http://dali.chenlongwang.top/Article/details/gtctecyhhg.html

[Q55] 排名（并列占位）
来源：http://dali.daxiang520.top/Article/details/gtobofrnvb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhengqikj.top/Article/details/gtcahlhjpj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnqzz.top/Article/details/gtjkevojgy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.0kj1m.cn/Article/details/gtndhivzvw.html

[Q57] 行号
来源：http://dali.xuetiantiany.cn/Article/details/gtnitokkqs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtocubpqxn.html

[Q58] 累计求和
来源：http://dali.ppjwa.cn/Article/details/gtkvftultk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtaetdqjze.html

[Q59] 分组内累计
来源：http://dali.mhx1999.top/Article/details/gtvjgfbajn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtjihzbfmt.html

[Q60] 取上一行 / 下一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetxealxu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.birdmap.top/Article/details/gtverbycmv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtttzivqrg.html

[Q61] 移动平均
来源：http://dali.zhengqikj.top/Article/details/gtdshxrvfs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gttxwvzudl.html

[Q62] 分组占比
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgqhikqp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsbowfij.html

[Q63] 开启事务
来源：http://dali.jinqigfzy.top/Article/details/gtwyiwfdpu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hongshengwenyu.top/Article/details/gtprvlfupf.html

[Q64] 提交事务
来源：http://dali.jlsjyb.cn/Article/details/gtukilvjgm.html

COMMIT;
来源：http://dali.fzhhl.top/Article/details/gtwtbvjuqu.html

[Q65] 回滚事务
来源：http://dali.wangshuangyany.cn/Article/details/gtppnpkonm.html

ROLLBACK;
来源：http://dali.jqgfzy.top/Article/details/gtqxfofuhg.html

[Q66] 行锁查询
来源：http://dali.tianlin.xyz/Article/details/gtuezikcpb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj20258.top/Article/details/gtplsrgqoa.html

[Q67] 设置隔离级别
来源：http://dali.jinqigufen.top/Article/details/gtspchjqao.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tanke756.top/Article/details/gtryfvqojz.html

[Q68] 保存点
来源：http://dali.andypj.xyz/Article/details/gtfmplabxx.html

SAVEPOINT sp1;
来源：http://dali.shuidangran.top/Article/details/gttbeextin.html

ROLLBACK TO sp1;
来源：http://dali.xylfe.cn/Article/details/gtmnpbgeje.html

[Q69] 查看执行计划
来源：http://dali.snrcjt.cn/Article/details/gtlztnnvpy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fzhhl.top/Article/details/gtknjkzeiw.html

[Q70] 更新统计信息
来源：http://dali.gotoacloud.top/Article/details/gtakidczgv.html

ANALYZE TABLE users;
来源：http://dali.yanxiufei.cn/Article/details/gtaurazxsj.html

[Q71] 查看建表语句
来源：http://dali.9152youxi.cn/Article/details/gttptpqfdf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cdnleiting.top/Article/details/gtzmeypgxv.html

[Q72] 查看索引
来源：http://dali.9152youxi.cn/Article/details/gtlbrxiyam.html

SHOW INDEX FROM users;
来源：http://dali.bjfxy.top/Article/details/gtmjeptkpc.html

[Q73] 查看表状态
来源：http://dali.zhongyouzk.top/Article/details/gtzrwsjeku.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenjidiqi.icu/Article/details/gtdovwbixr.html

[Q74] 强制使用索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpzkjdzfm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.c1oappe.top/Article/details/gtlmmjmcsz.html

[Q75] 日期格式化
来源：http://dali.ppjwa.cn/Article/details/gtlwfikglq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.havefunace.top/Article/details/gtaksefntg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yvedp.cn/Article/details/gtdocpxfod.html

[Q76] 按天统计
来源：http://dali.pycfn.com/Article/details/gtmrmfrwed.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yangfankeji.com/Article/details/gtgdhfytbt.html

[Q77] 时间加减
来源：http://dali.jqgufenzy.top/Article/details/gtdxjllzvy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hnqzz.top/Article/details/gtjdhvbnph.html

[Q78] 当前时间
来源：http://dali.hnxiangtu.top/Article/details/gtxtcpdsea.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.smart0.xyz/Article/details/gtidghupsm.html

[Q79] 字符串拼接
来源：http://dali.gzhubu.top/Article/details/gtmvvizrkc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhengqikj.top/Article/details/gtxcjcjbzn.html

[Q80] 字符串截取
来源：http://dali.hammf.cn/Article/details/gtzysxbmxw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtnewnmnox.html

[Q81] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gtcqmvlgld.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtmbmpuzyn.html

[Q82] 字符长度与字节长度
来源：http://dali.hfpthk.cn/Article/details/gtikxoocqw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sweek.top/Article/details/gtyrbgcxxa.html

[Q83] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtigzewqwy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gttgspgniv.html

[Q84] 去除首尾空格
来源：http://dali.daria6918.cn/Article/details/gtbmhvcozi.html

SELECT TRIM(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtttkgnthr.html

[Q85] 数值取整
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxoymggox.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.vqdsnc.cn/Article/details/gtuufjyzch.html

[Q86] 读取 JSON 字段
来源：http://dali.pycfn.com/Article/details/gthpfczmdo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhengqikj.top/Article/details/gtbzblbbmm.html

[Q87] JSON 字段做条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjlckfvbf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxuanxn.top/Article/details/gtsrepqgsc.html

[Q88] 行转列（条件聚合）
来源：http://dali.yuanzhike.top/Article/details/gtiokgqyul.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gogol.net.cn/Article/details/gtxvlimdoc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tanke756.top/Article/details/gtrsgtbevq.html

[Q89] 判断表是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gtpxchtgoy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhixingplan.top/Article/details/gtnmkvihjk.html

[Q90] 生成序号列
来源：http://dali.haohaochexian.top/Article/details/gtqdrhuoso.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hysaishi.cn/Article/details/gtxmshebyy.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtjntxucmd.html

R. Bash 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxspzsipp.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtzioblrfy.html

[R01] shebang 与严格模式
来源：http://dali.guowangkeji.top/Article/details/gtrrnssiji.html

#!/usr/bin/env bash
来源：http://dali.vqdsnc.cn/Article/details/gttoxgrdga.html

set -euo pipefail
来源：http://dali.tianlin.xyz/Article/details/gtldjcqpcx.html

[R02] 变量赋值与使用
来源：http://dali.hammf.cn/Article/details/gtvwwwfwoh.html

name="Tom"; echo "$name"
来源：http://dali.xuanzx.com/Article/details/gthtporppb.html

[R03] 只读变量
来源：http://dali.hammf.cn/Article/details/gtpotfsvka.html

readonly PI=3.14
来源：http://dali.9152youxi.cn/Article/details/gtugikcvtz.html

[R04] 位置参数
来源：http://dali.bjfxy.top/Article/details/gtalxnpqaz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hysaishi.cn/Article/details/gtreaptnyd.html

[R05] 参数默认值
来源：http://dali.xinyue.icu/Article/details/gtbfptyffk.html

name="${1:-default}"
来源：http://dali.daxiang520.top/Article/details/gtchprzvho.html

[R06] 判断命令是否存在
来源：http://dali.aibaodan.cn/Article/details/gtlmkaqujp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cucudq.cn/Article/details/gtstlbwwju.html

[R07] if 判断文件
来源：http://dali.fzhhl.top/Article/details/gtrtmlguni.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.0kj1m.cn/Article/details/gtqgdlmvqc.html

[R08] 数值比较
来源：http://dali.yj202588.top/Article/details/gttjpymoqu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhixingplan.top/Article/details/gtcfmnhlso.html

[R09] 字符串比较
来源：http://dali.yj20258888.top/Article/details/gtfigpumau.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hywenlv.cn/Article/details/gtxxqxnccy.html

[R10] 正则匹配
来源：http://dali.0kj1m.cn/Article/details/gtbllcytji.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtwnouwicd.html

[R11] case 多分支
来源：http://dali.pycfn.com/Article/details/gtohoohlff.html

case "$1" in
来源：http://dali.andypj.xyz/Article/details/gtcupkdinl.html

start) echo "启动" ;;
来源：http://dali.hysaishi.cn/Article/details/gtowiwbtsy.html

stop)  echo "停止" ;;
来源：http://dali.quarkkingdee.top/Article/details/gtvufolhii.html

*)     echo "未知命令" ;;
来源：http://dali.316326.xyz/Article/details/gterzhtdtc.html

esac
来源：http://dali.pycfn.com/Article/details/gtyaweaowo.html

[R12] for 遍历文件
来源：http://dali.nwbrower.top/Article/details/gtknoyakkj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yanxiufei.cn/Article/details/gtbwcbarir.html

[R13] for 计数循环
来源：http://dali.yanxiufei.cn/Article/details/gterqmxniq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtaqunhmmb.html

[R14] C 风格 for
来源：http://dali.zhixingplan.top/Article/details/gthhpimlpj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gtnwudinmz.html

[R15] while 逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtudnxrizy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.quarkkingdee.top/Article/details/gtpkhtgjsx.html

[R16] until 等待条件
来源：http://dali.nwbrower.top/Article/details/gteqtbkgmb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gotoacloud.top/Article/details/gtfcroqjkw.html

[R17] 数组定义与取值
来源：http://dali.guannengcc.top/Article/details/gtzgtyvozu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sufxvd.cn/Article/details/gtebzyqcni.html

[R18] 遍历数组
来源：http://dali.fzhhl.top/Article/details/gteynhkvha.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtooypnrat.html

[R19] 数组长度
来源：http://dali.cucudq.cn/Article/details/gtdpjkfdks.html

echo "${#arr[@]}"
来源：http://dali.ehwqpu.com/Article/details/gtxgebydvg.html

[R20] 关联数组（字典）
来源：http://dali.vqdsnc.cn/Article/details/gtustziibm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.fzhhl.top/Article/details/gtafuxeddz.html

[R21] 字符串长度
来源：http://dali.c1oappe.top/Article/details/gtssyuqjde.html

echo "${#s}"
来源：http://dali.sysykeji.top/Article/details/gthdcstsdk.html

[R22] 截取子串
来源：http://dali.ydzc1.top/Article/details/gtqiouxldh.html

echo "${s:0:5}"
来源：http://dali.yongpay.top/Article/details/gtmziufubh.html

[R23] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gtcmfkfpvt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.c1oappe.top/Article/details/gtvdgdinno.html

[R24] 大小写转换
来源：http://dali.pengpengdd.cyou/Article/details/gtklgpaywj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guowangkeji.top/Article/details/gtqakryuwg.html

[R25] 去后缀 / 去前缀
来源：http://dali.xinyue.icu/Article/details/gtjaaqepxn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.snrcjt.cn/Article/details/gtwyxuxuou.html

[R26] 命令替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtagwtgamu.html

now=$(date +%F); echo "$now"
来源：http://dali.jyoumei.cn/Article/details/gthtwtapbw.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gttuqqwweo.html

echo $((1 + 2 * 3))
来源：http://dali.sysykeji.top/Article/details/gtiixzwzkz.html

[R28] 浮点运算
来源：http://dali.yuxming.cn/Article/details/gtcrtrjafi.html

echo "scale=2; 10/3" | bc
来源：http://dali.yueranfly.top/Article/details/gtflyjujvl.html

[R29] 定义函数
来源：http://dali.nanxinkj.top/Article/details/gthlkocbab.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnqzz.top/Article/details/gtcwklclae.html

[R30] 函数返回状态码
来源：http://dali.wangdashe.top/Article/details/gtwynwovty.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jianghu66.top/Article/details/gtewxkmbyq.html

[R31] 局部变量
来源：http://dali.ppjwa.cn/Article/details/gtfioqtcnu.html

f() { local x=1; echo "$x"; }
来源：http://dali.sysykeji.top/Article/details/gtkzptaxop.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gtcbhmwlmk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fzhhl.top/Article/details/gtagxyloel.html

[R33] 捕获错误并提示行号
来源：http://dali.c1oappe.top/Article/details/gthjcukvmv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hammf.cn/Article/details/gtdpsgelna.html

[R34] 退出时清理
来源：http://dali.zhixingplan.top/Article/details/gtwqrlgzkg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gtnimmaptg.html

[R35] 后台执行并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrxkjxqk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.svipenyu.cn/Article/details/gtsssjrnsn.html

[R36] 并发执行多个任务
来源：http://dali.aizwys.cn/Article/details/gtgfewtjss.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.dianchejie.cn/Article/details/gttpphqena.html

[R37] 把输出赋给变量
来源：http://dali.0kj1m.cn/Article/details/gtzfbznppl.html

files=$(ls -1)
来源：http://dali.yvedp.cn/Article/details/gtvruskmao.html

[R38] 管道串联
来源：http://dali.zdqjudy.top/Article/details/gtbknvjfbi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnxiangtu.top/Article/details/gttorqpihq.html

[R39] 重定向标准输出与错误
来源：http://dali.yueranfly.top/Article/details/gthmebewxb.html

cmd > out.log 2>&1
来源：http://dali.shuidangran.top/Article/details/gtrcawijmn.html

[R40] 追加写日志
来源：http://dali.jqgufenzy.top/Article/details/gtqxhtyncl.html

echo "log" >> out.log
来源：http://dali.haohaochexian.top/Article/details/gtoesdriac.html

[R41] 丢弃输出
来源：http://dali.smart0.xyz/Article/details/gtdcnmkagm.html

cmd >/dev/null 2>&1
来源：http://dali.sufxvd.cn/Article/details/gtaflljmwx.html

[R42] 输入重定向
来源：http://dali.kuanghao11.cn/Article/details/gtevrjqyxh.html

wc -l < a.txt
来源：http://dali.c1oappe.top/Article/details/gthuikbjhs.html

[R43] 按名字查找文件
来源：http://dali.gzhubu.top/Article/details/gtpetbdwni.html

find . -name "*.log" -type f
来源：http://dali.zhixingplan.top/Article/details/gtsvbhnvot.html

[R44] 按修改时间查找
来源：http://dali.svipenyu.cn/Article/details/gtiskutbay.html

find . -mtime -7 -type f
来源：http://dali.ppjwa.cn/Article/details/gtnnddosxv.html

[R45] 批量删除
来源：http://dali.hnqzz.top/Article/details/gteqaujczp.html

find . -name "*.tmp" -delete
来源：http://dali.xuetiantiany.cn/Article/details/gtxxlllefi.html

[R46] 递归替换文件内容
来源：http://dali.yvedp.cn/Article/details/gtuodrtchi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinqigufen.top/Article/details/gtsaqukbdo.html

[R47] sed 单行替换
来源：http://dali.bjfxy.top/Article/details/gtflctqqyw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sufxvd.cn/Article/details/gttxhqyxjq.html

[R48] awk 取指定列
来源：http://dali.jqgfzy.top/Article/details/gthwuqzlvb.html

awk '{print $1, $3}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtyfzekykg.html

[R49] awk 带条件
来源：http://dali.zhongyouzk.top/Article/details/gtrsrzgdtz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daria6918.cn/Article/details/gtilcqwqnu.html

[R50] awk 求和
来源：http://dali.guowangkeji.top/Article/details/gtixsrluhb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hysaishi.cn/Article/details/gtfdvnukpc.html

[R51] 排序去重取前几
来源：http://dali.xziqi.cn/Article/details/gtaxkiwddn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dashuyun.cn/Article/details/gteywpbeer.html

[R52] 统计行数
来源：http://dali.havefunace.top/Article/details/gtnamjorsk.html

wc -l a.txt
来源：http://dali.svipenyu.cn/Article/details/gtpevhowae.html

[R53] 查看文件头与实时尾
来源：http://dali.chenzaomai.com/Article/details/gteshyjybu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshwbtrec.html

[R54] 比较两个文件
来源：http://dali.hywenlv.cn/Article/details/gtxglvesxq.html

diff a.txt b.txt
来源：http://dali.yongpay.top/Article/details/gtpzureene.html

[R55] 压缩与解压
来源：http://dali.hnxiangtu.top/Article/details/gtbtcovfhn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hysaishi.cn/Article/details/gtdhcgqfcu.html

[R56] 远程拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtadachwms.html

scp file user@host:/path/
来源：http://dali.xylfe.cn/Article/details/gtbjylvwed.html

[R57] 远程执行命令
来源：http://dali.pycfn.com/Article/details/gtkrgzweyk.html


<!-- 参考信息 -->