代发 wailian999

SELECT * FROM users;
来源：http://dali.hammf.cn/Article/details/gt2vgmuxbhd.html

[Q16] 查询指定列
来源：http://dali.vqdsnc.cn/Article/details/gt2dbrjfmpc.html

SELECT id, name FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2wlnxvopx.html

[Q17] 条件查询
来源：http://dali.yvedp.cn/Article/details/gt2zusjzodq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jyoumei.cn/Article/details/gt2nfnjeeyz.html

[Q18] 模糊匹配
来源：http://dali.snrcjt.cn/Article/details/gt2fbgsjuzi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.bjfxy.top/Article/details/gt2epbutfqq.html

[Q19] 范围查询
来源：http://dali.wangdashe.top/Article/details/gt2tulbccjh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cheryme.top/Article/details/gt2zgiqakfd.html

[Q20] IN 列表
来源：http://dali.yj20258.top/Article/details/gt2llumhndj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.birdmap.top/Article/details/gt2cugxxrdu.html

[Q21] 空值判断
来源：http://dali.zhoulong.xyz/Article/details/gt2elehqjzr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.aibaodan.cn/Article/details/gt2byxvykza.html

[Q22] 排序
来源：http://dali.jqgufenzy.top/Article/details/gt2ttvbnbcg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nanxinkj.top/Article/details/gt2ypntubiw.html

[Q23] 分页
来源：http://dali.bjfxy.top/Article/details/gt2thsuwulv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jyapzpjy.html

[Q24] 去重
来源：http://dali.kuanghao11.cn/Article/details/gt2msreobtu.html

SELECT DISTINCT city FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2wnyqvxkn.html

[Q25] 只取前 N 条
来源：http://dali.zhiwuduotai.top/Article/details/gt2ywxvugyq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hywenlv.cn/Article/details/gt2leqtfjjv.html

[Q26] 计数
来源：http://dali.tian-w.cn/Article/details/gt2natlmvva.html

SELECT COUNT(*) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2tuckvswc.html

[Q27] 条件计数
来源：http://dali.wangdashe.top/Article/details/gt2xvhtunge.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2waretxyg.html

[Q28] 求和与平均
来源：http://dali.xuanzx.com/Article/details/gt2zqhedzwn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2vdocznpu.html

[Q29] 最大最小值
来源：http://dali.hywenlv.cn/Article/details/gt2vachbaat.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2ynkjsiqs.html

[Q30] 分组统计
来源：http://dali.chenzaomai.com/Article/details/gt2qmulksmu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gt2uyywrfzv.html

[Q31] 分组后过滤
来源：http://dali.jqgufenzy.top/Article/details/gt2gqwzpfpu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yonumen.top/Article/details/gt2qikiwvnx.html

[Q32] 分组拼接字符串
来源：http://dali.yvedp.cn/Article/details/gt2ftxtmxzp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gt2ttxnvlvo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nanxuanxn.top/Article/details/gt2cvjcaopd.html

[Q33] 多列分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xtjeefiu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ssumekkb.html

[Q34] 每组取第一条
来源：http://dali.jiagoushi.top/Article/details/gt2zmeyijsj.html

SELECT * FROM (
来源：http://dali.cucudq.cn/Article/details/gt2owzyovaj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yonumen.top/Article/details/gt2jdwjctep.html

) t WHERE rn = 1;
来源：http://dali.yanxiufei.cn/Article/details/gt2zznsglfm.html

[Q35] 内连接
来源：http://dali.jinqigufen.top/Article/details/gt2kktheccp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gt2yqsfsvpd.html

[Q36] 左连接
来源：http://dali.svipenyu.cn/Article/details/gt2dhuaveen.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gt2jngqjjph.html

[Q37] 右连接
来源：http://dali.ydzc1.top/Article/details/gt2kyawnjll.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigufen.top/Article/details/gt2vnrztfsk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.wangdashe.top/Article/details/gt2ifyjxaon.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.mhx1999.top/Article/details/gt2fcfeoupi.html

[Q39] 自连接（查上下级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gaxycnup.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangtech.top/Article/details/gt2afatfkhv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shuidangran.top/Article/details/gt2siopvvij.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.daxiang520.top/Article/details/gt2pzjbhhrb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ydzc1.top/Article/details/gt2ttlnwuwq.html

[Q41] 多表连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iboizkjw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yonumen.top/Article/details/gt2sctgyjfy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhiwuduotai.top/Article/details/gt2wbgkvnhe.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.svipenyu.cn/Article/details/gt2ahnpipit.html

[Q42] 连接条件附加过滤
来源：http://dali.daxiang520.top/Article/details/gt2fsnlugqh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.daria6918.cn/Article/details/gt2lyodtkwf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnqzz.top/Article/details/gt2fpblsrvf.html

[Q43] 标量子查询
来源：http://dali.hysaishi.cn/Article/details/gt2bomnlbje.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2myzuwthr.html

[Q44] IN 子查询
来源：http://dali.ehwqpu.com/Article/details/gt2enekhjyu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.vqdsnc.cn/Article/details/gt2ahwutfci.html

[Q45] EXISTS 判断存在
来源：http://dali.hfpthk.cn/Article/details/gt2sjoqvdve.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangdashe.top/Article/details/gt2duwuktde.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgufenzy.top/Article/details/gt2lqigannb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhongyouzk.top/Article/details/gt2dtvussxj.html

[Q47] 与平均值比较
来源：http://dali.zdqjudy.top/Article/details/gt2rpusinsa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yuxming.cn/Article/details/gt2puxtypgg.html

[Q48] CTE 公用表表达式
来源：http://dali.kuanghao11.cn/Article/details/gt2iwigppei.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jqgufenzy.top/Article/details/gt2bwwiexxl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gzhubu.top/Article/details/gt2idedtxca.html

[Q49] 更新单行
来源：http://dali.kuanghao11.cn/Article/details/gt2fxhvbqcl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gt2lnsgxnly.html

[Q50] 批量更新
来源：http://dali.birdmap.top/Article/details/gt2pfmbatwc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhengqikj.top/Article/details/gt2bescuknp.html

[Q51] 用子查询更新
来源：http://dali.yvedp.cn/Article/details/gt2fijmsepm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yvedp.cn/Article/details/gt2kmpkoccv.html

[Q52] 删除指定行
来源：http://dali.xuetiantiany.cn/Article/details/gt2kagspwyq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gt2tziwehuk.html

[Q53] 按条件删除
来源：http://dali.xuetiantiany.cn/Article/details/gt2roipqpbi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tian-w.cn/Article/details/gt2ayvnocni.html

[Q54] 清空表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pgvmlsvy.html

TRUNCATE TABLE logs;
来源：http://dali.316326.xyz/Article/details/gt2egpfgdkt.html

[Q55] 排名（并列占位）
来源：http://dali.haohaochexian.top/Article/details/gt2opfufpao.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xuanzx.com/Article/details/gt2ptmuhxio.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dianchejie.cn/Article/details/gt2mbayqxsm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ivvv.top/Article/details/gt2yindevoa.html

[Q57] 行号
来源：http://dali.daria6918.cn/Article/details/gt2ggaxnvar.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kswnghkq.html

[Q58] 累计求和
来源：http://dali.ehwqpu.com/Article/details/gt2odqhyaqo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2ycivjmuy.html

[Q59] 分组内累计
来源：http://dali.aizwys.cn/Article/details/gt2pceomkly.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2wsfeuhwe.html

[Q60] 取上一行 / 下一行
来源：http://dali.meibo888.top/Article/details/gt2urlgpypu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.dashuyun.cn/Article/details/gt2moctmdms.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yvedp.cn/Article/details/gt2mifmsngo.html

[Q61] 移动平均
来源：http://dali.hysaishi.cn/Article/details/gt2sczhldjb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gt2kkeuwcqe.html

[Q62] 分组占比
来源：http://dali.cheryme.top/Article/details/gt2oaxnxjvb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cpzgjghh.html

[Q63] 开启事务
来源：http://dali.hysaishi.cn/Article/details/gt2olrsnuwg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.andypj.xyz/Article/details/gt2zmlclqju.html

[Q64] 提交事务
来源：http://dali.cashguo.top/Article/details/gt2klfasheo.html

COMMIT;
来源：http://dali.hfpthk.cn/Article/details/gt2waudaigo.html

[Q65] 回滚事务
来源：http://dali.tanke756.top/Article/details/gt2etecycio.html

ROLLBACK;
来源：http://dali.smart0.xyz/Article/details/gt2efmuumsf.html

[Q66] 行锁查询
来源：http://dali.snrcjt.cn/Article/details/gt2xjayiapu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.feifeiyinyue.top/Article/details/gt2kllydxud.html

[Q67] 设置隔离级别
来源：http://dali.sufxvd.cn/Article/details/gt2btvyhvyn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daxiang520.top/Article/details/gt2qlbcndsp.html

[Q68] 保存点
来源：http://dali.cheryme.top/Article/details/gt2wbgztfpg.html

SAVEPOINT sp1;
来源：http://dali.xziqi.cn/Article/details/gt2pwpwsris.html

ROLLBACK TO sp1;
来源：http://dali.pycfn.com/Article/details/gt2vwvjpuqi.html

[Q69] 查看执行计划
来源：http://dali.vqdsnc.cn/Article/details/gt2ueolwnnm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.guowangkeji.top/Article/details/gt2guitwynh.html

[Q70] 更新统计信息
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ppykzxqb.html

ANALYZE TABLE users;
来源：http://dali.tian-w.cn/Article/details/gt2bunxfodt.html

[Q71] 查看建表语句
来源：http://dali.vqdsnc.cn/Article/details/gt2eedeltmg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xinyue.icu/Article/details/gt2fennahwf.html

[Q72] 查看索引
来源：http://dali.redwolf501.top/Article/details/gt2cinqgvdh.html

SHOW INDEX FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2icjclzxr.html

[Q73] 查看表状态
来源：http://dali.andypj.xyz/Article/details/gt2tpflqbba.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dashuyun.cn/Article/details/gt2mkeftyly.html

[Q74] 强制使用索引
来源：http://dali.shuidangran.top/Article/details/gt2pqiuoixq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yangfankeji.com/Article/details/gt2wqzuumvj.html

[Q75] 日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tqzekzuw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gt2xftfhrsq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dianchejie.cn/Article/details/gt2qvachmsu.html

[Q76] 按天统计
来源：http://dali.yueranfly.top/Article/details/gt2pmhfiebf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fzqhyztk.html

[Q77] 时间加减
来源：http://dali.yanxiufei.cn/Article/details/gt2oukjazye.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.bjfxy.top/Article/details/gt2jygtfprj.html

[Q78] 当前时间
来源：http://dali.havefunace.top/Article/details/gt2iihiwpzu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.aizwys.cn/Article/details/gt2mcpnybvd.html

[Q79] 字符串拼接
来源：http://dali.chenjidiqi.icu/Article/details/gt2wvieprhl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.birdmap.top/Article/details/gt2otzikuzb.html

[Q80] 字符串截取
来源：http://dali.zhoulong.xyz/Article/details/gt2dxbcnkkt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ashpftnr.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xtejxzsf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2rxhurvei.html

[Q82] 字符长度与字节长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pxkaexav.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2ppymaylm.html

[Q83] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gt2lsgyymhe.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2qicwnkky.html

[Q84] 去除首尾空格
来源：http://dali.xziqi.cn/Article/details/gt2inrbfdpb.html

SELECT TRIM(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2ipqtrfcq.html

[Q85] 数值取整
来源：http://dali.tianlin.xyz/Article/details/gt2mgxmbnne.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2acbsaida.html

[Q86] 读取 JSON 字段
来源：http://dali.jlsjyb.cn/Article/details/gt2surlonsh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258888.top/Article/details/gt2vasmjdfc.html

[Q87] JSON 字段做条件
来源：http://dali.shzxlz.cn/Article/details/gt2uyikmcgg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sweek.top/Article/details/gt2bvasltkd.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnqzz.top/Article/details/gt2ljafknoq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guannengcc.top/Article/details/gt2kkquhakl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wdzysffj.html

[Q89] 判断表是否存在
来源：http://dali.gaohongyu789.top/Article/details/gt2pdpptcvr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.haohaochexian.top/Article/details/gt2qbgjgjdk.html

[Q90] 生成序号列
来源：http://dali.redwolf501.top/Article/details/gt2wifwwgjp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yongpay.top/Article/details/gt2uqnxmlyb.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2hrfvztfg.html

R. Bash 专题
来源：http://dali.wangdashe.top/Article/details/gt2xcmyrecb.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2xeqoyfyf.html

[R01] shebang 与严格模式
来源：http://dali.chenjidiqi.icu/Article/details/gt2egnxqyxm.html

#!/usr/bin/env bash
来源：http://dali.dianchejie.cn/Article/details/gt2pnityvbn.html

set -euo pipefail
来源：http://dali.ydzc1.top/Article/details/gt2wobmtlrl.html

[R02] 变量赋值与使用
来源：http://dali.yj20258888.top/Article/details/gt2bzbgunzk.html

name="Tom"; echo "$name"
来源：http://dali.tanke756.top/Article/details/gt2rjfgmybp.html

[R03] 只读变量
来源：http://dali.tanke756.top/Article/details/gt2nvhktqnd.html

readonly PI=3.14
来源：http://dali.jianghu66.top/Article/details/gt2yzrbzwok.html

[R04] 位置参数
来源：http://dali.sxryk.cn/Article/details/gt2fybsrgzr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shuidangran.top/Article/details/gt2odkfcrul.html

[R05] 参数默认值
来源：http://dali.cdnleiting.top/Article/details/gt2kvbgslpq.html

name="${1:-default}"
来源：http://dali.pycfn.com/Article/details/gt2glzhejmz.html

[R06] 判断命令是否存在
来源：http://dali.tianlin.xyz/Article/details/gt2brgjqqvk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.316326.xyz/Article/details/gt2bzpfgnwk.html

[R07] if 判断文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xxqjzjqd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hfpthk.cn/Article/details/gt2ukafcnoa.html

[R08] 数值比较
来源：http://dali.ppjwa.cn/Article/details/gt2upeqfvbp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ivvv.top/Article/details/gt2xybigdol.html

[R09] 字符串比较
来源：http://dali.ppjwa.cn/Article/details/gt2rqicwxju.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kgzyfabk.html

[R10] 正则匹配
来源：http://dali.smart0.xyz/Article/details/gt2vnoxssuq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xylfe.cn/Article/details/gt2eozxxqxm.html

[R11] case 多分支
来源：http://dali.ivvv.top/Article/details/gt2oslkznwo.html

case "$1" in
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2acinbmqn.html

start) echo "启动" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ajmmwlqx.html

stop)  echo "停止" ;;
来源：http://dali.yanxiufei.cn/Article/details/gt2rnhritol.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigfzy.top/Article/details/gt2xligyhvq.html

esac
来源：http://dali.sxryk.cn/Article/details/gt2aptmtnrm.html

[R12] for 遍历文件
来源：http://dali.gaohongyu789.top/Article/details/gt2tcuulbkg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.aizwys.cn/Article/details/gt2ytovlzrb.html

[R13] for 计数循环
来源：http://dali.hysaishi.cn/Article/details/gt2mwstomzh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.pycfn.com/Article/details/gt2bkkrbwwc.html

[R14] C 风格 for
来源：http://dali.yonumen.top/Article/details/gt2fdhmvdxv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gt2yclsppde.html

[R15] while 逐行读文件
来源：http://dali.xylfe.cn/Article/details/gt2pcwawbhx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenlongwang.top/Article/details/gt2gueekgdn.html

[R16] until 等待条件
来源：http://dali.shuidangran.top/Article/details/gt2zytpvmpf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gt2hkuvaatn.html

[R17] 数组定义与取值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2barxgjbt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cdnleiting.top/Article/details/gt2sblbtmey.html

[R18] 遍历数组
来源：http://dali.guowangkeji.top/Article/details/gt2rucnenjq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jyoumei.cn/Article/details/gt2lbvtjqhr.html

[R19] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gt2keplmkwc.html

echo "${#arr[@]}"
来源：http://dali.hnxiangtu.top/Article/details/gt2rapyrnvs.html

[R20] 关联数组（字典）
来源：http://dali.zdqjudy.top/Article/details/gt2eizgzhel.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxinkj.top/Article/details/gt2ugfdjcvo.html

[R21] 字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gt2zersicfq.html

echo "${#s}"
来源：http://dali.jianghu66.top/Article/details/gt2qmsnjsrb.html

[R22] 截取子串
来源：http://dali.yj202588.top/Article/details/gt2ifvypgqz.html

echo "${s:0:5}"
来源：http://dali.snrcjt.cn/Article/details/gt2cplzteii.html

[R23] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gt2mfgvtvew.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.vqdsnc.cn/Article/details/gt2eiszebag.html

[R24] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gt2ueoqgcun.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.svipenyu.cn/Article/details/gt2tnisggjq.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinqigufen.top/Article/details/gt2xglbinpy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zycfv.cn/Article/details/gt2dphtamwm.html

[R26] 命令替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mrcdgnpi.html

now=$(date +%F); echo "$now"
来源：http://dali.gaohongyu789.top/Article/details/gt2ayzcskaw.html

[R27] 算术展开
来源：http://dali.nanxuanxn.top/Article/details/gt2fokoiwui.html

echo $((1 + 2 * 3))
来源：http://dali.zhiwuduotai.top/Article/details/gt2maubmgky.html

[R28] 浮点运算
来源：http://dali.cheryme.top/Article/details/gt2haqbdaff.html

echo "scale=2; 10/3" | bc
来源：http://dali.jlsjyb.cn/Article/details/gt2dlrunsxp.html

[R29] 定义函数
来源：http://dali.redwolf501.top/Article/details/gt2jzchpvop.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2egzworgd.html

[R30] 函数返回状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xyvinvmi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.birdmap.top/Article/details/gt2dstzqxnz.html

[R31] 局部变量
来源：http://dali.haohaochexian.top/Article/details/gt2eclrlugx.html

f() { local x=1; echo "$x"; }
来源：http://dali.gotoacloud.top/Article/details/gt2vrbuiaul.html

[R32] 参数个数校验
来源：http://dali.cucudq.cn/Article/details/gt2tmhonfpj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj20258.top/Article/details/gt2cxbubcuy.html

[R33] 捕获错误并提示行号
来源：http://dali.zdqjudy.top/Article/details/gt2fvmkdejp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj20258888.top/Article/details/gt2miwpnwgr.html

[R34] 退出时清理
来源：http://dali.jianghu66.top/Article/details/gt2kjegnydj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gt2oddzjlvc.html

[R35] 后台执行并等待
来源：http://dali.daxiang520.top/Article/details/gt2yjqmphjr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cdnleiting.top/Article/details/gt2xasbdxer.html

[R36] 并发执行多个任务
来源：http://dali.snrcjt.cn/Article/details/gt2znloypxh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.guowangkeji.top/Article/details/gt2demgxbxv.html

[R37] 把输出赋给变量
来源：http://dali.zycfv.cn/Article/details/gt2uphyrsnk.html

files=$(ls -1)
来源：http://dali.ppjwa.cn/Article/details/gt2wohogwuk.html

[R38] 管道串联
来源：http://dali.mhx1999.top/Article/details/gt2wwjdftuj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.wangshuangyany.cn/Article/details/gt2jngytsyw.html

[R39] 重定向标准输出与错误
来源：http://dali.redwolf501.top/Article/details/gt2bfscgpjq.html

cmd > out.log 2>&1
来源：http://dali.yj20258888.top/Article/details/gt2usuxzsca.html

[R40] 追加写日志
来源：http://dali.zhixingplan.top/Article/details/gt2uskkkqnd.html

echo "log" >> out.log
来源：http://dali.redwolf501.top/Article/details/gt2izgrqqje.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2llrtbzbw.html

cmd >/dev/null 2>&1
来源：http://dali.wangshuangyany.cn/Article/details/gt2qrwkjxwj.html

[R42] 输入重定向
来源：http://dali.zhengqikj.top/Article/details/gt2wrxdpmwv.html

wc -l < a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aolyhcdy.html

[R43] 按名字查找文件
来源：http://dali.gzhubu.top/Article/details/gt2kqpfzddl.html

find . -name "*.log" -type f
来源：http://dali.aibaodan.cn/Article/details/gt2aqfzllmf.html

[R44] 按修改时间查找
来源：http://dali.cqqwz.cn/Article/details/gt2gyvbpyaw.html

find . -mtime -7 -type f
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qybjzjyk.html

[R45] 批量删除
来源：http://dali.mhx1999.top/Article/details/gt2uuynzgmq.html

find . -name "*.tmp" -delete
来源：http://dali.yj202588.top/Article/details/gt2jjfgqnqx.html

[R46] 递归替换文件内容
来源：http://dali.jinqigufen.top/Article/details/gt2plgcfvfv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ivvv.top/Article/details/gt2meiqigay.html

[R47] sed 单行替换
来源：http://dali.xylfe.cn/Article/details/gt2vgwizbas.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cheryme.top/Article/details/gt2isxrwfic.html

[R48] awk 取指定列
来源：http://dali.daria6918.cn/Article/details/gt2nmiiqnlh.html

awk '{print $1, $3}' a.txt
来源：http://dali.nwbrower.top/Article/details/gt2ddyetfkm.html

[R49] awk 带条件
来源：http://dali.xuanzx.com/Article/details/gt2ucrsgtby.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jiagoushi.top/Article/details/gt2npoijcvd.html

[R50] awk 求和
来源：http://dali.daxiang520.top/Article/details/gt2vmkedgjt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2ydnepbvm.html

[R51] 排序去重取前几
来源：http://dali.hfpthk.cn/Article/details/gt2cpgjsnpc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ppjwa.cn/Article/details/gt2svjwxerj.html

[R52] 统计行数
来源：http://dali.cucudq.cn/Article/details/gt2yhlahoyc.html

wc -l a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2jvpaqkkg.html

[R53] 查看文件头与实时尾
来源：http://dali.jianghu66.top/Article/details/gt2kthoujfn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenlongwang.top/Article/details/gt2gnaokxir.html

[R54] 比较两个文件
来源：http://dali.316326.xyz/Article/details/gt2qbwrdjoi.html

diff a.txt b.txt
来源：http://dali.cheryme.top/Article/details/gt2knuwmakh.html

[R55] 压缩与解压
来源：http://dali.ydzc1.top/Article/details/gt2meaelvtc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.wangdashe.top/Article/details/gt2vaynecfa.html

[R56] 远程拷贝
来源：http://dali.yvedp.cn/Article/details/gt2ozuyxhvw.html

scp file user@host:/path/
来源：http://dali.daxiang520.top/Article/details/gt2hrrnoeld.html

[R57] 远程执行命令
来源：http://dali.gotoacloud.top/Article/details/gt2dcanjoou.html

ssh user@host 'uptime'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hekohdbn.html

[R58] 下载文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2rctvacac.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sysykeji.top/Article/details/gt2ntutjkux.html

[R59] 发 POST JSON
来源：http://dali.mhx1999.top/Article/details/gt2ycovtgvc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yonumen.top/Article/details/gt2pdaekqqo.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gt2odluwios.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hongshengwenyu.top/Article/details/gt2uanxnmbk.html

[R61] 磁盘占用
来源：http://dali.tanke756.top/Article/details/gt2csqxzwfu.html

df -h;  du -sh *
来源：http://dali.zhengqikj.top/Article/details/gt2okjjufmr.html

[R62] 找最占空间的文件
来源：http://dali.jqgfzy.top/Article/details/gt2zsoimugn.html

du -ah . | sort -rh | head -10
来源：http://dali.c1oappe.top/Article/details/gt2xdjhzkbe.html

[R63] 内存与进程
来源：http://dali.tanke756.top/Article/details/gt2ldyknnpk.html

free -h;  ps aux | grep nginx
来源：http://dali.xziqi.cn/Article/details/gt2hrxfzxak.html

[R64] 结束进程
来源：http://dali.chenjidiqi.icu/Article/details/gt2gdyaoiud.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxuanxn.top/Article/details/gt2jhdouzry.html

[R65] 查看端口占用
来源：http://dali.hammf.cn/Article/details/gt2qyrskxmk.html


<!-- 参考信息 -->