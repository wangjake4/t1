代发 wailian999

[Q33] 多列分组
来源：http://dali.yj202588.top/Article/details/gtdkjcfypy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj202588.top/Article/details/gtiyqqxgfn.html

[Q34] 每组取第一条
来源：http://dali.yvedp.cn/Article/details/gtlandtpgf.html

SELECT * FROM (
来源：http://dali.jianghu66.top/Article/details/gtkbfbjjpg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.iojbl.cn/Article/details/gttjxauzrc.html

) t WHERE rn = 1;
来源：http://dali.sxryk.cn/Article/details/gtmyykjpxo.html

[Q35] 内连接
来源：http://dali.xziqi.cn/Article/details/gtrghntbkv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gtjquugnie.html

[Q36] 左连接
来源：http://dali.kuanghao11.cn/Article/details/gtncxmvngy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhoulong.xyz/Article/details/gtnuutyrbi.html

[Q37] 右连接
来源：http://dali.xuetiantiany.cn/Article/details/gtgapdqgyb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hfpthk.cn/Article/details/gtzvnxexaa.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmmghzov.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cucudq.cn/Article/details/gtmyfwwssw.html

[Q39] 自连接（查上下级）
来源：http://dali.yangfankeji.com/Article/details/gtjfhrwnql.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.316326.xyz/Article/details/gtwaddqcmz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.mhx1999.top/Article/details/gtsqlpqwyh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.fengsongda.top/Article/details/gtujvbgckj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhoulong.xyz/Article/details/gteklqvxaf.html

[Q41] 多表连接
来源：http://dali.cashguo.top/Article/details/gtrwoxmzmk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhengqikj.top/Article/details/gtdwiuplex.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhongyouzk.top/Article/details/gtbfysojxi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gzhubu.top/Article/details/gtclpffqjr.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxinkj.top/Article/details/gtxzpczxgy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.dashuyun.cn/Article/details/gtodwyaval.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.redwolf501.top/Article/details/gtridmnphn.html

[Q43] 标量子查询
来源：http://dali.andypj.xyz/Article/details/gtfypqivll.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.tianlin.xyz/Article/details/gtftwcwpnf.html

[Q44] IN 子查询
来源：http://dali.nanxinkj.top/Article/details/gtsbrjfokb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cucudq.cn/Article/details/gtyaveqnnj.html

[Q45] EXISTS 判断存在
来源：http://dali.0kj1m.cn/Article/details/gtrbyezcht.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gtbwqgjagp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.daria6918.cn/Article/details/gtppqlsvmp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jlsjyb.cn/Article/details/gtctintale.html

[Q47] 与平均值比较
来源：http://dali.shuidangran.top/Article/details/gttceqbcec.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yuanzhike.top/Article/details/gtrszvxrei.html

[Q48] CTE 公用表表达式
来源：http://dali.jinqigufen.top/Article/details/gtoqcprszl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.daria6918.cn/Article/details/gtqauxagjr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.daria6918.cn/Article/details/gtnvemyjhv.html

[Q49] 更新单行
来源：http://dali.cashguo.top/Article/details/gtvdxoczoc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gthimtfprd.html

[Q50] 批量更新
来源：http://dali.xuanzx.com/Article/details/gtrpukzkep.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daxiang520.top/Article/details/gthisphzyf.html

[Q51] 用子查询更新
来源：http://dali.dashuyun.cn/Article/details/gteitmwshj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jianghu66.top/Article/details/gtmuyguofz.html

[Q52] 删除指定行
来源：http://dali.shangyingyoupin.top/Article/details/gtnspyjakz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.kuanghao11.cn/Article/details/gtszotkkvn.html

[Q53] 按条件删除
来源：http://dali.yueranfly.top/Article/details/gtqgjlanvk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenzaomai.com/Article/details/gtwzaeidyo.html

[Q54] 清空表
来源：http://dali.andypj.xyz/Article/details/gtohvgsfjh.html

TRUNCATE TABLE logs;
来源：http://dali.316326.xyz/Article/details/gtoiyytqwe.html

[Q55] 排名（并列占位）
来源：http://dali.guowangkeji.top/Article/details/gtldlfjbvj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj20258.top/Article/details/gthpeoensj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yanxiufei.cn/Article/details/gtwharyghq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jqgufenzy.top/Article/details/gtkgesbhsd.html

[Q57] 行号
来源：http://dali.dianchejie.cn/Article/details/gttgipmlta.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdjfberh.html

[Q58] 累计求和
来源：http://dali.zhixingplan.top/Article/details/gtaalgvtgn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtbkbzvkcw.html

[Q59] 分组内累计
来源：http://dali.sweek.top/Article/details/gtwsmwuifv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtoaqqjcmw.html

[Q60] 取上一行 / 下一行
来源：http://dali.xinyue.icu/Article/details/gtjbyatxej.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.c1oappe.top/Article/details/gtekgudvib.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtknnxtnkf.html

[Q61] 移动平均
来源：http://dali.jianghu66.top/Article/details/gtbhlqeqct.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtoeeyvqwb.html

[Q62] 分组占比
来源：http://dali.feifeiyinyue.top/Article/details/gtbnovuqlu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gtkwlfkutx.html

[Q63] 开启事务
来源：http://dali.gotoacloud.top/Article/details/gtxvuwshzo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hysaishi.cn/Article/details/gtlghmvsab.html

[Q64] 提交事务
来源：http://dali.sxryk.cn/Article/details/gtxgaglzmc.html

COMMIT;
来源：http://dali.dianchejie.cn/Article/details/gtolyavfjd.html

[Q65] 回滚事务
来源：http://dali.shanyushiyangtech.top/Article/details/gthrjsmrsk.html

ROLLBACK;
来源：http://dali.nwbrower.top/Article/details/gtlztlipfn.html

[Q66] 行锁查询
来源：http://dali.ivvv.top/Article/details/gttctndzer.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hfpthk.cn/Article/details/gtippogbfu.html

[Q67] 设置隔离级别
来源：http://dali.hnqzz.top/Article/details/gtbtmiaqbg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sysykeji.top/Article/details/gttadaqbhb.html

[Q68] 保存点
来源：http://dali.wangdashe.top/Article/details/gtybyygwyl.html

SAVEPOINT sp1;
来源：http://dali.yueranfly.top/Article/details/gtveavmitt.html

ROLLBACK TO sp1;
来源：http://dali.zycfv.cn/Article/details/gtupzuegtk.html

[Q69] 查看执行计划
来源：http://dali.yonumen.top/Article/details/gtqzrjywtk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.guowangkeji.top/Article/details/gtwrvcynri.html

[Q70] 更新统计信息
来源：http://dali.tianlin.xyz/Article/details/gtwooczhut.html

ANALYZE TABLE users;
来源：http://dali.xinyue.icu/Article/details/gtsdiayegt.html

[Q71] 查看建表语句
来源：http://dali.jlsjyb.cn/Article/details/gtkcjeffso.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.pycfn.com/Article/details/gtfkgynmdi.html

[Q72] 查看索引
来源：http://dali.pengpengdd.cyou/Article/details/gtmiclyrxd.html

SHOW INDEX FROM users;
来源：http://dali.yangfankeji.com/Article/details/gthrqyopur.html

[Q73] 查看表状态
来源：http://dali.yj20258888.top/Article/details/gtzllgisjo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gtzuwxkgpu.html

[Q74] 强制使用索引
来源：http://dali.shangyingyoupin.top/Article/details/gtrfwpajwd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ehwqpu.com/Article/details/gtvmidqzen.html

[Q75] 日期格式化
来源：http://dali.gaohongyu789.top/Article/details/gtybhnmsgf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtvzkkcvyb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ivvv.top/Article/details/gtuymsamlk.html

[Q76] 按天统计
来源：http://dali.wangdashe.top/Article/details/gtubcmitdo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.pengpengdd.cyou/Article/details/gtzaoladxq.html

[Q77] 时间加减
来源：http://dali.mhx1999.top/Article/details/gtjtpmivyw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hywenlv.cn/Article/details/gtxlbvwtlu.html

[Q78] 当前时间
来源：http://dali.tian-w.cn/Article/details/gthvdoywsl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hysaishi.cn/Article/details/gtnvdknync.html

[Q79] 字符串拼接
来源：http://dali.quarkkingdee.top/Article/details/gtoredunjn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhoulong.xyz/Article/details/gtaqrhubie.html

[Q80] 字符串截取
来源：http://dali.gotoacloud.top/Article/details/gtothselkv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtywwjqfpd.html

[Q81] 字符串替换
来源：http://dali.jqgfzy.top/Article/details/gtgqjgfyzh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.aizwys.cn/Article/details/gtaehynkep.html

[Q82] 字符长度与字节长度
来源：http://dali.aizwys.cn/Article/details/gttsamsxtk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtsslszshs.html

[Q83] 大小写转换
来源：http://dali.vqdsnc.cn/Article/details/gtgxnpwxgz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtdafwutqg.html

[Q84] 去除首尾空格
来源：http://dali.zhongyouzk.top/Article/details/gtuqgduhxb.html

SELECT TRIM(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gtwakagakr.html

[Q85] 数值取整
来源：http://dali.cqqwz.cn/Article/details/gtmnskkgxc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.316326.xyz/Article/details/gtgvtovtgz.html

[Q86] 读取 JSON 字段
来源：http://dali.chenlongwang.top/Article/details/gtdgoingfa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxbfwmlc.html

[Q87] JSON 字段做条件
来源：http://dali.sufxvd.cn/Article/details/gtmrkwilgf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sysykeji.top/Article/details/gtnexvonlf.html

[Q88] 行转列（条件聚合）
来源：http://dali.ybcxt.top/Article/details/gthlmqltdt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nanxuanxn.top/Article/details/gtvfqmkdod.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zycfv.cn/Article/details/gtiynsnbyx.html

[Q89] 判断表是否存在
来源：http://dali.jianghu66.top/Article/details/gtgidbmslm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hywenlv.cn/Article/details/gtrjacvcow.html

[Q90] 生成序号列
来源：http://dali.yj20258.top/Article/details/gtwfbwqket.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yangfankeji.com/Article/details/gtwmpyqkdf.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtybolynds.html

R. Bash 专题
来源：http://dali.tian-w.cn/Article/details/gtujwxqdii.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtktcblpel.html

[R01] shebang 与严格模式
来源：http://dali.ppjwa.cn/Article/details/gtzjgvtdzh.html

#!/usr/bin/env bash
来源：http://dali.yangfankeji.com/Article/details/gtkdilpijt.html

set -euo pipefail
来源：http://dali.sxryk.cn/Article/details/gtydxbmcaa.html

[R02] 变量赋值与使用
来源：http://dali.pycfn.com/Article/details/gtoqmikmhb.html

name="Tom"; echo "$name"
来源：http://dali.andypj.xyz/Article/details/gtpmszqxgr.html

[R03] 只读变量
来源：http://dali.yvedp.cn/Article/details/gtfaqcavlg.html

readonly PI=3.14
来源：http://dali.yangfankeji.com/Article/details/gtreodumul.html

[R04] 位置参数
来源：http://dali.tianlin.xyz/Article/details/gtcfalnndf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.guannengcc.top/Article/details/gtkdmukayq.html

[R05] 参数默认值
来源：http://dali.yj20258888.top/Article/details/gtnaezzpmo.html

name="${1:-default}"
来源：http://dali.cashguo.top/Article/details/gtvkddobwb.html

[R06] 判断命令是否存在
来源：http://dali.snrcjt.cn/Article/details/gtncizpnjr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gtpyieznvn.html

[R07] if 判断文件
来源：http://dali.gaohongyu789.top/Article/details/gtftdtzrug.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtklrshuhs.html

[R08] 数值比较
来源：http://dali.gogol.net.cn/Article/details/gtzzygmetx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxnzwgae.html

[R09] 字符串比较
来源：http://dali.guannengcc.top/Article/details/gtlsexmfza.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtrsuslzul.html

[R10] 正则匹配
来源：http://dali.jinqigufen.top/Article/details/gtfdhihfvo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.dianchejie.cn/Article/details/gtbnjdxaeb.html

[R11] case 多分支
来源：http://dali.gaohongyu789.top/Article/details/gtlsqjklaq.html

case "$1" in
来源：http://dali.xuanzx.com/Article/details/gtdscdukiq.html

start) echo "启动" ;;
来源：http://dali.cqqwz.cn/Article/details/gtljqqpvnh.html

stop)  echo "停止" ;;
来源：http://dali.smart0.xyz/Article/details/gtafbcxdrh.html

*)     echo "未知命令" ;;
来源：http://dali.cheryme.top/Article/details/gtrjzhmxep.html

esac
来源：http://dali.aibaodan.cn/Article/details/gtsehqpgpo.html

[R12] for 遍历文件
来源：http://dali.nanxuanxn.top/Article/details/gtsdjbilik.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yueranfly.top/Article/details/gtaeirgfta.html

[R13] for 计数循环
来源：http://dali.chenlongwang.top/Article/details/gtnqhhmihz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gtanombdad.html

[R14] C 风格 for
来源：http://dali.xziqi.cn/Article/details/gtnbwxtnol.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.wangdashe.top/Article/details/gtgutcjirt.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpcguhgl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yonumen.top/Article/details/gtsgvomdrt.html

[R16] until 等待条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpqpltpn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gtejksvrmj.html

[R17] 数组定义与取值
来源：http://dali.ydzc1.top/Article/details/gtnllgtuue.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258888.top/Article/details/gtsqwtxedj.html

[R18] 遍历数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgboiadd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yvedp.cn/Article/details/gtlzpgdrnn.html

[R19] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gtdczgbtib.html

echo "${#arr[@]}"
来源：http://dali.hnqzz.top/Article/details/gtwprzzqfd.html

[R20] 关联数组（字典）
来源：http://dali.yuxming.cn/Article/details/gtgwpkminm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.fzhhl.top/Article/details/gtrdyikexv.html

[R21] 字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gtppwxigas.html

echo "${#s}"
来源：http://dali.jianghu66.top/Article/details/gtfmobnzik.html

[R22] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gtnhflqopz.html

echo "${s:0:5}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjzpdxfg.html

[R23] 字符串替换
来源：http://dali.yuxming.cn/Article/details/gtrkhxwjlq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xziqi.cn/Article/details/gtqagjfwrb.html

[R24] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gtjhjfawdv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.dianchejie.cn/Article/details/gtbddyirrc.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenjidiqi.icu/Article/details/gtuikrcbnx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.andypj.xyz/Article/details/gtroypyyij.html

[R26] 命令替换
来源：http://dali.shzxlz.cn/Article/details/gttusxzfmn.html

now=$(date +%F); echo "$now"
来源：http://dali.aibaodan.cn/Article/details/gtwhklhrcb.html

[R27] 算术展开
来源：http://dali.jinqigufen.top/Article/details/gtyryczzyi.html

echo $((1 + 2 * 3))
来源：http://dali.dianchejie.cn/Article/details/gtowzdyxhz.html

[R28] 浮点运算
来源：http://dali.dashuyun.cn/Article/details/gtxuvmszqc.html

echo "scale=2; 10/3" | bc
来源：http://dali.jyoumei.cn/Article/details/gtqlnajylw.html

[R29] 定义函数
来源：http://dali.wangdashe.top/Article/details/gtslerkmvh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jqgfzy.top/Article/details/gttlvvybrs.html

[R30] 函数返回状态码
来源：http://dali.yangfankeji.com/Article/details/gtipanyajy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cheryme.top/Article/details/gtixvrslus.html

[R31] 局部变量
来源：http://dali.redwolf501.top/Article/details/gtbutaencw.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuanzhike.top/Article/details/gtdncudtwp.html

[R32] 参数个数校验
来源：http://dali.0kj1m.cn/Article/details/gtgqvtdmhh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gtviqaopnq.html

[R33] 捕获错误并提示行号
来源：http://dali.kuanghao11.cn/Article/details/gtcbduzpji.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hammf.cn/Article/details/gterbykale.html

[R34] 退出时清理
来源：http://dali.nanxinkj.top/Article/details/gtnpgiehbu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daria6918.cn/Article/details/gtatqllgdt.html

[R35] 后台执行并等待
来源：http://dali.xylfe.cn/Article/details/gtwuwlelxe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zycfv.cn/Article/details/gtewlswfnx.html

[R36] 并发执行多个任务
来源：http://dali.dashuyun.cn/Article/details/gtmkcepatr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj20258888.top/Article/details/gtlhtwebnc.html

[R37] 把输出赋给变量
来源：http://dali.c1oappe.top/Article/details/gthxgkkdwh.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gtrecruffi.html

[R38] 管道串联
来源：http://dali.gzhubu.top/Article/details/gtklhuvypa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tianlin.xyz/Article/details/gtefdquudr.html

[R39] 重定向标准输出与错误
来源：http://dali.fzhhl.top/Article/details/gtmypcgqre.html

cmd > out.log 2>&1
来源：http://dali.guannengcc.top/Article/details/gtooyamtkx.html

[R40] 追加写日志
来源：http://dali.shzxlz.cn/Article/details/gthwbsatwi.html

echo "log" >> out.log
来源：http://dali.hnqzz.top/Article/details/gtrfkzrkuh.html

[R41] 丢弃输出
来源：http://dali.zhongyouzk.top/Article/details/gtlxywhcfy.html

cmd >/dev/null 2>&1
来源：http://dali.chenzaomai.com/Article/details/gtnqpatedh.html

[R42] 输入重定向
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqmumnwc.html

wc -l < a.txt
来源：http://dali.dashuyun.cn/Article/details/gtypwbokug.html

[R43] 按名字查找文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnejbdcij.html

find . -name "*.log" -type f
来源：http://dali.yuanzhike.top/Article/details/gtsxprmkab.html

[R44] 按修改时间查找
来源：http://dali.cucudq.cn/Article/details/gtlrzdxmey.html

find . -mtime -7 -type f
来源：http://dali.yvedp.cn/Article/details/gtwkyxcoij.html

[R45] 批量删除
来源：http://dali.wangshuangyany.cn/Article/details/gtrvrweedw.html

find . -name "*.tmp" -delete
来源：http://dali.yongpay.top/Article/details/gtyhgzitvh.html

[R46] 递归替换文件内容
来源：http://dali.wangdashe.top/Article/details/gtrbnmgcnq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.redwolf501.top/Article/details/gtbsrfvspl.html

[R47] sed 单行替换
来源：http://dali.svipenyu.cn/Article/details/gtxzikocfy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuanzx.com/Article/details/gtlusyugwr.html

[R48] awk 取指定列
来源：http://dali.yangfankeji.com/Article/details/gtmydlgqaj.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj20258.top/Article/details/gtiqhgdwur.html

[R49] awk 带条件
来源：http://dali.mhx1999.top/Article/details/gtnbvcmdeh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuetiantiany.cn/Article/details/gtvznqlrjy.html

[R50] awk 求和
来源：http://dali.chenjidiqi.icu/Article/details/gtxgnjcers.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtbibpqquk.html

[R51] 排序去重取前几
来源：http://dali.jqgufenzy.top/Article/details/gtiocljztj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dianchejie.cn/Article/details/gtlgbynvsh.html

[R52] 统计行数
来源：http://dali.sweek.top/Article/details/gtbqteetds.html

wc -l a.txt
来源：http://dali.zdqjudy.top/Article/details/gtbflonymo.html

[R53] 查看文件头与实时尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxuxlfjh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenzaomai.com/Article/details/gtpzsnibhh.html

[R54] 比较两个文件
来源：http://dali.birdmap.top/Article/details/gtgzuvnvdx.html

diff a.txt b.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtwwxsfxqh.html

[R55] 压缩与解压
来源：http://dali.sysykeji.top/Article/details/gtewskyodk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigfzy.top/Article/details/gtuosinoeh.html

[R56] 远程拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtnvvtgdlj.html

scp file user@host:/path/
来源：http://dali.c1oappe.top/Article/details/gtccaqemly.html

[R57] 远程执行命令
来源：http://dali.xuetiantiany.cn/Article/details/gthhggaojs.html

ssh user@host 'uptime'
来源：http://dali.ppjwa.cn/Article/details/gthkdycqdv.html

[R58] 下载文件
来源：http://dali.vqdsnc.cn/Article/details/gtfezneubk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gaohongyu789.top/Article/details/gtajbjpfgu.html

[R59] 发 POST JSON
来源：http://dali.yj20258888.top/Article/details/gtsisyzikn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangtech.top/Article/details/gtatiyeckr.html

[R60] 只看 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gtjcgmosec.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.feifeiyinyue.top/Article/details/gttwdlcycf.html

[R61] 磁盘占用
来源：http://dali.yj20258888.top/Article/details/gtvmxewsae.html

df -h;  du -sh *
来源：http://dali.ppjwa.cn/Article/details/gtlpmmcmpu.html

[R62] 找最占空间的文件
来源：http://dali.ybcxt.top/Article/details/gtaruuzlbr.html

du -ah . | sort -rh | head -10
来源：http://dali.yvedp.cn/Article/details/gtrvjnldsh.html

[R63] 内存与进程
来源：http://dali.birdmap.top/Article/details/gtzgvohyvn.html

free -h;  ps aux | grep nginx
来源：http://dali.andypj.xyz/Article/details/gtxdyuahlb.html

[R64] 结束进程
来源：http://dali.jianghu66.top/Article/details/gtckixsrbb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.guowangkeji.top/Article/details/gtvtxajphg.html

[R65] 查看端口占用
来源：http://dali.zhiwuduotai.top/Article/details/gtlturksqp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zycfv.cn/Article/details/gtriiezunw.html

[R66] 定时任务
来源：http://dali.nanxuanxn.top/Article/details/gtzmpriahg.html

crontab -e;  crontab -l
来源：http://dali.daxiang520.top/Article/details/gtjytqqqye.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258.top/Article/details/gtafvsfoqp.html

openssl rand -hex 16
来源：http://dali.sweek.top/Article/details/gterfdvseh.html

[R68] 计算文件校验值
来源：http://dali.pycfn.com/Article/details/gtvktoiaaq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.mhx1999.top/Article/details/gteqifyepd.html

[R69] 生成随机密码
来源：http://dali.yangfankeji.com/Article/details/gtpajfptar.html

head -c 16 /dev/urandom | base64
来源：http://dali.feifeiyinyue.top/Article/details/gtmhzxclgl.html

[R70] 时间戳与互转
来源：http://dali.xziqi.cn/Article/details/gtucayxuyl.html

date +%s;  date -d @1700000000
来源：http://dali.feifeiyinyue.top/Article/details/gtwasifufv.html

[R71] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gtjsdfzixk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xinyue.icu/Article/details/gttxqgzypd.html

[R72] 等待端口就绪
来源：http://dali.zdqjudy.top/Article/details/gtoaktrrct.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fengsongda.top/Article/details/gtbumeovgj.html

[R73] 分割大日志
来源：http://dali.hfpthk.cn/Article/details/gtgowpxaxy.html

split -l 1000 big.log part_
来源：http://dali.dashuyun.cn/Article/details/gtoaioptbi.html

[R74] 批量重命名
来源：http://dali.yj202588.top/Article/details/gtjxtafrxq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuxming.cn/Article/details/gtgfodexmi.html

[R75] 导出环境变量
来源：http://dali.snrcjt.cn/Article/details/gtjqfqwswz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dashuyun.cn/Article/details/gthsrejfzl.html

[R76] 使用临时文件
来源：http://dali.xylfe.cn/Article/details/gtgvnxfraw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gthqtnlxzm.html

[R77] 读取用户输入
来源：http://dali.sxryk.cn/Article/details/gtbgealutl.html

read -rp "请输入: " ans
来源：http://dali.pycfn.com/Article/details/gtzrxusaqa.html

[R78] 交互式菜单
来源：http://dali.shangyingyoupin.top/Article/details/gtmeohwgxl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.dianchejie.cn/Article/details/gtbancfftm.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gteimonubb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhixingplan.top/Article/details/gtwjzzdano.html

[R80] 查看脚本执行耗时
来源：http://dali.shangyingyoupin.top/Article/details/gtenkneigh.html

time ./run.sh
来源：http://dali.ydzc1.top/Article/details/gtkkzhckcj.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtwqalopff.html

S. C / C++ 专题
来源：http://dali.shangyingyoupin.top/Article/details/gtlosgjfgy.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtfnuawlot.html

[S01] C：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtfzkovdwp.html

#include <stdio.h>
来源：http://dali.316326.xyz/Article/details/gtigcvonlq.html


<!-- 参考信息 -->