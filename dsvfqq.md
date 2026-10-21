代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shuidangran.top/Article/details/gtcpnthejs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.vqdsnc.cn/Article/details/gtahpilcit.html

[Q13] 忽略重复插入
来源：http://dali.c1oappe.top/Article/details/gtjdnkkgcs.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xuanzx.com/Article/details/gtmzlewrsp.html

[Q14] 存在则更新（upsert）
来源：http://dali.haohaochexian.top/Article/details/gtlgywjqnb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guowangkeji.top/Article/details/gtnguzfkmq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuanzhike.top/Article/details/gtekzgubam.html

[Q15] 查询全部
来源：http://dali.c1oappe.top/Article/details/gtnxkzsisl.html

SELECT * FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtnyoskjat.html

[Q16] 查询指定列
来源：http://dali.daria6918.cn/Article/details/gtlwgefwzm.html

SELECT id, name FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtldkoemca.html

[Q17] 条件查询
来源：http://dali.vqdsnc.cn/Article/details/gtogbmclse.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjanyqsa.html

[Q18] 模糊匹配
来源：http://dali.hfpthk.cn/Article/details/gtoiogcofw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.0kj1m.cn/Article/details/gtizsxpmco.html

[Q19] 范围查询
来源：http://dali.chenjidiqi.icu/Article/details/gtduhiricc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ppjwa.cn/Article/details/gtruerpxvj.html

[Q20] IN 列表
来源：http://dali.sweek.top/Article/details/gtjvwtusle.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinqigfzy.top/Article/details/gtkhidslhj.html

[Q21] 空值判断
来源：http://dali.daxiang520.top/Article/details/gtifaohzug.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.guowangkeji.top/Article/details/gttqltwxuv.html

[Q22] 排序
来源：http://dali.chenlongwang.top/Article/details/gttffozngw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tianlin.xyz/Article/details/gtqssrgtou.html

[Q23] 分页
来源：http://dali.nwbrower.top/Article/details/gtxlkljcyf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yvedp.cn/Article/details/gtbfwjwzof.html

[Q24] 去重
来源：http://dali.ybcxt.top/Article/details/gthkyvxoft.html

SELECT DISTINCT city FROM users;
来源：http://dali.cucudq.cn/Article/details/gtlrsrbfpr.html

[Q25] 只取前 N 条
来源：http://dali.ppjwa.cn/Article/details/gtprvjetyl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gotoacloud.top/Article/details/gtgliaeogf.html

[Q26] 计数
来源：http://dali.zhongyouzk.top/Article/details/gtaajsqmvo.html

SELECT COUNT(*) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtlfkodmhu.html

[Q27] 条件计数
来源：http://dali.yuxming.cn/Article/details/gtknlndgaq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj20258.top/Article/details/gtbovifvhm.html

[Q28] 求和与平均
来源：http://dali.wangshuangyany.cn/Article/details/gttxpnfqbp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuleujhtv.html

[Q29] 最大最小值
来源：http://dali.chenjidiqi.icu/Article/details/gtwfvripyb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtnvopcvzp.html

[Q30] 分组统计
来源：http://dali.ybcxt.top/Article/details/gtebzehftl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gtrylwzlau.html

[Q31] 分组后过滤
来源：http://dali.jlsjyb.cn/Article/details/gtpwyysdmn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.dashuyun.cn/Article/details/gtkvhdfumy.html

[Q32] 分组拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtoqgrficu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gtvzboyqzt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cqqwz.cn/Article/details/gtxgoepycg.html

[Q33] 多列分组
来源：http://dali.nanxinkj.top/Article/details/gtgxfngliu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.guannengcc.top/Article/details/gtqoduknrg.html

[Q34] 每组取第一条
来源：http://dali.birdmap.top/Article/details/gtzbwvverx.html

SELECT * FROM (
来源：http://dali.ivvv.top/Article/details/gtgvptehkc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nanxinkj.top/Article/details/gtqrabdkpz.html

) t WHERE rn = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjxizcdc.html

[Q35] 内连接
来源：http://dali.yvedp.cn/Article/details/gtkfdjeqkp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gtuocjskyz.html

[Q36] 左连接
来源：http://dali.tian-w.cn/Article/details/gtlfimtpqk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gtcmpopegu.html

[Q37] 右连接
来源：http://dali.sysykeji.top/Article/details/gtxhjrzvwm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shuidangran.top/Article/details/gtqkhxpuzn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.fengsongda.top/Article/details/gtfgxakgwc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gogol.net.cn/Article/details/gtcqgopzvx.html

[Q39] 自连接（查上下级）
来源：http://dali.yongpay.top/Article/details/gtkmylpasr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nwbrower.top/Article/details/gtazvfvleo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.c1oappe.top/Article/details/gtluonblrl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhengqikj.top/Article/details/gtdyyemzjn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.kuanghao11.cn/Article/details/gtfyglqtbl.html

[Q41] 多表连接
来源：http://dali.pengpengdd.cyou/Article/details/gtdlncbwqw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daria6918.cn/Article/details/gtoargdcsb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.aibaodan.cn/Article/details/gtigrrcaqj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gzhubu.top/Article/details/gtcptvaqhq.html

[Q42] 连接条件附加过滤
来源：http://dali.vqdsnc.cn/Article/details/gtomiyumaz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.birdmap.top/Article/details/gtrdncawrp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hysaishi.cn/Article/details/gtowkaltcl.html

[Q43] 标量子查询
来源：http://dali.haohaochexian.top/Article/details/gtwmzoelhy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.andypj.xyz/Article/details/gttunonpjh.html

[Q44] IN 子查询
来源：http://dali.yueranfly.top/Article/details/gtmrslzecn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.andypj.xyz/Article/details/gthrlqnpvr.html

[Q45] EXISTS 判断存在
来源：http://dali.gaohongyu789.top/Article/details/gtzpsknlcr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gtmxznzntm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.c1oappe.top/Article/details/gtgybliicz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jlsjyb.cn/Article/details/gtniwewpff.html

[Q47] 与平均值比较
来源：http://dali.hongshengwenyu.top/Article/details/gtuvrxpogj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.dashuyun.cn/Article/details/gtlesqbofy.html

[Q48] CTE 公用表表达式
来源：http://dali.cheryme.top/Article/details/gthdljsakk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.kuanghao11.cn/Article/details/gtkwqpmfnz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xuanzx.com/Article/details/gtutsksgrc.html

[Q49] 更新单行
来源：http://dali.chenjidiqi.icu/Article/details/gtoypkpysr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gtfiihyaet.html

[Q50] 批量更新
来源：http://dali.dianchejie.cn/Article/details/gtbyayzaus.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.haohaochexian.top/Article/details/gtzquceaew.html

[Q51] 用子查询更新
来源：http://dali.shzxlz.cn/Article/details/gtrhxleajv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sxryk.cn/Article/details/gtpewgygid.html

[Q52] 删除指定行
来源：http://dali.jqgfzy.top/Article/details/gtvhxadpaa.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtyqgnscsu.html

[Q53] 按条件删除
来源：http://dali.tanke756.top/Article/details/gtzamkamro.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nwbrower.top/Article/details/gtlxtxpujt.html

[Q54] 清空表
来源：http://dali.hywenlv.cn/Article/details/gtwaurhzpf.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gtxlvybxpr.html

[Q55] 排名（并列占位）
来源：http://dali.sxryk.cn/Article/details/gtwvqfikjn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gtfzfmkrdt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.pengpengdd.cyou/Article/details/gtsgszjsjz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ydzc1.top/Article/details/gtryzzwdla.html

[Q57] 行号
来源：http://dali.gotoacloud.top/Article/details/gtkerhypjr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtxrgfwppr.html

[Q58] 累计求和
来源：http://dali.ehwqpu.com/Article/details/gtvszbxpcj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtjrltfyfn.html

[Q59] 分组内累计
来源：http://dali.chenzaomai.com/Article/details/gtvjdatuaz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtgkywbwye.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj202588.top/Article/details/gtebajwjkc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shuidangran.top/Article/details/gtmbsusnqt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yuxming.cn/Article/details/gteqlgrklm.html

[Q61] 移动平均
来源：http://dali.shangyingyoupin.top/Article/details/gtmmmbxjzv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtpsqbfdyg.html

[Q62] 分组占比
来源：http://dali.shzxlz.cn/Article/details/gtnczjteyw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gtpjrknfkx.html

[Q63] 开启事务
来源：http://dali.cucudq.cn/Article/details/gtzcsfmsgi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgufenzy.top/Article/details/gtnuhbfwex.html

[Q64] 提交事务
来源：http://dali.aizwys.cn/Article/details/gtjccbzwsi.html

COMMIT;
来源：http://dali.xinyue.icu/Article/details/gtnteuvktl.html

[Q65] 回滚事务
来源：http://dali.zdqjudy.top/Article/details/gtppeffquv.html

ROLLBACK;
来源：http://dali.jqgfzy.top/Article/details/gtkzjrunsm.html

[Q66] 行锁查询
来源：http://dali.0kj1m.cn/Article/details/gtkixblvxv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhengqikj.top/Article/details/gtawwwnmiv.html

[Q67] 设置隔离级别
来源：http://dali.xziqi.cn/Article/details/gtvtsrwopg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tian-w.cn/Article/details/gtjzjevdqd.html

[Q68] 保存点
来源：http://dali.zhiwuduotai.top/Article/details/gtahnggqhb.html

SAVEPOINT sp1;
来源：http://dali.zdqjudy.top/Article/details/gtrirbzjry.html

ROLLBACK TO sp1;
来源：http://dali.quarkkingdee.top/Article/details/gtqgtublct.html

[Q69] 查看执行计划
来源：http://dali.jinqigfzy.top/Article/details/gtxsdbtmcn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yangfankeji.com/Article/details/gtslfzweor.html

[Q70] 更新统计信息
来源：http://dali.ybcxt.top/Article/details/gtixxruidl.html

ANALYZE TABLE users;
来源：http://dali.cqqwz.cn/Article/details/gtdjdpfiig.html

[Q71] 查看建表语句
来源：http://dali.jqgfzy.top/Article/details/gtkpomxbnf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hongshengwenyu.top/Article/details/gtzkzdqgun.html

[Q72] 查看索引
来源：http://dali.nanxinkj.top/Article/details/gthsuwivue.html

SHOW INDEX FROM users;
来源：http://dali.yj20258888.top/Article/details/gtlgfrsscb.html

[Q73] 查看表状态
来源：http://dali.svipenyu.cn/Article/details/gtljgtdekn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ehwqpu.com/Article/details/gtcdrvuiqj.html

[Q74] 强制使用索引
来源：http://dali.chenzaomai.com/Article/details/gtfulqfzhw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhoulong.xyz/Article/details/gttqrevqfz.html

[Q75] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gtpyenycyl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtqtsiztpk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.iojbl.cn/Article/details/gtxmjocswf.html

[Q76] 按天统计
来源：http://dali.birdmap.top/Article/details/gtwgznolzz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuanzhike.top/Article/details/gtwcldzwkc.html

[Q77] 时间加减
来源：http://dali.wangshuangyany.cn/Article/details/gtbpigdlcd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.wangshuangyany.cn/Article/details/gtrwygdqai.html

[Q78] 当前时间
来源：http://dali.yj20258888.top/Article/details/gtrhgnjpsg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.aizwys.cn/Article/details/gtcnzccqly.html

[Q79] 字符串拼接
来源：http://dali.sweek.top/Article/details/gthegatfux.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nanxuanxn.top/Article/details/gtvhzwjfkf.html

[Q80] 字符串截取
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfmhzjdz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtsytplcwp.html

[Q81] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gtcppxeizs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtvisbnpwm.html

[Q82] 字符长度与字节长度
来源：http://dali.yonumen.top/Article/details/gtlrisruva.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtapapjdhw.html

[Q83] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gtwhxnpkuf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtsskmlbxh.html

[Q84] 去除首尾空格
来源：http://dali.chenjidiqi.icu/Article/details/gtfslglkiy.html

SELECT TRIM(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gtqfumrfig.html

[Q85] 数值取整
来源：http://dali.mhx1999.top/Article/details/gtnahuqxhw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ppjwa.cn/Article/details/gtrhrfthmn.html

[Q86] 读取 JSON 字段
来源：http://dali.birdmap.top/Article/details/gtihtprdjp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenlongwang.top/Article/details/gtqwgafjso.html

[Q87] JSON 字段做条件
来源：http://dali.nwbrower.top/Article/details/gttjsdozcy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhixingplan.top/Article/details/gthotnohiw.html

[Q88] 行转列（条件聚合）
来源：http://dali.tanke756.top/Article/details/gtevqqvsoy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guannengcc.top/Article/details/gtdbzveqrn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.havefunace.top/Article/details/gtjydvlnib.html

[Q89] 判断表是否存在
来源：http://dali.sufxvd.cn/Article/details/gtedqlstvg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yangfankeji.com/Article/details/gtstfjjhem.html

[Q90] 生成序号列
来源：http://dali.daxiang520.top/Article/details/gtbvmqhhhk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ybcxt.top/Article/details/gtagffbaha.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtyertynjo.html

R. Bash 专题
来源：http://dali.zhoulong.xyz/Article/details/gttkmkkqrp.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gthrfkgzgc.html

[R01] shebang 与严格模式
来源：http://dali.guowangkeji.top/Article/details/gtxmqxjauc.html

#!/usr/bin/env bash
来源：http://dali.dashuyun.cn/Article/details/gtrtasnsmv.html

set -euo pipefail
来源：http://dali.xylfe.cn/Article/details/gthftvnhph.html

[R02] 变量赋值与使用
来源：http://dali.zdqjudy.top/Article/details/gtdesjidbc.html

name="Tom"; echo "$name"
来源：http://dali.sxryk.cn/Article/details/gtxprzhoou.html

[R03] 只读变量
来源：http://dali.tian-w.cn/Article/details/gtjsbbiqoe.html

readonly PI=3.14
来源：http://dali.cdnleiting.top/Article/details/gtnfljbqtg.html

[R04] 位置参数
来源：http://dali.ivvv.top/Article/details/gtcqwvtbei.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hongshengwenyu.top/Article/details/gtwyfbdwsh.html

[R05] 参数默认值
来源：http://dali.birdmap.top/Article/details/gtabgtmhwk.html

name="${1:-default}"
来源：http://dali.zhongyouzk.top/Article/details/gtkhkzfwel.html

[R06] 判断命令是否存在
来源：http://dali.hammf.cn/Article/details/gtzyebhlaa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.316326.xyz/Article/details/gtdvbvywju.html

[R07] if 判断文件
来源：http://dali.chenzaomai.com/Article/details/gtdhbuyrfu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgfzy.top/Article/details/gtndbxdoxz.html

[R08] 数值比较
来源：http://dali.vqdsnc.cn/Article/details/gtogygprhp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtmsycubrc.html

[R09] 字符串比较
来源：http://dali.zhengqikj.top/Article/details/gtnefxcghz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daria6918.cn/Article/details/gtlupoyorz.html

[R10] 正则匹配
来源：http://dali.yj20258.top/Article/details/gtrqnsnydw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.c1oappe.top/Article/details/gtfzyvwgjg.html

[R11] case 多分支
来源：http://dali.cheryme.top/Article/details/gtjwhtffqz.html

case "$1" in
来源：http://dali.cashguo.top/Article/details/gtawvqlhey.html

start) echo "启动" ;;
来源：http://dali.gzhubu.top/Article/details/gthcamishv.html

stop)  echo "停止" ;;
来源：http://dali.wangdashe.top/Article/details/gtpgpweyod.html

*)     echo "未知命令" ;;
来源：http://dali.birdmap.top/Article/details/gtnmricikl.html

esac
来源：http://dali.yuanzhike.top/Article/details/gtlaahyxsk.html

[R12] for 遍历文件
来源：http://dali.gaohongyu789.top/Article/details/gthbmvycdc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yanxiufei.cn/Article/details/gtufvauyuz.html

[R13] for 计数循环
来源：http://dali.redwolf501.top/Article/details/gtcevnpoaj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjcynsaf.html

[R14] C 风格 for
来源：http://dali.zhengqikj.top/Article/details/gttljrdzbx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkuuzoxf.html

[R15] while 逐行读文件
来源：http://dali.cheryme.top/Article/details/gtmbtgngzy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yongpay.top/Article/details/gtnmgbjfvm.html

[R16] until 等待条件
来源：http://dali.xuanzx.com/Article/details/gttqvpqbos.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.andypj.xyz/Article/details/gtgjyzdxmz.html

[R17] 数组定义与取值
来源：http://dali.zhengqikj.top/Article/details/gtddbdburr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hysaishi.cn/Article/details/gtbcdtijvg.html

[R18] 遍历数组
来源：http://dali.ehwqpu.com/Article/details/gtvkldsird.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.vqdsnc.cn/Article/details/gtaddrozuu.html

[R19] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gtlharutar.html

echo "${#arr[@]}"
来源：http://dali.chenlongwang.top/Article/details/gteytgxczj.html

[R20] 关联数组（字典）
来源：http://dali.hysaishi.cn/Article/details/gtluwcytpf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.svipenyu.cn/Article/details/gtekbdrlzv.html

[R21] 字符串长度
来源：http://dali.cucudq.cn/Article/details/gthnncsfbp.html

echo "${#s}"
来源：http://dali.chenjidiqi.icu/Article/details/gtpabcrczk.html

[R22] 截取子串
来源：http://dali.feifeiyinyue.top/Article/details/gtdazwupxw.html

echo "${s:0:5}"
来源：http://dali.nanxinkj.top/Article/details/gtczwrimky.html

[R23] 字符串替换
来源：http://dali.haohaochexian.top/Article/details/gtsmobwmfo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dashuyun.cn/Article/details/gtnxcpbygy.html

[R24] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gtnvdbnzqb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.svipenyu.cn/Article/details/gtusqfecqy.html

[R25] 去后缀 / 去前缀
来源：http://dali.aibaodan.cn/Article/details/gtucfczwts.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yongpay.top/Article/details/gtnmszweqv.html

[R26] 命令替换
来源：http://dali.tian-w.cn/Article/details/gthcmpkpft.html

now=$(date +%F); echo "$now"
来源：http://dali.fengsongda.top/Article/details/gtvlrjuxey.html

[R27] 算术展开
来源：http://dali.cucudq.cn/Article/details/gtryigvvgt.html

echo $((1 + 2 * 3))
来源：http://dali.shangyingyoupin.top/Article/details/gtnbsjbqeq.html

[R28] 浮点运算
来源：http://dali.yj202588.top/Article/details/gtudyuvwxg.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gtbuseskeu.html

[R29] 定义函数
来源：http://dali.fengsongda.top/Article/details/gtgjvlzred.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gzhubu.top/Article/details/gtpjzaacgt.html

[R30] 函数返回状态码
来源：http://dali.mhx1999.top/Article/details/gtetfmthff.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.0kj1m.cn/Article/details/gtweasfqdz.html

[R31] 局部变量
来源：http://dali.ydzc1.top/Article/details/gtglxhekwd.html

f() { local x=1; echo "$x"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtrwxnvqmi.html

[R32] 参数个数校验
来源：http://dali.chenlongwang.top/Article/details/gtjtnflqhj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gtzykzfucs.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgufenzy.top/Article/details/gtfeddsoji.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.kuanghao11.cn/Article/details/gtobjzywvz.html

[R34] 退出时清理
来源：http://dali.yangfankeji.com/Article/details/gtbbxwydeb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gtxqfugspj.html

[R35] 后台执行并等待
来源：http://dali.hysaishi.cn/Article/details/gtookgcdlv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigufen.top/Article/details/gtlsyjrxpy.html

[R36] 并发执行多个任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqksrtoto.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yanxiufei.cn/Article/details/gtteeucnpm.html

[R37] 把输出赋给变量
来源：http://dali.shzxlz.cn/Article/details/gtvfgebjqb.html

files=$(ls -1)
来源：http://dali.birdmap.top/Article/details/gtbmthphum.html

[R38] 管道串联
来源：http://dali.316326.xyz/Article/details/gtzjawwvfw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xuetiantiany.cn/Article/details/gtmfostegi.html

[R39] 重定向标准输出与错误
来源：http://dali.zycfv.cn/Article/details/gtahqxyjtx.html

cmd > out.log 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gtognufqrw.html

[R40] 追加写日志
来源：http://dali.hywenlv.cn/Article/details/gtsqwdtjjj.html

echo "log" >> out.log
来源：http://dali.shanyushiyangtech.top/Article/details/gtqrpiyake.html

[R41] 丢弃输出
来源：http://dali.sxryk.cn/Article/details/gtcvnsxtum.html

cmd >/dev/null 2>&1
来源：http://dali.cucudq.cn/Article/details/gtrokldslo.html

[R42] 输入重定向
来源：http://dali.quarkkingdee.top/Article/details/gtrhgvphrp.html

wc -l < a.txt
来源：http://dali.hammf.cn/Article/details/gtatugnnxv.html

[R43] 按名字查找文件
来源：http://dali.hnxiangtu.top/Article/details/gtyhsbmlcp.html

find . -name "*.log" -type f
来源：http://dali.guowangkeji.top/Article/details/gtyqmsoixb.html

[R44] 按修改时间查找
来源：http://dali.zycfv.cn/Article/details/gtqpbenmnd.html

find . -mtime -7 -type f
来源：http://dali.jqgufenzy.top/Article/details/gtgguansnd.html

[R45] 批量删除
来源：http://dali.tanke756.top/Article/details/gtlnvycwfj.html

find . -name "*.tmp" -delete
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnlxvuau.html

[R46] 递归替换文件内容
来源：http://dali.jyoumei.cn/Article/details/gtyhgtgent.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tianlin.xyz/Article/details/gtpakevotu.html

[R47] sed 单行替换
来源：http://dali.dianchejie.cn/Article/details/gtecfgqywl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258.top/Article/details/gtcghumcvl.html

[R48] awk 取指定列
来源：http://dali.gogol.net.cn/Article/details/gtlkifvyzq.html

awk '{print $1, $3}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtobxjprsk.html

[R49] awk 带条件
来源：http://dali.aibaodan.cn/Article/details/gtlmcrinda.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hnqzz.top/Article/details/gttnkcednv.html

[R50] awk 求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbvhehkl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtktqdrngk.html

[R51] 排序去重取前几
来源：http://dali.hammf.cn/Article/details/gtubjggupf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pycfn.com/Article/details/gtegjrrtbs.html

[R52] 统计行数
来源：http://dali.yj20258.top/Article/details/gtivrlbkbx.html

wc -l a.txt
来源：http://dali.ivvv.top/Article/details/gtkobcfpwx.html

[R53] 查看文件头与实时尾
来源：http://dali.hammf.cn/Article/details/gtvktdkkex.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hfpthk.cn/Article/details/gtxdpuafho.html

[R54] 比较两个文件
来源：http://dali.hnxiangtu.top/Article/details/gthpchzrzl.html

diff a.txt b.txt
来源：http://dali.sweek.top/Article/details/gtjpxiisfe.html

[R55] 压缩与解压
来源：http://dali.redwolf501.top/Article/details/gtpevyvzpk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zycfv.cn/Article/details/gtwsfnucjr.html

[R56] 远程拷贝
来源：http://dali.shuidangran.top/Article/details/gtntxnznjf.html

scp file user@host:/path/
来源：http://dali.chenjidiqi.icu/Article/details/gtskftyxhf.html

[R57] 远程执行命令
来源：http://dali.iojbl.cn/Article/details/gtdsyswmtx.html

ssh user@host 'uptime'
来源：http://dali.c1oappe.top/Article/details/gtnlnxbvnn.html

[R58] 下载文件
来源：http://dali.chenzaomai.com/Article/details/gtdwnslvdf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.daria6918.cn/Article/details/gtmvvxmgui.html

[R59] 发 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gtylrfyjzf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gtdgvgcvsb.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gtihxtoekp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xziqi.cn/Article/details/gtaeqmqixg.html

[R61] 磁盘占用
来源：http://dali.andypj.xyz/Article/details/gtncqdlhkw.html


<!-- 参考信息 -->