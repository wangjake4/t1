代发 wailian999

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gt2kuyileyf.html

[Q09] 创建唯一索引
来源：http://dali.xylfe.cn/Article/details/gt2arqnnlfn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tian-w.cn/Article/details/gt2cmazullb.html

[Q10] 插入单行
来源：http://dali.yj20258888.top/Article/details/gt2sffkalqy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.aibaodan.cn/Article/details/gt2hrwzadli.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2retyxohb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hfpthk.cn/Article/details/gt2tzwkshlv.html

[Q12] 插入后取自增 ID
来源：http://dali.havefunace.top/Article/details/gt2qwmqwaur.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhiwuduotai.top/Article/details/gt2wmyjkaak.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zycfv.cn/Article/details/gt2mfnvwnja.html

[Q13] 忽略重复插入
来源：http://dali.aizwys.cn/Article/details/gt2hjhpxtxa.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.meibo888.top/Article/details/gt2vcwklcvh.html

[Q14] 存在则更新（upsert）
来源：http://dali.aizwys.cn/Article/details/gt2pzgwxrbz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhoulong.xyz/Article/details/gt2mpmyvhzn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tanke756.top/Article/details/gt2iykqmzco.html

[Q15] 查询全部
来源：http://dali.sysykeji.top/Article/details/gt2masylvwj.html

SELECT * FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2hkvoiwgd.html

[Q16] 查询指定列
来源：http://dali.yuxming.cn/Article/details/gt2riihtwid.html

SELECT id, name FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fpvqtcyn.html

[Q17] 条件查询
来源：http://dali.dashuyun.cn/Article/details/gt2lvssbcxv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.vqdsnc.cn/Article/details/gt2akajqbgl.html

[Q18] 模糊匹配
来源：http://dali.redwolf501.top/Article/details/gt2aupjdgxs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.svipenyu.cn/Article/details/gt2eydfzpkg.html

[Q19] 范围查询
来源：http://dali.dianchejie.cn/Article/details/gt2uvhtzudm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xziqi.cn/Article/details/gt2ellkezqk.html

[Q20] IN 列表
来源：http://dali.yj20258.top/Article/details/gt2chxjcmem.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.birdmap.top/Article/details/gt2ysmrpicb.html

[Q21] 空值判断
来源：http://dali.yvedp.cn/Article/details/gt2jxoxwuqy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.guowangkeji.top/Article/details/gt2ooujewoz.html

[Q22] 排序
来源：http://dali.yueranfly.top/Article/details/gt2xzfcnegt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ybcxt.top/Article/details/gt2wkqafsni.html

[Q23] 分页
来源：http://dali.sxryk.cn/Article/details/gt2chngadjk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hongshengwenyu.top/Article/details/gt2oyjbhjpg.html

[Q24] 去重
来源：http://dali.guowangkeji.top/Article/details/gt2hfwginqo.html

SELECT DISTINCT city FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2ffkklcut.html

[Q25] 只取前 N 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kxtxxugs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.feifeiyinyue.top/Article/details/gt2nzubifsj.html

[Q26] 计数
来源：http://dali.smart0.xyz/Article/details/gt2uwjpdamx.html

SELECT COUNT(*) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2ktwnmcok.html

[Q27] 条件计数
来源：http://dali.yj202588.top/Article/details/gt2fwnegiwy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2lxtnfwek.html

[Q28] 求和与平均
来源：http://dali.cashguo.top/Article/details/gt2ohgfmrcr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2kkzxuvij.html

[Q29] 最大最小值
来源：http://dali.kuanghao11.cn/Article/details/gt2nnlnrrdy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dacpqcwc.html

[Q30] 分组统计
来源：http://dali.dashuyun.cn/Article/details/gt2twblhuth.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gt2quddnjaa.html

[Q31] 分组后过滤
来源：http://dali.9152youxi.cn/Article/details/gt2tuodmtpr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.havefunace.top/Article/details/gt2rpacpvhp.html

[Q32] 分组拼接字符串
来源：http://dali.tian-w.cn/Article/details/gt2vcnlrrxq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gt2qhxwafzx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.316326.xyz/Article/details/gt2diacjwze.html

[Q33] 多列分组
来源：http://dali.yj202588.top/Article/details/gt2vwdifxra.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hnqzz.top/Article/details/gt2wbngzewf.html

[Q34] 每组取第一条
来源：http://dali.guowangkeji.top/Article/details/gt2lyfllgkt.html

SELECT * FROM (
来源：http://dali.mhx1999.top/Article/details/gt2tkhsvarm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.redwolf501.top/Article/details/gt2vbnmqvhc.html

) t WHERE rn = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2qrpctiaw.html

[Q35] 内连接
来源：http://dali.wangshuangyany.cn/Article/details/gt2ijzqtsxn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gt2ighwtean.html

[Q36] 左连接
来源：http://dali.yanxiufei.cn/Article/details/gt2lplkbieg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2bhpqaegw.html

[Q37] 右连接
来源：http://dali.redwolf501.top/Article/details/gt2lzoqomts.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gogol.net.cn/Article/details/gt2qxlcngfh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.iojbl.cn/Article/details/gt2lsljgdyp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinqigufen.top/Article/details/gt2yiaovvgt.html

[Q39] 自连接（查上下级）
来源：http://dali.cheryme.top/Article/details/gt2xycosfiu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hfpthk.cn/Article/details/gt2tndewfee.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hysaishi.cn/Article/details/gt2zngjydgi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xuetiantiany.cn/Article/details/gt2fpsklpqi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhengqikj.top/Article/details/gt2msjsmutz.html

[Q41] 多表连接
来源：http://dali.jyoumei.cn/Article/details/gt2gpiervhf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.birdmap.top/Article/details/gt2kxpbvrmx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinqigfzy.top/Article/details/gt2zisoecgi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuetiantiany.cn/Article/details/gt2zhrhihag.html

[Q42] 连接条件附加过滤
来源：http://dali.snrcjt.cn/Article/details/gt2cfsskunt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gogol.net.cn/Article/details/gt2qxssqcwp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenjidiqi.icu/Article/details/gt2oxqefdrp.html

[Q43] 标量子查询
来源：http://dali.havefunace.top/Article/details/gt2owaljzmj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sysykeji.top/Article/details/gt2naaftsgh.html

[Q44] IN 子查询
来源：http://dali.chenjidiqi.icu/Article/details/gt2fvmbvkrj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nanxuanxn.top/Article/details/gt2odzoxxub.html

[Q45] EXISTS 判断存在
来源：http://dali.ivvv.top/Article/details/gt2lbkvqcqw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cdnleiting.top/Article/details/gt2yhlgytgi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.mhx1999.top/Article/details/gt2rpkopuby.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gt2ahfyspdk.html

[Q47] 与平均值比较
来源：http://dali.jinqigufen.top/Article/details/gt2qypzpmpw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cheryme.top/Article/details/gt2gyluwbek.html

[Q48] CTE 公用表表达式
来源：http://dali.andypj.xyz/Article/details/gt2mpbrlpno.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sweek.top/Article/details/gt2dxhnbbwf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hfpthk.cn/Article/details/gt2galkfxpd.html

[Q49] 更新单行
来源：http://dali.svipenyu.cn/Article/details/gt2sxfzgmkq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xziqi.cn/Article/details/gt2ifabwmvi.html

[Q50] 批量更新
来源：http://dali.dashuyun.cn/Article/details/gt2qoqkzsvt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zycfv.cn/Article/details/gt2vtkxwuhp.html

[Q51] 用子查询更新
来源：http://dali.vqdsnc.cn/Article/details/gt2asqbvjgl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2ugpsqnxj.html

[Q52] 删除指定行
来源：http://dali.aibaodan.cn/Article/details/gt2yzbqqiec.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ybcxt.top/Article/details/gt2sdrwtrif.html

[Q53] 按条件删除
来源：http://dali.vqdsnc.cn/Article/details/gt2zgbnjies.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tianlin.xyz/Article/details/gt2fudqqxoc.html

[Q54] 清空表
来源：http://dali.birdmap.top/Article/details/gt2gbvxjuzc.html

TRUNCATE TABLE logs;
来源：http://dali.jqgfzy.top/Article/details/gt2rvbaalic.html

[Q55] 排名（并列占位）
来源：http://dali.chenjidiqi.icu/Article/details/gt2nxbthwau.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xziqi.cn/Article/details/gt2qxbrxshf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.daria6918.cn/Article/details/gt2csayachb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cashguo.top/Article/details/gt2jjweibyc.html

[Q57] 行号
来源：http://dali.chenlongwang.top/Article/details/gt2wusbmkwe.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.316326.xyz/Article/details/gt2jqqoaadw.html

[Q58] 累计求和
来源：http://dali.ydzc1.top/Article/details/gt2iukmvxrr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.bjfxy.top/Article/details/gt2zbscexuw.html

[Q59] 分组内累计
来源：http://dali.iojbl.cn/Article/details/gt2dixtulxh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2krfbrbvl.html

[Q60] 取上一行 / 下一行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jhgtizpr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.vqdsnc.cn/Article/details/gt2oknvpwmb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gt2wdxjkjpj.html

[Q61] 移动平均
来源：http://dali.jiagoushi.top/Article/details/gt2izyjrada.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2muwyeqqm.html

[Q62] 分组占比
来源：http://dali.jianghu66.top/Article/details/gt2esamqjly.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2exmjdhwy.html

[Q63] 开启事务
来源：http://dali.yangfankeji.com/Article/details/gt2pjosswcj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenjidiqi.icu/Article/details/gt2njhgofpz.html

[Q64] 提交事务
来源：http://dali.meibo888.top/Article/details/gt2wokimvfl.html

COMMIT;
来源：http://dali.chenzaomai.com/Article/details/gt2nwqanodp.html

[Q65] 回滚事务
来源：http://dali.shuidangran.top/Article/details/gt2uzkziedj.html

ROLLBACK;
来源：http://dali.jiagoushi.top/Article/details/gt2zfuycimt.html

[Q66] 行锁查询
来源：http://dali.ivvv.top/Article/details/gt2zxeastwq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ikynkhxd.html

[Q67] 设置隔离级别
来源：http://dali.zhongyouzk.top/Article/details/gt2iypqsyhz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxuanxn.top/Article/details/gt2xugdtpue.html

[Q68] 保存点
来源：http://dali.chenlongwang.top/Article/details/gt2vfgankqa.html

SAVEPOINT sp1;
来源：http://dali.gzhubu.top/Article/details/gt2wjacdmzn.html

ROLLBACK TO sp1;
来源：http://dali.yvedp.cn/Article/details/gt2xtiryyqr.html

[Q69] 查看执行计划
来源：http://dali.cheryme.top/Article/details/gt2tbupnhjn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gotoacloud.top/Article/details/gt2woaiopst.html

[Q70] 更新统计信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2phhhwfkm.html

ANALYZE TABLE users;
来源：http://dali.jinqigfzy.top/Article/details/gt2gbllyebs.html

[Q71] 查看建表语句
来源：http://dali.zycfv.cn/Article/details/gt2xksupcdn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhiwuduotai.top/Article/details/gt2tfeoczmy.html

[Q72] 查看索引
来源：http://dali.svipenyu.cn/Article/details/gt2ljlxjjcj.html

SHOW INDEX FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2bwuhzemz.html

[Q73] 查看表状态
来源：http://dali.yj20258888.top/Article/details/gt2ikaeatmv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mptynskn.html

[Q74] 强制使用索引
来源：http://dali.shuidangran.top/Article/details/gt2xghlzzft.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nanxinkj.top/Article/details/gt2kcinccdl.html

[Q75] 日期格式化
来源：http://dali.yonumen.top/Article/details/gt2zuvkcoou.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yuxming.cn/Article/details/gt2wdhdteat.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sxryk.cn/Article/details/gt2bjvktgwv.html

[Q76] 按天统计
来源：http://dali.nwbrower.top/Article/details/gt2froatuen.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.fengsongda.top/Article/details/gt2fcdvigmt.html

[Q77] 时间加减
来源：http://dali.yuanzhike.top/Article/details/gt2mavjveln.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tanke756.top/Article/details/gt2wjwuuzzg.html

[Q78] 当前时间
来源：http://dali.yongpay.top/Article/details/gt2hurzcheb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxinkj.top/Article/details/gt2rkgjpkrq.html

[Q79] 字符串拼接
来源：http://dali.zhixingplan.top/Article/details/gt2cfugastq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.fengsongda.top/Article/details/gt2dsvnuyzt.html

[Q80] 字符串截取
来源：http://dali.zhiwuduotai.top/Article/details/gt2vbbsfhht.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vkdnnxdv.html

[Q81] 字符串替换
来源：http://dali.sweek.top/Article/details/gt2gkmyfmxe.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2qbmfoqsq.html

[Q82] 字符长度与字节长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2allqmowe.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2mokzgfoq.html

[Q83] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2iprgfkaz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2kvwztlfz.html

[Q84] 去除首尾空格
来源：http://dali.zhengqikj.top/Article/details/gt2gsaeimwr.html

SELECT TRIM(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2krjmegip.html

[Q85] 数值取整
来源：http://dali.sxryk.cn/Article/details/gt2hhguxayr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj202588.top/Article/details/gt2fqhnwuuo.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kacvahxa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ndqmebxo.html

[Q87] JSON 字段做条件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iiqegfyj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xuetiantiany.cn/Article/details/gt2paqwzkpl.html

[Q88] 行转列（条件聚合）
来源：http://dali.hywenlv.cn/Article/details/gt2tnwcwprt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.kuanghao11.cn/Article/details/gt2adbgqqdx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2qxqntrmv.html

[Q89] 判断表是否存在
来源：http://dali.tianlin.xyz/Article/details/gt2wkkioazo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yuanzhike.top/Article/details/gt2krtnjrzp.html

[Q90] 生成序号列
来源：http://dali.zycfv.cn/Article/details/gt2xwynnccv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.svipenyu.cn/Article/details/gt2yruxkopy.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2obxmvyhi.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbtvunj.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2lhrrozwk.html

[R01] shebang 与严格模式
来源：http://dali.jqgufenzy.top/Article/details/gt2pfxrnvec.html

#!/usr/bin/env bash
来源：http://dali.yangfankeji.com/Article/details/gt2mzxazncq.html

set -euo pipefail
来源：http://dali.jqgufenzy.top/Article/details/gt2dymoyjeu.html

[R02] 变量赋值与使用
来源：http://dali.yangfankeji.com/Article/details/gt2wplmwwgb.html

name="Tom"; echo "$name"
来源：http://dali.yj202588.top/Article/details/gt2kbcgtmfa.html

[R03] 只读变量
来源：http://dali.ppjwa.cn/Article/details/gt2qkobflac.html

readonly PI=3.14
来源：http://dali.ydzc1.top/Article/details/gt2yrwlkbkt.html

[R04] 位置参数
来源：http://dali.jiagoushi.top/Article/details/gt2idaiczlk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuetiantiany.cn/Article/details/gt2kypjiraj.html

[R05] 参数默认值
来源：http://dali.xuetiantiany.cn/Article/details/gt2durfxoew.html

name="${1:-default}"
来源：http://dali.xuanzx.com/Article/details/gt2usvgkdwc.html

[R06] 判断命令是否存在
来源：http://dali.shzxlz.cn/Article/details/gt2qnbbzcju.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gt2fmuczsup.html

[R07] if 判断文件
来源：http://dali.0kj1m.cn/Article/details/gt2jbvjvjuh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zdqjudy.top/Article/details/gt2qxinbelz.html

[R08] 数值比较
来源：http://dali.hysaishi.cn/Article/details/gt2baaqjzzw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xylfe.cn/Article/details/gt2ffcrwizy.html

[R09] 字符串比较
来源：http://dali.jianghu66.top/Article/details/gt2xdxlqngl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gzhubu.top/Article/details/gt2sptqgosy.html

[R10] 正则匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iwhiogch.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.redwolf501.top/Article/details/gt2eykzdfip.html

[R11] case 多分支
来源：http://dali.xuanzx.com/Article/details/gt2kpofrolz.html

case "$1" in
来源：http://dali.9152youxi.cn/Article/details/gt2akwnfzso.html

start) echo "启动" ;;
来源：http://dali.fengsongda.top/Article/details/gt2rxhdfusk.html

stop)  echo "停止" ;;
来源：http://dali.yj202588.top/Article/details/gt2wfwfkaqf.html

*)     echo "未知命令" ;;
来源：http://dali.cqqwz.cn/Article/details/gt2wcxzluge.html

esac
来源：http://dali.ydzc1.top/Article/details/gt2tvopjbij.html

[R12] for 遍历文件
来源：http://dali.9152youxi.cn/Article/details/gt2mzybzrsi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hysaishi.cn/Article/details/gt2xouptjgx.html

[R13] for 计数循环
来源：http://dali.aizwys.cn/Article/details/gt2zyxmwrqh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigufen.top/Article/details/gt2geggdshq.html

[R14] C 风格 for
来源：http://dali.daxiang520.top/Article/details/gt2fiswleuv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daria6918.cn/Article/details/gt2rtarqbtk.html

[R15] while 逐行读文件
来源：http://dali.wangdashe.top/Article/details/gt2lxdekfmn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xinyue.icu/Article/details/gt2psagobgh.html

[R16] until 等待条件
来源：http://dali.mhx1999.top/Article/details/gt2ttzjwlrc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gt2jrzkhwdz.html

[R17] 数组定义与取值
来源：http://dali.gotoacloud.top/Article/details/gt2sbpmlbrf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hysaishi.cn/Article/details/gt2grwmgibg.html

[R18] 遍历数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hqpaxnuu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.vqdsnc.cn/Article/details/gt2jsddxoqr.html

[R19] 数组长度
来源：http://dali.havefunace.top/Article/details/gt2pcsmsoaf.html

echo "${#arr[@]}"
来源：http://dali.nanxinkj.top/Article/details/gt2apapevgy.html

[R20] 关联数组（字典）
来源：http://dali.xinyue.icu/Article/details/gt2fwjzsvny.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kuduxnqz.html

[R21] 字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gt2glomrhpo.html

echo "${#s}"
来源：http://dali.yj20258888.top/Article/details/gt2xilnetef.html

[R22] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gt2msdyfgtu.html

echo "${s:0:5}"
来源：http://dali.jianghu66.top/Article/details/gt2djwfvlit.html

[R23] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gdlkurxt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenlongwang.top/Article/details/gt2khmnxcui.html

[R24] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gt2eatqdnrc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cashguo.top/Article/details/gt2xjcgrwyi.html

[R25] 去后缀 / 去前缀
来源：http://dali.jianghu66.top/Article/details/gt2hihjhvnq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj20258888.top/Article/details/gt2mzvnbjau.html

[R26] 命令替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2kaqjovkh.html

now=$(date +%F); echo "$now"
来源：http://dali.svipenyu.cn/Article/details/gt2uxjnejjh.html

[R27] 算术展开
来源：http://dali.hammf.cn/Article/details/gt2tyvnxpfc.html

echo $((1 + 2 * 3))
来源：http://dali.hammf.cn/Article/details/gt2zsbyapis.html

[R28] 浮点运算
来源：http://dali.daria6918.cn/Article/details/gt2lsolatoc.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhiwuduotai.top/Article/details/gt2qkwbciqh.html

[R29] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gt2gfdhvrzb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.0kj1m.cn/Article/details/gt2fvcfcwan.html

[R30] 函数返回状态码
来源：http://dali.c1oappe.top/Article/details/gt2wbutnehz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.guannengcc.top/Article/details/gt2todrgpor.html

[R31] 局部变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2ylwzcwlz.html

f() { local x=1; echo "$x"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2hiafxpbe.html

[R32] 参数个数校验
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mygiiolm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gt2pzhmexpb.html

[R33] 捕获错误并提示行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fsamdszb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.bjfxy.top/Article/details/gt2kluwsgxo.html

[R34] 退出时清理
来源：http://dali.smart0.xyz/Article/details/gt2tgfkjkrg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gt2tqjpissx.html

[R35] 后台执行并等待
来源：http://dali.c1oappe.top/Article/details/gt2qtvhwsgs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhengqikj.top/Article/details/gt2pxuqqgwv.html

[R36] 并发执行多个任务
来源：http://dali.zhongyouzk.top/Article/details/gt2usfxbpop.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gotoacloud.top/Article/details/gt2ohyglnuq.html

[R37] 把输出赋给变量
来源：http://dali.9152youxi.cn/Article/details/gt2cptytxdw.html

files=$(ls -1)
来源：http://dali.yj20258.top/Article/details/gt2ogocpalf.html

[R38] 管道串联
来源：http://dali.redwolf501.top/Article/details/gt2ddytnfqx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.meibo888.top/Article/details/gt2pmsdmpmv.html

[R39] 重定向标准输出与错误
来源：http://dali.dashuyun.cn/Article/details/gt2swpvqkly.html

cmd > out.log 2>&1
来源：http://dali.jyoumei.cn/Article/details/gt2xrwkgimx.html

[R40] 追加写日志
来源：http://dali.haohaochexian.top/Article/details/gt2wrojksog.html

echo "log" >> out.log
来源：http://dali.nanxinkj.top/Article/details/gt2pqkxgvgc.html

[R41] 丢弃输出
来源：http://dali.cashguo.top/Article/details/gt2umtxgkzk.html

cmd >/dev/null 2>&1
来源：http://dali.quarkkingdee.top/Article/details/gt2ijtkbbpr.html

[R42] 输入重定向
来源：http://dali.zhengqikj.top/Article/details/gt2mmzzgela.html

wc -l < a.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2jxfmdukt.html

[R43] 按名字查找文件
来源：http://dali.yvedp.cn/Article/details/gt2tbxeqwsz.html

find . -name "*.log" -type f
来源：http://dali.haohaochexian.top/Article/details/gt2yysnvger.html

[R44] 按修改时间查找
来源：http://dali.daxiang520.top/Article/details/gt2fwhpohjd.html

find . -mtime -7 -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hnwlffrw.html

[R45] 批量删除
来源：http://dali.yangfankeji.com/Article/details/gt2eerkiusp.html

find . -name "*.tmp" -delete
来源：http://dali.zycfv.cn/Article/details/gt2ujdsnnnk.html

[R46] 递归替换文件内容
来源：http://dali.tanke756.top/Article/details/gt2fcgijkhn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sxryk.cn/Article/details/gt2zkjffkbw.html

[R47] sed 单行替换
来源：http://dali.nanxuanxn.top/Article/details/gt2tauukgdd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gt2omfokyrt.html

[R48] awk 取指定列
来源：http://dali.zhoulong.xyz/Article/details/gt2bgtrghpu.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj20258888.top/Article/details/gt2ipixbxpr.html

[R49] awk 带条件
来源：http://dali.zycfv.cn/Article/details/gt2zdmaefer.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.c1oappe.top/Article/details/gt2rvzpbgzl.html

[R50] awk 求和
来源：http://dali.bjfxy.top/Article/details/gt2vitbyppz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jiagoushi.top/Article/details/gt2hrlcozei.html

[R51] 排序去重取前几
来源：http://dali.0kj1m.cn/Article/details/gt2ynzoqdvb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinqigufen.top/Article/details/gt2narvoygk.html

[R52] 统计行数
来源：http://dali.nanxinkj.top/Article/details/gt2oohioyim.html

wc -l a.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2wqrobcuo.html

[R53] 查看文件头与实时尾
来源：http://dali.tian-w.cn/Article/details/gt2djmboeqr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhixingplan.top/Article/details/gt2gungnksw.html

[R54] 比较两个文件
来源：http://dali.hywenlv.cn/Article/details/gt2rdwzvlkn.html

diff a.txt b.txt
来源：http://dali.guannengcc.top/Article/details/gt2swhzqxbu.html

[R55] 压缩与解压
来源：http://dali.mhx1999.top/Article/details/gt2uwvfhuih.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hfpthk.cn/Article/details/gt2ymwwcutn.html

[R56] 远程拷贝
来源：http://dali.nanxuanxn.top/Article/details/gt2krfbpbpl.html

scp file user@host:/path/
来源：http://dali.cheryme.top/Article/details/gt2ifrvttsb.html

[R57] 远程执行命令
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sjlczdyb.html


<!-- 参考信息 -->