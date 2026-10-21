代发 wailian999

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guowangkeji.top/Article/details/gtwnrwzidm.html

) t WHERE rn = 1;
来源：http://dali.xziqi.cn/Article/details/gttgdnnouc.html

[Q35] 内连接
来源：http://dali.ppjwa.cn/Article/details/gtntayrpcy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gtsyomjxcj.html

[Q36] 左连接
来源：http://dali.hnxiangtu.top/Article/details/gtrwrwzoug.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yvedp.cn/Article/details/gtrflomwcw.html

[Q37] 右连接
来源：http://dali.zhongyouzk.top/Article/details/gtildoamla.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ppjwa.cn/Article/details/gtpbdmosiz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aizwys.cn/Article/details/gtadmgmmmh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xuanzx.com/Article/details/gtxcdjdsvz.html

[Q39] 自连接（查上下级）
来源：http://dali.hnqzz.top/Article/details/gtpfselsxk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yonumen.top/Article/details/gtswhhyurb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jianghu66.top/Article/details/gtackgayah.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinqigufen.top/Article/details/gtpzgivgoz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.bjfxy.top/Article/details/gtemqgvjnc.html

[Q41] 多表连接
来源：http://dali.shuidangran.top/Article/details/gtbqpqqjjs.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gzhubu.top/Article/details/gthsbamclf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cqqwz.cn/Article/details/gtgejqoaib.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.pengpengdd.cyou/Article/details/gtcqapclhn.html

[Q42] 连接条件附加过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gttkxqjbxw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cqqwz.cn/Article/details/gteuvxlxvj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yvedp.cn/Article/details/gtbbdfjroc.html

[Q43] 标量子查询
来源：http://dali.daria6918.cn/Article/details/gtnwrhzpjb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ydzc1.top/Article/details/gtzwfcgktj.html

[Q44] IN 子查询
来源：http://dali.wangdashe.top/Article/details/gtgvpwdwiv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gotoacloud.top/Article/details/gtirsskelw.html

[Q45] EXISTS 判断存在
来源：http://dali.yangfankeji.com/Article/details/gtqxuyahvz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hywenlv.cn/Article/details/gtfrpkdsgu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cdnleiting.top/Article/details/gtmdtnqquz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gtsqxdrdxy.html

[Q47] 与平均值比较
来源：http://dali.andypj.xyz/Article/details/gtrrsjlnba.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jyoumei.cn/Article/details/gtxzgucrwj.html

[Q48] CTE 公用表表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gthppwaxib.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nwbrower.top/Article/details/gtjqrbxbbb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.daria6918.cn/Article/details/gtjfrksxtw.html

[Q49] 更新单行
来源：http://dali.dashuyun.cn/Article/details/gttqaamoky.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgfzy.top/Article/details/gtvwrekwxe.html

[Q50] 批量更新
来源：http://dali.xuanzx.com/Article/details/gtavglvrsr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cdnleiting.top/Article/details/gtenapoofb.html

[Q51] 用子查询更新
来源：http://dali.zhixingplan.top/Article/details/gtrigpjjwq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.aibaodan.cn/Article/details/gtijqnypoy.html

[Q52] 删除指定行
来源：http://dali.xziqi.cn/Article/details/gtpbridntx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtiqahogew.html

[Q53] 按条件删除
来源：http://dali.jinqigfzy.top/Article/details/gtlsyosoxw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvhdycvgo.html

[Q54] 清空表
来源：http://dali.yueranfly.top/Article/details/gtwjplxwwe.html

TRUNCATE TABLE logs;
来源：http://dali.hywenlv.cn/Article/details/gtidyhfebr.html

[Q55] 排名（并列占位）
来源：http://dali.hammf.cn/Article/details/gthfpbqhdw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ybcxt.top/Article/details/gthhjmtuvg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jqgfzy.top/Article/details/gtqcjpwdvj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gthcrprwdx.html

[Q57] 行号
来源：http://dali.tian-w.cn/Article/details/gtpwqbcjww.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yonumen.top/Article/details/gthnycwnby.html

[Q58] 累计求和
来源：http://dali.birdmap.top/Article/details/gtxkebuvuj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtaskrlmer.html

[Q59] 分组内累计
来源：http://dali.snrcjt.cn/Article/details/gtsopjapfq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlkxyyfz.html

[Q60] 取上一行 / 下一行
来源：http://dali.daria6918.cn/Article/details/gtcmgwaeoi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tian-w.cn/Article/details/gtacgupnkn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtcyarycpr.html

[Q61] 移动平均
来源：http://dali.nwbrower.top/Article/details/gtipelgvei.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtdibxwlnk.html

[Q62] 分组占比
来源：http://dali.yj20258.top/Article/details/gtxjzwuepq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtpingrmlw.html

[Q63] 开启事务
来源：http://dali.jiagoushi.top/Article/details/gtufbeffqc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gogol.net.cn/Article/details/gtgucefoyj.html

[Q64] 提交事务
来源：http://dali.nanxuanxn.top/Article/details/gtbolikvna.html

COMMIT;
来源：http://dali.vqdsnc.cn/Article/details/gtqhlbdvam.html

[Q65] 回滚事务
来源：http://dali.sweek.top/Article/details/gtluhsnqar.html

ROLLBACK;
来源：http://dali.chenjidiqi.icu/Article/details/gtvjzhstfr.html

[Q66] 行锁查询
来源：http://dali.pengpengdd.cyou/Article/details/gtnunpftos.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yueranfly.top/Article/details/gtdkwyjchb.html

[Q67] 设置隔离级别
来源：http://dali.wangdashe.top/Article/details/gtnyxnbzon.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gogol.net.cn/Article/details/gtbcegaqsp.html

[Q68] 保存点
来源：http://dali.sxryk.cn/Article/details/gtbuzwgqkz.html

SAVEPOINT sp1;
来源：http://dali.shangyingyoupin.top/Article/details/gtvbnnbora.html

ROLLBACK TO sp1;
来源：http://dali.zhengqikj.top/Article/details/gtdlknkfhm.html

[Q69] 查看执行计划
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmbfdayr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.havefunace.top/Article/details/gtjqfuxkyr.html

[Q70] 更新统计信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhaliolu.html

ANALYZE TABLE users;
来源：http://dali.nanxinkj.top/Article/details/gtxhtqmcwk.html

[Q71] 查看建表语句
来源：http://dali.ydzc1.top/Article/details/gtmbbaqvsa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhongyouzk.top/Article/details/gthncazleq.html

[Q72] 查看索引
来源：http://dali.shangyingyoupin.top/Article/details/gtawxjvirx.html

SHOW INDEX FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtwikuwcgb.html

[Q73] 查看表状态
来源：http://dali.tanke756.top/Article/details/gtfbeopjzw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jqgufenzy.top/Article/details/gthqqasmep.html

[Q74] 强制使用索引
来源：http://dali.guannengcc.top/Article/details/gtaxkhvcpv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.meibo888.top/Article/details/gtdmuhpomo.html

[Q75] 日期格式化
来源：http://dali.hysaishi.cn/Article/details/gtwkstmkgp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj202588.top/Article/details/gtweurblzd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jianghu66.top/Article/details/gtvauogwbb.html

[Q76] 按天统计
来源：http://dali.aizwys.cn/Article/details/gtyxhkqszs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhiwuduotai.top/Article/details/gtnphbusti.html

[Q77] 时间加减
来源：http://dali.yangfankeji.com/Article/details/gtshoxbpbl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.meibo888.top/Article/details/gtjtpbgjjt.html

[Q78] 当前时间
来源：http://dali.cucudq.cn/Article/details/gtfccaowiq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenlongwang.top/Article/details/gtawhucunl.html

[Q79] 字符串拼接
来源：http://dali.tanke756.top/Article/details/gtrkpafppc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sysykeji.top/Article/details/gtpkwoocaq.html

[Q80] 字符串截取
来源：http://dali.hywenlv.cn/Article/details/gtcesmsbzi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtrxeykrwz.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gtvrcxcjed.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.smart0.xyz/Article/details/gtiektyjxx.html

[Q82] 字符长度与字节长度
来源：http://dali.jinqigfzy.top/Article/details/gtkmlxmqiw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtegbsaqpf.html

[Q83] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gtnkrtjaab.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtdnavzbuc.html

[Q84] 去除首尾空格
来源：http://dali.jinghuilouyu.cn/Article/details/gtynuzeghr.html

SELECT TRIM(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtulwtziwp.html

[Q85] 数值取整
来源：http://dali.havefunace.top/Article/details/gtbfhqyqex.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tianlin.xyz/Article/details/gtbmqrdajz.html

[Q86] 读取 JSON 字段
来源：http://dali.iojbl.cn/Article/details/gttlmapwzd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.andypj.xyz/Article/details/gtbhgmpzjz.html

[Q87] JSON 字段做条件
来源：http://dali.xuetiantiany.cn/Article/details/gtjfcrwuqk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aizwys.cn/Article/details/gtztgjkyld.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhoulong.xyz/Article/details/gtvdapspeq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sxryk.cn/Article/details/gtxmlasnui.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtgfpthfxs.html

[Q89] 判断表是否存在
来源：http://dali.zhixingplan.top/Article/details/gtcpvlzcub.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.0kj1m.cn/Article/details/gtxhsxkqkb.html

[Q90] 生成序号列
来源：http://dali.ppjwa.cn/Article/details/gtgtmjijch.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shzxlz.cn/Article/details/gtedqzezyp.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtngchoqmg.html

R. Bash 专题
来源：http://dali.sufxvd.cn/Article/details/gtqescxiwl.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtadordinz.html

[R01] shebang 与严格模式
来源：http://dali.yangfankeji.com/Article/details/gtpnnctpbl.html

#!/usr/bin/env bash
来源：http://dali.dashuyun.cn/Article/details/gtbschdkdb.html

set -euo pipefail
来源：http://dali.gogol.net.cn/Article/details/gtpltlinau.html

[R02] 变量赋值与使用
来源：http://dali.guowangkeji.top/Article/details/gtbjlgdmdh.html

name="Tom"; echo "$name"
来源：http://dali.yangfankeji.com/Article/details/gtpcutkezt.html

[R03] 只读变量
来源：http://dali.ppjwa.cn/Article/details/gtggawgtsf.html

readonly PI=3.14
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsktkldry.html

[R04] 位置参数
来源：http://dali.meibo888.top/Article/details/gtflfrtppi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gotoacloud.top/Article/details/gtaonjjqde.html

[R05] 参数默认值
来源：http://dali.mhx1999.top/Article/details/gtbwlmppop.html

name="${1:-default}"
来源：http://dali.aizwys.cn/Article/details/gtpzrmqcmi.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gtcxlujiss.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gttifrtnyb.html

[R07] if 判断文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtpearulkq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigufen.top/Article/details/gtpesegsil.html

[R08] 数值比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmsdcsup.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yonumen.top/Article/details/gtfbsfvkgn.html

[R09] 字符串比较
来源：http://dali.gotoacloud.top/Article/details/gtgfeqcvry.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfkztldd.html

[R10] 正则匹配
来源：http://dali.hongshengwenyu.top/Article/details/gttjqtagoe.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtggbnmddp.html

[R11] case 多分支
来源：http://dali.nanxinkj.top/Article/details/gtcbmfoxvf.html

case "$1" in
来源：http://dali.wangdashe.top/Article/details/gtfrswvvoo.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gtvkohudho.html

stop)  echo "停止" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtjyhhzjio.html

*)     echo "未知命令" ;;
来源：http://dali.aibaodan.cn/Article/details/gtdhktobdf.html

esac
来源：http://dali.jqgfzy.top/Article/details/gtkcbaagiq.html

[R12] for 遍历文件
来源：http://dali.ybcxt.top/Article/details/gtlzskosnq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.dianchejie.cn/Article/details/gtutjxfqmb.html

[R13] for 计数循环
来源：http://dali.0kj1m.cn/Article/details/gtgngrfjtk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.svipenyu.cn/Article/details/gtvuooocgs.html

[R14] C 风格 for
来源：http://dali.yongpay.top/Article/details/gtooazzvev.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gtemuniiln.html

[R15] while 逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtokktubyf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.guowangkeji.top/Article/details/gtqduwprdg.html

[R16] until 等待条件
来源：http://dali.xinyue.icu/Article/details/gtdfvlmifd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.aibaodan.cn/Article/details/gtotwqcopr.html

[R17] 数组定义与取值
来源：http://dali.bjfxy.top/Article/details/gtkhthugdr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhoulong.xyz/Article/details/gtbcwziehc.html

[R18] 遍历数组
来源：http://dali.chenjidiqi.icu/Article/details/gtmywgjpyx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ydzc1.top/Article/details/gtoyyrcacq.html

[R19] 数组长度
来源：http://dali.aizwys.cn/Article/details/gtnuawevdl.html

echo "${#arr[@]}"
来源：http://dali.gaohongyu789.top/Article/details/gtatlsiqpe.html

[R20] 关联数组（字典）
来源：http://dali.nanxinkj.top/Article/details/gtrhwzmplf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cdnleiting.top/Article/details/gtykqorgys.html

[R21] 字符串长度
来源：http://dali.fengsongda.top/Article/details/gtwwcvvekg.html

echo "${#s}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrollwrn.html

[R22] 截取子串
来源：http://dali.zycfv.cn/Article/details/gthcwfleon.html

echo "${s:0:5}"
来源：http://dali.zhongyouzk.top/Article/details/gtbqanvfsc.html

[R23] 字符串替换
来源：http://dali.zhongyouzk.top/Article/details/gtjhfqsakd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yangfankeji.com/Article/details/gtrppwtyrk.html

[R24] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gtuxbqttsm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.316326.xyz/Article/details/gtnmsjegfv.html

[R25] 去后缀 / 去前缀
来源：http://dali.9152youxi.cn/Article/details/gtziipdeno.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj20258.top/Article/details/gtbcdxgivq.html

[R26] 命令替换
来源：http://dali.iojbl.cn/Article/details/gtultufjfc.html

now=$(date +%F); echo "$now"
来源：http://dali.sufxvd.cn/Article/details/gtbeagcgxb.html

[R27] 算术展开
来源：http://dali.jiagoushi.top/Article/details/gtmwmeucuh.html

echo $((1 + 2 * 3))
来源：http://dali.wangshuangyany.cn/Article/details/gtdewluuvw.html

[R28] 浮点运算
来源：http://dali.316326.xyz/Article/details/gtypetwxfr.html

echo "scale=2; 10/3" | bc
来源：http://dali.9152youxi.cn/Article/details/gttlzegqpc.html

[R29] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gtqxphcsat.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yangfankeji.com/Article/details/gthjdbkygd.html

[R30] 函数返回状态码
来源：http://dali.fzhhl.top/Article/details/gtjcxsfiby.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhiwuduotai.top/Article/details/gtapimcnyp.html

[R31] 局部变量
来源：http://dali.wangdashe.top/Article/details/gtoqoxrniv.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtimznjdjt.html

[R32] 参数个数校验
来源：http://dali.ehwqpu.com/Article/details/gtubspziff.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtskvsuatt.html

[R33] 捕获错误并提示行号
来源：http://dali.yueranfly.top/Article/details/gtvlfcdcbu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guowangkeji.top/Article/details/gtrzpsbnou.html

[R34] 退出时清理
来源：http://dali.chenzaomai.com/Article/details/gtxrskogms.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuanzhike.top/Article/details/gtgqzfsvjs.html

[R35] 后台执行并等待
来源：http://dali.zycfv.cn/Article/details/gtkcjxulhg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjjuxwao.html

[R36] 并发执行多个任务
来源：http://dali.meibo888.top/Article/details/gtcfbflwxz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.wangshuangyany.cn/Article/details/gtoxkyokem.html

[R37] 把输出赋给变量
来源：http://dali.chenlongwang.top/Article/details/gtemhbdekr.html

files=$(ls -1)
来源：http://dali.snrcjt.cn/Article/details/gtmshjqayw.html

[R38] 管道串联
来源：http://dali.meibo888.top/Article/details/gtomaaatvp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zdqjudy.top/Article/details/gtbbrxfjnm.html

[R39] 重定向标准输出与错误
来源：http://dali.meibo888.top/Article/details/gtszocgbsd.html

cmd > out.log 2>&1
来源：http://dali.snrcjt.cn/Article/details/gtcozzawfs.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gtcajucmcj.html

echo "log" >> out.log
来源：http://dali.svipenyu.cn/Article/details/gthmbfmnme.html

[R41] 丢弃输出
来源：http://dali.ybcxt.top/Article/details/gtcqankspe.html

cmd >/dev/null 2>&1
来源：http://dali.hysaishi.cn/Article/details/gtgzvlzyrg.html

[R42] 输入重定向
来源：http://dali.daria6918.cn/Article/details/gtkrkulfuw.html

wc -l < a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtexkyjkat.html

[R43] 按名字查找文件
来源：http://dali.yuanzhike.top/Article/details/gtfbztfnwz.html

find . -name "*.log" -type f
来源：http://dali.dianchejie.cn/Article/details/gtqlovuxzu.html

[R44] 按修改时间查找
来源：http://dali.birdmap.top/Article/details/gtfvvafhsl.html

find . -mtime -7 -type f
来源：http://dali.sweek.top/Article/details/gttdloftpz.html

[R45] 批量删除
来源：http://dali.quarkkingdee.top/Article/details/gtahaucabn.html

find . -name "*.tmp" -delete
来源：http://dali.jinqigfzy.top/Article/details/gthejtxflo.html

[R46] 递归替换文件内容
来源：http://dali.yuxming.cn/Article/details/gtqbyxgzyp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zdqjudy.top/Article/details/gtfyrqqqpu.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumrqqecu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hammf.cn/Article/details/gthqtyetdr.html

[R48] awk 取指定列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtastdanho.html

awk '{print $1, $3}' a.txt
来源：http://dali.smart0.xyz/Article/details/gthbhzypmb.html

[R49] awk 带条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtncqmmnwg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hywenlv.cn/Article/details/gthghmzglb.html

[R50] awk 求和
来源：http://dali.jinqigufen.top/Article/details/gtwxvzdecr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtzygfhvin.html

[R51] 排序去重取前几
来源：http://dali.yangfankeji.com/Article/details/gtybmcfsjj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ydzc1.top/Article/details/gtfrgqlkvz.html

[R52] 统计行数
来源：http://dali.yuanzhike.top/Article/details/gtjlpxawmb.html

wc -l a.txt
来源：http://dali.sweek.top/Article/details/gtznrqfart.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtywpgsjab.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigfzy.top/Article/details/gtvptkpdfq.html

[R54] 比较两个文件
来源：http://dali.pengpengdd.cyou/Article/details/gtzvdiipca.html

diff a.txt b.txt
来源：http://dali.c1oappe.top/Article/details/gtmlzbnaoj.html

[R55] 压缩与解压
来源：http://dali.ehwqpu.com/Article/details/gticjfrutu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jianghu66.top/Article/details/gtwetstiin.html

[R56] 远程拷贝
来源：http://dali.c1oappe.top/Article/details/gtaqduonij.html

scp file user@host:/path/
来源：http://dali.andypj.xyz/Article/details/gtiyvgrmuy.html

[R57] 远程执行命令
来源：http://dali.gzhubu.top/Article/details/gteltrooez.html

ssh user@host 'uptime'
来源：http://dali.yuxming.cn/Article/details/gtllcmnsbj.html

[R58] 下载文件
来源：http://dali.fengsongda.top/Article/details/gtonimextp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jlsjyb.cn/Article/details/gtjisyvcdj.html

[R59] 发 POST JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtdvgyokwp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.0kj1m.cn/Article/details/gtallnztpd.html

[R60] 只看 HTTP 状态码
来源：http://dali.hysaishi.cn/Article/details/gtocnozrpn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jyoumei.cn/Article/details/gtkpxaylbl.html

[R61] 磁盘占用
来源：http://dali.hysaishi.cn/Article/details/gtrcyijdwc.html

df -h;  du -sh *
来源：http://dali.hysaishi.cn/Article/details/gttiypprvi.html

[R62] 找最占空间的文件
来源：http://dali.tanke756.top/Article/details/gtbynoxvue.html

du -ah . | sort -rh | head -10
来源：http://dali.chenzaomai.com/Article/details/gtpkpkwrkp.html

[R63] 内存与进程
来源：http://dali.jianghu66.top/Article/details/gtyylddwqe.html

free -h;  ps aux | grep nginx
来源：http://dali.shangyingyoupin.top/Article/details/gtbdfpagkg.html

[R64] 结束进程
来源：http://dali.hysaishi.cn/Article/details/gtmjwmybls.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gotoacloud.top/Article/details/gtxoogaqta.html

[R65] 查看端口占用
来源：http://dali.wangshuangyany.cn/Article/details/gtabsakxqk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhixingplan.top/Article/details/gtxopzqbqy.html

[R66] 定时任务
来源：http://dali.chenjidiqi.icu/Article/details/gtrwowpwwa.html

crontab -e;  crontab -l
来源：http://dali.feifeiyinyue.top/Article/details/gttplfxgqj.html

[R67] 生成随机十六进制串
来源：http://dali.jlsjyb.cn/Article/details/gtjxmsopol.html

openssl rand -hex 16
来源：http://dali.hnxiangtu.top/Article/details/gtesbjbtqv.html

[R68] 计算文件校验值
来源：http://dali.aibaodan.cn/Article/details/gtoshistgm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.0kj1m.cn/Article/details/gtqomanylv.html

[R69] 生成随机密码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttigmaviy.html

head -c 16 /dev/urandom | base64
来源：http://dali.gaohongyu789.top/Article/details/gttfgjdxgd.html

[R70] 时间戳与互转
来源：http://dali.yj20258.top/Article/details/gthgacaeku.html

date +%s;  date -d @1700000000
来源：http://dali.yanxiufei.cn/Article/details/gtoskcxizg.html

[R71] 日期格式化
来源：http://dali.havefunace.top/Article/details/gtqmykxwns.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hfpthk.cn/Article/details/gtmrcqmbjz.html

[R72] 等待端口就绪
来源：http://dali.pengpengdd.cyou/Article/details/gtnkvnnajc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gtzsbfqwif.html

[R73] 分割大日志
来源：http://dali.xinyue.icu/Article/details/gtrhzakfzh.html

split -l 1000 big.log part_
来源：http://dali.shangyingyoupin.top/Article/details/gttykbxvkb.html

[R74] 批量重命名
来源：http://dali.yj20258888.top/Article/details/gtssterwau.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxinkj.top/Article/details/gtuwtxgurq.html

[R75] 导出环境变量
来源：http://dali.cqqwz.cn/Article/details/gttudpkfxx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tianlin.xyz/Article/details/gtuqoynoiv.html

[R76] 使用临时文件
来源：http://dali.wangshuangyany.cn/Article/details/gtrdefwxhd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gtlbjaqoli.html

[R77] 读取用户输入
来源：http://dali.jiagoushi.top/Article/details/gtehyectuk.html

read -rp "请输入: " ans
来源：http://dali.c1oappe.top/Article/details/gtdmhhpcex.html

[R78] 交互式菜单
来源：http://dali.yj20258.top/Article/details/gtibnbtrvm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.mhx1999.top/Article/details/gtwkqngssl.html

[R79] 解析命令行选项
来源：http://dali.daria6918.cn/Article/details/gtoywxuyai.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gtahdcguhe.html

[R80] 查看脚本执行耗时
来源：http://dali.birdmap.top/Article/details/gtktegdcsz.html

time ./run.sh
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdherfmp.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtactpugog.html

S. C / C++ 专题
来源：http://dali.ivvv.top/Article/details/gtrevcrzqi.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtymrwdljn.html

[S01] C：Hello World
来源：http://dali.cheryme.top/Article/details/gtkoihabfl.html

#include <stdio.h>
来源：http://dali.chenlongwang.top/Article/details/gtibvqfrcq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.andypj.xyz/Article/details/gtltemcisp.html

[S02] C：变量与格式化输出
来源：http://dali.dianchejie.cn/Article/details/gtjvinvicl.html

int a = 10; printf("%d\n", a);
来源：http://dali.gogol.net.cn/Article/details/gtfgsbbkfu.html

[S03] C：读入整数
来源：http://dali.xziqi.cn/Article/details/gtamyjrutp.html


<!-- 参考信息 -->