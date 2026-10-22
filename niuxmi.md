代发 wailian999

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ivvv.top/Article/details/gtksattudv.html

[Q20] IN 列表
来源：http://dali.snrcjt.cn/Article/details/gtnflkvhth.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.dashuyun.cn/Article/details/gtrcrxqclt.html

[Q21] 空值判断
来源：http://dali.xylfe.cn/Article/details/gtovyrleyp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.quarkkingdee.top/Article/details/gtmzjmkrhm.html

[Q22] 排序
来源：http://dali.shuidangran.top/Article/details/gtlrxpajph.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.havefunace.top/Article/details/gtygqxgzai.html

[Q23] 分页
来源：http://dali.jinqigfzy.top/Article/details/gtmsvqyjwd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yanxiufei.cn/Article/details/gtbrpkruve.html

[Q24] 去重
来源：http://dali.sweek.top/Article/details/gtcvepzqwk.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtmzijeumk.html

[Q25] 只取前 N 条
来源：http://dali.hongshengwenyu.top/Article/details/gtzpzydnvi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sxryk.cn/Article/details/gtduyzglsw.html

[Q26] 计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gthawxwhjm.html

SELECT COUNT(*) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtczwwqejm.html

[Q27] 条件计数
来源：http://dali.gotoacloud.top/Article/details/gtjudlgwlk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tian-w.cn/Article/details/gttjnnizrk.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxfvooip.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cheryme.top/Article/details/gtugiazkat.html

[Q29] 最大最小值
来源：http://dali.xziqi.cn/Article/details/gtbmhftsvk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtuxxhrctt.html

[Q30] 分组统计
来源：http://dali.fzhhl.top/Article/details/gtcjvwtijs.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gtyxnyjssd.html

[Q31] 分组后过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmmwuikm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jlsjyb.cn/Article/details/gtnscskpar.html

[Q32] 分组拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gtyaevldfq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtzmilmcfo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hysaishi.cn/Article/details/gtfgwwxabg.html

[Q33] 多列分组
来源：http://dali.jiagoushi.top/Article/details/gttsnrtvog.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xuanzx.com/Article/details/gtvwtbgtmd.html

[Q34] 每组取第一条
来源：http://dali.guowangkeji.top/Article/details/gtuthgswzz.html

SELECT * FROM (
来源：http://dali.daria6918.cn/Article/details/gtdraquchf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaaujnift.html

) t WHERE rn = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhzzsqhk.html

[Q35] 内连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuhscsjcv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.9152youxi.cn/Article/details/gtjlwlxkso.html

[Q36] 左连接
来源：http://dali.jyoumei.cn/Article/details/gtstvebfcw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jiagoushi.top/Article/details/gtboxcdcuj.html

[Q37] 右连接
来源：http://dali.guowangkeji.top/Article/details/gtcfbhtlrf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shangyingyoupin.top/Article/details/gteglinnyf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.vqdsnc.cn/Article/details/gtizyazade.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenjidiqi.icu/Article/details/gttmulnipy.html

[Q39] 自连接（查上下级）
来源：http://dali.nwbrower.top/Article/details/gtprgbfzbq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daxiang520.top/Article/details/gtreeqecoq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ybcxt.top/Article/details/gtnktgpbzl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tanke756.top/Article/details/gtwvqblvqc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.smart0.xyz/Article/details/gtcqcpdreo.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gtnsyhdwry.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.havefunace.top/Article/details/gtvhtujbbx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gtzrzkexcp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xinyue.icu/Article/details/gtafvbxwxu.html

[Q42] 连接条件附加过滤
来源：http://dali.xuanzx.com/Article/details/gtbmxucccv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj202588.top/Article/details/gtpcolgacu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.bjfxy.top/Article/details/gtxrwosktz.html

[Q43] 标量子查询
来源：http://dali.dianchejie.cn/Article/details/gtuxpfehpp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.svipenyu.cn/Article/details/gtmkhvwgjd.html

[Q44] IN 子查询
来源：http://dali.zhixingplan.top/Article/details/gtrvcxtrhh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hysaishi.cn/Article/details/gtdyxcoyak.html

[Q45] EXISTS 判断存在
来源：http://dali.dianchejie.cn/Article/details/gtyoiyyuwu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gttgdbxiun.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangshuangyany.cn/Article/details/gtkohjooqb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gtlcczkokl.html

[Q47] 与平均值比较
来源：http://dali.xuanzx.com/Article/details/gtyycnbytt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yangfankeji.com/Article/details/gtxbtyqwhd.html

[Q48] CTE 公用表表达式
来源：http://dali.hysaishi.cn/Article/details/gtvvyzmoze.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.havefunace.top/Article/details/gtfjiugqlz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hnxiangtu.top/Article/details/gtpdmvpima.html

[Q49] 更新单行
来源：http://dali.zhixingplan.top/Article/details/gtfshylper.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxinkj.top/Article/details/gtejsyjqhf.html

[Q50] 批量更新
来源：http://dali.quarkkingdee.top/Article/details/gtsfyxwqsd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zdqjudy.top/Article/details/gtnfhxkanf.html

[Q51] 用子查询更新
来源：http://dali.ivvv.top/Article/details/gttrymoatd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.smart0.xyz/Article/details/gtukqsqrrg.html

[Q52] 删除指定行
来源：http://dali.feifeiyinyue.top/Article/details/gtrvmwvxcl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gtotvkseew.html

[Q53] 按条件删除
来源：http://dali.yueranfly.top/Article/details/gtubnhdwaw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinghuilouyu.cn/Article/details/gtzsftklag.html

[Q54] 清空表
来源：http://dali.bjfxy.top/Article/details/gtwujqotil.html

TRUNCATE TABLE logs;
来源：http://dali.hammf.cn/Article/details/gtcmgwneqj.html

[Q55] 排名（并列占位）
来源：http://dali.hnxiangtu.top/Article/details/gtqsprjwbu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hongshengwenyu.top/Article/details/gtaknehtib.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jqgfzy.top/Article/details/gtceuhccdt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shangyingyoupin.top/Article/details/gtzycidyiu.html

[Q57] 行号
来源：http://dali.nanxuanxn.top/Article/details/gtblqcxyir.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtxenhzrzi.html

[Q58] 累计求和
来源：http://dali.jqgfzy.top/Article/details/gtmvtfuyxp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtqsqmwnzc.html

[Q59] 分组内累计
来源：http://dali.jlsjyb.cn/Article/details/gtxnjtnell.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gttntpvblh.html

[Q60] 取上一行 / 下一行
来源：http://dali.snrcjt.cn/Article/details/gtstwfugsc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sufxvd.cn/Article/details/gtcxirocwa.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtrwxqpgav.html

[Q61] 移动平均
来源：http://dali.zhixingplan.top/Article/details/gtnystnudy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtagkiiwvr.html

[Q62] 分组占比
来源：http://dali.vqdsnc.cn/Article/details/gtmwcndxda.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gtconeqjxs.html

[Q63] 开启事务
来源：http://dali.sufxvd.cn/Article/details/gtuaniamea.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigfzy.top/Article/details/gtordceplv.html

[Q64] 提交事务
来源：http://dali.chenlongwang.top/Article/details/gtjmnsfjhf.html

COMMIT;
来源：http://dali.zdqjudy.top/Article/details/gtjgotalnp.html

[Q65] 回滚事务
来源：http://dali.zycfv.cn/Article/details/gthxvrnmqr.html

ROLLBACK;
来源：http://dali.jiagoushi.top/Article/details/gtyzynbiem.html

[Q66] 行锁查询
来源：http://dali.yongpay.top/Article/details/gthqusrkon.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yongpay.top/Article/details/gtrnaxttxh.html

[Q67] 设置隔离级别
来源：http://dali.tanke756.top/Article/details/gtucxdiupe.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.9152youxi.cn/Article/details/gtystnnsml.html

[Q68] 保存点
来源：http://dali.sysykeji.top/Article/details/gttpwvbcjm.html

SAVEPOINT sp1;
来源：http://dali.wangshuangyany.cn/Article/details/gtwzumkjgi.html

ROLLBACK TO sp1;
来源：http://dali.yuxming.cn/Article/details/gtwvfychay.html

[Q69] 查看执行计划
来源：http://dali.jiagoushi.top/Article/details/gtbrqwwnnc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hysaishi.cn/Article/details/gtkktgmijk.html

[Q70] 更新统计信息
来源：http://dali.vqdsnc.cn/Article/details/gtrnaqzlek.html

ANALYZE TABLE users;
来源：http://dali.jinqigufen.top/Article/details/gteafvwopl.html

[Q71] 查看建表语句
来源：http://dali.xylfe.cn/Article/details/gtthhomray.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jyoumei.cn/Article/details/gtpedccwob.html

[Q72] 查看索引
来源：http://dali.chenjidiqi.icu/Article/details/gtzoioeycd.html

SHOW INDEX FROM users;
来源：http://dali.fengsongda.top/Article/details/gthoqfdhnc.html

[Q73] 查看表状态
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdhlmngn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xziqi.cn/Article/details/gtwaqecwsg.html

[Q74] 强制使用索引
来源：http://dali.jianghu66.top/Article/details/gtayqmhlxh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.bjfxy.top/Article/details/gtfuynhkal.html

[Q75] 日期格式化
来源：http://dali.sweek.top/Article/details/gtjxwsirey.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtfumestit.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jqgfzy.top/Article/details/gtpcmjhuvt.html

[Q76] 按天统计
来源：http://dali.iojbl.cn/Article/details/gtjojxktjs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.0kj1m.cn/Article/details/gtvnrrwwsy.html

[Q77] 时间加减
来源：http://dali.jinqigfzy.top/Article/details/gtdphrnifb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.birdmap.top/Article/details/gtofnngudc.html

[Q78] 当前时间
来源：http://dali.aibaodan.cn/Article/details/gtwtxqzncc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigufen.top/Article/details/gtqgndlqnb.html

[Q79] 字符串拼接
来源：http://dali.sysykeji.top/Article/details/gthrjmoorf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.meibo888.top/Article/details/gtbdqgjfsc.html

[Q80] 字符串截取
来源：http://dali.meibo888.top/Article/details/gtzcypcxjh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmodlens.html

[Q81] 字符串替换
来源：http://dali.aibaodan.cn/Article/details/gthgatcttw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.iojbl.cn/Article/details/gtohpaglzp.html

[Q82] 字符长度与字节长度
来源：http://dali.gaohongyu789.top/Article/details/gthgzdjxya.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtxohoibni.html

[Q83] 大小写转换
来源：http://dali.snrcjt.cn/Article/details/gtzgxvaqhy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtkotpsmya.html

[Q84] 去除首尾空格
来源：http://dali.redwolf501.top/Article/details/gtxczwfexi.html

SELECT TRIM(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtxuhyeyzn.html

[Q85] 数值取整
来源：http://dali.nanxuanxn.top/Article/details/gtmgtxpdno.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cqqwz.cn/Article/details/gtmgplihkz.html

[Q86] 读取 JSON 字段
来源：http://dali.birdmap.top/Article/details/gtmmsphcom.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ydzc1.top/Article/details/gttjuwtqlv.html

[Q87] JSON 字段做条件
来源：http://dali.xuanzx.com/Article/details/gttxdazmkb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenjidiqi.icu/Article/details/gtvcilhgdm.html

[Q88] 行转列（条件聚合）
来源：http://dali.cheryme.top/Article/details/gtgixeckys.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.vqdsnc.cn/Article/details/gtxoyiytrl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwvuwypw.html

[Q89] 判断表是否存在
来源：http://dali.fzhhl.top/Article/details/gtbayixpcp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwegpnqw.html

[Q90] 生成序号列
来源：http://dali.sysykeji.top/Article/details/gtmwttuppr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ehwqpu.com/Article/details/gtdvmrphip.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtxdnbxgvt.html

R. Bash 专题
来源：http://dali.yongpay.top/Article/details/gtfovnawho.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtamcyepyu.html

[R01] shebang 与严格模式
来源：http://dali.guowangkeji.top/Article/details/gtkmgigsod.html

#!/usr/bin/env bash
来源：http://dali.svipenyu.cn/Article/details/gtbqujxukm.html

set -euo pipefail
来源：http://dali.zhongyouzk.top/Article/details/gtmfpimdsg.html

[R02] 变量赋值与使用
来源：http://dali.tian-w.cn/Article/details/gtyhiapvlj.html

name="Tom"; echo "$name"
来源：http://dali.0kj1m.cn/Article/details/gtwgtffqti.html

[R03] 只读变量
来源：http://dali.zhiwuduotai.top/Article/details/gtqgjwftrk.html

readonly PI=3.14
来源：http://dali.ehwqpu.com/Article/details/gthmltssdz.html

[R04] 位置参数
来源：http://dali.yj202588.top/Article/details/gtoanydftz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cdnleiting.top/Article/details/gtieerchkh.html

[R05] 参数默认值
来源：http://dali.zhongyouzk.top/Article/details/gttxlfcapn.html

name="${1:-default}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtsnjcwhre.html

[R06] 判断命令是否存在
来源：http://dali.jqgufenzy.top/Article/details/gtelkrzvvc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gtbnfbkkpc.html

[R07] if 判断文件
来源：http://dali.jlsjyb.cn/Article/details/gtwwkwpwkc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.svipenyu.cn/Article/details/gtrjhgdnrt.html

[R08] 数值比较
来源：http://dali.shuidangran.top/Article/details/gtjxmtwcsp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gthouvqalf.html

[R09] 字符串比较
来源：http://dali.shuidangran.top/Article/details/gtsrhkncos.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.9152youxi.cn/Article/details/gtbuhrczmk.html

[R10] 正则匹配
来源：http://dali.tian-w.cn/Article/details/gtzktsegux.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cucudq.cn/Article/details/gtnelkbcve.html

[R11] case 多分支
来源：http://dali.jqgfzy.top/Article/details/gthlsfiwse.html

case "$1" in
来源：http://dali.tanke756.top/Article/details/gtirsdkapb.html

start) echo "启动" ;;
来源：http://dali.bjfxy.top/Article/details/gtconysqae.html

stop)  echo "停止" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtribzxzfn.html

*)     echo "未知命令" ;;
来源：http://dali.fzhhl.top/Article/details/gtxfvtamcj.html

esac
来源：http://dali.iojbl.cn/Article/details/gthabaavtp.html

[R12] for 遍历文件
来源：http://dali.daria6918.cn/Article/details/gtzbhhzjhu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhoulong.xyz/Article/details/gtkugzigxm.html

[R13] for 计数循环
来源：http://dali.snrcjt.cn/Article/details/gtstrhqhxt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gttufrngpn.html

[R14] C 风格 for
来源：http://dali.shangyingyoupin.top/Article/details/gtojmnjglf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gtzerblxfu.html

[R15] while 逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtwzodxwdv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hammf.cn/Article/details/gtdwupihrz.html

[R16] until 等待条件
来源：http://dali.guannengcc.top/Article/details/gtjmcofhtq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hfpthk.cn/Article/details/gtfmgxakiq.html

[R17] 数组定义与取值
来源：http://dali.jinghuilouyu.cn/Article/details/gtxpazwocx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.smart0.xyz/Article/details/gtdavcocvt.html

[R18] 遍历数组
来源：http://dali.zhiwuduotai.top/Article/details/gtivwtmwdq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjilxafov.html

[R19] 数组长度
来源：http://dali.vqdsnc.cn/Article/details/gtxtsclvfh.html

echo "${#arr[@]}"
来源：http://dali.c1oappe.top/Article/details/gtkoweeymb.html

[R20] 关联数组（字典）
来源：http://dali.wangdashe.top/Article/details/gtdpjpvucn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxinkj.top/Article/details/gtokipbsmg.html

[R21] 字符串长度
来源：http://dali.yj202588.top/Article/details/gtrzhsfhej.html

echo "${#s}"
来源：http://dali.guowangkeji.top/Article/details/gtvubpagsu.html

[R22] 截取子串
来源：http://dali.tian-w.cn/Article/details/gtukvamsky.html

echo "${s:0:5}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkkjnxut.html

[R23] 字符串替换
来源：http://dali.quarkkingdee.top/Article/details/gttlosppmy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hnqzz.top/Article/details/gtfbgvjoxg.html

[R24] 大小写转换
来源：http://dali.hammf.cn/Article/details/gtycqpymhm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.bjfxy.top/Article/details/gtxwmlvitz.html

[R25] 去后缀 / 去前缀
来源：http://dali.xinyue.icu/Article/details/gtvaqwodys.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cheryme.top/Article/details/gtoubqrmwy.html

[R26] 命令替换
来源：http://dali.xuanzx.com/Article/details/gtfelrcgdn.html

now=$(date +%F); echo "$now"
来源：http://dali.hammf.cn/Article/details/gtdjzjjzmt.html

[R27] 算术展开
来源：http://dali.zhengqikj.top/Article/details/gtyioeptim.html

echo $((1 + 2 * 3))
来源：http://dali.zhaomingkeji.xyz/Article/details/gttembaxlv.html

[R28] 浮点运算
来源：http://dali.vqdsnc.cn/Article/details/gthacguyzi.html

echo "scale=2; 10/3" | bc
来源：http://dali.hongshengwenyu.top/Article/details/gtncpgcpmm.html

[R29] 定义函数
来源：http://dali.jianghu66.top/Article/details/gtxskydluh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.andypj.xyz/Article/details/gtgdwhdfgu.html

[R30] 函数返回状态码
来源：http://dali.gaohongyu789.top/Article/details/gtskbhspoq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fengsongda.top/Article/details/gtlfycjmlz.html

[R31] 局部变量
来源：http://dali.gaohongyu789.top/Article/details/gtdtcffqvr.html

f() { local x=1; echo "$x"; }
来源：http://dali.havefunace.top/Article/details/gtwettlook.html

[R32] 参数个数校验
来源：http://dali.yj202588.top/Article/details/gtpedwxiyv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yonumen.top/Article/details/gtorxgaxne.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangtech.top/Article/details/gtcijzkdgh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guowangkeji.top/Article/details/gtxvjdzejx.html

[R34] 退出时清理
来源：http://dali.nanxuanxn.top/Article/details/gtkuvrqodx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nwbrower.top/Article/details/gtndbbpljz.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangtech.top/Article/details/gtgyguqlwi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yvedp.cn/Article/details/gtabwfhjzm.html

[R36] 并发执行多个任务
来源：http://dali.jqgufenzy.top/Article/details/gtuxjaxnlv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhoulong.xyz/Article/details/gtcvofuzya.html

[R37] 把输出赋给变量
来源：http://dali.yongpay.top/Article/details/gtrahjnndf.html

files=$(ls -1)
来源：http://dali.xylfe.cn/Article/details/gttmhpycqn.html

[R38] 管道串联
来源：http://dali.cqqwz.cn/Article/details/gtdafeppvc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhoulong.xyz/Article/details/gtepebmkqi.html

[R39] 重定向标准输出与错误
来源：http://dali.sweek.top/Article/details/gtkhginelr.html

cmd > out.log 2>&1
来源：http://dali.tanke756.top/Article/details/gtrmhkgcwu.html

[R40] 追加写日志
来源：http://dali.pengpengdd.cyou/Article/details/gtmualwxmj.html

echo "log" >> out.log
来源：http://dali.jyoumei.cn/Article/details/gtosxjfzdq.html

[R41] 丢弃输出
来源：http://dali.hnxiangtu.top/Article/details/gtgbqjiaeo.html

cmd >/dev/null 2>&1
来源：http://dali.chenzaomai.com/Article/details/gtrgukvcux.html

[R42] 输入重定向
来源：http://dali.nwbrower.top/Article/details/gtwcavndnq.html

wc -l < a.txt
来源：http://dali.havefunace.top/Article/details/gtvriteths.html

[R43] 按名字查找文件
来源：http://dali.wangshuangyany.cn/Article/details/gtdqjzngit.html

find . -name "*.log" -type f
来源：http://dali.bjfxy.top/Article/details/gtielsarbs.html

[R44] 按修改时间查找
来源：http://dali.aibaodan.cn/Article/details/gtsaongblj.html

find . -mtime -7 -type f
来源：http://dali.svipenyu.cn/Article/details/gtaeehlgfu.html

[R45] 批量删除
来源：http://dali.zhixingplan.top/Article/details/gtnxkteydy.html

find . -name "*.tmp" -delete
来源：http://dali.gaohongyu789.top/Article/details/gteopmzuxn.html

[R46] 递归替换文件内容
来源：http://dali.pycfn.com/Article/details/gtpvuzlfxd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cashguo.top/Article/details/gtoxubkfzf.html

[R47] sed 单行替换
来源：http://dali.zhoulong.xyz/Article/details/gtymgjilek.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hysaishi.cn/Article/details/gtqedbltgf.html

[R48] awk 取指定列
来源：http://dali.cucudq.cn/Article/details/gtefzhugdq.html

awk '{print $1, $3}' a.txt
来源：http://dali.yueranfly.top/Article/details/gtvbkwwoeb.html

[R49] awk 带条件
来源：http://dali.xziqi.cn/Article/details/gtbpxifhvj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.0kj1m.cn/Article/details/gtyiolscdn.html

[R50] awk 求和
来源：http://dali.svipenyu.cn/Article/details/gtxoewgfgw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtmlhdlxhp.html

[R51] 排序去重取前几
来源：http://dali.dashuyun.cn/Article/details/gtqsieryxv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ppjwa.cn/Article/details/gtumiguhvv.html

[R52] 统计行数
来源：http://dali.9152youxi.cn/Article/details/gtqnbrpxbv.html

wc -l a.txt
来源：http://dali.316326.xyz/Article/details/gtyjobrlij.html

[R53] 查看文件头与实时尾
来源：http://dali.shuidangran.top/Article/details/gtyljnebqc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnxiangtu.top/Article/details/gttbjccldo.html

[R54] 比较两个文件
来源：http://dali.cucudq.cn/Article/details/gtyholmeco.html

diff a.txt b.txt
来源：http://dali.fengsongda.top/Article/details/gtuvbfriaq.html

[R55] 压缩与解压
来源：http://dali.tanke756.top/Article/details/gtmokvwwma.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hnxiangtu.top/Article/details/gtjftpjczi.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzxjiydp.html

scp file user@host:/path/
来源：http://dali.wangshuangyany.cn/Article/details/gtjmvzrwdz.html

[R57] 远程执行命令
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjdrpnff.html

ssh user@host 'uptime'
来源：http://dali.hnqzz.top/Article/details/gtokzocsjt.html

[R58] 下载文件
来源：http://dali.zycfv.cn/Article/details/gtslmfjklf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gogol.net.cn/Article/details/gtuachnfmb.html

[R59] 发 POST JSON
来源：http://dali.nanxuanxn.top/Article/details/gtvhrpymyk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fengsongda.top/Article/details/gtxlvtktlc.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxinkj.top/Article/details/gteobbgcit.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.kuanghao11.cn/Article/details/gtllyfmvzr.html

[R61] 磁盘占用
来源：http://dali.havefunace.top/Article/details/gtdalsljhq.html

df -h;  du -sh *
来源：http://dali.redwolf501.top/Article/details/gtlxpyzskc.html

[R62] 找最占空间的文件
来源：http://dali.jyoumei.cn/Article/details/gthmruedmo.html

du -ah . | sort -rh | head -10
来源：http://dali.tanke756.top/Article/details/gtxdmhbnzw.html

[R63] 内存与进程
来源：http://dali.hfpthk.cn/Article/details/gtdadxlxim.html

free -h;  ps aux | grep nginx
来源：http://dali.vqdsnc.cn/Article/details/gteesotllo.html

[R64] 结束进程
来源：http://dali.sysykeji.top/Article/details/gtfvofruhl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sysykeji.top/Article/details/gtkiinjgkt.html

[R65] 查看端口占用
来源：http://dali.ybcxt.top/Article/details/gtgfexuhbd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xziqi.cn/Article/details/gtsfhqgtzz.html

[R66] 定时任务
来源：http://dali.tian-w.cn/Article/details/gtxlbrmgew.html

crontab -e;  crontab -l
来源：http://dali.yonumen.top/Article/details/gtxealhfuq.html

[R67] 生成随机十六进制串
来源：http://dali.iojbl.cn/Article/details/gtujokkzti.html

openssl rand -hex 16
来源：http://dali.hnqzz.top/Article/details/gtrmpfjadp.html

[R68] 计算文件校验值
来源：http://dali.vqdsnc.cn/Article/details/gtzyaqftnj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtdenmmjgh.html

[R69] 生成随机密码
来源：http://dali.hnxiangtu.top/Article/details/gtyqcxkjrw.html


<!-- 参考信息 -->