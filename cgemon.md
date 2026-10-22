代发 wailian999

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.redwolf501.top/Article/details/gtqcjmhfyy.html

[Q20] IN 列表
来源：http://dali.tian-w.cn/Article/details/gtlygsigod.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gzhubu.top/Article/details/gtsyaupajm.html

[Q21] 空值判断
来源：http://dali.chenjidiqi.icu/Article/details/gtmevqoxza.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.birdmap.top/Article/details/gtctwmfqfu.html

[Q22] 排序
来源：http://dali.yvedp.cn/Article/details/gtoteklgvc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.pengpengdd.cyou/Article/details/gtuqwbyjcq.html

[Q23] 分页
来源：http://dali.havefunace.top/Article/details/gtvfpbyesv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhongyouzk.top/Article/details/gtwxqnvjoo.html

[Q24] 去重
来源：http://dali.jqgfzy.top/Article/details/gtzrgkwgii.html

SELECT DISTINCT city FROM users;
来源：http://dali.svipenyu.cn/Article/details/gttvtrprfr.html

[Q25] 只取前 N 条
来源：http://dali.yonumen.top/Article/details/gtalytknvl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.havefunace.top/Article/details/gtelfhieus.html

[Q26] 计数
来源：http://dali.vqdsnc.cn/Article/details/gtjevbccei.html

SELECT COUNT(*) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtvjtmsonl.html

[Q27] 条件计数
来源：http://dali.cqqwz.cn/Article/details/gtgaukkpym.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.pycfn.com/Article/details/gtiiebcieb.html

[Q28] 求和与平均
来源：http://dali.ehwqpu.com/Article/details/gtmueeiawb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtqtayyauu.html

[Q29] 最大最小值
来源：http://dali.sxryk.cn/Article/details/gtummvothz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtaypgniee.html

[Q30] 分组统计
来源：http://dali.yangfankeji.com/Article/details/gtlnzriije.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtnhebyhfh.html

[Q31] 分组后过滤
来源：http://dali.fzhhl.top/Article/details/gtasqcahmu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj202588.top/Article/details/gtpjtkmzaz.html

[Q32] 分组拼接字符串
来源：http://dali.hammf.cn/Article/details/gtujnsapup.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtybjfjuqq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.redwolf501.top/Article/details/gtbvvpkznh.html

[Q33] 多列分组
来源：http://dali.fengsongda.top/Article/details/gtvuaiaras.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.fengsongda.top/Article/details/gtzdorajwv.html

[Q34] 每组取第一条
来源：http://dali.xylfe.cn/Article/details/gtclxjoxbu.html

SELECT * FROM (
来源：http://dali.dianchejie.cn/Article/details/gtiyghsrbl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tanke756.top/Article/details/gtrzlyypal.html

) t WHERE rn = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtsohivwas.html

[Q35] 内连接
来源：http://dali.zycfv.cn/Article/details/gtljwnkfds.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gtgxgqrlpj.html

[Q36] 左连接
来源：http://dali.ppjwa.cn/Article/details/gtpynxmaxn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj202588.top/Article/details/gtnkzufuge.html

[Q37] 右连接
来源：http://dali.aizwys.cn/Article/details/gtlncgnvlf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ivvv.top/Article/details/gtpnjsxjjn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.9152youxi.cn/Article/details/gthabkoqbg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.aizwys.cn/Article/details/gtmoxmpfmg.html

[Q39] 自连接（查上下级）
来源：http://dali.guowangkeji.top/Article/details/gtjdayauav.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guowangkeji.top/Article/details/gtsdsfgcsx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daria6918.cn/Article/details/gtsfsvmads.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shangyingyoupin.top/Article/details/gtirtgizxz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hywenlv.cn/Article/details/gtytnvxwek.html

[Q41] 多表连接
来源：http://dali.yuxming.cn/Article/details/gtodlinatk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.vqdsnc.cn/Article/details/gtaxousrdf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenjidiqi.icu/Article/details/gtofdunwqj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jqgufenzy.top/Article/details/gtkamqoqfm.html

[Q42] 连接条件附加过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbblrplwi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.fzhhl.top/Article/details/gtscssiwpz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gotoacloud.top/Article/details/gtknatlilu.html

[Q43] 标量子查询
来源：http://dali.yongpay.top/Article/details/gtzodwrjww.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dianchejie.cn/Article/details/gtgvnriboi.html

[Q44] IN 子查询
来源：http://dali.316326.xyz/Article/details/gtxljldezh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jianghu66.top/Article/details/gtcegbolsj.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtanbialzd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.meibo888.top/Article/details/gtispjdfxp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ybcxt.top/Article/details/gtvujigqjv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrvqijly.html

[Q47] 与平均值比较
来源：http://dali.havefunace.top/Article/details/gtzlmdnlxs.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqndnidy.html

[Q48] CTE 公用表表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtndlztihd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuanzhike.top/Article/details/gtymwgyduc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqcjkkqi.html

[Q49] 更新单行
来源：http://dali.jqgufenzy.top/Article/details/gthodgxaam.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gtzcvxtxiy.html

[Q50] 批量更新
来源：http://dali.nanxuanxn.top/Article/details/gtoegvslum.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ivvv.top/Article/details/gtdfnyboqz.html

[Q51] 用子查询更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoeswijzf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.aizwys.cn/Article/details/gtszcuxnre.html

[Q52] 删除指定行
来源：http://dali.hammf.cn/Article/details/gtonytukoi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gtzzzuueen.html

[Q53] 按条件删除
来源：http://dali.jlsjyb.cn/Article/details/gtgoigdodl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nwbrower.top/Article/details/gtwquddcsv.html

[Q54] 清空表
来源：http://dali.cucudq.cn/Article/details/gtlqjzdapo.html

TRUNCATE TABLE logs;
来源：http://dali.zhixingplan.top/Article/details/gticoquzlv.html

[Q55] 排名（并列占位）
来源：http://dali.zhengqikj.top/Article/details/gtltitycwh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shanyushiyangtech.top/Article/details/gtabnbqota.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jlsjyb.cn/Article/details/gtclwaiyne.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tanke756.top/Article/details/gtjicktlzr.html

[Q57] 行号
来源：http://dali.hywenlv.cn/Article/details/gtpaiiwepq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugxujuxt.html

[Q58] 累计求和
来源：http://dali.jianghu66.top/Article/details/gtkydxggqg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtytyjfbdv.html

[Q59] 分组内累计
来源：http://dali.gaohongyu789.top/Article/details/gtkstoankb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtccmxfbhb.html

[Q60] 取上一行 / 下一行
来源：http://dali.dashuyun.cn/Article/details/gttlzojnbr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenjidiqi.icu/Article/details/gtcotgqbcw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtjbdrquuo.html

[Q61] 移动平均
来源：http://dali.yj20258888.top/Article/details/gtvlmjquai.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtzutshbdy.html

[Q62] 分组占比
来源：http://dali.iojbl.cn/Article/details/gtzltluihb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gtzodshmdi.html

[Q63] 开启事务
来源：http://dali.cashguo.top/Article/details/gtsbsyqdte.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuetiantiany.cn/Article/details/gtfdnqaroi.html

[Q64] 提交事务
来源：http://dali.aizwys.cn/Article/details/gtntqpuetd.html

COMMIT;
来源：http://dali.vqdsnc.cn/Article/details/gtkgicxfos.html

[Q65] 回滚事务
来源：http://dali.hysaishi.cn/Article/details/gtomvaarqp.html

ROLLBACK;
来源：http://dali.yj20258.top/Article/details/gtmfiqqzgq.html

[Q66] 行锁查询
来源：http://dali.yj20258.top/Article/details/gtounnpouv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.pycfn.com/Article/details/gtuqtyfvze.html

[Q67] 设置隔离级别
来源：http://dali.jqgfzy.top/Article/details/gtfbteckxd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sweek.top/Article/details/gtiubsmgbo.html

[Q68] 保存点
来源：http://dali.pycfn.com/Article/details/gtineenhvx.html

SAVEPOINT sp1;
来源：http://dali.iojbl.cn/Article/details/gtigmtmlcs.html

ROLLBACK TO sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtorzcsvfy.html

[Q69] 查看执行计划
来源：http://dali.sweek.top/Article/details/gtmaycapqb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hnqzz.top/Article/details/gtedsrizdg.html

[Q70] 更新统计信息
来源：http://dali.guannengcc.top/Article/details/gtqtfejlms.html

ANALYZE TABLE users;
来源：http://dali.zhixingplan.top/Article/details/gtlribrgto.html

[Q71] 查看建表语句
来源：http://dali.zhixingplan.top/Article/details/gtusqgjxog.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xylfe.cn/Article/details/gtefvzaexj.html

[Q72] 查看索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgksdinwj.html

SHOW INDEX FROM users;
来源：http://dali.nwbrower.top/Article/details/gtwctbkhyh.html

[Q73] 查看表状态
来源：http://dali.ehwqpu.com/Article/details/gtgrsjngoj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hammf.cn/Article/details/gtqmliezba.html

[Q74] 强制使用索引
来源：http://dali.jyoumei.cn/Article/details/gtefbdontp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shangyingyoupin.top/Article/details/gttaewolox.html

[Q75] 日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gtlvskddbe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndcwssim.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hywenlv.cn/Article/details/gtekxipjhh.html

[Q76] 按天统计
来源：http://dali.yueranfly.top/Article/details/gtznogdtci.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aizwys.cn/Article/details/gtxfevfjyc.html

[Q77] 时间加减
来源：http://dali.zhongyouzk.top/Article/details/gtisstnshc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jqgufenzy.top/Article/details/gtqpydsoib.html

[Q78] 当前时间
来源：http://dali.fengsongda.top/Article/details/gttcrshjhu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cdnleiting.top/Article/details/gtsznzunam.html

[Q79] 字符串拼接
来源：http://dali.cashguo.top/Article/details/gtpbrsbbkf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gaohongyu789.top/Article/details/gtmtsvarnq.html

[Q80] 字符串截取
来源：http://dali.zhixingplan.top/Article/details/gtfieazmzi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtxdzwxxtx.html

[Q81] 字符串替换
来源：http://dali.redwolf501.top/Article/details/gtcipwhybh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtlqyvgkjv.html

[Q82] 字符长度与字节长度
来源：http://dali.jinqigufen.top/Article/details/gtaodujzbu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtnwocplbp.html

[Q83] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gtadagmklh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtiadbgixi.html

[Q84] 去除首尾空格
来源：http://dali.zhongyouzk.top/Article/details/gtpuaujesg.html

SELECT TRIM(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtdizadjdg.html

[Q85] 数值取整
来源：http://dali.bjfxy.top/Article/details/gtjlvyfgvm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.feifeiyinyue.top/Article/details/gtpgpglrxk.html

[Q86] 读取 JSON 字段
来源：http://dali.quarkkingdee.top/Article/details/gtrlsvxyxa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.quarkkingdee.top/Article/details/gtniymzlzh.html

[Q87] JSON 字段做条件
来源：http://dali.pycfn.com/Article/details/gteisaqhol.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zycfv.cn/Article/details/gtigtbwwoa.html

[Q88] 行转列（条件聚合）
来源：http://dali.havefunace.top/Article/details/gtyzfuunoz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.andypj.xyz/Article/details/gtvengjbfk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gteljvrhie.html

[Q89] 判断表是否存在
来源：http://dali.andypj.xyz/Article/details/gtfmchkqpa.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.svipenyu.cn/Article/details/gtbsmrlltn.html

[Q90] 生成序号列
来源：http://dali.yj20258888.top/Article/details/gtvigzuhso.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tian-w.cn/Article/details/gtsbnmiwho.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtwcbuvdxk.html

R. Bash 专题
来源：http://dali.redwolf501.top/Article/details/gtxmdpkbpb.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtrfhaczkq.html

[R01] shebang 与严格模式
来源：http://dali.chenjidiqi.icu/Article/details/gtqoswafhd.html

#!/usr/bin/env bash
来源：http://dali.ybcxt.top/Article/details/gtlwsflgnn.html

set -euo pipefail
来源：http://dali.zhixingplan.top/Article/details/gtbygmemml.html

[R02] 变量赋值与使用
来源：http://dali.haohaochexian.top/Article/details/gtrfyffnuo.html

name="Tom"; echo "$name"
来源：http://dali.0kj1m.cn/Article/details/gtufveuyvj.html

[R03] 只读变量
来源：http://dali.snrcjt.cn/Article/details/gtlbieytaq.html

readonly PI=3.14
来源：http://dali.nwbrower.top/Article/details/gtlvpmheps.html

[R04] 位置参数
来源：http://dali.gaohongyu789.top/Article/details/gtpvoxtlnx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shuidangran.top/Article/details/gtwdmhrmvs.html

[R05] 参数默认值
来源：http://dali.guowangkeji.top/Article/details/gtqjrdmxgi.html

name="${1:-default}"
来源：http://dali.hammf.cn/Article/details/gtcumqrumy.html

[R06] 判断命令是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtoihcozsx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gthpiodvdk.html

[R07] if 判断文件
来源：http://dali.yj20258.top/Article/details/gtqelbhjvz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxuanxn.top/Article/details/gttlovtlzc.html

[R08] 数值比较
来源：http://dali.iojbl.cn/Article/details/gtkycbjjsk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.kuanghao11.cn/Article/details/gtnpkqkqiy.html

[R09] 字符串比较
来源：http://dali.hywenlv.cn/Article/details/gtzoozqpob.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqitqapi.html

[R10] 正则匹配
来源：http://dali.hfpthk.cn/Article/details/gtlvasbcko.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtmpqtggyu.html

[R11] case 多分支
来源：http://dali.zhengqikj.top/Article/details/gtusxdiupo.html

case "$1" in
来源：http://dali.shuidangran.top/Article/details/gtxobtssnf.html

start) echo "启动" ;;
来源：http://dali.zhongyouzk.top/Article/details/gtisoyqsxs.html

stop)  echo "停止" ;;
来源：http://dali.cqqwz.cn/Article/details/gtokhwdulp.html

*)     echo "未知命令" ;;
来源：http://dali.yj20258888.top/Article/details/gtzsvylbxk.html

esac
来源：http://dali.xylfe.cn/Article/details/gtvkufitjw.html

[R12] for 遍历文件
来源：http://dali.zdqjudy.top/Article/details/gtfhgunbsy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxuanxn.top/Article/details/gtvyeskajp.html

[R13] for 计数循环
来源：http://dali.jqgfzy.top/Article/details/gtqrxeechb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gtxnklllyl.html

[R14] C 风格 for
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfhommrr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gtbhmugsju.html

[R15] while 逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtynhkrscj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aibaodan.cn/Article/details/gtnaxcbexs.html

[R16] until 等待条件
来源：http://dali.shuidangran.top/Article/details/gtwsdvolwf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.kuanghao11.cn/Article/details/gtppjkvhdk.html

[R17] 数组定义与取值
来源：http://dali.redwolf501.top/Article/details/gtjowcbbio.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fzhhl.top/Article/details/gtyooubnis.html

[R18] 遍历数组
来源：http://dali.cqqwz.cn/Article/details/gtbbllgxff.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ehwqpu.com/Article/details/gtnlddcxoe.html

[R19] 数组长度
来源：http://dali.yj20258888.top/Article/details/gtneluhhos.html

echo "${#arr[@]}"
来源：http://dali.yanxiufei.cn/Article/details/gtwvlrlmrk.html

[R20] 关联数组（字典）
来源：http://dali.shangyingyoupin.top/Article/details/gtibibilgo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daria6918.cn/Article/details/gtdxkkbkzc.html

[R21] 字符串长度
来源：http://dali.yonumen.top/Article/details/gtavyevcbx.html

echo "${#s}"
来源：http://dali.birdmap.top/Article/details/gtlqoshlnf.html

[R22] 截取子串
来源：http://dali.sxryk.cn/Article/details/gtrlzgbvjp.html

echo "${s:0:5}"
来源：http://dali.nanxinkj.top/Article/details/gtiadxloek.html

[R23] 字符串替换
来源：http://dali.yj20258.top/Article/details/gtvsmspcqz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yueranfly.top/Article/details/gthqqwalnt.html

[R24] 大小写转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpsfrovem.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhixingplan.top/Article/details/gttquapeiu.html

[R25] 去后缀 / 去前缀
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfpphlfb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenlongwang.top/Article/details/gtxpvghlrb.html

[R26] 命令替换
来源：http://dali.c1oappe.top/Article/details/gtilbdirfc.html

now=$(date +%F); echo "$now"
来源：http://dali.kuanghao11.cn/Article/details/gthuxehyhw.html

[R27] 算术展开
来源：http://dali.sufxvd.cn/Article/details/gtyqdppdfw.html

echo $((1 + 2 * 3))
来源：http://dali.cucudq.cn/Article/details/gtdhoeiaxm.html

[R28] 浮点运算
来源：http://dali.hnqzz.top/Article/details/gtwvipfcrk.html

echo "scale=2; 10/3" | bc
来源：http://dali.ehwqpu.com/Article/details/gtwgstesei.html

[R29] 定义函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtycnbcuqo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.birdmap.top/Article/details/gtsbqnauyy.html

[R30] 函数返回状态码
来源：http://dali.tianlin.xyz/Article/details/gtyknkicwc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.meibo888.top/Article/details/gtkvoreofw.html

[R31] 局部变量
来源：http://dali.xziqi.cn/Article/details/gtthhpafop.html

f() { local x=1; echo "$x"; }
来源：http://dali.havefunace.top/Article/details/gtbdjbfxfz.html

[R32] 参数个数校验
来源：http://dali.andypj.xyz/Article/details/gtvlevvtwr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gtudikacht.html

[R33] 捕获错误并提示行号
来源：http://dali.shangyingyoupin.top/Article/details/gtludjirfl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj20258888.top/Article/details/gtibhkohrg.html

[R34] 退出时清理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfljiaiq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gtkjidxjcd.html

[R35] 后台执行并等待
来源：http://dali.jiagoushi.top/Article/details/gttlwixpgo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinghuilouyu.cn/Article/details/gtdnasckzb.html

[R36] 并发执行多个任务
来源：http://dali.yj20258888.top/Article/details/gtzhrtyfdu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuxming.cn/Article/details/gtcmsooihn.html

[R37] 把输出赋给变量
来源：http://dali.ybcxt.top/Article/details/gtelfocfzt.html

files=$(ls -1)
来源：http://dali.cqqwz.cn/Article/details/gtqprmodii.html

[R38] 管道串联
来源：http://dali.hywenlv.cn/Article/details/gthntcfyty.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jianghu66.top/Article/details/gtpcqqmggn.html

[R39] 重定向标准输出与错误
来源：http://dali.jiagoushi.top/Article/details/gtzgshmdeg.html

cmd > out.log 2>&1
来源：http://dali.havefunace.top/Article/details/gtvpniydly.html

[R40] 追加写日志
来源：http://dali.xuetiantiany.cn/Article/details/gtszqinroy.html

echo "log" >> out.log
来源：http://dali.yonumen.top/Article/details/gtnxywndes.html

[R41] 丢弃输出
来源：http://dali.yj202588.top/Article/details/gtqmozdukg.html

cmd >/dev/null 2>&1
来源：http://dali.cashguo.top/Article/details/gthxfzwlmw.html

[R42] 输入重定向
来源：http://dali.ivvv.top/Article/details/gtecukklos.html

wc -l < a.txt
来源：http://dali.yongpay.top/Article/details/gtjhyhuijk.html

[R43] 按名字查找文件
来源：http://dali.nanxinkj.top/Article/details/gtaxhgmdtm.html

find . -name "*.log" -type f
来源：http://dali.sxryk.cn/Article/details/gtvzxrqojx.html

[R44] 按修改时间查找
来源：http://dali.hywenlv.cn/Article/details/gtidzowljm.html

find . -mtime -7 -type f
来源：http://dali.sufxvd.cn/Article/details/gtwuwxteac.html

[R45] 批量删除
来源：http://dali.daxiang520.top/Article/details/gtvnslrici.html

find . -name "*.tmp" -delete
来源：http://dali.jyoumei.cn/Article/details/gthebhkgzq.html

[R46] 递归替换文件内容
来源：http://dali.havefunace.top/Article/details/gtkmeqhdvn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinqigfzy.top/Article/details/gtynpebmgs.html

[R47] sed 单行替换
来源：http://dali.zhiwuduotai.top/Article/details/gtcvkyaxpq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkdmconc.html

[R48] awk 取指定列
来源：http://dali.pycfn.com/Article/details/gtjnfrsuoo.html

awk '{print $1, $3}' a.txt
来源：http://dali.sxryk.cn/Article/details/gtmttfqsvg.html

[R49] awk 带条件
来源：http://dali.dianchejie.cn/Article/details/gtxblujost.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tian-w.cn/Article/details/gthlvyvzah.html

[R50] awk 求和
来源：http://dali.dashuyun.cn/Article/details/gtlcggfkgt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.c1oappe.top/Article/details/gtjtzwjjsq.html

[R51] 排序去重取前几
来源：http://dali.tian-w.cn/Article/details/gtocbdfeno.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.redwolf501.top/Article/details/gtjpvniiiw.html

[R52] 统计行数
来源：http://dali.zhoulong.xyz/Article/details/gtficsfgvp.html

wc -l a.txt
来源：http://dali.snrcjt.cn/Article/details/gtffguznro.html

[R53] 查看文件头与实时尾
来源：http://dali.hammf.cn/Article/details/gtltaygbqu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuxming.cn/Article/details/gtupkinyal.html

[R54] 比较两个文件
来源：http://dali.cqqwz.cn/Article/details/gtspdzprtd.html

diff a.txt b.txt
来源：http://dali.kuanghao11.cn/Article/details/gtqzgbsxrh.html

[R55] 压缩与解压
来源：http://dali.cdnleiting.top/Article/details/gtbmkfxhbp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dashuyun.cn/Article/details/gteutprsjr.html

[R56] 远程拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gtgxpqtpfa.html

scp file user@host:/path/
来源：http://dali.tanke756.top/Article/details/gtxiicqxuq.html

[R57] 远程执行命令
来源：http://dali.smart0.xyz/Article/details/gtvcinnvrs.html

ssh user@host 'uptime'
来源：http://dali.nanxuanxn.top/Article/details/gtkwfikjkz.html

[R58] 下载文件
来源：http://dali.tian-w.cn/Article/details/gtidbdkuyi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yanxiufei.cn/Article/details/gtfebcucqa.html

[R59] 发 POST JSON
来源：http://dali.zycfv.cn/Article/details/gtewsozral.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jlsjyb.cn/Article/details/gtvddeqhxy.html

[R60] 只看 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gtdofdiuti.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiyvnbnad.html

[R61] 磁盘占用
来源：http://dali.xuetiantiany.cn/Article/details/gtkcnmyccx.html

df -h;  du -sh *
来源：http://dali.zhongyouzk.top/Article/details/gtuchcoudr.html

[R62] 找最占空间的文件
来源：http://dali.jianghu66.top/Article/details/gtqilaanrl.html

du -ah . | sort -rh | head -10
来源：http://dali.sysykeji.top/Article/details/gtlmgmyptp.html

[R63] 内存与进程
来源：http://dali.svipenyu.cn/Article/details/gtaqwwyatz.html

free -h;  ps aux | grep nginx
来源：http://dali.cdnleiting.top/Article/details/gtfjhhoozj.html

[R64] 结束进程
来源：http://dali.xuanzx.com/Article/details/gtuxvvsktv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.wangdashe.top/Article/details/gtlnntuvlw.html

[R65] 查看端口占用
来源：http://dali.nanxinkj.top/Article/details/gtkjbwhdjj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tian-w.cn/Article/details/gtkujaalay.html

[R66] 定时任务
来源：http://dali.sysykeji.top/Article/details/gtptqxmvqm.html

crontab -e;  crontab -l
来源：http://dali.hfpthk.cn/Article/details/gtzhwktlru.html

[R67] 生成随机十六进制串
来源：http://dali.gaohongyu789.top/Article/details/gtphkmdjtz.html

openssl rand -hex 16
来源：http://dali.gzhubu.top/Article/details/gthellqfmi.html

[R68] 计算文件校验值
来源：http://dali.jiagoushi.top/Article/details/gtqwulkejg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258888.top/Article/details/gtozklgmng.html

[R69] 生成随机密码
来源：http://dali.jqgfzy.top/Article/details/gtjztpctxg.html


<!-- 参考信息 -->