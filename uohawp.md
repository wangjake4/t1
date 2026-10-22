代发 wailian999

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj202588.top/Article/details/gtlhkcrpgs.html

[Q20] IN 列表
来源：http://dali.yonumen.top/Article/details/gtwrjeqhmv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nanxuanxn.top/Article/details/gttokuaobf.html

[Q21] 空值判断
来源：http://dali.zhiwuduotai.top/Article/details/gtocjltgik.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fengsongda.top/Article/details/gtpxwwdsxl.html

[Q22] 排序
来源：http://dali.gaohongyu789.top/Article/details/gtxzbaugqa.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhengqikj.top/Article/details/gtfzdhuqyf.html

[Q23] 分页
来源：http://dali.xuanzx.com/Article/details/gtwmuebvox.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cheryme.top/Article/details/gtqcymjeap.html

[Q24] 去重
来源：http://dali.gaohongyu789.top/Article/details/gtjjlxirak.html

SELECT DISTINCT city FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtjpbyzclv.html

[Q25] 只取前 N 条
来源：http://dali.havefunace.top/Article/details/gtrxypkkuj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhongyouzk.top/Article/details/gtoonxcpko.html

[Q26] 计数
来源：http://dali.yvedp.cn/Article/details/gtfpwhohpi.html

SELECT COUNT(*) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtddvrxhib.html

[Q27] 条件计数
来源：http://dali.yanxiufei.cn/Article/details/gthzgshweb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangdashe.top/Article/details/gtfdsnisdg.html

[Q28] 求和与平均
来源：http://dali.cashguo.top/Article/details/gtwmdbnrbf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtgaqxeieb.html

[Q29] 最大最小值
来源：http://dali.guowangkeji.top/Article/details/gtfibckeau.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gttbfyjvbd.html

[Q30] 分组统计
来源：http://dali.wangshuangyany.cn/Article/details/gtbqmpibuo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gtlqysuxrf.html

[Q31] 分组后过滤
来源：http://dali.cheryme.top/Article/details/gtcduqsfjm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xziqi.cn/Article/details/gttnqlistb.html

[Q32] 分组拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtazidqzos.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtqosueooh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hnqzz.top/Article/details/gtcluncqrd.html

[Q33] 多列分组
来源：http://dali.9152youxi.cn/Article/details/gtglyzxgaw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hywenlv.cn/Article/details/gtethzwwqs.html

[Q34] 每组取第一条
来源：http://dali.sufxvd.cn/Article/details/gthverhdnt.html

SELECT * FROM (
来源：http://dali.jiagoushi.top/Article/details/gtxlaeksew.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pengpengdd.cyou/Article/details/gtpertydpf.html

) t WHERE rn = 1;
来源：http://dali.jyoumei.cn/Article/details/gtknentutj.html

[Q35] 内连接
来源：http://dali.hongshengwenyu.top/Article/details/gtqyyhhdef.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmsdcbbez.html

[Q36] 左连接
来源：http://dali.zycfv.cn/Article/details/gtlppqoesp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jianghu66.top/Article/details/gtldqmbftt.html

[Q37] 右连接
来源：http://dali.snrcjt.cn/Article/details/gtthecavth.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuanzx.com/Article/details/gtkhtcmgjg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yanxiufei.cn/Article/details/gtbjyjuiml.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258.top/Article/details/gtyhrumjpl.html

[Q39] 自连接（查上下级）
来源：http://dali.c1oappe.top/Article/details/gtihmzwqsr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tanke756.top/Article/details/gtrhopqlxg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gaohongyu789.top/Article/details/gtptadwtoa.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cashguo.top/Article/details/gtoqiljybc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhongyouzk.top/Article/details/gthcdqqknu.html

[Q41] 多表连接
来源：http://dali.cdnleiting.top/Article/details/gtxrcofoci.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.dashuyun.cn/Article/details/gtwyvxsmcj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcjvdqwj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xinyue.icu/Article/details/gtvkdjcwlj.html

[Q42] 连接条件附加过滤
来源：http://dali.pycfn.com/Article/details/gtdvnmdtdv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoazgzoqz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj202588.top/Article/details/gtrgbuatsu.html

[Q43] 标量子查询
来源：http://dali.havefunace.top/Article/details/gtxszdzdfu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yj202588.top/Article/details/gtnrdhufjt.html

[Q44] IN 子查询
来源：http://dali.jqgufenzy.top/Article/details/gtfyzswccw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yongpay.top/Article/details/gtvjmffzcj.html

[Q45] EXISTS 判断存在
来源：http://dali.haohaochexian.top/Article/details/gtdyfspysd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.bjfxy.top/Article/details/gtjkkwezzj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ppjwa.cn/Article/details/gtfoawijrr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tianlin.xyz/Article/details/gtfzegtstw.html

[Q47] 与平均值比较
来源：http://dali.vqdsnc.cn/Article/details/gtovceaezg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.bjfxy.top/Article/details/gtlccwmiif.html

[Q48] CTE 公用表表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtbqnlxmba.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiaphrbrb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.iojbl.cn/Article/details/gtabvoqlzn.html

[Q49] 更新单行
来源：http://dali.cdnleiting.top/Article/details/gthxykhohi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuanzx.com/Article/details/gtnttokujs.html

[Q50] 批量更新
来源：http://dali.xuanzx.com/Article/details/gtkwcmsmxt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aibaodan.cn/Article/details/gtzrblhywr.html

[Q51] 用子查询更新
来源：http://dali.wangshuangyany.cn/Article/details/gtqzwlwunk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cqqwz.cn/Article/details/gtoctqphrk.html

[Q52] 删除指定行
来源：http://dali.fzhhl.top/Article/details/gtmcldbgjy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtmytfczsr.html

[Q53] 按条件删除
来源：http://dali.gaohongyu789.top/Article/details/gtzmnamvto.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.guannengcc.top/Article/details/gthezlprwc.html

[Q54] 清空表
来源：http://dali.dianchejie.cn/Article/details/gtgsaqwueq.html

TRUNCATE TABLE logs;
来源：http://dali.yongpay.top/Article/details/gtfmsqntsx.html

[Q55] 排名（并列占位）
来源：http://dali.chenjidiqi.icu/Article/details/gtncseogyv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gtzogdveva.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcnuymhb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtcpeesrfo.html

[Q57] 行号
来源：http://dali.bjfxy.top/Article/details/gttgxlblqb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.316326.xyz/Article/details/gtvpnbuspb.html

[Q58] 累计求和
来源：http://dali.dianchejie.cn/Article/details/gtgnaxdeal.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtncrrczbw.html

[Q59] 分组内累计
来源：http://dali.cdnleiting.top/Article/details/gtsjabammv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtbkegkqgv.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj20258.top/Article/details/gtklzakzbb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xylfe.cn/Article/details/gtcqwnlali.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtcpyodhex.html

[Q61] 移动平均
来源：http://dali.yvedp.cn/Article/details/gtuswwhesd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gturyfvvwn.html

[Q62] 分组占比
来源：http://dali.chenlongwang.top/Article/details/gtaogjlkln.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gtmeujnqpn.html

[Q63] 开启事务
来源：http://dali.cheryme.top/Article/details/gtjzkvvkjc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gzhubu.top/Article/details/gtxmecvlnf.html

[Q64] 提交事务
来源：http://dali.iojbl.cn/Article/details/gtpurzdwix.html

COMMIT;
来源：http://dali.feifeiyinyue.top/Article/details/gtfxjkjglu.html

[Q65] 回滚事务
来源：http://dali.sufxvd.cn/Article/details/gtscgfqarv.html

ROLLBACK;
来源：http://dali.chenlongwang.top/Article/details/gtpksvpnrx.html

[Q66] 行锁查询
来源：http://dali.aibaodan.cn/Article/details/gtwpxaxplc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tanke756.top/Article/details/gtfhefpvmf.html

[Q67] 设置隔离级别
来源：http://dali.guowangkeji.top/Article/details/gtgkqvbyhc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dashuyun.cn/Article/details/gtnotwtoxe.html

[Q68] 保存点
来源：http://dali.chenlongwang.top/Article/details/gtioxnrebe.html

SAVEPOINT sp1;
来源：http://dali.snrcjt.cn/Article/details/gtxfdmcmyp.html

ROLLBACK TO sp1;
来源：http://dali.ppjwa.cn/Article/details/gtxbwnmqbp.html

[Q69] 查看执行计划
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrqcmeuw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hfpthk.cn/Article/details/gtarkimvjl.html

[Q70] 更新统计信息
来源：http://dali.pengpengdd.cyou/Article/details/gtoafhugzy.html

ANALYZE TABLE users;
来源：http://dali.birdmap.top/Article/details/gtzodchjlj.html

[Q71] 查看建表语句
来源：http://dali.cdnleiting.top/Article/details/gtgxjbirsg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinqigufen.top/Article/details/gtnoguqkdt.html

[Q72] 查看索引
来源：http://dali.gotoacloud.top/Article/details/gtuepwgdil.html

SHOW INDEX FROM users;
来源：http://dali.wangdashe.top/Article/details/gtnoypzrby.html

[Q73] 查看表状态
来源：http://dali.jlsjyb.cn/Article/details/gtmdjgghfa.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinqigfzy.top/Article/details/gtgkpcults.html

[Q74] 强制使用索引
来源：http://dali.sweek.top/Article/details/gtndtloxkq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuetiantiany.cn/Article/details/gtbmwlvlih.html

[Q75] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gtxxicizuk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtpprfglhu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrrfjssz.html

[Q76] 按天统计
来源：http://dali.guowangkeji.top/Article/details/gtdwzyqruk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zdqjudy.top/Article/details/gtdvofooez.html

[Q77] 时间加减
来源：http://dali.316326.xyz/Article/details/gtrjaprahi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daria6918.cn/Article/details/gtqtsjusln.html

[Q78] 当前时间
来源：http://dali.xziqi.cn/Article/details/gteqikgmwt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.fzhhl.top/Article/details/gtdtkftbos.html

[Q79] 字符串拼接
来源：http://dali.dianchejie.cn/Article/details/gttjvffhpi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hysaishi.cn/Article/details/gtclkufftq.html

[Q80] 字符串截取
来源：http://dali.zhoulong.xyz/Article/details/gtidvxlmbm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtypbsqbnc.html

[Q81] 字符串替换
来源：http://dali.jlsjyb.cn/Article/details/gtlazqxnvk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.iojbl.cn/Article/details/gtcxpyvoje.html

[Q82] 字符长度与字节长度
来源：http://dali.yuanzhike.top/Article/details/gtxnfgzlwt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtynhqnxoc.html

[Q83] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gtudewsrmn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtvsewbhjk.html

[Q84] 去除首尾空格
来源：http://dali.jqgfzy.top/Article/details/gtpwbggrux.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gteivyzrex.html

[Q85] 数值取整
来源：http://dali.yj20258.top/Article/details/gtdjpnogtj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ppjwa.cn/Article/details/gtcahfixyk.html

[Q86] 读取 JSON 字段
来源：http://dali.cashguo.top/Article/details/gtnajtrfkq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.daxiang520.top/Article/details/gtzttmynec.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gtsarpjjeq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gtqiumhxhz.html

[Q88] 行转列（条件聚合）
来源：http://dali.sweek.top/Article/details/gtliakuzkz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ppjwa.cn/Article/details/gthlzbrgdz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gthpxiestc.html

[Q89] 判断表是否存在
来源：http://dali.hywenlv.cn/Article/details/gtbyzdjjdl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gtofwrcqrz.html

[Q90] 生成序号列
来源：http://dali.aibaodan.cn/Article/details/gtutljnjel.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinqigfzy.top/Article/details/gtwwnxukvm.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gteciizkhl.html

R. Bash 专题
来源：http://dali.fzhhl.top/Article/details/gtejfnmffj.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtxnadoqnr.html

[R01] shebang 与严格模式
来源：http://dali.tanke756.top/Article/details/gtyfmjslzy.html

#!/usr/bin/env bash
来源：http://dali.smart0.xyz/Article/details/gtvnrdtisn.html

set -euo pipefail
来源：http://dali.aizwys.cn/Article/details/gtcprknwwd.html

[R02] 变量赋值与使用
来源：http://dali.dashuyun.cn/Article/details/gturdwduic.html

name="Tom"; echo "$name"
来源：http://dali.hfpthk.cn/Article/details/gthxhaavyj.html

[R03] 只读变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiangspoj.html

readonly PI=3.14
来源：http://dali.aizwys.cn/Article/details/gtyoywrhji.html

[R04] 位置参数
来源：http://dali.9152youxi.cn/Article/details/gtdafvugtc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yonumen.top/Article/details/gthcnsghgl.html

[R05] 参数默认值
来源：http://dali.bjfxy.top/Article/details/gtxhfxtlac.html

name="${1:-default}"
来源：http://dali.cheryme.top/Article/details/gthwhbvbul.html

[R06] 判断命令是否存在
来源：http://dali.chenzaomai.com/Article/details/gtflgltwjt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gtgjynoxcc.html

[R07] if 判断文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemcccark.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.redwolf501.top/Article/details/gtsjshorzi.html

[R08] 数值比较
来源：http://dali.hysaishi.cn/Article/details/gtbriefxzw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.aizwys.cn/Article/details/gtwoczyiaf.html

[R09] 字符串比较
来源：http://dali.hnqzz.top/Article/details/gtafdmydsf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ivvv.top/Article/details/gtxhebwfjk.html

[R10] 正则匹配
来源：http://dali.ehwqpu.com/Article/details/gthiwkaohk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.c1oappe.top/Article/details/gtytsmhyld.html

[R11] case 多分支
来源：http://dali.havefunace.top/Article/details/gtgdbayohu.html

case "$1" in
来源：http://dali.jiagoushi.top/Article/details/gtbamfankw.html

start) echo "启动" ;;
来源：http://dali.cucudq.cn/Article/details/gtusmtxpog.html

stop)  echo "停止" ;;
来源：http://dali.hysaishi.cn/Article/details/gtdbtytndm.html

*)     echo "未知命令" ;;
来源：http://dali.316326.xyz/Article/details/gtspnmdwnj.html

esac
来源：http://dali.xinyue.icu/Article/details/gtmndbyxrs.html

[R12] for 遍历文件
来源：http://dali.chenlongwang.top/Article/details/gthsmhgmqc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.birdmap.top/Article/details/gtyehpuspr.html

[R13] for 计数循环
来源：http://dali.zdqjudy.top/Article/details/gtwjaojfau.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaosjeacm.html

[R14] C 风格 for
来源：http://dali.haohaochexian.top/Article/details/gttqxytuda.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nanxuanxn.top/Article/details/gtjazifoac.html

[R15] while 逐行读文件
来源：http://dali.cashguo.top/Article/details/gtpwaezurq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangshuangyany.cn/Article/details/gthmkxdwmz.html

[R16] until 等待条件
来源：http://dali.gzhubu.top/Article/details/gtgbbmuuzv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gtifnockcn.html

[R17] 数组定义与取值
来源：http://dali.tianlin.xyz/Article/details/gtolawrinx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hammf.cn/Article/details/gtrjspekrk.html

[R18] 遍历数组
来源：http://dali.meibo888.top/Article/details/gtafczgnjz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.smart0.xyz/Article/details/gtjdinesrc.html

[R19] 数组长度
来源：http://dali.tian-w.cn/Article/details/gtxjikoyps.html

echo "${#arr[@]}"
来源：http://dali.zhixingplan.top/Article/details/gtgrqtecbj.html

[R20] 关联数组（字典）
来源：http://dali.cashguo.top/Article/details/gtzupwbrua.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cucudq.cn/Article/details/gtvxdvoaak.html

[R21] 字符串长度
来源：http://dali.dashuyun.cn/Article/details/gtcarfnkyf.html

echo "${#s}"
来源：http://dali.zhoulong.xyz/Article/details/gtwyhffpeq.html

[R22] 截取子串
来源：http://dali.meibo888.top/Article/details/gtkzqdtivv.html

echo "${s:0:5}"
来源：http://dali.zhongyouzk.top/Article/details/gtmkqlimjc.html

[R23] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gtlnkstpll.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgfzy.top/Article/details/gtvemprqwr.html

[R24] 大小写转换
来源：http://dali.havefunace.top/Article/details/gtgzjzqezr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjbdsgqe.html

[R25] 去后缀 / 去前缀
来源：http://dali.shangyingyoupin.top/Article/details/gtulgtbvtl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuanzx.com/Article/details/gtxhybhuhf.html

[R26] 命令替换
来源：http://dali.vqdsnc.cn/Article/details/gtiqdpnpfa.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigufen.top/Article/details/gtlaoxoudu.html

[R27] 算术展开
来源：http://dali.xziqi.cn/Article/details/gtamyuijet.html

echo $((1 + 2 * 3))
来源：http://dali.havefunace.top/Article/details/gtxvjzytdj.html

[R28] 浮点运算
来源：http://dali.iojbl.cn/Article/details/gtkzybmbhe.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnqzz.top/Article/details/gteurllkai.html

[R29] 定义函数
来源：http://dali.yj202588.top/Article/details/gtmeinfxwb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigfzy.top/Article/details/gtqzznbtpn.html

[R30] 函数返回状态码
来源：http://dali.chenjidiqi.icu/Article/details/gtqkqdcvbi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gotoacloud.top/Article/details/gtylkshuog.html

[R31] 局部变量
来源：http://dali.svipenyu.cn/Article/details/gtzljgtegc.html

f() { local x=1; echo "$x"; }
来源：http://dali.ehwqpu.com/Article/details/gtoycjegqe.html

[R32] 参数个数校验
来源：http://dali.jinqigfzy.top/Article/details/gtfbupysxe.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.feifeiyinyue.top/Article/details/gtflgzkfvw.html

[R33] 捕获错误并提示行号
来源：http://dali.c1oappe.top/Article/details/gttnaqnvap.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsyqufvkd.html

[R34] 退出时清理
来源：http://dali.xinyue.icu/Article/details/gtydierxho.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gtdbqpmbua.html

[R35] 后台执行并等待
来源：http://dali.xylfe.cn/Article/details/gtmktxvfja.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenjidiqi.icu/Article/details/gtlfbqbdcn.html

[R36] 并发执行多个任务
来源：http://dali.quarkkingdee.top/Article/details/gtzaymeeil.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.vqdsnc.cn/Article/details/gtnzbuygow.html

[R37] 把输出赋给变量
来源：http://dali.yonumen.top/Article/details/gtypzmvdem.html

files=$(ls -1)
来源：http://dali.zhoulong.xyz/Article/details/gtvnoerhko.html

[R38] 管道串联
来源：http://dali.hysaishi.cn/Article/details/gtpktkhqki.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhixingplan.top/Article/details/gtssniqusu.html

[R39] 重定向标准输出与错误
来源：http://dali.birdmap.top/Article/details/gtnguieeib.html

cmd > out.log 2>&1
来源：http://dali.yanxiufei.cn/Article/details/gtmeyseace.html

[R40] 追加写日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumavtoso.html

echo "log" >> out.log
来源：http://dali.pengpengdd.cyou/Article/details/gttznjzpho.html

[R41] 丢弃输出
来源：http://dali.daria6918.cn/Article/details/gtznfcktdz.html

cmd >/dev/null 2>&1
来源：http://dali.yuxming.cn/Article/details/gtcbdkpmyz.html

[R42] 输入重定向
来源：http://dali.nwbrower.top/Article/details/gtflvsxvyz.html

wc -l < a.txt
来源：http://dali.fengsongda.top/Article/details/gtelnmqsox.html

[R43] 按名字查找文件
来源：http://dali.shangyingyoupin.top/Article/details/gticfpggsx.html

find . -name "*.log" -type f
来源：http://dali.cheryme.top/Article/details/gtquccxmhs.html

[R44] 按修改时间查找
来源：http://dali.havefunace.top/Article/details/gtixhgzvzy.html

find . -mtime -7 -type f
来源：http://dali.jqgfzy.top/Article/details/gtxnkfrtgk.html

[R45] 批量删除
来源：http://dali.gaohongyu789.top/Article/details/gtjyvplqrd.html

find . -name "*.tmp" -delete
来源：http://dali.yonumen.top/Article/details/gtsgtoicxe.html

[R46] 递归替换文件内容
来源：http://dali.316326.xyz/Article/details/gtgfhkxudk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.aibaodan.cn/Article/details/gtwgyigenb.html

[R47] sed 单行替换
来源：http://dali.yj202588.top/Article/details/gtaanpooyl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtvpftmnog.html

[R48] awk 取指定列
来源：http://dali.yj20258.top/Article/details/gtcfmvvjat.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtfdvadqde.html

[R49] awk 带条件
来源：http://dali.fzhhl.top/Article/details/gtfdwjkblg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sweek.top/Article/details/gtlgrblwxr.html

[R50] awk 求和
来源：http://dali.wangshuangyany.cn/Article/details/gtboxdggez.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gotoacloud.top/Article/details/gtzwyvwwnj.html

[R51] 排序去重取前几
来源：http://dali.ydzc1.top/Article/details/gtucexjdrm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.mhx1999.top/Article/details/gtjenzxson.html

[R52] 统计行数
来源：http://dali.ehwqpu.com/Article/details/gtxwomffyx.html

wc -l a.txt
来源：http://dali.sxryk.cn/Article/details/gtvpomfhmh.html

[R53] 查看文件头与实时尾
来源：http://dali.hnxiangtu.top/Article/details/gtocjotcis.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hysaishi.cn/Article/details/gtziapcxxj.html

[R54] 比较两个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmwfuhoum.html

diff a.txt b.txt
来源：http://dali.sxryk.cn/Article/details/gtbuojxhlw.html

[R55] 压缩与解压
来源：http://dali.jlsjyb.cn/Article/details/gtnceduasa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.9152youxi.cn/Article/details/gtggpcqbnr.html

[R56] 远程拷贝
来源：http://dali.yvedp.cn/Article/details/gtovnbwhln.html

scp file user@host:/path/
来源：http://dali.cqqwz.cn/Article/details/gtzhinvwoj.html

[R57] 远程执行命令
来源：http://dali.jinghuilouyu.cn/Article/details/gtcsfblnww.html

ssh user@host 'uptime'
来源：http://dali.pycfn.com/Article/details/gtwvypamrk.html

[R58] 下载文件
来源：http://dali.yj20258.top/Article/details/gtdgauvlbw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yuanzhike.top/Article/details/gtcaqtiqmn.html

[R59] 发 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gtnompdlja.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gaohongyu789.top/Article/details/gtdwqtvtvc.html

[R60] 只看 HTTP 状态码
来源：http://dali.hammf.cn/Article/details/gtcmmssevx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xuanzx.com/Article/details/gtnbdbvxfc.html

[R61] 磁盘占用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticuwqmuy.html

df -h;  du -sh *
来源：http://dali.xylfe.cn/Article/details/gtxxbxfwse.html

[R62] 找最占空间的文件
来源：http://dali.ydzc1.top/Article/details/gtyvagaghw.html

du -ah . | sort -rh | head -10
来源：http://dali.yueranfly.top/Article/details/gtlirlkmpi.html

[R63] 内存与进程
来源：http://dali.yonumen.top/Article/details/gthkdgzhag.html

free -h;  ps aux | grep nginx
来源：http://dali.chenjidiqi.icu/Article/details/gtmzlpuwex.html

[R64] 结束进程
来源：http://dali.316326.xyz/Article/details/gtnyowpofa.html

kill -9 $(pgrep -f app.py)
来源：http://dali.havefunace.top/Article/details/gtdkdfbdkd.html

[R65] 查看端口占用
来源：http://dali.9152youxi.cn/Article/details/gtxpjcduhf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yvedp.cn/Article/details/gtrlegkdtl.html

[R66] 定时任务
来源：http://dali.tian-w.cn/Article/details/gtwcecysck.html

crontab -e;  crontab -l
来源：http://dali.gogol.net.cn/Article/details/gtlcqcitjh.html

[R67] 生成随机十六进制串
来源：http://dali.hysaishi.cn/Article/details/gtxkerxhyg.html

openssl rand -hex 16
来源：http://dali.jianghu66.top/Article/details/gtjgwgettw.html

[R68] 计算文件校验值
来源：http://dali.xuetiantiany.cn/Article/details/gtigklsyyd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.fzhhl.top/Article/details/gtwpzmbrgq.html

[R69] 生成随机密码
来源：http://dali.jinqigufen.top/Article/details/gtfqwfyilv.html


<!-- 参考信息 -->