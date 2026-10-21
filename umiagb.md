代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hywenlv.cn/Article/details/gtwxwypabk.html

[Q24] 去重
来源：http://dali.yuanzhike.top/Article/details/gtyzmadowx.html

SELECT DISTINCT city FROM users;
来源：http://dali.mhx1999.top/Article/details/gtfrjzzeco.html

[Q25] 只取前 N 条
来源：http://dali.guowangkeji.top/Article/details/gtyvfhjxxp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sufxvd.cn/Article/details/gtfmllqpiy.html

[Q26] 计数
来源：http://dali.daxiang520.top/Article/details/gtlzzihedi.html

SELECT COUNT(*) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtafjujqsn.html

[Q27] 条件计数
来源：http://dali.aibaodan.cn/Article/details/gtdavshehx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtnikrkapt.html

[Q28] 求和与平均
来源：http://dali.zycfv.cn/Article/details/gtezlmmyku.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sweek.top/Article/details/gtawggtbqz.html

[Q29] 最大最小值
来源：http://dali.9152youxi.cn/Article/details/gtnndfrlov.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzlxmutzt.html

[Q30] 分组统计
来源：http://dali.yj202588.top/Article/details/gtfamjplkh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gtjdeizxyx.html

[Q31] 分组后过滤
来源：http://dali.daxiang520.top/Article/details/gtnjfkxqtx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjgspres.html

[Q32] 分组拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gtfhfvooio.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gtomyvlpgs.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hnxiangtu.top/Article/details/gtwwjtkqcx.html

[Q33] 多列分组
来源：http://dali.yangfankeji.com/Article/details/gttmnzaxrt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hfpthk.cn/Article/details/gtouxdlzdc.html

[Q34] 每组取第一条
来源：http://dali.mhx1999.top/Article/details/gtkqyxlliu.html

SELECT * FROM (
来源：http://dali.redwolf501.top/Article/details/gttjeowvjr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhongyouzk.top/Article/details/gtljxqayqo.html

) t WHERE rn = 1;
来源：http://dali.gotoacloud.top/Article/details/gtfuijjuau.html

[Q35] 内连接
来源：http://dali.shzxlz.cn/Article/details/gtkbvfhxdr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.c1oappe.top/Article/details/gtgfiefrws.html

[Q36] 左连接
来源：http://dali.nwbrower.top/Article/details/gtbfbwoehs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gtncbzbcqq.html

[Q37] 右连接
来源：http://dali.zycfv.cn/Article/details/gtteozjpib.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj202588.top/Article/details/gttxnjvluk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hfpthk.cn/Article/details/gtthcwntzp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinqigfzy.top/Article/details/gtocaggyfm.html

[Q39] 自连接（查上下级）
来源：http://dali.gogol.net.cn/Article/details/gtlptyuzod.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.fengsongda.top/Article/details/gtjcleyutd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tianlin.xyz/Article/details/gtmatijhkc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cdnleiting.top/Article/details/gtebrysiob.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.havefunace.top/Article/details/gtyfbdyzhp.html

[Q41] 多表连接
来源：http://dali.dashuyun.cn/Article/details/gtlpbzxiyo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tanke756.top/Article/details/gtdqlcqckk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fengsongda.top/Article/details/gtkdyimkbu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tianlin.xyz/Article/details/gtebjdgmbe.html

[Q42] 连接条件附加过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtniyvbjno.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ivvv.top/Article/details/gtikdatutv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258.top/Article/details/gtlxfpifee.html

[Q43] 标量子查询
来源：http://dali.0kj1m.cn/Article/details/gtczhfimam.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.birdmap.top/Article/details/gtijtegjgc.html

[Q44] IN 子查询
来源：http://dali.hnqzz.top/Article/details/gtqrorvvui.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sufxvd.cn/Article/details/gtvyqutcqf.html

[Q45] EXISTS 判断存在
来源：http://dali.hnqzz.top/Article/details/gtwyxgjmrk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nwbrower.top/Article/details/gtubjjudnb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.pengpengdd.cyou/Article/details/gtkwdgqtau.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gtfkpgzwff.html

[Q47] 与平均值比较
来源：http://dali.gogol.net.cn/Article/details/gtzxtevtlr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258.top/Article/details/gtnxcjlzxr.html

[Q48] CTE 公用表表达式
来源：http://dali.sweek.top/Article/details/gtforwxxmk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.andypj.xyz/Article/details/gtogeccsof.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tanke756.top/Article/details/gtxqsssnbi.html

[Q49] 更新单行
来源：http://dali.zhiwuduotai.top/Article/details/gttqecgvgk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yonumen.top/Article/details/gtjfgzzoab.html

[Q50] 批量更新
来源：http://dali.svipenyu.cn/Article/details/gtganqlmth.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guowangkeji.top/Article/details/gtolesifzu.html

[Q51] 用子查询更新
来源：http://dali.mhx1999.top/Article/details/gtnqksmlfk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.fzhhl.top/Article/details/gtrppocvpj.html

[Q52] 删除指定行
来源：http://dali.nwbrower.top/Article/details/gthnqktrvv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtuymlzyot.html

[Q53] 按条件删除
来源：http://dali.nwbrower.top/Article/details/gtfbunermz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gtqmqwivpl.html

[Q54] 清空表
来源：http://dali.sxryk.cn/Article/details/gtiqtzaapt.html

TRUNCATE TABLE logs;
来源：http://dali.cdnleiting.top/Article/details/gtdxlxzgpj.html

[Q55] 排名（并列占位）
来源：http://dali.daxiang520.top/Article/details/gtjplbdmpz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gteeiriahk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ivvv.top/Article/details/gtcdmahgva.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhoulong.xyz/Article/details/gtvsojkaza.html

[Q57] 行号
来源：http://dali.bjfxy.top/Article/details/gtmzwbidlg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tanke756.top/Article/details/gtnvbgjldc.html

[Q58] 累计求和
来源：http://dali.yvedp.cn/Article/details/gtxuqibuft.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtanqgunfo.html

[Q59] 分组内累计
来源：http://dali.nwbrower.top/Article/details/gtdetijfis.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopshxiyt.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhongyouzk.top/Article/details/gtqpokkvxo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwaadriyi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtuypefaky.html

[Q61] 移动平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvwbtuya.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gturuhnkcw.html

[Q62] 分组占比
来源：http://dali.fzhhl.top/Article/details/gtqooagwma.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtudsyfxnu.html

[Q63] 开启事务
来源：http://dali.haohaochexian.top/Article/details/gtmgtogavk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenlongwang.top/Article/details/gtnbpqzmds.html

[Q64] 提交事务
来源：http://dali.sweek.top/Article/details/gtpbiuhpip.html

COMMIT;
来源：http://dali.meibo888.top/Article/details/gtwowdvtih.html

[Q65] 回滚事务
来源：http://dali.birdmap.top/Article/details/gtsgoqxspq.html

ROLLBACK;
来源：http://dali.hongshengwenyu.top/Article/details/gtzicjagka.html

[Q66] 行锁查询
来源：http://dali.svipenyu.cn/Article/details/gtxozjloke.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.9152youxi.cn/Article/details/gtuzqjbkda.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangtech.top/Article/details/gtdomgzyuc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shzxlz.cn/Article/details/gtguitanik.html

[Q68] 保存点
来源：http://dali.tianlin.xyz/Article/details/gtfergfyjp.html

SAVEPOINT sp1;
来源：http://dali.guannengcc.top/Article/details/gtidaqgpsk.html

ROLLBACK TO sp1;
来源：http://dali.gzhubu.top/Article/details/gtyaadaxlp.html

[Q69] 查看执行计划
来源：http://dali.shangyingyoupin.top/Article/details/gtcyvywalt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenjidiqi.icu/Article/details/gtuhuiizip.html

[Q70] 更新统计信息
来源：http://dali.0kj1m.cn/Article/details/gtqjlljntw.html

ANALYZE TABLE users;
来源：http://dali.gogol.net.cn/Article/details/gtwjrblvmi.html

[Q71] 查看建表语句
来源：http://dali.xuanzx.com/Article/details/gtyhynsglf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jiagoushi.top/Article/details/gtfbbdjoyd.html

[Q72] 查看索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhvrmtdj.html

SHOW INDEX FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtffjusfmw.html

[Q73] 查看表状态
来源：http://dali.ivvv.top/Article/details/gtlokxpsfz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuanzhike.top/Article/details/gtarrbmqpf.html

[Q74] 强制使用索引
来源：http://dali.wangdashe.top/Article/details/gtwkrokwch.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuetiantiany.cn/Article/details/gtzqwtoquu.html

[Q75] 日期格式化
来源：http://dali.tianlin.xyz/Article/details/gtkodlroxw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtshrpcsvt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hywenlv.cn/Article/details/gtuunshhfk.html

[Q76] 按天统计
来源：http://dali.havefunace.top/Article/details/gttzytamvp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yangfankeji.com/Article/details/gtejdjlmid.html

[Q77] 时间加减
来源：http://dali.yonumen.top/Article/details/gtolhuyjtr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daxiang520.top/Article/details/gtfmuyafuw.html

[Q78] 当前时间
来源：http://dali.zhixingplan.top/Article/details/gtwzxtdxgk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nwbrower.top/Article/details/gtmeclnmqk.html

[Q79] 字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gtjlftjbux.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdaarlpo.html

[Q80] 字符串截取
来源：http://dali.gogol.net.cn/Article/details/gtvtettaoy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtipeqsydu.html

[Q81] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gtopzxlgqs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yonumen.top/Article/details/gtscclwhmt.html

[Q82] 字符长度与字节长度
来源：http://dali.quarkkingdee.top/Article/details/gtpasrpfgz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gtfjueaped.html

[Q83] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gtaogzrpns.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gtjwquevda.html

[Q84] 去除首尾空格
来源：http://dali.aibaodan.cn/Article/details/gtgykawdaj.html

SELECT TRIM(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtzxuwchyp.html

[Q85] 数值取整
来源：http://dali.316326.xyz/Article/details/gtvjywuxoo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cqqwz.cn/Article/details/gtlwrsdnbu.html

[Q86] 读取 JSON 字段
来源：http://dali.zhixingplan.top/Article/details/gtsfpqcszg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sysykeji.top/Article/details/gtlrxvnijy.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigfzy.top/Article/details/gtsapdgrse.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangdashe.top/Article/details/gtpyubgqpp.html

[Q88] 行转列（条件聚合）
来源：http://dali.hywenlv.cn/Article/details/gtkmuvcwmz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.0kj1m.cn/Article/details/gtinoxqcqi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtumrbfquh.html

[Q89] 判断表是否存在
来源：http://dali.guannengcc.top/Article/details/gtcdhltbqs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gogol.net.cn/Article/details/gtihpyhqoq.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gtqzejtjpm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.fzhhl.top/Article/details/gtffyziakx.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtykcskznb.html

R. Bash 专题
来源：http://dali.feifeiyinyue.top/Article/details/gtfhnyebnq.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtkhlubiha.html

[R01] shebang 与严格模式
来源：http://dali.gotoacloud.top/Article/details/gtjwiatnvu.html

#!/usr/bin/env bash
来源：http://dali.dashuyun.cn/Article/details/gtzeajqswn.html

set -euo pipefail
来源：http://dali.tianlin.xyz/Article/details/gtlnhrtcfw.html

[R02] 变量赋值与使用
来源：http://dali.jianghu66.top/Article/details/gtgvaaieia.html

name="Tom"; echo "$name"
来源：http://dali.chenjidiqi.icu/Article/details/gtdcjseblw.html

[R03] 只读变量
来源：http://dali.9152youxi.cn/Article/details/gtfvaktpxi.html

readonly PI=3.14
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdwnocotz.html

[R04] 位置参数
来源：http://dali.hnqzz.top/Article/details/gtnawjytxv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pengpengdd.cyou/Article/details/gtsadsorvb.html

[R05] 参数默认值
来源：http://dali.hywenlv.cn/Article/details/gthwlcgvtw.html

name="${1:-default}"
来源：http://dali.yueranfly.top/Article/details/gtvijragwi.html

[R06] 判断命令是否存在
来源：http://dali.yuxming.cn/Article/details/gtzolpttnc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gtuxyetffk.html

[R07] if 判断文件
来源：http://dali.fengsongda.top/Article/details/gtxrwqquhu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbolisgc.html

[R08] 数值比较
来源：http://dali.sweek.top/Article/details/gtowdgicnl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.aizwys.cn/Article/details/gtidzpcpul.html

[R09] 字符串比较
来源：http://dali.zhengqikj.top/Article/details/gtymhdwrlv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.redwolf501.top/Article/details/gtzseuvomt.html

[R10] 正则匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtpmowrcjv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.pycfn.com/Article/details/gtgqsbqhqk.html

[R11] case 多分支
来源：http://dali.jinqigufen.top/Article/details/gtsprdyugv.html

case "$1" in
来源：http://dali.zhiwuduotai.top/Article/details/gtqccktvcm.html

start) echo "启动" ;;
来源：http://dali.zycfv.cn/Article/details/gtnyacagin.html

stop)  echo "停止" ;;
来源：http://dali.cucudq.cn/Article/details/gtcfilovol.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gtoimedgjn.html

esac
来源：http://dali.snrcjt.cn/Article/details/gthultjzdu.html

[R12] for 遍历文件
来源：http://dali.c1oappe.top/Article/details/gtxkujdhhl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.vqdsnc.cn/Article/details/gtvknsdsxd.html

[R13] for 计数循环
来源：http://dali.zdqjudy.top/Article/details/gttnjrynjp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gtcxurtegf.html

[R14] C 风格 for
来源：http://dali.hfpthk.cn/Article/details/gtukdgsyrg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gtaabtdhbv.html

[R15] while 逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gtyhlmnyok.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenlongwang.top/Article/details/gtuwomcqbt.html

[R16] until 等待条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpdsakyd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gtqdmjfaic.html

[R17] 数组定义与取值
来源：http://dali.tian-w.cn/Article/details/gtopjbezni.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pycfn.com/Article/details/gtbjzjzcaf.html

[R18] 遍历数组
来源：http://dali.ivvv.top/Article/details/gtggkqamzg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jiagoushi.top/Article/details/gtlqmhinpg.html

[R19] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gteglygjxk.html

echo "${#arr[@]}"
来源：http://dali.zycfv.cn/Article/details/gtidbxpqqd.html

[R20] 关联数组（字典）
来源：http://dali.zdqjudy.top/Article/details/gtmoibjnaf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzyuuuml.html

[R21] 字符串长度
来源：http://dali.jyoumei.cn/Article/details/gtyhusgxhn.html

echo "${#s}"
来源：http://dali.yj202588.top/Article/details/gtpzxploea.html

[R22] 截取子串
来源：http://dali.chenlongwang.top/Article/details/gtgjqmmjbc.html

echo "${s:0:5}"
来源：http://dali.svipenyu.cn/Article/details/gtupjobzzo.html

[R23] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gtpnparuxl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jlsjyb.cn/Article/details/gtllxmncdz.html

[R24] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gtmquhdyob.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ivvv.top/Article/details/gtmltkwxor.html

[R25] 去后缀 / 去前缀
来源：http://dali.shanyushiyangkeji.top/Article/details/gtioxiwiqh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yangfankeji.com/Article/details/gtgysxdkdi.html

[R26] 命令替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsynhdzfs.html

now=$(date +%F); echo "$now"
来源：http://dali.pycfn.com/Article/details/gticzmmvso.html

[R27] 算术展开
来源：http://dali.cashguo.top/Article/details/gtgzefhqkh.html

echo $((1 + 2 * 3))
来源：http://dali.yuanzhike.top/Article/details/gtyrpwqwyf.html

[R28] 浮点运算
来源：http://dali.gzhubu.top/Article/details/gttwynlasv.html

echo "scale=2; 10/3" | bc
来源：http://dali.kuanghao11.cn/Article/details/gtaiuqarnp.html

[R29] 定义函数
来源：http://dali.ivvv.top/Article/details/gtoznytptg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtblllswed.html

[R30] 函数返回状态码
来源：http://dali.ydzc1.top/Article/details/gtjqqncbes.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ydzc1.top/Article/details/gtjjdawlqw.html

[R31] 局部变量
来源：http://dali.yuanzhike.top/Article/details/gtyzoiooqx.html

f() { local x=1; echo "$x"; }
来源：http://dali.hysaishi.cn/Article/details/gtldbubzik.html

[R32] 参数个数校验
来源：http://dali.pengpengdd.cyou/Article/details/gtckhvqvxc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.havefunace.top/Article/details/gteucwypic.html

[R33] 捕获错误并提示行号
来源：http://dali.gogol.net.cn/Article/details/gtnivadsof.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.pycfn.com/Article/details/gttfkgxiaa.html

[R34] 退出时清理
来源：http://dali.hfpthk.cn/Article/details/gtopoiabme.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gtqiwkmbub.html

[R35] 后台执行并等待
来源：http://dali.ybcxt.top/Article/details/gtigtdmaov.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.haohaochexian.top/Article/details/gtmdzivmzv.html

[R36] 并发执行多个任务
来源：http://dali.redwolf501.top/Article/details/gtohcvjsco.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jlsjyb.cn/Article/details/gtejxqqryv.html

[R37] 把输出赋给变量
来源：http://dali.ydzc1.top/Article/details/gtbymrajku.html

files=$(ls -1)
来源：http://dali.cucudq.cn/Article/details/gtfuzaildg.html

[R38] 管道串联
来源：http://dali.hnqzz.top/Article/details/gtzaolwlbb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cqqwz.cn/Article/details/gtcpkeaabt.html

[R39] 重定向标准输出与错误
来源：http://dali.fzhhl.top/Article/details/gteqjssvnu.html

cmd > out.log 2>&1
来源：http://dali.nwbrower.top/Article/details/gtmlgnxbcm.html

[R40] 追加写日志
来源：http://dali.xinyue.icu/Article/details/gtbjruqmjz.html

echo "log" >> out.log
来源：http://dali.cheryme.top/Article/details/gtpykgnnhc.html

[R41] 丢弃输出
来源：http://dali.sxryk.cn/Article/details/gtxpzenyov.html

cmd >/dev/null 2>&1
来源：http://dali.ppjwa.cn/Article/details/gtkqllzhmo.html

[R42] 输入重定向
来源：http://dali.sysykeji.top/Article/details/gtbajatydt.html

wc -l < a.txt
来源：http://dali.hywenlv.cn/Article/details/gtoxatipdy.html

[R43] 按名字查找文件
来源：http://dali.shuidangran.top/Article/details/gtlchhkoph.html

find . -name "*.log" -type f
来源：http://dali.shangyingyoupin.top/Article/details/gtygavhpcx.html

[R44] 按修改时间查找
来源：http://dali.fengsongda.top/Article/details/gtgaufqajp.html

find . -mtime -7 -type f
来源：http://dali.kuanghao11.cn/Article/details/gtzrsegkuo.html

[R45] 批量删除
来源：http://dali.haohaochexian.top/Article/details/gtrbouhega.html

find . -name "*.tmp" -delete
来源：http://dali.sxryk.cn/Article/details/gtnyhdrira.html

[R46] 递归替换文件内容
来源：http://dali.mhx1999.top/Article/details/gtxfaabzwe.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yongpay.top/Article/details/gtavsbymew.html

[R47] sed 单行替换
来源：http://dali.cdnleiting.top/Article/details/gtiqxwlmxi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dianchejie.cn/Article/details/gtiimlaook.html

[R48] awk 取指定列
来源：http://dali.dianchejie.cn/Article/details/gtomwawjzb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtgwhaxago.html

[R49] awk 带条件
来源：http://dali.feifeiyinyue.top/Article/details/gtaurnhxmp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xziqi.cn/Article/details/gtelwbykzg.html

[R50] awk 求和
来源：http://dali.feifeiyinyue.top/Article/details/gtnkevnedh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ybcxt.top/Article/details/gtgyigkjft.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gtffxrujaq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxuanxn.top/Article/details/gtbbosumxh.html

[R52] 统计行数
来源：http://dali.dianchejie.cn/Article/details/gtdzcmiecf.html

wc -l a.txt
来源：http://dali.daxiang520.top/Article/details/gtcpwnrqhe.html

[R53] 查看文件头与实时尾
来源：http://dali.iojbl.cn/Article/details/gtmcpvtdxx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xylfe.cn/Article/details/gtsothgvwn.html

[R54] 比较两个文件
来源：http://dali.yangfankeji.com/Article/details/gtzixhnyaj.html

diff a.txt b.txt
来源：http://dali.chenjidiqi.icu/Article/details/gttcwiddjc.html

[R55] 压缩与解压
来源：http://dali.jinqigfzy.top/Article/details/gtejlbsomp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nwbrower.top/Article/details/gtorbdayru.html

[R56] 远程拷贝
来源：http://dali.xinyue.icu/Article/details/gtuntclcnu.html

scp file user@host:/path/
来源：http://dali.sxryk.cn/Article/details/gtxnpngiil.html

[R57] 远程执行命令
来源：http://dali.jinghuilouyu.cn/Article/details/gtiqndkouc.html

ssh user@host 'uptime'
来源：http://dali.zdqjudy.top/Article/details/gtkamnasxd.html

[R58] 下载文件
来源：http://dali.hnxiangtu.top/Article/details/gtktqsngcr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.fzhhl.top/Article/details/gtzqttrrdk.html

[R59] 发 POST JSON
来源：http://dali.daria6918.cn/Article/details/gtvwflvhul.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tian-w.cn/Article/details/gteqafnpkx.html

[R60] 只看 HTTP 状态码
来源：http://dali.cqqwz.cn/Article/details/gtfogisffp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.0kj1m.cn/Article/details/gtalirbual.html

[R61] 磁盘占用
来源：http://dali.cashguo.top/Article/details/gtbnyubtsw.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gtzwupjzvw.html

[R62] 找最占空间的文件
来源：http://dali.c1oappe.top/Article/details/gtnskvzupg.html

du -ah . | sort -rh | head -10
来源：http://dali.jinghuilouyu.cn/Article/details/gtpotnzghx.html

[R63] 内存与进程
来源：http://dali.ydzc1.top/Article/details/gtiyvhmics.html

free -h;  ps aux | grep nginx
来源：http://dali.zhiwuduotai.top/Article/details/gtjicbgugj.html

[R64] 结束进程
来源：http://dali.kuanghao11.cn/Article/details/gtgeztxeqf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yonumen.top/Article/details/gtljilypzy.html

[R65] 查看端口占用
来源：http://dali.chenlongwang.top/Article/details/gtdyahfvve.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nwbrower.top/Article/details/gtkviibwcx.html

[R66] 定时任务
来源：http://dali.zhengqikj.top/Article/details/gtlcodgieu.html

crontab -e;  crontab -l
来源：http://dali.hywenlv.cn/Article/details/gtdltybuuc.html

[R67] 生成随机十六进制串
来源：http://dali.zhongyouzk.top/Article/details/gtymxdynce.html

openssl rand -hex 16
来源：http://dali.meibo888.top/Article/details/gtizrifdfz.html

[R68] 计算文件校验值
来源：http://dali.shangyingyoupin.top/Article/details/gtteopxuka.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cqqwz.cn/Article/details/gtymulqbgs.html

[R69] 生成随机密码
来源：http://dali.yanxiufei.cn/Article/details/gtwodkspwn.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfynzpqo.html

[R70] 时间戳与互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiutdxbfq.html

date +%s;  date -d @1700000000
来源：http://dali.jqgfzy.top/Article/details/gtqzmpspza.html

[R71] 日期格式化
来源：http://dali.aibaodan.cn/Article/details/gtwhsbnhru.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnqzz.top/Article/details/gtoviimdgk.html

[R72] 等待端口就绪
来源：http://dali.guowangkeji.top/Article/details/gtgouomcnq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj202588.top/Article/details/gtsqyombss.html

[R73] 分割大日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtpwmpkjya.html


<!-- 参考信息 -->