代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zdqjudy.top/Article/details/gt2lrizfxev.html

[Q18] 模糊匹配
来源：http://dali.ivvv.top/Article/details/gt2twcfkbjr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hywenlv.cn/Article/details/gt2txofywbd.html

[Q19] 范围查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2snyexesd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.haohaochexian.top/Article/details/gt2czphxchm.html

[Q20] IN 列表
来源：http://dali.sysykeji.top/Article/details/gt2lzntewib.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cqqwz.cn/Article/details/gt2vublkslz.html

[Q21] 空值判断
来源：http://dali.zhoulong.xyz/Article/details/gt2fcjsoqcp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pppdkpvh.html

[Q22] 排序
来源：http://dali.wangshuangyany.cn/Article/details/gt2qsbtgvef.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sweek.top/Article/details/gt2ihbsawyj.html

[Q23] 分页
来源：http://dali.pengpengdd.cyou/Article/details/gt2xmgfxuuy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.aibaodan.cn/Article/details/gt2sozakwsc.html

[Q24] 去重
来源：http://dali.yvedp.cn/Article/details/gt2thvzcsok.html

SELECT DISTINCT city FROM users;
来源：http://dali.316326.xyz/Article/details/gt2wtzcvvvk.html

[Q25] 只取前 N 条
来源：http://dali.yongpay.top/Article/details/gt2dhzbsmdf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.0kj1m.cn/Article/details/gt2yezzrnjd.html

[Q26] 计数
来源：http://dali.gzhubu.top/Article/details/gt2uvblwbck.html

SELECT COUNT(*) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2yewhybvx.html

[Q27] 条件计数
来源：http://dali.aibaodan.cn/Article/details/gt2bwmduuxg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2wkkcbqra.html

[Q28] 求和与平均
来源：http://dali.hfpthk.cn/Article/details/gt2oxrzxdfc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tanke756.top/Article/details/gt2zntkiwqt.html

[Q29] 最大最小值
来源：http://dali.hnqzz.top/Article/details/gt2flbopuyu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2envkfbzt.html

[Q30] 分组统计
来源：http://dali.sweek.top/Article/details/gt2qulkxljm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gt2wkjntmjz.html

[Q31] 分组后过滤
来源：http://dali.xinyue.icu/Article/details/gt2iwvzkbdi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhiwuduotai.top/Article/details/gt2pqlnaygc.html

[Q32] 分组拼接字符串
来源：http://dali.xziqi.cn/Article/details/gt2dalcuhfq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gt2ibypdmru.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hongshengwenyu.top/Article/details/gt2qjxnkxpi.html

[Q33] 多列分组
来源：http://dali.bjfxy.top/Article/details/gt2kuvybgmi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sysykeji.top/Article/details/gt2okwdhqya.html

[Q34] 每组取第一条
来源：http://dali.ybcxt.top/Article/details/gt2stzcarbf.html

SELECT * FROM (
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ngxycndh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jlsjyb.cn/Article/details/gt2jcmasoqa.html

) t WHERE rn = 1;
来源：http://dali.gotoacloud.top/Article/details/gt2eqbvwrfl.html

[Q35] 内连接
来源：http://dali.tian-w.cn/Article/details/gt2hghgkdff.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gt2dnnncysi.html

[Q36] 左连接
来源：http://dali.shuidangran.top/Article/details/gt2vohjocyy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.pengpengdd.cyou/Article/details/gt2yssxpioa.html

[Q37] 右连接
来源：http://dali.bjfxy.top/Article/details/gt2jlyryfro.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cqqwz.cn/Article/details/gt2mcvmvitl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aizwys.cn/Article/details/gt2vrjajdfl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tian-w.cn/Article/details/gt2snwzpppz.html

[Q39] 自连接（查上下级）
来源：http://dali.xuetiantiany.cn/Article/details/gt2sabmzyyo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zdqjudy.top/Article/details/gt2ovgopdol.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2srhcplim.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.andypj.xyz/Article/details/gt2mskwsbvl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sweek.top/Article/details/gt2jslviwgk.html

[Q41] 多表连接
来源：http://dali.sufxvd.cn/Article/details/gt2lqtbicej.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.fzhhl.top/Article/details/gt2gjmdhhwi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shuidangran.top/Article/details/gt2eytuqrdy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eykbgiah.html

[Q42] 连接条件附加过滤
来源：http://dali.chenjidiqi.icu/Article/details/gt2mrrbmddi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jyoumei.cn/Article/details/gt2bbifzefu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2utrccjmx.html

[Q43] 标量子查询
来源：http://dali.aizwys.cn/Article/details/gt2rdbviqvf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.guowangkeji.top/Article/details/gt2yoencqok.html

[Q44] IN 子查询
来源：http://dali.svipenyu.cn/Article/details/gt2fslynlmo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhixingplan.top/Article/details/gt2fxlvevrh.html

[Q45] EXISTS 判断存在
来源：http://dali.mhx1999.top/Article/details/gt2nqmyqmpp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hammf.cn/Article/details/gt2umylwofa.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgufenzy.top/Article/details/gt2bjfnwern.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gt2zxtvagzt.html

[Q47] 与平均值比较
来源：http://dali.chenlongwang.top/Article/details/gt2ctobqtvd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyhehom.html

[Q48] CTE 公用表表达式
来源：http://dali.pycfn.com/Article/details/gt2vjfllwyd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cqqwz.cn/Article/details/gt2ozfefhem.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cucudq.cn/Article/details/gt2lkidigir.html

[Q49] 更新单行
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zfmuhvbg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gt2vgxzjxpo.html

[Q50] 批量更新
来源：http://dali.yj202588.top/Article/details/gt2jyvdtytt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ibpxjvrn.html

[Q51] 用子查询更新
来源：http://dali.ehwqpu.com/Article/details/gt2rahfrmsf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sxryk.cn/Article/details/gt2npywfcao.html

[Q52] 删除指定行
来源：http://dali.guowangkeji.top/Article/details/gt2bvnbnunk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258888.top/Article/details/gt2uzmxlqom.html

[Q53] 按条件删除
来源：http://dali.iojbl.cn/Article/details/gt2dixpswjq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.quarkkingdee.top/Article/details/gt2mtuhnaen.html

[Q54] 清空表
来源：http://dali.tianlin.xyz/Article/details/gt2jwhxmzjt.html

TRUNCATE TABLE logs;
来源：http://dali.yueranfly.top/Article/details/gt2lkcgepcx.html

[Q55] 排名（并列占位）
来源：http://dali.yvedp.cn/Article/details/gt2ipjmpreg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.aizwys.cn/Article/details/gt2cglboftz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2leedrodl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.dashuyun.cn/Article/details/gt2gaxdrkuz.html

[Q57] 行号
来源：http://dali.hammf.cn/Article/details/gt2xzwcfoid.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2gvpplhyk.html

[Q58] 累计求和
来源：http://dali.cqqwz.cn/Article/details/gt2asqpgdwa.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ohaskmit.html

[Q59] 分组内累计
来源：http://dali.wangshuangyany.cn/Article/details/gt2nfcsrsqp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sweek.top/Article/details/gt2zpuzgcsj.html

[Q60] 取上一行 / 下一行
来源：http://dali.gotoacloud.top/Article/details/gt2segxvyov.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sujzwahm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.andypj.xyz/Article/details/gt2ghsoobrj.html

[Q61] 移动平均
来源：http://dali.redwolf501.top/Article/details/gt2qycsgnlq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gt2llzpbokv.html

[Q62] 分组占比
来源：http://dali.pengpengdd.cyou/Article/details/gt2nyztmxqh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gt2fvfsmvwx.html

[Q63] 开启事务
来源：http://dali.guannengcc.top/Article/details/gt2lpdbjpid.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.redwolf501.top/Article/details/gt2kplkajeg.html

[Q64] 提交事务
来源：http://dali.jyoumei.cn/Article/details/gt2gpdkvdgm.html

COMMIT;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tgobyxdq.html

[Q65] 回滚事务
来源：http://dali.xylfe.cn/Article/details/gt2tbgzxxng.html

ROLLBACK;
来源：http://dali.dianchejie.cn/Article/details/gt2uaqxlcno.html

[Q66] 行锁查询
来源：http://dali.chenlongwang.top/Article/details/gt2gjupngdi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hysaishi.cn/Article/details/gt2xhfskxta.html

[Q67] 设置隔离级别
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2acikdliv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ehwqpu.com/Article/details/gt2llzelltk.html

[Q68] 保存点
来源：http://dali.xuetiantiany.cn/Article/details/gt2ugztaass.html

SAVEPOINT sp1;
来源：http://dali.kuanghao11.cn/Article/details/gt2ygwegkph.html

ROLLBACK TO sp1;
来源：http://dali.guowangkeji.top/Article/details/gt2kobdbvlm.html

[Q69] 查看执行计划
来源：http://dali.jyoumei.cn/Article/details/gt2wwxucjhi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daxiang520.top/Article/details/gt2pxelksxx.html

[Q70] 更新统计信息
来源：http://dali.yuanzhike.top/Article/details/gt2tnlfsbqp.html

ANALYZE TABLE users;
来源：http://dali.yuxming.cn/Article/details/gt2qbjpbktt.html

[Q71] 查看建表语句
来源：http://dali.quarkkingdee.top/Article/details/gt2eiuowblj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.bjfxy.top/Article/details/gt2pezlzlht.html

[Q72] 查看索引
来源：http://dali.wangshuangyany.cn/Article/details/gt2nwnogoik.html

SHOW INDEX FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2wbfwlilb.html

[Q73] 查看表状态
来源：http://dali.hywenlv.cn/Article/details/gt2ifabapto.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nanxuanxn.top/Article/details/gt2cggszfrj.html

[Q74] 强制使用索引
来源：http://dali.kuanghao11.cn/Article/details/gt2bcocwufd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nwbrower.top/Article/details/gt2turhoogl.html

[Q75] 日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2npdmrocb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gt2jrpfirnk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhengqikj.top/Article/details/gt2ecjajnlh.html

[Q76] 按天统计
来源：http://dali.zdqjudy.top/Article/details/gt2oplmvibx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhongyouzk.top/Article/details/gt2ihbhllfu.html

[Q77] 时间加减
来源：http://dali.guannengcc.top/Article/details/gt2ieweukjo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yvedp.cn/Article/details/gt2juunvpsp.html

[Q78] 当前时间
来源：http://dali.ivvv.top/Article/details/gt2pkaoyuus.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jlsjyb.cn/Article/details/gt2kmbdgkgl.html

[Q79] 字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gt2eypwltpl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sysykeji.top/Article/details/gt2fayukybi.html

[Q80] 字符串截取
来源：http://dali.aizwys.cn/Article/details/gt2bkjopzhw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2wnlgxrni.html

[Q81] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gt2qgiftwfd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2pquspmay.html

[Q82] 字符长度与字节长度
来源：http://dali.tanke756.top/Article/details/gt2pidkstvm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ibhyljir.html

[Q83] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gt2gfuzxncy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2bwyuhmyq.html

[Q84] 去除首尾空格
来源：http://dali.xylfe.cn/Article/details/gt2wlytkcyd.html

SELECT TRIM(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2zjokchvn.html

[Q85] 数值取整
来源：http://dali.c1oappe.top/Article/details/gt2byxmgqoj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xylfe.cn/Article/details/gt2zhzrqtyb.html

[Q86] 读取 JSON 字段
来源：http://dali.gotoacloud.top/Article/details/gt2pbytdbek.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ybcxt.top/Article/details/gt2tvxutycw.html

[Q87] JSON 字段做条件
来源：http://dali.jianghu66.top/Article/details/gt2cqrfkxmd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinqigufen.top/Article/details/gt2xtoblfoe.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnxiangtu.top/Article/details/gt2tmgfqaso.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xziqi.cn/Article/details/gt2tfrcurvg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2pbwjnyiw.html

[Q89] 判断表是否存在
来源：http://dali.hnqzz.top/Article/details/gt2vecmogkg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pqlqpvyz.html

[Q90] 生成序号列
来源：http://dali.yj20258888.top/Article/details/gt2pmscxjnn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gzhubu.top/Article/details/gt2jdztfnoe.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2zbidovri.html

R. Bash 专题
来源：http://dali.hysaishi.cn/Article/details/gt2sxuocpcp.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2obvskfzm.html

[R01] shebang 与严格模式
来源：http://dali.haohaochexian.top/Article/details/gt2blxabawo.html

#!/usr/bin/env bash
来源：http://dali.yueranfly.top/Article/details/gt2ynidvtvu.html

set -euo pipefail
来源：http://dali.tianlin.xyz/Article/details/gt2eippfgwp.html

[R02] 变量赋值与使用
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2egxewocc.html

name="Tom"; echo "$name"
来源：http://dali.wangshuangyany.cn/Article/details/gt2dmzfpwcg.html

[R03] 只读变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2yzvjbmsy.html

readonly PI=3.14
来源：http://dali.haohaochexian.top/Article/details/gt2iwenfufd.html

[R04] 位置参数
来源：http://dali.sxryk.cn/Article/details/gt2lgtgddgt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hammf.cn/Article/details/gt2auctfusy.html

[R05] 参数默认值
来源：http://dali.ivvv.top/Article/details/gt2kgjqcnzf.html

name="${1:-default}"
来源：http://dali.meibo888.top/Article/details/gt2tfcxeikb.html

[R06] 判断命令是否存在
来源：http://dali.daria6918.cn/Article/details/gt2mgizmptv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gt2xuaopjpb.html

[R07] if 判断文件
来源：http://dali.zhongyouzk.top/Article/details/gt2abxsblzr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jianghu66.top/Article/details/gt2sognrrnc.html

[R08] 数值比较
来源：http://dali.daria6918.cn/Article/details/gt2jvgtejih.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yueranfly.top/Article/details/gt2lasgljec.html

[R09] 字符串比较
来源：http://dali.ehwqpu.com/Article/details/gt2oshztqmn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sysykeji.top/Article/details/gt2cvyweblg.html

[R10] 正则匹配
来源：http://dali.iojbl.cn/Article/details/gt2otjdxsls.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj202588.top/Article/details/gt2bwljpghz.html

[R11] case 多分支
来源：http://dali.ybcxt.top/Article/details/gt2oyncvdct.html

case "$1" in
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iwcnjvzc.html

start) echo "启动" ;;
来源：http://dali.sxryk.cn/Article/details/gt2uihqlrug.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjfppjr.html

*)     echo "未知命令" ;;
来源：http://dali.vqdsnc.cn/Article/details/gt2xhinkorf.html

esac
来源：http://dali.ydzc1.top/Article/details/gt2njobhult.html

[R12] for 遍历文件
来源：http://dali.andypj.xyz/Article/details/gt2tvnjlaml.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yanxiufei.cn/Article/details/gt2qyyxqcxp.html

[R13] for 计数循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2goaiubos.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gt2bgwboxky.html

[R14] C 风格 for
来源：http://dali.gotoacloud.top/Article/details/gt2yudqngrc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gt2singqjmh.html

[R15] while 逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gt2gzvgnlrj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2qodhiipu.html

[R16] until 等待条件
来源：http://dali.hysaishi.cn/Article/details/gt2ixsfzfsi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gt2opsguncg.html

[R17] 数组定义与取值
来源：http://dali.zhongyouzk.top/Article/details/gt2hzqiydyh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cucudq.cn/Article/details/gt2ldiavqhs.html

[R18] 遍历数组
来源：http://dali.jinqigfzy.top/Article/details/gt2pzycfrdf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2knctlssg.html

[R19] 数组长度
来源：http://dali.iojbl.cn/Article/details/gt2ihtkgkxp.html

echo "${#arr[@]}"
来源：http://dali.havefunace.top/Article/details/gt2xvsqsqnh.html

[R20] 关联数组（字典）
来源：http://dali.yvedp.cn/Article/details/gt2uhgorugy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgfzy.top/Article/details/gt2oiptfmfv.html

[R21] 字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2pxgyuatf.html

echo "${#s}"
来源：http://dali.xziqi.cn/Article/details/gt2bvwhmvmf.html

[R22] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gt2lmrwtlgn.html

echo "${s:0:5}"
来源：http://dali.jinqigfzy.top/Article/details/gt2sciphapa.html

[R23] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mushvejy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhoulong.xyz/Article/details/gt2isnddwkj.html

[R24] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gt2jsxkzzsm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj20258888.top/Article/details/gt2sblfirvj.html

[R25] 去后缀 / 去前缀
来源：http://dali.guannengcc.top/Article/details/gt2ahnyrtvn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.fengsongda.top/Article/details/gt2iqodlscd.html

[R26] 命令替换
来源：http://dali.daria6918.cn/Article/details/gt2zltgdggt.html

now=$(date +%F); echo "$now"
来源：http://dali.ehwqpu.com/Article/details/gt2xwfitfaw.html

[R27] 算术展开
来源：http://dali.chenjidiqi.icu/Article/details/gt2tuwcueby.html

echo $((1 + 2 * 3))
来源：http://dali.tian-w.cn/Article/details/gt2jtzhavgv.html

[R28] 浮点运算
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fqcxdzis.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinqigfzy.top/Article/details/gt2zhqagrmw.html

[R29] 定义函数
来源：http://dali.daxiang520.top/Article/details/gt2ibywjxqh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhixingplan.top/Article/details/gt2shycipib.html

[R30] 函数返回状态码
来源：http://dali.hammf.cn/Article/details/gt2uctyewqt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yonumen.top/Article/details/gt2bzjtuznr.html

[R31] 局部变量
来源：http://dali.yj202588.top/Article/details/gt2hpafssjc.html

f() { local x=1; echo "$x"; }
来源：http://dali.xuanzx.com/Article/details/gt2cxbzyizr.html

[R32] 参数个数校验
来源：http://dali.birdmap.top/Article/details/gt2xabnactw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gt2oxgayjik.html

[R33] 捕获错误并提示行号
来源：http://dali.chenzaomai.com/Article/details/gt2imnznqbi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guannengcc.top/Article/details/gt2mawzimdp.html

[R34] 退出时清理
来源：http://dali.cucudq.cn/Article/details/gt2hmltnios.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.fzhhl.top/Article/details/gt2wqwxdxar.html

[R35] 后台执行并等待
来源：http://dali.yongpay.top/Article/details/gt2qnwafroh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.bjfxy.top/Article/details/gt2yfsxeekr.html

[R36] 并发执行多个任务
来源：http://dali.chenzaomai.com/Article/details/gt2oajuzktn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnqzz.top/Article/details/gt2rvwvjzyq.html

[R37] 把输出赋给变量
来源：http://dali.aizwys.cn/Article/details/gt2idalrgwl.html

files=$(ls -1)
来源：http://dali.svipenyu.cn/Article/details/gt2dyreryto.html

[R38] 管道串联
来源：http://dali.cashguo.top/Article/details/gt2esvolcpx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shangyingyoupin.top/Article/details/gt2fpnsltzp.html

[R39] 重定向标准输出与错误
来源：http://dali.ivvv.top/Article/details/gt2ujhejigf.html

cmd > out.log 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gt2xxqrfdep.html

[R40] 追加写日志
来源：http://dali.sxryk.cn/Article/details/gt2jwzdyjuw.html

echo "log" >> out.log
来源：http://dali.yj202588.top/Article/details/gt2ewibpimg.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vffwvmrb.html

cmd >/dev/null 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gt2segfffqn.html

[R42] 输入重定向
来源：http://dali.ydzc1.top/Article/details/gt2lukhjqcn.html

wc -l < a.txt
来源：http://dali.dianchejie.cn/Article/details/gt2bbynpcxe.html

[R43] 按名字查找文件
来源：http://dali.xziqi.cn/Article/details/gt2uicvqtse.html

find . -name "*.log" -type f
来源：http://dali.sxryk.cn/Article/details/gt2xvrqfyln.html

[R44] 按修改时间查找
来源：http://dali.c1oappe.top/Article/details/gt2tdzeecoq.html

find . -mtime -7 -type f
来源：http://dali.yongpay.top/Article/details/gt2uwfqgjrv.html

[R45] 批量删除
来源：http://dali.nwbrower.top/Article/details/gt2zymomkyc.html

find . -name "*.tmp" -delete
来源：http://dali.gzhubu.top/Article/details/gt2rxzfsvml.html

[R46] 递归替换文件内容
来源：http://dali.jinqigfzy.top/Article/details/gt2eobkbxby.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.316326.xyz/Article/details/gt2yiilifil.html

[R47] sed 单行替换
来源：http://dali.vqdsnc.cn/Article/details/gt2xxeepmfb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2ndqqbcjc.html

[R48] awk 取指定列
来源：http://dali.xziqi.cn/Article/details/gt2zdnuwpci.html

awk '{print $1, $3}' a.txt
来源：http://dali.redwolf501.top/Article/details/gt2lpfvdjnm.html

[R49] awk 带条件
来源：http://dali.andypj.xyz/Article/details/gt2pmokpxje.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenlongwang.top/Article/details/gt2tuspyofo.html

[R50] awk 求和
来源：http://dali.316326.xyz/Article/details/gt2ykmwmddq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lbjjqksj.html

[R51] 排序去重取前几
来源：http://dali.tian-w.cn/Article/details/gt2eytencvp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cyjtoeps.html

[R52] 统计行数
来源：http://dali.bjfxy.top/Article/details/gt2izcjviol.html

wc -l a.txt
来源：http://dali.hnqzz.top/Article/details/gt2fjlgwkod.html

[R53] 查看文件头与实时尾
来源：http://dali.iojbl.cn/Article/details/gt2pvzbkjua.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ydzc1.top/Article/details/gt2blawgxvf.html

[R54] 比较两个文件
来源：http://dali.meibo888.top/Article/details/gt2kpvqydgr.html

diff a.txt b.txt
来源：http://dali.jqgfzy.top/Article/details/gt2wkquunhr.html

[R55] 压缩与解压
来源：http://dali.yonumen.top/Article/details/gt2mbdcpckv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rfdpqbua.html

[R56] 远程拷贝
来源：http://dali.jqgufenzy.top/Article/details/gt2lhnurnkm.html

scp file user@host:/path/
来源：http://dali.yueranfly.top/Article/details/gt2tizhgcmh.html

[R57] 远程执行命令
来源：http://dali.smart0.xyz/Article/details/gt2aldnuybb.html

ssh user@host 'uptime'
来源：http://dali.gotoacloud.top/Article/details/gt2dxshuphx.html

[R58] 下载文件
来源：http://dali.hnxiangtu.top/Article/details/gt2qmktdjtr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.daxiang520.top/Article/details/gt2tjhlxmhf.html

[R59] 发 POST JSON
来源：http://dali.xuetiantiany.cn/Article/details/gt2phnrmwog.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.316326.xyz/Article/details/gt2zgitsqwg.html

[R60] 只看 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gt2genzjnsa.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.guowangkeji.top/Article/details/gt2xywtjlmk.html

[R61] 磁盘占用
来源：http://dali.sweek.top/Article/details/gt2yzdrtoly.html

df -h;  du -sh *
来源：http://dali.nanxuanxn.top/Article/details/gt2hhtztook.html

[R62] 找最占空间的文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2teoiwovh.html

du -ah . | sort -rh | head -10
来源：http://dali.chenlongwang.top/Article/details/gt2ckaocbev.html

[R63] 内存与进程
来源：http://dali.mhx1999.top/Article/details/gt2tozrckek.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigufen.top/Article/details/gt2ylgorjct.html

[R64] 结束进程
来源：http://dali.dianchejie.cn/Article/details/gt2mobhqgft.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gaohongyu789.top/Article/details/gt2dougilfu.html

[R65] 查看端口占用
来源：http://dali.yongpay.top/Article/details/gt2mpgdftxe.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mcvcbeom.html

[R66] 定时任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bnxsgvro.html

crontab -e;  crontab -l
来源：http://dali.hywenlv.cn/Article/details/gt2vqcgzxhz.html

[R67] 生成随机十六进制串
来源：http://dali.snrcjt.cn/Article/details/gt2acawykng.html


<!-- 参考信息 -->