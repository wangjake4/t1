代发 wailian999

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenlongwang.top/Article/details/gtewfwxtgo.html

[Q11] 一次插入多行
来源：http://dali.cucudq.cn/Article/details/gtsnnhcutm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gteckgsahe.html

[Q12] 插入后取自增 ID
来源：http://dali.hywenlv.cn/Article/details/gtmzzicrcr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zdqjudy.top/Article/details/gtuvjcxaqg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.iojbl.cn/Article/details/gthucwlcvw.html

[Q13] 忽略重复插入
来源：http://dali.zhiwuduotai.top/Article/details/gtlswotbii.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sysykeji.top/Article/details/gtzymxkwiz.html

[Q14] 存在则更新（upsert）
来源：http://dali.xziqi.cn/Article/details/gtuzmbyfcb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.wangdashe.top/Article/details/gtyrqtqsmy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yangfankeji.com/Article/details/gtphwboqtf.html

[Q15] 查询全部
来源：http://dali.jiagoushi.top/Article/details/gtqvsdoyyb.html

SELECT * FROM users;
来源：http://dali.birdmap.top/Article/details/gtgypqxavl.html

[Q16] 查询指定列
来源：http://dali.shangyingyoupin.top/Article/details/gtyclhqvrt.html

SELECT id, name FROM users;
来源：http://dali.andypj.xyz/Article/details/gtbbwilhyv.html

[Q17] 条件查询
来源：http://dali.zhongyouzk.top/Article/details/gtfaubvtaw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jqgfzy.top/Article/details/gtrdqqlkyh.html

[Q18] 模糊匹配
来源：http://dali.316326.xyz/Article/details/gtkkskgpzc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yanxiufei.cn/Article/details/gtdkznivrr.html

[Q19] 范围查询
来源：http://dali.smart0.xyz/Article/details/gtogddkqqp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenjidiqi.icu/Article/details/gtldkvvtyw.html

[Q20] IN 列表
来源：http://dali.hammf.cn/Article/details/gtlpkoiafc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuanzhike.top/Article/details/gtaakaomhy.html

[Q21] 空值判断
来源：http://dali.jinqigufen.top/Article/details/gthfsdqffn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.wangdashe.top/Article/details/gtldwfkuab.html

[Q22] 排序
来源：http://dali.andypj.xyz/Article/details/gtgcmujzxr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ybcxt.top/Article/details/gtprfsozlp.html

[Q23] 分页
来源：http://dali.hysaishi.cn/Article/details/gtwvufmduu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gtzkkvpuun.html

[Q24] 去重
来源：http://dali.chenzaomai.com/Article/details/gtwirdsngh.html

SELECT DISTINCT city FROM users;
来源：http://dali.aizwys.cn/Article/details/gtmkehdbrv.html

[Q25] 只取前 N 条
来源：http://dali.yangfankeji.com/Article/details/gteynwfhqt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hongshengwenyu.top/Article/details/gtlaaoldxo.html

[Q26] 计数
来源：http://dali.ybcxt.top/Article/details/gtvzrptouu.html

SELECT COUNT(*) FROM users;
来源：http://dali.ivvv.top/Article/details/gtjwkhklko.html

[Q27] 条件计数
来源：http://dali.xuetiantiany.cn/Article/details/gtxqebanhr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtltrneqzw.html

[Q28] 求和与平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqyilatx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtclzbxdtn.html

[Q29] 最大最小值
来源：http://dali.zhiwuduotai.top/Article/details/gtlcuhhwwo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gttyidvuts.html

[Q30] 分组统计
来源：http://dali.chenlongwang.top/Article/details/gtjkvejlmw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtbndhtmwz.html

[Q31] 分组后过滤
来源：http://dali.sweek.top/Article/details/gtkpgrmhtx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtwgysamoa.html

[Q32] 分组拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtcxdnsisj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gtukueqlia.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.daxiang520.top/Article/details/gtkpczomwi.html

[Q33] 多列分组
来源：http://dali.9152youxi.cn/Article/details/gtspzwqbak.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshzaxjsb.html

[Q34] 每组取第一条
来源：http://dali.shuidangran.top/Article/details/gtqpwbzcwg.html

SELECT * FROM (
来源：http://dali.havefunace.top/Article/details/gtxboncdqk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptbnvhiz.html

) t WHERE rn = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtmaedfuqg.html

[Q35] 内连接
来源：http://dali.tanke756.top/Article/details/gtgvbblyqh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttgtuttug.html

[Q36] 左连接
来源：http://dali.chenjidiqi.icu/Article/details/gthgukxtri.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gtkxutpwyk.html

[Q37] 右连接
来源：http://dali.mhx1999.top/Article/details/gtkkvlsptd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdntzeaq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmckrbvwb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sxryk.cn/Article/details/gtaosinrok.html

[Q39] 自连接（查上下级）
来源：http://dali.hfpthk.cn/Article/details/gtzykoqcdc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.kuanghao11.cn/Article/details/gtczzbtopo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jqgufenzy.top/Article/details/gtdhzrejhs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.andypj.xyz/Article/details/gtygvelnxo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sysykeji.top/Article/details/gtpwcrgcfp.html

[Q41] 多表连接
来源：http://dali.daxiang520.top/Article/details/gtvgmuprko.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhiwuduotai.top/Article/details/gttdidhned.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shzxlz.cn/Article/details/gtbhtxgtqv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.svipenyu.cn/Article/details/gtdunlltpt.html

[Q42] 连接条件附加过滤
来源：http://dali.tanke756.top/Article/details/gtmfshyykh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvopslfe.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fzhhl.top/Article/details/gtxkinhhub.html

[Q43] 标量子查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyklmodjm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aibaodan.cn/Article/details/gtschzpuev.html

[Q44] IN 子查询
来源：http://dali.xylfe.cn/Article/details/gtctlnbwei.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yuxming.cn/Article/details/gtdxaewezl.html

[Q45] EXISTS 判断存在
来源：http://dali.bjfxy.top/Article/details/gtbkbllbmd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zycfv.cn/Article/details/gtehfjqgzw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cqqwz.cn/Article/details/gtfjccqiqn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlhpsnqdc.html

[Q47] 与平均值比较
来源：http://dali.gotoacloud.top/Article/details/gtkkdnasxy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.andypj.xyz/Article/details/gtqkalgptm.html

[Q48] CTE 公用表表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtvzdketzo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzhimljb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sxryk.cn/Article/details/gtqwpsugni.html

[Q49] 更新单行
来源：http://dali.vqdsnc.cn/Article/details/gtvtefxeij.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.mhx1999.top/Article/details/gtweuekowr.html

[Q50] 批量更新
来源：http://dali.jinqigfzy.top/Article/details/gtmhkkrhxr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ehwqpu.com/Article/details/gtserrynmd.html

[Q51] 用子查询更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjgexazgm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sysykeji.top/Article/details/gtuaresxif.html

[Q52] 删除指定行
来源：http://dali.andypj.xyz/Article/details/gtgrkfyxhh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmiuomvya.html

[Q53] 按条件删除
来源：http://dali.vqdsnc.cn/Article/details/gtchuwxhjv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.fengsongda.top/Article/details/gtuvsizfpi.html

[Q54] 清空表
来源：http://dali.jqgfzy.top/Article/details/gtaivopozc.html

TRUNCATE TABLE logs;
来源：http://dali.cucudq.cn/Article/details/gtgwflgczq.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpspjfgm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zycfv.cn/Article/details/gtxmvrqmyi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.c1oappe.top/Article/details/gtptuafrqi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinqigufen.top/Article/details/gthqdrfnnx.html

[Q57] 行号
来源：http://dali.havefunace.top/Article/details/gtxsaegmyf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tanke756.top/Article/details/gtnxmpnanf.html

[Q58] 累计求和
来源：http://dali.cheryme.top/Article/details/gtdrfjrmux.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yongpay.top/Article/details/gtvpcydzua.html

[Q59] 分组内累计
来源：http://dali.cqqwz.cn/Article/details/gtmqulbpit.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtswnjppyd.html

[Q60] 取上一行 / 下一行
来源：http://dali.hywenlv.cn/Article/details/gtppprinas.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jqgfzy.top/Article/details/gtomuyecpo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.havefunace.top/Article/details/gtgdcjybkx.html

[Q61] 移动平均
来源：http://dali.chenlongwang.top/Article/details/gtyexikxwj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtcuhgngsu.html

[Q62] 分组占比
来源：http://dali.vqdsnc.cn/Article/details/gtlrlpwrin.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gtpnfjklxz.html

[Q63] 开启事务
来源：http://dali.hywenlv.cn/Article/details/gtqwcxkkuk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yanxiufei.cn/Article/details/gtnbwexrcw.html

[Q64] 提交事务
来源：http://dali.meibo888.top/Article/details/gtgljuteae.html

COMMIT;
来源：http://dali.vqdsnc.cn/Article/details/gtgdhvdrzd.html

[Q65] 回滚事务
来源：http://dali.jqgufenzy.top/Article/details/gtwmbbxfoq.html

ROLLBACK;
来源：http://dali.pengpengdd.cyou/Article/details/gtkqpqyocc.html

[Q66] 行锁查询
来源：http://dali.316326.xyz/Article/details/gtkfbgpcav.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fengsongda.top/Article/details/gtwdafqntg.html

[Q67] 设置隔离级别
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqoarwzd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nwbrower.top/Article/details/gttpzinawh.html

[Q68] 保存点
来源：http://dali.xziqi.cn/Article/details/gttndfetqo.html

SAVEPOINT sp1;
来源：http://dali.nanxinkj.top/Article/details/gtogmsgalg.html

ROLLBACK TO sp1;
来源：http://dali.hammf.cn/Article/details/gtdwbcfqng.html

[Q69] 查看执行计划
来源：http://dali.daria6918.cn/Article/details/gtxnyulmnc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.andypj.xyz/Article/details/gtvlmrbcoq.html

[Q70] 更新统计信息
来源：http://dali.wangshuangyany.cn/Article/details/gthsvpylmc.html

ANALYZE TABLE users;
来源：http://dali.vqdsnc.cn/Article/details/gtnilgmpfk.html

[Q71] 查看建表语句
来源：http://dali.feifeiyinyue.top/Article/details/gtdnxxbszr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jyoumei.cn/Article/details/gtatlrlxbu.html

[Q72] 查看索引
来源：http://dali.pengpengdd.cyou/Article/details/gtgeytyuli.html

SHOW INDEX FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtuakphhdv.html

[Q73] 查看表状态
来源：http://dali.meibo888.top/Article/details/gttprogjjn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.pycfn.com/Article/details/gtyaiihjly.html

[Q74] 强制使用索引
来源：http://dali.havefunace.top/Article/details/gtzfwwykqw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.svipenyu.cn/Article/details/gtspisblko.html

[Q75] 日期格式化
来源：http://dali.bjfxy.top/Article/details/gthhsfdbdg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtfazwcvxo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenjidiqi.icu/Article/details/gtdvvwivsj.html

[Q76] 按天统计
来源：http://dali.birdmap.top/Article/details/gtehvdbxeo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxinkj.top/Article/details/gtgkricubz.html

[Q77] 时间加减
来源：http://dali.tanke756.top/Article/details/gtarmdjfby.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.mhx1999.top/Article/details/gtdzqiasjm.html

[Q78] 当前时间
来源：http://dali.fengsongda.top/Article/details/gtaqzdvqut.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sxryk.cn/Article/details/gtexjiezyn.html

[Q79] 字符串拼接
来源：http://dali.nwbrower.top/Article/details/gtgvmhnbrl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.svipenyu.cn/Article/details/gtcvxzmchl.html

[Q80] 字符串截取
来源：http://dali.cdnleiting.top/Article/details/gtwgzsneyq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtdjobzuxr.html

[Q81] 字符串替换
来源：http://dali.316326.xyz/Article/details/gtzarnxodv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xuanzx.com/Article/details/gtycrinucy.html

[Q82] 字符长度与字节长度
来源：http://dali.bjfxy.top/Article/details/gtstkduhjh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtwemhdzbp.html

[Q83] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gtttgcehjs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gtabeeiehm.html

[Q84] 去除首尾空格
来源：http://dali.hammf.cn/Article/details/gtvdiptbrq.html

SELECT TRIM(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gtteglwfea.html

[Q85] 数值取整
来源：http://dali.havefunace.top/Article/details/gtzqrfprfy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yonumen.top/Article/details/gtyiwtaqwe.html

[Q86] 读取 JSON 字段
来源：http://dali.sufxvd.cn/Article/details/gtnoufcuce.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhengqikj.top/Article/details/gtvsmxxuqj.html

[Q87] JSON 字段做条件
来源：http://dali.jqgfzy.top/Article/details/gtfnmhbvwp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tanke756.top/Article/details/gtgfhhxiky.html

[Q88] 行转列（条件聚合）
来源：http://dali.xinyue.icu/Article/details/gtviyaumyp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangtech.top/Article/details/gtzkujfuke.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gzhubu.top/Article/details/gtrksfffqb.html

[Q89] 判断表是否存在
来源：http://dali.0kj1m.cn/Article/details/gtvuvadepy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.meibo888.top/Article/details/gtimtaropi.html

[Q90] 生成序号列
来源：http://dali.yj20258888.top/Article/details/gtzrdbsaxu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gzhubu.top/Article/details/gtbjczqwnd.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtvzqmcfji.html

R. Bash 专题
来源：http://dali.yueranfly.top/Article/details/gthhzylrjz.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gthkijcvvx.html

[R01] shebang 与严格模式
来源：http://dali.zhoulong.xyz/Article/details/gtlskvujsh.html

#!/usr/bin/env bash
来源：http://dali.smart0.xyz/Article/details/gtkhdtfknp.html

set -euo pipefail
来源：http://dali.yuxming.cn/Article/details/gtrbkvgxvf.html

[R02] 变量赋值与使用
来源：http://dali.hnxiangtu.top/Article/details/gtrrndmods.html

name="Tom"; echo "$name"
来源：http://dali.ivvv.top/Article/details/gtfnmpyczi.html

[R03] 只读变量
来源：http://dali.zhengqikj.top/Article/details/gthjtyznhe.html

readonly PI=3.14
来源：http://dali.jlsjyb.cn/Article/details/gthtsewtpp.html

[R04] 位置参数
来源：http://dali.zhengqikj.top/Article/details/gtcbixdfse.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvznbvvs.html

[R05] 参数默认值
来源：http://dali.jianghu66.top/Article/details/gtmfmwdxcc.html

name="${1:-default}"
来源：http://dali.havefunace.top/Article/details/gthmtnsuoc.html

[R06] 判断命令是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmjsmdku.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinqigufen.top/Article/details/gtgnccbboy.html

[R07] if 判断文件
来源：http://dali.gzhubu.top/Article/details/gtfsnrmmvi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtidtcrrfi.html

[R08] 数值比较
来源：http://dali.jinqigfzy.top/Article/details/gtcvvilhmh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxrcyxno.html

[R09] 字符串比较
来源：http://dali.pycfn.com/Article/details/gtofcozgqi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cdnleiting.top/Article/details/gthagkjwmq.html

[R10] 正则匹配
来源：http://dali.daxiang520.top/Article/details/gtoklpqyoo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.iojbl.cn/Article/details/gtmyhndfrw.html

[R11] case 多分支
来源：http://dali.mhx1999.top/Article/details/gtweyiwobl.html

case "$1" in
来源：http://dali.redwolf501.top/Article/details/gtmxsegvnz.html

start) echo "启动" ;;
来源：http://dali.tianlin.xyz/Article/details/gtmkhwcbwu.html

stop)  echo "停止" ;;
来源：http://dali.hnqzz.top/Article/details/gtcgzntcfl.html

*)     echo "未知命令" ;;
来源：http://dali.aizwys.cn/Article/details/gtvanwozpg.html

esac
来源：http://dali.ybcxt.top/Article/details/gtbrhpnsdi.html

[R12] for 遍历文件
来源：http://dali.cqqwz.cn/Article/details/gtwfeegfkg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtjxycphve.html

[R13] for 计数循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxavdrpi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gtcuvxpkbm.html

[R14] C 风格 for
来源：http://dali.daxiang520.top/Article/details/gtbuvjkyej.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gtpvkfzhcj.html

[R15] while 逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtozlponmz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fengsongda.top/Article/details/gtzyogkdvf.html

[R16] until 等待条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcldbhoq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gtikcpeyfs.html

[R17] 数组定义与取值
来源：http://dali.ppjwa.cn/Article/details/gtlrvttczn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuetiantiany.cn/Article/details/gtwnqmoipd.html

[R18] 遍历数组
来源：http://dali.fzhhl.top/Article/details/gtojaoyaid.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jianghu66.top/Article/details/gtcdlzadmj.html

[R19] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gtkcxqteto.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtisiihftn.html

[R20] 关联数组（字典）
来源：http://dali.jyoumei.cn/Article/details/gtyqdobtix.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cucudq.cn/Article/details/gthbywanxq.html

[R21] 字符串长度
来源：http://dali.yangfankeji.com/Article/details/gtbdduoctc.html

echo "${#s}"
来源：http://dali.pycfn.com/Article/details/gtcgsxuevf.html

[R22] 截取子串
来源：http://dali.tian-w.cn/Article/details/gtcgklgrrj.html

echo "${s:0:5}"
来源：http://dali.cheryme.top/Article/details/gtfoungxhe.html

[R23] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gtshtbjisi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jlsjyb.cn/Article/details/gtywdkaudh.html

[R24] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gtkqppkuxl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.316326.xyz/Article/details/gtnkjflmhc.html

[R25] 去后缀 / 去前缀
来源：http://dali.sxryk.cn/Article/details/gtoytpxrmo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuxming.cn/Article/details/gtjbpitukq.html

[R26] 命令替换
来源：http://dali.yuxming.cn/Article/details/gtuwlpqyza.html

now=$(date +%F); echo "$now"
来源：http://dali.shzxlz.cn/Article/details/gtvuqwpiyu.html

[R27] 算术展开
来源：http://dali.xinyue.icu/Article/details/gtrhwobpum.html

echo $((1 + 2 * 3))
来源：http://dali.ybcxt.top/Article/details/gtmofcbway.html

[R28] 浮点运算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrxvzvqk.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinqigfzy.top/Article/details/gtzhfcxtdv.html

[R29] 定义函数
来源：http://dali.jinqigufen.top/Article/details/gtkizohfwm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yuanzhike.top/Article/details/gtktpotfil.html

[R30] 函数返回状态码
来源：http://dali.dashuyun.cn/Article/details/gtkuxnyqbt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gaohongyu789.top/Article/details/gtushrpzgc.html

[R31] 局部变量
来源：http://dali.zhongyouzk.top/Article/details/gtzzkrgrix.html

f() { local x=1; echo "$x"; }
来源：http://dali.svipenyu.cn/Article/details/gtbtbahgzo.html

[R32] 参数个数校验
来源：http://dali.iojbl.cn/Article/details/gteeotymwn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenzaomai.com/Article/details/gtvvctaptw.html

[R33] 捕获错误并提示行号
来源：http://dali.hnxiangtu.top/Article/details/gtlammqxyd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xylfe.cn/Article/details/gtjgmcwlnw.html

[R34] 退出时清理
来源：http://dali.yueranfly.top/Article/details/gtnykalgeu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gtfcoiagwv.html

[R35] 后台执行并等待
来源：http://dali.sxryk.cn/Article/details/gthscsiepo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guannengcc.top/Article/details/gtwyefbfch.html

[R36] 并发执行多个任务
来源：http://dali.xinyue.icu/Article/details/gtrduhmfoz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xinyue.icu/Article/details/gtkysxcgjm.html

[R37] 把输出赋给变量
来源：http://dali.yj20258.top/Article/details/gtvsbwhaku.html

files=$(ls -1)
来源：http://dali.daxiang520.top/Article/details/gtcjiyymnf.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gttwvajalq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenlongwang.top/Article/details/gtxtsmsdgn.html

[R39] 重定向标准输出与错误
来源：http://dali.xylfe.cn/Article/details/gtvequrbsa.html

cmd > out.log 2>&1
来源：http://dali.jianghu66.top/Article/details/gttysyoneu.html

[R40] 追加写日志
来源：http://dali.xylfe.cn/Article/details/gtrwhulkjc.html

echo "log" >> out.log
来源：http://dali.sweek.top/Article/details/gtlihhcxcx.html

[R41] 丢弃输出
来源：http://dali.cashguo.top/Article/details/gtqnhfbvdx.html

cmd >/dev/null 2>&1
来源：http://dali.guowangkeji.top/Article/details/gtvofkllen.html

[R42] 输入重定向
来源：http://dali.nanxuanxn.top/Article/details/gtuowsbxjf.html

wc -l < a.txt
来源：http://dali.aibaodan.cn/Article/details/gtwjbjavft.html

[R43] 按名字查找文件
来源：http://dali.jiagoushi.top/Article/details/gtjgdhhtth.html

find . -name "*.log" -type f
来源：http://dali.sweek.top/Article/details/gtmulxnzky.html

[R44] 按修改时间查找
来源：http://dali.sweek.top/Article/details/gtqzgxtsyd.html

find . -mtime -7 -type f
来源：http://dali.hysaishi.cn/Article/details/gtvkdczdcb.html

[R45] 批量删除
来源：http://dali.daxiang520.top/Article/details/gttekwslcm.html

find . -name "*.tmp" -delete
来源：http://dali.sufxvd.cn/Article/details/gthzwbetia.html

[R46] 递归替换文件内容
来源：http://dali.quarkkingdee.top/Article/details/gtmstlcqpe.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenzaomai.com/Article/details/gtunisckvr.html

[R47] sed 单行替换
来源：http://dali.hnqzz.top/Article/details/gtfywfqevj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbuvokomh.html

[R48] awk 取指定列
来源：http://dali.ehwqpu.com/Article/details/gtfylylvee.html

awk '{print $1, $3}' a.txt
来源：http://dali.jianghu66.top/Article/details/gtkzrzvfhm.html

[R49] awk 带条件
来源：http://dali.mhx1999.top/Article/details/gtcvuhpjnq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zdqjudy.top/Article/details/gtfcptupjk.html

[R50] awk 求和
来源：http://dali.c1oappe.top/Article/details/gtoynrcura.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jiagoushi.top/Article/details/gthttxlwfz.html

[R51] 排序去重取前几
来源：http://dali.fzhhl.top/Article/details/gtqwwjwqnl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.mhx1999.top/Article/details/gtcfeompiv.html

[R52] 统计行数
来源：http://dali.tian-w.cn/Article/details/gtideoagsf.html

wc -l a.txt
来源：http://dali.chenzaomai.com/Article/details/gtekgyqvvr.html

[R53] 查看文件头与实时尾
来源：http://dali.svipenyu.cn/Article/details/gtywyvdjmn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guannengcc.top/Article/details/gtnunupstv.html

[R54] 比较两个文件
来源：http://dali.yanxiufei.cn/Article/details/gtwchuaaks.html

diff a.txt b.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtprtwbyct.html

[R55] 压缩与解压
来源：http://dali.feifeiyinyue.top/Article/details/gtbvipzjcg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.andypj.xyz/Article/details/gtilifpzyl.html

[R56] 远程拷贝
来源：http://dali.xuanzx.com/Article/details/gtzmxollwx.html

scp file user@host:/path/
来源：http://dali.gogol.net.cn/Article/details/gtoxwyksyf.html

[R57] 远程执行命令
来源：http://dali.yanxiufei.cn/Article/details/gtnkqmwzoj.html

ssh user@host 'uptime'
来源：http://dali.jiagoushi.top/Article/details/gtmxzldwfl.html

[R58] 下载文件
来源：http://dali.yj20258888.top/Article/details/gtolywbhio.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jiagoushi.top/Article/details/gtsexarkgp.html

[R59] 发 POST JSON
来源：http://dali.daxiang520.top/Article/details/gtzrdjntxx.html


<!-- 参考信息 -->