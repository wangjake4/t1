代发 wailian999

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gogol.net.cn/Article/details/gt2lfpbhmdu.html

[Q07] 删除表
来源：http://dali.tian-w.cn/Article/details/gt2ctxcspfi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xinyue.icu/Article/details/gt2fgsywhfd.html

[Q08] 创建普通索引
来源：http://dali.zhengqikj.top/Article/details/gt2rmljknin.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.fzhhl.top/Article/details/gt2bvvzaxfk.html

[Q09] 创建唯一索引
来源：http://dali.gaohongyu789.top/Article/details/gt2ezicyrsh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yonumen.top/Article/details/gt2pgcdcpat.html

[Q10] 插入单行
来源：http://dali.tanke756.top/Article/details/gt2xtgsjvdc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gt2mvvgxvry.html

[Q11] 一次插入多行
来源：http://dali.xziqi.cn/Article/details/gt2qqwdmaaq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ehwqpu.com/Article/details/gt2krhiwljx.html

[Q12] 插入后取自增 ID
来源：http://dali.zhiwuduotai.top/Article/details/gt2pydchnix.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.snrcjt.cn/Article/details/gt2pflbaovz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuanzhike.top/Article/details/gt2zdqjblmv.html

[Q13] 忽略重复插入
来源：http://dali.jinqigfzy.top/Article/details/gt2vvzriwch.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sweek.top/Article/details/gt2azkzeczk.html

[Q14] 存在则更新（upsert）
来源：http://dali.hfpthk.cn/Article/details/gt2dwpcujkv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.aizwys.cn/Article/details/gt2ibbjeggo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yongpay.top/Article/details/gt2ifgyysiu.html

[Q15] 查询全部
来源：http://dali.andypj.xyz/Article/details/gt2nfkjfelq.html

SELECT * FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2inurgdki.html

[Q16] 查询指定列
来源：http://dali.hnqzz.top/Article/details/gt2wigsrrbj.html

SELECT id, name FROM users;
来源：http://dali.pycfn.com/Article/details/gt2xabptysx.html

[Q17] 条件查询
来源：http://dali.yvedp.cn/Article/details/gt2wgjcqlfx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yuxming.cn/Article/details/gt2pwnfmapy.html

[Q18] 模糊匹配
来源：http://dali.svipenyu.cn/Article/details/gt2hdkouvha.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hywenlv.cn/Article/details/gt2aygjzmen.html

[Q19] 范围查询
来源：http://dali.yongpay.top/Article/details/gt2eupefwmm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hfpthk.cn/Article/details/gt2wuciyxqk.html

[Q20] IN 列表
来源：http://dali.zhongyouzk.top/Article/details/gt2sxbvlhae.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2ugviistp.html

[Q21] 空值判断
来源：http://dali.cashguo.top/Article/details/gt2pdkttflb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.aizwys.cn/Article/details/gt2lvqyjprg.html

[Q22] 排序
来源：http://dali.hysaishi.cn/Article/details/gt2hoqhimit.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2trnpdvvf.html

[Q23] 分页
来源：http://dali.fengsongda.top/Article/details/gt2jrbhfhuz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj202588.top/Article/details/gt2kbkgblsa.html

[Q24] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gt2ahrgpyed.html

SELECT DISTINCT city FROM users;
来源：http://dali.sweek.top/Article/details/gt2cznvnhia.html

[Q25] 只取前 N 条
来源：http://dali.zhiwuduotai.top/Article/details/gt2mhnkjfgk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daxiang520.top/Article/details/gt2nvcrsorm.html

[Q26] 计数
来源：http://dali.ybcxt.top/Article/details/gt2edqoneeg.html

SELECT COUNT(*) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bzxzcgmc.html

[Q27] 条件计数
来源：http://dali.pycfn.com/Article/details/gt2xwjoqhvb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2hslsvpmm.html

[Q28] 求和与平均
来源：http://dali.chenlongwang.top/Article/details/gt2neeshrpc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2ctlouryv.html

[Q29] 最大最小值
来源：http://dali.shangyingyoupin.top/Article/details/gt2dzzrvsdd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2htdmhsax.html

[Q30] 分组统计
来源：http://dali.fzhhl.top/Article/details/gt2cuaxzdvo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jgbueedz.html

[Q31] 分组后过滤
来源：http://dali.iojbl.cn/Article/details/gt2zfxnndhj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nanxinkj.top/Article/details/gt2fskrgelt.html

[Q32] 分组拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2bexpiaky.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gt2yhfdwsln.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cashguo.top/Article/details/gt2tyroorvw.html

[Q33] 多列分组
来源：http://dali.cqqwz.cn/Article/details/gt2aqvmjyij.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sweek.top/Article/details/gt2rokafwoe.html

[Q34] 每组取第一条
来源：http://dali.daria6918.cn/Article/details/gt2ujlqihgr.html

SELECT * FROM (
来源：http://dali.zhiwuduotai.top/Article/details/gt2rdbusxet.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.0kj1m.cn/Article/details/gt2syrtzbkf.html

) t WHERE rn = 1;
来源：http://dali.tian-w.cn/Article/details/gt2fmsrkqhm.html

[Q35] 内连接
来源：http://dali.tianlin.xyz/Article/details/gt2ojyovqcb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gt2nlcdklur.html

[Q36] 左连接
来源：http://dali.ybcxt.top/Article/details/gt2zheadwyi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gt2mvdouuiv.html

[Q37] 右连接
来源：http://dali.nwbrower.top/Article/details/gt2khxqyaqh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhoulong.xyz/Article/details/gt2kfnbvwuc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xylfe.cn/Article/details/gt2wksbvrfp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cqqwz.cn/Article/details/gt2zfxqubnc.html

[Q39] 自连接（查上下级）
来源：http://dali.zycfv.cn/Article/details/gt2dfeibwwr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xylfe.cn/Article/details/gt2dnmibmml.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.c1oappe.top/Article/details/gt2rqjbzsph.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangdashe.top/Article/details/gt2ltaskpww.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.guannengcc.top/Article/details/gt2cfachauk.html

[Q41] 多表连接
来源：http://dali.jinqigufen.top/Article/details/gt2jsxsvpei.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.316326.xyz/Article/details/gt2fjlgfbfo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhongyouzk.top/Article/details/gt2ikfpefqa.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.fengsongda.top/Article/details/gt2nkqlygzn.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxuanxn.top/Article/details/gt2oqycqurx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.fzhhl.top/Article/details/gt2jmvdpztf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hongshengwenyu.top/Article/details/gt2qhuldxmv.html

[Q43] 标量子查询
来源：http://dali.feifeiyinyue.top/Article/details/gt2lokyhawo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.snrcjt.cn/Article/details/gt2igtjcabb.html

[Q44] IN 子查询
来源：http://dali.iojbl.cn/Article/details/gt2afjkzmhi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.316326.xyz/Article/details/gt2vlnddyjf.html

[Q45] EXISTS 判断存在
来源：http://dali.hnqzz.top/Article/details/gt2fegdliwh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ykdqfvjn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lndfwvny.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cheryme.top/Article/details/gt2jfsacbvl.html

[Q47] 与平均值比较
来源：http://dali.chenlongwang.top/Article/details/gt2qdxqbrjq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fengsongda.top/Article/details/gt2kznpnttd.html

[Q48] CTE 公用表表达式
来源：http://dali.hfpthk.cn/Article/details/gt2hgpccwzp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ehwqpu.com/Article/details/gt2bhifmyop.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hfpthk.cn/Article/details/gt2dzbwifgp.html

[Q49] 更新单行
来源：http://dali.hywenlv.cn/Article/details/gt2nobbtukl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zycfv.cn/Article/details/gt2wnwrzubv.html

[Q50] 批量更新
来源：http://dali.chenjidiqi.icu/Article/details/gt2seqbrcrv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.havefunace.top/Article/details/gt2deiddukb.html

[Q51] 用子查询更新
来源：http://dali.cheryme.top/Article/details/gt2fzzwyuci.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cucudq.cn/Article/details/gt2zgachrcg.html

[Q52] 删除指定行
来源：http://dali.xziqi.cn/Article/details/gt2ygtkvksp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gt2oefjxhgz.html

[Q53] 按条件删除
来源：http://dali.9152youxi.cn/Article/details/gt2knunafzr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yueranfly.top/Article/details/gt2mlnldpid.html

[Q54] 清空表
来源：http://dali.feifeiyinyue.top/Article/details/gt2nimdvhvj.html

TRUNCATE TABLE logs;
来源：http://dali.yj202588.top/Article/details/gt2qwqshfka.html

[Q55] 排名（并列占位）
来源：http://dali.xziqi.cn/Article/details/gt2xhnkswia.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gt2dbvdejkp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ivvv.top/Article/details/gt2qtgkoxhe.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.316326.xyz/Article/details/gt2rtlyddbe.html

[Q57] 行号
来源：http://dali.daria6918.cn/Article/details/gt2ltimskkn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2jvqdhlvc.html

[Q58] 累计求和
来源：http://dali.shuidangran.top/Article/details/gt2inxpbhxq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gt2uhzjrezg.html

[Q59] 分组内累计
来源：http://dali.yuanzhike.top/Article/details/gt2pkmgbyge.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.havefunace.top/Article/details/gt2xisooawc.html

[Q60] 取上一行 / 下一行
来源：http://dali.jyoumei.cn/Article/details/gt2gmrzrbvk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xuanzx.com/Article/details/gt2jeepqwpg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.316326.xyz/Article/details/gt2lhuhdzww.html

[Q61] 移动平均
来源：http://dali.9152youxi.cn/Article/details/gt2cuykwudx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2vmtaxivh.html

[Q62] 分组占比
来源：http://dali.yueranfly.top/Article/details/gt2kqtufphu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gt2fpmebdbk.html

[Q63] 开启事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jtaldxuq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2niwiqbtr.html

[Q64] 提交事务
来源：http://dali.zhixingplan.top/Article/details/gt2gbihkwdk.html

COMMIT;
来源：http://dali.zdqjudy.top/Article/details/gt2xrceajnb.html

[Q65] 回滚事务
来源：http://dali.c1oappe.top/Article/details/gt2zlbpjzxv.html

ROLLBACK;
来源：http://dali.daxiang520.top/Article/details/gt2psaphcfn.html

[Q66] 行锁查询
来源：http://dali.0kj1m.cn/Article/details/gt2xfpccjhy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.c1oappe.top/Article/details/gt2pwxzqnfb.html

[Q67] 设置隔离级别
来源：http://dali.jqgufenzy.top/Article/details/gt2mmeyxxjg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aibaodan.cn/Article/details/gt2qdiwcopv.html

[Q68] 保存点
来源：http://dali.feifeiyinyue.top/Article/details/gt2gxhwlptm.html

SAVEPOINT sp1;
来源：http://dali.ppjwa.cn/Article/details/gt2jikjibyb.html

ROLLBACK TO sp1;
来源：http://dali.bjfxy.top/Article/details/gt2crhnkxak.html

[Q69] 查看执行计划
来源：http://dali.bjfxy.top/Article/details/gt2vnxdnzza.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jianghu66.top/Article/details/gt2xxgincmd.html

[Q70] 更新统计信息
来源：http://dali.hysaishi.cn/Article/details/gt2tgokrhzq.html

ANALYZE TABLE users;
来源：http://dali.gaohongyu789.top/Article/details/gt2hrjynosp.html

[Q71] 查看建表语句
来源：http://dali.redwolf501.top/Article/details/gt2wmpetvxv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dashuyun.cn/Article/details/gt2awlwmqfg.html

[Q72] 查看索引
来源：http://dali.jianghu66.top/Article/details/gt2ehenevlv.html

SHOW INDEX FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2duxlbxvt.html

[Q73] 查看表状态
来源：http://dali.dashuyun.cn/Article/details/gt2cuzdumda.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258888.top/Article/details/gt2rwkfromk.html

[Q74] 强制使用索引
来源：http://dali.jqgfzy.top/Article/details/gt2jkptmzmd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hammf.cn/Article/details/gt2dwxrchje.html

[Q75] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gt2qedqhodl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zycfv.cn/Article/details/gt2cnmmgkyr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dianchejie.cn/Article/details/gt2pypwtatu.html

[Q76] 按天统计
来源：http://dali.xuetiantiany.cn/Article/details/gt2bvctdktw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.meibo888.top/Article/details/gt2awcmzjdx.html

[Q77] 时间加减
来源：http://dali.cdnleiting.top/Article/details/gt2syawdbmz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.aibaodan.cn/Article/details/gt2ekjqqnxh.html

[Q78] 当前时间
来源：http://dali.zhengqikj.top/Article/details/gt2ckautsfi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yongpay.top/Article/details/gt2tkvmybvu.html

[Q79] 字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gt2frkhgxtj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.dashuyun.cn/Article/details/gt2lzrhydwn.html

[Q80] 字符串截取
来源：http://dali.wangdashe.top/Article/details/gt2rpvqyhgr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2ibzsdczg.html

[Q81] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gt2fmivazqa.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj202588.top/Article/details/gt2hanivyap.html

[Q82] 字符长度与字节长度
来源：http://dali.c1oappe.top/Article/details/gt2bubtrkbr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wfhaspwe.html

[Q83] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gt2qhqxaxlt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2jkdgglfu.html

[Q84] 去除首尾空格
来源：http://dali.daria6918.cn/Article/details/gt2zsbusrns.html

SELECT TRIM(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gt2mlafhgnv.html

[Q85] 数值取整
来源：http://dali.yangfankeji.com/Article/details/gt2ljnvdmwx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.c1oappe.top/Article/details/gt2xblmkakk.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigfzy.top/Article/details/gt2afrjpqus.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.daxiang520.top/Article/details/gt2bvypqdku.html

[Q87] JSON 字段做条件
来源：http://dali.chenzaomai.com/Article/details/gt2paexvjly.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gzhubu.top/Article/details/gt2sposozee.html

[Q88] 行转列（条件聚合）
来源：http://dali.sxryk.cn/Article/details/gt2guzjdtse.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sxryk.cn/Article/details/gt2oqdguazw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2nfadhgun.html

[Q89] 判断表是否存在
来源：http://dali.sufxvd.cn/Article/details/gt2mjadfwfw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tygwdxec.html

[Q90] 生成序号列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kdmcrzee.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhoulong.xyz/Article/details/gt2jakjrtjn.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2wpwsblaw.html

R. Bash 专题
来源：http://dali.havefunace.top/Article/details/gt2dszefoqo.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2qiwsddcr.html

[R01] shebang 与严格模式
来源：http://dali.meibo888.top/Article/details/gt2pvmqztrx.html

#!/usr/bin/env bash
来源：http://dali.hammf.cn/Article/details/gt2awkophva.html

set -euo pipefail
来源：http://dali.shangyingyoupin.top/Article/details/gt2zvefxpig.html

[R02] 变量赋值与使用
来源：http://dali.haohaochexian.top/Article/details/gt2skzvhnnf.html

name="Tom"; echo "$name"
来源：http://dali.zhiwuduotai.top/Article/details/gt2bxvqdhoy.html

[R03] 只读变量
来源：http://dali.snrcjt.cn/Article/details/gt2gybryrhp.html

readonly PI=3.14
来源：http://dali.mhx1999.top/Article/details/gt2rfcqovla.html

[R04] 位置参数
来源：http://dali.zhongyouzk.top/Article/details/gt2tnsxoaut.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shuidangran.top/Article/details/gt2hdesxzwz.html

[R05] 参数默认值
来源：http://dali.hammf.cn/Article/details/gt2balpcucd.html

name="${1:-default}"
来源：http://dali.cheryme.top/Article/details/gt2waeibemi.html

[R06] 判断命令是否存在
来源：http://dali.yueranfly.top/Article/details/gt2sofoyzit.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.vqdsnc.cn/Article/details/gt2fghfjkqt.html

[R07] if 判断文件
来源：http://dali.wangdashe.top/Article/details/gt2bumbclsw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.havefunace.top/Article/details/gt2cbhpcwji.html

[R08] 数值比较
来源：http://dali.daria6918.cn/Article/details/gt2hmnqcioo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guannengcc.top/Article/details/gt2ebpyaqfk.html

[R09] 字符串比较
来源：http://dali.c1oappe.top/Article/details/gt2wycewmdm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jianghu66.top/Article/details/gt2dmqkcwjr.html

[R10] 正则匹配
来源：http://dali.yangfankeji.com/Article/details/gt2clsuriba.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hfpthk.cn/Article/details/gt2lykoviqv.html

[R11] case 多分支
来源：http://dali.jinqigufen.top/Article/details/gt2ncckmxdo.html

case "$1" in
来源：http://dali.hnxiangtu.top/Article/details/gt2rpnbigai.html

start) echo "启动" ;;
来源：http://dali.fengsongda.top/Article/details/gt2xhzjobgk.html

stop)  echo "停止" ;;
来源：http://dali.hywenlv.cn/Article/details/gt2ctmwyfkh.html

*)     echo "未知命令" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vwfdagzl.html

esac
来源：http://dali.ivvv.top/Article/details/gt2zjjaqtno.html

[R12] for 遍历文件
来源：http://dali.svipenyu.cn/Article/details/gt2uxucljam.html

for f in *.txt; do echo "$f"; done
来源：http://dali.bjfxy.top/Article/details/gt2ipjzvcoy.html

[R13] for 计数循环
来源：http://dali.cdnleiting.top/Article/details/gt2pudevyyr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gt2ziowigvy.html

[R14] C 风格 for
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rluzzwlw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2dxumcebl.html

[R15] while 逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2boluzgrw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sufxvd.cn/Article/details/gt2duaprtcw.html

[R16] until 等待条件
来源：http://dali.chenjidiqi.icu/Article/details/gt2dpwrwzft.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gt2smpljjio.html

[R17] 数组定义与取值
来源：http://dali.xuetiantiany.cn/Article/details/gt2nbecobgv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenlongwang.top/Article/details/gt2ihrwuakb.html

[R18] 遍历数组
来源：http://dali.yonumen.top/Article/details/gt2hoyylysv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigfzy.top/Article/details/gt2dlvgilub.html

[R19] 数组长度
来源：http://dali.tanke756.top/Article/details/gt2lvacbcpw.html

echo "${#arr[@]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iflksgxo.html

[R20] 关联数组（字典）
来源：http://dali.jinqigufen.top/Article/details/gt2ynvmgqcy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yanxiufei.cn/Article/details/gt2dnbkibha.html

[R21] 字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gt2gqqavjzg.html

echo "${#s}"
来源：http://dali.daxiang520.top/Article/details/gt2dpmprxgo.html

[R22] 截取子串
来源：http://dali.9152youxi.cn/Article/details/gt2lvobtqon.html

echo "${s:0:5}"
来源：http://dali.tianlin.xyz/Article/details/gt2bzslgudf.html

[R23] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gt2fzgruelu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hfpthk.cn/Article/details/gt2msuzcvmp.html

[R24] 大小写转换
来源：http://dali.birdmap.top/Article/details/gt2etywuedi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ydzc1.top/Article/details/gt2nsnkejxy.html

[R25] 去后缀 / 去前缀
来源：http://dali.ivvv.top/Article/details/gt2bpvqtycv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tanke756.top/Article/details/gt2gfwsxykh.html

[R26] 命令替换
来源：http://dali.birdmap.top/Article/details/gt2btmugamy.html

now=$(date +%F); echo "$now"
来源：http://dali.zycfv.cn/Article/details/gt2kzwiieue.html

[R27] 算术展开
来源：http://dali.sufxvd.cn/Article/details/gt2rnqwzqsa.html

echo $((1 + 2 * 3))
来源：http://dali.sweek.top/Article/details/gt2uvrfhupx.html

[R28] 浮点运算
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kyqxegyv.html

echo "scale=2; 10/3" | bc
来源：http://dali.hywenlv.cn/Article/details/gt2rcdootsb.html

[R29] 定义函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ezwnwqeh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.c1oappe.top/Article/details/gt2sakdkuox.html

[R30] 函数返回状态码
来源：http://dali.ppjwa.cn/Article/details/gt2ngkypsan.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jiagoushi.top/Article/details/gt2gwnlpbwi.html

[R31] 局部变量
来源：http://dali.xuanzx.com/Article/details/gt2bibtqley.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2aposgcaq.html

[R32] 参数个数校验
来源：http://dali.chenjidiqi.icu/Article/details/gt2yjxjueik.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gt2vzahggfg.html

[R33] 捕获错误并提示行号
来源：http://dali.chenlongwang.top/Article/details/gt2bdhmrzko.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.quarkkingdee.top/Article/details/gt2imkrhczj.html

[R34] 退出时清理
来源：http://dali.yangfankeji.com/Article/details/gt2bxalzmdg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gt2ywktjpwm.html

[R35] 后台执行并等待
来源：http://dali.cdnleiting.top/Article/details/gt2yfcyicqz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhiwuduotai.top/Article/details/gt2ruoajcwz.html

[R36] 并发执行多个任务
来源：http://dali.hammf.cn/Article/details/gt2lafscmyt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yanxiufei.cn/Article/details/gt2niixotdu.html

[R37] 把输出赋给变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sblqtnzt.html

files=$(ls -1)
来源：http://dali.cucudq.cn/Article/details/gt2apgqbfsy.html

[R38] 管道串联
来源：http://dali.yonumen.top/Article/details/gt2hmncldrt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cashguo.top/Article/details/gt2jolgjgtn.html

[R39] 重定向标准输出与错误
来源：http://dali.snrcjt.cn/Article/details/gt2yxjjlpci.html

cmd > out.log 2>&1
来源：http://dali.pengpengdd.cyou/Article/details/gt2eqxumlvi.html

[R40] 追加写日志
来源：http://dali.svipenyu.cn/Article/details/gt2qjgkurtp.html

echo "log" >> out.log
来源：http://dali.gogol.net.cn/Article/details/gt2dxmfflvf.html

[R41] 丢弃输出
来源：http://dali.yanxiufei.cn/Article/details/gt2zyqcosqy.html

cmd >/dev/null 2>&1
来源：http://dali.shuidangran.top/Article/details/gt2pqzbwmzy.html

[R42] 输入重定向
来源：http://dali.quarkkingdee.top/Article/details/gt2bicyldwt.html

wc -l < a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2kjxdllzh.html

[R43] 按名字查找文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zljbelff.html

find . -name "*.log" -type f
来源：http://dali.zhongyouzk.top/Article/details/gt2siltvcxm.html

[R44] 按修改时间查找
来源：http://dali.shangyingyoupin.top/Article/details/gt2djlkrhsl.html

find . -mtime -7 -type f
来源：http://dali.zdqjudy.top/Article/details/gt2pdkyxaro.html

[R45] 批量删除
来源：http://dali.tianlin.xyz/Article/details/gt2jdohzjmg.html

find . -name "*.tmp" -delete
来源：http://dali.redwolf501.top/Article/details/gt2bqhmsnrf.html

[R46] 递归替换文件内容
来源：http://dali.birdmap.top/Article/details/gt2vljipmsc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhengqikj.top/Article/details/gt2ahtnnuvr.html

[R47] sed 单行替换
来源：http://dali.tianlin.xyz/Article/details/gt2gyigtpgw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2ycjvmidu.html

[R48] awk 取指定列
来源：http://dali.snrcjt.cn/Article/details/gt2nazcaniu.html

awk '{print $1, $3}' a.txt
来源：http://dali.smart0.xyz/Article/details/gt2tnyvmpit.html

[R49] awk 带条件
来源：http://dali.snrcjt.cn/Article/details/gt2puuummke.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgfzy.top/Article/details/gt2eqtwfxyp.html

[R50] awk 求和
来源：http://dali.tianlin.xyz/Article/details/gt2quxeewil.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ushuimzo.html

[R51] 排序去重取前几
来源：http://dali.zhongyouzk.top/Article/details/gt2bbyohztq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dashuyun.cn/Article/details/gt2tjffxpyf.html

[R52] 统计行数
来源：http://dali.zhengqikj.top/Article/details/gt2otkwvpsi.html

wc -l a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2kucztcra.html

[R53] 查看文件头与实时尾
来源：http://dali.aibaodan.cn/Article/details/gt2bdzqfpux.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jlsjyb.cn/Article/details/gt2frhuqbmn.html

[R54] 比较两个文件
来源：http://dali.316326.xyz/Article/details/gt2chgujhdl.html

diff a.txt b.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2qnmzewhs.html

[R55] 压缩与解压
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eavrldvn.html


<!-- 参考信息 -->