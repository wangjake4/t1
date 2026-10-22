代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pengpengdd.cyou/Article/details/gtekpdwjhl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yueranfly.top/Article/details/gthrzhperx.html

[Q13] 忽略重复插入
来源：http://dali.bjfxy.top/Article/details/gtmhudrklu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sufxvd.cn/Article/details/gtbzkdhmqy.html

[Q14] 存在则更新（upsert）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyaapdoch.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.daria6918.cn/Article/details/gtwhekcvze.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yanxiufei.cn/Article/details/gtfculgahw.html

[Q15] 查询全部
来源：http://dali.hnqzz.top/Article/details/gtjllmxlsb.html

SELECT * FROM users;
来源：http://dali.sweek.top/Article/details/gtnwytxhff.html

[Q16] 查询指定列
来源：http://dali.guannengcc.top/Article/details/gtfnologaz.html

SELECT id, name FROM users;
来源：http://dali.sysykeji.top/Article/details/gtlpxwixoe.html

[Q17] 条件查询
来源：http://dali.yuxming.cn/Article/details/gtunrznwpt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yongpay.top/Article/details/gtmrmdaajo.html

[Q18] 模糊匹配
来源：http://dali.jinqigfzy.top/Article/details/gtitqjikwi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sufxvd.cn/Article/details/gtawpyblxl.html

[Q19] 范围查询
来源：http://dali.hnqzz.top/Article/details/gtyydbzbtg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cucudq.cn/Article/details/gtgcckbumm.html

[Q20] IN 列表
来源：http://dali.gotoacloud.top/Article/details/gtwgkmzpab.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yongpay.top/Article/details/gthqwmsniz.html

[Q21] 空值判断
来源：http://dali.0kj1m.cn/Article/details/gtzvxbhgru.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xziqi.cn/Article/details/gtfyvqhcnt.html

[Q22] 排序
来源：http://dali.hfpthk.cn/Article/details/gtxwhovqug.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cheryme.top/Article/details/gtyexftoqd.html

[Q23] 分页
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzqeafpa.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hysaishi.cn/Article/details/gtejxxddrk.html

[Q24] 去重
来源：http://dali.chenlongwang.top/Article/details/gtgfpteyhy.html

SELECT DISTINCT city FROM users;
来源：http://dali.9152youxi.cn/Article/details/gteceugkun.html

[Q25] 只取前 N 条
来源：http://dali.sweek.top/Article/details/gtpjnsyarb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yonumen.top/Article/details/gtnvmwowhm.html

[Q26] 计数
来源：http://dali.zdqjudy.top/Article/details/gtlcfrzqiu.html

SELECT COUNT(*) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtfuqtwtoe.html

[Q27] 条件计数
来源：http://dali.zhongyouzk.top/Article/details/gtjqgzcdmz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.iojbl.cn/Article/details/gteajhitqc.html

[Q28] 求和与平均
来源：http://dali.xylfe.cn/Article/details/gtwesnkncl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtinegtpej.html

[Q29] 最大最小值
来源：http://dali.zhixingplan.top/Article/details/gtsgiwcpba.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtadvoxwsl.html

[Q30] 分组统计
来源：http://dali.haohaochexian.top/Article/details/gtcnttbfik.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gtadihimky.html

[Q31] 分组后过滤
来源：http://dali.chenzaomai.com/Article/details/gtoejaqoft.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.meibo888.top/Article/details/gtmgzapbbj.html

[Q32] 分组拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gtaaixicxc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gtkyoyjaap.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuetiantiany.cn/Article/details/gtdgosekbv.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gtntojylgx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shangyingyoupin.top/Article/details/gtlmyoivwv.html

[Q34] 每组取第一条
来源：http://dali.svipenyu.cn/Article/details/gtxorwlfxz.html

SELECT * FROM (
来源：http://dali.hfpthk.cn/Article/details/gtgxuuipbj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.svipenyu.cn/Article/details/gtaydgsuuh.html

) t WHERE rn = 1;
来源：http://dali.yuxming.cn/Article/details/gtolkcomtv.html

[Q35] 内连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzobdyta.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258.top/Article/details/gtncidxicv.html

[Q36] 左连接
来源：http://dali.hongshengwenyu.top/Article/details/gtbrydvczo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gtqufkatcl.html

[Q37] 右连接
来源：http://dali.ydzc1.top/Article/details/gtcewzdlej.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hongshengwenyu.top/Article/details/gtvgqpawch.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jyoumei.cn/Article/details/gtwlejrhwt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.9152youxi.cn/Article/details/gtwrfkbsdo.html

[Q39] 自连接（查上下级）
来源：http://dali.tianlin.xyz/Article/details/gtkpkmthnb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.iojbl.cn/Article/details/gtwnfomyto.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.haohaochexian.top/Article/details/gtmsjtlqrw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcxethvh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hnqzz.top/Article/details/gtxrsaowpe.html

[Q41] 多表连接
来源：http://dali.yj202588.top/Article/details/gtravrwwvc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shzxlz.cn/Article/details/gtugynvyga.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ybcxt.top/Article/details/gtcscgqupj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ivvv.top/Article/details/gtfrmjzbaw.html

[Q42] 连接条件附加过滤
来源：http://dali.bjfxy.top/Article/details/gtwomosvwp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ehwqpu.com/Article/details/gtljcysbwc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenzaomai.com/Article/details/gtmrcjwinw.html

[Q43] 标量子查询
来源：http://dali.xuanzx.com/Article/details/gtvtxdgxxx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xuetiantiany.cn/Article/details/gtzjaatvyq.html

[Q44] IN 子查询
来源：http://dali.zhiwuduotai.top/Article/details/gtmbajzspx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yangfankeji.com/Article/details/gtskysupoj.html

[Q45] EXISTS 判断存在
来源：http://dali.cashguo.top/Article/details/gtztazoyjx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gtgjncakdc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yonumen.top/Article/details/gtflvmsrbx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.andypj.xyz/Article/details/gtmfahwuqa.html

[Q47] 与平均值比较
来源：http://dali.ehwqpu.com/Article/details/gtpsevozuj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.daxiang520.top/Article/details/gtnxxkurgl.html

[Q48] CTE 公用表表达式
来源：http://dali.c1oappe.top/Article/details/gtjwvvwkum.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuxming.cn/Article/details/gtwbqepztd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj202588.top/Article/details/gtgchjsfdl.html

[Q49] 更新单行
来源：http://dali.wangdashe.top/Article/details/gttddnwpjh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gtmflbgoup.html

[Q50] 批量更新
来源：http://dali.smart0.xyz/Article/details/gtfmxmgczy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gtokveoebj.html

[Q51] 用子查询更新
来源：http://dali.bjfxy.top/Article/details/gtwcxuzblv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jianghu66.top/Article/details/gtrrjuvlbs.html

[Q52] 删除指定行
来源：http://dali.jqgufenzy.top/Article/details/gtwmtgeysm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.wangdashe.top/Article/details/gtayrfcfdm.html

[Q53] 按条件删除
来源：http://dali.chenlongwang.top/Article/details/gtidutvofg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gtweexpcic.html

[Q54] 清空表
来源：http://dali.tianlin.xyz/Article/details/gtrddejygr.html

TRUNCATE TABLE logs;
来源：http://dali.nwbrower.top/Article/details/gtwyiqfrji.html

[Q55] 排名（并列占位）
来源：http://dali.aizwys.cn/Article/details/gtypptdumd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.c1oappe.top/Article/details/gthkmvkrpv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yongpay.top/Article/details/gtfgmywlmz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.smart0.xyz/Article/details/gtefkcdqgb.html

[Q57] 行号
来源：http://dali.havefunace.top/Article/details/gtstnfcahj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ydzc1.top/Article/details/gtqyeckxhg.html

[Q58] 累计求和
来源：http://dali.jlsjyb.cn/Article/details/gtfrjdarho.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtfeynhznk.html

[Q59] 分组内累计
来源：http://dali.yangfankeji.com/Article/details/gtkdnhpctq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gthkztzidw.html

[Q60] 取上一行 / 下一行
来源：http://dali.quarkkingdee.top/Article/details/gtvmejdxpp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jiagoushi.top/Article/details/gtkwqjrqvq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtjlcnbaqp.html

[Q61] 移动平均
来源：http://dali.sweek.top/Article/details/gtcacuodjy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtzrtmvucc.html

[Q62] 分组占比
来源：http://dali.dianchejie.cn/Article/details/gtwkpxikwr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gtrpuuodji.html

[Q63] 开启事务
来源：http://dali.chenlongwang.top/Article/details/gtmwwjyflo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sufxvd.cn/Article/details/gthpfcpzsz.html

[Q64] 提交事务
来源：http://dali.c1oappe.top/Article/details/gtvjcxxzhp.html

COMMIT;
来源：http://dali.jianghu66.top/Article/details/gthsfbrwib.html

[Q65] 回滚事务
来源：http://dali.jqgfzy.top/Article/details/gtnssikiui.html

ROLLBACK;
来源：http://dali.sweek.top/Article/details/gtsrisgznu.html

[Q66] 行锁查询
来源：http://dali.gzhubu.top/Article/details/gtnpxnekxb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xinyue.icu/Article/details/gtfluvrdse.html

[Q67] 设置隔离级别
来源：http://dali.xuanzx.com/Article/details/gtaurhayai.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cashguo.top/Article/details/gthhzpgukz.html

[Q68] 保存点
来源：http://dali.sweek.top/Article/details/gttwnemayk.html

SAVEPOINT sp1;
来源：http://dali.svipenyu.cn/Article/details/gtxzsligst.html

ROLLBACK TO sp1;
来源：http://dali.aizwys.cn/Article/details/gtkvrqwauc.html

[Q69] 查看执行计划
来源：http://dali.xziqi.cn/Article/details/gtfnykamhl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ivvv.top/Article/details/gtxnxswkbp.html

[Q70] 更新统计信息
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrhozwdc.html

ANALYZE TABLE users;
来源：http://dali.dianchejie.cn/Article/details/gtzvosfmyv.html

[Q71] 查看建表语句
来源：http://dali.jqgufenzy.top/Article/details/gtjvzlmcnu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.wangdashe.top/Article/details/gtrsubbrjs.html

[Q72] 查看索引
来源：http://dali.tanke756.top/Article/details/gtxswtlbvn.html

SHOW INDEX FROM users;
来源：http://dali.fzhhl.top/Article/details/gtbwfdfcfq.html

[Q73] 查看表状态
来源：http://dali.wangdashe.top/Article/details/gtdxwiwows.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.haohaochexian.top/Article/details/gtwsnzkpzc.html

[Q74] 强制使用索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhrceogf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.9152youxi.cn/Article/details/gtpthtvyrw.html

[Q75] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gtkmpqmqif.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtvcafnbsl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yvedp.cn/Article/details/gtgvnhbehr.html

[Q76] 按天统计
来源：http://dali.cashguo.top/Article/details/gtukyfalzj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gotoacloud.top/Article/details/gtmghnpsfy.html

[Q77] 时间加减
来源：http://dali.dianchejie.cn/Article/details/gtcrawsfsa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.haohaochexian.top/Article/details/gtzoxicygh.html

[Q78] 当前时间
来源：http://dali.yuanzhike.top/Article/details/gtjbuwrged.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxuanxn.top/Article/details/gtlbocbbhx.html

[Q79] 字符串拼接
来源：http://dali.shangyingyoupin.top/Article/details/gtykvnzvjn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nanxinkj.top/Article/details/gtwmqqzxsv.html

[Q80] 字符串截取
来源：http://dali.hnqzz.top/Article/details/gtfkdjlsmr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj202588.top/Article/details/gtitvfhuyl.html

[Q81] 字符串替换
来源：http://dali.xuanzx.com/Article/details/gtxfytwrzy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtqywgvbeb.html

[Q82] 字符长度与字节长度
来源：http://dali.wangdashe.top/Article/details/gthnzaieiw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gttyjpwpwi.html

[Q83] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gtkhwuuaop.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtuukefxuz.html

[Q84] 去除首尾空格
来源：http://dali.hysaishi.cn/Article/details/gtbpnyljno.html

SELECT TRIM(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtvdudszgq.html

[Q85] 数值取整
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyosshka.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sweek.top/Article/details/gtkrqonnhb.html

[Q86] 读取 JSON 字段
来源：http://dali.ivvv.top/Article/details/gtzoyvacyu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.daria6918.cn/Article/details/gtwfapknnf.html

[Q87] JSON 字段做条件
来源：http://dali.guowangkeji.top/Article/details/gtfdxgwble.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.dashuyun.cn/Article/details/gtpqtienjv.html

[Q88] 行转列（条件聚合）
来源：http://dali.daria6918.cn/Article/details/gttlteevsy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daria6918.cn/Article/details/gtefjrxvzd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylgzymem.html

[Q89] 判断表是否存在
来源：http://dali.xziqi.cn/Article/details/gtqqqctcfm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.bjfxy.top/Article/details/gtmdkbabfv.html

[Q90] 生成序号列
来源：http://dali.birdmap.top/Article/details/gtvabcowdo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenzaomai.com/Article/details/gtjmnbvbmq.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gthvnduqhm.html

R. Bash 专题
来源：http://dali.ybcxt.top/Article/details/gtrtuveemj.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzyhagjc.html

[R01] shebang 与严格模式
来源：http://dali.tian-w.cn/Article/details/gtboorktqx.html

#!/usr/bin/env bash
来源：http://dali.daria6918.cn/Article/details/gtojxqozkd.html

set -euo pipefail
来源：http://dali.yangfankeji.com/Article/details/gtsraqniju.html

[R02] 变量赋值与使用
来源：http://dali.chenjidiqi.icu/Article/details/gtnbylbhwv.html

name="Tom"; echo "$name"
来源：http://dali.jqgfzy.top/Article/details/gtkktyzxwu.html

[R03] 只读变量
来源：http://dali.zhixingplan.top/Article/details/gtiwmholjt.html

readonly PI=3.14
来源：http://dali.havefunace.top/Article/details/gtfkooigdt.html

[R04] 位置参数
来源：http://dali.feifeiyinyue.top/Article/details/gtrapoazum.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tanke756.top/Article/details/gtewqubmbw.html

[R05] 参数默认值
来源：http://dali.yj20258888.top/Article/details/gtmiezwwcu.html

name="${1:-default}"
来源：http://dali.redwolf501.top/Article/details/gtbnglcrvv.html

[R06] 判断命令是否存在
来源：http://dali.jianghu66.top/Article/details/gtictgmifh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gtjwpbznro.html

[R07] if 判断文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwcivzwvl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.dashuyun.cn/Article/details/gtupkagpbu.html

[R08] 数值比较
来源：http://dali.gaohongyu789.top/Article/details/gtgtluxkbc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ydzc1.top/Article/details/gtjtzwtcjs.html

[R09] 字符串比较
来源：http://dali.316326.xyz/Article/details/gtirhzbbum.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guannengcc.top/Article/details/gtwkreywox.html

[R10] 正则匹配
来源：http://dali.chenzaomai.com/Article/details/gtbyvmdspm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cheryme.top/Article/details/gtroqkmwgc.html

[R11] case 多分支
来源：http://dali.jianghu66.top/Article/details/gtrgrbmbdm.html

case "$1" in
来源：http://dali.nanxinkj.top/Article/details/gtdiqdqqwm.html

start) echo "启动" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoikysxoi.html

stop)  echo "停止" ;;
来源：http://dali.gzhubu.top/Article/details/gtdjouaybq.html

*)     echo "未知命令" ;;
来源：http://dali.yuanzhike.top/Article/details/gtgfvuehjk.html

esac
来源：http://dali.bjfxy.top/Article/details/gtglpirnbf.html

[R12] for 遍历文件
来源：http://dali.jlsjyb.cn/Article/details/gtxtrqqjpg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxuanxn.top/Article/details/gtkbhrfyek.html

[R13] for 计数循环
来源：http://dali.yuanzhike.top/Article/details/gttinrsqld.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.andypj.xyz/Article/details/gtnnuuretk.html

[R14] C 风格 for
来源：http://dali.shzxlz.cn/Article/details/gtokfdwnjf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gtwylglcdv.html

[R15] while 逐行读文件
来源：http://dali.yongpay.top/Article/details/gtdpzoglbh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gaohongyu789.top/Article/details/gtqwusqfrs.html

[R16] until 等待条件
来源：http://dali.mhx1999.top/Article/details/gtouevbimp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xinyue.icu/Article/details/gtarokiyag.html

[R17] 数组定义与取值
来源：http://dali.ppjwa.cn/Article/details/gtawfoiepm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shuidangran.top/Article/details/gtstfhkvei.html

[R18] 遍历数组
来源：http://dali.jyoumei.cn/Article/details/gthclwjjnn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yvedp.cn/Article/details/gtrzmcqkal.html

[R19] 数组长度
来源：http://dali.havefunace.top/Article/details/gtyaxapptb.html

echo "${#arr[@]}"
来源：http://dali.quarkkingdee.top/Article/details/gteofejcla.html

[R20] 关联数组（字典）
来源：http://dali.dashuyun.cn/Article/details/gtaxxhiahe.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gogol.net.cn/Article/details/gtzvztinpx.html

[R21] 字符串长度
来源：http://dali.daxiang520.top/Article/details/gtyualzbga.html

echo "${#s}"
来源：http://dali.sweek.top/Article/details/gtaqwtgrsp.html

[R22] 截取子串
来源：http://dali.yonumen.top/Article/details/gtxmphnwas.html

echo "${s:0:5}"
来源：http://dali.hnxiangtu.top/Article/details/gtyrubohyr.html

[R23] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gtctqvkbqe.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.smart0.xyz/Article/details/gtexszjvrx.html

[R24] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gtdrlxqozb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.wangdashe.top/Article/details/gtnojtbtus.html

[R25] 去后缀 / 去前缀
来源：http://dali.cheryme.top/Article/details/gtixqhoitq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbphairv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gttpgvzycc.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gtaelqooqj.html

[R27] 算术展开
来源：http://dali.dashuyun.cn/Article/details/gtcmfhabmm.html

echo $((1 + 2 * 3))
来源：http://dali.cheryme.top/Article/details/gtfhnvprdd.html

[R28] 浮点运算
来源：http://dali.gotoacloud.top/Article/details/gtjpkwrhtk.html

echo "scale=2; 10/3" | bc
来源：http://dali.sysykeji.top/Article/details/gtdpccvqgq.html

[R29] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtskdaiiza.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hammf.cn/Article/details/gtuglmoepm.html

[R30] 函数返回状态码
来源：http://dali.cdnleiting.top/Article/details/gthpqvhtwq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhengqikj.top/Article/details/gtyxtefgsu.html

[R31] 局部变量
来源：http://dali.ppjwa.cn/Article/details/gtvkjsafoe.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtllnawivx.html

[R32] 参数个数校验
来源：http://dali.chenzaomai.com/Article/details/gtlyxjvlwi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvygbhma.html

[R33] 捕获错误并提示行号
来源：http://dali.yj20258.top/Article/details/gtqhwmfxfb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdsauyrh.html

[R34] 退出时清理
来源：http://dali.kuanghao11.cn/Article/details/gtubbddunu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gtjendmodq.html

[R35] 后台执行并等待
来源：http://dali.shuidangran.top/Article/details/gtyohoezgw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhongyouzk.top/Article/details/gtthqdbxut.html

[R36] 并发执行多个任务
来源：http://dali.zhongyouzk.top/Article/details/gtotwviidf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sufxvd.cn/Article/details/gtcaqaxpms.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gttdlahcie.html

files=$(ls -1)
来源：http://dali.hfpthk.cn/Article/details/gtwahqiyvc.html

[R38] 管道串联
来源：http://dali.jinqigufen.top/Article/details/gtncximqfj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.snrcjt.cn/Article/details/gtzamzaafb.html

[R39] 重定向标准输出与错误
来源：http://dali.yuxming.cn/Article/details/gtpkfxeajk.html

cmd > out.log 2>&1
来源：http://dali.fengsongda.top/Article/details/gtoynpzwoq.html

[R40] 追加写日志
来源：http://dali.gotoacloud.top/Article/details/gtprvexuib.html

echo "log" >> out.log
来源：http://dali.cdnleiting.top/Article/details/gtxrrruspl.html

[R41] 丢弃输出
来源：http://dali.xinyue.icu/Article/details/gtydisppls.html

cmd >/dev/null 2>&1
来源：http://dali.nanxinkj.top/Article/details/gtzouuarpu.html

[R42] 输入重定向
来源：http://dali.zhoulong.xyz/Article/details/gtbkwushzz.html

wc -l < a.txt
来源：http://dali.aizwys.cn/Article/details/gtbeltbmgn.html

[R43] 按名字查找文件
来源：http://dali.feifeiyinyue.top/Article/details/gtmceviwqc.html

find . -name "*.log" -type f
来源：http://dali.fengsongda.top/Article/details/gtrktarlqa.html

[R44] 按修改时间查找
来源：http://dali.zhiwuduotai.top/Article/details/gtyonjjlti.html

find . -mtime -7 -type f
来源：http://dali.jinqigufen.top/Article/details/gtnkoisjox.html

[R45] 批量删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxeqxsitk.html

find . -name "*.tmp" -delete
来源：http://dali.cucudq.cn/Article/details/gtameyeytx.html

[R46] 递归替换文件内容
来源：http://dali.zhixingplan.top/Article/details/gtranjvefi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsaksidjg.html

[R47] sed 单行替换
来源：http://dali.aizwys.cn/Article/details/gtibccseyq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtjzgjqazq.html

[R48] awk 取指定列
来源：http://dali.tanke756.top/Article/details/gtkbwsrpyn.html

awk '{print $1, $3}' a.txt
来源：http://dali.zycfv.cn/Article/details/gtamwybghb.html

[R49] awk 带条件
来源：http://dali.c1oappe.top/Article/details/gtcjxtkifm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuixzecju.html

[R50] awk 求和
来源：http://dali.jinqigfzy.top/Article/details/gtdwjpygwx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtqxatmngu.html

[R51] 排序去重取前几
来源：http://dali.ehwqpu.com/Article/details/gtjxvgvsbf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yongpay.top/Article/details/gtmajjimvh.html

[R52] 统计行数
来源：http://dali.bjfxy.top/Article/details/gtophjeevv.html

wc -l a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtyqgsrpie.html

[R53] 查看文件头与实时尾
来源：http://dali.sysykeji.top/Article/details/gtscovezlu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.fzhhl.top/Article/details/gtwysesqtg.html

[R54] 比较两个文件
来源：http://dali.yangfankeji.com/Article/details/gtgodnbczk.html

diff a.txt b.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtztequvqq.html

[R55] 压缩与解压
来源：http://dali.cqqwz.cn/Article/details/gtdqxajrna.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvrsjfvrh.html

[R56] 远程拷贝
来源：http://dali.hysaishi.cn/Article/details/gtldprfsss.html

scp file user@host:/path/
来源：http://dali.tian-w.cn/Article/details/gtabvmeezk.html

[R57] 远程执行命令
来源：http://dali.dianchejie.cn/Article/details/gtejeezxet.html

ssh user@host 'uptime'
来源：http://dali.fzhhl.top/Article/details/gttknqrxpv.html

[R58] 下载文件
来源：http://dali.haohaochexian.top/Article/details/gtarfuyyiq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.pycfn.com/Article/details/gtrgjznkep.html

[R59] 发 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxulgiwa.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnxiangtu.top/Article/details/gtqysabaud.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfkwzvmc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzilmycc.html

[R61] 磁盘占用
来源：http://dali.jqgufenzy.top/Article/details/gtxrgivbpc.html


<!-- 参考信息 -->