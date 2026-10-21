代发 wailian999

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hysaishi.cn/Article/details/gtbagqsdsq.html

[Q11] 一次插入多行
来源：http://dali.yuxming.cn/Article/details/gtqdgaadef.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtyqzzgart.html

[Q12] 插入后取自增 ID
来源：http://dali.zhongyouzk.top/Article/details/gtjxakumyb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ybcxt.top/Article/details/gtwduqgjxu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jqgfzy.top/Article/details/gtnhjowxpa.html

[Q13] 忽略重复插入
来源：http://dali.redwolf501.top/Article/details/gtybdoklhb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jqgfzy.top/Article/details/gtaishuuxs.html

[Q14] 存在则更新（upsert）
来源：http://dali.tian-w.cn/Article/details/gtfmnhjegy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenlongwang.top/Article/details/gtnsscsfxk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ppjwa.cn/Article/details/gtlvdyawvo.html

[Q15] 查询全部
来源：http://dali.zhengqikj.top/Article/details/gtddjfcwgo.html

SELECT * FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtituvsjnk.html

[Q16] 查询指定列
来源：http://dali.cdnleiting.top/Article/details/gtfptmcgup.html

SELECT id, name FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtrnzvuydt.html

[Q17] 条件查询
来源：http://dali.yj20258888.top/Article/details/gtthkkawpv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yonumen.top/Article/details/gtnlitoxmq.html

[Q18] 模糊匹配
来源：http://dali.mhx1999.top/Article/details/gthzvglwja.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.guowangkeji.top/Article/details/gtsigdpxbv.html

[Q19] 范围查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnppudop.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hywenlv.cn/Article/details/gtmeunjuqb.html

[Q20] IN 列表
来源：http://dali.c1oappe.top/Article/details/gtnxhmsfjw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hywenlv.cn/Article/details/gtqtuyjxte.html

[Q21] 空值判断
来源：http://dali.shangyingyoupin.top/Article/details/gtncbwkpoe.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.smart0.xyz/Article/details/gtevhllcvj.html

[Q22] 排序
来源：http://dali.nanxuanxn.top/Article/details/gtzdqorftc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.guannengcc.top/Article/details/gtlsjgqikx.html

[Q23] 分页
来源：http://dali.c1oappe.top/Article/details/gtqqhjlqir.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hnxiangtu.top/Article/details/gtpzlxvzve.html

[Q24] 去重
来源：http://dali.wangdashe.top/Article/details/gtvjeahpsy.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuanzx.com/Article/details/gtftfhzxaj.html

[Q25] 只取前 N 条
来源：http://dali.sxryk.cn/Article/details/gtrphgoxzu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.9152youxi.cn/Article/details/gtmkwtphlz.html

[Q26] 计数
来源：http://dali.xuanzx.com/Article/details/gtxgfehkpm.html

SELECT COUNT(*) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtbudesari.html

[Q27] 条件计数
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxzfrhcp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtuwykrxrv.html

[Q28] 求和与平均
来源：http://dali.smart0.xyz/Article/details/gtcmdvubmw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtcmyapjhj.html

[Q29] 最大最小值
来源：http://dali.bjfxy.top/Article/details/gtokngevux.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtowfktrwb.html

[Q30] 分组统计
来源：http://dali.pycfn.com/Article/details/gthjertlab.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtlltountg.html

[Q31] 分组后过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtcrcrvopd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj202588.top/Article/details/gttfxaehvc.html

[Q32] 分组拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtoomnxvwk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gtyycorgtg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.daxiang520.top/Article/details/gtuxegrzgu.html

[Q33] 多列分组
来源：http://dali.wangshuangyany.cn/Article/details/gttcgjzclx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.9152youxi.cn/Article/details/gtqwgnrqgz.html

[Q34] 每组取第一条
来源：http://dali.shzxlz.cn/Article/details/gtledxupsp.html

SELECT * FROM (
来源：http://dali.zhongyouzk.top/Article/details/gtzmxjbooi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.meibo888.top/Article/details/gtqgtnhmdb.html

) t WHERE rn = 1;
来源：http://dali.sufxvd.cn/Article/details/gttohnncrr.html

[Q35] 内连接
来源：http://dali.cashguo.top/Article/details/gtkpdmjnzg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gtuqhraxbr.html

[Q36] 左连接
来源：http://dali.yanxiufei.cn/Article/details/gtzcqngiwy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gthjcljmkn.html

[Q37] 右连接
来源：http://dali.aizwys.cn/Article/details/gtpbzpvixf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuanzhike.top/Article/details/gtvlikabfr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jyoumei.cn/Article/details/gttvztekbx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenzaomai.com/Article/details/gtcxmwpfuq.html

[Q39] 自连接（查上下级）
来源：http://dali.gotoacloud.top/Article/details/gthrtfkmro.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yueranfly.top/Article/details/gtqobndjlh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ehwqpu.com/Article/details/gtgykmznzi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.quarkkingdee.top/Article/details/gtbznoqwkf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.0kj1m.cn/Article/details/gtxzslzzcz.html

[Q41] 多表连接
来源：http://dali.aizwys.cn/Article/details/gtdktxvelx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hysaishi.cn/Article/details/gtcwpgvqrj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.feifeiyinyue.top/Article/details/gtsuxhemdx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yonumen.top/Article/details/gtrefxrkjo.html

[Q42] 连接条件附加过滤
来源：http://dali.yonumen.top/Article/details/gtechgvcnn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.fzhhl.top/Article/details/gtxkcofpgl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuxming.cn/Article/details/gtfbxmeejo.html

[Q43] 标量子查询
来源：http://dali.xylfe.cn/Article/details/gtcaznuyng.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgufenzy.top/Article/details/gtgdigazgq.html

[Q44] IN 子查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifvfozwp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhiwuduotai.top/Article/details/gtmmbhnrbo.html

[Q45] EXISTS 判断存在
来源：http://dali.hysaishi.cn/Article/details/gtvfrzdqim.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daxiang520.top/Article/details/gtvthobxmp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sweek.top/Article/details/gtithsvqtf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fengsongda.top/Article/details/gtsuiqvdkq.html

[Q47] 与平均值比较
来源：http://dali.cashguo.top/Article/details/gtdtqezsyo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.aizwys.cn/Article/details/gtpzddqesg.html

[Q48] CTE 公用表表达式
来源：http://dali.yvedp.cn/Article/details/gtsxdjtkti.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pengpengdd.cyou/Article/details/gtmdxtvmgo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xuanzx.com/Article/details/gtnogzxjte.html

[Q49] 更新单行
来源：http://dali.svipenyu.cn/Article/details/gtaunvozri.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.mhx1999.top/Article/details/gtslictksr.html

[Q50] 批量更新
来源：http://dali.jinqigufen.top/Article/details/gtbmifhwke.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jyoumei.cn/Article/details/gtqnatfqcr.html

[Q51] 用子查询更新
来源：http://dali.ybcxt.top/Article/details/gtgpetruno.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj202588.top/Article/details/gtckeevzvq.html

[Q52] 删除指定行
来源：http://dali.zhongyouzk.top/Article/details/gtcxgnqtmi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nanxinkj.top/Article/details/gtoqpxduzz.html

[Q53] 按条件删除
来源：http://dali.dashuyun.cn/Article/details/gtvtbzwdgi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowcpbmzg.html

[Q54] 清空表
来源：http://dali.ivvv.top/Article/details/gthgixwobt.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gtcubcyjpo.html

[Q55] 排名（并列占位）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtftwbzmrv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ybcxt.top/Article/details/gtuzhafemr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yuanzhike.top/Article/details/gtqteczzuj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibrwnkie.html

[Q57] 行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwijirivg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.daria6918.cn/Article/details/gtqwwdqwbd.html

[Q58] 累计求和
来源：http://dali.nwbrower.top/Article/details/gtfmcozyjc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtwdeevdqn.html

[Q59] 分组内累计
来源：http://dali.gzhubu.top/Article/details/gtmfqbwpsb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtnsyoquwu.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gtxbdgvmud.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.redwolf501.top/Article/details/gtmqjwtdii.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtpyhoifkc.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gtxrftbbhe.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cheryme.top/Article/details/gtesluxgaw.html

[Q62] 分组占比
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjvkrnhj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtdrdbkiir.html

[Q63] 开启事务
来源：http://dali.hywenlv.cn/Article/details/gtdkxfsfpx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nanxuanxn.top/Article/details/gtruvlasyq.html

[Q64] 提交事务
来源：http://dali.zhoulong.xyz/Article/details/gtsyoelbtr.html

COMMIT;
来源：http://dali.dianchejie.cn/Article/details/gtikqagyfz.html

[Q65] 回滚事务
来源：http://dali.zhoulong.xyz/Article/details/gtixwvqvyr.html

ROLLBACK;
来源：http://dali.meibo888.top/Article/details/gtwhmvqjie.html

[Q66] 行锁查询
来源：http://dali.gaohongyu789.top/Article/details/gtoqittmyb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.mhx1999.top/Article/details/gtptcmfrid.html

[Q67] 设置隔离级别
来源：http://dali.yj202588.top/Article/details/gtomsqtryz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shuidangran.top/Article/details/gtvnoplqwf.html

[Q68] 保存点
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxrofhnox.html

SAVEPOINT sp1;
来源：http://dali.sufxvd.cn/Article/details/gtdkbclomm.html

ROLLBACK TO sp1;
来源：http://dali.zhengqikj.top/Article/details/gtvhpbmiwj.html

[Q69] 查看执行计划
来源：http://dali.guannengcc.top/Article/details/gtwjioqsdu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cqqwz.cn/Article/details/gtefjfsmdr.html

[Q70] 更新统计信息
来源：http://dali.redwolf501.top/Article/details/gtjixvukwt.html

ANALYZE TABLE users;
来源：http://dali.vqdsnc.cn/Article/details/gtczjvwknq.html

[Q71] 查看建表语句
来源：http://dali.hnqzz.top/Article/details/gtzmdblxui.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.kuanghao11.cn/Article/details/gtpocsqivj.html

[Q72] 查看索引
来源：http://dali.jqgufenzy.top/Article/details/gtszmceqfc.html

SHOW INDEX FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtjxekbybh.html

[Q73] 查看表状态
来源：http://dali.yonumen.top/Article/details/gtcpuoxzzg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhengqikj.top/Article/details/gteyptzvcw.html

[Q74] 强制使用索引
来源：http://dali.tanke756.top/Article/details/gtvjhnlntn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinghuilouyu.cn/Article/details/gtuuzlepst.html

[Q75] 日期格式化
来源：http://dali.shzxlz.cn/Article/details/gtzutyvcdn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtdsarllfa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.pycfn.com/Article/details/gtanrrukzw.html

[Q76] 按天统计
来源：http://dali.xylfe.cn/Article/details/gtewqmjwdq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yonumen.top/Article/details/gtxrksbsfo.html

[Q77] 时间加减
来源：http://dali.ydzc1.top/Article/details/gtwedrtumi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.smart0.xyz/Article/details/gtxbbqwoqk.html

[Q78] 当前时间
来源：http://dali.yuxming.cn/Article/details/gtmlmovoyx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuanzhike.top/Article/details/gtotncfaog.html

[Q79] 字符串拼接
来源：http://dali.wangdashe.top/Article/details/gtguapicqc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tanke756.top/Article/details/gtdjhvhwpo.html

[Q80] 字符串截取
来源：http://dali.nwbrower.top/Article/details/gtzutcdmiq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtucmoxnaq.html

[Q81] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gtsizynsex.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtnikgzvee.html

[Q82] 字符长度与字节长度
来源：http://dali.zhengqikj.top/Article/details/gtfhmljozb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtmcwmlikx.html

[Q83] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gtrmyqcejb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtqaiteqyc.html

[Q84] 去除首尾空格
来源：http://dali.jiagoushi.top/Article/details/gtdvwsjmze.html

SELECT TRIM(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtmmatjxvk.html

[Q85] 数值取整
来源：http://dali.sxryk.cn/Article/details/gtvttvynbw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sufxvd.cn/Article/details/gtnykqfcrh.html

[Q86] 读取 JSON 字段
来源：http://dali.hfpthk.cn/Article/details/gtgadihgtw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gotoacloud.top/Article/details/gtsrjijomb.html

[Q87] JSON 字段做条件
来源：http://dali.nwbrower.top/Article/details/gtjedcnzej.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jlsjyb.cn/Article/details/gtatlbyopu.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhiwuduotai.top/Article/details/gtonkgltyf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yueranfly.top/Article/details/gtfudpgovv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtqflizmsd.html

[Q89] 判断表是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtijmprcjm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gtimajphqt.html

[Q90] 生成序号列
来源：http://dali.zhengqikj.top/Article/details/gtzwzfucof.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yvedp.cn/Article/details/gtwxpcomlz.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtbaiftwan.html

R. Bash 专题
来源：http://dali.daria6918.cn/Article/details/gtgqhsqvtk.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gthcdrkjci.html

[R01] shebang 与严格模式
来源：http://dali.hywenlv.cn/Article/details/gtqtwmqbgy.html

#!/usr/bin/env bash
来源：http://dali.meibo888.top/Article/details/gtgmyikoxw.html

set -euo pipefail
来源：http://dali.xylfe.cn/Article/details/gtzcqolyyl.html

[R02] 变量赋值与使用
来源：http://dali.zdqjudy.top/Article/details/gtpkcttulx.html

name="Tom"; echo "$name"
来源：http://dali.cucudq.cn/Article/details/gtqpwickvc.html

[R03] 只读变量
来源：http://dali.c1oappe.top/Article/details/gtequckkgo.html

readonly PI=3.14
来源：http://dali.tian-w.cn/Article/details/gtqkreivbv.html

[R04] 位置参数
来源：http://dali.shuidangran.top/Article/details/gtvsgmxwqm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gtvfdntnga.html

[R05] 参数默认值
来源：http://dali.feifeiyinyue.top/Article/details/gtktaqcvry.html

name="${1:-default}"
来源：http://dali.yvedp.cn/Article/details/gtohhmyuww.html

[R06] 判断命令是否存在
来源：http://dali.shuidangran.top/Article/details/gtgaouyasu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gtaplejxnv.html

[R07] if 判断文件
来源：http://dali.nanxinkj.top/Article/details/gttwrebony.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cucudq.cn/Article/details/gtmczslwfz.html

[R08] 数值比较
来源：http://dali.feifeiyinyue.top/Article/details/gtemibvgjl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.andypj.xyz/Article/details/gtbmabupdm.html

[R09] 字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gtywyeckdu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hysaishi.cn/Article/details/gtrcwhxhdh.html

[R10] 正则匹配
来源：http://dali.zhengqikj.top/Article/details/gtpgfszfnw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xziqi.cn/Article/details/gtembepzos.html

[R11] case 多分支
来源：http://dali.jlsjyb.cn/Article/details/gtdavrtiho.html

case "$1" in
来源：http://dali.shanyushiyangtech.top/Article/details/gtdfuozbpu.html

start) echo "启动" ;;
来源：http://dali.chenlongwang.top/Article/details/gttgdldhkh.html

stop)  echo "停止" ;;
来源：http://dali.hywenlv.cn/Article/details/gthkwjxjpp.html

*)     echo "未知命令" ;;
来源：http://dali.zycfv.cn/Article/details/gtsgzshkil.html

esac
来源：http://dali.ybcxt.top/Article/details/gtdodqrtuz.html

[R12] for 遍历文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvuriojc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gotoacloud.top/Article/details/gtjftagmtj.html

[R13] for 计数循环
来源：http://dali.c1oappe.top/Article/details/gtczshxrcz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gttykbxiri.html

[R14] C 风格 for
来源：http://dali.cashguo.top/Article/details/gthkzloilh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gtjkhqxcnw.html

[R15] while 逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtspvkgicw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shzxlz.cn/Article/details/gtkdrtrdon.html

[R16] until 等待条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwuvkeufw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ehwqpu.com/Article/details/gtlcuicpfd.html

[R17] 数组定义与取值
来源：http://dali.sweek.top/Article/details/gtgmisjhze.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zdqjudy.top/Article/details/gtzxrxdspm.html

[R18] 遍历数组
来源：http://dali.yj20258.top/Article/details/gtyarwkdoa.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.0kj1m.cn/Article/details/gtoicimwkz.html

[R19] 数组长度
来源：http://dali.shangyingyoupin.top/Article/details/gtdwjnwaij.html

echo "${#arr[@]}"
来源：http://dali.316326.xyz/Article/details/gtrouowmoc.html

[R20] 关联数组（字典）
来源：http://dali.sufxvd.cn/Article/details/gtlfjxmmel.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258.top/Article/details/gtuufuctbb.html

[R21] 字符串长度
来源：http://dali.dianchejie.cn/Article/details/gtviykzsxg.html

echo "${#s}"
来源：http://dali.yonumen.top/Article/details/gtzoszoisi.html

[R22] 截取子串
来源：http://dali.chenzaomai.com/Article/details/gtmnbpoodl.html

echo "${s:0:5}"
来源：http://dali.cashguo.top/Article/details/gtakmmerou.html

[R23] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gtsziaakab.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.feifeiyinyue.top/Article/details/gtpionlovo.html

[R24] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gtyabicoeu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ybcxt.top/Article/details/gtuaxszfoz.html

[R25] 去后缀 / 去前缀
来源：http://dali.shzxlz.cn/Article/details/gtafvokqau.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhiwuduotai.top/Article/details/gtffobgjwf.html

[R26] 命令替换
来源：http://dali.quarkkingdee.top/Article/details/gthcfnplrs.html

now=$(date +%F); echo "$now"
来源：http://dali.pengpengdd.cyou/Article/details/gteqiyrgsx.html

[R27] 算术展开
来源：http://dali.andypj.xyz/Article/details/gtkhhtonyi.html

echo $((1 + 2 * 3))
来源：http://dali.ybcxt.top/Article/details/gtdgloyihj.html

[R28] 浮点运算
来源：http://dali.hongshengwenyu.top/Article/details/gtlxufizxj.html

echo "scale=2; 10/3" | bc
来源：http://dali.jianghu66.top/Article/details/gtcufypgts.html

[R29] 定义函数
来源：http://dali.yangfankeji.com/Article/details/gtnjrwnkwb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.redwolf501.top/Article/details/gtsrkxorfa.html

[R30] 函数返回状态码
来源：http://dali.meibo888.top/Article/details/gtnlxfoykc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigufen.top/Article/details/gtusoyrybo.html

[R31] 局部变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevvhmftt.html

f() { local x=1; echo "$x"; }
来源：http://dali.c1oappe.top/Article/details/gtyamzldnm.html

[R32] 参数个数校验
来源：http://dali.fengsongda.top/Article/details/gtzaduioge.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.c1oappe.top/Article/details/gtupboudrr.html

[R33] 捕获错误并提示行号
来源：http://dali.daxiang520.top/Article/details/gtuqbysbec.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.wangshuangyany.cn/Article/details/gtjsqcalmn.html

[R34] 退出时清理
来源：http://dali.dianchejie.cn/Article/details/gtjtdjxyxr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sxryk.cn/Article/details/gtpfhkgwbx.html

[R35] 后台执行并等待
来源：http://dali.wangdashe.top/Article/details/gtenqmmnus.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hammf.cn/Article/details/gttmryoavu.html

[R36] 并发执行多个任务
来源：http://dali.ppjwa.cn/Article/details/gtedumjrdz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinghuilouyu.cn/Article/details/gtggwskkhk.html

[R37] 把输出赋给变量
来源：http://dali.zhixingplan.top/Article/details/gtomnigzzp.html

files=$(ls -1)
来源：http://dali.zhongyouzk.top/Article/details/gtfyysexoq.html

[R38] 管道串联
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrsivbgkx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnxiangtu.top/Article/details/gtyccpqaab.html

[R39] 重定向标准输出与错误
来源：http://dali.chenjidiqi.icu/Article/details/gtsclbeohn.html

cmd > out.log 2>&1
来源：http://dali.guowangkeji.top/Article/details/gtqxuenjny.html

[R40] 追加写日志
来源：http://dali.guannengcc.top/Article/details/gthrdpfyis.html

echo "log" >> out.log
来源：http://dali.feifeiyinyue.top/Article/details/gtwiweifrk.html

[R41] 丢弃输出
来源：http://dali.xylfe.cn/Article/details/gtlacoduuc.html

cmd >/dev/null 2>&1
来源：http://dali.wangdashe.top/Article/details/gtaxvqvirg.html

[R42] 输入重定向
来源：http://dali.feifeiyinyue.top/Article/details/gtebbedlmd.html

wc -l < a.txt
来源：http://dali.cqqwz.cn/Article/details/gtaeamzqbn.html

[R43] 按名字查找文件
来源：http://dali.zhixingplan.top/Article/details/gthptdzexe.html

find . -name "*.log" -type f
来源：http://dali.chenzaomai.com/Article/details/gtjpqqpulx.html

[R44] 按修改时间查找
来源：http://dali.birdmap.top/Article/details/gtyqzoknfc.html

find . -mtime -7 -type f
来源：http://dali.havefunace.top/Article/details/gtpcsoelpt.html

[R45] 批量删除
来源：http://dali.gogol.net.cn/Article/details/gtwhlmupcz.html

find . -name "*.tmp" -delete
来源：http://dali.0kj1m.cn/Article/details/gtywiuwhwx.html

[R46] 递归替换文件内容
来源：http://dali.sysykeji.top/Article/details/gtjkbniyjk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhixingplan.top/Article/details/gtmpirqeot.html

[R47] sed 单行替换
来源：http://dali.9152youxi.cn/Article/details/gtnzricvaj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtiiwkjzth.html

[R48] awk 取指定列
来源：http://dali.havefunace.top/Article/details/gtsufmauez.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxyamcdhx.html

[R49] awk 带条件
来源：http://dali.ydzc1.top/Article/details/gtjahmjrvw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gotoacloud.top/Article/details/gtuvlbkhox.html

[R50] awk 求和
来源：http://dali.yangfankeji.com/Article/details/gtscfjcrui.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmryvuzs.html

[R51] 排序去重取前几
来源：http://dali.cucudq.cn/Article/details/gtaccvbczk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.quarkkingdee.top/Article/details/gtplvwlwej.html

[R52] 统计行数
来源：http://dali.gogol.net.cn/Article/details/gtbjoxmtuw.html

wc -l a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyyqoknxg.html

[R53] 查看文件头与实时尾
来源：http://dali.tianlin.xyz/Article/details/gtqwagatne.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sweek.top/Article/details/gtcfzgdqfz.html

[R54] 比较两个文件
来源：http://dali.gzhubu.top/Article/details/gtslpaqynt.html

diff a.txt b.txt
来源：http://dali.yj20258888.top/Article/details/gtpyryxtca.html

[R55] 压缩与解压
来源：http://dali.chenlongwang.top/Article/details/gtrlmmtavs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daxiang520.top/Article/details/gtpzwtqwpl.html

[R56] 远程拷贝
来源：http://dali.shuidangran.top/Article/details/gtkvclvoiy.html

scp file user@host:/path/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoztbljcu.html

[R57] 远程执行命令
来源：http://dali.yj20258.top/Article/details/gtndcgiqdg.html

ssh user@host 'uptime'
来源：http://dali.daria6918.cn/Article/details/gtjmemdegv.html

[R58] 下载文件
来源：http://dali.fengsongda.top/Article/details/gtpjqhvytl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xinyue.icu/Article/details/gtoekoaqaq.html

[R59] 发 POST JSON
来源：http://dali.xuanzx.com/Article/details/gtfcwroija.html


<!-- 参考信息 -->