代发 wailian999

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gzhubu.top/Article/details/gtthgjzwgm.html

[Q28] 求和与平均
来源：http://dali.c1oappe.top/Article/details/gtnppqnzqv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtkvcmcaec.html

[Q29] 最大最小值
来源：http://dali.316326.xyz/Article/details/gtqbzlesza.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtscxggbdb.html

[Q30] 分组统计
来源：http://dali.yj20258888.top/Article/details/gtysappgga.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtojwgdlzb.html

[Q31] 分组后过滤
来源：http://dali.yj20258888.top/Article/details/gtvcubpxyz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yuanzhike.top/Article/details/gtbnikttlu.html

[Q32] 分组拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtvwtvvcma.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gtgdknezpm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.feifeiyinyue.top/Article/details/gtjpjaozqb.html

[Q33] 多列分组
来源：http://dali.yuxming.cn/Article/details/gtbnzvvwnd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cucudq.cn/Article/details/gtjpeycjys.html

[Q34] 每组取第一条
来源：http://dali.smart0.xyz/Article/details/gtgohbvgpy.html

SELECT * FROM (
来源：http://dali.yongpay.top/Article/details/gtghjklqbk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yongpay.top/Article/details/gtwfbwfjek.html

) t WHERE rn = 1;
来源：http://dali.jiagoushi.top/Article/details/gthpjkratb.html

[Q35] 内连接
来源：http://dali.yueranfly.top/Article/details/gtagrbmcne.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gtisiyxhhs.html

[Q36] 左连接
来源：http://dali.ehwqpu.com/Article/details/gtghihfmxi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuanzx.com/Article/details/gthugdswng.html

[Q37] 右连接
来源：http://dali.shuidangran.top/Article/details/gtxpalyqei.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nwbrower.top/Article/details/gteqkakmfx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.smart0.xyz/Article/details/gtqrpvwqze.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yangfankeji.com/Article/details/gtxarcduma.html

[Q39] 自连接（查上下级）
来源：http://dali.zhiwuduotai.top/Article/details/gtrptrhnvc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzpwzodz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.smart0.xyz/Article/details/gtknbgtqdj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xziqi.cn/Article/details/gtelmiuybp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhoulong.xyz/Article/details/gttsvhjedm.html

[Q41] 多表连接
来源：http://dali.yanxiufei.cn/Article/details/gtjkrinask.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.smart0.xyz/Article/details/gtulfwsqwc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhixingplan.top/Article/details/gthiqhxoco.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.0kj1m.cn/Article/details/gtqnhmootw.html

[Q42] 连接条件附加过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxlbzwuco.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuanzx.com/Article/details/gtoterrhuz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fengsongda.top/Article/details/gtgclnrgzo.html

[Q43] 标量子查询
来源：http://dali.cashguo.top/Article/details/gtckjgvxgw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ehwqpu.com/Article/details/gtqadwtcxi.html

[Q44] IN 子查询
来源：http://dali.mhx1999.top/Article/details/gtfnrsnanf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gotoacloud.top/Article/details/gtiksrppmx.html

[Q45] EXISTS 判断存在
来源：http://dali.birdmap.top/Article/details/gtizamvzuv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gtxziwnimq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.birdmap.top/Article/details/gtmtgardrz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gtscdsozkb.html

[Q47] 与平均值比较
来源：http://dali.sysykeji.top/Article/details/gtrkqfwaly.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgufenzy.top/Article/details/gtprwkicxi.html

[Q48] CTE 公用表表达式
来源：http://dali.tian-w.cn/Article/details/gtbesicvsg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.c1oappe.top/Article/details/gtqgmqyrph.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.iojbl.cn/Article/details/gthahthfgg.html

[Q49] 更新单行
来源：http://dali.jinqigfzy.top/Article/details/gtbrzsrxpx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhongyouzk.top/Article/details/gtlmmptqhi.html

[Q50] 批量更新
来源：http://dali.cdnleiting.top/Article/details/gtineexsxb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqekgcrch.html

[Q51] 用子查询更新
来源：http://dali.zdqjudy.top/Article/details/gtctmkqhhf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtimkujljk.html

[Q52] 删除指定行
来源：http://dali.hnxiangtu.top/Article/details/gtyoiapntg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtvzacnkmp.html

[Q53] 按条件删除
来源：http://dali.wangshuangyany.cn/Article/details/gtepzwajps.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenjidiqi.icu/Article/details/gtsmijspld.html

[Q54] 清空表
来源：http://dali.pycfn.com/Article/details/gtxdjoryfl.html

TRUNCATE TABLE logs;
来源：http://dali.hongshengwenyu.top/Article/details/gtoocnifux.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqcfgknv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sufxvd.cn/Article/details/gtfypjkkwb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.snrcjt.cn/Article/details/gtbnbtijyn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuanzx.com/Article/details/gtqotvyjrd.html

[Q57] 行号
来源：http://dali.snrcjt.cn/Article/details/gtsgnewqhm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtmwaugugi.html

[Q58] 累计求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejdgejro.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtgwcqasbu.html

[Q59] 分组内累计
来源：http://dali.zhongyouzk.top/Article/details/gtrqmxpuee.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtpwsxzscs.html

[Q60] 取上一行 / 下一行
来源：http://dali.snrcjt.cn/Article/details/gtojzvqcmd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jqgufenzy.top/Article/details/gttgyxbbfv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtqprhgpky.html

[Q61] 移动平均
来源：http://dali.nanxinkj.top/Article/details/gtkbnyfuws.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj20258.top/Article/details/gtkyqgpvig.html

[Q62] 分组占比
来源：http://dali.yuanzhike.top/Article/details/gtezjcqcxy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gtqfxiokhc.html

[Q63] 开启事务
来源：http://dali.nanxuanxn.top/Article/details/gtophqalnx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ivvv.top/Article/details/gtzbxfzcpf.html

[Q64] 提交事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpbumavp.html

COMMIT;
来源：http://dali.ehwqpu.com/Article/details/gtagqfeytj.html

[Q65] 回滚事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzkkkxlt.html

ROLLBACK;
来源：http://dali.smart0.xyz/Article/details/gttflaobln.html

[Q66] 行锁查询
来源：http://dali.shuidangran.top/Article/details/gtwqkbttoa.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tanke756.top/Article/details/gtjqdlmvzr.html

[Q67] 设置隔离级别
来源：http://dali.nwbrower.top/Article/details/gtyfzbvcfx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yangfankeji.com/Article/details/gtudrmqrvz.html

[Q68] 保存点
来源：http://dali.zdqjudy.top/Article/details/gtgacyvjqv.html

SAVEPOINT sp1;
来源：http://dali.0kj1m.cn/Article/details/gtefkhxjfg.html

ROLLBACK TO sp1;
来源：http://dali.xinyue.icu/Article/details/gtrwldeful.html

[Q69] 查看执行计划
来源：http://dali.yj20258888.top/Article/details/gthkdabdec.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yonumen.top/Article/details/gtkqyyiezz.html

[Q70] 更新统计信息
来源：http://dali.shuidangran.top/Article/details/gtsmplwsxy.html

ANALYZE TABLE users;
来源：http://dali.zhiwuduotai.top/Article/details/gtodfmtfsy.html

[Q71] 查看建表语句
来源：http://dali.xinyue.icu/Article/details/gtikmnczjp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.guowangkeji.top/Article/details/gtsztiyqbv.html

[Q72] 查看索引
来源：http://dali.daxiang520.top/Article/details/gtouglkkke.html

SHOW INDEX FROM users;
来源：http://dali.cucudq.cn/Article/details/gtkzzxzexs.html

[Q73] 查看表状态
来源：http://dali.cashguo.top/Article/details/gtsuokprpz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenjidiqi.icu/Article/details/gtxxahvdxa.html

[Q74] 强制使用索引
来源：http://dali.wangshuangyany.cn/Article/details/gtlnoduokz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ehwqpu.com/Article/details/gtfhbastfn.html

[Q75] 日期格式化
来源：http://dali.pycfn.com/Article/details/gtbppgqeir.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gttudndsyu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.smart0.xyz/Article/details/gtyudxaumd.html

[Q76] 按天统计
来源：http://dali.yanxiufei.cn/Article/details/gtorbucnob.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sysykeji.top/Article/details/gtlbckcfdx.html

[Q77] 时间加减
来源：http://dali.xziqi.cn/Article/details/gtwezthmka.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.wangdashe.top/Article/details/gtpxezdspu.html

[Q78] 当前时间
来源：http://dali.yvedp.cn/Article/details/gteqspimam.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjlmtwiwz.html

[Q79] 字符串拼接
来源：http://dali.jqgfzy.top/Article/details/gtykwubzsx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hywenlv.cn/Article/details/gtmcazzelk.html

[Q80] 字符串截取
来源：http://dali.chenzaomai.com/Article/details/gtioevluaj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtnnsdnjmt.html

[Q81] 字符串替换
来源：http://dali.yj20258.top/Article/details/gtjwtwbnme.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtvwejkjqa.html

[Q82] 字符长度与字节长度
来源：http://dali.zhengqikj.top/Article/details/gtdmyrzapa.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtozrfeats.html

[Q83] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gtxxiicbfh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtjquhtmam.html

[Q84] 去除首尾空格
来源：http://dali.jlsjyb.cn/Article/details/gtqeenqxoq.html

SELECT TRIM(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtitivecmp.html

[Q85] 数值取整
来源：http://dali.chenjidiqi.icu/Article/details/gticifftyo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xylfe.cn/Article/details/gtzhpdybyv.html

[Q86] 读取 JSON 字段
来源：http://dali.hammf.cn/Article/details/gtswqoevtt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.birdmap.top/Article/details/gtkupyceaa.html

[Q87] JSON 字段做条件
来源：http://dali.xuanzx.com/Article/details/gtjtcfdqdf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.andypj.xyz/Article/details/gtgnxdcyih.html

[Q88] 行转列（条件聚合）
来源：http://dali.xziqi.cn/Article/details/gtprmkdzzb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.9152youxi.cn/Article/details/gtczhayvwe.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daxiang520.top/Article/details/gtwirvlpdo.html

[Q89] 判断表是否存在
来源：http://dali.daxiang520.top/Article/details/gtozvgywne.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gaohongyu789.top/Article/details/gtefixuvfk.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorxerqus.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jlsjyb.cn/Article/details/gtxwiwwoyh.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtxnovguzf.html

R. Bash 专题
来源：http://dali.xuetiantiany.cn/Article/details/gtefuuhvic.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtycmuoztg.html

[R01] shebang 与严格模式
来源：http://dali.zdqjudy.top/Article/details/gtfmcbvmhp.html

#!/usr/bin/env bash
来源：http://dali.jinqigufen.top/Article/details/gttblenirl.html

set -euo pipefail
来源：http://dali.vqdsnc.cn/Article/details/gteerpnfab.html

[R02] 变量赋值与使用
来源：http://dali.c1oappe.top/Article/details/gtkagxqccy.html

name="Tom"; echo "$name"
来源：http://dali.ppjwa.cn/Article/details/gtewzgjcko.html

[R03] 只读变量
来源：http://dali.yuanzhike.top/Article/details/gtaldjswps.html

readonly PI=3.14
来源：http://dali.dashuyun.cn/Article/details/gtzsvfylbe.html

[R04] 位置参数
来源：http://dali.hfpthk.cn/Article/details/gtijscgkoi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yongpay.top/Article/details/gtrcuktnuw.html

[R05] 参数默认值
来源：http://dali.gaohongyu789.top/Article/details/gtetcaguah.html

name="${1:-default}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzuabxhc.html

[R06] 判断命令是否存在
来源：http://dali.vqdsnc.cn/Article/details/gtelgsjjki.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yanxiufei.cn/Article/details/gtsrcslukq.html

[R07] if 判断文件
来源：http://dali.sxryk.cn/Article/details/gtrwapkfla.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.dashuyun.cn/Article/details/gtwykuosnz.html

[R08] 数值比较
来源：http://dali.zhixingplan.top/Article/details/gtnguhwdml.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsnfarvks.html

[R09] 字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gthblhxnns.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.andypj.xyz/Article/details/gtscolnqcc.html

[R10] 正则匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtdahjhjnv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cheryme.top/Article/details/gtsazjnpwx.html

[R11] case 多分支
来源：http://dali.pengpengdd.cyou/Article/details/gtkwcczfow.html

case "$1" in
来源：http://dali.xylfe.cn/Article/details/gtnlleweae.html

start) echo "启动" ;;
来源：http://dali.tanke756.top/Article/details/gthesxbedz.html

stop)  echo "停止" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gtqljodyzm.html

*)     echo "未知命令" ;;
来源：http://dali.gotoacloud.top/Article/details/gtlftczoji.html

esac
来源：http://dali.zhongyouzk.top/Article/details/gtpphvweqd.html

[R12] for 遍历文件
来源：http://dali.xuetiantiany.cn/Article/details/gtabigezjr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sufxvd.cn/Article/details/gtzgbmxtad.html

[R13] for 计数循环
来源：http://dali.pycfn.com/Article/details/gtpuvvjovb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrimflngm.html

[R14] C 风格 for
来源：http://dali.hongshengwenyu.top/Article/details/gtgykwtejl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgpqjjpz.html

[R15] while 逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtmshzubgy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nwbrower.top/Article/details/gtrqwwkeky.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gtcpduwpmh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gtopzjncsg.html

[R17] 数组定义与取值
来源：http://dali.yuanzhike.top/Article/details/gtrgscrmkq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cheryme.top/Article/details/gtfzspcnzk.html

[R18] 遍历数组
来源：http://dali.redwolf501.top/Article/details/gthkahzeip.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ivvv.top/Article/details/gtseboffvq.html

[R19] 数组长度
来源：http://dali.yuxming.cn/Article/details/gtqouqxbwt.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtagkvxoxz.html

[R20] 关联数组（字典）
来源：http://dali.zhiwuduotai.top/Article/details/gttjzqglhi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yonumen.top/Article/details/gtluwmgboq.html

[R21] 字符串长度
来源：http://dali.redwolf501.top/Article/details/gtjyspjhzl.html

echo "${#s}"
来源：http://dali.hysaishi.cn/Article/details/gtngokwegv.html

[R22] 截取子串
来源：http://dali.jianghu66.top/Article/details/gtohyzdziv.html

echo "${s:0:5}"
来源：http://dali.zycfv.cn/Article/details/gtbgifrlnq.html

[R23] 字符串替换
来源：http://dali.iojbl.cn/Article/details/gtskzvdkme.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hammf.cn/Article/details/gtrsoaoojt.html

[R24] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gtuhfpsfzv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuxming.cn/Article/details/gtrvgrpwtg.html

[R25] 去后缀 / 去前缀
来源：http://dali.dianchejie.cn/Article/details/gtacdqhskl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yueranfly.top/Article/details/gtblklpwjz.html

[R26] 命令替换
来源：http://dali.shzxlz.cn/Article/details/gtuazfcdsr.html

now=$(date +%F); echo "$now"
来源：http://dali.9152youxi.cn/Article/details/gtxkkyilrw.html

[R27] 算术展开
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimbqfjmu.html

echo $((1 + 2 * 3))
来源：http://dali.sysykeji.top/Article/details/gtbmeczipg.html

[R28] 浮点运算
来源：http://dali.svipenyu.cn/Article/details/gtorzrrskh.html

echo "scale=2; 10/3" | bc
来源：http://dali.xylfe.cn/Article/details/gtzqjtvere.html

[R29] 定义函数
来源：http://dali.havefunace.top/Article/details/gtgmlvrgnx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gthaauzkzp.html

[R30] 函数返回状态码
来源：http://dali.hysaishi.cn/Article/details/gtsziftpyj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhiwuduotai.top/Article/details/gtuiafhton.html

[R31] 局部变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubxoltzd.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuowkfsld.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcisnwugs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gtjbpbktyf.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangtech.top/Article/details/gtewsamdgl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ywan-chungtsiang.top/Article/details/gtanbqfaqu.html

[R34] 退出时清理
来源：http://dali.kuanghao11.cn/Article/details/gtslcemwid.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gtiqqyssiw.html

[R35] 后台执行并等待
来源：http://dali.snrcjt.cn/Article/details/gtgfzhkabs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shzxlz.cn/Article/details/gtephlpzbb.html

[R36] 并发执行多个任务
来源：http://dali.yj20258.top/Article/details/gthlywwqpy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.smart0.xyz/Article/details/gtkglyzgpn.html

[R37] 把输出赋给变量
来源：http://dali.pycfn.com/Article/details/gtpmtrgvid.html

files=$(ls -1)
来源：http://dali.xziqi.cn/Article/details/gtzdqefpzf.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gtwcqxlcby.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gotoacloud.top/Article/details/gtpzscxkyd.html

[R39] 重定向标准输出与错误
来源：http://dali.tianlin.xyz/Article/details/gttjjakdbc.html

cmd > out.log 2>&1
来源：http://dali.jlsjyb.cn/Article/details/gtrkwuvgat.html

[R40] 追加写日志
来源：http://dali.fzhhl.top/Article/details/gtlesjdxpx.html

echo "log" >> out.log
来源：http://dali.smart0.xyz/Article/details/gtmlqqadyv.html

[R41] 丢弃输出
来源：http://dali.fengsongda.top/Article/details/gtpyuikfzi.html

cmd >/dev/null 2>&1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlemhbjlz.html

[R42] 输入重定向
来源：http://dali.aibaodan.cn/Article/details/gtkepqorhf.html

wc -l < a.txt
来源：http://dali.zhixingplan.top/Article/details/gtgsrfdnjr.html

[R43] 按名字查找文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmetyqjbt.html

find . -name "*.log" -type f
来源：http://dali.pengpengdd.cyou/Article/details/gtgwojfpvx.html

[R44] 按修改时间查找
来源：http://dali.hnqzz.top/Article/details/gtfxckdutd.html

find . -mtime -7 -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxdvteio.html

[R45] 批量删除
来源：http://dali.andypj.xyz/Article/details/gtsqwsnzqu.html

find . -name "*.tmp" -delete
来源：http://dali.zdqjudy.top/Article/details/gtniazlaab.html

[R46] 递归替换文件内容
来源：http://dali.xinyue.icu/Article/details/gtskazugfb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yvedp.cn/Article/details/gtyjxzfclm.html

[R47] sed 单行替换
来源：http://dali.hammf.cn/Article/details/gtgidqpnni.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cdnleiting.top/Article/details/gtpbrjwwoi.html

[R48] awk 取指定列
来源：http://dali.wangdashe.top/Article/details/gtsbcydpho.html

awk '{print $1, $3}' a.txt
来源：http://dali.hywenlv.cn/Article/details/gtazmfyepe.html

[R49] awk 带条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdplhunci.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hnxiangtu.top/Article/details/gtadbwhehm.html

[R50] awk 求和
来源：http://dali.hfpthk.cn/Article/details/gtuairyfyk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jyoumei.cn/Article/details/gtrjymqmiy.html

[R51] 排序去重取前几
来源：http://dali.shzxlz.cn/Article/details/gtqknbjlku.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nwbrower.top/Article/details/gtjozzafji.html

[R52] 统计行数
来源：http://dali.shuidangran.top/Article/details/gtgwztbfpd.html

wc -l a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtyhoadegw.html

[R53] 查看文件头与实时尾
来源：http://dali.hysaishi.cn/Article/details/gtyygpwyji.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuanzhike.top/Article/details/gtgjhecosd.html

[R54] 比较两个文件
来源：http://dali.fengsongda.top/Article/details/gtxwszqsjf.html

diff a.txt b.txt
来源：http://dali.jiagoushi.top/Article/details/gtskwqkunm.html

[R55] 压缩与解压
来源：http://dali.tianlin.xyz/Article/details/gtwpkvrosj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxinkj.top/Article/details/gtnoaqbddk.html

[R56] 远程拷贝
来源：http://dali.sweek.top/Article/details/gteqhndbfy.html

scp file user@host:/path/
来源：http://dali.nanxinkj.top/Article/details/gtagctyvvg.html

[R57] 远程执行命令
来源：http://dali.shzxlz.cn/Article/details/gtzhvosgkq.html

ssh user@host 'uptime'
来源：http://dali.0kj1m.cn/Article/details/gtactzkrtc.html

[R58] 下载文件
来源：http://dali.nwbrower.top/Article/details/gtmdlxgxwe.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gtunwrqnmr.html

[R59] 发 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gtobyxybcu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jqgfzy.top/Article/details/gtcutrdrrv.html

[R60] 只看 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gtausgwenq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.fengsongda.top/Article/details/gtivcdogym.html

[R61] 磁盘占用
来源：http://dali.pengpengdd.cyou/Article/details/gtpvdfrlup.html

df -h;  du -sh *
来源：http://dali.guannengcc.top/Article/details/gtobezvbtn.html

[R62] 找最占空间的文件
来源：http://dali.yongpay.top/Article/details/gtatiifvyc.html

du -ah . | sort -rh | head -10
来源：http://dali.snrcjt.cn/Article/details/gtcbrdqxrp.html

[R63] 内存与进程
来源：http://dali.bjfxy.top/Article/details/gtdrxmojvz.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258888.top/Article/details/gtvqmbohvy.html

[R64] 结束进程
来源：http://dali.xuanzx.com/Article/details/gtjbuhcbwz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhoulong.xyz/Article/details/gtvxetamsp.html

[R65] 查看端口占用
来源：http://dali.daxiang520.top/Article/details/gtvcqqxbvg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgmbwkrt.html

[R66] 定时任务
来源：http://dali.316326.xyz/Article/details/gtbepkevhs.html

crontab -e;  crontab -l
来源：http://dali.cheryme.top/Article/details/gtmkbimoyi.html

[R67] 生成随机十六进制串
来源：http://dali.wangshuangyany.cn/Article/details/gtsywtnrnv.html

openssl rand -hex 16
来源：http://dali.tian-w.cn/Article/details/gtxcacqiuy.html

[R68] 计算文件校验值
来源：http://dali.wangdashe.top/Article/details/gtwmhaotup.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.haohaochexian.top/Article/details/gttwwgxxdi.html

[R69] 生成随机密码
来源：http://dali.chenlongwang.top/Article/details/gtfupfznvp.html

head -c 16 /dev/urandom | base64
来源：http://dali.pengpengdd.cyou/Article/details/gtozkehnaz.html

[R70] 时间戳与互转
来源：http://dali.kuanghao11.cn/Article/details/gtvvraytkj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gtzuafepdj.html

[R71] 日期格式化
来源：http://dali.pycfn.com/Article/details/gtlsjwkyul.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.mhx1999.top/Article/details/gtlynfbppk.html

[R72] 等待端口就绪
来源：http://dali.jianghu66.top/Article/details/gtfnexijuo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gtljjrocxw.html

[R73] 分割大日志
来源：http://dali.yanxiufei.cn/Article/details/gtkcbajkze.html

split -l 1000 big.log part_
来源：http://dali.chenlongwang.top/Article/details/gtfzwdamuc.html

[R74] 批量重命名
来源：http://dali.ywan-chungtsiang.top/Article/details/gthnyqonbj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.c1oappe.top/Article/details/gtehmwtvol.html

[R75] 导出环境变量
来源：http://dali.cdnleiting.top/Article/details/gtmflhfpus.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xuanzx.com/Article/details/gtppkognul.html

[R76] 使用临时文件
来源：http://dali.shuidangran.top/Article/details/gtoyphuryg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ybcxt.top/Article/details/gtqmynjies.html

[R77] 读取用户输入
来源：http://dali.xinyue.icu/Article/details/gtnnkvoqtu.html


<!-- 参考信息 -->