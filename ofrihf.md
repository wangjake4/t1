代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gogol.net.cn/Article/details/gtzuhxrazj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuanzhike.top/Article/details/gtjsliuakl.html

[Q13] 忽略重复插入
来源：http://dali.xuanzx.com/Article/details/gtgrjrwfsg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.aizwys.cn/Article/details/gtkadgdeiz.html

[Q14] 存在则更新（upsert）
来源：http://dali.snrcjt.cn/Article/details/gtxmqtkwsa.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yangfankeji.com/Article/details/gtrnmyykvg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhiwuduotai.top/Article/details/gtesbdrhex.html

[Q15] 查询全部
来源：http://dali.sysykeji.top/Article/details/gtzsdnwtqh.html

SELECT * FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtxmaxrgjy.html

[Q16] 查询指定列
来源：http://dali.jinqigfzy.top/Article/details/gtdmjomjab.html

SELECT id, name FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtctsqhheu.html

[Q17] 条件查询
来源：http://dali.jinqigfzy.top/Article/details/gtvgxbrpbf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhoulong.xyz/Article/details/gthnjdvrey.html

[Q18] 模糊匹配
来源：http://dali.gogol.net.cn/Article/details/gtzftywjlk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cqqwz.cn/Article/details/gtmxntfwal.html

[Q19] 范围查询
来源：http://dali.xuanzx.com/Article/details/gthiumhjmn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jyoumei.cn/Article/details/gtfzpejomv.html

[Q20] IN 列表
来源：http://dali.yongpay.top/Article/details/gtfuersueb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.bjfxy.top/Article/details/gtqhxwxzxw.html

[Q21] 空值判断
来源：http://dali.sufxvd.cn/Article/details/gtobmsewsf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.c1oappe.top/Article/details/gttvkplddj.html

[Q22] 排序
来源：http://dali.yongpay.top/Article/details/gtoknalfur.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tanke756.top/Article/details/gtjgeuqerv.html

[Q23] 分页
来源：http://dali.yonumen.top/Article/details/gtkmccajmw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.havefunace.top/Article/details/gtxpqthrdv.html

[Q24] 去重
来源：http://dali.chenjidiqi.icu/Article/details/gtkqqduyun.html

SELECT DISTINCT city FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtepyonszr.html

[Q25] 只取前 N 条
来源：http://dali.xuetiantiany.cn/Article/details/gtoefuuxmw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.9152youxi.cn/Article/details/gtgkwmsmee.html

[Q26] 计数
来源：http://dali.pycfn.com/Article/details/gtvtlivaqm.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtusbswggf.html

[Q27] 条件计数
来源：http://dali.yanxiufei.cn/Article/details/gtlecowvab.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yvedp.cn/Article/details/gtvvsyhzgl.html

[Q28] 求和与平均
来源：http://dali.chenzaomai.com/Article/details/gtmwckbvsh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtzmzdjpph.html

[Q29] 最大最小值
来源：http://dali.gzhubu.top/Article/details/gtupflglnc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtyyqmmjtr.html

[Q30] 分组统计
来源：http://dali.feifeiyinyue.top/Article/details/gtgedrqjmm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtzogmgyse.html

[Q31] 分组后过滤
来源：http://dali.yueranfly.top/Article/details/gtolaeokws.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sweek.top/Article/details/gthovdwfit.html

[Q32] 分组拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtrtdwgtid.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gtrivuvwpr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gtorsehirh.html

[Q33] 多列分组
来源：http://dali.cqqwz.cn/Article/details/gtxdzlffpm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.guannengcc.top/Article/details/gtvotcblus.html

[Q34] 每组取第一条
来源：http://dali.zdqjudy.top/Article/details/gtjateqkev.html

SELECT * FROM (
来源：http://dali.cashguo.top/Article/details/gtfgqmbllm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yanxiufei.cn/Article/details/gtctccskyc.html

) t WHERE rn = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtlwqjcevf.html

[Q35] 内连接
来源：http://dali.birdmap.top/Article/details/gtgftotsej.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hammf.cn/Article/details/gtjqhwtptc.html

[Q36] 左连接
来源：http://dali.gaohongyu789.top/Article/details/gtjvaqwjhz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sysykeji.top/Article/details/gtvqngglvv.html

[Q37] 右连接
来源：http://dali.tanke756.top/Article/details/gtsumclkfc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hywenlv.cn/Article/details/gtaefvyjew.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nwbrower.top/Article/details/gtmhlyjyan.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlyitqupk.html

[Q39] 自连接（查上下级）
来源：http://dali.hongshengwenyu.top/Article/details/gtrbybbclz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenjidiqi.icu/Article/details/gtjoaxnssd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nanxuanxn.top/Article/details/gtntqcjouh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenzaomai.com/Article/details/gtiahwdibf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xuetiantiany.cn/Article/details/gtxunnjevx.html

[Q41] 多表连接
来源：http://dali.jinqigfzy.top/Article/details/gtgvyljxdx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gotoacloud.top/Article/details/gtcpgifyyc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ybcxt.top/Article/details/gtnndpwmkr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.wangshuangyany.cn/Article/details/gtmiktbjux.html

[Q42] 连接条件附加过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtrolzpjnf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ivvv.top/Article/details/gtgtytvwsw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sweek.top/Article/details/gteipidvbl.html

[Q43] 标量子查询
来源：http://dali.chenlongwang.top/Article/details/gtofnjcolk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yj202588.top/Article/details/gtxfaqqqvv.html

[Q44] IN 子查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwbevdzj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.haohaochexian.top/Article/details/gtspqqwnar.html

[Q45] EXISTS 判断存在
来源：http://dali.jiagoushi.top/Article/details/gtgsonfqah.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gtcxbwlgno.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gzhubu.top/Article/details/gtdkxoxhof.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yanxiufei.cn/Article/details/gtqeojsqgm.html

[Q47] 与平均值比较
来源：http://dali.feifeiyinyue.top/Article/details/gtcaldboxv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdfteccd.html

[Q48] CTE 公用表表达式
来源：http://dali.c1oappe.top/Article/details/gtvdlhgdjm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenzaomai.com/Article/details/gtozfwrhhc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgufenzy.top/Article/details/gtudhidqpf.html

[Q49] 更新单行
来源：http://dali.aibaodan.cn/Article/details/gtlwbepjfg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gtdtfcovzo.html

[Q50] 批量更新
来源：http://dali.316326.xyz/Article/details/gtvkzhkjla.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yvedp.cn/Article/details/gtnhkulpeh.html

[Q51] 用子查询更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkhvgyyq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtjhygebyd.html

[Q52] 删除指定行
来源：http://dali.pycfn.com/Article/details/gtfkqazxih.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtggukxmvc.html

[Q53] 按条件删除
来源：http://dali.haohaochexian.top/Article/details/gtllpwmtlb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.iojbl.cn/Article/details/gtdplcewst.html

[Q54] 清空表
来源：http://dali.mhx1999.top/Article/details/gtslgkqnqr.html

TRUNCATE TABLE logs;
来源：http://dali.yongpay.top/Article/details/gttbwbskxu.html

[Q55] 排名（并列占位）
来源：http://dali.fzhhl.top/Article/details/gtrhinsqtz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.wangshuangyany.cn/Article/details/gtqkegbeor.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj20258.top/Article/details/gtgchbzxnl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tanke756.top/Article/details/gtbzdndsfb.html

[Q57] 行号
来源：http://dali.hfpthk.cn/Article/details/gtbcjwtdpm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtzkfmsblt.html

[Q58] 累计求和
来源：http://dali.yonumen.top/Article/details/gtummcojwd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.havefunace.top/Article/details/gtinrxhilz.html

[Q59] 分组内累计
来源：http://dali.yueranfly.top/Article/details/gtuuupqqia.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtouxumnhu.html

[Q60] 取上一行 / 下一行
来源：http://dali.jianghu66.top/Article/details/gtchvkbogx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hysaishi.cn/Article/details/gtpqayoxet.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yonumen.top/Article/details/gtpzjlglpi.html

[Q61] 移动平均
来源：http://dali.fzhhl.top/Article/details/gtddmtxzyv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtzpdpwljq.html

[Q62] 分组占比
来源：http://dali.hnqzz.top/Article/details/gtwzgemulb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtkbanzkcc.html

[Q63] 开启事务
来源：http://dali.jinqigufen.top/Article/details/gthrqkyjve.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigfzy.top/Article/details/gtnleubffe.html

[Q64] 提交事务
来源：http://dali.nanxuanxn.top/Article/details/gttlbawaqm.html

COMMIT;
来源：http://dali.yj202588.top/Article/details/gtyrpilvtd.html

[Q65] 回滚事务
来源：http://dali.feifeiyinyue.top/Article/details/gtjencpyix.html

ROLLBACK;
来源：http://dali.ppjwa.cn/Article/details/gthrzypirl.html

[Q66] 行锁查询
来源：http://dali.dashuyun.cn/Article/details/gtijttqmde.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nwbrower.top/Article/details/gtrnzjqftv.html

[Q67] 设置隔离级别
来源：http://dali.gogol.net.cn/Article/details/gtsojymwae.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yuanzhike.top/Article/details/gtpijcrwum.html

[Q68] 保存点
来源：http://dali.wangshuangyany.cn/Article/details/gtwupwmdre.html

SAVEPOINT sp1;
来源：http://dali.smart0.xyz/Article/details/gttrfrjhar.html

ROLLBACK TO sp1;
来源：http://dali.gogol.net.cn/Article/details/gtxbdtlrnv.html

[Q69] 查看执行计划
来源：http://dali.nanxuanxn.top/Article/details/gtylzybaux.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlzqvywkv.html

[Q70] 更新统计信息
来源：http://dali.vqdsnc.cn/Article/details/gtutgieocm.html

ANALYZE TABLE users;
来源：http://dali.jqgufenzy.top/Article/details/gtuwhudmwl.html

[Q71] 查看建表语句
来源：http://dali.jinqigfzy.top/Article/details/gtqqlycimt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yonumen.top/Article/details/gtnvkffgvr.html

[Q72] 查看索引
来源：http://dali.nanxinkj.top/Article/details/gtnwckupvr.html

SHOW INDEX FROM users;
来源：http://dali.gogol.net.cn/Article/details/gthsubkrpa.html

[Q73] 查看表状态
来源：http://dali.yvedp.cn/Article/details/gtmsqrplna.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwjhmocx.html

[Q74] 强制使用索引
来源：http://dali.gaohongyu789.top/Article/details/gtopeojelv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hywenlv.cn/Article/details/gtrmtdiwpw.html

[Q75] 日期格式化
来源：http://dali.birdmap.top/Article/details/gtaskazvpg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtcbmionuf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhengqikj.top/Article/details/gtfocfnypr.html

[Q76] 按天统计
来源：http://dali.cqqwz.cn/Article/details/gtmnhhakkx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.meibo888.top/Article/details/gteqjlttfy.html

[Q77] 时间加减
来源：http://dali.0kj1m.cn/Article/details/gtvcrhmogx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj20258.top/Article/details/gtgqvhxsos.html

[Q78] 当前时间
来源：http://dali.chenjidiqi.icu/Article/details/gttvttzxlv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.svipenyu.cn/Article/details/gtxkghyjib.html

[Q79] 字符串拼接
来源：http://dali.tian-w.cn/Article/details/gttuvkxjvw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jyoumei.cn/Article/details/gtfnrfmbwb.html

[Q80] 字符串截取
来源：http://dali.daxiang520.top/Article/details/gtblqbanba.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtaxmxeqka.html

[Q81] 字符串替换
来源：http://dali.ivvv.top/Article/details/gtbbwqdbck.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nwbrower.top/Article/details/gtcwovwtws.html

[Q82] 字符长度与字节长度
来源：http://dali.sufxvd.cn/Article/details/gtvaxsbaoq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtwsntxzlp.html

[Q83] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gthkmmppys.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtvixkwreq.html

[Q84] 去除首尾空格
来源：http://dali.wangshuangyany.cn/Article/details/gtwozydhle.html

SELECT TRIM(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtdosotnit.html

[Q85] 数值取整
来源：http://dali.gaohongyu789.top/Article/details/gtlsjufqcb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shangyingyoupin.top/Article/details/gtrofcgkpm.html

[Q86] 读取 JSON 字段
来源：http://dali.jyoumei.cn/Article/details/gtyjbqdfsa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinghuilouyu.cn/Article/details/gtonidcqzi.html

[Q87] JSON 字段做条件
来源：http://dali.tianlin.xyz/Article/details/gtqebwuvps.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aizwys.cn/Article/details/gtbyetvbzp.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinqigfzy.top/Article/details/gtvmofaufn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.bjfxy.top/Article/details/gttbsofonp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtwiulngnr.html

[Q89] 判断表是否存在
来源：http://dali.ppjwa.cn/Article/details/gtsiclrpbc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sxryk.cn/Article/details/gtelbbkydi.html

[Q90] 生成序号列
来源：http://dali.yuanzhike.top/Article/details/gtekldupri.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenzaomai.com/Article/details/gtyjhpuseg.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtzrvicmia.html

R. Bash 专题
来源：http://dali.hongshengwenyu.top/Article/details/gtbtawftid.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtsyrsgtjs.html

[R01] shebang 与严格模式
来源：http://dali.0kj1m.cn/Article/details/gtarksbkou.html

#!/usr/bin/env bash
来源：http://dali.kuanghao11.cn/Article/details/gtbwpoluic.html

set -euo pipefail
来源：http://dali.0kj1m.cn/Article/details/gtfvksluro.html

[R02] 变量赋值与使用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtauzesvkr.html

name="Tom"; echo "$name"
来源：http://dali.zycfv.cn/Article/details/gtfabgjpki.html

[R03] 只读变量
来源：http://dali.jqgfzy.top/Article/details/gthgdrhros.html

readonly PI=3.14
来源：http://dali.andypj.xyz/Article/details/gtnytovvuc.html

[R04] 位置参数
来源：http://dali.hfpthk.cn/Article/details/gtalywskzz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sufxvd.cn/Article/details/gttgnqzkow.html

[R05] 参数默认值
来源：http://dali.cdnleiting.top/Article/details/gtplfpfvgx.html

name="${1:-default}"
来源：http://dali.yangfankeji.com/Article/details/gtqggpfrrp.html

[R06] 判断命令是否存在
来源：http://dali.ppjwa.cn/Article/details/gtcggwqqda.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbekwbeyz.html

[R07] if 判断文件
来源：http://dali.ybcxt.top/Article/details/gtbuxtello.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.aibaodan.cn/Article/details/gtqdggripd.html

[R08] 数值比较
来源：http://dali.zdqjudy.top/Article/details/gtvhwhjsjz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtglqklvjz.html

[R09] 字符串比较
来源：http://dali.wangdashe.top/Article/details/gtihjumbkk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ppjwa.cn/Article/details/gtmqvybkhz.html

[R10] 正则匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtfqsaoxtg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hysaishi.cn/Article/details/gtoizxwtmk.html

[R11] case 多分支
来源：http://dali.jiagoushi.top/Article/details/gtihmhgrkm.html

case "$1" in
来源：http://dali.daria6918.cn/Article/details/gtwbtooqua.html

start) echo "启动" ;;
来源：http://dali.cucudq.cn/Article/details/gtjilpasyd.html

stop)  echo "停止" ;;
来源：http://dali.jqgfzy.top/Article/details/gtztuchiue.html

*)     echo "未知命令" ;;
来源：http://dali.bjfxy.top/Article/details/gtvmnpciwe.html

esac
来源：http://dali.ydzc1.top/Article/details/gtkivvgxre.html

[R12] for 遍历文件
来源：http://dali.tanke756.top/Article/details/gtxrohjjiu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yonumen.top/Article/details/gtcpfcncjv.html

[R13] for 计数循环
来源：http://dali.yvedp.cn/Article/details/gtrtoovpai.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gtomglvodu.html

[R14] C 风格 for
来源：http://dali.chenlongwang.top/Article/details/gthzjqyrci.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gogol.net.cn/Article/details/gthkokineh.html

[R15] while 逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtlssrvfsr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.guannengcc.top/Article/details/gtkhkesugq.html

[R16] until 等待条件
来源：http://dali.gotoacloud.top/Article/details/gtxeudbktg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.andypj.xyz/Article/details/gthzthsoda.html

[R17] 数组定义与取值
来源：http://dali.daxiang520.top/Article/details/gtfiklcmrr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.dashuyun.cn/Article/details/gteshuqwxo.html

[R18] 遍历数组
来源：http://dali.shzxlz.cn/Article/details/gtcbyjmbsk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gaohongyu789.top/Article/details/gtqkosdtyn.html

[R19] 数组长度
来源：http://dali.zhiwuduotai.top/Article/details/gthpxrhlkc.html

echo "${#arr[@]}"
来源：http://dali.nanxinkj.top/Article/details/gthgrlvhwd.html

[R20] 关联数组（字典）
来源：http://dali.feifeiyinyue.top/Article/details/gtwwzxhzog.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ydzc1.top/Article/details/gtybjecqow.html

[R21] 字符串长度
来源：http://dali.ehwqpu.com/Article/details/gteyvlveka.html

echo "${#s}"
来源：http://dali.316326.xyz/Article/details/gtnnhyqsen.html

[R22] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gtgiehwxed.html

echo "${s:0:5}"
来源：http://dali.havefunace.top/Article/details/gtvbaigtrj.html

[R23] 字符串替换
来源：http://dali.daxiang520.top/Article/details/gtrklzcbze.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.snrcjt.cn/Article/details/gtafslfamm.html

[R24] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gtvhrmbmig.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.vqdsnc.cn/Article/details/gteebrjysk.html

[R25] 去后缀 / 去前缀
来源：http://dali.xinyue.icu/Article/details/gtiaaevnmc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jyoumei.cn/Article/details/gtwvbgcqjk.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gtghsosbjs.html

now=$(date +%F); echo "$now"
来源：http://dali.guannengcc.top/Article/details/gtvmrtbpbp.html

[R27] 算术展开
来源：http://dali.ppjwa.cn/Article/details/gttlgnrnsc.html

echo $((1 + 2 * 3))
来源：http://dali.hnxiangtu.top/Article/details/gtysanrxii.html

[R28] 浮点运算
来源：http://dali.tianlin.xyz/Article/details/gtqdltqymm.html

echo "scale=2; 10/3" | bc
来源：http://dali.yanxiufei.cn/Article/details/gtgtyuvdnd.html

[R29] 定义函数
来源：http://dali.xinyue.icu/Article/details/gtjnxvlero.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sweek.top/Article/details/gtzduufked.html

[R30] 函数返回状态码
来源：http://dali.dianchejie.cn/Article/details/gtskjulvew.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hnqzz.top/Article/details/gtpmaglwgc.html

[R31] 局部变量
来源：http://dali.jqgufenzy.top/Article/details/gtvasyvrcq.html

f() { local x=1; echo "$x"; }
来源：http://dali.c1oappe.top/Article/details/gtfvppzojc.html

[R32] 参数个数校验
来源：http://dali.guowangkeji.top/Article/details/gtwyktrxpq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.guannengcc.top/Article/details/gtpjlshklf.html

[R33] 捕获错误并提示行号
来源：http://dali.guannengcc.top/Article/details/gtbrsjvzoe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.316326.xyz/Article/details/gtkydysbki.html

[R34] 退出时清理
来源：http://dali.cheryme.top/Article/details/gtsaiozzlj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gtivqtulri.html

[R35] 后台执行并等待
来源：http://dali.zhiwuduotai.top/Article/details/gtrwwogywb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sweek.top/Article/details/gtcryrgrau.html

[R36] 并发执行多个任务
来源：http://dali.tianlin.xyz/Article/details/gtjcuirikl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tianlin.xyz/Article/details/gtnmveifda.html

[R37] 把输出赋给变量
来源：http://dali.jinqigufen.top/Article/details/gtmfdotyqe.html

files=$(ls -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteutwgouu.html

[R38] 管道串联
来源：http://dali.guannengcc.top/Article/details/gtetaklkny.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sysykeji.top/Article/details/gtnjferuzo.html

[R39] 重定向标准输出与错误
来源：http://dali.hongshengwenyu.top/Article/details/gtuuoagsyn.html

cmd > out.log 2>&1
来源：http://dali.0kj1m.cn/Article/details/gtjpzmdpon.html

[R40] 追加写日志
来源：http://dali.shangyingyoupin.top/Article/details/gtmagjhznt.html

echo "log" >> out.log
来源：http://dali.jyoumei.cn/Article/details/gtqvlgnisf.html

[R41] 丢弃输出
来源：http://dali.fzhhl.top/Article/details/gttwwtidbt.html

cmd >/dev/null 2>&1
来源：http://dali.yvedp.cn/Article/details/gtgqpjiicp.html

[R42] 输入重定向
来源：http://dali.316326.xyz/Article/details/gtxdpzkkky.html

wc -l < a.txt
来源：http://dali.bjfxy.top/Article/details/gtwdmecfcz.html

[R43] 按名字查找文件
来源：http://dali.snrcjt.cn/Article/details/gtatyussfv.html

find . -name "*.log" -type f
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzldinxk.html

[R44] 按修改时间查找
来源：http://dali.xuanzx.com/Article/details/gtnhriruvx.html

find . -mtime -7 -type f
来源：http://dali.meibo888.top/Article/details/gtifytsmnp.html

[R45] 批量删除
来源：http://dali.yvedp.cn/Article/details/gtjbpnbeoo.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfcxjlky.html

[R46] 递归替换文件内容
来源：http://dali.yuxming.cn/Article/details/gtleupdyxq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yanxiufei.cn/Article/details/gtxrrxmasm.html

[R47] sed 单行替换
来源：http://dali.hywenlv.cn/Article/details/gtgzjkyunz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shuidangran.top/Article/details/gtrllypiiu.html

[R48] awk 取指定列
来源：http://dali.xuanzx.com/Article/details/gtfvgcahqx.html

awk '{print $1, $3}' a.txt
来源：http://dali.cucudq.cn/Article/details/gtfeiybrkv.html

[R49] awk 带条件
来源：http://dali.yanxiufei.cn/Article/details/gtxqeqkffq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.redwolf501.top/Article/details/gtazeobkwo.html

[R50] awk 求和
来源：http://dali.yuxming.cn/Article/details/gtczijwycd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.316326.xyz/Article/details/gtzqvqxtxs.html

[R51] 排序去重取前几
来源：http://dali.meibo888.top/Article/details/gtndywooys.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ybcxt.top/Article/details/gtybzwntcr.html

[R52] 统计行数
来源：http://dali.yj20258.top/Article/details/gtquryrjqo.html

wc -l a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtbhlyuahq.html

[R53] 查看文件头与实时尾
来源：http://dali.nwbrower.top/Article/details/gtmwhiviax.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xylfe.cn/Article/details/gtrtcyxkbs.html

[R54] 比较两个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlzgxxype.html

diff a.txt b.txt
来源：http://dali.birdmap.top/Article/details/gttzsipahu.html

[R55] 压缩与解压
来源：http://dali.xinyue.icu/Article/details/gtoyqrncye.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.feifeiyinyue.top/Article/details/gtzhyongal.html

[R56] 远程拷贝
来源：http://dali.9152youxi.cn/Article/details/gtomiztihd.html

scp file user@host:/path/
来源：http://dali.wangdashe.top/Article/details/gtexrhupxh.html

[R57] 远程执行命令
来源：http://dali.hammf.cn/Article/details/gtckeudyyr.html

ssh user@host 'uptime'
来源：http://dali.yongpay.top/Article/details/gtegdzxebc.html

[R58] 下载文件
来源：http://dali.bjfxy.top/Article/details/gtqxqiigsd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hammf.cn/Article/details/gtkstaglbe.html

[R59] 发 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwaxslse.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gthazuqlro.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gtgweljzsj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.vqdsnc.cn/Article/details/gtehxzzthj.html

[R61] 磁盘占用
来源：http://dali.nanxuanxn.top/Article/details/gtfdzrazyf.html


<!-- 参考信息 -->