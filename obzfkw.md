代发 wailian999

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.pycfn.com/Article/details/gtcidnrxli.html

[Q11] 一次插入多行
来源：http://dali.c1oappe.top/Article/details/gtiibqssoe.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gtgiprwmuj.html

[Q12] 插入后取自增 ID
来源：http://dali.316326.xyz/Article/details/gtrqqqkebf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aibaodan.cn/Article/details/gtqtsqgvnw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.snrcjt.cn/Article/details/gtjijvvekt.html

[Q13] 忽略重复插入
来源：http://dali.hywenlv.cn/Article/details/gtxzxcltpy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ybcxt.top/Article/details/gtarthdbfu.html

[Q14] 存在则更新（upsert）
来源：http://dali.guannengcc.top/Article/details/gteurqtdqa.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guowangkeji.top/Article/details/gtihgninhk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhixingplan.top/Article/details/gtckwakztt.html

[Q15] 查询全部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqiohtao.html

SELECT * FROM users;
来源：http://dali.nwbrower.top/Article/details/gtwnvsgwdt.html

[Q16] 查询指定列
来源：http://dali.ivvv.top/Article/details/gtphknjuip.html

SELECT id, name FROM users;
来源：http://dali.iojbl.cn/Article/details/gtievjubkt.html

[Q17] 条件查询
来源：http://dali.fzhhl.top/Article/details/gtrnaqilpr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.dianchejie.cn/Article/details/gtghndocuu.html

[Q18] 模糊匹配
来源：http://dali.hfpthk.cn/Article/details/gtzrzpgkqy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.daxiang520.top/Article/details/gtwqsazvfw.html

[Q19] 范围查询
来源：http://dali.xziqi.cn/Article/details/gtodyazvcg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj202588.top/Article/details/gtszuqnzsn.html

[Q20] IN 列表
来源：http://dali.gogol.net.cn/Article/details/gtkrxslbdv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.snrcjt.cn/Article/details/gtmwnjrjvd.html

[Q21] 空值判断
来源：http://dali.cheryme.top/Article/details/gtbqtssefz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ybcxt.top/Article/details/gtrpttmsok.html

[Q22] 排序
来源：http://dali.sufxvd.cn/Article/details/gtgpmrzfou.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.snrcjt.cn/Article/details/gtygixbdtw.html

[Q23] 分页
来源：http://dali.jiagoushi.top/Article/details/gtpfujcwun.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj20258.top/Article/details/gtwnhdrykn.html

[Q24] 去重
来源：http://dali.yuxming.cn/Article/details/gtpdqziqwd.html

SELECT DISTINCT city FROM users;
来源：http://dali.xylfe.cn/Article/details/gtkfvuttzy.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwkmvyyn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hysaishi.cn/Article/details/gtrdwlsyau.html

[Q26] 计数
来源：http://dali.fzhhl.top/Article/details/gtuipiwkop.html

SELECT COUNT(*) FROM users;
来源：http://dali.fzhhl.top/Article/details/gthqmcjqft.html

[Q27] 条件计数
来源：http://dali.iojbl.cn/Article/details/gtboqdutsj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yongpay.top/Article/details/gtykjvicxb.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqxtuoue.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdzrlapst.html

[Q29] 最大最小值
来源：http://dali.pengpengdd.cyou/Article/details/gtjceiesqg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtgmhjfjxa.html

[Q30] 分组统计
来源：http://dali.zhongyouzk.top/Article/details/gttubowphh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gtizplfsvz.html

[Q31] 分组后过滤
来源：http://dali.cashguo.top/Article/details/gtkuoazkbi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.kuanghao11.cn/Article/details/gtcxoljjwn.html

[Q32] 分组拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtlebbatlj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.316326.xyz/Article/details/gtaemaqepb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.daria6918.cn/Article/details/gtlvvkcwxg.html

[Q33] 多列分组
来源：http://dali.shuidangran.top/Article/details/gtmbyomanb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xinyue.icu/Article/details/gtnwkbunjv.html

[Q34] 每组取第一条
来源：http://dali.gaohongyu789.top/Article/details/gtzmvcjfbh.html

SELECT * FROM (
来源：http://dali.chenlongwang.top/Article/details/gtbogunaww.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gaohongyu789.top/Article/details/gtoynzaonh.html

) t WHERE rn = 1;
来源：http://dali.jiagoushi.top/Article/details/gtsombjxfu.html

[Q35] 内连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxnfavqu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gteqzexnwn.html

[Q36] 左连接
来源：http://dali.hongshengwenyu.top/Article/details/gtdlrlxmqo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aibaodan.cn/Article/details/gtxglwmkmq.html

[Q37] 右连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtkmhisont.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yanxiufei.cn/Article/details/gtcdmeuhid.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwhyksjm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nanxinkj.top/Article/details/gtdpixvqps.html

[Q39] 自连接（查上下级）
来源：http://dali.fzhhl.top/Article/details/gtqfmbhxpq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hammf.cn/Article/details/gtauqkijsz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.wangshuangyany.cn/Article/details/gtkkrxnczx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gogol.net.cn/Article/details/gtwmcxckip.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xylfe.cn/Article/details/gtlrnqvubw.html

[Q41] 多表连接
来源：http://dali.jinqigufen.top/Article/details/gtzxmoqfdz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ehwqpu.com/Article/details/gtulirvuri.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shangyingyoupin.top/Article/details/gtewjlhjjq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hysaishi.cn/Article/details/gtnxwzyici.html

[Q42] 连接条件附加过滤
来源：http://dali.fengsongda.top/Article/details/gtvaswyrje.html

SELECT u.name, o.amount FROM users u
来源：http://dali.wangdashe.top/Article/details/gtwoyukpjb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.wangdashe.top/Article/details/gtrpnmnwnz.html

[Q43] 标量子查询
来源：http://dali.pycfn.com/Article/details/gtgfzxipmk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.tanke756.top/Article/details/gtekpzjqca.html

[Q44] IN 子查询
来源：http://dali.sweek.top/Article/details/gtrsqeoruc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.316326.xyz/Article/details/gtvblbapll.html

[Q45] EXISTS 判断存在
来源：http://dali.yuxming.cn/Article/details/gtqmxhcxnr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gtmqvhjmoe.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinqigfzy.top/Article/details/gtyjpswfjk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hammf.cn/Article/details/gtyhqjyfpz.html

[Q47] 与平均值比较
来源：http://dali.c1oappe.top/Article/details/gtchpmorvb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnqzz.top/Article/details/gtpdjicsdh.html

[Q48] CTE 公用表表达式
来源：http://dali.daxiang520.top/Article/details/gtdeaxoenh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.snrcjt.cn/Article/details/gtcwrlnmxw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cashguo.top/Article/details/gtclzopjfr.html

[Q49] 更新单行
来源：http://dali.xinyue.icu/Article/details/gtsmbmwfbq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.dashuyun.cn/Article/details/gtkrguhggg.html

[Q50] 批量更新
来源：http://dali.pycfn.com/Article/details/gtduuldmpr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yueranfly.top/Article/details/gtuionlmfz.html

[Q51] 用子查询更新
来源：http://dali.tianlin.xyz/Article/details/gttvgngyse.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tanke756.top/Article/details/gtobpeodyc.html

[Q52] 删除指定行
来源：http://dali.haohaochexian.top/Article/details/gtcswuernu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yanxiufei.cn/Article/details/gtbwaxekyp.html

[Q53] 按条件删除
来源：http://dali.xylfe.cn/Article/details/gtllpcrkwh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cheryme.top/Article/details/gtsttbfsfu.html

[Q54] 清空表
来源：http://dali.kuanghao11.cn/Article/details/gttsntcafw.html

TRUNCATE TABLE logs;
来源：http://dali.yuanzhike.top/Article/details/gtljtgphlh.html

[Q55] 排名（并列占位）
来源：http://dali.sweek.top/Article/details/gtpmnsusxq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xziqi.cn/Article/details/gtujvnetkm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.9152youxi.cn/Article/details/gtmuxjmslc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtarjenvwf.html

[Q57] 行号
来源：http://dali.hywenlv.cn/Article/details/gtmglnxaaz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtzpitrpjm.html

[Q58] 累计求和
来源：http://dali.andypj.xyz/Article/details/gtaxvndrji.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtiticdsyq.html

[Q59] 分组内累计
来源：http://dali.gaohongyu789.top/Article/details/gtqfafowfn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtjvpsusab.html

[Q60] 取上一行 / 下一行
来源：http://dali.daria6918.cn/Article/details/gtxtwiouma.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ydzc1.top/Article/details/gtyzsiuoth.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtddvepxpn.html

[Q61] 移动平均
来源：http://dali.zhixingplan.top/Article/details/gtvsmjbcfb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pycfn.com/Article/details/gttgopxnoy.html

[Q62] 分组占比
来源：http://dali.hywenlv.cn/Article/details/gtyhfpnaep.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gtgbjwwykt.html

[Q63] 开启事务
来源：http://dali.smart0.xyz/Article/details/gtiecmgjcz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnqzz.top/Article/details/gtahywsbcf.html

[Q64] 提交事务
来源：http://dali.ydzc1.top/Article/details/gtrqvcmfzp.html

COMMIT;
来源：http://dali.pycfn.com/Article/details/gtejixtbhg.html

[Q65] 回滚事务
来源：http://dali.pycfn.com/Article/details/gtviwuegts.html

ROLLBACK;
来源：http://dali.quarkkingdee.top/Article/details/gtclavqrij.html

[Q66] 行锁查询
来源：http://dali.tian-w.cn/Article/details/gtrjpvuvpl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.haohaochexian.top/Article/details/gtgjlkfoov.html

[Q67] 设置隔离级别
来源：http://dali.c1oappe.top/Article/details/gtlybhrjkm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hongshengwenyu.top/Article/details/gtueyckmgt.html

[Q68] 保存点
来源：http://dali.fengsongda.top/Article/details/gteowqpfss.html

SAVEPOINT sp1;
来源：http://dali.xinyue.icu/Article/details/gtkjgxdqwh.html

ROLLBACK TO sp1;
来源：http://dali.hywenlv.cn/Article/details/gtpdqbueff.html

[Q69] 查看执行计划
来源：http://dali.daria6918.cn/Article/details/gtiouxwttd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hywenlv.cn/Article/details/gtrtsafedf.html

[Q70] 更新统计信息
来源：http://dali.havefunace.top/Article/details/gtmzjplovx.html

ANALYZE TABLE users;
来源：http://dali.chenzaomai.com/Article/details/gtwtlvamgf.html

[Q71] 查看建表语句
来源：http://dali.jqgufenzy.top/Article/details/gtznjtrtwh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhiwuduotai.top/Article/details/gtunmlunan.html

[Q72] 查看索引
来源：http://dali.yuxming.cn/Article/details/gtabxsfjqu.html

SHOW INDEX FROM users;
来源：http://dali.hnqzz.top/Article/details/gtwwdkftng.html

[Q73] 查看表状态
来源：http://dali.sysykeji.top/Article/details/gtajtzbcfo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ydzc1.top/Article/details/gtntlsbgva.html

[Q74] 强制使用索引
来源：http://dali.cashguo.top/Article/details/gtgebfbwdb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.birdmap.top/Article/details/gtzqqbbmhy.html

[Q75] 日期格式化
来源：http://dali.yuanzhike.top/Article/details/gtbbrbgzcq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtfffvnxhv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhengqikj.top/Article/details/gtwloymwoc.html

[Q76] 按天统计
来源：http://dali.ppjwa.cn/Article/details/gtcescapsp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.birdmap.top/Article/details/gtluaqoanr.html

[Q77] 时间加减
来源：http://dali.zhengqikj.top/Article/details/gtlsojdjmn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuanzhike.top/Article/details/gtkdzechim.html

[Q78] 当前时间
来源：http://dali.jinqigufen.top/Article/details/gtlyxcbzod.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tanke756.top/Article/details/gtocxonrya.html

[Q79] 字符串拼接
来源：http://dali.dashuyun.cn/Article/details/gtpmukhrku.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cheryme.top/Article/details/gtwncjquwt.html

[Q80] 字符串截取
来源：http://dali.zhixingplan.top/Article/details/gtldzrvzef.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtkcfvxspa.html

[Q81] 字符串替换
来源：http://dali.sweek.top/Article/details/gtucgjqtht.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zycfv.cn/Article/details/gtsmczincl.html

[Q82] 字符长度与字节长度
来源：http://dali.cheryme.top/Article/details/gtjanwrzvm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtefgsfvpw.html

[Q83] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gthilrkhix.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtfslncwom.html

[Q84] 去除首尾空格
来源：http://dali.yangfankeji.com/Article/details/gtnyngqqle.html

SELECT TRIM(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gtsngmovmw.html

[Q85] 数值取整
来源：http://dali.birdmap.top/Article/details/gtjnadnysz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj20258888.top/Article/details/gtmrvibxab.html

[Q86] 读取 JSON 字段
来源：http://dali.xylfe.cn/Article/details/gthbuptglq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yangfankeji.com/Article/details/gteyogzbqn.html

[Q87] JSON 字段做条件
来源：http://dali.zycfv.cn/Article/details/gtqjfkwdhv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinghuilouyu.cn/Article/details/gtytfxdyqc.html

[Q88] 行转列（条件聚合）
来源：http://dali.guowangkeji.top/Article/details/gtixjdwedy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnqzz.top/Article/details/gtzgwjrwoz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtcuiaesxd.html

[Q89] 判断表是否存在
来源：http://dali.yvedp.cn/Article/details/gtjhmudzqd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvpguggrg.html

[Q90] 生成序号列
来源：http://dali.havefunace.top/Article/details/gtggmbjkkw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shzxlz.cn/Article/details/gtbzfckfbu.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguqifrmv.html

R. Bash 专题
来源：http://dali.yj202588.top/Article/details/gthfjwtkcc.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtttjvmbyd.html

[R01] shebang 与严格模式
来源：http://dali.ppjwa.cn/Article/details/gtendfskuw.html

#!/usr/bin/env bash
来源：http://dali.jinyuanbaomall.cn/Article/details/gtypphostp.html

set -euo pipefail
来源：http://dali.haohaochexian.top/Article/details/gtjvzwmsyy.html

[R02] 变量赋值与使用
来源：http://dali.cdnleiting.top/Article/details/gtfhvwypxa.html

name="Tom"; echo "$name"
来源：http://dali.gzhubu.top/Article/details/gtlkmcmuqb.html

[R03] 只读变量
来源：http://dali.gogol.net.cn/Article/details/gtpvlpvgtv.html

readonly PI=3.14
来源：http://dali.meibo888.top/Article/details/gtstpakrxm.html

[R04] 位置参数
来源：http://dali.bjfxy.top/Article/details/gteafndxxt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.daxiang520.top/Article/details/gtkqawyiad.html

[R05] 参数默认值
来源：http://dali.jinqigufen.top/Article/details/gtqhidutkn.html

name="${1:-default}"
来源：http://dali.nanxinkj.top/Article/details/gtvwrbbmts.html

[R06] 判断命令是否存在
来源：http://dali.ivvv.top/Article/details/gtoypjmwns.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gteteqtxjz.html

[R07] if 判断文件
来源：http://dali.jlsjyb.cn/Article/details/gtjxvpkemw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.redwolf501.top/Article/details/gtmoletppe.html

[R08] 数值比较
来源：http://dali.yvedp.cn/Article/details/gtvupqkwnt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.aizwys.cn/Article/details/gtbqaknoga.html

[R09] 字符串比较
来源：http://dali.zhongyouzk.top/Article/details/gtkqpnfohv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj202588.top/Article/details/gtbovuhxup.html

[R10] 正则匹配
来源：http://dali.snrcjt.cn/Article/details/gtnlhdsvpi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gotoacloud.top/Article/details/gtaasiqusn.html

[R11] case 多分支
来源：http://dali.redwolf501.top/Article/details/gtwgkptyig.html

case "$1" in
来源：http://dali.yj202588.top/Article/details/gtpbeeypea.html

start) echo "启动" ;;
来源：http://dali.gaohongyu789.top/Article/details/gteoveipkl.html

stop)  echo "停止" ;;
来源：http://dali.xuanzx.com/Article/details/gtllagceyn.html

*)     echo "未知命令" ;;
来源：http://dali.zhongyouzk.top/Article/details/gtgofbclwx.html

esac
来源：http://dali.hfpthk.cn/Article/details/gtvsqlhhqf.html

[R12] for 遍历文件
来源：http://dali.smart0.xyz/Article/details/gtbmporzob.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyidqiqeb.html

[R13] for 计数循环
来源：http://dali.yuxming.cn/Article/details/gtyajoijvi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.316326.xyz/Article/details/gtsfxooflo.html

[R14] C 风格 for
来源：http://dali.hammf.cn/Article/details/gtawgbzymy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gtutflvbur.html

[R15] while 逐行读文件
来源：http://dali.yonumen.top/Article/details/gtaimkdmyc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yanxiufei.cn/Article/details/gtuojveghr.html

[R16] until 等待条件
来源：http://dali.svipenyu.cn/Article/details/gtfdosckcw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gtcbdkrtms.html

[R17] 数组定义与取值
来源：http://dali.yuxming.cn/Article/details/gturuuzqlh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fengsongda.top/Article/details/gtpwyslnkk.html

[R18] 遍历数组
来源：http://dali.andypj.xyz/Article/details/gtvegfgagt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aibaodan.cn/Article/details/gtdrygnwep.html

[R19] 数组长度
来源：http://dali.shuidangran.top/Article/details/gtirazvfbz.html

echo "${#arr[@]}"
来源：http://dali.zycfv.cn/Article/details/gtmvyhzqnw.html

[R20] 关联数组（字典）
来源：http://dali.svipenyu.cn/Article/details/gtlwkyazdf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.svipenyu.cn/Article/details/gtdxxagrzu.html

[R21] 字符串长度
来源：http://dali.chenlongwang.top/Article/details/gtgmrlswcr.html

echo "${#s}"
来源：http://dali.smart0.xyz/Article/details/gtgzlgpejc.html

[R22] 截取子串
来源：http://dali.tanke756.top/Article/details/gtfylzyzrj.html

echo "${s:0:5}"
来源：http://dali.andypj.xyz/Article/details/gtwdddnbdh.html

[R23] 字符串替换
来源：http://dali.jyoumei.cn/Article/details/gtkkfndqpa.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivgddsht.html

[R24] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gtfafstwxr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxuanxn.top/Article/details/gtnfdbqzxe.html

[R25] 去后缀 / 去前缀
来源：http://dali.havefunace.top/Article/details/gtmqqfdpum.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.redwolf501.top/Article/details/gtglloendc.html

[R26] 命令替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlknwzfcs.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgufenzy.top/Article/details/gtnthsinnc.html

[R27] 算术展开
来源：http://dali.zdqjudy.top/Article/details/gtleedmljz.html

echo $((1 + 2 * 3))
来源：http://dali.sufxvd.cn/Article/details/gtwywtkkhl.html

[R28] 浮点运算
来源：http://dali.sweek.top/Article/details/gtevwscbue.html

echo "scale=2; 10/3" | bc
来源：http://dali.gogol.net.cn/Article/details/gtzgopnzdx.html

[R29] 定义函数
来源：http://dali.mhx1999.top/Article/details/gtdloohswl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnqzz.top/Article/details/gtfycdmbyq.html

[R30] 函数返回状态码
来源：http://dali.gzhubu.top/Article/details/gtrbkzkpdd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xuetiantiany.cn/Article/details/gtawiposhn.html

[R31] 局部变量
来源：http://dali.iojbl.cn/Article/details/gtsbboeudr.html

f() { local x=1; echo "$x"; }
来源：http://dali.birdmap.top/Article/details/gtiutcvsiq.html

[R32] 参数个数校验
来源：http://dali.shuidangran.top/Article/details/gtrqabquir.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gtgftdpddf.html

[R33] 捕获错误并提示行号
来源：http://dali.zycfv.cn/Article/details/gtjwijyfqi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.wangdashe.top/Article/details/gtkzoytjiv.html

[R34] 退出时清理
来源：http://dali.daria6918.cn/Article/details/gtehcqnuqh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xinyue.icu/Article/details/gtgdxyqdis.html

[R35] 后台执行并等待
来源：http://dali.ydzc1.top/Article/details/gtpzxlhiuk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmczinrh.html

[R36] 并发执行多个任务
来源：http://dali.tian-w.cn/Article/details/gtlkbftblx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj20258888.top/Article/details/gtdisjlcvt.html

[R37] 把输出赋给变量
来源：http://dali.xuanzx.com/Article/details/gtttbbwnkh.html

files=$(ls -1)
来源：http://dali.smart0.xyz/Article/details/gttqvkijfr.html

[R38] 管道串联
来源：http://dali.yanxiufei.cn/Article/details/gtmrxevwnk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gzhubu.top/Article/details/gtffqlqjnq.html

[R39] 重定向标准输出与错误
来源：http://dali.wangshuangyany.cn/Article/details/gtvhahacrn.html

cmd > out.log 2>&1
来源：http://dali.meibo888.top/Article/details/gtudwrryhc.html

[R40] 追加写日志
来源：http://dali.gaohongyu789.top/Article/details/gtmgmipxwn.html

echo "log" >> out.log
来源：http://dali.gotoacloud.top/Article/details/gtvgkwdhxt.html

[R41] 丢弃输出
来源：http://dali.zhiwuduotai.top/Article/details/gttrdyzyli.html

cmd >/dev/null 2>&1
来源：http://dali.cheryme.top/Article/details/gtjwiiourv.html

[R42] 输入重定向
来源：http://dali.xylfe.cn/Article/details/gtwfgruikd.html

wc -l < a.txt
来源：http://dali.cucudq.cn/Article/details/gtwfrqyqvg.html

[R43] 按名字查找文件
来源：http://dali.yanxiufei.cn/Article/details/gtndoapykg.html

find . -name "*.log" -type f
来源：http://dali.zhoulong.xyz/Article/details/gtptgoxube.html

[R44] 按修改时间查找
来源：http://dali.fengsongda.top/Article/details/gtizgpddnl.html

find . -mtime -7 -type f
来源：http://dali.jianghu66.top/Article/details/gtshptptpm.html

[R45] 批量删除
来源：http://dali.nanxuanxn.top/Article/details/gtchavcejz.html

find . -name "*.tmp" -delete
来源：http://dali.zhongyouzk.top/Article/details/gtdjpbmglr.html

[R46] 递归替换文件内容
来源：http://dali.yj20258.top/Article/details/gtxfgcbocz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gogol.net.cn/Article/details/gtwshhsall.html

[R47] sed 单行替换
来源：http://dali.bjfxy.top/Article/details/gtjbqdogep.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cucudq.cn/Article/details/gtjuwodvah.html

[R48] awk 取指定列
来源：http://dali.nwbrower.top/Article/details/gtqpcohfif.html

awk '{print $1, $3}' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtwufzpysb.html

[R49] awk 带条件
来源：http://dali.zycfv.cn/Article/details/gtuwvtdfjc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.c1oappe.top/Article/details/gtnloanhsh.html

[R50] awk 求和
来源：http://dali.hywenlv.cn/Article/details/gtujhvcksd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.dianchejie.cn/Article/details/gthecfpcwe.html

[R51] 排序去重取前几
来源：http://dali.cheryme.top/Article/details/gtxnifscab.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yueranfly.top/Article/details/gtfrsexgcd.html

[R52] 统计行数
来源：http://dali.xylfe.cn/Article/details/gtiamwmeig.html

wc -l a.txt
来源：http://dali.daria6918.cn/Article/details/gtozrlmpmy.html

[R53] 查看文件头与实时尾
来源：http://dali.xuanzx.com/Article/details/gtnctxphao.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sysykeji.top/Article/details/gtrcjgitmk.html

[R54] 比较两个文件
来源：http://dali.zhengqikj.top/Article/details/gtgsyyvadr.html

diff a.txt b.txt
来源：http://dali.gaohongyu789.top/Article/details/gtmgwvogwb.html

[R55] 压缩与解压
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgerygmr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.wangdashe.top/Article/details/gtxaqthfve.html

[R56] 远程拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtjptqwwzb.html

scp file user@host:/path/
来源：http://dali.hywenlv.cn/Article/details/gttedrchnv.html

[R57] 远程执行命令
来源：http://dali.wangshuangyany.cn/Article/details/gtdcthtmwa.html

ssh user@host 'uptime'
来源：http://dali.hfpthk.cn/Article/details/gtroyxzila.html

[R58] 下载文件
来源：http://dali.hnqzz.top/Article/details/gtpkwvuqon.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ydzc1.top/Article/details/gtmezdaqzn.html

[R59] 发 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gtzyojpvvt.html


<!-- 参考信息 -->