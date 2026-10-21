代发 wailian999

SELECT * FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtrtqptkhz.html

[Q16] 查询指定列
来源：http://dali.wangshuangyany.cn/Article/details/gtjiekeldj.html

SELECT id, name FROM users;
来源：http://dali.c1oappe.top/Article/details/gtjvejnayp.html

[Q17] 条件查询
来源：http://dali.shzxlz.cn/Article/details/gtyfbezhlu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtlmxxutcy.html

[Q18] 模糊匹配
来源：http://dali.chenlongwang.top/Article/details/gtflbieyqp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shuidangran.top/Article/details/gtauodbgcx.html

[Q19] 范围查询
来源：http://dali.daxiang520.top/Article/details/gtowgmgpjm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guannengcc.top/Article/details/gtnyxsdgqw.html

[Q20] IN 列表
来源：http://dali.daria6918.cn/Article/details/gtgmkeijtl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenlongwang.top/Article/details/gtgkaygzmc.html

[Q21] 空值判断
来源：http://dali.316326.xyz/Article/details/gtdtchpkwh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhixingplan.top/Article/details/gtfqydlqbo.html

[Q22] 排序
来源：http://dali.guowangkeji.top/Article/details/gtgkhyfldx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xziqi.cn/Article/details/gtmaotvpsy.html

[Q23] 分页
来源：http://dali.cucudq.cn/Article/details/gtkcylfdjz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xuanzx.com/Article/details/gtdyudyugj.html

[Q24] 去重
来源：http://dali.hysaishi.cn/Article/details/gtarqundmi.html

SELECT DISTINCT city FROM users;
来源：http://dali.meibo888.top/Article/details/gtuywmphhf.html

[Q25] 只取前 N 条
来源：http://dali.wangdashe.top/Article/details/gtxbceodcg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.dianchejie.cn/Article/details/gttwnjpjth.html

[Q26] 计数
来源：http://dali.aizwys.cn/Article/details/gtmxleiakm.html

SELECT COUNT(*) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtidjndhhp.html

[Q27] 条件计数
来源：http://dali.wangshuangyany.cn/Article/details/gtoumrppqb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtlzwckmtr.html

[Q28] 求和与平均
来源：http://dali.hfpthk.cn/Article/details/gtwsxqomjn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtnhknqnov.html

[Q29] 最大最小值
来源：http://dali.jianghu66.top/Article/details/gtzbgzjmbp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtqmzggtal.html

[Q30] 分组统计
来源：http://dali.ybcxt.top/Article/details/gtrhehhwsr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtxcspcshw.html

[Q31] 分组后过滤
来源：http://dali.yangfankeji.com/Article/details/gtbrmeuohs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtavwxknig.html

[Q32] 分组拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtboftumst.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtoeyxaorz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yonumen.top/Article/details/gtjjuhfbba.html

[Q33] 多列分组
来源：http://dali.gogol.net.cn/Article/details/gtlpzqkgne.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiveimwrl.html

[Q34] 每组取第一条
来源：http://dali.nwbrower.top/Article/details/gtvapynmgf.html

SELECT * FROM (
来源：http://dali.gzhubu.top/Article/details/gtawdrsbmo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjmfcfxc.html

) t WHERE rn = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtvgsrweag.html

[Q35] 内连接
来源：http://dali.wangshuangyany.cn/Article/details/gtmexligxd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sxryk.cn/Article/details/gtixuybwkv.html

[Q36] 左连接
来源：http://dali.shuidangran.top/Article/details/gtyxtkgwsc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gtdqlqhtcf.html

[Q37] 右连接
来源：http://dali.hysaishi.cn/Article/details/gtojoiabsj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xinyue.icu/Article/details/gtttpsegdh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aibaodan.cn/Article/details/gtdiebancx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jianghu66.top/Article/details/gtmiytsfls.html

[Q39] 自连接（查上下级）
来源：http://dali.yongpay.top/Article/details/gtugjstjpp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xuanzx.com/Article/details/gtgajawbjr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hysaishi.cn/Article/details/gtyyytxuhl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.mhx1999.top/Article/details/gtcnbwfcgb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xuanzx.com/Article/details/gthyunknij.html

[Q41] 多表连接
来源：http://dali.pycfn.com/Article/details/gtdxhoggoz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj202588.top/Article/details/gtbasqjyhx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.dianchejie.cn/Article/details/gtvnzqwfuz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cucudq.cn/Article/details/gtfrmgnrld.html

[Q42] 连接条件附加过滤
来源：http://dali.wangdashe.top/Article/details/gtsdegdjer.html

SELECT u.name, o.amount FROM users u
来源：http://dali.guannengcc.top/Article/details/gtdfihkjbd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.316326.xyz/Article/details/gtcejikmrs.html

[Q43] 标量子查询
来源：http://dali.hfpthk.cn/Article/details/gtrgdgarkf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cqqwz.cn/Article/details/gtyzabzbhx.html

[Q44] IN 子查询
来源：http://dali.dashuyun.cn/Article/details/gtohocohib.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhengqikj.top/Article/details/gtpibpztua.html

[Q45] EXISTS 判断存在
来源：http://dali.hongshengwenyu.top/Article/details/gtoalkwhpw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ppjwa.cn/Article/details/gtcqyunzzt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.bjfxy.top/Article/details/gtydrsidru.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ybcxt.top/Article/details/gtrinzjhib.html

[Q47] 与平均值比较
来源：http://dali.hongshengwenyu.top/Article/details/gtkssqlxff.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.9152youxi.cn/Article/details/gtlesxjyxx.html

[Q48] CTE 公用表表达式
来源：http://dali.yj20258888.top/Article/details/gtmdmccjoz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shzxlz.cn/Article/details/gtrpdtsxfx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhixingplan.top/Article/details/gtzvuskrwj.html

[Q49] 更新单行
来源：http://dali.tian-w.cn/Article/details/gtiyqdmnag.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gtczpqsyyx.html

[Q50] 批量更新
来源：http://dali.aizwys.cn/Article/details/gtqvcxtnay.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shangyingyoupin.top/Article/details/gtyvheuqzv.html

[Q51] 用子查询更新
来源：http://dali.jqgfzy.top/Article/details/gthbtcysrq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ppjwa.cn/Article/details/gtpsxyppsx.html

[Q52] 删除指定行
来源：http://dali.mhx1999.top/Article/details/gtxuvtdhzw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hnxiangtu.top/Article/details/gthcyhzbdi.html

[Q53] 按条件删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxskbuana.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.redwolf501.top/Article/details/gtddzshuac.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gtxrmodzor.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangtech.top/Article/details/gtnlcuhana.html

[Q55] 排名（并列占位）
来源：http://dali.xuetiantiany.cn/Article/details/gtnxncqvhv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.wangdashe.top/Article/details/gtruwdifat.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gzhubu.top/Article/details/gtdualntmx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.316326.xyz/Article/details/gtwvnxdqtr.html

[Q57] 行号
来源：http://dali.xziqi.cn/Article/details/gtsmxqdxfq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtxpqjrldc.html

[Q58] 累计求和
来源：http://dali.0kj1m.cn/Article/details/gtaxbkkhcy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtarxubqzn.html

[Q59] 分组内累计
来源：http://dali.guowangkeji.top/Article/details/gtwdbmxglf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtaylpgupm.html

[Q60] 取上一行 / 下一行
来源：http://dali.sxryk.cn/Article/details/gtsimnzlfq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sysykeji.top/Article/details/gtnunwprur.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gttgqojcdt.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gtxhbuoyyd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtiounsthl.html

[Q62] 分组占比
来源：http://dali.daxiang520.top/Article/details/gtpdouckbr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gtonswuddy.html

[Q63] 开启事务
来源：http://dali.pengpengdd.cyou/Article/details/gttxvlgqcj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhongyouzk.top/Article/details/gtlhwrpvir.html

[Q64] 提交事务
来源：http://dali.feifeiyinyue.top/Article/details/gtqgsrgzaq.html

COMMIT;
来源：http://dali.ivvv.top/Article/details/gtkfwxphto.html

[Q65] 回滚事务
来源：http://dali.hfpthk.cn/Article/details/gtzeopqglr.html

ROLLBACK;
来源：http://dali.xinyue.icu/Article/details/gtngtsqpkj.html

[Q66] 行锁查询
来源：http://dali.yuanzhike.top/Article/details/gtsgchcotb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.aizwys.cn/Article/details/gtmwoapcnt.html

[Q67] 设置隔离级别
来源：http://dali.fzhhl.top/Article/details/gtaushrwjr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.bjfxy.top/Article/details/gtzzyogwgp.html

[Q68] 保存点
来源：http://dali.jinqigfzy.top/Article/details/gtpkvfkupx.html

SAVEPOINT sp1;
来源：http://dali.jinqigfzy.top/Article/details/gtmsembovt.html

ROLLBACK TO sp1;
来源：http://dali.hnxiangtu.top/Article/details/gtzppdzqzm.html

[Q69] 查看执行计划
来源：http://dali.yj20258888.top/Article/details/gtfnqcmimg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.haohaochexian.top/Article/details/gthjstkkjp.html

[Q70] 更新统计信息
来源：http://dali.pycfn.com/Article/details/gtsyenkoqv.html

ANALYZE TABLE users;
来源：http://dali.ybcxt.top/Article/details/gtjtxmovjn.html

[Q71] 查看建表语句
来源：http://dali.zycfv.cn/Article/details/gthpenosra.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zdqjudy.top/Article/details/gtubzgflpl.html

[Q72] 查看索引
来源：http://dali.cdnleiting.top/Article/details/gtjzkabotw.html

SHOW INDEX FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtbjkpzrdx.html

[Q73] 查看表状态
来源：http://dali.nwbrower.top/Article/details/gtvoiqdzrm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhengqikj.top/Article/details/gtfzqumogs.html

[Q74] 强制使用索引
来源：http://dali.sxryk.cn/Article/details/gtaiqlsyoj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ehwqpu.com/Article/details/gtklplbpwk.html

[Q75] 日期格式化
来源：http://dali.yj20258.top/Article/details/gtswfevwwz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtdejdcabg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenjidiqi.icu/Article/details/gtjkkphjau.html

[Q76] 按天统计
来源：http://dali.vqdsnc.cn/Article/details/gtgtvqoxzu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj202588.top/Article/details/gttmteatfo.html

[Q77] 时间加减
来源：http://dali.ydzc1.top/Article/details/gthxnbvlyd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj20258.top/Article/details/gthaiegupf.html

[Q78] 当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdczwbctj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenlongwang.top/Article/details/gtgzuxysos.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gttodqtwst.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ehwqpu.com/Article/details/gtpwqeyfho.html

[Q80] 字符串截取
来源：http://dali.chenzaomai.com/Article/details/gtlqdsvnay.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtabmarkrj.html

[Q81] 字符串替换
来源：http://dali.quarkkingdee.top/Article/details/gtklftyuuf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtzopaitry.html

[Q82] 字符长度与字节长度
来源：http://dali.shuidangran.top/Article/details/gtnzjlsyob.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtomwjkadm.html

[Q83] 大小写转换
来源：http://dali.pycfn.com/Article/details/gtvqdwkakb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtzvcuprqr.html

[Q84] 去除首尾空格
来源：http://dali.sysykeji.top/Article/details/gtqhqkzrjb.html

SELECT TRIM(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtkxmnfbne.html

[Q85] 数值取整
来源：http://dali.sxryk.cn/Article/details/gtapklpwis.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gogol.net.cn/Article/details/gtpcmjwlkw.html

[Q86] 读取 JSON 字段
来源：http://dali.ppjwa.cn/Article/details/gtugadklnh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxuanxn.top/Article/details/gtaklprbwo.html

[Q87] JSON 字段做条件
来源：http://dali.hnxiangtu.top/Article/details/gtlspohlqc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmewxifg.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhoulong.xyz/Article/details/gtcbzqpocm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnxiangtu.top/Article/details/gtokjdamxc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yonumen.top/Article/details/gtqezjlvzw.html

[Q89] 判断表是否存在
来源：http://dali.xylfe.cn/Article/details/gtwvxsjalc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpkyhxra.html

[Q90] 生成序号列
来源：http://dali.guowangkeji.top/Article/details/gtovsoaprt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.9152youxi.cn/Article/details/gtlekqbhvx.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtpoxasrdy.html

R. Bash 专题
来源：http://dali.xinyue.icu/Article/details/gtknppnhmj.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtyjbqjhok.html

[R01] shebang 与严格模式
来源：http://dali.shangyingyoupin.top/Article/details/gtnzcsnccn.html

#!/usr/bin/env bash
来源：http://dali.xuetiantiany.cn/Article/details/gtolocsdqy.html

set -euo pipefail
来源：http://dali.aizwys.cn/Article/details/gtvciuosub.html

[R02] 变量赋值与使用
来源：http://dali.jinqigufen.top/Article/details/gtazzbgrwb.html

name="Tom"; echo "$name"
来源：http://dali.sweek.top/Article/details/gtjqooyzeh.html

[R03] 只读变量
来源：http://dali.fengsongda.top/Article/details/gtcexgdsyf.html

readonly PI=3.14
来源：http://dali.bjfxy.top/Article/details/gtcqbqzlku.html

[R04] 位置参数
来源：http://dali.meibo888.top/Article/details/gtbszfbfxa.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hongshengwenyu.top/Article/details/gtqpdmvfgt.html

[R05] 参数默认值
来源：http://dali.shangyingyoupin.top/Article/details/gtzztmlhus.html

name="${1:-default}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunxtwybr.html

[R06] 判断命令是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtvlfsxhoo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gtdczxites.html

[R07] if 判断文件
来源：http://dali.hywenlv.cn/Article/details/gtoojfimqs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jyoumei.cn/Article/details/gtpweeqycb.html

[R08] 数值比较
来源：http://dali.hammf.cn/Article/details/gtczujjtnd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtufaezfcw.html

[R09] 字符串比较
来源：http://dali.gaohongyu789.top/Article/details/gteuqlbiix.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.aizwys.cn/Article/details/gtbbzokmcb.html

[R10] 正则匹配
来源：http://dali.meibo888.top/Article/details/gtrhgpsldg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258888.top/Article/details/gtcpylcirr.html

[R11] case 多分支
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnpakiywr.html

case "$1" in
来源：http://dali.gogol.net.cn/Article/details/gtrgallurl.html

start) echo "启动" ;;
来源：http://dali.jianghu66.top/Article/details/gttxcggzjz.html

stop)  echo "停止" ;;
来源：http://dali.yuxming.cn/Article/details/gtyylgkcsp.html

*)     echo "未知命令" ;;
来源：http://dali.andypj.xyz/Article/details/gtprtbhdjm.html

esac
来源：http://dali.shanyushiyangtech.top/Article/details/gtsafqruvq.html

[R12] for 遍历文件
来源：http://dali.xziqi.cn/Article/details/gtycqmacwa.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shuidangran.top/Article/details/gteurrqkqh.html

[R13] for 计数循环
来源：http://dali.zhixingplan.top/Article/details/gtgmlgexer.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.fzhhl.top/Article/details/gtrehnxodm.html

[R14] C 风格 for
来源：http://dali.jqgfzy.top/Article/details/gtbbtzzraz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gtbnlwhrqn.html

[R15] while 逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtoepszwqj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.316326.xyz/Article/details/gtjlnleyaf.html

[R16] until 等待条件
来源：http://dali.nwbrower.top/Article/details/gtikdefejz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.smart0.xyz/Article/details/gteyubcuzq.html

[R17] 数组定义与取值
来源：http://dali.ppjwa.cn/Article/details/gtvpzzjnwm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.0kj1m.cn/Article/details/gtkxanvzry.html

[R18] 遍历数组
来源：http://dali.ybcxt.top/Article/details/gthhxfibqf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dianchejie.cn/Article/details/gtjinmbjzb.html

[R19] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gtxmjaskqz.html

echo "${#arr[@]}"
来源：http://dali.gogol.net.cn/Article/details/gtuyncrxmq.html

[R20] 关联数组（字典）
来源：http://dali.zhaomingkeji.xyz/Article/details/gteadbrpqj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.316326.xyz/Article/details/gtrlhaktwk.html

[R21] 字符串长度
来源：http://dali.haohaochexian.top/Article/details/gtquwremsx.html

echo "${#s}"
来源：http://dali.ydzc1.top/Article/details/gtbiofwhfs.html

[R22] 截取子串
来源：http://dali.xinyue.icu/Article/details/gttdwsfoin.html

echo "${s:0:5}"
来源：http://dali.tanke756.top/Article/details/gtepfreuwt.html

[R23] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gtabhcfeae.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hongshengwenyu.top/Article/details/gtwwgfjplg.html

[R24] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttepbxule.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jqgufenzy.top/Article/details/gtcsbrewbi.html

[R25] 去后缀 / 去前缀
来源：http://dali.iojbl.cn/Article/details/gtrdrphwqm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hywenlv.cn/Article/details/gtttfdlpeo.html

[R26] 命令替换
来源：http://dali.hnqzz.top/Article/details/gtknbxeecn.html

now=$(date +%F); echo "$now"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpcejhzkk.html

[R27] 算术展开
来源：http://dali.jyoumei.cn/Article/details/gtlaubgdsu.html

echo $((1 + 2 * 3))
来源：http://dali.jianghu66.top/Article/details/gtsbsyjvwm.html

[R28] 浮点运算
来源：http://dali.jianghu66.top/Article/details/gtttmminqq.html

echo "scale=2; 10/3" | bc
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqavqxgx.html

[R29] 定义函数
来源：http://dali.bjfxy.top/Article/details/gtetcigjae.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtioxcyppa.html

[R30] 函数返回状态码
来源：http://dali.smart0.xyz/Article/details/gtgelcbrau.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zycfv.cn/Article/details/gtcdqjsvuz.html

[R31] 局部变量
来源：http://dali.nanxuanxn.top/Article/details/gtbhglfpgi.html

f() { local x=1; echo "$x"; }
来源：http://dali.svipenyu.cn/Article/details/gtdicqcnvu.html

[R32] 参数个数校验
来源：http://dali.dianchejie.cn/Article/details/gtmshdjzuz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gtiymkppan.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigfzy.top/Article/details/gteycehbkr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ehwqpu.com/Article/details/gtrbbyggdw.html

[R34] 退出时清理
来源：http://dali.daxiang520.top/Article/details/gtfcswpivk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gtiywuyybq.html

[R35] 后台执行并等待
来源：http://dali.hnqzz.top/Article/details/gtubbrvhxv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daria6918.cn/Article/details/gtyyvemqal.html

[R36] 并发执行多个任务
来源：http://dali.andypj.xyz/Article/details/gtmvzkzskr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xylfe.cn/Article/details/gtgosiqcyj.html

[R37] 把输出赋给变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqazghje.html

files=$(ls -1)
来源：http://dali.xylfe.cn/Article/details/gtjfpeseyz.html

[R38] 管道串联
来源：http://dali.zhongyouzk.top/Article/details/gtveppdveh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.pycfn.com/Article/details/gtxdkhawyr.html

[R39] 重定向标准输出与错误
来源：http://dali.dashuyun.cn/Article/details/gtagxndzwu.html

cmd > out.log 2>&1
来源：http://dali.andypj.xyz/Article/details/gtdzizbavs.html

[R40] 追加写日志
来源：http://dali.zdqjudy.top/Article/details/gtmuvxewjx.html

echo "log" >> out.log
来源：http://dali.hongshengwenyu.top/Article/details/gtyysrwszh.html

[R41] 丢弃输出
来源：http://dali.yonumen.top/Article/details/gtbsamhmaq.html

cmd >/dev/null 2>&1
来源：http://dali.hammf.cn/Article/details/gtczilnhoj.html

[R42] 输入重定向
来源：http://dali.316326.xyz/Article/details/gtkgfrtjwj.html

wc -l < a.txt
来源：http://dali.cqqwz.cn/Article/details/gtmlmntdyg.html

[R43] 按名字查找文件
来源：http://dali.tanke756.top/Article/details/gtdhyskvmd.html

find . -name "*.log" -type f
来源：http://dali.pycfn.com/Article/details/gtzbmatuyz.html

[R44] 按修改时间查找
来源：http://dali.yvedp.cn/Article/details/gtubmmxzqy.html

find . -mtime -7 -type f
来源：http://dali.gogol.net.cn/Article/details/gtrvxisgvj.html

[R45] 批量删除
来源：http://dali.jinqigufen.top/Article/details/gtfhgypzib.html

find . -name "*.tmp" -delete
来源：http://dali.shuidangran.top/Article/details/gtvtlixmxh.html

[R46] 递归替换文件内容
来源：http://dali.hnqzz.top/Article/details/gtvudpdgdo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hfpthk.cn/Article/details/gtvsflxtys.html

[R47] sed 单行替换
来源：http://dali.vqdsnc.cn/Article/details/gtyczcepow.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuxming.cn/Article/details/gtmkuijmkq.html

[R48] awk 取指定列
来源：http://dali.jinqigfzy.top/Article/details/gthaesncvz.html

awk '{print $1, $3}' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtgtajuxbi.html

[R49] awk 带条件
来源：http://dali.chenjidiqi.icu/Article/details/gticppwzwz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yangfankeji.com/Article/details/gtmfezvibo.html

[R50] awk 求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwlmqjqp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtrghmqwpd.html

[R51] 排序去重取前几
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbtsptkw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sysykeji.top/Article/details/gtvffqebni.html

[R52] 统计行数
来源：http://dali.hysaishi.cn/Article/details/gttqhcdjtf.html

wc -l a.txt
来源：http://dali.guannengcc.top/Article/details/gtxtozdwzf.html

[R53] 查看文件头与实时尾
来源：http://dali.fzhhl.top/Article/details/gtxycgubmi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tian-w.cn/Article/details/gtihtcpiea.html

[R54] 比较两个文件
来源：http://dali.jqgufenzy.top/Article/details/gtjdyohzpe.html

diff a.txt b.txt
来源：http://dali.nanxinkj.top/Article/details/gtgkmckofd.html

[R55] 压缩与解压
来源：http://dali.zycfv.cn/Article/details/gtpwjnxqeo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yonumen.top/Article/details/gtkntkjubj.html

[R56] 远程拷贝
来源：http://dali.cheryme.top/Article/details/gtwxzyprfm.html

scp file user@host:/path/
来源：http://dali.nanxinkj.top/Article/details/gtzoasolkv.html

[R57] 远程执行命令
来源：http://dali.pycfn.com/Article/details/gtqyyvuhmn.html

ssh user@host 'uptime'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogfuxtdc.html

[R58] 下载文件
来源：http://dali.9152youxi.cn/Article/details/gtxjjlczcg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj20258888.top/Article/details/gtizhrbetu.html

[R59] 发 POST JSON
来源：http://dali.fengsongda.top/Article/details/gtwyhldlgo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ppjwa.cn/Article/details/gtxbijrojl.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhiwuduotai.top/Article/details/gtycjwbfjr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tanke756.top/Article/details/gtggytxvqn.html

[R61] 磁盘占用
来源：http://dali.ehwqpu.com/Article/details/gtvwxposka.html

df -h;  du -sh *
来源：http://dali.yj20258888.top/Article/details/gtoosifggr.html

[R62] 找最占空间的文件
来源：http://dali.yangfankeji.com/Article/details/gtmfiqxzmq.html

du -ah . | sort -rh | head -10
来源：http://dali.xziqi.cn/Article/details/gtcbnptgib.html

[R63] 内存与进程
来源：http://dali.daria6918.cn/Article/details/gtbvmyjnmn.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxinkj.top/Article/details/gtezvfkvzl.html

[R64] 结束进程
来源：http://dali.tianlin.xyz/Article/details/gtdfcwbbke.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cqqwz.cn/Article/details/gtqacyycyw.html

[R65] 查看端口占用
来源：http://dali.iojbl.cn/Article/details/gtlgbgzund.html


<!-- 参考信息 -->