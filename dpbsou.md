代发 wailian999

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pengpengdd.cyou/Article/details/gtfbewptml.html

[Q20] IN 列表
来源：http://dali.xuetiantiany.cn/Article/details/gtzkphtifo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gtvkpxdjgc.html

[Q21] 空值判断
来源：http://dali.feifeiyinyue.top/Article/details/gtswddvxeg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yuxming.cn/Article/details/gtivwueavk.html

[Q22] 排序
来源：http://dali.xziqi.cn/Article/details/gtubiykrhe.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.redwolf501.top/Article/details/gtowuaueyg.html

[Q23] 分页
来源：http://dali.jiagoushi.top/Article/details/gtibpqmmly.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.guowangkeji.top/Article/details/gtppbvpant.html

[Q24] 去重
来源：http://dali.xuanzx.com/Article/details/gttvqoawwj.html

SELECT DISTINCT city FROM users;
来源：http://dali.ivvv.top/Article/details/gtuayxugmb.html

[Q25] 只取前 N 条
来源：http://dali.aibaodan.cn/Article/details/gtjwqhioqa.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nanxinkj.top/Article/details/gtfzpjmquc.html

[Q26] 计数
来源：http://dali.yj20258.top/Article/details/gtsvgjqsdt.html

SELECT COUNT(*) FROM users;
来源：http://dali.xylfe.cn/Article/details/gthvurrass.html

[Q27] 条件计数
来源：http://dali.hammf.cn/Article/details/gterfwgbay.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtrsklycvf.html

[Q28] 求和与平均
来源：http://dali.redwolf501.top/Article/details/gttuttfony.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtfooinycp.html

[Q29] 最大最小值
来源：http://dali.jianghu66.top/Article/details/gtomxgshde.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtallgsvcs.html

[Q30] 分组统计
来源：http://dali.zhixingplan.top/Article/details/gtateqnghi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtrrrnwmwx.html

[Q31] 分组后过滤
来源：http://dali.guowangkeji.top/Article/details/gttebzdgji.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nwbrower.top/Article/details/gtbywlqruh.html

[Q32] 分组拼接字符串
来源：http://dali.cashguo.top/Article/details/gteghkrgvx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gttwrlqlum.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sxryk.cn/Article/details/gtpchbeefb.html

[Q33] 多列分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkymeuclq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenjidiqi.icu/Article/details/gtiqonebyi.html

[Q34] 每组取第一条
来源：http://dali.zycfv.cn/Article/details/gtectqhcaz.html

SELECT * FROM (
来源：http://dali.xuanzx.com/Article/details/gtfjankpvs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.quarkkingdee.top/Article/details/gtfnnuqtju.html

) t WHERE rn = 1;
来源：http://dali.havefunace.top/Article/details/gtcktbphgz.html

[Q35] 内连接
来源：http://dali.daxiang520.top/Article/details/gtzwvdwuxt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258.top/Article/details/gtdcckmivi.html

[Q36] 左连接
来源：http://dali.hammf.cn/Article/details/gtzwxuvatj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cqqwz.cn/Article/details/gtxqzbrmzr.html

[Q37] 右连接
来源：http://dali.aibaodan.cn/Article/details/gtwamwspvy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gtnsylulhx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.birdmap.top/Article/details/gtxgashuun.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cqqwz.cn/Article/details/gtffbidjbr.html

[Q39] 自连接（查上下级）
来源：http://dali.gaohongyu789.top/Article/details/gtputfyxbv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cucudq.cn/Article/details/gtxmagoboz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnqzz.top/Article/details/gtdrlsstoa.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.meibo888.top/Article/details/gtsdudnpvm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhixingplan.top/Article/details/gtllvzzbwn.html

[Q41] 多表连接
来源：http://dali.0kj1m.cn/Article/details/gtpkoqlhnf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shzxlz.cn/Article/details/gtbkwapnjn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fengsongda.top/Article/details/gtpwilhwuh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhoulong.xyz/Article/details/gtksurgvpg.html

[Q42] 连接条件附加过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnuntfmwl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.snrcjt.cn/Article/details/gtkthtzxss.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.andypj.xyz/Article/details/gtljppfvwy.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gtgfypbwzn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ywan-chungtsiang.top/Article/details/gthavfbhfh.html

[Q44] IN 子查询
来源：http://dali.dashuyun.cn/Article/details/gtlmaoingw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsffstgrg.html

[Q45] EXISTS 判断存在
来源：http://dali.hnxiangtu.top/Article/details/gtbfifxeud.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigufen.top/Article/details/gtggkxisks.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zycfv.cn/Article/details/gtndsczqfz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkhkyqhp.html

[Q47] 与平均值比较
来源：http://dali.nanxuanxn.top/Article/details/gttuefmsei.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhixingplan.top/Article/details/gtkczyeeyp.html

[Q48] CTE 公用表表达式
来源：http://dali.hammf.cn/Article/details/gtfsoegxfs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.316326.xyz/Article/details/gtcfftkydm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yuxming.cn/Article/details/gttlatvcrs.html

[Q49] 更新单行
来源：http://dali.jinqigufen.top/Article/details/gtyaeqdfww.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenzaomai.com/Article/details/gtfgftpjwq.html

[Q50] 批量更新
来源：http://dali.ehwqpu.com/Article/details/gtogskdzig.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gtmbrjdvje.html

[Q51] 用子查询更新
来源：http://dali.havefunace.top/Article/details/gtfgwsydjk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.aizwys.cn/Article/details/gtzssvzviq.html

[Q52] 删除指定行
来源：http://dali.jianghu66.top/Article/details/gtucjbxxxz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gttliqbvwi.html

[Q53] 按条件删除
来源：http://dali.jqgfzy.top/Article/details/gtremwcrgf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jqgfzy.top/Article/details/gthhpyawba.html

[Q54] 清空表
来源：http://dali.c1oappe.top/Article/details/gtfeoutbcx.html

TRUNCATE TABLE logs;
来源：http://dali.xinyue.icu/Article/details/gtebpyydfh.html

[Q55] 排名（并列占位）
来源：http://dali.zhongyouzk.top/Article/details/gtccvdbtvf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gtbcdwwqyj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinghuilouyu.cn/Article/details/gtyteexchj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.birdmap.top/Article/details/gtdkzgbaau.html

[Q57] 行号
来源：http://dali.pycfn.com/Article/details/gtbhhzsryv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258.top/Article/details/gtumjjxxjn.html

[Q58] 累计求和
来源：http://dali.316326.xyz/Article/details/gtwildeney.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtekoatbbh.html

[Q59] 分组内累计
来源：http://dali.shzxlz.cn/Article/details/gtcxgawoph.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.meibo888.top/Article/details/gtzeqxjhux.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigfzy.top/Article/details/gtzskzujvk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.iojbl.cn/Article/details/gtlyjxtywv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtvewlufms.html

[Q61] 移动平均
来源：http://dali.gaohongyu789.top/Article/details/gtdnvjtkxx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtdxncyaae.html

[Q62] 分组占比
来源：http://dali.pengpengdd.cyou/Article/details/gtquiekeol.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gtuyasvezc.html

[Q63] 开启事务
来源：http://dali.c1oappe.top/Article/details/gtfqosawaz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjtxuesxu.html

[Q64] 提交事务
来源：http://dali.vqdsnc.cn/Article/details/gtuljxsqmk.html

COMMIT;
来源：http://dali.feifeiyinyue.top/Article/details/gtmtfomebw.html

[Q65] 回滚事务
来源：http://dali.yangfankeji.com/Article/details/gthtuizsxq.html

ROLLBACK;
来源：http://dali.hongshengwenyu.top/Article/details/gtwnaldapx.html

[Q66] 行锁查询
来源：http://dali.ppjwa.cn/Article/details/gteytrhwck.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.0kj1m.cn/Article/details/gtvjiuqaje.html

[Q67] 设置隔离级别
来源：http://dali.zhongyouzk.top/Article/details/gtggiggfbr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jiagoushi.top/Article/details/gtvmjbuvof.html

[Q68] 保存点
来源：http://dali.wangshuangyany.cn/Article/details/gtaqosxdaa.html

SAVEPOINT sp1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjchkciw.html

ROLLBACK TO sp1;
来源：http://dali.svipenyu.cn/Article/details/gtwtobfaua.html

[Q69] 查看执行计划
来源：http://dali.jinghuilouyu.cn/Article/details/gtniavskna.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cqqwz.cn/Article/details/gtnnynzpdi.html

[Q70] 更新统计信息
来源：http://dali.cheryme.top/Article/details/gtwizjorvm.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gtjxusbsrs.html

[Q71] 查看建表语句
来源：http://dali.havefunace.top/Article/details/gtyosanuhb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jianghu66.top/Article/details/gtkdfcgvjk.html

[Q72] 查看索引
来源：http://dali.gogol.net.cn/Article/details/gtsllgofqp.html

SHOW INDEX FROM users;
来源：http://dali.havefunace.top/Article/details/gtqbrmvscr.html

[Q73] 查看表状态
来源：http://dali.bjfxy.top/Article/details/gtcrbfzcbg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenjidiqi.icu/Article/details/gtqcughjim.html

[Q74] 强制使用索引
来源：http://dali.fzhhl.top/Article/details/gtondnyuiy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ehwqpu.com/Article/details/gtokurjwtt.html

[Q75] 日期格式化
来源：http://dali.aizwys.cn/Article/details/gtkmsaunpw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtudvkvjol.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.smart0.xyz/Article/details/gtajzuebbs.html

[Q76] 按天统计
来源：http://dali.nwbrower.top/Article/details/gtdftertma.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xuetiantiany.cn/Article/details/gtouotxoja.html

[Q77] 时间加减
来源：http://dali.yonumen.top/Article/details/gtkhmcbzjx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.haohaochexian.top/Article/details/gttrguiias.html

[Q78] 当前时间
来源：http://dali.jqgfzy.top/Article/details/gtfgmrrrtz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shuidangran.top/Article/details/gtrbtkngyz.html

[Q79] 字符串拼接
来源：http://dali.daria6918.cn/Article/details/gtiviakbss.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gotoacloud.top/Article/details/gtbktgcfra.html

[Q80] 字符串截取
来源：http://dali.nwbrower.top/Article/details/gthcftvafo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtiivreobh.html

[Q81] 字符串替换
来源：http://dali.yj202588.top/Article/details/gthrpfdatd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtargrkrwe.html

[Q82] 字符长度与字节长度
来源：http://dali.zdqjudy.top/Article/details/gtyosjunli.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sweek.top/Article/details/gtsnyrlycb.html

[Q83] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gtehqgabom.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gthdeyoxnd.html

[Q84] 去除首尾空格
来源：http://dali.ydzc1.top/Article/details/gttpbdudyg.html

SELECT TRIM(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtolualbpq.html

[Q85] 数值取整
来源：http://dali.xziqi.cn/Article/details/gtrhnysdkj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxdtgqxb.html

[Q86] 读取 JSON 字段
来源：http://dali.gotoacloud.top/Article/details/gtgdbjsmtu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jiagoushi.top/Article/details/gtsglrywnb.html

[Q87] JSON 字段做条件
来源：http://dali.gogol.net.cn/Article/details/gtdnbzwilx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daria6918.cn/Article/details/gtpsayvpff.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhongyouzk.top/Article/details/gtvahuurmt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.quarkkingdee.top/Article/details/gtnqnabmce.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yongpay.top/Article/details/gtcaeokkyn.html

[Q89] 判断表是否存在
来源：http://dali.9152youxi.cn/Article/details/gtaonryqym.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhoulong.xyz/Article/details/gtcmczabyw.html

[Q90] 生成序号列
来源：http://dali.mhx1999.top/Article/details/gtbseyczzf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.snrcjt.cn/Article/details/gtnngoeeob.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtdsssdolm.html

R. Bash 专题
来源：http://dali.ybcxt.top/Article/details/gtxdcshgms.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtrmeqwejv.html

[R01] shebang 与严格模式
来源：http://dali.gaohongyu789.top/Article/details/gttdsmebym.html

#!/usr/bin/env bash
来源：http://dali.shanyushiyangtech.top/Article/details/gttkkknuth.html

set -euo pipefail
来源：http://dali.0kj1m.cn/Article/details/gthqhpzzeb.html

[R02] 变量赋值与使用
来源：http://dali.jqgufenzy.top/Article/details/gtyqqhscry.html

name="Tom"; echo "$name"
来源：http://dali.hfpthk.cn/Article/details/gtbjiljmad.html

[R03] 只读变量
来源：http://dali.jianghu66.top/Article/details/gtxgwzdksq.html

readonly PI=3.14
来源：http://dali.haohaochexian.top/Article/details/gtkpcdqqnj.html

[R04] 位置参数
来源：http://dali.ppjwa.cn/Article/details/gtitsxtaqz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhongyouzk.top/Article/details/gtqlumdmax.html

[R05] 参数默认值
来源：http://dali.guannengcc.top/Article/details/gtetsrldxi.html

name="${1:-default}"
来源：http://dali.chenjidiqi.icu/Article/details/gtagqvojxv.html

[R06] 判断命令是否存在
来源：http://dali.chenzaomai.com/Article/details/gtfqjeikiu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.fzhhl.top/Article/details/gtacgvpexx.html

[R07] if 判断文件
来源：http://dali.hnqzz.top/Article/details/gtnazvlgdi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.mhx1999.top/Article/details/gtjgqbauqg.html

[R08] 数值比较
来源：http://dali.chenlongwang.top/Article/details/gtilgcjbow.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtivnmbzgq.html

[R09] 字符串比较
来源：http://dali.ivvv.top/Article/details/gtqvbnmusx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtpapamoon.html

[R10] 正则匹配
来源：http://dali.yj20258888.top/Article/details/gtxcvznlzt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jyoumei.cn/Article/details/gtgwcfhfpx.html

[R11] case 多分支
来源：http://dali.jyoumei.cn/Article/details/gtlzeshjqp.html

case "$1" in
来源：http://dali.shuidangran.top/Article/details/gtipxlpxcv.html

start) echo "启动" ;;
来源：http://dali.tianlin.xyz/Article/details/gtwujnntfo.html

stop)  echo "停止" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtenzmcgnn.html

*)     echo "未知命令" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtuhfuzacn.html

esac
来源：http://dali.havefunace.top/Article/details/gtedrcxkrq.html

[R12] for 遍历文件
来源：http://dali.yj20258888.top/Article/details/gtrbuhfaqr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.andypj.xyz/Article/details/gtuymntgrj.html

[R13] for 计数循环
来源：http://dali.xylfe.cn/Article/details/gtohcxisoi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gtxvgriqnn.html

[R14] C 风格 for
来源：http://dali.ydzc1.top/Article/details/gtvodbxtkf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cdnleiting.top/Article/details/gtencjwczh.html

[R15] while 逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtwpxkgksw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jqgfzy.top/Article/details/gtbedqtobx.html

[R16] until 等待条件
来源：http://dali.nanxuanxn.top/Article/details/gtqeowtfyd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadiqbtsn.html

[R17] 数组定义与取值
来源：http://dali.jqgfzy.top/Article/details/gtwzpbphnu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nwbrower.top/Article/details/gtwvqacpkz.html

[R18] 遍历数组
来源：http://dali.nanxuanxn.top/Article/details/gtadmfyvgi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gzhubu.top/Article/details/gtjskowrel.html

[R19] 数组长度
来源：http://dali.redwolf501.top/Article/details/gtqcjmdwhp.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgasbuyd.html

[R20] 关联数组（字典）
来源：http://dali.jqgufenzy.top/Article/details/gtietuuhel.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenzaomai.com/Article/details/gtckikuwoo.html

[R21] 字符串长度
来源：http://dali.cucudq.cn/Article/details/gtwtlnjncf.html

echo "${#s}"
来源：http://dali.hnxiangtu.top/Article/details/gtmhipirqx.html

[R22] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gtfofmoxof.html

echo "${s:0:5}"
来源：http://dali.chenzaomai.com/Article/details/gtnrpnyyrx.html

[R23] 字符串替换
来源：http://dali.jlsjyb.cn/Article/details/gtmzimbfex.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.guannengcc.top/Article/details/gtvovedbur.html

[R24] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gtifxiduqf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shzxlz.cn/Article/details/gtzvjfwaoh.html

[R25] 去后缀 / 去前缀
来源：http://dali.guannengcc.top/Article/details/gtakqlejeb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aibaodan.cn/Article/details/gtjdwdsrij.html

[R26] 命令替换
来源：http://dali.zhoulong.xyz/Article/details/gtjvnxyzut.html

now=$(date +%F); echo "$now"
来源：http://dali.gogol.net.cn/Article/details/gtpfbimqtz.html

[R27] 算术展开
来源：http://dali.yanxiufei.cn/Article/details/gtihzknapu.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaiolvixh.html

[R28] 浮点运算
来源：http://dali.kuanghao11.cn/Article/details/gtvummthkh.html

echo "scale=2; 10/3" | bc
来源：http://dali.shangyingyoupin.top/Article/details/gtyujhkcqs.html

[R29] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gtezkiwagf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hysaishi.cn/Article/details/gtzbdqsqyg.html

[R30] 函数返回状态码
来源：http://dali.cashguo.top/Article/details/gtfulyusjt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.bjfxy.top/Article/details/gtpenbpina.html

[R31] 局部变量
来源：http://dali.jinqigufen.top/Article/details/gtctegzeaf.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258.top/Article/details/gtxfjwrbqw.html

[R32] 参数个数校验
来源：http://dali.snrcjt.cn/Article/details/gttkkfjevn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shuidangran.top/Article/details/gtsqldeutl.html

[R33] 捕获错误并提示行号
来源：http://dali.xinyue.icu/Article/details/gtlmhewadj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ydzc1.top/Article/details/gtukmzmbpj.html

[R34] 退出时清理
来源：http://dali.kuanghao11.cn/Article/details/gtxyoplwsj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gtttyrrtbx.html

[R35] 后台执行并等待
来源：http://dali.cheryme.top/Article/details/gtrwmwzvhf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnqzz.top/Article/details/gtwbsxlaci.html

[R36] 并发执行多个任务
来源：http://dali.cashguo.top/Article/details/gtldmeaoxh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gtfimlfcvg.html

[R37] 把输出赋给变量
来源：http://dali.xziqi.cn/Article/details/gtxpnwjmsp.html

files=$(ls -1)
来源：http://dali.daxiang520.top/Article/details/gtmbidpjpr.html

[R38] 管道串联
来源：http://dali.aibaodan.cn/Article/details/gtxxklkdkw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ybcxt.top/Article/details/gtsojiqffv.html

[R39] 重定向标准输出与错误
来源：http://dali.zhengqikj.top/Article/details/gtsnvauzck.html

cmd > out.log 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gtjpaihgua.html

[R40] 追加写日志
来源：http://dali.redwolf501.top/Article/details/gtbiwzbguv.html

echo "log" >> out.log
来源：http://dali.redwolf501.top/Article/details/gtctxxsvda.html

[R41] 丢弃输出
来源：http://dali.gogol.net.cn/Article/details/gtaamqhiio.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigufen.top/Article/details/gtvhhvaraa.html

[R42] 输入重定向
来源：http://dali.316326.xyz/Article/details/gtqewzxnmw.html

wc -l < a.txt
来源：http://dali.nwbrower.top/Article/details/gtcrxfjwyg.html

[R43] 按名字查找文件
来源：http://dali.svipenyu.cn/Article/details/gtgvdzybto.html

find . -name "*.log" -type f
来源：http://dali.zhengqikj.top/Article/details/gtnhyuapfr.html

[R44] 按修改时间查找
来源：http://dali.ehwqpu.com/Article/details/gtynkwttiy.html

find . -mtime -7 -type f
来源：http://dali.wangdashe.top/Article/details/gtaldjlfbh.html

[R45] 批量删除
来源：http://dali.shzxlz.cn/Article/details/gttmxhagad.html

find . -name "*.tmp" -delete
来源：http://dali.cucudq.cn/Article/details/gtenxtjsmf.html

[R46] 递归替换文件内容
来源：http://dali.aibaodan.cn/Article/details/gtvdttmgru.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dianchejie.cn/Article/details/gtzalyjyrl.html

[R47] sed 单行替换
来源：http://dali.gotoacloud.top/Article/details/gtzwjiyuli.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtzxhocpih.html

[R48] awk 取指定列
来源：http://dali.cashguo.top/Article/details/gtyhmurscr.html

awk '{print $1, $3}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gtrqepcojn.html

[R49] awk 带条件
来源：http://dali.hongshengwenyu.top/Article/details/gtacqbrgvk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yuxming.cn/Article/details/gttpelimuz.html

[R50] awk 求和
来源：http://dali.haohaochexian.top/Article/details/gtnamrgsex.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daxiang520.top/Article/details/gtjnavhtuv.html

[R51] 排序去重取前几
来源：http://dali.yj202588.top/Article/details/gtzsfvzqry.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.haohaochexian.top/Article/details/gtrjewehlz.html

[R52] 统计行数
来源：http://dali.zhiwuduotai.top/Article/details/gtlmtsvqsu.html

wc -l a.txt
来源：http://dali.guowangkeji.top/Article/details/gtalfkiilj.html

[R53] 查看文件头与实时尾
来源：http://dali.iojbl.cn/Article/details/gtlkcddvjk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigufen.top/Article/details/gtbnhwfopp.html

[R54] 比较两个文件
来源：http://dali.fengsongda.top/Article/details/gtpoopxbdf.html

diff a.txt b.txt
来源：http://dali.0kj1m.cn/Article/details/gtcsxjncuv.html

[R55] 压缩与解压
来源：http://dali.jlsjyb.cn/Article/details/gtpfdnjtop.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aizwys.cn/Article/details/gtnsxsuopl.html

[R56] 远程拷贝
来源：http://dali.zdqjudy.top/Article/details/gtqnuikhrs.html

scp file user@host:/path/
来源：http://dali.gogol.net.cn/Article/details/gtmbwiwgev.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gtnhahmeys.html

ssh user@host 'uptime'
来源：http://dali.yanxiufei.cn/Article/details/gttbjhcoqh.html

[R58] 下载文件
来源：http://dali.0kj1m.cn/Article/details/gtvlasxcbb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shanyushiyangtech.top/Article/details/gtqnxclaar.html

[R59] 发 POST JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtxkdhgubw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nanxuanxn.top/Article/details/gtvbntkqyc.html

[R60] 只看 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gtzzkrsxiv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.mhx1999.top/Article/details/gtrvmxemhq.html

[R61] 磁盘占用
来源：http://dali.jinqigufen.top/Article/details/gtsshmjaba.html

df -h;  du -sh *
来源：http://dali.zhongyouzk.top/Article/details/gtdwmobskc.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtagnsriij.html

du -ah . | sort -rh | head -10
来源：http://dali.sufxvd.cn/Article/details/gtifkjbbtr.html

[R63] 内存与进程
来源：http://dali.chenjidiqi.icu/Article/details/gtkwvqohst.html

free -h;  ps aux | grep nginx
来源：http://dali.shangyingyoupin.top/Article/details/gtsjuuuefy.html

[R64] 结束进程
来源：http://dali.tian-w.cn/Article/details/gtdhknmxcj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yueranfly.top/Article/details/gtmxtqpbwc.html

[R65] 查看端口占用
来源：http://dali.yj202588.top/Article/details/gtkoojsjfp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.9152youxi.cn/Article/details/gtslzlffms.html

[R66] 定时任务
来源：http://dali.cucudq.cn/Article/details/gtcusmkpan.html

crontab -e;  crontab -l
来源：http://dali.andypj.xyz/Article/details/gtvyuhyoqf.html

[R67] 生成随机十六进制串
来源：http://dali.xylfe.cn/Article/details/gtguldlmsc.html

openssl rand -hex 16
来源：http://dali.9152youxi.cn/Article/details/gtarijmgit.html

[R68] 计算文件校验值
来源：http://dali.ivvv.top/Article/details/gtgklpeztm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aizwys.cn/Article/details/gtwcxgjsjm.html

[R69] 生成随机密码
来源：http://dali.feifeiyinyue.top/Article/details/gtddixmhaj.html


<!-- 参考信息 -->