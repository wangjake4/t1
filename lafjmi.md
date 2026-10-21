代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yongpay.top/Article/details/gtrdvjuisd.html

[Q18] 模糊匹配
来源：http://dali.zhengqikj.top/Article/details/gtzgajomnv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.quarkkingdee.top/Article/details/gtkcsnghdl.html

[Q19] 范围查询
来源：http://dali.chenlongwang.top/Article/details/gtorgazadc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yanxiufei.cn/Article/details/gtynbjssyz.html

[Q20] IN 列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizkekmpk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtczdcmnzp.html

[Q21] 空值判断
来源：http://dali.chenzaomai.com/Article/details/gtzlggcmgh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sufxvd.cn/Article/details/gtjrbhgavd.html

[Q22] 排序
来源：http://dali.zhongyouzk.top/Article/details/gtjztjuair.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cheryme.top/Article/details/gtvxsbhsmg.html

[Q23] 分页
来源：http://dali.sufxvd.cn/Article/details/gtuyjnqsdz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dianchejie.cn/Article/details/gtzpgoagzo.html

[Q24] 去重
来源：http://dali.smart0.xyz/Article/details/gtrdougazg.html

SELECT DISTINCT city FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtvoxhiymm.html

[Q25] 只取前 N 条
来源：http://dali.yangfankeji.com/Article/details/gtiiqkqmyv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sysykeji.top/Article/details/gtdzwdhtgx.html

[Q26] 计数
来源：http://dali.nanxinkj.top/Article/details/gthozenfam.html

SELECT COUNT(*) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtzxpiqkza.html

[Q27] 条件计数
来源：http://dali.aibaodan.cn/Article/details/gtvszlgclu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtgmxigral.html

[Q28] 求和与平均
来源：http://dali.cqqwz.cn/Article/details/gtsnfyowuh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtbrrmvsvh.html

[Q29] 最大最小值
来源：http://dali.jyoumei.cn/Article/details/gtupvjxjfv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtsckwqjtk.html

[Q30] 分组统计
来源：http://dali.yangfankeji.com/Article/details/gthxslhzak.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gtpqptqjrr.html

[Q31] 分组后过滤
来源：http://dali.sysykeji.top/Article/details/gtwxaymcpo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cqqwz.cn/Article/details/gtgnrfknlc.html

[Q32] 分组拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtcdnjgzdq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddgwyvbh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hfpthk.cn/Article/details/gtcbwrsmev.html

[Q33] 多列分组
来源：http://dali.zhixingplan.top/Article/details/gtpqiyhfov.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ivvv.top/Article/details/gtdjnbhzaz.html

[Q34] 每组取第一条
来源：http://dali.hfpthk.cn/Article/details/gtrpvjhogt.html

SELECT * FROM (
来源：http://dali.sxryk.cn/Article/details/gtditcolms.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gtcdcwsvoj.html

) t WHERE rn = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtmumzagnc.html

[Q35] 内连接
来源：http://dali.9152youxi.cn/Article/details/gtdukeuase.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yangfankeji.com/Article/details/gtbrzvtsvl.html

[Q36] 左连接
来源：http://dali.yj20258.top/Article/details/gtbgyhsujr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gtycfskzin.html

[Q37] 右连接
来源：http://dali.jyoumei.cn/Article/details/gtnchhshfi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.aibaodan.cn/Article/details/gtimzygzow.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hammf.cn/Article/details/gtpbddigje.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangdashe.top/Article/details/gtnyhwyceh.html

[Q39] 自连接（查上下级）
来源：http://dali.pengpengdd.cyou/Article/details/gtnqbzjybr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxuanxn.top/Article/details/gtzczxmiml.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sweek.top/Article/details/gtlzgfmxgb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.smart0.xyz/Article/details/gtpvykllan.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nwbrower.top/Article/details/gtpmjrwgyh.html

[Q41] 多表连接
来源：http://dali.feifeiyinyue.top/Article/details/gtejhbqirj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daxiang520.top/Article/details/gtenhbxpmq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yvedp.cn/Article/details/gtilupaxon.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yvedp.cn/Article/details/gthdeexzlm.html

[Q42] 连接条件附加过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtguszoiol.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmycnthyq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.smart0.xyz/Article/details/gtcrmetbrz.html

[Q43] 标量子查询
来源：http://dali.jyoumei.cn/Article/details/gtnxuemokz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.daria6918.cn/Article/details/gtdfeyrfhz.html

[Q44] IN 子查询
来源：http://dali.nwbrower.top/Article/details/gtscruwrhy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpotzzsac.html

[Q45] EXISTS 判断存在
来源：http://dali.gzhubu.top/Article/details/gtfkitojaz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pengpengdd.cyou/Article/details/gthqwibtcc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.vqdsnc.cn/Article/details/gtbdutwxds.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.birdmap.top/Article/details/gtbzsundvo.html

[Q47] 与平均值比较
来源：http://dali.cashguo.top/Article/details/gtioholeoj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmfsdsztc.html

[Q48] CTE 公用表表达式
来源：http://dali.zdqjudy.top/Article/details/gtucozkifo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aizwys.cn/Article/details/gtriagupwc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhixingplan.top/Article/details/gtctpuxisg.html

[Q49] 更新单行
来源：http://dali.yuanzhike.top/Article/details/gtjwakowhj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gtumbxfnqa.html

[Q50] 批量更新
来源：http://dali.guowangkeji.top/Article/details/gttlydziqx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sweek.top/Article/details/gtreqmmicm.html

[Q51] 用子查询更新
来源：http://dali.cdnleiting.top/Article/details/gthlfqhain.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtssanumsw.html

[Q52] 删除指定行
来源：http://dali.nwbrower.top/Article/details/gtnnefosey.html

DELETE FROM users WHERE id = 10;
来源：http://dali.mhx1999.top/Article/details/gtyiuimbpr.html

[Q53] 按条件删除
来源：http://dali.shangyingyoupin.top/Article/details/gtbiiomxmm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbiugxdok.html

[Q54] 清空表
来源：http://dali.9152youxi.cn/Article/details/gthlzzovqy.html

TRUNCATE TABLE logs;
来源：http://dali.yangfankeji.com/Article/details/gtrpklsszq.html

[Q55] 排名（并列占位）
来源：http://dali.daxiang520.top/Article/details/gtlhuowqxl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenlongwang.top/Article/details/gtvgfdhwiz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jqgufenzy.top/Article/details/gtmfxuycwp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gzhubu.top/Article/details/gtvsjfglvl.html

[Q57] 行号
来源：http://dali.hongshengwenyu.top/Article/details/gtxfgformx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtwpkkhium.html

[Q58] 累计求和
来源：http://dali.ybcxt.top/Article/details/gtluhmiyuc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyklbpuyc.html

[Q59] 分组内累计
来源：http://dali.havefunace.top/Article/details/gtmfxiwfgb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdzakbaet.html

[Q60] 取上一行 / 下一行
来源：http://dali.guowangkeji.top/Article/details/gtcfapewzr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.guannengcc.top/Article/details/gtphrpbvrh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtuvmuzfld.html

[Q61] 移动平均
来源：http://dali.ivvv.top/Article/details/gtuqvpuoyq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtdwvapurr.html

[Q62] 分组占比
来源：http://dali.yj20258888.top/Article/details/gtrdzbiagn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gtaeaetmrb.html

[Q63] 开启事务
来源：http://dali.hnxiangtu.top/Article/details/gttxrprnre.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cucudq.cn/Article/details/gtoostgfzs.html

[Q64] 提交事务
来源：http://dali.gaohongyu789.top/Article/details/gtiiqdbxdy.html

COMMIT;
来源：http://dali.gzhubu.top/Article/details/gtnypdeojp.html

[Q65] 回滚事务
来源：http://dali.jyoumei.cn/Article/details/gtnirfwjhk.html

ROLLBACK;
来源：http://dali.shzxlz.cn/Article/details/gtbqvwzitd.html

[Q66] 行锁查询
来源：http://dali.yj202588.top/Article/details/gtwxneaozq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cheryme.top/Article/details/gtvtsqnggy.html

[Q67] 设置隔离级别
来源：http://dali.cashguo.top/Article/details/gtkikyuhkt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shangyingyoupin.top/Article/details/gtlbmfxrci.html

[Q68] 保存点
来源：http://dali.guannengcc.top/Article/details/gtclnhxafc.html

SAVEPOINT sp1;
来源：http://dali.tianlin.xyz/Article/details/gtcxidnqgs.html

ROLLBACK TO sp1;
来源：http://dali.birdmap.top/Article/details/gttbdupscc.html

[Q69] 查看执行计划
来源：http://dali.vqdsnc.cn/Article/details/gtzayjbuam.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yongpay.top/Article/details/gttxqijsaq.html

[Q70] 更新统计信息
来源：http://dali.shanyushiyangkeji.top/Article/details/gttympsdnb.html

ANALYZE TABLE users;
来源：http://dali.9152youxi.cn/Article/details/gtdrxijagy.html

[Q71] 查看建表语句
来源：http://dali.hywenlv.cn/Article/details/gtjpunrkns.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj202588.top/Article/details/gtufnfwdqc.html

[Q72] 查看索引
来源：http://dali.fzhhl.top/Article/details/gtknfgqsjq.html

SHOW INDEX FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtelllwcdb.html

[Q73] 查看表状态
来源：http://dali.jinqigfzy.top/Article/details/gtsmaednit.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hnxiangtu.top/Article/details/gtvyodxytn.html

[Q74] 强制使用索引
来源：http://dali.jlsjyb.cn/Article/details/gtmmuqluwl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj20258.top/Article/details/gtbxvmbrur.html

[Q75] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gtqehwiqvn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtdlvjygwj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hongshengwenyu.top/Article/details/gtwfzfpuhn.html

[Q76] 按天统计
来源：http://dali.ppjwa.cn/Article/details/gtkpyheixq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jqgfzy.top/Article/details/gtkzhxmbgh.html

[Q77] 时间加减
来源：http://dali.gzhubu.top/Article/details/gtnzoyjcey.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenjidiqi.icu/Article/details/gtrjzitnvg.html

[Q78] 当前时间
来源：http://dali.svipenyu.cn/Article/details/gtezfceqnh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hongshengwenyu.top/Article/details/gtzhcgtsfh.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbtxwqpl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.fzhhl.top/Article/details/gtfmejedoy.html

[Q80] 字符串截取
来源：http://dali.xylfe.cn/Article/details/gteyyzuram.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtrtmjnugl.html

[Q81] 字符串替换
来源：http://dali.xuetiantiany.cn/Article/details/gtxliikcrt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yueranfly.top/Article/details/gtfunvgruk.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgfzy.top/Article/details/gtidcfzjdv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtnmirmzjz.html

[Q83] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gtefvvrhze.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtaagcejfj.html

[Q84] 去除首尾空格
来源：http://dali.sxryk.cn/Article/details/gtjijccuwr.html

SELECT TRIM(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtegegwond.html

[Q85] 数值取整
来源：http://dali.quarkkingdee.top/Article/details/gtrbjmoziv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.0kj1m.cn/Article/details/gtixerqiqg.html

[Q86] 读取 JSON 字段
来源：http://dali.zhengqikj.top/Article/details/gtzaxmvkyw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.haohaochexian.top/Article/details/gtfzhueojq.html

[Q87] JSON 字段做条件
来源：http://dali.9152youxi.cn/Article/details/gtuynrjlcn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tanke756.top/Article/details/gtbhziuwpq.html

[Q88] 行转列（条件聚合）
来源：http://dali.aibaodan.cn/Article/details/gthtaimtaf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.smart0.xyz/Article/details/gtstsjoawz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtcqokjmex.html

[Q89] 判断表是否存在
来源：http://dali.yongpay.top/Article/details/gtxafsrsne.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenjidiqi.icu/Article/details/gtmruverof.html

[Q90] 生成序号列
来源：http://dali.dianchejie.cn/Article/details/gtbuvebpdx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ivvv.top/Article/details/gtmbwhycff.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtcdvqkdha.html

R. Bash 专题
来源：http://dali.cqqwz.cn/Article/details/gtnxqpbhmd.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtzfdctagt.html

[R01] shebang 与严格模式
来源：http://dali.ydzc1.top/Article/details/gtvercguyl.html

#!/usr/bin/env bash
来源：http://dali.hongshengwenyu.top/Article/details/gtnsrcdbtm.html

set -euo pipefail
来源：http://dali.yj20258.top/Article/details/gtldbyygri.html

[R02] 变量赋值与使用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxgklkyp.html

name="Tom"; echo "$name"
来源：http://dali.dianchejie.cn/Article/details/gtudbokxsa.html

[R03] 只读变量
来源：http://dali.sufxvd.cn/Article/details/gtbjsgzspn.html

readonly PI=3.14
来源：http://dali.daria6918.cn/Article/details/gtqjlapktm.html

[R04] 位置参数
来源：http://dali.c1oappe.top/Article/details/gtndugclue.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuetiantiany.cn/Article/details/gtjmzmqefa.html

[R05] 参数默认值
来源：http://dali.jqgfzy.top/Article/details/gtlqksggps.html

name="${1:-default}"
来源：http://dali.zhoulong.xyz/Article/details/gtnedappbr.html

[R06] 判断命令是否存在
来源：http://dali.wangshuangyany.cn/Article/details/gtbruhzucy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.iojbl.cn/Article/details/gtlagvzjqp.html

[R07] if 判断文件
来源：http://dali.daria6918.cn/Article/details/gtjdqcphzd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhengqikj.top/Article/details/gtrfweysqw.html

[R08] 数值比较
来源：http://dali.yueranfly.top/Article/details/gtrboaxrco.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dianchejie.cn/Article/details/gtlzmrvnuf.html

[R09] 字符串比较
来源：http://dali.andypj.xyz/Article/details/gtkymejjim.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nanxinkj.top/Article/details/gtcwwajiwp.html

[R10] 正则匹配
来源：http://dali.sufxvd.cn/Article/details/gtuozlgxyd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.316326.xyz/Article/details/gtjxcqpama.html

[R11] case 多分支
来源：http://dali.yj20258.top/Article/details/gtajmyllgg.html

case "$1" in
来源：http://dali.svipenyu.cn/Article/details/gttsviaekg.html

start) echo "启动" ;;
来源：http://dali.fengsongda.top/Article/details/gtsacmzmjz.html

stop)  echo "停止" ;;
来源：http://dali.ybcxt.top/Article/details/gtcrwwiacy.html

*)     echo "未知命令" ;;
来源：http://dali.yonumen.top/Article/details/gtxwrlkqpw.html

esac
来源：http://dali.xinyue.icu/Article/details/gtrjxyazqn.html

[R12] for 遍历文件
来源：http://dali.nwbrower.top/Article/details/gtfhaeyjro.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tian-w.cn/Article/details/gtijxyyjkc.html

[R13] for 计数循环
来源：http://dali.feifeiyinyue.top/Article/details/gtzakjfkpi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yangfankeji.com/Article/details/gtfkkhjbyy.html

[R14] C 风格 for
来源：http://dali.hongshengwenyu.top/Article/details/gtiojlirmu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gtjikruczs.html

[R15] while 逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtjhrvjafr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.pycfn.com/Article/details/gteotodxmg.html

[R16] until 等待条件
来源：http://dali.jqgufenzy.top/Article/details/gtwwpxlykk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gtwekqeiue.html

[R17] 数组定义与取值
来源：http://dali.ppjwa.cn/Article/details/gtlveylrmh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangdashe.top/Article/details/gtssreaeyn.html

[R18] 遍历数组
来源：http://dali.nanxuanxn.top/Article/details/gttsnutnch.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daxiang520.top/Article/details/gtpknokfyc.html

[R19] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gttsaaeogg.html

echo "${#arr[@]}"
来源：http://dali.aibaodan.cn/Article/details/gtfcmdghkw.html

[R20] 关联数组（字典）
来源：http://dali.zhixingplan.top/Article/details/gtvihqfwqi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cheryme.top/Article/details/gtqxhtpcvb.html

[R21] 字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gtrdvawciz.html

echo "${#s}"
来源：http://dali.sysykeji.top/Article/details/gtasexcyuv.html

[R22] 截取子串
来源：http://dali.shanyushiyangtech.top/Article/details/gtoqbnaguu.html

echo "${s:0:5}"
来源：http://dali.yueranfly.top/Article/details/gtpzukeqbe.html

[R23] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gtlyxyxdgb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtauzerjvf.html

[R24] 大小写转换
来源：http://dali.iojbl.cn/Article/details/gtuaerdugs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.c1oappe.top/Article/details/gtitvdjudy.html

[R25] 去后缀 / 去前缀
来源：http://dali.zycfv.cn/Article/details/gtntiwwxeh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgufenzy.top/Article/details/gtvpmzmnco.html

[R26] 命令替换
来源：http://dali.gogol.net.cn/Article/details/gtucwxgtpi.html

now=$(date +%F); echo "$now"
来源：http://dali.svipenyu.cn/Article/details/gthpvhjsyn.html

[R27] 算术展开
来源：http://dali.yangfankeji.com/Article/details/gtcwxdebhq.html

echo $((1 + 2 * 3))
来源：http://dali.shangyingyoupin.top/Article/details/gtigxzsuvz.html

[R28] 浮点运算
来源：http://dali.ehwqpu.com/Article/details/gtsyeialvg.html

echo "scale=2; 10/3" | bc
来源：http://dali.pengpengdd.cyou/Article/details/gtmstciqfz.html

[R29] 定义函数
来源：http://dali.hysaishi.cn/Article/details/gtcktkhwgk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jlsjyb.cn/Article/details/gtggvdifjz.html

[R30] 函数返回状态码
来源：http://dali.316326.xyz/Article/details/gtesecqmjp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hongshengwenyu.top/Article/details/gtusoslifs.html

[R31] 局部变量
来源：http://dali.sxryk.cn/Article/details/gtyrozchhm.html

f() { local x=1; echo "$x"; }
来源：http://dali.shuidangran.top/Article/details/gtpvdbbgkm.html

[R32] 参数个数校验
来源：http://dali.jinqigufen.top/Article/details/gtvzhmilpc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gtseveoewj.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfinyqwy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yvedp.cn/Article/details/gtxvqhovzs.html

[R34] 退出时清理
来源：http://dali.jinqigfzy.top/Article/details/gtbyvfenbd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gtypjctuqz.html

[R35] 后台执行并等待
来源：http://dali.sysykeji.top/Article/details/gtecphfusn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xinyue.icu/Article/details/gtvfrtlyuy.html

[R36] 并发执行多个任务
来源：http://dali.sysykeji.top/Article/details/gtksrnzqmq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cucudq.cn/Article/details/gtxprnnrek.html

[R37] 把输出赋给变量
来源：http://dali.sxryk.cn/Article/details/gtqfcdbouf.html

files=$(ls -1)
来源：http://dali.9152youxi.cn/Article/details/gtzajrdqij.html

[R38] 管道串联
来源：http://dali.daria6918.cn/Article/details/gtflcjssyr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnqzz.top/Article/details/gtionaemus.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigufen.top/Article/details/gtikzniwvc.html

cmd > out.log 2>&1
来源：http://dali.0kj1m.cn/Article/details/gtfqfvkxhk.html

[R40] 追加写日志
来源：http://dali.shzxlz.cn/Article/details/gtlybkqlef.html

echo "log" >> out.log
来源：http://dali.cheryme.top/Article/details/gtxcfawlou.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gtnzudmfls.html

cmd >/dev/null 2>&1
来源：http://dali.sysykeji.top/Article/details/gturhfyynh.html

[R42] 输入重定向
来源：http://dali.shangyingyoupin.top/Article/details/gtojnyofpt.html

wc -l < a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtlgotaied.html

[R43] 按名字查找文件
来源：http://dali.yj20258888.top/Article/details/gtkvpboiss.html

find . -name "*.log" -type f
来源：http://dali.aibaodan.cn/Article/details/gtyekrjyar.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gtudkjwcmy.html

find . -mtime -7 -type f
来源：http://dali.quarkkingdee.top/Article/details/gtaagirbqt.html

[R45] 批量删除
来源：http://dali.zhixingplan.top/Article/details/gtdivbfbxg.html

find . -name "*.tmp" -delete
来源：http://dali.zycfv.cn/Article/details/gtpsnqvkgs.html

[R46] 递归替换文件内容
来源：http://dali.birdmap.top/Article/details/gtcchtpqxz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gotoacloud.top/Article/details/gthlmofrvp.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtcprqnmrf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtbsvmmnvk.html

[R48] awk 取指定列
来源：http://dali.zhixingplan.top/Article/details/gttbkrhbic.html

awk '{print $1, $3}' a.txt
来源：http://dali.hywenlv.cn/Article/details/gtvgfdbeal.html

[R49] awk 带条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtakfhsbou.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.svipenyu.cn/Article/details/gtylmgzqkz.html

[R50] awk 求和
来源：http://dali.hnxiangtu.top/Article/details/gtrnbxnvur.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtzhsotwgw.html

[R51] 排序去重取前几
来源：http://dali.yonumen.top/Article/details/gteeyqramg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwchaqry.html

[R52] 统计行数
来源：http://dali.ybcxt.top/Article/details/gtsxewzkne.html

wc -l a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gttoeslenh.html

[R53] 查看文件头与实时尾
来源：http://dali.gogol.net.cn/Article/details/gttbhcgjin.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tianlin.xyz/Article/details/gtmsizbbdx.html

[R54] 比较两个文件
来源：http://dali.xinyue.icu/Article/details/gtlqpueclh.html

diff a.txt b.txt
来源：http://dali.dianchejie.cn/Article/details/gtdqvbvgjn.html

[R55] 压缩与解压
来源：http://dali.gaohongyu789.top/Article/details/gtzqlauxny.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gaohongyu789.top/Article/details/gtgwshjhzn.html

[R56] 远程拷贝
来源：http://dali.tianlin.xyz/Article/details/gtysaspdwp.html

scp file user@host:/path/
来源：http://dali.zhongyouzk.top/Article/details/gtzduqpcdt.html

[R57] 远程执行命令
来源：http://dali.haohaochexian.top/Article/details/gtskplsikj.html

ssh user@host 'uptime'
来源：http://dali.316326.xyz/Article/details/gtcgvcrnby.html

[R58] 下载文件
来源：http://dali.jinqigfzy.top/Article/details/gtmfznnktl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gzhubu.top/Article/details/gthhffovns.html

[R59] 发 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gtzclkrduy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sweek.top/Article/details/gtpzdibxla.html

[R60] 只看 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gtkloqcgmw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.havefunace.top/Article/details/gtszggmolm.html

[R61] 磁盘占用
来源：http://dali.jianghu66.top/Article/details/gtnybofeqv.html

df -h;  du -sh *
来源：http://dali.yongpay.top/Article/details/gtzswkbjzj.html

[R62] 找最占空间的文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgeuljosu.html

du -ah . | sort -rh | head -10
来源：http://dali.ehwqpu.com/Article/details/gtcvjippbl.html

[R63] 内存与进程
来源：http://dali.pengpengdd.cyou/Article/details/gtxptlmsxl.html

free -h;  ps aux | grep nginx
来源：http://dali.chenzaomai.com/Article/details/gturlscvvb.html

[R64] 结束进程
来源：http://dali.gzhubu.top/Article/details/gtzwumyqzk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.guannengcc.top/Article/details/gttvfwbzpu.html

[R65] 查看端口占用
来源：http://dali.xinyue.icu/Article/details/gtzyxnzfgy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangkeji.top/Article/details/gtboxwkyit.html

[R66] 定时任务
来源：http://dali.quarkkingdee.top/Article/details/gtcehsudcn.html

crontab -e;  crontab -l
来源：http://dali.xuanzx.com/Article/details/gtomzcorot.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258888.top/Article/details/gtpwdvsznh.html


<!-- 参考信息 -->