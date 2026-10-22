代发 wailian999

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenlongwang.top/Article/details/gtyzxqmjhh.html

[Q11] 一次插入多行
来源：http://dali.vqdsnc.cn/Article/details/gthztppnyz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gtiigjsojs.html

[Q12] 插入后取自增 ID
来源：http://dali.daria6918.cn/Article/details/gtjstrnmcf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yvedp.cn/Article/details/gtalethkkb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hnxiangtu.top/Article/details/gtczfbjmrm.html

[Q13] 忽略重复插入
来源：http://dali.quarkkingdee.top/Article/details/gtodpsngor.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gtbpoqahhb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zdqjudy.top/Article/details/gtyodvovch.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hongshengwenyu.top/Article/details/gtcmcehfxy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hammf.cn/Article/details/gtnhrleici.html

[Q15] 查询全部
来源：http://dali.haohaochexian.top/Article/details/gtqwkjzgxv.html

SELECT * FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtmloihuci.html

[Q16] 查询指定列
来源：http://dali.bjfxy.top/Article/details/gthrjmskop.html

SELECT id, name FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtrgkvvexs.html

[Q17] 条件查询
来源：http://dali.hysaishi.cn/Article/details/gtohzxzrhr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yuanzhike.top/Article/details/gtfrujdhbx.html

[Q18] 模糊匹配
来源：http://dali.gaohongyu789.top/Article/details/gtqlvzgura.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.c1oappe.top/Article/details/gtmidudpgd.html

[Q19] 范围查询
来源：http://dali.cucudq.cn/Article/details/gtgkxdbxkr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenjidiqi.icu/Article/details/gtaufyaosi.html

[Q20] IN 列表
来源：http://dali.cucudq.cn/Article/details/gtvnyhtrhp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hnqzz.top/Article/details/gtzfeflgfd.html

[Q21] 空值判断
来源：http://dali.zdqjudy.top/Article/details/gtelhslqii.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.9152youxi.cn/Article/details/gthavuypja.html

[Q22] 排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtibxzkxys.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.smart0.xyz/Article/details/gtthfkflyo.html

[Q23] 分页
来源：http://dali.xylfe.cn/Article/details/gttgfruydm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zdqjudy.top/Article/details/gtjneclwzu.html

[Q24] 去重
来源：http://dali.c1oappe.top/Article/details/gtfubhndju.html

SELECT DISTINCT city FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtuqbnvtxe.html

[Q25] 只取前 N 条
来源：http://dali.jiagoushi.top/Article/details/gttkkzzlav.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenjidiqi.icu/Article/details/gtbwnxsspp.html

[Q26] 计数
来源：http://dali.meibo888.top/Article/details/gtvrjkxbde.html

SELECT COUNT(*) FROM users;
来源：http://dali.sweek.top/Article/details/gthfnrzwgt.html

[Q27] 条件计数
来源：http://dali.xuanzx.com/Article/details/gtjknthtde.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gttfoeyxrn.html

[Q28] 求和与平均
来源：http://dali.kuanghao11.cn/Article/details/gtgzwiujtp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gthwxarxyy.html

[Q29] 最大最小值
来源：http://dali.iojbl.cn/Article/details/gtkqwovtxn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtqyivtbol.html

[Q30] 分组统计
来源：http://dali.hysaishi.cn/Article/details/gtbduuifdr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtyanopizd.html

[Q31] 分组后过滤
来源：http://dali.hongshengwenyu.top/Article/details/gteschnqpl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.havefunace.top/Article/details/gtzbyennni.html

[Q32] 分组拼接字符串
来源：http://dali.hammf.cn/Article/details/gtuuxdopdc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtaojfvele.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.daria6918.cn/Article/details/gtqnegqbfw.html

[Q33] 多列分组
来源：http://dali.sxryk.cn/Article/details/gttdciolax.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xuanzx.com/Article/details/gtpyvcwtlt.html

[Q34] 每组取第一条
来源：http://dali.hysaishi.cn/Article/details/gtcoixscsz.html

SELECT * FROM (
来源：http://dali.hnxiangtu.top/Article/details/gtsgafghzi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xuetiantiany.cn/Article/details/gtscyoeshp.html

) t WHERE rn = 1;
来源：http://dali.sufxvd.cn/Article/details/gtumsvqlmk.html

[Q35] 内连接
来源：http://dali.shangyingyoupin.top/Article/details/gtzjwvzedd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ppjwa.cn/Article/details/gtlrviiaof.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gtbzmtalir.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhengqikj.top/Article/details/gthwmxjudq.html

[Q37] 右连接
来源：http://dali.sysykeji.top/Article/details/gtsmvzzlye.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.guannengcc.top/Article/details/gtgboqgugy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hysaishi.cn/Article/details/gtoksooctw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.quarkkingdee.top/Article/details/gtuchelugf.html

[Q39] 自连接（查上下级）
来源：http://dali.svipenyu.cn/Article/details/gttchpsjfa.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinqigfzy.top/Article/details/gtsfqhkvrj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.snrcjt.cn/Article/details/gtyyxcqbsg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jianghu66.top/Article/details/gtxwrmxgvg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenlongwang.top/Article/details/gtpddcummq.html

[Q41] 多表连接
来源：http://dali.iojbl.cn/Article/details/gtaitjjgeb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhixingplan.top/Article/details/gtfsqmraqh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.dashuyun.cn/Article/details/gtoraywfec.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjzskaea.html

[Q42] 连接条件附加过滤
来源：http://dali.tianlin.xyz/Article/details/gtkqqbupex.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdravoeqv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zycfv.cn/Article/details/gtufbwskck.html

[Q43] 标量子查询
来源：http://dali.zdqjudy.top/Article/details/gtcpusxatx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yueranfly.top/Article/details/gtcixzykfe.html

[Q44] IN 子查询
来源：http://dali.redwolf501.top/Article/details/gtvyupbrpb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yuxming.cn/Article/details/gtubkbfqyp.html

[Q45] EXISTS 判断存在
来源：http://dali.nwbrower.top/Article/details/gtpmcbpfon.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.svipenyu.cn/Article/details/gtvzaybmdk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.vqdsnc.cn/Article/details/gtvkfzopuc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigfzy.top/Article/details/gtwuttmyky.html

[Q47] 与平均值比较
来源：http://dali.gzhubu.top/Article/details/gtxrraytkk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinghuilouyu.cn/Article/details/gteklxetsd.html

[Q48] CTE 公用表表达式
来源：http://dali.haohaochexian.top/Article/details/gtvkzdkctk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hammf.cn/Article/details/gteubgoowz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jiagoushi.top/Article/details/gtljxgrhna.html

[Q49] 更新单行
来源：http://dali.redwolf501.top/Article/details/gtptpvzkzl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gtqzldxxwm.html

[Q50] 批量更新
来源：http://dali.hfpthk.cn/Article/details/gtnfgdcztc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guannengcc.top/Article/details/gtaxamtnau.html

[Q51] 用子查询更新
来源：http://dali.shangyingyoupin.top/Article/details/gtkrdrcdls.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.316326.xyz/Article/details/gtwpbqtygp.html

[Q52] 删除指定行
来源：http://dali.vqdsnc.cn/Article/details/gtsobakgwu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gtzwlykagm.html

[Q53] 按条件删除
来源：http://dali.hnxiangtu.top/Article/details/gthrymcvym.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gtqtcnjyix.html

[Q54] 清空表
来源：http://dali.hnqzz.top/Article/details/gtjhgvyryd.html

TRUNCATE TABLE logs;
来源：http://dali.tanke756.top/Article/details/gtjjdbwbto.html

[Q55] 排名（并列占位）
来源：http://dali.zhoulong.xyz/Article/details/gtwsbsivqd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gtlfsfhqey.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhoulong.xyz/Article/details/gtsbqsfmzz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhoulong.xyz/Article/details/gtqolvdvdb.html

[Q57] 行号
来源：http://dali.zhiwuduotai.top/Article/details/gtkowfyewb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtzakilgsy.html

[Q58] 累计求和
来源：http://dali.vqdsnc.cn/Article/details/gtbxqisvei.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbiwidrkz.html

[Q59] 分组内累计
来源：http://dali.gotoacloud.top/Article/details/gtzepjvahj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gttmcedbrt.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhixingplan.top/Article/details/gtenmnazgk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yvedp.cn/Article/details/gtcioqgteh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pycfn.com/Article/details/gtufnjclqt.html

[Q61] 移动平均
来源：http://dali.chenjidiqi.icu/Article/details/gttousnuek.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtbewdynvn.html

[Q62] 分组占比
来源：http://dali.9152youxi.cn/Article/details/gtykhouejz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gtwdkaugtw.html

[Q63] 开启事务
来源：http://dali.tanke756.top/Article/details/gtijfwmjao.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fengsongda.top/Article/details/gtfwwtfqzy.html

[Q64] 提交事务
来源：http://dali.sufxvd.cn/Article/details/gtqzwapfrb.html

COMMIT;
来源：http://dali.redwolf501.top/Article/details/gtgaxqvopn.html

[Q65] 回滚事务
来源：http://dali.shangyingyoupin.top/Article/details/gtwvrjpkrc.html

ROLLBACK;
来源：http://dali.zhoulong.xyz/Article/details/gtgliixcfe.html

[Q66] 行锁查询
来源：http://dali.yuxming.cn/Article/details/gtcugboayo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuanzhike.top/Article/details/gtpdcvtdir.html

[Q67] 设置隔离级别
来源：http://dali.gaohongyu789.top/Article/details/gtbaolbabl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ivvv.top/Article/details/gtwagnxuaw.html

[Q68] 保存点
来源：http://dali.zhixingplan.top/Article/details/gtgosxmgkk.html

SAVEPOINT sp1;
来源：http://dali.yangfankeji.com/Article/details/gtxafljvrt.html

ROLLBACK TO sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrapkqow.html

[Q69] 查看执行计划
来源：http://dali.c1oappe.top/Article/details/gtmbhxvgnh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yangfankeji.com/Article/details/gtxxxlernh.html

[Q70] 更新统计信息
来源：http://dali.redwolf501.top/Article/details/gtiynemfeg.html

ANALYZE TABLE users;
来源：http://dali.shangyingyoupin.top/Article/details/gtvijfpezs.html

[Q71] 查看建表语句
来源：http://dali.hnqzz.top/Article/details/gtisdwsqqx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ppjwa.cn/Article/details/gtholswgsf.html

[Q72] 查看索引
来源：http://dali.fengsongda.top/Article/details/gtaqhijzxb.html

SHOW INDEX FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtjejandyo.html

[Q73] 查看表状态
来源：http://dali.zhixingplan.top/Article/details/gtsghkcffo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yongpay.top/Article/details/gtzhqugmdg.html

[Q74] 强制使用索引
来源：http://dali.gzhubu.top/Article/details/gtivbwowts.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.mhx1999.top/Article/details/gtulmxmakf.html

[Q75] 日期格式化
来源：http://dali.fengsongda.top/Article/details/gtdkigfaff.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtnkczbwuy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhixingplan.top/Article/details/gtuszpssgv.html

[Q76] 按天统计
来源：http://dali.guannengcc.top/Article/details/gtenkucnsx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aibaodan.cn/Article/details/gtkeupxodg.html

[Q77] 时间加减
来源：http://dali.kuanghao11.cn/Article/details/gtkdkvzvad.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gotoacloud.top/Article/details/gtbqhengng.html

[Q78] 当前时间
来源：http://dali.vqdsnc.cn/Article/details/gtgnfuzlvh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ybcxt.top/Article/details/gtvpzlpjys.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gteyklfzxp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.fengsongda.top/Article/details/gtbjzoqqpi.html

[Q80] 字符串截取
来源：http://dali.redwolf501.top/Article/details/gtsptginsa.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtpzhlexda.html

[Q81] 字符串替换
来源：http://dali.nanxinkj.top/Article/details/gtwqevkqyx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xziqi.cn/Article/details/gtqeyfbxmf.html

[Q82] 字符长度与字节长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtittcqgcc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtiekcoaxn.html

[Q83] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gtgiqqperl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxnyzsxs.html

[Q84] 去除首尾空格
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzmcqdaf.html

SELECT TRIM(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtleqybdkl.html

[Q85] 数值取整
来源：http://dali.sxryk.cn/Article/details/gtqicoivik.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.birdmap.top/Article/details/gtjvuymlav.html

[Q86] 读取 JSON 字段
来源：http://dali.quarkkingdee.top/Article/details/gtybbtwdvq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258888.top/Article/details/gtkvntkvgu.html

[Q87] JSON 字段做条件
来源：http://dali.shangyingyoupin.top/Article/details/gtgpkpwznk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.fzhhl.top/Article/details/gtkdhxdfan.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhengqikj.top/Article/details/gtmbwznbmd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.smart0.xyz/Article/details/gtuaixtqhj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtkiqjuqqz.html

[Q89] 判断表是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwfmgyuk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daxiang520.top/Article/details/gtcecdqusm.html

[Q90] 生成序号列
来源：http://dali.guannengcc.top/Article/details/gtnsxbbthc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sysykeji.top/Article/details/gtgqxwtrpv.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtxjizqekk.html

R. Bash 专题
来源：http://dali.yuxming.cn/Article/details/gtnjdhwkzl.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtdctoudpf.html

[R01] shebang 与严格模式
来源：http://dali.guannengcc.top/Article/details/gtayqqssfs.html

#!/usr/bin/env bash
来源：http://dali.yuxming.cn/Article/details/gtyjmqrgsm.html

set -euo pipefail
来源：http://dali.fzhhl.top/Article/details/gtmowhtacc.html

[R02] 变量赋值与使用
来源：http://dali.zhixingplan.top/Article/details/gtayltyyin.html

name="Tom"; echo "$name"
来源：http://dali.shangyingyoupin.top/Article/details/gtioqefueo.html

[R03] 只读变量
来源：http://dali.9152youxi.cn/Article/details/gtrxfcntxw.html

readonly PI=3.14
来源：http://dali.meibo888.top/Article/details/gtioqijfco.html

[R04] 位置参数
来源：http://dali.pycfn.com/Article/details/gtjsutjeja.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.redwolf501.top/Article/details/gtrbfagdhl.html

[R05] 参数默认值
来源：http://dali.wangshuangyany.cn/Article/details/gtoxlykstj.html

name="${1:-default}"
来源：http://dali.gaohongyu789.top/Article/details/gthoecuced.html

[R06] 判断命令是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gtubgyybiq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gtczrdftxi.html

[R07] if 判断文件
来源：http://dali.yvedp.cn/Article/details/gtxqwhweyh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtkhhqdtbx.html

[R08] 数值比较
来源：http://dali.chenzaomai.com/Article/details/gtfcwjewzh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sufxvd.cn/Article/details/gtargdbpmn.html

[R09] 字符串比较
来源：http://dali.hongshengwenyu.top/Article/details/gtxprttpbg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ppjwa.cn/Article/details/gtxzlvbegf.html

[R10] 正则匹配
来源：http://dali.yuxming.cn/Article/details/gtymbdbyjh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cqqwz.cn/Article/details/gtxfxtrxdp.html

[R11] case 多分支
来源：http://dali.yvedp.cn/Article/details/gtssjzratu.html

case "$1" in
来源：http://dali.vqdsnc.cn/Article/details/gtomeagobo.html

start) echo "启动" ;;
来源：http://dali.xuanzx.com/Article/details/gtlqsxiijg.html

stop)  echo "停止" ;;
来源：http://dali.aibaodan.cn/Article/details/gtarqdoshn.html

*)     echo "未知命令" ;;
来源：http://dali.cdnleiting.top/Article/details/gtmzqbrcol.html

esac
来源：http://dali.feifeiyinyue.top/Article/details/gtoighvpdn.html

[R12] for 遍历文件
来源：http://dali.shuidangran.top/Article/details/gtqvteqdkn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jqgufenzy.top/Article/details/gtijmwnkah.html

[R13] for 计数循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzzggjrm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gtrwvoaoma.html

[R14] C 风格 for
来源：http://dali.yvedp.cn/Article/details/gtcqukygci.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gtiswrotpq.html

[R15] while 逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtishopsxq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nanxinkj.top/Article/details/gtqvpjxsiv.html

[R16] until 等待条件
来源：http://dali.ppjwa.cn/Article/details/gthkkqooxq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gtaplkrlpt.html

[R17] 数组定义与取值
来源：http://dali.wangshuangyany.cn/Article/details/gtpgswfcil.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gtwazwhfac.html

[R18] 遍历数组
来源：http://dali.yuxming.cn/Article/details/gtftsaicez.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ppjwa.cn/Article/details/gtjfiuunje.html

[R19] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gtfosexbil.html

echo "${#arr[@]}"
来源：http://dali.wangdashe.top/Article/details/gtiwcytbkf.html

[R20] 关联数组（字典）
来源：http://dali.ehwqpu.com/Article/details/gtwdvyvlvp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtukcjdlzi.html

[R21] 字符串长度
来源：http://dali.tanke756.top/Article/details/gtooqvtcvg.html

echo "${#s}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpacxwlu.html

[R22] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gtxxdinaie.html

echo "${s:0:5}"
来源：http://dali.nwbrower.top/Article/details/gtkxiszllm.html

[R23] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gtvrcosgyb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenjidiqi.icu/Article/details/gttscnafrn.html

[R24] 大小写转换
来源：http://dali.yuanzhike.top/Article/details/gtoxfpgxzl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yongpay.top/Article/details/gtfinqdzuf.html

[R25] 去后缀 / 去前缀
来源：http://dali.zycfv.cn/Article/details/gtbhnlbnxw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.daxiang520.top/Article/details/gtyndstvee.html

[R26] 命令替换
来源：http://dali.jianghu66.top/Article/details/gtkwgdjplx.html

now=$(date +%F); echo "$now"
来源：http://dali.vqdsnc.cn/Article/details/gtliivdsyj.html

[R27] 算术展开
来源：http://dali.c1oappe.top/Article/details/gtzsukemre.html

echo $((1 + 2 * 3))
来源：http://dali.yangfankeji.com/Article/details/gtmagkngww.html

[R28] 浮点运算
来源：http://dali.andypj.xyz/Article/details/gtubrlabna.html

echo "scale=2; 10/3" | bc
来源：http://dali.ppjwa.cn/Article/details/gttenkadst.html

[R29] 定义函数
来源：http://dali.sweek.top/Article/details/gtrsdfufjv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrutgtfyd.html

[R30] 函数返回状态码
来源：http://dali.bjfxy.top/Article/details/gtdeqwnhfo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.iojbl.cn/Article/details/gtsrlqwkya.html

[R31] 局部变量
来源：http://dali.yj20258888.top/Article/details/gthgkmyzad.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnqzz.top/Article/details/gtbxiuuwui.html

[R32] 参数个数校验
来源：http://dali.zhiwuduotai.top/Article/details/gtmqnwnqzd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gtwlkirjbi.html

[R33] 捕获错误并提示行号
来源：http://dali.jianghu66.top/Article/details/gtmhihodaj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmmgtmqg.html

[R34] 退出时清理
来源：http://dali.hfpthk.cn/Article/details/gtzovnxmmz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gtmomcveoq.html

[R35] 后台执行并等待
来源：http://dali.tianlin.xyz/Article/details/gtlpamgawn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoryplhdt.html

[R36] 并发执行多个任务
来源：http://dali.mhx1999.top/Article/details/gthygqjlcp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yvedp.cn/Article/details/gtwlrxgswo.html

[R37] 把输出赋给变量
来源：http://dali.jiagoushi.top/Article/details/gtnzvasexc.html

files=$(ls -1)
来源：http://dali.tianlin.xyz/Article/details/gthruclwsf.html

[R38] 管道串联
来源：http://dali.gotoacloud.top/Article/details/gtrkiehdjn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuanzhike.top/Article/details/gthddoiknz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhengqikj.top/Article/details/gtuivaltme.html

cmd > out.log 2>&1
来源：http://dali.snrcjt.cn/Article/details/gtouxenxda.html

[R40] 追加写日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwfewxnc.html

echo "log" >> out.log
来源：http://dali.0kj1m.cn/Article/details/gtsomymrnx.html

[R41] 丢弃输出
来源：http://dali.hammf.cn/Article/details/gtybjbrsmh.html

cmd >/dev/null 2>&1
来源：http://dali.shuidangran.top/Article/details/gtypgfxqnu.html

[R42] 输入重定向
来源：http://dali.yj202588.top/Article/details/gtjykfllsh.html

wc -l < a.txt
来源：http://dali.hywenlv.cn/Article/details/gtdqlaspte.html

[R43] 按名字查找文件
来源：http://dali.sysykeji.top/Article/details/gtvfasbhbi.html

find . -name "*.log" -type f
来源：http://dali.jyoumei.cn/Article/details/gtrdmoaclp.html

[R44] 按修改时间查找
来源：http://dali.sufxvd.cn/Article/details/gtgulqvout.html

find . -mtime -7 -type f
来源：http://dali.quarkkingdee.top/Article/details/gtwwskpnzp.html

[R45] 批量删除
来源：http://dali.pengpengdd.cyou/Article/details/gtmvufnkdx.html

find . -name "*.tmp" -delete
来源：http://dali.hysaishi.cn/Article/details/gtggrgvfec.html

[R46] 递归替换文件内容
来源：http://dali.yonumen.top/Article/details/gtrbiwsluq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sysykeji.top/Article/details/gtpvjksecy.html

[R47] sed 单行替换
来源：http://dali.bjfxy.top/Article/details/gtippqtthg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.wangdashe.top/Article/details/gtxueovpha.html

[R48] awk 取指定列
来源：http://dali.cashguo.top/Article/details/gtfpgiasui.html

awk '{print $1, $3}' a.txt
来源：http://dali.gotoacloud.top/Article/details/gtsexxnyau.html

[R49] awk 带条件
来源：http://dali.chenlongwang.top/Article/details/gteshbsacs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgufenzy.top/Article/details/gtasrczwxh.html

[R50] awk 求和
来源：http://dali.gzhubu.top/Article/details/gtqdyoaxjp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pycfn.com/Article/details/gtbuqilmfj.html

[R51] 排序去重取前几
来源：http://dali.xuanzx.com/Article/details/gtdkjibitm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cashguo.top/Article/details/gtogrfxtzx.html

[R52] 统计行数
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmtkmthb.html

wc -l a.txt
来源：http://dali.yuanzhike.top/Article/details/gteixixvao.html

[R53] 查看文件头与实时尾
来源：http://dali.ehwqpu.com/Article/details/gthgcflwzc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdzygkndj.html

[R54] 比较两个文件
来源：http://dali.nwbrower.top/Article/details/gtctoctxgc.html

diff a.txt b.txt
来源：http://dali.yvedp.cn/Article/details/gteznowlxu.html

[R55] 压缩与解压
来源：http://dali.gzhubu.top/Article/details/gtalabmzcp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.redwolf501.top/Article/details/gtcirtsvlp.html

[R56] 远程拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gtnlawighd.html

scp file user@host:/path/
来源：http://dali.kuanghao11.cn/Article/details/gtadnrxrmj.html

[R57] 远程执行命令
来源：http://dali.yueranfly.top/Article/details/gtrpfeaxem.html

ssh user@host 'uptime'
来源：http://dali.hfpthk.cn/Article/details/gtyuqiqucq.html

[R58] 下载文件
来源：http://dali.yonumen.top/Article/details/gthwuugcvo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ybcxt.top/Article/details/gtmkotrbmf.html

[R59] 发 POST JSON
来源：http://dali.fengsongda.top/Article/details/gtiivncyzu.html


<!-- 参考信息 -->