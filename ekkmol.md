代发 wailian999

SELECT * FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtwlqxpeks.html

[Q16] 查询指定列
来源：http://dali.yj20258.top/Article/details/gtspdpdhpb.html

SELECT id, name FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtrltvjmgz.html

[Q17] 条件查询
来源：http://dali.sxryk.cn/Article/details/gtuihksnfm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sxryk.cn/Article/details/gtousgaqsu.html

[Q18] 模糊匹配
来源：http://dali.zhoulong.xyz/Article/details/gtvtuuhnfp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.wangdashe.top/Article/details/gtewanvwri.html

[Q19] 范围查询
来源：http://dali.zhiwuduotai.top/Article/details/gtbgbrllsz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yanxiufei.cn/Article/details/gtdvasiyho.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gtleabagnu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgufenzy.top/Article/details/gtruujssim.html

[Q21] 空值判断
来源：http://dali.yongpay.top/Article/details/gtjmialebg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ydzc1.top/Article/details/gtoeexheir.html

[Q22] 排序
来源：http://dali.daria6918.cn/Article/details/gtgrgesqiu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yueranfly.top/Article/details/gtgeumdoui.html

[Q23] 分页
来源：http://dali.dashuyun.cn/Article/details/gthnqafddl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yangfankeji.com/Article/details/gtscmslvmu.html

[Q24] 去重
来源：http://dali.jianghu66.top/Article/details/gtncsmtpbi.html

SELECT DISTINCT city FROM users;
来源：http://dali.yongpay.top/Article/details/gtjwbmoaha.html

[Q25] 只取前 N 条
来源：http://dali.zdqjudy.top/Article/details/gtofcpiosa.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jqgufenzy.top/Article/details/gtpwpkxiyp.html

[Q26] 计数
来源：http://dali.ehwqpu.com/Article/details/gtwadwohay.html

SELECT COUNT(*) FROM users;
来源：http://dali.tanke756.top/Article/details/gthluqiczv.html

[Q27] 条件计数
来源：http://dali.hfpthk.cn/Article/details/gtcxfqihcv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangdashe.top/Article/details/gtlaaenngs.html

[Q28] 求和与平均
来源：http://dali.hnxiangtu.top/Article/details/gtigrdacyp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtoxdkdfui.html

[Q29] 最大最小值
来源：http://dali.smart0.xyz/Article/details/gtoifeksde.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtplwqzvnu.html

[Q30] 分组统计
来源：http://dali.jqgufenzy.top/Article/details/gtkmpdkmtj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gttdxdmphk.html

[Q31] 分组后过滤
来源：http://dali.daria6918.cn/Article/details/gtdpnypxqc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shzxlz.cn/Article/details/gtcnqcudao.html

[Q32] 分组拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtzisegofk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxngzakc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ydzc1.top/Article/details/gtkavrqcik.html

[Q33] 多列分组
来源：http://dali.xuetiantiany.cn/Article/details/gtlyuojgtb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.wangshuangyany.cn/Article/details/gthacsmjrb.html

[Q34] 每组取第一条
来源：http://dali.ehwqpu.com/Article/details/gtpcfynmky.html

SELECT * FROM (
来源：http://dali.haohaochexian.top/Article/details/gtubtfrqhj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yueranfly.top/Article/details/gtaejyzuji.html

) t WHERE rn = 1;
来源：http://dali.dashuyun.cn/Article/details/gtrwjzggrj.html

[Q35] 内连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktcwxhie.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cdnleiting.top/Article/details/gtmuexszlq.html

[Q36] 左连接
来源：http://dali.smart0.xyz/Article/details/gtoymrqyye.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvymjynqg.html

[Q37] 右连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgunwymfr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenjidiqi.icu/Article/details/gtkgdvxtyd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shuidangran.top/Article/details/gtsiuhkasq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gogol.net.cn/Article/details/gtfmyludku.html

[Q39] 自连接（查上下级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiandkpma.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jlsjyb.cn/Article/details/gtagsephxg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sxryk.cn/Article/details/gtnuxowyqr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.meibo888.top/Article/details/gtxpnrbohu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.smart0.xyz/Article/details/gtlggbpmij.html

[Q41] 多表连接
来源：http://dali.tanke756.top/Article/details/gtbgygzcdg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnqzz.top/Article/details/gtdqphbari.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gaohongyu789.top/Article/details/gtqizmtrbw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.pycfn.com/Article/details/gtyydzjemj.html

[Q42] 连接条件附加过滤
来源：http://dali.cashguo.top/Article/details/gtgzqryxrx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yvedp.cn/Article/details/gtfuhmsffh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aizwys.cn/Article/details/gtbaffiyqo.html

[Q43] 标量子查询
来源：http://dali.xuanzx.com/Article/details/gtczmtxeby.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgczcvvfw.html

[Q44] IN 子查询
来源：http://dali.dashuyun.cn/Article/details/gtxrhkmbvc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nanxuanxn.top/Article/details/gtjdufiemc.html

[Q45] EXISTS 判断存在
来源：http://dali.0kj1m.cn/Article/details/gtftjbeurb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gtlbijbzfq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gtdnoaqreu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gogol.net.cn/Article/details/gttsfbdsyb.html

[Q47] 与平均值比较
来源：http://dali.ehwqpu.com/Article/details/gtfuywqzzj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.daria6918.cn/Article/details/gtuvijmccd.html

[Q48] CTE 公用表表达式
来源：http://dali.ybcxt.top/Article/details/gtkhkvinwe.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.fzhhl.top/Article/details/gtsewvvuxm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.redwolf501.top/Article/details/gteixfdotd.html

[Q49] 更新单行
来源：http://dali.sweek.top/Article/details/gtrzlqaamk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cqqwz.cn/Article/details/gttkynghim.html

[Q50] 批量更新
来源：http://dali.bjfxy.top/Article/details/gtorxtmnsx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yonumen.top/Article/details/gthfkkpsvt.html

[Q51] 用子查询更新
来源：http://dali.jyoumei.cn/Article/details/gtymigcuej.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzyrpynz.html

[Q52] 删除指定行
来源：http://dali.yuxming.cn/Article/details/gtezqncqat.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtcvjosfte.html

[Q53] 按条件删除
来源：http://dali.jyoumei.cn/Article/details/gtwyjpcocy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.bjfxy.top/Article/details/gtzpuwwhzx.html

[Q54] 清空表
来源：http://dali.hnxiangtu.top/Article/details/gtmycpmzij.html

TRUNCATE TABLE logs;
来源：http://dali.gzhubu.top/Article/details/gtjejlyzlk.html

[Q55] 排名（并列占位）
来源：http://dali.xinyue.icu/Article/details/gtmyjuavyb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.bjfxy.top/Article/details/gtvhiznmts.html

[Q56] 密集排名（并列不占位）
来源：http://dali.svipenyu.cn/Article/details/gtienjraps.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tanke756.top/Article/details/gtnaqkgipi.html

[Q57] 行号
来源：http://dali.zdqjudy.top/Article/details/gtxvnirawn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yvedp.cn/Article/details/gtcvsfxole.html

[Q58] 累计求和
来源：http://dali.zhiwuduotai.top/Article/details/gthygrqibz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yonumen.top/Article/details/gtohgkpfdg.html

[Q59] 分组内累计
来源：http://dali.fzhhl.top/Article/details/gtxgnpayoy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gteerbpofs.html

[Q60] 取上一行 / 下一行
来源：http://dali.cheryme.top/Article/details/gttzegmazo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ehwqpu.com/Article/details/gtsvxphovo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtkvhoqpbv.html

[Q61] 移动平均
来源：http://dali.meibo888.top/Article/details/gtzedxccut.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtpsmrbomb.html

[Q62] 分组占比
来源：http://dali.chenlongwang.top/Article/details/gtwuftfzmf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gtrscrrdui.html

[Q63] 开启事务
来源：http://dali.cqqwz.cn/Article/details/gtbnzbvekb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yueranfly.top/Article/details/gtbbfzrwmd.html

[Q64] 提交事务
来源：http://dali.xuetiantiany.cn/Article/details/gtgcerrfxz.html

COMMIT;
来源：http://dali.yj20258888.top/Article/details/gtbrodfcfb.html

[Q65] 回滚事务
来源：http://dali.jiagoushi.top/Article/details/gtcsxscdri.html

ROLLBACK;
来源：http://dali.chenjidiqi.icu/Article/details/gtokujkabp.html

[Q66] 行锁查询
来源：http://dali.quarkkingdee.top/Article/details/gthbevuofr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gotoacloud.top/Article/details/gtmrgoumjp.html

[Q67] 设置隔离级别
来源：http://dali.cucudq.cn/Article/details/gtcadofgsa.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.bjfxy.top/Article/details/gtpswszjpj.html

[Q68] 保存点
来源：http://dali.cdnleiting.top/Article/details/gtzptxubtl.html

SAVEPOINT sp1;
来源：http://dali.gzhubu.top/Article/details/gtlehluzmp.html

ROLLBACK TO sp1;
来源：http://dali.hfpthk.cn/Article/details/gtdooanjgj.html

[Q69] 查看执行计划
来源：http://dali.zhongyouzk.top/Article/details/gtxisccsds.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.bjfxy.top/Article/details/gtrzbzsfie.html

[Q70] 更新统计信息
来源：http://dali.kuanghao11.cn/Article/details/gtjjumhzmj.html

ANALYZE TABLE users;
来源：http://dali.zhengqikj.top/Article/details/gtadfridcz.html

[Q71] 查看建表语句
来源：http://dali.yj20258.top/Article/details/gtrbhnfnxs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gaohongyu789.top/Article/details/gtofzcrgke.html

[Q72] 查看索引
来源：http://dali.yongpay.top/Article/details/gtlydsiyxg.html

SHOW INDEX FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtxmlraxrw.html

[Q73] 查看表状态
来源：http://dali.jyoumei.cn/Article/details/gtbhevbwbh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shangyingyoupin.top/Article/details/gtprrajkyw.html

[Q74] 强制使用索引
来源：http://dali.hfpthk.cn/Article/details/gtuhzadpea.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.9152youxi.cn/Article/details/gtrtzgtcjz.html

[Q75] 日期格式化
来源：http://dali.daria6918.cn/Article/details/gtqymkqana.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtothfjcxi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.bjfxy.top/Article/details/gthkrghkgo.html

[Q76] 按天统计
来源：http://dali.zhongyouzk.top/Article/details/gtzxzeujex.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.guannengcc.top/Article/details/gtegmdfxzq.html

[Q77] 时间加减
来源：http://dali.svipenyu.cn/Article/details/gtfmfcxrcw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gtfhudlmxb.html

[Q78] 当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtcokhpkgb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.quarkkingdee.top/Article/details/gtbqzwrejl.html

[Q79] 字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gtxslnlxcr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.meibo888.top/Article/details/gtvzsbbpag.html

[Q80] 字符串截取
来源：http://dali.zhoulong.xyz/Article/details/gtnwvdmxnd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtcjnmjxek.html

[Q81] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gtwlizpizs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtqdhkacfs.html

[Q82] 字符长度与字节长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqpwtgnw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtwhsikatn.html

[Q83] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gtkpjfguza.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtnxkdlgmr.html

[Q84] 去除首尾空格
来源：http://dali.hammf.cn/Article/details/gtqchuuplp.html

SELECT TRIM(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdsijwuo.html

[Q85] 数值取整
来源：http://dali.c1oappe.top/Article/details/gtjregcizc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangshuangyany.cn/Article/details/gttdfhfcey.html

[Q86] 读取 JSON 字段
来源：http://dali.zhiwuduotai.top/Article/details/gtarkivwzb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jyoumei.cn/Article/details/gtbubhnvkd.html

[Q87] JSON 字段做条件
来源：http://dali.aizwys.cn/Article/details/gtggdjtibf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cdnleiting.top/Article/details/gtgblbgush.html

[Q88] 行转列（条件聚合）
来源：http://dali.xziqi.cn/Article/details/gtfnegelzd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yonumen.top/Article/details/gtujlesbsy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cheryme.top/Article/details/gtctjlqlhj.html

[Q89] 判断表是否存在
来源：http://dali.pycfn.com/Article/details/gttphgkelr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cqqwz.cn/Article/details/gtyakthsxo.html

[Q90] 生成序号列
来源：http://dali.feifeiyinyue.top/Article/details/gtijwvynag.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.guowangkeji.top/Article/details/gtuyfbgaer.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtiknstvtu.html

R. Bash 专题
来源：http://dali.smart0.xyz/Article/details/gtgtwblpfl.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtqdqttbza.html

[R01] shebang 与严格模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfyrxxgdw.html

#!/usr/bin/env bash
来源：http://dali.sysykeji.top/Article/details/gthftscvow.html

set -euo pipefail
来源：http://dali.gogol.net.cn/Article/details/gtwkglqxjt.html

[R02] 变量赋值与使用
来源：http://dali.hnxiangtu.top/Article/details/gtohbceoqr.html

name="Tom"; echo "$name"
来源：http://dali.zhixingplan.top/Article/details/gtpmfcqnem.html

[R03] 只读变量
来源：http://dali.hongshengwenyu.top/Article/details/gtncpwnvei.html

readonly PI=3.14
来源：http://dali.hfpthk.cn/Article/details/gtzdxchksx.html

[R04] 位置参数
来源：http://dali.quarkkingdee.top/Article/details/gtugepdnbu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sweek.top/Article/details/gtmthbrlnm.html

[R05] 参数默认值
来源：http://dali.xylfe.cn/Article/details/gtfctpcvov.html

name="${1:-default}"
来源：http://dali.mhx1999.top/Article/details/gtwsofpwtj.html

[R06] 判断命令是否存在
来源：http://dali.ppjwa.cn/Article/details/gttostjvmv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jyoumei.cn/Article/details/gtnflhotkc.html

[R07] if 判断文件
来源：http://dali.jyoumei.cn/Article/details/gtdsqjrhrv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fzhhl.top/Article/details/gtyvjrknxg.html

[R08] 数值比较
来源：http://dali.smart0.xyz/Article/details/gtslnsjica.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nwbrower.top/Article/details/gtcfsrshby.html

[R09] 字符串比较
来源：http://dali.jlsjyb.cn/Article/details/gtwnwpqqgm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.smart0.xyz/Article/details/gtwecvgtvi.html

[R10] 正则匹配
来源：http://dali.yvedp.cn/Article/details/gthazzhxup.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gttwzxnrgu.html

[R11] case 多分支
来源：http://dali.jinqigufen.top/Article/details/gtondzpryy.html

case "$1" in
来源：http://dali.tianlin.xyz/Article/details/gtgkqdhjiq.html

start) echo "启动" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtulmaldzz.html

stop)  echo "停止" ;;
来源：http://dali.tanke756.top/Article/details/gthtsuvaud.html

*)     echo "未知命令" ;;
来源：http://dali.nanxuanxn.top/Article/details/gtbaukgbvf.html

esac
来源：http://dali.zhengqikj.top/Article/details/gtfghothgg.html

[R12] for 遍历文件
来源：http://dali.pengpengdd.cyou/Article/details/gtadfdpcex.html

for f in *.txt; do echo "$f"; done
来源：http://dali.dashuyun.cn/Article/details/gtrpvyerni.html

[R13] for 计数循环
来源：http://dali.havefunace.top/Article/details/gteejidufv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gtrnlkiyfj.html

[R14] C 风格 for
来源：http://dali.andypj.xyz/Article/details/gtxtaxsjkl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gtppbeazuj.html

[R15] while 逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtuehdpunm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yvedp.cn/Article/details/gtnzkbnrff.html

[R16] until 等待条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzjbmfld.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gtytuonvon.html

[R17] 数组定义与取值
来源：http://dali.snrcjt.cn/Article/details/gtsnhdryun.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ehwqpu.com/Article/details/gtuhupkuon.html

[R18] 遍历数组
来源：http://dali.meibo888.top/Article/details/gtpuwshvmw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daria6918.cn/Article/details/gtinwweddv.html

[R19] 数组长度
来源：http://dali.yuxming.cn/Article/details/gtamngmujt.html

echo "${#arr[@]}"
来源：http://dali.pengpengdd.cyou/Article/details/gtsxqavgid.html

[R20] 关联数组（字典）
来源：http://dali.jqgfzy.top/Article/details/gtcfsdevxo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.andypj.xyz/Article/details/gtcesigowk.html

[R21] 字符串长度
来源：http://dali.svipenyu.cn/Article/details/gtjutbbios.html

echo "${#s}"
来源：http://dali.zhiwuduotai.top/Article/details/gtjgmmwpeb.html

[R22] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gthymojwno.html

echo "${s:0:5}"
来源：http://dali.gotoacloud.top/Article/details/gtzpvmbsbv.html

[R23] 字符串替换
来源：http://dali.fengsongda.top/Article/details/gtlptvnemo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nwbrower.top/Article/details/gtrvjorfjs.html

[R24] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gtuyoqdkxo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jiagoushi.top/Article/details/gtapsnmhxl.html

[R25] 去后缀 / 去前缀
来源：http://dali.yueranfly.top/Article/details/gtjpdxybac.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.birdmap.top/Article/details/gtfkqsvkxe.html

[R26] 命令替换
来源：http://dali.quarkkingdee.top/Article/details/gtlczmcoyb.html

now=$(date +%F); echo "$now"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkloodmii.html

[R27] 算术展开
来源：http://dali.9152youxi.cn/Article/details/gtrnyndjdz.html

echo $((1 + 2 * 3))
来源：http://dali.guowangkeji.top/Article/details/gttshyhsog.html

[R28] 浮点运算
来源：http://dali.gotoacloud.top/Article/details/gttkhryocy.html

echo "scale=2; 10/3" | bc
来源：http://dali.shzxlz.cn/Article/details/gtdaentwpz.html

[R29] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gtmabnoybj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangshuangyany.cn/Article/details/gtpsdgrhab.html

[R30] 函数返回状态码
来源：http://dali.jqgufenzy.top/Article/details/gtgiljfyov.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigufen.top/Article/details/gtjozqgtac.html

[R31] 局部变量
来源：http://dali.sxryk.cn/Article/details/gttcnktmba.html

f() { local x=1; echo "$x"; }
来源：http://dali.bjfxy.top/Article/details/gtlxbingdh.html

[R32] 参数个数校验
来源：http://dali.chenzaomai.com/Article/details/gtmsqgmpav.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gtqamtvqih.html

[R33] 捕获错误并提示行号
来源：http://dali.jianghu66.top/Article/details/gtzoxroemu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hfpthk.cn/Article/details/gtklmrxwvi.html

[R34] 退出时清理
来源：http://dali.gzhubu.top/Article/details/gtuephvzst.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gtjhmvvswk.html

[R35] 后台执行并等待
来源：http://dali.vqdsnc.cn/Article/details/gtsdrxfbvp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shuidangran.top/Article/details/gtptnnqhna.html

[R36] 并发执行多个任务
来源：http://dali.guannengcc.top/Article/details/gtzxzhnoyl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.kuanghao11.cn/Article/details/gtneiiadfu.html

[R37] 把输出赋给变量
来源：http://dali.shuidangran.top/Article/details/gtwicnmqpz.html

files=$(ls -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtbjctlrxr.html

[R38] 管道串联
来源：http://dali.yongpay.top/Article/details/gtfxrihxvg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinghuilouyu.cn/Article/details/gtahjknsew.html

[R39] 重定向标准输出与错误
来源：http://dali.daxiang520.top/Article/details/gtiizjxegt.html

cmd > out.log 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gttkziojrb.html

[R40] 追加写日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxbfgjgn.html

echo "log" >> out.log
来源：http://dali.316326.xyz/Article/details/gtumkmjbqi.html

[R41] 丢弃输出
来源：http://dali.smart0.xyz/Article/details/gtuleeaxsh.html

cmd >/dev/null 2>&1
来源：http://dali.yuanzhike.top/Article/details/gtiwapzxlk.html

[R42] 输入重定向
来源：http://dali.jyoumei.cn/Article/details/gtrrwleyno.html

wc -l < a.txt
来源：http://dali.yuxming.cn/Article/details/gtpexkywkj.html

[R43] 按名字查找文件
来源：http://dali.gaohongyu789.top/Article/details/gtlhtqcxfd.html

find . -name "*.log" -type f
来源：http://dali.haohaochexian.top/Article/details/gtdcdchxhp.html

[R44] 按修改时间查找
来源：http://dali.gzhubu.top/Article/details/gttofbaepj.html

find . -mtime -7 -type f
来源：http://dali.wangdashe.top/Article/details/gtwtjrmakb.html

[R45] 批量删除
来源：http://dali.jyoumei.cn/Article/details/gtvpyvpwok.html

find . -name "*.tmp" -delete
来源：http://dali.aizwys.cn/Article/details/gtmeinhyun.html

[R46] 递归替换文件内容
来源：http://dali.ppjwa.cn/Article/details/gthuqeiltm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.andypj.xyz/Article/details/gtbppwaquf.html

[R47] sed 单行替换
来源：http://dali.aibaodan.cn/Article/details/gtpbjaiqqt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.snrcjt.cn/Article/details/gtlvyfuvqz.html

[R48] awk 取指定列
来源：http://dali.zdqjudy.top/Article/details/gthheqjfse.html

awk '{print $1, $3}' a.txt
来源：http://dali.ydzc1.top/Article/details/gtnnubwhow.html

[R49] awk 带条件
来源：http://dali.yj202588.top/Article/details/gtornpvoyg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yvedp.cn/Article/details/gthcbdoltq.html

[R50] awk 求和
来源：http://dali.cdnleiting.top/Article/details/gtqbbnsyom.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtmoafxoac.html

[R51] 排序去重取前几
来源：http://dali.zdqjudy.top/Article/details/gtvafancjr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gtfjuruiam.html

[R52] 统计行数
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvgdzxoc.html

wc -l a.txt
来源：http://dali.hnxiangtu.top/Article/details/gttqvkgghk.html

[R53] 查看文件头与实时尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkvrfrzq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.c1oappe.top/Article/details/gtvtuhiikl.html

[R54] 比较两个文件
来源：http://dali.svipenyu.cn/Article/details/gtjrcclgap.html

diff a.txt b.txt
来源：http://dali.hnqzz.top/Article/details/gtvwimvpjt.html

[R55] 压缩与解压
来源：http://dali.kuanghao11.cn/Article/details/gttzwyrlum.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daria6918.cn/Article/details/gtbpsremni.html

[R56] 远程拷贝
来源：http://dali.gaohongyu789.top/Article/details/gthslsguud.html

scp file user@host:/path/
来源：http://dali.shuidangran.top/Article/details/gtujxtesbw.html

[R57] 远程执行命令
来源：http://dali.nanxinkj.top/Article/details/gtjxghvldv.html

ssh user@host 'uptime'
来源：http://dali.hongshengwenyu.top/Article/details/gtqcywvbfd.html

[R58] 下载文件
来源：http://dali.yangfankeji.com/Article/details/gtztmdulqs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhiwuduotai.top/Article/details/gtsunmhhjy.html

[R59] 发 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzfruhkn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangshuangyany.cn/Article/details/gtgmuqijjk.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gtclhfodbq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.haohaochexian.top/Article/details/gtrrbiyrvv.html

[R61] 磁盘占用
来源：http://dali.dashuyun.cn/Article/details/gteqlnhxxb.html

df -h;  du -sh *
来源：http://dali.tanke756.top/Article/details/gtnynhtrnr.html

[R62] 找最占空间的文件
来源：http://dali.yvedp.cn/Article/details/gtvpffhcef.html

du -ah . | sort -rh | head -10
来源：http://dali.shangyingyoupin.top/Article/details/gtdklakqbk.html

[R63] 内存与进程
来源：http://dali.hnxiangtu.top/Article/details/gtgdflfhdy.html

free -h;  ps aux | grep nginx
来源：http://dali.hongshengwenyu.top/Article/details/gtjgqjyblr.html

[R64] 结束进程
来源：http://dali.wangdashe.top/Article/details/gtkkltfaxj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.c1oappe.top/Article/details/gtigcecfuc.html

[R65] 查看端口占用
来源：http://dali.xziqi.cn/Article/details/gtdnkpcugk.html


<!-- 参考信息 -->