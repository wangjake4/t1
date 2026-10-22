代发 wailian999

[Q14] 存在则更新（upsert）
来源：http://dali.svipenyu.cn/Article/details/gt2byhiawee.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zycfv.cn/Article/details/gt2tjqoxihn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.kuanghao11.cn/Article/details/gt2ivjzjdxh.html

[Q15] 查询全部
来源：http://dali.0kj1m.cn/Article/details/gt2qwsoestj.html

SELECT * FROM users;
来源：http://dali.yongpay.top/Article/details/gt2ojicnsrp.html

[Q16] 查询指定列
来源：http://dali.jqgfzy.top/Article/details/gt2vuhkppax.html

SELECT id, name FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2ptbbesdi.html

[Q17] 条件查询
来源：http://dali.yj20258.top/Article/details/gt2pkrdtven.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2qbffsdkv.html

[Q18] 模糊匹配
来源：http://dali.daxiang520.top/Article/details/gt2lxljaotv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.bjfxy.top/Article/details/gt2syxrgacs.html

[Q19] 范围查询
来源：http://dali.fzhhl.top/Article/details/gt2bqfekfbp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhixingplan.top/Article/details/gt2ugnayqtl.html

[Q20] IN 列表
来源：http://dali.xuetiantiany.cn/Article/details/gt2sxovmked.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sxryk.cn/Article/details/gt2gisvcmdg.html

[Q21] 空值判断
来源：http://dali.dashuyun.cn/Article/details/gt2wyanbglk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnqzz.top/Article/details/gt2anymahds.html

[Q22] 排序
来源：http://dali.jqgufenzy.top/Article/details/gt2nydjtoqy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zdqjudy.top/Article/details/gt2szwbbeja.html

[Q23] 分页
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2drjgqbut.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hywenlv.cn/Article/details/gt2hpkzrsje.html

[Q24] 去重
来源：http://dali.guowangkeji.top/Article/details/gt2ppkcxcrd.html

SELECT DISTINCT city FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2cjpxxtur.html

[Q25] 只取前 N 条
来源：http://dali.hysaishi.cn/Article/details/gt2wspljwlm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.guannengcc.top/Article/details/gt2pseeuegs.html

[Q26] 计数
来源：http://dali.ybcxt.top/Article/details/gt2pstukrml.html

SELECT COUNT(*) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2llcacagc.html

[Q27] 条件计数
来源：http://dali.316326.xyz/Article/details/gt2hulsslae.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2biljyvdz.html

[Q28] 求和与平均
来源：http://dali.jqgufenzy.top/Article/details/gt2lvuloadi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2zvbkpdct.html

[Q29] 最大最小值
来源：http://dali.yuanzhike.top/Article/details/gt2ktwrtocp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2pqpaoqvv.html

[Q30] 分组统计
来源：http://dali.zhixingplan.top/Article/details/gt2bhpqwfsu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gt2hmubrtes.html

[Q31] 分组后过滤
来源：http://dali.0kj1m.cn/Article/details/gt2xszgazlc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuanzx.com/Article/details/gt2likcftqm.html

[Q32] 分组拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2fxbtjbyr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gt2sqhfzorq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.0kj1m.cn/Article/details/gt2uiecftud.html

[Q33] 多列分组
来源：http://dali.snrcjt.cn/Article/details/gt2jmlpfuns.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.iojbl.cn/Article/details/gt2rhufxdmd.html

[Q34] 每组取第一条
来源：http://dali.xziqi.cn/Article/details/gt2wfcimocz.html

SELECT * FROM (
来源：http://dali.tanke756.top/Article/details/gt2johzewte.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hfpthk.cn/Article/details/gt2aieuqkjs.html

) t WHERE rn = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2wjyqgpak.html

[Q35] 内连接
来源：http://dali.shzxlz.cn/Article/details/gt2edohjaue.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gt2ewzemfci.html

[Q36] 左连接
来源：http://dali.redwolf501.top/Article/details/gt2ngfwjklx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnqzz.top/Article/details/gt2zyvowsxc.html

[Q37] 右连接
来源：http://dali.mhx1999.top/Article/details/gt2uxtejmxo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jqgfzy.top/Article/details/gt2jentpmnu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tianlin.xyz/Article/details/gt2gkxwpcho.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.guowangkeji.top/Article/details/gt2zimvhamk.html

[Q39] 自连接（查上下级）
来源：http://dali.cucudq.cn/Article/details/gt2leoekwcl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cashguo.top/Article/details/gt2tkiuotyp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jyoumei.cn/Article/details/gt2rkhtxslr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nanxinkj.top/Article/details/gt2rlgdmdtu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.fengsongda.top/Article/details/gt2pmwumojs.html

[Q41] 多表连接
来源：http://dali.guannengcc.top/Article/details/gt2ipvrxmzj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ivvv.top/Article/details/gt2vantozis.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ltrshibk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.birdmap.top/Article/details/gt2pjmsxpdw.html

[Q42] 连接条件附加过滤
来源：http://dali.hywenlv.cn/Article/details/gt2itmncmzv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jiagoushi.top/Article/details/gt2qboelvmq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.kuanghao11.cn/Article/details/gt2kkrggjmc.html

[Q43] 标量子查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jpteahyt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ppjwa.cn/Article/details/gt2kypsyknw.html

[Q44] IN 子查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tujuxgrr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nwbrower.top/Article/details/gt2vaccildk.html

[Q45] EXISTS 判断存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bbrsbses.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.birdmap.top/Article/details/gt2alzbwrak.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xylfe.cn/Article/details/gt2cxvluzkj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gt2xjxwpmxz.html

[Q47] 与平均值比较
来源：http://dali.guowangkeji.top/Article/details/gt2jqyivujv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgfzy.top/Article/details/gt2urpftduu.html

[Q48] CTE 公用表表达式
来源：http://dali.hnxiangtu.top/Article/details/gt2pjqirdhm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tian-w.cn/Article/details/gt2xdazyvrs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ppjwa.cn/Article/details/gt2bhsxydne.html

[Q49] 更新单行
来源：http://dali.birdmap.top/Article/details/gt2wzitflcp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aizwys.cn/Article/details/gt2mhingssz.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhtahxs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigufen.top/Article/details/gt2brtqwywx.html

[Q51] 用子查询更新
来源：http://dali.iojbl.cn/Article/details/gt2bazcwsia.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2vywyxyzo.html

[Q52] 删除指定行
来源：http://dali.hfpthk.cn/Article/details/gt2ptdkljjy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gt2blbdkhpn.html

[Q53] 按条件删除
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sfaojjit.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sbqashuk.html

[Q54] 清空表
来源：http://dali.chenjidiqi.icu/Article/details/gt2eqjkqfyg.html

TRUNCATE TABLE logs;
来源：http://dali.zhoulong.xyz/Article/details/gt2ejdihqvr.html

[Q55] 排名（并列占位）
来源：http://dali.guannengcc.top/Article/details/gt2dqntbfeu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gt2pnjtzkyv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ydzc1.top/Article/details/gt2fqlblmcm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhengqikj.top/Article/details/gt2bmxnafas.html

[Q57] 行号
来源：http://dali.sysykeji.top/Article/details/gt2saaiopwg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2bdqyihej.html

[Q58] 累计求和
来源：http://dali.gaohongyu789.top/Article/details/gt2alcilugy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gt2mcevpajj.html

[Q59] 分组内累计
来源：http://dali.fzhhl.top/Article/details/gt2mtitreby.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2izortbic.html

[Q60] 取上一行 / 下一行
来源：http://dali.ybcxt.top/Article/details/gt2lrhpbvwt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xylfe.cn/Article/details/gt2grbxesaw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2fqlwnaly.html

[Q61] 移动平均
来源：http://dali.dianchejie.cn/Article/details/gt2itqlfaue.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2uhaqfrlz.html

[Q62] 分组占比
来源：http://dali.wangdashe.top/Article/details/gt2olsghhjm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gt2zbonckbw.html

[Q63] 开启事务
来源：http://dali.yanxiufei.cn/Article/details/gt2kezdbnvx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuanzx.com/Article/details/gt2njgbnbdy.html

[Q64] 提交事务
来源：http://dali.yj20258.top/Article/details/gt2obwomgyz.html

COMMIT;
来源：http://dali.iojbl.cn/Article/details/gt2syxruanf.html

[Q65] 回滚事务
来源：http://dali.hfpthk.cn/Article/details/gt2huybprqg.html

ROLLBACK;
来源：http://dali.ivvv.top/Article/details/gt2ubpykiys.html

[Q66] 行锁查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uikghjbv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenjidiqi.icu/Article/details/gt2sovducvi.html

[Q67] 设置隔离级别
来源：http://dali.shuidangran.top/Article/details/gt2kihoysph.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.mhx1999.top/Article/details/gt2xikthzjn.html

[Q68] 保存点
来源：http://dali.iojbl.cn/Article/details/gt2alfjjkhp.html

SAVEPOINT sp1;
来源：http://dali.shuidangran.top/Article/details/gt2zlozjhqy.html

ROLLBACK TO sp1;
来源：http://dali.yangfankeji.com/Article/details/gt2bptqqtmw.html

[Q69] 查看执行计划
来源：http://dali.zhongyouzk.top/Article/details/gt2oknegbnf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daxiang520.top/Article/details/gt2aulqqpkm.html

[Q70] 更新统计信息
来源：http://dali.bjfxy.top/Article/details/gt2auhmjeus.html

ANALYZE TABLE users;
来源：http://dali.dianchejie.cn/Article/details/gt2hxrljvcg.html

[Q71] 查看建表语句
来源：http://dali.hysaishi.cn/Article/details/gt2rwzvurkp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ivvv.top/Article/details/gt2vwipfwcp.html

[Q72] 查看索引
来源：http://dali.cheryme.top/Article/details/gt2lnxnuhsh.html

SHOW INDEX FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pjikjbwv.html

[Q73] 查看表状态
来源：http://dali.ivvv.top/Article/details/gt2regnkhov.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nanxinkj.top/Article/details/gt2wltlqwsa.html

[Q74] 强制使用索引
来源：http://dali.kuanghao11.cn/Article/details/gt2uxbpmtps.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sxryk.cn/Article/details/gt2bbnezanx.html

[Q75] 日期格式化
来源：http://dali.daria6918.cn/Article/details/gt2gdbxlsak.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2ootcrrxi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhiwuduotai.top/Article/details/gt2sssxgpds.html

[Q76] 按天统计
来源：http://dali.ydzc1.top/Article/details/gt2nppsigqf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhixingplan.top/Article/details/gt2ynrzemhl.html

[Q77] 时间加减
来源：http://dali.chenlongwang.top/Article/details/gt2uotawxos.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.mhx1999.top/Article/details/gt2vqnjpoyj.html

[Q78] 当前时间
来源：http://dali.birdmap.top/Article/details/gt2uktfmddn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yangfankeji.com/Article/details/gt2nomcfpqk.html

[Q79] 字符串拼接
来源：http://dali.hysaishi.cn/Article/details/gt2yuuqadye.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.wangdashe.top/Article/details/gt2guadqall.html

[Q80] 字符串截取
来源：http://dali.aibaodan.cn/Article/details/gt2lqmvezla.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yonumen.top/Article/details/gt2orzqhjff.html

[Q81] 字符串替换
来源：http://dali.vqdsnc.cn/Article/details/gt2nunbpipj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2yctrjqfd.html

[Q82] 字符长度与字节长度
来源：http://dali.tanke756.top/Article/details/gt2kummzlee.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2qrfczact.html

[Q83] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gt2cchdasqo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2trdbaxsk.html

[Q84] 去除首尾空格
来源：http://dali.jlsjyb.cn/Article/details/gt2owgfryjh.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gt2pdifrtkc.html

[Q85] 数值取整
来源：http://dali.gotoacloud.top/Article/details/gt2rmlvufnz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hfpthk.cn/Article/details/gt2hlvnwbkm.html

[Q86] 读取 JSON 字段
来源：http://dali.sxryk.cn/Article/details/gt2egfvxuck.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dashuyun.cn/Article/details/gt2gxfwqemp.html

[Q87] JSON 字段做条件
来源：http://dali.yangfankeji.com/Article/details/gt2ayvhczkc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.iojbl.cn/Article/details/gt2yzlkcldn.html

[Q88] 行转列（条件聚合）
来源：http://dali.gzhubu.top/Article/details/gt2tgwoezoi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2himvtdqt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mddckuoo.html

[Q89] 判断表是否存在
来源：http://dali.kuanghao11.cn/Article/details/gt2netuokmd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ivvv.top/Article/details/gt2nmowqfxa.html

[Q90] 生成序号列
来源：http://dali.yj202588.top/Article/details/gt2cahaqpvl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dianchejie.cn/Article/details/gt2ymvcpszt.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2srdvucxe.html

R. Bash 专题
来源：http://dali.c1oappe.top/Article/details/gt2uoyszyzi.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2fgxofkkk.html

[R01] shebang 与严格模式
来源：http://dali.yanxiufei.cn/Article/details/gt2tztyplpj.html

#!/usr/bin/env bash
来源：http://dali.yj20258888.top/Article/details/gt2yqpxqrcm.html

set -euo pipefail
来源：http://dali.hnxiangtu.top/Article/details/gt2ourrzqva.html

[R02] 变量赋值与使用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uacqxnir.html

name="Tom"; echo "$name"
来源：http://dali.gotoacloud.top/Article/details/gt2yopfutfe.html

[R03] 只读变量
来源：http://dali.haohaochexian.top/Article/details/gt2ympdjhzx.html

readonly PI=3.14
来源：http://dali.tanke756.top/Article/details/gt2uwitxzud.html

[R04] 位置参数
来源：http://dali.cheryme.top/Article/details/gt2pqkxcjnj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jiagoushi.top/Article/details/gt2mfreylcg.html

[R05] 参数默认值
来源：http://dali.yvedp.cn/Article/details/gt2jdysktbl.html

name="${1:-default}"
来源：http://dali.smart0.xyz/Article/details/gt2qqpagmam.html

[R06] 判断命令是否存在
来源：http://dali.yj20258.top/Article/details/gt2tbwutohk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.smart0.xyz/Article/details/gt2xatrddrh.html

[R07] if 判断文件
来源：http://dali.yj202588.top/Article/details/gt2afheelaj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gt2eoxpddrd.html

[R08] 数值比较
来源：http://dali.ydzc1.top/Article/details/gt2sifzdjog.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cheryme.top/Article/details/gt2fmgaovts.html

[R09] 字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2xaegetch.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuanzhike.top/Article/details/gt2vxkdhhtm.html

[R10] 正则匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ddbtbhle.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258888.top/Article/details/gt2gihnmdtn.html

[R11] case 多分支
来源：http://dali.cdnleiting.top/Article/details/gt2xzatjzyc.html

case "$1" in
来源：http://dali.havefunace.top/Article/details/gt2bapzfluw.html

start) echo "启动" ;;
来源：http://dali.ybcxt.top/Article/details/gt2ulobxacd.html

stop)  echo "停止" ;;
来源：http://dali.sufxvd.cn/Article/details/gt2vrmwgkvx.html

*)     echo "未知命令" ;;
来源：http://dali.fengsongda.top/Article/details/gt2dprhomtn.html

esac
来源：http://dali.snrcjt.cn/Article/details/gt2ityszrpy.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfujznc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.316326.xyz/Article/details/gt2zhkubnjc.html

[R13] for 计数循环
来源：http://dali.yongpay.top/Article/details/gt2jyzdpuki.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hysaishi.cn/Article/details/gt2wrnczmxs.html

[R14] C 风格 for
来源：http://dali.tanke756.top/Article/details/gt2rttwizsi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258888.top/Article/details/gt2gtjixkbm.html

[R15] while 逐行读文件
来源：http://dali.yongpay.top/Article/details/gt2ylpyhute.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenzaomai.com/Article/details/gt2hfvdhruu.html

[R16] until 等待条件
来源：http://dali.yongpay.top/Article/details/gt2jdruuxuy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gt2nqxntxat.html

[R17] 数组定义与取值
来源：http://dali.yj202588.top/Article/details/gt2ocbiejvk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gotoacloud.top/Article/details/gt2cfcxscjr.html

[R18] 遍历数组
来源：http://dali.316326.xyz/Article/details/gt2xtseklnp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2bmejtohu.html

[R19] 数组长度
来源：http://dali.tanke756.top/Article/details/gt2zkfdzmwp.html

echo "${#arr[@]}"
来源：http://dali.chenzaomai.com/Article/details/gt2zyxnnmbj.html

[R20] 关联数组（字典）
来源：http://dali.0kj1m.cn/Article/details/gt2wjvrqzes.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenlongwang.top/Article/details/gt2adbwexhw.html

[R21] 字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2faeiepsc.html

echo "${#s}"
来源：http://dali.yueranfly.top/Article/details/gt2phovqrrx.html

[R22] 截取子串
来源：http://dali.redwolf501.top/Article/details/gt2adokwxjg.html

echo "${s:0:5}"
来源：http://dali.hnxiangtu.top/Article/details/gt2wtlijjjp.html

[R23] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2renchjox.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenlongwang.top/Article/details/gt2pgfmxrqr.html

[R24] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gt2whtujeyn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxinkj.top/Article/details/gt2vcbxvnjk.html

[R25] 去后缀 / 去前缀
来源：http://dali.quarkkingdee.top/Article/details/gt2whgcvwaf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.birdmap.top/Article/details/gt2qivkined.html

[R26] 命令替换
来源：http://dali.yj20258.top/Article/details/gt2pbjbyfka.html

now=$(date +%F); echo "$now"
来源：http://dali.quarkkingdee.top/Article/details/gt2grzgrcti.html

[R27] 算术展开
来源：http://dali.hnxiangtu.top/Article/details/gt2awtnddea.html

echo $((1 + 2 * 3))
来源：http://dali.dashuyun.cn/Article/details/gt2lkmgigke.html

[R28] 浮点运算
来源：http://dali.ydzc1.top/Article/details/gt2nbyaxgsn.html

echo "scale=2; 10/3" | bc
来源：http://dali.yuxming.cn/Article/details/gt2skqsffqn.html

[R29] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2rayyptho.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.havefunace.top/Article/details/gt2szlzftiv.html

[R30] 函数返回状态码
来源：http://dali.c1oappe.top/Article/details/gt2fletivay.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigufen.top/Article/details/gt2tizfbcdx.html

[R31] 局部变量
来源：http://dali.nanxuanxn.top/Article/details/gt2yomphvjh.html

f() { local x=1; echo "$x"; }
来源：http://dali.hywenlv.cn/Article/details/gt2shxdxdmq.html

[R32] 参数个数校验
来源：http://dali.chenlongwang.top/Article/details/gt2bcwtfnig.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ndzvocah.html

[R33] 捕获错误并提示行号
来源：http://dali.feifeiyinyue.top/Article/details/gt2mtvytret.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhongyouzk.top/Article/details/gt2xsnixzob.html

[R34] 退出时清理
来源：http://dali.zhoulong.xyz/Article/details/gt2wzmjkeet.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gt2ffsfjzmf.html

[R35] 后台执行并等待
来源：http://dali.yj20258.top/Article/details/gt2skzxhheo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gaohongyu789.top/Article/details/gt2zytfocsa.html

[R36] 并发执行多个任务
来源：http://dali.jiagoushi.top/Article/details/gt2zavyqler.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jlsjyb.cn/Article/details/gt2eyjybpml.html

[R37] 把输出赋给变量
来源：http://dali.xziqi.cn/Article/details/gt2sxftzhog.html

files=$(ls -1)
来源：http://dali.aizwys.cn/Article/details/gt2chkhnuuz.html

[R38] 管道串联
来源：http://dali.pengpengdd.cyou/Article/details/gt2kyduerlc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ivvv.top/Article/details/gt2wenxdzpj.html

[R39] 重定向标准输出与错误
来源：http://dali.ppjwa.cn/Article/details/gt2niqmciyp.html

cmd > out.log 2>&1
来源：http://dali.jinqigufen.top/Article/details/gt2vfvldbjc.html

[R40] 追加写日志
来源：http://dali.gotoacloud.top/Article/details/gt2jgfjdabz.html

echo "log" >> out.log
来源：http://dali.xylfe.cn/Article/details/gt2gxxdyatd.html

[R41] 丢弃输出
来源：http://dali.yanxiufei.cn/Article/details/gt2hvubuugu.html

cmd >/dev/null 2>&1
来源：http://dali.xuanzx.com/Article/details/gt2glcjvdsx.html

[R42] 输入重定向
来源：http://dali.zhengqikj.top/Article/details/gt2auxvftez.html

wc -l < a.txt
来源：http://dali.ehwqpu.com/Article/details/gt2osgjaqgg.html

[R43] 按名字查找文件
来源：http://dali.hnxiangtu.top/Article/details/gt2zmcerhbp.html

find . -name "*.log" -type f
来源：http://dali.cashguo.top/Article/details/gt2xlvrjilw.html

[R44] 按修改时间查找
来源：http://dali.gzhubu.top/Article/details/gt2ktylgfyw.html

find . -mtime -7 -type f
来源：http://dali.hongshengwenyu.top/Article/details/gt2jybhpohc.html

[R45] 批量删除
来源：http://dali.smart0.xyz/Article/details/gt2jkrgdaly.html

find . -name "*.tmp" -delete
来源：http://dali.sxryk.cn/Article/details/gt2pamfsyyo.html

[R46] 递归替换文件内容
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oswikube.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shuidangran.top/Article/details/gt2hkntwybr.html

[R47] sed 单行替换
来源：http://dali.sweek.top/Article/details/gt2zcoflgzf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2kfiogldp.html

[R48] awk 取指定列
来源：http://dali.snrcjt.cn/Article/details/gt2wqzlssqf.html

awk '{print $1, $3}' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2smenmupu.html

[R49] awk 带条件
来源：http://dali.yj20258.top/Article/details/gt2lmduovui.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenzaomai.com/Article/details/gt2xzfvseln.html

[R50] awk 求和
来源：http://dali.hnqzz.top/Article/details/gt2tzxlbsel.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.c1oappe.top/Article/details/gt2wjpexgsn.html

[R51] 排序去重取前几
来源：http://dali.havefunace.top/Article/details/gt2wwiedvli.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jiagoushi.top/Article/details/gt2lywjmtlb.html

[R52] 统计行数
来源：http://dali.sysykeji.top/Article/details/gt2wfenylqp.html

wc -l a.txt
来源：http://dali.nanxuanxn.top/Article/details/gt2bqnbvhtt.html

[R53] 查看文件头与实时尾
来源：http://dali.sweek.top/Article/details/gt2vwzxsihd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnqzz.top/Article/details/gt2oeyppbru.html

[R54] 比较两个文件
来源：http://dali.meibo888.top/Article/details/gt2hqzkormj.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oglgcdya.html

[R55] 压缩与解压
来源：http://dali.xylfe.cn/Article/details/gt2mgfaiiqz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shangyingyoupin.top/Article/details/gt2wlgypmfp.html

[R56] 远程拷贝
来源：http://dali.sxryk.cn/Article/details/gt2xjfaostv.html

scp file user@host:/path/
来源：http://dali.yueranfly.top/Article/details/gt2gtsginvt.html

[R57] 远程执行命令
来源：http://dali.tian-w.cn/Article/details/gt2rlxahkni.html

ssh user@host 'uptime'
来源：http://dali.shzxlz.cn/Article/details/gt2mgjvwogz.html

[R58] 下载文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2yenfktla.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tanke756.top/Article/details/gt2mmurhrph.html

[R59] 发 POST JSON
来源：http://dali.ivvv.top/Article/details/gt2nfvohyda.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenjidiqi.icu/Article/details/gt2ozjwfaxr.html

[R60] 只看 HTTP 状态码
来源：http://dali.ppjwa.cn/Article/details/gt2pcojtoms.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sxryk.cn/Article/details/gt2ahuwpjvf.html

[R61] 磁盘占用
来源：http://dali.pengpengdd.cyou/Article/details/gt2soavtaqp.html

df -h;  du -sh *
来源：http://dali.yuxming.cn/Article/details/gt2yzsdspls.html

[R62] 找最占空间的文件
来源：http://dali.gaohongyu789.top/Article/details/gt2nlnuzqxk.html

du -ah . | sort -rh | head -10
来源：http://dali.svipenyu.cn/Article/details/gt2vltjpuur.html

[R63] 内存与进程
来源：http://dali.zhixingplan.top/Article/details/gt2jvrijuhv.html


<!-- 参考信息 -->