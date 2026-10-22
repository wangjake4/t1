代发 wailian999

SELECT * FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2ppvjkxbx.html

[Q16] 查询指定列
来源：http://dali.dianchejie.cn/Article/details/gt2ujygtgsr.html

SELECT id, name FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2rfguuurm.html

[Q17] 条件查询
来源：http://dali.9152youxi.cn/Article/details/gt2qauwhxss.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yanxiufei.cn/Article/details/gt2upmszzud.html

[Q18] 模糊匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2kowxoyrg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.wangshuangyany.cn/Article/details/gt2xjxboapv.html

[Q19] 范围查询
来源：http://dali.9152youxi.cn/Article/details/gt2etgnxoiw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.daxiang520.top/Article/details/gt2yretvvle.html

[Q20] IN 列表
来源：http://dali.chenjidiqi.icu/Article/details/gt2khrzrxvs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shzxlz.cn/Article/details/gt2njbjrrqy.html

[Q21] 空值判断
来源：http://dali.xuetiantiany.cn/Article/details/gt2cisewkpg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yanxiufei.cn/Article/details/gt2pdkwbmot.html

[Q22] 排序
来源：http://dali.sweek.top/Article/details/gt2eyjjaygt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yuanzhike.top/Article/details/gt2xrujvhqh.html

[Q23] 分页
来源：http://dali.sufxvd.cn/Article/details/gt2lrrokeqp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuanzhike.top/Article/details/gt2cwgumwql.html

[Q24] 去重
来源：http://dali.cdnleiting.top/Article/details/gt2njjtujtx.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uelcqyho.html

[Q25] 只取前 N 条
来源：http://dali.jinqigufen.top/Article/details/gt2anppvwbe.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hywenlv.cn/Article/details/gt2wjejzbwr.html

[Q26] 计数
来源：http://dali.xuetiantiany.cn/Article/details/gt2ovqonohd.html

SELECT COUNT(*) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2usbakewd.html

[Q27] 条件计数
来源：http://dali.gogol.net.cn/Article/details/gt2cnxjfwoi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cheryme.top/Article/details/gt2spcvjpfi.html

[Q28] 求和与平均
来源：http://dali.hnqzz.top/Article/details/gt2aapaqqsk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gt2crrqwmnz.html

[Q29] 最大最小值
来源：http://dali.ybcxt.top/Article/details/gt2issknopl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2aqpjmsdg.html

[Q30] 分组统计
来源：http://dali.iojbl.cn/Article/details/gt2mpvwmxji.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gt2byerzvue.html

[Q31] 分组后过滤
来源：http://dali.zhixingplan.top/Article/details/gt2nmvtugkb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ybcxt.top/Article/details/gt2qpngdgti.html

[Q32] 分组拼接字符串
来源：http://dali.daxiang520.top/Article/details/gt2ossyjher.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vjfubroy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.quarkkingdee.top/Article/details/gt2ncqcyriq.html

[Q33] 多列分组
来源：http://dali.yj202588.top/Article/details/gt2fbmunfcj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenzaomai.com/Article/details/gt2inurzqwj.html

[Q34] 每组取第一条
来源：http://dali.hammf.cn/Article/details/gt2mysscsov.html

SELECT * FROM (
来源：http://dali.yonumen.top/Article/details/gt2mqlcseyd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zycfv.cn/Article/details/gt2qntmznwi.html

) t WHERE rn = 1;
来源：http://dali.birdmap.top/Article/details/gt2zqtaxegd.html

[Q35] 内连接
来源：http://dali.nanxuanxn.top/Article/details/gt2pviorzmx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gt2rhzzjzsx.html

[Q36] 左连接
来源：http://dali.yonumen.top/Article/details/gt2qazbpkqh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zdqjudy.top/Article/details/gt2npucsobb.html

[Q37] 右连接
来源：http://dali.redwolf501.top/Article/details/gt2volquuop.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cheryme.top/Article/details/gt2zydidgel.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yangfankeji.com/Article/details/gt2vqwpyies.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yangfankeji.com/Article/details/gt2khhjwhqk.html

[Q39] 自连接（查上下级）
来源：http://dali.jinqigufen.top/Article/details/gt2iflhrwjw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yonumen.top/Article/details/gt2eacxnxws.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xinyue.icu/Article/details/gt2vcmjzgle.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinqigfzy.top/Article/details/gt2esiwprsp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangshuangyany.cn/Article/details/gt2tibrpgle.html

[Q41] 多表连接
来源：http://dali.gaohongyu789.top/Article/details/gt2qvqqbsng.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.feifeiyinyue.top/Article/details/gt2sdqvgtst.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zdqjudy.top/Article/details/gt2ozyurttd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gotoacloud.top/Article/details/gt2ilpuzyea.html

[Q42] 连接条件附加过滤
来源：http://dali.havefunace.top/Article/details/gt2amxirwcf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.wangshuangyany.cn/Article/details/gt2hhluuzqv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zdqjudy.top/Article/details/gt2wekltrzi.html

[Q43] 标量子查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2rpdhhujo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shuidangran.top/Article/details/gt2ztfvmlmr.html

[Q44] IN 子查询
来源：http://dali.aizwys.cn/Article/details/gt2gzcsjdff.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gaohongyu789.top/Article/details/gt2vhghxhnu.html

[Q45] EXISTS 判断存在
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ejfcizmc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.c1oappe.top/Article/details/gt2jlrxnnqr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xinyue.icu/Article/details/gt2eefnucal.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.mhx1999.top/Article/details/gt2fldnniay.html

[Q47] 与平均值比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2dofiusfb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2njqlvreq.html

[Q48] CTE 公用表表达式
来源：http://dali.xuanzx.com/Article/details/gt2ttbaivkm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hysaishi.cn/Article/details/gt2toadecvj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yanxiufei.cn/Article/details/gt2nzvmvtob.html

[Q49] 更新单行
来源：http://dali.yangfankeji.com/Article/details/gt2oaevphos.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yuxming.cn/Article/details/gt2qpkjcblq.html

[Q50] 批量更新
来源：http://dali.xylfe.cn/Article/details/gt2kwifwvgq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.havefunace.top/Article/details/gt2qzmjcazp.html

[Q51] 用子查询更新
来源：http://dali.yj20258.top/Article/details/gt2zvpaesbl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rfxqwggm.html

[Q52] 删除指定行
来源：http://dali.gotoacloud.top/Article/details/gt2qdlwkajs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hysaishi.cn/Article/details/gt2gourmyrk.html

[Q53] 按条件删除
来源：http://dali.dashuyun.cn/Article/details/gt2lhcbrpxf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zycfv.cn/Article/details/gt2domlmmys.html

[Q54] 清空表
来源：http://dali.dianchejie.cn/Article/details/gt2ygkhnnja.html

TRUNCATE TABLE logs;
来源：http://dali.hongshengwenyu.top/Article/details/gt2rpjmvvfh.html

[Q55] 排名（并列占位）
来源：http://dali.ehwqpu.com/Article/details/gt2cjxdktcc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jianghu66.top/Article/details/gt2ivqllgzv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tanke756.top/Article/details/gt2btiypjje.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xziqi.cn/Article/details/gt2grrodllt.html

[Q57] 行号
来源：http://dali.snrcjt.cn/Article/details/gt2tdomxuax.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2ugxyxmdl.html

[Q58] 累计求和
来源：http://dali.yuanzhike.top/Article/details/gt2xjvsrzbr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gt2ruvqilfq.html

[Q59] 分组内累计
来源：http://dali.guannengcc.top/Article/details/gt2amgfkcwe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2ihklrelp.html

[Q60] 取上一行 / 下一行
来源：http://dali.jianghu66.top/Article/details/gt2sqdjlhnl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sufxvd.cn/Article/details/gt2adsexuje.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258.top/Article/details/gt2tregjjaq.html

[Q61] 移动平均
来源：http://dali.nwbrower.top/Article/details/gt2fikbnynj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2ebgxetlu.html

[Q62] 分组占比
来源：http://dali.jqgfzy.top/Article/details/gt2lhazhhzh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gt2buudopwy.html

[Q63] 开启事务
来源：http://dali.yongpay.top/Article/details/gt2ecnfkcnb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.smart0.xyz/Article/details/gt2czdunurt.html

[Q64] 提交事务
来源：http://dali.yongpay.top/Article/details/gt2mysfmqgp.html

COMMIT;
来源：http://dali.xziqi.cn/Article/details/gt2mdbmlnno.html

[Q65] 回滚事务
来源：http://dali.nanxinkj.top/Article/details/gt2qxnyhkdh.html

ROLLBACK;
来源：http://dali.ivvv.top/Article/details/gt2tbfycnfd.html

[Q66] 行锁查询
来源：http://dali.gzhubu.top/Article/details/gt2tfyujche.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sweek.top/Article/details/gt2yzcsvray.html

[Q67] 设置隔离级别
来源：http://dali.fzhhl.top/Article/details/gt2aedzgnou.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yueranfly.top/Article/details/gt2pfuoznbg.html

[Q68] 保存点
来源：http://dali.zycfv.cn/Article/details/gt2eryokhvq.html

SAVEPOINT sp1;
来源：http://dali.daxiang520.top/Article/details/gt2esbwyjqk.html

ROLLBACK TO sp1;
来源：http://dali.zhoulong.xyz/Article/details/gt2vzhufbik.html

[Q69] 查看执行计划
来源：http://dali.sxryk.cn/Article/details/gt2rubzetev.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.guannengcc.top/Article/details/gt2ndagjgns.html

[Q70] 更新统计信息
来源：http://dali.ybcxt.top/Article/details/gt2jpsrhuxx.html

ANALYZE TABLE users;
来源：http://dali.fengsongda.top/Article/details/gt2ejopbdra.html

[Q71] 查看建表语句
来源：http://dali.chenzaomai.com/Article/details/gt2unieurzw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jlsjyb.cn/Article/details/gt2emfkrpfu.html

[Q72] 查看索引
来源：http://dali.vqdsnc.cn/Article/details/gt2ewvaabrs.html

SHOW INDEX FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2egpwhrpb.html

[Q73] 查看表状态
来源：http://dali.haohaochexian.top/Article/details/gt2vqzjooub.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.daria6918.cn/Article/details/gt2zdfwsmxo.html

[Q74] 强制使用索引
来源：http://dali.xylfe.cn/Article/details/gt2nlfwqlwf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.birdmap.top/Article/details/gt2xgkwuyqt.html

[Q75] 日期格式化
来源：http://dali.cdnleiting.top/Article/details/gt2phtknnmh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2nmymxudl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shangyingyoupin.top/Article/details/gt2kqvpfhvr.html

[Q76] 按天统计
来源：http://dali.smart0.xyz/Article/details/gt2cqjjetxh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shuidangran.top/Article/details/gt2cfjuuhwt.html

[Q77] 时间加减
来源：http://dali.0kj1m.cn/Article/details/gt2eusrrofg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cqqwz.cn/Article/details/gt2kmlztvha.html

[Q78] 当前时间
来源：http://dali.yj20258.top/Article/details/gt2pxvyypba.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.kuanghao11.cn/Article/details/gt2rclgxvqd.html

[Q79] 字符串拼接
来源：http://dali.bjfxy.top/Article/details/gt2edhfifjp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.quarkkingdee.top/Article/details/gt2rcqjomsx.html

[Q80] 字符串截取
来源：http://dali.dashuyun.cn/Article/details/gt2pamxvjob.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2wsojurhz.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kmuzcqcp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2syqehxdt.html

[Q82] 字符长度与字节长度
来源：http://dali.ppjwa.cn/Article/details/gt2bylwapib.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2qewdemxq.html

[Q83] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gt2vylvzrym.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2jwqpjkaf.html

[Q84] 去除首尾空格
来源：http://dali.snrcjt.cn/Article/details/gt2gtegyokr.html

SELECT TRIM(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2jgningxd.html

[Q85] 数值取整
来源：http://dali.tianlin.xyz/Article/details/gt2ohmwghbh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.feifeiyinyue.top/Article/details/gt2jmebnvhx.html

[Q86] 读取 JSON 字段
来源：http://dali.chenzaomai.com/Article/details/gt2qjgahgtu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.smart0.xyz/Article/details/gt2ggtnrubv.html

[Q87] JSON 字段做条件
来源：http://dali.zhoulong.xyz/Article/details/gt2hmhvhwqn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.andypj.xyz/Article/details/gt2lfuytapg.html

[Q88] 行转列（条件聚合）
来源：http://dali.ybcxt.top/Article/details/gt2jkwwjqmp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yvedp.cn/Article/details/gt2eaeieopn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jiyvsonz.html

[Q89] 判断表是否存在
来源：http://dali.cqqwz.cn/Article/details/gt2bhdwlmay.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenzaomai.com/Article/details/gt2qqxuvogd.html

[Q90] 生成序号列
来源：http://dali.meibo888.top/Article/details/gt2odrjasyk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.mhx1999.top/Article/details/gt2qbwcmvow.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2wiavrtks.html

R. Bash 专题
来源：http://dali.mhx1999.top/Article/details/gt2fcnahcll.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2ctfknowb.html

[R01] shebang 与严格模式
来源：http://dali.xuanzx.com/Article/details/gt2limerhmj.html

#!/usr/bin/env bash
来源：http://dali.zhiwuduotai.top/Article/details/gt2rcbfyplz.html

set -euo pipefail
来源：http://dali.hysaishi.cn/Article/details/gt2xpsiytci.html

[R02] 变量赋值与使用
来源：http://dali.yj20258.top/Article/details/gt2bfmrbfsb.html

name="Tom"; echo "$name"
来源：http://dali.snrcjt.cn/Article/details/gt2tkdmcbct.html

[R03] 只读变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2nuezvkik.html

readonly PI=3.14
来源：http://dali.yangfankeji.com/Article/details/gt2logrmxmj.html

[R04] 位置参数
来源：http://dali.daria6918.cn/Article/details/gt2gmpduloj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxinkj.top/Article/details/gt2gqkywwvj.html

[R05] 参数默认值
来源：http://dali.cqqwz.cn/Article/details/gt2oyiewfjz.html

name="${1:-default}"
来源：http://dali.c1oappe.top/Article/details/gt2nmmahcsj.html

[R06] 判断命令是否存在
来源：http://dali.yanxiufei.cn/Article/details/gt2eojiwaen.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shuidangran.top/Article/details/gt2fpzyuoil.html

[R07] if 判断文件
来源：http://dali.zhengqikj.top/Article/details/gt2bdstotpv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zdqjudy.top/Article/details/gt2ppbzhchy.html

[R08] 数值比较
来源：http://dali.pycfn.com/Article/details/gt2mjurrjoj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dashuyun.cn/Article/details/gt2ooboyief.html

[R09] 字符串比较
来源：http://dali.xziqi.cn/Article/details/gt2faceyslp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2upbwsqnc.html

[R10] 正则匹配
来源：http://dali.guowangkeji.top/Article/details/gt2tnzfmbyq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cdnleiting.top/Article/details/gt2wzcgehzy.html

[R11] case 多分支
来源：http://dali.jqgfzy.top/Article/details/gt2lmpftcwn.html

case "$1" in
来源：http://dali.sufxvd.cn/Article/details/gt2phfqzfgi.html

start) echo "启动" ;;
来源：http://dali.hnxiangtu.top/Article/details/gt2hgshtzfx.html

stop)  echo "停止" ;;
来源：http://dali.gotoacloud.top/Article/details/gt2dhlcvevw.html

*)     echo "未知命令" ;;
来源：http://dali.mhx1999.top/Article/details/gt2cupzeevn.html

esac
来源：http://dali.xziqi.cn/Article/details/gt2nlgzommy.html

[R12] for 遍历文件
来源：http://dali.c1oappe.top/Article/details/gt2qsgcykgh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.andypj.xyz/Article/details/gt2jgifwfgl.html

[R13] for 计数循环
来源：http://dali.sysykeji.top/Article/details/gt2chdsgsaw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gt2zjakhmes.html

[R14] C 风格 for
来源：http://dali.jinghuilouyu.cn/Article/details/gt2parpmrxk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gt2bzgugxny.html

[R15] while 逐行读文件
来源：http://dali.gzhubu.top/Article/details/gt2givlurzd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangdashe.top/Article/details/gt2groyxjge.html

[R16] until 等待条件
来源：http://dali.tianlin.xyz/Article/details/gt2hcspzsxj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gt2ldnnyviy.html

[R17] 数组定义与取值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pqrbcmmj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nwbrower.top/Article/details/gt2kvqvorug.html

[R18] 遍历数组
来源：http://dali.ydzc1.top/Article/details/gt2qatkjpuj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2kgsupwwe.html

[R19] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gt2sjpxfird.html

echo "${#arr[@]}"
来源：http://dali.fengsongda.top/Article/details/gt2ypcgokwf.html

[R20] 关联数组（字典）
来源：http://dali.316326.xyz/Article/details/gt2bniqtkmv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daxiang520.top/Article/details/gt2fusyalvt.html

[R21] 字符串长度
来源：http://dali.zycfv.cn/Article/details/gt2pterthqc.html

echo "${#s}"
来源：http://dali.gotoacloud.top/Article/details/gt2ygytqkgh.html

[R22] 截取子串
来源：http://dali.quarkkingdee.top/Article/details/gt2hfybavum.html

echo "${s:0:5}"
来源：http://dali.0kj1m.cn/Article/details/gt2podlvsuj.html

[R23] 字符串替换
来源：http://dali.daxiang520.top/Article/details/gt2cziqpgjx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.9152youxi.cn/Article/details/gt2alxhtzbw.html

[R24] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gt2edhahbho.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigufen.top/Article/details/gt2ykgkopuk.html

[R25] 去后缀 / 去前缀
来源：http://dali.vqdsnc.cn/Article/details/gt2pbkxaxam.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhoulong.xyz/Article/details/gt2zbpkaord.html

[R26] 命令替换
来源：http://dali.mhx1999.top/Article/details/gt2orkwjnlj.html

now=$(date +%F); echo "$now"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cmsxgyjo.html

[R27] 算术展开
来源：http://dali.vqdsnc.cn/Article/details/gt2voywautv.html

echo $((1 + 2 * 3))
来源：http://dali.hnxiangtu.top/Article/details/gt2mqcyticw.html

[R28] 浮点运算
来源：http://dali.yj20258.top/Article/details/gt2mncwljbx.html

echo "scale=2; 10/3" | bc
来源：http://dali.cheryme.top/Article/details/gt2nbpgrbgo.html

[R29] 定义函数
来源：http://dali.smart0.xyz/Article/details/gt2lnluhoyh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2mjamktgy.html

[R30] 函数返回状态码
来源：http://dali.dashuyun.cn/Article/details/gt2cgnoujjm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigufen.top/Article/details/gt2jzqfoyuu.html

[R31] 局部变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2phssniue.html

f() { local x=1; echo "$x"; }
来源：http://dali.tianlin.xyz/Article/details/gt2btkhrpne.html

[R32] 参数个数校验
来源：http://dali.birdmap.top/Article/details/gt2asxcqkub.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gt2gjhkzxgn.html

[R33] 捕获错误并提示行号
来源：http://dali.quarkkingdee.top/Article/details/gt2uofsilpo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.daxiang520.top/Article/details/gt2wixtwwvh.html

[R34] 退出时清理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mhvomtom.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gt2drlofvxq.html

[R35] 后台执行并等待
来源：http://dali.dianchejie.cn/Article/details/gt2rpunbppz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cdnleiting.top/Article/details/gt2nrlkllym.html

[R36] 并发执行多个任务
来源：http://dali.shzxlz.cn/Article/details/gt2isbxbwzs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gogol.net.cn/Article/details/gt2roermqwh.html

[R37] 把输出赋给变量
来源：http://dali.chenzaomai.com/Article/details/gt2mwlnlvnl.html

files=$(ls -1)
来源：http://dali.shuidangran.top/Article/details/gt2fdyhdbmf.html

[R38] 管道串联
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gablggkk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgfzy.top/Article/details/gt2tkrignge.html

[R39] 重定向标准输出与错误
来源：http://dali.hywenlv.cn/Article/details/gt2otpvckke.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zlcdodtx.html

[R40] 追加写日志
来源：http://dali.cdnleiting.top/Article/details/gt2utvoeunf.html

echo "log" >> out.log
来源：http://dali.wangshuangyany.cn/Article/details/gt2ixjmjrlz.html

[R41] 丢弃输出
来源：http://dali.mhx1999.top/Article/details/gt2bgdnvvyh.html

cmd >/dev/null 2>&1
来源：http://dali.hammf.cn/Article/details/gt2vdamcrja.html

[R42] 输入重定向
来源：http://dali.jiagoushi.top/Article/details/gt2gmaxpboc.html

wc -l < a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uxsylqnx.html

[R43] 按名字查找文件
来源：http://dali.zhengqikj.top/Article/details/gt2qxnidwmj.html

find . -name "*.log" -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xxidielz.html

[R44] 按修改时间查找
来源：http://dali.sxryk.cn/Article/details/gt2hmqopute.html

find . -mtime -7 -type f
来源：http://dali.hysaishi.cn/Article/details/gt2cqzbtduf.html

[R45] 批量删除
来源：http://dali.tianlin.xyz/Article/details/gt2izwpnsiz.html

find . -name "*.tmp" -delete
来源：http://dali.chenzaomai.com/Article/details/gt2gplgoufi.html

[R46] 递归替换文件内容
来源：http://dali.xinyue.icu/Article/details/gt2zcdhsziv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jyoumei.cn/Article/details/gt2opfqoblx.html

[R47] sed 单行替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uoflkthv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sxryk.cn/Article/details/gt2wcwmbctc.html

[R48] awk 取指定列
来源：http://dali.chenzaomai.com/Article/details/gt2epiypbvm.html

awk '{print $1, $3}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2wmmapbze.html

[R49] awk 带条件
来源：http://dali.yanxiufei.cn/Article/details/gt2iojtcsgt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hysaishi.cn/Article/details/gt2xjiqgopk.html

[R50] awk 求和
来源：http://dali.hnqzz.top/Article/details/gt2bmhfiact.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yvedp.cn/Article/details/gt2hzxqavyl.html

[R51] 排序去重取前几
来源：http://dali.haohaochexian.top/Article/details/gt2intgxquj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuanzhike.top/Article/details/gt2nbdfvpvw.html

[R52] 统计行数
来源：http://dali.andypj.xyz/Article/details/gt2yawosqdt.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgkakyn.html

[R53] 查看文件头与实时尾
来源：http://dali.yueranfly.top/Article/details/gt2tqiohszs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenzaomai.com/Article/details/gt2hkejjdhf.html

[R54] 比较两个文件
来源：http://dali.iojbl.cn/Article/details/gt2bepwztjb.html

diff a.txt b.txt
来源：http://dali.cheryme.top/Article/details/gt2maissadv.html

[R55] 压缩与解压
来源：http://dali.cashguo.top/Article/details/gt2cejoeesl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yueranfly.top/Article/details/gt2ziklrwky.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlspemg.html

scp file user@host:/path/
来源：http://dali.mhx1999.top/Article/details/gt2bqjbhcyp.html

[R57] 远程执行命令
来源：http://dali.ppjwa.cn/Article/details/gt2yrffunnf.html

ssh user@host 'uptime'
来源：http://dali.dianchejie.cn/Article/details/gt2ncolphgy.html

[R58] 下载文件
来源：http://dali.birdmap.top/Article/details/gt2bqfmwyup.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hywenlv.cn/Article/details/gt2agemjftv.html

[R59] 发 POST JSON
来源：http://dali.yj20258888.top/Article/details/gt2xqhydaku.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yongpay.top/Article/details/gt2gwaelwso.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gt2xbirvnlx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.mhx1999.top/Article/details/gt2arfyuuvw.html

[R61] 磁盘占用
来源：http://dali.wangdashe.top/Article/details/gt2zvtqlrpt.html

df -h;  du -sh *
来源：http://dali.feifeiyinyue.top/Article/details/gt2sdrkmpwn.html

[R62] 找最占空间的文件
来源：http://dali.birdmap.top/Article/details/gt2ageyuzdx.html

du -ah . | sort -rh | head -10
来源：http://dali.shzxlz.cn/Article/details/gt2mjmzjubu.html

[R63] 内存与进程
来源：http://dali.hfpthk.cn/Article/details/gt2dcdzxror.html

free -h;  ps aux | grep nginx
来源：http://dali.daxiang520.top/Article/details/gt2ueajlifu.html

[R64] 结束进程
来源：http://dali.aibaodan.cn/Article/details/gt2cywdaeqn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.birdmap.top/Article/details/gt2ybszquzy.html

[R65] 查看端口占用
来源：http://dali.guowangkeji.top/Article/details/gt2idnstguy.html


<!-- 参考信息 -->