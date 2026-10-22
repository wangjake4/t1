代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xuanzx.com/Article/details/gtmvrxldku.html

[Q18] 模糊匹配
来源：http://dali.xziqi.cn/Article/details/gtmgzfrvtf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shanyushiyangtech.top/Article/details/gturxwyfvb.html

[Q19] 范围查询
来源：http://dali.haohaochexian.top/Article/details/gtjlbgqdhz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yueranfly.top/Article/details/gtlvubdhwy.html

[Q20] IN 列表
来源：http://dali.tanke756.top/Article/details/gtijuqkqbn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrpqtbxs.html

[Q21] 空值判断
来源：http://dali.birdmap.top/Article/details/gtdmvysieo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tianlin.xyz/Article/details/gtqunipzxv.html

[Q22] 排序
来源：http://dali.gotoacloud.top/Article/details/gtyopstkia.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.vqdsnc.cn/Article/details/gtjdjywbig.html

[Q23] 分页
来源：http://dali.yj20258.top/Article/details/gtcmegfidi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hammf.cn/Article/details/gtqsninokl.html

[Q24] 去重
来源：http://dali.cheryme.top/Article/details/gtdzpfgody.html

SELECT DISTINCT city FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtftkjzbcw.html

[Q25] 只取前 N 条
来源：http://dali.jinqigfzy.top/Article/details/gtmltllgkc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuxming.cn/Article/details/gthvvdvhsy.html

[Q26] 计数
来源：http://dali.hongshengwenyu.top/Article/details/gtiegzhlxe.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcqpnrxk.html

[Q27] 条件计数
来源：http://dali.aibaodan.cn/Article/details/gtxedzjtjn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtkqutgevz.html

[Q28] 求和与平均
来源：http://dali.hnqzz.top/Article/details/gtzixgacup.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqqtbcwj.html

[Q29] 最大最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbtsuvix.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtrvjpqvuk.html

[Q30] 分组统计
来源：http://dali.nwbrower.top/Article/details/gtvbjfkumg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gtztuwbpde.html

[Q31] 分组后过滤
来源：http://dali.xziqi.cn/Article/details/gtbncakekd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.daria6918.cn/Article/details/gtmlnbnply.html

[Q32] 分组拼接字符串
来源：http://dali.xuanzx.com/Article/details/gtignlhysj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gtzodgwzqu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinqigfzy.top/Article/details/gthujqhoik.html

[Q33] 多列分组
来源：http://dali.ehwqpu.com/Article/details/gtkmagxpom.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.316326.xyz/Article/details/gtgyngdlkc.html

[Q34] 每组取第一条
来源：http://dali.jqgfzy.top/Article/details/gtbtwjnbmx.html

SELECT * FROM (
来源：http://dali.jinghuilouyu.cn/Article/details/gtleedpgzy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xinyue.icu/Article/details/gtnfeotpuu.html

) t WHERE rn = 1;
来源：http://dali.chenlongwang.top/Article/details/gtipfxrnwl.html

[Q35] 内连接
来源：http://dali.quarkkingdee.top/Article/details/gthumywsbx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.smart0.xyz/Article/details/gtxvidnwml.html

[Q36] 左连接
来源：http://dali.daxiang520.top/Article/details/gtodpshudn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.c1oappe.top/Article/details/gtzdjryrgz.html

[Q37] 右连接
来源：http://dali.yueranfly.top/Article/details/gtgkpcxgzj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jlsjyb.cn/Article/details/gtrnwjsuok.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuetiantiany.cn/Article/details/gtovvcbubs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.redwolf501.top/Article/details/gtqrvoveht.html

[Q39] 自连接（查上下级）
来源：http://dali.0kj1m.cn/Article/details/gtjufrdbjx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ybcxt.top/Article/details/gtgchdceyz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yongpay.top/Article/details/gtbyvbozct.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.snrcjt.cn/Article/details/gthrhjdany.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hfpthk.cn/Article/details/gttzlxqwre.html

[Q41] 多表连接
来源：http://dali.quarkkingdee.top/Article/details/gtsmtyejcd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cheryme.top/Article/details/gtpvsafmnh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.dashuyun.cn/Article/details/gtppsnfxhz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nwbrower.top/Article/details/gtsevnzefl.html

[Q42] 连接条件附加过滤
来源：http://dali.yongpay.top/Article/details/gtbdbkalhs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cqqwz.cn/Article/details/gtzkhznjoj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gtdohpmoff.html

[Q43] 标量子查询
来源：http://dali.jianghu66.top/Article/details/gtwqfqayxf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cheryme.top/Article/details/gtqhuttrzz.html

[Q44] IN 子查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwrvvpmt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvjmsyab.html

[Q45] EXISTS 判断存在
来源：http://dali.aizwys.cn/Article/details/gtknppjtbz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gtsrdwhejx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xinyue.icu/Article/details/gtztwxcbhj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnxiangtu.top/Article/details/gtyviltkgn.html

[Q47] 与平均值比较
来源：http://dali.sufxvd.cn/Article/details/gtnzlxhtiv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.smart0.xyz/Article/details/gtnluyldws.html

[Q48] CTE 公用表表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtqnprihgp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.guannengcc.top/Article/details/gtejfehzjb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxinkj.top/Article/details/gtwthgnadr.html

[Q49] 更新单行
来源：http://dali.havefunace.top/Article/details/gtifpqhebv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gtgkqxddkk.html

[Q50] 批量更新
来源：http://dali.haohaochexian.top/Article/details/gtqqhlzxbz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zdqjudy.top/Article/details/gtmdyejsae.html

[Q51] 用子查询更新
来源：http://dali.hammf.cn/Article/details/gtztisowbn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtjkzgfmmh.html

[Q52] 删除指定行
来源：http://dali.nwbrower.top/Article/details/gtspdwtytx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258888.top/Article/details/gtgafazuku.html

[Q53] 按条件删除
来源：http://dali.daria6918.cn/Article/details/gtbewenikk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.svipenyu.cn/Article/details/gtwekwbpil.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gtjnvhaatn.html

TRUNCATE TABLE logs;
来源：http://dali.yanxiufei.cn/Article/details/gtmpizqnop.html

[Q55] 排名（并列占位）
来源：http://dali.gzhubu.top/Article/details/gtnuyexrlk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj20258.top/Article/details/gtqwyezsoa.html

[Q56] 密集排名（并列不占位）
来源：http://dali.fengsongda.top/Article/details/gtkdwcemvp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.daria6918.cn/Article/details/gtsrqstgwa.html

[Q57] 行号
来源：http://dali.yanxiufei.cn/Article/details/gtfqgfjqvs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fengsongda.top/Article/details/gtcismsnyz.html

[Q58] 累计求和
来源：http://dali.wangshuangyany.cn/Article/details/gtaklaiyiv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtgcqsyeww.html

[Q59] 分组内累计
来源：http://dali.andypj.xyz/Article/details/gtztagkrki.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtmtndkois.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhiwuduotai.top/Article/details/gtexjbpemo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jqgufenzy.top/Article/details/gtfuwrvvyn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtwpoyhmys.html

[Q61] 移动平均
来源：http://dali.quarkkingdee.top/Article/details/gtkgirugch.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtysroxsin.html

[Q62] 分组占比
来源：http://dali.sweek.top/Article/details/gtfssgbpmq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gtqsoxhbfd.html

[Q63] 开启事务
来源：http://dali.pengpengdd.cyou/Article/details/gthpkzbcuk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sysykeji.top/Article/details/gtkuvhvlfs.html

[Q64] 提交事务
来源：http://dali.yvedp.cn/Article/details/gtnpsumkqx.html

COMMIT;
来源：http://dali.aibaodan.cn/Article/details/gtpwplgcbu.html

[Q65] 回滚事务
来源：http://dali.pycfn.com/Article/details/gtbkjeyljp.html

ROLLBACK;
来源：http://dali.wangdashe.top/Article/details/gtunroptwk.html

[Q66] 行锁查询
来源：http://dali.sweek.top/Article/details/gthetfgszb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinghuilouyu.cn/Article/details/gthopblatj.html

[Q67] 设置隔离级别
来源：http://dali.tanke756.top/Article/details/gtkaxicrrg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.316326.xyz/Article/details/gtmsxklgqk.html

[Q68] 保存点
来源：http://dali.yongpay.top/Article/details/gtlxdqndyf.html

SAVEPOINT sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnadjkald.html

ROLLBACK TO sp1;
来源：http://dali.daria6918.cn/Article/details/gtnstgzeye.html

[Q69] 查看执行计划
来源：http://dali.yj20258888.top/Article/details/gtbvwmxlvw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sxryk.cn/Article/details/gtdbpdtomr.html

[Q70] 更新统计信息
来源：http://dali.gogol.net.cn/Article/details/gtgbmntnmi.html

ANALYZE TABLE users;
来源：http://dali.zhengqikj.top/Article/details/gthbkshxyx.html

[Q71] 查看建表语句
来源：http://dali.redwolf501.top/Article/details/gtrpjmoiia.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.havefunace.top/Article/details/gtxrxvhkhy.html

[Q72] 查看索引
来源：http://dali.havefunace.top/Article/details/gtkvxckxfw.html

SHOW INDEX FROM users;
来源：http://dali.yonumen.top/Article/details/gtlxwohsvm.html

[Q73] 查看表状态
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqvttfbs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhengqikj.top/Article/details/gtbbdnflxx.html

[Q74] 强制使用索引
来源：http://dali.daria6918.cn/Article/details/gthszhhbtq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.fzhhl.top/Article/details/gtvlrizdcy.html

[Q75] 日期格式化
来源：http://dali.yuanzhike.top/Article/details/gtfeundpdz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtfvdrvzum.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jlsjyb.cn/Article/details/gtvwgalohl.html

[Q76] 按天统计
来源：http://dali.yongpay.top/Article/details/gtvhqzdlnw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.quarkkingdee.top/Article/details/gtyfidklvd.html

[Q77] 时间加减
来源：http://dali.birdmap.top/Article/details/gtlusgfpsm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.birdmap.top/Article/details/gtkmgcitsh.html

[Q78] 当前时间
来源：http://dali.cqqwz.cn/Article/details/gtxygapjtx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigfzy.top/Article/details/gtqyfruryz.html

[Q79] 字符串拼接
来源：http://dali.iojbl.cn/Article/details/gtlzeiplod.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.fzhhl.top/Article/details/gtoounxlcp.html

[Q80] 字符串截取
来源：http://dali.yuanzhike.top/Article/details/gtfptlghyg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtffqyiyhf.html

[Q81] 字符串替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtxelopzxn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtpioxgbdg.html

[Q82] 字符长度与字节长度
来源：http://dali.jyoumei.cn/Article/details/gtxyhkbrwa.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtqxrvrmrq.html

[Q83] 大小写转换
来源：http://dali.nanxuanxn.top/Article/details/gtyuqyykuc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtdvrnypxv.html

[Q84] 去除首尾空格
来源：http://dali.tanke756.top/Article/details/gtfsglzqrg.html

SELECT TRIM(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtdtejrkwx.html

[Q85] 数值取整
来源：http://dali.zhongyouzk.top/Article/details/gttrnmclja.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sysykeji.top/Article/details/gtvoimuqeb.html

[Q86] 读取 JSON 字段
来源：http://dali.nanxuanxn.top/Article/details/gtbbclieta.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hongshengwenyu.top/Article/details/gtmtovxddz.html

[Q87] JSON 字段做条件
来源：http://dali.jlsjyb.cn/Article/details/gtpfdzafkq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gaohongyu789.top/Article/details/gttojsvcyv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gtyqkdsjnm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.vqdsnc.cn/Article/details/gtnrbsaelw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtzetdmxci.html

[Q89] 判断表是否存在
来源：http://dali.gzhubu.top/Article/details/gtgbaspthb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cdnleiting.top/Article/details/gttqgjbtkj.html

[Q90] 生成序号列
来源：http://dali.jyoumei.cn/Article/details/gtddshdzhl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.meibo888.top/Article/details/gtnazoevlo.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtpphyynba.html

R. Bash 专题
来源：http://dali.dianchejie.cn/Article/details/gtzjqutlrj.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtunfrujju.html

[R01] shebang 与严格模式
来源：http://dali.0kj1m.cn/Article/details/gtffeyqkfr.html

#!/usr/bin/env bash
来源：http://dali.yj20258888.top/Article/details/gthqwymivy.html

set -euo pipefail
来源：http://dali.aibaodan.cn/Article/details/gtxkjdgimb.html

[R02] 变量赋值与使用
来源：http://dali.jyoumei.cn/Article/details/gtlplnmlnw.html

name="Tom"; echo "$name"
来源：http://dali.cqqwz.cn/Article/details/gtpzzygyob.html

[R03] 只读变量
来源：http://dali.gotoacloud.top/Article/details/gtczmevqxr.html

readonly PI=3.14
来源：http://dali.sufxvd.cn/Article/details/gtvimmsmmw.html

[R04] 位置参数
来源：http://dali.cdnleiting.top/Article/details/gtkgigntke.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhixingplan.top/Article/details/gtufjrtnpf.html

[R05] 参数默认值
来源：http://dali.haohaochexian.top/Article/details/gtnvefkhrb.html

name="${1:-default}"
来源：http://dali.jyoumei.cn/Article/details/gtguptoayz.html

[R06] 判断命令是否存在
来源：http://dali.aibaodan.cn/Article/details/gtiphttdao.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgfzy.top/Article/details/gtwoaevgli.html

[R07] if 判断文件
来源：http://dali.9152youxi.cn/Article/details/gtyrocjkjb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jiagoushi.top/Article/details/gtqzqjvtzy.html

[R08] 数值比较
来源：http://dali.xziqi.cn/Article/details/gtdwsdngmb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.andypj.xyz/Article/details/gttlpovbry.html

[R09] 字符串比较
来源：http://dali.iojbl.cn/Article/details/gtxsyvagfa.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuxming.cn/Article/details/gtezmdgnrk.html

[R10] 正则匹配
来源：http://dali.c1oappe.top/Article/details/gttyymowcj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sysykeji.top/Article/details/gtnzdhetnn.html

[R11] case 多分支
来源：http://dali.shuidangran.top/Article/details/gtujvnqtfp.html

case "$1" in
来源：http://dali.birdmap.top/Article/details/gtwovgfgap.html

start) echo "启动" ;;
来源：http://dali.yonumen.top/Article/details/gtzgqwofjt.html

stop)  echo "停止" ;;
来源：http://dali.yj20258888.top/Article/details/gtpfrexoad.html

*)     echo "未知命令" ;;
来源：http://dali.jianghu66.top/Article/details/gtcpiwbwhw.html

esac
来源：http://dali.vqdsnc.cn/Article/details/gtreqlsfmm.html

[R12] for 遍历文件
来源：http://dali.sufxvd.cn/Article/details/gtnacskqvn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenzaomai.com/Article/details/gtrbhstlwu.html

[R13] for 计数循环
来源：http://dali.quarkkingdee.top/Article/details/gtxdxognxy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yuanzhike.top/Article/details/gtctftbtdo.html

[R14] C 风格 for
来源：http://dali.shuidangran.top/Article/details/gthshdhjxl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gtzamzpnfn.html

[R15] while 逐行读文件
来源：http://dali.ivvv.top/Article/details/gtlodbqdrg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfuvzyne.html

[R16] until 等待条件
来源：http://dali.sweek.top/Article/details/gtecformds.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cucudq.cn/Article/details/gtncxxmofn.html

[R17] 数组定义与取值
来源：http://dali.zhiwuduotai.top/Article/details/gtaojdthfd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.feifeiyinyue.top/Article/details/gteupfpriv.html

[R18] 遍历数组
来源：http://dali.tian-w.cn/Article/details/gtzbwbamvw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shuidangran.top/Article/details/gtmdwxjddf.html

[R19] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gtfwnqxbfh.html

echo "${#arr[@]}"
来源：http://dali.havefunace.top/Article/details/gtprmajgbc.html

[R20] 关联数组（字典）
来源：http://dali.ivvv.top/Article/details/gtexowfswo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tanke756.top/Article/details/gtatxwarqi.html

[R21] 字符串长度
来源：http://dali.daxiang520.top/Article/details/gtvuxayxun.html

echo "${#s}"
来源：http://dali.xziqi.cn/Article/details/gtibkbesli.html

[R22] 截取子串
来源：http://dali.pycfn.com/Article/details/gtdwwngyus.html

echo "${s:0:5}"
来源：http://dali.shuidangran.top/Article/details/gtcnpzzxvw.html

[R23] 字符串替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtutscblyf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dianchejie.cn/Article/details/gtceqhdplu.html

[R24] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gtkkgsikjq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhengqikj.top/Article/details/gtewuqjolz.html

[R25] 去后缀 / 去前缀
来源：http://dali.xylfe.cn/Article/details/gtntxxkqjf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sysykeji.top/Article/details/gtamitylfc.html

[R26] 命令替换
来源：http://dali.zdqjudy.top/Article/details/gtkldcqxzd.html

now=$(date +%F); echo "$now"
来源：http://dali.chenjidiqi.icu/Article/details/gtwaqeaigo.html

[R27] 算术展开
来源：http://dali.nwbrower.top/Article/details/gtfnkvecqt.html

echo $((1 + 2 * 3))
来源：http://dali.redwolf501.top/Article/details/gtdqjldojk.html

[R28] 浮点运算
来源：http://dali.guowangkeji.top/Article/details/gtohpzwyca.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gtwsbtbmhe.html

[R29] 定义函数
来源：http://dali.ppjwa.cn/Article/details/gtoydomfvv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dashuyun.cn/Article/details/gtwdpobvvd.html

[R30] 函数返回状态码
来源：http://dali.cheryme.top/Article/details/gtrhhjdmfs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinghuilouyu.cn/Article/details/gtegbexodm.html

[R31] 局部变量
来源：http://dali.yj20258.top/Article/details/gtzeszuyaq.html

f() { local x=1; echo "$x"; }
来源：http://dali.sweek.top/Article/details/gtixcqkmpn.html

[R32] 参数个数校验
来源：http://dali.yvedp.cn/Article/details/gtnsrfvwxs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gtmebuigkl.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gtbcwgrvkg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.aibaodan.cn/Article/details/gtyxmsmcau.html

[R34] 退出时清理
来源：http://dali.birdmap.top/Article/details/gtclzooszy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangshuangyany.cn/Article/details/gtzhzdzdde.html

[R35] 后台执行并等待
来源：http://dali.cdnleiting.top/Article/details/gtulsrjppn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangdashe.top/Article/details/gtmynacipi.html

[R36] 并发执行多个任务
来源：http://dali.sweek.top/Article/details/gtpmcjvnhz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.meibo888.top/Article/details/gtamwugfnt.html

[R37] 把输出赋给变量
来源：http://dali.pengpengdd.cyou/Article/details/gtayngvjko.html

files=$(ls -1)
来源：http://dali.hywenlv.cn/Article/details/gteozvrqnc.html

[R38] 管道串联
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtabyqwq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cashguo.top/Article/details/gtyiszmaxv.html

[R39] 重定向标准输出与错误
来源：http://dali.zdqjudy.top/Article/details/gtzhvvhmzo.html

cmd > out.log 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gtazjszpge.html

[R40] 追加写日志
来源：http://dali.0kj1m.cn/Article/details/gtixsebsma.html

echo "log" >> out.log
来源：http://dali.sysykeji.top/Article/details/gtmtuuwwif.html

[R41] 丢弃输出
来源：http://dali.dashuyun.cn/Article/details/gtchkphkgr.html

cmd >/dev/null 2>&1
来源：http://dali.9152youxi.cn/Article/details/gtdsphzzwf.html

[R42] 输入重定向
来源：http://dali.shzxlz.cn/Article/details/gtczgbbfzb.html

wc -l < a.txt
来源：http://dali.jqgfzy.top/Article/details/gtpjcbcdry.html

[R43] 按名字查找文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmnbexgu.html

find . -name "*.log" -type f
来源：http://dali.cashguo.top/Article/details/gtnnprhevo.html

[R44] 按修改时间查找
来源：http://dali.wangdashe.top/Article/details/gtnxvqqwnv.html

find . -mtime -7 -type f
来源：http://dali.jlsjyb.cn/Article/details/gtvxhnmcsx.html

[R45] 批量删除
来源：http://dali.tianlin.xyz/Article/details/gtmmpjpchw.html

find . -name "*.tmp" -delete
来源：http://dali.zdqjudy.top/Article/details/gtujfodolv.html

[R46] 递归替换文件内容
来源：http://dali.daxiang520.top/Article/details/gtwsqxrtrc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258888.top/Article/details/gtlpuiftwx.html

[R47] sed 单行替换
来源：http://dali.xuanzx.com/Article/details/gtxmxmamhy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtbiuervqn.html

[R48] awk 取指定列
来源：http://dali.ppjwa.cn/Article/details/gteeieiidu.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj202588.top/Article/details/gtfzvkuppq.html

[R49] awk 带条件
来源：http://dali.guannengcc.top/Article/details/gtxirohkjn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gogol.net.cn/Article/details/gtmsldzfbi.html

[R50] awk 求和
来源：http://dali.zhixingplan.top/Article/details/gtohqjpsss.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sysykeji.top/Article/details/gtvpjfxlwb.html

[R51] 排序去重取前几
来源：http://dali.cheryme.top/Article/details/gtdoeqwrqc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yonumen.top/Article/details/gtkxabxtmt.html

[R52] 统计行数
来源：http://dali.jinghuilouyu.cn/Article/details/gteajnugpn.html

wc -l a.txt
来源：http://dali.cqqwz.cn/Article/details/gthqwgefly.html

[R53] 查看文件头与实时尾
来源：http://dali.ppjwa.cn/Article/details/gtkzlorjik.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sxryk.cn/Article/details/gtcdmwsorn.html

[R54] 比较两个文件
来源：http://dali.nanxuanxn.top/Article/details/gtbemueojs.html

diff a.txt b.txt
来源：http://dali.jyoumei.cn/Article/details/gtgehnigbq.html

[R55] 压缩与解压
来源：http://dali.yuxming.cn/Article/details/gthmujeric.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigufen.top/Article/details/gtznakqmzj.html

[R56] 远程拷贝
来源：http://dali.0kj1m.cn/Article/details/gtuzjkcqcv.html

scp file user@host:/path/
来源：http://dali.cqqwz.cn/Article/details/gtdoimsecj.html

[R57] 远程执行命令
来源：http://dali.sxryk.cn/Article/details/gtcnoskygq.html

ssh user@host 'uptime'
来源：http://dali.tian-w.cn/Article/details/gtcdjdyrnb.html

[R58] 下载文件
来源：http://dali.iojbl.cn/Article/details/gtcpiybcaj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.daxiang520.top/Article/details/gtmocobjod.html

[R59] 发 POST JSON
来源：http://dali.xuetiantiany.cn/Article/details/gttddogokl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.0kj1m.cn/Article/details/gtwgnrajxw.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtsspwxelj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.svipenyu.cn/Article/details/gtzhdztqjc.html

[R61] 磁盘占用
来源：http://dali.hammf.cn/Article/details/gtzuzprfsh.html

df -h;  du -sh *
来源：http://dali.aibaodan.cn/Article/details/gtsioruwhu.html

[R62] 找最占空间的文件
来源：http://dali.yuxming.cn/Article/details/gtmwshtfju.html

du -ah . | sort -rh | head -10
来源：http://dali.shangyingyoupin.top/Article/details/gttvvqodhd.html

[R63] 内存与进程
来源：http://dali.jianghu66.top/Article/details/gtgsivixoy.html

free -h;  ps aux | grep nginx
来源：http://dali.yonumen.top/Article/details/gtqqhcmdmd.html

[R64] 结束进程
来源：http://dali.daria6918.cn/Article/details/gtqjjaxrtq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ybcxt.top/Article/details/gthctcqyid.html

[R65] 查看端口占用
来源：http://dali.shangyingyoupin.top/Article/details/gtcfdqityl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sufxvd.cn/Article/details/gtlkhkgufv.html

[R66] 定时任务
来源：http://dali.iojbl.cn/Article/details/gtuplvsqiw.html

crontab -e;  crontab -l
来源：http://dali.pengpengdd.cyou/Article/details/gtrwgpsijd.html

[R67] 生成随机十六进制串
来源：http://dali.iojbl.cn/Article/details/gtodgsjiwg.html


<!-- 参考信息 -->