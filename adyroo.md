代发 wailian999

);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tzfhlqis.html

[Q03] 增加列
来源：http://dali.feifeiyinyue.top/Article/details/gt2tocxpuoc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hysaishi.cn/Article/details/gt2dybflmeo.html

[Q04] 修改列类型
来源：http://dali.tianlin.xyz/Article/details/gt2ypkvaxue.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgfzy.top/Article/details/gt2ezunttbp.html

[Q05] 重命名列
来源：http://dali.birdmap.top/Article/details/gt2nqpptsel.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.fengsongda.top/Article/details/gt2mefqfrhf.html

[Q06] 删除列
来源：http://dali.yvedp.cn/Article/details/gt2vlulqrka.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.feifeiyinyue.top/Article/details/gt2szytcffx.html

[Q07] 删除表
来源：http://dali.cqqwz.cn/Article/details/gt2lidcfegi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2neskxmqi.html

[Q08] 创建普通索引
来源：http://dali.jianghu66.top/Article/details/gt2adushayc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yonumen.top/Article/details/gt2hydbcaun.html

[Q09] 创建唯一索引
来源：http://dali.svipenyu.cn/Article/details/gt2kvqvpaoj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhoulong.xyz/Article/details/gt2dpjyutxe.html

[Q10] 插入单行
来源：http://dali.havefunace.top/Article/details/gt2vgvrctae.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ybcxt.top/Article/details/gt2wreuwzqj.html

[Q11] 一次插入多行
来源：http://dali.chenlongwang.top/Article/details/gt2osyybfcd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cashguo.top/Article/details/gt2axqoqnmb.html

[Q12] 插入后取自增 ID
来源：http://dali.yonumen.top/Article/details/gt2eewxkxfv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jiagoushi.top/Article/details/gt2eogndmvo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jianghu66.top/Article/details/gt2gepjsrbg.html

[Q13] 忽略重复插入
来源：http://dali.gaohongyu789.top/Article/details/gt2wyoddblw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.aizwys.cn/Article/details/gt2bowbdlas.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhongyouzk.top/Article/details/gt2vipfhrep.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.0kj1m.cn/Article/details/gt2ksnpbeyc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gzhubu.top/Article/details/gt2xszdpqwq.html

[Q15] 查询全部
来源：http://dali.yuxming.cn/Article/details/gt2hemwkcev.html

SELECT * FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2wxekhtdc.html

[Q16] 查询指定列
来源：http://dali.daria6918.cn/Article/details/gt2kizowyiz.html

SELECT id, name FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2wkbbabqr.html

[Q17] 条件查询
来源：http://dali.birdmap.top/Article/details/gt2ccofvgqe.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tian-w.cn/Article/details/gt2foozftcq.html

[Q18] 模糊匹配
来源：http://dali.ybcxt.top/Article/details/gt2bbzmldcv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.svipenyu.cn/Article/details/gt2bpankzrk.html

[Q19] 范围查询
来源：http://dali.fengsongda.top/Article/details/gt2asaqnkyk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxinkj.top/Article/details/gt2qkeaymox.html

[Q20] IN 列表
来源：http://dali.nanxinkj.top/Article/details/gt2lmwpofii.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.0kj1m.cn/Article/details/gt2zhxcmyny.html

[Q21] 空值判断
来源：http://dali.sufxvd.cn/Article/details/gt2rbfnlbxh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gotoacloud.top/Article/details/gt2hopzfuqa.html

[Q22] 排序
来源：http://dali.gotoacloud.top/Article/details/gt2rwveaafd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj20258888.top/Article/details/gt2enfrkxfz.html

[Q23] 分页
来源：http://dali.zhixingplan.top/Article/details/gt2sifjtldl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hnqzz.top/Article/details/gt2diaiewjs.html

[Q24] 去重
来源：http://dali.c1oappe.top/Article/details/gt2nneratjv.html

SELECT DISTINCT city FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2eeqvrtdv.html

[Q25] 只取前 N 条
来源：http://dali.zhiwuduotai.top/Article/details/gt2mskbmjhx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuxming.cn/Article/details/gt2eekkimri.html

[Q26] 计数
来源：http://dali.yj20258.top/Article/details/gt2mmnbsbpf.html

SELECT COUNT(*) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2eswzpsre.html

[Q27] 条件计数
来源：http://dali.gotoacloud.top/Article/details/gt2kjbnfktm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2erkijvdl.html

[Q28] 求和与平均
来源：http://dali.zhengqikj.top/Article/details/gt2laqmustx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2orfmjatd.html

[Q29] 最大最小值
来源：http://dali.guannengcc.top/Article/details/gt2qmlaualp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2buysfmtn.html

[Q30] 分组统计
来源：http://dali.zdqjudy.top/Article/details/gt2razffdwu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxnaurta.html

[Q31] 分组后过滤
来源：http://dali.aibaodan.cn/Article/details/gt2xxjblpyy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vnqjecll.html

[Q32] 分组拼接字符串
来源：http://dali.daria6918.cn/Article/details/gt2qwtgmxjz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gt2bxyfqnze.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sufxvd.cn/Article/details/gt2hzdemgxi.html

[Q33] 多列分组
来源：http://dali.0kj1m.cn/Article/details/gt2kxylbueo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgidqonb.html

[Q34] 每组取第一条
来源：http://dali.xziqi.cn/Article/details/gt2wkajctmb.html

SELECT * FROM (
来源：http://dali.hysaishi.cn/Article/details/gt2aoaofokp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.daxiang520.top/Article/details/gt2ycukbezl.html

) t WHERE rn = 1;
来源：http://dali.hnxiangtu.top/Article/details/gt2hkycqpad.html

[Q35] 内连接
来源：http://dali.chenzaomai.com/Article/details/gt2crquwdky.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2tiffmawl.html

[Q36] 左连接
来源：http://dali.nanxinkj.top/Article/details/gt2kcbsecsj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.birdmap.top/Article/details/gt2dzsbcdgl.html

[Q37] 右连接
来源：http://dali.tianlin.xyz/Article/details/gt2mqczbqla.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.haohaochexian.top/Article/details/gt2hwbojpmd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj20258.top/Article/details/gt2qzazywzo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yuxming.cn/Article/details/gt2jmjcsnkr.html

[Q39] 自连接（查上下级）
来源：http://dali.chenlongwang.top/Article/details/gt2rbnnkpzl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.snrcjt.cn/Article/details/gt2ldptdsba.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ybcxt.top/Article/details/gt2wwtxrdbe.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xuetiantiany.cn/Article/details/gt2vtlmlktb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xuetiantiany.cn/Article/details/gt2fzmxrsra.html

[Q41] 多表连接
来源：http://dali.zycfv.cn/Article/details/gt2dweitklh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hfpthk.cn/Article/details/gt2ubfthiso.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nanxinkj.top/Article/details/gt2usfxwmcf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jiagoushi.top/Article/details/gt2qiimuhhy.html

[Q42] 连接条件附加过滤
来源：http://dali.guannengcc.top/Article/details/gt2tjydkryt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.vqdsnc.cn/Article/details/gt2pgennksc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gotoacloud.top/Article/details/gt2mvfpuzoc.html

[Q43] 标量子查询
来源：http://dali.hywenlv.cn/Article/details/gt2vbtrjstp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nanxinkj.top/Article/details/gt2mcjxkppw.html

[Q44] IN 子查询
来源：http://dali.ehwqpu.com/Article/details/gt2iftxdgrg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sysykeji.top/Article/details/gt2ahgavfdh.html

[Q45] EXISTS 判断存在
来源：http://dali.cashguo.top/Article/details/gt2gtjxmngh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ybcxt.top/Article/details/gt2pwafatzx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhiwuduotai.top/Article/details/gt2upigotqk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.9152youxi.cn/Article/details/gt2rvcdxdmp.html

[Q47] 与平均值比较
来源：http://dali.guannengcc.top/Article/details/gt2nwsvasqu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgfzy.top/Article/details/gt2tpskhwek.html

[Q48] CTE 公用表表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2blhcjkdr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jyoumei.cn/Article/details/gt2qbstsuwd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj202588.top/Article/details/gt2doyacvyy.html

[Q49] 更新单行
来源：http://dali.zhongyouzk.top/Article/details/gt2hjudhism.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gt2cetegixw.html

[Q50] 批量更新
来源：http://dali.zycfv.cn/Article/details/gt2bbfidbvy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gt2gxanapkb.html

[Q51] 用子查询更新
来源：http://dali.hongshengwenyu.top/Article/details/gt2hpahmbyr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sysykeji.top/Article/details/gt2mlpflegd.html

[Q52] 删除指定行
来源：http://dali.andypj.xyz/Article/details/gt2lbxrsxdg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gt2xpdpyzlu.html

[Q53] 按条件删除
来源：http://dali.xziqi.cn/Article/details/gt2gsqqbjct.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yonumen.top/Article/details/gt2lrmzuuoy.html

[Q54] 清空表
来源：http://dali.vqdsnc.cn/Article/details/gt2pczgxqdf.html

TRUNCATE TABLE logs;
来源：http://dali.feifeiyinyue.top/Article/details/gt2jlzykhoc.html

[Q55] 排名（并列占位）
来源：http://dali.gotoacloud.top/Article/details/gt2xilfqcrt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gt2dzhyhdvm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhengqikj.top/Article/details/gt2jelhmuis.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhongyouzk.top/Article/details/gt2vzitgbqy.html

[Q57] 行号
来源：http://dali.wangdashe.top/Article/details/gt2zmamklse.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2yxyrxnan.html

[Q58] 累计求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hmqyddoi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gt2kykveflh.html

[Q59] 分组内累计
来源：http://dali.jiagoushi.top/Article/details/gt2wwnnqbfd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gt2ndtdxfbq.html

[Q60] 取上一行 / 下一行
来源：http://dali.snrcjt.cn/Article/details/gt2tvthiqox.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jlsjyb.cn/Article/details/gt2leddoizt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gt2vazsezvj.html

[Q61] 移动平均
来源：http://dali.daxiang520.top/Article/details/gt2nutdnlwo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gt2nfqjozmz.html

[Q62] 分组占比
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pxuswmvl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gt2rxftlbjn.html

[Q63] 开启事务
来源：http://dali.wangshuangyany.cn/Article/details/gt2ujvcwpra.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cashguo.top/Article/details/gt2hipjugqp.html

[Q64] 提交事务
来源：http://dali.redwolf501.top/Article/details/gt2rjpnmybd.html

COMMIT;
来源：http://dali.shuidangran.top/Article/details/gt2ifgjkymj.html

[Q65] 回滚事务
来源：http://dali.xylfe.cn/Article/details/gt2wmpmrnlu.html

ROLLBACK;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zqftopxg.html

[Q66] 行锁查询
来源：http://dali.gaohongyu789.top/Article/details/gt2vrpmrsuh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ivvv.top/Article/details/gt2auqddgfe.html

[Q67] 设置隔离级别
来源：http://dali.chenlongwang.top/Article/details/gt2raxmtqqc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shangyingyoupin.top/Article/details/gt2nzkewkqo.html

[Q68] 保存点
来源：http://dali.sxryk.cn/Article/details/gt2qheuinzk.html

SAVEPOINT sp1;
来源：http://dali.zycfv.cn/Article/details/gt2gukuykhz.html

ROLLBACK TO sp1;
来源：http://dali.yonumen.top/Article/details/gt2wjlopdpj.html

[Q69] 查看执行计划
来源：http://dali.cashguo.top/Article/details/gt2itzpvrmp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yuxming.cn/Article/details/gt2xyymdxcr.html

[Q70] 更新统计信息
来源：http://dali.dianchejie.cn/Article/details/gt2bgaipqts.html

ANALYZE TABLE users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2prjmlctv.html

[Q71] 查看建表语句
来源：http://dali.pengpengdd.cyou/Article/details/gt2myjmolss.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hysaishi.cn/Article/details/gt2tagxomit.html

[Q72] 查看索引
来源：http://dali.aizwys.cn/Article/details/gt2gowssmbi.html

SHOW INDEX FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2loavxudb.html

[Q73] 查看表状态
来源：http://dali.zhiwuduotai.top/Article/details/gt2uhnvbxso.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.mhx1999.top/Article/details/gt2axaeoxxd.html

[Q74] 强制使用索引
来源：http://dali.quarkkingdee.top/Article/details/gt2ynwadljc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tianlin.xyz/Article/details/gt2iqahkqzz.html

[Q75] 日期格式化
来源：http://dali.316326.xyz/Article/details/gt2uggbknfb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shuidangran.top/Article/details/gt2ouwbldzn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hfpthk.cn/Article/details/gt2mwvrzxfz.html

[Q76] 按天统计
来源：http://dali.aizwys.cn/Article/details/gt2lwrmgiuq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hammf.cn/Article/details/gt2rhjbqclh.html

[Q77] 时间加减
来源：http://dali.haohaochexian.top/Article/details/gt2dgjcqnpa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhixingplan.top/Article/details/gt2gypkgvoz.html

[Q78] 当前时间
来源：http://dali.hnqzz.top/Article/details/gt2gpmmzjlh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shangyingyoupin.top/Article/details/gt2yxmnhtvy.html

[Q79] 字符串拼接
来源：http://dali.xuanzx.com/Article/details/gt2yuwfzser.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nwbrower.top/Article/details/gt2qlwzjcxv.html

[Q80] 字符串截取
来源：http://dali.fzhhl.top/Article/details/gt2evvbfqab.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2esktkoyk.html

[Q81] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gt2fborushc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jiorvizr.html

[Q82] 字符长度与字节长度
来源：http://dali.xylfe.cn/Article/details/gt2vtxqikka.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2gmuxcqnz.html

[Q83] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gt2zkbsalcd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2nvpgjhvb.html

[Q84] 去除首尾空格
来源：http://dali.jinqigfzy.top/Article/details/gt2icndzgmi.html

SELECT TRIM(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2zkarnush.html

[Q85] 数值取整
来源：http://dali.xylfe.cn/Article/details/gt2olldzusy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.meibo888.top/Article/details/gt2jjutncqr.html

[Q86] 读取 JSON 字段
来源：http://dali.aibaodan.cn/Article/details/gt2rueispeo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ivvv.top/Article/details/gt2bjbdyfyy.html

[Q87] JSON 字段做条件
来源：http://dali.birdmap.top/Article/details/gt2vhkoqlkv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daxiang520.top/Article/details/gt2wwnomqgh.html

[Q88] 行转列（条件聚合）
来源：http://dali.jiagoushi.top/Article/details/gt2zqitmclr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zdqjudy.top/Article/details/gt2fohokeeh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hammf.cn/Article/details/gt2zhaxdjab.html

[Q89] 判断表是否存在
来源：http://dali.andypj.xyz/Article/details/gt2uimhmkvd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gogol.net.cn/Article/details/gt2mfplldfx.html

[Q90] 生成序号列
来源：http://dali.xziqi.cn/Article/details/gt2eaovsyrb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.guowangkeji.top/Article/details/gt2kwzywyux.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2jzlgdkxx.html

R. Bash 专题
来源：http://dali.cheryme.top/Article/details/gt2eesdiumx.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2rhtnjfkt.html

[R01] shebang 与严格模式
来源：http://dali.0kj1m.cn/Article/details/gt2fbedpdwg.html

#!/usr/bin/env bash
来源：http://dali.cheryme.top/Article/details/gt2zexyjdfv.html

set -euo pipefail
来源：http://dali.kuanghao11.cn/Article/details/gt2ccwsliim.html

[R02] 变量赋值与使用
来源：http://dali.birdmap.top/Article/details/gt2oaglspsz.html

name="Tom"; echo "$name"
来源：http://dali.0kj1m.cn/Article/details/gt2rqhlpbkx.html

[R03] 只读变量
来源：http://dali.ybcxt.top/Article/details/gt2ptoqwkor.html

readonly PI=3.14
来源：http://dali.yueranfly.top/Article/details/gt2zdjzoooo.html

[R04] 位置参数
来源：http://dali.guowangkeji.top/Article/details/gt2fdngmyqo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258888.top/Article/details/gt2pwlwccly.html

[R05] 参数默认值
来源：http://dali.c1oappe.top/Article/details/gt2brtiqmfk.html

name="${1:-default}"
来源：http://dali.9152youxi.cn/Article/details/gt2xtnioskp.html

[R06] 判断命令是否存在
来源：http://dali.shzxlz.cn/Article/details/gt2hzxnuklq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.meibo888.top/Article/details/gt2ysszxfmy.html

[R07] if 判断文件
来源：http://dali.bjfxy.top/Article/details/gt2beavglei.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.0kj1m.cn/Article/details/gt2hpwwwiln.html

[R08] 数值比较
来源：http://dali.daria6918.cn/Article/details/gt2xumhilwr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jqgfzy.top/Article/details/gt2twaqyvjv.html

[R09] 字符串比较
来源：http://dali.zhongyouzk.top/Article/details/gt2qgllauiw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tian-w.cn/Article/details/gt2mdjmcpft.html

[R10] 正则匹配
来源：http://dali.hnqzz.top/Article/details/gt2ebjxibje.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cqqwz.cn/Article/details/gt2qerzwdue.html

[R11] case 多分支
来源：http://dali.yuanzhike.top/Article/details/gt2rfeucbhk.html

case "$1" in
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2attfsplx.html

start) echo "启动" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zsqertzx.html

stop)  echo "停止" ;;
来源：http://dali.cqqwz.cn/Article/details/gt2vymfyfhh.html

*)     echo "未知命令" ;;
来源：http://dali.redwolf501.top/Article/details/gt2tztrelml.html

esac
来源：http://dali.vqdsnc.cn/Article/details/gt2lpwngzse.html

[R12] for 遍历文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2cnflzwdi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.dianchejie.cn/Article/details/gt2fwzimdwa.html

[R13] for 计数循环
来源：http://dali.haohaochexian.top/Article/details/gt2gojmulxn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gt2szqlbeny.html

[R14] C 风格 for
来源：http://dali.aibaodan.cn/Article/details/gt2okemdxzy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gt2chvedfqt.html

[R15] while 逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gt2chmjalyh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.0kj1m.cn/Article/details/gt2ibssufaw.html

[R16] until 等待条件
来源：http://dali.xylfe.cn/Article/details/gt2sdegbtyu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gt2wwzftmcn.html

[R17] 数组定义与取值
来源：http://dali.hywenlv.cn/Article/details/gt2hupqmatz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fzhhl.top/Article/details/gt2njgijjik.html

[R18] 遍历数组
来源：http://dali.tanke756.top/Article/details/gt2mvjrhmpa.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2iakxblpg.html

[R19] 数组长度
来源：http://dali.sysykeji.top/Article/details/gt2kyxktmdp.html

echo "${#arr[@]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gnhccfgo.html

[R20] 关联数组（字典）
来源：http://dali.ppjwa.cn/Article/details/gt2ewscumle.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj202588.top/Article/details/gt2vafntdev.html

[R21] 字符串长度
来源：http://dali.ivvv.top/Article/details/gt2ucceewhk.html

echo "${#s}"
来源：http://dali.aibaodan.cn/Article/details/gt2ofjcyjmj.html

[R22] 截取子串
来源：http://dali.zdqjudy.top/Article/details/gt2xlcgzeli.html

echo "${s:0:5}"
来源：http://dali.shuidangran.top/Article/details/gt2xjvxjddl.html

[R23] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yjuroukz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj202588.top/Article/details/gt2ngeglrpc.html

[R24] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gt2xnlthpkd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yueranfly.top/Article/details/gt2fyfxrgvz.html

[R25] 去后缀 / 去前缀
来源：http://dali.yueranfly.top/Article/details/gt2pjtdslmf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yonumen.top/Article/details/gt2gcqnweeb.html

[R26] 命令替换
来源：http://dali.guowangkeji.top/Article/details/gt2qoxtoxcm.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgufenzy.top/Article/details/gt2jypurfle.html

[R27] 算术展开
来源：http://dali.xuanzx.com/Article/details/gt2qlgrbaly.html

echo $((1 + 2 * 3))
来源：http://dali.dianchejie.cn/Article/details/gt2gqesyifc.html

[R28] 浮点运算
来源：http://dali.hysaishi.cn/Article/details/gt2hoximsxw.html

echo "scale=2; 10/3" | bc
来源：http://dali.jyoumei.cn/Article/details/gt2vyrkzlfa.html

[R29] 定义函数
来源：http://dali.zhengqikj.top/Article/details/gt2fllrjmyr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cashguo.top/Article/details/gt2fzxmcpkr.html

[R30] 函数返回状态码
来源：http://dali.daxiang520.top/Article/details/gt2eoepwjvc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2avhjmqma.html

[R31] 局部变量
来源：http://dali.mhx1999.top/Article/details/gt2qqnxmtiz.html

f() { local x=1; echo "$x"; }
来源：http://dali.daria6918.cn/Article/details/gt2gyrvuunk.html

[R32] 参数个数校验
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2izocuqsp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2bkfmuvuq.html

[R33] 捕获错误并提示行号
来源：http://dali.zhengqikj.top/Article/details/gt2emkxghlu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fengsongda.top/Article/details/gt2tkrvjxxb.html

[R34] 退出时清理
来源：http://dali.mhx1999.top/Article/details/gt2msgthwxo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gt2tbmxtqvn.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2grtqczsf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.quarkkingdee.top/Article/details/gt2mvezywfa.html

[R36] 并发执行多个任务
来源：http://dali.quarkkingdee.top/Article/details/gt2blftrjco.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yueranfly.top/Article/details/gt2dduxrdcm.html

[R37] 把输出赋给变量
来源：http://dali.haohaochexian.top/Article/details/gt2zypljuon.html

files=$(ls -1)
来源：http://dali.hammf.cn/Article/details/gt2sgfsqlqb.html

[R38] 管道串联
来源：http://dali.hnxiangtu.top/Article/details/gt2bhoflsuz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sufxvd.cn/Article/details/gt2ywbxuzng.html

[R39] 重定向标准输出与错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pecvawwc.html

cmd > out.log 2>&1
来源：http://dali.redwolf501.top/Article/details/gt2mtlggpid.html

[R40] 追加写日志
来源：http://dali.yj20258.top/Article/details/gt2xdbjrllp.html

echo "log" >> out.log
来源：http://dali.hysaishi.cn/Article/details/gt2glrazdfs.html

[R41] 丢弃输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rkpwusfz.html

cmd >/dev/null 2>&1
来源：http://dali.ybcxt.top/Article/details/gt2xhoxzrba.html

[R42] 输入重定向
来源：http://dali.fzhhl.top/Article/details/gt2ncerpxqd.html

wc -l < a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2zwkuwvfp.html

[R43] 按名字查找文件
来源：http://dali.yangfankeji.com/Article/details/gt2avkeekpn.html

find . -name "*.log" -type f
来源：http://dali.yongpay.top/Article/details/gt2bshgmdjz.html

[R44] 按修改时间查找
来源：http://dali.sxryk.cn/Article/details/gt2xmtcdycu.html

find . -mtime -7 -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nuciznpc.html

[R45] 批量删除
来源：http://dali.shangyingyoupin.top/Article/details/gt2ilosyzec.html

find . -name "*.tmp" -delete
来源：http://dali.redwolf501.top/Article/details/gt2djfdzoig.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zqxbpbik.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.vqdsnc.cn/Article/details/gt2qpdzvuxm.html

[R47] sed 单行替换
来源：http://dali.yuxming.cn/Article/details/gt2itnqindv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.316326.xyz/Article/details/gt2zysjqzht.html

[R48] awk 取指定列
来源：http://dali.ybcxt.top/Article/details/gt2ureeygxl.html

awk '{print $1, $3}' a.txt
来源：http://dali.sxryk.cn/Article/details/gt2rmahudym.html

[R49] awk 带条件
来源：http://dali.zdqjudy.top/Article/details/gt2gdwkbtwz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yangfankeji.com/Article/details/gt2exnvwysx.html

[R50] awk 求和
来源：http://dali.shuidangran.top/Article/details/gt2qozmqtux.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenlongwang.top/Article/details/gt2tanbtglk.html

[R51] 排序去重取前几
来源：http://dali.hywenlv.cn/Article/details/gt2ztukryho.html


<!-- 参考信息 -->