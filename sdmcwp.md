代发 wailian999

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.quarkkingdee.top/Article/details/gtyweawemt.html

) t WHERE rn = 1;
来源：http://dali.c1oappe.top/Article/details/gtdgkdeyky.html

[Q35] 内连接
来源：http://dali.gogol.net.cn/Article/details/gtxvxhormq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqubdzwba.html

[Q36] 左连接
来源：http://dali.hywenlv.cn/Article/details/gtsoribicl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuetiantiany.cn/Article/details/gtggnubkfg.html

[Q37] 右连接
来源：http://dali.shangyingyoupin.top/Article/details/gtfeeunmoq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrhporifc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.smart0.xyz/Article/details/gtqcxoltln.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtoqjhcyeu.html

[Q39] 自连接（查上下级）
来源：http://dali.hywenlv.cn/Article/details/gtbkzaqqrd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.iojbl.cn/Article/details/gtvdgybjmh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfvzafln.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jqgfzy.top/Article/details/gtgytregbh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.svipenyu.cn/Article/details/gtffsxaydy.html

[Q41] 多表连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcujhmxjk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenzaomai.com/Article/details/gtcycfuuld.html

JOIN users u ON u.id = o.user_id
来源：http://dali.iojbl.cn/Article/details/gtzummblpe.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhoulong.xyz/Article/details/gtslvwnmhx.html

[Q42] 连接条件附加过滤
来源：http://dali.ydzc1.top/Article/details/gtmsjgxqfe.html

SELECT u.name, o.amount FROM users u
来源：http://dali.0kj1m.cn/Article/details/gtvqgvsbwi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.kuanghao11.cn/Article/details/gtqykwxjgi.html

[Q43] 标量子查询
来源：http://dali.tian-w.cn/Article/details/gtfxzzztmk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yj20258888.top/Article/details/gteeoabtik.html

[Q44] IN 子查询
来源：http://dali.fzhhl.top/Article/details/gtgartbckm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nwbrower.top/Article/details/gthzdsckaj.html

[Q45] EXISTS 判断存在
来源：http://dali.daria6918.cn/Article/details/gtzokhnxjh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gtvxjfehqe.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sxryk.cn/Article/details/gtzogvnikt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gtegazuzvr.html

[Q47] 与平均值比较
来源：http://dali.shzxlz.cn/Article/details/gtwhwbbcog.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgfzy.top/Article/details/gtjiraxmvm.html

[Q48] CTE 公用表表达式
来源：http://dali.guannengcc.top/Article/details/gtuttiforr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.c1oappe.top/Article/details/gttqsddxxk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.haohaochexian.top/Article/details/gtparzahnr.html

[Q49] 更新单行
来源：http://dali.zhongyouzk.top/Article/details/gtwiscjywj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxinkj.top/Article/details/gtrkynkqtq.html

[Q50] 批量更新
来源：http://dali.jinqigufen.top/Article/details/gtoqrihjeq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.iojbl.cn/Article/details/gtpodqgiqd.html

[Q51] 用子查询更新
来源：http://dali.haohaochexian.top/Article/details/gtssofmmrp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtpvqmqwmu.html

[Q52] 删除指定行
来源：http://dali.yangfankeji.com/Article/details/gtnyfjahuo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gotoacloud.top/Article/details/gtqvkbeuwe.html

[Q53] 按条件删除
来源：http://dali.havefunace.top/Article/details/gtbrllzvgk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sysykeji.top/Article/details/gtrezouqnd.html

[Q54] 清空表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkihjetp.html

TRUNCATE TABLE logs;
来源：http://dali.nanxinkj.top/Article/details/gtrdkiwzpl.html

[Q55] 排名（并列占位）
来源：http://dali.yueranfly.top/Article/details/gtrpwerkdc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gttacyzylt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigfzy.top/Article/details/gtiiclyvks.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.redwolf501.top/Article/details/gtfuzefjye.html

[Q57] 行号
来源：http://dali.svipenyu.cn/Article/details/gtolpokhio.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtnfawestx.html

[Q58] 累计求和
来源：http://dali.yuanzhike.top/Article/details/gtyhhafusu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtkxofpssx.html

[Q59] 分组内累计
来源：http://dali.sxryk.cn/Article/details/gtwbxzqfop.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtmehbkvye.html

[Q60] 取上一行 / 下一行
来源：http://dali.tianlin.xyz/Article/details/gtyrzracvh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sysykeji.top/Article/details/gteqyjhdtn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtpefjhueb.html

[Q61] 移动平均
来源：http://dali.yuxming.cn/Article/details/gtxivyonom.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtkoaypgyd.html

[Q62] 分组占比
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixnvmiiu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gtvpovhecj.html

[Q63] 开启事务
来源：http://dali.yanxiufei.cn/Article/details/gtykvqcanh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigufen.top/Article/details/gtpnwktwir.html

[Q64] 提交事务
来源：http://dali.tanke756.top/Article/details/gtvstbcejs.html

COMMIT;
来源：http://dali.bjfxy.top/Article/details/gtxexyedqi.html

[Q65] 回滚事务
来源：http://dali.snrcjt.cn/Article/details/gtloehiwja.html

ROLLBACK;
来源：http://dali.havefunace.top/Article/details/gtqcjbojhu.html

[Q66] 行锁查询
来源：http://dali.yj20258888.top/Article/details/gtlynydkpa.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj202588.top/Article/details/gtmvpzledc.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuigntixw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.c1oappe.top/Article/details/gtcipjqsnc.html

[Q68] 保存点
来源：http://dali.hammf.cn/Article/details/gtrmspcutn.html

SAVEPOINT sp1;
来源：http://dali.yanxiufei.cn/Article/details/gtasnienql.html

ROLLBACK TO sp1;
来源：http://dali.birdmap.top/Article/details/gtucvpadgq.html

[Q69] 查看执行计划
来源：http://dali.ydzc1.top/Article/details/gtffmoocji.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hysaishi.cn/Article/details/gtqvwbrpfk.html

[Q70] 更新统计信息
来源：http://dali.cucudq.cn/Article/details/gtnheoifah.html

ANALYZE TABLE users;
来源：http://dali.iojbl.cn/Article/details/gtoqwzuwzs.html

[Q71] 查看建表语句
来源：http://dali.shangyingyoupin.top/Article/details/gtsmjaepde.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticminypd.html

[Q72] 查看索引
来源：http://dali.gzhubu.top/Article/details/gtmcnyluit.html

SHOW INDEX FROM users;
来源：http://dali.daria6918.cn/Article/details/gttbfpupce.html

[Q73] 查看表状态
来源：http://dali.dianchejie.cn/Article/details/gtimnljplv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zycfv.cn/Article/details/gttlejmgwy.html

[Q74] 强制使用索引
来源：http://dali.zhoulong.xyz/Article/details/gtlzuhbsji.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhiwuduotai.top/Article/details/gtehmoputr.html

[Q75] 日期格式化
来源：http://dali.daria6918.cn/Article/details/gtfkwwoqte.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtzqowvaww.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tanke756.top/Article/details/gtchqqfbwq.html

[Q76] 按天统计
来源：http://dali.hfpthk.cn/Article/details/gtyuihldvb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gotoacloud.top/Article/details/gtmiuzubcr.html

[Q77] 时间加减
来源：http://dali.aibaodan.cn/Article/details/gtxzorsgww.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.aizwys.cn/Article/details/gtpzukjaxg.html

[Q78] 当前时间
来源：http://dali.316326.xyz/Article/details/gtrtvrnxax.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ivvv.top/Article/details/gtrigndxih.html

[Q79] 字符串拼接
来源：http://dali.jinqigufen.top/Article/details/gtkvoqlxcp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sufxvd.cn/Article/details/gtcdvhdwdb.html

[Q80] 字符串截取
来源：http://dali.jlsjyb.cn/Article/details/gtralyfood.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtnxcfjzby.html

[Q81] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gtuqcghefu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nwbrower.top/Article/details/gtxikemhcv.html

[Q82] 字符长度与字节长度
来源：http://dali.chenjidiqi.icu/Article/details/gtbgwywlex.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtrgxupklo.html

[Q83] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gtacuwtsnd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtesinylvi.html

[Q84] 去除首尾空格
来源：http://dali.hnxiangtu.top/Article/details/gtglxalzxj.html

SELECT TRIM(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtkxpfubfp.html

[Q85] 数值取整
来源：http://dali.haohaochexian.top/Article/details/gtmfxkcgku.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.bjfxy.top/Article/details/gtqafzyapy.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigufen.top/Article/details/gtfhuzxgnk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajalpouk.html

[Q87] JSON 字段做条件
来源：http://dali.cdnleiting.top/Article/details/gtrrwzkdes.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.smart0.xyz/Article/details/gttfuhkbpe.html

[Q88] 行转列（条件聚合）
来源：http://dali.guowangkeji.top/Article/details/gtpvrxsxni.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yvedp.cn/Article/details/gtjxqvkxfq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daria6918.cn/Article/details/gtbksexheb.html

[Q89] 判断表是否存在
来源：http://dali.gogol.net.cn/Article/details/gthoxomzhr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shuidangran.top/Article/details/gtbhxkerid.html

[Q90] 生成序号列
来源：http://dali.zdqjudy.top/Article/details/gtveteyckd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnqzz.top/Article/details/gtnaoapqej.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtfzqzvxmw.html

R. Bash 专题
来源：http://dali.cqqwz.cn/Article/details/gtvayijmoa.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtoviidtsy.html

[R01] shebang 与严格模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugzzjlpp.html

#!/usr/bin/env bash
来源：http://dali.jlsjyb.cn/Article/details/gtxyejxnla.html

set -euo pipefail
来源：http://dali.ppjwa.cn/Article/details/gtffdsqwyg.html

[R02] 变量赋值与使用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlygnkzur.html

name="Tom"; echo "$name"
来源：http://dali.pycfn.com/Article/details/gtmjoqfmja.html

[R03] 只读变量
来源：http://dali.hnxiangtu.top/Article/details/gtzioplmda.html

readonly PI=3.14
来源：http://dali.hammf.cn/Article/details/gticvxwtxk.html

[R04] 位置参数
来源：http://dali.yangfankeji.com/Article/details/gtynapozna.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ybcxt.top/Article/details/gtqiqomaxw.html

[R05] 参数默认值
来源：http://dali.nanxinkj.top/Article/details/gtawkcqfkh.html

name="${1:-default}"
来源：http://dali.tianlin.xyz/Article/details/gtabzihxpu.html

[R06] 判断命令是否存在
来源：http://dali.xinyue.icu/Article/details/gtfwgkkjoc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gttgdhcpop.html

[R07] if 判断文件
来源：http://dali.kuanghao11.cn/Article/details/gtvhxqxjyd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj20258888.top/Article/details/gtpjutihly.html

[R08] 数值比较
来源：http://dali.316326.xyz/Article/details/gtknsiwpcl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtalgokvbm.html

[R09] 字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtagyjfhsu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.smart0.xyz/Article/details/gtvhmxvfag.html

[R10] 正则匹配
来源：http://dali.316326.xyz/Article/details/gtklwbshgp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgfzy.top/Article/details/gtgrfthgtj.html

[R11] case 多分支
来源：http://dali.cdnleiting.top/Article/details/gtxzjdefxf.html

case "$1" in
来源：http://dali.jqgfzy.top/Article/details/gtrjsunfwv.html

start) echo "启动" ;;
来源：http://dali.zycfv.cn/Article/details/gtdwtyhekv.html

stop)  echo "停止" ;;
来源：http://dali.yj20258.top/Article/details/gtlmriribq.html

*)     echo "未知命令" ;;
来源：http://dali.andypj.xyz/Article/details/gtbltkjgaz.html

esac
来源：http://dali.zhengqikj.top/Article/details/gtvvzkhcyi.html

[R12] for 遍历文件
来源：http://dali.xziqi.cn/Article/details/gtttesrpsy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yangfankeji.com/Article/details/gtpfiewmdq.html

[R13] for 计数循环
来源：http://dali.pengpengdd.cyou/Article/details/gtjaoxeqqc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tianlin.xyz/Article/details/gtlxyhszgq.html

[R14] C 风格 for
来源：http://dali.havefunace.top/Article/details/gtzibdnvir.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tianlin.xyz/Article/details/gtybgjbdxe.html

[R15] while 逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtgkruwogh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ybcxt.top/Article/details/gtztbvdffi.html

[R16] until 等待条件
来源：http://dali.nanxuanxn.top/Article/details/gtojjcewhc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.9152youxi.cn/Article/details/gthsqmrtof.html

[R17] 数组定义与取值
来源：http://dali.hysaishi.cn/Article/details/gtwletphab.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shzxlz.cn/Article/details/gthqmfzdnq.html

[R18] 遍历数组
来源：http://dali.wangshuangyany.cn/Article/details/gtguaibyoq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xinyue.icu/Article/details/gtnkrejzjj.html

[R19] 数组长度
来源：http://dali.cashguo.top/Article/details/gtqqebjcfd.html

echo "${#arr[@]}"
来源：http://dali.iojbl.cn/Article/details/gtzukvbosf.html

[R20] 关联数组（字典）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbocuwwwf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xziqi.cn/Article/details/gtrzstcevm.html

[R21] 字符串长度
来源：http://dali.jianghu66.top/Article/details/gtjlolgstq.html

echo "${#s}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddikzpuj.html

[R22] 截取子串
来源：http://dali.feifeiyinyue.top/Article/details/gtjnchcmsp.html

echo "${s:0:5}"
来源：http://dali.hongshengwenyu.top/Article/details/gtsdxktefp.html

[R23] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gtgrrisdpc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cashguo.top/Article/details/gtskxlqjkh.html

[R24] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gtasczvsnp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.dashuyun.cn/Article/details/gtxuwzshnx.html

[R25] 去后缀 / 去前缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtopyfeabe.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cheryme.top/Article/details/gtqxmeyvsx.html

[R26] 命令替换
来源：http://dali.sweek.top/Article/details/gtgyprweqp.html

now=$(date +%F); echo "$now"
来源：http://dali.meibo888.top/Article/details/gtemixzmng.html

[R27] 算术展开
来源：http://dali.cucudq.cn/Article/details/gtzimsmsrf.html

echo $((1 + 2 * 3))
来源：http://dali.ppjwa.cn/Article/details/gtymdpkmiy.html

[R28] 浮点运算
来源：http://dali.kuanghao11.cn/Article/details/gteggbnfpp.html

echo "scale=2; 10/3" | bc
来源：http://dali.sysykeji.top/Article/details/gtonckeeyy.html

[R29] 定义函数
来源：http://dali.ehwqpu.com/Article/details/gtkqzqeniu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.316326.xyz/Article/details/gthtmvxoio.html

[R30] 函数返回状态码
来源：http://dali.daxiang520.top/Article/details/gtlmkxfwuq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhongyouzk.top/Article/details/gtdakherde.html

[R31] 局部变量
来源：http://dali.cashguo.top/Article/details/gtpecjmihd.html

f() { local x=1; echo "$x"; }
来源：http://dali.fengsongda.top/Article/details/gtrgvjbtjl.html

[R32] 参数个数校验
来源：http://dali.chenzaomai.com/Article/details/gtuijzyycy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmwnnozg.html

[R33] 捕获错误并提示行号
来源：http://dali.kuanghao11.cn/Article/details/gtdezqepzd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yonumen.top/Article/details/gtftncflra.html

[R34] 退出时清理
来源：http://dali.yueranfly.top/Article/details/gtzsmpjkse.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gtkwmcndwx.html

[R35] 后台执行并等待
来源：http://dali.gaohongyu789.top/Article/details/gtxmcyiwza.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhengqikj.top/Article/details/gtiznlzguo.html

[R36] 并发执行多个任务
来源：http://dali.hfpthk.cn/Article/details/gtpwgrcurn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.andypj.xyz/Article/details/gtpxopoegr.html

[R37] 把输出赋给变量
来源：http://dali.yj20258888.top/Article/details/gtvyhafugv.html

files=$(ls -1)
来源：http://dali.yanxiufei.cn/Article/details/gtkrnsysop.html

[R38] 管道串联
来源：http://dali.tanke756.top/Article/details/gtnotffvpf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.quarkkingdee.top/Article/details/gtgvplygjy.html

[R39] 重定向标准输出与错误
来源：http://dali.andypj.xyz/Article/details/gtezwkwugo.html

cmd > out.log 2>&1
来源：http://dali.hammf.cn/Article/details/gtotunwbnv.html

[R40] 追加写日志
来源：http://dali.havefunace.top/Article/details/gtoprrkisc.html

echo "log" >> out.log
来源：http://dali.wangshuangyany.cn/Article/details/gtolvlsgvu.html

[R41] 丢弃输出
来源：http://dali.sufxvd.cn/Article/details/gtyvrvkgsx.html

cmd >/dev/null 2>&1
来源：http://dali.yuanzhike.top/Article/details/gtopmvirac.html

[R42] 输入重定向
来源：http://dali.hysaishi.cn/Article/details/gtpcqwuoaz.html

wc -l < a.txt
来源：http://dali.cheryme.top/Article/details/gtvrdqaszt.html

[R43] 按名字查找文件
来源：http://dali.hysaishi.cn/Article/details/gtpmhlebyz.html

find . -name "*.log" -type f
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbknvjlcr.html

[R44] 按修改时间查找
来源：http://dali.hywenlv.cn/Article/details/gtknrdjsjq.html

find . -mtime -7 -type f
来源：http://dali.hywenlv.cn/Article/details/gtkkxwfzjm.html

[R45] 批量删除
来源：http://dali.zhengqikj.top/Article/details/gtnyhgdvuw.html

find . -name "*.tmp" -delete
来源：http://dali.yuxming.cn/Article/details/gtfrlcoqms.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhartqwn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.pycfn.com/Article/details/gtqzobrqzk.html

[R47] sed 单行替换
来源：http://dali.guowangkeji.top/Article/details/gtngtlkwjz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ybcxt.top/Article/details/gtaurmmqdr.html

[R48] awk 取指定列
来源：http://dali.yj20258.top/Article/details/gtvlottxyh.html

awk '{print $1, $3}' a.txt
来源：http://dali.smart0.xyz/Article/details/gtnazsrpyg.html

[R49] awk 带条件
来源：http://dali.zhixingplan.top/Article/details/gtqisgcqdx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj202588.top/Article/details/gtlhpydyzv.html

[R50] awk 求和
来源：http://dali.guannengcc.top/Article/details/gtgqybzsuh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtyigifjmw.html

[R51] 排序去重取前几
来源：http://dali.cucudq.cn/Article/details/gtnmkfombi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuxming.cn/Article/details/gtpzplbgps.html

[R52] 统计行数
来源：http://dali.xziqi.cn/Article/details/gtimdkbtsd.html

wc -l a.txt
来源：http://dali.guannengcc.top/Article/details/gtofrtabsu.html

[R53] 查看文件头与实时尾
来源：http://dali.tanke756.top/Article/details/gtrpulwdyb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shzxlz.cn/Article/details/gtltkueers.html

[R54] 比较两个文件
来源：http://dali.hnqzz.top/Article/details/gtohzramrt.html

diff a.txt b.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtmlwgnrxd.html

[R55] 压缩与解压
来源：http://dali.jianghu66.top/Article/details/gtlshqnuib.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shangyingyoupin.top/Article/details/gtqserxasr.html

[R56] 远程拷贝
来源：http://dali.redwolf501.top/Article/details/gtjrgmlvzj.html

scp file user@host:/path/
来源：http://dali.guowangkeji.top/Article/details/gtcgcyiyow.html

[R57] 远程执行命令
来源：http://dali.jlsjyb.cn/Article/details/gtxinafhxi.html

ssh user@host 'uptime'
来源：http://dali.jlsjyb.cn/Article/details/gtyosfocta.html

[R58] 下载文件
来源：http://dali.yvedp.cn/Article/details/gtnsgamahm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxuanxn.top/Article/details/gtzedxcgee.html

[R59] 发 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtbbhzjfdj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ivvv.top/Article/details/gtokpwimbd.html

[R60] 只看 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gtinrzcawt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yuanzhike.top/Article/details/gtcaujkhkr.html

[R61] 磁盘占用
来源：http://dali.hfpthk.cn/Article/details/gtdflkavrp.html

df -h;  du -sh *
来源：http://dali.quarkkingdee.top/Article/details/gtxnjuvbwx.html

[R62] 找最占空间的文件
来源：http://dali.ydzc1.top/Article/details/gtelyfbeit.html

du -ah . | sort -rh | head -10
来源：http://dali.haohaochexian.top/Article/details/gtsoxbkzsy.html

[R63] 内存与进程
来源：http://dali.jinghuilouyu.cn/Article/details/gtpovtayam.html

free -h;  ps aux | grep nginx
来源：http://dali.quarkkingdee.top/Article/details/gtwqlmlpso.html

[R64] 结束进程
来源：http://dali.hongshengwenyu.top/Article/details/gtkjuizhem.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ehwqpu.com/Article/details/gtvlmruivh.html

[R65] 查看端口占用
来源：http://dali.jiagoushi.top/Article/details/gtjqnrvybq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuetiantiany.cn/Article/details/gtyequaopr.html

[R66] 定时任务
来源：http://dali.316326.xyz/Article/details/gtgnnasjve.html

crontab -e;  crontab -l
来源：http://dali.ivvv.top/Article/details/gtmoarzhsg.html

[R67] 生成随机十六进制串
来源：http://dali.aibaodan.cn/Article/details/gtmfwwgzgi.html

openssl rand -hex 16
来源：http://dali.dianchejie.cn/Article/details/gtpccnerob.html

[R68] 计算文件校验值
来源：http://dali.zhoulong.xyz/Article/details/gtvjwikrjm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ybcxt.top/Article/details/gtzevxfssg.html

[R69] 生成随机密码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzlyghmp.html

head -c 16 /dev/urandom | base64
来源：http://dali.bjfxy.top/Article/details/gtmztqxbhn.html

[R70] 时间戳与互转
来源：http://dali.haohaochexian.top/Article/details/gtsvonphka.html

date +%s;  date -d @1700000000
来源：http://dali.dashuyun.cn/Article/details/gtidlmbhmo.html

[R71] 日期格式化
来源：http://dali.yueranfly.top/Article/details/gtvkdcfvhb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cashguo.top/Article/details/gtuewgsekm.html

[R72] 等待端口就绪
来源：http://dali.tanke756.top/Article/details/gtwtopogvd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gtmnscxufh.html

[R73] 分割大日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjrklwny.html

split -l 1000 big.log part_
来源：http://dali.daxiang520.top/Article/details/gtdhzdodzk.html

[R74] 批量重命名
来源：http://dali.svipenyu.cn/Article/details/gttuhbvvdc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.redwolf501.top/Article/details/gttdcbzilz.html

[R75] 导出环境变量
来源：http://dali.zhengqikj.top/Article/details/gtqtgepgio.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.redwolf501.top/Article/details/gtfltcoguz.html

[R76] 使用临时文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbyodgbru.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gtomkxdyom.html

[R77] 读取用户输入
来源：http://dali.hywenlv.cn/Article/details/gtjxtwtszi.html

read -rp "请输入: " ans
来源：http://dali.yuanzhike.top/Article/details/gtzxlfvcxj.html

[R78] 交互式菜单
来源：http://dali.hysaishi.cn/Article/details/gtoihkgcim.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigfzy.top/Article/details/gtnlsimfie.html

[R79] 解析命令行选项
来源：http://dali.dianchejie.cn/Article/details/gtnpusjqkh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daria6918.cn/Article/details/gtqgzrxvxv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhixingplan.top/Article/details/gtmhzfdgfa.html

time ./run.sh
来源：http://dali.hfpthk.cn/Article/details/gtydksdjzp.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtsjeceghq.html

S. C / C++ 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gtsanjugrm.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtxxccheda.html

[S01] C：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtrnxygdaa.html

#include <stdio.h>
来源：http://dali.jinqigfzy.top/Article/details/gtnwstrutn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shuidangran.top/Article/details/gtfufeofsy.html

[S02] C：变量与格式化输出
来源：http://dali.yongpay.top/Article/details/gtwwyqlabh.html

int a = 10; printf("%d\n", a);
来源：http://dali.xylfe.cn/Article/details/gtckzwopwx.html

[S03] C：读入整数
来源：http://dali.daxiang520.top/Article/details/gtlxkonaui.html


<!-- 参考信息 -->