代发 wailian999

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtlenbuiws.html

[Q30] 分组统计
来源：http://dali.cqqwz.cn/Article/details/gtvnseydyl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gtfeqmoftv.html

[Q31] 分组后过滤
来源：http://dali.tianlin.xyz/Article/details/gtbhyodvxq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.wangdashe.top/Article/details/gtbqywqjbo.html

[Q32] 分组拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gtciepbtfj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtrwwjizav.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tanke756.top/Article/details/gtcofvwaiv.html

[Q33] 多列分组
来源：http://dali.fzhhl.top/Article/details/gtpmsyoqkz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shuidangran.top/Article/details/gtakxrlwta.html

[Q34] 每组取第一条
来源：http://dali.hywenlv.cn/Article/details/gtzjygkrop.html

SELECT * FROM (
来源：http://dali.jinghuilouyu.cn/Article/details/gtlzhobulx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.havefunace.top/Article/details/gtvxadhdgv.html

) t WHERE rn = 1;
来源：http://dali.yuanzhike.top/Article/details/gtmvnhjong.html

[Q35] 内连接
来源：http://dali.cqqwz.cn/Article/details/gtnnkdhoii.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.svipenyu.cn/Article/details/gtkrawxcxv.html

[Q36] 左连接
来源：http://dali.yvedp.cn/Article/details/gtsjjerloe.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtijblapmy.html

[Q37] 右连接
来源：http://dali.ppjwa.cn/Article/details/gticycszoa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xinyue.icu/Article/details/gtybpholju.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuanzx.com/Article/details/gtutiflnxh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenlongwang.top/Article/details/gtxjpxctvg.html

[Q39] 自连接（查上下级）
来源：http://dali.jianghu66.top/Article/details/gtpinzmlay.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cqqwz.cn/Article/details/gtynslulrx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.9152youxi.cn/Article/details/gtywxkglcf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shangyingyoupin.top/Article/details/gtnoqcydns.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.316326.xyz/Article/details/gtgekboliq.html

[Q41] 多表连接
来源：http://dali.yangfankeji.com/Article/details/gtkmplzbgt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nanxinkj.top/Article/details/gtrgqxqslu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hnqzz.top/Article/details/gtouwmkbjy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuetiantiany.cn/Article/details/gtgwnqatun.html

[Q42] 连接条件附加过滤
来源：http://dali.shzxlz.cn/Article/details/gtjlsoscuz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.0kj1m.cn/Article/details/gtxwsylngt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtolgktelm.html

[Q43] 标量子查询
来源：http://dali.meibo888.top/Article/details/gtziavgbmf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xinyue.icu/Article/details/gtrttupqyf.html

[Q44] IN 子查询
来源：http://dali.daxiang520.top/Article/details/gthegxotdr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xuetiantiany.cn/Article/details/gthrqtuggr.html

[Q45] EXISTS 判断存在
来源：http://dali.0kj1m.cn/Article/details/gtvasumcoo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gtniilectv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgufenzy.top/Article/details/gtvbhxvvid.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ppjwa.cn/Article/details/gtfsxbdrpz.html

[Q47] 与平均值比较
来源：http://dali.jyoumei.cn/Article/details/gtubqzgpys.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nanxuanxn.top/Article/details/gtnkiawisf.html

[Q48] CTE 公用表表达式
来源：http://dali.jinqigufen.top/Article/details/gtiarqmlvl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.mhx1999.top/Article/details/gttvvzjwhc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.haohaochexian.top/Article/details/gtciniwoxi.html

[Q49] 更新单行
来源：http://dali.haohaochexian.top/Article/details/gtreekmkzt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gtpbotcito.html

[Q50] 批量更新
来源：http://dali.hfpthk.cn/Article/details/gtnquyjmeo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258.top/Article/details/gtxqowpomd.html

[Q51] 用子查询更新
来源：http://dali.jyoumei.cn/Article/details/gtkxldrhfr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.0kj1m.cn/Article/details/gtcjcyeimp.html

[Q52] 删除指定行
来源：http://dali.jinghuilouyu.cn/Article/details/gtstyczwvl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdltwsrxf.html

[Q53] 按条件删除
来源：http://dali.wangshuangyany.cn/Article/details/gtprkxscal.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.quarkkingdee.top/Article/details/gtgakzacdh.html

[Q54] 清空表
来源：http://dali.yuxming.cn/Article/details/gtbzmklbsq.html

TRUNCATE TABLE logs;
来源：http://dali.ppjwa.cn/Article/details/gtsibbynfz.html

[Q55] 排名（并列占位）
来源：http://dali.mhx1999.top/Article/details/gtrhzciwng.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.316326.xyz/Article/details/gttbespycc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jiagoushi.top/Article/details/gtuikvylje.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gtcojehooq.html

[Q57] 行号
来源：http://dali.guowangkeji.top/Article/details/gtbvpwzsqd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shuidangran.top/Article/details/gtdozqwlgr.html

[Q58] 累计求和
来源：http://dali.aibaodan.cn/Article/details/gtkxlsufrg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtijafeurg.html

[Q59] 分组内累计
来源：http://dali.tanke756.top/Article/details/gtkcaxujlt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gthkzlrcep.html

[Q60] 取上一行 / 下一行
来源：http://dali.andypj.xyz/Article/details/gtekodwrek.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ydzc1.top/Article/details/gtisetmput.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtyzvbnoza.html

[Q61] 移动平均
来源：http://dali.xinyue.icu/Article/details/gtvnxkxsdr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtrxoffzqv.html

[Q62] 分组占比
来源：http://dali.mhx1999.top/Article/details/gtsileealc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gtsqtbpmxx.html

[Q63] 开启事务
来源：http://dali.meibo888.top/Article/details/gtvyghjgwv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.guowangkeji.top/Article/details/gttowbnroc.html

[Q64] 提交事务
来源：http://dali.cdnleiting.top/Article/details/gtxgicfgjb.html

COMMIT;
来源：http://dali.xziqi.cn/Article/details/gtfbvdjagv.html

[Q65] 回滚事务
来源：http://dali.9152youxi.cn/Article/details/gtxxzlibyo.html

ROLLBACK;
来源：http://dali.yueranfly.top/Article/details/gtlesqyxim.html

[Q66] 行锁查询
来源：http://dali.xuanzx.com/Article/details/gtivmtnjvj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.smart0.xyz/Article/details/gtfitsngqi.html

[Q67] 设置隔离级别
来源：http://dali.jyoumei.cn/Article/details/gtgbjgkprs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aizwys.cn/Article/details/gtqemvpbtd.html

[Q68] 保存点
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpinuuiny.html

SAVEPOINT sp1;
来源：http://dali.ydzc1.top/Article/details/gtmmojpoum.html

ROLLBACK TO sp1;
来源：http://dali.nanxinkj.top/Article/details/gtwovvzoxo.html

[Q69] 查看执行计划
来源：http://dali.daxiang520.top/Article/details/gtldcneahh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.wangshuangyany.cn/Article/details/gtvtfrzisg.html

[Q70] 更新统计信息
来源：http://dali.shangyingyoupin.top/Article/details/gtrgnqsemg.html

ANALYZE TABLE users;
来源：http://dali.ehwqpu.com/Article/details/gtlthfdnee.html

[Q71] 查看建表语句
来源：http://dali.daxiang520.top/Article/details/gtskioknul.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj202588.top/Article/details/gtoasflhts.html

[Q72] 查看索引
来源：http://dali.yongpay.top/Article/details/gtcupmxkvk.html

SHOW INDEX FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtbvunglbq.html

[Q73] 查看表状态
来源：http://dali.jinqigufen.top/Article/details/gtxqpmgrwb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tian-w.cn/Article/details/gthazexfct.html

[Q74] 强制使用索引
来源：http://dali.xziqi.cn/Article/details/gtssnjcbyl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.c1oappe.top/Article/details/gtsvzqbiwe.html

[Q75] 日期格式化
来源：http://dali.gaohongyu789.top/Article/details/gtxojaeshq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtmqileyjd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yangfankeji.com/Article/details/gtlbcspiwo.html

[Q76] 按天统计
来源：http://dali.yonumen.top/Article/details/gtimmlyugg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gogol.net.cn/Article/details/gthmijxvma.html

[Q77] 时间加减
来源：http://dali.ivvv.top/Article/details/gtgclgilio.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ybcxt.top/Article/details/gtgjxndoqf.html

[Q78] 当前时间
来源：http://dali.ehwqpu.com/Article/details/gtoeyxtxpb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgufenzy.top/Article/details/gtfkhwkhyd.html

[Q79] 字符串拼接
来源：http://dali.xuanzx.com/Article/details/gtptvbueis.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hysaishi.cn/Article/details/gtdoopziuv.html

[Q80] 字符串截取
来源：http://dali.xylfe.cn/Article/details/gtjidhgxuq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtlztfgkfn.html

[Q81] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gtqhqpujtb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtrbwzng.html

[Q82] 字符长度与字节长度
来源：http://dali.gogol.net.cn/Article/details/gtchzlhdot.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtbrefrbqe.html

[Q83] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gtiudexojw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtqlmbmksh.html

[Q84] 去除首尾空格
来源：http://dali.aizwys.cn/Article/details/gtgxohivxd.html

SELECT TRIM(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gtekpzriyt.html

[Q85] 数值取整
来源：http://dali.cdnleiting.top/Article/details/gtbhpfgeep.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.aizwys.cn/Article/details/gtmedhmrod.html

[Q86] 读取 JSON 字段
来源：http://dali.yanxiufei.cn/Article/details/gtjocugual.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dashuyun.cn/Article/details/gtlvwlroeu.html

[Q87] JSON 字段做条件
来源：http://dali.hfpthk.cn/Article/details/gtvzscytds.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinqigfzy.top/Article/details/gtycunzevt.html

[Q88] 行转列（条件聚合）
来源：http://dali.0kj1m.cn/Article/details/gtafziusze.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hongshengwenyu.top/Article/details/gttnsoafzb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtlvkreexv.html

[Q89] 判断表是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtesccvnfh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hywenlv.cn/Article/details/gtuamurmlx.html

[Q90] 生成序号列
来源：http://dali.cashguo.top/Article/details/gtudpsnlln.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gzhubu.top/Article/details/gtxqhmjjtk.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtlmmsmqpm.html

R. Bash 专题
来源：http://dali.sweek.top/Article/details/gtmwwkxjjr.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtimkpbcmd.html

[R01] shebang 与严格模式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhrtpqnd.html

#!/usr/bin/env bash
来源：http://dali.yangfankeji.com/Article/details/gtmzjslgis.html

set -euo pipefail
来源：http://dali.xinyue.icu/Article/details/gtmupcjtmn.html

[R02] 变量赋值与使用
来源：http://dali.mhx1999.top/Article/details/gtzdqpeoim.html

name="Tom"; echo "$name"
来源：http://dali.sysykeji.top/Article/details/gtyicqgfde.html

[R03] 只读变量
来源：http://dali.sweek.top/Article/details/gtwdnptztr.html

readonly PI=3.14
来源：http://dali.jqgufenzy.top/Article/details/gtrxyoqvuf.html

[R04] 位置参数
来源：http://dali.xylfe.cn/Article/details/gtqikpefnt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.9152youxi.cn/Article/details/gtqhsmwsaa.html

[R05] 参数默认值
来源：http://dali.fengsongda.top/Article/details/gtamqdgxjl.html

name="${1:-default}"
来源：http://dali.yj20258888.top/Article/details/gtyvfxxqyx.html

[R06] 判断命令是否存在
来源：http://dali.aizwys.cn/Article/details/gtspdecuhc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenzaomai.com/Article/details/gtkmsuzrku.html

[R07] if 判断文件
来源：http://dali.yueranfly.top/Article/details/gtiaxkhhrb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwmoiubs.html

[R08] 数值比较
来源：http://dali.jianghu66.top/Article/details/gtmqglrxct.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtyyfyygux.html

[R09] 字符串比较
来源：http://dali.bjfxy.top/Article/details/gtblitsqoh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cdnleiting.top/Article/details/gtemyvdupd.html

[R10] 正则匹配
来源：http://dali.svipenyu.cn/Article/details/gtktreahwf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jiagoushi.top/Article/details/gtkjpdjvij.html

[R11] case 多分支
来源：http://dali.9152youxi.cn/Article/details/gtmozpxzyw.html

case "$1" in
来源：http://dali.yangfankeji.com/Article/details/gtmxytpyaj.html

start) echo "启动" ;;
来源：http://dali.svipenyu.cn/Article/details/gtvwufosit.html

stop)  echo "停止" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiolahawz.html

*)     echo "未知命令" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gtusccfkbj.html

esac
来源：http://dali.yuanzhike.top/Article/details/gtdqqhcjye.html

[R12] for 遍历文件
来源：http://dali.jqgfzy.top/Article/details/gtypfocrxw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.bjfxy.top/Article/details/gtvbftlpxr.html

[R13] for 计数循环
来源：http://dali.yongpay.top/Article/details/gtusikjeuq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gogol.net.cn/Article/details/gtrzluaasy.html

[R14] C 风格 for
来源：http://dali.tian-w.cn/Article/details/gtixsvaxvz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hnxiangtu.top/Article/details/gtzycnkayw.html

[R15] while 逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtbjtbqahe.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhengqikj.top/Article/details/gtntquynhz.html

[R16] until 等待条件
来源：http://dali.chenjidiqi.icu/Article/details/gtucokcwrc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenzaomai.com/Article/details/gthjqsuayr.html

[R17] 数组定义与取值
来源：http://dali.dashuyun.cn/Article/details/gtvyvaqtay.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.iojbl.cn/Article/details/gthjcounnh.html

[R18] 遍历数组
来源：http://dali.pengpengdd.cyou/Article/details/gtgvcpgcaw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sweek.top/Article/details/gtgfdffhtw.html

[R19] 数组长度
来源：http://dali.sysykeji.top/Article/details/gtnlsppwhy.html

echo "${#arr[@]}"
来源：http://dali.daxiang520.top/Article/details/gtoxbsleyk.html

[R20] 关联数组（字典）
来源：http://dali.hfpthk.cn/Article/details/gtzrxraxhx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hammf.cn/Article/details/gtbjninsst.html

[R21] 字符串长度
来源：http://dali.jianghu66.top/Article/details/gtrwwfwlcx.html

echo "${#s}"
来源：http://dali.jinqigufen.top/Article/details/gtsonhqzwp.html

[R22] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gtjjjizcrg.html

echo "${s:0:5}"
来源：http://dali.jinqigfzy.top/Article/details/gtzkdclcau.html

[R23] 字符串替换
来源：http://dali.tian-w.cn/Article/details/gtgiuuiked.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.0kj1m.cn/Article/details/gtxkxybivg.html

[R24] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwuczzqoy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xylfe.cn/Article/details/gtgsdnwjrk.html

[R25] 去后缀 / 去前缀
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhhgmjpj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuxming.cn/Article/details/gtbrmrjqnw.html

[R26] 命令替换
来源：http://dali.zhiwuduotai.top/Article/details/gtwejryhoq.html

now=$(date +%F); echo "$now"
来源：http://dali.hongshengwenyu.top/Article/details/gtzxitqwko.html

[R27] 算术展开
来源：http://dali.yvedp.cn/Article/details/gtcvkmqejt.html

echo $((1 + 2 * 3))
来源：http://dali.birdmap.top/Article/details/gtzcoexjij.html

[R28] 浮点运算
来源：http://dali.hongshengwenyu.top/Article/details/gtqxndoivb.html

echo "scale=2; 10/3" | bc
来源：http://dali.jyoumei.cn/Article/details/gtvsbuhlqk.html

[R29] 定义函数
来源：http://dali.kuanghao11.cn/Article/details/gtlivndldz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.redwolf501.top/Article/details/gtchzlbtlc.html

[R30] 函数返回状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznrrrate.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.snrcjt.cn/Article/details/gtdbrjvnwi.html

[R31] 局部变量
来源：http://dali.dashuyun.cn/Article/details/gtrgtxrmku.html

f() { local x=1; echo "$x"; }
来源：http://dali.yvedp.cn/Article/details/gtgnrxmsma.html

[R32] 参数个数校验
来源：http://dali.pengpengdd.cyou/Article/details/gtpszdxupj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gtuvmczqol.html

[R33] 捕获错误并提示行号
来源：http://dali.zhongyouzk.top/Article/details/gtnvfdnlft.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cdnleiting.top/Article/details/gtrodzpqnw.html

[R34] 退出时清理
来源：http://dali.jqgufenzy.top/Article/details/gtjwqyouyi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gtobemylja.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangtech.top/Article/details/gtzoffarej.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gtmlgrzrxt.html

[R36] 并发执行多个任务
来源：http://dali.sxryk.cn/Article/details/gtkyigzrrr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuxming.cn/Article/details/gtrwkzzhwz.html

[R37] 把输出赋给变量
来源：http://dali.feifeiyinyue.top/Article/details/gtvfdyjxhk.html

files=$(ls -1)
来源：http://dali.haohaochexian.top/Article/details/gtiefuhfou.html

[R38] 管道串联
来源：http://dali.cdnleiting.top/Article/details/gttpkxdycw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shzxlz.cn/Article/details/gtrogsiheg.html

[R39] 重定向标准输出与错误
来源：http://dali.fengsongda.top/Article/details/gtzgadyvma.html

cmd > out.log 2>&1
来源：http://dali.c1oappe.top/Article/details/gtjkfefuye.html

[R40] 追加写日志
来源：http://dali.chenlongwang.top/Article/details/gttrntyddr.html

echo "log" >> out.log
来源：http://dali.zhixingplan.top/Article/details/gtyjhiqipn.html

[R41] 丢弃输出
来源：http://dali.snrcjt.cn/Article/details/gtctufedyl.html

cmd >/dev/null 2>&1
来源：http://dali.meibo888.top/Article/details/gthhznoxol.html

[R42] 输入重定向
来源：http://dali.fzhhl.top/Article/details/gttxpbyflc.html

wc -l < a.txt
来源：http://dali.gzhubu.top/Article/details/gtkkmunvzy.html

[R43] 按名字查找文件
来源：http://dali.cashguo.top/Article/details/gtdzdapiyw.html

find . -name "*.log" -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gttdkcgtca.html

[R44] 按修改时间查找
来源：http://dali.quarkkingdee.top/Article/details/gtjebxwfsy.html

find . -mtime -7 -type f
来源：http://dali.hywenlv.cn/Article/details/gtbwpoajyi.html

[R45] 批量删除
来源：http://dali.daria6918.cn/Article/details/gtmbnvzrfm.html

find . -name "*.tmp" -delete
来源：http://dali.jinghuilouyu.cn/Article/details/gtxebwmucv.html

[R46] 递归替换文件内容
来源：http://dali.shangyingyoupin.top/Article/details/gtxaigrjva.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ppjwa.cn/Article/details/gtcfszbsmh.html

[R47] sed 单行替换
来源：http://dali.jlsjyb.cn/Article/details/gtuktcbifz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtcblmauwe.html

[R48] awk 取指定列
来源：http://dali.tanke756.top/Article/details/gtntvjroll.html

awk '{print $1, $3}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoygppgos.html

[R49] awk 带条件
来源：http://dali.cdnleiting.top/Article/details/gtqwksiyhv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.c1oappe.top/Article/details/gtjrfbrsmw.html

[R50] awk 求和
来源：http://dali.haohaochexian.top/Article/details/gtnuhpjeys.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gtsdqcsrzz.html

[R51] 排序去重取前几
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdwvlkcg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.bjfxy.top/Article/details/gtigufeqvm.html

[R52] 统计行数
来源：http://dali.quarkkingdee.top/Article/details/gtmdgfwjtr.html

wc -l a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtpmjoleyl.html

[R53] 查看文件头与实时尾
来源：http://dali.aizwys.cn/Article/details/gtzqprvesv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhixingplan.top/Article/details/gtmtfpzefv.html

[R54] 比较两个文件
来源：http://dali.wangdashe.top/Article/details/gtrnpgntkf.html

diff a.txt b.txt
来源：http://dali.chenlongwang.top/Article/details/gtpfhwbvos.html

[R55] 压缩与解压
来源：http://dali.yonumen.top/Article/details/gtocscurdg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ehwqpu.com/Article/details/gtjtfoiyis.html

[R56] 远程拷贝
来源：http://dali.jinghuilouyu.cn/Article/details/gtjsayyatr.html

scp file user@host:/path/
来源：http://dali.andypj.xyz/Article/details/gtfpeunfbl.html

[R57] 远程执行命令
来源：http://dali.yonumen.top/Article/details/gtwvzansxa.html

ssh user@host 'uptime'
来源：http://dali.hammf.cn/Article/details/gtnwhrsynh.html

[R58] 下载文件
来源：http://dali.meibo888.top/Article/details/gtwvbvpglx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xylfe.cn/Article/details/gtoxyxorek.html

[R59] 发 POST JSON
来源：http://dali.gzhubu.top/Article/details/gtukmetedb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zdqjudy.top/Article/details/gtltkzcmme.html

[R60] 只看 HTTP 状态码
来源：http://dali.aibaodan.cn/Article/details/gtwhqdpcay.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycezgqnt.html

[R61] 磁盘占用
来源：http://dali.yueranfly.top/Article/details/gtpvbvwamz.html

df -h;  du -sh *
来源：http://dali.xylfe.cn/Article/details/gtmyhizrow.html

[R62] 找最占空间的文件
来源：http://dali.shangyingyoupin.top/Article/details/gtybdjqouc.html

du -ah . | sort -rh | head -10
来源：http://dali.jinqigfzy.top/Article/details/gtzpstwfwu.html

[R63] 内存与进程
来源：http://dali.iojbl.cn/Article/details/gtjjcjwdao.html

free -h;  ps aux | grep nginx
来源：http://dali.jlsjyb.cn/Article/details/gtzmsgilyb.html

[R64] 结束进程
来源：http://dali.daria6918.cn/Article/details/gtabslgdvu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shuidangran.top/Article/details/gtshqifbhs.html

[R65] 查看端口占用
来源：http://dali.jqgufenzy.top/Article/details/gtxpmpbnho.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.fengsongda.top/Article/details/gtwemqbkzv.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gtidtkjepu.html

crontab -e;  crontab -l
来源：http://dali.ybcxt.top/Article/details/gtswstkfgk.html

[R67] 生成随机十六进制串
来源：http://dali.wangdashe.top/Article/details/gtafeyhart.html

openssl rand -hex 16
来源：http://dali.jqgufenzy.top/Article/details/gtcumjtbuq.html

[R68] 计算文件校验值
来源：http://dali.tanke756.top/Article/details/gtrqyqtvwh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nwbrower.top/Article/details/gttitqzlkl.html

[R69] 生成随机密码
来源：http://dali.c1oappe.top/Article/details/gtyhlaokwi.html

head -c 16 /dev/urandom | base64
来源：http://dali.hfpthk.cn/Article/details/gtarfhfqhv.html

[R70] 时间戳与互转
来源：http://dali.tanke756.top/Article/details/gtoxiovtgg.html

date +%s;  date -d @1700000000
来源：http://dali.0kj1m.cn/Article/details/gtnddpvxwo.html

[R71] 日期格式化
来源：http://dali.cheryme.top/Article/details/gtfjjulgtd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yanxiufei.cn/Article/details/gtfjasbnex.html

[R72] 等待端口就绪
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavhzsmig.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.aizwys.cn/Article/details/gtxhsghttx.html

[R73] 分割大日志
来源：http://dali.gotoacloud.top/Article/details/gtunoqokfr.html

split -l 1000 big.log part_
来源：http://dali.sweek.top/Article/details/gtaewogixf.html

[R74] 批量重命名
来源：http://dali.jiagoushi.top/Article/details/gtzkcoewlr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pycfn.com/Article/details/gticumvtnu.html

[R75] 导出环境变量
来源：http://dali.chenlongwang.top/Article/details/gtnnkroxco.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sysykeji.top/Article/details/gtgzhfrvdq.html

[R76] 使用临时文件
来源：http://dali.yonumen.top/Article/details/gtqoqmvnjr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sufxvd.cn/Article/details/gtvbellwlr.html

[R77] 读取用户输入
来源：http://dali.zhoulong.xyz/Article/details/gthofdmrzb.html

read -rp "请输入: " ans
来源：http://dali.jinqigfzy.top/Article/details/gteeuqkheb.html

[R78] 交互式菜单
来源：http://dali.yj20258888.top/Article/details/gtjdzynyff.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuetiantiany.cn/Article/details/gtzmtuhrip.html

[R79] 解析命令行选项
来源：http://dali.dianchejie.cn/Article/details/gtdeuoqfiz.html


<!-- 参考信息 -->