代发 wailian999

SELECT * FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2qesffcaj.html

[Q16] 查询指定列
来源：http://dali.xuetiantiany.cn/Article/details/gt2vgvybhgw.html

SELECT id, name FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2yebdricf.html

[Q17] 条件查询
来源：http://dali.gzhubu.top/Article/details/gt2ersxwfhw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.316326.xyz/Article/details/gt2hfdmttps.html

[Q18] 模糊匹配
来源：http://dali.daxiang520.top/Article/details/gt2uzzpsthh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj20258888.top/Article/details/gt2lfeoqhuz.html

[Q19] 范围查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yvcbqzgd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shzxlz.cn/Article/details/gt2ovdeuxal.html

[Q20] IN 列表
来源：http://dali.0kj1m.cn/Article/details/gt2jwoquaof.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sysykeji.top/Article/details/gt2gyccabwz.html

[Q21] 空值判断
来源：http://dali.jqgufenzy.top/Article/details/gt2ejgklufu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinqigufen.top/Article/details/gt2rktvmjbt.html

[Q22] 排序
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uomoqejn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.daxiang520.top/Article/details/gt2uxqylzbk.html

[Q23] 分页
来源：http://dali.gotoacloud.top/Article/details/gt2ntywqfdc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.fzhhl.top/Article/details/gt2pqeqxkhh.html

[Q24] 去重
来源：http://dali.bjfxy.top/Article/details/gt2ddtnmybq.html

SELECT DISTINCT city FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2tadovqif.html

[Q25] 只取前 N 条
来源：http://dali.birdmap.top/Article/details/gt2njihzsbk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj202588.top/Article/details/gt2rapiakzm.html

[Q26] 计数
来源：http://dali.fzhhl.top/Article/details/gt2yiyraysd.html

SELECT COUNT(*) FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2gsqpoxah.html

[Q27] 条件计数
来源：http://dali.hnqzz.top/Article/details/gt2kzcjajgp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2cfldkxqy.html

[Q28] 求和与平均
来源：http://dali.zhongyouzk.top/Article/details/gt2axsryakc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gt2zifkahzz.html

[Q29] 最大最小值
来源：http://dali.cheryme.top/Article/details/gt2olutytzn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2engajfwy.html

[Q30] 分组统计
来源：http://dali.bjfxy.top/Article/details/gt2bliumvjl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gt2glpbznsk.html

[Q31] 分组后过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tweecxjx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xreyrhfs.html

[Q32] 分组拼接字符串
来源：http://dali.nwbrower.top/Article/details/gt2brzehemt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gt2xcjrdhwi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ehwqpu.com/Article/details/gt2atjcppeu.html

[Q33] 多列分组
来源：http://dali.shuidangran.top/Article/details/gt2ofggsdro.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2seuhjgsj.html

[Q34] 每组取第一条
来源：http://dali.zhoulong.xyz/Article/details/gt2oqevgzoo.html

SELECT * FROM (
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iexebdpl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tianlin.xyz/Article/details/gt2lcmtoewi.html

) t WHERE rn = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2ktyspwyf.html

[Q35] 内连接
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ktckbkjw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.guowangkeji.top/Article/details/gt2rnnljmwg.html

[Q36] 左连接
来源：http://dali.sxryk.cn/Article/details/gt2ctogvikd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.pycfn.com/Article/details/gt2gycfksdf.html

[Q37] 右连接
来源：http://dali.tianlin.xyz/Article/details/gt2acmuhswg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.aibaodan.cn/Article/details/gt2yofwwavy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aizwys.cn/Article/details/gt2cuoihygb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.birdmap.top/Article/details/gt2vwmugocr.html

[Q39] 自连接（查上下级）
来源：http://dali.jianghu66.top/Article/details/gt2imyxisos.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgufenzy.top/Article/details/gt2bdywzzxe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cqqwz.cn/Article/details/gt2iukiqckt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yangfankeji.com/Article/details/gt2ndzsbtxk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jlsjyb.cn/Article/details/gt2nyhrwdcz.html

[Q41] 多表连接
来源：http://dali.fengsongda.top/Article/details/gt2raqtzmxm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.haohaochexian.top/Article/details/gt2nodqbuwr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.haohaochexian.top/Article/details/gt2zuwdchsf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hysaishi.cn/Article/details/gt2qcwroanh.html

[Q42] 连接条件附加过滤
来源：http://dali.xuetiantiany.cn/Article/details/gt2xbllorew.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigufen.top/Article/details/gt2myitqgxv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gaohongyu789.top/Article/details/gt2mfyxohgs.html

[Q43] 标量子查询
来源：http://dali.smart0.xyz/Article/details/gt2fancqyew.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aibaodan.cn/Article/details/gt2wjlwyrfe.html

[Q44] IN 子查询
来源：http://dali.gotoacloud.top/Article/details/gt2mkastroy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xylfe.cn/Article/details/gt2qcbjdadi.html

[Q45] EXISTS 判断存在
来源：http://dali.gogol.net.cn/Article/details/gt2myqsxmia.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ydzc1.top/Article/details/gt2bemimscq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.aizwys.cn/Article/details/gt2yxltkhju.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tzcysgjh.html

[Q47] 与平均值比较
来源：http://dali.aizwys.cn/Article/details/gt2euzvozsp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yuanzhike.top/Article/details/gt2faaayrui.html

[Q48] CTE 公用表表达式
来源：http://dali.nanxinkj.top/Article/details/gt2tgadzgwd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shuidangran.top/Article/details/gt2aeagmgdl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shangyingyoupin.top/Article/details/gt2pxtgcqky.html

[Q49] 更新单行
来源：http://dali.ivvv.top/Article/details/gt2flfwakse.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.0kj1m.cn/Article/details/gt2ndlkemfv.html

[Q50] 批量更新
来源：http://dali.yj202588.top/Article/details/gt2zmqoojko.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.wangdashe.top/Article/details/gt2wpchjdpd.html

[Q51] 用子查询更新
来源：http://dali.zhongyouzk.top/Article/details/gt2oelbrvpl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinqigfzy.top/Article/details/gt2qkkfwztr.html

[Q52] 删除指定行
来源：http://dali.shangyingyoupin.top/Article/details/gt2zpfqmbbq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gt2ckkvbjqq.html

[Q53] 按条件删除
来源：http://dali.vqdsnc.cn/Article/details/gt2rpqxapwp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.andypj.xyz/Article/details/gt2ztvykjia.html

[Q54] 清空表
来源：http://dali.jlsjyb.cn/Article/details/gt2ngpfudpi.html

TRUNCATE TABLE logs;
来源：http://dali.sweek.top/Article/details/gt2fwdcoyrl.html

[Q55] 排名（并列占位）
来源：http://dali.dianchejie.cn/Article/details/gt2quezzpoh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gt2aybvdtic.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ydzc1.top/Article/details/gt2hezynipi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yueranfly.top/Article/details/gt2ztryssee.html

[Q57] 行号
来源：http://dali.yuxming.cn/Article/details/gt2lkdyaayz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2dsmtbaoj.html

[Q58] 累计求和
来源：http://dali.zhengqikj.top/Article/details/gt2wxjwmzlf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2tetiyhcp.html

[Q59] 分组内累计
来源：http://dali.yanxiufei.cn/Article/details/gt2xsigoazm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gt2kyefgupc.html

[Q60] 取上一行 / 下一行
来源：http://dali.tanke756.top/Article/details/gt2usfujrkf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hywenlv.cn/Article/details/gt2wybgmzma.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2fkateyov.html

[Q61] 移动平均
来源：http://dali.smart0.xyz/Article/details/gt2prvmlvfc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2jlooyhyf.html

[Q62] 分组占比
来源：http://dali.pycfn.com/Article/details/gt2ibgmioph.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gt2xjvtidlk.html

[Q63] 开启事务
来源：http://dali.yongpay.top/Article/details/gt2kpttxehv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gotoacloud.top/Article/details/gt2urnwkopr.html

[Q64] 提交事务
来源：http://dali.cashguo.top/Article/details/gt2wjwcwrmi.html

COMMIT;
来源：http://dali.birdmap.top/Article/details/gt2tctmhmua.html

[Q65] 回滚事务
来源：http://dali.jyoumei.cn/Article/details/gt2lbpojgya.html

ROLLBACK;
来源：http://dali.yj20258.top/Article/details/gt2iqaoajgf.html

[Q66] 行锁查询
来源：http://dali.cheryme.top/Article/details/gt2lordifww.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2shxdejjj.html

[Q67] 设置隔离级别
来源：http://dali.gaohongyu789.top/Article/details/gt2dorfvxhd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xziqi.cn/Article/details/gt2btejygqa.html

[Q68] 保存点
来源：http://dali.cqqwz.cn/Article/details/gt2gbdugqsf.html

SAVEPOINT sp1;
来源：http://dali.xinyue.icu/Article/details/gt2zbydfzeb.html

ROLLBACK TO sp1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2tepyxmka.html

[Q69] 查看执行计划
来源：http://dali.yj20258.top/Article/details/gt2ogolawqo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.svipenyu.cn/Article/details/gt2xvihehnz.html

[Q70] 更新统计信息
来源：http://dali.cashguo.top/Article/details/gt2rladnikx.html

ANALYZE TABLE users;
来源：http://dali.jqgufenzy.top/Article/details/gt2umbngvdj.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ldadznsn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hnxiangtu.top/Article/details/gt2lulhtqbw.html

[Q72] 查看索引
来源：http://dali.nwbrower.top/Article/details/gt2cehflxga.html

SHOW INDEX FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2zeczetmx.html

[Q73] 查看表状态
来源：http://dali.jlsjyb.cn/Article/details/gt2ychwoneu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jlsjyb.cn/Article/details/gt2bwnsvzta.html

[Q74] 强制使用索引
来源：http://dali.nanxuanxn.top/Article/details/gt2vrbhsovu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jiagoushi.top/Article/details/gt2ggettcxa.html

[Q75] 日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nuvxwzkz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gt2kcarmfzf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.snrcjt.cn/Article/details/gt2rbizzphq.html

[Q76] 按天统计
来源：http://dali.jinqigufen.top/Article/details/gt2nampamvv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hongshengwenyu.top/Article/details/gt2jgpklxlr.html

[Q77] 时间加减
来源：http://dali.zhengqikj.top/Article/details/gt2pjgyuaxt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.feifeiyinyue.top/Article/details/gt2vlffdtnq.html

[Q78] 当前时间
来源：http://dali.sxryk.cn/Article/details/gt2xuufgfmw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zdqjudy.top/Article/details/gt2jnrqczjn.html

[Q79] 字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nozynzum.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.316326.xyz/Article/details/gt2nhlwpwht.html

[Q80] 字符串截取
来源：http://dali.yj202588.top/Article/details/gt2dfqiynlh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2hlhvuwtg.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhnxkgv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ajjxdfug.html

[Q82] 字符长度与字节长度
来源：http://dali.nanxuanxn.top/Article/details/gt2pmztjjjs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2wmnjrswj.html

[Q83] 大小写转换
来源：http://dali.vqdsnc.cn/Article/details/gt2zpebxchs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2gytfcria.html

[Q84] 去除首尾空格
来源：http://dali.wangdashe.top/Article/details/gt2utpljymg.html

SELECT TRIM(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2gcxevrho.html

[Q85] 数值取整
来源：http://dali.daxiang520.top/Article/details/gt2hxuenpfm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jendxfal.html

[Q86] 读取 JSON 字段
来源：http://dali.sweek.top/Article/details/gt2onxalpbr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhongyouzk.top/Article/details/gt2zjntzqud.html

[Q87] JSON 字段做条件
来源：http://dali.xylfe.cn/Article/details/gt2ancjqooh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xuanzx.com/Article/details/gt2jmfgomzn.html

[Q88] 行转列（条件聚合）
来源：http://dali.shangyingyoupin.top/Article/details/gt2sofezdgl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cucudq.cn/Article/details/gt2wrivlqvc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2srplssvl.html

[Q89] 判断表是否存在
来源：http://dali.gotoacloud.top/Article/details/gt2hwiottyg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jqabjivm.html

[Q90] 生成序号列
来源：http://dali.cheryme.top/Article/details/gt2vxqhjlou.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gaohongyu789.top/Article/details/gt2vhtpjscd.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2oruoerso.html

R. Bash 专题
来源：http://dali.gogol.net.cn/Article/details/gt2jncmjvol.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2mobokdly.html

[R01] shebang 与严格模式
来源：http://dali.cucudq.cn/Article/details/gt2ynsdrtkf.html

#!/usr/bin/env bash
来源：http://dali.feifeiyinyue.top/Article/details/gt2trpyyvgj.html

set -euo pipefail
来源：http://dali.cashguo.top/Article/details/gt2qxeakigt.html

[R02] 变量赋值与使用
来源：http://dali.chenjidiqi.icu/Article/details/gt2qnzpbgqn.html

name="Tom"; echo "$name"
来源：http://dali.gzhubu.top/Article/details/gt2rrddxmam.html

[R03] 只读变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2lliwsazh.html

readonly PI=3.14
来源：http://dali.cqqwz.cn/Article/details/gt2mrniqsxb.html

[R04] 位置参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vkybbtaw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuxming.cn/Article/details/gt2owaheltn.html

[R05] 参数默认值
来源：http://dali.bjfxy.top/Article/details/gt2qqnsslrd.html

name="${1:-default}"
来源：http://dali.yanxiufei.cn/Article/details/gt2vinknuhm.html

[R06] 判断命令是否存在
来源：http://dali.0kj1m.cn/Article/details/gt2xplveczf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gt2wtchosgq.html

[R07] if 判断文件
来源：http://dali.sweek.top/Article/details/gt2gtnnyeal.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj20258.top/Article/details/gt2ibdmptpe.html

[R08] 数值比较
来源：http://dali.aibaodan.cn/Article/details/gt2jmsyursh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnqzz.top/Article/details/gt2vulhixat.html

[R09] 字符串比较
来源：http://dali.chenlongwang.top/Article/details/gt2tmomypdk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuanzx.com/Article/details/gt2rfjwvnni.html

[R10] 正则匹配
来源：http://dali.jinqigufen.top/Article/details/gt2badcncdg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fengsongda.top/Article/details/gt2qqcutarj.html

[R11] case 多分支
来源：http://dali.svipenyu.cn/Article/details/gt2fnjugnsf.html

case "$1" in
来源：http://dali.zhixingplan.top/Article/details/gt2yijvkxxi.html

start) echo "启动" ;;
来源：http://dali.cdnleiting.top/Article/details/gt2xxjnpnoa.html

stop)  echo "停止" ;;
来源：http://dali.jlsjyb.cn/Article/details/gt2iikbvjfk.html

*)     echo "未知命令" ;;
来源：http://dali.zhongyouzk.top/Article/details/gt2mufemqzu.html

esac
来源：http://dali.yj202588.top/Article/details/gt2vhfqkpze.html

[R12] for 遍历文件
来源：http://dali.fzhhl.top/Article/details/gt2fxrlzdqp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cucudq.cn/Article/details/gt2tgfguzjz.html

[R13] for 计数循环
来源：http://dali.dashuyun.cn/Article/details/gt2omcsckuu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gt2yzhfuwkc.html

[R14] C 风格 for
来源：http://dali.vqdsnc.cn/Article/details/gt2tgksefnm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.iojbl.cn/Article/details/gt2gqmgannl.html

[R15] while 逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gt2kyyeehoh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shuidangran.top/Article/details/gt2ogckktyv.html

[R16] until 等待条件
来源：http://dali.ppjwa.cn/Article/details/gt2iwaekgfj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gt2sqyhmwfi.html

[R17] 数组定义与取值
来源：http://dali.aizwys.cn/Article/details/gt2odemclse.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.guannengcc.top/Article/details/gt2klqxerfj.html

[R18] 遍历数组
来源：http://dali.dianchejie.cn/Article/details/gt2ycenbbbh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jqgfzy.top/Article/details/gt2hwuahqei.html

[R19] 数组长度
来源：http://dali.0kj1m.cn/Article/details/gt2zjvamaqp.html

echo "${#arr[@]}"
来源：http://dali.zdqjudy.top/Article/details/gt2xpirwaob.html

[R20] 关联数组（字典）
来源：http://dali.iojbl.cn/Article/details/gt2hfbfugab.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2ftmgtudm.html

[R21] 字符串长度
来源：http://dali.smart0.xyz/Article/details/gt2ppwhelqi.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aeazwruk.html

[R22] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gt2hjkwxblp.html

echo "${s:0:5}"
来源：http://dali.gaohongyu789.top/Article/details/gt2ndylyixr.html

[R23] 字符串替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bleicpdk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuanzx.com/Article/details/gt2gzpdjncm.html

[R24] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gt2mlvrypdv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.birdmap.top/Article/details/gt2lmjmfyzu.html

[R25] 去后缀 / 去前缀
来源：http://dali.sufxvd.cn/Article/details/gt2cfvxmbnh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gghvmbke.html

[R26] 命令替换
来源：http://dali.svipenyu.cn/Article/details/gt2cmtejprj.html

now=$(date +%F); echo "$now"
来源：http://dali.wangshuangyany.cn/Article/details/gt2ckrtoooc.html

[R27] 算术展开
来源：http://dali.wangshuangyany.cn/Article/details/gt2segbmtpp.html

echo $((1 + 2 * 3))
来源：http://dali.tanke756.top/Article/details/gt2gymduzna.html

[R28] 浮点运算
来源：http://dali.yj20258.top/Article/details/gt2whqwsqgn.html

echo "scale=2; 10/3" | bc
来源：http://dali.ivvv.top/Article/details/gt2cxftmlcw.html

[R29] 定义函数
来源：http://dali.gzhubu.top/Article/details/gt2dmfqhkbz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hammf.cn/Article/details/gt2bqdhodiq.html

[R30] 函数返回状态码
来源：http://dali.cucudq.cn/Article/details/gt2qdwofzmd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhiwuduotai.top/Article/details/gt2jlsbncqa.html

[R31] 局部变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2gcmelbdg.html

f() { local x=1; echo "$x"; }
来源：http://dali.yvedp.cn/Article/details/gt2tttobkqn.html

[R32] 参数个数校验
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pppdcaof.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ydzc1.top/Article/details/gt2bpxkndmy.html

[R33] 捕获错误并提示行号
来源：http://dali.316326.xyz/Article/details/gt2lhtgsmdo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xylfe.cn/Article/details/gt2efjsujyy.html

[R34] 退出时清理
来源：http://dali.hnqzz.top/Article/details/gt2fzgiyjmp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hysaishi.cn/Article/details/gt2yitozqob.html

[R35] 后台执行并等待
来源：http://dali.sweek.top/Article/details/gt2teojtveu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yueranfly.top/Article/details/gt2isrfymvl.html

[R36] 并发执行多个任务
来源：http://dali.pycfn.com/Article/details/gt2xbpjhdfa.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hammf.cn/Article/details/gt2kdllfqvj.html

[R37] 把输出赋给变量
来源：http://dali.snrcjt.cn/Article/details/gt2acpniqfu.html

files=$(ls -1)
来源：http://dali.vqdsnc.cn/Article/details/gt2egnhddmq.html

[R38] 管道串联
来源：http://dali.gogol.net.cn/Article/details/gt2deuoxzfh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xinyue.icu/Article/details/gt2ddcaogcq.html

[R39] 重定向标准输出与错误
来源：http://dali.xuetiantiany.cn/Article/details/gt2lnjfzchn.html

cmd > out.log 2>&1
来源：http://dali.xziqi.cn/Article/details/gt2obppreef.html

[R40] 追加写日志
来源：http://dali.cashguo.top/Article/details/gt2doynwlcz.html

echo "log" >> out.log
来源：http://dali.birdmap.top/Article/details/gt2ibpfdbqr.html

[R41] 丢弃输出
来源：http://dali.ppjwa.cn/Article/details/gt2oifangga.html

cmd >/dev/null 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gt2eftevlms.html

[R42] 输入重定向
来源：http://dali.guowangkeji.top/Article/details/gt2fsxykvnb.html

wc -l < a.txt
来源：http://dali.birdmap.top/Article/details/gt2hjaoggbv.html

[R43] 按名字查找文件
来源：http://dali.vqdsnc.cn/Article/details/gt2exdotnqz.html

find . -name "*.log" -type f
来源：http://dali.chenlongwang.top/Article/details/gt2algidyhr.html

[R44] 按修改时间查找
来源：http://dali.yj202588.top/Article/details/gt2abdznilt.html

find . -mtime -7 -type f
来源：http://dali.ydzc1.top/Article/details/gt2tzihpyiy.html

[R45] 批量删除
来源：http://dali.cqqwz.cn/Article/details/gt2vgulrloy.html

find . -name "*.tmp" -delete
来源：http://dali.aibaodan.cn/Article/details/gt2gtuuxgbj.html

[R46] 递归替换文件内容
来源：http://dali.xuetiantiany.cn/Article/details/gt2fxihvelw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.aizwys.cn/Article/details/gt2hsvhjcis.html

[R47] sed 单行替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2svoopplw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cheryme.top/Article/details/gt2kapsjusa.html

[R48] awk 取指定列
来源：http://dali.tianlin.xyz/Article/details/gt2cxcuwrns.html

awk '{print $1, $3}' a.txt
来源：http://dali.wangdashe.top/Article/details/gt2xgxifpmf.html

[R49] awk 带条件
来源：http://dali.sysykeji.top/Article/details/gt2ztdtwovf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxlwjwk.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2izwsoaws.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.c1oappe.top/Article/details/gt2rumyjkxz.html

[R51] 排序去重取前几
来源：http://dali.daxiang520.top/Article/details/gt2fecvptzd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dashuyun.cn/Article/details/gt2jksgfjmk.html

[R52] 统计行数
来源：http://dali.yj202588.top/Article/details/gt2frnkvuoy.html

wc -l a.txt
来源：http://dali.jianghu66.top/Article/details/gt2gdkdytxi.html

[R53] 查看文件头与实时尾
来源：http://dali.chenlongwang.top/Article/details/gt2tczcdubq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhengqikj.top/Article/details/gt2zvskxfuh.html

[R54] 比较两个文件
来源：http://dali.ybcxt.top/Article/details/gt2krdjxpfn.html

diff a.txt b.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2tyebsrob.html

[R55] 压缩与解压
来源：http://dali.kuanghao11.cn/Article/details/gt2hwzipmmt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zycfv.cn/Article/details/gt2ylmsbcuc.html

[R56] 远程拷贝
来源：http://dali.tanke756.top/Article/details/gt2dnpzcicd.html

scp file user@host:/path/
来源：http://dali.cheryme.top/Article/details/gt2kpcgzxog.html

[R57] 远程执行命令
来源：http://dali.jinqigufen.top/Article/details/gt2palbobty.html

ssh user@host 'uptime'
来源：http://dali.dianchejie.cn/Article/details/gt2lbjvtzgn.html

[R58] 下载文件
来源：http://dali.cdnleiting.top/Article/details/gt2bnxtlbzm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhixingplan.top/Article/details/gt2vdcfkpah.html

[R59] 发 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gt2lzlcssuz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnxiangtu.top/Article/details/gt2cuyfjhwc.html

[R60] 只看 HTTP 状态码
来源：http://dali.hysaishi.cn/Article/details/gt2ykftyfuw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhixingplan.top/Article/details/gt2nfyqednv.html

[R61] 磁盘占用
来源：http://dali.9152youxi.cn/Article/details/gt2mdumxpcr.html

df -h;  du -sh *
来源：http://dali.jqgufenzy.top/Article/details/gt2zyxivnka.html

[R62] 找最占空间的文件
来源：http://dali.jyoumei.cn/Article/details/gt2rivwptbi.html

du -ah . | sort -rh | head -10
来源：http://dali.wangdashe.top/Article/details/gt2mbhazikx.html

[R63] 内存与进程
来源：http://dali.zhixingplan.top/Article/details/gt2rofqtpvg.html

free -h;  ps aux | grep nginx
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yxcyuwil.html

[R64] 结束进程
来源：http://dali.zhixingplan.top/Article/details/gt2lswnwcth.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj20258.top/Article/details/gt2smxvzxyx.html

[R65] 查看端口占用
来源：http://dali.tian-w.cn/Article/details/gt2zpdthvtt.html


<!-- 参考信息 -->