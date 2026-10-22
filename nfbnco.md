代发 wailian999

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xuetiantiany.cn/Article/details/gtbgatipew.html

[Q26] 计数
来源：http://dali.gogol.net.cn/Article/details/gttfxcgmxx.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtnhokvgof.html

[Q27] 条件计数
来源：http://dali.gzhubu.top/Article/details/gtizbcfluv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ybcxt.top/Article/details/gtwiatzplu.html

[Q28] 求和与平均
来源：http://dali.xylfe.cn/Article/details/gtrznukimk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkkvncpx.html

[Q29] 最大最小值
来源：http://dali.yj20258888.top/Article/details/gtskjxccod.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtrgawhixc.html

[Q30] 分组统计
来源：http://dali.cqqwz.cn/Article/details/gtqwwufgis.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gtvbtlndbs.html

[Q31] 分组后过滤
来源：http://dali.guowangkeji.top/Article/details/gtspgimddx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinqigufen.top/Article/details/gtaqdlohmf.html

[Q32] 分组拼接字符串
来源：http://dali.bjfxy.top/Article/details/gtrikbyyhi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gtdoaplvpq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sysykeji.top/Article/details/gtnbymrfoh.html

[Q33] 多列分组
来源：http://dali.zhengqikj.top/Article/details/gtceorlqow.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yanxiufei.cn/Article/details/gtetnrlbty.html

[Q34] 每组取第一条
来源：http://dali.9152youxi.cn/Article/details/gtvymkvkgs.html

SELECT * FROM (
来源：http://dali.yangfankeji.com/Article/details/gtbkkkmvmm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhixingplan.top/Article/details/gtyojaqjgn.html

) t WHERE rn = 1;
来源：http://dali.chenzaomai.com/Article/details/gtxhaszitn.html

[Q35] 内连接
来源：http://dali.hnqzz.top/Article/details/gtjmdpwvmz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gtprigskuc.html

[Q36] 左连接
来源：http://dali.ivvv.top/Article/details/gtvwnhppmy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gtucsrbhar.html

[Q37] 右连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyrcqpyk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.dianchejie.cn/Article/details/gtbktatwji.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinqigfzy.top/Article/details/gtyxpuonhn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cdnleiting.top/Article/details/gtkkctbpaj.html

[Q39] 自连接（查上下级）
来源：http://dali.sweek.top/Article/details/gtbdlywqca.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnxiangtu.top/Article/details/gtrbroscrn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xylfe.cn/Article/details/gtplkblkfl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnwnjjrk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.316326.xyz/Article/details/gtrixagkno.html

[Q41] 多表连接
来源：http://dali.chenlongwang.top/Article/details/gtmambjurm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hongshengwenyu.top/Article/details/gtwcwxheiq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxkrtzedm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.iojbl.cn/Article/details/gtxjwhudgx.html

[Q42] 连接条件附加过滤
来源：http://dali.316326.xyz/Article/details/gtomotjyuc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sysykeji.top/Article/details/gtkbymbnvn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuanzhike.top/Article/details/gtzwxlvvmm.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gtynhvvyhl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jlsjyb.cn/Article/details/gtirmmvvol.html

[Q44] IN 子查询
来源：http://dali.havefunace.top/Article/details/gtdwfphcbm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jyoumei.cn/Article/details/gtefygbgsg.html

[Q45] EXISTS 判断存在
来源：http://dali.zhongyouzk.top/Article/details/gtingbvcda.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqthqrcdf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yongpay.top/Article/details/gtpzdfgpyi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xylfe.cn/Article/details/gtkcgllase.html

[Q47] 与平均值比较
来源：http://dali.zhiwuduotai.top/Article/details/gtddohkqka.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gzhubu.top/Article/details/gtjikgjoih.html

[Q48] CTE 公用表表达式
来源：http://dali.zhoulong.xyz/Article/details/gtfgynfdto.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.feifeiyinyue.top/Article/details/gtcymrzvcg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.birdmap.top/Article/details/gthfyjyxnf.html

[Q49] 更新单行
来源：http://dali.yj20258.top/Article/details/gtkkroilys.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.316326.xyz/Article/details/gttbdzaxyq.html

[Q50] 批量更新
来源：http://dali.cdnleiting.top/Article/details/gthfjlywcz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.svipenyu.cn/Article/details/gtzllouhtv.html

[Q51] 用子查询更新
来源：http://dali.daxiang520.top/Article/details/gtqcmcazna.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodtfxzcg.html

[Q52] 删除指定行
来源：http://dali.zycfv.cn/Article/details/gtpwdsmrwa.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gthsugqzrl.html

[Q53] 按条件删除
来源：http://dali.havefunace.top/Article/details/gtidpyrzer.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.meibo888.top/Article/details/gtzpgtlzxg.html

[Q54] 清空表
来源：http://dali.haohaochexian.top/Article/details/gtjvpfpwgp.html

TRUNCATE TABLE logs;
来源：http://dali.tanke756.top/Article/details/gtloiiggrp.html

[Q55] 排名（并列占位）
来源：http://dali.aizwys.cn/Article/details/gtcpzjdsmp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cdnleiting.top/Article/details/gtufcysncy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuanzx.com/Article/details/gttcqqkznt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhengqikj.top/Article/details/gtpherwlyp.html

[Q57] 行号
来源：http://dali.feifeiyinyue.top/Article/details/gtvfzsholj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.svipenyu.cn/Article/details/gthxroapvy.html

[Q58] 累计求和
来源：http://dali.hongshengwenyu.top/Article/details/gtkqlgsmcv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtihcjbxsp.html

[Q59] 分组内累计
来源：http://dali.jqgfzy.top/Article/details/gtxwlbtyas.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtmseqjmwf.html

[Q60] 取上一行 / 下一行
来源：http://dali.nwbrower.top/Article/details/gtllujdgtr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cashguo.top/Article/details/gtuoqoxagm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtmorgjbio.html

[Q61] 移动平均
来源：http://dali.0kj1m.cn/Article/details/gtjuobtspv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtunzjumpr.html

[Q62] 分组占比
来源：http://dali.guannengcc.top/Article/details/gtoxmyunzb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtllytfdou.html

[Q63] 开启事务
来源：http://dali.haohaochexian.top/Article/details/gtlqxewems.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.guowangkeji.top/Article/details/gtbbwbsftd.html

[Q64] 提交事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gteehzusny.html

COMMIT;
来源：http://dali.vqdsnc.cn/Article/details/gtnmffgnpt.html

[Q65] 回滚事务
来源：http://dali.svipenyu.cn/Article/details/gtkcigjgli.html

ROLLBACK;
来源：http://dali.zhixingplan.top/Article/details/gtfitgxsoa.html

[Q66] 行锁查询
来源：http://dali.gogol.net.cn/Article/details/gtuhlfxnme.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuetiantiany.cn/Article/details/gtulmlpard.html

[Q67] 设置隔离级别
来源：http://dali.jyoumei.cn/Article/details/gtbarlvrsw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xziqi.cn/Article/details/gtzypuphvr.html

[Q68] 保存点
来源：http://dali.havefunace.top/Article/details/gtsxfdefmc.html

SAVEPOINT sp1;
来源：http://dali.gogol.net.cn/Article/details/gtacmojzbu.html

ROLLBACK TO sp1;
来源：http://dali.jyoumei.cn/Article/details/gtagycylxu.html

[Q69] 查看执行计划
来源：http://dali.meibo888.top/Article/details/gtpivrqaub.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yongpay.top/Article/details/gtntnpzhab.html

[Q70] 更新统计信息
来源：http://dali.dashuyun.cn/Article/details/gtghrgqrhd.html

ANALYZE TABLE users;
来源：http://dali.nwbrower.top/Article/details/gtrhipavjw.html

[Q71] 查看建表语句
来源：http://dali.aizwys.cn/Article/details/gtihzhobiv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gtqfhihles.html

[Q72] 查看索引
来源：http://dali.mhx1999.top/Article/details/gtyujglrss.html

SHOW INDEX FROM users;
来源：http://dali.havefunace.top/Article/details/gtoxunvqih.html

[Q73] 查看表状态
来源：http://dali.shzxlz.cn/Article/details/gtehvokjim.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xuanzx.com/Article/details/gtbdhioros.html

[Q74] 强制使用索引
来源：http://dali.cheryme.top/Article/details/gtxccifpgh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yvedp.cn/Article/details/gtlajistsf.html

[Q75] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtgvrcvvyv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.316326.xyz/Article/details/gtjysgqxib.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nanxuanxn.top/Article/details/gtcsdqpbrj.html

[Q76] 按天统计
来源：http://dali.xylfe.cn/Article/details/gtvdkbyfle.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cdnleiting.top/Article/details/gtrlakvali.html

[Q77] 时间加减
来源：http://dali.meibo888.top/Article/details/gtagwmamfc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tian-w.cn/Article/details/gtqsxtjprf.html

[Q78] 当前时间
来源：http://dali.hfpthk.cn/Article/details/gtyhdlytmw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhixingplan.top/Article/details/gtzfminbfu.html

[Q79] 字符串拼接
来源：http://dali.ybcxt.top/Article/details/gtkyhmjhts.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgufenzy.top/Article/details/gtphafgsss.html

[Q80] 字符串截取
来源：http://dali.dashuyun.cn/Article/details/gtbanbloto.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtqzwgqocc.html

[Q81] 字符串替换
来源：http://dali.vqdsnc.cn/Article/details/gtzgwirfvu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.smart0.xyz/Article/details/gtsptnpbbv.html

[Q82] 字符长度与字节长度
来源：http://dali.zhixingplan.top/Article/details/gtzvslsqdi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtgqgnacmu.html

[Q83] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gtxqhmlyqs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtwdcjgroj.html

[Q84] 去除首尾空格
来源：http://dali.tian-w.cn/Article/details/gtallljwef.html

SELECT TRIM(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtzattjftl.html

[Q85] 数值取整
来源：http://dali.feifeiyinyue.top/Article/details/gtlsppheeg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cheryme.top/Article/details/gtqrferrzb.html

[Q86] 读取 JSON 字段
来源：http://dali.birdmap.top/Article/details/gtznktbilm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yuanzhike.top/Article/details/gtubrkcdxw.html

[Q87] JSON 字段做条件
来源：http://dali.vqdsnc.cn/Article/details/gtuuykqdib.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jianghu66.top/Article/details/gtwcdwrmut.html

[Q88] 行转列（条件聚合）
来源：http://dali.snrcjt.cn/Article/details/gtzkjhhwtp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhixingplan.top/Article/details/gtlrguygfh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtsqovjjzh.html

[Q89] 判断表是否存在
来源：http://dali.hnqzz.top/Article/details/gtxjstaick.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.smart0.xyz/Article/details/gtvpwckrsq.html

[Q90] 生成序号列
来源：http://dali.cashguo.top/Article/details/gtraxuafpx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tian-w.cn/Article/details/gtzhhxwplx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtyvbfilyk.html

R. Bash 专题
来源：http://dali.svipenyu.cn/Article/details/gtvzgrymlm.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtttgjgrgh.html

[R01] shebang 与严格模式
来源：http://dali.gogol.net.cn/Article/details/gtelhuskzr.html

#!/usr/bin/env bash
来源：http://dali.zycfv.cn/Article/details/gtxrihfquk.html

set -euo pipefail
来源：http://dali.sxryk.cn/Article/details/gtgdwebyvm.html

[R02] 变量赋值与使用
来源：http://dali.quarkkingdee.top/Article/details/gtwrrmwdlj.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gtwmlzvfxn.html

[R03] 只读变量
来源：http://dali.gzhubu.top/Article/details/gtxnjjtwgb.html

readonly PI=3.14
来源：http://dali.jinqigfzy.top/Article/details/gthaoalaaa.html

[R04] 位置参数
来源：http://dali.chenlongwang.top/Article/details/gtkmrxicnd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangshuangyany.cn/Article/details/gtyhwfkyjl.html

[R05] 参数默认值
来源：http://dali.cdnleiting.top/Article/details/gtjphixlfv.html

name="${1:-default}"
来源：http://dali.nanxuanxn.top/Article/details/gtlxenmtkk.html

[R06] 判断命令是否存在
来源：http://dali.zdqjudy.top/Article/details/gtixhubhzc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.iojbl.cn/Article/details/gtftxqbhuy.html

[R07] if 判断文件
来源：http://dali.snrcjt.cn/Article/details/gtgelyruou.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigufen.top/Article/details/gtsvsjrhyv.html

[R08] 数值比较
来源：http://dali.sysykeji.top/Article/details/gtgyzfsypc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtyyuunizu.html

[R09] 字符串比较
来源：http://dali.nanxinkj.top/Article/details/gtuulggwts.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuxming.cn/Article/details/gtprxbdxvo.html

[R10] 正则匹配
来源：http://dali.cashguo.top/Article/details/gtzfzleovr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ivvv.top/Article/details/gtcbnsicui.html

[R11] case 多分支
来源：http://dali.yuanzhike.top/Article/details/gtfhavbael.html

case "$1" in
来源：http://dali.nanxuanxn.top/Article/details/gtacbrlkyj.html

start) echo "启动" ;;
来源：http://dali.ehwqpu.com/Article/details/gtyfzeccqk.html

stop)  echo "停止" ;;
来源：http://dali.yj20258.top/Article/details/gtulhdutdc.html

*)     echo "未知命令" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadrpcfjj.html

esac
来源：http://dali.feifeiyinyue.top/Article/details/gtllohhkgy.html

[R12] for 遍历文件
来源：http://dali.sxryk.cn/Article/details/gtrsfhkxut.html

for f in *.txt; do echo "$f"; done
来源：http://dali.vqdsnc.cn/Article/details/gtrniszbde.html

[R13] for 计数循环
来源：http://dali.daxiang520.top/Article/details/gthrnooymy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gtizxeynkl.html

[R14] C 风格 for
来源：http://dali.fengsongda.top/Article/details/gtwcfkmuhw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.pycfn.com/Article/details/gtqyffmjpt.html

[R15] while 逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtboklincv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gaohongyu789.top/Article/details/gtekoicurg.html

[R16] until 等待条件
来源：http://dali.mhx1999.top/Article/details/gtgaddenks.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gtydudoxoj.html

[R17] 数组定义与取值
来源：http://dali.sysykeji.top/Article/details/gtwgaqzogb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhoulong.xyz/Article/details/gtpqszuzyz.html

[R18] 遍历数组
来源：http://dali.jianghu66.top/Article/details/gtoqpoiqlo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhoulong.xyz/Article/details/gtnzcosiju.html

[R19] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gtljytdgdh.html

echo "${#arr[@]}"
来源：http://dali.haohaochexian.top/Article/details/gtphizlcls.html

[R20] 关联数组（字典）
来源：http://dali.feifeiyinyue.top/Article/details/gtncacnxzh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nwbrower.top/Article/details/gthhtcsuis.html

[R21] 字符串长度
来源：http://dali.gotoacloud.top/Article/details/gtpwwjstrn.html

echo "${#s}"
来源：http://dali.yangfankeji.com/Article/details/gtggnhkyug.html

[R22] 截取子串
来源：http://dali.zhengqikj.top/Article/details/gtholyqzlx.html

echo "${s:0:5}"
来源：http://dali.nanxinkj.top/Article/details/gtsxjroiin.html

[R23] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gtwfbfsokn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhiwuduotai.top/Article/details/gtdpouoclg.html

[R24] 大小写转换
来源：http://dali.ydzc1.top/Article/details/gtakeqdtjh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkldjrspm.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhoulong.xyz/Article/details/gtnegdixyc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aizwys.cn/Article/details/gtkwqiydfz.html

[R26] 命令替换
来源：http://dali.guowangkeji.top/Article/details/gtdfeqniec.html

now=$(date +%F); echo "$now"
来源：http://dali.hammf.cn/Article/details/gtnhpjpvwl.html

[R27] 算术展开
来源：http://dali.ydzc1.top/Article/details/gtqjynroud.html

echo $((1 + 2 * 3))
来源：http://dali.c1oappe.top/Article/details/gtqzzwrboa.html

[R28] 浮点运算
来源：http://dali.jqgufenzy.top/Article/details/gtofybzbog.html

echo "scale=2; 10/3" | bc
来源：http://dali.svipenyu.cn/Article/details/gtqshavxpe.html

[R29] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gtnhcvcebg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yvedp.cn/Article/details/gtvjfdwsdv.html

[R30] 函数返回状态码
来源：http://dali.dianchejie.cn/Article/details/gtiptkrovi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shzxlz.cn/Article/details/gticeyqjaz.html

[R31] 局部变量
来源：http://dali.mhx1999.top/Article/details/gtrvsyzjup.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpudorawp.html

[R32] 参数个数校验
来源：http://dali.xinyue.icu/Article/details/gtzxlzaqpk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gtvchxgyam.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gttnvuohyz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.pycfn.com/Article/details/gtaobtmegv.html

[R34] 退出时清理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlsfprspm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hongshengwenyu.top/Article/details/gtmtnzpwgh.html

[R35] 后台执行并等待
来源：http://dali.xylfe.cn/Article/details/gtjxoyinkc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yangfankeji.com/Article/details/gtxfdwqlbe.html

[R36] 并发执行多个任务
来源：http://dali.yj202588.top/Article/details/gtsbaanheo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cucudq.cn/Article/details/gtlgwgpghl.html

[R37] 把输出赋给变量
来源：http://dali.sysykeji.top/Article/details/gtfiasvnyb.html

files=$(ls -1)
来源：http://dali.shuidangran.top/Article/details/gtrcmyfjqd.html

[R38] 管道串联
来源：http://dali.yj202588.top/Article/details/gtwfckrqsm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gzhubu.top/Article/details/gtpcitalke.html

[R39] 重定向标准输出与错误
来源：http://dali.haohaochexian.top/Article/details/gtzylwjmwd.html

cmd > out.log 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gtovgsrflv.html

[R40] 追加写日志
来源：http://dali.jinqigfzy.top/Article/details/gtnnjzxfks.html

echo "log" >> out.log
来源：http://dali.shangyingyoupin.top/Article/details/gtomuswhfh.html

[R41] 丢弃输出
来源：http://dali.daria6918.cn/Article/details/gtanjbmbbi.html

cmd >/dev/null 2>&1
来源：http://dali.c1oappe.top/Article/details/gtgrulypkk.html

[R42] 输入重定向
来源：http://dali.wangshuangyany.cn/Article/details/gtqtcshxoc.html

wc -l < a.txt
来源：http://dali.hnqzz.top/Article/details/gtgimovajq.html

[R43] 按名字查找文件
来源：http://dali.yuxming.cn/Article/details/gtiyzlosqz.html

find . -name "*.log" -type f
来源：http://dali.cqqwz.cn/Article/details/gtzhtqezcj.html

[R44] 按修改时间查找
来源：http://dali.kuanghao11.cn/Article/details/gttvsujrlp.html

find . -mtime -7 -type f
来源：http://dali.zhixingplan.top/Article/details/gtjwymecjx.html

[R45] 批量删除
来源：http://dali.xuetiantiany.cn/Article/details/gtihmygupp.html

find . -name "*.tmp" -delete
来源：http://dali.hfpthk.cn/Article/details/gtlopyisti.html

[R46] 递归替换文件内容
来源：http://dali.jianghu66.top/Article/details/gtkandactx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangdashe.top/Article/details/gtsqgknluk.html

[R47] sed 单行替换
来源：http://dali.yj20258888.top/Article/details/gtsnajbkau.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtquuwsllv.html

[R48] awk 取指定列
来源：http://dali.9152youxi.cn/Article/details/gtttcfcmty.html

awk '{print $1, $3}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtrnekohto.html

[R49] awk 带条件
来源：http://dali.andypj.xyz/Article/details/gtbjnutubt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj202588.top/Article/details/gtxtrnqkeg.html

[R50] awk 求和
来源：http://dali.nanxuanxn.top/Article/details/gtmykgltna.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.wangdashe.top/Article/details/gtscxaouzb.html

[R51] 排序去重取前几
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumznvmmq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijpcxnfs.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gtdmihcpox.html

wc -l a.txt
来源：http://dali.yvedp.cn/Article/details/gtfmwaqofv.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxuanxn.top/Article/details/gtibpgkxnf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jianghu66.top/Article/details/gtveptytxy.html

[R54] 比较两个文件
来源：http://dali.xylfe.cn/Article/details/gtgzltefhp.html

diff a.txt b.txt
来源：http://dali.jqgufenzy.top/Article/details/gtazdnezyz.html

[R55] 压缩与解压
来源：http://dali.yvedp.cn/Article/details/gtavywrsjs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.wangshuangyany.cn/Article/details/gtgwrcqqkv.html

[R56] 远程拷贝
来源：http://dali.haohaochexian.top/Article/details/gtjdieowtb.html

scp file user@host:/path/
来源：http://dali.shzxlz.cn/Article/details/gteuyhhjcy.html

[R57] 远程执行命令
来源：http://dali.yueranfly.top/Article/details/gtxlldfxyi.html

ssh user@host 'uptime'
来源：http://dali.nanxinkj.top/Article/details/gtmwxjkknh.html

[R58] 下载文件
来源：http://dali.cashguo.top/Article/details/gtefglwqtx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yanxiufei.cn/Article/details/gtdgtmrzbg.html

[R59] 发 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gtrlcqlahv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zdqjudy.top/Article/details/gtofkmghjq.html

[R60] 只看 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gtazhpipym.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj20258.top/Article/details/gtqajblgee.html

[R61] 磁盘占用
来源：http://dali.chenjidiqi.icu/Article/details/gtavvbcpln.html

df -h;  du -sh *
来源：http://dali.gotoacloud.top/Article/details/gtxdsuqumb.html

[R62] 找最占空间的文件
来源：http://dali.gotoacloud.top/Article/details/gtxmvgbfdk.html

du -ah . | sort -rh | head -10
来源：http://dali.jiagoushi.top/Article/details/gtcbuwxiyr.html

[R63] 内存与进程
来源：http://dali.shanyushiyangtech.top/Article/details/gtavnnjflz.html

free -h;  ps aux | grep nginx
来源：http://dali.sufxvd.cn/Article/details/gtslhtmhcw.html

[R64] 结束进程
来源：http://dali.guowangkeji.top/Article/details/gtdxxmxkqq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.c1oappe.top/Article/details/gtnwawthzr.html

[R65] 查看端口占用
来源：http://dali.jyoumei.cn/Article/details/gtmnzotpyw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hysaishi.cn/Article/details/gtwabeyofr.html

[R66] 定时任务
来源：http://dali.birdmap.top/Article/details/gtrgoblica.html

crontab -e;  crontab -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzqjrfzr.html

[R67] 生成随机十六进制串
来源：http://dali.havefunace.top/Article/details/gtgocfstjx.html

openssl rand -hex 16
来源：http://dali.redwolf501.top/Article/details/gthmamzzzq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gtrktxjlrj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nanxinkj.top/Article/details/gtpirpkaoc.html

[R69] 生成随机密码
来源：http://dali.jqgufenzy.top/Article/details/gtwvfrqiie.html

head -c 16 /dev/urandom | base64
来源：http://dali.sufxvd.cn/Article/details/gtffnbuqmo.html

[R70] 时间戳与互转
来源：http://dali.vqdsnc.cn/Article/details/gtiemsarii.html

date +%s;  date -d @1700000000
来源：http://dali.hongshengwenyu.top/Article/details/gtclxrfufq.html

[R71] 日期格式化
来源：http://dali.tianlin.xyz/Article/details/gtnpmnfaou.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.fengsongda.top/Article/details/gtqgdrugjl.html

[R72] 等待端口就绪
来源：http://dali.jianghu66.top/Article/details/gtehbyjidq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.birdmap.top/Article/details/gtozwnouly.html

[R73] 分割大日志
来源：http://dali.jqgfzy.top/Article/details/gtrycljmvk.html

split -l 1000 big.log part_
来源：http://dali.iojbl.cn/Article/details/gtnqyimvrt.html

[R74] 批量重命名
来源：http://dali.sxryk.cn/Article/details/gtoitjnums.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.daxiang520.top/Article/details/gtavenasxn.html

[R75] 导出环境变量
来源：http://dali.ivvv.top/Article/details/gtmnlwjqin.html


<!-- 参考信息 -->