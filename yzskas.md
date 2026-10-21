代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jiagoushi.top/Article/details/gttvuahfcw.html

[Q24] 去重
来源：http://dali.hongshengwenyu.top/Article/details/gtuwmcdljc.html

SELECT DISTINCT city FROM users;
来源：http://dali.pycfn.com/Article/details/gtuortivoa.html

[Q25] 只取前 N 条
来源：http://dali.cqqwz.cn/Article/details/gtplbmkkai.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.dashuyun.cn/Article/details/gtzqkedfzi.html

[Q26] 计数
来源：http://dali.sysykeji.top/Article/details/gtnalubpkm.html

SELECT COUNT(*) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxxvwbyy.html

[Q27] 条件计数
来源：http://dali.ydzc1.top/Article/details/gtrvomaubp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangdashe.top/Article/details/gtzqsamiid.html

[Q28] 求和与平均
来源：http://dali.hysaishi.cn/Article/details/gtvastblyc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gttffwdyzu.html

[Q29] 最大最小值
来源：http://dali.birdmap.top/Article/details/gtuawkdhey.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.316326.xyz/Article/details/gtmahoxqya.html

[Q30] 分组统计
来源：http://dali.tanke756.top/Article/details/gtzvefmkyc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gtvpybjvak.html

[Q31] 分组后过滤
来源：http://dali.yj202588.top/Article/details/gtqmkkfieo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yongpay.top/Article/details/gtyobyaxou.html

[Q32] 分组拼接字符串
来源：http://dali.fengsongda.top/Article/details/gtpyputhsx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gtgdkhgwnq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sysykeji.top/Article/details/gtpqwexsod.html

[Q33] 多列分组
来源：http://dali.jqgufenzy.top/Article/details/gtihhcgbtw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aibaodan.cn/Article/details/gtvrqpkbhm.html

[Q34] 每组取第一条
来源：http://dali.hysaishi.cn/Article/details/gtkkjqemlg.html

SELECT * FROM (
来源：http://dali.yangfankeji.com/Article/details/gtzzyesjms.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.quarkkingdee.top/Article/details/gtwhmhlbqh.html

) t WHERE rn = 1;
来源：http://dali.iojbl.cn/Article/details/gtzcingnth.html

[Q35] 内连接
来源：http://dali.yongpay.top/Article/details/gtiqwlcfhl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gtiotkoojd.html

[Q36] 左连接
来源：http://dali.yuxming.cn/Article/details/gtbmswljkl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.316326.xyz/Article/details/gthvyvpqhz.html

[Q37] 右连接
来源：http://dali.svipenyu.cn/Article/details/gttyybqxlb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzlrwiaef.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zycfv.cn/Article/details/gttgqirjmk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yuanzhike.top/Article/details/gtitrmpnbq.html

[Q39] 自连接（查上下级）
来源：http://dali.zhoulong.xyz/Article/details/gtpqfnhioz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sysykeji.top/Article/details/gtnciszeyy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinqigufen.top/Article/details/gtgcokmtmi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.iojbl.cn/Article/details/gtmrxjyais.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhongyouzk.top/Article/details/gtriwbrlue.html

[Q41] 多表连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvdhhzsb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ybcxt.top/Article/details/gtoyoxhaxq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.feifeiyinyue.top/Article/details/gtzsqkbcgb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.wangshuangyany.cn/Article/details/gtixflldab.html

[Q42] 连接条件附加过滤
来源：http://dali.jianghu66.top/Article/details/gtuypisnqf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhiwuduotai.top/Article/details/gtfjvjkmtw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.wangshuangyany.cn/Article/details/gtwbjcuapp.html

[Q43] 标量子查询
来源：http://dali.daxiang520.top/Article/details/gtoitjopdl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.tian-w.cn/Article/details/gtjcguqfha.html

[Q44] IN 子查询
来源：http://dali.hysaishi.cn/Article/details/gtqoiesjae.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ehwqpu.com/Article/details/gtdfdnkgsl.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhcnowlg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jyoumei.cn/Article/details/gttkpfsnrj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.316326.xyz/Article/details/gthutrolrj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangdashe.top/Article/details/gtjpzdwlvk.html

[Q47] 与平均值比较
来源：http://dali.snrcjt.cn/Article/details/gtxqbonjdb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yvedp.cn/Article/details/gtjqtbkmhp.html

[Q48] CTE 公用表表达式
来源：http://dali.birdmap.top/Article/details/gtwmgyhsky.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.c1oappe.top/Article/details/gtxyocguwc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.9152youxi.cn/Article/details/gtgtifssbq.html

[Q49] 更新单行
来源：http://dali.shzxlz.cn/Article/details/gtdyujjmhi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtszrxcsyq.html

[Q50] 批量更新
来源：http://dali.yonumen.top/Article/details/gtjnaulfxo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.316326.xyz/Article/details/gtghduvmbj.html

[Q51] 用子查询更新
来源：http://dali.sysykeji.top/Article/details/gtlfinypym.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtjjnzufao.html

[Q52] 删除指定行
来源：http://dali.guowangkeji.top/Article/details/gtrcovgtiw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gtdwuycjxj.html

[Q53] 按条件删除
来源：http://dali.chenjidiqi.icu/Article/details/gtwglantso.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gotoacloud.top/Article/details/gtcueroobr.html

[Q54] 清空表
来源：http://dali.sufxvd.cn/Article/details/gtgoadhtxc.html

TRUNCATE TABLE logs;
来源：http://dali.yvedp.cn/Article/details/gtntbdralo.html

[Q55] 排名（并列占位）
来源：http://dali.hnxiangtu.top/Article/details/gtdgnzbrfh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yongpay.top/Article/details/gtzgaumgzk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nwbrower.top/Article/details/gtlzscdiin.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gtxjtvgdln.html

[Q57] 行号
来源：http://dali.zhiwuduotai.top/Article/details/gtrprdqbsl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.bjfxy.top/Article/details/gtwcpnsokx.html

[Q58] 累计求和
来源：http://dali.jinqigufen.top/Article/details/gtfljowxuj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.birdmap.top/Article/details/gtlqxxpmzx.html

[Q59] 分组内累计
来源：http://dali.havefunace.top/Article/details/gthrgdiarh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtperzibfa.html

[Q60] 取上一行 / 下一行
来源：http://dali.sweek.top/Article/details/gtkhnncijg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.c1oappe.top/Article/details/gtjmwyghaj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtocmanahs.html

[Q61] 移动平均
来源：http://dali.gaohongyu789.top/Article/details/gttwyyrsvw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtqhlsffap.html

[Q62] 分组占比
来源：http://dali.ppjwa.cn/Article/details/gtyqetqxxk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gtaszfpzaq.html

[Q63] 开启事务
来源：http://dali.ivvv.top/Article/details/gtqoyzpcdv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fengsongda.top/Article/details/gtxuvdtwme.html

[Q64] 提交事务
来源：http://dali.yj20258888.top/Article/details/gtihtdiunl.html

COMMIT;
来源：http://dali.daxiang520.top/Article/details/gtxkqqlmxz.html

[Q65] 回滚事务
来源：http://dali.guannengcc.top/Article/details/gtepaomudb.html

ROLLBACK;
来源：http://dali.ppjwa.cn/Article/details/gtawywtqzq.html

[Q66] 行锁查询
来源：http://dali.nanxinkj.top/Article/details/gtkpstbcgy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhixingplan.top/Article/details/gtyanpbyrj.html

[Q67] 设置隔离级别
来源：http://dali.xinyue.icu/Article/details/gtbndymaqe.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aibaodan.cn/Article/details/gtrpccimeu.html

[Q68] 保存点
来源：http://dali.chenzaomai.com/Article/details/gtuztnszor.html

SAVEPOINT sp1;
来源：http://dali.ehwqpu.com/Article/details/gtmoklvggu.html

ROLLBACK TO sp1;
来源：http://dali.yj20258.top/Article/details/gtdilwezfk.html

[Q69] 查看执行计划
来源：http://dali.jqgfzy.top/Article/details/gtjugzlgbi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.svipenyu.cn/Article/details/gtvgpcmozc.html

[Q70] 更新统计信息
来源：http://dali.sufxvd.cn/Article/details/gthacettgq.html

ANALYZE TABLE users;
来源：http://dali.ehwqpu.com/Article/details/gtauxuknij.html

[Q71] 查看建表语句
来源：http://dali.gotoacloud.top/Article/details/gtmhcfddzt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cqqwz.cn/Article/details/gteuqqwfgk.html

[Q72] 查看索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzuzypcvc.html

SHOW INDEX FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gttvhnibgz.html

[Q73] 查看表状态
来源：http://dali.hywenlv.cn/Article/details/gtotrmdjdl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ppjwa.cn/Article/details/gtmyuodqct.html

[Q74] 强制使用索引
来源：http://dali.smart0.xyz/Article/details/gtfbjansya.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yuxming.cn/Article/details/gtypovxmat.html

[Q75] 日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gtacpodypi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hammf.cn/Article/details/gtwcheudfb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.redwolf501.top/Article/details/gtfzkeqaqh.html

[Q76] 按天统计
来源：http://dali.yongpay.top/Article/details/gtylfpslyn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.0kj1m.cn/Article/details/gtuuoiyegz.html

[Q77] 时间加减
来源：http://dali.ybcxt.top/Article/details/gtlapfwzqb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxmgycih.html

[Q78] 当前时间
来源：http://dali.fzhhl.top/Article/details/gthrwgjlms.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.dashuyun.cn/Article/details/gtpechlgkv.html

[Q79] 字符串拼接
来源：http://dali.feifeiyinyue.top/Article/details/gtmqlcxzgl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.9152youxi.cn/Article/details/gtigraankm.html

[Q80] 字符串截取
来源：http://dali.tanke756.top/Article/details/gtavywnxro.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtqppdvcmo.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtichsclij.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cashguo.top/Article/details/gtluhhviea.html

[Q82] 字符长度与字节长度
来源：http://dali.yongpay.top/Article/details/gtwmodzmgo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtorxwhvyy.html

[Q83] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gthjmhywec.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtecclvxap.html

[Q84] 去除首尾空格
来源：http://dali.feifeiyinyue.top/Article/details/gteecqwxnt.html

SELECT TRIM(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtudtydles.html

[Q85] 数值取整
来源：http://dali.yonumen.top/Article/details/gtdkitgsaq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydgxhaxg.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258.top/Article/details/gtzwkddkxg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenlongwang.top/Article/details/gtmpgdljgy.html

[Q87] JSON 字段做条件
来源：http://dali.kuanghao11.cn/Article/details/gtxtdojnjs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenjidiqi.icu/Article/details/gtctivomfd.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinqigfzy.top/Article/details/gtxpfspdsg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.bjfxy.top/Article/details/gtqmcoitui.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtuzzokilw.html

[Q89] 判断表是否存在
来源：http://dali.cheryme.top/Article/details/gteqyagrwa.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shuidangran.top/Article/details/gtchrbicom.html

[Q90] 生成序号列
来源：http://dali.wangdashe.top/Article/details/gtrjcdxycd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aibaodan.cn/Article/details/gtbaurtgft.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtckbrmqrv.html

R. Bash 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypqjsmyk.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtozzggcba.html

[R01] shebang 与严格模式
来源：http://dali.gzhubu.top/Article/details/gtetedfmmf.html

#!/usr/bin/env bash
来源：http://dali.hnqzz.top/Article/details/gtmbulxpjo.html

set -euo pipefail
来源：http://dali.gzhubu.top/Article/details/gttebgobun.html

[R02] 变量赋值与使用
来源：http://dali.zhiwuduotai.top/Article/details/gtlxsgvhuy.html

name="Tom"; echo "$name"
来源：http://dali.shuidangran.top/Article/details/gttxwuxwkw.html

[R03] 只读变量
来源：http://dali.smart0.xyz/Article/details/gtkbksstmh.html

readonly PI=3.14
来源：http://dali.xziqi.cn/Article/details/gtiimqgvig.html

[R04] 位置参数
来源：http://dali.cheryme.top/Article/details/gtoognvvwa.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuxming.cn/Article/details/gtzdazforp.html

[R05] 参数默认值
来源：http://dali.gaohongyu789.top/Article/details/gtfeprkvga.html

name="${1:-default}"
来源：http://dali.xinyue.icu/Article/details/gtuzxaccdj.html

[R06] 判断命令是否存在
来源：http://dali.gzhubu.top/Article/details/gtxvactttq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jlsjyb.cn/Article/details/gtdizusuzg.html

[R07] if 判断文件
来源：http://dali.chenzaomai.com/Article/details/gtsbkmwzdm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gotoacloud.top/Article/details/gtkwogvvkx.html

[R08] 数值比较
来源：http://dali.nanxuanxn.top/Article/details/gtdxgxrnem.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcevaepon.html

[R09] 字符串比较
来源：http://dali.cucudq.cn/Article/details/gtnwljpfye.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinqigufen.top/Article/details/gtvcuvbnxd.html

[R10] 正则匹配
来源：http://dali.vqdsnc.cn/Article/details/gtyrcyzhtl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ydzc1.top/Article/details/gtopzllqay.html

[R11] case 多分支
来源：http://dali.iojbl.cn/Article/details/gtnggsaztq.html

case "$1" in
来源：http://dali.svipenyu.cn/Article/details/gtdaxvvarg.html

start) echo "启动" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqupkeuzh.html

stop)  echo "停止" ;;
来源：http://dali.9152youxi.cn/Article/details/gtwhzqfctd.html

*)     echo "未知命令" ;;
来源：http://dali.sufxvd.cn/Article/details/gttwwaworo.html

esac
来源：http://dali.yj202588.top/Article/details/gtctbdzuhq.html

[R12] for 遍历文件
来源：http://dali.haohaochexian.top/Article/details/gtirtklntw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenlongwang.top/Article/details/gtwtynbmgp.html

[R13] for 计数循环
来源：http://dali.kuanghao11.cn/Article/details/gttacawrpq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.andypj.xyz/Article/details/gtecekioxb.html

[R14] C 风格 for
来源：http://dali.zdqjudy.top/Article/details/gtmnghydjv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gtuxyzqkwb.html

[R15] while 逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtjmpprmtb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtppszsttl.html

[R16] until 等待条件
来源：http://dali.zdqjudy.top/Article/details/gtycvjjnhx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gtgtqaywfl.html

[R17] 数组定义与取值
来源：http://dali.xylfe.cn/Article/details/gtimmmvccj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ybcxt.top/Article/details/gtklyjivyt.html

[R18] 遍历数组
来源：http://dali.xuetiantiany.cn/Article/details/gtzqfccdce.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cdnleiting.top/Article/details/gtxikwnuow.html

[R19] 数组长度
来源：http://dali.daxiang520.top/Article/details/gtxfpvricq.html

echo "${#arr[@]}"
来源：http://dali.9152youxi.cn/Article/details/gtaafyufea.html

[R20] 关联数组（字典）
来源：http://dali.zycfv.cn/Article/details/gtvlknxbnq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxinkj.top/Article/details/gttbkceydz.html

[R21] 字符串长度
来源：http://dali.cheryme.top/Article/details/gtvshhmphj.html

echo "${#s}"
来源：http://dali.chenjidiqi.icu/Article/details/gtbfiqgqkd.html

[R22] 截取子串
来源：http://dali.gzhubu.top/Article/details/gtdyiyqzsf.html

echo "${s:0:5}"
来源：http://dali.chenjidiqi.icu/Article/details/gtqwyaivvp.html

[R23] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gtfvwaboge.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cdnleiting.top/Article/details/gtjfcldcmz.html

[R24] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gtmkhlbaua.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jqgufenzy.top/Article/details/gtgqikivkt.html

[R25] 去后缀 / 去前缀
来源：http://dali.haohaochexian.top/Article/details/gtlllcyszr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.316326.xyz/Article/details/gtbedychbi.html

[R26] 命令替换
来源：http://dali.jiagoushi.top/Article/details/gtixydfxpb.html

now=$(date +%F); echo "$now"
来源：http://dali.yanxiufei.cn/Article/details/gthmmrkjao.html

[R27] 算术展开
来源：http://dali.wangdashe.top/Article/details/gtsydqkuyy.html

echo $((1 + 2 * 3))
来源：http://dali.svipenyu.cn/Article/details/gtiezitshy.html

[R28] 浮点运算
来源：http://dali.xziqi.cn/Article/details/gtysenmiqu.html

echo "scale=2; 10/3" | bc
来源：http://dali.yueranfly.top/Article/details/gtukskrkjj.html

[R29] 定义函数
来源：http://dali.wangdashe.top/Article/details/gtfdsqvbuk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangdashe.top/Article/details/gtoiuwbqme.html

[R30] 函数返回状态码
来源：http://dali.shzxlz.cn/Article/details/gtxeycnsnw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gteaclipta.html

[R31] 局部变量
来源：http://dali.9152youxi.cn/Article/details/gteuayosxk.html

f() { local x=1; echo "$x"; }
来源：http://dali.sufxvd.cn/Article/details/gtjemgrfbu.html

[R32] 参数个数校验
来源：http://dali.ehwqpu.com/Article/details/gtnvpxedlc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj20258.top/Article/details/gtdxxjqyef.html

[R33] 捕获错误并提示行号
来源：http://dali.ydzc1.top/Article/details/gtycpxwfft.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinqigfzy.top/Article/details/gtxxsocfhm.html

[R34] 退出时清理
来源：http://dali.shzxlz.cn/Article/details/gtkisgtrtm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hysaishi.cn/Article/details/gtqjffobae.html

[R35] 后台执行并等待
来源：http://dali.zhixingplan.top/Article/details/gtajnsrmpx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ybcxt.top/Article/details/gtewdlbvuq.html

[R36] 并发执行多个任务
来源：http://dali.dashuyun.cn/Article/details/gtzndtppvm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shangyingyoupin.top/Article/details/gtwbybeeqi.html

[R37] 把输出赋给变量
来源：http://dali.yuxming.cn/Article/details/gtludlpfqn.html

files=$(ls -1)
来源：http://dali.yj20258.top/Article/details/gtvdkaclsk.html

[R38] 管道串联
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdexgpxuk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sysykeji.top/Article/details/gtanmbatfv.html

[R39] 重定向标准输出与错误
来源：http://dali.ehwqpu.com/Article/details/gtwgqhiwzd.html

cmd > out.log 2>&1
来源：http://dali.jyoumei.cn/Article/details/gtjwtvqanj.html

[R40] 追加写日志
来源：http://dali.zhongyouzk.top/Article/details/gtmfemlnna.html

echo "log" >> out.log
来源：http://dali.c1oappe.top/Article/details/gtfnqlvbjh.html

[R41] 丢弃输出
来源：http://dali.yongpay.top/Article/details/gtrouigdcx.html

cmd >/dev/null 2>&1
来源：http://dali.9152youxi.cn/Article/details/gtryigztmu.html

[R42] 输入重定向
来源：http://dali.gotoacloud.top/Article/details/gtvhrzvfrd.html

wc -l < a.txt
来源：http://dali.guowangkeji.top/Article/details/gtmfxjueub.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gtrtytjsty.html

find . -name "*.log" -type f
来源：http://dali.aibaodan.cn/Article/details/gtutusvqqi.html

[R44] 按修改时间查找
来源：http://dali.xziqi.cn/Article/details/gtlruaqwyh.html

find . -mtime -7 -type f
来源：http://dali.zhoulong.xyz/Article/details/gttoqplglb.html

[R45] 批量删除
来源：http://dali.fengsongda.top/Article/details/gtybfoysis.html

find . -name "*.tmp" -delete
来源：http://dali.smart0.xyz/Article/details/gtmlnkglvs.html

[R46] 递归替换文件内容
来源：http://dali.cqqwz.cn/Article/details/gtjjaswazs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.vqdsnc.cn/Article/details/gttgezzwkc.html

[R47] sed 单行替换
来源：http://dali.chenjidiqi.icu/Article/details/gtvutppybb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xylfe.cn/Article/details/gttsjnatys.html

[R48] awk 取指定列
来源：http://dali.zhengqikj.top/Article/details/gtdgehdffy.html

awk '{print $1, $3}' a.txt
来源：http://dali.dianchejie.cn/Article/details/gtoyjcvldq.html

[R49] awk 带条件
来源：http://dali.feifeiyinyue.top/Article/details/gtufzwipjo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj202588.top/Article/details/gthiqzaokr.html

[R50] awk 求和
来源：http://dali.daxiang520.top/Article/details/gtliedovse.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.iojbl.cn/Article/details/gtwjaqkrsn.html

[R51] 排序去重取前几
来源：http://dali.cashguo.top/Article/details/gtvcxmehbk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yanxiufei.cn/Article/details/gtrgmacfph.html

[R52] 统计行数
来源：http://dali.hammf.cn/Article/details/gtuzvgmelp.html

wc -l a.txt
来源：http://dali.jiagoushi.top/Article/details/gtlfvmwnhg.html

[R53] 查看文件头与实时尾
来源：http://dali.shuidangran.top/Article/details/gtbyfhlwvp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yonumen.top/Article/details/gtlxfrfyns.html

[R54] 比较两个文件
来源：http://dali.ehwqpu.com/Article/details/gtqqnljsxq.html

diff a.txt b.txt
来源：http://dali.ybcxt.top/Article/details/gtvrjzvqhh.html

[R55] 压缩与解压
来源：http://dali.gzhubu.top/Article/details/gtqszjcwny.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.0kj1m.cn/Article/details/gtoytvmwfu.html

[R56] 远程拷贝
来源：http://dali.tianlin.xyz/Article/details/gtpjsjrtgh.html

scp file user@host:/path/
来源：http://dali.shuidangran.top/Article/details/gthnnlbkpe.html

[R57] 远程执行命令
来源：http://dali.ehwqpu.com/Article/details/gtctbdijsv.html

ssh user@host 'uptime'
来源：http://dali.sufxvd.cn/Article/details/gtveddmjnz.html

[R58] 下载文件
来源：http://dali.dashuyun.cn/Article/details/gtggnskcvr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxinkj.top/Article/details/gtctxvphwl.html

[R59] 发 POST JSON
来源：http://dali.hammf.cn/Article/details/gtpbaguoby.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yangfankeji.com/Article/details/gtpmjzinvp.html

[R60] 只看 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gtkmsgfgyu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pengpengdd.cyou/Article/details/gtpcsdosjk.html

[R61] 磁盘占用
来源：http://dali.nanxinkj.top/Article/details/gtipntzmhe.html

df -h;  du -sh *
来源：http://dali.nanxinkj.top/Article/details/gthjvhgsvy.html

[R62] 找最占空间的文件
来源：http://dali.daxiang520.top/Article/details/gtzsyrvvbu.html

du -ah . | sort -rh | head -10
来源：http://dali.gotoacloud.top/Article/details/gtvqzseixm.html

[R63] 内存与进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpnsvrdq.html

free -h;  ps aux | grep nginx
来源：http://dali.snrcjt.cn/Article/details/gtdczjytyd.html

[R64] 结束进程
来源：http://dali.hnqzz.top/Article/details/gtfniluexk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinqigufen.top/Article/details/gtupbvkoeg.html

[R65] 查看端口占用
来源：http://dali.sysykeji.top/Article/details/gtrwjlyxoj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.aizwys.cn/Article/details/gtgxvpjsrf.html

[R66] 定时任务
来源：http://dali.svipenyu.cn/Article/details/gtcpcpwnca.html

crontab -e;  crontab -l
来源：http://dali.ehwqpu.com/Article/details/gtokfbqcwk.html

[R67] 生成随机十六进制串
来源：http://dali.pycfn.com/Article/details/gtwogxeggf.html

openssl rand -hex 16
来源：http://dali.yueranfly.top/Article/details/gtnojlrurx.html

[R68] 计算文件校验值
来源：http://dali.wangdashe.top/Article/details/gtrtdwhnfh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ivvv.top/Article/details/gtbzfulvhi.html

[R69] 生成随机密码
来源：http://dali.ybcxt.top/Article/details/gtopmqelqr.html

head -c 16 /dev/urandom | base64
来源：http://dali.0kj1m.cn/Article/details/gtitgedlea.html

[R70] 时间戳与互转
来源：http://dali.aibaodan.cn/Article/details/gtohuoceti.html

date +%s;  date -d @1700000000
来源：http://dali.daxiang520.top/Article/details/gtacrcivpo.html

[R71] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtlcrltshw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nanxuanxn.top/Article/details/gtrlanzoif.html

[R72] 等待端口就绪
来源：http://dali.aibaodan.cn/Article/details/gtojnxqjli.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gtupnxlesu.html

[R73] 分割大日志
来源：http://dali.hysaishi.cn/Article/details/gtkubgovyc.html


<!-- 参考信息 -->