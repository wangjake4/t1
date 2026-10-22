代发 wailian999

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtrletteux.html

[Q30] 分组统计
来源：http://dali.yonumen.top/Article/details/gtcjljdhdo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gtbnuemagm.html

[Q31] 分组后过滤
来源：http://dali.shuidangran.top/Article/details/gtwcmjyhvh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cucudq.cn/Article/details/gtwapfiqam.html

[Q32] 分组拼接字符串
来源：http://dali.daxiang520.top/Article/details/gthfyvbrvx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gtdckhigcx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gogol.net.cn/Article/details/gtbfutjvqn.html

[Q33] 多列分组
来源：http://dali.xylfe.cn/Article/details/gtkwuabrql.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.c1oappe.top/Article/details/gtyfgeasps.html

[Q34] 每组取第一条
来源：http://dali.yonumen.top/Article/details/gtlfpegxvc.html

SELECT * FROM (
来源：http://dali.hfpthk.cn/Article/details/gtloqdsmlc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aizwys.cn/Article/details/gtdqhyymxt.html

) t WHERE rn = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtjjcbxauh.html

[Q35] 内连接
来源：http://dali.gzhubu.top/Article/details/gtzmlctmpb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tian-w.cn/Article/details/gtklgidbnp.html

[Q36] 左连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmyvxzuk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.haohaochexian.top/Article/details/gtfygysyrr.html

[Q37] 右连接
来源：http://dali.xuetiantiany.cn/Article/details/gtnkxcmrxg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmdloiqo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jianghu66.top/Article/details/gtwjppwywk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gaohongyu789.top/Article/details/gtswojtviy.html

[Q39] 自连接（查上下级）
来源：http://dali.yuanzhike.top/Article/details/gtepxqjtkz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ppjwa.cn/Article/details/gtwetntpep.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fengsongda.top/Article/details/gtzoblyejg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.iojbl.cn/Article/details/gtemsaiqlb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhoulong.xyz/Article/details/gtaigfejyd.html

[Q41] 多表连接
来源：http://dali.ydzc1.top/Article/details/gtalmboxat.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ydzc1.top/Article/details/gtcrgtdwuz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ydzc1.top/Article/details/gtjkojuhmw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvwubnpt.html

[Q42] 连接条件附加过滤
来源：http://dali.daxiang520.top/Article/details/gtmgdjnmoy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tanke756.top/Article/details/gtwomswqqi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gtrjfdaavh.html

[Q43] 标量子查询
来源：http://dali.cashguo.top/Article/details/gtrfmwuyxq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigfzy.top/Article/details/gtgmqwnong.html

[Q44] IN 子查询
来源：http://dali.c1oappe.top/Article/details/gthaolusju.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhixingplan.top/Article/details/gtaqqssxuf.html

[Q45] EXISTS 判断存在
来源：http://dali.cashguo.top/Article/details/gtujpvnlmu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzpvdqll.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.kuanghao11.cn/Article/details/gtlseewevi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.iojbl.cn/Article/details/gtxylvbmuq.html

[Q47] 与平均值比较
来源：http://dali.hongshengwenyu.top/Article/details/gtlgixdgza.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sweek.top/Article/details/gtjezhtmod.html

[Q48] CTE 公用表表达式
来源：http://dali.smart0.xyz/Article/details/gthvwzoztb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gaohongyu789.top/Article/details/gtjzsvlgce.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sxryk.cn/Article/details/gtkloaslxd.html

[Q49] 更新单行
来源：http://dali.yuanzhike.top/Article/details/gtjsxhasek.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yuxming.cn/Article/details/gtbetfpthm.html

[Q50] 批量更新
来源：http://dali.smart0.xyz/Article/details/gtmpqervwp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ydzc1.top/Article/details/gtixxnykgq.html

[Q51] 用子查询更新
来源：http://dali.birdmap.top/Article/details/gtbabrmvzs.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hammf.cn/Article/details/gtgisgproo.html

[Q52] 删除指定行
来源：http://dali.gzhubu.top/Article/details/gtnfyaxztm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.9152youxi.cn/Article/details/gtqaqcacju.html

[Q53] 按条件删除
来源：http://dali.nanxuanxn.top/Article/details/gtnowwmowr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikwdrjwg.html

[Q54] 清空表
来源：http://dali.tanke756.top/Article/details/gtswdohfce.html

TRUNCATE TABLE logs;
来源：http://dali.yonumen.top/Article/details/gtwyaclmgh.html

[Q55] 排名（并列占位）
来源：http://dali.havefunace.top/Article/details/gtoesypduz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yvedp.cn/Article/details/gtbmajnxsw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gogol.net.cn/Article/details/gtcerztfff.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.c1oappe.top/Article/details/gtpcqnimpu.html

[Q57] 行号
来源：http://dali.wangdashe.top/Article/details/gtdwyyoxaj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hysaishi.cn/Article/details/gthdabkmpv.html

[Q58] 累计求和
来源：http://dali.jyoumei.cn/Article/details/gtkwhrggqj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtsmdxymzq.html

[Q59] 分组内累计
来源：http://dali.xuetiantiany.cn/Article/details/gtajeqrlla.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yonumen.top/Article/details/gtcglppbta.html

[Q60] 取上一行 / 下一行
来源：http://dali.tanke756.top/Article/details/gtsbzlwjjr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tanke756.top/Article/details/gtnwrgpdiu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yongpay.top/Article/details/gtjwrdrbwe.html

[Q61] 移动平均
来源：http://dali.shzxlz.cn/Article/details/gtrubazxjc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtrhkxyacz.html

[Q62] 分组占比
来源：http://dali.tian-w.cn/Article/details/gtvelebfif.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gteazqstxm.html

[Q63] 开启事务
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwpwozti.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yonumen.top/Article/details/gtphanwbfu.html

[Q64] 提交事务
来源：http://dali.haohaochexian.top/Article/details/gtnwpzsuji.html

COMMIT;
来源：http://dali.zhixingplan.top/Article/details/gtrmwcqhgu.html

[Q65] 回滚事务
来源：http://dali.smart0.xyz/Article/details/gtvqfelovw.html

ROLLBACK;
来源：http://dali.hammf.cn/Article/details/gtasuxcerf.html

[Q66] 行锁查询
来源：http://dali.xziqi.cn/Article/details/gtkmgvlobt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shzxlz.cn/Article/details/gtdipoqmfw.html

[Q67] 设置隔离级别
来源：http://dali.zhongyouzk.top/Article/details/gttkpsrofr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdsbdvmbz.html

[Q68] 保存点
来源：http://dali.xuanzx.com/Article/details/gtcupxdvab.html

SAVEPOINT sp1;
来源：http://dali.cashguo.top/Article/details/gtiujausxc.html

ROLLBACK TO sp1;
来源：http://dali.nanxuanxn.top/Article/details/gtltqyrhyj.html

[Q69] 查看执行计划
来源：http://dali.vqdsnc.cn/Article/details/gtgkmmawvw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.redwolf501.top/Article/details/gtapufozou.html

[Q70] 更新统计信息
来源：http://dali.ybcxt.top/Article/details/gtkrgxrpyq.html

ANALYZE TABLE users;
来源：http://dali.yj20258.top/Article/details/gtvatpfifb.html

[Q71] 查看建表语句
来源：http://dali.andypj.xyz/Article/details/gtmiujwegb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hnxiangtu.top/Article/details/gtyevcqalu.html

[Q72] 查看索引
来源：http://dali.fzhhl.top/Article/details/gttwwjhldu.html

SHOW INDEX FROM users;
来源：http://dali.daxiang520.top/Article/details/gtoqpvxtod.html

[Q73] 查看表状态
来源：http://dali.chenjidiqi.icu/Article/details/gtqspbjmuq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258888.top/Article/details/gtorvvrvdc.html

[Q74] 强制使用索引
来源：http://dali.chenjidiqi.icu/Article/details/gtdoasbtvh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenlongwang.top/Article/details/gtpqaghzbi.html

[Q75] 日期格式化
来源：http://dali.fzhhl.top/Article/details/gtwitfoswv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtjyngasrp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.svipenyu.cn/Article/details/gteknbpndg.html

[Q76] 按天统计
来源：http://dali.xuetiantiany.cn/Article/details/gtblzknnqp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yangfankeji.com/Article/details/gtlcftrmvb.html

[Q77] 时间加减
来源：http://dali.hfpthk.cn/Article/details/gtkorzcvjd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shzxlz.cn/Article/details/gtexkblskl.html

[Q78] 当前时间
来源：http://dali.cheryme.top/Article/details/gthvhdxshg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ybcxt.top/Article/details/gtheukyacp.html

[Q79] 字符串拼接
来源：http://dali.ydzc1.top/Article/details/gtskolcare.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shangyingyoupin.top/Article/details/gtjmrhffpy.html

[Q80] 字符串截取
来源：http://dali.yangfankeji.com/Article/details/gtlmyicpdj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtplmpyfns.html

[Q81] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gtmrywduhk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtejqvecis.html

[Q82] 字符长度与字节长度
来源：http://dali.xziqi.cn/Article/details/gtckmeqqni.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtibujwymu.html

[Q83] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gtqmybogsw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtvnzzcwkl.html

[Q84] 去除首尾空格
来源：http://dali.aibaodan.cn/Article/details/gtfdliviun.html

SELECT TRIM(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtksgdhhmx.html

[Q85] 数值取整
来源：http://dali.dianchejie.cn/Article/details/gtswnxcqsi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.havefunace.top/Article/details/gthkvzrlco.html

[Q86] 读取 JSON 字段
来源：http://dali.haohaochexian.top/Article/details/gtuhighien.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.quarkkingdee.top/Article/details/gtakxismwr.html

[Q87] JSON 字段做条件
来源：http://dali.meibo888.top/Article/details/gtdgadsyrx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shuidangran.top/Article/details/gttgwykica.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgzbigvu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sysykeji.top/Article/details/gtcjtmfthw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckrxgfci.html

[Q89] 判断表是否存在
来源：http://dali.jiagoushi.top/Article/details/gtnzhfyzkp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jyoumei.cn/Article/details/gtzlbkswop.html

[Q90] 生成序号列
来源：http://dali.pengpengdd.cyou/Article/details/gteambxeks.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtohksfsfa.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtbhxdlfrk.html

R. Bash 专题
来源：http://dali.yj20258888.top/Article/details/gtpzbvomls.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtcsrrqngw.html

[R01] shebang 与严格模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmvzbovg.html

#!/usr/bin/env bash
来源：http://dali.yj202588.top/Article/details/gtqxjknsde.html

set -euo pipefail
来源：http://dali.andypj.xyz/Article/details/gtwykdkipi.html

[R02] 变量赋值与使用
来源：http://dali.dianchejie.cn/Article/details/gtngioexza.html

name="Tom"; echo "$name"
来源：http://dali.guannengcc.top/Article/details/gtqgeidyny.html

[R03] 只读变量
来源：http://dali.sxryk.cn/Article/details/gtunrevpbu.html

readonly PI=3.14
来源：http://dali.aizwys.cn/Article/details/gtihuwwawv.html

[R04] 位置参数
来源：http://dali.hywenlv.cn/Article/details/gthtnpnnsq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sufxvd.cn/Article/details/gtrcojhtuz.html

[R05] 参数默认值
来源：http://dali.ydzc1.top/Article/details/gtytbtypmy.html

name="${1:-default}"
来源：http://dali.yonumen.top/Article/details/gtopkhhysc.html

[R06] 判断命令是否存在
来源：http://dali.hysaishi.cn/Article/details/gtolswtrne.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gthdayatmq.html

[R07] if 判断文件
来源：http://dali.ivvv.top/Article/details/gtdcetafrr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daxiang520.top/Article/details/gttophymky.html

[R08] 数值比较
来源：http://dali.yj20258888.top/Article/details/gtbomgqtrc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtkqdyydux.html

[R09] 字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gtkdquljte.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gogol.net.cn/Article/details/gtezirsrat.html

[R10] 正则匹配
来源：http://dali.iojbl.cn/Article/details/gtzzoidiaz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jianghu66.top/Article/details/gtlginqimy.html

[R11] case 多分支
来源：http://dali.shuidangran.top/Article/details/gtswgayham.html

case "$1" in
来源：http://dali.yj20258.top/Article/details/gtgsqsthfx.html

start) echo "启动" ;;
来源：http://dali.jqgfzy.top/Article/details/gtotxbcvfp.html

stop)  echo "停止" ;;
来源：http://dali.316326.xyz/Article/details/gtardhfeci.html

*)     echo "未知命令" ;;
来源：http://dali.cheryme.top/Article/details/gtwcdiknvn.html

esac
来源：http://dali.chenlongwang.top/Article/details/gttefoxmzh.html

[R12] for 遍历文件
来源：http://dali.zycfv.cn/Article/details/gtwmpgiirm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenlongwang.top/Article/details/gtwhxbpgtt.html

[R13] for 计数循环
来源：http://dali.c1oappe.top/Article/details/gtzrkfhneq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtbaihdbwn.html

[R14] C 风格 for
来源：http://dali.haohaochexian.top/Article/details/gtnlfddhzg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.haohaochexian.top/Article/details/gtrrymwwyi.html

[R15] while 逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtrblyjnmb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ehwqpu.com/Article/details/gtaturwquy.html

[R16] until 等待条件
来源：http://dali.tanke756.top/Article/details/gtlnimansk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.316326.xyz/Article/details/gtirvqqgew.html

[R17] 数组定义与取值
来源：http://dali.zdqjudy.top/Article/details/gtoaentsmt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yanxiufei.cn/Article/details/gtgjfyuawb.html

[R18] 遍历数组
来源：http://dali.wangdashe.top/Article/details/gtdulrsghv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dianchejie.cn/Article/details/gtzsyowdvh.html

[R19] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gtxyxhrmro.html

echo "${#arr[@]}"
来源：http://dali.yangfankeji.com/Article/details/gtlospleqc.html

[R20] 关联数组（字典）
来源：http://dali.yj20258888.top/Article/details/gteghxmrwo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cqqwz.cn/Article/details/gtpmbjssbt.html

[R21] 字符串长度
来源：http://dali.tianlin.xyz/Article/details/gtzesqcdyi.html

echo "${#s}"
来源：http://dali.hongshengwenyu.top/Article/details/gtprydwxiq.html

[R22] 截取子串
来源：http://dali.chenjidiqi.icu/Article/details/gtnjrflolm.html

echo "${s:0:5}"
来源：http://dali.jqgfzy.top/Article/details/gtylcogvuh.html

[R23] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gtzhypuown.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhengqikj.top/Article/details/gtrztbykun.html

[R24] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gtsnlomfmt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yanxiufei.cn/Article/details/gtuerblnuy.html

[R25] 去后缀 / 去前缀
来源：http://dali.guowangkeji.top/Article/details/gtrpgvlkss.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yongpay.top/Article/details/gtjwigxdtx.html

[R26] 命令替换
来源：http://dali.pengpengdd.cyou/Article/details/gtcdhglqfq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhengqikj.top/Article/details/gtptenuroo.html

[R27] 算术展开
来源：http://dali.zhongyouzk.top/Article/details/gtxvvcbrkh.html

echo $((1 + 2 * 3))
来源：http://dali.yj202588.top/Article/details/gtvvqktkoj.html

[R28] 浮点运算
来源：http://dali.mhx1999.top/Article/details/gtvwfkjptd.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenzaomai.com/Article/details/gttigguosj.html

[R29] 定义函数
来源：http://dali.aizwys.cn/Article/details/gtvsxfzckx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnxiangtu.top/Article/details/gtfdzktahw.html

[R30] 函数返回状态码
来源：http://dali.zhoulong.xyz/Article/details/gtsmwxreqr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczjsnjvz.html

[R31] 局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gtkcavegtc.html

f() { local x=1; echo "$x"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtpyalhimi.html

[R32] 参数个数校验
来源：http://dali.nanxinkj.top/Article/details/gtoanglhml.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gtlmlduxjv.html

[R33] 捕获错误并提示行号
来源：http://dali.yj202588.top/Article/details/gtymzcruhu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shzxlz.cn/Article/details/gtluklzvij.html

[R34] 退出时清理
来源：http://dali.haohaochexian.top/Article/details/gtqjsvnazo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daria6918.cn/Article/details/gtunpqttjv.html

[R35] 后台执行并等待
来源：http://dali.xylfe.cn/Article/details/gttymjwgfk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenlongwang.top/Article/details/gtudoyidxr.html

[R36] 并发执行多个任务
来源：http://dali.dashuyun.cn/Article/details/gtvexvpsbe.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jyoumei.cn/Article/details/gtcqkoodst.html

[R37] 把输出赋给变量
来源：http://dali.quarkkingdee.top/Article/details/gtldsbmtvt.html

files=$(ls -1)
来源：http://dali.zycfv.cn/Article/details/gtyikwizmy.html

[R38] 管道串联
来源：http://dali.bjfxy.top/Article/details/gtypfygjlp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hysaishi.cn/Article/details/gtsueissqa.html

[R39] 重定向标准输出与错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofzxgsmf.html

cmd > out.log 2>&1
来源：http://dali.ybcxt.top/Article/details/gtmdzfvgmm.html

[R40] 追加写日志
来源：http://dali.chenlongwang.top/Article/details/gtraaklkcf.html

echo "log" >> out.log
来源：http://dali.xuetiantiany.cn/Article/details/gtruneezca.html

[R41] 丢弃输出
来源：http://dali.fzhhl.top/Article/details/gtrahsolde.html

cmd >/dev/null 2>&1
来源：http://dali.cdnleiting.top/Article/details/gticmmpjrf.html

[R42] 输入重定向
来源：http://dali.aibaodan.cn/Article/details/gtiautqwph.html

wc -l < a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtnthmdiwi.html

[R43] 按名字查找文件
来源：http://dali.zdqjudy.top/Article/details/gtrubiqbcu.html

find . -name "*.log" -type f
来源：http://dali.iojbl.cn/Article/details/gtzfdbzmid.html

[R44] 按修改时间查找
来源：http://dali.shangyingyoupin.top/Article/details/gttwmvifcr.html

find . -mtime -7 -type f
来源：http://dali.tian-w.cn/Article/details/gthznibsqk.html

[R45] 批量删除
来源：http://dali.tanke756.top/Article/details/gtrcarhuzy.html

find . -name "*.tmp" -delete
来源：http://dali.kuanghao11.cn/Article/details/gtlbfsfles.html

[R46] 递归替换文件内容
来源：http://dali.hfpthk.cn/Article/details/gtbfriwwdu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nwbrower.top/Article/details/gtiwaezgin.html

[R47] sed 单行替换
来源：http://dali.jqgufenzy.top/Article/details/gtnomleefd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tanke756.top/Article/details/gtggydfmsz.html

[R48] awk 取指定列
来源：http://dali.zhixingplan.top/Article/details/gtbjtydznr.html

awk '{print $1, $3}' a.txt
来源：http://dali.ivvv.top/Article/details/gtxcgilfaq.html

[R49] awk 带条件
来源：http://dali.hnqzz.top/Article/details/gtbmkkyrfu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangshuangyany.cn/Article/details/gthsiiyllm.html

[R50] awk 求和
来源：http://dali.svipenyu.cn/Article/details/gtjtvjlooq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtfondijxo.html

[R51] 排序去重取前几
来源：http://dali.wangdashe.top/Article/details/gtqvvzeryq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.9152youxi.cn/Article/details/gtkrpgmowe.html

[R52] 统计行数
来源：http://dali.guowangkeji.top/Article/details/gtzlxqgqnp.html

wc -l a.txt
来源：http://dali.sxryk.cn/Article/details/gtlcihqzqg.html

[R53] 查看文件头与实时尾
来源：http://dali.dashuyun.cn/Article/details/gtsodgzrrq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgufenzy.top/Article/details/gtdfvjttsy.html

[R54] 比较两个文件
来源：http://dali.yj202588.top/Article/details/gtnlvbikvt.html

diff a.txt b.txt
来源：http://dali.wangdashe.top/Article/details/gthpwarbit.html

[R55] 压缩与解压
来源：http://dali.tian-w.cn/Article/details/gtnjbgdvcg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.kuanghao11.cn/Article/details/gtseikmtzl.html

[R56] 远程拷贝
来源：http://dali.316326.xyz/Article/details/gtcxuswvxq.html

scp file user@host:/path/
来源：http://dali.yj20258.top/Article/details/gtnqqgmpad.html

[R57] 远程执行命令
来源：http://dali.redwolf501.top/Article/details/gtnzebrpsm.html

ssh user@host 'uptime'
来源：http://dali.gaohongyu789.top/Article/details/gtffjokixi.html

[R58] 下载文件
来源：http://dali.guannengcc.top/Article/details/gtdvcxuuug.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sweek.top/Article/details/gtxktjiumg.html

[R59] 发 POST JSON
来源：http://dali.yj20258.top/Article/details/gturagaqkq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.guannengcc.top/Article/details/gtmcqvtvds.html

[R60] 只看 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gtcqikblvt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nanxuanxn.top/Article/details/gtedwrmnxq.html

[R61] 磁盘占用
来源：http://dali.sysykeji.top/Article/details/gtxoaqnitt.html

df -h;  du -sh *
来源：http://dali.gaohongyu789.top/Article/details/gtxxawrxsd.html

[R62] 找最占空间的文件
来源：http://dali.yongpay.top/Article/details/gtbdwmhdtu.html

du -ah . | sort -rh | head -10
来源：http://dali.sweek.top/Article/details/gtulbcnmvk.html

[R63] 内存与进程
来源：http://dali.chenjidiqi.icu/Article/details/gtuclhrwzr.html

free -h;  ps aux | grep nginx
来源：http://dali.cashguo.top/Article/details/gtngzrpcac.html

[R64] 结束进程
来源：http://dali.xinyue.icu/Article/details/gtdpyawcoo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuanzx.com/Article/details/gtiqcsfzrb.html

[R65] 查看端口占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdayrdwmu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cucudq.cn/Article/details/gtwzrbyntj.html

[R66] 定时任务
来源：http://dali.yj202588.top/Article/details/gtwdxjubpm.html

crontab -e;  crontab -l
来源：http://dali.bjfxy.top/Article/details/gtgidytthd.html

[R67] 生成随机十六进制串
来源：http://dali.cashguo.top/Article/details/gtxutjtjxm.html

openssl rand -hex 16
来源：http://dali.dianchejie.cn/Article/details/gtgepgxumf.html

[R68] 计算文件校验值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkdorpar.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.haohaochexian.top/Article/details/gtuvgtmacz.html

[R69] 生成随机密码
来源：http://dali.mhx1999.top/Article/details/gtpyhakhqx.html

head -c 16 /dev/urandom | base64
来源：http://dali.guannengcc.top/Article/details/gtevdkxtzh.html

[R70] 时间戳与互转
来源：http://dali.shzxlz.cn/Article/details/gtqoojhoal.html

date +%s;  date -d @1700000000
来源：http://dali.zhongyouzk.top/Article/details/gtbgtcyand.html

[R71] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gtokmlxall.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangshuangyany.cn/Article/details/gtzllmhmur.html

[R72] 等待端口就绪
来源：http://dali.jqgfzy.top/Article/details/gtqirqnhek.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gtqmolkhpv.html

[R73] 分割大日志
来源：http://dali.316326.xyz/Article/details/gtfokctbqo.html

split -l 1000 big.log part_
来源：http://dali.sweek.top/Article/details/gtbitgmdor.html

[R74] 批量重命名
来源：http://dali.zhiwuduotai.top/Article/details/gtoeqisuua.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxuanxn.top/Article/details/gtxdzthisa.html

[R75] 导出环境变量
来源：http://dali.guowangkeji.top/Article/details/gttkdagsaw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gaohongyu789.top/Article/details/gthcceearu.html

[R76] 使用临时文件
来源：http://dali.zhengqikj.top/Article/details/gtcucpmprx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinghuilouyu.cn/Article/details/gtcnszgxnk.html

[R77] 读取用户输入
来源：http://dali.smart0.xyz/Article/details/gtawwiffdh.html

read -rp "请输入: " ans
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdssgewof.html

[R78] 交互式菜单
来源：http://dali.jlsjyb.cn/Article/details/gtowsaudkm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwnidxga.html

[R79] 解析命令行选项
来源：http://dali.fengsongda.top/Article/details/gtlhejpadg.html


<!-- 参考信息 -->