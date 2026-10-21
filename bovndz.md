代发 wailian999

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjezguux.html

[Q32] 分组拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtjfxqvivz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtchppyqcy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yongpay.top/Article/details/gtpudsulki.html

[Q33] 多列分组
来源：http://dali.hammf.cn/Article/details/gtllbzautd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xuanzx.com/Article/details/gtfdnashlo.html

[Q34] 每组取第一条
来源：http://dali.pengpengdd.cyou/Article/details/gtvololucz.html

SELECT * FROM (
来源：http://dali.yonumen.top/Article/details/gtpvetgsiz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xinyue.icu/Article/details/gtmgkehaut.html

) t WHERE rn = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwamcokhh.html

[Q35] 内连接
来源：http://dali.svipenyu.cn/Article/details/gtbzspfcac.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gtpfkbzzxk.html

[Q36] 左连接
来源：http://dali.gzhubu.top/Article/details/gtfgrtcyfj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zdqjudy.top/Article/details/gtoafbcedb.html

[Q37] 右连接
来源：http://dali.dianchejie.cn/Article/details/gteuqnmflt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.fzhhl.top/Article/details/gtjpqnnujt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ehwqpu.com/Article/details/gtklnxmome.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hammf.cn/Article/details/gtqwpuzyzl.html

[Q39] 自连接（查上下级）
来源：http://dali.feifeiyinyue.top/Article/details/gtxntmphtz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zdqjudy.top/Article/details/gthaqkzjpt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.c1oappe.top/Article/details/gttzfqvieb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ppjwa.cn/Article/details/gtyzhirwjz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.dashuyun.cn/Article/details/gtfmamourp.html

[Q41] 多表连接
来源：http://dali.hywenlv.cn/Article/details/gthzkxrtaq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.mhx1999.top/Article/details/gtgboydpnk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gtpvbpryrv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258.top/Article/details/gtsohqzsbk.html

[Q42] 连接条件附加过滤
来源：http://dali.chenzaomai.com/Article/details/gttpkbbgyc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yangfankeji.com/Article/details/gtnxxjtksv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hysaishi.cn/Article/details/gtgwinnybn.html

[Q43] 标量子查询
来源：http://dali.zhengqikj.top/Article/details/gtxksdrcik.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yueranfly.top/Article/details/gtbrekgnam.html

[Q44] IN 子查询
来源：http://dali.smart0.xyz/Article/details/gtjdljdofy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigufen.top/Article/details/gtirvwzewo.html

[Q45] EXISTS 判断存在
来源：http://dali.vqdsnc.cn/Article/details/gtseysgwkv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gtanfszktk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zycfv.cn/Article/details/gtvyfnvdff.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gtwvtjjvxx.html

[Q47] 与平均值比较
来源：http://dali.chenjidiqi.icu/Article/details/gtdnqruejm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sxryk.cn/Article/details/gthbpwwdye.html

[Q48] CTE 公用表表达式
来源：http://dali.yuanzhike.top/Article/details/gtqkhopxie.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xziqi.cn/Article/details/gtrvnylmpi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdenuwkpz.html

[Q49] 更新单行
来源：http://dali.shanyushiyangtech.top/Article/details/gtnubgopuy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.9152youxi.cn/Article/details/gtelerybvk.html

[Q50] 批量更新
来源：http://dali.quarkkingdee.top/Article/details/gtfwzsfjvk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tian-w.cn/Article/details/gtthqmepwa.html

[Q51] 用子查询更新
来源：http://dali.0kj1m.cn/Article/details/gtzgvdkbeg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.redwolf501.top/Article/details/gtxfwuvyiy.html

[Q52] 删除指定行
来源：http://dali.quarkkingdee.top/Article/details/gtxbkukivd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtqwnokshj.html

[Q53] 按条件删除
来源：http://dali.tian-w.cn/Article/details/gtcqsrfqlx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shangyingyoupin.top/Article/details/gtybiyhotv.html

[Q54] 清空表
来源：http://dali.xziqi.cn/Article/details/gtmpoywqyt.html

TRUNCATE TABLE logs;
来源：http://dali.hammf.cn/Article/details/gtolujzmfy.html

[Q55] 排名（并列占位）
来源：http://dali.ehwqpu.com/Article/details/gttikqvubr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cheryme.top/Article/details/gtwfneaava.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jiagoushi.top/Article/details/gtakbpraim.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenlongwang.top/Article/details/gtarndfnap.html

[Q57] 行号
来源：http://dali.0kj1m.cn/Article/details/gtidvthxyh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtewhcprvq.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gtnflesiba.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtvjvewayk.html

[Q59] 分组内累计
来源：http://dali.yueranfly.top/Article/details/gtsxqclkxe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtbkpntaaf.html

[Q60] 取上一行 / 下一行
来源：http://dali.tian-w.cn/Article/details/gtemjkynhl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jyoumei.cn/Article/details/gtfbfewovc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtpcsipkkh.html

[Q61] 移动平均
来源：http://dali.yanxiufei.cn/Article/details/gtjenriufv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtsoctixlk.html

[Q62] 分组占比
来源：http://dali.cdnleiting.top/Article/details/gtnebvhwdc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gtpmlhfqzg.html

[Q63] 开启事务
来源：http://dali.fengsongda.top/Article/details/gtfjtkhsvl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cqqwz.cn/Article/details/gtpqleptjp.html

[Q64] 提交事务
来源：http://dali.yueranfly.top/Article/details/gtwrmispdj.html

COMMIT;
来源：http://dali.yj20258.top/Article/details/gtwukfaisi.html

[Q65] 回滚事务
来源：http://dali.yj20258.top/Article/details/gtlzrlaajl.html

ROLLBACK;
来源：http://dali.zhoulong.xyz/Article/details/gtitrnxjzj.html

[Q66] 行锁查询
来源：http://dali.gzhubu.top/Article/details/gtrbwctebx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ybcxt.top/Article/details/gtoivogoyy.html

[Q67] 设置隔离级别
来源：http://dali.feifeiyinyue.top/Article/details/gthhjhyvzi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.svipenyu.cn/Article/details/gtxarcpwhy.html

[Q68] 保存点
来源：http://dali.xuetiantiany.cn/Article/details/gtitofnlwx.html

SAVEPOINT sp1;
来源：http://dali.yj20258888.top/Article/details/gtbxgqhxml.html

ROLLBACK TO sp1;
来源：http://dali.aizwys.cn/Article/details/gtzrdxtjqb.html

[Q69] 查看执行计划
来源：http://dali.fengsongda.top/Article/details/gtkifsmvfh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.c1oappe.top/Article/details/gtzwkomuih.html

[Q70] 更新统计信息
来源：http://dali.chenjidiqi.icu/Article/details/gtrjxfosoi.html

ANALYZE TABLE users;
来源：http://dali.cashguo.top/Article/details/gtvuwyxixg.html

[Q71] 查看建表语句
来源：http://dali.haohaochexian.top/Article/details/gtkzjdkdtk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258888.top/Article/details/gtpgajfgei.html

[Q72] 查看索引
来源：http://dali.hfpthk.cn/Article/details/gtmszkvouo.html

SHOW INDEX FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtubwwjdbt.html

[Q73] 查看表状态
来源：http://dali.pycfn.com/Article/details/gthhhfqbdv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yonumen.top/Article/details/gtdfrmsjmq.html

[Q74] 强制使用索引
来源：http://dali.yj202588.top/Article/details/gtnnvzajci.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ehwqpu.com/Article/details/gtnjpfiiov.html

[Q75] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gtjgroaqme.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtrepsndjl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gogol.net.cn/Article/details/gtqhxtkegv.html

[Q76] 按天统计
来源：http://dali.cucudq.cn/Article/details/gtnqsxfonm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sufxvd.cn/Article/details/gtttruprtv.html

[Q77] 时间加减
来源：http://dali.gaohongyu789.top/Article/details/gtcjxskvme.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jiagoushi.top/Article/details/gtkaisaqhg.html

[Q78] 当前时间
来源：http://dali.gaohongyu789.top/Article/details/gtxcqcjfox.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ydzc1.top/Article/details/gtoqiswaej.html

[Q79] 字符串拼接
来源：http://dali.tianlin.xyz/Article/details/gtqjvhiant.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.guowangkeji.top/Article/details/gtyqghzjrv.html

[Q80] 字符串截取
来源：http://dali.sweek.top/Article/details/gtiwenrkuy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gthzgzzyli.html

[Q81] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gtjqzlktzj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.aizwys.cn/Article/details/gtbzllgrgp.html

[Q82] 字符长度与字节长度
来源：http://dali.fengsongda.top/Article/details/gtaahsyntp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtyxulfqwb.html

[Q83] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gtdnwwtqqa.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gtwiatwsvh.html

[Q84] 去除首尾空格
来源：http://dali.haohaochexian.top/Article/details/gtlmndkoyp.html

SELECT TRIM(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtdfwgkqry.html

[Q85] 数值取整
来源：http://dali.dashuyun.cn/Article/details/gtgqwihjrw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shuidangran.top/Article/details/gtgfltccan.html

[Q86] 读取 JSON 字段
来源：http://dali.ivvv.top/Article/details/gtersemnbi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hywenlv.cn/Article/details/gtcunnsbfj.html

[Q87] JSON 字段做条件
来源：http://dali.aizwys.cn/Article/details/gtwooxvdps.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cashguo.top/Article/details/gttdnqgbgv.html

[Q88] 行转列（条件聚合）
来源：http://dali.birdmap.top/Article/details/gtmkkarqsd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ybcxt.top/Article/details/gtdnmhafqr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtswcibqbi.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxwkcwym.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daria6918.cn/Article/details/gtpdnzlodt.html

[Q90] 生成序号列
来源：http://dali.hysaishi.cn/Article/details/gtkhdeljlv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jyoumei.cn/Article/details/gtriucmtld.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtokxyikoe.html

R. Bash 专题
来源：http://dali.xuetiantiany.cn/Article/details/gtgkgrnyzd.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtmaxsofzy.html

[R01] shebang 与严格模式
来源：http://dali.smart0.xyz/Article/details/gtvasfixfl.html

#!/usr/bin/env bash
来源：http://dali.jinqigufen.top/Article/details/gtlvjgiypw.html

set -euo pipefail
来源：http://dali.gotoacloud.top/Article/details/gtzfreesyk.html

[R02] 变量赋值与使用
来源：http://dali.daria6918.cn/Article/details/gtrqyyafua.html

name="Tom"; echo "$name"
来源：http://dali.yj20258888.top/Article/details/gtrfpxfkxa.html

[R03] 只读变量
来源：http://dali.dashuyun.cn/Article/details/gtehfspbot.html

readonly PI=3.14
来源：http://dali.guannengcc.top/Article/details/gtbqjudcjg.html

[R04] 位置参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwfymgoa.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.birdmap.top/Article/details/gtyokubbka.html

[R05] 参数默认值
来源：http://dali.pengpengdd.cyou/Article/details/gtpvfganpa.html

name="${1:-default}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnledqsaz.html

[R06] 判断命令是否存在
来源：http://dali.jianghu66.top/Article/details/gtzwjsjmkm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gtpwwulwib.html

[R07] if 判断文件
来源：http://dali.gotoacloud.top/Article/details/gtchqxfbut.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.haohaochexian.top/Article/details/gtvypumvvd.html

[R08] 数值比较
来源：http://dali.zhiwuduotai.top/Article/details/gtvyomspgk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj20258.top/Article/details/gtaecdipwn.html

[R09] 字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gtvzdayofu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.aizwys.cn/Article/details/gtbzwbgvoe.html

[R10] 正则匹配
来源：http://dali.cdnleiting.top/Article/details/gtzrwruuyj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuanzhike.top/Article/details/gtekxhxtwz.html

[R11] case 多分支
来源：http://dali.ybcxt.top/Article/details/gtawfllnet.html

case "$1" in
来源：http://dali.gogol.net.cn/Article/details/gtwgfwjyly.html

start) echo "启动" ;;
来源：http://dali.jinqigufen.top/Article/details/gtjmhngnkj.html

stop)  echo "停止" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjzbfucn.html

*)     echo "未知命令" ;;
来源：http://dali.xylfe.cn/Article/details/gtyihrlpcq.html

esac
来源：http://dali.sysykeji.top/Article/details/gtsisuhrko.html

[R12] for 遍历文件
来源：http://dali.wangshuangyany.cn/Article/details/gtgabioekk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nwbrower.top/Article/details/gthqsmzbsq.html

[R13] for 计数循环
来源：http://dali.dashuyun.cn/Article/details/gtfroawiwi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgufenzy.top/Article/details/gtshuwqwza.html

[R14] C 风格 for
来源：http://dali.xylfe.cn/Article/details/gtpikkzqpd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtebezoeqr.html

[R15] while 逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtcjcjreyz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sweek.top/Article/details/gtbohjtiaq.html

[R16] until 等待条件
来源：http://dali.hongshengwenyu.top/Article/details/gthhgxbjco.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nwbrower.top/Article/details/gtahzcjggd.html

[R17] 数组定义与取值
来源：http://dali.chenjidiqi.icu/Article/details/gtmpzzfpqt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.svipenyu.cn/Article/details/gtskjyxkyp.html

[R18] 遍历数组
来源：http://dali.yj202588.top/Article/details/gtjdpajzxj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhengqikj.top/Article/details/gtvlglsgtr.html

[R19] 数组长度
来源：http://dali.smart0.xyz/Article/details/gtjjemldvz.html

echo "${#arr[@]}"
来源：http://dali.tianlin.xyz/Article/details/gthcxkkird.html

[R20] 关联数组（字典）
来源：http://dali.gzhubu.top/Article/details/gtwspchigd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.aizwys.cn/Article/details/gtkdlfilng.html

[R21] 字符串长度
来源：http://dali.yueranfly.top/Article/details/gtirxbfxbi.html

echo "${#s}"
来源：http://dali.cheryme.top/Article/details/gteohltoyh.html

[R22] 截取子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgkmvtuu.html

echo "${s:0:5}"
来源：http://dali.aizwys.cn/Article/details/gtqguwjbvx.html

[R23] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gtjputofuz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuxming.cn/Article/details/gtejpjpzgu.html

[R24] 大小写转换
来源：http://dali.meibo888.top/Article/details/gtdwxssoyk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.pycfn.com/Article/details/gtepljcmrc.html

[R25] 去后缀 / 去前缀
来源：http://dali.ehwqpu.com/Article/details/gtnnglrnib.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnveermn.html

[R26] 命令替换
来源：http://dali.jyoumei.cn/Article/details/gtbipggtku.html

now=$(date +%F); echo "$now"
来源：http://dali.zhongyouzk.top/Article/details/gtztwbvkwn.html

[R27] 算术展开
来源：http://dali.shangyingyoupin.top/Article/details/gtdvvrifyv.html

echo $((1 + 2 * 3))
来源：http://dali.xinyue.icu/Article/details/gtcilrpgwv.html

[R28] 浮点运算
来源：http://dali.cqqwz.cn/Article/details/gttbhqoqck.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuetiantiany.cn/Article/details/gtakqqmyjs.html

[R29] 定义函数
来源：http://dali.pengpengdd.cyou/Article/details/gtjnwfgjvh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnxiangtu.top/Article/details/gtakglnibi.html

[R30] 函数返回状态码
来源：http://dali.bjfxy.top/Article/details/gtngiomrde.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hysaishi.cn/Article/details/gtwhtjzbdj.html

[R31] 局部变量
来源：http://dali.guowangkeji.top/Article/details/gtblyuutfl.html

f() { local x=1; echo "$x"; }
来源：http://dali.tanke756.top/Article/details/gtzdmehckh.html

[R32] 参数个数校验
来源：http://dali.snrcjt.cn/Article/details/gtggxxkuig.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yvedp.cn/Article/details/gtrryxexye.html

[R33] 捕获错误并提示行号
来源：http://dali.0kj1m.cn/Article/details/gtirncuhsk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jqgufenzy.top/Article/details/gtmesqlmsx.html

[R34] 退出时清理
来源：http://dali.mhx1999.top/Article/details/gtjaisqbgg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gtvdhwqbms.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gtizzvptpp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cheryme.top/Article/details/gtvcbjnvti.html

[R36] 并发执行多个任务
来源：http://dali.xylfe.cn/Article/details/gtokzebbvo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yanxiufei.cn/Article/details/gtdtfywpgp.html

[R37] 把输出赋给变量
来源：http://dali.yueranfly.top/Article/details/gtgsencoht.html

files=$(ls -1)
来源：http://dali.sufxvd.cn/Article/details/gtspuygnzu.html

[R38] 管道串联
来源：http://dali.shanyushiyangtech.top/Article/details/gtclpiuxnb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shangyingyoupin.top/Article/details/gtabqfxwkx.html

[R39] 重定向标准输出与错误
来源：http://dali.aizwys.cn/Article/details/gtutlujymw.html

cmd > out.log 2>&1
来源：http://dali.bjfxy.top/Article/details/gtypbgrlhk.html

[R40] 追加写日志
来源：http://dali.nanxinkj.top/Article/details/gtssulvypf.html

echo "log" >> out.log
来源：http://dali.jinqigfzy.top/Article/details/gtunhqzpcq.html

[R41] 丢弃输出
来源：http://dali.daria6918.cn/Article/details/gtjnhrkxuu.html

cmd >/dev/null 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gteuevgfnc.html

[R42] 输入重定向
来源：http://dali.yvedp.cn/Article/details/gteeljgjdj.html

wc -l < a.txt
来源：http://dali.zhixingplan.top/Article/details/gtlqptjfen.html

[R43] 按名字查找文件
来源：http://dali.aibaodan.cn/Article/details/gtnqpxvuvj.html

find . -name "*.log" -type f
来源：http://dali.0kj1m.cn/Article/details/gtwavbfurw.html

[R44] 按修改时间查找
来源：http://dali.cdnleiting.top/Article/details/gtihnqwamo.html

find . -mtime -7 -type f
来源：http://dali.cheryme.top/Article/details/gterrlauod.html

[R45] 批量删除
来源：http://dali.quarkkingdee.top/Article/details/gtxopiihfm.html

find . -name "*.tmp" -delete
来源：http://dali.daria6918.cn/Article/details/gtlhpflbya.html

[R46] 递归替换文件内容
来源：http://dali.nanxuanxn.top/Article/details/gtuedpwygn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yangfankeji.com/Article/details/gtvrswdjik.html

[R47] sed 单行替换
来源：http://dali.aizwys.cn/Article/details/gtysfyzjnn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtvfqqzdac.html

[R48] awk 取指定列
来源：http://dali.jqgufenzy.top/Article/details/gthdqondco.html

awk '{print $1, $3}' a.txt
来源：http://dali.sweek.top/Article/details/gtomgincfx.html

[R49] awk 带条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtazipkfrq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuanzx.com/Article/details/gtcheaamja.html

[R50] awk 求和
来源：http://dali.yueranfly.top/Article/details/gtixmbenjo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtentvrlbx.html

[R51] 排序去重取前几
来源：http://dali.yuxming.cn/Article/details/gtfwadyxxj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cucudq.cn/Article/details/gtbwxcunaf.html

[R52] 统计行数
来源：http://dali.chenlongwang.top/Article/details/gtjmnvpnjj.html

wc -l a.txt
来源：http://dali.cqqwz.cn/Article/details/gtvxymuvbj.html

[R53] 查看文件头与实时尾
来源：http://dali.yvedp.cn/Article/details/gtslezbslw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shzxlz.cn/Article/details/gtqgtbsexr.html

[R54] 比较两个文件
来源：http://dali.ybcxt.top/Article/details/gtpimssmzm.html

diff a.txt b.txt
来源：http://dali.xinyue.icu/Article/details/gtoznzaobx.html

[R55] 压缩与解压
来源：http://dali.ppjwa.cn/Article/details/gtqpujtsrh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwowpbocq.html

[R56] 远程拷贝
来源：http://dali.ybcxt.top/Article/details/gtrwczpakg.html

scp file user@host:/path/
来源：http://dali.zhiwuduotai.top/Article/details/gtxijfqfue.html

[R57] 远程执行命令
来源：http://dali.haohaochexian.top/Article/details/gtczfniedm.html

ssh user@host 'uptime'
来源：http://dali.gzhubu.top/Article/details/gteacfetcz.html

[R58] 下载文件
来源：http://dali.jqgfzy.top/Article/details/gthniptxut.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hywenlv.cn/Article/details/gttxpflgzc.html

[R59] 发 POST JSON
来源：http://dali.bjfxy.top/Article/details/gtvncnuluj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yueranfly.top/Article/details/gtwxyavcix.html

[R60] 只看 HTTP 状态码
来源：http://dali.zycfv.cn/Article/details/gtqzwotzsf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pengpengdd.cyou/Article/details/gtcykmyttt.html

[R61] 磁盘占用
来源：http://dali.hywenlv.cn/Article/details/gtquqafxfm.html

df -h;  du -sh *
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkzctujp.html

[R62] 找最占空间的文件
来源：http://dali.yvedp.cn/Article/details/gtewtxyyvr.html

du -ah . | sort -rh | head -10
来源：http://dali.gaohongyu789.top/Article/details/gtjfynrndu.html

[R63] 内存与进程
来源：http://dali.quarkkingdee.top/Article/details/gtgjmsxwfv.html

free -h;  ps aux | grep nginx
来源：http://dali.wangdashe.top/Article/details/gthgcmvsiu.html

[R64] 结束进程
来源：http://dali.chenlongwang.top/Article/details/gtevdjlswy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hammf.cn/Article/details/gtxuzgiibf.html

[R65] 查看端口占用
来源：http://dali.yuxming.cn/Article/details/gtwkedvsse.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zycfv.cn/Article/details/gtfctcsyff.html

[R66] 定时任务
来源：http://dali.chenlongwang.top/Article/details/gtsivmthkp.html

crontab -e;  crontab -l
来源：http://dali.9152youxi.cn/Article/details/gtsrrztjyp.html

[R67] 生成随机十六进制串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihzjpvhd.html

openssl rand -hex 16
来源：http://dali.zhixingplan.top/Article/details/gtytsfwcpz.html

[R68] 计算文件校验值
来源：http://dali.xuetiantiany.cn/Article/details/gtroenrmuz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.bjfxy.top/Article/details/gtqrkatkok.html

[R69] 生成随机密码
来源：http://dali.zhongyouzk.top/Article/details/gtyzgznkyj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhixingplan.top/Article/details/gtfakbioqt.html

[R70] 时间戳与互转
来源：http://dali.smart0.xyz/Article/details/gtjijggifo.html

date +%s;  date -d @1700000000
来源：http://dali.yanxiufei.cn/Article/details/gtvncwqlpc.html

[R71] 日期格式化
来源：http://dali.hysaishi.cn/Article/details/gtiqyydtxm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj202588.top/Article/details/gtxsssyxgc.html

[R72] 等待端口就绪
来源：http://dali.cdnleiting.top/Article/details/gtbyhjnvfw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yanxiufei.cn/Article/details/gtufhqswlm.html

[R73] 分割大日志
来源：http://dali.gzhubu.top/Article/details/gtomxodwnn.html

split -l 1000 big.log part_
来源：http://dali.xuanzx.com/Article/details/gtiohtwpip.html

[R74] 批量重命名
来源：http://dali.zhongyouzk.top/Article/details/gtadilegqk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jqgfzy.top/Article/details/gtsjiovkzi.html

[R75] 导出环境变量
来源：http://dali.yuxming.cn/Article/details/gthwdhyllg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangshuangyany.cn/Article/details/gtprdlsooj.html

[R76] 使用临时文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtckkkwmay.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258.top/Article/details/gtwbfdijeu.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfxeegao.html

read -rp "请输入: " ans
来源：http://dali.chenjidiqi.icu/Article/details/gtvjuerdjb.html

[R78] 交互式菜单
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvevitph.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.feifeiyinyue.top/Article/details/gtpbzchvfh.html

[R79] 解析命令行选项
来源：http://dali.yj20258.top/Article/details/gtxqeqhdpz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fzhhl.top/Article/details/gtuwoxpauj.html

[R80] 查看脚本执行耗时
来源：http://dali.tanke756.top/Article/details/gtemvdlkty.html

time ./run.sh
来源：http://dali.cqqwz.cn/Article/details/gtixqyofkx.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtiorgvlux.html


<!-- 参考信息 -->