代发 wailian999

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jlsjyb.cn/Article/details/gtsyewboxy.html

[Q22] 排序
来源：http://dali.shzxlz.cn/Article/details/gtgfsulixa.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hnqzz.top/Article/details/gtdewegojg.html

[Q23] 分页
来源：http://dali.cucudq.cn/Article/details/gthlyzhzzm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hysaishi.cn/Article/details/gtweskxcgu.html

[Q24] 去重
来源：http://dali.tanke756.top/Article/details/gtlnamtdgp.html

SELECT DISTINCT city FROM users;
来源：http://dali.aizwys.cn/Article/details/gtousvjgji.html

[Q25] 只取前 N 条
来源：http://dali.c1oappe.top/Article/details/gtppozpkkb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sufxvd.cn/Article/details/gtoeousmhg.html

[Q26] 计数
来源：http://dali.daria6918.cn/Article/details/gtrdzntpkt.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gttdibylnn.html

[Q27] 条件计数
来源：http://dali.havefunace.top/Article/details/gtafcoefhb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtwciabpii.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzdbnhme.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.316326.xyz/Article/details/gtnamefekl.html

[Q29] 最大最小值
来源：http://dali.feifeiyinyue.top/Article/details/gtjhwbcoxp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtrbdydhoj.html

[Q30] 分组统计
来源：http://dali.nanxuanxn.top/Article/details/gtgnszgfzc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtvewgljtl.html

[Q31] 分组后过滤
来源：http://dali.c1oappe.top/Article/details/gtxjvlybpu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj20258888.top/Article/details/gtbhyxarsn.html

[Q32] 分组拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gtnnioamsc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gtxkicasef.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nanxuanxn.top/Article/details/gtlhytzsfp.html

[Q33] 多列分组
来源：http://dali.sxryk.cn/Article/details/gtuevgcrcx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pengpengdd.cyou/Article/details/gtpzvxqnsp.html

[Q34] 每组取第一条
来源：http://dali.yvedp.cn/Article/details/gtdmcsdvda.html

SELECT * FROM (
来源：http://dali.sysykeji.top/Article/details/gtzulowtbm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cheryme.top/Article/details/gtlpkarvyx.html

) t WHERE rn = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtizdwwqsu.html

[Q35] 内连接
来源：http://dali.cdnleiting.top/Article/details/gtmrkohbre.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gtmrxhcsbc.html

[Q36] 左连接
来源：http://dali.jyoumei.cn/Article/details/gtkxbzjadj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yonumen.top/Article/details/gtvrpkufty.html

[Q37] 右连接
来源：http://dali.gaohongyu789.top/Article/details/gtrmgzwerc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuetiantiany.cn/Article/details/gtnoxyzsic.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gotoacloud.top/Article/details/gtzkncwmgr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yuanzhike.top/Article/details/gtkqdonowb.html

[Q39] 自连接（查上下级）
来源：http://dali.jyoumei.cn/Article/details/gtdjifymbh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.vqdsnc.cn/Article/details/gtiwanubzl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcsdnknmw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenlongwang.top/Article/details/gtkvmiyrpo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhoulong.xyz/Article/details/gtonjuxhmj.html

[Q41] 多表连接
来源：http://dali.nwbrower.top/Article/details/gtnprsggke.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xylfe.cn/Article/details/gtqgldafgz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.quarkkingdee.top/Article/details/gtttyarqee.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.316326.xyz/Article/details/gtdbghcfzy.html

[Q42] 连接条件附加过滤
来源：http://dali.jianghu66.top/Article/details/gtnpxgtyea.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zycfv.cn/Article/details/gtxkfbeaok.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj202588.top/Article/details/gtqbrddsxq.html

[Q43] 标量子查询
来源：http://dali.guowangkeji.top/Article/details/gtyrdkhazd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sweek.top/Article/details/gtjptpikfy.html

[Q44] IN 子查询
来源：http://dali.c1oappe.top/Article/details/gteewzbjbu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenzaomai.com/Article/details/gtnbahtmlm.html

[Q45] EXISTS 判断存在
来源：http://dali.dianchejie.cn/Article/details/gtawoweofd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.meibo888.top/Article/details/gtewmpxhnc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.guowangkeji.top/Article/details/gtuvalltyp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenlongwang.top/Article/details/gtxryrfkzu.html

[Q47] 与平均值比较
来源：http://dali.zhiwuduotai.top/Article/details/gtmveiaznd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.iojbl.cn/Article/details/gtygpgmcpc.html

[Q48] CTE 公用表表达式
来源：http://dali.jqgfzy.top/Article/details/gthzwprvat.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sufxvd.cn/Article/details/gtfojpeqcx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jyoumei.cn/Article/details/gtucxajnwv.html

[Q49] 更新单行
来源：http://dali.hfpthk.cn/Article/details/gtawyhveay.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xylfe.cn/Article/details/gtfogsjxhu.html

[Q50] 批量更新
来源：http://dali.jinqigufen.top/Article/details/gtbgwtlonk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hammf.cn/Article/details/gtyvdfffmd.html

[Q51] 用子查询更新
来源：http://dali.wangshuangyany.cn/Article/details/gtybzhnnqu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hywenlv.cn/Article/details/gtoftwwtus.html

[Q52] 删除指定行
来源：http://dali.ybcxt.top/Article/details/gttptfbixn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.guowangkeji.top/Article/details/gtuynzgrkd.html

[Q53] 按条件删除
来源：http://dali.cheryme.top/Article/details/gtmmfqwcnd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenzaomai.com/Article/details/gttmqxyhju.html

[Q54] 清空表
来源：http://dali.yuanzhike.top/Article/details/gtvwvczcmg.html

TRUNCATE TABLE logs;
来源：http://dali.yanxiufei.cn/Article/details/gtxavulkqj.html

[Q55] 排名（并列占位）
来源：http://dali.mhx1999.top/Article/details/gtuycptvcs.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gteawsofhl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.aibaodan.cn/Article/details/gtdjpuleew.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gtrrcfzjrx.html

[Q57] 行号
来源：http://dali.nanxinkj.top/Article/details/gtfnyscmgw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cucudq.cn/Article/details/gtamvbzfba.html

[Q58] 累计求和
来源：http://dali.nanxinkj.top/Article/details/gtzhzubahf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtbnswhmaw.html

[Q59] 分组内累计
来源：http://dali.daxiang520.top/Article/details/gtvplkjyrm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.316326.xyz/Article/details/gtftravzlj.html

[Q60] 取上一行 / 下一行
来源：http://dali.hnxiangtu.top/Article/details/gthmlxoiac.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhongyouzk.top/Article/details/gtszmeador.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtavjjcgos.html

[Q61] 移动平均
来源：http://dali.fengsongda.top/Article/details/gtbipgjfur.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtsljbkffi.html

[Q62] 分组占比
来源：http://dali.xuetiantiany.cn/Article/details/gtvfujxepj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gtcdmfurpz.html

[Q63] 开启事务
来源：http://dali.pycfn.com/Article/details/gtzhtmajdj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ybcxt.top/Article/details/gtjrvxyxly.html

[Q64] 提交事务
来源：http://dali.daxiang520.top/Article/details/gtfoasyeeg.html

COMMIT;
来源：http://dali.iojbl.cn/Article/details/gtddodmrge.html

[Q65] 回滚事务
来源：http://dali.pycfn.com/Article/details/gtfuiucbkc.html

ROLLBACK;
来源：http://dali.tianlin.xyz/Article/details/gtreerkndd.html

[Q66] 行锁查询
来源：http://dali.iojbl.cn/Article/details/gtdpchdliw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shuidangran.top/Article/details/gttuukcpij.html

[Q67] 设置隔离级别
来源：http://dali.zdqjudy.top/Article/details/gtrgthtsxv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.svipenyu.cn/Article/details/gttgydxkwi.html

[Q68] 保存点
来源：http://dali.ehwqpu.com/Article/details/gtkcwefcpx.html

SAVEPOINT sp1;
来源：http://dali.nanxinkj.top/Article/details/gtidghrzxo.html

ROLLBACK TO sp1;
来源：http://dali.ivvv.top/Article/details/gtrmmcygxh.html

[Q69] 查看执行计划
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvteysdp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhiwuduotai.top/Article/details/gtjudhvvvu.html

[Q70] 更新统计信息
来源：http://dali.kuanghao11.cn/Article/details/gtcdtpenej.html

ANALYZE TABLE users;
来源：http://dali.xziqi.cn/Article/details/gtkkbnvguq.html

[Q71] 查看建表语句
来源：http://dali.hnxiangtu.top/Article/details/gtiqhdrzkm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hnqzz.top/Article/details/gtcifnclmu.html

[Q72] 查看索引
来源：http://dali.wangdashe.top/Article/details/gtuooilnol.html

SHOW INDEX FROM users;
来源：http://dali.redwolf501.top/Article/details/gtmteklout.html

[Q73] 查看表状态
来源：http://dali.gzhubu.top/Article/details/gtfsufhlmb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.fzhhl.top/Article/details/gtehxjhoyo.html

[Q74] 强制使用索引
来源：http://dali.hnqzz.top/Article/details/gtgfdhiccg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.bjfxy.top/Article/details/gtdujajuaz.html

[Q75] 日期格式化
来源：http://dali.yonumen.top/Article/details/gtwlwtattw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtmuyqjeos.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gtwejuyjkt.html

[Q76] 按天统计
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgceptsjp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yangfankeji.com/Article/details/gthztvlgsk.html

[Q77] 时间加减
来源：http://dali.fengsongda.top/Article/details/gtxsomrrzf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenjidiqi.icu/Article/details/gtwkwbumdv.html

[Q78] 当前时间
来源：http://dali.snrcjt.cn/Article/details/gtiahwlwey.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yongpay.top/Article/details/gtnavjxsdq.html

[Q79] 字符串拼接
来源：http://dali.chenlongwang.top/Article/details/gtgldiyuix.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.feifeiyinyue.top/Article/details/gtiorerebl.html

[Q80] 字符串截取
来源：http://dali.xuetiantiany.cn/Article/details/gtgbghqasp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtouixbdom.html

[Q81] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gtsnknyobl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.andypj.xyz/Article/details/gtwlatqzvg.html

[Q82] 字符长度与字节长度
来源：http://dali.xinyue.icu/Article/details/gtipdabvtg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtnihxkczh.html

[Q83] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnghheupn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtszfxreey.html

[Q84] 去除首尾空格
来源：http://dali.andypj.xyz/Article/details/gtyaxrqehe.html

SELECT TRIM(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtvohymxpw.html

[Q85] 数值取整
来源：http://dali.chenjidiqi.icu/Article/details/gtrvwpveqc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.pengpengdd.cyou/Article/details/gthezoyubd.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrjmunyc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxsiqdax.html

[Q87] JSON 字段做条件
来源：http://dali.mhx1999.top/Article/details/gtlryaxrrn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhixingplan.top/Article/details/gtweyqgomv.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangdashe.top/Article/details/gtkssnwgfa.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangtech.top/Article/details/gtywbnqtfb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cucudq.cn/Article/details/gthldsektr.html

[Q89] 判断表是否存在
来源：http://dali.quarkkingdee.top/Article/details/gtezccaxhv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenjidiqi.icu/Article/details/gtrzoftpbm.html

[Q90] 生成序号列
来源：http://dali.sysykeji.top/Article/details/gtvaqwwnim.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.haohaochexian.top/Article/details/gtnusmjzjz.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtoeusrsvv.html

R. Bash 专题
来源：http://dali.feifeiyinyue.top/Article/details/gtlzgnlzkm.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgnaupdd.html

[R01] shebang 与严格模式
来源：http://dali.mhx1999.top/Article/details/gtiehwlydp.html

#!/usr/bin/env bash
来源：http://dali.9152youxi.cn/Article/details/gtdutuqhft.html

set -euo pipefail
来源：http://dali.yanxiufei.cn/Article/details/gtsozfwljj.html

[R02] 变量赋值与使用
来源：http://dali.xylfe.cn/Article/details/gtqvoidojl.html

name="Tom"; echo "$name"
来源：http://dali.c1oappe.top/Article/details/gtaevnxggk.html

[R03] 只读变量
来源：http://dali.yuxming.cn/Article/details/gtmcyaqpbl.html

readonly PI=3.14
来源：http://dali.svipenyu.cn/Article/details/gthjqodpjl.html

[R04] 位置参数
来源：http://dali.cdnleiting.top/Article/details/gtotnmjkox.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuanzx.com/Article/details/gtazmwiqdm.html

[R05] 参数默认值
来源：http://dali.jianghu66.top/Article/details/gtauqnqdxs.html

name="${1:-default}"
来源：http://dali.tian-w.cn/Article/details/gtfqjwsauq.html

[R06] 判断命令是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gtytzgbdxy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmasgjcna.html

[R07] if 判断文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyojpipsc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daria6918.cn/Article/details/gthumnmlpt.html

[R08] 数值比较
来源：http://dali.daxiang520.top/Article/details/gtjctymrzh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj20258888.top/Article/details/gtzhtaztqt.html

[R09] 字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gttcafaiip.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.fengsongda.top/Article/details/gtprusgzew.html

[R10] 正则匹配
来源：http://dali.sufxvd.cn/Article/details/gttdgwwokd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aibaodan.cn/Article/details/gtmbptcyqx.html

[R11] case 多分支
来源：http://dali.yongpay.top/Article/details/gtzxbmnnkn.html

case "$1" in
来源：http://dali.shzxlz.cn/Article/details/gthjanjcgn.html

start) echo "启动" ;;
来源：http://dali.zhengqikj.top/Article/details/gtgulgsghe.html

stop)  echo "停止" ;;
来源：http://dali.jianghu66.top/Article/details/gtwvgdwxij.html

*)     echo "未知命令" ;;
来源：http://dali.ivvv.top/Article/details/gtmxvueszw.html

esac
来源：http://dali.birdmap.top/Article/details/gtttltrylg.html

[R12] for 遍历文件
来源：http://dali.zhengqikj.top/Article/details/gtjjuejrlg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.iojbl.cn/Article/details/gtlnzbjmvv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gtqfdoimvi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.quarkkingdee.top/Article/details/gtzpmgswrx.html

[R14] C 风格 for
来源：http://dali.hongshengwenyu.top/Article/details/gtftlxqwyz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gtzuwqqszm.html

[R15] while 逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtphkjaafu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncqgsixi.html

[R16] until 等待条件
来源：http://dali.gaohongyu789.top/Article/details/gtsjsokcrb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuxming.cn/Article/details/gtchinfozy.html

[R17] 数组定义与取值
来源：http://dali.jlsjyb.cn/Article/details/gtgbxihxjj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258.top/Article/details/gtuwefctqa.html

[R18] 遍历数组
来源：http://dali.jlsjyb.cn/Article/details/gtonbfzrco.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhjaqzhf.html

[R19] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gtygcocrik.html

echo "${#arr[@]}"
来源：http://dali.hammf.cn/Article/details/gtwyayhuft.html

[R20] 关联数组（字典）
来源：http://dali.316326.xyz/Article/details/gtjaahwqlc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhiwuduotai.top/Article/details/gtzxaigzee.html

[R21] 字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfycgtyn.html

echo "${#s}"
来源：http://dali.mhx1999.top/Article/details/gtsqusbceu.html

[R22] 截取子串
来源：http://dali.xylfe.cn/Article/details/gtvderbihx.html

echo "${s:0:5}"
来源：http://dali.bjfxy.top/Article/details/gtqoiistwh.html

[R23] 字符串替换
来源：http://dali.bjfxy.top/Article/details/gtdraeomwd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ppjwa.cn/Article/details/gtihvykoiv.html

[R24] 大小写转换
来源：http://dali.shuidangran.top/Article/details/gtawssbzml.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.mhx1999.top/Article/details/gtjwvtbium.html

[R25] 去后缀 / 去前缀
来源：http://dali.ehwqpu.com/Article/details/gtsxvkqtlr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cqqwz.cn/Article/details/gtehaksxlw.html

[R26] 命令替换
来源：http://dali.gotoacloud.top/Article/details/gtmoaxnfcm.html

now=$(date +%F); echo "$now"
来源：http://dali.mhx1999.top/Article/details/gtcxxhoebz.html

[R27] 算术展开
来源：http://dali.jqgfzy.top/Article/details/gtcohtpgbt.html

echo $((1 + 2 * 3))
来源：http://dali.yueranfly.top/Article/details/gtwpovxhaf.html

[R28] 浮点运算
来源：http://dali.birdmap.top/Article/details/gtmyjnypcc.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuanzx.com/Article/details/gtltfbajnc.html

[R29] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gttgrmbmaj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenzaomai.com/Article/details/gtrasaxgxq.html

[R30] 函数返回状态码
来源：http://dali.yangfankeji.com/Article/details/gtcjbdciwh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jiagoushi.top/Article/details/gtjnlygybq.html

[R31] 局部变量
来源：http://dali.ehwqpu.com/Article/details/gtzagxjkux.html

f() { local x=1; echo "$x"; }
来源：http://dali.xylfe.cn/Article/details/gtysacfjwf.html

[R32] 参数个数校验
来源：http://dali.yangfankeji.com/Article/details/gtlzstdifg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gtvryotvwv.html

[R33] 捕获错误并提示行号
来源：http://dali.yangfankeji.com/Article/details/gtsxmmevel.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.aibaodan.cn/Article/details/gtcgumhaum.html

[R34] 退出时清理
来源：http://dali.0kj1m.cn/Article/details/gtlajrnpta.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yanxiufei.cn/Article/details/gtpxdqigvj.html

[R35] 后台执行并等待
来源：http://dali.zycfv.cn/Article/details/gtsjtagebb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dianchejie.cn/Article/details/gtugkaabtm.html

[R36] 并发执行多个任务
来源：http://dali.quarkkingdee.top/Article/details/gtleyavizu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhoulong.xyz/Article/details/gtkapzccif.html

[R37] 把输出赋给变量
来源：http://dali.yuanzhike.top/Article/details/gteoemlfqq.html

files=$(ls -1)
来源：http://dali.guowangkeji.top/Article/details/gtyslsrvrh.html

[R38] 管道串联
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvfsefcv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yangfankeji.com/Article/details/gtuzavdcxv.html

[R39] 重定向标准输出与错误
来源：http://dali.daxiang520.top/Article/details/gtbkstotfi.html

cmd > out.log 2>&1
来源：http://dali.ivvv.top/Article/details/gtrgrvkegu.html

[R40] 追加写日志
来源：http://dali.hnqzz.top/Article/details/gttmvwqxbe.html

echo "log" >> out.log
来源：http://dali.gzhubu.top/Article/details/gtrhxeezap.html

[R41] 丢弃输出
来源：http://dali.jinqigfzy.top/Article/details/gtsijdyzgl.html

cmd >/dev/null 2>&1
来源：http://dali.yanxiufei.cn/Article/details/gtismetcjv.html

[R42] 输入重定向
来源：http://dali.wangshuangyany.cn/Article/details/gtyfmofegf.html

wc -l < a.txt
来源：http://dali.daxiang520.top/Article/details/gtrvhvexfx.html

[R43] 按名字查找文件
来源：http://dali.cucudq.cn/Article/details/gtpopxoetq.html

find . -name "*.log" -type f
来源：http://dali.hfpthk.cn/Article/details/gtizwkoikp.html

[R44] 按修改时间查找
来源：http://dali.ivvv.top/Article/details/gtdfcksauf.html

find . -mtime -7 -type f
来源：http://dali.xylfe.cn/Article/details/gttenhjrwl.html

[R45] 批量删除
来源：http://dali.sufxvd.cn/Article/details/gtflyblmfr.html

find . -name "*.tmp" -delete
来源：http://dali.gzhubu.top/Article/details/gtktxnyiis.html

[R46] 递归替换文件内容
来源：http://dali.xuanzx.com/Article/details/gtdkhwgies.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinqigufen.top/Article/details/gtdobqkcfd.html

[R47] sed 单行替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqzanfgy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zycfv.cn/Article/details/gtowcxguev.html

[R48] awk 取指定列
来源：http://dali.yj202588.top/Article/details/gteurbbheo.html

awk '{print $1, $3}' a.txt
来源：http://dali.daxiang520.top/Article/details/gtpnrqvnpc.html

[R49] awk 带条件
来源：http://dali.sysykeji.top/Article/details/gtboxwmhdk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.svipenyu.cn/Article/details/gtphysrmzp.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gtfekxcifn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hysaishi.cn/Article/details/gtbtqonywp.html

[R51] 排序去重取前几
来源：http://dali.jinghuilouyu.cn/Article/details/gtcoowewiq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenzaomai.com/Article/details/gttlpyzqyt.html

[R52] 统计行数
来源：http://dali.jiagoushi.top/Article/details/gtojxcebmg.html

wc -l a.txt
来源：http://dali.havefunace.top/Article/details/gtxdoxwpyg.html

[R53] 查看文件头与实时尾
来源：http://dali.hnqzz.top/Article/details/gtdhivizst.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj20258888.top/Article/details/gtnjfdzjei.html

[R54] 比较两个文件
来源：http://dali.hammf.cn/Article/details/gtvpsaamgi.html

diff a.txt b.txt
来源：http://dali.yangfankeji.com/Article/details/gtuncbajvy.html

[R55] 压缩与解压
来源：http://dali.zhongyouzk.top/Article/details/gtpwmlqqls.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nwbrower.top/Article/details/gtctbdffcj.html

[R56] 远程拷贝
来源：http://dali.9152youxi.cn/Article/details/gtzdiqbxsc.html

scp file user@host:/path/
来源：http://dali.snrcjt.cn/Article/details/gtnexykrvw.html

[R57] 远程执行命令
来源：http://dali.guannengcc.top/Article/details/gtbwygjpre.html

ssh user@host 'uptime'
来源：http://dali.dianchejie.cn/Article/details/gteltlnmcw.html

[R58] 下载文件
来源：http://dali.pengpengdd.cyou/Article/details/gtflpbbzvl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.wangdashe.top/Article/details/gtamljjcor.html

[R59] 发 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnpwfxxsk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zycfv.cn/Article/details/gtpojahijz.html

[R60] 只看 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gtgzenffcy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sweek.top/Article/details/gtonazirdf.html

[R61] 磁盘占用
来源：http://dali.guannengcc.top/Article/details/gtgbvrwdoy.html

df -h;  du -sh *
来源：http://dali.andypj.xyz/Article/details/gtyextavzx.html

[R62] 找最占空间的文件
来源：http://dali.havefunace.top/Article/details/gtdrzdsrkz.html

du -ah . | sort -rh | head -10
来源：http://dali.yangfankeji.com/Article/details/gtcjczmpzk.html

[R63] 内存与进程
来源：http://dali.gotoacloud.top/Article/details/gtjsuyxnre.html

free -h;  ps aux | grep nginx
来源：http://dali.xuanzx.com/Article/details/gtqhnwvbfg.html

[R64] 结束进程
来源：http://dali.yvedp.cn/Article/details/gtqtfczcna.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jianghu66.top/Article/details/gtnwwvcasb.html

[R65] 查看端口占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfawtmcc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258888.top/Article/details/gtfqzabrrr.html

[R66] 定时任务
来源：http://dali.zhengqikj.top/Article/details/gtvtkmroma.html

crontab -e;  crontab -l
来源：http://dali.nanxuanxn.top/Article/details/gtajyeddkr.html

[R67] 生成随机十六进制串
来源：http://dali.dianchejie.cn/Article/details/gtwmjhgauk.html

openssl rand -hex 16
来源：http://dali.nanxuanxn.top/Article/details/gtrlgeknqe.html

[R68] 计算文件校验值
来源：http://dali.yuxming.cn/Article/details/gtjmgfbvpp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.316326.xyz/Article/details/gtrvjnfbix.html

[R69] 生成随机密码
来源：http://dali.quarkkingdee.top/Article/details/gtqcimfejd.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gttligkvqk.html

[R70] 时间戳与互转
来源：http://dali.hnqzz.top/Article/details/gtgtryzrvu.html

date +%s;  date -d @1700000000
来源：http://dali.guannengcc.top/Article/details/gtklzeumxl.html

[R71] 日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gtartbmwsg.html


<!-- 参考信息 -->