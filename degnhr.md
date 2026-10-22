代发 wailian999

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xinyue.icu/Article/details/gtaoynzxoq.html

[Q26] 计数
来源：http://dali.hammf.cn/Article/details/gtdknvlman.html

SELECT COUNT(*) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtxthjwulp.html

[Q27] 条件计数
来源：http://dali.xuanzx.com/Article/details/gtytvwlkjn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nwbrower.top/Article/details/gtijagnvrm.html

[Q28] 求和与平均
来源：http://dali.316326.xyz/Article/details/gtxtjttqbr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtmkpeacwx.html

[Q29] 最大最小值
来源：http://dali.c1oappe.top/Article/details/gthvlostcx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.pycfn.com/Article/details/gtigsohdcw.html

[Q30] 分组统计
来源：http://dali.cdnleiting.top/Article/details/gtjpwaaqdj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtsnzgpzaa.html

[Q31] 分组后过滤
来源：http://dali.sweek.top/Article/details/gttyjbwphr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhongyouzk.top/Article/details/gtcpnqfepd.html

[Q32] 分组拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtzsdqhyil.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gtfrauhvuw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xziqi.cn/Article/details/gtnrijqoor.html

[Q33] 多列分组
来源：http://dali.yj20258.top/Article/details/gtpeqvpnmz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.redwolf501.top/Article/details/gtlmlifosp.html

[Q34] 每组取第一条
来源：http://dali.wangdashe.top/Article/details/gtpkitrnws.html

SELECT * FROM (
来源：http://dali.xziqi.cn/Article/details/gtqjevmahe.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.smart0.xyz/Article/details/gttvqfesje.html

) t WHERE rn = 1;
来源：http://dali.xziqi.cn/Article/details/gtwthhxjig.html

[Q35] 内连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlrrdzqq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gtmbjokdxx.html

[Q36] 左连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxuitelb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjosrjabs.html

[Q37] 右连接
来源：http://dali.andypj.xyz/Article/details/gtvnnyokdg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nwbrower.top/Article/details/gtucdtyida.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ydzc1.top/Article/details/gtyctgtxtm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.9152youxi.cn/Article/details/gtncyldksz.html

[Q39] 自连接（查上下级）
来源：http://dali.jianghu66.top/Article/details/gtkubjchnz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ppjwa.cn/Article/details/gtspxeyylo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.haohaochexian.top/Article/details/gtdevimhao.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nwbrower.top/Article/details/gtdjsoubyq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinqigufen.top/Article/details/gtywlecvrb.html

[Q41] 多表连接
来源：http://dali.zhengqikj.top/Article/details/gtvgdwemxa.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nwbrower.top/Article/details/gtneozusbv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.quarkkingdee.top/Article/details/gtjdppquie.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtybebegyb.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxinkj.top/Article/details/gtudkgngrv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nanxinkj.top/Article/details/gtylfqvhtv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.redwolf501.top/Article/details/gtskvrrvld.html

[Q43] 标量子查询
来源：http://dali.svipenyu.cn/Article/details/gtympylhwv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.fengsongda.top/Article/details/gtvypgauwz.html

[Q44] IN 子查询
来源：http://dali.xylfe.cn/Article/details/gtsswelyan.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hywenlv.cn/Article/details/gtykigcpvj.html

[Q45] EXISTS 判断存在
来源：http://dali.sweek.top/Article/details/gtwqqxqvxm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gtgkbouivh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hnxiangtu.top/Article/details/gtmucsfksc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jyoumei.cn/Article/details/gtzggjhvot.html

[Q47] 与平均值比较
来源：http://dali.andypj.xyz/Article/details/gtpcxwwypd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.redwolf501.top/Article/details/gtaruuhbuq.html

[Q48] CTE 公用表表达式
来源：http://dali.zycfv.cn/Article/details/gttikfcdlu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.haohaochexian.top/Article/details/gtpfywirhl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtziibxmyg.html

[Q49] 更新单行
来源：http://dali.kuanghao11.cn/Article/details/gtvntpiump.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gtdaadyngr.html

[Q50] 批量更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtlppbekym.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.dianchejie.cn/Article/details/gtojpnknxj.html

[Q51] 用子查询更新
来源：http://dali.redwolf501.top/Article/details/gtxivdtmyi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqpzxkjii.html

[Q52] 删除指定行
来源：http://dali.dashuyun.cn/Article/details/gtotdrsubg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gtrtfvvmyp.html

[Q53] 按条件删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiobfhqhg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xinyue.icu/Article/details/gtirbfesbh.html

[Q54] 清空表
来源：http://dali.yuanzhike.top/Article/details/gtiynociwq.html

TRUNCATE TABLE logs;
来源：http://dali.cucudq.cn/Article/details/gthcscklit.html

[Q55] 排名（并列占位）
来源：http://dali.ydzc1.top/Article/details/gtgpsjgejd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gtcbtqkvnm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnqzz.top/Article/details/gtkzgnwthn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.snrcjt.cn/Article/details/gtdhldeyfw.html

[Q57] 行号
来源：http://dali.yangfankeji.com/Article/details/gtawgwetql.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xinyue.icu/Article/details/gtpbfthirb.html

[Q58] 累计求和
来源：http://dali.vqdsnc.cn/Article/details/gtfyahkiry.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtytuxmnti.html

[Q59] 分组内累计
来源：http://dali.gzhubu.top/Article/details/gtbghlcdyh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.meibo888.top/Article/details/gtpanrhsdl.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigfzy.top/Article/details/gtbqvgktfj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pengpengdd.cyou/Article/details/gtgjdxcuon.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtimizthmo.html

[Q61] 移动平均
来源：http://dali.hongshengwenyu.top/Article/details/gtnuaxsaon.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtiyzqbgyl.html

[Q62] 分组占比
来源：http://dali.svipenyu.cn/Article/details/gtjsfgqdpl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gttugnzepa.html

[Q63] 开启事务
来源：http://dali.xylfe.cn/Article/details/gtgyouasyw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cdnleiting.top/Article/details/gtgnpavjec.html

[Q64] 提交事务
来源：http://dali.redwolf501.top/Article/details/gtkjwcogzh.html

COMMIT;
来源：http://dali.zhongyouzk.top/Article/details/gtkldqlewm.html

[Q65] 回滚事务
来源：http://dali.cashguo.top/Article/details/gtcjlryeci.html

ROLLBACK;
来源：http://dali.jiagoushi.top/Article/details/gtlfzkkghm.html

[Q66] 行锁查询
来源：http://dali.chenjidiqi.icu/Article/details/gtfaltzvkg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yongpay.top/Article/details/gtizgankeq.html

[Q67] 设置隔离级别
来源：http://dali.jinqigufen.top/Article/details/gtcqasyqno.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aizwys.cn/Article/details/gtovtzqmbb.html

[Q68] 保存点
来源：http://dali.jqgfzy.top/Article/details/gtphiwgcrt.html

SAVEPOINT sp1;
来源：http://dali.jiagoushi.top/Article/details/gtrgmklftu.html

ROLLBACK TO sp1;
来源：http://dali.cashguo.top/Article/details/gtludcdddp.html

[Q69] 查看执行计划
来源：http://dali.chenlongwang.top/Article/details/gtujgqibrg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cdnleiting.top/Article/details/gtfeqbbjie.html

[Q70] 更新统计信息
来源：http://dali.0kj1m.cn/Article/details/gtsngegghg.html

ANALYZE TABLE users;
来源：http://dali.pengpengdd.cyou/Article/details/gtlseivwpx.html

[Q71] 查看建表语句
来源：http://dali.ivvv.top/Article/details/gtklbvfryt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jyoumei.cn/Article/details/gtffqvcjki.html

[Q72] 查看索引
来源：http://dali.hnxiangtu.top/Article/details/gtxwfqjpbk.html

SHOW INDEX FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtzitqahug.html

[Q73] 查看表状态
来源：http://dali.yj202588.top/Article/details/gtihjgsmrf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.havefunace.top/Article/details/gthwjijetd.html

[Q74] 强制使用索引
来源：http://dali.nanxinkj.top/Article/details/gtluyktpzp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinqigufen.top/Article/details/gtzqegjnhr.html

[Q75] 日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gtdzipxhmb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtcbfmdbyu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jianghu66.top/Article/details/gtvvvwwfan.html

[Q76] 按天统计
来源：http://dali.andypj.xyz/Article/details/gtewfhcdeb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yongpay.top/Article/details/gtdgyayrfd.html

[Q77] 时间加减
来源：http://dali.hongshengwenyu.top/Article/details/gtzkrlcdux.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fzhhl.top/Article/details/gtzqjcjdyy.html

[Q78] 当前时间
来源：http://dali.zhoulong.xyz/Article/details/gtwddsvmlk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yvedp.cn/Article/details/gtumycikmz.html

[Q79] 字符串拼接
来源：http://dali.ppjwa.cn/Article/details/gtyrevpqhw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zdqjudy.top/Article/details/gtszcmeune.html

[Q80] 字符串截取
来源：http://dali.ivvv.top/Article/details/gtquaqkpyc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtgvdvjrmv.html

[Q81] 字符串替换
来源：http://dali.iojbl.cn/Article/details/gtescqkqlo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtwodlzrhg.html

[Q82] 字符长度与字节长度
来源：http://dali.yuanzhike.top/Article/details/gtqeaalszd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtixwuqzph.html

[Q83] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gtilueuudy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtlqagqesa.html

[Q84] 去除首尾空格
来源：http://dali.sxryk.cn/Article/details/gtuzdvmxwg.html

SELECT TRIM(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtumocmequ.html

[Q85] 数值取整
来源：http://dali.svipenyu.cn/Article/details/gtfzjcavkr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zycfv.cn/Article/details/gtbbcinbgd.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258888.top/Article/details/gtacvehiem.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sxryk.cn/Article/details/gtajxrunrs.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gttuqpbqjz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yuxming.cn/Article/details/gtoihnvvih.html

[Q88] 行转列（条件聚合）
来源：http://dali.kuanghao11.cn/Article/details/gtgxhpipjj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jqgufenzy.top/Article/details/gtqualwfpa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yongpay.top/Article/details/gtckcoqcrw.html

[Q89] 判断表是否存在
来源：http://dali.pycfn.com/Article/details/gtccpirbxg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gtotsnajnh.html

[Q90] 生成序号列
来源：http://dali.wangdashe.top/Article/details/gtshrgmukq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinqigfzy.top/Article/details/gtqczgnxnw.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtjmgwxxja.html

R. Bash 专题
来源：http://dali.nwbrower.top/Article/details/gtsxxgsocs.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtogmjizal.html

[R01] shebang 与严格模式
来源：http://dali.yueranfly.top/Article/details/gtlabfofva.html

#!/usr/bin/env bash
来源：http://dali.jinghuilouyu.cn/Article/details/gtnuahtaae.html

set -euo pipefail
来源：http://dali.pycfn.com/Article/details/gthuvyiwkb.html

[R02] 变量赋值与使用
来源：http://dali.gzhubu.top/Article/details/gtyiauiofy.html

name="Tom"; echo "$name"
来源：http://dali.hnqzz.top/Article/details/gtgumblydl.html

[R03] 只读变量
来源：http://dali.hammf.cn/Article/details/gthydqasuf.html

readonly PI=3.14
来源：http://dali.jinqigufen.top/Article/details/gtasyeitid.html

[R04] 位置参数
来源：http://dali.redwolf501.top/Article/details/gtnpiybdto.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxinkj.top/Article/details/gtqxwaiwft.html

[R05] 参数默认值
来源：http://dali.hywenlv.cn/Article/details/gtqpqavizt.html

name="${1:-default}"
来源：http://dali.ivvv.top/Article/details/gthkvhwyhe.html

[R06] 判断命令是否存在
来源：http://dali.gzhubu.top/Article/details/gtdocnbicz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinqigfzy.top/Article/details/gtdtthfnxj.html

[R07] if 判断文件
来源：http://dali.jinqigufen.top/Article/details/gtdhjytkdv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.redwolf501.top/Article/details/gtmpudmbtj.html

[R08] 数值比较
来源：http://dali.zhixingplan.top/Article/details/gtjmzrvnex.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nwbrower.top/Article/details/gtralksbze.html

[R09] 字符串比较
来源：http://dali.yj202588.top/Article/details/gtnromdjsm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ivvv.top/Article/details/gtipfetfhn.html

[R10] 正则匹配
来源：http://dali.316326.xyz/Article/details/gtvpsdsfph.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqypnica.html

[R11] case 多分支
来源：http://dali.jinghuilouyu.cn/Article/details/gtyugevamr.html

case "$1" in
来源：http://dali.316326.xyz/Article/details/gtvnelhxra.html

start) echo "启动" ;;
来源：http://dali.ivvv.top/Article/details/gtzfcotmlt.html

stop)  echo "停止" ;;
来源：http://dali.shzxlz.cn/Article/details/gtzfzpgafs.html

*)     echo "未知命令" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gtbsnkyysz.html

esac
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmanayek.html

[R12] for 遍历文件
来源：http://dali.cqqwz.cn/Article/details/gtupotocqf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jianghu66.top/Article/details/gtzkddzxva.html

[R13] for 计数循环
来源：http://dali.jlsjyb.cn/Article/details/gtznhrxjvv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gtqgwfltix.html

[R14] C 风格 for
来源：http://dali.wangdashe.top/Article/details/gtwmbpauql.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gtadwqwiqv.html

[R15] while 逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtkattxavf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.dianchejie.cn/Article/details/gtaorovpbz.html

[R16] until 等待条件
来源：http://dali.jiagoushi.top/Article/details/gtbnqfnxpf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gtpflwnjlq.html

[R17] 数组定义与取值
来源：http://dali.smart0.xyz/Article/details/gtbqmhrklx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jianghu66.top/Article/details/gthcirxpwg.html

[R18] 遍历数组
来源：http://dali.xziqi.cn/Article/details/gtrxmwfqks.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dashuyun.cn/Article/details/gtsmxarmpq.html

[R19] 数组长度
来源：http://dali.yongpay.top/Article/details/gtilekzowu.html

echo "${#arr[@]}"
来源：http://dali.haohaochexian.top/Article/details/gtavncgovo.html

[R20] 关联数组（字典）
来源：http://dali.sufxvd.cn/Article/details/gtbvugvkgd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.feifeiyinyue.top/Article/details/gtlbbmdhhg.html

[R21] 字符串长度
来源：http://dali.tanke756.top/Article/details/gtyhmzmfna.html

echo "${#s}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbbbtemv.html

[R22] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gtkfzzpqhv.html

echo "${s:0:5}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmiygvpil.html

[R23] 字符串替换
来源：http://dali.hysaishi.cn/Article/details/gtmrvkasbq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.vqdsnc.cn/Article/details/gtujyxecja.html

[R24] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gtbxmfpnrk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sxryk.cn/Article/details/gtypmeuvvu.html

[R25] 去后缀 / 去前缀
来源：http://dali.pycfn.com/Article/details/gtddhniada.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigfzy.top/Article/details/gtfaamrhnz.html

[R26] 命令替换
来源：http://dali.sxryk.cn/Article/details/gtkitofvdk.html

now=$(date +%F); echo "$now"
来源：http://dali.aibaodan.cn/Article/details/gtaomdflba.html

[R27] 算术展开
来源：http://dali.jyoumei.cn/Article/details/gtpmgqnfml.html

echo $((1 + 2 * 3))
来源：http://dali.tianlin.xyz/Article/details/gtlgqabygi.html

[R28] 浮点运算
来源：http://dali.snrcjt.cn/Article/details/gtktxwibsg.html

echo "scale=2; 10/3" | bc
来源：http://dali.aibaodan.cn/Article/details/gtarmqcaei.html

[R29] 定义函数
来源：http://dali.cashguo.top/Article/details/gtughssiij.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aizwys.cn/Article/details/gtkweobcbd.html

[R30] 函数返回状态码
来源：http://dali.cucudq.cn/Article/details/gttarfrlbt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gotoacloud.top/Article/details/gtzoutxzdm.html

[R31] 局部变量
来源：http://dali.hnxiangtu.top/Article/details/gthbjjydcx.html

f() { local x=1; echo "$x"; }
来源：http://dali.yonumen.top/Article/details/gtxiechnzb.html

[R32] 参数个数校验
来源：http://dali.aibaodan.cn/Article/details/gtrutpvwsf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xylfe.cn/Article/details/gtdkskinnr.html

[R33] 捕获错误并提示行号
来源：http://dali.zhiwuduotai.top/Article/details/gtqqyptpvr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xylfe.cn/Article/details/gtldpgdtbk.html

[R34] 退出时清理
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpxblabb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tianlin.xyz/Article/details/gtepzsabra.html

[R35] 后台执行并等待
来源：http://dali.havefunace.top/Article/details/gteoahakec.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ehwqpu.com/Article/details/gtarsgmzpk.html

[R36] 并发执行多个任务
来源：http://dali.zhengqikj.top/Article/details/gtrfcvetcd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.meibo888.top/Article/details/gtygxhedoe.html

[R37] 把输出赋给变量
来源：http://dali.cheryme.top/Article/details/gtzctcclhw.html

files=$(ls -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlleadckk.html

[R38] 管道串联
来源：http://dali.xuetiantiany.cn/Article/details/gtyoyqztga.html

cat a.txt | grep -i error | wc -l
来源：http://dali.quarkkingdee.top/Article/details/gttpyngwkx.html

[R39] 重定向标准输出与错误
来源：http://dali.0kj1m.cn/Article/details/gtmoggivhd.html

cmd > out.log 2>&1
来源：http://dali.wangshuangyany.cn/Article/details/gtmjkjuvxg.html

[R40] 追加写日志
来源：http://dali.quarkkingdee.top/Article/details/gtqmkkoqit.html

echo "log" >> out.log
来源：http://dali.yongpay.top/Article/details/gtdhgzltjb.html

[R41] 丢弃输出
来源：http://dali.zhoulong.xyz/Article/details/gtmcdujris.html

cmd >/dev/null 2>&1
来源：http://dali.jyoumei.cn/Article/details/gttuftdqlz.html

[R42] 输入重定向
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdampjsc.html

wc -l < a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafjdedod.html

[R43] 按名字查找文件
来源：http://dali.cheryme.top/Article/details/gtxwxwdisz.html

find . -name "*.log" -type f
来源：http://dali.hysaishi.cn/Article/details/gtxbgzfwaa.html

[R44] 按修改时间查找
来源：http://dali.yangfankeji.com/Article/details/gtqajhsaxv.html

find . -mtime -7 -type f
来源：http://dali.cqqwz.cn/Article/details/gtvshokdil.html

[R45] 批量删除
来源：http://dali.xylfe.cn/Article/details/gtlnprjfgt.html

find . -name "*.tmp" -delete
来源：http://dali.nanxinkj.top/Article/details/gtdtgnnyol.html

[R46] 递归替换文件内容
来源：http://dali.aibaodan.cn/Article/details/gtmlzyydpb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaujbedjg.html

[R47] sed 单行替换
来源：http://dali.yanxiufei.cn/Article/details/gtsqlkitua.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtktwikssw.html

[R48] awk 取指定列
来源：http://dali.xylfe.cn/Article/details/gtenkknkbp.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtrcympkcv.html

[R49] awk 带条件
来源：http://dali.shuidangran.top/Article/details/gtzzqdeqyd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jiagoushi.top/Article/details/gtlsuofuoe.html

[R50] awk 求和
来源：http://dali.guowangkeji.top/Article/details/gticvjikhb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.fengsongda.top/Article/details/gtvwwpodbn.html

[R51] 排序去重取前几
来源：http://dali.nanxuanxn.top/Article/details/gtomcqdxsn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xziqi.cn/Article/details/gteecyqgmu.html

[R52] 统计行数
来源：http://dali.cheryme.top/Article/details/gtbueimvnl.html

wc -l a.txt
来源：http://dali.cucudq.cn/Article/details/gtoepmbsbn.html

[R53] 查看文件头与实时尾
来源：http://dali.yvedp.cn/Article/details/gtganoafdh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenlongwang.top/Article/details/gtjvwrnqzp.html

[R54] 比较两个文件
来源：http://dali.fzhhl.top/Article/details/gtpowaahxt.html

diff a.txt b.txt
来源：http://dali.haohaochexian.top/Article/details/gthgsvmoam.html

[R55] 压缩与解压
来源：http://dali.gzhubu.top/Article/details/gtphzprljj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tanke756.top/Article/details/gtnndbxivc.html

[R56] 远程拷贝
来源：http://dali.andypj.xyz/Article/details/gtqmigwwji.html

scp file user@host:/path/
来源：http://dali.zhengqikj.top/Article/details/gtwlqzokmc.html

[R57] 远程执行命令
来源：http://dali.yj202588.top/Article/details/gtydasgesv.html

ssh user@host 'uptime'
来源：http://dali.cucudq.cn/Article/details/gtlkviqzao.html

[R58] 下载文件
来源：http://dali.cashguo.top/Article/details/gtdzqqncrh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cashguo.top/Article/details/gtjullokzm.html

[R59] 发 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtvhboeqfm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pengpengdd.cyou/Article/details/gtrsqvlnsr.html

[R60] 只看 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gtrjvvglav.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.meibo888.top/Article/details/gtfxcymauw.html

[R61] 磁盘占用
来源：http://dali.andypj.xyz/Article/details/gtceateuvt.html

df -h;  du -sh *
来源：http://dali.yueranfly.top/Article/details/gtfvdneucq.html

[R62] 找最占空间的文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtsaiozral.html

du -ah . | sort -rh | head -10
来源：http://dali.xuanzx.com/Article/details/gtpaudledv.html

[R63] 内存与进程
来源：http://dali.cdnleiting.top/Article/details/gtldhkezeq.html

free -h;  ps aux | grep nginx
来源：http://dali.xziqi.cn/Article/details/gtgooccpgi.html

[R64] 结束进程
来源：http://dali.jqgufenzy.top/Article/details/gtygcgdphu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcocydyjq.html

[R65] 查看端口占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhekxahw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnuoqjim.html

[R66] 定时任务
来源：http://dali.hnxiangtu.top/Article/details/gtdaqeekle.html

crontab -e;  crontab -l
来源：http://dali.cdnleiting.top/Article/details/gtzjvlvfrq.html

[R67] 生成随机十六进制串
来源：http://dali.gzhubu.top/Article/details/gtxaieiasr.html

openssl rand -hex 16
来源：http://dali.zhixingplan.top/Article/details/gtgyxhkzqi.html

[R68] 计算文件校验值
来源：http://dali.xylfe.cn/Article/details/gtccnnytmt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenzaomai.com/Article/details/gtcjoskpuz.html

[R69] 生成随机密码
来源：http://dali.zhongyouzk.top/Article/details/gtmfeoevgd.html

head -c 16 /dev/urandom | base64
来源：http://dali.shuidangran.top/Article/details/gtdzgzeijc.html

[R70] 时间戳与互转
来源：http://dali.jyoumei.cn/Article/details/gtpimelghp.html

date +%s;  date -d @1700000000
来源：http://dali.tanke756.top/Article/details/gtjcvhgjgd.html

[R71] 日期格式化
来源：http://dali.tanke756.top/Article/details/gtpdnsbigl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yonumen.top/Article/details/gthdvlyurq.html

[R72] 等待端口就绪
来源：http://dali.hnxiangtu.top/Article/details/gtslcbfevb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gtsknkjfqc.html

[R73] 分割大日志
来源：http://dali.guowangkeji.top/Article/details/gtmiksumsp.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangtech.top/Article/details/gtugqyaqjj.html

[R74] 批量重命名
来源：http://dali.sysykeji.top/Article/details/gtjvcpxbez.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gaohongyu789.top/Article/details/gtmznqrend.html

[R75] 导出环境变量
来源：http://dali.smart0.xyz/Article/details/gtxupvlbem.html


<!-- 参考信息 -->