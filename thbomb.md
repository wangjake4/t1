代发 wailian999

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yonumen.top/Article/details/gtrvnrhawv.html

[Q28] 求和与平均
来源：http://dali.svipenyu.cn/Article/details/gtfozkhtxb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtqplwdevd.html

[Q29] 最大最小值
来源：http://dali.tanke756.top/Article/details/gtptqbjgmw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtrjzlppyo.html

[Q30] 分组统计
来源：http://dali.gaohongyu789.top/Article/details/gtclkkssmo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gtyrdiczus.html

[Q31] 分组后过滤
来源：http://dali.xinyue.icu/Article/details/gtjsalctrz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yanxiufei.cn/Article/details/gttmydrual.html

[Q32] 分组拼接字符串
来源：http://dali.xylfe.cn/Article/details/gtqadvgidw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gtwvngbkjl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalntewfu.html

[Q33] 多列分组
来源：http://dali.daxiang520.top/Article/details/gtlelalvhr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.feifeiyinyue.top/Article/details/gtydshtlui.html

[Q34] 每组取第一条
来源：http://dali.nanxuanxn.top/Article/details/gtpogxyvrt.html

SELECT * FROM (
来源：http://dali.gaohongyu789.top/Article/details/gtobwupwit.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.andypj.xyz/Article/details/gthjaxenhr.html

) t WHERE rn = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjynozvdi.html

[Q35] 内连接
来源：http://dali.jqgfzy.top/Article/details/gttnmqhnga.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gtfxqvkhof.html

[Q36] 左连接
来源：http://dali.daxiang520.top/Article/details/gtdqosezqj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuanzx.com/Article/details/gtctbzahff.html

[Q37] 右连接
来源：http://dali.ydzc1.top/Article/details/gtfpfwxxkp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.c1oappe.top/Article/details/gtkggpzhqq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxinkj.top/Article/details/gtncvrmxom.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.mhx1999.top/Article/details/gtauahihsj.html

[Q39] 自连接（查上下级）
来源：http://dali.dashuyun.cn/Article/details/gtainzdftp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hammf.cn/Article/details/gtldtbkmas.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gogol.net.cn/Article/details/gtikfqbmlr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hongshengwenyu.top/Article/details/gtlisaqsii.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zycfv.cn/Article/details/gtcwqupfco.html

[Q41] 多表连接
来源：http://dali.smart0.xyz/Article/details/gtfgmcfvyy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.meibo888.top/Article/details/gtjfbjkvrc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj202588.top/Article/details/gtbzdijtht.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhengqikj.top/Article/details/gtjhladlnl.html

[Q42] 连接条件附加过滤
来源：http://dali.yuanzhike.top/Article/details/gtjraxlxkc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsydzzkae.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenlongwang.top/Article/details/gtrzwfdxzr.html

[Q43] 标量子查询
来源：http://dali.ybcxt.top/Article/details/gtewkwtxit.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shzxlz.cn/Article/details/gtfjqaigtb.html

[Q44] IN 子查询
来源：http://dali.jyoumei.cn/Article/details/gtuxwfrrvr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.c1oappe.top/Article/details/gtwkkwtotb.html

[Q45] EXISTS 判断存在
来源：http://dali.ehwqpu.com/Article/details/gthlioiobc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.vqdsnc.cn/Article/details/gtlpncoozv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhixingplan.top/Article/details/gtwncbbymv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gtiybeedcc.html

[Q47] 与平均值比较
来源：http://dali.cucudq.cn/Article/details/gtwtjfmpqh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.feifeiyinyue.top/Article/details/gtpxbxracb.html

[Q48] CTE 公用表表达式
来源：http://dali.zhixingplan.top/Article/details/gtlewqzctj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cucudq.cn/Article/details/gtayhwhfio.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqilzryoy.html

[Q49] 更新单行
来源：http://dali.316326.xyz/Article/details/gtlsgyqhwm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hfpthk.cn/Article/details/gttrphjjeq.html

[Q50] 批量更新
来源：http://dali.hammf.cn/Article/details/gtknzycqrk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hysaishi.cn/Article/details/gtgxtueqjr.html

[Q51] 用子查询更新
来源：http://dali.yonumen.top/Article/details/gtvxkcybkj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtiadtdszd.html

[Q52] 删除指定行
来源：http://dali.ppjwa.cn/Article/details/gtcncvoupt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gtanlwlezr.html

[Q53] 按条件删除
来源：http://dali.vqdsnc.cn/Article/details/gtbrpoipgn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yonumen.top/Article/details/gtbwzsdmet.html

[Q54] 清空表
来源：http://dali.iojbl.cn/Article/details/gtpgqumigk.html

TRUNCATE TABLE logs;
来源：http://dali.haohaochexian.top/Article/details/gtjreaernu.html

[Q55] 排名（并列占位）
来源：http://dali.tianlin.xyz/Article/details/gtjjxgcxti.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gtisyutqmm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hongshengwenyu.top/Article/details/gtyciqswas.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gtglevsiey.html

[Q57] 行号
来源：http://dali.hywenlv.cn/Article/details/gtpgljxjry.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtohopewre.html

[Q58] 累计求和
来源：http://dali.yvedp.cn/Article/details/gtxhpbkwvm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtvclrktjj.html

[Q59] 分组内累计
来源：http://dali.cucudq.cn/Article/details/gtmpktpbar.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtyeuchevr.html

[Q60] 取上一行 / 下一行
来源：http://dali.redwolf501.top/Article/details/gtbwtswnlq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ydzc1.top/Article/details/gtmzutgxuw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtytehfkfy.html

[Q61] 移动平均
来源：http://dali.316326.xyz/Article/details/gtxahokapm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.havefunace.top/Article/details/gtkttgnfku.html

[Q62] 分组占比
来源：http://dali.ydzc1.top/Article/details/gtxslwxvgq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtxlllbzug.html

[Q63] 开启事务
来源：http://dali.ppjwa.cn/Article/details/gtiglxklix.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.dashuyun.cn/Article/details/gtsjtmwajo.html

[Q64] 提交事务
来源：http://dali.cqqwz.cn/Article/details/gtauktvcet.html

COMMIT;
来源：http://dali.316326.xyz/Article/details/gtgzgdjqab.html

[Q65] 回滚事务
来源：http://dali.sxryk.cn/Article/details/gtmvcvhtwc.html

ROLLBACK;
来源：http://dali.svipenyu.cn/Article/details/gtbicbcmpv.html

[Q66] 行锁查询
来源：http://dali.xuanzx.com/Article/details/gtcxbmfxil.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuanzx.com/Article/details/gtpisgysck.html

[Q67] 设置隔离级别
来源：http://dali.smart0.xyz/Article/details/gtlujsmtgq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxncaxxhh.html

[Q68] 保存点
来源：http://dali.xuanzx.com/Article/details/gtauaeqbdc.html

SAVEPOINT sp1;
来源：http://dali.zhongyouzk.top/Article/details/gtlfyqkgld.html

ROLLBACK TO sp1;
来源：http://dali.chenzaomai.com/Article/details/gtvgywqwdx.html

[Q69] 查看执行计划
来源：http://dali.tian-w.cn/Article/details/gtzwnpxbqi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sysykeji.top/Article/details/gtfobzaumn.html

[Q70] 更新统计信息
来源：http://dali.316326.xyz/Article/details/gtekakvhgp.html

ANALYZE TABLE users;
来源：http://dali.yongpay.top/Article/details/gtzzjyococ.html

[Q71] 查看建表语句
来源：http://dali.tian-w.cn/Article/details/gtygwsewwh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.aizwys.cn/Article/details/gtjxhenabs.html

[Q72] 查看索引
来源：http://dali.cheryme.top/Article/details/gtkclupsra.html

SHOW INDEX FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtfvcesmwk.html

[Q73] 查看表状态
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvozgwwfb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sufxvd.cn/Article/details/gtyziwkzrk.html

[Q74] 强制使用索引
来源：http://dali.yvedp.cn/Article/details/gtoykhcjic.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhengqikj.top/Article/details/gtnkjbxzde.html

[Q75] 日期格式化
来源：http://dali.wangdashe.top/Article/details/gtstvqscbd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtaacnsqgo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yuxming.cn/Article/details/gtfsertrak.html

[Q76] 按天统计
来源：http://dali.aibaodan.cn/Article/details/gtsoqfluha.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aizwys.cn/Article/details/gtsypjkasx.html

[Q77] 时间加减
来源：http://dali.cashguo.top/Article/details/gtneewcnpa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daria6918.cn/Article/details/gttljcfery.html

[Q78] 当前时间
来源：http://dali.tanke756.top/Article/details/gtmuqhrwoe.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hysaishi.cn/Article/details/gtzsqugyfg.html

[Q79] 字符串拼接
来源：http://dali.quarkkingdee.top/Article/details/gtdmasnfpz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.316326.xyz/Article/details/gtcenckogz.html

[Q80] 字符串截取
来源：http://dali.nanxuanxn.top/Article/details/gtdnouhomq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtqauisqbb.html

[Q81] 字符串替换
来源：http://dali.hysaishi.cn/Article/details/gtdtluzeqs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sysykeji.top/Article/details/gtsylahxfe.html

[Q82] 字符长度与字节长度
来源：http://dali.c1oappe.top/Article/details/gtdzsyyego.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtvdbocvjy.html

[Q83] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gtukmjbvje.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtjfozofcq.html

[Q84] 去除首尾空格
来源：http://dali.dashuyun.cn/Article/details/gtdbuwknjz.html

SELECT TRIM(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtulpigkwj.html

[Q85] 数值取整
来源：http://dali.c1oappe.top/Article/details/gthippbvub.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cqqwz.cn/Article/details/gticcxiukw.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigfzy.top/Article/details/gttiaclpcd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhixingplan.top/Article/details/gtklwufclk.html

[Q87] JSON 字段做条件
来源：http://dali.nwbrower.top/Article/details/gtraygsuhy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhoulong.xyz/Article/details/gtttgogmvx.html

[Q88] 行转列（条件聚合）
来源：http://dali.hammf.cn/Article/details/gtlzdzhisa.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shuidangran.top/Article/details/gtcuqkwqot.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtxsstxscr.html

[Q89] 判断表是否存在
来源：http://dali.sysykeji.top/Article/details/gtweoakajn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pycfn.com/Article/details/gtkgvrparz.html

[Q90] 生成序号列
来源：http://dali.316326.xyz/Article/details/gtgbperygx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jiagoushi.top/Article/details/gtxbkcfuet.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtwkyabchj.html

R. Bash 专题
来源：http://dali.zdqjudy.top/Article/details/gtmkllifju.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtkazuvekg.html

[R01] shebang 与严格模式
来源：http://dali.hammf.cn/Article/details/gtdbckbzxg.html

#!/usr/bin/env bash
来源：http://dali.birdmap.top/Article/details/gtmefsistu.html

set -euo pipefail
来源：http://dali.vqdsnc.cn/Article/details/gtnqqnttlc.html

[R02] 变量赋值与使用
来源：http://dali.hnqzz.top/Article/details/gtkxizayrq.html

name="Tom"; echo "$name"
来源：http://dali.sweek.top/Article/details/gtqglugnve.html

[R03] 只读变量
来源：http://dali.fengsongda.top/Article/details/gtwnvworfe.html

readonly PI=3.14
来源：http://dali.aibaodan.cn/Article/details/gtirgucofz.html

[R04] 位置参数
来源：http://dali.yj20258888.top/Article/details/gtklltdiee.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jlsjyb.cn/Article/details/gtyztarocd.html

[R05] 参数默认值
来源：http://dali.gaohongyu789.top/Article/details/gtsvjuhhkh.html

name="${1:-default}"
来源：http://dali.yvedp.cn/Article/details/gtneuuyhkh.html

[R06] 判断命令是否存在
来源：http://dali.jinqigfzy.top/Article/details/gtsevnfmqh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gtetuosazb.html

[R07] if 判断文件
来源：http://dali.pengpengdd.cyou/Article/details/gtqtfeoday.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hammf.cn/Article/details/gtdtwxurdb.html

[R08] 数值比较
来源：http://dali.ydzc1.top/Article/details/gtosnaikrq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xziqi.cn/Article/details/gtohuvhyeh.html

[R09] 字符串比较
来源：http://dali.snrcjt.cn/Article/details/gtspcxueyr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.haohaochexian.top/Article/details/gtmthhxeme.html

[R10] 正则匹配
来源：http://dali.aizwys.cn/Article/details/gtwkvsbtbz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.bjfxy.top/Article/details/gtvkfwjxck.html

[R11] case 多分支
来源：http://dali.svipenyu.cn/Article/details/gtdoacwcdk.html

case "$1" in
来源：http://dali.pengpengdd.cyou/Article/details/gtewkkzvjb.html

start) echo "启动" ;;
来源：http://dali.redwolf501.top/Article/details/gtnzgddsna.html

stop)  echo "停止" ;;
来源：http://dali.nanxinkj.top/Article/details/gtiluaphcl.html

*)     echo "未知命令" ;;
来源：http://dali.mhx1999.top/Article/details/gtmqqbnfyb.html

esac
来源：http://dali.shangyingyoupin.top/Article/details/gtuxitxqah.html

[R12] for 遍历文件
来源：http://dali.ivvv.top/Article/details/gtpwfqimck.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hywenlv.cn/Article/details/gtqgvjtxnn.html

[R13] for 计数循环
来源：http://dali.haohaochexian.top/Article/details/gtaxbetths.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cdnleiting.top/Article/details/gtzxapscyx.html

[R14] C 风格 for
来源：http://dali.ivvv.top/Article/details/gtltulubwd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtgjycvstp.html

[R15] while 逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gtszolbnjk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zycfv.cn/Article/details/gtkepuftnb.html

[R16] until 等待条件
来源：http://dali.yj202588.top/Article/details/gtelyewsug.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gtexvlmhay.html

[R17] 数组定义与取值
来源：http://dali.cucudq.cn/Article/details/gtbjjuadfr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aizwys.cn/Article/details/gtirybxbal.html

[R18] 遍历数组
来源：http://dali.cheryme.top/Article/details/gthsmisufg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ybcxt.top/Article/details/gteouhtoqi.html

[R19] 数组长度
来源：http://dali.zhongyouzk.top/Article/details/gtkuemudgh.html

echo "${#arr[@]}"
来源：http://dali.feifeiyinyue.top/Article/details/gtviooefqd.html

[R20] 关联数组（字典）
来源：http://dali.jqgufenzy.top/Article/details/gtzllexrzs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigufen.top/Article/details/gtwteytvwj.html

[R21] 字符串长度
来源：http://dali.zycfv.cn/Article/details/gtlxpdusjz.html

echo "${#s}"
来源：http://dali.9152youxi.cn/Article/details/gtjkpdjzhd.html

[R22] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gtjpgwrzyi.html

echo "${s:0:5}"
来源：http://dali.gaohongyu789.top/Article/details/gtyxtokxkg.html

[R23] 字符串替换
来源：http://dali.jyoumei.cn/Article/details/gtmvqqyhlm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cashguo.top/Article/details/gthjvzporv.html

[R24] 大小写转换
来源：http://dali.sweek.top/Article/details/gtbqnfxldf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jlsjyb.cn/Article/details/gtjhegevhb.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnxiangtu.top/Article/details/gtailugkjs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yvedp.cn/Article/details/gtzzjffkdk.html

[R26] 命令替换
来源：http://dali.yangfankeji.com/Article/details/gthslnnqed.html

now=$(date +%F); echo "$now"
来源：http://dali.haohaochexian.top/Article/details/gtfenodvvn.html

[R27] 算术展开
来源：http://dali.jinqigfzy.top/Article/details/gtnhypahji.html

echo $((1 + 2 * 3))
来源：http://dali.xylfe.cn/Article/details/gtbtmsmaly.html

[R28] 浮点运算
来源：http://dali.sysykeji.top/Article/details/gtlyzdjreg.html

echo "scale=2; 10/3" | bc
来源：http://dali.sufxvd.cn/Article/details/gtchxrnxtb.html

[R29] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gthsynxtxe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.birdmap.top/Article/details/gtsuverqzl.html

[R30] 函数返回状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbenuoso.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.c1oappe.top/Article/details/gtjbciafdv.html

[R31] 局部变量
来源：http://dali.cashguo.top/Article/details/gtfrlwyrsm.html

f() { local x=1; echo "$x"; }
来源：http://dali.sysykeji.top/Article/details/gtcfezhpiw.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gtmdbcgejg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gtgiwpcwsp.html

[R33] 捕获错误并提示行号
来源：http://dali.yonumen.top/Article/details/gtgcpwisjx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cdnleiting.top/Article/details/gtfudknvss.html

[R34] 退出时清理
来源：http://dali.jiagoushi.top/Article/details/gtaklxpbvc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenzaomai.com/Article/details/gtikmykrft.html

[R35] 后台执行并等待
来源：http://dali.xylfe.cn/Article/details/gtsfqukfhd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zdqjudy.top/Article/details/gtccfovbaj.html

[R36] 并发执行多个任务
来源：http://dali.jqgfzy.top/Article/details/gtblbkdgjl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yongpay.top/Article/details/gtujikdiao.html

[R37] 把输出赋给变量
来源：http://dali.zhiwuduotai.top/Article/details/gtxifywtuv.html

files=$(ls -1)
来源：http://dali.xziqi.cn/Article/details/gtgomyuiol.html

[R38] 管道串联
来源：http://dali.jyoumei.cn/Article/details/gtwsyjyrcz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.smart0.xyz/Article/details/gtsvakgmla.html

[R39] 重定向标准输出与错误
来源：http://dali.zhongyouzk.top/Article/details/gtdwqeobpc.html

cmd > out.log 2>&1
来源：http://dali.zhixingplan.top/Article/details/gtymocqxfj.html

[R40] 追加写日志
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxbexorr.html

echo "log" >> out.log
来源：http://dali.xziqi.cn/Article/details/gteybkqhat.html

[R41] 丢弃输出
来源：http://dali.pycfn.com/Article/details/gtkrbqhgym.html

cmd >/dev/null 2>&1
来源：http://dali.ppjwa.cn/Article/details/gtejsdvhsh.html

[R42] 输入重定向
来源：http://dali.xinyue.icu/Article/details/gtyrnpkxsz.html

wc -l < a.txt
来源：http://dali.nwbrower.top/Article/details/gtqfhrkrzj.html

[R43] 按名字查找文件
来源：http://dali.kuanghao11.cn/Article/details/gtihbftnju.html

find . -name "*.log" -type f
来源：http://dali.zycfv.cn/Article/details/gtmqbsqvuz.html

[R44] 按修改时间查找
来源：http://dali.shangyingyoupin.top/Article/details/gtmrtqwzfp.html

find . -mtime -7 -type f
来源：http://dali.jqgufenzy.top/Article/details/gtksufjhom.html

[R45] 批量删除
来源：http://dali.shzxlz.cn/Article/details/gtareguepj.html

find . -name "*.tmp" -delete
来源：http://dali.jiagoushi.top/Article/details/gtvxzhcykg.html

[R46] 递归替换文件内容
来源：http://dali.xylfe.cn/Article/details/gtfdrhalao.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.iojbl.cn/Article/details/gtetvxjeda.html

[R47] sed 单行替换
来源：http://dali.redwolf501.top/Article/details/gtezfyhzou.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtuilyaxnd.html

[R48] awk 取指定列
来源：http://dali.pengpengdd.cyou/Article/details/gtvpjncwld.html

awk '{print $1, $3}' a.txt
来源：http://dali.wangdashe.top/Article/details/gtxgecxrvy.html

[R49] awk 带条件
来源：http://dali.bjfxy.top/Article/details/gtqgguccws.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.kuanghao11.cn/Article/details/gtnmgwzxxn.html

[R50] awk 求和
来源：http://dali.zhiwuduotai.top/Article/details/gtjhaobmlr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtlirsnulk.html

[R51] 排序去重取前几
来源：http://dali.jianghu66.top/Article/details/gtphhkrisb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cucudq.cn/Article/details/gtaljxskkk.html

[R52] 统计行数
来源：http://dali.mhx1999.top/Article/details/gtzjbntezm.html

wc -l a.txt
来源：http://dali.havefunace.top/Article/details/gtmgxixbyn.html

[R53] 查看文件头与实时尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrrthvqq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cashguo.top/Article/details/gtvkpuzcaa.html

[R54] 比较两个文件
来源：http://dali.shzxlz.cn/Article/details/gtpqvryqtj.html

diff a.txt b.txt
来源：http://dali.hnqzz.top/Article/details/gtdniplnld.html

[R55] 压缩与解压
来源：http://dali.jyoumei.cn/Article/details/gtzefietss.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.svipenyu.cn/Article/details/gtgbvpvyhl.html

[R56] 远程拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtfriiqxvu.html

scp file user@host:/path/
来源：http://dali.hammf.cn/Article/details/gtazplsfuz.html

[R57] 远程执行命令
来源：http://dali.jinghuilouyu.cn/Article/details/gtypbnrqaq.html

ssh user@host 'uptime'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxauphcyd.html

[R58] 下载文件
来源：http://dali.birdmap.top/Article/details/gtmznqmzqw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hammf.cn/Article/details/gtsdigsjga.html

[R59] 发 POST JSON
来源：http://dali.shangyingyoupin.top/Article/details/gtgiohkddf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuxming.cn/Article/details/gtwmwosvzc.html

[R60] 只看 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gtccjacmtf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tanke756.top/Article/details/gtxyxhlxsp.html

[R61] 磁盘占用
来源：http://dali.andypj.xyz/Article/details/gtkajwgvuv.html

df -h;  du -sh *
来源：http://dali.hongshengwenyu.top/Article/details/gtfgmgxnzc.html

[R62] 找最占空间的文件
来源：http://dali.chenzaomai.com/Article/details/gtlllgzkfk.html

du -ah . | sort -rh | head -10
来源：http://dali.316326.xyz/Article/details/gtjrscsfhj.html

[R63] 内存与进程
来源：http://dali.yangfankeji.com/Article/details/gtekolgmqf.html

free -h;  ps aux | grep nginx
来源：http://dali.smart0.xyz/Article/details/gtcyasgehw.html

[R64] 结束进程
来源：http://dali.gzhubu.top/Article/details/gtlooscmuf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.havefunace.top/Article/details/gtxmtyvimo.html

[R65] 查看端口占用
来源：http://dali.nanxinkj.top/Article/details/gtzasfgytj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhiwuduotai.top/Article/details/gtzzduymou.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gtdjvndpac.html

crontab -e;  crontab -l
来源：http://dali.dashuyun.cn/Article/details/gtmuajoksf.html

[R67] 生成随机十六进制串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmmpjwek.html

openssl rand -hex 16
来源：http://dali.xylfe.cn/Article/details/gtbeeuqgfz.html

[R68] 计算文件校验值
来源：http://dali.nanxinkj.top/Article/details/gtwqeaphtn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgfzy.top/Article/details/gtnaehmtfq.html

[R69] 生成随机密码
来源：http://dali.chenzaomai.com/Article/details/gtkkniepxu.html

head -c 16 /dev/urandom | base64
来源：http://dali.hnxiangtu.top/Article/details/gtctxkerpp.html

[R70] 时间戳与互转
来源：http://dali.nanxinkj.top/Article/details/gthmopigzq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gtgiaggcve.html

[R71] 日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gtduxvmwbi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuxming.cn/Article/details/gtajemswxj.html

[R72] 等待端口就绪
来源：http://dali.daria6918.cn/Article/details/gtmkvxcuvi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gtqlplivex.html

[R73] 分割大日志
来源：http://dali.snrcjt.cn/Article/details/gtstnszeuq.html

split -l 1000 big.log part_
来源：http://dali.jlsjyb.cn/Article/details/gtfsspomks.html

[R74] 批量重命名
来源：http://dali.jqgufenzy.top/Article/details/gtvcxdbjqz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aibaodan.cn/Article/details/gtfbgmmhvv.html

[R75] 导出环境变量
来源：http://dali.jyoumei.cn/Article/details/gtcqkskbrl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hammf.cn/Article/details/gthxzrtwwj.html

[R76] 使用临时文件
来源：http://dali.dashuyun.cn/Article/details/gtofxrdjmh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yongpay.top/Article/details/gtfpxtyovi.html

[R77] 读取用户输入
来源：http://dali.smart0.xyz/Article/details/gtygqgoswi.html


<!-- 参考信息 -->