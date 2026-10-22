代发 wailian999

SELECT * FROM users;
来源：http://dali.gzhubu.top/Article/details/gtapckmtwo.html

[Q16] 查询指定列
来源：http://dali.nwbrower.top/Article/details/gthdkwufgv.html

SELECT id, name FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtddmryeua.html

[Q17] 条件查询
来源：http://dali.xuetiantiany.cn/Article/details/gtlaanusxb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtuozqligl.html

[Q18] 模糊匹配
来源：http://dali.hnqzz.top/Article/details/gtqvvodkcq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.feifeiyinyue.top/Article/details/gtkeknifox.html

[Q19] 范围查询
来源：http://dali.vqdsnc.cn/Article/details/gtafaqtprx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.dianchejie.cn/Article/details/gtbhkzbevw.html

[Q20] IN 列表
来源：http://dali.bjfxy.top/Article/details/gtkcmzlrmu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hysaishi.cn/Article/details/gtgtanewqp.html

[Q21] 空值判断
来源：http://dali.pengpengdd.cyou/Article/details/gtlkhsfdmt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnxiangtu.top/Article/details/gtyhlbxisj.html

[Q22] 排序
来源：http://dali.gogol.net.cn/Article/details/gtkzxqbbdj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cheryme.top/Article/details/gtyldbcdig.html

[Q23] 分页
来源：http://dali.fzhhl.top/Article/details/gtwmkobjde.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.c1oappe.top/Article/details/gtlntxugjp.html

[Q24] 去重
来源：http://dali.sufxvd.cn/Article/details/gtrrgttmlv.html

SELECT DISTINCT city FROM users;
来源：http://dali.sweek.top/Article/details/gtivvrowsl.html

[Q25] 只取前 N 条
来源：http://dali.chenzaomai.com/Article/details/gtiowpasle.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinqigufen.top/Article/details/gtkilqqurk.html

[Q26] 计数
来源：http://dali.ivvv.top/Article/details/gtmdncipou.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtrzkilxpv.html

[Q27] 条件计数
来源：http://dali.fzhhl.top/Article/details/gtxnyjrsmd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtoqwohnza.html

[Q28] 求和与平均
来源：http://dali.zhengqikj.top/Article/details/gttazopwww.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtffqmmqop.html

[Q29] 最大最小值
来源：http://dali.aizwys.cn/Article/details/gtedacrhqu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtrpmibjzs.html

[Q30] 分组统计
来源：http://dali.xylfe.cn/Article/details/gteizfpeoe.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gttenqyqbl.html

[Q31] 分组后过滤
来源：http://dali.nanxinkj.top/Article/details/gtlquzggwh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xinyue.icu/Article/details/gtiybnfskr.html

[Q32] 分组拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gtpcrllnfz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gtdvbdhnlt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hnxiangtu.top/Article/details/gtdczivgnc.html

[Q33] 多列分组
来源：http://dali.feifeiyinyue.top/Article/details/gthdznfjhw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pycfn.com/Article/details/gtyqplunvz.html

[Q34] 每组取第一条
来源：http://dali.dianchejie.cn/Article/details/gtdslbmrgi.html

SELECT * FROM (
来源：http://dali.gotoacloud.top/Article/details/gtnrdzvnhs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shangyingyoupin.top/Article/details/gtutlffgxq.html

) t WHERE rn = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtdhlorxyq.html

[Q35] 内连接
来源：http://dali.yuxming.cn/Article/details/gtwjcqoijp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ybcxt.top/Article/details/gtcdnsuuzd.html

[Q36] 左连接
来源：http://dali.sweek.top/Article/details/gtnlbxraim.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gttbdinbah.html

[Q37] 右连接
来源：http://dali.andypj.xyz/Article/details/gtrowdtjxu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.birdmap.top/Article/details/gtjhjkyzvi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hammf.cn/Article/details/gtudhxjptl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.316326.xyz/Article/details/gtzytbkelw.html

[Q39] 自连接（查上下级）
来源：http://dali.zhongyouzk.top/Article/details/gtoxqmzckv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuanzhike.top/Article/details/gtfwmarhix.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cqqwz.cn/Article/details/gtoqdjqvfj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hfpthk.cn/Article/details/gtobzbniib.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.mhx1999.top/Article/details/gtgadfhefn.html

[Q41] 多表连接
来源：http://dali.xziqi.cn/Article/details/gtarurunhv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guowangkeji.top/Article/details/gtbhhmdwwp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jianghu66.top/Article/details/gtagaqftjv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.guowangkeji.top/Article/details/gtijxrycto.html

[Q42] 连接条件附加过滤
来源：http://dali.jqgfzy.top/Article/details/gtanibuxua.html

SELECT u.name, o.amount FROM users u
来源：http://dali.fengsongda.top/Article/details/gtcrmnfrkt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhixingplan.top/Article/details/gtphcywhkh.html

[Q43] 标量子查询
来源：http://dali.smart0.xyz/Article/details/gtwosozrmm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenlongwang.top/Article/details/gtuypkeoez.html

[Q44] IN 子查询
来源：http://dali.zdqjudy.top/Article/details/gtbwjgstvq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.havefunace.top/Article/details/gtygqglcwj.html

[Q45] EXISTS 判断存在
来源：http://dali.zhixingplan.top/Article/details/gtjnrffchp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tianlin.xyz/Article/details/gtlxmtjmnm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangdashe.top/Article/details/gtlovckect.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.kuanghao11.cn/Article/details/gtmqegfiba.html

[Q47] 与平均值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtimdzvant.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gttxqmcrla.html

[Q48] CTE 公用表表达式
来源：http://dali.mhx1999.top/Article/details/gtteqngeyr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yanxiufei.cn/Article/details/gtsqileqjn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangdashe.top/Article/details/gtxzsedtpk.html

[Q49] 更新单行
来源：http://dali.meibo888.top/Article/details/gtzkkikgnk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gtcxhajgde.html

[Q50] 批量更新
来源：http://dali.kuanghao11.cn/Article/details/gtyciykagw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.316326.xyz/Article/details/gtyzllgkyh.html

[Q51] 用子查询更新
来源：http://dali.gaohongyu789.top/Article/details/gtsaawkpsd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.iojbl.cn/Article/details/gtiocpbglv.html

[Q52] 删除指定行
来源：http://dali.sysykeji.top/Article/details/gttxrkypwg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tanke756.top/Article/details/gtevjbrcvb.html

[Q53] 按条件删除
来源：http://dali.shanyushiyangkeji.top/Article/details/gthnijybht.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dianchejie.cn/Article/details/gtxteermpy.html

[Q54] 清空表
来源：http://dali.ivvv.top/Article/details/gtswejvjxj.html

TRUNCATE TABLE logs;
来源：http://dali.nanxuanxn.top/Article/details/gtmdifvokb.html

[Q55] 排名（并列占位）
来源：http://dali.yuanzhike.top/Article/details/gtwgiimuuj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtffgvheqz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ybcxt.top/Article/details/gtbhgaikqk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.dashuyun.cn/Article/details/gtjlfwkxwt.html

[Q57] 行号
来源：http://dali.redwolf501.top/Article/details/gtksuhgmkl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhgmdhwz.html

[Q58] 累计求和
来源：http://dali.ehwqpu.com/Article/details/gtboyynchg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtidsdpyzw.html

[Q59] 分组内累计
来源：http://dali.zdqjudy.top/Article/details/gtcpedefzy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtjcvxqfly.html

[Q60] 取上一行 / 下一行
来源：http://dali.ydzc1.top/Article/details/gtnlmgcbfy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shzxlz.cn/Article/details/gtdbflfdtb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.havefunace.top/Article/details/gtelepyggz.html

[Q61] 移动平均
来源：http://dali.chenjidiqi.icu/Article/details/gtonltfgeo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtqnnkqcum.html

[Q62] 分组占比
来源：http://dali.sysykeji.top/Article/details/gteuswvmpo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gtdcgxdohp.html

[Q63] 开启事务
来源：http://dali.tianlin.xyz/Article/details/gtftixgnvl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhoulong.xyz/Article/details/gtzwcwdfia.html

[Q64] 提交事务
来源：http://dali.yueranfly.top/Article/details/gtehvbqhgh.html

COMMIT;
来源：http://dali.redwolf501.top/Article/details/gtxbjzzgpr.html

[Q65] 回滚事务
来源：http://dali.jlsjyb.cn/Article/details/gtmyegwnqa.html

ROLLBACK;
来源：http://dali.ivvv.top/Article/details/gthldptlfd.html

[Q66] 行锁查询
来源：http://dali.ppjwa.cn/Article/details/gtitltipsp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuanzx.com/Article/details/gtpoalrgvq.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gtizluqtsj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.birdmap.top/Article/details/gtncllmuyt.html

[Q68] 保存点
来源：http://dali.ydzc1.top/Article/details/gtckmmgtlq.html

SAVEPOINT sp1;
来源：http://dali.yangfankeji.com/Article/details/gtuamtajrf.html

ROLLBACK TO sp1;
来源：http://dali.yonumen.top/Article/details/gtpcpmfxlj.html

[Q69] 查看执行计划
来源：http://dali.316326.xyz/Article/details/gtntzznggg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jlsjyb.cn/Article/details/gtmhhcgfjm.html

[Q70] 更新统计信息
来源：http://dali.haohaochexian.top/Article/details/gtmzlfxcer.html

ANALYZE TABLE users;
来源：http://dali.smart0.xyz/Article/details/gtndngbtcn.html

[Q71] 查看建表语句
来源：http://dali.ivvv.top/Article/details/gtfkrcggeb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ivvv.top/Article/details/gtcamqdhzo.html

[Q72] 查看索引
来源：http://dali.zhixingplan.top/Article/details/gtwrxuzqiq.html

SHOW INDEX FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtgytpyqel.html

[Q73] 查看表状态
来源：http://dali.hfpthk.cn/Article/details/gtqxzvrpiz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jyoumei.cn/Article/details/gtogdefkqp.html

[Q74] 强制使用索引
来源：http://dali.yanxiufei.cn/Article/details/gtwfxaflpj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gaohongyu789.top/Article/details/gtaxqxaftw.html

[Q75] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtuljzcekf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtcxxxefpf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xuetiantiany.cn/Article/details/gtyihtibsg.html

[Q76] 按天统计
来源：http://dali.ppjwa.cn/Article/details/gtjxjgnmma.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yueranfly.top/Article/details/gtedzbibuq.html

[Q77] 时间加减
来源：http://dali.jqgufenzy.top/Article/details/gtebyygzol.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.andypj.xyz/Article/details/gtnhcpuqbh.html

[Q78] 当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgmkeygqy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenlongwang.top/Article/details/gtdrazuccq.html

[Q79] 字符串拼接
来源：http://dali.jinqigfzy.top/Article/details/gtkqoyezis.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenjidiqi.icu/Article/details/gtadgajtlv.html

[Q80] 字符串截取
来源：http://dali.c1oappe.top/Article/details/gtnyycwsfx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizohbfkb.html

[Q81] 字符串替换
来源：http://dali.316326.xyz/Article/details/gtmgvupqjj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yvedp.cn/Article/details/gtsduyjpyx.html

[Q82] 字符长度与字节长度
来源：http://dali.zycfv.cn/Article/details/gtgizavwfg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfiaakivr.html

[Q83] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gtpltjqovv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtiyacrkzu.html

[Q84] 去除首尾空格
来源：http://dali.wangshuangyany.cn/Article/details/gtxvxekrfh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtedbpiwjh.html

[Q85] 数值取整
来源：http://dali.nwbrower.top/Article/details/gtguqhjmpd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhongyouzk.top/Article/details/gtgenkyuxs.html

[Q86] 读取 JSON 字段
来源：http://dali.vqdsnc.cn/Article/details/gtzdjuvoxv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gzhubu.top/Article/details/gtrhalobjt.html

[Q87] JSON 字段做条件
来源：http://dali.yj20258888.top/Article/details/gtdeyqbkvb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hysaishi.cn/Article/details/gtqxnzxyro.html

[Q88] 行转列（条件聚合）
来源：http://dali.daria6918.cn/Article/details/gtgjugmdin.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cashguo.top/Article/details/gtyegcrokh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.birdmap.top/Article/details/gtxmrwhocv.html

[Q89] 判断表是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gtodvtwzhu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nwbrower.top/Article/details/gtluugjmzq.html

[Q90] 生成序号列
来源：http://dali.0kj1m.cn/Article/details/gttkbsfouv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangdashe.top/Article/details/gtwngwgzmm.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtwwzovdvl.html

R. Bash 专题
来源：http://dali.9152youxi.cn/Article/details/gtpxvvhfla.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtrkowcxzf.html

[R01] shebang 与严格模式
来源：http://dali.aizwys.cn/Article/details/gtyqzmjduk.html

#!/usr/bin/env bash
来源：http://dali.nanxinkj.top/Article/details/gturldsbwk.html

set -euo pipefail
来源：http://dali.yongpay.top/Article/details/gtcihuroqs.html

[R02] 变量赋值与使用
来源：http://dali.daria6918.cn/Article/details/gtzkzcznwf.html

name="Tom"; echo "$name"
来源：http://dali.yangfankeji.com/Article/details/gtvobrkjxg.html

[R03] 只读变量
来源：http://dali.gogol.net.cn/Article/details/gtnsrjxinw.html

readonly PI=3.14
来源：http://dali.snrcjt.cn/Article/details/gtfkfixcmg.html

[R04] 位置参数
来源：http://dali.yangfankeji.com/Article/details/gtoubnrjsk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.havefunace.top/Article/details/gtfuehfjmm.html

[R05] 参数默认值
来源：http://dali.daxiang520.top/Article/details/gtmgmrtfxp.html

name="${1:-default}"
来源：http://dali.0kj1m.cn/Article/details/gtczztpfxh.html

[R06] 判断命令是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gtaasnkgdq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gtnyzbqmsa.html

[R07] if 判断文件
来源：http://dali.smart0.xyz/Article/details/gtforiaoyf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fzhhl.top/Article/details/gtjqudxslr.html

[R08] 数值比较
来源：http://dali.hongshengwenyu.top/Article/details/gteysnlmvn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shzxlz.cn/Article/details/gtnopaxzvh.html

[R09] 字符串比较
来源：http://dali.birdmap.top/Article/details/gtsvzjghhh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gotoacloud.top/Article/details/gtykzljvjp.html

[R10] 正则匹配
来源：http://dali.yvedp.cn/Article/details/gtstrlydhl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtabanfbss.html

[R11] case 多分支
来源：http://dali.chenjidiqi.icu/Article/details/gtmzpvhecj.html

case "$1" in
来源：http://dali.guannengcc.top/Article/details/gtcynduclu.html

start) echo "启动" ;;
来源：http://dali.yj20258.top/Article/details/gtwdmyweoi.html

stop)  echo "停止" ;;
来源：http://dali.yj202588.top/Article/details/gtkdatinrw.html

*)     echo "未知命令" ;;
来源：http://dali.ydzc1.top/Article/details/gtsltnrdxi.html

esac
来源：http://dali.jinqigufen.top/Article/details/gttjvoprhb.html

[R12] for 遍历文件
来源：http://dali.chenjidiqi.icu/Article/details/gticuxawky.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nwbrower.top/Article/details/gttnmnraks.html

[R13] for 计数循环
来源：http://dali.sufxvd.cn/Article/details/gtkqoluhfi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ehwqpu.com/Article/details/gtemiqgoui.html

[R14] C 风格 for
来源：http://dali.xylfe.cn/Article/details/gteomazvem.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.svipenyu.cn/Article/details/gtodhabaip.html

[R15] while 逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtakoicudh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.redwolf501.top/Article/details/gtjtqbpwjo.html

[R16] until 等待条件
来源：http://dali.yj20258888.top/Article/details/gtnwrjdgtq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gtxtiertgm.html

[R17] 数组定义与取值
来源：http://dali.yvedp.cn/Article/details/gtgshxicvw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgfzy.top/Article/details/gtdmrgvhau.html

[R18] 遍历数组
来源：http://dali.xylfe.cn/Article/details/gtadewppvo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jqgufenzy.top/Article/details/gtrvnxoxif.html

[R19] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gtwzifxrrp.html

echo "${#arr[@]}"
来源：http://dali.redwolf501.top/Article/details/gtanplqnlh.html

[R20] 关联数组（字典）
来源：http://dali.jianghu66.top/Article/details/gtspfapdhh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daxiang520.top/Article/details/gtrsrkglfk.html

[R21] 字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gtpfrueoig.html

echo "${#s}"
来源：http://dali.vqdsnc.cn/Article/details/gtgyyupvug.html

[R22] 截取子串
来源：http://dali.redwolf501.top/Article/details/gtpndifrlu.html

echo "${s:0:5}"
来源：http://dali.shangyingyoupin.top/Article/details/gtvnxkntml.html

[R23] 字符串替换
来源：http://dali.quarkkingdee.top/Article/details/gtgqscxfpi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gtdsrtksgn.html

[R24] 大小写转换
来源：http://dali.birdmap.top/Article/details/gtzgumukal.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jyoumei.cn/Article/details/gtoeesvphq.html

[R25] 去后缀 / 去前缀
来源：http://dali.shzxlz.cn/Article/details/gtkkxieoki.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nwbrower.top/Article/details/gtiomfqbze.html

[R26] 命令替换
来源：http://dali.sysykeji.top/Article/details/gtsbkpccul.html

now=$(date +%F); echo "$now"
来源：http://dali.fzhhl.top/Article/details/gtcidlqtrv.html

[R27] 算术展开
来源：http://dali.hnqzz.top/Article/details/gthbsdtjgk.html

echo $((1 + 2 * 3))
来源：http://dali.pengpengdd.cyou/Article/details/gtycrurami.html

[R28] 浮点运算
来源：http://dali.gogol.net.cn/Article/details/gtcxsywxub.html

echo "scale=2; 10/3" | bc
来源：http://dali.tianlin.xyz/Article/details/gtsdxmxeuy.html

[R29] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gtcxktrazo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqzfvmmg.html

[R30] 函数返回状态码
来源：http://dali.daria6918.cn/Article/details/gtbqmqiykd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hfpthk.cn/Article/details/gtvwtyjagg.html

[R31] 局部变量
来源：http://dali.yj20258888.top/Article/details/gtrnixggtm.html

f() { local x=1; echo "$x"; }
来源：http://dali.jianghu66.top/Article/details/gtpdkxrlqu.html

[R32] 参数个数校验
来源：http://dali.nwbrower.top/Article/details/gtsvudvuzy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.dianchejie.cn/Article/details/gtepomitgq.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgufenzy.top/Article/details/gtyasjprsh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jiagoushi.top/Article/details/gtlmirdvfs.html

[R34] 退出时清理
来源：http://dali.daxiang520.top/Article/details/gtnigfepok.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gtdckupaek.html

[R35] 后台执行并等待
来源：http://dali.fengsongda.top/Article/details/gtjfieonyd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnqzz.top/Article/details/gtvuskimek.html

[R36] 并发执行多个任务
来源：http://dali.sweek.top/Article/details/gtaqteiusn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nwbrower.top/Article/details/gtzfyuskzs.html

[R37] 把输出赋给变量
来源：http://dali.xuetiantiany.cn/Article/details/gtgeeyrgaa.html

files=$(ls -1)
来源：http://dali.hywenlv.cn/Article/details/gtavdtxxke.html

[R38] 管道串联
来源：http://dali.meibo888.top/Article/details/gtkwxxngio.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnqzz.top/Article/details/gttlkgebar.html

[R39] 重定向标准输出与错误
来源：http://dali.sufxvd.cn/Article/details/gthwomejwz.html

cmd > out.log 2>&1
来源：http://dali.yueranfly.top/Article/details/gtpkyptthk.html

[R40] 追加写日志
来源：http://dali.jqgufenzy.top/Article/details/gtuflvyvbj.html

echo "log" >> out.log
来源：http://dali.quarkkingdee.top/Article/details/gtlptsvgax.html

[R41] 丢弃输出
来源：http://dali.wangshuangyany.cn/Article/details/gtqmtedzdj.html

cmd >/dev/null 2>&1
来源：http://dali.haohaochexian.top/Article/details/gtxmvvfuyo.html

[R42] 输入重定向
来源：http://dali.zhiwuduotai.top/Article/details/gtejqivirv.html

wc -l < a.txt
来源：http://dali.daria6918.cn/Article/details/gthvqtsfgr.html

[R43] 按名字查找文件
来源：http://dali.chenzaomai.com/Article/details/gtixpiipwu.html

find . -name "*.log" -type f
来源：http://dali.9152youxi.cn/Article/details/gtvgugmauf.html

[R44] 按修改时间查找
来源：http://dali.xuetiantiany.cn/Article/details/gteeluonsn.html

find . -mtime -7 -type f
来源：http://dali.daria6918.cn/Article/details/gtxadorune.html

[R45] 批量删除
来源：http://dali.xinyue.icu/Article/details/gtuosbytxh.html

find . -name "*.tmp" -delete
来源：http://dali.kuanghao11.cn/Article/details/gtisqznnla.html

[R46] 递归替换文件内容
来源：http://dali.guowangkeji.top/Article/details/gtudistzzp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sysykeji.top/Article/details/gtqdlcoxnf.html

[R47] sed 单行替换
来源：http://dali.quarkkingdee.top/Article/details/gttczisqvj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.redwolf501.top/Article/details/gtitnnqobn.html

[R48] awk 取指定列
来源：http://dali.xinyue.icu/Article/details/gtuysfxdka.html

awk '{print $1, $3}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtryvgwdtl.html

[R49] awk 带条件
来源：http://dali.zhiwuduotai.top/Article/details/gtgkhnjpsi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cheryme.top/Article/details/gtxjsrclml.html

[R50] awk 求和
来源：http://dali.xziqi.cn/Article/details/gtbumgpsuj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cdnleiting.top/Article/details/gtkgfdqlfz.html

[R51] 排序去重取前几
来源：http://dali.chenlongwang.top/Article/details/gtkugziylf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xziqi.cn/Article/details/gtsdnpiokz.html

[R52] 统计行数
来源：http://dali.xziqi.cn/Article/details/gtvzafuxjr.html

wc -l a.txt
来源：http://dali.jyoumei.cn/Article/details/gtaqyxtbpa.html

[R53] 查看文件头与实时尾
来源：http://dali.daxiang520.top/Article/details/gthfbjvclc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jiagoushi.top/Article/details/gtrazxreks.html

[R54] 比较两个文件
来源：http://dali.fzhhl.top/Article/details/gtxrjxbpel.html

diff a.txt b.txt
来源：http://dali.zdqjudy.top/Article/details/gtogrgwejp.html

[R55] 压缩与解压
来源：http://dali.gzhubu.top/Article/details/gtmtfukxrp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.c1oappe.top/Article/details/gtyggpdszw.html

[R56] 远程拷贝
来源：http://dali.cucudq.cn/Article/details/gtjhgwzfcw.html

scp file user@host:/path/
来源：http://dali.bjfxy.top/Article/details/gtqyhfumsd.html

[R57] 远程执行命令
来源：http://dali.hnxiangtu.top/Article/details/gtkoicrwrt.html

ssh user@host 'uptime'
来源：http://dali.meibo888.top/Article/details/gtmbjlftcf.html

[R58] 下载文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtcahdmxfg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cashguo.top/Article/details/gtrzpanbtv.html

[R59] 发 POST JSON
来源：http://dali.tian-w.cn/Article/details/gtknnaddqj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.havefunace.top/Article/details/gttiekctty.html

[R60] 只看 HTTP 状态码
来源：http://dali.sufxvd.cn/Article/details/gtghnqmsik.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yvedp.cn/Article/details/gthfzmeqvm.html

[R61] 磁盘占用
来源：http://dali.smart0.xyz/Article/details/gthenixwxv.html

df -h;  du -sh *
来源：http://dali.cheryme.top/Article/details/gtsemhctwu.html

[R62] 找最占空间的文件
来源：http://dali.meibo888.top/Article/details/gtbojrcgla.html

du -ah . | sort -rh | head -10
来源：http://dali.aibaodan.cn/Article/details/gttbljqmml.html

[R63] 内存与进程
来源：http://dali.sweek.top/Article/details/gtbbfqvxgq.html

free -h;  ps aux | grep nginx
来源：http://dali.jlsjyb.cn/Article/details/gtpdmjhsmo.html

[R64] 结束进程
来源：http://dali.feifeiyinyue.top/Article/details/gtjtxyjzga.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnxiangtu.top/Article/details/gtgnsakztq.html

[R65] 查看端口占用
来源：http://dali.gzhubu.top/Article/details/gtnxtfhgyd.html


<!-- 参考信息 -->