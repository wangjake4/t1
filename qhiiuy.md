代发 wailian999

SELECT * FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtzfzspbqs.html

[Q16] 查询指定列
来源：http://dali.daxiang520.top/Article/details/gtirrtzhuc.html

SELECT id, name FROM users;
来源：http://dali.hnqzz.top/Article/details/gtimyhnwty.html

[Q17] 条件查询
来源：http://dali.yuanzhike.top/Article/details/gtjnrltmsa.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.aibaodan.cn/Article/details/gtklwkodwf.html

[Q18] 模糊匹配
来源：http://dali.zhengqikj.top/Article/details/gtcaesjjjr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ehwqpu.com/Article/details/gtalgdtulz.html

[Q19] 范围查询
来源：http://dali.chenlongwang.top/Article/details/gtjsirfdwu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cheryme.top/Article/details/gtfkgsywto.html

[Q20] IN 列表
来源：http://dali.daxiang520.top/Article/details/gtppnumqzu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guowangkeji.top/Article/details/gtlpukwlkv.html

[Q21] 空值判断
来源：http://dali.cucudq.cn/Article/details/gtvwfmripv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tanke756.top/Article/details/gtmijrnfti.html

[Q22] 排序
来源：http://dali.gotoacloud.top/Article/details/gtfouyeoqf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cqqwz.cn/Article/details/gtglsxlepv.html

[Q23] 分页
来源：http://dali.hnqzz.top/Article/details/gtuohccvua.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenzaomai.com/Article/details/gtuvhuqvvy.html

[Q24] 去重
来源：http://dali.fengsongda.top/Article/details/gtlypoaard.html

SELECT DISTINCT city FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtlfxsqnrw.html

[Q25] 只取前 N 条
来源：http://dali.fzhhl.top/Article/details/gtrcwzybhr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj202588.top/Article/details/gtbfvltqvo.html

[Q26] 计数
来源：http://dali.gaohongyu789.top/Article/details/gtuuadfqmj.html

SELECT COUNT(*) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkioowojs.html

[Q27] 条件计数
来源：http://dali.cheryme.top/Article/details/gtgpvbxyzg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zycfv.cn/Article/details/gtvlefxayf.html

[Q28] 求和与平均
来源：http://dali.jlsjyb.cn/Article/details/gtxdhjiqgb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtfsakqncf.html

[Q29] 最大最小值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfkpzdvyu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhtauwea.html

[Q30] 分组统计
来源：http://dali.xylfe.cn/Article/details/gttvkcspap.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gtmvkhwfsr.html

[Q31] 分组后过滤
来源：http://dali.vqdsnc.cn/Article/details/gtzblqbwkl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nwbrower.top/Article/details/gtxuvptxjp.html

[Q32] 分组拼接字符串
来源：http://dali.xuanzx.com/Article/details/gthqljkypw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gtdcalttpb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hfpthk.cn/Article/details/gtkhmgywiv.html

[Q33] 多列分组
来源：http://dali.tianlin.xyz/Article/details/gtnngxjbpx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfrttdtx.html

[Q34] 每组取第一条
来源：http://dali.nanxinkj.top/Article/details/gtdhdbfqbj.html

SELECT * FROM (
来源：http://dali.haohaochexian.top/Article/details/gtbkjftina.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xylfe.cn/Article/details/gtvkfbordh.html

) t WHERE rn = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtdsrjwtue.html

[Q35] 内连接
来源：http://dali.yueranfly.top/Article/details/gtwvexnvjh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigufen.top/Article/details/gtsgbbcbtm.html

[Q36] 左连接
来源：http://dali.wangdashe.top/Article/details/gttbxancyy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxinkj.top/Article/details/gtfcvnnlgh.html

[Q37] 右连接
来源：http://dali.cqqwz.cn/Article/details/gtegbtyver.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj202588.top/Article/details/gtqfnmdagn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jianghu66.top/Article/details/gtvbjpuguh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhongyouzk.top/Article/details/gtutcherdu.html

[Q39] 自连接（查上下级）
来源：http://dali.xuetiantiany.cn/Article/details/gtcesmmnaa.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nwbrower.top/Article/details/gtxtarassb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gaohongyu789.top/Article/details/gtdanimzln.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tian-w.cn/Article/details/gtytskfemy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkovwnbv.html

[Q41] 多表连接
来源：http://dali.yj20258888.top/Article/details/gtmyisczyu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangshuangyany.cn/Article/details/gtzulpbuux.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gotoacloud.top/Article/details/gtyeiuavlv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.kuanghao11.cn/Article/details/gtzqueeowe.html

[Q42] 连接条件附加过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrcbvpli.html

SELECT u.name, o.amount FROM users u
来源：http://dali.haohaochexian.top/Article/details/gtrrztcnzx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jianghu66.top/Article/details/gtqhidcoyi.html

[Q43] 标量子查询
来源：http://dali.iojbl.cn/Article/details/gttrlhwliv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jlsjyb.cn/Article/details/gtlaihzjhf.html

[Q44] IN 子查询
来源：http://dali.andypj.xyz/Article/details/gtlnnvdhte.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xinyue.icu/Article/details/gtgfxrdinc.html

[Q45] EXISTS 判断存在
来源：http://dali.xinyue.icu/Article/details/gtnnguvuil.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gtudlkgmmp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.havefunace.top/Article/details/gtfyeeclje.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcftinsly.html

[Q47] 与平均值比较
来源：http://dali.tian-w.cn/Article/details/gtuvrpfxgl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hywenlv.cn/Article/details/gtcndcufwx.html

[Q48] CTE 公用表表达式
来源：http://dali.yuxming.cn/Article/details/gtexdyqqvx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj20258.top/Article/details/gtmaepdkos.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhoulong.xyz/Article/details/gtgyfzlxtd.html

[Q49] 更新单行
来源：http://dali.bjfxy.top/Article/details/gtxzmvwewb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gthumdtkrb.html

[Q50] 批量更新
来源：http://dali.sufxvd.cn/Article/details/gtlqhnozwm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cashguo.top/Article/details/gtarwinbqa.html

[Q51] 用子查询更新
来源：http://dali.sufxvd.cn/Article/details/gtcefgzsii.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhixingplan.top/Article/details/gtbkpsensc.html

[Q52] 删除指定行
来源：http://dali.316326.xyz/Article/details/gtxfxgexgw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xinyue.icu/Article/details/gttrclzclt.html

[Q53] 按条件删除
来源：http://dali.jlsjyb.cn/Article/details/gtkrdbcsrn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jyoumei.cn/Article/details/gtrnnbpbcw.html

[Q54] 清空表
来源：http://dali.wangshuangyany.cn/Article/details/gtzcxxgcnz.html

TRUNCATE TABLE logs;
来源：http://dali.guowangkeji.top/Article/details/gtgtuwpdyg.html

[Q55] 排名（并列占位）
来源：http://dali.daria6918.cn/Article/details/gtgsdoqlum.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.guowangkeji.top/Article/details/gtborqpwna.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhixingplan.top/Article/details/gtopucfenr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj202588.top/Article/details/gtgkexmxhu.html

[Q57] 行号
来源：http://dali.feifeiyinyue.top/Article/details/gtmlnzkamq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtfifbapoj.html

[Q58] 累计求和
来源：http://dali.yuanzhike.top/Article/details/gtrzcdwvcx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtnbbcbtea.html

[Q59] 分组内累计
来源：http://dali.wangshuangyany.cn/Article/details/gtviupnynj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtonuknudq.html

[Q60] 取上一行 / 下一行
来源：http://dali.bjfxy.top/Article/details/gtytbhgotq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ehwqpu.com/Article/details/gthfzdobfl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtciqgxeae.html

[Q61] 移动平均
来源：http://dali.yj202588.top/Article/details/gtbrldyfat.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtvivzhers.html

[Q62] 分组占比
来源：http://dali.tianlin.xyz/Article/details/gtpxgkmmvu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gtwihcasip.html

[Q63] 开启事务
来源：http://dali.cheryme.top/Article/details/gtnrkcfofv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigfzy.top/Article/details/gtnowasrbk.html

[Q64] 提交事务
来源：http://dali.bjfxy.top/Article/details/gtpuprqnqs.html

COMMIT;
来源：http://dali.zhengqikj.top/Article/details/gtrpjieimj.html

[Q65] 回滚事务
来源：http://dali.gotoacloud.top/Article/details/gtunenrhpq.html

ROLLBACK;
来源：http://dali.daria6918.cn/Article/details/gtsrdposql.html

[Q66] 行锁查询
来源：http://dali.yonumen.top/Article/details/gtfbfawftu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hysaishi.cn/Article/details/gttjhqpddx.html

[Q67] 设置隔离级别
来源：http://dali.yvedp.cn/Article/details/gtvjhvqbgi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hywenlv.cn/Article/details/gtbgprkxwm.html

[Q68] 保存点
来源：http://dali.hysaishi.cn/Article/details/gtvyixtggs.html

SAVEPOINT sp1;
来源：http://dali.yj202588.top/Article/details/gtyjlcwovw.html

ROLLBACK TO sp1;
来源：http://dali.kuanghao11.cn/Article/details/gtnrgizphg.html

[Q69] 查看执行计划
来源：http://dali.ivvv.top/Article/details/gtuyhvghor.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.wangdashe.top/Article/details/gtingbxlrq.html

[Q70] 更新统计信息
来源：http://dali.gzhubu.top/Article/details/gtfdsabfba.html

ANALYZE TABLE users;
来源：http://dali.haohaochexian.top/Article/details/gtdjvsvuky.html

[Q71] 查看建表语句
来源：http://dali.nanxuanxn.top/Article/details/gtdeotputl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlbaawlc.html

[Q72] 查看索引
来源：http://dali.tianlin.xyz/Article/details/gtlrjpyhbu.html

SHOW INDEX FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtbwkgrzbe.html

[Q73] 查看表状态
来源：http://dali.jinqigfzy.top/Article/details/gtmeujrfak.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvdirqtd.html

[Q74] 强制使用索引
来源：http://dali.wangshuangyany.cn/Article/details/gtjdglziyy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ivvv.top/Article/details/gttubtdvtk.html

[Q75] 日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtkanvhaug.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ivvv.top/Article/details/gtoxcvjfwl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cqqwz.cn/Article/details/gtjwcbymzp.html

[Q76] 按天统计
来源：http://dali.0kj1m.cn/Article/details/gtwgkxvouz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tanke756.top/Article/details/gtxideykvm.html

[Q77] 时间加减
来源：http://dali.hnqzz.top/Article/details/gtwvjxbjdf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.meibo888.top/Article/details/gttngbwsno.html

[Q78] 当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gtakqxnsfd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjwvbjon.html

[Q79] 字符串拼接
来源：http://dali.jyoumei.cn/Article/details/gtsdmbxsmi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenzaomai.com/Article/details/gtwecpusun.html

[Q80] 字符串截取
来源：http://dali.ehwqpu.com/Article/details/gtisncwhsw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtbubqqbrk.html

[Q81] 字符串替换
来源：http://dali.redwolf501.top/Article/details/gtghgksfou.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtjzlcnpas.html

[Q82] 字符长度与字节长度
来源：http://dali.guannengcc.top/Article/details/gteohkzkvy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtqefqhyfy.html

[Q83] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtedcdqpvt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtannblxdv.html

[Q84] 去除首尾空格
来源：http://dali.ppjwa.cn/Article/details/gtfutzribb.html

SELECT TRIM(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtqsigrkcv.html

[Q85] 数值取整
来源：http://dali.ehwqpu.com/Article/details/gtsebrzvsn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shangyingyoupin.top/Article/details/gtiymaalse.html

[Q86] 读取 JSON 字段
来源：http://dali.cheryme.top/Article/details/gtazqrnxdu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhixingplan.top/Article/details/gtjtzddrlt.html

[Q87] JSON 字段做条件
来源：http://dali.gzhubu.top/Article/details/gtpworxzpl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhixingplan.top/Article/details/gtttmwusuf.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj202588.top/Article/details/gttqpihstd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sysykeji.top/Article/details/gtccvfuigx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.birdmap.top/Article/details/gtidimfxcx.html

[Q89] 判断表是否存在
来源：http://dali.hywenlv.cn/Article/details/gtkftnkdnw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.birdmap.top/Article/details/gtuhdnvqsq.html

[Q90] 生成序号列
来源：http://dali.gogol.net.cn/Article/details/gtokleadno.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yuxming.cn/Article/details/gtjzqtcvtq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtjelkanqq.html

R. Bash 专题
来源：http://dali.redwolf501.top/Article/details/gtotwunwgv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblzbwnnr.html

[R01] shebang 与严格模式
来源：http://dali.jiagoushi.top/Article/details/gtqjiuhiuk.html

#!/usr/bin/env bash
来源：http://dali.yanxiufei.cn/Article/details/gtpsphcmba.html

set -euo pipefail
来源：http://dali.mhx1999.top/Article/details/gtjmczgnyu.html

[R02] 变量赋值与使用
来源：http://dali.ppjwa.cn/Article/details/gtluivbrux.html

name="Tom"; echo "$name"
来源：http://dali.tian-w.cn/Article/details/gtkutyvmlg.html

[R03] 只读变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtusdhvwju.html

readonly PI=3.14
来源：http://dali.aizwys.cn/Article/details/gtrhekayol.html

[R04] 位置参数
来源：http://dali.sufxvd.cn/Article/details/gtngfpbobs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ehwqpu.com/Article/details/gtpxnxawca.html

[R05] 参数默认值
来源：http://dali.yj20258.top/Article/details/gtoljirqol.html

name="${1:-default}"
来源：http://dali.ivvv.top/Article/details/gtsxbcspgt.html

[R06] 判断命令是否存在
来源：http://dali.aizwys.cn/Article/details/gthomghwiq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yvedp.cn/Article/details/gtzbnpghgc.html

[R07] if 判断文件
来源：http://dali.zycfv.cn/Article/details/gtxyrbjrez.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zycfv.cn/Article/details/gtsafpttta.html

[R08] 数值比较
来源：http://dali.hnxiangtu.top/Article/details/gtvljmplam.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shzxlz.cn/Article/details/gtgoisoviy.html

[R09] 字符串比较
来源：http://dali.fzhhl.top/Article/details/gtnlikowhm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guowangkeji.top/Article/details/gtkcbkewcn.html

[R10] 正则匹配
来源：http://dali.wangshuangyany.cn/Article/details/gthdgnfshv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtnuehsorr.html

[R11] case 多分支
来源：http://dali.gzhubu.top/Article/details/gtfbsyjfhy.html

case "$1" in
来源：http://dali.tanke756.top/Article/details/gtnuhfhlbv.html

start) echo "启动" ;;
来源：http://dali.sxryk.cn/Article/details/gtxdpvigkf.html

stop)  echo "停止" ;;
来源：http://dali.ybcxt.top/Article/details/gtzphspjiw.html

*)     echo "未知命令" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gthqqdtohr.html

esac
来源：http://dali.tian-w.cn/Article/details/gtlzmvxzjb.html

[R12] for 遍历文件
来源：http://dali.dianchejie.cn/Article/details/gtczrnkntu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.mhx1999.top/Article/details/gtebkqnmlm.html

[R13] for 计数循环
来源：http://dali.nanxinkj.top/Article/details/gtzrvtxjzx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.haohaochexian.top/Article/details/gtoiifxxqu.html

[R14] C 风格 for
来源：http://dali.jqgufenzy.top/Article/details/gtczmwqqsz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnckfejyw.html

[R15] while 逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunedugna.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cashguo.top/Article/details/gtplwlovjl.html

[R16] until 等待条件
来源：http://dali.hnxiangtu.top/Article/details/gtiuyzraul.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gtyxebrlns.html

[R17] 数组定义与取值
来源：http://dali.dianchejie.cn/Article/details/gtndgdrlbg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.meibo888.top/Article/details/gtbmbmgytn.html

[R18] 遍历数组
来源：http://dali.redwolf501.top/Article/details/gtpppbkord.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxuanxn.top/Article/details/gtuisyiuyr.html

[R19] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gtaanmspzh.html

echo "${#arr[@]}"
来源：http://dali.hammf.cn/Article/details/gtcjkbspeb.html

[R20] 关联数组（字典）
来源：http://dali.yangfankeji.com/Article/details/gtxhokawux.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tian-w.cn/Article/details/gtjbncjalp.html

[R21] 字符串长度
来源：http://dali.sufxvd.cn/Article/details/gtwvsjqxqn.html

echo "${#s}"
来源：http://dali.sysykeji.top/Article/details/gtlnkphkdj.html

[R22] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gtapddbncw.html

echo "${s:0:5}"
来源：http://dali.hysaishi.cn/Article/details/gtomboroyu.html

[R23] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gtoplcases.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jlsjyb.cn/Article/details/gttjuqwtqk.html

[R24] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gtkkzshhhn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuxming.cn/Article/details/gtzvswbkqa.html

[R25] 去后缀 / 去前缀
来源：http://dali.tianlin.xyz/Article/details/gtpxuqbrdz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shzxlz.cn/Article/details/gtppeltfib.html

[R26] 命令替换
来源：http://dali.yj20258888.top/Article/details/gtwfozudgx.html

now=$(date +%F); echo "$now"
来源：http://dali.daxiang520.top/Article/details/gtlkgvivvj.html

[R27] 算术展开
来源：http://dali.zhaomingkeji.xyz/Article/details/gtebivyotd.html

echo $((1 + 2 * 3))
来源：http://dali.nanxinkj.top/Article/details/gtdwzigknf.html

[R28] 浮点运算
来源：http://dali.sufxvd.cn/Article/details/gtpybkvbmp.html

echo "scale=2; 10/3" | bc
来源：http://dali.hfpthk.cn/Article/details/gtbxdjrunv.html

[R29] 定义函数
来源：http://dali.svipenyu.cn/Article/details/gtdvwmfgcb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hammf.cn/Article/details/gtkqxswqew.html

[R30] 函数返回状态码
来源：http://dali.yangfankeji.com/Article/details/gtnouecjxd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuanzhike.top/Article/details/gtekfmpccr.html

[R31] 局部变量
来源：http://dali.jqgfzy.top/Article/details/gtxdkryxdy.html

f() { local x=1; echo "$x"; }
来源：http://dali.zycfv.cn/Article/details/gthmrhabsx.html

[R32] 参数个数校验
来源：http://dali.316326.xyz/Article/details/gtossnwxgl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gtymdhcmgt.html

[R33] 捕获错误并提示行号
来源：http://dali.jianghu66.top/Article/details/gtgtwrbdrs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xuetiantiany.cn/Article/details/gtkndnamcd.html

[R34] 退出时清理
来源：http://dali.yj20258.top/Article/details/gtcyrnxmri.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gtfxowijxm.html

[R35] 后台执行并等待
来源：http://dali.pengpengdd.cyou/Article/details/gtsucayils.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.fengsongda.top/Article/details/gtihvttydk.html

[R36] 并发执行多个任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqspixyu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.svipenyu.cn/Article/details/gtvbznljtd.html

[R37] 把输出赋给变量
来源：http://dali.pycfn.com/Article/details/gtvfhsvsig.html

files=$(ls -1)
来源：http://dali.andypj.xyz/Article/details/gtimgjyxwb.html

[R38] 管道串联
来源：http://dali.tian-w.cn/Article/details/gtanitkmkj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xuetiantiany.cn/Article/details/gtnamvyeyv.html

[R39] 重定向标准输出与错误
来源：http://dali.gaohongyu789.top/Article/details/gtcnnbccqm.html

cmd > out.log 2>&1
来源：http://dali.c1oappe.top/Article/details/gtrhtjcyia.html

[R40] 追加写日志
来源：http://dali.daria6918.cn/Article/details/gtgupximoe.html

echo "log" >> out.log
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwofcqfpg.html

[R41] 丢弃输出
来源：http://dali.xinyue.icu/Article/details/gtktyzfccp.html

cmd >/dev/null 2>&1
来源：http://dali.yangfankeji.com/Article/details/gtjeyycnwl.html

[R42] 输入重定向
来源：http://dali.zhiwuduotai.top/Article/details/gtezlwfirb.html

wc -l < a.txt
来源：http://dali.chenzaomai.com/Article/details/gtkgtjpwpj.html

[R43] 按名字查找文件
来源：http://dali.gogol.net.cn/Article/details/gttkkcvfhq.html

find . -name "*.log" -type f
来源：http://dali.hnxiangtu.top/Article/details/gtlsbuqnjg.html

[R44] 按修改时间查找
来源：http://dali.mhx1999.top/Article/details/gtzmkzcadp.html

find . -mtime -7 -type f
来源：http://dali.mhx1999.top/Article/details/gtmqldsimv.html

[R45] 批量删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvnphnkjq.html

find . -name "*.tmp" -delete
来源：http://dali.0kj1m.cn/Article/details/gtbzygrjkg.html

[R46] 递归替换文件内容
来源：http://dali.ydzc1.top/Article/details/gtduatezgh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.vqdsnc.cn/Article/details/gtqdyhcwqc.html

[R47] sed 单行替换
来源：http://dali.yj20258.top/Article/details/gtemqdugmi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmzaacrks.html

[R48] awk 取指定列
来源：http://dali.zhengqikj.top/Article/details/gtmeydmnch.html

awk '{print $1, $3}' a.txt
来源：http://dali.316326.xyz/Article/details/gtusoqkccm.html

[R49] awk 带条件
来源：http://dali.hfpthk.cn/Article/details/gtpuseqmop.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangshuangyany.cn/Article/details/gtvirdkadh.html

[R50] awk 求和
来源：http://dali.nanxinkj.top/Article/details/gtoqqsqrkc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtbfvybxrv.html

[R51] 排序去重取前几
来源：http://dali.tianlin.xyz/Article/details/gtwifevbws.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ivvv.top/Article/details/gttmkeczgl.html

[R52] 统计行数
来源：http://dali.andypj.xyz/Article/details/gtywhxcegt.html

wc -l a.txt
来源：http://dali.tianlin.xyz/Article/details/gtmvacrscy.html

[R53] 查看文件头与实时尾
来源：http://dali.shzxlz.cn/Article/details/gtephfkbeb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.c1oappe.top/Article/details/gtktckwxlf.html

[R54] 比较两个文件
来源：http://dali.wangdashe.top/Article/details/gtfisajwcv.html

diff a.txt b.txt
来源：http://dali.daria6918.cn/Article/details/gtxwqoubxa.html

[R55] 压缩与解压
来源：http://dali.guowangkeji.top/Article/details/gtsxpditag.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sysykeji.top/Article/details/gtwbzhdyiv.html

[R56] 远程拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gtgoxllgma.html

scp file user@host:/path/
来源：http://dali.cucudq.cn/Article/details/gtjoshivwz.html

[R57] 远程执行命令
来源：http://dali.tanke756.top/Article/details/gtehvmonvd.html

ssh user@host 'uptime'
来源：http://dali.meibo888.top/Article/details/gtioabweao.html

[R58] 下载文件
来源：http://dali.yj20258.top/Article/details/gtqclajwmq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sufxvd.cn/Article/details/gtgtegwedd.html

[R59] 发 POST JSON
来源：http://dali.wangdashe.top/Article/details/gtaelsggmb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.guowangkeji.top/Article/details/gtmsipnuwb.html

[R60] 只看 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gtspvjtigx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yongpay.top/Article/details/gtqxcrwqyj.html

[R61] 磁盘占用
来源：http://dali.shuidangran.top/Article/details/gtvakjekst.html

df -h;  du -sh *
来源：http://dali.hfpthk.cn/Article/details/gtdycywjbq.html

[R62] 找最占空间的文件
来源：http://dali.sweek.top/Article/details/gtyaxvmwis.html

du -ah . | sort -rh | head -10
来源：http://dali.gogol.net.cn/Article/details/gtxneivfsh.html

[R63] 内存与进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqezkgspc.html

free -h;  ps aux | grep nginx
来源：http://dali.sufxvd.cn/Article/details/gtcevqjppv.html

[R64] 结束进程
来源：http://dali.tian-w.cn/Article/details/gtnuqgeoav.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daria6918.cn/Article/details/gtxocseafd.html

[R65] 查看端口占用
来源：http://dali.yuxming.cn/Article/details/gtgwetejrr.html


<!-- 参考信息 -->