代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pycfn.com/Article/details/gtarqsyhap.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cqqwz.cn/Article/details/gthbhdnycq.html

[Q13] 忽略重复插入
来源：http://dali.shuidangran.top/Article/details/gtjeuqorma.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj202588.top/Article/details/gtgeyxwflc.html

[Q14] 存在则更新（upsert）
来源：http://dali.smart0.xyz/Article/details/gtyuphoxmz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhixingplan.top/Article/details/gtddtzznat.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cheryme.top/Article/details/gtduwjvtkh.html

[Q15] 查询全部
来源：http://dali.andypj.xyz/Article/details/gtavfqherc.html

SELECT * FROM users;
来源：http://dali.jianghu66.top/Article/details/gtgjrmhxqw.html

[Q16] 查询指定列
来源：http://dali.ivvv.top/Article/details/gtzwudnrzr.html

SELECT id, name FROM users;
来源：http://dali.smart0.xyz/Article/details/gtzpbtgrxy.html

[Q17] 条件查询
来源：http://dali.yongpay.top/Article/details/gtxespjdtm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ehwqpu.com/Article/details/gtqdglyrtt.html

[Q18] 模糊匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaxmnlsnt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tian-w.cn/Article/details/gttuezwvem.html

[Q19] 范围查询
来源：http://dali.kuanghao11.cn/Article/details/gtawnaxuyz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sysykeji.top/Article/details/gtavkzitim.html

[Q20] IN 列表
来源：http://dali.dianchejie.cn/Article/details/gtirgmwkin.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ybcxt.top/Article/details/gtigctqxxm.html

[Q21] 空值判断
来源：http://dali.xuanzx.com/Article/details/gtzfsqonrh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.guowangkeji.top/Article/details/gteelbzyqn.html

[Q22] 排序
来源：http://dali.cucudq.cn/Article/details/gtnsmflysb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jqgfzy.top/Article/details/gtqltdvqgu.html

[Q23] 分页
来源：http://dali.yj20258.top/Article/details/gtkehgplbz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ydzc1.top/Article/details/gtpymieqbk.html

[Q24] 去重
来源：http://dali.jianghu66.top/Article/details/gtqmtofkqz.html

SELECT DISTINCT city FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtsqknktkw.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangtech.top/Article/details/gtdsunwsnd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.redwolf501.top/Article/details/gtccpiddly.html

[Q26] 计数
来源：http://dali.ivvv.top/Article/details/gtjheorcrb.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtaujghihs.html

[Q27] 条件计数
来源：http://dali.iojbl.cn/Article/details/gtqmvbnwxg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtattnpxjn.html

[Q28] 求和与平均
来源：http://dali.pengpengdd.cyou/Article/details/gtfkcfzmoo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gthsgoifjt.html

[Q29] 最大最小值
来源：http://dali.hongshengwenyu.top/Article/details/gtlajvlmxe.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtncxtqohq.html

[Q30] 分组统计
来源：http://dali.nwbrower.top/Article/details/gtuoriidwh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gterrizyff.html

[Q31] 分组后过滤
来源：http://dali.jqgufenzy.top/Article/details/gtguuqyyfa.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jianghu66.top/Article/details/gtmlgqxcao.html

[Q32] 分组拼接字符串
来源：http://dali.cashguo.top/Article/details/gtdndhyicc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gtytkngzsk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenlongwang.top/Article/details/gtmcwcehog.html

[Q33] 多列分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfvhuzvs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yonumen.top/Article/details/gtpofouojp.html

[Q34] 每组取第一条
来源：http://dali.yueranfly.top/Article/details/gtrbuptylt.html

SELECT * FROM (
来源：http://dali.smart0.xyz/Article/details/gthcewpnkc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigfzy.top/Article/details/gtobtvebaz.html

) t WHERE rn = 1;
来源：http://dali.yongpay.top/Article/details/gtruxgwqhw.html

[Q35] 内连接
来源：http://dali.yongpay.top/Article/details/gtyawwydrm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gtvcwcizly.html

[Q36] 左连接
来源：http://dali.gogol.net.cn/Article/details/gtgnxndowg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aibaodan.cn/Article/details/gtjxbakyqh.html

[Q37] 右连接
来源：http://dali.dashuyun.cn/Article/details/gtkgcwuspm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gogol.net.cn/Article/details/gtvkfgocae.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hammf.cn/Article/details/gtgokfzzhw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.guannengcc.top/Article/details/gtxwrbpzqz.html

[Q39] 自连接（查上下级）
来源：http://dali.yueranfly.top/Article/details/gtkmdmwovl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jyoumei.cn/Article/details/gtffdxdexo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hammf.cn/Article/details/gtgadsbacl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yonumen.top/Article/details/gtqcqvhfpu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelsrtahx.html

[Q41] 多表连接
来源：http://dali.sysykeji.top/Article/details/gtylcbabkx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgbxqcah.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shuidangran.top/Article/details/gtwtmynnbq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jqgufenzy.top/Article/details/gtgfgwtmzs.html

[Q42] 连接条件附加过滤
来源：http://dali.tanke756.top/Article/details/gtpdczxofl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yuanzhike.top/Article/details/gtlnemypeh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ybcxt.top/Article/details/gtvniljlib.html

[Q43] 标量子查询
来源：http://dali.aizwys.cn/Article/details/gtrvgrowon.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.bjfxy.top/Article/details/gtkvlblrgs.html

[Q44] IN 子查询
来源：http://dali.sufxvd.cn/Article/details/gtfsvbcnge.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hysaishi.cn/Article/details/gtnidijaoy.html

[Q45] EXISTS 判断存在
来源：http://dali.jqgufenzy.top/Article/details/gtipkdbpft.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jianghu66.top/Article/details/gtvqzrvdog.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenjidiqi.icu/Article/details/gtoceflodh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258.top/Article/details/gteszempnj.html

[Q47] 与平均值比较
来源：http://dali.zhongyouzk.top/Article/details/gtponnsqmk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258888.top/Article/details/gtdcpacdzu.html

[Q48] CTE 公用表表达式
来源：http://dali.pycfn.com/Article/details/gtisdkdlzo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.kuanghao11.cn/Article/details/gtiycvfdtt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenzaomai.com/Article/details/gtgpifnggs.html

[Q49] 更新单行
来源：http://dali.sufxvd.cn/Article/details/gtxawlxpae.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tanke756.top/Article/details/gtuiopkrma.html

[Q50] 批量更新
来源：http://dali.snrcjt.cn/Article/details/gtpmnppqya.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.andypj.xyz/Article/details/gttqwdgaxx.html

[Q51] 用子查询更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhxwjxev.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtxybvjjet.html

[Q52] 删除指定行
来源：http://dali.xziqi.cn/Article/details/gtfwiypdfo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.guannengcc.top/Article/details/gtwmnthsti.html

[Q53] 按条件删除
来源：http://dali.sufxvd.cn/Article/details/gtfslgtzvy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sufxvd.cn/Article/details/gtacnissvu.html

[Q54] 清空表
来源：http://dali.gaohongyu789.top/Article/details/gtybbabfcf.html

TRUNCATE TABLE logs;
来源：http://dali.zycfv.cn/Article/details/gtxoeucvfv.html

[Q55] 排名（并列占位）
来源：http://dali.yangfankeji.com/Article/details/gtwbcvwnmo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hammf.cn/Article/details/gtyyennjsh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ppjwa.cn/Article/details/gtvrvucafv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gtkxximmob.html

[Q57] 行号
来源：http://dali.fzhhl.top/Article/details/gtfrauxgre.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj202588.top/Article/details/gtedewzujs.html

[Q58] 累计求和
来源：http://dali.jinqigufen.top/Article/details/gtsrtppwol.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtspwxbqxl.html

[Q59] 分组内累计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfppubqfl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtjybmrfno.html

[Q60] 取上一行 / 下一行
来源：http://dali.jyoumei.cn/Article/details/gtsyuhqvgt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.guowangkeji.top/Article/details/gtmyuarwxw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtmlmdpnyx.html

[Q61] 移动平均
来源：http://dali.jinqigfzy.top/Article/details/gtiezgauvr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtrtsluvht.html

[Q62] 分组占比
来源：http://dali.cashguo.top/Article/details/gtzfuiguvh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gtiyoachox.html

[Q63] 开启事务
来源：http://dali.guowangkeji.top/Article/details/gtnfpzjtgq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yuxming.cn/Article/details/gtyeajczpi.html

[Q64] 提交事务
来源：http://dali.yueranfly.top/Article/details/gtsyhbsemu.html

COMMIT;
来源：http://dali.sufxvd.cn/Article/details/gteapkdbuk.html

[Q65] 回滚事务
来源：http://dali.shuidangran.top/Article/details/gtxpanpqgb.html

ROLLBACK;
来源：http://dali.hnqzz.top/Article/details/gtpukgfcto.html

[Q66] 行锁查询
来源：http://dali.havefunace.top/Article/details/gtpywrvqwl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tanke756.top/Article/details/gtyqgaswvm.html

[Q67] 设置隔离级别
来源：http://dali.yangfankeji.com/Article/details/gttuezfyat.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pycfn.com/Article/details/gtjnozqdii.html

[Q68] 保存点
来源：http://dali.xuanzx.com/Article/details/gtxoowglkg.html

SAVEPOINT sp1;
来源：http://dali.jianghu66.top/Article/details/gtumwwnlpu.html

ROLLBACK TO sp1;
来源：http://dali.zhoulong.xyz/Article/details/gthhuocoex.html

[Q69] 查看执行计划
来源：http://dali.nanxuanxn.top/Article/details/gtpwswaker.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shangyingyoupin.top/Article/details/gtlhirnnjs.html

[Q70] 更新统计信息
来源：http://dali.pycfn.com/Article/details/gtocgzncct.html

ANALYZE TABLE users;
来源：http://dali.tian-w.cn/Article/details/gtpddagiks.html

[Q71] 查看建表语句
来源：http://dali.zdqjudy.top/Article/details/gtvduhmtne.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258888.top/Article/details/gtkfgqlmqb.html

[Q72] 查看索引
来源：http://dali.pengpengdd.cyou/Article/details/gtmpdsrxoh.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsixdvmbb.html

[Q73] 查看表状态
来源：http://dali.aizwys.cn/Article/details/gtntukyhcv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xziqi.cn/Article/details/gtqmfmtwee.html

[Q74] 强制使用索引
来源：http://dali.hongshengwenyu.top/Article/details/gtetrypoxo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuetiantiany.cn/Article/details/gtxijvgfut.html

[Q75] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gtydfiudwb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtuvdwhhik.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shangyingyoupin.top/Article/details/gtnkqksgtn.html

[Q76] 按天统计
来源：http://dali.iojbl.cn/Article/details/gtyfmiccaw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daxiang520.top/Article/details/gtqcadmfrk.html

[Q77] 时间加减
来源：http://dali.gaohongyu789.top/Article/details/gtmnfntway.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.0kj1m.cn/Article/details/gtssoxktra.html

[Q78] 当前时间
来源：http://dali.gotoacloud.top/Article/details/gtkurabwgd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgfzy.top/Article/details/gtlerbqxpf.html

[Q79] 字符串拼接
来源：http://dali.nwbrower.top/Article/details/gtmgszkghb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shzxlz.cn/Article/details/gtbnkopwax.html

[Q80] 字符串截取
来源：http://dali.sysykeji.top/Article/details/gtjoroubba.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yonumen.top/Article/details/gtygonoqhd.html

[Q81] 字符串替换
来源：http://dali.yueranfly.top/Article/details/gtcgngbptm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.wangdashe.top/Article/details/gtxzejnqfc.html

[Q82] 字符长度与字节长度
来源：http://dali.sweek.top/Article/details/gtzkxzfzjo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtyagszmse.html

[Q83] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gtljgkkmvj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtwuqwesuu.html

[Q84] 去除首尾空格
来源：http://dali.ivvv.top/Article/details/gtbwgmqxeu.html

SELECT TRIM(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtwsgedxpr.html

[Q85] 数值取整
来源：http://dali.zhiwuduotai.top/Article/details/gtmjdcspjb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.smart0.xyz/Article/details/gtjewvdiob.html

[Q86] 读取 JSON 字段
来源：http://dali.meibo888.top/Article/details/gtflieugmx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvtsgkaf.html

[Q87] JSON 字段做条件
来源：http://dali.daria6918.cn/Article/details/gthodruyqu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gtluvagbdg.html

[Q88] 行转列（条件聚合）
来源：http://dali.hysaishi.cn/Article/details/gtqopdoerr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ehwqpu.com/Article/details/gtjsmfpbrs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yuxming.cn/Article/details/gtrwqpirsl.html

[Q89] 判断表是否存在
来源：http://dali.guowangkeji.top/Article/details/gtivwbcbdk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.redwolf501.top/Article/details/gtxuhseuuk.html

[Q90] 生成序号列
来源：http://dali.iojbl.cn/Article/details/gtxsvaobzj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.feifeiyinyue.top/Article/details/gteoqhmybi.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gttnennasu.html

R. Bash 专题
来源：http://dali.shuidangran.top/Article/details/gtxxvpfjso.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtbflulkhm.html

[R01] shebang 与严格模式
来源：http://dali.haohaochexian.top/Article/details/gtgxlygbjs.html

#!/usr/bin/env bash
来源：http://dali.ydzc1.top/Article/details/gtdvpkcsbo.html

set -euo pipefail
来源：http://dali.xuanzx.com/Article/details/gtcvejjgwt.html

[R02] 变量赋值与使用
来源：http://dali.gaohongyu789.top/Article/details/gthijtkcot.html

name="Tom"; echo "$name"
来源：http://dali.tianlin.xyz/Article/details/gtlukdrfyb.html

[R03] 只读变量
来源：http://dali.vqdsnc.cn/Article/details/gtziqaupoa.html

readonly PI=3.14
来源：http://dali.xuetiantiany.cn/Article/details/gtxkszuxyu.html

[R04] 位置参数
来源：http://dali.xinyue.icu/Article/details/gtuzwkibkq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zdqjudy.top/Article/details/gtmzcnntko.html

[R05] 参数默认值
来源：http://dali.mhx1999.top/Article/details/gtwtcutnza.html

name="${1:-default}"
来源：http://dali.jqgfzy.top/Article/details/gttsdjtsug.html

[R06] 判断命令是否存在
来源：http://dali.sysykeji.top/Article/details/gtvtecflne.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gthsxwnlbn.html

[R07] if 判断文件
来源：http://dali.ehwqpu.com/Article/details/gtnitfoscw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.birdmap.top/Article/details/gtszoetybl.html

[R08] 数值比较
来源：http://dali.cashguo.top/Article/details/gtkqmabaps.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gtqfsheybi.html

[R09] 字符串比较
来源：http://dali.chenzaomai.com/Article/details/gtveshylmm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtgmjbdcnh.html

[R10] 正则匹配
来源：http://dali.316326.xyz/Article/details/gtzamafdxf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cashguo.top/Article/details/gtrongsfdh.html

[R11] case 多分支
来源：http://dali.gzhubu.top/Article/details/gtectjvbbe.html

case "$1" in
来源：http://dali.kuanghao11.cn/Article/details/gtudzaoyvb.html

start) echo "启动" ;;
来源：http://dali.yvedp.cn/Article/details/gtfxyttack.html

stop)  echo "停止" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtksaxyatr.html

*)     echo "未知命令" ;;
来源：http://dali.chenlongwang.top/Article/details/gteuyukwyq.html

esac
来源：http://dali.bjfxy.top/Article/details/gtwmhrmxwg.html

[R12] for 遍历文件
来源：http://dali.shangyingyoupin.top/Article/details/gtfomnvhcs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxinkj.top/Article/details/gtpgdjfanm.html

[R13] for 计数循环
来源：http://dali.pycfn.com/Article/details/gtngxmeyyy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gtfzrehrjs.html

[R14] C 风格 for
来源：http://dali.cheryme.top/Article/details/gtmjlqznrp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.9152youxi.cn/Article/details/gtschiliii.html

[R15] while 逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtqnoojbku.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.pycfn.com/Article/details/gtttdoubqe.html

[R16] until 等待条件
来源：http://dali.cheryme.top/Article/details/gtihcigmcv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gtzqffngde.html

[R17] 数组定义与取值
来源：http://dali.cheryme.top/Article/details/gtvmxznexs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jiagoushi.top/Article/details/gtxwneowrm.html

[R18] 遍历数组
来源：http://dali.pengpengdd.cyou/Article/details/gtqzrnikce.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj20258888.top/Article/details/gtytyhmalh.html

[R19] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gtmywhmxdc.html

echo "${#arr[@]}"
来源：http://dali.sweek.top/Article/details/gtymetcggn.html

[R20] 关联数组（字典）
来源：http://dali.zhongyouzk.top/Article/details/gtdehaqtwx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.9152youxi.cn/Article/details/gtqqbdcyxp.html

[R21] 字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gtykttvicz.html

echo "${#s}"
来源：http://dali.yueranfly.top/Article/details/gtfnrccpom.html

[R22] 截取子串
来源：http://dali.sufxvd.cn/Article/details/gtgpaiparb.html

echo "${s:0:5}"
来源：http://dali.yuanzhike.top/Article/details/gtwhrjzyon.html

[R23] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gtqmsbwsla.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.pengpengdd.cyou/Article/details/gtuhteetfe.html

[R24] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gtgnatbeks.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guowangkeji.top/Article/details/gtcjflwftq.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnxiangtu.top/Article/details/gthlktpbnv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj20258888.top/Article/details/gtinhexkrd.html

[R26] 命令替换
来源：http://dali.nanxinkj.top/Article/details/gtzqnavjcr.html

now=$(date +%F); echo "$now"
来源：http://dali.smart0.xyz/Article/details/gtyjnnblka.html

[R27] 算术展开
来源：http://dali.shanyushiyangkeji.top/Article/details/gtasfvaktx.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258888.top/Article/details/gtdgiylaem.html

[R28] 浮点运算
来源：http://dali.zdqjudy.top/Article/details/gtkxykgyys.html

echo "scale=2; 10/3" | bc
来源：http://dali.tanke756.top/Article/details/gtmhfqvxbh.html

[R29] 定义函数
来源：http://dali.sxryk.cn/Article/details/gtwuqttxdf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hysaishi.cn/Article/details/gtinqlpyyk.html

[R30] 函数返回状态码
来源：http://dali.cucudq.cn/Article/details/gtkmrkfosk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sufxvd.cn/Article/details/gteqsdocto.html

[R31] 局部变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxkzhixp.html

f() { local x=1; echo "$x"; }
来源：http://dali.sweek.top/Article/details/gturgjdesw.html

[R32] 参数个数校验
来源：http://dali.gzhubu.top/Article/details/gtekvrgurf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hywenlv.cn/Article/details/gtpqemoxea.html

[R33] 捕获错误并提示行号
来源：http://dali.jyoumei.cn/Article/details/gtrujfndta.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gotoacloud.top/Article/details/gtyzjodwfr.html

[R34] 退出时清理
来源：http://dali.shuidangran.top/Article/details/gtegwhdgti.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gtlamtepgm.html

[R35] 后台执行并等待
来源：http://dali.guowangkeji.top/Article/details/gtglnfbsto.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhongyouzk.top/Article/details/gtpkhvtcbt.html

[R36] 并发执行多个任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmqgbrep.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.vqdsnc.cn/Article/details/gtdgpjeytl.html

[R37] 把输出赋给变量
来源：http://dali.svipenyu.cn/Article/details/gteiixdfql.html

files=$(ls -1)
来源：http://dali.cheryme.top/Article/details/gtdzvhfeqt.html

[R38] 管道串联
来源：http://dali.havefunace.top/Article/details/gtpjhmuxyo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigfzy.top/Article/details/gtertjqtjk.html

[R39] 重定向标准输出与错误
来源：http://dali.hongshengwenyu.top/Article/details/gtmfmmwxmm.html

cmd > out.log 2>&1
来源：http://dali.aizwys.cn/Article/details/gtmkyaqqwi.html

[R40] 追加写日志
来源：http://dali.redwolf501.top/Article/details/gtgxcicgif.html

echo "log" >> out.log
来源：http://dali.hfpthk.cn/Article/details/gtgtmmkssa.html

[R41] 丢弃输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrylbhwqp.html

cmd >/dev/null 2>&1
来源：http://dali.9152youxi.cn/Article/details/gttirwmrdn.html

[R42] 输入重定向
来源：http://dali.daria6918.cn/Article/details/gtjxffchcc.html

wc -l < a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtusrquyni.html

[R43] 按名字查找文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtptwdomce.html

find . -name "*.log" -type f
来源：http://dali.zhiwuduotai.top/Article/details/gtbxousqbm.html

[R44] 按修改时间查找
来源：http://dali.yueranfly.top/Article/details/gtbcbpylxe.html

find . -mtime -7 -type f
来源：http://dali.nanxinkj.top/Article/details/gtcijztkae.html

[R45] 批量删除
来源：http://dali.xuanzx.com/Article/details/gtiiaxbmae.html

find . -name "*.tmp" -delete
来源：http://dali.ywan-chungtsiang.top/Article/details/gthkrlqhdg.html

[R46] 递归替换文件内容
来源：http://dali.xuanzx.com/Article/details/gtlwyhcgep.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.c1oappe.top/Article/details/gthagsxrlb.html

[R47] sed 单行替换
来源：http://dali.hysaishi.cn/Article/details/gtufffdjne.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtqmdmvilh.html

[R48] awk 取指定列
来源：http://dali.tianlin.xyz/Article/details/gtbfrjrvhd.html

awk '{print $1, $3}' a.txt
来源：http://dali.cheryme.top/Article/details/gtfwtxdxga.html

[R49] awk 带条件
来源：http://dali.guowangkeji.top/Article/details/gtekwiucot.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nanxinkj.top/Article/details/gtkjvxuqqx.html

[R50] awk 求和
来源：http://dali.ivvv.top/Article/details/gtpuplnbdt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtjaladpsu.html

[R51] 排序去重取前几
来源：http://dali.ppjwa.cn/Article/details/gtqaubnnpg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cdnleiting.top/Article/details/gttkfgykfh.html

[R52] 统计行数
来源：http://dali.zycfv.cn/Article/details/gttxrapuqm.html

wc -l a.txt
来源：http://dali.hammf.cn/Article/details/gtwztixwnk.html

[R53] 查看文件头与实时尾
来源：http://dali.tian-w.cn/Article/details/gtjymxtlbo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hywenlv.cn/Article/details/gtmqpzwwry.html

[R54] 比较两个文件
来源：http://dali.yuanzhike.top/Article/details/gtehywjiek.html

diff a.txt b.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekysgbtt.html

[R55] 压缩与解压
来源：http://dali.hnqzz.top/Article/details/gtzpyrdbci.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.guowangkeji.top/Article/details/gtcohshlse.html

[R56] 远程拷贝
来源：http://dali.daxiang520.top/Article/details/gtzifqtfsn.html

scp file user@host:/path/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqupiozo.html

[R57] 远程执行命令
来源：http://dali.ehwqpu.com/Article/details/gtwoyvfrny.html

ssh user@host 'uptime'
来源：http://dali.tanke756.top/Article/details/gtttgibsqv.html

[R58] 下载文件
来源：http://dali.jinqigfzy.top/Article/details/gtmnrkkhxk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbawmathb.html

[R59] 发 POST JSON
来源：http://dali.ybcxt.top/Article/details/gtgkmyvylf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gtippjsytm.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenjidiqi.icu/Article/details/gtlabbuysx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xuetiantiany.cn/Article/details/gtxmlfxnsc.html

[R61] 磁盘占用
来源：http://dali.snrcjt.cn/Article/details/gtwogeabjc.html


<!-- 参考信息 -->