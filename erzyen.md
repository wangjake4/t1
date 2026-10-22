代发 wailian999

[Q33] 多列分组
来源：http://dali.fzhhl.top/Article/details/gtjuhahgep.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.c1oappe.top/Article/details/gtxkqmcokn.html

[Q34] 每组取第一条
来源：http://dali.dianchejie.cn/Article/details/gtlkfunzzc.html

SELECT * FROM (
来源：http://dali.yuxming.cn/Article/details/gtuevqfacu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aizwys.cn/Article/details/gthqjzsasv.html

) t WHERE rn = 1;
来源：http://dali.gogol.net.cn/Article/details/gtxkijxlme.html

[Q35] 内连接
来源：http://dali.mhx1999.top/Article/details/gtuuhbybsq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yonumen.top/Article/details/gtpeyaubzd.html

[Q36] 左连接
来源：http://dali.ivvv.top/Article/details/gtpfnoxlyl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.guannengcc.top/Article/details/gttenabwfj.html

[Q37] 右连接
来源：http://dali.xuetiantiany.cn/Article/details/gtghweznva.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ydzc1.top/Article/details/gttfxzwwav.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj202588.top/Article/details/gtxrdqonul.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvsutiqpk.html

[Q39] 自连接（查上下级）
来源：http://dali.sxryk.cn/Article/details/gthpjoszmv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.9152youxi.cn/Article/details/gtcilqyaag.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnxiangtu.top/Article/details/gtmdzwsxfb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenlongwang.top/Article/details/gtoihkonhk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangdashe.top/Article/details/gtwfbcfkfm.html

[Q41] 多表连接
来源：http://dali.zdqjudy.top/Article/details/gtedofvaqe.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.snrcjt.cn/Article/details/gtzlpuidmt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhiwuduotai.top/Article/details/gtdsffghry.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhixingplan.top/Article/details/gtrrkxriwy.html

[Q42] 连接条件附加过滤
来源：http://dali.guannengcc.top/Article/details/gtvuzdakmy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jqgufenzy.top/Article/details/gtrbebxhgv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenlongwang.top/Article/details/gtoaoawnht.html

[Q43] 标量子查询
来源：http://dali.hammf.cn/Article/details/gtrlkwvygq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.iojbl.cn/Article/details/gtccnowpgy.html

[Q44] IN 子查询
来源：http://dali.tian-w.cn/Article/details/gtvlcuoyte.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhiwuduotai.top/Article/details/gtmnjndrds.html

[Q45] EXISTS 判断存在
来源：http://dali.sxryk.cn/Article/details/gtymuwdurs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yueranfly.top/Article/details/gtzftjnqcc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ydzc1.top/Article/details/gtmkhbqsxu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.kuanghao11.cn/Article/details/gtetzxirbv.html

[Q47] 与平均值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpusqactd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenjidiqi.icu/Article/details/gtityjwsvq.html

[Q48] CTE 公用表表达式
来源：http://dali.guannengcc.top/Article/details/gthkjxemmk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shzxlz.cn/Article/details/gtjvvejzjl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.daxiang520.top/Article/details/gtthuljjii.html

[Q49] 更新单行
来源：http://dali.cheryme.top/Article/details/gtnwcrkbky.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cqqwz.cn/Article/details/gtihfjnknx.html

[Q50] 批量更新
来源：http://dali.yongpay.top/Article/details/gtpwpbakzx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.0kj1m.cn/Article/details/gtykhovufr.html

[Q51] 用子查询更新
来源：http://dali.yueranfly.top/Article/details/gtzdwyelaz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtrtjnomzi.html

[Q52] 删除指定行
来源：http://dali.jyoumei.cn/Article/details/gtoktowfne.html

DELETE FROM users WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gtxngizaez.html

[Q53] 按条件删除
来源：http://dali.xylfe.cn/Article/details/gteooiclbu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pengpengdd.cyou/Article/details/gtxjwzlkev.html

[Q54] 清空表
来源：http://dali.ivvv.top/Article/details/gtcuymumbt.html

TRUNCATE TABLE logs;
来源：http://dali.yanxiufei.cn/Article/details/gthnpwhntw.html

[Q55] 排名（并列占位）
来源：http://dali.meibo888.top/Article/details/gtgzfvbxiv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ehwqpu.com/Article/details/gtucvusyxg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.snrcjt.cn/Article/details/gtgipuwngd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aizwys.cn/Article/details/gtyfuomnaq.html

[Q57] 行号
来源：http://dali.dashuyun.cn/Article/details/gtnbcreurs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtxaovenud.html

[Q58] 累计求和
来源：http://dali.guannengcc.top/Article/details/gtnvtrefvy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tanke756.top/Article/details/gtnexxldzf.html

[Q59] 分组内累计
来源：http://dali.zdqjudy.top/Article/details/gtnovrcnoc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtpwsnfxhz.html

[Q60] 取上一行 / 下一行
来源：http://dali.pycfn.com/Article/details/gtodvnxddu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xinyue.icu/Article/details/gthjdkqxct.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtfvwpeayr.html

[Q61] 移动平均
来源：http://dali.redwolf501.top/Article/details/gtsfrjxxqu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtptfjpfoq.html

[Q62] 分组占比
来源：http://dali.316326.xyz/Article/details/gtkaixxdup.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gtbzpvegew.html

[Q63] 开启事务
来源：http://dali.xziqi.cn/Article/details/gtgrbwomgs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sufxvd.cn/Article/details/gttseniqfs.html

[Q64] 提交事务
来源：http://dali.sysykeji.top/Article/details/gtpkzajsfs.html

COMMIT;
来源：http://dali.yonumen.top/Article/details/gtykjyfmnv.html

[Q65] 回滚事务
来源：http://dali.pengpengdd.cyou/Article/details/gtlfuarupf.html

ROLLBACK;
来源：http://dali.316326.xyz/Article/details/gttydzfcsw.html

[Q66] 行锁查询
来源：http://dali.chenzaomai.com/Article/details/gtcwxmpmfe.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hysaishi.cn/Article/details/gtsqkhsvav.html

[Q67] 设置隔离级别
来源：http://dali.nanxuanxn.top/Article/details/gtpzcmnskx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sxryk.cn/Article/details/gtlqzjawon.html

[Q68] 保存点
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppsonyrj.html

SAVEPOINT sp1;
来源：http://dali.chenzaomai.com/Article/details/gtweprfubx.html

ROLLBACK TO sp1;
来源：http://dali.cheryme.top/Article/details/gtolggnnfe.html

[Q69] 查看执行计划
来源：http://dali.zhoulong.xyz/Article/details/gtbdibawrb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ehwqpu.com/Article/details/gtjtnmqrzk.html

[Q70] 更新统计信息
来源：http://dali.haohaochexian.top/Article/details/gtztlfmzas.html

ANALYZE TABLE users;
来源：http://dali.birdmap.top/Article/details/gtzwwzdykm.html

[Q71] 查看建表语句
来源：http://dali.haohaochexian.top/Article/details/gthzoohinw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.pycfn.com/Article/details/gtkvbmakbr.html

[Q72] 查看索引
来源：http://dali.ydzc1.top/Article/details/gttxsxbfvo.html

SHOW INDEX FROM users;
来源：http://dali.yj20258.top/Article/details/gtulexxlqf.html

[Q73] 查看表状态
来源：http://dali.chenzaomai.com/Article/details/gtfimdtfyo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gotoacloud.top/Article/details/gtelshdxve.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbqshykx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.dashuyun.cn/Article/details/gtfwwnefxd.html

[Q75] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gtnbpwekze.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtnjacnapu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jyoumei.cn/Article/details/gtrowcqxjg.html

[Q76] 按天统计
来源：http://dali.meibo888.top/Article/details/gtdyvgtttw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhixingplan.top/Article/details/gtvxdldgbq.html

[Q77] 时间加减
来源：http://dali.yangfankeji.com/Article/details/gtpjcyghxw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.bjfxy.top/Article/details/gteadqnmid.html

[Q78] 当前时间
来源：http://dali.fzhhl.top/Article/details/gtenlrrrzd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.dianchejie.cn/Article/details/gtmmpybfje.html

[Q79] 字符串拼接
来源：http://dali.zycfv.cn/Article/details/gtmmdcdmzg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tianlin.xyz/Article/details/gtoeoyxzdv.html

[Q80] 字符串截取
来源：http://dali.hongshengwenyu.top/Article/details/gtcfcvcpms.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtztvytupe.html

[Q81] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gtpamqbjzz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.aizwys.cn/Article/details/gtzfhcakbp.html

[Q82] 字符长度与字节长度
来源：http://dali.yuxming.cn/Article/details/gtdwigends.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtnbkceeon.html

[Q83] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gtnzkygutx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gtenrddpll.html

[Q84] 去除首尾空格
来源：http://dali.sweek.top/Article/details/gtnlwwcxfk.html

SELECT TRIM(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtrjotmigd.html

[Q85] 数值取整
来源：http://dali.chenlongwang.top/Article/details/gtanwljjml.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.meibo888.top/Article/details/gtauhitsqj.html

[Q86] 读取 JSON 字段
来源：http://dali.hammf.cn/Article/details/gtxdkslzvt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjmobxsq.html

[Q87] JSON 字段做条件
来源：http://dali.gotoacloud.top/Article/details/gtvxwvzeuy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nwbrower.top/Article/details/gtekpsauco.html

[Q88] 行转列（条件聚合）
来源：http://dali.hongshengwenyu.top/Article/details/gtrrqdzbys.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shuidangran.top/Article/details/gtdghswtlz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtlxhdikmp.html

[Q89] 判断表是否存在
来源：http://dali.tanke756.top/Article/details/gtrwqmumff.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gtlnlpkgeh.html

[Q90] 生成序号列
来源：http://dali.sufxvd.cn/Article/details/gtrppdfeck.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sxryk.cn/Article/details/gtoovianip.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtwyophlca.html

R. Bash 专题
来源：http://dali.xinyue.icu/Article/details/gtkkvssoyv.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtvaraimed.html

[R01] shebang 与严格模式
来源：http://dali.jinqigfzy.top/Article/details/gtzylzoqsq.html

#!/usr/bin/env bash
来源：http://dali.havefunace.top/Article/details/gtaccxozir.html

set -euo pipefail
来源：http://dali.snrcjt.cn/Article/details/gtahqnoosz.html

[R02] 变量赋值与使用
来源：http://dali.chenzaomai.com/Article/details/gtjfrbjyrz.html

name="Tom"; echo "$name"
来源：http://dali.zhixingplan.top/Article/details/gtuteekhmo.html

[R03] 只读变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdtdjcsw.html

readonly PI=3.14
来源：http://dali.guannengcc.top/Article/details/gtyqatuiep.html

[R04] 位置参数
来源：http://dali.nwbrower.top/Article/details/gtjkokxdth.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yvedp.cn/Article/details/gtzbminboc.html

[R05] 参数默认值
来源：http://dali.yvedp.cn/Article/details/gtouuhpanv.html

name="${1:-default}"
来源：http://dali.shuidangran.top/Article/details/gtshwculln.html

[R06] 判断命令是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gtgfotajox.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gtmiauymwg.html

[R07] if 判断文件
来源：http://dali.yvedp.cn/Article/details/gtwsofyvuh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.bjfxy.top/Article/details/gtwcnlrhxn.html

[R08] 数值比较
来源：http://dali.snrcjt.cn/Article/details/gtmtqwtxku.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.fzhhl.top/Article/details/gtsvmfbtlv.html

[R09] 字符串比较
来源：http://dali.meibo888.top/Article/details/gtmzhkfpdo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jqgfzy.top/Article/details/gtfpflyjij.html

[R10] 正则匹配
来源：http://dali.sysykeji.top/Article/details/gtdjjmntkz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.pycfn.com/Article/details/gtewipldvp.html

[R11] case 多分支
来源：http://dali.vqdsnc.cn/Article/details/gtjoclxgkm.html

case "$1" in
来源：http://dali.jiagoushi.top/Article/details/gtfcjgcloo.html

start) echo "启动" ;;
来源：http://dali.0kj1m.cn/Article/details/gtalnwseok.html

stop)  echo "停止" ;;
来源：http://dali.zhoulong.xyz/Article/details/gtfqowergx.html

*)     echo "未知命令" ;;
来源：http://dali.fzhhl.top/Article/details/gtpreaseip.html

esac
来源：http://dali.xuetiantiany.cn/Article/details/gtivpgawgi.html

[R12] for 遍历文件
来源：http://dali.xylfe.cn/Article/details/gtrlzwyhre.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guowangkeji.top/Article/details/gtaitwvfvc.html

[R13] for 计数循环
来源：http://dali.nwbrower.top/Article/details/gtpqmjkkfe.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.redwolf501.top/Article/details/gtazqqswrj.html

[R14] C 风格 for
来源：http://dali.meibo888.top/Article/details/gtblntoiob.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtqjnidgko.html

[R15] while 逐行读文件
来源：http://dali.meibo888.top/Article/details/gtrfxmaiue.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjkxydzx.html

[R16] until 等待条件
来源：http://dali.svipenyu.cn/Article/details/gtjgtsngam.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xuanzx.com/Article/details/gtfkjvitgn.html

[R17] 数组定义与取值
来源：http://dali.316326.xyz/Article/details/gtqxqinxky.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zdqjudy.top/Article/details/gthpouctwm.html

[R18] 遍历数组
来源：http://dali.aizwys.cn/Article/details/gtqjnmcflx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tian-w.cn/Article/details/gtrbjbkzxy.html

[R19] 数组长度
来源：http://dali.tian-w.cn/Article/details/gtabkpitxo.html

echo "${#arr[@]}"
来源：http://dali.ppjwa.cn/Article/details/gtlwklaosg.html

[R20] 关联数组（字典）
来源：http://dali.kuanghao11.cn/Article/details/gtworrbtoz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenlongwang.top/Article/details/gtchmofefk.html

[R21] 字符串长度
来源：http://dali.guannengcc.top/Article/details/gtifjnxafl.html

echo "${#s}"
来源：http://dali.zdqjudy.top/Article/details/gtvxgwhffw.html

[R22] 截取子串
来源：http://dali.dashuyun.cn/Article/details/gtbkpgizmh.html

echo "${s:0:5}"
来源：http://dali.vqdsnc.cn/Article/details/gtlgtdsehh.html

[R23] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gtvkuqsjlh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj20258888.top/Article/details/gtpjwfeorp.html

[R24] 大小写转换
来源：http://dali.yuanzhike.top/Article/details/gtenbapnxs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shzxlz.cn/Article/details/gtnagabgpt.html

[R25] 去后缀 / 去前缀
来源：http://dali.shangyingyoupin.top/Article/details/gtcjrmrdma.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jianghu66.top/Article/details/gtbifqwxcw.html

[R26] 命令替换
来源：http://dali.gotoacloud.top/Article/details/gtxyzoycuw.html

now=$(date +%F); echo "$now"
来源：http://dali.pengpengdd.cyou/Article/details/gtmnpxdmhf.html

[R27] 算术展开
来源：http://dali.jinqigufen.top/Article/details/gtpqhyoxwa.html

echo $((1 + 2 * 3))
来源：http://dali.yueranfly.top/Article/details/gtnhirsndm.html

[R28] 浮点运算
来源：http://dali.shzxlz.cn/Article/details/gtnkzfgzzg.html

echo "scale=2; 10/3" | bc
来源：http://dali.hongshengwenyu.top/Article/details/gtfsoinglt.html

[R29] 定义函数
来源：http://dali.snrcjt.cn/Article/details/gtablzvwmh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jianghu66.top/Article/details/gttcvptlcg.html

[R30] 函数返回状态码
来源：http://dali.gaohongyu789.top/Article/details/gtasfwsmlq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xuetiantiany.cn/Article/details/gtabshxxjr.html

[R31] 局部变量
来源：http://dali.jlsjyb.cn/Article/details/gtaztapxka.html

f() { local x=1; echo "$x"; }
来源：http://dali.ybcxt.top/Article/details/gtqhuxzvwq.html

[R32] 参数个数校验
来源：http://dali.shangyingyoupin.top/Article/details/gtyauxflbj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfrtjimii.html

[R33] 捕获错误并提示行号
来源：http://dali.sweek.top/Article/details/gtgqyvrwav.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.mhx1999.top/Article/details/gtzkhkvyxq.html

[R34] 退出时清理
来源：http://dali.c1oappe.top/Article/details/gtbzkfzpsh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvdndmgz.html

[R35] 后台执行并等待
来源：http://dali.jinqigufen.top/Article/details/gtisegosjs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.fzhhl.top/Article/details/gtjpphizot.html

[R36] 并发执行多个任务
来源：http://dali.xinyue.icu/Article/details/gtnvrjgyad.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cqqwz.cn/Article/details/gtzkrvoemq.html

[R37] 把输出赋给变量
来源：http://dali.yangfankeji.com/Article/details/gtdnvdkfmf.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gtalegbsgs.html

[R38] 管道串联
来源：http://dali.tanke756.top/Article/details/gtobycogeg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnqzz.top/Article/details/gtemjhphpn.html

[R39] 重定向标准输出与错误
来源：http://dali.fzhhl.top/Article/details/gtriiztfqd.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gtlkjeeklk.html

[R40] 追加写日志
来源：http://dali.iojbl.cn/Article/details/gtaukqomwo.html

echo "log" >> out.log
来源：http://dali.smart0.xyz/Article/details/gtptjyupaz.html

[R41] 丢弃输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbsnwpbor.html

cmd >/dev/null 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjiistzg.html

[R42] 输入重定向
来源：http://dali.9152youxi.cn/Article/details/gtuvoveysu.html

wc -l < a.txt
来源：http://dali.gzhubu.top/Article/details/gtlnpkofrl.html

[R43] 按名字查找文件
来源：http://dali.guowangkeji.top/Article/details/gtsqqxtrkx.html

find . -name "*.log" -type f
来源：http://dali.cheryme.top/Article/details/gttbewvviq.html

[R44] 按修改时间查找
来源：http://dali.hammf.cn/Article/details/gtldfcbedm.html

find . -mtime -7 -type f
来源：http://dali.cheryme.top/Article/details/gtwotyczza.html

[R45] 批量删除
来源：http://dali.daria6918.cn/Article/details/gtoeyrkqdd.html

find . -name "*.tmp" -delete
来源：http://dali.redwolf501.top/Article/details/gtzjtczpzq.html

[R46] 递归替换文件内容
来源：http://dali.meibo888.top/Article/details/gtjkeseppt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.meibo888.top/Article/details/gtoblenehy.html

[R47] sed 单行替换
来源：http://dali.zhixingplan.top/Article/details/gthcnwmmka.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xinyue.icu/Article/details/gtbqebnaph.html

[R48] awk 取指定列
来源：http://dali.kuanghao11.cn/Article/details/gtrzoyqczt.html

awk '{print $1, $3}' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtjlvghlqi.html

[R49] awk 带条件
来源：http://dali.hnqzz.top/Article/details/gtwxdykjlh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cheryme.top/Article/details/gtdtlskhpi.html

[R50] awk 求和
来源：http://dali.tianlin.xyz/Article/details/gtvsuywcsm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.smart0.xyz/Article/details/gtvjxepmeq.html

[R51] 排序去重取前几
来源：http://dali.jyoumei.cn/Article/details/gttnwsvtbw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jyoumei.cn/Article/details/gtuvazmidd.html

[R52] 统计行数
来源：http://dali.jiagoushi.top/Article/details/gtgbnpgdcs.html

wc -l a.txt
来源：http://dali.yj20258888.top/Article/details/gtkxykrfak.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258888.top/Article/details/gtwftgzusg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tian-w.cn/Article/details/gtedessfoy.html

[R54] 比较两个文件
来源：http://dali.gotoacloud.top/Article/details/gtofxaeqjv.html

diff a.txt b.txt
来源：http://dali.daria6918.cn/Article/details/gtaqnzmopo.html

[R55] 压缩与解压
来源：http://dali.jqgfzy.top/Article/details/gtqbqlhils.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.smart0.xyz/Article/details/gtjltllxzu.html

[R56] 远程拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavualwzi.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gtqvvggzgj.html

[R57] 远程执行命令
来源：http://dali.feifeiyinyue.top/Article/details/gtwcmsynys.html

ssh user@host 'uptime'
来源：http://dali.daxiang520.top/Article/details/gtwtdtlnau.html

[R58] 下载文件
来源：http://dali.gogol.net.cn/Article/details/gtnfvrzosf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.316326.xyz/Article/details/gtgwcrzlwx.html

[R59] 发 POST JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtnzbskynu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ivvv.top/Article/details/gtmjkbwxyk.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gthogarvez.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenlongwang.top/Article/details/gtlkauizei.html

[R61] 磁盘占用
来源：http://dali.sysykeji.top/Article/details/gtvwnuswfu.html

df -h;  du -sh *
来源：http://dali.hywenlv.cn/Article/details/gtvleinepp.html

[R62] 找最占空间的文件
来源：http://dali.gzhubu.top/Article/details/gtogjcsase.html

du -ah . | sort -rh | head -10
来源：http://dali.cucudq.cn/Article/details/gtivawabhf.html

[R63] 内存与进程
来源：http://dali.jinqigfzy.top/Article/details/gtfefpkviy.html

free -h;  ps aux | grep nginx
来源：http://dali.chenjidiqi.icu/Article/details/gtrydjrjdg.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gtqbjbgpce.html

kill -9 $(pgrep -f app.py)
来源：http://dali.0kj1m.cn/Article/details/gtqvkulzei.html

[R65] 查看端口占用
来源：http://dali.hnxiangtu.top/Article/details/gtpjvpkqyy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yvedp.cn/Article/details/gtoaghvymb.html

[R66] 定时任务
来源：http://dali.sysykeji.top/Article/details/gtserfzzit.html

crontab -e;  crontab -l
来源：http://dali.feifeiyinyue.top/Article/details/gtckonavog.html

[R67] 生成随机十六进制串
来源：http://dali.shuidangran.top/Article/details/gtbytmdibj.html

openssl rand -hex 16
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlfxuojux.html

[R68] 计算文件校验值
来源：http://dali.sweek.top/Article/details/gtvamsddbg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.redwolf501.top/Article/details/gtbnfhjvtf.html

[R69] 生成随机密码
来源：http://dali.dashuyun.cn/Article/details/gtrfufmhsw.html

head -c 16 /dev/urandom | base64
来源：http://dali.sysykeji.top/Article/details/gthzsncsdl.html

[R70] 时间戳与互转
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxxieali.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gtcvoruvkp.html

[R71] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gtlmwhylla.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shuidangran.top/Article/details/gtevcwjtbt.html

[R72] 等待端口就绪
来源：http://dali.xinyue.icu/Article/details/gtbwmhxadc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.havefunace.top/Article/details/gtidkyxpqq.html

[R73] 分割大日志
来源：http://dali.chenlongwang.top/Article/details/gtxgmvatpy.html

split -l 1000 big.log part_
来源：http://dali.yonumen.top/Article/details/gtbsratddy.html

[R74] 批量重命名
来源：http://dali.zhongyouzk.top/Article/details/gtqaociqji.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yanxiufei.cn/Article/details/gtwtyscurj.html

[R75] 导出环境变量
来源：http://dali.cucudq.cn/Article/details/gtoplyzent.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sxryk.cn/Article/details/gtjtrfinid.html

[R76] 使用临时文件
来源：http://dali.chenzaomai.com/Article/details/gtdtnexcky.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cashguo.top/Article/details/gtuyqxllsn.html

[R77] 读取用户输入
来源：http://dali.yj20258888.top/Article/details/gtxewqtbov.html

read -rp "请输入: " ans
来源：http://dali.gzhubu.top/Article/details/gtrqbdtzdz.html

[R78] 交互式菜单
来源：http://dali.hnqzz.top/Article/details/gtbedjnjbr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ppjwa.cn/Article/details/gtxqekrdas.html

[R79] 解析命令行选项
来源：http://dali.bjfxy.top/Article/details/gtjanhfnmb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuanzx.com/Article/details/gtvyqznhyc.html

[R80] 查看脚本执行耗时
来源：http://dali.cucudq.cn/Article/details/gtkjqidwkk.html

time ./run.sh
来源：http://dali.ybcxt.top/Article/details/gtogoypkjg.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtkdgryrym.html

S. C / C++ 专题
来源：http://dali.xylfe.cn/Article/details/gtcppijlsm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtzrvqnghp.html

[S01] C：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtdflxkten.html

#include <stdio.h>
来源：http://dali.gzhubu.top/Article/details/gtrydsdetu.html


<!-- 参考信息 -->