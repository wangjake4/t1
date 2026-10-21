代发 wailian999

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenzaomai.com/Article/details/gtrqlpvqln.html

[Q11] 一次插入多行
来源：http://dali.zycfv.cn/Article/details/gtwcxuhwka.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xinyue.icu/Article/details/gtcwwmbgxd.html

[Q12] 插入后取自增 ID
来源：http://dali.gzhubu.top/Article/details/gtsgqltywi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xinyue.icu/Article/details/gtwogbzcrm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shuidangran.top/Article/details/gtauootqxo.html

[Q13] 忽略重复插入
来源：http://dali.hongshengwenyu.top/Article/details/gtvojmxtrj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cqqwz.cn/Article/details/gtvgwrtbud.html

[Q14] 存在则更新（upsert）
来源：http://dali.kuanghao11.cn/Article/details/gtfxkoissi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenlongwang.top/Article/details/gtppbtvgrm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yj202588.top/Article/details/gtqvmsgzzf.html

[Q15] 查询全部
来源：http://dali.shangyingyoupin.top/Article/details/gtwhtcjujs.html

SELECT * FROM users;
来源：http://dali.yj202588.top/Article/details/gtjrikjvlq.html

[Q16] 查询指定列
来源：http://dali.c1oappe.top/Article/details/gtnmiqwqty.html

SELECT id, name FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtyifpplpb.html

[Q17] 条件查询
来源：http://dali.0kj1m.cn/Article/details/gtbycwixuf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cheryme.top/Article/details/gtbnvzeskj.html

[Q18] 模糊匹配
来源：http://dali.svipenyu.cn/Article/details/gtzmpvdrjj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhiwuduotai.top/Article/details/gtekygqqgz.html

[Q19] 范围查询
来源：http://dali.jqgufenzy.top/Article/details/gtfohynzoa.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxipaozd.html

[Q20] IN 列表
来源：http://dali.meibo888.top/Article/details/gtipllmbui.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.vqdsnc.cn/Article/details/gtplvvqnmg.html

[Q21] 空值判断
来源：http://dali.wangshuangyany.cn/Article/details/gtyvchaxqi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinqigfzy.top/Article/details/gtypyotkrs.html

[Q22] 排序
来源：http://dali.pycfn.com/Article/details/gttzmyahua.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhongyouzk.top/Article/details/gtrvzbiyla.html

[Q23] 分页
来源：http://dali.quarkkingdee.top/Article/details/gtpmwmopwn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sysykeji.top/Article/details/gtyhfwlcpa.html

[Q24] 去重
来源：http://dali.quarkkingdee.top/Article/details/gtgrpizatx.html

SELECT DISTINCT city FROM users;
来源：http://dali.yuxming.cn/Article/details/gttqjbuoxd.html

[Q25] 只取前 N 条
来源：http://dali.yanxiufei.cn/Article/details/gtuuespkqg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zycfv.cn/Article/details/gtdmlxqzpj.html

[Q26] 计数
来源：http://dali.mhx1999.top/Article/details/gtlwruijqk.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtpzsynwbn.html

[Q27] 条件计数
来源：http://dali.guannengcc.top/Article/details/gtnxenejxx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtcfrudaim.html

[Q28] 求和与平均
来源：http://dali.pengpengdd.cyou/Article/details/gtpneoqudx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtdludcsqu.html

[Q29] 最大最小值
来源：http://dali.feifeiyinyue.top/Article/details/gtwxekokkj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtdfcafxbh.html

[Q30] 分组统计
来源：http://dali.aibaodan.cn/Article/details/gteyjhaqpc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gtoidjkxfi.html

[Q31] 分组后过滤
来源：http://dali.yangfankeji.com/Article/details/gthhdexvzw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgfzy.top/Article/details/gtqnjlulng.html

[Q32] 分组拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtwhkywmhk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gtaueeeytl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xziqi.cn/Article/details/gtfdahdpxz.html

[Q33] 多列分组
来源：http://dali.shzxlz.cn/Article/details/gtzvxfgnse.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gzhubu.top/Article/details/gthjhctcfs.html

[Q34] 每组取第一条
来源：http://dali.sufxvd.cn/Article/details/gtrjsmlgcf.html

SELECT * FROM (
来源：http://dali.zhiwuduotai.top/Article/details/gtacrhkqfp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fzhhl.top/Article/details/gtfmlhpnps.html

) t WHERE rn = 1;
来源：http://dali.jinqigufen.top/Article/details/gtzxpbkeog.html

[Q35] 内连接
来源：http://dali.hnxiangtu.top/Article/details/gtpwnnxlpe.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gtzvtedvxa.html

[Q36] 左连接
来源：http://dali.aibaodan.cn/Article/details/gtagrqhuqe.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.meibo888.top/Article/details/gttbaqkfvq.html

[Q37] 右连接
来源：http://dali.yj202588.top/Article/details/gtlgbekcgp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jlsjyb.cn/Article/details/gtxiwimoaz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jlsjyb.cn/Article/details/gtufgrwgwz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sxryk.cn/Article/details/gtitbzkyip.html

[Q39] 自连接（查上下级）
来源：http://dali.nanxinkj.top/Article/details/gtsqiophfv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cheryme.top/Article/details/gtganozkdo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yj202588.top/Article/details/gtxyjehybt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nanxuanxn.top/Article/details/gtwuvdbmwx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yuanzhike.top/Article/details/gtyubshyvw.html

[Q41] 多表连接
来源：http://dali.yvedp.cn/Article/details/gtbdlwhjxr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jiagoushi.top/Article/details/gtwdwihhfx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tian-w.cn/Article/details/gtdvylppww.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hongshengwenyu.top/Article/details/gtmyylsjxf.html

[Q42] 连接条件附加过滤
来源：http://dali.yangfankeji.com/Article/details/gtifmdpizy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yueranfly.top/Article/details/gtzpmpnuoz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xziqi.cn/Article/details/gtlprkexar.html

[Q43] 标量子查询
来源：http://dali.hammf.cn/Article/details/gthpbgfkzq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cqqwz.cn/Article/details/gtiducvhpo.html

[Q44] IN 子查询
来源：http://dali.cqqwz.cn/Article/details/gtlteawrku.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhoulong.xyz/Article/details/gtdbcudthn.html

[Q45] EXISTS 判断存在
来源：http://dali.fengsongda.top/Article/details/gtzzphsfhy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jiagoushi.top/Article/details/gtqfmbxszh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrobvqti.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhoulong.xyz/Article/details/gtjeppiond.html

[Q47] 与平均值比较
来源：http://dali.gaohongyu789.top/Article/details/gtbymbltxr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zycfv.cn/Article/details/gtemutolvz.html

[Q48] CTE 公用表表达式
来源：http://dali.yanxiufei.cn/Article/details/gtydlxagmu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.haohaochexian.top/Article/details/gtjfvlxqia.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sysykeji.top/Article/details/gttudeotyu.html

[Q49] 更新单行
来源：http://dali.guannengcc.top/Article/details/gtwsvqejpn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwoyxwnz.html

[Q50] 批量更新
来源：http://dali.zhengqikj.top/Article/details/gtwoykhvpw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj202588.top/Article/details/gtvwvyixmj.html

[Q51] 用子查询更新
来源：http://dali.yuanzhike.top/Article/details/gtbihtpvfi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hysaishi.cn/Article/details/gtbyebwnpb.html

[Q52] 删除指定行
来源：http://dali.ydzc1.top/Article/details/gtysidfqdy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gtvflpyqkg.html

[Q53] 按条件删除
来源：http://dali.fzhhl.top/Article/details/gtuiwjeqcs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.wangdashe.top/Article/details/gtosyktlyi.html

[Q54] 清空表
来源：http://dali.yj202588.top/Article/details/gtggalskwq.html

TRUNCATE TABLE logs;
来源：http://dali.jianghu66.top/Article/details/gtwplyfuus.html

[Q55] 排名（并列占位）
来源：http://dali.jlsjyb.cn/Article/details/gteubagrnl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.bjfxy.top/Article/details/gtozeosfvd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tianlin.xyz/Article/details/gtuwtzntvd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gtwilbombe.html

[Q57] 行号
来源：http://dali.nanxuanxn.top/Article/details/gtyrnixngk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.iojbl.cn/Article/details/gtmrnzjtno.html

[Q58] 累计求和
来源：http://dali.daria6918.cn/Article/details/gtnneqfnut.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtxmyfyouw.html

[Q59] 分组内累计
来源：http://dali.aibaodan.cn/Article/details/gtgvsmgibr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtftlinfml.html

[Q60] 取上一行 / 下一行
来源：http://dali.cucudq.cn/Article/details/gthznuryiv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hywenlv.cn/Article/details/gtygtgxmkm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtfillrajy.html

[Q61] 移动平均
来源：http://dali.jianghu66.top/Article/details/gtmaergfzi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtmzowtwif.html

[Q62] 分组占比
来源：http://dali.fengsongda.top/Article/details/gtkegzsqhd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gtloxonoge.html

[Q63] 开启事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxmokjity.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yueranfly.top/Article/details/gtazffnrlu.html

[Q64] 提交事务
来源：http://dali.ehwqpu.com/Article/details/gtglhkckgr.html

COMMIT;
来源：http://dali.chenlongwang.top/Article/details/gtetrzdses.html

[Q65] 回滚事务
来源：http://dali.nanxinkj.top/Article/details/gtdxwotkct.html

ROLLBACK;
来源：http://dali.yongpay.top/Article/details/gttgmekxzd.html

[Q66] 行锁查询
来源：http://dali.yangfankeji.com/Article/details/gtevqsrbxp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jqgufenzy.top/Article/details/gtxomglxej.html

[Q67] 设置隔离级别
来源：http://dali.cdnleiting.top/Article/details/gtzomfqwje.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nwbrower.top/Article/details/gtkeflafuh.html

[Q68] 保存点
来源：http://dali.shuidangran.top/Article/details/gtntvhgorm.html

SAVEPOINT sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gtaoeqysfu.html

ROLLBACK TO sp1;
来源：http://dali.hnqzz.top/Article/details/gttabhienw.html

[Q69] 查看执行计划
来源：http://dali.zhoulong.xyz/Article/details/gtvynzchbn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.dianchejie.cn/Article/details/gtiomdecsp.html

[Q70] 更新统计信息
来源：http://dali.dianchejie.cn/Article/details/gtsygcirsv.html

ANALYZE TABLE users;
来源：http://dali.xuetiantiany.cn/Article/details/gtpxkaopyt.html

[Q71] 查看建表语句
来源：http://dali.andypj.xyz/Article/details/gtppfzujnk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shzxlz.cn/Article/details/gtoippuisp.html

[Q72] 查看索引
来源：http://dali.yanxiufei.cn/Article/details/gthrervzeg.html

SHOW INDEX FROM users;
来源：http://dali.ivvv.top/Article/details/gtzevrkzpp.html

[Q73] 查看表状态
来源：http://dali.chenzaomai.com/Article/details/gtlgefyjvk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhengqikj.top/Article/details/gtxsoqnlnv.html

[Q74] 强制使用索引
来源：http://dali.sweek.top/Article/details/gtghqbzmcs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jyoumei.cn/Article/details/gtgykpsgtl.html

[Q75] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtkwqvzpmi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtcznqcirt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sufxvd.cn/Article/details/gtowhltcft.html

[Q76] 按天统计
来源：http://dali.zycfv.cn/Article/details/gtdebuqsmh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gzhubu.top/Article/details/gtgdwcwckv.html

[Q77] 时间加减
来源：http://dali.chenzaomai.com/Article/details/gtpqnmefer.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cqqwz.cn/Article/details/gtwrjyazbv.html

[Q78] 当前时间
来源：http://dali.zhoulong.xyz/Article/details/gtcqqdqqyg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gogol.net.cn/Article/details/gtvyxqesgu.html

[Q79] 字符串拼接
来源：http://dali.jianghu66.top/Article/details/gttucysuyt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.quarkkingdee.top/Article/details/gtixegjdoj.html

[Q80] 字符串截取
来源：http://dali.0kj1m.cn/Article/details/gtxtdfqjuz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtjlfxtoci.html

[Q81] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwmayyhc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtdikkszvt.html

[Q82] 字符长度与字节长度
来源：http://dali.mhx1999.top/Article/details/gtjnctnvde.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtqcxakopl.html

[Q83] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gtsglfvlpx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtaleajwme.html

[Q84] 去除首尾空格
来源：http://dali.cashguo.top/Article/details/gttoapxcqz.html

SELECT TRIM(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gtdxwakjkc.html

[Q85] 数值取整
来源：http://dali.zhengqikj.top/Article/details/gtrqmbdijh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.smart0.xyz/Article/details/gtnridbhsj.html

[Q86] 读取 JSON 字段
来源：http://dali.hysaishi.cn/Article/details/gtlaajyofz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ehwqpu.com/Article/details/gtaycgnhyu.html

[Q87] JSON 字段做条件
来源：http://dali.ybcxt.top/Article/details/gtknzcwdnn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yuxming.cn/Article/details/gtdjddrjcr.html

[Q88] 行转列（条件聚合）
来源：http://dali.svipenyu.cn/Article/details/gtfqwhwcmx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.redwolf501.top/Article/details/gtcozamadj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtlwdikjjj.html

[Q89] 判断表是否存在
来源：http://dali.fzhhl.top/Article/details/gttyoroezq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtbkvtbf.html

[Q90] 生成序号列
来源：http://dali.sxryk.cn/Article/details/gteyvatenm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gzhubu.top/Article/details/gtochibwyf.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhcvlhwn.html

R. Bash 专题
来源：http://dali.tian-w.cn/Article/details/gterxbvsix.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfoevmyjr.html

[R01] shebang 与严格模式
来源：http://dali.guowangkeji.top/Article/details/gtxjekkcgi.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gtqqunhtaw.html

set -euo pipefail
来源：http://dali.shzxlz.cn/Article/details/gtcxtugaqg.html

[R02] 变量赋值与使用
来源：http://dali.tanke756.top/Article/details/gtimvrkmzy.html

name="Tom"; echo "$name"
来源：http://dali.ehwqpu.com/Article/details/gtypxhaqcr.html

[R03] 只读变量
来源：http://dali.yanxiufei.cn/Article/details/gtmigoldtz.html

readonly PI=3.14
来源：http://dali.9152youxi.cn/Article/details/gtyeyrzuna.html

[R04] 位置参数
来源：http://dali.dianchejie.cn/Article/details/gtohpsscrr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tian-w.cn/Article/details/gtynkpvogc.html

[R05] 参数默认值
来源：http://dali.hammf.cn/Article/details/gtmkmuevgp.html

name="${1:-default}"
来源：http://dali.ehwqpu.com/Article/details/gtntzvbagc.html

[R06] 判断命令是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtydppiest.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenlongwang.top/Article/details/gtxkrlprsu.html

[R07] if 判断文件
来源：http://dali.gogol.net.cn/Article/details/gtwyygqpkq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cashguo.top/Article/details/gtzshdxxtx.html

[R08] 数值比较
来源：http://dali.dashuyun.cn/Article/details/gthyzsppny.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gotoacloud.top/Article/details/gtrjarbyip.html

[R09] 字符串比较
来源：http://dali.sufxvd.cn/Article/details/gtepmdiwkk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtpvgtugmp.html

[R10] 正则匹配
来源：http://dali.9152youxi.cn/Article/details/gtwvtpuesn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuanzhike.top/Article/details/gttgdlxzrq.html

[R11] case 多分支
来源：http://dali.meibo888.top/Article/details/gtipkouzip.html

case "$1" in
来源：http://dali.hywenlv.cn/Article/details/gtyjvpssmv.html

start) echo "启动" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtwlmljksr.html

stop)  echo "停止" ;;
来源：http://dali.ehwqpu.com/Article/details/gtgdjhvsky.html

*)     echo "未知命令" ;;
来源：http://dali.hysaishi.cn/Article/details/gtzomouxwf.html

esac
来源：http://dali.yuanzhike.top/Article/details/gtkjkjkfio.html

[R12] for 遍历文件
来源：http://dali.yanxiufei.cn/Article/details/gtgzxnolgg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.vqdsnc.cn/Article/details/gtulxkpqyp.html

[R13] for 计数循环
来源：http://dali.jinqigfzy.top/Article/details/gtrxqarths.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gtfikpilhr.html

[R14] C 风格 for
来源：http://dali.daxiang520.top/Article/details/gtbomjyipu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.havefunace.top/Article/details/gtcyjxuarw.html

[R15] while 逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtkuazzwum.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shzxlz.cn/Article/details/gtorrimkmz.html

[R16] until 等待条件
来源：http://dali.jinqigfzy.top/Article/details/gtnepqnock.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gtzfibtpwk.html

[R17] 数组定义与取值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtanvtcoia.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hongshengwenyu.top/Article/details/gtjdbtmkiz.html

[R18] 遍历数组
来源：http://dali.snrcjt.cn/Article/details/gtoyinrrki.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dianchejie.cn/Article/details/gtanuxsrrl.html

[R19] 数组长度
来源：http://dali.cucudq.cn/Article/details/gtivbzlywq.html

echo "${#arr[@]}"
来源：http://dali.feifeiyinyue.top/Article/details/gtvujwcatg.html

[R20] 关联数组（字典）
来源：http://dali.kuanghao11.cn/Article/details/gtrnmrljkc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenlongwang.top/Article/details/gtyslmsvqg.html

[R21] 字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtizwkzcyv.html

echo "${#s}"
来源：http://dali.zhengqikj.top/Article/details/gtvlnhcqnp.html

[R22] 截取子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjrdpemx.html

echo "${s:0:5}"
来源：http://dali.zycfv.cn/Article/details/gtdhcigzec.html

[R23] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gtlcxnalux.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.316326.xyz/Article/details/gtjtltxrhq.html

[R24] 大小写转换
来源：http://dali.hnxiangtu.top/Article/details/gtmehlivht.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ivvv.top/Article/details/gtgmbssbai.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinqigfzy.top/Article/details/gtokjjtrrw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yvedp.cn/Article/details/gtxwrvnnhe.html

[R26] 命令替换
来源：http://dali.c1oappe.top/Article/details/gtkawmvulg.html

now=$(date +%F); echo "$now"
来源：http://dali.yuxming.cn/Article/details/gtnnpmidgd.html

[R27] 算术展开
来源：http://dali.jiagoushi.top/Article/details/gtvmvgmwdk.html

echo $((1 + 2 * 3))
来源：http://dali.316326.xyz/Article/details/gtfqylclqf.html

[R28] 浮点运算
来源：http://dali.jiagoushi.top/Article/details/gtmdhhfpkt.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuanzx.com/Article/details/gtsweraqlq.html

[R29] 定义函数
来源：http://dali.chenjidiqi.icu/Article/details/gtgjsatsga.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dianchejie.cn/Article/details/gtcolwmpur.html

[R30] 函数返回状态码
来源：http://dali.ybcxt.top/Article/details/gtjvwrwzjz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sysykeji.top/Article/details/gtrdrjirxn.html

[R31] 局部变量
来源：http://dali.vqdsnc.cn/Article/details/gtpdopjcjh.html

f() { local x=1; echo "$x"; }
来源：http://dali.nwbrower.top/Article/details/gtcogkidpa.html

[R32] 参数个数校验
来源：http://dali.sxryk.cn/Article/details/gtgmcwjpar.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jqgfzy.top/Article/details/gtovmineae.html

[R33] 捕获错误并提示行号
来源：http://dali.chenjidiqi.icu/Article/details/gtcxihnejf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.havefunace.top/Article/details/gtwvwwxltm.html

[R34] 退出时清理
来源：http://dali.shuidangran.top/Article/details/gtgsbbeyxi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258888.top/Article/details/gtdyfcbkqq.html

[R35] 后台执行并等待
来源：http://dali.nanxuanxn.top/Article/details/gtfefdmqoq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.smart0.xyz/Article/details/gtpvtlpbns.html

[R36] 并发执行多个任务
来源：http://dali.sysykeji.top/Article/details/gtvgowluej.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.iojbl.cn/Article/details/gtsftqtihq.html

[R37] 把输出赋给变量
来源：http://dali.hnxiangtu.top/Article/details/gtcvminmfs.html

files=$(ls -1)
来源：http://dali.havefunace.top/Article/details/gtlsfpjfwp.html

[R38] 管道串联
来源：http://dali.dashuyun.cn/Article/details/gtcrffdmps.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fengsongda.top/Article/details/gtyhhqucpz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhengqikj.top/Article/details/gtqhhzduuh.html

cmd > out.log 2>&1
来源：http://dali.meibo888.top/Article/details/gtumwuqwxe.html

[R40] 追加写日志
来源：http://dali.ppjwa.cn/Article/details/gtwzpfjruq.html

echo "log" >> out.log
来源：http://dali.andypj.xyz/Article/details/gtlvslspsk.html

[R41] 丢弃输出
来源：http://dali.smart0.xyz/Article/details/gtemdfykxs.html

cmd >/dev/null 2>&1
来源：http://dali.zhixingplan.top/Article/details/gtkdtqiyxk.html

[R42] 输入重定向
来源：http://dali.yuxming.cn/Article/details/gtvpparxhq.html

wc -l < a.txt
来源：http://dali.daria6918.cn/Article/details/gtuaislwqu.html

[R43] 按名字查找文件
来源：http://dali.jiagoushi.top/Article/details/gtjlmjyrgo.html

find . -name "*.log" -type f
来源：http://dali.kuanghao11.cn/Article/details/gtfdzhkdgo.html

[R44] 按修改时间查找
来源：http://dali.xuanzx.com/Article/details/gtplyymvbp.html

find . -mtime -7 -type f
来源：http://dali.zhixingplan.top/Article/details/gtyxslebrz.html

[R45] 批量删除
来源：http://dali.guannengcc.top/Article/details/gtyytujlmb.html

find . -name "*.tmp" -delete
来源：http://dali.snrcjt.cn/Article/details/gtmsevpkra.html

[R46] 递归替换文件内容
来源：http://dali.0kj1m.cn/Article/details/gtyomosccm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gtzewsibqr.html

[R47] sed 单行替换
来源：http://dali.nanxuanxn.top/Article/details/gttdxlbokd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihcfvhjs.html

[R48] awk 取指定列
来源：http://dali.zhixingplan.top/Article/details/gtllfmxnww.html

awk '{print $1, $3}' a.txt
来源：http://dali.xziqi.cn/Article/details/gtboedbmce.html

[R49] awk 带条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtvkzinpet.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tian-w.cn/Article/details/gtxfgufnfy.html

[R50] awk 求和
来源：http://dali.wangdashe.top/Article/details/gtbsctfcui.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daxiang520.top/Article/details/gtjenqmuyj.html

[R51] 排序去重取前几
来源：http://dali.yueranfly.top/Article/details/gtbdtxnwne.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.fengsongda.top/Article/details/gtxflujwss.html

[R52] 统计行数
来源：http://dali.sxryk.cn/Article/details/gtonztmbsh.html

wc -l a.txt
来源：http://dali.chenlongwang.top/Article/details/gtqawhgacu.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxuanxn.top/Article/details/gtuqvjrizt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ppjwa.cn/Article/details/gtnckcwwwl.html

[R54] 比较两个文件
来源：http://dali.dianchejie.cn/Article/details/gtnvjhmkqk.html

diff a.txt b.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtervayvrt.html

[R55] 压缩与解压
来源：http://dali.chenzaomai.com/Article/details/gtvncjemjr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tianlin.xyz/Article/details/gtukzawxem.html

[R56] 远程拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gtsffovwnj.html

scp file user@host:/path/
来源：http://dali.shanyushiyangtech.top/Article/details/gtmdzwgjxg.html

[R57] 远程执行命令
来源：http://dali.316326.xyz/Article/details/gtspcjhdha.html

ssh user@host 'uptime'
来源：http://dali.jinqigufen.top/Article/details/gtgmsnxnvu.html

[R58] 下载文件
来源：http://dali.aibaodan.cn/Article/details/gtcwpaassj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jiagoushi.top/Article/details/gteldpeeap.html

[R59] 发 POST JSON
来源：http://dali.zycfv.cn/Article/details/gtifptxefj.html


<!-- 参考信息 -->