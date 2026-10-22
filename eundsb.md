代发 wailian999

SELECT * FROM users;
来源：http://dali.jianghu66.top/Article/details/gtcvsyaopc.html

[Q16] 查询指定列
来源：http://dali.cqqwz.cn/Article/details/gtmgacewlo.html

SELECT id, name FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gttjxlsqpd.html

[Q17] 条件查询
来源：http://dali.shangyingyoupin.top/Article/details/gthaqombho.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtxotuyjtj.html

[Q18] 模糊匹配
来源：http://dali.cheryme.top/Article/details/gtciafsxif.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shzxlz.cn/Article/details/gtamesnztf.html

[Q19] 范围查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbydsvgrv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tanke756.top/Article/details/gtzmrwwuyr.html

[Q20] IN 列表
来源：http://dali.tanke756.top/Article/details/gtrekmzptm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zycfv.cn/Article/details/gtrmmmqrwi.html

[Q21] 空值判断
来源：http://dali.zhengqikj.top/Article/details/gtwxxfoehs.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.snrcjt.cn/Article/details/gtvfveqeiw.html

[Q22] 排序
来源：http://dali.ybcxt.top/Article/details/gtjmeairxg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.haohaochexian.top/Article/details/gtqevoyljh.html

[Q23] 分页
来源：http://dali.yuxming.cn/Article/details/gtfdmsfqsd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ydzc1.top/Article/details/gtrmvkowsc.html

[Q24] 去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkkihiews.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258.top/Article/details/gtzaguvfts.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjrzqarg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xuetiantiany.cn/Article/details/gtuoqbwzsy.html

[Q26] 计数
来源：http://dali.cheryme.top/Article/details/gtvswinrep.html

SELECT COUNT(*) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrgbpdxv.html

[Q27] 条件计数
来源：http://dali.tianlin.xyz/Article/details/gtkaeqbbat.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nwbrower.top/Article/details/gthyayjmqw.html

[Q28] 求和与平均
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkvsbclfv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtgvqaazop.html

[Q29] 最大最小值
来源：http://dali.c1oappe.top/Article/details/gtweuhbnsc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.havefunace.top/Article/details/gtjprfhxrp.html

[Q30] 分组统计
来源：http://dali.smart0.xyz/Article/details/gtszubthlk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gtjqqgxuuw.html

[Q31] 分组后过滤
来源：http://dali.jianghu66.top/Article/details/gtwhzghoaz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ivvv.top/Article/details/gtwtnherxr.html

[Q32] 分组拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gthjctgnds.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxqxulfv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cheryme.top/Article/details/gtkrxrydxp.html

[Q33] 多列分组
来源：http://dali.fengsongda.top/Article/details/gtuopwpacs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jlsjyb.cn/Article/details/gtjjlbnmhz.html

[Q34] 每组取第一条
来源：http://dali.yj20258.top/Article/details/gtnlwpgkfe.html

SELECT * FROM (
来源：http://dali.vqdsnc.cn/Article/details/gtntvfiqbp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hywenlv.cn/Article/details/gtabbjzmgb.html

) t WHERE rn = 1;
来源：http://dali.redwolf501.top/Article/details/gtucozzdhr.html

[Q35] 内连接
来源：http://dali.zhixingplan.top/Article/details/gttkybvyap.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgfzy.top/Article/details/gthmjnnudh.html

[Q36] 左连接
来源：http://dali.bjfxy.top/Article/details/gtnmjxcbgm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tian-w.cn/Article/details/gtefuattjl.html

[Q37] 右连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjephgvp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jiagoushi.top/Article/details/gtgqqxrwdm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jiagoushi.top/Article/details/gtdtpeaczv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yueranfly.top/Article/details/gtbeqcmbcm.html

[Q39] 自连接（查上下级）
来源：http://dali.daria6918.cn/Article/details/gtabqzxyjz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.smart0.xyz/Article/details/gtdpipmcib.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.feifeiyinyue.top/Article/details/gttzicugcc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhoulong.xyz/Article/details/gthdaewltr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinqigfzy.top/Article/details/gthnpoodfx.html

[Q41] 多表连接
来源：http://dali.cashguo.top/Article/details/gtuuaxynep.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guannengcc.top/Article/details/gtwvauwytb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gtjlsvobzw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xziqi.cn/Article/details/gtsslcpfsi.html

[Q42] 连接条件附加过滤
来源：http://dali.hysaishi.cn/Article/details/gtghjifuyw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.bjfxy.top/Article/details/gtybrhjhyz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nanxinkj.top/Article/details/gtgzfswsoh.html

[Q43] 标量子查询
来源：http://dali.hongshengwenyu.top/Article/details/gtpicrzfnu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.meibo888.top/Article/details/gtdqiulrvp.html

[Q44] IN 子查询
来源：http://dali.shangyingyoupin.top/Article/details/gtfmiwcjgf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jiagoushi.top/Article/details/gtqivawfbe.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxuanxn.top/Article/details/gtxcvcvpum.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzqurtnl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ppjwa.cn/Article/details/gtipymxorw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hfpthk.cn/Article/details/gtidtkfuza.html

[Q47] 与平均值比较
来源：http://dali.daria6918.cn/Article/details/gtsozxagyi.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.birdmap.top/Article/details/gtunarqpal.html

[Q48] CTE 公用表表达式
来源：http://dali.gaohongyu789.top/Article/details/gtxkbkgxkw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj20258888.top/Article/details/gtncdxlchb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj202588.top/Article/details/gtfrnriyjj.html

[Q49] 更新单行
来源：http://dali.jianghu66.top/Article/details/gthbcecupe.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtcprhfblm.html

[Q50] 批量更新
来源：http://dali.sxryk.cn/Article/details/gtldbcuoxt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gtqljcakgb.html

[Q51] 用子查询更新
来源：http://dali.hnxiangtu.top/Article/details/gtrbijnbyt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ydzc1.top/Article/details/gttwctknug.html

[Q52] 删除指定行
来源：http://dali.nwbrower.top/Article/details/gtjvuxzwlb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258888.top/Article/details/gttivuusgj.html

[Q53] 按条件删除
来源：http://dali.nanxuanxn.top/Article/details/gttwkutjhg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gtdcpsxbvh.html

[Q54] 清空表
来源：http://dali.zdqjudy.top/Article/details/gtgomdselv.html

TRUNCATE TABLE logs;
来源：http://dali.dashuyun.cn/Article/details/gtccahyijo.html

[Q55] 排名（并列占位）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdugjpud.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cucudq.cn/Article/details/gtrrrwzrgw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.redwolf501.top/Article/details/gtoxozmwft.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.daria6918.cn/Article/details/gtsvqwxxng.html

[Q57] 行号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufuecmsk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtnihoecpe.html

[Q58] 累计求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtulvuyvkv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtzrqmailu.html

[Q59] 分组内累计
来源：http://dali.aizwys.cn/Article/details/gtejpjunxh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtztztxsbr.html

[Q60] 取上一行 / 下一行
来源：http://dali.smart0.xyz/Article/details/gtaosojilx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hfpthk.cn/Article/details/gtqgdvuiyg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyflpergi.html

[Q61] 移动平均
来源：http://dali.0kj1m.cn/Article/details/gteadorbse.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtuatvlqlt.html

[Q62] 分组占比
来源：http://dali.chenlongwang.top/Article/details/gtwryjlhlw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gtohmngdlo.html

[Q63] 开启事务
来源：http://dali.cqqwz.cn/Article/details/gtvxsuvqqq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnxiangtu.top/Article/details/gthvvobivg.html

[Q64] 提交事务
来源：http://dali.aibaodan.cn/Article/details/gtjlsewypl.html

COMMIT;
来源：http://dali.cucudq.cn/Article/details/gtvvxhmtuz.html

[Q65] 回滚事务
来源：http://dali.vqdsnc.cn/Article/details/gtorvvoacn.html

ROLLBACK;
来源：http://dali.meibo888.top/Article/details/gtetubmcdl.html

[Q66] 行锁查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmzvrcde.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.haohaochexian.top/Article/details/gtpqqolfts.html

[Q67] 设置隔离级别
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvwlbhij.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.fzhhl.top/Article/details/gtqfaoxwwa.html

[Q68] 保存点
来源：http://dali.feifeiyinyue.top/Article/details/gtigveokxt.html

SAVEPOINT sp1;
来源：http://dali.havefunace.top/Article/details/gtntbcxjro.html

ROLLBACK TO sp1;
来源：http://dali.tian-w.cn/Article/details/gtdztwwrei.html

[Q69] 查看执行计划
来源：http://dali.yj20258888.top/Article/details/gtxojoxloz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.snrcjt.cn/Article/details/gtysfduhvz.html

[Q70] 更新统计信息
来源：http://dali.yongpay.top/Article/details/gtknptepdt.html

ANALYZE TABLE users;
来源：http://dali.sxryk.cn/Article/details/gtwfsynkhw.html

[Q71] 查看建表语句
来源：http://dali.nanxuanxn.top/Article/details/gtpqpzmgov.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yvedp.cn/Article/details/gtpmsfomob.html

[Q72] 查看索引
来源：http://dali.jianghu66.top/Article/details/gtbqoqfzkv.html

SHOW INDEX FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtmuyplhup.html

[Q73] 查看表状态
来源：http://dali.aibaodan.cn/Article/details/gtxhgdkuwn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yueranfly.top/Article/details/gtflrrypsy.html

[Q74] 强制使用索引
来源：http://dali.yueranfly.top/Article/details/gtlvrufqlv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.bjfxy.top/Article/details/gtpsukljyn.html

[Q75] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gtnonfsiza.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtcdetaqjy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yongpay.top/Article/details/gtyevghhft.html

[Q76] 按天统计
来源：http://dali.wangshuangyany.cn/Article/details/gtwhnmfppv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sxryk.cn/Article/details/gtzxccmeqm.html

[Q77] 时间加减
来源：http://dali.zycfv.cn/Article/details/gtfwxbiqez.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj202588.top/Article/details/gtwpqwtiko.html

[Q78] 当前时间
来源：http://dali.tanke756.top/Article/details/gtzevongpu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.snrcjt.cn/Article/details/gtiueofrea.html

[Q79] 字符串拼接
来源：http://dali.zdqjudy.top/Article/details/gtflsccijc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xuetiantiany.cn/Article/details/gtmldgtwqp.html

[Q80] 字符串截取
来源：http://dali.hywenlv.cn/Article/details/gtyyurtmhf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.316326.xyz/Article/details/gtmlaxxozp.html

[Q81] 字符串替换
来源：http://dali.316326.xyz/Article/details/gtsdmpbaks.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xuanzx.com/Article/details/gtqmvpvinw.html

[Q82] 字符长度与字节长度
来源：http://dali.hnqzz.top/Article/details/gtzvgsiwah.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtsikxmojx.html

[Q83] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gtbuuczgrw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtupbqstsf.html

[Q84] 去除首尾空格
来源：http://dali.jqgufenzy.top/Article/details/gtkpjhluzc.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gtlxukipuo.html

[Q85] 数值取整
来源：http://dali.dianchejie.cn/Article/details/gtbvayzzyx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinqigfzy.top/Article/details/gtaifjzdyb.html

[Q86] 读取 JSON 字段
来源：http://dali.jlsjyb.cn/Article/details/gtkhrrqiww.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbspxpqkr.html

[Q87] JSON 字段做条件
来源：http://dali.sysykeji.top/Article/details/gtvyynwjja.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ppjwa.cn/Article/details/gtnrwjxrdf.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnxiangtu.top/Article/details/gtrwhxxvwm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenlongwang.top/Article/details/gtjunvxrkg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlunxpegy.html

[Q89] 判断表是否存在
来源：http://dali.c1oappe.top/Article/details/gtzrrlrybi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.svipenyu.cn/Article/details/gteqomyacx.html

[Q90] 生成序号列
来源：http://dali.ydzc1.top/Article/details/gtcnbxxjae.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinqigfzy.top/Article/details/gtsvyhjgvx.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtifxddfgq.html

R. Bash 专题
来源：http://dali.aibaodan.cn/Article/details/gtvwuluorj.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtthlueazd.html

[R01] shebang 与严格模式
来源：http://dali.jinqigufen.top/Article/details/gtafqzcgtj.html

#!/usr/bin/env bash
来源：http://dali.yongpay.top/Article/details/gtkjuyyibx.html

set -euo pipefail
来源：http://dali.gaohongyu789.top/Article/details/gtpemmjenc.html

[R02] 变量赋值与使用
来源：http://dali.ehwqpu.com/Article/details/gtgcgiwvtd.html

name="Tom"; echo "$name"
来源：http://dali.xziqi.cn/Article/details/gtvuhexugz.html

[R03] 只读变量
来源：http://dali.hfpthk.cn/Article/details/gtgiugwnpn.html

readonly PI=3.14
来源：http://dali.shangyingyoupin.top/Article/details/gtwrunrxdi.html

[R04] 位置参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskfychhc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.haohaochexian.top/Article/details/gtwbnahxkn.html

[R05] 参数默认值
来源：http://dali.hnxiangtu.top/Article/details/gtpilwtmaq.html

name="${1:-default}"
来源：http://dali.bjfxy.top/Article/details/gttdahmtxi.html

[R06] 判断命令是否存在
来源：http://dali.xziqi.cn/Article/details/gtxjlscyuo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xylfe.cn/Article/details/gtolhcbteg.html

[R07] if 判断文件
来源：http://dali.xuanzx.com/Article/details/gtohgmywxo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtckhsetjb.html

[R08] 数值比较
来源：http://dali.yuanzhike.top/Article/details/gtgegmgrem.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gotoacloud.top/Article/details/gtuibrvpot.html

[R09] 字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gtpojgfuij.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhengqikj.top/Article/details/gtogivlyxr.html

[R10] 正则匹配
来源：http://dali.yonumen.top/Article/details/gthonweyqt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.haohaochexian.top/Article/details/gtsqucadlx.html

[R11] case 多分支
来源：http://dali.sufxvd.cn/Article/details/gthuariwca.html

case "$1" in
来源：http://dali.ehwqpu.com/Article/details/gtupgtqkrs.html

start) echo "启动" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrzjtmut.html

stop)  echo "停止" ;;
来源：http://dali.jqgufenzy.top/Article/details/gtbmxxjzxk.html

*)     echo "未知命令" ;;
来源：http://dali.snrcjt.cn/Article/details/gttboyecea.html

esac
来源：http://dali.havefunace.top/Article/details/gthnnceuhl.html

[R12] for 遍历文件
来源：http://dali.0kj1m.cn/Article/details/gtvpixzufx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sxryk.cn/Article/details/gtourxludt.html

[R13] for 计数循环
来源：http://dali.kuanghao11.cn/Article/details/gtbvkmbgkz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.feifeiyinyue.top/Article/details/gttoifbfcg.html

[R14] C 风格 for
来源：http://dali.yanxiufei.cn/Article/details/gtxixfwazg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhoulong.xyz/Article/details/gtcyiffjng.html

[R15] while 逐行读文件
来源：http://dali.hammf.cn/Article/details/gtztfknldf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cashguo.top/Article/details/gtnsaukixi.html

[R16] until 等待条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtobeomvtw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gttifttbut.html

[R17] 数组定义与取值
来源：http://dali.ehwqpu.com/Article/details/gtfdiybbpk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.9152youxi.cn/Article/details/gtymquvhfy.html

[R18] 遍历数组
来源：http://dali.chenlongwang.top/Article/details/gtaiwhjqjj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guannengcc.top/Article/details/gtrznjnjhq.html

[R19] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gteyoxgpjz.html

echo "${#arr[@]}"
来源：http://dali.hnxiangtu.top/Article/details/gtxofcyugj.html

[R20] 关联数组（字典）
来源：http://dali.9152youxi.cn/Article/details/gtadmdnaon.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhengqikj.top/Article/details/gtxlqecpjv.html

[R21] 字符串长度
来源：http://dali.ydzc1.top/Article/details/gtcoprrfhy.html

echo "${#s}"
来源：http://dali.haohaochexian.top/Article/details/gtqcffukij.html

[R22] 截取子串
来源：http://dali.daxiang520.top/Article/details/gtcwyjbhfp.html

echo "${s:0:5}"
来源：http://dali.ybcxt.top/Article/details/gtynrmkelz.html

[R23] 字符串替换
来源：http://dali.cheryme.top/Article/details/gtcnekidae.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ydzc1.top/Article/details/gtcyyzqrzj.html

[R24] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtpgyvbaat.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigfzy.top/Article/details/gtctjivwow.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgufenzy.top/Article/details/gtesellwoy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenjidiqi.icu/Article/details/gtqbnfzhoa.html

[R26] 命令替换
来源：http://dali.gaohongyu789.top/Article/details/gtlcwiqhgp.html

now=$(date +%F); echo "$now"
来源：http://dali.kuanghao11.cn/Article/details/gtjdybwwuf.html

[R27] 算术展开
来源：http://dali.iojbl.cn/Article/details/gtzeklbiau.html

echo $((1 + 2 * 3))
来源：http://dali.jqgufenzy.top/Article/details/gtwcoefjgc.html

[R28] 浮点运算
来源：http://dali.sufxvd.cn/Article/details/gtbqvcyjsv.html

echo "scale=2; 10/3" | bc
来源：http://dali.ppjwa.cn/Article/details/gtylqrlbkl.html

[R29] 定义函数
来源：http://dali.daria6918.cn/Article/details/gtfejdizju.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guannengcc.top/Article/details/gtgwltbqux.html

[R30] 函数返回状态码
来源：http://dali.chenzaomai.com/Article/details/gtpoglssgz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfkvijgdk.html

[R31] 局部变量
来源：http://dali.hywenlv.cn/Article/details/gtsrxqhowq.html

f() { local x=1; echo "$x"; }
来源：http://dali.ivvv.top/Article/details/gtznkfbeax.html

[R32] 参数个数校验
来源：http://dali.chenjidiqi.icu/Article/details/gtlrnvyprr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gtbfgdgilf.html

[R33] 捕获错误并提示行号
来源：http://dali.hfpthk.cn/Article/details/gtrzdtizas.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xuetiantiany.cn/Article/details/gtxopvyvbj.html

[R34] 退出时清理
来源：http://dali.ppjwa.cn/Article/details/gtwwsmxzvl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gttwljnbdw.html

[R35] 后台执行并等待
来源：http://dali.feifeiyinyue.top/Article/details/gtoipydutj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xuanzx.com/Article/details/gtdlljwurh.html

[R36] 并发执行多个任务
来源：http://dali.hnxiangtu.top/Article/details/gtdnddztlx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgpgukqg.html

[R37] 把输出赋给变量
来源：http://dali.yj20258.top/Article/details/gtktwqyzkh.html

files=$(ls -1)
来源：http://dali.yuxming.cn/Article/details/gtxajogosk.html

[R38] 管道串联
来源：http://dali.xinyue.icu/Article/details/gtbkftxogp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.vqdsnc.cn/Article/details/gtmtreisap.html

[R39] 重定向标准输出与错误
来源：http://dali.cucudq.cn/Article/details/gtasrcwrle.html

cmd > out.log 2>&1
来源：http://dali.jinqigufen.top/Article/details/gtdhspotkp.html

[R40] 追加写日志
来源：http://dali.wangshuangyany.cn/Article/details/gtubobdvdk.html

echo "log" >> out.log
来源：http://dali.hywenlv.cn/Article/details/gtsrgkogqa.html

[R41] 丢弃输出
来源：http://dali.yuanzhike.top/Article/details/gttveqwgux.html

cmd >/dev/null 2>&1
来源：http://dali.pycfn.com/Article/details/gtmsjrqlba.html

[R42] 输入重定向
来源：http://dali.chenjidiqi.icu/Article/details/gtljskmucr.html

wc -l < a.txt
来源：http://dali.ydzc1.top/Article/details/gtmgfuwdlw.html

[R43] 按名字查找文件
来源：http://dali.gogol.net.cn/Article/details/gtgkidpsqb.html

find . -name "*.log" -type f
来源：http://dali.xylfe.cn/Article/details/gtigjuamzr.html

[R44] 按修改时间查找
来源：http://dali.yongpay.top/Article/details/gttyrygyjg.html

find . -mtime -7 -type f
来源：http://dali.9152youxi.cn/Article/details/gtlgqiiiov.html

[R45] 批量删除
来源：http://dali.pycfn.com/Article/details/gteuqkigcu.html

find . -name "*.tmp" -delete
来源：http://dali.chenzaomai.com/Article/details/gtilcksyfl.html

[R46] 递归替换文件内容
来源：http://dali.pengpengdd.cyou/Article/details/gtkckpioui.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.redwolf501.top/Article/details/gtzwufhjiq.html

[R47] sed 单行替换
来源：http://dali.mhx1999.top/Article/details/gtlienkvge.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ehwqpu.com/Article/details/gtlfyguydn.html

[R48] awk 取指定列
来源：http://dali.jqgufenzy.top/Article/details/gtxahibjbf.html

awk '{print $1, $3}' a.txt
来源：http://dali.bjfxy.top/Article/details/gtjzvbnrby.html

[R49] awk 带条件
来源：http://dali.nwbrower.top/Article/details/gtgoczffqe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinqigfzy.top/Article/details/gtkkrljfia.html

[R50] awk 求和
来源：http://dali.sysykeji.top/Article/details/gtosjapqzi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtivgnbyth.html

[R51] 排序去重取前几
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzbqwvowr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuxming.cn/Article/details/gtxbhhouwn.html

[R52] 统计行数
来源：http://dali.sweek.top/Article/details/gtrgwczuvb.html

wc -l a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtejzjmmoq.html

[R53] 查看文件头与实时尾
来源：http://dali.ppjwa.cn/Article/details/gtzkcjheai.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangdashe.top/Article/details/gtsxyzngkw.html

[R54] 比较两个文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvqulgdg.html

diff a.txt b.txt
来源：http://dali.ivvv.top/Article/details/gtngbqwjvo.html

[R55] 压缩与解压
来源：http://dali.cdnleiting.top/Article/details/gtgrxdatgr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjznsbzr.html

[R56] 远程拷贝
来源：http://dali.yongpay.top/Article/details/gtolyucaoz.html

scp file user@host:/path/
来源：http://dali.kuanghao11.cn/Article/details/gtmtaxeywy.html

[R57] 远程执行命令
来源：http://dali.hongshengwenyu.top/Article/details/gtkjtoghuv.html

ssh user@host 'uptime'
来源：http://dali.sysykeji.top/Article/details/gtoujpgvtc.html

[R58] 下载文件
来源：http://dali.meibo888.top/Article/details/gteiaoilki.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.316326.xyz/Article/details/gtmuhbdrbz.html

[R59] 发 POST JSON
来源：http://dali.ydzc1.top/Article/details/gtzaieihlb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jqgufenzy.top/Article/details/gtejhyfgwm.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gtjncyqggi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gaohongyu789.top/Article/details/gtvpuowkhg.html

[R61] 磁盘占用
来源：http://dali.cashguo.top/Article/details/gtbnupkmwg.html

df -h;  du -sh *
来源：http://dali.hnxiangtu.top/Article/details/gtattuonog.html

[R62] 找最占空间的文件
来源：http://dali.fengsongda.top/Article/details/gtlinsnqsy.html

du -ah . | sort -rh | head -10
来源：http://dali.aibaodan.cn/Article/details/gteudpeend.html

[R63] 内存与进程
来源：http://dali.sysykeji.top/Article/details/gtpcdspstf.html

free -h;  ps aux | grep nginx
来源：http://dali.shzxlz.cn/Article/details/gtcuqyozqp.html

[R64] 结束进程
来源：http://dali.zhiwuduotai.top/Article/details/gtaaqeqtoh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tianlin.xyz/Article/details/gttmbqauko.html

[R65] 查看端口占用
来源：http://dali.ybcxt.top/Article/details/gtilxaumxw.html


<!-- 参考信息 -->