代发 wailian999

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xziqi.cn/Article/details/gtdczykkkt.html

[Q22] 排序
来源：http://dali.vqdsnc.cn/Article/details/gtyhhxkqlr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cheryme.top/Article/details/gtwecbohaf.html

[Q23] 分页
来源：http://dali.tian-w.cn/Article/details/gtamlxspxo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gzhubu.top/Article/details/gtrobibngz.html

[Q24] 去重
来源：http://dali.xinyue.icu/Article/details/gtswpvfrdp.html

SELECT DISTINCT city FROM users;
来源：http://dali.andypj.xyz/Article/details/gtjajbvhpe.html

[Q25] 只取前 N 条
来源：http://dali.hywenlv.cn/Article/details/gtzjjrzust.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.guannengcc.top/Article/details/gtnozfxzfs.html

[Q26] 计数
来源：http://dali.xylfe.cn/Article/details/gtntwtmwml.html

SELECT COUNT(*) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtjxuokkoh.html

[Q27] 条件计数
来源：http://dali.cqqwz.cn/Article/details/gtcildxlmh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtrpvejuch.html

[Q28] 求和与平均
来源：http://dali.andypj.xyz/Article/details/gtzzwntbdm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gttwvzhxuj.html

[Q29] 最大最小值
来源：http://dali.redwolf501.top/Article/details/gtebtqegyp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj20258.top/Article/details/gtinagmmgw.html

[Q30] 分组统计
来源：http://dali.daxiang520.top/Article/details/gtqoaqvruj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gtgqalisyn.html

[Q31] 分组后过滤
来源：http://dali.ybcxt.top/Article/details/gtworoiiwt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yongpay.top/Article/details/gtpiicarel.html

[Q32] 分组拼接字符串
来源：http://dali.meibo888.top/Article/details/gtpckgydlp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gtopbmvmfg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258.top/Article/details/gtlymupejh.html

[Q33] 多列分组
来源：http://dali.ppjwa.cn/Article/details/gtrzszckkj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.vqdsnc.cn/Article/details/gtamplqbtr.html

[Q34] 每组取第一条
来源：http://dali.daxiang520.top/Article/details/gtcsngdgvz.html

SELECT * FROM (
来源：http://dali.fzhhl.top/Article/details/gtmivfplbh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hywenlv.cn/Article/details/gthzrjlfvn.html

) t WHERE rn = 1;
来源：http://dali.yvedp.cn/Article/details/gtpuieeosp.html

[Q35] 内连接
来源：http://dali.hfpthk.cn/Article/details/gtidoouxgn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkduhvluv.html

[Q36] 左连接
来源：http://dali.chenzaomai.com/Article/details/gttamjjwxf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gtcqfvjcws.html

[Q37] 右连接
来源：http://dali.jinqigfzy.top/Article/details/gtnjocgedb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuanzhike.top/Article/details/gtxnocqans.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.bjfxy.top/Article/details/gttujjxamz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.c1oappe.top/Article/details/gtbmgkzfvq.html

[Q39] 自连接（查上下级）
来源：http://dali.daxiang520.top/Article/details/gthjzoautf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yanxiufei.cn/Article/details/gtqvjspqvi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenjidiqi.icu/Article/details/gtgxqknynw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zycfv.cn/Article/details/gtwqewosag.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.snrcjt.cn/Article/details/gtfimjvthm.html

[Q41] 多表连接
来源：http://dali.fengsongda.top/Article/details/gtnqpdylbc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jiagoushi.top/Article/details/gtlljzxgyr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.wangshuangyany.cn/Article/details/gtztnsqgdx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.havefunace.top/Article/details/gtujivpdon.html

[Q42] 连接条件附加过滤
来源：http://dali.mhx1999.top/Article/details/gtneibbfcf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yongpay.top/Article/details/gtkgsspukp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fzhhl.top/Article/details/gtvckfyets.html

[Q43] 标量子查询
来源：http://dali.hammf.cn/Article/details/gtoehqqxml.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cqqwz.cn/Article/details/gtvrcfswdx.html

[Q44] IN 子查询
来源：http://dali.fzhhl.top/Article/details/gtownrsxsq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.feifeiyinyue.top/Article/details/gtplnqhycu.html

[Q45] EXISTS 判断存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtashvzldh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gtuwlgyskc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.meibo888.top/Article/details/gtroyuwurh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhoulong.xyz/Article/details/gtumymzdos.html

[Q47] 与平均值比较
来源：http://dali.jinqigufen.top/Article/details/gtapotnfgd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangtech.top/Article/details/gtytlgzlha.html

[Q48] CTE 公用表表达式
来源：http://dali.yuanzhike.top/Article/details/gtieoiakna.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cqqwz.cn/Article/details/gtinedxkdj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.pengpengdd.cyou/Article/details/gtxxenzhdu.html

[Q49] 更新单行
来源：http://dali.nanxinkj.top/Article/details/gttxvzszrf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gtkarznrrp.html

[Q50] 批量更新
来源：http://dali.daxiang520.top/Article/details/gtgygzpouv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj202588.top/Article/details/gttwwgbzfa.html

[Q51] 用子查询更新
来源：http://dali.jyoumei.cn/Article/details/gtvtsywpmo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.dashuyun.cn/Article/details/gtczhjyjfj.html

[Q52] 删除指定行
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpcylzuw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gtejbzszey.html

[Q53] 按条件删除
来源：http://dali.haohaochexian.top/Article/details/gtxugyiaas.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gotoacloud.top/Article/details/gtnzfsyzso.html

[Q54] 清空表
来源：http://dali.yuxming.cn/Article/details/gtlbytvdxn.html

TRUNCATE TABLE logs;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjchrvctl.html

[Q55] 排名（并列占位）
来源：http://dali.yangfankeji.com/Article/details/gtuxlpauwt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.andypj.xyz/Article/details/gtalyhdgit.html

[Q56] 密集排名（并列不占位）
来源：http://dali.vqdsnc.cn/Article/details/gtusthujwq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xziqi.cn/Article/details/gtinimlgif.html

[Q57] 行号
来源：http://dali.zhoulong.xyz/Article/details/gtkfojjspr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtrtykzfou.html

[Q58] 累计求和
来源：http://dali.guannengcc.top/Article/details/gthmmlnzas.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtminuuumy.html

[Q59] 分组内累计
来源：http://dali.nwbrower.top/Article/details/gtzozsgtax.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtzobaocnv.html

[Q60] 取上一行 / 下一行
来源：http://dali.cdnleiting.top/Article/details/gtymebkjqm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.feifeiyinyue.top/Article/details/gtulpkacgn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjhgoxao.html

[Q61] 移动平均
来源：http://dali.ybcxt.top/Article/details/gtcdykcrvv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtqyhnwzna.html

[Q62] 分组占比
来源：http://dali.aibaodan.cn/Article/details/gttwnivvln.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtyezhpast.html

[Q63] 开启事务
来源：http://dali.aizwys.cn/Article/details/gtvqybdaqe.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sxryk.cn/Article/details/gtrwiploeu.html

[Q64] 提交事务
来源：http://dali.havefunace.top/Article/details/gtjlzisqzx.html

COMMIT;
来源：http://dali.yueranfly.top/Article/details/gtegdxxzbm.html

[Q65] 回滚事务
来源：http://dali.cqqwz.cn/Article/details/gtjrjqioue.html

ROLLBACK;
来源：http://dali.zhongyouzk.top/Article/details/gtiohxbeeg.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gtqwkxaeco.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ivvv.top/Article/details/gtjszczwgv.html

[Q67] 设置隔离级别
来源：http://dali.wangshuangyany.cn/Article/details/gtsnwtnkgp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hnxiangtu.top/Article/details/gtvetylbsy.html

[Q68] 保存点
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzwdkhpj.html

SAVEPOINT sp1;
来源：http://dali.zdqjudy.top/Article/details/gtmoqyyxls.html

ROLLBACK TO sp1;
来源：http://dali.pengpengdd.cyou/Article/details/gtwbrsuqbh.html

[Q69] 查看执行计划
来源：http://dali.gotoacloud.top/Article/details/gtfteimtad.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenzaomai.com/Article/details/gtfrqrijbh.html

[Q70] 更新统计信息
来源：http://dali.shzxlz.cn/Article/details/gtfqpvdbwf.html

ANALYZE TABLE users;
来源：http://dali.sweek.top/Article/details/gthruluxdj.html

[Q71] 查看建表语句
来源：http://dali.chenzaomai.com/Article/details/gtwiyvzclc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hnxiangtu.top/Article/details/gtllutzeld.html

[Q72] 查看索引
来源：http://dali.tianlin.xyz/Article/details/gtrscfjljf.html

SHOW INDEX FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtssqvbegi.html

[Q73] 查看表状态
来源：http://dali.zhixingplan.top/Article/details/gtjwuaudrp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.andypj.xyz/Article/details/gttwdntowt.html

[Q74] 强制使用索引
来源：http://dali.yuxming.cn/Article/details/gtkftkfeav.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hysaishi.cn/Article/details/gtovthvbsj.html

[Q75] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gtytfgnefv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtmxnhhffo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.svipenyu.cn/Article/details/gtizxdpvkm.html

[Q76] 按天统计
来源：http://dali.gotoacloud.top/Article/details/gtnuntktij.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yanxiufei.cn/Article/details/gtiflclemz.html

[Q77] 时间加减
来源：http://dali.sweek.top/Article/details/gtnfphztyt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dianchejie.cn/Article/details/gtpeluueuc.html

[Q78] 当前时间
来源：http://dali.yj20258.top/Article/details/gtexfocewl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxuanxn.top/Article/details/gtnpvbdehh.html

[Q79] 字符串拼接
来源：http://dali.feifeiyinyue.top/Article/details/gtxchgpjun.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gogol.net.cn/Article/details/gtfwfjbrhu.html

[Q80] 字符串截取
来源：http://dali.jqgufenzy.top/Article/details/gtzuwvedvu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtxkjenxlt.html

[Q81] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gtnakysesg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shuidangran.top/Article/details/gtsgxbwhbs.html

[Q82] 字符长度与字节长度
来源：http://dali.zhiwuduotai.top/Article/details/gthpssaoiw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gttsjnsfbj.html

[Q83] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gtlyphroyi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtmmvbkqdu.html

[Q84] 去除首尾空格
来源：http://dali.hnxiangtu.top/Article/details/gtthcabaxm.html

SELECT TRIM(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtqxktrzsq.html

[Q85] 数值取整
来源：http://dali.jiagoushi.top/Article/details/gtfnlzepwc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jyoumei.cn/Article/details/gtaiunugkb.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258.top/Article/details/gtxfpkrhhr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zdqjudy.top/Article/details/gtzkxxjinq.html

[Q87] JSON 字段做条件
来源：http://dali.quarkkingdee.top/Article/details/gtodkxkzia.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zdqjudy.top/Article/details/gtvrknlcmf.html

[Q88] 行转列（条件聚合）
来源：http://dali.pengpengdd.cyou/Article/details/gtfmudmwfg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.smart0.xyz/Article/details/gtwvhryski.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtbfyicshs.html

[Q89] 判断表是否存在
来源：http://dali.yj20258.top/Article/details/gtociyxcur.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tian-w.cn/Article/details/gtrmljzfpa.html

[Q90] 生成序号列
来源：http://dali.snrcjt.cn/Article/details/gthkojmnqu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yuxming.cn/Article/details/gteywpcepa.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtlixnwmeq.html

R. Bash 专题
来源：http://dali.316326.xyz/Article/details/gtuiksjydr.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtryfizuxe.html

[R01] shebang 与严格模式
来源：http://dali.shzxlz.cn/Article/details/gtifokhodj.html

#!/usr/bin/env bash
来源：http://dali.bjfxy.top/Article/details/gtnyiioreu.html

set -euo pipefail
来源：http://dali.cheryme.top/Article/details/gtfxnsxfwl.html

[R02] 变量赋值与使用
来源：http://dali.cucudq.cn/Article/details/gtzqiiazvx.html

name="Tom"; echo "$name"
来源：http://dali.sxryk.cn/Article/details/gtyknjbuid.html

[R03] 只读变量
来源：http://dali.quarkkingdee.top/Article/details/gtcruynljr.html

readonly PI=3.14
来源：http://dali.shuidangran.top/Article/details/gtdobkmkiv.html

[R04] 位置参数
来源：http://dali.316326.xyz/Article/details/gtggqcschl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cucudq.cn/Article/details/gtynxyqctq.html

[R05] 参数默认值
来源：http://dali.yj20258.top/Article/details/gtbhzrqijx.html

name="${1:-default}"
来源：http://dali.jinqigufen.top/Article/details/gtlikcnuoz.html

[R06] 判断命令是否存在
来源：http://dali.snrcjt.cn/Article/details/gtffzcumgx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gtytrrmapo.html

[R07] if 判断文件
来源：http://dali.bjfxy.top/Article/details/gtfdicugel.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yvedp.cn/Article/details/gtihzxsrls.html

[R08] 数值比较
来源：http://dali.guannengcc.top/Article/details/gtocoxgurm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gtxesmowbr.html

[R09] 字符串比较
来源：http://dali.yj20258888.top/Article/details/gtemfmcrfl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenlongwang.top/Article/details/gtbhjjcxdv.html

[R10] 正则匹配
来源：http://dali.yj20258888.top/Article/details/gtctxfslff.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cqqwz.cn/Article/details/gtefpzxywl.html

[R11] case 多分支
来源：http://dali.ehwqpu.com/Article/details/gtkrwhdxtk.html

case "$1" in
来源：http://dali.feifeiyinyue.top/Article/details/gtemfubdri.html

start) echo "启动" ;;
来源：http://dali.vqdsnc.cn/Article/details/gtlrbmdxxz.html

stop)  echo "停止" ;;
来源：http://dali.fengsongda.top/Article/details/gtkhcrswjq.html

*)     echo "未知命令" ;;
来源：http://dali.snrcjt.cn/Article/details/gtrvnpxiko.html

esac
来源：http://dali.jlsjyb.cn/Article/details/gthioedxrn.html

[R12] for 遍历文件
来源：http://dali.jiagoushi.top/Article/details/gttnpcpqhs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.0kj1m.cn/Article/details/gtckrrikij.html

[R13] for 计数循环
来源：http://dali.yvedp.cn/Article/details/gtwylaahvt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gturmxjifc.html

[R14] C 风格 for
来源：http://dali.wangshuangyany.cn/Article/details/gtuwxhxhvw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gtwbbqaxoc.html

[R15] while 逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtpyzuvoro.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.pycfn.com/Article/details/gtocgzomry.html

[R16] until 等待条件
来源：http://dali.zhoulong.xyz/Article/details/gtwbwxophg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gaohongyu789.top/Article/details/gtymuyiwox.html

[R17] 数组定义与取值
来源：http://dali.guannengcc.top/Article/details/gtdximsotw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nanxinkj.top/Article/details/gtssudxfwr.html

[R18] 遍历数组
来源：http://dali.xuanzx.com/Article/details/gtnhkmaybb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhongyouzk.top/Article/details/gtibdadfpg.html

[R19] 数组长度
来源：http://dali.daria6918.cn/Article/details/gtissxdsbs.html

echo "${#arr[@]}"
来源：http://dali.xinyue.icu/Article/details/gtmsfctgjs.html

[R20] 关联数组（字典）
来源：http://dali.hongshengwenyu.top/Article/details/gtcyyebhef.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xuanzx.com/Article/details/gtdydbbyub.html

[R21] 字符串长度
来源：http://dali.tian-w.cn/Article/details/gtuqwhwyog.html

echo "${#s}"
来源：http://dali.iojbl.cn/Article/details/gtkyhhotoc.html

[R22] 截取子串
来源：http://dali.cdnleiting.top/Article/details/gtpzjxbwol.html

echo "${s:0:5}"
来源：http://dali.pycfn.com/Article/details/gtpcebbfcm.html

[R23] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gtgdaukjzq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj20258888.top/Article/details/gtqdgiixwf.html

[R24] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gtldfotsbk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.mhx1999.top/Article/details/gtsljbllty.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgfzy.top/Article/details/gtomjcuyqz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shuidangran.top/Article/details/gtwysrkjtq.html

[R26] 命令替换
来源：http://dali.havefunace.top/Article/details/gtfwzdevhr.html

now=$(date +%F); echo "$now"
来源：http://dali.aibaodan.cn/Article/details/gthvrnbqyd.html

[R27] 算术展开
来源：http://dali.yuxming.cn/Article/details/gtqlaeopqm.html

echo $((1 + 2 * 3))
来源：http://dali.gzhubu.top/Article/details/gtykszobbi.html

[R28] 浮点运算
来源：http://dali.chenlongwang.top/Article/details/gtejguxkel.html

echo "scale=2; 10/3" | bc
来源：http://dali.tian-w.cn/Article/details/gtoleeqpbi.html

[R29] 定义函数
来源：http://dali.yuxming.cn/Article/details/gthkdsqffn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sweek.top/Article/details/gtcbovmrqj.html

[R30] 函数返回状态码
来源：http://dali.yj20258.top/Article/details/gtvrkhgelj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqzdbccp.html

[R31] 局部变量
来源：http://dali.chenlongwang.top/Article/details/gtemkblqmp.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangdashe.top/Article/details/gtqyseepgh.html

[R32] 参数个数校验
来源：http://dali.snrcjt.cn/Article/details/gtchndcjqd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jqgfzy.top/Article/details/gtrpzggszx.html

[R33] 捕获错误并提示行号
来源：http://dali.gzhubu.top/Article/details/gtdsapxlgd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sysykeji.top/Article/details/gthyfiurhe.html

[R34] 退出时清理
来源：http://dali.yuxming.cn/Article/details/gtomwlvvap.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gtbgbfzrrc.html

[R35] 后台执行并等待
来源：http://dali.zhengqikj.top/Article/details/gtwargvnrg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sxryk.cn/Article/details/gtpqehjwbu.html

[R36] 并发执行多个任务
来源：http://dali.wangshuangyany.cn/Article/details/gtrvpfvxvb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ppjwa.cn/Article/details/gtoezeixjd.html

[R37] 把输出赋给变量
来源：http://dali.gogol.net.cn/Article/details/gtymlppdbz.html

files=$(ls -1)
来源：http://dali.smart0.xyz/Article/details/gthxjuypzd.html

[R38] 管道串联
来源：http://dali.c1oappe.top/Article/details/gtnczuqyix.html

cat a.txt | grep -i error | wc -l
来源：http://dali.birdmap.top/Article/details/gtaiukjxsw.html

[R39] 重定向标准输出与错误
来源：http://dali.pycfn.com/Article/details/gtyieyqmvh.html

cmd > out.log 2>&1
来源：http://dali.nwbrower.top/Article/details/gtnpbpyxoj.html

[R40] 追加写日志
来源：http://dali.chenjidiqi.icu/Article/details/gtnkmsfgxg.html

echo "log" >> out.log
来源：http://dali.jinqigfzy.top/Article/details/gtxkowstzd.html

[R41] 丢弃输出
来源：http://dali.zhiwuduotai.top/Article/details/gtksxcuohx.html

cmd >/dev/null 2>&1
来源：http://dali.tanke756.top/Article/details/gtfawsdfrb.html

[R42] 输入重定向
来源：http://dali.sufxvd.cn/Article/details/gtkmehxftj.html

wc -l < a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtkpjctqgk.html

[R43] 按名字查找文件
来源：http://dali.dianchejie.cn/Article/details/gtncekkgfs.html

find . -name "*.log" -type f
来源：http://dali.hammf.cn/Article/details/gtubfhdlkf.html

[R44] 按修改时间查找
来源：http://dali.svipenyu.cn/Article/details/gtjrntfplq.html

find . -mtime -7 -type f
来源：http://dali.feifeiyinyue.top/Article/details/gtpsgkgeqo.html

[R45] 批量删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklqeeurd.html

find . -name "*.tmp" -delete
来源：http://dali.ybcxt.top/Article/details/gtfqqbnoaf.html

[R46] 递归替换文件内容
来源：http://dali.jiagoushi.top/Article/details/gtkannqwmr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.9152youxi.cn/Article/details/gtunijtqol.html

[R47] sed 单行替换
来源：http://dali.jyoumei.cn/Article/details/gtcdnkkegl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xylfe.cn/Article/details/gtxvqofrwo.html

[R48] awk 取指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gtmeflxhfh.html

awk '{print $1, $3}' a.txt
来源：http://dali.sysykeji.top/Article/details/gtpxjzwqej.html

[R49] awk 带条件
来源：http://dali.yj20258888.top/Article/details/gtgwrcdbhc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nwbrower.top/Article/details/gtlyapjhdi.html

[R50] awk 求和
来源：http://dali.hywenlv.cn/Article/details/gtehptzsvh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hysaishi.cn/Article/details/gtogmrhmsy.html

[R51] 排序去重取前几
来源：http://dali.yueranfly.top/Article/details/gtdjpvudxp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.andypj.xyz/Article/details/gtxzzwaeng.html

[R52] 统计行数
来源：http://dali.mhx1999.top/Article/details/gtimbgwjla.html

wc -l a.txt
来源：http://dali.yj20258888.top/Article/details/gtrclzxqfu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvlctmpd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuxming.cn/Article/details/gtuusruseg.html

[R54] 比较两个文件
来源：http://dali.tianlin.xyz/Article/details/gtzinkkmjw.html

diff a.txt b.txt
来源：http://dali.yongpay.top/Article/details/gturyejyrc.html

[R55] 压缩与解压
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnaglfciz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.pengpengdd.cyou/Article/details/gtxvoteyzn.html

[R56] 远程拷贝
来源：http://dali.yj20258.top/Article/details/gtycritqnc.html

scp file user@host:/path/
来源：http://dali.ppjwa.cn/Article/details/gttsglpxun.html

[R57] 远程执行命令
来源：http://dali.iojbl.cn/Article/details/gtnzvalbfz.html

ssh user@host 'uptime'
来源：http://dali.sysykeji.top/Article/details/gtlvixqcdr.html

[R58] 下载文件
来源：http://dali.yuxming.cn/Article/details/gtnsejqlep.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xylfe.cn/Article/details/gthbvwmfmi.html

[R59] 发 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gtjinlihyk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hfpthk.cn/Article/details/gttpdfsabv.html

[R60] 只看 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gthmcsjrug.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hnxiangtu.top/Article/details/gtqeyflidk.html

[R61] 磁盘占用
来源：http://dali.meibo888.top/Article/details/gtyxjddfuz.html

df -h;  du -sh *
来源：http://dali.chenzaomai.com/Article/details/gtdotfkfpw.html

[R62] 找最占空间的文件
来源：http://dali.c1oappe.top/Article/details/gtvbbnhryj.html

du -ah . | sort -rh | head -10
来源：http://dali.tanke756.top/Article/details/gtwgpsketh.html

[R63] 内存与进程
来源：http://dali.9152youxi.cn/Article/details/gtnmwovnep.html

free -h;  ps aux | grep nginx
来源：http://dali.jyoumei.cn/Article/details/gtmnstqvcv.html

[R64] 结束进程
来源：http://dali.yanxiufei.cn/Article/details/gtwjrzoapq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.snrcjt.cn/Article/details/gtqevhfvsm.html

[R65] 查看端口占用
来源：http://dali.jyoumei.cn/Article/details/gtxlcguexq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shangyingyoupin.top/Article/details/gtjilqihsr.html

[R66] 定时任务
来源：http://dali.cqqwz.cn/Article/details/gtjvgmcqcu.html

crontab -e;  crontab -l
来源：http://dali.kuanghao11.cn/Article/details/gtgibqmhrx.html

[R67] 生成随机十六进制串
来源：http://dali.jyoumei.cn/Article/details/gtuardtjea.html

openssl rand -hex 16
来源：http://dali.xylfe.cn/Article/details/gtramtsqlk.html

[R68] 计算文件校验值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxijoewmn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zdqjudy.top/Article/details/gtwndefqtt.html

[R69] 生成随机密码
来源：http://dali.gogol.net.cn/Article/details/gtgyehffsq.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkiyilon.html

[R70] 时间戳与互转
来源：http://dali.guannengcc.top/Article/details/gttcusiupr.html

date +%s;  date -d @1700000000
来源：http://dali.0kj1m.cn/Article/details/gtpanrozvs.html

[R71] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtnnayotky.html


<!-- 参考信息 -->