代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gaohongyu789.top/Article/details/gttommmsuw.html

[Q24] 去重
来源：http://dali.xuanzx.com/Article/details/gtaoegduxx.html

SELECT DISTINCT city FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtjnrzmtfe.html

[Q25] 只取前 N 条
来源：http://dali.ivvv.top/Article/details/gtfwzupepp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhixingplan.top/Article/details/gtplvpphji.html

[Q26] 计数
来源：http://dali.tian-w.cn/Article/details/gtlfzivpat.html

SELECT COUNT(*) FROM users;
来源：http://dali.cheryme.top/Article/details/gtuiogsqeh.html

[Q27] 条件计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhxgckto.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtnwfkvdqq.html

[Q28] 求和与平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlguduymr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtyrdneabk.html

[Q29] 最大最小值
来源：http://dali.sysykeji.top/Article/details/gtccmsuyte.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gthgeuzdau.html

[Q30] 分组统计
来源：http://dali.sufxvd.cn/Article/details/gtjssnwheb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gtxekolyyk.html

[Q31] 分组后过滤
来源：http://dali.dianchejie.cn/Article/details/gthvuoiwsh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.316326.xyz/Article/details/gtqsijnomh.html

[Q32] 分组拼接字符串
来源：http://dali.cashguo.top/Article/details/gtyqyekmfi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxmsthyh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zycfv.cn/Article/details/gtqjjrlnaq.html

[Q33] 多列分组
来源：http://dali.havefunace.top/Article/details/gtnhbejxwi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ybcxt.top/Article/details/gtcbypujhs.html

[Q34] 每组取第一条
来源：http://dali.cdnleiting.top/Article/details/gtcxbkohyc.html

SELECT * FROM (
来源：http://dali.vqdsnc.cn/Article/details/gtzqnjluts.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yvedp.cn/Article/details/gtsmapyuir.html

) t WHERE rn = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtpzybavkp.html

[Q35] 内连接
来源：http://dali.svipenyu.cn/Article/details/gtwmydyuym.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gtrvmdnkeu.html

[Q36] 左连接
来源：http://dali.hywenlv.cn/Article/details/gtkikwoize.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sysykeji.top/Article/details/gttupzkbjj.html

[Q37] 右连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldiaoumt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.dianchejie.cn/Article/details/gtzqlpeamc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.vqdsnc.cn/Article/details/gtpbttadhe.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrenwidn.html

[Q39] 自连接（查上下级）
来源：http://dali.dianchejie.cn/Article/details/gtmafmodih.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cdnleiting.top/Article/details/gtavtikcjp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.316326.xyz/Article/details/gtdeqqjemh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yongpay.top/Article/details/gthlmaeksc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenjidiqi.icu/Article/details/gtzqhqgpbs.html

[Q41] 多表连接
来源：http://dali.nanxuanxn.top/Article/details/gtauukfxeb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhixingplan.top/Article/details/gtgwsicbbz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.316326.xyz/Article/details/gtzkczfwsb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yonumen.top/Article/details/gtzbajaqhp.html

[Q42] 连接条件附加过滤
来源：http://dali.chenlongwang.top/Article/details/gtxajwxiak.html

SELECT u.name, o.amount FROM users u
来源：http://dali.snrcjt.cn/Article/details/gtzlttxlby.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aizwys.cn/Article/details/gtuaveohqs.html

[Q43] 标量子查询
来源：http://dali.cheryme.top/Article/details/gtmwhqimrs.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sufxvd.cn/Article/details/gtevbttozg.html

[Q44] IN 子查询
来源：http://dali.tanke756.top/Article/details/gtmhzdyulw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtickwtich.html

[Q45] EXISTS 判断存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvtdndrzw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gtoynxlzmi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sysykeji.top/Article/details/gtkxkmtoeg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tanke756.top/Article/details/gtsufzmjcd.html

[Q47] 与平均值比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzcurofw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlobbonnq.html

[Q48] CTE 公用表表达式
来源：http://dali.xinyue.icu/Article/details/gtvrpxicnw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aizwys.cn/Article/details/gtyzleebsq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgahxswm.html

[Q49] 更新单行
来源：http://dali.yvedp.cn/Article/details/gtaikrxhnc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtadtghozk.html

[Q50] 批量更新
来源：http://dali.wangshuangyany.cn/Article/details/gtpsgsvttj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.9152youxi.cn/Article/details/gttvgqmoug.html

[Q51] 用子查询更新
来源：http://dali.sufxvd.cn/Article/details/gtggapqzil.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.316326.xyz/Article/details/gtreffrzdw.html

[Q52] 删除指定行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkfoxhcd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj202588.top/Article/details/gtmibntjdb.html

[Q53] 按条件删除
来源：http://dali.sweek.top/Article/details/gtjwzbemiu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.c1oappe.top/Article/details/gtfuroiroi.html

[Q54] 清空表
来源：http://dali.cqqwz.cn/Article/details/gthzeyzbhc.html

TRUNCATE TABLE logs;
来源：http://dali.xylfe.cn/Article/details/gtljxczvyv.html

[Q55] 排名（并列占位）
来源：http://dali.xziqi.cn/Article/details/gtwkzykzdz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sweek.top/Article/details/gtbirystin.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dashuyun.cn/Article/details/gtxuazcecu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj20258.top/Article/details/gtqbizvjbk.html

[Q57] 行号
来源：http://dali.9152youxi.cn/Article/details/gtzcfxxqgf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xinyue.icu/Article/details/gtiypofqiw.html

[Q58] 累计求和
来源：http://dali.shzxlz.cn/Article/details/gtkmrvbzyt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtqevewxkk.html

[Q59] 分组内累计
来源：http://dali.shzxlz.cn/Article/details/gtunztpvph.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtbjsgpzvz.html

[Q60] 取上一行 / 下一行
来源：http://dali.tanke756.top/Article/details/gtggplrbax.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.dashuyun.cn/Article/details/gtwcdgctes.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqaqywsbo.html

[Q61] 移动平均
来源：http://dali.jinqigufen.top/Article/details/gtngqedsnf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtzsxrzwqf.html

[Q62] 分组占比
来源：http://dali.ivvv.top/Article/details/gtwkwjbohc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtzllkbnzy.html

[Q63] 开启事务
来源：http://dali.hongshengwenyu.top/Article/details/gtrvskuacd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.dianchejie.cn/Article/details/gtswpzjcpi.html

[Q64] 提交事务
来源：http://dali.sweek.top/Article/details/gtdlmaapfz.html

COMMIT;
来源：http://dali.haohaochexian.top/Article/details/gtvlpltufn.html

[Q65] 回滚事务
来源：http://dali.xinyue.icu/Article/details/gtvmvicctm.html

ROLLBACK;
来源：http://dali.cheryme.top/Article/details/gtozcofkvb.html

[Q66] 行锁查询
来源：http://dali.vqdsnc.cn/Article/details/gtsrimqynh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ivvv.top/Article/details/gtbkkaduyz.html

[Q67] 设置隔离级别
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqglmyme.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.vqdsnc.cn/Article/details/gtjuolbzbm.html

[Q68] 保存点
来源：http://dali.smart0.xyz/Article/details/gtklsxeqku.html

SAVEPOINT sp1;
来源：http://dali.ppjwa.cn/Article/details/gtsplbbvxy.html

ROLLBACK TO sp1;
来源：http://dali.gogol.net.cn/Article/details/gtgrbzeals.html

[Q69] 查看执行计划
来源：http://dali.shzxlz.cn/Article/details/gtdnmodcbz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.kuanghao11.cn/Article/details/gtlxgtvmaw.html

[Q70] 更新统计信息
来源：http://dali.jqgufenzy.top/Article/details/gtqiimepjj.html

ANALYZE TABLE users;
来源：http://dali.dashuyun.cn/Article/details/gthbgcqdiy.html

[Q71] 查看建表语句
来源：http://dali.kuanghao11.cn/Article/details/gtxptazswo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yangfankeji.com/Article/details/gtmbnozdfn.html

[Q72] 查看索引
来源：http://dali.nanxinkj.top/Article/details/gtghxtyrps.html

SHOW INDEX FROM users;
来源：http://dali.guannengcc.top/Article/details/gtjovkhpii.html

[Q73] 查看表状态
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkvwrmpz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xylfe.cn/Article/details/gtwyctxcdr.html

[Q74] 强制使用索引
来源：http://dali.xylfe.cn/Article/details/gtfnlccvub.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.dianchejie.cn/Article/details/gtwbasvxfn.html

[Q75] 日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gtwpjrcrkl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtgchhkvjw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gogol.net.cn/Article/details/gtaoxnflqc.html

[Q76] 按天统计
来源：http://dali.yongpay.top/Article/details/gtibscjojn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gzhubu.top/Article/details/gtmhknxltn.html

[Q77] 时间加减
来源：http://dali.tian-w.cn/Article/details/gtjgzklvob.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xuanzx.com/Article/details/gtxyisyrpn.html

[Q78] 当前时间
来源：http://dali.yonumen.top/Article/details/gtzybakhor.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.snrcjt.cn/Article/details/gtqxrzmvhg.html

[Q79] 字符串拼接
来源：http://dali.ppjwa.cn/Article/details/gtxqgvcrxs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aizwys.cn/Article/details/gtakynqypn.html

[Q80] 字符串截取
来源：http://dali.pycfn.com/Article/details/gtuowbujgv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gthgsqztqh.html

[Q81] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gtusjsexhx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtzamztwre.html

[Q82] 字符长度与字节长度
来源：http://dali.daxiang520.top/Article/details/gtpafkicbe.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtvfzjcvlo.html

[Q83] 大小写转换
来源：http://dali.nanxuanxn.top/Article/details/gtwzvothbq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtszsasacd.html

[Q84] 去除首尾空格
来源：http://dali.ivvv.top/Article/details/gtyyxtdqmn.html

SELECT TRIM(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtxhzdlwfh.html

[Q85] 数值取整
来源：http://dali.birdmap.top/Article/details/gtqwbflupd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.meibo888.top/Article/details/gtzgzsziyg.html

[Q86] 读取 JSON 字段
来源：http://dali.cqqwz.cn/Article/details/gtvkysbejw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nwbrower.top/Article/details/gtpkwpzhnt.html

[Q87] JSON 字段做条件
来源：http://dali.ivvv.top/Article/details/gtrkqixdhf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ybcxt.top/Article/details/gtekygjpti.html

[Q88] 行转列（条件聚合）
来源：http://dali.xziqi.cn/Article/details/gtucoqdopp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nwbrower.top/Article/details/gtpqeryetf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuanzx.com/Article/details/gtyfzaplim.html

[Q89] 判断表是否存在
来源：http://dali.dashuyun.cn/Article/details/gtddgtvwtp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxuanxn.top/Article/details/gtqxhhpydw.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangtech.top/Article/details/gtjojzkpgk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gogol.net.cn/Article/details/gtiqgynkjr.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtmpfnegbv.html

R. Bash 专题
来源：http://dali.daria6918.cn/Article/details/gtzvfkemma.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtqwssyvws.html

[R01] shebang 与严格模式
来源：http://dali.meibo888.top/Article/details/gtvxgmoxqa.html

#!/usr/bin/env bash
来源：http://dali.jyoumei.cn/Article/details/gtdvmpjbng.html

set -euo pipefail
来源：http://dali.gaohongyu789.top/Article/details/gtzsjsvwat.html

[R02] 变量赋值与使用
来源：http://dali.dashuyun.cn/Article/details/gtprajyryx.html

name="Tom"; echo "$name"
来源：http://dali.guowangkeji.top/Article/details/gtkhlsfcuy.html

[R03] 只读变量
来源：http://dali.vqdsnc.cn/Article/details/gtvshughxd.html

readonly PI=3.14
来源：http://dali.xuanzx.com/Article/details/gtidrizvmn.html

[R04] 位置参数
来源：http://dali.xziqi.cn/Article/details/gtxtdplrgv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258.top/Article/details/gthwhfocwn.html

[R05] 参数默认值
来源：http://dali.cucudq.cn/Article/details/gthsvuwqlc.html

name="${1:-default}"
来源：http://dali.nanxuanxn.top/Article/details/gtgkvxhdpe.html

[R06] 判断命令是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtkdtciphi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gtvmqlzkzr.html

[R07] if 判断文件
来源：http://dali.nanxinkj.top/Article/details/gttybeutbi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtigiagcuu.html

[R08] 数值比较
来源：http://dali.wangdashe.top/Article/details/gtkqjjqfll.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zdqjudy.top/Article/details/gtvmjmwqln.html

[R09] 字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gtxhaigjwq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtyjxbwmck.html

[R10] 正则匹配
来源：http://dali.wangdashe.top/Article/details/gtyaugxiwi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtrktmwayv.html

[R11] case 多分支
来源：http://dali.yuanzhike.top/Article/details/gtuewkujtj.html

case "$1" in
来源：http://dali.vqdsnc.cn/Article/details/gteaegmglj.html

start) echo "启动" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtpkbelhlm.html

stop)  echo "停止" ;;
来源：http://dali.jianghu66.top/Article/details/gtaiayuebo.html

*)     echo "未知命令" ;;
来源：http://dali.yonumen.top/Article/details/gtglgtvjyz.html

esac
来源：http://dali.yuxming.cn/Article/details/gtdbsxydio.html

[R12] for 遍历文件
来源：http://dali.cdnleiting.top/Article/details/gterzbakba.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yuxming.cn/Article/details/gtnjrxrbqd.html

[R13] for 计数循环
来源：http://dali.nanxuanxn.top/Article/details/gtafqjwsuh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxuanxn.top/Article/details/gtmrmteskj.html

[R14] C 风格 for
来源：http://dali.cheryme.top/Article/details/gtltzwqecx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dashuyun.cn/Article/details/gtcvuqwodw.html

[R15] while 逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtkkprgzdu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.0kj1m.cn/Article/details/gtycjjdhip.html

[R16] until 等待条件
来源：http://dali.tian-w.cn/Article/details/gtfugivpdo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstcehejn.html

[R17] 数组定义与取值
来源：http://dali.yvedp.cn/Article/details/gtkfvwjzad.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenlongwang.top/Article/details/gtneoadqqd.html

[R18] 遍历数组
来源：http://dali.zhongyouzk.top/Article/details/gtcnsreufi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cashguo.top/Article/details/gtvusuwtew.html

[R19] 数组长度
来源：http://dali.cheryme.top/Article/details/gtgkiczwuq.html

echo "${#arr[@]}"
来源：http://dali.yanxiufei.cn/Article/details/gtltlrmwoj.html

[R20] 关联数组（字典）
来源：http://dali.xuanzx.com/Article/details/gtgoizwedg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.svipenyu.cn/Article/details/gtfxcrfqnv.html

[R21] 字符串长度
来源：http://dali.dianchejie.cn/Article/details/gtjqyidqwq.html

echo "${#s}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakuzipbl.html

[R22] 截取子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqeklyomj.html

echo "${s:0:5}"
来源：http://dali.yongpay.top/Article/details/gtrgokdplb.html

[R23] 字符串替换
来源：http://dali.yj20258.top/Article/details/gtvtltkldx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cheryme.top/Article/details/gtihmtsews.html

[R24] 大小写转换
来源：http://dali.iojbl.cn/Article/details/gtvcjhyefr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.smart0.xyz/Article/details/gtqgfntfkk.html

[R25] 去后缀 / 去前缀
来源：http://dali.aibaodan.cn/Article/details/gtvopzhbtc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigufen.top/Article/details/gteimksatw.html

[R26] 命令替换
来源：http://dali.tian-w.cn/Article/details/gtzbqligfl.html

now=$(date +%F); echo "$now"
来源：http://dali.hywenlv.cn/Article/details/gtjwcmgdwu.html

[R27] 算术展开
来源：http://dali.jyoumei.cn/Article/details/gtffdfkwnh.html

echo $((1 + 2 * 3))
来源：http://dali.yuxming.cn/Article/details/gtqzdeidme.html

[R28] 浮点运算
来源：http://dali.zhiwuduotai.top/Article/details/gtcpiythay.html

echo "scale=2; 10/3" | bc
来源：http://dali.quarkkingdee.top/Article/details/gtzhtuppdu.html

[R29] 定义函数
来源：http://dali.jianghu66.top/Article/details/gtywllbgxe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.pengpengdd.cyou/Article/details/gtulcbmvbm.html

[R30] 函数返回状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxbvgzoy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xuetiantiany.cn/Article/details/gtqgcjbkri.html

[R31] 局部变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtatzuwvao.html

f() { local x=1; echo "$x"; }
来源：http://dali.svipenyu.cn/Article/details/gtgwjongej.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhwdgfpj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gtyewhutmp.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmoqmmdid.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.wangdashe.top/Article/details/gtidzyhwvh.html

[R34] 退出时清理
来源：http://dali.hywenlv.cn/Article/details/gtqbmfnpeh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gtdoytchaz.html

[R35] 后台执行并等待
来源：http://dali.cdnleiting.top/Article/details/gtjtnxnhdz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.vqdsnc.cn/Article/details/gteihtylmp.html

[R36] 并发执行多个任务
来源：http://dali.tanke756.top/Article/details/gtlhsauqbd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.meibo888.top/Article/details/gtxgvkcamh.html

[R37] 把输出赋给变量
来源：http://dali.zhongyouzk.top/Article/details/gtkhbbnbzp.html

files=$(ls -1)
来源：http://dali.guowangkeji.top/Article/details/gtzdflcyan.html

[R38] 管道串联
来源：http://dali.fzhhl.top/Article/details/gtpmdqkcri.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gtwsshqcum.html

[R39] 重定向标准输出与错误
来源：http://dali.zhoulong.xyz/Article/details/gtylirqzgk.html

cmd > out.log 2>&1
来源：http://dali.redwolf501.top/Article/details/gtooclzybl.html

[R40] 追加写日志
来源：http://dali.snrcjt.cn/Article/details/gtidabrniv.html

echo "log" >> out.log
来源：http://dali.havefunace.top/Article/details/gtfgmcvgpb.html

[R41] 丢弃输出
来源：http://dali.gzhubu.top/Article/details/gtxuyuxacz.html

cmd >/dev/null 2>&1
来源：http://dali.shuidangran.top/Article/details/gtomhrzhik.html

[R42] 输入重定向
来源：http://dali.316326.xyz/Article/details/gtvjjkreze.html

wc -l < a.txt
来源：http://dali.fengsongda.top/Article/details/gtanxodxsy.html

[R43] 按名字查找文件
来源：http://dali.ehwqpu.com/Article/details/gtxehwnrzx.html

find . -name "*.log" -type f
来源：http://dali.chenlongwang.top/Article/details/gtdprmkyre.html

[R44] 按修改时间查找
来源：http://dali.vqdsnc.cn/Article/details/gtsfibrikq.html

find . -mtime -7 -type f
来源：http://dali.dianchejie.cn/Article/details/gtqurdyxih.html

[R45] 批量删除
来源：http://dali.hysaishi.cn/Article/details/gtvyifzywh.html

find . -name "*.tmp" -delete
来源：http://dali.pengpengdd.cyou/Article/details/gtuvtqjwvv.html

[R46] 递归替换文件内容
来源：http://dali.chenzaomai.com/Article/details/gtddcdskzr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.aibaodan.cn/Article/details/gtyhwypucg.html

[R47] sed 单行替换
来源：http://dali.hnxiangtu.top/Article/details/gtbnzjvwcm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.havefunace.top/Article/details/gtsfnzgucs.html

[R48] awk 取指定列
来源：http://dali.zycfv.cn/Article/details/gtanueymeu.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtoblghzka.html

[R49] awk 带条件
来源：http://dali.aibaodan.cn/Article/details/gttnmfpahn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cheryme.top/Article/details/gtblnyxurs.html

[R50] awk 求和
来源：http://dali.yj20258.top/Article/details/gtifkelyqy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtzczsqnpm.html

[R51] 排序去重取前几
来源：http://dali.chenzaomai.com/Article/details/gtwoqndvmd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.quarkkingdee.top/Article/details/gtkujrpbbo.html

[R52] 统计行数
来源：http://dali.vqdsnc.cn/Article/details/gtfdzdvoxe.html

wc -l a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtswgxeixa.html

[R53] 查看文件头与实时尾
来源：http://dali.mhx1999.top/Article/details/gtagypzvah.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxuanxn.top/Article/details/gtnyzzoyof.html

[R54] 比较两个文件
来源：http://dali.jqgufenzy.top/Article/details/gtmxphyrvb.html

diff a.txt b.txt
来源：http://dali.hnxiangtu.top/Article/details/gtzvztabko.html

[R55] 压缩与解压
来源：http://dali.cucudq.cn/Article/details/gttpxxjrxe.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gzhubu.top/Article/details/gtpkygekbd.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gtufvusmxy.html

scp file user@host:/path/
来源：http://dali.kuanghao11.cn/Article/details/gtkxdtfitl.html

[R57] 远程执行命令
来源：http://dali.jianghu66.top/Article/details/gttittppob.html

ssh user@host 'uptime'
来源：http://dali.yj20258888.top/Article/details/gtnhmrgwyt.html

[R58] 下载文件
来源：http://dali.snrcjt.cn/Article/details/gtfxfnvaxv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.feifeiyinyue.top/Article/details/gtsjkidlbl.html

[R59] 发 POST JSON
来源：http://dali.chenlongwang.top/Article/details/gtasggaebo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cashguo.top/Article/details/gtznynjlqk.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhengqikj.top/Article/details/gtkdkgsbkg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jqgfzy.top/Article/details/gtvzbkxapo.html

[R61] 磁盘占用
来源：http://dali.hnxiangtu.top/Article/details/gtdsthdtjf.html

df -h;  du -sh *
来源：http://dali.gotoacloud.top/Article/details/gtxtaxxuea.html

[R62] 找最占空间的文件
来源：http://dali.guowangkeji.top/Article/details/gtadbshqnw.html

du -ah . | sort -rh | head -10
来源：http://dali.zhiwuduotai.top/Article/details/gtqjbzwyqo.html

[R63] 内存与进程
来源：http://dali.guannengcc.top/Article/details/gtpsqwhtvu.html

free -h;  ps aux | grep nginx
来源：http://dali.gzhubu.top/Article/details/gthiofkfzi.html

[R64] 结束进程
来源：http://dali.guannengcc.top/Article/details/gtpsqzctap.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzzafyfm.html

[R65] 查看端口占用
来源：http://dali.nanxinkj.top/Article/details/gtcnodpsni.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangshuangyany.cn/Article/details/gticihavyy.html

[R66] 定时任务
来源：http://dali.yongpay.top/Article/details/gtlcbggyza.html

crontab -e;  crontab -l
来源：http://dali.dianchejie.cn/Article/details/gtyixmgyzf.html

[R67] 生成随机十六进制串
来源：http://dali.gzhubu.top/Article/details/gtxpxxobzl.html

openssl rand -hex 16
来源：http://dali.yvedp.cn/Article/details/gtcxzxboxl.html

[R68] 计算文件校验值
来源：http://dali.jianghu66.top/Article/details/gtytjnuxcl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.guowangkeji.top/Article/details/gtcuhrylwc.html

[R69] 生成随机密码
来源：http://dali.sweek.top/Article/details/gtsbhedpee.html

head -c 16 /dev/urandom | base64
来源：http://dali.quarkkingdee.top/Article/details/gtpdovbzlu.html

[R70] 时间戳与互转
来源：http://dali.hysaishi.cn/Article/details/gtepddlsck.html

date +%s;  date -d @1700000000
来源：http://dali.yanxiufei.cn/Article/details/gthkrhwgoy.html

[R71] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtnuvpcddn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sxryk.cn/Article/details/gteglteykq.html

[R72] 等待端口就绪
来源：http://dali.dianchejie.cn/Article/details/gtidbmibja.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangshuangyany.cn/Article/details/gtjakoviix.html

[R73] 分割大日志
来源：http://dali.yvedp.cn/Article/details/gtakgliada.html


<!-- 参考信息 -->