代发 wailian999

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.guannengcc.top/Article/details/gttrmbupqg.html

[Q26] 计数
来源：http://dali.andypj.xyz/Article/details/gtdhbrqnar.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkcxpape.html

[Q27] 条件计数
来源：http://dali.wangdashe.top/Article/details/gttrcmuycn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj202588.top/Article/details/gtwjikfkxl.html

[Q28] 求和与平均
来源：http://dali.jqgufenzy.top/Article/details/gtujgutvgc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gttygsptzb.html

[Q29] 最大最小值
来源：http://dali.yueranfly.top/Article/details/gtvfcnhqgj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtolvtwchm.html

[Q30] 分组统计
来源：http://dali.hammf.cn/Article/details/gtayjpxfuo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljjyxjnt.html

[Q31] 分组后过滤
来源：http://dali.nanxuanxn.top/Article/details/gtabjeyqqb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.andypj.xyz/Article/details/gttxfiyqdq.html

[Q32] 分组拼接字符串
来源：http://dali.birdmap.top/Article/details/gtcobywzde.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtgrtxvvwj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sxryk.cn/Article/details/gtdzgevjwr.html

[Q33] 多列分组
来源：http://dali.jiagoushi.top/Article/details/gtagcjfhec.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sysykeji.top/Article/details/gtdacsrjzu.html

[Q34] 每组取第一条
来源：http://dali.gaohongyu789.top/Article/details/gtvrsnqfyf.html

SELECT * FROM (
来源：http://dali.jinqigfzy.top/Article/details/gtyxyiahlt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aizwys.cn/Article/details/gtbibktynk.html

) t WHERE rn = 1;
来源：http://dali.tian-w.cn/Article/details/gtfvniilgw.html

[Q35] 内连接
来源：http://dali.nanxinkj.top/Article/details/gtldjeseza.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xinyue.icu/Article/details/gtnsvvcxwq.html

[Q36] 左连接
来源：http://dali.chenlongwang.top/Article/details/gthcsqntcx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yangfankeji.com/Article/details/gtclbqnjbp.html

[Q37] 右连接
来源：http://dali.havefunace.top/Article/details/gtihbgwyra.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj202588.top/Article/details/gtsrddsbes.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cdnleiting.top/Article/details/gtfgvfctfd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.snrcjt.cn/Article/details/gtbriiljmp.html

[Q39] 自连接（查上下级）
来源：http://dali.dashuyun.cn/Article/details/gtnaadsxlb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.birdmap.top/Article/details/gtqkvvzzat.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cheryme.top/Article/details/gtwihuvklo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.316326.xyz/Article/details/gtlxseitic.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.guowangkeji.top/Article/details/gtxtbekbsj.html

[Q41] 多表连接
来源：http://dali.nanxuanxn.top/Article/details/gtqynxsbgf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhongyouzk.top/Article/details/gtdleognxk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.mhx1999.top/Article/details/gtyipcraox.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.bjfxy.top/Article/details/gthlaqiqzm.html

[Q42] 连接条件附加过滤
来源：http://dali.sufxvd.cn/Article/details/gtsrgvtznx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.0kj1m.cn/Article/details/gtlwwjvhiz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jianghu66.top/Article/details/gtkvlezdoy.html

[Q43] 标量子查询
来源：http://dali.hywenlv.cn/Article/details/gttglvrjim.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.iojbl.cn/Article/details/gtdgzdbynd.html

[Q44] IN 子查询
来源：http://dali.ppjwa.cn/Article/details/gtgrahvtox.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenjidiqi.icu/Article/details/gtsjowlsnf.html

[Q45] EXISTS 判断存在
来源：http://dali.chenzaomai.com/Article/details/gtkkhxfivb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gtckjhjjdl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jiagoushi.top/Article/details/gtfwniuxkq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnxiangtu.top/Article/details/gtkehpncty.html

[Q47] 与平均值比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtcycjpuln.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sweek.top/Article/details/gtzhqktznb.html

[Q48] CTE 公用表表达式
来源：http://dali.jqgufenzy.top/Article/details/gtxomxadvk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yongpay.top/Article/details/gtxiaiszlb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangdashe.top/Article/details/gtgmddqatk.html

[Q49] 更新单行
来源：http://dali.xinyue.icu/Article/details/gtnkdguzkj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtmjdbcicj.html

[Q50] 批量更新
来源：http://dali.yuxming.cn/Article/details/gtzdppzfys.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yueranfly.top/Article/details/gtsqxuvgkc.html

[Q51] 用子查询更新
来源：http://dali.chenzaomai.com/Article/details/gtndouxfbu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtmxahzbll.html

[Q52] 删除指定行
来源：http://dali.hammf.cn/Article/details/gtxrzdwwlc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwtpkhum.html

[Q53] 按条件删除
来源：http://dali.cdnleiting.top/Article/details/gttdziydfe.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gtxihhfztq.html

[Q54] 清空表
来源：http://dali.zhongyouzk.top/Article/details/gthsmabqzu.html

TRUNCATE TABLE logs;
来源：http://dali.yvedp.cn/Article/details/gtrfvndpks.html

[Q55] 排名（并列占位）
来源：http://dali.zhengqikj.top/Article/details/gtjutknvqh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gtfllxapyn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yvedp.cn/Article/details/gtyuoaewnx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinqigufen.top/Article/details/gtdrrfbhtm.html

[Q57] 行号
来源：http://dali.yuanzhike.top/Article/details/gtlzbnepzr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fengsongda.top/Article/details/gtjokrexzq.html

[Q58] 累计求和
来源：http://dali.yj20258.top/Article/details/gtsbvjlvpm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cashguo.top/Article/details/gtrkscsyhj.html

[Q59] 分组内累计
来源：http://dali.yj20258888.top/Article/details/gtxdnwjveo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtmnxefqzf.html

[Q60] 取上一行 / 下一行
来源：http://dali.shangyingyoupin.top/Article/details/gtxyfzowsy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ppjwa.cn/Article/details/gtpvdfaxxf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtsgkejlua.html

[Q61] 移动平均
来源：http://dali.hfpthk.cn/Article/details/gtlvbjudfm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtneurovmr.html

[Q62] 分组占比
来源：http://dali.jinqigfzy.top/Article/details/gtcunnwtif.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gtytjnzpgy.html

[Q63] 开启事务
来源：http://dali.guannengcc.top/Article/details/gtfaatsdci.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sysykeji.top/Article/details/gtdwlicisx.html

[Q64] 提交事务
来源：http://dali.daria6918.cn/Article/details/gtzzugebre.html

COMMIT;
来源：http://dali.0kj1m.cn/Article/details/gtensyvzzw.html

[Q65] 回滚事务
来源：http://dali.hammf.cn/Article/details/gtilimjali.html

ROLLBACK;
来源：http://dali.tianlin.xyz/Article/details/gtsphtdtzt.html

[Q66] 行锁查询
来源：http://dali.iojbl.cn/Article/details/gthvkcgyof.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinqigufen.top/Article/details/gtwboeexsh.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxedwetu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sxryk.cn/Article/details/gtyizomewq.html

[Q68] 保存点
来源：http://dali.9152youxi.cn/Article/details/gtypzwpeuy.html

SAVEPOINT sp1;
来源：http://dali.cqqwz.cn/Article/details/gtcibmnxdi.html

ROLLBACK TO sp1;
来源：http://dali.vqdsnc.cn/Article/details/gtzelnsspf.html

[Q69] 查看执行计划
来源：http://dali.fzhhl.top/Article/details/gtunnohdgg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hywenlv.cn/Article/details/gtlgpoljbw.html

[Q70] 更新统计信息
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjioigrpm.html

ANALYZE TABLE users;
来源：http://dali.aizwys.cn/Article/details/gtbvyyogho.html

[Q71] 查看建表语句
来源：http://dali.yuxming.cn/Article/details/gtdqierrvl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.snrcjt.cn/Article/details/gtmtzwwnqu.html

[Q72] 查看索引
来源：http://dali.ydzc1.top/Article/details/gttnmlvdau.html

SHOW INDEX FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtsyorkavx.html

[Q73] 查看表状态
来源：http://dali.redwolf501.top/Article/details/gtxpgbmiwm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shuidangran.top/Article/details/gtacnxmdnc.html

[Q74] 强制使用索引
来源：http://dali.jqgufenzy.top/Article/details/gtqeiwnqjd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pengpengdd.cyou/Article/details/gtvoqkxqlw.html

[Q75] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gtnjksomlp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtgmztqpds.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.fzhhl.top/Article/details/gtujzamojn.html

[Q76] 按天统计
来源：http://dali.zdqjudy.top/Article/details/gtzyplcgfr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daria6918.cn/Article/details/gtcofiuihr.html

[Q77] 时间加减
来源：http://dali.redwolf501.top/Article/details/gtkzekyvsr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.wangdashe.top/Article/details/gtrpishans.html

[Q78] 当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gttbidubxk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jiagoushi.top/Article/details/gtglqyfsjx.html

[Q79] 字符串拼接
来源：http://dali.316326.xyz/Article/details/gtdpdupndt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.dashuyun.cn/Article/details/gtwjpxirlf.html

[Q80] 字符串截取
来源：http://dali.pengpengdd.cyou/Article/details/gthlmwlnkd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtuvulssmd.html

[Q81] 字符串替换
来源：http://dali.dianchejie.cn/Article/details/gtbvgkkoqy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtnrbwwkgq.html

[Q82] 字符长度与字节长度
来源：http://dali.hammf.cn/Article/details/gtxomjoxnx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtkvdazalr.html

[Q83] 大小写转换
来源：http://dali.birdmap.top/Article/details/gtbuaqiasj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtbvslbstz.html

[Q84] 去除首尾空格
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgzgwfaf.html

SELECT TRIM(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtqqofyhrc.html

[Q85] 数值取整
来源：http://dali.hammf.cn/Article/details/gtwyvclzdf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvkgyrxp.html

[Q86] 读取 JSON 字段
来源：http://dali.fengsongda.top/Article/details/gtgfndrcwa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.redwolf501.top/Article/details/gtdujnmwma.html

[Q87] JSON 字段做条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfkxlpea.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.pycfn.com/Article/details/gtnrypyskb.html

[Q88] 行转列（条件聚合）
来源：http://dali.guowangkeji.top/Article/details/gtnzpoksfu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhengqikj.top/Article/details/gtlhyrwnnb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gzhubu.top/Article/details/gtgphirkvl.html

[Q89] 判断表是否存在
来源：http://dali.jianghu66.top/Article/details/gtxizifxjx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gtqlnmmuhh.html

[Q90] 生成序号列
来源：http://dali.zdqjudy.top/Article/details/gtzbbxqejv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.pycfn.com/Article/details/gtodkjzsgw.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtzhqzdjls.html

R. Bash 专题
来源：http://dali.aizwys.cn/Article/details/gtuuejejqs.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtwfotkszh.html

[R01] shebang 与严格模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtysiuanbc.html

#!/usr/bin/env bash
来源：http://dali.pengpengdd.cyou/Article/details/gttsoqjydy.html

set -euo pipefail
来源：http://dali.zhixingplan.top/Article/details/gtjretbhmx.html

[R02] 变量赋值与使用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjskafygl.html

name="Tom"; echo "$name"
来源：http://dali.nanxinkj.top/Article/details/gtpawurtsq.html

[R03] 只读变量
来源：http://dali.gotoacloud.top/Article/details/gtupwktodr.html

readonly PI=3.14
来源：http://dali.zhoulong.xyz/Article/details/gtyfuurcuf.html

[R04] 位置参数
来源：http://dali.c1oappe.top/Article/details/gtegileaua.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xinyue.icu/Article/details/gtearytfae.html

[R05] 参数默认值
来源：http://dali.shanyushiyangtech.top/Article/details/gtxkyvxela.html

name="${1:-default}"
来源：http://dali.jqgufenzy.top/Article/details/gtujqzmotq.html

[R06] 判断命令是否存在
来源：http://dali.daria6918.cn/Article/details/gtlamptsuf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gtflawheat.html

[R07] if 判断文件
来源：http://dali.nanxuanxn.top/Article/details/gtyosdhyif.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.316326.xyz/Article/details/gtiphgzlyh.html

[R08] 数值比较
来源：http://dali.gaohongyu789.top/Article/details/gtfvqgpfqq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhengqikj.top/Article/details/gttqfusfiv.html

[R09] 字符串比较
来源：http://dali.tanke756.top/Article/details/gtgceqjebe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtwumqgbzb.html

[R10] 正则匹配
来源：http://dali.nanxinkj.top/Article/details/gtkvheidrk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfsbcime.html

[R11] case 多分支
来源：http://dali.ybcxt.top/Article/details/gtolvsqmqa.html

case "$1" in
来源：http://dali.yvedp.cn/Article/details/gthekjpuml.html

start) echo "启动" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtdoiqqldl.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gtdzmljtuv.html

*)     echo "未知命令" ;;
来源：http://dali.svipenyu.cn/Article/details/gtcqifnlki.html

esac
来源：http://dali.havefunace.top/Article/details/gticcictlw.html

[R12] for 遍历文件
来源：http://dali.zhongyouzk.top/Article/details/gtavliomxp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ivvv.top/Article/details/gtvkixdxeo.html

[R13] for 计数循环
来源：http://dali.hongshengwenyu.top/Article/details/gtuomquenz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gogol.net.cn/Article/details/gtjxngvsae.html

[R14] C 风格 for
来源：http://dali.tian-w.cn/Article/details/gtvmwprdzo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gtyokzbxqb.html

[R15] while 逐行读文件
来源：http://dali.ivvv.top/Article/details/gtlbkufxyn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.9152youxi.cn/Article/details/gtltohvsei.html

[R16] until 等待条件
来源：http://dali.sweek.top/Article/details/gtevsqihrd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gtndawrbmu.html

[R17] 数组定义与取值
来源：http://dali.guowangkeji.top/Article/details/gtmawjfrjh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcjkzdei.html

[R18] 遍历数组
来源：http://dali.zycfv.cn/Article/details/gtyusxbtgc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxinkj.top/Article/details/gtdiionzdo.html

[R19] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gtgmlvsynv.html

echo "${#arr[@]}"
来源：http://dali.zdqjudy.top/Article/details/gtehpzwcvi.html

[R20] 关联数组（字典）
来源：http://dali.andypj.xyz/Article/details/gtjujkiptg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shuidangran.top/Article/details/gtknyopbfb.html

[R21] 字符串长度
来源：http://dali.haohaochexian.top/Article/details/gtuctsvsnm.html

echo "${#s}"
来源：http://dali.0kj1m.cn/Article/details/gtzgxqqoow.html

[R22] 截取子串
来源：http://dali.havefunace.top/Article/details/gtoysqheeh.html

echo "${s:0:5}"
来源：http://dali.316326.xyz/Article/details/gtcxijjuow.html

[R23] 字符串替换
来源：http://dali.cqqwz.cn/Article/details/gtngjwhbcy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.svipenyu.cn/Article/details/gtioxkzmkr.html

[R24] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gtxusukbys.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shangyingyoupin.top/Article/details/gtsewblgxd.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhengqikj.top/Article/details/gtwoclriey.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pycfn.com/Article/details/gtwtfnhavk.html

[R26] 命令替换
来源：http://dali.vqdsnc.cn/Article/details/gtaluxdeed.html

now=$(date +%F); echo "$now"
来源：http://dali.hywenlv.cn/Article/details/gtxhfcxcip.html

[R27] 算术展开
来源：http://dali.feifeiyinyue.top/Article/details/gtfsnmltlh.html

echo $((1 + 2 * 3))
来源：http://dali.ybcxt.top/Article/details/gtaracutze.html

[R28] 浮点运算
来源：http://dali.hfpthk.cn/Article/details/gtixlhbujm.html

echo "scale=2; 10/3" | bc
来源：http://dali.guowangkeji.top/Article/details/gttzbvwjxt.html

[R29] 定义函数
来源：http://dali.yangfankeji.com/Article/details/gtnsqoeete.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.redwolf501.top/Article/details/gtfvsawncx.html

[R30] 函数返回状态码
来源：http://dali.ehwqpu.com/Article/details/gtzntizvui.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ehwqpu.com/Article/details/gtansfdbiz.html

[R31] 局部变量
来源：http://dali.xuanzx.com/Article/details/gtdzxecfts.html

f() { local x=1; echo "$x"; }
来源：http://dali.fzhhl.top/Article/details/gtwspepywk.html

[R32] 参数个数校验
来源：http://dali.yueranfly.top/Article/details/gtzynebdtp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gtrudditwd.html

[R33] 捕获错误并提示行号
来源：http://dali.aizwys.cn/Article/details/gttgeugybq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhiwuduotai.top/Article/details/gtppjcgzkc.html

[R34] 退出时清理
来源：http://dali.hysaishi.cn/Article/details/gtyqrpgxii.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gtdmqyvcsq.html

[R35] 后台执行并等待
来源：http://dali.vqdsnc.cn/Article/details/gtinietemd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yvedp.cn/Article/details/gtzomwaxxe.html

[R36] 并发执行多个任务
来源：http://dali.tianlin.xyz/Article/details/gtwbslwzwv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tian-w.cn/Article/details/gtkhowtijt.html

[R37] 把输出赋给变量
来源：http://dali.jlsjyb.cn/Article/details/gtrtzwtdnr.html

files=$(ls -1)
来源：http://dali.shzxlz.cn/Article/details/gtcsohvtvp.html

[R38] 管道串联
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxxuyfrj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.mhx1999.top/Article/details/gtwsknvodw.html

[R39] 重定向标准输出与错误
来源：http://dali.jiagoushi.top/Article/details/gtmggzdbty.html

cmd > out.log 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gtbxewburs.html

[R40] 追加写日志
来源：http://dali.xuetiantiany.cn/Article/details/gtvwoefcmz.html

echo "log" >> out.log
来源：http://dali.shanyushiyangtech.top/Article/details/gtogzbicsy.html

[R41] 丢弃输出
来源：http://dali.9152youxi.cn/Article/details/gteoedkgrv.html

cmd >/dev/null 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gtctddzlsm.html

[R42] 输入重定向
来源：http://dali.yj202588.top/Article/details/gtexyvcxtm.html

wc -l < a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjsdicebd.html

[R43] 按名字查找文件
来源：http://dali.gotoacloud.top/Article/details/gtndhnzioq.html

find . -name "*.log" -type f
来源：http://dali.snrcjt.cn/Article/details/gtworxwoxm.html

[R44] 按修改时间查找
来源：http://dali.daxiang520.top/Article/details/gtaxvryykc.html

find . -mtime -7 -type f
来源：http://dali.yuxming.cn/Article/details/gtuywsxddu.html

[R45] 批量删除
来源：http://dali.guannengcc.top/Article/details/gttzcrvmvs.html

find . -name "*.tmp" -delete
来源：http://dali.mhx1999.top/Article/details/gtgtbzqost.html

[R46] 递归替换文件内容
来源：http://dali.zhoulong.xyz/Article/details/gththxxlgr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sufxvd.cn/Article/details/gtmfbbefjd.html

[R47] sed 单行替换
来源：http://dali.tian-w.cn/Article/details/gtmtqxxktj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hysaishi.cn/Article/details/gturbuqgin.html

[R48] awk 取指定列
来源：http://dali.dianchejie.cn/Article/details/gtuapwmdvs.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtbbqnmbbr.html

[R49] awk 带条件
来源：http://dali.andypj.xyz/Article/details/gtwijcrivd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shangyingyoupin.top/Article/details/gtejedmmkw.html

[R50] awk 求和
来源：http://dali.xuetiantiany.cn/Article/details/gtrhupjuly.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgfzy.top/Article/details/gttlgzkjcn.html

[R51] 排序去重取前几
来源：http://dali.tianlin.xyz/Article/details/gtnnparmuh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.meibo888.top/Article/details/gttibyrhol.html

[R52] 统计行数
来源：http://dali.ehwqpu.com/Article/details/gtqayqzxsy.html

wc -l a.txt
来源：http://dali.meibo888.top/Article/details/gtcrrnobcf.html

[R53] 查看文件头与实时尾
来源：http://dali.cqqwz.cn/Article/details/gtjtwecqpm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yangfankeji.com/Article/details/gtsbcakyws.html

[R54] 比较两个文件
来源：http://dali.yongpay.top/Article/details/gtsfbvahrx.html

diff a.txt b.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwhjbtjb.html

[R55] 压缩与解压
来源：http://dali.zdqjudy.top/Article/details/gtqxivgaxd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.havefunace.top/Article/details/gtddltsplm.html

[R56] 远程拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtnjvadzpu.html

scp file user@host:/path/
来源：http://dali.hammf.cn/Article/details/gtsiunjbda.html

[R57] 远程执行命令
来源：http://dali.yj202588.top/Article/details/gtwfwrsawc.html

ssh user@host 'uptime'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkyuqtxm.html

[R58] 下载文件
来源：http://dali.jlsjyb.cn/Article/details/gtpebwwddn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.redwolf501.top/Article/details/gtihfwywpw.html

[R59] 发 POST JSON
来源：http://dali.sufxvd.cn/Article/details/gttkjuxewa.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jqgufenzy.top/Article/details/gttiwkjfru.html

[R60] 只看 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gtlprabzgj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zycfv.cn/Article/details/gtjoxwlcbw.html

[R61] 磁盘占用
来源：http://dali.snrcjt.cn/Article/details/gtlyrywetj.html

df -h;  du -sh *
来源：http://dali.vqdsnc.cn/Article/details/gtaolrvxcy.html

[R62] 找最占空间的文件
来源：http://dali.yj20258888.top/Article/details/gtjmypctlp.html

du -ah . | sort -rh | head -10
来源：http://dali.ybcxt.top/Article/details/gtieiavmls.html

[R63] 内存与进程
来源：http://dali.yj20258888.top/Article/details/gtqumqlmwd.html

free -h;  ps aux | grep nginx
来源：http://dali.mhx1999.top/Article/details/gtyzzvfafa.html

[R64] 结束进程
来源：http://dali.ybcxt.top/Article/details/gtviqrqffg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchcudovk.html

[R65] 查看端口占用
来源：http://dali.snrcjt.cn/Article/details/gtjctpncdk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhixingplan.top/Article/details/gtcgnvysnv.html

[R66] 定时任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvebzondz.html

crontab -e;  crontab -l
来源：http://dali.iojbl.cn/Article/details/gtiazjwjtk.html

[R67] 生成随机十六进制串
来源：http://dali.xylfe.cn/Article/details/gthlwvdghx.html

openssl rand -hex 16
来源：http://dali.feifeiyinyue.top/Article/details/gtysnvjebs.html

[R68] 计算文件校验值
来源：http://dali.jiagoushi.top/Article/details/gtzodtaaci.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sxryk.cn/Article/details/gtawwvurxm.html

[R69] 生成随机密码
来源：http://dali.zycfv.cn/Article/details/gttoglmnse.html

head -c 16 /dev/urandom | base64
来源：http://dali.jlsjyb.cn/Article/details/gtchrbmuux.html

[R70] 时间戳与互转
来源：http://dali.iojbl.cn/Article/details/gtacaontwh.html

date +%s;  date -d @1700000000
来源：http://dali.wangdashe.top/Article/details/gtfqgosnhp.html

[R71] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtwzbyqvtr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jlsjyb.cn/Article/details/gturjsetkn.html

[R72] 等待端口就绪
来源：http://dali.nanxuanxn.top/Article/details/gttozjramw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gttklqdgyk.html

[R73] 分割大日志
来源：http://dali.aibaodan.cn/Article/details/gtrkddamvx.html

split -l 1000 big.log part_
来源：http://dali.jiagoushi.top/Article/details/gtkvejdaam.html

[R74] 批量重命名
来源：http://dali.pycfn.com/Article/details/gtxpovisbp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.dianchejie.cn/Article/details/gtwkjnrzwg.html

[R75] 导出环境变量
来源：http://dali.c1oappe.top/Article/details/gtqaqncrjf.html


<!-- 参考信息 -->