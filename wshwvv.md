代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.dianchejie.cn/Article/details/gt2ifmqsymj.html

[Q05] 重命名列
来源：http://dali.gotoacloud.top/Article/details/gt2pcsdwwby.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.smart0.xyz/Article/details/gt2cjempgsy.html

[Q06] 删除列
来源：http://dali.316326.xyz/Article/details/gt2bnildeay.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjpkngc.html

[Q07] 删除表
来源：http://dali.xuetiantiany.cn/Article/details/gt2bnltsjrf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hnqzz.top/Article/details/gt2slgvjbrg.html

[Q08] 创建普通索引
来源：http://dali.yuanzhike.top/Article/details/gt2eyarnzul.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gt2bdovdpyo.html

[Q09] 创建唯一索引
来源：http://dali.cdnleiting.top/Article/details/gt2wnzxqnjs.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.mhx1999.top/Article/details/gt2haoexdna.html

[Q10] 插入单行
来源：http://dali.tianlin.xyz/Article/details/gt2cdrtftnt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cucudq.cn/Article/details/gt2wxzjtpdp.html

[Q11] 一次插入多行
来源：http://dali.guowangkeji.top/Article/details/gt2xbdjbgxm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xziqi.cn/Article/details/gt2amssezks.html

[Q12] 插入后取自增 ID
来源：http://dali.fzhhl.top/Article/details/gt2puwpjbuq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cdnleiting.top/Article/details/gt2lqjqumra.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xylfe.cn/Article/details/gt2fbsyewxm.html

[Q13] 忽略重复插入
来源：http://dali.daxiang520.top/Article/details/gt2gwxvlvqk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangdashe.top/Article/details/gt2jucpevac.html

[Q14] 存在则更新（upsert）
来源：http://dali.pycfn.com/Article/details/gt2etdwifuc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.316326.xyz/Article/details/gt2fallhlwq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zzguiaol.html

[Q15] 查询全部
来源：http://dali.svipenyu.cn/Article/details/gt2papodkwo.html

SELECT * FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2wmmoxjjr.html

[Q16] 查询指定列
来源：http://dali.aizwys.cn/Article/details/gt2sjnljryl.html

SELECT id, name FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xsjkvkpn.html

[Q17] 条件查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2rqfrxdcz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.nwbrower.top/Article/details/gt2zsnbsfnm.html

[Q18] 模糊匹配
来源：http://dali.mhx1999.top/Article/details/gt2yiwwictn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jianghu66.top/Article/details/gt2bewzhzxs.html

[Q19] 范围查询
来源：http://dali.jyoumei.cn/Article/details/gt2qsvoebwc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guannengcc.top/Article/details/gt2fkvayflb.html

[Q20] IN 列表
来源：http://dali.hnqzz.top/Article/details/gt2vmzuhclt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shzxlz.cn/Article/details/gt2xzojlkbi.html

[Q21] 空值判断
来源：http://dali.ehwqpu.com/Article/details/gt2ngzjbjph.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sweek.top/Article/details/gt2tgfbafvl.html

[Q22] 排序
来源：http://dali.havefunace.top/Article/details/gt2rrscgeff.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yanxiufei.cn/Article/details/gt2susgfpia.html

[Q23] 分页
来源：http://dali.zhixingplan.top/Article/details/gt2zgtseebb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.fengsongda.top/Article/details/gt2zvcqhmxl.html

[Q24] 去重
来源：http://dali.cdnleiting.top/Article/details/gt2ifkqmjsm.html

SELECT DISTINCT city FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2bfmaxoqj.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kecfoigo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ehwqpu.com/Article/details/gt2fkuvumdg.html

[Q26] 计数
来源：http://dali.daria6918.cn/Article/details/gt2fvsqnlyo.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2admurjzk.html

[Q27] 条件计数
来源：http://dali.fzhhl.top/Article/details/gt2uqeqyimc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2muadxxdk.html

[Q28] 求和与平均
来源：http://dali.gotoacloud.top/Article/details/gt2ancyiiul.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2jmjkyjkm.html

[Q29] 最大最小值
来源：http://dali.daria6918.cn/Article/details/gt2twvoqqwx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2mtkybihe.html

[Q30] 分组统计
来源：http://dali.jqgfzy.top/Article/details/gt2atcszynh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gt2sctbwnnb.html

[Q31] 分组后过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gt2knygbfyz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj202588.top/Article/details/gt2qdsxrtya.html

[Q32] 分组拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gt2sqzqgmks.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.316326.xyz/Article/details/gt2cbrrwuzr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.haohaochexian.top/Article/details/gt2cljbtrpi.html

[Q33] 多列分组
来源：http://dali.gogol.net.cn/Article/details/gt2qcscvheq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aibaodan.cn/Article/details/gt2fpjmucwq.html

[Q34] 每组取第一条
来源：http://dali.sufxvd.cn/Article/details/gt2lhuotdwy.html

SELECT * FROM (
来源：http://dali.ybcxt.top/Article/details/gt2eunfcmoi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tktotwpj.html

) t WHERE rn = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2jyfcbqwr.html

[Q35] 内连接
来源：http://dali.hammf.cn/Article/details/gt2vvtskgkh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.smart0.xyz/Article/details/gt2xigxqmmd.html

[Q36] 左连接
来源：http://dali.zycfv.cn/Article/details/gt2adeqjgid.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gt2tedoccqg.html

[Q37] 右连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dsbweijm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zycfv.cn/Article/details/gt2lwxnnnxa.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.wangdashe.top/Article/details/gt2maoujmar.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ticzjqcw.html

[Q39] 自连接（查上下级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mjfytsgd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhixingplan.top/Article/details/gt2tzyqngsg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.9152youxi.cn/Article/details/gt2dcohuktn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cucudq.cn/Article/details/gt2lotsgmur.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hnqzz.top/Article/details/gt2suwryiuj.html

[Q41] 多表连接
来源：http://dali.yj20258.top/Article/details/gt2yyupqnkw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jianghu66.top/Article/details/gt2ytfyuycp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ljwznvbp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gzhubu.top/Article/details/gt2qzakmziu.html

[Q42] 连接条件附加过滤
来源：http://dali.shangyingyoupin.top/Article/details/gt2fvgsqyqj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sxryk.cn/Article/details/gt2qmbjnalc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yongpay.top/Article/details/gt2gdbsfjzh.html

[Q43] 标量子查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2vroweyxg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ahluvfuh.html

[Q44] IN 子查询
来源：http://dali.jyoumei.cn/Article/details/gt2gktwvmma.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.guowangkeji.top/Article/details/gt2pxvdumkf.html

[Q45] EXISTS 判断存在
来源：http://dali.tianlin.xyz/Article/details/gt2eoenmpxd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yanxiufei.cn/Article/details/gt2kfsqsqbu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.svipenyu.cn/Article/details/gt2bqfgvkrc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxinkj.top/Article/details/gt2gpwuzusg.html

[Q47] 与平均值比较
来源：http://dali.hnqzz.top/Article/details/gt2cykohybd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.svipenyu.cn/Article/details/gt2pquxmeeq.html

[Q48] CTE 公用表表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xcwrnzyz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hnxiangtu.top/Article/details/gt2obmgpgzi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shangyingyoupin.top/Article/details/gt2egftvipt.html

[Q49] 更新单行
来源：http://dali.tanke756.top/Article/details/gt2ojpvvpuh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gt2pigauhuo.html

[Q50] 批量更新
来源：http://dali.fzhhl.top/Article/details/gt2aqhjqqzr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gt2sprybmgj.html

[Q51] 用子查询更新
来源：http://dali.ybcxt.top/Article/details/gt2likfwphw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenzaomai.com/Article/details/gt2xpnatyjp.html

[Q52] 删除指定行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2osngvrkn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.quarkkingdee.top/Article/details/gt2wezmfwug.html

[Q53] 按条件删除
来源：http://dali.wangshuangyany.cn/Article/details/gt2cgqnuaqy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.mhx1999.top/Article/details/gt2mxwibfrl.html

[Q54] 清空表
来源：http://dali.jinqigufen.top/Article/details/gt2ryycchde.html

TRUNCATE TABLE logs;
来源：http://dali.birdmap.top/Article/details/gt2lvpayquz.html

[Q55] 排名（并列占位）
来源：http://dali.yj202588.top/Article/details/gt2cppsvord.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2raeuvdaj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hongshengwenyu.top/Article/details/gt2uppksfao.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aizwys.cn/Article/details/gt2sawbqqli.html

[Q57] 行号
来源：http://dali.jiagoushi.top/Article/details/gt2tasdnfgc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2lnlpjxmc.html

[Q58] 累计求和
来源：http://dali.sufxvd.cn/Article/details/gt2bfbpzejq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.mhx1999.top/Article/details/gt2lyiybyfn.html

[Q59] 分组内累计
来源：http://dali.9152youxi.cn/Article/details/gt2zkzkxcyz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2xsaagjin.html

[Q60] 取上一行 / 下一行
来源：http://dali.cdnleiting.top/Article/details/gt2fksialpz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.svipenyu.cn/Article/details/gt2yugoiiiw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2makoiuhf.html

[Q61] 移动平均
来源：http://dali.yj20258.top/Article/details/gt2cvmnnwpn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gt2pltzkfjw.html

[Q62] 分组占比
来源：http://dali.sufxvd.cn/Article/details/gt2rernipgv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gt2jppodkvi.html

[Q63] 开启事务
来源：http://dali.cdnleiting.top/Article/details/gt2vbbxrsaz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj20258888.top/Article/details/gt2nmexjnyx.html

[Q64] 提交事务
来源：http://dali.guannengcc.top/Article/details/gt2movltciq.html

COMMIT;
来源：http://dali.cqqwz.cn/Article/details/gt2tihijzjf.html

[Q65] 回滚事务
来源：http://dali.guannengcc.top/Article/details/gt2lggxxeqg.html

ROLLBACK;
来源：http://dali.yj20258888.top/Article/details/gt2ppncdggs.html

[Q66] 行锁查询
来源：http://dali.redwolf501.top/Article/details/gt2tdkzpryo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xziqi.cn/Article/details/gt2okkceuhw.html

[Q67] 设置隔离级别
来源：http://dali.hammf.cn/Article/details/gt2ctveuwvp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.vqdsnc.cn/Article/details/gt2jvuremum.html

[Q68] 保存点
来源：http://dali.ybcxt.top/Article/details/gt2rdraddri.html

SAVEPOINT sp1;
来源：http://dali.jqgufenzy.top/Article/details/gt2xxylrjrv.html

ROLLBACK TO sp1;
来源：http://dali.tanke756.top/Article/details/gt2lbqnpvmt.html

[Q69] 查看执行计划
来源：http://dali.yvedp.cn/Article/details/gt2jjsytgqw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.guowangkeji.top/Article/details/gt2izekdxhv.html

[Q70] 更新统计信息
来源：http://dali.yuanzhike.top/Article/details/gt2gdlnmsyj.html

ANALYZE TABLE users;
来源：http://dali.iojbl.cn/Article/details/gt2iqsyvhhr.html

[Q71] 查看建表语句
来源：http://dali.jianghu66.top/Article/details/gt2albgtmjl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.pengpengdd.cyou/Article/details/gt2jvlnpzzu.html

[Q72] 查看索引
来源：http://dali.zhixingplan.top/Article/details/gt2yjtcdnhp.html

SHOW INDEX FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2zunziakm.html

[Q73] 查看表状态
来源：http://dali.pengpengdd.cyou/Article/details/gt2xbbylcqd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gt2kirgkcbj.html

[Q74] 强制使用索引
来源：http://dali.cheryme.top/Article/details/gt2zesnyfgu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhixingplan.top/Article/details/gt2ioijtgya.html

[Q75] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gt2ulexezpj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2edokefgj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.quarkkingdee.top/Article/details/gt2oqrlzuyk.html

[Q76] 按天统计
来源：http://dali.feifeiyinyue.top/Article/details/gt2byfndcsw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnqzz.top/Article/details/gt2pqvjlzzd.html

[Q77] 时间加减
来源：http://dali.nanxuanxn.top/Article/details/gt2aabgonry.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vprvkdan.html

[Q78] 当前时间
来源：http://dali.jinqigfzy.top/Article/details/gt2byuwaucr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.smart0.xyz/Article/details/gt2zkegrowv.html

[Q79] 字符串拼接
来源：http://dali.hammf.cn/Article/details/gt2epddgybx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vjqqwshc.html

[Q80] 字符串截取
来源：http://dali.sufxvd.cn/Article/details/gt2fusewjeq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2swiflvaw.html

[Q81] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gt2hpkmgjtm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2cqtgshpd.html

[Q82] 字符长度与字节长度
来源：http://dali.aibaodan.cn/Article/details/gt2uwhcppou.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gt2cxdjdlza.html

[Q83] 大小写转换
来源：http://dali.pycfn.com/Article/details/gt2yhlgmmta.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2znejsrrj.html

[Q84] 去除首尾空格
来源：http://dali.xziqi.cn/Article/details/gt2aekmtkxd.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2wuowhamh.html

[Q85] 数值取整
来源：http://dali.zhixingplan.top/Article/details/gt2ofskerxw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kyvfiqrk.html

[Q86] 读取 JSON 字段
来源：http://dali.xuetiantiany.cn/Article/details/gt2xqtxqejy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258888.top/Article/details/gt2fziizcxr.html

[Q87] JSON 字段做条件
来源：http://dali.birdmap.top/Article/details/gt2lhcrcnrv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.pycfn.com/Article/details/gt2kvqdsuuc.html

[Q88] 行转列（条件聚合）
来源：http://dali.cashguo.top/Article/details/gt2ovxzrbji.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yanxiufei.cn/Article/details/gt2xyuupvti.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2ggdjdzuo.html

[Q89] 判断表是否存在
来源：http://dali.ehwqpu.com/Article/details/gt2xdhrbbya.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cucudq.cn/Article/details/gt2cehxsdsx.html

[Q90] 生成序号列
来源：http://dali.bjfxy.top/Article/details/gt2pkjqyyon.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nanxinkj.top/Article/details/gt2dmssugsv.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2vxpprnfp.html

R. Bash 专题
来源：http://dali.yangfankeji.com/Article/details/gt2wawfihqg.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2woelathc.html

[R01] shebang 与严格模式
来源：http://dali.nanxinkj.top/Article/details/gt2wmuzbdyl.html

#!/usr/bin/env bash
来源：http://dali.quarkkingdee.top/Article/details/gt2rbkzgxri.html

set -euo pipefail
来源：http://dali.svipenyu.cn/Article/details/gt2abmuppoo.html

[R02] 变量赋值与使用
来源：http://dali.jqgufenzy.top/Article/details/gt2dybbtziw.html

name="Tom"; echo "$name"
来源：http://dali.hfpthk.cn/Article/details/gt2atnnlpaw.html

[R03] 只读变量
来源：http://dali.sufxvd.cn/Article/details/gt2juawftlz.html

readonly PI=3.14
来源：http://dali.hongshengwenyu.top/Article/details/gt2firkuooz.html

[R04] 位置参数
来源：http://dali.dianchejie.cn/Article/details/gt2afbbdtst.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jiagoushi.top/Article/details/gt2wgjlambs.html

[R05] 参数默认值
来源：http://dali.sweek.top/Article/details/gt2iiehvxne.html

name="${1:-default}"
来源：http://dali.shuidangran.top/Article/details/gt2sfquhgpy.html

[R06] 判断命令是否存在
来源：http://dali.yuxming.cn/Article/details/gt2rfwhmdnq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gt2uxjenevh.html

[R07] if 判断文件
来源：http://dali.yuanzhike.top/Article/details/gt2cygocsro.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ivvv.top/Article/details/gt2txcitoyb.html

[R08] 数值比较
来源：http://dali.svipenyu.cn/Article/details/gt2agxlywmo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yanxiufei.cn/Article/details/gt2mlmzysxm.html

[R09] 字符串比较
来源：http://dali.chenzaomai.com/Article/details/gt2sitlgugc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sufxvd.cn/Article/details/gt2gpfknxsv.html

[R10] 正则匹配
来源：http://dali.yuanzhike.top/Article/details/gt2watuefzw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.snrcjt.cn/Article/details/gt2qzfofqqu.html

[R11] case 多分支
来源：http://dali.yongpay.top/Article/details/gt2pxpaaoiy.html

case "$1" in
来源：http://dali.ivvv.top/Article/details/gt2hxftnysh.html

start) echo "启动" ;;
来源：http://dali.yangfankeji.com/Article/details/gt2sluypyio.html

stop)  echo "停止" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gt2xjnaqmru.html

*)     echo "未知命令" ;;
来源：http://dali.havefunace.top/Article/details/gt2qqerdzir.html

esac
来源：http://dali.gzhubu.top/Article/details/gt2dntvafca.html

[R12] for 遍历文件
来源：http://dali.yuxming.cn/Article/details/gt2ejuavljw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hywenlv.cn/Article/details/gt2nhjvmtsa.html

[R13] for 计数循环
来源：http://dali.sweek.top/Article/details/gt2rpasucty.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gt2toxplgzm.html

[R14] C 风格 for
来源：http://dali.feifeiyinyue.top/Article/details/gt2rbahngkm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.smart0.xyz/Article/details/gt2qhgueuml.html

[R15] while 逐行读文件
来源：http://dali.fzhhl.top/Article/details/gt2nzcbrcbb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.pycfn.com/Article/details/gt2rptetazf.html

[R16] until 等待条件
来源：http://dali.guannengcc.top/Article/details/gt2tdcanehc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ygqyuzyj.html

[R17] 数组定义与取值
来源：http://dali.ybcxt.top/Article/details/gt2dmpbckqn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.c1oappe.top/Article/details/gt2hpbyuolu.html

[R18] 遍历数组
来源：http://dali.hywenlv.cn/Article/details/gt2rfhctqfh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.andypj.xyz/Article/details/gt2ppbfuoum.html

[R19] 数组长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tdayufql.html

echo "${#arr[@]}"
来源：http://dali.guannengcc.top/Article/details/gt2zagilcch.html

[R20] 关联数组（字典）
来源：http://dali.yuxming.cn/Article/details/gt2mpozbkcm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yonumen.top/Article/details/gt2shncgdaj.html

[R21] 字符串长度
来源：http://dali.cashguo.top/Article/details/gt2scraoabc.html

echo "${#s}"
来源：http://dali.iojbl.cn/Article/details/gt2bayaeiab.html

[R22] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gt2egaxjxrf.html

echo "${s:0:5}"
来源：http://dali.smart0.xyz/Article/details/gt2owpjeodx.html

[R23] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zkmqgcrl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.fengsongda.top/Article/details/gt2brbrfexx.html

[R24] 大小写转换
来源：http://dali.yj202588.top/Article/details/gt2zmsxuvxk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.c1oappe.top/Article/details/gt2efqacjtt.html

[R25] 去后缀 / 去前缀
来源：http://dali.svipenyu.cn/Article/details/gt2kgnzoxyp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.meibo888.top/Article/details/gt2potmslyg.html

[R26] 命令替换
来源：http://dali.yuanzhike.top/Article/details/gt2zrhrjdum.html

now=$(date +%F); echo "$now"
来源：http://dali.shangyingyoupin.top/Article/details/gt2majnwqmr.html

[R27] 算术展开
来源：http://dali.zhiwuduotai.top/Article/details/gt2ysvdmnbh.html

echo $((1 + 2 * 3))
来源：http://dali.daria6918.cn/Article/details/gt2kiszzodg.html

[R28] 浮点运算
来源：http://dali.yuxming.cn/Article/details/gt2njxrrtzd.html

echo "scale=2; 10/3" | bc
来源：http://dali.dianchejie.cn/Article/details/gt2bdrcirwq.html

[R29] 定义函数
来源：http://dali.aibaodan.cn/Article/details/gt2plkwwuhx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shangyingyoupin.top/Article/details/gt2bhylkyjt.html

[R30] 函数返回状态码
来源：http://dali.ybcxt.top/Article/details/gt2nkgzcdjh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cashguo.top/Article/details/gt2guyltgyv.html

[R31] 局部变量
来源：http://dali.yongpay.top/Article/details/gt2nptcevbq.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnqzz.top/Article/details/gt2rgcbrwoi.html

[R32] 参数个数校验
来源：http://dali.iojbl.cn/Article/details/gt2fszokcij.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ixkpxsrn.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxuanxn.top/Article/details/gt2fqaxqugu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.dashuyun.cn/Article/details/gt2glbpeyqh.html

[R34] 退出时清理
来源：http://dali.gogol.net.cn/Article/details/gt2fwfqpbxo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gt2ctwjlnei.html

[R35] 后台执行并等待
来源：http://dali.tanke756.top/Article/details/gt2svsycnny.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iohawvkj.html

[R36] 并发执行多个任务
来源：http://dali.sufxvd.cn/Article/details/gt2ioteansi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tian-w.cn/Article/details/gt2xknokozl.html

[R37] 把输出赋给变量
来源：http://dali.xylfe.cn/Article/details/gt2duqluswk.html

files=$(ls -1)
来源：http://dali.fzhhl.top/Article/details/gt2bghswpsf.html

[R38] 管道串联
来源：http://dali.xuanzx.com/Article/details/gt2rumbigod.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuanzhike.top/Article/details/gt2cgzeddeh.html

[R39] 重定向标准输出与错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vtwmrgud.html

cmd > out.log 2>&1
来源：http://dali.tian-w.cn/Article/details/gt2hxkagpwf.html

[R40] 追加写日志
来源：http://dali.iojbl.cn/Article/details/gt2vkcvjetl.html

echo "log" >> out.log
来源：http://dali.ivvv.top/Article/details/gt2bojniexr.html

[R41] 丢弃输出
来源：http://dali.zycfv.cn/Article/details/gt2rnaxsjkp.html

cmd >/dev/null 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sedurjug.html

[R42] 输入重定向
来源：http://dali.yuxming.cn/Article/details/gt2opdyjxpo.html

wc -l < a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2orfwkfxb.html

[R43] 按名字查找文件
来源：http://dali.aizwys.cn/Article/details/gt2gazmjnrd.html

find . -name "*.log" -type f
来源：http://dali.birdmap.top/Article/details/gt2pwgnxsjw.html

[R44] 按修改时间查找
来源：http://dali.cashguo.top/Article/details/gt2qwusfmop.html

find . -mtime -7 -type f
来源：http://dali.mhx1999.top/Article/details/gt2yeenzlhd.html

[R45] 批量删除
来源：http://dali.ehwqpu.com/Article/details/gt2kainuxxk.html

find . -name "*.tmp" -delete
来源：http://dali.daxiang520.top/Article/details/gt2ttemttov.html

[R46] 递归替换文件内容
来源：http://dali.aibaodan.cn/Article/details/gt2zgqchqxo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258.top/Article/details/gt2jdorgfzi.html

[R47] sed 单行替换
来源：http://dali.xuanzx.com/Article/details/gt2dxuabqcc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2vdrutdpz.html

[R48] awk 取指定列
来源：http://dali.yj202588.top/Article/details/gt2fuwueycp.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2swgcmrtz.html

[R49] awk 带条件
来源：http://dali.jianghu66.top/Article/details/gt2bgbtixjs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jyoumei.cn/Article/details/gt2ryoubrlm.html

[R50] awk 求和
来源：http://dali.hongshengwenyu.top/Article/details/gt2ilntaixb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gt2wbnmfvph.html

[R51] 排序去重取前几
来源：http://dali.guannengcc.top/Article/details/gt2iuswxccp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhiwuduotai.top/Article/details/gt2bvodcxqm.html

[R52] 统计行数
来源：http://dali.hongshengwenyu.top/Article/details/gt2zyqfhnva.html

wc -l a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nmcdtkbq.html

[R53] 查看文件头与实时尾
来源：http://dali.zdqjudy.top/Article/details/gt2bvgsrktf.html


<!-- 参考信息 -->