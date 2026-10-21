代发 wailian999

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tian-w.cn/Article/details/gtdnjzeuai.html

[Q26] 计数
来源：http://dali.kuanghao11.cn/Article/details/gtofungeuj.html

SELECT COUNT(*) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtvphuwann.html

[Q27] 条件计数
来源：http://dali.svipenyu.cn/Article/details/gtrhmmcvif.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtanlucemn.html

[Q28] 求和与平均
来源：http://dali.xuetiantiany.cn/Article/details/gtnixddilm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtyjkyvrma.html

[Q29] 最大最小值
来源：http://dali.gzhubu.top/Article/details/gtfygorwst.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtnpsqhqnh.html

[Q30] 分组统计
来源：http://dali.aibaodan.cn/Article/details/gtvmttgifm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gtjsmxivlg.html

[Q31] 分组后过滤
来源：http://dali.quarkkingdee.top/Article/details/gthntcxorq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.dashuyun.cn/Article/details/gtugtcupzb.html

[Q32] 分组拼接字符串
来源：http://dali.nwbrower.top/Article/details/gtzwwofkhp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gtcqykdmri.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.svipenyu.cn/Article/details/gtdgewsiih.html

[Q33] 多列分组
来源：http://dali.hnxiangtu.top/Article/details/gtwlpskvby.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.c1oappe.top/Article/details/gtltbahiat.html

[Q34] 每组取第一条
来源：http://dali.zhengqikj.top/Article/details/gtnirokpzt.html

SELECT * FROM (
来源：http://dali.yonumen.top/Article/details/gtyqobuzap.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yuanzhike.top/Article/details/gtfwpgexie.html

) t WHERE rn = 1;
来源：http://dali.sysykeji.top/Article/details/gthgumuyyx.html

[Q35] 内连接
来源：http://dali.jqgufenzy.top/Article/details/gtizeymzbd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gtafhwbshe.html

[Q36] 左连接
来源：http://dali.hammf.cn/Article/details/gthirhqkoj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.guannengcc.top/Article/details/gtvrzjbfot.html

[Q37] 右连接
来源：http://dali.ppjwa.cn/Article/details/gtycorjgfc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sysykeji.top/Article/details/gtefkvlwwd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.smart0.xyz/Article/details/gtynabqpcr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.vqdsnc.cn/Article/details/gtzjnbgppo.html

[Q39] 自连接（查上下级）
来源：http://dali.yanxiufei.cn/Article/details/gtzhoyakhv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangshuangyany.cn/Article/details/gtdfpmzjtt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zycfv.cn/Article/details/gtvdlwsqtg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ydzc1.top/Article/details/gtrbtxfcbl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhixingplan.top/Article/details/gtutvpbmvx.html

[Q41] 多表连接
来源：http://dali.gogol.net.cn/Article/details/gtrftqflsl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jqgufenzy.top/Article/details/gtmiefnvtl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhiwuduotai.top/Article/details/gtohdumziz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yueranfly.top/Article/details/gtrudkgmgx.html

[Q42] 连接条件附加过滤
来源：http://dali.sysykeji.top/Article/details/gttedopvba.html

SELECT u.name, o.amount FROM users u
来源：http://dali.fengsongda.top/Article/details/gtlstybjox.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sufxvd.cn/Article/details/gtegwxsmay.html

[Q43] 标量子查询
来源：http://dali.gogol.net.cn/Article/details/gtehcenljh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hysaishi.cn/Article/details/gtxxzwhhnz.html

[Q44] IN 子查询
来源：http://dali.feifeiyinyue.top/Article/details/gtvvquvgph.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.316326.xyz/Article/details/gttyycrxfa.html

[Q45] EXISTS 判断存在
来源：http://dali.zhongyouzk.top/Article/details/gtqjtaftfx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gteohasguz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gogol.net.cn/Article/details/gtosgvoqsj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gtyhlxorww.html

[Q47] 与平均值比较
来源：http://dali.hongshengwenyu.top/Article/details/gtfvqrrizg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.kuanghao11.cn/Article/details/gtxygbrjfv.html

[Q48] CTE 公用表表达式
来源：http://dali.quarkkingdee.top/Article/details/gtkzwfjwbe.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sweek.top/Article/details/gtlsbizqiv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cucudq.cn/Article/details/gtkeuidxzx.html

[Q49] 更新单行
来源：http://dali.yueranfly.top/Article/details/gtnltrgwpq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.pycfn.com/Article/details/gturbddibl.html

[Q50] 批量更新
来源：http://dali.316326.xyz/Article/details/gtwehflvyu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cheryme.top/Article/details/gtjkpujxpe.html

[Q51] 用子查询更新
来源：http://dali.guowangkeji.top/Article/details/gtnyuowuwt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cucudq.cn/Article/details/gtprrrztah.html

[Q52] 删除指定行
来源：http://dali.zdqjudy.top/Article/details/gtmnciokwx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gtmsgycqby.html

[Q53] 按条件删除
来源：http://dali.ybcxt.top/Article/details/gtywaqdwqp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gtanovfskp.html

[Q54] 清空表
来源：http://dali.hongshengwenyu.top/Article/details/gtlxlhzacl.html

TRUNCATE TABLE logs;
来源：http://dali.wangshuangyany.cn/Article/details/gtfkrackdd.html

[Q55] 排名（并列占位）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxberucvx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nwbrower.top/Article/details/gtubtwutfc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.redwolf501.top/Article/details/gtyqhxjmam.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cheryme.top/Article/details/gtzygbekpt.html

[Q57] 行号
来源：http://dali.shzxlz.cn/Article/details/gtmvjdiuec.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hfpthk.cn/Article/details/gteapvayba.html

[Q58] 累计求和
来源：http://dali.wangdashe.top/Article/details/gtzvwfarqc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtvkbztazt.html

[Q59] 分组内累计
来源：http://dali.hnqzz.top/Article/details/gtdpfudlbl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtrgdgnxtp.html

[Q60] 取上一行 / 下一行
来源：http://dali.shangyingyoupin.top/Article/details/gtlzyhnaum.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenzaomai.com/Article/details/gtujpgnppj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtnjfhjkix.html

[Q61] 移动平均
来源：http://dali.chenzaomai.com/Article/details/gtfigheypp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtqarkowfn.html

[Q62] 分组占比
来源：http://dali.hysaishi.cn/Article/details/gtcjljoizc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gtbvvgzdje.html

[Q63] 开启事务
来源：http://dali.redwolf501.top/Article/details/gtbopvfliu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jyoumei.cn/Article/details/gtimukeqtu.html

[Q64] 提交事务
来源：http://dali.pycfn.com/Article/details/gtdrvewqdw.html

COMMIT;
来源：http://dali.redwolf501.top/Article/details/gtrsljhaau.html

[Q65] 回滚事务
来源：http://dali.guowangkeji.top/Article/details/gthhzsjuam.html

ROLLBACK;
来源：http://dali.vqdsnc.cn/Article/details/gtoprxiqtx.html

[Q66] 行锁查询
来源：http://dali.sufxvd.cn/Article/details/gtzvphejuq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zdqjudy.top/Article/details/gtrwgtbglm.html

[Q67] 设置隔离级别
来源：http://dali.xylfe.cn/Article/details/gtcqdwjmaz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.guannengcc.top/Article/details/gtwfusmazh.html

[Q68] 保存点
来源：http://dali.cucudq.cn/Article/details/gtshvuvawk.html

SAVEPOINT sp1;
来源：http://dali.xuanzx.com/Article/details/gtfqmfkxih.html

ROLLBACK TO sp1;
来源：http://dali.xuetiantiany.cn/Article/details/gtjoagmnsd.html

[Q69] 查看执行计划
来源：http://dali.hammf.cn/Article/details/gtwfjrjhhy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.wangdashe.top/Article/details/gtwtdomznf.html

[Q70] 更新统计信息
来源：http://dali.iojbl.cn/Article/details/gtmbmgyjcp.html

ANALYZE TABLE users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfnhvrju.html

[Q71] 查看建表语句
来源：http://dali.feifeiyinyue.top/Article/details/gtpiolryhb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hnxiangtu.top/Article/details/gtjfzgloka.html

[Q72] 查看索引
来源：http://dali.zhengqikj.top/Article/details/gtvgsqobqi.html

SHOW INDEX FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtzmyxixwq.html

[Q73] 查看表状态
来源：http://dali.zhiwuduotai.top/Article/details/gtcqeehwbg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenlongwang.top/Article/details/gtmqgtwtih.html

[Q74] 强制使用索引
来源：http://dali.chenzaomai.com/Article/details/gtwfqzldze.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.dashuyun.cn/Article/details/gttjpbocyd.html

[Q75] 日期格式化
来源：http://dali.aibaodan.cn/Article/details/gtpdwscijd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gttslmgkwo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xylfe.cn/Article/details/gtkhimjntj.html

[Q76] 按天统计
来源：http://dali.sysykeji.top/Article/details/gtkvdbjskv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sufxvd.cn/Article/details/gthebfogeg.html

[Q77] 时间加减
来源：http://dali.gotoacloud.top/Article/details/gtdfuomlan.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.9152youxi.cn/Article/details/gtwpdxvrqw.html

[Q78] 当前时间
来源：http://dali.jyoumei.cn/Article/details/gthyrtiwjw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuetiantiany.cn/Article/details/gtfhgjodlo.html

[Q79] 字符串拼接
来源：http://dali.chenlongwang.top/Article/details/gtudmrjees.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xylfe.cn/Article/details/gtwieaibrp.html

[Q80] 字符串截取
来源：http://dali.redwolf501.top/Article/details/gtkkvzpqlj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtndzzblpt.html

[Q81] 字符串替换
来源：http://dali.gogol.net.cn/Article/details/gtsoyqxhwp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtbragmqrq.html

[Q82] 字符长度与字节长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyssnmakh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtmouslxks.html

[Q83] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gtppiaznme.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtdyuhsubq.html

[Q84] 去除首尾空格
来源：http://dali.xziqi.cn/Article/details/gtganzeypd.html

SELECT TRIM(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtxbiuogkk.html

[Q85] 数值取整
来源：http://dali.tian-w.cn/Article/details/gtbuoufibj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shuidangran.top/Article/details/gtoppivyek.html

[Q86] 读取 JSON 字段
来源：http://dali.zhixingplan.top/Article/details/gtnoyjlfev.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhongyouzk.top/Article/details/gtprskjijl.html

[Q87] JSON 字段做条件
来源：http://dali.vqdsnc.cn/Article/details/gtkagdgclt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.feifeiyinyue.top/Article/details/gthrijzhzj.html

[Q88] 行转列（条件聚合）
来源：http://dali.daria6918.cn/Article/details/gtakcwdtqw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yuxming.cn/Article/details/gtmqextbgu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daxiang520.top/Article/details/gtvykepzyy.html

[Q89] 判断表是否存在
来源：http://dali.iojbl.cn/Article/details/gttcdzztre.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cucudq.cn/Article/details/gtypjdlsmk.html

[Q90] 生成序号列
来源：http://dali.hfpthk.cn/Article/details/gttpkbvyry.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.316326.xyz/Article/details/gtmbnfrsuo.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtwajcdlxh.html

R. Bash 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkfjfvylc.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtkgasgixp.html

[R01] shebang 与严格模式
来源：http://dali.hammf.cn/Article/details/gtolsewqxz.html

#!/usr/bin/env bash
来源：http://dali.yvedp.cn/Article/details/gtolzupdgu.html

set -euo pipefail
来源：http://dali.yj20258888.top/Article/details/gthtfllwwe.html

[R02] 变量赋值与使用
来源：http://dali.tanke756.top/Article/details/gtpcipylsv.html

name="Tom"; echo "$name"
来源：http://dali.316326.xyz/Article/details/gtpijlqiwj.html

[R03] 只读变量
来源：http://dali.dashuyun.cn/Article/details/gtsjnvebhz.html

readonly PI=3.14
来源：http://dali.hywenlv.cn/Article/details/gtgwnyomxg.html

[R04] 位置参数
来源：http://dali.hysaishi.cn/Article/details/gtlncfrlsm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pycfn.com/Article/details/gtglzqyrwq.html

[R05] 参数默认值
来源：http://dali.fzhhl.top/Article/details/gtnrzewdru.html

name="${1:-default}"
来源：http://dali.gogol.net.cn/Article/details/gtbdfnyqzu.html

[R06] 判断命令是否存在
来源：http://dali.gotoacloud.top/Article/details/gthakbnxmt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gthihcvyph.html

[R07] if 判断文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiacezerh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.wangdashe.top/Article/details/gthhjohxme.html

[R08] 数值比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtueugjjqz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.aizwys.cn/Article/details/gtaegyllsy.html

[R09] 字符串比较
来源：http://dali.meibo888.top/Article/details/gtlliicetz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258.top/Article/details/gtlvkyaqan.html

[R10] 正则匹配
来源：http://dali.cdnleiting.top/Article/details/gtsrdernla.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cheryme.top/Article/details/gtjlsiyarz.html

[R11] case 多分支
来源：http://dali.guowangkeji.top/Article/details/gtqklmizxy.html

case "$1" in
来源：http://dali.ydzc1.top/Article/details/gtxcrbngpj.html

start) echo "启动" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gthfqjugwo.html

stop)  echo "停止" ;;
来源：http://dali.316326.xyz/Article/details/gtgptvgskg.html

*)     echo "未知命令" ;;
来源：http://dali.cheryme.top/Article/details/gtcwijtfog.html

esac
来源：http://dali.shangyingyoupin.top/Article/details/gtvgahoezr.html

[R12] for 遍历文件
来源：http://dali.nanxuanxn.top/Article/details/gturawzycc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtqmpsjtbe.html

[R13] for 计数循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupwyyiia.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gtooxrgzta.html

[R14] C 风格 for
来源：http://dali.quarkkingdee.top/Article/details/gtavjbkoxy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtmtsheeqb.html

[R15] while 逐行读文件
来源：http://dali.havefunace.top/Article/details/gtmeruxxlj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jqgfzy.top/Article/details/gtwowhsybf.html

[R16] until 等待条件
来源：http://dali.birdmap.top/Article/details/gtpfykgfnq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gtngyasnqx.html

[R17] 数组定义与取值
来源：http://dali.haohaochexian.top/Article/details/gtecdqenie.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhoulong.xyz/Article/details/gtftirvvbb.html

[R18] 遍历数组
来源：http://dali.tanke756.top/Article/details/gtshpcfemd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtdgpdphpe.html

[R19] 数组长度
来源：http://dali.sweek.top/Article/details/gtxkpfyxzq.html

echo "${#arr[@]}"
来源：http://dali.hongshengwenyu.top/Article/details/gtbiwivjdy.html

[R20] 关联数组（字典）
来源：http://dali.zhengqikj.top/Article/details/gtgqhlwuat.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuanzhike.top/Article/details/gtohohabpq.html

[R21] 字符串长度
来源：http://dali.tian-w.cn/Article/details/gtlpqtgobc.html

echo "${#s}"
来源：http://dali.svipenyu.cn/Article/details/gthwvuwtoq.html

[R22] 截取子串
来源：http://dali.shzxlz.cn/Article/details/gtmyqwaysh.html

echo "${s:0:5}"
来源：http://dali.fzhhl.top/Article/details/gtnqolvhcl.html

[R23] 字符串替换
来源：http://dali.sweek.top/Article/details/gtqbfgwqnr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shzxlz.cn/Article/details/gttmxlspjg.html

[R24] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gtzroucfxi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ivvv.top/Article/details/gtwvwxgbkd.html

[R25] 去后缀 / 去前缀
来源：http://dali.nwbrower.top/Article/details/gtyvcppwod.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.dashuyun.cn/Article/details/gtwlnovjmu.html

[R26] 命令替换
来源：http://dali.hammf.cn/Article/details/gtncqcxbhb.html

now=$(date +%F); echo "$now"
来源：http://dali.yangfankeji.com/Article/details/gtbuxpylqo.html

[R27] 算术展开
来源：http://dali.zhengqikj.top/Article/details/gtkasvukby.html

echo $((1 + 2 * 3))
来源：http://dali.zhiwuduotai.top/Article/details/gtdjchtese.html

[R28] 浮点运算
来源：http://dali.pengpengdd.cyou/Article/details/gtzvjcdhhk.html

echo "scale=2; 10/3" | bc
来源：http://dali.svipenyu.cn/Article/details/gtxvprcrfm.html

[R29] 定义函数
来源：http://dali.cheryme.top/Article/details/gtlafhawia.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shuidangran.top/Article/details/gtdffrstos.html

[R30] 函数返回状态码
来源：http://dali.guowangkeji.top/Article/details/gtgydwfean.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.smart0.xyz/Article/details/gtdifxgjmz.html

[R31] 局部变量
来源：http://dali.shuidangran.top/Article/details/gtahhzatrv.html

f() { local x=1; echo "$x"; }
来源：http://dali.tian-w.cn/Article/details/gtyurvsati.html

[R32] 参数个数校验
来源：http://dali.c1oappe.top/Article/details/gtpvoklzhr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gtncwxrjfi.html

[R33] 捕获错误并提示行号
来源：http://dali.fengsongda.top/Article/details/gthbvnelfe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zdqjudy.top/Article/details/gtycvixgjw.html

[R34] 退出时清理
来源：http://dali.cashguo.top/Article/details/gtisyfxznp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zdqjudy.top/Article/details/gtaelwgmno.html

[R35] 后台执行并等待
来源：http://dali.aibaodan.cn/Article/details/gthzkvvquv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.havefunace.top/Article/details/gtsfjgjbld.html

[R36] 并发执行多个任务
来源：http://dali.nanxinkj.top/Article/details/gtzbjucswc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yongpay.top/Article/details/gtrowdvzwe.html

[R37] 把输出赋给变量
来源：http://dali.sufxvd.cn/Article/details/gtlkazutid.html

files=$(ls -1)
来源：http://dali.iojbl.cn/Article/details/gtvoktzuqz.html

[R38] 管道串联
来源：http://dali.yj20258.top/Article/details/gtrionsoza.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhongyouzk.top/Article/details/gtmtibhwiv.html

[R39] 重定向标准输出与错误
来源：http://dali.cucudq.cn/Article/details/gtysvluvnv.html

cmd > out.log 2>&1
来源：http://dali.fengsongda.top/Article/details/gtvjwknyrs.html

[R40] 追加写日志
来源：http://dali.zycfv.cn/Article/details/gthijdcgvk.html

echo "log" >> out.log
来源：http://dali.yueranfly.top/Article/details/gtdouickwn.html

[R41] 丢弃输出
来源：http://dali.gaohongyu789.top/Article/details/gtlxwkyhhr.html

cmd >/dev/null 2>&1
来源：http://dali.snrcjt.cn/Article/details/gtbcoumjwh.html

[R42] 输入重定向
来源：http://dali.0kj1m.cn/Article/details/gtqkyiewwo.html

wc -l < a.txt
来源：http://dali.nwbrower.top/Article/details/gtwqeugqen.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gtuxeeuchx.html

find . -name "*.log" -type f
来源：http://dali.zhiwuduotai.top/Article/details/gthmhpdvyk.html

[R44] 按修改时间查找
来源：http://dali.zhoulong.xyz/Article/details/gthbekqkvy.html

find . -mtime -7 -type f
来源：http://dali.aibaodan.cn/Article/details/gtekhmfoyj.html

[R45] 批量删除
来源：http://dali.wangdashe.top/Article/details/gttmaifsar.html

find . -name "*.tmp" -delete
来源：http://dali.yuxming.cn/Article/details/gtpqdttbya.html

[R46] 递归替换文件内容
来源：http://dali.jiagoushi.top/Article/details/gtfcibgjwp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shzxlz.cn/Article/details/gtsdzekhrj.html

[R47] sed 单行替换
来源：http://dali.hnqzz.top/Article/details/gtcnbulwrm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtwtffcjrs.html

[R48] awk 取指定列
来源：http://dali.hongshengwenyu.top/Article/details/gtjmsrltuc.html

awk '{print $1, $3}' a.txt
来源：http://dali.daria6918.cn/Article/details/gtceoqrclk.html

[R49] awk 带条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxliyngi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenzaomai.com/Article/details/gtazckuiyr.html

[R50] awk 求和
来源：http://dali.ivvv.top/Article/details/gtbywjuzbq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtlkmefbow.html

[R51] 排序去重取前几
来源：http://dali.hysaishi.cn/Article/details/gtrkcpeiwh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.haohaochexian.top/Article/details/gtfqbwylxc.html

[R52] 统计行数
来源：http://dali.yuxming.cn/Article/details/gtqpvvxsva.html

wc -l a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtakrunbxo.html

[R53] 查看文件头与实时尾
来源：http://dali.wangshuangyany.cn/Article/details/gtvniqlexf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jlsjyb.cn/Article/details/gtlatlqyfd.html

[R54] 比较两个文件
来源：http://dali.quarkkingdee.top/Article/details/gtgiwamnwh.html

diff a.txt b.txt
来源：http://dali.gzhubu.top/Article/details/gtmftrcefs.html

[R55] 压缩与解压
来源：http://dali.316326.xyz/Article/details/gtbzvxqdoy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.316326.xyz/Article/details/gtuyqtdcho.html

[R56] 远程拷贝
来源：http://dali.shuidangran.top/Article/details/gtzqtosssh.html

scp file user@host:/path/
来源：http://dali.meibo888.top/Article/details/gtsnyeatgr.html

[R57] 远程执行命令
来源：http://dali.fzhhl.top/Article/details/gtghqsgqhz.html

ssh user@host 'uptime'
来源：http://dali.xylfe.cn/Article/details/gtlodbhxvs.html

[R58] 下载文件
来源：http://dali.aizwys.cn/Article/details/gtnqhiacvd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sysykeji.top/Article/details/gtcjcwguew.html

[R59] 发 POST JSON
来源：http://dali.nwbrower.top/Article/details/gtiftpwwgb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sufxvd.cn/Article/details/gtbldakixw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gtwpoeuhiu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gtovpushxs.html

[R61] 磁盘占用
来源：http://dali.xylfe.cn/Article/details/gtofbjlkxs.html

df -h;  du -sh *
来源：http://dali.kuanghao11.cn/Article/details/gtqzpuevfb.html

[R62] 找最占空间的文件
来源：http://dali.yonumen.top/Article/details/gtthudnzim.html

du -ah . | sort -rh | head -10
来源：http://dali.bjfxy.top/Article/details/gtvvwpngjp.html

[R63] 内存与进程
来源：http://dali.hnqzz.top/Article/details/gtfmcjlitm.html

free -h;  ps aux | grep nginx
来源：http://dali.pengpengdd.cyou/Article/details/gtogoofxou.html

[R64] 结束进程
来源：http://dali.aibaodan.cn/Article/details/gtupinztqg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj202588.top/Article/details/gtqikrmtbv.html

[R65] 查看端口占用
来源：http://dali.daxiang520.top/Article/details/gtynoxzxsp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.havefunace.top/Article/details/gthcmbfbqu.html

[R66] 定时任务
来源：http://dali.jqgufenzy.top/Article/details/gtloauqofy.html

crontab -e;  crontab -l
来源：http://dali.nwbrower.top/Article/details/gtznagdpsm.html

[R67] 生成随机十六进制串
来源：http://dali.c1oappe.top/Article/details/gtkiwwrglg.html

openssl rand -hex 16
来源：http://dali.cheryme.top/Article/details/gthtipumfv.html

[R68] 计算文件校验值
来源：http://dali.xuanzx.com/Article/details/gtvuzjmqit.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yueranfly.top/Article/details/gtmnvuqpuj.html

[R69] 生成随机密码
来源：http://dali.wangshuangyany.cn/Article/details/gtrrzjkudv.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedmbshap.html

[R70] 时间戳与互转
来源：http://dali.dianchejie.cn/Article/details/gtkaupykpj.html

date +%s;  date -d @1700000000
来源：http://dali.hysaishi.cn/Article/details/gtfuldkuyf.html

[R71] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gtgfzcdndq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecoujbpb.html

[R72] 等待端口就绪
来源：http://dali.yanxiufei.cn/Article/details/gtbtbvxnqz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrnsuudxe.html

[R73] 分割大日志
来源：http://dali.fzhhl.top/Article/details/gtpwfiahjs.html

split -l 1000 big.log part_
来源：http://dali.haohaochexian.top/Article/details/gtddbqfxil.html

[R74] 批量重命名
来源：http://dali.ivvv.top/Article/details/gtgryopvkq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.guowangkeji.top/Article/details/gtrpeshbus.html

[R75] 导出环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gtzrmnhwzd.html


<!-- 参考信息 -->