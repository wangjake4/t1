代发 wailian999

SELECT * FROM users;
来源：http://dali.meibo888.top/Article/details/gtmxvvdjfh.html

[Q16] 查询指定列
来源：http://dali.hongshengwenyu.top/Article/details/gtpevkqxmd.html

SELECT id, name FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugcgwtig.html

[Q17] 条件查询
来源：http://dali.zhixingplan.top/Article/details/gtotnwwxvl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenzaomai.com/Article/details/gtvcbocimq.html

[Q18] 模糊匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtakdevyqj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxuanxn.top/Article/details/gtxufminrn.html

[Q19] 范围查询
来源：http://dali.xylfe.cn/Article/details/gthcvsspik.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcemmteea.html

[Q20] IN 列表
来源：http://dali.cdnleiting.top/Article/details/gtszpvzhtc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xinyue.icu/Article/details/gtxrsiyvnr.html

[Q21] 空值判断
来源：http://dali.hammf.cn/Article/details/gtbsbfqmoa.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahpbuloa.html

[Q22] 排序
来源：http://dali.yueranfly.top/Article/details/gtfywltbqa.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.quarkkingdee.top/Article/details/gtlualpmbu.html

[Q23] 分页
来源：http://dali.wangshuangyany.cn/Article/details/gtsrgxlmvp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xinyue.icu/Article/details/gtjokwalnl.html

[Q24] 去重
来源：http://dali.pycfn.com/Article/details/gtvlxuphqf.html

SELECT DISTINCT city FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxiycaaoz.html

[Q25] 只取前 N 条
来源：http://dali.guowangkeji.top/Article/details/gtnfwexqmi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shzxlz.cn/Article/details/gtqucbwykg.html

[Q26] 计数
来源：http://dali.ybcxt.top/Article/details/gtddittste.html

SELECT COUNT(*) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtupvkxzhe.html

[Q27] 条件计数
来源：http://dali.birdmap.top/Article/details/gtdhambuby.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sysykeji.top/Article/details/gtiihcghfd.html

[Q28] 求和与平均
来源：http://dali.hywenlv.cn/Article/details/gtbcmmbyxx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gturzdspod.html

[Q29] 最大最小值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtjmufwi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtospmkuej.html

[Q30] 分组统计
来源：http://dali.vqdsnc.cn/Article/details/gthgtczlmk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtplufxdor.html

[Q31] 分组后过滤
来源：http://dali.tanke756.top/Article/details/gtjdiohfxo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.aibaodan.cn/Article/details/gtbqvsiknc.html

[Q32] 分组拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gtlzvdrkhl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpsegoaql.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yongpay.top/Article/details/gtdxhboszr.html

[Q33] 多列分组
来源：http://dali.gogol.net.cn/Article/details/gtsvbmraju.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nanxuanxn.top/Article/details/gtczbxosrv.html

[Q34] 每组取第一条
来源：http://dali.cucudq.cn/Article/details/gttfquwfev.html

SELECT * FROM (
来源：http://dali.xuanzx.com/Article/details/gtmoszoidc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xuanzx.com/Article/details/gtdztegpsc.html

) t WHERE rn = 1;
来源：http://dali.yuanzhike.top/Article/details/gtqratcyrx.html

[Q35] 内连接
来源：http://dali.zhiwuduotai.top/Article/details/gtgewoibqb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258.top/Article/details/gtczypulen.html

[Q36] 左连接
来源：http://dali.svipenyu.cn/Article/details/gtspgxpjpu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbvpamwam.html

[Q37] 右连接
来源：http://dali.gaohongyu789.top/Article/details/gtxidutnbx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.wangdashe.top/Article/details/gtvoiewnkg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xylfe.cn/Article/details/gtnpvaqdhu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yonumen.top/Article/details/gtbztxadbd.html

[Q39] 自连接（查上下级）
来源：http://dali.zhoulong.xyz/Article/details/gtaagedbet.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnqzz.top/Article/details/gtammrdpgx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinqigfzy.top/Article/details/gtlxonnxxu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.bjfxy.top/Article/details/gtdlnhkmvj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gttkoghdjy.html

[Q41] 多表连接
来源：http://dali.hnxiangtu.top/Article/details/gtjiyyyeho.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hammf.cn/Article/details/gtifutxbrx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gtphlxjszp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.quarkkingdee.top/Article/details/gtuqpzckaa.html

[Q42] 连接条件附加过滤
来源：http://dali.yonumen.top/Article/details/gtsphbhdcs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hysaishi.cn/Article/details/gtbimokkqn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yanxiufei.cn/Article/details/gthwfddfej.html

[Q43] 标量子查询
来源：http://dali.aizwys.cn/Article/details/gtuepwnani.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenlongwang.top/Article/details/gtnklwvhjm.html

[Q44] IN 子查询
来源：http://dali.cheryme.top/Article/details/gtsvlsvpvb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ybcxt.top/Article/details/gtsqxaojut.html

[Q45] EXISTS 判断存在
来源：http://dali.xziqi.cn/Article/details/gtpwghcdka.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhguzbkv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.nwbrower.top/Article/details/gtbhawhwwr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gttxgzfvjn.html

[Q47] 与平均值比较
来源：http://dali.hammf.cn/Article/details/gtswlvmydk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zdqjudy.top/Article/details/gtgpyrueng.html

[Q48] CTE 公用表表达式
来源：http://dali.chenzaomai.com/Article/details/gtjcuwsapm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cqqwz.cn/Article/details/gtmqkyexgo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tianlin.xyz/Article/details/gtyfyweunf.html

[Q49] 更新单行
来源：http://dali.ppjwa.cn/Article/details/gtnxaqhphs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gtolhgeywb.html

[Q50] 批量更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzncsshte.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tanke756.top/Article/details/gtcwafxprv.html

[Q51] 用子查询更新
来源：http://dali.snrcjt.cn/Article/details/gtclwdjwmx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenlongwang.top/Article/details/gtosdrpnbv.html

[Q52] 删除指定行
来源：http://dali.tianlin.xyz/Article/details/gtubwbcouw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tian-w.cn/Article/details/gtpdrwblew.html

[Q53] 按条件删除
来源：http://dali.sxryk.cn/Article/details/gtvirojyzd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.9152youxi.cn/Article/details/gtadfjphmw.html

[Q54] 清空表
来源：http://dali.snrcjt.cn/Article/details/gtjrkzosli.html

TRUNCATE TABLE logs;
来源：http://dali.jqgfzy.top/Article/details/gtwquojdjg.html

[Q55] 排名（并列占位）
来源：http://dali.wangshuangyany.cn/Article/details/gtjbyxjsow.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenjidiqi.icu/Article/details/gtodscbsxt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gaohongyu789.top/Article/details/gtbdpgtphd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvktgbnnj.html

[Q57] 行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzuwjpkfr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtodhuukwi.html

[Q58] 累计求和
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzqeycvk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtpssmwkhr.html

[Q59] 分组内累计
来源：http://dali.snrcjt.cn/Article/details/gtuxifwyev.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtsycwgoye.html

[Q60] 取上一行 / 下一行
来源：http://dali.nwbrower.top/Article/details/gtawqvqbew.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenjidiqi.icu/Article/details/gtsqolpkge.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gthimyrkew.html

[Q61] 移动平均
来源：http://dali.xziqi.cn/Article/details/gtgctutelw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtkfwtnxxb.html

[Q62] 分组占比
来源：http://dali.zdqjudy.top/Article/details/gtqfofwlwc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwenkfbx.html

[Q63] 开启事务
来源：http://dali.gzhubu.top/Article/details/gtdtcqwcqx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shzxlz.cn/Article/details/gtyhqeqwfu.html

[Q64] 提交事务
来源：http://dali.yueranfly.top/Article/details/gtvxiicwqz.html

COMMIT;
来源：http://dali.snrcjt.cn/Article/details/gthjsrmxhr.html

[Q65] 回滚事务
来源：http://dali.zhongyouzk.top/Article/details/gtbczndhsv.html

ROLLBACK;
来源：http://dali.jqgfzy.top/Article/details/gtijgtpfzl.html

[Q66] 行锁查询
来源：http://dali.jinqigufen.top/Article/details/gtayoallml.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhiwuduotai.top/Article/details/gtzosggdtu.html

[Q67] 设置隔离级别
来源：http://dali.yj20258.top/Article/details/gtwcfxngrr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxuanxn.top/Article/details/gthduviofy.html

[Q68] 保存点
来源：http://dali.316326.xyz/Article/details/gtzahtilct.html

SAVEPOINT sp1;
来源：http://dali.zdqjudy.top/Article/details/gtyzkjgnjm.html

ROLLBACK TO sp1;
来源：http://dali.aizwys.cn/Article/details/gtbaebwmqd.html

[Q69] 查看执行计划
来源：http://dali.mhx1999.top/Article/details/gtspdgcldv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.pycfn.com/Article/details/gtgqpugvnw.html

[Q70] 更新统计信息
来源：http://dali.tianlin.xyz/Article/details/gtwzzpbahs.html

ANALYZE TABLE users;
来源：http://dali.jinqigfzy.top/Article/details/gtftwmudhf.html

[Q71] 查看建表语句
来源：http://dali.shanyushiyangkeji.top/Article/details/gtluducgnl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ydzc1.top/Article/details/gtoddwoudq.html

[Q72] 查看索引
来源：http://dali.hammf.cn/Article/details/gtyiqvwlmx.html

SHOW INDEX FROM users;
来源：http://dali.sysykeji.top/Article/details/gtfwjfeddz.html

[Q73] 查看表状态
来源：http://dali.birdmap.top/Article/details/gtiwypbhtm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dashuyun.cn/Article/details/gtgczpaxqf.html

[Q74] 强制使用索引
来源：http://dali.jqgufenzy.top/Article/details/gtuxigffvq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.fzhhl.top/Article/details/gtmczxqokj.html

[Q75] 日期格式化
来源：http://dali.aibaodan.cn/Article/details/gtkmkdrqzp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gttepksdcp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cdnleiting.top/Article/details/gtabqpwpwo.html

[Q76] 按天统计
来源：http://dali.fzhhl.top/Article/details/gtrxdkhyqu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.fengsongda.top/Article/details/gtcwujxlkz.html

[Q77] 时间加减
来源：http://dali.meibo888.top/Article/details/gttsovbgne.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.vqdsnc.cn/Article/details/gtpgnifvbo.html

[Q78] 当前时间
来源：http://dali.jlsjyb.cn/Article/details/gtogreyqdt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigfzy.top/Article/details/gtyaohbxsp.html

[Q79] 字符串拼接
来源：http://dali.svipenyu.cn/Article/details/gtvovgajku.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhongyouzk.top/Article/details/gtcmrkmnlx.html

[Q80] 字符串截取
来源：http://dali.jianghu66.top/Article/details/gtnagwsgym.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtipscoojm.html

[Q81] 字符串替换
来源：http://dali.sysykeji.top/Article/details/gthsltjcaj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258.top/Article/details/gtvtgkyhgc.html

[Q82] 字符长度与字节长度
来源：http://dali.gaohongyu789.top/Article/details/gtljbxhike.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtkkaiqdzz.html

[Q83] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gtykytsewe.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtxvjvnjfn.html

[Q84] 去除首尾空格
来源：http://dali.xinyue.icu/Article/details/gtgcobpqln.html

SELECT TRIM(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtbdkphnke.html

[Q85] 数值取整
来源：http://dali.tian-w.cn/Article/details/gtkkszjkgm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gzhubu.top/Article/details/gtjttnhihq.html

[Q86] 读取 JSON 字段
来源：http://dali.xinyue.icu/Article/details/gtteqmrlth.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ehwqpu.com/Article/details/gthrjfieus.html

[Q87] JSON 字段做条件
来源：http://dali.xinyue.icu/Article/details/gtvnctecuu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.snrcjt.cn/Article/details/gtvhycmdwx.html

[Q88] 行转列（条件聚合）
来源：http://dali.aibaodan.cn/Article/details/gtznxzsdev.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhoulong.xyz/Article/details/gtickvjkwk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtyposdpzz.html

[Q89] 判断表是否存在
来源：http://dali.yuanzhike.top/Article/details/gtnbcberhh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtveokkxub.html

[Q90] 生成序号列
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjdvcnam.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxsvucrz.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtjxcccdgd.html

R. Bash 专题
来源：http://dali.xziqi.cn/Article/details/gtmprsnenp.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtuptldyex.html

[R01] shebang 与严格模式
来源：http://dali.hywenlv.cn/Article/details/gtqxvdvatb.html

#!/usr/bin/env bash
来源：http://dali.jqgufenzy.top/Article/details/gtaonzaqcq.html

set -euo pipefail
来源：http://dali.cashguo.top/Article/details/gtyuewcnes.html

[R02] 变量赋值与使用
来源：http://dali.cdnleiting.top/Article/details/gtuzheziig.html

name="Tom"; echo "$name"
来源：http://dali.dashuyun.cn/Article/details/gthmebknxx.html

[R03] 只读变量
来源：http://dali.guannengcc.top/Article/details/gtmoabipbs.html

readonly PI=3.14
来源：http://dali.shanyushiyangtech.top/Article/details/gtljiuilqm.html

[R04] 位置参数
来源：http://dali.xylfe.cn/Article/details/gteonayxlb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sxryk.cn/Article/details/gtczvjnxgg.html

[R05] 参数默认值
来源：http://dali.nanxuanxn.top/Article/details/gteilnfjou.html

name="${1:-default}"
来源：http://dali.xylfe.cn/Article/details/gtwbfzxmab.html

[R06] 判断命令是否存在
来源：http://dali.shzxlz.cn/Article/details/gtdohpbwow.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nwbrower.top/Article/details/gtsfiruoqb.html

[R07] if 判断文件
来源：http://dali.jqgufenzy.top/Article/details/gtlvcsssmn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.guannengcc.top/Article/details/gtzijeukxl.html

[R08] 数值比较
来源：http://dali.hywenlv.cn/Article/details/gtgmgflgsc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daxiang520.top/Article/details/gtzjmyazqu.html

[R09] 字符串比较
来源：http://dali.316326.xyz/Article/details/gtrpxytdnu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtdrdcmbvp.html

[R10] 正则匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtbwumkotc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.9152youxi.cn/Article/details/gtbvkpfzwy.html

[R11] case 多分支
来源：http://dali.chenjidiqi.icu/Article/details/gtfopfdnwj.html

case "$1" in
来源：http://dali.hysaishi.cn/Article/details/gtuhlrgqch.html

start) echo "启动" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylbrrwyw.html

stop)  echo "停止" ;;
来源：http://dali.vqdsnc.cn/Article/details/gttcjadlie.html

*)     echo "未知命令" ;;
来源：http://dali.andypj.xyz/Article/details/gtqiabbezb.html

esac
来源：http://dali.smart0.xyz/Article/details/gtdkhousem.html

[R12] for 遍历文件
来源：http://dali.svipenyu.cn/Article/details/gtanzinfat.html

for f in *.txt; do echo "$f"; done
来源：http://dali.haohaochexian.top/Article/details/gtqnjmxtvg.html

[R13] for 计数循环
来源：http://dali.cheryme.top/Article/details/gtevyynjuv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtampdwkhj.html

[R14] C 风格 for
来源：http://dali.mhx1999.top/Article/details/gtfjzkkvjn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtqiqnitpq.html

[R15] while 逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtgkamyakn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nwbrower.top/Article/details/gtcqqsmbup.html

[R16] until 等待条件
来源：http://dali.zdqjudy.top/Article/details/gtukfuhjbk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gtvnqnpnpu.html

[R17] 数组定义与取值
来源：http://dali.bjfxy.top/Article/details/gtyniczico.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jlsjyb.cn/Article/details/gtqxrpniio.html

[R18] 遍历数组
来源：http://dali.316326.xyz/Article/details/gtyaiywadx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cheryme.top/Article/details/gtcbfebcfj.html

[R19] 数组长度
来源：http://dali.daria6918.cn/Article/details/gtnnprcqzw.html

echo "${#arr[@]}"
来源：http://dali.ivvv.top/Article/details/gtnqfuwvgf.html

[R20] 关联数组（字典）
来源：http://dali.tanke756.top/Article/details/gtlrddccca.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cdnleiting.top/Article/details/gtseptrrgz.html

[R21] 字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtfxzstkop.html

echo "${#s}"
来源：http://dali.zhixingplan.top/Article/details/gtxyxabnsn.html

[R22] 截取子串
来源：http://dali.316326.xyz/Article/details/gtgaosuzrl.html

echo "${s:0:5}"
来源：http://dali.gzhubu.top/Article/details/gtandkeann.html

[R23] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gtenkozipr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dashuyun.cn/Article/details/gttcihfxli.html

[R24] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gtygxwuzgf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.meibo888.top/Article/details/gtohxpkyqk.html

[R25] 去后缀 / 去前缀
来源：http://dali.ehwqpu.com/Article/details/gttcytqrru.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ppjwa.cn/Article/details/gtojdxfkll.html

[R26] 命令替换
来源：http://dali.xylfe.cn/Article/details/gtthgtdobx.html

now=$(date +%F); echo "$now"
来源：http://dali.nanxuanxn.top/Article/details/gtxwmmzjrk.html

[R27] 算术展开
来源：http://dali.zhixingplan.top/Article/details/gtydayqbjj.html

echo $((1 + 2 * 3))
来源：http://dali.9152youxi.cn/Article/details/gtympgupfm.html

[R28] 浮点运算
来源：http://dali.jyoumei.cn/Article/details/gtovxvlgmm.html

echo "scale=2; 10/3" | bc
来源：http://dali.dianchejie.cn/Article/details/gtaasymafb.html

[R29] 定义函数
来源：http://dali.zhiwuduotai.top/Article/details/gtuxaqspnc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.kuanghao11.cn/Article/details/gtmzdbgzsp.html

[R30] 函数返回状态码
来源：http://dali.yanxiufei.cn/Article/details/gthyqejiwv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nanxuanxn.top/Article/details/gtbsvwblnb.html

[R31] 局部变量
来源：http://dali.pengpengdd.cyou/Article/details/gtvtoaewkx.html

f() { local x=1; echo "$x"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvaqiyzzj.html

[R32] 参数个数校验
来源：http://dali.jinghuilouyu.cn/Article/details/gtzugcqwxz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yvedp.cn/Article/details/gtkivgrzxi.html

[R33] 捕获错误并提示行号
来源：http://dali.aibaodan.cn/Article/details/gtudeebboh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tianlin.xyz/Article/details/gtlvswhlkj.html

[R34] 退出时清理
来源：http://dali.sufxvd.cn/Article/details/gtwtriuvvi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daria6918.cn/Article/details/gtuevqbmco.html

[R35] 后台执行并等待
来源：http://dali.chenlongwang.top/Article/details/gtchtchsaw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangdashe.top/Article/details/gtiqjbykhq.html

[R36] 并发执行多个任务
来源：http://dali.sysykeji.top/Article/details/gtgydfuvay.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenzaomai.com/Article/details/gtffzuwzej.html

[R37] 把输出赋给变量
来源：http://dali.c1oappe.top/Article/details/gtakdjfjoj.html

files=$(ls -1)
来源：http://dali.shuidangran.top/Article/details/gtsztbpcpy.html

[R38] 管道串联
来源：http://dali.kuanghao11.cn/Article/details/gtihvrlnfm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.wangshuangyany.cn/Article/details/gtlxrqrvmp.html

[R39] 重定向标准输出与错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaoxbmjwh.html

cmd > out.log 2>&1
来源：http://dali.fzhhl.top/Article/details/gtjvibbobo.html

[R40] 追加写日志
来源：http://dali.tian-w.cn/Article/details/gtgcypivhp.html

echo "log" >> out.log
来源：http://dali.gaohongyu789.top/Article/details/gtgpmgidvf.html

[R41] 丢弃输出
来源：http://dali.andypj.xyz/Article/details/gtlpwcoxiw.html

cmd >/dev/null 2>&1
来源：http://dali.quarkkingdee.top/Article/details/gtyavegevz.html

[R42] 输入重定向
来源：http://dali.316326.xyz/Article/details/gthovhhmab.html

wc -l < a.txt
来源：http://dali.nwbrower.top/Article/details/gtrkxamzmt.html

[R43] 按名字查找文件
来源：http://dali.redwolf501.top/Article/details/gtzatmltfd.html

find . -name "*.log" -type f
来源：http://dali.hammf.cn/Article/details/gtkckjofxt.html

[R44] 按修改时间查找
来源：http://dali.redwolf501.top/Article/details/gtjylkyhgy.html

find . -mtime -7 -type f
来源：http://dali.sweek.top/Article/details/gtizzqfsmu.html

[R45] 批量删除
来源：http://dali.jyoumei.cn/Article/details/gtkbgebcnw.html

find . -name "*.tmp" -delete
来源：http://dali.yangfankeji.com/Article/details/gtpnbpvmls.html

[R46] 递归替换文件内容
来源：http://dali.pengpengdd.cyou/Article/details/gtfytovobd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nanxuanxn.top/Article/details/gtcnkcvyis.html

[R47] sed 单行替换
来源：http://dali.aizwys.cn/Article/details/gtnoumaqad.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.aizwys.cn/Article/details/gtkamozkmu.html

[R48] awk 取指定列
来源：http://dali.nanxuanxn.top/Article/details/gtemigjrcz.html

awk '{print $1, $3}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gthxkshahn.html

[R49] awk 带条件
来源：http://dali.jlsjyb.cn/Article/details/gtgxkxckgh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhiwuduotai.top/Article/details/gtobeogecl.html

[R50] awk 求和
来源：http://dali.daria6918.cn/Article/details/gtwlqzxabj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtexklgpuc.html

[R51] 排序去重取前几
来源：http://dali.zhixingplan.top/Article/details/gtqcqqgqcp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhongyouzk.top/Article/details/gtqeutiodx.html

[R52] 统计行数
来源：http://dali.snrcjt.cn/Article/details/gtuyfbwzex.html

wc -l a.txt
来源：http://dali.ppjwa.cn/Article/details/gtmzqekdwk.html

[R53] 查看文件头与实时尾
来源：http://dali.shzxlz.cn/Article/details/gtfkdydsmo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.9152youxi.cn/Article/details/gtqpjbvkrm.html

[R54] 比较两个文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptbrsnea.html

diff a.txt b.txt
来源：http://dali.mhx1999.top/Article/details/gtrjkhqhgz.html

[R55] 压缩与解压
来源：http://dali.c1oappe.top/Article/details/gtweyfxnyb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xinyue.icu/Article/details/gtxmbyyitk.html

[R56] 远程拷贝
来源：http://dali.smart0.xyz/Article/details/gtajbsspku.html

scp file user@host:/path/
来源：http://dali.jyoumei.cn/Article/details/gteolkozpg.html

[R57] 远程执行命令
来源：http://dali.yuxming.cn/Article/details/gtnimuqlun.html

ssh user@host 'uptime'
来源：http://dali.sufxvd.cn/Article/details/gtdhqmbyix.html

[R58] 下载文件
来源：http://dali.cdnleiting.top/Article/details/gtqprkihzl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.mhx1999.top/Article/details/gtmodefkbg.html

[R59] 发 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gtpqkjxjyw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gtipuzctfp.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbknjzwsg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.havefunace.top/Article/details/gtsnsxejvq.html

[R61] 磁盘占用
来源：http://dali.gaohongyu789.top/Article/details/gtsgbmumgg.html

df -h;  du -sh *
来源：http://dali.birdmap.top/Article/details/gtadcgerym.html

[R62] 找最占空间的文件
来源：http://dali.cheryme.top/Article/details/gtsgufawul.html

du -ah . | sort -rh | head -10
来源：http://dali.haohaochexian.top/Article/details/gtpmqifolp.html

[R63] 内存与进程
来源：http://dali.yonumen.top/Article/details/gtlwiuyflp.html

free -h;  ps aux | grep nginx
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckatapzi.html

[R64] 结束进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlzjvzfe.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zycfv.cn/Article/details/gtvqtqpume.html

[R65] 查看端口占用
来源：http://dali.snrcjt.cn/Article/details/gtucujsqlw.html


<!-- 参考信息 -->