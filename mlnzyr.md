代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhixingplan.top/Article/details/gt2tzlszoqu.html

[Q05] 重命名列
来源：http://dali.cqqwz.cn/Article/details/gt2srllyvcg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xuanzx.com/Article/details/gt2cecljtcn.html

[Q06] 删除列
来源：http://dali.zhixingplan.top/Article/details/gt2svonsnaj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shzxlz.cn/Article/details/gt2nwmkejkj.html

[Q07] 删除表
来源：http://dali.c1oappe.top/Article/details/gt2fxwrojix.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2jeuztmzf.html

[Q08] 创建普通索引
来源：http://dali.xuanzx.com/Article/details/gt2fvufvooe.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hongshengwenyu.top/Article/details/gt2bffewvha.html

[Q09] 创建唯一索引
来源：http://dali.iojbl.cn/Article/details/gt2xruvejoe.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.316326.xyz/Article/details/gt2eoegijrk.html

[Q10] 插入单行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cpotqchg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gt2uvxvwaad.html

[Q11] 一次插入多行
来源：http://dali.birdmap.top/Article/details/gt2combzsdo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2iwliexzl.html

[Q12] 插入后取自增 ID
来源：http://dali.mhx1999.top/Article/details/gt2qcdtgvau.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.316326.xyz/Article/details/gt2ejzuzyuq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.9152youxi.cn/Article/details/gt2ezuigwtt.html

[Q13] 忽略重复插入
来源：http://dali.ehwqpu.com/Article/details/gt2ohcelpzq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.havefunace.top/Article/details/gt2gwcpqjqn.html

[Q14] 存在则更新（upsert）
来源：http://dali.guowangkeji.top/Article/details/gt2bcqsiukf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wzbtlrpx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xudqslgl.html

[Q15] 查询全部
来源：http://dali.ydzc1.top/Article/details/gt2kzdtxukh.html

SELECT * FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2vpebyozv.html

[Q16] 查询指定列
来源：http://dali.chenzaomai.com/Article/details/gt2khgxkugq.html

SELECT id, name FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2heeodovo.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmzipfi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2uvitfmrj.html

[Q18] 模糊匹配
来源：http://dali.c1oappe.top/Article/details/gt2izpjvful.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhoulong.xyz/Article/details/gt2outkuyek.html

[Q19] 范围查询
来源：http://dali.chenjidiqi.icu/Article/details/gt2jcxeqacm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhongyouzk.top/Article/details/gt2ciyohutn.html

[Q20] IN 列表
来源：http://dali.xinyue.icu/Article/details/gt2dwsgazqc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.feifeiyinyue.top/Article/details/gt2cilmocsu.html

[Q21] 空值判断
来源：http://dali.ybcxt.top/Article/details/gt2sflfxpra.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gaohongyu789.top/Article/details/gt2kfyilnvr.html

[Q22] 排序
来源：http://dali.hammf.cn/Article/details/gt2xltsyyeu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hnqzz.top/Article/details/gt2xpybeqjd.html

[Q23] 分页
来源：http://dali.chenlongwang.top/Article/details/gt2prhybiri.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.316326.xyz/Article/details/gt2zgfnfzti.html

[Q24] 去重
来源：http://dali.fengsongda.top/Article/details/gt2dlekfnfg.html

SELECT DISTINCT city FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2prrbbkfm.html

[Q25] 只取前 N 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gezevmab.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xziqi.cn/Article/details/gt2aiidizsc.html

[Q26] 计数
来源：http://dali.jqgfzy.top/Article/details/gt2lpubcigq.html

SELECT COUNT(*) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2segqhiai.html

[Q27] 条件计数
来源：http://dali.zhoulong.xyz/Article/details/gt2dgdbuitf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2pgqepohq.html

[Q28] 求和与平均
来源：http://dali.cqqwz.cn/Article/details/gt2asknzowh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gt2rjxgrkzn.html

[Q29] 最大最小值
来源：http://dali.meibo888.top/Article/details/gt2bbrpqodn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2cxxghzqu.html

[Q30] 分组统计
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gqexltbn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gt2jqxkejwm.html

[Q31] 分组后过滤
来源：http://dali.cheryme.top/Article/details/gt2rwvrlbhk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.9152youxi.cn/Article/details/gt2xdbgcsem.html

[Q32] 分组拼接字符串
来源：http://dali.sysykeji.top/Article/details/gt2xujkuwut.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gt2coojheqr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258888.top/Article/details/gt2knvjvuhm.html

[Q33] 多列分组
来源：http://dali.jianghu66.top/Article/details/gt2ovppvhis.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.snrcjt.cn/Article/details/gt2riruxkie.html

[Q34] 每组取第一条
来源：http://dali.yuanzhike.top/Article/details/gt2cwfubqml.html

SELECT * FROM (
来源：http://dali.bjfxy.top/Article/details/gt2mzimejya.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ivvv.top/Article/details/gt2frrqnhkl.html

) t WHERE rn = 1;
来源：http://dali.xziqi.cn/Article/details/gt2mawdtyqk.html

[Q35] 内连接
来源：http://dali.hysaishi.cn/Article/details/gt2okpxysnj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2siicvlrp.html

[Q36] 左连接
来源：http://dali.cashguo.top/Article/details/gt2lkzzmugv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.pycfn.com/Article/details/gt2crfbyayb.html

[Q37] 右连接
来源：http://dali.yanxiufei.cn/Article/details/gt2aqceokbz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigufen.top/Article/details/gt2hwjumldb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhengqikj.top/Article/details/gt2qrngjbjk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.9152youxi.cn/Article/details/gt2bdeksqfs.html

[Q39] 自连接（查上下级）
来源：http://dali.sysykeji.top/Article/details/gt2hcuhkkem.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xuanzx.com/Article/details/gt2xqadstzr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwijlfo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xziqi.cn/Article/details/gt2xmgxefyy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangshuangyany.cn/Article/details/gt2tdjqgysp.html

[Q41] 多表连接
来源：http://dali.zdqjudy.top/Article/details/gt2kqhqozkm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.mhx1999.top/Article/details/gt2ledsisiv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ehwqpu.com/Article/details/gt2extaamjx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nanxinkj.top/Article/details/gt2rqmclylm.html

[Q42] 连接条件附加过滤
来源：http://dali.jianghu66.top/Article/details/gt2ugsapzot.html

SELECT u.name, o.amount FROM users u
来源：http://dali.aizwys.cn/Article/details/gt2wxnfqcas.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhiwuduotai.top/Article/details/gt2vmhaputi.html

[Q43] 标量子查询
来源：http://dali.kuanghao11.cn/Article/details/gt2tnmmgswh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.quarkkingdee.top/Article/details/gt2xzijorze.html

[Q44] IN 子查询
来源：http://dali.guannengcc.top/Article/details/gt2zobpxnvu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.fengsongda.top/Article/details/gt2wfjqbapo.html

[Q45] EXISTS 判断存在
来源：http://dali.hfpthk.cn/Article/details/gt2ikffgwya.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guowangkeji.top/Article/details/gt2bbbskeav.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sysykeji.top/Article/details/gt2gmldjuwt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gt2axbgrszd.html

[Q47] 与平均值比较
来源：http://dali.andypj.xyz/Article/details/gt2eeqrppay.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xinyue.icu/Article/details/gt2jvgmdqwm.html

[Q48] CTE 公用表表达式
来源：http://dali.ybcxt.top/Article/details/gt2qdgbmzhq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj202588.top/Article/details/gt2mxaxarzj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yueranfly.top/Article/details/gt2melolvdw.html

[Q49] 更新单行
来源：http://dali.ppjwa.cn/Article/details/gt2ckiyifoq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gt2zgeqqmtm.html

[Q50] 批量更新
来源：http://dali.wangdashe.top/Article/details/gt2qwcellzx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.9152youxi.cn/Article/details/gt2zlfxiegr.html

[Q51] 用子查询更新
来源：http://dali.yuxming.cn/Article/details/gt2mvtynxgu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2wpukfzkf.html

[Q52] 删除指定行
来源：http://dali.andypj.xyz/Article/details/gt2rhhqimho.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigfzy.top/Article/details/gt2qpdlgznm.html

[Q53] 按条件删除
来源：http://dali.jianghu66.top/Article/details/gt2ewhgqgav.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gzhubu.top/Article/details/gt2omosfhcc.html

[Q54] 清空表
来源：http://dali.yuanzhike.top/Article/details/gt2hllojzia.html

TRUNCATE TABLE logs;
来源：http://dali.zhengqikj.top/Article/details/gt2hadyhnas.html

[Q55] 排名（并列占位）
来源：http://dali.cdnleiting.top/Article/details/gt2tiyjdgei.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2loyrgrza.html

[Q56] 密集排名（并列不占位）
来源：http://dali.aizwys.cn/Article/details/gt2xecolcuy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gt2duxraamn.html

[Q57] 行号
来源：http://dali.yangfankeji.com/Article/details/gt2azswcipo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj202588.top/Article/details/gt2skvxkddh.html

[Q58] 累计求和
来源：http://dali.redwolf501.top/Article/details/gt2mfgncfcx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.pycfn.com/Article/details/gt2kjtjnotl.html

[Q59] 分组内累计
来源：http://dali.yuanzhike.top/Article/details/gt2yufppphn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gt2ndfbypnq.html

[Q60] 取上一行 / 下一行
来源：http://dali.jqgufenzy.top/Article/details/gt2ijpivtbd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tian-w.cn/Article/details/gt2ilgcphtw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gt2xgsebypf.html

[Q61] 移动平均
来源：http://dali.hongshengwenyu.top/Article/details/gt2rplpljkv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2eiggexue.html

[Q62] 分组占比
来源：http://dali.cashguo.top/Article/details/gt2fzhtygob.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tfovnpro.html

[Q63] 开启事务
来源：http://dali.sysykeji.top/Article/details/gt2tvcpvmaj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.quarkkingdee.top/Article/details/gt2zqejhcth.html

[Q64] 提交事务
来源：http://dali.cqqwz.cn/Article/details/gt2vhxjoubr.html

COMMIT;
来源：http://dali.zhengqikj.top/Article/details/gt2mnwqblin.html

[Q65] 回滚事务
来源：http://dali.shuidangran.top/Article/details/gt2pacjzlcl.html

ROLLBACK;
来源：http://dali.hysaishi.cn/Article/details/gt2venfazlh.html

[Q66] 行锁查询
来源：http://dali.yuxming.cn/Article/details/gt2fahpnpcp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nanxuanxn.top/Article/details/gt2xtlmyodg.html

[Q67] 设置隔离级别
来源：http://dali.dianchejie.cn/Article/details/gt2uljgldbm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhixingplan.top/Article/details/gt2scdfnbme.html

[Q68] 保存点
来源：http://dali.zhoulong.xyz/Article/details/gt2buwiiedd.html

SAVEPOINT sp1;
来源：http://dali.sweek.top/Article/details/gt2vhzmvilo.html

ROLLBACK TO sp1;
来源：http://dali.havefunace.top/Article/details/gt2rrchueyg.html

[Q69] 查看执行计划
来源：http://dali.yuanzhike.top/Article/details/gt2kpswdnuj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qvjdqbmv.html

[Q70] 更新统计信息
来源：http://dali.hnxiangtu.top/Article/details/gt2paqvwroz.html

ANALYZE TABLE users;
来源：http://dali.havefunace.top/Article/details/gt2qgnllbgn.html

[Q71] 查看建表语句
来源：http://dali.ydzc1.top/Article/details/gt2zkrcftlc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daria6918.cn/Article/details/gt2tnijrzzy.html

[Q72] 查看索引
来源：http://dali.yonumen.top/Article/details/gt2eshptzqv.html

SHOW INDEX FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2kfpbsfgj.html

[Q73] 查看表状态
来源：http://dali.hongshengwenyu.top/Article/details/gt2dkpoycxb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ppjwa.cn/Article/details/gt2exekmamm.html

[Q74] 强制使用索引
来源：http://dali.quarkkingdee.top/Article/details/gt2sreavshk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhixingplan.top/Article/details/gt2kndhqfbf.html

[Q75] 日期格式化
来源：http://dali.hammf.cn/Article/details/gt2erqsdmrs.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2hhdadjkk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.c1oappe.top/Article/details/gt2xiqlhnji.html

[Q76] 按天统计
来源：http://dali.nwbrower.top/Article/details/gt2mwvbewzq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gotoacloud.top/Article/details/gt2sdybcmxh.html

[Q77] 时间加减
来源：http://dali.zdqjudy.top/Article/details/gt2quaiiruz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jqgfzy.top/Article/details/gt2eqnwumyv.html

[Q78] 当前时间
来源：http://dali.9152youxi.cn/Article/details/gt2bgmhwlic.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxinkj.top/Article/details/gt2hvmdpcha.html

[Q79] 字符串拼接
来源：http://dali.jinqigufen.top/Article/details/gt2zuwbvvdk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yuanzhike.top/Article/details/gt2nkbuzopb.html

[Q80] 字符串截取
来源：http://dali.daria6918.cn/Article/details/gt2qgobdojo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.meibo888.top/Article/details/gt2jzeeywgt.html

[Q81] 字符串替换
来源：http://dali.zhoulong.xyz/Article/details/gt2ywvgmbkl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2ktqwthox.html

[Q82] 字符长度与字节长度
来源：http://dali.nanxinkj.top/Article/details/gt2ahuuaazk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2zhsinwlf.html

[Q83] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gt2jzpifjta.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2nsflsdao.html

[Q84] 去除首尾空格
来源：http://dali.tian-w.cn/Article/details/gt2toxupvzr.html

SELECT TRIM(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2nikzdqjo.html

[Q85] 数值取整
来源：http://dali.ydzc1.top/Article/details/gt2amioskao.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.fzhhl.top/Article/details/gt2nieifbni.html

[Q86] 读取 JSON 字段
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sprhaaxn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hfpthk.cn/Article/details/gt2lktootat.html

[Q87] JSON 字段做条件
来源：http://dali.guannengcc.top/Article/details/gt2bpgfihky.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.316326.xyz/Article/details/gt2bldyview.html

[Q88] 行转列（条件聚合）
来源：http://dali.0kj1m.cn/Article/details/gt2lfclovmr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenlongwang.top/Article/details/gt2bmniyyro.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2wgidifzs.html

[Q89] 判断表是否存在
来源：http://dali.svipenyu.cn/Article/details/gt2ziqyomkw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cdnleiting.top/Article/details/gt2jihtonru.html

[Q90] 生成序号列
来源：http://dali.sysykeji.top/Article/details/gt2ifwpgfqp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gaohongyu789.top/Article/details/gt2iyhocomm.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2isptpvzr.html

R. Bash 专题
来源：http://dali.xinyue.icu/Article/details/gt2pkvsntca.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2gfponmgu.html

[R01] shebang 与严格模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rrcqdziz.html

#!/usr/bin/env bash
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uooujrbj.html

set -euo pipefail
来源：http://dali.hfpthk.cn/Article/details/gt2csqflsye.html

[R02] 变量赋值与使用
来源：http://dali.zhiwuduotai.top/Article/details/gt2sauvjbxv.html

name="Tom"; echo "$name"
来源：http://dali.yonumen.top/Article/details/gt2axtylikh.html

[R03] 只读变量
来源：http://dali.sxryk.cn/Article/details/gt2vtmhueov.html

readonly PI=3.14
来源：http://dali.jiagoushi.top/Article/details/gt2ediyatic.html

[R04] 位置参数
来源：http://dali.jqgufenzy.top/Article/details/gt2lihrfiay.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gotoacloud.top/Article/details/gt2vmwcicce.html

[R05] 参数默认值
来源：http://dali.xinyue.icu/Article/details/gt2ieozjldb.html

name="${1:-default}"
来源：http://dali.ppjwa.cn/Article/details/gt2haqafdys.html

[R06] 判断命令是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gt2jnxhbwlg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gt2tufqcaiw.html

[R07] if 判断文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2rkzgxspe.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigfzy.top/Article/details/gt2cejkahbq.html

[R08] 数值比较
来源：http://dali.hammf.cn/Article/details/gt2gccsthjp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.bjfxy.top/Article/details/gt2kcpcwkuh.html

[R09] 字符串比较
来源：http://dali.haohaochexian.top/Article/details/gt2ujttxdja.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.aibaodan.cn/Article/details/gt2eaydjgrp.html

[R10] 正则匹配
来源：http://dali.ydzc1.top/Article/details/gt2dkjyzbrt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jianghu66.top/Article/details/gt2qzmenxhz.html

[R11] case 多分支
来源：http://dali.vqdsnc.cn/Article/details/gt2hoduoann.html

case "$1" in
来源：http://dali.chenzaomai.com/Article/details/gt2ivnclffb.html

start) echo "启动" ;;
来源：http://dali.zhoulong.xyz/Article/details/gt2geftkkrc.html

stop)  echo "停止" ;;
来源：http://dali.quarkkingdee.top/Article/details/gt2okvpimkj.html

*)     echo "未知命令" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ckmacdim.html

esac
来源：http://dali.tian-w.cn/Article/details/gt2mprgjcto.html

[R12] for 遍历文件
来源：http://dali.gogol.net.cn/Article/details/gt2yhxkjjbp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2vhxnvqnr.html

[R13] for 计数循环
来源：http://dali.ydzc1.top/Article/details/gt2enuuzeeb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2wsnrncpq.html

[R14] C 风格 for
来源：http://dali.sxryk.cn/Article/details/gt2mswtqbdl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fzhhl.top/Article/details/gt2shmaqpme.html

[R15] while 逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gt2avuucjwm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenzaomai.com/Article/details/gt2jhegvlgv.html

[R16] until 等待条件
来源：http://dali.hysaishi.cn/Article/details/gt2efimwcbg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gt2zuqgjvsf.html

[R17] 数组定义与取值
来源：http://dali.meibo888.top/Article/details/gt2xnmfeyqg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2bynzttti.html

[R18] 遍历数组
来源：http://dali.cucudq.cn/Article/details/gt2agjogomh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gogol.net.cn/Article/details/gt2ftxtovtl.html

[R19] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gt2fwszjgwl.html

echo "${#arr[@]}"
来源：http://dali.gzhubu.top/Article/details/gt2aumwstcj.html

[R20] 关联数组（字典）
来源：http://dali.daxiang520.top/Article/details/gt2gdseykga.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ehwqpu.com/Article/details/gt2esntijsj.html

[R21] 字符串长度
来源：http://dali.yj20258888.top/Article/details/gt2attksgvg.html

echo "${#s}"
来源：http://dali.nanxinkj.top/Article/details/gt2ipskcnpy.html

[R22] 截取子串
来源：http://dali.redwolf501.top/Article/details/gt2tjcmvxzk.html

echo "${s:0:5}"
来源：http://dali.jinqigfzy.top/Article/details/gt2kssrdamm.html

[R23] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gt2rwpzaljz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.smart0.xyz/Article/details/gt2focgjwfr.html

[R24] 大小写转换
来源：http://dali.mhx1999.top/Article/details/gt2aurahdvy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sufxvd.cn/Article/details/gt2aplbjveq.html

[R25] 去后缀 / 去前缀
来源：http://dali.ybcxt.top/Article/details/gt2obauxosy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnqzz.top/Article/details/gt2qceztkyx.html

[R26] 命令替换
来源：http://dali.9152youxi.cn/Article/details/gt2aylwskfr.html

now=$(date +%F); echo "$now"
来源：http://dali.nwbrower.top/Article/details/gt2pfrrodjp.html

[R27] 算术展开
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vomwmcuo.html

echo $((1 + 2 * 3))
来源：http://dali.pycfn.com/Article/details/gt2umpfbxwn.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2efbjnxpm.html

echo "scale=2; 10/3" | bc
来源：http://dali.pycfn.com/Article/details/gt2kplgmhye.html

[R29] 定义函数
来源：http://dali.cqqwz.cn/Article/details/gt2xjrwrzvv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yangfankeji.com/Article/details/gt2aufmvtji.html

[R30] 函数返回状态码
来源：http://dali.sufxvd.cn/Article/details/gt2qzrpkxrf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.birdmap.top/Article/details/gt2ncrniadg.html

[R31] 局部变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2nnxxkmvk.html

f() { local x=1; echo "$x"; }
来源：http://dali.fzhhl.top/Article/details/gt2gzimgogf.html

[R32] 参数个数校验
来源：http://dali.cqqwz.cn/Article/details/gt2xmnbmltz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gt2qsscextb.html

[R33] 捕获错误并提示行号
来源：http://dali.xziqi.cn/Article/details/gt2dcgiaoep.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nwbrower.top/Article/details/gt2vaawykmk.html

[R34] 退出时清理
来源：http://dali.cheryme.top/Article/details/gt2mslmogig.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xziqi.cn/Article/details/gt2gkdzzefj.html

[R35] 后台执行并等待
来源：http://dali.jinqigufen.top/Article/details/gt2weaznrqb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tmntapcw.html

[R36] 并发执行多个任务
来源：http://dali.ehwqpu.com/Article/details/gt2jnuusqzq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.guowangkeji.top/Article/details/gt2etvzybgr.html

[R37] 把输出赋给变量
来源：http://dali.yonumen.top/Article/details/gt2heoxirbg.html

files=$(ls -1)
来源：http://dali.hammf.cn/Article/details/gt2mlmnocmh.html

[R38] 管道串联
来源：http://dali.gzhubu.top/Article/details/gt2wwmdgxic.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daria6918.cn/Article/details/gt2fbbadlhk.html

[R39] 重定向标准输出与错误
来源：http://dali.jiagoushi.top/Article/details/gt2ewznufba.html

cmd > out.log 2>&1
来源：http://dali.ivvv.top/Article/details/gt2gzglmxul.html

[R40] 追加写日志
来源：http://dali.yvedp.cn/Article/details/gt2bsgqeekf.html

echo "log" >> out.log
来源：http://dali.xinyue.icu/Article/details/gt2ikhmwzvh.html

[R41] 丢弃输出
来源：http://dali.jianghu66.top/Article/details/gt2pdlkfsxr.html

cmd >/dev/null 2>&1
来源：http://dali.0kj1m.cn/Article/details/gt2kystiosc.html

[R42] 输入重定向
来源：http://dali.hongshengwenyu.top/Article/details/gt2qoeyylcn.html

wc -l < a.txt
来源：http://dali.hammf.cn/Article/details/gt2ovlvfcrj.html

[R43] 按名字查找文件
来源：http://dali.vqdsnc.cn/Article/details/gt2xgqtnons.html

find . -name "*.log" -type f
来源：http://dali.hnxiangtu.top/Article/details/gt2xtglgosf.html

[R44] 按修改时间查找
来源：http://dali.pengpengdd.cyou/Article/details/gt2bkqdjekf.html

find . -mtime -7 -type f
来源：http://dali.wangdashe.top/Article/details/gt2vooskfkp.html

[R45] 批量删除
来源：http://dali.yangfankeji.com/Article/details/gt2iibkxwxn.html

find . -name "*.tmp" -delete
来源：http://dali.quarkkingdee.top/Article/details/gt2gdnwlouo.html

[R46] 递归替换文件内容
来源：http://dali.sysykeji.top/Article/details/gt2twyusnni.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258.top/Article/details/gt2tylhjdar.html

[R47] sed 单行替换
来源：http://dali.yueranfly.top/Article/details/gt2rnkklwrj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2axgvnkdu.html

[R48] awk 取指定列
来源：http://dali.hywenlv.cn/Article/details/gt2mqujxnjj.html

awk '{print $1, $3}' a.txt
来源：http://dali.ybcxt.top/Article/details/gt2hqivbepa.html

[R49] awk 带条件
来源：http://dali.xinyue.icu/Article/details/gt2tosyloez.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ydzc1.top/Article/details/gt2emcoiedf.html

[R50] awk 求和
来源：http://dali.gotoacloud.top/Article/details/gt2pijcmnlw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj20258888.top/Article/details/gt2noynhjzx.html

[R51] 排序去重取前几
来源：http://dali.0kj1m.cn/Article/details/gt2vvbtzmsp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuanzhike.top/Article/details/gt2mggmuyfq.html

[R52] 统计行数
来源：http://dali.ehwqpu.com/Article/details/gt2ctmmzdpg.html

wc -l a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2vepwukfe.html

[R53] 查看文件头与实时尾
来源：http://dali.wangshuangyany.cn/Article/details/gt2kmyqcttu.html


<!-- 参考信息 -->