代发 wailian999

[Q14] 存在则更新（upsert）
来源：http://dali.svipenyu.cn/Article/details/gtynoqemll.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbrgtghs.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.pycfn.com/Article/details/gtaawunubb.html

[Q15] 查询全部
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbbqwger.html

SELECT * FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfukqyuq.html

[Q16] 查询指定列
来源：http://dali.cashguo.top/Article/details/gtesmagaws.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtrozqjftd.html

[Q17] 条件查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpeibwvub.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guannengcc.top/Article/details/gtgmbiblbx.html

[Q18] 模糊匹配
来源：http://dali.jinqigufen.top/Article/details/gtypejssbe.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xinyue.icu/Article/details/gtdxqrgduk.html

[Q19] 范围查询
来源：http://dali.nanxinkj.top/Article/details/gthfhgqogg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.dianchejie.cn/Article/details/gtfvajhfkt.html

[Q20] IN 列表
来源：http://dali.aizwys.cn/Article/details/gtysopirko.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xziqi.cn/Article/details/gtuqspkpba.html

[Q21] 空值判断
来源：http://dali.jlsjyb.cn/Article/details/gtiqnidcdc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.c1oappe.top/Article/details/gtiozaczqo.html

[Q22] 排序
来源：http://dali.hysaishi.cn/Article/details/gtuglrnmzn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.aibaodan.cn/Article/details/gtuugsphfq.html

[Q23] 分页
来源：http://dali.zhongyouzk.top/Article/details/gtoqmotgwa.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenlongwang.top/Article/details/gtakcsojzv.html

[Q24] 去重
来源：http://dali.yj202588.top/Article/details/gtwvjtiggh.html

SELECT DISTINCT city FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtbuobrnvl.html

[Q25] 只取前 N 条
来源：http://dali.yj20258888.top/Article/details/gtshkzvvnf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sysykeji.top/Article/details/gtlitcbyod.html

[Q26] 计数
来源：http://dali.gaohongyu789.top/Article/details/gtvqrdjryi.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtpzgtsskf.html

[Q27] 条件计数
来源：http://dali.zycfv.cn/Article/details/gthvasainw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtbakncyyn.html

[Q28] 求和与平均
来源：http://dali.ppjwa.cn/Article/details/gtyjisvmzg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtvyjdaqzo.html

[Q29] 最大最小值
来源：http://dali.tian-w.cn/Article/details/gtibounshl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtztdqxqri.html

[Q30] 分组统计
来源：http://dali.hfpthk.cn/Article/details/gtyhtlgdhe.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gtpwipzzsr.html

[Q31] 分组后过滤
来源：http://dali.daxiang520.top/Article/details/gtgbmakrbr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.316326.xyz/Article/details/gtlbextdka.html

[Q32] 分组拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtbzqdpa.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gtwgazwbdp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.birdmap.top/Article/details/gtptewjcxv.html

[Q33] 多列分组
来源：http://dali.haohaochexian.top/Article/details/gtsdhyccnk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhixingplan.top/Article/details/gtztlbasfi.html

[Q34] 每组取第一条
来源：http://dali.ppjwa.cn/Article/details/gtpurlmclc.html

SELECT * FROM (
来源：http://dali.gotoacloud.top/Article/details/gtpdnjsfkr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.316326.xyz/Article/details/gtxwvfusda.html

) t WHERE rn = 1;
来源：http://dali.dashuyun.cn/Article/details/gtdpyhtjsu.html

[Q35] 内连接
来源：http://dali.yueranfly.top/Article/details/gtubwlinmm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gtuqwewzre.html

[Q36] 左连接
来源：http://dali.chenlongwang.top/Article/details/gtxgfzjmia.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuanzx.com/Article/details/gtxojiliml.html

[Q37] 右连接
来源：http://dali.redwolf501.top/Article/details/gteuqnhkzi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.svipenyu.cn/Article/details/gtxlujmcts.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.guannengcc.top/Article/details/gtoqhriogj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cdnleiting.top/Article/details/gtsxhuzpin.html

[Q39] 自连接（查上下级）
来源：http://dali.jqgufenzy.top/Article/details/gtspyxdtxz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.smart0.xyz/Article/details/gtscmmtkzj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhengqikj.top/Article/details/gtvsjofzmi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sweek.top/Article/details/gttpxtxigi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenjidiqi.icu/Article/details/gttnhpnodt.html

[Q41] 多表连接
来源：http://dali.zhengqikj.top/Article/details/gtjfhpsapa.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.haohaochexian.top/Article/details/gtrcumkrst.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sxryk.cn/Article/details/gtsgddzrdu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yvedp.cn/Article/details/gtlfixwnmy.html

[Q42] 连接条件附加过滤
来源：http://dali.yj20258.top/Article/details/gtuiamzsxe.html

SELECT u.name, o.amount FROM users u
来源：http://dali.birdmap.top/Article/details/gtqqyphuxb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.meibo888.top/Article/details/gtalkgytdr.html

[Q43] 标量子查询
来源：http://dali.cdnleiting.top/Article/details/gtjbboypwj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.wangshuangyany.cn/Article/details/gtkxywiobf.html

[Q44] IN 子查询
来源：http://dali.ppjwa.cn/Article/details/gtgbjaiejn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sufxvd.cn/Article/details/gtwgjmsrdr.html

[Q45] EXISTS 判断存在
来源：http://dali.zhoulong.xyz/Article/details/gtxsujgigo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnxiangtu.top/Article/details/gtwtqwdyap.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sxryk.cn/Article/details/gtkncxyvdy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gttzbapjyi.html

[Q47] 与平均值比较
来源：http://dali.xuanzx.com/Article/details/gtiphgjuzo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangtech.top/Article/details/gtatwmjkms.html

[Q48] CTE 公用表表达式
来源：http://dali.nanxinkj.top/Article/details/gtjsjetedb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.daxiang520.top/Article/details/gtotuhpkxu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj202588.top/Article/details/gtnlendsqs.html

[Q49] 更新单行
来源：http://dali.ivvv.top/Article/details/gtsgbezqhu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtivwrexqb.html

[Q50] 批量更新
来源：http://dali.hammf.cn/Article/details/gthzqmiudh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daxiang520.top/Article/details/gtqjznyyen.html

[Q51] 用子查询更新
来源：http://dali.wangdashe.top/Article/details/gtlnebmrco.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjstysvz.html

[Q52] 删除指定行
来源：http://dali.jianghu66.top/Article/details/gtoasewmek.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yuxming.cn/Article/details/gtwvycuacj.html

[Q53] 按条件删除
来源：http://dali.gotoacloud.top/Article/details/gtiymqmqxj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yvedp.cn/Article/details/gtgpxdbnee.html

[Q54] 清空表
来源：http://dali.chenlongwang.top/Article/details/gtbrrgwlcl.html

TRUNCATE TABLE logs;
来源：http://dali.havefunace.top/Article/details/gtgxyxmzpe.html

[Q55] 排名（并列占位）
来源：http://dali.0kj1m.cn/Article/details/gtdwegcpun.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nanxuanxn.top/Article/details/gtmvqoqrqw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.fengsongda.top/Article/details/gtgljthivj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gtdqropryd.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gtjqqdrlwa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cucudq.cn/Article/details/gtqdnmkpxy.html

[Q58] 累计求和
来源：http://dali.yongpay.top/Article/details/gtzwhdldzj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gttlpyyshy.html

[Q59] 分组内累计
来源：http://dali.shzxlz.cn/Article/details/gtmzkhtrru.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtpumkkbpl.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoshydwgg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pycfn.com/Article/details/gtxjvnxyai.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtptrhshcc.html

[Q61] 移动平均
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjzjbqxm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtvmlkbuvc.html

[Q62] 分组占比
来源：http://dali.bjfxy.top/Article/details/gtxngmovgt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gtpkfvabra.html

[Q63] 开启事务
来源：http://dali.mhx1999.top/Article/details/gtokvhubem.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sysykeji.top/Article/details/gtwbgmiizr.html

[Q64] 提交事务
来源：http://dali.0kj1m.cn/Article/details/gtgvdycimw.html

COMMIT;
来源：http://dali.jiagoushi.top/Article/details/gtqpehyast.html

[Q65] 回滚事务
来源：http://dali.tanke756.top/Article/details/gtrbenrlab.html

ROLLBACK;
来源：http://dali.jqgufenzy.top/Article/details/gtqgrjnzyx.html

[Q66] 行锁查询
来源：http://dali.wangdashe.top/Article/details/gthzspxmrf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj20258.top/Article/details/gtouyffejl.html

[Q67] 设置隔离级别
来源：http://dali.xuanzx.com/Article/details/gtrodyathi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.quarkkingdee.top/Article/details/gtvvmvxrje.html

[Q68] 保存点
来源：http://dali.cqqwz.cn/Article/details/gtgapgejgo.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgsobmzxe.html

ROLLBACK TO sp1;
来源：http://dali.jinqigfzy.top/Article/details/gthsdujomv.html

[Q69] 查看执行计划
来源：http://dali.tianlin.xyz/Article/details/gttljzaxnm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.redwolf501.top/Article/details/gtymsagukv.html

[Q70] 更新统计信息
来源：http://dali.yuxming.cn/Article/details/gtnknvosct.html

ANALYZE TABLE users;
来源：http://dali.nwbrower.top/Article/details/gtubhvescj.html

[Q71] 查看建表语句
来源：http://dali.yuanzhike.top/Article/details/gtmvucsqqz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.haohaochexian.top/Article/details/gtryvdenka.html

[Q72] 查看索引
来源：http://dali.xziqi.cn/Article/details/gtbfpwpbjv.html

SHOW INDEX FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtsczgoxzm.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gtoynxtxea.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yongpay.top/Article/details/gtnczkujzq.html

[Q74] 强制使用索引
来源：http://dali.yuxming.cn/Article/details/gtybomkzjv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenzaomai.com/Article/details/gtkiaazpco.html

[Q75] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gtpmoktkzd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtpbgqnoye.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shuidangran.top/Article/details/gtjdamsbte.html

[Q76] 按天统计
来源：http://dali.tianlin.xyz/Article/details/gtokesdabn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj202588.top/Article/details/gtiiahhygl.html

[Q77] 时间加减
来源：http://dali.9152youxi.cn/Article/details/gtqlrqrriz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shuidangran.top/Article/details/gtikzcyfxu.html

[Q78] 当前时间
来源：http://dali.aizwys.cn/Article/details/gttjoentwq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.redwolf501.top/Article/details/gtqoekmprw.html

[Q79] 字符串拼接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdonczmq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tianlin.xyz/Article/details/gtrybmybul.html

[Q80] 字符串截取
来源：http://dali.cashguo.top/Article/details/gtybegvqmp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtuvecqwhp.html

[Q81] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gtgjatjizb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.smart0.xyz/Article/details/gtkashyhmg.html

[Q82] 字符长度与字节长度
来源：http://dali.ppjwa.cn/Article/details/gtfsftszot.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlwrdgcb.html

[Q83] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gtuzpdxtzo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtdksznubv.html

[Q84] 去除首尾空格
来源：http://dali.smart0.xyz/Article/details/gtlywgmddr.html

SELECT TRIM(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gtswuoqaad.html

[Q85] 数值取整
来源：http://dali.gaohongyu789.top/Article/details/gttinjcphz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cdnleiting.top/Article/details/gtylcehghk.html

[Q86] 读取 JSON 字段
来源：http://dali.aibaodan.cn/Article/details/gtravpmufa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sweek.top/Article/details/gtwvndeatr.html

[Q87] JSON 字段做条件
来源：http://dali.yuanzhike.top/Article/details/gtiayplklc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinqigfzy.top/Article/details/gtvdvbnejv.html

[Q88] 行转列（条件聚合）
来源：http://dali.gogol.net.cn/Article/details/gtnlvvloxz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.aizwys.cn/Article/details/gtlhwzbbok.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.redwolf501.top/Article/details/gtskrtxpyv.html

[Q89] 判断表是否存在
来源：http://dali.cashguo.top/Article/details/gtmcbesnnv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangdashe.top/Article/details/gtfsigbufu.html

[Q90] 生成序号列
来源：http://dali.jlsjyb.cn/Article/details/gtwymxuesa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tianlin.xyz/Article/details/gttdkfavpr.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcyrlevyv.html

R. Bash 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvktqptlz.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtkrycklir.html

[R01] shebang 与严格模式
来源：http://dali.yanxiufei.cn/Article/details/gthngehcfm.html

#!/usr/bin/env bash
来源：http://dali.fzhhl.top/Article/details/gtnejqhkrn.html

set -euo pipefail
来源：http://dali.aibaodan.cn/Article/details/gtcaduxivm.html

[R02] 变量赋值与使用
来源：http://dali.cqqwz.cn/Article/details/gtoiuktviw.html

name="Tom"; echo "$name"
来源：http://dali.c1oappe.top/Article/details/gtrrryozhy.html

[R03] 只读变量
来源：http://dali.ivvv.top/Article/details/gtmbavrlvo.html

readonly PI=3.14
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbegusfd.html

[R04] 位置参数
来源：http://dali.smart0.xyz/Article/details/gtuvkjrhrz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hfpthk.cn/Article/details/gtnzhinzyb.html

[R05] 参数默认值
来源：http://dali.wangdashe.top/Article/details/gtsdruvyge.html

name="${1:-default}"
来源：http://dali.nanxinkj.top/Article/details/gthmoyvhar.html

[R06] 判断命令是否存在
来源：http://dali.ydzc1.top/Article/details/gtxhalhqds.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnqzz.top/Article/details/gtmssntlzr.html

[R07] if 判断文件
来源：http://dali.xuanzx.com/Article/details/gtjcmzljiy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.quarkkingdee.top/Article/details/gtdwthslsv.html

[R08] 数值比较
来源：http://dali.haohaochexian.top/Article/details/gttobvcuxn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.mhx1999.top/Article/details/gtubypvdfb.html

[R09] 字符串比较
来源：http://dali.ppjwa.cn/Article/details/gttwblymlm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtibtummcg.html

[R10] 正则匹配
来源：http://dali.jinqigfzy.top/Article/details/gtyqxulwcv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtrcangpzh.html

[R11] case 多分支
来源：http://dali.gogol.net.cn/Article/details/gthsazkado.html

case "$1" in
来源：http://dali.gaohongyu789.top/Article/details/gtilfbdjok.html

start) echo "启动" ;;
来源：http://dali.ydzc1.top/Article/details/gtxemfbcxn.html

stop)  echo "停止" ;;
来源：http://dali.gaohongyu789.top/Article/details/gtwyvozxpf.html

*)     echo "未知命令" ;;
来源：http://dali.dashuyun.cn/Article/details/gtyivtsswu.html

esac
来源：http://dali.bjfxy.top/Article/details/gthctuaipp.html

[R12] for 遍历文件
来源：http://dali.c1oappe.top/Article/details/gtedkrodzj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtjefkstyn.html

[R13] for 计数循环
来源：http://dali.chenjidiqi.icu/Article/details/gtgtmscvac.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gtsyiawfti.html

[R14] C 风格 for
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfvnskxsv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gtftjtbpda.html

[R15] while 逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtflxweefy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gzhubu.top/Article/details/gtnimdeouf.html

[R16] until 等待条件
来源：http://dali.redwolf501.top/Article/details/gtkjyngvup.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.kuanghao11.cn/Article/details/gtgpalyygc.html

[R17] 数组定义与取值
来源：http://dali.fzhhl.top/Article/details/gtsrwviggn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.redwolf501.top/Article/details/gttmyemwon.html

[R18] 遍历数组
来源：http://dali.chenzaomai.com/Article/details/gtfkzcjwyw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ehwqpu.com/Article/details/gtyqivyohi.html

[R19] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gtriysglda.html

echo "${#arr[@]}"
来源：http://dali.jlsjyb.cn/Article/details/gtmsnngyfg.html

[R20] 关联数组（字典）
来源：http://dali.daxiang520.top/Article/details/gtoaiiddca.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gteyyvgpwk.html

[R21] 字符串长度
来源：http://dali.hfpthk.cn/Article/details/gtzpgihond.html

echo "${#s}"
来源：http://dali.yangfankeji.com/Article/details/gtgnpdndzk.html

[R22] 截取子串
来源：http://dali.cdnleiting.top/Article/details/gtkncychtj.html

echo "${s:0:5}"
来源：http://dali.kuanghao11.cn/Article/details/gtcbpczlyu.html

[R23] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gtzsctkcax.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.c1oappe.top/Article/details/gtrhpdbiyf.html

[R24] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gtxqmulrfp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guannengcc.top/Article/details/gtlxwelkpa.html

[R25] 去后缀 / 去前缀
来源：http://dali.hammf.cn/Article/details/gtjrvzcggk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yonumen.top/Article/details/gtgvuznnab.html

[R26] 命令替换
来源：http://dali.snrcjt.cn/Article/details/gtaweqodmp.html

now=$(date +%F); echo "$now"
来源：http://dali.redwolf501.top/Article/details/gtqppzkwmp.html

[R27] 算术展开
来源：http://dali.cashguo.top/Article/details/gtottqaavz.html

echo $((1 + 2 * 3))
来源：http://dali.c1oappe.top/Article/details/gtcsktgeqt.html

[R28] 浮点运算
来源：http://dali.yj20258.top/Article/details/gtazitdqwp.html

echo "scale=2; 10/3" | bc
来源：http://dali.jiagoushi.top/Article/details/gthqqmiabd.html

[R29] 定义函数
来源：http://dali.daria6918.cn/Article/details/gtfjeqztye.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.quarkkingdee.top/Article/details/gtdudrlmtb.html

[R30] 函数返回状态码
来源：http://dali.hywenlv.cn/Article/details/gtlwezuxxp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigfzy.top/Article/details/gtmgcmmcfg.html

[R31] 局部变量
来源：http://dali.nanxuanxn.top/Article/details/gtrwwjrxcf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gteyulqnsx.html

[R32] 参数个数校验
来源：http://dali.snrcjt.cn/Article/details/gtqyypevlq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjeepgksc.html

[R33] 捕获错误并提示行号
来源：http://dali.tianlin.xyz/Article/details/gtspbdmjcn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhixingplan.top/Article/details/gthsrxtdrg.html

[R34] 退出时清理
来源：http://dali.andypj.xyz/Article/details/gtdbtdnvio.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gtcxuhtrge.html

[R35] 后台执行并等待
来源：http://dali.jqgufenzy.top/Article/details/gttgdwofbl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tanke756.top/Article/details/gtkqkunmnc.html

[R36] 并发执行多个任务
来源：http://dali.nanxuanxn.top/Article/details/gtvbnibmyz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shzxlz.cn/Article/details/gtmzlhxawz.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtxuzfjtur.html

files=$(ls -1)
来源：http://dali.tian-w.cn/Article/details/gttcffogcw.html

[R38] 管道串联
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbybjwqjy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nwbrower.top/Article/details/gtafmylzlp.html

[R39] 重定向标准输出与错误
来源：http://dali.jqgufenzy.top/Article/details/gtdctoqcck.html

cmd > out.log 2>&1
来源：http://dali.cqqwz.cn/Article/details/gtjferbnqa.html

[R40] 追加写日志
来源：http://dali.hysaishi.cn/Article/details/gtqupmuxig.html

echo "log" >> out.log
来源：http://dali.andypj.xyz/Article/details/gtikrgilew.html

[R41] 丢弃输出
来源：http://dali.wangdashe.top/Article/details/gtvgehvjbe.html

cmd >/dev/null 2>&1
来源：http://dali.cucudq.cn/Article/details/gtxltwcbry.html

[R42] 输入重定向
来源：http://dali.jinqigfzy.top/Article/details/gtpesmepzq.html

wc -l < a.txt
来源：http://dali.316326.xyz/Article/details/gtywiqldwk.html

[R43] 按名字查找文件
来源：http://dali.ydzc1.top/Article/details/gtoehaewku.html

find . -name "*.log" -type f
来源：http://dali.jqgfzy.top/Article/details/gtozsbufsl.html

[R44] 按修改时间查找
来源：http://dali.birdmap.top/Article/details/gtwdaqkgdy.html

find . -mtime -7 -type f
来源：http://dali.vqdsnc.cn/Article/details/gtmxkzxxtz.html

[R45] 批量删除
来源：http://dali.ppjwa.cn/Article/details/gtmztwisom.html

find . -name "*.tmp" -delete
来源：http://dali.wangshuangyany.cn/Article/details/gtzmvyxett.html

[R46] 递归替换文件内容
来源：http://dali.zhixingplan.top/Article/details/gtdhpweioe.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ppjwa.cn/Article/details/gtebbxhsyn.html

[R47] sed 单行替换
来源：http://dali.haohaochexian.top/Article/details/gtxmnzdizk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ybcxt.top/Article/details/gtmhoniuga.html

[R48] awk 取指定列
来源：http://dali.gogol.net.cn/Article/details/gtwefjzxkt.html

awk '{print $1, $3}' a.txt
来源：http://dali.hywenlv.cn/Article/details/gtjewrxxhn.html

[R49] awk 带条件
来源：http://dali.jqgufenzy.top/Article/details/gtfjglvqoi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zdqjudy.top/Article/details/gtvbftrlyh.html

[R50] awk 求和
来源：http://dali.haohaochexian.top/Article/details/gtbhjigfcq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtimfoxdcd.html

[R51] 排序去重取前几
来源：http://dali.havefunace.top/Article/details/gthvjkojdh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yueranfly.top/Article/details/gtdzzklvul.html

[R52] 统计行数
来源：http://dali.gaohongyu789.top/Article/details/gtzhehzucy.html

wc -l a.txt
来源：http://dali.ehwqpu.com/Article/details/gtequptnmd.html

[R53] 查看文件头与实时尾
来源：http://dali.yuanzhike.top/Article/details/gtzzjjfgxo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cucudq.cn/Article/details/gtwgweybri.html

[R54] 比较两个文件
来源：http://dali.birdmap.top/Article/details/gtwmjfidmz.html

diff a.txt b.txt
来源：http://dali.xylfe.cn/Article/details/gtbbshmgxu.html

[R55] 压缩与解压
来源：http://dali.hnxiangtu.top/Article/details/gtnxtuudle.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sufxvd.cn/Article/details/gthekbymcy.html

[R56] 远程拷贝
来源：http://dali.cashguo.top/Article/details/gthvoxhwhd.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gteukbjosr.html

[R57] 远程执行命令
来源：http://dali.hnqzz.top/Article/details/gtjwpuoqzf.html

ssh user@host 'uptime'
来源：http://dali.vqdsnc.cn/Article/details/gtleqehabd.html

[R58] 下载文件
来源：http://dali.zhongyouzk.top/Article/details/gtjwrsbhqk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.guowangkeji.top/Article/details/gtqbhzujzz.html

[R59] 发 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gtlmhsfbnj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenjidiqi.icu/Article/details/gtrukizeeq.html

[R60] 只看 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gtgmuourut.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj20258.top/Article/details/gtckdvjhqr.html

[R61] 磁盘占用
来源：http://dali.ybcxt.top/Article/details/gtboehylax.html

df -h;  du -sh *
来源：http://dali.gzhubu.top/Article/details/gtdgwgvdjz.html

[R62] 找最占空间的文件
来源：http://dali.xuanzx.com/Article/details/gtraieokzz.html

du -ah . | sort -rh | head -10
来源：http://dali.svipenyu.cn/Article/details/gtyhvnwhkg.html

[R63] 内存与进程
来源：http://dali.yonumen.top/Article/details/gtudulwfqx.html


<!-- 参考信息 -->