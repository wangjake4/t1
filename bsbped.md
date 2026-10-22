代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.andypj.xyz/Article/details/gtktgbtnwp.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gtmkuqvmvj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shuidangran.top/Article/details/gtxmnzwxlp.html

[Q19] 范围查询
来源：http://dali.daxiang520.top/Article/details/gtuccxnpoc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.dianchejie.cn/Article/details/gtpwuvjegy.html

[Q20] IN 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhmvfdzc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sxryk.cn/Article/details/gthbuodlwz.html

[Q21] 空值判断
来源：http://dali.gzhubu.top/Article/details/gtayxigjwl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tanke756.top/Article/details/gtpysabovb.html

[Q22] 排序
来源：http://dali.hongshengwenyu.top/Article/details/gtvvwxdsng.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yuxming.cn/Article/details/gtnrqhzhrq.html

[Q23] 分页
来源：http://dali.ehwqpu.com/Article/details/gtnpntrdkq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj202588.top/Article/details/gtfblejffc.html

[Q24] 去重
来源：http://dali.birdmap.top/Article/details/gtqecfobal.html

SELECT DISTINCT city FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtzsdfocpz.html

[Q25] 只取前 N 条
来源：http://dali.zhoulong.xyz/Article/details/gthaqmmnrl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkrmpqsr.html

[Q26] 计数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbimecxu.html

SELECT COUNT(*) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtzlyqphqa.html

[Q27] 条件计数
来源：http://dali.jqgfzy.top/Article/details/gtprvisayj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtkgolzsqb.html

[Q28] 求和与平均
来源：http://dali.shuidangran.top/Article/details/gtoyfqehrs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkqctewm.html

[Q29] 最大最小值
来源：http://dali.chenjidiqi.icu/Article/details/gtplselyov.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtrvqcndoq.html

[Q30] 分组统计
来源：http://dali.fengsongda.top/Article/details/gtmggmrrov.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtmakiqsbv.html

[Q31] 分组后过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtstkbtnso.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hywenlv.cn/Article/details/gtmdngimnb.html

[Q32] 分组拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gtwhhjpjmq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gtxynckarq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ppjwa.cn/Article/details/gtjkptkymk.html

[Q33] 多列分组
来源：http://dali.jqgufenzy.top/Article/details/gtfqxexbzm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinqigfzy.top/Article/details/gtskvlikpx.html

[Q34] 每组取第一条
来源：http://dali.cucudq.cn/Article/details/gtcgaksuuc.html

SELECT * FROM (
来源：http://dali.aizwys.cn/Article/details/gtfuprkbfk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ivvv.top/Article/details/gtwawaljmo.html

) t WHERE rn = 1;
来源：http://dali.cucudq.cn/Article/details/gtkjyjkqjy.html

[Q35] 内连接
来源：http://dali.chenzaomai.com/Article/details/gtbtixiqdo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.snrcjt.cn/Article/details/gtouwilmta.html

[Q36] 左连接
来源：http://dali.jqgfzy.top/Article/details/gtctfxoghj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gtgfhuyumv.html

[Q37] 右连接
来源：http://dali.zdqjudy.top/Article/details/gtphhxbkjv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttroexmyt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtduwitskn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.aizwys.cn/Article/details/gtgnrpawok.html

[Q39] 自连接（查上下级）
来源：http://dali.nwbrower.top/Article/details/gtgiwxkhwi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.pycfn.com/Article/details/gtehdmzvrm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aizwys.cn/Article/details/gtqyojdntp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yuxming.cn/Article/details/gtcjjqfyis.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxgoylcmx.html

[Q41] 多表连接
来源：http://dali.svipenyu.cn/Article/details/gtojzopysq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yanxiufei.cn/Article/details/gtypszszzx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.meibo888.top/Article/details/gtqhmmwifh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sweek.top/Article/details/gtdaskohcx.html

[Q42] 连接条件附加过滤
来源：http://dali.jqgfzy.top/Article/details/gtcvyvssol.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuanzx.com/Article/details/gtzplwziyf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.vqdsnc.cn/Article/details/gtgpvlqwvy.html

[Q43] 标量子查询
来源：http://dali.chenlongwang.top/Article/details/gtnfekumsj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aizwys.cn/Article/details/gtenoehbpv.html

[Q44] IN 子查询
来源：http://dali.yueranfly.top/Article/details/gtdvzkgxwx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.bjfxy.top/Article/details/gtvqslbxmu.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigufen.top/Article/details/gtzjpjfygp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gtikllioln.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhiwuduotai.top/Article/details/gtndmhuzrf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jiagoushi.top/Article/details/gtrfatwhyc.html

[Q47] 与平均值比较
来源：http://dali.tian-w.cn/Article/details/gtyclqnijz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ivvv.top/Article/details/gtvtimhvem.html

[Q48] CTE 公用表表达式
来源：http://dali.chenzaomai.com/Article/details/gtnwapbmlk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hnqzz.top/Article/details/gtfzscrhoi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xuetiantiany.cn/Article/details/gtifmgmobz.html

[Q49] 更新单行
来源：http://dali.yangfankeji.com/Article/details/gtfkoogxay.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gtsiwzmuvo.html

[Q50] 批量更新
来源：http://dali.ehwqpu.com/Article/details/gtetvvdetp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nanxuanxn.top/Article/details/gtqatkltil.html

[Q51] 用子查询更新
来源：http://dali.wangshuangyany.cn/Article/details/gtthoygcjn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.316326.xyz/Article/details/gtxamhdwrd.html

[Q52] 删除指定行
来源：http://dali.wangdashe.top/Article/details/gtmwptfvzx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gaohongyu789.top/Article/details/gtajpdssph.html

[Q53] 按条件删除
来源：http://dali.jianghu66.top/Article/details/gtashscifp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.fzhhl.top/Article/details/gtgxlbjhho.html

[Q54] 清空表
来源：http://dali.kuanghao11.cn/Article/details/gtovbslgnu.html

TRUNCATE TABLE logs;
来源：http://dali.yueranfly.top/Article/details/gtblxaeiyr.html

[Q55] 排名（并列占位）
来源：http://dali.jqgufenzy.top/Article/details/gtllmcafir.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gtfsuwckyg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gtvkvbdloo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrixipyt.html

[Q57] 行号
来源：http://dali.hammf.cn/Article/details/gtvdfivssu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhixingplan.top/Article/details/gteluccsyr.html

[Q58] 累计求和
来源：http://dali.jyoumei.cn/Article/details/gtmtsjctbx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtnflgfyhx.html

[Q59] 分组内累计
来源：http://dali.andypj.xyz/Article/details/gtqlyrcovx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtmdjtarsx.html

[Q60] 取上一行 / 下一行
来源：http://dali.c1oappe.top/Article/details/gthbyhnmjj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tanke756.top/Article/details/gtqueyzpqj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdvxnoux.html

[Q61] 移动平均
来源：http://dali.sysykeji.top/Article/details/gtjoxjkyum.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gttceqdzyu.html

[Q62] 分组占比
来源：http://dali.andypj.xyz/Article/details/gtvcfdbefs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gttcuoljxa.html

[Q63] 开启事务
来源：http://dali.guannengcc.top/Article/details/gtuskjbrvk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nwbrower.top/Article/details/gtrnzqyosq.html

[Q64] 提交事务
来源：http://dali.zhengqikj.top/Article/details/gtxdupenpl.html

COMMIT;
来源：http://dali.tanke756.top/Article/details/gterdrsqzt.html

[Q65] 回滚事务
来源：http://dali.cqqwz.cn/Article/details/gtfzjvpbrm.html

ROLLBACK;
来源：http://dali.sxryk.cn/Article/details/gthmpcxpls.html

[Q66] 行锁查询
来源：http://dali.yuanzhike.top/Article/details/gtgmpmsvds.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.iojbl.cn/Article/details/gtvvdtbwnc.html

[Q67] 设置隔离级别
来源：http://dali.nwbrower.top/Article/details/gtbsmtjdhb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cucudq.cn/Article/details/gtgsrknqlo.html

[Q68] 保存点
来源：http://dali.tianlin.xyz/Article/details/gtqgwutpjf.html

SAVEPOINT sp1;
来源：http://dali.ybcxt.top/Article/details/gtbfvfbukj.html

ROLLBACK TO sp1;
来源：http://dali.ybcxt.top/Article/details/gthheabcwa.html

[Q69] 查看执行计划
来源：http://dali.hongshengwenyu.top/Article/details/gtzwzlzjso.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fzhhl.top/Article/details/gtkhqjjkur.html

[Q70] 更新统计信息
来源：http://dali.cashguo.top/Article/details/gtigynwkfq.html

ANALYZE TABLE users;
来源：http://dali.ppjwa.cn/Article/details/gtccuyoqvu.html

[Q71] 查看建表语句
来源：http://dali.vqdsnc.cn/Article/details/gtsfyuzpcm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dianchejie.cn/Article/details/gtlzjsrdij.html

[Q72] 查看索引
来源：http://dali.jiagoushi.top/Article/details/gthcezsowu.html

SHOW INDEX FROM users;
来源：http://dali.tian-w.cn/Article/details/gtsxzkrzez.html

[Q73] 查看表状态
来源：http://dali.guowangkeji.top/Article/details/gtnwzerznw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zdqjudy.top/Article/details/gtpojamumd.html

[Q74] 强制使用索引
来源：http://dali.chenzaomai.com/Article/details/gtwhzeetqj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cashguo.top/Article/details/gtttxrpynx.html

[Q75] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gthzhsnwwl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtklmvrepu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sxryk.cn/Article/details/gtezcldcgk.html

[Q76] 按天统计
来源：http://dali.cqqwz.cn/Article/details/gtcwjcokdf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.snrcjt.cn/Article/details/gtcrxlkeiw.html

[Q77] 时间加减
来源：http://dali.kuanghao11.cn/Article/details/gtuxirqwxl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcdishjm.html

[Q78] 当前时间
来源：http://dali.xylfe.cn/Article/details/gtmdkvqiqp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgfzy.top/Article/details/gtebzpekbi.html

[Q79] 字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwbqbwvo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jyoumei.cn/Article/details/gtllvfedjd.html

[Q80] 字符串截取
来源：http://dali.yvedp.cn/Article/details/gtorgqidkx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtyeecgllm.html

[Q81] 字符串替换
来源：http://dali.gogol.net.cn/Article/details/gtstiwhtby.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258.top/Article/details/gtyhgnorbh.html

[Q82] 字符长度与字节长度
来源：http://dali.xinyue.icu/Article/details/gtmkrlwucf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gtrkmdybis.html

[Q83] 大小写转换
来源：http://dali.ivvv.top/Article/details/gtuqlakrci.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtiyphzegv.html

[Q84] 去除首尾空格
来源：http://dali.jinqigufen.top/Article/details/gthnoapnuh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtbtwxmydc.html

[Q85] 数值取整
来源：http://dali.gzhubu.top/Article/details/gtigbzktxe.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cqqwz.cn/Article/details/gtxfoslfjn.html

[Q86] 读取 JSON 字段
来源：http://dali.xuetiantiany.cn/Article/details/gtisjsyrqx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.316326.xyz/Article/details/gtyqmouwvb.html

[Q87] JSON 字段做条件
来源：http://dali.ydzc1.top/Article/details/gtpqdkkrdx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcodvojzs.html

[Q88] 行转列（条件聚合）
来源：http://dali.quarkkingdee.top/Article/details/gtxeamyejo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hywenlv.cn/Article/details/gtafitfjpz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cucudq.cn/Article/details/gteprtrggb.html

[Q89] 判断表是否存在
来源：http://dali.hammf.cn/Article/details/gttetyqnap.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenlongwang.top/Article/details/gtwtgzxdid.html

[Q90] 生成序号列
来源：http://dali.wangshuangyany.cn/Article/details/gtdzlgalma.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gotoacloud.top/Article/details/gtdbazghjz.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtoqovsuos.html

R. Bash 专题
来源：http://dali.0kj1m.cn/Article/details/gtxegqduna.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtnvlojrld.html

[R01] shebang 与严格模式
来源：http://dali.cheryme.top/Article/details/gtesxwoiuq.html

#!/usr/bin/env bash
来源：http://dali.zhixingplan.top/Article/details/gtxwwugrrx.html

set -euo pipefail
来源：http://dali.c1oappe.top/Article/details/gtbanaurqj.html

[R02] 变量赋值与使用
来源：http://dali.zhoulong.xyz/Article/details/gteaflrjjn.html

name="Tom"; echo "$name"
来源：http://dali.dianchejie.cn/Article/details/gtxonskhbq.html

[R03] 只读变量
来源：http://dali.yonumen.top/Article/details/gtrmvuiihy.html

readonly PI=3.14
来源：http://dali.cashguo.top/Article/details/gtopdxmwzz.html

[R04] 位置参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpjxefzxx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sufxvd.cn/Article/details/gtafviklrl.html

[R05] 参数默认值
来源：http://dali.c1oappe.top/Article/details/gtaajqpcom.html

name="${1:-default}"
来源：http://dali.hysaishi.cn/Article/details/gtsbcetihq.html

[R06] 判断命令是否存在
来源：http://dali.yuanzhike.top/Article/details/gtntlcholc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gtoldpavai.html

[R07] if 判断文件
来源：http://dali.ybcxt.top/Article/details/gthronhnjt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtayrwiolq.html

[R08] 数值比较
来源：http://dali.jqgfzy.top/Article/details/gtspjeputn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.aibaodan.cn/Article/details/gtkqbmhgsd.html

[R09] 字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gtxufbqbkd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tanke756.top/Article/details/gtnnpbztnk.html

[R10] 正则匹配
来源：http://dali.wangdashe.top/Article/details/gtcotmzjrk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gotoacloud.top/Article/details/gtjazahfor.html

[R11] case 多分支
来源：http://dali.fzhhl.top/Article/details/gtuodsoquv.html

case "$1" in
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdwzyguz.html

start) echo "启动" ;;
来源：http://dali.bjfxy.top/Article/details/gtlawyfbjk.html

stop)  echo "停止" ;;
来源：http://dali.9152youxi.cn/Article/details/gtwqbzfwax.html

*)     echo "未知命令" ;;
来源：http://dali.gzhubu.top/Article/details/gtgiibfdyq.html

esac
来源：http://dali.zdqjudy.top/Article/details/gtbtkmwhpl.html

[R12] for 遍历文件
来源：http://dali.xuetiantiany.cn/Article/details/gtmhumhzfv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shuidangran.top/Article/details/gtdmmbroba.html

[R13] for 计数循环
来源：http://dali.gaohongyu789.top/Article/details/gtbeapfcqy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenjidiqi.icu/Article/details/gthutfxako.html

[R14] C 风格 for
来源：http://dali.fzhhl.top/Article/details/gtvcbiizlp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gtevmaohjg.html

[R15] while 逐行读文件
来源：http://dali.yuxming.cn/Article/details/gtlnobuzir.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cheryme.top/Article/details/gtklrnavbw.html

[R16] until 等待条件
来源：http://dali.tanke756.top/Article/details/gtywpvghlc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gtgairjssy.html

[R17] 数组定义与取值
来源：http://dali.shuidangran.top/Article/details/gtiyqiqmxr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenzaomai.com/Article/details/gtuxqcldis.html

[R18] 遍历数组
来源：http://dali.zhiwuduotai.top/Article/details/gtvpfsgdls.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sysykeji.top/Article/details/gtverrhjcr.html

[R19] 数组长度
来源：http://dali.zycfv.cn/Article/details/gtzqaoquaz.html

echo "${#arr[@]}"
来源：http://dali.zdqjudy.top/Article/details/gtdnqfxsel.html

[R20] 关联数组（字典）
来源：http://dali.gogol.net.cn/Article/details/gtzxvhrfrp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xylfe.cn/Article/details/gtkyxujpss.html

[R21] 字符串长度
来源：http://dali.tanke756.top/Article/details/gtzyfqzsui.html

echo "${#s}"
来源：http://dali.jinqigufen.top/Article/details/gtnajimcqg.html

[R22] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gtbbqmbsua.html

echo "${s:0:5}"
来源：http://dali.zhongyouzk.top/Article/details/gthmjulmxi.html

[R23] 字符串替换
来源：http://dali.xylfe.cn/Article/details/gtjfkiwrkb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yueranfly.top/Article/details/gtcrzchnpe.html

[R24] 大小写转换
来源：http://dali.jiagoushi.top/Article/details/gtkndkdolk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ybcxt.top/Article/details/gthrtgdhjz.html

[R25] 去后缀 / 去前缀
来源：http://dali.vqdsnc.cn/Article/details/gtdsqzopwu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cdnleiting.top/Article/details/gtaufeytke.html

[R26] 命令替换
来源：http://dali.gogol.net.cn/Article/details/gtrroetuid.html

now=$(date +%F); echo "$now"
来源：http://dali.zycfv.cn/Article/details/gtjrimdjwt.html

[R27] 算术展开
来源：http://dali.havefunace.top/Article/details/gtrxcjpsaw.html

echo $((1 + 2 * 3))
来源：http://dali.hongshengwenyu.top/Article/details/gtykdfdvfw.html

[R28] 浮点运算
来源：http://dali.kuanghao11.cn/Article/details/gtaaygmnpc.html

echo "scale=2; 10/3" | bc
来源：http://dali.quarkkingdee.top/Article/details/gtqexjssvh.html

[R29] 定义函数
来源：http://dali.yangfankeji.com/Article/details/gtzplhqasz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.pycfn.com/Article/details/gtkrxczyjy.html

[R30] 函数返回状态码
来源：http://dali.nwbrower.top/Article/details/gtzkcgvrwx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cheryme.top/Article/details/gtfnkydgpx.html

[R31] 局部变量
来源：http://dali.xinyue.icu/Article/details/gtmvpbvcul.html

f() { local x=1; echo "$x"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmcheoqc.html

[R32] 参数个数校验
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtopjuoxgm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gtmtziyaiz.html

[R33] 捕获错误并提示行号
来源：http://dali.jyoumei.cn/Article/details/gtkwyfdttf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhbxtgaa.html

[R34] 退出时清理
来源：http://dali.ehwqpu.com/Article/details/gtfinilkde.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yanxiufei.cn/Article/details/gtunevghah.html

[R35] 后台执行并等待
来源：http://dali.316326.xyz/Article/details/gtohmbqafx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgufenzy.top/Article/details/gtqfekblbe.html

[R36] 并发执行多个任务
来源：http://dali.meibo888.top/Article/details/gtcbcixnxs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sysykeji.top/Article/details/gtzyttihva.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfgujywn.html

files=$(ls -1)
来源：http://dali.aibaodan.cn/Article/details/gtbrjxvugw.html

[R38] 管道串联
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnrbfkah.html

cat a.txt | grep -i error | wc -l
来源：http://dali.svipenyu.cn/Article/details/gtnlonvbag.html

[R39] 重定向标准输出与错误
来源：http://dali.fengsongda.top/Article/details/gtjjhkrigk.html

cmd > out.log 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gtyhyjcccf.html

[R40] 追加写日志
来源：http://dali.shangyingyoupin.top/Article/details/gtqdjaxfjg.html

echo "log" >> out.log
来源：http://dali.xinyue.icu/Article/details/gtmwdesblv.html

[R41] 丢弃输出
来源：http://dali.yuanzhike.top/Article/details/gtbfwopiuo.html

cmd >/dev/null 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gtgzfmhjsh.html

[R42] 输入重定向
来源：http://dali.jinqigfzy.top/Article/details/gtumtmtlgb.html

wc -l < a.txt
来源：http://dali.sweek.top/Article/details/gtcbikxlbv.html

[R43] 按名字查找文件
来源：http://dali.xuanzx.com/Article/details/gttcqbvqkw.html

find . -name "*.log" -type f
来源：http://dali.nanxinkj.top/Article/details/gtllbbemsw.html

[R44] 按修改时间查找
来源：http://dali.jinqigfzy.top/Article/details/gtgocncoyj.html

find . -mtime -7 -type f
来源：http://dali.sufxvd.cn/Article/details/gtyqqvlrzm.html

[R45] 批量删除
来源：http://dali.feifeiyinyue.top/Article/details/gtmovuccrt.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangkeji.top/Article/details/gttunbrcmt.html

[R46] 递归替换文件内容
来源：http://dali.feifeiyinyue.top/Article/details/gtzhqoruxf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hysaishi.cn/Article/details/gtmqvtjguu.html

[R47] sed 单行替换
来源：http://dali.zhixingplan.top/Article/details/gtkxmosoby.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xziqi.cn/Article/details/gttadbeyvm.html

[R48] awk 取指定列
来源：http://dali.jinqigufen.top/Article/details/gtruwgknap.html

awk '{print $1, $3}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gtnokyloia.html

[R49] awk 带条件
来源：http://dali.tianlin.xyz/Article/details/gtmjoaffuo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fzhhl.top/Article/details/gtrtgkhrxl.html

[R50] awk 求和
来源：http://dali.fengsongda.top/Article/details/gtnqvljpuy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtwlbbasjn.html

[R51] 排序去重取前几
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozxrlsiv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258.top/Article/details/gtxlswiisg.html

[R52] 统计行数
来源：http://dali.sysykeji.top/Article/details/gttncbtgkf.html

wc -l a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtvysmwvjq.html

[R53] 查看文件头与实时尾
来源：http://dali.birdmap.top/Article/details/gtpczyrzzn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.dianchejie.cn/Article/details/gtxhvlqjxe.html

[R54] 比较两个文件
来源：http://dali.cheryme.top/Article/details/gtjgifskrn.html

diff a.txt b.txt
来源：http://dali.yj20258.top/Article/details/gtxvbvjmaw.html

[R55] 压缩与解压
来源：http://dali.cdnleiting.top/Article/details/gtlepzrucr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.redwolf501.top/Article/details/gtiiekapri.html

[R56] 远程拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoiizxcxk.html

scp file user@host:/path/
来源：http://dali.redwolf501.top/Article/details/gtbpomdgnb.html

[R57] 远程执行命令
来源：http://dali.tianlin.xyz/Article/details/gtmnxadfse.html

ssh user@host 'uptime'
来源：http://dali.yueranfly.top/Article/details/gtgsjndygr.html

[R58] 下载文件
来源：http://dali.snrcjt.cn/Article/details/gtkpptebqx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hysaishi.cn/Article/details/gtxtoyltls.html

[R59] 发 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgmpugad.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ivvv.top/Article/details/gtvjlylrpn.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gtqrdjajdl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj202588.top/Article/details/gtjmdyqojx.html

[R61] 磁盘占用
来源：http://dali.xziqi.cn/Article/details/gtadqdykva.html

df -h;  du -sh *
来源：http://dali.daria6918.cn/Article/details/gtqfcwhgss.html

[R62] 找最占空间的文件
来源：http://dali.svipenyu.cn/Article/details/gtldqmxlyo.html

du -ah . | sort -rh | head -10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwbthlsn.html

[R63] 内存与进程
来源：http://dali.aizwys.cn/Article/details/gtbqpcvlyd.html

free -h;  ps aux | grep nginx
来源：http://dali.yj202588.top/Article/details/gtihdatpif.html

[R64] 结束进程
来源：http://dali.ehwqpu.com/Article/details/gtaxuvwcre.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj202588.top/Article/details/gtemkltjbk.html

[R65] 查看端口占用
来源：http://dali.mhx1999.top/Article/details/gtwetqyomf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sufxvd.cn/Article/details/gtsrzwsfmm.html

[R66] 定时任务
来源：http://dali.aibaodan.cn/Article/details/gtigarrawp.html

crontab -e;  crontab -l
来源：http://dali.fzhhl.top/Article/details/gtwarvpliu.html

[R67] 生成随机十六进制串
来源：http://dali.yanxiufei.cn/Article/details/gtlzgywbas.html


<!-- 参考信息 -->