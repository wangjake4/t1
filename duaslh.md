代发 wailian999

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vhhwjctn.html

[Q20] IN 列表
来源：http://dali.hammf.cn/Article/details/gt2suztviyf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lycoygii.html

[Q21] 空值判断
来源：http://dali.cheryme.top/Article/details/gt2ppcskojf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinqigufen.top/Article/details/gt2jntyztqb.html

[Q22] 排序
来源：http://dali.tianlin.xyz/Article/details/gt2ipknncim.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.andypj.xyz/Article/details/gt2zldhpjkx.html

[Q23] 分页
来源：http://dali.jqgufenzy.top/Article/details/gt2ngzmggko.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bawbengs.html

[Q24] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vrzvhvkt.html

SELECT DISTINCT city FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2zbouakon.html

[Q25] 只取前 N 条
来源：http://dali.hnxiangtu.top/Article/details/gt2hrniapip.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenlongwang.top/Article/details/gt2fhtpcglo.html

[Q26] 计数
来源：http://dali.hongshengwenyu.top/Article/details/gt2whiyujye.html

SELECT COUNT(*) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2cvgyowep.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtltcyh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2vucavpfw.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqgruss.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj202588.top/Article/details/gt2mxztaopl.html

[Q29] 最大最小值
来源：http://dali.jinqigfzy.top/Article/details/gt2gtgebstv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2ewpqyels.html

[Q30] 分组统计
来源：http://dali.hongshengwenyu.top/Article/details/gt2lhhnpfkb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gt2acuudoep.html

[Q31] 分组后过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2idttgkyk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgfzy.top/Article/details/gt2nnpasuzj.html

[Q32] 分组拼接字符串
来源：http://dali.yvedp.cn/Article/details/gt2zkdjmbmr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gt2bmvugyoh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xylfe.cn/Article/details/gt2rghtkkou.html

[Q33] 多列分组
来源：http://dali.gotoacloud.top/Article/details/gt2yrgtngxc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yvedp.cn/Article/details/gt2imyrhtol.html

[Q34] 每组取第一条
来源：http://dali.zhengqikj.top/Article/details/gt2abqgilsx.html

SELECT * FROM (
来源：http://dali.yongpay.top/Article/details/gt2hamrifij.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pycfn.com/Article/details/gt2wxiewjtf.html

) t WHERE rn = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2gulkesbu.html

[Q35] 内连接
来源：http://dali.wangshuangyany.cn/Article/details/gt2pdkckcgt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xziqi.cn/Article/details/gt2ziptuchu.html

[Q36] 左连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ixkfgrgs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wokkgxry.html

[Q37] 右连接
来源：http://dali.jinqigfzy.top/Article/details/gt2bplcsaou.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xinyue.icu/Article/details/gt2ncgmjubi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.smart0.xyz/Article/details/gt2ydkxbyhd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sxryk.cn/Article/details/gt2pptfcnvy.html

[Q39] 自连接（查上下级）
来源：http://dali.pycfn.com/Article/details/gt2aqxodfgv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xuanzx.com/Article/details/gt2mkcaswot.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.birdmap.top/Article/details/gt2ulxkjnau.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.daxiang520.top/Article/details/gt2zqwjftlk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yueranfly.top/Article/details/gt2yuorerlo.html

[Q41] 多表连接
来源：http://dali.hammf.cn/Article/details/gt2xmzfedpl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.316326.xyz/Article/details/gt2smywhxbz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.guannengcc.top/Article/details/gt2gklthrtg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yueranfly.top/Article/details/gt2hrkwwygo.html

[Q42] 连接条件附加过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pivzqorx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.havefunace.top/Article/details/gt2vdmqbsjv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.meibo888.top/Article/details/gt2ikctmrho.html

[Q43] 标量子查询
来源：http://dali.hysaishi.cn/Article/details/gt2akiantxv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gotoacloud.top/Article/details/gt2bfhmkgjy.html

[Q44] IN 子查询
来源：http://dali.daria6918.cn/Article/details/gt2aymdlzns.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nwbrower.top/Article/details/gt2bxiqjmae.html

[Q45] EXISTS 判断存在
来源：http://dali.iojbl.cn/Article/details/gt2ektvwyqe.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigfzy.top/Article/details/gt2otbjxrse.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenjidiqi.icu/Article/details/gt2llsamrwu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gzhubu.top/Article/details/gt2lmgiddgv.html

[Q47] 与平均值比较
来源：http://dali.bjfxy.top/Article/details/gt2pfdsrdex.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgufenzy.top/Article/details/gt2zulpatlg.html

[Q48] CTE 公用表表达式
来源：http://dali.yj20258888.top/Article/details/gt2afsrdjyw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sysykeji.top/Article/details/gt2rampzfdd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.fengsongda.top/Article/details/gt2dhcpxdzc.html

[Q49] 更新单行
来源：http://dali.nwbrower.top/Article/details/gt2vudeiptr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.9152youxi.cn/Article/details/gt2gbjfjfky.html

[Q50] 批量更新
来源：http://dali.bjfxy.top/Article/details/gt2uhvwlsoa.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhengqikj.top/Article/details/gt2fsuukfdj.html

[Q51] 用子查询更新
来源：http://dali.jinqigfzy.top/Article/details/gt2xlwzpjnd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2zicexlvn.html

[Q52] 删除指定行
来源：http://dali.haohaochexian.top/Article/details/gt2luakbzvp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gt2nefhddwe.html

[Q53] 按条件删除
来源：http://dali.ivvv.top/Article/details/gt2kxvaiyty.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2cpoevull.html

[Q54] 清空表
来源：http://dali.quarkkingdee.top/Article/details/gt2exaxeuss.html

TRUNCATE TABLE logs;
来源：http://dali.vqdsnc.cn/Article/details/gt2utrifmhu.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vtnejeci.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gt2ekstxrfy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ehwqpu.com/Article/details/gt2zdkkqctk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gt2hatouhvd.html

[Q57] 行号
来源：http://dali.hfpthk.cn/Article/details/gt2qkfncrhn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2ohhwfajq.html

[Q58] 累计求和
来源：http://dali.yuanzhike.top/Article/details/gt2zivzzpgf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gt2uozbmmgp.html

[Q59] 分组内累计
来源：http://dali.xuanzx.com/Article/details/gt2algcullo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gt2tlqrwfoh.html

[Q60] 取上一行 / 下一行
来源：http://dali.ydzc1.top/Article/details/gt2ierykfzz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jqgufenzy.top/Article/details/gt2cmzubzti.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2elmggdhm.html

[Q61] 移动平均
来源：http://dali.xziqi.cn/Article/details/gt2ccwzkqay.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2utfuelph.html

[Q62] 分组占比
来源：http://dali.tanke756.top/Article/details/gt2eerklmxa.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gt2skzvzcqn.html

[Q63] 开启事务
来源：http://dali.cashguo.top/Article/details/gt2keoecvlj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigfzy.top/Article/details/gt2gwfsqxfr.html

[Q64] 提交事务
来源：http://dali.hywenlv.cn/Article/details/gt2ubhtelxu.html

COMMIT;
来源：http://dali.feifeiyinyue.top/Article/details/gt2sfxooqai.html

[Q65] 回滚事务
来源：http://dali.jqgufenzy.top/Article/details/gt2ybnomman.html

ROLLBACK;
来源：http://dali.gotoacloud.top/Article/details/gt2dsnskwor.html

[Q66] 行锁查询
来源：http://dali.shzxlz.cn/Article/details/gt2ptwupqkt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jlsjyb.cn/Article/details/gt2uouiegyz.html

[Q67] 设置隔离级别
来源：http://dali.9152youxi.cn/Article/details/gt2tkkbfska.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pycfn.com/Article/details/gt2wuwbctpw.html

[Q68] 保存点
来源：http://dali.smart0.xyz/Article/details/gt2cwfeqjxi.html

SAVEPOINT sp1;
来源：http://dali.yvedp.cn/Article/details/gt2ribfdfcn.html

ROLLBACK TO sp1;
来源：http://dali.sweek.top/Article/details/gt2ijcjvcoz.html

[Q69] 查看执行计划
来源：http://dali.gzhubu.top/Article/details/gt2bxtkgxee.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tian-w.cn/Article/details/gt2lmveunqr.html

[Q70] 更新统计信息
来源：http://dali.havefunace.top/Article/details/gt2qwoirsnd.html

ANALYZE TABLE users;
来源：http://dali.smart0.xyz/Article/details/gt2vvhjpkzy.html

[Q71] 查看建表语句
来源：http://dali.hfpthk.cn/Article/details/gt2nmtasbkm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xuetiantiany.cn/Article/details/gt2vthtabbc.html

[Q72] 查看索引
来源：http://dali.jqgufenzy.top/Article/details/gt2pahbyqwd.html

SHOW INDEX FROM users;
来源：http://dali.yongpay.top/Article/details/gt2wrxjjvnk.html

[Q73] 查看表状态
来源：http://dali.iojbl.cn/Article/details/gt2nmwfvfqi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.smart0.xyz/Article/details/gt2ndajaele.html

[Q74] 强制使用索引
来源：http://dali.zhiwuduotai.top/Article/details/gt2ceozidyg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hnxiangtu.top/Article/details/gt2auujdbri.html

[Q75] 日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gt2srpiznbi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gt2aftxhpmb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2glmkiqdu.html

[Q76] 按天统计
来源：http://dali.dianchejie.cn/Article/details/gt2wnvtarer.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenzaomai.com/Article/details/gt2ltysqhyt.html

[Q77] 时间加减
来源：http://dali.ybcxt.top/Article/details/gt2jjarfgtf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cqqwz.cn/Article/details/gt2elmncjcu.html

[Q78] 当前时间
来源：http://dali.zdqjudy.top/Article/details/gt2razgjcld.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sxryk.cn/Article/details/gt2lzgfuizc.html

[Q79] 字符串拼接
来源：http://dali.gzhubu.top/Article/details/gt2yoccvguk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xziqi.cn/Article/details/gt2qqulnboq.html

[Q80] 字符串截取
来源：http://dali.9152youxi.cn/Article/details/gt2idigniyu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2bgaebagw.html

[Q81] 字符串替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2sztwdpny.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gjmbdpee.html

[Q82] 字符长度与字节长度
来源：http://dali.guannengcc.top/Article/details/gt2yvsznzad.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2fnmriiia.html

[Q83] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gt2ziwuletn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2tsqwovfc.html

[Q84] 去除首尾空格
来源：http://dali.jlsjyb.cn/Article/details/gt2vdjbwlje.html

SELECT TRIM(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2zmyrbrru.html

[Q85] 数值取整
来源：http://dali.zycfv.cn/Article/details/gt2obxwocny.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sysykeji.top/Article/details/gt2ymdwuhrd.html

[Q86] 读取 JSON 字段
来源：http://dali.ybcxt.top/Article/details/gt2irehdxsa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sufxvd.cn/Article/details/gt2nizfiojf.html

[Q87] JSON 字段做条件
来源：http://dali.yanxiufei.cn/Article/details/gt2hdwrozzy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinqigfzy.top/Article/details/gt2bkfikvau.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj20258.top/Article/details/gt2xkdrbkte.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuanzx.com/Article/details/gt2cdflrbyn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.birdmap.top/Article/details/gt2phngasza.html

[Q89] 判断表是否存在
来源：http://dali.gogol.net.cn/Article/details/gt2nboveirh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ltozesmz.html

[Q90] 生成序号列
来源：http://dali.chenjidiqi.icu/Article/details/gt2ytmzbzvp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jqgfzy.top/Article/details/gt2maftalqk.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2gnvhashh.html

R. Bash 专题
来源：http://dali.hysaishi.cn/Article/details/gt2dsgffuuo.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2fcislcbs.html

[R01] shebang 与严格模式
来源：http://dali.redwolf501.top/Article/details/gt2pnaqtzlx.html

#!/usr/bin/env bash
来源：http://dali.xinyue.icu/Article/details/gt2ethpezlq.html

set -euo pipefail
来源：http://dali.daxiang520.top/Article/details/gt2yzlelnps.html

[R02] 变量赋值与使用
来源：http://dali.jqgfzy.top/Article/details/gt2doszgtoh.html

name="Tom"; echo "$name"
来源：http://dali.sysykeji.top/Article/details/gt2pddrhqfn.html

[R03] 只读变量
来源：http://dali.zhixingplan.top/Article/details/gt2cudjuwfm.html

readonly PI=3.14
来源：http://dali.chenlongwang.top/Article/details/gt2iifseeoj.html

[R04] 位置参数
来源：http://dali.yj20258888.top/Article/details/gt2jpypuxhi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cdnleiting.top/Article/details/gt2bmdwdgip.html

[R05] 参数默认值
来源：http://dali.9152youxi.cn/Article/details/gt2zbmmljba.html

name="${1:-default}"
来源：http://dali.cashguo.top/Article/details/gt2hzovorze.html

[R06] 判断命令是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2foytptdp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yangfankeji.com/Article/details/gt2tbzvjzcx.html

[R07] if 判断文件
来源：http://dali.aizwys.cn/Article/details/gt2tfvlkhgw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yueranfly.top/Article/details/gt2phpjuypc.html

[R08] 数值比较
来源：http://dali.fzhhl.top/Article/details/gt2tedtzrpz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dashuyun.cn/Article/details/gt2acdwqpkq.html

[R09] 字符串比较
来源：http://dali.havefunace.top/Article/details/gt2zadkqndk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.svipenyu.cn/Article/details/gt2ovcfpbir.html

[R10] 正则匹配
来源：http://dali.sufxvd.cn/Article/details/gt2ueuswtyf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zycfv.cn/Article/details/gt2sigzampi.html

[R11] case 多分支
来源：http://dali.chenzaomai.com/Article/details/gt2fvabjpal.html

case "$1" in
来源：http://dali.zhengqikj.top/Article/details/gt2madzjnmo.html

start) echo "启动" ;;
来源：http://dali.ppjwa.cn/Article/details/gt2zxgdjrjy.html

stop)  echo "停止" ;;
来源：http://dali.andypj.xyz/Article/details/gt2vyqpfnpj.html

*)     echo "未知命令" ;;
来源：http://dali.bjfxy.top/Article/details/gt2cdrkxwhe.html

esac
来源：http://dali.yj202588.top/Article/details/gt2gctrgqvn.html

[R12] for 遍历文件
来源：http://dali.yvedp.cn/Article/details/gt2xgdzwctu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuanzx.com/Article/details/gt2pwozcjfk.html

[R13] for 计数循环
来源：http://dali.gaohongyu789.top/Article/details/gt2qlknvkrh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gt2usmkchsa.html

[R14] C 风格 for
来源：http://dali.jinqigfzy.top/Article/details/gt2sxhftygv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gt2nwaekagj.html

[R15] while 逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gt2ihcoqfyi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2dhhjzuof.html

[R16] until 等待条件
来源：http://dali.aizwys.cn/Article/details/gt2aauhqjul.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gt2yzujiizy.html

[R17] 数组定义与取值
来源：http://dali.hnxiangtu.top/Article/details/gt2tkxfgbvn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.guowangkeji.top/Article/details/gt2cpsuokjs.html

[R18] 遍历数组
来源：http://dali.shangyingyoupin.top/Article/details/gt2fgzuthul.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2yukgnjvd.html

[R19] 数组长度
来源：http://dali.smart0.xyz/Article/details/gt2ppgyocph.html

echo "${#arr[@]}"
来源：http://dali.svipenyu.cn/Article/details/gt2gjvczjum.html

[R20] 关联数组（字典）
来源：http://dali.yangfankeji.com/Article/details/gt2yhumzzja.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zycfv.cn/Article/details/gt2cqdzvbgs.html

[R21] 字符串长度
来源：http://dali.ydzc1.top/Article/details/gt2fendrtzg.html

echo "${#s}"
来源：http://dali.nanxuanxn.top/Article/details/gt2kkovnfnn.html

[R22] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gt2flwqnyrr.html

echo "${s:0:5}"
来源：http://dali.9152youxi.cn/Article/details/gt2vgxxovnm.html

[R23] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gt2aenytomw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dashuyun.cn/Article/details/gt2hkhrhwcg.html

[R24] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gt2azdprdkg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2olxclvqk.html

[R25] 去后缀 / 去前缀
来源：http://dali.cdnleiting.top/Article/details/gt2tzemzfeo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yueranfly.top/Article/details/gt2elqmychn.html

[R26] 命令替换
来源：http://dali.sxryk.cn/Article/details/gt2zvfoeqma.html

now=$(date +%F); echo "$now"
来源：http://dali.zdqjudy.top/Article/details/gt2kvyytwys.html

[R27] 算术展开
来源：http://dali.jqgufenzy.top/Article/details/gt2ldwyzooq.html

echo $((1 + 2 * 3))
来源：http://dali.nanxuanxn.top/Article/details/gt2adenwvsh.html

[R28] 浮点运算
来源：http://dali.chenzaomai.com/Article/details/gt2neqvutmf.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dvthyhmv.html

[R29] 定义函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ckerkgwf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zycfv.cn/Article/details/gt2lrgpygyo.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pivwjteb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.andypj.xyz/Article/details/gt2mwfpbvek.html

[R31] 局部变量
来源：http://dali.chenzaomai.com/Article/details/gt2zqdrauls.html

f() { local x=1; echo "$x"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2gwdwerqa.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lzqropjh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kfifahgp.html

[R33] 捕获错误并提示行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gztynrre.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cdnleiting.top/Article/details/gt2pbtnclzh.html

[R34] 退出时清理
来源：http://dali.yongpay.top/Article/details/gt2trlhignx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gt2cchglaok.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rfvhlxwu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jiagoushi.top/Article/details/gt2lhbyoigx.html

[R36] 并发执行多个任务
来源：http://dali.ivvv.top/Article/details/gt2btddisbp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hywenlv.cn/Article/details/gt2vxljnpiq.html

[R37] 把输出赋给变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qdkgtxgx.html

files=$(ls -1)
来源：http://dali.ppjwa.cn/Article/details/gt2qgapepum.html

[R38] 管道串联
来源：http://dali.tanke756.top/Article/details/gt2cozgtawx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guowangkeji.top/Article/details/gt2wjdoedcz.html

[R39] 重定向标准输出与错误
来源：http://dali.sweek.top/Article/details/gt2ageigfqm.html

cmd > out.log 2>&1
来源：http://dali.daxiang520.top/Article/details/gt2ktvewlfb.html

[R40] 追加写日志
来源：http://dali.yuanzhike.top/Article/details/gt2djzhuzjp.html

echo "log" >> out.log
来源：http://dali.zhiwuduotai.top/Article/details/gt2uzxpstfl.html

[R41] 丢弃输出
来源：http://dali.jianghu66.top/Article/details/gt2qoigwfci.html

cmd >/dev/null 2>&1
来源：http://dali.xuanzx.com/Article/details/gt2ixphgzci.html

[R42] 输入重定向
来源：http://dali.bjfxy.top/Article/details/gt2wxixkknz.html

wc -l < a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2lfznkthu.html

[R43] 按名字查找文件
来源：http://dali.bjfxy.top/Article/details/gt2wjvnxugw.html

find . -name "*.log" -type f
来源：http://dali.guannengcc.top/Article/details/gt2ozprwxlf.html

[R44] 按修改时间查找
来源：http://dali.guowangkeji.top/Article/details/gt2rwpiwhfs.html

find . -mtime -7 -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2itshahbg.html

[R45] 批量删除
来源：http://dali.jinghuilouyu.cn/Article/details/gt2maazntae.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rhlutnsa.html

[R46] 递归替换文件内容
来源：http://dali.aizwys.cn/Article/details/gt2mdxivuwq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shzxlz.cn/Article/details/gt2mawbapyg.html

[R47] sed 单行替换
来源：http://dali.smart0.xyz/Article/details/gt2qeropuqy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yueranfly.top/Article/details/gt2ichisydh.html

[R48] awk 取指定列
来源：http://dali.xziqi.cn/Article/details/gt2hktjpvnv.html

awk '{print $1, $3}' a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2zwukpmmf.html

[R49] awk 带条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nllzchnt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yanxiufei.cn/Article/details/gt2vbqciytc.html

[R50] awk 求和
来源：http://dali.quarkkingdee.top/Article/details/gt2ftktdpna.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nwbrower.top/Article/details/gt2hfzusisy.html

[R51] 排序去重取前几
来源：http://dali.shangyingyoupin.top/Article/details/gt2ktoreiea.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenjidiqi.icu/Article/details/gt2xatucihj.html

[R52] 统计行数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lnztexib.html

wc -l a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2ptgifptc.html

[R53] 查看文件头与实时尾
来源：http://dali.meibo888.top/Article/details/gt2hqkxlcta.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhoulong.xyz/Article/details/gt2xnufkqfy.html

[R54] 比较两个文件
来源：http://dali.zycfv.cn/Article/details/gt2sdbzmpdr.html

diff a.txt b.txt
来源：http://dali.haohaochexian.top/Article/details/gt2kilrphmi.html

[R55] 压缩与解压
来源：http://dali.wangdashe.top/Article/details/gt2bczauvvl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.iojbl.cn/Article/details/gt2sspwzkfv.html

[R56] 远程拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gt2rwqzaosp.html

scp file user@host:/path/
来源：http://dali.wangdashe.top/Article/details/gt2tfsfkzvi.html

[R57] 远程执行命令
来源：http://dali.yuanzhike.top/Article/details/gt2cktipcei.html

ssh user@host 'uptime'
来源：http://dali.gzhubu.top/Article/details/gt2mwapexyv.html

[R58] 下载文件
来源：http://dali.dianchejie.cn/Article/details/gt2luetmqnu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxuanxn.top/Article/details/gt2pabqyqfe.html

[R59] 发 POST JSON
来源：http://dali.gogol.net.cn/Article/details/gt2ieghhgeq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sweek.top/Article/details/gt2dwsgcfst.html

[R60] 只看 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gt2hxoiecyw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenjidiqi.icu/Article/details/gt2azqrzete.html

[R61] 磁盘占用
来源：http://dali.wangshuangyany.cn/Article/details/gt2xhrozutv.html

df -h;  du -sh *
来源：http://dali.xylfe.cn/Article/details/gt2bzandxca.html

[R62] 找最占空间的文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2wyylihdi.html

du -ah . | sort -rh | head -10
来源：http://dali.zhengqikj.top/Article/details/gt2elhvkxtw.html

[R63] 内存与进程
来源：http://dali.cqqwz.cn/Article/details/gt2pgqqfdxt.html

free -h;  ps aux | grep nginx
来源：http://dali.yanxiufei.cn/Article/details/gt2xwpmztjk.html

[R64] 结束进程
来源：http://dali.zhiwuduotai.top/Article/details/gt2zrieqptu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.wangdashe.top/Article/details/gt2ihdhopxd.html

[R65] 查看端口占用
来源：http://dali.dianchejie.cn/Article/details/gt2egjzsmue.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenjidiqi.icu/Article/details/gt2synksmyg.html

[R66] 定时任务
来源：http://dali.meibo888.top/Article/details/gt2upqoumsj.html

crontab -e;  crontab -l
来源：http://dali.chenzaomai.com/Article/details/gt2gakhewjt.html

[R67] 生成随机十六进制串
来源：http://dali.chenlongwang.top/Article/details/gt2ocwerelx.html

openssl rand -hex 16
来源：http://dali.xuetiantiany.cn/Article/details/gt2ijsywicd.html

[R68] 计算文件校验值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ifzrpjxl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2ptidcyiy.html

[R69] 生成随机密码
来源：http://dali.zhoulong.xyz/Article/details/gt2hubdabwm.html


<!-- 参考信息 -->